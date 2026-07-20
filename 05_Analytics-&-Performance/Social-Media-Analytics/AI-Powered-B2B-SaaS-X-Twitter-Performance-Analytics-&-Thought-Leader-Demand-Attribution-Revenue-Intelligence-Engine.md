# AI-Powered B2B SaaS X/Twitter Performance Analytics & Thought Leader Demand Attribution Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** social-media-analytics, x-twitter, dark-social, thought-leadership, pipeline-attribution, b2b, demand-gen, revenue-ops

## Overview
Builds a complete analytics framework for measuring X/Twitter's contribution to B2B SaaS pipeline and revenue — including Thought Leader Ads attribution, dark social signal extraction, community conversation mining, and cross-platform integration with your CRM and ABM stack. Use this when you need to prove (or disprove) X/Twitter's ROI, optimize your thought leader content investment, or identify high-intent account signals hiding in public conversations.

## Quick Copy-Paste Version

You are a senior B2B marketing analytics strategist specializing in social media attribution and dark funnel intelligence. Analyze the X/Twitter performance data for a B2B SaaS company and build a complete revenue attribution framework.

Company context:
- Product: [Your SaaS product — e.g., "AI-powered revenue intelligence platform for enterprise sales teams"]
- Target ICP: [Ideal customer profile — e.g., "VP Sales, CRO, RevOps leaders at Series B+ B2B SaaS companies, 50-500 employees"]
- Monthly X/Twitter budget: [e.g., "$8,000/month across organic + Thought Leader Ads"]
- Current X/Twitter activity: [e.g., "CEO posts 3x/week, 2 Account Executives active, no paid TLA yet"]
- CRM: [e.g., "Salesforce"]
- Monthly pipeline target: [e.g., "$3M/month"]

Build a complete X/Twitter performance analytics system that covers:

1. CONTENT PERFORMANCE METRICS
   - Which content formats drive the highest engagement-to-pipeline correlation (threads, polls, replies, original takes, data posts)
   - Follower quality scoring: distinguish between ICP followers vs. vanity followers
   - Content half-life analysis: how long do posts drive traffic and pipeline signals?
   - Engagement rate benchmarks for B2B SaaS accounts by follower size

2. THOUGHT LEADER ADS (TLA) ATTRIBUTION
   - How to measure TLA contribution to pipeline when direct attribution is hidden by dark social
   - Incrementality methodology for TLA campaigns: control vs. exposed account pipeline rates
   - Optimal TLA post selection criteria: which organic posts to amplify and why
   - TLA audience targeting recommendations for ICP accounts
   - Cost-per-ICP-impression vs. cost-per-pipeline-influenced metrics

3. DARK SOCIAL SIGNAL EXTRACTION
   - How to identify X/Twitter as a demand source even when it doesn't appear in UTM attribution
   - Self-reported attribution survey design to capture "Where did you first hear about us?"
   - Conversation mining: finding accounts discussing your category, competitors, or pain points
   - Brand mention monitoring for buying signals vs. general awareness mentions
   - Converting public conversations into outbound triggers for sales/SDR teams

4. ACCOUNT-LEVEL ENGAGEMENT INTELLIGENCE
   - Identifying ICP companies engaging with your content (follows, likes, replies, quote posts)
   - Integrating X/Twitter account engagement into your ABM platform (6sense, Demandbase)
   - Creating "social engagement score" for target accounts and routing to SDR/AE teams
   - Executive-level engagement signals: when a target company's VP+ engages, alert AE

5. COMPETITIVE INTELLIGENCE FROM X/TWITTER
   - Tracking competitor share of voice in relevant conversations and hashtags
   - Mining competitor mentions for dissatisfied customers (acquisition opportunities)
   - Monitoring competitor executive posts for strategic direction signals
   - Category conversation trend analysis: which pain points are gaining traction?

6. REPORTING & PIPELINE ATTRIBUTION MODEL
   - Monthly X/Twitter impact report structure for CMO/leadership
   - How to include dark social attribution in pipeline source reporting
   - CAC calculation for X/Twitter channel including Thought Leader Ads investment
   - Pipeline influenced vs. pipeline sourced from X/Twitter: definitions and tracking methods

