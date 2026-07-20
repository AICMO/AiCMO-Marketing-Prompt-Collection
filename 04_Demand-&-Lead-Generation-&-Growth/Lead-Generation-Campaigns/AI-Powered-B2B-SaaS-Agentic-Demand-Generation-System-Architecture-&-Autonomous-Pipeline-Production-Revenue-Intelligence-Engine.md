# AI-Powered B2B SaaS Agentic Demand Generation System Architecture & Autonomous Pipeline Production Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** demand-gen, ai-agents, pipeline, automation, b2b, agentic-gtm, revenue-ops

## Overview
Designs a complete multi-agent AI system for autonomous B2B SaaS demand generation — covering agent role definition, signal monitoring workflows, autonomous outreach orchestration, quality gates, and revenue attribution. Use this when you need to move from human-operated campaign execution to a self-running, continuously-optimizing pipeline production engine.

## Quick Copy-Paste Version

You are a senior GTM architect specializing in agentic AI systems for B2B SaaS demand generation. Design a complete autonomous demand generation system for a B2B SaaS company.

Company context:
- Product: [Your SaaS product — e.g., "project management platform for engineering teams"]
- ACV: [Average contract value — e.g., "$24,000/year"]
- Target ICP: [Ideal customer profile — e.g., "VP Engineering at Series B-D tech companies, 50-500 employees"]
- Current pipeline gap: [Monthly pipeline needed — e.g., "$2M/month in new pipeline"]
- Sales cycle: [Length — e.g., "60-90 days"]
- Existing tools: [CRM, MAP, enrichment — e.g., "HubSpot, Apollo, 6sense, Salesforce"]

Design a multi-agent demand generation architecture that includes:

1. SIGNAL MONITORING AGENTS (3-5 agents)
   - What signals each agent monitors (job postings, funding news, product usage, competitor mentions, intent data, dark social)
   - Trigger thresholds and confidence scores
   - Data sources and enrichment logic
   - Output format for downstream agents

2. ACCOUNT QUALIFICATION AGENTS (2-3 agents)
   - ICP fit scoring methodology
   - Buying committee mapping logic
   - Account prioritization tiers (Tier 1/2/3)
   - Disqualification criteria that prevent wasted outreach

3. CONTENT PERSONALIZATION AGENTS (3-4 agents)
   - How each agent personalizes outreach for different signal types
   - Message variants for each buying committee persona (Champion, Economic Buyer, Technical Evaluator, End User)
   - A/B testing framework the agent runs autonomously
   - Content refresh triggers when response rates drop below threshold

4. OUTREACH ORCHESTRATION AGENTS (2-3 agents)
   - Channel sequencing logic (email → LinkedIn → phone → direct mail)
   - Cadence timing and spacing rules
   - Sentiment analysis for reply classification (interested / objection / not now / wrong person)
   - Automatic handoff to human SDR/AE when engagement score exceeds threshold

5. FEEDBACK & OPTIMIZATION AGENTS (2 agents)
   - What metrics each agent tracks
   - How agents update playbooks based on win/loss patterns
   - Pipeline velocity monitoring and bottleneck identification
   - Weekly self-reported performance summary format

6. HUMAN OVERSIGHT FRAMEWORK
   - Which decisions require human approval before execution
   - Daily/weekly review cadences for marketing leadership
   - Quality gates and compliance checks
   - Kill switches and rollback procedures

7. TECHNOLOGY STACK REQUIREMENTS
   - Recommended agent orchestration layer (n8n, Clay, Zapier, LangChain, etc.)
   - Data infrastructure needed
   - Integration points with existing MarTech stack
   - Estimated setup complexity and build sequence

8. 90-DAY ACTIVATION ROADMAP
   - Week 1-2: Foundation and data wiring
   - Week 3-4: First agent deployment (which to start with and why)
   - Month 2: Scale to full system
   - Month 3: Optimization loop live

