# AI-Powered B2B SaaS Organic Social Competitive Intelligence & Buyer Signal Demand Activation Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** b2b, social-media, competitive-intelligence, demand-generation, buyer-signals, social-listening, pipeline, automation

## Overview

Builds a fully automated organic social intelligence system that scans LinkedIn, X/Twitter, Reddit, and niche communities in real time to intercept in-market buyers, identify competitor-dissatisfied customers, and route high-confidence buying signals directly into CRM sequences — converting passive social monitoring into an active, AI-driven demand generation engine without paid media spend.

## Quick Copy-Paste Version

You are a senior B2B SaaS demand generation strategist specializing in social intelligence and signal-based pipeline generation. Build a complete organic social buyer signal interception system for [Your Company] that sells [Product Description] to [ICP: Title, Company Size, Industry].

Design the following:

1. SIGNAL LIBRARY & BUYING TRIGGER TAXONOMY
Build a comprehensive signal detection framework:
- Competitor complaint signals: exact phrases and patterns that indicate dissatisfaction with [Competitor 1], [Competitor 2], [Competitor 3] (e.g., "switching from X", "frustrated with X", "X is getting worse", "looking for alternative to X")
- Category intent signals: posts and questions indicating active evaluation (e.g., "[Category] software recommendations", "anyone using [category] tools", "help choosing between [us] and [competitor]")
- Pain point signals: statements that map to our core value proposition without mentioning any vendor (e.g., pain-point language your ICP uses about the problem we solve)
- Trigger event signals: job changes, funding announcements, company scaling signals, tech stack changes detectable via social posts
- Buying committee signals: posts from CFO/VP/Director titles at target account companies about relevant budget, initiative, or project topics

2. PLATFORM MONITORING INFRASTRUCTURE
Specify the exact setup for each platform:
- LinkedIn: Boolean search strings for Sales Navigator, hashtag combinations to monitor, creator accounts to watch for ICP engagement, Company Page follower analysis
- X/Twitter: Advanced search operators, Twitter Lists of competitor customers and industry practitioners, real-time alert setup for competitor mentions
- Reddit: Subreddits to monitor (list specific subreddits), post frequency and upvote thresholds that indicate high-signal discussions, PRAW API configuration for automated scanning
- G2/Capterra/TrustRadius: Review alert setup for new competitor reviews mentioning switching intent or dissatisfaction patterns
- Industry Slack/Discord communities: which communities to join, keyword alert setup, engagement protocols

3. AI-POWERED SIGNAL SCORING & QUALIFICATION ENGINE
Design the qualification workflow:
- Signal scoring matrix: score each signal 1-10 based on (a) intent clarity, (b) ICP fit of poster, (c) urgency indicators, (d) buying committee seniority
- AI enrichment workflow: when a signal is detected, auto-enrich the prospect's company with Clearbit/Clay (funding, headcount, tech stack, recent news)
- ICP fit scoring: cross-reference signal source against ICP criteria before routing to sales
- False positive filtering: patterns and language that look like signals but aren't (researchers, students, competitors monitoring you, existing customers)
- Priority tiers: Tier 1 (score 8-10, route to sales within 2 hours), Tier 2 (score 5-7, add to automated nurture), Tier 3 (score 1-4, log for reporting only)

4. ENGAGEMENT PLAYBOOK & RESPONSE SCRIPTS
Define the exact engagement strategy for each signal type:
- Competitor complaint post: how to respond publicly without being salesy (add value first, offer insight, never directly pitch)
- Category question post: how to provide a genuinely helpful answer that naturally positions your product
- Pain point discussion: how to join the conversation authentically and establish expertise
- Direct mention of your brand by a non-customer: response protocol, timing, who responds (marketing vs. sales vs. executive)
- DM sequence for high-intent signals: 3-message sequence that warms cold social prospects without triggering spam responses
- "Comment-first, connect-second" protocol: the exact playbook for LinkedIn engagement that feels organic

5. AUTOMATION & ROUTING INFRASTRUCTURE
Build the end-to-end automation stack:
- Monitoring tool setup: Mention.com / Brand24 / Talkwalker configuration for automated alerts
- Clay workflow: auto-enrich social signal contacts, score ICP fit, push qualified leads to HubSpot/Salesforce
- Slack alert routing: real-time Slack notifications to sales rep assigned to that account territory
- CRM integration: how to log social signal touches as marketing interactions in Salesforce/HubSpot without corrupting attribution
- Zapier/Make automation chains: trigger → enrich → score → route → alert → log
- Weekly digest: automated report showing signals captured, qualified, engaged, and pipeline generated

