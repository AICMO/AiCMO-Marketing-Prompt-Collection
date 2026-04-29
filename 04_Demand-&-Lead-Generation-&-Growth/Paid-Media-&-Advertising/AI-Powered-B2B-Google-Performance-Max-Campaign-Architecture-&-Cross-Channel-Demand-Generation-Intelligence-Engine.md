# AI-Powered B2B Google Performance Max Campaign Architecture & Cross-Channel Demand Generation Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** google-ads, performance-max, pmax, b2b, demand-generation, paid-media, cross-channel, smart-bidding

## Overview

Designs and deploys a fully optimized B2B Google Performance Max (PMax) campaign—from asset group architecture and audience signal strategy to search theme configuration, exclusion frameworks, and pipeline-level attribution. Use this when launching PMax as part of your Google Ads program, recovering a poorly-configured PMax campaign that is burning budget on irrelevant placements, or scaling cross-channel Google demand generation beyond standard search campaigns.

## Quick Copy-Paste Version

You are a B2B Google Performance Max campaign strategist. Build a complete PMax campaign architecture for the following company:

Company: [Your Company Name]
Product/Service: [What you sell and who buys it]
ICP: [Ideal customer profile — industry, company size, buyer titles, e.g., "VP of IT at 200-2,000 employee manufacturing companies"]
Monthly PMax budget: $[X]
Average Contract Value (ACV): $[X]
Sales cycle length: [X weeks/months]
Pipeline goal (next 90 days): $[X in sourced pipeline]
Top 3 competitors: [List them]
Primary conversion goal: [Demo request / Free trial / Contact sales]
Existing Google Ads assets available: [List existing search campaigns, customer lists, videos if any]

Deliver:
1. Campaign structure: How many PMax campaigns to run, how to segment them (by audience intent, by product line, by geo), and what to exclude from each
2. Asset group architecture: Number of asset groups per campaign, how to theme them, and complete asset requirements checklist (headlines, descriptions, images, logos, videos, callouts, sitelinks)
3. Audience signal strategy: First-party signals (customer match lists, website visitor segments), Google intent signals (in-market, affinity, custom intent), and how to layer them per asset group
4. Search themes configuration: 25 search theme phrases per campaign that guide the algorithm without locking to exact match keywords — covering branded defense, category/solution, problem-aware, and competitor conquest intents
5. Exclusion framework: Branded keyword exclusions (if running parallel search campaigns), placement exclusions (consumer apps, games, irrelevant sites), negative keyword lists, and audience exclusions (existing customers for acquisition campaigns)
6. Smart Bidding configuration: Target CPA setup for B2B, recommended starting CPA, ramp-up strategy, and when to switch from Maximize Conversions to Target CPA
7. Asset performance monitoring: How to read asset-level performance labels (Best/Good/Low), what to replace weekly, and how to A/B test creative systematically
8. Attribution and pipeline tracking: How to pass UTM parameters through PMax, connect conversions to CRM opportunities, and measure pipeline influence (not just form fills)
9. 30/60/90-day optimization roadmap with specific milestones and decision triggers
10. Top 5 B2B PMax pitfalls and how to prevent each

Format as an executable campaign brief a demand generation marketer can implement in Google Ads within three business days.

## Advanced Customizable Version

# ROLE
You are a senior B2B paid media strategist who has architected and managed Google Performance Max campaigns for enterprise and mid-market SaaS, professional services, and technology companies. You have scaled PMax accounts from $15K to $800K monthly spend, navigated the forced migration from Smart Shopping and Discovery campaigns, and developed systematic approaches for controlling Google's AI-driven campaign type in B2B environments where audience precision matters more than reach volume. You understand that PMax was designed for e-commerce and must be carefully constrained and configured to work for complex B2B sales cycles—the defaults will waste budget on consumer placements and irrelevant searches. You know how to use asset groups, audience signals, search themes, and exclusion lists to guide the algorithm toward high-quality pipeline without surrendering all control to Google's automation.

# CONTEXT
**Company:** [Company Name]
**Industry vertical:** [e.g., Construction Tech SaaS, Legal Practice Management, Supply Chain Visibility, Revenue Intelligence, HR Compliance Software]
**Stage:** [Seed / Series A / Growth / Enterprise / Public]
**ARR:** [$X]
**ACV (average contract value):** [$X — critical for setting CPA targets and determining how aggressive to bid]
**Sales cycle:** [X weeks/months — determines attribution window and remarketing duration]
**ICP definition:**
  - Firmographics: [Industries, employee count range, annual revenue range, geographies, ownership type]
  - Primary buyer titles: [e.g., VP of Operations, CFO, Head of Compliance, Director of Engineering]
  - Economic buyer: [e.g., COO, CEO — who signs the contract]
  - Technographics: [Current tech stack, incumbent vendors being displaced]
  - Trigger events: [What causes them to search/buy — compliance deadline, system failure, growth milestone, budget cycle, M&A]
