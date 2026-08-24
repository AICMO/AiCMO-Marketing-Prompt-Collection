# AI-Powered B2B SaaS Feature Adoption Signal Intelligence & Product-Led Expansion Revenue Architecture Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** feature-adoption, product-led-growth, expansion-revenue, product-marketing, usage-analytics, NRR, revenue-intelligence, PLG

## Overview
Builds a complete system for converting feature adoption data into expansion revenue signals — enabling product marketers and CS teams to identify the exact moments when customer usage patterns predict upsell readiness, churn risk, or cross-sell opportunity. Use this when your product has rich usage data sitting unused while expansion deals close slowly and CS teams operate on gut instinct rather than behavioral signals.

## Quick Copy-Paste Version

You are a senior product marketing strategist specializing in product-led expansion revenue for B2B SaaS companies. I need a complete feature adoption signal intelligence system for [Your Company].

Company context:
- Product: [Your Product] — [one-line value prop]
- Primary features: [List 5-8 core product features with their intended business outcome]
- ICP: [e.g., Operations leaders at Series B–D logistics companies, 100–800 employees]
- Current expansion motion: [e.g., CS team does quarterly business reviews, manual upsell identification]
- Data available: [e.g., Mixpanel/Amplitude events, Salesforce CRM, HubSpot, Gainsight health scores]
- Expansion goal: [e.g., increase NRR from 108% to 125% within 18 months]
- Average expansion deal size: [e.g., $18,000 ACV increase]

Deliver:

1. ADOPTION SIGNAL MATRIX — For each product feature, define: the usage threshold that indicates value realization vs. surface-level engagement, the behavioral pattern that correlates with expansion readiness (not just usage frequency — identify the specific sequence of actions that precede customers who expanded), and the inverse signals that predict churn risk within 90 days. Score each feature on a Value-Risk scale: high adoption = value delivered + expansion trigger; low adoption on a high-value feature = immediate churn risk.

2. EXPANSION REVENUE TRIGGER ARCHITECTURE — Design a signal-based expansion trigger system that fires when: (a) a customer reaches a feature adoption threshold that historically precedes expansion conversations, (b) a new team or department in the customer account starts using features designated for the higher tier, (c) a customer's usage growth rate exceeds the capacity of their current plan. For each trigger type: define the exact signal (event + threshold + timeframe), the automated action (sales alert vs. CS task vs. in-app message vs. email sequence), and the expected conversion rate based on signal type.

3. AI-POWERED USAGE INTELLIGENCE BRIEF — Design the automated account intelligence brief that fires to the CS/AE team when an expansion trigger activates: what usage data to include, how to frame the expansion conversation (business outcome language, not feature language), and what proof to attach (benchmarks showing what customers at this usage level typically achieve).

4. DARK ADOPTION RECOVERY SYSTEM — For features with low adoption that are critical to retention: design the AI-powered intervention sequence that detects the adoption gap, identifies the root cause (awareness, complexity, relevance, technical friction), routes to the correct intervention (in-app tooltip, email nurture, CS outreach, product feedback loop), and tracks lift.

5. PMM EXPANSION REVENUE REPORTING — Build the product marketing attribution model that proves PMM's impact on expansion revenue: what metrics to own, how to structure the monthly PMM → Expansion Revenue report, and what data to present to the CMO to demonstrate product marketing's contribution to NRR.

Format all outputs as deployable playbooks with specific thresholds, timeframes, and tool configurations.

## Advanced Customizable Version

ROLE: You are a product-led growth architect and product marketing revenue strategist who has built feature adoption signal systems that increased NRR by 15–25 percentage points within 18 months at multiple B2B SaaS companies. You understand that feature usage data is the highest-fidelity revenue signal available to modern SaaS companies — but only when properly instrumented, interpreted, and actioned through coordinated PMM, CS, and Sales workflows.

