# Amazon Ads Performance Analytics & Retail Media Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** amazon-ads, retail-media, sponsored-products, sponsored-brands, sponsored-display, dsp, acos, tacos, roas, d2c, cpg, e-commerce, search-term-analytics, retail-media-network

## Overview
Diagnoses Amazon Ads account performance across Sponsored Products, Sponsored Brands, Sponsored Display, and DSP — surfacing wasted spend patterns, search term cannibalization, keyword bid inefficiencies, ACOS runaway, and organic rank suppression signals — so an AI agent can produce a prioritized optimization brief ready for immediate execution by an Amazon PPC manager or brand growth team.

## Quick Copy-Paste Version

You are a senior Amazon Ads performance analyst specializing in retail media optimization and marketplace revenue growth. Analyze the following Amazon Ads data and produce a complete optimization brief.

Account context: [Paste your Amazon Ads bulk report export, Search Term Report, or describe key metrics below]

Analyze and deliver:

1. SPONSORED PRODUCTS DIAGNOSIS
- Top and bottom 10 keywords by ACOS — flag any keyword with ACOS >3x your target ACOS
- Search Term Report audit: Identify converting search terms not yet added as exact-match keywords (harvesting opportunities)
- Identify search terms burning spend with zero conversions in the last 30 days — immediate negative keyword candidates
- Match type efficiency: Broad vs Phrase vs Exact — which match type delivers the best ACOS per campaign?
- Auto vs Manual campaign performance: Are auto campaigns discovering profitable terms that manual campaigns should capture?

2. CAMPAIGN STRUCTURE & BUDGET EFFICIENCY
- Budget utilization: Which campaigns are hitting daily budget caps before 6PM in primary timezone? Flag as revenue-limiting
- Bid landscape: Identify keywords where your bid is >50% below first-page bid estimate — calculate revenue opportunity cost
- Campaign-level ACOS vs TACoS (Total Advertising Cost of Sale): Flag any ASIN where advertising spend represents >30% of total revenue
- Dayparting opportunities: Hour-of-day and day-of-week conversion rate patterns — where can budget be concentrated?
- Portfolio-level budget: Are profitable campaigns being starved of budget while losing campaigns overspend?

3. SPONSORED BRANDS & VIDEO PERFORMANCE
- Branded keyword defense: Is your brand name protected? What is competitor ACOS on your branded terms?
- Video ad hook rate: What percentage of video viewers watch past 5 seconds? Flag videos with <40% retention
- Custom image headline ads vs standard Sponsored Brands: Which format drives lower CPC and higher CVR?
- Category-level conquesting: Which competitor branded campaigns have ACOS below target — scale opportunities?

4. SPONSORED DISPLAY & DSP (if applicable)
- Audience retargeting performance: Purchased vs viewed vs browsed audiences — ACOS ranked best to worst
- Product targeting: Which competitor ASINs and categories drive the most efficient retargeting?
- DSP view-through attribution: Flag if DSP view-through conversions represent >40% of reported DSP revenue (potential attribution inflation)
- Off-Amazon audience performance (DSP): Which audience segments drive the strongest new-to-brand (NTB) purchase rate?

5. PRODUCT & ORGANIC RANK HEALTH
- ASIN-level advertising suppression check: Are any high-spend ASINs losing organic rank despite strong ad spend? (Ad-organic cannibalization signal)
- Buy Box win rate by ASIN — flag any ASIN with Buy Box win rate <85% (spend waste risk)
- New-to-Brand (NTB) metrics: What percentage of your Sponsored Brands and DSP purchases are NTB? (Benchmark: >50% for growth brands)
- Inventory health: Flag any ASIN with <14 days of inventory that is currently receiving significant ad spend — pause risk

6. PRIORITIZED ACTION PLAN
Produce a ranked list of 5-10 specific actions with:
- Action description (specific, immediately executable)
- Expected impact (High/Medium/Low) with estimated ACOS improvement or revenue lift %
- Implementation effort (Hours/Days)
- Owner: PPC Manager / Brand Manager / Creative Team / Supply Chain

Format output as a structured brief suitable for a Notion doc, Linear ticket, or Amazon agency weekly standup.

