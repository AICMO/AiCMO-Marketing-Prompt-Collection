# Customer Health Score & Early Warning Intelligence Engine - AI-Powered Churn Prediction & Proactive Intervention System

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** customer-health, churn-prevention, cs-automation, saas, retention, predictive-analytics, b2b, revenue-intelligence

## Overview
Builds a complete customer health scoring system — defining the right signals, weighting model, risk tiers, and automated intervention playbooks — that enables CS teams to predict churn 60–90 days before it happens and trigger the right response before the customer ever decides to leave. Use it when you need to move from reactive firefighting to a proactive, data-driven retention motion.

## Quick Copy-Paste Version

You are a senior Customer Success strategist and data analyst. Build a complete customer health scoring system for the following SaaS company.

COMPANY CONTEXT:
- Product: [What your SaaS product does — 1-2 sentences]
- Customer segment: [SMB / Mid-Market / Enterprise — and typical company size]
- Average contract value (ACV): [$ amount]
- Current churn rate: [% annual or monthly]
- Key product action that signals value delivery: [The "aha moment" or core workflow customers must do to get ROI]
- CS-to-customer ratio: [e.g., 1 CSM : 75 accounts]
- Data available: [CRM data / product usage data / support tickets / NPS/CSAT / billing data]

Build a complete Customer Health Score system including:

1. **Signal Library**: List the 15 most predictive health signals for this type of product, grouped by category (Product Adoption, Engagement, Relationship, Financial, Support). For each signal, specify: what to measure, how often to sample, leading vs. lagging indicator classification, and direction (positive/negative impact on score).

2. **Scoring Model**: Design a weighted 0–100 health score model. Assign point weights to each signal category. Define three health tiers: Green (Healthy, 70–100), Yellow (At-Risk, 40–69), Red (Critical, 0–39). Include the formula logic and explain why each category weight reflects churn causation for this product type.

3. **Early Warning Triggers**: Define 10 specific event-based triggers that should immediately flag an account for CSM review (regardless of overall score), such as key user deactivation, sudden usage drop, support escalation, or missed executive sponsor meeting.

4. **Intervention Playbooks**: For each health tier (Green, Yellow, Red), create a 4-week CSM intervention playbook with specific touchpoints, messaging objectives, and escalation criteria. Include email templates for the first outreach at each tier.

5. **Automated Workflow Logic**: Design the automation rules — what triggers an automated email vs. a CSM task vs. an executive escalation. Output this as a decision tree with if/then logic that can be configured in Gainsight, ChurnZero, or HubSpot.

6. **Health Score Review Cadence**: Define the weekly, monthly, and quarterly review process for the CS team — what to look for in the score distribution, how to identify systemic issues vs. account-specific issues, and what to present to leadership.

Output everything as a ready-to-implement framework. Be specific — use realistic signal names (e.g., "# of logins in last 14 days," "% of licensed seats with activity in last 30 days") not vague categories.

## Advanced Customizable Version

**ROLE:** You are a VP of Customer Success with 15+ years building data-driven CS operations at B2B SaaS companies from Series B to post-IPO. You have built health score models used by CS teams managing $500M+ in ARR. You understand the difference between vanity metrics and true churn predictors, and you design systems that CSMs actually use.

**OBJECTIVE:** Design a fully automated, AI-executable Customer Health Score Intelligence System that predicts churn 60–90 days in advance, triggers the right intervention at the right time, and creates a continuous feedback loop that improves scoring accuracy over time.

**INPUTS — Fill all fields:**

PRODUCT & CUSTOMER PROFILE:
- Product name and category: ___
- Primary value delivered (what customers pay for): ___
- Core "sticky" workflow (action customer must do to be retained): ___
- Average time-to-value (days from contract start to first measurable ROI): ___
- Customer segments tracked (e.g., SMB self-serve / MM managed / Enterprise strategic): ___
- ACV by segment: ___
- Gross revenue churn rate (current): ___
- Net revenue retention rate (current): ___
- Typical reasons for churn (if known): ___

