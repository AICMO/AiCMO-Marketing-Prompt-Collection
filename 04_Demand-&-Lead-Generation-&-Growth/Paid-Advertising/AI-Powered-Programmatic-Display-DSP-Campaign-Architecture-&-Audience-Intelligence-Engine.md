# AI-Powered Programmatic Display & DSP Campaign Architecture & Audience Intelligence Engine - Complete Programmatic Media System for Full-Funnel Demand Generation

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** programmatic, display, dsp, trade-desk, dv360, paid-media, demand-generation, retargeting, audience-intelligence

## Overview
Architect, launch, and continuously optimize programmatic display campaigns across DSPs — including The Trade Desk, Google DV360, Amazon DSP, and Adobe Advertising Cloud — that generate measurable pipeline at efficient CPCs and CPLs. Use this engine when you need to scale beyond search and social into programmatic inventory, leverage first-party data and intent signals for precise audience targeting, and build always-on display programs connected to revenue attribution.

## Quick Copy-Paste Version

You are a senior programmatic media strategist with deep DSP expertise across The Trade Desk, Google DV360, and Amazon DSP. Build a complete programmatic display campaign architecture for the following:

Company: [Your Company]
Product/Service: [What you sell]
Target buyer: [Job title, industry, company size]
Monthly programmatic budget: $[Amount]
Primary goal: [Pipeline / MQL / Brand awareness / Retargeting]
DSP platform(s): [The Trade Desk / DV360 / Amazon DSP / Multiple]
CRM/CDP: [HubSpot / Salesforce + any CDP]
First-party data available: [CRM lists / pixel audiences / none]

Deliver:

1. CAMPAIGN STRUCTURE (full-funnel programmatic architecture)
   - Prospecting campaigns: audience strategy, inventory type, CPM targets
   - Retargeting campaigns: segments, bid multipliers, frequency caps
   - Account-based display: TAL targeting, custom deal IDs, site lists

2. AUDIENCE STRATEGY
   - First-party audience segments (pixel-based and CRM-matched)
   - Third-party data segments to layer (by category and provider)
   - Intent data activation (Bombora, G2, TechTarget integration)
   - Lookalike and contextual targeting approach

3. INVENTORY STRATEGY
   - Open exchange vs. private marketplace (PMP) vs. programmatic guaranteed
   - Recommended deal IDs to pursue for your vertical
   - Publisher allowlist and brand safety configuration
   - Viewability and fraud protection thresholds

4. CREATIVE & FORMAT STRATEGY
   - Display formats with performance rationale (728×90, 300×250, 300×600, native)
   - Dynamic creative optimization (DCO) approach by audience segment
   - Creative rotation logic and refresh cadence

5. BIDDING & BUDGET ALLOCATION
   - Bid strategy per campaign objective
   - Budget split: prospecting vs. retargeting vs. ABM
   - Pacing and dayparting settings

6. MEASUREMENT & ATTRIBUTION
   - View-through vs. click-through conversion windows
   - Cross-channel attribution model
   - Incrementality testing approach

7. 30-DAY LAUNCH PLAN
   - Pixel deployment and audience build phase
   - Campaign launch sequence
   - Optimization milestones

Output a structured programmatic brief executable by an in-house team or agency immediately.

## Advanced Customizable Version

ROLE: You are a programmatic media architect and demand generation strategist with 12+ years experience building $100K–$2M/month programmatic programs for B2B SaaS, enterprise technology, and D2C brands. You operate across The Trade Desk, Google DV360, Amazon DSP, and Adobe Advertising Cloud, combining DSP capabilities with CRM data, intent signals, first-party audiences, and revenue attribution to build self-optimizing programmatic demand programs.

COMPANY CONTEXT:
- Company: [COMPANY_NAME]
- Industry/Category: [INDUSTRY]
- Product type: [B2B SaaS / Enterprise / D2C / E-Commerce]
- ACV or AOV: $[VALUE]
- Sales cycle: [Self-serve / 30 / 60 / 90 / 180+ days]
- Monthly programmatic display budget: $[BUDGET]
- Primary DSP(s): [The Trade Desk / DV360 / Amazon DSP / Adobe / Multi-DSP]
- CRM: [HubSpot / Salesforce / Other]
- CDP available: [Segment / mParticle / Lytics / None]

TARGET AUDIENCE PROFILE:
PERSONA 1 (Primary):
- Job titles: [VP of X, Director of X, Head of X]
- Seniority: [Director / VP / C-Suite / Manager]
- Industries: [List top 3-5]
- Company size: [Employees or ARR range]
- Digital behavior signals: [Content they consume, sites they visit, topics they research]
- Purchase intent topics (Bombora): [List relevant B2B topics if known]