## Advanced Customizable Version

ROLE: You are a senior Amazon Ads performance analyst with 10+ years specializing in retail media optimization, marketplace growth strategy, and multi-channel e-commerce for [BUSINESS_TYPE: D2C brand / CPG enterprise / private label seller / Amazon-first brand / omnichannel retailer]. You combine deep Amazon Ads Console platform expertise with organic rank mechanics, retail fundamentals, category dynamics, and a margin-first analytical framework. Every recommendation must tie to ACOS efficiency, TACoS reduction, NTB customer acquisition, or organic rank improvement — never vanity metrics like raw impressions or click volume.

ACCOUNT CONTEXT:
- Brand/Seller: [BRAND_NAME] — [brief product category and ASINs: e.g., "premium whey protein supplements, 12 parent ASINs, 47 child ASINs"]
- Seller type: [1P Vendor / 3P Seller / Hybrid]
- Monthly Amazon ad spend: $[MONTHLY_SPEND]
- Target ACOS: [TARGET_ACOS]% | Current blended ACOS: [CURRENT_ACOS]%
- Target TACoS: [TARGET_TACOS]% | Current TACoS: [CURRENT_TACOS]%
- Primary product category: [CATEGORY] — average order value: $[AOV]
- Campaign types running: [Sponsored Products / Sponsored Brands / Sponsored Brands Video / Sponsored Display / DSP / AMC]
- Attribution model: [Amazon Last Touch / Amazon Attribution / AMC multi-touch]
- Third-party tools: [Helium 10 / Jungle Scout / Scale Insights / Perpetua / Pacvue / Intentwise / None]
- Amazon marketplace(s): [US / UK / EU / JP / etc.]
- Competitive context: [Highly competitive branded category / emerging category / niche with limited competition]
- Organic rank baseline: [Average organic rank for your top 5 head terms]

PERFORMANCE DATA:
[Paste your Amazon Ads bulk performance report, or provide the following manually:]
- Campaign names, types, spend, impressions, clicks, CTR, CPC
- Orders, revenue, ACOS, ROAS by campaign and ad group
- Search Term Report: search term, match type, impressions, clicks, spend, orders, ACOS
- Keyword-level performance: bid, impressions, clicks, spend, orders, ACOS, suggested bid
- ASIN-level: ad spend, ad revenue, ACOS, total ASIN revenue, TACoS, organic rank (if available)
- Portfolio-level: daily budget, total spend, total revenue
- Sponsored Display or DSP: audience type, spend, attributed revenue, NTB%, view-through conversions

ANALYSIS FRAMEWORK — deliver all 8 modules:

MODULE 1: SEARCH TERM INTELLIGENCE & KEYWORD ARCHITECTURE
- Mine the Search Term Report for: (a) profitable converting terms not yet added as exact-match targets, (b) zero-conversion spend wasters for immediate negation, (c) high-impression/zero-click terms indicating a listing content gap
- Keyword cannibalization audit: Are the same search terms appearing in multiple campaigns/ad groups, creating internal bid competition?
- Match type pyramid health: Is budget appropriately weighted toward exact-match (highest intent) vs broad (discovery)? Recommended ratio: 60% exact / 25% phrase / 15% broad
- Long-tail opportunity mapping: Identify 3-5 word search terms with <5 competitors and >2% conversion rate — these are low-competition, high-conversion gems to aggressively target
- Seasonal intent shifts: Flag any top-20 keywords showing >25% search volume change month-over-month — adjust bids proactively

MODULE 2: BID OPTIMIZATION & BUDGET ALLOCATION
- Keyword-level bid analysis: For each keyword, compare your current bid to (a) first-page bid estimate, (b) top-of-page bid estimate, (c) product page bid estimate — calculate gap and revenue opportunity cost for each tier
- Dayparting analysis: Hour-of-day and day-of-week breakdown of CVR and ACOS — recommend bid adjustments and budget concentration windows
- Budget pacing audit: Identify the exact campaigns hitting daily budget caps and at what hour — calculate estimated daily revenue opportunity loss
- Portfolio budget redistribution: Rank all portfolios by ACOS efficiency — recommend shifting $X from the lowest-performing portfolio to the top-performing portfolio with headroom
- Rule-based automation triggers: Define specific bid rules for [Scale Insights / Perpetua / Pacvue / manual] — e.g., "if ACOS <15% for 7 days, increase bid 15%; if ACOS >35% for 3 days, decrease bid 20%"

