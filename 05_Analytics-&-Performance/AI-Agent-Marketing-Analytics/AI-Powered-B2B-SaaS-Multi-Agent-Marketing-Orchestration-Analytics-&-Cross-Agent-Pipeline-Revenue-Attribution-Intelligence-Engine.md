# AI Marketing Multi-Agent Orchestration Analytics & Cross-Agent Pipeline Revenue Attribution Intelligence Engine - Measure, Debug, and Optimize Every AI Agent Collaboration in Your Revenue Stack

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** ai-agents, multi-agent, orchestration, analytics, pipeline-attribution, marketing-operations, b2b, revenue-intelligence

## Overview
This prompt builds a complete analytics framework for multi-agent marketing systems — measuring how AI agents collaborate, hand off work to each other, and jointly contribute to pipeline and revenue. Use it when you've deployed 3+ AI marketing agents that interact (e.g., an intent detection agent feeds an email personalization agent feeds an SDR agent) and need to attribute revenue across the chain, identify orchestration failures, and optimize agent collaboration to maximize pipeline velocity.

## Quick Copy-Paste Version

You are a Multi-Agent Marketing Systems Analyst. Analyze the performance of our interconnected AI marketing agent network and produce a complete cross-agent revenue attribution and orchestration health report.

Our agent network:
- Agent 1 (Signal/Detection layer): [e.g., Intent monitoring agent — monitors G2, Bombora, web behavior signals]
- Agent 2 (Enrichment layer): [e.g., Account enrichment agent — pulls firmographic + technographic data]
- Agent 3 (Personalization layer): [e.g., Message personalization agent — writes custom outreach]
- Agent 4 (Outbound execution layer): [e.g., AI SDR agent — executes email/LinkedIn/phone sequences]
- Agent 5 (Qualification layer): [e.g., Inbound qualification agent — scores and routes responses]
- Agent 6 (Nurture layer): [e.g., Long-cycle nurture agent — manages 6-18 month pipeline]

Monthly data:
- Total accounts entered agent network: [X]
- Accounts reaching human sales handoff: [X]
- Meetings booked: [X]
- Pipeline created: $[X]M
- Revenue closed from agent-touched accounts: $[X]K

Produce:
1. CROSS-AGENT ATTRIBUTION MAP — For each pipeline dollar, what % credit goes to each agent in the chain?
2. ORCHESTRATION HEALTH SCORECARD — Where does the agent chain break down? What are the dropout rates at each agent handoff?
3. AGENT CHAIN VELOCITY METRICS — How fast does an account move from detection to booked meeting through the agent network?
4. FAILURE MODE ANALYSIS — What are the top 3 reasons the agent chain fails to convert a qualifying account?
5. OPTIMIZATION PRIORITY MATRIX — Which single agent upgrade produces the highest pipeline lift?

Deliver the output as a dashboard I can plug into HubSpot, Salesforce, or Google Sheets.

## Advanced Customizable Version

# ROLE
You are a Senior Revenue Engineering Analyst specializing in agentic GTM systems, multi-agent AI orchestration, and B2B revenue attribution. You sit at the intersection of marketing operations, data science, and AI systems design. You understand LangChain, CrewAI, and custom orchestration architectures at a technical level, but translate insights into revenue language for CMO and CRO audiences. You have built attribution models for distributed AI systems where no single agent owns the outcome — the pipeline is a product of agent collaboration.

# MISSION
Build a complete Multi-Agent Marketing Orchestration Analytics System for the company below. This system must: (1) attribute pipeline and revenue across every agent in the chain using a defensible model, (2) measure orchestration health — handoff quality, failure rates, latency, and recovery — at each node, (3) identify the single highest-leverage intervention to improve total pipeline throughput, and (4) produce a continuously updatable monitoring dashboard that alerts on orchestration degradation before it impacts revenue.

# COMPANY CONTEXT
- Company: [Company Name]
- Stage: [Series A/B/C/Public]
- ARR: $[X]M, growing [X]% YoY
- ACV: $[X]K average deal size
- Sales cycle: [X] months average
- ICP: [Brief description — e.g., "VP/Director RevOps at 200-2000 employee B2B SaaS companies"]
- Monthly pipeline target: $[X]M
- CRM: [HubSpot / Salesforce / other]
- Data warehouse: [Snowflake / BigQuery / Redshift / none]
- Agent orchestration framework: [LangChain / CrewAI / n8n / Zapier / custom / vendor tools]
- Primary attribution model today: [First-touch / Last-touch / Multi-touch / None]