For each agent, specify: agent name, primary job, inputs consumed, outputs produced, tools/APIs needed, and success metric.

Output the full architecture as a structured blueprint a RevOps team could hand to an engineer to build.

## Advanced Customizable Version

ROLE: You are a Chief Revenue Architect with deep expertise in agentic AI systems, B2B SaaS demand generation, and revenue operations. You have designed autonomous pipeline production systems for companies from Series B to public SaaS. You think in systems, not campaigns.

CONTEXT:
Company: [Company name]
Stage: [Series A/B/C/D/Public]
Product category: [e.g., "AI-powered data observability platform"]
ICP definition:
  - Primary: [Title, company size, industry, tech stack signals]
  - Secondary: [Expansion titles and adjacent ICPs]
ACV: [$X annual / $X monthly]
Monthly pipeline target: [$X new pipeline required]
Current state: [Current demand gen approach — e.g., "manual SDR-led outbound + some inbound from content"]
Pipeline gap: [e.g., "Currently generating $800K/month, need $2M/month"]
Sales team size: [AEs and SDRs]
Marketing team size: [Headcount available to manage this system]
Budget available for tooling: [$X/month]
Compliance constraints: [GDPR/CCPA/industry-specific data rules]

OBJECTIVE: Design a production-ready agentic demand generation system that can autonomously identify, qualify, engage, and convert target accounts into pipeline — with minimal human intervention for routine execution and clear human escalation paths for judgment calls.

SYSTEM ARCHITECTURE REQUIREMENTS:

## LAYER 1: INTELLIGENCE & SIGNAL ARCHITECTURE

Design the signal monitoring infrastructure:

**Buying Signal Categories (rank by conversion predictivity for this ICP):**
- Intent signals: G2 profile visits, competitor content consumption, category keyword searches
- Firmographic triggers: funding rounds, headcount growth >20% in target department, new office openings
- Technographic signals: tool adoption, tool replacement indicators, integration partner usage
- Behavioral signals: website visits, content downloads, dark social mentions
- Hiring signals: job postings for roles that indicate budget and readiness (specify which titles)
- News signals: leadership changes, product announcements, regulatory events
- Engagement signals: email opens/clicks, webinar attendees, community activity

For each signal type, specify:
- Data source(s) and API/integration method
- Signal freshness window (how recent must it be to trigger action)
- Confidence scoring model (0-100 scale with thresholds for Tier 1/2/3 account assignment)
- Enrichment requirements before signal is actionable

## LAYER 2: ACCOUNT INTELLIGENCE AGENTS

Design agents that build a complete account picture before any outreach:

**Account Research Agent:**
- Inputs: domain, company name, trigger signal
- Process: pull firmographics (Clearbit/Apollo), financials (Crunchbase/PitchBook), tech stack (BuiltWith/HG Insights), recent news (Perplexity/Exa), employee count trends (LinkedIn), org chart (Apollo/LinkedIn Sales Nav)
- Outputs: Account Intelligence Card (AIC) — structured JSON with ICP fit score, buying committee map, recommended entry points, competing vendors in use, key pain points based on signals
- Confidence threshold: Only proceed to outreach if ICP fit score ≥ [X]

**Buying Committee Mapping Agent:**
- Inputs: Account Intelligence Card
- Process: Identify all relevant personas (Economic Buyer, Champion, Technical Evaluator, End User, Legal/Procurement) using LinkedIn + ZoomInfo/Apollo
- Outputs: Buying committee map with LinkedIn URLs, email addresses, phone numbers, tenure, recent posts/activity, mutual connections, previous engagement with your content
- Prioritization: Rank contact list by engagement likelihood score

**Competitive Intelligence Agent:**
- Inputs: Account domain, existing tech stack
- Process: Identify current vendor in your category, assess satisfaction signals (G2 reviews, social complaints, renewal timing indicators), map switching triggers
- Outputs: Competitive context card appended to AIC — informs messaging angle (displacement vs. greenfield vs. expansion)

