# cpanel hosting plans: What RackNerd Actually Includes, the $10.49/Year Promo Math, and How to Pick Between Shared and Reseller

Anyone searching for cPanel hosting plans is usually trying to answer three questions: what does it cost without teaser games, is the control panel really included, and what gets quietly stripped out at the cheap end. RackNerd's shared hosting answers all three in an unusual way. The three standard plans run **$5.59, $9.59, and $15.59 per month**, every one of them ships with cPanel, LiteSpeed, CloudLinux, and daily off-site backups as standard, and there are annual promo prices that drop the entry plan to roughly $10.49 for a whole year. The trade-off you need to know about upfront: no money-back guarantee. This piece walks through the full plan table, the promo pricing math, the reseller tier, and where each plan makes sense.

> **Quick pick:** for a personal blog or a single WordPress site, the 30 GB shared plan at $5.59/month (or $10.49/year on promo) covers it, with cPanel, LiteSpeed caching, and free migration included. 👉 [Check the 30 GB cPanel plan and current pricing](https://my.racknerd.com/cart.php?a=add&pid=81&aff=11397)

## RackNerd's cPanel shared hosting plans at a glance

There are three standard shared plans, and the only things that change between them are storage and bandwidth. Per RackNerd's own order guide, all three include unlimited domains and unlimited databases, and all are available in US, European, and Asian datacenters.

| Plan | SSD storage | Monthly bandwidth | Domains & databases | Monthly price | Order |
| --- | --- | --- | --- | --- | --- |
| Shared – 30 GB | 30 GB | 2 TB | Unlimited | $5.59/mo | [Order the 30 GB plan](https://my.racknerd.com/cart.php?a=add&pid=81&aff=11397) |
| Shared – 100 GB | 100 GB | 3 TB | Unlimited | $9.59/mo | [Order the 100 GB plan](https://my.racknerd.com/cart.php?a=add&pid=82&aff=11397) |
| Shared – 200 GB | 200 GB | 5 TB | Unlimited | $15.59/mo | [Order the 200 GB plan](https://my.racknerd.com/cart.php?a=add&pid=83&aff=11397) |

The hardware underneath is the same across tiers: the shared fleet runs on AMD Ryzen 7950X processors (boost clocks up to 5.70 GHz per core), 128 GB DDR5 per node, Gen4 NVMe storage, CloudLinux OS 9, and LiteSpeed Enterprise. Multiple reviews of the service flag this as the part that separates it from the $2.99/month tier of budget hosts, which usually cut exactly these corners.

### The annual promo lineup

Alongside the standard monthly plans, RackNerd runs annual promo shared plans with lower headline prices and slightly different specs. Two independent sources currently list the promo tiers as:

| Promo plan | Storage | Monthly bandwidth | Hosted domains | Annual price | Order |
| --- | --- | --- | --- | --- | --- |
| Shared promo 30 GB | 30 GB | 3 TB | 3 (1 primary + 2 add-on) | $10.49/yr | [Get the 30 GB annual promo](https://my.racknerd.com/aff.php?aff=11397&pid=933) |
| Shared promo 85 GB | 85 GB | 10 TB | 11 (1 primary + 10 add-on) | $24.99/yr | [Get the 85 GB annual promo](https://my.racknerd.com/aff.php?aff=11397&pid=934) |
| Shared promo 200 GB | 200 GB | 30 TB | Unlimited | $59.00/yr | [Get the 200 GB annual promo](https://my.racknerd.com/aff.php?aff=11397&pid=935) |

Note the domain caps. The standard monthly plans allow unlimited domains; the promo listings cap hosted domains on the lower two tiers. If you plan to host more than three sites, the 30 GB promo will box you in even though it's the cheapest headline number.

## What's included in every plan

Feature gating is where budget hosts usually get you, so this is worth listing in full. Every shared plan, including the cheapest one, ships with:

- **cPanel** control panel, with one-click app installs through Softaculous (400+ applications including WordPress, Joomla, and Magento)
- **LiteSpeed Web Server with LSCache** — pair it with the free LiteSpeed Cache plugin on WordPress and you're using the fastest caching stack available on shared hosting
- **CloudLinux** account isolation, so a noisy neighbor on the same box doesn't tank your site
- **JetBackup daily backups**, stored off-site, restorable by you from inside cPanel without filing a support ticket
- **Free Let's Encrypt SSL** with automatic issuance and renewal
- **KernelCare** kernel patching without reboots, plus DDoS protection at the network level
- **Sitejet AI site builder** and premium outbound mail delivery
- **Free cPanel-to-cPanel migration** from any existing cPanel host

There's no starter tier that quietly drops backups or SSL. The stack is identical; you're only paying for storage, bandwidth, and (on promos) domain count.

## The catch: no refunds, and how to work around it

RackNerd does not offer a money-back guarantee. Its terms state payments are non-refundable, and three independent reviews of the service flag the same thing. On a $10.49 annual plan that's a limited risk, but it changes how you should buy.

The workaround is simple and costs you one month of patience: start monthly, then switch. A 30 GB plan at $5.59 for a test month, followed by the $10.49 annual promo, puts your first-year total at about $16.08. Compare that to paying monthly for a full year, which runs $67.08 for the same plan, or to annual-first purchases at hosts that do offer refunds but charge three to four times as much for the equivalent spec.

On renewal pricing: RackNerd's VPS specials are explicitly lifetime recurring — the official page states you renew at the same rate for as long as you keep the service. For the shared promo pricing, reviews note the order system bills the promo rate as a recurring annual price rather than a first-term teaser, but checkout doesn't print a separate renewal figure, so glance at your first invoice before the renewal date.

## Why the price is this low: the cPanel license math

Here's the part most comparison posts skip. cPanel isn't free for hosts — it's licensed per account, and the 2026 price schedule that took effect for new orders in December 2025 lists a Solo license (1 account) at **$29.99/month**, with Admin (5 accounts) at $35.99, Pro (30 accounts) at $53.99, and Premier (100 accounts) at $69.99 per month.

That means the cheapest way to run cPanel yourself — a cheap VPS plus a Solo license — costs more in licensing alone, every month, than RackNerd's entire 30 GB plan costs per year. One reviewer ran the full DIY stack math: cPanel license, LiteSpeed, CloudLinux, JetBackup, off-site backup storage, malware scanning, and mail delivery, all added up on a $10/month VPS. It doesn't come close. RackNerd gets volume pricing as an infrastructure provider running its own hardware and spends very little on marketing, which is where the margin comes from.

For context on the broader market: Hostinger's cPanel VPS option starts at a $6.49/month promotional rate on a 24-month term and renews at $11.99/month, with 1 vCPU and 50 GB NVMe at entry. Hosting.com's cPanel shared plans start at 1 website with 15 GB of NVMe storage. Both are managed offerings with refund windows, so they're reasonable if a guarantee matters more to you than raw price — but on storage-per-dollar and domain limits, RackNerd's standard plans are more generous. It's also not a fly-by-night operation: the company is a four-time Inc. 5000 honoree, most recently at No. 3693.

## Picking a datacenter

Five locations are available for cPanel hosting: Los Angeles, New York (the Newark, NJ facility added in October 2025), Frankfurt/Strasbourg in Germany, France, and Singapore. You choose at checkout. Three are free; **Singapore adds $8/year**.

The rule of thumb is distance to your visitors. Los Angeles tends to be the pick for Asia-Pacific audiences — one detailed guide measured roughly 180 ms from LA to China — while Newark serves East Coast US and Europe well through its NYIIX peering. Changing datacenter later requires a support ticket and possibly a migration, so it's worth thirty seconds of thought at order time.

## Reseller hosting: the cPanel/WHM tier

If you're selling hosting to clients rather than hosting your own sites, RackNerd's reseller plans give you WHM to create and manage individual cPanel accounts:

| Plan | SSD storage | Monthly transfer | cPanel account cap | Monthly price | Order |
| --- | --- | --- | --- | --- | --- |
| Reseller 40 GB | 40 GB | 2 TB | 20 accounts | $14.59/mo | [View reseller plans](https://bit.ly/RacKnerd) |
| Reseller 100 GB | 100 GB | Unlimited | 40 accounts | $22.59/mo | [View reseller plans](https://bit.ly/RacKnerd) |
| Reseller 200 GB | 200 GB | Unlimited | 60 accounts | $36.59/mo | [View reseller plans](https://bit.ly/RacKnerd) |

All three include white-label hostnames and nameservers, the same LiteSpeed/CloudLinux/JetBackup stack as shared, and a free ClientExec license — the billing and support platform that normally runs $11.95/month. You claim it by opening a ticket from the client area after ordering. If you outgrow your account cap, extra cPanel accounts cost $0.50 each per month, or $6 per year, without forcing a plan upgrade. RackNerd also lists smaller annual reseller promos (3 to 12 accounts starting around $34/year) on its promo pages if your client roster is tiny.

## Ordering, activation, and migration

The order flow is short, and it's worth knowing where people trip:

1. Pick a plan and click through to the cart.
2. Enter your domain — register a new one, transfer one, or use an existing domain and update nameservers later.
3. Choose billing cycle (monthly, annually, biennially, or triennially; longer terms drop the effective monthly rate), datacenter, and add order notes if you need a specific PHP version.
4. Pay via PayPal, credit card, cryptocurrency, or bank wire, then complete the order.

Activation is automatic and usually completes within 5 to 15 minutes; the confirmation email contains your cPanel login. One known snag: if the domain you enter is already attached to a RackNerd account, the cart throws an error — use a different domain or suffix to get through, then sort the domain pointing afterward.

Migration is free from any cPanel-based host. You open a ticket with your old host's credentials or a cPanel backup file, and their team moves the accounts. If your current host doesn't use cPanel, migration assistance doesn't apply, so factor in some manual work.

## FAQ

**Do all the plans really include cPanel, even the cheapest?** Yes. cPanel is standard on every shared and reseller plan, with no per-account license surcharge, which is the entire premise of the pricing.

**What renews at what price?** Standard plans renew at their listed monthly rates. Promo annual plans bill the promo rate as recurring annual pricing, per third-party reviews; RackNerd states lifetime recurring renewal explicitly for its VPS specials.

**Can I upgrade later?** Yes. Plans upgrade at any time, and you can change your billing cycle from the client area without a support ticket.

**What if I outgrow shared hosting?** The honest line: shared cPanel hosting covers blogs, business sites, and WordPress up to real traffic, but if you need root access, custom PHP extensions, or always-on processes, you want a VPS instead. RackNerd's KVM VPS specials start at $21.99/year with full root access, and those renew at the same rate for life.

## Which plan to actually get

One site or a handful of small ones: the 30 GB standard plan at $5.59/month does the job, and if it's still running fine after a month, switch to the $10.49 annual promo and let the price lock in. Several client sites or a growing blog with real bandwidth: the 85 GB promo at $24.99/year (or 100 GB standard at $9.59/month if you want unlimited domains and monthly flexibility). An agency or content-heavy network of sites: 200 GB at $59/year is the only tier with unlimited domains on the promo side. Reselling: start at 40 GB unless you already have more than 15 client sites.

Two things to confirm before you click buy: your datacenter choice (it's annoying to change later), and whether you're comfortable with the no-refund policy — if not, pay for one month first. 👉 [Open RackNerd's cPanel hosting order page and choose your plan and datacenter](https://bit.ly/RacKnerd)
