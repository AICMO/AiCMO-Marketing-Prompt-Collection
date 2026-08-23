# AI-Powered B2B SaaS Sales-Marketing Revenue Alignment Architecture & Closed-Loop Lead Intelligence Engine - Build an AI-Agent-Managed Smarketing System That Eliminates Lead Quality Disputes and Turns Every Rejected Lead Into Scoring Model Fuel

**Difficulty:** Advanced | **Time:** 45-60 min | **Tags:** sales-marketing alignment, smarketing, lead quality, closed-loop reporting, MQL definition, SLA, revenue operations, B2B SaaS, HubSpot, Salesforce, Marketo, pipeline intelligence, lead routing, feedback loops, revenue alignment

## Overview
Designs and deploys a complete AI-powered sales-marketing alignment architecture — from shared lead quality definitions and SLA frameworks through automated feedback loops, lead recycling cadences, and closed-loop revenue attribution. Use this when sales says marketing leads are garbage, when MQL-to-opportunity conversion rates are below 15%, when lead rejection reasons are captured inconsistently (or not at all), or when marketing has no visibility into why pipeline stalls after handoff. This prompt produces a self-improving, AI-agent-managed alignment system where every sales rejection makes the next batch of MQLs more accurate.

## Quick Copy-Paste Version

You are a B2B SaaS revenue operations architect specializing in sales-marketing alignment. Build a complete, AI-agent-executable closed-loop lead intelligence system that eliminates MQL quality disputes and makes both teams accountable to shared revenue outcomes.

COMPANY CONTEXT:
- My Company: [e.g., "Gong.io — revenue intelligence platform for B2B sales teams at companies with 50-1,000 reps"]
- ICP Definition: [e.g., "VP Sales, CRO, and Revenue Ops Directors at B2B SaaS companies with 30-500 AEs, $10M-$200M ARR"]
- Average ACV: [e.g., "$42,000"]
- Sales Motion: [e.g., "Sales-assisted: SDR qualifies, AE runs demo → POC → negotiation; 60-day avg sales cycle"]
- Current MQL Volume: [e.g., "~300 MQLs/month"]
- Current MQL-to-Opportunity Rate: [e.g., "9% — sales frequently complains about lead quality"]
- Lead Rejection Rate: [e.g., "~45% of MQLs are rejected or recycled within 5 days"]
- CRM: [HubSpot / Salesforce]
- Marketing Automation: [HubSpot / Marketo / Pardot]
- Sales Engagement Platform: [Salesloft / Outreach / Apollo / None]

OUTPUT REQUIRED:
1. SHARED REVENUE DEFINITION FRAMEWORK: The exact MQL/SQL/Opportunity definitions both teams sign off on — with measurable criteria, not vague descriptions, plus the Revenue Qualified Lead (RQL) threshold that predicts a 25%+ close rate
2. SLA ARCHITECTURE: Contact SLAs by lead tier (MQL Tier 1: 4-hour response; Tier 2: 24 hours; Tier 3: 48 hours), plus the automated escalation triggers when SLAs breach
3. REJECTION TAXONOMY: A standardized lead rejection reason code system (8-12 codes covering fit, timing, data quality, and duplicate issues) with the CRM field mapping to capture reasons at rejection, not after the fact
4. CLOSED-LOOP FEEDBACK ENGINE: The AI agent workflow that processes every rejected lead — extracts the rejection reason, maps it to the responsible scoring signal, adjusts signal weights, and feeds learning back to the scoring model within 24 hours
5. LEAD RECYCLING ARCHITECTURE: The rules for recycling vs. disqualifying leads — time-based re-entry into nurture, trigger-based re-scoring, and the lifecycle statuses that prevent recycled leads from being re-contacted by sales before marketing re-qualifies them
6. SMARKETING CADENCE: The weekly/monthly meeting architecture with AI-prepared agenda, lead quality scorecards, and the specific metrics both teams review together to maintain alignment without blame

Designed to run autonomously via AI agents: rejection capture, scoring model updates, recycling enrollment, and SLA monitoring should all execute without human intervention. Reserve human judgment for monthly model reviews and when MQL-to-pipeline conversion drops more than 3 points.

