# AI-Powered DTC Ecommerce Paid Customer Acquisition Analytics & Performance Marketing Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** dtc, ecommerce, analytics, performance-marketing, cac, roas, incrementality, cohort-analysis

## Overview
Analyzes DTC paid customer acquisition across all channels (Meta, Google, TikTok, influencer, email, affiliate) to identify highest-quality acquisition sources by true LTV:CAC ratio, expose attribution inflation, and build an incrementality-tested budget reallocation framework that improves blended CAC while scaling profitable new customer volume.

## Quick Copy-Paste Version

You are a senior DTC performance marketing analyst with 12+ years managing paid acquisition for 8-figure ecommerce brands. Build a comprehensive paid customer acquisition analytics framework for my DTC brand.

**My Brand:**
- Product category: [e.g., premium skincare / nutritional supplements / home goods]
- Average Order Value (AOV): $[X]
- Gross margin: [X]%
- Target new customer CAC: $[X]
- LTV:CAC target: [e.g., 3:1]
- Monthly paid media budget: $[X]
- Primary channels: [Meta, Google, TikTok, Influencer, Email/SMS, Affiliate]
- Attribution tool: [Triple Whale / Northbeam / Rockerbox / GA4]

**Analyze and deliver:**

1. **Channel Performance Scorecard**: For each active channel calculate:
   - New customer CAC (excluding returning customer orders)
   - Blended CAC vs. new customer CAC gap (indicates attribution inflation)
   - 90-day and 12-month LTV by acquisition channel
   - True LTV:CAC ratio and payback period in months
   - Contribution margin after COGS, fulfillment, and acquisition cost

2. **Cohort Quality Ranking**: Grade each channel A-D based on:
   - 30/60/90-day repeat purchase rate
   - Average orders per customer in first 12 months
   - Subscription or bundle conversion rate by source
   - Customer churn rate at month 3 and month 6

3. **Attribution Accuracy Assessment**: For each channel estimate:
   - Self-reported ROAS inflation (%) vs. true incremental contribution
   - View-through vs. click-through revenue split
   - Channel position in buyer journey (awareness / mid / lower funnel)
   - Confidence level in data: High / Medium / Low

4. **Budget Reallocation Recommendation**:
   - Which channels to scale (profitable CAC + high LTV cohorts)
   - Which channels to cut or restructure (low LTV:CAC, high attribution inflation)
   - Next 2-3 channels to pilot for diversification
   - 90-day projected impact on blended CAC and new customer volume

Format as an executive dashboard with channel ranking table, attribution risk flags, and a prioritized 90-day action plan with specific dollar amounts and expected outcomes.

## Advanced Customizable Version

ROLE: You are a Chief Analytics Officer specializing in DTC ecommerce customer economics, with deep expertise in multi-touch attribution, marketing mix modeling, incrementality testing, and cohort lifetime value analysis.

CONTEXT:
Brand name: [DTC Brand Name]
Stage: [Early growth $1M-$5M / Scaling $5M-$20M / Established $20M+]
Product category: [e.g., premium nutritional supplements / beauty / pet / apparel]
Business model: [One-time purchase / Subscription / Hybrid with upsell]
Annual revenue: $[X]M
Monthly paid media budget: $[X]
Primary attribution tool: [Northbeam / Triple Whale / Rockerbox / GA4 / None]
Ecommerce platform: [Shopify / WooCommerce / BigCommerce]

CURRENT CHANNEL MIX:
- Meta Ads (Facebook + Instagram): $[X]/month, platform-reported ROAS: [X]x
- Google Ads (Search + Shopping + PMax): $[X]/month, platform-reported ROAS: [X]x
- TikTok Ads: $[X]/month, platform-reported ROAS: [X]x
- Influencer / Creator: $[X]/month, tracked via discount codes / UTMs
- Email marketing (owned): $[X] CPM equivalent value
- SMS marketing (owned): $[X] CPM equivalent value
- Affiliate / Publisher: $[X]/month, reported ROAS: [X]x
- Retail Media (Amazon / Walmart): $[X]/month [if applicable]

CUSTOMER ECONOMICS BASELINE:
- AOV (first order): $[X]
- AOV (repeat orders): $[X]
- Gross margin (post-COGS): [X]%
- Fulfillment + shipping cost: $[X] per order
- Return rate: [X]%
- Target new customer CAC: $[X]
- Actual blended CAC last 30 days: $[X]
- 90-day repeat purchase rate: [X]%
- 12-month LTV estimate: $[X]
- Subscription conversion rate (if applicable): [X]%

