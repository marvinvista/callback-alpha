---
name: sales-hiring-profile
description: Define sales hiring profiles, interview loops, scorecards, and compensation guardrails for stage-appropriate B2B sales roles. Use when the user asks who to hire for SDR, AE, customer success, or early management roles, how to interview them, or how to shape an offer and candidate-close plan.
---

# Sales Hiring Profile

## Overview

Use this skill to define who to hire, how to evaluate them, and how to close the right candidate without overhiring for the current stage.

The goal is to produce a hiring packet that is specific enough to guide sourcing, interviewing, and offers.

## When to Use

- Use when the user is about to hire an SDR, AE, CS role, or early manager.
- Use when the job spec is vague, overstuffed, or copied from a much larger company.
- Use when interview loops and scorecards need structure.

## When Not to Use

- Do not use when the user only wants generic recruiting copy.
- Do not use when the issue is onboarding or coaching after the hire is made.
- Do not use when the company has not clarified the role’s place in the sales motion.

## Inputs

- Role to hire
- Stage of sales motion
- Deal size and sales complexity
- Team structure
- Geography and market context, if relevant

## Workflow

1. Define the role in the current sales system:
   - what part of the motion it owns
   - what it should not own
2. Specify must-have capabilities and raw traits using `references/hiring-packet.md`.
3. Separate stage-appropriate needs from later-stage “nice to have” traits.
4. Design the interview loop:
   - screen
   - role-fit interview
   - practical exercise or mock
   - values or culture interview
   - close interview
5. Create a scorecard with clear pass, concern, and reject markers.
6. Set compensation and offer logic based on market and role economics.
7. Prepare the candidate-close plan.

## Output Contract

Return:

- `Role definition`
- `Must-have traits`
- `Red flags`
- `Interview loop`
- `Scorecard`
- `Compensation guardrails`
- `Offer and close plan`

## Quality Bar

- Hire for the actual motion, not for fantasy scale.
- Avoid generic “sales person is a sales person” thinking.
- Keep scorecards specific enough that interviewers can disagree usefully.
- Do not let compensation logic drift into one-off improvisation without reason.

## References

- Read `references/hiring-packet.md` for scorecard fields, interview prompts, and offer checklist.
