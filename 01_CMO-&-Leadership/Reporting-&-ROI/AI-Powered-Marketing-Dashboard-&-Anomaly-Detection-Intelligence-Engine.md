# AI-Powered Marketing Dashboard & Anomaly Detection Intelligence Engine - Build a Self-Updating Performance Command Center That Alerts You Before Problems Become Disasters

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** marketing-analytics, reporting, dashboards, anomaly-detection, kpi-alerting, b2b, saas, marketing-operations, data-viz, automated-insights

## Overview
Designs a unified marketing performance dashboard architecture, configures AI-powered anomaly detection rules across all channels and funnel stages, and generates an automated weekly insights narrative engine — so your team spots revenue-threatening performance drops in hours, not weeks. Use this when you're managing 5+ marketing channels and can't see the full picture in one place, when performance reviews happen monthly instead of daily, or when you've been blindsided by a budget problem that was quietly building for weeks.

## Quick Copy-Paste Version

You are a senior marketing analytics architect with 15+ years of experience building performance dashboards for B2B SaaS CMOs. Design a unified marketing dashboard system with AI-powered anomaly detection and automated insights narratives for my marketing team.

My current reporting situation:
- Marketing channels active: [list channels — Google Ads, LinkedIn, email, SEO, events, etc.]
- Data sources/tools: [CRM, MAP, paid platforms, analytics, BI tools you use]
- Current reporting cadence: [daily / weekly / monthly]
- How reports are built today: [manual pulls / automated / mixed]
- Team size receiving reports: [executive team / marketing team / board — specify]
- Biggest reporting gaps: [describe top 3 problems — e.g., "by the time I see a CPL spike, we've wasted $50K"]

