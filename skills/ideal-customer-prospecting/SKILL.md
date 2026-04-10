---
name: ideal-customer-prospecting
description: Define an ideal customer profile, qualification rules, sourcing criteria, and first target list for B2B sales. Use when the user asks who to target, who to disqualify, how to prioritize accounts or contacts, how to score fit, or how to build an initial prospect list.
---

# Ideal Customer Prospecting

## Overview

Use this skill to decide who should be in the funnel before writing outreach or booking meetings.

The goal is to spend time on accounts that are likely to have the problem, urgency, and operating shape needed for success.

## When to Use

- Use when the user needs an ICP, account scoring, qualification logic, or an initial prospect list.
- Use when the current targeting is driven by convenience, personal network, or vague market size.
- Use when prospecting needs clearer required traits, positive signals, and disqualifiers.

## When Not to Use

- Do not use when the user already has a strong ICP and only needs copywriting.
- Do not use when the task is mainly inbound triage or outbound sequencing.
- Do not use when there is no clear business problem yet; clarify the narrative first.

## Inputs

- Product and core problem
- Buyer role or user role
- Known customer examples, if any
- Any known exclusions, segment limits, or deal size constraints

## Workflow

1. Define the business pain precisely enough that someone can either have it or not have it.
   - If the prompt already defines the product and problem clearly, proceed from that context.
   - Only inspect local files when the user asks for company-specific grounding or the prompt is too thin to define the motion.
2. List required account traits:
   - team shape
   - workflow maturity
   - industry or segment fit
   - technical or process prerequisites
3. List positive demand signals:
   - headcount patterns
   - open roles
   - current tools
   - workflow complexity
   - budget or sophistication signals
4. List disqualifiers and anti-signals.
5. Convert the above into a simple scoring rubric using `references/icp-and-sourcing.md`.
6. Define the first contact map:
   - user
   - manager
   - economic buyer
   - operator or admin
7. Build discovery questions for the traits that are not outwardly visible.
8. Recommend the first sourcing motion:
   - where to look for accounts
   - what signals to verify
   - what order to prioritize
9. If the user asks for a target list, stop once there is enough evidence to produce a practical first wave; prefer a bounded, prioritized list over exhaustive market research.

## Output Contract

Return:

- `ICP summary`
- `Required traits`
- `Positive signals`
- `Disqualifiers`
- `Priority tiers`
- `Contact map`
- `Discovery questions`
- `First sourcing plan`

If the user asks for a list, produce a prioritized target list with reasoning, not an undifferentiated directory dump.

## Quality Bar

- Favor need over familiarity.
- Avoid “anyone with a heartbeat” targeting.
- Be explicit about why an account fits or does not fit.
- Keep disqualification logic just as visible as qualification logic.

## References

- Read `references/icp-and-sourcing.md` for the ICP worksheet, scoring model, and discovery question bank.
