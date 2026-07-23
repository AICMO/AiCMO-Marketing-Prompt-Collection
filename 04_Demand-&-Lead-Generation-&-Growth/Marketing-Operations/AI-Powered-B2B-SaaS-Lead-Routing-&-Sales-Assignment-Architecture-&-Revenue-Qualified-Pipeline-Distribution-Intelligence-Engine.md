# AI-Powered B2B SaaS Lead Routing & Sales Assignment Architecture & Revenue-Qualified Pipeline Distribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** b2b-saas, lead-routing, sales-assignment, marketing-operations, revenue-operations, hubspot, salesforce, leandata, chili-piper, round-robin, territory-management, pipeline-velocity, crm-automation

## Overview
Designs a complete AI-powered lead routing and sales assignment system that instantly distributes inbound leads, demo requests, and product signups to the right sales rep — based on score tier, territory, company segment, ACV potential, and rep capacity — eliminating manual triage and ensuring every high-intent buyer gets a response within minutes, not days. Use this when you have a lead response time problem, a territory conflict problem, or when leads are falling through the cracks between marketing and sales.

## Quick Copy-Paste Version

You are a revenue operations architect specializing in lead routing and sales assignment systems for B2B SaaS companies. Design a complete lead routing architecture for the company below.

COMPANY SNAPSHOT:
- Company: [Company name and product — e.g., "Meridian AI, a sales forecasting platform for B2B SaaS revenue teams"]
- Current ARR: [e.g., $12M ARR]
- Sales team structure: [e.g., "6 SDRs (inbound + outbound), 8 AEs split by segment: 3 SMB, 3 mid-market, 2 enterprise; 1 Sales Ops manager"]
- Segments & ACV ranges: [e.g., "SMB: <$10K ACV, Mid-Market: $10K–$50K ACV, Enterprise: >$50K ACV"]
- Lead sources to route: [e.g., "Demo requests, free trial signups, contact form, inbound chat, webinar registrants, event badge scans"]
- Territory model: [e.g., "Named accounts for enterprise (top 500 list), geographic territories for mid-market (East/West/Central), round-robin for SMB"]
- Current routing method: [e.g., "Manual — SDR manager assigns leads in Salesforce each morning; 12–18 hour average first response time"]
- CRM/MAP stack: [e.g., "Salesforce + Outreach + Chili Piper / HubSpot + Salesloft + HubSpot Meetings"]
- Key pain: [e.g., "Hot leads wait 18+ hours for response; enterprise leads routed to SMB reps; no cap on SDR queues causing rep burnout"]
- Lead volume: [e.g., "~250 inbound leads/month; 60 demo requests; 120 free trial signups"]

DELIVERABLES REQUIRED:
1. ROUTING DECISION TREE: Complete logic flowchart from lead submission to rep assignment — including all branch conditions (segment, territory, score, rep availability, business hours, overflow).
2. SEGMENT QUALIFICATION CRITERIA: Exact firmographic and behavioral signals used to classify each lead into SMB/Mid-Market/Enterprise before routing.
3. ASSIGNMENT RULES BY SEGMENT: Specific routing logic per segment — named account matching for enterprise, geographic/industry territory for mid-market, weighted round-robin for SMB — with rep capacity caps.
4. RESPONSE TIME SLAs: Required first-response time by lead tier and segment. Include business hours vs. after-hours handling and escalation triggers.
5. LEAD SOURCE ROUTING MATRIX: Table mapping each lead source (demo request, trial signup, chat, webinar, event) to the appropriate routing path and initial sales motion.
6. OVERFLOW & FALLBACK RULES: What happens when the assigned rep is at capacity, out of office, or doesn't respond within SLA — with auto-escalation logic.
7. CRM AUTOMATION WORKFLOWS: Specific workflow steps to implement in Salesforce or HubSpot that execute this routing logic without human intervention, including field mappings and triggers.
8. ROUTING PERFORMANCE METRICS: KPIs to track — speed-to-lead, assignment accuracy rate, fallback rate, rep utilization — with target benchmarks.

Every output must be directly implementable with specific field names, workflow triggers, and assignment logic — not a conceptual framework.

## Advanced Customizable Version

