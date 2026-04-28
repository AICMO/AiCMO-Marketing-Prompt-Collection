# AI-Powered B2B CTV Connected TV & OTT Campaign Architecture & Streaming Audience Pipeline Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-35 min | **Tags:** ctv, connected-tv, ott, streaming-tv, programmatic, b2b-advertising, brand-awareness, abm, demand-generation, pipeline, the-trade-desk, dv360, account-based

## Overview
Designs and executes a full-funnel Connected TV (CTV) and Over-the-Top (OTT) advertising program for B2B SaaS and technology companies — from account-level audience targeting and creative strategy to frequency management, cross-device attribution, and pipeline influence measurement. Use this when you need to reach executive buyers and decision-making committees in their living rooms and on their personal devices at scale, reinforce brand credibility across long enterprise sales cycles, or add a premium video touchpoint that LinkedIn and Google cannot replicate.

## Quick Copy-Paste Version

You are a senior B2B programmatic advertising strategist specializing in Connected TV and OTT campaigns for technology companies. I need a complete CTV/OTT campaign architecture for my company.

Company: [Your Company Name]
Product: [What you sell — e.g., enterprise security platform, HR software, data infrastructure, financial operations tool]
Target audience: [Job titles/buying committee roles — e.g., CISO, CFO, VP Engineering, CHRO, VP Operations]
Target accounts: [ICP description — e.g., 500-5,000 employee FinTech and InsurTech companies in North America]
Monthly CTV Budget: $[X]
Goal: [Brand awareness among target accounts / Pipeline acceleration for late-stage deals / Executive committee reach / Competitive conquest]
ACV: $[Average contract value]
Current sales cycle length: [X months]
Primary buying committee pain points: [Top 3 problems your product solves]
CRM: [HubSpot / Salesforce]

Build me:

1. AUDIENCE TARGETING ARCHITECTURE
   - Account-level targeting strategy using IP matching and ABM data integrations
   - Job function and seniority segments to layer on top of account targeting
   - Third-party data segments from Bombora, Dun & Bradstreet, or Transunion for intent enrichment
   - Lookalike audiences based on best customer profiles
   - Household extension strategy to reach decision-makers at home

2. PLATFORM & INVENTORY STRATEGY
   - DSP recommendation (The Trade Desk, DV360, Amazon DSP, or multi-DSP) with rationale
   - Premium streaming inventory sources (Hulu, Peacock, Paramount+, Tubi, Pluto TV, Amazon Prime Video — AVOD tier)
   - Inventory quality tiers and PMPs (Private Marketplace deals) for brand safety
   - CTV vs. OTT vs. Desktop/Mobile video allocation

3. CREATIVE SPECIFICATIONS & STRATEGY
   - 15-second and 30-second video ad briefs for each buying committee persona
   - Creative messaging framework by funnel stage (awareness vs. consideration vs. pipeline acceleration)
   - QR code and interactive overlay strategy for direct response lift
   - Creative rotation and frequency capping to prevent ad fatigue

4. BUDGET & BIDDING FRAMEWORK
   - CPM benchmarks for B2B CTV targeting (by audience quality tier)
   - Budget allocation across awareness vs. retargeting programs
   - Minimum effective frequency thresholds for brand recall
   - Reach and frequency modeling for target account coverage

5. MEASUREMENT & PIPELINE ATTRIBUTION
   - Brand lift study setup and methodology
   - Website visit lift measurement
   - CRM-connected pipeline influence tracking
   - Cross-device attribution approach (CTV to desktop/mobile conversion path)
   - 30/60/90 day KPI milestones

Format as a structured playbook I can hand to a programmatic media buyer or agency.

## Advanced Customizable Version

ROLE: You are a world-class B2B programmatic advertising strategist with deep expertise in Connected TV and OTT campaigns for enterprise technology companies. You've planned and executed $30M+ in CTV/OTT spend for B2B SaaS companies across security, data infrastructure, HR tech, FinTech, and DevTools. You understand the unique mechanics of CTV inventory procurement, account-level audience matching via IP targeting, the creative constraints of non-skippable video, cross-device attribution in cookieless environments, and how to measure CTV's contribution to enterprise pipeline when last-touch attribution will never capture the full picture.

COMPANY CONTEXT:
- Company: [Company Name]
- Product category: [e.g., Enterprise Data Security Platform / HR Operations Software / RevOps Intelligence Platform / Cloud Infrastructure Management]
- Primary value proposition: [One sentence — specific, quantified if possible]
- Buying committee (list all personas who influence the purchase):
  * Economic buyer: [e.g., CFO, COO, CEO]
  * Technical buyer: [e.g., VP Engineering, CTO, CISO]
  * End user champion: [e.g., Head of Data Engineering, HR Director, VP Sales Operations]
  * Blocker/influencer: [e.g., General Counsel, IT Director, Procurement]
- ICP (Ideal Customer Profile):
  * Company size: [e.g., 250-5,000 employees]
  * Industries: [e.g., FinTech, Healthcare SaaS, Insurance, Professional Services]
  * Geography: [e.g., US only / North America / Global with US priority]
  * Tech stack signals: [e.g., Salesforce + Snowflake shops, AWS-native, Workday customers]
