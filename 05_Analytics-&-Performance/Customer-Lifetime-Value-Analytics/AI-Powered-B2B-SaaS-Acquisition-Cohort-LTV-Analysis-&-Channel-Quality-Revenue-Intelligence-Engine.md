# AI-Powered B2B SaaS Acquisition Cohort LTV Analysis & Channel Quality Revenue Intelligence Engine - Measure Which Channels and Segments Actually Produce Your Best Customers — Not Just Your Most Customers

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** cohort-analysis, ltv, acquisition-quality, channel-roi, revenue-intelligence, b2b, saas, unit-economics, marketing-attribution, churn, expansion, nrr

## Overview
Transforms your acquisition data into a cohort-by-channel LTV matrix that reveals which marketing channels, campaigns, and ICP segments are producing your highest-lifetime-value customers — and which are burning CAC on accounts that churn before paying back. Use this when you suspect your best-performing channels by volume are not your best-performing channels by customer quality, when board or finance is pressuring you to prove acquisition ROI beyond pipeline, or when CAC payback timelines are extending and you need to diagnose the root cause.

## Quick Copy-Paste Version

You are a senior B2B SaaS revenue analytics expert specializing in cohort-based customer lifetime value analysis. Analyze the following acquisition cohort data and produce a complete channel quality and LTV intelligence report.

COMPANY CONTEXT:
- Product: [Your SaaS product — brief description]
- Business model: [Annual contracts / monthly / usage-based / hybrid]
- Current ARR: [$X]
- Primary customer segments: [e.g., SMB / Mid-Market / Enterprise, or by industry]
- Average gross margin: [X%]
- Discount rate for LTV calculations: [use 12% if unsure]

ACQUISITION COHORT DATA — provide for each of your primary acquisition channels:

Channel 1: [e.g., Organic Search / Inbound Content]
- New logos acquired (last 12 months): [X]
- Average ACV at close: [$X]
- Average CAC (fully-loaded, including sales): [$X]
- 12-month logo retention rate: [X%] (what % are still customers at 12 months)
- 12-month NRR: [X%] (revenue retained + expanded at 12 months)
- Average time-to-first-expansion: [X months, or "none observed yet"]
- Average product engagement score at 90 days: [X/100 or "not measured"]

Channel 2: [e.g., Outbound SDR / Sales-Led]
- [Same fields]

Channel 3: [e.g., Paid Search / LinkedIn Ads]
- [Same fields]

Channel 4: [e.g., Partner / Referral / Ecosystem]
- [Same fields]

Channel 5: [e.g., Product-Led / Self-Serve / Freemium]
- [Same fields]

PRODUCE THE FOLLOWING:

1. COHORT LTV CALCULATION BY CHANNEL
   - Calculate 36-month predicted LTV for each channel cohort: LTV = (ACV × GM) × (12-month NRR) × projected tenure
   - Project tenure from 12-month retention rate: Projected Tenure = 1 / (1 − 12-month retention rate) in years
   - Calculate LTV:CAC ratio per channel (A = >5x, B = 3-5x, C = 2-3x, D = <2x)
   - Rank channels by LTV — not by volume, not by CAC alone, but by LTV:CAC ratio

2. CHANNEL QUALITY SCORE MATRIX
   - For each channel, produce a Channel Quality Score (0-100) based on:
     - LTV:CAC ratio (40% weight)
     - 12-month logo retention rate (30% weight)
     - 12-month NRR vs. company average (20% weight)
     - Time-to-first-expansion vs. company average (10% weight)
   - Classify channels: Premium (80-100), Efficient (60-79), Average (40-59), Poor (<40)

3. BUDGET REALLOCATION RECOMMENDATION
   - Current channel budget split vs. CLV-optimal budget split
   - Which channels deserve more investment based on cohort LTV data?
   - Which channels are you over-investing in based on volume but under-delivering on quality?
   - Specific dollar shift recommendations with expected portfolio LTV impact

4. EARLY LTV SIGNAL IDENTIFICATION
   - Which 90-day behavioral signals most strongly predict high 36-month LTV?
   - Recommended leading indicators to track immediately (product engagement, feature adoption, support quality, etc.)
   - Early warning indicators that a cohort's LTV is trending below expectations

5. 30-DAY QUICK-WIN PLAN
   - 3 actions you can take in the next 30 days to improve cohort LTV trajectory
   - For each: target channel/segment, action, expected LTV impact, measurement approach

Format output as a Channel Quality & Cohort LTV Intelligence Report with executive summary, channel comparison table, budget reallocation model, and early-signal framework.

