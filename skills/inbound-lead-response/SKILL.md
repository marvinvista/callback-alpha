---
name: inbound-lead-response
description: Qualify inbound leads, route them to the right next step, and draft fast response copy for early B2B sales. Use when the user asks how to respond to a form fill, referral, reply, or demo request, or needs triage, lightweight discovery, follow-up timing, or polite disqualification.
---

# Inbound Lead Response

## Overview

Use this skill to keep inbound from becoming a slow, messy queue.

The output should tell the seller what to do next and give them the exact response to send.

## When to Use

- Use when a lead submits a form, asks for a demo, replies to outreach, or arrives through a referral.
- Use when the user needs qualification, response copy, routing, or lightweight discovery.
- Use when speed to response matters.

## When Not to Use

- Do not use for broad outbound campaigns.
- Do not use for late-stage negotiation or close strategy.
- Do not use when there is no qualification framework yet; define ICP first.

## Inputs

- Lead source
- What the lead asked for
- Known company and role details
- Qualification criteria
- Desired next step

## Workflow

1. Capture the source and the lead’s explicit request.
2. Judge fit using the triage model in `references/inbound-triage.md`.
3. Classify the lead:
   - hot
   - warm
   - unclear
   - disqualified
4. If the prompt already includes enough detail, classify directly and avoid unnecessary repo searches or extra qualification loops.
5. Draft the fastest useful response for that class.
6. If fit is plausible but incomplete, ask a short set of discovery questions.
7. Recommend the next step:
   - book a meeting
   - request more detail
   - redirect
   - politely disqualify
8. Add follow-up timing if the lead goes quiet.

## Output Contract

Return:

- `Lead classification`
- `Why it fits or does not fit`
- `Response draft`
- `Discovery questions`
- `Recommended next step`
- `Follow-up timing`

## Quality Bar

- Move quickly.
- Avoid over-qualifying hot leads into delay.
- Avoid over-investing in poor-fit leads.
- Keep discovery short enough that the lead still feels momentum.

## References

- Read `references/inbound-triage.md` for the routing matrix and response patterns.