- ACV: $[X] | Sales cycle: [X months] | Current pipeline count: [X open opportunities]
- Monthly CTV/OTT budget: $[X]
- Primary campaign objective: [Brand awareness at accounts in ICP / Pipeline acceleration for deals stalled 60+ days / Competitive conquest against [Competitor Name] installed base / Executive committee penetration for ABM Tier 1 accounts]
- Existing ABM program: [Yes — using [6sense / Bombora / Demandbase / RollWorks] / No — net new CTV program]
- CRM + MAP: [Salesforce + Marketo / HubSpot / other]
- Attribution tool: [Bizible/Marketo Measure / LeanData / Attribution / None]
- Current brand awareness metrics: [% unaided recall / % aided recall / or "unknown — this is a baseline measurement campaign"]

CONSTRAINTS:
- All inventory must meet GARM brand safety standards (no misinformation, no adult content, no politically extreme content)
- Account-level targeting must be verifiable — every audience segment must be traceable to a known data source (not black-box targeting)
- Creative must be approved for non-skippable format — assume 95%+ completion rate; message must land in 15 seconds
- Attribution must be conservative and defensible — no inflated view-through windows; focus on incrementality and influenced pipeline, not claimed pipeline

DELIVERABLE 1: ACCOUNT-LEVEL AUDIENCE ARCHITECTURE

The foundational advantage of B2B CTV over traditional programmatic display is the ability to match known business IP addresses to streaming households and devices — reaching the same decision-makers who visit your website at work, now on their living room TV.

A) First-Party Account Targeting (Highest Priority)

Tier 1 — ACTIVE PIPELINE ACCOUNTS (Direct CRM List Match)
- Upload your open opportunity accounts (company name + domain) to your DSP for IP-to-household matching
- Targeting mechanism: DSP matches company IP ranges → extends to residential IP addresses of employees (via data partners like Tapad, LiveRamp, or FullContact)
- Expected match rate: 35-60% of B2B account lists match to CTV households (lower than digital, but impressions are far higher value)
- Rationale: If a deal has been stalled for 60+ days, CTV brand exposure to the CFO and economic buyer at home can unstick committee-level skepticism that the sales team cannot reach
- Frequency target: 8-12 impressions per account per month for pipeline acceleration (enough to build recall without inducing fatigue)
- Separate ad group from awareness targeting — use late-stage messaging emphasizing ROI proof, peer validation, and de-risking the decision

Tier 2 — TARGET ACCOUNT LIST (ABM Program Accounts)
- Upload your full ICP account list (Tier 1 + Tier 2 ABM accounts) for brand awareness reach
- For each account segment, define: [Account List Name] + [Persona Segment] + [Creative Variant]
- Layer intent data on top of account list:
  * Bombora Company Surge® topics: [Relevant research topics — e.g., "Data Security" + "Cloud Migration" + "Compliance Automation"]
  * G2 Buyer Intent: Accounts actively researching your category or named competitors on G2
  * 6sense or Demandbase Account Score: Target accounts in "Decision" or "Purchase" stage of the AI-predicted buying journey
- Prioritize: Accounts scoring in top 20% of intent signals get 2x impression allocation vs. baseline

Tier 3 — ICP LOOKALIKE EXPANSION (Audience Extension)
- Seed: Your best-fit closed-won customers from the past 18 months (upload domain list to DSP)
- DSP builds lookalike household model based on: IP address patterns, device behavior, content consumption categories, demographic overlaps with seed list
- Expected audience size: 5-15x the size of your seed list
- Use for: Net-new awareness to companies not yet in your ABM database
- Creative: Pure awareness messaging (no late-stage proof points — this audience doesn't know you yet)

B) Third-Party Audience Segments (Layered Enrichment)

Layer these segments on top of account targeting to increase persona precision within matched accounts:

Job Function Segments (from DSP data marketplace):
- [Economic Buyer Persona]: C-Suite Executives / CFO segment / COO segment — available via Oracle Data Cloud, Transunion, Dun & Bradstreet
- [Technical Buyer Persona]: IT Decision Makers / Technology Purchasers / Engineering Leaders — available via Bombora, TechTarget Intent Data, IDG
- [End User Champion]: [Function]-specific segments (e.g., HR Leaders for HR Tech, Finance Professionals for FinOps) — available via Acxiom, Experian, Transunion

Industry Vertical Segments:
- Select 3-5 most important verticals from your ICP and apply industry-specific targeting available via Dun & Bradstreet / Infogroup / Transunion Business targeting in DSP

Company Size Firmographic Segments:
- 250-1,000 employees: Segment A — typically departmental champion budget, 60-90 day cycles
- 1,000-5,000 employees: Segment B — multiple stakeholders, 90-180 day cycles, committee buying
- 5,000+ Enterprise: Segment C — longest cycles, board-level approval, custom creative required

