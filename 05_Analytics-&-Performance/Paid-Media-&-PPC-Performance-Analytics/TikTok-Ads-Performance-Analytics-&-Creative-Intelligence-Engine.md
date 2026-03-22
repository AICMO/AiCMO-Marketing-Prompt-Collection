# TikTok Ads Performance Analytics & Creative Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** tiktok-ads, paid-social, creative-analytics, ugc, spark-ads, social-commerce, tiktok-shop, cpa, roas, d2c, b2c, creative-fatigue

## Overview
Diagnoses TikTok Ads account performance across campaign types, creative formats, audience strategies, and attribution models — surfacing creative fatigue patterns, CPM inflation signals, audience exhaustion, and shop/commerce conversion gaps — so an AI agent can produce a prioritized optimization brief ready for immediate media buyer and creative team execution.

## Quick Copy-Paste Version

You are a senior TikTok Ads performance analyst specializing in paid social optimization and creative-driven growth. Analyze the following TikTok Ads data and produce a complete optimization brief.

Account context: [Paste your TikTok Ads Manager performance export, or describe key metrics below]

Analyze and deliver:

1. CREATIVE PERFORMANCE DIAGNOSIS
- Top 3 and bottom 3 creatives by CTR, CVR, CPA, and video completion rate (VCR)
- Average creative lifespan: How many days until each ad's CTR drops >30% from its launch peak?
- Flag any creative running >7 days with CTR declining week-over-week (creative fatigue signal)
- Hook strength: What % of viewers watch past the first 3 seconds? (Benchmark: >60% is strong)
- Identify winning creative patterns: UGC vs polished production, hook type, video length, CTA style

2. CAMPAIGN & BUDGET EFFICIENCY
- CPM trends by campaign: Flag campaigns with CPM >2x account average (audience saturation signal)
- Campaign objective performance: Traffic vs Lead Gen vs Conversions vs Shop Purchases — CPA ranked best to worst
- Budget pacing: Over-paced vs under-paced campaigns by day of week
- Frequency: Average user frequency by campaign — flag >5 impressions/user/week (fatigue zone)

3. AUDIENCE STRATEGY REVIEW
- Performance by audience type: Broad, Interest-based, Behavioral, Lookalike, Custom (website visitors, customer list, video engagers)
- Identify audience segments with CPM >2x account average — prime candidates for exclusion or bid reduction
- Lookalike seed quality: Are your highest-LTV customers or 30-day purchasers being used as lookalike seeds?
- Audience overlap: Identify if campaigns are cannibalizing each other with overlapping targeting

4. TIKTOK SHOP & COMMERCE PERFORMANCE (if applicable)
- Product-level ROAS from TikTok Shop vs standard ad links — which products convert best in-app?
- Affiliate/creator shop performance: Any organic creator content driving outsized shop revenue?
- Add-to-cart rate vs purchase rate gap: Where is commerce friction highest?
- Product catalog health: Are all active SKUs synced, inventory accurate, and product pages optimized for TikTok browsing behavior?

5. ATTRIBUTION & MEASUREMENT HEALTH
- TikTok Pixel vs Events API: Is server-side Events API active? If not, flag as measurement gap
- View-through conversion window: Flag if 7-day VTC is inflating CPA by >2x compared to click-through-only view
- TikTok Ads-reported conversions vs third-party attribution (Northbeam / Triple Whale / Rockerbox) — calculate the inflation multiplier
- iOS 14+ signal loss: What % of conversions are modeled vs observed?

6. PRIORITIZED ACTION PLAN
Produce a ranked list of 5-10 specific actions with:
- Action description (specific, not vague)
- Expected impact (High/Medium/Low)
- Implementation effort (Hours/Days)
- Owner: Media Buyer / Creative Team / Analytics / Developer

Format the output as a structured brief that can be copied directly into a Notion doc or Linear ticket.

## Advanced Customizable Version

