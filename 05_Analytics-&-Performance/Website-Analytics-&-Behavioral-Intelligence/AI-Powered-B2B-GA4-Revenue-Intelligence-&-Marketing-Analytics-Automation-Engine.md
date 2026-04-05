# AI-Powered B2B GA4 Revenue Intelligence & Marketing Analytics Automation Engine - Transform GA4 Data Into Pipeline-Grade B2B Marketing Intelligence With Automated Reporting

**Difficulty:** Advanced | **Time:** 30-45 min | **Tags:** GA4, google analytics 4, marketing analytics, B2B analytics, revenue intelligence, marketing attribution, conversion tracking, BigQuery, Looker Studio, marketing operations, pipeline analytics

## Overview
Designs a complete GA4-based B2B revenue intelligence system — from event taxonomy and custom dimension architecture to automated weekly insights reports, AI-powered anomaly detection, and CRM-connected pipeline attribution — engineered for marketing teams that need to move beyond vanity metrics and connect website behavior directly to pipeline and revenue. Use this when your GA4 is generating data but not generating decisions, or when your team is still manually building analytics reports instead of acting on AI-surfaced insights.

## Quick Copy-Paste Version

You are a senior B2B marketing analytics architect with deep expertise in GA4 implementation, revenue attribution, and marketing intelligence automation for SaaS and technology companies. Build a complete GA4 revenue intelligence system for the company below.

COMPANY CONTEXT:
- Company: [Your Company] — [e.g., "B2B procurement automation platform for mid-market manufacturing companies"]
- Business model: [e.g., "SaaS, $45K ACV, 90-day sales cycle, demo-first GTM motion"]
- Primary conversion goals: [e.g., "demo request, free trial signup, pricing page visit + 2+ min session"]
- Monthly website traffic: [e.g., "~35,000 sessions/month, 60% organic, 25% paid, 15% direct/other"]
- Current GA4 status: [e.g., "Basic GA4 installed with default events only — no custom events, no CRM integration, no custom reports"]
- CRM: [e.g., "HubSpot with deals, contacts, companies — using UTM parameters inconsistently"]
- Team: [e.g., "1 marketing ops person, analytics is secondary to their role"]
- Key marketing channels: [e.g., "SEO content, LinkedIn ads, Google Ads, email nurture, webinars"]

DELIVERABLES:

1. GA4 MEASUREMENT ARCHITECTURE FOR B2B
   - Complete event taxonomy: which custom events to track beyond GA4 defaults (form interactions, scroll milestones, CTA clicks, chatbot engagement, pricing page behavior, resource downloads, video views)
   - Custom dimensions and metrics needed for B2B intelligence (company size, industry, ICP tier, lead source, persona, deal stage if connected to CRM)
   - Conversion event hierarchy: micro-conversions → macro-conversions → pipeline events
   - UTM parameter governance framework: naming conventions that preserve attribution through the entire funnel to CRM deal

2. AUTOMATED REVENUE INTELLIGENCE REPORTS
   - Weekly executive dashboard: 5 KPIs that tell the revenue story (traffic quality, conversion rate by channel, pipeline-influenced sessions, content-to-conversion paths)
   - Channel performance scorecard: which channels drive traffic vs. conversions vs. pipeline — with week-over-week and trend analysis
   - Content performance report: which pages, posts, and resources drive the most conversions and what to create more of
   - Lead quality by source: mapping GA4 sessions to CRM conversion rates to identify which traffic sources produce the highest-quality pipeline (not just the most leads)

3. AI-POWERED ANOMALY DETECTION & ALERTS
   - 10 specific anomalies to monitor automatically (e.g., demo conversion rate drops >15%, organic traffic drops >20%, paid ROAS drops below threshold, specific landing page conversion rate collapses)
   - Alert trigger logic: thresholds, comparison windows, and escalation rules
   - Root cause analysis framework: when an anomaly fires, the sequence of diagnostic queries to run in GA4 to identify the cause within 30 minutes

4. CRM REVENUE ATTRIBUTION BRIDGE
   - GA4-to-HubSpot/Salesforce connection architecture: how to pass session data, UTM parameters, and GA4 client IDs to CRM contacts and deals
   - First-touch, last-touch, and multi-touch attribution setup in GA4 for B2B multi-session buying journeys
   - Pipeline influence tracking: how to measure which content and channels influenced deals that closed (not just leads created)
   - Revenue per visitor calculation: connecting closed-won deal value back to original traffic sources

