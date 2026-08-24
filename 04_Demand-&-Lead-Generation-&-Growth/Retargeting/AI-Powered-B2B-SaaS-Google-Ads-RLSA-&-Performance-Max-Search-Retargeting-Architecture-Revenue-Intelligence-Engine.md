# AI-Powered B2B SaaS Google Ads RLSA & Performance Max Search Retargeting Architecture Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** google-ads, rlsa, performance-max, retargeting, paid-search, b2b-saas, demand-generation, pipeline-acceleration

## Overview

This prompt engineers a fully autonomous Google Ads search retargeting system for B2B SaaS companies using Remarketing Lists for Search Ads (RLSA) and Performance Max campaigns — turning high-intent website visitors, trial abandoners, and lost pipeline into search-captured pipeline at dramatically lower CPAs. Deploy when you want to recapture buyers who have already demonstrated interest before they evaluate competitors.

## Quick Copy-Paste Version

You are a senior B2B SaaS paid search strategist with deep expertise in Google Ads RLSA architecture, Performance Max campaigns, and Customer Match for enterprise pipeline generation.

Build a complete Google Ads search retargeting system for [Your SaaS Product] — a [product category] platform serving [ICP: e.g., "Director of Finance at 200-2000 person companies"].

Our current Google Ads situation:
- Monthly Google Ads spend: $[X]
- Current blended CPA for new visitors: $[X]
- Website monthly unique visitors: [X]
- Trial signups per month: [X]
- Pipeline deals lost per quarter: [X]

Build the following RLSA + Performance Max architecture:

**1. Audience Segment Construction**
For each segment below, define the exact Google Ads audience rules, minimum list size requirements, and exclusion logic:
- Pricing page visitors (last 30, 60, 90 days)
- Features/solutions page visitors who did NOT visit pricing
- Trial/freemium signups who did NOT activate (< 2 logins in 14 days)
- Demo requesters who no-showed or ghosted
- Customer Match list: closed-lost CRM contacts from last 12 months
- Customer Match list: current churned customers

**2. RLSA Bid Modifier Strategy**
For each audience above, recommend:
- Bid adjustment percentage (e.g., +80% for pricing page visitors)
- Keyword matching strategy (broader match is safe with RLSA)
- Ad copy differentiation vs. cold traffic (what changes?)
- Landing page routing logic (send to different pages than cold traffic?)

**3. Performance Max Retargeting Campaigns**
Design 3 Performance Max campaign structures targeting warm audiences:
- One for high-intent retargeting (pricing + demo request visitors)
- One for mid-funnel nurture (feature page visitors, blog readers)
- One for Customer Match win-back (churned + closed-lost)

For each, specify: asset groups, audience signals, budget allocation, conversion goals, and exclusion lists.

**4. Ad Creative & Messaging Matrix**
Write specific ad headlines (30 chars max), descriptions (90 chars max), and RSA pinning strategy for each audience tier. Include:
- Urgency/scarcity angles for hot retargeting
- Social proof angles for mid-funnel
- Win-back offers for churned/lost deals
- Competitor displacement copy for prospects evaluating alternatives

**5. Conversion Tracking & Bid Strategy Architecture**
Define:
- Conversion action hierarchy (which conversions to optimize for, in priority order)
- Smart bidding strategy per campaign (tCPA, tROAS, Maximize Conversions)
- Target CPA/ROAS by audience tier (warm audiences should have different targets than cold)
- Value-based bidding setup if CRM deal size data is available

**6. Negative Audience & Exclusion Logic**
Define precise exclusion lists to prevent budget waste:
- Current paying customers
- Employees and competitors
- Bounced visitors under [X] seconds
- Irrelevant geographies

**7. Weekly Optimization Cadence**
Create a 4-week ramp-up plan with specific weekly actions:
- Week 1: List population checks, baseline bid modifiers
- Week 2: First performance data review and bid adjustments
- Week 3: A/B ad copy test analysis
- Week 4: Full performance review, budget reallocation

Output: A complete campaign architecture document with implementation checklist, bid modifier table, ad copy matrix, and 30-day optimization calendar ready to hand off to a Google Ads specialist or import into campaign management tools.

## Advanced Customizable Version

ROLE: You are a Principal B2B SaaS Paid Search Architect with 12+ years specializing in Google Ads RLSA, Performance Max, and Customer Match for enterprise B2B companies. You have managed $50M+ in Google Ads spend and consistently achieve 40-60% lower CPAs on retargeting audiences vs. cold prospecting campaigns.

