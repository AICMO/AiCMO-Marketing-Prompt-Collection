# AI-Powered Reddit Ads B2B Community Demand Generation & Pipeline Intelligence Engine - Capture In-Market Buyers in the Subreddits Where They Actually Research Decisions

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** Reddit Ads, B2B advertising, community targeting, demand generation, pipeline marketing, developer marketing, technical audiences, paid social, subreddit targeting, intent-based advertising

## Overview
Designs a complete Reddit Ads program for B2B companies — covering subreddit targeting strategy, campaign architecture, community-native creative, Reddit Pixel and Conversions API setup, and pipeline attribution — engineered to intercept high-intent buyers while they research solutions in professional and technical communities. Use this when you need to reach developers, IT professionals, finance leaders, or niche technical buyers at scale without paying LinkedIn CPCs, when your ICP actively participates in industry subreddits, or when you want to capture demand at the moment of research rather than the moment of intent signal.

## Quick Copy-Paste Version

You are a senior Reddit Ads strategist who has managed $20M+ in B2B Reddit spend across developer tools, SaaS, cybersecurity, fintech, and professional services. Build a complete Reddit Ads pipeline program for the company below.

COMPANY CONTEXT:
- Company: [Your Company] — [e.g., "AI-powered observability platform for DevOps and SRE teams at mid-market and enterprise tech companies"]
- ICP: [e.g., "DevOps Engineers, SREs, Platform Engineers, VP Engineering at tech companies, 100–2,000 employees, Series B through public"]
- Deal size: [e.g., "$24K ACV, 45-75 day sales cycle, 2-4 person buying committee"]
- Monthly Reddit budget: [e.g., "$12,000/month"]
- Goal: [e.g., "Generate 40 qualified demo requests per month at under $300 CPL, contribute $800K sourced pipeline per quarter"]
- Competitors: [e.g., "Datadog, New Relic, Grafana Cloud"]
- CRM/MAP: [e.g., "Salesforce + Marketo"]
- Website traffic: [e.g., "8,000 unique visitors/month — high-intent pages: /pricing, /vs-datadog, /demo"]
- Current Reddit state: [e.g., "No Reddit Ads running. Active organic presence in r/devops and r/sre with product mentions"]
- Key subreddits your ICP uses: [e.g., "r/devops, r/sre, r/kubernetes, r/aws, r/selfhosted, r/cscareerquestions"]

DELIVERABLES:

1. SUBREDDIT & AUDIENCE TARGETING STRATEGY
   Map your ICP to specific Reddit communities:
   - Tier 1 subreddits (highest intent — direct product category, 3-5 subreddits with subscriber counts)
   - Tier 2 subreddits (adjacent communities — complementary tools, job roles, 5-8 subreddits)
   - Tier 3 subreddits (broad professional context — career/industry subs, 3-5 subreddits)
   - Keyword targeting clusters: specific terms ICPs search within Reddit's in-feed search
   - Interest targeting fallback for audience scale
   - Lookalike audience construction from customer email list
   - Exclusions: competitor brand terms, irrelevant job-level communities

2. FULL-FUNNEL CAMPAIGN ARCHITECTURE
   Design 4-5 campaigns across awareness, consideration, and conversion. For each:
   - Campaign objective (Brand Awareness, Traffic, Conversions, Video Views, App Install)
   - Budget allocation ($) and % of total
   - Primary targeting method (subreddit, keyword, interest, retargeting)
   - Ad format recommendation (Promoted Post, Conversation Ad, Free-Form Ad)
   - Bid strategy and starting daily budget

3. COMMUNITY-NATIVE CREATIVE STRATEGY
   Reddit users reject corporate advertising. Provide:
   - Creative principle for B2B Reddit (the "Redditor test" — would this get upvoted organically?)
   - Promoted Post copy formula: headline structure, body copy format, CTA approach
   - Conversation Ad strategy: how to use comment-section ads to spark authentic discussion
   - Free-Form Ad layout for comparison/educational content
   - 3 specific ad concepts for this company with headline, body copy, and targeting rationale
   - What NOT to do: specific creative patterns that Reddit communities downvote or report

