# AI-Powered B2B SaaS LinkedIn Performance Analytics & Dark Social Pipeline Revenue Attribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** linkedin-analytics, dark-social, pipeline-attribution, b2b-saas, social-media-analytics, revenue-attribution, organic-social, paid-social, thought-leadership

## Overview
This prompt builds a complete LinkedIn analytics and revenue attribution system for B2B SaaS companies — covering organic company page performance, employee advocacy analytics, LinkedIn ads attribution, dark social pipeline tracking, and a unified LinkedIn-to-revenue model that proves ROI to CMOs and CFOs who currently dismiss LinkedIn as unattributable.

## Quick Copy-Paste Version

You are a B2B SaaS marketing analytics expert specializing in LinkedIn performance measurement and dark social attribution. I need a complete LinkedIn analytics and pipeline attribution framework.

Company: [Your Company]
Product/Category: [e.g., "Sales intelligence platform for enterprise B2B SaaS"]
ICP: [Job titles and company size, e.g., "VP Sales and CRO at B2B SaaS companies, 200-2,000 employees"]
Current LinkedIn Presence: [Company page followers, avg post engagement rate, LinkedIn ads monthly budget, e.g., "8,200 followers, 2.1% avg engagement, $25K/month LinkedIn ads"]
Analytics Stack: [CRM + Marketing automation, e.g., "Salesforce + Marketo + Google Analytics 4"]
Primary Attribution Challenge: [Your biggest LinkedIn ROI challenge, e.g., "Can't connect LinkedIn engagement to pipeline because buyers research on LinkedIn but convert via direct/brand search weeks later"]

Build me:

1. LINKEDIN PERFORMANCE METRICS FRAMEWORK — The 12 metrics that actually matter for B2B SaaS (not vanity metrics), with benchmarks for each by company stage and ICP
2. DARK SOCIAL ATTRIBUTION ARCHITECTURE — A complete methodology to attribute pipeline that originated from LinkedIn but never left a UTM cookie trail — covering self-reported attribution, CRM tagging, and cohort analysis approaches
3. CONTENT PERFORMANCE ANALYTICS MODEL — How to analyze which content formats, topics, and authors (company vs. employee) drive qualified pipeline, not just impressions
4. LINKEDIN ADS ATTRIBUTION FRAMEWORK — Multi-touch attribution for LinkedIn Campaign Manager that accounts for the long B2B sales cycle and buyer committee overlap
5. COMPETITIVE LINKEDIN INTELLIGENCE — How to benchmark your LinkedIn performance against competitors using available data and third-party tools
6. MONTHLY LINKEDIN REVENUE REPORT TEMPLATE — A board-ready one-page LinkedIn ROI summary that connects social activity to pipeline contribution

Every metric must have a data source, a calculation method, and a CRM-connected tracking mechanism. No "engagement is a proxy for brand awareness" cop-outs — this report must defend LinkedIn investment to a skeptical CFO.

## Advanced Customizable Version

ROLE: You are a senior B2B SaaS marketing analytics architect with 14+ years of experience building revenue attribution models for high-growth SaaS companies. You have solved LinkedIn's dark social attribution problem for companies ranging from Series B startups ($10M ARR) to public SaaS enterprises ($500M+ ARR). Your expertise spans:
- LinkedIn native analytics (Company Page Insights, Campaign Manager, Sales Navigator Reporting)
- Dark social attribution methodology: self-reported attribution surveys, CRM source waterfall models, and probabilistic attribution
- Multi-touch attribution design for long-cycle B2B sales (3-18 month buying cycles, 5-12 person buying committees)
- LinkedIn content performance analytics: post-level, author-level, format-level, and topic-level analysis
- Integration of LinkedIn data with Salesforce, HubSpot, Marketo, GA4, and BI tools (Looker, Tableau, Power BI)
- LinkedIn competitive intelligence using native benchmarks, third-party tools (Vainu, Socialinsider, Sprout Social), and manual competitive monitoring

OBJECTIVE: Build a complete, AI-executable LinkedIn Analytics & Dark Social Revenue Attribution Intelligence System for a B2B SaaS company. Every component must be production-ready — designed so an AI agent can pull data, calculate metrics, generate insights, and produce a board-ready monthly report without requiring a data scientist.

COMPANY CONTEXT:
- Company Name: [Company Name]
- Product Description: [One sentence: what it does, for whom, and the primary outcome delivered]
- Product Category: [e.g., "Revenue Intelligence," "DevSecOps," "HR Tech"]
- ACV: [e.g., "$45,000 ACV"]
- Sales Cycle Length: [e.g., "60-120 days for mid-market, 6-18 months for enterprise"]
- Buying Committee Size: [e.g., "4-8 stakeholders per deal: economic buyer, champion, IT, legal, procurement"]
- Primary ICP: [Job titles and company profile — who your ideal buyer is]
- LinkedIn Company Page URL: [Your company LinkedIn URL]
- Current Follower Count: [e.g., 12,400 followers]
- Current Average Engagement Rate: [e.g., 2.8% — calculated as total engagements ÷ impressions per post]
- Top Performing Post Topics: [Your top 3 content themes by engagement, if known]
- Employee Advocacy Participation: [How many employees actively post about company — e.g., "12 active creators, including 3 executives"]
- LinkedIn Ads Monthly Spend: [e.g., "$38,000/month across Sponsored Content, Message Ads, and Thought Leader Ads"]
- LinkedIn Campaign Manager Conversion Tracking: [What conversions you currently track — demo requests, content downloads, webinar registrations]
- CRM Platform: [Salesforce / HubSpot / Pipedrive / other]
- Marketing Automation Platform: [Marketo / HubSpot Marketing / Pardot / other]
- Current Attribution Model: [First-touch / Last-touch / Multi-touch / No formal model]
- Primary Attribution Pain Points: [Describe your top 2-3 LinkedIn measurement challenges]
- BI Tool: [Looker / Tableau / Power BI / Google Data Studio / spreadsheets]
- Top 3 Competitors on LinkedIn: [Company names for competitive benchmarking]

