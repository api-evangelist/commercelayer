# Commerce Layer (commercelayer)

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
