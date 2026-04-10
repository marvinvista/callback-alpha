---
name: pipeline-hygiene
description: Keep a sales pipeline clean, prioritized, and learnable by identifying stale deals, missing next steps, close-lost calls, and follow-up gaps. Use when the user asks for a pipeline review, deal prioritization, stage cleanup, loss-reason discipline, or clearer next actions.
---

# Pipeline Hygiene

## Overview

Use this skill to separate real opportunities from clutter and make the next best actions obvious.

The goal is to preserve focus, shorten response times, and leave a useful record for future follow-up.

## When to Use

- Use when the user wants a pipeline review, next-step priorities, stale-deal cleanup, or close-lost discipline.
- Use when too many deals look active but few are genuinely moving.
- Use when the team needs tighter follow-up and better records for future re-engagement.

## When Not to Use

- Do not use when the issue is ICP definition or prospect sourcing.
- Do not use when the user needs a demo script or close plan for one active call.
- Do not use when there is no stage model at all; define one first.

## Inputs

- Pipeline export or deal list
- Stage definitions, if available
- Last-touch dates
- Known next steps or blocker notes
- Win/loss context, if available

## Workflow

1. Normalize stage meanings before judging deal quality.
2. Sort deals by urgency using:
   - last activity
   - next action clarity
   - stage age
   - deal quality
3. Flag:
   - untouched opportunities
   - opportunities with no real next step
   - deals that should be closed lost
   - deals worth re-prioritizing immediately
4. Require a concrete next action for every retained deal.
5. Capture a useful loss reason for dead deals using `references/pipeline-review.md`.
6. Preserve enough notes that future follow-up is easier.
7. Recommend a weekly review rhythm.

## Output Contract

Return:

- `Immediate priorities`
- `Stale deals`
- `Deals to close lost`
- `Required next actions`
- `Loss-reason themes`
- `Future follow-up notes`

## Quality Bar

- Protect time for the best opportunities.
- Do not keep fantasy deals alive for comfort.
- Record enough context that “future you” can re-enter the deal intelligently.
- Separate “not now” from “never” when possible.

## References

- Read `references/pipeline-review.md` for the review checklist, stage exit questions, and close-lost taxonomy.
