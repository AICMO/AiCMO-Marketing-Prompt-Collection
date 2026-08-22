# AI-Powered B2B SaaS Autonomous Cross-Channel Budget Optimization & Real-Time Marketing Spend Reallocation Revenue Intelligence Engine - Build an AI Agent That Continuously Moves Budget to the Channels Generating the Most Pipeline

**Difficulty:** Advanced | **Time:** 30-45 min | **Tags:** demand gen ops, budget optimization, cross-channel, marketing ROI, spend reallocation, pipeline attribution, real-time, AI agents, revenue operations, HubSpot, Salesforce, Google Ads, LinkedIn Ads, marketing automation

## Overview
Designs and deploys an AI-agent-managed system that monitors cross-channel marketing performance in real-time, automatically reallocates spend from underperforming channels to overperforming ones, and enforces revenue-weighted budget guardrails — without requiring weekly human budget reviews. Use this when your marketing budget is spread across 6+ channels, you're losing pipeline due to slow reallocation decisions, or you want to replace the monthly "budget meeting" with a continuously optimizing spend engine.

## Quick Copy-Paste Version

You are a senior B2B SaaS demand generation operations architect specializing in AI-agent-managed budget optimization. Design a fully autonomous cross-channel budget reallocation system for a B2B SaaS company.

COMPANY INPUTS:
- Company: [e.g., "Conduit — B2B SaaS revenue operations platform for mid-market sales teams"]
- Monthly marketing budget: [e.g., "$180,000/month total"]
- Current channel mix: [e.g., "Google Ads $45K, LinkedIn Ads $55K, content/SEO $20K, events $30K, outbound SDR tools/data $20K, direct mail $10K"]
- Revenue goal: [e.g., "$2.4M in marketing-sourced pipeline per quarter"]
- CRM: [HubSpot / Salesforce / other]
- Attribution model: [First-touch / Last-touch / Multi-touch linear / Time-decay / Data-driven]
- Reporting cadence: [Daily / Weekly / Real-time dashboard]

DELIVERABLES:

1. PERFORMANCE MONITORING ARCHITECTURE
Define the exact KPIs and thresholds for each channel that trigger a reallocation event:
- Primary metric: Cost per Marketing Qualified Lead (MQL), Cost per Sales Qualified Opportunity (SQO), Cost per pipeline dollar (CPP)
- Threshold triggers: When does a channel go on "scale" vs. "hold" vs. "pause"?
- Lagging vs. leading indicators: What early signals (CTR, CPC, lead volume) predict whether SQO cost will degrade before it shows in the pipeline data?
- Data freshness requirements: How often must data refresh for the AI agent to make accurate reallocation decisions?

2. REALLOCATION RULES ENGINE
Define the decision logic for automated budget moves:
- Rule 1 (Underperformance): If [channel] CPP exceeds [X]% above blended average for [Y] consecutive days, reduce budget by [Z]%
- Rule 2 (Overperformance): If [channel] CPP is [X]% below blended average with >$[Y] remaining monthly budget headroom, increase by [Z]%
- Rule 3 (Quality degradation): If lead-to-SQO conversion drops below [X]% on a channel for [Y] days, pause regardless of volume
- Rule 4 (Budget floor/ceiling): No single channel drops below [X]% or exceeds [Y]% of total monthly budget
- Rule 5 (Pipeline gap response): If monthly pipeline is tracking [X]% below target by day 15, trigger emergency reallocation protocol

3. AUTONOMOUS REALLOCATION WORKFLOW
Design the step-by-step AI agent workflow:
- Data ingestion: What APIs, reports, and CRM fields the agent reads daily
- Scoring: How the agent weights each channel's pipeline contribution vs. spend
- Decision: The reallocation calculation logic (with example numbers)
- Execution: What the agent does automatically vs. what requires human approval
- Notification: What alerts fire to the CMO/Demand Gen lead and at what thresholds
- Audit log: How every reallocation decision is recorded with rationale

4. CHANNEL-SPECIFIC OPTIMIZATION ACTIONS
For each active channel, define what the AI agent can adjust autonomously:
- Paid search: Keyword bids, campaign budgets, ad scheduling, audience exclusions
- Paid social: Campaign budgets, bid strategies, audience refresh triggers, creative rotation
- Outbound/SDR tools: Sequence volume, data purchase cadence, territory allocation
- Events/field: Hold/cancel recommendations based on pipeline tracking
- Content/SEO: Promotion budget, content refresh prioritization based on conversion data

