# Customer Lifetime Value (CLV) Maximization & Revenue Intelligence Engine - AI-Powered LTV Prediction, Segmentation & Growth Playbook

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** CLV, LTV, customer lifetime value, NRR, revenue intelligence, customer success, B2B SaaS, cohort analysis, retention

## Overview
Predicts, segments, and maximizes customer lifetime value (CLV) using AI-powered cohort analysis, behavioral signals, and acquisition data. Use this engine to identify your highest-LTV customer profiles, model future revenue by segment, and generate specific playbooks for each CLV tier — from protecting your diamond accounts to culling low-ROI relationships. Designed to run end-to-end with your CRM and product analytics data, producing board-ready CLV intelligence with no manual modeling required.

## Quick Copy-Paste Version

You are an expert B2B SaaS revenue intelligence analyst specializing in customer lifetime value modeling and retention strategy. Analyze the following customer cohort data and generate a complete CLV intelligence report with actionable playbooks.

BUSINESS CONTEXT:
- Company: [Meridian Software]
- Product Category: [B2B project management SaaS]
- Average Contract Value: [$18,000 ARR]
- Average Gross Margin: [78%]
- Current Average Logo Churn Rate: [14% annually]
- Current Average Expansion Rate: [22% annually — net NRR 108%]
- CAC by Channel: [Paid Search $4,200 | Outbound SDR $6,800 | Partner/Referral $2,100 | PLG/Freemium $800]

CUSTOMER SEGMENTS (describe your top 3-5 cohorts or paste CRM data):
- Segment A: Enterprise (500+ employees), avg ARR $45,000, 8% churn, 28% expansion, avg tenure 3.2 years
- Segment B: Mid-Market (100-499 employees), avg ARR $14,000, 16% churn, 18% expansion, avg tenure 1.8 years
- Segment C: SMB (<100 employees), avg ARR $4,200, 31% churn, 9% expansion, avg tenure 0.9 years

Perform ALL of the following analyses and produce ready-to-use outputs:

1. CLV CALCULATION BY SEGMENT: Calculate CLV using the SaaS formula: CLV = ARPU × Gross Margin % × (1 / Churn Rate). Then calculate CLV:CAC ratio for each acquisition channel × segment combination. Identify which combinations are wealth-creating (CLV:CAC >3x) vs. value-destroying (<1x).

2. CLV TIER CLASSIFICATION: Create a 4-tier system (Diamond / Gold / Silver / Bronze) with specific ARR thresholds, behavioral characteristics, and CS resource allocation rules for each tier.

3. LEADING INDICATORS OF HIGH CLV: Identify the top 5 behavioral and firmographic signals from the data that predict a customer will land in the top CLV quartile. These should be measurable within the first 90 days of onboarding.

4. CLV GROWTH PLAYBOOK: For each tier, specify 3 concrete actions (with owners: CS/Marketing/Product/Sales) that will increase CLV by a minimum of 15% over the next 12 months.

5. ACQUISITION REALLOCATION RECOMMENDATION: Based on CLV:CAC analysis, recommend how to reallocate acquisition budget across channels to maximize total portfolio CLV. Include projected NRR impact.

6. BOARD NARRATIVE: Write a 150-word executive summary of CLV health, risks, and the 90-day action plan — formatted for a CFO or board slide.

Output all sections with specific numbers from the data. Every recommendation must be immediately actionable.

## Advanced Customizable Version

ROLE: You are a Chief Revenue Intelligence Officer with expertise in SaaS financial modeling, customer success strategy, and predictive analytics. You combine the rigor of a CFO with the customer empathy of a CS leader. Your mandate is to transform raw customer data into a CLV maximization strategy that the CEO can present to the board and the CS team can execute tomorrow.