DATA INFRASTRUCTURE:
- CRM: ___
- CS platform (Gainsight / ChurnZero / Totango / HubSpot / Planhat / custom): ___
- Product analytics (Amplitude / Mixpanel / Pendo / Heap / custom): ___
- Support platform (Zendesk / Intercom / Freshdesk): ___
- Billing system (Stripe / Zuora / Chargebee): ___
- NPS/CSAT tool: ___
- Data warehouse available (Y/N): ___

CS TEAM STRUCTURE:
- Number of CSMs: ___
- Accounts per CSM: ___
- CS motion (high-touch / digital / hybrid): ___
- Executive Sponsor program in place (Y/N): ___

**DELIVERABLES:**

### 1. Predictive Signal Library (Tiered by Churn Causation)

**Tier 1 — High-Predictive Signals (weight: 15–20 pts each in model)**

For each signal, output in this format:
| Signal Name | What to Measure | Measurement Frequency | Leading/Lagging | Healthy Threshold | Warning Threshold | Critical Threshold | Data Source |
|---|---|---|---|---|---|---|---|

Cover these signal categories:
- **Product Adoption Depth**: DAU/MAU ratio, feature adoption breadth (% of paid features used), power user ratio (% of seats reaching weekly usage threshold), workflow completion rate
- **License Utilization**: Provisioned vs. active seats (% utilized), seat growth/contraction MoM, seat utilization trend (3-month direction)
- **Engagement & Relationship**: Last CSM touchpoint (days since), executive sponsor engagement (last 90-day meeting Y/N), champion seniority (VP+ vs. IC-level main contact), number of stakeholders engaged in last quarter
- **Financial Signals**: Invoice payment behavior (days late), expansion/contraction trend, add-on usage, contract renewal date proximity (90/60/30-day windows)
- **Support Health**: CSAT score trend, open P1/P2 tickets (count), time-to-resolution trend, escalation frequency (tickets escalated to management in last 60 days)
- **Voice of Customer**: Last NPS score and trend direction, survey response rate (engagement signal), sentiment from last QBR notes

**Tier 2 — Supplementary Signals (weight: 5–10 pts each)**
- Competitor mentions in support tickets or NPS verbatims
- Champion job change (LinkedIn API or Salesforce person change signal)
- Leadership change at customer (CEO/CTO/VP-level turnover)
- Community/event participation (webinar attendance, user group activity)
- Referral/advocacy activity (reference calls given, case study participation)

### 2. Health Score Architecture

**Scoring Model Design:**

Construct a 0–100 composite score with the following weighted category structure. Justify each weight based on churn causation research:

| Category | Weight | Rationale |
|---|---|---|
| Product Adoption & Usage | 35% | Usage frequency is the #1 predictor of retention in SaaS — customers who use the product daily churn at 5–8x lower rates than monthly users |
| Relationship & Engagement | 25% | Single-threaded relationships and disengaged executive sponsors are the #2 churn cause — relationship breadth is 3x more predictive than satisfaction scores alone |
| Business Outcomes Achieved | 20% | Customers who can articulate ROI churn 60% less; this measures whether they're achieving the value they contracted for |
| Financial Health | 12% | Payment behavior, expansion trajectory, and contract risk proximity signal intent and organizational health |
| Support Experience | 8% | Chronic unresolved issues and CSAT decline are lagging but high-signal churn indicators |

**Tier Definitions and Response SLAs:**

| Tier | Score Range | Definition | CSM Response SLA | Escalation Trigger |
|---|---|---|---|---|
| Green — Thriving | 85–100 | Strong adoption, multi-threaded, achieving ROI, expansion likely | Monthly check-in | Score drops 15+ pts in 30 days |
| Green — Healthy | 70–84 | Solid usage, good relationship, on-track for renewal | Bi-weekly check-in | Score drops 10+ pts in 14 days |
| Yellow — Watch | 55–69 | Partial adoption, single-threaded, or value gaps emerging | Weekly touchpoint | No CSM response in 5 days |
| Yellow — At-Risk | 40–54 | Usage decline, relationship cooling, support friction | 48-hour outreach + executive loop | No meeting booked in 7 days |
| Red — Critical | 0–39 | Multiple failure signals, churn likely within 60–90 days | Same-day outreach + VP escalation | No response in 24 hours |

