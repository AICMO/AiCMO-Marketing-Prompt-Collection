# AI-Powered B2B SaaS Willingness-To-Pay Research Architecture & Price Sensitivity Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** pricing, b2b, saas, research, revenue-optimization, strategy

## Overview
This prompt architects a fully automated willingness-to-pay (WTP) research program for B2B SaaS companies, combining Van Westendorp Price Sensitivity Meter, Gabor-Granger conjoint analysis, and competitive price benchmarking into a single AI-orchestrated intelligence engine. Use it when you're launching a new pricing tier, repositioning after a competitive price move, or conducting your annual pricing review.

## Quick Copy-Paste Version

You are a senior pricing strategist at a B2B SaaS company. Design a comprehensive willingness-to-pay research program for [Your Product] targeting [Your ICP: e.g., mid-market HR teams at companies with 200-2,000 employees].

Execute the following in sequence:

1. SURVEY DESIGN — Write a 10-question Van Westendorp Price Sensitivity Meter survey with these four core questions adapted for B2B SaaS:
   - "At what monthly price would [product] be so expensive you would not consider it?"
   - "At what price would it be expensive but you'd still consider it?"
   - "At what price would it feel like a bargain — a great deal for the value?"
   - "At what price would you question the quality or seriousness of the solution?"
   Add 6 supporting questions about budget ownership, decision timeline, competitive alternatives being evaluated, and current spend on the problem.

2. SEGMENT ANALYSIS FRAMEWORK — Create a data analysis template that identifies:
   - Acceptable Price Range (APR): range between "bargain" and "expensive"
   - Optimal Price Point (OPP): intersection of "not cheap" and "not expensive" curves
   - Acceptable Price Range by segment (company size, industry, buyer persona)
   - Price sensitivity elasticity score per segment

3. CONJOINT SIMULATION — Design a 5-feature conjoint exercise testing these trade-offs:
   - Price tier (define 3 price points spanning ±40% of current/target price)
   - Feature bundles (3 configurations)
   - Contract term (monthly vs. annual vs. multi-year)
   - Support tier (self-serve vs. dedicated CSM vs. white-glove)
   - Implementation included vs. add-on

4. COMPETITIVE PRICE MAP — Provide a framework to benchmark pricing against 3-5 competitors using public data (pricing pages, G2 reviews mentioning price, sales intelligence tools). Output a price-value map positioning matrix.

5. EXECUTIVE PRICE RECOMMENDATION — Synthesize into a one-page pricing recommendation with:
   - Recommended price point and rationale
   - Risk-adjusted scenarios (bear/base/bull)
   - Segment-specific pricing exceptions (enterprise vs. mid-market)
   - Implementation timeline and change management plan

Output format: Structured JSON for each section so results can be piped directly into HubSpot, Airtable, or a BI dashboard.

## Advanced Customizable Version

# Role
You are a world-class B2B SaaS pricing intelligence engine with expertise in behavioral economics, conjoint analysis, and revenue optimization. You combine the methodologies of Simon-Kucher & Partners, OpenView Partners pricing research, and Kyle Poyar's PLG pricing frameworks.

# Company Context
- Company: [Company Name]
- Product: [Product description — what it does in one sentence]
- Current pricing: [Existing tiers and prices, or "pre-launch"]
- ICP: [Ideal Customer Profile — industry, company size, buyer persona]
- ACV target: [e.g., $18,000–$60,000 annual contract value]
- GTM motion: [Sales-led / Product-led / Hybrid]
- Key value metric: [What customers pay for — seats, API calls, revenue processed, etc.]
- Competitive set: [List 3-5 competitors with known pricing if available]
- Research budget: [e.g., $5,000 for Wynter panel / internal customer interviews / Gong call mining]

# Objective
Design and execute an end-to-end willingness-to-pay research program that produces actionable pricing intelligence within 30 days. All outputs must be ready to present to the CFO and board without further editing.

# Phase 1: Research Architecture (Days 1–5)

