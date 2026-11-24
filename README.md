# DeeDee Pulse · AI API 中转站实测榜

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Pulse](https://img.shields.io/badge/Pulse-deedee.tech-blue)](https://pulse.deedee.tech)
[![Data](https://img.shields.io/badge/Data-2026--11--24-green)](https://pulse.deedee.tech/best)

> 公开、免费、无需登录的中转站实测榜。收录 7,462 个站，监控 1,152 个站；805 个站、5,882 个分组有站方可用率；423 个站做过统一标准实测。数据截至 2026-11-24，随 Pulse 采集每天更新；榜单名单每月 1 日 09:00 固化。
>
> 在线榜单：[pulse.deedee.tech](https://pulse.deedee.tech) · [月榜 /best](https://pulse.deedee.tech/best) · [全部站点 /sites](https://pulse.deedee.tech/sites) · [自测 /probe](https://pulse.deedee.tech/probe) · [方法 /methodology](https://pulse.deedee.tech/methodology)

> ⭐ 如果这份榜单帮你避过坑，欢迎点个 Star。排名规则公开、数据可导出复核，付费不改分。

## 为什么做这个排行榜

站的状态变得很快，靠手工整理容易过期。Pulse 每天汇总站方公开监控，轮流对站做真伪与降智实测，榜单每月 1 日 09:00 冻结更新。榜单是挑站的参考，正式用之前先小额充值、自己测一遍。

这个榜只回答一个问题：钱充进去，模型是不是真的、稳不稳、扣费对不对。先看数据再充钱，小额试。

## 你关心什么，从这里开始

| 你关心什么 | 从这里开始 |
| --- | --- |
| 哪个站最稳 | [月榜 /best](https://pulse.deedee.tech/best) |
| 按模型挑（GPT / Claude / Gemini / Grok） | [按模型前三组](#按模型前三组首页2026-11-24-0827) · [完整 GPT 榜 /best/gpt](https://pulse.deedee.tech/best/gpt) |
| 查某个站 | [全部站点 /sites](https://pulse.deedee.tech/sites) |
| 自己测手上的 Key | [自测 /probe](https://pulse.deedee.tech/probe)（报告仅自己可见，Key 不保留） |
| 方法论 | [METHODOLOGY.md](METHODOLOGY.md) |

## 怎么挑一个靠谱的中转站

| 维度 | 要看什么 | 怎么判断 |
| --- | --- | --- |
| 稳不稳 | 7 天和 30 天两个窗口的可用率 | 都不低于 95% 才算达标。收录站里有 7 天读数的 1,766 个分组，两个窗口都达标的只有 746 个（42.2%）。伪 200、空回复、超时、流式中断都算失败；小样本的 100% 参考价值低 |
| 一个站不等于一条线路 | 同一家站有多个分组 | 榜单测的是其中一个分组，你买的可能是另一个。认准站点域名、分组名、模型名三件套，再去站内确认 |
| 真伪看实测 | 统一标准实测结论 | 不看站方写的模型名。结论分通过、降智、未通过、待复核、不符合标准。没测过的站是未测，不是通过也不是失败 |
| 价格先统一单位 | 实付 = 官方价 × 分组倍率 ÷ 充值汇率 | 三个数缺一个都算不准。缓存读写另算，别把假设命中率当成实际折扣 |
| 跑路信号 | 运营主体、客服响应、账单明细、价格异常波动 | 信号清单见站内《跑路前的可核实信号》 |
| 退款政策 | 站内页面是否写明 | 写明支持 / 有条件 / 需联系客服 / 未提供。没写清的按不可退处理 |
| 小额试用 | 最低档或赠送额度 | 先跑自己的真实任务再加量，别一上来就大额充值 |
| 不要大额充值 | 用多少充多少 | 这个行业变化快，榜单只能帮你缩小范围，正式用之前先小额跑一段时间 |

完整版见站内教程：[中转站评测怎么看](https://pulse.deedee.tech/learn/relay-ranking-guide) · [中转站是什么](https://pulse.deedee.tech/learn/what-is-relay) · [倍率怎么算](https://pulse.deedee.tech/learn/rate) · [缓存怎么收费](https://pulse.deedee.tech/learn/cache-pricing)

## 2026 年 11 月推荐榜（GPT / Codex）

> **不要大额充值，用多少充多少。**

数据截至 2026-11-24 08:57（北京时间）。本月只有 6 个站同时满足入选条件，按实有数量列出，不补位。Codex 走 OpenAI Responses 协议，与 GPT 用同一套统一标准实测，所以 Codex 榜取 GPT 主榜。

| 名次 | 站点 | 最优分组 | 站方倍率 | 7 / 30 天可用率 | 样本（7d / 30d） | 实测结论与日期 | 综合分 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | [悦聚](https://pulse.deedee.tech/site/yangyue99.store) | GPT 不降智 | 0.12x | 97.8% / 98.0% | 336 / 1440 | 通过（2026-10-22） | 92.9 |
| 2 | [NC API](https://pulse.deedee.tech/site/ncncapi.top) | GPT-Pro-正价 | 0.2x | 100.0% / 100.0% | 336 / 1440 | 通过（2026-10-22） | 92.8 |
| 3 | [pulseaify.com](https://pulse.deedee.tech/site/pulseaify.com) | ChatGPT | 0.1x | 98.4% / 97.9% | 336 / 1440 | 通过（2026-11-01） | 91.5 |
| 4 | [www.aisale.best](https://pulse.deedee.tech/site/www.aisale.best) | GPT 通用 | 0.18x | 99.2% / 99.2% | 336 / 1440 | 通过（2026-10-29） | 91.4 |
| 5 | [www.ai2api.online](https://pulse.deedee.tech/site/www.ai2api.online) | pro | 0.18x | 98.9% / 98.6% | 336 / 1440 | 通过（2026-11-15） | 90.7 |
| 6 | [ai.tokensfree.xyz](https://pulse.deedee.tech/site/ai.tokensfree.xyz) | Pro | 0.17x | 99.6% / 97.9% | 336 / 1440 | 通过（2026-10-26） | 90.4 |

数据截至 2026-11-24 08:57，窗口 7 天（336 样本）/ 30 天（1440 样本），方法版本见 [METHODOLOGY.md](METHODOLOGY.md)，数据文件 [data/2026-11-ranking.json](data/2026-11-ranking.json)。完整榜单 → [月榜 /best](https://pulse.deedee.tech/best)，按模型 → [完整 GPT 榜 /best/gpt](https://pulse.deedee.tech/best/gpt)。

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
- 能用：[bya.re](https://pulse.deedee.tech/site/bya.re) · Claude Code，倍率 0.042x，7 天 99.5%，30 天 97.1%
- 能用：[cf.dzhsmartai.com](https://pulse.deedee.tech/site/cf.dzhsmartai.com) · Claude-kiro 稳定，倍率 0.06x，7 天 98.2%，30 天 97.0%

### GPT（[完整 GPT 榜](https://pulse.deedee.tech/best/gpt)）

- 推荐：[api.cenai.top](https://pulse.deedee.tech/site/api.cenai.top) · plus·team，倍率 0.065x，7 天 95.2%，30 天 98.2%
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

## 中性

结论未定，不推荐也不否定，只列事实，等复测：

- 悦聚：1 个分组待复核（2026-11-24 站内状态）；Grok 分组降智记录（2026-10-24）后 30 天可用率回升，观察中。
- ai.tokensfree.xyz：Gemini 分组待复核（2026-11-24 站内状态）。

## 不推荐

只按分组点名，不按整站定罪。下面这些分组是已实测未通过或未达标，日期以站内页面为准。同一家站的其他分组仍可能在推荐档（悦聚 GPT、www.ai2api.online pro、ai.tokensfree.xyz Pro 都在 11 月榜上）。

- pulseaify.com · Gemini 分组：7 天 36.0%、30 天 43.5%，未达标（2026-11-24）。
- www.ai2api.online · 特惠分组 0.1x：76.3% / 93.4%，未达标；11 月 21 日单日跌到 20%（2026-11-24）。同站 kiro-claude 分组未通过（2026-11-16），grok 分组降智（2026-11-15）。
- ai.tokensfree.xyz · Plus特惠分组 0.06x：76.3% / 90.3%，不符合标准；Plus分组未通过（2026-11-24）。
- 悦聚 · Grok 分组：降智记录（2026-10-24），观察中。

## 需谨慎的标准

以下情况核实后会写进「不推荐」，按分组列出：

- 已确认的跑路、长期无法登录、无法提现退款。
- 有可复现证据的模型替换或降级（同一题目、同一分组、带时间戳）。
- 计费与日志明显不符且站点拒绝说明。
- 泄露用户 Key 或数据的安全事件。

目前没有点名任何整站；上面「不推荐」的都是按分组列的实测结论。有线索按标准核实后再写，见[参与与纠错](#参与与纠错)。

## 红黑榜怎么读

- Pulse 的结论按分组给，不按整站给。同一家站，GPT 分组通过、Grok 分组降智是常事，上面逐站说明里就有两例。别把一个分组的结论扩大成整站。
- 未测不进黑榜。收录 7,462 个站里只有 423 个做过统一标准实测，其余站是证据不足，不是失败也不是通过。
- 本仓库列推荐档、能用档、中性与不推荐。完整名单、待复核与不建议的分组见站内[全部站点](https://pulse.deedee.tech/sites)与各站详情页。
- 排名不接受付费，付费不改分。DeeDeeAI 为自营，不参与排名。

## 评分体系

```
推荐档 = 实测通过 且 7d ≥ 95% 且 30d ≥ 95% 且 无警告、无降智
7d：336 次采样，最多失败 16 次；30d：1440 次采样，最多失败 72 次
无 7 天读数的分组不进榜；站方无监控、由 Pulse 自测补足的分组，样本不少于 20 次
一票否决：分组实测未通过或降智，该分组直接排除，不参与月榜
```

实测评分四项权重：

| 维度 | 权重 |
| --- | --- |
| 真伪 | 35 |
| 降智与推理截断 | 20 |
| 能力答题 | 30 |
| 完整性 | 15 |

- 综合分另按六个维度加权：价格、可靠、真伪、智商、福利、计费诚信；具体权重以站内页面为准。计费诚信样本不足时不出分、不计入。
- 统一标准实测按模型族固定模型和思考档：Claude claude-opus-5-5 · xhigh；GPT gpt-6.1-sol · xhigh；Grok grok-4.7 · xhigh；Gemini gemini-4-argon · high。
- 实付倍率 = 分组倍率 ÷ 已核汇率。未核汇率不换算。缓存读写另算。
- 检测细则不公开，只给结论。主榜只收统一标准实测完整的分组。
- 详情见 [METHODOLOGY.md](METHODOLOGY.md)，以站内为准。

## 数据可验证

| 你想核对的数字 | 去哪里复核 |
| --- | --- |
| 某站分组可用率 | 站内 [/site/\<域名\>](https://pulse.deedee.tech/sites) 看 30 天趋势 |
| 实测通过及日期 | 同页实测结论 |
| 11 月榜单 | [data/2026-11-ranking.csv](data/2026-11-ranking.csv) |
| 权重与达标线 | [METHODOLOGY.md](METHODOLOGY.md) |

## 已知局限

- 可用率是站方自报监控的聚合，不是 Pulse 全量自测。
- 未测只是证据不足：7,462 个站里只有 423 个做过统一标准实测。
- 倍率是站方标价，实付还要折充值汇率。
- 榜单只给分组结论，不给整站背书。

## 数据

- 本仓数据：[data/2026-11-ranking.json](data/2026-11-ranking.json)（月榜 + 按模型前三组）、[data/2026-11-ranking.csv](data/2026-11-ranking.csv)（月榜）。
- 数据每天随 Pulse 采集刷新；每月 1 日 09:00 固化当月名单；本仓 data/ 随月榜同步，每月固化后归档在 data/ 下。
- 规模（2026-11-24 07:27）：收录 7,462 个站，监控 1,152 个站；805 个站、5,882 个分组有站方可用率；约 2,070 个站由 Pulse 轮流自测；已实测 423 个站。
- 引用：转载月榜数据请注明「DeeDee Pulse、月份（如 2026-11）与数据文件版本」。数据文件以 CC BY 4.0 许可。数据为月度快照，不含原始运行记录，不承诺可复算。

## 常见问题

- **为什么某站不在 11 月榜上？** 入选条件是实测通过 + 7 天与 30 天可用率都达标 + 无警告和降智。不满足或未测的都不进榜；完整名单见站内[全部站点](https://pulse.deedee.tech/sites)。
- **表格数据多久更新？** 站内每天随采集刷新，月榜每月 1 日 09:00 固化；本仓 data/ 随月榜同步；数据截至时间见表上方。
- **数据有错怎么提？** 到站内对应页面提交纠错，或在本仓提 Issue（附链接、时间、最小复现步骤，不要贴 API Key）。

选站方法类问题见站内教程：[中转站评测怎么看](https://pulse.deedee.tech/learn/relay-ranking-guide) · [中转站是什么](https://pulse.deedee.tech/learn/what-is-relay) · [倍率怎么算](https://pulse.deedee.tech/learn/rate) · [缓存怎么收费](https://pulse.deedee.tech/learn/cache-pricing)

## English quick guide

Pulse is a public, free ranking of AI API relay stations, tested against unified standards — no login required. Monthly picks, per-model top 3, and machine-readable data exports.

A relay station resells API access: you top up at the station, get a base_url and a Key, and point your tool (Claude Code, Codex, or your own app) at it. The station forwards your requests to its upstream account and charges you official price × group multiplier.

Checklist before you top up:

1. Check 7-day and 30-day availability — both should be ≥ 95%.
2. Judge by group, not by station — one station has many groups, and the ranking tests one group at a time.
3. Trust the test verdict, not the model name the station writes.
4. Compare prices in the same unit: what you actually pay = official price × group multiplier ÷ top-up exchange rate.
5. Start small. Top up only what you need; never park a large balance at any station.

Links: [monthly best](https://pulse.deedee.tech/best) · [test your own Key](https://pulse.deedee.tech/probe) · [methodology](METHODOLOGY.md)

## 本仓结构

```
pulse/
├── README.md # 本文档：指南 + 月榜 + 逐站说明 + 评分体系
├── GUIDE.md # 选站与接入指南：怎么挑、怎么接、怎么核对计费
├── METHODOLOGY.md # 检测方法与数据口径
├── CHANGELOG.md # 更新日志，版本按月份
├── CONTRIBUTING.md # 参与指南：欢迎的贡献与不在范围的内容
├──.github/
│ └── ISSUE_TEMPLATE/
│ ├── 数据纠错.md # 数据有错按这个模板提
│ └── 站长收录与踩坑报告.md # 申请收录或报告踩坑
└── data/
├── 2026-11-ranking.json # 月榜 + 按模型前三组
└── 2026-11-ranking.csv # 月榜
```

## 参与与纠错

- 数据有问题：到站内对应页面提交纠错，或在本仓提 Issue（[数据纠错](.github/ISSUE_TEMPLATE/数据纠错.md)），附链接、时间、最小复现步骤，不要贴任何站的 API Key。
- 站长投稿：想让你的站进入实测队列，到 [pulse.deedee.tech/probe](https://pulse.deedee.tech/probe) 自测一次，或在 Telegram 讨论群留站名与分组说明；通过初筛的进下月实测队列。收录免费，排名不接受付费。
- 踩坑报告：提 Issue（[站长收录与踩坑报告](.github/ISSUE_TEMPLATE/站长收录与踩坑报告.md)），写清时间、模型、分组，截图请打码。
- Telegram 频道：[t.me/deedeepulse](https://t.me/deedeepulse)（榜单更新）；讨论群：[t.me/deedeepulse_chat](https://t.me/deedeepulse_chat)。
- 改本仓数据文件请附来源与日期；想改文档见 [CONTRIBUTING.md](CONTRIBUTING.md)。

## 为什么可信

- 规则公开：[METHODOLOGY.md](METHODOLOGY.md) 写清实测标准、权重与达标线。
- 数据可导出复核：月榜数据在 [data/](data/)，引用格式见[数据](#数据)。
- DeeDeeAI 自营不参与排名。
- 付费不改分，Telegram 公开频道接受监督。

## 注意

- 中转站是第三方转售，任何站都可能涨价、降智或停服。本榜不担保任何站。建议少量充值、按需续费。
- 本仓只发榜单和数据，不含检测代码。检测细则不公开，只给结论。
- 官方入口：pulse.deedee.tech；Telegram 频道 t.me/deedeepulse。更新日期 2026-11-24。只认这两个入口，其他同名站点、群组与本榜无关。
- 数据口径见 [METHODOLOGY.md](METHODOLOGY.md)，以站内为准。

License: MIT.