# AGENT NETWORK ARCHITECTURE

Define each agent in your network using this schema:

AGENT NODE CARD:
- Agent ID: [A1, A2, A3...]
- Agent Name: [Descriptive name]
- Layer: [Detection / Enrichment / Personalization / Execution / Qualification / Nurture / Handoff]
- Primary input: [What triggers this agent — e.g., "account exceeds intent score threshold of 70"]
- Primary output: [What this agent produces — e.g., "personalized email sequence + LinkedIn connection request"]
- Destination: [Where output goes — e.g., "passed to A4 Outbound Execution Agent"]
- Monthly input volume: [X] accounts/triggers/events
- Monthly output volume: [X] outputs produced (completion rate = output/input)
- Tool/API: [Clay / Apollo / Claude API / HubSpot workflows / Salesforce flows / custom]
- Monthly cost: $[X]
- Human oversight: [X] hrs/month

[Repeat for all agents in network]

# ANALYTICAL FRAMEWORK

## Module 1: Cross-Agent Revenue Attribution Model

**The Agentic Attribution Problem:**
Traditional attribution (first-touch, last-touch, linear) assumes touchpoints are independent. In a multi-agent network, agents are interdependent — Agent 2's output quality determines Agent 3's success rate. Standard models undercount upstream agents and overcount execution agents. You must build a **Causal Chain Attribution Model** instead.

**Causal Chain Attribution Methodology:**

STEP 1 — DEFINE THE ATTRIBUTION CHAIN
Map every agent's contribution type:
- ENABLING agents (without their output, downstream agents cannot run): [List A1, A2...]
- CONVERTING agents (their output directly creates buyer action — click, reply, meeting): [List]
- SUSTAINING agents (their output keeps accounts in-funnel over long cycles): [List]

STEP 2 — MEASURE MARGINAL CONTRIBUTION
For each agent, calculate the counterfactual: "What would pipeline look like if this agent were removed?"

MARGINAL CONTRIBUTION FORMULA per agent:
- Baseline pipeline (all agents running): $[X]M/month
- Simulated pipeline (agent removed): $[X]M/month [estimate using historical periods, A/B tests, or agent shutdown logs]
- Marginal contribution: Baseline - Simulated = $[X]K
- Attribution share: Marginal contribution / Sum of all marginal contributions = [X]%

STEP 3 — BUILD ATTRIBUTION TABLE
Produce a table for each pipeline dollar:

| Agent | Layer | Marginal Contribution ($) | Attribution Share (%) | Type |
|-------|-------|--------------------------|----------------------|------|
| A1 Intent Monitor | Detection | $[X]K | [X]% | Enabling |
| A2 Enrichment | Enrichment | $[X]K | [X]% | Enabling |
| A3 Personalizer | Personalization | $[X]K | [X]% | Converting |
| A4 AI SDR | Execution | $[X]K | [X]% | Converting |
| A5 Qualifier | Qualification | $[X]K | [X]% | Converting |
| A6 Nurture | Nurture | $[X]K | [X]% | Sustaining |
| **TOTAL** | | **$[X]M** | **100%** | |

STEP 4 — REVENUE PER AGENT DOLLAR INVESTED
For each agent: Pipeline attributed / Agent cost = Pipeline ROI multiplier
Rank agents by pipeline-per-dollar to set investment priorities.

## Module 2: Orchestration Health Monitoring

**The Agent Chain Funnel:**
Track account progression through the agent network exactly like a marketing funnel — with explicit conversion rates at each node.

AGENT CHAIN FUNNEL FORMAT:

[Input Trigger Pool: X accounts/month]
        ↓ [A1 Detection Agent: X% completion rate]
[Qualified Intent Signals: X accounts]
        ↓ [A1→A2 Handoff Quality Score: X/100]
[Enriched Accounts: X accounts]  ← X% dropout (missing data fields)
        ↓ [A2→A3 Handoff Quality Score: X/100]
[Personalized Sequences Ready: X accounts] ← X% dropout (personalization failed)
        ↓ [A3→A4 Handoff Quality Score: X/100]
[Outbound Sequences Launched: X accounts] ← X% dropout (deliverability/blocking)
        ↓ [Positive Replies / Intent Signals: X]
[Qualified Responses: X accounts] ← X% dropout (A5 qualification failure)
        ↓
[Human SDR Handoff: X accounts]
        ↓
[Meetings Booked: X] ← X% show rate
[Pipeline Created: $XM]

