# AI-Powered Amazon Ads Campaign Architecture & Retail Media Intelligence Engine - Complete Amazon Advertising System for DTC, CPG, and E-Commerce Revenue Growth

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** amazon-ads, retail-media, paid-media, sponsored-products, amazon-dsp, e-commerce, dtc, cpg, performance-marketing

## Overview
Architect, launch, and continuously optimize full-funnel Amazon Advertising programs — spanning Sponsored Products, Sponsored Brands, Sponsored Display, and Amazon DSP — that drive measurable sales velocity, category share, and organic rank improvement for brands competing on the world's largest retail media network. Use this engine when you need to convert Amazon's 300M+ active shoppers into revenue, covering campaign structure, keyword strategy, bid optimization, ASIN targeting, creative for brand stores, and attribution from first impression to repurchase.

## Quick Copy-Paste Version

You are a senior Amazon Ads strategist with deep expertise in retail media and Sponsored Ads architecture. Build a complete Amazon Advertising campaign architecture for the following:

Company: [Your Company]
Product/ASIN: [Product name and ASIN]
Category: [Amazon product category — e.g., Health & Household, Beauty, Electronics]
Monthly budget: $[Amount]
Primary goal: [New customer acquisition / Sales velocity / Rank improvement / Brand awareness / Market share defense]
Current Amazon monthly revenue: $[Amount] or [New to Amazon]
Seller type: [Seller Central (3P) / Vendor Central (1P) / Both]

Deliver:

1. CAMPAIGN STRUCTURE (full-funnel Sponsored Ads architecture)
   - Sponsored Products: Auto + Manual campaigns with match type strategy
   - Sponsored Brands: Headline Search + Video Ads for category awareness
   - Sponsored Display: Retargeting + competitor ASIN targeting
   - Budget allocation across each campaign type

2. KEYWORD STRATEGY
   - Seed keyword discovery approach (auto campaign harvest + competitor reverse ASIN)
   - Match type segmentation (Exact, Phrase, Broad with modifiers)
   - Negative keyword strategy to eliminate wasted spend
   - Keyword bid strategy per funnel stage and intent level

3. ASIN TARGETING STRATEGY
   - Own ASIN defense (protect your PDPs from competitor ads)
   - Competitor ASIN conquest (target top 3-5 competitor listings)
   - Complementary product targeting (cross-sell and bundle opportunities)
   - Category targeting for broad awareness

4. BID OPTIMIZATION & BUDGET STRATEGY
   - Starting bid recommendations by match type and placement
   - When to use Dynamic Bidding (Down Only vs. Up and Down)
   - Placement bid adjustments (Top of Search vs. Rest of Search vs. PDP)
   - Budget pacing rules to avoid mid-day exhaustion

5. ACOS & PROFITABILITY TARGETS
   - Break-even ACOS calculation based on margins
   - Target ACOS by campaign type (launch vs. steady state vs. defense)
   - TACoS (Total ACOS including organic revenue) target and interpretation
   - Profitability guardrails for scaling decisions

6. CREATIVE & LISTING OPTIMIZATION
   - Sponsored Brands headline copy formula
   - Video ad script for 15-30 second Sponsored Brands Video
   - Amazon Storefront architecture recommendation
   - A+ Content modules to support conversion

7. FIRST 60-DAY LAUNCH PLAN
   - Days 1-14: Auto campaigns for keyword discovery
   - Days 15-30: Manual campaign builds from harvested data
   - Days 31-60: Optimization, negative harvesting, and scaling winners

Output structured as an executable campaign brief that a media buyer, brand manager, or AI agent can implement immediately in Amazon Ads Console.

## Advanced Customizable Version

ROLE: You are an Amazon Ads performance architect and retail media strategist with 10+ years running $500K–$10M/month Amazon Advertising programs for DTC brands, CPG companies, and private label sellers. You combine Amazon's auction-based ad system with organic rank science, Buy Box strategy, and retail media analytics to build self-optimizing revenue programs that drive both paid and organic sales velocity simultaneously. You understand how advertising investment compounds into organic rank improvement, which is the true flywheel of Amazon success.