Produce a 90-day X/Twitter analytics implementation plan with specific metrics, data sources, and tools needed. Include a sample dashboard structure and the top 5 KPIs to report to leadership.

## Advanced Customizable Version

ROLE: You are a Chief Marketing Intelligence Officer with 15+ years of B2B SaaS marketing analytics experience. You specialize in dark funnel attribution, social media revenue intelligence, and connecting platform signals to CRM pipeline data. You approach X/Twitter not as a vanity metrics platform but as a buyer intelligence system.

CONTEXT:
Company: [Company name]
Stage: [Series A/B/C/D or Revenue range]
Product category: [e.g., "AI-powered compliance automation for financial services"]
ICP definition:
  - Primary: [Title, company size, industry, tech stack indicators]
  - Secondary: [Adjacent personas and expansion titles]
ACV: [$X annual contract value]
Current X/Twitter presence:
  - Company account followers: [X]
  - Avg engagement rate: [X%]
  - Active executive/employee posters: [names and follower counts]
  - Current Thought Leader Ads investment: [$X/month or "none yet"]
  - Top-performing post types historically: [threads/data/hot takes/replies]
Marketing attribution model: [last-touch / multi-touch / self-reported / MMM]
CRM: [Salesforce/HubSpot with relevant objects]
ABM platform: [6sense/Demandbase/Terminus or "none"]
Monthly pipeline target: [$X]
Current pipeline source mix: [% from each channel]

OBJECTIVE: Design a comprehensive X/Twitter analytics intelligence system that transforms social engagement data into actionable pipeline insights, proving the channel's revenue contribution and identifying high-intent accounts before they raise their hand.

---

## LAYER 1: X/TWITTER CONTENT PERFORMANCE ANALYTICS

**Content Taxonomy & Performance Framework:**

Categorize all X/Twitter content into these archetypes and track performance by type:

1. **POV/Contrarian Takes** — Strong opinions that challenge conventional wisdom in your category
   - KPIs: Impressions, reply rate, quote post rate, follower growth, ICP follower conversion
   - Benchmark target: Reply rate >0.8% for accounts with 5K+ followers

2. **Data/Research Posts** — Proprietary data, survey results, industry benchmarks
   - KPIs: Bookmarks, link clicks to full report, media pickup rate
   - Benchmark target: Bookmark rate >2x your average engagement rate

3. **Thread Deep-Dives** — Educational multi-tweet threads on category problems
   - KPIs: Thread completion rate (engagement on final tweet vs. first), saves, newsletter signups attributed
   - Benchmark target: Final tweet engagement ≥25% of first tweet engagement

4. **Engagement Bait (Strategic)** — Polls, questions, "hot take" prompts designed to surface ICP opinions
   - KPIs: Poll response rate, reply quality score (are responders ICP?), lead-to-conversation rate
   - Benchmark target: >15% of poll respondents should match ICP persona

5. **Customer Story/Proof Posts** — Social proof with real customer outcomes
   - KPIs: Saves, shares to other channels, demo request correlation within 7 days of post

**ICP Follower Quality Scoring:**

Build a follower quality model that goes beyond raw follower count:

- ICP Fit Score (0-100): Title match + company size + industry + tech stack indicators scraped from bio
- Engagement History Score: Has this follower liked/replied/shared in past 90 days?
- Account Stage Score: Is this follower's company in your CRM? At what pipeline stage?
- Influence Multiplier: Does this follower have >1,000 followers in your ICP audience? Weight 2x.

Monthly reporting metric: **ICP Follower Growth Rate** (track growth of followers who score >70 on ICP Fit Score separately from total follower growth)

**Content Half-Life Analysis:**

For each post type, track traffic and engagement decay:
- Day 1: Baseline impressions and engagement
- Day 3: % of Day 1 impressions remaining (X algorithm tail)
- Day 7: Direct link clicks still occurring
- Day 30: Inbound form submissions attributing to this post (via self-reported attribution)

Insight: If your threads have longer half-lives than single posts, invest in threads for evergreen traffic. If data posts get media pickup that drives sustained traffic, prioritize proprietary research.

