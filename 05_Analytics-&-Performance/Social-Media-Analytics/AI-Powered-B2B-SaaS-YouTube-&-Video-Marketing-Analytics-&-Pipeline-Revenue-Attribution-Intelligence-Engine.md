# AI-Powered B2B SaaS YouTube & Video Marketing Analytics & Pipeline Revenue Attribution Intelligence Engine - Connect Every View, Watch-Time Minute, and Subscriber to Pipeline and Revenue

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** b2b, saas, analytics, youtube, video-marketing, pipeline-attribution, revenue-attribution, video-seo, content-performance, demand-generation, dark-social, organic-growth

## Overview
Builds a comprehensive YouTube and video marketing analytics system for B2B SaaS companies that attributes pipeline influence to specific video content, tracks watch-time-to-intent signals, measures cross-platform video distribution performance, and produces a board-ready video ROI model. Use this when leadership demands proof that video content drives pipeline (not just vanity view counts), when you need to allocate budget between video content types (tutorials, thought leadership, demos, customer stories), or when your YouTube channel is growing but you can't connect it to closed-won revenue.

## Quick Copy-Paste Version

You are a senior B2B marketing analytics expert specializing in video content performance measurement and pipeline attribution for SaaS companies. I need to build a YouTube and video marketing analytics system that proves pipeline and revenue contribution.

My context:
- Company: [Company Name], selling [product] to [ICP: job titles, company sizes, industries]
- ARR: [$X] | Sales cycle: [X days average] | ACV: [$X]
- YouTube channel subscribers: [X] | Monthly views: [X] | Avg watch time: [X min]
- Video content types: [Product demos / Tutorials / Thought leadership / Customer stories / Webinar recordings / Other]
- Other video platforms: [LinkedIn Video / X/Twitter / Wistia (gated) / Loom / Other]
- CRM: [HubSpot / Salesforce]
- Current analytics tools: [YouTube Studio / GA4 / Wistia / Vidyard / VidIQ / TubeBuddy / Other]
- Biggest measurement gap: [e.g., "Can't connect video views to pipeline," "Don't know which videos drive demo requests," "YouTube grows but leads don't come from it"]

Please deliver:

1. Video Attribution Framework — A 4-tier model connecting video touchpoints (organic YouTube views, gated video plays, embedded website video, LinkedIn video reposts) to CRM pipeline stages. Include how to tag UTM parameters for YouTube traffic, set up GA4 video engagement events, and handle dark social video sharing (Slack reposts, screenshot-and-share, private DMs). Define what constitutes a "video-influenced opportunity" vs. "video-sourced opportunity."

