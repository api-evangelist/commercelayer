# Commerce Layer (commercelayer)

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

Commerce Layer is a headless, composable commerce platform that exposes a JSON:API-compliant REST API for building omnichannel storefronts and order management. The Core API serves SKUs, prices, stock, orders, line items, customers, addresses, shipments, payment methods, markets, and promotions, with OAuth2 authentication, market-scoped access tokens, and real-time webhooks.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/commercelayer/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/commercelayer/refs/heads/main/apis.yml)

## Tags

- Commerce
- Headless
- Composable
- eCommerce
- JSON:API
- Orders

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Commerce Layer SKUs, Prices & Stock API

Manage product SKUs and their variations, price lists and prices, and stock items and stock locations as JSON:API resources, with market-scoped reads that filter catalog and inventory by the access token's market.

- **Human URL:** [https://docs.commercelayer.io/core/api-reference](https://docs.commercelayer.io/core/api-reference)
- **Base URL:** `https://yourdomain.commercelayer.io/api`

#### Tags

- SKUs
- Prices
- Stock
- Inventory

#### Properties

- [Documentation](https://docs.commercelayer.io/core/api-reference)
- [API Reference](https://docs.commercelayer.io/core/api-reference)
- [OpenAPI](openapi/commercelayer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/commercelayer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercelayer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Commerce Layer Orders & Line Items API

Create and manage shopping carts and orders, add and update line items, and drive the checkout state machine (pending, placed, approved) through the JSON:API order and line_item resources.

- **Human URL:** [https://docs.commercelayer.io/core/api-reference](https://docs.commercelayer.io/core/api-reference)
- **Base URL:** `https://yourdomain.commercelayer.io/api`

#### Tags

- Orders
- Line Items
- Cart
- Checkout

#### Properties

- [Documentation](https://docs.commercelayer.io/core/api-reference)
- [API Reference](https://docs.commercelayer.io/core/api-reference)
- [OpenAPI](openapi/commercelayer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/commercelayer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercelayer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Commerce Layer Customers & Addresses API

Manage customer records, customer addresses, and the address book, including billing and shipping addresses associated with orders and customer accounts.

- **Human URL:** [https://docs.commercelayer.io/core/api-reference](https://docs.commercelayer.io/core/api-reference)
- **Base URL:** `https://yourdomain.commercelayer.io/api`

#### Tags

- Customers
- Addresses
- Accounts

#### Properties

- [Documentation](https://docs.commercelayer.io/core/api-reference)
- [API Reference](https://docs.commercelayer.io/core/api-reference)
- [OpenAPI](openapi/commercelayer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/commercelayer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercelayer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Commerce Layer Shipments API

Manage order shipments and their fulfillment lifecycle, including shipping methods, stock transfers, and shipment status transitions tied to stock locations.

- **Human URL:** [https://docs.commercelayer.io/core/api-reference](https://docs.commercelayer.io/core/api-reference)
- **Base URL:** `https://yourdomain.commercelayer.io/api`

#### Tags

- Shipments
- Fulfillment
- Shipping

#### Properties

- [Documentation](https://docs.commercelayer.io/core/api-reference)
- [API Reference](https://docs.commercelayer.io/core/api-reference)
- [OpenAPI](openapi/commercelayer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/commercelayer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercelayer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Commerce Layer Payments API

Configure payment methods and payment gateways and manage payment sources used to authorize and capture funds against orders across supported PSPs.

- **Human URL:** [https://docs.commercelayer.io/core/api-reference](https://docs.commercelayer.io/core/api-reference)
- **Base URL:** `https://yourdomain.commercelayer.io/api`

#### Tags

- Payments
- Payment Methods
- Gateways

#### Properties

- [Documentation](https://docs.commercelayer.io/core/api-reference)
- [API Reference](https://docs.commercelayer.io/core/api-reference)
- [OpenAPI](openapi/commercelayer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/commercelayer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercelayer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Commerce Layer Markets API

Manage markets that bind a price list, an inventory model, and a merchant to scope catalog, pricing, and inventory for a region, channel, or brand via market-scoped access tokens.

- **Human URL:** [https://docs.commercelayer.io/core/api-reference](https://docs.commercelayer.io/core/api-reference)
- **Base URL:** `https://yourdomain.commercelayer.io/api`

#### Tags

- Markets
- Pricing
- Localization

#### Properties

- [Documentation](https://docs.commercelayer.io/core/api-reference)
- [API Reference](https://docs.commercelayer.io/core/api-reference)
- [OpenAPI](openapi/commercelayer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/commercelayer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercelayer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Commerce Layer Promotions API

Configure promotions such as percentage and fixed-amount discounts, free shipping, free gifts, and buy-X-pay-Y rules, along with coupon codes and promotion rules applied at checkout.

- **Human URL:** [https://docs.commercelayer.io/core/api-reference](https://docs.commercelayer.io/core/api-reference)
- **Base URL:** `https://yourdomain.commercelayer.io/api`

#### Tags

- Promotions
- Discounts
- Coupons

#### Properties

- [Documentation](https://docs.commercelayer.io/core/api-reference)
- [API Reference](https://docs.commercelayer.io/core/api-reference)
- [OpenAPI](openapi/commercelayer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/commercelayer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercelayer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Commerce Layer Webhooks API

Subscribe to event topics (e.g. orders.place, orders.approve) and receive signed POST callbacks to a callback_url, with a per-webhook circuit breaker (circuit_state) that opens after repeated delivery failures.

- **Human URL:** [https://docs.commercelayer.io/core/real-time-webhooks](https://docs.commercelayer.io/core/real-time-webhooks)
- **Base URL:** `https://yourdomain.commercelayer.io/api`

#### Tags

- Webhooks
- Events
- Callbacks

#### Properties

- [Documentation](https://docs.commercelayer.io/core/real-time-webhooks)
- [API Reference](https://docs.commercelayer.io/core/api-reference/webhooks)
- [OpenAPI](openapi/commercelayer-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/commercelayer.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/commercelayer.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/commercelayer)
- [LinkedIn](https://www.linkedin.com/company/commerce-layer)
- [Website](https://commercelayer.io)
- [Documentation](https://docs.commercelayer.io)
- [Plans](plans/commercelayer-plans-pricing.yml)
- [Rate Limits](rate-limits/commercelayer-rate-limits.yml)
- [Fin Ops](finops/commercelayer-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