## Advanced Customizable Version

ROLE: You are a VP of Marketing Analytics and Revenue Intelligence with 15+ years of B2B SaaS experience, specializing in cohort-based LTV analysis, acquisition channel quality measurement, and marketing investment optimization against lifetime revenue — not just first-year ARR. You have built cohort analytics frameworks at companies scaling from $5M to $500M ARR. You are expert in Salesforce, HubSpot, ChartMogul, Amplitude, Mixpanel, Looker, dbt, and building cohort LTV models in SQL and Python. You understand the critical difference between channels that produce high-volume pipelines and channels that produce high-quality customers.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
COMPANY PROFILE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Company Name: [Company Name]
ARR Stage: [<$5M / $5M-$25M / $25M-$100M / $100M-$500M / $500M+]
Current ARR: [$X]
YoY Growth Rate: [X%]
Funding Stage: [Bootstrapped / Seed / Series A / B / C / Growth / Public]
Business Model: [Pure SaaS / Usage-based / Seat-based / Transaction-fee / Hybrid]
Primary GTM Motion: [Inbound PLG / Outbound sales-led / Channel-led / CS-led expansion / Mixed]
Gross Margin: [X%]
Discount Rate for LTV (WACC): [X% — use 12% as default]
Fiscal Year Start: [Month] (for cohort quarter alignment)
CRM: [Salesforce / HubSpot / Other]
Product Analytics: [Amplitude / Mixpanel / Pendo / Heap / Custom / None]
Revenue Intelligence: [ChartMogul / Baremetrics / Stripe / Maxio / Custom]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
ACQUISITION CHANNEL DEFINITIONS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Define your primary acquisition channels as tracked in your CRM. Include all channels that represent >5% of closed-won logos in the last 24 months.

[Repeat for each channel — provide 4-8 channels for meaningful analysis]

CHANNEL: [e.g., "Inbound — Organic Search"]
  CRM lead source tag(s): [e.g., "Organic Search", "SEO", "Blog"]
  Definition / how customers enter this channel: [describe briefly]
  Primary ICP segment served by this channel: [e.g., "Mid-Market IT leaders, 200-1000 employees"]

CHANNEL: [e.g., "Outbound — SDR-Sourced"]
  CRM lead source tag(s): [e.g., "Outbound SDR", "Cold Outbound"]
  Definition: [describe]
  Primary ICP segment served: [describe]

[Continue for all channels]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
COHORT DATA BY ACQUISITION CHANNEL
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
[Provide data for each channel across each time cohort where available. At minimum, provide the most recent 12-month cohort. Provide 24-month and 36-month data where customers have been customers long enough.]

CHANNEL: [Name]

  COHORT: [e.g., "FY2024 (customers acquired Jan-Dec 2024)"]
    New logos in cohort: [X]
    Average ACV at close: [$X]
    Median ACV at close: [$X]
    Average CAC (fully-loaded, including SDR + AE + marketing allocation): [$X]
    Average sales cycle length: [X days]
    Logos retained at 3 months: [X%]
    Logos retained at 6 months: [X%]
    Logos retained at 12 months: [X%]
    Logos retained at 24 months: [X% or "insufficient data"]
    Logos retained at 36 months: [X% or "insufficient data"]
    Revenue retained at 12 months (GRR): [X%]
    Net Revenue Retention at 12 months (NRR): [X%]
    Net Revenue Retention at 24 months: [X% or "insufficient data"]
    Average ACV of expansions (for accounts that expanded): [$X]
    % of cohort accounts that expanded at least once: [X%]
    Average months to first expansion: [X months]
    % of cohort accounts that sourced at least one referral: [X%]
    Average onboarding time to first value (days to key activation event): [X days]
    Average product engagement score at 30 days: [X/100 or "not tracked"]
    Average product engagement score at 90 days: [X/100 or "not tracked"]
    Number of integrations connected at 90 days (average): [X]
    Support tickets per account per month (average, first 6 months): [X]
    Primary churn reasons (top 3 from exit surveys): [list]
    Primary expansion triggers (top 3): [list]

  COHORT: [e.g., "FY2023"]
    [Same fields]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
ICP SEGMENT OVERLAY
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
For each of your primary ICP segments, provide additional context:

SEGMENT: [e.g., "Mid-Market FinTech (200-1000 employees, financial services industry)"]
  Channels that primarily source this segment: [list channels]
  12-month NRR for this segment: [X%]
  Logo churn rate: [X%]
  Average ACV at close: [$X]
  Key use case(s): [describe]
  Competitors typically evaluated alongside you: [list]
  Primary buying trigger: [e.g., "digital transformation initiative", "compliance requirement", "team scaling"]