HANDOFF QUALITY SCORECARD (for each A→B transition):

**Handoff: [Agent A] → [Agent B]**

DATA COMPLETENESS SCORE (0-100):
- Required fields from A that B needs: [list fields]
- % of handoffs with all required fields populated: [X]%
- Most common missing field: [field name] — impact: [what breaks without it]
- Score: [X]/100

TIMING SCORE (0-100):
- Ideal handoff latency (A output → B starts): [X] minutes
- Actual median latency: [X] minutes
- P95 latency (worst case): [X] minutes
- Timeout/expiration rate (B never starts because A output expired): [X]%
- Score: [X]/100

CONTEXT INTEGRITY SCORE (0-100):
- Account context preserved from original trigger to handoff: [X]%
- Enrichment data drift (stale data rate): [X]%
- Scoring/ranking preserved accurately: [X]%
- Score: [X]/100

COMPOSITE HANDOFF HEALTH: (Data × 0.4) + (Timing × 0.3) + (Context × 0.3) = [X]/100
- Green: ≥85 | Yellow: 70-84 | Red: <70 — auto-alert on Red

## Module 3: Orchestration Failure Mode Analysis

Categorize every agent chain failure into one of five failure modes and quantify pipeline impact:

**FAILURE MODE TAXONOMY:**

1. **STARVATION** — Agent receives insufficient or no input
   - Root cause: Upstream agent underperforming, trigger threshold too high, data source outage
   - Detection signal: Agent input volume drops >25% week-over-week
   - Pipeline impact calculation: Accounts lost × conversion rate × ACV = $[X]K/month lost
   - Recovery playbook: [Specific steps — e.g., "lower intent threshold from 70 to 55, add Bombora as secondary signal source"]

2. **CONTAMINATION** — Agent receives low-quality input that poisons downstream
   - Root cause: Enrichment agent pulling stale/incorrect data, ICP signal mismatch
   - Detection signal: Downstream conversion rate drops without input volume drop
   - Pipeline impact: [X]% conversion rate drop × [X] accounts × ACV = $[X]K/month lost
   - Recovery playbook: [Specific steps — e.g., "add ICP re-validation step between A2 and A3, reject accounts with >2 critical field mismatches"]

3. **BOTTLENECK** — Agent processing creates latency spike that kills buyer responsiveness
   - Root cause: API rate limits, token quota exhaustion, external data source slowdowns
   - Detection signal: Handoff latency P95 exceeds [X] minutes; reply rate drops [X]% with each hour of delay
   - Pipeline impact: Speed-to-lead degradation × [X] accounts = $[X]K pipeline at risk
   - Recovery playbook: [Specific steps — e.g., "implement priority queue for high-intent (score >85) accounts, process within 4 minutes; batch lower-intent overnight"]

4. **HALLUCINATION CASCADE** — AI agent produces incorrect output that cascades as factual input to downstream agents
   - Root cause: LLM hallucination in personalization agent inventing contact details, company facts, or use cases
   - Detection signal: Reply negative sentiment spike; spam complaint rate increase; "that's wrong" responses
   - Pipeline impact: [X]% of sequences affected × [X] accounts × ACV = $[X]K pipeline burned
   - Recovery playbook: [Specific steps — e.g., "add output validation layer between A3 and A4 that fact-checks company name, title, and product references against CRM record before send"]

5. **LOOP FAILURE** — Agent network enters infinite retry or deadlock state
   - Root cause: Orchestration logic error, missing exit conditions, external API returning ambiguous responses
   - Detection signal: Same account processed >3x without progression; orchestration logs show circular routing
   - Pipeline impact: [X]% of orchestration runs affected × operational cost = $[X]K wasted + pipeline delay
   - Recovery playbook: [Specific steps — e.g., "implement maximum retry limit of 3 per account per 7-day window with mandatory human review queue for loop-flagged accounts"]

**FAILURE MODE PRIORITY MATRIX:**

| Failure Mode | Frequency (% of runs) | Pipeline Impact ($) | Ease of Fix (1-5) | Fix Priority |
|-------------|----------------------|--------------------|--------------------|-------------|
| Starvation | [X]% | $[X]K | [X] | [High/Med/Low] |
| Contamination | [X]% | $[X]K | [X] | |
| Bottleneck | [X]% | $[X]K | [X] | |
| Hallucination Cascade | [X]% | $[X]K | [X] | |
| Loop Failure | [X]% | $[X]K | [X] | |

Address failures in priority order: highest pipeline impact × highest ease of fix first.

