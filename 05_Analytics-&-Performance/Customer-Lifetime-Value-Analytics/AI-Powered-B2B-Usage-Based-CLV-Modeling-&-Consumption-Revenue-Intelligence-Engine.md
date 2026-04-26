# AI-Powered B2B Usage-Based CLV Modeling & Consumption Revenue Intelligence Engine - Predict, Protect, and Grow CLV Under Consumption Pricing

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** clv, ltv, usage-based-pricing, consumption-revenue, unit-economics, b2b, saas, revenue-intelligence, expansion, analytics, ubb

## Overview
Builds a complete CLV model for usage-based and consumption-priced B2B products — where lifetime value isn't fixed at contract close but evolves with actual usage patterns, tier migrations, and consumption growth curves. Use this when you're running a metered, seat+usage, or token-based pricing model and need to predict CLV, identify expansion triggers, detect consumption plateaus that signal churn risk, and design marketing programs around usage milestones.

## Quick Copy-Paste Version

You are a senior B2B SaaS revenue analytics expert specializing in usage-based pricing (UBP) and consumption revenue modeling. Analyze the following data and produce a complete usage-based CLV intelligence report.

COMPANY CONTEXT:
- Product: [Your SaaS product — brief description]
- Pricing model: [Pure usage / Seat + usage overage / Tiered consumption / Token-based / API calls / Hybrid]
- Billing unit: [e.g., API calls, active users, data processed (GB), tokens, events, records, compute hours]
- Current ARR (or ACV if annual committed): [$X]
- Average monthly consumption per account: [X units]
- Price per unit (or tier thresholds): [e.g., $0.008/API call, or Starter: 10K calls/$99, Growth: 100K calls/$499]

CUSTOMER DATA BY USAGE COHORT (fill in what you have — estimates are fine):

Low-Usage Cohort (bottom 33% by monthly consumption):
- Account count: [X]
- Average monthly consumption: [X units]
- Average monthly revenue: [$X]
- Average monthly consumption growth rate: [X%]
- 12-month churn rate: [X%]
- Average tenure so far: [X months]

Mid-Usage Cohort (middle 33%):
- [Same fields]

High-Usage Cohort (top 33%):
- [Same fields]

PRODUCE THE FOLLOWING:

1. USAGE-BASED CLV MODEL PER COHORT
   - Project consumption growth curve for each cohort using the growth rate (compound monthly)
   - Calculate CLV = Sum of (Monthly Revenue × Gross Margin) over projected tenure, discounted at 1% per month
   - Estimate tenure using churn rate: expected tenure (months) = 1 / monthly churn rate
   - Show "consumption ceiling risk": if a cohort's growth rate will exceed current tier ceiling within 6 months, flag upgrade opportunity and incremental revenue impact
   - Rank cohorts by CLV and flag the LTV:CAC ratio for each (assume CAC provided or use $X if not given)

2. USAGE PLATEAU DETECTION & CHURN RISK SCORING
   - Define plateau signal: consumption growth rate drops to <2% for 2+ consecutive months
   - For each cohort, calculate: if consumption flatlines today, what % of projected CLV is lost?
   - Identify the "danger zone": accounts approaching a usage plateau in the mid-cohort (historically the highest churn risk segment — enough usage to survive onboarding but not enough to embed deeply)
   - Design 3 trigger-based interventions for plateau accounts (specific campaign, channel, message, offer)

3. EXPANSION REVENUE SIGNAL INTELLIGENCE
   - Tier upgrade triggers: at what consumption level should marketing/CS activate an upgrade campaign? (Recommend: 70% of current tier limit = expansion trigger)
   - Consumption milestone events: list 5 usage milestones that correlate with long-term retention and CLV (e.g., "first 1,000 API calls", "connected 3+ integrations", "processed first $1M in transactions")
   - Automated expansion campaign design: for each tier upgrade trigger, provide the message, channel, incentive, and timing
   - Expected expansion CLV uplift: if X% of mid-cohort accounts upgrade to high-usage tier, what is the portfolio CLV increase?