[Repeat for 2-4 segments]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MARKETING INVESTMENT CONTEXT
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Total marketing budget (annual): [$X]
Current spend allocation by channel (approximate):
  - Channel 1: [$X or X%]
  - Channel 2: [$X or X%]
  - Channel 3: [$X or X%]
  - [etc.]
Attribution model currently in use: [First-touch / Last-touch / Linear / Time-decay / Data-driven / None]
Current success metric marketing is measured on: [e.g., "MQLs generated", "pipeline sourced", "new logos", "ARR closed"]
Is marketing currently measured on LTV or customer quality metrics? [Yes/No — describe if yes]
Primary budget pressure or constraint: [e.g., "board wants CAC payback under 18 months", "Series B investors want proof of efficient growth", "planning to shift more budget to PLG motion"]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
ANALYTICAL DELIVERABLES
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Execute the following Acquisition Cohort LTV Intelligence framework:

**MODULE 1: COHORT LTV MODEL BY CHANNEL**

For each channel and available cohort, calculate and present:

A. 36-Month Predicted LTV per Customer (account-level):
   Step 1 — Project tenure from observed retention:
   - If 12-month retention = R₁₂, projected annual churn = 1 − R₁₂
   - Expected tenure in years = 1 / (1 − R₁₂) [geometric series approximation]
   - Cap projected tenure at 7 years for any channel with <24 months of observed data
   
   Step 2 — Project expansion-adjusted revenue per year:
   - Year 1 revenue = ACV × GM
   - Year 2 revenue = Year 1 × (NRR/100) [accounts for both expansion and retained churn]
   - Year 3+ revenue = Prior year × (NRR/100) [compounding NRR effect]
   
   Step 3 — Discount future cash flows to present value:
   - 36-Month LTV (DCF) = Σ [Year N Revenue / (1 + discount rate)^N] for N = 1 to 3
   - Full-tenure LTV (DCF) = Σ [Year N Revenue / (1 + discount rate)^N] for N = 1 to projected tenure

B. Channel LTV Comparison Table:
   Present for each channel:
   | Channel | Avg ACV | 12M NRR | Logo Churn | Projected Tenure | 36M LTV | Full LTV | CAC | LTV:CAC | Quality Grade |
   
C. LTV Cohort Trend Analysis:
   For each channel where 2+ annual cohorts exist:
   - Is cohort quality improving, stable, or declining over time?
   - What changed between cohorts (ICP shift, messaging change, channel expansion, pricing change)?
   - Flag any channel where recent cohort LTV:CAC dropped >20% vs. prior cohort as "Quality Degradation Alert"

D. Referral-Augmented LTV by Channel:
   - For channels with measurable referral rates: add referred pipeline value to base LTV
   - Referral-Augmented LTV = Base LTV + (Referral Rate × Average Referred Customer LTV × Average Referrals per Account)
   - Channels with high referral rates (>15% of accounts sourcing referrals) are systematically undervalued by standard LTV models
   - Present Referral-Augmented LTV as the "True Economic Value" for channels where data supports it

**MODULE 2: CHANNEL QUALITY SCORING MATRIX**

Build a composite Channel Quality Score (0-100) for each channel:

Scoring rubric:
  LTV:CAC Ratio (40% weight):
    >6x = 40 points | 4-6x = 32 points | 3-4x = 24 points | 2-3x = 16 points | <2x = 0 points

  12-Month Logo Retention (30% weight):
    >90% = 30 points | 80-90% = 24 points | 70-80% = 18 points | 60-70% = 12 points | <60% = 0 points

  12-Month NRR vs. Company Average (20% weight):
    >120% of company avg NRR = 20 points | 110-120% = 16 points | 100-110% = 12 points | 90-100% = 8 points | <90% = 0 points

  Time-to-First-Expansion vs. Company Average (10% weight):
    >30% faster than avg = 10 points | 15-30% faster = 8 points | Within 15% of avg = 6 points | 15-30% slower = 4 points | >30% slower = 0 points

Channel Quality Classifications:
  - Premium (80-100): Disproportionately increase investment — these channels produce your best long-term customers
  - Efficient (60-79): Maintain investment — solid quality, optimize for cost efficiency
  - Average (40-59): Maintain cautiously — invest only to fill specific ICP gaps, don't scale
  - Poor (<40): Reduce or restructure investment — quality signals do not support continued scaling at current economics