## Module 4: Agent Chain Velocity Analytics

Speed is a competitive weapon in agentic GTM. Measure end-to-end velocity:

**AGENT CHAIN VELOCITY DASHBOARD:**

DEFINITION: Time from initial trigger (account enters intent threshold) to booked meeting.

TARGET VELOCITY: [X] hours (industry benchmark for high-performing agentic GTM: <4 hours for high-intent accounts)

VELOCITY BREAKDOWN BY STAGE:
- A1 Detection → Alert fired: [X] minutes (target: <15 min)
- Alert fired → A2 Enrichment complete: [X] minutes (target: <10 min)
- A2 complete → A3 Personalization complete: [X] minutes (target: <20 min)
- A3 complete → A4 First outbound touch: [X] minutes (target: <5 min)
- First touch → First positive response: [X] hours (median)
- Positive response → A5 qualification complete: [X] minutes (target: <10 min)
- Qualification complete → Human SDR notified: [X] minutes (target: <2 min)
- SDR notified → Meeting booked: [X] hours (median)

**TOTAL END-TO-END VELOCITY: [X] hours**

VELOCITY COHORT ANALYSIS (revenue impact of speed):
Segment accounts by time-to-first-outbound:
- <1 hour: [X] accounts, [X]% meeting rate, $[X]K pipeline
- 1-4 hours: [X] accounts, [X]% meeting rate, $[X]K pipeline
- 4-24 hours: [X] accounts, [X]% meeting rate, $[X]K pipeline
- >24 hours: [X] accounts, [X]% meeting rate, $[X]K pipeline

Revenue impact of reducing velocity from [current] to [target]:
- Accounts per month at [target] speed: [X]
- Meeting rate improvement at target speed: +[X]%
- Incremental meetings: [X]
- Incremental pipeline: $[X]K/month

## Module 5: Optimization Priority Matrix

Identify the single highest-leverage intervention in the agent network:

**SENSITIVITY ANALYSIS — What happens if each agent improves by 20%?**

For each agent, calculate pipeline impact of a 20% performance improvement:

| Agent | Current Performance Metric | +20% Scenario | Incremental Pipeline | Investment Required |
|-------|--------------------------|---------------|---------------------|---------------------|
| A1 Intent Monitor | [X]% signal accuracy | [Y]% accuracy | +$[X]K/month | $[X]K |
| A2 Enrichment | [X]% field completion | [Y]% completion | +$[X]K/month | $[X]K |
| A3 Personalizer | [X]% reply rate | [Y]% reply rate | +$[X]K/month | $[X]K |
| A4 AI SDR | [X]% sequence completion | [Y]% completion | +$[X]K/month | $[X]K |
| A5 Qualifier | [X]% qualification accuracy | [Y]% accuracy | +$[X]K/month | $[X]K |
| A6 Nurture | [X]% re-engagement rate | [Y]% rate | +$[X]K/month | $[X]K |

**TOP RECOMMENDATION:** Improve [Agent X] — produces $[X]K incremental pipeline at $[X]K investment cost = [X]x ROI.

Specific improvement actions for top-priority agent:
1. [Specific technical change — e.g., "Switch from GPT-4o-mini to Claude 3.5 Sonnet for personalization; projected reply rate lift: +22% based on A/B test in weeks 1-2"]
2. [Specific data change — e.g., "Add LinkedIn Sales Navigator data to enrichment layer; reduces missing seniority field rate from 34% to 6%"]
3. [Specific orchestration change — e.g., "Implement priority routing for accounts with Bombora intent score >80 — process within 15 min instead of batch nightly"]

# OUTPUT DELIVERABLES

Produce in this exact order:

1. **Agent Network Architecture Map** — visual description of agent chain with input/output flows
2. **Cross-Agent Attribution Table** — pipeline credit by agent using causal chain model
3. **Orchestration Health Scorecard** — handoff quality scores for every A→B transition
4. **Agent Chain Funnel** — dropout rates at each node with pipeline value lost per dropout
5. **Failure Mode Analysis Report** — top failure modes ranked by pipeline impact with recovery playbooks
6. **Velocity Analytics Dashboard** — end-to-end speed breakdown with revenue impact of improvement
7. **Optimization Priority Matrix** — ranked list of interventions by incremental pipeline per dollar invested
8. **30-60-90 Day Roadmap** — specific actions to improve orchestration health and pipeline throughput

Format all tables for direct paste into Google Sheets. Format all dashboards as text-based tables with clear headers. Use dollar amounts for every metric where possible — avoid vague "efficiency" claims.

