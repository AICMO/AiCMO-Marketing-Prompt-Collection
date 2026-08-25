# AI-Powered B2B SaaS Feature Stickiness Analytics & Adoption-Depth Churn Prevention Marketing Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** feature-adoption, churn-prevention, retention, product-stickiness, customer-marketing, nrr, product-led-growth, b2b-saas, product-marketing, customer-success

## Overview
This prompt builds an AI-powered system that identifies which features create true product stickiness — the deep workflow integration that makes cancellation costly — then designs autonomous marketing campaigns to drive at-risk accounts toward those features before they churn. Use it when you have product analytics data, rising churn signals, and no systematic way to connect low-adoption accounts to targeted re-engagement marketing before your CS team notices the problem.

## Quick Copy-Paste Version

You are a B2B SaaS product marketing strategist specializing in retention and churn prevention through feature adoption. Analyze our product usage data to identify which features create "stickiness" — deep workflow dependency that raises switching costs — then design an automated marketing system that identifies at-risk accounts and drives them toward these stickiness features before they churn.

Company context:
- Product: [Your Product Name] — [one-sentence value proposition]
- Customer base: [e.g., "340 customers, Operations and Finance teams at $30M–$500M companies"]
- Current ARR: [e.g., "$14M ARR, 6.2% annual gross churn"]
- Core features: [e.g., "Workflow Automation, Reporting Dashboard, Integrations, Collaboration Tools, Admin Controls, API Access"]
- Churn trigger patterns (if known): [e.g., "Churned accounts averaged 2.1 active users vs. 7.3 for retained; 78% of churned accounts never activated Integrations"]
- Data available: [e.g., "Mixpanel product analytics, HubSpot CRM, Gainsight, Intercom for in-app messaging"]

Produce:

1. STICKINESS FEATURE IDENTIFICATION — Which 3-5 features, when adopted at sufficient depth, create the highest switching cost? Distinguish between "stickiness through workflow dependency" (the feature owns a daily job-to-be-done), "stickiness through data accumulation" (years of data stored in the feature), and "stickiness through team network effects" (the feature is only valuable with multiple users). For each, define the minimum adoption threshold that creates stickiness.

2. CHURN RISK PROFILE — What behavioral pattern distinguishes a 90-day-pre-churn account from a retained account? Define the Early Warning Signal Set (EWSS) — the 5-7 specific usage behaviors that, in combination, predict renewal risk 60-90 days before the renewal date.

3. MARKETING INTERVENTION LIBRARY — Design 6 automated marketing campaigns that activate when specific EWSS signals trigger. For each: target account segment, intervention timing, channel mix (email, in-app, CSM alert, paid retargeting), message angle, and expected lift in feature adoption within 30 days.

4. STICKINESS JOURNEY SEQUENCES — Write 2 complete, ready-to-use campaign sequences (email + in-app) that guide at-risk accounts toward the top stickiness feature. Include full copy for each touchpoint.

5. RETENTION IMPACT MODEL — Build a simple model showing how a 10-percentage-point increase in stickiness-feature adoption across your customer base translates to gross ARR retention improvement.

Output as a complete playbook the product marketing team can implement within 30 days.

## Advanced Customizable Version

ROLE: You are a VP of Product Marketing who has owned gross churn reduction programs at three B2B SaaS companies, improving gross churn by an average of 2.8 percentage points over 18 months through systematic feature adoption marketing — not by adding CSM headcount, but by designing automated marketing systems that intervene before accounts become CS-rescue cases. You understand that most B2B SaaS companies treat churn as a Customer Success problem and miss the 60-90 day window where marketing can tip an at-risk account into a retained one. You define "feature stickiness" with precision: a feature is sticky when (1) it owns a recurring job-to-be-done that the user performs 3+ times per week, (2) removing the feature would require rebuilding a workflow in another tool, OR (3) the feature stores cumulative data that becomes more valuable over time and is difficult to migrate. You build marketing systems that run autonomously — monitoring product signals daily, triggering personalized interventions, and coordinating with CS without requiring human judgment for every action. You measure success by Gross ARR Churn Rate, Feature-Triggered Retention Lift (FTRL), and Marketing-Attributed Renewals.

---

COMPANY PROFILE:

**Product & Customer Base:**
- Company name + product: [e.g., "Verdant — an AI-powered procurement intelligence platform that helps Procurement and Finance teams at mid-market companies automate vendor management, track contract obligations, and eliminate maverick spending"]
- ICP: [e.g., "VP Procurement, Controller, Director of Finance, and Senior Buyer at companies with $75M–$1B revenue in manufacturing, professional services, and logistics"]
- ACV range: [e.g., "$18,000–$96,000, median $38,000"]
- Customer count and ARR: [e.g., "310 customers, $14M ARR"]
- Gross ARR churn: [e.g., "6.8% — target is below 4% within 18 months"]
- Renewal cycle: [e.g., "Annual contracts, 60-day cancellation notice window"]
- Current retention motion: [e.g., "QBRs at 6-month mark for accounts >$30K ACV. No systematic marketing-led retention program. CSMs manage renewal conversations ad hoc"]

**Product Architecture:**
- Core modules (included in base license): [e.g., "Vendor Directory & Onboarding, Contract Repository, Spend Tracking Dashboard, Approval Workflow Engine, Basic Reporting"]
- Add-on modules: [e.g., "AI Contract Risk Scoring ($9,000/year), Supplier Performance Intelligence ($7,200/year), ERP Integration Pack ($4,800/year)"]
- Typical user profile per account: [e.g., "Primary admin (Procurement Manager), 3-6 general users (buyers and AP staff), optional Finance viewer seats"]
- Feature adoption rates across current customer base: [e.g., "Vendor Directory: 97% | Contract Repository: 82% | Spend Tracking Dashboard: 74% | Approval Workflow Engine: 61% | Basic Reporting: 44% | AI Contract Risk Scoring: 28% | ERP Integration: 22% | Supplier Performance Intelligence: 19%"]

**Churn Signal Data:**
- Accounts churned in last 12 months: [e.g., "21 accounts, representing $960K ARR"]
- Known behavioral patterns of churned accounts vs. retained: [e.g., "Churned accounts: average 2.4 weekly active users at month 6 vs. 6.1 for retained; 81% of churned accounts never activated Approval Workflow Engine; 74% had Spend Tracking Dashboard usage drop >40% in months 4-6; 67% never connected an ERP integration; CSM was first alerted to risk an average of 28 days before renewal notice deadline"]
- Accounts you rescued from churn last year (if any): [e.g., "4 accounts totaling $190K ARR — all via CS-led intervention after executive escalation. Average intervention started 45 days before deadline"]
- Current churn prediction tool or process: [e.g., "Gainsight health scores based on login frequency and NPS — but health scores lag the actual risk signal by 30-45 days"]

**Product Analytics Stack:**
- Product analytics: [e.g., "Mixpanel — tracking user-level events, feature activation flags, workflow completion events, and session frequency"]
- CRM: [e.g., "Salesforce"]
- Customer success: [e.g., "Gainsight"]
- In-app messaging: [e.g., "Pendo"]
- Marketing automation: [e.g., "Marketo"]
- Data warehouse: [e.g., "Snowflake with dbt transformations — product data available as daily snapshots in Marketo as company-level properties"]

---

DELIVERABLES — produce each section in ready-to-implement detail:

**SECTION 1: FEATURE STICKINESS TAXONOMY**

Define the stickiness architecture for the product described above:

1a. **Stickiness Classification Framework**: Classify each core feature into one of three stickiness types:
- **Workflow Dependency Stickiness (WDS)**: Feature owns a daily or weekly job-to-be-done. Users would need to rebuild this workflow in a new tool — creating friction that delays cancellation decisions.
- **Data Accumulation Stickiness (DAS)**: Feature stores data that grows more valuable over time (historical spend data, contract archives, vendor performance history). Migration cost increases with tenure.
- **Network Effect Stickiness (NES)**: Feature requires multiple users or external parties (vendors, approvers) to be valuable. Cancellation disrupts organizational workflows beyond the procurement team.

For each feature, assign its stickiness type(s), stickiness intensity (Low/Medium/High), and the specific workflow or data loss that would occur if the account cancelled.

1b. **Minimum Stickiness Threshold (MST)**: For each high-stickiness feature, define the exact behavioral threshold that indicates the feature has "crossed the dependency threshold" — the point at which the account has embedded the feature so deeply that cancellation requires active effort. Express as: [Feature] is sticky when [specific usage event] has occurred [frequency/count] over [time window] by [minimum number of users/roles].

