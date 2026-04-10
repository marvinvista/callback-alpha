---
name: sales-narrative
description: Build or revise a B2B sales narrative by clarifying the problem, buyer, status quo, why-now shift, proof, and pricing logic. Use when the user asks for positioning, messaging, an elevator pitch, a first-call story, a sales deck storyline, or a sharper explanation of why customers should buy.
---

# Sales Narrative

## Overview

Use this skill to turn rough product context into a coherent sales story that someone can say out loud, put into slides, and repeat consistently.

The goal is not clever copy. The goal is a durable narrative that explains the pain, the buyer, why existing approaches fall short, what changed, why this product is better, and how to talk about value without hand-waving.

## When to Use

- Use when the user has a product, feature, or company idea and needs the core sales story.
- Use when creating or revising an elevator pitch, sales deck outline, demo opener, or pricing framing.
- Use when the current explanation sounds feature-heavy, generic, or hard to repeat.

## When Not to Use

- Do not use when the user only wants line edits on existing copy.
- Do not use when the work is really prospect selection, outbound sequencing, or pipeline cleanup; route to the narrower skill.
- Do not use when the product itself is still too unclear to state the problem and buyer with any confidence.

## Inputs

- Product description and target user
- The main pain or workflow being addressed
- Known competitors, substitutes, or status quo behaviors
- Any proof points, customer evidence, or pricing assumptions already available

If the user does not provide all of these, infer a draft but label assumptions clearly.

## Workflow

1. Define the problem in plain language.
2. Specify the buyer and the team that feels the pain most directly.
3. Identify the current alternative:
   - no solution
   - manual process
   - service provider
   - incumbent product
4. Explain why the current approach is insufficient.
5. State what changed in the market, workflow, or technology such that a better approach now makes sense.
6. Explain how the product works in buyer language, not internal architecture language.
7. Add proof:
   - quantitative proof if available
   - qualitative proof if quantitative proof is thin
   - explicit evidence gaps if proof is still weak
8. Frame pricing in relation to value, budget logic, or alternative costs.
9. Produce the final narrative pack using the structure in `references/narrative-framework.md`.

## Output Contract

Return a compact narrative pack with:

- `Problem`
- `Buyer`
- `Current Alternative`
- `Why Change Now`
- `How It Works`
- `Why It Is Better`
- `Proof`
- `Pricing Frame`
- `30-second pitch`
- `2-minute pitch`
- `Sales deck storyline`

Keep it grounded. If proof is weak, say so. If pricing logic is speculative, say so.

## Quality Bar

- Prefer sharp problem statements over aspirational slogans.
- Tie claims to buyer pains and concrete workflows.
- Avoid feature lists masquerading as messaging.
- Do not present invented proof as real proof.
- Do not bury assumptions.

## References

- Read `references/narrative-framework.md` for the narrative skeleton, proof checklist, and pricing framing prompts.
