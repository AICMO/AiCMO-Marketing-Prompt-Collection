# Post-Event Lead Conversion & Pipeline Attribution Intelligence Engine - AI-Powered System for Converting Event Attendees into Revenue Pipeline

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** event-marketing, lead-conversion, pipeline-attribution, demand-gen, b2b, automation, account-based

## Overview
This engine transforms raw event attendance data into a scored, segmented, and fully-orchestrated post-event follow-up system — automatically prioritizing attendees by pipeline potential, assigning personalized follow-up sequences, attributing pipeline to specific event touchpoints, and escalating high-value opportunities to AEs within minutes of event close. Use it after tradeshows, virtual summits, executive dinners, webinars, and field events.

## Quick Copy-Paste Version

You are a B2B demand generation expert specializing in post-event pipeline conversion. I just completed an event and need to convert attendees into sales pipeline.

Event Details:
- Event Name: [Event Name]
- Event Type: [Tradeshow / Webinar / Executive Dinner / Virtual Summit / Field Event]
- Total Attendees/Leads: [Number]
- ICP Profile: [Your ideal customer — title, company size, industry]
- Average Deal Size: [$ ACV]
- Sales Cycle: [Days]
- CRM: [HubSpot / Salesforce / Other]
- Sales Engagement Tool: [Outreach / Salesloft / Apollo / Other]

Please produce:

1. ATTENDEE SCORING MODEL
Create a point-based scoring rubric (0-100) that weights:
- ICP fit (industry, company size, title match): 40 points
- Engagement depth at event (session attendance, booth time, demo requests, content downloads): 30 points
- Buying signal indicators (asked pricing, requested follow-up, brought colleagues): 20 points
- Recency and timing signals (active job posting for relevant roles, recent funding): 10 points

Segment scored leads into:
- Tier 1 HOT (70-100): AE-owned immediate follow-up within 4 hours
- Tier 2 WARM (40-69): SDR-owned follow-up within 24 hours with personalized sequence
- Tier 3 NURTURE (0-39): Marketing automation nurture track

2. FOLLOW-UP SEQUENCE BY TIER
Write complete email sequences for each tier:

Tier 1 (3 touchpoints over 5 days): AE sends personal note referencing specific conversation, value prop, clear next step
Tier 2 (5 touchpoints over 14 days): SDR sequence with event callback, insight share, case study, ROI angle, breakup
Tier 3 (7-email nurture over 60 days): Content-led educational sequence

3. PIPELINE ATTRIBUTION FRAMEWORK
Define attribution rules for sourcing and influencing credit:
- What constitutes "event-sourced" pipeline
- How to split credit when event was one of multiple touchpoints
- Recommended UTM structure and CRM campaign tagging
- How to build the attribution report in [HubSpot/Salesforce]

4. POST-EVENT DEBRIEF METRICS
List the 10 KPIs to measure within 30, 60, and 90 days post-event to determine event ROI.

5. SLACK/TEAMS ALERT TEMPLATE
Write the internal Slack notification template to alert the AE/SDR team immediately with lead assignments.

## Advanced Customizable Version

ROLE: You are a Senior Demand Generation Strategist and Revenue Operations Architect with 15+ years running B2B event marketing programs at scale. You have deep expertise in lead scoring models, sales engagement platforms, CRM attribution, and AI-powered follow-up orchestration. You've managed post-event programs that converted 15-25% of attendees into pipeline opportunities.

CONTEXT:
Company: [Company Name]
Stage: [Series A / Series B / Enterprise / Public]
Product: [One-sentence description]
ICP: 
  - Primary: [Title] at [Company Size] [Industry] companies
  - Secondary: [Title] at [Company Size] [Industry] companies
  - Negative ICP (exclude): [Criteria that disqualifies leads]
ACV: $[Amount]
Sales Cycle: [Days] average
Win Rate: [%]
CRM: [HubSpot / Salesforce / Other]
Marketing Automation: [Marketo / HubSpot / Pardot / Other]
Sales Engagement: [Outreach / Salesloft / Apollo / Groove / Other]
Video Prospecting Tool: [Vidyard / Loom / BombBomb / None]

