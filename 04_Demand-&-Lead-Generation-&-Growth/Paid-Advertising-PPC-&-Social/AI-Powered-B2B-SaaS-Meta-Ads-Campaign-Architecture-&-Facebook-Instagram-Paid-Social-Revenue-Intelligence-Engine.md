# AI-Powered B2B SaaS Meta Ads Campaign Architecture & Facebook-Instagram Paid Social Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** meta-ads, facebook-ads, instagram-ads, paid-social, b2b-saas, retargeting, demand-generation, custom-audiences, lookalike-audiences

## Overview
Designs a complete Meta Ads (Facebook + Instagram) campaign architecture for B2B SaaS — including full-funnel campaign structure, CRM-based audience strategy, creative frameworks optimized for B2B buyers on social, Conversions API setup, and closed-loop pipeline attribution — producing a ready-to-execute playbook an AI agent can build via the Meta Marketing API. Use when launching a Meta Ads program to complement LinkedIn and Google, scaling retargeting coverage on existing pipeline, or driving cost-efficient brand awareness to ICP audiences that LinkedIn pricing makes uneconomical at scale.

## Quick Copy-Paste Version

You are a senior B2B SaaS Meta Ads strategist. Design a complete Meta Ads campaign architecture for [Your SaaS Product] — a [brief product description] targeting [ICP: role/persona] at [company size/type] companies.

Meta's B2B targeting is intent-based and behavioral, not job-title based like LinkedIn. Design a strategy that maximizes Meta's retargeting and lookalike audience strengths while compensating for the lack of professional targeting.

Build a full campaign structure with these components:

1. AUDIENCE STRATEGY (Meta-native approach — no job title targeting):
   - Cold audiences: Interest + behavior targeting stacks, lookalikes from closed-won customers
   - Warm audiences: Website Custom Audiences by page visited and recency window
   - CRM audiences: Customer list upload for suppression, lookalike seeding, and win-back campaigns
   - Video engagement retargeting: Users who watched 50%+ of your video ads

2. CAMPAIGN OBJECTIVE STRUCTURE (full funnel):
   - Awareness: Reach or Video Views for cold ICP-adjacent audiences
   - Consideration: Traffic or Engagement to warm audiences and blog content
   - Conversion: Leads (Lead Ads) or Sales (website conversion) for bottom-funnel

3. CREATIVE PLAN (one ad set per funnel stage):
   - Top-of-funnel: Short-form video (15-sec hook + problem statement), no brand mention until second half
   - Mid-funnel: Carousel or single image with customer outcome proof, case study teaser
   - Bottom-of-funnel: Lead Ad form with demo/trial offer, or dynamic retargeting to pricing/demo pages

4. BUDGET FRAMEWORK:
   - Cold prospecting: 40% of budget (lookalikes + interest stacks)
   - Retargeting: 45% of budget (website visitors by recency and page depth)
   - CRM win-back / expansion: 15% of budget

5. MEASUREMENT & ATTRIBUTION:
   - Meta Pixel + Conversions API (CAPI) for server-side event tracking
   - UTM structure for CRM closed-loop attribution
   - Custom conversions: demo request, trial signup, pricing page (micro-conversion)

Output a complete implementation brief an engineer or Meta Ads AI agent can execute via the Meta Marketing API, including audience specifications, creative briefs, and tracking configuration.

## Advanced Customizable Version

ROLE: You are a Meta Ads revenue architect with 12+ years building B2B SaaS paid social programs across Facebook and Instagram. You understand the fundamental difference between Meta and LinkedIn for B2B: Meta wins on cost efficiency, retargeting precision, and lookalike audience quality — not on professional targeting. You architect programs that route the right message to the right audience at the right funnel stage, using CRM data and website behavior as the targeting spine.

COMPANY CONTEXT:
- Product: [product name] — [one-sentence description]
- Category: [e.g., "AI-powered revenue intelligence platform for enterprise sales teams"]
- Primary ICP: [role/persona description], e.g., "VP of Sales and Sales Operations leaders at B2B SaaS companies, 100–1,500 employees, Series B through growth stage"
- ACV (Average Contract Value): $[X]
- Sales cycle: [X weeks/months]
- Monthly Meta Ads budget: $[X]
- Existing pixel data: [X website visitors/month] (if <1,000/month, note cold audience limitations)
- CRM contacts available for upload: [X total] (customers: [X], leads: [X], churned: [X])
- Primary competitors: [Competitor A], [Competitor B], [Competitor C]
- Primary conversion goals: [demo request / free trial / pricing page visit / contact form]
- Geographic focus: [US / EMEA / global]
- Existing ad accounts: [new account / existing with pixel history]

OBJECTIVE: Design a complete Meta Ads architecture that generates [X] qualified MQLs per month at a target CPL of $[X], with pipeline influence attributable to closed-won ARR via CRM integration.

---

DELIVERABLE 1 — AUDIENCE ARCHITECTURE:

Meta B2B TARGETING PHILOSOPHY:
Unlike LinkedIn, Meta has no reliable job title targeting. Instead, build your ICP reach through four audience layers:

LAYER 1 — COLD PROSPECTING (Lookalike Audiences — highest quality cold reach):

