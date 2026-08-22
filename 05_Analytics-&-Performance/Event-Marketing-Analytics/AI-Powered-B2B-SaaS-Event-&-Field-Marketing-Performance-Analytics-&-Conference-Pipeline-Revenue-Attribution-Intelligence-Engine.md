# AI-Powered B2B SaaS Event & Field Marketing Performance Analytics & Conference Pipeline Revenue Attribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** event-marketing, field-marketing, analytics, pipeline-attribution, conference-roi, revenue-intelligence, b2b-saas, marketing-operations

## Overview

This prompt engineers a fully autonomous event marketing measurement system that transforms scattered event data — badge scans, booth visits, meeting notes, sponsored dinner RSVPs, webinar registrations — into unified pipeline attribution, ROI benchmarking, and forward-looking event investment recommendations. Use it when your event spend exceeds $200K annually, your board asks for event ROI, or your event pipeline attribution is stuck on "last-touch field event" with no nuance.

## Quick Copy-Paste Version

You are a senior B2B SaaS marketing analytics strategist with deep expertise in event marketing measurement, pipeline attribution, and field marketing ROI.

Build a complete event marketing performance analytics system for [Your SaaS Company] — a [product category] platform targeting [ICP: e.g., "VP Engineering at 200-2,000 employee SaaS companies"].

Our event portfolio includes:
- Sponsored trade shows and industry conferences (3-5 per year, $25K-$150K each)
- Executive dinners and roundtables we host (8-12 per year, $8K-$20K each)
- Virtual webinars and online summits (monthly, minimal hard cost)
- Speaking engagements at third-party events (pipeline influenced, no booth)
- Customer user conference (1 per year, $300K-$800K)

For each event type, build:
1. Pre-event success criteria and pipeline target-setting methodology
2. During-event lead capture quality scoring (not all badge scans are equal)
3. Post-event attribution model that allocates pipeline credit across touchpoints
4. 90-day pipeline velocity tracking by event type
5. Cost-per-outcome benchmarking: CPL, cost-per-opportunity, cost-per-won-dollar
6. Event mix optimization model — where to cut, where to double down

Include an AI agent workflow that ingests event data from badge scan exports, CRM contacts, and meeting notes, then automatically creates pipeline influence reports, CRM tasks for sales follow-up, and executive-ready ROI summaries.

Output: A complete event analytics playbook with attribution architecture, benchmark targets, measurement cadence, and agent automation specs.

## Advanced Customizable Version

### Role & Identity

You are a senior marketing analytics architect with 15+ years of experience building event measurement systems for B2B SaaS companies at $10M-$500M ARR. You have deep expertise in:
- Multi-touch pipeline attribution for in-person and virtual events
- Revenue operations integration (Salesforce, HubSpot) with event data sources (Cvent, Eventbrite, Splash, Bizzabo)
- Statistical rigor in event ROI measurement, including control group methodology to separate event influence from organic pipeline
- AI agent workflows for automating event data processing, lead enrichment, and sales handoff
- CFO-ready event ROI presentation frameworks that survive finance scrutiny

### Context Requirements

Before building the system, establish:

**Company Profile:**
- Annual event budget: [e.g., $1.2M across all event types]
- ACV: [e.g., $48,000/year]
- Sales cycle length: [e.g., 90-120 days for enterprise]
- ICP: [Company size, industry, buyer title]
- CRM: [Salesforce / HubSpot]
- Event management platform: [Cvent / Splash / Bizzabo / Eventbrite / Manual]
- Current attribution method: [Last-touch / First-touch / Custom / None]
- Events per year by type: [Trade shows X, Owned events X, Virtual X, Speaking X]

**Measurement Gaps to Solve:**
- [ ] No consistent lead quality scoring across event types
- [ ] Badge scans not syncing to CRM correctly
- [ ] Cannot prove which events drive closed-won revenue
- [ ] Event team and demand gen team using different metrics
- [ ] No benchmark for event CPL vs. other channels
- [ ] Cannot make data-driven decisions about which events to cut

