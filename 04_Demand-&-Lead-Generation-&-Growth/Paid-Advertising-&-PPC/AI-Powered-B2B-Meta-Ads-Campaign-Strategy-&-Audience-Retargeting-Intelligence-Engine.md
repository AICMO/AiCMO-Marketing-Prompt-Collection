# AI-Powered B2B Meta Ads Campaign Strategy & Audience Retargeting Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** b2b, meta-ads, facebook-ads, paid-social, retargeting, demand-gen, lookalike-audiences, pipeline, automation

## Overview
Builds a complete, execution-ready B2B Meta Ads (Facebook + Instagram) campaign architecture — from cold audience targeting and retargeting strategy to creative formats, bidding logic, and pipeline attribution — designed to maximize ROI at every funnel stage. Use this when launching a Meta Ads demand generation program, scaling retargeting to convert high-intent website visitors, or building a full-funnel paid social strategy that complements LinkedIn and Google Ads.

## Quick Copy-Paste Version

You are a senior B2B paid social strategist. Build a complete Meta Ads campaign strategy for a B2B SaaS company.

Company: [Your Company] — [one-line description of what you do]
Target buyers: [Job titles, e.g., VP of Marketing, Head of Operations, CFO]
ICP firmographics: [Company size, industry, geography, e.g., 100-1000 employee SaaS companies, North America]
Monthly Meta Ads budget: $[X]
Primary conversion goal: [Demo request / Gated content download / Webinar registration / Free trial]
Top competitors: [Competitor 1, Competitor 2, Competitor 3]
Pixel status: [Not installed / Installed but no conversion events / Fully instrumented]
CRM/MAP: [HubSpot / Salesforce+Marketo / other]

Deliver the following, ready to implement in Meta Ads Manager:

1. CAMPAIGN ARCHITECTURE
   - 3-5 campaigns with objective, format, and budget allocation
   - Recommended campaign objectives (Awareness / Traffic / Engagement / Lead Generation / Conversions)
   - Budget split across funnel stages (TOFU/MOFU/BOFU)
   - Advantage+ Campaign Budget (ACB) vs. manual budget allocation recommendation

2. AUDIENCE TARGETING STRATEGY (per campaign)
   - Cold audiences: interest + behavior targeting for B2B buyers
   - Custom Audiences: website retargeting segments (all visitors, product page, pricing page by recency)
   - Customer list upload: email match strategy, lookalike audience construction
   - Lookalike audiences: which seed audience to use and at what percentage (1-3% vs. 5-10%)
   - Audience exclusions: existing customers, current opportunities, low-intent bounces

3. AD FORMATS & CREATIVE STRATEGY
   - Recommended ad format per campaign (Single Image, Carousel, Video, Lead Ad, Instant Experience)
   - 3 complete ad variants per campaign (primary text 125 chars, headline 40 chars, description 30 chars, CTA)
   - Creative testing matrix: which variables to A/B test first
   - Video creative brief for a 15-second and 30-second cut

4. META LEAD ADS STRATEGY (if applicable)
   - Form type: More Volume vs. Higher Intent
   - Field recommendations and custom qualifying questions
   - Instant form vs. website landing page decision logic
   - CRM integration instructions (native HubSpot/Salesforce connection or Zapier)

5. BIDDING & OPTIMIZATION STRATEGY
   - Recommended bid strategy per campaign (Highest Volume / Cost Cap / Bid Cap / Value Optimization)
   - Estimated CPM, CPC, and CPL benchmarks for B2B on Meta
   - Learning phase management: what not to change in the first 7-14 days
   - Optimization triggers (pause/scale/test rules) after learning phase exits

6. ATTRIBUTION & MEASUREMENT
   - Meta Pixel + Conversions API (CAPI) setup checklist
   - Conversion events to track and value assignments
   - Attribution window selection: 1-day click / 7-day click / 1-day view
   - How to connect Meta pipeline data to CRM opportunity reporting
   - Self-reported attribution question placement

Format as a structured Meta Ads Manager implementation plan with clear section headers. Every ad must be complete and copy-paste ready.

## Advanced Customizable Version

