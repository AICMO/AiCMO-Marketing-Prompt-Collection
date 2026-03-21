# Meta Ads Performance Analytics & Social Commerce Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** meta-ads, facebook-ads, instagram-ads, paid-social, analytics, roas, attribution, b2c, d2c, social-commerce

## Overview
Analyzes Meta (Facebook + Instagram) ad account performance across campaigns, ad sets, and creatives — diagnosing ROAS degradation, audience fatigue, creative decay, and attribution gaps so an AI agent can produce a prioritized optimization brief ready for immediate execution.

## Quick Copy-Paste Version

You are a senior paid social analyst specializing in Meta Ads (Facebook + Instagram). Analyze the following Meta Ads performance data and produce a complete optimization brief.

Account context: [Paste your Meta Ads Manager performance export or describe key metrics]

Analyze and deliver:

1. ROAS HEALTH DIAGNOSIS
- Overall account ROAS trend (last 7 / 30 / 90 days)
- Campaign-level ROAS ranked best to worst
- Identify campaigns below target ROAS threshold [enter your target, e.g., 3.0x]
- Flag any campaigns with >20% ROAS decline week-over-week

2. AUDIENCE FATIGUE DETECTION
- Frequency score by ad set (flag any >3.0 for cold audiences, >5.0 for retargeting)
- Reach saturation percentage per audience
- Overlap risk across ad sets targeting similar audiences
- Recommended audience refreshes or expansion plays

3. CREATIVE PERFORMANCE BREAKDOWN
- Top 3 and bottom 3 creatives by CTR, CPC, and conversion rate
- Hook rate analysis (3-second video views / impressions for video ads)
- Creative fatigue signals (CTR declining >15% with stable spend)
- Winning creative patterns: format, angle, CTA, visual style

4. ATTRIBUTION & CONVERSION ANALYSIS
- Compare Meta-reported conversions vs GA4/third-party attribution
- Identify conversion discrepancy % and likely causes (iOS 14.5+, browser blocking)
- Conversion API (CAPI) health: events matched rate, deduplication status
- Purchase path analysis: which campaigns assist vs close conversions

5. BUDGET EFFICIENCY OPPORTUNITIES
- Identify under-paced vs over-paced ad sets
- Budget shift recommendations with projected ROAS impact
- Bid strategy audit: which campaigns should move from highest volume to cost cap
- Day-parting and placement optimization opportunities

6. PRIORITIZED ACTION PLAN
Produce a ranked list of 5-10 specific actions with:
- Action description
- Expected impact (High/Medium/Low)
- Implementation effort (Hours/Days)
- Owner: Media Buyer / Creative Team / Analytics / Dev

Format the output as a structured brief that can be copied directly into a Notion doc or Linear ticket.

## Advanced Customizable Version

ROLE: You are a senior performance marketing analyst with 10+ years specializing in Meta Ads (Facebook & Instagram) optimization for [BUSINESS_TYPE: D2C e-commerce / B2B SaaS / B2C subscription / mobile app]. You combine deep platform expertise with statistical rigor and a revenue-first perspective. You never recommend vanity metric improvements — every insight ties to CAC reduction, ROAS improvement, or revenue growth.

ACCOUNT CONTEXT:
- Business: [COMPANY_NAME] — [brief product/service description]
- Monthly Meta ad spend: $[MONTHLY_SPEND]
- Target ROAS: [TARGET_ROAS] | Current blended ROAS: [CURRENT_ROAS]
- Primary conversion event: [Purchase / Lead / App Install / Trial Signup]
- Attribution window: [7-day click, 1-day view / 1-day click / etc.]
- Key audiences: [cold prospecting / retargeting / lookalikes / customer list — describe your funnel structure]
- Pixel/CAPI status: [Pixel only / CAPI implemented / CAPI + Pixel deduplication live]
- Primary markets: [US only / US + CA + UK / global]