CONTEXT:
Company: [YOUR_COMPANY_NAME]
Product Category: [YOUR_PRODUCT_CATEGORY]
Business Model: [SaaS / Usage-Based / Hybrid / Transactional]
Target NRR: [%]
Current NRR: [%]
Gross Margin: [%]
Average Sales Cycle: [DAYS]
CRM: [HubSpot / Salesforce / other]
CS Platform: [Gainsight / ChurnZero / Totango / Spreadsheets]
Product Analytics: [Mixpanel / Amplitude / Heap / Pendo / None]

═══════════════════════════════════════════
CUSTOMER DATA INPUT (paste whatever you have — engine will adapt to partial data):

ACQUISITION DATA:
- Total customers by segment: [SEGMENT: COUNT, ARR, ACQ_DATE_RANGE]
- CAC by channel: [CHANNEL: $CAC]
- Lead source breakdown: [% by channel]
- Time-to-close by segment: [SEGMENT: DAYS]
- Discount rate at close by segment: [SEGMENT: %]

RETENTION & EXPANSION DATA:
- Logo churn rate by segment (annual): [SEGMENT: %]
- Revenue churn rate by segment (annual): [SEGMENT: %]
- Expansion rate by segment (annual): [SEGMENT: %]
- Net Revenue Retention by segment: [SEGMENT: %]
- Average contract length: [MONTHS]
- Renewal rate by tier: [%]

BEHAVIORAL DATA (use whatever is available):
- Time-to-first-value (onboarding): [SEGMENT: DAYS]
- Feature adoption breadth (% of available features used): [SEGMENT: %]
- Monthly active user % (MAU / licensed seats): [SEGMENT: %]
- Support ticket volume and sentiment: [SEGMENT: AVG TICKETS/MONTH, % POSITIVE]
- NPS by segment: [SEGMENT: SCORE]
- Last login recency distribution: [SEGMENT: % active within 30 days]

FIRMOGRAPHIC DATA:
- Industry verticals represented: [LIST with % of ARR]
- Company size distribution: [EMPLOYEE_RANGE: % of ARR]
- Geography: [REGION: % of ARR]
- Tech stack indicators (if available): [KEY_INTEGRATIONS]
- Funding stage of customer base: [% Bootstrap / Seed / Series A / B / C+ / Public]

═══════════════════════════════════════════
ANALYSIS FRAMEWORK — Execute all 9 modules:

MODULE 1: CLV MODELING ENGINE
Calculate CLV for each segment using the appropriate formula for your business model:

For SaaS/Subscription:
CLV = (ARPU × Gross Margin %) ÷ Revenue Churn Rate

For Usage-Based:
CLV = (Avg Monthly Spend × Gross Margin %) ÷ Logo Churn Rate × Usage Growth Multiplier

For Transactional:
CLV = Avg Order Value × Purchase Frequency × Gross Margin % × (1 ÷ (1 - Retention Rate))

Present as a table:
| Segment | ARPU | Gross Margin | Churn Rate | CLV | Avg Tenure | CLV × Volume |
|---|---|---|---|---|---|---|
[Complete for all segments]

Then calculate CLV:CAC ratio for each Segment × Acquisition Channel matrix:
| Segment | Channel | CAC | CLV | CLV:CAC | Status |
|---|---|---|---|---|---|
[Complete matrix — flag any CLV:CAC <1x as "Value-Destroying" and >5x as "Underinvested"]

MODULE 2: CLV TIER ARCHITECTURE
Design a 4-tier customer segmentation framework based on CLV calculation results:

💎 DIAMOND TIER (Top 10% by CLV)
- CLV threshold: $[X]+
- ARR range: $[X]-$[X]
- Defining behavioral characteristics: [5 signals]
- CS model: [High-touch, named CSM ratio X:1]
- Marketing treatment: [Advisory board, co-marketing, executive sponsorship]
- Product input: [Beta access, roadmap influence, named feature requests]
- Financial commitment: [Maximum retention investment justified: up to $X CAC equivalent per account]