4. CLV IMPROVEMENT ACTION PLAN (30/60/90 DAYS)
   - 30 days: 2 quick-win campaigns to activate low-usage accounts before they plateau
   - 60 days: expansion campaign for mid-cohort accounts approaching tier ceiling
   - 90 days: retention deep-dive for high-usage accounts (highest CLV — protect at all costs)

Format output as a Usage-Based CLV Intelligence Report with an Executive Summary, cohort CLV tables, plateau risk assessment, expansion opportunity sizing, and campaign briefs.

## Advanced Customizable Version

ROLE: You are a VP of Revenue Analytics and Customer Economics with 15+ years of B2B SaaS experience, specializing in usage-based and consumption pricing models, CLV forecasting under revenue uncertainty, and designing marketing programs triggered by behavioral usage signals. You have built UBP CLV frameworks at companies including API-first infrastructure providers, AI/ML platforms, data platforms, and developer tooling companies. You are expert in Stripe Billing, Metronome, Orb, Salesforce, Amplitude, dbt, and consumption revenue forecasting in Python/SQL.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
COMPANY PROFILE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Company Name: [Company Name]
ARR Stage: [<$5M / $5M-$25M / $25M-$100M / $100M-$500M / $500M+]
Current ARR (committed baseline): [$X]
Consumption Revenue (above committed baseline, variable): [$X annually]
Variable Revenue as % of Total Revenue: [X%]
YoY Total Revenue Growth: [X%]
Pricing Model: [Select: Pure pay-as-you-go / Committed baseline + overages / Tiered volume / Seat + consumption / Token/credit-based / Hybrid committed+flex]
Primary Billing Unit: [e.g., API calls, tokens, active users, records processed, compute minutes, GB stored, events ingested]
Tier Structure (if applicable):
  - Tier 1: [Name, consumption threshold, price per unit or flat fee]
  - Tier 2: [Name, consumption threshold, price per unit or flat fee]
  - Tier 3: [Name, consumption threshold, price per unit or flat fee]
  - Enterprise: [Custom pricing model]
Gross Margin (blended): [X%]
Gross Margin by Tier (if different): [Tier 1: X%, Tier 2: X%, Tier 3: X%]
Discount Rate for CLV NPV Calculation: [X% monthly — use 1.0-1.5% for most SaaS]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
CONSUMPTION COHORT DATA
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
[Define 3-5 cohorts by consumption level or usage growth trajectory. Provide for each:]

COHORT: [e.g., "Ramp Accounts — growing >15% MoM" / "Mature High-Usage" / "Plateau Risk" / "Low Engagement"]
  Account count (active): [X]
  Average monthly consumption (billing units): [X]
  Average monthly revenue per account: [$X]
  Median monthly revenue per account: [$X]
  Month-over-month consumption growth rate (trailing 3 months): [X%]
  Consumption growth curve shape: [Linear / Exponential / Step-function / Plateau / Declining]
  Average tenure (months since first invoice): [X]
  Monthly logo churn rate: [X%]
  Monthly revenue churn rate: [X%]
  Net Revenue Retention (trailing 12 months): [X%]
  Average time-to-first-expansion (months from signup to first tier upgrade): [X]
  Current tier distribution within cohort: [e.g., 60% Tier 1, 35% Tier 2, 5% Tier 3]
  Fully-loaded CAC for this cohort (average): [$X]
  Primary acquisition channels for this cohort: [e.g., product-led 50%, outbound 30%, inbound 20%]
  Primary churn reasons (from exit interviews): [list top 3]
  Leading feature adoption indicators: [e.g., "connected API key + made first 100 calls + set up webhook"]
  Time-to-value (days from account creation to first meaningful consumption): [X days]
  Average integrations connected: [X]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