---

DELIVERABLE 1 — LINKEDIN PERFORMANCE METRICS ARCHITECTURE

Section 1A: The 12 LinkedIn Metrics That Actually Matter for B2B SaaS

For each metric below, provide:
- Precise calculation formula
- Data source (LinkedIn native, CRM, MA platform, or third-party tool)
- B2B SaaS benchmark by company ARR stage (Seed/Series A, Series B/C, Series D+/Public)
- Why this metric matters for revenue (not for "brand awareness" — connect to pipeline or revenue outcome)
- Red/Yellow/Green thresholds for your company's stage

TIER 1 — PIPELINE-CONNECTED METRICS (Primary):
1. LinkedIn-Sourced MQL Rate
   - Definition: Percentage of new MQLs in a given period where LinkedIn is recorded as first touch or self-reported channel
   - Formula: (MQLs where Lead Source includes "LinkedIn") ÷ (Total MQLs) × 100
   - Benchmark: [Stage-specific benchmark]
   - CRM tracking: Required fields and workflow logic

2. LinkedIn Influenced Pipeline ($)
   - Definition: Total pipeline value where a LinkedIn engagement was recorded on the contact record within 90 days prior to opportunity creation
   - Formula: SUM(Opportunity Amount) where Contact Activity Log contains LinkedIn engagement event in [-90, 0] days from Opportunity Create Date
   - Benchmark: [Stage-specific benchmark]
   - CRM tracking: Required webhook or MA platform integration

3. LinkedIn-Sourced Closed-Won Revenue ($)
   - Definition: Revenue from closed-won deals where ANY contact on the opportunity has LinkedIn as their recorded first-touch or assisted touch
   - Formula: SUM(Closed-Won ARR) where Opportunity has ≥1 Contact with LinkedIn attribution recorded
   - Benchmark: [Stage-specific benchmark]
   - CRM tracking: Required opportunity field and contact attribution model

4. Content-to-Demo Conversion Rate (Organic)
   - Definition: For each piece of organic LinkedIn content published, the number of demo requests submitted within 14 days by followers who engaged with that post
   - Formula: (Demo requests submitted within 14 days of post publish date, from contacts following Company Page) ÷ (Post reach among ICP-qualified followers)
   - Limitation: Requires intent data enrichment or follow-up survey to attribute accurately
   - Benchmark: [Stage-specific benchmark]

TIER 2 — ENGAGEMENT QUALITY METRICS (Leading Indicators):
5. ICP Engagement Rate
   - Definition: Engagement rate calculated only against ICP-qualified follower segment (job titles, company size, industries that match your ICP)
   - Why this beats standard engagement rate: A post with 5% engagement from DevOps engineers is worthless if your ICP is CFOs; a post with 1.8% engagement from CFOs at target accounts is highly valuable
   - Calculation: (Engagements from ICP-qualified followers) ÷ (Impressions served to ICP-qualified followers) × 100
   - Data source: LinkedIn Campaign Manager (for ads) + third-party tools (Socialinsider, Shield App) for organic ICP segmentation

6. Follower Quality Score
   - Definition: Percentage of total followers who match your ICP criteria (job title AND company size AND industry)
   - Formula: (Followers with ICP-matching job title at ICP-matching company type) ÷ (Total followers) × 100
   - Calculation method: Export follower demographics from LinkedIn Page Analytics → cross-reference with ICP criteria
   - Benchmark: >35% ICP-qualified follower base = Strong; 20-35% = Average; <20% = Audience quality problem

7. Company Page Visitor-to-Follower Conversion Rate
   - Formula: (New followers gained in period) ÷ (Unique visitors to Company Page in period) × 100
   - Benchmark: 8-15% for B2B SaaS companies with relevant content programs
   - Why it matters: A high visitor count with low follower conversion signals a positioning/content relevance problem

8. Employee Advocacy Amplification Multiplier
   - Definition: Total impressions generated by employee posts mentioning/tagging company vs. impressions from Company Page alone
   - Formula: (Total impressions from tagged employee posts) ÷ (Total Company Page impressions)
   - Benchmark: High-performing advocacy programs generate 3x-8x the Company Page reach through employee networks

TIER 3 — EFFICIENCY METRICS (Channel ROI):
9. LinkedIn Ads Cost Per Pipeline Dollar (CP$P)
   - Formula: (Total LinkedIn Ads spend in period) ÷ (LinkedIn-attributed pipeline $ created in period)
   - Benchmark by ACV: <$0.05 per pipeline dollar = Excellent; $0.05-0.15 = Good; >$0.15 = Underperforming
   - Tracking requirement: Opportunity source field must capture LinkedIn Ads campaign ID or UTM parameter

