# AI-Powered B2B SaaS Technical POC Call Orchestration & Proof-of-Value Management Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** poc, proof-of-value, technical-evaluation, enterprise-sales, b2b, sales-call, deal-velocity, champion, technical-buyer, revenue

## Overview
Automates the complete technical POC and proof-of-value call sequence for enterprise B2B SaaS — generating scoping call agendas, success criteria frameworks, progress check-in scripts, executive readout templates, and objection handling playbooks. Use it when enterprise deals require a structured technical evaluation before executive sign-off to slash POC duration, reduce no-decision outcomes, and turn technical wins into signed contracts.

## Quick Copy-Paste Version

You are a senior enterprise SaaS sales strategist who has closed $100M+ in complex B2B deals requiring technical evaluations, security reviews, and multi-stakeholder proof-of-value engagements. I need you to build a complete POC call orchestration system.

My context:
- Product: [Describe your product and the core technical problem it solves in 2-3 sentences]
- ICP: [Target buyer, company size, industry — e.g., VP Engineering at $100M+ SaaS companies]
- Typical POC request trigger: [What usually triggers a customer asking for a POC — e.g., "after second demo when 3+ technical stakeholders are involved"]
- POC success definition (your side): [What outcome makes this POC a win — e.g., "data pipeline runs successfully in their environment and latency benchmarks beat their current tool"]
- Typical POC duration: [e.g., 3 weeks]
- Top 3 POC failure modes: [Why POCs stall or result in no-decision — e.g., "champion goes dark," "IT security blocks deployment," "scope creep kills timeline"]

Build me:

1. POC SCOPING CALL AGENDA (45-minute pre-POC kickoff)
   - Agenda to define success criteria, timeline, stakeholders, and technical requirements before the POC begins
   - Success criteria co-creation framework (prospect + AE agree on what "win" looks like in writing)
   - Go/No-Go gate: what must be agreed before POC officially starts

2. POC KICKOFF CALL SCRIPT (30-minute first-day alignment call)
   - Stakeholder introductions and role assignments
   - Live review of the agreed success criteria document
   - Week-by-week milestone schedule
   - Technical onboarding steps with owner and due date

3. POC PROGRESS CHECK-IN FRAMEWORK (weekly, 30 minutes)
   - Green/Yellow/Red status across each success criterion
   - Early warning signals that predict POC failure
   - Escalation script for when POC is at risk

4. EXECUTIVE READOUT PRESENTATION STRUCTURE
   - How to present POC results to economic buyer in 20 minutes
   - Before/after metrics format with specific numbers
   - Business case narrative linking technical results to revenue impact

5. TECHNICAL OBJECTION HANDLING PLAYBOOK
   - Top 5 technical objections during POC evaluation
   - Response scripts that address security, integration, performance, and implementation complexity

## Advanced Customizable Version

### Role
You are an elite enterprise SaaS sales architect and revenue operations consultant specializing in complex technical evaluations, proof-of-concept orchestration, and multi-stakeholder deal acceleration. You have led POC programs at SaaS companies from $20M to $2B ARR and understand how to convert technical wins into signed contracts while managing champion risk, security review delays, and scope creep.

### Context

**Product:**
- Company name: [Company name]
- Product category: [e.g., data observability platform, cloud security posture management, revenue intelligence]
- Core technical value proposition: [One sentence: "We enable [technical buyer] to [achieve technical outcome] by [mechanism]"]
- Deployment model: [Cloud SaaS / Hybrid / On-Prem agent / API integration]
- Primary integration dependencies: [e.g., "must connect to Snowflake, dbt, and Jira"]
- Typical security review requirements: [e.g., SOC 2 Type II, SSO/SAML, data residency, penetration test results]

**Ideal Customer Profile:**
- Segment: [Mid-Market / Enterprise / Strategic]
- Company revenue: [e.g., $100M–$2B]
- Industries: [e.g., fintech, e-commerce, healthcare]
- Primary technical buyer: [e.g., VP Engineering, VP Data, CISO, CTO]
- Economic buyer: [e.g., CFO, CTO, COO]
- Typical POC stakeholders: [e.g., "Engineering lead, data platform team, IT security, and the VP who sponsors the initiative"]

