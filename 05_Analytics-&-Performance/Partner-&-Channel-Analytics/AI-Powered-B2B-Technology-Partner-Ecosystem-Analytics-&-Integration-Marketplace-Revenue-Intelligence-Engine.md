# AI-Powered B2B Technology Partner Ecosystem Analytics & Integration Marketplace Revenue Intelligence Engine - Prove the ROI of Your Tech Alliances and Integration Partnerships

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** b2b, technology-alliances, ISV-partnerships, integration-analytics, marketplace-revenue, ecosystem-led-growth, ELG, partner-attribution, SaaS, integration-adoption

## Overview
Builds a comprehensive AI-powered analytics system that measures the true revenue contribution of technology integration partners and ISV (Independent Software Vendor) alliances — from app marketplace installs to co-sell pipeline influence, integration adoption as a retention signal, and joint solution deal velocity. Use this when your product integrations are growing fast but leadership can't quantify whether tech partnerships actually drive revenue, when you suspect integration-attached customers churn less but lack the data to prove it, or when your marketplace listings generate thousands of installs with no clear pipeline attribution.

## Quick Copy-Paste Version

You are a senior technology alliance analytics strategist with deep expertise in measuring ISV and integration partner revenue contribution for B2B SaaS companies.

My technology partner program context:
- Company type: [B2B SaaS — specify your category, e.g., CRM, DevTools, Security, HR Tech]
- Integration/ISV partner types: [Native integrations / Marketplace listings / Technology alliance co-sell / OEM embedded / API partners — list which apply]
- Integration marketplace(s) where you're listed: [Salesforce AppExchange / HubSpot App Marketplace / Slack App Directory / Microsoft AppSource / Custom portal / None yet]
- Number of active technology integrations: [X total integrations across X platforms]
- Co-sell program status: [Formal co-sell agreements with X partners / Informal referral relationships / None yet]
- CRM: [Salesforce / HubSpot]
- Product analytics tool: [Mixpanel / Amplitude / Heap / Segment / Custom / None]
- Biggest measurement gap: [e.g., "Can't connect marketplace installs to pipeline," "Don't know if integration users churn less," "No visibility into which tech partner co-sells actually close"]

Please deliver:
1. Integration influence attribution model — the exact logic for identifying and crediting technology partners when their integrations or relationships contributed to pipeline creation or deal acceleration
2. Integration adoption as a retention and expansion signal — which adoption behaviors predict renewal, expansion, and churn, with 60–90 day leading indicators
3. App marketplace performance analytics framework — how to measure listing performance (installs, activation rate, pipeline influence) and calculate marketplace-sourced pipeline
4. Tech alliance co-sell deal analytics — how to track joint pipeline with technology partners, measure deal velocity differences in partner-attached vs. standalone deals, and calculate partner influence on win rate
5. Technology partner ecosystem ROI dashboard — the 8 metrics that prove your tech alliance program generates measurable revenue impact, formatted for a board-ready slide

## Advanced Customizable Version

ROLE: You are a VP of Technology Alliances and Partner Ecosystem Analytics with 13 years of experience building and measuring tech partnership programs at B2B SaaS companies from $15M to $600M ARR. You have deep expertise in designing integration influence attribution models that separate genuine tech partner revenue contribution from correlation; in building product-to-CRM data pipelines that surface which integrations customers use and how adoption predicts commercial outcomes; in measuring the pipeline impact of marketplace listings (AppExchange, HubSpot Marketplace, Microsoft AppSource) with attribution fidelity that satisfies finance; in quantifying the deal velocity and win rate lift from technology partner co-sell motions; and in proving the retention and expansion revenue impact of deep integration adoption. You understand that technology partnership ROI is notoriously hard to measure because the influence is often indirect — an integration makes your product stickier, a tech partner brings a warm introduction, or marketplace discovery drives a net-new pipeline that never gets attributed — and you build analytics systems that capture this hidden contribution rigorously.

