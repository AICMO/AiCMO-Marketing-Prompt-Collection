# Churn Prevention & Expansion Revenue Engine - Predict, Prevent, and Convert At-Risk Accounts Into Growth

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** churn-prevention, expansion-revenue, net-revenue-retention, customer-health, upsell, b2b-saas, customer-success, automation

## Overview
Automatically score every account for churn risk and expansion potential, generate personalized intervention playbooks for at-risk customers, and surface upsell/cross-sell opportunities at the exact moment a customer is most likely to expand. Use this when you want to protect NRR (Net Revenue Retention) above 110% and convert your CS team from reactive firefighters into proactive revenue drivers.

## Quick Copy-Paste Version

You are a senior Customer Success strategist specializing in churn prevention and expansion revenue for B2B SaaS companies.

My business context:
- Company: [Your Company Name]
- Product: [What you sell, e.g., B2B revenue intelligence platform]
- Total ARR: [e.g., $4.2M]
- Number of accounts: [e.g., 180 accounts]
- Average ACV: [e.g., $23K]
- Current NRR: [e.g., 98%]
- Churn rate (annual): [e.g., 14%]
- CRM / CS platform: [HubSpot / Salesforce / Gainsight / ChurnZero / other]
- Product analytics tool: [Mixpanel / Amplitude / Heap / Pendo / other, or "none"]

Deliver a complete churn prevention and expansion revenue system with these components:

1. CHURN RISK SCORING MODEL
   - 10 leading indicators of churn (usage, engagement, support, sentiment, payment, relationship signals)
   - Weighted scoring formula I can implement in a spreadsheet or CS platform
   - Three risk tiers: Red (act in 14 days), Yellow (act in 30 days), Green (monitor monthly)
   - Trigger events that auto-escalate any account to Red regardless of score

2. INTERVENTION PLAYBOOK BY TIER
   For each risk tier, provide:
   - Who owns the intervention (CSM, Account Exec, VP CS, CEO)
   - Outreach sequence: subject lines, email body, call talk track — all production-ready
   - What to offer (success review, custom training, executive sponsor call, commercial remedy)
   - Escalation path if no response within X days

3. EXPANSION OPPORTUNITY IDENTIFICATION
   - 8 behavioral and firmographic signals that predict upgrade readiness
   - Upsell trigger logic: "When [event], send [message] with [offer]"
   - Cross-sell conversation starters mapped to each product tier or add-on
   - Expansion email sequence (3 emails) with subject lines and body copy

4. AUTOMATED QBR PREPARATION BRIEF
   - Data points to pull 48 hours before each QBR
   - Narrative structure: Value Delivered → Adoption Gaps → Expansion Roadmap
   - 5 questions to ask that surface expansion pain without being pushy

5. WIN-BACK CAMPAIGN FOR RECENTLY CHURNED ACCOUNTS
   - Timing: when to reach out after churn (30 / 60 / 90 days)
   - 3-email win-back sequence with subject lines
   - Offer structure: what incentive justifies re-engagement
   - Qualification criteria: which churned accounts are worth targeting

6. NRR METRICS DASHBOARD
   - 10 weekly and monthly metrics to track
   - Red/Yellow/Green thresholds for each metric
   - Leading vs. lagging indicator breakdown

Make every deliverable production-ready with specific copy, not frameworks. Use realistic numbers and industry benchmarks throughout.

## Advanced Customizable Version

You are a world-class Customer Success and Revenue Operations strategist with 15+ years building high-NRR SaaS businesses. You have led CS teams at companies scaling from $1M to $100M ARR and know exactly which signals predict churn 60-90 days before it happens. Your frameworks have been used to drive NRR from 95% to 130% at multiple portfolio companies.

COMPANY CONTEXT:
- Company name: [Company]
- Product category: [e.g., project management SaaS for construction firms]
- Total ARR: [ARR]
- Customer count: [Count] accounts, [Count] users
- Segment breakdown: [e.g., 20 Enterprise ($50K+ ACV), 80 Mid-Market ($10-50K), 80 SMB (<$10K)]
- Average ACV: [ACV] | Average contract length: [e.g., 12-month annual]
- Current NRR: [NRR]% | Gross Revenue Retention (GRR): [GRR]%
- Logo churn rate: [X]% annually
- Expansion revenue as % of new ARR: [X]%
- CS team structure: [e.g., 3 CSMs, 1 CS Ops, 1 onboarding specialist]
- CS-to-account ratio: [e.g., 1 CSM : 60 accounts]
- CRM: [Tool] | CS platform: [Tool] | Product analytics: [Tool]
- Available data: [Check all that apply: login frequency, feature adoption, support ticket volume, NPS/CSAT scores, payment history, contract renewal dates, champion job changes, executive sponsor engagement]

