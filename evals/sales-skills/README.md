# Sales Skills Eval Pack

This folder contains a lightweight evaluation pack for the 11 installed sales skills:

- `sales-narrative`
- `ideal-customer-prospecting`
- `outbound-appointment-setting`
- `inbound-lead-response`
- `demo-and-closing`
- `pipeline-hygiene`
- `customer-success-renewals`
- `sales-metrics-inspection`
- `sales-hiring-profile`
- `sales-onboarding-bootcamp`
- `sales-manager-readiness`

## Files

- `cases.yaml`: structured prompt set and skill-specific pass checks
- `rubric.md`: global pass/fail scoring guide

## How To Use

1. Pick a case from `cases.yaml`.
2. Run it against Codex or another evaluator.
3. Score the output using `rubric.md`.
4. Mark the case `pass` only if:
   - the answer stays within the intended skill boundary
   - all required contract sections are meaningfully covered
   - no critical fail condition is triggered

## Suggested Manual Runner

```bash
codex exec --skip-git-repo-check -s read-only "<prompt from cases.yaml>"
```

## Notes

- The prompts are designed to test routing, output quality, and scope control.
- Several cases are boundary cases meant to catch adjacent-skill drift.
- The pack assumes concise, decision-ready outputs rather than long generic essays.