PERSONA 2 (Secondary, if applicable):
- Job titles: [Role titles]
- Seniority: [Level]
- Role in buying process: [Influencer / Evaluator / End user]

ICP ACCOUNT PARAMETERS:
- Target account list available: [Yes (size: X accounts) / No]
- CRM suppression list available: [Yes / No]
- Pixel deployed on website: [Yes — pages covered / No — need deployment]
- CRM-to-DSP audience sync available: [Yes (via LiveRamp / TradeDesk ID / DV360 Customer Match) / No]
- Intent data subscriptions: [Bombora / G2 / TechTarget / 6sense / None]
- First-party data quality: [Clean CRM list of X contacts / Pixel audiences of X visitors / None]

COMPETITIVE & MARKET CONTEXT:
- Main competitors: [Competitor 1, Competitor 2, Competitor 3]
- Key differentiators: [Differentiator 1, 2, 3]
- Brand awareness level: [Unknown / Some awareness / Strong brand]
- Current paid display performance (if running): [CTR, viewability rate, VCR, CPL if known]

---

DELIVERABLE 1: FULL-FUNNEL PROGRAMMATIC CAMPAIGN ARCHITECTURE

Design a 4-layer programmatic campaign structure:

LAYER 1 — PROSPECTING (Net-New Audience Acquisition)
Objective: Reach high-fit prospects who haven't engaged with your brand
Inventory strategy:
  - Primary: Private Marketplace (PMP) deals with premium B2B publishers
  - Secondary: Open exchange with strict brand safety and viewability filters
  - Recommended PMP categories for B2B: [Business/Finance, Technology, Industry verticals]
  - Minimum viewability threshold: 70% (IAB standard)
  - Fraud filter: IAS or DoubleVerify integration, minimum 95% authentic impressions

Audience strategy:
  a) Third-party B2B data segments (via DSP data marketplace):
     - Oracle Data Cloud / Lotame: Job function + seniority + company size
     - Bombora Intent Surge: Companies surging on [Product Category] topics (top 20%)
     - B2B technographic: Companies using [Competitor tech] or adjacent solutions
     - Industry/vertical segments: [Your top 3 SIC/NAICS codes]
  b) Contextual targeting:
     - Keyword contextual: [10-20 high-intent B2B keywords relevant to your category]
     - Category contextual: Business technology, software, cloud computing, [your vertical]
     - Competitor content: pages discussing [Competitor names] (brand displacement)
  c) Lookalike modeling:
     - Seed: Upload CRM customer list (best 500-1,000 customers) → DSP lookalike model
     - TTD: Predictive targeting from UID2 matched seed
     - DV360: Similar audiences from Google's modeled signals

Budget allocation: [25-35% of total programmatic budget]
KPIs: CPM ($8-18 for B2B premium inventory), CTR (0.08-0.15% for display), reach, frequency
Frequency cap: 10-15 impressions per unique per month (adjust by deal type)
Formats: 300×250 (highest volume), 728×90, 160×600, 300×600, native ad units

LAYER 2 — INTENT-BASED ABM DISPLAY (Account-Based Targeting)
Objective: Surround target accounts with coordinated display as part of ABM orchestration
Audience: Target account list (upload CRM TAL as company-level match)
Matching method:
  - The Trade Desk: Company IP targeting + UID2 email match
  - DV360: Customer Match + Company targeting via account-based data providers
  - Account-level data providers: Bombora Company Surge, DemandBase, 6sense segments

PMP deal strategy for ABM:
  - Source 3-5 direct programmatic deals with B2B publisher networks your ICP reads
  - Publishers to pursue: [Industry trades, business media (Bloomberg, WSJ Business), LinkedIn Audience Network via PMP, TechTarget network, IDG/Foundry network]
  - Negotiate: Floor CPMs for high-quality guaranteed inventory within your TAL

Geo-frequency strategy:
  - Tier 1 accounts (top 50): 20-30 impressions/account/month, premium PMP only
  - Tier 2 accounts (next 200): 10-15 impressions/account/month, PMP + open exchange
  - Tier 3 accounts (next 500+): 5-8 impressions/account/month, open exchange with intent filter

Dynamic creative for ABM:
  - Industry-specific creative variants (one per top 3 verticals in TAL)
  - Company name insertion if display platform supports dynamic DCO
  - Message sequencing: Awareness → Problem → Solution → Proof → CTA over 4-week window

Budget allocation: [20-30% of total programmatic budget]
KPIs: Account reach rate (% of TAL accounts exposed), account engagement lift, site visit rate from TAL accounts, pipeline influence from TAL accounts

