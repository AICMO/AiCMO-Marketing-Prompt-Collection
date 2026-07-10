# AI-Powered B2B SaaS Employee Advocacy Analytics & Social Selling Revenue Attribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** employee-advocacy, social-selling, revenue-attribution, linkedin-analytics, dark-social, pipeline-attribution, b2b-saas, advocacy-roi, executive-branding, sales-enablement

## Overview
This prompt builds a complete employee advocacy analytics system for B2B SaaS companies — measuring how employee social content drives pipeline, quantifying the revenue contribution of individual advocates, and producing CFO-ready reporting that defends advocacy program investment. It solves the #1 problem that kills employee advocacy budgets: proving that employee LinkedIn posts and social selling activity actually convert to closed revenue, not just impressions and engagement vanity metrics.

## Quick Copy-Paste Version

You are a B2B SaaS revenue analytics expert specializing in employee advocacy and social selling measurement. I need a complete framework for measuring the pipeline and revenue impact of our employee advocacy program.

Company: [Your Company]
Product/Category: [e.g., "Sales engagement platform for enterprise B2B SaaS"]
ICP: [Job titles and company size, e.g., "VP Sales and Sales Operations leaders at B2B SaaS companies 200-2,000 employees"]
Employee Advocacy Program: [Scale and structure, e.g., "45 active advocates — 12 executives, 18 AEs/SDRs, 8 marketing team, 7 CSMs — publishing 3-5 posts/week via Bambu/EveryoneSocial"]
Monthly Advocate Social Activity: [Posts published and total estimated reach]
CRM and Analytics Stack: [e.g., "Salesforce + LinkedIn Sales Navigator + Clari + GA4"]
Primary Attribution Challenge: [e.g., "We can see our AEs' posts get strong engagement from prospects, but we can't connect that social activity to the opportunities those reps close — LinkedIn doesn't share who engaged vs. who later converted"]

Build me:

1. EMPLOYEE ADVOCACY PERFORMANCE METRICS FRAMEWORK — The 10 metrics that actually prove employee advocacy drives revenue (not engagement rates and reach), with benchmarks by advocate type (executives, sales reps, CSMs, marketing)
2. SOCIAL SELLING REVENUE ATTRIBUTION METHODOLOGY — A complete system to capture pipeline influenced by employee social activity, including LinkedIn engagement-to-CRM matching, CRM overlap analysis, and the social dark funnel attribution model
3. INDIVIDUAL ADVOCATE PERFORMANCE SCORING — A standardized scoring model to identify top advocates, underperformers, and highest-ROI social selling behaviors across the entire program
4. CONTENT TYPE PERFORMANCE INTELLIGENCE — Which post formats, content angles, and publishing behaviors generate the most pipeline per advocate — so you can coach advocates to replicate what works
5. MONTHLY ADVOCACY PROGRAM ROI REPORT — A board-ready report template that proves employee advocacy investment to a CFO who currently views it as unstructured social media time

Every metric must have a data source, calculation method, and CRM tracking requirement. No "thought leadership is hard to measure" cop-outs — this system must defend advocacy program time and tool investment to a skeptical finance team.

## Advanced Customizable Version

ROLE: You are a senior B2B SaaS revenue attribution architect with 14+ years of experience building social selling measurement systems for B2B technology companies. You have solved the LinkedIn dark social attribution problem for employee advocacy programs at companies ranging from Series B startups to $500M ARR public SaaS enterprises. Your expertise spans:
- LinkedIn analytics: impressions, engagement quality scoring, follower demographic analysis, and Sales Navigator account engagement tracking
- Social-to-pipeline attribution: CRM overlap matching between LinkedIn engaged users and CRM prospect records, Sales Navigator InMail response rate analytics, and social engagement-to-demo conversion tracking
- Employee advocacy platform analytics: Bambu, EveryoneSocial, Hootsuite Amplify, PostBeyond, and LinkedIn Elevate — extracting pipeline-relevant data from engagement dashboards
- Dark social attribution for employee social activity: connecting employee post views (non-clickers who later convert) to pipeline using CRM overlap, self-reported attribution, and cohort analysis
- Integration across Salesforce, HubSpot, LinkedIn Sales Navigator, Clari, Gong, and BI tools (Looker, Tableau, Power BI)
- Sales enablement analytics: measuring rep content sharing activity in Seismic/Highspot and correlating to deal velocity and win rate

OBJECTIVE: Build a complete, AI-executable Employee Advocacy Analytics & Social Selling Revenue Attribution System for a B2B SaaS company. Every component must be production-ready — designed so an AI agent can pull data, calculate metrics, generate insights, and produce a board-ready monthly advocacy ROI report without requiring manual analysis.

COMPANY CONTEXT:
- Company Name: [Company Name]
- Product Description: [One sentence: what it does, for whom, and the primary outcome delivered]
- Product Category: [e.g., "Sales Intelligence," "Customer Data Platform," "HR Tech"]
- ACV: [e.g., "$36,000 ACV"]
- Sales Cycle Length: [e.g., "45-75 days for mid-market, 120-180 days for enterprise"]
- ICP Job Titles: [Primary buyer personas]
- ICP Company Profile: [Company size, industry, and growth stage of ideal buyers]
- Employee Advocacy Program Inventory:
  - Executive advocates: [Number, LinkedIn follower ranges, posting frequency target]
  - Sales advocate cohort: [Number of AEs and SDRs, avg follower count, posting frequency target]
  - Marketing advocates: [Number, role types, content focus]
  - Customer Success advocates: [Number, content focus — renewal influence, expansion, referral]
  - Other advocates: [Product, Engineering, HR — any technical or cultural storytelling roles]
- Advocacy Platform: [Bambu / EveryoneSocial / Hootsuite Amplify / PostBeyond / None — organic only]
- Total Program Investment: [Time cost + platform license, e.g., "$4,500/month platform + estimated 120 hours/month of advocate time at loaded cost"]
- CRM Platform: [Salesforce / HubSpot / Pipedrive / other]
- Sales Intelligence Tool: [LinkedIn Sales Navigator / ZoomInfo / Apollo / none]
- Marketing Automation Platform: [Marketo / HubSpot Marketing / Pardot / other]
- Conversation Intelligence Tool: [Gong / Chorus / Salesloft / none]
- BI Tool: [Looker / Tableau / Power BI / Google Data Studio / spreadsheets]
- Current Attribution Gap: [Describe your top 2-3 social selling measurement challenges]

---

DELIVERABLE 1 — EMPLOYEE ADVOCACY PERFORMANCE METRICS ARCHITECTURE

Section 1A: The 10 Employee Advocacy Metrics That Actually Matter for B2B SaaS Revenue

