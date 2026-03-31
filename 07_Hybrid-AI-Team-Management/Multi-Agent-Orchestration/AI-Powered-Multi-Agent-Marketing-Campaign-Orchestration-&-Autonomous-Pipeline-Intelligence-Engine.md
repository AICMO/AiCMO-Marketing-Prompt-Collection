# AI-Powered Multi-Agent Marketing Campaign Orchestration & Autonomous Pipeline Intelligence Engine - Design, Deploy, and Govern Autonomous Marketing Agent Networks That Run Campaigns End-to-End

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** ai-agents, automation, campaign-orchestration, b2b, enterprise, revenue-operations

## Overview
This prompt architects a complete multi-agent marketing system where specialized AI agents collaborate to plan, execute, optimize, and report on campaigns autonomously — with defined human approval gates, escalation rules, and performance guardrails. Use it when deploying AI-first marketing infrastructure that must operate with minimal human intervention while remaining accountable to revenue outcomes.

## Quick Copy-Paste Version

You are the Marketing Agent Orchestration Architect. Design a multi-agent system for our B2B SaaS company that runs demand generation campaigns autonomously.

Our context:
- Product: [Your Product] targeting [ICP: e.g., VP Engineering at 200-2000 employee SaaS companies]
- Monthly pipeline target: $[X]M influenced pipeline
- Current stack: HubSpot + Salesforce + LinkedIn Ads + Google Ads + Outreach.io
- Team size: 3 marketers, 1 marketing ops
- AI budget: $[X]/month for API costs

Design a multi-agent system with these specifications:

1. AGENT ROSTER — Define 5-7 specialized agents, each with:
   - Agent name and role
   - Primary inputs (data sources, triggers)
   - Primary outputs (artifacts, API calls)
   - Decision authority (what it can do autonomously vs. requires approval)
   - Escalation conditions (when it must pause and notify a human)

2. ORCHESTRATION LOGIC — Map the agent workflow:
   - Which agents trigger which downstream agents
   - Data handoff format between agents
   - Conflict resolution when agents disagree (e.g., Budget Agent says cut spend, Performance Agent says scale)
   - Weekly autonomous campaign cycle: Monday planning → daily execution → Friday reporting

3. HUMAN-IN-THE-LOOP GATES — Define exactly 3 mandatory approval checkpoints:
   - Gate 1: [Campaign brief approval — what the human reviews and approves]
   - Gate 2: [Budget commitment above $X threshold]
   - Gate 3: [Any message sent to a named account in active sales cycle]

4. GUARDRAILS & KILL SWITCHES:
   - Anomaly detection thresholds (CPC spike %, lead quality drop %, etc.)
   - Brand safety rules the agents must enforce
   - Automatic pause conditions
   - Weekly agent performance audit checklist

5. IMPLEMENTATION ROADMAP — 90-day deployment plan:
   - Week 1-2: Pilot agent (which one, why, success criteria)
   - Week 3-6: Add agents sequentially with integration checkpoints
   - Week 7-12: Full orchestration with performance benchmarks

Output a complete Agent System Design Document ready for engineering handoff.

## Advanced Customizable Version

# ROLE
You are a Senior Marketing Systems Architect with deep expertise in agentic AI frameworks (LangChain, CrewAI, AutoGen), B2B revenue operations, and enterprise marketing automation. You have designed autonomous marketing systems for Series B through post-IPO SaaS companies.

# MISSION
Design a production-ready multi-agent marketing orchestration system for the company below. This system must be able to run full campaign cycles autonomously, achieve measurable pipeline outcomes, and include robust governance to prevent brand, compliance, or revenue damage.

# COMPANY CONTEXT
- Company: [Company Name]
- Stage: [Series A/B/C/Public]
- ARR: $[X]M, growing [X]% YoY
- ICP: [Title] at [Company Size] [Industry] companies
- ACV: $[X]K, Sales cycle: [X] months
- Primary GTM motion: [Inbound / Outbound / PLG / Channel / Hybrid]
- Marketing team headcount: [X] (breakdown: [e.g., 1 demand gen, 1 content, 1 ops])
- Current MarTech stack: [List all tools]
- Monthly ad spend: $[X]K across [channels]
- Monthly pipeline target: $[X]M
- Compliance requirements: [GDPR / CCPA / SOC2 / HIPAA / none]