LAYER 3 — RETARGETING (Re-engagement & Conversion Acceleration)
Objective: Convert high-intent site visitors and CRM prospects who haven't converted
Retargeting segments (build in DSP via pixel or CRM audience sync):

SEGMENT 1 — High-Intent Pages (bid 3× base):
  - Visited: pricing page, demo page, comparison pages, contact page
  - Window: Last 14 days
  - Frequency cap: 20 impressions/person/month
  - Message: Direct conversion — demo offer, free trial, specific ROI claim

SEGMENT 2 — Product/Solution Pages (bid 2× base):
  - Visited: product pages, features pages, use case pages
  - Window: Last 30 days (exclude Segment 1)
  - Frequency cap: 15 impressions/person/month
  - Message: Proof point + comparison — customer case study, competitive comparison

SEGMENT 3 — Content Engagers (bid 1.5× base):
  - Visited: blog posts, resources, webinar pages (3+ pages or 2+ min on site)
  - Window: Last 45 days (exclude Segments 1-2)
  - Frequency cap: 10 impressions/person/month
  - Message: Lead magnet — relevant content upgrade, benchmark report, assessment

SEGMENT 4 — CRM Prospects (bid 2× base, suppress from all other segments):
  - CRM contacts at MQL or opportunity stage (upload via LiveRamp or DSP Customer Match)
  - Window: Evergreen, refresh weekly
  - Frequency cap: 15 impressions/person/month
  - Message: Late-stage acceleration — customer story matching their profile, ROI calculator

SUPPRESSION AUDIENCES (exclude from all campaigns):
  - Current customers (upload customer email list)
  - Recent converters (demo request or trial signup in last 30 days)
  - Internal employees

Budget allocation: [30-40% of total programmatic budget]
KPIs: View-through conversion rate, click-through conversion rate, retargeting CPL, pipeline from retargeting

LAYER 4 — SEQUENTIAL STORYTELLING (Message Orchestration)
Objective: Move prospects through a coordinated narrative over 30-60 days
Sequence structure (trigger-based message rotation within DSP):

Exposure 1-3 (Days 1-7): Problem Awareness
  - Message: Industry trend, pain point quantification, "Did you know..." stat
  - Format: 300×600 or native for longer dwell time
  - Goal: Establish brand presence and problem framing

Exposure 4-7 (Days 8-18): Solution Introduction
  - Message: Category education, your approach vs. status quo
  - Format: 300×250 or 728×90
  - Goal: Position your solution category

Exposure 8-12 (Days 19-30): Proof & Differentiation
  - Message: Customer outcome stat, named case study, third-party validation
  - Format: Native or 300×600 with prominent logo and data point
  - Goal: Build credibility and preference

Exposure 13+ (Days 31+): Direct Conversion
  - Message: Specific CTA — demo, trial, report download
  - Format: All formats with urgency signal if applicable
  - Goal: Convert to known lead

Sequence logic: Advance to next message group after user sees N impressions from current group. Requires frequency capping and creative sequencing by segment ID in DSP.
Platform support: The Trade Desk (native sequencing), DV360 (Floodlight-based sequencing), Amazon DSP (lifecycle audiences).

---

DELIVERABLE 2: AUDIENCE DATA STRATEGY & FIRST-PARTY DATA ACTIVATION

FIRST-PARTY DATA ACTIVATION ROADMAP:

Pixel Deployment (if not already done):
  - Universal pixel on all pages (The Trade Desk Universal Pixel / DV360 Floodlight / Amazon Pixel)
  - Conversion events: Demo request, trial signup, content download, pricing page visit
  - Segment triggers: Visited /pricing (high intent), visited /[feature-page] (product interest)
  - CRM sync frequency: Weekly export → LiveRamp → DSP audience upload

Identity Resolution for B2B:
  - The Trade Desk UID2: Match CRM email list for people-based targeting at scale
  - DV360 Customer Match: Upload hashed email lists for Google identity graph matching
  - LiveRamp RampID: Universal identity spine connecting CRM, DSP, and publisher data
  - Expected match rates: 30-60% for B2B email lists (lower than B2C due to work email prevalence)

THIRD-PARTY DATA SELECTION FRAMEWORK:

Tier 1 — High-confidence B2B intent:
  - Bombora Company Surge Topics: [Your 5-10 most relevant B2B research topics]
    Examples for SaaS: "Cloud Software Evaluation", "Enterprise Software", [Your Category]
  - G2 Intent data (if subscribed): Companies researching your category or competitors on G2
  - TechTarget ABM: Companies downloading content about your category from TechTarget network

Tier 2 — Firmographic targeting:
  - Oracle Data Cloud B2B: Job function (select 3-5) + Seniority (Director+) + Company Revenue range
  - Dun & Bradstreet: Industry + company size + growth signal
  - Experian B2B: Business demographics overlay

