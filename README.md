# niceweblist

**Web 出海开发者去哪里看好产品：实测过的信息源 + 收入经过验证的优秀案例。**

中文 | [English](README.en.md)

每天都有很多新的 Web 产品上线。问题不是信息太少，而是不知道去哪里看、看到的数字能不能信。这份清单里的每个信息源都实测过，标了怎么订阅、数据可不可信；案例区只收收入能核实的产品。

> 最后核实：2026-09 · 下次核实：2026-12

## 目录

- [5 分钟上手：推荐组合](#5-分钟上手推荐组合)
- [看新发布](#看新发布)
- [看谁在赚钱](#看谁在赚钱)
- [看流量和需求](#看流量和需求)
- [中文社区](#中文社区)
- [不推荐](#不推荐)
- [已停](#已停)
- [优秀案例](#优秀案例)
- [看榜单时要警惕的偏差](#看榜单时要警惕的偏差)
- [怎么实测的](#怎么实测的)

**数据可信度图例**

| 标记 | 含义 |
|---|---|
| 🟢 | 收入经支付商 API 验证 |
| 🔵 | 部分验证，或者是第三方估算 |
| ⚪ | 只有热度（票数、评论、访问量），和收入无关 |
| 🟠 | 收入是创始人自己报的，不可信 |

## 5 分钟上手：推荐组合

**每天（5–10 分钟）**

1. [TrustMRR](https://trustmrr.com/recent) 新加入的产品：看到一个产品的同时，就知道它有没有人付钱。
2. [Show HN](https://hnrss.org/show?points=50) 过去 24 小时分数最高的几个。
3. [Product Hunt](https://www.producthunt.com/) 或它的中文版 [DecoHack](https://decohack.com/)：扫一眼今天的题材。
4. [V2EX 分享创造](https://www.v2ex.com/go/create)：看国内同行在做什么。

**每周（30 分钟）**

- TrustMRR 首页排行榜、分类页和 [/stats](https://trustmrr.com/stats)：看哪些类目的收入中位数高。
- Reddit r/SaaS、r/SideProject 的 top/week。
- [Microns](https://www.microns.io/) 和 TrustMRR 的在售列表：看小产品的收入和售价倍数。
- 从这周看到的产品里挑 1–2 个，用 Similarweb 和 Google Trends 核对流量与需求。

## 看新发布

| 名称 | 看什么 | 更新频率 | 怎么订阅 | 数据可信度 | 最后核实 |
|---|---|---|---|---|---|
| [Product Hunt](https://www.producthunt.com/) | 每天的新品和热度 | 每天 | [RSS](https://www.producthunt.com/feed)，可以按分类订阅，如 `/feed?category=developer-tools` | ⚪ 刷票、互投群常见，大公司会占榜位；RSS 不带票数 | 2026-09 |
| [Show HN](https://news.ycombinator.com/show) | 技术圈的新作品和真实反馈 | 实时 | [hnrss.org/show?points=50](https://hnrss.org/show?points=50)；也可以用 [Algolia API](https://hn.algolia.com/api) 一次拿到分数和评论数 | ⚪ 比 PH 难刷，评论质量高；大部分帖子只有个位数分数，偏开发者工具 | 2026-09 |
| [BetaList](https://betalist.com/) | 还没正式上线的早期产品 | 每天 | [RSS](https://feeds.feedburner.com/BetaList) | ⚪ 付费可以插队 | 2026-09 |
| [Uneed](https://www.uneed.best/) | 新品日榜 | 每天 | 只能看网页 | ⚪ 榜首几十票，卖点是外链 | 2026-09 |
| [Fazier](https://fazier.com/) | 新品日榜 | 每天 | 只能看网页 | ⚪ 票数低，广告位多 | 2026-09 |
| [Microlaunch](https://microlaunch.net/) | 按月一批的新品 | 每月 | 只能看网页 | ⚪ 票数低 | 2026-09 |
| [TinyLaunch](https://www.tinylaunch.com/) | 新品周榜 | 每周 | 只能看网页 | ⚪ 榜首个位数票，卖点是外链 | 2026-09 |
| [Peerlist Launchpad](https://peerlist.io/launchpad) | 新品周榜 | 每周 | 只能用浏览器打开 | ⚪ 榜首个位数票 | 2026-09 |
| [DevHunt](https://devhunt.org/) | 只收开发者工具 | 每周 | 只能用浏览器打开 | ⚪ 票数低 | 2026-09 |
| [SaaSHub](https://www.saashub.com/) | 「XX 的替代品」目录，适合查竞品 | 每天 | 只能看网页 | ⚪ | 2026-09 |
| [GitHub Trending](https://github.com/trending?since=daily) | 开发者圈的热度 | 每天 | 网页；或 Search API 按 `created:>日期&sort=stars` 查 | ⚪ 偏 AI 和基础设施，离能赚钱的 Web 产品比较远 | 2026-09 |
| Reddit：[r/SideProject](https://www.reddit.com/r/SideProject/top/?t=week)、[r/SaaS](https://www.reddit.com/r/SaaS/top/?t=week)、[r/indiehackers](https://www.reddit.com/r/indiehackers/top/?t=week)、[r/microsaas](https://www.reddit.com/r/microsaas/top/?t=week) | 新作品，以及获客和定价的讨论 | 每天 | 建议每周手动看 top/week。`.json` 不登录会返回 403，RSS 连续请求会被限流，官方 API 要先申请 | 🟠 晒收入基本是截图 | 2026-09 |

发布平台（Uneed 到 DevHunt 这几个）的商业模式是卖外链和曝光，很多人提交产品是为了 SEO，票数又低。**适合扫题材，不适合判断产品行不行。**

## 看谁在赚钱

| 名称 | 看什么 | 更新频率 | 怎么订阅 | 数据可信度 | 最后核实 |
|---|---|---|---|---|---|
| **[TrustMRR](https://trustmrr.com/)** ★ | 按验证收入排序的产品榜：MRR、30 天收入、增长、是否在售 | 每天 | 网页：[最新加入](https://trustmrr.com/recent)、[统计](https://trustmrr.com/stats)；公开 JSON `trustmrr.com/api/ai/discovery`，每天给出 25 个新加入和 25 个增长最快的产品；完整 API 要申请 key | 🟢 创始人提供支付商（Stripe、LemonSqueezy、Paddle、Polar、Creem 等）的只读 API key，收入由平台自己算 | 2026-09 |
| [Microns](https://www.microns.io/) | 在售小产品的年收入和要价 | 每天 | 只能看网页 | 🔵 首页写着 Verified metrics | 2026-09 |
| [Acquire.com](https://acquire.com/) | 在售的 SaaS 和网站 | 每天 | 看详情要注册买家账号 | 🔵 平台宣称做验证，具体方式未核实 | 2026-09 |
| [Flippa](https://flippa.com/search) | 在售的网站和 SaaS | 每天 | 列表公开，API 要授权 | 🔵 部分挂牌接了 Stripe / GA 验证 | 2026-09 |
| [Starter Story](https://www.starterstory.com/) | 3,000+ 个带收入的创业案例访谈 | 不定期 | 网页，部分内容付费 | 🟠 收入是采访时自述 | 2026-09 |
| [Indie Hackers 产品库](https://www.indiehackers.com/products) | 创始人的故事和访谈 | 不定期 | 只能看网页 | 🟠 标注为 self-reported revenue，榜单里有明显乱填的数字 | 2026-09 |
| X / Twitter `#buildinpublic` | 创始人公开的 MRR 和增长过程 | 实时 | 搜 `"MRR" #buildinpublic` | 🟠 截图可以伪造 | 2026-09 |

- **TrustMRR 的局限**：只有愿意公开的人才会接入，待售产品比例高；「增长最快」多是小基数算出来的百分比，一定要同时看绝对金额；收入不等于利润。它的条款禁止拿数据克隆产品或批量转载。
- **交易市场的偏差**：来挂牌的往往是增长停了、或者创始人不想做了的产品。好处是能看到「多少收入能卖多少钱」。

## 看流量和需求

| 名称 | 看什么 | 更新频率 | 怎么订阅 | 数据可信度 | 最后核实 |
|---|---|---|---|---|---|
| [There's An AI For That](https://theresanaiforthat.com/) | AI 新工具，带访问量和收藏数 | 每小时 | 只能用浏览器打开 | ⚪ 付费可以买曝光 | 2026-09 |
| [Toolify](https://www.toolify.ai/) | 30,000+ 个 AI 工具，Just launched 每天更新 | 每天 | 只能用浏览器打开 | ⚪ 它的 Revenue 榜其实是「用了哪家支付 + 估算流量」，不是收入，而且被大公司占满 | 2026-09 |
| [Similarweb](https://www.similarweb.com/) | 单个网站的流量估算 | 按需查 | 网页免费查少量，API 付费 | 🔵 第三方估算，适合查单个竞品 | 2026-09 |
| [Google Trends](https://trends.google.com/) | 某个需求是不是正在升温 | 实时 | 网页 | 🔵 相对热度，不是绝对值 | 2026-09 |

## 中文社区

| 名称 | 看什么 | 更新频率 | 怎么订阅 | 数据可信度 | 最后核实 |
|---|---|---|---|---|---|
| [V2EX 分享创造](https://www.v2ex.com/go/create) | 国内独立开发者发的新作品 | 每天 | [RSS](https://www.v2ex.com/feed/create.xml)（网页版常被 Cloudflare 拦，RSS 能用） | ⚪ 噪音低，最适合看国内同行 | 2026-09 |
| [DecoHack](https://decohack.com/) | Product Hunt 每日热榜的中文版 | 每天 | [RSS](https://decohack.com/feed/) | ⚪ 同 PH；只能看它选了什么，没有原始票数 | 2026-09 |
| [独立开发前线](https://indiefront.cn/) | 国内独立产品收录 | 不定期 | 只能看网页 | ⚪ 规模小，约 84 款 | 2026-09 |
| [w2solo 产品出海节点](https://w2solo.com/topics/node44) | 出海相关讨论 | 更新慢 | 只能看网页 | ⚪ | 2026-09 |
| [出海.tools](https://www.chuhai.tools/)、[Indie Hacker Tools](https://indiehackertools.net/) | 出海工具和渠道合集 | 不定期 | 只能看网页 | — 不是产品流，当工具箱查 | 2026-09 |

## 不推荐

| 做法 | 为什么不推荐 |
|---|---|
| 在 [PublicWWW](https://publicwww.com/) 搜 `buy.stripe.com`，找挂了支付链接的网站 | 能搜出约 6.3 万个页面，但排在前面的是媒体和开源项目的捐赠链接。正经 SaaS 大多用动态生成的 Checkout，源码里搜不到。只能知道「能收钱」，不知道「收了多少」。导出要付费 |
| [BuiltWith](https://trends.builtwith.com/payment/Stripe) 的 Stripe 网站列表 | 付费，而且同样只知道「用了 Stripe」 |
| 每天看新注册域名（如 [whoisds](https://www.whoisds.com/newly-registered-domains)） | 每天几十万个，几乎全是噪音 |
| Chrome Web Store 按最新排序 | `sortBy=newest` 实测没有生效，也没有官方的「新扩展」接口 |
| 每天刷完所有发布平台 | 票数太低，大家为外链而来，还会互相投票 |
| 相信 Indie Hackers 或 X 上的收入数字 | 都是自己报的。Indie Hackers 上有人自报月入 $102 万 |

## 已停

| 名称 | 状态 |
|---|---|
| [Open Startup](https://openstartup.tm/) | 页面显示 paused，会跳转到 PayRequest |
| [Open Startup List](https://openstartuplist.com/) | 已被收购，列的还是老案例，基本不更新 |
| Baremetrics Open Startups | 现在主要是营销页 |
| Indie Hackers 的 Stripe 验证徽章 | 产品页上已找不到 verified 标记，这个功能还在不在未核实 |

「Open Startup」这件事，现在基本集中到了 TrustMRR 上。

## 优秀案例

**入选标准**

- 必须有能核实的收入信号。目前全部来自 TrustMRR 的支付商验证数据。
- **可复制的小产品**：MRR 约 $1k–$50k，团队 ≤5 人、没有融资。
- **标杆**：独立开发者起家、后来做大了的产品，最多 3 个。
- 在售的产品也收，会标出来。
- 收入写约数和数据日期。数字每天在变，以来源页面为准。团队规模多是创始人自填，TrustMRR 没有验证。

想推荐案例？请[提交 Issue](https://github.com/yifengingit/niceweblist/issues/new?template=case.yml)，必须附上收入信号的链接。

### 可复制的小产品

#### [VectoSolve](https://vectosolve.com/)

设计工具 · 约 $1.7k MRR（[TrustMRR 验证](https://trustmrr.com/startup/vectosolve)，2026-09）· 1 人 · 在售

**是什么**：把 PNG / JPG 转成 SVG 矢量图，并能导出切割机、激光雕刻机和刺绣机要用的格式（DXF、G-code、DST 等）。

**值得学什么**：图片转矢量是个老需求，它没有做成通用工具，而是只盯住 Cricut、激光、刺绣这些手作用户要的格式。获客渠道只有 SEO 和博客；免费出带水印的预览，付费是 $6.99 起的积分包或 $7.99/月起的订阅。

发现于：[TrustMRR](#看谁在赚钱) · 最后核实：2026-09

#### [Animalo](https://animalo.com/)

垂直 SaaS · 约 $1.1k MRR（[TrustMRR 验证](https://trustmrr.com/startup/animalo)，2026-09）· 1 人 · 在售

**是什么**：给宠物寄养、日托、美容、训练商家用的管理软件，包括预约、排班、开票和收款。

**值得学什么**：一个非 AI 的小众行业软件。16 个付费客户撑起约 $1k MRR，平均每个客户约 $68/月。做 B2B 行业软件不需要很多客户，需要的是找准一个没人好好服务的行业。

发现于：[TrustMRR](#看谁在赚钱) · 最后核实：2026-09

#### [Publbee](https://www.publbee.com/)

内容创作工具 · 约 $3k MRR（[TrustMRR 验证](https://trustmrr.com/startup/publbee)，2026-09）· 2–5 人 · 在售

**是什么**：给亚马逊 KDP 自出版作者用的工具，覆盖选题研究、关键词优化和 AI 辅助写作。

**值得学什么**：围绕一个平台上的卖家做工具。KDP 作者本身就在靠这个平台赚钱，愿意为能帮他们多卖书的工具付费。定价分四档：免费、$29.99、$58.99、$116.99/月。

发现于：[TrustMRR](#看谁在赚钱) · 最后核实：2026-09

#### [TapeSearch](https://www.tapesearch.com/)

搜索工具 · 约 $4.3k MRR，累计约 $9.2 万（[TrustMRR 验证](https://trustmrr.com/startup/tapesearch)，2026-09）· 1 人 · 未出售

**是什么**：播客逐字稿搜索引擎。用 AI 把播客转成带时间戳的文字，可以全文搜索、设关键词提醒、看话题趋势，也提供 API。

**值得学什么**：数据本身就是获客渠道。它给约 500 万期节目各生成一个公开页面，页面上有摘要和逐字稿开头，看全文要登录；这些页面全部写进 sitemap 交给搜索引擎。付费的是市场研究、金融分析、记者这些要从播客里找信息的人，定价 $16.66 / $31 / $60 每月（年付折算），最贵的一档卖 API。创始人在 X 上只有几百个粉丝，不靠个人影响力；过去 12 个月每月收入都在 $3.7k–$5k 之间，没有爆发，但做了近 4 年一直稳定。

发现于：[TrustMRR](#看谁在赚钱) · 最后核实：2026-09

#### [Data Bloo](https://www.databloo.com/)

数据分析 · 约 $6.1k MRR，累计约 $65 万（[TrustMRR 验证](https://trustmrr.com/startup/data-bloo)，2026-09）· 1 人（据公开资料）· 未出售

**是什么**：Google Looker Studio 的报表模板和数据连接器，面向营销人员、代理商和电商。

**值得学什么**：寄生在 Google 免费的 Looker Studio 上。模板免费，还上了 Google 官方的模板库，用来拉流量；真正收钱的是把各平台数据接进报表的连接器，按年订阅（$99.99–$399.99/年）。做了 5 年，累计约 $65 万。

发现于：[TrustMRR](#看谁在赚钱) · 最后核实：2026-09

#### [SuperX](https://superx.so/)

社交媒体工具 · 约 $20k MRR（[TrustMRR 验证](https://trustmrr.com/startup/superx)，2026-09）· 3 位联合创始人 · 未出售

**是什么**：X（Twitter）的写作和涨粉工具，包括 AI 写作、定时发布、互动和数据分析。

**值得学什么**：产品服务的平台，就是它的获客渠道。做 X 运营工具的人自己在 X 上有粉丝（联合创始人之一 Rob Hallam 约 6 万粉），用户在 X 上天天看到他们。上线约一年做到约 $20k MRR，定价 $49 / $99 / $199 每月。

发现于：[TrustMRR](#看谁在赚钱) · 最后核实：2026-09

### 标杆

> 注意：这两个产品的创始人 Marc Lou 同时也是 TrustMRR 的运营者。

#### [DataFast](https://datafa.st/)

网站分析 · 约 $31k MRR，1,400+ 个付费订阅（[TrustMRR 验证](https://trustmrr.com/startup/datafast)，2026-09）· 1 人 · 未出售

**是什么**：以收入为核心的网站分析工具，能把收入归因到具体的营销渠道。

**值得学什么**：网站分析是 Google Analytics、Plausible 这些产品早就占满的赛道。它换了一个角度切进去：不只看访问量，而是回答「哪个渠道带来了收入」，这正好是独立开发者最关心的问题。$9/月起、14 天免费试用且不用绑卡，门槛很低，现在有 1,400+ 个付费订阅。要注意的是，创始人在 X 上有约 40 万粉丝，而这些粉丝本身就是目标用户，这份分发优势很难复制。

发现于：[TrustMRR](#看谁在赚钱) · 最后核实：2026-09

#### [ShipFast](https://shipfa.st/)

开发者工具 · 一次性买断，累计约 $127 万，近 12 个月约 $12 万（[TrustMRR 验证](https://trustmrr.com/startup/shipfast)，2026-09）· 1 人 · 未出售

**是什么**：Next.js 的 SaaS 模板（boilerplate），一次性付费购买。

**值得学什么**：卖「铲子」给想做 SaaS 的开发者，把每个项目都要重写的登录、支付、邮件、SEO 打包成模板。一次性买断（$199–$299），不收订阅，累计约 $127 万，说明开发者愿意为「省下几周时间」直接付钱。但近 12 个月只有约 $12 万，不到累计额的十分之一：一次性买断能很快回款，收入却不会自己持续，要不断找新买家。可以和同一个人后来做的订阅产品 DataFast 对照着看。

发现于：[TrustMRR](#看谁在赚钱) · 最后核实：2026-09

## 看榜单时要警惕的偏差

1. **幸存者偏差**：榜单只展示活下来、并且愿意公开的产品。TrustMRR 上 67.7% 的产品收入在 $1k 以下，这才是常态。
2. **自报收入不可信**：只有支付商 API 验证的数字才算硬数据，而且那也只是收入，不是利润。
3. **公开本身就是营销**：公开收入的人，很多是在卖课、卖模板，或者要卖掉产品本身。
4. **头部集中**：有流量的创始人做什么都更容易赚钱。照着做同一个产品，结果可能完全不一样。
5. **增长率陷阱**：「增长最快」多是小基数算出来的，+439,221% 这种数字没有意义，一定要同时看绝对金额。
6. **协同造势**：同一个名字同一天出现在 PH、HN、GitHub 热门和 TrustMRR 上的情况并不少见。只看单一榜单，容易被带偏。

## 怎么实测的

2026 年 9 月逐个用 `curl` 请求每个信息源，记录 HTTP 状态和订阅方式；curl 被拦截的，再用浏览器确认能不能打开。只有第三方说法、没法实测的，写明「未核实」。案例的收入数据来自 TrustMRR 的公开接口和产品页。每季度重新核实一次。

## 参与贡献

推荐新的信息源、报告失效链接、推荐案例，见 [CONTRIBUTING.md](CONTRIBUTING.md)。

## 维护者

由 [@puexip](https://x.com/puexip) 维护。

## 许可证

[CC BY 4.0](LICENSE)：可以自由转载和改编，请注明出处并链接回本仓库。