C) Audience Exclusions (Budget Protection)
- Exclude: Current customers (upload customer domain list for suppression)
- Exclude: Accounts in final contract stage (sales-led close — marketing interruption counterproductive)
- Exclude: Disqualified accounts from CRM (churn candidates, permanently declined, budget-frozen)
- Geographic exclusion: Countries where you cannot support (if geographic restrictions apply)
- Content category exclusion: News/political content (brand safety risk regardless of GARM compliance), children's content (audience mismatch), sports live events (frequency spikes, poor recall environment)

DELIVERABLE 2: PLATFORM & INVENTORY STRATEGY

A) DSP Selection Framework

THE TRADE DESK (TTD) — RECOMMENDED FOR MOST B2B PROGRAMS
- Best for: Premium inventory access, strongest B2B third-party data integrations, Unified ID 2.0 for cookieless attribution, best CTV-specific reporting and frequency management
- B2B-specific advantages: Deep integrations with Bombora, D&B, and major identity resolution vendors; Koa™ AI for predictive audience modeling; most transparent auction mechanics in the market
- When to choose TTD: Budget above $20K/month, premium brand-safe inventory required, sophisticated attribution needs, in-house programmatic capability or strong agency relationship
- Access model: Managed service via TTD-certified agency, or self-serve if in-house team has TTD experience

GOOGLE DV360 — SECONDARY RECOMMENDATION
- Best for: Google ecosystem integration (if you use Google Analytics 4, Campaign Manager 360, or YouTube ads already), YouTube OTT and connected TV inventory access, Performance Max alignment
- B2B-specific advantages: Google's first-party audience signals (Business Category, Industry segments), seamless SA360 integration for search + CTV unified measurement
- When to choose DV360: Already using Google Marketing Platform stack, want to unify CTV with YouTube TrueView campaigns, need Google Audience segments for B2B persona targeting

AMAZON DSP — SITUATIONAL
- Best for: E-commerce adjacent B2B (SMB tools, productivity software, AWS ecosystem products), reaching business owners and operators via Amazon's first-party purchase behavior data
- When to choose Amazon DSP: Product-led growth motion where individual users convert, SMB-focused ICP, AWS Marketplace co-sell motion (Amazon DSP + AWS Marketplace activations)
- When to avoid: Enterprise B2B with committee buying — Amazon's B2B audience data is weaker for enterprise decision-makers than TTD's integrations

B) Inventory Quality Tiers & Allocation

Tier 1 — PREMIUM GUARANTEED INVENTORY (30-40% of CTV budget)
Acquire via Private Marketplace (PMP) deals or Programmatic Guaranteed (PG) for brand safety and audience quality assurance:
- Hulu (Disney Advertising): Best B2B reach — 50M+ subscribers, AVOD tier growing; strong targeting capabilities; premium entertainment association enhances brand perception
  * CPM range: $35-$55 for targeted B2B segments
  * Audience notes: Skews 25-54, higher household income, tech early adopters
  * Best for: Awareness campaigns, executive buyer reach
- Peacock (NBCUniversal): Strong for professional/business content adjacency (news, business news, sports)
  * CPM range: $28-$45 for targeted segments
  * Best for: Financial services, professional services ICPs (CNBC content adjacency)
- Paramount+ / Pluto TV (Paramount): Growing AVOD inventory; Pluto TV free tier reaches price-sensitive segments useful for SMB ICP
  * CPM range: $22-$38
  * Best for: SMB-focused ICPs, broad awareness programs with cost efficiency constraints

Tier 2 — PREMIUM OPEN AUCTION INVENTORY (40-50% of CTV budget)
- Amazon Fire TV / Freevee: Strong household data, good for IP-based account matching
  * CPM range: $20-$35
- Tubi (Fox): Largest free ad-supported streaming TV service; broad reach, lower CPM, appropriate for top-of-funnel awareness
  * CPM range: $15-$25
- Roku (OneView DSP or via TTD): Massive reach on Roku devices; Roku data for targeting is excellent for household-level matching
  * CPM range: $18-$30
- Samsung TV Plus / LG Channels: Smart TV native apps; strong household device matching
  * CPM range: $12-$22

Tier 3 — OTT & DESKTOP/MOBILE VIDEO EXTENSION (20-30% of budget)
- OTT pre-roll (non-CTV streaming on tablets, laptops): Extend reach of CTV campaign to same audience on other devices
  * CPM range: $8-$18
- LinkedIn Video (if budget allows): Unique advantage — verified professional context for same persona while at work; connects CTV at-home impression to at-work engagement
  * Note: LinkedIn Video is not CTV but is the closest B2B-verified video complement to CTV

C) Inventory Exclusion List (Brand Safety)
- Programmatic exclusions: Adult content, user-generated content platforms without editorial oversight, gambling, weapons, hate speech (apply IAB/GARM exclusion lists)
- Contextual exclusions: News content adjacent to political controversy (use keyword/URL exclusion lists), local news without national reach (CPM premium with audience quality discount)

DELIVERABLE 3: CREATIVE SPECIFICATIONS & STRATEGY

A) Video Ad Specifications

15-Second Non-Skippable (PRIMARY FORMAT — 70% of creative budget):
- Resolution: 1920×1080 (16:9), MP4 or MOV
- Bitrate: 15 Mbps minimum
- Audio: -14 LUFS normalized (TV broadcast standard)
- File size: Under 200MB
- Companion banner: 300×250 or 728×90 (for OTT overlay — not available on all CTV placements)
- Critical constraint: Brand must appear within first 3 seconds; core message must land by second 12; CTA must be visible and memorable by second 15