Tier 3 — Behavioral/interest signals:
  - Contextual by keyword: custom keyword list of 20-30 category terms
  - Site retargeting from premium publishers: TechCrunch, Forbes, Bloomberg B2B sections
  - Trade publication audiences: [Industry-specific publishers in your vertical]

DATA SEGMENT TESTING FRAMEWORK:
- Launch with 3-4 audience hypotheses simultaneously, each with $500-1,000/month minimum
- Evaluate after 30 days: CTR, site engagement rate (pages per session), CPL
- Scale audiences with CTR > 0.10% AND site engagement above baseline
- Retire audiences with CTR < 0.05% or zero conversions after 1,000 clicks

---

DELIVERABLE 3: CREATIVE STRATEGY & DYNAMIC CREATIVE OPTIMIZATION (DCO)

CREATIVE ARCHITECTURE BY FUNNEL STAGE:

PROSPECTING CREATIVE BRIEF:
Objective: Interrupt and engage unknown ICP prospects
Hook approach: Data-driven insight, bold claim, or industry pain point
Key principle: Assume zero brand awareness — your logo means nothing; the message must work alone

Ad sizes to produce (in priority order):
  1. 300×600 Half-Page — highest viewability, most impactful for awareness
  2. 300×250 Medium Rectangle — highest volume inventory available
  3. 728×90 Leaderboard — desktop-heavy B2B audiences
  4. 320×50 Mobile Banner — mobile B2B consumption (growing)
  5. Native ad unit — least intrusive, often highest CTR for B2B

Creative variants per campaign (minimum 3 per format):
  Variant A — Stat-led: "[Specific number] % of [Persona] face [Pain]"
  Variant B — Outcome-led: "[Customer name] [achieved specific result] in [timeframe]"
  Variant C — Question-led: "Are you still [doing painful manual process]?"

Animation: Limit to 15-second loop max (IAB standard). Frame 1 must work as a static image (many publishers block animation above the fold). CTA must appear in final frame prominently.

RETARGETING CREATIVE BRIEF:
Objective: Convert a warm prospect who has already seen your brand
Key principle: Do not repeat the same awareness message — escalate specificity and proof
Segments → messages:
  - Pricing page visitors: Show specific pricing tier relevant to their company size, or "See what [similar company] pays"
  - Product page visitors: Show use-case-specific creative matching the page they visited (if DCO, pull dynamic content)
  - Case study readers: Show a second case study from a similar industry/use case
  - MQL-stage CRM contacts: Show sales social proof — "Join 500+ [personas] who use [Product]"

DCO IMPLEMENTATION:
If DCO platform available (Google Studio, Jivox, Flashtalking, Sizmek):
  - Dynamic variables: company name (from ABM segment), industry (from data segment), job function, page last visited
  - Feed structure: [product_name], [customer_logo], [customer_stat], [cta_text], [hero_image]
  - Rules engine: if industry == "Financial Services" → show fintech customer logo; if segment == "pricing_visitor" → show pricing-focused CTA

CREATIVE REFRESH CADENCE:
  - Prospecting: Refresh creative every 45 days or when CTR drops > 30% from baseline
  - Retargeting: Refresh every 30 days (higher frequency = faster fatigue)
  - Frequency signal: When average frequency exceeds 8/month per segment, creative fatigue is likely — introduce new variant

---

DELIVERABLE 4: PRIVATE MARKETPLACE (PMP) & DEAL STRATEGY

PMPs give you access to premium inventory that open exchange cannot reach, with better brand safety and viewability guarantees.

DEAL TYPES:
  - Preferred Deals (non-guaranteed): Fixed CPM, no guaranteed volume — best for testing premium publishers
  - Private Auctions: Invitation-only real-time bidding with select publishers
  - Programmatic Guaranteed: Fixed CPM + guaranteed impression volume — use for high-priority ABM campaigns

HOW TO SOURCE DEALS:
  1. Publisher direct outreach: Reach out to your top 10 B2B media publishers' programmatic sales teams
  2. DSP marketplace: The Trade Desk Deal Discovery, DV360 Marketplace — search by publisher + deal type
  3. SSP negotiations: Work with PubMatic, Magnite, Index Exchange for premium business content deals
  4. Vertical networks: TechTarget, IDG/Foundry, Questex, Penton — offer audience-guaranteed deal IDs at CPMs of $25-60 for tech B2B