### Objective

Design a complete, AI-agent-driven event marketing measurement system with the following deliverables:

---

### Deliverable 1: Event Taxonomy & Tiered Performance Framework

Define a consistent taxonomy across all event types before measurement can be standardized:

**Event Type Classification Matrix:**

| Event Type | Role | Avg Cost | Primary Goal | Pipeline Attribution Window |
|---|---|---|---|---|
| Tier 1 Conference (e.g., Dreamforce, SaaStr) | Sponsor + Booth | $80K-$200K | Pipeline creation + brand | 180 days |
| Tier 2 Conference (industry-specific) | Sponsor + Booth | $20K-$60K | Pipeline creation | 90 days |
| Speaking Engagement (no booth) | Speaker only | $2K-$8K | Brand + dark funnel | 90 days |
| Owned Executive Roundtable | Organizer | $10K-$25K | Pipeline acceleration | 60 days |
| Owned Webinar / Virtual Event | Organizer | $3K-$8K | Pipeline creation + MQL | 45 days |
| Customer User Conference | Organizer | $300K-$800K | Retention + expansion | 180 days |
| Partner/Co-Sponsored Event | Co-organizer | $15K-$40K | Pipeline creation via partner | 90 days |

**Performance Tier Definitions:**

*Tier A — Prove & Scale:*
- Pipeline influenced ≥ 5x event cost within attribution window
- CPL ≤ 60% of blended marketing CPL benchmark
- ≥ 30% of attendee contacts advance to SQL or Opportunity within 90 days
- Decision: Increase investment 20-40% year-over-year

*Tier B — Optimize & Hold:*
- Pipeline influenced 2-4x event cost
- CPL within 80-120% of blended benchmark
- 15-30% attendee contact advancement rate
- Decision: Maintain budget, implement specific optimizations, re-evaluate in 6 months

*Tier C — Fix or Cut:*
- Pipeline influenced < 2x event cost
- CPL > 120% of blended benchmark
- < 15% attendee contact advancement
- Decision: Identify root cause (wrong event, poor follow-up, wrong audience) — fix one variable, cut if still Tier C at next occurrence

---

### Deliverable 2: Event Lead Quality Scoring Engine

Not all event interactions carry equal pipeline weight. Implement a five-dimension lead quality score at the point of capture:

**Event Lead Quality Score (ELQS) — 100-Point Scale:**

**Dimension 1: ICP Fit (0-30 points)**
- Company size matches ICP (target range): 15 points
- Industry/vertical matches ICP: 10 points
- Job title/function matches buyer or influencer persona: 5 points
- Scoring tool: Enrich badge scan data with Clearbit/Apollo/Clay in real-time at the booth

**Dimension 2: Engagement Depth (0-25 points)**
- Attended a session/keynote where your company was featured: 5 points
- Visited booth + demo viewed (tracked via iPad or badge scanner): 10 points
- Requested follow-up meeting at event: 15 points
- Attended your hosted event (dinner, roundtable, VIP experience): 20 points (use max, not additive)

**Dimension 3: Buying Signal (0-20 points)**
- Mentioned active evaluation or RFP in conversation: 15 points
- Asked pricing/packaging questions: 10 points
- Referenced competitor pain point: 5 points
- No qualifying conversation held: 0 points

**Dimension 4: CRM History (0-15 points)**
- Known account (exists in CRM): 5 points
- Account in ICP TAM list: 5 points
- Previous marketing engagement (email open, content download, webinar): 5 points
- New account with no prior touch: 0 points

**Dimension 5: Recency & Context (0-10 points)**
- Event occurs within account's buying cycle (Q1/Q2 for fiscal year buyers): 5 points
- Identified by sales as target account pre-event: 5 points