5. BIGQUERY + LOOKER STUDIO AUTOMATION (for scale)
   - BigQuery export configuration: which tables to activate and what queries to run for B2B intelligence
   - 3 SQL query templates for: (a) channel-to-pipeline attribution, (b) content-to-conversion path analysis, (c) ICP vs. non-ICP traffic breakdown
   - Looker Studio dashboard template: layout, data connections, calculated fields, and automated refresh schedule

6. 90-DAY IMPLEMENTATION ROADMAP
   - Week 1-2: Quick wins — fix UTM governance, add 5 high-impact custom events, set up basic conversion goals
   - Week 3-6: Build the intelligence layer — custom dimensions, CRM integration, core dashboards
   - Week 7-12: Automate and scale — BigQuery export, automated reports, anomaly alerts

Output as a complete implementation guide that a marketing ops professional can execute without a full-time data engineer.

## Advanced Customizable Version

ROLE: You are a Principal Marketing Analytics Architect and Revenue Intelligence Strategist with 14+ years designing measurement systems for B2B SaaS companies from Series A through public markets. You specialize in GA4 implementation architecture, CRM-connected attribution, and building automated marketing intelligence programs that replace manual reporting with AI-powered insights. You've led analytics transformations at companies including [reference tier of company], connecting website behavior to pipeline and revenue with precision. Your frameworks include Data Layer architecture, UTM governance, multi-touch attribution modeling, BigQuery analytics engineering, and Looker Studio dashboard design. You build systems where insights surface automatically and analysts spend their time acting — not extracting.

---

BUSINESS CONTEXT:

Company Overview:
- Company name and description: [Name] — [1-sentence description of what you do and for whom]
- Business model: [SaaS / Usage-based / Transactional / Hybrid]
- ACV and sales cycle: [$X ACV, Y-day sales cycle]
- GTM motion: [Demo-led / Trial-led / Product-led / Sales-led / Hybrid]
- Primary ICP: [Job title, company size, industry, geography]
- Buying committee: [Who is involved in the purchase decision? e.g., VP Marketing, CMO, Marketing Ops, CFO]

Current State Assessment:
- Monthly website sessions: [X sessions/month]
- Traffic mix: [X% organic / Y% paid / Z% direct / W% referral / V% email]
- GA4 implementation status: [None / Default only / Partially configured / Well-configured]
- Current conversion rate (sessions → demo/trial): [X%]
- CRM: [HubSpot / Salesforce / Pipedrive / Other] with [brief description of deal/lead data quality]
- Marketing channels active: [List all channels: SEO, LinkedIn Ads, Google Ads, email, webinars, events, content syndication, etc.]
- Reporting stack today: [e.g., manual GA4 exports + Google Sheets, or Looker, or nothing structured]
- Team analytics capability: [e.g., "1 marketing ops person who knows basic GA4 but no SQL or BigQuery"]

Revenue Goals:
- MQL target: [X per month]
- Pipeline target: [$X pipeline per month from marketing]
- Marketing-influenced revenue target: [$X per quarter]
- Top 3 measurement questions you need answered: [e.g., "Which content drives the most pipeline-qualified leads?", "What's our true cost per pipeline dollar by channel?", "Which pages are losing high-intent visitors?"]

---

DELIVERABLE 1: COMPLETE GA4 MEASUREMENT ARCHITECTURE

**1A. Event Taxonomy Design**

For each of the following event categories, define: Event Name, Event Parameters (custom dimensions to capture), Trigger Condition, and Revenue Intelligence Value.

Engagement Events (user interactions beyond pageview):
- Form interactions: form_start, form_submit, form_abandon — with form_id, form_name, form_type parameters
- CTA clicks: cta_click — with cta_text, cta_location, cta_destination parameters
- Scroll depth: scroll_milestone — 25%, 50%, 75%, 90% — for long-form content and landing pages
- Resource engagement: resource_download, video_play, video_complete, chatbot_open, chatbot_lead_captured
- Navigation signals: internal_search, filter_applied, navigation_click_type, exit_intent_trigger
- Pricing page intelligence: pricing_page_view, pricing_tier_hover, pricing_faq_expand, pricing_cta_click
- Social proof engagement: case_study_open, testimonial_click, g2_badge_click, customer_logo_click