---

## LAYER 2: THOUGHT LEADER ADS (TLA) ANALYTICS & ATTRIBUTION

**TLA Campaign Architecture:**

Thought Leader Ads amplify posts from your executives and employees to targeted audiences. Unlike standard ads, they appear as organic posts, driving higher trust and engagement rates.

**TLA Attribution Methodology (for a long B2B sales cycle):**

Since buyers won't click a "Book a Demo" CTA on a TLA post, attribution requires a probabilistic approach:

1. **Exposed vs. Control Account Analysis:**
   - Define TLA target audience: company-specific targeting for Tier 1 ABM accounts, job title + industry for broader ICP
   - Separate accounts into: (A) Exposed to TLA impressions, (B) Matched control group (same ICP criteria, NOT targeted)
   - Measure pipeline creation rate difference between A and B groups over 30/60/90 days
   - If exposed accounts convert to pipeline at 2x+ the rate of control accounts → TLA is causal

2. **TLA Halo Effect Measurement:**
   - Track website visits from target accounts in the week following TLA campaign launch
   - Use Warmly, RB2B, or Dealfront to identify target company visitors
   - Flag accounts that visit pricing/demo pages within 14 days of TLA exposure → "TLA-influenced" pipeline segment

3. **Post Selection Criteria for TLA Amplification:**

Amplify posts that score highest on the TLA Performance Prediction Score:
   - Original engagement rate >2% → High relevance signal (worth amplifying)
   - Replies from ICP personas → Content resonates with target audience
   - Low promotional language → Passes authenticity filter (ads that feel like ads underperform)
   - Pain-point or insight focus (NOT product feature focus) → Converts at higher rate
   - Short enough to read without "Show More" → Full visibility without interaction required

4. **TLA Audience Targeting Layers:**

   - **Tier 1 ABM:** Company list upload (Salesforce opportunity stage "Awareness" or "Researching")
   - **Tier 2 ICP:** Job title targeting (CRO, VP Sales, RevOps, Sales Enablement) + company size + industry
   - **Tier 3 Competitive:** Followers of competitor accounts + relevant hashtag followers
   - **Retargeting:** Website visitors from target accounts in past 90 days

5. **TLA KPIs:**
   - Cost per ICP-matched impression: [(TLA spend) / (impressions × ICP match rate)]
   - TLA-to-pipeline acceleration: Time from TLA exposure to first meaningful engagement (meeting, demo, form fill)
   - Share of voice gain: Your exec's follower count growth vs. competitor executives in TLA flight period
   - Brand search lift: Branded search volume increase during/after TLA campaigns (Google Search Console)

---

## LAYER 3: DARK SOCIAL SIGNAL EXTRACTION & PIPELINE ATTRIBUTION

**The Dark Social Problem:**

Up to 70% of B2B buyers read content on X/Twitter without clicking, sharing, or engaging publicly. They mention your brand to colleagues in Slack, bring you up in meetings, and search your name directly — leaving no UTM trail. Standard analytics misses this.

**Dark Social Attribution Framework:**

1. **Self-Reported Attribution (Primary Method):**
   - Add "Where did you first hear about us?" as a required field in all demo request, trial, and gated content forms
   - Include "X/Twitter" and "Saw a post from [executive name]" as explicit options
   - Analyze monthly: what % of pipeline self-reports X/Twitter as first touchpoint?
   - Correlate with active TLA periods and high-engagement organic posts

2. **Conversation Signal Mining (Active Intelligence):**

Set up X/Twitter monitoring for these signal types:

   **Buying Signal Conversations:**
   - "[Category keyword] software recommendations" or "looking for a [category] tool"
   - "anyone use [your category]?" — direct vendor research intent
   - "our [specific pain point] is killing us" — pain amplification, pre-purchase signal

   **Competitive Signal Conversations:**
   - Complaints about competitors: "frustrated with [competitor name]" or "[competitor] keeps [problem]"
   - Competitor migration conversations: "[Competitor] → alternatives?" signals switching intent
   - "switching from [competitor]" — direct acquisition opportunity

   **Brand Signal Conversations:**
   - Mentions of your company name, executive names, or product name
   - Conference/event mentions where you're exhibiting or speaking
   - Content mentions: "read this piece from [your company]" or "great thread by [exec]"