For each channel, provide:
  - Channel Quality Score with breakdown by scoring dimension
  - Top strength (highest-scoring dimension)
  - Top weakness (lowest-scoring dimension)
  - Recommended investment direction: Scale / Maintain / Reduce / Restructure

**MODULE 3: MARKETING INVESTMENT REALLOCATION MODEL**

A. Current vs. LTV-Optimal Budget Allocation:
   Present a side-by-side comparison:
   
   | Channel | Current Budget | Current % | LTV-Optimal Budget | LTV-Optimal % | Shift |
   
   LTV-optimal allocation methodology:
   - Allocate budget proportional to (Channel Quality Score × Channel Volume Potential)
   - Volume potential = current new logos × realistic scale multiplier (1.0x to 3.0x based on channel type)
   - Cap any single channel at 40% of total budget to maintain diversification
   - Minimum 5% allocation for any channel with Premium or Efficient quality rating (maintain presence)
   - Zero new investment for any channel with Poor rating until quality is restructured

B. Dollar Shift Recommendations:
   - List specific shifts: "Move $X from [Channel A] to [Channel B]"
   - Rationale for each shift tied directly to cohort LTV data
   - Expected timeline for portfolio LTV improvement (improvements typically visible at 6-12 month cohort mark)
   - Risk flag: identify any channel where large budget reduction will create pipeline gap before new channel volumes up

C. Portfolio LTV Impact Projection:
   - Current estimated portfolio LTV contribution by channel (Channel LTV × Annual Volume)
   - Projected portfolio LTV after reallocation (24-month horizon)
   - Expected portfolio LTV improvement: absolute ($X) and percentage (X%)
   - Break-even timeline: how long before reallocation produces measurably improved cohort LTV data?

**MODULE 4: EARLY LTV SIGNAL FRAMEWORK**

Identify and codify the behavioral signals available in the first 30-90 days after close that best predict 36-month LTV trajectory:

A. Product Engagement Signals (if product analytics data is available):
   Correlate 90-day product engagement metrics with 12-month NRR outcomes:
   - Features activated in first 30 days vs. 12-month NRR: [analyze correlation]
   - Sessions per week in first 90 days vs. 12-month retention: [analyze correlation]
   - Integrations connected in first 60 days vs. expansion rate: [analyze correlation]
   - Team adoption breadth (users active / seats purchased) at 90 days vs. LTV: [analyze]
   
   Define your "Activation Threshold": the specific combination of product signals in first 90 days that predicts 12-month NRR >110%. Example: "3+ features activated + 2+ integrations + 5+ weekly active users by day 60 → predicts 118% NRR at 12 months in our Enterprise cohort."

B. Relationship and Sales Quality Signals:
   Analyze whether these early signals predict LTV:
   - Deals with executive sponsor identified at close vs. those without: LTV difference?
   - Deals with defined success criteria in contract vs. without: retention difference?
   - Multi-threaded deals (3+ contacts in CRM) vs. single-threaded: churn difference?
   - Closed with competitive displacement vs. greenfield: expansion rate difference?
   - Sales cycle length vs. LTV: do faster or slower sales cycles produce higher-quality customers?

C. Onboarding Signals:
   - Onboarding completion rate (% of onboarding milestones hit in first 30 days) vs. 12-month retention
   - Time-to-first-value (days to first meaningful output/result from product) vs. churn risk
   - Champion engagement during onboarding vs. long-term retention

D. LTV Early Warning Score:
   Combine the top 3-5 predictive signals into a single LTV Early Warning Score (0-100) assigned to each new customer at day 60-90:
   - LTV Early Warning Score = (Signal 1 weight × score) + (Signal 2 weight × score) + ...
   - Define threshold: LTV Early Warning Score <40 = "High LTV Risk" → trigger proactive CS + marketing intervention
   - Define threshold: LTV Early Warning Score >70 = "High LTV Potential" → trigger expansion nurture + advocacy program enrollment
   - Expected accuracy: score should predict 12-month NRR within 15% for >70% of accounts (validate quarterly)

**MODULE 5: CHANNEL-SPECIFIC LTV ACCELERATION PROGRAMS**

For each channel with Channel Quality Score <60 (Average or Poor), design a structured intervention program to improve cohort LTV:

PROGRAM STRUCTURE for each channel:
  Target cohort: [Most recent 12-month cohort for this channel]
  LTV Gap: [Current LTV vs. company benchmark — quantified]
  Root cause hypothesis: [Based on churn reasons + low-NRR pattern — why is this channel producing lower-quality customers?]
  
  Intervention 1 — ICP Targeting Tightening:
    - Specific ICP filters to add or tighten to improve quality at top of funnel
    - Expected impact on lead volume: X% reduction
    - Expected impact on closed-won customer quality: X% improvement in 12-month NRR
    - Measurement: Compare NRR of new cohort post-ICP-filter vs. prior cohort at 6 months
  
  Intervention 2 — Onboarding Enhancement for This Channel's Typical Customer:
    - What does this channel's typical customer struggle with in onboarding? (from churn data)
    - Specific onboarding improvement: additional training material, CSM check-in, in-app guide, etc.
    - Expected impact on time-to-value and 90-day engagement score
    - Measurement: 90-day engagement score of new cohort vs. prior cohort
  
  Intervention 3 — Early Expansion Seeding:
    - What expansion opportunity can be introduced at 90-120 days for this channel's customers?
    - Trigger: [specific product usage or business event]
    - Content: [value story / ROI case study from similar customers who expanded]
    - Expected impact on expansion rate and time-to-first-expansion
    - Measurement: % of cohort expanding by 12 months vs. prior cohort

For Premium and Efficient channels (Quality Score ≥60), design a LTV Amplification Program:
  - How to scale volume from this channel without degrading quality
  - What expansion programs would work best for this channel's typical customer profile
  - Referral activation strategy for this channel's customer profile

**MODULE 6: CMO REPORTING FRAMEWORK FOR COHORT LTV**

A. Cohort LTV Dashboard (Monthly):
   - New logo cohort count and average predicted LTV (by channel)
   - Portfolio Cohort LTV total: sum of all active cohort predicted LTVs
   - LTV:CAC ratio by channel, trending MoM
   - LTV Early Warning Score distribution for most recent cohort (% in High Risk / Medium / High Potential tiers)
   - Cohort quality trend: is average new logo predicted LTV increasing or decreasing QoQ?

B. Board-Ready Cohort LTV Narrative:
   Produce a 3-paragraph narrative for board slides:
   - Paragraph 1: Current state — which channels are producing your highest-LTV customers and at what volume
   - Paragraph 2: Trend — how cohort quality has evolved over the last 8 quarters
   - Paragraph 3: Roadmap — the specific actions being taken to improve cohort LTV and when the data will show results

C. Finance Partnership: Connecting Cohort LTV to ARR Planning:
   - How to use cohort LTV data to build a more accurate 3-year ARR forecast
   - Cohort revenue retention schedule: for each active cohort, project year-by-year ARR contribution
   - Provide the finance team with a cohort ARR waterfall: Current Cohort ARR + (Cohort ARR × Projected NRR) for each year
   - This converts marketing's cohort LTV model into the ARR bridge that finance uses for board and investor reporting

D. Marketing OKR Recommendations Based on Cohort LTV:
   Replace or augment volume-based MQL targets with quality-based cohort targets:
   - OKR 1: "Increase average new logo predicted 36M LTV by X% by [date]" — measured at cohort close, tracked at 6 and 12 months
   - OKR 2: "Improve LTV:CAC ratio for [Lowest-Quality Channel] from [current] to [target] by [date]" — measured by cohort grade
   - OKR 3: "Increase share of new logos from Premium channels from X% to Y% of total new logos by [date]" — measured monthly
   - OKR 4: "Reduce LTV Early Warning Score <40 rate for [newest cohort] from X% to Y% by [date]" — measures onboarding quality improvement

Output format: Full Acquisition Cohort LTV Intelligence Report with Executive Summary, channel comparison table, cohort LTV model with DCF calculations, Channel Quality Scoring Matrix, Budget Reallocation Recommendation with projected portfolio LTV impact, Early LTV Signal Framework with activation thresholds, channel-specific intervention programs, and CMO reporting templates — formatted for direct use in board slides, finance presentations, and marketing planning.

## Example Input/Output

**Input Example:**

Company: Vantral (B2B RevOps SaaS, $35M ARR, Series B)
Channels and cohort data (FY2024 cohort):
- Organic Search/Content: 87 logos, $28K ACV, $9,200 CAC, 88% 12M retention, 118% 12M NRR, 7.2 months to expand, 14% referral rate
- Outbound SDR: 124 logos, $31K ACV, $19,800 CAC, 72% 12M retention, 98% 12M NRR, 11.4 months to expand, 4% referral rate
- LinkedIn Paid Ads: 63 logos, $24K ACV, $14,400 CAC, 76% 12M retention, 103% 12M NRR, 9.8 months to expand, 6% referral rate
- Partner/Ecosystem: 34 logos, $47K ACV, $22,100 CAC, 91% 12M retention, 128% 12M NRR, 5.9 months to expand, 22% referral rate
- Product-Led/Self-Serve: 212 logos, $8K ACV, $3,100 CAC, 61% 12M retention, 92% 12M NRR, 14.1 months to expand, 3% referral rate

