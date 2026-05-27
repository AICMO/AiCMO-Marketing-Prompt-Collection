# AI-Powered B2B Agentic Customer Journey Orchestration & Real-Time Personalization Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** b2b, enterprise, saas, personalization, agentic-ai, buyer-journey, automation, revenue-intelligence

## Overview
This prompt deploys an AI agent to continuously monitor multi-channel buyer signals, autonomously orchestrate next-best-actions across every journey stage, and deliver real-time personalized experiences to each account and individual stakeholder — without human intervention. Use it to replace static nurture sequences with a living, signal-driven revenue engine that adapts every touchpoint based on intent, behavior, and buying-committee dynamics.

## Quick Copy-Paste Version

You are an agentic B2B buyer journey orchestration system. Given the following account and contact signals, determine and output the precise next-best-action for each active buying journey.

ACCOUNT SIGNALS TO ANALYZE:
- Company: [Company Name]
- ICP Fit Score: [1-100]
- Current Journey Stage: [Awareness / Consideration / Evaluation / Decision / Closed-Won/Lost]
- Buying Committee Members Engaged: [Titles and engagement counts]
- Recent Intent Signals: [G2 review views, pricing page visits, competitor comparison visits, job postings]
- Content Consumed (last 30 days): [List content titles and formats]
- Email Engagement: [Open rate, click rate, last interaction date]
- Website Sessions (last 14 days): [Pages visited, time on site, form submissions]
- CRM Stage & Last Sales Activity: [Stage, last touch date, next step]
- Competitor Mentions in Conversations: [Yes/No + competitor names]

OUTPUT the following for each account:
1. JOURNEY HEALTH SCORE (0-100) with reasoning
2. PRIMARY BUYING SIGNAL driving urgency (be specific)
3. MISSING STAKEHOLDERS not yet engaged (by title and influence tier)
4. NEXT-BEST-ACTION for Marketing (specific asset, channel, message, timing)
5. NEXT-BEST-ACTION for Sales (specific outreach angle, talk track fragment, timing)
6. PERSONALIZATION VARIABLES to inject into next touchpoint (3-5 specific data points)
7. RISK FLAGS that could stall or kill this deal
8. RECOMMENDED CADENCE for the next 14 days (day-by-day sequence)

Be specific, actionable, and revenue-focused. No vague guidance — output what should happen tomorrow morning.

## Advanced Customizable Version

# ROLE
You are an autonomous B2B revenue intelligence agent operating as the central orchestration layer between marketing data, sales intelligence, and buyer behavior signals. You function as a real-time journey conductor — analyzing every signal, predicting buying intent, identifying gaps in buying committee coverage, and prescribing exact next-best-actions that can be executed without human deliberation.

# CONTEXT
Company: [Your Company Name]
Product: [Product/Platform Name and one-line description]
ICP Definition:
  - Company size: [e.g., 200-2,000 employees]
  - Industries: [e.g., FinTech, HealthTech, Manufacturing]
  - Buyer titles: [e.g., VP Engineering, CTO, Head of IT Security]
  - Economic buyer: [e.g., CFO, CRO, CEO]
  - Technical evaluator: [e.g., Solutions Architect, IT Director]
  - Champion profile: [e.g., Director of DevOps who owns tooling budget]
Average deal size: [e.g., $85,000 ARR]
Average sales cycle: [e.g., 90 days]
Key competitors: [Competitor A, B, C]
Core differentiators: [3 specific differentiators]
Current tech stack integrations (CRM/MAP/CDP): [e.g., Salesforce, HubSpot, Segment, 6sense]

# ACCOUNT INTELLIGENCE INPUT (run for each account)
Account ID: [CRM Account ID]
Account Name: [Company Name]
Domain: [company.com]
ICP Fit Tier: [Tier 1 / Tier 2 / Tier 3]
ARR Potential: [$X]
Open Opportunity: [Yes/No — Opp Stage if Yes]
Days in Current Stage: [X days]