A) Closed-Won Customer Lookalike:
- Source list: Export CRM — Closed Won accounts from last 18 months, primary contact email + phone
- List size: Minimum 100 seed records (500+ is ideal for quality)
- Lookalike percentage: 1% (highest similarity to source; expand to 2–3% only if 1% exhausts budget)
- Geographic match: Match to your target geographies only
- Why: This is your highest-value cold audience — Meta's algorithm finds people who behaviorally resemble your best customers
- Layer with: Broad interest exclusions to remove obvious non-ICP users (exclude: "High school students," "Stay-at-home parents" interests)

B) MQL/SQL Lookalike:
- Source list: Export CRM — all contacts that reached MQL or SQL stage (regardless of outcome)
- Lookalike percentage: 1–2%
- Use for: Separate ad set to test CPL efficiency vs. Closed-Won lookalike

C) High-Intent Website Visitor Lookalike:
- Source: Custom Audience — Pricing or Demo page visitors, 180 days
- Lookalike percentage: 1%
- Use for: Cold prospecting when CRM list quality is low (<100 records)

LAYER 2 — INTEREST + BEHAVIOR STACKS (Broad cold prospecting — Meta-specific):

Interest Stack A — Business Decision Makers:
- Facebook targeting category: "Business Decision Makers" (Meta's built-in B2B segment — limited but usable)
- Layer with: "Business-to-business (B2B)" behavior
- Add: Pages liked related to [your category] — e.g., HubSpot, Salesforce, Gainsight (competitors' and adjacent tools' Facebook pages indicate professional interest)
- Age bracket: 28–55 (filter out student demographics)
- Estimated reach: [varies by geography — note in implementation]
- Budget recommendation: 20% of cold prospecting budget; use primarily to find new audiences for lookalike seeding

Interest Stack B — Competitor Audience Targeting:
- Target: Users who have expressed interest in [Competitor A], [Competitor B], [Competitor C] (via page likes or engagement)
- This is imprecise on Meta (unlike LinkedIn's skills targeting) but directionally valuable
- Ad angle: "There's a reason 200+ [Competitor A] customers switched to [Your Product] in 2025" — migration narrative
- Use: Separate ad set; test CPL vs. Lookalike campaigns

LAYER 3 — WEBSITE CUSTOM AUDIENCES (Retargeting — highest conversion intent):

Build the following Website Custom Audience segments in Events Manager:

| Audience Name | URL Rule | Time Window | Estimated Size | Priority |
|---|---|---|---|---|
| All Site Visitors | Domain: yourdomain.com | 90 days | [X] | Medium |
| High-Intent: Pricing Page | URL contains /pricing | 30 days | [X] | Critical |
| High-Intent: Demo Page Non-Converters | URL contains /demo — EXCLUDE: Thank-you page | 14 days | [X] | Critical |
| Case Study Readers | URL contains /customers | 60 days | [X] | High |
| Competitor Comparison Visitors | URL contains /vs | 30 days | [X] | High |
| Blog Readers — [Category Topic] | URL contains /blog | 90 days | [X] | Medium |
| Pricing Page — Re-entry (high-intent repeat) | URL contains /pricing, viewed 2+ times | 14 days | [X] | Critical |

EXCLUSION AUDIENCES (always exclude to prevent budget waste):
- Current Customers: upload CRM customer list → exclude from all acquisition campaigns
- Converted leads (last 30 days): users who already submitted a demo request
- Employees: upload internal team email list

LAYER 4 — CRM CUSTOM AUDIENCES (deterministic matching — highest precision):

Upload the following CRM lists to Meta Custom Audiences (match via email + phone for highest match rate — typically 50–70% match):

| List Name | CRM Export | Campaign Use |
|---|---|---|
| Closed-Won Customers | Closed-Won contacts | Suppression + Lookalike seed |
| Open Opportunities | Contacts with open deals | Influence buying committee members; reinforce sales motion |
| MQL/SQL — Unconverted | Contacts stalled in funnel | Re-engagement with new offer |
| Churned Customers (6–18 mo) | Churned + churned reason not "no budget" | Win-back campaign |
| Competitive Displacement Targets | Contacts using competitor (if tracked in CRM) | Migration narrative ads |
| Trial Users — Unconverted | Free trial users past Day 14, not converted | Trial conversion sequence |

---

DELIVERABLE 2 — CAMPAIGN STRUCTURE MAP:

Produce a hierarchical campaign table:
| Campaign | Objective | Audience | Ad Format | Monthly Budget | Primary KPI |

META CAMPAIGN ARCHITECTURE — 5 CAMPAIGNS:

A) BRAND AWARENESS CAMPAIGN (Cold — Lookalike Audiences):
- Objective: Video Views or Awareness (Reach)
- Audience: Closed-Won Customer Lookalike 1% + MQL Lookalike 1% (separate ad sets, shared campaign budget)
- Ad format: Short-form video (15–30 seconds; hook in first 3 seconds is critical)
- Content angle: Category education — name the problem your ICP has, not your product. Frame the cost of inaction.
- CTA: "Learn More" → ungated blog post or thought leadership content (not demo request — too early)
- Budget: 20% of total monthly spend
- Frequency cap: 2 impressions per person per week (Meta default — adjust if budget is high)
- Primary KPI: 3-second video view rate >35%, ThruPlay rate >15%, CPM <$12 (Meta CPMs are significantly lower than LinkedIn)
- Secondary goal: Build Video Engagement Custom Audiences for mid-funnel retargeting

B) CONTENT ENGAGEMENT CAMPAIGN (Warm — Website Custom Audiences + Content Retargeting):
- Objective: Traffic or Engagement
- Audience:
  - Ad Set 1: All site visitors 90 days (EXCLUDE: pricing/demo page visitors — they belong in higher-intent campaigns)
  - Ad Set 2: Blog readers + case study viewers 90 days
  - Ad Set 3: Video viewers — 50%+ of awareness video (retargeting from Campaign A)
