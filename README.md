# budget hosting WordPress: What Cheap Plans Really Cost, and When a $49.99/Year BandwagonHost VPS Beats Shared Hosting

Type "budget hosting WordPress" into a search engine and you get two very different answers. One camp says you can run a site for the price of two coffees a month. The other insists anything under $10/mo is a trap. Both camps are partly right, and the confusion comes from the fact that "budget" covers two products that look similar on a pricing page but work completely differently: cheap shared hosting, where someone else runs the server, and a cheap unmanaged VPS, where you run it.

This guide walks through what budget WordPress hosting actually costs right now, where shared plans break down, and when a self-managed VPS — specifically the KVM plans sold by BandwagonHost, which start at **$49.99 per year** — is the smarter buy. All plans and prices below were pulled from BandwagonHost's live order system, and there's a **30-day money-back guarantee** if the answer turns out to be "not for me."

## What "budget" actually means for a WordPress site

A WordPress site needs four things from its host: a web server (Apache or Nginx), PHP, a MySQL-compatible database, and enough RAM and CPU to run your theme and plugins. Every budget hosting product bundles those four things — the difference is who's responsible for them.

With shared hosting, the provider runs the stack and you get a dashboard. With an unmanaged VPS, you rent a slice of a real or virtual machine and set up the stack yourself. The second route used to be the expensive one. It isn't anymore, which is exactly why the "budget hosting WordPress" search results are so tangled: a VPS at $4.17/month now competes directly with shared plans at $5–9/month.

The trade you're making is time and skill for money and control. Keep that frame for the rest of this article, because every number below only makes sense relative to it.

## The real price of cheap shared "WordPress hosting"

The headline prices on shared plans are real, but they come with structure. A well-known WordPress education site that tested eight budget providers put the cheapest credible entry plans around **$4.79/month**, which works out to about **$57.48 paid upfront for the first year**. Community advice in web hosting forums lands in the same range: for a new, low-traffic site, decent shared hosting at **$5–15/month** is usually enough.

Three things to check before you click buy:

- **The billing cycle.** Most budget shared prices assume you pay for a year or more in advance. The monthly-cycle price on the same plan is usually noticeably higher.
- **The renewal price.** Intro rates typically apply to the first term only. The renewal rate is the number that actually matters, so look it up before committing.
- **What "WordPress hosting" adds.** On budget tiers it's mostly a pre-installed WordPress and an auto-updater on top of ordinary shared hosting. Fine, but it's not a different product.

None of this is a scam — it's a legitimate product at a fair price for small sites. The problems start when the site stops being small.

## When cheap shared hosting stops being enough

There's no exact threshold, but the failure patterns are consistent enough that experienced users describe them the same way. WordPress is light when it's a blog with ten plugins and heavy the moment WooCommerce, page builders, or caching plugins pile up. On shared hosting, your site competes for CPU with dozens of other accounts on the same machine; when a neighbor gets a traffic spike or another site on the box gets abused, your load times take the hit too.

The other ceiling is control. On shared hosting you can't tune PHP workers, you can't install server-level caching like Redis yourself, you can't get a shell prompt, and you can't see why your site is actually slow. Reddit threads on the shared-vs-VPS question keep circling the same conclusion: shared is fine until you need full freedom over the server, and once you need it, nothing on a shared plan will give it to you.

So the honest trigger list for moving to a budget VPS is:

1. You're hitting CPU limits on a shared plan, or your host keeps asking you to upgrade.
2. You want root access — server-level caching, custom PHP settings, staging on the same box.
3. You're consolidating several small sites on one box instead of paying per-site.
4. You simply want a predictable monthly cost and no per-feature upsells.

## The alternative: a self-managed budget VPS

BandwagonHost (often called BWH or, in Chinese, 搬瓦工) is a long-running budget VPS brand under the IT7 network family. It sells exactly one thing: **self-managed KVM VPS hosting**. There is no cPanel, no "WordPress plan," no managed anything — the company says outright that self-management is how it keeps prices down.