**ELQS Thresholds:**
- 70-100: Hot Lead — AE contact within 24 hours, auto-create Opportunity in CRM
- 45-69: Warm Lead — SDR sequence activation within 48 hours, MQL status
- 25-44: Nurture Lead — Marketing automation enrollment, event nurture track
- 0-24: Contact Only — CRM contact creation, no immediate sales action

---

### Deliverable 3: Multi-Touch Attribution Model for Events

Events are rarely the only touchpoint in a B2B SaaS deal. Use a position-based attribution model calibrated for event influence:

**Recommended Attribution Framework: Event-Adjusted W-Shaped Model**

Standard W-shape attributes 30% to first touch, 30% to lead creation, 30% to opportunity creation, 10% distributed across middle touches. For events, apply the following adjustments:

*Scenario A: Event is first touch (cold attendee with no prior engagement)*
- Event gets 40% pipeline credit (10% uplift from standard first touch — event costs warrant higher credit)
- Subsequent touches split remaining 60%

*Scenario B: Event accelerates existing opportunity (contact in active pipeline attends event)*
- Do NOT create new pipeline credit — track as "Event Influenced Opportunity"
- Measure sales cycle compression: compare cycle length for event-influenced vs. non-influenced opps
- Report metric: Average days saved in sales cycle due to event touch (typically 15-35 days in B2B SaaS)

*Scenario C: Event re-engages dormant contact (cold for > 90 days, re-activates post-event)*
- Event gets 50% first-touch credit (strong signal of event causality)

*Scenario D: Meeting booked AT the event converts to closed-won*
- Event gets 35% first-touch + 35% opportunity-creation credit (60% total — highest single-channel credit)

**Attribution Implementation in Salesforce / HubSpot:**

Custom Field: Event_Attribution_Type (picklist)
Values: First Touch | Accelerator | Re-Engagement | Booked Meeting

Custom Field: Event_Name (text — standardized event naming convention)
Format: [Year]-[Event Type]-[Event Name] e.g., "2026-CONF-SaaStr Annual"

Custom Field: Event_Attendance_Type (picklist)
Values: Booth Visit | Session Attendee | Hosted Event | Speaker Audience | Virtual Attendee

Custom Object: Event_Touchpoint (related to Contact + Campaign)
Fields: Event Name, Date, ELQS Score, Attribution Type, AE Notified (Y/N), Follow-Up Date

**Control Group Methodology (for statistically rigorous ROI measurement):**

For large events (> 200 contacts), create a control group to separate event lift from organic pipeline:
1. Pull all contacts at target accounts who were eligible to attend but did NOT attend
2. Track their pipeline advancement rate for 90 days post-event
3. Compare to event attendee advancement rate
4. Event Lift = (Attendee advancement rate) - (Non-attendee advancement rate)
5. Only apply Event Lift % to pipeline for attributable event revenue claim

Example: If 25% of event attendees advance to SQL vs. 12% of eligible non-attendees, event lift = 13 percentage points. Apply 13% uplift (not 25% total) to event pipeline attribution for credible CFO reporting.

---

### Deliverable 4: Event ROI Measurement Dashboard Architecture

**Primary Event KPIs (measure within 90 days of each event):**

| Metric | Calculation | Target Benchmark |
|---|---|---|
| Cost Per Event Lead (CPEL) | Event Cost / Total Leads Captured | < 120% of blended CPL |
| Cost Per Qualified Event Lead (CPQEL) | Event Cost / ELQS ≥ 45 leads | < $800 for mid-market events |
| Event-Sourced Pipeline | Sum of pipeline created where event = first touch | ≥ 3x event cost |
| Event-Influenced Pipeline | Pipeline that had event touchpoint in buyer journey | ≥ 5x event cost |
| Pipeline Per Attendee | Total pipeline created / total unique attendees | > $2,000 for sponsored conferences |
| Event MQL to SQL Conversion | Event MQLs → SQLs in 45 days | ≥ 25% (vs. 15-18% blended) |
| Sales Cycle Compression | Days to close for event-influenced vs. non-influenced | ≥ 15 days shorter |
| Event Closed-Won Revenue | Closed ARR attributed to event (180-day window) | ≥ 1.5x event cost by month 12 |

