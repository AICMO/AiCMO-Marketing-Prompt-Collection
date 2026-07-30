# AI-Powered B2B SaaS Agentic Marketing Operations & Autonomous GTM Stack Orchestration Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** b2b-saas, marketing-operations, ai-agents, gtm-engineering, agentic-ai, revenue-operations, clay, apollo, 6sense, rb2b, clearbit, salesforce, hubspot, automation, martech-stack, signal-based-gtm, autonomous-workflows

## Overview
Designs a fully autonomous, AI-agent-native marketing operations architecture that replaces manual MOps workflows with orchestrated AI agents monitoring buyer signals, enriching data, triggering campaigns, qualifying accounts, and routing revenue opportunities — all without human intervention between signal and action. Use this when your marketing stack is human-bottlenecked (campaigns wait on ops tickets), when you want to compress signal-to-outreach latency from days to minutes, or when rebuilding MOps for an AI-first GTM motion.

## Quick Copy-Paste Version

You are a GTM Engineering and AI Marketing Operations expert who architects autonomous revenue systems for B2B SaaS companies. Design a fully agentic marketing operations architecture for the company below.

COMPANY SNAPSHOT:
- Company: [Company name and product — e.g., "Meridian, a contract intelligence platform for enterprise legal and procurement teams"]
- ARR & stage: [e.g., "$18M ARR, Series B, 120% NRR, 45-day avg sales cycle"]
- ICP: [e.g., "General Counsel, VP Legal, Chief Procurement Officer at enterprises 500–10,000 employees, Fortune 2000, US + EU"]
- Current stack: [e.g., "HubSpot + Salesforce + Apollo + ZoomInfo + 6sense + Slack + Clay + RB2B"]
- Core pain: [e.g., "High-intent signals (website visits, G2 views, LinkedIn ad clicks) take 48–72 hours to reach an SDR. By then the buyer has moved on or been contacted by a competitor."]
- Monthly new signals: [e.g., ~2,000 intent events/month across channels]
- SDR team size: [e.g., 6 SDRs, each currently spending 3 hrs/day on manual research]

DELIVERABLES:

1. AUTONOMOUS SIGNAL TAXONOMY: Map every buyer signal your stack can detect (first-party web, intent data, review site, social, technographic change, job posting, funding event, champion movement) with: signal source, data freshness, signal strength tier (1-3), and the autonomous action each tier triggers.

2. AGENT ARCHITECTURE BLUEPRINT: Design the AI agent layer with named agents, their responsibilities, tools/APIs they call, trigger conditions, and handoff logic. Include: Signal Monitoring Agent, Account Enrichment Agent, Scoring & Routing Agent, Campaign Orchestration Agent, and SDR Briefing Agent. For each: inputs → processing logic → outputs → escalation rules.

3. AUTOMATION WORKFLOWS (TOP 3): For the three highest-ROI autonomous workflows, write complete logic including: trigger event, data enrichment steps (Clay/Clearbit/ZoomInfo calls), scoring logic, branching conditions (if Tier 1 account → X; if known contact → Y; if anonymous → Z), campaign enrollment, CRM update, and Slack/SDR notification format.

4. LATENCY REDUCTION ROADMAP: Current state (manual) vs. future state (agentic) for signal-to-action latency. Show the time reduction for each signal type and the revenue impact formula: (monthly signals × conversion lift from speed) × ACV.

5. STACK INTEGRATION MAP: For each tool in the current stack, define: what data it contributes, which agents consume it, what it writes back, and the API/webhook architecture that makes it real-time. Flag any stack gaps that require a new tool.

6. HUMAN-IN-THE-LOOP DESIGN: Define exactly where humans must approve vs. where agents act autonomously. Include: confidence threshold logic (when agent escalates vs. acts), the SDR daily "agent briefing" format, and the weekly MOps review cadence to tune agent logic.

7. MEASUREMENT FRAMEWORK: KPIs for the agentic system — signal-to-first-touch latency (target: <15 min for Tier 1), agent-generated pipeline %, SDR research time reclaimed, MQL-to-SQL conversion rate change, and cost-per-qualified-opportunity.

Output as a structured architecture document with implementation priority order and a 90-day rollout plan.

## Advanced Customizable Version