MODULE 3: SPONSORED BRANDS & VIDEO STRATEGY AUDIT
- Brand defense audit: Query your brand name, brand + product variants, and brand + category terms — are competitors outbidding you on your own brand? Calculate brand defense gap
- Video creative performance: Hook rate (5-second retention), full-view rate, CVR for each video ad — identify creative fatigue (>21 days running with declining CTR)
- Headline and creative testing: Which headline copy combinations (product benefit vs social proof vs urgency) produce the lowest CPC and highest CVR?
- Custom image ad performance vs standard Sponsored Brands: Quantify the CPC and CVR difference
- Category-level conquesting effectiveness: For your top 5 competitor ASIN targets in Sponsored Brands — what is your win rate and ACOS?

MODULE 4: SPONSORED DISPLAY & DSP ATTRIBUTION DEEP DIVE
- Audience funnel performance: Purchased (365d) vs Purchased (30d) vs Cart Abandon vs Product Detail View audiences — ACOS and NTB% per audience segment
- Product targeting audit: Top 10 competitor ASINs being targeted by Sponsored Display — rank by ACOS and click-to-conversion rate
- DSP audience architecture: Describe the full DSP audience funnel from awareness to retargeting — identify any funnel gaps
- Attribution inflation check: Calculate DSP view-through conversion rate — if view-through represents >40% of DSP revenue, run a holdout test to validate true incrementality
- Amazon Marketing Cloud (AMC) integration: If AMC is available, identify the path-to-purchase sequence with highest conversion rate — which ad type serves best at each funnel stage?

MODULE 5: PRODUCT & LISTING HEALTH INTEGRATION
- Buy Box ownership: For each actively advertised ASIN, report Buy Box win % — flag any ASIN with <85% win rate receiving >$500/month in ad spend (high waste risk)
- Organic rank tracking: For your top 10 head terms, is organic rank improving, stable, or declining despite ad investment? (Declining organic rank with high ad spend = ad-organic cannibalization or listing quality issue)
- Listing quality score: Flag ASINs with: <1,000 reviews, <4.2 star average, images <7, no A+ content, no video content — these ASINs should receive reduced ad spend until listing is fixed
- Inventory risk management: Flag any ASIN projected to reach <14 days of inventory within the next 21 days that is currently receiving significant ad spend — recommend spend pause trigger thresholds
- Price competitiveness: For top 10 ASINs, compare your price vs the category average price — are you competitively priced to make ad spend efficient?

MODULE 6: NEW-TO-BRAND & CUSTOMER ACQUISITION ANALYSIS
- NTB rate by campaign type: Sponsored Products vs Sponsored Brands vs Sponsored Display vs DSP — which drives the most new customers?
- NTB ACOS: Calculate separate ACOS for NTB vs repeat purchases — is your customer acquisition cost acceptable given your LTV?
- Repeat purchase rate from Amazon ads: Of customers acquired via Amazon Ads in the past 90 days, what % returned to purchase again? (Amazon Brand Analytics if available)
- Category and competitor conquesting NTB efficiency: Which competitor ASIN targets and category targets produce the highest NTB%?
- Subscription (Subscribe & Save) conversion: What % of ad-driven buyers subscribe? Flag opportunities to optimize product page for S&S conversion

MODULE 7: COMPETITIVE & CATEGORY INTELLIGENCE
- Share of Voice (SOV) estimation: For your top 5 head terms, estimate your impression share vs category leaders (use impression data from Search Term Report and Auction Insights if available)
- Category average CPC trends: Is CPC rising quarter-over-quarter in your category? Flag as a signal to invest in organic rank and content-led demand to reduce paid dependence
- Competitor new product launches: Flag any new competitor ASINs with rapid review accumulation in your category — potential threat requiring defensive Sponsored Display investment
- Brand Analytics data integration: If Brand Analytics is available, pull Repeat Purchase Rate, Market Basket Analysis, and Demographics to inform bid strategy and audience targeting

