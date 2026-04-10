# Sales Skills Rubric

Use this rubric for every case in `cases.yaml`.

## Pass / Fail Rule

Mark a case `pass` only if all three conditions hold:

1. `Route fit` passes.
2. `Contract coverage` passes.
3. No `critical fail` condition is triggered.

If any of those fail, mark the case `fail`.

## Core Checks

### 1. Route Fit

Pass if the answer clearly behaves like the intended skill and does not drift into neighboring work.

Examples:

- `sales-narrative` should not become ICP design or outbound copy.
- `ideal-customer-prospecting` should not become a messaging deck or cold email sequence.
- `inbound-lead-response` should not over-qualify a hot lead into delay.
- `sales-manager-readiness` should not jump straight into a hiring packet without first answering readiness.

### 2. Contract Coverage

Pass if the answer covers the skill’s required output sections in a meaningful way.

This does not require exact headings, but it does require the substance.

Examples:

- `demo-and-closing` must include a direct ask, not just objections and demo notes.
- `pipeline-hygiene` must identify next actions, not just comment on stale deals.
- `sales-hiring-profile` must include a scorecard and interview loop, not just candidate traits.

### 3. Quality And Actionability

Pass if the answer is concrete enough to use.

Look for:

- stage-appropriate recommendations
- direct next steps
- explicit tradeoffs or risks where relevant
- concise discovery questions rather than broad questionnaires

## Assumption Discipline

Mark this as `good` if the answer:

- labels speculation when data is missing
- avoids invented proof, invented customers, or fake metrics
- notes evidence gaps when the prompt is thin

Mark this as `bad` if the answer presents assumptions as facts.

Bad assumption discipline is a `critical fail` for skills that mention proof, metrics, or readiness.

## Critical Fail Conditions

Any one of these is an automatic `fail`:

- fabricated proof, customer names, or metrics
- missing a required decision when the prompt explicitly asks for one
- obvious adjacent-skill drift that leaves the requested task unanswered
- generic advice that ignores key prompt details
- contradicting the skill’s quality bar

## Skill-Specific Reminders

- `sales-narrative`: must state proof gaps when proof is weak
- `ideal-customer-prospecting`: must show disqualification logic, not just inclusion logic
- `outbound-appointment-setting`: must ask for a meeting clearly
- `inbound-lead-response`: must keep discovery short and preserve momentum
- `demo-and-closing`: must not skip the ask
- `pipeline-hygiene`: must separate real opportunities from fantasy deals
- `customer-success-renewals`: must tie plans to customer outcomes, not vendor activity
- `sales-metrics-inspection`: must name alternative explanations and missing data when relevant
- `sales-hiring-profile`: must fit the current motion, not fantasy scale
- `sales-onboarding-bootcamp`: must make repetition and checkpoints explicit
- `sales-manager-readiness`: must answer readiness before profile design and avoid title inflation