For each metric, provide:
- Precise calculation formula
- Data source (LinkedIn analytics, advocacy platform, CRM, Sales Navigator, or conversation intelligence tool)
- B2B SaaS benchmark by advocate type (executive, AE/SDR, marketing, CSM)
- Revenue connection (why this metric predicts pipeline or revenue, not just engagement)
- Red/Yellow/Green thresholds for your program scale

TIER 1 — PIPELINE-CONNECTED METRICS (Primary — defend budget with these):

1. Social-Influenced Opportunity Rate
   - Definition: Percentage of new opportunities where the prospect Account or a Contact on the Account engaged with an employee advocate's LinkedIn content within 90 days prior to opportunity creation
   - Formula: (Opportunities where ≥1 Contact on Account engaged with advocate content in 90-day pre-opportunity window) ÷ (Total new opportunities created in period) × 100
   - Data source: LinkedIn Company Page Analytics (post engagement) + Sales Navigator Account Hub engagement alerts + CRM opportunity creation date → requires CRM overlap matching methodology (see Deliverable 2)
   - Benchmark by segment: Enterprise (ACV >$50K): 12-25% social-influenced opportunity rate for mature advocacy programs (18+ months active); Mid-market (ACV $15K-50K): 18-35%
   - Revenue connection: Prospects who engage with employee content before entering the funnel have consumed pre-sales education from a trusted peer voice — they arrive with higher intent and shorter time-to-qualification
   - Thresholds: Green >18% | Yellow 10-17% | Red <10%

2. Advocate-Sourced Pipeline ($)
   - Definition: Total open opportunity value where advocate social engagement with a prospect is the first trackable interaction (social-first pipeline)
   - Formula: SUM(Opportunity Amount) where the first logged CRM/Sales Navigator activity on the Account is an advocate LinkedIn engagement event AND the opportunity was created within 90 days of first social engagement
   - Data source: Sales Navigator engagement data exported to CRM + opportunity creation date
   - Benchmark: Mature advocacy programs (12+ months) generate 6-18% of total pipeline with social-first attribution; early-stage programs (<6 months) typically attribute 2-5%
   - CRM tracking: Requires a custom CRM field "First Social Touch Date" and "Social Advocate Name" on the Contact record, populated when Sales Navigator flags an inbound LinkedIn engagement from a prospect

3. Social Selling Assist Rate (Pipeline Acceleration)
   - Definition: Percentage of closed-won deals where the AE had meaningful LinkedIn engagement (≥3 advocate-to-prospect or prospect-to-advocate LinkedIn interactions) with a contact on the deal, indicating social relationship built during the sales cycle
   - Formula: (Closed-won deals with ≥3 LinkedIn engagement events between AE and ≥1 deal contact in 90 days prior to close) ÷ (Total closed-won deals in period) × 100
   - Data source: Sales Navigator InMail + connection request + content engagement data → manual weekly export or Sales Navigator API → CRM activity log
   - Benchmark: AEs with active social selling behaviors (>4 posts/week, daily Sales Navigator engagement) show 15-30% higher deal win rates vs. AEs with minimal social activity — measure the correlation at your own company by cohort analysis (see Section 1B)
   - Thresholds: Green >25% Social Selling Assist Rate | Yellow 12-24% | Red <12%

4. Executive Thought Leadership Pipeline ROI Multiplier
   - Definition: Total pipeline attributed to executive advocate content ÷ total cost of executive social media investment (writing support, photography, posting time at executive hourly rate)
   - Formula: (Executive-attributed pipeline) ÷ (Executive advocacy program cost) in same quarter
   - Executive advocacy program cost = (Platform license pro-rated to executives) + (Ghostwriter/content support cost) + (Executive time: avg hours/month × loaded hourly rate)
   - Data source: CRM pipeline report filtered to executive social-attributed opportunities + finance cost data
   - Benchmark: Executive advocate programs should generate 8-20x pipeline ROI multiplier for B2B SaaS companies where the executive has >5,000 ICP-relevant followers; below 5x warrants restructuring the content strategy
   - Why it matters: Executive content generates 3-5x more engagement per impression than individual contributor content because audiences perceive executive perspectives as category intelligence rather than promotional content

5. Social Selling Index (SSI) to Quota Attainment Correlation
   - Definition: Correlation coefficient between an AE or SDR's LinkedIn Social Selling Index score and their quarterly quota attainment — the primary metric proving that investment in sales team social activity drives revenue results
   - Formula: Calculate Pearson correlation coefficient: r(SSI quartile, quota attainment) across all AEs with ≥6 months of LinkedIn activity data
   - Data source: LinkedIn Sales Navigator SSI scores (exported monthly per rep) + CRM quarterly quota attainment data
   - Benchmark: Studies across mid-market B2B SaaS consistently show r = 0.35-0.62 correlation between SSI score and quota attainment — reps in the top SSI quartile typically attain 20-35% more quota than the bottom quartile
   - Action: If correlation is <0.25 at your company → the SSI score isn't reflecting revenue-generating behavior (reps are gaming activity metrics without building genuine relationships) → audit which SSI sub-components are inflated

TIER 2 — PROGRAM HEALTH METRICS (Leading Indicators of Future Pipeline):

6. ICP Audience Engagement Rate
   - Definition: Percentage of a given advocate's post engagements (likes, comments, shares, reposts) that come from contacts matching your ICP — the quality filter on raw engagement numbers
   - Formula: (Engagements from ICP job titles + ICP company sizes) ÷ (Total engagements) × 100
   - Data source: LinkedIn post analytics "Who viewed your post" breakdown (by job title and company) + cross-reference against CRM or ICP definition
   - Benchmark: ICP Engagement Rate >35% = Strong ICP reach; 20-35% = Moderate — content resonates but reaches a broad audience; <20% = Content is attracting the wrong audience or the advocate's follower base needs building in the target ICP segment
   - Why it matters: 10,000 impressions from marketing managers at SMBs is worthless for an enterprise B2B SaaS company; 400 impressions from VP of Operations at companies 500-5,000 employees = significant pipeline potential

7. Content-to-Connection Pipeline Rate
   - Definition: Rate at which new LinkedIn connections from ICP-matched prospects (who connected after engaging with advocate content) convert into CRM opportunities within 120 days
   - Formula: (New CRM opportunities where Contact first connected with advocate on LinkedIn ≤120 days before opportunity creation) ÷ (Total new ICP-matched LinkedIn connections in period) × 100
   - Data source: LinkedIn connection history export + CRM Contact creation date + opportunity association date
   - Benchmark: Top-performing social sellers convert 5-15% of new ICP connections to CRM opportunities within 120 days; industry average is 1.5-4%
   - High-intent signal: Prospects who connect after engaging with educational content (not after receiving a direct outreach request) convert at 2-3x the rate of connections initiated via cold InMail