EVENT DETAILS:
Event Name: [Name]
Event Type: [Tradeshow | Virtual Summit | Webinar | Executive Dinner | Field Event | Conference Speaking]
Event Date(s): [Date(s)]
Total Registered: [Number]
Total Attended: [Number]
Attendance Rate: [%]
Booth/Session Interactions: [Number]
Demo Requests at Event: [Number]
Business Cards / Badge Scans / Form Fills: [Number]
Content Downloads During Event: [Number]
Pre-Event Intent Data Available: [Yes/No — source: 6sense / Bombora / G2 / Other]

OBJECTIVE: Create a complete post-event intelligence system that:
1. Scores and segments every attendee by pipeline potential
2. Routes leads to the right follow-up owner within 2 hours of event close
3. Executes hyper-personalized, multi-channel follow-up automatically
4. Attributes pipeline accurately to event touchpoints for budget justification
5. Generates executive-ready ROI reporting at 30/60/90 days

---

DELIVERABLE 1: AI-POWERED LEAD SCORING ENGINE

Design a weighted scoring algorithm (0-100 scale) with these dimensions:

A. FIRMOGRAPHIC FIT (40 points max):
- Company size match to ICP: [exact match = 15pts, adjacent = 8pts, miss = 0pts]
- Industry/vertical match: [exact = 10pts, adjacent = 5pts, miss = 0pts]
- Title/seniority match: [economic buyer = 15pts, influencer = 10pts, end user = 5pts, blocker = 0pts]

B. EVENT ENGAGEMENT DEPTH (30 points max):
- Requested a demo or meeting: 15pts
- Attended a session, keynote, or roundtable: 8pts
- Visited booth or interacted with staff: 7pts
- Downloaded content or scanned badge only: 3pts
- Registered but did not attend (virtual): 1pt

C. BUYING SIGNALS (20 points max):
- Explicitly asked about pricing, timelines, or contracts: 10pts
- Brought colleagues from the buying committee: 5pts
- Referenced a current vendor, competitive evaluation, or pain point: 5pts
- Indicated active budget or initiative: bonus 5pts (can exceed cap)

D. INTENT & TIMING SIGNALS (10 points max — use if intent data available):
- Active in-market intent signal from 6sense/Bombora: 5pts
- G2 product page visit in last 30 days: 3pts
- Recent trigger event (funding, hiring surge, exec change): 2pts

SCORING TIER ASSIGNMENT:
- HOT (75-100): [Specific routing and SLA]
- WARM (45-74): [Specific routing and SLA]
- ENGAGED (25-44): [Specific routing and SLA]
- NURTURE (0-24): [Specific routing and SLA]

OUTPUT: Provide the scoring rubric as a structured table that can be imported into a spreadsheet or used as a scoring prompt for AI enrichment.

---

DELIVERABLE 2: COMPLETE FOLLOW-UP SEQUENCE LIBRARY

Write all email and LinkedIn outreach copy for each tier. All copy must:
- Reference the specific event by name
- Avoid generic "just following up" language
- Lead with a relevant insight, observation, or value hook
- Have a single, clear CTA per touchpoint
- Be under 120 words for emails (150 for LinkedIn)

TIER 1 — HOT LEAD SEQUENCE (AE-Owned, 4-hour SLA):
Touchpoint 1 (Hour 4 — AE personal email): Reference specific conversation from event, acknowledge their stated challenge, propose a concrete next step (30-min call with agenda)
Touchpoint 2 (Day 2 — AE LinkedIn DM): Reinforce the value with a relevant customer story or data point
Touchpoint 3 (Day 5 — AE email with collateral): Send tailored 1-pager or ROI case study relevant to their vertical, propose calendar link

TIER 2 — WARM LEAD SEQUENCE (SDR-Owned, 24-hour SLA):
Touchpoint 1 (Day 1 — SDR email): Event callback + specific value prop for their role
Touchpoint 2 (Day 3 — LinkedIn connect + note): Professional connection with context
Touchpoint 3 (Day 5 — SDR email): Insight email — share a relevant industry stat or trend with subtle relevance to your product
Touchpoint 4 (Day 8 — SDR email): Customer case study email — 1 specific customer success story matching their vertical/size
Touchpoint 5 (Day 14 — SDR breakup email): Acknowledge timing might be off, offer to resurface in 90 days, include a self-serve resource

