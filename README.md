# DeeDee Pulse · AI API 中转站实测榜

> 公开、免费、无需登录的中转站实测榜。收录 7,462 个站，监控 1,152 个站；805 个站、5,882 个分组有站方可用率；423 个站做过统一标准实测。数据截至 2026-11-24，随 Pulse 采集每天更新；榜单名单每月 1 日 09:00 固化。
>
> 在线榜单：[pulse.deedee.tech](https://pulse.deedee.tech) · [月榜 /best](https://pulse.deedee.tech/best) · [全部站点 /sites](https://pulse.deedee.tech/sites) · [自测 /probe](https://pulse.deedee.tech/probe) · [方法 /methodology](https://pulse.deedee.tech/methodology)

## 怎么挑一个靠谱的中转站

1. **先看稳不稳。** 只看今天能不能用不够。看 7 天和 30 天两个窗口的可用率，都不低于 95% 才算达标。收录站里有 7 天读数的 1,766 个分组，两个窗口都达标的只有 746 个（42.2%）。
2. **一个站不等于一条线路。** 同一家站有多个分组，榜单测的是其中一个分组，你买的可能是另一个。认准站点域名、分组名、模型名三件套，再去站内确认。
3. **真伪看实测，不看站方写的模型名。** 统一标准实测按模型族固定模型和思考档，结论分通过、降智、未通过、待复核、不符合标准。没测过的站是未测，不是通过也不是失败。
4. **价格先统一单位再比。** 实付 = 官方价 × 分组倍率 ÷ 充值汇率，三个数缺一个都算不准。缓存读写另算，别把假设命中率当成实际折扣。
5. **看跑路信号。** 运营主体、客服响应、账单明细、价格异常波动，都能提前看到。信号清单见站内《跑路前的可核实信号》。
6. **最重要的一句：不要大额充值。** 用多少充多少。这个行业变化快，榜单只能帮你缩小范围，正式用之前先小额跑一段时间。

完整版见站内教程：[中转站评测怎么看](https://pulse.deedee.tech/learn/relay-ranking-guide) · [中转站是什么](https://pulse.deedee.tech/learn/what-is-relay) · [倍率怎么算](https://pulse.deedee.tech/learn/rate) · [缓存怎么收费](https://pulse.deedee.tech/learn/cache-pricing)

## 2026 年 11 月推荐榜（GPT / Codex）

数据截至 2026-11-24 08:57（北京时间）。本月只有 6 个站同时满足入选条件，按实有数量列出，不补位。Codex 走 OpenAI Responses 协议，与 GPT 用同一套统一标准实测，所以 Codex 榜取 GPT 主榜。

| 名次 | 站点 | 最优分组 | 站方倍率 | 7 / 30 天可用率 | 实测结论与日期 | 综合分 |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [悦聚](https://pulse.deedee.tech/site/yangyue99.store) | GPT 不降智 | 0.12x | 97.8% / 98.0% | 通过（2026-10-22） | 92.9 |
| 2 | [NC API](https://pulse.deedee.tech/site/ncncapi.top) | GPT-Pro-正价 | 0.2x | 100.0% / 100.0% | 通过（2026-10-22） | 92.8 |
| 3 | [pulseaify.com](https://pulse.deedee.tech/site/pulseaify.com) | 【0.1x】ChatGPT【特惠不降智】 | 0.1x | 98.4% / 97.9% | 通过（2026-11-01） | 91.5 |
| 4 | [www.aisale.best](https://pulse.deedee.tech/site/www.aisale.best) | GPT 通用 | 0.18x | 99.2% / 99.2% | 通过（2026-10-29） | 91.4 |
| 5 | [www.ai2api.online](https://pulse.deedee.tech/site/www.ai2api.online) | pro | 0.18x | 98.9% / 98.6% | 通过（2026-11-15） | 90.7 |
| 6 | [ai.tokensfree.xyz](https://pulse.deedee.tech/site/ai.tokensfree.xyz) | Pro | 0.17x | 99.6% / 97.9% | 通过（2026-10-26） | 90.4 |

本月暂无入选：Claude Code、便宜 Claude、Gemini、Grok（没有站点同时满足实测、7 天与 30 天可用率达标、无警告和降智，按规则不补位）。

## 逐站说明

### 1. 悦聚

8 个分组。GPT「不降智」0.12x，7 天 97.8%、30 天 98.0%，实测通过（2026-10-22）。注意同一站的 Grok 分组有降智记录（2026-10-24），另有 1 个分组待复核；近 30 天可用率呈回升趋势，倍率 30 天内变动 3 次。认准 GPT 分组，别按站名一概而论。

### 2. NC API

12 个分组，12 个全部达标，是本月唯一全达标的站。GPT-Pro-正价 0.2x，7 天与 30 天都是 100.0%，实测通过（2026-10-22）；GPT-Max（不降智）也通过（2026-10-23）。30 天日均可用率 99.6%，波动最小。

### 3. pulseaify.com

10 个分组，有 7 天与 30 天数据的 9 个里 7 个达标。GPT「特惠不降智」0.1x，98.4% / 97.9%，实测通过（2026-11-01）；Claude kiro 分组 0.16x，99.8% / 99.5%。短板在 Gemini 分组：7 天 36.0%、30 天 43.5%，未达标。近 30 天倍率没有变动。

### 4. www.aisale.best

全站只有 2 个分组，都是 GPT，两个都达标。GPT 通用 0.18x，99.2% / 99.2%，实测通过（2026-10-29）；30 天日均 99.2%，最稳的站之一。只做 GPT，没有 Claude、Gemini、Grok 分组，要别的模型别找它。

### 5. www.ai2api.online

GPT pro 分组 0.18x，98.9% / 98.6%，实测通过（2026-11-15），是它上榜的理由。但同站 kiro-claude 分组未通过（2026-11-16），grok 分组降智（2026-11-15）；特惠分组 0.1x 只有 76.3% / 93.4%，未达标；近 7 天比前 7 天下滑，11 月 21 日特惠分组单日跌到 20%。只认 pro 分组，其他分组别碰。

### 6. ai.tokensfree.xyz

Pro 分组 0.17x，99.6% / 97.9%，实测通过（2026-10-26）。但便宜分组问题不少：Plus特惠 0.06x 只有 76.3% / 90.3% 且不符合标准，Plus分组未通过，Gemini 待复核；近 7 天也在下滑。便宜的分组别贪，只认 Pro。

## 按模型前三组（首页，2026-11-24 08:27）

每个模型族取前 3 组：先列「推荐」档，推荐不足时用「能用」档补位并如实标注。倍率为站方分组倍率，可用率为 7 / 30 天。

### Claude

- 能用：[chenshuapi.com](https://pulse.deedee.tech/site/chenshuapi.com) · Claude-官方0.2折，倍率 0.02x，7 天可用率 98.8%，30 天 97.9%
- 能用：[bya.re](https://pulse.deedee.tech/site/bya.re) · Claude Code【Kiro反代】，倍率 0.042x，7 天 99.5%，30 天 97.1%
- 能用：[cf.dzhsmartai.com](https://pulse.deedee.tech/site/cf.dzhsmartai.com) · Claude-kiro 稳定，倍率 0.06x，7 天 98.2%，30 天 97.0%

### GPT

- 推荐：[api.cenai.top](https://pulse.deedee.tech/site/api.cenai.top) · plus·team【性价比高】，倍率 0.065x，7 天 95.2%，30 天 98.2%
- 推荐：[sub.baiyuapi.xyz](https://pulse.deedee.tech/site/sub.baiyuapi.xyz) · gpt-低价（最高0.108），倍率 0.07x，7 天 99.3%，30 天 99.0%
- 推荐：[api.yunqing.asia](https://pulse.deedee.tech/site/api.yunqing.asia) · B组，倍率 0.1x，7 天 96.4%，30 天 97.0%

### Gemini

- 能用：[api.new.bi](https://pulse.deedee.tech/site/api.new.bi) · default，已实测通过，倍率 1.0x，7 天 96.9%，30 天 56.9%
- 能用：[worldcodes.online](https://pulse.deedee.tech/site/worldcodes.online) · Gemini 反重力，倍率 0.25x，7 天 92.0%，30 天 92.3%
- 能用：[linkapi.ai](https://pulse.deedee.tech/site/linkapi.ai) · geminicheap，倍率 0.5x，7 天 91.9%，30 天 97.6%

### Grok

- 推荐：[sub.baiyuapi.xyz](https://pulse.deedee.tech/site/sub.baiyuapi.xyz) · grok，倍率 0.2x，7 天 99.7%，30 天 99.6%
- 能用：[api.cenai.top](https://pulse.deedee.tech/site/api.cenai.top) · grok-官转（Openai协议）直连专线，已实测通过，倍率 0.3x，7 天 96.7%，30 天 95.2%
- 能用：[p.icodex.cc](https://pulse.deedee.tech/site/p.icodex.cc) · Grok，已实测通过，倍率 0.38x，7 天 98.1%，30 天 96.9%

## 红黑榜怎么读

- Pulse 的结论按分组给，不按整站给。同一家站，GPT 分组通过、Grok 分组降智是常事，上面逐站说明里就有两例。别把一个分组的结论扩大成整站。
- 未测不进黑榜。收录 7,462 个站里只有 423 个做过统一标准实测，其余站是证据不足，不是失败也不是通过。
- 本仓库只列推荐档与能用档。完整名单、待复核与不建议的分组见站内[全部站点](https://pulse.deedee.tech/sites)与各站详情页。
- 排名不接受付费，付费不改分。DeeDeeAI 为自营，不参与排名。

## 评分体系

- 综合分按六个维度加权：价格、可靠、真伪、智商、福利、计费诚信；具体权重以站内页面为准。计费诚信样本不足时不出分、不计入。
- 达标线：7 天与 30 天可用率均 ≥ 95%（7 天 336 次采样，最多失败 16 次；30 天 1440 次，最多失败 72 次）。
- 统一标准实测按模型族固定模型和思考档：Claude claude-opus-5-5 · xhigh；GPT gpt-6.1-sol · xhigh；Grok grok-4.7 · xhigh；Gemini gemini-4-argon · high。
- 实付倍率 = 分组倍率 ÷ 已核汇率。未核汇率不换算。缓存读写另算。
- 检测细则不公开，只给结论。主榜只收统一标准实测完整的分组。
- 详情见 [METHODOLOGY.md](METHODOLOGY.md)，以站内为准。

## 数据

- 本仓数据：[data/2026-11-ranking.json](data/2026-11-ranking.json)（月榜 + 按模型前三组）、[data/2026-11-ranking.csv](data/2026-11-ranking.csv)（月榜）。
- 数据每天随 Pulse 采集刷新；每月 1 日 09:00 固化当月名单。
- 规模（2026-11-24 07:27）：收录 7,462 个站，监控 1,152 个站；805 个站、5,882 个分组有站方可用率；约 2,070 个站由 Pulse 轮流自测；已实测 423 个站。

## 常见问题

- **榜单排得靠前就适合所有人吗？** 还要看你实际用的模型、分组和工具是否被同一标准覆盖，以及价格与可用率是否符合你的需要。
- **没有实测分数是不是代表不可靠？** 未测只表示缺少证据。应查看原因和已有公开资料，不能直接当成通过或失败。
- **能聊天就算完成评测了吗？** 普通对话只覆盖一部分。若工作依赖流式输出、工具调用或长上下文，还需要验证相应流程。
- **一次失败能否说明整个站有问题？** 先保留错误、时间与分组，核对客户端和请求条件，再看独立复测证据，避免把局部结果扩大。

## 本仓结构

```
pulse/
├── README.md                  # 本文档：指南 + 月榜 + 逐站说明 + 评分体系
├── GUIDE.md                   # 选站与接入指南：怎么挑、怎么接、怎么核对计费
├── METHODOLOGY.md             # 检测方法与数据口径
└── data/
    ├── 2026-11-ranking.json   # 月榜 + 按模型前三组
    └── 2026-11-ranking.csv    # 月榜
```

## 参与与纠错

- 数据有问题：到站内对应页面提交纠错，附链接、时间和最小复现步骤。
- 改本仓数据文件请附来源与日期。

## 注意

- 中转站是第三方转售，任何站都可能涨价、降智或停服。本榜不担保任何站。建议少量充值、按需续费。
- 本仓只发榜单和数据，不含检测代码。检测细则不公开，只给结论。
- 数据口径见 [METHODOLOGY.md](METHODOLOGY.md)，以站内为准。

License: MIT.