8. Advocacy Post Reach-to-ICP Penetration Score
   - Definition: Estimated number of ICP-matched unique individuals reached per post × engagement quality weighting — a normalized measure of how effectively the advocacy program is penetrating the target buyer universe
   - Formula: ICP Penetration Score = (Estimated ICP impressions per post) × (1 + ICP Engagement Rate) × (Content Quality Multiplier)
   - Content Quality Multiplier: Comment rate >0.5% = 1.3x; 0.2-0.5% = 1.0x; <0.2% = 0.8x — weighted because comments signal genuine intellectual engagement vs. passive scrolling
   - Data source: LinkedIn analytics (impressions) × estimated ICP % of audience (from follower demographics)
   - Monthly aggregate: Sum all advocate ICP Penetration Scores → compare month-over-month → leading indicator of pipeline growth 60-90 days forward

9. Social Engagement Signal-to-Outreach Conversion Rate
   - Definition: Percentage of prospect LinkedIn engagement events (likes, comments, shares on advocate posts) that SDR/AE teams convert into meaningful outreach responses — the metric connecting social intelligence to sales motion
   - Formula: (LinkedIn engagement events that triggered outreach attempts AND received a positive response or meeting booked) ÷ (Total LinkedIn engagement alerts acted upon) × 100
   - Data source: Sales Navigator engagement alerts + CRM activity log (outreach sequences with social touch trigger)
   - Benchmark: Outreach triggered by genuine content engagement (prospect commented thoughtfully) converts at 12-28%; outreach triggered by a like alone converts at 2-6% — this data point should drive your SDR alert-to-action prioritization rules
   - Implementation: Build a CRM workflow: when Sales Navigator flags a prospect engagement on advocate content → create a CRM task for the assigned AE/SDR with the engagement context and a suggested personalized follow-up opening line

10. Monthly Active Advocate Retention Rate
    - Definition: Percentage of enrolled program advocates who published ≥2 pieces of LinkedIn content in the current month — the foundational health metric for program sustainability
    - Formula: (Advocates who published ≥2 posts in month) ÷ (Total enrolled advocates) × 100
    - Data source: Advocacy platform activity dashboard or LinkedIn analytics for enrolled advocates
    - Benchmark: >65% monthly active rate = healthy program; 40-65% = moderate engagement drop-off requiring content support intervention; <40% = structural program failure — advocates lack content, time, or perceived value of participation
    - Why it matters: Pipeline attribution from advocacy requires consistent publishing cadence — a program where 80% of advocates post once per quarter generates 80% less pipeline than one where 80% post weekly

---

Section 1B: Advocate Cohort Analysis — Social Sellers vs. Non-Social Sellers

The most compelling proof of advocacy program value is a direct cohort comparison: do AEs and SDRs who actively use social selling close more revenue than their non-social peers?

Cohort Design:
- HIGH SOCIAL: AEs with SSI >70 AND posting frequency >3x/week AND ≥20 Sales Navigator engagement alerts acted upon per month
- LOW SOCIAL: AEs who posted <2x/month AND have SSI <50

Metrics to compare (matched by territory, ACV band, and tenure):
| Metric | High-Social Cohort | Low-Social Cohort | Expected Differential |
|---|---|---|---|
| Quarterly quota attainment | Measure | Measure | High-Social typically 18-32% higher |
| Average deal size | Measure | Measure | High-Social typically 8-15% larger ACV |
| Sales cycle length (days) | Measure | Measure | High-Social typically 12-22% shorter |
| Pipeline coverage ratio | Measure | Measure | High-Social typically 0.4-0.8x higher coverage |
| Win rate vs. competition | Measure | Measure | High-Social typically 10-20% higher win rate |
| Outbound response rates | Measure | Measure | High-Social typically 2-4x higher response rates |

Run this analysis quarterly. A statistically significant differential (n>15 per cohort, p<0.05) becomes the primary business case for expanding the advocacy program to under-active reps and executives.

---

Section 1C: Metrics Reporting Cadence

| Metric | Cadence | Owner | Audience |
|---|---|---|---|
| Monthly Active Advocate Rate | Weekly | Advocacy Manager | CMO, VP Sales |
| ICP Audience Engagement Rate | Per post batch | Advocacy Manager | Advocacy Manager |
| Social Engagement Signal-to-Outreach Rate | Weekly | Sales Ops | VP Sales, SDR Manager |
| Social-Influenced Opportunity Rate | Monthly | Marketing Ops | CMO, CRO |
| Advocate-Sourced Pipeline | Monthly | Marketing Ops | CMO, CFO |
| Executive TL Pipeline ROI Multiplier | Quarterly | CMO | CEO, CFO, Board |
| SSI-to-Quota Correlation | Quarterly | Sales Ops | VP Sales, CRO |
| Social Selling Assist Rate | Quarterly | Sales Ops | VP Sales, CMO |

---

DELIVERABLE 2 — SOCIAL SELLING REVENUE ATTRIBUTION METHODOLOGY

Section 2A: Why Employee Advocacy Has a Structural Attribution Problem

Employee advocacy faces the same dark social attribution challenge as creator marketing — but with an additional layer of complexity:

The problem: A VP Operations at a 500-person SaaS company sees your Head of Revenue Operations post about ARR bridge analysis on LinkedIn (passive impression — no click, no engagement). Two weeks later, they mention your company in a budget planning call. Three months later, an SDR cold-calls them and they say "actually, I've heard of you." The deal closes 90 days later.

Your attribution model shows: SDR-sourced, outbound. Employee advocacy post that created brand awareness and pre-disposed the VP to your brand: ZERO credit.

This is the structural dark funnel problem for all employee advocacy content — and it's estimated to represent 55-75% of the actual pipeline influence employee advocacy generates.

Section 2B: Four-Layer Employee Advocacy Attribution Architecture

LAYER 1 — LINKEDIN ENGAGEMENT-TO-CRM OVERLAP (Highest confidence signal)

Implementation:
1. Weekly LinkedIn analytics export: Export all accounts and job titles who engaged with advocate posts (likes, comments, reposts) from LinkedIn Company Page analytics and Sales Navigator account engagement data
2. CRM matching: Cross-reference engaged LinkedIn accounts against open CRM prospect accounts and contacts — match on Company Name (fuzzy), LinkedIn Company ID (exact), and Contact Job Title
3. CRM enrichment: When a match is found, create a CRM Activity record: "LinkedIn Engagement — [Advocate Name] — [Post Date] — [Engagement Type]" linked to the Contact record
4. Opportunity association: When a matched Contact is added to an opportunity → opportunity tagged "Social Touch Pre-Opportunity"

