# AI-Powered B2B SaaS Creator & Influencer Marketing Performance Analytics & Pipeline Revenue Attribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** influencer-analytics, creator-marketing, pipeline-attribution, b2b-saas, dark-social, revenue-attribution, creator-roi, podcast-analytics, newsletter-sponsorship, thought-leader-ads

## Overview
This prompt builds a complete creator and influencer marketing analytics system for B2B SaaS companies — covering podcast sponsorship ROI, LinkedIn creator performance, newsletter sponsorship attribution, employee advocacy measurement, and dark social pipeline tracking across creator-driven touchpoints. It solves the core measurement problem that kills creator budgets: proving that creator-generated awareness actually converts to revenue.

## Quick Copy-Paste Version

You are a B2B SaaS marketing analytics expert specializing in creator and influencer marketing measurement. I need a complete creator marketing performance analytics and revenue attribution framework.

Company: [Your Company]
Product/Category: [e.g., "Revenue intelligence platform for mid-market B2B SaaS"]
ICP: [Job titles and company size, e.g., "VP Sales and RevOps leaders at B2B SaaS companies 100-1,000 employees"]
Current Creator Program: [Types and scale, e.g., "3 podcast sponsorships ($15K/month), 5 LinkedIn creator partnerships ($8K/month), 1 newsletter sponsorship ($6K/month)"]
Total Creator/Influencer Budget: [Monthly spend, e.g., "$29,000/month"]
Analytics Stack: [CRM + Marketing automation, e.g., "HubSpot + ActiveCampaign + GA4"]
Primary Attribution Challenge: [Your biggest measurement problem, e.g., "Podcast listeners never click our tracked URLs — they search our brand name directly weeks later after hearing multiple episodes"]

Build me:

1. CREATOR PROGRAM PERFORMANCE METRICS FRAMEWORK — The 10 metrics that actually matter for B2B SaaS creator marketing (not downloads and impressions), with benchmarks and CRM tracking requirements
2. DARK SOCIAL ATTRIBUTION METHODOLOGY — A complete system to capture pipeline that originated from creator content but arrived via brand search, direct, or word-of-mouth — covering promo codes, self-reported attribution, and cohort analysis
3. CREATOR ROI SCORING MODEL — A standardized scoring matrix to compare ROI across completely different creator formats (podcasts vs. newsletters vs. LinkedIn creators vs. YouTube channels)
4. CREATOR SELECTION INTELLIGENCE FRAMEWORK — Data-driven criteria to evaluate new creator partnerships before committing budget, including audience quality scoring and historical conversion rate estimation
5. MONTHLY CREATOR PROGRAM REVENUE REPORT — A board-ready report template that proves creator marketing ROI to a CFO who currently views it as untestable brand spend

Every metric must have a data source, calculation method, and CRM-connected tracking mechanism. No "brand awareness is hard to measure" cop-outs — this report must defend creator budget to a skeptical CFO.

## Advanced Customizable Version

ROLE: You are a senior B2B SaaS marketing analytics architect with 12+ years of experience building revenue attribution models for creator and influencer marketing programs. You have solved the dark social attribution problem for creator channels at companies ranging from Series B startups to public SaaS enterprises. Your expertise spans:
- Podcast advertising attribution: promo code tracking, unique URL methodology, post-attribution lift studies, and brand search correlation analysis
- LinkedIn creator and Thought Leader Ads performance measurement and pipeline attribution
- Newsletter sponsorship ROI modeling: subscriber-to-trial conversion rates, direct URL tracking, and audience overlap analysis
- YouTube and short-form video creator partnership measurement: view-through attribution, comment sentiment analysis, and audience quality scoring
- Employee advocacy program analytics: amplification measurement, pipeline attribution, and social selling revenue contribution
- Dark social attribution for creator channels: self-reported first-touch, CRM source waterfall models, and incrementality testing
- Integration of creator analytics data with Salesforce, HubSpot, Marketo, GA4, and BI tools (Looker, Tableau, Power BI)

OBJECTIVE: Build a complete, AI-executable Creator & Influencer Marketing Analytics Intelligence System for a B2B SaaS company. Every component must be production-ready — designed so an AI agent can pull data, calculate metrics, generate insights, and produce a board-ready monthly report without requiring manual analysis.

COMPANY CONTEXT:
- Company Name: [Company Name]
- Product Description: [One sentence: what it does, for whom, and the primary outcome delivered]
- Product Category: [e.g., "Revenue Intelligence," "DevSecOps," "HR Tech"]
- ACV: [e.g., "$28,000 ACV"]
- Sales Cycle Length: [e.g., "30-60 days for SMB, 90-180 days for mid-market"]
- ICP Job Titles: [Primary buyer personas]
- ICP Company Profile: [Company size, industry, and growth stage of ideal buyers]
- Current Creator Program Inventory:
  - Podcast sponsorships: [List podcasts, format (host-read vs. pre-roll), monthly cost, episode frequency]
  - LinkedIn creator partnerships: [List creators, follower count, audience ICP match estimate, monthly cost]
  - Newsletter sponsorships: [List newsletters, subscriber count, estimated ICP % of list, monthly cost]
  - YouTube creators: [List channels, subscriber count, views/video, monthly cost]
  - Employee advocacy participants: [Number of active employee creators, avg follower count]
  - Other: [Micro-influencer programs, community sponsorships, analyst/practitioner partnerships]
