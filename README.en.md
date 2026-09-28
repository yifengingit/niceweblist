# niceweblist

**Where indie web makers find great products: tested sources + revenue-verified case studies.**

[中文](README.md) | English

New web products launch every day. The problem isn't a lack of information. It's knowing where to look and whether the numbers you see can be trusted. Every source in this list has been tested, with notes on how to follow it and how reliable its data is. The case study section only includes products whose revenue can be verified.

> Last verified: 2026-09 · Next check: 2026-12

## Contents

- [Start here: a 5-minute routine](#start-here-a-5-minute-routine)
- [New launches](#new-launches)
- [Who's actually making money](#whos-actually-making-money)
- [Traffic and demand](#traffic-and-demand)
- [Chinese communities](#chinese-communities)
- [Not recommended](#not-recommended)
- [Discontinued](#discontinued)
- [Case studies](#case-studies)
- [Biases to watch for](#biases-to-watch-for)
- [How this was tested](#how-this-was-tested)

**Reliability legend**

| Mark | Meaning |
|---|---|
| 🟢 | Revenue verified through the payment provider's API |
| 🔵 | Partly verified, or a third-party estimate |
| ⚪ | Popularity only (votes, comments, visits), unrelated to revenue |
| 🟠 | Revenue is self-reported by the founder and can't be trusted |

## Start here: a 5-minute routine

**Daily (5–10 minutes)**

1. Newly added products on [TrustMRR](https://trustmrr.com/recent): you see the product and whether anyone pays for it at the same time.
2. The top-scoring [Show HN](https://hnrss.org/show?points=50) posts from the last 24 hours.
3. [Product Hunt](https://www.producthunt.com/): skim today's themes.
4. [V2EX 分享创造](https://www.v2ex.com/go/create) if you read Chinese: what Chinese indie makers are shipping.

**Weekly (30 minutes)**

- TrustMRR's leaderboard, category pages and [/stats](https://trustmrr.com/stats): which categories have high median revenue.
- Top of the week on r/SaaS and r/SideProject.
- For-sale listings on [Microns](https://www.microns.io/) and TrustMRR: revenue and asking-price multiples of small products.
- Pick 1–2 products from the week and check their traffic and demand on Similarweb and Google Trends.

## New launches

| Name | What you get | Frequency | How to follow | Reliability | Verified |
|---|---|---|---|---|---|
| [Product Hunt](https://www.producthunt.com/) | Daily launches and popularity | Daily | [RSS](https://www.producthunt.com/feed), also per category, e.g. `/feed?category=developer-tools` | ⚪ Vote rings are common and big companies take top spots; the RSS has no vote counts | 2026-09 |
| [Show HN](https://news.ycombinator.com/show) | New projects with honest technical feedback | Real time | [hnrss.org/show?points=50](https://hnrss.org/show?points=50), or the [Algolia API](https://hn.algolia.com/api) for points and comment counts in one call | ⚪ Harder to game than PH, high-quality comments; most posts get single-digit points and lean toward dev tools | 2026-09 |
| [BetaList](https://betalist.com/) | Early products before launch | Daily | [RSS](https://feeds.feedburner.com/BetaList) | ⚪ Paid listings can skip the queue | 2026-09 |
| [Uneed](https://www.uneed.best/) | Daily launch board | Daily | Website only | ⚪ Top launch gets a few dozen votes; the selling point is a backlink | 2026-09 |
| [Fazier](https://fazier.com/) | Daily launch board | Daily | Website only | ⚪ Low votes, many ad slots | 2026-09 |
| [Microlaunch](https://microlaunch.net/) | Monthly launch batches | Monthly | Website only | ⚪ Low votes | 2026-09 |
| [TinyLaunch](https://www.tinylaunch.com/) | Weekly launch board | Weekly | Website only | ⚪ Top launch gets single-digit votes; the selling point is a backlink | 2026-09 |
| [Peerlist Launchpad](https://peerlist.io/launchpad) | Weekly launch board | Weekly | Browser only | ⚪ Top launch gets single-digit votes | 2026-09 |
| [DevHunt](https://devhunt.org/) | Developer tools only | Weekly | Browser only | ⚪ Low votes | 2026-09 |
| [SaaSHub](https://www.saashub.com/) | "Alternatives to X" directory, good for competitor research | Daily | Website only | ⚪ | 2026-09 |
| [GitHub Trending](https://github.com/trending?since=daily) | What developers are starring | Daily | Website, or the Search API with `created:>DATE&sort=stars` | ⚪ Leans toward AI and infrastructure, far from revenue-generating web products | 2026-09 |
| Reddit: [r/SideProject](https://www.reddit.com/r/SideProject/top/?t=week), [r/SaaS](https://www.reddit.com/r/SaaS/top/?t=week), [r/indiehackers](https://www.reddit.com/r/indiehackers/top/?t=week), [r/microsaas](https://www.reddit.com/r/microsaas/top/?t=week) | New projects, plus discussions on acquisition and pricing | Daily | Browse top/week by hand. `.json` returns 403 without login, RSS gets rate-limited, the official API needs approval | 🟠 Revenue posts are mostly screenshots | 2026-09 |

The launch platforms (Uneed through DevHunt) make money by selling backlinks and exposure. Many people submit for SEO, and vote counts are low. **Good for spotting themes, not for judging whether a product works.**

## Who's actually making money

| Name | What you get | Frequency | How to follow | Reliability | Verified |
|---|---|---|---|---|---|
| **[TrustMRR](https://trustmrr.com/)** ★ | Products ranked by verified revenue: MRR, 30-day revenue, growth, for-sale status | Daily | Website: [recently added](https://trustmrr.com/recent), [stats](https://trustmrr.com/stats). Public JSON at `trustmrr.com/api/ai/discovery` with 25 newly added and 25 fastest-growing products each day. The full API needs a key | 🟢 Founders connect a read-only key from their payment provider (Stripe, LemonSqueezy, Paddle, Polar, Creem, etc.) and the platform computes revenue itself | 2026-09 |
| [Microns](https://www.microns.io/) | Annual revenue and asking price of small products for sale | Daily | Website only | 🔵 The homepage says "Verified metrics" | 2026-09 |
| [Acquire.com](https://acquire.com/) | SaaS and websites for sale | Daily | Details require a buyer account | 🔵 Claims verification; method not verified | 2026-09 |
| [Flippa](https://flippa.com/search) | Websites and SaaS for sale | Daily | Listings are public, the API needs authorization | 🔵 Some listings connect Stripe or GA | 2026-09 |
| [Starter Story](https://www.starterstory.com/) | 3,000+ founder interviews with revenue figures | Irregular | Website, partly paywalled | 🟠 Revenue is what founders said in interviews | 2026-09 |
| [Indie Hackers products](https://www.indiehackers.com/products) | Founder stories and interviews | Irregular | Website only | 🟠 Marked "self-reported revenue"; some numbers are obviously made up | 2026-09 |
| X / Twitter `#buildinpublic` | Founders sharing MRR and progress | Real time | Search `"MRR" #buildinpublic` | 🟠 Screenshots can be faked | 2026-09 |

- **TrustMRR's limits**: only founders willing to go public join, and many listed products are for sale. "Fastest growing" percentages usually come from a tiny base, so always check the absolute amount. Revenue isn't profit. Its terms forbid using the data to clone businesses or republish it in bulk.
- **Marketplace bias**: products listed for sale often have stalled growth or a founder who wants out. The upside is you see how much revenue sells for how much.

## Traffic and demand

| Name | What you get | Frequency | How to follow | Reliability | Verified |
|---|---|---|---|---|---|
| [There's An AI For That](https://theresanaiforthat.com/) | New AI tools with visits and saves | Hourly | Browser only | ⚪ Exposure can be bought | 2026-09 |
| [Toolify](https://www.toolify.ai/) | 30,000+ AI tools; "Just launched" updates daily | Daily | Browser only | ⚪ Its "Revenue" ranking is really payment provider + estimated traffic, not revenue, and big companies dominate it | 2026-09 |
| [Similarweb](https://www.similarweb.com/) | Traffic estimates for a single site | On demand | Limited free lookups on the website; the API is paid | 🔵 Third-party estimate, good for checking one competitor | 2026-09 |
| [Google Trends](https://trends.google.com/) | Whether demand for something is rising | Real time | Website | 🔵 Relative interest, not absolute numbers | 2026-09 |

## Chinese communities

For makers who read Chinese.

| Name | What you get | Frequency | How to follow | Reliability | Verified |
|---|---|---|---|---|---|
| [V2EX 分享创造](https://www.v2ex.com/go/create) | New projects from Chinese indie makers | Daily | [RSS](https://www.v2ex.com/feed/create.xml) (the website is often blocked by Cloudflare, the RSS works) | ⚪ Low noise | 2026-09 |
| [DecoHack](https://decohack.com/) | Product Hunt's daily top list, in Chinese | Daily | [RSS](https://decohack.com/feed/) | ⚪ Same as PH; shows only what it picks, no raw votes | 2026-09 |
| [独立开发前线](https://indiefront.cn/) | Directory of Chinese indie products | Irregular | Website only | ⚪ Small, about 84 products | 2026-09 |
| [w2solo 产品出海](https://w2solo.com/topics/node44) | Discussions on going global | Slow | Website only | ⚪ | 2026-09 |
| [出海.tools](https://www.chuhai.tools/), [Indie Hacker Tools](https://indiehackertools.net/) | Collections of tools and channels for going global | Irregular | Website only | — Not a product feed; use as a toolbox | 2026-09 |

## Not recommended

| Approach | Why not |
|---|---|
| Searching [PublicWWW](https://publicwww.com/) for `buy.stripe.com` to find sites with payment links | Returns about 63,000 pages, topped by donation links on media and open-source sites. Most real SaaS use dynamic Checkout sessions that don't appear in page source. It tells you a site *can* take money, not how much it makes. Export is paid |
| [BuiltWith](https://trends.builtwith.com/payment/Stripe)'s list of Stripe sites | Paid, and again only tells you a site uses Stripe |
| Watching newly registered domains (e.g. [whoisds](https://www.whoisds.com/newly-registered-domains)) | Hundreds of thousands a day, almost all noise |
| Chrome Web Store sorted by newest | `sortBy=newest` had no effect in testing, and there's no official "new extensions" feed |
| Checking every launch platform every day | Votes are too low, people come for backlinks and upvote each other |
| Trusting revenue numbers on Indie Hackers or X | They're self-reported. Someone on Indie Hackers claims $1.02M a month |

## Discontinued

| Name | Status |
|---|---|
| [Open Startup](https://openstartup.tm/) | Shows "paused" and redirects to PayRequest |
| [Open Startup List](https://openstartuplist.com/) | Acquired; still lists old examples and is barely updated |
| Baremetrics Open Startups | Now mostly a marketing page |
| Indie Hackers' Stripe-verified badge | No "verified" mark found on product pages; whether the feature still exists is unverified |

The "open startup" movement has largely moved to TrustMRR.

## Case studies

**Criteria**

- Must have a verifiable revenue signal. Right now all of them come from TrustMRR's payment-provider data.
- **Replicable small products**: roughly $1k–$50k MRR, a team of 5 or fewer, no outside funding.
- **Benchmarks**: products that started as solo projects and grew big. At most 3.
- Products for sale are included and marked.
- Revenue is shown as a rounded figure with a date. Numbers change daily, so the source page is authoritative. Team size is usually self-reported by founders and isn't verified by TrustMRR.

Want to suggest a case? [Open an issue](https://github.com/yifengingit/niceweblist/issues/new?template=case.yml) with a link to its revenue proof.

### Replicable small products

#### [VectoSolve](https://vectosolve.com/)

Design tool · ~$1.7k MRR ([verified on TrustMRR](https://trustmrr.com/startup/vectosolve), 2026-09) · Solo · For sale

**What it is**: Converts PNG / JPG to SVG, and exports the formats cutting machines, laser engravers and embroidery machines need (DXF, G-code, DST, etc.).

**What to learn**: Image-to-vector is an old need. Instead of a general converter, it targets the formats crafters with Cricut, laser and embroidery machines need. Its only channels are SEO and a blog. Previews are free with a watermark; paid options start at $6.99 for a credit pack or $7.99/month.

Found on: [TrustMRR](#whos-actually-making-money) · Last verified: 2026-09

#### [Animalo](https://animalo.com/)

Vertical SaaS · ~$1.1k MRR ([verified on TrustMRR](https://trustmrr.com/startup/animalo), 2026-09) · Solo · For sale

**What it is**: Management software for pet boarding, daycare, grooming and training businesses: bookings, scheduling, invoicing and payments.

**What to learn**: A non-AI niche industry tool. 16 paying customers bring in about $1k MRR, around $68 per customer per month. B2B vertical software doesn't need many customers; it needs an industry nobody serves well.

Found on: [TrustMRR](#whos-actually-making-money) · Last verified: 2026-09

#### [Publbee](https://www.publbee.com/)

Content creation tool · ~$3k MRR ([verified on TrustMRR](https://trustmrr.com/startup/publbee), 2026-09) · 2–5 people · For sale

**What it is**: Tools for Amazon KDP self-publishing authors: topic research, keyword optimization and AI-assisted writing.

**What to learn**: Build tools for sellers on one platform. KDP authors already earn money there and will pay for anything that helps them sell more books. Four tiers: free, $29.99, $58.99 and $116.99/month.

Found on: [TrustMRR](#whos-actually-making-money) · Last verified: 2026-09

#### [TapeSearch](https://www.tapesearch.com/)

Search tool · ~$4.3k MRR, ~$92k all-time ([verified on TrustMRR](https://trustmrr.com/startup/tapesearch), 2026-09) · Solo · Not for sale

**What it is**: A search engine for podcast transcripts. It uses AI to turn podcasts into timestamped text you can search in full, set keyword alerts on, chart topic trends from, or pull through an API.

**What to learn**: The data is the acquisition channel. Each of roughly 5 million episodes gets a public page with a summary and the start of the transcript; the full transcript needs a login, and every page is listed in the sitemap for search engines. The people who pay are market researchers, financial analysts and journalists who need to find things said on podcasts. Pricing is $16.66 / $31 / $60 a month (billed annually), and the top tier sells API access. The founder has only a few hundred followers on X, so this isn't riding a personal audience. Monthly revenue has stayed between $3.7k and $5k for the past 12 months: no breakout, but steady for almost four years.

Found on: [TrustMRR](#whos-actually-making-money) · Last verified: 2026-09

#### [Data Bloo](https://www.databloo.com/)

Analytics · ~$6.1k MRR, ~$650k all-time ([verified on TrustMRR](https://trustmrr.com/startup/data-bloo), 2026-09) · Solo (per public sources) · Not for sale

**What it is**: Report templates and data connectors for Google Looker Studio, aimed at marketers, agencies and e-commerce.

**What to learn**: It lives on top of Google's free Looker Studio. The templates are free and even featured in Google's official gallery, which brings in traffic. The money comes from connectors that pipe data from each platform into the reports, sold as annual plans ($99.99–$399.99/year). Five years in, about $650k all-time.

Found on: [TrustMRR](#whos-actually-making-money) · Last verified: 2026-09

#### [SuperX](https://superx.so/)

Social media tool · ~$20k MRR ([verified on TrustMRR](https://trustmrr.com/startup/superx), 2026-09) · 3 co-founders · Not for sale

**What it is**: A writing and growth tool for X (Twitter): AI writing, scheduling, engagement and analytics.

**What to learn**: The platform it serves is also its acquisition channel. The people building an X tool have an audience on X themselves (co-founder Rob Hallam has about 60k followers), so users see them there every day. About $20k MRR within roughly a year, priced at $49 / $99 / $199 a month.

Found on: [TrustMRR](#whos-actually-making-money) · Last verified: 2026-09

### Benchmarks

> Note: Marc Lou, the founder of both products below, also runs TrustMRR.

#### [DataFast](https://datafa.st/)

Web analytics · ~$31k MRR, 1,400+ paid subscriptions ([verified on TrustMRR](https://trustmrr.com/startup/datafast), 2026-09) · Solo · Not for sale

**What it is**: Revenue-first web analytics that attributes revenue to specific marketing channels.

**What to learn**: Web analytics is a crowded space owned by Google Analytics, Plausible and others. DataFast got in with a different angle: instead of just counting visits, it answers "which channel brought in revenue", exactly what indie makers care about most. It starts at $9/month with a 14-day free trial and no card required, and now has 1,400+ paid subscriptions. Keep in mind the founder has about 400k followers on X who are themselves the target users, a distribution advantage that's hard to copy.

Found on: [TrustMRR](#whos-actually-making-money) · Last verified: 2026-09

#### [ShipFast](https://shipfa.st/)

Developer tool · One-time purchase, ~$1.27M all-time, ~$120k in the last 12 months ([verified on TrustMRR](https://trustmrr.com/startup/shipfast), 2026-09) · Solo · Not for sale

**What it is**: A Next.js SaaS boilerplate sold as a one-time purchase.

**What to learn**: It sells shovels to developers who want to build SaaS, packaging the login, payments, email and SEO setup every project rewrites into one boilerplate. A one-time purchase ($199–$299), no subscription, about $1.27M all-time: developers will pay upfront to save a few weeks. But the last 12 months brought in only about $120k, under a tenth of the total. One-time sales bring cash in fast, but revenue doesn't keep coming on its own; you have to keep finding new buyers. Compare it with DataFast, the same founder's later subscription product.

Found on: [TrustMRR](#whos-actually-making-money) · Last verified: 2026-09

## Biases to watch for

1. **Survivorship bias**: lists only show products that survived and chose to go public. 67.7% of products on TrustMRR make under $1k. That's the norm.
2. **Self-reported revenue can't be trusted**: only numbers verified through a payment provider's API count, and even those are revenue, not profit.
3. **Going public is marketing**: many people who share revenue are selling a course, a template, or the product itself.
4. **Concentration at the top**: founders with an audience make money more easily with anything. Building the same product won't get you the same result.
5. **The growth-rate trap**: "fastest growing" is usually computed from a tiny base. +439,221% means nothing without the absolute amount.
6. **Coordinated hype**: the same name showing up on PH, HN, GitHub trending and TrustMRR on the same day isn't rare. Relying on a single list makes it easy to be misled.

## How this was tested

In September 2026 every source was requested with `curl` to record its HTTP status and how it can be followed. Sources that blocked curl were checked in a browser. Claims that only come from third parties and couldn't be tested are marked "unverified". Case study revenue comes from TrustMRR's public endpoints and product pages. Everything is re-checked every quarter.

## Contributing

To suggest a source, report a dead link or recommend a case study, see [CONTRIBUTING.md](CONTRIBUTING.md).

## Maintainer

Maintained by [@puexip](https://x.com/puexip).

## License

[CC BY 4.0](LICENSE): free to share and adapt, with credit and a link back to this repository.