4. BOFU RETARGETING SEQUENCE
   Design a retargeting program for a 45-75 day buying cycle:
   - Segment 1 (Hot — visited /pricing or /demo in last 14 days): audience size estimate, creative angle, offer, CTA
   - Segment 2 (Warm — visited /vs-competitor or /features in last 30 days): audience, creative angle, offer
   - Segment 3 (Engaged — visited blog/technical content in last 60 days): audience, creative angle, offer
   - Competitive conquesting approach: targeting users in competitor-named subreddits or communities
   - Frequency caps per segment to avoid Reddit community backlash

5. REDDIT PIXEL & CONVERSIONS API SETUP
   - Required pixel events for B2B: PageView, Lead, SignUp, Purchase (demo request = conversion event)
   - Reddit Conversions API (CAPI) setup for cookieless tracking
   - Server-side event configuration: which identifiers to pass (email hash, MAID)
   - UTM structure: utm_source=reddit, campaign/adset/ad naming convention
   - Attribution window setting for a 45-75 day B2B sales cycle

6. PIPELINE MEASUREMENT FRAMEWORK
   - Weekly KPI dashboard: CPM, CTR, CPC, CPL, MQL-to-SQL conversion rate, cost-per-opportunity, sourced pipeline
   - How to close the loop from Reddit lead to CRM opportunity to closed-won
   - 30/60/90-day performance benchmarks for this ICP and budget
   - Early warning signals that a campaign is failing on Reddit (before burning budget)
   - Reddit-specific quality signals (comment engagement rate, upvote ratio on promoted posts)

Output as a structured, actionable plan. Include specific subreddit names with subscriber counts, exact copy examples, and implementation steps executable in Reddit Ads Manager today.

## Advanced Customizable Version

ROLE: You are a principal Reddit Ads strategist and B2B demand generation architect with 10+ years building pipeline programs for technical and professional B2B companies. You have managed Reddit Ads programs ranging from $5K/month for seed-stage startups to $150K/month for enterprise software companies. You understand Reddit's auction mechanics, community culture, ad relevance scoring, and the fundamental difference between advertising to a community versus advertising at one. You know how to identify buyer subreddits, construct targeting stacks that reach real decision-makers (not students and hobbyists), write copy that earns upvotes rather than downvotes, and connect Reddit spend to closed revenue in complex multi-touch B2B sales cycles. Unlike most paid social practitioners who copy LinkedIn playbooks onto Reddit, you treat Reddit as an entirely distinct channel with its own psychology, creative requirements, and performance benchmarks. Your output should feel like hiring a $275/hr B2B Reddit specialist who has built this exact motion for companies in this space.

---

SECTION 1: PROGRAM PARAMETERS

Company Overview:
- Company name and description: [Name] — [1-sentence description: what you do, who you do it for, key outcome]
- Category: [e.g., DevOps tooling / Cybersecurity / HR Tech / FinTech / Data Infrastructure / Developer Tools / RevOps]
- Stage: [Seed / Series A / Series B / Series C+ / Public]
- ARR range: [e.g., "$5M–$15M ARR"]

ICP Definition (be specific — Reddit targeting works best with precision):
- Primary buyer persona: [Title, department, company stage, team size they manage]
- Secondary personas (buying committee): [Other stakeholders who influence the deal]
- Company profile: [Employee count range, funding stage, tech stack signals, industry verticals]
- Geographic focus: [US only / NA / Global — Reddit skews heavily US/English-speaking]
- What does this ICP search on Reddit when they have the problem you solve?: [3-5 specific search queries or post topics]

Business Goals:
- Monthly Reddit budget: [$X]
- Primary KPI: [CPL / cost-per-demo / cost-per-trial / cost-per-opportunity]
- Monthly lead volume target: [X leads/month]
- Pipeline target: [$X sourced pipeline per quarter]
- Sales cycle length: [X days average]
- ACV: [$X average contract value]

Competitive Context:
- Direct competitors: [List 3-5]
- Competitor subreddits or communities: [e.g., "r/datadog users complain in r/devops"]
- Your key differentiators vs. each competitor: [1-2 per competitor]
- Competitor weaknesses Reddit users commonly mention: [e.g., "pricing complaints, support issues, complexity"]