## Example Input/Output

**Input Example:**

Company: Meridian Data (B2B SaaS, Series B, $22M ARR, $47K ACV)
ICP: Director/VP Data Engineering at 500-5000 employee companies
Agent network: 5 agents
- A1: Bombora + G2 intent monitor (detects accounts crossing intent score 65+)
- A2: Clay enrichment agent (pulls tech stack, headcount, funding, contacts)
- A3: Claude-based personalization agent (writes custom 3-touch email sequence)
- A4: Apollo AI outbound agent (sends emails + LinkedIn messages on schedule)
- A5: HubSpot AI qualification agent (scores inbound responses, routes >70-score to SDR)
Monthly data: 820 accounts entered, 34 meetings booked, $1.6M pipeline created

---

**Output Example:**

**MERIDIAN DATA — MULTI-AGENT ORCHESTRATION ANALYTICS REPORT**
*Month: August 2026 | Report generated by: Multi-Agent Analytics Engine*

---

**AGENT CHAIN FUNNEL:**

[820 accounts triggered by intent threshold]
        ↓ A1 Detection: 94% completion (773 passed)
[773 qualified intent signals]
        ↓ A1→A2 handoff health: 81/100 (Yellow)
[698 fully enriched accounts] ← 75 dropout (9.7% — missing contact data)
        ↓ A2→A3 handoff health: 88/100 (Green)
[671 personalized sequences ready] ← 27 dropout (3.9% — ICP mismatch on personalization)
        ↓ A3→A4 handoff health: 93/100 (Green)
[671 sequences launched]
        ↓ A4 outbound: 312 positive engagement signals (46.5% engagement rate)
[312 signals sent to A5 qualification]
        ↓ A5 qualification: 89 qualified responses (28.5% qualification rate)
[89 human SDR handoffs]
        ↓ SDR meeting booking: 38.2% meeting rate
[34 meetings booked → $1.6M pipeline]

**Pipeline Lost to Orchestration Failures:**
- A1→A2 dropout (75 accounts): 75 × 4.1% × $47K = $144K pipeline/month lost
- A2→A3 dropout (27 accounts): 27 × 4.1% × $47K = $52K pipeline/month lost
- **Total orchestration failure cost: $196K pipeline/month**

---

**CROSS-AGENT ATTRIBUTION TABLE:**

| Agent | Layer | Marginal Contribution | Attribution % | Pipeline $ |
|-------|-------|----------------------|---------------|-----------|
| A1 Intent Monitor | Detection | $312K | 19.5% | $312K |
| A2 Enrichment | Enrichment | $271K | 16.9% | $271K |
| A3 Personalizer | Personalization | $445K | 27.8% | $445K |
| A4 AI SDR | Execution | $398K | 24.9% | $398K |
| A5 Qualifier | Qualification | $174K | 10.9% | $174K |
| **TOTAL** | | **$1.6M** | **100%** | **$1.6M** |

**Pipeline per Agent Dollar Invested:**
- A3 Personalizer: $445K / $2,100 = 212x — Scale immediately
- A4 AI SDR: $398K / $3,400 = 117x — Scale
- A1 Intent Monitor: $312K / $1,800 = 173x — Scale
- A2 Enrichment: $271K / $2,800 = 97x — Optimize (fix contact data dropout)
- A5 Qualifier: $174K / $600 = 290x — Scale aggressively

---

**TOP OPTIMIZATION RECOMMENDATION:**

Fix A1→A2 handoff contact data dropout. Current cost: $144K pipeline/month lost.
Fix: Add LinkedIn Sales Navigator API to A2 enrichment as fallback for missing contacts.
Cost: $1,200/month additional.
Expected recovery: 60 of 75 monthly dropout accounts reach A3.
Expected pipeline lift: 60 × 4.1% × $47K = **$115K/month additional pipeline**
**ROI: 96x. Payback: <1 week.**

## Success Metrics

- **Attribution clarity**: Every dollar of pipeline has an agent attribution breakdown within 30 days of system deployment
- **Orchestration health**: All agent handoffs achieve Green status (≥85/100) within 60 days
- **Dropout reduction**: Total agent chain dropout rate reduced by ≥30% within 90 days
- **Velocity target**: High-intent accounts (score >80) reach first outbound touch within 4 hours for ≥90% of accounts
- **Failure mode elimination**: Zero Hallucination Cascade failures in production; Bottleneck failures <2% of runs
- **Optimization ROI**: First optimization recommendation implemented produces ≥5x ROI within 45 days