## 1A. Methodology Selection Matrix
Evaluate and recommend the optimal WTP research methodology given our GTM motion and budget:

| Methodology | Best For | Accuracy | Cost | Time |
|---|---|---|---|---|
| Van Westendorp PSM | Price range discovery | Medium | Low | 1 week |
| Gabor-Granger | Demand curve modeling | High | Medium | 2 weeks |
| Discrete Choice Conjoint | Feature-price trade-offs | Very High | High | 4 weeks |
| BANT-Scored Interviews | Qual validation | High | Medium | 2 weeks |
| Gong/Chorus Call Mining | In-deal price objection analysis | High | Low (existing data) | 1 week |

Recommend the optimal combination for our situation. Justify with reasoning tied to our ACV, sales cycle length, and buyer complexity.

## 1B. Sample Design
- Target sample: [n=X] responses minimum for statistical significance at 95% confidence ±5% margin of error
- Segmentation variables to capture: company ARR/revenue, industry vertical, buyer title, current solution, deal stage if prospect
- Recruitment strategy: [Customer panel via CS / Prospect outreach via SDR / Third-party panel via Wynter or User Interviews / Gong call analysis]
- Screening criteria: Must have budget authority or direct influence on software purchasing decisions for [category]

## 1C. Survey Instrument (Van Westendorp + Extended)

**Core Van Westendorp Questions (adapt for SaaS context):**

Q1: "Thinking about [Product]'s value for your team, at what monthly price would [Product] become so expensive that you would not consider purchasing it, regardless of its quality?" 
[Open numeric input — capture in $/month]

Q2: "At what monthly price would you consider [Product] to be expensive, but you would still seriously consider purchasing it if it delivered the promised outcomes?"
[Open numeric input]

Q3: "At what monthly price would [Product] feel like a great deal — delivering strong value relative to what you're paying?"
[Open numeric input]

Q4: "At what monthly price would you begin to worry that [Product] might not be high-quality or serious enough to solve your problem?"
[Open numeric input]

**Extended B2B-Specific Questions:**

Q5: "Who holds the budget for this purchase at your company?" 
[Single select: I do / My manager / VP/C-Suite / Shared across team / Procurement]

Q6: "What is your anticipated timeline to make a purchase decision for a solution like this?"
[Single select: This quarter / Next quarter / 6-12 months / 12+ months / No active initiative]

Q7: "What is your current annual spend on solutions addressing this problem (including all tools, services, and internal headcount)?"
[Range select: <$10K / $10K-$50K / $50K-$150K / $150K-$500K / $500K+]

Q8: "Which of the following are you actively evaluating?" 
[Multi-select: list 5-7 competitors + "Building in-house" + "Status quo / doing nothing"]

Q9: "What would make you choose a higher-priced option over a cheaper alternative?"
[Multi-select: Better ROI proof / Implementation support / Enterprise security / Integrations / Brand reputation / References from peers]

Q10: "Which pricing model would you strongly prefer?"
[Single select: Flat monthly seat-based / Usage/consumption-based / Outcome-based / Annual contract with monthly payment / Annual prepaid]

## Phase 2: Data Analysis Framework (Days 6–15)

## 2A. Van Westendorp Output Calculations
Produce cumulative frequency curves for all four price points. Calculate:

- **PMC (Point of Marginal Cheapness)**: Intersection of "too cheap" and "cheap/bargain" curves — floor price below which quality perception deteriorates
- **PME (Point of Marginal Expensiveness)**: Intersection of "expensive" and "too expensive" curves — ceiling above which volume collapses
- **OPP (Optimal Price Point)**: Intersection of "not cheap" and "not expensive" curves — maximum acceptable price for the broadest market
- **APR (Acceptable Price Range)**: Range between PMC and PME — the pricing corridor with minimal resistance

Report all four data points with confidence intervals. Break out by segment (company size: SMB/Mid-Market/Enterprise; buyer title; industry vertical).

