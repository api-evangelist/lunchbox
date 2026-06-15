# Lunchbox (lunchbox)

Lunchbox is a digital ordering and guest engagement platform for enterprise restaurant chains and ghost kitchens, offering online ordering, catering, loyalty, marketing CRM, order aggregation, and call center tooling across thousands of locations. For technology partners, Lunchbox provides an Open API that connects a restaurant's tech stack to its ecosystem, exposing location and menu data, guest account management, and order injection into the POS. The Open API supports last-mile delivery webhooks, menu consumption for digital boards and kiosks, and third-party marketplace integrations, and is documented on a dedicated developer portal at docs.lunchbox.io.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lunchbox/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lunchbox/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Restaurant
- Online Ordering
- Guest Engagement
- Catering
- Menus
- Orders
- Loyalty
- Enterprise

## Timestamps

- **Created:** 2026-06-02
- **Modified:** 2026-06-02

## APIs

### Lunchbox Core API

The Lunchbox 2.0 Core API is used for interfacing with ordering functions and building frontend interfaces that interact with Lunchbox integrations: POS, Last Mile, Loyalty, Marketing, Gift Card and more. It exposes guest (customer) account management, store and menu data, order creation and item management, discounts, payments, group ordering, and order webhooks.

- **Human URL:** [https://docs.lunchbox.io/](https://docs.lunchbox.io/)
- **Base URL:** `https://{chain_name}.lunchbox.io/api/v2`

#### Tags

- Online Ordering
- Menus
- Orders
- Guests
- Webhooks

#### Properties

- [Documentation](https://docs.lunchbox.io/)
- [Getting Started](https://support.lunchbox.io/en/articles/8684620-open-api-overview)
- [OpenAPI](openapi/lunchbox-core-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lunchbox-core.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lunchbox-core.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lunchbox Management API

The Lunchbox 2.0 Management API performs administrative functions for a restaurant chain, including listing and configuring stores, configuring service types, fetching and managing orders, voiding orders, canceling deliveries, and issuing refunds.

- **Human URL:** [https://docs.lunchbox.io/](https://docs.lunchbox.io/)
- **Base URL:** `https://{chain_name}.lunchbox.io/api/v2`

#### Tags

- Administration
- Stores
- Orders

#### Properties

- [Documentation](https://docs.lunchbox.io/)
- [OpenAPI](openapi/lunchbox-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lunchbox-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lunchbox-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lunchbox Loyalty API

The Lunchbox 2.0 Loyalty API interacts with Lunchbox Loyalty so that partners can adjust loyalty balances, redeem rewards, and catalog user wallets. It is served by the loyalty engine and authenticated with an API key.

- **Human URL:** [https://docs.lunchbox.io/](https://docs.lunchbox.io/)
- **Base URL:** `https://{loyalty_base_url}`

#### Tags

- Loyalty
- Wallets
- Rewards

#### Properties

- [Documentation](https://docs.lunchbox.io/)
- [OpenAPI](openapi/lunchbox-loyalty-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lunchbox-loyalty.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lunchbox-loyalty.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lunchbox POS API

The Lunchbox 2.0 POS API defines the contract between Lunchbox and a POS provider integration. Lunchbox retrieves store details and submits orders to the POS provider, and the POS provider notifies Lunchbox of store and order changes via webhooks.

- **Human URL:** [https://docs.lunchbox.io/](https://docs.lunchbox.io/)
- **Base URL:** `https://{chain_name}.lunchbox.io/api/v2`

#### Tags

- POS
- Orders
- Webhooks
- Stores

#### Properties

- [Documentation](https://docs.lunchbox.io/)
- [OpenAPI](openapi/lunchbox-pos-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lunchbox-pos.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lunchbox-pos.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://lunchbox.io/)
- [Documentation](https://docs.lunchbox.io/)
- [API Reference](https://docs.lunchbox.io/)
- [Support](https://support.lunchbox.io/)
- [GitHub Organization](https://github.com/lunchboxinc)
- [LinkedIn](https://www.linkedin.com/company/lunchboxtechnologies)
- [Pricing](https://lunchbox.io/service-fees)
- [Status Page](https://lunchbox.instatus.com)
- [Plans](plans/lunchbox-plans-pricing.yml)
- [Rate Limits](rate-limits/lunchbox-rate-limits.yml)
- [Fin Ops](finops/lunchbox-finops.yml)
- [Vocabulary](vocabulary/lunchbox-vocabulary.yml)
- [Spectral Rules](rules/lunchbox-spectral-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
