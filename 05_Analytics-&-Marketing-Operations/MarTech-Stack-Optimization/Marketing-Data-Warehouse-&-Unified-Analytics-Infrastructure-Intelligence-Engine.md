# Marketing Data Warehouse & Unified Analytics Infrastructure Intelligence Engine - Build a Scalable Marketing Data Foundation for Self-Serve Analytics

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** data-warehouse, marketing-analytics, martech, data-infrastructure, snowflake, bigquery, self-serve-analytics, unified-customer-view, revops

## Overview
Generates a complete marketing data warehouse architecture, unified customer data model, implementation roadmap, and governance framework for B2B SaaS and enterprise marketing teams. Use this when you need to move beyond disconnected dashboards and build a single source of truth for all marketing data — enabling attribution, cohort analysis, LTV modeling, and self-serve analytics without constant engineering dependency.

## Quick Copy-Paste Version

You are a senior marketing data architect and analytics engineer. Design a complete marketing data warehouse and unified analytics infrastructure for my company.

Company context:
- Company: [Your Company Name]
- Stage: [Series B / Enterprise / SMB]
- Current MarTech stack: [List tools: HubSpot/Salesforce, Google Ads, LinkedIn Ads, Marketo, Segment, etc.]
- Cloud/data warehouse preference: [Snowflake / BigQuery / Redshift / Databricks]
- BI tool: [Looker / Tableau / Metabase / Power BI]
- Team: [Marketing team size and data/ops capabilities]
- Primary analytics use cases: [Attribution, LTV, cohort analysis, pipeline reporting, etc.]

Deliver:
1. ARCHITECTURE BLUEPRINT — Data flow diagram (text-based), source connectors needed, transformation layer design, and warehouse schema structure
2. UNIFIED CUSTOMER DATA MODEL — Core tables/entities (Contacts, Accounts, Sessions, Events, Opportunities, Campaigns, Touchpoints) with key fields and relationships
3. MARKETING DATA MARTS — Specific schemas for: Attribution & Pipeline, Campaign Performance, Audience & Segmentation, Product Usage & PQL scoring
4. IMPLEMENTATION ROADMAP — Phased 90-day plan: Phase 1 (foundations + 3 critical sources), Phase 2 (all major sources + basic attribution), Phase 3 (advanced models + self-serve)
5. TOOL RECOMMENDATIONS — Best ETL/ELT (Fivetran/Airbyte/Stitch), transformation (dbt), orchestration (Airflow/Prefect), semantic layer options with rationale
6. GOVERNANCE FRAMEWORK — Naming conventions, documentation standards, data quality checks, access control matrix, and change management process
7. SELF-SERVE ANALYTICS ENABLEMENT — Dashboard templates for CMO, demand gen, content, and RevOps personas with specific metrics and dimensions

Format each section clearly. Include specific SQL schema examples for the most critical marketing tables. Prioritize revenue impact in the roadmap sequencing.

## Advanced Customizable Version

ROLE: You are a Principal Marketing Analytics Engineer and Revenue Operations Architect with 12+ years experience designing data infrastructure for B2B SaaS companies ranging from $5M to $500M ARR. You have deep expertise in dbt, Snowflake, BigQuery, Fivetran, and have built unified customer data models used by marketing teams at Salesforce, HubSpot, Gainsight, and Drift. You understand both the technical architecture AND the business outcomes marketing leaders need to drive.

COMPANY PROFILE:
- Company name: [Company Name]
- Industry/vertical: [e.g., B2B SaaS / FinTech / HealthTech]
- ARR/stage: [e.g., $25M ARR, Series B]
- ICP: [e.g., Mid-market CFOs at 200-2000 employee companies]
- GTM motion: [e.g., Inbound + outbound + PLG / Enterprise field sales / Product-led]
- Monthly marketing spend: [$X across paid, events, content]

CURRENT TECHNOLOGY LANDSCAPE:
Marketing Automation: [HubSpot / Marketo / Pardot]
CRM: [Salesforce / HubSpot CRM / Dynamics]
Paid Advertising: [Google Ads, LinkedIn Ads, Meta, G2, etc.]
Product Analytics: [Amplitude / Mixpanel / Heap / Segment]
CDP/Enrichment: [Segment / Clearbit / 6sense / Bombora]
Website Analytics: [GA4 / Heap / Hotjar]
Customer Success: [Gainsight / ChurnZero / Totango]
Current Reporting: [Spreadsheets / Looker / Tableau / Salesforce dashboards]
Existing Data Infrastructure: [None / Basic / Partial warehouse / Full stack]

