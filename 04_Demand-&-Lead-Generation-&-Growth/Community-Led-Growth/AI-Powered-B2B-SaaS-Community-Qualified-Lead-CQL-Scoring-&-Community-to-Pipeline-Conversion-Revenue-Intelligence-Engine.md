# AI-Powered B2B SaaS Community-Qualified Lead (CQL) Scoring & Community-to-Pipeline Conversion Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** community-led-growth, lead-scoring, pipeline-generation, b2b, automation, intent-signals

## Overview
This prompt engineers a full AI-agent-driven system that identifies, scores, and converts community members showing purchase intent into qualified sales pipeline — transforming your Slack, Discord, Discourse, or Circle community from a cost center into a measurable revenue channel. Use it when you have an active B2B community with 500+ members and need to systematically extract pipeline without burning community trust.

## Quick Copy-Paste Version

You are a B2B SaaS community revenue intelligence agent. Your mission is to design a Community-Qualified Lead (CQL) scoring and conversion system for [Your Product] that identifies which community members are ready for a sales conversation — and routes them to revenue without disrupting community culture.

Context:
- Product: [Your SaaS product, e.g., "DataBridge — a data pipeline platform for RevOps teams"]
- Community platform: [Slack / Discord / Circle / Discourse / Khoros]
- Community size: [e.g., 4,200 members]
- ICP: [e.g., "VP RevOps and Director of Data Engineering at B2B SaaS companies, 50–500 employees, $5M–$50M ARR"]
- Current community goal: [e.g., "Product feedback, peer learning, category education"]
- CRM: [HubSpot / Salesforce / other]

Deliverables:

1. CQL SCORING MODEL
Build a 100-point CQL score with behavioral signals, ICP fit attributes, and engagement recency weights. Include:
- Positive signals (e.g., posts a use case question, shares integration need, mentions competitor frustration, asks about pricing/implementation, joins product-specific channel)
- Negative signals (e.g., competitor employee, student, pure lurker with no ICP fit)
- Score thresholds: CQL-Ready (75+), CQL-Warm (50–74), CQL-Nurture (25–49), CQL-Excluded (<25)
- Decay logic: reduce score by X points per week of inactivity

2. SIGNAL DETECTION PLAYBOOK
For each of the top 8 buying signals, write:
- Signal name and description
- Detection method (keyword triggers, channel activity, reaction patterns, DM requests)
- Immediate automated action
- Human review required? Yes/No
- Example trigger message/behavior

3. CQL-TO-PIPELINE WORKFLOW
Design the end-to-end automated sequence:
- Signal detected → Score updated in CRM
- CQL-Ready threshold crossed → Alert to Community Manager + AE
- Outreach playbook (community-native first, never cold email first)
- Handoff SLA and conversation templates
- Decline/no-response path

4. COMMUNITY-NATIVE OUTREACH SCRIPTS
Write 3 outreach scripts for different CQL scenarios:
a) Member asked a product-adjacent question publicly → helpful DM from community manager
b) Member shared a problem your product solves → peer-style "have you tried X?" response
c) High-ICP lurker who attended 3 events → personal invite to private office hours

5. ATTRIBUTION & REPORTING FRAMEWORK
Define how to track community-sourced pipeline:
- UTM/tracking parameters for community links
- CRM field mappings for community touchpoints
- Monthly CQL report structure (volume, conversion rate, pipeline $, CAC vs. non-community)
- Board-ready community ROI metric: Community-Influenced Pipeline %

Output format: Structured playbook with scoring matrix, signal table, workflow diagram (text-based), outreach scripts, and reporting template.

## Advanced Customizable Version

ROLE: You are a senior demand generation architect and community-led growth strategist with 12+ years of B2B SaaS experience. You have designed CQL programs at companies ranging from Series A ($3M ARR) to post-IPO ($200M ARR). You understand both the commercial imperative to monetize community AND the community-first principle that trust, once broken, cannot be recovered.