PRODUCT USAGE SIGNAL DATA
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Product analytics tool: [Amplitude / Mixpanel / Segment / Heap / Pendo / custom / none]
Consumption data source: [Stripe / Metronome / Orb / custom billing / Snowflake]
Key usage events available for trigger-based marketing: [list events your system tracks]
Aha moment event (the single action most correlated with long-term retention): [event name or "unknown"]
Consumption plateau definition used internally: [e.g., "<3% MoM growth for 3 consecutive months" or "unknown"]
Known expansion trigger signals: [e.g., "reaching 80% of tier limit", "adding 3rd team member", "first automated workflow run"]
Known churn precursors (from retrospective analysis): [e.g., "no API calls for 14 days", "support tickets increase >2x", "champion departs" — or "unknown"]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
CURRENT MARKETING & CS INVESTMENT
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Total expansion + retention marketing budget (annual): [$X]
Current programs for consumption growth: [describe or "none currently"]
Current programs for plateau intervention: [describe or "none currently"]
In-app messaging capability: [Intercom / Appcues / Pendo / Chameleon / none]
Email automation platform: [HubSpot / Marketo / Braze / Customer.io / Iterable / other]
CS platform: [Gainsight / Totango / ChurnZero / Catalyst / Salesforce CS / none]
CS coverage model: [High-touch (dedicated CSM) / Tech-touch (automated) / Hybrid by tier]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
ANALYTICAL DELIVERABLES
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Execute the following usage-based CLV intelligence framework:

**MODULE 1: USAGE-BASED CLV MODEL**

A. Consumption Growth Curve Projection:
   For each cohort, project monthly consumption over the expected tenure using the appropriate curve:
   - Linear growth: Consumption(t) = C₀ + (growth rate × C₀ × t)
   - Exponential growth: Consumption(t) = C₀ × (1 + growth rate)^t
   - Step-function: Consumption grows in discrete jumps at predictable triggers (e.g., hiring events, seasonal peaks)
   - Plateau model: Consumption reaches ceiling at approximately [C₀ × plateau multiplier] and stabilizes
   Identify which curve best fits each cohort based on trailing 3-month data and historical patterns.

B. NPV-Based CLV Calculation per Cohort:
   Using the projected consumption growth curve:
   CLV = Σ [Revenue(t) × Gross Margin] / (1 + monthly discount rate)^t, summed over expected tenure
   Where expected tenure = 1 / monthly logo churn rate (months)
   
   Present results as:
   - Base case CLV (current growth trajectory continues)
   - Bear case CLV (growth drops to 0% — plateau scenario)
   - Bull case CLV (growth accelerates 50% above current rate — expansion scenario)
   - CLV range = Bear case to Bull case; base case = most likely outcome
   
   Critical insight: In usage-based models, the CLV range is typically 3-8x wider than seat-based SaaS. Flag this explicitly — it means both churn prevention AND growth acceleration are higher-leverage interventions than in fixed-contract SaaS.

C. LTV:CAC Ratio by Cohort and Acquisition Channel:
   - Calculate LTV:CAC per cohort (base case CLV / average CAC)
   - Identify which acquisition channels deliver accounts in the highest-CLV cohorts
   - Flag: if Product-Led accounts (self-serve signups) consistently land in low-usage cohorts, this is a product-led growth expansion problem, not an acquisition problem
   - Identify the "CLV arbitrage" opportunity: cohorts where LTV:CAC < 3x but consumption trajectory suggests CLV will exceed 3x LTV:CAC threshold within 12 months — these are under-valued cohorts that deserve acquisition investment ahead of the curve

D. Tier Migration Revenue Model:
   - For each cohort, calculate: what % of accounts will hit their current tier ceiling within 3 / 6 / 12 months at current growth rate?
   - Model the revenue impact of tier migrations: accounts that upgrade contribute an average ACV step-up of $[X] per upgrade event
   - Total expansion revenue opportunity from tier migrations: (accounts approaching ceiling × migration rate × average ACV step-up)
   - Marketing-influenceable share of tier migrations: what % of upgrades are triggered by proactive marketing vs. organic growth? (Benchmark: 30-50% of upgrades in well-instrumented companies are attributable to marketing-triggered campaigns)

**MODULE 2: CONSUMPTION PLATEAU DETECTION & CHURN RISK INTELLIGENCE**

A. Plateau Risk Scoring Model:
   Define consumption plateau criteria for your product:
   - Stage 1 Warning: MoM growth rate drops below [X]% for 1 month (early warning)
   - Stage 2 Alert: MoM growth rate <[X]% for 2 consecutive months (intervention required)
   - Stage 3 Critical: MoM growth rate <[X]% or negative for 3 consecutive months (churn imminent — CS escalation)
   
   For each cohort, calculate:
   - % of accounts currently in Stage 1 / 2 / 3
   - Average CLV at risk per plateau account (base case CLV × (1 − plateau survival rate))
   - Total portfolio CLV at risk from current plateau accounts: [$ amount]
   - Time to churn from plateau onset (benchmark: usage-based accounts typically churn within 3-6 months of consumption plateau)