6. PIPELINE ATTRIBUTION & MEASUREMENT SYSTEM
Define the full measurement framework:
- Social signal → pipeline attribution model: how to credit social intelligence-sourced opportunities
- Conversion funnel: Signal detected → Signal qualified → Engagement sent → Response received → Meeting booked → Opportunity created → Closed won
- Weekly KPIs: signals detected per platform, qualification rate, engagement response rate, meetings booked from social signals, pipeline sourced
- Monthly ROI report: time invested in social monitoring + tool costs vs. pipeline generated

Provide specific tool recommendations (Clay, Mention.com, Brand24, PRAW, PhantomBuster, LinkedIn Sales Navigator, Talkwalker, Zapier, HubSpot, Salesforce) for each layer. Output a 30/60/90-day ramp plan showing expected signal volume, qualification rates, and pipeline contribution by quarter.

## Advanced Customizable Version

ROLE: You are a Principal B2B Demand Generation Strategist with 15+ years of experience building signal-based pipeline programs for B2B SaaS companies. You specialize in converting passive social monitoring into active, high-converting demand generation engines. You have built social intelligence programs at companies from $10M to $500M ARR that generated 10-20% of total pipeline from organic social signals — with no paid media. You understand not just the strategy but the technical implementation: API configurations, Clay workflows, Zapier chains, CRM integration logic, and the psychology of engaging social prospects without triggering resistance. You know the exact language patterns that indicate buyer intent across LinkedIn, X/Twitter, Reddit, and G2, and you build AI-powered systems that detect these patterns at scale without a full-time social media team.

CONTEXT:
- Company: [Company Name]
- Product: [One-sentence description of what you sell and who benefits]
- Primary ICP: [Title/Seniority, Company size, Industry vertical(s), Geography]
- ACV: [Average contract value — determines how much sales effort per signal is justified]
- Sales motion: [Self-serve / Sales-assisted / Enterprise — determines engagement protocol]
- Top 3 competitors: [Name each; specify what customers complain about most on G2/Reddit]
- Category pain points: [List the 3-5 core pain statements your ICP makes about the problem you solve]
- Current social monitoring: [What you currently do — none, manual Google Alerts, tool-based]
- CRM: [Salesforce / HubSpot / Pipedrive / Other]
- Team capacity: [Who will handle signal engagement — SDR team, marketing, founder]
- Tool budget: [Monthly budget available for monitoring/enrichment tools]
- Top social platforms your ICP uses: [LinkedIn / X/Twitter / Reddit / other]
- Key industry communities: [Slack groups, Discord servers, forums your ICP frequents]

OBJECTIVE: Design a production-ready organic social intelligence and demand activation system that:
1. Detects 50-200 high-confidence buying signals per month across monitored platforms
2. Qualifies signals to 15-25% precision (Tier 1 + Tier 2 combined) to focus sales effort on real opportunities
3. Converts 8-15% of engaged social signals into booked meetings through authentic, non-spammy outreach
4. Routes qualified signals to CRM within 2 hours of detection to maximize speed-to-lead advantage over competitors
5. Generates attributable pipeline of $200K-$2M+ annually depending on ACV and market size
6. Operates with 3-5 hours/week of human effort via AI-powered automation of signal detection, enrichment, and routing

CONSTRAINTS:
- No scraping that violates platform Terms of Service (LinkedIn forbids automated scraping without API access; use LinkedIn Sales Navigator + Clay instead)
- No mass DM blasting — every outreach must feel personalized and contextually relevant to the specific signal
- All engagement must be authentic — if you can't genuinely add value to the conversation, don't engage
- Signal response time standards: Tier 1 signals must be engaged within 2 hours; X/Twitter and Reddit conversations have a 6-hour half-life after which engagement feels late
- Privacy compliance: GDPR/CCPA-compliant signal capture and storage — no storing personal social data beyond what's needed for sales qualification

OUTPUT FORMAT — Produce the following deliverables in sequence:

**DELIVERABLE 1: Signal Library & Trigger Taxonomy**
Create a comprehensive signal detection database with:
- 50+ specific search strings organized by signal type (competitor complaint, category intent, pain point, trigger event)
- Platform-specific formatting for each string (LinkedIn boolean, X/Twitter advanced search, Reddit search, Google Alert syntax)
- Signal priority tier assignment for each string type
- False positive exclusion filters (keywords, account types, context patterns to exclude)
- Signal freshness guidelines: which signals are still valid at 2 hours, 6 hours, 24 hours, 72 hours

**DELIVERABLE 2: Platform Monitoring Setup Guide**
Step-by-step configuration for each monitored platform:
- LinkedIn Sales Navigator: 5-8 account/lead alert configurations with exact boolean strings; Company Insights setup for target account trigger monitoring
- X/Twitter: TweetDeck/HootSuite column setup, advanced search operators, Twitter List curation (whose followers to monitor), Mention.com alert configuration
- Reddit: 10-15 specific subreddits with monitoring rationale; PRAW/Reddit search API integration guide for automated monitoring; upvote/comment threshold guidelines for signal qualification
- G2/Capterra/TrustRadius: New review notification setup, specific competitor review monitoring, alert cadence configuration
- Industry communities: Which Slack/Discord/forum communities to join, keyword alert bot configuration, engagement protocol guidelines

**DELIVERABLE 3: AI Signal Qualification Engine**
Design the automated qualification workflow:
- Signal scoring rubric: 10-point matrix covering intent clarity (0-3), ICP fit (0-3), urgency signals (0-2), buying committee seniority (0-2)
- Clay workflow architecture: webhook trigger → person enrichment → company enrichment → ICP scoring → tier classification → CRM push
- AI classification prompt templates: prompts to feed into GPT-4/Claude to classify signal intent and extract key information from social post text
- Enrichment data fields to capture: company size, funding stage, tech stack (from Clearbit/BuiltWith), LinkedIn headcount growth rate, recent press mentions
- Disqualification logic: what automatically disqualifies a signal regardless of score (competitor employee, existing customer, wrong industry, wrong company size)
- Tier routing rules: exact criteria for Tier 1 (immediate sales alert), Tier 2 (automated nurture enrollment), Tier 3 (log only)

**DELIVERABLE 4: Engagement Playbook**
Response scripts and protocols for each signal scenario:
- Scenario A (Competitor complaint — public post): Response strategy + 3 example comment scripts that add genuine value without pitching; transition to DM criteria and timing
- Scenario B (Category question — "recommendations for X software"): Full answer framework + example response that naturally positions your product through helpfulness, not promotion
- Scenario C (Pain point discussion — no vendor mentioned): Comment engagement approach + example scripts that establish expertise and create natural follow-up opportunity
- Scenario D (Trigger event — new job, funding, expansion post): Congratulatory engagement + subtle value bridge + DM sequence trigger criteria
- DM sequence templates (per scenario): 3-message sequences with day intervals, personalization variables, and fallback if no reply
- Engagement velocity rules: how many signals to engage per day per platform to avoid triggering platform spam filters; optimal posting windows for fastest response

**DELIVERABLE 5: Automation Stack & Integration Architecture**
Technical implementation blueprint:
- Tool stack recommendation with pricing: Mention.com/Brand24 (monitoring), Clay (enrichment + routing), Zapier/Make (automation chains), LinkedIn Sales Navigator (LinkedIn signals), HubSpot/Salesforce (CRM logging)
- Zapier/Make automation chain diagrams for each signal type: trigger → webhook → Clay → CRM → Slack alert
- CRM field mapping: custom fields to create for "Signal Source," "Signal Type," "Signal Date," "Signal Score," "Engagement Method," "Social Response Rate"
- Slack alert template: what information appears in the real-time Slack notification to sales reps (prospect name, company, signal text, ICP score, recommended response, one-click CRM link)
- Deduplication logic: how to prevent the same prospect from being alerted on multiple times from different signals
- Weekly automated digest: what data to surface in the weekly social intelligence report (auto-generated from CRM data)

