# Lunchbox (lunchbox)

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