DEAL ID TARGETING STRATEGY:
  Deal ID 1 — Premium B2B Discovery: Publisher network covering [Your top industry trades]
    - Floor CPM: $20-30 | Deal volume: 500K-2M impressions/month
    - Best for: Prospecting TOFU
  Deal ID 2 — High-Intent B2B Research Content: Publishers with known evaluation/comparison content
    - Floor CPM: $30-50 | Deal volume: 100K-500K impressions/month
    - Best for: MOFU and competitor displacement
  Deal ID 3 — ABM Guaranteed Reach: Publisher-guaranteed impressions to a whitelist of target domains/IPs
    - Floor CPM: $40-70 | Deal volume: Fixed per account commitment
    - Best for: ABM Layer (TAL accounts)

BRAND SAFETY CONFIGURATION:
  - IAS or DoubleVerify integration: required for any campaign $5K+/month
  - Minimum viewability: 70% (display), 50% (video)
  - Fraud protection: < 1% invalid traffic (IVT) tolerance
  - Brand safety categories to block: Adult content, piracy, hate speech, fake news, gambling (unless relevant)
  - Contextual blocking: Competitor brand names as negative keywords in contextual targeting
  - Publisher allowlist for ABM: Manually curate to 200-500 premium domains to guarantee quality

---

DELIVERABLE 5: BIDDING STRATEGY & BUDGET OPTIMIZATION

BID STRATEGY BY CAMPAIGN OBJECTIVE:

PROSPECTING:
  - Open exchange: Start with CPM fixed bid at $6-12 (B2B) or $8-18 (premium inventory)
  - PMP deals: Bid at floor CPM + 20% to win consistently; reduce to floor once you have deal volume data
  - Optimization goal: CTR first (0.08%+ target), then site engagement, then CPL
  - Auto-optimization: Enable DSP ML optimization after 500+ impressions collected; optimize toward site visit or conversion

RETARGETING:
  - Bid multipliers by segment:
    - Pricing page visitors (last 14 days): 3× base CPM
    - Product page visitors (last 30 days): 2× base CPM
    - Content engagers (last 45 days): 1.5× base CPM
    - CRM-matched prospects: 2× base CPM
  - Frequency control: Hard caps by segment (see Layer 3)
  - Suppression: Exclude converters within 24 hours of conversion event

ABM DISPLAY:
  - Bid at 2-3× prospecting CPM to ensure account reach and frequency delivery
  - If using programmatic guaranteed deals: bid at agreed floor, no dynamic bidding
  - Account reach priority over efficiency — accept higher CPM for guaranteed account coverage

BUDGET ALLOCATION MODEL (for $25,000/month example):
  - Prospecting (net-new audience): $7,500 (30%)
  - ABM display (TAL-targeted): $6,250 (25%)
  - High-intent retargeting: $6,250 (25%)
  - Content/blog retargeting: $3,750 (15%)
  - Testing reserve (new audiences, creative): $1,250 (5%)

Scale signal: When retargeting CPL is within target and retargeting audience is saturated (frequency maxed), reallocate 10-15% of retargeting budget to prospecting to feed top of funnel.

---

DELIVERABLE 6: MEASUREMENT, ATTRIBUTION & INCREMENTALITY

CONVERSION WINDOW SETTINGS:
  - Click-through conversion window: 7 days (standard display)
  - View-through conversion window: 1 day (to minimize false attribution claims)
  - Cross-device attribution: Enable if DSP supports it; use conservative (last-touch equivalent for view-through)

ATTRIBUTION MODEL RECOMMENDATIONS:
  - Do NOT use last-click for display — it will show zero credit (display is an influence channel, not a direct response channel)
  - Recommended: Multi-touch attribution (W-shaped or Data-Driven)
  - In HubSpot/Salesforce: Use Campaign Influence reporting with 90-day lookback window
  - Display attribution metric to report: "Pipeline Influenced" (opportunities where display touchpoint occurred before opportunity creation)

INCREMENTALITY TESTING (required for budgets > $15K/month):
  Method: Ghost bidding or holdout group test
  - Hold out 10-15% of target audience from display exposure (control group)
  - Compare conversion rates: exposed vs. holdout over 60-day window
  - Tools: The Trade Desk iSpot incrementality, DV360 Reach Planner holdout, third-party measurement partners (Nielsen, Analytic Partners)
  - Signal: If exposed group converts 20%+ more than holdout, display is incremental
  - Repeat quarterly to validate ongoing incrementality as programs mature

WEEKLY REPORTING FRAMEWORK:
  Metric Category | KPI | Target
  Delivery | Impressions served | On-pace to budget
  Engagement | CTR | > 0.08% (display), > 0.15% (native)
  Viewability | Viewable rate | > 70%
  Fraud | Invalid traffic rate | < 1%
  Site quality | Pages per session from display click | > 2.0
  Pipeline | Display-influenced pipeline $ | Track vs. benchmark
  Efficiency | Display-influenced CPL | < [2% of ACV for B2B]
  ABM | % of TAL accounts reached | > 70% of active TAL