🥇 GOLD TIER (Next 20% by CLV)
- CLV threshold: $[X]-$[X]
- ARR range: $[X]-$[X]
- Defining behavioral characteristics: [5 signals]
- CS model: [Scaled high-touch, CSM ratio X:1]
- Marketing treatment: [Case study candidates, peer community leads, upsell campaigns]
- Growth levers: [Specific expansion plays most likely to work for this tier]

🥈 SILVER TIER (Middle 40% by CLV)
- CLV threshold: $[X]-$[X]
- ARR range: $[X]-$[X]
- Defining behavioral characteristics: [5 signals]
- CS model: [Tech-touch + pooled CSM coverage]
- Marketing treatment: [Automated nurture, in-app engagement, group webinars]
- Primary goal: [Convert 15% of Silver to Gold within 12 months — define trigger criteria]

🥉 BRONZE TIER (Bottom 30% by CLV)
- CLV threshold: Under $[X]
- ARR range: Under $[X]
- Defining behavioral characteristics: [5 signals]
- CS model: [Fully automated, community self-serve]
- Decision framework: [Conditions under which Bronze accounts are worth retaining vs. not renewing proactively]
- Rescue criteria: [Signals that indicate a Bronze account can move to Silver within 6 months]

MODULE 3: PREDICTIVE CLV SIGNALS — 90-DAY EARLY WARNING
Identify the top behavioral indicators that predict final CLV tier, measurable within the first 90 days of customer life. Present as a scoring model:

| Signal | Weight | Diamond Threshold | Gold Threshold | Silver Threshold | Data Source |
|---|---|---|---|---|---|
[List 8-10 signals with measurable thresholds]

Examples of signals to evaluate:
- Time-to-first-value (days to activate core use case)
- Number of users who completed onboarding
- Feature adoption breadth at Day 30 / Day 60 / Day 90
- Integration depth (number of connected tools)
- Support ticket quality (strategic vs. basic questions)
- Executive sponsor engagement (EBR attendance, QBR attendance)
- Champion seniority and internal champion network size
- Number of internal use cases documented
- Referral or review given within first 90 days
- Contract structure (annual prepaid vs. monthly)

Create a "CLV Predictor Score" (0-100) using these weighted signals. Define:
- Score 80+: Fast-track to Diamond/Gold treatment immediately
- Score 50-79: Standard onboarding with Gold conversion goal
- Score <50: Activate early intervention protocol (define specific actions)

MODULE 4: CLV GROWTH PLAYBOOKS BY TIER

For each tier, provide:
a) The primary CLV lever (is growth coming from expansion, tenure extension, or both?)
b) Three specific campaigns/motions with owners, timelines, and expected CLV impact
c) The one metric that will tell you within 30 days if the playbook is working

💎 DIAMOND TIER PLAYBOOK
Primary lever: [Tenure extension + multi-product expansion]
Campaign 1: Executive Co-Innovation Program
- What: [Quarterly CTO/VP roundtable + shared roadmap sessions]
- Owner: [VP CS + CMO]
- Timeline: [Ongoing, quarterly cadence]
- CLV impact: [Estimated +X% tenure extension = +$X CLV per account]
Campaign 2: [...]
Campaign 3: [...]
30-day health signal: [Specific metric]

🥇 GOLD TIER PLAYBOOK
[Same structure]

🥈 SILVER TIER PLAYBOOK
[Same structure — focus on automation, self-serve enablement, product-led expansion]

🥉 BRONZE TIER PLAYBOOK
[Same structure — focus on identifying rescue candidates; accepting natural attrition for rest]

MODULE 5: ACQUISITION REALLOCATION MODEL
Based on CLV:CAC analysis from Module 1, build a budget reallocation recommendation:

Current portfolio CLV calculation:
- Total portfolio CLV (all segments × volume): $[X]
- Blended CLV:CAC ratio: [X]x
- % of portfolio that is value-destroying (CLV:CAC <1x): [%] representing $[X] ARR

