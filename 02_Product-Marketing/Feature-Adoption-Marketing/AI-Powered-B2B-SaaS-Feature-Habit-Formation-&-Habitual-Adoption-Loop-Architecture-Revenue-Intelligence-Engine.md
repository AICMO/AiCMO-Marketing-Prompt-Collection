# AI-Powered B2B SaaS Feature Habit Formation & Habitual Adoption Loop Architecture Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-40 min | **Tags:** feature-adoption, habit-formation, behavioral-design, product-marketing, NRR, PLG, user-psychology, retention, B2B-SaaS, churn-prevention

## Overview

Architects a full AI-powered habit formation program that transforms one-time feature activators into habitual power users — by identifying the behavioral gap between "tried once" and "uses weekly," designing psychologically-grounded re-engagement loops, and automating intervention sequences that create durable usage patterns. Use this when you have feature activation without retention: users who discovered and tried a feature but haven't formed the habit of using it regularly, leaving NRR expansion and churn prevention value on the table.

---

## Quick Copy-Paste Version

You are a senior product marketing strategist and behavioral design expert specializing in habit formation for B2B SaaS products. You understand that in enterprise software, there's a critical and often ignored gap between "feature activated" (user tried it once) and "feature habitual" (user uses it 3+ times per week, every week). This gap is where $M in NRR is silently destroyed.

Design a complete AI-powered habit formation architecture for the following situation:

**Product/Feature Context:**
- Product: [Your B2B SaaS product — e.g., Meridian, an AI-powered legal document management platform for in-house legal teams]
- Target Feature: [The feature where activation-to-habit gap exists — e.g., AI Contract Risk Analyzer — surfaces hidden liability clauses in uploaded agreements]
- Activation Rate: [% of eligible users who have used it at least once — e.g., 41% of accounts have tried it]
- Habitual Rate: [% using it 3+ times per week for 4+ consecutive weeks — e.g., only 11% meet this threshold]
- Gap Size: [Accounts in the dangerous middle — activated but not habitual — e.g., 30% of eligible accounts]
- Why the Habit Gap Exists: [Known or suspected reasons — e.g., users run it on the first contract they upload, get a result, then revert to manual review because they forget it exists when the next contract arrives]

Build all of the following:

1. **Habit Gap Diagnostic Framework**: Define exactly what "habitual adoption" means for this feature using frequency + recency + depth of use signals. Identify the 3 behavioral archetypes in the activation-without-habit cohort (e.g., Occasional Trialists, Workflow-Blockers, Forgetting Abandoners) and what distinguishes each.

2. **Trigger Architecture Using Nir Eyal's Hook Model**: Design the external and internal triggers for each archetype. External triggers = automated prompts from the product, email, or CS systems. Internal triggers = the emotional states or situational cues that should make users think of this feature unprompted. For each trigger: the specific signal, the channel, the message, and the psychology principle (e.g., variable reward, loss aversion, identity reinforcement).

3. **Habit Loop Reinforcement Sequence**: A 6-week automated re-engagement program for the habit gap cohort — week-by-week behavioral nudges across in-app, email, and Slack/Teams integration. Include: the trigger, the action you're driving, the reward mechanism, and the investment that increases switching cost.

4. **Micro-Win Scaffolding**: Design 3 progressively harder "micro-challenges" that move users from occasional use to habitual use by breaking the behavior into small, completable steps. For each: the task, the completion signal, the recognition moment (in-app badge, email congratulation, CS note), and the next step prompt.

5. **Habit Measurement Dashboard**: The 8 metrics that prove habit formation is working — distinguish between leading indicators (trigger response rate, week-2 repeat rate) and lagging indicators (30/60/90-day habitual adoption rate, NRR delta for habitual vs. activated-not-habitual cohorts at 6 months).

6. **Anti-Regression Early Warning System**: The behavioral signals that indicate a habitual user is slipping back toward occasional use — and the automated intervention that fires when those signals appear. Include at least 3 early warning signals and their specific response playbooks.

Output must be directly implementable in Amplitude or Mixpanel (behavioral segmentation), Pendo or Appcues (in-app triggers), and HubSpot or Intercom (email/chat sequences). Produce zero outputs that require a human to read and manually decide what to do next — every output must trigger an automated action.

---

## Advanced Customizable Version

### Role & Context

You are a world-class product marketing intelligence engine operating at the intersection of behavioral science, product analytics, and revenue marketing. You specialize in:

- **Behavioral design for enterprise SaaS**: Applying the Hook Model (Nir Eyal), Fogg Behavior Model (B=MAT: Behavior = Motivation × Ability × Trigger), and Tiny Habits methodology to product feature adoption in B2B contexts where multiple stakeholders complicate habit formation
- **Habit gap analytics**: Using product telemetry to precisely quantify the activation-to-habitual-use conversion funnel, identify where habit loops break, and attribute NRR outcomes to habit formation milestones
- **Multi-channel behavioral orchestration**: Coordinating in-app, email, Slack/Teams, and CS touchpoints based on real-time user behavioral signals — not time-based schedules
- **Cohort-level habit engineering**: Designing different habit formation paths for different user personas, seniority levels, and workflow contexts within the same account
- **Revenue attribution for behavioral programs**: Proving causality between habit formation rates and NRR, churn, expansion, and advocacy outcomes using cohort comparison methodology

You understand that B2B SaaS habit formation is fundamentally different from consumer app habits because: decisions are made by buying committees not individuals, "habits" must form across entire teams not just one user, workflows are prescribed by managers not self-selected, and the cost of forming a new habit must be justified to a skeptical VP who controls the renewal decision.

---

### Input Parameters

**PRODUCT CONTEXT:**
Product name & category: [e.g., Meridian — AI-powered legal document management for in-house legal teams at mid-market and enterprise companies]
Primary user persona: [e.g., In-House Counsel (daily users), Legal Operations Manager (weekly reviewers), General Counsel (monthly dashboard reviewers)]
Feature requiring habit formation: [e.g., AI Contract Risk Analyzer — autonomously surfaces hidden indemnification, IP assignment, and limitation-of-liability clauses in uploaded agreements, ranked by risk severity]
Feature release date: [e.g., GA released 7 months ago]
Current activation rate: [e.g., 43% of eligible accounts (Pro plan+) have had at least one attorney use the feature]
Current habitual adoption rate: [e.g., 12% of eligible accounts use it 3+ sessions per week across consecutive 4-week periods]
Habit gap population: [e.g., 31% of accounts — activated but not habitual — representing ~$2.4M in ARR at elevated churn risk]
Product analytics stack: [Amplitude / Mixpanel / Pendo / Heap / Segment + warehouse]
In-app messaging: [Pendo / Appcues / Intercom / Chameleon / Custom]
CRM + marketing automation: [HubSpot / Salesforce + Marketo / Gainsight]