ROLE: You are a Revenue Operations architect with 14+ years of experience designing lead routing and sales assignment systems for B2B SaaS companies scaling from $5M to $200M ARR. You have built routing systems on Salesforce (with LeanData, Chili Piper, and native assignment rules), HubSpot (with native workflows and Chili Piper), and custom RevOps stacks. You understand that most B2B companies lose 35–50% of inbound pipeline value to slow lead response and misrouted leads — and you know that a properly architected routing system is worth more than doubling your SDR headcount.

Your north star is revenue velocity, not lead volume. You design systems that guarantee the right rep reaches the right buyer within the right time window — with zero manual triage.

COMPANY CONTEXT:
Company Name: [Full name]
Product: [Detailed description — core use case, primary buyer workflow automated, measurable ROI delivered to customers]
Current ARR: [Exact or range]
Growth stage: [Seed / Series A / Series B / Series C / Growth / Pre-IPO]
Fiscal year: [Calendar year or specify]

SALES TEAM ARCHITECTURE:
SDR team: [Number of SDRs, split between inbound-focused vs. outbound-focused if applicable]
AE team by segment: [Number of AEs per segment with segment names and ACV ranges]
Named accounts: [Do enterprise AEs own a named account list? How many accounts per AE?]
Overlay teams: [Solutions engineers, overlay specialists, or industry-focused reps? When do they get involved?]
Geographic coverage: [Territories by region, country, time zone — specify gaps in coverage]
Capacity model: [Target number of active opportunities per AE by segment; SDR daily activity quotas]
Rep availability signals: [How does the system know if a rep is at capacity, OOO, or has blocked calendar time?]

SEGMENTATION ARCHITECTURE:
Define each segment with exact criteria:

Segment 1 — [Name, e.g., "SMB"]:
- Employee count range: [e.g., "1–99 employees"]
- Revenue range (if available): [e.g., "<$10M ARR"]
- Funding stage (if SaaS): [e.g., "Bootstrap or Pre-Seed"]
- ACV expectation: [e.g., "$3K–$10K ACV"]
- Sales motion: [e.g., "Product-led or low-touch inbound AE — no SDR step"]
- Routing destination: [e.g., "Automated self-serve sequence → SMB AE round-robin if they request a demo"]

Segment 2 — [Name, e.g., "Mid-Market"]:
- Employee count range: [e.g., "100–999 employees"]
- Revenue range: [e.g., "$10M–$200M ARR"]
- Funding stage: [e.g., "Series A–C"]
- ACV expectation: [e.g., "$12K–$45K ACV"]
- Sales motion: [e.g., "SDR qualifies → AE runs discovery → SE joins for technical eval"]
- Routing destination: [e.g., "SDR round-robin → AE by geographic territory"]

Segment 3 — [Name, e.g., "Enterprise"]:
- Employee count range: [e.g., "1,000+ employees"]
- Revenue range: [e.g., ">$200M ARR"]
- Funding stage: [e.g., "Late-stage or public"]
- ACV expectation: [e.g., ">$50K ACV, often $100K+"]
- Sales motion: [e.g., "Named account AE owns account; SDR supports with multi-threading"]
- Routing destination: [e.g., "Named account lookup → assigned enterprise AE; if not on named list → enterprise AE round-robin"]

TERRITORY MODEL:
Enterprise territory type: [Named accounts / vertical-based / hybrid]
Named account list size: [Total accounts and accounts per AE]
Mid-market territory type: [Geographic / industry vertical / hybrid / round-robin]
Territory coverage map: [List regions or verticals with assigned rep names/teams]
Territory conflict resolution: [What happens when a lead matches two territories? Who decides?]
Expansion territory: [International markets — which countries are covered, which are unassigned?]

LEAD SOURCES & INBOUND CHANNELS:
List every lead source with current volume and priority:

| Lead Source | Monthly Volume | Intent Signal | Priority Tier | Notes |
|---|---|---|---|---|
| Demo request form | [X] | High | Tier 1 | [Any qualification questions on form?] |
| Free trial signup | [X] | Medium–High | Tier 1–2 | [PQL scoring applied?] |
| Contact us form | [X] | Medium | Tier 2 | [Generic — needs qualification] |
| Inbound chat (Drift/Intercom) | [X] | High (live) | Tier 1 | [Business hours only?] |
| Webinar registrant | [X] | Medium | Tier 2 | [Attended vs. registered split?] |
| Content download (gated) | [X] | Low–Medium | Tier 3 | [MQL score required before routing?] |
| Partner referral | [X] | High | Tier 1 | [Routes to partner-aligned AE?] |
| Event badge scan | [X] | Medium | Tier 2 | [Time-sensitive post-event routing?] |
| Inbound call | [X] | Very High | Tier 1 | [Routes to SDR on-call?] |

ENRICHMENT & SIGNAL STACK:
Enrichment tool: [Clearbit, ZoomInfo, Apollo, Cognism, etc. — what data is auto-appended at lead creation]
Intent data: [6sense, Bombora, G2 Buyer Intent — how intent signals modify routing priority]
CRM data: [Existing account/contact data used to match against — account ownership, prior opportunities, blacklist]
Lead scoring output: [Does a lead score or MQL score feed into routing priority? Describe the scoring tiers]

TECH STACK:
CRM: [Salesforce / HubSpot / other]
Routing tool: [LeanData / Chili Piper / Salesforce native assignment rules / HubSpot native workflows / RingLead / Openprise / custom]
Sales engagement: [Outreach / Salesloft / Apollo / HubSpot Sequences]
Meeting scheduling: [Chili Piper / Calendly / HubSpot Meetings / direct AE calendar]
Chat: [Drift / Intercom / HubSpot Chat / Qualified]
Enrichment: [Clearbit / ZoomInfo / Apollo / Cognism]

CURRENT STATE DIAGNOSIS:
Current routing method: [Manual / automated / hybrid — describe exactly]
Current average speed-to-lead (high-intent): [X hours/minutes]
Current MQL-to-meeting-booked conversion: [X%] (benchmark: 20–35% for inbound demo requests)
Current SDR accept rate for inbound leads: [X%] (benchmark: >80%)
Top routing failures observed: [e.g., "Enterprise leads going to SMB reps; weekend leads sitting until Monday; rep OOO leaves leads unassigned for 5 days"]
Current territory conflicts: [Describe recurring conflict patterns]

---

DESIGN THE COMPLETE ROUTING SYSTEM — Build ALL components:

**MODULE 1: LEAD CLASSIFICATION ENGINE**

Before any lead can be routed, it must be classified. Design the classification system:

1.1 FIRMOGRAPHIC CLASSIFICATION
Using enrichment data auto-appended at lead creation, define the exact field logic to classify every lead into a segment:
- Primary classification signal: [e.g., employee count from Clearbit Enrichment]
- Secondary override signals: [e.g., funding round from Crunchbase, annual revenue from ZoomInfo]
- Classification hierarchy: [What wins when signals conflict — e.g., "If employee count says SMB but funding round is Series C+, classify as Mid-Market"]
- Missing data handling: [What to do when enrichment fails — default segment, alert, or manual review queue]

1.2 INTENT & BEHAVIOR CLASSIFICATION
Layer behavioral signals onto firmographic classification:
- Define Tier 1 (immediate route): [Behavioral signals that trigger instant routing regardless of score — e.g., "Demo request + visited pricing page 3x in 7 days + intent spike from 6sense"]
- Define Tier 2 (route after qualification): [Signals requiring SDR qualification before AE assignment]
- Define Tier 3 (nurture first): [Signals indicating the lead is not yet ready for sales — send to automated nurture sequence, re-evaluate after 14 days]

1.3 NAMED ACCOUNT MATCHING
For enterprise leads, define the named account lookup:
- Data source for named account list: [Salesforce Account object / static CSV / 6sense account data]
- Match criteria: [Company domain match / company name fuzzy match / DUNS number / manual override]
- Match confidence thresholds: [e.g., "100% domain match = auto-assign; 80–99% name match = flag for SDR review; <80% = create as new account"]
- Conflict resolution: [What happens if the domain matches a named account owned by a rep in a different region?]

**MODULE 2: ROUTING DECISION ENGINE**