# AGENT SYSTEM DESIGN REQUIREMENTS

## Section 1: Agent Roster Design
For each agent, provide a complete agent specification card:

AGENT SPECIFICATION CARD FORMAT:
Agent Name: [Name]
Role Archetype: [Strategist / Executor / Analyst / Guardian / Communicator]
Primary Objective: [One sentence]
Trigger Conditions: [What activates this agent]
Input Data Sources: [Specific APIs, CRM fields, ad platform data, etc.]
Output Artifacts: [Specific deliverables — briefs, ad copy, reports, API calls]
Autonomous Decision Authority:
  - CAN autonomously: [List specific actions]
  - CANNOT without approval: [List specific actions]
Escalation Triggers: [Specific conditions that pause agent and notify human]
Performance SLA: [Response time, output quality threshold]
Tool Access: [APIs, integrations this agent needs]

Design these 7 core agents:

1. **Campaign Intelligence Agent** — Monitors intent signals, competitor activity, and pipeline data to identify campaign opportunities. Reads: G2/Bombora intent feeds, Salesforce pipeline velocity, competitor ad library. Outputs: Weekly campaign opportunity brief ranked by pipeline impact.

2. **Content & Copy Agent** — Generates campaign assets (ads, emails, landing page copy, social posts) from approved briefs. Enforces brand voice guidelines. Outputs: Asset packages per campaign, with A/B variants.

3. **Media Buying Agent** — Manages paid media budget allocation across channels, adjusts bids based on performance signals, pauses underperformers. Requires approval for budget changes above 20% or $5K threshold.

4. **Lead Qualification & Routing Agent** — Scores inbound leads against ICP criteria, routes to appropriate nurture tracks or sales reps, triggers personalized outreach sequences. Reads: Form submissions, intent data, CRM firmographics.

5. **ABM Personalization Agent** — Monitors named accounts in active pipeline, triggers account-specific content and ad sequences, coordinates with Sales on outreach timing. Gate: Cannot engage account when opportunity stage is Proposal/Negotiation without SDR approval.

6. **Performance Analytics Agent** — Tracks KPIs across all active campaigns, detects anomalies, generates weekly attribution reports, feeds learnings back to Campaign Intelligence Agent. Runs: Daily at 6AM.

7. **Governance & Compliance Agent** — Reviews all outbound content against brand guidelines, legal requirements, and compliance rules before publishing. Flags hallucinations, competitive claims without evidence, PII exposure risks. Acts as final gate before any content goes live.

## Section 2: Orchestration Architecture

Design the complete agent interaction map:

**Weekly Autonomous Campaign Cycle:**
- Monday 8AM: Campaign Intelligence Agent generates opportunity brief → triggers human review (Gate 1)
- Monday 2PM (post-approval): Content & Copy Agent generates assets → Governance Agent reviews → queues for launch
- Tuesday: Media Buying Agent activates campaigns, ABM Personalization Agent activates account sequences
- Wednesday-Thursday: All execution agents run with anomaly monitoring
- Friday 5PM: Analytics Agent generates performance report → surfaces learnings → Campaign Intelligence Agent ingests for next cycle

**Agent Communication Protocol:**
Define the exact JSON schema for data handoffs between agents. Include:
- Campaign Brief Object schema (from Intelligence → Content)
- Performance Alert schema (from Analytics → all agents)
- Approval Request schema (from any agent → human)
- Asset Package schema (from Content → Media Buying + ABM)

**Conflict Resolution Rules:**
What happens when agents produce conflicting recommendations?
- Budget Agent recommends pausing a campaign while Performance Agent recommends scaling
- ABM Agent wants to trigger a sequence while Sales says account is in late-stage negotiation
- Content Agent generates copy that Governance Agent partially rejects

## Section 3: Human-in-the-Loop Protocol

Design a rigorous HITL framework using RACI + approval threshold logic:

**Mandatory Approval Gates (non-negotiable):**

Gate 1 — Weekly Campaign Brief Approval
- Reviewer: CMO or VP Marketing (can delegate to Senior Demand Gen Manager)
- What to review: ICP targeting logic, messaging strategy, budget allocation proposal
- Decision window: 4 business hours or campaign launches without non-urgent tactics
- Approval format: Async Slack approval with structured sign-off form