CONTEXT:
Company: [Company Name]
Product: [SaaS product — one sentence description]
ICP: [Title], [Company Size], [Industry]
ACV: $[X]K average contract value
Sales cycle: [X] months
Current Google Ads monthly spend: $[X] (breakdown: $[X] brand, $[X] non-brand, $[X] competitor)
Website traffic: [X] monthly unique visitors
Monthly trial signups: [X]
Closed-lost deals per quarter: [X] (CRM export available: [yes/no])
Current Google Ads CPA (new visitors): $[X]
Target CPA for retargeting (expected): $[X]
Google Ads account history: [X] months / conversion data: [X] conversions in last 90 days]
Primary conversion goals in order of priority: [e.g., Demo Request > Trial Signup > Content Download]
CRM: [HubSpot/Salesforce] — [is Customer Match sync available?]
Key competitors we lose deals to: [Competitor 1, 2, 3]

OBJECTIVE: Design a complete, implementation-ready Google Ads RLSA + Performance Max retargeting architecture that:
1. Reduces retargeting CPA by 40%+ vs. current cold traffic campaigns
2. Creates distinct audience tiers with differentiated messaging and bid strategies
3. Integrates Customer Match for CRM-based retargeting (churned + closed-lost)
4. Establishes a systematic optimization cadence that can run autonomously with weekly human review

SECTION 1: AUDIENCE TAXONOMY & LIST ARCHITECTURE

Build a 5-tier audience hierarchy using these frameworks:
- Tier 1 (Hottest): Pricing page + demo request page visitors (last 14 days)
- Tier 2 (Hot): Any high-intent page visitor (pricing/features/integrations) last 30 days not in Tier 1
- Tier 3 (Warm): Blog/content readers, webinar registrants, comparison page visitors (last 60 days)
- Tier 4 (Customer Match — Lost): Closed-lost CRM contacts, demo no-shows, trial non-activators
- Tier 5 (Customer Match — Churned): Former paying customers who churned in last 18 months

For each tier:
a) Exact Google Ads audience build rules (URL contains, page category, time window)
b) Minimum list size estimate and time to populate
c) Lookalike/Similar Audiences expansion strategy (where applicable)
d) Suppression list that overlaps with this tier (who to exclude from this specific list)

RLSA COMBINATION STRATEGY:
Show how to use audience combinations to create compound segments:
- "Visited pricing AND visited features" (high research intent)
- "Visited pricing NOT submitted demo form" (clear intent gap)
- "Trial signup AND visited upgrade page NOT converted" (expansion signal)

SECTION 2: RLSA CAMPAIGN ARCHITECTURE FOR EXISTING SEARCH CAMPAIGNS

For each of the company's existing campaign types (brand, non-brand, competitor), prescribe:

A) BRAND CAMPAIGNS + RLSA:
- Bid modifier recommendations per tier (Tier 1: +150%, Tier 2: +80%, Tier 3: +40%)
- Ad copy variants for retargeting audiences vs. first-time searchers
- Sitelink and callout extension differentiation by audience tier
- Landing page routing: should Tier 1 visitors go to a direct "Welcome back" page vs. standard homepage?

B) NON-BRAND / CATEGORY CAMPAIGNS + RLSA:
- Keyword match type expansion strategy (RLSA enables broader match safely)
- Budget reallocation: what % of non-brand budget should prioritize retargeting audiences?
- Ad scheduling adjustments for warm audiences (do warm audiences convert better at specific times?)

C) COMPETITOR CAMPAIGNS + RLSA:
- Bid modifier for "visited competitor comparison page" audience (these are highly valuable)
- Win-back specific copy for closed-lost deals who are re-searching competitor terms
- Offer differentiation: what exclusive offer or proof point moves a competitor evaluator?

SECTION 3: PERFORMANCE MAX RETARGETING CAMPAIGNS

Design 3 distinct Performance Max (PMax) campaign structures:

CAMPAIGN A — HIGH-INTENT RETARGETING ("Pipeline Rescue"):
- Audience signals: Tier 1 + Tier 2 custom segments
- Asset groups (minimum 3): [Describe asset group themes, not just structure]
  * Asset Group 1: ROI/business case focused (for economic buyers)
  * Asset Group 2: Feature/capability focused (for technical evaluators)
  * Asset Group 3: Social proof focused (customer logos, G2 rating, case study)