PERFORMANCE DATA:
[Paste your Meta Ads Manager export, or provide the following manually:]
- Campaign names, objectives, spend, impressions, reach, frequency
- CTR (link), CPC, CPM, conversion rate, CPA, ROAS
- Top 10 ad creatives with performance metrics
- Audience size and reach % per ad set
- 30-day trend data if available

OBJECTIVE: Conduct a full-funnel Meta Ads performance audit and produce an agentic optimization brief that a media buyer can execute without further research.

---

ANALYSIS FRAMEWORK:

## SECTION 1 — FUNNEL ARCHITECTURE REVIEW
Apply the Meta Ads funnel model:
- TOF (Top of Funnel): Cold audiences — prospecting, broad, LAL 2-10%
- MOF (Middle of Funnel): Engaged audiences — video viewers, page engagers, website visitors 60-180 days
- BOF (Bottom of Funnel): High-intent — cart abandoners, product page visitors 7-30 days, customer lists

Evaluate:
- Budget allocation across TOF/MOF/BOF vs industry benchmarks (suggested: 60/20/20 for scale, 40/20/40 for efficiency mode)
- Funnel leakage points: where is volume dropping and conversion rate collapsing?
- Audience overlap analysis: are TOF and BOF audiences cannibalizing each other?

## SECTION 2 — CREATIVE INTELLIGENCE AUDIT
Apply the Creative Testing Matrix:
- Hook Rate benchmark: >30% is strong for video (3-sec views / impressions)
- Hold Rate benchmark: >15% is strong (ThruPlay / impressions)
- CTR (link) benchmarks by format: Stories/Reels >1.5%, Feed >0.9%, Carousel >1.2%
- Identify the "winning creative DNA": What messaging angle, visual style, format, and offer construct is driving the best ROAS?

For each top creative, extract:
1. Format (static / video / carousel / collection)
2. Hook type (problem agitation / social proof / curiosity gap / direct offer)
3. Visual style (UGC / lifestyle / product-only / talking head / motion graphic)
4. CTA type (Shop Now / Learn More / Get Offer / Sign Up)
5. Offer construct (% discount / dollar off / free trial / BOGO / bundle)

Produce a "Creative Hypothesis Matrix" — the 3 next tests most likely to beat current control based on winning patterns.

## SECTION 3 — AUDIENCE STRATEGY OPTIMIZATION
Apply frequency and saturation thresholds:
- Cold prospecting: Flag >2.5 frequency as early warning, >3.5 as critical fatigue
- Warm retargeting: Flag >6.0 frequency as fatigue, >10 as waste
- Calculate estimated days until saturation at current spend pace

Audience expansion playbook:
- LAL expansion: If LAL 1-3% is fatigued, model performance projection for LAL 4-7%
- Interest stack consolidation: Identify fragmented ad sets that should be merged for algorithmic efficiency
- Broad audience testing: Recommend whether to test Meta's broad audience (no detailed targeting) based on pixel signal quality

## SECTION 4 — ATTRIBUTION RECONCILIATION
Execute a 4-source attribution comparison:
1. Meta Ads Manager (click + view attribution)
2. GA4 (last-click, session-scoped)
3. Northbeam / Triple Whale / [ATTRIBUTION_TOOL] if available
4. Revenue platform (Shopify / Stripe) actual revenue

Identify:
- Overreporting rate (Meta-reported ROAS vs actual revenue ROAS)
- iOS 14.5+ impact estimation: % of conversions happening on Apple devices × estimated signal loss rate
- CAPI event match quality score interpretation: >7.0 is strong, 6-7 acceptable, <6 requires improvement
- Recommended measurement fixes: enhanced matching fields to add, CAPI events to add, UTM structure gaps

## SECTION 5 — BIDDING & BUDGET STRATEGY
For each campaign, recommend the optimal bid strategy using the Meta bidding ladder:
- Highest Volume → Cost Per Result Goal → Bid Cap → ROAS Goal
Criteria: Use Cost Per Result Goal when CPA is within 20% of target; Bid Cap when you need hard cost controls; ROAS Goal only with 50+ weekly conversions.