COMPANY CONTEXT:
- Company: [COMPANY_NAME]
- Business model: [DTC brand / CPG company / Private label / Amazon-native brand / Omnichannel brand]
- Product category: [Amazon category] — [brief description of what the product does/solves]
- Hero ASIN(s): [List up to 5 primary ASINs to advertise]
- Average selling price on Amazon: $[X]
- Product COGS: $[X] (needed for ACOS break-even calculation)
- Amazon referral fee: [X%] (varies by category: 8-15% typical)
- FBA fee or fulfillment cost: $[X]
- Gross margin after COGS + Amazon fees: [X%]
- Monthly Amazon Ads budget: $[BUDGET]
- Current monthly Amazon revenue (organic + paid): $[X] or [New to Amazon]
- Seller type: [Seller Central (3P) / Vendor Central (1P)]
- Amazon market: [US / UK / EU / CA / AU / JP]
- Competitive ranking goal: [Reach top 3 BSR in subcategory / Defend #1 position / Enter new subcategory]

PRODUCT DETAILS:
- Primary benefit/use case: [Main job-to-be-done for the buyer]
- Key differentiator vs. top competitors: [Why a shopper should choose you over the #1 bestseller]
- Price positioning: [Premium / Mid-market / Value]
- Review count: [Current number of reviews] | Average rating: [X.X stars]
- Prime eligible: [Yes / No / FBA / SFP]
- Subscribe & Save eligible: [Yes / No] — if yes, S&S attach rate: [X%]
- Seasonal demand profile: [Year-round stable / Q4-heavy / Spring peak / Summer peak / Other]
- Top 3 competitor ASINs: [B0XXXXXXXX, B0XXXXXXXX, B0XXXXXXXX]

CURRENT AMAZON ADS PERFORMANCE (if already advertising):
- Monthly ad spend: $[X]
- Advertising Cost of Sale (ACoS): [X%]
- Total ACoS (TACoS): [X%]
- ROAS: [X]×
- Click-Through Rate (CTR): [X%]
- Conversion Rate (CVR): [X%]
- Top-performing campaign or keyword: [Name/term]
- Worst-performing spend category: [Auto / Broad / Competitor targeting / etc.]

---

DELIVERABLE 1: FULL-FUNNEL AMAZON ADS CAMPAIGN ARCHITECTURE

Design a multi-layer campaign structure using the Amazon Revenue Flywheel model — where paid advertising drives sales velocity, which improves organic rank, which generates organic revenue, which in turn lowers your effective TACoS over time.

CAMPAIGN LAYER 1 — SPONSORED PRODUCTS (Core Revenue Driver)

**1A: Auto Campaign — Keyword Discovery Engine**
Purpose: Let Amazon's algorithm identify converting search terms across all 4 auto targeting types
Auto Targeting Types:
  - Close match: Amazon shows ad when shopper searches for terms closely related to your product
  - Loose match: Amazon expands to adjacent terms in your category
  - Substitutes: Amazon shows ad on competitor ASIN detail pages
  - Complements: Amazon shows ad on complementary product pages
Bid strategy: Start at $0.75 flat bid across all targeting types; reduce Loose match to $0.50 after week 2
Daily budget: $[Monthly budget × 15% ÷ 30] — auto campaigns should receive 15% of total budget
Harvest cadence: Pull Search Term Report weekly; add any term with ≥5 clicks and ≥1 purchase to manual Exact campaigns; add high-spend/zero-conversion terms as negatives after $[2× product price] in spend without conversion
Negative keywords: Add brand terms as negatives (protect from cannibalizing brand traffic) + irrelevant variations

**1B: Manual Exact Campaign — Highest-Intent Buyers**
Purpose: Capture shoppers who search your precise converting keywords with maximum bid control
Keyword strategy:
  - Seed list: Pull from auto campaign winners + Helium 10 / Jungle Scout reverse ASIN lookup on top 3 competitors
  - Launch with 20-50 exact match keywords sorted by search volume and relevance
  - Structure: One Ad Group per keyword cluster (not all keywords in one ad group)
Starting bids: [Category average CPC × 1.2] — bid above average to secure top-of-search placement during launch
Dynamic bidding: Down Only during first 30 days (protect budget while learning); switch to Up and Down after CVR is established
Placement bid adjustments:
  - Top of Search: +50-80% (highest intent, highest conversion)
  - Product Detail Pages: +20-30% (moderate intent, good for cross-category discovery)
  - Rest of Search: +0% (baseline; optimize via negative placement over time)
ACOS target: [Break-even ACOS - 5%] for exact match (should be your most efficient campaign)
Budget allocation: 35% of total budget

**1C: Manual Phrase Campaign — Broader Intent Capture**
Purpose: Capture variations and modifiers of your core terms the Exact campaign misses
Strategy: Use top 10-15 exact match performers as phrase match seeds; phrase match captures "[your keyword] for men", "[keyword] bulk pack", "[keyword] gift set", etc.
Starting bids: [Exact match bid × 0.75] — phrase deserves slightly lower bid due to lower precision
Harvest cadence: Weekly; migrate converting phrase terms to Exact; negate non-converting at $[1.5× product price] threshold
Budget allocation: 20% of total budget

**1D: Manual Broad Campaign — Keyword Expansion Engine**
Purpose: Discover new keyword opportunities and expand your converting term universe
Strategy: Use broad match modifier (+keyword) to maintain some relevance control
Starting bids: [Exact match bid × 0.50] — broad is exploratory, not conversion-optimized
Rule: Never use standard broad match without modifiers; risk of irrelevant spend is too high
Budget allocation: 10% of total budget; treat as R&D spend

---

CAMPAIGN LAYER 2 — SPONSORED BRANDS (Category Awareness & Brand Building)

**2A: Sponsored Brands Headline Search — Category Conquest**
Format: Banner ad at top of search results page (above all Sponsored Products)
Creative components:
  - Headline: [Must include brand name + primary category keyword + benefit claim in ≤50 characters]
  - Logo: Brand logo (minimum 400×400px, no white border)
  - Products shown: Feature hero ASIN + 2 complementary ASINs or top variants
  - Landing destination: Amazon Storefront (not individual ASIN — drives higher cart value)
Headline formula: "[Brand Name] — [Category Claim]: [Top Benefit]"
Example: "NovaSkin — #1 Rated SPF Moisturizer: Lightweight, Reef-Safe, 48-Hour Protection"
Keyword targeting: Focus on your top 20 exact match converting keywords + category-level broad terms
Bid: [Exact match SP bid × 1.3] — SB placement is more competitive; premium worth it for brand building
Budget allocation: 10% of total budget

**2B: Sponsored Brands Video — Story-Led Demand Capture**
Format: Auto-play video ad in middle of search results; 15-30 seconds; plays silently (captions required)
Video script framework (for 30-second version):
  - 0-3 sec: Visual hook — show the problem or the product's most dramatic benefit (must work without sound)
  - 3-10 sec: Product in use — show the real-world application; real people, not studio models
  - 10-22 sec: Key benefit callouts — 3 text overlays of your top 3 differentiators
  - 22-27 sec: Social proof — star rating + review count on screen ("4.8★ from 12,000+ reviews")
  - 27-30 sec: Logo + CTA + Offer callout ("Subscribe & Save 15%" or "Pack of 3 available")
Targeting: Target your top keyword cluster in Exact match; SB Video often achieves lower CPCs than standard SB
Required caption file: .SRT format; Amazon requires captions for all video ads
Budget allocation: 5% of total budget (test, then scale based on VCTR and branded search lift)

---

CAMPAIGN LAYER 3 — SPONSORED DISPLAY (Retargeting & ASIN Conquest)

**3A: Views Retargeting — Re-Engage Browsers Who Didn't Buy**
Purpose: Show ads to shoppers who viewed your ASIN but did not purchase within 7-30 days
Audience: Product views — audiences who viewed your ASIN(s) in the last 7, 14, or 30 days (create separate campaigns per lookback window; 7-day is highest intent)
Creative: Use lifestyle image + benefit headline + star rating badge
Bid: $0.35-0.60 CPM starting point; optimize to Target CPA
Budget allocation: 5% of total budget
Attribution: 14-day click, 14-day view — Sponsored Display has longer attribution windows; account for this in ACOS interpretation

**3B: Competitor ASIN Conquest — Steal Category Share**
Purpose: Show your product ad on competitor product detail pages to intercept in-market buyers
Targeting method: Individual ASIN targeting (list top 10-20 competitor ASINs) + Category-level targeting as secondary
Ad placement: Appears in "Sponsored products related to this item" section on competitor PDP
Creative strategy: Use your price advantage, review count superiority, or key differentiator vs. the specific competitor being targeted — create custom ads per competitor cluster if budgets allow
Expected CVR: Lower than keyword (0.5-1.5%) but high intent — shopper is in active purchase mode
Bid: $0.40-0.80 CPC; start conservative, optimize weekly
Budget allocation: 5% of total budget

**3C: Own ASIN Defense — Block Competitor Ads on Your Listings**
Purpose: Prevent competitors from running Sponsored Display on your own PDPs
Targeting: Target your own ASINs with Sponsored Display ads linking back to your Storefront or hero ASIN
Budget needed: Minimal — even $10-20/day per ASIN significantly reduces competitor placement frequency
This is defensive spend — measure by reduction in competitor ads visible on your PDPs (audit manually monthly)

---

DELIVERABLE 2: KEYWORD BID STRATEGY & ACOS ECONOMICS

BREAK-EVEN ACOS CALCULATION:
Break-even ACoS = Gross Margin % after Amazon fees
Formula: (Selling Price - COGS - Amazon Referral Fee - FBA Fee) ÷ Selling Price = Break-even ACoS
Example: ($39.99 selling price - $8 COGS - $6 referral fee - $5 FBA fee) ÷ $39.99 = 52.5% break-even ACoS

Target ACoS by campaign type:
- Launch phase (months 1-3): Accept up to [Break-even ACoS + 10%] — invest in velocity and rank
- Steady state (months 4+): Target [Break-even ACoS - 10 to 15%] — profitability zone
- Defense campaigns (own brand/ASIN): Accept up to [Break-even ACoS] — these protect organic rank
- Competitor conquest: Target [Break-even ACoS - 5%] — these should pay their own way

TACoS INTERPRETATION:
Total ACoS = Total Ad Spend ÷ Total Amazon Revenue (organic + paid)
- TACoS > ACoS: Your organic revenue is growing (the flywheel is working) — this is good
- TACoS = ACoS: 100% of your revenue is paid (no organic lift yet — normal in launch)
- TACoS target for mature brand: [5-15%] depending on category competitiveness and margin structure
- Improvement benchmark: Every percentage point TACoS drops = more organic rank contribution from paid investment

BID LADDER STRATEGY:
Starting bids by match type (adjust based on category CPC benchmarks):

| Match Type | Starting Bid | Rationale |
|---|---|---|
| Exact (top terms) | $1.20-2.50 | Highest precision; pay for top placement |
| Exact (secondary) | $0.75-1.20 | Good terms, lower competition |
| Phrase | $0.65-0.90 | Slightly lower intent than exact |
| Broad (+modifier) | $0.40-0.65 | Exploration budget |
| Auto (close) | $0.75-1.00 | Amazon's best guess |
| Auto (loose) | $0.50-0.65 | Cast wider net |
| SD Retargeting | $0.35-0.60 CPM | Re-engagement; lower urgency |
| SD Competitor | $0.50-0.80 CPC | Higher intent interception |

PLACEMENT BID MULTIPLIERS:
- Top of Search: +50% adjustment starting bid — Amazon shows data that top-of-search CVR is 2-3× higher than other placements; premium is worth paying for proven exact match terms
- Product Detail Pages: +20% for competitor ASIN conquest campaigns
- Rest of Search: 0% adjustment; monitor performance and adjust based on 30-day ACOS data

---

DELIVERABLE 3: CREATIVE SYSTEM FOR AMAZON ADS

SPONSORED BRANDS HEADLINE FORMULA:
Framework: [Brand] + [Category Differentiator] + [Primary Benefit] + [Social Proof Signal]
Headlines that win on Amazon follow the "Search Intent Mirror" principle — reflect exactly what the shopper typed, then immediately justify the premium.

5 headline templates for [COMPANY_NAME]:
1. "[Brand] [Category]: [#1 Benefit]. [Social Proof Signal]"
   → "Zestify Protein: 25g Per Serving. 4.9★ from 8,200 Customers"
2. "Best [Category] for [Primary Use Case] — [Brand]"
   → "Best Pre-Workout for Women — Zestify. Clean Label, No Crash."
3. "[Brand]: [Differentiation claim] + [Secondary Benefit]"
   → "Zestify: No Artificial Sweeteners + 3rd-Party Lab Tested"
4. "Save [X%] on [Category] — [Brand] Subscribe & Save"
   → "Save 20% on Protein Powder — Zestify Subscribe & Save"
5. "[Category] That [Key Problem Solved] — [Brand]"
   → "Protein Powder That Mixes Instantly — Zestify. No Clumping."

SPONSORED BRANDS VIDEO SCRIPT (30-second template):
[0-3s] HOOK: Visual close-up of hero product benefit being experienced — no voiceover needed; pure visual impact. Text overlay: "[Biggest Pain Point You Solve]?"
[3-10s] PRODUCT IN USE: Lifestyle shot of real person using the product in the natural context where it's purchased (kitchen, gym, bathroom, office). Text overlay: "[Brand Name] [Product Type]"
[10-18s] BENEFIT CALLOUTS: Three consecutive text cards (2-3 seconds each):
  → Card 1: "[Primary functional benefit + proof point]"
  → Card 2: "[Secondary benefit or differentiator]"
  → Card 3: "[Third differentiator or ingredient/material callout]"
[18-25s] SOCIAL PROOF: Star rating fills in animated on screen + "[X,XXX] 5-star reviews on Amazon"
[25-30s] BRAND CLOSE: Logo + product shot + "[Primary CTA]" + "Prime delivery available"
Audio note: Design for silent viewing; captions for every spoken word; background music at 15-20% volume

AMAZON STOREFRONT ARCHITECTURE (for Sponsored Brands landing):
Page 1 — Hero Brand Page:
  - Above fold: Brand video or hero lifestyle image (1500×600px desktop)
  - Below fold: Top 4 hero ASINs with star ratings displayed
  - Module: "Why [Brand Name]?" — 3-column feature grid with icons
  - Module: Customer reviews carousel (pull 5 best written reviews)
  - Module: "Best Sellers" — top 4 products by units sold

Page 2 — [Hero Category] (link from Sponsored Brands headline campaigns):
  - Product grid filtered to hero subcategory
  - Video module: Product demo or testimonial video
  - Comparison chart if multiple variants (flavors, sizes, types)

Page 3 — Bundles & Value Packs (high AOV page):
  - Link here from "Subscribe & Save" or bundle-focused Sponsored Brands ads
  - Show savings calculator: "Buy individually: $X / Buy bundle: $X (Save Y%)"
  - Module: "Frequently Bought Together" ASINs

A+ CONTENT MODULES FOR HERO ASIN (supports conversion rate improvement):
Module 1: Brand story header with lifestyle photography — "Who We Are & Why We Created This"
Module 2: Comparison chart — your product vs. generic category standard (features you win on)
Module 3: Ingredient/material callout grid — 4-6 icons with brief explanations of key differentiators
Module 4: Use case scenarios — 3 different buyer archetypes and how they use the product
Module 5: Subscribe & Save value proposition — highlight cost per use vs. one-time purchase

---

DELIVERABLE 4: NEGATIVE KEYWORD STRATEGY

Proactive Negative Keywords (add before launch):
- [Brand name]: Add to non-branded campaigns to prevent cannibalization
- [Competitor brand names]: Add to your own brand and generic campaigns (let competitor campaigns target these separately)
- Irrelevant modifiers: wholesale, bulk industrial, commercial, used, refurbished (unless you sell these)
- Wrong demographic signals: [e.g., "men" if you're a women's product; "kids" if adult-only]
- Wrong format signals: [e.g., "digital download" for physical products; "subscription box" if individual sale]
- DIY/how-to terms: "how to make", "DIY", "recipe" — searchers are not in buying mode
- Jobs/career terms: "jobs", "careers", "wholesale opportunity"

Reactive Negatives (add weekly from Search Term Reports):
Rule 1: Any search term with ≥$[2× product price] in spend and zero orders → add as Exact negative at ad group level
Rule 2: Any search term where ACoS > [Break-even ACoS × 2] over 30+ days → add as Phrase negative to isolate and control
Rule 3: Any search term with CTR < 0.1% over 1,000+ impressions → indicates irrelevance; add as Exact negative
Rule 4: Any search term already captured in your Exact match campaign → add as Exact negative to Auto and Phrase campaigns to prevent internal auction competition

Negative Match Type Strategy:
- Add most irrelevant terms as Exact negatives (surgical; only blocks that precise term)
- Add broader category mismatches as Phrase negatives (blocks the term and all terms containing it)
- Use Campaign-level negatives for cross-campaign budget protection; use Ad Group-level for precision

---

DELIVERABLE 5: AMAZON DSP STRATEGY (Advanced — $20K+/month programs)

Amazon DSP (Demand-Side Platform) runs programmatic display ads both on and off Amazon — on Amazon properties (Fire TV, Alexa, Kindle, IMDb), Amazon-owned apps, and third-party websites. This is the "awareness" layer above Sponsored Ads.

When to add DSP:
- Sponsored Ads ACoS is at target and you've exhausted keyword expansion
- Category has a long consideration cycle (furniture, electronics, B2B supplies)
- Building brand awareness for a new product category entry
- Retargeting Amazon shoppers across the open web

DSP Audience Segments available:
- In-Market: Amazon shoppers actively browsing your category in the last 30 days (highest intent)
- Lifestyle: Shoppers who regularly buy in your broader category (health-conscious, outdoor enthusiast, etc.)
- Retargeting: Visitors to your ASIN or Storefront who did not purchase (mirrors Sponsored Display)
- Lookalike: Modeled off your recent purchaser audience

DSP Recommended Entry Strategy ($20K/month):
- Allocation 1: 60% to In-Market retargeting (highest ROI; lowest risk for DSP beginners)
- Allocation 2: 25% to ASIN retargeting (viewers who viewed your PDP but did not buy in last 14 days)
- Allocation 3: 15% to Lifestyle/In-Market prospecting for new customer acquisition
- Attribution note: DSP uses 14-day view-through attribution; benchmark separately from Sponsored Ads; look for branded search lift and direct sales lift in DSP-exposed audiences vs. control

---

DELIVERABLE 6: WEEKLY OPTIMIZATION PROTOCOL (AI-Ready Checklist)

MONDAY — Keyword & Bid Review:
□ Pull Search Term Report (last 7 days): Add converting terms to Exact manual; add waste terms as negatives
□ Review Keyword Performance report: Identify keywords with ACoS > [Break-even + 20%] over 14+ days; reduce bid by 15-20%
□ Identify keywords with ACoS < [Target ACoS - 15%] and impression share < 30%; increase bid 10-15% to capture more top-of-search real estate
□ Check for keywords with zero impressions (bid too low or quality threshold unmet) — increase bid 20% or add to Sponsored Brands for broader reach

WEDNESDAY — Campaign Structure Review:
□ Check budget utilization per campaign: Any campaign hitting daily budget cap before 8pm local time → increase budget 20% or restrict hours to highest-conversion windows
□ Review Placement Report: If Top of Search ACoS is significantly lower than Rest of Search, increase Top of Search placement bid multiplier +10%
□ Auto campaign check: Harvest any auto term with ≥3 orders in 7 days; add to Exact manual at winning bid
□ Review Sponsored Display ACOS: SD has 14-day click attribution; give 14 days before optimization judgment

FRIDAY — Creative & ASIN Review:
□ Check Sponsored Brands CTR by headline: If < 0.35%, test new headline variation
□ Review Sponsored Brands Video: If video completion rate < 40%, first 3 seconds need rework
□ Check your PDP: Are competitor Sponsored Products showing on your listing? → Increase SD own-ASIN defense budget
□ Review BSR trend (Best Seller Rank): Is rank improving week-over-week? Advertising → sales velocity → organic rank is the core flywheel metric

MONTHLY — Strategic Review:
□ TACoS trend analysis: Is TACoS declining quarter-over-quarter? (Should be as organic rank grows)
□ Harvest top 30 exact match keywords driving both paid and organic sales — these are your rank-building priorities
□ Review Share of Voice: Run a SERP audit for your 10 most important keywords — how often do your Sponsored Products, Sponsored Brands, and Sponsored Display ads appear?
□ Competitive audit: Run reverse ASIN on top competitors using Helium 10 or DataDive — have they added new keywords you should be targeting?
□ Review Subscribe & Save metrics: Are S&S subscribers driving TACoS improvement? If S&S % is growing, ACOS targets can be relaxed (LTV justifies higher acquisition cost)

---

DELIVERABLE 7: 60-DAY LAUNCH ROADMAP

WEEK 1-2 (Days 1-14): Foundation & Discovery
- Day 1: Set up Auto campaign (all 4 targeting types) for hero ASIN at conservative bids
- Day 2: Build initial Exact Manual campaign from seed keyword list (Helium 10 / JS reverse ASIN + customer language from reviews)
- Day 3: Build Sponsored Brands Headline Search campaign targeting top 20 exact keywords; link to Storefront
- Day 5: Set up Sponsored Display retargeting on own ASIN views (7-day and 30-day lookback)
- Day 7: First Search Term Report pull — add early converters to Exact manual; add obvious waste as negatives
- Day 14: Performance review — confirm pixel/attribution setup; pause any keyword with >$[3× product price] spend and zero orders

WEEK 3-4 (Days 15-30): Data-Informed Manual Campaign Build
- Expand Exact manual campaign with top 15 new terms harvested from Auto
- Build Phrase match campaign using top exact performers as seeds
- Launch Sponsored Display competitor ASIN targeting on top 3 competitor ASINs
- Add first round of reactive negatives to all campaigns based on Search Term Reports
- Upload A+ Content to hero ASIN if not already live (direct impact on CVR)
- Launch Broad +modifier campaign for continued keyword discovery
- Establish first baseline ACoS benchmark by campaign type; document for Month 2 comparison

WEEK 5-6 (Days 31-44): Optimization & Scale
- Bid optimization round 1: Increase bids for keywords with ACoS < target; decrease for keywords > 2× target
- Analyze Placement Report: Adjust Top of Search and PDP bid multipliers based on conversion data by placement
- Launch Sponsored Brands Video (if creative is ready) — target your top 10 exact keywords
- Test second Sponsored Brands headline variation against Week 1 control
- Evaluate Auto campaign targeting types individually: pause under-performers, increase budget for close match if it's efficient

WEEK 7-8 (Days 45-60): Full Funnel Running & 60-Day Audit
- Full campaign structure live: SP Auto + SP Exact + SP Phrase + SP Broad + SB Headline + SB Video + SD Retargeting + SD Competitor
- Calculate first TACoS: Total ad spend ÷ total Amazon revenue (paid + organic)
- Evaluate BSR trend: Is organic rank improving? Paid velocity → organic rank improvement should be visible by Day 45-60
- Present 60-day report: Spend, ACoS, TACoS, BSR trend, top 20 converting keywords, negative keyword actions, Month 3 scaling plan

Output the entire campaign architecture as a structured brief that can be handed directly to an Amazon Ads media buyer, e-commerce brand manager, or AI agent for immediate implementation.

## Example Input/Output

**Input Example:**
Company: BrewHaven (DTC premium coffee subscription brand expanding to Amazon)
Product: Single-Origin Ethiopian Pour-Over Coffee, 12oz bag, ASIN: B08XYZ1234
Category: Grocery & Gourmet Food → Coffee
Monthly budget: $8,000
Goal: Establish presence, achieve top 20 BSR in "single origin coffee" subcategory within 90 days
Current Amazon monthly revenue: $4,200 (mostly organic, minimal ads)
Price: $18.99 | COGS: $5.50 | Amazon referral fee: $1.90 (10%) | FBA fee: $3.20
Break-even ACoS: ($18.99 - $5.50 - $1.90 - $3.20) ÷ $18.99 = 44.7%
Competitor ASINs: B07ABC2345 (42,000 reviews, #1 BSR), B09DEF3456 (8,200 reviews, #3 BSR)

**Output Example (excerpt):**

---
**CAMPAIGN ARCHITECTURE OVERVIEW — BREWHAVEN**

**ACOS TARGET FRAMEWORK:**
- Break-even ACoS: 44.7%
- Launch phase (months 1-3): Accept up to 54% ACoS — invest in velocity for rank
- Steady state target: 35% ACoS (8.7 points below break-even = profitability)
- TACoS target (month 3): < 25% (meaning 63%+ of revenue comes from organic rank)

**CAMPAIGN 1 — SP Auto Discovery**
- Daily budget: $40 (15% of $8K monthly ÷ 30)
- Bids: Close match $0.85 | Loose match $0.55 | Substitutes $0.65 | Complements $0.50
- Harvest trigger: Any term with ≥2 orders → add to Exact manual within 7 days
- Expected output in 30 days: 40-80 converting search terms ready for Exact campaign migration

**CAMPAIGN 2 — SP Exact Manual (Precision Conversion)**
- Seed keywords (from Helium 10 reverse ASIN on top 2 competitors):
  - "single origin coffee" (18,000 monthly searches) — bid $1.45
  - "ethiopian pour over coffee" (9,200 searches) — bid $1.20
  - "light roast coffee beans" (24,000 searches) — bid $1.10
  - "specialty coffee amazon" (6,800 searches) — bid $1.35
  - "fair trade coffee" (11,200 searches) — bid $0.95
- Daily budget: $93 (35% of monthly ÷ 30)
- Placement multipliers: Top of Search +60% | PDP +25%
- Expected ACoS at target bids: 42-48% in launch phase

**CAMPAIGN 4 — Sponsored Brands Headline**
- Headline: "BrewHaven — Single-Origin Ethiopian Coffee: Specialty Grade. Fair Trade. Prime Delivery."
- Keywords: Top 20 exact match from Exact SP campaign
- Landing: BrewHaven Storefront → Coffee category page
- Budget: $27/day (10%)

**SPONSORED BRANDS VIDEO BRIEF:**
- 0-3s: Extreme close-up of coffee being poured from a glass kettle into a pour-over — the slow, beautiful, golden stream (no text needed; visual does the work)
- 3-10s: Hands cradling a warm mug; waft of steam; comfortable morning setting. Text: "BrewHaven Ethiopian Single-Origin"
- 10-18s: Three text cards: "Direct trade from Yirgacheffe" → "Roasted within 48hrs of your order" → "Cupping score: 87+"
- 18-25s: ⭐⭐⭐⭐⭐ animates in. "4.8 stars from 2,100 Amazon reviews"
- 25-30s: Logo + bag product shot + "Subscribe & Save: Save 15% on every order"

**PROJECTED PERFORMANCE AT 60 DAYS:**
- Monthly ad spend: $8,000
- Paid revenue (at 4.2× ROAS on converting campaigns): $33,600
- Organic revenue (baseline + rank lift): $8,400 (organic growing from velocity)
- Total Amazon revenue: $42,000
- TACoS: 19% ($8,000 ÷ $42,000) — ahead of target
- BSR trend: Category rank improvement from ~850 to ~180 in "single origin coffee"
- Subscribe & Save attach rate target: 25%+ by month 3 (LTV multiplier; justifies continued ad investment)

---

## Success Metrics

**Campaign Efficiency Metrics (track weekly):**
- ACoS by campaign type: Exact should be lowest; Broad/Auto should be highest (tolerated as research spend)
- TACoS trend: Must be declining quarter-over-quarter as organic rank grows from paid velocity investment
- Click-Through Rate (CTR): Sponsored Products top-of-search target > 0.35%; SB Headline target > 0.45%; SB Video target > 0.30%
- Conversion Rate (CVR): Category average is 10-15%; target yours at [Category average + 20%] — listing quality drives this
- Cost Per Click (CPC): Track vs. category benchmark; significant CPC inflation = increased competitor ad pressure

**Organic Rank & Flywheel Metrics (track weekly):**
- Best Seller Rank (BSR): Track main category and subcategory rank daily during launch; expect 2-3% weekly improvement when velocity targets met
- Organic rank position: For your top 10 keywords, track position 1-30 in Helium 10 / DataDive weekly
- Organic revenue %: As % of total Amazon revenue; target > 50% by month 6 (indicates flywheel is spinning)
- Sessions vs. Units Ordered rate: Amazon's internal CVR signal; impacts organic rank algorithm

**Profitability Metrics (track monthly):**
- Blended ACoS across all campaign types: Target [Break-even ACoS - 10%] in steady state
- TACoS (Total ACoS): The north star metric; target < 15% for mature, well-ranked product
- New-to-Brand % (available in Sponsored Brands and SP reports): Target > 60% from advertising (acquiring new customers, not just convincing repeat buyers to click ads)
- Subscribe & Save revenue contribution: If applicable, target 20-35% of repeat sales on S&S (dramatically improves LTV and lowers effective TACoS)

## Related Prompts
- [`AI-Powered-Google-Ads-Campaign-Architecture-&-Performance-Max-Intelligence-Engine.md`](./AI-Powered-Google-Ads-Campaign-Architecture-&-Performance-Max-Intelligence-Engine.md) — Google Shopping and Search ads to drive external traffic to Amazon listings or DTC site
- [`AI-Powered-Meta-Ads-Campaign-Architecture-&-Advantage-Plus-Intelligence-Engine.md`](./AI-Powered-Meta-Ads-Campaign-Architecture-&-Advantage-Plus-Intelligence-Engine.md) — Meta Ads for off-Amazon demand creation that feeds Amazon search volume
- [`../../05_Analytics-&-Performance/Paid-Media-&-PPC-Performance-Analytics/Amazon-Ads-Performance-Analytics-&-Retail-Media-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Paid-Media-&-PPC-Performance-Analytics/Amazon-Ads-Performance-Analytics-&-Retail-Media-Intelligence-Engine.md) — Deep performance analytics, TACoS optimization, and Share of Voice measurement for ongoing Amazon Ads programs
- [`../../02_Product-Marketing/Go-To-Market-Strategy/SaaS-Pricing-Strategy-&-Packaging-Intelligence-Engine.md`](../../02_Product-Marketing/Go-To-Market-Strategy/SaaS-Pricing-Strategy-&-Packaging-Intelligence-Engine.md) — Pricing strategy framework applicable to Amazon price positioning and pack size architecture

## Integration Tips

**Shopify + Amazon Multi-Channel (DTC + Amazon simultaneously):**
- Use Amazon Attribution tags on all external traffic sources (Meta, Google, email) to measure off-Amazon ad contribution to Amazon sales — critical for omnichannel brands proving multi-touchpoint ROI
- Sync Shopify customer email list to Amazon Ads as a Custom Audience (requires Amazon Marketing Cloud access) to model lookalikes from your best buyers
- Use Amazon Buy with Prime on your Shopify DTC site — lets shoppers checkout using Amazon Prime benefits, increases DTC CVR 25-30% for Prime-loyal buyers
- Connect inventory management (Skubana, Linnworks, Cin7) to prevent stockouts during ad-driven velocity spikes — running out of stock during a ranking phase resets BSR gains and wastes ad spend

**HubSpot / Salesforce (B2B brands on Amazon Business):**
- Amazon Business (separate from consumer marketplace) serves 6M+ registered business buyers; if you sell B2B supplies (office products, industrial, MRO), run separate B2B campaigns in Amazon Ads Console targeting "Business Customers Only"
- Use Amazon Attribution to track which B2B buyer accounts discover via Amazon → then show up in your CRM via direct sales motion; build cross-channel attribution for enterprise accounts
- Connect Amazon seller data with CRM to identify when existing CRM accounts are purchasing on Amazon (fragmented buying signal) vs. going through your direct sales channel

**Helium 10 / Jungle Scout / DataDive (Third-Party Research):**
- Helium 10 Cerebro: Run reverse ASIN on top 3 competitors monthly — export all keywords driving their traffic; import top 50 into your Exact manual campaigns
- Helium 10 Magnet: Pull keyword search volume trends; identify rising keywords before they peak and bids inflate
- DataDive: Multivariate analysis of what top 10 BSR listings have in common (title keywords, bullet point structure, image count, A+ Content) — reverse-engineer the algorithm's listing preference for your category
- Jungle Scout Opportunity Finder: Identify adjacent subcategories where demand is growing but competition is still low; prime targets for Sponsored Products expansion into new keyword clusters

**Amazon Marketing Cloud (AMC — Advanced Attribution):**
- AMC is Amazon's clean room analytics environment — available to DSP advertisers and enterprise Sponsored Ads accounts
- Use AMC to run path-to-purchase analysis: How many shoppers saw a Sponsored Display ad, then a Sponsored Brand, then converted via Sponsored Products? (Multi-touch attribution within Amazon)
- Build custom audience segments in AMC: Shoppers who viewed product but didn't buy in 45+ days (high-intent lapsed); shoppers who bought once but haven't reordered (Subscribe & Save pitch audience)
- AMC new-to-brand analysis: What % of Sponsored Brands purchasers were genuinely new customers who had never bought your brand on Amazon before? Benchmark target: > 60%

**Zapier / Make Automation:**
- Trigger: ACoS exceeds [Break-even ACoS + 15%] for any campaign for 3 consecutive days → Pause campaign → Slack alert to Amazon Ads manager
- Trigger: New seller feedback or product review posted → Notify brand manager in Slack for response within 24 hours (review velocity and star rating directly impact organic rank)
- Trigger: BSR drops below target rank → Increase BOFU Sponsored Products budget 20% automatically → Re-evaluate after 72 hours
- Trigger: Weekly Amazon Ads report export → Populate Google Sheets TACoS dashboard → Email marketing team Monday morning with spend/revenue/TACoS vs. prior week

## Troubleshooting

**Problem: ACoS is 2-3× above target despite 4+ weeks of data and bid adjustments**
Solution: Diagnose in this priority order — (1) Listing conversion rate first: If CTR is healthy (>0.35%) but CVR is low (<8%), the problem is your product detail page, not your campaigns. Your main image, title, bullet points, price, or review count is failing to convert browsers. Fix the listing before optimizing bids. (2) Price competitiveness: Run a price comparison against your top 3 Buy Box competitors — if you're priced >15% above the average for comparable products, no bid strategy will overcome the conversion handicap. (3) Keyword relevance: Pull Search Term Report and sort by spend; are you paying for searches that are not about your product? Add these as negatives. High-spend/low-relevance terms (especially from Broad and Auto) are the most common cause of inflated ACoS. (4) Bid inflation in a competitive category: If CPCs have risen industry-wide (common in Q4, Prime Day, and competitive niches), your target ACoS may simply need temporary relaxation — accept break-even ACoS for 30 days while organic rank compounds.

**Problem: Good ACoS on Sponsored Products but sales velocity is flat — organic rank not improving**
Solution: Paid sales alone drive BSR and organic rank, but Amazon's A10 algorithm also weights conversion rate, session volume, and velocity consistency. Check: (1) Are you running ads 24/7 or only certain hours? Budget exhaustion mid-day creates velocity gaps that confuse the algorithm — ensure budget is sufficient to run continuously; (2) Confirm your campaigns are targeting keywords where you actually appear — use Amazon's "Search Query Performance" report to verify impressions; if you have zero impressions on your target keywords, either your bid is below first-page threshold or your listing relevance score is too low (add the keyword to your title/bullets if absent); (3) Review rate and recency: Amazon's algorithm weights recent review velocity; if your review rate has declined, velocity improvements from ads won't translate to rank as efficiently — implement a compliant review request sequence via Amazon's "Request a Review" button (accessible via Seller Central).

**Problem: Competitor Sponsored Display ads are appearing on my product detail page and stealing sales**
Solution: This is an own-ASIN defense problem. Implement Sponsored Display own-ASIN targeting immediately: (1) Create a Sponsored Display campaign, select "Product Targeting," and enter your own ASIN(s) as targets — your ads will then fill the placement competitor ads are occupying; (2) Set a modest daily budget ($10-20/day per ASIN) — even partial coverage significantly reduces competitor visibility; (3) Use your best lifestyle image + a compelling headline ("The original [category] — 4.8★") to win back the conversion intent; (4) Long-term solution: As your BSR improves organically, your PDPs become less attractive to competitor conquest (lower ROAS for them) — organic rank defense is the ultimate answer to Sponsored Display competition.

## Version History
- v1.0: Initial creation (auto-generated)