ROLE: You are a senior GTM Engineer and AI Marketing Operations Architect with 12+ years designing revenue systems for B2B SaaS companies from Series A through public. You have built agentic MOps systems at companies like [reference peer company], reducing signal-to-outreach latency from 72 hours to under 10 minutes and increasing SDR-qualified pipeline by 40%+ without adding headcount.

CONTEXT:
Company: {{COMPANY_NAME}} — {{PRODUCT_DESCRIPTION}}
Business model: {{ARR}}, {{GROWTH_RATE}}, {{SALES_MOTION}} (PLG/inbound/outbound/enterprise)
ICP definition: {{ICP_FIRMOGRAPHICS}}, {{ICP_TECHNOGRAPHICS}}, {{ICP_BEHAVIORAL_SIGNALS}}
Current stack: {{MARTECH_STACK_LIST}}
Current MOps bottleneck: {{DESCRIBE_BOTTLENECK_OR_PAIN}}
Available engineering resources: {{ENGINEERING_BANDWIDTH — e.g., "0.5 FTE GTM engineer, no dedicated MOps dev"}}
Data quality rating: {{1-5 on CRM data completeness/accuracy}}

OBJECTIVE: Design a production-ready agentic marketing operations architecture that:
1. Detects buying intent signals within minutes of occurrence
2. Autonomously enriches, scores, and routes accounts without human intervention
3. Triggers precisely personalized campaigns based on signal context
4. Delivers SDRs pre-researched, signal-contextualized outreach briefs
5. Continuously self-optimizes based on conversion feedback loops

ARCHITECTURE REQUIREMENTS:

SECTION 1 — SIGNAL INTELLIGENCE LAYER
Design the complete signal taxonomy with:
- Signal type (first-party, third-party intent, social, technographic, firmographic trigger)
- Source system and API (RB2B for de-anonymization, 6sense for intent, LinkedIn for social signals, Bombora for third-party intent, Crunchbase/Diffbot for funding/hiring)
- Signal freshness requirements (real-time webhook vs. daily batch vs. weekly)
- Signal strength scoring model: assign a 1–100 composite score based on: recency (40%), signal type weight (30%), ICP fit (20%), prior engagement history (10%)
- Tier assignment logic: Tier 1 (score 80-100): immediate SDR alert + autonomous enrollment; Tier 2 (score 50-79): automated nurture + SDR briefing within 4 hours; Tier 3 (score 20-49): autonomous nurture only

SECTION 2 — AGENT ARCHITECTURE
For each agent, specify using the Agent Card format:

**Agent Name**: [Descriptive name]
**Role**: [Single sentence purpose]
**Trigger**: [What event/schedule activates this agent]
**Inputs**: [Data sources and API calls it makes]
**Processing Logic**: [Decision rules, scoring calculations, LLM prompts it uses]
**Outputs**: [What it writes/sends/creates]
**Tools**: [Specific APIs, webhooks, LLM models used]
**Escalation**: [When it passes to human or different agent]
**Latency SLA**: [Expected processing time]

Design these five core agents:
1. Signal Sentinel Agent — monitors all signal sources in real-time
2. Account Intelligence Agent — enriches accounts using Clay waterfalls (ZoomInfo → Clearbit → Apollo → LinkedIn scraping fallback)
3. ICP & Intent Scoring Agent — runs multi-dimensional scoring model, assigns tier and routing path
4. Campaign Orchestration Agent — selects and enrolls contacts in the right sequence with context-personalized first touch
5. SDR Activation Agent — generates pre-call research brief, drafts first outreach, and posts to Slack with one-click approve/edit/send

SECTION 3 — WORKFLOW LOGIC (DETAIL 3 PRIORITY WORKFLOWS)

For each workflow, write complete pseudo-code logic:

WORKFLOW A: Anonymous High-Intent Website Visitor De-anonymization → Outreach
WORKFLOW B: Champion Movement Signal (Job Change Detection) → Warm Outreach to New Company
WORKFLOW C: Competitor Displacement Trigger (Tech Stack Change Detected) → Competitive Campaign Enrollment