- Total Monthly Creator Budget: [e.g., "$42,000/month"]
- Current Tracking Infrastructure: [Promo codes: Y/N; Unique landing pages: Y/N; UTM parameters: Y/N; Self-reported attribution field on demo form: Y/N]
- CRM Platform: [Salesforce / HubSpot / Pipedrive / other]
- Marketing Automation Platform: [Marketo / HubSpot Marketing / ActiveCampaign / other]
- Current Attribution Model: [First-touch / Last-touch / Multi-touch / No formal model]
- BI Tool: [Looker / Tableau / Power BI / Google Data Studio / spreadsheets]
- Primary Measurement Gap: [Describe your top 2-3 creator marketing measurement challenges]

---

DELIVERABLE 1 — CREATOR PROGRAM PERFORMANCE METRICS ARCHITECTURE

Section 1A: The 10 Creator Marketing Metrics That Actually Matter for B2B SaaS

For each metric below, provide:
- Precise calculation formula
- Data source (creator analytics, CRM, MA platform, promo code platform, or third-party tool)
- B2B SaaS benchmark by ACV tier ($0-15K ACV, $15K-50K ACV, $50K+ ACV)
- Why this metric matters for revenue (not for "brand awareness" — connect to pipeline or revenue outcome)
- Red/Yellow/Green thresholds for your creator program scale

TIER 1 — PIPELINE-CONNECTED METRICS (Primary):

1. Creator-Sourced Trial/Demo Rate
   - Definition: Number of trial starts or demo requests that used a creator-specific promo code or unique tracking URL in a given period
   - Formula: SUM(trials + demo requests) where Source = Creator Promo Code OR Unique Creator URL
   - Data source: CRM Lead Source field, promo code redemption platform (Rewardful, PartnerStack, or custom), unique URL redirect tracking (Rebrandly, Bitly Analytics, or custom UTM)
   - Benchmark by ACV: <$15K ACV: 40-80 trials per $10K spent; $15K-50K ACV: 8-20 demos per $10K spent; $50K+ ACV: 2-6 demos per $10K spent
   - CRM tracking: Required Lead Source = "Creator-[Creator Name]-[Format]" field with promo code ID or URL campaign ID linked to Lead record

2. Creator-Attributed Pipeline ($)
   - Definition: Total open opportunity value where the associated Contact record has a Creator-attributed Lead Source within 90 days prior to opportunity creation
   - Formula: SUM(Opportunity Amount) where Contact.Lead_Source contains "Creator" AND Contact.Lead_Created_Date is within 90 days of Opportunity.Created_Date
   - Data source: CRM opportunity report filtered by contact lead source
   - Benchmark: Creator-attributed pipeline should represent 8-20% of total pipeline for companies with $30K+/month creator budgets
   - CRM tracking: Requires Lead Source waterfall model — Creator attribution must be set at contact creation and preserved through opportunity association

3. Creator-Sourced Closed-Won Revenue ($)
   - Definition: Closed-won ARR from deals where ANY contact on the opportunity has a Creator-attributed Lead Source
   - Formula: SUM(Closed-Won ARR) where Opportunity has ≥1 Contact with Lead_Source containing "Creator"
   - Data source: CRM closed-won report
   - Benchmark: Creator sourced closed-won revenue typically lags by 90-180 days relative to creator spend — align reporting windows accordingly

4. Creator Cost Per Acquired Customer (Creator CAC)
   - Definition: Total creator program investment divided by customers acquired with creator attribution in the same period (with 90-day attribution window)
   - Formula: (Total Creator Spend in Period) ÷ (Customers Acquired where Contact.Lead_Source contains "Creator" and deal closed within period + 90 days)
   - Benchmark: Creator CAC should be within 1.5x of blended marketing CAC for the program to be justified; top-performing creator programs achieve 0.6-0.9x blended CAC

5. Creator Pipeline ROI Multiplier
   - Definition: Total pipeline attributed to creator program divided by total creator spend — the highest-level efficiency metric for creator investment justification
   - Formula: Creator-Attributed Pipeline ($) ÷ Creator Spend ($) in same period
   - Benchmark: <$15K ACV: Target 6-12x; $15K-50K ACV: Target 8-18x; $50K+ ACV: Target 12-25x (longer sales cycles warrant higher multiplier targets)

TIER 2 — AUDIENCE QUALITY METRICS (Leading Indicators):

6. ICP Audience Match Score (Pre-Partnership Evaluation)
   - Definition: Estimated percentage of a creator's audience that matches your ICP — the foundational metric for creator selection
   - Calculation methodology:
     a) Request creator media kit — evaluate audience demographics (job titles, company sizes, industries)
     b) Cross-reference claimed demographics against LinkedIn follower data (for LinkedIn creators), podcast listener data (from podcast apps via Chartable/Spotify for Podcasters), or newsletter subscriber demographics (via Beehiiv/Substack analytics if shared)
     c) Request 3 introductions to recent audience members or customers who engaged with creator content — qualify against ICP criteria in 15-minute conversations
     d) Score: (Estimated ICP audience members) ÷ (Total claimed audience) × 100
   - Benchmark: >40% ICP match = Strong partnership candidate; 20-40% = Acceptable with right content angle; <20% = Audience misalignment risk

7. Creator Engagement Quality Score (EQS)
   - Definition: A composite score that evaluates whether creator audience engagement indicates genuine professional relevance — not vanity metrics
   - Formula: EQS = (Professional Comment Rate × 0.4) + (Save/Share Rate × 0.3) + (Reply Rate × 0.2) + (Click-Through Rate × 0.1)
   - Where:
     - Professional Comment Rate = Comments containing industry-specific language, specific examples, or questions vs. total comments
     - Save/Share Rate = Saves + Shares ÷ Total impressions (highest intent signal — indicates content useful enough to reference later)
     - Reply Rate = Creator's reply rate to audience comments within 48 hours (signals active community, not passive broadcast)
     - Click-Through Rate = Clicks ÷ Impressions on sponsorship-eligible content
   - Benchmark: EQS >7.0 = High-quality engaged audience; 4.0-6.9 = Moderate; <4.0 = Passive audience, conversion unlikely