2. B2B YouTube Channel KPI Stack — The 15 metrics that actually predict pipeline impact for B2B SaaS, organized by:
   - Audience Quality (% viewers matching ICP job titles via YouTube Analytics demographics, subscriber-to-view ratio, subscriber growth rate by content type)
   - Content Performance (average view duration %, click-through rate from impressions, save rate, top-of-funnel to mid-funnel content ratio, comment sentiment score)
   - Pipeline Signals (YouTube→website conversion rate, organic search impression share for target keywords, video-influenced MQL rate, demo request lift on weeks with new video release)
   - Revenue Correlation (video-touched accounts' win rate vs. untouched, deal velocity for prospects who watched 3+ videos, ACV premium for video-educated buyers)

3. Video Content Scoring Model — A weighted scoring formula that ranks every video by business impact (not view count):
   - Score = (Watch Time Completion % × 0.25) + (ICP Audience Match % × 0.30) + (CTR to Demo/Trial × 0.25) + (Pipeline Influence Rate × 0.20)
   - Include thresholds: Hero content (score >80), Core content (score 50-79), Pruning candidates (score <30)
   - Map each video type to its expected funnel stage and conversion benchmark

4. YouTube SEO & Organic Discovery Analytics — How to measure video SEO performance including: target keyword ranking by video, impressions vs. clicks from YouTube Search vs. Browse Features vs. Suggested, competitive share of voice for 5 priority B2B terms, transcript-to-ranking correlation analysis, and thumbnail A/B test framework with click-through rate benchmarks by video category

5. Cross-Platform Video Distribution Analytics — A unified dashboard measuring video performance across YouTube + LinkedIn Video + Website embeds (Wistia/Vidyard):
   - Platform-by-platform: views, completion rate, click-through, pipeline influence
   - Repurposing ROI: cost per view by platform vs. cost to produce
   - LinkedIn video benchmarks: 3-second view rate, full-watch rate, profile visit lift after video post
   - Gated vs. ungated video conversion: lead capture rate from Wistia/Vidyard forms

6. Board-Ready Video ROI Model — A CFO-proof calculation framework:
   - Total video investment (production + distribution + tooling + team time)
   - Video-influenced pipeline ($) and video-sourced pipeline ($) using your attribution model
   - Video ROI = (Video-Influenced Closed-Won Revenue × Attribution Weight) / Total Video Investment
   - Comparable CPL: cost per video-influenced lead vs. paid search CPL, content syndication CPL
   - Benchmark against industry: B2B SaaS video ROI ranges ($3-8 pipeline per $1 invested at mature programs)

7. 30-Day Video Analytics Quick-Start — Specific actions to implement immediately:
   - GA4 events to configure (video_start, video_progress_25/50/75/100, video_complete, cta_click)
   - UTM parameter structure for YouTube links (utm_source=youtube, utm_medium=organic, utm_campaign=[series-name], utm_content=[video-slug])
   - CRM field to add: "Video Content Engaged" checkbox + "Videos Watched Count" + "Last Video Title Watched"
   - HubSpot/Salesforce workflow: auto-tag contacts who click YouTube→website as "Video Prospect"

Output format: Executive summary (3 bullets), then each section with specific formulas, benchmark numbers, and implementation steps. No vague "track engagement" advice — every recommendation must name the specific platform, metric, field, or tool.

## Advanced Customizable Version

ROLE: You are a Principal Marketing Analytics Architect with 15 years of experience building video attribution systems for B2B SaaS companies ranging from $5M to $500M ARR. You specialize in connecting YouTube organic performance to closed-won revenue using multi-touch attribution, GA4 event architecture, and CRM integration.

CONTEXT:
Company Profile:
- Company: [Company Name]
- Product: [What it does, for whom]
- ARR: [$X] | Growth target: [X% YoY]
- ACV: [$X] | Sales cycle: [X days] | Sales motion: [PLG / Enterprise / Mid-Market / SMB]
- ICP: [Job titles] at [Company sizes/industries]

Video Program Maturity:
- YouTube channel: [Subscribers: X | Monthly views: X | Videos published: X]
- Video cadence: [X videos/month across what content types]
- Production model: [In-house / Agency / Hybrid | Budget: $X/month]
- Content pillars: [e.g., Product tutorials, Thought leadership, Customer stories, Category education]
- Video distribution: [YouTube only / YouTube + LinkedIn / Full repurposing stack]

Technology Stack:
- CRM: [HubSpot / Salesforce] with [what data currently tracked]
- Analytics: [GA4 / Amplitude / Mixpanel]
- Video hosting: [YouTube / Wistia / Vidyard / Loom]
- YouTube analytics tools: [VidIQ / TubeBuddy / Tubular / Native YouTube Studio only]
- Attribution model currently used: [First-touch / Last-touch / Linear / Data-driven / None]

Current Pain Points:
- Primary gap: [e.g., "Leadership questions video ROI monthly, I have no answer"]
- Secondary gap: [e.g., "Can't tell which video types generate demo requests"]
- Data limitation: [e.g., "YouTube Analytics and CRM are completely siloed"]

OBJECTIVE:
Build a complete video marketing analytics and pipeline attribution system. Deliverables must be immediately implementable with the stated tech stack, use real benchmark numbers, and produce outputs I can present to a CFO within 30 days.

SECTION 1 — ATTRIBUTION ARCHITECTURE
Design a multi-touch video attribution model with these components:

A) Data Collection Layer:
- GA4 implementation: List every event to configure (event names, parameters, trigger conditions) for YouTube-embedded website players and external YouTube traffic
- UTM taxonomy: Define the complete UTM structure for all video distribution channels with examples for each content type
- CRM field schema: Name every custom field/property to create in HubSpot or Salesforce, data type, and population method (manual / workflow / API)
- YouTube→CRM connection: Step-by-step method to match YouTube viewer email (from YouTube for logged-in users, from content offers, from comment CTAs) to CRM contacts