**POC Economics:**
- Average contract value: [ACV — e.g., $120,000/year]
- Typical sales cycle: [days — e.g., 90–120 days]
- POC duration (target): [weeks — e.g., 3 weeks]
- POC duration (actual average): [weeks — e.g., 6 weeks, when unmanaged]
- Win rate when POC completes on time: [e.g., 72%]
- Win rate when POC extends past target: [e.g., 31%]
- Top 3 POC failure modes: [e.g., (1) champion goes dark or gets reassigned, (2) IT security blocks deployment indefinitely, (3) technical team proves the point but economic buyer never sees results]

**Success Criteria Framework:**
- Primary technical proof point: [e.g., "data pipeline ingestion latency under 200ms at 10M events/hour"]
- Secondary proof point: [e.g., "alert noise reduction >40% vs. current tooling"]
- Business outcome the EB cares about: [e.g., "engineering team reclaims 15+ hours/week spent firefighting data quality incidents"]

### Objective
Generate a complete, field-ready Technical POC Call Orchestration System that AEs and Solutions Engineers can execute immediately — from scoping call through executive readout — with zero additional editing required. Every template must be specific to the product, ICP, and POC dynamics above.

### Output Requirements

#### 1. PRE-POC SCOPING CALL SYSTEM

**Purpose:** Establish written agreement on success criteria, stakeholder roles, and timeline before a single line of code runs. A POC without a signed success criteria document is a free consulting engagement.

**Pre-Call Preparation Checklist:**
- Account intelligence to gather 24 hours before scoping call: current tech stack (technographic data), open engineering/data job postings (signals team growth and pain areas), any recent incident reports or Glassdoor mentions of technical friction
- Champion pre-brief: 15-minute call to align on who will attend and what political landmines to avoid in the full scoping session
- Pre-read to send 48 hours before: one-page POC overview document + blank success criteria template for prospect to populate in advance

**Scoping Call Agenda (45 minutes):**

| Time | Segment | Goal | AE/SE Lead |
|------|---------|------|------------|
| 0–5 min | Welcome + attendee roles | Confirm who is in the room and their POC stake | AE |
| 5–15 min | Current state assessment | Understand exact pain, tooling gaps, and what triggered the evaluation | SE |
| 15–25 min | Success criteria co-creation | Define 3–5 measurable criteria that constitute a definitive win | AE + SE |
| 25–35 min | Technical requirements + blockers | Uncover security, data access, and integration requirements before kickoff | SE |
| 35–42 min | Stakeholder map + escalation path | Name every person who can block or accelerate the POC | AE |
| 42–45 min | Go/No-Go gate + next steps | Confirm written success criteria agreement; schedule kickoff call | AE |

**Success Criteria Co-Creation Framework:**

Use this live during the scoping call. Do not pre-fill it — build it with the prospect in real time so they own it.

| Success Criterion | Measurement Method | Target Threshold | Current Baseline | Owner (Prospect) | Owner (Vendor) | Week Due |
|------------------|--------------------|-----------------|-----------------|-----------------|----------------|---------|
| [Technical KPI 1] | [How measured — e.g., "API latency log export"] | [Threshold — e.g., "<200ms p95"] | [Current state] | [Prospect engineer name] | [SE name] | [Week 2] |
| [Technical KPI 2] | [How measured] | [Threshold] | [Current state] | [Owner] | [SE name] | [Week 2] |
| [Business KPI 1] | [How measured — e.g., "Hours tracked in JIRA ticket"] | [Threshold] | [Current state] | [Champion name] | [AE name] | [Week 3] |

**Go/No-Go Gate — Required Before POC Starts:**
- [ ] Success criteria document signed (or email-confirmed) by champion AND technical lead
- [ ] Economic buyer briefed on POC launch and expected business outcome
- [ ] IT/Security requirements identified — timeline for access provisioning confirmed
- [ ] Week-by-week milestone schedule agreed
- [ ] Escalation path documented: "If POC is blocked for more than 3 business days, [Champion name] will contact [AE name] and we will jointly decide whether to extend or modify scope"