[If video prospecting tool available:]
Touchpoint 2.5 (Day 4 — personalized video via Vidyard/Loom): 60-second personalized video referencing event + their specific company

TIER 3 — NURTURE SEQUENCE (Marketing Automation, 60-day track):
Email 1 (Day 3): Welcome to ongoing relationship — share most valuable content asset
Email 2 (Day 10): Educational insight relevant to their likely pain point
Email 3 (Day 18): Customer success story in their industry
Email 4 (Day 25): Invite to upcoming webinar or virtual event
Email 5 (Day 35): Trend report or benchmark data relevant to their role
Email 6 (Day 45): Product use case relevant to their company profile
Email 7 (Day 60): Soft re-engagement — "Is now a better time?"

---

DELIVERABLE 3: MULTI-TOUCH ATTRIBUTION FRAMEWORK

Define the complete attribution model for this event:

A. SOURCE ATTRIBUTION RULES:
- Definition of "event-sourced" pipeline: [Lead was first known via event registration/attendance and had no prior CRM record OR was inactive for 180+ days]
- Definition of "event-influenced" pipeline: [Lead was known but event was a touchpoint within the 180-day window before opportunity creation]
- How to tag: Campaign = [Event Name], Campaign Type = Event, Attribution Window = [90 days]

B. UTM STRUCTURE:
Provide exact UTM parameters for:
- Pre-event email campaigns
- Event registration landing pages
- Post-event follow-up emails
- Any paid retargeting of event attendees
Format: utm_source / utm_medium / utm_campaign / utm_content / utm_term

C. CRM CAMPAIGN STRUCTURE:
- HubSpot: Define the campaign hierarchy (Parent Campaign > Child Campaigns per tactic)
- OR Salesforce: Define Campaign hierarchy and Campaign Member Statuses
- Member Status definitions: Invited → Registered → Attended → Engaged → Opportunity

D. ATTRIBUTION SPLIT FOR MULTI-TOUCH DEALS:
- If event was the FIRST touch: 100% event source credit
- If event was the LAST touch before opp creation: 50% source credit
- If event was a MIDDLE touch: Influenced credit only, no source
- For W-shaped / Full-path attribution models: specify how to configure in HubSpot/Salesforce

---

DELIVERABLE 4: POST-EVENT ROI DASHBOARD SPECIFICATION

Define the exact metrics and data sources for the post-event ROI report:

30-DAY METRICS (Speed & Conversion):
1. Lead-to-meeting rate by tier (target: Tier 1 ≥ 40%, Tier 2 ≥ 20%)
2. Meeting-to-opportunity rate (target: ≥ 50% of meetings)
3. Total pipeline sourced (opportunities created where event = source)
4. Total pipeline influenced (opportunities touched where event = influence)
5. Cost per meeting (event spend / total meetings booked)
6. Cost per opportunity (event spend / opportunities created)

60-DAY METRICS (Pipeline Health):
7. Pipeline stage progression (% moving to Stage 2+)
8. Sequence completion rate and engagement (reply rate, click rate by tier)
9. Pipeline velocity (days to advance one stage vs. baseline)
10. Unresponsive lead rate (flag for re-routing or marketing nurture)

90-DAY METRICS (Revenue Impact):
11. Closed-won revenue attributed to event
12. ROI calculation: (Revenue Attributed - Event Cost) / Event Cost x 100
13. Average deal size vs. company baseline
14. Sales cycle length vs. baseline
15. Event vs. other demand gen sources: pipeline efficiency comparison

Provide the report as a structured template that can be built in Google Sheets or imported as a dashboard in HubSpot/Salesforce.

---

DELIVERABLE 5: AI AGENT AUTOMATION BLUEPRINT

Design the complete AI agent workflow that runs automatically after the event closes:

Step 1 — DATA INGESTION (T+0 hours):
- Pull attendee/lead list from event platform (Hopin, Webex Events, ON24, Cvent, badge scan CSV)
- Enrich each record via [Clearbit / Apollo / ZoomInfo / 6sense API]
- Cross-reference against CRM to identify existing contacts vs. net-new

Step 2 — SCORING & SEGMENTATION (T+1 hour):
- Apply scoring rubric automatically
- Assign tier classification
- Identify which leads belong to existing open opportunities (flag for AE)
- Identify leads from top target accounts (ABM list)

Step 3 — ROUTING & ASSIGNMENT (T+2 hours):
- Tier 1: Create task in CRM assigned to territory AE, send Slack/Teams alert with lead score, event notes, and suggested talking points
- Tier 2: Enroll in SDR sequence in Outreach/Salesloft/Apollo
- Tier 3: Enroll in HubSpot/Marketo nurture workflow

Step 4 — PERSONALIZATION LAYER (T+2-4 hours):
- For Tier 1-2: Generate personalized first-touch email using attendee's company, title, inferred pain point, and event interaction data
- If video tool available: Generate video script personalized to top 20 Tier 1 leads

Step 5 — EXECUTIVE REPORTING (T+24 hours):
- Auto-generate post-event pipeline summary: leads by tier, meetings booked, estimated pipeline at target conversion rates
- Email to CMO, VP Demand Gen, VP Sales, SDR Manager

Specify the tools, APIs, and automation platforms (Zapier, Make, n8n, Clay, HubSpot Workflows, Salesforce Flow) needed to execute each step without human intervention.

---

OUTPUT FORMAT:
Return each deliverable as a clearly labeled section with copy-paste ready content. All email sequences should be formatted with Subject Line and Body clearly labeled. All tables should use markdown format. Include an Executive Summary at the top summarizing the expected pipeline output based on the attendee numbers provided.

## Example Input/Output

**Input Example:**
Company: Vaultify (B2B SaaS)
Product: AI-powered contract management platform for legal and finance teams
ICP: Legal Operations Managers, General Counsel, CFOs at 500-5000 employee companies
ACV: $65,000
Event: LegalTech Summit 2026 — 3-day conference in San Francisco
Total attendees/leads captured: 187
Demo requests at event: 23
ICP-match estimate: ~60%
CRM: Salesforce
Sales Engagement: Outreach
Video Tool: Vidyard

**Output Example (Excerpt):**

**Executive Summary:**
187 leads captured → 112 ICP-match candidates → estimated 22 HOT, 51 WARM, 39 NURTURE. At target conversion rates (Tier 1: 40% meeting rate, Tier 2: 18%), projected 23 meetings within 14 days. At 50% meeting-to-opportunity rate and $65K ACV: estimated $747,500 in sourced pipeline by Day 30.

**Scoring Model (Sample):**

| Criteria | Max Points | Example Score |
|---|---|---|
| Title = GC, Legal Ops, CLO | 15 | 15 |
| Company 500-5000 employees | 15 | 15 |
| Legal / Tech / Finance industry | 10 | 10 |
| Requested demo at event | 15 | 15 |
| Attended contract mgmt session | 8 | 8 |
| Mentioned current vendor pain | 5 | 5 |
| 6sense in-market signal | 5 | 5 |
| **Total** | **100** | **73 → WARM** |

**Tier 1 Email — Touchpoint 1 (AE, Hour 4):**
Subject: Your exact comment about contract turnaround time
Body: [Name], when you mentioned that your team spends 3 weeks on average just getting contracts reviewed and signed — that's exactly what our customers at [Similar Company] felt before cutting that to 4 days. I'd love to show you a 25-minute walkthrough of how they did it. Does [Day] at [Time] work? — [AE Name]

**Tier 2 Email — Touchpoint 1 (SDR, Day 1):**
Subject: From LegalTech Summit → your contract workflow
Body: [Name], great meeting you at LegalTech yesterday. Legal ops teams at companies like yours are averaging 22 days to fully execute a contract — we cut that to under 5 with AI-native redlining and approval routing. Worth 20 minutes to see if Vaultify's a fit for your stack? Book here: [Link]

