# AI-Powered B2B SaaS Account-Based Sequential Retargeting Architecture - Buying Committee Multi-Stakeholder Demand Nurture Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** retargeting, ABM, buying-committee, paid-media, demand-generation, pipeline-acceleration, b2b, enterprise

## Overview
Designs a fully autonomous, account-level sequential retargeting program that delivers coordinated, stage-matched messages to each stakeholder in the buying committee — across LinkedIn, programmatic display, YouTube, and Google RLSA — based on real-time account engagement signals rather than individual cookie behavior. Use this when your ICP has 4–8-person buying committees, long sales cycles (60–180 days), and you need paid media to do more than spray banner ads at people who visited your homepage.

## Quick Copy-Paste Version

You are an expert B2B demand generation strategist with deep expertise in account-based marketing and paid media orchestration. Design a complete account-based sequential retargeting architecture for a B2B SaaS company.

Company context:
- Product: [Your SaaS product]
- ICP: [Target company size, industry, revenue range]
- Average ACV: [$ amount]
- Sales cycle length: [X days/months]
- Buying committee: [key roles, e.g., "VP Engineering, CISO, CFO, End-User Champion"]
- Current CRM/MAP: [HubSpot/Salesforce/Marketo]
- Ad platforms available: LinkedIn Ads, Google Ads, Programmatic Display, YouTube

Deliver the following:

1. ACCOUNT SEGMENTATION TIERS for retargeting (Active Pipeline, Engaged Non-MQA, Cold ICP)
2. BUYING COMMITTEE PERSONA MAP: For each stakeholder role, define:
   - Primary pain point to address in ads
   - Proof format that converts them (case study, ROI calc, technical demo, peer review)
   - Preferred content stage (TOFU/MOFU/BOFU)
3. SEQUENTIAL RETARGETING JOURNEY (6-stage): Map the exact ad creative progression for an account from first website visit to late-stage deal support, with audience exclusions and frequency caps at each stage
4. PLATFORM-SPECIFIC TACTICS: LinkedIn Matched Audiences vs Google Customer Match vs Programmatic ABM DSP — when to use which for which persona
5. ACCOUNT ENGAGEMENT SCORING TRIGGERS that automatically promote accounts between retargeting stages (use CRM/MAP field logic)
6. AD CREATIVE BRIEFS for 3 key stages: Awareness Retargeting, Evaluation-Stage Retargeting, and Late-Stage Deal Acceleration
7. BUDGET ALLOCATION MODEL: How to distribute retargeting budget across account tiers and platforms
8. MEASUREMENT FRAMEWORK: Account-level attribution metrics, not click-based vanity metrics

Format everything as an actionable playbook an in-house demand gen team can implement in HubSpot + LinkedIn Campaign Manager + Google Ads this week.

## Advanced Customizable Version

ROLE: You are a senior B2B demand generation architect with 12+ years of experience in account-based advertising, buying committee orchestration, and multi-channel paid media strategy for enterprise SaaS. You combine the rigor of Demandbase's ABM methodology with the creative sophistication of a B2B creative director.

CONTEXT:
Company: [Company Name]
Product Category: [e.g., Revenue Intelligence Platform, Compliance Management SaaS]
ICP Definition:
  - Company size: [e.g., 500–5,000 employees]
  - Industries: [e.g., Financial Services, Healthcare, Manufacturing]
  - Revenue: [e.g., $50M–$1B ARR]
  - Geography: [e.g., North America, EMEA]
  - Tech stack indicators: [e.g., Salesforce + SAP users, AWS infrastructure]