5. WEEKLY AUTONOMOUS REPORT
Design the auto-generated report format the agent sends to marketing leadership every Monday at 7am:
- Executive summary: Pipeline tracking vs. goal, budget spent vs. plan, top reallocation action taken
- Channel performance table: Spend | Leads | MQLs | SQOs | Pipeline | CPP | vs. last week | Trend
- Reallocation log: Decisions made in the past 7 days with rationale and pipeline impact estimate
- Alerts: Channels showing early degradation signals that haven't yet triggered auto-reallocation
- Recommendations: 1-3 strategic adjustments requiring human decision (budget increases, new channel tests, contract negotiations)

Output this as an actionable blueprint a demand gen operations manager can implement in HubSpot + Google Ads + LinkedIn Ads + Zapier within 30 days.

## Advanced Customizable Version

ROLE: You are a Principal Demand Generation Operations Architect with 18+ years of experience building AI-native, autonomous marketing operations systems for B2B SaaS companies. You have designed real-time budget optimization engines for companies from Series B ($8M ARR) through pre-IPO ($200M ARR), managing aggregate marketing spend exceeding $400M across paid search, paid social, outbound, field marketing, content, and direct mail. You understand the technical architecture of marketing data pipelines, the mechanics of each ad platform's budget system, CRM attribution models, and the organizational dynamics of transitioning from manual weekly budget reviews to autonomous AI-managed optimization. You design systems for operational excellence: every reallocation decision is logged with full rationale, every threshold is calibrated to historical win rates, and the human-in-the-loop touchpoints are designed to preserve strategic judgment while eliminating low-value operational meetings.

OBJECTIVE: Build a production-ready autonomous cross-channel budget optimization system that:
- Monitors all marketing channel performance daily against revenue-weighted KPIs
- Executes pre-approved budget reallocations automatically when performance thresholds are breached
- Surfaces only high-stakes decisions (new channel investment, budget increases above 20%, program cancellation) to human review
- Reduces the time marketing leadership spends on budget operations from 8+ hours/week to <2 hours/week
- Improves pipeline-per-dollar efficiency by 15-25% within 90 days through faster reallocation response times

---

COMPANY & PROGRAM INPUTS:

Company Profile:
- Company name and product: [e.g., "Conduit — AI-native revenue operations platform that automates CRM hygiene, forecasting, and sales process enforcement for B2B SaaS companies with 50-500 AEs"]
- ARR and growth stage: [e.g., "Series C, $42M ARR, growing 65% YoY, targeting $68M ARR"]
- ICP: [e.g., "VP Revenue Operations, CRO, and VP Sales at B2B SaaS companies with 200-2,000 employees, 50+ AEs, Salesforce CRM"]
- ACV: [e.g., "$85,000 average, range $35K-$300K, annual commitment"]
- Sales motion: [e.g., "Sales-led — inbound MQL to SDR qualification, AE demo, 45-75 day sales cycle, multi-stakeholder (CRO + VP RevOps + IT security)"]

Marketing Budget Architecture:
- Total monthly marketing budget: [e.g., "$220,000"]
- Current channel allocation:
  * Google Ads (paid search + PMax): [e.g., "$52,000 — 24% of budget"]
  * LinkedIn Ads (sponsored content + document ads + TLA): [e.g., "$68,000 — 31% of budget"]
  * Outbound (SDR tools, data, sequences): [e.g., "$30,000 — 14% of budget"]
  * Events/field marketing: [e.g., "$38,000 — 17% of budget"]
  * Content & SEO (tools, freelancers, promotion): [e.g., "$18,000 — 8% of budget"]
  * Direct mail & gifting (ABM Tier 1): [e.g., "$14,000 — 6% of budget"]
- Pipeline target: [e.g., "$3.2M marketing-sourced pipeline per quarter, $8M influenced"]
- Revenue target: [e.g., "$1.1M marketing-sourced closed-won per quarter at 34% average win rate"]

Technology Stack:
- CRM: [Salesforce / HubSpot / other — specify instance setup]
- Marketing automation: [Marketo / HubSpot Marketing Hub / Pardot / other]
- Attribution tool: [Bizible/Marketo Measure / HubSpot attribution / Triple Whale / Northbeam / custom UTM + CRM]
- Paid media management: [Native platforms (Google Ads, LinkedIn Campaign Manager) / Madgicx / Skai / other]
- Data warehouse: [Snowflake / BigQuery / Redshift / none — using CRM reports only]
- BI/reporting: [Tableau / Looker / Power BI / HubSpot dashboards / Google Data Studio]
- Workflow automation: [Zapier / Make / n8n / internal engineering / Salesforce Flow]