BUSINESS OBJECTIVES FOR DATA INFRASTRUCTURE:
Primary: [e.g., Unified multi-touch attribution across 8 channels]
Secondary: [e.g., Self-serve analytics for 5 marketing personas, reduce eng requests]
Revenue: [e.g., Connect marketing activity to closed-won revenue and NRR]
Operational: [e.g., Real-time campaign performance alerting, faster reporting cycles]

CONSTRAINTS & REQUIREMENTS:
Budget: [e.g., $2K-5K/month for data infrastructure tools]
Timeline: [e.g., Full implementation in 90 days, first use cases in 30 days]
Team: [e.g., 1 marketing ops person, access to 1 data engineer 50% of time]
Compliance: [GDPR / CCPA / SOC 2 / HIPAA requirements]
Cloud preference: [AWS / GCP / Azure / No preference]

DELIVERABLES — Generate each section with maximum specificity:

---
SECTION 1: ARCHITECTURE BLUEPRINT & DATA FLOW
- End-to-end data flow diagram (ASCII/text format) from sources → ingestion → warehouse → transformation → semantic layer → consumption
- Source system inventory matrix: system, data type, update frequency, volume estimate, business priority, connector recommendation
- Medallion architecture design (Bronze/Silver/Gold layers) adapted for marketing use cases
- Identity resolution approach: how to unify Person, Account, and Anonymous Visitor records across systems
- Decision framework: real-time streaming vs. batch ETL for each source category

---
SECTION 2: UNIFIED CUSTOMER DATA MODEL (ENTITY-RELATIONSHIP)
Design the core marketing data model with:

a) Core entities and relationships:
   - dim_accounts: Account firmographics, ICP score, segment, health score, contract value
   - dim_contacts: Person identity, role, persona, engagement score, lifecycle stage
   - dim_campaigns: Campaign metadata, budget, targeting, channel, tactic
   - fact_touchpoints: Every marketing interaction with timestamp, channel, content, account_id, contact_id, session_id
   - fact_opportunities: Pipeline, stage, close date, influence tracking, marketing source
   - fact_product_events: Product usage events linked to contact/account for PQL scoring

b) Identity graph design: merging anonymous sessions → known contacts → account associations
c) Slowly Changing Dimensions (SCD) strategy for persona/segment changes
d) Include DDL (CREATE TABLE SQL) for the 3 most business-critical tables

---
SECTION 3: MARKETING DATA MARTS
Design purpose-built data marts for each marketing function:

a) ATTRIBUTION MART: Multi-touch attribution model implementation (U-shaped, W-shaped, data-driven), position-based weighting, time-decay falloff, first-party signal prioritization vs. ad platform data, cross-device/cross-session stitching methodology

b) PIPELINE & REVENUE MART: Marketing-sourced vs. marketing-influenced pipeline definitions, campaign-to-opportunity association rules, revenue attribution SQL logic, MQL→SQL→SAL→SQO→Won funnel with stage timestamps

c) AUDIENCE & SEGMENTATION MART: ICP scoring model schema, persona classification, engagement tier calculation, lookalike seed audience generation, cohort definitions for retention analysis

d) PRODUCT USAGE & PQL MART: Behavioral event taxonomy, PQL scoring model (activation milestones, usage thresholds, engagement recency), freemium-to-paid conversion tracking

e) CAMPAIGN ECONOMICS MART: Blended CAC calculation, channel-level CPL/CPA/CAC, ROAS with revenue attribution, payback period calculation, LTV:CAC by cohort and channel

---
SECTION 4: TOOL SELECTION & TECHNOLOGY RECOMMENDATIONS
For each category, provide recommendation + rationale + total cost estimate:

a) ELT/Ingestion: [Fivetran vs. Airbyte vs. Stitch vs. Census vs. custom] — for each data source
b) Data Transformation: [dbt Core vs. dbt Cloud vs. SQLMesh] — with project structure recommendation
c) Orchestration: [Airflow vs. Prefect vs. Dagster vs. dbt Cloud Jobs]
d) Semantic/Metrics Layer: [dbt Metrics vs. Cube.js vs. LookML vs. AtScale]
e) BI/Visualization: [Looker vs. Tableau vs. Metabase vs. Power BI vs. Sigma] — mapped to user personas
f) Reverse ETL (for activation): [Census vs. Hightouch vs. Polytomic] — for syncing segments back to CRM/MAP
g) Data Quality/Observability: [Monte Carlo vs. Great Expectations vs. dbt tests]
h) Total stack cost breakdown: monthly and annual