Average ACV: [$X]
Sales cycle: [X–Y days]
Buying committee composition: [List all roles with influence level: Champion, Economic Buyer, Technical Evaluator, Legal/Procurement, End User]
Current pipeline health: [# active opportunities, avg deal stage, # stalled >60 days]
Available first-party data: [Website visitors, CRM contacts, email engagers, event attendees, trial users]
MarTech stack: [CRM + MAP + CDP + Ad platforms]
Monthly retargeting budget: [$X across all platforms]

OBJECTIVE: Design a complete account-based sequential retargeting architecture that:
1. Treats the ACCOUNT as the targeting unit, not the individual
2. Delivers role-specific messages to each buying committee member simultaneously
3. Automatically escalates or de-escalates ad pressure based on account engagement signals
4. Supports active sales deals with late-stage deal acceleration ads
5. Produces pipeline influence and multi-touch attribution that satisfies CFO scrutiny

DELIVERABLE 1 — ACCOUNT AUDIENCE ARCHITECTURE
Build 5 account audience segments for retargeting:

Segment A: HOT PIPELINE ACCOUNTS (Active opportunities, Stage 2+)
- Targeting logic: CRM opportunity created, stage ≥ [X], close date within [X] days
- Retargeting intensity: Maximum (daily frequency cap: 8–12 impressions/person/day)
- Goal: Accelerate deal velocity, address late-stage objections
- Exclusions: Closed-lost (past 6 months), current customers

Segment B: WARM ENGAGED NON-MQA ACCOUNTS (High website engagement, no CRM opportunity)
- Targeting logic: [X]+ page views in [30] days, OR [X]+ minutes on site, OR visited pricing/demo page
- Retargeting intensity: High (frequency cap: 5–8 impressions/person/day)
- Goal: Convert account engagement to demo request / MQA
- Exclusions: Active pipeline, customers

Segment C: ICP INTENT ACCOUNTS (Third-party intent data match, no website history)
- Targeting logic: Intent data vendor signal (G2, Bombora, TechTarget) for target keywords, matched to ICP firmographic filter
- Retargeting intensity: Moderate (frequency cap: 3–5 impressions/person/day)
- Goal: Capture dark funnel demand, drive first website visit
- Exclusions: Active pipeline, Segment B, customers

Segment D: COLD ICP ACCOUNTS (Firmographic match only, no engagement)
- Targeting logic: LinkedIn Matched Audience from ICP account list, firmographic targeting
- Retargeting intensity: Low (frequency cap: 2–3 impressions/person/day)
- Goal: Brand awareness, category education, future pipeline seeding
- Exclusions: All other segments

Segment E: CHURNED CUSTOMER RE-ENGAGEMENT (Lost customers 6–24 months ago)
- Targeting logic: CRM closed-lost date range + churned customer tag
- Retargeting intensity: Moderate (frequency cap: 4–6 impressions/person/day)
- Goal: Win-back during competitor contract renewal seasons
- Exclusions: Active customers, recently lost (<6 months)

DELIVERABLE 2 — BUYING COMMITTEE PERSONA TARGETING MATRIX
For each buying committee role, define:

| Role | Job Title Targets (LinkedIn) | Primary Pain Point | Proof Asset Type | Ad Format | CTA | Content Stage |
|---|---|---|---|---|---|---|
| Economic Buyer | [C-suite titles] | [Business outcome risk] | [Board-ready ROI case study] | [Single Image + Document] | [Request Executive Briefing] | MOFU-BOFU |
| Champion/Power User | [VP/Director titles] | [Day-to-day operational pain] | [Product walkthrough, peer review] | [Video demo ad, carousel] | [Start Free Trial / Watch Demo] | TOFU-MOFU |
| Technical Evaluator | [Technical titles] | [Integration, security, scalability] | [Technical whitepaper, API docs, security review] | [Document ad, text] | [Download Tech Eval Guide] | MOFU |
| Legal/Procurement | [Legal/Ops titles] | [Vendor risk, contract complexity] | [Trust center, compliance docs] | [Single image, document] | [Review Security & Compliance Docs] | BOFU |
| End User | [IC-level titles] | [Workflow inefficiency, tool frustration] | [Tutorial video, customer testimonial] | [Video, carousel] | [See How Others Use It / Join Free] | TOFU |

DELIVERABLE 3 — 6-STAGE SEQUENTIAL RETARGETING JOURNEY
Map the creative escalation journey from first website touch to closed-won:

STAGE 1 — FIRST TOUCH CAPTURE (Days 1–7 post first site visit)
- Audience: Any ICP account visitor, all roles
- Creative angle: Category problem framing (not product pitch)
- Headline formula: "[Industry pain point] is costing [job function] teams [quantified cost/time]"
- CTA: Educational content download (no demo ask)
- Platforms: LinkedIn, Programmatic Display
- Frequency: 3–5 impressions/person/day
- Auto-progression trigger: [X] pages viewed OR [X] minutes on site

STAGE 2 — PROBLEM AGITATION & SOCIAL PROOF (Days 8–21)
- Audience: Accounts with [X]+ sessions, multiple stakeholders engaged
- Creative angle: Customer proof from their industry/company size
- Headline formula: "How [Customer Name, similar ICP] achieved [specific outcome] in [timeframe]"
- CTA: Case study download or customer video
- Platforms: LinkedIn Video, YouTube Pre-Roll, Programmatic
- Frequency: 4–6 impressions/person/day
- Auto-progression trigger: Pricing page visit OR demo page visit

STAGE 3 — EVALUATION SUPPORT (Days 22–45)
- Audience: Accounts that visited demo/pricing/comparison pages
- Creative angle: Why you win in head-to-head evaluations
- Headline formula: "[Competitor] vs [Your Brand]: Why [Target Company Size] companies choose [Your Brand]"
- CTA: Competitive comparison guide, analyst report, free trial
- Platforms: LinkedIn, Google RLSA (bidding premium on bottom-funnel keywords)
- Frequency: 6–8 impressions/person/day
- Auto-progression trigger: Demo request submitted OR CRM opportunity created

STAGE 4 — ACTIVE DEAL ACCELERATION (Opportunity Stage 2–3)
- Audience: CRM opportunity created, all buying committee members at account
- Creative angle: Risk mitigation, implementation success, peer validation
- Headline formula: "[Number] of [ICP companies] went live in [X weeks]. Here's how."
- CTA: Implementation guide, customer reference request, ROI calculator
- Platforms: LinkedIn (matched audience from CRM), Programmatic
- Frequency: 8–12 impressions/person/day
- Auto-progression trigger: Opportunity stage advance OR champion last-activity >14 days

STAGE 5 — LATE-STAGE OBJECTION BUSTING (Opportunity Stage 4–5, Close Date <60 days)
- Audience: CRM opportunity in final stages, focus on economic buyer + legal/procurement
- Creative angle: Address final objections (security, ROI, implementation risk)
- Per-role creative: [Economic Buyer] → CFO testimonial + ROI guarantee; [Legal] → Trust Center + MSA template
- Headline formula: "Before you sign: [Specific final objection] — answered"
- Platforms: LinkedIn (job title targeting overlaid with account list)
- Frequency: 10–14 impressions/person/day
- Auto-progression trigger: Opportunity stalled >21 days OR legal review stage

STAGE 6 — WIN-BACK & EXPANSION (Post-close or post-stall 90+ days)
- Audience A (New logo): New customers for cross-sell expansion
- Audience B (Stalled/lost): Accounts that went cold for re-engagement
- Creative angle: Expansion value (new features, ROI validation) or competitive displacement
- Platforms: LinkedIn, Programmatic
- Frequency: 3–4 impressions/person/day

DELIVERABLE 4 — PLATFORM ORCHESTRATION STRATEGY
For each platform, define the exact targeting method and use case:

LINKEDIN CAMPAIGN MANAGER
- Matched Audiences (Company List upload): For Tiers A, B, E — upload CRM account lists
- Contact List upload: For active deal stakeholders (Tier A Stage 4–5)
- Job Title + Company List combined: For specific persona targeting within target accounts
- Lookalike Audiences: For Tier D cold ICP expansion
- Retargeting (LinkedIn Insight Tag): For website visitors from ICP accounts
- Lead Gen Forms vs. Website Click ads: [When to use each]

GOOGLE ADS — RLSA (Remarketing Lists for Search Ads)
- Bid multiplier recommendations by list membership:
  - Pricing page visitors: +90% bid adjustment
  - Demo page visitors: +75%
  - Blog visitors (multiple): +40%
  - General site visitors (single session): +15%
- Keywords to RLSA-activate: [competitor brand terms, BOFU category terms]
- Negative bid adjustments for customer lists: -100%

PROGRAMMATIC DISPLAY (DSP: The Trade Desk, DV360, or Demandbase)
- Use IP-based account targeting to reach accounts without cookies
- Audience overlay: ICP firmographic match + intent signal from [vendor]
- Creative sequencing: Sequential messaging rules based on impression count
- Brand safety: [Specific exclusion categories for your industry]

YOUTUBE TRUEVIEW
- Audience: Website visitors from ICP accounts + LinkedIn Matched Audience crossover (via Google Customer Match)
- Video creative framework: [Problem → Proof → CTA] in 15s and 60s formats
- Skippable vs. non-skippable: [When to use each based on funnel stage]

DELIVERABLE 5 — ACCOUNT ENGAGEMENT SCORING MODEL FOR RETARGETING AUTOMATION
Define the signal thresholds that trigger audience segment promotion in your MAP/CRM:

| Signal | Points | Segment Action Triggered |
|---|---|---|
| 1st website visit (ICP account) | +10 | Move to Segment B |
| Pricing page visit | +25 | Increase bid multiplier by 50% |
| 3+ sessions in 7 days | +30 | Move to Stage 2 retargeting |
| Demo page visit | +40 | Move to Stage 3 |
| Demo form submit | +75 | Trigger Stage 4 (CRM opportunity creation) |
| Case study download | +20 | Activate persona-specific proof content |
| 14+ days of no engagement | -30 | Reduce to Stage 1 or pause |
| LinkedIn ad form fill | +50 | Notify SDR + activate Stage 3 |

DELIVERABLE 6 — BUDGET ALLOCATION MODEL
Monthly budget: [$X total]
Allocate by account tier (priority = pipeline proximity):
- Tier A (Hot Pipeline): [40%] → Max frequency, all platforms
- Tier B (Warm Engaged): [30%] → LinkedIn + RLSA primary
- Tier C (Intent Data): [15%] → Programmatic primary
- Tier D (Cold ICP): [10%] → LinkedIn brand awareness
- Tier E (Win-Back): [5%] → LinkedIn + Programmatic

Platform split within each tier:
- LinkedIn: [50%] (highest account precision)
- Google RLSA: [25%] (capture active search behavior)
- Programmatic Display: [15%] (scale + frequency)
- YouTube: [10%] (proof content for mid-funnel)

DELIVERABLE 7 — ACCOUNT-LEVEL MEASUREMENT FRAMEWORK
Replace click-through-rate as your primary KPI with these account-level metrics:

Pipeline Metrics (Primary):
- Accounts influenced in active pipeline (ad impression ≥1 on opportunity account): Target [X]%
- Pipeline influenced revenue ($): [Impressions on accounts with open opportunities]
- Deal velocity for ad-touched accounts vs. non-touched: Target [X]% faster close
- Win rate: Ad-touched accounts vs. non-touched: Target [X]% higher win rate

Funnel Progression Metrics (Secondary):
- ICP accounts progressing from Tier D → Tier B per month
- Accounts escalating from Stage 1 → Stage 3 retargeting per month
- Demo requests from accounts with [X]+ ad impressions in [30] days

Efficiency Metrics (Supporting):
- Cost per account touched (pipeline tier)
- Frequency delivered per buying committee member in active pipeline
- Platform overlap: % of buying committee members reached across ≥2 platforms

DELIVERABLE 8 — 90-DAY IMPLEMENTATION ROADMAP
Week 1–2: Foundation
- [ ] Upload ICP account list to LinkedIn Campaign Manager and Google Ads Customer Match
- [ ] Install LinkedIn Insight Tag on all website pages; create audience segments
- [ ] Set up CRM/MAP automation rules for segment promotion triggers
- [ ] Create Stage 1 ad creative (3 variants per persona for A/B testing)

Week 3–4: Launch Core Segments
- [ ] Launch Tier B (Warm Engaged) and Tier D (Cold ICP) on LinkedIn
- [ ] Activate RLSA bid multipliers in Google Ads
- [ ] Launch Stage 1–2 sequential retargeting
- [ ] Connect CRM opportunity stage to ad audience auto-population

Month 2: Optimize & Expand
- [ ] Launch Tier A (Active Pipeline) deal acceleration ads
- [ ] Activate programmatic display for Tier C (Intent Data)
- [ ] Analyze Stage 1 → Stage 2 progression rate; adjust scoring thresholds
- [ ] A/B test persona-specific creative vs. single creative across buying committee

Month 3: Scale & Automate
- [ ] Build automated audience refresh (CRM → LinkedIn sync, weekly)
- [ ] Launch YouTube retargeting for mid-funnel proof content
- [ ] Implement account-level reporting dashboard in BI tool
- [ ] Present pipeline influence data to leadership with revenue attribution

OUTPUT FORMAT: Return the full architecture as a structured playbook with all 8 deliverables. Include specific ad copy headlines, audience targeting logic, and budget numbers (use placeholder variables where company-specific data is needed). Make it implementation-ready: a demand gen manager should be able to open LinkedIn Campaign Manager after reading this and know exactly what to build.

## Example Input/Output

**Input Example:**
Company: Meridian DataOps (B2B SaaS)
Product: Data pipeline monitoring & observability platform
ICP: 200–2,000 employee companies, Data/Analytics-heavy industries (FinTech, eCommerce, SaaS)
ACV: $85,000
Sales cycle: 90 days
Buying committee: VP Data Engineering (Champion), CTO (Economic Buyer), Platform Engineer (Technical Evaluator), VP Finance (Budget Approver)
CRM: Salesforce + Marketo
Platforms: LinkedIn Ads, Google Ads, DV360
Monthly retargeting budget: $18,000
Current pipeline: 47 open opportunities, 12 stalled >45 days

**Output Example (abbreviated):**

**ACCOUNT SEGMENTATION:**
- Tier A (Hot Pipeline): 47 accounts → $7,200/month, all platforms at maximum frequency
- Tier B (Warm Engaged): Accounts with 4+ page views OR pricing page visit in 30 days → $5,400/month
- Tier C (Bombora Intent): "Data Observability," "Pipeline Monitoring" intent accounts, not in CRM → $2,700/month

**BUYING COMMITTEE MATRIX (VP Data Engineering — Champion):**
- LinkedIn targeting: "Head of Data Engineering," "VP Data Engineering," "Director of Data Platform" at [matched accounts]
- Pain: Pagerduty-fatigue from manual pipeline monitoring; 3AM incident calls
- Ad creative: Carousel showing "From 3AM incidents to 8AM dashboards: How Stripe's data team reclaimed their nights"
- CTA: "See the 15-min setup" → Product tour landing page
- Platform: LinkedIn Video ad (30s) + Programmatic sequential display

**BUYING COMMITTEE MATRIX (CTO — Economic Buyer):**
- LinkedIn targeting: "CTO," "VP Engineering," "Chief Technology Officer" at [matched accounts]
- Pain: Data downtime costs $150K+ per incident; engineering talent burned on reactive firefighting
- Ad creative: Single image with stat overlay: "Data incidents cost SaaS companies $230K avg per event. See how Confluent cut theirs by 94%."
- CTA: "Get the ROI Report" → Gated ROI calculator
- Platform: LinkedIn Single Image + YouTube 15s pre-roll (executive audience hour 7–9AM)

**STAGE 4 AD HEADLINE (Active Deal Acceleration):**
> "47 data teams went from alert chaos to autonomous monitoring in under 3 weeks. Here's the implementation guide." → CTA: Download Implementation Blueprint

**BUDGET ALLOCATION (Month 1):**
- LinkedIn: $9,000 (50%) — primary account-precision platform
- Google RLSA: $4,500 (25%) — capture active "data observability platform" searches
- DV360 Programmatic: $3,150 (17.5%) — Bombora intent audience + sequential display
- YouTube: $1,350 (7.5%) — proof content for VP Data Eng + CTO mid-funnel

**ACCOUNT ENGAGEMENT SCORE THRESHOLDS:**
- 4+ pages in session → +35 pts → Trigger LinkedIn Stage 2 escalation
- Pricing page visit → +40 pts → Add to RLSA "high intent" list; bid +90%
- Demo form submit → +75 pts → Create Salesforce opportunity, notify SDR within 5 min, activate Tier A Stage 4 ads within 2 hours via Marketo → LinkedIn sync

**PRIMARY MEASUREMENT KPI (Month 1 target):**
- Pipeline influenced by retargeting: 65% of active opportunities (30 of 47)
- Average impressions delivered per buying committee member in Tier A: 45 impressions in 30 days
- Deal velocity: Tier A ad-touched deals close 18% faster than non-touched (baseline from last quarter)

## Success Metrics

**Pipeline Metrics (review weekly):**
- % of active pipeline accounts with ≥1 impression delivered across ≥2 buying committee members
- Pipeline influenced revenue (ad impression ≥1 on account with open opportunity)
- Deal velocity: Average days to close for ad-touched accounts vs. control group
- Win rate: Ad-touched accounts vs. accounts with 0 ad impressions during sales cycle

**Funnel Progression Metrics (review monthly):**
- Tier D → Tier B account progression rate per month (brand awareness → engaged)
- Stage 1 → Stage 3 account progression rate
- Demo requests from accounts with ≥8 impressions in 30-day window

**Efficiency Benchmarks:**
- LinkedIn CPM for ABM Matched Audience: $35–$65 (B2B SaaS benchmark)
- Google RLSA CTR improvement over standard search: +35–60% minimum to validate
- Target: 70%+ of buying committee members at Tier A accounts reached per month

**Red Flags to Watch:**
- LinkedIn Matched Audience match rate <40% (upload quality issue — fix CRM data hygiene)
- Frequency at Tier A <15 impressions/member/30 days (under-investing in pipeline support)
- Zero account progression from Tier D → Tier B after 60 days (audience quality or ICP list issue)

## Related Prompts
- [ABM Program Architecture & Account Tier Strategy](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/AI-Powered-B2B-ABM-Program-Architecture-&-Account-Tier-Strategy-Intelligence-Engine.md)
- [Cross-Channel Behavioral Retargeting & Intent Signal Activation](../../04_Demand-&-Lead-Generation-&-Growth/Retargeting/AI-Powered-B2B-SaaS-Cross-Channel-Behavioral-Retargeting-&-Intent-Signal-Activation-Revenue-Intelligence-Engine.md)
- [ABM Buying Committee Engagement Scoring & Multi-Stakeholder Deal Velocity Analytics](../../05_Analytics-&-Performance/Account-Based-Marketing-Analytics/AI-Powered-ABM-Buying-Committee-Engagement-Scoring-&-Multi-Stakeholder-Deal-Velocity-Intelligence-Engine.md)
- [LinkedIn Ads Campaign Builder](../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-(PPC-&-Social)/LinkedIn-Ads-Campaign-Builder.md)

## Integration Tips

**LinkedIn Campaign Manager:**
- Use **Company List** uploads (CSV of account domains) as the foundation for Matched Audiences — refresh weekly via Salesforce integration
- Enable **LinkedIn Insight Tag** on all pages and create **website retargeting audiences** with ICP company filters
- Use **Lead Gen Forms** for Stage 3–4 CTAs (pre-filled forms convert 3–5× better than click-to-website for mid-funnel)
- Set up **Campaign Groups** by account tier (not by creative type) so you can see spend and performance per segment

**Salesforce + HubSpot:**
- Build **Account Engagement Score fields** in CRM to trigger audience segment changes automatically
- Use **Salesforce Advertising Studio** or **HubSpot Ads** integration to auto-sync opportunity stages → LinkedIn audience membership
- Create **Salesforce Workflow Rules**: "When Opportunity Stage changes to 'Proposal,' add account to LinkedIn Tier A audience via Campaign Manager sync"
- Set up **Account Activity views** in CRM showing ad impression data from LinkedIn alongside sales activity for AE context

**Google Ads:**
- Import **Salesforce opportunity contacts** to Google Customer Match monthly for RLSA overlay
- Create separate RLSA lists for each funnel stage (pricing visitors, demo visitors, blog-only visitors) and apply different bid multipliers
- Enable **Observation** (not Targeting) for initial RLSA lists to collect data before restricting reach

**The Trade Desk / DV360:**
- Connect to **Bombora** or **G2 Buyer Intent** data for third-party intent audience activation
- Use **CRM account list upload** (IP-based matching via LiveRamp or ABM platform) for account-level targeting without cookies
- Set up **sequential deal rules** in DSP: "If an account has seen creative A 3+ times, switch to creative B automatically"

**Zapier / Make Automation:**
- Build: "When Salesforce account score crosses [75 pts] → Push domain to LinkedIn Campaign Manager audience list → Slack alert to SDR"
- Build: "When opportunity created in Salesforce → Set LinkedIn ad frequency cap to maximum for that account domain → Auto-generate deal-specific ad using content API"

## Troubleshooting

**Problem: LinkedIn Matched Audience match rate is below 40%**
*Solution:* Clean your account list domain format (use root domains, not subdomains), remove duplicates, ensure company names match LinkedIn's database exactly. Upload a minimum of 300 accounts — LinkedIn requires volume for match quality. Try company name + domain combined upload. If still low, use **LinkedIn Company Targeting** (search by company name) instead of list upload as fallback.

**Problem: Ad-touched accounts aren't progressing through pipeline faster than non-touched**
*Solution:* Check your frequency delivery in Tier A — if buying committee members are receiving fewer than 20 impressions per 30-day window, you're under-investing. The typical threshold for measurable deal velocity lift is 25–40 impressions per buying committee member per month. Increase budget in Tier A and confirm your CRM opportunity audience syncs are refreshing weekly (not monthly). Also verify you're reaching 2+ roles at each account, not just the champion.

**Problem: Budget burns too fast on LinkedIn with poor-quality impressions**
*Solution:* Add **seniority filters** (Director+) to all LinkedIn campaigns to avoid serving ads to IC-level employees who aren't buying committee members. Enable **Audience Expansion = Off** on all ABM campaigns — LinkedIn's default expansion will dilute account targeting precision. Use **AND targeting** (Company List AND Job Title) rather than OR logic. Reduce daily budget caps on Tier D accounts and reallocate to Tier A and Tier B where pipeline influence is measurable.

## Version History
- v1.0: Initial creation (auto-generated)
