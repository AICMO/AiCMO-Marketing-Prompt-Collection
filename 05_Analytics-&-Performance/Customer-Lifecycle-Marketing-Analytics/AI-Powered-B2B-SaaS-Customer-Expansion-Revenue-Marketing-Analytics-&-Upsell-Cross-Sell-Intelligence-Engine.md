# AI-Powered B2B SaaS Customer Expansion Revenue Marketing Analytics & Upsell/Cross-Sell Intelligence Engine - Measure and Maximize Marketing's Contribution to Expansion ARR

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** b2b, saas, analytics, expansion-revenue, upsell, cross-sell, customer-marketing, nrr, product-led-sales, revenue-attribution

## Overview
Builds a comprehensive analytics intelligence system that identifies expansion-ready accounts, attributes marketing's true contribution to upsell/cross-sell revenue, and optimizes lifecycle programs that drive expansion ARR growth. Use this when marketing needs to prove its role in net revenue retention beyond acquisition, when CS and marketing are misaligned on expansion ownership, or when you need to build a data-driven case for investing in customer marketing as a growth lever — not just a retention function.

## Quick Copy-Paste Version

You are a senior B2B SaaS marketing analytics expert specializing in customer expansion revenue and upsell/cross-sell attribution.

I need a comprehensive analytics framework to identify expansion-ready accounts and measure marketing's direct contribution to expansion ARR.

My company context:
- Product: [describe your SaaS platform — e.g., "enterprise project management platform"]
- Current ARR: [$X] | Expansion ARR as % of new ARR: [X%]
- NRR: [X%] | Target NRR: [X%]
- Customer segments: [SMB / Mid-Market / Enterprise with ARR thresholds]
- Products/modules available for upsell: [list your upsell paths — e.g., "Starter → Professional → Enterprise, AI Add-on, SSO module, API seats"]
- Cross-sell products: [list any adjacent products]
- Marketing tools: [HubSpot / Marketo / Customer.io / Gainsight / Iterable]
- Product analytics: [Mixpanel / Amplitude / Pendo / Heap]
- CRM: [Salesforce / HubSpot]
- Current lifecycle programs: [list what you run — e.g., "monthly feature newsletters, QBR invites, admin-targeted upgrade campaigns"]

Please deliver:

1. **Expansion-Ready Account Scoring Model**: Define a scoring framework using product usage signals (feature adoption depth, seat utilization rate, API call volume), marketing engagement (campaign clicks, webinar attendance, help center visits), and firmographic triggers (headcount growth, funding events, new department hires). Score accounts 0–100 for expansion readiness with tier thresholds (Hot: 75+, Warm: 50–74, Cold: below 50).

2. **Marketing Expansion Attribution Model**: Define rules for attributing upsell/cross-sell revenue to marketing programs — what counts as a marketing-influenced expansion event, the lookback window (30/60/90 days), and how to avoid double-counting with CS-led expansion. Include first-touch, last-touch, and any-touch attribution variants.

3. **Whitespace Revenue Intelligence**: How to identify which accounts have unused product capacity (seats under-utilized, features not activated, departments not onboarded) and calculate the addressable whitespace ARR per account — then show how to prioritize accounts for expansion campaigns by whitespace value × expansion readiness score.

4. **Expansion Campaign Performance Analytics**: For each expansion marketing program type (feature adoption campaigns, tier-upgrade nurture sequences, seat expansion outreach, cross-sell introductions), define the measurement framework: control/treatment cohorts, conversion rate to expansion event, influenced expansion ARR per campaign dollar, and statistical significance requirements.

5. **Expansion Revenue Forecasting Model**: A bottom-up model that uses current expansion-ready account counts × average expansion ACV × historical marketing-influenced conversion rates to forecast marketing-attributable expansion ARR for the next 90 days.