Intent Escalation Events (signals of high purchase intent):
- demo_request_initiated, demo_request_completed, demo_request_abandoned
- free_trial_started, free_trial_activated, free_trial_converted
- pricing_page_engaged (2+ minutes on pricing with CTA interaction)
- comparison_page_viewed (viewed >[competitor] comparison page)
- roi_calculator_completed, assessment_completed

**1B. Custom Dimensions & Metrics Architecture**

User-Scoped Custom Dimensions (persist across sessions):
- icp_tier: [Tier 1 / Tier 2 / Tier 3 / Non-ICP] — populated via Clearbit/6sense enrichment or CRM sync
- persona_segment: [Champion / Economic Buyer / Technical Evaluator / End User] — populated via form data or progressive profiling
- lifecycle_stage: [New Visitor / Known Lead / Opportunity / Customer] — synced from CRM via GA4 Measurement Protocol
- account_industry: [Industry classification from enrichment]
- company_size_band: [SMB <100 / Mid-Market 100-1000 / Enterprise 1000+]

Session-Scoped Custom Dimensions:
- utm_campaign_id: Campaign ID for granular attribution beyond default UTM
- content_topic: Primary topic cluster of the session's first landing page
- intent_score_session: Rolling intent score based on events fired in session (low / medium / high / very_high)
- is_return_visitor: Boolean — critical for B2B where 8-12 touchpoints precede conversion

Event-Scoped Custom Dimensions:
- form_id, form_name, form_type, form_step
- cta_category: [Primary / Secondary / Exit intent / Sticky / Navigation]
- content_format: [Blog / Case Study / Webinar / Tool / Pricing / Demo Landing Page]