KNOWN ATTRIBUTION CHALLENGES:
- iOS 14.5+ signal loss impact: [High / Medium / Low]
- Primary attribution window currently used: [7-day click / 1-day view / 28-day]
- Attribution model: [Last-click / Data-driven / MTA / MMM]
- Key attribution problems you suspect: [e.g., Meta over-attributing, Google Brand inflated]

ANALYTICAL FRAMEWORKS TO APPLY:

Framework 1 — Demand Creation vs. Demand Capture Classification:
Classify each channel by primary job:
- Demand Creation (awareness, prospecting, new audience introduction)
- Demand Capture (intercepting existing intent — Google Search, Shopping, Brand)
- Demand Amplification (retargeting, nurture, win-back)
Different jobs require different ROAS benchmarks. Demand creation channels should be evaluated on 90-day LTV, not 7-day ROAS.

Framework 2 — New Customer ROAS (ncROAS) vs. Blended ROAS:
For each channel, calculate the true new customer contribution:
ncROAS = Revenue from First-Time Buyers Only / Ad Spend Attributed to Channel
Brands with healthy retention should see ncROAS 30-50% below blended ROAS.
If ncROAS is within 10% of blended ROAS, returning customer attribution is minimal.
If ncROAS is 60%+ below blended ROAS, significant returning customer inflation.

Framework 3 — Cohort LTV Progression Model:
Score channels by LTV trajectory at 4 intervals:
- Day 0-30: First repeat purchase rate
- Day 31-90: Cumulative LTV vs. CAC (break-even tracking)
- Day 91-180: Subscription/loyalty conversion (if applicable)
- Day 181-365: 12-month LTV ceiling estimate
Channel grade: A (break-even by Day 90 + 3:1 LTV:CAC) / B (break-even by Day 180 + 2.5:1) / C (marginal) / D (negative cohort economics)

Framework 4 — Attribution Inflation Estimation:
Estimate true incremental contribution before running a formal incrementality test:
- Google Brand Search: Assume 40-70% of conversions are organic demand; test by pausing Brand in low-season week
- Meta: Apply 1.2-1.6x de-inflation multiplier to reported ROAS based on iOS signal loss severity
- Influencer: Discount code captures ~25-40% of real influence; supplement with post-purchase survey ("How did you hear about us?")
- Retargeting (all channels): Assume 20-40% of retargeting conversions are returning customers who would convert anyway; exclude returning customer orders from ROAS denominator

DELIVERABLE 1 — Channel Performance Scorecard (one block per channel):
┌──────────────────────────────────────────────────────────────┐
│ CHANNEL: [Name] | Monthly Spend: $[X]                       │
├──────────────────────────────────────────────────────────────┤
│ Reported ROAS: [X]x | Estimated True Incremental ROAS: [X]x │
│ Blended CAC: $[X] | New Customer CAC (ncCAC): $[X]          │
│ 30-day Repeat Rate: [X]% | 90-day Repeat Rate: [X]%         │
│ 12-month LTV: $[X] | LTV:CAC Ratio: [X]:1                  │
│ Payback Period: [X] months | Contribution Margin: [X]%      │
│ Attribution Confidence: [High/Medium/Low]                    │
│ Scale Headroom: [High/Medium/Low/Saturated]                  │
│ Channel Grade: [A/B/C/D] | Action: [Scale/Hold/Test/Cut]    │
└──────────────────────────────────────────────────────────────┘

DELIVERABLE 2 — Attribution Risk Matrix:
Create a 2x2 matrix plotting each channel on:
- X-axis: Attribution confidence (Low → High)
- Y-axis: Channel importance to revenue (Low → High)
High importance + Low confidence = "Measurement Priority" (run incrementality test immediately)
High importance + High confidence = "Core Channel" (scale based on ncROAS)
Low importance + Low confidence = "Evaluate or Cut"
Low importance + High confidence = "Optimize or Hold"

For each "Measurement Priority" channel, prescribe the specific incrementality test design:
- Test type: Geo holdout / PSA test / Conversion Lift / Ghost bidding
- Geographic markets to use (avoid major metros for cleaner holdout)
- Required holdout budget: $[X] for [X] weeks
- Minimum detectable effect at 80% statistical power
- Decision criteria: If incremental ROAS > $[X] threshold, scale. If below, cut by [X]%.

