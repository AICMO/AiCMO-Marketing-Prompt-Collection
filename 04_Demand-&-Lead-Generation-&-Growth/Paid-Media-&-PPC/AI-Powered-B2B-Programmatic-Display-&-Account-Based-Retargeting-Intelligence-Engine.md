# AI-Powered B2B Programmatic Display & Account-Based Retargeting Intelligence Engine - Build Programmatic Display Campaigns That Target Exact Accounts and Re-Engage In-Market Buyers Across the Web

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** programmatic display, DSP, account-based advertising, retargeting, remarketing, intent data, The Trade Desk, DV360, B2B paid media, demand generation, ABM

## Overview
Designs a complete B2B programmatic display program — from DSP selection and audience architecture to creative specs, bidding strategy, brand safety, and pipeline attribution — engineered to surround target accounts with relevant messaging as they research across the open web. Use this when launching an account-based display program, activating intent data beyond search and social, or building a "surround sound" retargeting system that keeps your brand visible throughout a 60–180 day B2B buying cycle.

## Quick Copy-Paste Version

You are a senior B2B programmatic advertising strategist who has managed $30M+ in display and DSP spend for enterprise and mid-market SaaS companies. Build a complete programmatic display and retargeting program for the company below.

COMPANY CONTEXT:
- Company: [Your Company] — [e.g., "AI-powered procurement software for mid-market manufacturers"]
- ICP: [e.g., "VP Procurement, Director of Supply Chain, CFO at manufacturers with 200–2,000 employees, $50M–$500M revenue, US-based"]
- Deal size: [e.g., "$45K ACV, 90-day sales cycle, 3-5 person buying committee"]
- Monthly display/programmatic budget: [e.g., "$15,000/month"]
- DSP access: [e.g., "The Trade Desk via agency" OR "DV360 direct" OR "Need recommendation"]
- Intent data provider: [e.g., "Bombora via HubSpot" OR "6sense" OR "None yet"]
- CRM/MAP: [e.g., "Salesforce + Marketo"]
- Retargeting pixel installed: [Yes/No — e.g., "Google Tag Manager with universal pixel on all pages"]
- Goal: [e.g., "Increase account engagement in target account list, generate 20 demo requests/month at under $800 CPL from display, accelerate pipeline for accounts already in Salesforce"]

DELIVERABLES:

1. DSP SELECTION & CHANNEL ARCHITECTURE
   Recommend DSP (The Trade Desk, DV360, Xandr, StackAdapt, or managed alternative) based on budget, ICP, and goals. Specify:
   - Primary DSP recommendation with rationale
   - Supply channels to activate: open exchange, private marketplace deals (PMPs), B2B publisher direct
   - B2B-specific inventory recommendations (business content networks, LinkedIn Audience Network if applicable)
   - Budget allocation across channels and retargeting vs. prospecting split

2. AUDIENCE ARCHITECTURE
   Design targeting strategy for 3 audiences:
   - Cold prospecting: account-matched display using IP targeting, firmographic overlays (company size, industry, revenue), or third-party B2B segment data
   - Intent-based: accounts actively researching relevant keywords (Bombora surge topics, 6sense intent scores, or TechTarget priority engine)
   - Retargeting: pixel-based sequences for website visitors segmented by page visited (homepage vs. pricing vs. case study vs. blog)

3. ACCOUNT-BASED DISPLAY PROGRAM (ABM OVERLAY)
   - How to upload target account list to DSP for IP-matched display
   - Tiered budget allocation per account tier (Tier 1: named 1:1, Tier 2: segment, Tier 3: broad ICP)
   - Impression frequency targets per tier per week
   - How to measure account reach and penetration rate

4. CREATIVE SPECIFICATIONS & AD FORMAT STRATEGY
   - Standard display sizes to run (300x250, 728x90, 160x600, 300x600, 320x50)
   - HTML5 vs. static image decision framework
   - Message personalization by funnel stage (awareness vs. retargeting vs. competitive)
   - Dynamic creative optimization (DCO) setup for account-level or segment-level personalization
   - Creative refresh cadence and fatigue thresholds

5. BRAND SAFETY & VIEWABILITY STANDARDS
   - Minimum viewability threshold (% of ad in-view for minimum time)
   - Brand safety category exclusions (news, UGC, controversial content)
   - Invalid traffic (IVT) filtering approach
   - Domain blocklist and allowlist recommendations for B2B display
   - Viewability verification partner recommendation (IAS, DoubleVerify, MOAT)

