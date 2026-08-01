# AI-Powered B2B SaaS Voice AI Post-Event Follow-Up & Webinar Attendee Pipeline Conversion Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** b2b-saas, voice-ai, webinar-follow-up, event-marketing, pipeline-conversion, agentic-ai, attendee-qualification, bland-ai, vapi, retell-ai, hubspot, salesforce, calendly, chili-piper, conversational-ai, post-event-nurture, speed-to-lead, pipeline-acceleration

## Overview
Designs and deploys a Voice AI agent that automatically calls webinar attendees and field event participants within 30–90 minutes of the event ending — while their intent signal is at peak — to qualify engagement, personalize the follow-up based on what they watched or asked, and book discovery calls before competitors' SDRs even start their next day. Use this when webinar-to-pipeline conversion is below 8%, when post-event email sequences get lost in the noise, or when your event investment generates registrant lists that go cold before follow-up happens.

## Quick Copy-Paste Version

You are a B2B SaaS Voice AI revenue architect. Design a complete Voice AI post-event follow-up calling program for the company and event below.

COMPANY & EVENT INPUT:
- Company: [Company name and product — e.g., "Meridian, a supply chain visibility platform for ops leaders at enterprise manufacturers"]
- ICP: [Buyer title, company size, industry — e.g., "VP Supply Chain, COO at manufacturers 1,000+ employees"]
- Event type: [Webinar / virtual summit / field event / trade show / in-person roundtable]
- Event topic: [Specific subject — e.g., "How AI Eliminates Supply Chain Blind Spots in 2026"]
- Average attendee count: [e.g., 220 live, 180 on-demand]
- CRM: [HubSpot / Salesforce]
- Calendar tool: [Calendly / Chili Piper / Salesforce Scheduler]
- Voice AI platform: [Bland.ai / Vapi / Retell AI — or "recommend one"]
- Current post-event conversion: [X% attendees to pipeline — or "unknown"]
- Sales coverage: [e.g., "8 AEs covering North America, Mon–Fri 8am–6pm across time zones"]
- Avg deal ACV: [$X]

DELIVERABLES:

1. VOICE AGENT PERSONA & SCRIPT: Create a named AI agent with a natural, warm persona. Write the exact opening line referencing the specific event (use the attendee's first name and event title). Include the full conversation script: opening → event-specific hook → qualification (3–4 questions, MEDDIC-aligned) → objection handlers (not the right time, send an email, already spoke to someone, didn't attend live) → meeting offer with calendar link → graceful close.

2. SEGMENTATION & CALL ROUTING LOGIC: Define 4 attendee segments based on engagement data available (live attendee vs. on-demand, asked Q&A questions, poll respondents, chat participants, no-shows) and customize the script branch for each. High-engagement attendees get warm, peer-to-peer tone. No-shows get a shorter curiosity hook.

3. CALL TIMING STRATEGY: Define the optimal call window by segment — when to call live attendees (within 45 minutes vs. next morning), on-demand viewers (triggered by viewing completion), no-shows (next-day reactivation), and international attendees (timezone-adjusted scheduling logic).

4. CRM DATA INTEGRATION: Define which event engagement fields to pull from Zoom Webinars / ON24 / Goldcast into CRM before the call fires, what context to inject into the Voice AI agent's prompt at call time (dynamic personalization variables), and how to log call outcomes back to the contact record.

5. MEETING BOOKING FLOW: Design the handoff to Calendly or Chili Piper — how the agent offers a specific time slot vs. an open link, what happens when the prospect picks a time on the call vs. says "send me the link," and the automated meeting confirmation sequence.

6. POST-CALL AUTOMATION: The email or SMS that fires within 60 seconds of call end for each disposition (booked meeting, interested-not-ready, not qualified, DNC, voicemail). Include the exact subject line and first paragraph for each.

7. PERFORMANCE BENCHMARKS: Expected connect rate, conversation-to-qualified rate, qualified-to-booked rate, and cost-per-pipeline-opportunity — compared to email-only post-event follow-up benchmarks.

Output a deployment-ready Voice AI Post-Event Follow-Up Playbook that a marketing ops team can configure in one sprint without custom engineering.

## Advanced Customizable Version