For each:
- Trigger event and detection mechanism
- Enrichment waterfall (tool 1 → fallback tool 2 → fallback tool 3)
- Scoring calculation with formula
- Branching decision tree (IF known contact THEN... ELIF anonymous company THEN... ELSE...)
- Campaign or sequence selected and why
- CRM fields updated (field name, value, update logic)
- Personalization tokens injected into first touch (use JTBD framework for message construction)
- SDR notification format (include: account name, signal detected, score, recommended talk track, objection pre-handle, suggested send time)
- Success metric and feedback loop (how the agent learns from outcome)

SECTION 4 — STACK INTEGRATION ARCHITECTURE
Build a complete data flow diagram in text format showing:
- Every tool in the stack as a node
- Data flowing IN to each agent (source → agent, data type, frequency)
- Data flowing OUT from each agent (agent → destination, data type, action triggered)
- Webhook endpoints required (list each with: tool, event, payload structure)
- API rate limits to respect and retry logic
- Data schema: the 15 most critical fields in Salesforce/HubSpot that agents read/write, with field type and owner

SECTION 5 — HUMAN-IN-THE-LOOP GOVERNANCE
Define the human oversight model:
- Autonomous action thresholds: which actions agents take without approval (CRM enrichment, nurture enrollment, Tier 2/3 email sequences) vs. which require SDR/MOps approval (Tier 1 direct outreach, executive sequences, re-engagement of churned customers)
- The daily SDR Agent Briefing: format, delivery time, content structure, action buttons
- Weekly MOps Agent Review: which metrics signal agent logic needs tuning, who reviews, decision protocol
- Agent confidence scoring: when an agent's confidence < 70%, it presents options to human rather than acting
- Audit trail requirements: what every agent action logs for compliance and optimization

SECTION 6 — IMPLEMENTATION ROADMAP
90-Day Phased Rollout:
- Week 1-2: Foundation (data quality audit, webhook infrastructure, base enrichment waterfall)
- Week 3-4: Signal Sentinel + Scoring Agent (real-time detection + ICP scoring model live)
- Week 5-8: Campaign Orchestration Agent (automated enrollment for Tier 2-3)
- Week 9-10: SDR Activation Agent (Tier 1 briefings and Slack integration)
- Week 11-12: Feedback loops + model tuning (conversion data flowing back to scoring agent)

For each phase: what's deployed, success criteria, who owns it, and what breaks if skipped.

SECTION 7 — ROI PROJECTION MODEL
Calculate projected impact using these formulas:
- Time reclaimed: (SDR headcount × hours/day on research × 0.7 reclaimed) × 250 work days
- Pipeline velocity: (monthly Tier 1 signals × baseline conversion rate × conversion lift from speed) × ACV
- Signal coverage improvement: (signals actioned within 15 min / total signals) — target 90%+ vs. current <10%
- Cost efficiency: (pipeline generated by agent system) / (tool cost + engineering cost)

OUTPUT FORMAT: Structured architecture document with section headers, agent cards in consistent format, workflow pseudo-code in code blocks, ROI model in table format, and 90-day roadmap as a numbered timeline.

CONSTRAINTS:
- Every recommendation must be implementable with {{AVAILABLE_ENGINEERING_BANDWIDTH}}
- Prefer webhook-native integrations over polling to minimize latency
- Design for zero manual data entry — agents maintain data hygiene autonomously
- All personalization must use first-party behavioral data, never assume demographic data is accurate
- Include GDPR/CCPA compliance checkpoints for EU-targeted signal processing

## Example Input/Output

**Input (Quick Version):**
- Company: Vantix, a spend intelligence platform for enterprise procurement and finance teams
- ARR & stage: $22M ARR, Series B, 38-day avg sales cycle, 118% NRR
- ICP: VP Procurement, Chief Procurement Officer, VP Finance, CFO at mid-to-large enterprises 1,000–20,000 employees, manufacturing, retail, and financial services verticals
- Current stack: HubSpot Marketing Hub + Salesforce + Apollo + ZoomInfo + Bombora + RB2B + Clay + Slack
- Core pain: Anonymous visitors with 3+ page views and pricing page visits take 72 hours to reach SDR pipeline. Bombora intent surges sit unread in a CSV sent Monday mornings. Champion job changes discovered weeks after they've already evaluated 2 competitors.
- Monthly new signals: ~3,200 intent events/month
- SDR team: 8 SDRs, spending avg. 2.8 hrs/day on account research

**Output (excerpt):**

---

**SIGNAL TAXONOMY (Tier Assignments)**