Historical Performance Benchmarks (fill in what you have):
- Blended CPL (cost per lead): [e.g., "$285"]
- Blended cost per MQL: [e.g., "$620"]
- Blended cost per SQO: [e.g., "$3,800"]
- Blended cost per pipeline dollar created: [e.g., "$0.068 or 6.8 cents per dollar of pipeline"]
- Lead-to-MQL conversion rate: [e.g., "28%"]
- MQL-to-SQO conversion rate: [e.g., "22%"]
- SQO-to-Closed Won rate: [e.g., "34%"]
- Average sales cycle: [e.g., "58 days"]

---

SYSTEM ARCHITECTURE DESIGN:

SECTION 1: DATA INFRASTRUCTURE & PERFORMANCE MONITORING LAYER

Design the complete data monitoring architecture:

1.1 — Daily Data Ingestion Specification
For each channel, specify:
- Data source API or export: What data does the AI agent pull daily, and from which platform API/report/webhook?
- Key fields required: Spend, impressions, clicks, CTR, CPC, conversions (by type: form fill, demo request, content download), conversion rate
- CRM sync requirements: How are leads from each channel tagged, attributed, and synced to the CRM within 24 hours?
- Lag correction: For channels with attribution lag (events, outbound, content), how does the agent adjust for incomplete data?

1.2 — Revenue-Weighted Channel Scoring Model
Design a composite channel score (0-100) based on:
- Pipeline contribution score (40% weight): Marketing-influenced pipeline generated in trailing 60 days divided by channel spend, normalized to blended average
- Lead quality score (30% weight): Channel-specific lead-to-SQO conversion rate vs. blended average, trended over 30 days
- Velocity score (15% weight): Average days from channel first-touch to SQO creation, compared to blended average
- Trend score (15% weight): 7-day vs. 30-day performance trajectory (improving, flat, degrading)

Score interpretation:
- 80-100: "Scale" — eligible for budget increase up to 25% of current spend
- 60-79: "Maintain" — hold current spend, monitor for trend changes
- 40-59: "Watch" — flag for human review, no automatic increase
- 20-39: "Reduce" — automatic 15% spend reduction trigger
- 0-19: "Pause" — automatic pause, human approval required to restart

1.3 — Early Warning Signal Library
Define the leading indicators the agent monitors before pipeline impact shows in lagging data:
- Paid search: Quality Score drops >1.5 points, impression share lost to budget >20%, click-to-MQL rate drops >30% week-over-week
- Paid social: CTR drops >40% below 30-day average (creative fatigue), frequency >4.5 in 7-day window, CPL exceeds 2x blended average for 3 consecutive days
- Outbound SDR: Reply rate drops below 2%, meeting show rate drops below 55%, sequence-to-SQO rate drops below 8%
- Events: Registration pace tracking >25% below plan with 3 weeks to event, historical post-event SQO rate below 8% for this event type/tier
- Content/SEO: Organic sessions-to-demo-request conversion rate drops >35% from 90-day baseline

---

SECTION 2: REALLOCATION RULES ENGINE

Design the complete decision logic:

2.1 — Standard Reallocation Triggers (Execute Automatically)

Rule Type A — Underperformance Response:
- Trigger: Channel composite score drops to 20-39 range AND sustains for 5 consecutive days
- Action: Reduce channel spend by 15% of current monthly budget
- Constraint: No channel reduced below [define floor %] of total budget without human approval
- Notification: Slack/email alert to Demand Gen Manager with trigger rationale and projected monthly savings
- Review window: Re-score after 14 days; if score remains <40, trigger second 15% reduction

Rule Type B — Overperformance Scaling:
- Trigger: Channel composite score reaches 80+ AND channel spend has not been increased in past 21 days AND available budget headroom exists (other channels at "Reduce" or "Maintain" status)
- Action: Increase channel spend by 20% (funded by reduction from lowest-scoring channel)
- Constraint: No channel may exceed [define ceiling %] of total monthly budget
- Constraint: Total budget does not exceed monthly authorized amount
- Notification: Slack/email confirmation with projected pipeline impact at new spend level