ROLE: You are a senior performance marketing analyst with 10+ years specializing in TikTok Ads and paid social creative optimization for [BUSINESS_TYPE: D2C e-commerce / B2C subscription / mobile app / consumer brand / B2B SaaS with broad awareness needs]. You combine deep TikTok Ads Manager platform expertise with native content strategy, creator economy dynamics, and a revenue-first analytical framework. Every insight must tie to CPM efficiency, creative lifespan extension, CVR improvement, or ROAS — never vanity metrics like raw video views or follower counts.

ACCOUNT CONTEXT:
- Business: [COMPANY_NAME] — [brief product/service description]
- Monthly TikTok ad spend: $[MONTHLY_SPEND]
- Target CPA: $[TARGET_CPA] | Current blended CPA: $[CURRENT_CPA]
- Target ROAS: [TARGET_ROAS] | Current blended ROAS: [CURRENT_ROAS]
- Primary conversion event: [Purchase / Lead Form / App Install / Trial Signup / TikTok Shop Purchase]
- Attribution window in use: [Click-through: 7-day | View-through: 1-day / 7-day]
- Campaign types running: [In-Feed Ads / Spark Ads / TopView / Branded Hashtag Challenge / TikTok Shop / Lead Generation]
- Creative inventory: [Number of active video creatives, UGC count vs branded production count, average creative age]
- TikTok Shop status: [Active / Not active / In setup]
- Attribution tools: [TikTok Pixel only / Events API active / Third-party: Northbeam, Triple Whale, Rockerbox, etc.]
- Audience strategy: [Describe your funnel — cold interest/behavioral, lookalike, custom audience retargeting]

PERFORMANCE DATA:
[Paste your TikTok Ads Manager performance export, or provide manually:]
- Campaign names, objectives, spend, impressions, reach, clicks, CTR
- Video completion rate (VCR) at 25%, 50%, 75%, 100%, and "watched full video" rate
- 3-second video view rate (hook rate) per creative
- Conversions, CPA, ROAS by campaign and ad group
- Audience segment performance (broad / interest / behavioral / lookalike / custom)
- Creative-level performance sorted by spend: CTR, CVR, CPA, VCR, 3s view rate
- 30-day trend data for CPM, CTR, CVR, and CPA
- Frequency data by campaign (impressions / reach = frequency)
- TikTok Shop data (if applicable): product ROAS, add-to-cart rate, checkout rate, purchase rate

OBJECTIVE: Conduct a full-funnel TikTok Ads performance audit and produce an agentic optimization brief that a media buyer and creative team can execute without further research.

---

ANALYSIS FRAMEWORK:

## SECTION 1 — CREATIVE INTELLIGENCE AUDIT (Highest Leverage on TikTok)

TikTok's algorithm is fundamentally creative-first: the creative IS the targeting. Unlike Meta or Google where audience targeting and bid strategies carry significant weight, TikTok's interest graph learns from content signals — meaning your best-performing creative will self-select its own optimal audience. Apply this creative-centric lens to every analysis.

**Hook Rate Analysis (0–3 seconds — the scroll-stop decision):**
- Strong hook: >65% of viewers watch past 3 seconds
- Adequate hook: 45-65% of viewers watch past 3 seconds
- Weak hook: <45% — viewers are swiping before your message registers
- Hook taxonomy: Classify each creative's opening approach:
  1. **Pattern interrupt**: Unexpected visual, sound effect, or on-screen text that breaks scroll behavior
  2. **Direct address**: Creator looks into camera and speaks directly to viewer persona ("If you're a [role] who [problem]...")
  3. **Social proof open**: Lead with outcome first ("I lost 30 lbs in 90 days — here's the exact stack")
  4. **Curiosity gap**: "The thing your [competitor/doctor/agency] doesn't want you to know about..."
  5. **Demonstration hook**: Product in action before any spoken word — show transformation or result
  6. **Trending audio/format**: Hijacking a viral audio or video format to create native familiarity