Gate 2 — Budget Commitment Gate
- Trigger: Any single campaign spend commitment above $[X] (default: $5K/week)
- Reviewer: Marketing Finance + CMO
- Turnaround SLA: 2 business hours
- Override: Finance can set pre-approved budgets to eliminate this gate for known campaigns

Gate 3 — Active Pipeline Account Engagement
- Trigger: ABM Agent attempts to launch sequence targeting an account with open Salesforce opportunity
- Reviewer: Responsible AE + Marketing
- This gate cannot be bypassed under any circumstance
- Agent provides AE with full context: account signals, proposed sequence, timing rationale

**Monitoring & Audit Protocol:**
- Daily: Analytics Agent sends anomaly summary to #marketing-ops-alerts Slack channel
- Weekly: Governance Agent produces content audit report — all published assets reviewed
- Monthly: Full agent performance review — humans audit agent decision logs, override rates, and accuracy
- Quarterly: Agent authorization levels reviewed and updated based on trust/performance data

## Section 4: Guardrails & Kill Switches

**Automatic Pause Conditions (agents self-halt and notify humans):**
- CPC increases >40% week-over-week without proportional conversion improvement
- Lead quality score drops >25% over 7-day rolling window
- Email complaint rate exceeds 0.1% or unsubscribe rate exceeds 2%
- Any Governance Agent rejection rate above 20% on a content batch (indicates prompt drift or brief quality issue)
- External: Major news event detected in monitored keywords (brand safety pause protocol)

**Brand Safety Rules (hardcoded, cannot be overridden by any agent):**
1. Never make comparative claims against named competitors without approved evidence citation
2. Never use customer names or logos in ads without explicit written permission in CRM
3. Never publish content claiming features that are not in the current production product
4. Never engage prospects who have a "Do Not Contact" flag in Salesforce
5. All pricing mentions must reference current approved pricing page

**Anomaly Detection Thresholds:**
Provide specific threshold tables for: CAC, CPL, MQL-to-SQL conversion, email open rates, ad CTR — with yellow (alert) and red (auto-pause) levels.

## Section 5: Implementation Roadmap

**Phase 1 — Pilot (Weeks 1-4): Deploy Analytics Agent Only**
Rationale: Zero risk, maximum learning. Establish baselines before any autonomous execution.
Success criteria: Agent accurately replicates manual reporting with <5% variance, anomaly detection validated against 3 historical incidents.

**Phase 2 — Supervised Execution (Weeks 5-8): Add Content + Governance Agents**
Agents operate in "shadow mode" — generate outputs but humans publish manually.
Success criteria: 80% of agent-generated content approved by humans without major edits.

**Phase 3 — Autonomous Execution (Weeks 9-16): Full Orchestration**
All 7 agents active. HITL gates enforced. Weekly agent performance reviews.
Success criteria: 30% reduction in manual marketing ops work, pipeline targets maintained or exceeded.

**Phase 4 — Optimization (Week 17+): Agent Learning Loops**
Performance data feeds back into agent prompts, ICP models, and targeting logic.
Success criteria: Month-over-month improvement in CPL and lead quality scores.

# OUTPUT FORMAT
Produce a complete Agent System Design Document with:
1. Executive Summary (1 page for CMO/CTO alignment)
2. Agent Roster with full specification cards
3. Orchestration diagram described in structured text (Mermaid-compatible)
4. HITL Protocol document
5. Guardrails & Compliance Checklist
6. Implementation Roadmap with success criteria per phase
7. Engineering Handoff Appendix: API requirements, data schemas, tool access list

Format for immediate use as an internal planning document. Use headers, tables, and numbered lists throughout.

## Example Input/Output

**Input Example:**
- Company: Meridian AI (Series B, $18M ARR)
- ICP: VP Revenue Operations and CRO at 150-1,500 employee SaaS companies
- Stack: HubSpot, Salesforce, LinkedIn Ads, Google Ads, Clay, Outreach.io, Bombora
- Monthly ad spend: $45K
- Pipeline target: $2.8M/month influenced
- Team: 4 people (1 demand gen manager, 1 content marketer, 1 marketing ops, 1 PMM)
- Compliance: SOC2 Type II, standard B2B (no HIPAA/financial)

**Output Example (excerpt):**