---

DELIVERABLE 7: 30-DAY PROGRAMMATIC LAUNCH ROADMAP

WEEK 1 (Days 1-7): Infrastructure & Data Layer
  □ Day 1: Deploy universal DSP pixels on all pages (verify with pixel debugger tool)
  □ Day 2: Configure conversion events (demo request, trial, content download)
  □ Day 3: Upload CRM suppression lists (customers, disqualified leads) to DSP
  □ Day 4: Upload CRM prospect lists for retargeting audiences; initiate LiveRamp match
  □ Day 5: Source and activate 2-3 PMP deal IDs with B2B publishers
  □ Day 6: Configure brand safety controls (IAS/DV integration, category blocking, publisher allowlist)
  □ Day 7: QA all pixel events, conversion tracking, and audience sizes (retargeting segments need minimum 1,000 users before launching)

WEEK 2 (Days 8-14): Soft Launch
  □ Launch retargeting campaigns first (fastest path to conversion data — high-intent visitors already exist)
  □ Set conservative daily budgets (25% of planned daily) during calibration
  □ Launch prospecting campaign with 3 audience segments simultaneously (each $500 minimum for statistical validity)
  □ Verify creative is rendering correctly across formats and publishers (check ad serving report)
  □ Confirm conversion events firing correctly by submitting test lead

WEEK 3 (Days 15-21): Prospecting Ramp
  □ Evaluate audience segment performance: CTR, site engagement, early conversions
  □ Scale top-performing audience segment by 50% budget increase
  □ Pause any segment with CTR < 0.04% after 10,000 impressions
  □ Activate ABM display campaign using TAL upload
  □ Begin creative A/B analysis: identify winning variant by CTR

WEEK 4 (Days 22-30): Optimization & Scale
  □ Full budget is now deployed across all campaign layers
  □ Enable DSP algorithmic optimization (oCPM/oCPC) on retargeting — enough signal to train model
  □ Pull first pipeline influence report: opportunities created with display touchpoint in previous 30 days
  □ Present initial performance to stakeholders: impressions, CTR, viewability, site quality, influenced pipeline
  □ Set Month 2 optimization targets: CPL reduction goal, TAL reach rate target, audience expansion plan

Output the full programmatic architecture as a structured brief executable by an in-house programmatic team, media agency, or AI agent workflow.

## Example Input/Output

**Input Example:**
Company: Cohere (enterprise AI language model API for developers and enterprises)
Product: Secure, private large language model API for enterprise deployments
Target buyer: VP Engineering, Head of AI/ML, CTO at 500-5,000 employee enterprises in financial services, healthcare, and technology
ACV: $150,000
Monthly programmatic budget: $30,000
DSP: The Trade Desk (primary) + DV360 (secondary)
CRM: Salesforce
First-party data: 12,000 CRM contacts, pixel deployed on site (3,500 monthly visitors)
Intent data: Bombora subscription active

**Output Example (excerpt):**

---
**PROGRAMMATIC CAMPAIGN OVERVIEW — COHERE ENTERPRISE AI**

**Campaign Layer 1: Prospecting — AI/ML Infrastructure Audience**
- Budget: $9,000/month (30%)
- Audiences (in priority order):
  1. Bombora Surge — Topics: "Artificial Intelligence", "Machine Learning", "Large Language Models", "Enterprise AI", "Generative AI" — Companies with surge score 60+ in past 30 days
  2. Oracle Data Cloud — Job function: IT/Engineering + Data Science/Analytics, Seniority: Director+ at 500-5,000 employee companies in financial services, healthcare, tech
  3. Contextual — Keywords: "LLM deployment", "enterprise AI security", "private AI model", "on-premise AI", "HIPAA AI compliance"
  4. Lookalike — Seed: 800 best current customers (Fortune 2000 enterprises) → TTD lookalike at 3× seed size

- Inventory: 60% PMP (TechCrunch, VentureBeat, MIT Technology Review, ZDNet deal IDs) + 40% open exchange with IAS brand safety
- Format mix: 300×600 (40%), 300×250 (35%), native (25%)
- CPM target: $15-22 (open exchange), $28-40 (premium PMP)
- Frequency cap: 12 impressions/person/month
- Creative: "Your data never leaves your infrastructure. Cohere deploys in your VPC." — security-first message for enterprise IT buyers

