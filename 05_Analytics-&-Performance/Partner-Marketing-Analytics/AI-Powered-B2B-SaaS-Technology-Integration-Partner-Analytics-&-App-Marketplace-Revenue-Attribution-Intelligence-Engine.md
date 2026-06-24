# AI-Powered B2B SaaS Technology Integration Partner Analytics & App Marketplace Revenue Attribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** b2b, saas, partner-analytics, integration-led-growth, ecosystem, revenue-attribution, martech

## Overview

This prompt builds a comprehensive analytics intelligence system that quantifies revenue, retention, and pipeline impact from technology integrations and app marketplace presence—turning your integration ecosystem into a measurable growth lever with AI-automated attribution, adoption scoring, and partner ROI reporting.

## Quick Copy-Paste Version

You are a B2B SaaS partner analytics expert. Analyze my technology integration partner program and app marketplace performance to surface revenue attribution insights.

My company: [Company name, product category]
Integration ecosystem: [List your top 5-10 integrations: e.g., HubSpot, Salesforce, Slack, Zapier]
Marketplace presence: [Which app marketplaces: e.g., HubSpot App Marketplace, Salesforce AppExchange, Microsoft Teams, Slack App Directory]
Data I have access to: [CRM data, product usage/event data, integration activation events, deal data]
Current tracking gaps: [What you can't currently measure]

Please deliver:

1. INTEGRATION-INFLUENCED REVENUE MODEL
   - Framework for calculating Integration-Qualified Leads (IQL) — define the criteria
   - Attribution logic: how to credit integrations for deals where integration was activated pre-close
   - Integration-influenced ARR vs. integration-sourced ARR definitions and calculation methodology
   - Recommended lookback window for integration → deal correlation

2. APP MARKETPLACE FUNNEL ANALYTICS
   - Marketplace listing → install → activation → expansion funnel with conversion benchmarks
   - ICP-fit scoring for marketplace-sourced installs (signals that predict enterprise conversion)
   - Marketplace keyword and listing optimization opportunities
   - Partner co-sell activation rate from marketplace installs

3. INTEGRATION ADOPTION & RETENTION CORRELATION
   - Integration depth scoring: shallow (installed, unused) vs. deep (daily active API calls)
   - Correlation framework: integration depth → NRR, churn probability, expansion likelihood
   - Churn risk signal: accounts with declining integration usage = early warning flag
   - Ideal integration adoption milestone for expansion revenue unlock

4. PARTNER ECOSYSTEM REVENUE WATERFALL
   - Partner-influenced pipeline by integration partner (tier 1/2/3 segmentation)
   - Joint go-to-market ROI by partner: co-marketing spend vs. partner-attributed ARR
   - ISV partner ranking model: which integrations drive the most strategic value
   - Integration sunset/sunset analysis: which integrations to invest in vs. deprioritize

5. EXECUTIVE DASHBOARD FRAMEWORK
   - 5 KPIs for weekly integration partner revenue reporting
   - Board-ready narrative: integration ecosystem as competitive moat and NRR driver
   - QBR metrics for each Tier 1 integration partner

Format each section with specific SQL query logic hints, data model requirements, and the exact metrics your RevOps team should instrument in your data warehouse.

## Advanced Customizable Version

ROLE: You are a senior Revenue Operations analyst and ecosystem growth strategist at a B2B SaaS company with 10+ years of experience measuring integration-led and partner ecosystem-led revenue. You combine data engineering precision with commercial storytelling to help CMOs prove integration ROI to boards.

COMPANY CONTEXT:
- Company: [Company name]
- ARR: [$X ARR, growth rate]
- Product category: [e.g., Marketing Automation, Sales Engagement, HR Tech]
- Sales motion: [PLG / Sales-led / Hybrid]
- Integration strategy: [API-first / native integrations / iPaaS connectors / App marketplace listings]
- Integration volume: [Number of live integrations, top 10 by activation count]
- Marketplaces listed on: [e.g., HubSpot App Marketplace, Salesforce AppExchange, Microsoft Teams Store, Slack App Directory, Zapier, Make/Integromat, AWS Marketplace, Google Workspace Marketplace]
- Current data stack: [e.g., Salesforce CRM, Segment CDP, Snowflake/BigQuery, dbt, Looker/Tableau]
- RevOps maturity: [Basic / Intermediate / Advanced]

PRIMARY OBJECTIVE:
Build a complete Integration Partner Revenue Attribution Intelligence System that:
1. Attributes revenue accurately to integration partners and marketplace presence
2. Scores integration health at the account level to predict expansion/churn
3. Provides partner-specific ROI to justify engineering investment and co-marketing spend
4. Automates weekly and quarterly partner analytics reporting for executive audiences

DELIVERABLE 1: INTEGRATION REVENUE ATTRIBUTION ARCHITECTURE

A. Integration-Qualified Lead (IQL) Framework
Define IQL criteria using this structure:
- Trigger: Account installs integration X within [30/60/90] days of [trial start / demo booked / contract signed]
- Signal strength scoring (1-10): Integration activation recency + frequency + depth of API usage
- IQL threshold: Score ≥ [X] qualifies as integration-influenced
- Funnel stages: Integration Install → Activation → Power User → Expansion Trigger

B. Attribution Model Design
Choose the right attribution model for your motion:
- For PLG: Last-touch integration attribution (integration → PQL upgrade)
- For Sales-led: W-shaped or time-decay across: (1) marketplace install, (2) integration activation, (3) sales discovery call
- For Hybrid: U-shaped model weighting integration activation at top and deal close
- Multi-partner attribution: When account has 3+ integrations active, use proportional credit model

Output: Attribution SQL logic template with these fields:
- account_id, integration_name, activation_date, integration_depth_score, deal_id, deal_close_date, arr_value, attribution_credit_pct

C. Integration-Influenced vs. Integration-Sourced ARR
- Integration-sourced: Deal closed where marketplace install was the first touch
- Integration-influenced: Deal closed where integration was activated before close (any touch)
- Partner co-sell: Deal where integration partner's sales team was involved
Provide quarterly roll-up reporting template.

DELIVERABLE 2: APP MARKETPLACE CONVERSION FUNNEL

For each marketplace ([list your top 3]):

A. Full Funnel Metrics
- Listing page impressions → clicks (listing CTR benchmark: 2-5% for B2B SaaS)
- Clicks → installs (install conversion benchmark: 15-30%)
- Installs → activated accounts (activation benchmark: 40-60% within 7 days)
- Activated accounts → ICP-qualified leads (ICP benchmark: 20-35% of activations)
- ICP leads → pipeline created (pipeline conversion: 10-20%)
- Pipeline → closed won (marketplace-sourced win rate benchmark: 25-40%)

B. Marketplace Listing SEO & Discovery Optimization
Using AI analysis of marketplace search behavior:
- Target keywords by category, use case, and competitor comparison terms
- Review mining: Extract most mentioned use cases from 1-5 star reviews to inform listing copy
- Screenshot/demo video optimization for install conversion lift
- Integration category positioning: where you rank vs. competitors on "most installed" lists

C. ICP Scoring for Marketplace Installs
Score each marketplace install 1-100 using:
- Firmographic fit: Company size, industry, tech stack match
- Behavioral fit: Activation depth within 48 hours, API call volume in week 1
- Engagement fit: Did they book a demo, engage with onboarding emails?
Threshold: Score ≥ 65 = route to Sales as IQL; Score < 65 = PLG nurture track

DELIVERABLE 3: INTEGRATION DEPTH & HEALTH SCORING

A. Integration Depth Scoring Model (per account, per integration)
Score 1-10 using:
- Level 1 (1-3): Integration installed, zero or <10 API calls/month
- Level 2 (4-6): Regular API calls, 1-2 use cases active
- Level 3 (7-9): Daily active use, 3+ use cases, bidirectional data sync
- Level 4 (10): Power user, custom workflows, API calls in top 10% of cohort

B. Integration Health → Revenue Correlation
Run cohort analysis answering:
- "Accounts with Integration Depth ≥ 7 have ___% lower churn rate than depth ≤ 3"
- "Accounts that activate [Integration X] within 30 days of onboarding have ___% higher 12-month NRR"
- "Accounts with 3+ active integrations have ___x higher ACV expansion rate"

Provide the correlation analysis framework as a dbt model structure:
int_integration_health_scores → fct_account_integration_health → mart_integration_churn_correlation

C. Early Warning: Integration Usage Decline Signals
Alert triggers (automate in your data warehouse):
- Alert 1: Integration API calls drop >50% week-over-week → CS alert within 24 hours
- Alert 2: Account deactivates integration → trigger 72-hour win-back sequence
- Alert 3: Integration health score drops from ≥7 to ≤4 → route to dedicated CSM

DELIVERABLE 4: PARTNER ECOSYSTEM REVENUE WATERFALL

A. Integration Partner Tier System
Tier 1 (Strategic Partners): [Top 3-5 partners by pipeline influence]
- Criteria: >$X integration-influenced ARR/quarter, active co-sell motions, joint roadmap
- Metrics: Co-sell win rate, joint pipeline, integration-activated account retention

Tier 2 (Growth Partners): [Next 5-10 by activation volume]
- Criteria: >100 active accounts using integration, growing activation trend
- Metrics: Integration install growth rate, account health score average

Tier 3 (Ecosystem Partners): [All others in marketplace]
- Criteria: Listed, minimal co-marketing investment
- Metrics: Install volume, activation rate

B. Partner ROI Calculation Template (per Tier 1 partner)
Partner: [Name]
Engineering investment in integration: [$X/year]
Co-marketing MDF spend: [$Y/quarter]
Partner-influenced ARR (trailing 12 months): [$Z]
Partner-sourced ARR (trailing 12 months): [$A]
Partner-influenced deals (count): [N]
Average ACV of partner-influenced deals vs. non-influenced: [$B vs. $C]
NRR of integration users vs. non-users: [X% vs. Y%]

Partner ROI Calculation:
= (Partner-influenced ARR × NRR uplift factor) / (Engineering cost + Co-marketing spend)
Benchmark: Tier 1 partners should show >5x ROI on total investment

C. Integration Investment Prioritization Matrix
Score each integration 1-100 across:
- Revenue Impact (40%): Integration-influenced ARR, deal acceleration
- Strategic Value (25%): Partner co-sell support, joint marketing, roadmap alignment
- Adoption Health (20%): Activation rate, depth score distribution, usage growth
- Competitive Moat (15%): Exclusive integration, competitor switching friction

Output: Integration investment prioritization rank order with Go/Grow/Sunset recommendation.

DELIVERABLE 5: EXECUTIVE REPORTING AUTOMATION

A. Weekly Integration Partner Revenue Flash (automated, 1-page)
- Total integration-influenced pipeline: Week-over-week trend
- Top 5 integrations by new activations this week
- IQL volume by marketplace: This week vs. last 4-week average
- Integration health score distribution: % of base at depth 7+
- Top 3 accounts with declining integration health (CS alert list)

B. Quarterly Partner Analytics QBR Package
For each Tier 1 partner, include:
1. Integration-influenced ARR: This quarter vs. last quarter vs. same quarter last year
2. New accounts activated this quarter
3. Integration depth score: Average and distribution
4. Win rate comparison: Deals with integration active vs. without (%)
5. NRR comparison: Integration power users vs. non-users
6. Co-marketing campaign performance: Spend vs. pipeline generated
7. 90-day joint pipeline forecast
8. Partner investment recommendation: Increase / Maintain / Reduce

C. Board Narrative Template
Frame integration ecosystem as competitive moat:
"Our [X] active integrations connect [Product Name] into the daily workflows of [Y]% of our enterprise customers. Integration-active accounts show [A]% higher NRR and [B]% lower churn than the base, contributing [C]% of our total ARR growth. Our [Top 3 Partners] co-sell motion generated $[X]M in partner-influenced pipeline this quarter."

CONSTRAINTS:
- All metrics must be calculable from CRM + product usage data (no manual surveys)
- Attribution logic must be agreed-upon by Marketing, Sales, and CS leadership
- Every metric should have a clear owner, a defined calculation, and a data source
- Report automation should require <2 hours/week to maintain once built
- Partner ROI must be defensible to both CFO (cost justification) and CPO (roadmap prioritization)

OUTPUT FORMAT:
For each deliverable, provide:
1. The metric/framework definition with calculation formula
2. The data model structure (which tables, which joins)
3. The visualization recommendation (chart type, axes, benchmarks)
4. The business narrative to present to executives
5. The AI agent automation opportunity (what can be automated vs. requires human judgment)

## Example Input/Output

**Input Example:**

Company: Propel HQ (fictional), a B2B SaaS project management platform for marketing agencies
ARR: $18M, growing 45% YoY
Top integrations: HubSpot, Salesforce, Slack, Google Workspace, Asana, ClickUp, Zapier
Marketplace presence: HubSpot App Marketplace (#3 in "Project Management" category), Slack App Directory
Sales motion: PLG with sales-assist for deals >$25K ACV
Data stack: HubSpot CRM, Segment, Snowflake, Looker

**Output Example:**

**Integration Revenue Attribution Summary:**

*IQL Framework for Propel HQ:*
- IQL Trigger: Account installs HubSpot or Salesforce integration AND makes >50 API calls within 14 days of install
- IQL Score ≥ 70: Route to SDR within 24 hours
- IQL Score 50-69: Enter 21-day integration-focused nurture sequence
- Result: 340 IQLs identified last quarter; 28% converted to pipeline (vs. 11% for non-IQLs)

*Integration-Influenced ARR (Last 12 Months):*
- HubSpot integration-influenced: $3.2M ARR (18% of total ARR)
- Salesforce integration-influenced: $1.8M ARR (10% of total ARR)
- Slack integration-influenced: $890K ARR (5% of total ARR)
- Combined integration-influenced ARR: $5.9M (33% of total)

*Integration Health → Retention Correlation:*
- Depth Score ≥ 7 accounts: 94% gross revenue retention
- Depth Score 4-6 accounts: 81% gross revenue retention
- Depth Score ≤ 3 accounts: 67% gross revenue retention
- **Insight: Moving an account from depth 4 to 7 is worth ~13 pts of GRR — prioritize integration onboarding campaigns**

*HubSpot Marketplace Funnel (Last Quarter):*
- Listing impressions: 12,400 → Installs: 287 (2.3% CTR)
- Installs → Activated (>50 API calls/7 days): 162 (56% activation rate)
- Activated → ICP qualified: 54 (33% ICP fit)
- ICP leads → Pipeline: $1.4M
- Pipeline → Closed won: $380K (27% win rate)
- **Marketplace CAC: $31 vs. average CAC of $1,240 — marketplace is the most efficient acquisition channel**

## Success Metrics

- Integration-influenced ARR is calculated and agreed-upon across Marketing, Sales, and CS within 30 days
- Weekly integration partner flash report is automated and distributed in <30 minutes of prep
- At least one Tier 1 partner has a formal co-sell motion with joint pipeline targets within 60 days
- Integration depth scoring is live in CRM with CS health alerts firing within 72 hours of score decline
- Board presentation includes integration ecosystem as a measurable competitive moat narrative
- Integration investment prioritization matrix is used in quarterly engineering roadmap discussions

## Related Prompts

- [Channel Partner Performance Analytics](../../05_Analytics-&-Performance/Partner-Marketing-Analytics/AI-Powered-B2B-SaaS-Partner-Ecosystem-Revenue-Analytics-&-Channel-Partner-Attribution-Intelligence-Engine.md)
- [Co-Marketing Campaign ROI Analytics](../../05_Analytics-&-Performance/Partner-Marketing-Analytics/AI-Powered-B2B-SaaS-Co-Marketing-Campaign-ROI-Analytics-&-Joint-Demand-Generation-Intelligence-Engine.md)
- [CAC Payback & Unit Economics](../../05_Analytics-&-Performance/CAC-Payback-&-Unit-Economics-Analytics/CAC-Payback-&-Unit-Economics-Intelligence-Engine.md)
- [Customer Lifetime Value Analytics](../../05_Analytics-&-Performance/Customer-Lifetime-Value-Analytics/Customer-Lifetime-Value-Prediction-&-Acquisition-Investment-Intelligence-Engine.md)

## Integration Tips

- **Snowflake/BigQuery**: Build `fct_integration_activations`, `int_integration_health_scores`, and `mart_partner_revenue_attribution` tables as the analytics foundation; run dbt transformations nightly
- **HubSpot/Salesforce**: Create a custom "Integration Health Score" field on the Account object, synced daily from your data warehouse via Reverse ETL (Census, Hightouch)
- **Segment/Amplitude**: Use integration activation events (`integration_connected`, `integration_first_api_call`, `integration_daily_active`) as the raw event source for depth scoring
- **Looker/Tableau**: Build a Partner Analytics dashboard with account-level drilldowns, weekly trend charts, and Tier 1 partner scorecards — share with both internal RevOps and external partner stakeholders
- **Slack**: Automate the weekly integration flash report as a Slack digest to the #revenue-analytics channel every Monday morning at 8am
- **Salesforce**: Tag deals with `Integration_Influenced__c = TRUE` and `Integration_Partner__c = [Partner Name]` to enable pipeline reporting without rebuilding your CRM attribution model

## Troubleshooting

**Problem:** Integration activation data exists in your product database but not in CRM, so Sales can't see integration context during deals.
**Solution:** Use Reverse ETL (Census, Hightouch, or Segment Unify) to sync `integration_health_score` and `top_integrations_active` fields to the Account object in Salesforce/HubSpot. Run this sync nightly. Create a CRM view that shows open deals sorted by integration health score — Sales will immediately see which accounts are deeply integrated vs. not.

**Problem:** Engineering team disputes the integration investment ROI calculation because "you can't prove causation."
**Solution:** Run a propensity-matched cohort analysis: match integration users to non-users with identical firmographic and behavioral profiles, then compare 12-month retention and expansion rates. Even correlational evidence is powerful when the delta is large (e.g., 94% GRR vs. 67% GRR). Present as "integration correlation" not "integration causation" — CFOs accept correlation-based ROI in competitive intelligence contexts.

**Problem:** Multiple integration partners want credit for the same deal (multi-partner attribution conflict).
**Solution:** Implement a proportional credit model: if HubSpot integration activated 90 days pre-close and Salesforce activated 14 days pre-close, assign credit by recency weight (60% HubSpot / 40% Salesforce). Document this in your "Partner Attribution Policy" and get written sign-off from your top 3 partners before they start tracking their numbers — avoids disputes at QBR time.

## Version History

- v1.0: Initial creation (auto-generated)