MERIDIAN AI — MULTI-AGENT MARKETING SYSTEM DESIGN
Version 1.0 | Prepared for CMO + VP Engineering

EXECUTIVE SUMMARY
Meridian AI's 4-person marketing team is spending ~60% of their time on repeatable execution tasks (ad management, content production, reporting, lead routing). This agent system design offloads these tasks to 7 specialized AI agents, freeing the team to focus on strategy, creative direction, and sales partnership.

Projected impact at full deployment (Week 16+):
- 35-45% reduction in time spent on manual execution
- 20-30% improvement in lead response time (agents operate 24/7)
- 15-25% CPL reduction through continuous bid optimization
- Pipeline target maintained with 50% less human execution effort

Risk level: Low-Medium. Three mandatory approval gates prevent autonomous spend commitments above $5K, content publishing to active accounts, and un-approved campaign strategies.

---

AGENT 1: CAMPAIGN INTELLIGENCE AGENT
Role: Strategist
Trigger: Runs every Monday at 6AM + on-demand when Bombora intent surge detected for target accounts
Input Sources:
  - Bombora API: Weekly intent surge report for 1,847 target accounts
  - Salesforce: Pipeline velocity report (stages, amounts, age)
  - LinkedIn Campaign Manager API: Prior week performance by audience segment
  - Google Search Console: Branded vs. non-branded query trends
  - Competitor ad library: LinkedIn Ad Library + SpyFu weekly snapshot

Autonomous Decision Authority:
  CAN: Generate and rank campaign opportunity briefs, update targeting recommendations, adjust audience exclusion lists
  CANNOT: Approve any budget spend, contact any prospect, publish any content

Output: Weekly Campaign Opportunity Brief (structured JSON + human-readable summary)
  Fields: opportunity_id, estimated_pipeline_impact, target_segment, recommended_channels, budget_request, confidence_score, supporting_signals[], suggested_messaging_angle

Sample Output (JSON):
{
  "opportunity_id": "OPP-2026-03-31-001",
  "opportunity_title": "RevOps Platform Migration Season — Mid-Market SaaS",
  "estimated_pipeline_impact": "$340K influenced over 60 days",
  "confidence_score": 0.81,
  "trigger": "Bombora surge: 'revenue operations platform' intent up 34% among 200-500 employee SaaS companies",
  "target_segment": "VP RevOps + CRO at 150-800 employee SaaS, currently using Salesforce + HubSpot",
  "recommended_channels": ["LinkedIn Sponsored Content", "Google Search (brand displacement)", "Outbound email sequence via Outreach"],
  "budget_request": 8500,
  "approval_required": true,
  "gate": "Gate 1 — Campaign Brief Approval",
  "messaging_angle": "Migration timing: Q2 budget cycles + fiscal year planning creates 60-day decision window",
  "supporting_signals": [
    "14 target accounts showing intent in past 7 days",
    "Competitor A ran price-increase announcement March 15 — displacement opportunity",
    "3 open Salesforce opportunities in same segment progressed to Stage 3 last week"
  ]
}

---

HUMAN-IN-THE-LOOP GATE 1 PROTOCOL

