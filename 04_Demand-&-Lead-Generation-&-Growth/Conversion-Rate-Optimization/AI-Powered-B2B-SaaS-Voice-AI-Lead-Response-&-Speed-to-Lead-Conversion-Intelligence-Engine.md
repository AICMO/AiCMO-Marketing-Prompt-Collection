# AI-Powered B2B SaaS Voice AI Lead Response & Speed-to-Lead Conversion Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** b2b-saas, voice-ai, speed-to-lead, cro, demo-request, inbound-conversion, ai-sdr, lead-response, pipeline-acceleration, conversational-ai

## Overview
Designs and deploys a fully automated Voice AI lead response system that calls inbound demo requesters within 60 seconds of form submission, qualifies them against MEDDIC criteria, and routes hot prospects to human sales reps — capturing the 21x conversion advantage that closes within the first five minutes. Use this when demo request show rates are below 60%, when inbound leads go uncontacted for more than 15 minutes, or when you need to extend coverage to nights, weekends, and international time zones without adding headcount.

## Quick Copy-Paste Version

You are a B2B SaaS growth engineer and Voice AI specialist. Design a complete Voice AI lead response system for the company below that converts inbound demo requests into qualified pipeline at maximum speed.

COMPANY INPUT:
- Company: [Your company name and product description]
- ICP: [Ideal customer profile — company size, industry, buyer role]
- Demo request form URL: [URL or describe current form fields]
- Current avg. lead response time: [Hours/minutes — or "unknown"]
- Current demo show rate: [X% — or "unknown"]
- Current lead-to-opportunity conversion: [X% — or "unknown"]
- CRM in use: [HubSpot / Salesforce / Pipedrive / other]
- Marketing automation: [HubSpot / Marketo / Pardot / Customer.io / other]
- Calendar scheduling tool: [Calendly / Chili Piper / Salesforce Scheduler / other]
- Sales team coverage hours: [e.g., Mon–Fri 9am–6pm EST]
- Average deal size: [$X ACV]
- Sales cycle length: [X weeks/months]

DESIGN REQUIREMENTS:
1. VOICE AI SCRIPT: Full conversation script for the AI agent — opening, qualification questions (MEDDIC-aligned), objection handlers, call-to-action to book a meeting, and graceful handoff to human rep. Include exact words.
2. QUALIFICATION LOGIC: Decision tree for routing — which answers route to immediate human transfer vs. booked meeting vs. nurture sequence vs. disqualify
3. SPEED-TO-LEAD WORKFLOW: Step-by-step automation from form submission → CRM record → Voice AI trigger → call → CRM update → human alert — all within 60 seconds
4. AFTER-HOURS PROTOCOL: How the system handles leads at 2am or on weekends without sacrificing conversion
5. INTEGRATION MAP: Which tools to connect and how (Zapier, native API, or middleware)
6. A/B TEST PLAN: 3 script variants to test in the first 30 days
7. KPI DASHBOARD: 6 metrics to track weekly with red-flag thresholds

Output a complete Voice AI Lead Response Playbook with specific scripts, decision trees, and implementation steps — not generic advice. Everything must be deployable without custom engineering using Bland AI, Vapi, or Retell AI.

## Advanced Customizable Version

ROLE: You are a senior revenue operations architect and Voice AI implementation specialist with 10+ years optimizing B2B SaaS inbound conversion. You have deployed Voice AI lead response systems for 40+ SaaS companies, run hundreds of conversation script A/B tests, and understand the psychology of cold-call-to-warm-prospect conversion at scale. You know the MIT/InsideSales.com research showing a 21x higher conversion rate when contacting prospects within 5 minutes vs. 30 minutes, and a 100x advantage in the first minute. You think in funnel math: every additional minute of response delay compounds lead decay. Your goal is not to build a bot — it is to build a revenue machine that runs 24/7/365 with zero lead decay.

CONTEXT:
Company: [Company name]
Product: [Detailed description — what it does, primary use case, key differentiators, pricing tier]
ICP definition: [Company size range, industries, buyer title, technographic fit]
Disqualifying criteria: [What makes a lead NOT worth pursuing — company size too small, wrong industry, competitor, student, etc.]
Sales motion: [Transactional self-serve / Inside sales demo-to-close / Enterprise multi-stakeholder]
Average deal size: [$X ACV — entry-level and enterprise]
Sales cycle: [X days/weeks average]
Team structure: [Number of SDRs, AEs, their territories and coverage hours]
Current inbound volume: [X demo requests per month]
Current conversion metrics (provide what you have):
- Lead-to-meeting booked: [X%]
- Meeting show rate: [X%]
- Meeting-to-opportunity: [X%]
- Overall inbound lead-to-closed-won: [X%]
Current response time: [Average and median — or "unknown"]