Benchmark: Typically 15-30% of engaged LinkedIn accounts for B2B SaaS advocacy programs are already CRM contacts or accounts — these represent the highest-value social selling signals because the prospect is actively demonstrating interest in your team's expertise

Tooling options: Manual export → VLOOKUP/Python matching → CRM import; OR Pharos (LinkedIn→CRM) OR Shield Analytics (advocacy platform → CRM integration); OR native Sales Navigator → Salesforce / HubSpot integration which logs account engagement automatically

LAYER 2 — SELF-REPORTED FIRST TOUCH ATTRIBUTION (High signal, moderate volume)

Implementation:
- Add to every demo request and inbound trial form: "How did you first hear about [Company Name]? (Be specific — heard from a colleague, followed someone from your team on LinkedIn, read about you in a newsletter, etc.)"
- Field type: Open text — NOT dropdown (dropdowns suppress social mentions by 60%)
- CRM sync: "Self-Reported First Touch" custom text field on Lead/Contact record

AI Agent NLP Classification for Employee Advocacy Signals:
- Contains employee name from active advocate list → tag: "Employee-Advocacy-[EmployeeName]"
- Contains "followed your [role] on LinkedIn" or "saw your team's posts" → tag: "Employee-Advocacy-General"
- Contains "colleague recommended" + "they showed me your content" → tag: "Employee-Advocacy-Peer-Referral"
- Contains "listened to your podcast" or "saw your article" → classify separately (creator/content channel)

Monthly aggregate: Employee advocacy mentions in self-reported field ÷ total responses = Employee Advocacy Self-Report Rate
Benchmark: For programs with 40+ active advocates, target 5-15% of new leads citing employee content or employee LinkedIn connections as first awareness

LAYER 3 — SALES NAVIGATOR ALERT-TO-PIPELINE TRACKING (Medium confidence, structured data)

Implementation:
1. Configure Sales Navigator saved lead lists: all CRM accounts in active sales stage → Sales Navigator "Buyer Intent" and "Account IQ" alerts enabled
2. Alert-to-CRM workflow: When Sales Navigator fires an engagement alert (prospect viewed rep profile, liked rep content, engaged with company page) → auto-create a CRM Activity in the associated account record
3. Sequence trigger: If CRM Activity type = "Sales Navigator Social Engagement" AND Account Stage = "Target/Open" → trigger SDR outreach sequence with social engagement context as first line personalization
4. Closed-loop tracking: Tag all opportunities that have ≥1 "Sales Navigator Social Engagement" activity in the 90 days before opportunity creation → monthly report: pipeline influenced by social signals from Sales Navigator

Benchmark: Sales Navigator alert-based outreach generates 2.5-4x higher response rates than cold outreach with no social signal — this data point, pulled from your own CRM sequences, is compelling evidence for expanding Sales Navigator seat investment

LAYER 4 — BRAND SEARCH LIFT CORRELATION (Dark funnel proxy measurement)

For executive advocates with large followings (>5,000 ICP-relevant followers), treat branded search volume as a proxy for advocacy-driven awareness:

Weekly methodology:
1. Tag each major executive post with category: "Thought Leadership," "Customer Story," "Product Insight," "Industry Data," "Career/Culture"
2. Log publication date + estimated reach for each post → executive content calendar in shared spreadsheet
3. Pull Google Search Console branded query data weekly
4. Calculate brand search lift in the 7-14 days following executive posts with estimated reach >10,000 impressions
5. Identify which content categories (thought leadership vs. product vs. customer stories) generate the strongest brand search lift correlation

Expected finding: Executive thought leadership posts on category-level problems (not product features) generate 8-30% branded search lift in the 7-14 days following publication for B2B SaaS companies with executive audiences concentrated in the ICP

---

DELIVERABLE 3 — INDIVIDUAL ADVOCATE PERFORMANCE SCORING

Section 3A: Advocate Value Score (AVS) — Standardized 100-Point Model

The Advocate Value Score enables fair comparison across executives, AEs, SDRs, CSMs, and marketing team members despite completely different roles and audience sizes.

AVS = (Pipeline Influence Score × 0.40) + (ICP Reach Quality Score × 0.30) + (Engagement Conversion Score × 0.20) + (Program Consistency Score × 0.10)

Pipeline Influence Score (0-100):
- Measures direct and assisted pipeline attribution within 90 days of the advocate's social activity
- Sources: CRM social-influenced opportunity data (Layer 1) + self-reported attribution mentions of the advocate's name (Layer 2) + Sales Navigator engagement-to-pipeline tracking (Layer 3)
- Scoring: No pipeline influence = 0-15pts; 1-2 influenced opportunities/quarter = 16-40pts; 3-5 opportunities/quarter = 41-70pts; 6+ opportunities/quarter = 71-100pts
- For CSM advocates: substitute "pipeline" with "expansion ARR influenced" — CSM social content that drives upsell awareness is an equivalent value contribution

ICP Reach Quality Score (0-100):
- Measures whether the advocate is actually reaching ICP-matched prospects with their content
- Formula: (ICP Audience Engagement Rate) × (Monthly Post Reach in ICP impressions ÷ program average) normalized to 0-100 scale
- An advocate with 40% ICP engagement rate and 3x program-average ICP reach scores higher than a high-follower advocate whose audience is primarily peers and competitors
- Scoring: ICP Engagement Rate <15% = 0-20pts regardless of reach; 15-25% ICP rate = 21-45pts; 25-40% = 46-70pts; >40% = 71-100pts (adjusted upward by reach multiplier)

Engagement Conversion Score (0-100):
- Measures whether the advocate's social activity generates outreach response and meeting conversion
- Formula: (Sales Navigator alert-to-meeting rate for this advocate's accounts) × 100 + (Self-reported attribution mentions of advocate name / advocate's monthly unique ICP impressions) × 1000
- Benchmark: Top social sellers generate 1 meeting booked per 500-1,500 ICP impressions; average is 1 per 3,000-8,000 impressions

Program Consistency Score (0-100):
- Measures posting cadence, content quality compliance, and program tool engagement
- Formula: (Posts published ÷ posts targeted in month) × 50 + (Advocacy platform usage: log-in + content sharing compliance) × 30 + (Sales Navigator usage: active alerts + profile views) × 20
- Thresholds: <50 = 0-25pts; 50-75 = 26-55pts; 75-90 = 56-80pts; >90 = 81-100pts

Section 3B: Advocate Segmentation Matrix

AVS 75-100 (Top Tier — Revenue Generators):
- 90-day action: Feature in internal advocacy newsletter as program examples; offer 1:1 content strategy coaching; consider amplifying their top content with paid promotion (Thought Leader Ads); provide LinkedIn Sales Navigator premium seats if not already assigned