30-Second Non-Skippable (SUPPLEMENTAL — 30% of creative budget):
- Same specifications as above
- Use 30s for pipeline acceleration (mid-funnel and late-funnel) where additional proof/narrative space is needed
- Never use 30s for pure awareness campaigns on cold audiences — 15s delivers better cost efficiency and forces message discipline

QR Code Overlay (Where Platform Supports — Hulu, Peacock, Roku):
- Include QR code in final 5 seconds of video pointing to dedicated CTV landing page (track separately from all other campaign traffic)
- Landing page must be mobile-optimized and load in <2 seconds (viewers scan QR on phone while watching TV)
- Low-friction CTA only: Free assessment, ROI calculator, benchmark report, interactive demo — not "Request a Demo" for cold audiences

B) Creative Messaging Framework by Campaign Objective

AWARENESS CREATIVE — "You've Never Heard of Us, But You Should Have":
Structure: [Industry-recognized problem → Scale/urgency signal → Category solution → Brand name + memorable tagline]
Duration: 15 seconds preferred
Tone: Confident, peer-credible, not corporate-polished — executives trust directness over production value
Visual direction: Real customers or recognizable enterprise environments; avoid stock footage of handshakes and laptops
Example script structure (15s):
- 0-3s: Problem statement that stops the viewer (visual + audio — assumes 20% of viewers have muted TV)
- 3-10s: The scale or cost of the problem (specific number, industry benchmark, or named peer company scenario)
- 10-13s: Category solution + brand name
- 13-15s: Tagline + website URL (if QR code not available, URL must be memorable — use vanity URL)

PIPELINE ACCELERATION CREATIVE — "You've Seen Us. Here's Why [Competitor/Status Quo] Isn't Enough":
Structure: [Peer validation → Specific ROI or outcome → De-risk the decision → Urgency signal]
Duration: 30 seconds for complex sales, 15 seconds for reminder frequency
Audience: Only serve to active pipeline accounts and retargeting lists — never to cold awareness audience
Tone: Social proof-heavy; reference customer name and metric where possible (with permission); speak directly to economic buyer's language (ROI, risk reduction, board-level metrics)
Example script structure (30s):
- 0-5s: Customer logo + outcome metric ("Acme Corp reduced X by 40% in 90 days")
- 5-15s: The specific problem they had (the one your ICP CFO/CTO lies awake thinking about)
- 15-25s: How your product solved it, in the economic buyer's language (not product features — business outcomes)
- 25-30s: Risk-reduction close + low-friction next step (QR code / vanity URL for demo or assessment)

COMPETITIVE CONQUEST CREATIVE — "You're Currently Using [Competitor]. Here's What You're Leaving Behind":
Structure: [Implicit competitor context → Specific gap → Migration simplicity → Peer validation from switchers]
Audience: Target accounts identified as using specific competitor (via Bombora Surge on competitor research topics, G2 intent on competitor profile page, technographic data from HG Insights or Clearbit showing competitor product installed)
Duration: 30 seconds — migration decisions require more narrative space
Tone: Respectful of current choice, not disparaging; focus on what's now possible, not what competitor lacks

C) Persona-Specific Creative Variants (Critical for B2B CTV)

For ECONOMIC BUYER (CFO, CEO, COO):
- Language: Revenue impact, risk mitigation, competitive position, board-level metrics
- Visual cues: Business outcomes graphs, peer company logos, ROI statements with $ amounts
- CTA: "See the ROI analysis" / "Get the [Industry] Benchmark" / "Talk to a peer"
- Message focus: Cost of inaction, board-level risk, competitive differentiation

For TECHNICAL BUYER (CTO, VP Engineering, CISO):
- Language: Architecture, scalability, security posture, engineering velocity, technical debt reduction
- Visual cues: Architecture diagrams (simplified), benchmark data, real product interface (not stock)
- CTA: "See the architecture" / "Free technical assessment" / "Explore the docs"
- Message focus: How the technical implementation works, migration path, integration depth

For END USER CHAMPION (Director/VP of the function your product serves):
- Language: Team productivity, workflow improvement, time savings, career outcomes ("get ahead of this problem before it becomes your problem")
- Visual cues: Team scenarios, day-in-the-life scenarios, specific workflow comparison
- CTA: "See it for your team" / "Get the [Function] playbook" / "Talk to someone like you"

D) Creative Testing Cadence
- Launch: 2 creative variants per audience segment (different hooks, same core message) — differentiate by opening 3 seconds only
- Week 3-4: Kill bottom-performing variant based on VCR (Video Completion Rate) and site visit lift; introduce new variant against winner
- Month 2: Test 15s vs. 30s with same creative concept for pipeline acceleration segments
- Month 3: Introduce QR code variant of top performer; measure QR scan rate as incremental conversion signal
- Frequency management: Cap at 4 impressions per household per week for awareness; 8 impressions per household per week for pipeline acceleration (higher frequency justified for active deals)

