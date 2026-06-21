# Polar (polar-sh)

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