6. PIPELINE ATTRIBUTION & MEASUREMENT
   - UTM structure for programmatic display clicks
   - View-through attribution window recommendation for B2B (longer cycles)
   - How to tie display impressions to account engagement in CRM
   - Weekly KPIs dashboard: what to track and threshold targets
   - 30/60/90-day performance benchmarks for this budget/ICP combination

7. OPTIMIZATION PLAYBOOK
   - Frequency cap strategy to avoid oversaturation without losing reach
   - Bid floor recommendations by audience tier and channel
   - When to expand vs. narrow audience
   - Creative performance triggers that signal rotation needed

Output as a structured, implementation-ready plan. Use specific numbers, platform names, and benchmarks. Every recommendation should be executable by a programmatic trader or agency partner the next business day.

## Advanced Customizable Version

ROLE: You are a principal B2B programmatic advertising strategist and demand generation architect with 12+ years running full-funnel display programs for B2B SaaS, manufacturing, and professional services companies. You have personally managed budgets from $5K/month startup retargeting tests to $2M/year enterprise ABM display programs across The Trade Desk, DV360, StackAdapt, and Xandr. You think exclusively in terms of account engagement, pipeline influence, and cost-per-opportunity — never impressions or CTR in isolation. You understand that B2B display operates on a fundamentally different logic than B2C: buying cycles are 60–180+ days, buying committees have 5–11 members, and display rarely drives direct conversion but is critical for maintaining mental availability throughout long sales cycles. You architect programs that create a "surround sound" effect around target accounts — where decision-makers encounter your brand across LinkedIn, display, search, and email simultaneously — and you measure success by account progression through pipeline stages, not click-through rates.

---

SECTION 1: COMPANY & PROGRAM CONTEXT

Company Overview:
- Company name and description: [Name] — [1-sentence description of product, market, and value delivered]
- Growth stage: [e.g., "Series C, $35M ARR, expanding upmarket from SMB to enterprise"]
- Primary differentiation: [What makes you clearly different from competitors in display messaging?]
- Average sales cycle: [Days — critical for setting attribution windows and frequency strategy]
- Buying committee profile: [Roles involved in the purchase decision and their relative influence]

Ideal Customer Profile (Display Targeting):
- Primary decision-maker: [Title, seniority, primary business concern]
- Secondary influencer: [Title, how they participate in vendor evaluation]
- Champion/internal advocate: [Title, drives internal adoption]
- Company firmographics:
  * Revenue range: [e.g., "$50M–$1B"] — required for firmographic targeting
  * Employee range: [e.g., "200–2,000"]
  * Industries (SIC/NAICS codes help with programmatic): [List 3-5 priority verticals]
  * Geographies: [Countries/states/metros]
  * Technographic signals: [Key tech stack indicators — e.g., "Uses SAP, Oracle, or Coupa"]
  * Negative ICP for exclusions: [Who to explicitly exclude — e.g., "Staffing agencies, government, non-profits"]

Named Target Account List:
- Total account list size: [Number of named accounts]
- Tier 1 accounts: [Number — highest ACV potential, most personalized treatment]
- Tier 2 accounts: [Number — segment-level personalization]
- Tier 3 accounts: [Number — broad ICP display targeting]
- CRM list ready for upload: [Yes/No — CSV with company name, domain, address]

---

SECTION 2: CURRENT STATE & INTENT DATA AUDIT

Current Display/Programmatic State:
- Active DSP(s): [Name or "None"]
- Monthly display budget: [Amount]
- Current retargeting status: [Pixel installed? Segments created? Burn pixel for converters?]
- Historical performance (if available):
  * Average CPM: [Amount — B2B display benchmark: $8–$25 for open exchange, $25–$65 for premium PMPs]
  * Average CTR: [% — B2B display benchmark: 0.05–0.15%; CTR is a weak signal for B2B]
  * View-through conversion rate: [% — primary B2B display signal]
  * Account penetration rate: [% of target accounts reached — goal: 70%+ of Tier 1/2]
  * Issues: [e.g., "Reaching wrong personas," "Low viewability," "No account-level reporting"]

Intent Data Assessment:
- Intent provider(s): [Bombora / 6sense / TechTarget Priority Engine / G2 Buyer Intent / Demandbase / None]
- Current intent signal activation: [How are you using it today?]
- Intent topic clusters relevant to your product: [List 5-10 Bombora/6sense topics your buyers research]
- Intent score threshold for "surging" accounts: [e.g., "6sense score 65+ = active buying cycle"]