1c. **Stickiness Gap Analysis**: Using the feature adoption rates provided, calculate what % of your current customer base has crossed the MST for each high-stickiness feature. Identify the "stickiness deficit" — the gap between current penetration and the target penetration needed to reach your churn goal.

---

**SECTION 2: EARLY WARNING SIGNAL SYSTEM (EWSS)**

Design an Early Warning Signal System that identifies at-risk accounts 60-90 days before their renewal date — early enough for marketing to intervene:

2a. **Leading vs. Lagging Churn Signals**: Classify the behavioral signals from the churn data provided into:
- **Leading signals** (appear 90-120 days before churn): indicate declining engagement trajectory before it becomes critical
- **Lagging signals** (appear 30-60 days before churn): indicate a decision has likely been made or is imminent

2b. **Churn Risk Score (CRS) Design**: Build a 0-100 Churn Risk Score computed from product usage signals. Define:
- 8-12 specific signals and their weight in the CRS
- Data source for each signal (Mixpanel event, Gainsight health metric, etc.)
- How signals interact (e.g., one signal may amplify another when they co-occur)
- Refresh frequency (daily recommended)

| Signal | Type | Weight | Source | Threshold for Risk |
|--------|------|--------|--------|-------------------|
| [e.g., Weekly Active Users drop >30% over 30 days] | Leading | 20% | Mixpanel | [define threshold] |
| [Continue for all 8-12 signals] | | | | |

2c. **CRS Band Definitions and Response Protocol**:
| Score | Risk Level | Marketing Motion | CS Involvement | Timeline |
|-------|------------|-----------------|----------------|----------|
| 80–100 | Critical | [define] | [define] | [days to act] |
| 60–79 | High | [define] | [define] | [days to act] |
| 40–59 | Elevated | [define] | [define] | [days to act] |
| 20–39 | Monitoring | [define] | [define] | [days to act] |
| 0–19 | Healthy | [define] | [define] | [days to act] |

2d. **Signal Velocity Alerts**: Define 3 specific signal-change scenarios that override the CRS score and trigger immediate escalation — cases where the speed of change matters more than the absolute score. For each scenario, define the automated response chain.

---

**SECTION 3: STICKINESS INTERVENTION LIBRARY**

Design 8 specific marketing interventions that activate when EWSS signals trigger. Each intervention should be:
- Triggered by a specific CRS signal or threshold crossing
- Targeted at a specific persona within the account (admin, end user, executive)
- Designed to drive adoption of a specific stickiness feature
- Runnable without CSM involvement (marketing-autonomous) or with CSM co-execution (hybrid)

For each intervention:
- **Trigger**: Exact signal or CRS event that fires this intervention
- **Target persona**: Role within the account and why this person
- **Stickiness feature goal**: Which feature this intervention drives toward
- **Channel mix**: Email, in-app prompt, CSM alert, retargeting ad, or combination
- **Message angle**: The specific frame that makes this feature feel urgent and valuable to this persona (not generic "here's a feature" — frame it as risk, loss, or competitive gap)
- **Timeline**: How many days after trigger, how many touchpoints, over what window
- **Success metric**: Feature activation rate within 30 days, measured per cohort

Interventions must address:
1. Account with 0 activation of top stickiness feature at Month 3 → urgency-driven activation campaign
2. Weekly active user count drop >25% over 30 days → re-engagement sequence for lapsed users
3. Only 1 active user in account (admin-only usage, no team adoption) → multi-user activation campaign targeting additional team members
4. Account using <50% of purchased seats actively → seat activation campaign
5. ERP/integration not connected → data synchronization value campaign
6. Approval Workflow Engine never activated → process efficiency campaign for finance persona
7. Account approaching renewal with CRS >60 → executive-targeted value demonstration campaign
8. Account that had support ticket about cancellation intent → concierge rescue sequence

---

**SECTION 4: RETENTION CAMPAIGN SEQUENCES — FULL COPY**

Write 3 complete, ready-to-deploy campaign sequences:

**Campaign A: "The Approval Workflow Activation" (Stickiness Feature: Workflow Dependency)**

