# AI-Powered B2B SaaS On-Demand Webinar Library Analytics & Evergreen Content Performance Revenue Intelligence Engine — Measure How Your Webinar Archive Drives Pipeline Months After the Live Event

**Difficulty:** Advanced | **Time:** 30-40 min | **Tags:** webinar-analytics, on-demand-content, content-decay, evergreen-content, revenue-attribution, pipeline-measurement, B2B SaaS, content-library, long-tail-demand, demand-generation

## Overview

Builds a comprehensive analytics system for your on-demand webinar content library — measuring how recorded webinar content continues to generate views, pipeline, and revenue weeks, months, and years after the original live broadcast. Use this when you have an archive of 20+ recorded webinars with no visibility into which recordings are still driving buyer engagement, which have decayed into irrelevance, and whether your on-demand library constitutes a compounding demand generation asset or a storage cost center.

## Quick Copy-Paste Version

You are a B2B SaaS content analytics architect specializing in on-demand webinar library performance and post-event revenue attribution. Build a complete analytics system for measuring and optimizing our on-demand webinar content library.

COMPANY CONTEXT:
- Company: [e.g., "Vaultline — AI-powered financial close automation for mid-market CFOs"]
- On-demand webinar library size: [e.g., "63 recorded webinars across 4 series, published over 36 months"]
- Webinar hosting/delivery: [e.g., "Wistia for on-demand hosting, YouTube for organic discovery, website for embedded player"]
- Registration/MAP: [e.g., "HubSpot — gate all on-demand via form on the webinar replay page"]
- CRM: [e.g., "Salesforce"]
- Current on-demand analytics: [e.g., "Wistia play rate, total views — no pipeline attribution, no contact-level view tracking"]
- Average monthly on-demand viewers: [e.g., "~1,400 views/month across the library, gated replay completions ~210/month"]
- Key problem: [e.g., "We produce 3 webinars/month but have no idea which of our 63 recordings still drive pipeline and which are wasting production resources to keep updated"]

OUTPUT REQUIRED:
1. ON-DEMAND ATTRIBUTION MODEL — A methodology for connecting on-demand webinar views to pipeline creation and pipeline influence, accounting for longer consideration windows (90–180 days) compared to live event attribution. Include the exact CRM field mapping and attribution window logic.
2. CONTENT DECAY ANALYSIS FRAMEWORK — A scoring system to classify each webinar recording as Evergreen (maintains consistent views and conversion), Decaying (views declining quarter-over-quarter), or Stale (minimal views, obsolete topic or technology references). Include a monthly decay score calculation that runs autonomously against your video analytics data.
3. EVERGREEN CONTENT IDENTIFICATION — Define the content characteristics that predict on-demand longevity: topic freshness windows, production format signals, ICP relevance durability, and competitive landscape sensitivity.
4. CUMULATIVE AUDIENCE METRICS DASHBOARD — A reporting structure for tracking total cumulative views, unique viewer-companies, watch-time distribution (average % of recording watched), and gate conversion rate for each recording and for the library as a whole.
5. CONTENT REFRESH VS. RETIRE DECISION ENGINE — An AI-executable scoring model that evaluates each recording on 6 dimensions (monthly views trend, pipeline contribution, topic relevance, production quality, gate conversion rate, competitive accuracy) and outputs a quarterly recommendation: Refresh, Repromote, Update, or Retire.
6. ON-DEMAND SEO AND DISCOVERABILITY ANALYTICS — Tracking organic search traffic to on-demand pages, YouTube search-driven views, and how replays perform as SEO assets for your target buyer search terms.

Output as a fully implementable analytics system with specific metric calculations, CRM workflow templates, and a 90-day implementation roadmap.

## Advanced Customizable Version

ROLE: You are a B2B SaaS content analytics architect with 14+ years of experience managing webinar content libraries and demand generation programs at companies ranging from $15M to $400M ARR. You have built on-demand webinar measurement systems that identified $2.8M in hidden pipeline influenced by webinar replays that standard live-event attribution had completely missed, designed content decay models that helped marketing teams cut their active webinar library from 120 to 38 recordings while increasing total monthly on-demand views by 40%, and built replay attribution workflows that traced replay views from anonymous website session to closed-won Salesforce opportunity. You think about webinar content like a fund manager thinks about a portfolio: individual assets have different performance characteristics, lifecycle stages, and compounding properties — and the goal is maximizing total portfolio return, not just the most recent addition. Your operating principle: an on-demand webinar library should function as a compounding demand generation asset, not a digital storage unit.

OBJECTIVE: Design a production-ready on-demand webinar library analytics system that:
- Measures each recording's true contribution to pipeline creation and pipeline influence over its full lifetime (not just the 30-day post-live attribution window most webinar analytics tools use by default)
- Identifies which webinar topics and formats have genuine evergreen value vs. which have decayed below the investment threshold of maintenance, promotion, or refresh
- Provides the content and demand generation team with a monthly prioritization list: which recordings to actively promote, which to refresh, and which to retire
- Builds attribution visibility at the individual viewer-company level: which named accounts have been watching replay content, creating invisible buying signals your SDR team is currently missing
- Produces a board-ready on-demand library ROI model: total pipeline influenced by the library this quarter, cost per view, cost per gate conversion, and revenue per dollar of webinar production investment