OBJECTIVE:
Build a fully automated churn prevention and expansion revenue engine that a 3-person CS team can operate without adding headcount. Every output must be deployable into [CRM/CS platform] within 2 weeks.

---

DELIVERABLE 1: PREDICTIVE CHURN RISK MODEL

Build a 100-point health score with these weighted dimensions:

Product Adoption (30 points):
- Login frequency vs. cohort baseline (daily/weekly/monthly active)
- Feature adoption depth (core features used vs. available)
- User seat utilization (active users / licensed seats)
- Mobile vs. desktop usage patterns (if applicable)

Engagement Signals (25 points):
- Executive sponsor last login date
- CS touchpoint recency (last meaningful interaction, not automated)
- QBR attendance rate (last 2 QBRs)
- Response rate to CS outreach (emails, calls)

Relationship & Sentiment (20 points):
- NPS score trajectory (improving / stable / declining)
- CSAT on last 3 support interactions
- Champion turnover risk (LinkedIn job change monitoring)
- Expansion conversations initiated (yes/no in last 90 days)

Commercial Risk (15 points):
- Payment failures or delays in last 6 months
- Open support tickets > 14 days unresolved
- Contract renewal date proximity (< 90 days = risk flag)
- Discount depth vs. peers (heavily discounted = low switching cost perception)

External Signals (10 points):
- Company headcount change (>20% reduction = risk)
- Funding status (no new funding in 24+ months for funded companies)
- Industry-specific economic indicators (if applicable)

SCORING TIERS:
- 80-100: Healthy (Green) — monthly check-in, expansion priority
- 60-79: Neutral (Yellow) — bi-weekly proactive outreach, identify friction
- 40-59: At-Risk (Orange) — weekly intervention, loop in AE
- 0-39: Critical (Red) — immediate executive escalation, intervention within 48 hours

HARD TRIGGERS (auto-escalate to Red regardless of score):
List 8 events that trigger immediate escalation: champion submits resignation on LinkedIn, 3 consecutive missed QBRs, support ticket marked "executive escalation," login frequency drops >60% week-over-week for 3 consecutive weeks, payment failure with no response in 5 business days, account opens competitor comparison page (if detectable via intent data), champion responds negatively to NPS with score 0-3, legal requests contract termination language.

---

DELIVERABLE 2: INTERVENTION PLAYBOOK BY TIER

For each health tier (Yellow, Orange, Red), provide:

A. OUTREACH SEQUENCE
Yellow tier:
- Touch 1 (Day 0): Personalized email from CSM referencing specific usage data. Subject line + full body. Offer: 30-min optimization session.
- Touch 2 (Day 7): Calendar invite with pre-filled agenda. Subject + body.
- Touch 3 (Day 14): Phone call talk track (90-second opening, 3 discovery questions, close for meeting).
- Touch 4 (Day 21): Loop in AE with warm intro email if no response.

Red tier:
- Touch 1 (Day 0): CSM email + VP CS phone call simultaneously. Both templates provided.
- Touch 2 (Day 2): VP CS LinkedIn direct message template.
- Touch 3 (Day 5): CEO/founder direct outreach template.
- Emergency lever: Commercial remedy decision tree — when to offer discount vs. free seats vs. success guarantee vs. partial refund.

B. SAVE OFFER DECISION TREE
Map save offer to churn reason:
- "Not getting value" → Dedicated success sprint: weekly CSM sessions for 60 days, custom implementation review, KPI dashboard built specifically for their use case.
- "Too expensive / budget cut" → Temporary seat reduction with 90-day re-expansion clause, or quarterly billing vs. annual, or success-based pricing pilot.
- "Champion left" → New champion onboarding package: 3 live training sessions, executive sponsor re-engagement call from VP CS, 30-day adoption guarantee.
- "Competitor offering more features" → Feature gap analysis with honest assessment + roadmap preview for relevant items, plus white-glove migration cost comparison.
- "Internal project deprioritized" → Pause option (30-60 days, no charge) with re-engagement trigger tied to their internal milestone.
- "Consolidating vendor stack" → Integration depth demo showing native connections that reduce their overall vendor count.