**Score Stability Rules:**
- Score cannot increase more than 20 points in a single week (prevents artificial inflation from one-time spikes)
- Score is recalculated daily using rolling 30-day averages for usage signals
- Manual score override available for CSM with required justification field (creates audit trail)
- Score change of ±15 points in any 7-day period triggers a Slack/CRM alert to CSM

### 3. Early Warning System — Event-Based Triggers

These fire immediately regardless of current health score:

**Trigger 1: Champion Departure**
- Signal: Contact who is primary champion or executive sponsor changes roles, goes inactive on platform, or LinkedIn shows job change
- Action: CSM task within 24 hours to re-map account, identify new champion, schedule executive introduction call
- Severity: Critical (treated as Red regardless of score)

**Trigger 2: Catastrophic Usage Drop**
- Signal: Core workflow completions drop >50% week-over-week for any account with >$25K ACV
- Action: CSM health check call within 48 hours; product team notification if multiple accounts show same pattern (potential bug/UX issue)
- Severity: High

**Trigger 3: Mass User Deactivation**
- Signal: ≥3 users deactivated or not logging in for 21+ days on an account with ≥10 licensed seats
- Action: CSM outreach within 24 hours; investigate whether new admin took over, company downsizing, or product dissatisfaction
- Severity: High

**Trigger 4: P1 Support Ticket Open >72 Hours**
- Signal: Priority 1 ticket (system down, data loss, security) unresolved beyond SLA
- Action: Immediate escalation to Support Manager + CSM notification; CSM proactive outreach to customer acknowledging issue and ownership
- Severity: Critical

**Trigger 5: Negative NPS Response (Detractor)**
- Signal: NPS score of 0–6 submitted
- Action: CSM outreach within 4 hours using closed-loop response protocol; NPS verbatim routed to Product for categorization
- Severity: High

**Trigger 6: CSAT Below 3.0 on Consecutive Tickets**
- Signal: Two or more support tickets in 30 days rated ≤3/5 by same account
- Action: CSM meeting scheduled within 5 business days; VP CS notified for accounts >$50K ACV
- Severity: Medium

**Trigger 7: Invoice Past Due >15 Days**
- Signal: Outstanding invoice not paid within 15 days of due date
- Action: CSM flagged (not Finance); CS-led outreach to gauge whether financial issue is a churn signal vs. billing friction
- Severity: High (potential expansion/renewal risk signal)

**Trigger 8: No CSM Touchpoint in 45 Days (for managed accounts)**
- Signal: No logged call, email reply, or meeting with any contact at the account in 45 days
- Action: CSM manager alert; CSM outreach required within 3 business days
- Severity: Medium

**Trigger 9: Renewal Enters 90-Day Window Without Scheduled Review**
- Signal: Contract renewal date is 90 days out and no EBR/QBR is scheduled
- Action: CSM task created to schedule renewal review meeting; VP CS visibility for accounts >$75K ACV
- Severity: High

**Trigger 10: Competitor Mention Detected**
- Signal: Competitor name appears in support ticket, NPS verbatim, or CSM call notes (via keyword detection)
- Action: CS leadership flagged; competitive intelligence brief routed to CSM with battlecard; discovery conversation initiated
- Severity: High

### 4. Intervention Playbooks by Health Tier

**GREEN (70–100) — Retention, Expansion, and Advocacy Playbook**

*Objective: Strengthen relationship, identify expansion opportunities, convert to advocates*