## 2B. Demand Curve Modeling (Gabor-Granger Simulation)
Using the Van Westendorp data, model a price sensitivity demand curve:

- At each tested price point, calculate % of respondents who would "definitely buy" + "probably buy"
- Plot willingness-to-pay distribution
- Calculate revenue-maximizing price point: Price × % Willing to Buy × Total Addressable Customers
- Identify the price elasticity coefficient (% change in demand / % change in price)
- Flag "cliff points" where demand drops more than 15% with a price increase of 10%

## 2C. Segment Price Premium Analysis
For each ICP segment, calculate:
- Segment-specific OPP vs. overall OPP
- Price premium or discount this segment will accept relative to baseline
- Recommended segment-specific packaging or pricing exceptions
- Propensity-to-pay score (composite of company size, budget ownership, urgency, current spend)

## Phase 3: Conjoint Feature-Price Trade-Off Analysis (Days 10–20)

## 3A. Conjoint Exercise Design
Present respondents with 8 choice tasks, each showing 3 hypothetical product configurations. Each configuration varies:

**Attributes and Levels:**
1. Price: [$X/month], [$Y/month], [$Z/month] — span 40% below and 40% above target price
2. Feature Set: Core / Professional / Enterprise (define specific features per tier)
3. Onboarding: Self-serve / Guided setup (4 weeks) / White-glove (dedicated PM)
4. Contract: Month-to-month / Annual (15% discount) / 2-year (25% discount)
5. Support: Email only / Business hours chat+phone / 24/7 dedicated CSM

**Analysis Outputs:**
- Part-worth utilities for each attribute level (what feature contributes most/least to perceived value)
- Relative importance of price vs. features vs. support vs. contract term
- Market simulation: Predicted market share at each price point vs. top 3 competitors
- Revenue optimization: Feature bundle configuration that maximizes WTP

## 3B. Willingness-to-Pay by Feature
For each key product feature or capability, calculate:
- Standalone WTP (what would customers pay just for this feature)
- Marginal WTP within bundle (incremental value when added to existing package)
- Feature-price anchoring opportunities (which features justify higher price points)

## Phase 4: Competitive Price Intelligence (Days 1–30, ongoing)

## 4A. Automated Competitive Price Monitoring
Set up monitoring across:
- Competitor pricing pages (scrape and alert on changes)
- G2/Capterra reviews mentioning price (sentiment: "expensive," "affordable," "worth it," "overpriced")
- LinkedIn posts and community discussions (Reddit r/[category], Slack communities)
- Sales call intelligence (Gong/Chorus flags competitor pricing mentioned in calls)
- Win/loss reports: Filter for "price" as primary loss reason

## 4B. Price-Value Positioning Map
Plot all competitors on a 2x2 matrix:
- X-axis: Relative Price (low to high)
- Y-axis: Perceived Value Delivered (low to high based on G2 ratings, review sentiment, analyst positioning)

Identify:
- **Premium Quadrant** (high price, high value): Target for [Company] positioning
- **Economy Quadrant** (low price, low value): Avoid — commoditization trap
- **Overpriced Quadrant** (high price, low value): Competitive displacement opportunity
- **Hidden Value Quadrant** (low price, high value): Potential disruptors to watch

## 4C. Price Response Playbook
For each competitive pricing scenario, define:
- If competitor drops price >20%: [Messaging response / Discounting authority / Feature acceleration]
- If competitor adds free tier: [PLG response / Value narrative update]
- If new low-cost entrant: [Market segmentation response]
- If premium competitor raises price: [Value capture opportunity / Upsell motion]

## Phase 5: Executive Pricing Recommendation (Days 20–30)

## 5A. Recommended Pricing Architecture
Output a complete pricing recommendation document:

**Recommended Price Points:**
- Tier 1 (Starter/Core): $[X]/month — Target: [Persona/Segment], Value metric: [metric]
- Tier 2 (Professional): $[Y]/month — Target: [Persona/Segment], includes [features]
- Tier 3 (Enterprise): Custom/$[Z+] — Target: [Persona/Segment], includes [features + services]