**Output Example (excerpt):**

---
**VANTRAL ACQUISITION COHORT LTV INTELLIGENCE REPORT**

**Executive Summary:**
Vantral's Partner/Ecosystem channel produces the highest-quality customers in the portfolio — delivering a Referral-Augmented LTV of $412,000 per logo against a $22,100 CAC (LTV:CAC 18.6x), yet receives only 11% of marketing investment despite representing 11% of new logo volume. The Organic Search channel is Vantral's second-highest quality channel with 118% NRR and an $181,000 predicted 36M LTV at a $9,200 CAC — the most capital-efficient acquisition motion in the portfolio. By contrast, the Self-Serve channel's 61% 12-month retention rate and 92% NRR produce a 36M LTV of $18,400 against a $3,100 CAC, resulting in an LTV:CAC of 5.9x that is significantly inflated by raw ratio math but masks a critical quality problem: 39% of these customers never reach payback. **Recommended reallocation: shift $920K from Outbound SDR scaling (LTV:CAC 2.6x after accounting for declining cohort quality) and $640K from Self-Serve volume campaigns into Partner program investment and Organic content velocity.**

**Channel LTV Comparison Table (FY2024 Cohort):**

| Channel | Avg ACV | 12M NRR | 12M Retention | Proj. Tenure | 36M LTV | Full LTV | CAC | LTV:CAC | Ref-Aug LTV | Quality Score | Grade |
|---------|---------|---------|--------------|-------------|---------|----------|-----|---------|------------|--------------|-------|
| Organic/Content | $28,000 | 118% | 88% | 8.3 yrs | $79,200 | $181,000 | $9,200 | 19.7x | $215,000 | 91 | Premium |
| Outbound SDR | $31,000 | 98% | 72% | 3.6 yrs | $52,800 | $82,000 | $19,800 | 4.1x | $84,000 | 58 | Average |
| LinkedIn Paid | $24,000 | 103% | 76% | 4.2 yrs | $43,200 | $72,000 | $14,400 | 5.0x | $78,000 | 62 | Efficient |
| Partner/Ecosystem | $47,000 | 128% | 91% | 11.1 yrs | $134,400 | $385,000 | $22,100 | 17.4x | $412,000 | 97 | Premium |
| Self-Serve PLG | $8,000 | 92% | 61% | 2.6 yrs | $14,400 | $21,600 | $3,100 | 7.0x | $22,000 | 41 | Average |

*36M LTV uses DCF at 12% discount rate; Full LTV uses projected tenure; Ref-Augmented adds referral pipeline value at avg $82K referred customer CLV.*

**Channel Quality Degradation Alert:**
Outbound SDR cohort quality has declined 2 consecutive years: FY2022 LTV:CAC = 5.8x → FY2023 = 4.4x → FY2024 = 4.1x. Root cause: SDR team expanded ICP targeting beyond core RevOps buyers to hit volume targets, introducing lower-fit SMB accounts with 18% higher early churn. Recommendation: tighten ICP filter on Outbound to 150-2000 employee companies with existing RevOps toolchain; accept 20% volume reduction to recover quality.

**LTV-Optimal Budget Reallocation:**

| Channel | Current Budget | Current % | LTV-Optimal | LTV-Optimal % | Shift |
|---------|---------------|-----------|-------------|--------------|-------|
| Organic/Content | $620,000 | 20% | $1,050,000 | 34% | +$430,000 |
| Outbound SDR | $1,280,000 | 41% | $640,000 | 21% | −$640,000 |
| LinkedIn Paid | $520,000 | 17% | $460,000 | 15% | −$60,000 |
| Partner Program | $340,000 | 11% | $720,000 | 23% | +$380,000 |
| Self-Serve/PLG | $340,000 | 11% | $230,000 | 7% | −$110,000 |
| **Total** | **$3,100,000** | **100%** | **$3,100,000** | **100%** | |

Expected portfolio LTV impact from reallocation: +$24.8M in projected 36-month portfolio LTV over 24 months (shift to higher-quality channels compounds at cohort renewal). Break-even on reallocation: 8 months (pipeline gap from SDR reduction offset by 90-day content velocity increase).