Week 1: Monthly value review email
- Subject: "[Company Name] — your [Product] impact this month"
- Content: Personalized usage summary (# workflows completed, time saved, key metrics), 1 "tip of the month" feature they aren't using yet, soft expansion ask: "We've added [Feature X] — I'd love 20 minutes to show you how [similar customer] used it to [specific outcome]"

Week 2: No touch (unless expansion signal fires)

Week 3: Expansion or advocacy outreach
- If expansion signal: Schedule discovery call for upsell/cross-sell
- If NPS ≥ 9: Reference request or case study invitation
- If power user ratio is high: Invite to user advisory board or beta program

Week 4: Renewal prep (if within 180 days of renewal)
- Begin compiling ROI summary for renewal business case
- Identify executive sponsor engagement cadence

---

**YELLOW — AT-RISK (40–69) — Rescue and Re-Engagement Playbook**

*Objective: Diagnose root cause, re-establish value, rebuild relationship breadth*

Day 1 (trigger fires): CSM outreach call/email
Subject: "Quick check-in — want to make sure [Product] is delivering for your team"
Body: "Hi [Name], I was reviewing your team's activity in [Product] and noticed [specific observation — e.g., 'usage has been lower over the last few weeks' or 'we haven't connected since [date]']. I want to make sure you're getting full value from [Product] and that we're addressing anything that's gotten in the way. Can we find 20 minutes this week? I have [specific value-add ready: a new use case walkthrough / benchmarks from your industry / a feature update relevant to your goals]."

Day 3 (if no reply): LinkedIn message or phone attempt
Day 5 (if no reply): Manager-to-manager escalation email
Day 7: Internal escalation — CSM manager reviews account, decides whether to escalate to VP or try different contact

Week 2–3: Discovery and diagnosis call
- Goal: Uncover whether the issue is adoption friction, team change, competing priority, product gap, or early dissatisfaction
- Ask: "On a scale of 1–10, how confident are you that [Product] is going to be a clear win to renew?" (Forces honest conversation)
- Build a Success Plan: Co-create 30/60/90-day milestones with customer-owned actions and CSM-owned support

Week 4: Progress check on Success Plan
- If improving: Move toward Green playbook
- If stagnant: Escalate to Red; involve VP CS and consider executive-to-executive engagement

---

**RED — CRITICAL (0–39) — Save Playbook**

*Objective: Stop churn through executive engagement, root cause resolution, and renewal negotiation if needed*

Day 1 (same-day): CSM calls customer; VP CS notified
Email: "I want to make sure we address this directly"
Subject: "I want to make sure [Product] is working for [Company Name]"
From: VP of Customer Success (not CSM)
Body: "Hi [Exec Name], I'm [VP name], Head of Customer Success at [Our Company]. I've been reviewing accounts personally and wanted to reach out directly to [Company Name]. I understand your team may have encountered [specific known issue / low usage / support friction]. I want to personally make sure we resolve anything getting in the way of value. Can we connect this week? I'll bring our product and CS leadership to make sure we leave with a clear path forward."

Week 1–2: Executive-to-executive alignment call
- Agenda: Acknowledge reality (don't pretend nothing is wrong), understand strategic priority (has their use case or team changed?), present what we're doing differently, propose a joint 30-day success sprint
- Bring: ROI data if available, product roadmap items relevant to their pain, contractual flexibility if appropriate (pause, swap features, etc.)

Week 3: Decision point
- If re-engaged: Move to formal Success Plan with executive sponsor co-signature
- If churn likely: Begin managed churn protocol (graceful exit, data export support, referral preservation, future re-engage plan)

Week 4: Either renewal negotiation or churn documentation
- Document: Root cause, what signals we missed and when, what interventions we tried, what product gaps contributed — feed back to Product and CS leadership for systematic improvement

### 5. Automation Decision Tree

IF health_score drops below 55:
  → Create CSM task: "Account moved to Yellow — review and schedule touchpoint within 5 days"
  → Send internal Slack alert to CSM and CS Manager

IF health_score drops below 40:
  → Create urgent CSM task: "CRITICAL — outreach required within 24 hours"
  → Email VP CS with account summary
  → Block CSM calendar for same-day call attempt

IF early_warning_trigger fires (any of the 10 above):
  → Create immediate CSM task with trigger description and suggested action
  → Log trigger in CRM as "Health Event" with timestamp
  → Notify CS Manager for Trigger 1, 4, 7, 10 (high-severity triggers)

IF renewal_date < 90 days AND score < 70:
  → Create renewal risk flag in CRM
  → Escalate to VP CS for accounts >$50K ACV
  → Add to weekly "Renewal Risk Review" meeting queue

IF score > 85 AND contract_age > 12 months AND no_expansion_opportunity_logged:
  → Create CSM task: "Expansion opportunity review — account is Thriving, evaluate upsell"

IF NPS_score submitted AND score <= 6:
  → Trigger closed-loop NPS workflow (immediate CSM outreach + verbatim routing to Product)

IF score_change > +20 in 7 days:
  → Flag for CS Manager review (possible score inflation or one-time spike)
  → Do NOT trigger expansion workflow until confirmed stable for 14 days

### 6. Health Score Review Cadence

**Weekly CSM Standup (15 minutes)**
Review:
- Any new Red accounts this week (score dropped to 0–39)
- Any Early Warning Triggers fired since last standup
- Open intervention plans: Are Success Plans being executed?
- Accounts entering 90-day renewal window

Format: Sorted list view in CS platform filtered by score change direction (biggest drops first)

**Monthly CS Team Review (60 minutes)**
Review:
- Score distribution chart: % of ARR in Green / Yellow / Red (compare to prior month)
- Churn prediction accuracy: Did Red accounts churn as predicted? Did any Green accounts surprise-churn?
- Top 10 at-risk accounts by ARR × churn probability
- Intervention effectiveness: Of accounts that moved from Yellow/Red to Green, what interventions worked?
- Product signal patterns: Are specific features correlated with higher/lower health? Route to Product team.

**Quarterly Leadership Review (90 minutes)**
Present to VP CS / CCO / CEO:
- NRR and GRR trend vs. health score distribution
- Health score model accuracy assessment (recalibrate weights if predictions are off by >20%)
- Segment analysis: Are SMB / MM / Enterprise health patterns different? Should each segment have its own model?
- CSM performance: Health score improvement rate per CSM (coaching signal, not punitive metric)
- Product-churn correlation: Feature gaps or UX friction patterns contributing to Red accounts

## Example Input/Output

**Input:**
- Product: Vantive — AI-powered contract intelligence for in-house legal teams
- Segment: Mid-Market, 200–2,000 employee companies
- ACV: $45K average
- Churn: 14% annual (industry benchmark: 8–10% for legal SaaS)
- Core sticky workflow: Weekly contract review queue processed through AI redlining
- CS ratio: 1 CSM per 65 accounts
- Data: Salesforce CRM, Pendo product analytics, Zendesk support, Qualtrics NPS

**Sample Health Score Output for Account "Meridian Financial" (Account ID #4421):**

| Signal | Score | Weight | Contribution |
|---|---|---|---|
| Weekly active users / licensed seats | 3/10 licensed users active | 35% | 10.5 pts |
| Core workflow completions (AI redlines/week) | 4 redlines/week (down from 22 four weeks ago) | 35% | 7 pts |
| Last CSM touchpoint | 34 days ago | 25% | 12.5 pts |
| Executive sponsor engagement | No meeting in 90 days | 25% | 5 pts |
| Open support tickets | 1 P2 open for 8 days | 8% | 2 pts |
| Last NPS score | 6 (detractor, submitted 3 weeks ago) | 8% | 2 pts |

**Composite Score: 39/100 — RED CRITICAL**

Early Warning Triggers also fired:
- ✅ Usage drop >50% week-over-week (redlines dropped from 22 → 4)
- ✅ NPS detractor response logged 3 weeks ago (closed-loop overdue)

**Automated Actions Generated:**
1. Urgent CSM task created: "Meridian Financial — CRITICAL — call required today 3/10"
2. VP CS Slack alert sent at 8:00 AM with account ARR ($45K), trigger summary, and suggested VP outreach
3. Executive email template pre-populated in CS platform (VP-to-GC level outreach)
4. NPS closed-loop task flagged as overdue — CSM required to complete within 24 hours

## Success Metrics

- **Churn prediction accuracy**: Health score model should correctly predict churn for ≥70% of accounts that churn (i.e., Red accounts account for ≥70% of churned ARR within the following 90 days)
- **Early intervention rate**: ≥80% of at-risk (Yellow/Red) accounts should receive CSM outreach within defined SLA
- **Rescue rate**: Of accounts that enter Red tier, ≥30% should return to Yellow or Green within 60 days after intervention
- **Surprise churn rate**: Accounts that churn from Green tier (score >70) should be <10% of total churn (high Green churn = model needs recalibration)
- **Score review coverage**: 100% of Red accounts reviewed in weekly standup; 100% of accounts entering 90-day renewal window reviewed with current score
- **Gross revenue churn impact**: A well-deployed health score system should reduce gross churn by 2–4 percentage points within 12 months of implementation

## Related Prompts

- `../../06_Customer-Success-&-Retention/Churn-Prevention-&-Expansion/Churn-Prevention-Expansion-Revenue-Engine.md`
- `../../06_Customer-Success-&-Retention/Customer-Success-Automation/QBR-EBR-Automation-Engine.md`
- `../../06_Customer-Success-&-Retention/Customer-Success-Automation/NPS-CSAT-Closed-Loop-Intelligence-Engine.md`
- `../../05_Analytics-&-Marketing-Operations/Advanced-Marketing-Intelligence/Predictive-Revenue-Forecasting-Engine.md`

## Integration Tips

- **Gainsight**: Map each signal in this framework to a Gainsight CTA (Call to Action) rule. Use Gainsight's Rules Engine to automate score recalculation daily and trigger CTAs for each tier change and early warning event. Use Scorecards 2.0 for the weighted composite model.
- **ChurnZero**: Configure ChurnScore using the weighted signal library above. Map each Early Warning Trigger to a ChurnZero Play. Use the Journey feature to automate the intervention playbook sequences.
- **HubSpot**: Build a custom "Customer Health" property (0–100) synced from your CS platform or product analytics. Create workflows triggered by score thresholds to auto-assign tasks, send internal notifications, and enroll accounts in email sequences.
- **Pendo / Amplitude**: Set up custom dashboards for each core usage signal. Use Pendo Segments or Amplitude Cohorts to define "active user" vs. "dormant user" thresholds, then push segment membership to your CRM via API for real-time health score updates.
- **Slack**: Configure webhook alerts from your CS platform for all Early Warning Trigger fires and Red-tier movements. Create a #cs-alerts channel with threaded account context so CSMs can respond and log actions without leaving Slack.
- **Google Sheets / Notion**: For teams without a dedicated CS platform, build a manual health score tracker using the scoring model above, refreshed weekly. Link to Zapier to auto-populate from HubSpot CRM fields and Stripe billing data.

## Troubleshooting

**Problem: Health scores are accurate but CSMs don't act on them**
Fix: Adoption failure — not a data problem. The model works only if CSMs trust it and have time to act. Two fixes: (1) Reduce noise — if every account is triggering alerts, CSMs stop paying attention. Tighten Early Warning thresholds so alerts are genuinely urgent. (2) Tie health score to CSM performance goals — if CSMs are measured on rescue rate and NRR improvement within their book, health score management becomes intrinsic. Never treat health score as a reporting metric for leadership only; make it the primary CSM workflow tool.

**Problem: Green accounts keep churning (surprise churn)**
Fix: Your model is missing a signal. Surprise churn from Green accounts is diagnostic — it means a key churn predictor isn't in your model. Run a cohort analysis on the last 12 months of Green-to-churn accounts and look for what they had in common that wasn't captured in your score. Common missed signals: champion job change (relationship signal), new competitor adoption (intent signal), failed expansion conversation (leading indicator of dissatisfaction), and budget freeze at the company level (financial signal from LinkedIn/news).

**Problem: Score model produces too many Red accounts and overwhelms the CS team**
Fix: Your weights are too aggressive or your thresholds are too low. A healthy model should have ~10–15% of ARR in Red at any given time. If you're seeing 30%+, recalibrate the scoring model: (1) Raise the "Critical" threshold from 0–39 to 0–29, shifting Yellow to 30–54; (2) Review whether single low-usage weeks are dragging scores down — switch usage signals to 30-day rolling averages instead of 7-day; (3) Temporarily prioritize interventions by ARR × churn probability (Red accounts over $50K first) until the system is calibrated.

## Version History
- v1.0: Initial creation (auto-generated)
