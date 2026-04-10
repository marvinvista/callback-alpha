---
name: outbound-appointment-setting
description: Draft outbound emails, call openers, voicemails, follow-up touches, and booking cadences for early B2B sales. Use when the user asks for cold outreach, appointment-setting sequences, objection responses for first meetings, or meeting invite and reminder copy.
---

# Outbound Appointment Setting

## Overview

Use this skill to turn a qualified target into a booked conversation through direct, high-activity outbound.

The output should be usable on the same day: a message pack, a cadence, and a clear ask for time on the calendar.

## When to Use

- Use when the user needs cold emails, call openers, voicemails, follow-ups, or a full outbound cadence.
- Use when the user knows who to target but needs help turning that into booked meetings.
- Use when appointment-setting objections are stalling first meetings.

## When Not to Use

- Do not use when the target account is not yet qualified.
- Do not use when the work is deeper sales-call prep or closing strategy.
- Do not use when the user only wants an ICP or target list.

## Inputs

- Product and core value
- Target account or segment
- Target role
- Pain signal or reason this account is relevant
- Desired call to action

## Workflow

1. Start with the qualified account and the reason it is qualified.
2. Write the opening hook around the buyer’s likely pain or context, not around the company origin story.
3. Draft:
   - first-touch email
   - call opener
   - voicemail
   - follow-up email
   - reminder or confirmation note
4. Build a short cadence using `references/outbound-cadence.md`.
5. Include direct asks for time on the calendar.
6. Prepare responses for the most likely appointment-setting objections.
7. If a meeting is booked, generate the invite title, agenda, and reminder note.

## Output Contract

Return:

- `First-touch email`
- `Call opener`
- `Voicemail`
- `Follow-up sequence`
- `Common objection responses`
- `Meeting invite copy`
- `Reminder note`

Keep the language direct and short enough that a seller could actually use it.

## Quality Bar

- Respect the prospect’s time.
- Lead with relevance, not company biography.
- Ask for a meeting clearly.
- Do not let “send me info” or “circle back later” end the motion without a next step.

## References

- Read `references/outbound-cadence.md` for a simple cadence, objection patterns, and invite checklist.
