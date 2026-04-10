# Contributing

Thanks for improving the revenue skills bundle.

## Contribution Rules

All contributions must be safe to publish.

Only submit content that is:

- original writing
- clearly licensed for redistribution
- stripped of customer, employer, or partner private information

Do not submit:

- copied or closely paraphrased book text
- paid course material
- private sales playbooks
- screenshots or exports from internal systems
- customer lists, deal data, or personal information

## Skill Change Standard

When editing a skill:

1. Keep `SKILL.md` concise and procedural.
2. Put detailed support material in `references/`.
3. Avoid turning one skill into multiple jobs.
4. Preserve the skill's output contract unless you also update evals.
5. Add or update eval cases when behavior changes materially.

## Before Opening A PR

1. Run the scrub checklist in `docs/SCRUB_CHECKLIST.md`.
2. Review the changed skill for scope creep.
3. Check that no private or source-tied strings were introduced.
4. Run at least one relevant prompt from `evals/sales-skills/cases.yaml`.
5. Update the eval pack if the expected behavior changed.

## Review Lens

Reviewers should prioritize:

- publishability
- route clarity
- actionability
- assumption discipline
- eval coverage

If a contribution is useful but too close to a private or copyrighted source, rewrite it before merge.