- Headlines (write 15 actual headlines, 30 chars each)
- Descriptions (write 4 actual descriptions, 90 chars each)
- Image concepts: describe the 3-5 visual concepts that will drive highest CTR for warm B2B audiences
- Video script brief: 30-second YouTube retargeting video outline
- Conversion goals: primary = Demo Request, secondary = Trial Signup
- Budget: [X]% of total retargeting budget
- Exclusions: current customers, Tier 4 Customer Match (handle separately)

CAMPAIGN B — MID-FUNNEL NURTURE ("Pipeline Warming"):
- Audience signals: Tier 3 custom segments
- Asset groups:
  * Asset Group 1: Educational content (guide, checklist, benchmark report)
  * Asset Group 2: Social proof light (1 customer quote + G2 rating)
  * Asset Group 3: Pain point articulation (problem > solution format)
- Headlines and descriptions: write 15 headlines, 4 descriptions
- Conversion goals: primary = Content Download, secondary = Webinar Registration
- Budget: [X]% of total retargeting budget

CAMPAIGN C — CUSTOMER MATCH WIN-BACK ("Closed-Lost & Churned Recovery"):
- Audience: Tier 4 + Tier 5 Customer Match lists
- Asset groups:
  * Asset Group 1: "What's new" — feature releases since they left
  * Asset Group 2: Win-back offer (special migration incentive, reduced onboarding fee, extended trial)
  * Asset Group 3: Displacement — why customers who left competitors came back
- Headlines and descriptions: write 15 headlines, 4 descriptions with win-back specific angles
- Conversion goals: primary = Demo Request with "Former Customer" form field flag
- Special: include URL parameter (?src=winback) for CRM tracking

SECTION 4: BID STRATEGY & SMART BIDDING ARCHITECTURE

For each campaign type, specify:

RLSA CAMPAIGNS (layered on existing):
- Use Target CPA (tCPA) with audience-level bid adjustments
- Set separate tCPA targets per audience tier:
  * Tier 1: [X]% below average account CPA (e.g., $200 if account average is $400)
  * Tier 2: [X]% below average
  * Tier 3: at average CPA
- New campaign minimum conversion threshold before switching to Smart Bidding: 30 conversions in 30 days

PERFORMANCE MAX CAMPAIGNS:
- Campaign A (High-Intent): Maximize Conversions, then switch to tCPA after 50+ conversions
- Campaign B (Mid-Funnel): Maximize Conversions with conversion value rules weighting Demo > Download
- Campaign C (Win-Back): Maximize Conversions with tCPA set 30% below new customer CPA (win-backs close faster)

VALUE-BASED BIDDING (if CRM data available):
- Assign conversion values by deal stage: MQL = $[X], SQL = $[X], Closed Won = $[X]
- Import offline conversions from CRM at each stage progression
- Configure tROAS targets: Campaign A = [X]x, Campaign B = [X]x

SECTION 5: AD COPY MATRIX & MESSAGING STRATEGY

Develop a full ad copy matrix with A/B test framework:

For each audience tier, write:
- 3 headline variants testing: (1) outcome-focused, (2) social proof, (3) urgency/scarcity
- 2 description variants testing: (1) feature differentiation, (2) risk reversal / guarantee

PSYCHOLOGICAL PRINCIPLES TO APPLY BY TIER:
- Tier 1 (Hot): Loss aversion ("Don't let [competitor] solve this first"), urgency, peer validation
- Tier 2 (Warm): Authority, specificity (name the problem exactly), social proof
- Tier 3 (Content): Reciprocity (free value offer), curiosity, belonging to a successful group
- Tier 4 (Lost Deals): Fresh start framing, "what's changed" hook, risk removal
- Tier 5 (Churned): Empathy + new capabilities, migration ease, win-back exclusivity

COMPETITOR DISPLACEMENT AD COPY:
For each of the 3 named competitors, write 3 RLSA-targeted headlines + 1 description that:
- Acknowledges the evaluation without naming the competitor directly (policy compliant)
- Highlights the single most compelling differentiation point vs. each competitor
- Includes a specific proof point (statistic, G2 comparison rating, customer quote fragment)

SECTION 6: LANDING PAGE & POST-CLICK EXPERIENCE

