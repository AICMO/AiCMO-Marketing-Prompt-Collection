# AI-Powered B2B SaaS Webinar Audience Intelligence & Real-Time Engagement Scoring Pipeline Conversion Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** webinar-marketing, engagement-scoring, pipeline-conversion, lead-prioritization, b2b-saas, demand-generation, marketing-automation, hubspot, salesforce, revenue-intelligence

## Overview
Most webinar follow-up is a blunt instrument — every attendee gets the same thank-you email regardless of whether they asked three burning product questions or checked their email for 45 minutes. This prompt builds an AI-powered engagement intelligence layer that scores every attendee in real-time, routes the hottest prospects to SDRs within 60 minutes, triggers segmented nurture sequences by engagement tier, and feeds a closed-loop pipeline attribution model back into the webinar scoring algorithm. Use it when you want to convert your existing webinar audience into 2–4x more pipeline without running more webinars.

## Quick Copy-Paste Version

You are a senior B2B demand generation strategist who has built AI-powered webinar intelligence systems that convert 18–35% of live attendees into pipeline opportunities within 30 days.

Help me build a real-time engagement scoring and post-event pipeline conversion system for our webinars.

Our context:
- Product: [e.g., "Nexar — AI-powered revenue intelligence platform for enterprise sales teams, $75,000–$200,000 ACV"]
- ICP: [e.g., "VP Sales, CRO, and RevOps leaders at B2B SaaS companies with 100–1,000 sales reps"]
- Webinar platform: [e.g., "Zoom Webinars / ON24 / Goldcast / Demio"]
- CRM: [e.g., "Salesforce + HubSpot Marketing Hub"]
- Average webinar size: [e.g., "400–700 registrants, 38% show rate (180–270 live attendees)"]
- Current conversion: [e.g., "4% of attendees request a demo within 14 days — we believe this should be 12–18%"]
- Follow-up today: [e.g., "One generic 'thank you + replay' email to all attendees 24 hours after the webinar"]
- Sales team: [e.g., "12 SDRs, 18 AEs; SDRs currently receive a flat list of webinar attendees with no prioritization"]

Build me:

1. **ENGAGEMENT SIGNAL CAPTURE SYSTEM**
   - The 8 behavioral signals to capture during every webinar: poll responses (by option selected, not just participation), chat message sentiment and volume, Q&A submissions and vote patterns, CTA clicks, resource downloads, watch time by minute, replay behavior, and post-event survey responses
   - How to configure Zoom/ON24/Goldcast to export these signals automatically to HubSpot/Salesforce within 15 minutes of webinar end
   - The "hidden signals" most marketers miss: attendees who stay 5+ minutes past the scheduled end time (97th percentile buyer intent), attendees who re-watch specific segments in the replay, attendees who share the replay link internally

2. **AI ENGAGEMENT SCORING MODEL**
   - A weighted scoring framework: poll engagement (15 pts), Q&A submission (20 pts per question submitted), chat activity (10 pts for 3+ messages), CTA click (25 pts), resource download (20 pts), watch time >75% (15 pts), stayed post-event (30 pts), NPS survey completed (10 pts), replay re-watch >50% (25 pts)
   - Tier definitions: Tier 1 (85+ pts = "Hand Raiser"), Tier 2 (50–84 pts = "Warm Lead"), Tier 3 (20–49 pts = "Nurture"), Tier 4 (<20 pts = "Awareness Only")
   - How to build this scoring in HubSpot workflows or Salesforce Einstein without custom development
   - The ICP multiplier: how to adjust scores based on company size, title, and firmographic fit data from your CRM

3. **AUTOMATED PIPELINE CONVERSION SEQUENCES BY TIER**
   - Tier 1 "Hand Raiser" sequence: SDR alert within 60 minutes → personalized video prospecting email referencing their specific Q&A question → LinkedIn connection request within 4 hours → phone call within same business day → all with specific copy frameworks
   - Tier 2 "Warm Lead" 7-day sequence: personalized content email based on poll answers → case study relevant to their industry → demo offer with social proof → re-engagement with replay clip
   - Tier 3 "Nurture" 21-day sequence: replay link with chapter timestamps → related content based on webinar topic → upcoming webinar invitation → community/newsletter invitation
   - Tier 4 "Awareness Only" path: add to email newsletter → 60-day drip → invite to next webinar