**Annual Discount Structure:**
- Annual prepay: [%] discount
- Multi-year (2-year): [%] discount
- Strategic accounts: [discretionary discount authority and approval process]

**Justification Framework** (for CFO/board presentation):
- WTP research finding: "X% of target buyers indicated willingness to pay $Y or higher"
- Revenue impact model: Current ARR × Price change % × Churn impact % = Net ARR delta
- Competitive position: "At $Y, we are [premium/competitive/value] versus [Competitor A] at $Z"
- Customer impact: "Existing customer price increase affects [n] accounts, estimated [%] churn risk"

## 5B. Risk-Adjusted Scenario Modeling

| Scenario | Price Change | Volume Impact | ARR Impact | Probability |
|---|---|---|---|---|
| Bear | [−X%] | [+Y%] | [net delta] | [%] |
| Base | [+X%] | [−Y%] | [net delta] | [%] |
| Bull | [+X%] | [−Y%] | [net delta] | [%] |

## 5C. Change Management & Rollout Plan
- Existing customer communication sequence (email 1: 60 days notice → email 2: 30 days → email 3: 7 days)
- Sales team enablement: Objection handling for "your price went up"
- Grandfathering policy: Who gets locked in at old price and for how long
- Metric to monitor post-launch: Revenue per customer, NRR, churn rate, deal velocity

# Output Format
Return all outputs as structured JSON with a separate section for each phase. Include an executive_summary field with a 5-bullet synthesis for the CMO/CFO. Flag any findings that deviate significantly from hypothesis (>20% variance) in a risk_flags array.

## Example Input/Output

**Input Example:**

Company: Meridian Analytics — a B2B SaaS business intelligence platform targeting mid-market finance and operations teams (500–5,000 employees). Current pricing: $800/month (flat, unlimited seats). Evaluating moving to usage-based pricing at $25/user/month or keeping flat pricing with a 30% increase to $1,050/month. Top competitors: Tableau (known high price), Metabase (open-source/low cost), Mode Analytics ($450/month). Pre-research hypothesis: Enterprise teams undervalue us; we're leaving $300–$500/month on the table.

**Output Example (excerpt):**

{
  "executive_summary": [
    "Van Westendorp OPP for mid-market segment: $1,100/month flat — 37% above current pricing",
    "Acceptable Price Range: $750–$1,400/month — current pricing sits at PMC floor, suggesting we signal low quality to premium buyers",
    "Usage-based model preferred by 68% of enterprise respondents (500+ seats) vs. only 31% of mid-market (50–200 seats)",
    "Feature commanding highest WTP premium: Native Salesforce bi-directional sync (+$220/month marginal WTP) — currently in Enterprise only",
    "Competitive price map: Meridian sits in 'Hidden Value' quadrant — opportunity to reposition as premium with minimal volume risk at $1,050–$1,200/month"
  ],
  "van_westendorp": {
    "PMC": 600,
    "OPP": 1100,
    "PME": 1600,
    "APR": {"min": 750, "max": 1400},
    "segment_breakdown": {
      "mid_market_200_999": {"OPP": 950, "APR_min": 650, "APR_max": 1250},
      "enterprise_1000_plus": {"OPP": 1400, "APR_min": 900, "APR_max": 2100}
    }
  },
  "conjoint_top_findings": {
    "highest_value_feature": "Native Salesforce sync",
    "marginal_WTP_premium": 220,
    "price_elasticity_coefficient": -1.3,
    "preferred_contract": "Annual prepay (58% of respondents)"
  },
  "recommendation": {
    "tier_1_starter": {"price": 799, "users": "up to 10", "billing": "monthly available"},
    "tier_2_professional": {"price": 1199, "users": "up to 50", "billing": "annual only"},
    "tier_3_enterprise": {"price": "custom", "minimum_ACV": 18000}
  },
  "risk_flags": [
    "SMB segment (<200 employees) shows OPP of $580 — current pricing may be creating churn risk in this cohort",
    "42% of respondents currently evaluating Metabase open-source — price sensitivity among technical buyers is 2.4x higher than business buyers"
  ]
}