COMPANY CONTEXT:
- Company: [Company Name]
- Product category: [e.g., Revenue Operations / Workforce Management / DevOps / FinTech Infrastructure]
- Core value proposition (in measurable business outcome language): [e.g., "Logistics operations teams eliminate 65% of manual dispatch decisions by automating route optimization with real-time constraint handling"]
- Current ARR: [e.g., $8M]
- Current NRR: [e.g., 108%] | NRR target: [e.g., 125%]
- Seat/usage-based pricing structure: [e.g., per seat, usage tiers, module-based, consumption]
- Expansion levers available: [e.g., seat expansion, feature tier upgrades, usage overages, professional services add-ons]
- Product analytics tool: [e.g., Mixpanel, Amplitude, Heap, Pendo, PostHog, or custom data warehouse]
- CRM: [e.g., Salesforce, HubSpot]
- CS platform: [e.g., Gainsight, Totango, ChurnZero, Planhat, or spreadsheets]
- Customer segment breakdown: [e.g., 40% SMB <$10K ACV, 45% mid-market $10K–$50K ACV, 15% enterprise >$50K ACV]
- Core features (list each with its intended business outcome): [Feature 1: ___. Feature 2: ___. Feature 3: ___]
- Features locked to higher tiers: [e.g., Advanced Reporting (Tier 2), API Access (Tier 3), Multi-site Management (Enterprise)]
- Historical expansion data available: [e.g., yes — 24 months of expansion deal data in Salesforce]

OBJECTIVE: Build an AI-powered feature adoption signal system that converts product usage data into predictable expansion revenue triggers, identifies churn risk 60–90 days before renewal, and gives PMM a defensible attribution model for NRR contribution.

---

DELIVERABLE 1 — FEATURE ADOPTION SIGNAL MATRIX

A. FEATURE VALUE REALIZATION SCORING

For each product feature, build a three-layer adoption model:

Layer 1 — SURFACE ENGAGEMENT (Feature Opened, Not Adopted)
Define: The minimum interaction that indicates awareness but not value delivery.
Signal characteristics: Feature accessed 1–3 times in first 30 days, then abandoned. No workflow integration evident.
Revenue risk classification: HIGH — surface engagement with no value realization is the strongest predictor of non-renewal.

Layer 2 — FUNCTIONAL ADOPTION (Feature Used, Value Uncertain)
Define: The usage threshold that indicates the feature is part of the customer's workflow but hasn't yet created measurable business impact.
Signal characteristics: Regular usage (weekly+ for collaboration features; daily for operational features), but no downstream outcome signals detected (e.g., reports exported, workflows triggered, integrations activated).
Revenue risk classification: MEDIUM — functional adoption protects renewal but does not trigger expansion.

Layer 3 — VALUE REALIZATION (Feature Integral, Expansion Predictive)
Define: The usage pattern that correlates with customers who subsequently expand. This is not frequency alone — it is the specific sequence of actions that indicates the customer has restructured a business workflow around the feature.
Signal characteristics: [Build this from your historical expansion deal data — look for the 3–5 behavioral events that expansion customers completed in the 60 days before they initiated or agreed to an expansion conversation]
Revenue risk classification: LOW churn risk + HIGH expansion readiness signal.

B. BEHAVIORAL SEQUENCE ANALYSIS (EXPANSION PREDICTOR MODEL)

Extract from your 24 months of expansion deal data:

Step 1: Identify the 20 customers with the largest expansion deals (by ACV increase). Pull their complete usage event log for the 90 days preceding the expansion close date.

Step 2: Apply this AI analysis prompt to each customer's event log:
"Analyze this customer's product usage events from [90 days before expansion close]. Identify: (a) which features showed a distinct usage inflection point — a period where usage accelerated, not just continued; (b) which features were first adopted for the first time in this period; (c) which user roles (by job title or permissions level) began using the product for the first time in this period; (d) which downstream outcome events were triggered — exports, API calls, integrations activated, reports generated. Synthesize the common behavioral pattern across all 20 customers — what is the specific sequence of events that preceded expansion, and how early before expansion close did this sequence begin?"

Step 3: Build the Expansion Predictor Sequence — a 3–5 event sequence that, when detected in any account, triggers the expansion qualification workflow.

Example output structure (fill in with your data):
Expansion Predictor Sequence for [Feature Name]:
- Event 1: [Specific product action] — detected [X] days before expansion on average
- Event 2: [Specific product action] — detected [X-Y] days before expansion
- Event 3: [New user role type] first logs in — detected [X-Z] days before expansion
- Event 4: [Downstream outcome event] triggers — detected [X-W] days before expansion
- Confidence threshold: Sequence must complete within [N] days to qualify as high-confidence expansion signal

C. CHURN RISK SIGNAL IDENTIFICATION

Mirror the expansion predictor analysis for the 20 highest-value churned customers:

"Analyze this churned customer's product usage events from 90 days before their renewal date. Identify: (a) which features showed a usage decline of more than 30% from their peak adoption level; (b) which features were adopted and then abandoned (adopted for 30+ days, then not used for 30+ days before churn); (c) which user roles stopped logging in; (d) whether any key success milestones (first export, first integration, first automated workflow) were never achieved. Synthesize the common behavioral pattern — what is the specific sequence of decline events that predicted churn, and how early did this sequence become detectable?"

Build the Churn Risk Signal:
- Early warning indicator (60–90 days before renewal risk): [Specific usage pattern]
- Active churn risk indicator (30–60 days before renewal risk): [Specific usage pattern]
- Late-stage churn indicator (0–30 days, renewal at risk): [Specific usage pattern]
- Feature-level churn mapping: [Feature X abandonment = Y% churn correlation; Feature Y abandonment = Z% churn correlation]

---

DELIVERABLE 2 — EXPANSION REVENUE TRIGGER ARCHITECTURE

A. TRIGGER TYPE DEFINITIONS

Trigger Type 1 — EXPANSION READINESS SIGNAL
When: Customer completes the Expansion Predictor Sequence.
Automated action: Create Salesforce opportunity (stage: Expansion Qualified), assign to AE/AM, generate Account Intelligence Brief (see Deliverable 3), log CS task "Expansion conversation ready — initiate within 5 business days."
Expected conversion rate: [From your historical data — what % of customers who completed the predictor sequence expanded within 90 days?]
Not a trigger if: Account has an open expansion opportunity already in progress, account is in contract renewal within 30 days (route to renewal team instead).

Trigger Type 2 — SEAT/LICENSE CAPACITY SIGNAL
When: Customer's seat utilization exceeds [85%] of licensed capacity for [3+ consecutive weeks].
Automated action: Alert AE/AM via Slack: "Account [X] is at [Y%] seat capacity — [Z] active users on [N] licensed seats. Expansion conversation timing: now." Log CS outreach task. Do NOT auto-send customer-facing communications (AE must initiate with context).
Expected conversion rate: High — this is a capacity-constrained expansion, not value-based. Conversion rates are typically 60–80% if actioned within 2 weeks of signal.

Trigger Type 3 — TIER FEATURE DISCOVERY SIGNAL
When: A customer on Tier [X] begins consistently using a feature that is unlocked in Tier [X+1] as a trial (if you offer feature trials) OR attempts to access a feature that requires upgrade [3+ times in 30 days].
Automated action: In-app message (contextual, not modal): "[Feature name] is [showing you/letting you do X]. Customers who unlock the full [Feature] tier [achieve specific measurable outcome] on average within 60 days — want to see what that looks like for [Account Name]?" Log intent signal in Salesforce. Route to CS for expansion conversation if 2+ users triggered this in the same 30-day period.
Expected conversion rate: Medium — feature-discovery expansions require a value conversation, not just a pricing conversation.

Trigger Type 4 — MULTI-DEPARTMENT EXPANSION SIGNAL
When: Users from a new department or business unit (identified by email domain, SSO group, or self-reported department in profile) begin using the product.
Automated action: Alert AE/AM: "New department detected at [Account Name]. [X] users with [Department Y] in their profile have logged in this month. Current licensed departments: [A, B]. This may indicate organic expansion you haven't priced yet."
Expected conversion rate: Variable — requires investigation into whether usage is within current contract scope or represents an un-contracted expansion.

B. TRIGGER SUPPRESSION RULES (PREVENT OVER-TRIGGERING)

Before any trigger fires, check:
1. Is there an open expansion opportunity in Salesforce already? → Suppress duplicate trigger, add note to existing opportunity.
2. Is the account in a renewal window (30 days before or after renewal)? → Route to renewal conversation instead of expansion conversation.
3. Has this account been contacted about expansion in the last [45] days? → Suppress trigger, log as supporting data for next outreach.
4. Is the account tagged as "At Churn Risk" in Gainsight/CS platform? → Override expansion trigger with churn prevention priority — do NOT initiate expansion conversation with an at-risk account.

---

DELIVERABLE 3 — AI-POWERED ACCOUNT INTELLIGENCE BRIEF

When a Trigger Type 1 (Expansion Readiness Signal) fires, auto-generate this brief and deliver it to the assigned AE/AM via Slack and Salesforce:

ACCOUNT EXPANSION INTELLIGENCE BRIEF — [Account Name]
Generated: [Date] | Signal: Expansion Predictor Sequence Completed | Confidence: [High/Medium]

USAGE SUMMARY (Last 30 Days):
- Total active users: [X] of [N] licensed seats ([Y%] utilization)
- Feature adoption breadth: [X] of [Y] core features with active usage
- Highest-activity feature: [Feature name] — [X] sessions, [Y] outcomes generated
- Expansion trigger events completed: [List the specific events from predictor sequence]
- New users in last 30 days: [X] (new department/team detected: [Y/N])

BENCHMARK CONTEXT (FRAME THE VALUE CONVERSATION):
Customers at [Account Name]'s usage level and segment ([industry], [company size]) typically achieve:
- [Specific measurable outcome] within [X months] of this adoption stage
- Expansion customers at this stage average [Y%] improvement in [business metric]
- [Account Name]'s usage is [above/below/at] the median for their segment

RECOMMENDED EXPANSION CONVERSATION FRAME:
Do NOT open with pricing. Open with: "Based on what your team has built with [Product], you're at the stage where companies typically [specific business outcome]. I'd love to show you what [2-3 customers at similar stage] unlocked when they [expanded in this specific way]. Does that seem directionally interesting?"