| Signal | Source | Freshness | Tier | Autonomous Action |
|---|---|---|---|---|
| Pricing page visit (2+ pages, >90 sec) | RB2B + HubSpot | Real-time | 1 | SDR brief + Slack alert within 8 min |
| Bombora intent surge (score 70+, ICP match) | Bombora API | Daily 6 AM | 1 | SDR brief + sequence enrollment |
| G2 profile view (3rd visit in 7 days) | G2 Buyer Intent | Every 4 hrs | 1 | SDR brief within 30 min |
| Job change: champion to new ICP company | LinkedIn/Diffbot | Daily | 1 | Warm outreach sequence within 2 hrs |
| Competitor tech removal (ZoomInfo) | ZoomInfo webhooks | Weekly | 2 | Displacement sequence enrollment |
| LinkedIn ad click → landing page | HubSpot | Real-time | 2 | Personalized nurture enrollment |
| Blog 3+ posts in session (anonymous) | RB2B | Real-time | 3 | Anonymous nurture via IP-based retargeting |

---

**AGENT CARD: SDR Activation Agent**

**Role:** Converts Tier 1 scored accounts into SDR-ready briefs with drafted first touch within 8 minutes of signal detection.

**Trigger:** ICP Scoring Agent output with tier = 1 and confidence ≥ 75%

**Inputs:**
- Account intelligence package from Account Intelligence Agent (firmographics, technographics, recent news, employee count change, funding history)
- Signal context (what event triggered, timestamp, specific pages/content consumed)
- Contact data (decision-maker name, title, LinkedIn URL, email — enriched via Clay waterfall)
- CRM history (past touches, last activity date, deal stage if exists, prior email engagement)

**Processing Logic:**
1. Select talk track template from JTBD library based on signal type + persona + vertical
2. Inject account-specific context into template using GPT-4o with system prompt: "You are a senior AE at Vantix writing a 3-sentence cold email to a {{TITLE}} at {{COMPANY}}. The buyer just {{SIGNAL_DESCRIPTION}}. Reference their specific situation using {{ACCOUNT_CONTEXT}}. Do not use generic benefits. Be specific to their vertical. No more than 75 words."
3. Score confidence in personalization quality (0–100): if <70, flag for SDR review
4. Select optimal send time based on contact timezone and historical open-rate data

**Outputs:**
- Slack message to assigned SDR's channel (formatted brief — see below)
- Draft email in HubSpot sequence (status: "pending SDR approval")
- HubSpot contact activity logged: "Agent Brief Generated — [timestamp]"
- Salesforce opportunity stage: "Agent Identified" if no existing opportunity

**SDR Slack Brief Format:**
🔥 TIER 1 SIGNAL — Vantix Agent Alert
Account: Hartfield Manufacturing (2,400 employees, Manufacturing, Chicago)
Signal: Pricing page + ROI Calculator (4 min 12 sec) — 8 minutes ago
ICP Score: 87/100 | Confidence: 91%

Contact Found: Marcus Webb, VP Procurement
📧 marcus.webb@hartfield.com | 🔗 LinkedIn
Last CRM Touch: Never contacted

Why They're Hot:
• Bombora intent surge: "procurement software" score 74 this week
• Hiring 2 Procurement Analysts (Indeed posting, 9 days ago)
• Currently using Coupa (ZoomInfo) — renewal typically Q4

Suggested Talk Track: Manufacturing vertical / procurement transformation / Coupa displacement
Draft Email Ready → [Review & Send] [Edit First] [Skip for Now]

Similar Won Deal: Renwick Industrial — 38-day cycle, $84K ACV

**Latency SLA:** Signal detection to Slack delivery < 8 minutes for 95% of Tier 1 signals

---

**WORKFLOW B: Champion Movement Detection → Warm Outreach**

TRIGGER: LinkedIn/Diffbot job change detected for contact in CRM with tag "Champion" OR "Economic Buyer"

STEP 1: Validate signal
  - Confirm new company exists (Clearbit Enrichment API)
  - Check new company against ICP scoring model
  - IF new company ICP score ≥ 60 → continue
  - ELSE → log signal, tag contact "Champion at Non-ICP", exit workflow