**Monthly PMax budget:** [$X]
**Total Google Ads budget (including Search):** [$X — PMax budget should be 20-40% of total Google spend for most B2B programs; do NOT replace Search entirely with PMax]
**Pipeline goal (90 days):** [$X in sourced pipeline attributed to Google Ads]
**Primary conversion actions (ranked by value):**
  1. [e.g., Demo request form — assign pipeline value $X]
  2. [e.g., Free trial activation — assign pipeline value $X]
  3. [e.g., Gated content download — assign lead value $X]
**Secondary micro-conversions:** [e.g., Pricing page visit, ROI calculator completion, 5+ minutes on site]
**Competitors to conquest or exclude from Google brand campaigns:** [Competitor A, B, C]
**Existing creative assets:**
  - Videos available: [Yes — list durations and topics / No — must script and produce]
  - Customer logos available: [Yes / No]
  - Case study assets: [Yes — describe / No]
  - Existing landing pages: [List URLs or "need to build"]
**First-party data available:**
  - Customer email list: [X records]
  - Open opportunities list: [X records]
  - Closed-lost list: [X records]
  - Website visitor remarketing pool: [X monthly unique visitors]
**CRM and attribution stack:** [e.g., Salesforce + Marketo / HubSpot / 6sense / Rockerbox / Northbeam / GA4]
**Existing Google Ads campaigns:** [Running Search campaigns (yes/no), existing PMax (yes/no — if yes, describe current structure and performance issues)]
**Geographic targeting:** [Countries / Regions / Cities — include exclusions]

# OBJECTIVE
Produce a complete, immediately executable B2B Google Performance Max campaign architecture that:
- Generates cross-channel pipeline through Google's full inventory (Search, Display, YouTube, Gmail, Discover) while maintaining B2B audience precision
- Maximizes signal quality to the PMax algorithm through structured first-party audience data, search themes, and asset groups
- Prevents budget waste through systematic exclusions of consumer placements, irrelevant audiences, and non-ICP geographies
- Connects every conversion event to a CRM opportunity with proper UTM attribution and offline conversion import
- Operates as a complement to (not replacement of) standard Google Search campaigns
- Provides weekly optimization levers despite PMax's limited transparency

# DELIVERABLES

## Deliverable 1: Campaign Architecture & Segmentation Strategy

**B2B PMax Campaign Structure Principles:**

Unlike standard search campaigns, PMax offers limited control over where ads appear. For B2B, the segmentation strategy must compensate by controlling what signals you feed the algorithm, not where it places ads.

**Recommended Campaign Structure for Most B2B Programs:**

**Campaign A — New Customer Acquisition (Primary PMax Campaign)**
- Budget: 60-70% of PMax budget
- Goal: Reach net-new ICP accounts not in your CRM
- Smart Bidding: Maximize Conversions → Target CPA (after 50+ conversions)
- Target CPA: Set at [ACV × 0.10-0.15] for demo requests (e.g., $10K ACV = $1,000-$1,500 Target CPA)
- Exclusions: Existing customers (customer match exclusion), open opportunities (suppress with CRM list), known non-ICP audiences
- Audience signals: Custom intent (competitor research terms + category solution terms), in-market segments relevant to your solution, website visitors who have not converted, similar-to-converter lookalikes

**Campaign B — Retargeting & Pipeline Acceleration (Secondary PMax Campaign)**
- Budget: 20-30% of PMax budget
- Goal: Re-engage warm prospects who have visited key pages (pricing, demo, product pages) but not converted
- Smart Bidding: Target CPA set at 0.6× Campaign A CPA (warm audiences convert higher)
- Audience signals: Pricing page visitors (7-30 days), demo page non-converters (14 days), case study readers (21 days), YouTube video viewers who engaged but did not click through
- Asset groups: Objection-handling creative (address common purchase barriers — "No setup fees," "Risk-free 30-day trial," competitor comparison angles)

**Campaign C — Customer Expansion (If running NRR marketing programs)**
- Budget: 10-15% of PMax budget
- Goal: Surface expansion offers to current customers (upsell, cross-sell, product line expansion)
- Audience signals: Customer match list (current paying customers only), segmented by product tier or usage
- Exclusions: Churned customers, customers under negotiation (suppress to avoid complicating renewals)

**When to Use a Single PMax Campaign vs. Multiple:**
- Single PMax: Budgets under $15K/month — insufficient data volume to split campaigns effectively
- Multiple PMax campaigns: Budgets $15K+/month, distinct product lines with different ICPs, or clear separation between new acquisition and retargeting needed

---

## Deliverable 2: Asset Group Architecture

**The fundamental building block of PMax is the asset group**, not the campaign. Asset groups are where you control creative messaging, audience signals, and URL targeting. Design asset groups to reflect distinct buyer segments, pain points, or funnel stages.

**Asset Group Strategy for B2B:**