DELIVERABLE 4: BUDGET & BIDDING FRAMEWORK

A) CPM Benchmarks for B2B CTV (2026 Actuals)

| Inventory Tier | Audience Type | CPM Range | Expected VCR | Best Use |
|---|---|---|---|---|
| Premium PMP (Hulu, Peacock) | B2B account-targeted | $38-$58 | 92-97% | Awareness, brand credibility |
| Premium Open Auction | B2B persona-targeted | $22-$38 | 88-94% | Awareness + retargeting |
| Mid-tier streaming (Tubi, Pluto) | Broad B2B lookalike | $12-$22 | 85-92% | Cost-efficient reach extension |
| OTT/Desktop video | Cross-device extension | $8-$16 | 70-85% | Frequency building, cross-device |
| LinkedIn Video (not CTV) | Verified professional | $25-$55 CPV | N/A | At-work complement to CTV |

B) Budget Allocation Model (Monthly)

| Program | Budget % | Primary Objective | Audience | Creative |
|---|---|---|---|---|
| Account Awareness (ABM list, cold) | 40% | Brand recall, committee reach | Tier 2 + Tier 3 accounts | 15s awareness |
| Pipeline Acceleration | 30% | Deal unstick, CFO/CTO impression | Tier 1 active pipeline accounts | 30s ROI proof |
| Competitive Conquest | 15% | Competitor displacement | Technographic-targeted competitor accounts | 30s switcher narrative |
| Retargeting (CTV visitors → cross-device) | 15% | Move aware viewers to action | CTV-exposed households → desktop retarget | 15s direct-response |

C) Minimum Budget Thresholds for Effective CTV

- Minimum viable CTV program: $15,000/month
  * Below this threshold, account-level match rates produce audience sizes too small for statistically significant measurement and algorithmic optimization
  * Recommended floor for ABM-targeted CTV: 500 target accounts minimum with at least 30-40% match rate required for program viability

- Scale inflection point: $40,000/month
  * Above this, sufficient budget to run true A/B creative tests, build holdout groups for incrementality measurement, and add competitive conquest layer alongside awareness program

- Enterprise CTV program: $100,000+/month
  * Justifies dedicated PG (Programmatic Guaranteed) deals with top inventory, custom brand lift studies, cross-device identity graph investments, and dedicated DSP management

D) Reach & Frequency Modeling

For awareness programs, model expected account coverage before committing budget:
- Input: [Number of target accounts] × [Average employees per account] × [CTV match rate 35-55%] = Addressable households
- Target frequency: 4-6 impressions per matched household per month for initial awareness
- Budget check: Addressable households × Target frequency × Average CPM = Required monthly budget
- Rule of thumb: $50/account/month for premium CTV awareness with adequate frequency; $150/account/month for pipeline acceleration with high frequency

Example: 500 target accounts × $50 = $25,000/month minimum for adequate awareness frequency

DELIVERABLE 5: MEASUREMENT & PIPELINE ATTRIBUTION

A) Brand Lift Study Setup

Platform-Provided Brand Lift (via DSP):
- The Trade Desk (TTD) provides KOA Brand Lift: Surveys exposed vs. unexposed audiences on aided recall, brand perception, purchase intent
  * Minimum budget required: $75,000 cumulative spend for statistical significance
  * Metrics: % aided recall, % message association, % purchase intent lift vs. control
  * Cadence: Measure at 60 days and 90 days; adjust creative if recall below 15% lift

Custom Brand Lift Study (via Kantar or Lucid):
- For programs below TTD Brand Lift minimums, run custom panel study using your ICP job title + company size targeting in Lucid Marketplace
- Pre-campaign baseline: Survey 500 qualified respondents on: brand awareness, perception, and association
- Post-campaign (90 days): Re-survey new sample of 500 to measure delta
- Cost: $8,000-$15,000 for custom study setup and fielding

B) Website Visit Lift (Cross-Device Attribution)

The most accessible near-term CTV measurement signal for B2B:

Methodology:
1. DSP (TTD or DV360) identifies households exposed to your CTV ads
2. Matches those households to desktop/mobile devices via device graph
3. Measures incremental website visits from matched devices vs. control group (unexposed households in same audience segment)
4. Calculates: Exposed group visit rate vs. control group visit rate = Website Visit Lift %

Target benchmarks:
- Brand awareness campaigns: 15-40% website visit lift vs. control
- Pipeline acceleration campaigns: 40-100% website visit lift (higher because audience is already familiar)
- Competitive conquest: 20-50% website visit lift (intent-qualified audience)

Implementation:
- Place DSP pixel/tag on all key pages: Homepage, Pricing, Key solution pages, Demo request page
- Create UTM parameter convention: `utm_source=ctv&utm_medium=video&utm_campaign=[campaign-name]&utm_content=[creative-id]`
- Set up separate GA4 traffic segment for CTV-attributed sessions: Filter on UTM source = ctv

C) CRM-Connected Pipeline Influence Tracking