---

DELIVERABLE 3: EXPANSION REVENUE IDENTIFICATION ENGINE

EXPANSION TRIGGER EVENTS — provide 10 triggers with exact workflow:
Format: "When [trigger], [automated action] fires within [timeframe]."

Core triggers to build from:
- Seat utilization > 85% for 30 consecutive days → CSM expansion email queued + AE deal created
- New department starts using product organically (new user emails from different domain department) → Multi-team expansion sequence triggered
- Champion promoted to Director or above → Congratulations email from AE + strategic value conversation scheduled
- Company announces Series B+ funding → AE notified with account enrichment data + outreach template
- Feature request submitted for premium-tier functionality → CSM flagged to reference in next touchpoint
- QBR shows ROI > 3x stated business case → Expansion conversation bridge deployed in same meeting
- Support ticket for capability only in enterprise plan → CSM receives Slack alert to use as natural upgrade conversation
- Account hits 90% of any usage limit → Automated warning email + upgrade CTA
- New competitor of customer wins major customer (signals growth intent) → AE personalized outreach referencing market opportunity
- Anniversary of go-live with strong adoption → Success milestone email with expansion ROI framing

EXPANSION EMAIL SEQUENCES (3 complete sequences, subject + full body):
1. Seat expansion sequence — triggered when capacity approaches limit
2. Tier upgrade sequence — triggered when behavior maps to premium features
3. Multi-team expansion sequence — triggered when viral adoption spreads to new department

UPSELL CONVERSATION FRAMEWORK:
- Exact QBR moment to raise expansion (after ROI slide, before 90-day roadmap — never in first 15 minutes)
- 3 expansion discovery questions that feel like genuine CS interest
- ROI framing using their own usage data (formula: [metric improvement] x [business value per unit] = [annualized expansion ROI])
- Objection responses for: "Not in budget right now," "Need to get buy-in from [stakeholder]," "We haven't fully adopted what we have," "Let's revisit at renewal"

---

DELIVERABLE 4: AUTOMATED QBR PREPARATION SYSTEM

48-HOUR PRE-QBR DATA PULL:
Exact fields to pull from each system and how to synthesize into a 90-second CSM briefing.

QBR SLIDE STRUCTURE:
1. Value Delivered (metrics-first: X hours saved, Y% improvement in [KPI], $Z revenue impact)
2. Adoption Heatmap (features used vs. available, power users vs. occasional users, unused seats)
3. ROI Quantification (their stated goal at kickoff vs. current actuals)
4. Top 3 Friction Points with resolution owners and deadlines
5. 90-Day Success Roadmap tied to their Q2/Q3 business objectives
6. Expansion Bridge (health score > 70 only): "Based on what you've told me today..."

5 QBR EXPANSION QUESTIONS:
Write each question, the positive-signal follow-up, and the bridge statement to proposal.

---

DELIVERABLE 5: WIN-BACK CAMPAIGN

QUALIFICATION CRITERIA: Target churned accounts with ACV > $10K, churn reason not "product-market fit failure," time since churn 30-180 days, no active legal dispute.

WIN-BACK SEQUENCE:
- 30-day email (subject + body, 110 words, empathetic tone — acknowledge the failure, own it)
- 60-day email (subject + body, 130 words — lead with a specific product improvement or new customer proof point relevant to their use case)
- 90-day call talk track (60-second opening, 3 re-qualification questions, reduced-risk re-entry offer)
- 6-month final outreach (email + LinkedIn from VP CS or CEO — different messenger, fresh perspective)

WIN-BACK OFFER BY CHURN REASON:
- Left for competitor: 60-day free trial of enterprise tier, no commitment, data migration covered
- Budget cut: Month-to-month pricing for 6 months at 20% discount, then standard annual
- Champion left: New executive sponsor welcome package + 90-day success guarantee with refund clause

---

DELIVERABLE 6: NRR COMMAND CENTER

WEEKLY METRICS (Monday review):
1. Health score distribution shift (accounts moving between tiers week-over-week)
2. Red accounts: count, total ARR at risk, intervention owner, days since trigger
3. Expansion pipeline: opportunities identified, conversations active, deals in legal
4. Save rate: interventions attempted vs. confirmed retentions (rolling 90-day)
5. New churn signals detected (volume and type breakdown)