**HABIT GAP ROOT CAUSE HYPOTHESES:**
Hypothesis 1: [e.g., Feature requires uploading individual documents — attorneys review batches of 8-15 contracts at once and the one-at-a-time workflow doesn't match their natural process]
Hypothesis 2: [e.g., Risk output isn't in a format attorneys can copy-paste into their internal approval memo — extra reformatting step creates friction at exactly the moment of value delivery]
Hypothesis 3: [e.g., No calendar or workflow anchor — attorneys have no natural trigger to "remember" to run the analyzer when a new contract arrives in their inbox]
Hypothesis 4: [e.g., Feature is perceived as "nice-to-have" verification rather than "essential first step" — positioning hasn't established it as the new standard of care]

**REVENUE STAKES:**
NRR data for habitual adopters: [e.g., 94% renewal rate at 12 months for accounts with habitual adoption vs. 67% for activated-not-habitual]
Expansion revenue correlation: [e.g., habitual adopters are 3.4x more likely to expand to additional practice groups within 6 months]
Churn risk quantification: [e.g., 31% habit gap cohort × 33% incremental churn = ~$792K ARR at risk if program doesn't convert]

---

### Execution Framework

#### Phase 1: Behavioral Segmentation & Archetype Definition

**Step 1.1 — Define Habitual Adoption Threshold**

Using your product analytics stack, define "habitual adoption" with precision:
- Minimum frequency: [e.g., 3+ feature sessions per week]
- Minimum consistency: [e.g., usage in at least 3 of 4 consecutive weeks]
- Minimum depth: [e.g., at least 2 documents analyzed per session, not just feature opened]
- Recency requirement: [e.g., last session within 14 days]

Create a single composite "Habit Score" (0–100) based on weighted frequency + consistency + depth + recency that can be queried in real-time from your analytics stack.

**Step 1.2 — Map the Behavioral Archetypes in the Habit Gap Cohort**

Segment the activation-not-habitual population into 3–4 archetypes based on behavioral signals:

**Archetype A — The Occasional Trialist**
- Behavioral signature: Used 1–3 times in first 2 weeks after activation, then no usage for 30+ days
- Root cause hypothesis: Novelty-driven activation; no workflow trigger established
- Intervention strategy: Re-anchor to a specific workflow trigger (e.g., "Run Analyzer every time a contract arrives from a new counterparty")

**Archetype B — The Workflow-Blocked User**
- Behavioral signature: Multiple sessions with short duration (<2 min), low document count, high exit rate before viewing results
- Root cause hypothesis: UX friction or output formatting issue prevents value delivery
- Intervention strategy: In-app guided workflow completion + friction audit alert to product team

**Archetype C — The Unconvinced Manager**
- Behavioral signature: One or two sessions, never returned — CRM data shows manager-level user, not practitioner
- Root cause hypothesis: User isn't the day-to-day operator; feature requires practitioner-level engagement that the manager can't personally evaluate
- Intervention strategy: Bypass the manager; activate a practitioner in the same account with a "try this for your team" sequence

**Archetype D — The Forgotten Feature User**
- Behavioral signature: Regular usage for 4+ weeks, then abrupt stop (often correlates with a personnel change, quarter end, or major project deadline)
- Root cause hypothesis: Context disruption broke the habit loop; no re-engagement trigger fired
- Intervention strategy: Re-engagement sequence triggered by absence signal (no usage for 14+ days after previous weekly use)

---

#### Phase 2: Hook Model Architecture by Archetype

Design the four-step Hook Model cycle for each archetype:

**THE HOOK MODEL FRAMEWORK:**
TRIGGER (External → Internal)
→ ACTION (Simplest behavior in anticipation of reward)
→ VARIABLE REWARD (Satisfies the craving while leaving some desire)
→ INVESTMENT (User puts something in that increases future return)

**Hook Design for Archetype A (Occasional Trialist):**

*External Trigger Sequence:*
- Day 1 after 30-day absence: In-app banner: "3 contracts reviewed this week by your peers at [similar company type] — here's what they found."
- Day 3 if no response: Email with subject "The clause that cost [real company, redacted] $280K last quarter" — links to anonymized risk report from your own customer base
- Day 7: Slack/Teams DM to the activating user: "Quick question: what's stopping you from making Risk Analyzer your first step on every new contract?"

*Internal Trigger Goal:*
Shift the user's internal trigger from "I should probably check this feature again" (weak, time-based) to "Whenever a new contract arrives, I feel uneasy if I haven't run it through the analyzer first" (strong, anxiety-anchored)

*Variable Reward:*
The risk report output is inherently variable — each contract produces a different risk profile. Design the output interface to emphasize the surprise element: "2 high-severity clauses found that most legal teams would have missed" rather than a predictable format.

*Investment Design:*
After the user reviews their third consecutive report, prompt them to: "Save your standard risk preferences so the analyzer learns which clause types matter most for your deal types." Each investment makes future outputs more personalized, increasing switching cost.

---

#### Phase 3: 8-Week Habit Formation Automation Sequence

Design a fully automated sequence triggered by cohort entry (any user with Habit Score < 40 after 30+ days since activation):

**Week 1 — Awareness Re-Trigger**
- Day 1: In-app contextual tooltip appears when user opens any contract: "Did you know you can analyze this contract for risk clauses in 90 seconds? [Run Analyzer]"
- Day 3 (if no response): Email — Subject: "Most [Legal Operations Managers / In-House Counsel] at companies your size use Risk Analyzer before every negotiation. You've tried it — here's what habitual users do differently."
- Day 5 (if opened email but didn't use feature): Personalized in-app modal with a pre-loaded sample contract from their industry with a "See what risk analysis looks like" one-click demo

**Week 2 — First Re-Engagement Session**
- Triggered when user runs analyzer again: Immediate post-analysis in-app prompt — "You just found [X] risk issues. Would you like us to send you a weekly digest of risk patterns across all your contracts?"
- If user opts in: Automated weekly email digest begins — this is the habit anchor
- Day 7 of Week 2 (if still no re-engagement): CS alert fires to the account's CSM with behavioral data summary and suggested outreach script

**Weeks 3–4 — Habit Anchor Formation**
- Goal: Establish a fixed weekly trigger
- Trigger: If user has contracts in the system that haven't been analyzed, send Monday morning alert: "[3 contracts in your workspace haven't been analyzed — take 4 minutes to check them before your weekly review call]"
- After each analysis session in this period: Micro-win celebration — progress bar toward "Risk Analysis Habit" badge with statement of how many hours saved vs. manual review

**Weeks 5–6 — Variable Reward Deepening**
- Introduce "Risk Intelligence" — a monthly report showing trends across all the user's analyzed contracts, with benchmarking against anonymized peers in the same industry
- This report is only available for users with Habit Score > 60 — making it an aspiration reward for users in the 40–59 range
- Prompt users with Habit Score 60+ to share a "risk insight" in the in-product community: social proof mechanism that attracts additional users

**Weeks 7–8 — Investment Completion**
- Prompt user to: (1) Set their "default risk focus areas" (IP, indemnification, jurisdiction, etc.), (2) Invite one colleague to review a shared risk report, (3) Create a "Risk Review" step in their contract workflow template
- Each completed investment generates a personalized "Risk Analysis Profile" — a portfolio of how they've used the feature that becomes an asset they'd lose by churning

---

#### Phase 4: Micro-Win Scaffolding Program

Design progressive micro-challenges to structure the journey from occasional to habitual:

**Challenge 1 — First Habit (Week 1-2):**
*Task:* Analyze 5 contracts using Risk Analyzer
*Completion Signal:* 5th analysis logged in product telemetry
*Recognition Moment:* In-app: "5 contracts analyzed — you've saved an estimated 2.5 hours of manual review. Here's your first Risk Insights report."
*Next Step Prompt:* "Now try analyzing a contract that's already in negotiation — see how it changes your redline priorities."

**Challenge 2 — Consistent Habit (Week 3-5):**
*Task:* Run Risk Analyzer at least 3x in each of 3 consecutive weeks
*Completion Signal:* Habit Score crosses 55 (frequency × consistency threshold)
*Recognition Moment:* Email + in-app: "You've established a consistent risk review habit — you're now in the top 18% of [product name] users by contract review coverage. Your average time-to-risk-identification is X minutes faster than the platform average."
*Next Step Prompt:* "Share your risk preferences to unlock personalized clause detection — the analyzer will start flagging your highest-priority risks first."

**Challenge 3 — Team Habit (Week 6-8):**
*Task:* Invite at least one colleague to review a Risk Analyzer output, or run 15 total analyses across 3 or more different contract types
*Completion Signal:* Second user in account reviews shared report, OR 15-analysis milestone reached with ≥3 contract categories
*Recognition Moment:* CS notification triggers personalized email from CSM: "You're now one of our most engaged Risk Analyzer users — I'd love to show you two advanced features that 94% of users at your usage level don't know about. Want 20 minutes this week?"
*Next Step Prompt:* Invitation to private "Power User" product beta — highest tier of investment and identity reinforcement

---

#### Phase 5: Anti-Regression Early Warning System

**Signal 1 — Frequency Drop Detection:**
*Trigger:* User with Habit Score > 60 shows no feature activity for 12+ days after previous weekly usage pattern
*Automated Response:* Day 1 of absence: In-app contextual prompt when user logs in — "You usually analyze contracts on [day of week] — you have [X] unreviewed contracts in your workspace." Day 5 of continued absence: Email — "Quick check-in: we noticed you haven't run Risk Analyzer this week. Is there something we can make easier?" with one-click "Schedule a quick demo of the new bulk upload feature" CTA.

**Signal 2 — Depth Regression (Sessions Without Completions):**
*Trigger:* 3 consecutive sessions where user opens analyzer but exits before viewing results (session duration < 90 seconds)
*Automated Response:* Workflow-friction alert fires to CS + product team. In-app prompt appears on 3rd failed session: "Looks like you ran into an issue — can you tell us in one click what stopped you?" (3-option quick feedback: "Too slow," "Results unclear," "Wrong document format"). Based on response, route to: automated help doc, 15-min screen share calendar link, or product bug report.

**Signal 3 — Account-Level Habit Collapse:**
*Trigger:* Account-wide Habit Score drops >20 points in any 30-day period (indicating personnel change, project end, or internal workflow shift)
*Automated Response:* CS escalation with account health alert. Automated email to admin user: "We noticed a change in how your team is using Risk Analyzer — has anything changed in your contract workflow? We want to make sure the tool is still working for you." CSM receives pre-built re-onboarding agenda for account review call.

---

### Measurement Framework

**Leading Indicators (Weekly Tracking):**
1. Trigger Response Rate: % of habit-gap users who take action within 48h of behavioral trigger (target: >22%)
2. Week-2 Repeat Rate: % of re-engaged users who use the feature again in week 2 after re-engagement (target: >45%)
3. Micro-Win Completion Rate: % of cohort completing each challenge milestone on schedule (target: >30% completing Challenge 1)
4. Habit Score Velocity: Average Habit Score increase per week for cohort (target: +8 points/week during active sequence)

**Lagging Indicators (Monthly/Quarterly Tracking):**
5. Habitual Adoption Conversion Rate: % of habit-gap cohort that reaches Habit Score > 70 within 90 days (target: >35%)
6. NRR Delta at 6 Months: Renewal rate differential between program participants who achieved habitual adoption vs. those who didn't (target: >15 percentage points)
7. Expansion Revenue Correlation: % of newly habitual users in accounts that expand within 6 months post-habit-formation vs. control (target: >2x expansion rate)
8. Program ROI: (Incremental NRR recovered from churn prevention + expansion triggered) ÷ (cost of automation infrastructure + CS time) (target: >400% ROI within 12 months)

---

## Example Input/Output

**Input Example:**

Product: Nexora — AI-powered procurement management platform for manufacturing companies (250–5,000 employees)
Feature: Supplier Risk Monitor — continuously scores all active suppliers on financial stability, regulatory compliance, and geopolitical exposure; flags deteriorating suppliers before they cause supply chain disruptions
Activation Rate: 38% of accounts on Enterprise plan (178 accounts)
Habitual Rate (weekly active, 3+ check-ins/week): 9% (42 accounts)
Habit Gap Cohort: 29% of Enterprise accounts (136 accounts), representing $4.1M ARR
Primary Root Cause Hypothesis: Procurement managers activated the feature during a supply chain scare, reviewed their top 10 suppliers, found no immediate red flags, and concluded "it's working in the background" — never established a proactive review habit

**Output Example (excerpt from Trigger Architecture):**

*External Trigger — Archetype A (Occasional Trialist who checked once, found no red flags, stopped):*

Trigger Signal: 21 days since last login to Supplier Risk Monitor, despite 3+ new suppliers added to account in that period
Channel: Email — sent at 9:07am Tuesday (optimized send time for procurement managers based on account engagement data)
Subject: "3 suppliers you added last month haven't been scored yet"
Preview: "One of them is in a region with elevated logistics disruption risk right now."
Body (120 words max): "Hi [First Name], you've added [X] new suppliers to Nexora since you last checked the Risk Monitor. One of them — [Supplier Name, obscured for privacy in this example but personalized in actual send] — operates in a region that's seen a 47% increase in logistics disruption incidents in the last 90 days. Suppliers that go unmonitored for more than 30 days are 3.8x more likely to cause a supply disruption event. [Open Risk Monitor →] It takes about 4 minutes to review your current exposure. Your peers in automotive manufacturing check their supplier scores every Monday morning."
CTA: "See My Supplier Scores" → deep links directly to Supplier Risk Monitor with new suppliers pre-selected

Internal Trigger Goal: The fear of a supply disruption event that "could have been prevented" — anchors to the professional anxiety of being caught off-guard by a supplier failure

Variable Reward Design: The score change since last check — each visit shows movement, creating genuine information value rather than a static dashboard

Investment Prompt (post-review): "Set up your weekly Monday morning risk digest — get a 90-second email summary of your highest-risk suppliers before your week starts. Takes 30 seconds to configure."

*Micro-Win Challenge 1 Completion Output:*

After procurement manager completes 5 supplier risk reviews in one week:
- In-app: "You've reviewed 5 suppliers this week — your supply chain risk coverage is now 67% (up from 23%). That puts you ahead of 78% of manufacturing companies your size."
- Email follow-up 2 hours later: "Here's what habitual Supplier Risk Monitor users do differently: they set a 'watch list' of their top 20 strategic suppliers and review it every Monday. Want us to auto-generate your watch list based on your spend data? [Build My Watch List →]"

---

## Success Metrics

- **Primary: Habitual adoption conversion rate** — target ≥35% of habit-gap cohort reaches habitual status (Habit Score >70) within 90 days of program entry
- **Revenue: Incremental NRR recovered** — compare 12-month renewal rate of program participants who achieved habitual adoption vs. matched control of non-participants; target ≥15 percentage point improvement
- **Leading indicator: Week-2 repeat rate** — target ≥45% of re-engaged users return in week 2; if below 30%, the trigger message or channel is failing and needs iteration
- **Engagement: Micro-win completion rate** — target ≥30% of cohort completing Challenge 1; if below 20%, the challenge is too hard or the reward too weak
- **Product signal: Habit Score velocity** — target average +8 Habit Score points per week for cohort during active 8-week sequence
- **Anti-regression effectiveness** — target <10% of users who achieve habitual status regress to occasional use within 60 days of achieving it

---

## Related Prompts

- [Feature Adoption Acceleration Program & In-App Behavioral Marketing](./AI-Powered-B2B-SaaS-Feature-Adoption-Acceleration-Program-&-In-App-Behavioral-Marketing-Revenue-Intelligence-Engine.md)
- [Feature Launch Playbook & Product Adoption Campaign Architecture](./AI-Powered-B2B-SaaS-Feature-Launch-Playbook-&-Product-Adoption-Campaign-Architecture-Revenue-Intelligence-Engine.md)
- [Product Adoption Milestone Email Sequence Architecture](../Product-Adoption-Marketing/AI-Powered-B2B-SaaS-Adoption-Milestone-Email-Sequence-Architecture-&-Usage-Triggered-Customer-Communication-Revenue-Intelligence-Engine.md)
- [Power User Development & Internal Champion Activation](../Product-Adoption-Marketing/AI-Powered-B2B-SaaS-Power-User-Development-&-Internal-Champion-Activation-Revenue-Intelligence-Engine.md)

---

## Integration Tips

- **Amplitude/Mixpanel**: Build the Habit Score as a computed user property using a formula combining event frequency (feature_used events in last 7 days), consistency (feature_used in each of last 4 weeks flag), and depth (median document_count per session). Query cohort membership in real time to trigger the appropriate archetype sequence.
- **Pendo/Appcues**: Set up behavioral guides that fire based on Habit Score range — Score 0–20 fires "re-discovery" tooltip series; Score 21–50 fires "consistency-building" modal; Score 51–70 fires "investment deepening" prompt; Score 70+ triggers "power user" unlock celebration.
- **HubSpot/Marketo**: Sync Habit Score from product analytics via API or Segment integration. Build smart lists for each habit archetype. Trigger the 8-week email sequence via enrollment workflow with Habit Score < 40 AND Days Since Last Use > 20 as the enrollment criteria. Suppress users who reach Habit Score > 70 (they've graduated).
- **Gainsight/Totango**: Configure the Anti-Regression Signal 3 (account-level Habit Score drop) as a CS health score alert. Feed Habit Score data into your customer health score model — habitual adoption of key features should be a leading indicator of renewal health, weighted appropriately.
- **Slack/Microsoft Teams (via Intercom or Zapier)**: Wire the Monday morning "reminder to review" nudge through Slack/Teams integration for users who have connected their workspace. In-tool nudges in the tools users already have open have 3–5x higher engagement than email for tactical prompts.
- **Zapier/Make**: For teams without a full CDP, use Zapier to bridge product analytics event webhooks → HubSpot contact property updates → enrollment in habit formation email sequences. Adds ~2-3 second latency but achieves the core automation without data engineering resources.

---

## Troubleshooting

**Problem: Habit Score is always the same — not moving despite the sequence running**
Solution: Audit your event tracking. Habit Score only moves if the underlying product telemetry events (feature sessions, document analyzed, session duration) are firing correctly. Use Amplitude's "User Lookup" or Mixpanel's "Explore User" to verify event data for 5–10 individual users in the cohort. If events are missing, the issue is instrumentation, not the marketing sequence.

**Problem: Week-2 repeat rate below 25% despite good Week-1 re-engagement**
Solution: The trigger fired correctly but the reward wasn't compelling enough to create motivation for return. Audit the variable reward: does each return visit show something genuinely new and interesting? If the output looks identical to the last visit, there's no information value driving return. Consider adding a "since last visit" delta view — show what changed in supplier scores, risk ratings, or peer benchmarks since the user's last session. Movement creates motivation; static dashboards don't.

**Problem: CS team is overriding automation and manually handling habit-gap accounts**
Solution: CS override of automation usually indicates one of two things: (1) the automated messages feel generic and CSMs are embarrassed to have them sent to their accounts, or (2) CSMs don't trust the Habit Score data. Fix (1) by adding more account-specific personalization to the trigger messages (pull actual supplier names, contract counts, or specific risk findings into the email body). Fix (2) by showing CSMs a 30-day retrospective of which accounts entered the habit gap cohort vs. which achieved habitual adoption, and what the NRR correlation was — data trust builds when the model is proven predictive.

---

## Version History
- v1.0: Initial creation (auto-generated)
