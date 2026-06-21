---
name: Swan
---

# Swan layer — cold outreach

The Swan-specific execution for this skill. The Swan runtime loads this alongside the parent; other agents ignore it.

## Loading context

- Load the ICP and personas via `swan-get-icp-segments`.
- Pull the company and contact from the CRM (`hubspot-*` today; whatever CRM is connected).
- Pull sender voice via `swan-get-sender-instructions` and recent approved messages via `swan-get-message-examples`.
- Check org memory (`swan-get-memory`) for any saved outreach preferences.

## Building the sequence

Build outreach with `swan-build-sequence`:
- Set `outreachReasoning` on each step so the rationale is visible at review.
- Keep `sendAutomatically: false` — the user approves before anything sends.
- Save a strong result back as a style example with `swan-save-message-example`.

## Setup state

No standing org config beyond sender voice. If no ICP or value prop is defined, this skill's quality drops — point the user to the ICP setup before running, and record any outreach defaults to memory via `swan-update-memory`.
</content>
