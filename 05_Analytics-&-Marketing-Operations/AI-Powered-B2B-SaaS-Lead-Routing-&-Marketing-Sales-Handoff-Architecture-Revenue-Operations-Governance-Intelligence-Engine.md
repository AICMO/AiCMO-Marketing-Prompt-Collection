# AI-Powered B2B SaaS Lead Routing & Marketing-Sales Handoff Architecture Revenue Operations Governance Intelligence Engine - Design a Zero-Friction, Fully Automated Lead Flow System That Eliminates Revenue Leakage at the Marketing-Sales Boundary

**Difficulty:** Advanced | **Time:** 30-45 min | **Tags:** lead routing, marketing operations, revenue operations, MQL, SQL, lead scoring, marketing-sales alignment, HubSpot, Salesforce, Marketo, LeanData, lead lifecycle, handoff automation, pipeline governance, SLA enforcement, RevOps, B2B SaaS

## Overview
Designs a complete AI-native lead routing and marketing-sales handoff governance system — covering scoring logic, routing rules, SLA enforcement, ownership assignment, and real-time fallback escalation — so every high-intent lead reaches the right rep within minutes, not days. Use this when marketing-sourced leads go dark after handoff, when MQL-to-SQL conversion rates are below 20%, or when "we never got that lead" is a recurring sales complaint.

## Quick Copy-Paste Version

You are a revenue operations architect with deep expertise in B2B SaaS lead lifecycle design. Design a complete, production-ready lead routing and marketing-sales handoff system for the company below.

COMPANY CONTEXT:
- Company: [e.g., "Fenix — AI-powered workforce scheduling platform for multi-location retail and hospitality operators"]
- ARR and stage: [e.g., "$19M ARR, Series B, adding 15 AEs over next 6 months"]
- Sales motion: [e.g., "Inbound + outbound; SMB self-serve under $5K ACV handled by SDRs, Mid-Market $15K–$80K ACV handled by AEs, Enterprise $80K+ runs through a named account overlay team"]
- Lead volume: [e.g., "~600 MQLs/month from inbound; 900 outbound sequences/month from SDRs; 120 high-intent demo requests/month"]
- Current routing system: [e.g., "HubSpot round-robin to SDR team; no territory logic; AE assignment manual; enterprise leads routed by SDR manager judgment — 4-hour average lead response time; 8% of MQLs never contacted"]
- CRM and MAP: [e.g., "Salesforce + HubSpot Marketing Hub; LeanData for routing; Chili Piper for scheduling"]
- Top routing failures: [e.g., "Leads from named enterprise accounts going to SMB SDRs; duplicate leads created when prospect fills form twice; no SLA breach alerts; reps cherry-pick easy leads and ignore others"]
- ICP signals available: [e.g., "Firmographic enrichment via Clearbit; G2 intent data; 6sense account scoring; product usage data from self-serve trial signups"]

OUTPUT REQUIRED:
1. LEAD SCORING ARCHITECTURE: A complete behavioral + firmographic scoring model with exact point values, decay logic, and MQL threshold — producing a score any rep can interpret in under 10 seconds
2. ROUTING DECISION TREE: The complete if-then routing logic covering all lead types (inbound form, demo request, chat, self-serve signup, event scan, outbound reply, partner referral) with ownership assignment rules and territory logic
3. SLA FRAMEWORK: Response time SLAs by lead tier with automated escalation sequences when breached — including the exact Salesforce/HubSpot workflow logic
4. HANDOFF PROTOCOL: The exact data fields, context, and insights automatically packaged for each rep at moment of assignment — zero manual research required
5. DUPLICATE AND CONFLICT RESOLUTION: Rules for deduplication, account matching, existing opportunity detection, and customer/competitor filtering
6. GOVERNANCE DASHBOARD: The metrics, alerts, and weekly audit process that catches routing failures within 24 hours — not at end-of-quarter QBR