**POC Go/No-Go Decision Script:**
> "Before we wrap up today — I want to make sure we're set up to run the tightest, most valuable evaluation possible. The single biggest factor in whether a POC delivers clear results is whether we've defined success in writing before we start. Can we agree right now on the three outcomes that would make this evaluation a clear win? If we can capture that today, I'll turn it into a one-page document and send it to you by end of day for your team to confirm. Does that work?"

#### 2. POC KICKOFF CALL SYSTEM

**Purpose:** Formally launch the POC with all stakeholders aligned, accountability assigned, and the first week's tasks clear before anyone leaves the call.

**Pre-Kickoff Checklist (AE/SE):**
- Confirmed success criteria document circulated and accepted 24 hours before kickoff
- Technical environment access provisioned or with explicit ETA confirmed
- Technical SE brief completed: SE knows the top 2 integration risks for this account
- Kick-off deck built: 10 slides max — agenda, success criteria, week-by-week milestones, stakeholder RACI chart

**Kickoff Call Agenda (30 minutes):**

| Time | Segment | Content |
|------|---------|---------|
| 0–3 min | Introductions | Names, roles, and "one thing you need this POC to prove" round-robin |
| 3–8 min | Success criteria review | Walk through the agreed document line by line — confirm no surprises |
| 8–15 min | Week-by-week milestone plan | Assign owners to each milestone; flag any pre-conditions |
| 15–22 min | Technical onboarding steps | SE walks through Day 1 setup tasks with specific owner and due date |
| 22–27 min | POC rules of engagement | Communication cadence, escalation path, scope change protocol |
| 27–30 min | First action items | Each stakeholder states their Week 1 commitment before call ends |

**RACI Chart Template:**

| Task | Prospect Technical Lead | Champion | IT/Security | AE | SE |
|------|------------------------|---------|-------------|----|----|
| Environment access provisioning | R | A | R | I | I |
| Integration setup | R | I | C | I | R |
| Test data preparation | R | I | I | I | C |
| Success criteria measurement | R | A | I | I | C |
| Weekly progress reporting | R | A | I | I | I |
| Executive readout scheduling | I | R | I | A | I |

**Rules of Engagement Script:**
> "A few ground rules that keep POCs on track — in our experience, these are what separate the evaluations that deliver clear results from the ones that drift. First, we'll have a 30-minute check-in every [day/week] on [day] at [time] — please protect that time. Second, if anything blocks progress for more than two business days, we escalate immediately rather than waiting for the next check-in. Third, any request to expand POC scope outside of these three success criteria requires both our sign-off — not because we're rigid, but because scope creep is the single most common reason POCs run long and lose their business case. Does everyone agree to operate that way?"

#### 3. WEEKLY POC PROGRESS CHECK-IN SYSTEM

**Check-In Agenda (30 minutes):**

| Time | Segment | Purpose |
|------|---------|---------|
| 0–3 min | Status dashboard review | Red/Yellow/Green against each success criterion |
| 3–12 min | Progress walkthrough | Technical lead demos results-to-date on each KPI |
| 12–18 min | Blockers + risk review | Surface anything threatening timeline or scope |
| 18–25 min | Week ahead tasklist | Confirm next week's tasks, owners, and deadlines |
| 25–28 min | Champion sync | Private 3 minutes with champion — political temperature check |
| 28–30 min | Next check-in confirmation | Confirm date, time, and attendees for following week |

**POC Status Dashboard:**

| Success Criterion | Target | Current Status | Week 1 Actual | Week 2 Actual | Week 3 Actual | Status |
|------------------|--------|---------------|---------------|---------------|---------------|--------|
| [KPI 1] | [Threshold] | [Value] | | | | 🟢 / 🟡 / 🔴 |
| [KPI 2] | [Threshold] | [Value] | | | | 🟢 / 🟡 / 🔴 |
| [Business KPI] | [Threshold] | [Value] | | | | 🟢 / 🟡 / 🔴 |

**POC Risk Early Warning System:**

