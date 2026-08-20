# AI-Powered B2B SaaS Marketing Operations Real-Time KPI Dashboard & Autonomous Performance Reporting Revenue Intelligence Engine - Build a Zero-Manual-Effort Marketing Intelligence System That Monitors Every KPI, Detects Anomalies, and Generates Board-Ready Reports Automatically

**Difficulty:** Advanced | **Time:** 30-45 min | **Tags:** marketing operations, KPI dashboard, performance reporting, marketing analytics, automation, revenue intelligence, anomaly detection, MarOps, marketing data, BI, Looker, Tableau, HubSpot, Salesforce, demand generation, pipeline metrics, autonomous reporting

## Overview
Designs a complete AI-powered marketing operations KPI dashboard and autonomous reporting system that ingests data from every marketing platform in real time, detects performance anomalies before they become pipeline problems, and generates daily digests, weekly scorecards, and monthly board-ready business reviews without a single hour of manual report-pulling. Use this when your marketing team spends more than 4 hours per week building reports, when leadership asks for metrics you can't answer in under 2 minutes, or when you discover performance problems in QBR prep instead of when they happen.

## Quick Copy-Paste Version

You are a marketing operations architect specializing in AI-powered performance intelligence systems. Design a complete, production-ready real-time KPI dashboard and autonomous reporting system for a B2B SaaS marketing team.

COMPANY CONTEXT:
- Company: [e.g., "Arctus — AI-powered contract intelligence platform for mid-market legal and procurement teams"]
- Annual revenue / growth stage: [e.g., "$28M ARR, Series B, targeting $60M ARR in 18 months"]
- Marketing team size: [e.g., "11 people — 1 Head of Marketing, 2 demand gen, 2 content, 1 PMM, 1 SEO, 1 paid media, 1 ops, 1 ABM, 1 marketing analyst"]
- Current reporting situation: [e.g., "Weekly slides built manually in Google Slides every Friday — 3 hours to compile; CMO asks for pipeline attribution data on Tuesday and it takes 2 days to pull; no anomaly detection, found out Q3 CAC spiked 40% in QBR prep"]
- Primary KPIs leadership cares about: [e.g., "Marketing-sourced pipeline, MQL volume, CAC by channel, MQL-to-SQL conversion rate, content-influenced revenue, paid ROAS"]
- MarTech stack: [e.g., "HubSpot (CRM + MAP), Google Analytics 4, Google Ads, LinkedIn Campaign Manager, Gong (call intelligence), Looker (BI), Google Sheets, Slack, Notion"]
- Biggest reporting pain: [e.g., "Data lives in 6 different platforms; nobody trusts the numbers because every tool reports differently; leadership sees data for the first time in weekly meeting instead of having continuous visibility"]

OUTPUT REQUIRED:
1. KPI TAXONOMY: The complete set of KPIs organized by marketing function (demand gen, paid, content, email, brand, pipeline) — with definitions, owners, target thresholds, and alert triggers for each metric
2. DATA PIPELINE ARCHITECTURE: How to connect every platform into a unified data layer using native integrations, webhooks, or ETL tools — with field mapping specifications and refresh frequency
3. DASHBOARD DESIGN SPECIFICATION: The exact dashboard structure for each audience (CMO view, channel view, campaign view, ops view) with the specific charts, tables, and filters for each
4. ANOMALY DETECTION SYSTEM: The rules, thresholds, and alert logic that fires a Slack notification before a metric becomes a crisis — not after
5. AUTONOMOUS REPORT GENERATION: The templates and automation logic for daily digest emails, weekly scorecards, and monthly CMO business review decks — generated without human input
6. IMPLEMENTATION ROADMAP: A phased 90-day rollout plan with Week 1 quick wins and a path to fully autonomous reporting at steady state

## Advanced Customizable Version

ROLE: You are a senior marketing operations architect with 14+ years of experience building marketing intelligence infrastructure at B2B SaaS companies from Series A through public. You have built autonomous reporting systems at four companies, have deep expertise in marketing data pipelines (Fivetran, dbt, Segment, Rudderstack), BI tools (Looker, Tableau, Metabase, Google Looker Studio), and marketing automation platforms (HubSpot, Marketo, Pardot). You understand that the single biggest threat to a marketing team's credibility is not bad strategy — it is bad data delivered too late. You design reporting systems that CMOs trust enough to present to their board without a pre-flight data check, and that ops teams can maintain with less than 2 hours per week of oversight. You have implemented anomaly detection rules that have caught CAC spikes, landing page conversion collapses, and email deliverability crises weeks before they would have appeared in a quarterly review. You think in data models, not spreadsheets.

OBJECTIVE: Design a complete, production-ready AI-powered marketing KPI dashboard and autonomous reporting system that:
- Ingests real-time or near-real-time data from every marketing platform into a unified semantic data layer with a single definition for every metric
- Presents the right KPIs to the right audience (board, CMO, channel owner, campaign manager) in dedicated dashboard views that answer their specific questions without requiring interpretation
- Detects statistical anomalies and performance deviations automatically, firing actionable Slack/email alerts with context and recommended responses before a human notices the problem
- Generates fully automated daily performance digests, weekly channel scorecards, and monthly CMO business review reports — zero manual compilation, zero formatting work
- Provides a self-service query layer where any marketing team member or stakeholder can ask performance questions in plain English using AI-powered analytics
- Operates with less than 2 hours per week of marketing ops oversight at steady state, with full audit logging and data quality monitoring built in
- Produces board-credible attribution reporting with a defensible methodology that CFOs and investors accept without asking "where does this number come from"

