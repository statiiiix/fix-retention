# Retention plan contract

Produce one product-specific plan that a founder and implementer can act on. Adjust length to complexity; preserve these decision fields rather than filling space. State unknowns explicitly. Do not invent code locations, metrics, infrastructure, or causal evidence.

## Decision first

Lead with the up to three best next actions. For each: problem, target segment, why now, evidence confidence, expected customer benefit, relative effort, and dependency. Distinguish validated fixes, hypotheses to test, and measurement/research work. Include “no product change yet” when justified. Avoid a laundry list of every possible mechanic.

## Product and evidence brief

Record the customer and buyer, job, acquisition promise, first/repeat value, natural cadence, relevant lifecycle states, business model, maturity, and constraints. Explain whether direct usage, automatic value, paid renewal, or a combination defines success.

Include evidence provenance: source/file and line or report/query, dates and environment, sample/coverage, metric definitions, access status, confidence, and gaps. Label observed, user-reported, inferred, and unknown. Explain limitations that could change the ranking.

## Diagnosis cards

For each main bottleneck provide:

- Observed pattern and affected eligible segment.
- Proposed explanation and customer consequence.
- Supporting evidence and important missing evidence.
- Strongest competing explanation.
- Observation or experiment that would disprove or weaken the diagnosis.

Use external app research as supporting mechanism evidence, with a direct source link and its evidence type. Explain why it fits this product. Company feature adoption is not a causal result for this SaaS.

## Intervention cards

For each selected intervention specify:

- Exact customer-facing behavior and where it appears in the journey.
- Audience, entry condition, cadence, relevant state transitions, and exit/fallback behavior.
- Personalization mapping to actual available fields; identify any new collection needed.
- Applicable mechanics from [interventions.md](interventions.md): for example streak recovery rules or send-time suppression.
- Actual code touchpoints and reuse opportunities; proposed new files clearly labeled as proposals.
- Dependencies, relative effort, rollout/rollback, owner or required capability, and acceptance criteria.
- Measurement: baseline or baseline-collection task, primary meaningful outcome, practical decision threshold, control/rollout design, assignment unit, eligibility, observation window, and guardrails.
- Sustained outcome after another relevant value cycle, plus post-incentive observation when applicable.
- Economics and customer burden; known costs and inputs still needed.

Targets proposed by the agent must be labeled proposals, not measured facts. Describe uncertainty in expected benefit. A numeric prioritization score is optional and cannot substitute for the reasoning.

## Sequence and rejected alternatives

Order work by dependencies and decisions: establish missing evidence, fix confirmed blockers, then run appropriate experiments. Specify what can happen independently and what needs a result first. Defer attractive but unsupported ideas and explain why. Honor actual user capacity rather than inventing calendar commitments.

The handoff must be implementable without another broad discovery exercise. Request a remaining essential decision specifically; otherwise provide a provisional plan and show what would change it.

## Save and resume

Use the project's documentation conventions; otherwise prefer `docs/retention/retention-plan.md`. Keep the plan readable. Store a dated snapshot and a compact decision log alongside it using established project conventions, or append them within the plan when simpler. Do not overwrite previous evidence without preserving its date and meaning.

Persist the metric contract, evidence references/retrieval dates, unresolved questions, selected interventions, experiment/rollout status, user decisions, and the next evaluation opportunity. Do not store credentials or unnecessary personal data.

On later invocations, read this state first, inspect what changed, and evaluate prior actions before proposing new ones. If no mature results exist, say so and identify the next useful observation. A saved next-review date is a planning note, not authorization to create an automation.

## Finish the run

Summarize the main diagnosis, priorities, evidence limits, saved artifact, and next decision. In plan mode, describe proposals as proposals. After authorized implementation, report actual changes, verification performed, and remaining rollout or measurement work. Do not claim retention improved before outcomes are observed.