DELIVERABLE 3 — 12-Month LTV Cohort Projection Table:
Build projected LTV curves by channel (using current cohort data as baseline):

| Channel | CAC | M1 LTV | M3 LTV | M6 LTV | M12 LTV | Break-even | 12-mo ROI |
|---------|-----|--------|--------|--------|---------|------------|-----------|
| Meta    | $XX | $XX    | $XX    | $XX    | $XX     | Month X    | [X]%      |
| Google  | $XX | $XX    | $XX    | $XX    | $XX     | Month X    | [X]%      |
| TikTok  | $XX | $XX    | $XX    | $XX    | $XX     | Month X    | [X]%      |
| Influencer| $XX| $XX   | $XX    | $XX    | $XX     | Month X    | [X]%      |

Highlight: Channels where LTV exceeds CAC by Month 3 (scale immediately), Month 6 (grow steadily), never (cut or restructure).

DELIVERABLE 4 — Budget Reallocation Recommendation:
Current monthly budget allocation: $[X] total
Recommended reallocation in 3 phases:

Phase 1 (Days 1-30 — Immediate optimization):
Move $[X] from [Channel X — reason: poor cohort LTV] → [Channel Y — reason: high LTV:CAC + scale headroom]
Expected impact: Blended CAC decrease from $[X] to $[X] (-[X]%)

Phase 2 (Days 31-60 — Test-informed decisions):
Implement incrementality test results for [Channel X]
If test confirms true ROAS > [X]x: Scale by $[X]/month
If test shows ROAS < [X]x: Cut by $[X]/month, reallocate to [Channel Z]

Phase 3 (Days 61-90 — Diversification):
Launch pilot for [New Channel 1]: $[X] test budget, [X]-week test, success metric: ncCAC < $[X]
Launch pilot for [New Channel 2]: $[X] test budget, success metric: [X]

DELIVERABLE 5 — New Channel Evaluation Shortlist:
For each of the top 3 new channels to test (select from: Connected TV/streaming, Pinterest, Reddit, Direct Mail, SMS acquisition, YouTube organic, Retail Media, Podcast advertising):

For each channel:
- Strategic rationale: Why this channel fits this brand's customer profile
- Audience overlap with existing buyers (estimate % reach of new vs. existing customers)
- Creative requirements and production cost
- Minimum viable test budget for statistical significance
- Attribution methodology (how to measure without relying on platform reporting)
- Benchmark ncCAC range for comparable brands in this category
- Kill criteria: Stop test if ncCAC > $[X] after $[X] spend

DELIVERABLE 6 — 90-Day Performance Marketing Roadmap:

Week 1-2 — Data foundation:
□ Implement UTM parameter standardization across all paid channels
□ Set up Klaviyo profile property to capture first-touch attribution at signup
□ Add post-purchase survey question: "How did you first discover us?" (Kno or Zigpoll)
□ Create Shopify customer tag for acquisition channel (first-order source)
□ Build Triple Whale / Northbeam cohort report filtered to first-time buyers only

Week 3-4 — Immediate optimizations:
□ Pause Google Brand campaigns for 5 days in 2 low-revenue ZIP codes (incrementality signal)
□ Shift Meta from [X]-day to 7-day click / 0-day view attribution window for cleaner signal
□ Create Klaviyo segment: customers acquired via Influencer (highest 90-day repeat rate cohort)
□ Build Lookalike audience of top influencer-acquired customers and launch in Meta prospecting

Month 2 — Incrementality testing:
□ Launch geo holdout test for [Priority Channel]: [X] test markets, [X] holdout markets
□ Run TikTok Conversion Lift Study (available natively in TikTok Ads Manager)
□ Analyze post-purchase survey data: reconcile with platform attribution for each channel

Month 3 — Scale and diversify:
□ Implement budget reallocation based on incrementality test results
□ Launch pilot for [New Channel 1] with $[X] budget
□ Build automated monthly LTV:CAC report in Looker Studio pulling Shopify + ad platforms
□ Present Q1 findings and Q2 budget plan to leadership with incrementality evidence

CONSTRAINTS:
- All recommendations must be actionable with a 2-3 person marketing team (no data science team required)
- Must account for iOS 14.5+ signal loss — no recommendation can rely solely on Meta's reported attribution
- Every budget recommendation must show expected impact on both blended CAC and new customer acquisition volume
- Include specific tool configurations (Triple Whale, Northbeam, Klaviyo, GA4) wherever actionable
- Prioritize decisions that improve LTV:CAC ratio, not just short-term ROAS