8. Promo Code Redemption Velocity
   - Definition: Rate at which creator-specific promo codes are redeemed, measured in redemptions per 1,000 audience members per episode/issue/post
   - Formula: (Promo code redemptions in period) ÷ (Unique audience reached in period) × 1,000
   - Benchmark by format: Podcast host-read (30-min episode): 0.8-3.0 per 1,000 listeners; Newsletter (primary placement): 2.0-6.0 per 1,000 subscribers; LinkedIn post (sponsored): 0.5-2.0 per 1,000 impressions
   - Why it matters: Low redemption velocity vs. benchmark indicates audience-offer mismatch, not audience quality failure — triggers offer optimization before canceling the partnership

TIER 3 — DARK SOCIAL PROXY METRICS (Attribution Completeness):

9. Creator Brand Search Lift
   - Definition: Increase in branded search volume (searches for your company/product name) in the 14 days following a creator's sponsorship episode or post
   - Data source: Google Search Console (branded query impressions and clicks), Google Trends relative search interest
   - Calculation: (Branded search volume in 14 days post-publication) ÷ (Baseline branded search volume — 30-day average prior to publication) - 1 = % lift
   - Benchmark: Successful podcast sponsorships generate 8-35% branded search lift in the 7-14 days following episode release; LinkedIn creator posts generate 3-12% lift in the 48-96 hours following post
   - Tracking method: Tag each creator episode/post release date in a calendar → correlate with Google Search Console weekly report

10. Self-Reported Creator Attribution Rate
    - Definition: Percentage of new leads/demo requests that explicitly name a creator, podcast, newsletter, or creator content as their first awareness touch in the "How did you hear about us?" form field
    - Formula: (Leads where Self-Reported First Touch mentions creator, podcast, newsletter, creator name) ÷ (Total leads with self-reported attribution field populated) × 100
    - Benchmark: Creator programs with $20K+/month spend should see 8-20% of self-reported first touches crediting creator channels
    - NLP classification: AI agent should parse self-reported text for creator names, podcast names, newsletter titles, and "heard on a podcast / newsletter / YouTube" signals → tag contact with "Creator Attribution: [Creator Name]"

---

Section 1B: Creator Analytics Reporting Cadence

| Metric | Reporting Cadence | Owner | Audience |
|---|---|---|---|
| Creator-Sourced Trial/Demo Rate | Weekly | Marketing Ops | Demand Gen Lead |
| Promo Code Redemption Velocity | Per Episode/Post | Creator Manager | CMO, Demand Gen Lead |
| Creator-Attributed Pipeline | Monthly | Marketing Ops | CMO |
| Creator Brand Search Lift | Per Episode/Post | SEO/Analytics | Creator Manager |
| ICP Audience Match Score | At partnership evaluation | Creator Manager | CMO, Finance |
| Creator CAC | Quarterly | Marketing Ops | CMO, CFO |
| Self-Reported Creator Attribution Rate | Monthly | Marketing Ops | CMO |
| Creator Pipeline ROI Multiplier | Monthly | Marketing Ops | CMO, CFO, Board |

---

DELIVERABLE 2 — DARK SOCIAL ATTRIBUTION ARCHITECTURE FOR CREATOR CHANNELS

Section 2A: Why Creator Channels Have a Structural Attribution Problem

Creator marketing has a fundamentally different attribution challenge than paid digital:
- A podcast listener hears your ad during their morning commute (no device interaction)
- They research your product that afternoon via Google brand search (attributed to: Google Organic)
- They visit your site via a saved bookmark 3 days later (attributed to: Direct)
- They sign up for a trial using their work email 2 weeks later (attributed to: Direct or Email)

Your attribution model shows: Google Organic + Direct = Source. LinkedIn creator post that drove the initial awareness: ZERO credit.

This pattern accounts for an estimated 50-80% of creator-influenced pipeline in B2B SaaS — and is structurally invisible to standard UTM-based attribution.

Section 2B: Four-Layer Creator Dark Social Attribution Methodology

LAYER 1 — PROMO CODE + UNIQUE URL TRACKING (Direct signal, low friction)

Promo Code Architecture:
- Assign each creator a unique promo code (e.g., REVOPS, CHAINSAW, PIPELINE20)
- Use codes that are memorable and natural for creator read-throughs — avoid codes like CREATOR_HUBSPOT_Q3 that break the podcast reading flow
- Track via: Rewardful, PartnerStack, Impact.com, or custom CRM coupon code field
- CRM mapping: When promo code is redeemed at signup → auto-populate Lead Source = "Creator-[CreatorName]" on the Contact record

Unique Landing Page Architecture:
- Create creator-specific landing pages: yourcompany.com/pod/[creatorname], yourcompany.com/nl/[newslettername]
- Use these for creator mentions where audiences are likely to type the URL manually (podcast read-throughs especially)
- Redirect to main demo/trial page with UTM parameters appended: utm_source=creator&utm_medium=podcast&utm_campaign=[creatorname]&utm_content=[episode-id]
- Benefit: Even if the prospect types the URL manually (not clicking a tracked link), the redirect captures the source

Benchmark: Promo codes + unique URLs typically capture 20-40% of actual creator-driven conversions — the remaining 60-80% arrives via brand search, direct, or word-of-mouth. Treat promo code data as a floor, not a ceiling.

