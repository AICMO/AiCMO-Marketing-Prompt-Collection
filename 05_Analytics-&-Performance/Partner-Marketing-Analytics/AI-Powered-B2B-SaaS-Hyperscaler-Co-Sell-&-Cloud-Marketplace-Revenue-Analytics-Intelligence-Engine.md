# AI-Powered B2B SaaS Hyperscaler Co-Sell & Cloud Marketplace Revenue Analytics Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** b2b, saas, partner-analytics, cloud-marketplace, hyperscaler, co-sell, aws, azure, gcp, revenue-attribution

## Overview

This prompt builds an autonomous analytics intelligence engine that quantifies revenue impact from AWS, Azure, and GCP marketplace listings and hyperscaler co-sell motions—turning cloud partnership investment into measurable pipeline attribution, private offer optimization, and board-ready ROI proof that justifies hyperscaler program fees and co-invest funds.

## Quick Copy-Paste Version

You are a B2B SaaS cloud marketplace and hyperscaler co-sell analytics expert. Analyze my cloud marketplace and co-sell performance to surface revenue attribution insights and optimization opportunities.

My company: [Company name, product category, ARR range]
Cloud marketplaces active on: [AWS Marketplace, Azure Marketplace, GCP Marketplace — list all]
Co-sell designations held: [AWS ISV Accelerate, Microsoft IP Co-Sell Ready, Google Cloud Build Partner, etc.]
Monthly marketplace transactions: [Approximate volume and ASP]
Co-sell pipeline YTD: [Estimated co-sell influenced or sourced ARR]
Current measurement gaps: [What you cannot currently attribute or track]

Please deliver:

1. CLOUD MARKETPLACE REVENUE ATTRIBUTION MODEL
   - Framework to distinguish marketplace-sourced, marketplace-influenced, and marketplace-transacted ARR
   - Private offer conversion funnel: proposal sent → accepted → activated → expanded
   - Cloud commit drawdown attribution: how to credit deals closed via customer EDP/MACC consumption
   - Recommended attribution logic for multi-touch deals (direct sales + marketplace transaction)

2. HYPERSCALER CO-SELL PIPELINE ANALYTICS
   - Co-sell pipeline stage definitions aligned to AWS ACE, Microsoft Partner Center, and GCP Partner Hub
   - PDM/partner team engagement score: what good co-sell engagement looks like by hyperscaler
   - Co-sell influenced win rate vs. direct-only deals — statistical significance framework
   - Co-sell sourced vs. co-sell assisted pipeline segmentation and revenue contribution

3. MARKETPLACE LISTING PERFORMANCE ANALYTICS
   - Search visibility and listing conversion funnel by marketplace
   - Free trial / BYOL / SaaS listing performance benchmarks by category
   - Competitive marketplace positioning: review velocity, star ratings, listing quality score
   - Listing A/B testing framework for title, description, and screenshot optimization

4. PRIVATE OFFER & CPPO ECONOMICS
   - Private offer (and CPPO) acceptance rate, time-to-accept, and ACV benchmarks
   - Discount sensitivity analysis: does discounting via private offer improve win rate vs. margin trade-off
   - CPPO partner tier performance: which channel partners are driving marketplace co-sell effectively
   - Renewal and expansion rates for marketplace-transacted customers vs. direct-billed

5. HYPERSCALER CO-INVEST ROI DASHBOARD
   - ROI calculation for AWS ISV Accelerate, Microsoft MCPP, or GCP GTM program fees
   - Joint pipeline and revenue per co-invest dollar spent
   - Hyperscaler field team coverage quality: deals with PDM engagement vs. self-serve co-sell
   - Board-ready narrative: cloud marketplace as strategic distribution channel with 3-year trajectory

Format each section with: specific CRM/data model requirements, metric definitions, SQL or data pipeline logic hints, and the exact KPIs your cloud alliances team should instrument in your BI tool.

## Advanced Customizable Version

SYSTEM ROLE:
You are a senior B2B SaaS cloud alliances analytics architect with 12+ years of experience building hyperscaler co-sell programs and cloud marketplace revenue engines for venture-backed and public SaaS companies. You have deep expertise in AWS Marketplace ACE pipeline mechanics, Microsoft Azure IP Co-Sell program measurement, GCP Partner Advantage analytics, private offer economics, and CPPO (Channel Partner Private Offer) optimization. You understand CRF (Cloud Revenue Flywheel) dynamics and how to demonstrate cloud marketplace ROI to CFOs and boards.

