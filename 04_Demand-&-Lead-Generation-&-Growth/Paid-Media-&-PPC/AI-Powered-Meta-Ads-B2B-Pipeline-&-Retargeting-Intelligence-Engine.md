# AI-Powered Meta Ads B2B Pipeline & Retargeting Intelligence Engine - Build Meta Campaigns That Generate Qualified Pipeline at 1/10th the Cost of LinkedIn

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** Meta Ads, Facebook Ads, Instagram Ads, B2B advertising, retargeting, demand generation, pipeline marketing, CAPI, lead gen, account-based advertising

## Overview
Designs a complete Meta Ads program for B2B companies — covering campaign architecture, audience sequencing, creative strategy, Conversions API setup, and revenue attribution — engineered to capture in-market buyers through cost-efficient retargeting and lookalike expansion. Use this when LinkedIn CPCs are too expensive to scale, when you need a lower-funnel retargeting engine for website visitors who didn't convert, or when you want to surround your ICP across channels at a fraction of the cost.

## Quick Copy-Paste Version

You are a senior Meta Ads strategist who has managed $30M+ in B2B Meta spend. Build a complete Meta Ads pipeline program for the company below.

COMPANY CONTEXT:
- Company: [Your Company] — [e.g., "AI-powered project management platform for engineering teams at mid-market SaaS companies"]
- ICP: [e.g., "VP Engineering, Engineering Manager, Head of Product at B2B SaaS companies, 50–500 employees, Series A through Series C"]
- Deal size: [e.g., "$18K ACV, 60-90 day sales cycle, 2-3 person buying committee"]
- Monthly Meta budget: [e.g., "$15,000/month"]
- Goal: [e.g., "Generate 60 Marketing Qualified Leads per month at under $250 CPL, contribute $1.5M sourced pipeline per quarter"]
- Competitors: [e.g., "Linear, Jira, Asana"]
- CRM/MAP: [e.g., "HubSpot + Salesforce"]
- Website traffic: [e.g., "12,000 unique visitors/month — high intent pages: /pricing, /demo, /features/engineering"]
- Current Meta state: [e.g., "Running broad interest campaigns targeting 'technology' — poor lead quality, $400+ CPL"]

DELIVERABLES:

1. FULL-FUNNEL CAMPAIGN ARCHITECTURE
   Design 4-6 campaigns covering TOFU, MOFU, and BOFU. For each:
   - Campaign objective (Traffic, Engagement, Lead Generation, Conversions, Video Views)
   - Budget allocation ($) and % of total
   - Core audience strategy
   - Ad format recommendation with rationale
   - Bid strategy and starting daily budget

2. AUDIENCE STRATEGY BLUEPRINT
   For each funnel stage:
   - Cold audiences: interest stacks, behavior targeting, and B2B job title overlays using Meta's limited B2B targeting
   - Custom Audiences: website visitors by page (segment high-intent pages separately), video viewers by percentage watched, lead form openers/submitters, customer list for suppression/lookalike seeding
   - Lookalike Audiences: seed source, percentage (1% vs. 2-5%), country layering
   - Exclusions to prevent wasting spend on existing customers and recent converters
   - Estimated audience size for each segment

3. B2B RETARGETING SEQUENCE (this is where Meta wins)
   Design a 3-stage retargeting waterfall for a 90-day buying cycle:
   - Stage 1 (Hot — visited /pricing or /demo in last 14 days): audience, creative angle, offer, frequency cap
   - Stage 2 (Warm — visited key feature pages in last 30 days): audience, creative angle, offer, frequency cap
   - Stage 3 (Nurture — visited blog/content in last 60 days): audience, creative angle, offer, frequency cap
   For each stage: specific ad copy angle, CTA, landing page destination, and expected CPL range

4. CREATIVE STRATEGY FOR B2B META
   Meta creative performs differently than LinkedIn. Provide:
   - Video ad structure for B2B (hook, problem statement, solution, CTA) with word counts per section
   - Static image ad formula that stops the scroll for a B2B audience on Facebook/Instagram feed
   - Carousel ad strategy: use case carousel vs. feature carousel vs. social proof carousel — when to use each
   - Lead Gen Ad form configuration: which fields to include/exclude, offer copy, privacy policy note, thank-you screen CTA
   - Creative testing matrix: what to test first in a new account (audience vs. creative vs. offer)