CONTEXT:
Company: [Company Name]
Product: [Product Name and one-line description]
Community Platform: [Primary platform — Slack/Discord/Circle/Discourse/Khoros/custom]
Secondary Community Touchpoints: [GitHub, Reddit, LinkedIn Group, X/Twitter community, in-person meetups, virtual events]
Community Size: [Total members] | Active Monthly Members: [MAM count]
Community Segments: [e.g., "Practitioners 60%, Decision-makers 20%, Partners 15%, Competitors/students 5%"]
ICP Definition:
  - Firmographic: [Company size, industry, tech stack, revenue stage]
  - Personas: [Primary buyer, champion/champion, economic buyer]
  - Negative ICP: [Who to exclude]
CRM: [HubSpot / Salesforce / Pipedrive / other]
Community-to-CRM Integration: [Native integration / Zapier / Make / custom API / none yet]
Current Monthly Community-Sourced Leads: [Number or "unknown"]
Sales Cycle: [Average days] | ACV: [$X]
Community Manager: [Dedicated / part-time / marketing generalist covers it]
Tone Constraint: [e.g., "Community is fiercely anti-sales — any overt selling would destroy trust. Outreach must feel 100% value-first."]

OBJECTIVE:
Design a fully automated, AI-agent-driven Community-Qualified Lead (CQL) system that:
1. Continuously monitors community signals in real-time
2. Scores each member against a revenue-weighted ICP model
3. Triggers the right action at the right threshold — automatically where possible, human-reviewed where trust is at stake
4. Converts CQL-Ready members to pipeline at a rate that outperforms cold outbound by 3x+
5. Attributes community revenue contribution to satisfy CFO scrutiny

DELIVERABLE 1: CQL SCORING ARCHITECTURE

Build a comprehensive CQL scoring model using the FIRE framework:
- F = Fit (ICP firmographic and technographic match): 0–30 points
- I = Intent (behavioral buying signals in community): 0–40 points
- R = Recency (time-weighted engagement): 0–20 points
- E = Engagement depth (quality vs. quantity of participation): 0–10 points

For each dimension, provide:
- Scoring criteria table with specific point values
- Data sources for each signal (community platform data, enrichment tools like Clearbit/Clay, CRM data)
- Automation method (API pull, webhook, Zapier/Make workflow, manual tag)

Score Thresholds and Actions:
| Score Range | Status | Action |
|-------------|--------|--------|
| 85–100 | CQL-Hot | Immediate alert to AE + Community Manager, 24hr outreach SLA |
| 70–84 | CQL-Ready | Alert to Community Manager, 48hr personalized DM, AE notify |
| 50–69 | CQL-Warm | Add to nurture sequence, invite to exclusive event/office hours |
| 30–49 | CQL-Nurture | Tag for content nurture, invite to product webinars |
| <30 | Observe | No commercial action, continue community engagement |
| Excluded | Block | Competitor, student, wrong geo — flag and remove from scoring |

Score Decay Logic:
- Define weekly decay rate for inactive members
- Define score reset triggers (e.g., member hasn't logged in for 60 days)
- Define score boost events (e.g., attended live event: +15 points; submitted support ticket: +10 points)

DELIVERABLE 2: TOP 12 BUYING SIGNAL DETECTION PLAYBOOK

For each signal, provide a structured playbook card:

Signal Card Format:
Signal Name: [Name]
Category: [Fit / Intent / Recency / Engagement]
Points: [Value added to CQL score]
Description: [What behavior this is]
Detection Method: [Keyword list / Channel / Webhook / Manual tag]
Sample Trigger: [Exact example message or behavior]
Automated Action: [What the system does instantly]
Human Review: [Yes — Community Manager / No — fully automated]
Outreach Script: [One-line response template]
CRM Field Updated: [Field name and value]

Signal categories to cover:
a) Explicit buying signals (pricing questions, procurement timeline, "evaluating X vs. Y", "need this for enterprise deployment")
b) Implicit buying signals (integration questions, use-case questions that match your core use case, mentions of pain points you solve)
c) Competitive signals (frustration with competitor, asking for migration help, tagging competitors)
d) Relationship signals (DM to team member, reacted to product announcement, responded to AMA)
e) Event signals (attended product demo day, registered for advanced training, joined private beta channel)
f) Network signals (tagged a colleague who matches ICP, forwarded community link to procurement)