3. **Conversation-to-CRM Pipeline:**
   - When a target ICP account (in your CRM or on your ABM list) posts a buying signal conversation → alert assigned SDR/AE
   - When a target account's executive follows you → alert AE with full account context
   - When a competitor customer posts complaints → route to BDR as warm outbound trigger
   - Response SLA: All Tier 1 account signals responded to within 4 business hours

4. **Anonymous Visitor De-Anonymization Linkage:**
   - When RB2B/Warmly/Dealfront identifies a target company visiting your site:
   - Check if that company has engagement activity on X/Twitter in the past 30 days
   - If yes, flag as "X/Twitter-influenced visitor" and route to AE with social context
   - Track correlation rate monthly: what % of website visitors from target accounts also showed X/Twitter activity?

---

## LAYER 4: ACCOUNT-LEVEL ENGAGEMENT SCORING & ABM INTEGRATION

**Account-Level Social Engagement Score:**

Build a composite score for each target account based on X/Twitter signals:

| Signal | Points | Decay |
|--------|--------|-------|
| Any employee from target company follows your account | +20 | None |
| Executive (VP+) from target company follows | +35 | None |
| Like/bookmark on your content | +5 | -50% per 30 days |
| Reply to your content (non-promotional) | +15 | -50% per 30 days |
| Quote post sharing your content | +25 | -50% per 30 days |
| Target company mentioned in conversation you're in | +10 | -75% per 14 days |
| Target company executive engages with your CEO/exec content | +30 | -50% per 30 days |
| Target company employee posts about your category | +20 | -75% per 14 days |

**ABM Integration Architecture:**

- Sync X/Twitter Account Engagement Score into 6sense/Demandbase as a custom intent signal
- When score exceeds threshold (e.g., >50 within 30 days): move account from "Awareness" to "Active Research" tier
- Trigger SDR outreach when: Engagement Score >50 AND company shows website intent AND firmographic fit >80
- In CRM: create "X/Twitter Social Engagement" activity log for all target accounts, visible on Account record

---

## LAYER 5: COMPETITIVE INTELLIGENCE FROM X/TWITTER

**Competitor Executive Monitoring:**

Track competitor CEOs, VPs of Marketing, and product leaders daily:
- New product announcements: flag to Product Marketing within 1 hour
- Hiring signals from executive posts: flag to demand gen ("excited to announce we're hiring 50 engineers")
- Strategic direction signals: new partnerships, pricing changes, market entry
- Customer complaint responses: mine thread replies for dissatisfied customers

**Category Conversation Trend Analysis:**

Weekly: Pull top 100 conversations mentioning your primary category keywords
- Track conversation sentiment over time: is pain around your category increasing?
- Identify emerging sub-topics: new pain points entering the conversation → new content opportunities
- Spot influencer voices: who generates the highest-quality conversations in your category? (Outreach candidates for partnerships)

**Competitor Customer Mining:**