---
SECTION 5: 90-DAY IMPLEMENTATION ROADMAP

SPRINT 0 (Days 1-7): Foundation
- Infrastructure setup, access provisioning, naming conventions, dbt project scaffolding

PHASE 1 (Days 8-30): Critical Path — Revenue Attribution
- Priority sources to connect first (ranked by revenue visibility impact)
- Core attribution model: which 3 sources provide 80% of attribution signal
- First dashboard: marketing pipeline contribution for CEO/CMO
- Success criteria: X% of closed-won opportunities have marketing attribution within 30 days

PHASE 2 (Days 31-60): Full Source Coverage + Self-Serve Foundation
- Connect remaining 6-8 sources
- Build dbt models for all 5 data marts
- Deploy self-serve dashboards for demand gen, content, and paid media teams
- Implement data quality tests and alerting

PHASE 3 (Days 61-90): Advanced Models + Activation
- PQL scoring model deployed to CRM
- Lookalike audiences activated via reverse ETL
- Predictive churn/expansion signals wired to CS/sales
- Full governance documentation and data catalog live
- Success metrics for each phase

---
SECTION 6: DATA GOVERNANCE & QUALITY FRAMEWORK
- Naming conventions: database → schema → table → column naming standards with examples
- Documentation requirements: what must be documented in dbt model YAML files
- Data freshness SLAs by data category (real-time / hourly / daily / weekly)
- Data quality checks: completeness, uniqueness, referential integrity, freshness tests for each critical table
- Access control matrix: who can access what (CMO, director, analyst, RevOps, sales, external agency)
- GDPR/CCPA compliance: PII identification, data retention policies, right-to-delete implementation
- Incident response: data quality alert escalation process
- Change management: how to propose, review, and deploy schema changes

---
SECTION 7: SELF-SERVE ANALYTICS ENABLEMENT

For each persona, define the canonical dashboard with specific metrics, dimensions, and refresh cadence:

a) CMO Dashboard: Pipeline contribution, CAC trends, LTV:CAC ratio, marketing-sourced ARR, channel mix efficiency, YoY/QoQ comparisons

b) Demand Gen Manager Dashboard: MQL volume, MQL→SQL conversion by source, campaign ROAS, CPL by channel, pipeline coverage ratio, forecast vs. actual

c) Content Marketing Dashboard: Content-attributed pipeline, organic traffic → lead conversion, content velocity, top-performing assets by stage and persona

d) Paid Media Dashboard: Blended CAC, ROAS by platform, cross-channel frequency analysis, audience overlap, daypart/dayofweek performance

e) RevOps/Operations Dashboard: Data freshness monitoring, funnel stage SLA compliance, attribution model confidence scores, data quality metrics

---
SECTION 8: AI AGENT AUTOMATION OPPORTUNITIES
- Which data pipeline tasks can be automated with AI agents (anomaly detection, narrative generation, audience refresh)
- Weekly automated insights digest: SQL + prompt template to generate executive commentary on data changes
- Automated alerting logic: thresholds and routing for pipeline drop, CAC spike, conversion rate decline
- Predictive model integration points: where ML models plug into the warehouse architecture

OUTPUT FORMAT: Use clear headers for each section. Include tables where comparisons are needed. Include SQL code blocks for schema definitions. Be specific — use real tool names, real cost ranges, real SQL syntax. Avoid generic advice; this should read like a $200/hr consultant's deliverable that a marketing ops team can act on immediately.

## Example Input/Output

**Example Company:** Meridian AI — B2B SaaS, $18M ARR Series B, 45-person company. Sells AI workflow automation to operations leaders at 500-5000 person companies. Current stack: HubSpot (MAP + CRM), Google Ads ($40K/mo), LinkedIn Ads ($25K/mo), Segment (product analytics), Clearbit (enrichment), Webflow (website), Gong (sales). BI: Spreadsheets + HubSpot native dashboards. Cloud: AWS.

**Example Output (excerpt):**

---

**ARCHITECTURE BLUEPRINT — Meridian AI**