MONTHLY METRICS:
6. Gross Revenue Retention (GRR) — expansions excluded
7. Net Revenue Retention (NRR) — expansion, contraction, churn waterfall breakdown
8. Time-to-detection: average days from first churn signal to CSM intervention
9. QBR completion rate and average health score delta 30 days post-QBR
10. Expansion revenue by trigger type with conversion rate per trigger

STAGE BENCHMARKS:
- Seed/Series A: GRR >85%, NRR >100%
- Series B/C: GRR >88%, NRR >110%
- Growth/Pre-IPO: GRR >90%, NRR >120%
- Best-in-class (top quartile): GRR >93%, NRR >130%

OUTPUT FORMAT INSTRUCTIONS:
Deliver each section with clear headers. All email copy must be complete and production-ready — the only placeholders should be account-specific data fields like [First Name], [Company], [metric]. Include word count for every email template. Explicitly flag which workflow steps are fully automatable vs. require CSM judgment. Provide Gainsight CTA names and HubSpot workflow trigger logic for every automated step.

## Example Input/Output

**Input Example:**

Company: Structurely — AI-powered lead qualification SaaS for real estate brokerages. 210 accounts, $28K average ACV, $5.9M ARR, current NRR 102%, logo churn 11% annually. CS team: 2 CSMs managing 105 accounts each, no dedicated CS Ops. CRM: HubSpot. Product analytics: Mixpanel. Available data: login frequency, feature adoption rates, NPS (quarterly), support ticket volume, payment history.

**Output Example (Partial):**

Churn Risk Model — Structurely Implementation:

Health Score Breakdown:
- Login frequency (10 pts): Structurely requires daily outreach activity. Accounts with fewer than 2 logins/week score 0; 2-4/week score 5; 5+/week score 10. Pulled from Mixpanel "Active Days" event, synced to HubSpot via Zapier.
- Feature adoption (20 pts): Three core modules — AI Conversation (primary value driver), Reporting Dashboard (stickiness indicator), CRM Sync (integration depth). Using all 3 = 20 pts; 2 of 3 = 12 pts; 1 of 3 = 0 pts.
- Hard Trigger: Any brokerage account showing >40% headcount reduction on LinkedIn (detectable via Clay or Kaspr enrichment) auto-escalates to Red within 24 hours regardless of health score.

Red-Tier Outreach (Day 0 — CSM Email, 94 words):
Subject: Quick question about your Structurely results, [First Name]

Hi [First Name], I was reviewing your team's activity in Structurely this week and noticed conversation volume dropped about 60% from your February baseline. Before we get to your upcoming renewal, I want to make sure we're solving whatever's getting in the way. I've seen this pattern before — usually it's one of three things — and all of them are fixable in under two weeks. Can I grab 20 minutes with you this week? Here's my calendar: [Link]. — [CSM Name]

Expansion Trigger — Seat Capacity (automated):
Trigger: Seat utilization hits 87% (18 of 21 licensed agents active for 21+ consecutive days, detected via Mixpanel cohort + HubSpot property sync).
HubSpot Workflow: Create "Expansion Opportunity" deal in pipeline, assign to paired AE, queue CSM email for 9am next business day, add task "Confirm expansion conversation in next QBR."

CSM Expansion Email (112 words):
Subject: Your team is maxing out Structurely — here's what that means

Hi [First Name], great news — your team's adoption puts you in the top 15% of Structurely accounts. With 18 of your 21 licenses fully active heading into spring market, you're approaching capacity at exactly the wrong time. I pulled your last 90-day ROI: your team converted 34% more leads than the quarter before implementing Structurely. With 3 more agents licensed, that's an estimated $190K in incremental closed commission annually at your average deal size. Worth a 20-minute look before you hit any limits? [Calendar link] — [CSM Name]

NRR Dashboard Snapshot (Week of Mar 2):
Red accounts: 4 ($312K ARR at risk). Interventions in progress: 2. Saves confirmed this week: 1 ($48K retained). Expansion pipeline: 7 active opportunities ($89K expansion ARR identified). Net new expansion MTD: +$34K MRR ($408K annualized run rate).