**Executive Event ROI Report Structure (auto-generated post-event):**

EVENT PERFORMANCE REPORT: [Event Name] — [Date]

INVESTMENT: $[Total Cost]
  → Sponsorship fee: $X | Booth/logistics: $X | Travel/hotel: $X | Hosted dinner: $X

RESULTS AT 30 DAYS:
  → Leads captured: [N] | Qualified leads (ELQS 45+): [N] | 
  → Meetings booked at event: [N] | Meetings completed post-event: [N]
  → Opportunities created: [N] | Pipeline sourced: $[X]

RESULTS AT 90 DAYS:
  → SQLs advanced: [N] | Active Opportunities: [N]
  → Pipeline sourced: $[X] | Pipeline influenced: $[X]
  → Cost-per-sourced-opportunity: $[X]
  → Projected closed-won at 12 months: $[X] (based on avg win rate [%])

BENCHMARK COMPARISON:
  → vs. prior [Event Name]: +/- [X]%
  → vs. blended marketing CPL: [better/worse] by [X]%
  → vs. Tier A threshold (5x cost): [On track / Below target]

RECOMMENDATION: [Tier A — Scale / Tier B — Optimize / Tier C — Cut]
NEXT YEAR INVESTMENT RECOMMENDATION: $[X] ([+/-X]% vs. this year)

---

### Deliverable 5: AI Agent Automation Architecture

**Agent 1: Event Lead Ingestion & Enrichment Agent (runs post-event, triggered manually)**

Trigger: Manual activation post-event OR file upload of badge scan CSV

Actions:
1. Ingest badge scan export (CSV/API from Cvent, Bizzabo, or manual scan list)
2. Deduplicate against existing CRM contacts (match on email + company domain)
3. Enrich each new contact via Clay/Apollo API:
   → Company name, domain, employee count, industry, funding stage
   → Contact job title, LinkedIn URL, department, seniority level
4. Calculate ELQS score for each contact using 5-dimension scoring model
5. Create/update CRM records:
   → New contacts: Create as MQL with source = [Event Name] + ELQS score field
   → Existing contacts: Add event touchpoint to activity timeline
6. Create Event Campaign in CRM, associate all contacts to campaign
7. Segment into follow-up tiers based on ELQS:
   → ELQS 70+: Create Opportunities + assign to AE + Slack alert to AE
   → ELQS 45-69: Enroll in SDR email sequence "Event Hot Lead"
   → ELQS 25-44: Enroll in marketing nurture "Event Attendee Track"
   → ELQS 0-24: Create contact only, no immediate sequence
8. Generate Event Lead Quality Summary: "85 contacts processed. 12 Hot (70+), 
   28 Warm (45-69), 31 Nurture (25-44), 14 Contact-only. 
   Estimated pipeline potential at current ELQS mix: $[X]"

**Agent 2: Post-Event Follow-Up Compliance Monitor (runs daily for 7 days post-event)**

Trigger: Scheduled daily at 8:00 AM for 7 days post-event

Actions:
1. Check all Opportunities and MQLs created from event (filter by Campaign)
2. Identify contacts with ELQS ≥ 70 where no AE activity logged within 48 hours
3. Escalation sequence:
   → Day 2 (no contact): Slack reminder to AE: "[Contact] at [Account] needs follow-up 
     — ELQS 82, requested demo at [Event]. Last event contact had $[X] ACV."
   → Day 4 (still no contact): Slack to AE manager: "SLA breach — [AE Name] has not 
     followed up with [N] hot event leads. Flagging for review."
   → Day 7 (still no contact): Auto-reassign to SDR with notification to AE