---

COMPANY AND LIBRARY PROFILE:

Provide the following to customize the analytics system architecture:

Company and ICP:
- Company name and product: [name | one-sentence outcome-focused description | primary buyer persona with title and company profile]
- ARR, growth rate, and average ACV: [$ARR | % YoY growth | $ACV | typical sales cycle in months]
- Primary buyer journey stage where webinar content appears: [are buyers typically watching replays during awareness, consideration, or evaluation? Or all stages depending on content type?]

On-Demand Library Profile:
- Total recorded webinars in active library: [count] 
- Library age — oldest recording: [date of first recording]
- Webinar types in library: [list all formats — e.g., thought leadership panels, product demos, customer success stories, joint partner webinars, competitive displacement content, training/education series]
- Average recording length: [minutes — note: average completion rate drops 15% for every 10 minutes of content beyond 30 minutes]
- Gate status: [All gated / Mix — which formats are gated vs. ungated / All ungated]
- Primary gate form fields: [what data you collect when someone accesses a replay]
- Monthly on-demand view volume: [total views per month across all recordings]
- Top-performing recording by views: [title + monthly view count — anchor for benchmarking]

Technology Stack:
- Video hosting platform: [Wistia / Vidyard / Vimeo / YouTube / Brightcove / ON24 On-Demand — critical because analytics API availability varies significantly]
- Website CMS: [WordPress / Webflow / HubSpot CMS / custom — determines how video embed tracking is configured]
- MAP/CRM integration: [HubSpot / Marketo / Pardot → Salesforce / HubSpot CRM — determines lead capture and attribution workflow]
- Web analytics: [GA4 / Adobe Analytics / Segment — for page-level traffic attribution]
- Current revenue attribution model: [none / last-touch / first-touch / multi-touch linear / W-shaped / custom]
- Intent data provider (if any): [6sense / Bombora / Demandbase — determines whether you can correlate on-demand views with third-party intent signals]

Business Goals:
- Primary question you need answered: [e.g., "Which of our 63 recordings should we actively promote via email campaigns and paid retargeting, vs. which have become outdated noise?"]
- Secondary question: [e.g., "How do we quantify the pipeline value of our on-demand library to justify continuing to produce 3 new webinars per month?"]
- Budget decisions the analytics will inform: [e.g., "Whether to invest in refreshing our 2023 product demo series or retire and replace"]

---

DELIVERABLE 1: ON-DEMAND WEBINAR VIEW ATTRIBUTION MODEL

A. WHY ON-DEMAND ATTRIBUTION REQUIRES DIFFERENT LOGIC THAN LIVE EVENT ATTRIBUTION

Live webinar attribution is primarily a 30–90 day lookback from the event date: did the attendee enter the pipeline within 90 days of attending? On-demand content operates differently:

1. LONGER CONSIDERATION WINDOWS: A buyer who watches your 2023 "State of RevOps" panel in month 1 of their evaluation, then proceeds through three more months of consideration before requesting a demo, would be missed by a 30-day attribution window. On-demand content attribution requires a 180-day lookback minimum.

2. ANONYMOUS-TO-KNOWN CONVERSION LAG: Many on-demand views happen anonymously (ungated pages, pre-gate video plays). The viewer becomes known only when they gate in months later. The attribution chain must trace backward from gate completion through anonymous session history using session stitching.

3. MULTI-TOUCH NATURE: On-demand webinars rarely create pipeline directly. They function as consideration-stage trust builders — a buyer who has watched 4+ hours of your webinar content before requesting a demo is qualitatively different from a cold inbound lead. The analytics must surface this "webinar consumption depth" as a pipeline quality signal, not just a binary touchpoint.

4. CONTENT COMPOUNDING: A well-performing on-demand recording accumulates pipeline influence over 24–36 months. Its total lifetime contribution is 5–10x its first-month contribution. Attribution models that only measure webinar ROI at 30 days systematically undervalue on-demand content.

B. ON-DEMAND ATTRIBUTION MODEL ARCHITECTURE

Step 1 — Session-to-Contact Identification (Requires: Video hosting analytics + MAP pixel or reverse IP):

For ungated replay pages:
- Install your MAP tracking pixel (HubSpot tracking code / Marketo Munchkin) on every webinar replay page
- Configure GA4 to capture video engagement events (play, 25%, 50%, 75%, 100% completion) alongside the MAP session
- When a visitor who previously watched an ungated replay later completes a gate (on any form), MAP will stitch the pre-form session history to the known contact, retroactively attributing the replay view

For gated replay pages:
- All views are attributed at gate completion — this is simpler but forces a conversion event earlier in the buyer journey
- Recommended: use a progressive gate strategy — ungated first 15 minutes, gated for full access — to capture identity at a less-friction point while preserving top-of-funnel consumption data

