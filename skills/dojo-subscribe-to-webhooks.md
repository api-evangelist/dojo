---
name: Subscribe to Dojo webhooks
description: Register a webhook subscription and manage the signing secret to receive Dojo events.
api: openapi/dojo-api.json
operations: [Webhooks_Subscribe, Webhooks_GenerateSecret, Webhooks_ActivateSecret, Webhooks_GetAlSubscriptions]
---

# Subscribe to Dojo webhooks

## Auth
`Authorization: Basic <api_key>` (literal `Basic ` prefix, not base64-encoded).

## Steps
1. **Create a subscription** — `Webhooks_Subscribe` with your HTTPS callback URL
   and the event types you want (e.g. `terminal_session.status_updated`).
2. **Generate a signing secret** — `Webhooks_GenerateSecret`.
3. **Activate the secret** — `Webhooks_ActivateSecret` so Dojo signs deliveries with it.
4. **Verify** — `Webhooks_GetAlSubscriptions` to list active subscriptions.

## Notes
- Validate the signature on every inbound event using the active secret before
  processing; rotate via generate + activate.
- Payment-lifecycle and terminal-session state changes are delivered as events;
  treat delivery as at-least-once and dedupe on event id.