B) Attribution Logic:
- Define "video-sourced" vs. "video-influenced" with precise rules (e.g., "video-sourced = YouTube was the first touchpoint; video-influenced = watched 1+ video within 90 days of opportunity create date")
- Attribution weight for video touches in a multi-touch model (recommend specific percentage split given sales cycle length)
- Dark social handling: How to capture video-driven pipeline that doesn't show up as YouTube referral traffic (self-reported attribution survey, "How did you first hear about us?" form field analysis)
- Lookback window: Recommended attribution lookback per ACV tier (SMB <$10K ACV: 30 days, Mid-Market $10K-$100K: 90 days, Enterprise >$100K: 180 days)

C) Pipeline Stage Mapping:
- Map video content types to buyer journey stages with conversion benchmarks:
  * Awareness videos (category education, thought leadership): target metric = subscriber growth, brand search lift
  * Consideration videos (product comparisons, ROI calculators, customer stories): target metric = demo CTA click rate >2%
  * Decision videos (product demos, implementation walkthroughs, onboarding previews): target metric = trial/demo request rate >5%
  * Expansion videos (advanced tutorials, use case deep dives): target metric = feature adoption rate for customers who watch

SECTION 2 — CHANNEL PERFORMANCE ANALYTICS

YouTube Channel Health Dashboard:
Build a weekly/monthly reporting framework with these metric categories:

Tier 1 — Revenue-Predictive Metrics (review weekly):
- Video-influenced MQL rate: (MQLs with video touch / Total MQLs) × 100 | Target: >15% for mature programs
- YouTube→Demo conversion rate: YouTube referral sessions that convert to demo request | Benchmark: 1.5-4% for B2B SaaS
- Demo-influenced win rate: Win rate for deals with 3+ video views vs. 0 video views | Expected lift: +12-25%
- High-intent video watch rate: % viewers who watch Decision-stage videos | Industry benchmark: 8-15% of subscriber base

Tier 2 — Content Performance Metrics (review weekly):
- Average view duration % by content type | Benchmark: Tutorial >55%, Thought Leadership >40%, Product Demo >65%
- Click-through rate (CTR) from impressions | B2B benchmark: 4-8% (below 3% = thumbnail/title optimization needed)
- Save rate (saves per view) | Strong indicator of ICP audience; B2B benchmark >1%
- Comment sentiment score: Run comments through sentiment analysis; track % positive, % question-intent (buying signals)

Tier 3 — Audience Quality Metrics (review monthly):
- ICP job title match %: Via YouTube Analytics→Audience→Advanced Mode (requires YouTube for Business/channel >1K subs)
- Subscriber quality score: (Demo requests from YouTube subscribers / Total YouTube subscribers) × 1,000
- New subscriber source mix: YouTube Search vs. External (website embeds) vs. Suggested vs. Browse Features
- Geographic concentration: % views from target markets (country/region level)

Tier 4 — SEO & Discovery Metrics (review monthly):
- Keyword ranking: Track top 20 target keywords in YouTube Search using VidIQ or TubeBuddy; benchmark position vs. 3 competitors
- Impression share: YouTube Search impressions for target category terms
- Traffic source breakdown: YouTube Search % (target: >35% for SEO-optimized channels), Browse/Home % (target: >25% for algorithmic distribution), Suggested %
- Thumbnail CTR by content series: A/B test thumbnails; expect 15-30% improvement from optimized vs. unoptimized

SECTION 3 — VIDEO CONTENT SCORING & OPTIMIZATION MODEL

Content Performance Score Formula:
Score (0-100) = (W1 × Watch Completion %) + (W2 × ICP Audience Match %) + (W3 × CTA Click Rate) + (W4 × Pipeline Influence Rate)

Weight calibration by company stage:
- Early stage (<$10M ARR): W1=0.20, W2=0.35, W3=0.25, W4=0.20 (prioritize audience quality over scale)
- Growth stage ($10M-$50M ARR): W1=0.25, W2=0.30, W3=0.25, W4=0.20
- Scale stage (>$50M ARR): W1=0.20, W2=0.25, W3=0.25, W4=0.30 (prioritize pipeline contribution)