6. **Marketing vs. CS Expansion Ownership Framework**: Clear decision rules for when an expansion is credited to marketing, CS, or sales — based on who touched the account first, which motion the customer responded to, and how to report joint-attribution scenarios.

7. **Weekly Expansion Marketing Dashboard**: Define the 8 KPIs to track weekly: expansion pipeline created, marketing-influenced expansion closed, expansion campaign conversion rates by segment, whitespace accounts activated, and NRR trend by marketing exposure cohort.

8. **Board-Ready Expansion Marketing Narrative**: A monthly one-page format showing marketing's contribution to NRR lift, top-performing expansion programs with ROI, and the 90-day expansion ARR forecast.

## Advanced Customizable Version

ROLE: You are a B2B SaaS Revenue Analytics Architect with 14+ years of experience building expansion revenue intelligence systems at high-growth SaaS companies ($20M–$1B ARR). You specialize in the intersection of product analytics, customer marketing attribution, and expansion revenue forecasting. You've built expansion measurement frameworks at companies including category leaders in HR tech, revenue intelligence, and DevOps — where marketing owned 30–45% of expansion pipeline.

CONTEXT:
Company Profile:
- Company: [Company name]
- Product Category: [e.g., "Revenue Intelligence Platform for enterprise sales teams"]
- ARR: [$X] | MRR: [$X]
- Customer count: [X customers across X segments]
- Expansion ARR last 12 months: [$X] — [X%] of total new ARR
- Current NRR: [X%] | Gross Revenue Retention (GRR): [X%]
- Target NRR for next fiscal year: [X%]

Revenue Architecture:
- Pricing model: [per-seat / usage-based / tiered / module-based]
- Upsell paths: [list all upgrade paths with typical ACV uplift — e.g., "Starter $12K → Professional $36K (+$24K), Professional → Enterprise $120K (+$84K)"]
- Cross-sell products: [list adjacent products and typical ACV — e.g., "Conversation Intelligence add-on at $18K/yr"]
- Expansion motion: [marketing-led / CS-led / sales-assisted / hybrid — describe current reality]

Customer Data Infrastructure:
- CRM: [Salesforce / HubSpot] with deal stages: [list your deal stages]
- Marketing automation: [Marketo / HubSpot / Customer.io / Iterable]
- Customer success platform: [Gainsight / Totango / ChurnZero / Catalyst]
- Product analytics: [Amplitude / Mixpanel / Pendo / Heap]
- Data warehouse: [Snowflake / BigQuery / Databricks] — available: [yes/no]
- First-party intent signals available: [product usage events, in-app behavior, help center searches]
- Third-party intent data: [Bombora / G2 / 6sense / Demandbase]

Current Expansion Marketing Programs:
- [List your lifecycle programs with current performance if known — e.g., "Monthly feature spotlight emails: 28% open rate, 4.2% CTR, no direct expansion attribution currently"]
- [List QBR/EBR programs, upgrade campaigns, seat expansion outreach, cross-sell sequences]

Analytics Gaps to Solve:
- [Describe your current measurement gaps — e.g., "Can't distinguish CS-influenced from marketing-influenced expansions," "No product signal integration into campaign triggers," "No whitespace ARR calculation by account"]

OBJECTIVE: Build a complete Expansion Revenue Marketing Intelligence System that:
1. Transforms raw product usage, engagement, and firmographic data into actionable expansion signals
2. Creates a defensible attribution model that CFO and CRO will accept
3. Enables marketing to forecast expansion ARR contribution with ±15% accuracy
4. Identifies the highest-ROI expansion programs and optimizes budget allocation toward them
5. Produces a weekly operating rhythm for the customer marketing team

DELIVERABLES:

**MODULE 1: EXPANSION-READY ACCOUNT INTELLIGENCE**