**LTV Early Warning Score Framework:**
Signals predictive of 36M LTV in Vantral's data:
1. Integrations connected at day 60 (weight 35%): 3+ integrations → predicts 121% NRR at 12M
2. Active users / seats purchased at day 90 (weight 30%): >40% seat utilization → predicts 89% retention
3. Executive sponsor identified in CRM at close (weight 20%): yes → 14% higher 12M retention
4. Sales cycle >30 days (weight 15%): associated with 23% higher 12M NRR vs. fast-close SMB deals

Activation Threshold: Accounts scoring ≥70 on LTV Early Warning Score (integrations connected + utilization + exec sponsor + sales cycle) have 94% 12-month retention and 124% NRR. Accounts scoring <40 have 58% retention and 89% NRR.
---

## Success Metrics

- **Portfolio Cohort LTV trend:** Average predicted 36M LTV of new logos closed this quarter vs. prior 4 quarters — target: QoQ improvement of >5%
- **Channel LTV:CAC improvement:** LTV:CAC ratio for targeted "restructure" channels trending up over 2+ cohorts
- **LTV Early Warning Score accuracy:** Score predicts 12-month NRR within ±15% for >70% of accounts (validate quarterly against actual outcomes)
- **Budget reallocation ROI:** Portfolio LTV per dollar of marketing spend — measured by comparing total portfolio predicted LTV to total marketing spend annually
- **Premium channel share:** % of new logos acquired from Premium-rated channels (Quality Score ≥80) trending up
- **Cohort quality degradation rate:** No more than 1 channel per year showing >15% YoY LTV:CAC decline — flags systematic quality erosion early
- **Activation threshold adoption:** % of new customers meeting Activation Threshold by day 90 — leading indicator of upcoming NRR and retention performance

## Related Prompts

- [AI-Powered B2B CLV Marketing Investment Optimization & Customer Portfolio Intelligence Engine](./AI-Powered-B2B-CLV-Marketing-Investment-Optimization-&-Customer-Portfolio-Intelligence-Engine.md)
- [AI-Powered CAC Channel Efficiency & Marketing Investment Optimization Intelligence Engine](../CAC-Payback-&-Unit-Economics-Analytics/AI-Powered-CAC-Channel-Efficiency-&-Marketing-Investment-Optimization-Intelligence-Engine.md)
- [AI-Powered ABM Program ROI & Board-Level Revenue Impact Measurement Intelligence Engine](../Account-Based-Marketing-Analytics/AI-Powered-ABM-Program-ROI-&-Board-Level-Revenue-Impact-Measurement-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Net Revenue Retention NRR Marketing Analytics & Expansion Revenue Attribution Intelligence Engine](../Churn-Prevention-&-Retention-Analytics/AI-Powered-B2B-SaaS-Net-Revenue-Retention-NRR-Marketing-Analytics-&-Expansion-Revenue-Attribution-Intelligence-Engine.md)

## Integration Tips