10. Thought Leader Ads (TLA) Engagement-to-Opportunity Rate
    - Definition: For LinkedIn Thought Leader Ads, the percentage of ad engagements that result in a tracked opportunity within 90 days
    - Formula: (Opportunities created where contact clicked a TLA within 90 days) ÷ (Total TLA clicks in period) × 100
    - Tracking: Requires UTM parameters on TLA landing pages + CRM opportunity source waterfall

11. Content-to-Conversation Rate (Dark Social Proxy)
    - Definition: Percentage of inbound demo requests in a given period where the prospect mentions LinkedIn content in the "How did you hear about us?" field OR in the discovery call
    - Why it's a dark social proxy: Most LinkedIn-influenced buyers don't click a tracked link — they research on LinkedIn, then search for your brand directly
    - Calculation: (Demo requests where "LinkedIn" appears in self-reported source field) ÷ (Total demo requests) × 100
    - How to improve tracking: See Deliverable 2

12. LinkedIn CAC vs. Blended Marketing CAC
    - Formula: (Total LinkedIn investment: organic content production cost + ads spend + tools + headcount allocation) ÷ (New customers acquired where LinkedIn is recorded in attribution model)
    - Benchmark: LinkedIn CAC should be within 1.5x of blended marketing CAC for it to be justified; ideally at par or lower for high-ACV enterprise products

---

Section 1B: Metrics Reporting Cadence

| Metric | Reporting Cadence | Owner | Audience |
|---|---|---|---|
| LinkedIn-Sourced MQL Rate | Weekly | Marketing Ops | Demand Gen Lead |
| LinkedIn Influenced Pipeline | Weekly | Marketing Ops | CMO, Demand Gen Lead |
| ICP Engagement Rate | Weekly | Social Media Manager | Marketing Team |
| Follower Quality Score | Monthly | Social Media Manager | CMO |
| Employee Advocacy Multiplier | Monthly | Employee Advocacy Lead | CMO, HR |
| LinkedIn Ads CP$P | Weekly | Paid Media Manager | CMO, CFO |
| LinkedIn CAC | Monthly | Marketing Ops | CMO, CFO |
| Content-to-Conversation Rate | Monthly | Marketing Ops | CMO, Board |

---

DELIVERABLE 2 — DARK SOCIAL ATTRIBUTION ARCHITECTURE

Section 2A: The Dark Social Problem Statement

LinkedIn dark social is the attribution gap between a buyer's LinkedIn research behavior and their eventual conversion action. The typical buyer journey:

1. Buyer sees your executive's LinkedIn post → reads but does NOT click (no cookie set)
2. Buyer sees competitor comparison post from employee → screenshots it (no click)
3. Buyer sees customer testimonial video → watches in-feed (no click, no cookie)
4. Buyer discusses you with colleague who saw your LinkedIn newsletter (no digital trail)
5. Buyer's colleague searches "[Your Company] demo" on Google → converts via brand search
6. Your attribution model credits: **Google Organic** or **Direct**
7. LinkedIn investment generates ZERO credit despite driving the entire consideration process

This pattern accounts for an estimated 40-70% of LinkedIn-influenced pipeline in B2B SaaS — and it is structurally invisible to standard UTM-based attribution.

Section 2B: Four-Layer Dark Social Attribution Methodology

LAYER 1 — SELF-REPORTED ATTRIBUTION (Highest signal, lowest volume)

Implementation: Add a single open-text question to every demo request form:
- Field label: "How did you first hear about [Company Name]? (Be specific — LinkedIn post, Google search, colleague recommendation, etc.)"
- Field type: Short text (NOT a dropdown — dropdowns suppress LinkedIn mentions by 60-80% because buyers choose the closest option, not the accurate one)
- CRM mapping: Sync this field as "Self-Reported First Touch" on the Lead/Contact record

AI Agent Processing Workflow:
1. Each new Lead created with "Self-Reported First Touch" populated → AI agent classifies the response into one of 8 channels: LinkedIn Organic, LinkedIn Ads, LinkedIn Newsletter, Employee Post (Organic), Employee Post (Amplified), Podcast, Content/Blog, Other Social
2. Classification runs via NLP pattern matching (e.g., any mention of "post," "video," "LinkedIn," "CEO/founder name" → LinkedIn channel)
3. CRM property "LinkedIn Dark Social Source" populated with classified channel
4. Monthly aggregate: (Self-reported LinkedIn mentions) ÷ (Total self-reported form submissions) = LinkedIn Dark Social Rate

Benchmark: B2B SaaS companies with active LinkedIn programs see 15-35% of self-reported attributions mention LinkedIn — vs. <5% in UTM-tracked attribution for the same company.

LAYER 2 — COHORT CORRELATION ANALYSIS (Medium signal, medium volume)

Methodology: Compare the pipeline creation rate for LinkedIn Company Page followers vs. non-followers within your CRM database.

Step 1 — Identify followers in CRM:
- Export LinkedIn Company Page follower list (via LinkedIn Page Admin > Analytics > Followers > Export)
- Note: LinkedIn exports only follower job titles and seniority aggregates — NOT individual identities. To link followers to CRM contacts, you need a lead enrichment layer.
- Tool options: Clay.com (enrich email list with LinkedIn profile → check if they follow your company page), Cognism, ZoomInfo

Step 2 — Tag CRM contacts as "LinkedIn Follower" (boolean field + date)