Approval Request Format (Slack message to #marketing-approvals):
┌────────────────────────────────────────────────┐
│ 🤖 CAMPAIGN INTELLIGENCE AGENT — APPROVAL REQUEST
│ Campaign: RevOps Platform Migration Season
│ Budget Request: $8,500 (7-day test period)
│ Estimated Pipeline Impact: $340K influenced
│ Confidence: 81%
│ Trigger: Bombora intent surge + competitor pricing news
│
│ Action Required: Approve or modify by Monday 2PM
│ Brief: [Link to full document]
│
│ ✅ Approve    ✏️ Modify    ❌ Reject
└────────────────────────────────────────────────┘

SLA: 4 business hours. If no response by 2PM Monday, non-urgent tactics delayed 24 hours.

## Success Metrics

- **Agent autonomy rate:** % of campaign cycle tasks completed without human intervention (target: >70% at Week 16)
- **Override rate:** % of agent decisions overridden by humans (healthy range: 5-15%; >25% indicates agent calibration issues)
- **Time-to-launch:** Hours from campaign brief approval to live campaign (target: <4 hours vs. 48+ hours manually)
- **Pipeline attribution accuracy:** Agent-run campaigns within 10% of human-managed campaigns on influenced pipeline metrics
- **Governance rejection rate:** <10% of content batches require revisions (indicates agent-generated content quality)
- **Anomaly catch rate:** Governance/Analytics agents catch 90%+ of issues before human review

## Related Prompts

- [`../../01_CMO-&-Leadership/Strategy-&-Planning/AI-Autonomous-Campaign-Agent-Deployment-&-Governance-Intelligence-Engine.md`](../../01_CMO-&-Leadership/Strategy-&-Planning/AI-Autonomous-Campaign-Agent-Deployment-&-Governance-Intelligence-Engine.md)
- [`../../05_Analytics-&-Marketing-Operations/MarTech-Stack-Optimization/AI-Powered-Data-Clean-Room-Strategy-&-Privacy-Safe-Audience-Intelligence-Engine.md`](../../05_Analytics-&-Marketing-Operations/MarTech-Stack-Optimization/AI-Powered-Data-Clean-Room-Strategy-&-Privacy-Safe-Audience-Intelligence-Engine.md)
- [`../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Signal-Based-GTM-Automation-&-Revenue-Trigger-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Signal-Based-GTM-Automation-&-Revenue-Trigger-Engine.md)
- [`../../01_CMO-&-Leadership/Strategy-&-Planning/Marketing-Operations-Excellence-&-AI-Workflow-Automation-Intelligence-Engine.md`](../../01_CMO-&-Leadership/Strategy-&-Planning/Marketing-Operations-Excellence-&-AI-Workflow-Automation-Intelligence-Engine.md)

## Integration Tips

- **LangChain / CrewAI / AutoGen:** The 7 agent specifications map directly to CrewAI Agent definitions. Use the JSON schemas in Section 2 as task output formats. The Governance Agent can be implemented as a LangChain output parser with guardrail checks.
- **HubSpot + Salesforce:** Campaign Intelligence Agent should connect to both via their native APIs. Use HubSpot's workflow automation to receive agent-generated lead scores and route to sequences. Salesforce's Apex triggers can notify the ABM Agent when opportunity stages change.
- **Slack:** Use Slack's Block Kit for structured approval request messages (Gate 1, 2, 3). Leverage Slack workflows to route approvals to the right person based on campaign type and budget size.
- **Zapier / Make (Integromat):** For teams without engineering resources, agents can be connected via Zapier — Campaign Intelligence Agent output triggers a Google Doc creation, which routes to a Slack approval, which triggers a HubSpot workflow enrollment.
- **Linear / Notion:** Log all agent decision events to a Notion database or Linear project for the monthly audit. Each campaign cycle should produce a structured event log.
- **Monitoring:** Pipe all agent outputs to a Datadog or Grafana dashboard. Create alert rules based on the anomaly thresholds defined in Section 4. Pager-level alerts for kill switch conditions.

## Troubleshooting

**Problem:** Agents are generating high volumes of outputs but human approval bottleneck is creating backlogs.
**Solution:** Implement tiered approval thresholds — pre-authorize common campaign types within known budget ranges. For example, any campaign brief that matches a previously approved template and requests <$3K spend gets auto-approved. Reserve human review for net-new strategies or above-threshold budgets. Review override data monthly: if humans approve >85% of requests unchanged, raise the auto-approval threshold.

**Problem:** Governance Agent is rejecting too much content (>25% rejection rate), causing production delays.
**Solution:** Rejection rate >25% signals a mismatch between Content Agent's prompt instructions and brand guidelines. Audit the last 20 rejections for patterns — are they all violating the same rule? Update the Content Agent's system prompt with specific examples of approved vs. rejected content. Consider adding a "pre-validation" step where Content Agent self-checks against the top 5 most common rejection reasons before passing to Governance Agent.

**Problem:** Performance data from the Analytics Agent doesn't match what the team sees in platform dashboards (attribution discrepancy).
**Solution:** Multi-touch attribution across agents requires a single source of truth. Designate one system (typically Salesforce with UTM data from HubSpot) as the canonical attribution layer. All agent performance metrics should pull from this single source. Discrepancies >15% indicate data pipeline issues — audit UTM parameter consistency, CRM field mapping, and ad platform conversion tracking. Run a 2-week parallel reporting period where agents and humans both report independently, then reconcile.

## Version History
- v1.0: Initial creation (auto-generated)