AVS 50-74 (Mid Tier — Engaged but Sub-Optimal):
- 90-day action: Identify specific AVS sub-score that's dragging overall score; create targeted intervention (ICP Reach Quality low → audit follower demographics and adjust content angle; Engagement Conversion low → improve SDR alert response workflow)

AVS 25-49 (Low Tier — Posting Without Impact):
- 90-day action: 1:1 review with advocate manager; assess whether content topic mismatch, audience size problem, or engagement-to-sales workflow failure is the root cause; provide a 30-day sprint plan with specific milestones

AVS <25 (Inactive or Misaligned — Program Risk):
- 90-day action: Formal re-enrollment conversation; if posting frequency <2x/month consistently → offer to remove from program and redirect content support resources to mid-tier advocates who will use them

Section 3C: Advocate Performance Dashboard

| Advocate | Role | AVS | Pipeline Score | ICP Reach Score | Engagement Conversion | Consistency | Active Pipeline Influenced | 90-Day Action |
|---|---|---|---|---|---|---|---|---|
| [Exec A] | CRO | 87 | 90 | 85 | 82 | 91 | $1.2M | Scale — allocate ghostwriting support |
| [AE B] | Mid-Market AE | 74 | 68 | 76 | 71 | 81 | $340K | Maintain — improve ICP targeting in content |
| [CSM C] | Enterprise CSM | 61 | 55 | 70 | 58 | 60 | $180K expansion | Coach — stronger expansion content focus |
| [SDR D] | Outbound SDR | 38 | 30 | 42 | 40 | 40 | $0 — no pipeline yet | Review — SDR has strong posting but alert-to-outreach not converting |
| [IC E] | Marketing PMM | 22 | 10 | 30 | 20 | 28 | $0 | Re-enroll or pause — minimal ICP reach and no pipeline signal |

---

DELIVERABLE 4 — CONTENT TYPE PERFORMANCE INTELLIGENCE

Section 4A: Content Performance Taxonomy

Classify all advocate posts into 8 content types and measure pipeline correlation for each:

| Content Type | Definition | Example | Expected ICP Engagement Rate | Expected Pipeline Influence Rate |
|---|---|---|---|---|
| Category Intelligence | Original point of view on an industry trend, not product-specific | "Why the 2026 CFO isn't buying software the same way they did in 2023 — and what that means for SaaS vendors" | High (35-55%) | Highest — drives brand awareness among category-aware buyers |
| Customer Outcome Story | Real customer result, told through the advocate's lens | "Watched a customer go from 14-week sales cycles to 9 weeks after implementing X. Here's the 3 things they changed." | High (30-50%) | High — creates proof at the right stage for mid-funnel prospects |
| Practitioner Framework | A specific methodology, template, or process that the ICP can immediately use | "The 5-step RevOps forecast review I run every Monday with my team — steal this" | High (40-60%) | High — establishes practitioner authority; saves come from ICP researchers |
| Company News Amplification | Sharing a press release, blog post, or company announcement | "We just closed our Series C! Excited to share..." | Low (8-18%) ICP engagement | Low — company news rarely drives cold prospect engagement |
| Product Feature Content | Promoting a product feature or capability | "New feature: [Feature Name] is live. Here's how it works." | Low-Moderate (10-22%) | Moderate for in-funnel prospects, low for cold awareness |
| Culture/Team Content | Team celebrations, hiring announcements, company culture | "Thrilled to welcome [Name] to the team as our new VP of X!" | Very Low ICP engagement | Minimal pipeline correlation — employer brand, not demand gen |
| Earned Media Amplification | Sharing a podcast appearance, byline, or media coverage | "Joined [Podcast Name] this week to talk about X. Key takeaway:" | Moderate (20-35%) ICP | Moderate — credibility signal for prospects already aware |
| Conversation Starter | Direct question to the audience to drive comments | "RevOps leaders: What's your #1 challenge with multi-source attribution right now?" | Moderate-High (25-45%) ICP | High comment engagement but lower direct pipeline attribution — use strategically |

Section 4B: Content Performance Reporting by Type

Monthly AI agent workflow:
1. Pull all advocate posts from advocacy platform + LinkedIn analytics exports for the month
2. Classify each post by content type (AI NLP classification against the taxonomy above)
3. Calculate per-post: ICP impressions, ICP engagement rate, saves, comments, Sales Navigator alert spike correlation (for advocates with Sales Navigator data)
4. Aggregate by content type: average metrics by category across all advocates
5. Identify top 3 performing post examples (by ICP engagement rate) in each content type → distribute to advocacy manager for internal example library

Monthly Content Intelligence Report output:
- Which content types are generating the most ICP engagement this month (ranked)
- Which content types are underperforming vs. 90-day baseline (flag for coaching)
- Top 5 individual posts by ICP Reach Quality Score across all advocates
- Recommended content type emphasis for next month (based on pipeline cycle — e.g., increase customer outcome stories when pipeline coverage is low; increase category intelligence posts when building awareness for a new ICP segment)

Section 4C: Post Timing and Format Optimization Intelligence

Publishing Pattern Analysis (run quarterly):
- Pull posting timestamps for all advocate posts in the past quarter
- Calculate average ICP engagement rate by: day of week, time of day, post format (text-only, image, document/carousel, video, article)
- Identify top 3 posting windows by ICP engagement rate at your specific company
- Benchmark against LinkedIn general data (Tuesday-Thursday 8-10 AM local = typically peak B2B engagement) but validate against your specific ICP behavior — enterprise buyers in different time zones and roles have different consumption patterns

Format Performance Benchmarks (B2B SaaS):
- Document/carousel posts: Highest save rate (3-5x text posts) — signals content useful enough to reference later; strong pipeline correlation
- Text-only posts with a numbered list: Highest comment rate for thought leadership content — drives algorithm amplification
- Native video (recorded on phone, not produced): Higher reach than polished video for advocates with <10K followers — authenticity signal
- External link posts (sharing an article): Lowest reach (LinkedIn suppresses external link posts algorithmically) — minimal as advocacy format

---

DELIVERABLE 5 — MONTHLY ADVOCACY PROGRAM ROI REPORT

Section 5A: Board-Ready One-Page Advocacy ROI Summary

EMPLOYEE ADVOCACY PROGRAM REVENUE CONTRIBUTION REPORT
[Company Name] | [Month/Year]