[Data Sources]                [Ingestion]         [Warehouse: Snowflake]        [Consumption]
─────────────────             ──────────          ──────────────────────────    ─────────────
HubSpot (CRM+MAP)  ──────────► Fivetran    ──────► BRONZE (raw, append-only)   ──► Metabase
Google Ads         ──────────► Fivetran    ──────► SILVER (cleaned, typed)     ──► Slack Alerts
LinkedIn Ads       ──────────► Fivetran    ──────► GOLD (business-logic marts)  ──► HubSpot (reverse ETL)
Segment (events)   ──────────► Segment CDP ──────► ┌─ attribution_mart         ──► Google Sheets
Clearbit           ──────────► Fivetran    ──────► ├─ pipeline_mart
Gong (calls)       ──────────► Fivetran    ──────► ├─ audience_mart
Webflow / GA4      ──────────► Fivetran    ──────► ├─ pql_scoring_mart
                                                   └─ campaign_economics_mart
                                           ──────► [dbt transformations throughout SILVER → GOLD]

**CRITICAL TABLE: fact_touchpoints**
CREATE TABLE gold.fact_touchpoints (
    touchpoint_id         VARCHAR(36)    NOT NULL,  -- UUID
    contact_id            VARCHAR(36),               -- FK to dim_contacts
    account_id            VARCHAR(36),               -- FK to dim_accounts  
    anonymous_id          VARCHAR(36),               -- Pre-identification session
    campaign_id           VARCHAR(36),               -- FK to dim_campaigns
    opportunity_id        VARCHAR(36),               -- FK to fact_opportunities (if influenced)
    touchpoint_timestamp  TIMESTAMP_NTZ NOT NULL,
    channel               VARCHAR(50),               -- 'paid_search' | 'linkedin_ads' | 'organic' | 'email' | 'direct_event'
    channel_group         VARCHAR(30),               -- 'paid' | 'organic' | 'outbound' | 'partner'
    source                VARCHAR(100),              -- UTM source
    medium                VARCHAR(100),              -- UTM medium
    campaign_name         VARCHAR(200),              -- UTM campaign
    content_asset         VARCHAR(200),              -- Landing page, ad creative, email ID
    touchpoint_type       VARCHAR(50),               -- 'ad_click' | 'form_fill' | 'email_open' | 'page_view' | 'demo_request' | 'event_attendance'
    is_converting_touch   BOOLEAN,                   -- Was this touch followed by lifecycle stage advancement?
    lifecycle_stage_before VARCHAR(50),
    lifecycle_stage_after  VARCHAR(50),
    attributed_pipeline   DECIMAL(15,2),             -- W-shaped attribution weight × opportunity ARR
    attributed_revenue    DECIMAL(15,2),             -- Same, post-close
    cost_per_touchpoint   DECIMAL(10,4),             -- Campaign spend ÷ touchpoints (for paid channels)
    data_source           VARCHAR(50),               -- 'hubspot' | 'segment' | 'google_ads_api' | 'linkedin_api'
    loaded_at             TIMESTAMP_NTZ DEFAULT CURRENT_TIMESTAMP(),
    PRIMARY KEY (touchpoint_id)
);

**PHASE 1 PRIORITY (Days 8-30) — Connect These 4 Sources First:**

| Source | Why First | Business Impact |
|--------|-----------|----------------|
| HubSpot CRM | All contacts, opportunities, stages | Pipeline attribution baseline |
| Google Ads | $40K/mo spend needs immediate ROAS visibility | CAC optimization, $8K-15K/mo savings potential |
| LinkedIn Ads | $25K/mo, B2B primary channel | ICP audience performance, quality score |
| Segment | Product events → PQL signals | Sales prioritization, 23% avg conversion lift |

**90-Day Success Criteria:**
- Day 30: CMO can see marketing-sourced pipeline % without opening 3 spreadsheets
- Day 60: Demand gen team self-serves weekly performance reports in <5 min
- Day 90: PQL scores flowing to HubSpot contact records, sales using for prioritization

**Tool Stack for Meridian AI (estimated $2,800/month):**
- Fivetran (Team): $800/month — 8 connectors
- Snowflake (Standard, 2 credits/day): $600/month
- dbt Cloud (Team): $200/month
- Metabase (Pro): $500/month
- Hightouch (reverse ETL to HubSpot): $300/month
- Monte Carlo (data observability): $400/month

---

## Success Metrics

**Architecture Quality:**
- All marketing data sources connected with <24hr latency (hourly for critical)
- 95%+ data freshness SLA met across core tables
- Zero discrepancy between warehouse attribution and platform-reported metrics (within 5%)