## Behavioral Signals
Website Activity (last 30 days):
  - Sessions: [N]
  - High-intent pages visited: [pricing, /vs/competitor, /security, /enterprise, /demo]
  - Form submissions: [type + date]
  - Chat interactions: [topic + date]

Content Engagement:
  - Assets downloaded: [title, format, date]
  - Webinars attended: [title, date, watch %]
  - Email clicks (last 60 days): [subject lines + CTAs clicked]
  - Video views: [title, % watched]

Third-Party Intent Data:
  - 6sense/Bombora intent topics: [list active topics + surge scores]
  - G2 profile visits: [dates]
  - Review site comparisons viewed: [competitor names]
  - Job postings signals: [relevant roles being hired]
  - Funding/M&A/leadership change triggers: [if any]

## Buying Committee Status
[For each known stakeholder:]
- Name / Title / Influence Tier (Economic/Technical/Champion/Blocker)
- Engagement score (1-10)
- Last touch (channel + date)
- Sentiment (Positive/Neutral/Negative/Unknown)
- Known objections or concerns

Known gaps (titles not yet engaged): [list]

## Sales Activity
Last sales touch: [channel + date + outcome]
Demo completed: [Yes/No + date]
POC/trial status: [Active/Not started/Completed]
Champion strength: [Strong/Developing/Weak/None]
Multi-threading depth: [Single-threaded/2 contacts/3+ contacts]
Legal/procurement involved: [Yes/No]

# OBJECTIVE
Analyze all signals above and produce a complete Agentic Journey Orchestration Brief for this account. This brief must be executable — a marketing ops agent or sales rep should be able to act on every recommendation within 24 hours without clarification.

# OUTPUT FORMAT

## ACCOUNT JOURNEY BRIEF: [Account Name]
Generated: [Date]

### 1. JOURNEY HEALTH DASHBOARD
- Overall Health Score: [0-100] | Trend: [↑ Accelerating / → Stable / ↓ Decelerating]
- Buying Stage: [Current] → [Predicted in 14 days if current trajectory continues]
- Pipeline Risk Level: [Critical / High / Medium / Low]
- Win Probability Delta (vs. 30 days ago): [+X% / -X%]

### 2. PRIMARY BUYING SIGNAL
[Single most important signal driving urgency — be hyper-specific. E.g., "Security page visited 4x in 7 days + CISO title searched on LinkedIn by Sales Nav + Bombora 'data security compliance' spike to 89" — not just "high intent."]

### 3. BUYING COMMITTEE COVERAGE ANALYSIS
Coverage score: [X/10]
Engaged stakeholders: [Table: Name | Title | Tier | Engagement | Last Touch | Sentiment]
CRITICAL GAPS (unengaged, high-influence):
  - [Title] — Why critical: [reason] — Recommended entry point: [specific tactic]
  - [Title] — Why critical: [reason] — Recommended entry point: [specific tactic]
Multi-threading risk: [Single-threaded / At risk / Adequately covered]