OUTPUT FORMAT: Executive-ready analysis with channel scorecard tables, clear grade and action for each channel, and a numbered 90-day action plan with budget amounts, responsible party, and success metric for each step.

## Example Input/Output

**Input Example:**
Brand: Revive Nutrition (DTC performance supplements, mid-scale)
AOV: $72 first order, $68 repeat | Gross margin: 66% | Fulfillment: $8/order
Monthly budget: $85,000 | Attribution tool: Triple Whale
Meta: $42K/month, reported ROAS 2.8x | Google (Search + PMax): $24K/month, reported ROAS 4.3x | TikTok: $11K/month, reported ROAS 1.7x | Influencer: $8K/month via discount codes
90-day repeat rate: 31% | LTV target: $180 at 12 months | Target CAC: $38

**Output Example (abbreviated):**

**Channel Scorecard — Executive Summary:**

| Channel | Spend | Reported ROAS | Est. True ROAS | ncCAC | 90-day Repeat | 12-mo LTV | LTV:CAC | Grade | Action |
|---------|-------|--------------|----------------|-------|--------------|-----------|---------|-------|--------|
| Google Search | $18K | 4.3x | 2.6-3.0x* | $28 | 44% | $214 | 7.6:1 | A | Scale to $24K |
| Google PMax | $6K | 4.3x (blended) | 1.8-2.2x* | $42 | 29% | $158 | 3.8:1 | B | Hold, monitor |
| Meta Prospecting | $32K | 2.8x | 1.9-2.3x** | $48 | 38% | $192 | 4.0:1 | B+ | Scale LAL of influencer cohort |
| Meta Retargeting | $10K | 2.8x (blended) | 0.9-1.3x | $61 | 34% | $175 | 2.9:1 | C | Reduce to $5K |
| TikTok | $11K | 1.7x | 1.4-1.6x | $71 | 22% | $128 | 1.8:1 | D | Cut to $3K test |
| Influencer | $8K | ~2.1x (code-adjusted) | ~3.5-4.0x*** | $38 | 51% | $247 | 6.5:1 | A- | Scale to $12K |

*Google Brand terms estimated at 45% organic demand overlap — running geo holdout test recommended
**Meta ROAS de-inflated by 1.35x for iOS signal loss (High impact classification for supplement category)
***Influencer discount codes capture ~30% of actual purchases; post-purchase survey data shows 3.1x actual attribution vs. 2.1x code-only

**Critical Finding — Influencer Cohort Quality:**
Influencer-acquired customers show the highest 90-day repeat rate (51%) and 12-month LTV ($247) — 29% above brand average. However, discount code attribution captures only ~30% of influenced purchases. Recommendation: Build Meta Lookalike audience from influencer customer list and launch $8K prospecting test targeting similar psychographic profile. Expected ncCAC: $42-$48 with projected 90-day repeat rate of 44-48%.

**Immediate Action (Week 1):**
Reallocate $6K from TikTok (LTV:CAC 1.8:1, poor cohort quality) → $4K to scale influencer budget → $2K to test geo holdout on Google Brand in Portland + Denver markets.

**30-Day Priority:** Launch Northbeam incrementality test for Meta. Allocate $6K holdout budget across 4 southeastern DMAs. Expected true ROAS range: 1.9-2.3x (vs. reported 2.8x). Still profitable at scale — but decision point at Day 21 will inform whether to grow Meta budget to $48K or hold.

**90-Day CAC Impact:** Implementing these recommendations projects blended CAC improvement from $52 to $41 (-21%) while growing new customer volume by approximately 15% through influencer scaling and Google Search expansion.

## Success Metrics

- **Attribution accuracy**: Channel true ROAS estimates align within 20% of incrementality test results
- **Cohort model accuracy**: 12-month LTV projections within 15% of actual cohort data at month 12
- **CAC improvement**: Blended CAC decreases ≥10% within 90 days of implementing reallocation
- **Decision quality**: Every channel recommendation includes specific dollar amounts, timeline, and kill/scale criteria
- **Incrementality test design**: Test achieves 80% statistical confidence with minimum viable budget
- **New customer volume**: ncCAC improvement achieved without reducing absolute new customer acquisition volume

## Related Prompts