1a. Product-Led Expansion (PLX) Signal Architecture
Design a signal taxonomy across three categories:
- Usage Depth Signals: Feature adoption rate (features used / features available × 100), power user density (# users in top quartile of engagement / total seats), API consumption velocity (calls per seat per month trending up/down), workflow automation breadth (# automated workflows created)
- Capacity Constraint Signals: Seat utilization rate (active users / licensed seats — flag accounts at 80%+ as expansion-ready), storage consumption rate, API rate limit proximity, export volume growth rate
- Expansion Intent Signals: Help center searches for premium features, pricing page visits by admin users, upgrade CTA clicks (tracked but unconverted), in-app upgrade intent pop-up dismissals (shows awareness without conversion)

1b. Firmographic Expansion Trigger Architecture
Define external signals that indicate an account's capacity to expand:
- Organizational growth: Headcount growth >15% in 6 months (via LinkedIn or ZoomInfo)
- Funding events: Series A–D rounds completed in last 90 days
- Department expansion: New departments/functions added that would benefit from your product
- Acquisition/merger activity: Parent company acquires a division that's a natural cross-sell target
- Competitive displacement: Competitor shut down or pricing change creating urgency

1c. Composite Expansion Readiness Score (ERS) Formula
Define the weighted scoring model:
ERS = (Usage Depth Score × 0.35) + (Capacity Constraint Score × 0.30) + (Expansion Intent Score × 0.20) + (Firmographic Trigger Score × 0.15)

Tier thresholds:
- Tier 1 (Hot): ERS 75–100 → Immediate SDR outreach + personalized upgrade campaign
- Tier 2 (Warm): ERS 50–74 → Automated nurture sequence + CS alert
- Tier 3 (Developing): ERS 25–49 → Feature adoption campaigns to increase usage depth
- Tier 4 (Not Ready): ERS 0–24 → Standard lifecycle programs, monitor quarterly

1d. Whitespace ARR Calculation by Account
For each account, calculate:
- Seats Whitespace ARR = (Potential seats at full penetration − current licensed seats) × per-seat price
- Tier Whitespace ARR = (Next tier ACV − current ACV)
- Cross-sell Whitespace ARR = (Cross-sell product ACV × likelihood score based on ICP fit)
- Total Addressable Expansion ARR per account = sum of above

Output: Rank all accounts by (ERS × Whitespace ARR) to create prioritized expansion target list

**MODULE 2: EXPANSION REVENUE ATTRIBUTION MODEL**

2a. Attribution Framework Architecture
Define clear attribution rules that CFO and CRO will accept:

Marketing-Owned Expansion (full credit):
- Customer submitted upgrade request or self-served upgrade within 30 days of clicking a marketing campaign
- Customer responded to marketing-triggered upgrade conversation (chatbot, in-app, email) without CS involvement
- Expansion originated from a marketing-generated webinar, event, or content asset and CS wasn't engaged

Marketing-Influenced Expansion (partial credit — default 50%):
- Marketing touched account (email click, webinar attendance, ad impression with engagement) within 90-day lookback window AND CS or sales closed the deal
- Account was in an active marketing campaign at time of expansion event
- Account triggered a marketing-defined expansion signal that generated a CS alert

CS-Owned Expansion (no marketing credit):
- Expansion originated from CS QBR/EBR conversation with no marketing touchpoint in 90 days
- CS proactively identified expansion without any marketing signal or campaign

Joint Attribution Rules:
- If both marketing and CS touched account, split attribution using agreed model (recommended: time-decay weighted toward most recent touchpoint)
- Log all attribution disputes in a weekly "expansion attribution review" between marketing and CS leadership

2b. Lookback Window Policy
- Full credit: Marketing touch within 30 days of expansion close
- 75% credit: Marketing touch 31–60 days before expansion close
- 50% credit: Marketing touch 61–90 days before expansion close
- No credit: Marketing touch >90 days before expansion close

2c. Anti-Double-Counting Rules
- Define "expansion event" as: upsell executed (new ACV > old ACV), cross-sell executed (new product added), or seat expansion ≥ 10% seats added
- Each expansion event can only be credited once per attribution model (first-touch OR last-touch OR any-touch — choose one model per fiscal year)
- Expansion renewals (same product, same price, same seats) do NOT count as expansion events

2d. Technical Implementation
- Create Salesforce opportunity record type: "Expansion Opportunity" with field: "Marketing Attribution Source" (dropdown: Marketing-Owned / Marketing-Influenced / CS-Owned)
- Marketo/HubSpot: Tag all campaign interactions with "Expansion Eligible = TRUE" flag for accounts in Tier 1 or Tier 2 ERS
- Build a weekly Salesforce report: "Expansion Opportunities Closed × Attribution Source × ARR Value" for revenue attribution tracking

**MODULE 3: EXPANSION CAMPAIGN PERFORMANCE ANALYTICS**

3a. Campaign-Level Measurement Framework
For each expansion marketing program, define:
- Treatment group: Accounts that received the campaign
- Control group: ERS-matched accounts that did NOT receive the campaign (randomly sampled at 20% holdout)
- Primary metric: Expansion conversion rate = accounts that had an expansion event / total accounts in group
- Revenue metric: Marketing-influenced expansion ARR per account in treatment group vs. control
- Efficiency metric: Influenced expansion ARR / campaign investment = Expansion Marketing ROI

3b. Program-Type Benchmarks (build toward these over 6 months)
Feature Adoption Campaigns:
- Objective: Drive usage depth to increase ERS from Tier 3 to Tier 2
- Success metric: Feature adoption rate increases >15% within 30 days of campaign
- Expansion conversion rate: expect 8–14% of activated accounts expand within 90 days

Tier-Upgrade Nurture Sequences (4–6 email series targeting Tier 2 accounts):
- Objective: Convert warm accounts to expansion without CS involvement
- Success metric: Self-served upgrade or upgrade request submitted
- Expansion conversion rate: expect 12–20% of Tier 1 recipients expand within 60 days

Seat Expansion Outreach (targeted at accounts at 80%+ seat utilization):
- Objective: Prompt admin to add seats before hitting wall
- Success metric: Seat expansion of ≥10% within 30 days
- Expansion conversion rate: expect 18–28% for accounts at 85%+ utilization

Cross-Sell Introduction Sequences (targeting accounts with ICP fit for adjacent product):
- Objective: Create awareness and generate cross-sell opportunities
- Success metric: Demo booked or cross-sell opportunity opened in CRM
- Expansion conversion rate: expect 6–12% generate cross-sell opportunity within 90 days

3c. Statistical Significance Requirements
- Minimum sample size: 50 accounts per treatment group before drawing conclusions
- Confidence level: 90% minimum for campaign optimization decisions; 95% for budget allocation decisions
- Minimum detectable effect: 5 percentage point difference in expansion conversion rate to declare a winner

**MODULE 4: EXPANSION REVENUE FORECASTING MODEL**

4a. Bottom-Up Expansion ARR Forecast (90-Day Rolling)

Step 1 — Build tier counts:
- Count of Tier 1 accounts (ERS 75+): [X accounts]
- Count of Tier 2 accounts (ERS 50–74): [X accounts]

Step 2 — Apply historical conversion rates by tier:
- Tier 1 accounts: [X%] historically expand within 90 days → Expected expansions: [X]
- Tier 2 accounts: [X%] historically expand within 90 days → Expected expansions: [X]

Step 3 — Apply average expansion ACV by tier:
- Tier 1 average expansion ACV: [$X] (upsell ACV or seat expansion value)
- Tier 2 average expansion ACV: [$X]

Step 4 — Apply marketing attribution rate:
- Of expansions that close, [X%] have a marketing-influenced touchpoint → Marketing-attributed expansions: [X]

Step 5 — Calculate 90-Day Marketing Expansion ARR Forecast:
Marketing-attributed expansion ARR = Tier 1 expansions × Avg ACV × Attribution rate + Tier 2 expansions × Avg ACV × Attribution rate

4b. Forecast Confidence Bands
- Base case: Use actual historical conversion rates
- Upside case: +25% conversion rate lift from new campaign initiative
- Downside case: -20% conversion rate (accounts are being churned instead)

4c. Forecast Accuracy Tracking
- Compare forecast to actuals monthly
- Track forecast error rate; target ±15% accuracy at 90-day horizon
- Recalibrate tier conversion rates quarterly using trailing 6-month data

**MODULE 5: MARKETING VS. CS EXPANSION ALIGNMENT OPERATING RHYTHM**

5a. Weekly Expansion Sync (30-min marketing + CS leadership)
Agenda:
1. Review expansion pipeline by attribution source (10 min)
2. Flag attribution disputes and resolve (5 min)
3. Review Tier 1 account list — CS confirms relationship status, marketing confirms campaign coverage (10 min)
4. Identify accounts approaching ERS threshold — coordinate marketing campaign with CS outreach (5 min)

5b. Monthly Expansion Attribution Reconciliation
- Pull Salesforce report: all expansion opportunities closed in month
- Classify each as Marketing-Owned, Marketing-Influenced, or CS-Owned
- Calculate: Total expansion ARR × Marketing attribution rate = Marketing Expansion Revenue Credit
- Present to CRO and CFO with evidence trail (campaign engagement timestamps, CS notes)

5c. SLA Agreement Between Marketing and CS
- Marketing commits: When a Tier 1 account is identified, marketing launches personalized campaign within 3 business days
- CS commits: When marketing flags a Tier 1 account, CS reviews relationship status within 48 hours
- Joint commit: Neither team approaches account for expansion without coordinating first

**MODULE 6: EXPANSION MARKETING WEEKLY DASHBOARD**

Define these 8 weekly KPIs:
1. Tier 1 Account Count: Total accounts currently at ERS 75+ (target: grow 5% week-over-week)
2. Expansion Pipeline Created (Marketing-Influenced): New expansion opportunities opened this week with marketing attribution ($ value)
3. Expansion ARR Closed (Marketing-Influenced): Expansion deals closed this week credited to marketing ($ value, compare to weekly target)
4. Seat Utilization Alert Rate: New accounts this week crossing 80% seat utilization threshold (expansion trigger)
5. Feature Adoption Campaign Performance: % of campaign recipients who activated target feature within 14 days (by program)
6. Tier Upgrade Conversion Rate: % of Tier-Upgrade nurture recipients who submitted upgrade request or self-served (30-day rolling)
7. Whitespace ARR Activated: $ expansion ARR closed this week vs. total addressable whitespace ARR in Tier 1+2 accounts (penetration rate)
8. NRR Trend by Marketing Exposure Cohort: Rolling 3-month NRR for accounts in active marketing programs vs. those not — track the gap

**MODULE 7: BOARD-READY EXPANSION MARKETING NARRATIVE**

Monthly one-page format:
- Headline metric: Marketing-influenced expansion ARR closed (month + trailing 12 months)
- NRR impact: Current NRR vs. prior period, showing marketing exposure cohort NRR vs. baseline
- Top 3 expansion programs with ROI (influenced ARR / campaign spend)
- 90-day expansion ARR forecast by tier
- Key initiative: What's the one expansion program change this month that will have the biggest NRR impact?
- Investment ask (if applicable): "An additional [$X] investment in [program type] is projected to generate [$X × 3-5] in influenced expansion ARR over the next 6 months based on current conversion rates"

CONSTRAINTS:
- Attribution model must be agreed with CS and CRO before implementation — present as a proposal, not a mandate
- All attribution claims must have an evidence trail (campaign engagement timestamp + CRM record)
- Avoid vanity metrics (email opens, impressions) — every metric must connect to expansion ARR or NRR
- When data is unavailable, provide proxy metrics and a plan to instrument the missing signals
- The model should work even if you don't have a data warehouse — provide Excel/Google Sheets-based alternatives for each calculation

OUTPUT FORMAT:
- Section 1: ERS Scoring Model with exact formula, signal definitions, and data sources
- Section 2: Attribution Framework with decision tree (visual-ready text format)
- Section 3: Campaign measurement templates (one per program type)
- Section 4: 90-Day Expansion Forecast model (table format, ready to populate)
- Section 5: Weekly/monthly operating rhythm templates
- Section 6: Implementation roadmap (Week 1–4 quick wins, Month 2–3 full buildout)

## Example Input/Output

**Input Example:**

Using the Quick Copy-Paste version for a mid-market HR tech SaaS company:

- Product: "AI-powered performance management platform for mid-market companies"
- ARR: $28M across 340 customers
- Expansion ARR last 12 months: $4.2M (15% of new ARR)
- Current NRR: 108% | Target NRR: 115%
- Segments: SMB ($20K–$50K ARR), Mid-Market ($50K–$150K ARR), Enterprise ($150K+)
- Upsell paths: "Core → Advanced at +$18K, Advanced → Enterprise at +$45K, Engagement Module add-on at +$12K, Compensation Planning module at +$22K"
- Marketing tools: HubSpot, Gainsight, Pendo
- Current lifecycle programs: Monthly product update emails, quarterly webinars, admin-targeted upgrade emails (sent once a year)

**Output Example:**

*Excerpt from Section 1 — ERS Scoring Model:*

> **EXPANSION-READY ACCOUNT SCORING MODEL FOR PERFORMAI**
>
> **Usage Depth Signals (35% weight):**
> — Feature Adoption Rate: (features enabled / 12 total features) × 100 → score 0–35
> — Specifically for your platform: if Core tier customers are using >6 of 8 Core features, they are feature-saturated and ready for Advanced tier (score 30–35)
>
> **Capacity Constraint Signals (30% weight):**
> — Seat Utilization Rate: Track active_users_last_30_days / licensed_seats via Pendo
> — Critical threshold: 80%+ utilization = score 25–30; 90%+ = 30
> — Data pull: Pendo report "Seat Utilization by Account" weekly → pipe into HubSpot custom property
>
> **Expansion Intent Signals (20% weight):**
> — Compensation Planning module: Any admin visiting the Compensation Planning feature preview page = +15 signal points
> — Pricing page visit: HubSpot tracks [app.performai.com/pricing] visits by known contacts = +10 signal points
> — In-app upgrade modal dismissed: Pendo tracks "Upgrade modal dismissed without converting" events = +8 signal points
>
> **Firmographic Triggers (15% weight):**
> — Headcount growth >10% in 6 months (LinkedIn Sales Navigator): +12 points
> — New CHRO/VP People hired in last 90 days (job change alert via HubSpot or Clearbit): +15 points (new exec = new priorities = expansion opportunity)
>
> **Tier Thresholds for PerformAI:**
> — Tier 1 (Hot): ERS 75+ → 34 accounts currently qualify → Priority for personal upgrade outreach
> — Tier 2 (Warm): ERS 50–74 → 67 accounts → Launch 6-email Upgrade Nurture sequence
> — Tier 3 (Developing): ERS 25–49 → 121 accounts → Feature adoption campaigns targeting unused Core features
>
> **Whitespace ARR Calculation (Top 10 Accounts):**
>
> | Account | Current ARR | ERS | Upsell Whitespace | Cross-sell Whitespace | Total Whitespace ARR |
> |---------|------------|-----|-------------------|----------------------|---------------------|
> | Meridian Healthcare | $65K | 82 | $45K (→Enterprise) | $22K (Comp module) | $67K |
> | Cascade Logistics | $48K | 79 | $18K (→Advanced) | $12K (Engagement) | $30K |
> | Vertex Financial | $52K | 77 | $18K (→Advanced) | $22K (Comp module) | $40K |
> | ... | | | | | |
> | **Total Top 10** | | | | | **$287K** |
>
> *Total addressable whitespace ARR across Tier 1+2 accounts: $1.8M*

*Excerpt from Section 4 — 90-Day Forecast:*

> **90-Day Marketing Expansion ARR Forecast (Q3 FY2026):**
>
> — Tier 1 accounts (34) × 22% historical 90-day conversion rate = 7.5 expansions expected
> — Tier 2 accounts (67) × 9% historical 90-day conversion rate = 6.0 expansions expected
> — Average expansion ACV: Tier 1 = $38K; Tier 2 = $22K
> — Gross expansion ARR expected: (7.5 × $38K) + (6.0 × $22K) = $285K + $132K = $417K
> — Marketing attribution rate (based on last 6 months): 41% of expansions had marketing touchpoint
> — **90-Day Marketing-Influenced Expansion ARR Forecast: $171K**
> — Current quarter target: $210K (marketing needs to improve attribution rate to 50% via new campaign)

## Success Metrics

- ERS model accuracy: >65% of Tier 1 accounts expand within 90 days (recalibrate if <50%)
- Forecast accuracy: Marketing expansion ARR forecast within ±15% of actuals at 90-day horizon
- Attribution coverage: ≥40% of expansion ARR has a documented marketing touchpoint within 90 days
- Campaign incrementality: Treatment cohort expansion rate exceeds control cohort by ≥5 percentage points (statistically significant)
- NRR lift from marketing exposure: Accounts in active expansion programs show NRR ≥3 percentage points higher than unexposed accounts over rolling 6 months
- Whitespace penetration rate: % of Tier 1+2 whitespace ARR captured each quarter (target: 15–20% annually)
- Operating rhythm adoption: Weekly expansion sync conducted 90%+ of weeks; attribution disputes resolved within 5 business days

## Related Prompts

- [Customer Lifecycle Marketing Performance Analytics & Retention Revenue Attribution](./AI-Powered-B2B-SaaS-Customer-Lifecycle-Marketing-Performance-Analytics-&-Retention-Revenue-Attribution-Intelligence-Engine.md) — The foundational NRR attribution framework; use alongside this one for complete lifecycle measurement
- [Net Revenue Retention & Expansion Revenue Intelligence](../../05_Analytics-&-Performance/Customer-Lifetime-Value-Analytics/AI-Powered-Net-Revenue-Retention-&-Expansion-Revenue-Intelligence-Engine.md) — NRR modeling and CLV optimization paired with this expansion analytics system
- [Marketing-Led Customer Expansion & Account Upsell Revenue Architecture](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/AI-Powered-B2B-SaaS-Marketing-Led-Customer-Expansion-&-Account-Upsell-Revenue-Architecture-Intelligence-Engine.md) — The demand generation counterpart — use that to design the programs, use this to measure them
- [Revenue Attribution Model Architecture & Unified Measurement Framework](../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/AI-Powered-B2B-Revenue-Attribution-Model-Architecture-&-Unified-Measurement-Framework-Intelligence-Engine.md) — Full attribution stack that this expansion model plugs into

## Integration Tips

**Salesforce:**
- Create custom Opportunity field: "Marketing Expansion Attribution" (picklist: Marketing-Owned / Marketing-Influenced / CS-Owned / Unattributed)
- Build Salesforce report: "Expansion Opportunities by Attribution Source" — share weekly with CRO and CS leadership
- Create custom Account field: "Expansion Readiness Score" (synced from HubSpot or calculated via formula field pulling from custom properties)
- Set up Salesforce alert: When ERS crosses 75, create a task for CS rep + enroll account in marketing Tier 1 campaign via Marketo/HubSpot webhook

**HubSpot / Marketo:**
- Create a smart list/active list called "Tier 1 Expansion Ready" based on ERS score ≥75 custom property
- Build a 6-email Tier Upgrade Nurture Workflow triggered when account enters Tier 1 list
- Tag all expansion-program email clicks with UTM parameters: utm_campaign=expansion, utm_content=[program-name] to enable campaign-level attribution in CRM
- Set up HubSpot/Marketo webhook to receive Pendo "seat utilization >80%" event → auto-enroll account in seat expansion outreach sequence

**Gainsight / ChurnZero:**
- Configure a Gainsight CTA (call-to-action) triggered when ERS crosses 75: "Expansion Opportunity Identified — coordinate with marketing before outreach"
- Push Whitespace ARR calculation to Gainsight Account 360 view so CS sees it in their workflow
- Build a Gainsight report: "CS-Touched Expansion Events vs. Marketing-Touched" to support attribution reconciliation

**Snowflake / BigQuery (if available):**
- Create a daily ERS calculation job that pulls from: product analytics API (usage signals), CRM API (firmographic triggers), marketing automation API (campaign engagement)
- Store ERS history table to track score trends over time — enables "ERS velocity" as a predictive signal
- Build a dbt model: `expansion_attribution` that joins Salesforce expansion opportunities with marketing touchpoints (via UTM tracking table) using the 30/60/90-day lookback window logic

**Pendo / Amplitude / Mixpanel:**
- Set up a "Seat Utilization Dashboard" filtered by account — trigger a Zapier/webhook when any account crosses 80% active_users/licensed_seats ratio
- Create feature adoption funnel: which Core features do accounts use before expanding to Advanced? Build this path analysis to identify the "gateway" features that predict expansion readiness
- Export weekly: "Feature adoption rate by account" CSV → import into HubSpot as custom property to feed ERS scoring

**Google Sheets / Excel (no data warehouse):**
- Download weekly: Pendo seat utilization export, Salesforce expansion opportunities, HubSpot campaign engagement
- Use VLOOKUP/INDEX-MATCH to join on Account ID and manually calculate ERS in a master spreadsheet
- Build the 90-day forecast model as a simple Google Sheet with formulas pulling from the ERS tier counts

## Troubleshooting

**Problem:** CS pushes back on marketing claiming attribution credit for expansions CS drove
**Solution:** Never implement the attribution model unilaterally. Present it as a proposal in a joint marketing-CS working session. Start with "influenced" credit (50/50 split) on joint-touch expansions rather than full marketing ownership. Build trust over two quarters before claiming full-credit attributions. Frame attribution as "total expansion ARR grew because both teams executed well" — not a zero-sum competition.

**Problem:** ERS model shows 80+ accounts as Tier 1 but conversion rate is only 6% (well below 22% target)
**Solution:** The scoring model needs recalibration — the signals you're weighting too heavily aren't actually predictive. Run a retrospective analysis: of the last 30 accounts that expanded, what was their ERS score 30/60/90 days prior? Identify which signals were highest for accounts that DID expand and lowest for those that didn't. Adjust signal weights accordingly. Also check: are Tier 1 accounts being contacted quickly enough? ERS decays — an account at 85 today may drop to 60 in 60 days if nothing changes.

**Problem:** No product analytics data available — expansion signals are all firmographic/marketing engagement only
**Solution:** Start with what you have: seat utilization (pull from your billing system — it knows licensed vs. active seats), marketing engagement signals (HubSpot/Marketo already tracks clicks and webinar attendance), and firmographic triggers (LinkedIn, ZoomInfo, or manual CS input on headcount growth). Build a simplified 3-signal ERS using only these sources at weights 40%/40%/20%. Simultaneously, prioritize instrumenting product analytics (Pendo has a free tier; Mixpanel has a startup plan) as a Q1 project — even basic page view tracking by account is better than nothing.

## Version History
- v1.0: Initial creation (auto-generated)
