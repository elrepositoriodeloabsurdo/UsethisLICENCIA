# Example: Node.js SaaS → Apache 2.0

## Scenario
A B2B SaaS analytics platform built with Express + MongoDB + Stripe billing.

## Why Apache 2.0?
- All dependencies (Express, Mongoose, Stripe SDK) are MIT or Apache 2.0 — no copyleft contamination
- Stripe integration means commercial intent → need patent protection clause
- Stripe SDK is Apache 2.0, which is compatible going up but requires explicit patent grant coming down
- SaaS doesn't trigger AGPL network clause since you're not distributing the software
- Enterprise clients will accept Apache 2.0 without legal review friction

## Expected output
See `expected.json` for the full agent response.