Step 1 — Account-Level Impression Data to CRM:
- DSP (TTD or DV360) can export account-level impression data (domain + impression count + frequency) as weekly CSV
- Match this data to your CRM accounts by domain: Create custom CRM field "CTV Impressions (Last 30 Days)" and "CTV Last Impression Date"
- This creates a CTV exposure flag on every account that has been reached by your campaign

Step 2 — Build CTV-Influenced Pipeline Report:
- In Salesforce/HubSpot: Filter open opportunities where "CTV Impressions (Last 30 Days) > 0"
- Create CTV Pipeline Influence Snapshot: Total pipeline value of accounts with CTV exposure
- Compare: Win rate of CTV-exposed accounts vs. matched control accounts (same ICP, no CTV exposure)
- Track: Average sales cycle length for CTV-exposed deals vs. non-exposed deals (test hypothesis that CTV exposure reduces cycle length)

Step 3 — Self-Reported Attribution Capture:
- Add "How did you hear about us?" field to all demo request and trial forms — include "TV / Streaming ad" as an option
- Track % of CTV program accounts who self-report TV/streaming as an awareness touchpoint
- Target: 5-15% of accounts in pipeline with CTV exposure self-report awareness via TV (lower than expected — most buyers don't consciously attribute; use as a floor indicator, not a ceiling)

D) 30/60/90 Day KPI Dashboard

Month 1 (Delivery & Technical Validation):
- Pixel fires confirmed: 100% of key pages tracking correctly in DSP and GA4
- Account match rate confirmed: Report from DSP on % of uploaded account list successfully matched to CTV households — target 35-55%; if below 25%, investigate data quality of account list
- Delivery metrics: Impressions delivered, households reached, average frequency, VCR by creative and platform
- Quality signals: Invalid traffic rate (target <5%), viewability (N/A for CTV — native format), brand safety incidents (target 0)
- Early site lift signal: Website sessions from CTV UTMs vs. pre-campaign baseline (Week 3-4 leading indicator)

Month 2 (Optimization Phase):
- VCR by creative: Identify top-performing creative by 15-second completion; reallocate budget toward winners
- Creative frequency analysis: Check if any household segments have exceeded 6 impressions/week — apply frequency cap if so
- Website visit lift preliminary: Compare exposed vs. control group visit rates (TTD measurement if budget qualifies; manual segment comparison if not)
- CRM account exposure check: How many open opportunities have now accumulated CTV impressions? What is the pipeline value of exposed accounts?
- Creative refresh: New variant live against Month 1 top performer

Month 3 (Measurement & Attribution):
- Brand lift study interim results (if applicable): Aided recall lift %, message association %, purchase intent lift %
- Website visit lift final: Exposed vs. control, full 90-day window
- Pipeline influence report: Pipeline value of CTV-exposed accounts; win rate comparison vs. control
- CTV self-report rate: % of accounts who self-attribute TV/streaming in "how did you hear about us" field
- Channel comparison: CTV CPM/reach efficiency vs. LinkedIn Ads CPM/reach for same ICP segment (justify CTV budget vs. alternatives)
- Decision: Scale, reallocate, or restructure based on pipeline influence signal and brand lift data

OUTPUT FORMAT: Structured programmatic media buying playbook with specific audience architecture, inventory recommendations with CPM benchmarks, copy-ready creative briefs for each persona and funnel stage, budget allocation model with rationale, and attribution setup instructions actionable by a media buyer or DSP account manager within one week.

## Example Input/Output

**Input Example:**
Company: Meridian FinOps (Series B, $42M raised)
Product: Cloud financial operations platform — real-time cloud cost visibility, allocation, and optimization for engineering and finance teams
ICP buying committee: VP Engineering, Head of Cloud Infrastructure, CFO, VP Finance — at 300-3,000 employee FinTech, InsurTech, and SaaS companies
ACV: $85,000 | Sales cycle: 90-120 days
Monthly CTV budget: $35,000
Goal: Brand awareness + pipeline acceleration for 40 open opportunities stalled in mid-stage
CRM: Salesforce + Marketo
ABM tool: 6sense (account scores available)
Competitors: CloudHealth by VMware, Apptio Cloudability, Spot.io

**Output Example (partial):**

AUDIENCE ARCHITECTURE — MERIDIAN FINOPS

Tier 1 — ACTIVE PIPELINE (40 accounts, $3.4M pipeline):
Upload all 40 open opportunity accounts from Salesforce to TTD account targeting. Set impression allocation: 10 impressions/household/week for CFO and VP Finance persona segment; 6 impressions/household/week for VP Engineering segment. Creative: 30-second pipeline acceleration variant featuring CloudHealth migration case study from peer FinTech company (if available) or ROI proof point with $ amount.

Estimated Tier 1 audience: 40 accounts × average 8 employees in buying committee → 320 target individuals → 35% CTV match rate → ~112 matched CTV households. Budget for Tier 1: $6,000/month at $28 CPM with 10 impressions/household/week = 55K impressions/month across 112 households. Frequency check: 10 impressions/week × 4 weeks = 40 impressions/household/month — reduce to 6/week if creative fatigue signals appear in Month 2.