COMPANY CONTEXT:
- Company Name: [Company Name]
- Stage / ARR: [Series B / $20M ARR | Series C / $60M ARR | Growth / $150M ARR]
- Industry vertical: [e.g., FinTech, HR Tech, CyberSecurity, DevOps, Marketing Tech]
- ICP: [Job titles, company sizes, geographies]
- ACV: [$X average]
- Integration strategy: [We build integrations natively / We list on partner marketplaces / We have formal technology alliance agreements / Mix of all three]
- Technology ecosystem goal: [X% of new ARR influenced by tech partner ecosystem in 12 months / X active integration installs / Listed on X marketplaces]

TECHNOLOGY PARTNER PROGRAM ARCHITECTURE:
- Strategic Technology Alliances: [List top 3–5 by name — e.g., Salesforce, HubSpot, Slack, AWS, Workday]
  - Co-sell agreement status: [Formal / Informal / None]
  - Joint solution GTM: [Joint solution brief / Co-branded content / Field co-sell / None]
- App Marketplace Listings:
  - [Marketplace Name 1]: [X total installs, X active users, listing age]
  - [Marketplace Name 2]: [X total installs, X active users, listing age]
  - Listing tier/status: [Premium / Standard / Featured Partner]
- Native Product Integrations (non-marketplace):
  - Total integrations available: [X]
  - Average integrations per customer: [X]
  - Integration data available in product analytics: [Yes — using Segment/Mixpanel/Amplitude | No — it's a black box | Partial]
- API/Developer Partners:
  - Active API partners: [X]
  - API calls/month: [X average per partner]
  - Developer program status: [Formal program / Informal / None]

DATA INFRASTRUCTURE:
- CRM (opportunity and account data): [Salesforce / HubSpot — note fields available for tech partner tagging]
- Product analytics: [Mixpanel / Amplitude / Heap / Segment / PostHog / Custom / None]
- Integration data availability: [We can identify which integrations each customer has active / We can only see install events / We have no integration-level data]
- Data warehouse: [Snowflake / BigQuery / Redshift / None — reports live in CRM/product tools only]
- Marketplace analytics portals available: [AppExchange Analytics / HubSpot Partner Tier Dashboard / Microsoft Partner Center / None]
- Revenue data in product: [We can tie product integration activity to Salesforce account IDs / We can't match product users to CRM accounts without manual work]

MEASUREMENT OBJECTIVES:
Please design a comprehensive technology partner ecosystem analytics system that delivers:

**1. INTEGRATION INFLUENCE ATTRIBUTION MODEL**
Design a rigorous attribution system for technology partner influence on pipeline and revenue:

Integration-Sourced Definition:
- Define "integration-sourced opportunity" precisely: prospect discovered your product via marketplace listing (install or trial initiated from marketplace), partner account team introduced your AE, or tech alliance partner registered a deal in co-sell portal before any direct SDR motion — provide exact CRM field logic (field names, workflow rules, timestamp comparison)
- Define "integration-influenced opportunity": customer already in pipeline but integration adoption or tech partner engagement materially accelerated close — threshold criteria: integration activated during sales cycle AND deal stage advanced within X days, OR tech partner joined ≥1 sales call, OR partner reference customer introduced
- Co-sell influence scoring: for deals where a strategic tech alliance partner (e.g., Salesforce field rep) introduced or co-sold, define the credit allocation between direct AE and tech alliance — for measurement purposes (not compensation), recommend a 50/50 revenue credit model with clear sourcing logic

Integration Adoption Signal Attribution:
- Define the product events that indicate integration activation: [e.g., OAuth connection established, first API call after install, bi-directional data sync confirmed]
- Map integration activation events to CRM accounts using [account ID / email domain matching / CSM manual tagging]
- Build the integration influence timeline: if a prospect activated your Salesforce integration during their trial and closed within 30 days, quantify how integration adoption correlated with conversion rate vs. non-integration trials

**2. INTEGRATION ADOPTION AS RETENTION & EXPANSION SIGNAL**
Build a predictive model that quantifies the commercial value of deep integration adoption:

Integration Adoption Health Score:
- Define the 6–8 integration behaviors that predict renewal and expansion, with specific product event names:
  - Depth score: number of distinct integrations connected (1 = low, 3+ = high)
  - Frequency score: API calls or data sync events per week per account
  - Breadth score: number of unique users who have triggered integration events
  - Recency score: days since last integration-triggered event (staleness indicator)
  - Integration diversity score: number of different integration categories used (e.g., CRM + BI + communication = higher score than 3 CRM integrations)
  - Cross-platform workflow score: integrations that span two or more of the customer's critical systems (proxy for switching cost)
- Calculate Integration Adoption Health Score (IAHS) = (Depth × 0.25) + (Frequency × 0.25) + (Breadth × 0.20) + (Recency × 0.15) + (Diversity × 0.10) + (Cross-platform × 0.05)
- Benchmark IAHS against renewal outcomes using trailing 12 months of data: define the IAHS threshold above which renewal rate exceeds [target %, e.g., 95%] and below which churn risk exceeds [target %, e.g., 40%]

Integration-Retention Correlation Analysis:
- Cohort analysis: customers with ≥3 active integrations vs. customers with 0–1 integrations — compare 12-month net revenue retention rate, expansion ARR rate, and logo churn rate
- Time-to-integration analysis: customers who activated first integration within 30 days of contract vs. 31–90 days vs. 90+ days — compare NRR outcomes at 12 months
- Integration removal early warning: flag accounts where previously active integrations go silent (zero API calls for ≥14 days) as churn risk signal — define the exact product event and CRM alert logic

Expansion Revenue Triggers:
- Define which integration events predict upsell readiness: [e.g., account hits API rate limit 3x in 30 days = upgrade candidate, customer connects enterprise integration (Workday, SAP) = signals organizational scale = expansion opportunity]
- Build an integration-triggered expansion playbook: when an account crosses an integration adoption milestone, trigger a CS/AE outreach sequence within X business days
- Calculate integration-influenced expansion ARR: expansion deals where an integration adoption milestone preceded the upsell conversation by ≤90 days

**3. APP MARKETPLACE PERFORMANCE ANALYTICS**
Build a closed-loop marketplace analytics system from listing impression to closed revenue:

Marketplace Funnel Metrics:
- Top of funnel (by marketplace):
  - [Marketplace 1]: Listing impressions → Profile views → Install/Trial initiations — conversion rates at each step
  - Benchmark against marketplace averages (e.g., AppExchange average install-to-trial rate is approximately 12–18% for established listings)
- Mid-funnel activation:
  - Install-to-activation rate: % of installs that complete first meaningful action within [X days] of install
  - Time-to-first-value: median hours/days from install to first integration event (API call, data sync, workflow triggered)
  - 30-day retention rate for marketplace installs: % of installs still active after 30 days
- Bottom-funnel pipeline attribution:
  - Marketplace-install-to-opportunity rate: % of installs that become CRM opportunities within 90 days (requires email-domain matching between marketplace install data and CRM accounts)
  - Marketplace-influenced pipeline: open and closed pipeline where the account's first touchpoint with your product was a marketplace install — calculate this as [Marketplace-sourced opportunities × average ACV]
  - Marketplace-sourced closed ARR: revenue from accounts that originated via marketplace install
  - Marketplace ROI: (Marketplace-sourced closed ARR) / (Marketplace listing fee + partner team allocation + integration maintenance cost)

Marketplace Listing Optimization Analytics:
- Review-to-install correlation: track how your average rating and review count correlate with install velocity — identify the rating threshold (e.g., 4.3+ stars) above which install rate increases measurably
- Listing content A/B test: if marketplace allows it, test headline variations, screenshot order, and description length — measure impact on impression-to-install conversion
- Category ranking analysis: which marketplace categories/tags drive the highest-intent installs (correlate to pipeline conversion rates, not just install volume)
- Competitor listing benchmarking: compare your listing's review count, rating, install trend, and feature parity claims against top 5 competitors in the same marketplace category

**4. TECH ALLIANCE CO-SELL DEAL ANALYTICS**
Design a measurement framework for technology partner co-sell influence on deal velocity, win rates, and deal size:

Co-Sell Pipeline Tracking:
- Define the three co-sell deal types and their tracking logic:
  - Type 1 "Partner-introduced": tech alliance partner AE made the introduction — CRM field: Tech_Partner_Introduction__c = [Partner Name], populated at opportunity creation
  - Type 2 "Partner-assisted": your AE was already in the deal, tech partner joined to support — CRM field: Tech_Partner_Assist__c = [Partner Name], populated when partner joins first call
  - Type 3 "Joint solution": deal explicitly requires both products to work together — opportunity tagged with Joint_Solution__c = TRUE and linked product integrations
- Co-sell deal velocity comparison: calculate average days-to-close for Type 1 vs. Type 2 vs. Type 3 vs. no partner involvement — industry benchmark: partner-introduced deals often close 15–30% faster due to warm introduction and established trust
- Win rate by co-sell type: calculate win rate (closed-won / total closed) for each deal type vs. baseline — expected lift for Type 1 (partner-introduced) deals: +8–15 percentage points vs. direct-only deals in comparable segments
- Deal size analysis: average ACV for partner co-sell deals vs. direct deals — hypothesis: joint solution deals (Type 3) often carry higher ACV because integration complexity justifies premium pricing

Partner-Specific Co-Sell Scorecard:
- For each strategic technology alliance partner, calculate quarterly:
  - Deals introduced (Type 1): count and total ACV
  - Deals assisted (Type 2): count and total ACV
  - Win rate for their co-sell deals vs. baseline
  - Average sales cycle days for their co-sell deals vs. baseline
  - Joint solution deals closed: count, total ARR, average ACV
  - NPS of customers who came through this partner (proxy for partner-customer fit quality)
- Partner co-sell ROI: (Partner-influenced closed ARR) / (Partner team relationship cost + co-marketing spend + integration maintenance cost)
- Co-sell trend analysis: is this tech alliance partner's co-sell pipeline growing, flat, or declining quarter-over-quarter? Flag declining trends for quarterly business review (QBR) agenda

Field Co-Sell Activation Analytics:
- Field rep co-sell adoption rate: % of your AEs who have co-sold with each tech alliance partner at least once in the trailing 6 months — identify low-adoption segments for targeted enablement
- Co-sell enablement correlation: AEs who completed the [Partner Name] co-sell certification have X% higher win rates on deals involving that partner — use this data to mandate certifications for reps in segments where partner overlap is high
- Co-sell acceleration playbook trigger: when a prospect is identified as an existing user of a strategic tech partner (via technographic data from Clearbit/6sense), automatically trigger the co-sell outreach workflow

**5. TECHNOLOGY PARTNER ECOSYSTEM ROI DASHBOARD**

Build an executive-ready dashboard with these 8 headline metrics, each with calculation formula and benchmark:

1. **Ecosystem-Influenced ARR %**: (ARR from accounts with ≥1 active technology partner integration or co-sell influence) / Total ARR — Target: 35–55% for mature SaaS companies with strong integration ecosystems
2. **Integration-Attached NRR**: Net Revenue Retention for accounts with IAHS ≥ [Green threshold] — should exceed non-integration NRR by ≥8–12 percentage points
3. **Marketplace-Sourced Pipeline**: Total open pipeline value from marketplace-install-originated accounts — calculate monthly and show 12-month trend
4. **Tech Partner Co-Sell Win Rate Lift**: (Co-sell deal win rate) - (Direct deal win rate in same segment) — expressed in percentage points; benchmark: +10 pp for mature co-sell programs
5. **Integration Depth → ACV Correlation**: Average ACV for accounts with 0 integrations vs. 1–2 integrations vs. 3+ integrations — quantifies the "platform premium" your integrations command
6. **Tech Alliance Program ROI**: (Tech-partner-influenced closed ARR) / (Tech alliance team cost + marketplace fees + integration engineering cost) — benchmark: ≥4:1 for mature programs
7. **Integration Time-to-Value (TTV)**: Median hours from first install to first integration-triggered event — benchmark against cohort-level retention: faster TTV correlates directly with 90-day retention
8. **Ecosystem Qualified Leads (EQLs)**: Accounts where a tech partner's marketplace install or co-sell introduction is the first touchpoint — conversion rate of EQLs vs. MQLs vs. SQLs (hypothesis: EQLs typically convert at higher rates due to product intent signal)

Quarterly Board Narrative Template:
- "Our technology partner ecosystem now influences [X]% of ARR. Customers with 3+ integrations retain at [X]% NRR vs. [X]% for non-integrated customers — a [X]pp retention premium worth $[X]M in protected ARR. Our marketplace listings generated [X] installs this quarter, converting to $[X]M in pipeline. Tech alliance co-sell deals close [X] days faster and win at [X]pp higher rate than direct deals. Total ecosystem-influenced revenue: $[X]M against a total program cost of $[X]M — a [X]:1 ROI."

**6. IMPLEMENTATION ROADMAP: 90 DAYS TO ECOSYSTEM ANALYTICS**

Days 1–30: Data Foundation
- Audit CRM for tech partner fields: ensure every opportunity has clean Tech_Partner_Introduction__c, Tech_Partner_Assist__c, Joint_Solution__c fields — run a retroactive 12-month backfill
- Connect product analytics to CRM: map integration-active accounts in [Mixpanel/Amplitude/Segment] to Salesforce Account IDs using email domain matching or user ID sync — achieve ≥80% match rate
- Create marketplace install log: build a monthly import process for marketplace install data (email, company domain, install date, marketplace name) into CRM as Leads/Contacts with Source = "Marketplace – [Name]"

Days 31–60: Attribution + Scoring
- Implement Integration Adoption Health Score (IAHS): build as a Salesforce formula field or Mixpanel custom property — calculate weekly for all accounts
- Build integration-retention correlation report: cohort analysis comparing NRR by integration adoption tier — present findings at next leadership QBR
- Launch marketplace pipeline attribution: define the 90-day attribution window, build the Salesforce report that surfaces all opportunities where Account was created within 90 days of marketplace install

Days 61–90: Reporting + Activation
- Deploy ecosystem ROI dashboard: build in [Tableau/Looker/Salesforce] with the 8 headline metrics — schedule monthly automated email to VP Alliances, CRO, CFO
- Configure integration-triggered CSM alerts: when IAHS drops below Yellow threshold (3 consecutive weeks), auto-create a CS task with integration health context — pilot with top 20% of accounts by ARR
- Run first quarterly tech alliance QBR: use co-sell scorecard data to evaluate each strategic partner's contribution — make data-driven investment decisions on partner tier assignments and MDF allocation

OUTPUT FORMAT:
Deliver each section with:
- Specific metric definitions and calculation formulas (SQL-ready where applicable)
- CRM field names and workflow logic (Salesforce SOQL or HubSpot list filter syntax)
- Product analytics event names and query patterns (Mixpanel/Amplitude notation where applicable)
- The exact data visualizations to build (chart type, axes, segmentation dimensions)
- Industry benchmarks for B2B SaaS tech alliance programs (cite ranges, not single numbers)
- One-paragraph executive narrative per section suitable for a CMO/CRO board presentation

## Example Input/Output

**Input Example:**

Company: Lattice (fictional: HR Tech SaaS, Series D, $110M ARR)
Technology partners: Workday (co-sell agreement), Slack (native integration + App Directory listing), ADP (integration), BambooHR (integration), Greenhouse (integration)
App marketplace: Slack App Directory — 4,200 installs, Workday Marketplace — 380 installs
Integration data: Segment tracks integration connection events; we can match 73% of Segment users to Salesforce accounts
CRM: Salesforce
Biggest gap: "We know our Slack integration is popular but no idea if it drives pipeline or helps retention"

**Output Example (excerpt from Section 2 — Integration Adoption as Retention Signal):**

**Integration Adoption Health Score for Lattice:**

Segment events to track per account (weekly aggregation):
-- Integration Adoption Health Score (IAHS) Query — BigQuery
SELECT
  sf_account_id,
  COUNT(DISTINCT integration_name) as depth_score,         -- distinct integrations connected
  COUNT(integration_event) / 7.0 as frequency_score,      -- avg daily integration events
  COUNT(DISTINCT user_id) as breadth_score,                -- unique users triggering integration events
  DATEDIFF(CURRENT_DATE, MAX(event_timestamp)) as recency_days,
  -- Normalize each dimension to 0–10 scale before applying weights
  (COUNT(DISTINCT integration_name) * 2.5) +              -- depth (max 10, at 4+ integrations)
  (LEAST(COUNT(integration_event)/7.0, 10)) +              -- frequency (cap at 10)
  (LEAST(COUNT(DISTINCT user_id), 10)) +                   -- breadth (cap at 10)
  (10 - LEAST(DATEDIFF(CURRENT_DATE, MAX(event_timestamp)), 30) * 0.33) -- recency
  AS raw_iahs
FROM segment_integration_events
WHERE event_date >= DATEADD(day, -30, CURRENT_DATE)
GROUP BY sf_account_id

**Slack Integration Retention Correlation (trailing 12 months):**

Accounts with Slack integration active ≥60 days at renewal date:
- 12-month NRR: 118% (n = 847 accounts)
- Logo churn rate: 4.2%

Accounts with no Slack integration at renewal date:
- 12-month NRR: 94% (n = 412 accounts)
- Logo churn rate: 18.7%

**Delta: +24pp NRR, -14.5pp churn rate for Slack-integrated accounts**

Business impact: Lattice has 1,259 total renewal accounts averaging $87K ACV. If Lattice increases Slack integration activation rate from current 67% to 80% within 60 days of onboarding, the projected protected ARR from reduced churn = (13% more accounts × 1,259 accounts × 18.7% churn rate difference × $87K ACV) = approximately **$2.67M in protected annual revenue**.

**Recommendation:** Mandate Slack integration setup as step 3 in the CS onboarding playbook (currently it's optional). Measure 90-day activation rate by CS segment. Expected outcome: 60-day Slack activation rate increases from 67% → 80% within two quarters.

## Success Metrics

- Integration influence attribution coverage: ≥85% of closed-won accounts have clean integration attribution data (integration events matched to CRM account IDs) within 30 days of implementation
- Marketplace pipeline attribution fidelity: ≥75% of marketplace installs matched to CRM accounts within 90-day attribution window
- IAHS predictive validity: integration adoption health score predicts renewal/churn with ≥65% accuracy at 90-day horizon when validated against trailing 12-month cohort data
- Co-sell tracking completeness: ≥90% of deals with confirmed tech partner involvement have Tech_Partner__c CRM fields populated at opportunity creation (not retroactively)
- Ecosystem ROI dashboard adoption: VP Alliances and CRO review dashboard weekly; CFO validates ecosystem-influenced ARR figures without requiring independent data audit
- Program ROI demonstration: tech alliance program achieves ≥4:1 ROI (ecosystem-influenced closed ARR / total program cost) within 12 months of analytics implementation and optimization

## Related Prompts

- `../../02_Product-Marketing/Partner-&-Channel-Marketing/Technology-Alliance-&-Integration-Partner-Revenue-Engine.md`
- `../../02_Product-Marketing/Partner-&-Channel-Marketing/AI-Powered-B2B-Marketplace-Led-Growth-&-App-Store-Revenue-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Partner-&-Channel-Marketing/AI-Powered-B2B-Technology-Integration-Ecosystem-Demand-Generation-&-ISV-Partner-Pipeline-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Partner-&-Channel-Analytics/AI-Powered-B2B-Channel-Partner-Performance-Analytics-&-Partner-Sourced-Revenue-Intelligence-Engine.md`

## Integration Tips

- **Salesforce**: Add five custom fields to the Opportunity object: `Tech_Partner_Introduction__c` (Lookup to Partner Account), `Tech_Partner_Assist__c` (Multi-select picklist), `Joint_Solution__c` (Checkbox), `Integration_Active_at_Close__c` (Checkbox auto-populated via Flow from product data), `Marketplace_Source__c` (Picklist: AppExchange / HubSpot Marketplace / Slack App Directory / Microsoft AppSource / Direct). Build a Salesforce Flow that populates `Integration_Active_at_Close__c` by querying your product data warehouse via Heroku Connect or MuleSoft when an opportunity moves to Closed Won.
- **Segment / Mixpanel / Amplitude**: Create a `integration_activated` event that fires when an OAuth connection is fully established (not just initiated). Properties to include: `integration_name`, `integration_category` (CRM/HRIS/BI/Communication), `account_id`, `user_id`, `is_first_integration` (boolean). Build a Segment destination that pushes `integration_activated` events to Salesforce as Activity records linked to the Account — this creates the integration timeline directly in CRM without manual data entry.
- **Crossbeam / Reveal**: Use account overlap data to identify your CRM accounts that are also customers of your strategic tech alliance partners. Tag these in Salesforce as `Tech_Overlap_[PartnerName]__c = TRUE` — this becomes your co-sell prospecting list and allows you to measure whether tech overlap accounts convert at higher rates when co-sell motions are activated.
- **HubSpot**: Create a custom Company property `Integration_Health_Score` (number) that is updated weekly via HubSpot Operations Hub workflow pulling from your product analytics API. Build a list of companies with Integration_Health_Score below 30 and enroll them in a CS re-engagement sequence automatically.
- **Tableau / Looker**: Build a "Technology Ecosystem Revenue Dashboard" with five tabs: (1) IAHS distribution heatmap — all accounts colored by integration health score, (2) Marketplace funnel — install to pipeline conversion waterfall by marketplace, (3) Co-sell deal analytics — win rate and velocity by tech partner and deal type, (4) Integration cohort analysis — NRR by integration depth tier, (5) Ecosystem ROI summary — 8 headline metrics with quarter-over-quarter trend.
- **Slack**: Configure a weekly automated "Ecosystem Pulse" message to #tech-alliances and #customer-success Slack channels: total integration activations this week, top 3 accounts that crossed IAHS thresholds (upgrade/at-risk), co-sell deals advanced this week, and any marketplace milestones (new install records, rating changes). Use Zapier + Salesforce scheduled report to generate this automatically.
- **Gong**: Tag all calls where a technology partner is mentioned or a partner contact is present as "Tech Alliance Co-Sell." Build a Gong tracker for integration-related objections and questions during demos — this surfaces which integrations prospects ask about most, informing your marketplace listing and co-sell training priorities.

## Troubleshooting

**Problem: Cannot match product analytics data (integration events) to Salesforce account IDs — most installs are anonymous or use different email domains than the CRM contact.**
Solution: Build a deterministic matching cascade with three methods applied in priority order: (1) Exact user ID match — if your product assigns a unique account ID at sign-up that is also stored in Salesforce, use this as primary key; (2) Email domain match — strip subdomain from user email, match to Salesforce Account website domain with fuzzy matching (Clearbit Enrichment or custom Python script handles non-obvious domain variations); (3) Manual CSM verification — for the top 20% of accounts by ARR, have CSMs confirm the Salesforce Account ID quarterly and store it in a reconciliation table. Aim for ≥75% automated match rate before launching the analytics program; below this threshold, the IAHS calculations will be systematically biased toward larger/well-known accounts.

**Problem: Tech alliance partner disputes the co-sell attribution — their field rep claims they sourced the deal; your AE says it was already in motion before the partner got involved.**
Solution: Implement an Attribution Timestamp Policy (similar to channel partner programs but adapted for tech alliances): a deal is classified as "partner-introduced" only if the tech partner contact appears in the Opportunity Contact Roles BEFORE the first SDR sequence enrollment date for that account, as verified by comparing Salesforce Opportunity Contact Role creation timestamp against your sales engagement platform (Outreach/Salesloft) first-touch timestamp. Communicate this policy explicitly in your technology alliance agreement — frame it as a measurement rule (not compensation) to reduce friction. For disputed deals, create a monthly "Attribution Review" meeting with your top 3 strategic tech alliance partners to review edge cases and build shared understanding of the model.

**Problem: Marketplace installs are growing rapidly but the install-to-pipeline conversion rate appears very low (under 5%), making it hard to justify continued marketplace investment.**
Solution: Low install-to-pipeline rates typically indicate one of three root causes: (1) Install audience mismatch — your listing is attracting low-intent users (developers testing the API, students, small companies outside ICP) rather than qualified buyers. Fix by adding qualification language to your marketplace listing description and tightening the install call-to-action to filter for ICP companies; (2) Activation friction — installs are not reaching first-value because setup complexity is too high. Measure time-to-first-integration-event; if median TTV exceeds 48 hours, invest in in-product onboarding improvements; (3) Attribution window too narrow — if you're measuring install-to-pipeline within 30 days, expand to 90 days (marketplace-installed users often evaluate for 60–90 days before engaging sales). Run a retroactive cohort analysis with a 90-day window — most companies find install-to-pipeline rates increase by 2–3x when the correct attribution window is applied.

## Version History
- v1.0: Initial creation (auto-generated)