Current State:
- Existing Reddit Ads: [None / Some campaigns running / link to account structure]
- Organic Reddit presence: [Company Reddit account activity, subreddit participation, organic mentions]
- Retargeting pool: [Website monthly visitors, high-intent page visitors, customer email list size]
- CRM and MAP: [e.g., Salesforce + HubSpot / Salesforce + Marketo / HubSpot only]
- Attribution model: [First-touch / Last-touch / Linear / Time-decay / Data-driven]

---

SECTION 2: SUBREDDIT INTELLIGENCE MAP

For this company's ICP, produce a comprehensive subreddit targeting map across three tiers.

TIER 1 — DIRECT INTENT COMMUNITIES (highest commercial relevance)
For each subreddit, provide:
- Subreddit name (r/example)
- Subscriber count and daily active estimate
- Why this community contains the ICP
- Dominant post types (troubleshooting, career, product comparison, news)
- Sentiment toward vendor advertising (tolerant / hostile / mixed)
- Top 3 post themes in this community that signal buying intent
- Recommended ad framing for this specific community
- Expected CPM range based on competition level

Provide 4-6 Tier 1 subreddits.

TIER 2 — ADJACENT PROFESSIONAL COMMUNITIES
Communities where the ICP participates for adjacent reasons (career development, related tools, industry news). Less purchase intent, more brand-building value.
Provide 6-8 Tier 2 subreddits with same structure above (abbreviated).

TIER 3 — BROAD PROFESSIONAL CONTEXT
Large professional subreddits (r/cscareerquestions, r/webdev, r/business, r/entrepreneur, r/sales) for scale and reach. Use for awareness only, not conversion campaigns.
Provide 3-5 Tier 3 subreddits.

KEYWORD TARGETING CLUSTERS
Reddit's keyword targeting matches ads to users who have searched or posted using specific terms. Build 4 keyword clusters:
- Cluster 1: Problem-aware keywords (what users type when experiencing the problem)
- Cluster 2: Solution-aware keywords (category terms, "best X for Y" queries)
- Cluster 3: Competitor keywords (competitor brand names, "vs" comparisons)
- Cluster 4: Job-role keywords (role-specific terminology ICPs use)
For each cluster: 10-15 specific keywords, estimated monthly search volume on Reddit, bid guidance.

---

SECTION 3: FULL-FUNNEL CAMPAIGN ARCHITECTURE

Design a complete Reddit Ads program with 4-6 campaigns. For each campaign:

Campaign [#]: [Name]
- Objective: [Brand Awareness / Traffic / Conversions / Video Views]
- Funnel stage: [TOFU / MOFU / BOFU]
- Primary targeting: [Subreddit targeting / Keyword targeting / Interest targeting / Retargeting]
- Target subreddits or keyword clusters: [Specific list]
- Ad format: [Promoted Post / Conversation Ad / Free-Form Ad / Trending Takeover]
- Budget: [$X/day | $X/month | X% of total budget]
- Bid strategy: [Target CPA / Max CPC / CPM / Optimized CPM]
- Starting bid: [$X CPM or $X CPC]
- Primary KPI for this campaign: [CPM / CTR / CPL / ROAS]
- Success threshold: [When to scale vs. pause]
- Audience size estimate: [X users]

Campaign budget allocation summary:
- TOFU awareness: X%
- MOFU consideration: X%
- BOFU conversion: X%
- Retargeting: X%

---

SECTION 4: COMMUNITY-NATIVE CREATIVE SYSTEM

Reddit creative that works looks nothing like LinkedIn or Meta creative. Build a creative system for this company.

THE REDDITOR TEST:
Before any ad runs, it must pass this test: "Would a Redditor upvote this if it appeared as an organic post from a company they respected?" Apply this framework to every creative concept below.

PROMOTED POST CREATIVE FORMULA
Anatomy of a high-performing B2B Reddit Promoted Post:
- Headline (max 300 characters): [Formula: benefit-first or problem-first? include specific numbers? question vs. statement?]
- Body copy structure: [How many paragraphs? Opening hook style? How to build credibility without sounding corporate?]
- Image/video guidance: [Screenshot vs. diagram vs. video? Technical vs. polished? File specs and dimensions]
- CTA button copy: [Which CTAs work for each funnel stage — "Learn More" vs. "Try Free" vs. "See Pricing"]
- Upvote/downvote management: [When to enable/disable comments, how to respond to negative comments professionally]

Write 3 complete Promoted Post ads for this company:
- Ad 1 (TOFU, community awareness): Full headline + body + CTA + target subreddit rationale
- Ad 2 (MOFU, competitive comparison): Full headline + body + CTA + competitive angle
- Ad 3 (BOFU, direct response to retargeting pool): Full headline + body + CTA + conversion focus

CONVERSATION AD STRATEGY
Conversation Ads appear in the comment thread below organic posts. Unlike Promoted Posts, they interrupt active discussions. Use only for:
- High-intent subreddits where competitors are being discussed negatively
- Organic posts comparing solutions (include your product in the discussion)
- Technical troubleshooting threads where your product solves the stated problem
Provide 2 Conversation Ad concepts with comment context, headline, and response copy.

FREE-FORM AD TEMPLATE
Free-form Ads allow custom layouts with more content — best for comparison pages, technical guides, and longer-form value propositions.
Design 1 Free-Form Ad layout for this company: section headers, content types (bullet lists, screenshots, callouts), and expected use case.

CREATIVE ANTI-PATTERNS (what destroys Reddit ad performance):
List 8 specific creative approaches that Reddit communities reject, with examples of each pattern and why it fails.

---

SECTION 5: BOFU RETARGETING & COMPETITIVE CONQUESTING

RETARGETING AUDIENCE SEGMENTS (build 4 segments based on website behavior):

Segment A — High Intent (last 14 days):
- Definition: Visited /pricing, /demo, /get-started, or /trial
- Estimated audience size: [X visitors/month]
- Creative angle: [Remove objections, provide social proof, urgency/scarcity if applicable]
- Offer: [Demo + bonus / ROI calculator / competitive comparison]
- Frequency cap: [X impressions/user/day — Reddit retargeting fatigue threshold]
- Budget allocation: [X% of retargeting budget]

Segment B — Consideration (last 30 days):
- Definition: Visited /features, /integrations, /vs-[competitor], or /case-studies
- Creative angle: [Differentiation, use case depth, customer evidence]
- Offer: [In-depth content / technical guide / recorded demo]
- Frequency cap: [X impressions/user/day]

Segment C — Early Research (last 60 days):
- Definition: Visited blog, documentation, or general product pages
- Creative angle: [Problem education, category leadership, brand credibility]
- Offer: [Newsletter signup / free tool / benchmark report]
- Frequency cap: [X impressions/user/day]

Segment D — Customer Suppression & Lookalike Seed:
- Upload customer email list for suppression (exclude from all campaigns)
- Use same list as seed for Reddit Lookalike Audience at 1% similarity
- Build secondary lookalike at 2-3% for scale with lower bid

COMPETITIVE CONQUESTING STRATEGY:
Reddit is uniquely valuable for competitive conquesting because competitors are openly discussed in communities. Build a conquesting approach:
- Identify 3 competitor brand-name keyword clusters to bid on
- Identify subreddits where competitor users congregate and complain
- Creative angle for each competitor comparison (address top Reddit complaints)
- Conquesting ad copy that doesn't mention competitors by name (Reddit policy compliance)
- Bid strategy for competitor keyword targeting (expect 30-50% higher CPCs)

---

SECTION 6: TECHNICAL SETUP — REDDIT PIXEL & CONVERSIONS API

REDDIT PIXEL IMPLEMENTATION
Required pixel events for B2B Reddit attribution:
- PageView: fire on all pages (universal tag)
- Lead: fire on demo request form submission, newsletter signup, gated content download
- SignUp: fire on free trial account creation, product signup
- Purchase: fire on paid subscription start or closed deal (via CRM webhook)
- Custom Events: [ViewContent for key product pages, Search for in-site search]

Event parameters to pass with each event:
- value (deal value or estimated LTV)
- currency (USD)
- item_id (product tier or campaign offer)
- email (hashed SHA-256 for identity resolution)

REDDIT CONVERSIONS API (CAPI) — COOKIELESS TRACKING
Reddit's CAPI allows server-side event firing that bypasses ad blockers and browser privacy restrictions.
Step-by-step CAPI setup:
1. Authentication: obtain access token and ad account ID
2. Required endpoint: POST https://ads-api.reddit.com/api/v2.0/conversions/events/[account_id]
3. Event deduplication: use event_id to prevent double-counting pixel + server-side events
4. Identifiers to pass for match rate optimization: email hash, IP address, user agent, external_id (CRM contact ID)
5. Testing: use Reddit's event testing tool to verify events fire correctly before launching
6. Expected match rate for B2B (email-based lists): 40-65% identity match on Reddit

UTM PARAMETER CONVENTION:
- utm_source: reddit
- utm_medium: paid-social
- utm_campaign: [campaign-objective]-[funnel-stage]-[target-community] (e.g., conversions-bofu-devops)
- utm_content: [ad-format]-[creative-variant] (e.g., promoted-post-v1-competitive)
- utm_term: [keyword-cluster-or-subreddit] (e.g., kubernetes-monitoring or r-devops)

ATTRIBUTION WINDOW CONFIGURATION:
- Click-through attribution: 30 days (Reddit click to CRM opportunity can take 2-4 weeks for B2B)
- View-through attribution: 1 day only (Reddit view-through is unreliable for B2B attribution)
- Cross-device attribution: enable if running both mobile and desktop campaigns

---

SECTION 7: PIPELINE MEASUREMENT & OPTIMIZATION FRAMEWORK

WEEKLY KPI DASHBOARD (track every Monday):
For each active campaign:
- Impressions, CPM, Impression Share (estimated)
- Clicks, CTR, CPC
- Leads/Conversions, CPL
- Upvote ratio (Reddit-specific quality signal — aim for >50%)
- Comment sentiment (positive/negative/neutral breakdown)
- MQL-to-SQL conversion rate (from CRM)
- Cost-per-opportunity (CPO)
- Pipeline sourced ($)

MONTHLY PIPELINE ATTRIBUTION REPORT:
- Total Reddit Ads spend
- Pipeline attributed (first-touch + linear)
- Pipeline-to-spend ratio (target: 5-10x for B2B SaaS)
- Closed-won revenue influenced by Reddit touchpoints
- ROAS (if using last-touch) and pipeline ROI (if using first-touch)
- Subreddit-level performance breakdown: which communities produce the highest-quality leads

PERFORMANCE BENCHMARKS (B2B SaaS Reddit Ads, updated Q1 2026):
- Average CPM: $4-$9 (vs. $30-$80 on LinkedIn)
- Average CTR on Promoted Posts: 0.4-1.2%
- Average CPC: $1.50-$5.00
- Average CPL for B2B (demo request): $80-$220
- Average upvote ratio on high-quality B2B promoted posts: 55-75%
- Conversion rate (click to lead): 3-8% for high-intent subreddit targeting

EARLY WARNING SIGNALS (pause campaign if any of these appear within 7 days):
1. Upvote ratio below 30% → Creative is being rejected by community; test new angle immediately
2. CTR below 0.15% for conversion campaigns → Audience-creative mismatch; review targeting
3. CPL above 3x target after 200+ clicks → Audience quality problem; tighten subreddit selection
4. Comment section showing product complaints or pricing objections → Sales/CS feedback loop needed
5. Impressions dropping despite stable bid → Campaign fatigue; refresh creative or expand targeting
6. MQL-to-SQL rate below 10% → Traffic quality problem; restrict to Tier 1 subreddits only

MONTHLY OPTIMIZATION CADENCE:
- Week 1: Review performance data, identify top and bottom performers
- Week 2: Kill bottom 20% of ad sets, double budget on top 20%
- Week 3: Launch 2-3 new creative variants based on community feedback signals
- Week 4: Update subreddit targeting based on new community research, refresh retargeting segments

---

SECTION 8: LAUNCH ROADMAP (90 DAYS)

Days 1-14 (Foundation):
- Install Reddit Pixel and verify all events fire correctly
- Set up CAPI integration with server-side events
- Upload customer email list for suppression and lookalike seeding
- Launch 1 TOFU Promoted Post campaign in 3 Tier 1 subreddits (no conversion objective yet)
- Launch 1 retargeting campaign for Segment A (high-intent website visitors)
- Budget: 70% TOFU awareness, 30% retargeting

Days 15-30 (Learning Phase):
- Review first 2 weeks of data: which subreddits produce clicks, which produce leads
- Launch MOFU campaign with competitive comparison angle
- A/B test 2 creative variants in best-performing subreddit
- Enable Conversation Ads in 2 highest-intent subreddits
- Budget: 50% TOFU, 30% MOFU, 20% retargeting

Days 31-60 (Optimization Phase):
- Scale budget to subreddits with CPL at or below target
- Pause underperforming communities
- Launch keyword targeting campaigns for top 2 keyword clusters
- Add competitive conquesting campaigns
- Begin lookalike expansion (1% lookalike of customer list)
- Budget: 30% TOFU, 40% MOFU, 30% retargeting/conquesting

Days 61-90 (Scale Phase):
- Run full-funnel program across all 4 campaign types
- Test Free-Form Ads for highest-converting offer
- Expand to Tier 2 subreddits with learnings from Tier 1
- Establish monthly optimization cadence
- Present 90-day pipeline attribution report to leadership
- Budget: 20% TOFU, 40% MOFU, 40% BOFU/retargeting

Produce this output as a structured implementation plan. Every recommendation must include the specific Reddit Ads Manager setting, menu location, or API field name to make execution frictionless.

## Example Input/Output

**Input Example:**

Company: Stackline — AI-powered infrastructure cost optimization platform for Kubernetes-heavy engineering teams at Series B through Series D SaaS companies.

ICP: Platform Engineers, DevOps Leads, VP Engineering at B2B SaaS companies, 150–1,500 employees, $5M–$100M ARR, Kubernetes in production.

Deal size: $32K ACV, 60-day sales cycle, 3-person buying committee (Platform Eng, VP Eng, CFO).

Monthly budget: $10,000/month. Goal: 30 qualified demo requests/month at under $335 CPL.

Competitors: Kubecost, CAST AI, StormForge.

Key subreddits: r/kubernetes, r/devops, r/aws, r/sre, r/googlecloud.

---

**Output Example (condensed):**

**Subreddit Targeting Map (Tier 1):**

| Subreddit | Subscribers | Intent Signal | CPM Est. | Recommended Framing |
|-----------|------------|--------------|----------|-------------------|
| r/kubernetes | 218K | "EKS costs out of control" posts weekly | $6-$9 | Technical cost audit content |
| r/devops | 312K | FinOps discussions, cloud bill complaints | $5-$7 | ROI calculator + "how we saved $180K" angle |
| r/sre | 95K | Capacity planning, resource optimization | $7-$10 | Reliability + cost trade-off framing |
| r/aws | 478K | Reserved instance vs. Spot discussions | $4-$6 | AWS-specific cost optimization |

**Sample TOFU Promoted Post (r/kubernetes):**

> **Headline:** We analyzed 500 Kubernetes clusters. The average team is overpaying by 47%.
>
> **Body:** Most teams configure Kubernetes for worst-case load and forget to right-size. After auditing 500 real-world clusters last quarter, we found the median team is running at 53% utilization while paying for 100%.
>
> We built a free Kubernetes Cost Audit that shows you exactly where the waste is — broken down by namespace, workload, and node pool.
>
> No sales call required. Just connect your cluster read-only and get your report in 15 minutes.
>
> **CTA:** Run Free Audit →

*Result: 1.2% CTR in r/kubernetes, 71% upvote ratio, $210 CPL, 22 demo requests in 30 days*

**30-Day Pipeline Attribution:**
- Spend: $8,400
- Demo requests: 22
- MQL-to-SQL rate: 45% (10 opportunities)
- Average deal size: $32K
- Pipeline sourced: $320K
- Pipeline-to-spend ratio: 38x

## Success Metrics

- **CPL at or below benchmark:** Target $150-$300 for technical B2B audiences (vs. $400-$900 on LinkedIn)
- **Upvote ratio above 50%:** Indicates creative is resonating with community, not being rejected
- **MQL-to-SQL rate above 25%:** Subreddit-targeted leads show higher intent than broad social
- **Pipeline-to-spend ratio above 10x:** Reddit should produce $10+ pipeline for every $1 spent within 90 days
- **Retargeting CPL 50% lower than prospecting:** Retargeting your website visitors via Reddit should be significantly more efficient than cold prospecting
- **Comment engagement rate above 2%:** Indicates posts are generating community discussion vs. being scrolled past

## Related Prompts

- [AI-Powered Meta Ads B2B Pipeline & Retargeting Intelligence Engine](./AI-Powered-Meta-Ads-B2B-Pipeline-&-Retargeting-Intelligence-Engine.md)
- [AI-Powered LinkedIn Ads B2B Pipeline & Account-Based Advertising Intelligence Engine](./AI-Powered-LinkedIn-Ads-B2B-Pipeline-&-Account-Based-Advertising-Intelligence-Engine.md)
- [AI-Powered B2B Performance Marketing & Paid Demand Generation Intelligence Engine](./AI-Powered-B2B-Performance-Marketing-&-Paid-Demand-Generation-Intelligence-Engine.md)
- [Reddit Organic Community Marketing & Demand Intelligence Engine](../../03_Content-&-Creative/Social-Media-Content/Reddit-Organic-Community-Marketing-&-Demand-Intelligence-Engine.md)

## Integration Tips

- **HubSpot:** Use HubSpot's Reddit Ads integration (via the Ads tool) to sync Reddit lead form submissions directly to contacts. Set lifecycle stage to "Lead" and source to "Paid Social - Reddit" automatically via workflow.
- **Salesforce:** Map Reddit UTM parameters to Campaign Influence using Salesforce's Campaign object. Create a Reddit Ads campaign record and associate opportunities via first-touch or multi-touch attribution.
- **Marketo:** Add Reddit as a program channel in Admin > Tags > Channels. Use Munchkin tracking on your website to capture Reddit click data and feed into scoring programs.
- **Google Analytics 4:** Create a custom channel group in GA4 that classifies `utm_source=reddit` + `utm_medium=paid-social` as "Reddit Ads" for accurate channel attribution in acquisition reports.
- **Zapier / Make:** When a Reddit Lead Gen Ad form is submitted, use Zapier to push the lead to HubSpot/Salesforce, trigger a Slack notification to SDR, and enroll in a 5-step email nurture sequence automatically.
- **Reddit's Lead Gen Ads API:** For high-volume Reddit lead gen campaigns, connect Reddit's Lead Gen Ads to your CRM via Reddit's direct API integration (available for HubSpot and Salesforce) to eliminate manual CSV downloads.

## Troubleshooting

**Problem: High impressions, very low CTR (under 0.1%), no leads**
*Solution:* Your creative is failing the Redditor test — it looks too corporate. Rewrite your headline to be data-driven or problem-focused (e.g., "We spent 6 months analyzing 300 DevOps teams' Kubernetes costs. Here's what we found."). Remove any stock imagery and replace with real product screenshots or community-relevant visuals. Consider turning off comments if you're testing a new angle — comment sections on failing ads often compound the damage.

**Problem: Leads are coming in but MQL-to-SQL conversion is below 10%**
*Solution:* You're reaching the wrong audience. Audit your targeting: if you're using Tier 3 broad subreddits (r/technology, r/programming), shift 80% of budget to Tier 1 community targeting only. Check UTM data — if most leads are coming from mobile devices at midnight, you're reaching students or hobbyists in your target subreddits, not professionals. Add company size and seniority overlays using Reddit's Interest Targeting filters to narrow the audience.

**Problem: Campaign is performing well in weeks 1-3, then performance drops sharply**
*Solution:* Reddit community audiences are relatively small compared to Facebook/Instagram. You're experiencing audience fatigue — Reddit users in niche subreddits will see your ad repeatedly and start ignoring it. Solutions: (1) Implement strict frequency caps (3 impressions/user/week maximum for subreddit-targeted campaigns), (2) Rotate creative every 3 weeks rather than every 6-8 weeks as you might on LinkedIn, (3) Expand to Tier 2 subreddits to extend reach, (4) Pause for 2 weeks and re-enter with fresh creative — Reddit community members have shorter ad memory than Facebook users.

## Version History
- v1.0: Initial creation (auto-generated)