PIPELINE IMPACT
- Social-Influenced Opportunities Opened: [XX] opportunities ($[X.XM] pipeline) where prospect engaged with employee content in 90 days prior
- Advocate-Sourced Pipeline (Social-First Attribution): $[XXX,XXX] — opportunities where first CRM touch = social engagement event
- Self-Reported Employee Advocacy Attribution: [XX] new leads credited employee/executive content as first awareness
- Executive Thought Leadership Estimated Pipeline Contribution (modeled): $[XXX,XXX]
- Total Advocacy-Attributed + Influenced Pipeline: $[X.XM] ([X.X%] of total open pipeline)
- Closed-Won Revenue with Social Touch in 90-Day Pre-Close Window: $[XXX,XXX]

EFFICIENCY METRICS
- Total Program Investment (Platform + Estimated Advocate Time): $[XX,XXX]/month
- Direct Attribution Pipeline ROI: [X.Xx] (attributed pipeline ÷ program cost)
- Full-Funnel Pipeline ROI (with modeled influence): [X.Xx]
- Social Selling CAC (Tracked): $[XX,XXX] vs. Blended Marketing CAC $[XX,XXX]
- Social Selling CAC Index: [X.Xx] (<1.0 = Social selling more efficient than blended average)

PROGRAM HEALTH
- Monthly Active Advocates: [XX] / [XX] enrolled ([X.X%] active rate)
- Total ICP Impressions (Estimated): [XXX,XXX] across all advocates
- Top Performing Advocate: [Name, Role] — AVS [XX], influenced $[XXX,XXX] in pipeline
- Content Type Driving Most Pipeline This Month: [Content Type]
- Sales Navigator Alert-to-Meeting Rate: [X.X%] ([XX] meetings booked from social signals)

SSI-TO-REVENUE CORRELATION UPDATE
- Top SSI Quartile AEs (SSI >70): [X.X%] avg quota attainment
- Bottom SSI Quartile AEs (SSI <50): [X.X%] avg quota attainment
- Differential: [+X.X%] — social sellers outperforming non-social sellers by [X.Xx]

KEY INSIGHT THIS MONTH: [AI-generated 1-sentence insight, e.g., "Customer Outcome Story posts are generating 2.8x the ICP engagement rate of Company News amplification — recommend shifting 40% of executive content from announcement amplification to customer story formats in Q4 to maximize pipeline influence per post."]

RECOMMENDED ACTION FOR NEXT MONTH: [One specific, data-backed recommendation]

---

AI AGENT EXECUTION WORKFLOW:

WEEKLY (Every Monday):
1. Pull Sales Navigator engagement alerts from the past 7 days → match to CRM accounts → create CRM Activity records for all ICP-matched social engagements
2. Pull LinkedIn post analytics for all advocate posts published in past 7 days → classify by content type → calculate ICP engagement rate for each post
3. Check weekly posting cadence compliance → flag advocates who haven't posted in 10+ days → trigger automated reminder (via advocacy platform or Slack integration)
4. Pull branded query impressions from Google Search Console → correlate with executive post publication dates from previous week → update executive content lift tracker

MONTHLY (First Monday):
1. Aggregate all weekly social engagement data → run CRM overlap matching → generate Social-Influenced Opportunity report
2. Calculate Advocate Value Scores for all enrolled advocates → update AVS dashboard → identify top tier, mid tier, and underperformers
3. Calculate SSI scores for all AE/SDR advocates (pull from Sales Navigator) → update SSI-to-quota-attainment correlation model
4. Run self-reported attribution NLP classification on all new leads created in month → count employee advocacy mentions
5. Generate content performance report by type → identify top-performing posts → prepare for internal content library distribution
6. Calculate program ROI metrics → generate board-ready Advocacy Revenue Contribution Report
7. Distribute report to CMO, CRO, VP Sales via automated email or Slack digest

QUARTERLY (Program Review):
1. Run full cohort analysis: High-Social vs. Low-Social AE cohort comparison → present to VP Sales with quota attainment differential
2. Evaluate advocate roster: expand program to under-active departments; remove consistently inactive advocates
3. Conduct advocate skills assessment: identify top 3 content type gaps based on quarterly content performance data → design targeted enablement session
4. Review advocacy platform contract and ROI: calculate total program investment vs. total pipeline attribution → make renewal/tier decision
5. Present Executive Advocate Program ROI to CEO with trailing 4-quarter pipeline contribution trend

CONSTRAINTS:
- All pipeline attribution claims must clearly distinguish between "tracked" (CRM overlap match, Sales Navigator alert, self-reported) and "modeled" (brand search correlation, cohort-based estimation) to maintain Finance credibility
- SSI-to-quota correlation must use matched cohorts (same territory, ACV band, tenure) — un-matched comparisons will be challenged by skeptical sales leaders as selection bias
- Social Selling Assist Rate analysis requires minimum 90-day attribution window — 30-day windows systematically miss the early social touches that influenced deals that close later
- AVS scores must be refreshed monthly — advocate performance changes with content strategy shifts, follower audience evolution, and changes in their book of business
- Never present impressions or follower counts as primary ROI metrics to CMO or CFO — always tie back to pipeline influenced, meeting conversion rates, or win rate differentials

OUTPUT FORMAT:
Deliver all 5 sections as complete, production-ready frameworks. All scoring models should include worked examples. The board report template should be populated with realistic placeholder values. Every metric must be traceable to a specific data source and CRM implementation requirement so a Sales Ops or Marketing Ops analyst can build it without a data engineering team.

## Example Input/Output

**Input Example:**

- Company: Sightline (fictional) — Sales Intelligence Platform for B2B SaaS
- Product: Account intelligence and buying signal platform for B2B SaaS revenue teams — helps SDRs and AEs prioritize outbound and time outreach to peak intent moments
- ICP: VP Sales, VP Revenue Operations, and Director of Sales Operations at B2B SaaS companies ($15M-$200M ARR)
- ACV: $32,000; Sales cycle: 45-90 days mid-market
- Employee Advocacy Program: 38 active advocates — 3 executives (CEO, CRO, CMO), 14 AEs/SDRs, 9 marketing team, 6 CSMs, 6 product/engineering
- Advocacy Platform: EveryoneSocial — advocates share company content + publish original content from personal profiles
- Total Program Investment: $3,200/month EveryoneSocial license + estimated 85 hours/month advocate time (loaded at $85/hr avg) = $10,425/month total
- CRM: Salesforce; Sales Navigator: Enterprise (22 AE/SDR seats); Analytics: Tableau
- Attribution Challenge: "Our CRO posts consistently get 400-600 engagements with 35% coming from VP Sales and RevOps titles. We know she's building brand familiarity but we can't quantify how much pipeline she's driving vs. our outbound SDR team — and the CFO wants to cut her content support budget."

**Output Example (Excerpts):**

**Executive Thought Leadership ROI Analysis — Q3 2026 (CRO Advocate):**