Reallocation recommendation:
| Channel | Current Budget | Current CLV:CAC | Recommended Budget | Expected Portfolio CLV Impact |
|---|---|---|---|---|
[Complete for each channel]

Projected outcomes at 12 months if reallocation is executed:
- New customer blended CLV: $[X] vs. current $[X]
- Portfolio CLV:CAC improvement: [X]x vs. current [X]x
- NRR impact: +[X]% from better-fit customer acquisition
- Payback period reduction: [X] months

ICP refinement recommendations (the firmographic and behavioral profile of your highest-CLV customers that should inform all ICP targeting):
- Top 5 firmographic signals of high-CLV customers: [LIST]
- Top 5 behavioral signals at close that predict high CLV: [LIST]
- Industries/segments to de-prioritize based on CLV:CAC: [LIST with rationale]

MODULE 6: CLV AT-RISK DETECTION
Identify customers whose actual CLV trajectory is deviating below their predicted CLV:

Early warning signals (rank by predictive power):
1. [SIGNAL]: At-risk threshold [X] | Response: [SPECIFIC ACTION]
2. [SIGNAL]: At-risk threshold [X] | Response: [SPECIFIC ACTION]
3. [SIGNAL]: At-risk threshold [X] | Response: [SPECIFIC ACTION]
4. [SIGNAL]: At-risk threshold [X] | Response: [SPECIFIC ACTION]
5. [SIGNAL]: At-risk threshold [X] | Response: [SPECIFIC ACTION]

CLV rescue campaign for at-risk accounts:
- Trigger: [When CLV Predictor Score drops X points in Y days]
- Immediate actions (0-7 days): [SPECIFIC ACTIONS]
- Escalation protocol (8-30 days): [SPECIFIC ACTIONS]
- Executive involvement threshold: [$ ARR at risk or CLV tier defines when CMO/CRO engages]
- Save/no-save decision framework: [Define criteria for proactive non-renewal vs. rescue investment]

MODULE 7: CLV-BASED MARKETING INTELLIGENCE
Generate insights for CMO and demand generation teams:

a) CLV-weighted ICP Profile: Rewrite your ICP document using CLV data — not just who buys but who creates the most lifetime value. Include:
- Firmographic profile of top CLV decile
- Technographic signals
- Buying trigger patterns (what event preceded purchase for high-CLV customers)
- Champion profile (role, seniority, department of high-CLV account champions)
- Deal structure patterns (contract length, discount level, payment terms of high-CLV deals)

b) Content/channel attribution by CLV tier: Which acquisition channels produce Diamond/Gold customers vs. Bronze? Provide:
| Channel | % Diamond/Gold Customers | Avg CLV of Customer Acquired | Recommendation |
|---|---|---|---|
[Complete for all channels]

c) CLV-informed messaging matrix: How should your value proposition change based on the CLV tier you're targeting?
| Tier Target | Primary Value Prop | Secondary Value Prop | Proof Point Type | Channel Mix |
|---|---|---|---|---|
[Complete for each tier]

MODULE 8: CLV FINANCIAL MODEL FOR BOARD
Produce a board-ready financial summary:

CURRENT STATE (as of [DATE]):
- Total portfolio CLV: $[X]
- Weighted average CLV: $[X] per customer
- CLV:CAC blended ratio: [X]x
- Payback period: [X] months
- NRR: [%]
- % of customers contributing 80% of CLV (Pareto): [X]% of customers = 80% of CLV

12-MONTH PROJECTIONS (with and without CLV maximization program):
| Metric | Without Program | With Program | Delta |
|---|---|---|---|
| NRR | [%] | [%] | +[X]% |
| Avg CLV | $[X] | $[X] | +$[X] |
| Portfolio CLV | $[X]M | $[X]M | +$[X]M |
| CAC Payback | [X] mo | [X] mo | -[X] mo |
| Churn Rate | [%] | [%] | -[X]% |