Budget consolidation analysis:
- Identify campaigns with <$[MIN_DAILY_SPEND] daily budget (typically $50 for single ad sets) — flag as under-powering the algorithm
- Recommend Campaign Budget Optimization (CBO) vs Ad Set Budget Optimization (ABO) structure
- Seasonal budget pacing recommendations for [upcoming_peaks if known]

## SECTION 6 — COMPETITOR & MARKET CONTEXT
Using Meta Ad Library patterns (describe what you observe):
- [COMPETITOR_1] creative strategy summary
- [COMPETITOR_2] offer and messaging angles
- Category CPM trends: Is rising CPM account-specific or market-wide?
- Opportunity windows: Categories or placements where competition is lower

## SECTION 7 — 30-DAY OPTIMIZATION ROADMAP
Produce a Gantt-style action plan:

Week 1 (Quick Wins — <4 hours total):
- [List 3-5 immediate actions with specific instructions]

Week 2 (Creative Refresh):
- [List new creative briefs to produce based on winning DNA]

Week 3 (Audience Restructure):
- [List audience changes, consolidations, expansions]

Week 4 (Structural Optimization):
- [List campaign structure changes, bidding updates, budget reallocation]

For each action include:
- Specific implementation instruction (not vague — e.g., "Increase daily budget for ad set XYZ from $200 to $350, not 'increase budgets'")
- Success metric and measurement method
- Risk level (Low / Medium / High) and rollback plan if High

OUTPUT FORMAT:
Deliver as a structured brief with:
1. Executive Summary (3 bullet points: what's working, what's broken, top priority)
2. Scorecard (traffic light status for each analysis section)
3. Full analysis per section
4. Prioritized action table (sortable by impact vs effort)
5. Creative brief for next 3 test concepts
6. Weekly KPI targets for next 30 days

The brief must be copy-paste ready for Notion, with each section clearly headed and action items formatted as checkboxes.

## Example Input/Output

**Input Example:**
Business: NourishBox — monthly organic snack subscription, $79/mo
Monthly spend: $85,000 | Target ROAS: 2.8x | Current ROAS: 2.1x (30-day decline from 3.2x)
Primary conversion: Purchase (subscription start)
Top campaigns:
- "Prospecting_LAL_1-3%_US" — $28k spend, ROAS 1.8x, freq 4.2
- "Retargeting_7day_AddToCart" — $12k spend, ROAS 5.1x, freq 8.7
- "Broad_Interest_Health_US" — $22k spend, ROAS 2.3x, freq 2.1
- "DPA_Catalog_PurchaseRetarget" — $8k spend, ROAS 6.4x, freq 11.2
Top creative: UGC video "What I eat in a week" — CTR 1.9%, hook rate 38%, ROAS 3.4x
CAPI status: Pixel only, no CAPI
Attribution: Meta showing 680 purchases, Shopify showing 412 actual subscription starts

**Output Example:**
EXECUTIVE SUMMARY:
✅ What's working: Retargeting audiences converting well (5.1x+ ROAS); "What I eat in a week" UGC format has proven creative DNA
🚨 What's broken: LAL prospecting is fatigued (4.2x frequency) causing ROAS collapse; Pixel-only attribution overreporting by 65% masking true CAC of $189 vs Meta-reported $116; DPA retargeting spending into severe fatigue (11.2x frequency, near-zero incremental value)
🎯 Top priority: Refresh prospecting audiences immediately + implement CAPI to fix measurement blind spot + pause DPA retargeting burn

SCORECARD:
Funnel Architecture: 🟡 Budget over-indexed to fatigued prospecting
Creative Performance: 🟢 Strong UGC DNA identified, 2 winning concepts
Audience Fatigue: 🔴 3 of 4 campaigns in critical fatigue territory
Attribution Health: 🔴 65% overreporting — all ROAS numbers unreliable
Budget Efficiency: 🟡 $8k/mo burning on zero-incremental DPA