## Success Metrics

- **Meeting booking rate:** Tier 1 ≥ 40% within 7 days, Tier 2 ≥ 18% within 14 days
- **Sequence reply rate:** Tier 2 sequences ≥ 8% positive reply rate
- **Pipeline sourced:** ≥ 10x event cost in sourced pipeline by Day 60
- **Lead routing speed:** 100% of Tier 1 leads assigned and first-touch sent within 4 hours
- **Attribution accuracy:** ≥ 90% of event leads properly tagged in CRM campaign
- **Opportunity creation rate:** ≥ 12% of ICP-match attendees become opportunities by Day 45
- **Event ROI:** Net-positive ROI (revenue closed ≥ event cost) by Day 90

## Related Prompts
- `../../04_Demand-&-Lead-Generation-&-Growth/Event-Marketing/B2B-Conference-Event-Demand-Generation-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Event-Marketing/Virtual-Summit-Webinar-Demand-Generation-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Lead-Nurture-Sequence-&-Pipeline-Acceleration-Email-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Outbound-&-ABM/Intent-Signal-Orchestration-&-Buying-Signal-ABM-Activation-Engine.md`

## Integration Tips

- **Salesforce:** Create a Campaign for the event with child campaigns for each follow-up tactic. Use Campaign Member Status fields (Invited, Registered, Attended, Meeting Booked, Opportunity Created) to track progression. Build a Campaign Influence report to capture multi-touch attribution.
- **HubSpot:** Use the Events tool to sync attendees. Build enrollment workflows triggered by contact property "Event Tier = HOT/WARM/NURTURE." Use Campaign Attribution reporting with "First Touch + Last Touch" model.
- **Outreach/Salesloft:** Create tier-specific sequences with conditional steps. Use custom fields to pass event score and event name for personalization tokens. Set up trigger-based sequence enrollment from Salesforce campaign member status change.
- **Clay:** Use Clay to enrich the raw attendee CSV — pull company data, LinkedIn profiles, recent news/funding, and intent signals — then push scored leads back to Salesforce/HubSpot via API.
- **Zapier/Make:** Build a Zap that triggers on new campaign member (Salesforce) → enriches via Clearbit/Apollo → scores via a scoring spreadsheet → assigns task in Salesforce → sends Slack alert to AE.
- **Vidyard/Loom:** For Tier 1 leads, use AI-generated scripts from Deliverable 2 as the basis for a 60-second personalized video. Embed in the first AE email with a custom thumbnail showing the lead's company name.
- **Google Sheets:** Build the ROI tracking dashboard using the 15 KPIs from Deliverable 4. Use data imports from Salesforce/HubSpot via Coefficient or Supermetrics for automated daily refresh.
- **6sense/Bombora:** Pull segment data for attendees 1-2 weeks post-event. Leads who show sustained or increased intent scores after event are prime re-engagement candidates for Tier 3 nurture acceleration.

## Troubleshooting

**Problem:** Lead data from badge scans is incomplete — missing emails, titles, or company names.
**Solution:** Run the raw badge scan list through a Clay or Apollo enrichment workflow before scoring. Use LinkedIn URL or company name as the enrichment anchor. Accept that ~15% of leads may not be enrichable and default them to Tier 3 nurture with a manual review flag.

**Problem:** AEs aren't following up on Tier 1 leads within the 4-hour SLA.
**Solution:** Add a 4-hour escalation automation: if no CRM activity logged on a Tier 1 lead after 4 hours, send an automated Slack DM to the AE's manager. Also have the SDR team as a backup first-touch for all Tier 1 leads that aren't contacted within 6 hours.

**Problem:** Pipeline attribution is being double-counted between the event campaign and other active campaigns.
**Solution:** Establish a clear attribution hierarchy in your CRM: event source wins over other campaigns if the event touchpoint was within 14 days of opportunity creation. Use Salesforce Campaign Influence with a custom attribution model, or in HubSpot set the event campaign as the "Primary Campaign Source" on the contact record at the time of opportunity conversion.

## Version History
- v1.0: Initial creation (auto-generated)