LinkedIn Post Analytics (Q3 2026 — CRO):
- Posts published: 34 (avg 2.6/week)
- Total impressions: 287,000
- Estimated ICP impressions (VP Sales + RevOps titles × company size filter): 89,000 (31% ICP concentration)
- Average ICP Engagement Rate: 38.4%
- Top content type by ICP engagement: Practitioner Frameworks (avg 42% ICP rate) > Customer Outcome Stories (38%) > Category Intelligence (35%) > Company News (11%)

CRM Overlap Analysis (Q3):
- LinkedIn engagement events from ICP-matched accounts: 1,847 individual engagement actions
- Matched to CRM accounts: 412 unique accounts (out of 1,847 engagement actions — multiple touches per account)
- Of 412 CRM-matched accounts: 71 (17.2%) had an opportunity created within 90 days of first social engagement
- Avg opportunity value in social-influenced deals: $34,800 (8.7% above company average — early social education effect on deal size)
- Social-influenced pipeline from CRO alone (Q3): $2,470,800

Brand Search Lift Correlation:
- CRO Practitioner Framework posts with >15K impressions: avg +22.3% branded search lift in 7-14 days post-publication
- CRO Customer Story posts: avg +14.7% lift
- CRO Company News posts: avg +3.1% lift (not statistically significant)

**Executive Advocacy Program ROI — Q3 2026:**

Total investment (3 executives × avg content support cost): $8,400/quarter
Executive-attributed + influenced pipeline (all 3 executives): $3.8M
Executive Advocacy Pipeline ROI: 45.2x ($3.8M ÷ $84K quarterly investment)
Executive social-first sourced closed-won Q3: $486,000 ARR

CFO Talking Point: "Our executive advocacy program generates $45 of pipeline for every $1 invested — making it our 3rd highest ROI demand channel behind organic SEO and customer referrals. The CRO's LinkedIn program alone is influencing 17% of opportunities in her content's target accounts. Cutting the $3,200/month content support would risk ~$1.2M of quarterly pipeline influence."

**Sales Team SSI-to-Quota Correlation (Q3 2026 — n=22 AEs):**

| SSI Quartile | Avg SSI Score | Q3 Quota Attainment | Avg ACV Closed | Avg Deals Won |
|---|---|---|---|---|
| Q4 (Top) | 81.3 | 118% | $34,200 | 4.2 |
| Q3 | 71.4 | 102% | $31,800 | 3.6 |
| Q2 | 58.9 | 87% | $29,400 | 3.0 |
| Q1 (Bottom) | 43.2 | 74% | $26,900 | 2.5 |

Correlation coefficient: r = 0.61 (strong positive correlation — top SSI quartile attains 44% more quota than bottom quartile)
Pipeline finding: AEs in top SSI quartile had 23% of their opportunities include ≥1 "Sales Navigator Social Engagement" CRM activity in 90 days pre-opportunity — vs. 4% for bottom quartile. This confirms the behavioral pathway: high SSI AEs are using social signals to identify and engage warm prospects before cold outreach.

## Success Metrics

- **Monthly Active Advocate Rate:** Target >65% of enrolled advocates publishing ≥2 posts/month — below 50% signals program sustainability risk requiring immediate content support or re-enrollment intervention
- **Social-Influenced Opportunity Rate:** Target 15-30% of new opportunities with at least one advocate social engagement event in the 90-day pre-opportunity window — below 8% suggests advocate content isn't reaching ICP accounts in the pipeline
- **Advocate Value Score Portfolio Average:** Target AVS >55 across active advocates; below 45 indicates the program needs significant coaching, content strategy revision, or roster pruning
- **SSI-to-Quota Attainment Differential:** Top SSI quartile AEs should close 15-35% more quota than bottom quartile — below 10% differential suggests SSI isn't reflecting actual social selling behavior (activity gaming) or that social selling isn't yet operationalized in the sales motion
- **Self-Reported Advocacy Attribution Rate:** For programs with 30+ advocates, target 5-15% of new leads citing an employee or executive by name as their first awareness — below 3% indicates the program isn't penetrating the ICP at meaningful scale
- **Executive TL Pipeline ROI Multiplier:** Target 15-40x for executive advocates with >3,000 ICP-relevant followers — below 8x warrants restructuring executive content strategy toward practitioner frameworks and customer stories
- **Sales Navigator Alert-to-Meeting Rate:** Target 8-18% of acted-upon engagement alerts generating a positive response or meeting — below 5% signals outreach personalization failure or poor alert prioritization (reps are acting on low-intent signals like single "likes" rather than comments or saves)

## Related Prompts

- [AI-Powered B2B SaaS Creator & Influencer Marketing Performance Analytics & Pipeline Revenue Attribution Intelligence Engine](./AI-Powered-B2B-SaaS-Creator-&-Influencer-Marketing-Performance-Analytics-&-Pipeline-Revenue-Attribution-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Employee Advocacy & LinkedIn Brand Ambassador Program Architecture Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Influencer-&-Creator-Marketing/AI-Powered-B2B-SaaS-Employee-Advocacy-&-LinkedIn-Brand-Ambassador-Program-Architecture-Intelligence-Engine.md)
- [AI-Powered B2B SaaS LinkedIn Creator Sponsorship & Thought Leader Paid Amplification Campaign Architecture Revenue Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Influencer-&-Creator-Marketing/AI-Powered-B2B-SaaS-LinkedIn-Creator-Sponsorship-&-Thought-Leader-Paid-Amplification-Campaign-Architecture-Revenue-Intelligence-Engine.md)
- [Dark Funnel Attribution & Anonymous Buyer Intent Intelligence Engine](../Attribution-&-Revenue-Analytics/Dark-Funnel-Attribution-&-Anonymous-Buyer-Intent-Intelligence-Engine.md)

## Integration Tips

