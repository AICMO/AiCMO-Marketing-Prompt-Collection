# YouTube Ads Performance Analytics & Video Demand Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** youtube-ads, paid-video, google-ads, demand-gen, performance-max, cpv, vtr, b2b, d2c, video-analytics, brand-lift, cpa

## Overview
Diagnoses YouTube ad account performance across campaign types, creative formats, and audience layers — identifying view-rate decay, creative fatigue, placement waste, and attribution gaps — so an AI agent can produce a prioritized optimization brief ready for immediate media buyer execution.

## Quick Copy-Paste Version

You are a senior YouTube Ads performance analyst specializing in paid video optimization. Analyze the following YouTube / Google Ads data and produce a complete optimization brief.

Account context: [Paste your Google Ads performance export for YouTube campaigns, or describe key metrics below]

Analyze and deliver:

1. VIEW-THROUGH PERFORMANCE DIAGNOSIS
- Overall video view rate (VVR) trend last 7 / 30 / 90 days
- Campaign-level CPV (cost per view), VTR (view-through rate), and skip rate ranked best to worst
- Flag campaigns with skip rate >70% on in-stream skippable (signals weak hook)
- Flag campaigns with VTR <15% (skippable) or CPV above [$X] target

2. CREATIVE PERFORMANCE BREAKDOWN
- Top 3 and bottom 3 videos by view rate, CPV, conversion rate, and average watch time
- Hook strength: What % of viewers watch past the 5-second skip point?
- Hold rate: Average watch time as % of video length (benchmark: >35% is strong)
- Identify winning creative patterns: video length, hook type, CTA placement, format (skippable / bumper / non-skip)

3. AUDIENCE & TARGETING EFFICIENCY
- Performance by audience segment (affinity, in-market, custom intent, remarketing, customer match)
- Identify audience segments with CPV >2x account average — candidates for exclusion or bid reduction
- Remarketing sequence logic: Are viewers moving from awareness → consideration → conversion campaigns?
- Demographic breakdown: Age/gender/device skew in top-converting segments

4. PLACEMENT & BRAND SAFETY AUDIT
- Top 10 YouTube placements by spend — are they contextually relevant?
- Identify placements generating impressions but zero conversions (prime exclusion candidates)
- Brand safety: Any placements on content categories misaligned with brand guidelines?
- Placement-level CPV vs account average — surface wasted spend in irrelevant channels/videos

5. CONVERSION & ATTRIBUTION ANALYSIS
- View-through conversion (VTC) rate vs click-through conversion (CTC) rate by campaign
- Compare Google Ads-reported conversions vs GA4 / third-party attribution
- Cross-campaign assist analysis: Which YouTube campaigns drive assists for Search/Shopping conversion?
- Attribution window review: Are view-through windows (1-day / 7-day / 30-day) inflating conversion counts?

6. BUDGET EFFICIENCY & PACING
- CPM trends by campaign: Is rising CPM account-specific or market-wide?
- Budget pacing: Over-paced vs under-paced campaigns
- Campaign type performance comparison: In-stream vs bumper vs Discovery vs Performance Max vs Demand Gen
- Frequency capping assessment: Are viewers seeing ads too often, causing tune-out?

7. PRIORITIZED ACTION PLAN
Produce a ranked list of 5-10 specific actions with:
- Action description (specific, not vague)
- Expected impact (High/Medium/Low)
- Implementation effort (Hours/Days)
- Owner: Media Buyer / Creative Team / Analytics / Dev

Format the output as a structured brief that can be copied directly into a Notion doc or Linear ticket.

## Advanced Customizable Version

ROLE: You are a senior performance marketing analyst with 10+ years specializing in YouTube Ads and paid video optimization for [BUSINESS_TYPE: B2B SaaS / D2C e-commerce / B2C subscription / mobile app / enterprise software]. You combine deep Google Ads platform expertise with video storytelling principles and a revenue-first analytical framework. Every insight must tie to CPV reduction, conversion rate improvement, or pipeline generation — never vanity metrics like raw view counts.

ACCOUNT CONTEXT:
- Business: [COMPANY_NAME] — [brief product/service description]
- Monthly YouTube ad spend: $[MONTHLY_SPEND]
- Target CPV: $[TARGET_CPV] | Current blended CPV: $[CURRENT_CPV]
- Target CPA / ROAS: [TARGET_CPA_OR_ROAS] | Current: [CURRENT_CPA_OR_ROAS]
- Primary conversion event: [Purchase / Demo Request / Trial Signup / Lead Form / App Install]
- Attribution window in use: [View-through: 1-day / 7-day / 30-day | Click-through: 30-day]
- Campaign types running: [Skippable In-Stream / Non-Skippable / Bumper / Video Discovery / Performance Max / Demand Gen]
- Audience strategy: [Describe your funnel — cold awareness, warm remarketing, customer match sequences]
- Creative inventory: [Number of active video assets, lengths, formats]
- Brand safety tier: [Standard / Expanded / Limited inventory setting]