MODULE 8: FULL OPTIMIZATION BRIEF — PRIORITIZED 90-DAY ROADMAP
Deliver a structured three-horizon optimization plan:

WEEK 1-2 (IMMEDIATE — STOP THE BLEEDING):
- List 3-5 actions that eliminate wasted spend immediately
- Each action: specific keyword/campaign/setting, expected ACOS impact, time to implement

WEEK 3-6 (OPTIMIZATION — IMPROVE EFFICIENCY):
- List 5-8 actions that improve conversion rates and bid efficiency
- Include specific bid rule configurations, match type restructuring steps, or creative rotation plans

MONTH 2-3 (GROWTH — SCALE WHAT WORKS):
- List 3-5 actions to aggressively scale highest-performing campaigns
- Include NTB customer acquisition tactics, new keyword expansion territories, and DSP audience scaling plans

OUTPUT FORMAT:
Produce a structured brief formatted for direct import into [Notion / Confluence / Google Docs] with clear section headers, bullet points, and an executive summary table showing: current ACOS, target ACOS, estimated ACOS improvement from implementing all recommendations, estimated monthly revenue opportunity, and top 3 highest-impact immediate actions.

## Example Input/Output

**Input Example:**

Business: NutriForge — premium creatine monohydrate supplements (3 parent ASINs, 9 child ASINs)
Monthly spend: $42,000 | Current ACOS: 31% | Target ACOS: 22% | TACoS: 18%
Top campaigns: SP-Auto-Creatine ($8,200/mo, ACOS 28%), SP-Manual-Exact-Creatine ($14,100/mo, ACOS 24%), SP-Manual-Broad-Discovery ($6,800/mo, ACOS 41%), SB-Brand-Defense ($4,200/mo, ACOS 18%), SD-Competitor-Retargeting ($5,100/mo, ACOS 39%)
Search Term Report: "creatine monohydrate" (1,420 clicks, $3,800 spend, 89 orders, ACOS 22%), "best creatine" (880 clicks, $2,100 spend, 31 orders, ACOS 35%), "creatine powder unflavored" (340 clicks, $890 spend, 0 orders — no conversions)
Buy Box: 94% on ASIN-A, 71% on ASIN-B (pricing issue — competitor $4 cheaper), 99% on ASIN-C
Inventory: ASIN-A at 9 days stock, ASIN-B at 45 days, ASIN-C at 31 days

**Output Example:**

---
**NUTRIFORGE AMAZON ADS OPTIMIZATION BRIEF — MARCH 2026**
**Executive Summary:** Current blended ACOS 31% → Projected ACOS 22.4% within 60 days. Estimated monthly revenue recovery: +$18,200. Monthly wasted spend identified: $9,100.

**TOP 3 IMMEDIATE ACTIONS:**
1. 🚨 PAUSE all ad spend on ASIN-A immediately — 9 days inventory with $14,000/month spend risks stockout during optimization; losing BSR rank will cost more than 2 weeks of paused revenue
2. ❌ NEGATIVE MATCH "creatine powder unflavored" across all campaigns — 340 clicks, $890 spend, $0 revenue; add as exact-match negative today
3. ⬆️ ADD "best creatine" as Exact Match in SP-Manual-Exact campaign with $2.40 bid (currently only in broad) — converts at 3.5% with room to scale to $5,000/month at 28% ACOS before hitting diminishing returns

**MODULE 1 — SEARCH TERM INTELLIGENCE:**
Harvesting opportunities found: 14 converting search terms in SP-Auto not yet added to SP-Manual-Exact. Top opportunity: "creatine monohydrate micronized" — 67 clicks, 8 orders, ACOS 19% — add as exact match at $2.10 bid with $800/month budget allocation.

Zero-conversion spend wasters (30 days): 23 search terms, total waste: $4,200. Top 5 to negative immediately: "creatine tablets" ($620 spend, 0 orders), "creatine gummies" ($410 spend, 0 orders), "creatine monohydrate pills" ($380 spend, 0 orders)...