COMPANY PROFILE:
- Company name and one-sentence product description: [name + product targeting enterprise/mid-market buyers]
- Current ARR and growth stage: [ARR | Series A/B/C/growth | growth rate YoY]
- Marketing team headcount and structure: [total headcount | roles | generalist vs. specialist split]
- Revenue targets for next 12 months: [ARR target | pipeline coverage ratio required | marketing's pipeline contribution % goal]
- ICP and primary segments: [primary ICP | 2-3 secondary segments | enterprise vs. mid-market vs. SMB split]
- Current reporting cadence: [weekly / monthly / quarterly | who builds reports | hours spent | tools used]
- Biggest data credibility problems: [e.g., "HubSpot and Salesforce show different MQL counts," "paid media ROAS varies by $0.40 depending on which tool you check," "no single attribution model leadership agrees on"]
- Current BI tooling: [Looker / Tableau / Metabase / Looker Studio / Power BI / none — just Google Sheets]
- Data warehouse: [Snowflake / BigQuery / Redshift / none]
- ETL/integration layer: [Fivetran / Airbyte / Segment / Rudderstack / native integrations only]

MARKETING TECH STACK (map every platform to data type):
- CRM: [Salesforce / HubSpot — what pipeline stages, lead statuses, and attribution fields exist]
- Marketing automation: [Marketo / HubSpot / Pardot / ActiveCampaign — campaign structure, lifecycle stages]
- Paid advertising: [Google Ads / LinkedIn Campaign Manager / Meta Ads / other — ad account structure, conversion tracking setup]
- SEO analytics: [Google Search Console / SEMrush / Ahrefs — keyword rank tracking, organic traffic]
- Web analytics: [GA4 / Segment / Heap / Amplitude — event taxonomy, conversion tracking]
- Content analytics: [HubSpot / Contently / custom — content asset engagement, pipeline influence]
- Email analytics: [Marketo / HubSpot / Customer.io — deliverability, engagement, revenue attribution]
- ABM / intent data: [6sense / Bombora / Demandbase — account engagement scores, intent signals]
- Call intelligence: [Gong / Chorus / Salesloft — conversation data, win/loss signals]
- Events / webinars: [ON24 / Zoom Webinars / Hopin — registration, attendance, pipeline conversion]
- BI / dashboarding: [Looker / Tableau / Metabase / Looker Studio / Power BI]
- Communication: [Slack channels for marketing alerts | email distribution lists for reports]

---

STEP 1 — KPI TAXONOMY ARCHITECTURE:

Define the complete KPI framework organized by marketing function. For each KPI, specify: definition, data source, calculation method, owner, target threshold, warning threshold, and alert trigger.

DEMAND GENERATION KPIs:
- Marketing Qualified Leads (MQLs): [Definition: contacts who reach lead score threshold X in MAP; Data source: HubSpot/Marketo; Refresh: hourly; Owner: Demand Gen Lead; Target: [X MQLs/month based on pipeline coverage model]; Warning: <80% of weekly pacing target by Wednesday; Alert trigger: MQL volume drops >20% week-over-week]
- MQL-to-SQL Conversion Rate: [Definition: SQLs created from MQL source in rolling 30-day window / MQLs in same window; Data source: Salesforce + HubSpot sync; Refresh: daily; Target: [%]; Warning: drops >3pp below 30-day average; Alert: drops >5pp or 2 consecutive weeks below target]
- Marketing-Sourced Pipeline Created: [Definition: sum of ARR of Opportunities with Marketing as primary source in Salesforce; Refresh: daily; Target: [% of total pipeline target]; Warning: weekly pipeline creation pace below [X% of monthly target] by midweek; Alert: month-to-date creation pace at risk of missing monthly target by >15%]
- Marketing-Influenced Pipeline: [Definition: sum of ARR of Opportunities where any marketing campaign touchpoint appears in attribution window; Refresh: daily; Target: [% of total pipeline]; Owner: Marketing Ops]
- Pipeline Coverage Ratio: [Definition: total open pipeline / remaining revenue target for quarter; Refresh: daily; Target: 3.5x minimum at quarter start, declining on a pacing curve; Alert: coverage drops below 2.5x at any point in quarter]
- Cost Per MQL by Channel: [Definition: channel spend / MQLs attributed to channel in rolling 30 days; Refresh: weekly; Target: benchmark by channel [e.g., paid search $X, LinkedIn $Y, content $Z]; Warning: any channel CPM exceeds 130% of 90-day average; Alert: 2 consecutive weeks above warning threshold]

PAID MEDIA KPIs:
- Return on Ad Spend (ROAS): [Definition: pipeline created attributed to paid / total paid spend in same period; Refresh: daily; Owner: Paid Media; Target: [X:1 minimum]; Warning: drops below [0.8x target]; Alert: drops below [0.7x target] or any single campaign shows 0 conversions after $[X] spend]
- Cost Per Click (CPC) by Platform: [Google / LinkedIn / Meta separately; Refresh: daily; Warning: >15% increase week-over-week; Alert: >25% increase WoW — potential auction shift or budget exhaustion]
- Ad Impression Share (Google Search): [Definition: impressions / eligible impressions; Target: >60% for branded, >30% for non-branded priority terms; Alert: branded impression share drops below 50% — potential competitor conquest campaign]
- LinkedIn Lead Gen Form Conversion Rate: [Refresh: daily; Target: [>X%]; Warning: drops >2pp WoW; Alert: drops >4pp — likely audience or offer problem]
- Paid Media Contribution to MQLs: [% of total MQL volume from paid sources; Refresh: weekly; Target: [X%]; Alert: spikes above [Y%] — over-reliance on paid; drops below [Z%] — paid programs failing]

CONTENT & SEO KPIs:
- Organic Traffic (Sessions): [Data source: GA4 + Google Search Console; Refresh: daily; Target: [X sessions/month]; Warning: drops >10% WoW; Alert: drops >20% WoW — possible algorithm impact, technical issue, or crawl error]
- Organic Leads (Form Submissions from Organic): [Refresh: daily; Target: [X/month]; Warning: <75% of monthly pacing by Week 2; Alert: drops >30% MoM]
- Keyword Ranking Velocity: [# of keywords moving into top 10 vs. out of top 10 per week; Data source: SEMrush/Ahrefs; Refresh: weekly; Target: net positive ranking velocity; Alert: any priority keyword drops >5 positions WoW]
- Content-Influenced Pipeline: [Pipeline where a content asset (blog, white paper, webinar recording) appears in the attribution path; Refresh: weekly; Target: [X% of total pipeline]]
- Blog Conversion Rate (Visitor to Lead): [Data source: GA4 goals + HubSpot/Marketo form data; Refresh: weekly; Target: [X%]; Warning: drops >0.5pp MoM; Alert: drops >1pp — CTA or content relevance issue]

EMAIL MARKETING KPIs:
- Email Deliverability Rate: [Delivered / Sent; Refresh: per send; Target: >98%; Warning: drops below 97%; Alert: drops below 95% — domain reputation or list quality issue requiring immediate investigation]
- Email Open Rate (by segment): [Refresh: per send; Benchmark by list type — prospect nurture, customer, re-engagement; Warning: any segment drops >5pp below 90-day average; Alert: drops >8pp — potential deliverability issue, subject line problem, or send time conflict]
- Email Click-to-Open Rate (CTOR): [Definition: unique clicks / unique opens; Target: [X%] by email type; Warning: drops >3pp below 30-day average; Alert: drops >5pp — content or CTA relevance issue]
- Unsubscribe Rate: [Target: <0.2% per send; Alert: any send exceeds 0.5% — list quality or message relevance emergency]
- Email-Sourced MQLs: [# of MQLs where last touch was email; Refresh: daily; Owner: Marketing Ops]

PIPELINE HEALTH KPIs:
- Weighted Pipeline (Probability-Adjusted): [Data source: Salesforce; Refresh: daily; Target: [X coverage]; Alert: drops below minimum coverage threshold at current quarter pacing]
- Average Days in Stage: [By pipeline stage; Refresh: weekly; Target: [X days per stage based on historical]; Warning: any stage average >125% of historical baseline; Alert: >150% — pipeline stall pattern]
- Win Rate (by source, segment, and rep): [Refresh: weekly; Target: [overall X%, paid Y%, organic Z%]; Warning: drops >3pp MoM; Alert: drops >5pp — PMF signal, competitive shift, or ICP drift]
- Closed-Won Revenue Attribution: [Breakdown of closed-won ARR by marketing source; Refresh: weekly; Target: marketing-sourced ≥ [X% of total]]
- Churned Revenue (Marketing Cohort Quality): [Churn rate for customers sourced by specific marketing channels; Refresh: monthly; Alert: any channel shows churn rate >1.5x company average — ICP signal problem]

BRAND & AWARENESS KPIs:
- Share of Voice (Branded Search): [Google Search Console branded impressions / estimated total category search volume; Refresh: weekly]
- G2 / Peer Review Rating & Volume: [G2 rating, # of new reviews per month; Refresh: weekly; Alert: average rating drops below 4.2 or 0 new reviews in any 30-day period]
- Direct Traffic Volume: [GA4 direct sessions as brand awareness proxy; Refresh: weekly; Warning: drops >15% MoM without a clear seasonal explanation]

---

STEP 2 — DATA PIPELINE ARCHITECTURE:

Design the complete data infrastructure that powers the dashboard:

LAYER 1 — SOURCE CONNECTIONS:
For each platform in the MarTech stack, specify:
- Connection method: [Native Fivetran connector / custom API integration / webhook / manual CSV upload as fallback]
- Data refresh frequency: [Real-time webhook / hourly sync / daily batch / weekly]
- Key tables and fields to extract: [List the 5-10 most important data objects and fields per source]
- Known data quality issues to engineer around: [e.g., "HubSpot contact create date vs. Salesforce lead create date mismatch," "LinkedIn conversions attributed to click date vs. impression date," "GA4 session attribution last-click vs. Salesforce first-touch"]

CORE SOURCE MAPPINGS:
- Salesforce → [Opportunities (Id, StageName, Amount, CloseDate, LeadSource, CampaignId, CreatedDate, OwnerId, AccountId), Contacts, Campaigns, CampaignMembers, Lead object]
- HubSpot / Marketo → [Contacts (lifecycle stage, lead score, create date, source, UTM fields), Form Submissions, Emails (send, open, click, unsubscribe), Campaigns, Company associations]
- Google Ads → [Campaigns (impressions, clicks, spend, conversions by date), Ad Groups, Keywords, Conversion Actions]
- LinkedIn Campaign Manager → [Campaign performance (impressions, clicks, spend, leads, conversions), Audience segments, Creative performance]
- GA4 → [Sessions (source/medium/campaign), Events (form_submit, demo_request, pricing_page_view, blog_engagement), User properties, Conversion events]
- Google Search Console → [Query (keyword, position, impressions, clicks), Page (URL, impressions, clicks), Date]

LAYER 2 — DATA WAREHOUSE / TRANSFORMATION:
- Staging layer: [Raw data from each source lands in source-specific schemas: `stg_salesforce`, `stg_hubspot`, `stg_google_ads`, `stg_linkedin`, `stg_ga4`]
- Transformation layer (dbt models): [Define the key dbt models that normalize and join data across sources]
  - `dim_contact`: Unified contact record joining HubSpot/Salesforce with deduplication logic on email
  - `dim_account`: Account entity joining Salesforce Account + HubSpot Company + 6sense intent data
  - `dim_campaign`: Canonical campaign table mapping marketing platform campaigns to internal campaign taxonomy (channel, type, segment, quarter)
  - `fct_pipeline_events`: All Opportunity stage change events with timestamp, previous stage, new stage, ACV, and associated marketing attribution
  - `fct_marketing_touches`: Every marketing touchpoint per contact (email open, ad click, form fill, event attendance) with UTM parameters and timestamp
  - `fct_attribution`: Multi-touch attribution model output assigning pipeline and revenue credit to marketing touches
  - `fct_paid_performance`: Daily paid media performance by platform, campaign, and ad group with spend, clicks, conversions, CPL, and ROAS
  - `mart_weekly_scorecard`: Pre-aggregated weekly rollup of all KPIs for dashboard performance and report generation
  - `mart_anomaly_detection`: Statistical baseline and current period comparison for every monitored KPI

LAYER 3 — SEMANTIC LAYER / METRICS DEFINITION:
Define each metric once in the semantic layer (LookML / dbt Metrics / Cube.dev) so every dashboard and report pulls from the same calculation:
- `marketing_sourced_pipeline`: Sum of `fct_pipeline_events.amount` where `first_touch_channel IN ('paid_search', 'paid_social', 'organic', 'email', 'content', 'event', 'referral')` and `stage_entered = 'Qualified Opportunity'`
- `mql_volume`: Count distinct `dim_contact.contact_id` where `lifecycle_stage = 'MQL'` and `mql_date` in reporting period
- `mql_to_sql_rate`: Count(`stage_entered = 'SQL'` and `source = 'MQL'`) / Count(`mql_volume`) in same 30-day rolling window
- [Define remaining 20-30 KPIs with exact SQL logic so every stakeholder sees the same number regardless of which dashboard or report they pull]

---

STEP 3 — DASHBOARD DESIGN SPECIFICATION:

Design four distinct dashboard views optimized for each stakeholder:

DASHBOARD 1 — CMO EXECUTIVE VIEW (Updated: Daily):
Purpose: Answer "Are we on track this week / month / quarter?" in under 60 seconds.
Layout — Above the fold (no scrolling):
- Pipeline Created MTD vs. target (gauge chart + % to goal + MoM trend arrow)
- MQL Volume MTD vs. target (gauge + MoM trend)
- Marketing-Sourced Pipeline Coverage (current quarter pipeline / remaining target — color coded: green >3x, yellow 2-3x, red <2x)
- CAC Last 30 Days (actual vs. 90-day average — color coded)
- Win Rate Last 90 Days vs. prior 90 days (delta highlighted)
- Active Anomaly Alerts (count of open anomaly alerts — click to drill down)

Layout — Below the fold (detailed trends):
- Weekly pipeline creation trend (12-week bar chart with goal line)
- MQL trend by channel (12-week stacked bar: paid / organic / email / events / referral)
- CAC by channel (table: channel | spend | MQLs | CPL | Opps created | pipeline | CAC)
- Top 5 campaigns by pipeline created (table: campaign name | channel | spend | pipeline | ROAS | stage breakdown)
- Competitive win rate trend (line chart: win rate overall vs. win rate vs. top 3 competitors)

Filters available: Date range (week / month / quarter / trailing 90 days), Segment (enterprise / mid-market / SMB), Channel, Region

DASHBOARD 2 — CHANNEL PERFORMANCE VIEW (Updated: Real-time for paid, daily for organic):
Purpose: Optimize spend allocation and campaign decisions at the channel level.
Tabs: Paid Search | Paid Social | Organic / SEO | Email | Events | Referral / Partner

PAID SEARCH TAB:
- Spend vs. budget (today / MTD / remaining days in period)
- Impressions, clicks, CTR, CPC, conversions, CPL, pipeline ROAS (rolling 7-day and 30-day side by side)
- Campaign-level table with sort/filter by: spend, conversions, CPL, ROAS, quality score
- Search impression share trend (branded vs. non-branded)
- Keyword performance: top 20 keywords by pipeline contribution; top 10 keywords with negative ROI (spend with zero pipeline)
- Anomaly flags: any campaign with spend > $[threshold] and zero conversions; impression share drops > 15pp WoW

PAID SOCIAL (LINKEDIN + META) TAB:
- Platform-level: spend, CPM, CTR, CPL, MQLs, pipeline created (both platforms side by side)
- Campaign-level table for each platform
- Audience performance: top audiences by CPL, bottom audiences by CPL (candidates for exclusion or bid reduction)
- Creative performance: top 5 creatives by CTOR, CPL, pipeline — bottom 5 by same metrics with "pause" recommendation flag
- LinkedIn-specific: Lead Gen Form conversion rate, Thought Leader Ad performance if applicable

ORGANIC / SEO TAB:
- Organic sessions trend (6-month)
- Organic MQLs trend (6-month)
- Top pages by organic traffic and organic conversion rate
- Keyword ranking movements: gained >3 positions (green), lost >3 positions (red), new in top 10 (starred)
- Core Web Vitals status (pass/fail by page type)
- Backlink acquisition trend (new links this month vs. prior month)

EMAIL MARKETING TAB:
- Send volume trend (12-week)
- Open rate, CTOR, unsubscribe rate, deliverability rate (all 12-week trend lines)
- Performance by email type (nurture / announcement / newsletter / re-engagement)
- Deliverability health: sender score, bounce rate, spam complaint rate (color-coded thresholds)
- Top performing emails by CTOR and pipeline influenced; bottom performing emails by open rate (candidates for subject line test)

DASHBOARD 3 — CAMPAIGN PERFORMANCE VIEW (Updated: Daily):
Purpose: Evaluate every running campaign against its goals.
- Active campaign table: campaign name | channel | start date | end date | budget | spend | budget consumed % | MQLs | CPL | Pipeline created | ROAS | status (on-track / at-risk / paused)
- Campaign detail drill-down: click any campaign to see day-by-day trend for spend, MQLs, CPL, pipeline — plus the multi-touch attribution path showing which campaigns appear alongside this one in the buyer journey
- Completed campaigns section: last 90 days, sorted by pipeline ROAS — postmortem-ready with all KPIs summarized

DASHBOARD 4 — MARKETING OPS HEALTH VIEW (Updated: Real-time):
Purpose: Monitor data pipeline health, data quality, and system reliability.
- Data freshness: last successful sync time for each source (green = within SLA, red = overdue)
- Data quality checks: [list of automated checks — e.g., "MQL count in HubSpot matches Salesforce yesterday's sync," "zero form submissions detected — possible tracking break," "CAC calculation inputs validated"]
- Active anomaly alerts log with timestamp, metric affected, current value, baseline value, severity, and assigned owner
- Automation health: list of all scheduled report sends with last successful run timestamp and next scheduled run

---

STEP 4 — ANOMALY DETECTION SYSTEM:

Define the statistical rules and operational thresholds that fire alerts before a human notices:

DETECTION METHODOLOGY:
- Baseline calculation: Rolling 6-week average for each metric (excluding the current week) — avoids recency bias while remaining responsive to trend changes
- Standard deviation thresholds: Warning = current period value > 1.5 standard deviations from 6-week mean; Alert = > 2.5 standard deviations
- Day-of-week normalization: Mondays compared to prior Mondays (not prior Tuesday) — prevents false positives from weekly traffic patterns
- Minimum sample threshold: Anomaly detection only fires when sample size is sufficient (e.g., minimum 100 clicks before CTR anomaly is flagged; minimum $500 spend before ROAS anomaly fires)

ANOMALY RULES BY CATEGORY:

PIPELINE EMERGENCY (Fire within 1 hour — post to #marketing-ops-alerts Slack with @marketing-ops-team mention):
- Marketing-Sourced Pipeline created this week = $0 and it is Wednesday or later
- MQL volume this week is 0 and it is Tuesday or later (possible tracking break — not a performance issue)
- Any campaign with spend > $500 today and zero conversions (paid campaigns only)

PERFORMANCE DEGRADATION (Fire daily digest — post to #marketing-performance Slack with no @ mention):
- MQL volume this week is tracking to end below 70% of weekly target (calculated by daily pacing)
- Week-over-week CAC increase > 25% for any channel with minimum $2,000 spend
- Email deliverability rate drops below 97% on any send
- Landing page conversion rate drops > 2 percentage points vs. 30-day average (minimum 500 sessions)
- Organic traffic drops > 15% week-over-week (day-of-week normalized)
- LinkedIn impression share drops > 20% week-over-week — possible budget exhaustion or audience saturation
- Google branded impression share drops below 55% — possible competitor conquest campaign or budget issue

POSITIVE SIGNALS (Fire weekly summary — include in Friday scorecard):
- Channel achieves ROAS > 1.5x its 30-day average (flag for budget reallocation)
- Any campaign achieves CPL below 60% of channel average (flag as "scale candidate")
- Organic sessions set a 6-month high (brand momentum signal)
- MQL volume 15% above weekly target for 2+ consecutive weeks (pipeline surplus — proactive sales alert)

ALERT FORMAT (Slack message structure for all operational alerts):
🔴 ANOMALY ALERT — [Metric Name]

Current: [value]
Expected baseline: [value]
Deviation: [X%] below/above 6-week average

Context: [1-sentence automated diagnosis — e.g., "MQL volume drop appears isolated to paid search channel. Organic and email MQLs are on track. Possible Google Ads budget exhaustion or bid issue."]

Recommended action: [1-2 specific suggested actions — e.g., "1. Check Google Ads budget pacing. 2. Review Search Impression Share for branded and top non-branded campaigns."]

Dashboard: [direct link to relevant dashboard view]
Owner: @[assigned channel owner]

---

STEP 5 — AUTONOMOUS REPORT GENERATION:

Define the three automated reports generated without human input:

REPORT 1 — DAILY PERFORMANCE DIGEST (Automated send: 7:00 AM recipient's time zone, Monday-Friday):
Recipients: CMO, Head of Demand Gen, Head of Content, Paid Media Lead, Marketing Ops
Format: Email from automated sender (marketing-intelligence@company.com) with subject: "Marketing Daily: [Day, Date] — [Performance Status: On Track / Needs Attention / Alert]"
Content generated automatically:
- Yesterday's KPIs vs. daily target (table: metric | yesterday actual | daily target | % to target | MTD pacing)
- Week-to-date pacing vs. weekly targets (progress bars for top 5 KPIs)
- Active anomaly alerts (any open alerts from last 24 hours with 1-line summary)
- Today's key activities (pulled from campaign calendar: any campaigns launching today, A/B tests concluding, budget reset dates)
- One AI-generated insight (automatically identifies the single most important data pattern from yesterday — e.g., "LinkedIn CPL dropped 18% yesterday after creative refresh. LinkedIn MQLs now pacing 22% above target for the week.")

REPORT 2 — WEEKLY PERFORMANCE SCORECARD (Automated send: Every Monday 8:00 AM):
Recipients: CMO, VP Sales, CFO (read-only), all marketing team leads
Format: Email + attached PDF + Slack post in #marketing-performance channel
Structure:
- Executive summary (3 bullet points auto-generated): Performance vs. target, biggest win, biggest concern
- Scorecard table (all KPIs | this week | last week | WoW change | 4-week average | monthly target | % to monthly target pacing)
- Channel performance rankings (channels ranked by pipeline ROAS this week — top 3 flagged green, bottom 3 flagged with "review" tag)
- Campaign spotlight (top 3 campaigns by pipeline created this week | bottom 3 campaigns by ROAS with "optimize or pause" flag)
- Anomaly summary (any alerts fired last week, their resolution status, and what action was taken)
- Next week's focus (auto-generated based on pacing: if behind on pipeline, flags demand gen acceleration; if behind on MQLs, flags top-of-funnel investment)

REPORT 3 — MONTHLY CMO BUSINESS REVIEW DECK (Automated generation: 1st of each month, delivered by 6:00 AM):
Format: Google Slides deck auto-populated via Slides API / Gamma / Notion AI or equivalent
Slides auto-generated:
- Slide 1: Month in summary (3 metrics: pipeline created vs. target, MQL volume vs. target, CAC vs. prior month)
- Slide 2: Revenue contribution (marketing-sourced pipeline, marketing-influenced pipeline, closed-won revenue from marketing-sourced pipeline — with QoQ trend)
- Slide 3: Channel performance (bar chart: spend by channel | CPL by channel | pipeline ROAS by channel — all channels side by side)
- Slide 4: Funnel efficiency (MQL → SQL → Opportunity → Closed-Won conversion rates vs. prior month and 6-month average)
- Slide 5: Content & organic performance (top 5 content pieces by pipeline influence, organic traffic vs. prior month, SEO ranking highlights)
- Slide 6: Paid media deep-dive (spend, pipeline, ROAS by platform — top 3 campaigns by ROAS, bottom 3 by ROAS — budget allocation recommendation for next month)
- Slide 7: Anomalies and actions taken (any significant anomalies detected last month, actions taken, measurable outcome of each action)
- Slide 8: Next month outlook (pipeline creation target, planned budget allocation by channel, campaigns launching, A/B tests running, key decisions needed from CMO)

---

STEP 6 — AI-POWERED SELF-SERVICE QUERY LAYER:

Enable any marketing team member or stakeholder to ask performance questions in plain English:

IMPLEMENTATION OPTIONS (choose based on existing stack):
- Looker + Looker Explore with LookerML dimensions and measures — enables natural language queries via Looker AI or integrated with Slack via Looker Blocks
- BigQuery + Gemini AI (if on Google Cloud) — natural language to SQL via Gemini integration in Looker Studio
- Snowflake Cortex (if on Snowflake) — native NL-to-SQL via Cortex Analyst
- Metabase + Metabase AI — lower cost option for smaller teams not on enterprise BI tooling
- Custom Slack bot using OpenAI function calling — queries dbt semantic layer via API, returns formatted answers in Slack

EXAMPLE QUERIES THE SYSTEM SHOULD ANSWER IN <30 SECONDS:
- "What is our CAC from LinkedIn ads this quarter compared to last quarter?"
- "Which 3 campaigns generated the most pipeline in June?"
- "What is the MQL-to-SQL conversion rate for leads from the enterprise segment in the last 90 days?"
- "Show me email campaigns with open rate above 30% and CPL below our channel average"
- "Which content pieces are in the buyer journey of deals that closed in Q2?"
- "What is our win rate against [Competitor X] over the last 6 months?"

## Example Input/Output

**Scenario:** Helix Data — an AI-powered revenue analytics platform for mid-market B2B SaaS companies. $22M ARR, Series B, 9-person marketing team. Currently spending 6+ hours every Friday building a "Monday morning deck" in Google Slides. CMO discovered in the Q2 board prep that their Google Ads CPL had spiked 38% in April — two months before anyone noticed. No anomaly detection. Three different MQL numbers depending on whether you looked in HubSpot, Salesforce, or the spreadsheet the analyst maintains.

**Sample Output — Anomaly Alert (what they would have received in April instead of discovering in June):**

---
Slack notification fired Thursday, April 11 at 9:00 AM:

🔴 ANOMALY ALERT — Google Ads Cost Per Lead

Current (this week, Day 4 pacing): $847/lead
Expected baseline (6-week avg): $591/lead
Deviation: +43% above 6-week average

Context: MQL volume from Google Ads is pacing on target (34 MQLs, tracking to 42 for the week). The CPL increase is driven by spend increase without proportional conversion increase. Organic and LinkedIn MQLs are on track at normal CPL. This appears isolated to Google Ads.

Recommended action:
1. Review Google Ads Search Impression Share — has it dropped? (Competitor entering auction or brand bidding on your terms may be inflating CPCs)
2. Check conversion rate by campaign: is the spend increase concentrated in one campaign with declining conversion rate?
3. Review Quality Scores for top spending ad groups — QS decline drives CPC inflation independently of competition

Dashboard: [link to Paid Search tab, Channel Performance View]
Owner: @alex-paid-media

---

**What happened next (simulated response):** Paid media lead reviews dashboard at 9:15 AM. Discovers a competitor began bidding on Helix Data's branded terms on April 9, inflating branded CPC from $2.10 to $6.40. Adds negative brand terms to non-brand campaigns. Increases branded campaign bid cap. CPL normalizes to $624 by the following week. Total wasteful spend avoided: ~$31,000 vs. discovering in June board prep.

---

**Sample Output — Weekly Scorecard (Monday 8:00 AM, auto-generated):**

Subject: 📊 Marketing Weekly: May 13 — ⚠️ Needs Attention

EXECUTIVE SUMMARY (AI-generated):
• Pipeline pacing: 73% of weekly target ($890K created vs. $1.22M target) — demand gen acceleration recommended
• Biggest win: LinkedIn CPL dropped 24% after audience exclusion update; now below channel average for first time in 8 weeks
• Biggest concern: Organic MQL volume down 18% WoW — 3 high-volume blog posts lost page 1 ranking for target keywords (details below)

[Scorecard table with all KPIs — auto-populated with live data]

## Success Metrics

**Data Infrastructure Metrics (Operational Quality):**
- Data freshness SLA: All sources refresh within defined SLA (real-time/hourly/daily) — target >99% SLA compliance per month
- KPI definition consistency: Zero discrepancy between metric values across all dashboards (same number everywhere) — measured by monthly data audit
- Data quality check pass rate: >95% of automated data quality checks pass daily without manual intervention
- Query response time: Self-service queries return results in <30 seconds for 95% of requests

**Adoption Metrics (Organizational Impact):**
- Report open rate: Weekly scorecard email open rate >80% (measures whether stakeholders trust and read automated reports)
- Dashboard daily active users: >60% of marketing team members access a dashboard at least once per week
- Manual report requests eliminated: Track volume of Slack messages asking "can you pull [metric] for me?" — target 90% reduction from baseline within 90 days
- CMO prep time for board meetings: Time spent on data assembly for board deck — target <30 minutes (vs. baseline hours)

**Anomaly Detection Efficacy:**
- Alert accuracy rate: % of fired alerts that represent genuine performance issues (not false positives) — target >85%
- Mean time to detection: Average time between a performance problem occurring and an alert firing — target <24 hours for daily-refresh metrics, <4 hours for real-time metrics
- Mean time to resolution: Average time from alert fire to documented resolution action — target <48 hours for warning alerts, <24 hours for emergency alerts
- Issues caught before human notice: % of performance problems that were detected by the system before any human noticed — target >75% by month 6

**Business Impact Metrics:**
- Wasted spend recovered: Track instances where anomaly detection identified underperforming paid campaigns before scheduled review — estimate spend that would have continued to flow to underperforming campaigns without the alert
- Pipeline creation improvement: Improvement in marketing-sourced pipeline vs. pre-dashboard baseline (better data → better decisions → more pipeline)
- CAC optimization: Reduction in blended CAC from real-time channel optimization enabled by dashboard — target 10-15% improvement in 6 months

## Related Prompts

- [CMO Monthly Marketing Business Review & Revenue Performance Intelligence Engine](../01_CMO-&-Leadership/Reporting-&-ROI/AI-Powered-B2B-CMO-Monthly-Marketing-Business-Review-&-Revenue-Performance-Intelligence-Engine.md)
- [Marketing Attribution Audit & Revenue Proof of Contribution Intelligence Engine](../01_CMO-&-Leadership/Reporting-&-ROI/AI-Powered-B2B-Marketing-Attribution-Audit-&-Revenue-Proof-of-Contribution-Intelligence-Engine.md)
- [Marketing Operations Performance Analytics & Revenue Operations Intelligence Engine](../05_Analytics-&-Performance/Marketing-Operations-Analytics/AI-Powered-B2B-SaaS-Marketing-Operations-Performance-Analytics-&-Revenue-Operations-Intelligence-Engine.md)
- [Demand Generation Budget Pacing & Real-Time Spend Optimization Intelligence Engine](../05_Analytics-&-Performance/Marketing-Operations-Analytics/AI-Powered-Demand-Generation-Budget-Pacing-&-Real-Time-Spend-Optimization-Intelligence-Engine.md)

## Integration Tips

**Salesforce:**
- Create a dedicated "Marketing Intelligence" connected app with read-only API access — never use admin credentials for automated data pulls
- Enable Salesforce Change Data Capture (CDC) for Opportunity and Lead objects to feed near-real-time pipeline events to your data warehouse without polling
- Build the `Campaign Influence` model in Salesforce matching your attribution model — this becomes the authoritative attribution source synced to your data warehouse, not a competing calculation

**HubSpot:**
- Use HubSpot's native Reporting API v3 for contact lifecycle stage history — this gives you the complete MQL date and source data needed for accurate funnel metrics
- Configure UTM parameter capture on all HubSpot forms and landing pages — map `utm_source`, `utm_medium`, `utm_campaign`, `utm_content` to custom contact properties stored permanently (HubSpot does not retain UTM data by default after contact merge)
- Use HubSpot Workflows to write a timestamp to a custom property when a contact reaches each lifecycle stage — this creates a reliable event log for funnel conversion rate calculations

**Google Analytics 4:**
- Implement a server-side tagging setup (Google Tag Manager server-side or Segment) to improve data completeness — browser-based GA4 loses 20-40% of events due to ad blockers and iOS privacy restrictions
- Create a BigQuery export of all GA4 raw event data — do not rely solely on the GA4 UI for attribution analysis; raw events in BigQuery give you full control over attribution modeling
- Define a canonical set of custom events in GA4 that map to your KPIs (e.g., `demo_request_submitted`, `pricing_page_viewed`, `content_downloaded`) — get marketing team, product, and engineering aligned on the event taxonomy before implementation

**Looker / Tableau:**
- Build a single certified semantic layer (LookML in Looker, or dbt metrics in Tableau via dbt integration) before building any dashboards — this prevents the proliferation of inconsistent metrics that created your original data credibility problem
- Use Looker's Schedules feature to deliver dashboard snapshots to Slack and email on a defined cadence — this is the mechanism for automating your weekly scorecard delivery
- Create a separate "Certified" content folder in Looker/Tableau where only approved dashboards live — stakeholders should never need to build their own — they should find pre-built, vetted answers

**Slack:**
- Create dedicated channels: `#marketing-performance` (weekly digest, milestone celebrations), `#marketing-ops-alerts` (anomaly alerts and data quality issues), `#pipeline-intel` (real-time pipeline creation notifications)
- Use Slack's Block Kit format for alert messages — structured formatting with action buttons ("Mark Resolved" / "Assign to Team Member") dramatically improves alert response rates vs. plain text messages
- Configure alert suppression logic: if an alert fires and is marked "acknowledged" within 2 hours, suppress repeat alerts for the same metric for 24 hours — prevents alert fatigue

**Google Sheets (transitional layer):**
- If you cannot immediately implement a data warehouse, use Google Sheets with Apps Script as a transitional layer — connect each marketing platform API to a master Google Sheet using Apps Script scheduled triggers, then build Looker Studio dashboards on top
- This approach can get you to 80% of the autonomous reporting value in 2-3 weeks vs. 2-3 months for a full warehouse implementation — use it as a bridge while the warehouse is being built

## Troubleshooting

**Problem 1: Stakeholders still pull their own numbers from native platform UIs, leading to conflicting metrics and loss of confidence in the centralized dashboard.**
Fix: This is a governance problem, not a data problem. (1) Run a "number audit" — document every place a metric is currently being pulled from and identify every discrepancy (e.g., "HubSpot shows 847 MQLs, Salesforce shows 791, the analyst's spreadsheet shows 823"). Use these discrepancies as proof of why the centralized system is necessary; (2) Document the single authoritative definition for every metric — publish this in Notion or Confluence as the "Marketing Metrics Glossary" with the calculation, data source, and a link to the certified dashboard; (3) Establish a "one source of truth" policy in writing, endorsed by the CMO and VP Sales — when anyone questions a number, the response is "what does the dashboard say?"; (4) Don't try to convince people with arguments. Run the centralized system in parallel with manual reports for 30 days, show where the discrepancies came from, and document which number turned out to be right.

**Problem 2: Anomaly alerts are firing too frequently (false positives) and team members have started ignoring them.**
Fix: Alert fatigue is a calibration problem. (1) Audit the last 30 days of alerts — categorize each as True Positive (genuine issue), False Positive (statistical noise), or Ambiguous; (2) For each False Positive category, tighten the detection threshold (e.g., raise from 1.5 standard deviations to 2.0 for that metric) or increase the minimum sample requirement; (3) Implement alert deduplication — if the same alert fires three consecutive days without resolution, escalate once (tag a senior owner) rather than sending three separate alerts; (4) Add a "thumbs down" reaction to Slack alert messages that automatically logs a feedback record for review — over time this builds a training dataset for threshold calibration; (5) Reduce alert frequency for low-priority metrics to weekly digest rather than real-time.

**Problem 3: Automated monthly CMO deck is generated but contains inaccurate or confusingly formatted AI-generated narrative text, undermining confidence.**
Fix: Separate data accuracy from narrative generation. (1) Prioritize getting the data tables and charts right before automating narrative text — a deck with accurate numbers and no narrative is more credible than one with polished but potentially wrong AI text; (2) Use AI narrative generation only for templated summaries where the logic is deterministic (e.g., "Pipeline is [X%] of target, [above/below] by [$Y]") rather than interpretive analysis; (3) Build in a 30-minute human review step for the CMO deck specifically — the CMO gets the auto-generated deck at 6 AM and has until a 9 AM calendar block to add 2-3 sentences of context before the deck is shared with the board; (4) Flag AI-generated text sections in the deck with a subtle indicator so the reviewer knows what to scrutinize vs. what is raw data.

## Version History
- v1.0: Initial creation (auto-generated)