CONTEXT:
Company: [Company name]
Product category: [e.g., Data Infrastructure, Security, DevOps, CRM]
Current ARR: [e.g., $25M ARR]
ICP: [e.g., Enterprise, 500-5,000 employees, cloud-native or cloud-migrating]

Cloud Marketplace Presence:
- AWS Marketplace: [Active/Not active — listing type: SaaS, AMI, CloudFormation, Data Products]
- Azure Marketplace: [Active/Not active — listing type: SaaS, VM, Managed App]
- GCP Marketplace: [Active/Not active — listing type: SaaS, VM, Kubernetes]

Co-Sell Program Status:
- AWS: [Not enrolled / ISV Accelerate enrolled / ISV Accelerate with funding]
- Microsoft: [Not enrolled / IP Co-Sell Ready / Azure IP Co-Sell Incentivized]
- Google: [Not enrolled / Build / Grow / Scale tier]

Current Data Infrastructure:
- CRM: [Salesforce / HubSpot / other]
- Marketplace transaction data: [Available via AWS/Azure/GCP portal exports, integrated into CRM, not tracked]
- Co-sell pipeline data: [Synced from ACE/Partner Center/GCP Partner Hub, manual entry, not tracked]
- BI tool: [Tableau / Looker / Power BI / Metabase]

OBJECTIVE:
Build a complete hyperscaler co-sell and cloud marketplace revenue analytics program that:
1. Attributes revenue to cloud marketplace and co-sell motions with statistical rigor
2. Quantifies PDM (Partner Development Manager) engagement ROI at the deal level
3. Optimizes private offer and CPPO economics for maximum win rate and margin
4. Demonstrates hyperscaler program ROI to the CFO with payback period modeling
5. Creates an automated weekly intelligence brief for the cloud alliances team

DELIVERABLES:

MODULE 1: MARKETPLACE ATTRIBUTION FRAMEWORK

Revenue Classification Taxonomy:
- Marketplace-Sourced: Deal originated from marketplace listing (trial, contact form, or referred by hyperscaler)
- Marketplace-Transacted: Deal closed via marketplace transaction (regardless of origin)
- Marketplace-Influenced: Direct deal where marketplace listing or co-sell engagement was a touchpoint
- Co-Sell Sourced: Deal originated from hyperscaler PDM referral via ACE/Partner Center/GCP Partner Hub
- Co-Sell Assisted: Direct deal where PDM engagement was logged and contributed to close

Data Model Requirements:
- CRM opportunity fields to instrument for attribution: marketplace_transacted [boolean], marketplace_source [AWS/Azure/GCP], private_offer_id, co_sell_deal_id, pdm_engagement_score, cloud_commit_drawdown [boolean]
- Attribution weight matrix: define fractional credit rules for multi-source deals
- Lookback window: [Recommend 90-day lookback for marketplace-influenced attribution]

SQL Logic for Marketplace Attribution:
Build a query framework that joins: opportunity table + marketplace transaction export + co-sell pipeline sync + PDM engagement log → produces attributed ARR by source with confidence intervals.

Metrics to Report Weekly:
- Marketplace-transacted new ARR (MTD, QTD, YoY)
- Marketplace new customer acquisition rate (% of new logos via marketplace)
- Co-sell sourced ARR as % of total new ARR
- Private offer acceptance rate (target: >70%)

MODULE 2: HYPERSCALER CO-SELL PERFORMANCE ANALYTICS

AWS ACE Program Analytics:
- Pipeline submission quality score: % of submitted opportunities accepted by AWS field team
- AWS PDM engagement rate: deals with >2 PDM touchpoints vs. self-serve co-sell
- AWS ISV Accelerate funding utilization: POC credits consumed, win rate on funded deals vs. unfunded
- ACE pipeline stage velocity: days in each stage (Submitted → Launched → In Progress → Closed Won)
- AWS co-sell win rate benchmark: industry benchmark is 2-3x vs. non-co-sell deals

Microsoft IP Co-Sell Analytics:
- Azure Consumed Revenue (ACR) contribution from your workloads: required for IP Co-Sell Incentivized status
- Partner Center pipeline quality: MPN-attached opportunity acceptance rate
- Co-sell incentive earned (Microsoft pays incentive on closed co-sell wins): track payout cadence and ROI
- Customer MACC/Azure commit drawdown: what % of your enterprise deals involve customers with Azure committed spend (MACC)

GCP Partner Advantage Analytics:
- GCP Partner Hub pipeline coverage: % of ICP accounts engaged via GCP co-sell
- Google Cloud Partner Success Manager (PSM) engagement score per deal
- GCP Marketplace consumption analytics: monthly recurring SaaS subscription revenue via GCP