Rule Type C — Quality Degradation Pause:
- Trigger: Lead-to-SQO conversion for a channel drops below 60% of blended average for 14 consecutive days (quality alarm, independent of volume)
- Action: Pause demand capture campaigns; maintain brand/awareness spend at 25% of prior level
- Human approval required to resume full spend: Demand Gen lead must review lead quality audit before restart
- Notification: Immediate Slack alert with lead quality data, last 30 days vs. prior 30 days

Rule Type D — Pipeline Emergency Protocol:
- Trigger: Cumulative marketing-sourced pipeline at day 15 of month tracking below 55% of monthly target
- Action: Shift 20% of budget from lowest-scoring channels to highest-scoring channels; increase outbound SDR sequence volume by 30% from reserve capacity; escalate to CMO dashboard
- Rationale: At day 15, the remaining 16 days are insufficient to close a pipeline gap without emergency acceleration; faster reallocation compresses the lag

2.2 — Budget Floor & Ceiling Guardrails (Hard Rules, Cannot Be Overridden Automatically)
- No single channel may fall below [e.g., 5%] of monthly budget without CMO approval
- No single channel may exceed [e.g., 40%] of monthly budget without CMO approval
- Events/field commitments (signed contracts) are excluded from real-time reallocation calculations
- Annual contracts (agency retainers, platform subscriptions) are modeled as fixed costs; only discretionary spend within each channel is subject to reallocation

2.3 — Human Approval Gate: Decisions Requiring VP/CMO Sign-Off
The following never execute automatically:
- Budget increases >25% above prior month for any channel
- New channel test allocation >$10,000
- Complete channel elimination (budget to zero)
- Reallocation decisions during board meeting weeks (blackout period: 3 days before, 2 days after board)
- Any decision affecting more than 30% of total monthly budget

---

SECTION 3: AUTONOMOUS WORKFLOW ARCHITECTURE

3.1 — Daily Agent Execution Schedule

6:00 AM — Data Ingestion
- Pull previous day spend from Google Ads API, LinkedIn Ads API, and any connected ad platforms
- Pull CRM data: leads created, MQLs created, SQOs created, opportunities updated — attributed to yesterday's channel touchpoints
- Pull outbound SDR tool data: sequences sent, replies received, meetings booked
- Refresh composite channel scores

7:00 AM — Threshold Check
- Run all Rule Type A, B, C checks against updated scores
- Queue any triggered actions for execution window

8:00 AM — Execution Window
- Execute pre-approved budget adjustments in platform APIs (Google Ads budget updates, LinkedIn campaign budget updates)
- Log all actions to audit table with timestamp, rationale, spend delta, and projected impact
- Send Slack notifications for any actions taken or queued for human review

Every Monday 7:00 AM — Weekly Autonomous Report (see Section 4)

15th of Month — Mid-Month Pipeline Assessment
- Run pipeline emergency protocol check (Rule Type D)
- Send CMO dashboard update with month-to-date vs. target tracking

---

SECTION 4: AUTONOMOUS WEEKLY REPORT DESIGN

Auto-generated every Monday at 7:00 AM, sent to CMO, VP Demand Gen, and RevOps lead:

**MARKETING SPEND INTELLIGENCE BRIEF — Week of [Date]**

EXECUTIVE SUMMARY (3 sentences max):
[Pipeline tracking status vs. monthly goal] | [Total spend efficiency vs. prior week — CPP delta] | [Top reallocation action taken and projected impact]

CHANNEL PERFORMANCE TABLE:
| Channel | Spend (WoW) | Leads | MQLs | SQOs | Pipeline Sourced | CPP | Score | Status |
[Populate with actuals + trends]

REALLOCATIONS EXECUTED THIS WEEK:
- [Channel] budget [increased/decreased] by [$X] on [Date]: Reason: [Trigger fired]. Projected impact: [+/- $Y pipeline over next 30 days]

EARLY WARNING FLAGS (Not Yet Triggering Auto-Reallocation):
- [Channel]: [Signal description] — monitoring for [X] more days before threshold breach

REQUIRES HUMAN DECISION (respond by Wednesday):
1. [Decision item] — Recommended action: [X] — Impact if not acted on: [Y]

---

SECTION 5: IMPLEMENTATION ROADMAP

Week 1-2: Foundation
- Audit CRM attribution tagging: ensure every lead has UTM source + channel, and every SQO is linked to a marketing-sourced channel
- Build channel performance dashboard in [BI tool] pulling from CRM + ad platform data
- Define historical baseline CPP and composite scores for each channel using trailing 90 days