Tier 2 — 6SENSE DECISION STAGE ACCOUNTS (accounts scoring 75+ in 6sense):
Export from 6sense all accounts in "Decision" or "Purchase" stage with Bombora intent on "Cloud Cost Management" + "Cloud FinOps" + "FinOps Framework" topics. Expected list size: 150-300 accounts. Upload to TTD for account-level IP matching. Budget: $12,000/month. Creative: 15-second awareness + ROI proof hybrid.

---

30-SECOND PIPELINE ACCELERATION AD — CFO/VP FINANCE PERSONA:

[0-5s] TEXT ON SCREEN + VOICEOVER: "The average 500-person SaaS company wastes $340,000 per year in unused cloud spend. Your finance team can't see it. Your engineers don't want to report it."

[5-15s] VISUAL: Clean split-screen showing cloud cost dashboard (real UI) vs. a confusing spreadsheet. VOICEOVER: "Meridian gives finance and engineering one shared view of cloud costs — so you stop the argument and start optimizing."

[15-25s] VISUAL: Customer logo (FinTech company) + metric. VOICEOVER: "Helix Payments recovered $1.2M in misallocated cloud spend in 90 days. Without a single engineering sprint."

[25-30s] VISUAL: Meridian logo + URL. VOICEOVER: "Meridian. Cloud finance, finally aligned." QR CODE appears for final 5 seconds pointing to meridianfinops.com/roi-calculator

Expected VCR: 93-96% | Expected CPM: $42-$48 (FinTech CFO household targeting, premium inventory)

---

90-DAY TARGETS — MERIDIAN FINOPS ($35K/MO):
- Total accounts reached (matched): 800-1,200 accounts across Tier 1-3
- Total impressions delivered: 1.8M-2.4M
- Website visit lift (exposed vs. control): Target 35%+ lift
- Pipeline acceleration metric: Reduction in average stage duration for Tier 1 CTV-exposed accounts vs. non-exposed matched control (target 15-25 day reduction in 90-120 day cycle)
- 6sense stage progression: % of Tier 2 accounts progressing from Decision to Purchase stage in 90 days (target 12-18%)
- Self-reported TV awareness: 8-12% of new demo requests from target accounts mention "TV ad" or "streaming ad" in attribution field
- New pipeline influenced (CTV-exposed accounts entering pipeline during 90 days): $400,000-$900,000

## Success Metrics

- **Account match rate:** Target 35-55% of uploaded account list successfully matched to CTV households. Below 25% indicates account list data quality issues (outdated domains, non-US accounts in list, SMB accounts with no dedicated office IP). Investigate before scaling budget.
- **Video Completion Rate (VCR):** Target 90%+ for 15-second ads on premium inventory; 85%+ for 30-second. VCR below 80% on CTV (non-skippable) indicates platform-level delivery issue or inventory quality problem — audit TTD/DV360 delivery report by publisher.
- **Website Visit Lift:** Exposed households should visit key pages (pricing, demo, solution pages) at 20-50% higher rates than matched control. Lift below 10% after 60 days indicates creative is not memorable enough to drive intent behavior, not a targeting problem.
- **Brand Lift (Aided Recall):** Target 15-30% lift in aided recall vs. control at 90 days. If recall lift is strong (>20%) but pipeline influence is low, message is memorable but not convincing — shift creative to proof-point focus.
- **Pipeline Influence Rate:** Target 60%+ of CTV program budget-period pipeline from target ICP to have CTV exposure logged in CRM. If below 40%, account match rate is too low — enrich account list with additional IP data or reduce target list to highest-confidence accounts.
- **Creative Fatigue Signal:** Monitor frequency distribution weekly. If any household segment averages above 15 impressions/week, creative fatigue is inevitable — rotate creative immediately even if performance metrics appear stable.

## Related Prompts

- [AI-Powered B2B Full-Funnel Paid Media Campaign Architecture & Budget Velocity Intelligence Engine](./AI-Powered-B2B-Full-Funnel-Paid-Media-Campaign-Architecture-&-Budget-Velocity-Intelligence-Engine.md)
- [AI-Powered B2B Intent Signal Activated Account Advertising & Programmatic ABM Revenue Intelligence Engine](./AI-Powered-B2B-Intent-Signal-Activated-Account-Advertising-&-Programmatic-ABM-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B LinkedIn Ads Campaign Architecture & Pipeline Revenue Intelligence Engine](./AI-Powered-B2B-LinkedIn-Ads-Campaign-Architecture-&-Pipeline-Revenue-Intelligence-Engine.md)
- [AI-Powered CTV OTT Streaming TV Advertising Performance Analytics & Intelligence Engine](../../../05_Analytics-&-Performance/Paid-Media-&-PPC-Performance-Analytics/AI-Powered-CTV-OTT-Streaming-TV-Advertising-Performance-Analytics-&-Intelligence-Engine.md)

## Integration Tips