RLSA LANDING PAGE ROUTING STRATEGY:
Create a decision tree for where each audience segment should land:
- Tier 1 pricing visitors: → Personalized pricing page with "You were looking at [plan]" message
- Trial non-activators: → "Welcome back" page with activation checklist + chat bot trigger
- Competitor evaluators: → Competitive comparison landing page with switching guide
- Closed-lost (Customer Match): → "What's new" page highlighting releases since their last evaluation
- Churned customers: → Win-back specific landing page with exclusive return offer

PERSONALIZATION PARAMETERS:
Define UTM and URL parameter structure to:
- Pass audience tier to landing page CMS (for dynamic content)
- Trigger appropriate CRM workflow (retargeting visitor vs. cold visitor)
- Enable proper attribution in analytics

SECTION 7: CUSTOMER MATCH IMPLEMENTATION GUIDE

Provide step-by-step Customer Match upload process:

1. CRM SEGMENT DEFINITION:
- Closed-lost deals: Stage = Closed Lost, Close Date = Last 12 months, Exclude: reactivated in last 90 days
- Trial non-activators: Created Date = Last 6 months, Login Count < 2, Exclude: current active trials
- Churned customers: Status = Churned, Churn Date = Last 18 months, ACV > $[X] (prioritize)

2. DATA PREPARATION:
- Required fields: email, first name, last name, phone (optional), company name
- Hashing: SHA256 hashing is required (Google handles this in UI; specify if using API)
- List refresh frequency: Weekly automated export + upload (specify API vs. manual process)

3. MATCH RATE OPTIMIZATION:
- Target match rate: >40% for B2B email lists (lower is normal vs. B2C)
- Tactics to improve match rate: include multiple email formats (work + personal), phone numbers
- Fallback: if match rate < 20%, use Similar Audiences as supplement

4. PRIVACY COMPLIANCE:
- Customer Match consent requirements (GDPR, CCPA, Google policy)
- Suppression list management (opt-outs, DNC lists)
- Data retention policy alignment with Google's 90-day maximum

SECTION 8: MEASUREMENT FRAMEWORK & ATTRIBUTION

Define the complete measurement architecture:

CONVERSION TRACKING HIERARCHY:
1. Primary: Demo Request form submit (Google Ads tag + CRM import)
2. Secondary: Trial Signup (Google Ads tag)
3. Tertiary: High-value content download (Google Ads tag, lower value)
4. Offline: CRM stage progression imports (SQL creation, Opportunity creation, Closed Won)

REPORTING DASHBOARD STRUCTURE (for weekly review):
- Top-line metrics: Impressions, Clicks, CTR, CPC, Conversions, CPA, ROAS by campaign
- Audience performance: Segment-level CPA comparison (Tier 1 vs. 2 vs. 3 vs. Customer Match)
- Ad copy performance: RSA asset ratings, top/learning/low asset identification
- Incrementality note: flag that Google Ads data overstates performance vs. true incrementality

INCREMENTALITY TESTING:
- Design a geo-based holdout experiment to measure true incremental pipeline from retargeting
- Suggested split: 80% exposed markets, 20% holdout markets for 4 weeks
- Success metric: pipeline created in exposed vs. holdout, normalized by baseline

SECTION 9: 30-DAY LAUNCH & OPTIMIZATION CALENDAR

Week 1 (Launch):
- Day 1: Audit existing audiences, confirm list sizes, set up new RLSA audience layers
- Day 2: Upload Customer Match lists (closed-lost, churned), verify match rates
- Day 3: Launch PMax Campaign A (High-Intent) and enable RLSA bid modifiers on brand
- Day 5: Launch PMax Campaign B (Mid-Funnel)
- Day 7: First performance snapshot — check impression share, list size confirmation

Week 2 (Early Optimization):
- Day 8: Review PMax asset group performance ratings; add learning assets if flagged
- Day 10: Adjust RLSA bid modifiers based on early CPA data (+/- 20% from initial settings)
- Day 12: Launch PMax Campaign C (Win-Back) with Customer Match
- Day 14: Mid-point review: pause underperforming ad copy, scale winning messages

Week 3 (Scaling):
- Day 15: Budget reallocation based on CPA performance across campaigns
- Day 17: Expand keyword coverage in RLSA campaigns (safer with warm audiences)
- Day 19: Create new ad copy variants based on top-performing RSA asset combinations
- Day 21: Set up offline conversion import from CRM for SQL and deal stage data