**Creative Fatigue Detection:**
TikTok creative fatigues 3-5x faster than Meta due to algorithm-driven content saturation. Apply the following fatigue signals:
- Primary fatigue signal: CTR decline >25% from launch-week peak, sustained for 3+ consecutive days
- Secondary signal: CPM rising >20% week-over-week on same creative (auction is deprioritizing low-engagement content)
- Tertiary signal: CPA rising >30% from creative's best-week performance

Build a "Creative Aging Matrix":
| Creative | Launch Date | Days Live | Peak CTR | Current CTR | CTR Decline % | Fatigue Status | Action |
|---|---|---|---|---|---|---|---|
For each creative: Green (healthy, <15% CTR decline), Yellow (monitor, 15-30% decline), Red (retire, >30% decline)

**Video Completion Quality:**
- Benchmark by length:
  - 7-15s: 85%+ watched full video = strong; <70% = retention problem
  - 15-30s: 60%+ watched full video = strong; <45% = drop-off analysis needed
  - 30-60s: 40%+ watched full video = strong; pinpoint quartile where audience exits
- Replay rate: High replay rate (>15% of viewers replay) signals content people want to re-watch — earns organic distribution credit from the algorithm
- Earned interactions: Saves, shares, and comments as % of views — >3% combined = algorithm amplification signal

**Winning Creative Pattern Extraction:**
From your top 5 creatives by CPA/ROAS, extract:
- Hook type (from taxonomy above)
- Native UGC style vs polished brand production
- Creator type: Employee, customer testimonial, paid creator, or faceless product demo
- Video length range
- Text overlay density: Heavy on-screen text vs clean visual
- CTA type: Soft (learn more) vs hard (buy now / get 50% off / shop today)
- Audio: Original brand audio, trending sound, or voice-over narration

Produce a "Creative Winning Formula" hypothesis: the combination of elements most correlated with top-quartile CPA in this account. This becomes your creative brief template for the next production batch.

## SECTION 2 — CAMPAIGN STRUCTURE & BUDGET OPTIMIZATION

**Campaign Objective Alignment:**
- Awareness objective: Use for TopView, Branded Hashtag Challenge, or when CPM efficiency matters more than conversion tracking
- Traffic objective: Appropriate for retargeting to high-intent pages; flag if being used for cold prospecting (inefficient — optimize for clicks, not buyers)
- Conversion objective (Website): Requires active Pixel with Conversions API — if Events API is not active, conversion campaign optimization is running blind on iOS audiences
- Lead Generation (native): TikTok's in-app Lead Gen forms convert 2-3x higher than external landing pages for mobile-first audiences; flag if using website lead forms instead
- Shop Purchases: TikTok Shop campaigns benefit from product catalog data — flag if campaign is not linked to product catalog

**Budget Allocation Framework:**
Apply the TikTok Funnel Budget Ladder:
- TOFU (Cold prospecting — Broad/Interest/Behavioral/Lookalike): 50-65% of budget for growth-focused accounts
- MOFU (Warm retargeting — Video viewers 50%+, profile visitors, website visitors 30-day): 20-30% of budget
- BOFU (High-intent retargeting — Add-to-cart, checkout initiated, customer list exclusion): 15-25% of budget

Flag if budget allocation is inverted (more spend on retargeting than cold prospecting) — signals audience exhaustion and limits growth ceiling.

**CPM Inflation Diagnosis:**
CPM rising over time is TikTok's signal that your creative is losing auction competitiveness (lower engagement rate = higher CPM to buy the same reach). Diagnose:
- Account-level CPM trend: Is CPM rising due to creative fatigue, competitive auction pressure, or seasonal factors?
- Campaign-level CPM outliers: Which campaigns have CPM >1.5x account average? (Candidates for creative refresh or audience expansion)
- Day-of-week CPM patterns: Identify lowest-CPM days for budget concentration (typically Tuesday-Thursday for most verticals)

## SECTION 3 — AUDIENCE STRATEGY OPTIMIZATION