B. Plateau Anatomy — Why Accounts Plateau:
   Analyze plateau causes by cohort and design targeted interventions:
   - Integration ceiling: product is fully integrated into one workflow but not expanding to adjacent use cases
     → Intervention: Use case expansion campaign showing adjacent workflows + ROI proof points
   - Team adoption ceiling: only 1-2 power users; rest of organization hasn't adopted
     → Intervention: Multi-stakeholder enablement campaign targeting other teams/departments
   - Technical ceiling: customer hit a technical limitation (API rate limit, data format constraint)
     → Intervention: Technical success review + upgrade path to remove ceiling
   - Budget ceiling: customer is at budget limit for current commitment; usage is discretionary
     → Intervention: Business case automation for champion to justify expanded commitment to CFO
   - Value realization gap: customer isn't fully realizing the value already available
     → Intervention: Value realization audit + personalized "You've unlocked X% of available value" campaign

C. CLV Rescue Campaign Architecture:
   Design a 3-stage consumption rescue sequence for Stage 2 plateau accounts:
   
   STAGE 2 PLATEAU — RESCUE SEQUENCE:
   - Day 1: In-app + email from CS/account team: "We noticed your [billing unit] usage has leveled off — are you hitting any friction?"
   - Day 7: Personalized usage audit email: "Here's what your peers in [industry] are doing with [Product] that you might not have explored yet" — include 3 adjacent use case examples with ROI data
   - Day 14: Executive-level check-in trigger (for accounts with ACV > $X): champion email from VP/Director account executive with "Value Realized vs. Value Available" report attached
   - Day 21: Case study spotlight: customer in same industry who overcame similar plateau → usage grew X% over next 6 months
   - Day 30: Offer: "Complimentary [1-hour / half-day] technical success review" with product expert to remove barriers

**MODULE 3: EXPANSION REVENUE TRIGGER INTELLIGENCE**

A. Tier Upgrade Trigger Design:
   For each tier boundary, design marketing triggers at 70%, 85%, and 95% of tier consumption ceiling:
   
   70% TRIGGER — Early Expansion Awareness:
   - Channel: In-app banner + automated email
   - Message: "[Customer Name], you've used [X%] of your [tier] allocation — you're growing fast. Here's what happens when you hit [tier ceiling] and how to plan ahead."
   - Content: Side-by-side comparison of current tier vs. next tier, with concrete use cases enabled by higher tier
   - CTA: "See your upgrade options" → personalized upgrade calculator
   - Owner: Marketing automation (no CS touch required at this stage)
   
   85% TRIGGER — Active Expansion Campaign:
   - Channel: Email from CSM / account owner + Slack if connected
   - Message: "You're 15% away from your limit — let's upgrade before you hit the ceiling and experience any service disruption"
   - Content: Personalized ROI projection: "At your current growth rate, upgrading now will cost $X/month and enable [specific use case or volume] over the next 6 months"
   - Incentive: [Waived setup fee / locked-in pricing for 12 months / additional professional services hours]
   - Owner: CS-assisted, marketing provides content and automated workflow
   
   95% TRIGGER — Urgency Conversion:
   - Channel: Phone call from CS + email from AE
   - Message: "You're at 95% of your limit — we want to get you upgraded today before you experience any disruption"
   - Offer: Emergency upgrade path with immediate activation + retroactive billing credit
   - Owner: CS + Sales, with marketing providing urgency content assets

B. Consumption Milestone Celebration Campaigns:
   Design 5 milestone-triggered campaigns that reinforce product value and accelerate CLV:
   
   MILESTONE 1: [First X billing units consumed — "First Value" milestone]
   MILESTONE 2: [First 30 days of consistent daily usage]
   MILESTONE 3: [Crossed into [usage tier] — proof of growth]
   MILESTONE 4: [First integration connected to core workflow]
   MILESTONE 5: [First team member invited / second department activated]
   
   For each milestone, provide: trigger event, delivery channel, message tone, content type, CTA, expected CLV impact.