- `../../05_Analytics-&-Performance/Ecommerce-&-DTC-Analytics/AI-Powered-DTC-Ecommerce-Revenue-Analytics-&-Customer-Acquisition-Retention-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Ecommerce-&-DTC-Analytics/AI-Powered-DTC-Social-Commerce-&-TikTok-Shop-Creator-Attribution-Analytics-Revenue-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Customer-Lifetime-Value-Analytics/Customer-Lifetime-Value-Prediction-&-Acquisition-Investment-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-(PPC-&-Social)/Cross-Channel-Paid-Media-Budget-Allocation-&-ROAS-Optimization-Engine.md`

## Integration Tips

- **Triple Whale**: Use Triple Whale's "New Customer ROAS" toggle in the Attribution tab (not default blended ROAS) — this is the most accurate first-party signal. Connect Shopify customer tag (acquisition channel) to build cohort LTV reports by source
- **Northbeam**: Use Northbeam's Media Mix Modeling module before running a formal holdout test — it surfaces channels with suspected attribution inflation without requiring spend pauses. Export channel-level efficiency curves to identify true scale headroom
- **Klaviyo**: Capture first-touch UTM source as a Klaviyo profile property using Klaviyo Forms hidden fields or a post-opt-in webhook. Build segments by acquisition channel to track email engagement and repeat purchase rates by source
- **GA4**: Set up GA4 Explorations cohort report filtered to "first purchase" events by session source/medium. Combine with Shopify's customer acquisition report for reconciliation — platform data vs. first-party Shopify data gap reveals attribution inflation magnitude
- **Kno / Zigpoll (Post-Purchase Survey)**: Install post-purchase survey asking "How did you first hear about us?" with channel options. Supplement with "What almost stopped you from purchasing?" for barrier identification. Export monthly to reconcile influencer, podcast, and word-of-mouth channels that platform tracking systematically under-counts
- **Looker Studio**: Build an automated monthly LTV:CAC dashboard connecting Shopify Orders API (filtered by first-order customer tag) + Meta Ads API + Google Ads API + email platform API. Refresh weekly. Available as a template in Looker Studio Community Gallery (search "DTC cohort LTV dashboard")
- **Rockerbox**: For brands managing 5+ paid channels, Rockerbox's unified first-party measurement reconciles platform-reported data against actual Shopify orders. Particularly valuable for Google/Meta overlap quantification

## Troubleshooting

**Problem: Platform-reported ROAS looks strong (3x+) but brand profitability is declining quarter-over-quarter.**
Solution: Classic "attribution inflation compounding" — platforms are taking credit for organic demand and each other's influenced purchases. Run a 2-week paused brand keyword test in 2 mid-sized DMAs. If organic orders don't drop proportionally, Google Brand is over-attributed (typically 40-70% of Brand conversions are organic demand in supplement/beauty categories). Simultaneously, install a post-purchase survey (Kno is fastest to implement) to capture self-reported attribution as a ground-truth benchmark. Expect to find 20-30% of "Meta-attributed" customers actually discovered the brand via influencer, word of mouth, or organic social.

**Problem: TikTok ROAS looks poor at 1.5-2x but creative team believes it's driving significant brand awareness.**
Solution: TikTok's demand creation role is systematically undervalued by last-click models. Run this test: Compare Google Search branded query volume in the 2 weeks following a TikTok campaign spike vs. baseline weeks. A meaningful correlation (15%+ branded search lift) indicates TikTok is generating demand that Google Search is later capturing and taking credit for. If correlation exists, evaluate TikTok on a "halo-adjusted ROAS" that accounts for the incremental Google branded searches driven. This typically increases true TikTok contribution by 40-80% above reported ROAS.

**Problem: Influencer discount code tracking shows only 1.2x ROAS, which looks unprofitable.**
Solution: Discount codes capture ~25-35% of actual influenced purchases for mid-funnel influencer content. Customers watch, consider for days or weeks, then purchase without the code (used a different browser, forgot the code, or searched organically). Triangulate with three data sources: (1) Post-purchase survey % selecting "social media / influencer" as first discovery source, (2) Branded search volume lift during influencer campaign periods, (3) Direct traffic spike in the 72 hours post-post. Combining these typically reveals true influencer contribution is 2.5-4x what discount codes report. If cohort data shows influencer-acquired customers have higher repeat rates (common — they buy based on identity alignment, not price promotion), justify scaling based on LTV:CAC, not first-order ROAS alone.

## Version History
- v1.0: Initial creation (auto-generated)