2.1 MASTER ROUTING FLOWCHART
Design the complete decision tree as a structured IF/THEN/ELSE logic chain:

STEP 1 — Is this lead already in CRM?
  IF yes → Is there an existing open opportunity?
    IF yes → Route to opportunity owner (AE) immediately [Tier 1]
    IF no → Is there an assigned account owner?
      IF yes → Route to account owner
      IF no → Proceed to Step 2
  IF no → Create new lead/contact, run enrichment, proceed to Step 2

STEP 2 — Named account check (enterprise tier)
  IF company domain matches named account list →
    Assign to named account AE
    Notify AE via Slack + CRM task with SLA timer
    IF AE is OOO → Route to enterprise AE backup (defined in step 2.3)
  IF no match → Proceed to Step 3

STEP 3 — Segment classification
  IF enterprise signals (1,000+ employees OR $200M+ revenue OR funding Stage D+) → Enterprise routing path
  IF mid-market signals (100–999 employees OR $10M–$200M revenue) → Mid-market routing path
  IF SMB signals (<100 employees) → SMB routing path
  IF signals missing/incomplete → Route to enrichment queue, re-evaluate in 15 min

STEP 4 — Lead source priority overlay
  [Customize per segment — e.g., demo request always bypasses SDR qualification for mid-market]

STEP 5 — Rep availability check
  IF assigned rep is OOO → Fallback rule (define below)
  IF assigned rep at queue capacity → Overflow rule (define below)
  IF outside business hours → After-hours handling rule (define below)