EXPANSION OPTIONS RANKED BY FIT:
1. [Most likely expansion type] — [why it fits based on usage signals]
2. [Second option] — [why it fits]
3. [Third option — only if 1 and 2 aren't relevant]

RISK FLAGS:
- [Any churn indicators detected alongside expansion signals? Flag them.]
- [Any support tickets open? Flag them — do not start expansion conversation if critical ticket unresolved.]

---

DELIVERABLE 4 — DARK ADOPTION RECOVERY SYSTEM

A. ADOPTION GAP DETECTION

Weekly automated report: For every customer account, calculate:
"Feature Adoption Gap Score" = (Expected adoption based on customer ICP and use case) − (Actual adoption measured by event data)

Flag accounts where:
- A feature critical to their stated use case has <30% adoption after 90 days of access
- A feature with >80% adoption at peer accounts has <40% adoption at this account
- Any feature that was adopted and then abandoned (no events for 21+ consecutive days after 14+ days of prior usage)

B. ROOT CAUSE CLASSIFICATION

When an adoption gap is detected, run this AI diagnostic prompt:

"Customer [Account Name] has a feature adoption gap for [Feature Name]. Their usage data shows: [paste recent event log]. Their onboarding completion was: [X%]. Their support tickets related to this feature: [list any]. Their stated use case at purchase was: [paste from CRM notes]. Classify the most likely root cause of the adoption gap from these categories:
- Awareness gap: Customer may not know the feature exists or how to access it
- Complexity gap: Customer has attempted to use the feature but encounters friction (support tickets, failed events)
- Relevance gap: Customer's actual workflow may not require this feature (despite ICP match)
- Technical gap: Integration or setup required that hasn't been completed
- Champion gap: The user who would benefit isn't the user who has access
Recommend the specific intervention from the intervention library below."

C. INTERVENTION ROUTING LIBRARY

Awareness Gap → In-app: Contextual spotlight tooltip triggered on next login. Email: "Your team hasn't tried [Feature] yet — here's why [Company with similar use case] made it their most-used feature in 90 days: [1-2 sentence outcome]. [Schedule 15-min walkthrough]."

Complexity Gap → CS task: Schedule feature-specific success session within 10 days. If CS capacity constrained: automated email sequence with 3 tutorial touchpoints over 14 days, each focused on one specific use case. Escalate to CS if no adoption signal detected after sequence.

Relevance Gap → CS task: Validate whether the feature's intended use case applies to this customer. If not relevant: remove from adoption gap report to prevent false churn signals. If relevant but unknown to customer: reframe value prop in next QBR.

Technical Gap → CS + Support routing: "Account [X] has not completed [Integration setup / Configuration step] required to use [Feature]. Trigger: CS task to schedule technical setup session within 7 days."

Champion Gap → CS task: Map which users have access to the feature vs. which users would benefit based on their job title/role. Recommend access expansion to new user group.

D. ADOPTION LIFT MEASUREMENT

For each intervention deployed, track:
- Adoption rate at 30-day post-intervention (feature events ÷ licensed users with access)
- Adoption rate at 90-day post-intervention
- Correlation between adoption recovery and renewal rate: [Did accounts that recovered adoption renew at higher rates than accounts that didn't?]
- Correlation between adoption recovery and expansion: [Did adoption recovery open expansion conversations?]

---

DELIVERABLE 5 — PMM EXPANSION REVENUE REPORTING ARCHITECTURE

A. METRICS PRODUCT MARKETING OWNS IN THE NRR MODEL

PMM-owned leading indicators:
1. Feature Adoption Breadth (FAB) Score: Average number of core features with active adoption per account (target: ≥ 4 of 7 core features for mid-market accounts)
2. Value Realization Milestone Completion Rate: % of accounts that have completed the defined value realization milestones within 90 days of onboarding
3. Expansion Signal Rate: % of accounts that reach Tier 1 expansion signal within 12 months of purchase
4. Dark Adoption Recovery Rate: % of detected adoption gaps that are resolved within 60 days of intervention

PMM-owned lagging indicators:
5. PMM-Influenced Expansion Pipeline: Expansion opportunities where the trigger was a PMM-designed adoption signal (vs. CS relationship-initiated or renewal upsell)
6. Feature Adoption → Expansion Conversion Rate: Of accounts that reached expansion predictor sequence completion, what % expanded within 90 days?
7. NRR Contribution Attributed to Adoption Programs: Expansion revenue generated from accounts in PMM-designed adoption campaigns vs. control group

B. MONTHLY PMM → EXPANSION REVENUE REPORT STRUCTURE

Audience: CMO, VP Sales, VP Customer Success
Cadence: Monthly, delivered first Tuesday of each month
Format: 1-page dashboard + 3-slide narrative

Dashboard metrics:
- Current period: Feature Adoption Breadth Score (trend vs. prior 6 months)
- Current period: Expansion Signal Rate (new signals generated this month)
- Current period: PMM-Influenced Expansion Pipeline ($) added this month
- Current period: Dark Adoption Recovery Rate
- Cohort view: Adoption signal → expansion conversion by customer segment

Three-slide narrative:
Slide 1 — "What the Product Told Us This Month": Top 3 behavioral signals detected this month, what they indicate about customer value realization, and what actions were triggered.
Slide 2 — "Expansion Opportunities PMM Generated": Expansion deals in pipeline that originated from adoption signals vs. expansion deals that were missed (where adoption signals existed but weren't actioned). This is the accountability slide — it shows both the wins and the gaps.
Slide 3 — "What We're Fixing": The 3 features with the largest adoption gaps this month and the interventions deployed. Expected lift: [%] recovery in [timeframe]. NRR impact if recovery achieved: [$].

C. QUARTERLY CMO NARRATIVE TEMPLATE

Frame product marketing's NRR contribution as:
"Product marketing owns the behavioral layer between product delivery and revenue expansion. This quarter, PMM-designed adoption signals generated [X] expansion opportunities worth [$Y] in pipeline. Of these, [Z%] have closed or are forecast to close within [90 days], representing [$W] in PMM-attributed expansion revenue. Our adoption gap interventions recovered [A%] of flagged accounts, of which [B%] have since renewed or expanded — [C percentage points] above the renewal rate for accounts with unresolved adoption gaps. The cost of the adoption signal infrastructure is [$D] per month, producing a [E:1] ROI on expansion revenue alone — before accounting for the churn prevention contribution."

---

## Example Input/Output

**Input Example:**

Company: Trackflow — workflow automation platform for operations teams at mid-market logistics companies
Product: Eliminates manual dispatcher decisions by automating routing, constraint enforcement, and exception handling across connected warehouse and delivery operations
ICP: VP Operations and Head of Logistics at 3PL and last-mile logistics companies, 200–1,000 employees
Core features: Route Optimizer (daily usage expected), Exception Handler (event-driven), Carrier API Connector (setup once, passive), Compliance Reporting (weekly), Analytics Dashboard (weekly), Multi-Site Manager (Tier 2 feature), Customer Portal (Tier 2 feature)
Current NRR: 109% | Target: 128%
Product analytics: Amplitude | CRM: Salesforce | CS: Gainsight
Expansion motions: Seat expansion, Tier 2 upgrade (Multi-Site Manager + Customer Portal), Professional Services

**Output Example (Deliverable 1 — Feature Adoption Signal Matrix, 2 features):**

ROUTE OPTIMIZER ADOPTION MATRIX:

Surface Engagement (High Risk): Account has logged into Route Optimizer 1–4 times in first 21 days. No routes generated. No integrations connected. → Classification: RED. Automated action: CS task — "Route Optimizer surface engagement only at Day 21. Schedule 30-min setup session within 5 days." Do not wait for QBR.

Functional Adoption: Account generates routes 3+ times per week. Routes are manually reviewed and approved at >70% rate (dispatch team hasn't automated approval yet). Carrier API Connector not yet integrated. → Classification: YELLOW. Value is being received but workflow automation is incomplete. Expected outcome: this account will renew but is unlikely to expand without CS-guided workflow deepening.

Value Realization (Expansion Predictive): Account generates routes autonomously (auto-approval rate >85%), Exception Handler is triggered and resolved 10+ times per month without dispatcher intervention, Carrier API Connector active with 2+ carrier integrations, Compliance Reports exported weekly. → Classification: GREEN + EXPANSION SIGNAL ACTIVE. Behavioral sequence to watch for Multi-Site Manager expansion trigger: Detection of 2+ geographic location identifiers in Route Optimizer data (indicating multi-location operations not yet managed through the platform).

EXPANSION PREDICTOR SEQUENCE FOR MULTI-SITE UPGRADE:

Event 1 (Day 1 of sequence): Route Optimizer data contains location identifiers for 2+ distinct geographic areas for 3+ consecutive weeks
Event 2 (Days 7–21): 3+ distinct user accounts with different location-identifying information active in same account
Event 3 (Days 14–28): Compliance Reporting exports filtered by location segment (user is manually sorting multi-site data)
Event 4 (Days 21–35): Support ticket OR in-app search for "multi-site" or "multiple locations" OR feature request logged
Confidence threshold: Events 1–3 must complete within 35 days. Event 4 is confirmatory but not required.
Historical conversion rate from sequence completion to Multi-Site upgrade: 67% within 90 days (based on 18 months of Salesforce data analysis)

EXCEPTION HANDLER ADOPTION MATRIX:

Surface Engagement (Critical Risk): Exception Handler enabled but 0 exceptions processed in first 45 days. This indicates either: (a) Route Optimizer is not being used at scale yet — check Route Optimizer adoption first, or (b) Exception Handler was not configured correctly during onboarding. → Classification: RED for Exception Handler; check root cause before actioning.

Value Realization Signal: Exception Handler processes 10+ exceptions per month with <15% manual override rate. This means the dispatch team trusts the system's automated exception decisions. → Classification: GREEN. This is the strongest predictor of renewal in logistics operations accounts — once dispatch teams trust AI exception decisions, churn becomes extremely rare.

CHURN RISK SIGNAL — Exception Handler Abandonment: Account had Exception Handler processing 15+ exceptions per month for 90 days, then drops below 3 per month for 21+ consecutive days. → Classification: CRITICAL CHURN RISK. Most common cause: a dispatch manager left and new manager prefers manual control. Immediate CS intervention required — do not wait for health score to catch this.

---

## Success Metrics

- Expansion signal detection rate: ≥75% of closed expansion deals should have had a detectable adoption signal 30+ days before the opportunity was created (measured quarterly against Salesforce data)
- Adoption gap resolution rate: ≥60% of flagged adoption gaps resolved within 60 days of intervention
- PMM-influenced expansion pipeline: ≥30% of total expansion pipeline attributed to PMM-designed adoption signals within 12 months of program launch
- Dark adoption intervention lift: Accounts with resolved adoption gaps renew at ≥15 percentage points higher rate than accounts with unresolved gaps
- NRR contribution tracking: Measurable PMM attribution to NRR delta — at minimum, the program should be able to claim contribution to ≥3 NRR percentage points within 18 months

## Related Prompts

- [Feature Adoption Acceleration Program & In-App Behavioral Marketing](./AI-Powered-B2B-SaaS-Feature-Adoption-Acceleration-Program-&-In-App-Behavioral-Marketing-Revenue-Intelligence-Engine.md)
- [Feature Habit Formation & Habitual Adoption Loop Architecture](./AI-Powered-B2B-SaaS-Feature-Habit-Formation-&-Habitual-Adoption-Loop-Architecture-Revenue-Intelligence-Engine.md)
- [Customer Health Score Intelligence & Proactive Marketing Intervention Architecture](../../05_Analytics-&-Performance/Customer-Lifecycle-Marketing-Analytics/AI-Powered-B2B-SaaS-Customer-Health-Score-Intelligence-&-Proactive-Marketing-Intervention-Architecture-Engine.md)
- [NRR Marketing Program Architecture & Expansion Revenue Campaign Intelligence](../../06_Customer-Success-&-Retention/Churn-Prevention-&-Expansion/AI-Powered-B2B-SaaS-NRR-Marketing-Program-Architecture-&-Expansion-Revenue-Campaign-Intelligence-Engine.md)

## Integration Tips

- **Amplitude/Mixpanel**: Create a cohort for "Expansion Predictor Sequence Completed" using your behavioral sequence definition. Set up automated cohort sync to Salesforce via the native integration — when a user enters the cohort, auto-create a Salesforce task for the AE. Amplitude's Salesforce connector can pass event properties directly to opportunity fields for tracking.
- **Gainsight**: Build the Expansion Signal into a CTA (Call to Action) rule: when a contact triggers Expansion Predictor Sequence events (synced from Amplitude), auto-create a "Expansion Opportunity Identified" CTA in Gainsight assigned to the CSM, with the Account Intelligence Brief pre-populated in the CTA notes using a Gainsight template.
- **Salesforce**: Create a custom object "Adoption Signal Events" linked to Account. Log each trigger type as a record with: signal type, detection date, action triggered, AE notified, and outcome (expansion closed Y/N, 90 days after signal). This creates your attribution data model and lets you run the quarterly PMM contribution report.
- **Slack**: Use Zapier or native Salesforce-Slack integration to fire the Account Intelligence Brief into the AE/AM's dedicated Slack channel when a Tier 1 expansion trigger fires. Format: "🟢 Expansion Signal at [Account Name] — [Trigger Type]. [2-sentence context]. See the full brief: [Salesforce link]."
- **HubSpot**: Use HubSpot's Custom Behavioral Events (available in Enterprise) to create product usage events in HubSpot contact records without a full Amplitude integration. Then build Workflows: When contact completes [X product events] within [Y days], enroll in "Expansion Nurture" workflow and create deal in pipeline stage "Expansion Qualified."
- **Notion**: Build a "Feature Adoption Signal Library" — a living database tracking for each customer segment: which features have the strongest expansion correlation, which have the highest churn correlation when abandoned, and what the current benchmark thresholds are. Update quarterly as you accumulate more expansion data.

## Troubleshooting

**Problem: The expansion predictor sequence isn't generating opportunities — CS says the accounts it flags aren't ready to buy.**
Solution: Your predictor sequence events are likely too early in the adoption journey. Pull the deal data again and look specifically at accounts that expanded within 30 days (not 90 days) — the behavioral events that immediately preceded expansion are higher-confidence signals than those 90 days out. Also check whether your expansion conversations are opening correctly: if AEs are leading with "I noticed you've been using X feature" rather than the recommended business outcome framing, the conversation will fail regardless of signal quality.

**Problem: Adoption gap interventions aren't driving recovery — accounts are receiving the email sequence but feature adoption isn't improving.**
Solution: Email alone rarely recovers adoption for complex features. Audit whether the root cause classification is accurate: pull a sample of 10 accounts where intervention failed and check whether Amplitude shows active attempts to use the feature (complexity gap) vs. no attempts at all (awareness gap). For complexity gaps, email sequences don't work — CS-led setup sessions are required. Also audit whether the email sequence is triggering to the right user: if the operations manager receives the adoption nudge but the dispatcher is the actual user, the message will never reach the person who needs to change behavior.

**Problem: PMM can't get clean data from product analytics to build the expansion predictor sequence.**
Solution: This is a data instrumentation problem before it's a marketing problem. Work with the product/data team to define the 5–8 events that need to be consistently tracked across all customer accounts before you can build the model. Use this prioritization framework: only instrument events that (a) directly correspond to a business outcome the customer cares about, and (b) can be observed consistently across all customer accounts regardless of configuration. Avoid tracking feature-level clicks — track outcome-level events (route generated, exception resolved, report exported) that indicate the customer achieved something with the feature.

## Version History
- v1.0: Initial creation (auto-generated)