- Monitor accounts replying positively to competitor content (they're customers) → Add to "Displacement Campaign" list
- Track competitor negative mention threads → Engage helpfully, not promotionally
- When competitor customers post publicly about switching or frustration → Tier 1 outreach trigger

---

## LAYER 6: REPORTING FRAMEWORK & PIPELINE ATTRIBUTION MODEL

**Monthly X/Twitter Intelligence Report Structure:**

**Section 1: Content Performance Summary**
- Top 5 posts by engagement (impressions × engagement rate)
- ICP follower growth rate vs. total follower growth rate
- Content type breakdown: what's working and why
- Competitor share of voice comparison

**Section 2: Thought Leader Ads Performance**
- Impressions delivered to ICP audience vs. total impressions
- TLA-exposed account pipeline creation rate vs. control group
- Cost per ICP impression this month
- Recommended posts to amplify next month (with performance prediction score)

**Section 3: Dark Social Attribution**
- Self-reported X/Twitter attribution from new leads this month
- Conversation signals captured and routed to sales
- Account-level engagement score distribution across Tier 1/2/3 accounts
- Correlation analysis: website visitor overlap with X/Twitter engaged accounts

**Section 4: Pipeline Intelligence**
- New pipeline opportunities where X/Twitter was a contributing signal
- Accounts that moved forward in pipeline within 30 days of high X/Twitter engagement
- Estimated pipeline influenced (not sourced) by X/Twitter this month
- CAC calculation: (TLA spend + X/Twitter team time) / (deals closed with X/Twitter attribution)

**Top 5 KPIs for Board/CMO Reporting:**
1. **ICP Follower Growth Rate** (quality followers, not vanity)
2. **TLA Pipeline Acceleration Rate** (exposed vs. control account pipeline conversion)
3. **Self-Reported X/Twitter Attribution %** (of all new pipeline this month)
4. **Conversation Signals Converted** (# of buying signal conversations that became pipeline)
5. **X/Twitter-Influenced Pipeline** ($ pipeline where X/Twitter was any touchpoint in buyer journey)

---

## 90-DAY IMPLEMENTATION ROADMAP

**Month 1: Foundation**
- [ ] Audit current X/Twitter presence: followers, engagement rates, content type performance
- [ ] Set up social listening tool (Brandwatch, Sprout Social, or native X/Twitter Advanced Search)
- [ ] Configure monitoring for: brand mentions, category keywords, competitor mentions, target account keywords
- [ ] Add self-reported attribution to all demand capture forms
- [ ] Build ICP Follower Quality Score model in spreadsheet (export followers via API + score manually for first 1,000)
- [ ] Create "X/Twitter Social Engagement" custom object/field in CRM

**Month 2: Intelligence Activation**
- [ ] Launch first Thought Leader Ads campaign: amplify top 3 posts from past 90 days to Tier 1 ABM account list
- [ ] Deploy account-level engagement tracking: route all Tier 1 account engagement alerts to AE/SDR team
- [ ] Run first competitive conversation mining: 30-day retrospective on competitor mentions
- [ ] Build X/Twitter-to-CRM signal routing workflow (n8n or Zapier): engagement → CRM activity log → SDR alert
- [ ] Establish baseline metrics for all 5 KPIs

**Month 3: Attribution & Optimization**
- [ ] Run first TLA exposed vs. control analysis (needs 30 days of data)
- [ ] Analyze self-reported attribution data: is X/Twitter showing up?
- [ ] Optimize TLA targeting based on ICP engagement data from Month 2
- [ ] Present first X/Twitter Intelligence Report to CMO/leadership
- [ ] Build first version of X/Twitter-influenced pipeline model for board reporting
- [ ] Decide: increase TLA investment or shift to organic content optimization based on data

---

OUTPUT FORMAT:
Produce the analytics architecture as:
1. Analytics System Overview (what we'll measure and why)
2. Data Collection Architecture (tools, APIs, manual processes)
3. Account Intelligence Workflow (how signals become sales actions)
4. Attribution Model Design (how we assign pipeline credit)
5. 30/60/90-day implementation plan with owner assignments
6. Dashboard wireframe description (what the CMO sees weekly)
7. 3 critical decision triggers: when to scale investment, when to reduce, when to shut down

## Example Input/Output

**Input Example:**

Company: Veridian — AI-powered contract intelligence platform for mid-market legal and finance teams
ACV: $36,000/year
ICP: General Counsel, VP Legal, CFO at 100-1,000 employee B2B companies using DocuSign, Ironclad, or Microsoft 365
Current X/Twitter: CEO (@mjohnson_gc) has 8,200 followers, posts 4x/week on contract tech/legal ops; 2 AEs posting occasionally; No Thought Leader Ads yet; Avg engagement rate 1.8%
CRM: HubSpot
ABM: None (evaluating 6sense)
Pipeline target: $1.5M/month
Pipeline source mix: 45% outbound SDR, 30% paid search, 15% content/SEO, 10% dark social/unknown

**Output Example (abbreviated):**

**ICP Follower Quality Analysis (Month 1 Audit):**

Of CEO's 8,200 followers, estimated ICP match:
- General Counsel / VP Legal titles: ~340 followers (4.1%)
- CFO / VP Finance titles at relevant company sizes: ~280 followers (3.4%)
- Total ICP followers: ~620 (7.5% of base)
- ICP Follower Growth target: +50 ICP followers/month (measured via monthly export + scoring)

This 7.5% ICP follower rate is actually strong for B2B SaaS. For context: accounts where ICP % drops below 4% typically see declining pipeline correlation from social. CEO should be targeting GC/VPL-heavy audience in every post — their current legal ops content is on track.

**TLA Campaign Design (Month 2):**

Target: 150 Tier 1 ABM accounts (identified in HubSpot as "Marketing Qualified" or "Opportunity")
Post to amplify: CEO's thread on "5 signs your contract process is leaking revenue" (4.2% engagement rate, 340 bookmarks)
Budget: $4,000 for 30-day TLA campaign to company-matched audience
Expected ICP impressions: 22,000 (at estimated $0.18/ICP impression)
Control group: 50 matched accounts NOT in TLA target list
Success metric: TLA-exposed accounts visit pricing page at 2x rate vs. control within 60 days

**Conversation Signal That Became Pipeline:**

Monitoring detected: @sarahmchen_gc (General Counsel at Fortis Capital, 380 employees) posted:
"Does anyone have a good recommendation for contract AI? Our current process is embarrassing — we're still using Word track changes for everything."

Alert routed to assigned AE → AE replied publicly with helpful resource (no product pitch) → GC followed back → AE sent DM 48 hours later → Demo booked → Opportunity created: $42K ACV deal

Classification: X/Twitter conversation signal → outbound trigger → pipeline created in 12 days (vs. avg 45-day cycle for cold outbound)

**Self-Reported Attribution (Month 3 finding):**

Of 38 new deals in Month 3:
- 6 (15.8%) cited "X/Twitter" or "saw a post from Mike Johnson" as first touchpoint
- 9 (23.7%) cited "word of mouth" (which correlates with dark social amplification)
- Combined potential X/Twitter influence: 15 deals = $540K pipeline

This substantially changes the channel ROI calculation: X/Twitter is contributing nearly 4x what last-touch attribution shows.

## Success Metrics

**Green (X/Twitter is working as a demand channel):**
- ICP follower growth rate: >50 new ICP-scored followers/month
- TLA-exposed account pipeline rate: >2x vs. matched control group
- Self-reported X/Twitter attribution: ≥10% of new pipeline
- Account engagement signals converted to pipeline: >2 per month from conversation mining
- CEO engagement rate: >1.5% (above B2B SaaS average of 0.8-1.2%)

**Yellow (Needs optimization):**
- ICP follower growth flat for 60+ days — audit content strategy and posting time/frequency
- TLA pipeline lift <1.5x vs. control — test different post types and refine audience targeting
- Self-reported attribution <5% — check if form option is clearly presented; may need attribution survey instead
- Zero conversation signals converted in 30 days — widen keyword monitoring and train SDR on response playbook

**Red (X/Twitter not generating sufficient ROI — reconsider investment):**
- TLA-exposed accounts show no pipeline lift vs. control after 90 days — pause TLA and audit content-audience fit
- Self-reported attribution <3% after 6 months — channel not resonating with ICP; redirect budget
- ICP follower % declining (dropping below 5%) — content is attracting wrong audience; content strategy reset required

## Related Prompts

- `../../05_Analytics-&-Performance/Social-Media-Analytics/AI-Powered-B2B-SaaS-LinkedIn-Performance-Analytics-&-Dark-Social-Pipeline-Revenue-Attribution-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Social-Media-Marketing/AI-Powered-B2B-SaaS-X-Twitter-Organic-Demand-Generation-&-Thought-Leader-Pipeline-Revenue-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-(PPC-&-Social)/X-Twitter-Ads-Campaign-Builder.md`
- `../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Dark-Funnel-Attribution-&-Anonymous-Buyer-Intent-Intelligence-Engine.md`

## Integration Tips

**HubSpot Integration:**
- Create custom property "X_Twitter_Engagement_Score" on Company record — update monthly via manual score or Zapier/Make workflow
- Build HubSpot workflow: when X/Twitter Engagement Score >50 + Company is in "Target Account" list → create Task for AE to review social activity
- Use HubSpot's "Original Source" field combined with self-reported attribution form field to build true first-touch attribution report
- Connect Brandwatch or Sprout Social to HubSpot via Zapier for real-time mention-to-activity logging

**Salesforce Integration:**
- Add "X/Twitter Engagement Score" as a custom field on the Account object
- Build Campaign record for each TLA flight — add exposed accounts as Campaign Members for attribution tracking
- Use Salesforce Reports to compare pipeline creation rate: Accounts with X/Twitter Engagement > 50 vs. matched accounts without engagement
- Build an Einstein Activity Timeline entry for each "Conversation Signal" captured from X/Twitter monitoring

**6sense/Demandbase Integration:**
- Use X/Twitter engagement data as a first-party intent signal uploaded via CSV weekly or API
- In 6sense: create custom segment "X/Twitter Engaged + High Intent" — combine social engagement score with 6sense intent stage
- Set up 6sense Advertising campaigns to retarget accounts showing BOTH X/Twitter engagement and website intent (compound signal = higher conversion)

**Sprout Social / Brandwatch Setup:**
- Create Smart Inbox rules: flag all mentions from accounts matching ICP firmographic criteria → auto-alert channel manager
- Build Competitive Analysis dashboard: your brand + 3 competitors, weekly share of voice report
- Export monthly "Brand Advocates" report: who engaged most with your content? Cross-reference against your CRM target account list

**Self-Reported Attribution Survey (Alternative to form field):**
- Deploy Typeform survey to all new customers at onboarding (Day 3): "We'd love to know — how did you first discover [Company]?"
- Include X/Twitter, TikTok, LinkedIn, Podcast, Event, Word-of-Mouth, Google Search, Sales Outreach as options
- Connect Typeform to HubSpot via native integration — auto-update "First Touch Channel" property on Contact
- Run quarterly: what % of customers who self-report X/Twitter closed in < average sales cycle? (Social-influenced deals often close faster)

## Troubleshooting

**Problem: Self-reported attribution shows <3% from X/Twitter despite active CEO posting**
Solution: X/Twitter is likely contributing as a lurker/passive awareness channel rather than a click channel. Buyers read posts without engaging — this is normal. Test: run a 30-day branded search volume analysis (Google Search Console) correlated with your busiest X/Twitter content periods. If branded search spikes during high-posting periods, X/Twitter is driving awareness even without clicks. Also survey your last 20 customers in onboarding calls with the specific question: "Before you booked a demo, had you seen any of our team's social media content?" You'll likely find 30-40% say yes, even if they didn't click.

**Problem: TLA campaign is reaching target accounts but pipeline isn't moving**
Solution: The issue is likely content-audience mismatch. Thought Leader Ads require content that addresses a pain point the audience is experiencing RIGHT NOW — not product features or company announcements. Pull the 5 organic posts with the highest engagement and audit: do they teach something specific, challenge a common assumption, or validate a frustration your ICP has? Those are the posts to amplify. If your CEO's best content is opinion-based personal reflection rather than professional insight, TLAs won't convert — organic LinkedIn may be a better channel for that content type.

**Problem: Conversation signal monitoring is generating too many irrelevant alerts — sales team ignoring them**
Solution: Your keyword triggers are too broad. Narrow from category keywords to buyer journey keywords. Instead of monitoring "contract management" (too broad), monitor "[your category] software" + "looking for" or "recommendations" + "frustrated" + "[competitor name]". Also add firmographic filters: only alert when the posting account's bio indicates ICP title (use Boolean logic in Brandwatch/Sprout: keyword match AND bio contains "General Counsel" OR "VP Legal" OR "CFO"). Within 2 weeks of narrowing, alert volume will drop 70% while signal quality triples — sales teams will start acting on them.

## Version History
- v1.0: Initial creation (auto-generated)