STEP 2: Enrich new company
  - Clay waterfall: ZoomInfo → Clearbit → Apollo → LinkedIn (fallback)
  - Fields captured: employee count, industry, tech stack, funding, revenue estimate
  - IF enrichment confidence < 70% on any critical field → flag for MOps review

STEP 3: Find new buying committee at target company
  - Apollo search: title contains ["Procurement" OR "Finance" OR "CFO" OR "COO"]
    AND company domain = new_company_domain
    AND seniority in [Director, VP, C-Suite]
  - Limit to top 3 contacts by title match score
  - Enrich each contact: email, LinkedIn, direct dial

STEP 4: Score opportunity
  - Champion relationship score (1-3): 
    3 = Champion was a closed-won customer, was an internal advocate
    2 = Champion was an active opportunity contact
    1 = Champion was a nurture/engaged contact only
  - New company ICP fit score (existing model)
  - Composite score = (Champion score × 0.5) + (ICP score × 0.5)
  - IF composite ≥ 70 → Tier 1 | IF 40-69 → Tier 2 | IF < 40 → Tier 3

STEP 5: Route by tier
  IF Tier 1:
    → Create new Salesforce opportunity: "Champion-Led Inbound — [New Company]"
    → Enroll champion contact in "Champion Movement — Warm Outreach" sequence
    → Enroll top new buying committee contact in "Champion-Referred — New Company" sequence
    → Generate SDR Slack brief with: champion name, new company, relationship context, suggested warm intro angle
    → Assign to AE who closed original champion's deal (if exists) ELSE assign to AE territory owner
  
  IF Tier 2:
    → Enroll champion in "Keep Warm — New Role" sequence (3 touches, 14-day cadence)
    → Flag new company for SDR territory review
    → Add to weekly SDR briefing digest
  
  IF Tier 3:
    → Tag champion: "Moved to Non-ICP"
    → Schedule re-evaluation in 90 days (Bombora intent check + ICP re-score)
    → No outreach

STEP 6: Log and feedback
  - Log: signal type, champion name, new company, composite score, tier, action taken, timestamp
  - Update champion contact: new company, new title, new email, "Last Detected Movement" date
  - Feed outcome (meeting booked Y/N, opportunity created Y/N) back to scoring model

**ROI Snapshot (Vantix example):**
Champion movement signals per month: ~45 detected
% that meet Tier 1 threshold: ~28% = 12.6 signals
Historical conversion (champion-referred): 31% to meeting
Meetings generated monthly: ~3.9
ACV: $84K average
Annual pipeline impact: $3.9 × 12 × $84K = $3.9M in influenced pipeline

---

## Success Metrics

**Operational Metrics:**
- Signal-to-first-touch latency: < 15 minutes for 95% of Tier 1 signals (baseline: 48–72 hours)
- Agent coverage rate: % of detectable signals acted on within SLA (target: >90%)
- SDR research time reclaimed: target 2+ hours/day/SDR redirected to selling
- Agent personalization quality score: >75/100 average (tracked by SDR acceptance rate)

**Revenue Metrics:**
- Agent-influenced pipeline %: target 35–50% of total pipeline touched by at least one autonomous agent action within 30 days
- MQL-to-SQL conversion rate: target 15–20% lift from speed-to-lead improvement
- Signal-to-opportunity cycle: time from first signal to Salesforce opportunity creation (target: <4 hours for Tier 1)
- Champion movement win rate: deals sourced from job-change signal (track separately, expected 2–3× baseline)

**System Health Metrics:**
- Agent uptime: >99.5% for Signal Sentinel and Scoring Agents
- Enrichment waterfall coverage: % of accounts fully enriched on first pass (target: >85%)
- False positive rate: Tier 1 signals that SDRs mark "Not Relevant" (target: <15%)
- CRM data freshness: % of ICP accounts with enrichment updated in last 30 days (target: >80%)

## Related Prompts

