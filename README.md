# Polar (polar-sh)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Polar is an open-source, developer-first monetization platform that acts as a Merchant of Record (MoR), handling billing, payments, and global sales tax so software teams can sell digital products, subscriptions, usage-based billing, and license keys. The Polar API (https://api.polar.sh/v1) exposes products, prices, checkouts, customers, subscriptions, orders, benefits, license keys, a customer portal, usage meters/events, and webhooks behind Bearer organization access tokens. Not affiliated with Polar Electro (fitness wearables) or the Polaris design system.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/polar-sh/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/polar-sh/refs/heads/main/apis.yml)

## Tags

- Billing
- Payments
- Merchant of Record
- Monetization
- Subscriptions
- Usage Based Billing

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Polar Products & Prices API

Create and manage the product catalog and its embedded pricing - one-time, recurring (monthly/yearly), and metered/usage-based prices - and attach benefits to products.

- **Human URL:** [https://polar.sh/docs/api-reference/products](https://polar.sh/docs/api-reference/products)
- **Base URL:** `https://api.polar.sh/v1`

#### Tags

- Products
- Prices
- Catalog

#### Properties

- [Documentation](https://polar.sh/docs/features/products)
- [API Reference](https://polar.sh/docs/api-reference/products/list)
- [OpenAPI](openapi/polar-sh-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/polar-sh.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polar-sh.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Polar Checkouts API

Create and confirm hosted checkout sessions and reusable checkout links that collect payment, apply discounts, and convert customers into orders and subscriptions.

- **Human URL:** [https://polar.sh/docs/api-reference/checkouts](https://polar.sh/docs/api-reference/checkouts)
- **Base URL:** `https://api.polar.sh/v1`

#### Tags

- Checkouts
- Payments
- Checkout Links

#### Properties

- [Documentation](https://polar.sh/docs/features/checkout/session)
- [API Reference](https://polar.sh/docs/api-reference/checkouts/create-session)
- [OpenAPI](openapi/polar-sh-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/polar-sh.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polar-sh.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Polar Customers API

Manage customers by Polar ID or your own external ID, read aggregated customer state (active subscriptions, granted benefits, meters), and list payment methods.

- **Human URL:** [https://polar.sh/docs/api-reference/customers](https://polar.sh/docs/api-reference/customers)
- **Base URL:** `https://api.polar.sh/v1`

#### Tags

- Customers
- Customer State
- External ID

#### Properties

- [Documentation](https://polar.sh/docs/features/customer-management)
- [API Reference](https://polar.sh/docs/api-reference/customers/list)
- [OpenAPI](openapi/polar-sh-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/polar-sh.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polar-sh.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Polar Subscriptions API

List, create, update, and revoke recurring subscriptions, including proration on plan changes and export of subscription records.

- **Human URL:** [https://polar.sh/docs/api-reference/subscriptions](https://polar.sh/docs/api-reference/subscriptions)
- **Base URL:** `https://api.polar.sh/v1`

#### Tags

- Subscriptions
- Recurring Billing

#### Properties

- [Documentation](https://polar.sh/docs/features/subscriptions)
- [API Reference](https://polar.sh/docs/api-reference/subscriptions/list)
- [OpenAPI](openapi/polar-sh-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/polar-sh.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polar-sh.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Polar Orders API

Retrieve transaction records (one-time purchases and subscription renewals), generate and download invoices and receipts, and export order history.

- **Human URL:** [https://polar.sh/docs/api-reference/orders](https://polar.sh/docs/api-reference/orders)
- **Base URL:** `https://api.polar.sh/v1`

#### Tags

- Orders
- Invoices
- Receipts

#### Properties

- [Documentation](https://polar.sh/docs/features/orders)
- [API Reference](https://polar.sh/docs/api-reference/orders/list)
- [OpenAPI](openapi/polar-sh-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/polar-sh.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polar-sh.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Polar Benefits & License Keys API

Define benefits (entitlements such as license keys, file downloads, Discord/GitHub access) attached to products, track benefit grants, and issue, validate, activate, and deactivate license keys.

- **Human URL:** [https://polar.sh/docs/api-reference/benefits](https://polar.sh/docs/api-reference/benefits)
- **Base URL:** `https://api.polar.sh/v1`

#### Tags

- Benefits
- License Keys
- Entitlements

#### Properties

- [Documentation](https://polar.sh/docs/features/benefits)
- [API Reference](https://polar.sh/docs/api-reference/license-keys/list)
- [OpenAPI](openapi/polar-sh-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/polar-sh.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polar-sh.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Polar Meters & Events API

Ingest usage events and define meters that aggregate those events into billable quantities for usage-based (metered) prices, with per-customer meter balances.

- **Human URL:** [https://polar.sh/docs/api-reference/meters](https://polar.sh/docs/api-reference/meters)
- **Base URL:** `https://api.polar.sh/v1`

#### Tags

- Meters
- Events
- Usage Based Billing

#### Properties

- [Documentation](https://polar.sh/docs/features/usage-based-billing/introduction)
- [API Reference](https://polar.sh/docs/api-reference/events/ingest)
- [OpenAPI](openapi/polar-sh-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/polar-sh.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polar-sh.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Polar Webhooks API

Register and manage webhook endpoints, rotate signing secrets, and inspect or redeliver webhook deliveries for order, subscription, benefit, and checkout lifecycle events.

- **Human URL:** [https://polar.sh/docs/api-reference/webhooks](https://polar.sh/docs/api-reference/webhooks)
- **Base URL:** `https://api.polar.sh/v1`

#### Tags

- Webhooks
- Events
- Deliveries

#### Properties

- [Documentation](https://polar.sh/docs/integrate/webhooks/endpoints)
- [API Reference](https://polar.sh/docs/api-reference/webhooks/create)
- [OpenAPI](openapi/polar-sh-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/polar-sh.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/polar-sh.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/polarsource)
- [LinkedIn](https://www.linkedin.com/company/polar-software)
- [Website](https://polar.sh/)
- [Documentation](https://polar.sh/docs)
- [Plans](plans/polar-sh-plans-pricing.yml)
- [Rate Limits](rate-limits/polar-sh-rate-limits.yml)
- [Fin Ops](finops/polar-sh-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