## Success Metrics
- Churn signal detection lead time: identify risk 60+ days before renewal (industry baseline: 14 days out)
- Save rate: >40% of Red-tier accounts retained after intervention (industry average: 28%)
- Expansion revenue as % of total new ARR: target 30-40% within 12 months of implementation
- NRR improvement: +8-15 percentage points within 6 months of full system deployment
- Time-to-intervention: <48 hours from trigger event to first CSM outreach confirmed in CRM

## Related Prompts
- [Customer Advocacy & Referral Revenue Engine](../Customer-Advocacy-&-Referral/Customer-Advocacy-Referral-Revenue-Engine.md)
- [Customer Onboarding Intelligence System](../Customer-Onboarding-&-Activation/Customer-Onboarding-Intelligence-System.md)
- [Customer Success Automation Engine](../Customer-Success-Automation/Customer-Success-Automation-Engine.md)
- [Customer LTV CAC Optimization Engine](../../05_Analytics-&-Marketing-Operations/Advanced-Marketing-Intelligence/Customer-LTV-CAC-Optimization-Engine.md)

## Integration Tips
- **Gainsight / ChurnZero:** Map all six health score dimensions directly to scorecard fields. Configure automated CTAs (calls-to-action) that fire when any account crosses a tier threshold. Use Timeline to auto-log every intervention touch and track save attempts over time. Set Cockpit priority rules so Red accounts always surface first in CSM queues.
- **HubSpot:** Build a custom "Account Health Score" calculated property using a HubSpot Operations Hub formula. Use Workflow enrollment triggers on score range changes to assign tasks, enroll contacts in sequences, and create deals in the expansion pipeline. Build a "Churn Risk" board view filtered by health score tier for weekly Monday reviews.
- **Salesforce + Totango:** Sync Totango health scores to Salesforce Account fields via the native integration. Configure Einstein Activity Capture to log CS touchpoints automatically. Use Flow Builder to create intervention tasks within 1 hour of any hard trigger firing.
- **Mixpanel / Amplitude:** Build a "Disengaged Users" cohort (fewer than X events in 30 days, segmented by account). Export this cohort to HubSpot or Salesforce via native integration or Zapier. Create Slack alerts using Mixpanel's alert feature when any key account drops below the engagement threshold defined in the health score model.
- **Slack:** Configure a #churn-risk channel with automated alerts from your CS platform or HubSpot. Alert format: Account Name | ACV | Renewal Date | Trigger That Fired | Health Score | Assigned CSM. This gives the full CS team visibility without requiring daily dashboard logins.
- **Google Sheets (no CS platform):** Build the health score formula using IMPORTRANGE pulling from weekly CRM CSV exports. Use conditional formatting for Red/Yellow/Green tier visualization. Add a Loom walkthrough each Monday narrating the week's changes. This approach handles up to ~150 accounts before the overhead justifies a dedicated CS platform investment.

## Troubleshooting
- **Problem:** Health score model is too complex for the CS team to maintain without a dedicated CS Ops resource.
  **Solution:** Start with exactly 3 inputs: login frequency (weekly), most recent NPS score, and count of support tickets open more than 14 days. This 3-variable model captures approximately 70% of churn signal with 10% of the implementation complexity. Add additional dimensions one per quarter as your data instrumentation matures and the team builds confidence in the model.

- **Problem:** Intervention emails go unanswered and accounts still churn despite proactive outreach.
  **Solution:** The root cause is almost always timing (detecting churn too late) or personalization (copy is too generic). Reference the specific data point that triggered the alert in the first sentence of every outreach — never open with "I wanted to check in." Accounts contacted with usage-specific language reply at 3-4x the rate of generic check-ins. If you are detecting churn signals fewer than 30 days from renewal, your model thresholds are set too late — move detection triggers to 90-day pre-renewal windows.

- **Problem:** CS team cannot approve save offers (discounts, free seats, billing changes) without slow multi-day sign-off that lets accounts churn while waiting.
  **Solution:** Pre-authorize a tiered save offer menu by ACV bracket, documented in writing from leadership. Recommended structure: accounts below $15K ACV — CSM can offer 1-month free extension or 1 bonus seat without any approval. Accounts $15K-$50K ACV — CSM plus AE can jointly approve up to 15% discount or 2 months free. Accounts above $50K ACV — VP CS must approve within 24 hours maximum, not 72. The cost of slow approvals is always higher than the cost of the offer itself.

## Version History
- v1.0: Initial creation (auto-generated)