- [AI-Powered B2B SaaS Intent Data Orchestration & Buying Signal Campaign Trigger Architecture](./AI-Powered-B2B-SaaS-Intent-Data-Orchestration-&-Buying-Signal-Campaign-Trigger-Architecture-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Inbound Lead Scoring & Revenue Qualified Pipeline Architecture](./AI-Powered-B2B-SaaS-Inbound-Lead-Scoring-&-Revenue-Qualified-Pipeline-Architecture-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Marketing to Sales Handoff Architecture & Revenue SLA](./AI-Powered-B2B-SaaS-Marketing-to-Sales-Handoff-Architecture-&-Revenue-SLA-Intelligence-Engine.md)
- [AI-Powered B2B Signal-Based GTM Architecture & Multi-Source Buyer Intent Orchestration](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/AI-Powered-B2B-SaaS-Signal-Based-GTM-Architecture-&-Multi-Source-Buyer-Intent-Orchestration-Intelligence-Engine.md)

## Integration Tips

**Clay:** Use Clay as the central enrichment orchestration layer. Build a "Master Account Table" that syncs from Salesforce/HubSpot and runs enrichment waterfalls automatically when new accounts enter or enrichment age exceeds 30 days. Use Clay's Claygent (AI agent) to research accounts using custom prompts, then push enriched data back to CRM via Clay's native HubSpot/Salesforce integrations.

**HubSpot Workflows:** Use HubSpot's native workflow engine for Tier 2–3 automated nurture sequences. Trigger on CRM properties updated by agents (e.g., "Intent Score Updated," "Agent Tier = 2"). Keep Tier 1 actions in a separate, SDR-gated workflow that requires manual approval before sending.

**Salesforce:** Create a custom object "GTM Signals" to log every agent-detected signal (type, source, score, action taken, outcome). This becomes the training data for improving scoring models over time. Build a Lightning dashboard: "Agent Activity Today" showing Tier 1 alerts, meetings booked from agent signals, and pipeline influenced.

**Slack:** Use Slack's Block Kit to create structured, interactive briefing messages with action buttons (Review & Send / Edit / Skip). Route Tier 1 alerts to individual SDR channels. Create a `#gtm-agent-pulse` channel for MOps to monitor agent activity, error logs, and performance metrics in real-time.

**n8n / Make (formerly Integromat):** For teams without a dedicated GTM engineer, n8n (self-hosted) or Make.com provide visual workflow builders that can connect webhooks from RB2B → Clay → HubSpot/Salesforce → Slack without custom code. Budget ~20 hours to build the initial signal routing infrastructure.

**6sense / Bombora:** Configure these platforms' webhook/API exports to push intent data in real-time (or daily batch at minimum) to your central agent system rather than waiting for weekly CSV reports. 6sense's Salesforce native integration can trigger Apex workflows for Tier 1 signals.

## Troubleshooting

**Problem: Agent is generating Tier 1 alerts for clearly non-ICP accounts**
Root cause: ICP scoring model hasn't been trained on sufficient negative examples (accounts that looked good but never converted).
Fix: Run a 90-day retrospective on all Tier 1 alerts. Tag outcomes (meeting booked, opportunity created, lost, irrelevant). Feed negative outcomes back into scoring model. Add hard-exclusion filters: employee count < 50, revenue < $10M, certain industries (non-ICP), or job titles that consistently produce no meetings. Typical tuning brings false positive rate from 30% down to <12% within 60 days.

**Problem: Signal-to-Slack latency is 45+ minutes instead of target <15 minutes**
Root cause: Enrichment waterfall is calling synchronous APIs sequentially instead of in parallel, or Clay workflow limits are throttling processing.
Fix: Audit Clay workflow step order — run ZoomInfo, Clearbit, and Apollo enrichment steps in parallel (Clay supports concurrent HTTP steps). Check API rate limits: if hitting ZoomInfo's hourly cap, add a fallback queue that processes overflow in the next rate-limit window. For RB2B webhook processing, ensure your webhook receiver (n8n/Make) is running on a server with <200ms response time. Target: enrichment complete within 3 minutes of signal detection.

**Problem: SDRs aren't using agent-generated drafts and are rewriting from scratch**
Root cause: Personalization quality is too low (generic benefit statements) or drafts don't match SDR's voice.
Fix: Run a "draft quality calibration" session — have SDRs rate 20 agent-generated drafts on a 1–5 scale and annotate why. Feed annotated examples back into the LLM system prompt as few-shot examples. Add a "voice calibration" step per SDR: have each SDR submit 5 of their best-performing emails; use these as style reference in the prompt. Within 2 sprints, SDR acceptance rate typically rises from ~30% to >65%.

## Version History
- v1.0: Initial creation (auto-generated)