Custom Metrics:
- engagement_score: Composite score (time on site × scroll depth × # events fired) normalized 0-100
- pipeline_qualified_session: Binary (1/0) — session that contains ≥2 high-intent signals

**1C. Conversion Hierarchy & Goal Configuration**

Level 1 — Micro-Conversions (leading indicators):
- Blog CTA click → weighing: 0.05x
- Resource download → weighing: 0.1x
- Pricing page 2+ min → weighing: 0.2x
- Chatbot lead capture → weighing: 0.3x

Level 2 — Macro-Conversions (direct demand gen):
- Demo request submitted → primary conversion, value: $[your CPL equivalent]
- Free trial activated → primary conversion, value: $[your CPL × trial-to-paid rate]
- Inbound call via tracked number → primary conversion

Level 3 — Pipeline Events (CRM-connected):
- MQL created → tracked via GA4 Measurement Protocol from CRM webhook
- SQL created → tracked via Measurement Protocol
- Opportunity opened → tracked via Measurement Protocol, value: expected pipeline value
- Deal closed-won → tracked via Measurement Protocol, value: actual ACV

---

DELIVERABLE 2: UTM GOVERNANCE FRAMEWORK

**Naming Convention Matrix:**

| Parameter | Format | Examples |
|-----------|--------|---------|
| utm_source | lowercase, no spaces, use underscore | linkedin, google, hubspot, newsletter |
| utm_medium | lowercase channel type | cpc, organic_social, email, cpm, sponsored_content |
| utm_campaign | [quarter]_[initiative]_[audience] | q2_enterprise_trial, q3_abm_financial_services |
| utm_content | [format]_[variant]_[cta] | carousel_a_demo, text_b_trial, banner_cro_v2 |
| utm_term | keyword or audience segment | enterprise_crm, procurement_automation |

**UTM Governance Rules:**
1. All paid media links must use Campaign Manager / UTM Builder — no manually typed UTMs
2. Email campaigns: use a shared UTM spreadsheet with dropdown validation per campaign
3. LinkedIn posts (organic): track separately with utm_medium=organic_social, utm_source=linkedin_organic
4. Partner links: utm_source=[partner_name], utm_medium=partner
5. Broken UTM audit: weekly automated scan of GA4 source/medium report for malformed parameters

**CRM UTM Persistence:**
- HubSpot: Install HubSpot tracking code + ensure all forms use HubSpot embed (not iframe) to capture UTM context
- Salesforce: Use custom UTM fields on Lead and Contact objects; map GA4 Client ID to contact for BigQuery join
- UTM persistence window: Use first-touch UTM stored in cookie (365-day window) AND last-touch UTM at conversion — report both in CRM

---

DELIVERABLE 3: AUTOMATED INTELLIGENCE REPORT TEMPLATES

**Weekly Revenue Intelligence Report (for CMO + Demand Gen)**

Section 1 — The Revenue Pulse (5 metrics, Monday AM auto-send)
- Pipeline-qualified sessions this week vs. 4-week average: [X sessions, +/-Y%]
- Demo conversion rate by top 3 channels: [channel: X%] — which channels are converting at above/below baseline
- Content pipeline influence: top 5 content pieces that appeared in converting sessions this week
- Organic traffic quality score: ICP-matching sessions / total organic sessions × 100
- Paid efficiency: pipeline-qualified sessions per $1,000 spent by campaign

Section 2 — Anomaly Alerts (AI-surfaced)
- Any metric that moved >15% week-over-week with likely root cause
- Channel mix shifts: if a channel's share of conversions changes >10%, flag with diagnostic

Section 3 — Top 3 Actionable Recommendations
- Each recommendation format: Observation → Root Cause Hypothesis → Recommended Action → Expected Impact → Responsible Owner

**Monthly Attribution Report (for CFO + CMO)**

Format the following as a boardroom-ready attribution analysis:
1. First-touch attribution: which channels introduced buyers to the brand
2. Last-touch attribution: which channels get credit for the conversion
3. Linear attribution: proportional credit across all touchpoints in the path
4. Data-driven attribution (GA4 ML model): AI-recommended credit allocation
5. "What actually matters" view: channels present in >30% of converting paths weighted by deal size

---

DELIVERABLE 4: ANOMALY DETECTION & DIAGNOSTIC PLAYBOOK

For each anomaly below, provide: Detection logic (threshold + time window), Diagnostic query sequence, Most likely root causes (top 3), and Resolution playbook.

Anomaly 1: Demo conversion rate drops >15% vs. 4-week average
Anomaly 2: Organic traffic drops >20% week-over-week
Anomaly 3: Paid search ROAS drops below breakeven threshold
Anomaly 4: Pricing page bounce rate increases >25%
Anomaly 5: Form abandonment rate spikes >20% on primary demo form
Anomaly 6: Mobile conversion rate diverges >30% from desktop rate
Anomaly 7: Top landing page's session duration drops >25%
Anomaly 8: Direct traffic spikes >40% (possible UTM tracking break)
Anomaly 9: New vs. returning visitor conversion rate ratio shifts significantly
Anomaly 10: A specific traffic source (e.g., LinkedIn, Google) conversion rate collapses to near zero

---

DELIVERABLE 5: BIGQUERY ANALYTICS ENGINEERING TEMPLATES

**Query 1: Channel-to-Pipeline Attribution**
-- This query joins GA4 BigQuery export with CRM pipeline data to calculate
-- pipeline-influenced revenue by marketing channel
-- Replace project_id, dataset, and CRM table references with your values

SELECT
  t.session_source AS channel,
  t.session_medium AS medium,
  COUNT(DISTINCT t.user_pseudo_id) AS total_sessions,
  COUNT(DISTINCT e.event_bundle_sequence_id) AS demo_requests,
  ROUND(COUNT(DISTINCT e.event_bundle_sequence_id) / COUNT(DISTINCT t.user_pseudo_id) * 100, 2) AS demo_cvr_pct,
  SUM(crm.deal_value) AS pipeline_influenced,
  ROUND(SUM(crm.deal_value) / NULLIF(COUNT(DISTINCT e.event_bundle_sequence_id), 0), 0) AS pipeline_per_demo
FROM `project_id.analytics_XXXXXXXX.events_*` t
LEFT JOIN (
  SELECT event_bundle_sequence_id, user_pseudo_id 
  FROM `project_id.analytics_XXXXXXXX.events_*`
  WHERE event_name = 'demo_request_completed'
    AND _TABLE_SUFFIX BETWEEN '20250101' AND FORMAT_DATE('%Y%m%d', CURRENT_DATE())
) e ON t.user_pseudo_id = e.user_pseudo_id
LEFT JOIN `project_id.crm_data.deals` crm ON t.user_pseudo_id = crm.ga4_client_id
WHERE t._TABLE_SUFFIX BETWEEN '20250101' AND FORMAT_DATE('%Y%m%d', CURRENT_DATE())
GROUP BY 1, 2
ORDER BY pipeline_influenced DESC
LIMIT 25

**Query 2: Content-to-Conversion Path Analysis**
-- Identifies which content pieces appear most frequently in converting user journeys
-- Helps content team understand what to create more of and what to promote

WITH converting_users AS (
  SELECT DISTINCT user_pseudo_id
  FROM `project_id.analytics_XXXXXXXX.events_*`
  WHERE event_name = 'demo_request_completed'
    AND _TABLE_SUFFIX >= FORMAT_DATE('%Y%m%d', DATE_SUB(CURRENT_DATE(), INTERVAL 90 DAY))
),
user_content_touches AS (
  SELECT
    e.user_pseudo_id,
    ep.value.string_value AS page_path,
    e.event_timestamp
  FROM `project_id.analytics_XXXXXXXX.events_*` e,
  UNNEST(event_params) AS ep
  WHERE e.event_name = 'page_view'
    AND ep.key = 'page_location'
    AND _TABLE_SUFFIX >= FORMAT_DATE('%Y%m%d', DATE_SUB(CURRENT_DATE(), INTERVAL 90 DAY))
)
SELECT
  uct.page_path,
  COUNT(DISTINCT uct.user_pseudo_id) AS converting_users_who_visited,
  ROUND(COUNT(DISTINCT uct.user_pseudo_id) / (SELECT COUNT(*) FROM converting_users) * 100, 1) AS pct_of_converters,
  AVG(touch_sequence) AS avg_touch_position
FROM user_content_touches uct
JOIN converting_users cu ON uct.user_pseudo_id = cu.user_pseudo_id
GROUP BY 1
HAVING COUNT(DISTINCT uct.user_pseudo_id) >= 10
ORDER BY 2 DESC
LIMIT 50

**Query 3: ICP vs. Non-ICP Traffic Quality Breakdown**
-- Segments sessions by ICP tier (populated via custom dimension from enrichment)
-- Shows which channels and pages attract ICP-matching visitors vs. non-ICP noise

SELECT
  custom_dim.icp_tier,
  t.session_source AS channel,
  COUNT(DISTINCT t.user_pseudo_id) AS sessions,
  AVG(CAST(engagement.value.int_value AS FLOAT64)) AS avg_engagement_score,
  COUNT(DISTINCT CASE WHEN demo.user_pseudo_id IS NOT NULL THEN t.user_pseudo_id END) AS demo_requests,
  ROUND(
    COUNT(DISTINCT CASE WHEN demo.user_pseudo_id IS NOT NULL THEN t.user_pseudo_id END) 
    / NULLIF(COUNT(DISTINCT t.user_pseudo_id), 0) * 100, 2
  ) AS demo_cvr_pct
FROM `project_id.analytics_XXXXXXXX.events_*` t,
UNNEST(event_params) AS custom_dim,
UNNEST(event_params) AS engagement
LEFT JOIN (
  SELECT DISTINCT user_pseudo_id
  FROM `project_id.analytics_XXXXXXXX.events_*`
  WHERE event_name = 'demo_request_completed'
    AND _TABLE_SUFFIX >= FORMAT_DATE('%Y%m%d', DATE_SUB(CURRENT_DATE(), INTERVAL 30 DAY))
) demo ON t.user_pseudo_id = demo.user_pseudo_id
WHERE custom_dim.key = 'icp_tier'
  AND engagement.key = 'engagement_score'
  AND t._TABLE_SUFFIX >= FORMAT_DATE('%Y%m%d', DATE_SUB(CURRENT_DATE(), INTERVAL 30 DAY))
GROUP BY 1, 2
ORDER BY 1, sessions DESC

---

DELIVERABLE 6: 90-DAY IMPLEMENTATION ROADMAP

Phase 1 — Foundation (Days 1-14): Accuracy & Quick Wins
- Day 1-3: UTM audit — identify all broken/missing UTMs in last 90 days of GA4 data, fix top 3 sources
- Day 3-5: Implement 5 highest-impact custom events: demo_request_completed, pricing_page_engaged, resource_download, video_play, chatbot_lead_captured
- Day 5-7: Configure GA4 conversion events and assign values based on historical CPL/pipeline data
- Day 7-10: Enable GA4 → BigQuery export (free up to 1M events/day)
- Day 10-14: Build Looker Studio "Revenue Pulse" dashboard connecting to GA4 with 5 core KPIs

Phase 2 — Intelligence Layer (Days 15-45): Custom Dimensions & CRM Bridge
- Day 15-20: Implement custom dimensions for icp_tier and persona_segment (requires enrichment tool or CRM webhook)
- Day 20-28: GA4 Measurement Protocol setup — send MQL, SQL, and opportunity events from CRM to GA4 to enable pipeline attribution
- Day 28-35: Build content performance and channel attribution reports in BigQuery + Looker Studio
- Day 35-45: Activate anomaly detection — set up automated alerts in GA4 Intelligence or Looker Studio

Phase 3 — Automation & Scale (Days 46-90): Self-Running Intelligence
- Day 46-55: Automate weekly Revenue Intelligence Report — schedule Looker Studio email delivery or connect to Slack via Zapier
- Day 55-65: Build data-driven attribution model in GA4 (requires 700+ conversions/month; if below threshold, use linear)
- Day 65-75: Train AI assistant (ChatGPT, Claude, or Gemini via BigQuery ML) on your GA4 data patterns to auto-generate weekly insights
- Day 75-90: Quarterly audit protocol — review event taxonomy, dimension coverage, report accuracy; schedule recurring monthly data quality checks

Output this as a complete implementation guide with week-by-week action items, tool requirements, and success criteria for each phase. Include estimated time investment per phase and clear owner assignments (marketing ops, developer, analytics lead).

## Example Input/Output

**Input Example:**

Company: Vantage Procurement Intelligence — AI-powered spend analytics and supplier management platform for mid-market manufacturers ($50M–$500M revenue)
Business model: B2B SaaS, $55K ACV, 110-day sales cycle, demo-led
Primary ICP: VP Operations, Director of Supply Chain, CFO at Tier 2-3 manufacturing companies in US/Canada
Monthly traffic: ~28,000 sessions/month — 52% organic, 28% paid search (Google Ads), 12% LinkedIn Ads, 8% direct/email
GA4 status: Default install only, no custom events, no CRM integration, conversions not configured
CRM: HubSpot with 340 contacts, 28 active deals, average deal value $55K
Key channels: SEO (22 blog posts ranking), Google Ads ($18K/month), LinkedIn sponsored content ($9K/month), monthly webinar series

**Output Example:**

**Immediate Anomaly Discovered:**
"Your Google Ads account shows 340 demo form clicks in GA4 last month, but HubSpot only shows 47 demo form submissions from paid search origin — a 7:1 discrepancy. This is a tracking break, not a qualification problem. The form is likely hosted on a subdomain (forms.vantagepi.com) that's not included in your GA4 data stream. This means you've been optimizing Google Ads toward phantom conversions. Estimated wasted spend: $4,200/month. Fix: Add forms subdomain to GA4 data stream and cross-domain measurement configuration."

**Content Intelligence Finding (from BigQuery Query 2):**
"Of your last 52 demo requests, 81% visited your 'True Cost of Manual Procurement' calculator before converting — but only 6% of your total sessions reach that page. It's buried in your blog footer. Moving this tool to your homepage navigation could increase demo conversion rate by an estimated 18-25%. This single change, if it holds at current traffic levels, is worth approximately $380K in additional annual pipeline."

**Channel Attribution Revelation:**
"LinkedIn Ads shows last-touch attribution of only 8 demo requests ($1,125 per demo at $9K spend). But first-touch attribution shows LinkedIn is introducing 31% of all eventual converters to the brand. Your Google Ads are capturing demand that LinkedIn created. True blended LinkedIn CPL when accounting for assist touches: $290 — well within your target. Recommendation: increase LinkedIn spend by $5K/month focused on awareness-stage content; expect Google Ads volume to increase as a downstream effect."

## Success Metrics

- **Tracking accuracy:** ≥95% of form submissions captured in GA4 (validate by comparing GA4 conversions vs. HubSpot new contacts weekly)
- **Attribution coverage:** ≥80% of CRM opportunities have first-touch and last-touch UTM data populated
- **Report automation:** Zero manual data exports required for weekly reporting — all dashboards self-refresh
- **Anomaly response time:** All anomalies detected and root cause identified within 24 hours of occurrence (vs. weeks when discovered manually)
- **Decision quality:** At least 2 budget reallocation decisions per quarter directly driven by GA4 intelligence (document these)
- **Pipeline per visitor improvement:** 15-25% increase in pipeline-qualified sessions within 90 days of full implementation, holding traffic volume constant

## Related Prompts

- [Customer Journey Analytics & Cross-Channel Path Intelligence Engine](./Customer-Journey-Analytics-&-Cross-Channel-Path-Intelligence-Engine.md)
- [AI-Powered B2B Anonymous Visitor Intelligence & Account Pipeline Identification Engine](./AI-Powered-B2B-Anonymous-Visitor-Intelligence-&-Account-Pipeline-Identification-Engine.md)
- [Multi-Touch Attribution & Revenue Marketing Intelligence Engine](../Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md)
- [Marketing Operations Data Quality & CRM Hygiene Intelligence Engine](../Marketing-Operations-Analytics/Marketing-Operations-Data-Quality-&-CRM-Hygiene-Intelligence-Engine.md)

## Integration Tips

- **GA4 → BigQuery:** Enable the native BigQuery export in GA4 Admin (free tier covers up to 1M events/day). Use `events_*` wildcard tables for historical queries and `events_intraday_*` for same-day data. Join on `user_pseudo_id` + `ga_session_id` for session-level analysis.
- **HubSpot integration:** Install the HubSpot-GA4 integration to sync UTM data to contact properties automatically. Use HubSpot's Contact Activity Timeline to verify GA4 sessions are connecting properly. For pipeline attribution, use the HubSpot → GA4 Measurement Protocol workflow: trigger → HubSpot webhook → Zapier/Make → GA4 MP API.
- **Salesforce integration:** Use Salesforce's native Google Analytics connector or a third-party tool (Windsor.ai, Supermetrics) to sync deal data to BigQuery alongside GA4 exports. Map GA4 `user_pseudo_id` to Salesforce Contact `GA4_Client_ID__c` field via form hidden field capture.
- **Looker Studio:** Connect directly to GA4 (native connector) and BigQuery (native connector). Use Blended Data sources to join GA4 and CRM data in a single dashboard. Schedule email delivery of dashboards to CMO and demand gen team every Monday at 8 AM.
- **Slack alerts:** Connect Looker Studio or BigQuery to Slack via Zapier or Make.com. Set up a `#marketing-intelligence` channel that receives automated weekly reports and anomaly alerts. This replaces manual reporting emails and keeps insights visible to the full team.
- **Google Ads & Meta integration:** Connect Google Ads and Meta Ads to GA4 via their native integrations to enable cross-platform ROAS reporting and auto-tagging. Import GA4 conversions back into Google Ads for Smart Bidding optimization using pipeline-quality signals (not just form fills).

## Troubleshooting

**Problem: GA4 conversion numbers don't match form submissions in HubSpot/Salesforce**
Solution: This is almost always a cross-domain tracking issue (forms on a subdomain or third-party form tool), an ad blocker/privacy browser impact, or a GA4 filter misconfiguration. Audit your GA4 data streams to confirm all domains and subdomains are included. Check that your form tool (HubSpot forms, Typeform, Webflow) fires a GA4 event on submission (not just on page load after redirect). Validate by comparing 7-day GA4 conversion data vs. CRM new leads daily for 2 weeks and identifying the systematic gap.

**Problem: Attribution data shows "direct / (none)" as top converting channel — impossible to act on**
Solution: "(direct)" in GA4 catches three things: truly direct traffic, broken UTMs from campaigns, and cross-device journeys where cookies didn't persist. Run the UTM audit query in BigQuery to identify campaigns sending traffic without UTM parameters (especially email campaigns and organic social). Implement UTM enforcement: no campaign link goes live without UTMs checked in your UTM builder. For cross-device attribution gaps, enable GA4's User ID feature by passing authenticated user IDs — this dramatically improves attribution for logged-in users and SaaS trial customers.

**Problem: BigQuery queries return no data or "table not found" errors**
Solution: GA4 BigQuery export has a 24-48 hour lag — intraday tables exist but may not include yesterday's data yet. Verify export is active in GA4 Admin → BigQuery Links. Confirm you're querying the correct project and dataset ID (format: `project_id.analytics_PROPERTY_ID.events_YYYYMMDD`). For wildcard queries, ensure your `_TABLE_SUFFIX` date range doesn't extend into the future. Common error: querying `events_*` without a WHERE clause on `_TABLE_SUFFIX` will scan your entire export history and either timeout or generate large BigQuery costs — always include a date range filter.

## Version History
- v1.0: Initial creation (auto-generated)