TECH STACK:
- CRM: [Name and key objects used — Lead, Contact, Opportunity]
- Marketing automation: [Name and key workflows in place]
- Calendar/scheduling: [Tool name, how meetings are routed to reps]
- Current lead routing logic: [Round-robin / territory-based / AE-owner / none]
- Voice AI platform (choose or let AI recommend): [Bland AI / Vapi / Retell AI / Synthflow / undecided]
- Existing integrations: [Zapier / Make / native API / custom webhook]

COMPETITIVE CONTEXT:
Competitors you most frequently see in deals: [List 2-3]
Why prospects choose you vs. competitors: [Key differentiators]
Why prospects don't choose you: [Top 3 objections]

ANALYSIS AND DESIGN FRAMEWORK — Complete ALL sections:

**1. SPEED-TO-LEAD REVENUE MODEL**
Before designing the system, calculate the revenue impact of speed:
- At current response time of [X hours], estimate what percentage of leads have already engaged a competitor or lost interest (use the InsideSales Velocity Decay Model: lead intent decays 50% every 30 minutes after form submission)
- Calculate: If average deal is $[X], lead volume is [X]/month, and current lead-to-close is [X%], what is the monthly revenue currently lost to slow response?
- Project: What does 60-second response add to annual revenue at target conversion rates?
- Present as a CFO-ready business case table with conservative, base, and upside scenarios

**2. COMPLETE VOICE AI CONVERSATION SCRIPT**

Design a full conversation script using the AIDA-Q framework (Attention → Interest → Desire → Action → Qualification):

Opening (Attention) — First 10 seconds:
- Caller ID strategy: Use company number, not unknown/800 number
- Opening line options (provide 3 variants A/B/C with rationale for each):
  * Direct value variant: "Hi [First Name], this is Aria from [Company] — you just requested a demo. I'm calling to make sure you get the fastest path to what you're looking for. Do you have 2 minutes?"
  * Human-warmth variant: [Write full script]
  * Urgency variant: [Write full script]
- Disclose AI identity — required by FTC 2026 guidelines: How to disclose without killing the conversation

Qualification Sequence (MEDDIC-aligned, maximum 5 questions):
For each question provide:
  a) Exact phrasing of the question
  b) The MEDDIC element it qualifies (Metrics / Economic Buyer / Decision Criteria / Decision Process / Identify Pain / Champion)
  c) Qualifying answer (routes to high-priority)
  d) Disqualifying answer (routes to nurture)
  e) Clarifying follow-up if answer is ambiguous

Minimum required qualification questions:
  Q1: Pain urgency ("What made you reach out today vs. 3 months ago?") → identifies active pain vs. passive research
  Q2: Timeline ("When are you hoping to have something in place?") → qualifies urgency
  Q3: Role ("Are you the one who'd be evaluating this, or is there a team involved?") → maps buying committee
  Q4: Budget signal ("Do you have a budget allocated for this, or is this still in the research stage?") → economic buyer signal
  Q5: [Design company-specific Q5 based on their product and ICP]

Objection Handlers — provide exact scripts for:
  - "I'm not the right person" → discovery redirect to find who is + offer to include them
  - "I was just looking / researching" → reframe to immediate value offer
  - "I don't have time right now" → micro-commitment script (30-second value pitch + calendar link by text)
  - "We already use [Competitor]" → competitive positioning script using the company's differentiator
  - "Send me an email instead" → email + call-to-action offer, capture interest signal

Call-to-Action (Book the Meeting):
  - Hard CTA: "I can get you booked with one of our team in the next 2 minutes — do you have time available [tomorrow/this week]?"
  - Soft CTA for not-quite-ready: "I'll text you a link to book a time whenever works — what's the best number for that?"
  - Meeting-by-text workflow: How the agent texts a Calendly link mid-call

**3. ROUTING DECISION TREE**

Design a qualification scoring matrix:

Hot Route (immediate human transfer during the call — live patch):
- Criteria: [Define exact threshold — e.g., enterprise company + budget allocated + decision in 30 days + economic buyer]
- Human patch script: How the AI transitions to the human rep mid-call
- Alert format: What the rep sees on their phone/screen when patched in

Warm Route (meeting booked for next business day):
- Criteria: [Define — e.g., ICP company size + active pain + 60-day timeline]
- Booking flow: AI offers specific slots, sends calendar invite, sends SMS confirmation
- Pre-meeting prep: What the AI sends to the rep (call transcript summary, qualification score, company firmographics pulled from Clearbit/Apollo)

Follow-Up Route (7-day nurture → try again):
- Criteria: [Define — e.g., right ICP but "just researching," no timeline]
- Handoff to marketing automation: What trigger fires in HubSpot/Marketo
- Re-engagement timing: When the AI calls again or marketing email fires

Disqualify Route:
- Criteria: [e.g., student, competitor, wrong geography, company too small]
- Handling: How to politely close without burning the relationship

No-Answer Protocol:
- Voicemail script (15 seconds, include SMS follow-up instruction): [Write exact script]
- Call cadence for no-answers: How many attempts, at what intervals, on which channels (call → SMS → email)
- At what point does AI hand off to human or stop

**4. SPEED-TO-LEAD AUTOMATION ARCHITECTURE**

Map the full workflow from form submit to call initiated — target: under 60 seconds:

Step 1 — Form Submission (T+0s):
- Form fields to capture: [Which fields are essential for routing vs. nice-to-have]
- Hidden fields to auto-populate: UTM source, campaign, referring URL, IP-based company identification
- Immediate confirmation: What the lead sees/receives at T+0

Step 2 — CRM Record Creation (T+5–15s):
- Lead object created in [CRM]: Required fields, owner assignment logic
- Data enrichment trigger: Which enrichment tool fires (Clearbit/Apollo/ZoomInfo) and what fields it populates before the call
- Duplicate check: What happens if the lead already exists as a contact/opportunity

Step 3 — Routing Logic Check (T+15–20s):
- Which routing rules disqualify from Voice AI call? (e.g., existing customer, opportunity already open, geography outside coverage)
- For disqualified records: What fires instead (email only, route to AE directly, etc.)

Step 4 — Voice AI Call Trigger (T+20–30s):
- API call to [Bland AI / Vapi / Retell] with dynamic variables populated: [List all dynamic variables — first name, company, product requested, form source, etc.]
- Caller ID configuration: Use company number for trust

Step 5 — Call Execution (T+30s–5min):
- Real-time CRM logging during call: Which fields update as the call progresses
- Transcription storage: Where call transcript goes (CRM note, Gong, Slack)

Step 6 — Post-Call Automation (T+5–7min):
- CRM record updated with: qualification score, MEDDIC fields populated, call disposition, meeting booked Y/N
- Rep notification: What the SDR/AE receives (Slack, email, Salesforce task) with call summary
- Marketing automation trigger: What fires if call result = "follow-up" vs. "booked" vs. "disqualified"

**5. AFTER-HOURS & WEEKEND PROTOCOL**

Design how the system handles leads submitted outside business hours:

Immediate (T+0):
- Voice AI still calls immediately with a modified script acknowledging the time: [Write the after-hours opening variant]
- Offer: Book a meeting for next business day (not "someone will call you")
- SMS confirmation with calendar link sent immediately

If No Answer After-Hours:
- Voicemail with callback number + text link (so the prospect can self-book at 2am)
- Next morning: First alert in SDR queue for personal follow-up at 8am local time

International Leads:
- Time zone detection from IP or phone number area code
- Language variant protocol: How to handle non-English speakers (escalate to human or use multilingual AI)

**6. VOICE AI PLATFORM SELECTION GUIDE**

If the company hasn't chosen a platform, evaluate and recommend based on their stack:

| Criterion | Bland AI | Vapi | Retell AI | Synthflow |
|-----------|----------|------|-----------|-----------|
| Native CRM integrations | [Detail] | [Detail] | [Detail] | [Detail] |
| Latency (time to respond in conversation) | [ms] | [ms] | [ms] | [ms] |
| Voice quality / naturalness | [Rating] | [Rating] | [Rating] | [Rating] |
| Script complexity handling | [Detail] | [Detail] | [Detail] | [Detail] |
| Cost per minute | [Detail] | [Detail] | [Detail] | [Detail] |
| FTC 2026 AI disclosure compliance | [Detail] | [Detail] | [Detail] | [Detail] |
| Best for | [Use case] | [Use case] | [Use case] | [Use case] |