C. Expansion Revenue Attribution Model:
   - Define the marketing-sourced expansion threshold: a tier upgrade is "marketing-influenced" if the account was touched by a marketing campaign within [30 / 60 / 90] days of the upgrade event
   - Build a Tier Migration Attribution Dashboard:
     | Migration Path | Accounts | Total Expansion ARR | Marketing-Influenced | Average Days-to-Upgrade After Trigger |
   - Calculate Marketing Expansion ROI: Total expansion ARR marketing-influenced / expansion marketing program cost (target: >10x)
   - Report this metric monthly to CMO as "Expansion Revenue Per Marketing Dollar" for consumption-driven growth

**MODULE 4: USAGE-BASED CLV FORECASTING & SCENARIO PLANNING**

A. Portfolio CLV Forecast (12 / 24 Months):
   Using cohort CLV models and current account mix, project total portfolio CLV under three scenarios:
   
   BASE CASE: Current growth rates and churn rates continue
   INTERVENTION CASE: Plateau rescue campaigns reduce plateau churn by 30%; tier trigger campaigns increase migration rate by 25%
   DOWNSIDE CASE: Macroeconomic pressure causes 20% of mid-usage accounts to reduce consumption by 30% and churn rate increases 15% across all cohorts
   
   For each scenario, calculate:
   - Total portfolio CLV at 12 months and 24 months
   - Revenue at risk vs. base case
   - Marketing investment required for intervention case and expected ROI
   - Key assumptions and sensitivity triggers (which variable has the largest impact on portfolio CLV?)

B. CLV Sensitivity Analysis — Which Levers Move the Needle Most:
   Run sensitivity analysis showing portfolio CLV impact of improving each lever by 10%:
   - 10% reduction in monthly churn rate → portfolio CLV impact: $[X] and [X%]
   - 10% increase in average consumption growth rate → portfolio CLV impact: $[X] and [X%]
   - 10% faster time-to-first-expansion → portfolio CLV impact: $[X] and [X%]
   - 10% improvement in tier migration rate → portfolio CLV impact: $[X] and [X%]
   - 10% increase in gross margin (e.g., infrastructure cost reduction) → portfolio CLV impact: $[X] and [X%]
   
   CRITICAL INSIGHT: In usage-based models, consumption growth rate is typically the highest-leverage CLV variable — more so than churn reduction. Rank levers by impact and direct marketing investment accordingly.

C. New Cohort CLV Prediction for Acquisition Planning:
   Using the behavioral signals from your highest-CLV cohorts, define the "CLV predictive onboarding score":
   - Score each new account at Day 14 based on: consumption in first 14 days + integrations connected + team members invited
   - Accounts scoring in top 25% of Day-14 onboarding score → predicted to land in high-usage cohort → assign to high-touch expansion track
   - Accounts scoring in bottom 25% → predicted low-usage → assign to automated activation sequence immediately (do not wait for churn signal)
   - Expected CLV improvement from early intervention: [X%] improvement in 12-month CLV for bottom-quartile onboarding accounts with proactive intervention vs. reactive response

**MODULE 5: BOARD-READY CONSUMPTION REVENUE CLV NARRATIVE**

A. CMO Metrics Dashboard (monthly):
   - Total portfolio CLV (base case): [$X]
   - CLV at Risk (Stage 2 + Stage 3 plateau accounts × average CLV): [$X]
   - CLV at Risk as % of total portfolio: [X%] — flag if >15%
   - Expansion-Influenced CLV this month: [$ expansion ARR marketing-influenced × average tenure multiple]
   - New logo predicted CLV (average CLV score of new accounts this month): [$X] vs. prior month trend
   - Consumption growth rate trend (portfolio-level, MoM): [X%] — flag if declining 3+ consecutive months