| Warning Signal | What It Means | Intervention |
|---------------|---------------|-------------|
| Champion misses two consecutive check-ins | Deprioritization or internal politics shift | AE to reach out via personal channel within 24 hours; request private call with champion |
| Technical lead stops responding to SE | Technical blocker, competing priority, or scope confusion | SE escalation call with champion to identify root cause |
| IT/Security review requests > 5 new documents | Procurement process has been activated — timeline will extend | AE to request a joint call with champion and IT lead to scope security requirements and set realistic completion date |
| Prospect requests scope expansion | Positive buying signal OR stall tactic | AE to acknowledge enthusiasm, reaffirm original scope, offer Phase 2 roadmap discussion post-contract |
| No champion access to economic buyer after Week 2 | EB is uninvested or champion is not internal-selling | AE to directly request a 20-minute "sponsor update" call with EB to share Week 2 results |

**At-Risk POC Escalation Script:**
> "[Champion name], I want to flag something before our next team check-in. Looking at the progress tracker, we're at [X] on [KPI] against a target of [Y] — we're on track, but [blocker] is starting to compress our timeline. I'd rather address this now than push the evaluation date. Can you and I spend 15 minutes before the team call today to align on how to resolve [blocker]? I'll have a proposed solution ready."

#### 4. EXECUTIVE READOUT SYSTEM

**Purpose:** Present technical POC results to the economic buyer in a format that translates engineering proof points into business case language that justifies the investment.

**Readout Scheduling Script (use when champion has not yet booked EB):**
> "We're heading into Week 3 of the evaluation, and the results are strong — [KPI 1] is tracking at [X% above] the target threshold. I want to make sure [Economic Buyer name] sees this in a format that connects the technical results to the business case we discussed in our first conversation. Can we get 20 minutes on [EB's] calendar before end of evaluation? I'll send you the readout deck 48 hours in advance so [EB] can come prepared with questions. This isn't a sales meeting — it's a results briefing."

**Executive Readout Deck Structure (20-minute presentation):**

**Slide 1 — Context Setting (2 min)**
> "Three weeks ago, we agreed to evaluate [product] against three specific criteria. Here is exactly what we set out to prove — in your team's own words."
[Show the signed success criteria document]

**Slide 2 — Results Summary (5 min)**
> "Here is what we measured, how we measured it, and where we finished."

| Success Criterion | Target | Result | Status |
|------------------|--------|--------|--------|
| [Technical KPI 1] | [Threshold] | [Actual] | ✅ Achieved / ⚠️ Partial / ❌ Not achieved |
| [Technical KPI 2] | [Threshold] | [Actual] | ✅ / ⚠️ / ❌ |
| [Business KPI] | [Threshold] | [Actual] | ✅ / ⚠️ / ❌ |

**Slide 3 — Business Impact Translation (5 min)**
> "Here is what the technical results mean in terms your business cares about."

| Technical Result | Business Translation | Annual Dollar Impact |
|-----------------|---------------------|---------------------|
| [e.g., "Latency reduced 60%"] | [e.g., "Engineering team recovers 18 hours/week from incident response"] | [e.g., "18 hrs × 50 weeks × $85/hr avg engineer cost = $76,500/year"] |
| [Technical result 2] | [Business translation] | [$X/year] |
| **Total Identified Value** | | **$[Sum]/year** |

**ROI Framing for Economic Buyer:**
> "Against an annual investment of $[ACV], the identified value from this evaluation alone is $[Sum] — that's a [X]x return in year one, with payback in [Y] months. And we've only quantified the two proof points from the evaluation; there are [N] additional capabilities we did not activate during the POC that [champion name]'s team has already flagged as high-priority for Phase 2."

**Slide 4 — Implementation Path (3 min)**
- Week 1–2: Production onboarding and data migration (supported by SE team)
- Week 3–4: Team training and workflow integration
- Week 6: Full operational state — first business review scheduled
- Named SE/CSM who will own post-sale implementation

**Slide 5 — Decision Path (5 min)**
- Proposed contract terms and start date
- What happens this week vs. next week if decision is delayed (cost of inaction math)
- Two paths forward: "Yes" path (next steps), "More information" path (what would close the gap?)

**Closing Statement for EB Readout:**
> "[EB name], the evaluation proved what we believed coming in — the technical results are strong. The business case is clear. The implementation path is defined. The only question remaining is whether this is the right time for your organization. What would help you make that decision with confidence today?"

#### 5. TECHNICAL OBJECTION HANDLING PLAYBOOK

**Objection 1: "Our security team needs to review this before we can go to production."**