## LAYER 3: PERSONALIZED CONTENT GENERATION AGENTS

Design agents that produce hyper-personalized outreach assets at scale:

**Message Personalization Agent:**
- Inputs: Account Intelligence Card + Buying Committee Map + Competitive Context + Signal Type
- Frameworks to apply: Jobs-to-be-Done (what outcome does this persona need?), SPIN Selling (situation/problem/implication/need-payoff for each persona), Challenger Sale (teach/tailor/take control framework for economic buyers)
- Required personalization variables per message:
  * Company-specific insight (something they won't have heard before)
  * Role-specific pain point (derived from their job description + recent activity)
  * Proof point from a similar company (reference customer in same industry/stage)
  * Clear, specific call to action (not "let's connect" — be specific about what value the meeting delivers)
- Output: 5-7 message variants per persona per signal type, with subject lines, preview text, and body copy in three lengths (short/medium/long)
- A/B test plan: which variables to test first and why

**Content Recommendation Agent:**
- Inputs: Persona + stage in buying journey (awareness/consideration/decision) + signal type
- Process: Match intent signals to existing content library; identify content gaps and flag to content team
- Outputs: Top 3 content assets to include/reference in outreach, with personalized framing for each asset (not just a generic link — specific reason this person should read this now)

**Ad Creative Brief Agent (for paid retargeting):**
- Inputs: Account list + persona + message angle from personalization agent
- Outputs: LinkedIn Matched Audience upload file + ad copy variants for each persona + bid recommendation + LinkedIn Conversation Ad script for the buying committee

## LAYER 4: OUTREACH ORCHESTRATION AGENTS

Design the multi-channel, multi-touch outreach engine:

**Sequence Orchestration Agent:**
- Channel logic: Email → LinkedIn connection + message → LinkedIn post engagement → Phone → Video message (Loom) → Direct mail (for Tier 1 only)
- Timing rules: Day 1 (email), Day 3 (LinkedIn connect), Day 5 (LinkedIn message), Day 8 (email follow-up with new angle), Day 12 (phone), Day 16 (email with case study), Day 21 (LinkedIn post comment + DM), Day 28 (breakup email with last CTA)
- Variance logic: Adjust timing based on email engagement (if Day 1 email opened 3+ times, accelerate to Day 2 phone)
- Persona routing: Different sequences for Champion vs. Economic Buyer vs. Technical Evaluator

**Reply Intelligence Agent:**
- Inputs: All inbound email replies, LinkedIn messages, call notes
- Process: Classify reply as: (a) Positive intent — route to AE with full context package, (b) Objection — select appropriate objection-handling response, (c) Not now — schedule re-engagement at specified date, (d) Wrong person — identify correct contact, (e) Unsubscribe — immediately suppress + update CRM, (f) Referral — process new contact information
- Outputs: Recommended next action + pre-drafted response for human review before sending (for high-value accounts) or auto-send (for standard sequences)

**Engagement Scoring Agent:**
- Track all digital engagement: email opens/clicks, LinkedIn profile views, website visits, content downloads, ad impressions
- Score each contact 0-100 based on recency and intent weight
- Trigger: When buying group engagement score exceeds [X], auto-alert AE with "hot account" notification including full engagement timeline

**Meeting Conversion Agent:**
- Inputs: Positive reply or high engagement score trigger
- Process: Analyze calendar availability, suggest 3 specific meeting times, send calendar link with pre-meeting questionnaire to qualify in/out
- Pre-meeting prep package: Auto-generate AE briefing document (company context, contact background, signal history, recommended discovery questions, competitive context, suggested opening)

## LAYER 5: PIPELINE ACCELERATION AGENTS

Design agents that work the pipeline after meeting booked:

**Deal Intelligence Agent:**
- Inputs: CRM opportunity data, meeting notes (auto-transcribed), email thread
- Process: Monitor deal health using MEDDPICC criteria; flag missing qualification criteria; suggest next best actions
- Outputs: Weekly deal health score + recommended marketing touchpoints to keep buying committee engaged between sales calls

**Multi-Thread Activation Agent:**
- Inputs: Current contacts engaged vs. full buying committee map
- Process: Identify stakeholders not yet engaged; create warm introduction requests for Champion to facilitate; trigger executive-to-executive outreach from your CEO/CMO to their C-suite
- Outputs: Draft LinkedIn messages, email intros, or executive briefing invitations

**Proof Content Agent:**
- Inputs: Deal stage + persona + objections raised in sales calls
- Process: Match objections to relevant case studies, ROI calculators, analyst reports, security documentation, reference customers
- Outputs: Personalized sales room (Notion/Highspot/Seismic) populated with curated content + recommended send sequence

## LAYER 6: OPTIMIZATION & LEARNING AGENTS

Design the feedback loop that makes the system smarter over time:

**Performance Analytics Agent:**
- Daily metrics: Signals processed, accounts qualified, messages sent, reply rate, meeting rate, pipeline generated
- Weekly metrics: MQL-to-meeting rate, meeting-to-opportunity rate, average deal velocity, CAC by signal type, win rate by ICP segment
- A/B test readout: Which message variants winning, statistical significance thresholds
- Underperforming sequence flags: Trigger review when reply rate drops >20% from 4-week average

**Playbook Update Agent:**
- Inputs: Win/loss data from CRM + call recordings + reply classifications
- Process: Monthly analysis of patterns in won vs. lost deals; identify which signals → messages → sequences produce highest conversion; update sequence playbooks accordingly
- Outputs: Playbook version update with changelog + performance prediction for new vs. old playbook

**Market Intelligence Agent:**
- Weekly scan: Competitor product announcements, pricing changes, customer win/loss patterns, category news
- Outputs: Alert to marketing leadership when competitive messaging needs updating + draft updated competitive battlecard sections

## LAYER 7: HUMAN OVERSIGHT FRAMEWORK

Define the human-in-the-loop decision points:

**Requires Human Approval Before Execution:**
- Any outreach to C-suite at Tier 1 accounts (>$100K potential ACV)
- Message variants that mention competitors by name
- Direct mail sends (budget threshold)
- Executive-to-executive outreach requests
- Any message flagged for potential compliance risk

**Daily Human Review (15 min):**
- Hot account notifications (engagement score triggers)
- Replies classified as "Positive intent" requiring same-day response
- Any unsubscribes or negative replies that need relationship repair

**Weekly Human Review (60 min):**
- Performance dashboard with anomaly flags
- A/B test results and playbook update recommendations
- Budget pacing vs. pipeline output
- Top 10 accounts approaching meeting-booking threshold

**Monthly Human Review (2 hours):**
- System-level performance vs. targets
- Playbook version approval
- ICP definition refinement based on conversion data
- Tooling cost vs. pipeline ROI

**Kill Switches:**
- Immediate: Pause all outreach for a specific domain (for sensitive accounts)
- Segment: Pause a specific signal type if false positive rate exceeds threshold
- Full system: Emergency stop all autonomous outreach pending review

## TECHNOLOGY STACK ARCHITECTURE

Specify the recommended tech stack:

**Agent Orchestration Layer:** [n8n / Make / LangChain / CrewAI / Relevance AI — select based on technical resources available]

**Data Infrastructure:**
- CRM: Salesforce or HubSpot (source of truth for all account/contact data)
- Data warehouse: Snowflake or BigQuery (for cross-tool analytics)
- CDP: Segment or RudderStack (for behavioral data unification)

**Signal Intelligence Tools:**
- Intent: Bombora / 6sense / G2 Buyer Intent
- Enrichment: Apollo / Clearbit / Clay
- Firmographic: Crunchbase / LinkedIn Sales Navigator
- Web visitor: Warmly / Dealfront / RB2B

**Outreach Execution:**
- Email: Outreach.io / Salesloft / Instantly (with warm-up protocols)
- LinkedIn: Heyreach / La Growth Machine / Dripify
- Phone: Orum / Nooks / Aircall
- Direct mail: Sendoso / Alyce

**AI/LLM Layer:**
- Personalization: Claude API / GPT-4 / Gemini Pro
- Conversation analysis: Gong / Chorus
- Content generation: Claude / Custom fine-tuned model on your top-performing messages

**Quality & Compliance:**
- Email validation: ZeroBounce / NeverBounce
- Spam testing: Mail-tester / GlockApps
- Data compliance: OneTrust for consent management

## 90-DAY ACTIVATION ROADMAP

**Weeks 1-2: Foundation**
- [ ] Audit existing data quality in CRM (contact accuracy, firmographic completeness)
- [ ] Define ICP scoring model with explicit tier criteria
- [ ] Map existing content to buyer personas and journey stages
- [ ] Select and configure agent orchestration platform
- [ ] Wire primary data sources (CRM + enrichment + intent)
- [ ] Build Account Intelligence Card template

**Weeks 3-4: First Agent Live**
- [ ] Deploy Signal Monitoring Agent (start with ONE high-conviction signal type — recommend intent data from 6sense/Bombora)
- [ ] Deploy Account Qualification Agent with ICP scoring
- [ ] Write first 3 message playbooks (one per top persona)
- [ ] Run first 50-account batch — manually review all outputs before sending
- [ ] Measure baseline reply rate for human-calibration comparison

**Month 2: System Expansion**
- [ ] Deploy Buying Committee Mapping Agent
- [ ] Deploy Message Personalization Agent (replace manual writing)
- [ ] Activate 3 additional signal types
- [ ] Deploy Reply Intelligence Agent with human oversight on all classifications
- [ ] Launch paid retargeting layer synced to active outreach sequences

**Month 3: Full Automation + Optimization Loop**
- [ ] Deploy Performance Analytics Agent with automated weekly report
- [ ] Deploy Playbook Update Agent (first recommendation cycle)
- [ ] Reduce human approval requirements for Tier 2/3 accounts to daily batch review
- [ ] Run first A/B test powered by Message Personalization Agent
- [ ] Calculate agent-assisted CAC vs. human-only CAC for board reporting

OUTPUT FORMAT:
Produce this architecture as:
1. Executive Summary (1 page) — what this system does, what it replaces, expected pipeline impact
2. Agent Directory — a table of every agent: Name | Layer | Job | Inputs | Outputs | Tool | Success Metric
3. Workflow diagram description — describe the end-to-end flow from signal to booked meeting as a process narrative
4. Tech stack decision matrix — for each tool category, recommend primary + 2 alternatives with trade-offs
5. 90-day build roadmap with weekly milestones
6. Risk register — top 5 risks (compliance, deliverability, over-automation, data quality, agent errors) with mitigation plan
7. ROI projection model — expected pipeline per $1 invested in system vs. traditional SDR model

## Example Input/Output

**Input Example:**

Company: Meridian Analytics — AI-powered supply chain intelligence platform
ACV: $48,000/year
ICP: VP Supply Chain / VP Operations at mid-market manufacturers (250-2,500 employees, $50M-$500M revenue), US-based, using SAP or Oracle ERP
Pipeline gap: Currently generating $600K/month, need $1.8M/month
Existing tools: HubSpot CRM, Apollo for enrichment, Bombora for intent
Monthly outreach budget for tools: $8,000/month
Team: 2 SDRs, 1 demand gen manager, 0 engineers (using RevOps consultant 10 hrs/month)

**Output Example (abbreviated):**

**Executive Summary:**
The Meridian Agentic Demand Gen System replaces 70% of manual SDR research and sequencing with AI agents, freeing SDRs to focus exclusively on active conversations and meeting facilitation. The system monitors 7 buying signals simultaneously — targeting accounts 4-6 weeks before they enter an active buying cycle. Expected output: 60-80 qualified pipeline opportunities per month at 35% lower CAC than the current SDR-led model.

**Agent Directory (sample rows):**

| Agent | Layer | Job | Inputs | Outputs | Primary Tool | Success Metric |
|-------|-------|-----|--------|---------|------|------|
| Supply Chain Signal Monitor | Intelligence | Monitor Bombora for surge on "supply chain optimization" + "ERP integration" keywords among ICP companies | Bombora API, Firmographic filters | Triggered account list with signal score | Bombora + n8n | >40 ICP accounts/week meeting signal threshold |
| Hiring Trigger Agent | Intelligence | Detect new VP Supply Chain hires + open roles for "Supply Chain Analyst" at ICP accounts | LinkedIn + Apollo API | Account trigger list with role data + tenure info | Clay + n8n | <24hr detection lag for qualifying hires |
| Meridian ICP Scorer | Qualification | Score all triggered accounts 0-100 on ICP fit | Bombora trigger + Apollo firmographics + HubSpot history | ICP Fit Score + Tier designation (1/2/3) + proceed/disqualify flag | Clay + Claude API | >80% Tier 1 accounts match closed-won ICP profile |
| Buying Committee Builder | Intelligence | Map VP Supply Chain + COO + IT Director + Procurement Director at each account | LinkedIn Sales Nav + Apollo | Buying committee JSON with LinkedIn URLs, emails, recent posts, mutual connections | Apollo + Clay | >3 contacts mapped per account before outreach |
| VP Supply Chain Personalizer | Content | Write personalized outreach for VP Supply Chain emphasizing operational efficiency ROI and peer benchmarking | Account Intelligence Card + signal type + recent LinkedIn activity | 6 email variants + LinkedIn message variants, ranked by predicted performance | Claude API | Reply rate >4% (vs. 1.2% industry benchmark) |
| Reply Classifier | Orchestration | Classify all inbound replies and route to correct workflow | Raw email/LinkedIn reply text | Classification tag + recommended next action + pre-drafted response | Claude API + HubSpot | >95% classification accuracy vs. human review |

**Recommended First Signal to Activate:** Bombora intent surge on "supply chain optimization" + "ERP integration" — historically correlates with 73% of Meridian's won deals showing pre-purchase intent surge 45 days before first sales contact.

**Week 1-2 Specific Actions for Meridian:**
1. Export last 24 months of won deals from HubSpot — identify the 3 most common trigger signals in the 60 days before first meeting
2. Build ICP scoring model in Clay: +20 pts for US-based, +15 pts for 250-2500 employees, +15 pts for SAP/Oracle in tech stack, +20 pts for manufacturing SIC codes, +15 pts for $50M-$500M revenue, +15 pts for Bombora intent score >60
3. Create "Meridian Account Intelligence Card" template in HubSpot custom object
4. Run first 30-account batch manually through n8n workflow — compare AI-generated personalization quality vs. SDR-written messages

## Success Metrics

**Green (System is working):**
- Signal-to-sequence entry rate: >30 ICP accounts processed per week per active signal type
- ICP qualification accuracy: >80% of Tier 1 accounts match post-meeting ICP criteria
- Email reply rate: >3.5% (vs. 1-2% industry average for cold outbound)
- Meeting-to-opportunity rate: >50% (higher than human-only because of better pre-qualification)
- Agent-assisted CAC: <60% of human-only SDR CAC within 90 days

**Yellow (Needs tuning):**
- Reply rate 1.5-3.5% — check personalization quality and signal-to-message relevance
- High unsubscribe rate (>0.5%) — check message tone, volume, and targeting precision
- Low signal volume (<15 accounts/week) — broaden signal sources or adjust ICP parameters

**Red (System problems):**
- Compliance flags: Any GDPR/CAN-SPAM violations — pause system immediately
- Deliverability score drops below 80 — check sending infrastructure, warm-up protocols
- AE rejection of agent-qualified leads >30% — recalibrate ICP scoring model

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Signal-Based-GTM-Automation-&-Revenue-Trigger-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/AI-Powered-ABM-Target-Account-List-Building-&-ICP-Scoring-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/AI-Powered-B2B-Autonomous-AI-SDR-Program-Architecture-&-Outbound-Pipeline-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Demand-Generation-Program-Analytics/AI-Powered-B2B-SaaS-Demand-Generation-Program-Analytics-&-Pipeline-Coverage-Intelligence-Engine.md`

## Integration Tips

**HubSpot Users:**
- Use HubSpot Custom Objects to store Account Intelligence Cards and signal history
- Build HubSpot Workflows triggered by ICP score threshold to assign to sequences
- Use HubSpot Reporting to track agent-initiated vs. human-initiated pipeline separately

**Salesforce Users:**
- Create "Agentic Pipeline Source" field to track all AI-initiated opportunities separately for ROI measurement
- Use Salesforce Flow to automate AE briefing document generation when opportunity created
- Einstein Activity Capture for logging all agent-initiated touchpoints in activity timeline

**Clay (Recommended for enrichment layer):**
- Build the Account Intelligence Card as a Clay Table with waterfall enrichment (Apollo → Clearbit → Bombora → LinkedIn scrape)
- Use Clay's AI column to generate message personalization variables before exporting to outreach tool
- Connect Clay → HubSpot/Salesforce via native integration for real-time CRM updates

**n8n (Recommended for orchestration):**
- Host n8n on cloud (Railway or Render) for <$50/month vs. n8n Cloud
- Use n8n's error handling to catch failed enrichment calls and route to manual queue
- Build separate n8n workflow for each signal type so you can pause/tune independently

**Compliance Setup:**
- Configure suppression list sync between all outreach tools (never rely on one tool's unsubscribe list)
- Add 48-hour delay after unsubscribe before system stops all active threads for that contact
- Log all AI-generated messages with timestamp and model version for audit trail

## Troubleshooting

**Problem: Reply rate below 1% after 2 weeks of operation**
Solution: The personalization agent is likely generating generic output. Test: pull 20 sent messages and score each on specificity (does the first sentence prove you've done real research on this company?). If generic, increase the specificity requirements in your prompt — require the agent to cite a specific company fact (exact funding amount, specific product launched, named executive hire) in the opening line. Also check: are you over-sending to the same contacts? Run a frequency analysis — if any contact received >3 touches in 7 days, dial back cadence.

**Problem: AEs are rejecting agent-qualified leads ("these aren't my ICP")**
Solution: Your ICP scoring model is miscalibrated. Run a 30-deal win analysis: pull the last 30 closed-won deals and score them through your current ICP model. If <70% score above your Tier 1 threshold, your criteria are wrong. Interview 3 AEs on what makes a "perfect account" — look for signals they mention that aren't in your model (e.g., "they always have a VP-level champion" or "they're always on Salesforce not HubSpot"). Rebuild the scoring model with these criteria weighted higher.

**Problem: Email deliverability dropping — messages going to spam**
Solution: Stop all outreach immediately and run a deliverability audit (Mailgenius.com, GlockApps). Check: (1) sending volume ramp — did you exceed 50 new contacts/day per inbox? (2) spam trigger words in agent-generated copy — run all templates through a spam checker, (3) domain/IP reputation — check MXToolbox for blacklisting, (4) unsubscribe rate — if >0.5%, you're targeting too broadly or messaging is too aggressive. Re-warm your sending domains for 2 weeks before resuming at lower daily limits.

## Version History
- v1.0: Initial creation (auto-generated)