B. Investor-Ready CLV Story for Usage-Based Model:
   Usage-based CLV is typically harder to explain to investors than SaaS ARR — address this directly:
   - Frame CLV as "Revenue Potential per Account" not just "contractual value" — usage upside is the differentiated value
   - Present the "usage floor vs. ceiling" for each cohort: committed revenue (floor) + consumption upside at current growth rate (ceiling)
   - Show the portfolio-level NRR impact of consumption growth: "Our top usage cohort delivers 148% NRR — our product gets more valuable to customers as they grow, creating a revenue compounding effect"
   - Frame CLV risk honestly: "Variable consumption means our CLV range is wider than pure-subscription SaaS — we manage this with [specific programs]"

C. CFO Alignment: CLV-Based Marketing Budget Justification:
   Present the marketing budget for expansion/consumption programs in CLV terms:
   - Total expansion marketing investment: [$X]
   - Total CLV protected/grown through these programs: [$X]
   - Marketing CLV ROI: [X]x — for every $1 invested in consumption growth programs, we protect/add $[X] of portfolio CLV
   - Incremental ARR generated from consumption-triggered tier upgrades: [$X] — directly attributable to marketing campaigns

Output format: Full Usage-Based CLV Intelligence Report with Executive Summary, cohort CLV model tables, consumption curve projections, plateau risk heat map, tier migration opportunity sizing, expansion campaign briefs, 12/24-month portfolio CLV forecast under 3 scenarios, and a prioritized CLV Improvement Roadmap (30 / 60 / 90 days) with campaign owners and measurable CLV targets.

## Example Input/Output

**Input Example:**

Company: Vektron AI (B2B AI data enrichment API, $18M ARR)
Pricing: Pure pay-as-you-go at $0.006/API call; tiers: Starter (<500K calls/$299/mo), Growth (500K-5M/$999/mo), Scale (5M-50M/$3,499/mo), Enterprise (custom)
Gross Margin: 71%
Cohorts:
- Low-Usage (<50K calls/mo): 1,240 accounts, avg $180/mo, 2.3% MoM growth, 7.8% monthly churn, 9-month avg tenure
- Mid-Usage (50K-500K calls/mo): 310 accounts, avg $1,100/mo, 11.2% MoM growth, 2.9% monthly churn, 18-month avg tenure
- High-Usage (500K+ calls/mo): 62 accounts, avg $6,800/mo, 18.7% MoM growth, 0.8% monthly churn, 31-month avg tenure
Monthly discount rate: 1.2%

**Output Example (excerpt):**

---
**VEKTRON AI — USAGE-BASED CLV INTELLIGENCE REPORT**

**Executive Summary:**
Vektron's High-Usage cohort delivers a base-case CLV of $238,000 per account — versus $18,700 for Low-Usage and $67,400 for Mid-Usage. However, portfolio CLV concentration risk is moderate: the 62 High-Usage accounts hold 51% of total portfolio CLV ($14.8M of $29.1M total). The most significant CLV opportunity is in the Mid-Usage cohort, which has an 11.2% MoM consumption growth rate — the fastest-growing cohort — and 31% of accounts are projected to hit the 500K-call Growth tier ceiling within 4 months. A marketing-triggered tier upgrade campaign targeting these 96 accounts at 70% consumption would generate $280K in incremental ARR and $3.2M in long-term CLV uplift at a program cost of under $15K. The Low-Usage cohort presents the highest churn risk: 7.8% monthly churn implies average tenure of 12.8 months and CLV of $18,700 — but Day-14 onboarding score analysis shows 35% of Low-Usage accounts could be reclassified as Mid-Usage within 90 days with aggressive activation intervention.

**Cohort CLV Model:**

| Cohort | Monthly Revenue | Tenure (mo) | Base CLV | Bear CLV (plateau) | Bull CLV (accel) | LTV:CAC |
|--------|----------------|-------------|----------|-------------------|-----------------|---------|
| Low-Usage | $180 | 12.8 | $18,700 | $10,400 | $31,200 | 1.4x |
| Mid-Usage | $1,100 | 34.5 | $67,400 | $28,900 | $142,000 | 3.6x |
| High-Usage | $6,800 | 125.0 | $238,000 | $89,000 | $610,000 | 7.9x |