5. CONVERSIONS API (CAPI) & ATTRIBUTION SETUP
   - Required CAPI events to fire for B2B: PageView, Lead, InitiateCheckout (demo request), Purchase (closed deal)
   - How to pass CRM data back to Meta via CAPI for offline conversion tracking
   - Event Match Quality (EMQ) score optimization: which identifiers to pass (email hash, phone, external_id)
   - UTM parameter structure for Meta (campaign/adset/ad level)
   - Attribution window recommendation for a 60-90 day B2B sales cycle

6. PIPELINE ATTRIBUTION & MEASUREMENT
   - Weekly KPI dashboard: CPM, CTR, CPL, MQL-to-SQL rate, cost-per-opportunity, pipeline sourced
   - How to connect Meta leads to CRM pipeline stages for revenue attribution
   - 30/60/90-day performance benchmarks for this ICP/budget
   - Early warning signals that a campaign is underperforming (before you waste budget)

Output as a structured, actionable plan. Use specific numbers and copy examples. Every recommendation must be implementable in Meta Ads Manager today.

## Advanced Customizable Version

ROLE: You are a principal Meta Ads strategist and B2B demand generation consultant with 12+ years building pipeline programs using Facebook and Instagram advertising. You have managed accounts ranging from $5K/month early-stage startups to $300K/month enterprise programs. Unlike most Meta agencies that optimize for B2C vanity metrics, you think exclusively in cost-per-opportunity and pipeline-to-revenue. You understand Meta's algorithm, auction dynamics, ad relevance diagnostics, and Advantage+ AI features at a technical level. You know how B2B buying committees behave on social and you design systems — not one-off campaigns — that compound over time. Your output should feel like hiring a $250/hr consultant who has built this exact motion dozens of times.

---

SECTION 1: COMPANY & PROGRAM PROFILE

Company Overview:
- Company name and description: [Name] — [1-sentence description of what you do and for whom]
- Stage and scale: [e.g., "Series B, $12M ARR, 85 employees, scaling from $1.5M to $4M ARR this year"]
- Primary value proposition: [What outcome do you deliver, for whom, measured in what metric?]
- Sales motion: [e.g., "Inbound + outbound; BDR qualifies inbound leads, AE closes; no-touch PLG for SMB under $5K"]

Ideal Customer Profile:
- Primary buying persona: [Title, seniority, key pain, why they care now]
- Secondary/influencer persona: [Title, how they influence the buying decision]
- Economic buyer: [Who signs the contract and owns the ROI conversation]
- Champion persona: [Who drives internal adoption and builds internal business case]
- Firmographics:
  * Employee range: [e.g., "100–2,000"]
  * Revenue range: [e.g., "$10M–$500M"]
  * Geographies: [e.g., "US primary, UK/Canada secondary"]
  * Priority verticals: [e.g., "FinTech, HealthTech, MarTech, Professional Services"]
  * Tech stack signals: [e.g., "Uses Salesforce, HubSpot, or Marketo — signals marketing maturity"]
  * Negative ICP: [Who to exclude — e.g., "Agencies, freelancers, companies under 20 employees, students"]

Deal Economics:
- Average ACV: [Amount]
- Sales cycle: [Days from first touch to close]
- Buying committee size: [Number of stakeholders]
- MQL-to-SQL rate: [%]
- SQL-to-close rate: [%]
- Target cost-per-MQL from Meta: [$]
- Target cost-per-opportunity: [$]

Current Meta Account State:
- Monthly budget: [$]
- Current top-performing campaign (if any): [describe]
- Current pain points: [e.g., "Low lead quality, high CPL, poor form completion rate, attribution gaps"]
- Pixel / CAPI status: [e.g., "Pixel installed but no CAPI, low EMQ score of 4.2"]
- Website visitor volume by segment: [e.g., "/pricing: 800/month, /demo: 400/month, blog: 8,000/month"]
- Existing customer list size for seeding lookalikes: [number of records]
- CRM/MAP: [e.g., "Salesforce + Marketo" or "HubSpot all-in-one"]

