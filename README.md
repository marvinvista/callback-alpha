# Callback

Open-source Codex skills and evals for practical B2B revenue work.

`Callback` is designed to be adapted, not used as a black box. It gives revenue teams, RevOps operators, enablement leads, and builders working on go-to-market workflows a clean starting point they can copy into their own Codex setup and tailor to their buyers, process, and language.

## Who This Is For

Use this repo if you want a faster starting point for Codex skills that support work such as:

- sales messaging and narrative
- prospecting and qualification
- outbound and inbound response workflows
- demos, closing, and pipeline review
- customer success, hiring, onboarding, and manager readiness

It is most useful for teams that want reusable structure and eval coverage, but still need to adapt the wording, assumptions, and examples to match their own market.

## Start With The Closest Skill

Pick the nearest fit, then adapt it to your environment.

- `sales-narrative`: shape a first-call story, pitch, and deck storyline
- `ideal-customer-prospecting`: define who to target, who to exclude, and how to prioritize
- `outbound-appointment-setting`: draft cold outreach and meeting-booking copy
- `inbound-lead-response`: qualify inbound demand and send the right next reply
- `demo-and-closing`: prepare discovery, demo flow, pricing framing, and next-step asks
- `pipeline-hygiene`: clean up deals, stale opportunities, and next-step discipline
- `customer-success-renewals`: structure implementation, reviews, renewal prep, and expansion logic
- `sales-metrics-inspection`: diagnose funnel or rep issues from activity and conversion data
- `sales-hiring-profile`: define hiring profiles, scorecards, and interview loops
- `sales-onboarding-bootcamp`: create a sales ramp plan and training sequence
- `sales-manager-readiness`: assess when a motion is ready for sales management

## Quick Start

Copy one skill into your local Codex skills directory:

```bash
cp -R skills/inbound-lead-response ~/.codex/skills/
```

Or copy the full bundle:

```bash
cp -R skills/* ~/.codex/skills/
```

You do not need any extra harness or build tooling to use this bundle.

## How To Adapt A Skill

The fastest path is usually:

1. Choose the closest existing skill instead of starting from zero.
2. Copy it under a new folder name in your own skills directory.
3. Rewrite `SKILL.md` so the buyer, problem, constraints, and output match your workflow.
4. Update `agents/openai.yaml` so the metadata and routing match your renamed skill.
5. Replace any reference material with your own original support material.
6. Run the eval pack against the prompts closest to your use case.

As you adapt, keep these rules in mind:

- keep one skill focused on one job
- preserve a clear output contract
- prefer concrete operating guidance over generic advice
- rewrite examples and assumptions so they match your environment
- do not copy private playbooks, customer material, or copyrighted source text

## Validate Your Version

The eval pack lives in [evals/sales-skills/cases.yaml](evals/sales-skills/cases.yaml) and [evals/sales-skills/rubric.md](evals/sales-skills/rubric.md).

Use it to check:

- route fit
- contract coverage
- scope control
- assumption discipline

Suggested manual run:

```bash
codex exec --skip-git-repo-check -s read-only "<prompt from cases.yaml>"
```

If your adaptation changes the expected output shape, update the relevant eval case or rubric alongside it.

## Repo Layout

```text
skills/
  <skill-name>/
    SKILL.md
    agents/openai.yaml
    references/
evals/
  sales-skills/
    cases.yaml
    rubric.md
docs/
  SCRUB_CHECKLIST.md
CONTRIBUTING.md
LICENSE
```

## Publishing Standard

This repo is intended to contain only original skill instructions, metadata, and eval artifacts.

Do not add:

- copyrighted source text
- private notes copied from books, courses, or paid material
- customer data
- internal company documents
- proprietary playbooks without permission

Before publishing changes, run the checklist in [docs/SCRUB_CHECKLIST.md](docs/SCRUB_CHECKLIST.md).

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[MIT](LICENSE)