| Asset Group | Audience Signal Theme | Headline Angle | Landing Page | 
|---|---|---|---|
| AG 1: Category/Solution Buyers | In-market for [solution category] + custom intent (solution search terms) | "The [Category] Platform Trusted by [X] [ICP Industry] Companies" | Product/solution page |
| AG 2: Problem-Aware Buyers | Custom intent (pain point search terms) + in-market for adjacent categories | "[Pain Point] Is Costing You [Outcome]. Here's How to Fix It." | Problem-specific landing page or gated diagnostic |
| AG 3: Competitor Conquest | Custom intent (competitor brand + product terms) | "A Better Alternative to [Competitor] — See Why [X] Teams Switched" | Comparison landing page |
| AG 4: Customer Proof / Social Proof | Similar to converters + RLSA (case study readers) | "[Customer Name] Achieved [Specific Outcome] in [Timeframe] with [Product]" | Case study or proof hub page |

**Complete Asset Requirements per Asset Group:**

*Headlines (15 required, 30 character limit each):*
- 3-4 keyword-driven headlines: Include your primary solution category name and key modifiers
- 3-4 proof-point headlines: G2 rating, customer count, specific outcome statistics
- 3-4 offer/CTA headlines: "See Live Demo," "Start Free Trial," "Get ROI Assessment"
- 2-3 ICP-specific headlines: Reference buyer title, industry, or specific use case
- 1-2 differentiator headlines: Speed to value, integration capability, compliance certification

*Descriptions (4 required, 90 character limit each):*
- Description 1: Primary pain + solution + CTA (pack with specifics: customer count, outcome metrics)
- Description 2: Differentiation from incumbent/competitor + proof point (G2, analyst ranking, certification)
- Description 3: ICP-specific context — reference the industry or buyer title and their specific challenge
- Description 4: Risk-reduction framing — free trial, no setup fees, customer success commitment

*Images (required — Google PMax minimum requirements):*
- Marketing images (1.91:1 ratio, min 600×314px): 3-5 variations — product screenshots, team photos, customer event photos, abstract brand visuals. Avoid stock photos — Google's algorithm favors authentic imagery.
- Square images (1:1 ratio, min 300×300px): 3-5 variations — same content as marketing images in square crop
- Portrait images (4:5 ratio, min 480×600px): 2-3 variations — optimized for mobile display placements
- Logo (1:1 and 4:1): 1 high-resolution version each — used across all placements; ensure legibility at small sizes

*Videos (minimum 1 required — critical for YouTube inventory):*
- 6-second bumper: Brand awareness/retargeting — single message, high visual impact, no voiceover required
- 15-30 second in-stream: Lead-in value proposition — skip button appears at 5 seconds; front-load hook in first 4 seconds
- 60-90 second explainer: Demo highlight, customer testimonial, or product walkthrough — for engaged in-market audiences

**Video Script Framework (if producing new videos for PMax):**
- Second 0-4 (Hook — before skip): "If you're a [ICP title] dealing with [specific pain], this is for you." OR "[Compelling statistic about the problem]."
- Second 5-15 (Problem agitation): Quantify the cost of the status quo for the viewer's specific role
- Second 15-45 (Solution + proof): Introduce your product, show the interface briefly, cite one customer outcome with real numbers
- Second 45-end (CTA): Single clear action — "Book a demo at [URL]" or "Start your free trial today"

*Callouts (4-10, 25 character limit each):*
Examples: "G2 Leader 4.9/5 Stars," "SOC2 Type II Certified," "No Setup Fees," "Deploy in 14 Days," "24/7 Support Included," "HIPAA Compliant," "Integrates with Salesforce," "500+ Enterprise Customers"

*Sitelinks (4-8 pairs — link text + description):*
- Request a Demo → See how [Product] works for [ICP industry] teams in a 20-minute live demo
- View Pricing → Transparent pricing with no surprise fees. Compare plans side by side.
- [Top Case Study Name] → How [Customer] achieved [specific outcome] in [timeframe]
- ROI Calculator → Calculate your potential ROI in 3 minutes. Based on [X] customer data points.
- Compare to [Competitor] → See a side-by-side comparison with real customer reviews
- View Integrations → [Product] connects with your existing stack — Salesforce, HubSpot, Slack, and 100+ more

---

## Deliverable 3: Audience Signal Strategy

**Critical PMax distinction:** Audience signals are *suggestions* to the algorithm, not targeting restrictions. Google will serve ads outside your signals if it believes it can find converters. Your job is to give the algorithm the highest-quality starting signals possible so it learns faster in the right direction.

**Tier 1 — First-Party Signals (Most Valuable — Upload to All Asset Groups):**