Named Account Identification (for ungated views):
- Integrate your video hosting platform with a reverse IP enrichment tool (Clearbit, 6sense, Demandbase) to identify the company of anonymous viewers even before gating
- Even without individual-level identity, company-level viewing data ("accounts from Salesforce watching this recording 3+ times") creates ABM activation signals

Step 2 — CRM Attribution Field Mapping:

Contact-level fields (populate when a known contact views or gates a replay):
- "On-Demand Webinar Viewed" (multi-select): [Recording title(s) viewed by this contact]
- "Total On-Demand Watch Time" (number): [Cumulative minutes watched across all recordings]
- "On-Demand Webinar Last View Date" (date): [Most recent replay view timestamp]
- "Webinar Series Completed" (boolean per series): [Has this contact watched ≥ 70% of a specific series?]
- "On-Demand View Count" (number): [Total number of individual recordings this contact has viewed]
- "On-Demand Gate Date" (date): [Date of first gate completion for on-demand content]

Opportunity-level fields (populate via workflow when opportunity is created or advances):
- "On-Demand Webinar Influenced" (boolean): [Did any contact on this opportunity view a replay within 180 days of opportunity creation?]
- "On-Demand Webinar Titles Viewed" (multi-select): [List of recordings viewed by buying committee members]
- "Total On-Demand Watch Time — Buying Committee" (number): [Sum of all minutes watched by all opportunity contacts]
- "On-Demand First Touch" (date): [Date of first replay view by any opportunity contact]

Attribution logic:
- Pipeline Sourced (On-Demand): Opportunity created within 30 days of a contact's first on-demand gate completion, and on-demand view was the first tracked marketing touchpoint
- Pipeline Influenced (On-Demand): Any opportunity contact viewed ≥ 1 replay within 180 days before or after opportunity creation date
- Pipeline Accelerated (On-Demand): Opportunity stage advanced within 14 days of a contact's on-demand viewing session — use stage change timestamp vs. video view timestamp

Step 3 — Cohort Analysis by Recording:

For each recording in your library, build a 180-day post-publish cohort:
- Month 0 (live event): Live attendees → pipeline created within 90 days
- Months 1–6 (early on-demand): Views within 6 months of recording → pipeline created within 180 days
- Months 7–18 (mid-life on-demand): Views between 6–18 months post-record → pipeline influenced (not sourced — this content is pure top/mid-funnel influence at this stage)
- Months 18+ (evergreen on-demand): Views 18+ months post-record → pipeline influenced + brand consideration signals

This cohort view transforms your on-demand library from "a pile of old videos" into a multi-stage demand generation asset with quantifiable lifetime value.

---

DELIVERABLE 2: CONTENT DECAY ANALYSIS FRAMEWORK

A. DECAY METRICS AND SCORING

For each recording in your library, calculate the following metrics monthly:

Monthly View Volume: Total views in the current calendar month
Quarterly View Trend: (Current month views / Average monthly views in same quarter last year) - 1
Gate Conversion Rate: Gates completed / Total replay page sessions × 100
Watch Completion Rate: Average % of recording viewed per session (from video hosting analytics)
Pipeline Conversion Rate: Opportunities influenced / Gates completed × 100 (trailing 180 days)
Content Freshness Score (manual, quarterly): Rate 1–5 on:
  - Product accuracy: Does the product shown match current product (UI, feature set, pricing)?
  - Market accuracy: Does the competitive landscape referenced reflect today's market?
  - Data accuracy: Are any statistics, benchmarks, or market data current (within 2 years)?
  - Persona accuracy: Is the ICP or buyer persona still the primary target?

B. DECAY CLASSIFICATION RULES

EVERGREEN (Score: High Perform, Low Decay):
- Monthly views stable or growing (quarterly trend ≥ -10%)
- Gate conversion rate ≥ library average
- Watch completion rate ≥ 45%
- Content freshness score ≥ 4/5
- Action: Actively promote — this recording compounds in value. Allocate paid retargeting budget. Feature in nurture email sequences. Create derivative content (blog, social clips) to drive discovery.

STEADY-STATE (Score: Average Perform, Low Decay):
- Monthly views within ±25% of library average
- Gate conversion rate near library average
- Content freshness score ≥ 3/5
- Action: Maintain current distribution. Review content freshness annually. Candidate for topic repurposing but not active promotion investment.

DECAYING (Score: Declining Perform):
- Monthly views declining ≥ 20% quarter-over-quarter for two consecutive quarters
- OR content freshness score ≤ 2/5 on any single dimension
- Action: Evaluate for Refresh or Retire. Do not invest in promotion. Flag for quarterly review with content brief recommendations.

STALE (Score: Minimal Views + Low Freshness):
- Monthly views below 15% of library median for 3+ consecutive months
- AND content freshness score ≤ 2/5 on any dimension
- Action: Retire (unpublish or password-protect). Create a redirect from the replay page to the most relevant current recording. Alert any active CRM nurture sequences that link to this recording to swap the link.

C. AUTOMATED MONTHLY DECAY REPORT