PDM Engagement Scoring Model:
Score each co-sell deal 1-10 based on:
- Number of PDM touchpoints
- PDM tier (generalist vs. specialist vs. ISV-dedicated)
- Joint customer meetings held
- PDM-authored co-sell opportunity
Correlate PDM engagement score → deal win rate and ACV → quantify PDM ROI per hyperscaler

MODULE 3: PRIVATE OFFER OPTIMIZATION ENGINE

Private Offer Economics Framework:
For each marketplace, analyze:
- Deal ACV distribution for marketplace-transacted vs. direct-billed deals
- Private offer discount depth vs. win rate correlation (by deal size bucket)
- Time-to-close on private offer deals vs. direct contract (marketplace reduces procurement friction)
- Net margin impact: marketplace fees (typically 3-5% for AWS/Azure after ISV Accelerate) vs. faster close value

CPPO (Channel Partner Private Offer) Analytics:
- CPPO partner activation rate: which VARs/MSPs are actually submitting marketplace transactions
- CPPO deal velocity: partner-originated private offers vs. vendor-originated
- CPPO discount economics: vendor-to-partner vs. partner-to-customer margin waterfall
- CPPO partner performance ranking: ARR contribution, deal size, win rate

Renewal and Expansion Analytics:
- Marketplace-transacted customer renewal rate vs. direct-billed cohort (H1: marketplace customers renew at higher rates due to embedded procurement flow)
- Expansion ARR for marketplace customers: is cloud commit drawdown driving higher NRR?
- Auto-renewal rate for SaaS marketplace subscriptions

MODULE 4: CLOUD MARKETPLACE LISTING ANALYTICS

Listing Funnel Performance by Marketplace:
AWS Marketplace SaaS Listing:
- Impressions → Product Detail Page views (CTR benchmark: 2-4%)
- PDP views → Free Trial starts (benchmark: 8-15%)
- Free Trial → Paid subscription (benchmark: 15-25%)
- Paid subscription → Annual commit conversion

Azure Marketplace:
- Azure Active Users seeing your listing → contact events
- Test drive activation rate and test-drive-to-purchase conversion
- Co-sell opportunity creation rate from listing traffic

Listing Quality Score Framework:
Build a composite score (1-100) from:
- Review count and average rating (target: >50 reviews, >4.2 stars)
- Listing content completeness (description word count, screenshot count, video presence)
- Category keyword ranking (search position for primary keywords)
- Recent review velocity (reviews in last 90 days signals active customer base)

Listing A/B Testing Roadmap:
Prioritize experiments by estimated impact:
1. Title optimization: include top buyer jobs-to-be-done keyword
2. Hero screenshot: before/after value visualization vs. product UI screenshot
3. Description opening paragraph: lead with customer outcome vs. product feature
4. Pricing display: monthly vs. annual vs. consumption-based pricing prominence

MODULE 5: HYPERSCALER PROGRAM ROI MODEL

Investment Tracking:
- AWS ISV Accelerate program fee (if applicable): $X/year
- Azure co-sell program compliance investment (engineering hours for ACR tagging, co-sell alignment): $X/year
- GCP Partner Advantage tier compliance investment: $X/year
- Marketplace listing and integration engineering costs (initial + ongoing): $X/year
- Alliances team headcount allocated to hyperscaler programs: $X/year FTE cost

Return Attribution:
- Marketplace-transacted ARR at standard gross margin: $X
- Co-sell sourced ARR (full credit): $X
- Co-sell assisted ARR (fractional credit, recommend 25-33%): $X
- Marketplace fee avoidance on direct deals closed faster: $X (procurement cycle reduction value)
- AWS/Microsoft/Google co-invest funds received (POC credits, MDF, GTMP funding): $X

Payback Period Model:
- Simple payback: Total cloud alliance investment ÷ Annual attributed contribution margin
- Target payback: <18 months for early-stage, <12 months for growth-stage companies

Board-Ready Narrative Framework:
Three-slide cloud marketplace story:
1. Slide 1: Marketplace as distribution channel — TAM of buyers with cloud committed spend
2. Slide 2: Our marketplace performance trajectory (trailing 4 quarters, forward projection)
3. Slide 3: Co-sell ROI proof — program investment vs. attributed ARR, win rate lift

OUTPUT FORMAT:
Deliver each module as a structured analytics specification document with:
- Exact metric definitions (numerator, denominator, time window)
- Data source requirements and integration specs
- Dashboard layout recommendations with visualization type per KPI
- Automated alert thresholds (e.g., "alert if private offer acceptance rate drops below 60%")
- Weekly report template for cloud alliances VP to present to CRO