| Signal Type | Source | Purpose | How to Configure |
|---|---|---|---|
| Converter list (past demo requesters/trial signups) | CRM export (email + phone) | Teach algorithm what a "good conversion" looks like | Upload as Customer Match → add to all asset groups as "optimized for" audience signal |
| Open opportunities | CRM export | Show ads to accounts in active sales cycle (pipeline acceleration) | Segment from new acquisition campaign; use in Campaign B (Retargeting) |
| Closed-lost (last 18 months) | CRM export | Re-engage buyers who evaluated but chose a competitor | Use in dedicated re-engagement asset group with competitive messaging |
| High-value website visitors | GA4 audience → linked to Google Ads | Visitors who viewed pricing + 2+ product pages in last 30 days | Upload as RLSA audience → use as bid signal in Campaign A, primary targeting in Campaign B |

**Tier 2 — Google Audience Signals (Use to Supplement First-Party Data):**

| Signal Type | Examples for B2B | Usage |
|---|---|---|
| In-market audiences | "Enterprise Software," "Business Intelligence Software," "CRM Software," [your specific category] | Add to all asset groups as secondary signals |
| Custom intent audiences | Build from: competitor brand searches, category solution terms, problem-aware search terms (e.g., "how to reduce [pain]"), industry-specific conference hashtags | Create 3-5 custom intent audiences from your search term data — these are the highest-value non-first-party signals |
| Affinity audiences | "Business Professionals," "B2B Decision Makers" (if available), industry-specific affinities | Lowest value for B2B — use only if first-party and in-market signals are insufficient |

**Custom Intent Audience Construction (Highest-Impact Action for B2B PMax):**

Build a custom intent audience using search terms that your ICP types into Google when they're in-market. Sources:
1. Pull your Google Search Ads top-converting search terms from the past 6 months
2. Add competitor brand name searches (e.g., "[Competitor] pricing," "[Competitor] alternative," "[Competitor] reviews")
3. Add solution category searches (e.g., "enterprise data catalog software," "cloud security posture management platform")
4. Add problem-aware searches (e.g., "how to automate compliance reporting," "why is cloud spend growing so fast")
5. Add URL signals: competitor websites, industry analyst sites (Gartner, Forrester), review sites (G2, TrustRadius) relevant to your category

---

## Deliverable 4: Search Theme Configuration

Search themes are the PMax equivalent of keywords—they guide the algorithm toward the search query types you want to capture without locking into specific keyword match types. Configure 7-10 search themes per asset group (maximum 25 per campaign).

**Search Theme Framework by Intent Stage:**

*Branded Defense Themes (prevent PMax from cannibalizing branded search budget — often better handled by standard Search campaigns):*
- [Your Brand Name]
- [Your Brand Name] pricing
- [Your Brand Name] demo
- [Your Brand Name] reviews
- [Your Brand Name] login (existing customer — exclude from acquisition campaigns)

*Category/Solution Themes:*
- [solution category] software/platform/tool
- best [solution category] for [ICP industry]
- [solution category] for [company size, e.g., "mid-market" or "enterprise"]
- [job outcome] platform (e.g., "revenue forecasting platform," "automated compliance reporting")
- [technical capability] solution (e.g., "SOC2 automation," "API security monitoring")

*Problem-Aware Themes:*
- how to [solve specific pain] (e.g., "how to automate SOC2 audits")
- [problem] tool/software (e.g., "manual audit trail software," "disconnected data reporting tool")
- [negative outcome] solution (e.g., "failed compliance audit," "slow onboarding automation")
- [ICP title] + challenge/problem (e.g., "CFO financial close process," "CISO audit management")

*Competitor Conquest Themes (for Campaign A or dedicated conquest asset group):*
- [Competitor A] alternative
- [Competitor A] vs [your brand category]
- [Competitor A] pricing 2025
- switch from [Competitor A]
- [Competitor A] reviews

*Integration/Ecosystem Themes (buyers researching compatible solutions):*
- [your product] [key integration] integration (e.g., "data catalog Salesforce integration")
- [stack technology] [your category] (e.g., "Snowflake data governance platform")

---

## Deliverable 5: Exclusion Framework

**Exclusions are where B2B PMax campaigns win or lose.** Without proper exclusions, PMax will serve ads in mobile games, consumer apps, YouTube channels irrelevant to your ICP, and to searchers with no buying intent.

**Level 1 — Negative Keywords (Apply at Campaign Level):**

*Employment/research intent:*
jobs, careers, hiring, salary, internship, resume, course, certification training, "what is," definition, tutorial (unless you have a free educational offer), university, research paper

*Non-buyer intent:*
free (if enterprise-priced), open source, DIY, self-hosted (if SaaS), crack, torrent, piracy

*Geography signals indicating non-ICP:*
[Countries outside your target market — list specifically; PMax especially over-serves low-CPM geographies if not excluded]

*Consumer/B2C modifiers:*
personal, home, individual, residential, hobby, small business (if targeting mid-market enterprise)

*Competitor employees (prevent wasting budget on competitor HR teams researching your product):*
[Competitor] careers, [Competitor] jobs, [Competitor] engineer, [Competitor] employee

**Level 2 — Placement Exclusions (Apply at Account Level — affects all campaigns):**