ROLE: You are a senior B2B paid social strategist with 12+ years running Meta Ads for SaaS, fintech, professional services, and enterprise software companies. You understand that Meta is primarily a retargeting and nurture channel for B2B — not a primary demand creation channel like LinkedIn — and you build strategies accordingly. You combine deep Meta Ads Manager expertise with first-party data strategy, creative psychology, and multi-touch attribution to prove Meta's pipeline contribution to CFOs and CMOs who are skeptical of social spend.

COMPANY CONTEXT:
- Company name and one-line description: [e.g., "Helios HR — AI-powered workforce planning platform for mid-market People Ops teams"]
- Product category: [e.g., HR tech, fintech, cybersecurity, marketing automation, RevOps]
- Primary ICP: [e.g., Chief People Officers and VPs of HR at 200-2000 employee companies in technology and professional services]
- Secondary ICP (if any): [e.g., HR Directors and Talent Acquisition Leaders at same firmographic]
- Geography: [e.g., US + Canada, EMEA, APAC]
- Monthly Meta Ads budget: $[X] (note if new account or existing)
- Sales cycle length: [e.g., 2-4 months, 3-6 stakeholders]
- Average contract value (ACV): $[X]
- Primary conversion goal: [Demo request / Free trial / Gated asset / Webinar / Contact sales]
- CRM: [HubSpot / Salesforce / other]
- Marketing automation: [Marketo / HubSpot / Pardot / other]
- Top 3 competitors: [names]
- Key differentiator vs. competitors: [1-2 sentences]
- Existing content assets: [e.g., case studies, ROI calculator, analyst report, product demo video]
- Meta Pixel status: [Not installed / Installed, no events / Installed with standard events / Full CAPI implementation]
- Monthly website visitors: [X] (critical for sizing retargeting audiences)
- Email list size in CRM: [X contacts] (for custom audience and lookalike construction)
- Current Meta Ads status: [New account / Existing account with $X/mo spend / Scaling from proven campaigns]

CAMPAIGN ARCHITECTURE REQUIREMENTS:
Design a full-funnel Meta Ads structure with the following specifications:

1. STRATEGIC ROLE OF META IN B2B PAID MIX
   Before building the campaign structure, define Meta's strategic role:
   - Primary use case for this company (retargeting, brand awareness, lookalike prospecting, or all three)
   - How Meta Ads complements LinkedIn Ads (demand creation) and Google Ads (demand capture)
   - Expected pipeline contribution vs. LinkedIn and Google: realistic benchmarks for B2B on Meta
   - Why Meta works for B2B despite B2C reputation: buyers are humans who use Facebook/Instagram outside work
   - When Meta Ads should NOT be the primary B2B paid channel (explain the conditions)

2. CAMPAIGN STRUCTURE & BUDGET ALLOCATION
   Build 4-6 campaigns organized by funnel stage and audience temperature:

   For each campaign provide:
   - Campaign name convention (include funnel stage, audience type, and objective in name)
   - Campaign objective selection with rationale (Awareness / Traffic / Engagement / Leads / Conversions / Catalog Sales)
   - Ad set count and why (1-3 ad sets per campaign to avoid audience overlap)
   - Daily or lifetime budget with rationale
   - Advantage+ Campaign Budget: when to use vs. manual ad set budgets
   - Success KPI and threshold for scaling vs. pausing

   Recommended campaign split (adjust for budget and pixel data volume):
   - TOFU Prospecting — Cold Lookalike + Interest: 20-25% of budget
   - MOFU Retargeting — Engaged Non-Converters: 35-40% of budget
   - BOFU Retargeting — High-Intent Converters: 30-35% of budget
   - Retention/Expansion — Customer Lookalike Upsell: 5-10% of budget (if ACV supports)