LAYER 2 — SELF-REPORTED ATTRIBUTION SYSTEM (High signal, moderate volume)

Implementation:
- Add open-text field to every demo request and trial signup form:
  - Field label: "How did you first hear about [Company Name]? (Be specific — e.g., heard on a podcast, read in a newsletter, colleague mentioned it)"
  - Field type: Short text — NOT a dropdown (dropdowns suppress creator mentions by 60-80% because "Podcast" isn't always an option)
  - CRM mapping: Sync as "Self-Reported First Touch" on Lead/Contact record

AI Agent NLP Classification Workflow:
1. New lead created with "Self-Reported First Touch" populated → AI agent analyzes text
2. Classification patterns:
   - Contains podcast name from your active sponsor list → tag: "Creator-Podcast-[PodcastName]"
   - Contains newsletter name → tag: "Creator-Newsletter-[NewsletterName]"
   - Contains LinkedIn creator's name or username → tag: "Creator-LinkedIn-[CreatorName]"
   - Contains "podcast," "episode," "listened" + no specific name → tag: "Creator-Podcast-Unknown"
   - Contains "newsletter," "email digest," "read" + no specific name → tag: "Creator-Newsletter-Unknown"
3. CRM property "Creator Dark Social Source" populated with classified tag
4. Monthly aggregate: Creator channels mentioned in self-reported field ÷ total self-reported submissions = Creator Dark Social Rate

Benchmark: For companies with $20K+/month creator investment, target 10-25% of self-reported first touches mentioning creator channels.

LAYER 3 — BRAND SEARCH LIFT CORRELATION ANALYSIS (Medium signal, high coverage)

Methodology: Treat brand search volume as a proxy for creator-driven awareness, then correlate spikes with specific creator activity.

Weekly data pull setup (AI agent):
1. Export Google Search Console data: branded query impressions and clicks, segmented by week
2. Log all creator publication events: podcast episode air dates, newsletter send dates, LinkedIn creator post publish times
3. Run rolling correlation: branded search volume in the 7-14 days following each creator publication vs. 30-day baseline
4. Flag events where post-publication search lift exceeds 10% → mark as "High-Lift Creator Activation"

Creator Attribution Lift Score:
- Take each creator's average brand search lift across all sponsored episodes/posts
- Weight by audience size and ICP match score
- Output: Ranked list of creators by brand search lift efficiency (lift per $1,000 spent)

This analysis typically reveals that 2-3 creators in a portfolio drive 70-80% of measurable brand awareness lift, enabling budget concentration decisions.

LAYER 4 — COHORT COMPARISON ANALYSIS (Lower signal, highest analytical rigor)

Holdout Testing Design (Recommended for creators with $5K+/month spend):
- Run a 60-day holdout test with a single high-spend creator before committing to renewal
- Method: Pause sponsorship for Creator X for 60 days → measure whether brand search volume, trial volume, and inbound demo request rate changes vs. the prior 60-day period (controlling for seasonality)
- If brand search drops 8%+ and trial volume drops 5%+ during the holdout → the creator is generating measurable incremental demand
- If no measurable change → creator partnership is generating awareness that isn't converting, or the audience isn't ICP-qualified

Audience Overlap Cohort Analysis:
- Step 1: Export your CRM contact database (email list)
- Step 2: Request the creator/podcast/newsletter to run an audience overlap analysis via LiveRamp, Bombora, or a shared identity resolution tool
- Step 3: Identify CRM contacts who are also subscribers/listeners/followers of that creator
- Step 4: Compare pipeline velocity and win rates for CRM contacts with creator audience overlap vs. matched contacts without overlap
- Expected finding: Contacts who were already in the creator's audience before converting typically show 15-35% higher win rates due to pre-existing trust transfer from the creator's recommendation

---

DELIVERABLE 3 — CREATOR ROI SCORING MODEL

Section 3A: Standardized Creator ROI Score (CRS)

The Creator ROI Score enables apples-to-apples comparison across completely different creator formats (a $15K/month podcast vs. a $3K/month LinkedIn creator vs. a $8K/month newsletter) using a standardized 100-point scoring matrix.

CRS = (Pipeline Contribution Score × 0.40) + (Audience Quality Score × 0.25) + (Brand Lift Score × 0.20) + (Conversion Efficiency Score × 0.15)

Pipeline Contribution Score (0-100):
- Source: Creator-Attributed Pipeline ÷ Creator Spend in same period (adjusted for 90-day attribution lag)
- Scoring: Pipeline ROI <3x = 0-20pts; 3-6x = 21-50pts; 6-12x = 51-75pts; 12x+ = 76-100pts

Audience Quality Score (0-100):
- Source: ICP Audience Match Score × Creator Engagement Quality Score
- Scoring: Combined score <25 = 0-20pts; 25-40 = 21-50pts; 40-55 = 51-75pts; 55+ = 76-100pts

Brand Lift Score (0-100):
- Source: Average branded search lift per episode/post, weighted by publication frequency
- Scoring: <5% avg lift = 0-20pts; 5-12% = 21-50pts; 12-25% = 51-75pts; 25%+ = 76-100pts

Conversion Efficiency Score (0-100):
- Source: Promo code/URL redemption velocity vs. format benchmark
- Scoring: Below 50% of benchmark = 0-20pts; 50-80% = 21-50pts; 80-120% = 51-75pts; 120%+ = 76-100pts

Section 3B: Creator Portfolio Performance Dashboard

| Creator | Format | Monthly Spend | CRS | Pipeline Contribution Score | Audience Quality Score | Brand Lift Score | Conversion Efficiency | 90-Day Action |
|---|---|---|---|---|---|---|---|---|
| [Creator A] | Podcast | $12,000 | 71 | 68 | 78 | 82 | 56 | Renew — strong brand lift driver |
| [Creator B] | LinkedIn | $4,000 | 84 | 90 | 72 | 69 | 95 | Scale — highest overall ROI |
| [Creator C] | Newsletter | $8,000 | 42 | 35 | 55 | 38 | 40 | Renegotiate — underperforming; reduce spend or test new offer angle |
| [Creator D] | YouTube | $6,000 | 28 | 20 | 40 | 30 | 22 | Pause — 60-day holdout test before renewal decision |

AI Agent Portfolio Optimization Logic:
- CRS 70+: Flag for budget increase consideration in next quarter
- CRS 50-69: Maintain current investment; optimize offer/creative
- CRS 30-49: Renegotiate terms or run A/B offer test before renewal
- CRS <30: Run 60-day holdout test; terminate if no measurable brand search lift during holdout

---

DELIVERABLE 4 — CREATOR SELECTION INTELLIGENCE FRAMEWORK

Section 4A: Pre-Partnership Evaluation Scorecard

Before committing to any creator partnership, run this standardized evaluation:

GATE 1 — AUDIENCE QUALIFICATION (Must pass before deeper evaluation):

| Criterion | Verification Method | Pass Threshold |
|---|---|---|
| ICP job title match | Request demographic breakdown from creator's platform analytics or media kit | >30% ICP-matching job titles in audience |
| ICP company size match | Ask for company size breakdown of engaged audience | >40% from companies in your ICP size range |
| Geography alignment | Review audience location data | >60% of audience in your target geography |
| Audience size minimum | Verify actual engaged audience (not claimed followers) | Podcast: >5,000 avg downloads; LinkedIn: >10K followers with >2% engagement; Newsletter: >3,000 active subscribers (define active as opened last 30 days) |

GATE 2 — CONTENT QUALITY & BRAND SAFETY EVALUATION:

- Review last 6 months of creator content for: brand safety risks (political content, controversial topics), positioning alignment with your product category, existing competitor sponsorships (deal-breaker if exclusive territory applies), and audience relationship quality (does the creator genuinely engage with audience, or is it a broadcast with no interaction?)
- Competitive conflict check: Has this creator recently sponsored a direct competitor? If yes within 90 days: pause evaluation until exclusivity window passes
- Content frequency: Confirm the creator publishes consistently — irregular creators deliver inconsistent brand exposure

GATE 3 — REFERENCE CHECK (For partnerships >$3,000/month):

- Request 2-3 references from B2B SaaS sponsors the creator has worked with previously
- Key questions: What was the redemption rate? What pipeline did you attribute to the sponsorship? Would you renew?
- Red flag: Creator hesitates to provide references or references are all DTC/consumer brands (signals they haven't successfully driven B2B pipeline before)

GATE 4 — PILOT STRUCTURE:

- Never commit to >3 episodes or >2 newsletter placements without seeing conversion data
- Pilot terms: 3-episode or 3-issue pilot with a creator-specific promo code and unique landing page
- Evaluation window: 45 days post-final pilot publication for redemption data; 90 days for pipeline data
- Go/No-Go criteria: If pilot generates Creator ROI Score <30 and less than 5% branded search lift — do not renew

Section 4B: Creator Discovery Pipeline

Identify new creator partnership candidates using:

1. Customer Intelligence Method: Ask your 10 best customers (highest ACV + lowest churn risk) which podcasts they listen to, newsletters they read, and LinkedIn voices they follow regularly. This generates a qualified audience overlap list — you know these creators reach your best customers.

2. Competitor Sponsorship Intelligence: Monitor competitor ad placements using Rephonic (podcast ad intelligence), Podcorn, or manual listening. If a competitor is sponsoring a podcast for 6+ consecutive episodes, they've likely seen conversion data that justifies renewal — evaluate that creator for your own sponsorship.

3. Audience Conversation Mining: Use a social listening tool (Brandwatch, Mention, or SparkToro) to identify which content sources your target ICP cites, shares, or references in professional conversations. High-frequency references = high-influence creators.

4. Sales Discovery Intelligence: Add to SDR/AE discovery script: "What are your go-to resources for staying current on [your product category]? What podcasts, newsletters, or LinkedIn voices do you follow?" Aggregate monthly — top responses = highest-priority creator targets.

---

DELIVERABLE 5 — MONTHLY CREATOR PROGRAM REVENUE REPORT

Section 5A: Board-Ready One-Page Creator ROI Summary

CREATOR MARKETING REVENUE CONTRIBUTION REPORT
[Company Name] | [Month/Year]

PIPELINE IMPACT
- Creator-Sourced Pipeline (Promo Code + URL Tracked): $[XXX,XXX] ([X.X%] of total pipeline)
- Creator Dark Social Attribution (Self-Reported + Brand Lift Model): $[XXX,XXX] additional estimated pipeline
- Total Creator Pipeline Contribution (Tracked + Modeled): $[XXX,XXX] ([X.X%] of total pipeline)
- Creator-Sourced Closed-Won ARR (Trailing 90 Days): $[XX,XXX]

EFFICIENCY METRICS
- Total Creator Investment This Month: $[XX,XXX]
- Directly Tracked Pipeline ROI: [X.Xx] (pipeline ÷ spend, tracked only)
- Full-Funnel Pipeline ROI (with dark social model): [X.Xx]
- Creator CAC (Trailing Quarter): $[XX,XXX] vs. Blended Marketing CAC $[XX,XXX]
- Creator CAC Index: [X.Xx] (<1.0 = Creator more efficient than blended average)

PROGRAM HEALTH
- Active Creator Partnerships: [X] creators across [X] formats
- Promo Code Redemptions This Month: [XXX] ([X.X per $1,000 of audience reached])
- Brand Search Lift (30-Day Average vs. Baseline): [+X.X%]
- Self-Reported Creator Attribution Rate: [X.X%] of new leads crediting creator channels
- Top Performing Creator This Month: [Creator Name] — CRS [XX], generated $[XXX,XXX] in attributed pipeline

PORTFOLIO BREAKDOWN
| Creator | Spend | CRS | Pipeline Attributed | Action |
|---|---|---|---|---|
| [Creator A] | $[X,XXX] | [XX] | $[XXX,XXX] | [Renew/Scale/Pause] |
| [Creator B] | $[X,XXX] | [XX] | $[XXX,XXX] | [Renew/Scale/Pause] |
| [Creator C] | $[X,XXX] | [XX] | $[XXX,XXX] | [Renew/Scale/Pause] |

KEY INSIGHT THIS MONTH: [One sentence AI-generated insight — e.g., "Podcast sponsorships are generating 3.2x the pipeline-per-dollar of newsletter placements this quarter; recommend shifting 25% of newsletter budget to expand podcast partnerships in the RevOps and sales operations category."]

RECOMMENDED ACTION FOR NEXT MONTH: [One specific, data-backed recommendation]

---

AI AGENT REPORTING WORKFLOW:

WEEKLY (Every Monday AM):
1. Pull promo code redemption data → calculate weekly redemption velocity by creator → flag creators below 50% of format benchmark
2. Pull Google Search Console branded query data → calculate 7-day brand search lift vs. 30-day baseline → correlate with creator publication schedule
3. Pull CRM new leads from past 7 days → run NLP classification on "Self-Reported First Touch" field → tag creator-attributed contacts
4. Update creator pipeline dashboard: new pipeline created this week where Lead Source = Creator

MONTHLY (First Monday):
1. Aggregate all weekly data → calculate monthly Creator ROI Scores for all active partnerships
2. Run pipeline attribution report: all opportunities created where contact lead source = Creator (90-day window)
3. Calculate Creator CAC vs. blended marketing CAC
4. Rank creator portfolio by CRS → generate portfolio optimization recommendations
5. Identify creators approaching renewal date → pull CRS trend and renewal recommendation
6. Generate board-ready Creator Marketing Revenue Report
7. Distribute to CMO, CRO, CFO via automated email or BI dashboard notification

QUARTERLY (Creator Portfolio Review):
1. Run holdout analysis on any creator relationship >$5K/month and >6 months active
2. Evaluate new creator candidates using Section 4 framework
3. Terminate or renegotiate partnerships with CRS <30 for 2+ consecutive months
4. Increase investment in creators with CRS >70 for 2+ consecutive months
5. Present full creator program ROI to leadership with trailing 4-quarter trend

CONSTRAINTS:
- All creator attribution claims must distinguish between "tracked" (promo code / unique URL) and "modeled" (dark social estimate) to maintain credibility with Finance
- Creator ROI Scores must use a minimum 90-day attribution window for pipeline data — using 30-day windows systematically undercounts longer sales cycles
- Branded search lift analysis must control for confounding variables: paid search budget changes, organic ranking improvements, earned media events — correlate with creator publication dates, not claim causality without holdout confirmation
- ICP Audience Match Scores must be refreshed at each partnership renewal — creator audiences shift over time as their own brand grows
- Never report vanity metrics (total impressions, total downloads, follower counts) as primary metrics to CMO or CFO — always tie back to pipeline or pipeline proxy (redemption rate, brand search lift, self-reported attribution)

OUTPUT FORMAT:
Deliver all 5 sections as complete, production-ready frameworks. All tables should be ready to populate with real data. Write the board report template with placeholder values that make the format immediately usable. Every formula must be written so a marketing ops analyst can implement it without a data scientist.

## Example Input/Output

**Input Example:**

- Company: Recurly (fictional analogue) — RevStream Analytics
- Product: Revenue analytics platform for B2B SaaS CFOs and RevOps leaders — tracks ARR, churn, expansion, and cohort performance in real-time
- ICP: CFO, VP Finance, and Director of RevOps at B2B SaaS companies ($5M-$100M ARR)
- ACV: $24,000
- Sales Cycle: 45-90 days
- Creator Program:
  - Podcast A — "SaaS CFO Show": 28,000 avg downloads, $9,500/month, host-read 60-second mid-roll
  - Newsletter B — "RevOps Weekly": 14,200 subscribers, $6,200/month, primary sponsor placement
  - LinkedIn Creator C — "Sarah Chen, RevOps advisor": 42,000 followers, 3.8% engagement rate, $4,800/month for 4 sponsored posts
- Total Monthly Budget: $20,500
- Analytics Stack: HubSpot + GA4 + Looker
- Attribution Challenge: "We have promo codes but only 15% of our inbound demos use them — we're getting 35-40 demos/month we believe come from the creator program but can't prove it."

**Output Example (Excerpts):**

**Creator ROI Score Analysis — Q3 2026:**

| Creator | Format | Spend | Promo Redemptions | Self-Reported Attribution | Avg Brand Search Lift | CRS | 90-Day Action |
|---|---|---|---|---|---|---|---|
| SaaS CFO Show | Podcast | $9,500 | 12 demos (using REVSTREAM code) | 22 self-reported | +18.3% post-episode lift | 76 | Renew — top brand lift driver; explore 2x episode frequency |
| RevOps Weekly | Newsletter | $6,200 | 8 demos (unique URL) | 11 self-reported | +6.1% lift | 54 | Maintain — solid mid-tier; test new offer angle (ROI calculator vs. free trial) |
| Sarah Chen LinkedIn | LinkedIn | $4,800 | 4 demos (promo code) | 8 self-reported | +9.4% lift | 69 | Maintain — strong engagement quality; negotiate 6-post package for Q4 |

**Dark Social Attribution Baseline (90 days post-implementation):**

Total inbound demos: 142 over 90 days
- Promo code attributed: 24 (16.9%)
- Self-reported creator mention: 41 (28.9%)
- Combined unique: 52 contacts with either promo code OR self-reported creator attribution (37% of total)

Cohort comparison (contacts with creator attribution vs. non-creator inbound):
- Creator-attributed contacts: 34% demo-to-opportunity conversion; $28,400 avg deal size; 61-day avg sales cycle
- Non-creator inbound (matched cohort): 27% demo-to-opportunity conversion; $21,800 avg deal size; 79-day avg sales cycle

Finding: Creator-attributed contacts close at a 26% higher rate with 13% larger deals and 23% shorter sales cycles — indicating strong ICP pre-education effect from creator content. Dark social attribution model should credit creator channel for 60% of unmatchable inbound demos based on proportional cohort performance.

**Board-Ready Monthly Report (October 2026):**

CREATOR MARKETING REVENUE CONTRIBUTION REPORT — RevStream Analytics | October 2026

PIPELINE IMPACT
- Creator-Sourced Pipeline (Tracked): $380,000 (8.4% of $4.5M total pipeline)
- Dark Social Attribution (Self-Reported + Cohort Model): $540,000 additional estimated pipeline
- Total Creator Pipeline Contribution: $920,000 (20.4% of total pipeline)
- Creator-Sourced Closed-Won ARR (Q3): $192,000

EFFICIENCY METRICS
- Total Creator Investment: $20,500/month ($61,500 in Q3)
- Full-Funnel Pipeline ROI: 14.9x ($920K pipeline ÷ $61.5K spend)
- Creator CAC: $10,250 vs. Blended Marketing CAC $14,800
- Creator CAC Index: 0.69 — Creator marketing 31% more efficient than blended average

KEY INSIGHT: "Podcast sponsorships (SaaS CFO Show) are generating 3.4x the brand search lift of newsletter placements, and creator-attributed contacts close 26% faster than non-creator inbound. Recommend allocating an additional $8K/month to test a second podcast targeting CFO audience in Q4."

## Success Metrics

- **Promo Code Coverage Rate:** Target 20-40% of creator-influenced conversions captured via promo code or unique URL within 90 days of program launch — below 15% signals tracking infrastructure problems or offers that don't motivate code use
- **Self-Reported Creator Attribution Rate:** 10-25% of new leads crediting creator channels for companies with $20K+/month creator budgets — below 8% suggests creator reach isn't penetrating your ICP
- **Brand Search Lift per Episode/Issue:** Target 8-25% branded search lift in the 7-14 days following sponsorship publication — below 5% consistently signals audience-ICP mismatch, not necessarily attribution failure
- **Creator Pipeline ROI Multiplier:** Target 8-18x for $15K-50K ACV products; below 5x warrants immediate portfolio review
- **Creator CAC Index:** Target 0.7-1.2x of blended marketing CAC — above 1.5x requires renegotiation or program pause
- **Creator ROI Score Portfolio Average:** Target average CRS of 55+ across active partnerships; below 45 means the portfolio needs significant restructuring
- **Cohort Win Rate Differential:** Creator-attributed contacts should close at 15-35% higher rates than matched non-creator inbound — lower differential suggests audience-ICP mismatch or pre-education value isn't transferring to sales conversations

## Related Prompts

- [AI-Powered B2B SaaS Influencer & Creator Marketing Program Architecture & Dark Social Pipeline Revenue Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Influencer-&-Creator-Marketing/AI-Powered-B2B-SaaS-Influencer-&-Creator-Marketing-Program-Architecture-&-Dark-Social-Pipeline-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Podcast Creator Partnership & Executive Guest Booking Pipeline Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Influencer-&-Creator-Marketing/AI-Powered-B2B-SaaS-Podcast-Creator-Partnership-&-Executive-Guest-Booking-Pipeline-Intelligence-Engine.md)
- [Dark Funnel Attribution & Anonymous Buyer Intent Intelligence Engine](../Attribution-&-Revenue-Analytics/Dark-Funnel-Attribution-&-Anonymous-Buyer-Intent-Intelligence-Engine.md)
- [AI-Powered B2B Organic Social Media Performance Analytics & Pipeline Revenue Attribution Intelligence Engine](../Social-Media-Analytics/AI-Powered-B2B-Organic-Social-Media-Performance-Analytics-&-Pipeline-Revenue-Attribution-Intelligence-Engine.md)

## Integration Tips

- **HubSpot:** Create a custom Contact property "Creator Dark Social Source" (single-line text) and "Promo Code Used" (single-line text). Build a HubSpot Workflow that fires when a Deal is created and the associated Contact has a Creator Lead Source → auto-creates a HubSpot Deal Tag "Creator-Attributed." Build a custom HubSpot Report: Deals closed-won where Associated Contact original source = Creator (last 90 days) — this becomes your monthly Creator Revenue number. Use HubSpot's Revenue Attribution Reports to track creator channel performance against email, paid, and organic in a unified dashboard.
- **Salesforce:** Add a custom Lead/Contact field "Creator Attribution Code" (text) that captures the promo code or URL campaign parameter at lead creation. Build a Salesforce Campaign for each creator — when a promo code is redeemed → Campaign Member created on that creator's Campaign → enables Campaign ROI reporting. Use Salesforce's Campaign Influence feature (Primary Campaign Source) to attribute pipeline to creator campaigns when opportunities are created.
- **Google Analytics 4:** Create GA4 Audiences for visitors arriving via creator-specific unique URLs (utm_source=creator). Build a GA4 Funnel Exploration: creator URL arrival → demo page visit → demo form submit → trial start. Enable GA4 → BigQuery export → join with CRM data to stitch creator-attributed GA4 sessions to known Contact records when they later convert.
- **Rewardful / PartnerStack / Impact.com:** Use these affiliate platforms to manage creator promo codes — they auto-track redemptions, prevent code sharing fraud, and export redemption data via API directly to your CRM. Set up webhook on successful promo redemption → auto-create a tagged Lead in your CRM with the creator as the attribution source. Monthly API export → populate creator performance dashboard.
- **Chartable / Spotify for Podcasters:** Use Chartable's SmartLinks (podcast-specific tracked URLs) to measure podcast listener behavior post-episode — SmartLinks track whether a listener clicked through, visited your landing page, and converted. Chartable's attribution data feeds directly into its dashboard and exports via API. Combine with promo code data for a more complete podcast attribution picture.
- **Looker / Tableau:** Build a Creator Attribution Dashboard with two tabs: (1) Tracked Attribution (promo codes + unique URLs — high confidence) and (2) Modeled Attribution (dark social estimates — labeled as modeled). Color-code tracked vs. modeled data consistently throughout all visualizations. Build a Creator ROI Scorecard view that calculates CRS automatically from the underlying metric inputs — enables weekly portfolio monitoring without manual calculation.
- **SparkToro:** Use SparkToro to identify which podcasts, newsletters, and YouTube channels your ICP spends time with — based on the social media behavior of your target audience segments. This is the highest-ROI tool for creator discovery: input your ICP's LinkedIn job titles and company profiles → SparkToro returns ranked creator recommendations sorted by ICP audience concentration.

## Troubleshooting

**Problem:** Promo code redemption rates are consistently below benchmark (below 15% of promo code impressions converting) despite the creator having a high-quality, ICP-matched audience.
**Solution:** Low promo code redemption almost always reflects an offer-audience mismatch, not an audience quality problem. Run this diagnostic: (1) Check whether the promo code offer is compelling for a B2B buyer vs. a consumer (e.g., "20% off your first month" is a consumer DTC offer — a B2B software buyer is more motivated by "skip the sales call — get a custom ROI analysis and 30-day pilot" or "see your data in the platform within 24 hours"). (2) Check whether the creator is reading the ad copy naturally or mechanically — poorly integrated sponsorship reads reduce conversion by 40-60% vs. host-generated authentic reads. Provide a creative brief with 3 key proof points and the creator's own anecdote/use case rather than a scripted read. (3) Check whether the landing page the promo code drives to matches the audience's context — a CFO podcast listener arriving at a generic marketing homepage with no financial metrics or executive language will bounce within 15 seconds. Build a creator-specific landing page with copy aligned to the show's audience (e.g., "Built for finance and RevOps leaders, not just sales teams").

**Problem:** Self-reported attribution field shows very low creator mentions (below 5%) despite strong promo code adoption and brand search lift signals indicating the creator program is working.
**Solution:** This indicates that your creators are reaching the ICP but the audience is not directly connecting the creator touchpoint to your brand in their memory when they convert. Two fixes: (1) Train creators to make your brand association more memorable — instead of "this episode is brought to you by [Company]," ask creators to use a specific, vivid connection: "I actually used [Company] to build our team's ARR dashboard this quarter — here's what it showed me." First-person endorsement from a trusted creator increases brand recall by 3-5x vs. generic sponsorship reads. (2) Add a time-delay attribution question for later in the sales cycle — instead of (or in addition to) the form question, build an SDR-scripted question for the first discovery call: "Out of curiosity, had you heard of [Company] before this week? If so, where did you first come across us?" Aggregate these discovery call responses monthly — they capture creator attribution that form-based self-reporting misses because many B2B buyers don't consciously connect a podcast they heard months ago to the brand they're now evaluating.

**Problem:** The Creator ROI Score for a top-spend creator drops significantly month-over-month despite no change in spend or format — the CMO wants to cancel the partnership before understanding the root cause.
**Solution:** A sudden CRS decline almost always has one of three causes: (1) Audience fatigue from over-sponsorship — if your brand has been sponsoring the same creator for 6+ consecutive months, audience familiarity can suppress redemption rates even as brand lift continues. Fix: Negotiate a "dark period" of 4-6 weeks with no sponsorship → return with a new offer or product angle — redemption rates typically recover 20-40% after a rest period. (2) Creator audience demographic drift — creators grow their audiences over time, and the audience that was 60% ICP-aligned 12 months ago may now be only 35% ICP-aligned as they've attracted a broader audience. Request updated audience demographic data from the creator and recalculate the ICP Audience Match Score — if it's dropped more than 15 percentage points, renegotiate pricing to reflect the reduced ICP concentration. (3) Competitive entry into the same creator — if a direct competitor recently started sponsoring the same creator, your share of attention (and therefore brand recall) is split. Check competitor sponsorship activity via Rephonic or manual listening — if a competitor is active on the same creator, consider proposing exclusivity terms or moving budget to a creator your competitor doesn't yet sponsor.

## Version History
- v1.0: Initial creation (auto-generated)