Run this AI prompt monthly against your video analytics export and CRM pipeline data:

"You are a content analytics engine for our B2B SaaS webinar library. Using the attached data exports — [Video Analytics CSV: recording title, monthly views, avg completion rate, gate conversion rate] and [CRM Pipeline Data: opportunities influenced by webinar title, date, value] — classify each of our [N] webinar recordings into one of four categories: Evergreen, Steady-State, Decaying, or Stale. Apply the following scoring rules: [paste scoring rules from Deliverable 2B]. Output a ranked table: Evergreen recordings sorted by total lifetime pipeline influenced; Decaying recordings sorted by urgency of review; Stale recordings recommended for retirement. For each Decaying recording, identify the most likely decay driver: topic obsolescence, competitive positioning change, production format aging, or traffic source decline. For each Stale recording, generate a one-sentence retirement announcement for our internal content calendar."

---

DELIVERABLE 3: EVERGREEN CONTENT PREDICTOR

A. CONTENT CHARACTERISTICS THAT PREDICT ON-DEMAND LONGEVITY

High Evergreen Potential (at production time):
- Topic framing around enduring problems, not product features ("How Finance Teams Eliminate Manual Reconciliation" outlasts "New Features in Vaultline 2.3")
- Framework or methodology content (reusable mental models have longer shelf life than tactical how-tos that change with platform updates)
- Customer story format (specific ROI stories age more slowly than competitive comparison content)
- Foundational category education ("What is Revenue Operations" ages more slowly than "Revenue Operations Trends for 2024")
- Third-party speaker credibility (analyst, customer, or industry expert content ages more slowly than vendor-only content — the speaker's authority outlasts the product specifics)

Low Evergreen Potential (signals to watch):
- Product screenshots or demos (UI changes in 12–18 months, making recordings feel dated)
- Competitive comparison content (competitive landscape shifts quarterly — content mentioning specific competitors by name decays rapidly)
- Trend prediction content (becomes empirically testable and often wrong within 24 months)
- Pricing or packaging references (any pricing mentioned will be wrong within 24 months for most SaaS companies)
- Regulatory or compliance content (changes frequently in most industries)

B. PRODUCTION FORMAT SIGNALS FOR LONGEVITY

Formats with highest evergreen ratio (based on B2B SaaS library benchmarks):
- Customer panel discussions: 24–36 month average longevity before decay to Stale
- Framework/methodology deep-dives: 18–30 month longevity
- Research report presentations (proprietary data): 12–18 month longevity (data feels old after 18 months)
- Product demo webinars: 6–12 month longevity (UI changes within 12 months)
- Competitive displacement webinars: 6–9 month longevity (competitive landscape shifts)
- Joint partner webinars covering partner product integrations: 6–9 month longevity (integration features evolve)

C. EVERGREEN PREDICTION MODEL (PRE-PRODUCTION CHECKLIST)

Before producing a new webinar, evaluate its predicted evergreen score:

Question 1: Does the title/topic avoid product version numbers, competitor names, and calendar year references? [Yes = +2 / No = 0]
Question 2: Is the primary speaker an external customer, analyst, or industry expert (not only internal) [Yes = +2 / No = 0]
Question 3: Does the content teach a framework or methodology that applies regardless of which vendor a buyer chooses? [Yes = +2 / No = 0]
Question 4: Is the production format one of the three highest-longevity formats (customer panel, framework deep-dive, proprietary research)? [Yes = +2 / No = 0]
Question 5: Does the content avoid product screenshots that will be outdated within 12 months? [Yes = +1 / Partial = 0 / No = -1]

Score interpretation:
- 8–9: High evergreen potential — invest in extended promotion plan, plan 24-month active distribution lifecycle
- 5–7: Moderate evergreen potential — plan 12–18 month active distribution lifecycle, schedule freshness review at month 12
- 0–4: Low evergreen potential — plan 6–9 month active distribution lifecycle, schedule retirement evaluation at month 9

---

DELIVERABLE 4: CUMULATIVE AUDIENCE METRICS DASHBOARD

A. LIBRARY-LEVEL KPIs (Monthly and Trailing 12-Month)

Total Monthly On-Demand Views: Sum of all views across all recordings in the current month
- Benchmark target for B2B SaaS: 10–25 monthly views per webinar in the active library; below 5 views/webinar/month signals library is too large relative to promotion investment

Unique Viewer-Companies (Monthly): Count of distinct company domains identified via gate data or reverse IP enrichment
- This is your "account awareness" number — the on-demand library's equivalent of LinkedIn Ads reach for your ICP

Gated Replay Conversion Rate (Monthly): Gate completions / Replay page sessions × 100
- Industry benchmark for B2B SaaS on-demand content: 12–22% gate conversion on replay pages with a professional gate form (first name, last name, work email, company) — below 10% signals either gate friction (too many fields) or content relevance mismatch (wrong buyers arriving at the page)

Average Watch Completion Rate (Library-Wide): Average % of recording watched per view session across all recordings
- Benchmark: 38–55% average completion across the library (sessions where viewers watch less than 20% should be classified as "abandonment" and excluded from the gate completion denominator)

On-Demand Pipeline Influence Rate: Opportunities with on-demand touchpoint / Total opportunities created × 100
- For companies with active on-demand libraries, 15–30% of total opportunities should show at least one on-demand webinar view in the 180-day attribution window

B. RECORDING-LEVEL DASHBOARD (Reported Monthly)

For each recording, report:
- Recording Title and Series Name
- Publish Date and Age in Months
- Decay Classification (Evergreen / Steady-State / Decaying / Stale)
- Monthly Views (current month)
- Monthly Views Trend (vs. 3-month average)
- Gate Conversion Rate (current month)
- Watch Completion Rate (current month average)
- Pipeline Influenced — Last 90 Days ($ value)
- Pipeline Influenced — Lifetime ($ value)
- Content Freshness Score (manual, quarterly)
- Recommended Action (Promote Actively / Maintain / Refresh / Retire)

C. SERIES-LEVEL CUMULATIVE ANALYTICS

For webinar series (3+ recordings on a connected topic):
- Total Series Views: Cumulative views across all recordings in the series (lifetime)
- Series Completion Rate: % of viewers who watched ≥ 50% of all episodes in the series
- Average Time Between Episodes Consumed: Median days between viewing episode 1 and episode 2 (indicates binge behavior vs. episodic viewing — binge viewers have 2.3× higher pipeline conversion rate than episodic viewers in most B2B SaaS programs)
- Series "Gateway Recording": Which episode of the series generates the highest new viewer acquisition? (Often not Episode 1 — frequently the most SEO-discoverable episode or the one promoted most recently)
- Pipeline Influenced per Series Episode: Rank episodes by pipeline contribution to identify which content drives most commercial intent

---

DELIVERABLE 5: ON-DEMAND CTA PERFORMANCE ANALYTICS

A. CTA TYPES AND PLACEMENT IN ON-DEMAND CONTENT

Most on-demand webinars include one or more calls to action within the recording and on the replay page. Measure each independently:

In-Video CTAs (Mid-Roll and End-Roll):
- Demo Request CTA: Typically placed at 75–85% of recording completion (when viewer has consumed enough value to convert)
- Resource Download CTA: Typically placed at 40–60% completion alongside a relevant offer
- Next Episode CTA (for series): Placed at 90–100% completion to extend session time on page
- Measure: Click rate on in-video CTA / viewers who reached that completion percentage

Replay Page CTAs (Sidebar, Header Banner, Exit Intent):
- Demo Request Banner: Measure clicks relative to replay page sessions
- Related Content Module: Measure click-through rate to related webinars or resources
- Consultation Offer: For high-ACV products, a "Talk to a specialist about [topic]" CTA
- Measure: Click rate per 100 replay page sessions; conversion from click to CRM lead

Gate Form as CTA (for gated replays):
- Gate form itself is the primary conversion action
- Measure: Gate start rate (how many visitors begin filling the form) vs. Gate completion rate (how many submit)
- Gate abandonment patterns: If gate start rate is high but completion is low, reduce form fields or change the value proposition

B. CTA PERFORMANCE ANALYSIS PROMPT

Run quarterly: "You are an on-demand content conversion rate optimizer. Using the attached data — [CTA click rates by recording, completion rate percentages, gate conversion data, pipeline creation within 30 days of CTA click] — analyze CTA performance across our on-demand webinar library. Identify: (1) Which CTA placements (mid-video vs. end-video vs. page CTA) drive the highest pipeline conversion per click, (2) Which recording types (customer stories vs. thought leadership vs. product demos) have the highest CTA click rates, (3) Which CTA copy variants (comparing our 3 current copy approaches) produce the highest gate completion and pipeline conversion. Output a prioritized A/B test roadmap for improving overall on-demand CTA conversion rate by 30% in the next 90 days, with specific test variants ranked by expected impact."

---

DELIVERABLE 6: CONTENT REFRESH VS. RETIRE DECISION ENGINE

A. SCORING MODEL (Run Quarterly for Each Recording)

Score each recording 1–5 on six dimensions:

Dimension 1 — Monthly Views Trend (automated from analytics):
5: Views growing ≥ 10% quarter-over-quarter
4: Views stable (±10%)
3: Views declining 10–25% quarter-over-quarter
2: Views declining 25–50%
1: Views declining >50% or below 5 views/month

Dimension 2 — Pipeline Contribution (automated from CRM):
5: Influenced ≥ 3 opportunities in the last 90 days
4: Influenced 1–2 opportunities
3: Influenced 0 opportunities but ≥ 5 gate completions with ICP contacts
2: Influenced 0 opportunities, <5 gate completions
1: No gate completions in 90 days

Dimension 3 — Topic Relevance (manual, quarterly):
5: Topic is highly relevant to current ICP pain points, no changes needed
4: Topic is relevant, minor updates would strengthen it
3: Topic is relevant but competitive landscape section outdated
2: Topic is partially outdated — product or market references stale
1: Topic is no longer relevant to current ICP or positioning

Dimension 4 — Production Quality (manual, annual):
5: Audio/video quality professional, no technical issues
4: Minor quality issues that don't affect comprehension
3: Moderate quality issues (outdated slide design, background quality) but content is strong
2: Quality issues detract from credibility
1: Poor quality — would be rejected if submitted to a modern review

Dimension 5 — Gate Conversion Rate vs. Library Average:
5: Gate conversion rate ≥ 150% of library average
4: 100–150% of library average
3: 75–100% of library average
2: 50–75% of library average
1: Below 50% of library average

Dimension 6 — Competitive Accuracy (manual, quarterly):
5: No competitor references, or all references accurate
4: Minor inaccuracies in competitive claims (pricing, feature parity)
3: Some competitive claims outdated — could mislead buyers
2: Significant competitive inaccuracies
1: Competitive section contradicts current sales positioning

B. DECISION MATRIX

Weighted Score Calculation:
- Views Trend: 25% weight
- Pipeline Contribution: 30% weight
- Topic Relevance: 20% weight
- Production Quality: 10% weight
- Gate Conversion Rate: 10% weight
- Competitive Accuracy: 5% weight

Total Weighted Score Thresholds:
- 4.0–5.0: ACTIVELY PROMOTE — Feature in email campaigns, paid retargeting, SDR sequences, and content partner distribution
- 3.0–3.9: MAINTAIN — Keep active, periodic promotion via evergreen email sequences and website discovery
- 2.0–2.9: REFRESH — Update competitive section and product screenshots; re-promote after refresh with a "new and updated" message to increase email engagement rate
- 1.0–1.9: RETIRE — Unpublish within 60 days; redirect URL to most relevant current recording; update any active email links or SDR sequences that reference this URL

C. REFRESH BRIEF TEMPLATE

When a recording scores in the REFRESH range, generate a brief:

Recording: [Title]
Current Score: [X.X / 5.0]
Decay Dimensions: [List dimensions scoring ≤ 2]
Recommended Refresh Scope: 
- [ ] Update product screenshots/UI references: [specific timestamps in recording to re-record or overlay]
- [ ] Update competitive claims: [specific slide or timestamp]
- [ ] Add current statistics/data: [specific claims that need source refresh]
- [ ] Re-record introduction (if branding or messaging has changed): [first N minutes]
- [ ] Update replay page copy and meta description for SEO
- [ ] Re-promote as "Updated" with email to prior viewers and gate completers
Estimated Production Effort: [Low: <2 hours / Medium: 2–8 hours / High: 8+ hours — full re-record recommended]

---

## Example Input/Output

**Input Example:**
Company: Vaultline — AI-powered financial close automation for mid-market CFOs
On-demand library: 63 recordings across 4 series, oldest from March 2023
Video hosting: Wistia (with heatmap analytics) — all replays gated after first 10 minutes
MAP/CRM: HubSpot + Salesforce
Monthly on-demand views: 1,620 total; 240 gate completions
Primary question: Which recordings to retire and which to allocate email promotion budget to in Q4

**Output Example (Excerpt — Library Summary + Top 5 Evergreen + Top 5 Retire Recommendations):**

*Vaultline On-Demand Library Assessment — Q3 2026*

Library Overview:
- Total active recordings: 63
- Monthly views: 1,620 (25.7 views/recording/month — above benchmark of 10–25, healthy)
- Gate conversion rate: 14.8% (library average — above 12–22% benchmark baseline)
- Average watch completion: 41% (below 45% benchmark — indicates pacing/format issue in some recordings)
- On-demand pipeline influence: 22% of total opportunities had on-demand touchpoint (90-day attribution) — strong
- Library content age distribution: 31% older than 24 months — retirement review warranted

Classification Summary:
- Evergreen: 14 recordings (22%)
- Steady-State: 19 recordings (30%)
- Decaying: 18 recordings (29%)
- Stale: 12 recordings (19%) — recommended for retirement within 60 days

Top 5 Evergreen Recordings (Recommended for Active Promotion):
1. "The CFO's Guide to Financial Close Automation: Framework & Checklist" (published Nov 2023)
   - Monthly views: 187 (growing 12% QoQ) | Gate conversion: 21.4% | Pipeline influenced last 90 days: $840K
   - Recommended: Feature in Q4 prospect nurture sequences, allocate $1,500/month in paid retargeting budget to replay page

2. "Customer Panel: How Meridian Health Cut Month-End Close from 14 Days to 4" (published Feb 2024)
   - Monthly views: 142 | Gate conversion: 18.9% | Pipeline influenced last 90 days: $610K
   - Recommended: Add to SDR touch sequence for CFO personas; promote to new email subscribers as #2 replay recommendation

3. "Eliminating Spreadsheet Risk in the Finance Close: A Practitioner's Framework" (published Aug 2023)
   - Monthly views: 128 | Gate conversion: 19.2% | Pipeline influenced last 90 days: $480K
   - Recommended: Co-promote with blog post of same framework; test mid-roll CTA placement at 65% completion

[2 additional evergreen recordings...]

Top 5 Recordings Recommended for Retirement:
1. "Vaultline Product Demo: Close Automation Suite v2.1" (published April 2023)
   - Monthly views: 12 (declining 68% QoQ) | Gate conversion: 4.1% | Pipeline influenced last 90 days: $0
   - Retirement reason: Product UI entirely different; v2.1 references outdated; competitive claims superseded by new market entrants
   - Action: Unpublish by Oct 15; redirect to current interactive demo page; notify 3 SDRs who have this link in active sequences

2. "2024 Financial Close Trends: Predictions and Benchmarks" (published Jan 2024)
   - Monthly views: 8 | Gate conversion: 7.2% | Pipeline influenced: $0
   - Retirement reason: Trend predictions now empirically testable and largely outdated; benchmark data from 2023 surveys
   - Action: Unpublish; redirect to updated 2026 State of Financial Close Research Report

[3 additional retirement recommendations...]

Top 5 Refresh Candidates (Estimated ≤4 Hours Production Each):
1. "Financial Close Automation ROI Calculator: Live Walkthrough" (published June 2023)
   - Refresh needed: Update product UI screenshots (slides 14–22); refresh ROI benchmark numbers with 2025 data
   - Current score: 2.7 | Post-refresh projected score: 4.1
   - Estimated views increase post-refresh: +40% (based on comparable refreshes in library)

---

## Success Metrics

**Library Health KPIs (Reviewed Monthly):**
- Active library size (recordings classified Evergreen or Steady-State): Should represent ≥ 60% of total library; if below 50%, retirement pace is lagging
- Average monthly views per recording: Track trend — a growing library with flat total monthly views means each recording is getting less traffic (over-production signal)
- Gate conversion rate (library-wide): ≥ 12% monthly; decline below 10% triggers content relevance review
- On-demand pipeline influence rate: % of new opportunities with on-demand touchpoint; target 15–30% for companies with active webinar programs

**Attribution KPIs (Reviewed Quarterly):**
- On-demand pipeline influenced ($ value, trailing 90 days): Primary ROI metric for the library
- Revenue per on-demand gate completion: Total closed-won revenue influenced ÷ Total gate completions (trailing 180 days)
- Cost per on-demand view: Total webinar production and platform cost ÷ Total annual views
- Content ROI by recording: Pipeline influenced ÷ Production cost for each Evergreen recording — surface the 20% of recordings producing 80% of pipeline value

**Content Longevity KPIs (Reviewed Quarterly):**
- Evergreen recording ratio: Target ≥ 25% of library classified as Evergreen; below 20% signals over-production of ephemeral content types
- Average recording lifetime (months to Stale classification): Benchmark against production investment — if average lifespan is 9 months with $8K average production cost, content ROI math sets your minimum pipeline-per-recording expectation
- Refresh conversion lift: Average % view increase for refreshed recordings vs. pre-refresh baseline — validates refresh investment

## Related Prompts

- [AI-Powered B2B SaaS Webinar Performance Analytics & Pipeline Revenue Attribution Intelligence Engine](./AI-Powered-B2B-SaaS-Webinar-Performance-Analytics-&-Pipeline-Revenue-Attribution-Intelligence-Engine.md)
- [AI-Powered B2B SaaS On-Demand Webinar Library & Evergreen Virtual Event Revenue Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Webinar-Marketing/AI-Powered-B2B-SaaS-On-Demand-Webinar-Library-&-Evergreen-Virtual-Event-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Content Decay Detection & Evergreen Refresh Prioritization Intelligence Engine](../../05_Analytics-&-Performance/Content-Analytics/AI-Powered-B2B-SaaS-Content-Decay-Detection-&-Evergreen-Refresh-Prioritization-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Webinar Series Architecture & Annual Programming Calendar Revenue Intelligence Engine](../../03_Content-&-Creative/Webinar-Content-Production/AI-Powered-B2B-SaaS-Webinar-Series-Architecture-&-Annual-Programming-Calendar-Revenue-Intelligence-Engine.md)

## Integration Tips

**Wistia + HubSpot (Most Common B2B SaaS Stack):**
Wistia's native HubSpot integration passes video view data (play, completion percentages, total watch time) directly to HubSpot contact timeline events — enabling the view-to-contact attribution model described in Deliverable 1 without custom development. Enable the integration in Wistia Settings → Integrations → HubSpot, then in HubSpot create a workflow triggered on "Contact had Wistia video view event" with actions to set the custom contact properties (On-Demand Webinar Viewed, Total Watch Time, Last View Date) defined in Deliverable 1B. For pipeline influence reporting, build a HubSpot custom report: Deals with associated contacts who have "On-Demand Webinar Viewed" containing any value, filtered to deal create date within 180 days of video view date. This produces your primary on-demand pipeline influence metric without Salesforce attribution.

**Vidyard + Salesforce (Enterprise Stack):**
Vidyard's Salesforce package writes video viewing data directly to Salesforce Contact and Lead records as activity history items, with a "Watched %" field on each viewing session. Build a Salesforce report filtering Activity Type = "Video View" and Watched % ≥ 25%, then join to Opportunities where Opportunity Create Date is within 180 days of Activity Date. This cohort defines your on-demand pipeline influence population. For the content decay dashboard, export Vidyard's Video Analytics CSV monthly and load to Google Sheets or Tableau — Vidyard's native analytics does not include the decay classification logic; you'll run the scoring model in a spreadsheet template against the exported data.

**GA4 (On-Demand Page Traffic Attribution):**
Configure GA4 Enhanced Measurement to automatically capture video engagement events when using embedded players on your website (works natively for YouTube embeds; for Wistia or Vidyard, use GA4 custom event tagging via Google Tag Manager). Create GA4 Exploration reports filtering to "page_location contains /webinar-library" or your replay page URL pattern to analyze organic search traffic by recording title, time-on-page, and scroll depth (scroll depth as proxy for replay engagement rate for ungated recordings). Monthly, export the GA4 "Landing page + source / medium" report for your replay page URLs to identify which search queries are driving on-demand discovery — this surfaces SEO optimization opportunities for replay page titles and meta descriptions.

**Salesforce + Outreach/Salesloft (SDR Sequence Management):**
When a recording is reclassified to "Retire" by the quarterly decay model, run a Salesforce report identifying all Leads and Contacts with "On-Demand Webinar Viewed" containing the retiring recording's title who are currently in an active Outreach or Salesloft sequence. Export this list and upload to Outreach/Salesloft to trigger a sequence step change — automatically swapping the retired recording URL with the most relevant Evergreen recording. Without this cleanup, SDR sequences continue promoting content that now returns 404 errors or outdated information, creating a negative buyer impression during the active sales cycle.

## Troubleshooting

**Problem: On-demand gate completions are high but pipeline influence rate is near zero — the analytics show we generate 200+ gate completions per month from replays but almost no opportunities are created or influenced.**
Solution: This is an audience quality problem, not a measurement problem. 200 gate completions from on-demand content with zero pipeline influence means your replay content is attracting non-ICP visitors (job seekers, students, competitors, existing customers in a non-expansion context, or international visitors outside your serviceable market). Diagnose by pulling the company domains of the last 100 gate completions and cross-referencing against your ICP firmographic criteria: if fewer than 30% of company domains match your ICP profile, your on-demand content is either distributed too broadly (appearing in non-ICP search results) or the gate form is capturing an audience segment that doesn't match your buyer. Fix: add a company size or job title qualification field to your gate form (reduces conversions 15–25% but dramatically improves ICP match rate), and restrict paid promotion of on-demand content to ICP-matched audiences only. Do not retire the content — the recordings may have genuine ICP value; the distribution targeting is the problem.

**Problem: The decay model is classifying too many recordings as Stale, recommending retirement for 40%+ of the library — this seems excessive and the content team is pushing back.**
Solution: Over-classification to Stale is typically caused by two root issues: (1) The monthly view volume threshold for Stale classification is set too high relative to your library's realistic promotion investment. If you never actively promote your on-demand library, every recording will underperform on a raw view metric. Before applying the decay framework, run a 60-day "promotion experiment": actively email your top 10 oldest recordings to a relevant list segment, measure the view and gate response, and reset your Stale threshold based on observed performance with active promotion. (2) The library is over-indexed with ephemeral content types (product demos, annual trends) that have structurally short lifespans. The solution is not to change the threshold but to change future production mix — using the Evergreen Prediction Model (Deliverable 3B) to evaluate new webinars before production, and setting a target of ≥ 40% of new production in high-longevity formats. For the current library, apply the Retire decision only to recordings scoring ≤ 1.9 on the weighted model; reclassify the 2.0–2.4 range as "Archive" (keep published but remove from active promotion) to reduce content team anxiety about the retirement label.

**Problem: We can't stitch on-demand views to individual contacts because most of our replay page traffic arrives from organic search and the viewer never completes a gate — we have 1,400 monthly views but only 200 gate completions, leaving 1,200 views unattributed.**
Solution: The 1,200 unattributed views represent your real measurement opportunity. Implement two parallel tracks: (1) Reverse IP identification for company-level attribution — integrate a tool like Clearbit Reveal, 6sense Site Intelligence, or Demandbase Site ID on your replay pages. Even without individual identity, knowing that "Salesforce Inc, 50,000 employees, CRM industry" viewed your "Financial Close Automation" replay 7 times in 30 days is a tier-1 ABM signal. Push this company-level viewing data to your CRM account record as a "Website Intent — Webinar View" activity and alert the AE owning that account. (2) Progressive profiling and non-gate engagement: for the 1,200 unidentified views, track scroll depth, video completion milestones, and click events on replay page CTAs using MAP pixel session tracking. When any of these anonymous visitors later fill out any form on your website — even an unrelated form like a newsletter signup — the MAP will retrospectively attribute the prior webinar view to the now-known contact, expanding your attributed view count without gating the content more aggressively.

## Version History
- v1.0: Initial creation (auto-generated)