*What it actually means:* Security review was not scoped in advance. This is now a weeks-long process that will push close date by 4–8 weeks if not accelerated immediately.

*Response:*
> "Completely expected — and something we should have mapped more explicitly in our scoping session. Let's make this fast: our security package includes SOC 2 Type II report, pen test results, data processing agreements, and answers to the top 40 security questionnaire questions. Can you introduce me to your security lead today? If we get in a room with them this week, we can typically compress a 6-week security review into 10 business days because we've done this 200+ times and can answer their questions live rather than via async document review. What's the best way to connect?"

**Objection 2: "The integration with [our existing tool] didn't work as expected."**

*What it actually means:* Integration scope was not defined precisely enough, or the technical lead encountered an edge case that needs SE involvement.

*Response:*
> "Thank you for flagging this before we submitted results — this is exactly why we have weekly check-ins. Can you and [SE name] get on a call today? Walk us through specifically what you expected versus what you saw. In 90% of cases, this is a configuration issue we can resolve in under an hour. In the remaining 10%, it is a legitimate gap that we need to document honestly. Either way, you deserve a clear answer before the evaluation closes, not an assumption. What's your availability in the next two hours?"

**Objection 3: "We want to extend the POC by four more weeks."**

*What it actually means:* One of three scenarios: (a) the champion does not yet have enough internal confidence to push for a decision, (b) a competing priority has de-ranked the evaluation, or (c) the prospect is using extension as a no-cost delay tactic.

*Response (Champion-first):*
> "[Champion name], before we discuss the timeline, help me understand what an additional four weeks would need to prove that the existing three weeks have not already demonstrated. If there's a specific gap — a use case we haven't tested, a stakeholder we haven't engaged — I want to address that directly. If the evaluation has proved what we set out to prove and the path forward is a decision conversation, I would rather spend that time helping you build the internal business case than extending the technical evaluation. What's creating the hesitation?"

**Objection 4: "Your performance results are good, but [Competitor] claims they can do the same thing."**

*What it actually means:* Prospect has been re-engaged by a competitor during the POC and is using that as leverage, or is genuinely unsure whether your differentiation is real.

*Response:*
> "That's a fair question to stress-test. Let me separate two things: what [Competitor] claims and what we've demonstrated in your environment with your data. The results you saw in Week 2 — [specific metric] at [specific number] — are not marketing claims. They are measurements from your production data. The question is not whether [Competitor] can match a benchmark on their test environment; it is whether they can match your specific results in your environment. I'd suggest running the same three success criteria against [Competitor] before making a comparison — it's the only fair test. Want me to help you design that evaluation structure if you decide to pursue a parallel assessment?"

**Objection 5: "We need to run this by IT before we can proceed."**

*What it actually means:* The champion does not have organizational authority to advance the decision, or IT was never part of the buying process and is now being introduced as a gatekeeper.

*Response:*
> "Understood — IT sign-off is standard in [industry] and we've navigated this process with companies like yours many times. Two paths: First, we can fast-track the IT review using our pre-built security package — would you like to introduce us to your IT lead so we can proactively answer their questions? Second, let's make sure this evaluation doesn't lose momentum while IT reviews — can we schedule the executive readout for [EB] while the IT process runs in parallel? The technical evaluation is complete; what [EB] sees should be the business case results, not a dependency on a process that is already underway. Which of those two paths would you prefer to start with?"

### Constraints
- All call scripts must be conversational and non-transactional — the prospect should feel guided, not pressured
- Every escalation script must be available in a champion-only version (direct, private) and a full-group version (diplomatic, public)
- The executive readout must be executable in exactly 20 minutes — no slide should exceed 2 minutes of talk time
- All success criteria templates must integrate with Salesforce Opportunity fields and HubSpot Deal properties without reformatting
- POC status dashboard must be exportable to a Slack message, Google Slides, or PDF with one-click simplicity
- Technical objection responses must never disparage competitors by name — redirect to proof and process

## Example Input/Output