- **LinkedIn Sales Navigator:** Enable "Buyer Intent" alerts for all saved accounts on your ICP target list — when a prospect engages with a company page post, Sales Navigator fires an alert to the assigned AE. Build a Salesforce or HubSpot workflow: when Sales Navigator alert fires → create a CRM Task "Social Engagement Alert — [Account Name] — [Engagement Type]" → assign to account owner with a pre-written personalization template for outreach. Pull monthly Sales Navigator "Account Hub" reports → export engaged accounts → cross-reference with open opportunities and new lead creation dates in CRM to calculate Social-Influenced Opportunity Rate.
- **EveryoneSocial / Bambu / PostBeyond:** These platforms track every share event (when an advocate shares company-curated content) — connect share event data to CRM via Zapier or native integration. EveryoneSocial's Earned Media Value metric is useful for executive summaries but should always be translated into pipeline metrics for Finance. Export monthly activity reports by advocate → feed into AVS calculation in your BI tool. Use the platform's leaderboard feature for internal gamification — advocates who can see their rank by AVS (not just post count) adjust behavior toward pipeline-generating content formats.
- **Salesforce:** Create a custom Activity type "Social Engagement — Advocate" with fields: Advocate Name, Post Date, Post Content Type, Engagement Type (like / comment / share / save), Platform, and ICP Match Score (populated automatically by CRM enrichment). Build a Salesforce Campaign for the advocacy program with Campaign Members auto-added when a Contact has a "Social Engagement — Advocate" activity → use Campaign Influence to credit the advocacy program on associated opportunities. Build a Salesforce Report: Opportunities with Related Activities containing "Social Engagement — Advocate" in the 90 days before Opportunity Created Date → this becomes your monthly Social-Influenced Pipeline number.
- **HubSpot:** Create a custom Contact property "Employee Advocate First Touch" (dropdown: list all advocates by name) populated by self-reported attribution NLP classification. Build a HubSpot Contact Report: contacts where Employee Advocate First Touch is populated → segment by advocate name → this is your self-reported advocacy attribution by advocate. Use HubSpot's Revenue Attribution Reports to add "Employee Advocacy" as a custom channel — classify contacts with Employee Advocate First Touch as "Employee Advocacy" channel and include in multi-touch attribution model.
- **Gong / Chorus:** Configure keyword tracking for your company name and executive names → surface calls where prospects say "I saw your CRO post about X" or "I've been following [Executive] on LinkedIn" → these are gold-standard social attribution signals. Export Gong call snippets where social mentions occur → build a monthly "Social Attribution in Conversations" report → use these verbatims as proof points in the advocacy ROI report to the CFO. Gong call data also reveals which customer outcome stories resonate most in conversations — advocate content briefings should reflect the stories that prospects reference in discovery.
- **Tableau / Looker:** Build a two-tab Advocacy Analytics dashboard: Tab 1 = Program Overview (active advocate rate, monthly ICP impressions, pipeline influenced, top 5 advocates by AVS); Tab 2 = Advocate Deep Dive (drill-down by individual advocate — SSI trend, content type mix, pipeline influence over rolling 90 days, 90-day action recommendation). Color-code tracked attribution (CRM overlap, self-reported) vs. modeled attribution (brand search lift correlation) consistently in all visualizations — Finance stakeholders lose trust when tracked and modeled are mixed without labeling.
- **Zapier / Make (workflow automation):** Build a Zap: New self-reported attribution form entry → run NLP classification → if employee name or "LinkedIn" + role type detected → update CRM Contact field "Employee Advocacy First Touch" → create CRM Task for advocacy manager to review. Build a Zap: Monthly on the 1st → pull EveryoneSocial API for advocate posting data → calculate monthly active advocate rate → post Slack message to #advocacy-program channel with current active rate and top 3 advocates by post volume.

## Troubleshooting

**Problem:** The SSI-to-quota attainment correlation is weak (r <0.25) even though the company has invested in LinkedIn Sales Navigator seats and an advocacy platform — the data suggests social selling isn't working, but anecdotally AEs report that LinkedIn is critical to their prospecting.
**Solution:** A weak SSI correlation almost always reflects one of two problems: (1) SSI gaming — reps have learned that sending connection requests and liking content inflates their SSI score without building genuine relationships. Check which SSI sub-components are highest for low-quota AEs: "Establish Your Professional Brand" component inflated by post frequency alone (not ICP reach quality) is a common gaming pattern. Fix: shift rep incentive tracking from SSI score to Sales Navigator Alert-to-Meeting Rate and Social-Influenced Opportunity attribution — behaviors that require genuine relationship building, not algorithmic gaming. (2) The social selling motion isn't integrated into the CRM workflow. If AEs are doing social selling activity in LinkedIn but not logging it as CRM activities, the data pipeline to calculate the correlation is broken. Fix: implement the Sales Navigator → CRM activity auto-logging workflow (Deliverable 2, Layer 3) and run the SSI correlation again after 90 days of clean data. A properly instrumented cohort almost always shows r >0.40 within two quarters.

**Problem:** The CRM overlap matching exercise (Deliverable 2, Layer 1) returns very few matches — only 5-8% of LinkedIn-engaged accounts appear in the CRM — suggesting the advocacy program is reaching people outside the company's prospect database rather than warming known accounts.
**Solution:** Low CRM overlap has two possible interpretations: (a) The advocacy program is generating genuine new awareness among prospects not yet in your CRM — which is valuable but requires longer attribution windows. Fix: run the CRM overlap analysis again at 180 days (not 90) — social-influenced buyers who weren't yet in your CRM at the time of engagement may enter the CRM months later as inbound leads. Track these late-entering contacts: "CRM Entered Date" vs. "LinkedIn First Engagement Date" — if a meaningful percentage entered the CRM 60-180 days after first advocate engagement, the advocacy program is generating top-of-funnel demand not captured in the 90-day window. (b) The advocacy content is primarily reaching the advocate's peer network (fellow marketers, former colleagues, random connections) rather than ICPs. Fix: run a LinkedIn follower demographic audit for your top 5 advocates — if the follower base is <25% ICP-matched job titles, the organic advocate program needs to be supplemented with Thought Leader Ads (paid amplification of advocate posts targeted to your ICP company list). TLA amplification can shift the ICP impression concentration from 20% to 55-70% within 60 days.

**Problem:** The executive advocacy program is generating strong engagement and brand search lift metrics, but when Finance requests a revenue number for the program the CMO can't produce a defensible figure — the attribution model's "modeled" estimates are rejected by the CFO as too speculative.
**Solution:** Finance teams accept modeled attribution when the modeling methodology is transparent and conservative. Three approaches to build CFO acceptance: (1) Present the cohort comparison data (Deliverable 1, Section 1B) as the primary proof — if executive content-engaged accounts close at 18% higher win rates than non-engaged matched accounts (a trackable, CRM-based fact), present that differential as the attribution anchor. The CFO is much more likely to accept "our data shows that executive-engaged accounts close 18% more often, and here's the pipeline math if we apply that differential conservatively to our modeled reach" than a black-box estimate. (2) Commission a 60-day holdout test: pause one executive's content program → measure whether deal velocity, pipeline creation from that executive's accounts, or branded search in the segment changes. Present holdout results as causal evidence, not correlation. (3) Use the self-reported attribution data as your lowest-bound revenue number: "We can directly attribute $X in closed-won revenue to prospects who named our executives by name in their first-touch field — this is the floor. The full impact including dark social influence is higher, but we'll only claim what we can prove." Starting with a defensible floor and building up to modeled estimates is more credible than leading with a large modeled number.

## Version History
- v1.0: Initial creation (auto-generated)