Week 4 (Performance Review):
- Day 22: Full performance review vs. cold traffic benchmarks
- Day 24: Incrementality analysis (if geo-holdout test is running)
- Day 26: Refresh Customer Match lists with past 7-day new entries
- Day 28: Decision: increase budget for highest-performing segments, sunset underperformers
- Day 30: Document lessons learned, update SOPs, set Month 2 targets

OUTPUT FORMAT:
Produce a structured implementation document with:
1. Executive Summary (3 bullets: expected CPA reduction, pipeline recovery estimate, timeline to results)
2. Audience Architecture Table (segment name, list size, bid modifier, CPA target, platform)
3. Campaign Structure Summary (campaign name, type, budget %, conversion goal, audience)
4. Ad Copy Matrix (by tier: 3 headlines, 2 descriptions, landing page destination)
5. Customer Match Upload Checklist (7-step process with data requirements)
6. 30-Day Optimization Calendar (table format)
7. KPIs and Measurement Framework (what to report, when, to whom)

All outputs should be directly importable into a Google Ads campaign management system or transferable to a paid search agency without additional clarification.

## Example Input/Output

**Input Example:**

Company: Mosaic Analytics — B2B SaaS financial planning platform
ICP: VP Finance, CFO at 100-1,000 person companies
ACV: $48K
Sales cycle: 4.5 months
Google Ads spend: $85,000/month (brand: $15K, non-brand: $55K, competitor: $15K)
Website: 28,000 monthly unique visitors
Monthly trial signups: 340
Closed-lost deals/quarter: 87
Current non-brand CPA: $1,240
Target retargeting CPA: $680
CRM: Salesforce, Customer Match sync available via Zapier
Key competitors: Pigment, Anaplan, Planful

**Output Example (excerpt):**

**EXECUTIVE SUMMARY**
- Expected outcome: 45% reduction in CPA for Tier 1-2 audiences ($1,240 → ~$680), recovering ~$420K in pipeline from closed-lost + churned segments in 90 days
- Timeline: Audiences populate in 7-14 days; Smart Bidding requires 4 weeks of learning; full performance visible at Day 45
- Investment: Reallocate 25% ($21,250/month) of existing spend to RLSA/PMax retargeting layers; no net budget increase required

**AUDIENCE ARCHITECTURE TABLE (excerpt)**

| Segment | List Size Est. | Bid Modifier (Brand) | Bid Modifier (Non-Brand) | CPA Target |
|---|---|---|---|---|
| Pricing page (14d) | ~840 users | +180% | +120% | $520 |
| High-intent pages (30d) | ~3,200 users | +100% | +65% | $720 |
| Blog/content (60d) | ~9,400 users | +35% | +15% | $1,050 |
| Customer Match: Closed-Lost | ~290 contacts | +80% | +60% | $680 |
| Customer Match: Churned | ~145 contacts | +90% | +70% | $580 |

**SAMPLE AD COPY — TIER 1 (Pricing Page Visitors, High-Intent):**

Headlines (15 written, top 5 shown):
1. "FP&A Teams Trust Mosaic" (30 chars)
2. "See Your ROI in 90 Days" (23 chars)
3. "500+ Finance Teams Chose Us" (27 chars)
4. "Schedule a Personal Demo" (24 chars)
5. "Rated #1 on G2 for FP&A" (24 chars)

Descriptions:
1. "Join Brex, Rippling & 500+ finance teams replacing spreadsheets with intelligent planning." (90 chars)
2. "Average 3.2x ROI in Year 1. Implementation in 6 weeks. See a live build of your model." (87 chars)

Landing page: /demo?src=rlsa-pricing-t1&audience=hot (routes to personalized demo page with CFO-specific case study pre-loaded)

**PERFORMANCE MAX CAMPAIGN A ASSET GROUP — "ROI Focus":**
- Headline 1 (pinned): "Cut FP&A Close Time by 60%"
- Headline 2 (pinned): "Mosaic — #1 Rated FP&A Platform"
- Headline 3 (flexible): [rotate 12 remaining headlines]
- Description 1: "Automate consolidation, scenario modeling & board reporting. Brex reduced close from 5 days to 2."
- Image concepts: (1) Dashboard screenshot with clean UI + data visualization, (2) Finance team in modern office looking at screen, (3) G2 Leader badge + 4.7 star rating overlay

## Success Metrics