4. Track follow-up SLA compliance rate: target ≥ 90% of Hot leads contacted in 48 hours
5. Generate daily compliance report: "Day 3 post-[Event]: 9/12 Hot leads contacted 
   (75%). 3 overdue — [AE Name] has 2, [AE Name] has 1. Revenue at risk: ~$[X]K."

**Agent 3: 90-Day Pipeline Attribution Reporter (runs at Day 30, 60, 90 post-event)**

Trigger: Scheduled at Day 30, 60, and 90 after event end date

Actions:
1. Pull all Contacts and Opportunities associated with Event Campaign
2. Calculate pipeline metrics:
   → Event-sourced pipeline: Sum ARR where Opportunity.Lead_Source = [Event]
   → Event-influenced pipeline: Sum ARR where Opportunity has event touchpoint
   → MQL-to-SQL conversion rate for this event vs. trailing 12-month event average
   → Pipeline per dollar invested
3. Compare to event benchmark thresholds (Tier A/B/C classification)
4. Generate auto-formatted ROI report (see Deliverable 4 template)
5. Send report to CMO + Demand Gen Lead via email + Slack
6. Update Event ROI Tracking Google Sheet:
   → Row per event, columns: Event Name, Date, Cost, Pipeline 30d/60d/90d, 
     Opportunities, SQLs, Win Rate, Closed-Won (to be updated at 180d), Tier
7. Flag if event is tracking Tier C at Day 60: "Early warning: [Event] is tracking 
   below 2x pipeline coverage at Day 60. Recommend immediate sales leadership review 
   of follow-up quality before Day 90 window closes."

**Agent 4: Annual Event Portfolio Optimizer (runs quarterly)**

Trigger: Quarterly, first Monday of Q2, Q3, Q4, Q1

Actions:
1. Pull trailing 12-month data for all events from Event ROI Google Sheet
2. Calculate blended benchmarks:
   → Average CPL across all event types
   → Average pipeline per event dollar by event type
   → Win rate for event-sourced vs. non-event-sourced pipeline
3. Run event portfolio scoring:
   → Rank all events by cost-per-won-dollar (most efficient to least)
   → Classify each recurring event as Tier A/B/C
   → Flag events with < 2 data points as "Insufficient data — requires 1 more occurrence"
4. Generate Event Portfolio Recommendations:
   → "Scale (Tier A): [Event List] — recommend 20-30% budget increase each"
   → "Optimize (Tier B): [Event List] — specific fixes: [pre-event outreach cadence, 
     audience targeting, booth staffing, follow-up speed]"
   → "Cut (Tier C): [Event List] — estimated savings: $[X]. Reallocate to: [top Tier A events]"
5. Draft Event Budget Recommendation memo for CMO review
6. Model projected pipeline impact of recommended budget reallocation

---

### Deliverable 6: Event Measurement Governance Standards

**Pre-Event Requirements (must complete ≥ 3 weeks before event):**
- [ ] Define target attendee list from CRM: Which accounts/contacts should be there?
- [ ] Set pipeline target for this specific event (minimum Tier B threshold)
- [ ] Confirm badge scan integration with CRM (test scan 48 hours before)
- [ ] Brief AEs on event ELQS scoring criteria and follow-up SLA (48 hours for Hot leads)
- [ ] Set up UTM tracking for all event-related digital assets (registration page, email invites)
- [ ] Create Event Campaign in CRM before event date

**At-Event Data Capture Requirements:**
- All booth interactions logged via badge scan or manual entry (no exceptions)
- Conversation notes captured in real-time via mobile CRM app or voice-to-text tool
- Meeting outcomes logged same day: next step, interest level, ELQS manual override if needed
- Demo requests immediately escalate to "Meeting Booked" status in event tracking

**Post-Event Requirements (within 48 hours):**
- Badge scan data exported and fed into Agent 1 for CRM ingestion
- AE-confirmed Hot Leads (ELQS 70+) must have first outreach logged
- Event debrief document completed: What worked, what didn't, recommendation for next occurrence