PERFORMANCE DATA:
[Paste your Google Ads YouTube campaign performance export, or provide manually:]
- Campaign names, types, objectives, spend, impressions, views, VTR, CPV
- Skip rate, average watch time, earned views, view-through conversions
- Audience segment performance (affinity / in-market / custom intent / remarketing)
- Top 10 placement URLs by spend with impressions and conversions
- Conversion data: VTC rate, CTC rate, CPA, ROAS (if applicable)
- 30-day trend data for VTR, CPV, and conversion rate

OBJECTIVE: Conduct a full-funnel YouTube Ads performance audit and produce an agentic optimization brief that a media buyer can execute without further research.

---

ANALYSIS FRAMEWORK:

## SECTION 1 — FUNNEL ARCHITECTURE REVIEW
Apply the YouTube video advertising funnel model:
- TOFU (Awareness): Skippable in-stream (15-60s) or bumper ads (6s) to cold audiences — affinity, in-market, custom intent (keyword targeting), broad demographics
- MOFU (Consideration): Longer-form in-stream (2-10 min) or Video Discovery to viewers who completed 25%+ of a TOFU video
- BOFU (Conversion): Remarketing sequences — retarget past video viewers, website visitors, cart abandoners, customer match lists with direct response CTAs

Evaluate:
- Budget allocation across TOFU/MOFU/BOFU vs revenue goals (recommended starting point: 50/25/25 for awareness-heavy brands, 30/20/50 for performance-first accounts)
- Remarketing list depth: Are MOFU/BOFU audiences large enough to sustain spend, or is frequency capping causing exhaustion?
- Funnel continuity: Can you trace a viewer's journey from first view → website visit → conversion across campaigns?

## SECTION 2 — CREATIVE INTELLIGENCE AUDIT
Apply the YouTube Creative Performance Matrix:

**Hook Analysis (0–5 seconds — the skip decision moment):**
- Strong hook signals: Skip rate <45% for skippable ads
- Weak hook signals: Skip rate >70% — viewers are skipping immediately
- Hook taxonomy: Classify each creative's hook type:
  1. Pattern interrupt (unexpected visual/sound)
  2. Curiosity gap ("The one mistake 90% of [role] make...")
  3. Direct value statement ("How [Company] cut their CAC by 40% in 60 days")
  4. Social proof opening (customer testimonial, logo wall, review)
  5. Problem agitation (pain-first hook)

**Hold Rate Analysis (completion quality):**
- Benchmark: 25% watch time / video length = adequate; 40%+ = strong creative
- Quartile analysis: At what % of video length does audience drop-off spike?
- Earned views (organic re-shares) as a signal of breakout content

**Format Performance Ladder:**
For each format, apply these benchmarks:
- 6s bumper: CPM < $8, completion rate 90%+ (non-skippable)
- 15s non-skippable: CPM < $12, expected VTC rate 0.3-0.8%
- 30s skippable: VTR >20%, CPV <$0.08 (competitive benchmarks; adjust for vertical)
- Long-form (2-5 min): VTR >30%, watch time >90 seconds, CTA click rate >3%

Produce a "Creative Hypothesis Matrix" — the 3 next video concepts most likely to outperform current control based on winning patterns (hook type, format length, messaging angle, CTA placement).

## SECTION 3 — AUDIENCE STRATEGY OPTIMIZATION
**Frequency & Saturation Thresholds:**
- Cold prospecting: Flag campaigns where individual users see >4 ads/week (likely causing tune-out)
- Remarketing: Flag >8 impressions/user/week — diminishing returns territory
- Calculate estimated days until audience list exhaustion at current pacing

**Audience Signal Quality Ranking:**
Rank active audiences by CPV efficiency and conversion intent signal strength:
1. Customer match (highest intent — existing relationships)
2. Website visitors (high intent — product-aware)
3. YouTube remarketing (warm — video-engaged)
4. Custom intent — URL-based (competitor site visitors, specific keyword searches)
5. Custom intent — keyword-based (active in-market signal)
6. In-market audiences (platform-inferred intent)
7. Affinity audiences (interest-based — lowest intent, highest scale)

Identify audiences where spend is concentrated in low-intent segments when high-intent segments are under-funded.