Upload placement exclusion list to Google Ads (Account Settings → Placement Exclusions). Key categories to exclude for B2B:
- Mobile gaming apps (Games category in Google Display)
- General entertainment apps (YouTube Music, Google Play Games)
- Children's content (COPPA-covered placements)
- Low-quality content sites (configure via content suitability settings — exclude "Sensitive Social Issues," "Tragedy and Conflict," "Sexually Suggestive" content)

Build a manual placement exclusion list targeting high-volume, low-conversion app placements. After 2 weeks, pull your placement report in Google Ads → filter by placements with 100+ impressions and 0 conversions → exclude systematically.

**Level 3 — Audience Exclusions:**

| Audience to Exclude | Where to Apply | Reason |
|---|---|---|
| Current customers (customer match list) | Campaign A (New Acquisition) | Prevent wasting acquisition budget on existing accounts |
| Employees of your own company | All campaigns | Internal traffic inflates impression share metrics |
| Open opportunities (active pipeline contacts) | Campaign A (New Acquisition) | Route to Campaign B (Retargeting) for appropriate messaging |
| Known non-ICP segments | All campaigns | e.g., if targeting B2B only, exclude consumer affinity audiences |

**Level 4 — Brand Keyword Exclusions (Critical for Running PMax alongside Search Campaigns):**

If you run standard Google Search brand defense campaigns alongside PMax, you MUST exclude your brand keywords from PMax to prevent PMax from cannibalizing your higher-converting, lower-CPC branded search traffic. Apply brand exclusions via the "Brand Exclusions" feature in PMax campaign settings (not the standard negative keyword tool — PMax requires a separate exclusion list for brand terms).

---

## Deliverable 6: Smart Bidding Configuration & Ramp-Up

**B2B PMax Bidding Ladder:**

| Phase | When | Bid Strategy | Target | Notes |
|---|---|---|---|---|
| Launch (0-30 days) | No conversion history | Maximize Conversions (no Target CPA) | No cap initially | Allow algorithm to explore; set a manual daily budget cap instead |
| Ramp (30-60 days) | 30+ conversions recorded | Maximize Conversions with CPA cap | Set CPA cap at 2× your eventual target | CPA cap prevents extreme overpaying while algorithm learns |
| Optimization (60+ days) | 50+ conversions/month | Target CPA | Set at [ACV × acceptable CAC ratio for PMax traffic] | Tighten incrementally — reduce Target CPA by 10-15% every 2 weeks if performance holds |
| Scale (90+ days) | Proven CPA efficiency | Target ROAS (if revenue data available) or sustained Target CPA | ROAS target = [Pipeline value generated / PMax spend] | Requires offline conversion import connecting CRM revenue to Google Ads |

**Target CPA Calculation for B2B:**
- Formula: Target CPA = ACV × Demo-to-Closed-Won Rate × Acceptable Marketing CAC Ratio
- Example: ACV = $48,000 × Demo-to-Closed-Won = 18% × 10% CAC ratio = $864 Target CPA per demo request
- PMax typically delivers 1.3-2× higher CPAs than standard Search for B2B — build this into your Target CPA vs. your Search campaign target CPA

**Important: Do NOT set a Target CPA in the first 30 days.** PMax requires conversion data to calibrate Smart Bidding. Setting a Target CPA too early with insufficient conversion history causes underdelivery (the algorithm constrains spend to avoid exceeding the target before it understands what drives conversions).

---

## Deliverable 7: Asset Performance Monitoring & Optimization Cadence

**Asset Performance Labels (how to read them):**

Google assigns "Best," "Good," "Low," or "Learning" labels to each asset within an asset group based on conversion contribution.

| Label | Action |
|---|---|
| Best | Analyze why it's performing — apply creative insights to new assets across other asset groups |
| Good | Monitor — do not replace; it's contributing positively |
| Low (after 2+ weeks of traffic) | Replace with a new variation — test a different angle, proof point, or format |
| Learning | Wait at least 2 weeks before judging — insufficient impression data |

**Weekly Optimization Tasks:**
1. Review asset performance labels → flag all "Low" assets → queue replacements (write 2-3 alternative headlines/descriptions, source 1-2 new image variants)
2. Pull placement report → exclude placements with 200+ impressions and 0 conversions
3. Review audience insights panel → check if algorithm is finding your target audience segments (compare discovered audience breakdown to ICP definition)
4. Check conversion volume → if <30 conversions in past 30 days, do NOT tighten Smart Bidding targets

**Bi-Weekly Optimization Tasks:**
1. Add new search terms from Insights → Search Themes report (identify high-performing search queries; manually add as new search themes if not already included)
2. Refresh creative assets → add at least 2 new headline variants and 1 new image variation to underperforming asset groups
3. Review Google Recommendations → accept only Recommendations with clear ROI logic; reject budget increase suggestions unless supported by CPA data