Recommendation: Based on the company's tech stack and use case, recommend one platform with implementation rationale.

**7. A/B TEST ROADMAP (First 90 Days)**

Design a structured test program:

Month 1 — Script Testing:
- Test 1: Opening line A vs. B (direct value vs. human warmth) — Primary metric: Call acceptance rate (% who stay on the line past 15 seconds)
- Test 2: Qualification question order — Does asking pain first vs. timeline first affect booking rate?
- Test 3: CTA framing — "Can I book you a time right now?" vs. "I'll text you a link" — which converts better?

Month 2 — Timing Testing:
- Test 4: Call timing — Immediate (T+60s) vs. 5 minutes vs. 15 minutes — Does a slight delay improve answer rate?
- Test 5: Day-of-week and time-of-day call timing for different ICP segments

Month 3 — Personalization Testing:
- Test 6: Dynamic script personalization by lead source (paid search vs. organic vs. content download) — Does referencing the source improve conversion?
- Test 7: Company size personalization — SMB vs. mid-market vs. enterprise scripts with different qualification thresholds

For each test, specify:
- Primary metric
- Minimum sample size (at 85% confidence level, acceptable for iteration speed)
- Expected timeline to significance
- What you'll implement if variant wins

**8. MEASUREMENT DASHBOARD**

Define a Voice AI Lead Response performance dashboard:

| KPI | Definition | Target | Red Flag |
|-----|------------|--------|----------|
| Speed-to-first-call | Time from form submit to call initiated | <60 seconds | >5 minutes |
| Call answer rate | % of calls answered by prospect | >35% | <20% |
| Qualified conversation rate | % of answered calls that complete qualification | >55% | <30% |
| AI-to-meeting conversion | % of answered calls that result in booked meeting | >25% | <12% |
| Meeting show rate | % of AI-booked meetings that attend | >70% | <50% |
| AI-influenced pipeline | Total pipeline sourced from Voice AI-converted leads | [Target $] | — |
| Revenue-per-call | Pipeline generated ÷ total calls made | [$X] | <[$Y] |
| Human transfer rate | % of calls escalated to live rep immediately | [Target 5–15%] | >30% (over-routing) |

Reporting cadence:
- Daily: Call volume, answer rate, meetings booked (Slack digest to revenue ops)
- Weekly: Full funnel view — calls → meetings → opportunities → revenue (1:1 with CMO/CRO)
- Monthly: Cohort analysis — do Voice AI-converted leads close at same rate as human-converted? LTV comparison.