Step 3 — Run cohort comparison:
- Cohort A: CRM contacts tagged as LinkedIn Followers
- Cohort B: CRM contacts NOT tagged as LinkedIn Followers (matched by ICP criteria, company stage, and inbound vs. outbound source to control for selection bias)
- Measure: Win rate, deal size, sales cycle length, close rate for Cohort A vs. Cohort B
- Expected finding: Cohort A (LinkedIn followers) typically shows 20-40% higher win rates and 15-25% shorter sales cycles

LAYER 3 — INTENT DATA CROSS-REFERENCE (Lower signal, high coverage)

Use third-party intent data to cross-reference LinkedIn-engaged accounts against pipeline:

- Tool: Bombora, G2 Buyer Intent, or 6sense
- Methodology: For accounts showing intent signals for your product category, cross-reference against LinkedIn Campaign Manager audience (accounts that have seen your LinkedIn ads) and Company Page visitor log (accounts that have visited your LinkedIn Company Page, visible in Page Analytics by company)
- Signal: Account that shows 3rd-party intent AND has LinkedIn Company Page visitors from that account → "LinkedIn-Activated Intent Account" tag in CRM
- Pipeline attribution: Track close rates for LinkedIn-Activated Intent Accounts vs. pure intent accounts with no LinkedIn touchpoint

LAYER 4 — SALES DISCOVERY INTELLIGENCE (Qualitative signal, highest conversion context)

Add LinkedIn attribution questions to the SDR/AE discovery workflow:

Question template for SDR qualifying call (scripted, not ad-hoc):
"Before I dive into qualifying questions — I'm curious, how did you first come across [Company Name]? What made you decide to reach out today specifically?"

If LinkedIn mentioned → SDR updates CRM Contact record: "LinkedIn Discovery: Yes" + note on specific content mentioned

AI Agent Aggregation:
- Monthly: Pull all Closed-Won opportunities where "LinkedIn Discovery: Yes" was logged by SDR/AE
- Report: LinkedIn Discovery Revenue ($) = Total ARR of closed-won deals where LinkedIn was mentioned in discovery

Section 2C: Dark Social Attribution Score

Combine all four layers into a contact-level "LinkedIn Dark Social Score":

| Signal | Score | Data Source |
|---|---|---|
| Self-reported LinkedIn in form | +50 | CRM lead form field |
| LinkedIn follower in CRM (enriched) | +25 | Clay/enrichment tool |
| Company Page visitor from account (30 days before demo) | +20 | LinkedIn Page Analytics export |
| LinkedIn ad click on contact record | +30 | LinkedIn Campaign Manager → CRM sync |
| Thought Leader Ad engagement | +25 | TLA data → CRM |
| SDR/AE discovery call notes LinkedIn | +40 | CRM activity note |
| Intent platform shows account engaging with LinkedIn content | +20 | Bombora/6sense |

Threshold interpretation:
- Score 70+: LinkedIn is primary influence driver → attribute 70% of deal to LinkedIn in multi-touch model
- Score 40-69: LinkedIn is significant influence → attribute 40% of deal to LinkedIn
- Score 20-39: LinkedIn is minor influence → attribute 15% of deal to LinkedIn
- Score <20: No meaningful LinkedIn influence → 0% LinkedIn attribution

---

DELIVERABLE 3 — CONTENT PERFORMANCE ANALYTICS MODEL

Section 3A: Content Performance Taxonomy

Build a content classification system that enables post-level performance analysis. Every LinkedIn post should be tagged at publish time with:

| Taxonomy Dimension | Values |
|---|---|
| Content Format | Text-only, Image, Carousel/Document, Video, LinkedIn Article, LinkedIn Newsletter, Poll, Reshare with commentary |
| Content Theme | Product/feature, Customer story, Thought leadership, Industry data/research, Company culture, Educational/how-to, Event promotion, Competitive commentary |
| Author Type | Company Page, Founder/CEO, C-Suite executive, Subject matter expert, Sales employee, CS employee, Marketing employee |
| Buyer Stage Target | Awareness (top-of-funnel), Consideration (mid-funnel), Decision (bottom-of-funnel), Retention (existing customers) |
| ICP Relevance | Primary ICP, Secondary ICP, Adjacent audience, Broad/general |

Section 3B: Content Performance Scoring Matrix

For each post, calculate a Content Pipeline Score (CPS):

CPS = (ICP Engagement Rate × 0.4) + (Share/Save Rate × 0.3) + (Comment Quality Score × 0.2) + (Profile Visit Rate × 0.1)

Where:
- ICP Engagement Rate = Engagements from ICP-matching profiles ÷ Impressions served to ICP-matching profiles
- Share/Save Rate = (Shares + Saves) ÷ Total impressions (shares/saves indicate intent to use or share internally — the highest engagement signal on LinkedIn)
- Comment Quality Score = AI-classified comments on a 1-3 scale: 1 = emoji/generic ("Great post!"), 2 = topical agreement ("This matches what I'm seeing"), 3 = substantive engagement ("We've had this exact challenge — specifically X") — average of all comments
- Profile Visit Rate = Profile visits generated by post ÷ Total impressions (available in LinkedIn post analytics for personal accounts, not Company Page)

Section 3C: Content Attribution Report Template

Run monthly. For each content theme and format:

| Content Category | Posts Published | Avg ICP Reach | Avg CPS | Self-Reported LinkedIn Mentions (30-day lag) | Pipeline Influenced ($) |
|---|---|---|---|---|---|
| Customer stories (carousel) | 4 | 3,200 | 7.8 | 6 | $480,000 |
| Executive thought leadership (text) | 12 | 1,800 | 6.2 | 11 | $620,000 |
| Product education (video) | 8 | 2,100 | 4.1 | 3 | $180,000 |
| Industry data (original research) | 2 | 8,400 | 9.1 | 14 | $840,000 |

Insight generation (AI agent): After populating the table monthly, AI agent generates a ranked list of "highest pipeline-per-post content categories" and flags any content type where investment (time + production cost) exceeds pipeline contribution proportionally.

---

DELIVERABLE 4 — LINKEDIN ADS ATTRIBUTION FRAMEWORK

Section 4A: Campaign Tagging Architecture

Every LinkedIn Campaign Manager campaign must follow this UTM taxonomy for CRM pipeline attribution:

utm_source = linkedin
utm_medium = [cpc | sponsored-content | message-ad | tla | inmail | spotlight]
utm_campaign = [FY-Quarter]_[Audience-Segment]_[Objective]_[CTA]
Example: FY26Q3_EnterpriseSecOps_DemoRequest_FreeTrial

utm_content = [Format]_[Post-ID]_[Creative-Variant]
Example: Carousel_Post47281_VariantA

utm_term = [Job-Title-Targeting-Group]
Example: CISO-VPEng-DevSecOps

Section 4B: LinkedIn Ads Multi-Touch Attribution Model

Standard last-touch attribution systematically undercredits LinkedIn because B2B buyers:
1. See LinkedIn ad (awareness) → no click
2. See LinkedIn ad again (consideration) → click to blog post
3. Return via branded Google search 3 weeks later → demo request
4. Last-touch model credits: Google Organic → LinkedIn investment gets zero credit

Recommended attribution model for LinkedIn Ads:

POSITION-BASED MODEL (W-Shaped for multi-stakeholder B2B):
- 40% credit to first touch (awareness — where the journey began)
- 40% credit to opportunity creation touch (the action that created the sales cycle)
- 20% distributed across all middle touches

LinkedIn Ads Reporting Setup:
1. LinkedIn Campaign Manager → Export conversion data (14-day, 30-day, 90-day view-through + click-through windows)
2. Import LinkedIn conversion events via API into CRM opportunity source field
3. Apply W-shaped weight to LinkedIn touchpoints in multi-touch attribution model

Section 4C: Account-Level LinkedIn Ads Attribution

For B2B with multiple buyers, apply Account-Level Attribution (not contact-level):

Account LinkedIn Ad Score = (Number of unique contacts at account who clicked or viewed LinkedIn ad in past 90 days) × (Seniority multiplier: Economic buyer = 3x, Champion = 2x, Influencer = 1x)

Score 12+: Account has reached "LinkedIn Saturated" — LinkedIn brand recall is high, likely to respond positively to direct outreach or content personalization
Score 6-11: Account is "LinkedIn Aware" — continue nurturing with relevant content, add to Thought Leader Ads audience
Score <6: Account is "LinkedIn Cold" — use Matched Audiences to increase exposure before SDR outreach

---

DELIVERABLE 5 — COMPETITIVE LINKEDIN INTELLIGENCE

Section 5A: Competitor Benchmarking Metrics

Data sources for competitor LinkedIn analytics (you do NOT have access to their internal data — use public + third-party sources):

PUBLIC SOURCES:
- LinkedIn Company Page (visible to anyone): Follower count, follower growth rate (tracked manually or via tool), post frequency, post format mix, engagement rate (visible per post: reactions + comments ÷ reported impressions on public posts — note: impressions only visible to page admins, so estimate using engagement benchmarks)
- LinkedIn Company Page "Life" tab: Culture content, employee count, hiring velocity (signals growth stage)
- Employee post activity: Who at competitor is creating content, on what topics, with what engagement

THIRD-PARTY TOOLS:
- Socialinsider ($): Exports competitor LinkedIn page analytics — follower growth, post frequency, average engagement rate, top content by engagement
- Shield App (personal LinkedIn analytics): Track competitor executives' post performance
- Vainu / Bombora: Track competitor company LinkedIn activity signals correlated with growth

Section 5B: Competitive Intelligence Dashboard (Monthly)

| Competitor | Follower Count | 30-Day Follower Growth | Avg Post Frequency (posts/week) | Avg Engagement Rate | Top Content Theme | Active Employee Creators |
|---|---|---|---|---|---|---|
| [Your Company] | [XX,XXX] | [+XXX] | [X.X] | [X.X%] | [Theme] | [XX] |
| Competitor A | [XX,XXX] | [+XXX] | [X.X] | [X.X%] | [Theme] | [XX] |
| Competitor B | [XX,XXX] | [+XXX] | [X.X] | [X.X%] | [Theme] | [XX] |
| Competitor C | [XX,XXX] | [+XXX] | [X.X] | [X.X%] | [Theme] | [XX] |

AI Agent Competitive Alert System:
Monitor competitors' LinkedIn posts weekly. Flag posts that:
- Announce funding, partnerships, product launches (competitive intelligence trigger)
- Generate unusually high engagement (>2x their average — signals what content resonates with shared audience)
- Receive comments from contacts in your CRM (signals your prospects are engaging with competitor content)
- Use keywords from your ICP's pain point vocabulary (competitive messaging intelligence)

---