**Business Impact:**
- Marketing team can answer attribution questions in <10 minutes vs. previous 2+ days
- Engineering request queue for marketing data drops by 80%
- Attribution accuracy improvement: 40%+ of pipeline has multi-touch attribution (vs. typically <20% in spreadsheet-era)

**Adoption:**
- 4+ marketing personas using self-serve dashboards weekly within 60 days
- CMO reviews data warehouse-powered dashboard in board prep (not spreadsheets)
- Reverse ETL activated: PQL scores and audience segments flowing back to CRM/MAP

## Related Prompts

- `../../05_Analytics-&-Marketing-Operations/MarTech-Stack-Optimization/CRM-Revenue-Operations-Intelligence-Engine.md`
- `../../05_Analytics-&-Marketing-Operations/MarTech-Stack-Optimization/First-Party-Data-CDP-Strategy-Engine.md`
- `../../05_Analytics-&-Marketing-Operations/Campaign-Performance-Analysis/Marketing-Attribution-ROI-Engine.md`
- `../../05_Analytics-&-Marketing-Operations/Advanced-Marketing-Intelligence/Privacy-First-Marketing-Measurement-&-Cookieless-Attribution-Engine.md`

## Integration Tips

**dbt Cloud:** Connect your Snowflake/BigQuery warehouse to dbt Cloud for transformation. Use the `generate_schema_name` macro to enforce the Bronze/Silver/Gold naming convention. Schedule daily full-refresh of dimension tables and incremental runs every hour for fact tables.

**Fivetran → Snowflake:** Use Fivetran's HubSpot connector for CRM data (syncs every 15 min). Enable the `HUBSPOT_ENGAGEMENT` schema for call/email activity. Map Fivetran's normalized output to your custom `dim_contacts` schema via dbt staging models.

**Hightouch (Reverse ETL) → HubSpot:** After building your PQL scoring model in the Gold layer, use Hightouch to sync `pql_score`, `engagement_tier`, and `predicted_conversion_date` back to HubSpot Contact custom properties. Trigger a HubSpot workflow on `pql_score > 75` to alert the SDR team.

**Metabase / Looker:** Create a "Marketing Command Center" collection with role-based access. Use row-level security to restrict individual rep data. Embed the CMO dashboard in Notion for board prep materials.

**Slack Alerting:** Use dbt Cloud webhooks + a Slack bot to push anomaly alerts (CAC spike >20%, MQL volume drop >30%, data freshness breach) to `#marketing-ops-alerts`. Include a "what changed" context block generated by querying the attribution mart delta.

**Google Sheets Export:** For stakeholders who prefer spreadsheets, use Metabase's scheduled question export or Coefficient.io to keep a live Google Sheet synced from the Gold layer. Useful for finance reconciliation of marketing spend.

## Troubleshooting

**Problem: HubSpot contact IDs don't match Segment anonymous IDs — touchpoints can't be stitched to known contacts.**
Fix: Implement `analytics.identify()` calls in your product/website when a form is filled or login occurs. Build an `identity_map` staging model that joins `segment.identifies` (which contains both `anonymous_id` and `user_id`/email) to your `dim_contacts`. This becomes your identity graph bridge table. Backfill is hard — prioritize getting it right going forward.

**Problem: Google Ads, LinkedIn, and HubSpot all report different numbers for the same campaign — no one trusts the warehouse.**
Fix: This is the "source of truth conflict" problem. Define a hierarchy in your `dim_campaigns` model: ad platform data is authoritative for impressions/clicks/spend; HubSpot/CRM is authoritative for lead counts and pipeline; Snowflake is the reconciliation layer. Document the discrepancy reasons (platform attribution windows, cross-device, view-through) in your data catalog. Build a "reconciliation dashboard" that shows platform-reported vs. warehouse-reported side by side with the delta explained.

**Problem: dbt models are running for 45+ minutes and slowing down the team.**
Fix: Audit your `fact_touchpoints` model — it's likely doing a full table scan. Add clustering keys on `touchpoint_timestamp` and `account_id` in Snowflake (or partitioning in BigQuery). Convert large dimension tables to incremental models using `is_incremental()` with a `where loaded_at > (select max(loaded_at) from {{ this }})` filter. Also check for unnecessary `CROSS JOIN` or missing `WHERE` clauses in staging models.

## Version History
- v1.0: Initial creation (auto-generated)