**Remarketing Sequence Gaps:**
- Map current audience rules to a 3-stage video funnel
- Identify gaps: Are viewers who watched 50%+ of a TOFU video being served a MOFU follow-up within 7 days?
- Audience exclusion audit: Are converted users excluded from active acquisition campaigns?

## SECTION 4 — PLACEMENT INTELLIGENCE AUDIT
Execute a placement-level spend analysis:

**Placement Quality Scoring:**
Classify each placement by:
- Contextual relevance score (1-5: does the video content align with your ICP's interests?)
- Conversion rate vs account average
- CPV vs account average
- Brand safety tier (standard / limited inventory / unknown)

**Exclusion Priority List:**
Automatically flag for exclusion:
- Any placement with >$[WASTE_THRESHOLD, e.g., $500] spend and 0 conversions
- Placements on mobile gaming apps (low engagement quality for most B2B/SaaS)
- Placements on children's content (COPPA compliance + zero purchase intent)
- Placements with CPV >3x account average AND below-average view rate

**Brand Suitability Review:**
- Identify if "Expanded inventory" setting is active — recommend switching to "Standard" for brand-safe categories
- Flag any ad serving on content categories misaligned with brand values (politics, sensitive topics)

## SECTION 5 — ATTRIBUTION RECONCILIATION
Execute a 4-source attribution comparison:
1. Google Ads (view-through + click-through attribution, your current window settings)
2. GA4 (session-scoped, last non-direct click)
3. Third-party attribution tool (Northbeam / Triple Whale / Rockerbox) if available
4. Revenue platform actual revenue (Shopify / Stripe / CRM)

**Identify:**
- View-through conversion inflation: Compare VTC rate to industry benchmarks — if VTC/CTC ratio >3:1, your attribution window is likely over-crediting video for organic conversions
- Cross-channel assist rate: What % of Google Search / Shopping conversions had a prior YouTube touchpoint?
- Attribution window impact: Model the difference in reported CPA at 1-day VTC vs 30-day VTC — present both to avoid false performance signals
- Walled garden problem: Google Ads inflates YouTube's contribution by design — recommended correction: Run a geo-based incrementality test (pause YouTube in 3 markets for 4 weeks, compare conversion rates)

**Measurement Fix Recommendations:**
- Google Tag / GA4 conversion event configuration gaps
- Enhanced conversions setup status (improves match rates for cross-device journeys)
- Offline conversion import status (for B2B: CRM deal close data back into Google Ads)

## SECTION 6 — CAMPAIGN TYPE OPTIMIZATION
For each active campaign type, apply the optimization ladder:

**Skippable In-Stream:**
- Bid strategy ladder: Maximize Conversions → Target CPA → Target ROAS (use Target CPA only when CPA is within 20% of goal and you have >30 conversions/month)
- Creative refresh trigger: When VTR drops >20% vs 4-week prior average, queue new creative within 5 business days

**Performance Max with Video Assets:**
- Asset group performance: Which asset groups are "Learning", "Limited", or "Eligible"?
- Video asset quality signal: Ensure at least 1 horizontal (16:9), 1 square (1:1), and 1 vertical (9:16) video per asset group
- Search themes audit: Are your PMax search themes cannibalizing branded search?

**Demand Gen Campaigns:**
- Benchmark: Demand Gen typically delivers 10-30% lower CPV than equivalent In-Stream campaigns due to broader placement eligibility (Shorts, Discover, Gmail)
- Image vs video asset split: If image assets outperforming video, signal that your video creative needs a refresh
- Lookalike audience performance vs standard audience signals

**Bumper Ads (6-second non-skippable):**
- Optimal use: Brand recall and retargeting frequency play — not primary conversion driver
- Sequence strategy: Run bumper retargeting against users who saw 25%+ of a longer-form in-stream ad
- CPM efficiency: If CPM >$15 for bumpers, evaluate reach/frequency campaign structure

## SECTION 7 — 30-DAY OPTIMIZATION ROADMAP
Produce a Gantt-style action plan:

Week 1 (Quick Wins — <4 hours total):
- [List 3-5 immediate actions with specific implementation instructions]

Week 2 (Creative Refresh):
- [List new video creative briefs based on winning hook types and formats]

Week 3 (Audience Restructure):
- [List audience changes, exclusions, remarketing sequence fixes]

Week 4 (Measurement & Structural Changes):
- [Attribution fixes, campaign structure changes, bid strategy updates]

For each action include:
- Specific implementation instruction (e.g., "Add mobile app placement exclusion list to all In-Stream campaigns — use Google's pre-built 'Mobile App Exclusion' list in Shared Library" — not vague "improve placements")
- Success metric and measurement method
- Risk level (Low / Medium / High) and rollback plan for High-risk changes

OUTPUT FORMAT:
Deliver as a structured brief with:
1. Executive Summary (3 bullet points: what's working, what's broken, top priority)
2. Scorecard (traffic light status for each section: Creative, Audiences, Placements, Attribution, Campaigns)
3. Full analysis per section
4. Prioritized action table (ranked by impact × urgency)
5. Video creative brief for next 3 concepts to test
6. Weekly KPI targets for next 30 days

The brief must be copy-paste ready for Notion, with each section clearly headed and action items formatted as checkboxes.

## Example Input/Output

**Input Example:**
Business: Meridian Ops — B2B SaaS revenue forecasting tool for VP Sales/RevOps, $299-$899/mo
Monthly YouTube spend: $42,000 | Target CPA (demo request): $180 | Current CPA: $267
Campaign types: Skippable in-stream (70% budget), bumper retargeting (15%), Video Discovery (15%)
Primary conversion: Demo request form submission
Attribution: 30-day view-through, 30-day click-through
Top campaigns:
- "Prospecting_CustomIntent_RevOps_Keywords" — $18k spend, VTR 14%, skip rate 73%, CPV $0.11, CPA $312
- "Prospecting_InMarket_BusinessSoftware" — $11k spend, VTR 22%, skip rate 51%, CPV $0.07, CPA $198
- "Remarketing_WebsiteVisitors_30day" — $8k spend, VTR 35%, skip rate 38%, CPV $0.05, CPA $143
- "Discovery_CompetitorKeywords" — $5k spend, VTR 28%, CPV $0.09, CPA $221
Top video asset: "60-second explainer — what is revenue forecasting?" — VTR 14%, avg watch time 12s
Placements: 40% on YouTube channels; 35% on Google Video Partners (GVP)
Attribution concern: Reporting 187 demo conversions but CRM shows only 61 actual demos booked

**Output Example:**

EXECUTIVE SUMMARY:
✅ What's working: Remarketing to 30-day website visitors is efficient ($143 CPA, 35% VTR) — clear signal that bottom-funnel targeting and creative messaging are resonating with product-aware buyers
🚨 What's broken: Cold prospecting creative has a catastrophic hook problem (73% skip rate = viewers bailing before your message lands); 30-day view-through attribution is inflating conversions by 3x — real CPA is ~$525, not $267; 35% of budget burning on Google Video Partners with no placement-level conversion data
🎯 Top priority: Replace explainer-first hook with a problem-agitation hook, apply mobile app + GVP placement exclusions to recover ~$15k/mo in wasted spend, and immediately switch to 7-day VTC to see true performance

SCORECARD:
Creative Performance: 🔴 73% skip rate on primary asset — hook is failing cold audiences
Audience Strategy: 🟡 Remarketing efficient; cold audiences need intent signal tightening
Placement Quality: 🔴 GVP blind spend — no conversion transparency; $14.7k at risk
Attribution Health: 🔴 3x overreporting — all CPA numbers misleading management
Campaign Structure: 🟡 Type mix reasonable; bid strategies need adjustment

WEEK 1 ACTIONS (4 hours):
☐ Add Google Video Partners exclusion to all 4 campaigns immediately — GVP placements have no YouTube-quality conversion signal and are wasting 35% of your budget ($14,700/mo)
☐ Add mobile gaming app placement exclusion list from Google Shared Library — B2B buyers are not watching pre-roll on Candy Crush
☐ Change attribution window from 30-day VTC to 7-day VTC across all campaigns — your current window is crediting YouTube for conversions that happened 3-4 weeks after a single view, likely organic
☐ Pull placement-level report for all GVP placements with >$200 spend — build a permanent exclusion list for any non-contextual placements
☐ Set frequency cap: Maximum 4 impressions per user per week on all prospecting campaigns

WEEK 2 (Creative Refresh):
☐ Brief 3 new 30-second video concepts using problem-agitation hooks (see Creative Brief below)
☐ Produce 3 × 6-second bumper variants from winning 30-second scripts — use for retargeting sequence

CREATIVE BRIEF — Top 3 Concepts to Test:
Concept 1 (Hook: Problem Agitation): Open with a VP Sales staring at a spreadsheet forecast. Cut to Slack message: "The board wants updated numbers by Friday." Voice-over: "Your forecast is a guess. Here's how 200+ revenue teams replaced it with certainty." — 30 seconds, ends with demo CTA
Concept 2 (Hook: Specificity + Social Proof): "Meridian customers reduce forecast error from 34% to 6% — without rebuilding their CRM stack." — Lead with a specific number, then show 10-second product demo clip, then customer quote. 45 seconds.
Concept 3 (Hook: Direct Address): "If you're a VP Sales using a Salesforce pipeline report as your forecast — watch the next 30 seconds." — Direct challenge to current behavior; positions switching cost as the risk of inaction. 30 seconds.

## Success Metrics
- Skip rate on primary cold prospecting creative drops from 73% → <50% within 30 days of creative refresh
- CPA (using 7-day VTC) tracks within 20% of $180 target within 60 days
- Placement exclusions recover >$12k/mo in wasted GVP spend (track via placement report week-over-week)
- Remarketing CPA maintains <$150 with frequency caps applied
- VTR on cold audience campaigns improves from 14% → >22% with new hook creative
- CRM demo bookings match (within 25%) Google Ads-reported conversions after attribution window correction

## Related Prompts
- `../../05_Analytics-&-Performance/Paid-Media-&-PPC-Performance-Analytics/Google-Ads-Performance-Analytics-&-Search-Intent-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Paid-Media-&-PPC-Performance-Analytics/Meta-Ads-Performance-Analytics-&-Social-Commerce-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Paid-Media-&-PPC-Performance-Analytics/LinkedIn-Ads-Performance-Analytics-&-B2B-Demand-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md`

## Integration Tips
- **Google Ads + Supermetrics → Google Sheets**: Schedule daily Supermetrics pulls of YouTube campaign data at the campaign/ad group/asset level into a master Sheet; run this prompt against the weekly export every Monday to automate your paid video brief
- **GA4 Cross-Channel Path Report**: Export the GA4 "Conversion paths" report filtered for YouTube touchpoints and feed it alongside Google Ads data into the Attribution Reconciliation section — produces specific window-correction recommendations
- **Zapier + Slack Alert**: Configure a Zapier trigger when weekly VTR drops >20% from prior week average (via Supermetrics → Zapier webhook) — auto-run the Quick Copy-Paste version and post to #paid-media Slack channel for immediate creative triage
- **HubSpot / Salesforce (B2B)**: For demo-request campaigns, import offline conversion data (demo actually held → opportunity created → deal closed) back into Google Ads via the Offline Conversion Import feature — this trains Smart Bidding on revenue outcomes, not just form fills, and dramatically improves CPA over 4-6 weeks
- **Northbeam / Triple Whale (DTC)**: Export the platform's YouTube attribution contribution data alongside Google Ads reported conversions and feed both into the Attribution Reconciliation section — surface the real media-efficient ROAS after deduplication
- **Notion / Confluence**: The output is structured for direct pasting — use Notion's `/toggle` block for each analysis section and `/table` for the action plan to create a permanent media review template your team fills weekly

## Troubleshooting

**Problem: View-through conversions are 5-10x higher than CRM/revenue platform records**
Solution: Your 30-day view-through attribution window is crediting YouTube for every conversion that occurred within 30 days of an ad impression — including customers who would have converted organically. In the Advanced version, explicitly add: "Model performance at 1-day VTC and compare to CRM actuals. Calculate the inflation multiplier. Recommend switching to 1-day VTC immediately for reporting, while keeping 30-day for Smart Bidding signals (Google's algorithm needs the broader window to learn, even if you report on the tighter window)." Run a geo holdout test in 2 markets to measure true incrementality before making budget decisions.

**Problem: Creative analysis returns generic advice ("make better hooks") because watch time data is missing**
Solution: Add quartile-level data to your input: the percentage of viewers who watched to 25%, 50%, 75%, and 100% of each video. This is available in the Google Ads UI under Video campaigns → Videos → Quartile columns. Feed the quartile breakdown to the prompt and it will pinpoint exactly where in each video viewer drop-off spikes — enabling specific script edits rather than wholesale creative replacement.

**Problem: Performance Max campaigns make it impossible to isolate YouTube spend from Search/Shopping**
Solution: In the Advanced version, add this instruction: "Segment PMax asset group performance by channel using the 'Asset group performance' report and the 'Combinations' report. Estimate YouTube-specific CPV by dividing total PMax video impressions into total PMax video spend (available in the Campaign type segment). Flag if PMax YouTube placement share is <15% — this indicates Google is routing budget away from video assets, signaling either weak video creative or that your Smart Bidding signals favor Search. Recommend running a separate dedicated YouTube campaign alongside PMax to maintain creative control and placement visibility."

## Version History
- v1.0: Initial creation (auto-generated)