4. **SDR PRIORITIZATION & HANDOFF PROTOCOL**
   - The SDR morning brief format: AI-generated list of Tier 1 leads ranked by score, with contextual notes ("Asked about enterprise security compliance during Q&A," "Downloaded pricing guide + stayed 12 minutes post-event")
   - Script frameworks for SDR outreach that directly reference specific webinar engagement signals
   - How to prevent SDR cherry-picking: round-robin assignment rules for Tier 1 with time-to-first-contact SLAs (60 minutes during business hours)
   - Escalation protocol: Tier 1 leads from target accounts get immediate AE review before SDR outreach

5. **CLOSED-LOOP ATTRIBUTION & MODEL OPTIMIZATION**
   - The pipeline attribution model: webinar-sourced (attended before any prior touch) vs. webinar-influenced (attended during active opportunity) — tracking both in Salesforce/HubSpot
   - Monthly scoring model audit: compare engagement scores at time of webinar → conversion to demo → conversion to opportunity → conversion to closed-won, identify which signals correlate highest with revenue
   - Quarterly score weight recalibration: how to adjust point values based on what your data shows actually predicts pipeline conversion at your company
   - The 12-month webinar program dashboard: cost per pipeline dollar by webinar type, engagement score distribution over time, tier conversion rates

Produce a complete, implementation-ready system I can deploy to my webinar platform, CRM, and SDR team within 30 days without a data science team.

## Advanced Customizable Version

ROLE: You are a principal-level B2B revenue marketing architect with deep expertise in webinar intelligence, behavioral scoring models, and CRM-integrated pipeline automation. You have built engagement scoring systems at companies like Gong, Drift, 6sense, and Clari that consistently convert 20–35% of live webinar attendees into pipeline-qualified opportunities within 21 days. You treat webinar data as a first-party intent signal comparable to pricing page visits — high-value, time-sensitive, and severely undermonetized by most marketing teams. You operate with the assumption that AI agents handle all scoring, sequencing, routing, and reporting — so the human marketer spends their time on strategy and message personalization, not spreadsheets.

---

COMPANY CONTEXT:

**Company & Product:**
- Company name + product: [e.g., "Nexar — AI-powered revenue intelligence and sales coaching platform, analyzing every sales call to identify coaching moments, deal risks, and competitive intelligence"]
- Product category: [e.g., "Revenue Intelligence / Conversational AI"]
- ICP: [e.g., "VP Sales, CRO, Chief Revenue Officer, and VP Revenue Operations at B2B SaaS companies with 50–500 sales reps and $20M–$200M in ARR"]
- ACV range: [e.g., "$75,000–$200,000; enterprise contracts at $300,000+"]
- Sales cycle: [e.g., "60–120 days; requires IT security review, RevOps evaluation, and CRO budget approval"]
- Current ARR: [e.g., "$42M growing 85% YoY"]

**Webinar Program State:**
- Webinar platform: [e.g., "ON24 for live + Wistia for replay hosting; Marketo for email sequences"]
- Webinar frequency: [e.g., "2 webinars/month: 1 thought leadership (500–800 registrants) + 1 product deep-dive (200–400 registrants)"]
- Average show rate: [e.g., "34% — 170–272 live attendees per thought leadership webinar"]
- Current follow-up: [e.g., "Single-segment email 24 hours post-webinar: replay link + top 3 takeaways; SDRs receive flat attendee list, no prioritization guidance"]
- Current demo conversion from webinar: [e.g., "3.8% of live attendees convert to demo request within 21 days"]
- Target demo conversion: [e.g., "15% of live attendees convert to demo request within 21 days"]

**Tech Stack:**
- CRM: [e.g., "Salesforce Sales Cloud + Marketing Cloud Account Engagement (Pardot)"]
- Marketing automation: [e.g., "Marketo Engage"]
- Data enrichment: [e.g., "Clearbit + Bombora intent data"]
- Sales engagement: [e.g., "Outreach.io for SDR sequences"]
- Scoring/analytics: [e.g., "MadKudu for predictive lead scoring + Looker for pipeline analytics"]

