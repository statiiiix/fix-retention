# From diagnosis to an intervention

Use this as a selection guide. Recommend a mechanism only when the product, segment, cadence, evidence, and delivery capacity support it. [Research records](research.md) distinguish empirical findings, app patterns, and practitioner models.

## Choose the mechanism

| Diagnosis | Candidate intervention | Fit check / primary validation |
| --- | --- | --- |
| Users expect a different outcome | Clarify acquisition promise and qualify use cases | Compare source/use-case cohorts and customer expectations |
| Setup blocks first success | Actionable errors, assisted setup, useful defaults, recovery | Successful first value and time/effort to achieve it |
| Core result is unreliable or poor | Quality and reliability improvements | Successful useful outcomes, failures, support burden |
| Repeat action is beneficial but missed | Contextual prompt, plan, or forgiving goal | Another meaningful action at the natural interval |
| Progress is hard to perceive | Milestones, outcome digest, truthful recap | Perceived usefulness and sustained successful use |
| Relevant options are buried | Curated next actions, fresh findings, preference controls | Relevant task completion and repeat value |
| Repeated work adds friction | Saved configuration, reusable templates, integrations | Less effort per successful recurring job |
| Collaboration is central | First useful invitation, shared workflow, role handoff | Account-level completed work and adoption |
| Competition is wanted and appropriate | Comparable opt-in groups, personal bests, bounded challenges | Quality-adjusted progress across affected segments |
| Users lapse or return to a stale context | Resume work, repair setup, reset goals, re-onboard | A second value cycle after return |
| Payments fail | Existing payment recovery, clear update path | Recovered valid subscriptions and complaint burden |
| Need has ended or is seasonal | Pause, appropriate exit, relevant future reactivation | Customer fit, useful reactivation, economics |

Inspect friction, value, and reliability before defaulting to messaging. Do not manufacture a daily task for occasional or automatic value. Keep cancellation understandable and user choices effective. Credit real progress and deliver actual benefits.

## Streaks, goals, quests, and milestones

Use when repetition creates customer value and users can reasonably control the qualifying action. An optional weekly target or completed-project milestone may fit better than consecutive days. Supporting evidence: [achievable streaks](research.md#r01), [recovery](research.md#r02), [quality alignment](research.md#r07), [broken streaks](research.md#r24), and [flexibility](research.md#r26).

Specify the qualifying successful outcome, authoritative event, cadence, target choice, timezone and travel rules, day/week boundaries, late/offline events, duplicates, backfill policy, grace/repair rules, reset display, and exit controls. Keep actual completion history distinct from protected streak status. Handle product outages without blaming users. Totals or login timestamps cannot reconstruct missing daily completion history.

Explain why the target is attainable and worthwhile for this segment. Plan success feedback and an easy next action. Evaluate completion quality, returning after a lapse, durable value, and any reward cost. Define how a user might game the score and how you will detect deterioration. Do not claim a fixed streak duration creates a habit.

## Lifecycle email, push, in-app, and digests

Design the returning experience with the message. Specify:

1. **Audience and state:** eligibility tied to a validated value gap, account/recipient role, consent and preferences, available destination.
2. **Trigger and timing:** authoritative event or inactivity rule, natural cadence, entry/re-entry limits, timezone policy, and quiet hours.
3. **Content and action:** useful reason to return, draft copy, authenticated deep link, preserved context, localization and missing-data fallback.
4. **Exit and suppression:** successful action, changed lifecycle state, opt-out, deleted/ineligible account, unresolved service failure, expiry, duplicates, and lack of relevant content.
5. **Delivery:** shared cross-campaign/channel ledger and priority rules, per-recipient frequency cap, spacing, idempotency, expiry, retry behavior, and a final eligibility check immediately before sending.
6. **Measurement:** assigned eligible control where feasible, successful return action, another value cycle, unsubscribes/complaints, total contact load, and cost.

Define numeric inactivity and frequency policies as product-specific proposals, not universal defaults. A per-minute delivery rate limit does not replace a recipient cap. Recheck queued messages after consent changes or task completion; entry eligibility may be stale. Coordinate with existing digests before adding sequences. Propose one useful message before expanding to a sequence when evidence is limited. Opens/clicks diagnose message response; they do not establish retention.

For a sequence, specify each step's additional value and stop conditions. A low-pressure restart and optional help can be appropriate. Do not invent accomplishments, savings, recipient relationships, urgency, or progress. If baseline savings cannot be established, report completed work instead of estimated money saved. [LinkedIn](research.md#r16) and [recipient-level orchestration](research.md#r17) inform these requirements.

## Personalization and recurring discovery

For every rule, record `input/source | availability and coverage | freshness | inferred/declared meaning | eligibility | selection rule | explanation/control | fallback | outcome`.

Examples: role-based setup help, recommendations based on the declared job, a digest of newly relevant findings, or resuming a real unfinished task. Labels must distinguish collected fields from new instrumentation proposals. Explicit interests may correct misleading activity; account behavior is not necessarily an individual preference. Start with transparent rules when data is sparse. Advanced ranking or bandits require sufficient feedback and a demonstrated decision benefit.

Refresh only when there is useful new material. Handle cold starts, low-confidence recommendations, negative feedback, and no-content cases. Measure useful outcomes and recommendation quality, not just novelty. See [Spotify](research.md#r11), [preference correction](research.md#r13), [Netflix](research.md#r15), and the [Hooked framework's limits](research.md#r34).

## Social mechanics and stored value

Establish whether collaborators actually improve the job. Invitations should lead to a useful shared outcome. For goals or rankings, define comparable peers, privacy, opt-in/out, scoring quality, and a viable solo experience. Account-level measurement and assignment may be necessary. Avoid interpreting existing power-user networks as the largest reachable opportunity. See [Friend Streak](research.md#r06) and [Strava](research.md#r19).

Saved work, integrations, and reusable configurations should reduce future effort and improve results. Preserve appropriate export, pause, and exit paths. Consider maintenance and setup cost before recommending new infrastructure.

## Economics and durability

For each candidate, identify affected eligible users/accounts, likely benefit, uncertainty, engineering effort, operating cost, reward/discount cost, support implications, and margin impact where data exists. Use ranges or qualitative judgments when inputs are missing. Do not invent an ROI or import another app's lift.

Pair short-term action with the appropriate longer-term outcome. Watch for reward-day spikes, discount-dependent renewals, point farming, message substitution, and gains concentrated in already-heavy users. Include stop/adjust criteria. Keep a small set of priorities and explain the strongest rejected alternative.