## Advanced Customizable Version

ROLE: You are a senior revenue operations architect and sales-marketing alignment specialist with 18+ years building closed-loop lead intelligence systems for B2B SaaS companies from Series B through IPO. You have solved the sales-marketing alignment problem at 75+ companies across cybersecurity, fintech, HR tech, DevTools, and marketing technology — spanning MQL volumes from 50 to 30,000 per month and ACVs from $5,000 to $1,200,000.

You understand precisely why most alignment efforts fail: why "defining MQLs together" in a single workshop doesn't stick unless the definition is encoded in the CRM as field validation rules that make it physically impossible to mark a lead MQL without meeting every criterion; why lead rejection rates above 40% almost always trace to three root causes — fit score thresholds set too low (optimizing for volume over quality), behavioral engagement scored without ICP fit weighting (a mid-market buyer and an unqualified researcher look identical if you only track page views), and timing misalignment (marketing sends MQLs immediately at threshold breach, but 60% of them are in research mode rather than active buying mode); why standardized rejection taxonomies must be enforced at the point of rejection — not in a post-rejection survey — because sales reps will mark "not interested" on 80% of rejections if a taxonomy isn't the only option presented to them in the CRM; why lead recycling without a time-based re-qualification gate creates circular pipeline that inflates MQL volume metrics while destroying conversion rates; and why the most durable alignment frameworks treat sales feedback as a continuous scoring model input (ML feature) rather than a periodic QA process.

You design alignment systems as fully autonomous AI agent workflows: every lead rejection triggers an automated extraction of the rejection reason, maps it to the specific scoring signals responsible for the bad MQL, queues a signal weight recalibration for the next model update cycle, and routes the rejected lead to the correct recycling path — all without human intervention between the rejection event and the corrective action. Human review is reserved for monthly model audits, quarterly SLA renegotiations, and anomaly detection when rejection rates spike more than 10 points in a single week.

OBJECTIVE: Design a production-ready, AI-agent-managed sales-marketing revenue alignment architecture that:
- Creates a shared Revenue Qualified Lead (RQL) definition that sales and marketing both contribute to, both can measure autonomously in the CRM, and that predicts ≥25% close rate when used as the MQL threshold
- Reduces MQL rejection rates from current baseline to below 20% within 90 days by turning every rejection into a scoring model improvement signal
- Establishes SLA frameworks that create mutual accountability — marketing is accountable for MQL quality scores, sales is accountable for SLA contact rates — with AI-generated weekly scorecards that surface violations without manual reporting
- Automates the entire lead recycling lifecycle — from rejection through re-qualification through re-routing — so no lead permanently dies in CRM limbo and no recycled lead reaches sales before re-earning MQL status
- Produces a self-improving system: the AI agent processes 100% of rejection data, updates signal weights monthly, and reduces the variance between marketing's prediction of which leads will convert and actual sales conversion rates

---

COMPANY & PROGRAM INPUTS:

**Company Profile:**
- Company Name & Description: [e.g., "Ramp — spend management and corporate card platform for finance teams at companies with 50-5,000 employees"]
- ICP Definition (be specific): [e.g., "VP Finance, CFO, and Finance Directors at B2B companies with 50-2,000 employees, primarily Series B+ tech, professional services, and growth-stage companies — characterized by multi-card corporate spend, rapid headcount growth, and manual reconciliation pain"]
- Average ACV: [e.g., "$28,000 annual contract; $2,333/month"]
- Sales Motion: [e.g., "Hybrid PLG + sales-assist: freemium trial → product activation → SDR outreach to high-PQL accounts → AE demo → 21-day avg close for SMB, 45 days for mid-market"]
- Current Team Size: [e.g., "12-person marketing team, 40 SDRs, 25 AEs across SMB and mid-market"]
- CRM: [Salesforce / HubSpot — specify version and key customizations]
- Marketing Automation: [Marketo / HubSpot / Pardot / Customer.io]
- Sales Engagement: [Salesloft / Outreach / Apollo]
- BI / Analytics: [Tableau / Looker / Metabase / Hex]

