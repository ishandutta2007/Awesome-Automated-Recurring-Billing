# Awesome-Automated-Recurring-Billing
# Awesome-Automated-Recurring-Billing

# Top Automated Recurring Billing Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Subscription Billing Automation, Usage Metering & Revenue Lifecycle Management*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Automated Recurring Billing**. These tools help businesses automate subscription lifecycles, usage-based charging, invoicing, dunning, and revenue recognition—covering everything from simple monthly plans to complex hybrid pricing models.

**Examples** include Chargebee Billing Automation, Stripe Billing, Zuora Billing, Recurly Automations, Maxio Automations, Ordway, BillingPlatform, Nitrobox, LogiSense, and Rebilly (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted billing engines, subscription management, usage metering, and revenue recognition—ideal for SaaS founders, finance engineers, platform teams, and developers building transparent, vendor-neutral billing infrastructure without per-transaction vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Chargebee Billing Automation](https://www.chargebee.com/)**  
  Subscription billing and revenue management platform handling recurring billing, usage-based charging, invoicing, and subscription lifecycle via web interface, REST API, webhooks, and hosted pages [citation:1].

- **[Stripe Billing](https://stripe.com/billing)**  
  Developer-first recurring billing infrastructure with subscription schedules, proration control, threshold billing, and flexible collection methods (auto-charge or invoice) [citation:14].

- **[Zuora Billing](https://www.zuora.com/)**  
  Enterprise subscription order-to-cash platform supporting complex recurring charges, amendments, cancellations, and multi-tenant subscription transaction management [citation:3].

- **[Recurly Automations](https://recurly.com/)**  
  Subscription management platform with granular coupon batching, decimal-level add-on pricing, localized payment methods, tax-inclusive invoicing, and AI-powered dunning workflows [citation:4].

- **[Maxio Automations](https://www.maxio.com/)**  
  Billing and financial reporting for B2B SaaS with usage-based billing, automated invoicing, GAAP/IFRS revenue recognition, dunning, and 85+ integrations [citation:5].

- **[Ordway](https://ordwaylabs.com/)**  
  Integrated billing and payments platform with AutoPay for recurring charges, threshold billing, automated dunning, cash application, and dispute management [citation:6].

- **[BillingPlatform](https://billingplatform.com/)**  
  Enterprise revenue lifecycle management recognized as a Leader in Gartner Magic Quadrant for Recurring Billing, with strength in complex usage, mixed billing, and enterprise-grade scenarios [citation:7].

- **[Nitrobox](https://www.nitrobox.com/)**  
  Financial platform for platform operators with subscription, usage-based, and hybrid monetization, convergent invoicing, and payment automation [citation:8].

- **[LogiSense](https://logisense.com/)**  
  Usage-based billing and monetization platform with consumption drawdown, price books, state-based subscriptions, automated bill runs, and dunning rules [citation:9].

- **[Rebilly](https://www.rebilly.com/)**  
  Subscription billing platform with orders, invoices, pricing plans (fixed, tiered, stair-step, volume), quotes, credit memos, coupons, and auto-pay [citation:10].

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