Trigger: Account has been live for 90+ days, Approval Workflow Engine has 0 completions, CRS is 40+.
Target persona: Account Admin (primary contact) + Finance Manager (if identified in account).
Goal: Drive Approval Workflow Engine to MST (3+ completed approval requests per week) within 30 days.

Deliverable:
- 4-email sequence (full copy for each, not subject lines only)
- 2 in-app message scripts (Pendo tooltip + modal)
- CSM Gainsight alert template with recommended talking points

For each email: write subject line, preheader, opening paragraph, body copy, CTA button copy, P.S. line, and send timing relative to trigger.

**Campaign B: "The Multi-User Dependency Build" (Stickiness Feature: Network Effect)**

Trigger: Account has only 1-2 active users at Month 4, purchased 5+ seats, CRS is 50+.
Target persona: Admin/Champion — encouraging them to activate their team.
Goal: Drive team adoption to 4+ unique users active weekly within 21 days.

Deliverable:
- 3-email sequence to the admin champion (full copy)
- 1 in-app prompt targeting the admin when they log in (Pendo in-app guide script)
- Invitation email template the admin can forward to team members

**Campaign C: "The Executive Value Brief" (Pre-Renewal Rescue)**

Trigger: Account renewal is 90 days out, CRS is 65+, no QBR has been scheduled.
Target persona: Economic buyer / executive sponsor (not the day-to-day admin).
Goal: Secure a 30-minute executive conversation within 14 days.

Deliverable:
- 2-email sequence to the executive (full copy — executive-appropriate, not product-heavy)
- 1 LinkedIn connection request message (if executive not in CRM)
- Executive "Value Summary" one-page brief template (key metrics format the CSM can populate in 15 minutes)

---

**SECTION 5: MARTECH IMPLEMENTATION ARCHITECTURE**

5a. **Churn Risk Score Computation Pipeline**: Map the exact data flow that computes the CRS daily:
- Mixpanel → Snowflake → dbt transformation layer → Marketo company property sync
- Specify: which Mixpanel events to pull, which dbt models to build, which Marketo properties to create, and the sync frequency

5b. **Marketo Program Architecture**: Define the 4 core Marketo programs needed:
- Program 1: CRS Computation and Segmentation (batch, daily)
- Program 2: Stickiness Feature Activation Programs (trigger-based)
- Program 3: Pre-Renewal Executive Sequence (trigger-based, 90-day window)
- Program 4: Multi-User Activation (trigger-based)

For each program: enrollment trigger, smart list definition, flow steps, exit criteria, and suppression rules.

5c. **Gainsight Integration — CS Handoff Protocol**: Define the Gainsight Rules Engine rules and CTA templates that fire when CRS crosses 60. Include: CTA title, description, recommended talking points, linked Marketo campaign enrollment status, and escalation path if CSM doesn't action within 5 business days.

