# Lunchbox

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

**Areas:** Restaurant · Online Ordering · Guest Engagement · Catering · Menus · Order · Loyalty · Enterprise

## Lunchbox on APIs.io

Everything profiled for Lunchbox is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/lunchbox/](https://apis.io/providers/lunchbox/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Lunchbox Customer API](https://apis.io/apis/lunchbox/lunchbox-customer-api/) — Guest account registration, authentication, and profile management.
- [Lunchbox Misc API](https://apis.io/apis/lunchbox/lunchbox-misc-api/) — Reference data such as contact, countries, and states.
- [Lunchbox Orders API](https://apis.io/apis/lunchbox/lunchbox-orders-api/) — Order creation, item management, discounts, payments, and group orders.
- [Lunchbox Service Types API](https://apis.io/apis/lunchbox/lunchbox-service-types-api/) — Configure store service types.
- [Lunchbox Stores API](https://apis.io/apis/lunchbox/lunchbox-stores-api/) — Store configuration, hours, menus, and discounts.
- [Lunchbox User Wallet API](https://apis.io/apis/lunchbox/lunchbox-user-wallet-api/) — Create, search, retrieve, update, validate, confirm, refund, and adjust loyalty user wallets.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Lunchbox Agentic Access](https://apis.io/agentic-access/lunchbox/lunchbox-agentic-access/)

#### JSON Schema (33)

The data models the API reads and writes.

- [AddItemsRequest](https://apis.io/schemas/lunchbox/core-add-items-request/)
- [Address](https://apis.io/schemas/lunchbox/core-address/)
- [AuthSession](https://apis.io/schemas/lunchbox/core-auth-session/)
- [Charges](https://apis.io/schemas/lunchbox/core-charges/)
- [Customer](https://apis.io/schemas/lunchbox/core-customer/)
- [LoginRequest](https://apis.io/schemas/lunchbox/core-login-request/)
- [Menu](https://apis.io/schemas/lunchbox/core-menu/)
- [MenuItem](https://apis.io/schemas/lunchbox/core-menu-item/)
- [NewOrderRequest](https://apis.io/schemas/lunchbox/core-new-order-request/)
- [Order](https://apis.io/schemas/lunchbox/core-order/)
- [OrderChildItem](https://apis.io/schemas/lunchbox/core-order-child-item/)
- [OrderItem](https://apis.io/schemas/lunchbox/core-order-item/)
- [RegistrationRequest](https://apis.io/schemas/lunchbox/core-registration-request/)
- [Store](https://apis.io/schemas/lunchbox/core-store/)
- [UserWallet](https://apis.io/schemas/lunchbox/loyalty-user-wallet/)
- [UserWalletCreate](https://apis.io/schemas/lunchbox/loyalty-user-wallet-create/)
- [UserWalletUpdate](https://apis.io/schemas/lunchbox/loyalty-user-wallet-update/)
- [WalletReward](https://apis.io/schemas/lunchbox/loyalty-wallet-reward/)
- [ManagedOrderSummary](https://apis.io/schemas/lunchbox/management-managed-order-summary/)
- [ManagedStore](https://apis.io/schemas/lunchbox/management-managed-store/)
- [ManagedStoreSummary](https://apis.io/schemas/lunchbox/management-managed-store-summary/)
- [OrderPage](https://apis.io/schemas/lunchbox/management-order-page/)
- [ServiceTypeConfig](https://apis.io/schemas/lunchbox/management-service-type-config/)
- [StorePage](https://apis.io/schemas/lunchbox/management-store-page/)
- [OrderUpdateEvent](https://apis.io/schemas/lunchbox/pos-order-update-event/)
- …and 8 more published on APIs.io

#### JSON Structure (33)

Data models expressed in JSON Structure.

- [Core Add Items Request Structure](https://apis.io/json-structure/lunchbox/core-add-items-request-structure/)
- [Core Address Structure](https://apis.io/json-structure/lunchbox/core-address-structure/)
- [Core Auth Session Structure](https://apis.io/json-structure/lunchbox/core-auth-session-structure/)
- [Core Charges Structure](https://apis.io/json-structure/lunchbox/core-charges-structure/)
- [Core Customer Structure](https://apis.io/json-structure/lunchbox/core-customer-structure/)
- [Core Login Request Structure](https://apis.io/json-structure/lunchbox/core-login-request-structure/)
- [Core Menu Item Structure](https://apis.io/json-structure/lunchbox/core-menu-item-structure/)
- [Core Menu Structure](https://apis.io/json-structure/lunchbox/core-menu-structure/)
- [Core New Order Request Structure](https://apis.io/json-structure/lunchbox/core-new-order-request-structure/)
- [Core Order Child Item Structure](https://apis.io/json-structure/lunchbox/core-order-child-item-structure/)
- [Core Order Item Structure](https://apis.io/json-structure/lunchbox/core-order-item-structure/)
- [Core Order Structure](https://apis.io/json-structure/lunchbox/core-order-structure/)
- [Core Registration Request Structure](https://apis.io/json-structure/lunchbox/core-registration-request-structure/)
- [Core Store Structure](https://apis.io/json-structure/lunchbox/core-store-structure/)
- [Loyalty User Wallet Create Structure](https://apis.io/json-structure/lunchbox/loyalty-user-wallet-create-structure/)
- [Loyalty User Wallet Structure](https://apis.io/json-structure/lunchbox/loyalty-user-wallet-structure/)
- [Loyalty User Wallet Update Structure](https://apis.io/json-structure/lunchbox/loyalty-user-wallet-update-structure/)
- [Loyalty Wallet Reward Structure](https://apis.io/json-structure/lunchbox/loyalty-wallet-reward-structure/)
- [Management Managed Order Summary Structure](https://apis.io/json-structure/lunchbox/management-managed-order-summary-structure/)
- [Management Managed Store Structure](https://apis.io/json-structure/lunchbox/management-managed-store-structure/)
- [Management Managed Store Summary Structure](https://apis.io/json-structure/lunchbox/management-managed-store-summary-structure/)
- [Management Order Page Structure](https://apis.io/json-structure/lunchbox/management-order-page-structure/)
- [Management Service Type Config Structure](https://apis.io/json-structure/lunchbox/management-service-type-config-structure/)
- [Management Store Page Structure](https://apis.io/json-structure/lunchbox/management-store-page-structure/)
- [Pos Order Update Event Structure](https://apis.io/json-structure/lunchbox/pos-order-update-event-structure/)
- …and 8 more published on APIs.io

#### JSON-LD (4)

Linked-data contexts for the provider's vocabulary.

- [Lunchbox Core Context](https://apis.io/jsonld/lunchbox/lunchbox-core-context/)
- [Lunchbox Loyalty Context](https://apis.io/jsonld/lunchbox/lunchbox-loyalty-context/)
- [Lunchbox Management Context](https://apis.io/jsonld/lunchbox/lunchbox-management-context/)
- [Lunchbox Pos Context](https://apis.io/jsonld/lunchbox/lunchbox-pos-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Lunchbox Vocabulary](https://apis.io/vocabularies/lunchbox/lunchbox-vocabulary/)

#### Examples (33)

Example requests and responses.

- [Core Add Items Request Example](https://apis.io/examples/lunchbox/core-add-items-request-example/)
- [Core Address Example](https://apis.io/examples/lunchbox/core-address-example/)
- [Core Auth Session Example](https://apis.io/examples/lunchbox/core-auth-session-example/)
- [Core Charges Example](https://apis.io/examples/lunchbox/core-charges-example/)
- [Core Customer Example](https://apis.io/examples/lunchbox/core-customer-example/)
- [Core Login Request Example](https://apis.io/examples/lunchbox/core-login-request-example/)
- [Core Menu Example](https://apis.io/examples/lunchbox/core-menu-example/)
- [Core Menu Item Example](https://apis.io/examples/lunchbox/core-menu-item-example/)
- [Core New Order Request Example](https://apis.io/examples/lunchbox/core-new-order-request-example/)
- [Core Order Child Item Example](https://apis.io/examples/lunchbox/core-order-child-item-example/)
- [Core Order Example](https://apis.io/examples/lunchbox/core-order-example/)
- [Core Order Item Example](https://apis.io/examples/lunchbox/core-order-item-example/)
- [Core Registration Request Example](https://apis.io/examples/lunchbox/core-registration-request-example/)
- [Core Store Example](https://apis.io/examples/lunchbox/core-store-example/)
- [Loyalty User Wallet Create Example](https://apis.io/examples/lunchbox/loyalty-user-wallet-create-example/)
- [Loyalty User Wallet Example](https://apis.io/examples/lunchbox/loyalty-user-wallet-example/)
- [Loyalty User Wallet Update Example](https://apis.io/examples/lunchbox/loyalty-user-wallet-update-example/)
- [Loyalty Wallet Reward Example](https://apis.io/examples/lunchbox/loyalty-wallet-reward-example/)
- [Management Managed Order Summary Example](https://apis.io/examples/lunchbox/management-managed-order-summary-example/)
- [Management Managed Store Example](https://apis.io/examples/lunchbox/management-managed-store-example/)
- [Management Managed Store Summary Example](https://apis.io/examples/lunchbox/management-managed-store-summary-example/)
- [Management Order Page Example](https://apis.io/examples/lunchbox/management-order-page-example/)
- [Management Service Type Config Example](https://apis.io/examples/lunchbox/management-service-type-config-example/)
- [Management Store Page Example](https://apis.io/examples/lunchbox/management-store-page-example/)
- [Pos Order Update Event Example](https://apis.io/examples/lunchbox/pos-order-update-event-example/)
- …and 8 more published on APIs.io

#### Collections (10)

Postman and Open Collection request collections.

- [Lunchbox Core API](https://apis.io/collections/lunchbox/open-lunchbox-core/)
- [Lunchbox Core Customer API](https://apis.io/collections/lunchbox/open-lunchbox-customer-api/)
- [Lunchbox Loyalty API](https://apis.io/collections/lunchbox/open-lunchbox-loyalty/)
- [Lunchbox Management API](https://apis.io/collections/lunchbox/open-lunchbox-management/)
- [Lunchbox Core Customer Misc API](https://apis.io/collections/lunchbox/open-lunchbox-misc-api/)
- [Lunchbox Core Customer Orders API](https://apis.io/collections/lunchbox/open-lunchbox-orders-api/)
- [Lunchbox POS API](https://apis.io/collections/lunchbox/open-lunchbox-pos/)
- [Lunchbox Core Customer Service Types API](https://apis.io/collections/lunchbox/open-lunchbox-service-types-api/)
- [Lunchbox Core Customer Stores API](https://apis.io/collections/lunchbox/open-lunchbox-stores-api/)
- [Lunchbox Core Customer User Wallet API](https://apis.io/collections/lunchbox/open-lunchbox-user-wallet-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Lunchbox — jsonschema rules](https://apis.io/rules/lunchbox/lunchbox-jsonschema-spectral-rules/)
- [Lunchbox API Rules](https://apis.io/rules/lunchbox/lunchbox-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Lunchbox Authentication](https://apis.io/security/lunchbox/lunchbox-authentication/)
- [Lunchbox Domain Security](https://apis.io/security/lunchbox/lunchbox-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Lunchbox Plans Pricing](https://apis.io/plans/lunchbox/lunchbox-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Lunchbox Rate Limits](https://apis.io/rate-limits/lunchbox/lunchbox-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Lunchbox Finops](https://apis.io/finops/lunchbox/lunchbox-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://lunchbox.io/)
- [Documentation](https://docs.lunchbox.io/)
- [API reference](https://docs.lunchbox.io/)
- [Pricing](https://lunchbox.io/service-fees)
- [Support](https://support.lunchbox.io/)
- [Blog](https://lunchbox.io/press)
- [GitHub](https://github.com/lunchboxinc)
- [Status](https://lunchbox.instatus.com)

## API Evangelist rating

**Kin Score 36.5** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 54.1 |
| Contract governance | 27.3 |
| Operational transparency | 10.5 |
| Developer ergonomics | 47.6 |
| Access clarity | 10.5 |

**Agent readiness 29.0** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/lunchbox/](https://apis.io/providers/lunchbox/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Lunchbox: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/lunchbox/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