Score interpretation and action:
- Score 80-100 (Hero Content): Amplify with paid promotion, repurpose into lead magnets, gated versions, blog posts; this content type defines your next production sprint
- Score 60-79 (Core Content): Optimize thumbnails and titles for CTR; add end-screen CTAs; update description SEO; consider sequel or companion content
- Score 40-59 (Underperforming): A/B test thumbnail; update title with higher-intent keywords; add chapters; if no improvement in 60 days, deprioritize format
- Score <40 (Pruning Candidate): Evaluate for private/unlisting; do not invest in similar content; extract learnings for what not to produce

SECTION 4 — CROSS-PLATFORM VIDEO DISTRIBUTION ANALYTICS

Unified Video Performance Matrix (run monthly):

| Platform | Views | 25% Completion | 50% Completion | 100% Completion | CTA Clicks | Pipeline Touches |
|---|---|---|---|---|---|---|
| YouTube Organic | | | | | | |
| LinkedIn Native Video | | | | | | |
| Website Embed (Wistia/Vidyard) | | | | | | |
| YouTube Paid Promotion | | | | | | |

Platform-specific benchmarks for B2B SaaS:
- YouTube (organic): 40-55% average view duration; 2-5% CTR to website
- LinkedIn native video: 15-25% view rate (3+ seconds); 1-3% engagement rate; 0.5-1.5% click-through
- Wistia/Vidyard gated: 60-75% completion rate (self-selected high-intent audience); 15-35% form conversion rate
- LinkedIn video ads: $0.06-0.20 cost-per-view; 15-25% view rate; $25-80 CPL for B2B

Repurposing ROI Model:
- Calculate cost-per-qualified-view: Total production cost ($X) + distribution cost ($X) / Total ICP-matched views
- Benchmark: Well-run B2B video programs achieve $0.05-0.50 cost per ICP-qualified view
- Repurposing multiplier: A single video repurposed across 4 platforms typically achieves 3.5-6× total reach at marginal incremental cost

SECTION 5 — BOARD-READY VIDEO ROI REPORT TEMPLATE

Executive Summary (3 bullets for CEO/CFO):
1. "Video marketing influenced $[X] in pipeline this quarter, representing [X%] of total marketing-influenced pipeline"
2. "Video-touched prospects convert to closed-won at [X%] higher rate than non-video-touched, with [X%] shorter sales cycles"
3. "Our video ROI is $[X] pipeline per $1 invested, vs. $[X] for paid search and $[X] for content syndication"

Investment vs. Return Table:
- Total video investment (production + tools + distribution + team time at loaded cost)
- Video-sourced pipeline (opportunities where video was first touch)
- Video-influenced pipeline (opportunities where video was any touch within lookback window)
- Closed-won revenue attributed to video (using your attribution weight)
- Video program ROI (conservative: sourced-only / optimistic: fully influenced)

Benchmark comparison for CFO context:
- B2B SaaS video program benchmarks (mature programs, 2+ years): $3-8 pipeline per $1 invested
- CPL comparison: YouTube organic leads typically cost 60-80% less than comparable paid search leads
- Retention impact: Customers who engaged with 5+ tutorial videos in first 90 days have 23% higher NRR on average (source: internal cohort analysis recommendation)

CONSTRAINTS:
- Every metric must be measurable with the stated tech stack; no "custom data science model needed"
- Recommend specific tool features, not generic advice ("Use VidIQ's Keyword Research tool" not "research keywords")
- Include at least 3 industry benchmark numbers per major section to contextualize performance
- All pipeline calculations must show the formula, not just the output number
- Flag the top 3 implementation priorities for a team doing this for the first time

OUTPUT FORMAT:
1. Implementation Priority Matrix: 3×3 grid of Impact vs. Effort, naming specific actions in each quadrant
2. 30-Day Quickstart Checklist: Numbered list of exactly what to configure, in order
3. Sections 1-5 as structured above
4. Sample Dashboard Layout: ASCII-art or table showing how to arrange the weekly/monthly reporting view

## Example Input/Output