---

SECTION 2: FULL-FUNNEL CAMPAIGN ARCHITECTURE

Design a complete Meta Ads account structure. For each campaign layer, specify:

TOFU — Awareness & Education (15-25% of budget):
Objective: Video Views or Traffic
Audience: Cold interest + behavior stacks, broad lookalikes (3-5%), content retargeting exclusions
Creative format: Video-first (15-30 second explainer or problem-agitation hook), supplemented by thought leadership static
Goal: Build a warm retargeting pool; do NOT expect direct pipeline here
KPI: Cost-per-video-view (target <$0.10), landing page view rate (target >35%), 3-second video view rate (target >35%)

MOFU — Consideration & Demand Capture (30-40% of budget):
Objective: Conversions or Lead Generation
Audience: 1% Lookalikes from customer list + CRM contacts + website visitors (30-day, all pages minus bounced), interest overlays if audience too small
Creative format: Carousel (use case or ROI proof), Lead Gen Ads for gated content, social proof static ads with customer logos + metrics
Goal: Capture emails and demo intent from in-market buyers
KPI: CPL (target 30-50% below LinkedIn benchmark), lead quality score (% MQL), form completion rate (target >40% for native Lead Gen)

BOFU — Pipeline Acceleration Retargeting (30-40% of budget):
Objective: Conversions
Audience: Website visitors to high-intent pages (/pricing, /demo, /compare) in last 14-21 days; video watchers (75%+, last 30 days); lead form openers who did not submit (last 30 days); CRM leads in MQL/SQL stage who have not booked a call
Creative format: Direct response — demo offer, free trial, ROI calculator, case study specific to their vertical; heavy personalization by segment
Goal: Convert known buyers who are in-market but haven't booked
KPI: Cost-per-demo-booked, demo-show rate, CPO (cost-per-opportunity)

COMPETITIVE — Displacement (10-15% of budget):
Objective: Conversions
Audience: Website visitors from competitor comparison pages + retargeting of leads who went cold after competitive evaluation; lookalike of won-against-competitor CRM segment
Creative format: Direct comparison ad, switching guide, ROI calculator vs. [Competitor], third-party review badges
Goal: Intercept buyers actively evaluating competitors
KPI: Comparison page CTR, competitive CPL, SQL rate from competitive segment

---

SECTION 3: AUDIENCE ARCHITECTURE

For each audience segment, produce a complete configuration spec:

