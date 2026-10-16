---
name: fix-retention
description: Use when a SaaS needs better customer retention, repeat usage, activation, reactivation, or churn diagnosis, including requests for streaks, retention emails, personalization, or engagement loops. Applies to product-level retention investigation and planning, with implementation when requested.
---

# Fix Retention

Understand why customers would keep receiving value before choosing a retention mechanic. Produce a product-specific, evidence-linked plan. **Default to investigation and planning; implement only when the user requests it.** Preserve existing authorization and project instructions.

## 1. Orient and ask

Read project instructions, product context, and any previous retention plan. Quickly locate the relevant app, core workflow, schema, billing, notifications, and analytics. Then use [discovery.md](references/discovery.md) to investigate and ask about unresolved context.

Use the host's native multiple-choice question tool when available in the current mode; otherwise offer concise numbered choices in chat. Tailor options to the product, allow uncertainty/free text where supported, and ask small adaptive batches. Do not ask the user to repeat what files or earlier answers already establish. Continue independent research while awaiting answers; do not finalize a diagnosis that depends on an unanswered essential question.

Establish the customer, buyer versus user, job, first value, repeat value, natural cadence, business model, and constraints. Check acquisition promises and source quality. **Low login frequency can coexist with successful automated or occasional use.** Identify the outcome customers should continue receiving.

## 2. Investigate the product and evidence

Follow acquisition → setup → first useful result → next value opportunity → lapse/renewal. Inspect relevant code, data models, jobs, integrations, and failure paths. When an app and appropriate access are available, walk the journey in a suitable sandbox and capture concrete friction; observe production without creating records or triggering messages unless authorized.

Use [analytics.md](references/analytics.md) to establish what is declared, wired, verified, and accessible. Prefer existing authorized read-only data, connectors, exports, or analytics dashboards. An installed SDK proves neither data collection nor account access. Confirm the property/project, environment, dates, filters, identity, and report semantics. Never expose credentials or expand access on your own.

When access or tracking is missing, identify the smallest missing evidence and explain the decision it enables. Suggest a connection or instrumentation plan when useful; continue with available evidence and explicit uncertainty. Do not make analytics setup a prerequisite for all useful recommendations.

## 3. Diagnose before selecting mechanics

Define meaningful retention at the appropriate user, account, or revenue level. Separate activation, ongoing value, reliability, acquisition mismatch, voluntary churn, payment failure, and reactivation. Adapt rigor to the available population and mature history: small products need individual journeys and qualitative evidence; sufficiently instrumented products can support cohorts and experiments.

For each leading diagnosis, state evidence, confidence, a competing explanation, and what would disprove it. Distinguish observed, user-reported, inferred, and unknown claims. Cite file locations and data/report provenance. Avoid causal conclusions from feature adopters versus non-adopters, circular streak metrics, or post-treatment-selected groups.

## 4. Design and prioritize

Read the synthesis in [research.md](references/research.md), then the relevant evidence records. Use [interventions.md](references/interventions.md) to turn suitable mechanisms into concrete proposals. Transfer the mechanism with its conditions; do not copy an app's feature or reported lift as a universal prescription.

Consider better product value, easier first success, progress, fresh relevance, saved work, collaboration, contextual prompts, forgiving goals, re-onboarding, and payment recovery. Select what addresses the actual bottleneck. Map personalization to available fields and truthful claims. Evaluate sustained outcomes, message burden, quality, operating cost, and margin where relevant.

## 5. Deliver a decision-ready plan

Follow [plan-contract.md](references/plan-contract.md). Lead with up to three highest-priority actions, then supporting evidence, exact intervention behavior, code touchpoints, measurement, sequence, and deferred ideas. Use fewer actions when evidence supports fewer. Include a no-change or measurement-first recommendation when justified.

Save in the project's established documentation location; otherwise use `docs/retention/retention-plan.md` when writable, or deliver inline. Keep a dated evidence snapshot and decision history so later runs assess what changed and whether prior interventions worked. Do not schedule ongoing monitoring unless requested.

Research is sufficient when the value loop is understood, relevant paths and available evidence are examined, major uncertainty is explicit, and each priority has a validation path. Spend effort where new evidence could change the decision; avoid artificial waiting and repeated searches with no decision value.

If implementation is requested, refresh affected assumptions and execute the authorized scope. Follow repository conventions and verification requirements, including any prohibition on creating test files. Report actual behavior verified and remaining limits. Sending campaigns, changing live tracking/billing, connecting new accounts, or deploying requires authorization for that action; planning alone does not grant it.