**Example Input:**
Product: Helios Data — a real-time data pipeline observability platform that monitors data quality, latency, and freshness across Snowflake, dbt, and Fivetran stacks
ICP: VP Data or VP Engineering at $100M–$1B SaaS companies with 10+ data engineers
Typical POC trigger: After second demo when data engineering lead confirms they have 3+ data quality incidents per month
POC success criteria: (1) Helios detects a simulated data quality incident in <5 minutes vs. current 4-hour mean-time-to-detect, (2) Alert noise below 15 alerts/week (vs. 80+ currently), (3) On-call rotation hours reduced by >30%
Typical POC duration: 3 weeks target, 5.5 weeks actual
Top 3 failure modes: (1) IT security blocks API credentials provisioning for 2–3 weeks, (2) Champion (usually data engineering lead) gets pulled into a major product sprint and stops attending check-ins, (3) Technical results are proven but economic buyer (VP Data or CTO) never sees a business case readout and decision defaults to "let's revisit next quarter"

**Example Output (Excerpts):**

*Scoping Call Success Criteria Co-Creation (live example):*
> "Alright — before anyone spends a minute of engineering time on setup, I want to make sure we agree on exactly what 'win' looks like. I've seen too many evaluations where the engineering team loved the product but couldn't clearly articulate a business case to the CTO. So here's what I'd like to do: let's define three specific, measurable outcomes that would make you confident recommending Helios. Based on what you've shared today, I'm hearing [KPI 1], [KPI 2], and [KPI 3] — does your team agree those are the right three? And more importantly: if Helios delivers all three, is there any other reason you would not move forward with a contract? I want to surface those now rather than after we've proven the technology."

*Week 2 Champion At-Risk Script (Helios Data context):*
> "Hey [Data Engineering Lead] — I noticed you weren't on Monday's check-in. The data quality simulation results from Week 1 are looking great — we're at 4.2 minutes MTTD against your 5-minute target. But I want to make sure we stay on track for the executive readout with [CTO name] that we scheduled for Week 3. Do you have 15 minutes tomorrow to walk me through what's on your plate right now? I want to understand if we need to adjust the POC timeline or get additional support from our SE team to keep this moving."

*Executive Readout Business Case Slide (Helios Data example):*

| Technical Result | Business Translation | Annual Value |
|-----------------|---------------------|-------------|
| MTTD reduced from 4 hours to 4.2 minutes — 98% faster | On-call engineers no longer spend 4 hours per incident manually tracing data lineage | 3 incidents/month × 4 hrs × 12 months × $95/hr avg engineer = $13,680/year per engineer; across 5 on-call engineers = **$68,400/year** |
| Alert noise reduced from 84/week to 9/week — 89% reduction | Engineering team eliminates 75 false-positive triage sessions per week | 75 alerts × 20 min each × 50 weeks × $95/hr = **$118,750/year** |
| On-call rotation hours reduced 44% | Senior engineers reclaim 8 hours/week from reactive incident response | 8 hrs × 50 weeks × $95/hr × 3 senior engineers = **$114,000/year** |
| **Total Identified Annual Value** | | **$301,150/year** |
| **Annual Investment (Helios Data)** | | **$96,000/year** |
| **ROI** | | **3.1x return; 4-month payback** |

> "The evaluation has produced $301K in identified annual value against a $96K investment — a 3.1x first-year return with a 4-month payback. And we only measured the three criteria from the POC. Your team flagged data lineage visualization and cross-pipeline impact analysis as Phase 2 priorities; we have not quantified those yet. The business case you have in front of you is conservative."

## Success Metrics
- POC completion rate (% that finish within original timeline): target ≥80% (industry baseline: 45–55%)
- POC-to-closed-won conversion rate: target ≥65% (industry baseline: 40–50%)
- Average POC duration vs. target: target within 5 business days of agreed timeline
- Executive readout completion rate (% of POCs where EB sees results): target ≥90%
- Technical objection resolution time: target <2 business days from identification to resolution
- Security review cycle time: target <15 business days from introduction to IT lead
- Champion engagement score (check-in attendance rate): target ≥85% across all scheduled check-ins

