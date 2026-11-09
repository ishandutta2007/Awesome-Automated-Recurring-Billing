# Awesome-Automated-Recurring-Billing

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.



I also have to flag what the search results actually support, because **most commercial entries have no published pricing**, and the open-source side has two strong projects.



## What the search results actually contain



**SaaS pricing (verified):**

- **Maxio**: **Grow $599/month** (up to $100K monthly billings); Scale quote-only; unlimited users at no additional charge .

- **Chargebee**: A comparison table in the Recurso README lists Chargebee **"from ~$599/mo"** . This is a third-party figure, not Chargebee's own pricing page.

- **Stripe Billing**: The same comparison lists **0.5%–0.8% of revenue** . Stripe's own docs describe usage-based and credit-based models but do not publish the Billing percentage .



**No pricing surfaced for:** Zuora, Recurly, Ordway, BillingPlatform, Nitrobox, LogiSense, or Rebilly. Their search results were pricing-strategy blog posts , not rate cards.



## Open-source: what actually exists



| Project | License | What it actually does | Key detail |

|---|---|---|---|

| **Kill Bill** | **Apache 2.0** | Subscription billing platform in production since 2010; catalog-driven subscriptions, plan changes, invoicing, payment plugins (Stripe, Braintree, Adyen), tax plugins (Avalara, Vertex, Kintsugi), usage-based billing for AI tokens/API calls, multi-tenant  | Mature, active (October 2026) |

| **Recurso** | **MIT** | Billing engine for SaaS: subscriptions, invoicing, multi-currency (Stripe + Razorpay), India GST / EU VAT / US sales tax, smart dunning, **double-entry ledger** with ASC 606 rev-rec, 8 aggregations / 7 charge models, self-serve importers from Stripe + Chargebee, MCP server  | Go + PostgreSQL; v1 released July 2026 |



**Both are genuine billing engines, not just invoicing tools.** Kill Bill is the established option with a decade of production use . Recurso is newer but explicitly positions against Chargebee and Stripe Billing on structural differences: **full source code, data ownership, and a built-in double-entry ledger** .



## What I recommend



**Split into two honest categories:**



**1. SaaS Recurring Billing Platforms** (proprietary):

- **Maxio** — $599/mo Grow, unlimited users 

- **Chargebee** — from ~$599/mo (third-party) 

- **Stripe Billing** — 0.5%–0.8% of revenue (third-party) 

- **Zuora, Recurly, Ordway, BillingPlatform, Nitrobox, LogiSense, Rebilly** — **pricing not surfaced**



**2. Open-Source Billing Engines** (strong section):

- **Kill Bill** — Apache 2.0, production since 2010, full subscription lifecycle, usage-based billing, payment and tax plugins 

- **Recurso** — MIT, double-entry ledger, India GST/EU VAT/US sales tax, smart dunning, Stripe + Chargebee importers, MCP server 



**Do not fabricate pricing for Zuora, Recurly, Ordway, BillingPlatform, Nitrobox, LogiSense, or Rebilly.** Their search results were blog posts, not rate cards.



**Flag the licensing difference explicitly:** Kill Bill is **Apache 2.0** (permissive, OSI-approved) ; Recurso is **MIT** (also permissive) . Both are genuinely open source, unlike some "open-core" billing tools.



If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not invent pricing for the seven vendors whose rate cards did not surface, or present third-party comparison figures as vendor-published prices.