DELIVERABLE 6 — MONTHLY LINKEDIN REVENUE REPORT TEMPLATE

Section 6A: Board-Ready One-Page LinkedIn ROI Summary

LINKEDIN REVENUE CONTRIBUTION REPORT
[Company Name] | [Month/Year]

PIPELINE IMPACT
- LinkedIn-Sourced Pipeline This Month: $[XXX,XXX] ([X.X%] of total pipeline)
- LinkedIn-Influenced Pipeline This Month: $[XXX,XXX] ([X.X%] of total pipeline)
- LinkedIn-Sourced Closed-Won ARR (This Quarter): $[XXX,XXX]
- Dark Social Attribution Estimate (self-reported + cohort model): $[XXX,XXX] additional influenced pipeline

EFFICIENCY METRICS
- Total LinkedIn Investment This Month: $[XX,XXX] (ads: $XX,XXX + content: $X,XXX + tools: $X,XXX)
- LinkedIn CAC (trailing 3 months): $[XX,XXX]
- Blended Marketing CAC (trailing 3 months): $[XX,XXX]
- LinkedIn CAC Index: [X.Xx] (LinkedIn CAC ÷ Blended CAC; <1.0 = LinkedIn more efficient than average)
- Pipeline $ Generated Per $1 Spent: $[X.XX]

ENGAGEMENT HEALTH
- LinkedIn Follower Growth: [+X,XXX] ([X.X%] MoM)
- ICP Follower % of Total Audience: [XX.X%]
- Average ICP Engagement Rate: [X.X%] (vs. [X.X%] industry benchmark)
- Employee Advocacy Amplification: [X.Xx] Company Page reach (X employees generated [X,XXX,XXX] impressions)
- Content-to-Conversation Rate (Dark Social): [X.X%] of demos self-reported LinkedIn as first touch

CONTENT PERFORMANCE
- Highest CPS Post: "[Post headline]" — [X,XXX] ICP impressions, [X.X%] ICP engagement, [X] self-reported attributions
- Top Content Theme by Pipeline Influence: [Theme] — $[XXX,XXX] pipeline in trailing 30 days

COMPETITIVE POSITION
- LinkedIn Share of Voice vs. Top 3 Competitors: [XX%] (your followers ÷ total followers across you + competitors)
- Engagement Rate vs. Competitor Avg: [+X.X%] above / [X.X%] below competitive benchmark

KEY INSIGHT THIS MONTH: [One sentence AI-generated insight — e.g., "Customer success story carousels generated 3.2x the pipeline-per-impression of product education posts this month — recommend shifting 40% of October content budget to customer story production."]

RECOMMENDED ACTION FOR NEXT MONTH: [One sentence — specific, actionable recommendation based on data]

---

AI AGENT REPORTING WORKFLOW:

WEEKLY (Every Monday AM):
1. Pull LinkedIn Campaign Manager data → calculate paid media efficiency metrics → update CRM dashboard
2. Pull Company Page Analytics → calculate ICP engagement rate, follower growth, top posts → update social media dashboard
3. Pull CRM new leads/opportunities from past 7 days → run dark social attribution scoring → flag high-score contacts for SDR review
4. Scan competitor Company Pages → flag unusual content or engagement spikes → add to competitive intelligence log

MONTHLY (First Monday):
1. Aggregate all weekly data → populate monthly LinkedIn Revenue Report template
2. Run cohort analysis: LinkedIn follower vs. non-follower pipeline comparison
3. Calculate Content Pipeline Score for all posts published in prior month → identify top/bottom performing content themes
4. Run competitive benchmarking dashboard update
5. Generate insight + recommendation using data patterns
6. Distribute report to CMO, CRO, CFO via automated email (PDF export from BI tool)

CONSTRAINTS:
- All attribution claims must be defensible with a data source — no estimates without stated methodology
- Dark social attribution must be clearly labeled as "modeled" vs. "tracked" to maintain credibility with finance
- LinkedIn influencer metrics (impressions, followers) should always be filtered to ICP-relevant audience segments — never report total impressions as the primary metric to a B2B audience
- LinkedIn ads attribution must use a view-through window appropriate for your sales cycle (minimum 30 days; for enterprise with 6+ month cycles, use 90-day view-through)
- All AI-generated competitive intelligence must note data source and confidence level (high/medium/low)

OUTPUT FORMAT:
Deliver all 6 sections as complete, production-ready frameworks. All tables should be ready to populate with real data. Write the board report template with placeholder values that make the format immediately usable. Every formula must be written so a marketing ops analyst — not a data scientist — can implement it.

## Example Input/Output

**Input Example:**

- Company: Veridian Security
- Product: Cloud-native application security platform for enterprise DevSecOps teams — identifies and remediates vulnerabilities in CI/CD pipelines in real-time
- ICP: VP Engineering, CISO, Director of DevSecOps at enterprise companies (1,000+ employees, tech-forward industries: fintech, healthtech, SaaS)
- ACV: $120,000
- Sales Cycle: 4-9 months
- LinkedIn Stats: 14,200 followers, 1.9% avg engagement, $42,000/month LinkedIn ads
- Analytics Stack: Salesforce + Marketo + GA4 + Tableau
- Attribution Challenge: "We're spending $42K/month on LinkedIn ads and can only attribute $180K/quarter in pipeline directly. Our CMO believes LinkedIn drives much more but can't prove it to the board."

**Output Example (Excerpts):**

