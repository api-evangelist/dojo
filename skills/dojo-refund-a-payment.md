---
name: Refund a Dojo payment
description: Issue a refund against a captured Dojo payment intent and confirm it.
api: openapi/dojo-api.json
operations: [PaymentIntents_Get, Refunds_Create, PaymentIntents_GetRefundById]
---

# Refund a Dojo payment

## Auth
`Authorization: Basic <api_key>` (literal `Basic ` prefix, not base64-encoded).
Set the `version` header.

## Steps
1. **Look up the intent** — `PaymentIntents_Get` to confirm it is `Captured` and
   read the refundable amount.
2. **Create the refund** — `Refunds_Create` with the amount (`Money`). Send a
   **unique** `IdempotencyKey` header per refund so retries do not double-refund.
3. **Confirm** — `PaymentIntents_GetRefundById` to read the refund status.

## Notes
- `IdempotencyKey` must be unique for each new refund on a payment intent.
- Handle `409` (conflict / duplicate key) and `422` (amount exceeds refundable).