[Extend this flowchart to cover every edge case specific to the company's structure]

2.2 SEGMENT-SPECIFIC ROUTING RULES

ENTERPRISE PATH:
- Primary routing: Named account AE (immediate, no SDR step for demo requests)
- For non-named accounts: Enterprise AE round-robin (weighted by capacity)
- SDR involvement: Enterprise SDR supports multi-threading, but AE is owner from day 1
- Escalation path: If AE does not respond within SLA → Manager alert → Enterprise team lead reassignment
- Notification: Slack DM to AE + Salesforce task + Chili Piper immediate meeting link generated

MID-MARKET PATH:
- Step 1: Route to inbound SDR (round-robin within geographic territory)
- Step 2: SDR runs qualification call within SLA window
- Step 3: If qualified → SDR books discovery call directly onto AE calendar (Chili Piper)
- Step 4: AE assigned at opportunity creation
- Territory split: [Define geographic or vertical territory rules with specific rep assignments]
- SDR queue cap: [e.g., "Max 40 active leads per SDR at once — overflow to next available SDR"]

SMB PATH:
- Demo requests: Route to SMB AE round-robin (no SDR step — direct to AE)
- Trial signups reaching PQL threshold: Alert SMB AE + trigger in-app onboarding sequence
- Trial signups below PQL threshold: Automated self-serve nurture (no rep assignment until PQL or demo request)
- Content downloads / webinar registrants below MQL score: Automated nurture only — no rep assignment

2.3 ROUND-ROBIN & WEIGHTED DISTRIBUTION
Define the exact distribution algorithm:
- Equal round-robin: [Which segments/scenarios use pure equal rotation]
- Weighted round-robin: [Which reps get higher lead allocation and why — e.g., "Senior AEs get 1.5x leads; ramp reps get 0.5x for first 60 days"]
- Capacity-based distribution: [How rep capacity (open pipeline count, current opportunities) modifies their position in rotation]
- Performance-based adjustment: [Whether meeting-booked conversion rate affects lead allocation — recommend monthly rebalance]
- Rotation reset logic: [When does the round-robin counter reset — daily / weekly / continuous]

**MODULE 3: RESPONSE TIME SLA ARCHITECTURE**

3.1 SLA TABLE BY TIER AND SEGMENT

| Lead Tier | Segment | Lead Source | SLA — First Response | SLA — Second Touch | Escalation Trigger |
|---|---|---|---|---|---|
| Tier 1 — Hot | Enterprise | Demo request | 5 minutes (business hours) | 30 minutes | AE manager notified at 10 min |
| Tier 1 — Hot | Mid-Market | Demo request | 15 minutes (business hours) | 2 hours | SDR manager notified at 30 min |
| Tier 1 — Hot | SMB | Demo request | 30 minutes (business hours) | 4 hours | AE manager notified at 1 hour |
| Tier 2 — Warm | Enterprise | Webinar attendee | 4 hours | 24 hours | Notified at 8 hours |
| Tier 2 — Warm | Mid-Market | High MQL score | 4 hours | 24 hours | Notified at 8 hours |
| Tier 3 — Cool | All | Content download | Automated email only | Automated sequence | No rep SLA — nurture track |

[Customize rows for every lead source and segment combination relevant to the company]

3.2 BUSINESS HOURS DEFINITION
Standard business hours: [e.g., "8 AM – 7 PM rep's local time, Monday–Friday"]
Holiday handling: [Which holidays suspend SLA timers? How are leads held?]
International leads outside coverage hours: [Route to on-call rep? Hold until coverage opens? Auto-acknowledge with human follow-up within X hours?]

3.3 AFTER-HOURS HANDLING
Tier 1 leads received outside business hours:
- Option A (recommended for enterprise): Immediate automated acknowledgment email from assigned AE's email address ("I received your demo request and will call you at [time X] tomorrow") + Chili Piper scheduling link + Slack notification to on-call AE
- Option B (for mid-market): Chatbot qualification (Drift/Intercom) collects context → SDR first thing next business day
- Option C (for SMB): Fully automated email sequence begins immediately; rep picks up next business day

**MODULE 4: OVERFLOW & FALLBACK ARCHITECTURE**

4.1 CAPACITY OVERFLOW RULES
Define overflow logic when the designated rep cannot accept a lead:
- Queue cap per SDR: [e.g., "40 active leads max — when hit, new leads route to next SDR in rotation"]
- Queue cap per AE: [e.g., "30 active opportunities max — when hit, new leads route to backup AE in same segment"]
- Capacity signal source: [How does the routing system detect capacity — CRM open opportunity count, rep-set availability flag, Chili Piper calendar availability]

4.2 OOO & ABSENCE HANDLING
- OOO detection method: [CRM OOO flag set by rep or ops / calendar API integration / manual Salesforce field]
- OOO routing: [Route to pre-designated backup rep; do NOT leave unassigned]
- OOO duration handling: [Leads assigned during OOO — reroute immediately vs. hold in queue with timestamp]
- Parental leave / extended absence: [Permanent reassignment vs. temporary backup rep with re-transfer on return]

4.3 UNRESPONSIVE REP ESCALATION
Define the escalation chain when SLA is missed:
- Step 1: [At SLA + 50% — Slack notification to rep with urgency flag in CRM]
- Step 2: [At SLA + 100% — Slack notification to rep's direct manager + CRM task marked overdue]
- Step 3: [At SLA + 200% — Manager can reassign via CRM override; lead marked "at-risk"]
- Step 4: [At SLA + 300% — Automatic reassignment to backup rep; original rep flagged in performance dashboard]

**MODULE 5: CRM AUTOMATION IMPLEMENTATION**

5.1 SALESFORCE IMPLEMENTATION
If using Salesforce native + LeanData:

LeanData Routing Board Configuration:
- Node 1: Duplicate/existing record check → merge or link to existing contact/account
- Node 2: Enrichment trigger (Clearbit / ZoomInfo enrichment on lead creation)
- Node 3: Named account match (fuzzy match against Account object by domain)
- Node 4: Segment classification (formula field evaluation: Employees + Revenue + Funding Stage)
- Node 5: Lead score threshold check (custom field: Lead Score ≥ 60 → Tier 1 routing)
- Node 6: Round-robin assignment (LeanData Round Robin pool by segment)
- Node 7: Notification triggers (Slack via webhook, email to rep, Chili Piper meeting link generation)
- Node 8: SLA timer start (custom DateTime field "SLA Due Date" stamped at assignment)
- Node 9: SLA monitoring workflow (process builder or flow checks SLA Due Date every 15 minutes; escalates on breach)

Required custom fields on Lead/Contact object:
- Routing_Segment__c (Picklist: SMB / Mid-Market / Enterprise / Unclassified)
- Routing_Tier__c (Picklist: Tier 1 / Tier 2 / Tier 3)
- Named_Account_Match__c (Checkbox)
- SLA_Due_Date__c (DateTime)
- SLA_Status__c (Picklist: On Track / Breached / Escalated)
- Assignment_Timestamp__c (DateTime)
- First_Response_Timestamp__c (DateTime)
- Routing_Source__c (Text — records which routing node assigned the lead)

5.2 HUBSPOT IMPLEMENTATION
If using HubSpot native workflows + Chili Piper:

Workflow 1 — Enrichment & Classification (triggers on: form submission / contact creation):
1. Trigger: Contact is created OR form is submitted
2. Action: Enrich with Clearbit (HubSpot integration) — wait up to 30 seconds
3. Action: Set property "Routing Segment" via if/then branch on Number of Employees
4. Action: Set property "Routing Tier" via if/then branch on Lead Source + Form Type
5. Action: Set property "Named Account Flag" via list enrollment (compare company domain against static list of named account domains)

Workflow 2 — Assignment & Notification (triggers on: Routing Segment is known):
1. Trigger: Contact property "Routing Segment" is set
2. Branch 1: If Enterprise + Named Account Flag = True → Assign owner to named account AE (HubSpot contact owner)
3. Branch 2: If Enterprise + Named Account Flag = False → Rotate through Enterprise AE team using HubSpot round-robin (Rotate Contact Owner action)
4. Branch 3: If Mid-Market → Rotate through inbound SDR team → Send internal email with Chili Piper link to book onto AE calendar
5. Branch 4: If SMB + Tier 1 → Rotate through SMB AE team
6. Branch 5: If SMB + Tier 2/3 → Enroll in automated nurture sequence (no rep assignment)
7. Action (all routed): Send rep notification email with contact context + Chili Piper booking link
8. Action: Set "SLA Due Date" = Now + [SLA hours based on tier]
9. Action: Create task on contact record "First response within [SLA]"

Workflow 3 — SLA Monitoring (triggers on: daily at 8 AM and 2 PM):
1. Filter: Contacts where SLA Due Date is past AND First Response Timestamp is empty AND Owner is set
2. Action: Send escalation email to contact owner's manager
3. Action: Update SLA Status to "Breached"
4. Action: Create escalation task on contact record

**MODULE 6: MEETING BOOKING & HANDOFF ARCHITECTURE**

6.1 INBOUND MEETING BOOKING FLOW
Demo request routing (fastest path to booked meeting):
- Chili Piper concierge on demo request confirmation page: Presents calendar of the assigned rep (populated within seconds of routing decision) — prospect books directly
- If Chili Piper not in stack: Rep sends Calendly/HubSpot Meetings link within SLA window via templated email from sales engagement tool
- Meeting confirmation: Automated confirmation with agenda prep email from sales engagement tool

6.2 SDR-TO-AE HANDOFF
Define the handoff protocol to eliminate deals dying between SDR and AE:
- Handoff trigger: SDR marks lead as "Qualified" in CRM and converts to opportunity
- Handoff actions: (1) AE assigned as opportunity owner; (2) SDR books intro call directly onto AE calendar; (3) SDR completes handoff notes field with: company context, pain identified, stakeholders met, buying timeline, budget indicator; (4) AE receives handoff Slack notification with opportunity link
- Handoff SLA: [e.g., "SDR must complete handoff notes within 24 hours of qualification; AE must review and accept/reject within 24 hours"]
- Recycle process: If AE rejects opportunity, it returns to SDR queue with rejection reason documented

**MODULE 7: ROUTING PERFORMANCE MEASUREMENT**

7.1 PRIMARY KPIs

| Metric | Definition | Target Benchmark | Measurement Source |
|---|---|---|---|
| Speed-to-Lead (Tier 1) | Time from lead creation to first rep response | <5 min enterprise; <15 min mid-market | CRM timestamp comparison |
| Lead Assignment Accuracy | % of leads correctly classified and routed to right segment/territory on first assignment | >95% | Monthly routing audit |
| SLA Attainment Rate | % of Tier 1 leads receiving first response within SLA | >90% | CRM SLA Status field |
| Round-Robin Equity Score | Standard deviation of leads distributed across reps in same pool | <10% variance | CRM lead owner distribution report |
| SDR Accept Rate | % of routed leads SDR accepts vs. bounces back to ops | >85% | CRM lead status tracking |
| Routing Fallback Rate | % of leads that triggered overflow or OOO fallback rules | <15% (high fallback = capacity problem) | Routing_Source field analysis |
| Meeting Booked Rate (Tier 1) | % of Tier 1 inbound demo requests that result in booked meeting | >55% | CRM opportunity creation |
| Rep Queue Depth | Average number of active leads per rep vs. capacity cap | Within 20% of cap | CRM lead count per owner |

7.2 MONTHLY ROUTING REVIEW PROCESS
1. Pull routing performance dashboard (CRM + routing tool reporting)
2. Identify top 3 routing failure patterns (wrong segment classification, SLA breaches, fallback overuse)
3. Audit a sample of misrouted leads (10 per segment) — identify enrichment data quality issues
4. Adjust round-robin weights based on rep ramp status and current quota attainment
5. Refresh named account list if any accounts have been won, lost, or reassigned
6. Update OOO fallback mappings for upcoming planned absences

## Example Input/Output

**Input Example:**

Company: Vanta AI, a compliance automation platform for Series A–C SaaS companies
ARR: $22M
Sales team: 5 SDRs (inbound-focused), 9 AEs (3 SMB, 4 mid-market, 2 enterprise), 1 RevOps manager
Segments: SMB <$8K ACV (1–99 employees), Mid-Market $12K–$40K ACV (100–999 employees), Enterprise $60K+ ACV (1,000+ employees, top 200 named accounts)
Lead sources: Demo requests (~80/month), free trial signups (~400/month), contact form (~40/month), webinar registrants (~150/month)
Stack: Salesforce + Outreach + Chili Piper + Clearbit Enrichment + 6sense intent data
Current problem: 14-hour average speed-to-lead on demo requests; enterprise leads being routed to mid-market SDRs; 3 enterprise leads per month going unassigned due to OOO gaps

**Output Example (excerpt):**

ROUTING CLASSIFICATION FOR VANTA AI:

ENTERPRISE CLASSIFICATION CRITERIA (auto-classified at lead creation):
- Employee count ≥ 1,000 (from Clearbit) OR
- Company on Named Account List (domain match against 200-account Salesforce list) OR
- 6sense intent tier = "In Market" AND employee count ≥ 500 (override to enterprise)
→ Routes to: Named account AE if matched; Enterprise AE round-robin (2 reps, weighted 50/50) if no match
→ SLA: 5 minutes first response, Chili Piper concierge active on demo request confirmation page
→ OOO fallback: Enterprise AE A ↔ Enterprise AE B mutual backup; if both OOO → VP Sales receives Slack alert within 10 minutes

DEMO REQUEST ROUTING (Tier 1 — all segments):
1. Lead created in Salesforce upon form submission
2. Clearbit enrichment fires immediately (webhook, synchronous)
3. LeanData routing board evaluates: named account match → segment → round-robin pool
4. Rep assigned within 60 seconds of form submission
5. Chili Piper concierge appears on thank-you page showing assigned rep's calendar (next 48 hours)
6. Rep receives Slack notification via LeanData + Salesforce task with 5-minute SLA timer
7. SLA monitoring: Outreach auto-creates a task; if rep does not log activity within 5 minutes → Slack alert to SDR/Sales manager

SPEED-TO-LEAD RESULTS (projected):
- Tier 1 demo requests: 14 hours → <8 minutes (enterprise), <15 minutes (mid-market)
- Meeting-booked rate from demo requests: 22% → 48% (industry data: speed-to-lead <5 min = 21x higher conversion vs. >30 min)

## Success Metrics

- **Speed-to-Lead (Tier 1):** Average first rep response under 10 minutes for demo requests within 30 days of implementation
- **Lead Assignment Accuracy:** 95%+ of leads correctly classified on first routing pass (audited monthly)
- **SLA Attainment Rate:** 90%+ of Tier 1 leads receive response within defined SLA
- **SDR Accept Rate:** 85%+ of routed leads accepted without being bounced back to ops as misrouted
- **Meeting Booked Rate:** 15%+ improvement in demo-request-to-booked-meeting conversion within 60 days
- **Zero Unassigned Leads:** Routing system eliminates leads falling through the cracks — 100% of inbound Tier 1 leads assigned within 2 minutes of submission

## Related Prompts

- [Inbound Lead Scoring & Revenue-Qualified Pipeline Architecture](./AI-Powered-B2B-SaaS-Inbound-Lead-Scoring-&-Revenue-Qualified-Pipeline-Architecture-Intelligence-Engine.md)
- [Marketing Automation Program Architecture & Lifecycle Revenue Governance](./AI-Powered-B2B-SaaS-Marketing-Automation-Program-Architecture-&-Lifecycle-Revenue-Governance-Intelligence-Engine.md)
- [ABM Target Account List Building & ICP Scoring](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/AI-Powered-ABM-Target-Account-List-Building-&-ICP-Scoring-Intelligence-Engine.md)
- [CFO Economic Buyer ABM Campaign Architecture](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/AI-Powered-B2B-SaaS-CFO-Economic-Buyer-ABM-Campaign-Architecture-&-Finance-Led-Deal-Acceleration-Revenue-Intelligence-Engine.md)

## Integration Tips

- **Salesforce + LeanData:** LeanData is the gold standard for complex B2B routing. Use LeanData's routing board for visual drag-and-drop logic; sync with Outreach for SLA task creation. LeanData's "Boomerang" feature automatically re-routes recycled leads without ops intervention.
- **HubSpot native:** Use HubSpot's "Rotate Contact Owner" action in workflows for round-robin. Combine with Chili Piper for instant meeting booking on the confirmation page. Use HubSpot's "Task" creation action to trigger SLA monitoring.
- **Chili Piper Concierge:** Implement on all demo request thank-you pages. Configure "round robin with weights" to match your routing model — Chili Piper respects availability from Google/Outlook calendar, automatically skipping OOO reps.
- **Slack notifications:** Use Slack webhooks (via Zapier, Make, or native CRM integration) to push routing notifications into a dedicated #hot-leads channel visible to the full sales team — creates team accountability and social pressure to respond within SLA.
- **Clearbit/ZoomInfo enrichment:** Run enrichment synchronously at lead creation (not async/batch) so routing fires with complete firmographic data. Accept lower match rates in exchange for routing accuracy — an unenriched enterprise lead routed to an SMB rep is an expensive mistake.
- **6sense + routing:** Use 6sense "In Market" account stage as a segment override signal — a 250-employee company showing enterprise-level intent should route to mid-market AE, not SMB. Map 6sense account stage to a custom CRM field that the routing logic evaluates.
- **Google Sheets audit dashboard:** Export routing_source field weekly into Google Sheets; use pivot tables to spot routing failure patterns (which nodes triggered most fallbacks, which reps have the longest queue depth, which lead sources produce the most misrouted leads).

## Troubleshooting

**Problem: Enrichment data is missing or wrong, causing leads to be misclassified.**
Solution: Add a "routing review" queue in CRM — leads where enrichment confidence score is below threshold (or enrichment fails entirely) land here for manual 2-minute classification by RevOps before routing fires. Accept that 5–10% of leads will require human review; the goal is to automate the other 90–95%.

**Problem: Round-robin becomes uneven over time because some reps reject leads or convert leads faster, creating gaps in the rotation.**
Solution: Track "leads accepted" not "leads assigned" as the round-robin input metric. Use LeanData's capacity-based routing or configure HubSpot to skip reps who have already received a lead from the same company domain in the last 30 days. Run a monthly equalization audit to reset round-robin counters.

**Problem: SLA timers fire incorrectly on weekends and holidays, flooding reps with escalation notifications Sunday morning.**
Solution: Configure SLA calculations to use "business hours" only — most routing tools (LeanData, Chili Piper) support business hours SLA calculation natively. In HubSpot, use scheduled workflows that only trigger during business hours. Store a "Business Hours SLA Due Date" field alongside a "Calendar SLA Due Date" field so reporting reflects both.

## Version History
- v1.0: Initial creation (auto-generated)