**Campaign Layer 2: ABM Display — Top 250 Target Accounts**
- Budget: $6,000/month (20%)
- TAL: 250 accounts (Fortune 1000 in financial services + healthcare + technology)
- Targeting method: TTD Company IP targeting + UID2 email match from Salesforce
- Deal IDs: 3 programmatic guaranteed deals with Bloomberg Intelligence, Wall Street Journal Tech section, Fortune.com at $45 CPM floor
- Account reach target: 80% of 250 accounts exposed by end of Month 1
- Frequency: 15-20 impressions/account/month
- Creative: Financial services vertical — "How JPMorgan-style AI deployments achieve SOC2 compliance in 60 days"

**PROJECTED MONTH 3 PERFORMANCE:**
- Total impressions: 2.2M (prospecting) + 310K (ABM) + 450K (retargeting)
- Unique prospects reached: ~180,000
- TAL accounts reached: 210 of 250 (84%)
- Estimated pipeline influenced: $1.8M-$2.4M (based on 12-15 influenced opportunities at $150K ACV)
- Display-influenced CPL: $420 (total display spend / total pipeline-influenced leads)
- Display pipeline efficiency: 60:1 (display spend vs. influenced pipeline)

---

## Success Metrics

**Delivery Quality Metrics (track weekly):**
- Viewability rate: Target > 70% (IAB standard); > 75% for PMP inventory
- Invalid traffic rate: < 1% (verify via IAS/DV dashboard)
- CTR: Target > 0.08% display, > 0.15% native, > 0.40% retargeting
- Frequency compliance: No segment exceeding its frequency cap by > 20%

**Audience & Engagement Metrics (track weekly):**
- Pages per session from display click: Target > 2.0 (benchmark for quality traffic)
- Bounce rate from display: Target < 65% (if above, audience-page relevance mismatch)
- Time on site from display: Target > 90 seconds
- ABM account reach rate: Target > 70% of active TAL reached per month

**Business Impact Metrics (track monthly):**
- Display-influenced pipeline: Track all opps with at least one display touchpoint in 90-day lookback
- Display-influenced CPL: Target < 2% of ACV (e.g., $150K ACV → max $3,000 CPL)
- Incremental conversion lift vs. holdout: Target > 15% lift after 60-day test
- Pipeline-to-spend ratio: Target 30:1 or higher for influence metric (i.e., $30K spend → $900K influenced pipeline)

**Account-Based Metrics (track monthly for ABM layer):**
- % of TAL accounts with display exposure: Target > 70%
- Account engagement rate: TAL accounts that visited site within 30 days of display exposure
- Account pipeline correlation: % of display-reached accounts that became opportunities within 90 days

## Related Prompts
- [`AI-Powered-Google-Ads-Campaign-Architecture-&-Performance-Max-Intelligence-Engine.md`](./AI-Powered-Google-Ads-Campaign-Architecture-&-Performance-Max-Intelligence-Engine.md) — Google Ads search and Performance Max for demand capture to complement programmatic awareness
- [`AI-Powered-LinkedIn-Ads-Campaign-Architecture-&-B2B-Demand-Intelligence-Engine.md`](./AI-Powered-LinkedIn-Ads-Campaign-Architecture-&-B2B-Demand-Intelligence-Engine.md) — LinkedIn paid social for precise B2B persona targeting alongside programmatic display
- [`../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md) — Intent data activation strategy that feeds the programmatic ABM layer
- [`../../05_Analytics-&-Performance/Paid-Media-&-PPC-Performance-Analytics/Paid-Media-Performance-Analytics-&-ROAS-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Paid-Media-&-PPC-Performance-Analytics/Paid-Media-Performance-Analytics-&-ROAS-Intelligence-Engine.md) — Cross-channel paid media analytics including programmatic attribution

## Integration Tips

**The Trade Desk:**
- UID2 integration: Connect CRM email list via TTD's UID2 framework (privacy-preserving email-based identity) for people-based targeting without third-party cookies
- Koa AI optimization: Enable TTD's Koa algorithmic optimization once you have 1,000+ conversion events; set goal as site visit or downstream conversion
- Solimar reporting: Build a custom Solimar report pulling daily performance by campaign, audience segment, and creative — export to Google Sheets via TTD API for automated BI integration
- Deal Center: Access PMP deals directly within TTD platform; negotiate directly with publishers from the Deal Center interface

**Google DV360:**
- Floodlight integration: Connect DV360 to Google Analytics 4 via Floodlight tags for cross-channel measurement — view GA4 events alongside display spend in a unified view
- Campaign Manager 360: Use CM360 as your ad server for cross-channel creative trafficking and unified attribution across DV360, Search Ads 360, and YouTube
- Google Audience Segments: Layer first-party audiences from Google Ads Customer Match with DV360 display campaigns for cross-platform unified reach
- Looker Studio: Build automated DV360 reporting dashboards via Looker Studio's native DV360 connector — refresh daily and share with leadership