90-DAY ACTION PLAN (for board slide):
- Week 1-2: [SPECIFIC ACTION] — Owner: [ROLE] — Expected impact: [METRIC]
- Week 3-4: [SPECIFIC ACTION] — Owner: [ROLE] — Expected impact: [METRIC]
- Month 2: [SPECIFIC ACTION] — Owner: [ROLE] — Expected impact: [METRIC]
- Month 3: [SPECIFIC ACTION] — Owner: [ROLE] — Expected impact: [METRIC]

Investment required: $[X] (CS headcount / tooling / marketing programs)
Expected ROI: [X]x within [TIMEFRAME]

MODULE 9: TECH STACK IMPLEMENTATION ROADMAP
Specify exactly how to build this CLV intelligence system in your existing tools:

GAINSIGHT/CHURNZERO:
- Create CLV Tier field (Diamond/Gold/Silver/Bronze) as a Company attribute
- Build CLV Predictor Score as a calculated field using the weighted signal model from Module 3
- Set up automated CTA rules: CLV Predictor Score drops 10+ points in 30 days → CS Manager review task
- Configure automated tier-based Journey/Playbooks for each CLV tier

SALESFORCE/HUBSPOT:
- Add CLV fields to Account object: [Predicted CLV, CLV Tier, CLV Predictor Score, CLV Risk Flag]
- Build CLV reporting dashboard: Portfolio CLV by segment, CLV:CAC by channel, CLV tier migration waterfall
- Create workflow: New account created → calculate 90-day CLV Predictor Score → assign to appropriate onboarding journey

PRODUCT ANALYTICS (MIXPANEL/AMPLITUDE/PENDO):
- Define CLV-predictive events as key behavioral milestones to track (from Module 3 signals)
- Build cohort analysis: Day 30 / Day 60 / Day 90 activation rates by CLV tier
- Create "Power User Identification" report: Users scoring 80th percentile+ on engagement → flag for CS to develop as champions

REPORTING (GOOGLE SHEETS / TABLEAU / LOOKER):
- Weekly CLV Dashboard template: Current CLV by tier, CLV migration (tier upgrades/downgrades), CLV at-risk $, top 10 CLV growth opportunities
- Monthly CLV Report for leadership: Portfolio CLV trend, CLV:CAC by channel, NRR by CLV tier, tier migration analysis

OUTPUT FORMAT: Produce all 9 modules as complete, ready-to-implement deliverables. Every number should be calculated from the input data. Every playbook action must have a named owner, a timeline, and a measurable outcome. The board summary (Module 8) should be paste-ready into a slide deck with zero editing required.

## Example Input/Output

**Input:**
Company: StackFlow (DevOps SaaS)
Gross Margin: 81%
Current NRR: 107%
Segments: Enterprise (500+ EE, avg $52K ARR, 7% churn, 31% expansion), Mid-Market (100-499 EE, avg $16K ARR, 18% churn, 17% expansion), SMB (<100 EE, avg $5K ARR, 34% churn, 6% expansion)
CAC: Paid Search $5,100 | Partner/Referral $1,800 | Outbound $7,400 | PLG $650
Customer counts: Enterprise 180, Mid-Market 640, SMB 1,200

**Output (Module 1 — CLV Modeling, excerpt):**