**Plateau Risk Assessment:**
Mid-Usage cohort plateau risk: 23% of accounts (71 accounts) show Stage 1 warning signals — MoM growth below 3% for 1 month. CLV at risk: $4.8M. If not intervened within 60 days, estimated 40% will progress to Stage 2 and 60% of Stage 2 accounts churn within 90 days. Recommended: deploy Consumption Rescue Sequence immediately to the 71 Stage 1 accounts (priority: accounts in months 8-14 of tenure — highest save rate window).

**Tier Migration Opportunity:**
96 Mid-Usage accounts at >70% of 500K-call tier ceiling. Projected to hit ceiling within 4 months at current growth rate. Expected tier upgrade revenue: 96 accounts × 55% migration rate × $700/month ACV step-up = $36,960/month incremental MRR ($443K annualized). Marketing campaign cost: $12,000. Expansion marketing ROI: 37x. CLV uplift from migrated accounts: +$3.2M portfolio CLV (CLV of Growth tier accounts vs. continued Starter tier trajectory).

**30-Day Action Plan:**
1. Launch 70% tier trigger campaign to 96 approaching-ceiling accounts (Mid-Usage): estimated $443K ARR uplift
2. Deploy Consumption Rescue Sequence to 71 Stage 1 plateau accounts: estimated 28 saves × $67K CLV = $1.9M CLV protected
3. Activate Day-14 onboarding CLV score for all new Low-Usage accounts: route bottom-quartile scorers to automated activation sequence → expected 35% uplift in 90-day CLV for intervened accounts
---

## Success Metrics

- **Portfolio CLV growth rate:** Total portfolio CLV ($ sum across all active accounts) growing ≥ revenue growth rate — indicates improving consumption depth per customer
- **Plateau rescue rate:** % of Stage 2 plateau accounts returned to positive consumption growth within 60 days of intervention (benchmark: 25-40%)
- **Tier migration rate (marketing-influenced):** % of tier upgrades with a marketing campaign touch within 60 days (target: >40% of all upgrades)
- **Expansion marketing ROI:** Incremental expansion ARR generated / expansion program cost (target: >10x)
- **Day-14 CLV score accuracy:** Correlation between Day-14 onboarding score and 12-month actual CLV (target: >0.6 Pearson correlation)
- **CLV range compression:** Ratio of bull-case to bear-case CLV — as your plateau interventions improve, this range narrows (healthy)
- **New logo high-usage cohort entry rate:** % of new accounts in month 3 that have graduated from Low to Mid or High usage cohort (target: improve 5% QoQ)

## Related Prompts

- [AI-Powered B2B CLV Marketing Investment Optimization & Customer Portfolio Intelligence Engine](./AI-Powered-B2B-CLV-Marketing-Investment-Optimization-&-Customer-Portfolio-Intelligence-Engine.md)
- [Customer Lifetime Value Prediction & Acquisition Investment Intelligence Engine](./Customer-Lifetime-Value-Prediction-&-Acquisition-Investment-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Activation Rate Optimization & PQL Marketing Automation Intelligence Engine](../Product-Analytics-&-Activation/AI-Powered-B2B-SaaS-Activation-Rate-Optimization-&-PQL-Marketing-Automation-Intelligence-Engine.md)
- [AI-Powered CAC Channel Efficiency & Marketing Investment Optimization Intelligence Engine](../CAC-Payback-&-Unit-Economics-Analytics/AI-Powered-CAC-Channel-Efficiency-&-Marketing-Investment-Optimization-Intelligence-Engine.md)

## Integration Tips