OUTPUT FORMAT:
Produce a complete Voice AI Lead Response System Design structured as:
- Revenue Business Case (table: current state vs. projected with Voice AI)
- Qualification Criteria Matrix (who gets called, how they're routed)
- Full Conversation Script (opening variants + qualification sequence + objection handlers + CTAs)
- Automation Architecture (step-by-step workflow with tool names)
- After-Hours Protocol
- A/B Test Roadmap (30/60/90 day)
- Platform Recommendation (with rationale)
- KPI Dashboard

Every recommendation must include: What to do, Why it works, How to implement (specific tool steps), and How to measure.

## Example Input/Output

**Example Input:**

Company: Meridian AI — B2B sales intelligence platform that identifies buying signals from 40+ data sources
ICP: VP Sales and Revenue Operations leaders at B2B SaaS companies, 50–500 employees
Current inbound: 180 demo requests/month
Average deal size: $18,000 ACV
Current lead-to-meeting rate: 34%
Current response time: 4.2 hours average (SDR team responds during business hours only)
Demo show rate: 52%
CRM: Salesforce
Marketing automation: HubSpot
Calendar: Chili Piper
Sales team: 4 SDRs, Mon–Fri 8am–6pm EST only
Voice AI platform: Undecided

**Example Output (excerpts):**

**REVENUE BUSINESS CASE**

| Scenario | Monthly Leads | Response Time | Lead-to-Meeting | Meeting Show | Incremental Pipeline/mo |
|----------|--------------|--------------|-----------------|--------------|------------------------|
| Current state | 180 | 4.2 hours | 34% | 52% | $0 (baseline) |
| Conservative (Voice AI, 60s response) | 180 | <60s | 44% (+10pts) | 60% (+8pts) | +$181K |
| Base case | 180 | <60s | 52% (+18pts) | 65% (+13pts) | +$324K |
| Upside (nights/weekends captured) | 200 (+11%) | <60s | 56% (+22pts) | 68% (+16pts) | +$468K |

Meridian is leaving approximately $324K/month in qualified pipeline on the table due to a 4.2-hour response delay. At 18,000 ACV and a 25% close rate, this represents ~$972K in ARR from inbound leads alone.

**OPENING SCRIPT — Variant A (Direct Value)**

"Hi [FirstName], this is Aria, an AI assistant at Meridian. You just requested a demo on our site — I'm calling to make sure we get you exactly what you're looking for without making you wait. Full transparency: I'm an AI agent, so if you'd rather talk to a human, just say so and I'll connect you right now. Otherwise I have two quick questions that'll let me set you up with the right person. Does that work?"

[If YES]: "Great. First — what made you reach out today? Are you actively evaluating tools, or more in the research phase right now?"

[If RESEARCH]: "Totally makes sense. What's driving the research — is there a specific pain point you're trying to solve, or more of a 'we should probably look at this' situation?"

[If ACTIVE EVALUATION]: "Perfect. What's your ideal timeline to have something in place?" → [Routes to qualification continuation]

**QUALIFICATION ROUTING MATRIX**

| Signal Combination | Route | Action |
|-------------------|-------|--------|
| Active eval + 30-day timeline + VP/Director title + 50+ employees | HOT | Live transfer to AE now |
| Active eval + 60-90 day timeline + right ICP | WARM | Book meeting for next 48 hours |
| Research phase + ICP fit | FOLLOW-UP | Book meeting 2 weeks out + enroll in nurture |
| Wrong company size (<10 employees) OR competitor | DISQUALIFY | Polite close + community/content offer |
| No answer | VOICEMAIL | SMS text with Chili Piper link immediately |

**VOICEMAIL SCRIPT (15 seconds)**
"Hi [FirstName], this is Aria from Meridian — you requested a demo a few minutes ago. I'm sending you a text right now with a link to book directly with our team — no back and forth. Talk soon."

[SMS sent simultaneously]: "Hi [FirstName] — Meridian here. Here's your direct booking link: [ChiliPiper Link]. Pick whatever time works and we'll send you prep materials. — Meridian Team"

**SALESFORCE WORKFLOW (Automation Architecture)**

T+0s: Form submitted on meridianai.com/demo → HubSpot form capture
T+5s: HubSpot → Zapier webhook fires → Salesforce Lead created with UTM fields
T+10s: Clearbit Enrichment fires → Company size, industry, tech stack populated on Lead record
T+15s: Routing check: Is lead an existing customer? Is there open Opportunity? → If no, proceed
T+20s: Zapier → Bland AI API call with dynamic variables: {FirstName}, {Company}, {LeadSource}, {ProductInterest}
T+25s: Bland AI initiates outbound call from +1 (415) 555-0140 (Meridian main line)
T+30s–4min: Conversation occurs; Bland AI webhooks update Salesforce Lead in real-time: QualScore, MeetingBooked, CallDisposition, TranscriptURL
T+4min: If meeting booked → Chili Piper invite fires → SDR Slack alert with call summary
T+4min: If no answer → SMS fires → Salesforce task created for morning SDR follow-up

## Success Metrics

- **Speed-to-first-call** reaches <60 seconds for 95%+ of inbound leads within 2 weeks of launch
- **Call answer rate** exceeds 30% within 30 days (baseline for B2B outbound is 23%)
- **AI-to-meeting conversion** reaches 20%+ of answered calls within 60 days
- **Demo show rate** for AI-booked meetings matches or exceeds human-booked meetings within 90 days
- **After-hours lead capture** increases total qualified meetings by 15%+ within 60 days (weekends and evenings)
- **Lead response SLA** of <5 minutes achieved for 99% of business hours submissions
- Output is specific enough that a RevOps engineer can build the full workflow in one sprint without custom code

## Related Prompts

- [AI-Powered Conversational Marketing & Chatbot Lead Qualification Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Inbound-Marketing/AI-Powered-Conversational-Marketing-&-Chatbot-Lead-Qualification-Intelligence-Engine.md)
- [AI-Powered SaaS Demo Request Conversion & Show Rate Optimization Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Inbound-Marketing/AI-Powered-SaaS-Demo-Request-Conversion-&-Show-Rate-Optimization-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Lead Capture Optimization & Conversion Friction Elimination Intelligence Engine](./AI-Powered-B2B-SaaS-Lead-Capture-Optimization-&-Conversion-Friction-Elimination-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Demand Capture CRO & High-Intent Funnel Conversion Intelligence Engine](./AI-Powered-B2B-SaaS-Demand-Capture-CRO-&-High-Intent-Funnel-Conversion-Intelligence-Engine.md)

## Integration Tips

- **Bland AI / Vapi / Retell AI**: Paste the full conversation script from this prompt directly into the voice AI platform's system prompt / agent configuration. Map each dynamic variable (FirstName, Company, LeadSource) to your CRM field names in the platform's variable mapper. Enable webhook callbacks to update CRM on call completion.
- **Salesforce**: Create a custom Lead object "Voice AI Qualification" with fields for: QualScore (1–5), MeetingBooked (checkbox), CallDisposition (picklist), TranscriptURL (URL), and TimeToFirstCall (number, seconds). Use these to power your SDR dashboard and attribution reporting.
- **HubSpot**: Build the routing workflow using HubSpot's Workflow tool with a webhook action to trigger Bland AI/Vapi. Use the "Enrolled in Sequence" property to prevent double-calling leads already being worked.
- **Chili Piper**: Enable Chili Piper's "Instant Booker" to let the Voice AI agent offer specific slots by round-robin pool. Configure the Voice AI to say "I have [Tuesday at 2pm or Wednesday at 10am] available — which works?" using Chili Piper's availability API.
- **Zapier / Make**: Use Zapier's Multi-Step Zap or Make's scenario to orchestrate: Form Submit → CRM Create → Enrichment → Routing Check → Voice AI Trigger. Run all steps in sequence with <10s between each.
- **Gong / Chorus**: Configure your Voice AI platform to upload call recordings to Gong via the Gong API. Tag all Voice AI calls with a custom "source: Voice AI" tracker so you can build a Gong library of high-performing qualification conversations to train both the AI and human SDRs.
- **Slack**: Build a Slack alert that fires for every Hot Route call (live transfer eligible) — so available AEs can self-assign and join the warm transfer immediately, reducing handoff drop-off.

## Troubleshooting

**Problem: Call answer rate is below 20% — prospects aren't picking up an unknown number.**
Fix: Configure the Voice AI to call from your company's main listed phone number (not a generic VoIP number), and send an SMS simultaneously with the call: "Hi [Name] — I'm Aria from [Company], giving you a quick call about your demo request. Picking up? If not, here's a link to book: [link]." The SMS primes them to expect the call. Also test calling at T+3 minutes instead of T+30 seconds — some prospects need a moment to finish submitting the form and settle before a call lands. Track answer rate by time-of-day and source to identify your best call windows.

**Problem: Prospects are frustrated to learn they're talking to an AI mid-conversation.**
Fix: The FTC's 2026 AI Disclosure Rule requires disclosure at the start of any AI-initiated conversation. Lead with it proactively and frame it as a feature, not a bug: "I'm Aria, an AI assistant — I'm reaching out immediately so you don't have to wait hours for a callback. If you'd prefer a human right now, I'll transfer you in 10 seconds." Disclosed upfront, this frames speed as the value and eliminates the deception trust breach. Measure abandonment rate by disclosure method — proactive disclosure consistently outperforms buried or no disclosure.

**Problem: AI-booked meetings show at lower rates than human-booked meetings.**
Fix: The show rate gap is almost always caused by weak confirmation sequences. Ensure three touchpoints fire after AI-booking: (1) immediate calendar invite with meeting agenda and prep questions, (2) SMS reminder 24 hours before with one-click reschedule, (3) SMS reminder 1 hour before. Also review whether the AI is booking meetings too far out — AI-booked meetings scheduled 5+ days ahead show at 40% vs. 72% for meetings within 48 hours. Adjust the AI's booking preference to prioritize slots in the next 24–48 hours.

## Version History
- v1.0: Initial creation (auto-generated)
