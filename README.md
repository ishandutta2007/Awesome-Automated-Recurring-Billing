# Awesome-Automated-Recurring-Billing

# Awesome-Automated-Recurring-Billing

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.



I also have to flag what the search results actually support, because **Chargebee's $160/mo is a usage-event tier, not the base billing price**, and several vendors have only placeholder or missing figures.



## The data problems



**Chargebee's $160/mo figure is for a specific usage-event tier.** The pricing page shows **$160/mo** with **100M usage events/mo** included, and a $0 plan exclusively for existing Chargebee Billing customers . **This is not the entry-level billing price.** The earlier research in this conversation established Flow at **$0 + 0.80% of invoicing or $99 + 0.65%**. Do not present $160 as the base price.



**Stripe Billing's price is now a single plan at 0.70% of billing volume.** Starter and Scale tiers were replaced; existing customers before July 10, 2024 pay a promotional 0.50% until June 30, 2025 . This is vendor-published and current.



**Recurly publishes transparent tiers.** Starter **$249/month + 0.9% of billing volume** (first $40K included); All-Access **<1% of billing volume** with $1M minimum, billed annually .



**Maxio publishes Grow at $599/month** up to $100K monthly billings; Scale quote-only; **unlimited users at no additional charge** .



**Ordway's Capterra listing shows $0.01**—a placeholder, not a real price . **Do not cite it.**



**BillingPlatform and LogiSense have no pricing**—BillingPlatform reviews discuss pricing structure but no figures ; LogiSense reviews confirm no free version and no rates .



**Nitrobox shows "Starting at €1.00 per year"**—a placeholder .



**Rebilly publishes a pricing calculator.** Pro base plan **$125/month** + **1% of monthly revenue**; additional team members **$10/mo each**; example estimate **$225/month** . This is a calculator output, not a rate card, but it is vendor-published methodology.



## Open-source: what actually exists



| Project | License | What it actually does | Status |

|---|---|---|---|

| **Kill Bill** | Open source | Subscription billing and payment platform; operates from an entirely open-source model; integrates with Stripe for payments while you own the recurring billing logic  | Mature (per prior research in this conversation) |

| **Lago** | Open source | Billing engine with **Agent SDK for LLM token billing** (Python and JS); wraps your existing LLM client, extracts normalized token usage, streams events to Lago, prices calls with live per-token prices, lets you add margin . **Lago plugin for Claude Code/Codex** teaches coding agents to implement usage-based billing  | Active (Nov 2026) |

| **Meteroid** | Open source | Cloud-native pricing and billing infrastructure for product-led SaaS; **explicitly an alternative to Chargebee, Metronome, Orb, Stripe Billing**; **"HIGHLY EXPERIMENTAL — use at your own risk"**  | Experimental, pre-stable |



**Lago is the most active open-source project surfaced**, with a genuine Agent SDK for LLM token billing and a coding agent plugin . **Kill Bill is the established mature option** . **Meteroid is explicitly experimental** and not production-ready .



## What I recommend



**Split into two honest categories:**



**1. SaaS Recurring Billing Platforms** (proprietary):

- **Stripe Billing** — 0.70% of billing volume 

- **Recurly** — Starter $249/mo + 0.9%; All-Access <1% 

- **Maxio** — Grow $599/mo, unlimited users 

- **Rebilly** — Pro base $125/mo + 1% of revenue 

- **Chargebee** — Flow $0 + 0.80% or $99 + 0.65% (from earlier research; not the $160 usage tier) 

- **Zuora, Ordway, BillingPlatform, Nitrobox, LogiSense** — **pricing not surfaced** 



**2. Open-Source Billing Engines:**

- **Kill Bill** — mature, open source, Stripe integration 

- **Lago** — active, LLM token billing SDK, coding agent plugin 

- **Meteroid** — experimental, explicitly not production-ready 



**Flag the Chargebee pricing confusion explicitly:** the $160/mo figure on the pricing page is a usage-event tier, not the base billing price . **Do not cite Ordway's $0.01 placeholder**  or Nitrobox's €1.00 placeholder  as real prices.



If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not present Chargebee's usage-event tier as the base price, cite placeholder figures, or claim Meteroid is production-ready when its own README says experimental.