- Ad format: Single Image or Carousel (3–4 frames: problem → insight → customer proof → CTA)
- Content angle: Proof and education — customer outcome data, benchmark statistics, "5 signs you need [category]" listicle
- CTA: "Download" to gated asset (checklist, ROI calculator, benchmark report) — collect email for CRM and Meta Custom Audience sync
- Budget: 25% of total monthly spend
- Primary KPI: Link click CTR >1.2%, Cost per landing page view <$3, Lead form completion rate >18%

C) DEMO/TRIAL CONVERSION CAMPAIGN (High-Intent — Bottom-Funnel Retargeting):
- Objective: Leads (Meta Lead Ad) or Sales (Website Conversions)
- Audience:
  - Ad Set 1: Pricing page visitors (30 days) — HIGHEST intent; allocate 40% of this campaign budget
  - Ad Set 2: Demo page non-converters (14 days)
  - Ad Set 3: Competitor comparison page visitors (30 days)
  - Ad Set 4: MQL/SQL stalled contacts (CRM upload)
- Ad format: Single Image with instant Lead Form OR carousel that leads to a landing page
- Lead Form Design (if using Meta Lead Ads):
  - Form type: "Higher Intent" (adds a review step before submission — improves lead quality at slight cost to volume)
  - Intro screen: "Book a 20-minute personalized demo — see [Your Product] on your real [use case]"
  - Questions: First name (pre-fill), Last name (pre-fill), Work email (pre-fill), Company name (pre-fill), Job title (custom question — dropdown for qualification)
  - Context card: 3 bullet points on what happens after submission
  - Thank-you screen: Confirmation message + calendar booking link (Calendly/Chili Piper embed)
- Content angle: Risk removal — ROI proof, peer validation, trial offer, implementation guarantee
- CTA: "Book a Demo" or "Start Free Trial"
- Budget: 40% of total monthly spend (this is your revenue-generating campaign; it should dominate spend)
- Primary KPI: Cost per Lead (target: $[X]); Lead-to-MQL rate >35%; Demo-to-SQL rate tracking

D) ABM NAMED ACCOUNT CAMPAIGN (Account-Based — CRM List + Lookalike):
- Objective: Traffic or Leads
- Audience: Upload CRM named account contact list → Meta Custom Audience (email + phone match). Layer with behavioral qualifiers if audience is too broad.
- Note: Unlike LinkedIn's company-level targeting, Meta matches at the contact level. If your named account list has contacts from each account, this works well. If not, upload decision-maker email lists purchased from ZoomInfo/Apollo.
- Ad format: Single Image (personalized by industry or company segment if running <100 target accounts; generalized by persona for 100+ accounts)
- Content angle: Account-specific pain points; reference industry, company size, or role-specific outcomes
- CTA: "See How [Industry] Teams Use [Product]" → case study or demo
- Budget: 10% of total monthly spend (higher CPL acceptable — strategic accounts)
- Primary KPI: Account reach % (% of target contacts served at least 1 impression), lead quality score

E) WIN-BACK & CHURNED CUSTOMER RE-ENGAGEMENT CAMPAIGN:
- Objective: Leads or Traffic
- Audience: Churned customer CRM list (6–18 months post-churn) + Trial users who never converted (90+ days ago)
- Ad format: Single Image or short video
- Content angle: "What's changed" — highlight product improvements, new features, customer milestones since they left. Offer: "Free migration back" or "No-commitment re-evaluation call"
- CTA: "See What's New" → Product changelog landing page + embedded demo booking
- Budget: 5% of total monthly spend
- Primary KPI: CPL (expect lower than cold; these are warm-to-product audiences)

---

DELIVERABLE 3 — CREATIVE FRAMEWORK:

For each campaign, produce 2–3 ad variations:

META AD CREATIVE STRUCTURE — B2B SaaS FORMULA:

AD VARIATION [#] — Format: [Video / Single Image / Carousel / Lead Ad]
Campaign: [Name]
Funnel Stage: [TOF / MOF / BOF]
Placement: Facebook Feed, Instagram Feed, Instagram Stories (adjust creative dimensions per placement)

VIDEO AD FRAMEWORK (TOF — 15-30 seconds):

HOOK (First 3 seconds — text overlay + visual + voiceover): Must stop the scroll. No company name. No logo. Lead with the pain.
Example: "Most [job role] are wasting 40% of their budget without knowing it."

PROBLEM (Seconds 4–10): Expand the pain. Use specifics. Industry data, failure story framing, or contrarian insight.
Example: "They're running paid campaigns with no idea which channels actually drove pipeline. Their attribution is broken, and finance is about to cut their budget."

SOLUTION FRAME (Seconds 11–22): Introduce the category or approach — not the product name. Let the solution click first.
Example: "Revenue-attributed marketing means every dollar is tied to a closed deal. The companies doing it are growing 2x faster."

BRAND REVEAL + CTA (Seconds 23–30): Product name + simple CTA.
Example: "[Product] makes revenue attribution automatic. Book a 20-minute demo." CTA button: "Learn More"

TEXT OVERLAY: Always include captions — 85% of Facebook videos are watched on mute.
Thumbnail: Frame that reads well without sound (compelling text overlay, not just a person's face)

---

SINGLE IMAGE AD FRAMEWORK (MOF/BOF):

PRIMARY TEXT (125 chars visible before "more" on mobile — lead with value):
[Hook line — problem statement, provocative stat, or bold claim. No "Are you looking for…" opener.]

FULL BODY TEXT (visible after "more" — 300–600 chars):
[Expand on hook. Social proof element: specific company/outcome. Risk-removal element. CTA direction.]

HEADLINE (below image — 27 chars shown on mobile; 40 on desktop):
[Direct value statement or offer]

DESCRIPTION (optional — shown on desktop):
[One-sentence elaboration or urgency element]

CTA BUTTON: [Learn More / Book Now / Download / Get Quote / Sign Up]

IMAGE SPECIFICATIONS:
- Single image: 1200 × 628px (Facebook Feed) — 1080 × 1080px (Instagram square)
- Stories: 1080 × 1920px (keep text within middle 60% of frame — safe zone for UI elements)
- Creative guidelines: Use high-contrast backgrounds, bold text overlays for scroll-stopping, real product UI screenshots or customer faces (authentic > polished stock)
- Avoid: Blue/white color schemes (blends into Facebook UI); generic stock photos of people smiling at laptops

PSYCHOLOGICAL PRINCIPLES TO APPLY (choose 2–3 per ad):
- Social proof: "[X] companies" or "[customer name]" with specific outcome — avoid vague claims
- Loss aversion: Frame the cost of inaction ("Every month without [solution] costs the average team $[X]")
- Specificity: Exact numbers ("47% faster ramp," "$2.1M ARR influenced") outperform vague claims ("faster," "more revenue")
- Authority: Analyst quotes, review site ratings ("4.8/5 on G2 — 480 reviews"), category leader claims
- Urgency/scarcity: Use sparingly in B2B — "Q3 cohort spots" or "Limited seats" for events/workshops only

---

CAROUSEL AD FRAMEWORK (MOF — Proof-Led):

CARD 1 (Hook): Problem statement image — "Is [painful status quo] holding your team back?"
CARD 2 (Context): Statistic or industry insight that validates the problem
CARD 3 (Solution): "[Product] gives [ICP] [specific capability] without [painful alternative]"
CARD 4 (Proof): "[Customer Logo] — [specific outcome in 90 days]"
CARD 5 (CTA): "See it in action — book a 20-min demo" → landing page or Lead Ad form

Carousel rules:
- Each card must be readable as a standalone image (some users skip cards)
- Use a consistent visual style across all cards; don't treat each card as a separate design
- CTA card: Highest contrast, clearest text, singular action

---

DELIVERABLE 4 — META ADVANTAGE+ VS. MANUAL CAMPAIGN DECISION FRAMEWORK:

META BIDDING AND AUTOMATION PHILOSOPHY:
Meta's AI (Advantage+) is powerful but requires significant conversion data to optimize properly. Use this framework to decide when to automate vs. control manually.

| Scenario | Recommended Approach | Rationale |
|---|---|---|
| New account — <50 conversions/month | Manual Campaigns — broad audiences | Advantage+ needs data to learn; without it, it spends on the wrong users |
| Account with >50 demo requests/month | Advantage+ Shopping Campaigns (ASC) or Advantage+ App Campaigns | Let Meta find converters autonomously |
| Retargeting small custom audiences (<5,000) | Manual Campaigns — manual CPM/CPC bidding | Advantage+ often expands audience beyond your retargeting pool |
| Lookalike audiences (cold prospecting) | Advantage+ Campaign Budget (ACB) with Advantage+ Audience | Let Meta optimize across lookalike percentages |
| ABM named account campaigns | Manual Campaigns only — do NOT enable Advantage+ Audience | You must control who sees these ads precisely |

BIDDING STRATEGY BY CAMPAIGN:
| Campaign | Objective | Bidding | Starting Budget | Optimization |
|---|---|---|---|---|
| Brand Awareness — Lookalike | Video Views | Lowest cost (auto) | $[X]/day | ThruPlay (15-sec views) |
| Content Engagement — Retargeting | Traffic | Lowest cost → Cost cap once CPL data available | $[X]/day | Landing page views |
| Demo/Trial Conversion — High Intent | Leads or Conversions | Cost cap at $[1.5x target CPL] initially; tighten after 50 events | $[X]/day | Lead form submits or demo request conversions |
| ABM Named Accounts | Reach | Lowest cost | $[X]/day | Reach + frequency |
| Win-Back | Leads | Lowest cost | $[X]/day | Leads |

BUDGET ALLOCATION MATRIX:
| Campaign | Monthly Budget | % of Total | Expected Leads | Target CPL |
|---|---|---|---|---|
| Brand Awareness | $X | 20% | — (pipeline influence) | CPM-based |
| Content Engagement | $X | 25% | X | $[X] |
| Demo/Trial Conversion | $X | 40% | X | $[X] |
| ABM Named Accounts | $X | 10% | X | $[X + premium] |
| Win-Back / Re-engagement | $X | 5% | X | $[X - 30%] |
| **TOTAL** | **$X** | **100%** | **X leads/month** | **$[blended CPL]** |

PIPELINE MATH:
- Total leads at blended CPL: [budget] ÷ [CPL] = [X leads/month]
- Meta Lead-to-MQL rate: [X]% (Meta leads typically require faster SDR follow-up to qualify — within 5 minutes ideal)
- MQL-to-SQL rate: [X]% → [Y SQLs/month]
- SQL-to-close rate: [X]% → [Z closed/month]
- ACV: $[X] → [Z × ACV = $X pipeline created/month]

NOTE ON META vs. LINKEDIN CPL: Meta CPL for B2B SaaS is typically 30–50% lower than LinkedIn, but lead quality is also lower on cold audiences. Compensate with faster SDR response time, stronger lead qualification forms, and higher-intent retargeting audience allocation.

---

DELIVERABLE 5 — CONVERSIONS API (CAPI) + PIXEL TRACKING SETUP:

WHY CAPI IS MANDATORY FOR B2B SAAS IN 2025+:
iOS 14+ privacy changes, browser-based ad blocking, and cookie restrictions have degraded browser-only pixel tracking by 20–40%. Meta's Conversions API sends conversion events server-side (directly from your CRM or web server) — bypassing browser limitations and recovering lost attribution.

IMPLEMENTATION APPROACH:

Option A — Direct CRM Integration (Recommended):
- HubSpot: Enable native Meta Ads integration (Settings → Marketing → Ads → Connect Account). HubSpot automatically sends server-side conversion events via CAPI when form submissions, deals, or lifecycle stage changes occur.
- Salesforce: Use Meta's official Salesforce connector or implement via Zapier → Meta Conversions API.

Option B — Server-Side via Google Tag Manager Server Container:
- Deploy GTM Server-Side container on your domain (e.g., gtm.yourdomain.com)
- Route all Meta pixel events through server container → Meta CAPI
- Recommended for teams with engineering resources; eliminates browser-side tracking entirely

Option C — Zapier/Make.com (No-Code):
- Trigger: CRM form submission → Zapier → Meta Conversions API → log as "Lead" event
- Trigger: CRM opportunity reaches SQL stage → Zapier → Meta Conversions API → log as "Purchase" event (use deal value as revenue signal)

CONVERSION EVENTS TO TRACK:
| Event Name | Trigger | Meta Event Type | Value |
|---|---|---|---|
| Demo Request | Thank-you page load or form submit | Lead | $[estimated pipeline value per demo] |
| Free Trial Signup | Trial confirmation page | CompleteRegistration | $[LTV estimate] |
| Pricing Page View | /pricing page load | ViewContent | $0 (micro-conversion) |
| Content Download | Gated asset thank-you page | Lead | $[content-attributed pipeline value] |
| MQL Reached | CRM lifecycle stage change (server-side via CAPI) | Lead (qualified) | $[ACV × MQL-to-close rate] |
| Closed Won | CRM deal closed (server-side via CAPI) | Purchase | $[actual deal value] |

UTM PARAMETER STRUCTURE:
`utm_source=facebook&utm_medium=paid-social&utm_campaign=[campaign_name]&utm_content=[ad_set_name]&utm_term=[ad_name]`

Meta auto-appends `fbclid` parameter — ensure your CRM captures and stores this for cross-device attribution.

CRM ATTRIBUTION MAPPING:
- Lead Source = "Meta Ads" — set on all contacts originating from Meta campaigns
- Campaign property = {{utm_campaign}} — store campaign name for multi-touch reporting
- fbclid storage: Capture in HubSpot custom property or Salesforce field for Meta's Conversions API deduplication

DEDUPLICATION STRATEGY (prevents double-counting browser + server events):
- Event ID: Generate a unique event_id for each conversion (UUID). Send same event_id from both browser pixel and CAPI → Meta deduplicates automatically.
- Event time: Must match within 7 days for CAPI events to be accepted.

---

DELIVERABLE 6 — META + LINKEDIN ORCHESTRATION ARCHITECTURE:

Meta and LinkedIn are complementary paid social channels — not alternatives. Use this orchestration model:

PHASE 1 — AWARENESS (LinkedIn leads, Meta reinforces):
- LinkedIn Sponsored Content: Professional-context awareness to cold ICP by job title
- Meta Awareness: Retarget website visitors from LinkedIn clicks within 24–48 hours with Meta ads (lower CPM = efficient reinforcement)
- Goal: 3–5 touchpoints before demo request ask; Meta's lower CPM makes frequency cost-efficient

PHASE 2 — CONSIDERATION (Meta nurtures, LinkedIn converts):
- Meta Mid-Funnel: Serve content engagement ads to website visitors (blog readers, case study viewers) — Meta's retargeting is precise and cost-efficient here
- LinkedIn Lead Gen: Run demo conversion campaigns simultaneously to same audience on LinkedIn (professional context increases demo show rates)
- Audience sync: Export email list of Meta lead form submitters → upload to LinkedIn Matched Audiences → LinkedIn follow-up sequence

PHASE 3 — CONVERSION (Both channels reinforce):
- Meta: Serve demo offer to pricing page visitors (high-intent retargeting)
- LinkedIn: Serve Conversation Ad to same pricing page visitors (professional context, higher CPL but higher quality)
- Combined signal: If a prospect clicks both Meta and LinkedIn conversion ads, flag in CRM for priority SDR outreach — multi-channel engagement signals strong intent

AUDIENCE SYNC WORKFLOW:
1. Meta lead form submit → Zapier → HubSpot/Salesforce contact created with utm_source=facebook
2. HubSpot workflow → 5-minute SDR alert → email + Slack notification
3. HubSpot workflow → Add to LinkedIn Matched Audience (via CSV export or HubSpot LinkedIn integration) → LinkedIn follow-up campaign begins
4. If no demo booked in 7 days → Meta retargeting campaign with softer offer (webinar, case study)

---

DELIVERABLE 7 — 90-DAY LAUNCH ROADMAP:

WEEKS 1–2 (Foundation):
- Install Meta Pixel on all pages (via Google Tag Manager) — verify firing with Meta Pixel Helper
- Implement Conversions API via CAPI Gateway or CRM integration
- Create all Website Custom Audiences (they need time to populate — start building now)
- Upload CRM customer list and generate Closed-Won Customer Lookalike 1%
- Launch Brand Awareness campaign (Lookalike targeting) — start generating video engagement audiences
- Launch Demo/Trial Conversion campaign targeting any existing pricing/demo page visitors

WEEKS 3–4 (Full Launch):
- Launch Content Engagement campaign targeting video viewers from Week 1–2 awareness campaign
- Upload ABM named account list to Meta Custom Audience (wait 24–48 hours for matching)
- Launch ABM Named Account campaign with personalized creative
- Begin A/B test: two video hook variations for awareness campaign
- Set up Zapier automation: Meta Lead form → CRM contact creation → SDR alert (target <5-minute response)

MONTH 2 (Optimization):
- Review: Lead quality score by campaign — if Meta leads have <30% MQL rate, add qualification question to Lead form
- Review: CPL trend by audience — shift budget from underperformers to top-converting audiences
- Launch Win-Back campaign to churned customer list
- Test Advantage+ Shopping Campaign (ASC) if demo conversion campaign has >50 events/month
- Rotate creative: Refresh video hooks for awareness campaign; test carousel vs. single image for MOF

MONTH 3 (Scale + Attribution):
- Activate CAPI offline conversion import: push Closed-Won deal values back to Meta for ROAS measurement
- Build Meta Attribution Report: compare Meta-reported conversions vs. CRM-reported conversions (expect 15–30% discrepancy — trust CRM as source of truth)
- Launch LinkedIn + Meta orchestration workflow (audience sync between platforms)
- Expand Lookalike Audiences from 1% to 2% for top-performing campaigns to scale volume
- Test Instagram Stories creative format (often 30–40% lower CPL for B2B retargeting vs. Facebook Feed)

CREATIVE REFRESH SCHEDULE:
- Awareness (video): Every 3–4 weeks (video frequency fatigue is faster than static images; monitor 3-second view rate drop)
- Conversion (single image): Every 5–6 weeks or when CTR drops >25% from peak
- Lead Ads: Test new headline and intro text every 30 days; form questions can stay stable

---

## Example Input/Output

**Input Example:**
Product: Nexus — AI-powered customer success and churn prevention platform for B2B SaaS companies
ICP: VP of Customer Success, Director of Customer Experience, Chief Customer Officer at B2B SaaS companies, 100–2,000 employees, $5M–$200M ARR
ACV: $42,000
Sales cycle: 45 days
Target CPL: $180
Monthly budget: $14,000
Competitors: Gainsight, ChurnZero, Totango
CRM contacts: 4,200 total (customers: 380, MQLs/SQLs: 1,800, churned: 210, open opps: 340)
Website visitors: 9,500/month
Primary conversions: Demo request, free trial
Geographic focus: US + Canada

**Output Example (excerpt):**

---
**AUDIENCE ARCHITECTURE**

Closed-Won Customer Lookalike:
- Source: 380 customer contacts (email + phone) → upload to Meta Custom Audiences
- Lookalike: 1% US + Canada → estimated reach: 280,000 people
- Budget allocation: 55% of Brand Awareness campaign spend

MQL/SQL Lookalike:
- Source: 1,800 MQL+ contacts from CRM
- Lookalike: 1% US + Canada → estimated reach: 420,000 people
- Budget allocation: 45% of Brand Awareness campaign spend

Pricing Page Retargeting:
- Audience: /pricing URL, 30-day lookback → estimated 760 visitors/month
- Priority: Highest intent audience — allocate 40% of conversion campaign budget
- Suppression: Exclude 380 customers (CRM upload)

Demo Page Non-Converters:
- Audience: /demo URL visited, 14-day lookback — EXCLUDE: /demo/thank-you page (already converted)
- Estimated: 190 visitors/month
- Budget: 30% of conversion campaign budget

**CAMPAIGN BUDGET TABLE:**

| Campaign | Monthly Budget | Expected Leads | Target CPL |
|---|---|---|---|
| Brand Awareness — Lookalike | $2,800 | — | CPM <$9 |
| Content Engagement — Retargeting | $3,500 | 28 leads | $125 |
| Demo Conversion — High Intent | $5,600 | 42 leads | $133 |
| ABM Named Accounts (340 open opps) | $1,400 | 8 leads | $175 |
| Win-Back — 210 Churned | $700 | 5 leads | $140 |
| **TOTAL** | **$14,000** | **~83 leads/mo** | **$169 blended CPL** |

**PIPELINE MATH:**
- 83 leads/month at $169 CPL
- Meta Lead-to-MQL rate: 38% → 31.5 MQLs/month
- MQL-to-SQL rate: 45% → 14.2 SQLs/month
- SQL-to-close rate: 28% → 3.97 closed deals/month
- ACV: $42,000 → **$166,740 net new ARR/month from Meta Ads**
- Meta ROAS: $166,740 ÷ $14,000 = **11.9x pipeline return**

---
**SAMPLE AD COPY — Demo Conversion Campaign:**

**Primary Text (hook — first 125 chars):**
"57% of SaaS companies lose a customer before their CS team even knows there's a problem."

**Body Text:**
Nexus surfaces churn risk signals 45 days before the typical warning signs appear — health score drops, feature abandonment, executive ghosting.

380 SaaS CS teams use Nexus to catch and close at-risk accounts before the renewal conversation gets awkward.

Book a 20-minute demo. We'll show you your churn risk profile on a live account.

**Headline:** Predict Churn 45 Days Earlier — See How
**CTA Button:** Book a Demo

**Psychological principles applied:**
- Specificity: "57%", "45 days before", "380 CS teams" — specific numbers are 3x more persuasive than vague claims
- Loss aversion: The framing is about what the prospect is *losing* (customers they don't know are at risk) — higher emotional activation than feature benefit framing
- Risk removal: "We'll show you your churn risk profile on a live account" — the demo itself delivers value, reducing fear of wasted time

---

## Success Metrics

**Weeks 1–2 (Launch Validation):**
- Pixel firing on all pages: verified via Meta Pixel Helper browser extension
- CAPI events receiving: verified via Events Manager → Test Events tool (look for server event match quality score >6/10)
- Custom Audiences populating: Pricing Page audience should show 300+ people within 7 days if site traffic > 1,000 visitors/month
- CPM awareness campaigns: <$15 (Meta B2B CPMs run $8–20 depending on audience size and competition)

**Month 1 Benchmarks:**
- Video 3-second view rate (awareness): >30%
- Video ThruPlay rate (15+ seconds): >15%
- Lead Ad form completion rate: >12% (Meta benchmark for B2B lead ads; "Higher Intent" form type: 8–12%)
- Demo conversion CPL: within 50% of target (Meta takes 2–4 weeks to exit Learning Phase — minimum 50 optimization events needed)
- Lead-to-MQL rate: >30% (lower than LinkedIn due to weaker professional targeting — acceptable; compensate with SDR speed)

**Month 3 (Optimization Maturity):**
- CPL trend: declining 15–25% from Month 1 as audience learning and CAPI signal improve
- Lookalike audience performance: Closed-Won Lookalike CPL should outperform MQL Lookalike by 20–30%
- CAPI match quality score: >7/10 in Events Manager (indicates strong data matching between Meta and CRM)
- Creative fatigue signal: 3-second video view rate drops >30% from peak → refresh hook

**Revenue Attribution:**
- Pipeline influenced by Meta Ads: tracked via CRM utm_source=facebook lead source
- Closed-won ARR from Meta leads: CRM reporting — filter by Lead Source = "Meta Ads," stage = Closed Won
- True ROAS: Push Closed-Won deal values back to Meta via CAPI offline conversions → Meta Ads Manager shows revenue-level ROAS (not just CPL)
- Multi-touch influenced pipeline: Accounts that interacted with both Meta and LinkedIn ads → flag in CRM → measure win rate vs. single-channel

## Related Prompts
- [`AI-Powered-B2B-SaaS-LinkedIn-Ads-Campaign-Architecture-&-Pipeline-Attributed-Paid-Social-Revenue-Intelligence-Engine.md`](AI-Powered-B2B-SaaS-LinkedIn-Ads-Campaign-Architecture-&-Pipeline-Attributed-Paid-Social-Revenue-Intelligence-Engine.md) — Pair Meta retargeting efficiency with LinkedIn's professional targeting precision for full paid social coverage
- [`AI-Powered-B2B-SaaS-Google-Ads-Campaign-Architecture-&-Paid-Search-Revenue-Intelligence-Engine.md`](AI-Powered-B2B-SaaS-Google-Ads-Campaign-Architecture-&-Paid-Search-Revenue-Intelligence-Engine.md) — Capture high-intent search demand from Meta-warmed audiences with Google Ads demand capture
- [`../../04_Demand-&-Lead-Generation-&-Growth/Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Paid-Media-Landing-Page-Architecture-&-Campaign-Conversion-Optimization-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Paid-Media-Landing-Page-Architecture-&-Campaign-Conversion-Optimization-Intelligence-Engine.md) — Optimize landing pages receiving traffic from Meta campaigns that send to website vs. Lead Ads
- [`../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/AI-Powered-Email-Audience-Sync-&-Paid-Media-Retargeting-Orchestration-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/AI-Powered-Email-Audience-Sync-&-Paid-Media-Retargeting-Orchestration-Intelligence-Engine.md) — Sync CRM email lists to Meta Custom Audiences for coordinated email + Meta retargeting sequences

## Integration Tips

**Meta Marketing API / AI Agent Execution:**
- Use Meta Marketing API (Graph API v20.0+) to programmatically create campaigns, ad sets, ads, and Lead Ad forms from this output
- Audience creation: `POST /act_{ad_account_id}/customaudiences` with `subtype=LOOKALIKE` or `subtype=CUSTOM`
- Campaign creation: `POST /act_{ad_account_id}/campaigns` with `objective=LEAD_GENERATION` or `CONVERSIONS`
- Lead Ad form: `POST /{page_id}/leadgen_forms` with questions array
- Webhook setup: Subscribe to `leadgen` webhook on your Facebook Page to receive real-time lead notifications without polling
- MCP integration: Use Meta's official Marketing API MCP server for AI agent access to campaign management

**HubSpot Integration:**
- Enable native Meta Ads integration: HubSpot Settings → Marketing → Ads → Connect Meta Account
- Sync: Lead Ad form submissions auto-create HubSpot contacts (real-time; no Zapier needed)
- Map fields: Work email → Email, Company → Company Name, Job Title → Job Title
- Lead Source automation: HubSpot workflow → set "Lead Source = Meta Ads" + "utm_campaign = {{utm_campaign}}" on all Meta-sourced contacts
- Nurture sequence: Enroll Meta leads in high-velocity nurture sequence immediately — Meta leads have 3–5x lower 7-day follow-up window than inbound leads before intent cools
- UTM tracking: `utm_source=facebook&utm_medium=paid-social&utm_campaign={{campaign.name}}`

**Salesforce Integration:**
- Use Zapier: Meta Lead Ad submit → Zapier → Salesforce Lead created (map all Lead Ad fields to Salesforce Lead fields)
- Alternatively: HubSpot as middleware — Meta → HubSpot → Salesforce (if using bidirectional HubSpot-Salesforce sync)
- Campaign influence: Create Salesforce Campaign for each Meta campaign → use Campaign Member object to track influenced contacts → report on pipeline influenced by Meta across funnel stages
- CAPI closed-loop: When Salesforce deal closes (Closed Won stage), trigger CAPI event with Opportunity Amount as `value` parameter → Meta Ads Manager shows closed ARR per campaign

**Zapier Automations:**
- Trigger: New Meta Lead Ad submission → Create CRM contact + enroll in "Meta Demo Request" nurture sequence + Slack alert to SDR with lead details (name, email, company, job title) — target <5 minutes response time
- Trigger: Meta lead scores as MQL in CRM → Pause Meta retargeting ads to that contact (prevent wasted impressions on already-engaged lead) + assign to SDR
- Trigger: CRM deal closes (Closed Won, utm_source=facebook) → Send CAPI Purchase event to Meta with deal value → feeds Meta's ROAS reporting
- Trigger: Meta campaign CPL exceeds target by 40% for 3 consecutive days → Slack alert to demand gen manager with campaign name + current CPL + budget spent

**Notion / Airtable Creative Tracker:**
- Log each ad variation: campaign, audience type, hook text, format, launch date, 3-second view rate, CTR, CPL, lead volume
- Track creative fatigue: alert when 3-second view rate drops 30% from launch peak → trigger creative refresh
- A/B test log: Document winning hooks, image styles, and CTA button text for cross-campaign creative intelligence

## Troubleshooting

**Problem: Meta Lead Ads generating high volume but very low MQL rate (<20%) — leads are poor quality**
Solution: Three root causes. First, the form has too little friction — switch from "More Volume" form type to "Higher Intent" (adds a review step and confirmation screen before submission; reduces volume ~30% but improves quality significantly). Second, add one qualifying custom question — a dropdown with 2–3 options such as "Team size" or "Current tool you use for [use case]" — this reduces completions but surfaces buyer intent. Third, the audience targeting is too broad — if you're running cold interest-based audiences, shift budget to Lookalike 1% from Closed-Won customers and Website Custom Audiences (pricing/demo page visitors). Meta lead quality is a direct function of audience precision.

**Problem: Campaigns stuck in "Learning Phase" indefinitely — Meta shows low delivery and CPL is inconsistent**
Solution: Meta's Learning Phase requires 50 optimization events per ad set per week to exit. For B2B SaaS with low conversion volume, this is the most common failure mode. Solutions: (1) Switch optimization event from "Demo Request" to a higher-volume micro-conversion like "Pricing Page View" or "Content Download" — once you hit 50 events/week on the micro-conversion, create a separate Conversion campaign for the demo request; (2) Consolidate ad sets — fewer, larger ad sets exit Learning Phase faster than many small targeted ones; (3) Increase daily budget — the minimum viable budget for a Conversions campaign to exit Learning Phase is approximately $50–100/day per ad set; below this, delivery is throttled.

**Problem: CAPI event match quality score is below 6 — attribution is unreliable and Meta can't optimize toward your best customers**
Solution: Event Match Quality (EMQ) score measures how well Meta can match your CAPI events to Meta user accounts. To improve it: (1) Send as many customer data parameters as possible — email, phone number, first name, last name, city, state, zip code, country, and `fbclid` (the Facebook Click ID appended to URLs) together improve match rate dramatically; (2) Hash all parameters client-side using SHA-256 before sending — Meta requires hashed PII; (3) Capture `fbclid` in your CRM when a user arrives from a Meta ad (store as a cookie + CRM field) and pass it back in your CAPI events — this is the single highest-impact EMQ improvement; (4) Verify via Events Manager → Overview → Web Events → select event → Event Match Quality column — target score of 7+ for reliable attribution.

## Version History
- v1.0: Initial creation (auto-generated)