What you actually get, per the current official pages:

- **KVM virtualization** with full root access, tun/tap support for VPNs, instant rDNS, snapshots and an API.
- **KiwiVM**, their in-house control panel: start/stop, OS reload, emergency console, datacenter migration, usage stats.
- **20+ OS templates** — AlmaLinux, RockyLinux, CentOS, CentOS Stream, Debian, Ubuntu, Fedora — plus bootable ISOs.
- **Locations in the US, Canada, Netherlands, Hong Kong, Japan, Singapore and Dubai.** Newer nodes run AMD EPYC CPUs with NVMe RAID-10 storage; older ones run Xeons.
- **99.9% uptime guarantee, instant setup, and a 30-day refund policy.**
- **Free migration between locations at any time, without data loss** — a genuinely unusual perk at this price.

The catch is written on the same page as the perks: this is self-managed hosting. If "SSH into the server and install a LEMP stack" sounds like a foreign language, budget another afternoon of learning — or stay on shared hosting, which is a perfectly reasonable answer.

👉 [See BandwagonHost's full current plan list and pricing](https://bit.ly/BandwagonHost)

## BandwagonHost plans and prices: the complete current lineup

BandwagonHost groups its VPS into four product lines: **Basic**, **E-Commerce (CN2 GIA)**, **E-Commerce +SLA**, and **Ultra** (Hong Kong / Tokyo / Osaka / Singapore). Every plan below is from the official order feed and in stock at the time of writing; the cheapest available billing cycle and the full cycle list are shown where they matter.

### Basic VPS line — the true budget play

Basic plans are the cheapest way in. They come with 1 Gbps ports, and you choose the location at checkout (currently New York, Los Angeles, Fremont, Amsterdam and Vancouver on the 20G plan).

| 套餐 | 配置 | 价格（USD） | 购买链接 |
| --- | --- | --- | --- |
| 20G KVM | 20 GB SSD / 1 GB RAM / 2 vCPU / 1 TB 流量 / 1 Gbps | $49.99/年 | [ Order the 20G plan — $49.99/year](https://bandwagonhost.com/aff.php?aff=79616&pid=44) |
| 40G KVM | 40 GB SSD / 2 GB RAM / 3 vCPU / 2 TB / 1 Gbps | $52.99/半年 · $99.99/年 | [ Check current 40G pricing](https://bandwagonhost.com/aff.php?aff=79616&pid=45) |
| 80G KVM | 80 GB SSD / 4 GB RAM / 4 vCPU / 3 TB / 1 Gbps | $19.99/月 · $56.99/季 · $107.99/半年 · $199.99/年 | [ View the 80G plan](https://bandwagonhost.com/aff.php?aff=79616&pid=46) |
| 160G KVM | 160 GB SSD / 8 GB RAM / 5 vCPU / 4 TB / 1 Gbps | $39.99/月 · $112.99/季 · $213.99/半年 · $399.99/年 | [ View the 160G plan](https://bandwagonhost.com/aff.php?aff=79616&pid=47) |
| 320G KVM | 320 GB SSD / 16 GB RAM / 6 vCPU / 5 TB / 1 Gbps | $79.99/月 · $227.99/季 · $432.99/半年 · $799.99/年 | [ View the 320G plan](https://bandwagonhost.com/aff.php?aff=79616&pid=48) |
| 480G KVM | 480 GB SSD / 24 GB RAM / 7 vCPU / 6 TB / 1 Gbps | $119.99/月 · $341.99/季 · $649.49/半年 · $1,199.99/年 | [ View the 480G plan](https://bandwagonhost.com/aff.php?aff=79616&pid=49) |

The 20G plan at $49.99/year is the one that gets all the attention, and the math explains why: it's **$4.17/month** for a gig of RAM and a terabyte of traffic. Two quirks worth knowing — the 40G plan's cheapest cycle is actually semi-annual, and the 80G plan's annual price ($199.99) is roughly what you'd expect to pay for two months of the 480G plan. The ladder isn't perfectly linear; price per gig improves as you go up.

### CN2 GIA E-Commerce line — for WordPress sites with China visitors

The E-Commerce line adds premium China routing (China Telecom CN2 GIA / CTGNet, China Unicom Premium, China Mobile CMIN2) and faster ports: **2.5 Gbps on the small plans, up to 10 Gbps on the big ones**, across 15 locations including Dubai. If your readers are in mainland China, this is the line that matters — BandwagonHost's own network explainer notes that ordinary China-bound routes can hit packet loss of 30% or more at peak times, which is fatal for a WordPress site's load times.

| 套餐 | 配置 | 价格（USD） | 购买链接 |
| --- | --- | --- | --- |
| 20G KVM GIA-E | 20 GB / 1 GB RAM / 2 vCPU / 1 TB / 2.5 Gbps | $49.99/季 · $89.99/半年 · $169.99/年 | [ Order the GIA-E 20G plan](https://bandwagonhost.com/aff.php?aff=79616&pid=87) |
| 40G KVM GIA-E | 40 GB / 2 GB / 3 vCPU / 2 TB / 2.5 Gbps | $89.99/季 · $169.99/半年 · $299.99/年 | [ Order the GIA-E 40G plan](https://bandwagonhost.com/aff.php?aff=79616&pid=88) |
| 80G KVM GIA-E | 80 GB / 4 GB / 4 vCPU / 3 TB / 2.5 Gbps | $56.99/月 · $149.99/季 · $289.99/半年 · $549.99/年 | [ Order the GIA-E 80G plan](https://bandwagonhost.com/aff.php?aff=79616&pid=89) |
| 160G KVM GIA-E | 160 GB / 8 GB / 6 vCPU / 4 TB / 5 Gbps | $86.99/月 · $239.99/季 · $459.99/半年 · $879.99/年 | [ Order the GIA-E 160G plan](https://bandwagonhost.com/aff.php?aff=79616&pid=90) |
| 320G KVM GIA-E | 320 GB / 16 GB / 8 vCPU / 8 TB / 5 Gbps | $159.99/月 · $459.99/季 · $869.99/半年 · $1,599.99/年 | [ Order the GIA-E 320G plan](https://bandwagonhost.com/aff.php?aff=79616&pid=91) |
| 640G KVM GIA-E | 640 GB / 32 GB / 10 vCPU / 10 TB / 10 Gbps | $289.99/月 · $799.99/季 · $1,499.99/半年 · $2,759.99/年 | [ Order the GIA-E 640G plan](https://bandwagonhost.com/aff.php?aff=79616&pid=92) |
| 1280G KVM GIA-E | 1.28 TB / 64 GB / 12 vCPU / 12 TB / 10 Gbps | $549.99/月 · $1,559.99/季 · $2,979.99/半年 · $5,499.99/年 | [ Order the GIA-E 1280G plan](https://bandwagonhost.com/aff.php?aff=79616&pid=93) |
| 1280G GIA-E · 15T 流量 | 同上，流量升至 15 TB/月 | $679/月 · $1,935/季 · $3,670/半年 · $6,790/年 | [ Order the 15T-traffic plan](https://bandwagonhost.com/aff.php?aff=79616&pid=160) |
| 1280G GIA-E · 20T 流量 | 同上，流量升至 20 TB/月 | $899/月 · $2,562/季 · $4,860/半年 · $8,999/年 | [ Order the 20T-traffic plan](https://bandwagonhost.com/aff.php?aff=79616&pid=161) |

The GIA-E 20G at **$169.99/year ($14.17/month)** is the line's entry point and, for a China-facing WordPress site, the plan most people should look at first.

### E-Commerce +SLA line — premium routing with a 99.99% uptime contract

Same premium China connectivity, but backed by a contractual **99.99% SLA**, slightly more RAM per tier, and only one location: the Coresite LA2 facility (USCA_5) in Los Angeles. These plans are for sites where downtime has a dollar cost.

| 套餐 | 配置 | 价格（USD） | 购买链接 |
| --- | --- | --- | --- |
| 20G KVM SLA | 20 GB / 1.06 GB RAM / 2 vCPU / 1 TB / 2.5 Gbps | $65.89/季 · $125.99/半年 · $239.99/年 | [ Compare the SLA 20G plan](https://bandwagonhost.com/aff.php?aff=79616&pid=164) |
| 40G KVM SLA | 40 GB / 2.09 GB / 3 vCPU / 2 TB / 2.5 Gbps | $116.99/季 · $219.99/半年 · $399.99/年 | [ Compare the SLA 40G plan](https://bandwagonhost.com/aff.php?aff=79616&pid=165) |
| 80G KVM SLA | 80 GB / 4.14 GB / 4 vCPU / 3 TB / 2.5 Gbps | $69.99/月 · $199.99/季 · $379.99/半年 · $699.99/年 | [ Compare the SLA 80G plan](https://bandwagonhost.com/aff.php?aff=79616&pid=166) |
| 160G KVM SLA | 160 GB / 8.26 GB / 6 vCPU / 5 TB / 5 Gbps | $109.99/月 · $299.99/季 · $569.99/半年 · $1,099.99/年 | [ Compare the SLA 160G plan](https://bandwagonhost.com/aff.php?aff=79616&pid=167) |
| 320G KVM SLA | 320 GB / 16.5 GB / 8 vCPU / 8 TB / 5 Gbps | $199.99/月 · $569.99/季 · $1,079.99/半年 · $1,999.99/年 | [ Compare the SLA 320G plan](https://bandwagonhost.com/aff.php?aff=79616&pid=168) |
| 640G KVM SLA | 640 GB / 32.9 GB / 10 vCPU / 10 TB / 10 Gbps | $369.99/月 · $1,055.99/季 · $1,999.99/半年 · $3,699.99/年 | [ Compare the SLA 640G plan](https://bandwagonhost.com/aff.php?aff=79616&pid=169) |
| 1280G KVM SLA | 1.28 TB / 64 GB / 12 vCPU / 12 TB / 10 Gbps | $699.99/月 · $1,989.99/季 · $3,779.99/半年 · $6,999.99/年 | [ Compare the SLA 1280G plan](https://bandwagonhost.com/aff.php?aff=79616&pid=170) |
| 1280G SLA · 15T 流量 | 同上，流量 15 TB/月 | $879.99/月 · $2,509.99/季 · $4,768.99/半年 · $8,799.99/年 | [ Compare the SLA 15T plan](https://bandwagonhost.com/aff.php?aff=79616&pid=171) |
| 1280G SLA · 20T 流量 | 同上，流量 20 TB/月 | $1,159.99/月 · $3,299.99/季 · $6,269.99/半年 · $11,598.99/年 | [ Compare the SLA 20T plan](https://bandwagonhost.com/aff.php?aff=79616&pid=172) |

### Ultra line — Hong Kong, Tokyo, Osaka and Singapore CN2 GIA

Absolute lowest latency to mainland China and East Asia, 1 Gbps ports, small traffic allowances (500 GB/month at the 40G tier), and prices to match. Hong Kong and Tokyo carry the premium; Osaka and Singapore run roughly 45% cheaper at the entry tier.

| 套餐 / 配置 | 香港 | 东京 | 大阪 | 新加坡 |
| --- | --- | --- | --- | --- |
| 40G KVM · 2 GB RAM · 500 GB | [$89.99/月 或 $899.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=95) | [$89.99/月 或 $899.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=108) | [$49.99/月 或 $499.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=134) | [$49.99/月 或 $499.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=173) |
| 80G KVM · 4 GB RAM · 1 TB | [$155.99/月 或 $1,559.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=96) | [$155.99/月 或 $1,559.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=109) | [$86.99/月 或 $869.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=135) | [$86.99/月 或 $869.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=174) |
| 160G KVM · 8 GB RAM · 2 TB | [$299.99/月 或 $2,999.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=97) | [$299.99/月 或 $2,999.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=110) | [$165.99/月 或 $1,665.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=136) | [$165.99/月 或 $1,665.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=175) |
| 320G KVM · 16 GB RAM · 4 TB | [$589.99/月 或 $5,899.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=98) | [$589.99/月 或 $5,899.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=111) | [$329.99/月 或 $3,199.00/年](https://bandwagonhost.com/aff.php?aff=79616&pid=137) | [$329.99/月 或 $3,199.00/年](https://bandwagonhost.com/aff.php?aff=79616&pid=176) |
| 640G KVM · 32 GB RAM · 6 TB | [$989.99/月 或 $9,989.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=122) | [$989.99/月 或 $9,989.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=123) | [$549.99/月 或 $5,549.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=138) | [$549.99/月 或 $5,549.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=177) |
| 1280G KVM · 64 GB RAM · 8 TB | [$1,889.99/月 或 $18,989.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=124) | [$1,889.99/月 或 $18,989.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=125) | [$1,059.99/月 或 $10,559.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=139) | [$1,059.99/月 或 $10,559.99/年](https://bandwagonhost.com/aff.php?aff=79616&pid=178) |

Each of those cells also has cheaper quarterly and semi-annual cycles at checkout. Unless you're running something latency-critical for Asian users, the Ultra line is a niche product — the GIA-E line in Los Angeles delivers most of the China-routing benefit at a fraction of the price.

👉 [Browse all current locations and cycles at checkout](https://bit.ly/BandwagonHost)

## Which budget actually fits your WordPress project

Put the two camps side by side and the decision gets a lot less foggy:

| 路线 | 真实成本 | 你得到什么 | 代价 |
| --- | --- | --- | --- |
| 入门共享主机 | 约 $4.79/月起，通常按年预付（首年约 $58） | 面板化管理，WordPress 自动安装，服务器有人管 | 无 root 权限，受邻居站点影响，插件一多就吃力 |
| BWH 20G Basic KVM | $49.99/年（$4.17/月） | 独立 root 权限、1 GB 内存、1 TB 流量、5 个机房 | 自己装、自己维护 WordPress |
| BWH 20G GIA-E | $169.99/年（$14.17/月） | 加上 CN2 GIA 优质中国线路、2.5 Gbps 端口、15 个机房可选 | 仍是 1 GB 内存，仍需自助管理 |
| BWH SLA 系列（仅洛杉矶） | $239.99/年起 | 99.99% SLA 合同保障 + 优质线路 | 小套餐无月付周期，仅单一机房 |
| BWH Ultra 香港/东京 | $899.99/年（$75/月）起 | 对中国/亚洲最低延迟 | 价格已超过多数共享主机商务套餐 |

Some concrete judgments, based on those numbers:

- **Hobby blog or portfolio, a few hundred visits a day:** shared hosting at $5-ish/month, or the $49.99/year Basic plan if you're comfortable with a terminal. Both are rational; the VPS just asks more of you.
- **A site with 10+ plugins, WooCommerce, or page builders:** the 1 GB plans will feel tight. Start at the 80G Basic ($19.99/month, 4 GB RAM) or the GIA-E 80G if China speed matters. Third-party reviews of BandwagonHost keep landing on the same trade-off: network quality is the selling point, traffic quotas are the constraint — these are steady-state plans, not burst plans.
- **A WordPress site with meaningful Chinese readership:** GIA-E is the whole point of this brand. The $169.99/year 20G plan is the cheapest serious answer to the China routing problem anywhere in hosting.
- **A revenue-producing site:** the SLA line exists precisely so you can put a contract behind your uptime, not a marketing claim.
- **Anyone considering Ultra Hong Kong at $75/month:** you're now spending more than managed WordPress hosting costs. Make sure latency, not habit, is driving that decision.

One more point in BandwagonHost's favor: recurring analyses keep noting that the brand doesn't play the low-intro-price-then-painful-renewal game. The $49.99 plan renews at $49.99. After you've compared renewal rates on shared hosts, you'll understand why people mention this.

## Running WordPress on a BandwagonHost VPS: the honest effort

Here's the full workflow, so you can judge the effort before buying.

1. **Order and pick your OS.** Choose the plan, location, and an OS template — Debian or Ubuntu are the usual picks for WordPress because of their long support windows and documentation coverage.
2. **Open KiwiVM.** From the client area, the panel auto-login takes you straight in. Start/stop, console, rDNS, snapshots and OS reloads all live here.
3. **Install WordPress.** Two routes. The manual route: SSH in, update packages, install a LEMP stack (Nginx, MySQL/MariaDB, PHP), then run the normal WordPress install. The shortcut route, documented in BandwagonHost's own knowledgebase: mount a **TurnKey Linux ISO** from KiwiVM, pick the WordPress appliance from the dropdown, boot from it, and you get a pre-configured WordPress stack.
4. **Maintain it.** From then on, updates, backups (KiwiVM snapshots help, but keep off-server backups too), and security are your job. Nobody will fix your broken plugin at 2 a.m.

That last step is the entire difference between this and a $5 shared plan. If reading "your job" made you tired, stay shared. If it made you feel in control, you're the target customer.

## The fine print worth knowing before you order

- **30-day money-back guarantee.** Real and self-serve: submit the refund request form from your account within 30 days and billing processes it, subject to the Terms of Service. The TOS notes refunds go back to the original payment method.
- **99.9% uptime guarantee** and instant setup on all plans.
- **Traffic is capped, not unmetered.** Exceeding your monthly transfer has consequences under the TOS, and the quotas (1 TB/month on entry plans) are one of the brand's known constraints.
- **Some network restrictions apply.** Port 111 is blocked network-wide for security reasons, and the CN2 GIA routes — premium as they are — are not tolerant of DDoS attacks; under attack, IPs can be null-routed. Worth knowing if you expect to be a target.
- **Coupons are mostly noise.** Coupon-aggregator sites list "150 verified codes" that are single-digit percent at best and frequently stale. Treat any code as a maybe until it applies in your cart — the plans' base pricing is the realistic number to plan around.

## Quick answers to the questions people actually search

**Is a $49.99/year VPS really enough for WordPress?** For a lean site — static-ish content, a handful of plugins, modest traffic — yes, a 1 GB RAM KVM with a full terabyte of monthly transfer handles it, and there's no noisy neighbor. The moment you run WooCommerce or a heavy page builder, jump to a 2–4 GB plan.

**Is BandwagonHost shared hosting?** No. It's VPS-only. If you specifically want a managed dashboard and someone else patching the server, its plans are the wrong tool no matter how cheap they are.

**Do I need the CN2 GIA plans?** Only if China access speed matters to your audience or your own workflow. For everyone else, Basic at half the price does the same WordPress job.

**What about hosts like Hostinger or Namecheap — are they cheaper?** Their entry shared plans land in the same $4–5/month range, so the sticker prices are comparable. You're comparing a managed shared product against an unmanaged VPS; read the section above twice before deciding which trade suits you.

The practical bottom line: budget shared hosting and a budget KVM VPS now cost nearly the same, so the choice is really about how much server you want to own versus rent. If you want to own it, [👉 start with the $49.99/year 20G plan](https://bandwagonhost.com/aff.php?aff=79616&pid=44) and use the 30-day guarantee as your safety net while you find out whether self-managing suits you.