5d. **Pendo In-App Targeting Architecture**: Define the 3 Pendo segments and guide types needed for stickiness feature activation campaigns. Specify: audience targeting criteria, guide type (tooltip/modal/banner), trigger event (page load, feature proximity), and suppression logic (don't show if user has completed MST).

---

**SECTION 6: RETENTION IMPACT FINANCIAL MODEL**

6a. **Current State Baseline**: Using the company data provided, calculate:
- Current gross ARR churn rate and dollar value lost
- % of churned accounts that had CRS signals 90+ days before cancellation but received no marketing intervention
- Estimated "addressable churn" — the portion of churned ARR that marketing intervention could have influenced (exclude: company bankruptcies, budget eliminations, product-fit mismatches)

6b. **Stickiness Lift Scenario Model**: For each stickiness feature, model what happens if you increase the % of accounts that cross the MST by 10 percentage points:

| Stickiness Feature | Current MST % | Target MST % | Estimated Churn Lift | ARR Retention Impact |
|--------------------|---------------|--------------|----------------------|---------------------|
| [Feature 1] | [X%] | [X+10%] | [e.g., -0.8pp churn] | [e.g., +$112K ARR retained] |
| [Continue] | | | | |

6c. **Program ROI Projection**: Estimate the cost (marketing ops hours, tool licenses, creative) of running this program for 12 months vs. the ARR retention value created. Include a break-even analysis.

6d. **90-Day Milestone Targets**: Define the leading-indicator metrics that prove the program is working before you see churn rate impact (which lags 12 months):
- Week 2: [e.g., CRS computation live in Marketo, first 15 accounts enrolled in Campaign A]
- Week 6: [e.g., 40% of enrolled accounts complete MST for target stickiness feature]
- Week 12: [e.g., 3 accounts with CRS 65+ converted to scheduled executive conversations]
- Month 6: [e.g., Gross churn in CRS-monitored cohort is 35% lower than CRS-unmonitored cohort]

---

**SECTION 7: 30/60/90-DAY ACTIVATION ROADMAP**

| Phase | Days | Initiatives | Owner | Success Criteria |
|-------|------|-------------|-------|-----------------|
| Data Foundation | 1–30 | CRS built in dbt; Marketo properties created; EWSS thresholds configured; Campaign A copy written and approved | Marketing Ops + PMM | CRS computing for 100% of active accounts; first 10 accounts enrolled in Campaign A |
| First Campaigns Live | 31–60 | Campaign A + B live; Pendo guides deployed for top 2 stickiness features; Gainsight CTAs active; CSM enablement complete | PMM + Marketing Ops + CS | 30% of CRS-monitored accounts enrolled in at least 1 campaign; CS team briefed on new protocol |
| Optimize + Executive Motion | 61–90 | Campaign C live; first cohort analysis of Campaign A lift; CRS threshold tuning based on false-positive data; executive sequence A/B tested | PMM | Campaign A cohort shows ≥20% higher stickiness-feature activation than control; 5 executive conversations secured via Campaign C |

## Example Input/Output

**Input Example:**

A product marketer at Verdant (AI-powered procurement platform) fills in:
- 310 customers, $14M ARR, 6.8% gross churn
- Core features: Vendor Directory (97%), Contract Repository (82%), Spend Tracking (74%), Approval Workflow Engine (61%), Basic Reporting (44%), ERP Integration (22%)
- Churned account pattern: 81% never activated Approval Workflow Engine; 74% had Spend Dashboard usage drop 40%+ in months 4-6; average 2.4 WAUs at month 6 vs. 6.1 retained
- Stack: Mixpanel, Salesforce, Gainsight, Pendo, Marketo

**Output Example (excerpt from Section 2 — EWSS Design):**

*Churn Risk Score Signal Matrix for Verdant:*

**Signal 1 (Weight: 22%): Approval Workflow Engine — zero completions at Day 90**
Type: Leading indicator. Verdant's data shows 81% of churned accounts never activated this feature. A procurement platform that hasn't embedded approval workflows has not displaced any existing process — the customer is using Verdant as a data repository, not a workflow system. This is the single highest-weight signal because it represents failed core value delivery. Threshold: 0 workflow completion events in Mixpanel by Day 90 post-activation.

**Signal 2 (Weight: 18%): Weekly Active User Count — drop >30% over 30-day rolling window**
Type: Leading indicator for accounts with established WAU >4. For new accounts (WAU never exceeded 3), use absolute threshold instead. A WAU crash after a period of healthy usage indicates a change event: champion departure, budget scrutiny, competitive evaluation beginning, or team dissatisfaction. Threshold: WAU drops from a 30-day average of X to <0.7X in any subsequent 30-day window.

**Signal 3 (Weight: 15%): Spend Tracking Dashboard — session frequency drop >40% MoM**
Type: Leading indicator. This is the feature most tied to ongoing business rhythms (monthly financial close). A drop in dashboard usage during the financial close period (month-end) is an especially strong signal — finance teams don't stop doing financial close, they just do it somewhere else.

*Churn Risk Score example for one account:*

Account: Brennan Industrial Supply (VP Procurement: Dana Osei, 18 employees, 7 purchased seats)
- Approval Workflow Engine: 0 completions at Day 95 (Signal 1: 22 points)
- WAU: Dropped from 5.2 to 2.8 in last 30 days (Signal 2: 14 points)
- Spend Dashboard: Sessions down 44% MoM (Signal 3: 11 points)
- ERP Integration: Not connected (Signal 4: 9 points)
- Contract Repository: Last upload was 45 days ago (Signal 5: 7 points)

**Total CRS: 63 — High Risk. Renewal in 94 days.**

*Automated response: Enroll in Campaign A (Approval Workflow Activation) immediately. Fire Gainsight CTA to CSM: "Brennan Industrial Supply has CRS 63 with renewal in 94 days. Primary risk: Approval Workflow Engine never activated despite 95 days on platform. Marketing campaign A enrolled. Recommended CSM action: confirm Dana Osei's onboarding timeline for approval workflows and offer a 30-min process setup call. If no CSM response in 3 business days, Campaign C pre-renewal executive sequence will auto-enqueue."*

**Output Example (Campaign A Email 1 — full copy):**

Subject: The one Verdant feature your team hasn't unlocked yet (it's the one that saves 4 hours a week)
Preheader: Your contract approvals are still happening over email. Here's how to fix that in 20 minutes.

