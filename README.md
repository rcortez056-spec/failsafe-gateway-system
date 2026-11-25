# Fail-Safe Gateway System (Demo)

A simulated routing gate for agent workflows. It validates an incoming payload, passes clean payloads forward, and flags failed payloads for human review.

## Live Demo
https://ramon-fail-safe.netlify.app: browser demo with scripted scenarios. It makes no live API calls.

## What the Demo Does
- Validates form input before routing.
- Path A: passes clean payloads forward.
- Path B: when validation fails or the enrichment API times out, sets Status = Requires_Human_Review, logs the reason, and adds the item to an alert list.

## Planned (Not Yet Built)
- Credential and secret scanning
- Prompt-injection detection
- Quarantine queue
- Live enrichment API calls
- Persistent audit log and monitoring dashboard

## Stack
- Hosting: Netlify
