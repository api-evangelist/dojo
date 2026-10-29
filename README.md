# Dojo

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

Dojo is a United Kingdom payments company (Paymentsense trading as Dojo, headquartered in London) that provides card acquiring and payment processing for in-person, online, and omnichannel merchants. It combines Dojo card machines and terminals, a payment gateway, and merchant tooling (bookings, EPOS integrations, business banking-style accounts) into a single acquirer-processor stack aimed at UK small and mid-market businesses and hospitality. Dojo is genuinely API-native and publishes a public developer portal at docs.dojo.tech with a REST API for payment intents, customers, refunds, captures, terminals, and webhooks, alongside separate specs for transactions, EPOS data ingestion, and Tap to Pay on iPhone. Authentication is a secret API key sent in the Authorization header (sandbox sk_sandbox_ and production sk_prod_ prefixes), and the platform supports webhook event subscriptions. Positioned within the UK's dense card-acquiring and PSP cluster alongside players like Checkout.com and SumUp.

**Areas:** Payments · United Kingdom · Payment Gateway · Payment Processing · Acquiring · Card Payments · In-Person Payments · Point-of-Sale · Webhook · Real-Time · Payment Terminals

## Dojo on APIs.io

Everything profiled for Dojo is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/dojo/](https://apis.io/providers/dojo/)** — or go straight to one of the APIs or properties below.

### APIs (19)

- [Dojo Areas API](https://apis.io/apis/dojo/dojo-areas-api/) — The Areas API from Dojo — 1 operation(s) for areas.
- [Dojo Capabilities API](https://apis.io/apis/dojo/dojo-capabilities-api/) — Register your REST and WebSockets endpoints.
- [Dojo Captures API](https://apis.io/apis/dojo/dojo-captures-api/) — Allows you to capture the full payment amount or part of the amount. **Documentation**: [Captures](../../payments/manage-payments/capture)
- [Dojo Customers API](https://apis.io/apis/dojo/dojo-customers-api/) — Allows to create and manage a customer of your business.
- [Dojo Events API](https://apis.io/apis/dojo/dojo-events-api/) — The Events API from Dojo — 1 operation(s) for events.
- [Dojo Flows API](https://apis.io/apis/dojo/dojo-flows-api/) — The Flows API from Dojo — 2 operation(s) for flows.
- [Dojo Orders API](https://apis.io/apis/dojo/dojo-orders-api/) — The Orders API from Dojo — 7 operation(s) for orders.
- [Dojo Parties API](https://apis.io/apis/dojo/dojo-parties-api/) — The Parties API from Dojo — 3 operation(s) for parties.
- [Dojo Payment intents API](https://apis.io/apis/dojo/dojo-payment-intents-api/) — Allows you to take and manage payments. **Documentation**: [Payment intents](../../payments/manage-payments/payment-intent)
- [Dojo Refunds API](https://apis.io/apis/dojo/dojo-refunds-api/) — Allows you to create a refund for a captured payment. **Documentation**: [Refunds](/payments/manage-payments/cancelling-payments/refund)
- [Dojo Reservations API](https://apis.io/apis/dojo/dojo-reservations-api/) — The Reservations API from Dojo — 3 operation(s) for reservations.
- [Dojo Reversal API](https://apis.io/apis/dojo/dojo-reversal-api/) — Allows you to create a reversal for payments. **Documentation**: [Reversal](../../payments/manage-payments/cancelling-payments/reversal)
- [Dojo Setup intents API](https://apis.io/apis/dojo/dojo-setup-intents-api/) — Allows you to setup a card for future payments. **Documentation**: [Setup intent](../payments/manage-payments/setup-intent)
- [Dojo Tables API](https://apis.io/apis/dojo/dojo-tables-api/) — The Tables API from Dojo — 1 operation(s) for tables.
- [Dojo Tap to Pay on iPhone API](https://apis.io/apis/dojo/dojo-tap-to-pay-on-iphone-api/) — Allows you to create a terminal secret value.
- [Dojo Terminal sessions API](https://apis.io/apis/dojo/dojo-terminal-sessions-api/) — Allows you to manage sessions on the terminal.
- [Dojo Terminals API](https://apis.io/apis/dojo/dojo-terminals-api/) — Allows you to manage payments on the terminal. **Documentation**: [Terminals](../payments/accept-payments/in-person-payments/pay-at-counter/terminals)
- [Dojo Transactions API](https://apis.io/apis/dojo/dojo-transactions-api/) — Allows you to take and manage payments.
- [Dojo Webhooks API](https://apis.io/apis/dojo/dojo-webhooks-api/) — Webhooks notify you when a specific event has occurred. **Documentation**: [Webhooks](../../development-resources/webhooks)

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [EPOS Data API (WebSockets)](https://apis.io/asyncapis/dojo/dojo-epos-data-asyncapi/)

#### Event channels (22)

Individual events and webhooks the provider emits.

- [CancelOrderByIdV1](https://apis.io/channels/dojo/cancelorderbyidv1/)
- [CreateOrderLockV1](https://apis.io/channels/dojo/createorderlockv1/)
- [CreateOrderV1](https://apis.io/channels/dojo/createorderv1/)
- [CreatePartyV1](https://apis.io/channels/dojo/createpartyv1/)
- [CreateReservationV1](https://apis.io/channels/dojo/createreservationv1/)
- [DeleteOrderLockV1](https://apis.io/channels/dojo/deleteorderlockv1/)
- [DeletePartyByIdV1](https://apis.io/channels/dojo/deletepartybyidv1/)
- [DeleteReservationByIdV1](https://apis.io/channels/dojo/deletereservationbyidv1/)
- [ExtendOrderLockV1](https://apis.io/channels/dojo/extendorderlockv1/)
- [GetOrderBillByIdV1](https://apis.io/channels/dojo/getorderbillbyidv1/)
- [GetOrderByIdV1](https://apis.io/channels/dojo/getorderbyidv1/)
- [GetPartyByIdV1](https://apis.io/channels/dojo/getpartybyidv1/)
- [GetReservationByIdV1](https://apis.io/channels/dojo/getreservationbyidv1/)
- [HandleEventV1](https://apis.io/channels/dojo/handleeventv1/)
- [ListAreasV1](https://apis.io/channels/dojo/listareasv1/)
- [RecordOrderPaymentByIdV1](https://apis.io/channels/dojo/recordorderpaymentbyidv1/)
- [SearchOrdersV1](https://apis.io/channels/dojo/searchordersv1/)
- [SearchPartiesV1](https://apis.io/channels/dojo/searchpartiesv1/)
- [SearchReservationsV1](https://apis.io/channels/dojo/searchreservationsv1/)
- [SearchTablesV1](https://apis.io/channels/dojo/searchtablesv1/)
- [UpdatePartyV1](https://apis.io/channels/dojo/updatepartyv1/)
- [UpdateReservationV1](https://apis.io/channels/dojo/updatereservationv1/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [dojo](https://apis.io/servers/dojo/dojo/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Dojo Agentic Access](https://apis.io/agentic-access/dojo/dojo-agentic-access/)

#### Collections (5)

Postman and Open Collection request collections.

- [Dojo API](https://apis.io/collections/dojo/open-dojo-api/)
- [EPOS Data API (REST)](https://apis.io/collections/dojo/open-dojo-epos-data-api/)
- [EPOS Tester](https://apis.io/collections/dojo/open-dojo-epos-tester-tool-api/)
- [Tap to Pay on iPhone](https://apis.io/collections/dojo/open-dojo-tap-to-pay-on-iphone-api/)
- [Transaction API](https://apis.io/collections/dojo/open-dojo-transactions-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Dojo Api Overlay](https://apis.io/overlays/dojo/dojo-api-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Dojo Authentication](https://apis.io/security/dojo/dojo-authentication/)
- [Dojo Domain Security](https://apis.io/security/dojo/dojo-domain-security/)
- [Dojo Vulnerability Disclosure](https://apis.io/security/dojo/dojo-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://dojo.tech/)
- [Documentation](https://docs.dojo.tech/docs)
- [Getting started](https://docs.dojo.tech/get-started)
- [API reference](https://docs.dojo.tech/api)
- [Pricing](https://dojo.tech/pricing/)
- [Sign up](https://developer.dojo.tech/signup)
- [Support](https://support.dojo.tech/hc/en-gb)
- [Changelog](https://docs.dojo.tech/changelog)
- [Blog](https://dojo.tech/blog/)
- [Terms of service](https://docs.dojo.tech/development-resources/terms-and-conditions)
- [Privacy policy](https://dojo.tech/legal/privacy-policy/)
- [GitHub](https://github.com/dojo-engineering)
- [Status](https://status.dojo.tech)

## API Evangelist rating

**Kin Score 53.6** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 60.6 |
| Contract governance | 4.5 |
| Operational transparency | 52.6 |
| Developer ergonomics | 61.3 |
| Access clarity | 38.2 |

**Agent readiness 35.8** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | derived (partial credit) |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 27.7** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/dojo/](https://apis.io/providers/dojo/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Dojo: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/dojo/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