A. Cold Audiences (TOFU/MOFU)
Note: Meta's B2B targeting is weaker than LinkedIn. Layer multiple signals:
- Job title keywords: [list 10-15 relevant titles from Meta's interest-based targeting]
- Employer-type behaviors: ["Business owners", "Small business owners" — use with care]
- Tech behaviors: [e.g., "Facebook Page admins", technology early adopters]
- Interest stacks: [List 8-12 relevant professional interests/publications/tools your ICP reads]
- Income tier overlay: [where applicable for seniority proxy]
- Advantage+ Audience vs. manual: When to trust Meta's AI and when to override

B. Custom Audiences (Core Retargeting Assets)
Build these in priority order:
1. All website visitors — last 180 days (suppression + lookalike seed)
2. High-intent page visitors — last 30 days (/pricing, /demo, /free-trial)
3. Blog/content readers — last 60 days (MOFU nurture)
4. Video watchers — 25%, 50%, 75%, 95% views (engagement ladder)
5. Lead Gen Form openers — last 30 days (high intent, didn't submit)
6. Lead Gen Form submitters — last 90 days (exclusion + lookalike)
7. Customer email list — all time (suppression + lookalike seed)
8. CRM MQL list — synced weekly (BOFU acceleration)
9. CRM Closed-Lost list — last 12 months (re-engagement campaign)

C. Lookalike Audiences
- 1% lookalike from: [customer email list — minimum 1,000 records for accuracy]
- 1% lookalike from: [all website converters]
- 2-3% lookalike from: [video watchers 75%+]
- 3-5% lookalike for: [TOFU reach expansion]
- Geo + seniority overlay on all lookalikes to improve quality

D. Exclusions (non-negotiable)
- Current customers (email list)
- Recent converters (last 30 days)
- Employees (exclude company page fans or manually)
- Specific low-value page visitors (e.g., /careers, /blog/author)

---

SECTION 4: CREATIVE STRATEGY FOR B2B META

Unlike LinkedIn, Meta is a personal feed. B2B ads must interrupt a personal scroll, not a professional one. Adapt accordingly:

Video Ad Framework (30-second B2B hook format):
- 0-3 seconds: Pattern interrupt — bold statement, surprising stat, or problem they feel daily
- 3-8 seconds: Problem agitation — make it specific, avoid jargon
- 8-20 seconds: Solution demonstration — show, don't tell; product screenshot or outcome visualization
- 20-28 seconds: Social proof — one line from a customer with a specific metric
- 28-30 seconds: CTA — single, friction-free ("Get the free guide" or "See it in 3 minutes")

Static Image Formula (thumb-stopping B2B):
- Bold text overlay that states the ICP's pain or desired outcome in <7 words
- Minimal visual clutter — one product screenshot or one powerful stat on clean background
- Brand colors visible but not overwhelming — Meta feed is busy
- Avoid stock photography — use product UI, data visualizations, or text-on-color formats
- Dimensions: 1:1 for feed (optimal for mobile), 9:16 for stories/reels

Lead Gen Ad Configuration:
- Form type: "Higher intent" (adds a review screen — reduces volume but improves quality)
- Required fields: First name, Last name, Work email ONLY (never ask for phone unless your SDR sequence uses it immediately)
- Prohibited fields: Company size, job title (Meta pre-fills these inaccurately — collect via enrichment post-conversion instead)
- Context card: One sentence on what they'll receive + 3 bullet points of specific value
- Thank-you screen: Direct link to the promised asset OR calendar booking link (eliminate email delivery delay)
- Privacy policy: Required — link directly to your privacy policy page

Carousel Ad Strategy:
- Use case carousel: Card 1 = pain, Cards 2-4 = use cases with outcomes, Card 5 = CTA → best for MOFU consideration
- ROI proof carousel: Card 1 = headline result ($X saved / Y% faster), Cards 2-4 = customer quotes with metrics by vertical, Card 5 = "Get your ROI estimate" → best for BOFU conversion
- Feature education carousel: Card 1 = big problem, Cards 2-5 = one feature per card solving one dimension of the problem → best for TOFU engagement

---

SECTION 5: CONVERSIONS API (CAPI) & ATTRIBUTION

CAPI is non-negotiable for B2B Meta. Without it, Meta's algorithm optimizes for the wrong signals in a cookieless, privacy-first world.

Required Events (implement in this priority order):
1. PageView — all pages (Pixel + CAPI duplicate for deduplication)
2. ViewContent — high-intent pages (/pricing, /demo)
3. Lead — form submission (Pixel + CAPI)
4. CompleteRegistration — trial/signup completion
5. Schedule — demo booking confirmed
6. Purchase — closed deal (passed from CRM via CAPI, delayed by sales cycle)

Offline Conversion Events (passed from CRM):
- MQL creation event (passed weekly)
- SQL/Opportunity creation (passed weekly)
- Closed Won (passed at deal close)
- Pass via: Meta Business Suite Offline Events API, or use a native CRM integration (HubSpot → Meta CAPI, Salesforce → Zapier → Meta CAPI)

Event Match Quality (EMQ) Optimization:
- Minimum required: Email hash (sha256), First name, Last name
- Strongly recommended: Phone number hash, City, State, Zip code, Country
- Best practice: Include external_id (your CRM contact ID) to enable deduplication at scale
- Target EMQ: 7.0+ (above 6.0 required for reliable optimization signals)

Attribution Window Recommendation:
- Standard B2B: 7-day click, 1-day view (balances attribution accuracy with cycle length)
- Long cycle (90+ days): Consider 28-day click for last-touch, but layer in data-driven attribution model in Meta's settings
- Cross-channel note: Do NOT rely on Meta's attributed conversions for CFO reporting; use CRM as source of truth with UTM-based multi-touch attribution

UTM Structure:
- utm_source=meta
- utm_medium=paid-social
- utm_campaign=[funnel-stage]-[audience-type] (e.g., "bofu-retargeting-pricing-visitors")
- utm_content=[creative-format]-[creative-concept] (e.g., "video-problem-agitation" or "carousel-roi-proof")
- utm_term=[adset-name-abbreviation]

---

SECTION 6: PIPELINE ATTRIBUTION & MEASUREMENT FRAMEWORK

Weekly KPI Dashboard — track these metrics at each funnel stage:

TOFU Metrics:
- CPM target: <$12 for cold B2B audiences
- 3-second video view rate: >35%
- Landing page view rate: >35%
- Frequency: <3 per 7 days (if higher, creative fatigue — rotate immediately)

MOFU Metrics:
- CTR (link): >1.2% for static, >0.8% for video
- Cost per landing page view: <$3
- Lead Gen form completion rate: >40%
- CPL: [set based on ICP, typically $80-250 for B2B SaaS]

BOFU Metrics:
- CPL from high-intent retargeting: 40-60% lower than cold CPL
- Demo booking rate from lead form thank-you page: >15%
- Cost-per-demo-booked: <[ACV × 2-3% × pipeline-to-close rate]
- Pipeline-per-$1,000-spent: minimum 3:1 return to justify continued investment

Early Warning Signals (trigger review within 48 hours):
- Frequency >4 before 7 days in retargeting campaigns (audience too small or creative exhausted)
- CPL increases >40% week-over-week (competitive pressure or audience saturation)
- Form completion rate drops below 25% (offer-market fit issue, not targeting)
- Ad relevance diagnostics "Below Average" on Quality or Engagement ranking
- EMQ score drops below 5.0 (CAPI implementation issue — affects optimization)

30/60/90-Day Performance Benchmarks:
- Day 30: Learning phase complete on all major campaigns, baseline CPL established, creative winners identified from A/B tests, retargeting audiences populated (need minimum 1,000 website visitors/month)
- Day 60: Lookalike audiences fully optimized, offline conversion data flowing to Meta, first pipeline attribution report produced with UTM + CRM reconciliation
- Day 90: Full funnel cost-per-opportunity established, budget reallocation to highest-ROI campaigns, monthly retargeting creative refresh cycle in place

---

SECTION 7: OPTIMIZATION PLAYBOOK

Creative Refresh Cadence (B2B Meta fatigues slower than B2C but still matters):
- Retargeting campaigns: New creative every 3-4 weeks (small audiences see ads daily)
- Cold/lookalike campaigns: New creative every 6-8 weeks (larger audiences, lower frequency)
- Refresh trigger: Frequency >3 in retargeting OR relevance ranking drops to Below Average
- Refresh strategy: Keep winning format/hook, change visual/copy variation only — do not rebuild entire creative

Audience Expansion Sequence (when core audiences saturate):
- Week 1-4: Core 1% lookalike + high-intent retargeting (focus)
- Week 5-8: Expand to 2% lookalike + broader retargeting window (30→60 days)
- Week 9-12: Layer in Advantage+ Audience (Meta's AI targeting) as a challenger ad set to core audiences
- Month 4+: Test new cold interest stacks, new vertical-specific messaging, geographic expansion

Bidding Strategy:
- Default: Lowest cost bidding during learning phase (first 50 conversions per ad set)
- Scale phase: Cost cap at 1.5× target CPL once learning phase complete
- Retargeting: Highest volume (no cap) — your retargeting audiences are small and qualified, don't throttle them
- Never use: Manual CPM bidding for conversion campaigns; it fights the algorithm

A/B Test Prioritization (run in this order for a new account):
1. Offer test: Demo request vs. gated content vs. free trial (most impactful on CPL)
2. Creative format test: Video vs. static vs. carousel (second-highest impact)
3. Audience test: Broad lookalike vs. narrow interest stack vs. Advantage+ (third)
4. Copy angle test: Pain-led vs. outcome-led vs. social proof-led (refine after above)
5. Landing page test: Native Lead Gen form vs. external landing page (test after baseline CPL known)

---

SECTION 8: META + LINKEDIN OMNICHANNEL COORDINATION

Use Meta and LinkedIn together to surround your ICP at lower total cost:
- LinkedIn: TOFU awareness + top 10% ICP targeting (accept high CPL for precision)
- Meta: MOFU retargeting + BOFU conversion of LinkedIn-engaged audience (low CPL, high ROI)
- Sequence: Run LinkedIn engagement campaigns → export LinkedIn engaged audience list (Company Engagement Report) → upload as Custom Audience to Meta → retarget LinkedIn-warmed buyers on Meta at 1/5th the cost
- Budget split guideline: 60% LinkedIn / 40% Meta for pure B2B; 40/60 for B2B with prosumer or SMB buyers who are more reachable on Meta

Output a complete, campaign-ready Meta Ads program. Include specific ad copy examples for at least 2 creative concepts per funnel stage using this company's context. Every specification must be actionable in Meta Ads Manager — no theoretical frameworks, only executable plans.

## Example Input/Output

**Input Example:**

Company: Meridian AI — AI-powered financial close automation platform for mid-market CFOs and Controllers at companies with $50M–$500M revenue.

ICP: Controller, Director of Finance, VP Finance, CFO at manufacturing, distribution, and professional services companies, 200–2,000 employees. Deal size: $32K ACV, 75-day sales cycle. Budget: $12,000/month Meta.

Website: 8,500 uniques/month. /pricing: 650 visits, /demo: 310 visits, /blog: 6,200 visits. Customer list: 280 records.

**Output Example (BOFU Retargeting Campaign):**

**Campaign: BOFU-Retargeting-High-Intent**
- Objective: Lead Generation
- Budget: $4,200/month ($140/day)
- Audience: Website visitors to /pricing OR /demo in last 21 days + Lead form openers last 14 days (estimated: 850 people) | Exclusions: existing customers, last 30-day form submitters
- Ad Format: Lead Gen Ad (native form)
- Bid: Highest Volume (audience too small for cost cap)

**Creative Concept — "Still on spreadsheets?" Static Ad:**
- Headline: "Close the books in 3 days, not 3 weeks."
- Primary text: "Controllers at companies like yours are cutting close cycles by 68% with Meridian AI. See it in 8 minutes — no demo prep required." 
- CTA: "Book a quick demo"
- Form fields: First name, Last name, Work email
- Thank-you screen: "Watch a 3-minute walkthrough → [URL]" (removes calendar friction)

**CAPI Events for Meridian:**
- Lead (form submission): EMQ 8.1 — passing email + first name + last name + company domain
- Schedule (demo booked): Passed from Calendly via Zapier → Meta CAPI within 24 hours
- Purchase (closed deal): Passed from Salesforce Closed Won via native HubSpot→Meta integration, delayed 75 days average

**Week 4 KPI Benchmarks:**
- CPL target: $140 (vs. $580 LinkedIn benchmark — 76% savings)
- Form completion rate target: 48%
- Estimated MQLs/month from retargeting: 30 (at $4,200/month = $140 CPL)
- Estimated pipeline contribution: $960K/quarter (30 MQLs/month × 40% MQL-to-SQL × 20% close rate × $32K ACV × 3 months)

## Success Metrics

- CPL is 30-60% lower than the company's LinkedIn benchmark within 60 days
- CAPI Event Match Quality score ≥ 7.0 for lead and conversion events
- Retargeting campaign generates ≥ 25% of total paid pipeline at ≤ 40% of total Meta budget
- Lead Gen form completion rate ≥ 35% across all Lead Gen campaigns
- UTM + CRM reconciliation shows ≥ 70% of Meta-attributed leads trackable in pipeline
- Creative fatigue (frequency > 3 in retargeting) does not trigger before 4-week mark

## Related Prompts

- [AI-Powered LinkedIn Ads B2B Pipeline & Account-Based Advertising Intelligence Engine](./AI-Powered-LinkedIn-Ads-B2B-Pipeline-&-Account-Based-Advertising-Intelligence-Engine.md)
- [AI-Powered B2B Google Search Ads Demand Capture & Pipeline Intelligence Engine](./AI-Powered-B2B-Google-Search-Ads-Demand-Capture-&-Pipeline-Intelligence-Engine.md)
- [AI-Powered B2B Performance Marketing & Paid Demand Generation Intelligence Engine](./AI-Powered-B2B-Performance-Marketing-&-Paid-Demand-Generation-Intelligence-Engine.md)
- [Multi-Touch Attribution & Revenue Marketing Intelligence Engine](../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md)

## Integration Tips

- **HubSpot:** Use HubSpot's native Meta Ads integration to sync lead form submissions directly to CRM contacts; map UTM parameters to HubSpot contact properties for source attribution; set up workflow to pass offline conversion events (MQL, SQL, Closed Won) back to Meta CAPI automatically.
- **Salesforce:** Use Salesforce's Marketing Cloud Advertising (or Zapier as a fallback) to create Meta Custom Audiences from Salesforce Contact/Lead lists; pass Opportunity Stage changes to Meta as offline conversion events via CAPI for algorithm optimization.
- **Google Analytics 4:** Ensure GA4 is capturing Meta UTMs correctly; set up GA4 → BigQuery export to build multi-touch attribution models that include Meta's full-funnel contribution beyond last-click.
- **Zapier / Make:** Build automation: (1) New Lead Gen Form submission → Create HubSpot contact + notify SDR in Slack within 5 minutes; (2) Demo booking confirmed → Fire Meta CAPI "Schedule" event; (3) Salesforce Closed Won → Fire Meta CAPI "Purchase" event with deal value for ROAS calculation.
- **Metadata.io / Madkudu:** Use intent-based audience targeting tools to upload high-intent account lists to Meta as Custom Audiences for TOFU account-based advertising — Meta can't target by company name, but you can upload contact lists from accounts showing intent.

## Troubleshooting

**Problem: Lead quality is poor — Meta leads have personal emails, wrong job titles, or are clearly outside ICP.**
Solution: Switch from "Higher Volume" form type to "Higher Intent" form type (adds a review screen that reduces volume 30-50% but improves quality significantly). Add a qualifying question to the form: "What is your company's annual revenue?" with dropdown options. Exclude audiences smaller than 1,000 people from cold campaigns. Review your lookalike seed source — if seeded from all website visitors (including bounces), rebuild with customers-only or high-intent converters-only list.

**Problem: CAPI Event Match Quality score is below 5.0 and campaign performance is declining.**
Solution: You are not passing enough customer information to Meta for it to match events to profiles. Minimum required: sha256-hashed email + first name + last name. Add: phone number (hashed), city, state, zip code, country. Pass CRM contact ID as external_id for deduplication. Audit your CAPI implementation in Meta Events Manager — look for mismatched event names (e.g., "form_submit" vs. Meta's standard "Lead" event). Deduplication between Pixel and CAPI requires identical event_id values — verify this in your implementation.

**Problem: Retargeting audiences are too small — campaigns stuck in learning phase or CPMs spiking above $50.**
Solution: Your website traffic is too low to support dedicated retargeting campaigns at this budget. Minimum viable website traffic: 3,000 unique visitors/month for retargeting to work efficiently. Short-term fix: Expand retargeting window from 14 to 30-60 days to increase audience size; combine /pricing and /demo visitors into one audience rather than separating. Long-term fix: Allocate 20-25% of budget to a TOFU video views campaign to build a video retargeting audience (75% video viewers) as a retargeting substitute while organic traffic grows.

## Version History
- v1.0: Initial creation (auto-generated)