Dana,

You've been using Verdant for three months — and your vendor directory and contract repository are in great shape.

But I noticed something: your team is still approving purchase orders and vendor exceptions over email.

That means every time someone on your team needs a fast approval, they're:
- Drafting an email to find the right person
- Waiting for a response that might come back 3 days later
- Chasing down a paper trail when the auditors ask for it six months from now

Verdant's Approval Workflow Engine was built specifically for procurement teams like yours. Most of our customers get it running in under 20 minutes — and the ones who do average 4.1 hours saved per week, per buyer.

Here's what it does:
→ Routes approval requests to the right person automatically based on spend thresholds you define
→ Sends reminders so approvals don't fall through the cracks
→ Creates a complete audit trail in your contract repository — automatically

[Set Up Your Approval Workflow in 20 Minutes →]

If you'd rather see it in action first, I can have our team walk you through a setup that mirrors your existing approval chain. Just reply to this email.

Best,
[Your Name]
Verdant Customer Success

P.S. Companies in manufacturing and logistics who activate Approval Workflows within their first 90 days renew at 94% — vs. 71% for those who don't. That gap isn't a coincidence.

## Success Metrics

- **Feature-Triggered Retention Lift (FTRL)**: Compare renewal rate for accounts enrolled in stickiness campaigns vs. matched control accounts (same ACV, same tenure, similar CRS baseline). Target: enrolled accounts renew at 15+ percentage points higher rate within 12 months.
- **Stickiness Feature Penetration Rate**: % of active customer base that has crossed the MST for each stickiness feature. Measure monthly. Target: 10-percentage-point increase in top stickiness feature penetration within 6 months.
- **EWSS Lead Time**: Average number of days between first EWSS signal and account cancellation notice, across all churned accounts. Target: signal fires 75+ days before cancellation notice in 80% of churned cases, giving marketing time to intervene.
- **Marketing-Attributed Renewal Rate**: % of renewals where a marketing-triggered stickiness campaign was part of the account's journey in the 90 days before renewal. Measure via Marketo campaign attribution + Salesforce renewal opportunity association.
- **Campaign A/B/C Conversion Rates**: Stickiness-feature MST achievement rate within 30 days for accounts enrolled in each campaign. Benchmark target: Campaign A ≥25% MST achievement, Campaign B ≥30%, Campaign C ≥40% executive conversation rate.
- **Gross ARR Churn Rate Reduction**: Ultimate lagging indicator. Measure quarterly, cohort by quarter of first EWSS enrollment. Target: accounts enrolled in the program churn at a rate 2.5+ percentage points lower than non-enrolled accounts at same ACV and tenure.

## Related Prompts

- [Feature Adoption Acceleration Program & In-App Behavioral Marketing](./AI-Powered-B2B-SaaS-Feature-Adoption-Acceleration-Program-&-In-App-Behavioral-Marketing-Revenue-Intelligence-Engine.md)
- [Feature Adoption Revenue Correlation & Expansion Revenue Activation](./AI-Powered-B2B-SaaS-Feature-Adoption-Revenue-Correlation-&-Expansion-Revenue-Activation-Intelligence-Engine.md)
- [Renewal Marketing Program Architecture & At-Risk Account Churn Prevention](../../04_Demand-&-Lead-Generation-&-Growth/Customer-Marketing/AI-Powered-B2B-SaaS-Renewal-Marketing-Program-Architecture-&-At-Risk-Account-Churn-Prevention-Revenue-Intelligence-Engine.md)
- [Churned Customer Win-Back Program Architecture & Revenue Recovery](../../04_Demand-&-Lead-Generation-&-Growth/Customer-Marketing/AI-Powered-B2B-SaaS-Churned-Customer-Win-Back-Program-Architecture-&-Revenue-Recovery-Intelligence-Engine.md)