## Related Prompts

- [AI Marketing Agent ROI Measurement](./AI-Powered-B2B-SaaS-Marketing-AI-Agent-ROI-Measurement-&-Cost-Per-Outcome-Revenue-Intelligence-Engine.md)
- [Agentic Marketing Operations Performance Analytics](./AI-Powered-B2B-SaaS-Agentic-Marketing-Operations-Performance-Analytics-&-AI-Agent-Portfolio-Optimization-Revenue-Intelligence-Engine.md)
- [Demand Generation Waterfall Architecture](../../04_Demand-&-Lead-Generation-&-Growth/Demand-Generation-Operations/AI-Powered-B2B-SaaS-Demand-Generation-Waterfall-Architecture-&-Marketing-Funnel-Conversion-Intelligence-Engine.md)
- [Revenue Attribution Model Architecture](../Attribution-&-Revenue-Analytics/AI-Powered-B2B-Revenue-Attribution-Model-Architecture-&-Unified-Measurement-Framework-Intelligence-Engine.md)

## Integration Tips

- **HubSpot**: Create custom contact/company properties for each agent interaction timestamp (e.g., `agent_a1_triggered_date`, `agent_a3_sequence_sent_date`). Build a calculated property for "total agent chain velocity (hours)" to track speed by cohort. Use workflow enrollment history to reconstruct agent chain funnels monthly.
- **Salesforce**: Build a custom object "Agent Orchestration Log" with lookup to Contact and Opportunity. Log each agent's action, timestamp, output quality score, and handoff status. Use this for cross-agent attribution in reports.
- **Snowflake / BigQuery**: Create an `agent_events` table with columns: account_id, agent_id, event_type (input_received, output_produced, handoff_sent, handoff_received, failure), timestamp, quality_score, output_size. Join to CRM opportunity table for pipeline attribution.
- **n8n / Zapier**: Add a logging step to every agent workflow that writes agent events to your data warehouse or a Google Sheet "Agent Activity Log" in real time. This creates the raw data needed for orchestration health monitoring without custom infrastructure.
- **Slack**: Create a `#agent-orchestration-alerts` channel. Trigger automated alerts when: any handoff health score drops below 70, end-to-end velocity for high-intent accounts exceeds 6 hours, or dropout rate at any node exceeds 15% in a 24-hour window.
- **Looker / Tableau**: Build an "Agent Chain Health" dashboard with: (1) Sankey diagram showing account flow through agent network, (2) handoff health heatmap by agent pair, (3) velocity distribution histogram, (4) failure mode trend line by week. Refresh daily from your data warehouse.
- **Clay**: Use Clay's built-in run logs as a proxy for A2 enrichment completion rates. Export Clay table activity logs monthly to calculate enrichment completion rate, field coverage, and time-to-complete.

## Troubleshooting

**Problem: Agent interactions are not logged, making cross-agent attribution impossible**
Solution: Retrofit logging into existing agent workflows before building attribution models. Add a single Zapier step or webhook call at the start and end of each agent's workflow that writes to a central Google Sheet with columns: timestamp, account_id, agent_id, action (start/complete/fail), output_summary. Even 30 days of this data is sufficient to build baseline attribution. Do not attempt attribution modeling without at least 4 weeks of clean event logs — you will produce misleading results that destroy credibility with finance.

**Problem: The "best agent" by attribution is actually just the last agent before conversion, creating a last-touch bias in causal analysis**
Solution: Apply the enabling/converting/sustaining taxonomy before running any attribution calculation. Enabling agents (detection, enrichment) should never receive less than 15% combined credit — if your model produces this, your counterfactual estimates are wrong. Run a two-week "agent blackout test" by temporarily disabling A1 (intent monitor) for a cohort and measuring pipeline impact directly. This empirical counterfactual corrects for modeling bias and produces board-defensible numbers.

**Problem: Hallucination cascade failures are hard to detect because AI agents confidently produce incorrect outputs**
Solution: Implement an automated output validation layer between the personalization agent (A3) and the execution agent (A4) that checks three things: (1) company name in email body matches CRM company field, (2) contact title in email matches enrichment data within one job level, (3) product claim in email matches approved messaging library (string matching or a fast classifier prompt). Flag any email failing >1 check for human review before send. This single control eliminates >80% of hallucination cascade failures at a cost of roughly 200ms per sequence.

## Version History
- v1.0: Initial creation (auto-generated)