Include specific benchmark data for each major metric so the team knows whether they are performing above or below industry standard.

## Example Input/Output

**Input Example:**

Company: Datastream Analytics (data pipeline and observability SaaS)
ARR: $18M, targeting $35M next 12 months
Cloud Marketplace: AWS Marketplace (SaaS listing, active 14 months), Azure Marketplace (SaaS listing, active 6 months)
Co-Sell: AWS ISV Accelerate enrolled (no dedicated funding yet), Microsoft IP Co-Sell Ready
Current tracking: AWS marketplace transactions sync to Salesforce via manual CSV export monthly; co-sell pipeline tracked in a separate spreadsheet; no Azure marketplace data in CRM
Goal: Build the case for hiring a dedicated cloud alliances manager and investing in GCP marketplace listing

---

**Output Example (abridged):**

**MODULE 1: ATTRIBUTION FRAMEWORK — DATASTREAM ANALYTICS**

Revenue Classification (Last 12 Months):
- Marketplace-Transacted ARR: $2.1M (12% of new ARR) — AWS Marketplace SaaS transactions
- Co-Sell Sourced ARR: $890K (5% of new ARR) — AWS ACE opportunities accepted and closed
- Co-Sell Assisted ARR: $3.2M (estimated, 18% of new ARR) — using 30-day PDM engagement lookback

Attribution gap identified: $4.1M in pipeline has both a marketplace transaction AND a direct Salesforce opportunity — implement de-duplication logic using `private_offer_id` as the definitive marketplace-close signal.

Data Model Change Required (Salesforce):
New Opportunity Fields:
- cloud_transacted [Picklist: AWS/Azure/GCP/None]
- private_offer_id [Text — populated from AWS/Azure portal export]
- co_sell_source [Picklist: ACE/Partner Center/GCP Hub/None]
- pdm_engagement_count [Number — auto-populated from co-sell sync]
- cloud_commit_drawdown [Checkbox — customer MACC/EDP applies]

**MODULE 2: AWS CO-SELL PERFORMANCE — DATASTREAM ANALYTICS**

AWS ACE Pipeline Scorecard (Last 6 Months):
- Opportunities submitted to AWS: 34
- Opportunities accepted by AWS field: 22 (65% acceptance rate — industry benchmark: 55-70% ✓)
- PDM engagement rate (≥2 touchpoints): 14/22 (64% — target: >70% ⚠️)
- AWS ISV Accelerate win rate: 41% vs. non-co-sell win rate: 24% — **1.7x lift confirmed**
- Average ACV with AWS co-sell: $87K vs. $52K direct — **67% ACV premium on co-sell deals**

Top Optimization Finding: 8 accepted ACE opportunities had zero PDM touchpoints — these are "co-sell registered but not activated." Implement PDM outreach SLA: within 5 business days of acceptance, alliances team must schedule joint customer call. Estimated impact of fixing this gap: +$620K additional influenced ARR annually.

**MODULE 5: HYPERSCALER PROGRAM ROI — DATASTREAM ANALYTICS**

Investment (Annual):
- AWS ISV Accelerate fees: $0 (pre-funding tier)
- Alliances manager time (partial — 40% of 1 FTE at $140K OTE): $56K
- Marketplace engineering (ongoing maintenance): $18K
- Total: $74K/year

Return (Attributed, Last 12 Months):
- Marketplace-transacted contribution margin (70% GM on $2.1M): $1.47M
- Co-sell sourced CM (70% GM on $890K): $623K
- Co-sell assisted fractional CM (30% × 70% GM on $3.2M): $672K
- Total attributed contribution margin: **$2.765M**

**Payback Period: 0.32 years (3.8 months)**
**Program ROI: 37x**

Recommendation for board: Invest in dedicated cloud alliances manager ($175K OTE) + GCP marketplace listing ($40K engineering). Even at 50% of current ROI in year 1 new investment, payback = 7 months. Build to $5M marketplace-transacted ARR by EOY.

## Success Metrics

