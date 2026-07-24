---
name: Create and charge a Dojo payment
description: Create a payment intent, charge it, and confirm capture using the Dojo API.
api: openapi/dojo-api.json
operations: [PaymentIntents_CreatePaymentIntent, PaymentIntents_ChargePaymentIntent, PaymentIntents_Get, Captures_Create]
---

# Create and charge a Dojo payment

Use the Dojo API (`https://api.dojo.tech`) to take a card payment.

## Auth
Send `Authorization: Basic <api_key>` on every request. `Basic ` is a literal
prefix — do **not** base64-encode the key. Use a `sk_sandbox_` key for testing and
`sk_prod_` for live. Set the `version` header (latest `2026-02-27`).

## Steps
1. **Create a payment intent** — `PaymentIntents_CreatePaymentIntent`. Supply the
   `Money` amount/currency and any customer/config details. The intent starts in
   `Created`. Send an `IdempotencyKey` header so retries are safe.
2. **Charge the intent** — `PaymentIntents_ChargePaymentIntent` with the payment
   method. On success the intent moves to `Authorized` (or `Captured` if auto-capture).
3. **Capture (if manual)** — `Captures_Create` to capture an `Authorized` intent.
4. **Confirm** — `PaymentIntents_Get` and check `status` (`Captured`).

## Notes
- A declined authorization leaves the intent in its prior status — it does **not**
  transition to a `declined` status, so branch on the charge response, not intent status.
- Errors are JSON; handle `409` (state conflict / duplicate IdempotencyKey) and `422`.
- Test with sandbox cards from `sandbox/dojo-sandbox.yml`.
