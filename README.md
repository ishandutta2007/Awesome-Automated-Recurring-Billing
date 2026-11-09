# Awesome-Automated-Recurring-Billing
# Awesome-Automated-Recurring-Billing

## Top Automated Recurring Billing Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Subscription Billing Automation, Usage Metering & Revenue Lifecycle Management*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Automated Recurring Billing**. These tools help businesses automate subscription lifecycles, usage-based charging, invoicing, dunning, and revenue recognition—covering everything from simple monthly plans to complex hybrid pricing models.

**Examples** include Chargebee Billing Automation, Stripe Billing, Zuora Billing, Recurly Automations, Maxio Automations, Ordway, BillingPlatform, Nitrobox, LogiSense, and Rebilly (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted billing engines, subscription management, usage metering, and revenue recognition—ideal for SaaS founders, finance engineers, platform teams, and developers building transparent, vendor-neutral billing infrastructure without per-transaction vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global subscription billing management software market is valued at approximately **$8.6B to $10.0B in 2026** (growing at a 12%–17% CAGR), embedded within a broader recurring payments transaction ecosystem surpassing $160B. The sector is **moderately fragmented**: hyper-scale payment infrastructure providers (e.g., Stripe) capture high-volume developer and checkout workflows, enterprise leaders (e.g., Zuora, Chargebee) dominate complex multi-attribute SaaS subscription and revenue operations, and specialized niche platforms compete on complex consumption-based, IoT, and ERP mediation.

## SaaS/Hosted Platforms

| Platform | Company Size (Valuation / Revenue) | Pricing | Free Tier / Free Trial Limit | Key Capabilities |
| :--- | :--- | :--- | :--- | :--- |
| **[Stripe Billing](https://stripe.com/billing)** | **$159B valuation** (~$6.8B net revenue) | **0.7% per transaction** on recurring billing volume (plus standard card processing fees of 2.9% + 30¢) | Free forever full-featured sandbox environment (Test Mode) with Test Clocks; no free production transaction allowance. | Developer-first recurring billing infrastructure with subscription schedules, proration control, threshold billing, and flexible collection methods. |
| **[Chargebee](https://www.chargebee.com/)** | **$3.5B valuation** (~$200M+ ARR) | **$0/mo** (Starter tier up to lifetime cap); paid tiers start at **$599/mo** (Performance tier) | **Free forever up to $250,000 cumulative lifetime billing** (0.75% overage fee applies thereafter); sandbox testing included. | Comprehensive subscription lifecycle management, usage-based charging, tax-inclusive invoicing, GAAP/IFRS revenue recognition (RevRec), and customer retention workflows. |
| **[Zuora](https://www.zuora.com/)** | **$1.7B acquisition valuation** (~$450M revenue) | Starts at **$40,000 – $75,000/year** (annual enterprise contract; no self-serve monthly plan) | No free tier; offers guided product demos and tailored enterprise sandbox test environments upon sales request. | Enterprise subscription order-to-cash platform supporting complex recurring charges, amendments, multi-entity subscription transactions, and automated revenue recognition. |
| **[BillingPlatform](https://billingplatform.com/)** | **$104M total funding** ($90M Series C in 2024; est. $205K+ ACV) | Starts at **~$250/mo** entry level; custom enterprise deployment contracts average **~$205,000/year** | **14-day free trial** test drive with product catalog configuration; no forever-free production tier. | Enterprise revenue lifecycle management recognized in the Gartner Magic Quadrant for Recurring Billing; excels at complex multi-tier usage, mediation, and ERP-integrated hybrid billing. |
| **[Maxio](https://www.maxio.com/)** | **~$50M+ ARR** (merged Chargify & SaaSOptics) | Starts at **$599/mo** (Grow tier for up to $100K/mo in billings) | **Build Plan ($0/mo developer sandbox)** with no expiration for API testing; no free production volume tier. | Billing and financial reporting purpose-built for B2B SaaS with usage-based billing, automated invoicing, GAAP/IFRS revenue recognition, SaaS metrics (NRR, LTV), and dunning. |
| **[Recurly](https://recurly.com/)** | **~$55M+ ARR** (majority owned by Accel-KKR; $40M funding) | Starts at **$249/mo + 0.9%** of billing volume (includes first $40,000/mo billing volume) | **90-day free trial** for platform evaluation; no forever-free production plan. | High-volume subscription management with granular coupon batching, localized payment methods, tax calculation, and AI-powered dunning workflows. |
| **[Ordway](https://ordwaylabs.com/)** | **$32.5M total funding** ($20M round in 2026; $40M Series A valuation) | Starts at **$5,000/year** (~$416/mo baseline platform & implementation fees) | No free tier or public self-serve trial; custom POC and sandbox environments provided during guided sales onboarding. | Integrated billing and payments platform with AutoPay for recurring charges, threshold billing, automated dunning, cash application, and CRM-to-ERP bridge workflows. |
| **[LogiSense](https://logisense.com/)** | **~$5M – $7M ARR** (bootstrapped/enterprise) | Starts at **$5,000/year** platform baseline (scales with consumption & mediation tiers) | **30-day free trial** sandbox for platform evaluation and mediation testing; no forever-free tier. | Usage-based billing and monetization platform with consumption drawdown, rating engines, price books, state-based subscriptions, and automated bill runs. |
| **[Rebilly](https://www.rebilly.com/)** | **~$6.4M ARR** (independent / bootstrapped) | Starts at **$15/mo** (Basic) or **$125/mo** (Pro) + 1% revenue share ($0 Rebilly transaction fees) | **30-day free trial** with full feature access on Basic and Pro plans; no forever-free production tier. | Subscription billing and payment orchestration platform with flexible pricing models (fixed, tiered, stair-step, volume), dunning rules, credit memos, and risk management. |
| **[Nitrobox](https://www.nitrobox.com/)** | **~$3.3M ARR** (Series A funded by Porsche Ventures & NeueCapital) | Custom enterprise quote; base list entry points from **€1,000 – €5,000+/year** platform fee | No self-serve free trial; live 1-on-1 guided proof-of-concept/demo sandbox upon request. | Central European agile monetization platform for platform operators and OEMs, supporting subscription, usage-based, and convergent multi-party invoicing. |

## Open-Source GitHub Projects

- **[Recurso](https://github.com/recurso-dev/recurso)**  
  Open-source (MIT) billing engine for SaaS in Go + PostgreSQL: subscriptions, invoicing, multi-currency payments, India GST/EU VAT, smart dunning, usage-based billing with 8 aggregations, built-in double-entry ledger, and self-serve importers from Stripe/Chargebee [citation:12].

### Additional Strong Open-Source Options

- **[BillCycle](https://pypi.org/project/syeedalireza-billcycle/)** — Subscription and usage-based billing engine scaffold (FastAPI + PostgreSQL + Celery Beat) with state machine and event sourcing architecture; early-stage project [citation:11].
- **[Kill Bill](https://github.com/killbill/killbill)** — Mature open-source subscription billing and payments platform with entitlements, invoicing, and usage metering for SaaS and telecom.
- **[Akaunting](https://github.com/akaunting/akaunting)** — Open-source accounting suite with recurring invoicing and subscription-style billing for small businesses.
- **[Crater](https://github.com/crater-invoice/crater)** — Open-source invoicing app with recurring invoices and subscription-like recurring billing for freelancers and SMEs.
- **[Invoice Ninja](https://github.com/invoiceninja/invoiceninja)** — Self-hosted invoicing, quoting, and recurring billing platform with client portal and payment gateway integrations.
- **[FOSSBilling](https://github.com/FOSSBilling/FOSSBilling)** — Open-source billing and client management for hosting providers and digital subscription businesses.
- **[Blesta](https://github.com/blesta/blesta)** — Client management, billing, and support software with recurring charges and payment gateway modules.
- Many community **Stripe/Paddle/Lemon Squeezy webhook processors** and **subscription state machines** for lightweight custom billing layers.

**Frameworks for building custom systems**: Combine **Recurso** for ledger-backed billing logic, **Kill Bill** for entitlements and metering, and **PostgreSQL + dbt** for revenue analytics—or layer **Invoice Ninja** on top for customer-facing invoicing.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Recurring billing tools must comply with applicable tax regulations (VAT, GST, sales tax, e-invoicing mandates) and payment card industry standards.
- Self-hosted open-source billing engines require proper PCI scope management, ledger reconciliation, and financial controls.

---

**Made for SaaS founders, finance engineers, billing platform teams, and developers building subscription businesses.**  
Let's make recurring billing more open, transparent, and auditable.