**Sales Team:**
- SDR team: [e.g., "16 SDRs organized by market segment: 8 Enterprise (500+ employees), 8 Mid-Market (50–500 employees)"]
- AE team: [e.g., "22 AEs; Enterprise AEs handle $150K+ deals, Mid-Market AEs handle $60K–$150K"]
- Current webinar-to-SDR handoff: [e.g., "CSV export every Friday morning; no real-time routing; no engagement context provided"]

---

OBJECTIVE:

Design and implement a fully automated, AI-powered Webinar Audience Intelligence and Engagement Scoring system that:
1. Captures all behavioral engagement signals during live webinars and replays
2. Scores and segments every attendee within 15 minutes of webinar end
3. Triggers segmented, personalized follow-up sequences by engagement tier and ICP firmographic profile
4. Routes Tier 1 leads to SDRs within 60 minutes with full engagement context
5. Feeds closed-loop pipeline attribution data back into the scoring model for continuous improvement
6. Requires zero manual data processing by the marketing team

---

DELIVERABLE 1: BEHAVIORAL SIGNAL CAPTURE ARCHITECTURE

**Live Webinar Signal Matrix (build a complete table):**

| Signal Category | Specific Signal | Data Source | Export Method | Timing |
|----------------|----------------|-------------|---------------|--------|
| Attendance | Joined + time-to-join, duration, drop-off minute | ON24/Zoom API | Webhook → Marketo | Real-time |
| Active participation | Poll responses (with option selected) | ON24 Polls | API push | Per poll completion |
| Question intent | Q&A submission text, upvotes received | ON24 Q&A | API export | Post-webinar |
| Content interest | Resource/CTA clicks (which specific resource) | ON24 CTAs | API push | Real-time |
| Post-event behavior | Replay watch %, chapters re-watched, share events | Wistia | Webhook → Marketo | Per session |
| Survey intent | NPS score, "ready to speak with sales?" response | Typeform | Zapier → Salesforce | Post-survey |

For each signal: exact API/webhook configuration for ON24 + Marketo, field mapping to Salesforce Contact/Lead record, and the data retention policy.

**The "Invisible Intent" Layer:**
- How to detect attendees who forward the replay link to colleagues (email tracking pixels + UTM parameters with contact ID)
- How to identify when an attendee's colleague from the same account registers for the next webinar (account-level engagement scoring)
- How to capture and score post-webinar social activity (LinkedIn post shares, comment mentions of your company in the 48 hours post-event)

---

DELIVERABLE 2: ENGAGEMENT SCORING MODEL

**Base Score Architecture:**

Design a 0–200 point scoring system across three dimensions:

**Dimension 1: Depth of Engagement (0–100 points)**
- Build the complete signal-to-point mapping table with rationale for each weight
- Include diminishing returns logic: Q&A submission = 25 pts for first question, 10 pts for each additional (prevents gaming)
- Watch-time curve: 0–25% = 0 pts, 26–50% = 5 pts, 51–75% = 15 pts, 76–100% = 25 pts, stayed post-event = +15 bonus pts

**Dimension 2: Commercial Intent Signals (0–60 points)**
- Pricing/ROI resource download: 30 pts
- Pricing-related Q&A submission: 25 pts
- CTA click to demo/trial page: 40 pts
- "Ready to talk to sales" survey response: 60 pts (cap tier at Tier 1 regardless of base score)
- Poll response indicating active evaluation: 20 pts (e.g., "We're evaluating solutions now" vs. "Researching for future")

**Dimension 3: ICP Fit Multiplier (0.5x–2.0x)**
- Perfect ICP fit (title + company size + industry all match): 2.0x multiplier
- Strong ICP fit (2 of 3 match): 1.5x multiplier
- Partial ICP fit (1 of 3 matches): 1.0x multiplier
- Outside ICP: 0.5x multiplier (still score, but deprioritize)

**Tier Definitions & Routing Rules:**
- Tier 1 "Buyer Signal" (120+ adjusted pts): SDR personal outreach within 60 minutes; AE review within 4 hours
- Tier 2 "High Intent" (80–119 adjusted pts): Personalized 7-day email sequence; SDR outreach on day 3 if no response
- Tier 3 "Warm Interest" (40–79 adjusted pts): 21-day educational nurture; re-invitation to next webinar
- Tier 4 "Audience Building" (<40 adjusted pts): Newsletter enrollment; long-cycle nurture

---