**Input Example:**
Company: Mosaic Analytics, selling financial planning software to CFOs/VPs Finance at Series B+ startups (50-500 employees)
ARR: $8M | Sales cycle: 45 days | ACV: $28,000
YouTube: 2,400 subscribers, 18,000 monthly views, 4 videos/month
Content types: Product demos (2/mo), CFO interview series (1/mo), Excel-to-Mosaic tutorial series (1/mo)
Platforms: YouTube + Wistia for gated demos
CRM: HubSpot, tracking basic UTM source but no video-specific fields
Tools: YouTube Studio only (no VidIQ/TubeBuddy)
Pain point: "I know our CFO interview series gets 800+ views per video but I have no idea if it drives demos or just entertains"

**Output Example (Section 2 excerpt):**

**Mosaic Analytics Video KPI Baseline (Month 1 Setup)**

*Revenue-Predictive Metrics — Target vs. Current:*

| Metric | Current | Month 3 Target | How to Measure |
|---|---|---|---|
| YouTube→Demo conversion | Unknown | 2.5% | GA4: YouTube referral sessions → demo_request event |
| Video-influenced MQL rate | 0% (not tracked) | 12% | HubSpot: add "Video Engaged" contact property; build list |
| CFO Interview watch-to-profile-visit | Unknown | >8% | YouTube Analytics: End Screen clicks on "About Mosaic" link |
| Tutorial completion rate | Unknown | >60% | YouTube Studio: Average % viewed by video |

*Priority #1 action: Your CFO Interview Series has 800 views/video but zero tracking downstream. Immediate fix: Add end screen to every CFO video with a "See how Mosaic works" CTA linking to demo page with UTM: utm_source=youtube&utm_medium=organic&utm_campaign=cfo-interview-series&utm_content=[guest-name]. In HubSpot, build a workflow: Contact with source "youtube/organic/cfo-interview-series" → auto-tag "CFO Interview Viewer" → enroll in accelerated demo outreach sequence. Expected result: Within 60 days you'll know exactly how many of those 800 viewers become demo requests.*

*Content Performance Score — CFO Interview Series:*
- Watch Completion %: ~48% (estimated from benchmark for talking-head interviews) → Score contribution: 48 × 0.25 = 12.0
- ICP Match % (CFO/VP Finance): ~62% based on LinkedIn audience overlap → Score contribution: 62 × 0.30 = 18.6
- CTA Click Rate: Currently 0% (no CTA configured) → Score contribution: 0 × 0.25 = 0
- Pipeline Influence Rate: Unknown → Score contribution: 0 × 0.20 = 0
- **Current Score: 30.6 / 100** — NOT because the content is bad, but because it has zero conversion infrastructure. With end screens + UTM tracking, estimated score improvement to 58-72 within 90 days.

## Success Metrics

- Video-influenced pipeline tracked and reported within 30 days of implementation
- YouTube→Demo conversion rate established as a baseline within 60 days
- At least one "Hero Content" video identified (Score >80) driving measurable pipeline
- Board-ready video ROI number calculated with actual data (not estimates) within 90 days
- CFO/leadership questions about video ROI answered with specific dollar figures, not view counts

**Leading indicators of a working system:**
- GA4 video events firing for >95% of video plays on website
- HubSpot/Salesforce contacts tagged with video engagement data rising week-over-week
- YouTube→website conversion rate established and trending (goal: >2% for B2B SaaS)
- ICP audience match % in YouTube Analytics improving as content strategy refines

## Related Prompts

- [AI-Powered B2B Organic Social Media Performance Analytics & Pipeline Revenue Attribution Intelligence Engine](./AI-Powered-B2B-Organic-Social-Media-Performance-Analytics-&-Pipeline-Revenue-Attribution-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Employee Advocacy Program Analytics & Social Selling Revenue Attribution Intelligence Engine](./AI-Powered-B2B-SaaS-Employee-Advocacy-Program-Analytics-&-Social-Selling-Revenue-Attribution-Intelligence-Engine.md)
- [AI-Powered B2B Content Marketing Performance Analytics & Content Program ROI Intelligence Engine](../../05_Analytics-&-Performance/Content-Marketing-Performance-Analytics/AI-Powered-B2B-Content-Marketing-Performance-Analytics-&-Content-Program-ROI-Intelligence-Engine.md)
- [AI-Powered B2B Multi-Touch Attribution & Revenue Marketing Intelligence Engine](../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md)

## Integration Tips