Week 3-4: Rules Configuration
- Document all reallocation rules in a decision matrix
- Set up Zapier/Make/n8n workflows connecting ad platform APIs to CRM for automated budget updates
- Create Slack notification templates and connect to workflow triggers
- Build audit log table (Airtable, Notion, Google Sheets, or CRM custom object)

Week 5-6: Dry Run
- Run the system in "recommendation mode" for 2 weeks: AI agent generates reallocation recommendations but does not execute automatically
- Human team validates recommendations vs. their intuition
- Calibrate thresholds based on dry run findings

Week 7+: Autonomous Execution
- Flip Rules A, B, C to automatic execution
- Maintain monthly human review of threshold calibration
- Track system-generated CPP vs. prior 90-day baseline to measure optimization lift

---

OUTPUT REQUIREMENTS:
Format as an implementation blueprint. Include:
1. The complete data monitoring architecture for this company's specific tech stack
2. The calibrated reallocation rules with exact thresholds filled in based on the provided benchmarks
3. The budget floor/ceiling guardrails with specific dollar amounts
4. The weekly report template in table format ready to deploy
5. The 6-week implementation roadmap with specific tasks, tool configurations, and success criteria
6. A "human judgment" decision framework: a decision tree showing when the AI agent acts vs. when it escalates to a human, with the rationale for each branch

Tone: Operational and precise. Use tables, thresholds with specific numbers, and decision trees. This is a working specification document, not a strategy deck.

## Example Input/Output

**Input Example:**

Company: Lattice — B2B SaaS people management platform (OKRs, performance reviews, compensation)
Monthly budget: $310,000
Channel mix: Google Ads $75K, LinkedIn Ads $95K, Meta Ads $22K, Outbound SDR $48K, Events $42K, Content/SEO tools $18K, Direct mail ABM $10K
Pipeline target: $4.1M/quarter marketing-sourced
CRM: Salesforce + Marketo + Bizible attribution
ICP: VP People, CHRO at B2B companies 500-5,000 employees

**Output Example (excerpt):**

**Channel Composite Score — Current State:**

| Channel | CPP ($/pipeline $) | Pipeline Score | Lead Quality Score | Velocity Score | Trend Score | Composite Score | Status |
|---|---|---|---|---|---|---|---|
| Google Ads | $0.048 | 88 | 79 | 82 | 72 | **84** | Scale |
| LinkedIn Ads | $0.071 | 72 | 68 | 74 | 61 | **70** | Maintain |
| Meta Ads | $0.142 | 38 | 31 | 44 | 28 | **35** | Reduce |
| Outbound SDR | $0.055 | 82 | 85 | 61 | 78 | **78** | Maintain |
| Events | $0.089 | 58 | 74 | 48 | 52 | **58** | Watch |
| Content/SEO | $0.034 | 92 | 88 | 58 | 81 | **88** | Scale |

**Automated Actions Queued:**
- Meta Ads: Composite score 35 (sustained 6 days) → Auto-reduce by 15% ($3,300/month). Funds redirect to Google Ads (+$1,800) and Content/SEO promotion (+$1,500).
- Google Ads: Score 84, eligible for Scale. +$9,000/month funded from Meta reduction + events optimization reserve.
- Events: Score 58 (Watch). No automatic action. Flag for human review: Q3 events calendar has 3 upcoming commitments totaling $38K; human to assess pre-payment risk vs. pipeline likelihood.

**Projected 30-Day Pipeline Impact of Queued Actions:** +$47,000 incremental pipeline at blended historical CPP of $0.071 for reallocated spend.

## Success Metrics

- **Speed of response**: Budget adjustments execute within 24 hours of threshold breach, vs. industry norm of 7-21 days
- **CPP improvement**: Blended cost per pipeline dollar decreases 12-25% within 90 days vs. pre-system baseline
- **Time savings**: Marketing leadership spends <2 hours/week on budget decisions, down from 6-10 hours
- **Pipeline gap rate**: Months where marketing-sourced pipeline misses target by >15% decrease from current frequency
- **Audit completeness**: 100% of reallocation decisions logged with rationale, spend delta, and projected impact within 1 hour of execution
- **Human escalation accuracy**: >80% of human-escalated decisions result in action (vs. no-action), confirming the escalation threshold is calibrated correctly

## Related Prompts