DELIVERABLE 3: SEGMENTED FOLLOW-UP SEQUENCE LIBRARY

For each of the 4 tiers, produce complete sequence assets:

**Tier 1 Sequence (Days 0–5):**
- **Day 0, Hour 0–1:** SDR alert email (format: subject line, body copy, engagement context summary, recommended talking points based on their Q&A question or poll response)
- **Day 0, Hour 1–4:** Automated personalized email from SDR referencing specific engagement signal — write 3 variants: (a) Q&A submitter, (b) CTA clicker, (c) Post-event stayer
- **Day 0, LinkedIn:** Connection request message template (150 characters max, references webinar)
- **Day 1:** SDR phone call voicemail script (30 seconds) + email follow-up if no answer
- **Day 3:** If no response — second personalized email with case study specific to their industry + soft demo CTA
- **Day 5:** "Break-up" email with low-friction alternative CTA (e.g., "30-minute industry benchmarking call" or "access the webinar benchmark data")

**Tier 2 Sequence (Days 0–21):**
- Complete 6-touch email sequence with subject lines, body copy, and CTAs
- Day 0: Personalized recap email with 3 key takeaways relevant to their specific poll answer
- Day 2: Case study from a company in their industry/segment
- Day 5: Replay chapter link (specific 8-minute segment most relevant to their engagement signals)
- Day 9: "Ask the expert" invitation for informal Q&A with the webinar speaker
- Day 14: ROI calculator or benchmark report offer
- Day 21: Final invitation to upcoming related webinar

**Tier 3 Sequence (Days 0–45):**
- Full replay email with chapter timestamps and "skip to what matters to you" UX copy
- Educational content series (3 emails): industry trend article, framework guide, competitive landscape overview
- Upcoming webinar invitation (Day 21)
- Community/newsletter subscription invitation (Day 30)
- Pause-and-check-in (Day 45): "Still relevant? Pick the topic you care most about" preference center link

**Tier 4 Path:**
- Single replay email with clear newsletter opt-in CTA
- Added to general company newsletter list
- 90-day re-invitation to next webinar of the same topic area

---

DELIVERABLE 4: SDR ENABLEMENT SYSTEM

**The SDR Morning Intelligence Brief (produce the exact template):**
- Format: Slack message + Outreach.io task queue auto-populated within 2 hours of webinar end
- For each Tier 1 lead: Name | Company | Title | Score | Top Signals | Recommended Opening | Outreach Priority (1–5)
- Example entry format: "Sarah Chen | DataForce (850 employees, SaaS, Series C) | VP Sales | Score: 156 | Signals: Asked 'How does Nexar handle multi-product team segmentation?' + stayed 18 min post-event + downloaded pricing guide | Opening: 'Your question about multi-product segmentation was the one we got most during Q&A — I have 3 customer examples for how they solved it' | Priority: 1"

**SDR Call Script Framework (produce complete scripts):**
- Opening framework: reference specific behavior (not generic "thanks for attending"), demonstrate you know what they cared about
- Discovery bridge: use their Q&A question or poll response as the entry to a discovery question
- Next step language: calendar booking language that converts 40%+ of conversations

**Outreach.io Sequence Configuration:**
- Step-by-step configuration for creating Tier 1 and Tier 2 sequences in Outreach.io
- Dynamic personalization fields to pull from Salesforce (engagement signals, company data, webinar-specific context)
- SLA enforcement: how to configure Outreach reminders and manager escalations for Tier 1 leads without first contact in 90 minutes

---

DELIVERABLE 5: CLOSED-LOOP ATTRIBUTION & OPTIMIZATION ENGINE

**Salesforce Campaign Hierarchy (design the complete structure):**
- Parent campaign: "[Year] Webinar Program"
- Child campaigns per webinar: "[Date] [Webinar Title]" with member statuses: Registered | Attended Live | Partial Attend | Registered No-Show | Replay Only
- Campaign influence model: First Touch, Last Touch, and Linear (weight each by sales cycle stage)
- How to track: Webinar-sourced pipeline (webinar was first marketing touch) vs. webinar-influenced pipeline (webinar touched an existing opportunity)

**The 30-Day Post-Webinar Analytics Review (produce the template):**