---

## Example Input/Output

**Company:** Meridian Workflow — B2B SaaS project management and workflow automation platform for mid-market professional services firms (50-250 employees)
- ACV: $32,000/year
- ICP: VP Operations, COO, Head of Professional Services
- Annual event budget: $680,000
- Events this year: SaaStr Annual (sponsored), ProjectWorld Conference (sponsored), 6 executive dinners, monthly webinar series, 1 customer summit
- CRM: Salesforce

**Sample Output — Quarterly Event Portfolio Review (Q2 2026):**

*Event Performance Summary — Q1 2026:*

| Event | Cost | Leads | Hot ELQS | Pipeline 90d | Pipeline/$ | Tier |
|---|---|---|---|---|---|---|
| SaaStr Annual (March) | $145,000 | 312 | 28 | $820,000 | 5.7x | A |
| ProjectWorld (Feb) | $38,000 | 94 | 6 | $68,000 | 1.8x | C |
| Executive Dinners (3x) | $52,000 | 87 | 31 | $340,000 | 6.5x | A |
| Monthly Webinars (3x) | $14,000 | 428 | 19 | $115,000 | 8.2x | A |

*Portfolio Recommendation memo (auto-generated by Agent 4):*

"Q1 event data reveals a bifurcated portfolio. SaaStr Annual (Tier A, 5.7x) and executive dinners (Tier A, 6.5x) are significantly outperforming. Webinars remain the highest pipeline-per-dollar channel at 8.2x, despite minimal hard cost.

ProjectWorld Conference (Tier C, 1.8x) has now underperformed at 2 consecutive occurrences (Q3 2025: 2.1x, Q1 2026: 1.8x). Root cause analysis points to audience mismatch — ProjectWorld skews toward construction/engineering PMs, not professional services leaders. Recommend cutting 2027 sponsorship ($38,000 savings).

Budget Reallocation Proposal:
→ Reinvest $38K saved from ProjectWorld into: SaaStr Annual booth upgrade (+$20K for private meeting space) and 2 additional executive dinners (+$18K, estimated $130K additional pipeline).
→ Projected pipeline impact of reallocation: +$390,000 incremental 90-day pipeline vs. current allocation."

---

## Success Metrics