**Monthly Optimization Tasks:**
1. Upload updated customer match lists from CRM (new customers, new open opportunities, additional closed-lost re-engagement)
2. Review asset group structure — if an asset group is consistently underperforming in conversions, evaluate whether the audience signal + creative combination is coherent
3. Competitive audit — check if competitor spend on your brand terms has increased (monitor Search Impression Share on brand campaigns running in parallel)

---

## Deliverable 8: Attribution & Pipeline Tracking Setup

**UTM Parameter Structure for PMax:**

PMax does not support keyword-level UTM parameters (unlike standard Search). Configure campaign-level and asset-group-level tracking:

utm_source=google
utm_medium=pmax
utm_campaign=[campaign-name, e.g., "pmax-acquisition-fy25"]
utm_content=[asset-group-name, e.g., "ag-category-buyers" or "ag-competitor-conquest"]

Pass UTM data into CRM via hidden form fields on all landing pages. This enables:
- Lead source attribution: "Google / PMax" appears on CRM Contact record
- Pipeline source tracking: Opportunity created from PMax campaign visible in CRM pipeline reports
- Cohort analysis: Compare PMax-sourced opportunities vs. Search-sourced opportunities on deal velocity, win rate, and ACV

**Offline Conversion Import (Required for Pipeline-Level Optimization):**

PMax's Smart Bidding algorithm improves dramatically when it receives downstream revenue signals (not just form fills). Configure:

1. Google Ads Conversion Actions: Create "Opportunity Created" and "Closed Won" as offline conversion events
2. CRM → Google Ads Integration:
   - Salesforce: Use native Salesforce + Google Ads integration to import offline conversions automatically when Opportunity Stage changes
   - HubSpot: Use Google Ads + HubSpot integration or Zapier to trigger offline conversion API calls when deal stage progresses
3. GCLID capture: Ensure GCLID (Google Click Identifier) is captured and stored on the CRM lead/contact record when a form is submitted — this is required to match offline conversions back to the originating Google Ads click
4. Conversion window: Set offline conversion import window to match your sales cycle (e.g., 90-day window for a 3-month average sales cycle)

**Result:** PMax Smart Bidding begins optimizing toward pipeline creation and revenue signals, not just form submissions — this is the single highest-leverage technical action for B2B PMax performance.

---

## Deliverable 9: 30/60/90-Day Scaling Roadmap

**Days 1-30 — Launch & Data Collection:**
- Week 1: Launch Campaign A with 2-3 asset groups; install conversion tracking, UTM infrastructure, and GCLID capture on all landing pages
- Week 2: Upload first-party audience lists (converter list, website visitors); configure placement exclusion list; add negative keyword list
- Week 3-4: Monitor placement report daily (exclude irrelevant placements); review asset performance labels weekly; build Campaign B (Retargeting) asset groups for activation in Day 31+
- Milestone: 15+ conversions tracked, placement exclusion list established, no brand keyword cannibalization confirmed (compare Search brand campaign metrics to pre-PMax baseline)

**Days 31-60 — Optimization & Audience Signal Expansion:**
- Activate Campaign B (Retargeting) with warm audience signals
- Add CPA cap to Campaign A (set at 2× eventual target CPA)
- Expand asset groups: add customer proof/social proof asset group if testimonial content is available
- Refresh underperforming assets (replace "Low" labeled assets)
- Upload updated CRM lists (new converters, new open opportunities)
- Milestone: 30+ monthly conversions, placement efficiency improving (spending on fewer junk placements), asset group performance differentiation visible

**Days 61-90 — Attribution & Scale:**
- Configure offline conversion import (CRM opportunity created + closed won events imported to Google Ads)
- Switch Campaign A to Target CPA Smart Bidding (set at established CPA from first 60 days × 1.15 buffer)
- Expand search themes based on Insights → Search Themes data
- Launch Campaign C (Customer Expansion) if NRR marketing budget available
- Evaluate incrementality: Run a geo-based holdout test or consult Google for a Conversion Lift study (available for accounts spending $50K+/month on Google)
- Milestone: Offline conversion import live, Target CPA stable, PMax pipeline influence visible in CRM reports, smart bidding receiving revenue signals

---

## Example Input/Output

**Input:**
- Company: Meridian — cloud-based fleet management platform
- ICP: VP of Operations and Fleet Managers at 150-2,000 employee logistics, transportation, and field services companies
- ACV: $42,000
- Sales cycle: 3-4 months
- PMax Budget: $22,000/month (total Google Ads: $75,000/month including Search)
- Pipeline goal: $900,000 sourced pipeline over 90 days
- Competitors: Samsara, Verizon Connect, Azuga
- Primary conversion: Demo request
- Existing assets: 2 customer testimonial videos (60 sec), G2 Leader badge, 8 customer logos

**Output excerpt:**

**Campaign A — New Customer Acquisition**
Budget: $14,000/month | Smart Bidding: Maximize Conversions (Days 1-45) → Target CPA $1,890 (Days 45+)
Target CPA calculation: $42,000 ACV × 22% demo-to-close rate × 20% CAC ratio = $1,848 → rounded to $1,890