**Dark Social Attribution Baseline (Month 1 Assessment):**

After implementing the self-reported attribution field on the demo request form and running the first 30-day data collection:
- Total demo requests in period: 112
- Self-reported LinkedIn mentions: 24 (21.4%)
- Breakdown:
  - LinkedIn organic post (employee/executive): 11 mentions (46%)
  - LinkedIn Company Page post: 6 mentions (25%)
  - LinkedIn ad: 4 mentions (17%)
  - LinkedIn newsletter: 3 mentions (12%)

Implication: Of the $180K/quarter in directly tracked LinkedIn pipeline, self-reported attribution suggests an additional ~$840K in influenced pipeline (21.4% of total quarterly pipeline of $3.9M) has LinkedIn as a first-touch influence that never appeared in UTM tracking.

**Top Performing Content Analysis (Q3 2026):**

| Content Type | Posts | Avg ICP Engagement | Self-Reported Attributions (30-day lag) | Pipeline Influenced |
|---|---|---|---|---|
| CISO vulnerability data (original research) | 3 | 4.1% | 9 | $1,080,000 |
| Customer story carousels | 5 | 3.2% | 7 | $840,000 |
| VP Eng thought leadership (text posts) | 18 | 2.8% | 11 | $660,000 |
| Product feature announcements | 8 | 1.1% | 2 | $120,000 |

Insight: Original research and customer stories generate 6-9x the pipeline-per-post of product feature content, despite receiving 2-3x fewer impressions. Recommendation: Reduce product announcement posts to 2/month; redirect production budget to quarterly original research publication.

**Board-Ready Monthly Report Excerpt (November 2026):**

LINKEDIN REVENUE CONTRIBUTION REPORT — Veridian Security | November 2026

PIPELINE IMPACT
- LinkedIn-Sourced Pipeline (UTM-tracked): $290,000 (7.4% of $3.9M total)
- LinkedIn-Influenced Pipeline (dark social model): $840,000 additional (modeled — labeled as estimated)
- Total LinkedIn Pipeline Contribution (tracked + modeled): $1,130,000 (29.0% of total pipeline)
- LinkedIn-Sourced Closed-Won ARR (Q3): $360,000

EFFICIENCY
- Total Investment: $52,000 ($42K ads + $8K content production + $2K tools)
- LinkedIn CAC (trailing 3 months): $43,333
- Blended Marketing CAC: $38,600
- LinkedIn CAC Index: 1.12 — LinkedIn is 12% less efficient than blended average for directly tracked pipeline; when dark social model is applied, LinkedIn CAC drops to $15,600 — 40% below blended average

KEY INSIGHT: "Without dark social attribution, LinkedIn appears 12% less efficient than average. With the self-reported attribution model running for 90 days, LinkedIn becomes our most efficient pipeline channel when CISO-targeted content is running. The $360K closed-won quarter represents a 2.0x return on LinkedIn ad investment based on tracked pipeline alone — the board should increase LinkedIn ads budget for Q4 with focus on CISO audience targeting."

## Success Metrics

- **Dark Social Attribution Coverage:** Within 90 days of implementing self-reported attribution field, target 60%+ of demo requests including a populated first-touch source — validates that the attribution infrastructure is working
- **Self-Reported LinkedIn Rate:** 15-30% of self-reported first touches crediting LinkedIn channels is healthy for an active LinkedIn program; below 10% suggests your LinkedIn content is not reaching the right ICP
- **LinkedIn CAC (with dark social):** Target within 1.0-1.3x of blended marketing CAC; significantly above means LinkedIn is underperforming as a channel; significantly below means you're under-investing
- **ICP Engagement Rate vs. Industry Benchmark:** Target 2.5-4.0% ICP engagement rate for B2B SaaS with ACV >$20K; below 1.5% indicates content-audience misalignment or poor ICP follower quality
- **Pipeline Per LinkedIn Dollar:** Target $4-12 of pipeline per $1 invested (including both tracked and dark social modeled pipeline); below $3 warrants serious channel evaluation
- **Competitive Share of Voice:** Target maintaining or growing LinkedIn share of voice vs. top 3 competitors; declining SOV indicates competitor content programs are outpacing yours
- **Employee Advocacy Multiplier:** Target 2x minimum; 4x+ indicates a high-functioning employee advocacy program with strong organic amplification

## Related Prompts

- [Organic Social Media Performance Analytics & Pipeline Revenue Attribution](./AI-Powered-B2B-Organic-Social-Media-Performance-Analytics-&-Pipeline-Revenue-Attribution-Intelligence-Engine.md)
- [Employee Advocacy Program Analytics & Social Selling Revenue Attribution](./AI-Powered-B2B-SaaS-Employee-Advocacy-Program-Analytics-&-Social-Selling-Revenue-Attribution-Intelligence-Engine.md)
- [B2B Multi-Touch Attribution & Revenue Marketing Intelligence Engine](../Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md)
- [Dark Funnel Attribution & Anonymous Buyer Intent Intelligence Engine](../Attribution-&-Revenue-Analytics/Dark-Funnel-Attribution-&-Anonymous-Buyer-Intent-Intelligence-Engine.md)

## Integration Tips