**Current State Assessment:**
- Monthly MQL Volume: [e.g., "480/month across inbound, content, events, and outbound"]
- MQL-to-Opportunity Rate: [e.g., "11% — target is 20%"]
- MQL-to-Closed-Won Rate: [e.g., "3.2% — target is 6%"]
- Current Lead Rejection Rate: [e.g., "42% of MQLs rejected or untouched within 7 days"]
- Top 3 Rejection Reasons (what sales says): [e.g., "Wrong company size (too small), prospect already contacted (duplicate), prospect is a student/agency/consultant not a buyer"]
- SLA Compliance Rate: [e.g., "SDRs contact 68% of MQLs within 24 hours; target is 90%"]
- Lead Recycling Process: [e.g., "No formal process — rejected leads sit in CRM with 'Disqualified' status permanently"]
- Scoring Model Last Updated: [e.g., "18 months ago, manually in HubSpot — no feedback loop from sales"]

**Alignment Dynamics:**
- Relationship Health (1-10): [e.g., "5 — recurring tension in pipeline reviews, VP Sales says MQL definition is meaningless"]
- Primary Friction Points: [e.g., "Sales doesn't give specific rejection feedback, marketing doesn't know why leads fail, both teams pull different pipeline numbers from the same CRM"]
- Executive Alignment: [e.g., "CRO and CMO both report to CEO who has mandated shared revenue accountability — political will exists but process doesn't"]

---

OUTPUT REQUIRED — COMPLETE ARCHITECTURE:

**MODULE 1: SHARED REVENUE DEFINITION FRAMEWORK**

Build the Revenue Qualified Lead (RQL) definition that both teams co-own:

A. RQL CRITERIA MATRIX
Design a 4-dimension qualification matrix where leads must meet minimum thresholds across all four:
- Firmographic Fit Score: [ICP company size, industry, tech stack, funding stage — minimum threshold to qualify]
- Contact Fit Score: [Title tier, seniority, buying committee role, department — mapped to MEDDPICC Economic Buyer and Champion criteria]
- Behavioral Engagement Score: [Weighted by intent signal type — product trial activity weighted 5x content downloads, demo requests weighted 10x email opens — with minimum engagement depth threshold]
- Timing Signal Score: [Recent engagement recency window, intent data surge above baseline, trigger event detection (job change, funding round, competitor contract expiry)]

B. LIFECYCLE STATUS TAXONOMY
Define every lead/contact status that can exist in the CRM with precise entry criteria, exit criteria, and maximum dwell time:
- Subscriber → MQL → RQL → SAL (Sales Accepted Lead) → SQL → Opportunity → [Won/Lost]
- Recycled → Re-Nurture → Re-Qualified → RQL (recycling re-entry path)
- Disqualified → Archived (permanent disqualification criteria that cannot be recycled)

C. CO-OWNERSHIP ACCOUNTABILITY
Define what marketing owns vs. what sales owns in the revenue funnel:
- Marketing SLA: [Deliver X RQLs/month at Y% ICP fit score, with Z% meeting firmographic minimum — measured weekly]
- Sales SLA: [Contact X% of Tier 1 RQLs within 4 hours, Tier 2 within 24 hours, provide rejection reason within 48 hours of rejection — measured weekly]
- Shared Metric: [RQL-to-Opportunity conversion rate — neither team can hit their individual target without the other performing]

---

**MODULE 2: AI-POWERED REJECTION FEEDBACK ENGINE**

A. REJECTION TAXONOMY DESIGN
Build a mandatory 10-category rejection taxonomy enforced at the CRM lead rejection action — this taxonomy replaces the free-text "notes" field with a required dropdown that must be selected before the status can be changed to Disqualified:

Fit Rejection Codes (wrong lead, right timing):
- F1: Company size outside ICP range [specify: too small / too large]
- F2: Industry outside ICP target list
- F3: Contact seniority below buyer threshold (end user, not economic buyer)
- F4: Technology stack incompatibility (requires integration we don't have)
- F5: Ineligible company type (agency, consultant, student, competitor, investor)

Timing Rejection Codes (right lead, wrong timing):
- T1: Active competitor contract in place (re-evaluate at [X] months)
- T2: Budget not allocated until next fiscal year
- T3: Actively evaluating — in an active deal already
- T4: Recent purchase within 12 months — not in buying mode

Data Quality Rejection Codes:
- D1: Duplicate contact (active lead or customer already in system)
- D2: Bounced email / uncontactable (bad data)
- D3: Opted out of communication

B. AI REJECTION PROCESSING WORKFLOW
Design the autonomous agent workflow triggered within 1 hour of any rejection:

Step 1 — Rejection Signal Extraction:
[AI agent reads rejection code + lead score at time of rejection + which scoring signals contributed most to the score]

Step 2 — Root Cause Mapping:
[Map each rejection code to the scoring signal responsible — F1 rejects indicate firmographic fit threshold is too low, T2 rejects indicate behavioral engagement model is picking up research-mode buyers too early, D1 rejects indicate deduplication is firing too late in the lead lifecycle]

Step 3 — Signal Weight Recalibration Queue:
[Flag the responsible signal for weight reduction in the next model update cycle — don't adjust in real-time (prevents overcorrection) but accumulate a 30-day window of rejection evidence before adjusting]

Step 4 — Recycling Path Assignment:
[Based on rejection code, automatically route to the correct recycling path:
- F1-F5: Disqualify permanently (wrong fit — no recycling)
- T1: Re-enter nurture at Month 9 (contract re-evaluation window)
- T2: Re-enter nurture at fiscal year start minus 60 days
- T3: Flag for Sales competitive intelligence, re-score if they don't close in 90 days
- T4: Re-enter nurture at Month 10 post-purchase (renewal consideration window)
- D1: Merge records, transfer engagement history to primary contact
- D2: Trigger data enrichment (Clearbit/ZoomInfo API) before re-qualifying]

---

**MODULE 3: LEAD RECYCLING ARCHITECTURE**

A. RECYCLING LIFECYCLE RULES
Design the complete recycling workflow with explicit guardrails that prevent recycled leads from becoming zombie pipeline:

Re-Qualification Gates:
- Recycled leads must accumulate [X] behavioral engagement score points BEFORE re-entering the RQL scoring model
- Recycled leads are invisible to sales sequences until they cross the re-qualification threshold — automation must enforce this via CRM field-gating on sequence enrollment
- Recycled leads that re-qualify must receive a "Recycled: [Date]" tag in CRM to give sales context on why this lead is re-appearing

Time-Based vs. Behavior-Based Recycling:
- Timing rejections (T1-T4): Time-based recycling cadences tied to the specific timing window
- Data rejections (D2-D3): Behavior-based — recycle only if the contact re-engages (email re-subscribe, new visit, product sign-up)
- Never recycle: F1-F5 (fit rejections) — permanently disqualify with archived status

Recycling Nurture Track Design:
For each T-code recycling path, design:
- Entry trigger: [What action re-enters the lead into the nurture track]
- Nurture duration: [How many days/touches before re-scoring]
- Content personalization: [What content maps to their rejection reason — T1 gets competitive comparison content, T2 gets budget justification content]
- Re-scoring event: [What behavioral trigger moves them from nurture back to scoring model evaluation]

B. PIPELINE HYGIENE AUTOMATION
Design the weekly AI agent audit that prevents recycled leads from polluting pipeline metrics:
- Scan for leads with "Disqualified" status older than 90 days with no recycling path assigned — route to archive
- Scan for recycled leads that have exceeded their nurture duration without re-qualifying — flag for marketing review
- Scan for active opportunities that share contact records with disqualified leads — flag potential data quality issues for RevOps

---

**MODULE 4: SMARKETING OPERATING CADENCE**

A. WEEKLY SMARKETING SYNC (30-minute AI-prepared agenda)

AI Agent Pre-Populates Before Each Meeting:
- MQL Volume vs. Target: [Actual / Target / Variance]
- RQL-to-Opportunity Rate: [This week / 4-week rolling average / target]
- SLA Compliance: [Marketing: Did we hit RQL volume and quality targets? Sales: Did we contact X% of Tier 1 RQLs within 4 hours?]
- Top 3 Rejection Reasons This Week: [With volume and trend vs. last week]
- Recycling Queue Status: [How many leads in each recycling track, any backlogs?]
- Scoring Model Recalibration Flags: [Any signals that have accumulated enough rejection evidence to trigger a weight change?]

Meeting Rules:
- No blame. Every data point points to a system failure, not a person failure
- Only discuss variances >10% from target — the AI handles everything within tolerance
- Every action item must be: owned by one person, have a specific deliverable, and have a due date before next meeting

B. MONTHLY ALIGNMENT REVIEW (60-minute with leadership)

AI Agent Pre-Populates:
- Month-over-month RQL-to-Opportunity trend
- MQL rejection rate trend (target: declining 3% month-over-month for first 6 months)
- Scoring model accuracy report: For MQLs passed 60-90 days ago, what percentage converted vs. what the model predicted?
- Lead recycling ROI: How many opportunities sourced from recycled leads? What's the revenue contribution?
- SLA breach log: Which breaches occurred and what was the revenue impact (estimated)?

Decision Points for Leadership Review:
- Should we adjust MQL volume targets based on RQL-to-opportunity trend?
- Do any rejection rate patterns indicate ICP definition needs to be updated?
- Are there new buyer signals (job title changes, technology additions) that should be added to the scoring model?

---

**MODULE 5: CLOSED-LOOP REVENUE ATTRIBUTION**

Design the attribution model that gives marketing visibility into what happens after the handoff:

A. FULL-FUNNEL VISIBILITY DASHBOARD (Built in CRM + BI Tool)
- MQL Cohort Tracking: For every MQL batch (weekly), track through to closed-won — not just opportunity creation
- First-Touch vs. Last-Touch vs. Linear Attribution for every closed-won deal
- Marketing-Influenced Pipeline: Deals where marketing had ANY touchpoint after SDR qualification
- RQL Prediction Accuracy: How often did an MQL with score X actually convert at the predicted rate?

B. AI-GENERATED ATTRIBUTION NARRATIVE (Monthly Report)
Auto-generate for CMO/CRO:
- Revenue from marketing-sourced pipeline: $[X]M
- Revenue from marketing-influenced pipeline: $[Y]M
- RQL model accuracy score: [X]% — meaning when the model predicted a 30% close rate, the actual rate was [Y]%
- Signal quality improvement: Which scoring signals improved in predictive accuracy this month vs. last?

---

**MODULE 6: IMPLEMENTATION ROADMAP**

Design a 90-day implementation plan:

Week 1-2: Foundation
- CRM field mapping for rejection taxonomy
- Lifecycle status redesign and CRM implementation
- SLA definition workshop with sales and marketing leadership

Week 3-4: Automation Build
- Rejection processing workflow (AI agent)
- SLA monitoring alerts
- Recycling cadence enrollment automation

Week 5-8: Calibration
- Run new taxonomy for 30 days, collect baseline rejection data
- First scoring model recalibration based on rejection feedback
- Week 6 checkpoint: Are rejection rates declining? If not, adjust thresholds

Week 9-12: Optimization
- Monthly alignment review implementation
- Pipeline hygiene automation activation
- Revenue attribution dashboard launch
- Document playbook for ongoing model maintenance

---

SUCCESS CRITERIA:
- MQL rejection rate: Below 20% (from current baseline) within 90 days
- SLA compliance: 90%+ of Tier 1 MQLs contacted within 4 hours within 60 days
- RQL-to-opportunity rate: 25%+ (from current baseline) within 120 days
- Model accuracy: AI-predicted conversion rates within 5% of actual rates within 6 months
- Smarketing relationship health (self-reported 1-10): 8+ within 6 months

## Example Input/Output

**Input Example:**

Company: DataStax — developer data platform for building real-time AI applications, targeting VP Engineering, CTO, and Principal Engineers at companies building AI-native products (primarily fintech, e-commerce, and media, $10M+ ARR)
ACV: $85,000 | Sales Motion: Sales-assisted with PLG trial | CRM: Salesforce | MAP: Marketo
Current State: 220 MQLs/month, 8% MQL-to-Opportunity, 52% rejection rate, zero formal recycling process, last scoring model update was 14 months ago

**Output Example (excerpt):**

**RQL CRITERIA MATRIX FOR DATASTAX:**

**Dimension 1 — Firmographic Fit Score (max 40 points)**
| Signal | Points | Data Source |
|--------|--------|-------------|
| Company is building AI/ML product (confirmed) | +20 | Clearbit + manual enrichment |
| Employee count 50-5,000 | +10 | ZoomInfo |
| Industry: Fintech, E-commerce, or Media | +7 | Clearbit |
| Series B+ funding or $10M+ ARR | +3 | Crunchbase API |
| *Minimum threshold to proceed: 25/40* | | |

**Dimension 2 — Contact Fit Score (max 30 points)**
| Signal | Points | Data Source |
|--------|--------|-------------|
| Title: VP Eng, CTO, Principal/Staff Engineer | +20 | LinkedIn enrichment |
| Reports to: CTO or Engineering leadership | +7 | ZoomInfo org chart |
| Has "AI/ML" in current or previous roles | +3 | LinkedIn |
| *Minimum threshold to proceed: 20/30* | | |

**Dimension 3 — Behavioral Engagement Score (max 40 points, recency-weighted)**
| Signal | Points | Weight Logic |
|--------|--------|-------------|
| Active trial user (logged in 3+ days in 14-day window) | +25 | Recency half-life: 14 days |
| Demo requested or attended | +15 | 30-day recency window |
| Docs or API reference visited 5+ pages | +10 | 7-day recency |
| Pricing page visited | +8 | 7-day recency |
| Case study or solution guide downloaded | +5 | 14-day recency |
| Newsletter engaged (3+ opens/clicks in 30 days) | +3 | 30-day window |
| *Minimum threshold to proceed: 25/40* | | |

**Dimension 4 — Timing Signal Score (max 30 points)**
| Signal | Points | Source |
|--------|--------|--------|
| Bombora intent surge: "vector database" or "AI infrastructure" | +20 | Bombora API |
| LinkedIn job posting for ML Engineer or AI roles | +7 | LinkedIn API |
| Recent funding round (60 days) | +3 | Crunchbase webhook |
| *Minimum threshold to proceed: 10/30* | | |

**RQL THRESHOLD: 85+ total points across all 4 dimensions, with no single dimension below minimum.** Historical analysis shows leads meeting this threshold convert to opportunity at 27% — above the 25% target.

---

**REJECTION TAXONOMY ENFORCEMENT (Salesforce Implementation):**

// Salesforce Flow: Force Rejection Reason Before Status Change
trigger LeadRejectionTaxonomy on Lead (before update) {
  for (Lead lead : Trigger.new) {
    Lead oldLead = Trigger.oldMap.get(lead.Id);
    if (lead.Status == 'Disqualified' && oldLead.Status != 'Disqualified') {
      if (lead.Rejection_Reason_Code__c == null || lead.Rejection_Reason_Code__c == '') {
        lead.addError('Rejection reason code is required. Select from: F1-F5 (fit) or T1-T4 (timing) or D1-D3 (data quality)');
      }
    }
  }
}

**RECYCLING PATHS FOR DATASTAX:**

T1 (Active competitor contract): 
- Re-enter: Marketo Smart Campaign trigger at Month 9 post-rejection
- Nurture track: "Cassandra Migration" 6-email sequence (competitor to DataStax migration guide)
- Re-qualify trigger: Trial signup OR 5+ docs page visits in 7-day window
- Sales visibility: Hidden until re-qualification

T2 (Budget not allocated):
- Re-enter: 45 days before prospect company's fiscal year start (estimated via LinkedIn/Crunchbase)
- Nurture track: "Q1 Budget Justification" sequence with ROI calculator CTA
- Re-qualify trigger: ROI calculator usage OR pricing page revisit + Bombora intent surge

---

**WEEK 1 SMARKETING SYNC AGENDA (AI-Generated):**

Meeting Date: [Auto-populated]
Prep Time: 0 minutes for either team — AI prepared everything

📊 DATASTAX SMARKETING FLASH REPORT — Week of [Date]

✅ GREEN (On Track):
• MQL Volume: 58 / 55 target (+5.5%)
• Tier 1 SLA Compliance: 92% contacted within 4 hours

⚠️ YELLOW (Watch):
• RQL-to-Opportunity: 12% vs. 16% target (-4 pts)
• Rejection Rate: 48% vs. 42% target (+6 pts)

🔴 RED (Action Required):
• F3 rejections (seniority too low): +18% vs. last week — marketing's contact title scoring may be weighting junior "Engineer" titles at too high a score

DISCUSSION ITEM (5 minutes max):
Marketing to investigate: Are junior engineer contacts being scored as Principal/Staff Engineers due to LinkedIn title ambiguity? Propose: Add seniority filter to contact fit score that requires "Principal," "Staff," "Lead," or "VP/Director" in exact title match. 

Owner: [Marketing Ops] | Due: [Next Wednesday]

Next meeting: [Auto-scheduled]

## Success Metrics

**Alignment Health Metrics (measure weekly):**
- MQL rejection rate: Target <20% within 90 days, <15% at 6 months
- SLA compliance rate: Tier 1 contact within 4 hours: >90%
- Rejection reason code completion rate: 100% (enforced by CRM — if below 100%, a workflow is broken)
- Recycling track enrollment rate: 100% of T-code rejections enter correct recycling path within 24 hours

**Revenue Impact Metrics (measure monthly):**
- MQL-to-Opportunity rate: Target 25%+ (leading indicator of quality improvement)
- RQL prediction accuracy: AI-predicted conversion rate within ±5% of actual rate
- Recycled lead pipeline contribution: Opportunities sourced from recycled leads as % of total pipeline
- Time to re-qualification: Average days for recycled leads to re-qualify (target: declining over time)

**Model Quality Metrics (measure quarterly):**
- Scoring model recalibration cycles completed: At least monthly
- Signal weight drift: Measure variance in signal weights quarter-over-quarter — high drift means model is still learning; low drift means model has stabilized
- Smarketing NPS (internal): Monthly self-reported relationship health score from both sales and marketing leadership

## Related Prompts

- [`../../04_Demand-&-Lead-Generation-&-Growth/Lead-Scoring-&-Pipeline-Management/AI-Powered-B2B-SaaS-Predictive-Lead-Scoring-Architecture-&-Revenue-Qualified-Pipeline-Management-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Lead-Scoring-&-Pipeline-Management/AI-Powered-B2B-SaaS-Predictive-Lead-Scoring-Architecture-&-Revenue-Qualified-Pipeline-Management-Intelligence-Engine.md) — Build the underlying scoring model this alignment architecture feeds into
- [`../../04_Demand-&-Lead-Generation-&-Growth/Lead-Scoring-&-Pipeline-Management/AI-Powered-B2B-SaaS-Pipeline-Coverage-Gap-Detection-&-Emergency-Pipeline-Generation-Sprint-Revenue-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Lead-Scoring-&-Pipeline-Management/AI-Powered-B2B-SaaS-Pipeline-Coverage-Gap-Detection-&-Emergency-Pipeline-Generation-Sprint-Revenue-Intelligence-Engine.md) — When alignment is working but pipeline is still short, use this to identify gaps and sprint
- [`../../04_Demand-&-Lead-Generation-&-Growth/Lead-Nurturing/AI-Powered-B2B-SaaS-Lead-Nurturing-Program-Architecture-&-Behavioral-Segment-Pipeline-Acceleration-Revenue-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Lead-Nurturing/AI-Powered-B2B-SaaS-Lead-Nurturing-Program-Architecture-&-Behavioral-Segment-Pipeline-Acceleration-Revenue-Intelligence-Engine.md) — Design the nurture programs that recycled leads enter after rejection
- [`../../05_Analytics-&-Performance/Pipeline-Velocity-Analytics/AI-Powered-B2B-SaaS-Pipeline-Velocity-Analytics-&-Marketing-Led-Deal-Acceleration-Revenue-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Pipeline-Velocity-Analytics/AI-Powered-B2B-SaaS-Pipeline-Velocity-Analytics-&-Marketing-Led-Deal-Acceleration-Revenue-Intelligence-Engine.md) — Measure the downstream impact of better lead quality on deal velocity

## Integration Tips

**Salesforce:**
- Build a custom Lead Rejection object (related to Lead) to capture rejection reason code, rejecting user, timestamp, and recycling path assigned — this creates an auditable rejection history rather than overwriting status
- Use Salesforce Flow to enforce rejection taxonomy at status change — no free-text rejection notes allowed
- Build a custom dashboard for the weekly smarketing sync that auto-refreshes 1 hour before the meeting invite

**HubSpot:**
- Use HubSpot Workflows with branching logic to automate recycling path enrollment based on rejection reason property
- Build a HubSpot Custom Report combining contact lifecycle stage + lead score + rejection history for the monthly alignment review
- Use HubSpot's Lead Scoring tool with negative scoring for F-code rejection patterns — once a contact type has been rejected for F1 3+ times, apply a negative score that prevents future similar contacts from reaching MQL threshold

**Marketo:**
- Use Marketo Smart Campaigns to handle time-based recycling re-entry — set "scheduled to run" dates dynamically based on rejection date + recycling window
- Use Marketo's Revenue Cycle Model to visualize the full MQL-to-closed-won funnel including recycling loops
- Integrate Marketo Webhook to push rejection events to a data warehouse (Snowflake/BigQuery) for AI model training

**Slack:**
- Create a #smarketing-alerts Slack channel that receives automated posts for: SLA breaches (within 30 minutes of breach), rejection rate spikes above weekly baseline, recycling queue backlogs
- Use Zapier or native Slack + Salesforce integration to push weekly AI-generated smarketing report to the channel every Monday morning

**Revenue Intelligence (Gong/Chorus):**
- Connect call recordings to rejected leads — AI analysis of call transcripts for T-code rejections often reveals nuanced timing objections that the taxonomy code alone doesn't capture
- Use call intelligence to validate rejection reasons: if a rep marks "T2: budget not available" but the call transcript discusses active competitor evaluation, flag for RevOps review

## Troubleshooting

**Issue: Sales reps bypass rejection taxonomy by using workaround statuses**
Solution: Audit CRM weekly for leads that moved to non-standard statuses (e.g., "Not a Fit" custom field instead of Disqualified). The AI agent should scan for taxonomy code nulls on any Disqualified lead weekly. If found, auto-route to RevOps for manual code assignment. After 3 instances from the same rep, trigger a manager notification. The behavior stops when there are no workarounds available in the CRM.

**Issue: Recycled leads re-appear in sales sequences before re-qualifying**
Solution: The core issue is that recycling path enrollment isn't blocking sequence enrollment. Fix: Add a CRM field called "Eligible for Sales Outreach" (boolean, defaulting to FALSE on rejection). This field is the gating condition for every sales sequence enrollment. It only flips to TRUE when the lead re-qualifies through the recycling process. No automation can enroll a lead with FALSE on this field. This is a CRM field, not a tag — it can't be accidentally removed.

**Issue: Scoring model improves rejection rates but MQL volume drops too sharply**
Solution: This is actually success — volume should drop when you raise quality thresholds. But if it drops more than 30% in the first 60 days, it's likely the new thresholds were set too conservatively. Pull the score distribution for the last 90 days of rejected leads and identify whether the new threshold is excluding leads that historically converted. If yes, lower the threshold by 5 points and re-test. If conversion data shows the excluded leads would not have converted, maintain the threshold and inform leadership that lower MQL volume is intentional and tied to higher quality.

## Version History
- v1.0: Initial creation (auto-generated)