**TikTok-Specific Audience Hierarchy (Ranked by Intent Signal Strength):**
1. Custom Audience — Customer list (CRM upload, highest LTV seed)
2. Custom Audience — Website visitors (Pixel-based, product-page or checkout visitors)
3. Custom Audience — TikTok engagement (video viewers 75%+, profile visitors, ad engagers)
4. Lookalike — Seeded from purchasers or high-LTV customers (1-3% similarity for scale + quality balance)
5. Custom Audience — App users (if applicable)
6. Behavioral targeting (in-app purchase behavior, content consumption signals)
7. Interest targeting (broad interest categories — lowest intent, highest reach)
8. Broad targeting (no audience restriction — let TikTok's algorithm optimize; increasingly effective as account matures and Pixel accumulates data)

**Broad vs Targeted Debate:**
TikTok increasingly performs better with broad or minimal targeting when:
- Account has >50 conversion events/week (algorithm has sufficient data to self-optimize)
- Creative is strong (>65% hook rate)
- Budget is sufficient for the algorithm's learning phase (typically 50 conversion events per ad group)
Recommend testing Broad targeting as a separate ad group alongside Interest targeting when these conditions are met.

**Audience Overlap & Cannibalization:**
- Flag ad groups within the same campaign that target overlapping audiences — they're bidding against each other in auction, inflating CPM
- Implement exclusion audiences: Exclude existing purchasers from cold prospecting campaigns; exclude 30-day purchasers from BOFU retargeting (they already converted)
- Lookalike refresh schedule: Recommend refreshing lookalike seeds every 60-90 days with updated purchaser lists

## SECTION 4 — TIKTOK SHOP & COMMERCE INTELLIGENCE

If TikTok Shop is active, apply the Commerce Conversion Funnel Analysis:

**In-App Commerce Funnel:**
Benchmark conversion rates through TikTok Shop:
- Ad impression → Product page view: >3% (flag if <1.5% — creative or landing page disconnect)
- Product page view → Add to cart: >8% (flag if <4% — product page optimization needed)
- Add to cart → Checkout initiated: >60% (flag if <40% — checkout friction)
- Checkout initiated → Purchase: >50% (flag if <35% — payment/trust barrier)

**Product-Level Performance:**
- Rank all active products by: ROAS, units sold, return rate, and review score
- Flag high-ad-spend / low-ROAS products (reduce budget or pause catalog inclusion)
- Flag high-ROAS / low-spend products (increase catalog bid or create dedicated campaign)
- Return rate outlier flag: Products with >25% return rate may be misrepresented in creative — investigate hook vs product reality gap

**Creator Affiliate Commerce:**
- Identify if any organic creator content (non-paid Spark Ads) is driving TikTok Shop revenue through affiliate links
- Calculate creator affiliate GMV contribution vs paid media GMV — if affiliate GMV >20% of paid, prioritize Spark Ads activation with top affiliate creators
- Creator product matching: Are the best-selling products being promoted by the right creator archetypes (size-inclusive creators for apparel, expert creators for tech/health, lifestyle creators for home goods)?

## SECTION 5 — ATTRIBUTION RECONCILIATION & MEASUREMENT HEALTH

**TikTok Attribution Architecture Audit:**
Execute a 4-source comparison:
1. TikTok Ads Manager (click-through + view-through at your current window settings)
2. TikTok Events API / Pixel (server-side vs browser-side signal quality)
3. Third-party attribution (Northbeam / Triple Whale / Rockerbox) if available
4. Revenue platform actuals (Shopify / Stripe / CRM) — ground truth

**Events API Implementation Status:**
- Pixel-only: Estimated 30-40% signal loss on iOS devices post-ATT — all iOS conversion optimization is running on modeled data
- Events API active: Signal loss reduced to 10-15%; Smart Bidding algorithm receives better signal
- Flag if Events API is not implemented: This is the single highest-impact technical fix for TikTok Ads efficiency — prioritize above all creative and audience optimizations

**View-Through Inflation Check:**
Compare TikTok-reported conversions vs third-party actuals:
- If TikTok reports 3x+ more conversions than Shopify/CRM, your 7-day view-through window is crediting TikTok for organic purchases
- Recommended diagnostic: Temporarily switch all campaigns to click-through only attribution and compare 2-week CPA — delta reveals true VTC inflation rate
- Industry benchmark: TikTok VTC inflation ratio typically 2-4x; above 4x indicates your audience was going to buy regardless

**iOS vs Android Performance Split:**
- Separate campaign performance by device OS
- Android campaigns have near-full measurement fidelity; iOS campaigns run on modeled conversions
- If iOS CPA appears dramatically better than Android CPA, iOS optimization signals may be over-attributing — require creative holdout test to validate

## SECTION 6 — SPARK ADS & CREATOR STRATEGY

**Spark Ads vs Dark Post Performance:**
- Spark Ads (boosting organic creator posts): Typically achieve 20-30% lower CPM than dark posts due to social proof signals (existing likes, comments, shares)
- Identify top-performing organic creator posts (by view count and engagement rate) as Spark Ads candidates
- Creator authorization status: Flag any Spark Ads authorizations expiring in <30 days

**Creator Performance Scoring Matrix:**
For each active creator partnership producing TikTok Ads content:
| Creator | Content Style | Avg Hook Rate | Avg CVR | CPA vs Account Avg | Relationship Status |
|---|---|---|---|---|---|

Flag creators consistently producing sub-average CVR despite strong view metrics — signals audience/product mismatch (creator's audience doesn't intend to buy your product).

**Creator Brief Quality Signals:**
Identify if poor creative performance correlates with:
- Overly scripted content (creator sounds robotic — audiences detect inauthenticity)
- Missing key product benefit in first 3 seconds
- CTA placed at end only (vs woven throughout)
- No on-screen text overlay (reduces accessibility and scroll-stopping power)

## SECTION 7 — 30-DAY OPTIMIZATION ROADMAP

Produce a prioritized weekly action plan:

**Week 1 — Quick Wins (< 6 hours total):**
- Retire all Red-status creatives from Creative Aging Matrix — cut wasted CPM spend immediately
- Apply audience exclusions: Exclude 180-day purchasers from all cold prospecting campaigns
- Implement frequency caps: Maximum 4 impressions/user/week on prospecting; 7/week on retargeting
- Fix attribution window: Switch any campaigns on 7-day VTC to 1-day VTC for reporting accuracy (keep 7-day for algorithm signal)

**Week 2 — Creative Production Sprint:**
- Brief new creative batch based on Winning Creative Formula
- Target: 5-8 new creatives prioritizing strongest hook types from the analysis
- Prioritize UGC-style concepts if polished production is underperforming
- Activate Spark Ads on top 3 organic creator posts identified in analysis

**Week 3 — Audience & Structure Optimization:**
- Launch Broad targeting test ad group alongside best-performing Interest ad group (same creative, equal budget)
- Refresh lookalike seeds with most recent 90-day purchaser list
- Consolidate overlapping ad groups to reduce internal auction competition

**Week 4 — Measurement Infrastructure:**
- Implement Events API (if not active) — highest technical leverage for campaign efficiency
- Configure advanced matching via Events API: email, phone, and external ID hashing
- Set up TikTok × Shopify/CRM revenue reconciliation dashboard in Supermetrics or Looker Studio
- Run 2-week click-through-only attribution diagnostic to measure view-through inflation

For each action include:
- Specific implementation instruction (not vague — step-by-step enough for execution without additional research)
- Success metric with measurement method
- Risk level (Low / Medium / High) and rollback plan for Medium/High-risk changes

OUTPUT FORMAT:
Deliver as a structured brief with:
1. Executive Summary (3 bullet points: what's working, what's broken, top priority)
2. Scorecard (traffic light status for each section: Creative Health, Budget Efficiency, Audience Strategy, Shop Commerce, Attribution Quality)
3. Creative Aging Matrix (table format)
4. Full analysis per section
5. Prioritized action table ranked by impact × urgency
6. New Creative Brief: 5 specific video concepts based on winning pattern analysis
7. Weekly KPI targets for next 30 days

The brief must be copy-paste ready for Notion with each section clearly headed and action items formatted as checkboxes.

## Example Input/Output

**Input Example:**
Business: Solara Skin — D2C skincare brand, hero product: $78 Vitamin C serum
Monthly TikTok spend: $55,000 | Target CPA (purchase): $28 | Current CPA: $41
Target ROAS: 3.0x | Current ROAS: 1.9x
Campaign types: In-Feed conversion campaigns (80%), Spark Ads from 3 creators (20%)
Primary conversion: Shopify purchase
Attribution: 7-day click, 7-day view-through
Active creatives: 11 ads | Ages: 2 running >21 days, 4 running 10-20 days, 5 running <7 days
Audience: Interest (Skincare, Beauty, Self-care) — 60% of spend; Lookalike 2% (past purchasers) — 25% of spend; Retargeting 15% of spend
Events API: Not implemented (Pixel only)
TikTok Shop: Not active
Third-party attribution: Triple Whale shows ROAS 1.4x vs TikTok's reported 1.9x

**Output Example:**

EXECUTIVE SUMMARY:
✅ What's working: Spark Ads from creator @SkincareBySophia are generating CPA of $22 (vs $41 account average) — her "morning routine" 60-second format with heavy on-screen benefit callouts is outperforming all brand-produced creatives by 46%; Lookalike prospecting (2% seed) maintains $31 CPA vs $52 on broad interest targeting
🚨 What's broken: 2 creatives aged 21+ days with CTR at 60% below their launch-week peak are consuming 38% of total budget — creative fatigue is the primary CPA inflation driver; Triple Whale reports 1.4x ROAS vs TikTok's 1.9x — 36% view-through inflation means your true economics are far worse than dashboard shows; Events API absence means iOS optimization is running blind on ~35% of mobile traffic
🎯 Top priority: Immediately pause the 2 fatigued creatives (recovers ~$20k/month from wasted CPM spend), activate Events API (highest single technical ROI action), and brief 5 new UGC concepts modeled on @SkincareBySophia's winning format

SCORECARD:
Creative Health: 🔴 2 of 11 active creatives in red-fatigue zone consuming 38% of spend
Budget Efficiency: 🔴 CPM on aged creatives is 2.3x account average — paying premium for declining engagement
Audience Strategy: 🟡 Lookalike efficient; Interest targeting over-indexed vs performance warrants
Shop Commerce: ⚪ Not active — high opportunity given TikTok Shop ROAS premiums in beauty vertical (industry avg 2.8x)
Attribution Quality: 🔴 Events API absent; 36% view-through inflation gap vs Triple Whale

CREATIVE AGING MATRIX:
| Creative | Launch Date | Days Live | Peak CTR | Current CTR | CTR Decline | Status | Action |
|---|---|---|---|---|---|---|---|
| SkinRoutine_BrandedV2 | Feb 14 | 36 days | 1.8% | 0.7% | -61% | 🔴 RED | Pause immediately |
| BeforeAfter_Static_Ad | Feb 19 | 31 days | 1.2% | 0.6% | -50% | 🔴 RED | Pause immediately |
| SkincareSophia_Spark | Mar 2 | 20 days | 3.1% | 2.6% | -16% | 🟢 GREEN | Scale budget +20% |
| IngredientExplainer_UGC | Mar 8 | 14 days | 2.4% | 1.9% | -21% | 🟡 YELLOW | Monitor 5 days |
| DermReaction_UGC | Mar 15 | 7 days | 2.8% | 2.6% | -7% | 🟢 GREEN | Hold, assess next week |

WEEK 1 ACTIONS:
☐ Pause "SkinRoutine_BrandedV2" and "BeforeAfter_Static_Ad" immediately — these two creatives are generating CPM 2.3x account average due to declining engagement signals; pausing recovers ~$20,800/month in wasted CPM spend
☐ Reallocate paused creative budget to SkincareSophia_Spark ad group — increase daily budget by 40% to maximize while creative is still healthy
☐ Implement TikTok Events API via Shopify integration (native TikTok Shopify App → Pixel → Events API toggle) — estimated 3-hour implementation; expected 15-25% CPA improvement over 30-45 days as algorithm receives better iOS conversion signal
☐ Switch reporting attribution to 7-day click / 1-day view-through (keep 7-day VTC for Smart Bidding signal only) — this will show true CPA closer to Triple Whale's $55 figure; adjust CPA targets accordingly for honest performance management
☐ Apply purchaser exclusion: Build 180-day purchaser Custom Audience from Shopify customer list; exclude from all cold prospecting campaigns

NEW CREATIVE BRIEF — 5 Concepts Based on Winning Formula:
Winning formula: 60-second UGC, creator visible on camera, 3-second hook = direct-to-camera statement with specific skin concern named, heavy on-screen text overlays at each key benefit point, before/after B-roll at 30-second mark, CTA callout at 45 and 60 seconds.

Concept 1 (Hook: Direct Address + Specificity): Creator opens to camera: "If your skin looks dull and tired every morning — this is the thing I wish I tried 2 years earlier." B-roll of applying serum. Overlay: "Vitamin C that actually works in 14 days." Time-lapse skin transformation at 30s. End: "Link in bio — first order ships free."

Concept 2 (Hook: Social Proof Lead): Open with screenshot of TikTok comment: "My coworker asked what I changed about my skin — I said nothing except this." Creator: "This is not the first time I've heard this." Walk through 3-step application routine. Overlay: "4.8 stars from 6,200 reviews."

Concept 3 (Hook: Curiosity Gap): "The reason most Vitamin C serums don't work — and why the formula matters more than the price tag." Educational explainer format with text-heavy overlays. Creator positions Solara as the insider knowledge pick.

Concept 4 (Hook: Demonstration): No speech for first 5 seconds — just close-up video of serum application with satisfying texture and absorption. Overlay: "Morning ritual. 14 days. You'll see it." Product-first visual hook with ASMR sensory appeal.

Concept 5 (Hook: Problem Agitation): "I spent $340 on serums last year that made my skin worse." Creator holds up three competitor bottles, sets them aside. "This is the only one I kept." No mention of price until end CTA.

## Success Metrics
- Blended account CPA drops from $41 → <$30 within 45 days of creative refresh and Events API activation
- Creative CTR decline: No active creative should show >30% CTR decline from launch peak (automated via weekly Creative Aging Matrix audit)
- Triple Whale ROAS closes gap to >2.5x (from 1.4x) within 60 days — driven by Events API improving optimization signal quality
- CPM on active creatives maintains within 1.4x of account average (early fatigue detection benchmark)
- Lookalike CPA maintains <$32 with refreshed seed list
- Frequency: No campaign exceeds 4.5 average impressions/user/week

## Related Prompts
- `../../05_Analytics-&-Performance/Paid-Media-&-PPC-Performance-Analytics/Meta-Ads-Performance-Analytics-&-Social-Commerce-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Paid-Media-&-PPC-Performance-Analytics/YouTube-Ads-Performance-Analytics-&-Video-Demand-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Paid-Media-&-PPC-Performance-Analytics/LinkedIn-Ads-Performance-Analytics-&-B2B-Demand-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md`

## Integration Tips
- **TikTok Ads Manager + Supermetrics → Google Sheets**: Schedule daily Supermetrics pulls of TikTok campaign data at the creative/ad level into a master Sheet; add a "Days Live" calculated column and a "CTR vs Peak CTR" formula to auto-populate the Creative Aging Matrix every Monday morning — run this prompt against the weekly export to automate your paid social brief
- **Shopify → TikTok Events API (Native Integration)**: Navigate to TikTok for Business app in Shopify App Store → Pixel section → enable "Advanced Matching" and toggle Events API — no developer required; estimated implementation time 45 minutes; immediately improves iOS signal recovery
- **Triple Whale / Northbeam → Attribution Reconciliation**: Export the "TikTok contribution" report from your MTA tool and paste alongside TikTok Ads Manager data for the Attribution Reconciliation section — the prompt will produce specific window-correction recommendations and a true ROAS figure for CFO reporting
- **Zapier + Slack Creative Fatigue Alert**: Configure Zapier to pull CTR data from Supermetrics daily; trigger a Slack alert to #paid-social when any creative's CTR drops >25% from its 7-day rolling average — auto-run the Quick Copy-Paste prompt and post the creative triage brief for same-day review
- **TikTok Creator Marketplace → Spark Ads Pipeline**: Use TikTok Creator Marketplace to identify creators whose audience demographics match your top-converting customer segments; request Spark Ads authorization for all partnerships before content launch so you can activate paid distribution on organic posts without production delay
- **Notion Performance Hub**: The output is structured for direct paste — create a Notion database with one page per weekly TikTok audit; use the Creative Aging Matrix as a recurring table view filtered by Status column (Green/Yellow/Red) to give your creative team a live queue of what to retire, monitor, or scale

## Troubleshooting

**Problem: TikTok Ads Manager shows ROAS 2.5x but Shopify revenue attribution to TikTok is only 1.1x — which number do I trust?**
Solution: Neither in isolation. TikTok Ads Manager over-attributes due to view-through windows claiming credit for purchases that would have happened organically. Shopify's "last-click" attribution under-attributes because TikTok ads often influence purchases that complete on a different device or after a Google search. The truth is in the middle — use a third-party MTA tool (Triple Whale for DTC, Northbeam for complex funnels) as the arbiter. In the Advanced version, add this instruction: "Calculate the 'attribution inflation ratio' by dividing TikTok Manager conversions by Shopify-attributed TikTok conversions for the same period. If ratio >2.0x, switch to 1-day view-through for reporting. If ratio >3.5x, disable view-through attribution entirely for optimization decisions and rely on click-through ROAS only. Never make budget-increase decisions based on TikTok Manager ROAS without cross-referencing at least one external source."

**Problem: New creatives launch strong but CTR collapses after 5-7 days — cycle is unsustainable for production team**
Solution: Creative fatigue this fast is usually caused by narrow audience targeting (small audience sees the same ad repeatedly, inflating frequency beyond 6/week) combined with a small creative rotation (algorithm serves the same 2-3 ads disproportionately). Fix in two steps: First, expand your audience — add Broad targeting ad group alongside Interest targeting to increase unique reach pool. Second, increase creative rotation depth — aim for 6-10 active creatives per campaign, not 2-4, so the algorithm has variety to serve. In the Advanced version, add: "Analyze frequency by campaign. For any campaign with average frequency >4.5 within 7 days, flag as 'audience pool exhausted.' Recommend either audience expansion (broader lookalike percentage, add Broad targeting) or budget reduction to extend creative lifespan. Creative fatigue is usually an audience size problem, not solely a creative problem."

**Problem: TikTok Spark Ads approval is delayed or rejected for creator content — blocking campaign launch**
Solution: TikTok Spark Ads authorization requires the creator to approve the request through their TikTok app — if the creator hasn't responded within 7 days, the authorization expires. Preventive protocol: In the Advanced version, add this workflow recommendation: "For all creator partnerships, request Spark Ads authorization the same day content is approved — before the post goes live — so the authorization is active when you're ready to launch. Build a creator authorization tracker in Airtable or Notion with columns: Creator Name, Post URL, Authorization Status, Expiry Date. Set a 5-day reminder before expiry to renew. If a post receives strong organic traction before you can activate Spark Ads, the delay in activation means your best-performing organic moment is burning without paid amplification — speed of authorization is a revenue-critical workflow."

## Version History
- v1.0: Initial creation (auto-generated)