A well-executed prompt output should produce:
- [ ] Event taxonomy with 7+ event types, consistent definitions, and attribution windows
- [ ] ELQS scoring model with 5 weighted dimensions — not a binary MQL/non-MQL call
- [ ] Attribution model that handles all 4 event touchpoint scenarios (first touch, accelerator, re-engagement, booked meeting)
- [ ] Control group methodology to separate event causality from correlation
- [ ] 4 AI agent specs implementable in HubSpot/Salesforce + Clay/n8n within 3 weeks
- [ ] Executive ROI report template that answers CFO questions without additional analysis
- [ ] Tier A/B/C performance classification with specific optimization actions per tier
- [ ] Quarterly portfolio optimizer that produces a budget reallocation recommendation

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Events-&-Webinars/AI-Powered-B2B-SaaS-Field-Event-&-Trade-Show-Pipeline-Architecture-&-In-Person-Event-Revenue-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Events-&-Webinars/AI-Powered-B2B-SaaS-Post-Event-Follow-Up-&-Attendee-to-Pipeline-Revenue-Conversion-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md`
- `../../01_CMO-&-Leadership/Reporting-&-ROI/AI-Powered-B2B-CMO-Monthly-Marketing-Business-Review-&-Revenue-Performance-Intelligence-Engine.md`

## Integration Tips

**Salesforce:**
- Create a custom `Event_Touchpoint__c` object related to both Contact and Campaign — enables true multi-touch event attribution without polluting the standard Lead object
- Build a Salesforce Flow that auto-calculates ELQS when a Campaign Member is created with Campaign Type = "Event"
- Use Salesforce Reports to track "Event-Influenced Pipeline" by filtering Opportunities where any related Contact has an Event_Touchpoint with the event date in the attribution window
- Create a dedicated Event Analytics Dashboard with Report components for each event tier

**HubSpot:**
- Use HubSpot Custom Properties to store `event_elqs_score`, `event_name`, `event_date`, `event_follow_up_tier` on the Contact record
- Build a Workflow: when Contact `event_elqs_score` ≥ 70, create a Task assigned to the Contact Owner (AE) with due date = 2 business days from enrollment
- Connect HubSpot to Splash or Eventbrite via native integration or Zapier for automated event registration sync
- Use HubSpot Lists to segment event leads by ELQS tier for targeted nurture sequence enrollment

**Clay (Lead Enrichment):**
- Build a Clay table that accepts badge scan CSV uploads, enriches each row with firmographic data (Clearbit/Apollo), calculates ELQS score via formula columns, then pushes enriched records to CRM via API
- Use Clay's AI column to generate personalized follow-up email drafts for AEs based on event conversation notes + company context
- Set up Clay webhook to trigger automatically when a new CSV is uploaded to a Google Drive folder (one folder per event)

**Cvent / Bizzabo / Splash:**
- Use native CRM integrations to sync event registrations and badge scan data automatically — avoid manual CSV exports when possible
- Configure custom registration questions that map to ELQS dimensions (e.g., "Are you currently evaluating solutions?" maps to Buying Signal scoring)
- Use Cvent's reporting API to pull session attendance data for attendees who attended your sponsored session (session attendance = Dimension 2 signal)

**Google Sheets + Looker Studio:**
- Maintain a master Event ROI Tracker in Google Sheets as the source of truth for cross-event benchmarking (CRM dashboards are siloed by event; Sheets enables portfolio-level comparison)
- Connect Looker Studio to the Google Sheet for a self-refreshing Event Portfolio Dashboard accessible to CMO and finance team without CRM access
- Include a rolling 12-month event calendar view showing planned investment vs. actual spend and pipeline coverage by quarter

## Troubleshooting

**Problem: Badge scan data quality is inconsistent — different events use different formats, fields are missing, company names are misspelled**
Fix: Standardize the enrichment-first approach. Never rely on badge scan data as the source of truth for company name, title, or contact quality. Instead, treat the email address as the only reliable field from badge scans, then enrich everything else via Clay/Clearbit/Apollo at the point of CRM ingestion. Build your ELQS scoring on enriched data, not raw badge scan fields. For events without badge scanning (attendee-hosted dinners, speaking sessions), create a templated mobile form (Typeform or HubSpot form on iPad) for booth staff to capture contacts with structured fields.

**Problem: Sales team claims events don't generate quality pipeline — but event attribution in CRM shows strong numbers**
Fix: This perception gap usually comes from lag between event and follow-up, not event quality. Audit follow-up SLA compliance: if AEs are taking 5-7 days to contact Hot leads instead of 48 hours, event quality degrades dramatically (research shows lead conversion rates drop 400% after 5 days). Run a cohort analysis: compare win rates for event leads contacted within 48 hours vs. those contacted after 5+ days. Share the data with sales leadership. If follow-up speed is within SLA and quality is still poor, run the control group analysis (Deliverable 3) to isolate whether the event is truly generating incremental pipeline or just capturing contacts who would have converted anyway.

**Problem: Cannot distinguish event influence from other marketing touches in multi-touch deals**
Fix: This is a fundamental attribution problem, not an event problem. Implement the Event-Adjusted W-Shaped model from Deliverable 3 and use the CRM `Attribution_Type` field to categorize each event touchpoint's role in the deal. For CFO reporting, use the control group methodology to establish an event lift percentage — this is defensible in finance reviews because it compares outcomes (not just touches). Accept that perfect attribution is impossible; the goal is directionally accurate portfolio-level comparisons, not per-deal precision.

## Version History
- v1.0: Initial creation (auto-generated) — August 2026