**DELIVERABLE 6: 90-Day Implementation Roadmap**
Week-by-week execution plan:
- Days 1-14: Foundation — signal library creation, platform monitoring setup, tool configuration, CRM field setup
- Days 15-30: Calibration — first 100 signals reviewed manually to calibrate scoring model, engagement scripts tested on Tier 1 signals, first pipeline opportunities identified
- Days 31-60: Automation — Clay + Zapier workflows deployed, Slack routing live, sales team trained on social signal engagement protocol, first attribution data visible in CRM
- Days 61-90: Optimization — scoring model refined based on conversion data, highest-converting signal types scaled, lowest-converting deprioritized, monthly pipeline contribution report to CMO/CRO
- Expected metrics at 30/60/90 days: signals detected per week, Tier 1 qualification rate, engagement response rate, meetings booked, pipeline generated

## Example Input/Output

**Input Example:**

Company: Rootstock Data
Product: AI-powered data quality monitoring platform for data engineering teams at Series B+ SaaS companies
ICP: Head of Data, VP Engineering, Data Engineering Manager at 200-2,000 person SaaS companies using dbt, Snowflake, or Databricks
ACV: $72,000/year
Sales motion: Sales-assisted (AE-led, 60-day average cycle)
Top competitors: Monte Carlo Data, Soda, Great Expectations
Competitor complaints on G2/Reddit: Monte Carlo pricing is opaque and scales poorly; Soda has poor documentation; Great Expectations requires too much custom engineering
Core pain points ICP expresses: "Silent data failures that only surface when a dashboard breaks," "Spending more time fixing data quality issues than building pipelines," "Can't prove data quality to the business stakeholders"
Team: 2 SDRs + 1 marketing manager available for social engagement
Tool budget: $800/month
ICP platforms: LinkedIn (primary), X/Twitter (secondary), Reddit (r/dataengineering, r/AnalyticsEngineers, r/dbt)

**Output Example (abbreviated):**

**Signal Library — Competitor Complaint Signals (Monte Carlo):**

LinkedIn boolean: `("Monte Carlo" OR "MCD") AND ("pricing" OR "expensive" OR "contract" OR "renewal" OR "switching" OR "alternative" OR "frustrated")`
X/Twitter advanced: `"Monte Carlo" (pricing OR contract OR expensive OR switching OR alternative) -filter:retweets`
Reddit search: `site:reddit.com "Monte Carlo" AND ("expensive" OR "pricing" OR "switching" OR "alternative to") subreddit:dataengineering`
G2 alert: New reviews for Monte Carlo mentioning "price," "cost," "switching," "contract," "expensive" — email alert via G2 Buyer Intent

Tier Assignment: Tier 1 if poster is Head of Data / VP Eng / Data Manager at 200-2,000 person company; Tier 2 if poster is senior IC (data engineer, analytics engineer) at same-size company; Tier 3 all others.

**Signal Example — Real Reddit Thread:**

Detected: r/dataengineering — "Monte Carlo renewal came in 40% higher. Anyone moved to alternatives recently?" — 47 upvotes, 23 comments, posted 3 hours ago. Poster is "u/dan_datainfra" — LinkedIn matched to Daniel Voss, Head of Data Infrastructure, Clearbit AI (Series B, 380 employees, dbt + Snowflake stack per BuiltWith). ICP score: 9/10.

**Routing Action:**
- Slack alert fired to SDR assigned to Clearbit AI territory within 8 minutes of detection
- CRM contact created: Daniel Voss, tagged "Social Signal — Competitor Complaint — Monte Carlo Renewal"
- Suggested engagement: Join the Reddit thread with a genuinely helpful comparison comment (example below), do NOT mention Rootstock in first touch

**Engagement Script — Reddit Comment (Scenario A):**

"Seen this pattern a lot lately — Monte Carlo's pricing tends to spike at renewal once you're deep enough in their data asset catalog that switching feels painful. A few things worth comparing before renewal:

1. Asset-based vs. table-based pricing: if your data model count is growing, asset-based models get expensive fast
2. How the platform handles dbt model lineage specifically (this matters a lot if you're dbt-heavy)
3. What migration complexity actually looks like — most vendors understate this in their pitch

Happy to share what teams in similar situations have evaluated if useful — drop a DM or I can link some comparison resources in a follow-up comment."

[24 hours later, if no DM received, SDR sends LinkedIn connection request to Daniel Voss with note: "Saw your thread on r/dataengineering about Monte Carlo renewal — I shared a comment there and had a few more thoughts if useful. Worth connecting."]

**DM Sequence (if LinkedIn connection accepted):**

Message 1 (Day 1): "Hey Daniel — appreciate you accepting. The Monte Carlo renewal question on Reddit resonated because I've seen a lot of data teams hit the same inflection point at your scale. Curious — are you evaluating alternatives actively or more trying to negotiate the renewal down?"

Message 2 (Day 5, if no reply): "No rush at all — if you're still in renewal mode, I put together a quick comparison framework for dbt-heavy teams choosing between Monte Carlo, Soda, and a few others. Want me to drop the link?"

Message 3 (Day 10, if no reply): "Last note — if the timing's off, no worries. If you ever want to compare notes on what data quality monitoring actually looks like at your data stack scale (saw you're on Snowflake + dbt from your profile), I'm happy to share what teams similar to Clearbit AI have found. Leaving the door open."

**Week 1 Metrics Targets:**
- Signals detected: 40-60 (across LinkedIn, X/Twitter, Reddit, G2)
- Tier 1 signals: 5-8
- Engagements initiated: 4-6
- LinkedIn connections accepted: 2-3
- DMs sent: 3-5
- Meetings booked from social signals: 0-1 (pipeline generation typically lags engagement by 10-14 days)

**90-Day Pipeline Projection:**
- Month 1: 180 signals detected, 22 qualified (Tier 1+2), 12 engaged, 3 meetings booked, $72K pipeline created
- Month 2: 220 signals detected (monitoring expanded), 35 qualified, 20 engaged, 7 meetings booked, $252K pipeline created
- Month 3: 260 signals, 45 qualified, 28 engaged, 11 meetings booked, $504K pipeline created
- Q1 total: ~$828K in social-signal-sourced pipeline on $800/month tool spend + ~12 hours/week team time

## Success Metrics

**Signal Detection Quality:**
- Signals detected per week per platform (LinkedIn, X/Twitter, Reddit, G2 — track separately)
- Signal-to-qualified ratio: what percentage of detected signals pass ICP + intent scoring (target: 15-25%)
- False positive rate: signals that reach Tier 1 routing but turn out to be non-ICP or non-buyers (target: <20%)
- Signal freshness: what percentage of Tier 1 signals are engaged within 2-hour SLA

**Engagement Performance:**
- Comment/response rate from public engagement: what percentage of posts you engage with result in DMs or profile visits
- LinkedIn connection acceptance rate for signal-sourced requests (target: 35-55% for personalized notes vs. cold)
- DM reply rate: what percentage of signal-triggered DMs receive a response (target: 20-35%)
- Meeting booking rate from social signal pipeline: signals → meeting booked conversion (target: 8-15%)

**Pipeline & Revenue:**
- Social signal-sourced MQLs per month (logged in CRM as "Social Signal" lead source)
- Pipeline created from social signal leads (track in CRM opportunity source field)
- Win rate from social signal opportunities vs. other sources (hypothesis: social signal leads close at higher rates due to pre-warmed context)
- Cost per opportunity: tool spend + team hours cost vs. pipeline generated (target: <10% of average ACV)

**Competitive Intelligence Value:**
- Competitor complaint signals captured per month by competitor (tracks market dissatisfaction trends)
- Response speed vs. competitors (are you engaging competitor complaints before competitors notice?)
- Win rate in competitive deals where social signal preceded outreach vs. cold outreach to same accounts

## Related Prompts

- [AI-Powered B2B SaaS LinkedIn Organic Demand Generation & Dark Social Pipeline Revenue Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Social-Media-Marketing/AI-Powered-B2B-SaaS-LinkedIn-Organic-Demand-Generation-&-Dark-Social-Pipeline-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS X/Twitter Organic Demand Generation & Thought Leader Pipeline Revenue Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Social-Media-Marketing/AI-Powered-B2B-SaaS-X-Twitter-Organic-Demand-Generation-&-Thought-Leader-Pipeline-Revenue-Intelligence-Engine.md)
- [Real-Time Competitive Monitoring & Market Signal Intelligence Engine](../../05_Analytics-&-Performance/Competitive-Intelligence-Analytics/Real-Time-Competitive-Monitoring-&-Market-Signal-Intelligence-Engine.md)
- [AI-Powered B2B Real-Time Social Listening Intelligence & Buyer Signal Revenue Activation Engine](../../05_Analytics-&-Performance/Brand-Health-&-Sentiment-Analytics/AI-Powered-B2B-Real-Time-Social-Listening-Intelligence-&-Buyer-Signal-Revenue-Activation-Engine.md)

## Integration Tips

**HubSpot:**
- Create a custom Contact property: "Social Signal Source" (dropdown: LinkedIn, X/Twitter, Reddit, G2, Community) and "Social Signal Type" (Competitor Complaint, Category Intent, Pain Point, Trigger Event)
- Build a HubSpot Workflow: when "Social Signal Source" is set → enroll in social signal nurture sequence → assign to owner → create task for 2-hour engagement SLA
- Build a Social Signal pipeline report: contacts by signal source, MQLs from social signals, pipeline value by signal type — present monthly in marketing<>sales sync

**Salesforce:**
- Create custom Lead and Contact fields: Social_Signal_Source__c, Social_Signal_Date__c, Social_Signal_Score__c, Social_Signal_Platform__c
- Build a Salesforce Report: "Social Signal Pipeline" showing opportunities where Social_Signal_Source is populated — track pipeline stage distribution and win rates vs. other sources
- Campaign object: create one Campaign per quarter called "Social Signal Q1 2026" to capture all social-signal-influenced pipeline for board reporting

**Clay:**
- Build a Clay Table: Webhook receiver → Person enrichment (Clearbit) → Company enrichment (Clearbit/Apollo) → ICP Score formula column → Tier assignment formula → HubSpot/Salesforce push action
- Use Clay's "AI column" to run a GPT-4 classification on the raw signal text: prompt = "Given this social media post: [post text], on a scale of 1-10, how clearly does this indicate an active search for software in the [your category] space? Explain your reasoning in one sentence."
- Clay enrichment stack: Clearbit for firmographics + BuiltWith for tech stack + LinkedIn for seniority/title confirmation + Apollo for verified email

**Slack:**
- Create a #social-signals Slack channel; configure Zapier to post a rich Slack message for every Tier 1 signal including: prospect name, title, company, signal text, platform, ICP score, recommended action, direct CRM link
- For Tier 2: weekly digest to #marketing-signals with full signal list + metrics summary
- Add emoji reaction system: sales reps react with ✅ when engaged, 📅 when meeting booked, ❌ when disqualified — this feeds back to signal quality reporting without manual data entry

**Mention.com / Brand24:**
- Set up Brand Alerts for: your brand name, your top 3 competitors, your category keywords, top 10 pain point phrases from your signal library
- Configure sentiment filtering: automatically flag negative sentiment mentions of competitors as Tier 1 candidates
- Export weekly signal reports to Google Sheets for trend analysis

**PRAW (Reddit API) + Python:**
- Use PRAW library to monitor 10-15 target subreddits for keyword matches in real time; configure signal scoring function based on post flair, upvote count, subreddit size, and keyword match strength; push matches to Clay webhook for enrichment

## Troubleshooting

**Problem: High false positive rate — most detected signals are from researchers, students, or existing customers, not true buyers**
Solution: Tighten the ICP qualification filter at the enrichment step before routing. Add mandatory ICP criteria to the Clay workflow: if company headcount < 100 OR company headcount > 5,000 (outside your ICP range) OR domain matches existing customer list → auto-disqualify regardless of signal score. Also add negative keyword filters to your monitoring strings: exclude "homework," "research paper," "academic," "internship," "student," "I work at [Your Company]" to reduce noise at the detection layer.

**Problem: Engagement feels intrusive — prospects are noticing the same company keeps appearing in their conversations across platforms**
Solution: Enforce a cross-platform engagement cap: no more than 2 touchpoints to the same prospect across all channels within a 30-day window. Track this in your CRM. Also audit your engagement copy — if your comments always reference the problem you solve, you're being too obvious. True social intelligence engagement adds value first: answer the question helpfully, share a resource, ask a clarifying question. The company pitch comes later, in DMs, only when the prospect opens the door.

**Problem: Signal volume is high but meeting conversion rate is below 5%**
Solution: The issue is almost always score calibration — your Tier 1 signals include too many low-intent signals. Run a retroactive analysis of your last 90 days: for every signal that converted to a meeting, what was its original score? For every signal that didn't, what was its score? Recalibrate the tier thresholds based on this data. Typically, this reveals that "competitor complaint" signals from senior titles convert at 3x the rate of "category question" signals from ICs — reallocate sales engagement time toward the higher-converting signal types.

## Version History
- v1.0: Initial creation (auto-generated)