- Retargeting CPA 35-55% lower than cold traffic CPA within 60 days
- Customer Match match rate >35% for closed-lost list, >30% for churned list
- RLSA Tier 1 CTR >3x the account average CTR (warm audiences engage more)
- Win-back pipeline created from Customer Match campaigns: measure as "reactivated pipeline" in CRM
- Performance Max asset ratings: >70% of assets rated "Good" or "Best" by Day 30
- Incrementality test result: retargeting drives >15% incremental demo requests vs. control markets

## Related Prompts

- [Cross-Channel Behavioral Retargeting & Intent Signal Activation](./AI-Powered-B2B-SaaS-Cross-Channel-Behavioral-Retargeting-&-Intent-Signal-Activation-Revenue-Intelligence-Engine.md)
- [Lost Opportunity Recovery & Retargeting Architecture](./AI-Powered-B2B-SaaS-Retargeting-&-Lost-Opportunity-Recovery-Revenue-Intelligence-Engine.md)
- [Google Demand Gen Campaign Architecture](../../04_Demand-&-Lead-Generation-&-Growth/Paid-Search-Advertising/AI-Powered-B2B-SaaS-Google-Demand-Gen-Campaign-Architecture-&-Upper-Funnel-Video-Image-Creative-Revenue-Intelligence-Engine.md)
- [Meta Facebook Retargeting Analytics](../../05_Analytics-&-Performance/Retargeting-Analytics/AI-Powered-B2B-SaaS-Meta-Facebook-Retargeting-Analytics-&-Custom-Audience-Pipeline-Revenue-Attribution-Intelligence-Engine.md)

## Integration Tips

- **Google Ads API + Zapier/Make:** Automate Customer Match list uploads on a weekly schedule — pull closed-lost + churned contacts from Salesforce/HubSpot filtered by date, export as CSV, upload via Google Ads API or manual UI upload
- **HubSpot Integration:** Use the native HubSpot → Google Ads Customer Match sync (available in HubSpot Marketing Hub Pro+) to automatically keep closed-lost and churned lists current; set sync frequency to daily
- **Salesforce + Google Ads:** Use Salesforce Marketing Cloud's Google Ads connector, or implement via Zapier: Trigger = "Opportunity Stage Changed to Closed Lost" → Action = "Add Contact to Google Customer Match List"
- **Google Analytics 4:** Import GA4 audiences (pricing page visitors, trial signups, high-intent segments) directly into Google Ads via the linked property — this ensures consistent audience definitions between analytics and ad buying
- **Looker Studio Dashboard:** Build a retargeting performance dashboard connecting Google Ads API data with CRM pipeline data to show retargeting-attributed pipeline at each deal stage; automate weekly email delivery to demand gen team
- **Offline Conversion Import:** Set up automated pipeline stage import from CRM → Google Ads using GCLID tracking: capture the GCLID at form submission, store in CRM, import when contact reaches SQL and Opportunity Created stages

## Troubleshooting

**Problem: Customer Match lists show "Policy Error" or very low match rates (<15%)**
Solution: Ensure emails are not hashed before upload (Google handles SHA-256 hashing in the UI). For low match rates, enrich your CRM export with personal email addresses in addition to business emails — LinkedIn Premium or Clay can help identify personal emails for key contacts. Also ensure your Google Ads account is Customer Match eligible (requires $50K+ lifetime spend or whitelisted status). Match rates for B2B lists typically run 25-45%; below 20% usually indicates stale or incorrect email data.

**Problem: Performance Max campaigns are spending budget on brand terms, inflating CPA**
Solution: Add your brand keywords and variants as negative keywords at the campaign level (PMax supports negative keyword lists). Also create a separate brand keyword exclusion list and apply it to all PMax campaigns. Monitor Search Terms report weekly (available under Insights → Search Terms in PMax) to identify and negate brand+competitor terms that PMax is bidding on with incorrect attribution.

**Problem: RLSA bid modifiers are active but audience reach is too low to impact performance**
Solution: Minimum list sizes for RLSA are 1,000 users for Search and 100 users for YouTube/Display. If pricing page audiences are under 1,000, expand the lookback window (14d → 30d → 60d) or broaden the URL pattern (include /features/ and /pricing/ in one list). For Customer Match lists under 1,000, supplement with Similar Audiences targeting. Also ensure the Google Ads tag is firing correctly on all relevant pages — verify in Google Tag Manager or use the Google Ads Tag Assistant Chrome extension.

## Version History
- v1.0: Initial creation (auto-generated)