**HubSpot:**
- UTM tracking: Append utm_source=programmatic, utm_medium=display, utm_campaign=[campaign-name] to all landing page URLs in display ads — HubSpot captures these on form submission and attributes to the correct campaign
- Original source tracking: Configure HubSpot to record the first paid source even when contact returns via organic later (prevents last-click organic attribution stealing programmatic credit)
- Display influence reporting: Build a custom HubSpot report showing all contacts with utm_medium=display in their original source OR any associated UTM in their contact activity, segmented by pipeline stage
- Programmatic to SDR workflow: Create enrollment trigger — if contact visits pricing page AND has display touchpoint in last 7 days → enroll in high-priority SDR sequence

**Salesforce:**
- Campaign hierarchy: Create programmatic display as a parent campaign with child campaigns per layer (Prospecting, ABM, Retargeting) — enables aggregate vs. segment-level pipeline attribution
- Pardot/MCAE: If using Pardot, create a programmatic display touchpoint trigger — when Pardot sees UTM params from display, stamp a custom field on prospect record for display influence tracking
- ABM account scoring: Add "Display Exposure Score" field to Account object — increment when display pixels fire on target accounts (integrate via reverse IP enrichment or Demandbase/6sense integration)
- Deal influence report: Build Opportunity Influence report filtered by Campaign Type = "Programmatic Display" with first-touch date before opportunity created date

**Zapier / Make Automation:**
- Trigger: New display-attributed lead (utm_medium=display) submitted form → Action: Slack alert to SDR team with company name, page visited, and display campaign that influenced → SDR prioritizes outreach within 24 hours
- Trigger: ABM account reaches display frequency threshold (via webhook from DSP API) → Action: Update Salesforce Account field "ABM Display Active = Yes" + notify account owner
- Trigger: Display campaign CPL exceeds 2× target (via DSP API daily report) → Action: Pause campaign + create HubSpot task for paid media manager to review

## Troubleshooting

**Problem: Display CTR is below 0.05% across all audiences after 500,000 impressions — campaigns appear to be serving but not engaging**
Solution: Low CTR in programmatic display typically signals one of three problems. First, check creative quality — is the ad visually distinct and does the message immediately communicate a relevant benefit without reading the headline? Display ads must work at a glance in under 1 second; if your creative looks like a generic banner, it will be ignored. Create a new variant with a single bold stat (e.g., "47% faster" in 72pt font) and test against current. Second, check audience relevance — pull the placement report and see which publisher domains are serving your ads; if you see irrelevant domains (recipe sites, sports sites, entertainment content), tighten your brand safety and publisher settings or add a custom blocklist. Third, check if your audience segments are too broad — B2B programmatic on open exchange often reaches consumers, not decision-makers; shift more budget to PMP deals where publishers guarantee B2B professional audiences.

**Problem: Display is driving lots of clicks and site traffic, but zero pipeline attribution — leadership says display isn't working**
Solution: This is almost always an attribution configuration problem, not a performance problem. Display is an influence channel that rarely gets direct last-click credit. Run three fixes immediately: (1) Set up view-through attribution with a 1-day window in your DSP and export view-through conversions separately — this shows prospects who saw your ad and then converted organically; (2) Pull a CRM report of all opportunities created in the last 90 days and cross-reference their UTM history — leads that touched display at any point before opportunity creation count as display-influenced; (3) If budget allows, run a 60-day incrementality test with a 10% holdout — comparing conversion rates of exposed vs. unexposed audiences is the only statistically valid way to prove display's causal impact to a skeptical CFO.

**Problem: ABM display campaigns are not reaching enough target accounts — account reach rate is below 40% after 30 days despite budget allocated**
Solution: Low ABM reach rates typically stem from audience matching failures or inventory constraints. Check three things: (1) Verify your TAL upload matched successfully in the DSP — B2B company IP targeting typically achieves 30-60% match rates; if your 500-account TAL only matched 150 companies, upload a hashed email list of contacts at those accounts via LiveRamp to supplement IP targeting; (2) Check if your CPM bid is winning auctions at target accounts — pull a frequency report; if frequency at reached accounts is very high (20+) but total account reach is low, you have a supply problem, not a match problem — increase bid floor by 25% or source direct PMP deals with publishers your target accounts are known to read; (3) Expand your target account definition temporarily — if your TAL is highly specific (50 named accounts), reach will always be limited; build a Tier 2 firmographic-matched audience alongside the TAL to maintain delivery volume while the TAL campaigns stabilize.

## Version History
- v1.0: Initial creation (auto-generated)