DELIVERABLE 3: END-TO-END CQL AUTOMATION WORKFLOW

Design the complete technical workflow as a step-by-step automation sequence. For each step specify:
- Trigger event
- Tool/system involved (Slack API, Make/Zapier, HubSpot/Salesforce, Clay, Clearbit, GPT-4 for message classification)
- Action taken
- Fallback if automation fails
- Time delay or SLA

Workflow Stages:
1. Signal Capture Layer: How raw community activity is ingested (webhook, API polling, Slack bot)
2. Enrichment Layer: How member identity is resolved (email matching, LinkedIn enrichment, CRM lookup)
3. Scoring Engine: How FIRE score is calculated and updated in CRM
4. Threshold Alert System: How CQL-Hot/Ready alerts reach Community Manager and AE
5. Outreach Sequencer: Community-native DM → value-add follow-up → soft ask → AE intro
6. Pipeline Creation: How accepted conversations become CRM opportunities
7. Decline/No-Response Path: Re-route to nurture, score decay, no aggressive follow-up
8. Closed-Loop Feedback: How won/lost deals feed signal quality improvement

DELIVERABLE 4: COMMUNITY-NATIVE OUTREACH PLAYBOOK

Write complete, ready-to-send scripts for 6 CQL scenarios. Each script must:
- Sound 100% human and community-first
- Never mention that they've been "scored" or tracked
- Lead with value (resource, insight, connection) before any commercial intent
- Include subject/opening line, body, and CTA
- Be under 150 words (DM length)

Scenarios:
a) CQL-Hot: Member publicly asked a product-fit question in #general
b) CQL-Hot: High-ICP silent lurker just joined your #advanced-users private channel
c) CQL-Ready: Member expressed competitor frustration in #tools-and-stack
d) CQL-Ready: Member tagged a colleague who also matches ICP
e) CQL-Warm: Member attended your last 2 virtual events but hasn't engaged in chat
f) CQL-Warm: Member asked for a resource in community and you fulfilled it — now following up

For each, also include: the DECLINE script (if they say "not now" or "no thanks") — maintaining relationship without burning bridge.

DELIVERABLE 5: CQL ATTRIBUTION & ROI REPORTING FRAMEWORK

CRM Implementation:
- Required fields to add to Contact and Deal objects
- Community source tracking taxonomy (Platform → Channel → Signal Type → Campaign)
- UTM parameter structure for all community links
- How to handle multi-touch attribution when community is one of several touchpoints

Monthly CQL Report Template (Board-Ready):

Executive Summary Metrics:
- Community-Sourced Pipeline Created ($): [Target vs. Actual]
- Community-Influenced Pipeline ($): [All deals with ≥1 community touch]
- CQL Conversion Rate (CQL-Ready → Opportunity): [Benchmark: aim for 15–25%]
- Community CAC vs. Blended CAC: [Expected: 40–60% lower]
- Community-to-Close Win Rate vs. Outbound: [Expected: 2–3x higher]
- Time-to-Close (Community-sourced vs. Outbound): [Expected: 20–35% faster]

Leading Indicators (Weekly):
- New CQL-Hot and CQL-Ready members this week
- Outreach sent / Response rate / Meetings booked
- Community MAM trend
- Top signal types generating CQLs

Attribution Narrative for CFO/Board:
Write a 3-sentence proof-of-value statement that frames community revenue contribution in financial terms — suitable for a board deck.

DELIVERABLE 6: COMMUNITY TRUST SAFEGUARDS