**HubSpot:**
- Create custom contact properties: "YouTube Videos Watched" (number), "Last YouTube Video Watched" (single-line text), "Video Content Series" (dropdown: Tutorial / CFO Interview / Product Demo / Customer Story), "First Video Date" (date), "Video Influenced" (checkbox)
- Build workflow: Contact with original source "Organic Search" AND visited /youtube-redirect URL → set "YouTube Traffic" = true
- Use HubSpot's "Content Engagement" report to show video-touched contacts' conversion rates vs. non-video-touched

**Salesforce:**
- Add Campaign Member record for each "YouTube Video Watch" using a custom campaign type; Campaign Influence reporting then automatically attributes pipeline to video campaigns
- Create a Flow that fires when Lead/Contact UTM Source contains "youtube" → populate custom "Video Source" field + add to Video Marketing Campaign

**GA4:**
- Custom event: `video_cta_click` with parameters `video_title`, `cta_destination`, `video_series`, `watch_percentage_at_click`
- Conversion event: Mark `demo_request` from YouTube traffic as a key conversion; add to Google Ads for YouTube ad optimization
- Audience: "Engaged YouTube Visitors" (visited site from YouTube + watched 50%+ of embedded video) → export to Google Ads for retargeting

**Wistia/Vidyard:**
- Enable Turnstile email capture at 50% watch mark for gated demos (expect 25-40% form completion from prospects who reach that point)
- Use HubSpot/Salesforce native integration to push video watch events directly to contact timeline
- Set "watched full demo video" as a HubSpot Lead Score property worth +20 points

**VidIQ / TubeBuddy:**
- Use VidIQ's Keyword Research to find keywords with >500 monthly YouTube searches AND low competition score (<40) for your category terms
- Set up competitor tracking for 5 key competitors' channels; monitor which of their video titles gain traction and create superior versions
- Use TubeBuddy's A/B thumbnail testing (requires Legend plan, ~$49/mo) to systematically improve CTR on existing top-performing videos

**Zapier:**
- Zap: New YouTube comment containing "demo", "pricing", "trial", "how do I" → create HubSpot contact + task for SDR follow-up (comment commenter often becomes a buyer)
- Zap: Weekly YouTube Analytics report → Google Sheet → Slack notification with key metrics to #marketing channel

## Troubleshooting

**Problem: YouTube Analytics shows thousands of views but GA4 shows almost no YouTube referral traffic**
*Solution:* This is normal — most YouTube viewers never click through to your website. YouTube views ≠ website sessions. The fix: (1) Add end screens to every video with explicit "click to learn more" CTAs; (2) Add a pinned comment on every video with your CTA link; (3) Include the URL in video descriptions. A 1-3% click-through rate from YouTube views to website is a healthy B2B benchmark — if you have 10,000 monthly views, expect 100-300 sessions, not thousands.

**Problem: Can't tell which specific videos are driving demo requests in HubSpot/Salesforce**
*Solution:* GA4's default attribution credits the last non-direct session, so YouTube videos that create awareness but aren't the last click get zero credit. Fix this with: (1) UTM parameters on every CTA link inside YouTube descriptions and end screens — make each video's UTM `utm_content` parameter unique to that video; (2) In HubSpot, create a custom "First YouTube Video" property populated by the first YouTube UTM hit; (3) Add self-reported attribution ("Where did you first hear about us?") to your demo request form with "YouTube video" as an option. Expect 15-25% of your video-influenced pipeline to be captured only through self-reported attribution, not click tracking.

**Problem: Leadership says YouTube performance looks great in YouTube Studio but questions whether it's worth the production cost**
*Solution:* YouTube Studio shows you audience metrics but not business metrics. The gap is the CRM→YouTube connection. To bridge it in 48 hours: Export your HubSpot/Salesforce closed-won contacts from the last 12 months. Upload the email list to YouTube Analytics' "Your Audience" comparison (under Analytics → Audience → Compare) to see what % of closed customers ever watched your YouTube content. If even 10-20% of customers touched your YouTube channel before or during their buying process, that's a revenue correlation that justifies the investment. Present this as: "X% of our closed-won customers last year engaged with our YouTube content — at our ACV of $[X], that represents $[Y] in revenue correlated with video engagement."

## Version History
- v1.0: Initial creation (auto-generated)