- Private offer acceptance rate: target >70% (above 60% is baseline, below 50% signals pricing or offer structure problem)
- AWS ACE opportunity acceptance rate: target >60% (below 50% means ICP and qualification need tightening)
- Co-sell win rate lift vs. direct: target >1.5x (if lift is <1.3x, co-sell program isn't adding sufficient value)
- PDM engagement rate on accepted co-sell deals: target >70% (measures whether field teams are actively helping)
- Marketplace listing funnel PDP-to-trial conversion: target >10% (below 5% signals listing content or pricing problem)
- Cloud marketplace program ROI: target >5x in year 1, >10x by year 3
- Marketplace-transacted ARR as % of new ARR: benchmark 8-15% for ISV Accelerate-enrolled companies at $10-50M ARR

## Related Prompts

- [Partner Ecosystem Revenue Analytics & Channel Attribution](./AI-Powered-B2B-SaaS-Partner-Ecosystem-Revenue-Analytics-&-Channel-Partner-Attribution-Intelligence-Engine.md)
- [Co-Marketing Campaign ROI & Joint Demand Generation Analytics](./AI-Powered-B2B-SaaS-Co-Marketing-Campaign-ROI-Analytics-&-Joint-Demand-Generation-Intelligence-Engine.md)
- [Cloud Marketplace GTM Architecture & Hyperscaler Revenue Channel Intelligence](../../02_Product-Marketing/Go-To-Market-Strategy/AI-Powered-B2B-SaaS-Cloud-Marketplace-GTM-Architecture-&-Hyperscaler-Revenue-Channel-Intelligence-Engine.md)
- [Partner Marketing Attribution & MDF ROI Intelligence](../../02_Product-Marketing/Partner-&-Channel-Marketing/Partner-Marketing-Attribution-&-MDF-ROI-Intelligence-Engine.md)

## Integration Tips

- **AWS Partner Central / ACE**: Connect ACE pipeline data to Salesforce via AWS Partner CRM Connector or Crossbeam. Sync daily; map ACE stage to Salesforce opportunity stage for unified reporting.
- **Microsoft Partner Center**: Use Partner Center API to pull co-sell pipeline into Salesforce. Map MPN opportunity IDs as external IDs on Salesforce opportunities to enable accurate attribution.
- **GCP Partner Hub**: Export Partner Hub pipeline CSV weekly; use a Google Sheets → Salesforce integration (via Zapier or a custom script) until native integration is available.
- **AWS Marketplace**: Seller portal transaction exports → S3 → daily sync to Snowflake/BigQuery via Fivetran or dbt pipeline. Join on `customer_aws_account_id` to match to Salesforce accounts.
- **Looker/Tableau**: Build a "Cloud Alliance Revenue" dashboard with three tabs: (1) Attribution waterfall, (2) Co-sell performance by hyperscaler, (3) Listing funnel analytics. Refresh daily from data warehouse.
- **Slack Alerts**: Set up automated Slack notifications to #cloud-alliances channel when: new ACE opportunity accepted, private offer accepted, marketplace trial started from enterprise account (matched to target account list).
- **Salesforce Reports**: Create a "Cloud Marketplace & Co-Sell" report folder with: weekly pipeline report for alliances team, monthly attribution report for CRO, quarterly ROI report for CFO.

## Troubleshooting

**Problem: Marketplace transactions and direct CRM opportunities are double-counting ARR (same deal appears in both)**
Solution: Implement `private_offer_id` as the definitive marketplace-close signal. Any opportunity with a non-null `private_offer_id` is marketplace-transacted. Build a deduplication rule: if an opportunity has a `private_offer_id` matching a direct Salesforce opportunity created within 180 days for the same account, merge them with the marketplace transaction as the close method. Run a retrospective cleanup on the last 24 months of data.

**Problem: Co-sell win rate lift analysis is showing no statistically significant difference vs. direct sales**
Solution: The most common cause is co-sell "registration theater" — opportunities are submitted to ACE/Partner Center after they're already in late stages, adding no value. Filter your analysis to opportunities where co-sell was engaged in Stage 1-2 (early pipeline) vs. Stage 4-5 (post-demo). Early co-sell engagement typically shows 1.5-2.5x win rate lift; late-stage registration shows near-zero lift and inflates the co-sell submission count.

**Problem: Cannot get reliable PDM engagement data — it lives in hyperscaler portals and doesn't sync to CRM**
Solution: Implement a lightweight engagement logging process: alliances team creates a Salesforce activity (call/meeting) on co-sell opportunities after each hyperscaler touchpoint, with a custom field `engagement_source: [AWS PDM / Azure PSM / GCP PSM / Joint Customer Call / Email Thread]`. This creates an auditable engagement trail without needing full API integration. For scale, build a Slack bot that prompts the alliances rep 48 hours after a co-sell opportunity is accepted: "Did you connect with the PDM? Log the engagement."

## Version History
- v1.0: Initial creation (auto-generated)