## Success Metrics

- Van Westendorp OPP identified within ±15% of subsequent market test results
- Survey completion rate ≥65% among qualified respondents (indicates question quality)
- Conjoint model fit: R² ≥0.85 on hold-out sample
- Post-implementation: New ACV within 10% of model prediction at 90 days
- Customer churn from price change within 5% of scenario model prediction
- Sales win rate maintained within 3% after 60 days at new price point

## Related Prompts

- `../../02_Product-Marketing/Pricing-&-Packaging/AI-Powered-B2B-SaaS-Pricing-Architecture-&-Value-Based-Packaging-Design-Revenue-Intelligence-Engine.md`
- `../../02_Product-Marketing/Pricing-&-Packaging/AI-Powered-B2B-SaaS-Usage-Based-Pricing-Transition-&-Consumption-Model-Revenue-Intelligence-Engine.md`
- `../../02_Product-Marketing/Competitive-Intelligence/AI-Powered-B2B-SaaS-Competitive-Pricing-Intelligence-&-Win-Loss-Pricing-Signal-Detection-Revenue-Intelligence-Engine.md`
- `../../02_Product-Marketing/Customer-&-Market-Research/AI-Powered-B2B-SaaS-Buyer-Psychology-&-Decision-Science-Research-Program-Intelligence-Engine.md`

## Integration Tips

- **Survey distribution**: Pipe Van Westendorp survey via Typeform → Zapier → Airtable for real-time tabulation as responses arrive; no manual export needed
- **Analysis automation**: Feed raw CSV into Claude or GPT-4 with this prompt's analysis framework to generate segment-level WTP curves within minutes vs. hours in Excel
- **CRM enrichment**: Tag HubSpot contacts who completed WTP survey with `wtp_score` property; use in lead scoring model to prioritize high-propensity accounts
- **Sales enablement**: Push OPP and APR data into Gong Deal Intelligence as deal context so reps know price flexibility before every call
- **Board reporting**: Connect Airtable base to Notion or Slides AI to auto-generate CFO pricing deck from live data
- **Ongoing monitoring**: Set up Clay.com workflow to scrape competitor pricing pages weekly and alert RevOps Slack channel on changes >5%
- **Win/loss tagging**: Configure Gong to auto-tag calls where "price" is mentioned as a primary loss reason; feed into monthly pricing review

## Troubleshooting

**Problem: Survey respondents skew toward existing customers who anchored on current price, skewing OPP lower than true market rate.**
Solution: Run separate survey cohorts for (a) existing customers, (b) active prospects, and (c) churned customers. Weight prospect cohort 2x in OPP calculation since they represent incremental revenue opportunity. Existing customers have anchoring bias; their data is most useful for churn risk modeling, not market pricing.

**Problem: Conjoint exercise produces unrealistically high WTP for premium features that don't match actual deal data.**
Solution: Validate conjoint results against 90 days of Gong call data filtered for deals where premium features were discussed. If conjoint overpredicts by >25%, apply a "reality discount factor" of 0.75 to stated WTP before publishing recommendations. Conjoint measures preference, not behavior — always calibrate against closed-won/lost deal data.

**Problem: Enterprise respondents refuse to give numeric price estimates, citing procurement policy.**
Solution: Switch to range-based questions ("Which price range best describes what you'd budget for this category?") with 8 ranges spanning 10x. Alternatively, run a Gabor-Granger monadic test where you show a single price to each respondent and ask "Would you purchase at this price: Yes / Probably Yes / Probably No / No" — this removes the direct anchoring problem while still producing a demand curve.

## Version History
- v1.0: Initial creation (auto-generated)