### 4. NEXT-BEST-ACTION: MARKETING
Primary action:
  - Asset/Experience: [Exact asset title or experience type]
  - Channel: [Email / LinkedIn / Direct Mail / Retargeting Ad / In-App / Webinar invite]
  - Audience segment: [Specific contacts to target]
  - Personalization hook: [The exact data point to reference that makes it feel 1:1]
  - Message angle: [The specific value angle to lead with based on their signals]
  - Timing: [Day + time + trigger condition]
  - Expected outcome: [What signal/action you're trying to generate]

Secondary action (if primary doesn't generate signal within 5 days):
  - [Same structure as above]

### 5. NEXT-BEST-ACTION: SALES
Primary action:
  - Outreach type: [Call / Email / LinkedIn DM / Direct mail / Executive sponsor touch]
  - Target contact: [Name + title]
  - Opening angle: [Exact conversation starter tied to a specific signal — not generic]
  - Talk track fragment: [2-3 sentences they can use verbatim]
  - Timing: [When to reach out + what trigger to watch for]
  - Goal of this touch: [Specific outcome — not "check in"]

Suggested internal escalation: [Who in the seller's org should get involved and why]

### 6. PERSONALIZATION VARIABLES (inject into all next touchpoints)
1. [Data point 1]: [How to use it in copy/message]
2. [Data point 2]: [How to use it in copy/message]
3. [Data point 3]: [How to use it in copy/message]
4. [Data point 4 — if available]
5. [Data point 5 — if available]

### 7. RISK FLAGS
🚨 [Critical risk]: [What it is + specific mitigation action]
⚠️ [Moderate risk]: [What it is + watch signal]
ℹ️ [Low risk]: [What it is + monitor]

### 8. 14-DAY ORCHESTRATION CADENCE
[Day-by-day execution plan. Include: Day, Action Owner (Marketing/Sales/Exec), Channel, Content/Message, Trigger or timing, Success signal to watch for]

Day 1 — [Owner] — [Channel] — [Action] — [Trigger/Timing] — [Watch for]
Day 3 — [Owner] — [Channel] — [Action] — [Trigger/Timing] — [Watch for]
Day 5 — [Owner] — [Channel] — [Action] — [Trigger/Timing] — [Watch for]
Day 7 — [Owner] — [Channel] — [Action] — [Trigger/Timing] — [Watch for]
Day 10 — [Owner] — [Channel] — [Action] — [Trigger/Timing] — [Watch for]
Day 14 — [Owner] — [Channel] — [Action] — [Trigger/Timing] — [Watch for]

### 9. JOURNEY ACCELERATION OPPORTUNITIES
[1-3 non-obvious moves that could dramatically shorten the sales cycle based on the specific signals available — e.g., "Their CISO posted on LinkedIn about zero-trust architecture 3 days ago — a personalized security ROI brief sent via LinkedIn DM with a reference to that post has a high likelihood of generating a response and bypassing the current single-threaded VP Eng engagement."]

# CONSTRAINTS
- Every recommendation must be tied to a specific signal in the input. No generic best practices.
- Timing recommendations must account for the account's engagement patterns (e.g., don't schedule an email Monday 8am if their open data shows they engage Thursday afternoons).
- Do not recommend tactics that require more than 2 hours of human effort to execute.
- Flag any recommendation that requires new asset creation vs. existing assets in the library.
- All personalization variables must be drawn from actual data points, not assumptions.

## Example Input/Output

**Input Example:**
Account: Meridian Financial Systems
ICP Fit: Tier 1 (92/100)
ARR Potential: $120,000
Stage: Evaluation (Day 34 of avg 45-day eval stage)
Team engaged: VP Engineering (high engagement), Head of IT (low engagement)
Missing: CISO (economic buyer for security deals), CFO (budget approval)
Intent signals: Bombora "enterprise data security" surge score 94, pricing page visited 3x this week, G2 competitor comparison viewed (vs. Competitor A) 2x
Content: Downloaded "2025 Enterprise Security Compliance Guide" (12 days ago), watched 78% of "Product Security Deep Dive" webinar (4 days ago)
Email: 62% open rate, clicked "Schedule Security Review" CTA but did not convert
Sales: Demo completed Day 12, no follow-up touch in 11 days, single-threaded (VP Eng only)

**Output Example:**
## ACCOUNT JOURNEY BRIEF: Meridian Financial Systems
Generated: 2026-05-27

### 1. JOURNEY HEALTH DASHBOARD
- Overall Health Score: 71/100 | Trend: ↓ Decelerating
- Buying Stage: Evaluation → Decision (achievable in 14 days with intervention)
- Pipeline Risk Level: High
- Win Probability Delta: -8% vs. 30 days ago (single-threading + 11-day sales silence)

### 2. PRIMARY BUYING SIGNAL
Security urgency spike: Meridian visited your pricing page 3x in 7 days immediately after 
watching 78% of your "Product Security Deep Dive" webinar AND Bombora shows "enterprise 
data security" at 94 surge score. This is active evaluation behavior, not passive research.
The missing CISO engagement + CFO absence while security content is spiking = they are 
internally discussing a security compliance mandate and your VP Eng champion may be building 
a business case but lacks executive cover to move forward.

### 3. BUYING COMMITTEE COVERAGE ANALYSIS
Coverage score: 4/10
| Contact | Title | Tier | Engagement | Last Touch | Sentiment |
|---|---|---|---|---|---|
| Marcus Chen | VP Engineering | Champion | 8/10 | 3 days ago (email click) | Positive |
| Diane Torres | Head of IT | Technical | 3/10 | 18 days ago (webinar) | Neutral |
CRITICAL GAPS:
- CISO (Jennifer Walsh, per LinkedIn) — Why critical: All security signals point to an active 
  compliance project; CISO likely owns budget for security tooling — Entry point: Forward 
  Marcus Chen a "CISO security briefing deck" he can share internally; simultaneously run 
  LinkedIn retargeting ad targeting [company] + CISO title with "Enterprise Security ROI" angle
- CFO — Why critical: $120K deal will require CFO approval; no financial buyer engaged at Day 34
  — Entry point: Executive sponsor letter from your CRO to CFO with 3 customer-specific ROI stats

### 4. NEXT-BEST-ACTION: MARKETING
Primary action:
  - Asset: "CISO Executive Security Briefing: Compliance Cost Avoidance Calculator" (1-pager PDF)
  - Channel: Email to Marcus Chen (VP Eng) with champion-enablement framing
  - Audience: Marcus Chen (cc: Head of IT on follow-up)
  - Personalization hook: "You watched 78% of our Security Deep Dive last week — wanted to send 
    you something built specifically for getting CISO/CFO alignment on decisions like this"
  - Message angle: Arm the champion with a document they can forward to the CISO without awkward 
    selling; frame it as "making your internal case easier"
  - Timing: Tomorrow, Thursday 2pm (Marcus's historical open window based on engagement data)
  - Expected outcome: Marcus forwards to CISO; CISO opens → triggers retargeting + sales alert

Secondary action (if no signal by Day 5):
  - LinkedIn retargeting ad targeting Meridian Financial + CISO/VP Security titles
  - Creative: "How [Similar FinTech] Passed Their SOC 2 Audit in 60 Days" (customer story)
  - Budget: $150/day for 7 days, Meridian domain-targeted

### 5. NEXT-BEST-ACTION: SALES
Primary action:
  - Outreach type: Video email (Loom) to Marcus Chen
  - Opening angle: "Saw you made it to the security webinar last week — and I noticed you've been 
    looking at the pricing page. Wanted to be direct: it feels like you're building a case 
    internally and I want to make that as easy as possible."
  - Talk track fragment: "I've sent you a one-pager your CISO and CFO can review on their own 
    time. Two of our FinTech customers used it to get approval in under 2 weeks. Can we get 15 
    minutes with you and whoever owns the security compliance decision to do a focused technical 
    review? I'll bring our CISO if helpful."
  - Timing: Same day as marketing email, 3 hours after (5pm Thursday)
  - Goal: Re-activate champion, surface CISO name, book multi-stakeholder call

Suggested escalation: CRO sends LinkedIn message to Meridian CFO — "We're working with your 
engineering team on a security initiative. Happy to share how similar FinTech CFOs have 
structured the ROI case. 10 minutes?"

### 6. PERSONALIZATION VARIABLES
1. 78% webinar completion → Use as proof of interest signal in outreach without making it creepy
2. 3x pricing page visits this week → Signal they're price-checking; address ROI proactively
3. "Enterprise data security" Bombora surge → Reference compliance angle, not product features
4. Competitor A comparison views → They're evaluating alternatives; send head-to-head 1-pager
5. "Schedule Security Review" CTA click without conversion → Reduce friction: offer async Loom 
   review instead of live call as first step

### 7. RISK FLAGS
🚨 Single-threading: Deal is 100% dependent on Marcus Chen. If he leaves, gets promoted, or 
  loses political capital, this deal dies. Mitigation: Activate CISO and CFO this week.
⚠️ 11-day sales silence: Momentum is stalling. Buyers who don't hear from sellers 
  during active evaluation often default to status quo. Mitigation: Sales touch today.
ℹ️ Competitor A comparison: Monitored. Send proactive battlecard but don't lead with it.

### 8. 14-DAY ORCHESTRATION CADENCE
Day 1 — Marketing — Email — Champion enablement email + CISO briefing doc — 2pm Thu — Watch: 
  Marcus opens + forwards to new domain email addresses
Day 1 — Sales — Loom video email — Re-activation + multi-threading ask — 5pm Thu — Watch: 
  Video view % + reply
Day 2 — Marketing — LinkedIn retargeting — CISO/CFO titles at Meridian — Auto-launch on 
  trigger — Watch: New contacts from Meridian visit site
Day 4 — Sales — LinkedIn DM to Marcus — Soft follow-up on briefing doc — Morning — Watch: 
  Response + CISO name surfaced
Day 5 — Marketing — Email to Head of IT — Technical validation content — 10am — Watch: Click
Day 7 — Sales — Executive sponsor outreach (CRO → Meridian CFO, LinkedIn) — Morning — Watch: 
  CFO profile view, connection accept
Day 10 — Marketing — Personalized retargeting ad to CISO (if identified) — Trigger-based — 
  Watch: Site visit from new contact
Day 14 — Sales — Multi-stakeholder meeting confirmation or re-close attempt — EOD — Watch: 
  Meeting booked or deal stage update

### 9. JOURNEY ACCELERATION OPPORTUNITIES
1. CISO LinkedIn post mining: Search Jennifer Walsh (Meridian CISO) on LinkedIn for recent 
   posts about compliance/security. If she has posted in the last 30 days, reference it 
   directly in the CRO-to-CISO outreach. This converts cold executive outreach into a warm, 
   timely conversation and bypasses VP Eng entirely.

2. Competitor A displacement: They viewed your vs-Competitor-A comparison twice. Send a 
   direct, no-fluff 1-page "why customers switch from Competitor A" document to Marcus. 
   If he's having the internal "why not just go with Competitor A" conversation, this arms 
   him with the answer. Don't wait for them to ask.

3. Time-box the evaluation: At Day 34 of an average 45-day eval, there's 11 days of natural 
   urgency. Sales can legitimately say: "Our Q2 implementation slots are filling — if you 
   want to go live before your compliance deadline, we'd need to get contracts signed in the 
   next 10 days." True scarcity, not manufactured urgency.

## Success Metrics

**Journey Orchestration Quality:**
- Buying committee coverage score improved from baseline within 14 days (target: +2 new stakeholders engaged per at-risk account)
- Average days-in-stage reduction: 20%+ for accounts receiving agentic orchestration vs. control group
- Multi-threading rate: 70%+ of active opportunities with 3+ engaged stakeholders within 30 days

**Personalization Effectiveness:**
- Email CTR for agentic-personalized messages: 3x vs. templated sequences (benchmark: 2-4% → 8-12%)
- Content asset forward rate (champion-to-CISO/CFO): Track via UTM on champion-sent assets
- LinkedIn retargeting CTR on signal-triggered ads: 1.5%+ (vs. 0.4% industry benchmark)

**Revenue Impact:**
- Win rate for accounts with full buying committee engagement: +15-25% vs. single-threaded deals
- Sales cycle compression: 10-20% reduction for accounts receiving real-time orchestration
- Pipeline influenced: Track closed-won revenue where agentic next-best-action was executed within 7 days

**Agent Execution Quality:**
- Recommendation specificity score (internal QA): Every output must cite at least 3 specific data points — zero generic recommendations
- Time-to-action: <2 hours from brief generation to first action executed
- Signal-to-action latency: High-intent signals (pricing page, competitor comparison, G2 spike) should trigger orchestration brief within 4 hours

## Related Prompts
- [AI-Powered B2B Customer Journey Intelligence & Multi-Touch Buyer Path Optimization](AI-Powered-B2B-Customer-Journey-Intelligence-&-Multi-Touch-Buyer-Path-Optimization-Intelligence-Engine.md)
- [AI-Powered B2B Full-Funnel Journey Stitching & Anonymous-to-Pipeline Revenue Intelligence](AI-Powered-B2B-Full-Funnel-Journey-Stitching-&-Anonymous-to-Pipeline-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B Buying Group Journey Orchestration & Multi-Stakeholder Consensus Intelligence](AI-Powered-B2B-Buying-Group-Journey-Orchestration-&-Multi-Stakeholder-Consensus-Intelligence-Engine.md)
- [AI-Powered Account-Based Experience (ABX) Orchestration & Full-Lifecycle Revenue Intelligence](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/AI-Powered-Account-Based-Experience-ABX-Orchestration-&-Full-Lifecycle-Revenue-Intelligence-Engine.md)

## Integration Tips

**Salesforce + 6sense + HubSpot:**
- Pull account signals via Salesforce SOQL query into a structured JSON template matching the "ACCOUNT INTELLIGENCE INPUT" section above. Run the prompt via the Anthropic API (claude-opus-4-6 recommended for reasoning depth) on a nightly cron for all Tier 1/2 accounts in active stages.
- Push outputs back to Salesforce as a custom "Agentic Journey Brief" field on the Account object. Trigger a Salesforce Flow to notify the account owner and create a task for Day 1 actions.
- Use 6sense's webhook API to trigger real-time brief generation when an account surpasses a defined intent surge threshold (e.g., 80+ on primary topic).

**HubSpot Workflows:**
- Create a HubSpot workflow that fires when an account meets: (website sessions > 3 in 7 days AND intent topic active AND deal stage = Evaluation). Pass enriched contact + account data to an n8n or Make.com workflow that calls this prompt via the Claude API and creates a HubSpot Note with the output.

**Clay + Slack:**
- Use Clay to enrich account signals (LinkedIn activity, job postings, funding data, Bombora intent) into a single enriched row. Pass the row to a Clay API call that hits this prompt. Output the orchestration brief to a dedicated Slack channel (`#agentic-account-alerts`) with @mention of the account owner.

**Notion CRM integration:**
- For teams using Notion as a lightweight CRM: use Notion's API + a Python script to pull deal pages, structure them into the prompt format, and write the resulting brief back to the deal page as a linked database block. Schedule with a GitHub Action nightly.

**RevOps automation (Zapier/Make):**
- Trigger: Zapier "New or Updated Deal" in Salesforce → Extract deal fields → Format into prompt → Call Claude API → Parse output → Create Salesforce Task → Send Slack DM to rep with Day 1 action only (not full brief — keep reps focused).

## Troubleshooting

**Problem: Recommendations are too generic (e.g., "send a personalized email" without specifics)**
Solution: The prompt requires specific signal data to produce specific recommendations. Audit your input: if any section has placeholders or vague entries like "some website activity," the output will be vague. Minimum viable signal set for high-quality output: (1) specific pages visited with dates, (2) specific content consumed with engagement metrics, (3) named contacts with titles and last-touch dates, (4) at least one third-party intent signal. If data is sparse, add a line: "DATA QUALITY NOTE: [field] is unavailable — make conservative assumptions and flag when a recommendation relies on an assumption."

**Problem: 14-day cadence is unrealistic for the sales team's bandwidth**
Solution: Add a constraint to the prompt: "Sales team capacity = maximum 2 outreach touches per account per week. Prioritize only the highest-leverage actions and collapse the cadence to 4 touchpoints over 14 days." Also specify: "Flag which actions can be automated by marketing ops without any sales rep involvement." This produces a cadence that is actually executed vs. aspirational.

**Problem: Buying committee gap analysis lists titles that don't exist at this company size**
Solution: Add the company size and org structure to the CONTEXT section: "Note: This is a 300-person company. Likely no dedicated CISO — security decisions owned by VP IT. No separate CFO — finance owned by COO." The agent will adjust its gap analysis to reflect realistic org chart realities rather than defaulting to enterprise-scale buying committee assumptions.

## Version History
- v1.0: Initial creation (auto-generated)
