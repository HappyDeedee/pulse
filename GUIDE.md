# 选站与接入指南

> Pulse 站内教程的浓缩版。详细版见每节链接，以站内为准。

## 中转站是什么

一句话：第三方开的接口转发站。你在站方充值，拿到一个接口地址（base_url）和一把 Key，把它填进 Claude Code、Codex 或自己的程序里；站方再把请求转到它手里的上游账号，按“官方价 × 分组倍率”从你的余额里扣费。

| 形态 | 你拿到什么 | 能接 Claude Code / Codex | 上游账号在谁手里 | 主要风险 |
| --- | --- | --- | --- | --- |
| 官方 API | 官方 Key，按量计费 | 能 | 你自己 | 地区与付款限制 |
| 中转站 | 站方 base_url + Key，按分组倍率扣费 | 能 | 站方 | 掺水降智、断供跑路、内容被看到 |
| 镜像站 | 仿官方的网页聊天界面 | 一般不能 | 站方 | 模型不透明、会员到期 |
| 拼车 | 共享的订阅账号 | 多数不能（网页额度） | 车主 | 违反条款、整车封号 |
| 公益站 | 免费或赠送额度的接口 | 能（多数是中转站） | 站方 | 额度和开放范围随时变化 |

最本质的一点：中转站能看到你发出的全部内容。不要把私钥、密码、生产凭据放进对话。

详细版：[中转站是什么](https://pulse.deedee.tech/learn/what-is-relay)

## 怎么挑

1. 看 7 天和 30 天两个窗口的可用率，都不低于 95% 才算达标。
2. 一个站不等于一条线路，认准站点域名、分组名、模型名三件套。
3. 真伪看统一标准实测结论，不看站方写的模型名；未测不等于通过。
4. 实付 = 官方价 × 分组倍率 ÷ 充值汇率，三个数缺一个都算不准；缓存读写另算。
5. 看跑路信号：运营主体、客服响应、账单明细、价格异常波动。
6. 不要大额充值，用多少充多少；正式用之前先小额跑一段时间。

详细版：[中转站评测怎么看](https://pulse.deedee.tech/learn/relay-ranking-guide) · [跑路前的可核实信号](https://pulse.deedee.tech/learn/relay-risk-signals) · [怎么判断掺水、降智、假模型](https://pulse.deedee.tech/learn/fake-model)

## 怎么接 Claude Code

1. 终端里临时设置两个变量：

```
export ANTHROPIC_BASE_URL=https://relay.example.com
export ANTHROPIC_AUTH_TOKEN=sk-你的中转站Key
```

2. 用 curl 发一条只要 1 个 token 的请求，确认地址和 Key 都对，再打开 Claude Code。
3. 验证通过后写进用户级 `~/.claude/settings.json` 的 env 块（Windows 是 `%USERPROFILE%\.claude\settings.json`）。
4. 启动后输入 `/status`，确认 base URL 显示你的中转地址、凭据已生效。

注意：Key 别写进项目里的 `.claude/settings.json`，那个文件会随仓库提交。凭据生效后，请求不再用 claude.ai 订阅额度，而是按站方分组倍率扣你的余额。

详细版：[Claude Code 怎么接入中转站](https://pulse.deedee.tech/learn/claude-code-setup) · [Codex 怎么接入中转站](https://pulse.deedee.tech/learn/codex-setup) · [Kiro 渠道怎么接](https://pulse.deedee.tech/learn/kiro-relay)

## 怎么核对计费

- 实付 = 官方价 × 分组倍率 ÷ 充值汇率。模型名和输入输出价格一起保存，方便之后复算。
- 缓存要确认本次是否命中、读写怎么收费，不能把假设命中率当成自己的实际折扣。
- 对账：站内账单明细 vs 自己记录的调用量；只显示余额少了多少、查不到明细的站要警惕。

详细版：[倍率怎么算、实付多少钱](https://pulse.deedee.tech/learn/rate) · [缓存是什么、对价格影响多大](https://pulse.deedee.tech/learn/cache-pricing)

## 用之前的五条底线

1. 用多少充多少，最大损失就是账户余额。
2. 给每个工具单独建 Key 并设置额度上限，不要一把 Key 用到底。
3. 不要把私钥、密码、生产凭据放进对话。
4. 看分组的 7 天和 30 天可用率，而不是只看今天能不能用。
5. 接好之后先跑一次检测，确认模型是真的再长期用。