- **Metronome / Orb / Stripe Billing:** These usage-based billing platforms expose consumption event streams via API. Export daily consumption data per account to Snowflake or BigQuery, then run cohort segmentation and plateau detection queries on a weekly cadence. Automate plateau signal alerting via dbt metrics + Slack webhook: "Alert: 14 accounts crossed Stage 2 plateau threshold this week."
- **Amplitude / Mixpanel:** Build a "Consumption Growth Dashboard" overlaying billing unit consumption data against product event data. Identify which in-product actions correlate most strongly with consumption acceleration (e.g., "accounts that connected a webhook within 7 days have 3.2x higher 90-day consumption growth"). Use these as early activation triggers.
- **Customer.io / Braze / Iterable:** Set up event-triggered campaigns using real-time consumption webhook data. Connect your billing platform's consumption events to your marketing automation platform: when account.consumption_pct_of_tier >= 0.70, trigger the 70% tier campaign; when consecutive_months_growth < 0.02 >= 2, trigger the plateau rescue sequence. No manual segmentation needed — fully automated.
- **Gainsight / ChurnZero:** Map consumption cohort scores to Gainsight's CTAs (Call-to-Action). When a Stage 2 plateau CTA is triggered, auto-generate a CSM task with the account's consumption trend chart, CLV at risk, and the first two Rescue Sequence assets pre-populated. This turns a marketing model into a CS workflow within minutes of plateau detection.
- **Salesforce:** Create a custom "Usage CLV Score" field on the Account object, updated weekly via Salesforce Flow pulling from your consumption data warehouse. Build a "Consumption Health" report for AEs showing tier proximity, growth rate, and estimated upgrade window. This surfaces natural conversation starters for QBRs: "Your growth rate suggests you'll hit your tier limit in ~6 weeks — let's get ahead of that together."
- **HubSpot:** Use HubSpot's Workflow tool to enroll contacts in tier-specific sequences based on custom properties synced from your billing platform. Create a "Consumption Tier" company property (Starter / Growth / Scale / Enterprise) and update it via API when tier migrations occur — this gates contacts into the appropriate post-upgrade celebration and next-tier-awareness sequences automatically.
- **Google Looker Studio / Tableau:** Build a live Usage-Based CLV Portfolio Dashboard with five views: (1) Portfolio CLV total vs. target, (2) Cohort distribution by consumption level, (3) Plateau risk heat map, (4) Tier migration pipeline with revenue impact, (5) Expansion campaign ROI. Refresh daily from your data warehouse. This is your weekly CMO review artifact.

## Troubleshooting

**Problem: "Our consumption data is siloed in engineering/billing systems and marketing doesn't have access to it. We can't run any of these triggers."**
Solution: This is the most common blocker for usage-based CLV marketing — and fixing it is worth the investment. Request a read-only data share from engineering: ask for a daily CSV export of (account_id, billing_period, units_consumed, tier_name) to your marketing data warehouse or Google Sheets. Even this minimal dataset enables cohort segmentation, plateau detection, and tier proximity calculations. Present the business case in CLV terms: "Access to this data enables a $X tier upgrade campaign with estimated $Y ARR impact — the data share takes 2 hours of engineering time." If a full integration is months away, start with a weekly manual export and build the workflows on top of it. Automate later.

**Problem: "Our consumption is extremely seasonal — some accounts spike 10x in December but are flat the rest of the year. The plateau model flags them as churn risk when they're actually healthy."**
Solution: Seasonality is a known failure mode for naive plateau detection. Adjust your plateau definition to use year-over-year consumption comparison instead of month-over-month: a plateau signal fires when current-month consumption is <5% higher than the same month last year, not just when MoM growth slows. For accounts with clear seasonality patterns (identifiable in 12+ months of data), build a "seasonal baseline" model: expected consumption for each month = last year's same-month consumption × [company-wide growth factor]. Deviation below this baseline triggers the alert, not raw MoM comparison. Tag seasonal accounts in your CRM to suppress false-positive plateau alerts during known off-peak months.

**Problem: "The tier migration opportunity looks massive on paper, but our Sales team says most of these accounts resist upgrading because they don't want to commit to a higher tier — they prefer to stay pay-as-you-go even if they exceed their tier."**
Solution: This is a pricing model objection, not a CLV modeling failure. Two paths: (1) If true pay-as-you-go overage pricing exists in your model, present the upgrade as a cost-savings play, not a commitment: "At your current usage rate, you're paying $X/month in overages. Upgrading to Growth tier saves you $Y/month — no increased commitment, just better pricing for your actual usage." Build an auto-generated "Your Overage Cost vs. Upgrade Savings" email that makes this math explicit for each account. (2) If your product requires committed tiers, frame the upgrade in terms of capability unlock, not volume: "Growth tier includes [specific feature / higher rate limit / priority support] that Starter doesn't — here's a customer who unlocked [outcome] after upgrading." Reframe from volume commitment to value access.

## Version History
- v1.0: Initial creation (auto-generated)