- [`../../Demand-Generation-Operations/AI-Powered-B2B-SaaS-Demand-Generation-Waterfall-Architecture-&-Marketing-Funnel-Conversion-Intelligence-Engine.md`](../../Demand-Generation-Operations/AI-Powered-B2B-SaaS-Demand-Generation-Waterfall-Architecture-&-Marketing-Funnel-Conversion-Intelligence-Engine.md) — Build and audit the funnel that this budget system optimizes against
- [`../../Demand-Generation-Operations/AI-Powered-B2B-SaaS-Lead-Scoring-Architecture-&-MQL-Pipeline-Qualification-Intelligence-Engine.md`](../../Demand-Generation-Operations/AI-Powered-B2B-SaaS-Lead-Scoring-Architecture-&-MQL-Pipeline-Qualification-Intelligence-Engine.md) — Design the MQL scoring system that feeds channel quality scores
- [`../../../05_Analytics-&-Marketing-Operations/KPI-Dashboard-Creation/AI-Powered-B2B-SaaS-Marketing-Budget-Pacing-&-Real-Time-Spend-Velocity-Intelligence-Engine.md`](../../../05_Analytics-&-Marketing-Operations/KPI-Dashboard-Creation/AI-Powered-B2B-SaaS-Marketing-Budget-Pacing-&-Real-Time-Spend-Velocity-Intelligence-Engine.md) — Real-time spend pacing dashboard that feeds the reallocation engine's data layer
- [`../../Demand-Generation-Operations/AI-Powered-B2B-SaaS-Intent-Data-Vendor-Evaluation-&-Buyer-Signal-Stack-Architecture-Revenue-Intelligence-Engine.md`](../../Demand-Generation-Operations/AI-Powered-B2B-SaaS-Intent-Data-Vendor-Evaluation-&-Buyer-Signal-Stack-Architecture-Revenue-Intelligence-Engine.md) — Choose the intent data sources that feed buyer signal scoring into this system

## Integration Tips

- **Salesforce + Google Ads**: Use Salesforce's Google Ads connector to import conversions directly into Google Ads — enables the reallocation engine to use actual SQO/pipeline data as Google Ads conversion goals, not just form fills
- **HubSpot + LinkedIn**: LinkedIn's CRM sync pushes lead data directly to HubSpot contact records with source attribution; configure custom properties for "channel composite score" that update daily via HubSpot Workflow triggered by data import
- **Zapier/Make automation**: Build a Zap/scenario that reads a Google Sheet or Airtable "reallocation decision log" updated by your BI tool, and calls Google Ads API or LinkedIn Ads API to update campaign budgets when status changes to "Execute"
- **Slack integration**: Use Incoming Webhooks to post weekly autonomous reports and real-time threshold breach alerts to a dedicated #marketing-budget-ops Slack channel; pin the weekly report for async team review
- **Google Looker Studio**: Build the channel performance dashboard connecting Google Ads and LinkedIn Ads data with Salesforce pipeline data via a Supermetrics or Funnel.io connector; set up scheduled email delivery of the report to marketing leadership every Monday at 7am

## Troubleshooting

**Problem:** The system reallocates budget based on CPP, but one channel has a 60-day attribution lag, making its CPP look artificially poor when spend is high.
**Solution:** Implement a lag-corrected CPP calculation: for channels with long attribution windows (events, content), use a 90-day trailing average rather than the current month's raw numbers. Add a "Lag Adjustment Factor" column to the channel scoring model that discounts current-month pipeline by the historical ratio of 30-day vs. 90-day attributed pipeline for that channel type.

**Problem:** The AI agent reduces LinkedIn Ads budget because CPP looks poor, but LinkedIn drives dark social and brand awareness that shows up as "direct" in CRM attribution — the system is penalizing an effective channel due to attribution gaps.
**Solution:** Add a "self-reported attribution supplement" to the channel scoring model. Run a quarterly survey asking closed-won customers "Which channels influenced your awareness of us before you filled out a form?" Weight LinkedIn's quality score using the blended attribution correction factor derived from that survey data. Set a floor rule: LinkedIn never drops below 25% of paid media budget without human override, protecting dark-funnel channels from algorithmic under-attribution.

**Problem:** The autonomous system executes a reallocation that creates a conflict with a paid media agency's contracted minimum spend commitments.
**Solution:** Before building the reallocation system, audit all vendor contracts and input floor commitments as hard constraints in the rules engine. Create a "contracted spend" layer that sits above the reallocation logic — the system can only reallocate discretionary spend above contractual minimums. Store contract end dates and flag renegotiation opportunities 60 days before renewal when historical performance suggests the contract should be restructured.

## Version History

- v1.0: Initial creation (auto-generated)