| Metric | This Webinar | Program Average | Target | Trend |
|--------|-------------|-----------------|--------|-------|
| Registrants | | | | |
| Show rate % | | | 40%+ | |
| Avg engagement score | | | | |
| Tier 1 (Hand Raisers) count | | | | |
| Tier 1 → demo conversion % | | | 60%+ | |
| Tier 2 → demo conversion % | | | 25%+ | |
| Pipeline sourced ($) | | | | |
| Pipeline influenced ($) | | | | |
| Cost per pipeline dollar | | | <$0.15 | |
| SDR avg time-to-first-contact (T1) | | | <60 min | |

**Quarterly Score Weight Recalibration Protocol:**
- Pull 90-day cohort: all attendees scored → which tier → demo → opportunity → closed-won
- Calculate correlation coefficient for each scoring signal against closed-won revenue
- Recommended statistical threshold for signal weight adjustment: >15% correlation shift triggers recalibration
- How to A/B test new scoring weights without disrupting active SDR sequences

**The Annual Webinar Program ROI Model:**
- Total program cost calculation: platform fees + team time + production + promotion spend
- Total pipeline attribution: sourced + influenced (at weighted partial credit)
- ROI formula: (Pipeline Closed-Won from webinar attribution × Average Win Rate) / Total Program Cost
- Benchmark: Target 8x–15x pipeline sourced ROI; 25x–40x on influenced pipeline at average B2B SaaS win rates

---

DELIVERABLE 6: IMPLEMENTATION ROADMAP

Provide a phased 90-day implementation plan:

**Phase 1 (Days 1–14): Signal Infrastructure**
- Configure ON24/Zoom webhooks to push engagement data to Marketo/HubSpot
- Build Salesforce custom fields for engagement score components and webinar tier
- Set up Zapier/native integration to sync survey responses
- Test with a shadow run on next scheduled webinar (score but don't act on data yet)

**Phase 2 (Days 15–30): Scoring & Routing Activation**
- Deploy scoring model in Marketo/HubSpot scoring system
- Build Salesforce assignment rules for Tier 1 routing
- Create Outreach.io sequences for each tier
- Train SDR team: 90-minute enablement session on new intelligence brief format and script frameworks

**Phase 3 (Days 31–60): Sequence Optimization**
- Run first two webinars on full system; track conversion metrics weekly
- A/B test Tier 1 email subject lines (benchmark: 45%+ open rate)
- Calibrate scoring weights based on early engagement → demo conversion data
- Add ICP firmographic multiplier using Clearbit data enrichment

**Phase 4 (Days 61–90): Attribution & Optimization Loop**
- Build Salesforce campaign hierarchy with influence model
- Create 30-day post-webinar review dashboard in Looker/Tableau
- Run first quarterly score weight audit
- Present webinar program ROI to CMO with full attribution model

Produce this as a complete implementation guide my demand generation team can execute without outside consulting support.

## Example Input/Output

**Input Example:**

Company: DataPilot — AI-powered data observability platform for data engineering teams
ICP: Head of Data Engineering, VP Data, Chief Data Officer at companies with 50–500-person data teams
ACV: $48,000–$180,000
Webinar platform: Zoom Webinars + Wistia replay
CRM: HubSpot Professional + Salesforce Sales Cloud
Recent webinar: "The 2025 State of Data Reliability: What 500 Data Engineers Told Us"
Registrants: 680 | Live attendees: 228 (33.5% show rate) | Current 14-day demo conversion: 4.4% (10 demos from 228 attendees)

**Output Example (Abbreviated):**

**Engagement Score Distribution from Webinar:**
- Tier 1 (Hand Raisers, 120+ pts): 18 attendees (7.9%)
- Tier 2 (High Intent, 80–119 pts): 41 attendees (18.0%)
- Tier 3 (Warm Interest, 40–79 pts): 76 attendees (33.3%)
- Tier 4 (Awareness Only, <40 pts): 93 attendees (40.8%)

**Projected Conversion at Industry Benchmarks:**
- Tier 1: 18 × 65% demo conversion = 11.7 demos → ~3–4 opportunities
- Tier 2: 41 × 28% demo conversion = 11.5 demos → ~3 opportunities
- Tier 3: 76 × 8% demo conversion = 6.1 demos → ~1–2 opportunities
- Tier 4: 93 × 2% demo conversion = 1.9 demos (long cycle)
- **Total projected: 31 demos vs. current 10 — a 3.1x improvement**

**Sample SDR Brief Entry:**
> **Priya Mehta | StreamCore Data (220 employees, fintech) | Head of Data Engineering | Score: 164**
> Signals: Asked "How does DataPilot handle schema drift in real-time streaming pipelines?" (voted #1 question by audience) + clicked the "ROI Calculator" CTA + stayed 22 minutes post-event
> Opening: "Priya — I noticed your question about schema drift in streaming pipelines was the one the audience wanted answered most. I have 3 fintech customers who solved this exact problem — can I show you how they did it in 20 minutes?"
> Outreach Priority: 1 | Call by: 3:00 PM today

**Tier 1 Day-0 Email (Subject: The answer to your schema drift question)**

> Hi Priya,
>
> Your question about schema drift in real-time streaming pipelines was voted the #1 question by the audience during today's webinar — which tells me you're not the only one wrestling with this.
>
> I have 3 case studies from fintech data teams who solved this at scale (one at a company very similar to StreamCore). I'd rather walk you through their exact setup than send you a deck.
>
> Are you free for 20 minutes this week? Here's my calendar: [link]
>
> Either way, I'm pulling together the schema drift deep-dive recording for the 8 people who asked follow-up questions — I'll send it over tomorrow.
>
> — [SDR Name]

## Success Metrics

**System Performance Metrics (review weekly):**
- Tier 1 lead count per webinar: target 6–10% of live attendees
- SDR time-to-first-contact on Tier 1: target <60 minutes during business hours (track in Salesforce)
- Tier 1 → demo conversion rate: target 55–70% (vs. industry average 20–25% for undifferentiated outreach)
- Tier 2 → demo conversion rate: target 20–30% within 21-day sequence
- Overall webinar → demo rate: target 12–18% of live attendees (vs. typical 3–5%)

**Pipeline Quality Metrics (review monthly):**
- Webinar-sourced pipeline per webinar: target 3–6x webinar program cost per event
- Average deal size from webinar leads vs. other channels: webinar-sourced deals typically run 15–25% larger ACV due to higher intent and pre-education
- Win rate on webinar-sourced opportunities: target >35% (vs. typical 20–28% for inbound leads)
- Time-to-close on Tier 1 webinar leads: should be 15–20% faster than average sales cycle

**Program Health Metrics (review quarterly):**
- Score weight calibration accuracy: correlation between scores and closed-won should increase each quarter
- ICP hit rate among Tier 1: target >85% of Tier 1 leads should be within ICP parameters
- Sequence engagement rates: Tier 1 emails target 55%+ open, 18%+ click; Tier 2 target 40%+ open, 12%+ click

## Related Prompts

- [AI-Powered B2B SaaS Webinar Marketing Program Architecture & Demand Generation Pipeline Revenue Intelligence Engine](./AI-Powered-B2B-SaaS-Webinar-Marketing-Program-Architecture-&-Demand-Generation-Pipeline-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Joint Webinar Co-Marketing & Partner Co-Production Pipeline Revenue Intelligence Engine](./AI-Powered-B2B-SaaS-Joint-Webinar-Co-Marketing-&-Partner-Co-Production-Pipeline-Revenue-Intelligence-Engine.md)
- [AI-Powered ABM Buying Committee Engagement Scoring & Multi-Stakeholder Deal Velocity Intelligence Engine](../../05_Analytics-&-Performance/Account-Based-Marketing-Analytics/AI-Powered-ABM-Buying-Committee-Engagement-Scoring-&-Multi-Stakeholder-Deal-Velocity-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Demo Request Conversion Architecture & Pipeline Qualification Velocity Intelligence Engine](../Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Demo-Request-Conversion-Architecture-&-Pipeline-Qualification-Velocity-Intelligence-Engine.md)

## Integration Tips

**HubSpot Integration:**
- Use HubSpot's native Zoom Webinars integration (Settings > Integrations > Zoom) to auto-sync attendee data including duration and registration status — no Zapier required for basic data
- Build scoring in HubSpot using "Score" contact property: create workflows triggered by webinar attendance custom properties, adding points for each behavioral signal
- Use HubSpot Lists to auto-segment attendees by tier within 30 minutes of webinar end, then enroll in corresponding sequences
- HubSpot Sequences can reference custom contact properties (engagement score, top signal, Q&A question text) for dynamic personalization

**Salesforce Integration:**
- Create a custom object "Webinar Engagement" with fields: Webinar Name, Engagement Score, Tier, Top Signal, Q&A Text, SDR Assignment Date, First Contact Date — link to Contact via lookup relationship
- Use Process Builder or Flow to auto-create Outreach tasks for Tier 1 leads with personalization tokens populated from the custom object
- Campaign hierarchy: Campaign → Campaign Member → Campaign Member Status (Registered | Attended | Tier 1 | Tier 2 etc.) enables proper attribution in opportunity influence reports
- Use Salesforce Einstein Lead Scoring alongside your webinar scores — Einstein score × webinar tier = combined priority rank

**ON24 Integration:**
- ON24's Audience Engagement Scoring (AES) provides native engagement scoring — use it as a baseline and layer your ICP multiplier on top in Salesforce/HubSpot
- Enable ON24 webhooks (Platform Configuration > Webhooks) to push real-time data to HubSpot or Salesforce via Zapier or direct API
- ON24 Intelligent Engagement Platform (IEP) can trigger in-webinar CTAs based on engagement score thresholds — e.g., a "schedule a demo" overlay appears only to attendees who exceed 80 points during the live event

**Outreach.io / Salesloft Integration:**
- Import Tier 1 leads via Salesforce task auto-creation (assign task to SDR owner with "Priority: Urgent" + custom fields for engagement context)
- Build Outreach sequences with custom variables mapped from Salesforce engagement object: {{engagement_top_signal}}, {{qa_question_text}}, {{webinar_poll_response}} — enables true 1:1 personalization at scale
- Set sequence SLA enforcement: Outreach "governance" feature can pause sequences and alert managers if Tier 1 leads are not contacted within the 60-minute SLA

**Zapier Automation Flows:**
- Trigger: "ON24 Webinar Ends" → Action: "Export All Attendee Data" → Action: "Create/Update HubSpot Contact" → Action: "Update Engagement Score Property" → Action: "Enroll in Appropriate Sequence" (all within 15 minutes)
- Trigger: "Wistia Video Reaches 50% Watch" → Action: "Update HubSpot Contact Score (+25 pts)" → Action: "Check Tier; if now Tier 1, create Outreach task"
- Trigger: "Typeform Survey Submitted with 'Ready for Sales' = Yes" → Action: "Immediately create Salesforce Lead with Priority: Urgent" → Action: "Slack DM to SDR manager"

## Troubleshooting

**Problem: ON24/Zoom data arrives in CRM 2–6 hours after webinar, making 60-minute SDR SLA impossible.**
Solution: Switch from batch export (which most default integrations use) to real-time webhooks. In ON24, enable "Attendee Activity" webhooks that push data as each event occurs (poll response, CTA click, etc.) rather than waiting for a post-event export. For Zoom, use the Zoom Events webhook for real-time push. For HubSpot, enable "Workflow enrollment via webhook trigger" so scoring happens the moment each signal arrives, not after the full export.

**Problem: SDRs are ignoring the engagement scores and reaching out to the "familiar names" on their target account lists regardless of tier.**
Solution: Remove the flat attendee list entirely from SDR access — instead, replace with the prioritized Outreach.io task queue that only shows name, company, score, and recommended opening. If SDRs can't see the full list, they can't cherry-pick. Additionally, tie SDR performance metrics to Tier 1 time-to-first-contact rate (measured in Salesforce) rather than just total demos booked — this aligns incentives with the scoring system's purpose.

**Problem: Engagement scores for most attendees are consistently low (<40 points), leaving few Tier 1 and Tier 2 leads.**
Solution: Low scores usually mean low webinar engagement, not a broken scoring system. Audit the webinar format: are you using polls? (Industry average webinars use 0–1 polls; high-performing programs use 3–4). Is Q&A enabled and actively promoted during the event? Is there a mid-webinar CTA or resource offer that creates click opportunities? Redesign the webinar format to include at least 3 polls, 2 CTA opportunities, and an explicit "submit your questions now" prompt. As a short-term fix, temporarily lower the Tier 1 threshold to 80 points while calibrating the webinar format, then raise it back once engagement signal volume increases.

## Version History
- v1.0: Initial creation (auto-generated)
