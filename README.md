# Dojo (dojo)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