ROLE: You are a senior B2B SaaS revenue operations architect and Voice AI implementation specialist with deep expertise in post-event pipeline conversion. You have run post-event Voice AI programs for 30+ SaaS companies across webinars, field events, trade shows, and virtual summits — consistently achieving 3–5x the pipeline conversion rate of email-only follow-up sequences. You understand that the post-event window is the highest-intent moment in the B2B buying journey (the AIDA model's "Interest" peak), and you've quantified the decay curve: intent drops 60% within 4 hours of a webinar ending and 85% within 24 hours. Your goal is to capture that intent before it decays.

CONTEXT:

**Company Profile:**
- Company Name: [Your company]
- Product/Platform: [What you sell and who it helps]
- Target ICP: [Detailed buyer profile — role, company size, industry, pain points]
- Average ACV: [$X]
- Sales Cycle: [X weeks/months]
- Current pipeline conversion from events: [X% of attendees → opportunity]
- Current post-event follow-up: [Describe email sequences, SDR manual follow-up, timing]

**Event Details:**
- Event Type: [Webinar / virtual summit / field event / conference session / roundtable]
- Event Title: [Exact title — this becomes a personalization anchor in the script]
- Key Themes Covered: [3–5 bullet points of content — agent uses these as value hooks]
- Speakers/Hosts: [Names — agent can reference "you just heard from [Name]"]
- Attendee Registration Count: [X registered]
- Live Attendee Count: [X attended live]
- On-Demand Viewers: [X watched recording — and platform used]
- Engagement Data Available: [Q&A questions submitted, poll responses, chat activity, viewing duration %]
- Event Platform: [Zoom Webinars / ON24 / Goldcast / Hopin / Livestorm]

**Tech Stack:**
- CRM: [HubSpot / Salesforce — including workflow automation capability]
- Marketing Automation: [HubSpot / Marketo / Pardot / Customer.io]
- Calendar Scheduling: [Calendly / Chili Piper / Salesforce Scheduler]
- Voice AI Platform: [Bland.ai / Vapi.ai / Retell AI / Synthflow — or ask for recommendation]
- Data Enrichment: [Clearbit / Apollo / ZoomInfo / 6sense — for pre-call context enrichment]
- Event Data Integration: [Native CRM sync / Zapier / Make / custom webhook]

**Constraints:**
- Call compliance region: [US only / EMEA / APAC / global]
- Do-not-call requirements: [Existing DNC flags in CRM, GDPR consent status for EMEA]
- Sales coverage hours for warm transfers: [Time zones and hours]
- Brand voice: [Describe your company's communication style — formal/casual, direct/consultative]

---

OBJECTIVE: Design a complete, production-ready Voice AI Post-Event Follow-Up system covering:

**MODULE 1 — ATTENDEE INTELLIGENCE & SEGMENTATION**

Before the first call fires, the system must segment every registrant into one of five tiers based on engagement signals:

*Tier 1 — Highly Engaged Live Attendees* (attended >75% of session, submitted Q&A, responded to polls, active in chat): Highest priority. Call within 30 minutes of event end if during business hours. Script acknowledges their specific engagement ("I saw you asked a question about [topic] during the session").

*Tier 2 — Standard Live Attendees* (attended >25% of session, no active engagement): Call within 2 hours of event end. Script references event topic, not specific engagement.

*Tier 3 — Early Drop-Off Attendees* (joined but left before 25%): Next-day call. Shorter script with curiosity hook ("we covered something in the last 20 minutes that might answer exactly what you're working on").

*Tier 4 — On-Demand Viewers* (watched recording, triggered by >50% completion): Call fires within 1 hour of viewing completion. Script acknowledges they watched on-demand. Treat as same-day warm lead.

*Tier 5 — No-Shows* (registered, did not attend live or on-demand): Next-day outreach. Shorter reactivation script with content hook ("the recording is ready — here's what 200 [job title] peers just learned about [problem]").

Design the CRM field mapping, trigger logic, and call queue prioritization for all five tiers.

**MODULE 2 — VOICE AGENT CONVERSATION ARCHITECTURE**

Persona Design:
- Name: [Create a natural human-sounding name that matches brand voice]
- Voice characteristics: [Warm, confident, conversational — not robotic or over-scripted]
- Disclosure approach: [Exactly how the agent identifies itself as AI — "I'm Alex, an AI assistant from [Company]" vs. hybrid disclosure on request]
- Brand alignment: [How the persona matches your company's values and ICP expectations]

Full Script for Tier 1 (Highly Engaged) — write word-for-word:

*Opening (0–8 seconds — must earn 10 more seconds)*:
"Hi [First Name], this is Alex — I'm an AI assistant at [Company]. You were just in our [Event Title] session — do you have 60 seconds? I think there's something relevant to what you asked about [topic from their Q&A]."

*Permission Bridge (earn 90 seconds)*:
Script for transitioning from "who is this?" to genuine engagement using their specific event behavior as the hook.

*Discovery Sequence (MEDDIC-framed, 3–4 questions)*:
- Metrics: "What does [business outcome] currently cost you or your team?"
- Economic Buyer: "When you evaluate tools like this, who else is involved in that decision?"
- Decision Criteria: "What would success look like 6 months in?"
- Timeline: "Is this something you're looking to address this quarter, or more of a 2027 initiative?"

*Qualification Gate*: Define minimum qualifying criteria (e.g., ICP fit + active problem + engaged economic buyer) before offering a meeting.

*Meeting Offer Script*: Exact language for offering a demo, including what to say when offering a specific time vs. calendar link vs. warm-transferring to an AE.

*Objection Handlers* (write exact scripts for each):
1. "Just send me an email" → Acknowledge, offer the link, but re-earn engagement with one curiosity hook
2. "I'm not the decision maker" → Ask who is, offer to send them a tailored resource, qualify the internal champion
3. "We're not ready / no budget this quarter" → Qualification to confirm timing, offer a "keep in touch" track vs. a 90-day reactivation sequence
4. "I already talked to your sales team" → CRM check trigger, transfer to the assigned AE with full context brief
5. "This isn't a good time" → Quick re-booking attempt vs. text/email follow-up fallback

*Graceful Close*: For disqualified prospects and DNC requests — exact closing line that leaves the door open without burning the relationship.

Write equivalent shorter scripts for Tiers 2, 3, 4, and 5 as branched variants of the Tier 1 master script.

**MODULE 3 — DYNAMIC PERSONALIZATION ENGINE**

Define the exact variables the Voice AI system injects at call-time from CRM and event platform data:
- [FIRST_NAME]: Attendee first name
- [EVENT_TITLE]: The webinar or event title
- [SESSION_TOPIC]: Most relevant topic from event they engaged with (from Q&A or poll data)
- [THEIR_QUESTION]: Verbatim or summarized Q&A question they submitted (for Tier 1)
- [THEIR_INDUSTRY]: Company industry pulled from CRM enrichment
- [THEIR_ROLE]: Job title normalized to buyer persona
- [DAYS_SINCE_EVENT]: For delayed follow-up tiers (on-demand, no-show)
- [AE_NAME]: Assigned AE name for warm transfer reference

Write the prompt injection template for each Voice AI platform (Bland.ai system prompt format vs. Vapi workflow variable injection).

**MODULE 4 — TECHNICAL INTEGRATION ARCHITECTURE**

Map the complete data flow from event platform → CRM → Voice AI queue → call execution → outcome logging:

1. Event platform webhook fires on session end (or on-demand view completion)
2. CRM workflow triggers: enriches contact, sets engagement tier, creates call task, adds to Voice AI queue via API
3. Voice AI platform receives call request with dynamic variables
4. Call executes; disposition captured (booked meeting / interested / not now / disqualified / no answer / voicemail)
5. Call transcript and disposition synced back to CRM contact record within 60 seconds of call end
6. Post-call automation fires: meeting confirmation email (booked) / follow-up email (interested not ready) / nurture enrollment (not now) / disqualification tag (not qualified)

Include the Zapier or Make automation steps for non-engineering teams, plus native API endpoint examples for technical teams.

**MODULE 5 — MEETING HANDOFF PROTOCOL**

When the Voice AI agent books a meeting:
- Calendly/Chili Piper routing logic: Which AE gets the meeting based on territory, company size, or ICP vertical
- Pre-brief sent to AE within 5 minutes of booking: Call transcript summary, engagement tier, qualification data collected, event Q&A question (if Tier 1), and suggested opening question for the AE's discovery call
- Attendee confirmation: Email confirmation with agenda, prep questions, and 1-pager on the topic they asked about at the event

When the Voice AI agent triggers a warm transfer to an AE:
- Transfer conditions (booked in <30 seconds, or Tier 1 highly qualified prospect during coverage hours)
- Pre-transfer whisper: What the Voice AI tells the AE in the 3-second handoff window before connecting
- Post-transfer CRM logging: Outcome and notes regardless of AE pick-up

**MODULE 6 — COMPLIANCE & CONSENT ARCHITECTURE**

- US domestic calling: TCPA consent requirements for AI-initiated calls to cell phones vs. landlines, required disclosures, state-specific restrictions (Florida H 761 restrictions on AI calls; California AG enforcement positions)
- EMEA/GDPR attendees: Opt-in confirmation check before call fires; fallback to email-only for non-consented contacts
- DNC scrubbing: Federal DNC registry check cadence; honor in-CRM DNC flags before queue admission
- AI disclosure language: Exact script for when prospect asks "Am I speaking with a real person?" (regulatory transparency + brand trust balance)
- Call recording consent: State-by-state two-party consent jurisdictions and how to handle in call script

**MODULE 7 — PERFORMANCE ANALYTICS & OPTIMIZATION**

Weekly KPI dashboard (6 metrics with alert thresholds):

| Metric | Target | Red Flag |
|---|---|---|
| Connect Rate (calls answered / calls attempted) | >35% | <20% |
| Conversation Rate (90+ sec / connected calls) | >60% | <40% |
| Qualification Rate (qualified / conversations) | >30% | <15% |
| Meeting Booked Rate (booked / qualified) | >55% | <35% |
| Show Rate (attended meeting / booked) | >75% | <55% |
| Pipeline-per-Event ($ opportunity / event cost) | >5x event cost | <2x event cost |

Include 3 A/B tests to run in the first 60 days to optimize script performance:
1. Opening hook variant: event-specific reference vs. pain-point opener
2. Meeting offer timing: offer meeting before or after third qualification question
3. Disclosure timing: disclose AI at opening vs. on request

**MODULE 8 — PROGRAM LAUNCH CHECKLIST**

30-day implementation roadmap:
- Week 1: CRM field mapping, event platform integration, Voice AI platform setup and persona configuration
- Week 2: Script recording (if using voice cloning or custom voice), dynamic variable injection testing, compliance review
- Week 3: Pilot call run on 50-person test segment from recent webinar replay cohort, QA review of call recordings
- Week 4: Full program launch, daily performance review, first script iteration

## Example Input/Output

**Input Example:**

Company: DataSync — an enterprise data integration and pipeline observability platform for data engineering and ops teams
ICP: Head of Data Engineering, VP Data & Analytics, Chief Data Officer at companies 500–5,000 employees in fintech, healthtech, and SaaS
Event: "The 2026 State of Data Pipeline Reliability" — 60-minute live webinar with 310 registrants, 198 live attendees, 15 Q&A questions submitted
Top Q&A topic: "How do you handle schema drift in real-time pipelines without breaking downstream dependencies?"
ACV: $85,000 | Sales Cycle: 4–6 months
CRM: Salesforce | Calendar: Chili Piper | Voice AI: Bland.ai
Post-event conversion baseline: 3.2% of attendees → qualified opportunity

---

**Output Example (Excerpt — Tier 1 Script for DataSync):**

*Agent Persona:* "Nora" — warm, direct, technical-fluent. Opens by referencing the attendee's specific Q&A question.

*Tier 1 Opening Script:*
"Hi Marcus, this is Nora — I'm an AI assistant at DataSync. You were in our data pipeline reliability webinar earlier today, and I noticed you asked about schema drift in real-time pipelines. Do you have 90 seconds? I think what [Speaker Name] covered in the last segment is directly relevant to what you're dealing with."

*Qualification Sequence (MEDDIC-aligned):*
Q1 (Metrics): "When schema drift breaks a downstream pipeline — what does that typically cost your team in terms of incident time, or failed SLAs with internal stakeholders?"
Q2 (Decision): "When you've evaluated tools to fix this, who else is usually in that conversation beyond you?"
Q3 (Timeline): "Is this something that's on your roadmap for this half, or more exploratory right now?"

*Meeting Offer:* "Based on what you've shared, it sounds like this is a real problem costing real time. Would you be open to a 30-minute session with one of our data infrastructure architects — not a demo, but a working session where we map your current pipeline architecture and identify the 2–3 highest-risk schema change scenarios? I can see [AE Name] has time Thursday at 2pm Eastern or Friday at 10am. Which works better?"

*Expected outcomes:*
- Connect rate: 38% (vs. 12% for cold email on same list)
- Conversation rate: 64% of connected calls reach qualification
- Meeting booked rate: 41% of qualified conversations → booked demo
- Resulting pipeline conversion: 9.8% of live attendees → qualified opportunity (vs. 3.2% baseline)
- Cost per pipeline opportunity: $47 (vs. $210 for human SDR follow-up call)

## Success Metrics

- **Connect Rate**: Target >35% for live attendees called within 90 minutes; benchmark against email open rate from the same post-event sequence
- **Conversation-to-Qualification Rate**: >30% of conversations should yield a qualified opportunity or clear disqualification — below 20% signals script or targeting problems
- **Meeting Show Rate**: Voice-AI-booked meetings should show at >72%; below 60% indicates booking before sufficient qualification
- **Pipeline-per-Event Ratio**: Revenue of event-sourced opportunities should exceed 5x total event cost (speaker fees, platform, production) within 180 days
- **Time-to-First-Contact**: Median time from event end to first Voice AI call attempt — target <45 minutes for Tier 1 attendees
- **Email vs. Voice AI Pipeline Split**: Track which attendees booked via Voice AI call vs. email sequence only; measure 90-day pipeline velocity difference between the two cohorts

## Related Prompts

- [Voice AI Autonomous Outbound SDR Pipeline Architecture](./AI-Powered-B2B-SaaS-Voice-AI-Autonomous-Outbound-SDR-Pipeline-Architecture-&-Agentic-Cold-Calling-Revenue-Intelligence-Engine.md) — outbound cold-calling counterpart to this inbound/warm follow-up system
- [Voice AI Lead Response & Speed-to-Lead Conversion](../Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Voice-AI-Lead-Response-&-Speed-to-Lead-Conversion-Intelligence-Engine.md) — applies Voice AI to inbound form-fill leads; pair with this for full inbound pipeline coverage
- [Webinar Post-Event Pipeline Conversion Architecture](../Webinar-Marketing/AI-Powered-B2B-SaaS-Webinar-Post-Event-Pipeline-Conversion-Architecture-&-Attendee-Revenue-Nurture-Intelligence-Engine.md) — email and multi-channel post-event nurture that runs in parallel with Voice AI calling
- [Webinar Audience Intelligence & Real-Time Engagement Scoring](../Webinar-Marketing/AI-Powered-B2B-SaaS-Webinar-Audience-Intelligence-&-Real-Time-Engagement-Scoring-Pipeline-Conversion-Revenue-Intelligence-Engine.md) — generates the engagement data that feeds Voice AI segmentation tiers

## Integration Tips

- **Zoom Webinars → HubSpot**: Use the native Zoom-HubSpot integration to sync attendance, duration, and Q&A data to contact records automatically within 5 minutes of session end; trigger Voice AI call queue enrollment via HubSpot workflow on the "Webinar Attendance Status = Attended" property update
- **Goldcast / ON24 → Salesforce**: Use Goldcast's Salesforce native connector or ON24 Salesforce integration to write engagement scores directly to Lead and Contact objects; build a Salesforce flow to enroll in Voice AI queue when engagement score >70 on session end
- **Bland.ai API**: Use the `/calls` endpoint with dynamic variable injection (`{FIRST_NAME}`, `{EVENT_TITLE}`, `{THEIR_QUESTION}`) passed in the `request_data` field; Bland.ai's pathway feature handles conditional script branching without custom code
- **Chili Piper Instant Booker**: Configure the Voice AI to send a Chili Piper booking link via SMS immediately after verbal commitment on the call; set up Chili Piper's CRM routing rules to assign to the correct AE based on Salesforce territory assignment
- **Calendly + Zapier**: When Voice AI logs "disposition = interested, send link," Zapier fires a Calendly invite link via SMS/email within 30 seconds; Calendly event creation triggers a Salesforce opportunity creation and AE pre-brief email via a second Zapier step
- **Post-call Transcripts → Gong/Chorus**: Configure Voice AI platform to push call recordings to Gong or Chorus for manager QA, script coaching, and aggregate conversation intelligence reporting; tag by event name for cohort analysis

## Troubleshooting

**Problem: Low connect rate (<20%) despite calling within 90 minutes of event end**
Solution: Audit call timing by attendee time zone — a 5pm ET webinar means West Coast attendees are at 2pm (prime calling window) but EMEA attendees are at 10pm (DND). Segment international attendees into a next-morning call queue adjusted to their local 9–11am window. Also verify caller ID display name — branded caller ID ("DataSync Team") vs. unknown number improves answer rates by 18–25%.

**Problem: High connect rate but low conversation rate (calls end in <30 seconds)**
Solution: The opening line is losing them before the value hook lands. A/B test three openings: (1) event-specific reference ("you were in our webinar today"), (2) pain-point lead ("I'm calling because you asked about schema drift"), and (3) outcome lead ("I'm following up because what you asked about could save your team 8–12 hours a week"). Review call recordings in bulk — if prospects are hanging up after "I'm an AI," test disclosing at 15 seconds instead of the opening line, or lead with the question first.

**Problem: Meetings booked but show rate below 60%**
Solution: Voice AI is booking too early in the qualification sequence — prospects are agreeing to meetings to end the call, not because they're genuinely qualified. Add one more commitment-check question before offering the meeting: "If you came to that session and we could show you exactly how [Outcome], would that change how your team thinks about this for this quarter?" Only proceed to meeting booking if the answer is affirmative. Also verify the meeting confirmation email includes a clear agenda — "here's exactly what we'll cover" increases show rates by 12–18%.

## Version History
- v1.0: Initial creation (auto-generated)