- **The Trade Desk (TTD):** Enable Unified ID 2.0 (UID2) on your website (requires hashing email addresses of known visitors) to dramatically improve cross-device attribution from CTV to desktop conversion events; set up TTD Measurement Studio to track exposed vs. unexposed cohort visit rates without requiring third-party cookies; use TTD's Koa™ AI to automate bid optimization toward account segments showing highest website visit lift signals
- **Salesforce:** Build a custom CTV Impressions object that receives weekly data exports from TTD/DV360 account-level impression reports; create a Salesforce report that joins open opportunities to CTV exposure data by account domain; set up a Salesforce Flow that flags accounts as "CTV Exposed" when impression data exceeds threshold (e.g., 20+ impressions in 30 days) — use this flag to trigger coordinated SDR outreach within 48-72 hours of CTV saturation (CTV → SDR sequencing dramatically improves cold outreach response rates)
- **6sense / Demandbase:** Sync your CTV-exposed account list back into your ABM platform as a custom segment called "CTV Exposed — Active"; use this segment to trigger coordinated outbound sequences in Outreach/Salesloft, push LinkedIn Sponsored Content ads to same accounts simultaneously (CTV at home → LinkedIn at work = multi-touchpoint committee saturation), and increase SDR prioritization score for accounts with both CTV exposure and high intent signals
- **HubSpot:** Install your DSP's pixel via HubSpot's custom tracking code section; create a custom Contact property "CTV Attributed Session" (Boolean) populated when a contact session originates from CTV UTM parameters; build a HubSpot workflow that triggers a "high-value CTV visit" task for assigned SDR when a CTV-attributed session from a target account includes pricing page or demo page visit — this real-time signal enables CTV-to-outreach sequencing within 24 hours
- **GA4:** Set up a dedicated CTV traffic segment (utm_source=ctv filter) to track CTV-attributed sessions separately from all other paid media; create a GA4 Exploration report comparing CTV traffic vs. LinkedIn traffic vs. organic for: pages per session, session duration, and demo form completion rate — use this data to justify CTV CPM premium vs. cheaper alternatives and inform landing page optimization for CTV-sourced visitors
- **Marketo:** Create a Smart List for "CTV Program — Target Account Contacts" using account domain matching to your CTV audience list; enroll these contacts in a CTV-aligned nurture track that coordinates email nurture cadence with your CTV impression schedule (email frequency and CTV impression frequency should be aligned — if a target account is receiving 6 CTV impressions/week, ensure email cadence is 1-2/week maximum to avoid total touchpoint overload)

## Troubleshooting

**Problem: Account list match rate is below 20% — insufficient audience size for program to deliver**
Solution: Low match rate typically has three root causes: (1) Account list quality — audit for stale domains, international accounts, or accounts with no physical office IP address (fully remote companies often have no consistent IP for matching); enrich your account list with tools like Clearbit, ZoomInfo, or Cognism to validate company domains and add alternative domain variants; (2) Account size mismatch — accounts with fewer than 50 employees often have insufficient IP data for CTV household matching because employees work from home or co-working spaces rather than a consistent company IP; for SMB ICPs, consider shifting from IP-matched account targeting to job title + industry + company size contextual targeting which does not require IP matching; (3) DSP data partner limitation — try switching identity resolution partner within your DSP (TTD offers multiple identity graph options including LiveRamp, Tapad, and Neustar; test which partner yields highest match rate for your specific account list).

**Problem: High VCR but zero measurable website visit lift after 60 days**
Solution: Viewers are completing the ad but not acting. This is a creative effectiveness problem, not a delivery problem. Run this diagnostic: (1) Message test — is the ad communicating the core value proposition clearly within 15 seconds, or is it brand-building without a specific problem-solution signal? CTV for B2B must communicate enough of a value proposition that the viewer is motivated to search for your brand on their phone or laptop within hours of viewing — generic brand ads rarely achieve this; add a specific, memorable claim or statistic that creates information-gap curiosity; (2) CTA visibility — is the URL or QR code on screen long enough and large enough? CTV viewers are often 8-12 feet from the screen; the URL should be a memorable vanity URL (not a long UTM-laden string) and on-screen for a minimum of 4 seconds; (3) Frequency insufficiency — check if each matched household has actually received the target frequency level; if average frequency is below 3 impressions/month, the ad has not had enough exposures to drive recall-driven intent behavior; increase frequency cap or budget before diagnosing creative failure.

**Problem: CTV-exposed accounts are not showing higher win rates or shorter sales cycles vs. control group after 90 days**
Solution: CTV influence on pipeline is real but typically operates on a 6-12 month lag for enterprise B2B — especially for deals not yet in pipeline at campaign start. Check your measurement window: (1) Confirm that your control group is truly comparable to your exposed group — if your Tier 1 CTV targeting includes your highest-priority pipeline accounts, these accounts may have been priority-targeted precisely because they are already more likely to close; use a randomized holdout methodology (randomly exclude 20-30% of target accounts from CTV targeting) rather than comparing exposed vs. never-targeted accounts which may differ systematically; (2) Extend measurement horizon — CTV awareness programs for enterprise B2B should be evaluated at 6 months minimum for pipeline influence, not 90 days; 90-day measurement captures only the most immediate effects; build an 18-month measurement plan from the start; (3) Check creative-to-audience alignment — if pipeline acceleration creative is running to cold awareness audiences or vice versa, attribution will be confused; audit DSP delivery reports to confirm each creative variant is reaching only its intended audience segment.

## Version History
- v1.0: Initial creation (auto-generated)