Deliver:
1. Dashboard Architecture Blueprint: What metrics go on which dashboard (CMO-level, channel-level, funnel-level), organized by decision-making audience
2. Anomaly Detection Rule Set: For each channel and funnel stage, define the alert thresholds that should trigger immediate investigation — not every blip, only signals that threaten pipeline or budget
3. Automated Weekly Insights Template: A 5-section narrative framework that AI can populate every Monday from the data — no human writing required
4. Alert Routing Map: Who gets alerted about what, via which channel (Slack, email, SMS), at what severity level
5. Top 5 dashboard KPIs by channel with baseline benchmarks
6. Tool configuration instructions for building this in [specify your BI tool or we'll recommend one]

Be specific with metric definitions, alert thresholds using percentage deviations from rolling 4-week averages, and Slack/email notification copy examples.

## Advanced Customizable Version

ROLE: You are a VP of Marketing Analytics and Revenue Intelligence with 17 years of experience. You've built marketing performance systems for companies ranging from Series A startups to Fortune 500 enterprises. You specialize in designing dashboards that drive decisions (not just display data), anomaly detection systems that surface revenue-threatening signals in real time, and automated narrative engines that eliminate 80% of manual reporting work. You've worked extensively with Looker, Tableau, Salesforce Reports, Google Looker Studio, Metabase, HubSpot, GA4, and custom data warehouse solutions on Snowflake and BigQuery.

COMPANY CONTEXT:
- Company: [Company Name]
- Industry: [B2B SaaS / B2C / D2C / Marketplace / Other]
- Stage: [Series A / Series B / Series C / Enterprise / Public]
- ARR: [$X] | MRR: [$X] | Growth rate: [X% YoY]
- ACV: [$X] | Sales cycle median: [X days]
- Monthly marketing spend: [$X total] | By channel breakdown: [allocate %]
- Monthly MQL target: [X] | Current MQL volume: [X]
- Pipeline coverage target: [Xх revenue target]

MARKETING TECH STACK — DATA SOURCES:
| Data Source | Tool | Metrics Available | API/Integration | Update Frequency | Data Quality 1-10 |
|------------|------|-------------------|-----------------|-----------------|------------------|
| CRM | [Salesforce/HubSpot/etc.] | [leads, opportunities, pipeline, closed-won] | [native/Zapier/manual] | [real-time/daily] | [score] |
| Marketing Automation | [Marketo/HubSpot/Pardot] | [emails sent, opens, clicks, MQLs] | [status] | [daily] | [score] |
| Paid — Search | [Google Ads/Microsoft Ads] | [impressions, clicks, CPL, conversions] | [status] | [hourly] | [score] |
| Paid — Social | [LinkedIn/Meta/etc.] | [spend, CTR, CPM, leads, CPL] | [status] | [daily] | [score] |
| Web Analytics | [GA4/Amplitude/Mixpanel] | [sessions, engagement, conversions] | [status] | [real-time] | [score] |
| SEO | [Semrush/Ahrefs/GSC] | [rankings, clicks, organic MQLs] | [status] | [weekly] | [score] |
| Intent Data | [6sense/Bombora/G2] | [account intent surges, buying stage] | [status] | [daily] | [score] |
| BI / Data Warehouse | [Looker/Tableau/Metabase/Snowflake] | [unified view] | [status] | [daily] | [score] |
[Add additional data sources as needed]

REPORTING AUDIENCE & CADENCE:
- CMO / VP Marketing: [daily digest / weekly review / monthly — what decisions do they make daily?]
- Channel managers: [what metrics do they need to act autonomously vs. escalate?]
- Executive team / CEO: [what they ask for in weekly staff meeting]
- Board / investors: [what they want in monthly/quarterly packages]
- Sales leadership: [what marketing data they track to hold marketing accountable]

CURRENT REPORTING PROBLEMS (rate each 1-5 for severity, 5=worst):
- Visibility lag (time from metric change to awareness): [describe current state + severity]
- Data fragmentation (metrics live in 5+ disconnected tools): [describe + severity]
- Manual report construction (hours per week spent pulling and formatting): [X hours/week + severity]
- Inconsistent metric definitions (CPL means different things to different people): [examples + severity]
- Alert fatigue or absence (too many meaningless alerts, or no alerts at all): [describe + severity]
- Attribution confusion (can't connect paid spend to pipeline): [describe + severity]
- Benchmark blindness (reporting actuals without context about whether they're good): [describe + severity]

KEY PERFORMANCE QUESTIONS (the decisions this dashboard must answer):
1. [e.g., "Is our Google Ads CPL trending toward our $180 target, or should we reallocate budget to LinkedIn?"]
2. [e.g., "Are we on track to hit 240 MQLs this month, and which channel is over/under-contributing?"]
3. [e.g., "Did last week's email campaign contribute to pipeline, and how much?"]
4. [e.g., "Is our website conversion rate declining, and if so, which pages are dragging it down?"]
5. [e.g., "What is the current pipeline coverage ratio, and is it improving week-over-week?"]
[Add up to 8 key performance questions]

ANOMALY DETECTION PREFERENCES:
- False positive tolerance: [Low — only alert on statistically significant deviations / Medium / High — alert me often even if it might be noise]
- Alert channels: [Slack / Email / SMS / Dashboard notification — specify which people get which]
- Weekend/off-hours alerts: [Yes for critical only / Yes for all / No]
- Historical baseline preference: [rolling 4-week average / same period last year / vs. target / vs. peer benchmark]

ANALYSIS REQUESTED:

**Section 1: Dashboard Architecture Blueprint**

Design a three-tier dashboard hierarchy with no more than 12 metrics per dashboard view:

*Tier 1 — CMO Command Center (Daily, 90-second review)*
- Purpose: Single-screen view of whether marketing is on track to hit pipeline and MQL targets this month
- Must answer in ≤90 seconds: [list the 3-4 decisions a CMO makes from this view daily]
- Metrics to include (max 12):

| Metric | Definition | Data Source | Display Format | Alert Threshold |
|--------|-----------|-------------|----------------|----------------|
| MQL Pace (month-to-date) | MQLs created MTD vs. linear pace to hit monthly target | CRM | Progress bar + % to target | Alert if pace drops below 85% of linear target by day 10 |
| Pipeline Created (MTD) | Gross new pipeline created this month | CRM | $X vs. $X target | Alert if <80% of target pace |
| Cost Per MQL (rolling 7-day) | Total ad spend ÷ MQLs sourced (paid channels) | Ads + CRM | $X current vs. $X 4-week avg | Alert if >20% above 4-week average |
| MQL → SQL Rate (rolling 30-day) | SQLs created ÷ MQLs created in same period | CRM | % trend line | Alert if drops >5pp vs. 4-week average |
| Paid Media Efficiency (ROAS / pipeline per $1 spent) | Pipeline attributed to paid ÷ paid spend | CRM + Ads | $X pipeline per $1 spend | Alert if drops >15% week-over-week |
| Website Conversion Rate (rolling 7-day) | Demo requests + form fills ÷ total sessions | GA4 + CRM | % vs. 4-week baseline | Alert if drops >10% vs. rolling baseline |
| Email Engagement (last send) | Open rate + click-to-open rate for most recent campaign | MAP | % vs. list benchmark | Alert if open rate <80% of list average |
| Pipeline Coverage Ratio | Total open pipeline ÷ (monthly revenue target × 3) | CRM | Xх — color coded green/yellow/red | Alert if drops below 2.5x |
[Additional metrics based on company context]

*Tier 2 — Channel Performance Hub (Weekly, channel managers)*
Design a separate view for each active channel: Paid Search, Paid Social, Organic/SEO, Email/Nurture, Events, Outbound. For each channel view include:
- Top 5 metrics specific to that channel
- Week-over-week trend (current week vs. last 4-week avg)
- Budget pacing (spend MTD vs. allocation)
- Channel-specific anomaly alerts
- Link to raw data for drill-down

*Tier 3 — Funnel Conversion Waterfall (Monthly, leadership team)*
Build a visual funnel showing:
VISITORS → LEADS → MQLS → SQLS → OPPORTUNITIES → PIPELINE → CLOSED-WON
For each stage transition:
- Conversion rate (current month vs. last quarter avg vs. industry benchmark)
- Volume at each stage
- Biggest drop-off point with root cause hypothesis
- Revenue impact of improving each conversion rate by 1 percentage point

**Section 2: Anomaly Detection Rule Engine**

For each metric in the system, define precisely when an alert fires. Use this format for each rule:

ANOMALY RULE: [Rule Name]
METRIC: [Exact metric being monitored]
BASELINE: [How baseline is calculated — rolling 4-week average / same weekday last 4 weeks / monthly target]
ALERT TRIGGER: [Precise threshold — e.g., "metric is >25% below baseline for 2 consecutive days"]
SEVERITY LEVEL: [P1-Critical / P2-High / P3-Medium — defines notification speed]
NOTIFICATION: [Who gets alerted, via which channel, with what message]
EXAMPLE ALERT TEXT: [Write the actual Slack/email message — specific numbers, links, and suggested action]
SUPPRESS IF: [Conditions that should suppress the alert — e.g., "MQL drop alert suppresses if it's within 3 days of a holiday or planned campaign pause"]

Mandatory anomaly rules to design:
1. MQL Volume Cliff — daily MQL pace drops >30% below target pace before day 15 of month
2. CPL Spike — rolling 7-day CPL rises >25% above 4-week average on any paid channel
3. Website Conversion Drop — conversion rate on demo/contact page drops >15% for 3 consecutive days
4. Email Deliverability Warning — bounce rate exceeds 2% or spam rate exceeds 0.08% on any send
5. Pipeline Coverage Alert — pipeline coverage drops below 2.5x monthly revenue target
6. CAC Trending Over — blended CAC rising >20% quarter-to-date vs. same period last quarter
7. SQL Qualification Rate Drop — MQL → SQL rate drops >8pp vs. 30-day rolling average (signals ICP drift or sales disengagement)
8. Paid Budget Pacing Overage — any channel's spend on track to exceed monthly budget by >10%
9. SEO Traffic Cliff — organic sessions drop >20% week-over-week (could signal Google algorithm update or technical SEO issue)
10. Account Intent Surge Missed — intent platform identifies ≥5 target accounts moving to "Decision" stage not yet in active sales cycle

[Add channel-specific rules based on company's active channels]

**Section 3: Automated Weekly Insights Narrative Engine**

Design a prompt template that an AI agent runs every Monday at 7:00 AM, pulling the prior week's data and producing a 5-section performance narrative. This narrative should require zero human editing before distribution to the leadership team.

Define the narrative structure and the data inputs each section requires:

*Section 1: Performance Snapshot (3 sentences max)*
Data inputs: [MTD MQL pace, pipeline created, paid spend, website sessions]
Output format: "Marketing is [on track / 12% behind / 8% ahead] to hit [X] MQLs this month. Last week, we generated [X] MQLs ([+/-X%] vs. 4-week avg) and created [$X] in new pipeline. [One sentence on the most notable positive or negative signal from the week.]"

*Section 2: Channel Winners & Losers (ranked list)*
Data inputs: [weekly MQL volume, CPL, conversion rate by channel]
Output format: "TOP PERFORMER: [Channel] generated [X] MQLs at $[CPL], [X%] below our 4-week avg CPL. UNDERPERFORMER: [Channel] CPL reached $[X], [X%] above benchmark — recommended action: [specific action]. [One sentence on the 'why' if data supports a hypothesis.]"

*Section 3: Funnel Health Check (traffic light summary)*
Data inputs: [conversion rates at each funnel stage vs. 4-week baseline]
Output format: Color-coded table — GREEN (within 5% of baseline) / YELLOW (5-15% variance) / RED (>15% variance below baseline). One sentence of context for each RED metric.

*Section 4: Alerts & Exceptions (items requiring action this week)*
Data inputs: [all P1 and P2 anomalies fired in prior 7 days]
Output format: Bulleted list: "⚠️ [Alert name]: [What happened, magnitude of deviation, estimated impact if unaddressed, recommended next step with owner]. Deadline: [by when]."

*Section 5: Forward-Looking Signal (1-2 insights about next 2 weeks)*
Data inputs: [pipeline coverage, scheduled campaigns, intent data surges, seasonal patterns]
Output format: "Pipeline coverage is currently [Xх] against [X-week forward target]. Based on [signal], we [should / may need to] [specific action] before [date]. [One notable opportunity or risk on the horizon.]"

Provide the complete AI prompt that generates this narrative each week, with exact data placeholders and formatting instructions.

**Section 4: Alert Routing & Escalation Matrix**

Define who gets notified about what, at what speed, via which channel:

| Alert Type | Severity | Primary Recipient | Notification Channel | Response SLA | Escalation Path |
|-----------|---------|-------------------|---------------------|-------------|----------------|
| MQL Cliff (>30% below pace) | P1 | CMO + Demand Gen Lead | Slack DM + Email | Acknowledge in 2 hours | No response in 2 hrs → auto-escalate to CMO |
| CPL Spike (>25% on paid channel) | P1 | Paid Media Manager + CMO | Slack channel #mktg-alerts | Triage plan in 4 hours | |
| Pipeline Coverage Below 2.5x | P1 | CMO + VP Sales | Email + Slack | Same-day response | |
| Email Deliverability Warning | P2 | Email Marketing Manager | Slack DM | Pause next send within 1 hour | |
| Budget Pacing Overage | P2 | CMO + Finance | Email | Response within 24 hours | |
| SQL Rate Drop | P2 | Demand Gen Lead + VP Sales | Slack | Weekly review meeting agenda | |
| Website Conversion Drop | P2 | Demand Gen + Web/UX | Slack | 48-hour diagnosis | |
| SEO Traffic Cliff | P3 | Content/SEO Lead | Slack channel | Weekly meeting agenda | |
[Add rows for all anomaly rules defined in Section 2]

**Section 5: Dashboard Build Instructions**

For the specific BI tools in our stack, provide step-by-step configuration:

*Data Connection Priority:*
1. Which connections to build first (ranked by data quality and decision-making value)
2. Recommended data refresh frequency per source
3. Transformations required before data is dashboard-ready (e.g., "Salesforce Opportunity Stage must be mapped to custom funnel stages")

*Metric Calculations:*
For each metric in the CMO Command Center, provide the exact SQL query or formula to calculate it:
- MQL Pace: [formula]
- Pipeline Coverage Ratio: [formula]
- Cost Per MQL (blended): [formula]
- MQL → SQL Conversion Rate (rolling 30-day): [formula]
[Continue for all Tier 1 metrics]

*Anomaly Detection Implementation:*
Choose between:
Option A: Native BI Tool Alerts (Looker, Tableau) — configure threshold-based alerts in the BI tool
Option B: Zapier/Make Automation — daily data pull → compare to baseline → trigger Slack/email if threshold breached
Option C: Custom Python script — run via cron job, more flexible for complex rules
Recommend Option [A/B/C] for [company's stack] and provide configuration instructions.

**Section 6: 30-Day Dashboard Launch Roadmap**

Structure as four weekly milestones:

*Week 1: Data Foundation*
- Connect [Priority Data Sources 1-3] to BI tool / data warehouse
- Define and document metric definitions (single source of truth glossary)
- Build CMO Command Center Tier 1 dashboard (12 metrics)
- Configure 3 most critical P1 anomaly alerts (MQL Cliff, Pipeline Coverage, CPL Spike)
- Success gate: CMO reviews dashboard and confirms it replaces one existing manual report

*Week 2: Channel Dashboards*
- Build Tier 2 channel-specific views for [top 3 channels by spend]
- Connect remaining data sources
- Configure all P2 alerts
- Test anomaly triggers with historical data
- Success gate: Channel managers confirm dashboards are replacing their manual channel reports

*Week 3: Funnel Waterfall & Insights Engine*
- Build Tier 3 funnel conversion waterfall
- Build and test the automated weekly insights narrative (run a test on last week's data)
- Configure full alert routing matrix
- Success gate: First auto-generated weekly insights narrative sent to leadership with zero human edits

*Week 4: Hardening & Adoption*
- Tune alert thresholds based on first 2 weeks of real data (eliminate false positives)
- Train channel managers on dashboard usage and alert response protocols
- Document all metric definitions, alert rules, and escalation paths in Notion/Confluence
- Success gate: Zero manual reports being produced; all reports replaced by automated dashboards

## Example Input/Output

**Input context:**
- Company: Luminary Analytics (B2B SaaS, Series B, $22M ARR, 165% NRR)
- Marketing team: 9 people, 1 dedicated analytics/ops
- Stack: Salesforce + Marketo + Google Ads + LinkedIn Ads + GA4 + Looker Studio + Slack
- Monthly spend: $120K across paid search ($65K), LinkedIn ($35K), events ($20K)
- MQL target: 180/month | Current: 142 last month
- Biggest problem: "CPL on LinkedIn doubled in 6 weeks and nobody noticed until the CFO asked why pipeline was thin"

**Output excerpt:**

**CMO Command Center — Tier 1 Dashboard:**

| Metric | This Week | 4-Week Avg | Status | Alert? |
|--------|-----------|-----------|--------|--------|
| MQL Pace (MTD) | 67 MQLs / Day 14 → 144/mo pace | 180 target | 🔴 80% of target | ⚠️ P1 Alert: Pace 20% below target |
| Paid Pipeline Created MTD | $892K | $1.1M target pace | 🟡 81% of pace | Watch closely |
| Blended CPL (rolling 7-day) | $387 | $294 (4-week avg) | 🔴 32% above baseline | ⚠️ P1 Alert: CPL spike |
| MQL → SQL Rate (30-day) | 19.2% | 23.8% | 🔴 Down 4.6pp | ⚠️ P2 Alert |
| Website Conversion Rate | 2.4% | 2.7% | 🟡 Down 11% | Monitoring |
| Pipeline Coverage Ratio | 2.7x | 3.1x target | 🟡 Below 3x target | Monitoring |

**Anomaly Detection Rule — CPL Spike:**
ANOMALY RULE: Paid Channel CPL Spike
METRIC: Rolling 7-day Cost Per MQL by channel (Google Ads, LinkedIn Ads)
BASELINE: Rolling 4-week average CPL per channel
ALERT TRIGGER: CPL exceeds baseline by >20% for 3 consecutive days, OR by >35% on any single day
SEVERITY: P1-Critical (this is the exact scenario that burned Luminary for 6 weeks)
NOTIFICATION: Paid Media Manager (Slack DM, immediate) + CMO (Slack DM, immediate)
EXAMPLE ALERT TEXT: "🚨 CPL SPIKE ALERT — LinkedIn Ads | LinkedIn CPL hit $618 today (+44% above 4-week avg of $429). You've spent $8,400 this week for 13 MQLs vs. expected 20. Projected monthly impact: -28 MQLs, +$31K in wasted spend if trend continues. Likely causes: audience fatigue, bid strategy change, ad creative stale. Action: Pause top-spending ad sets, review audience frequency, refresh creative. View dashboard: [link]. Escalation: If no response in 2 hours, CMO will be notified."
SUPPRESS IF: Campaign was intentionally paused and reactivated in prior 48 hours (filter for budget anomalies caused by planned campaign scheduling).

**Automated Weekly Insights Narrative (Week of March 17):**

> **MARKETING PERFORMANCE DIGEST — Week of March 17**
>
> **Snapshot:** Marketing is running 20% behind pace for March MQL target (67 MQLs through Day 14; 144/month trajectory vs. 180 target). Last week generated 31 MQLs (−18% vs. 4-week average of 38). The primary drag: LinkedIn CPL doubled while Google Ads maintained efficiency — budget reallocation is the highest-leverage action this week.
>
> **Channel Performance:**
> TOP PERFORMER: Google Ads — 22 MQLs at $214 CPL, 27% below our 4-week average. Branded search + competitor terms are converting at 6.2% vs. site avg of 2.4%.
> UNDERPERFORMER: LinkedIn Ads — 9 MQLs at $618 CPL, 44% above benchmark. Audience frequency reached 8.2x — creative fatigue is the likely cause. Recommended action: Pause bottom 3 ad sets by CPL, refresh creative with new testimonial format tested in January. Budget savings of ~$12K could move to Google retargeting.
>
> **Funnel Health:**
> | Stage | Conversion Rate | vs. Baseline | Status |
> |-------|----------------|-------------|--------|
> | Visitor → Lead | 1.8% | −0.2pp | 🟢 Normal |
> | Lead → MQL | 41% | −3pp | 🟡 Watch |
> | MQL → SQL | 19% | −5pp | 🔴 Investigate |
> | SQL → Opportunity | 68% | +2pp | 🟢 Healthy |
>
> MQL → SQL rate drop from 24% to 19% is the biggest funnel concern. Possible cause: LinkedIn MQLs have lower ICP fit (CPL spike suggests LinkedIn served ads to a broader, less-targeted audience). Recommend: Sales review last 30 LinkedIn-sourced MQLs for ICP alignment.
>
> **Actions Required This Week:**
> ⚠️ LinkedIn Creative Refresh — Pause 3 highest-CPL ad sets by EOD Monday. Brief new creative by Wednesday. Budget shift: $12K from LinkedIn to Google remarketing. Owner: [Paid Media Manager]. Deadline: Monday EOD.
> ⚠️ MQL Pace Recovery Plan — Identify top-of-funnel gap (search volume down? or conversion rate drop?). Pull GA4 demo page performance for last 14 days. Owner: [Demand Gen Lead]. Report back: Wednesday standup.
>
> **Forward Look:** Pipeline coverage sits at 2.7x against March target — within range but 0.4x below our 3x safety threshold. The MQL shortfall from LinkedIn over the past 3 weeks will show up as SQL shortfall in 2-3 weeks based on our 18-day avg MQL-to-SQL cycle. If March closes at 144 MQLs (current pace), we'll enter April with ~$180K less pipeline than targeted. Action: Evaluate event-sourced pipeline from the March 22 webinar as a buffer.

## Success Metrics

The dashboard system is delivering value when, within 30 days of launch:
- **Alert response time** drops from days/weeks to <4 hours for P1 anomalies — verify by measuring time from alert fire to documented response action
- **Manual reporting hours** reduced by ≥70% — track weekly via team time log (baseline vs. 30-day post-launch)
- **Performance surprises in monthly reviews** decrease to zero — leadership team should have seen every major variance in real time before the monthly review
- **CMO daily review time** drops to <5 minutes — dashboard should answer all daily questions without opening additional tools
- **False positive rate** on alerts ≤15% after tuning — if >30% of alerts require no action, thresholds need refinement
- **Data freshness compliance** ≥95% — connected data sources update within their defined refresh windows ≥19 of 20 business days

Quarterly health check: Are the dashboards still being used, or has the team regressed to manual reports? The failure mode of most dashboard projects is initial adoption followed by drift back to spreadsheets — audit usage monthly for the first quarter.

## Related Prompts

- [`./Marketing-Pipeline-Velocity-Weekly-Revenue-Intelligence-Engine.md`](./Marketing-Pipeline-Velocity-Weekly-Revenue-Intelligence-Engine.md) — Pair with this to build the pipeline velocity module within your Tier 1 dashboard
- [`./CMO-Board-Presentation-Builder.md`](./CMO-Board-Presentation-Builder.md) — Use dashboard outputs to auto-populate board presentation slides
- [`../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md) — Build attribution model that feeds into dashboard pipeline metrics
- [`../../05_Analytics-&-Performance/Funnel-Conversion-&-Pipeline-Velocity/Marketing-Funnel-Conversion-&-Pipeline-Velocity-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Funnel-Conversion-&-Pipeline-Velocity/Marketing-Funnel-Conversion-&-Pipeline-Velocity-Intelligence-Engine.md) — Full funnel conversion analysis to set baseline benchmarks for anomaly thresholds

## Integration Tips

**Looker Studio (Google):**
Looker Studio is the fastest no-cost path to the CMO Command Center. Connect directly to Google Ads, GA4, and Google Sheets (for Salesforce data exported via scheduled reports). Use Looker Studio's built-in date comparison controls to show week-over-week and vs. target variances automatically. For anomaly alerting, use the "Scheduled email delivery" feature to send the dashboard as a PDF every Monday at 7 AM — pair this with a Zapier automation that calculates threshold variances and adds a flag row to your Google Sheet data source if any metric is in alert territory. The flag row appears as a visual indicator on the Looker Studio chart.

**Salesforce + HubSpot:**
Build a "Marketing Performance" custom report type in Salesforce that exposes MQL creation date, source, MQL→SQL conversion date, and associated pipeline value in a single object — this becomes the spine of your funnel dashboard. In HubSpot, use the "Custom Report Builder" to create a single report showing contacts by lifecycle stage by week, broken down by original source. Both tools support scheduled report delivery to email; use these for P2 and P3 alert monitoring before investing in dedicated anomaly detection tooling.

**Zapier / Make — Anomaly Alert Automation:**
Build a daily "Metrics Heartbeat" automation that fires at 7 AM every business day. Steps: (1) Pull key metrics from Google Ads API, LinkedIn Ads API, and Salesforce Reports via Zapier data operations. (2) Compare each metric to baseline stored in a Google Sheet (updated weekly with the rolling 4-week average). (3) For each metric where current value deviates from baseline by the threshold percentage, fire a formatted Slack message to the appropriate channel using the alert text templates defined in the anomaly rule engine. Total build time for the first 5 alerts: approximately 6-8 hours in Zapier for a non-developer. This is the most practical starting point for teams without a dedicated BI platform.

**Slack:**
Create a dedicated #mktg-performance-alerts Slack channel with defined channel norms: P1 alerts require acknowledgment within 2 hours (use Slack's reminder feature), P2 alerts go on the weekly standup agenda, P3 alerts are reviewed weekly. Integrate your anomaly alert automation to post directly to this channel with structured message blocks (Slack Block Kit) that include the metric, the deviation, the estimated revenue impact, the likely cause, and a direct link to the relevant dashboard view. Pin a "Alert Response Playbook" in the channel that documents the standard investigation steps for each alert type — so any team member can triage without waiting for the channel manager.

**Python + Snowflake/BigQuery (Advanced):**
For teams with a data warehouse and RevOps/analytics engineer, build the anomaly detection as a Python script running via cron job (or dbt test) that queries all marketing metrics, calculates rolling baselines, compares to current values, and writes alert records to a Slack webhook. This approach enables far more sophisticated anomaly detection: statistical significance testing (z-score >2.5), day-of-week seasonality normalization (so Monday always being lower than Thursday doesn't trigger false alarms), and multi-metric correlation alerts (e.g., "CPL spiked AND conversion rate dropped on the same channel simultaneously" is a more reliable signal than either alone). Pair with Monte Carlo Data or Great Expectations for data pipeline monitoring so your dashboard only shows clean data.

## Troubleshooting

**"The anomaly alerts fire constantly and the team has started ignoring them — classic alert fatigue."**
This is almost always a calibration problem, not a system design problem. The fix: run a 2-week "silent mode" audit. Configure the anomaly rules but route all alerts to a single Google Sheet instead of Slack. After 2 weeks, review which alerts fired most frequently and which ones led to a documented action vs. no action. Delete or raise thresholds for any alert with >70% "no action taken" rate. For the surviving alerts, require a brief 3-line response in the Slack alert thread (What did I find? What did I do? What was the outcome?) — this creates accountability and surfaces whether alerts are actually driving decisions. Target: no more than 2-3 P1/P2 alerts per week in a stable marketing environment. Anything more means your thresholds are too sensitive.

**"Our data quality is so inconsistent that dashboard metrics are unreliable — sales doesn't trust the numbers."**
Build trust by establishing a single "approved" definition for each metric in a publicly accessible glossary (Notion or Confluence works well). For every metric on the CMO Command Center, document: exact definition, data source, calculation method, known limitations, and last validation date. When sales disputes a pipeline number, show them the data source path — this turns philosophical disagreements into specific data quality investigations. Run a weekly data audit of the 5 most disputed metrics and track accuracy over time. Typically, 3-4 specific data entry or integration problems cause 80% of the discrepancies — fixing those root causes (e.g., Salesforce Opportunity Stage not mapped correctly to marketing pipeline stages) resolves most of the trust issues.

**"We built the dashboard but nobody looks at it — people still come to me asking for ad hoc reports."**
The dashboard doesn't replace ad hoc requests until it earns trust by being right more often than manual reports. Spend 2 weeks deliberately using the dashboard to answer ad hoc requests — "that question is answered on this dashboard view, let me show you" repeated enough times builds the habit. More importantly: remove the ability to generate the old manual reports. If the weekly Salesforce report export still lands in the CMO's inbox every Friday alongside the new dashboard, the old report wins every time. Replace all scheduled report deliveries with the new dashboard digest. Use the anomaly alerts to proactively surface insights that people didn't know to ask for — when the dashboard alerts the CMO about the LinkedIn CPL spike before anyone asks, it demonstrates value that no manual report process could match.

## Version History
- v1.0: Initial creation (auto-generated)