- **Salesforce:** Create a custom Contact field "LinkedIn Dark Social Score" (number) and "Self-Reported First Touch" (text). Build a Salesforce Flow that auto-calculates the Dark Social Score when a new signal fires. Create a LinkedIn Pipeline Dashboard using Salesforce Reports filtered by Lead Source = LinkedIn + Self-Reported First Touch contains "linkedin." Set up a Salesforce Campaign for each major LinkedIn initiative (campaign launch, newsletter issue, event) to track multi-touch influenced pipeline.
- **HubSpot:** Use HubSpot's "Original Source Drill-Down" fields + a custom "Self-Reported First Touch" property. Build a LinkedIn Attribution Report in HubSpot Analytics using Contact Source and Deal Influence. Use HubSpot's LinkedIn Ads integration to sync ad engagement data directly to contact timelines — this provides mid-touch LinkedIn ad data without requiring manual CRM updates.
- **Marketo:** Build a Marketo Smart List of contacts with LinkedIn as any tracked touchpoint. Use Marketo's LinkedIn Lead Gen Form integration to auto-sync LinkedIn Lead Gen Form submissions directly to Marketo (no UTM required — LinkedIn sends contact data via API). Create Marketo Programs for each LinkedIn campaign type to enable multi-touch attribution reporting.
- **Google Analytics 4:** Set up GA4 Audiences for visitors who arrive via LinkedIn (utm_source=linkedin). Build a LinkedIn Conversion Funnel in GA4 using Event-based goals. Enable GA4 → Salesforce/HubSpot data import via BigQuery export + CRM integration to stitch LinkedIn session data to known contact records when they later convert on-site.
- **Tableau / Looker:** Build a unified LinkedIn Attribution Dashboard with two views: (1) Tracked Attribution (UTM-based, 100% confidence) and (2) Modeled Attribution (dark social estimate, labeled as modeled). Color-code modeled vs. tracked data in all visualizations to maintain CFO/board trust. Connect Tableau to LinkedIn Marketing Solutions API for direct data pulls — eliminates manual CSV export workflows.
- **Clay.com:** Build a Clay table that enriches your CRM contact list with LinkedIn profile data → checks if each contact follows your Company Page → calculates ICP fit score → syncs enriched data back to CRM. This enables the cohort analysis in Deliverable 2B and gives you LinkedIn follower data at the contact level rather than just aggregate demographics.
- **Bombora / 6sense:** Set up a data share between your intent platform and CRM to create the "LinkedIn-Activated Intent Account" tag described in Deliverable 2B, Layer 3. In 6sense, use the Account Engagement Score alongside your LinkedIn Dark Social Score to create a composite "LinkedIn + Intent" segment for high-priority SDR follow-up.

## Troubleshooting

**Problem:** Self-reported attribution field is being left blank by 40%+ of demo requesters — the dark social attribution layer has insufficient data volume.
**Solution:** The field needs a nudge to be completed. (1) Make it required (but with an "I don't remember" escape option) to force engagement. (2) Move the field to the top of the form, not the bottom — conversion psychology shows fields at the top are filled more carefully. (3) Change the label from a neutral question to an interest-piquing one: "What made you decide to reach out today?" performs 20-30% better than "How did you hear about us?" — it invites a narrative rather than prompting a channel lookup. (4) Add a placeholder text example: "e.g., 'Saw your CISO's post about zero-trust last week' or 'A colleague forwarded me your LinkedIn carousel'" — this modeling dramatically increases LinkedIn-specific mentions.

**Problem:** CFO/Finance is dismissing the dark social attribution model as "made-up numbers" and insisting on UTM-trackable proof before approving LinkedIn budget increases.
**Solution:** Reframe the conversation with two concrete data points Finance cannot dispute: (1) Run a 90-day holdout test — pause LinkedIn ads for a defined geographic or account segment (e.g., mid-market EMEA) for 60 days while maintaining them elsewhere. Measure whether demo request rate, brand search volume, or inbound inquiry rate declines in the holdout segment vs. the control. A measurable decline = proof of LinkedIn's contribution even without UTM tracking. (2) Present the "Close Rate Differential" analysis — pull all closed-won deals from the past 12 months. Filter to contacts where LinkedIn Follower = True. Compare average close rate for LinkedIn followers vs. non-followers. In most B2B SaaS companies with active LinkedIn programs, LinkedIn followers close at 1.3-2.0x the rate of non-followers. Close rate is a Finance-friendly metric that doesn't rely on attribution modeling.

**Problem:** The LinkedIn content analytics show high ICP engagement but the pipeline attribution data doesn't reflect corresponding pipeline growth — the engagement isn't converting.
**Solution:** This is typically a "last mile" problem — LinkedIn is creating awareness and consideration, but the conversion pathway is broken. Diagnose with three checks: (1) Check the demo request form completion rate for visitors arriving via LinkedIn UTM links — if <30%, the landing page or form is creating friction that kills conversion after LinkedIn successfully delivers the interested prospect. Fix the landing page first. (2) Check whether your highest-engagement LinkedIn content has a clear next step — posts with >3% ICP engagement but no CTA (or a weak CTA like "Learn more") are creating awareness with no conversion path. Add a contextual offer at the bottom of top-performing posts: "We just published a 3-page guide on this — DM me and I'll send it directly." (3) Check the timing lag — LinkedIn is a slow-burn channel. Run the pipeline attribution query with a 90-day window instead of 30 days. Many B2B SaaS companies see LinkedIn's pipeline contribution only appear when the attribution window extends to 60-120 days post-engagement.

## Version History
- v1.0: Initial creation (auto-generated)