**Asset Group 2: Problem-Aware Fleet Managers**
Audience signals: Custom intent audience built from search terms ("reduce fleet fuel costs," "GPS fleet tracking ROI," "how to reduce driver overtime," "fleet compliance violations"), in-market for Fleet Management Software, website visitors of Samsara.com and VerizonConnect.com (URL signals)

Sample Headlines:
1. Fleet Fuel Costs Eating Margins? (H1 pinned)
2. Cut Fleet Costs 31% on Average (H2 pinned)
3. GPS + Compliance + Dispatch in One
4. See 20-Min Demo — No Commitment
5. Trusted by 900 Logistics Companies
6. Samsara Alternative — See Comparison
7. Reduce Driver Hours With Route AI
8. G2 Leader — Fleet Management 2025
9. Deploy in Days — Not Months
10. Integrates With Your ERP or TMS
11. FMCSA Compliance Automation Built In
12. Switch From Verizon Connect in 30 Days
13. Free ROI Analysis for Your Fleet
14. No Hardware Costs — 100% Software
15. 24/7 Support — Average 4-Minute Response

Descriptions:
- D1: Fleet managers at logistics companies cut fuel costs 31% and driver overtime by 19% with Meridian. GPS tracking, route optimization, and FMCSA compliance automation in one platform. Book your 20-min demo.
- D2: Unlike Samsara and Verizon Connect, Meridian deploys in 5 business days with no hardware installation. Rated #1 for ease of use on G2. 900+ fleets trust us. See a live demo of your use case today.

**Offline conversion import result (simulated after 60 days):**
- PMax conversions: 31 demo requests
- CRM-matched opportunities: 22 created (71% lead-to-opportunity rate)
- Smart Bidding signal: $462,000 pipeline value imported as offline conversions
- Result: Algorithm shifted budget toward asset groups and search themes correlated with high-ACV opportunities; CPA decreased 18% over subsequent 30 days

---

## Success Metrics

**Campaign Health:**
- Conversion Tracking Coverage: 100% of form submits captured with GCLID within first 14 days
- Brand Cannibalization: Branded Search campaign CTR and CPC stable within ±10% vs. pre-PMax baseline (PMax not stealing brand traffic)
- Placement Quality: <15% of spend on mobile app placements after exclusion list applied (pull from placement report)
- Asset Performance Distribution: ≥50% of assets rated "Good" or "Best" at 30 days; no more than 30% rated "Low"

**Performance:**
- Target CPA Achievement: Within 25% of Target CPA within 60 days; at or below target by Day 90
- Conversion Volume: ≥30 primary conversions/month (threshold for effective Smart Bidding)
- Demo-to-Opportunity Rate: ≥40% (measure in CRM — PMax-sourced demos should match Search-sourced quality if audience signals are configured correctly)

**Pipeline:**
- PMax-Sourced Pipeline: Track pipeline tagged "Google / PMax" in CRM; compare pipeline contribution to budget share vs. standard Search campaigns
- Pipeline Quality Benchmark: PMax-sourced opportunities should achieve ≥80% of the win rate and ACV of Search-sourced opportunities (lower indicates poor audience signal quality — revisit custom intent audiences)
- Offline Conversion Import: ≥60% of CRM opportunities from PMax-sourced leads have GCLID matched (critical for Smart Bidding revenue optimization)

---

## Related Prompts

- [AI-Powered B2B Google Search Ads Demand Capture & High-Intent Buyer Acquisition Intelligence Engine](./AI-Powered-B2B-Google-Search-Ads-Demand-Capture-&-High-Intent-Buyer-Acquisition-Intelligence-Engine.md)
- [AI-Powered B2B Full-Funnel Paid Media Campaign Architecture & Budget Velocity Intelligence Engine](./AI-Powered-B2B-Full-Funnel-Paid-Media-Campaign-Architecture-&-Budget-Velocity-Intelligence-Engine.md)
- [AI-Powered B2B LinkedIn Ads Campaign Architecture & Pipeline Revenue Intelligence Engine](./AI-Powered-B2B-LinkedIn-Ads-Campaign-Architecture-&-Pipeline-Revenue-Intelligence-Engine.md)
- [ABM Intent Data Activation & Buying Signal Prioritization Engine](../Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md)

---

## Integration Tips

**HubSpot:**
- Install native Google Ads integration in HubSpot → auto-syncs GCLID and UTM data to Contact records on form submit
- Configure HubSpot Workflow: When Contact Source = "Google / pmax" AND Lifecycle Stage moves to "Opportunity" → trigger Slack notification to SDR team + enroll in accelerated 5-email nurture sequence
- Use HubSpot's Revenue Attribution report → filter by "First touch = Google PMax" to track pipeline and closed revenue attribution over 90-180 day windows
- For offline conversions: Use HubSpot → Google Ads integration (native) to automatically send "Deal Created" and "Deal Won" events as offline conversions when HubSpot deal stage changes

