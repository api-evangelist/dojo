# Dojo (dojo)

Dojo is a United Kingdom payments company (Paymentsense trading as Dojo, headquartered in London) that provides card acquiring and payment processing for in-person, online, and omnichannel merchants. It combines Dojo card machines and terminals, a payment gateway, and merchant tooling into a single acquirer-processor stack aimed at UK small and mid-market businesses and hospitality. Dojo is genuinely API-native, publishing a public developer portal at [docs.dojo.tech](https://docs.dojo.tech) with a REST API served from `https://api.dojo.tech`.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dojo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dojo/refs/heads/main/apis.yml)

## Tags

- Payments
- United Kingdom
- Payment Gateway
- Payment Processing
- Acquiring
- Card Payments
- In-Person Payments
- Terminals
- Point of Sale
- Webhooks

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

### Dojo API

Core REST payments API for accepting and managing card payments: payment intents, refunds, reversals, captures, customers, setup intents, terminals, terminal sessions, capabilities, and webhook event subscriptions. Authenticates with a secret API key in the `Authorization` header. Version 2026-02-27 (40 paths).

- **Human URL:** [https://docs.dojo.tech/api](https://docs.dojo.tech/api)
- **Base URL:** `https://api.dojo.tech`
- [OpenAPI](openapi/dojo-api.json)
- [Documentation](https://docs.dojo.tech/docs)
- [API Reference](https://docs.dojo.tech/api)

### Dojo Transaction API

Retrieves processed card transaction records for a merchant.

- **Human URL:** [https://docs.dojo.tech/transactions/api](https://docs.dojo.tech/transactions/api)
- **Base URL:** `https://api.dojo.tech`
- [OpenAPI](openapi/dojo-transactions-api.json)

### Dojo EPOS Data API

A REST contract a merchant's EPOS (point-of-sale) system implements so Dojo can read orders, tables, areas, parties, and reservations for hospitality integrations. The server is merchant-hosted. Version 1.0 (15 paths).

- **Human URL:** [https://docs.dojo.tech/epos-data/api](https://docs.dojo.tech/epos-data/api)
- [OpenAPI](openapi/dojo-epos-data-api.json)

### Dojo Tap to Pay on iPhone API

Supports Dojo's Tap to Pay on iPhone in-person acceptance flow.

- **Human URL:** [https://docs.dojo.tech/payments/accept-payments/in-person-payments/tap-to-pay/tap-to-pay-on-iphone/api](https://docs.dojo.tech/payments/accept-payments/in-person-payments/tap-to-pay/tap-to-pay-on-iphone/api)
- **Base URL:** `https://api.dojo.tech`
- [OpenAPI](openapi/dojo-tap-to-pay-on-iphone-api.json)

### Dojo EPOS Tester Tool API

Helper API for validating an EPOS integration against Dojo's EPOS Data contract.

- **Human URL:** [https://docs.dojo.tech/epos-tester-tool/api](https://docs.dojo.tech/epos-tester-tool/api)
- [OpenAPI](openapi/dojo-epos-tester-tool-api.json)

## Common Properties

- [Website](https://dojo.tech/)
- [Developer Portal](https://docs.dojo.tech)
- [Documentation](https://docs.dojo.tech/docs)
- [API Reference](https://docs.dojo.tech/api)
- [Getting Started](https://docs.dojo.tech/get-started)
- [Postman](https://docs.dojo.tech/development-resources/postman)
- [Change Log](https://docs.dojo.tech/changelog)
- [Status Page](https://status.dojo.tech)
- [GitHub Organization](https://github.com/dojo-engineering)
- [LinkedIn](https://www.linkedin.com/company/dojo-tech)

## Authentication

Secret API key sent in the `Authorization` header. Sandbox keys are prefixed `sk_sandbox_` and production keys `sk_prod_`; keys are generated in the Dojo developer portal.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