> **CLV by Segment:**
>
> | Segment | ARPU/yr | Gross Margin | Annual Churn | CLV | Avg Customers | Portfolio CLV |
> |---|---|---|---|---|---|---|
> | Enterprise | $52,000 | 81% | 7% | $601,714 | 180 | $108.3M |
> | Mid-Market | $16,000 | 81% | 18% | $72,000 | 640 | $46.1M |
> | SMB | $5,000 | 81% | 34% | $11,912 | 1,200 | $14.3M |
>
> **Insight:** Enterprise (11% of customers) generates 64% of total portfolio CLV ($108M of $168.7M). SMB (60% of customers) generates only 8.5% of CLV — a structural imbalance.
>
> **CLV:CAC Matrix (critical finding):**
>
> | Segment × Channel | CAC | CLV | CLV:CAC | Decision |
> |---|---|---|---|---|
> | Enterprise × Partner | $1,800 | $601,714 | 334x | 🚀 Massively underinvested |
> | Enterprise × Paid Search | $5,100 | $601,714 | 118x | ✅ Excellent |
> | Enterprise × Outbound | $7,400 | $601,714 | 81x | ✅ Strong |
> | Mid-Market × Partner | $1,800 | $72,000 | 40x | ✅ Excellent |
> | Mid-Market × Paid Search | $5,100 | $72,000 | 14x | ✅ Good |
> | SMB × PLG | $650 | $11,912 | 18x | ✅ Good for volume |
> | SMB × Paid Search | $5,100 | $11,912 | 2.3x | ⚠️ Marginal |
> | SMB × Outbound | $7,400 | $11,912 | 1.6x | 🔴 Value-destroying — STOP |
>
> **Immediate action:** Eliminate outbound SDR motion targeting SMB accounts entirely. Reallocate the ~$890K/year in SDR quota-carrying cost to Enterprise partner development. Projected portfolio CLV impact: +$12-18M over 24 months.

**Output (Module 8 — Board Narrative excerpt):**

> **StackFlow CLV Intelligence Summary — Q1 2026**
>
> StackFlow's $168.7M portfolio CLV is heavily concentrated: 180 Enterprise accounts ($600K CLV each) represent 64% of total lifetime value. Our CLV:CAC analysis reveals an immediate budget reallocation opportunity — eliminating outbound SDR investment in SMB (CLV:CAC 1.6x, value-destroying) and redirecting to Enterprise partner development (CLV:CAC 334x, currently underfunded). If executed over 12 months, we project NRR improvement from 107% to 114%, portfolio CLV growth from $168.7M to $197M, and CAC payback reduction from 8.2 to 6.4 months. The 90-day plan centers on three actions: (1) implement CLV tier architecture in Gainsight by April 1, (2) launch Enterprise partner co-sell program by April 15, (3) sunset SMB outbound motion by May 1 with full budget redeployment by June 1.

## Success Metrics

**Prompt output quality indicators:**
- CLV calculations use the correct formula for the business model (SaaS vs. usage-based vs. transactional)
- CLV:CAC matrix covers every channel × segment combination in the input data
- At least one "value-destroying" combination is identified with a specific discontinuation recommendation
- Board narrative is under 200 words and paste-ready into a slide deck
- All playbook actions have named owners (not "the team"), specific timelines, and measurable outcomes
- CLV Predictor Score uses at least 6 specific, measurable signals — no vague indicators

**Business outcomes to track after implementation:**
- NRR improvement: target +3-7 percentage points within 12 months of implementing tier-based CS model
- Portfolio CLV growth: target +15-25% in 12 months from acquisition reallocation and tier playbooks
- CLV:CAC blended ratio: target improvement from current to >5x within 18 months
- Tier migration rate: target 10-15% of Silver accounts moving to Gold within 12 months
- CAC payback period: target -2 to -4 months within 12 months from ICP refinement

## Related Prompts

- `../../06_Customer-Success-&-Retention/Churn-Prevention-&-Expansion/Upsell-Cross-Sell-Revenue-Intelligence-Engine.md`
- `../../06_Customer-Success-&-Retention/Churn-Prevention-&-Expansion/Churn-Prevention-Expansion-Revenue-Engine.md`
- `../../06_Customer-Success-&-Retention/Customer-Success-Automation/Customer-Health-Score-&-Early-Warning-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md`

## Integration Tips