- **ChartMogul / Baremetrics:** Use the "Cohort Analysis" report to export monthly MRR retention curves by customer cohort. Map cohorts to your CRM acquisition channel tags to get channel-level retention data. Export the "MRR Movements" report to calculate NRR by channel: filter by Lead Source, then compute (Expansion MRR − Churn MRR + Starting MRR) / Starting MRR for each cohort. Schedule monthly exports to a Google Sheet that feeds the LTV dashboard.
- **Salesforce:** Create a "Cohort LTV Score" formula field on the Account object: (ACV × Estimated Tenure) × (NRR / 100). Add an "Acquisition Channel LTV Tier" picklist (Premium / Efficient / Average / Poor) driven by a Salesforce Flow that maps Lead Source to the Channel Quality Grade from your cohort analysis. Build a Salesforce Report that shows pipeline and closed-won by Acquisition Channel LTV Tier — this gives your VP Sales real-time visibility into whether the pipeline is coming from quality-producing channels.
- **HubSpot:** Create a custom "Predicted Cohort LTV" property on the Company object, populated by a HubSpot Workflow triggered at deal close. Calculate the value from ACV × Estimated Tenure (pulled from a static table by segment) × NRR forecast (by channel, from your cohort analysis). Use this property to segment all customers into LTV tiers and enroll them in tier-appropriate lifecycle marketing sequences automatically.
- **Amplitude / Mixpanel:** Build a "Cohort LTV Predictor" chart that overlays 30-, 60-, and 90-day product engagement signals (features activated, sessions per week, integrations connected) against 12-month NRR outcomes for historical cohorts. Use Amplitude's Correlation or Mixpanel's Funnels to identify which specific engagement events at day 30-90 most strongly predict high NRR. Export the correlation output to validate and calibrate your LTV Early Warning Score weightings quarterly.
- **Gainsight / Totango:** Configure a custom LTV Early Warning Score in Gainsight's Success Plans or Totango's SuccessPlays. Map your defined early signals (integration count, user adoption, exec sponsor) to scorecards. Set automated CSM alerts when a new account's LTV Early Warning Score drops below your "High LTV Risk" threshold at day 60. This ensures CS acts on LTV signals — not just health score — within the critical onboarding window.
- **Google Looker Studio / Tableau:** Build a Cohort LTV Dashboard that pulls from Salesforce (new logos by channel and quarter) + ChartMogul (cohort NRR by channel) + Amplitude (engagement scores). Create a waterfall chart showing projected ARR contribution from each active cohort over the next 36 months — this is the visual that resonates most with CFOs and board members reviewing marketing's revenue contribution beyond current-year ARR.
- **dbt + Snowflake / BigQuery:** For data-mature teams, build a `cohort_ltv` table in your data warehouse that joins CRM close data (channel, ACV, date) with product events (activation milestones, feature usage) and subscription data (MRR, churn, expansion). Schedule a monthly dbt run that refreshes cohort LTV predictions for all active accounts. Expose this table to your BI tool for real-time cohort LTV reporting without needing to re-run this prompt manually each month.
- **6sense / Bombora:** Reverse-engineer your Premium channel's ICP profile. Export firmographic and technographic data for the top-quartile accounts (by LTV Early Warning Score or actual 12-month NRR) from each Premium channel. Upload these account lists to 6sense as "seed audiences" for lookalike modeling — 6sense will identify in-market accounts that match your highest-LTV customer profiles, not just your average customer profiles. This closes the loop between cohort LTV analysis and prospecting targeting.

## Troubleshooting

**Problem: "I don't have 36 months of cohort data — most of our customers are less than 18 months old."**
Solution: This is the most common issue for growth-stage companies. Use a two-step approach: (1) Run the prompt with what you have — 12-month NRR and logo retention are sufficient for directionally valid comparisons across channels, even if the absolute LTV projections carry uncertainty. State clearly in your output that projections are extrapolated from ≤18 months of data. (2) Benchmark your 12-month metrics against SaaS cohort benchmarks: a channel with 90%+ logo retention and 115%+ NRR at 12 months is almost certainly producing high-LTV customers regardless of what happens after month 18. Conversely, a channel with 68% 12-month retention has already lost 32% of accounts before payback — that data point alone justifies reallocation without needing 36-month projections.

**Problem: "Our CRM lead source attribution is a mess — we can't reliably attribute customers to a specific channel."**
Solution: Don't let imperfect attribution block cohort LTV analysis — build a "Pragmatic Attribution" layer before running the model. Step 1: Export all closed-won accounts from the last 24 months with whatever lead source data exists. Step 2: Manually reclassify a random 10% sample into 4-6 clean channel buckets using your own knowledge of where those accounts actually came from (first meeting context, sales notes, etc.). Step 3: Use this reclassified sample to train a simple rule-based classifier: accounts with SDR activity > 3 touches = Outbound; accounts that came from a trial = PLG; accounts where first touch was a content page = Organic. Step 4: Apply these rules to all accounts to create a "Pragmatic Channel" field. Run the cohort analysis on this — the signal will be directionally correct even if 15-20% of accounts are miscategorized.

**Problem: "The cohort analysis shows our highest-volume channel (Outbound SDR) has the worst LTV — but my CEO is convinced outbound is what got us to $35M ARR."**
Solution: This is one of the most valuable — and politically sensitive — insights cohort LTV analysis produces. Frame the finding carefully: "Outbound SDR is the reason we scaled past $10M ARR and remains important for filling specific ICP gaps that inbound doesn't reach. The LTV data suggests we've been scaling it past its efficient frontier — adding SDR headcount that targets lower-quality ICP profiles to hit volume targets, which has degraded cohort NRR over the last 2 cohorts. The recommendation isn't to eliminate outbound — it's to tighten ICP filters, accept 20% lower volume in exchange for 30% better cohort quality, and redirect the saved budget to channels with demonstrated LTV:CAC >5x." Show the CEO the cohort trend (FY2022 vs. FY2023 vs. FY2024 SDR cohort quality): declining quality on a long-running channel is harder to argue with than a single point-in-time comparison.

## Version History
- v1.0: Initial creation (auto-generated)
