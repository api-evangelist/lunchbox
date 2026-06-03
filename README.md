# Lunchbox (lunchbox)
Lunchbox is a digital ordering and guest engagement platform for enterprise restaurant chains and ghost kitchens, offering online ordering, catering, loyalty, marketing CRM, order aggregation, and call center tooling across thousands of locations. For technology partners, Lunchbox provides an Open API that connects a restaurant's tech stack to its ecosystem, exposing location and menu data, guest account management, and order injection into the POS. The Open API supports last-mile delivery webhooks, menu consumption for digital boards and kiosks, and third-party marketplace integrations, and is documented on a dedicated developer portal at docs.lunchbox.io.

**URL:** [Visit APIs.json URL](https://docs.lunchbox.io/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Restaurant, Online Ordering, Guest Engagement, Catering, Menus, Orders, Loyalty, Enterprise

## Timestamps

- **Created:** 2026-06-02
- **Modified:** 2026-06-02

## APIs

### Lunchbox Core API
The Lunchbox 2.0 Core API is used for interfacing with ordering functions and building frontend interfaces that interact with Lunchbox integrations: POS, Last Mile, Loyalty, Marketing, Gift Card and more. It exposes guest (customer) account management, store and menu data, order creation and item management, discounts, payments, group ordering, and order webhooks.

**Human URL:** [https://docs.lunchbox.io/](https://docs.lunchbox.io/)

#### Tags:

 - Online Ordering, Menus, Orders, Guests, Webhooks

#### Properties

- [Documentation](https://docs.lunchbox.io/)
- [GettingStarted](https://support.lunchbox.io/en/articles/8684620-open-api-overview)
- [OpenAPI](openapi/lunchbox-core-openapi.yml)
- [NaftikoCapability](capabilities/core-customer.yaml)
- [NaftikoCapability](capabilities/core-orders.yaml)
- [NaftikoCapability](capabilities/core-stores.yaml)
- [NaftikoCapability](capabilities/core-misc.yaml)

### Lunchbox Management API
The Lunchbox 2.0 Management API performs administrative functions for a restaurant chain, including listing and configuring stores, configuring service types, fetching and managing orders, voiding orders, canceling deliveries, and issuing refunds.

**Human URL:** [https://docs.lunchbox.io/](https://docs.lunchbox.io/)

#### Tags:

 - Administration, Stores, Orders

#### Properties

- [Documentation](https://docs.lunchbox.io/)
- [OpenAPI](openapi/lunchbox-management-openapi.yml)
- [NaftikoCapability](capabilities/management-stores.yaml)
- [NaftikoCapability](capabilities/management-service-types.yaml)
- [NaftikoCapability](capabilities/management-orders.yaml)

### Lunchbox Loyalty API
The Lunchbox 2.0 Loyalty API interacts with Lunchbox Loyalty so that partners can adjust loyalty balances, redeem rewards, and catalog user wallets. It is served by the loyalty engine and authenticated with an API key.

**Human URL:** [https://docs.lunchbox.io/](https://docs.lunchbox.io/)

#### Tags:

 - Loyalty, Wallets, Rewards

#### Properties

- [Documentation](https://docs.lunchbox.io/)
- [OpenAPI](openapi/lunchbox-loyalty-openapi.yml)
- [NaftikoCapability](capabilities/loyalty-user-wallet.yaml)

### Lunchbox POS API
The Lunchbox 2.0 POS API defines the contract between Lunchbox and a POS provider integration. Lunchbox retrieves store details and submits orders to the POS provider, and the POS provider notifies Lunchbox of store and order changes via webhooks.

**Human URL:** [https://docs.lunchbox.io/](https://docs.lunchbox.io/)

#### Tags:

 - POS, Orders, Webhooks, Stores

#### Properties

- [Documentation](https://docs.lunchbox.io/)
- [OpenAPI](openapi/lunchbox-pos-openapi.yml)
- [NaftikoCapability](capabilities/pos-stores.yaml)
- [NaftikoCapability](capabilities/pos-orders.yaml)

## Common Properties

- [Website](https://lunchbox.io/)
- [Documentation](https://docs.lunchbox.io/)
- [APIReference](https://docs.lunchbox.io/)
- [Support](https://support.lunchbox.io/)
- [GitHubOrganization](https://github.com/lunchboxinc)
- [LinkedIn](https://www.linkedin.com/company/lunchboxtechnologies)
- [Pricing](https://lunchbox.io/service-fees)
- [StatusPage](https://lunchbox.instatus.com)
- [Plans](plans/lunchbox-plans-pricing.yml)
- [RateLimits](rate-limits/lunchbox-rate-limits.yml)
- [FinOps](finops/lunchbox-finops.yml)
- [Vocabulary](vocabulary/lunchbox-vocabulary.yml)
- [Spectral](rules/lunchbox-spectral-rules.yml)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Lunchbox Core API](openapi/lunchbox-core-openapi.yml)
- [Lunchbox Management API](openapi/lunchbox-management-openapi.yml)
- [Lunchbox Loyalty API](openapi/lunchbox-loyalty-openapi.yml)
- [Lunchbox POS API](openapi/lunchbox-pos-openapi.yml)

### JSON Schema

33 JSON Schema files extracted from the OpenAPI component schemas, in [json-schema/](json-schema/).

### JSON Structure

33 JSON Structure files converted from the JSON Schemas, in [json-structure/](json-structure/).

### JSON-LD

- [Lunchbox Core Context](json-ld/lunchbox-core-context.jsonld)
- [Lunchbox Management Context](json-ld/lunchbox-management-context.jsonld)
- [Lunchbox Loyalty Context](json-ld/lunchbox-loyalty-context.jsonld)
- [Lunchbox POS Context](json-ld/lunchbox-pos-context.jsonld)

### Examples

33 example payloads (one per schema) in [examples/](examples/).

## Capabilities

Naftiko capabilities, one self-contained file per OpenAPI tag, each exposing the surface as both a REST adapter and an MCP adapter.

| Capability | API | MCP Tools |
|------------|-----|-----------|
| [Core — Customer](capabilities/core-customer.yaml) | Core | 39 |
| [Core — Orders](capabilities/core-orders.yaml) | Core | 20 |
| [Core — Stores](capabilities/core-stores.yaml) | Core | 16 |
| [Core — Misc](capabilities/core-misc.yaml) | Core | 4 |
| [Management — Stores](capabilities/management-stores.yaml) | Management | 2 |
| [Management — Service Types](capabilities/management-service-types.yaml) | Management | 1 |
| [Management — Orders](capabilities/management-orders.yaml) | Management | 7 |
| [Loyalty — User Wallet](capabilities/loyalty-user-wallet.yaml) | Loyalty | 8 |
| [POS — Stores](capabilities/pos-stores.yaml) | POS | 2 |
| [POS — Orders](capabilities/pos-orders.yaml) | POS | 3 |

## Vocabulary

- [Lunchbox Vocabulary](vocabulary/lunchbox-vocabulary.yml) — Unified taxonomy mapping 15 resources, 10 actions, 10 workflows, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Plans, Rate Limits & FinOps

- [Plans & Pricing](plans/lunchbox-plans-pricing.yml) — API Commons Plans 0.1 capturing the SMB and Enterprise tiers and per-product per-restaurant subscription model.
- [Rate Limits](rate-limits/lunchbox-rate-limits.yml) — API Commons Rate Limits 0.1; limits are provisioned per chain/partner during onboarding rather than publicly documented.
- [FinOps](finops/lunchbox-finops.yml) — FOCUS-aligned FinOps describing the tiered subscription plus pass-through card processing billing model.

## Rules

- [Lunchbox Spectral Rules](rules/lunchbox-spectral-rules.yml) — 31 rules across 13 categories enforcing Lunchbox API conventions (Title Case "Lunchbox ..." summaries, camelCase operationIds, snake_case parameters, token/Api-Key auth).

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