Design the guardrails that prevent the CQL system from destroying community trust:
- Opting members out of commercial tracking (GDPR/CCPA compliance approach)
- Signal suppression rules (never reach out to someone who hasn't logged in 30+ days with a sales message)
- Community Manager override capabilities
- Quarterly community NPS tracking and correlation with CQL activity
- "Community charter" language to add to your community onboarding that sets expectations

OUTPUT FORMAT:
1. Executive Summary (3 bullets: what this system does, expected pipeline impact, implementation timeline)
2. FIRE Scoring Matrix (table format)
3. Signal Detection Playbook (12 signal cards)
4. Automation Workflow (numbered step sequence with tools)
5. Outreach Scripts (6 scenarios + 6 decline responses)
6. Attribution Framework (CRM fields + monthly report template)
7. Trust Safeguards Checklist

CONSTRAINTS:
- Every automated action must be technically achievable with Slack/Discord API + HubSpot or Salesforce + Make or Zapier — no custom engineering required beyond configuration
- Outreach must be community-manager-voiced, not sales-voiced
- System must comply with GDPR/CCPA by default
- Pipeline projections must be conservative and based on industry benchmarks, not optimistic assumptions

## Example Input/Output

**Input Example:**

Company: Fieldstream Analytics
Product: Fieldstream — operational analytics platform for industrial IoT and manufacturing operations teams
Community: "Ops Intelligence Community" on Slack — 3,800 members, 620 monthly active
ICP: Head of Operations / Director of Manufacturing Operations at industrial manufacturers with 200–2,000 employees
ACV: $48,000 | Sales Cycle: 90 days average
Community Manager: Sarah (part-time, 50% of her role)
Integration: Slack + HubSpot via Make (already live)
Tone: "Community is technical practitioners — they hate being sold to. Must be peer-to-peer only."

**Output Example (excerpt):**

**FIRE Score — Sample Member: Marcus T., Director of Operations @ PrecisionParts Inc.**

| Dimension | Signal | Points |
|-----------|--------|--------|
| Fit | 850-person manufacturer, automotive industry (exact ICP) | +28 |
| Fit | Uses OSIsoft PI (tech stack match) | +5 |
| Intent | Asked "how do you handle shift-change data gaps in dashboards?" | +22 |
| Intent | Joined #enterprise-deployments channel (new this week) | +18 |
| Recency | Active 4 of last 7 days | +18 |
| Engagement | 3 substantive replies, 0 posts in last 30 days | +6 |
| **TOTAL** | | **97 — CQL-Hot** |

**Automated Action Triggered:**
- HubSpot contact updated: Community_CQL_Status = "Hot", Community_Score = 97
- Slack alert to #cql-alerts: "@sarah @mike_ae — Marcus T. from PrecisionParts just hit CQL-Hot. He's asking about enterprise deployment gaps in #enterprise-deployments. Suggested approach: Sarah replies to his thread with the Shift-Change Data Gap guide, then DMs 24hrs later."
- 24hr outreach SLA timer set in HubSpot task

**Sarah's DM to Marcus (sent 24 hours later):**
> "Hey Marcus — saw your question about shift-change data gaps in the main channel and thought of you when we published this internal guide from a few of our manufacturing users last month: [link]. One of the authors (Dana at Acme Metals) had almost the exact same setup as what you described. Happy to intro you if useful — or no worries if you've already figured it out!"

**Result (hypothetical):** Marcus responds within 4 hours. Intro to Dana happens. Marcus books a demo through Dana's referral. Opportunity created: $52,000. Time from first signal to opportunity: 6 days.

**CQL Conversion Rate (Fieldstream benchmark after 90 days):**
- CQL-Hot → Meeting Booked: 34%
- CQL-Ready → Meeting Booked: 19%
- Community-sourced CAC: $4,200 vs. blended $11,800

## Success Metrics

**Primary:**
- CQL-Ready → Sales Opportunity conversion rate ≥ 15% (benchmark; aim for 20–25% at maturity)
- Community-sourced pipeline as % of total pipeline: target 10–20% within 6 months
- Community CAC 40–60% lower than blended CAC

**Secondary:**
- Signal detection accuracy: ≥ 80% of CQL-Hot outreach results in a reply (positive or not)
- Community NPS remains stable or improves (≥ +35) after CQL program launch
- Time-from-signal-to-outreach SLA adherence: ≥ 90% within defined SLA

**Guardrail Metrics (watch for trust erosion):**
- Community churn rate (members leaving) stays below 3% monthly
- Spam complaints or negative reactions to outreach: target < 2% of outreach sent
- Community Manager time per CQL: target < 15 minutes per CQL-Ready member (automation doing the heavy lifting)

## Related Prompts
- [Community-Led Growth Architecture & Member-to-Pipeline Revenue](../../04_Demand-&-Lead-Generation-&-Growth/Community-Led-Growth/AI-Powered-B2B-SaaS-Community-Led-Growth-Architecture-&-Member-to-Pipeline-Revenue-Intelligence-Engine.md)
- [Predictive Lead Scoring Architecture & Revenue-Qualified Pipeline](../../04_Demand-&-Lead-Generation-&-Growth/Lead-Scoring-&-Pipeline-Management/AI-Powered-B2B-SaaS-Predictive-Lead-Scoring-Architecture-&-Revenue-Qualified-Pipeline-Management-Intelligence-Engine.md)
- [ABM Intent Data Activation & Buying Signal Prioritization](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md)
- [Community-Led Expansion Revenue & Champion Network NRR](../../04_Demand-&-Lead-Generation-&-Growth/Community-Led-Growth/AI-Powered-B2B-SaaS-Community-Led-Expansion-Revenue-Architecture-&-Champion-Network-Net-Revenue-Retention-Intelligence-Engine.md)

## Integration Tips

**HubSpot:**
- Create a custom Contact property: `Community_CQL_Score` (number), `Community_CQL_Status` (dropdown: Hot/Ready/Warm/Nurture/Observe/Excluded), `Community_Platform` (text), `Community_Last_Active` (date), `Community_Top_Signal` (text)
- Build a HubSpot workflow: trigger on `Community_CQL_Score ≥ 85` → create Task assigned to Community Manager with signal context → notify AE via Slack integration
- Use HubSpot's Revenue Attribution to tag community as an interaction source on deals

**Salesforce:**
- Add custom fields to Lead and Contact objects; use Process Builder or Flow to trigger CQL alerts
- Connect to Slack via Zapier: Salesforce Field Updated → Slack #cql-alerts message with merge fields

**Slack/Discord API:**
- Use Slack's Events API to capture message_posted, reaction_added, channel_joined events
- Pipe events to Make (Integromat) for scoring logic and CRM updates
- For Discord: use a bot (built with discord.js or Zapier Discord integration) to capture message events

**Clay (Enrichment):**
- Use Clay to auto-enrich new community members joining with LinkedIn, company size, tech stack
- Pipe enriched data to CRM as ICP Fit score component
- Set up Clay table with community member email/username → enrich → push to HubSpot

**Make (Integromat) — Core Automation Hub:**
- Build a Make scenario: Slack webhook → parse message for keyword signals → score update → CRM write → conditional: if score ≥ 85, send Slack alert to #cql-alerts
- Use Make's HTTP module to call OpenAI API for nuanced intent classification on longer community messages

## Troubleshooting

**Problem: Community members feel "creeped out" by personalized outreach that references their community behavior**
Solution: Never reference the specific post or signal in your outreach. Instead, lead with a relevant resource or connection that would be naturally useful to someone with their role/industry. The intelligence informs WHO you reach out to; your message should feel organic, not surveillance-y. Have the Community Manager (not Sales) own all first touch.

**Problem: CQL score keeps triggering false positives (high-score members who have zero purchase intent)**
Solution: Add a manual "CQL Override" flag that the Community Manager can set to suppress commercial outreach for specific members (e.g., consultants, researchers, students who write sophisticatedly). Also add a negative signal for members who have been explicitly asked if they'd like to learn more and declined — add -30 points and set a 90-day outreach suppression flag.

**Problem: Attribution is contested — Sales says community wasn't the real source, came from paid search**
Solution: Use multi-touch attribution with a "community-influenced" tag (separate from "community-sourced"). A deal is community-sourced only if the first meaningful engagement happened in community. A deal is community-influenced if any community touch occurred in the 90 days before the opportunity was created. Report both numbers — the CFO will trust community-influenced more initially, then as the data matures, community-sourced will speak for itself.

## Version History
- v1.0: Initial creation (auto-generated)