**MODULE 2 — BID & BUDGET OPTIMIZATION:**
SP-Manual-Exact-Creatine hitting daily budget cap at 2:17PM EST on average. Cap increase from $470/day to $680/day estimated to recover $3,800/month in revenue at current 24% ACOS.

ASIN-B Buy Box at 71% — recommend price drop of $3.50 (from $34.99 to $31.49) to recapture Buy Box; at current ad spend, Buy Box loss is wasting ~$1,800/month in clicks that convert for competitors...
---

## Success Metrics

- ACOS within target range (your defined target) within 30-60 days of implementing recommendations
- TACoS trending down quarter-over-quarter as organic rank improves
- Search Term Report waste (zero-conversion spend) reduced by >50% within 2 weeks of negation actions
- Budget utilization: High-efficiency campaigns no longer hitting daily budget caps before 3PM
- NTB rate >40% for Sponsored Brands and DSP campaigns
- Buy Box win rate >90% on all actively advertised ASINs
- Keyword harvest rate: >3 new exact-match keywords added per week from auto campaign discovery

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-(PPC-&-Social)/Amazon-Ads-Campaign-Builder.md`
- `../../05_Analytics-&-Performance/Paid-Media-&-PPC-Performance-Analytics/Google-Ads-Performance-Analytics-&-Search-Intent-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Paid-Media-&-PPC-Performance-Analytics/Cross-Channel-Paid-Media-Budget-Allocation-&-ROAS-Optimization-Engine.md` (if it exists)
- `../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md`

## Integration Tips

- **Helium 10 / Jungle Scout:** Export Search Term Report, Keyword Tracker, and Market Tracker data directly into the Advanced Version context window. Use Helium 10 Cerebro for reverse-ASIN keyword harvesting to supplement Amazon's own data.
- **Perpetua / Pacvue / Scale Insights:** Use the optimization brief's bid rule recommendations to configure automation rules directly in your bid management platform. Map each recommendation to a rule trigger (ACOS threshold, impression threshold, days-active threshold).
- **Amazon Marketing Cloud (AMC):** Connect AMC for path-to-purchase SQL queries — ask Claude to write the AMC SQL query for multi-touch attribution across Sponsored Products, Sponsored Brands, and DSP touchpoints.
- **Google Sheets / Looker Studio:** Paste the bulk performance report CSV into Google Sheets; use the analysis output to build a weekly ACOS dashboard. Ask Claude to generate the Google Sheets formula logic for automated ACOS alerts.
- **Slack / Zapier automation:** Set up a weekly Zapier zap that exports your Amazon Ads report, pastes it into this prompt via Claude API, and delivers the optimization brief to your #amazon-ads Slack channel every Monday morning.
- **Notion:** The output brief is structured for direct copy-paste into a Notion database as a weekly PPC review template. Create a recurring template that captures weekly ACOS trend alongside the AI brief.

## Troubleshooting

- **Problem:** Amazon's Search Term Report only shows 30 days of data and misses seasonal trends.
  **Solution:** Run this prompt monthly and maintain a running Google Sheet with cumulative Search Term data. Ask Claude to compare current month vs prior 3-month average to identify trending or declining terms that a single 30-day window would miss.

- **Problem:** DSP view-through attribution inflates revenue numbers and makes ROI look artificially strong.
  **Solution:** In the Advanced prompt, explicitly instruct Claude to calculate two versions of DSP ROAS: (1) click-through only and (2) including 14-day view-through. If view-through represents >40% of attributed revenue, flag as unvalidated and recommend a holdout test via Amazon's incrementality measurement tool before scaling DSP budget.

- **Problem:** The optimization brief recommends raising bids on keywords that have high ACOS historically, but the account is in a competitive Q4 season.
  **Solution:** Add seasonal context to the Account Context section — specify the current season, competitor promotional activity, and your inventory position. This will cause Claude to modulate bid recommendations based on seasonal elasticity rather than applying flat ACOS rules.

## Version History
- v1.0: Initial creation (auto-generated)