**HubSpot:**
- Create four custom Company properties: `CLV_Tier` (dropdown: Diamond/Gold/Silver/Bronze), `CLV_Predicted` (number), `CLV_Predictor_Score` (number, 0-100), `CLV_Risk_Flag` (checkbox)
- Build a Workflow: New deal closes → trigger CLV Predictor Score calculation → assign CLV Tier → enroll in tier-specific onboarding sequence
- Use Lists to segment your contact database by CLV tier for all marketing campaigns — replace segment-based lists with CLV-tier-based lists
- Create a CLV Dashboard with: Total portfolio CLV by tier (bar chart), CLV:CAC by channel (scatter plot), tier migration waterfall (month-over-month), top 20 CLV growth opportunities table

**Salesforce + Gainsight:**
- Add CLV fields to the Account object and sync bidirectionally with Gainsight Company object
- Build a Gainsight Rules Engine rule: CLV Predictor Score decreases by 15+ points in 30 days → create CTA (red, P1) for CSM + notify CS Manager via Slack
- Configure Gainsight Journeys: Diamond tier → Executive Partnership Journey; Gold → Growth Journey; Silver → Tech-Touch Scale Journey; Bronze → Self-Serve Journey with 90-day checkpoint
- Set up Success Plan templates for each CLV tier with pre-built milestone tasks mapped to the tier playbooks from Module 4

**Tableau / Looker:**
- Build a "CLV Command Center" dashboard with four panels: (1) Portfolio CLV waterfall by quarter, (2) CLV:CAC scatter plot by channel × segment, (3) CLV tier migration sankey diagram, (4) At-risk CLV pipeline (accounts with declining CLV Predictor Score)
- Schedule automated weekly email delivery of the CLV dashboard to the CS leadership team and CMO

**Google Sheets (lightweight implementation):**
- CLV Calculator template: Input ARPU, Gross Margin, Churn Rate by segment → auto-calculates CLV, CLV:CAC matrix, portfolio CLV — available as a starter template
- Monthly CLV cohort tracker: New customers entered with acquisition channel and firmographic data → auto-assigns predicted CLV tier → tracks actual CLV vs. predicted at 90/180/365 days

**Zapier / Make automation:**
- Trigger: Account NPS drops below 6 → Zap fires → Updates CLV_Risk_Flag to TRUE in CRM → Creates Slack alert in #cs-at-risk channel with account name, CLV tier, and CSM owner
- Trigger: Account logs into product for first time in 30+ days → Zap fires → Sends re-engagement email sequence from CSM's email address, personalized by CLV tier

## Troubleshooting

**Problem: I don't have accurate churn data by segment — the CLV formula breaks down**
Fix: Work backward from what you have. If you know total logo churn (say, 20% annually) but not by segment, use a 60/30/10 distribution assumption (Enterprise 60% lower than avg, Mid-Market at avg, SMB 60% higher) and label outputs as "estimated." Even directionally accurate CLV calculations will reveal the acquisition channel reallocation opportunity. Then implement segment-level churn tracking in your CRM as the 30-day priority — it's the single most valuable data hygiene investment you can make.

**Problem: The CLV:CAC matrix shows every channel is positive — no clear reallocation signal**
Fix: This usually means CAC is understated. Verify your CAC includes fully-loaded costs: sales salary + benefits + quota, marketing program spend + headcount + tools, and management overhead (typically add 30-40% to direct spend). If CAC is accurate and all channels show strong CLV:CAC, the analysis shifts to opportunity cost — rank channels by CLV:CAC and recommend doubling investment in the top 1-2 (334x partner referral example) even if all are positive.

**Problem: The board presentation is met with skepticism about CLV accuracy**
Fix: Anchor the analysis to a cohort you can fully observe — customers acquired 3+ years ago whose full value is partially realized. Show the actual vs. predicted CLV for that cohort to validate the model. Then present the prospective CLV for newer cohorts as "CLV trajectory" rather than a fixed prediction. CFOs respond better to "customers acquired via partner channel in 2023 have generated 3.2x more ARR in their first 24 months than those acquired via outbound" than to abstract CLV formulas.

## Version History
- v1.0: Initial creation (auto-generated)