**Salesforce:**
- Use the Salesforce + Google Ads native connector for offline conversion import: map Opportunity Stage = "SQL" → "Opportunity Created" offline conversion; Opportunity Stage = "Closed Won" → "Revenue" offline conversion
- Build Salesforce Campaign records for each PMax asset group → assign Campaign Member records for all Contacts who converted from PMax → enables Campaign Influence reporting across multi-touch attribution models
- Create a Salesforce Dashboard widget: "Pipeline by Google Ads Type" — compare PMax-sourced vs. Search-sourced pipeline on ACV, win rate, and sales cycle length to validate PMax audience signal quality

**Google Analytics 4 (GA4):**
- Link GA4 to Google Ads → enables audience sharing (send GA4 behavioral segments as audience signals to PMax)
- Create GA4 Audience: "High-Intent Visitors" = users who viewed Pricing page AND at least one Product page in same session → sync to Google Ads as audience signal for Campaign A
- Monitor GA4 Landing Page report for PMax traffic → compare bounce rate, pages/session, and goal completions for PMax vs. Search traffic to detect if PMax is bringing low-quality visitors
- Use GA4 Path Exploration: trace PMax-sourced sessions through the conversion funnel — identify if users are dropping at a specific page (indicates landing page mismatch)

**Zapier / Make (Automation):**
- Trigger: New PMax lead form conversion event in Google Ads → Zap → Create HubSpot Contact + Assign SDR + Send qualified lead alert to Slack #inbound-leads channel
- Trigger: CRM deal stage = "Closed Won" with source = "Google PMax" → Zap → Send offline conversion event to Google Ads Conversions API (for CRMs without native Google Ads integration)
- Trigger: Weekly Monday 8am → Zap → Pull Google Ads placement report via API → Append new placements with 0 conversions to Google Sheet → Alert paid media manager to add placements to exclusion list

**6sense / Bombora / G2 Buyer Intent:**
- Export accounts in "Active Buying Stage" from 6sense → upload email list to Google Ads as Customer Match audience → add as Tier 1 audience signal in PMax Campaign A to concentrate budget on accounts already showing intent
- Sync Bombora intent surge accounts to Google Ads Customer Match weekly via Zapier → as accounts enter intent surge for your category, they automatically become PMax audience signals
- Use G2 buyer activity data (available for G2 enhanced profiles) → export email list of G2 category page visitors → upload as Customer Match signal in PMax (these buyers are actively comparing vendors)

---

## Troubleshooting

**Problem: PMax is spending almost exclusively on branded search terms, cannibalizing existing branded Search campaigns and producing inflated conversion numbers**

Solution: This is one of the most common B2B PMax issues. Google's algorithm rapidly learns that branded searches convert at high rates and over-invests there. Fix via two actions: (1) Apply brand exclusions in PMax campaign settings — use the "Brand Exclusions" feature (not standard negative keywords; PMax requires a separate brand exclusion list) to prevent PMax from bidding on your brand name and its close variants. (2) Verify your branded Search campaign is still running alongside PMax — branded Search campaigns should always run in parallel to capture brand intent at lower CPCs and with more messaging control than PMax provides.

**Problem: PMax campaign is underdelivering — spending only 40-60% of daily budget and conversion volume is low**

Solution: Underdelivery in PMax typically has one of three causes: (a) Target CPA set too low relative to what the algorithm can achieve with current conversion volume — if you set a Target CPA in the first 30 days before 30+ conversions are recorded, the algorithm will underspend rather than risk exceeding the target. Remove the Target CPA temporarily and run Maximize Conversions until 30+ conversions/month are achieved, then reintroduce a CPA cap at 2× your target. (b) Audience signals too narrow — if your Customer Match lists are small (< 1,000 records) and you have no other signals, the algorithm has limited data to learn from. Expand audience signals with in-market and custom intent audiences. (c) Negative keyword or placement exclusion list too aggressive — review for false positives; if you excluded too many relevant search themes or placements, the algorithm cannot find sufficient inventory.

**Problem: PMax asset groups are generating conversions but CRM shows these leads are low quality — wrong industry, wrong company size, or individual buyers instead of business buyers**

Solution: Audience signal quality is the root cause. The algorithm found a pattern that produces form submissions but not qualified pipeline. Take three actions: (1) Upload a suppression list of known non-ICP accounts and individuals (e.g., small business owners, students, non-target industries from your CRM disqualification data) as Customer Match exclusion audiences. (2) Rebuild your custom intent audience — remove any broad or consumer-oriented search terms and tighten to enterprise-specific, B2B-only phrases (e.g., replace "project management software" with "enterprise project management platform for teams over 100" or "PMO software for construction"). (3) If offline conversion import is live, ensure it's properly assigning conversion value: a "Qualified Opportunity" event should carry $X value while a disqualified lead carries $0 — this teaches Smart Bidding to optimize toward pipeline-generating signals, not all form fills equally.

---

## Version History
- v1.0: Initial creation (auto-generated)