## Advanced Customizable Version

ROLE: You are a senior revenue operations architect with 15+ years building marketing-sales alignment infrastructure at B2B SaaS companies scaling from $5M to $200M ARR. You have implemented lead routing systems at eight companies, including three where you rebuilt a broken handoff process mid-hypergrowth while simultaneously onboarding 20+ new AEs. You hold deep expertise in LeanData, Chili Piper, HubSpot, Salesforce routing automation, and behavioral scoring models. You have a core belief: every hour a high-intent lead spends uncontacted is $400 of ACV evaporating — and the majority of revenue leakage in B2B SaaS happens not from bad marketing or bad selling, but from the 48-hour gap between the two. You design systems that eliminate that gap entirely.

OBJECTIVE: Design a complete, production-ready AI-native lead routing and marketing-sales handoff governance system that:
- Scores every lead in real time using behavioral signals, firmographic fit, intent data, and product usage signals — producing a single composite score that auto-routes without human judgment
- Routes every lead type (inbound form, demo request, chat conversation, self-serve trial activation, webinar attendance, partner referral, outbound reply, content download, high-intent page sequence) to the right owner within minutes of the qualifying action
- Enforces time-based SLAs with automated escalation sequences that guarantee no lead sits uncontacted — and alerts RevOps and the rep's manager when a breach occurs
- Packages a complete, AI-generated context brief for every rep at the moment of assignment — firmographic profile, intent signals, behavioral trail, similar customer references, and recommended talk track — requiring zero manual prep
- Detects and resolves routing conflicts (existing opportunity, current customer, competitor domain, duplicate, matched named account) before assignment — not after the rep calls and discovers the problem
- Produces a real-time governance dashboard and weekly audit report that surfaces routing failures, SLA breach rates, and segment-level conversion performance without manual analysis

COMPANY PROFILE:
- Company name and one-sentence product description: [name + what it does for what buyer at what company size]
- Current ARR, funding stage, and growth velocity: [ARR | round | YoY growth rate | next ARR milestone]
- Sales team structure: [SDR count | AE count | territories or segments | inside sales vs. field | overlay roles]
- GTM motions in play: [inbound / outbound / PLG self-serve / partner / ABM / event — mix and relative volume]
- Monthly lead volumes by source: [MQL count by channel | demo requests | self-serve signups | partner referrals | event leads]
- Current MQL-to-SQL conversion rate and average lead response time: [% | hours — be honest]
- Sales segments and ACV ranges: [SMB ACV | MM ACV | Enterprise ACV | named account list size]
- Territory design: [geographic / vertical / account size / named / round-robin — current state]
- CRM and MAP: [Salesforce / HubSpot | Marketo / HubSpot / Pardot | version / tier]
- Routing tools: [LeanData / Chili Piper / Calendly / Clearbit / 6sense / native only]
- Enrichment and intent data: [firmographic enrichment provider | intent data provider | product usage telemetry available]

LEAD TYPES TO ROUTE (provide routing logic for each):
- High-intent demo request (form or Chili Piper)
- Inbound marketing qualified lead (behavior threshold crossed)
- Self-serve trial signup (PLG entry)
- Chat conversation (Drift / Intercom handoff)
- Webinar or event attendee (live or on-demand)
- Content asset download (gated asset)
- Outbound sequence reply (positive / neutral / out-of-office)
- Partner or affiliate referral
- Inbound phone call (if applicable)
- Product qualified lead (PQL — trial usage threshold)

ROUTING ARCHITECTURE REQUIREMENTS:
Design the complete system across these six layers:

**Layer 1 — Scoring Model**
- Behavioral scoring: [define which actions score and at what point values — page visits, content downloads, email opens/clicks, demo requests, pricing page, feature pages, chat engagement, webinar attendance, product trial actions]
- Firmographic fit scoring: [company size, industry vertical, tech stack signals, funding stage, employee growth rate, revenue estimate — map each to a point value]
- Intent signal integration: [how 6sense / Bombora / G2 / competitor comparison page visits layer into score — don't just add intent as a binary flag]
- Product usage scoring (PQL layer): [trial feature adoption milestones that trigger routing to sales regardless of behavioral/firmographic score]
- Score decay logic: [how scores decrease over inactivity — time windows and decay rates by action type]
- MQL threshold: [the exact score that triggers MQL status and routing — with rationale tied to historical conversion data]
- Score interpretation tier: [Hot / Warm / Cold bands mapped to routing urgency tiers]

**Layer 2 — Routing Decision Tree**
- Named account detection: [how accounts are matched to the named account / TAL list before any other routing logic]
- Existing opportunity detection: [lookup against open Salesforce opportunities — route to opportunity owner, not territory rep]
- Current customer detection: [lookup against active Accounts — route to CSM or customer marketing, not sales]
- Competitor domain filtering: [block routing to SDR queue, flag for competitive intelligence]
- Duplicate detection: [dedup logic by email, company domain, phone — merge or link, don't create duplicate lead]
- Territory assignment: [the complete ruleset for how segment, industry, geography, company size, or account tier determines assignment — including round-robin with weighted distribution for high-volume segments]
- Overflow and fallback: [what happens when the assigned rep is OOO, at capacity, or unresponsive — escalation path and max escalation time]

**Layer 3 — SLA Enforcement**
- SLA tiers by lead quality: [Tier 1 = 5 min | Tier 2 = 1 hour | Tier 3 = 4 hours | Tier 4 = next business day — with exact criteria for each tier]
- SLA clock definition: [when does the clock start — assignment timestamp, not form submission; handle time zone and business hours correctly]
- SLA breach sequence: [exact automation steps: T+5 min: rep SMS | T+15 min: rep email | T+30 min: manager Slack | T+1 hr: auto-reassign — with actual message templates]
- SLA reporting: [how breach rate is tracked, reported, and reviewed — by rep, segment, and source]

**Layer 4 — Rep Context Brief (AI-Generated)**
At the moment of assignment, automatically deliver to the rep (via Salesforce, Slack, or email) a structured context package containing:
- Company snapshot: size, industry, tech stack, recent funding, recent hires, public news
- Lead's behavioral trail: every touchpoint in chronological order with timestamps
- Lead's intent signals: active research topics, competitor pages visited, G2 categories in-market
- Qualification pre-score: predicted deal size, segment fit score, likelihood to convert
- Recommended outreach: the specific personalized talk track, subject line, and first message — generated by AI from all available signals
- Similar customers: 2-3 reference customers in same industry/size with outcomes — ready for the rep to mention
- Open questions: the 3 discovery questions most likely to accelerate qualification based on behavioral signals

**Layer 5 — Conflict and Exception Handling**
- What to do when a lead matches multiple rules (priority hierarchy)
- What to do when firmographic enrichment fails or returns low-confidence data
- What to do when a lead scores MQL but the company is too small / too large for any active segment
- What to do when a lead is from a market not yet covered by a territory
- What to do when the same person submits multiple forms in 30 days
- Manual override logging: any rep or manager override is logged, timestamped, and reviewed in weekly governance audit

**Layer 6 — Governance and Continuous Improvement**
- Weekly routing audit report: leads routed, SLA performance, conversion rate by source and segment, routing conflicts detected, manual overrides made
- Monthly lead lifecycle review: MQL-to-SQL rate trend, average response time trend, stage conversion by routing tier, rep-level performance on lead follow-up
- Routing model versioning: how scoring threshold changes are tested (A/B or holdout group) before full deployment
- Feedback loop from sales to marketing: what signals predict SQLs that aren't being captured in the current score — systematic sales feedback mechanism

CONSTRAINTS:
- Every routing decision must be logged in the CRM with the rule name and data values that triggered it — no black-box routing
- All SLA timers must account for business hours and rep OOO status automatically
- The system must handle a 3x volume spike (e.g., post-event, post-funding announcement) without manual intervention
- No lead should require a human to "figure out what to do with it" — every lead type has a defined path, even if that path is "park in nurture"
- The handoff context brief must be generated in under 60 seconds of assignment

OUTPUT FORMAT:
Deliver the complete system as:
1. Executive summary: the 3 highest-impact changes this system makes vs. current state
2. Scoring model table: action / point value / decay window for every scoring signal
3. Routing decision tree: visual text representation of the complete if-then logic
4. SLA matrix: tier definitions, time windows, and escalation sequence per tier
5. Rep context brief template: the exact structure of the AI-generated handoff package
6. Conflict resolution rules: priority hierarchy and exception handling table
7. Governance dashboard spec: the 8 metrics that matter, their data sources, and alert thresholds
8. 30-day implementation plan: what to configure in week 1 vs. weeks 2–4 to go live fast

## Example Input/Output

**Input Example:**

Company: Vantiq — real-time application development platform for operational AI and event-driven enterprise systems
ARR: $31M ARR, Series C, targeting $55M in 18 months
Sales structure: 6 SDRs (outbound-focused), 9 AEs in three segments (Digital Transformation <$40K ACV, Platform Modernization $40K–$150K, Enterprise Transformation $150K+), plus 1 named account AE covering 50 Fortune 500 target accounts
Monthly volume: ~320 MQLs, 85 demo requests, 210 outbound positive replies, 40 event leads
CRM/MAP: Salesforce + Marketo; LeanData (basic plan); Chili Piper (scheduling only)
Current problem: AEs complain that 30% of leads are "not real" — wrong company size or no buying intent; SDRs contact leads 6–18 hours after form fill; enterprise leads routinely land in SMB SDR queue because the enrichment isn't running at form submission time

**Output Example (condensed):**

**EXECUTIVE SUMMARY**

Three changes will recover the most revenue immediately:
1. **Real-time enrichment trigger at form submission** — run Clearbit Reveal + 6sense account match before the routing decision executes, not after. This alone will eliminate 85% of enterprise-in-SMB-queue incidents.
2. **5-minute Tier 1 SLA with automatic SDR SMS + Slack notification** — your 6–18 hour response time costs ~$180K in potential ACV monthly at current conversion rates. Every hour of delay on a hot demo request drops conversion probability by ~8%.
3. **Named account pre-filter as the first routing check** — before any score-based routing, match the lead's company to Vantiq's 50-account TAL and route to the named AE. No scoring threshold required for TAL accounts.

**SCORING MODEL (Top Signals)**

| Behavioral Action | Points | Decay Window |
|---|---|---|
| Demo request (any form) | 80 | None — permanent |
| Pricing page visit (2+ sessions) | 35 | 30-day half-life |
| Product feature page (3+ unique pages) | 25 | 21-day half-life |
| Competitor comparison page | 30 | 14-day half-life |
| Webinar attended (live) | 20 | 45-day half-life |
| Case study download (industry match) | 15 | 30-day half-life |
| Email click (high-intent CTA) | 10 | 21-day half-life |
| Blog post read (3+ sessions) | 5 | 14-day half-life |

| Firmographic Signal | Points | Source |
|---|---|---|
| Company size 100–5,000 employees | 30 | Clearbit |
| Industry: Financial Services, Healthcare, Logistics, Manufacturing | 25 | Clearbit |
| Tech stack: AWS / Azure / Kubernetes / microservices signals | 20 | Clearbit / BuiltWith |
| Funding: raised in last 18 months | 15 | Clearbit |
| Employee growth >15% YoY | 10 | LinkedIn / Clearbit |

MQL Threshold: 60 points | Hot (route Tier 1): 90+ | Warm (route Tier 2): 60–89

**ROUTING DECISION TREE (Top Level)**

LEAD ENTERS SYSTEM
  ↓
[Check 1] Is domain in competitor list? → YES → Flag for Competitive Intel, block routing
  ↓ NO
[Check 2] Is company an active Vantiq customer? → YES → Route to CSM + customer marketing tag
  ↓ NO
[Check 3] Is company on Named Account TAL (50 accounts)? → YES → Route to Named Account AE (immediate, no SLA tier — treat as Tier 1)
  ↓ NO
[Check 4] Is there an open Salesforce Opportunity for this account? → YES → Route to Opportunity Owner
  ↓ NO
[Check 5] Run enrichment (Clearbit + 6sense) — get employee count + intent score
  ↓
[Check 6] Employee count > 1,000 OR 6sense Stage 4–5? → Route to Enterprise AE queue (Tier 1 SLA)
           Employee count 200–1,000 AND score ≥ 60? → Route to Platform Modernization AE (Tier 2 SLA)
           Employee count < 200 OR score < 60? → Route to Digital Transformation SDR (Tier 3 SLA)
           Score < 40 regardless of firmographic? → Nurture sequence, no SDR assignment

**REP CONTEXT BRIEF (Auto-Generated at Assignment)**

> **Lead Alert: Tier 1 Demo Request — Vantiq Platform**
>
> **Sarah Chen** | Director of Digital Transformation | **MegaLogix Global** (4,200 employees, $890M revenue, Logistics & Supply Chain)
>
> **Why this lead is hot:** Visited pricing page 3x in 5 days, downloaded "Real-Time AI for Logistics Operations" case study, attended your "Event-Driven Architecture for Operations" webinar last Tuesday (stayed 48 of 52 minutes). 6sense Stage 5 — active vendor evaluation in Real-Time Data Processing category.
>
> **Composite Score:** 127 / 100 (Hot)
>
> **Recommended first message subject:** "MegaLogix + real-time ops — a 12-minute conversation"
>
> **Recommended talk track opener:** "I noticed you attended our webinar on event-driven architecture for logistics — we've worked with three companies your size on exactly the operational AI challenge you're likely evaluating. Worth a quick 12-minute call to see if there's a fit?"
>
> **Reference customers to mention:** DHL Supply Chain (48% reduction in exception handling time), XPO Logistics (real-time visibility across 200 facilities), Geodis (autonomous exception resolution for last-mile).
>
> **Discovery questions to prioritize:** (1) What event-driven or real-time use case is driving this evaluation right now? (2) Are you evaluating Vantiq alongside any streaming platforms like Kafka or Flink? (3) What does "good" look like in 12 months for your operations team?

## Success Metrics

- **MQL-to-SQL conversion rate:** Target 25–35% (industry benchmark for well-routed leads); baseline your current rate before implementation
- **Lead response time (Tier 1):** Under 5 minutes for 90%+ of Tier 1 leads; under 30 minutes for 95%
- **Lead contact rate:** % of routed leads contacted within SLA window; target >92%
- **Routing accuracy rate:** % of leads routed to the correct segment/owner on first assignment; target >95% (measure by SDR/AE override frequency)
- **Revenue leakage metric:** % of MQLs that expire uncontacted; target <3%
- **Rep context brief utilization:** % of reps who view the context brief before first outreach; track in CRM (open event)
- **SLA breach rate:** Track weekly — target <5% breach rate for Tier 1 and Tier 2; zero tolerance for Tier 1 breaches without documented reason

## Related Prompts

- [Marketing Operations KPI Dashboard & Autonomous Performance Reporting](./AI-Powered-B2B-SaaS-Marketing-Operations-Real-Time-KPI-Dashboard-&-Autonomous-Performance-Reporting-Revenue-Intelligence-Engine.md)
- [Marketing Funnel Conversion Audit & Lead Lifecycle Leak Detection](../04_Demand-&-Lead-Generation-&-Growth/Demand-Generation-Operations/AI-Powered-B2B-SaaS-Marketing-Funnel-Conversion-Audit-&-Lead-Lifecycle-Leak-Detection-Revenue-Intelligence-Engine.md)
- [ABM Target Account List Building & ICP Scoring](../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/AI-Powered-ABM-Target-Account-List-Building-&-ICP-Scoring-Intelligence-Engine.md)
- [Lead Scoring Architecture & MQL Pipeline Qualification](../04_Demand-&-Lead-Generation-&-Growth/Demand-Generation-Operations/AI-Powered-B2B-SaaS-Lead-Scoring-Architecture-&-MQL-Pipeline-Qualification-Intelligence-Engine.md)

## Integration Tips

- **Salesforce:** Use Process Builder or Flow to trigger routing automations; log every routing decision as a Task with the rule name in the Description field for full auditability; create a custom "Routing Tier" field on Lead and Contact objects
- **HubSpot:** Use Workflows for scoring and routing; HubSpot's native lead rotation handles round-robin but lacks territory logic — pair with LeanData or Chili Piper Distro for account-match routing
- **LeanData:** Configure as the routing orchestration layer sitting between your MAP and CRM; use LeanData Matching for account deduplication and LeanData Routing for the decision tree — this eliminates 90% of manual routing edge cases
- **Chili Piper:** Use for Tier 1 demo requests — instant calendar scheduling at the moment of form fill eliminates the response time problem entirely for high-intent leads; configure rep pools by territory and segment
- **6sense / Bombora:** Layer intent data into scoring via native CRM integrations; configure segment membership as a scoring trigger in HubSpot/Marketo (e.g., "Account in 6sense Stage 4+ = +40 points") rather than manually reviewing account lists
- **Slack:** Build a dedicated #lead-routing-alerts channel where every Tier 1 assignment fires a Slack message with the lead summary, direct CRM link, and one-click call/email button — reps see it immediately without logging into Salesforce
- **Clearbit Enrichment:** Configure enrichment to run at form submission (webhook) not on CRM save — this ensures routing decisions have complete firmographic data before the first routing rule evaluates
- **Zapier / Make.com:** For teams without LeanData, build the routing logic as Zapier multi-step zaps triggered by CRM lead creation — slower but functional for <300 MQL/month volumes

## Troubleshooting

**Problem: "Enrichment data is wrong or missing for 20–30% of leads, causing routing errors"**
Solution: Implement a dual-enrichment strategy — run Clearbit as the primary enricher and fall back to Apollo or ZoomInfo for failed enrichments. For leads where enrichment confidence is below 80%, route to a dedicated "Needs Review" queue visible to RevOps, not to a rep — and set a 4-hour SLA for manual review before routing. Never route on incomplete data; a 4-hour hold is better than routing to the wrong segment.

**Problem: "Sales reps are ignoring the routing system and cherry-picking leads"**
Solution: This is a governance problem, not a tooling problem. Implement three controls: (1) Remove the ability for reps to see unassigned leads — they can only work leads explicitly assigned to them; (2) Make SLA compliance a visible rep metric in the weekly standup dashboard — social accountability drives behavior; (3) Tie a portion of SDR variable comp to lead contact rate within SLA, not just pipeline generated. Within 30 days of implementing these three controls, SLA compliance typically jumps from 60% to 90%+.

**Problem: "The same lead keeps routing to different reps on repeat form submissions"**
Solution: Build a "prior owner" lookup as the first routing check — before any territory or score-based logic runs, query the CRM for any prior lead or contact record with matching email or company domain. If a prior owner exists and is still active, always route back to that owner. This preserves relationship continuity and eliminates the "six reps contacted the same person" complaint that destroys buyer trust. Use LeanData's "Route to Existing Owner" feature or build this as a SOQL query in a Salesforce Flow.

## Version History
- v1.0: Initial creation (auto-generated)