3. AUDIENCE ARCHITECTURE (build all targeting in detail)

   COLD AUDIENCES (for TOFU when retargeting pool is small):
   - Interest targeting clusters: 5-8 B2B-relevant interest categories with size estimates
   - Behavioral targeting: business decision maker behaviors Meta tracks (note: significantly reduced post-iOS 14)
   - Job title targeting via Meta's "Detailed Targeting" (limited but available): specify exact options
   - Why to layer interests + behaviors vs. broad targeting with Advantage+ Audience
   - Lookalike seed strategy (see below) — cold lookalikes outperform interest targeting for B2B

   CUSTOM AUDIENCES — RETARGETING (build all segments):
   Website Custom Audiences (requires Pixel or CAPI):
   - All website visitors: 30-day, 60-day, 90-day windows — when to use each
   - Product/feature page visitors: 30-day (highest intent)
   - Pricing page visitors: 14-day (critical BOFU segment — prioritize budget here)
   - Blog readers: 60-day (MOFU educational content engagement)
   - Demo/contact page visitors who didn't convert: 30-day (BOFU recovery)
   - Video viewers: 25%, 50%, 75% completion segments — create from Facebook-hosted video

   Customer/Prospect List Custom Audiences:
   - Full CRM contact list upload: file format (CSV), required fields (email, phone, first/last name), expected match rate (30-50%)
   - MQL list: contacts who engaged with marketing but haven't demoed — MOFU nurture targeting
   - Closed-won customer list: use as exclusion AND as lookalike seed
   - Churned customers: re-engagement campaign if product has improved
   - Open opportunity list: exclude from prospecting, consider for deal acceleration creatives
   - List upload frequency: monthly refresh cadence from CRM export

   Engagement Custom Audiences:
   - Facebook/Instagram page engagers: 30-day, 60-day, 180-day
   - Video viewers (see above)
   - Lead Ad form openers (didn't submit) vs. form submitters
   - Instagram profile visitors and story engagers

   LOOKALIKE AUDIENCES (highest ROI for B2B prospecting):
   - Seed audience selection priority: (1) Closed-won customers, (2) MQL list, (3) Demo completions, (4) All website converters
   - Lookalike percentage: 1-2% for quality (smallest, most similar), 3-5% for scale, 6-10% for volume
   - Country-specific lookalikes vs. multinational: when to split
   - Minimum seed audience size: 100 contacts (1000+ strongly recommended for quality lookalikes)
   - Advantage+ Lookalike: when Meta's automated lookalike construction outperforms manual
   - Stack multiple lookalike percentages: 1-2%, 3-5% as separate ad sets to understand quality vs. volume tradeoff

   AUDIENCE EXCLUSIONS (critical for budget efficiency):
   - Current customers (upload from CRM, refresh monthly)
   - Active pipeline opportunities stage 3+ (exclude from prospecting, not BOFU)
   - Employees and contractors (exclude company email domain via custom audience)
   - Recent converters (exclude 30-day converters from conversion campaigns — they already converted)
   - Audience overlap check: use Meta's Audience Overlap tool before launching to prevent cannibalization

4. AD CREATIVE SPECIFICATIONS (produce all copy)

   CREATIVE PHILOSOPHY FOR B2B META ADS:
   - Meta is a disruption environment — buyers are NOT looking for your solution when they see your ad
   - Interrupt → Intrigue → Deliver value → Ask for micro-commitment (not "Book a demo" cold)
   - TOFU creative must lead with a problem or insight, NEVER with product features
   - Use social proof in MOFU/BOFU: customer logos, specific metrics, recognizable names
   - Video dramatically outperforms static for cold audiences; static (single image/carousel) works well for retargeting

   SINGLE IMAGE ADS (3 variants per campaign):
   For each ad provide:
   - Primary text (125 characters max — hook in first 2 lines before "See more" cutoff)
   - Headline (40 characters max — benefit-driven, specific number where possible)
   - Description (30 characters max — secondary CTA or proof point)
   - CTA button: Learn More / Download / Sign Up / Get Quote / Book Now / Watch More
   - Visual concept description: image composition, text overlay copy (keep under 20% of image area), emotional tone
   - Psychological principle: which of Cialdini's 7 principles (reciprocity, commitment, social proof, authority, liking, scarcity, unity)

   Apply these frameworks by funnel stage:
   - TOFU: Lead with a contrarian insight or industry stat. No product mention. CTA = "Learn More" to ungated content. Goal: earn the click, not the conversion.
   - MOFU: Acknowledge the problem your prospect has. Feature a customer story or use-case specific outcome. CTA = "Download" or "Watch." Goal: move from awareness to consideration.
   - BOFU: Direct response. Reference the specific product benefit for their role. Include urgency (limited cohort, end of quarter) or risk reduction (free trial, money-back guarantee). CTA = "Book a Demo" or "Start Free Trial." Goal: conversion.

   CAROUSEL ADS (1 per MOFU consideration campaign):
   - Card 1 (hook): problem statement + striking visual — must make them want to swipe
   - Cards 2-4: solution story, feature-benefit pairs, or step-by-step process
   - Card 5 (CTA): clear offer with CTA button
   - Best use case: product walkthroughs, feature comparisons, customer journey visualization, "5 reasons why" content

   VIDEO ADS (produce for TOFU and MOFU):
   - Hook (first 3 seconds): script that works WITHOUT sound — use text overlay. Must stop the scroll.
   - 15-second structure: Hook (0-3s) → Problem (3-8s) → Solution tease (8-13s) → CTA (13-15s)
   - 30-second structure: Hook (0-3s) → Problem + Pain (3-12s) → Solution + Social proof (12-24s) → CTA (24-30s)
   - Captions: always on (85% of Facebook videos watched without sound)
   - Retargeting segment to create from video viewers: 25%, 50%, 75% viewed — use for MOFU custom audiences
   - Thumbnail selection: never a blurry mid-frame — use a text-on-image thumbnail that conveys the video's value

   META LEAD ADS (for lead generation campaigns):
   - Form type selection: "More Volume" (lower friction, pre-filled) vs. "Higher Intent" (adds review screen, higher quality)
   - When to use Lead Ads vs. website landing page: use Lead Ads when website conversion rate < 3% or when testing a new offer
   - Field strategy:
     * Volume play (2-3 fields): Email, First/Last name (auto-filled by Meta — near zero friction)
     * Quality play (4-5 fields): Add Company, Job Title — accept 40-60% drop in volume for 2x quality
     * Qualification play (5-6 fields): Add one custom question ("How many employees does your company have?" with buckets)
   - Intro screen: company logo, benefit statement, privacy reassurance — do NOT skip this
   - Thank-you screen: set expectations for follow-up timing ("Our team will reach out within 1 business day")
   - Completion rate benchmark: > 50% of form openers should complete — if lower, reduce fields or simplify questions

5. BIDDING STRATEGY & PACING
   Phase 1 — Learning Phase (Days 1-21):
   - Use Highest Volume (formerly "Lowest Cost") bid strategy to gather data
   - Do NOT edit targeting, budget (by more than 20%), or creative during learning phase
   - Learning phase exit criteria: 50 optimization events per ad set per week
   - If you can't reach 50 events/week: consolidate ad sets, broaden audience, or change optimization event to higher-volume action (add to cart instead of purchase; lead instead of demo request)
   - "Learning Limited" status: what causes it and how to fix it

   Phase 2 — Optimization (Days 22-45):
   - Evaluate creative performance: pause ads with CTR < 0.5% (cold) or < 1% (retargeting) after 1000+ impressions
   - Frequency management: refresh creative when frequency > 3 for cold audiences, > 6 for warm retargeting
   - Ad set consolidation: merge low-performing ad sets into winners to accelerate learning
   - Cost Cap introduction: only add cost cap after learning phase exits and you have a stable CPL baseline; set cap at 1.3x current average CPL

   Phase 3 — Scaling (Day 45+):
   - Budget scaling rule: increase daily budget by max 20% every 3-4 days — larger jumps re-enter learning
   - Horizontal scaling: duplicate winning ad sets with new audience segments vs. vertical scaling (increasing budget)
   - Creative refresh cadence: new creative every 3-4 weeks for cold audiences; retargeting creative can run 6-8 weeks
   - Advantage+ Shopping/Lead campaigns: when to graduate from manual to automated Meta campaigns

   Benchmarks for B2B Meta Ads (use for internal expectation setting):
   - Cold prospecting (interest/lookalike): CPM $8-18, CTR 0.5-1.2%, CPL $60-180
   - Warm retargeting (website visitors, video viewers): CPM $12-25, CTR 1.5-3%, CPL $25-80
   - BOFU retargeting (pricing page, demo page): CPM $15-35, CTR 2-5%, CPL $15-50
   - Lead Ads (pre-filled form): CPL 30-50% lower than website conversion — but lead quality also lower
   - Note: Meta CPLs are often lower than LinkedIn but lead-to-MQL rate is also lower — optimize for cost per pipeline, not cost per lead

6. POST-iOS 14 FIRST-PARTY DATA & MEASUREMENT STRATEGY
   iOS 14+ fundamentally changed Meta Ads measurement. This section is critical:

   Conversions API (CAPI) Implementation:
   - Why CAPI is non-negotiable: iOS 14 blocks ~40% of Meta Pixel signals; CAPI sends server-side events that aren't blocked
   - Implementation options: direct API integration, Meta's gateway, CRM native (HubSpot, Salesforce), or tag manager
   - Event match quality score: target > 7.0/10 — achieved by matching email + phone + name
   - Deduplication: pixel and CAPI will fire for the same event — Meta deduplicates if event_id matches
   - Priority events (Meta allows 8 "Aggregated Event Measurement" events per domain — choose wisely):
     * Tier 1: Purchase / Demo Request / Free Trial Start (highest value)
     * Tier 2: Lead form submit / Contact page submit
     * Tier 3: Content download / Webinar registration
     * Tier 4: Pricing page view / Product page view (volume events for optimization)

   Attribution Window Selection:
   - 7-day click, 1-day view: recommended default for B2B with longer sales cycles (captures full consideration window)
   - 1-day click: use only for direct response with very short intent cycles (free trial signups)
   - View-through attribution debate: include for awareness campaigns; exclude for conversion-only reporting to CFO
   - Compare-with period matching: always compare same day-of-week ranges (avoid comparing Tuesday to Saturday)

   Self-Reported Attribution:
   - Add "How did you first hear about us?" to every demo request form and free trial signup
   - Meta Ads will appear in self-reported data even when pixel/CAPI misses the attribution
   - Combine self-reported + platform-reported + CRM influenced pipeline for true Meta ROI picture
   - Monthly reconciliation: cross-reference Meta-attributed leads with CRM source field

7. MEASUREMENT FRAMEWORK & ATTRIBUTION
   Technical setup checklist:
   - Meta Pixel verification: confirm pixel fires on all key pages (use Meta Pixel Helper Chrome extension)
   - CAPI event confirmation: verify in Meta Events Manager that server events match pixel events
   - UTM parameter convention: `utm_source=facebook&utm_medium=paid-social&utm_campaign=[campaign-name]&utm_content=[ad-variant-name]`
   - Conversion event value setup: assign monetary values to each conversion (demo request = $300, content download = $15, webinar = $40)

   Reporting cadence:
   - Daily: Spend pacing, delivery issues, learning phase status alerts
   - Weekly: CPL by campaign, frequency check, creative fatigue signals, ROAS if e-commerce
   - Monthly: Pipeline influenced by Meta Ads (pull from CRM by UTM source), cost per opportunity, lead-to-MQL rate by campaign
   - Quarterly: Full-funnel attribution analysis, Meta's share of sourced vs. influenced pipeline, budget reallocation recommendation vs. LinkedIn and Google

   The B2B Meta Ads metrics hierarchy (present to leadership in this order):
   1. Pipeline sourced or influenced by Meta Ads (CRM pull, UTM + CAPI combined)
   2. Cost per opportunity (CPO) and cost per closed-won ($)
   3. Cost per qualified lead (MQL rate applied to CPL)
   4. Platform efficiency (CTR, CPM, CPL) — context only, not business outcomes
   5. Reach and frequency — awareness validation only

OUTPUT FORMAT:
Deliver a complete Meta Ads Manager implementation plan organized by the 7 sections above. Include all ad copy written out in full — no "[insert headline here]" placeholders. Include a pre-launch checklist at the end covering Pixel/CAPI verification, audience minimum sizes, and budget confirmation. Format for easy handoff to an in-house demand gen manager or paid media agency.

## Example Input/Output

**Input Example:**
Company: Rova — AI-powered customer success platform that reduces churn and identifies expansion revenue for B2B SaaS companies
Target buyers: VP of Customer Success, Head of CS, Chief Customer Officer, VP Customer Experience
ICP: 100-1500 employee B2B SaaS companies, US + Canada
Monthly Meta budget: $8,000
Primary goal: Demo request
Competitors: Gainsight, ChurnZero, Totango
ACV: $28,000
CRM: HubSpot
Pixel status: Installed with standard events (PageView, Lead, Contact)
Monthly website visitors: 12,000
CRM contact list: 8,400 contacts

**Output Example (partial):**

**STRATEGIC ROLE OF META IN ROVA'S PAID MIX:**
Meta Ads serves as Rova's retargeting and lookalike prospecting engine — not the primary demand creation channel (LinkedIn owns that for CS leader targeting). With 12,000 monthly website visitors and 8,400 CRM contacts, Rova has enough first-party data to make retargeting highly efficient. Expected contribution: 20-25% of total paid pipeline at 40-60% lower CPL than LinkedIn. Meta's B2B targeting is inferior to LinkedIn for cold audiences, but the retargeting and lookalike capabilities are superior in cost efficiency.

**CAMPAIGN ARCHITECTURE — 4 Campaigns, $8,000/month:**

| Campaign | Objective | Format | Budget | Bid Strategy | Primary KPI |
|---|---|---|---|---|---|
| TOFU — Lookalike Prospecting | Leads | Video + Single Image | $1,600 | Highest Volume | CPL < $150, Lead-to-MQL > 20% |
| MOFU — Blog & Content Retargeting | Traffic + Conversions | Carousel + Single Image | $2,400 | Highest Volume | CPL < $90, asset download rate > 3% |
| BOFU — Pricing & Demo Page Recovery | Conversions | Single Image | $3,200 | Cost Cap $75 | CPL < $75, Demo show rate > 55% |
| Retention — Customer Lookalike | Leads | Single Image | $800 | Highest Volume | CPL < $120, expansion MQL > 15% |

**SAMPLE AD COPY — BOFU Demo Recovery Campaign, Ad Variant 1:**
- **Primary text:** You visited Rova's pricing page. Most CS teams that find us are dealing with the same thing: churn they can see coming but can't stop fast enough. We can show you how 40+ SaaS teams fixed it in 20 minutes.
- **Headline:** See Rova in 20 minutes
- **Description:** No sales pressure. Just the demo.
- **CTA:** Book Now
- **Visual:** Split screen — left: red churn alert dashboard (generic/blurred); right: Rova's green health score trending upward with a revenue expansion overlay. Text overlay: "From churn risk to expansion revenue."
- **Psychological principle:** Loss aversion (churn fear) + Social proof (40+ SaaS teams) + Reciprocity (low-commitment "just the demo" framing)

**AUDIENCE — BOFU Demo Recovery Campaign:**
- Primary: Website Custom Audience — Pricing page visitors, last 14 days (estimated: ~240 people/month based on 2% of 12K visitors)
- Secondary: Website Custom Audience — Demo page visitors who did NOT submit, last 30 days
- Secondary: Lead Ad form openers who did NOT submit, last 30 days
- Exclusions: Current HubSpot customers (upload as Customer List CA), Active opportunities (upload from HubSpot deal pipeline stage 3+), Recent demo completers (last 30 days — they're already in the funnel)
- Estimated combined audience: 800-1,200 (small but extremely high intent — this is where BOFU budget is justified)
- Budget rationale: $3,200/month on 1,000-person audience yields high frequency (6-8) — use 3 creative variants to avoid fatigue

**LOOKALIKE STRATEGY:**
- Seed: Closed-won customer list from HubSpot (upload 180 contacts) → 1-2% US+Canada Lookalike
- Seed: All MQLs from last 12 months (upload 620 contacts) → 3-5% US+Canada Lookalike
- Note: 8,400-person CRM list → 2,520-4,200 matched profiles (30-50% match rate) → build 1% Lookalike
- Run 1-2% and 3-5% as separate ad sets to measure quality vs. volume tradeoff before consolidating

## Success Metrics

**Green (campaign is healthy):**
- Cold audience CTR > 0.6%, retargeting CTR > 1.5%, BOFU retargeting CTR > 2.5%
- CPL within target: set target at 8-10% of ACV (for $28K ACV, target CPL = $224-280 for qualified lead)
- Lead-to-MQL rate > 25% for retargeting, > 15% for cold lookalike (Meta leads are lower intent than LinkedIn by default)
- Demo show rate from Meta leads > 50% (lower bar than LinkedIn given audience cold start)
- Meta-influenced pipeline ≥ 2.5x Meta Ads spend (pipeline ROI ratio)

**Yellow (investigate):**
- Frequency > 4 on cold audience within first 30 days (creative fatigue setting in early)
- Lead-to-MQL rate < 15% for retargeting audiences (sign that audience is too broad or creative is misleading)
- CPL rising > 25% week-over-week for 2+ consecutive weeks (audience exhaustion)
- CAPI event match quality score < 6.0 (attribution data degrading — fix server-side events)

**Red (pause and diagnose):**
- CPL > 3x target for 3+ consecutive weeks across all campaigns
- Zero pipeline influence from Meta Ads after 90 days of spend
- Retargeting audience size < 200 people (insufficient to exit learning phase — fix website traffic first)
- CAPI connection broken for > 7 days (you're flying blind on optimization)

## Related Prompts
- [`04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-&-PPC/AI-Powered-B2B-LinkedIn-Ads-Campaign-Strategy-&-Audience-Targeting-Intelligence-Engine.md`](./AI-Powered-B2B-LinkedIn-Ads-Campaign-Strategy-&-Audience-Targeting-Intelligence-Engine.md) — Pair Meta Ads (retargeting + lookalike) with LinkedIn Ads (demand creation) for full paid social coverage
- [`04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-&-PPC/AI-Powered-B2B-Google-Ads-Campaign-Strategy-&-Search-Intent-Demand-Capture-Intelligence-Engine.md`](./AI-Powered-B2B-Google-Ads-Campaign-Strategy-&-Search-Intent-Demand-Capture-Intelligence-Engine.md) — Capture demand that Meta and LinkedIn create with Google Search
- [`05_Analytics-&-Performance/Paid-Media-&-PPC-Performance-Analytics/Meta-Ads-Performance-Analytics-&-Social-Commerce-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Paid-Media-&-PPC-Performance-Analytics/Meta-Ads-Performance-Analytics-&-Social-Commerce-Intelligence-Engine.md) — Deep-dive analytics and optimization for live Meta campaigns
- [`04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md`](../Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md) — Layer ABM intent signals onto Meta Ads targeting for account-based retargeting

## Integration Tips

**HubSpot:**
- Connect Meta Lead Ads natively via HubSpot's Meta Ads integration (Settings → Marketing → Ads → Connect Account)
- Map Meta Lead Ad form fields to HubSpot contact properties; set `hs_analytics_source` = "PAID_SOCIAL" and `hs_analytics_source_data_1` = "Facebook" automatically via integration
- Create a HubSpot workflow: trigger on Meta Lead Ad form submission → set lifecycle stage = Marketing Qualified Lead (if company size and title meet ICP criteria) → enroll in lead nurture sequence → notify assigned SDR within 5 minutes with personalized alert including the ad creative that converted them
- Use HubSpot's CAPI integration for server-side event matching: HubSpot → Settings → Ads → Conversions API — this significantly improves event match quality without developer resources
- Monthly audience sync: export HubSpot contact lists (MQLs, customers, open deals) as CSV → upload to Meta Custom Audiences → refresh the first of every month

**Salesforce:**
- Use Zapier or a native connector to trigger Meta Lead Ad webhook → Salesforce Lead create with `LeadSource` = "Paid Social — Meta" and `Campaign` = [Meta Campaign Name]
- Build a Salesforce report: "Meta-Influenced Opportunities" — filter Contacts where `Lead Source` contains "Meta" or "Facebook" and associated Opportunity Stage ≠ Closed Lost
- Create a Salesforce Campaign for each Meta campaign to enable multi-touch attribution — add Campaign Members when leads from Meta enter the funnel at any stage
- UTM parameters from Meta Ads auto-populate in Salesforce if you use the standard UTM→Salesforce field mapping: `utm_source` → `Lead Source Detail`, `utm_campaign` → `Ad Campaign`

**Marketo:**
- Meta Pixel + CAPI fires a "Fills Out Meta Lead Ad Form" activity in Marketo when using the native connector
- Build a Marketo Smart Campaign: trigger on Meta Lead Ad form fill → score += 20 → if score > 40 → alert SDR → if score > 60 → auto-qualify as MQL
- Use Marketo's custom activity logging to capture `utm_content` (ad variant) and `utm_campaign` (campaign name) — enables creative-level attribution inside Marketo
- Dynamic content: reference the specific Meta ad content in the first nurture email ("You downloaded our [Asset Name]...") using tokens populated from the Meta lead form custom fields

**Zapier (for custom and non-native integrations):**
- Trigger: "New Lead from Meta Lead Ad" → Action: "Create Contact in CRM" + "Send Slack alert to #demand-gen" with lead name, company, job title, and ad name
- Trigger: "Meta CAPI — Purchase/Demo event" → Action: "Update CRM Contact with Meta conversion timestamp" → "Add to post-conversion sequence"
- Use Zapier to refresh Meta Custom Audience lists automatically: schedule daily export from CRM → upload to Meta → ensures exclusion lists (customers, active deals) stay current without manual work

**Google Sheets (reporting):**
- Build a weekly Meta Ads dashboard: pull data via Meta Ads API (or manual export) → paste into Google Sheets
- Key columns: Date, Campaign, Ad Set, Ad Name, Spend, Impressions, CPM, Clicks, CTR, Leads, CPL, Lead-to-MQL rate, MQLs, Cost per MQL, Pipeline Influenced ($), Pipeline ROI
- Conditional formatting: CPL cells go red when > 1.5x target; CPM cells go yellow when > $20 for retargeting (possible audience exhaustion)
- Cross-channel comparison tab: Meta vs. LinkedIn vs. Google — CPL, Lead-to-MQL, CPO, Pipeline Influenced — update monthly to inform budget reallocation decisions

## Troubleshooting

**Problem: Campaigns stuck in "Learning Limited" status for 2+ weeks, insufficient optimization events**
Solution: Your conversion event is too low-volume for Meta's algorithm to exit learning. First, check how many times your primary event (e.g., demo request) fires per week — you need 50+ per ad set. If you're getting 5-10 per week, switch the optimization event to a higher-volume action in the funnel: optimize for "Lead" (form submission) instead of "Demo Request" (call scheduled), or optimize for "Pricing Page View" as a proxy signal. Once you accumulate data at the higher-volume event, switch back to your true conversion goal. Second option: consolidate your ad sets — instead of 5 ad sets each getting 10 events/week, merge into 2 ad sets getting 25 events/week. You'll exit learning faster with consolidated budgets and audiences.

**Problem: Meta CPLs are low but lead quality is terrible — SDRs report most Meta leads are unqualified**
Solution: Meta's targeting is less precise than LinkedIn for job-title-level B2B targeting, and Lead Ads pre-fill forms which reduces friction AND qualification signals. Take these three steps simultaneously: (1) Add a qualifying custom question to your Lead Ad form — "How many customers does your company currently support?" with buckets — and immediately filter out answers that don't fit your ICP. This alone often cuts volume 40% but doubles lead-to-MQL rate. (2) Switch from "More Volume" to "Higher Intent" form type in Meta Lead Ads — adds a review screen that reduces accidental submissions. (3) Shift 50% of your Lead Ad budget to website conversion campaigns that send traffic to a landing page — website form fills generate higher intent than native Meta forms for B2B because they require deliberate navigation. Compare lead-to-MQL rates across both approaches after 4 weeks and optimize allocation accordingly.

**Problem: BOFU retargeting campaign has very small audience (< 500 people), exits learning constantly, CPL unreliable**
Solution: Your website traffic volume is insufficient to sustain a meaningful BOFU retargeting pool. Address this in two ways: (1) Extend your retargeting window — if you're targeting 14-day pricing page visitors and getting only 200 people, extend to 30 days or 60 days. Yes, intent decays over time, but it's better to have a stable audience than constant learning fluctuations. (2) Expand your BOFU audience definition — include all visitors who spent 60+ seconds on any product page in the last 30 days, not just pricing page visitors. Create this time-on-page segment using Meta's Advanced Custom Audience rules. For longer-term fix, run MOFU campaigns to drive more qualified traffic to high-intent pages — your BOFU retargeting pool will grow as MOFU campaigns scale. Minimum viable BOFU pool for stable Meta learning: 1,000 people.

## Version History
- v1.0: Initial creation (auto-generated)