## Related Prompts
- [AI-Powered B2B Discovery Call Optimization & MEDDIC Qualification Automation Intelligence Engine](./AI-Powered-B2B-Discovery-Call-Optimization-&-MEDDIC-Qualification-Automation-Intelligence-Engine.md)
- [AI-Powered B2B Enterprise Sales Negotiation Intelligence & Multi-Stakeholder Deal Closing Acceleration Engine](./AI-Powered-B2B-Enterprise-Sales-Negotiation-Intelligence-&-Multi-Stakeholder-Deal-Closing-Acceleration-Engine.md)
- [AI-Powered B2B Active Deal Pipeline Influence & Buying Committee Orchestration Intelligence Engine](../Account-Based-Marketing/AI-Powered-B2B-Active-Deal-Pipeline-Influence-&-Buying-Committee-Orchestration-Intelligence-Engine.md)
- [AI-Powered B2B Enterprise POC Marketing & Technical Buyer Conversion Intelligence Engine](../../02_Product-Marketing/Sales-Enablement/AI-Powered-B2B-Enterprise-POC-Marketing-&-Technical-Buyer-Conversion-Intelligence-Engine.md)

## Integration Tips
- **Salesforce:** Create a POC Stage on the Opportunity object with custom fields: POC Start Date, POC Target End Date, Success Criteria Document URL, POC Status (On Track / At Risk / Extended / Complete), MTTD Result, Alert Noise Result, Business Value Identified ($). Build a workflow that emails AE manager when POC Status changes to "At Risk."
- **HubSpot:** Create a POC pipeline stage with required properties matching success criteria fields. Build a sequence that auto-sends the Success Criteria Template to champion 48 hours after POC stage is entered, then triggers weekly check-in reminders to the AE every Monday at 8am.
- **Gong / Chorus:** Add POC-specific trackers: "success criteria," "security review," "when does the evaluation end," "who else needs to see results," "executive readout." Flag calls where none of these keywords appear — it usually indicates a drifting POC with no agreed end state.
- **Notion:** Build a POC Tracker template with a database for each active POC: success criteria table, RACI chart, weekly status dashboard, and executive readout deck link. Shared with both AE/SE and champion for mutual visibility.
- **Slack:** Create a #active-pocs channel. AE posts a 3-line status update every Friday: KPI progress, blockers, and next week's critical action. Tag champion on the external shared Slack channel (if your account allows it) for joint accountability.
- **DocuSign / Pandadoc:** E-sign the Success Criteria Agreement before the POC starts. Counterintuitively, asking a prospect to sign a one-page document listing the three things you will prove dramatically reduces scope creep and no-decision outcomes — it signals mutual commitment and creates a shared standard for "done."

## Troubleshooting
- **Problem:** The champion agrees on success criteria verbally but will not sign or email-confirm the document before the POC starts.
  **Solution:** Do not start the POC. A champion who will not commit to written success criteria before the evaluation begins will not champion the results after the evaluation ends. Frame it this way: "I want to make sure your team gets full credit for the results we're about to generate. Having this document means that when [Economic Buyer name] asks 'did we test this?' — you have a clear, dated answer. It protects your team as much as it protects us. Can we spend 10 minutes right now getting this into writing?" If they still resist, treat it as a qualification signal and escalate with your manager before allocating SE resources.

- **Problem:** The POC technical results are strong, but the economic buyer has not attended the readout and keeps rescheduling.
  **Solution:** The EB is not invested. Send the executive readout deck directly to the EB via champion with this note: "I'd love to walk [EB name] through this live, but I also want to make sure the results don't sit in a queue waiting for calendar time. Here's a 5-minute video walkthrough I recorded — it covers the business case in the format I'd use in a live readout. If [EB name] has any questions after watching, I'm available at their convenience." Use Loom or Vidyard. A video that can be consumed asynchronously in 5 minutes is often more EB-friendly than a 30-minute meeting request.

- **Problem:** IT security has been reviewing the product for six weeks and is still not done, but the champion says they're close.
  **Solution:** IT security reviews that are "almost done" for more than three weeks are typically stuck in a queue, not close to completion. Request a joint call between you, the champion, and the IT security lead specifically to scope remaining open items, set a concrete completion date, and understand what accelerating the review would require. Bring your security engineer, VP of Engineering, or CISO to that call if needed — peer-to-peer technical conversation compresses security reviews dramatically faster than email chains between non-technical stakeholders.

## Version History
- v1.0: Initial creation (auto-generated)
