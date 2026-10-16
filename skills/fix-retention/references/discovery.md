# Product discovery and adaptive interview

## Inspect before assuming

Use repository instructions and existing product/marketing/customer context. Identify the product within a monorepo. Search relevant files with the available search tools; follow a real journey instead of dumping the repository into context.

Inspect:

- Landing pages, acquisition promises, pricing, intended use cases, and supported platforms.
- Signup, authentication, imports/integrations, empty states, onboarding, and the first useful result.
- Repeat workflows, saved work, collaboration, background jobs, output delivery, and errors.
- User/account identifiers, roles, plan and subscription lifecycle, preferences, data timestamps, and deletions.
- Event definitions and actual call sites; billing webhooks; mail templates, audience logic, queues, scheduled tasks, suppression, and unsubscribe behavior.
- Existing feedback, support summaries, cancellation reasons, experiment history, and prior retention decisions.

Schema fields indicate potential inputs, not populated or reliable data. A coded feature may not be deployed or enabled. Record uncertainty explicitly.

## Interview from the gaps

Ask the smallest next question whose answer changes diagnosis or prioritization. Use the actual structured-question tool exposed by the host; tool names and availability vary. If unavailable, show lettered or numbered choices and accept a free-text answer. Follow tool option limits. An unsubmitted default is not a response.

Useful starting questions, tailored after initial inspection:

| Unresolved issue | Example question | Example choices |
| --- | --- | --- |
| Customer job | What do customers most need to accomplish? | Product-specific outcomes; unsure |
| Cadence | When should a successful customer receive value again? | Daily; weekly; monthly; task/event-driven |
| Retention concern | What first made you suspect a retention problem? | Cancellations; missed value actions; declining output use; dashboard inactivity |
| Audience | Who needs the result and who pays? | Individual; team; administrator buying for others |
| Maturity | What evidence do we have? | Prelaunch; a few paying accounts; mature event/billing history |
| Constraints | What can we realistically change next? | Small fixes; one focused feature; broader product work |
| Data access | How should we inspect the detected analytics? | Existing authorized connection; authenticated dashboard; anonymized export; proceed provisionally |

Do not run this table as a mandatory questionnaire. Ask about user age, accessibility needs, channels, or local operating constraints only when material to the product. Do not infer sensitive traits from behavior.

## Walk the experience

When appropriate access exists, use an existing demo, sandbox, or approved account. Inspect mobile and desktop paths when relevant. Capture what the user sees, expected action, friction, evidence, and likely consequence. Do not initiate real charges, send invitations, or populate live customer accounts merely to complete a walkthrough.

Identify motivation, ability, and prompt gaps as hypotheses. Distinguish unnecessary friction from setup steps that are essential to producing a useful result. Verify that an email deep link reaches the relevant next action with understandable authentication and recovery.

## Qualitative evidence when numbers are sparse

Use existing interviews/support material or propose questions for customers with successful outcomes, blocked activation, and lapses. Ask about their latest real task: what triggered it, what they expected, what happened, what alternative they used, and what remains unfinished. Avoid leading questions such as “Would a streak make you return?”

Preparing an interview guide does not authorize contacting customers. Small samples can expose a concrete failure without supporting a precise prevalence or causal lift estimate.

## Product brief to retain

Record customer/role, desired outcome, acquisition promise, first-value event, repeat-value event or background outcome, cadence, monetization, constraints, available evidence, and unanswered questions. Separate active use from delivered value and paid renewal. For B2B, identify the account's adoption and renewal unit.