## Integration Tips

- **Mixpanel → Snowflake → Marketo pipeline**: Use Mixpanel's Data Pipelines (or a CDP like Segment) to export daily user-level events to Snowflake. Build a dbt model that aggregates events at the account level, computes the CRS, and writes the score and signal flags back to Marketo as custom company properties via Hightouch or Census. Schedule the sync at 6 AM daily so Marketo workflows run on fresh data each morning.
- **Gainsight CTA automation**: Create a Gainsight Rules Engine rule that fires a CTA to the account CSM whenever CRS crosses 60. Include in the CTA body: CRS score, the 3 highest-weight signals that drove it, renewal date, Marketo campaign enrollment status, and a one-click link to create a Salesforce Task for the account. Set a 3-business-day SLA on the CTA — escalate to CS manager if not actioned.
- **Pendo audience targeting**: Create a Pendo account-level segment that syncs the CRS property from Marketo (via a daily CSV push or API sync). Use this segment to target in-app guides specifically at CRS 40+ accounts. Suppress guides for accounts that have already achieved MST for the targeted feature to avoid irrelevant messaging to healthy users.
- **Marketo → Salesforce renewal opportunity**: Build a Marketo webhook that updates a custom field ("Marketing Retention Intervention") on the Salesforce Account when an account is enrolled in a stickiness campaign. This allows CS and Sales to see marketing activity in their renewal pipeline view and prevents conflicting outreach.
- **Slack CS alerts**: Create a #cs-retention-alerts Slack channel and use Zapier or Gainsight's Slack integration to post a daily digest of accounts whose CRS crossed a threshold in the last 24 hours. Format: Account Name | CRS Score | Renewal Date | Primary Risk Signal | Marketo Campaign Enrolled | CSM Owner.
- **LinkedIn Matched Audiences for executive retargeting**: For Campaign C (pre-renewal executive), upload a monthly list of accounts with CRS 65+ and renewal within 90 days to LinkedIn as a Matched Audiences company list. Run LinkedIn ads showing customer ROI data and case studies from peer companies — this warms the executive before the email sequence lands, increasing open rates by 15-25% in comparable programs.

## Troubleshooting

**Problem: We don't have enough churn history to validate which features are actually sticky — the company is only 2 years old.**
Solution: You don't need historical churn data to identify stickiness candidates — you need a logical framework. Apply the three stickiness tests to each feature: (1) Does removing this feature require rebuilding a workflow elsewhere? (2) Does the feature store data that accumulates value over time? (3) Does the feature require multiple users or external parties? Features that pass two or more tests are stickiness candidates. Validate your hypothesis at 6 months by comparing CRS-above-threshold accounts vs. below-threshold accounts on renewal rate — you'll have enough data to calibrate within 2 renewal cycles.

**Problem: Our CS team is resistant to marketing running "retention" campaigns because they feel it's their domain — and they're worried marketing will confuse customers with conflicting outreach.**
Solution: Design the system with CS as co-pilots, not bystanders. Route every Campaign A and B enrollment through a 24-hour "CS review window" — Gainsight fires a CTA to the CSM first, giving them the option to suppress the marketing sequence if they're actively working the account. CS teams that understand this become advocates, not opponents, because the EWSS gives them earlier visibility into risk than their own health scores do. Run a kickoff workshop with CS leadership to walk through the signal logic — when CSMs realize the CRS is catching risk 45+ days before their Gainsight health scores, they become your biggest internal sponsor.

**Problem: The CRS model is firing too many false positives — accounts flagged as CRS 60+ that renew without intervention, making the CS team distrust the system.**
Solution: Recalibrate the signal weights after your first 90 days of data. Pull all accounts that hit CRS 60+ in the first quarter and segment by outcome: churned, renewed without intervention, renewed after intervention. Accounts that renewed without intervention — what distinguished them from churned accounts? Likely a signal that's not in your current CRS (e.g., recent executive engagement, NPS score increase, new user added). Add those signals and reduce weight on signals that appeared equally in renewing and churning accounts. A well-calibrated CRS should have a false positive rate below 25% within 6 months.

## Version History
- v1.0: Initial creation (auto-generated)