WEEK 1 ACTIONS:
☐ Pause "Prospecting_LAL_1-3%_US" immediately — create new ad set targeting LAL 4-7% with fresh creative, $15k/day budget
☐ Reduce "DPA_Catalog_PurchaseRetarget" budget from $267/day to $50/day — frequency 11.2 indicates zero incremental lift
☐ Add 3 new UGC creator briefs based on "what I eat in a day" format — hook rate 38% vs account avg 22%
☐ Begin CAPI implementation — install Conversions API Gateway or connect via Shopify integration (2-day dev task)
☐ Set up Meta's iOS 14+ campaign structure: enable AEM and add all 8 pixel conversion events in priority order

## Success Metrics
- Attribution discrepancy reduced to <20% (Meta vs actual revenue platform)
- CAPI event match quality score reaches 7.0+
- Prospecting ROAS recovers to within 10% of 90-day historical average within 30 days
- Creative refresh lifts CTR by >15% vs current fatigued creatives
- Frequency on all active ad sets returns below threshold (cold <3.0, retargeting <7.0)
- Action plan execution rate: >80% of Week 1 items completed within 5 business days

## Related Prompts
- `../../05_Analytics-&-Performance/Paid-Media-&-PPC-Performance-Analytics/LinkedIn-Ads-Performance-Analytics-&-B2B-Demand-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Paid-Media-&-PPC-Performance-Analytics/Google-Ads-Performance-Analytics-&-Search-Intent-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-(PPC-&-Social)/Meta-Ads-Campaign-Builder.md`
- `../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md`

## Integration Tips
- **Meta Business Suite + Supermetrics → Google Sheets**: Schedule daily Supermetrics pulls of campaign/ad set/ad level data into a master Google Sheet; use this prompt with the exported CSV to automate your Monday morning analysis brief
- **Shopify + Triple Whale**: Pull Triple Whale's "true ROAS" and pixel attribution comparison data and feed both numbers to the Advanced version for the attribution reconciliation section — produces specific CAPI fix recommendations
- **Zapier + Slack**: When ROAS drops >15% week-over-week (trigger via Supermetrics + Zapier), auto-run the Quick Copy-Paste version against the latest data export and post the brief to your #paid-media Slack channel
- **HubSpot (B2B)**: For B2B campaigns using Meta Lead Ads, cross-reference Meta's cost-per-lead with HubSpot's lead-to-opportunity rate to calculate true blended CAC — feed this into the Attribution Reconciliation section
- **Northbeam / Rockerbox / Triple Whale**: The Advanced version's Attribution section is designed to take direct exports from these platforms — include the MTA model comparison columns for maximum diagnostic depth
- **Notion**: The output format is pre-structured for Notion — paste into a Notion doc and use `/table` to convert the action table, `/toggle` for each analysis section

## Troubleshooting

**Problem: Meta-reported ROAS is 3x higher than Shopify/GA4 revenue**
Solution: This is almost always iOS 14.5+ signal loss combined with view-through attribution inflation. In the Advanced version, add this to the attribution section: "Switch attribution window to 7-day click, 0-day view. Compare new ROAS to Shopify actual revenue. The gap narrows to signal loss alone — typically 20-40% for iOS-heavy audiences. Prioritize CAPI implementation and use the Meta Conversion API Gateway for a no-code fix."

**Problem: Creative analysis produces generic suggestions ("test more UGC")**
Solution: Your input data is too aggregated. Feed ad-level data (not ad set level) including 3-second video view rate, hook rate, and thumb-stop ratio. If you only have CTR and CPC, explicitly state this limitation and ask the prompt to produce a creative hypothesis matrix based on industry benchmarks for your vertical instead.

**Problem: Audience fatigue analysis not actionable because you don't control audience definitions**
Solution: Add your current audience structure (exact audiences in each ad set) to the context. The prompt will then produce specific audience duplication, exclusion, and expansion recommendations rather than generic frequency thresholds.

## Version History
- v1.0: Initial creation (auto-generated)