Pixel & Audience Infrastructure:
- Universal pixel/tag deployed: [Yes/No — Google Tag Manager, Segment, mParticle?]
- Key retargeting segments needed:
  * High-intent visitors: [Pricing page, demo request page, ROI calculator — visited but didn't convert]
  * Product-aware visitors: [Case study, product pages, integration pages]
  * Early-stage visitors: [Blog readers, ungated content, homepage-only visitors]
  * Converted (suppress): [Existing customers, current MQLs in active sales cycle]
  * Competitive researchers: [Visited comparison pages or competitor-named URLs]

---

SECTION 3: DSP SELECTION FRAMEWORK

Evaluate and recommend the optimal DSP for this program based on:

A. BUDGET THRESHOLD GUIDANCE
- Under $5K/month: Managed service via StackAdapt, Basis Technologies, or programmatic ad network (avoid self-serve DSPs — minimum spend requirements and complexity don't justify the investment)
- $5K–$25K/month: StackAdapt self-serve (B2B-friendly, strong native + display, accessible UI) or The Trade Desk via agency partner
- $25K–$100K/month: The Trade Desk (premium supply access, strongest intent data integrations, Kokai AI bidding) or DV360 (best for companies already in Google ecosystem with DV360 Display & Video)
- $100K+/month: The Trade Desk or DV360 with dedicated account team; consider adding Xandr (AT&T premium inventory) for B2B-specific publisher access

B. SUPPLY CHANNEL ACTIVATION
For each budget tier, specify:

OPEN EXCHANGE (OX):
- Pros: Maximum reach, lowest CPM ($3–$15 for B2B), scale for retargeting large audiences
- Cons: Lower viewability (55–65% average), higher IVT risk, weaker brand safety without robust exclusions
- Use for: Early retargeting at scale, awareness to broad ICP, frequency building
- Required fraud protection: Enable pre-bid IVT filtering (IAS or DoubleVerify integration in DSP)

PRIVATE MARKETPLACE DEALS (PMPs):
- Pros: Premium inventory, higher viewability (70–85%), lower IVT, better brand safety, often audience-verified
- Cons: Higher CPM ($20–$60+), smaller scale, requires deal negotiation with publishers
- Priority B2B PMP categories: Business news (WSJ, Bloomberg, Forbes programmatic PMPs), trade publications (specific to your vertical), professional content networks (Dotdash Meredith business vertical)
- Use for: Tier 1 account targeting, brand positioning, competitive moments when you need premium placement

B2B AUDIENCE EXTENSION NETWORKS:
- Dun & Bradstreet + Bombora audience segments available directly in The Trade Desk: target by revenue, employee count, industry, job function
- LinkedIn Audience Network (LAN): Available via Campaign Manager — extend LinkedIn targeting to off-platform display inventory; lower quality than direct LinkedIn but leverages the same firmographic data
- G2 Buyer Intent activation: G2's programmatic offering targets active software buyers by category; particularly strong for SaaS
- TechTarget Priority Engine: Precision B2B tech audiences based on active content consumption behavior

C. DSP RECOMMENDATION OUTPUT
Produce:
- Primary DSP recommendation with 3-bullet rationale
- Recommended supply mix (OX %, PMP %, B2B network %) with budget breakdown
- Deal IDs or PMP packages to negotiate based on target vertical
- Any DSP-specific B2B features to activate (e.g., The Trade Desk's Kokai AI, StackAdapt's native ABM targeting)

---

SECTION 4: AUDIENCE ARCHITECTURE & TARGETING STRATEGY

Design a three-tier audience system:

TIER A — COLD ACCOUNT-BASED PROSPECTING

Goal: Reach decision-makers at named accounts who have never visited your website.

IP-Based Account Matching:
- Upload target account list as CSV (company name + domain + billing address) to DSP for IP targeting
- Expected match rate: 50–70% of accounts will be reachable via IP targeting
- Layering: Add job function/title data from Dun & Bradstreet or Bombora overlay to reach specific personas within matched accounts
- Minimum impressions per account per week (Tier 1): 20–40 impressions across buying committee members
- Frequency cap: 3–5 impressions/person/day, 15–25/person/week (B2B needs repetition — unlike B2C, don't cap too aggressively)

Firmographic Prospecting (for accounts not on named list):
- Industry: [SIC/NAICS codes or DSP-native industry segments]
- Revenue: [$50M+ filter — available in Dun & Bradstreet segments via TTD/StackAdapt]
- Employee count: [200+ filter]
- Job function: [Procurement / Finance / Operations / IT — depending on buying committee]
- Seniority: [Director / VP / C-Suite]
- Geography: [State/DMA/country targeting]
- Estimated audience size after all filters: [Specify range — aim for 500K–5M people for cold prospecting]

TIER B — INTENT DATA ACTIVATION

Goal: Surge budget toward accounts actively researching your category.

Bombora Intent Activation (via The Trade Desk or HubSpot native):
- Intent topics to track (select 8–12 from Bombora taxonomy):
  * [Topic 1 — e.g., "Procurement Software"]
  * [Topic 2 — e.g., "Supply Chain Management"]
  * [Topic 3 — e.g., "ERP Integration"]
  * [Topic 4 — e.g., "Vendor Management"]
  * [Topic 5 — competitor name topics if available]
- Surge threshold: Accounts with Bombora surge score 60+ = "in-market" — prioritize with 2x bid multiplier
- Budget allocation: Shift 30–50% of prospecting budget toward intent-surging accounts
- Refresh cycle: Bombora scores update weekly — refresh audience segments every 7 days

6sense Intent Activation (if using 6sense):
- 6sense intent stage mapping to display bidding:
  * Awareness stage (score 40–60): Standard bid, awareness creative
  * Consideration stage (score 60–75): 1.5x bid multiplier, solution-focused creative
  * Decision stage (score 75+): 2x bid multiplier, demo/comparison creative, ABM 1:1 personalization
- 6sense segments push directly to The Trade Desk via native integration — no CSV required

G2 Buyer Intent (if applicable):
- Activate "actively researching [your category]" segment in G2 Buyer Intent console
- Push to DSP via G2's programmatic activation or export list for upload
- Strong signal: These are buyers actively reading reviews for your category right now

TIER C — RETARGETING & ACCOUNT ENGAGEMENT SEQUENCES

Design pixel-based retargeting sequences by audience segment:

HIGH-INTENT VISITORS (Pricing / Demo / ROI Calculator pages — did not convert):
- Segment: All visitors to /pricing, /demo, /request-a-demo, /roi-calculator in last 30 days
- Creative message: Remove friction — "No long demo required — get a 15-min focused walkthrough" or "See how [Company] handles [specific use case]"
- Frequency: 5–8 impressions/person/day for first 7 days, then step down to 2–3/day for days 8–30
- Bid: 3–5x standard CPM (this is your hottest audience)
- Duration: 30 days
- Conversion goal: Demo request click-through OR view-through conversion within 30 days

PRODUCT-AWARE VISITORS (Case studies, product pages, integration pages — last 60 days):
- Segment: Visitors to /case-studies, /product, /integrations, /customers — NOT pricing/demo
- Creative message: Social proof and use case specificity — "How [Customer] achieved [specific outcome]" / "See [Product Feature] in action"
- Frequency: 3–5 impressions/person/day
- Bid: 2–3x standard CPM
- Duration: 60 days
- Conversion goal: Move to high-intent segment (visits pricing/demo page)

EARLY-STAGE VISITORS (Blog, homepage, ungated content — last 90 days):
- Segment: Visitors to blog posts, homepage, resource pages who did NOT visit product/pricing
- Creative message: Category education and thought leadership — "The 2026 State of [Category] Report" / "Why [Pain Point] is costing manufacturers $X annually"
- Frequency: 2–3 impressions/person/day
- Bid: Standard CPM
- Duration: 90 days
- Conversion goal: Content download or product page visit (move up funnel)

COMPETITIVE RESEARCHERS (Visited competitor-comparison pages):
- Segment: Visitors to /vs-[competitor], /alternatives, /compare — last 30 days
- Creative message: Direct head-to-head positioning — "[Your Company] vs. [Competitor]: Here's what CFOs say after switching" / "Why 300 [ICP] teams chose [Your Company] over [Competitor]"
- Frequency: 5–7 impressions/person/day
- Bid: 3–4x standard CPM (high-intent buyer evaluating alternatives)
- Duration: 30 days

BURNOUT / SUPPRESSION SEGMENTS (Always exclude):
- Existing customers (domain list from CRM)
- Current MQLs/SQLs in active sales cycle (contact list from CRM — suppress to avoid confusion with sales outreach)
- Recent form completers (30-day post-conversion window)
- Employees of your own company

---

SECTION 5: CREATIVE STRATEGY & SPECIFICATIONS

A. REQUIRED AD SIZES (IAB Standard)
Always produce all 5 standard sizes — DSPs require variety to serve across publisher inventory:
- 300x250 (Medium Rectangle): Highest volume placement; 40–50% of all display impressions
- 728x90 (Leaderboard): Desktop-heavy, above-fold placement; 20–25% of impressions
- 160x600 (Wide Skyscraper): Sidebar placement; 10–15% of impressions
- 300x600 (Half Page): Premium placement, highest viewability; 10–15% of impressions
- 320x50 (Mobile Banner): Mobile-only; 15–20% of impressions for mobile-heavy audiences

B. FORMAT DECISION FRAMEWORK
- Static PNG/JPG: Fastest production, lowest cost, works everywhere; use for retargeting and high-frequency campaigns
- HTML5 Animated (3–15 second loop): Higher CTR (+30–50% vs. static), allows message progression; use for cold prospecting and awareness
- Dynamic Creative Optimization (DCO): Personalize headline, offer, or logo based on audience segment, account name, or intent score; requires DCO template setup in DSP (available in TTD, DV360, StackAdapt); best ROI at scale when running 5+ audience segments

C. MESSAGE FRAMEWORK BY FUNNEL STAGE

AWARENESS (Cold prospecting, intent-surging accounts not yet on-site):
- Message: Category problem + thought leadership
- Formula: "[Shocking statistic about category pain] — [Company] solves it differently"
- Example: "67% of procurement teams still rely on spreadsheets for supplier risk. [Company] changes that."
- CTA: "See How" / "Learn More" / "Read the Report"
- Avoid: Product features, pricing, competitor names at this stage

CONSIDERATION (Product-aware visitors, account list with some prior touchpoints):
- Message: Use case specificity + social proof
- Formula: "How [Customer like them] achieved [specific outcome] with [Company]"
- Example: "How [Manufacturer Name] cut procurement cycle time by 40% in 90 days"
- CTA: "Read the Case Study" / "Watch 2-min Demo" / "Get the Playbook"

CONVERSION (High-intent visitors, intent score 75+, competitors evaluation):
- Message: Remove the last barrier to conversion
- Formula: "[Specific low-friction CTA] + [Risk reversal or social proof]"
- Example: "See [Company] in 15 minutes — no sales pitch, just your use case"
- CTA: "Book 15-min Walkthrough" / "Start Free" / "Get Your Custom ROI Report"

D. BRAND SAFETY CONFIGURATION

Mandatory exclusion categories (IAB Content Taxonomy):
- Adult content (IAB25)
- Fake news / misinformation (IAB1)
- Hate speech (IAB26)
- Violence (IAB13)
- Piracy (IAB7)
- User-generated content platforms (high IVT risk)

Contextual safety parameters:
- Minimum viewability threshold: 70% (IAB recommendation for B2B display)
- Minimum 50% of pixels in view for minimum 1 second (display), 2 seconds (video)
- IVT filter: Enable pre-bid fraud filtering via IAS, DoubleVerify, or MOAT integration within DSP
- Domain blocklist: Request your DSP or agency's standard B2B brand safety blocklist (typically 500K+ blocked domains for IVT and unsafe content)

Viewability measurement:
- Deploy DoubleVerify or IAS tag alongside your DSP trafficking tags
- Weekly viewability report: Flag any placements below 50% viewability for exclusion
- Benchmark: Good B2B display programs achieve 65–75% viewability on open exchange, 80–90% on PMPs

---

SECTION 6: ATTRIBUTION & MEASUREMENT FRAMEWORK

A. UTM TAXONOMY FOR DISPLAY
Every click from display must carry UTM parameters for CRM attribution:
- utm_source=programmatic
- utm_medium=display
- utm_campaign=[audience-tier]-[segment-name]-[quarter] (e.g., "tier1-abm-highintent-q2-2026")
- utm_content=[creative-size]-[variant] (e.g., "300x250-v2-awareness")
- utm_term=[intent-topic-or-audience] (e.g., "bombora-procurement-surge")

B. VIEW-THROUGH ATTRIBUTION (VTA) — CRITICAL FOR B2B DISPLAY

VTA credits a conversion when a user sees your ad (but doesn't click) and converts within a defined window. This is the primary measurement mechanism for B2B display — most buyers see display ads but convert through direct/organic/email channels later.

Recommended VTA windows by buying cycle:
- 30-day sales cycle (SMB): 7-day VTA window
- 60–90 day sales cycle (mid-market): 14-day VTA window
- 90–180 day sales cycle (enterprise): 30-day VTA window

CRM Integration for View-Through:
- Enable impression pixels in DSP and fire on-site for logged-in users or IP-matched accounts
- Push impression data to CRM via Bombora or 6sense account engagement sync
- Tag accounts that received 10+ display impressions within 30 days in Salesforce/HubSpot as "Display Reached" — track if pipeline velocity is higher for reached vs. non-reached accounts

Account-Level Attribution (the B2B Display Gold Standard):
- Goal: Measure what % of Tier 1/2 target accounts were reached with 10+ impressions
- Goal: Track if accounts receiving display had faster progression through opportunity stages
- Method: Match DSP impression logs (account domain/IP) to CRM account list monthly
- Report: "Display-influenced pipeline" — total open + closed pipeline from accounts reached by display in the prior 90 days

C. WEEKLY KPI DASHBOARD

| Metric | Benchmark | Alert Threshold |
|---|---|---|
| CPM (Open Exchange) | $8–$20 | >$30 = audience too narrow |
| CPM (PMP) | $25–$60 | >$80 = renegotiate deal |
| Viewability Rate | 65–75% | <55% = add viewability filter |
| IVT Rate | <5% | >8% = audit placements |
| CTR | 0.05–0.15% | <0.03% = creative fatigue |
| View-Through Conversion Rate | 0.5–2.0% | <0.3% = offer or landing page issue |
| Account Penetration (Tier 1) | 70%+ reached/month | <50% = increase bid or broaden list |
| Cost-Per-View-Through Conversion | 3–8x ACV | >15x ACV = restructure program |
| Display-Influenced Pipeline (Monthly) | Track trend | No growth after 90 days = strategy review |

---

SECTION 7: OPTIMIZATION PLAYBOOK

A. FREQUENCY MANAGEMENT
B2B display is uniquely frequency-sensitive: too little and you're forgotten in a 90-day cycle; too much and you burn brand equity.

Recommended frequency caps by audience tier:
- Cold prospecting (Tier 3): 2–3 impressions/person/day, 10–15/person/week
- Intent-surging accounts (Tier B): 3–5 impressions/person/day, 20–30/person/week
- High-intent retargeting (Tier C, pricing/demo visitors): 5–8 impressions/person/day, 30–40/person/week (first 7 days), then step down to 2–3/day
- Tier 1 ABM accounts: No strict frequency cap — fill impression budget per account; prioritize reach across all buying committee members

Fatigue signals to monitor:
- CTR drops >30% week-over-week for the same creative unit
- Engagement rate (post-click time on site) drops >20%
- Same audiences are consistently not completing the defined conversion path after 30 days

Creative refresh triggers:
- Awareness: Refresh every 30 days
- Consideration: Refresh every 45 days
- Retargeting: Refresh every 14–21 days (high frequency = faster fatigue)

B. BIDDING STRATEGY BY AUDIENCE
- Cold prospecting (open exchange): Start at CPM goal based on budget; use Kokai AI (TTD) or automated bidding to optimize toward view-through conversions after 2–3 weeks of data
- Intent-surging accounts: Bid 1.5–2x standard CPM floor — the incremental cost is justified by the signal quality
- High-intent retargeting: Bid 3–5x standard CPM floor — these visitors are the most likely to convert; fight for premium placement
- ABM Tier 1 (named account PMP): Negotiate fixed CPM deal with publisher for guaranteed delivery to named accounts; avoid auction for top accounts

C. SCALING & AUDIENCE EXPANSION SEQUENCE
1. Core: Named account list (IP-matched) + high-intent retargeting
2. Expand: Add Bombora/6sense intent-surging accounts outside named list
3. Expand: Firmographic prospecting (revenue + industry + job function) via D&B or DSP segments
4. Expand: LinkedIn Audience Network extension (same ICP targeting, off-LinkedIn inventory)
5. Expand: Lookalike audiences based on your best customer company list (available in TTD Kokai, StackAdapt)
6. Validate: Run account penetration lift study after 90 days — are you reaching more target accounts than control?

## Example Input/Output

**Input Example:**

Company: Fieldmotion — AI-powered field service management software for HVAC and plumbing contractors with 20–500 technicians.

ICP: COO/VP Operations, CFO, Owner at HVAC/plumbing service companies with 25–500 technicians, $5M–$75M revenue, US-based.

Monthly display budget: $12,000. Goal: Reach 80% of 450 target accounts with consistent display presence, generate 15 demo requests/month from display-influenced pipeline, cut cost-per-opportunity to under $2,500.

Intent data: Bombora via HubSpot (topics: "Field Service Management Software," "Technician Scheduling," "Mobile Workforce Management," "Service Revenue Optimization").

DSP: No current DSP. Open to StackAdapt (agency managed, $10K/month threshold).

CRM: HubSpot + Salesforce. Retargeting pixel deployed via Google Tag Manager on all pages.

---

**Output Example (Partial):**

**DSP RECOMMENDATION:** StackAdapt (managed service) at $12K/month. Rationale: (1) B2B-friendly native + display inventory with strong SMB/trades audience reach via business content; (2) Under $25K/month threshold makes self-serve TTD operationally complex — StackAdapt's managed model provides hands-on optimization; (3) Built-in Bombora intent data integration activates your existing subscription without additional data fees.

**AUDIENCE ARCHITECTURE:**

| Audience | Source | Estimated Size | Monthly Budget | CPM Target |
|---|---|---|---|---|
| Tier 1 ABM — Named 450 accounts (IP match) | CRM export → StackAdapt upload | ~90,000 buying committee members | $4,800 (40%) | $18–$28 (PMP deal for trades publishers) |
| Bombora Intent-Surging — "Field Service Mgmt" surge score 60+ | Bombora via StackAdapt integration | ~12,000 accounts/week refreshed | $3,000 (25%) | $14–$20 |
| High-Intent Retargeting — Pricing/Demo page visitors (last 30 days) | Pixel segment | ~1,200–2,000 people/month | $2,400 (20%) | $35–$50 (premium retargeting CPM) |
| Product-Aware Retargeting — Case study/product page visitors (last 60 days) | Pixel segment | ~4,000–6,000 people | $1,800 (15%) | $18–$25 |

**ACCOUNT PENETRATION PROJECTION:** At $4,800/month on the 450-account IP-matched list targeting ~90K total buying committee members, expect 75–85% of accounts reached with 10+ impressions/month. At $18 CPM, that's 266,000 impressions/month distributed across the list — or ~590 impressions/account/month across 3–5 committee members.

**CREATIVE RECOMMENDATION FOR HIGH-INTENT RETARGETING:**
- 300x250 static: "You looked at Fieldmotion. Here's what 200 HVAC companies saw first: [Customer photo + 40% fewer missed appointments]" — CTA: "Watch 3-min demo"
- 728x90: "Still evaluating field service software? 15 minutes shows you exactly what you need." — CTA: "Book now"
- HTML5 300x600 (animated, 3-frame): Frame 1 — "Fieldmotion: Built for HVAC & Plumbing" → Frame 2 — "[Customer]: Grew revenue 28% in year 1" → Frame 3 — "See it in 15 minutes"

**PROJECTED PIPELINE IMPACT:** At $12K/month with this architecture, expect: 70–85% Tier 1 account reach within 60 days; 8–15 view-through demo conversions/month; $25–35 display-influenced CPL (view-through). Display-influenced pipeline after 90 days: $1.5–$2.5M based on $45K ACV and estimated 5–8% lead-to-opp rate for display-influenced leads.

## Success Metrics

- **Account penetration rate:** 70%+ of Tier 1/Tier 2 named accounts reached with 10+ impressions/month within 60 days of launch; below 50% indicates IP matching is failing or budget is insufficient for list size
- **Viewability rate:** 65–75% on open exchange, 80%+ on PMPs; below 55% triggers immediate placement audit and domain blocklist expansion
- **View-through conversion rate:** 0.5–2.0% of impressions resulting in conversion within VTA window; below 0.3% after 60 days signals landing page friction or offer mismatch
- **Display-influenced pipeline velocity:** Accounts that received 10+ display impressions should show 15–25% faster stage progression than matched control accounts; measure at 90-day intervals
- **Cost-per-display-influenced opportunity:** Should be 3–8x target ACV; calculate as total display spend ÷ opportunities created by display-influenced accounts (multi-touch attribution window)
- **IVT rate:** Keep below 5%; above 8% requires immediate review of domain targeting and IVT pre-bid filter configuration
- **Creative fatigue signal:** CTR should hold within 20% of baseline for first 21 days; if it drops more than 30% week-over-week, rotate to new creative variant before performance degrades further

## Related Prompts

- [AI-Powered B2B Performance Marketing & Paid Demand Generation Intelligence Engine](./AI-Powered-B2B-Performance-Marketing-&-Paid-Demand-Generation-Intelligence-Engine.md)
- [AI-Powered LinkedIn Ads B2B Pipeline & Account-Based Advertising Intelligence Engine](./AI-Powered-LinkedIn-Ads-B2B-Pipeline-&-Account-Based-Advertising-Intelligence-Engine.md)
- [ABM Campaign Orchestration & Account Intelligence Engine](../Account-Based-Marketing/ABM-Campaign-Orchestration-&-Account-Intelligence-Engine.md)
- [AI-Powered ABM Target Account List Building & ICP Scoring Intelligence Engine](../Account-Based-Marketing/AI-Powered-ABM-Target-Account-List-Building-&-ICP-Scoring-Intelligence-Engine.md)

## Integration Tips

- **The Trade Desk:** Connect Bombora intent data natively via TTD's Data Marketplace; sync Salesforce account lists via TTD's UID2.0 identity framework for cookieless targeting; use Kokai AI bidding with view-through conversion goal after 4+ weeks of data (minimum 50 view-through conversions required to optimize)
- **Salesforce:** Create custom "Display Reached" checkbox field on Account object; populate via weekly import of DSP impression logs matched to account domain; build a pipeline report filtered by "Display Reached = True" to measure display-influenced revenue at QBR
- **HubSpot:** Use HubSpot's Bombora intent integration to automatically add accounts to "Programmatic Display Boost" list when surge score exceeds threshold; push this list to StackAdapt or TTD via API or CSV export on weekly schedule; this creates a closed-loop where CRM intent triggers display budget reallocation automatically
- **6sense:** Use 6sense's native DSP integrations (TTD, DV360, StackAdapt) to push account audiences directly without CSV exports; configure 6sense to automatically shift display impressions toward accounts in "Decision" stage; 6sense's Revenue AI can trigger Salesforce tasks for SDRs when display-reach + intent score combination crosses threshold
- **Zapier / Make:** Automate the weekly workflow: DSP performance report (CSV export) → Zapier parses CPM/viewability/CTR by campaign → updates Google Sheet dashboard → Slack notification to demand gen team with accounts that crossed 50-impression threshold this week
- **Google Looker Studio:** Connect DSP CSV exports, Salesforce pipeline data, and GA4 view-through data into unified programmatic performance dashboard; display alongside LinkedIn and Google Ads data for true cross-channel view; share with CMO as live link updated weekly

## Troubleshooting

**Problem: Account penetration rate is below 40% — most target accounts not being reached**
Solution: IP targeting match rate is failing. Diagnose by checking: (1) Is your account list formatted correctly? DSPs require company name + domain + physical billing address for best IP matching; PO boxes and virtual offices have low match rates. (2) Are many of your accounts small businesses (under 50 employees) where employees work from home? IP-based targeting works poorly for distributed workforces — supplement with LinkedIn Audience Network (LAN) which uses LinkedIn profile data, not IP address. (3) Is your account list stale? Companies change offices; refresh your address data against Dun & Bradstreet or ZoomInfo quarterly. Consider supplementing IP matching with domain-matched programmatic (available in StackAdapt and some PMPs) where you target users whose email domain matches your account list.

**Problem: View-through attribution shows high conversions but no lift in actual pipeline or closed revenue**
Solution: Your VTA window is too long or your attribution is capturing organic/direct conversions as "display-influenced." Fix in three steps: (1) Shorten VTA window — if you're running 30-day VTA, test 14-day; if 14-day, test 7-day. (2) Run an A/B holdout test: suppress display ads to 20% of your target account list for 60 days and compare conversion rates between exposed vs. unexposed cohorts. The true incrementality of display is measured by this lift test, not last-touch or view-through rate. (3) Add quality filter: only count view-through conversions where the account also appears in your named account list AND had at least 10 impressions — this filters out accidental view-through matches to non-ICP visitors.

**Problem: CPMs are skyrocketing ($50+ on open exchange) with small reach**
Solution: Audience targeting is over-constrained. B2B display audiences naturally shrink when you layer multiple targeting dimensions. Diagnose by removing one dimension at a time: first remove skills/technographic overlay, then relax job title to job function + seniority, then expand company size range. In programmatic, the sweet spot for B2B cold prospecting is 500K–3M people — below 200K you face severe delivery issues and CPM inflation. Also check: are you running IP-matched account targeting AND firmographic targeting in the same campaign? Separate these into distinct line items so the algorithm can optimize delivery independently for each method.

## Version History
- v1.0: Initial creation (auto-generated)
