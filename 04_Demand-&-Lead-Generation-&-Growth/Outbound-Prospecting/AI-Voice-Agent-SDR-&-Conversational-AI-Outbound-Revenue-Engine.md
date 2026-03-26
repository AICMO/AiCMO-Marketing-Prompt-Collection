# AI Voice Agent SDR & Conversational AI Outbound Revenue Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** ai-sdr, voice-agent, outbound, conversational-ai, b2b, automation, demand-gen, pipeline-generation

## Overview
Designs and deploys a production-ready AI voice agent SDR program — including call scripts, objection handling trees, qualification frameworks, and handoff logic — that autonomously calls cold and warm prospects, qualifies buying intent, and books meetings directly onto sales calendars. Use it when building your first AI-powered outbound calling program, scaling SDR capacity without proportional headcount growth, or testing AI-native prospecting as a parallel motion to human SDR outreach.

## Quick Copy-Paste Version

You are a senior B2B revenue engineer with deep expertise in conversational AI and outbound sales automation. I need you to design a complete AI voice agent SDR program for my company.

My context:
- Company: [Describe your product and the core problem it solves in 2-3 sentences]
- ICP: [Job title, company size, industry, typical pain points]
- Target outcome per call: [e.g., book a 30-min demo / qualify for AE outreach / invite to webinar]
- Average deal size: [ACV range — e.g., $15K–$80K/year]
- AI voice platform I'm using or evaluating: [Bland AI / Vapi / Synthflow / ElevenLabs / Retell AI / Other]
- CRM: [HubSpot / Salesforce / Pipedrive / Other]
- Current outbound channels: [Email only / Email + LinkedIn / Full multi-channel]

Produce the following:

1. CALL SCRIPT ARCHITECTURE
   - Opening hook (first 8 seconds that avoid instant hang-ups)
   - Soft permission-ask framework (before the pitch)
   - Value proposition delivery (20 seconds max, jargon-free)
   - Discovery questions (3 qualifying questions using SPIN or MEDDIC logic)
   - Meeting ask + calendar booking language
   - Voicemail script (if no answer)

2. OBJECTION HANDLING TREE
   - Top 5 objections with specific rebuttals for B2B cold calling
   - "I'm busy" / "Send me an email" deflection responses
   - "We already have a solution" competitive handling
   - "Not interested" — soft re-engagement before disconnect
   - "Call me next quarter" — future pipeline sequencing logic

3. QUALIFICATION FRAMEWORK
   - 3 mandatory qualification gates the AI must clear before booking a meeting
   - Disqualification criteria: who NOT to book to protect AE calendar
   - MQL → SQL handoff data the AI must capture before transfer

4. INTEGRATION & HANDOFF WORKFLOW
   - How booked meetings sync to CRM and AE calendars
   - What data the AI captures and logs per call
   - How to trigger follow-up email sequences post-call

5. PERFORMANCE BENCHMARKS
   - Connect rate, conversation rate, meeting booked rate targets
   - What "good" looks like at 90 days post-launch

## Advanced Customizable Version

ROLE: You are an elite GTM engineer and conversational AI architect. You have designed and deployed AI voice agent SDR programs that generated $10M+ in qualified pipeline for B2B SaaS companies — without a single human making those calls. You understand the psychology of cold calling, the technical constraints of voice AI platforms, and the operational requirements of a sales development program. You give specific, production-ready recommendations — no theory, no vague frameworks.

MISSION: Design a complete, launch-ready AI voice agent SDR system. Every script must survive contact with a real, skeptical B2B buyer. Every recommendation must be deployable within 30 days.

COMPANY CONTEXT:
- Company name: [Your company]
- Product/service: [What you do and the specific outcome you deliver]
- Unique differentiation: [Your strongest proof point vs. status quo and competitors]
- Customer proof: [3 specific customer results with numbers — e.g., "Reduced onboarding time from 14 days to 3 days for a 200-person logistics company"]
- Pricing: [ACV range and billing model]
- Sales cycle: [Average days from first meeting to closed-won]

ICP DEFINITION:
- Primary buying persona: [Title, seniority, key responsibilities]
- Secondary influencer: [Who else is in the buying committee]
- Company profile: [Size, industry, stage, tech stack signals]
- Pain trigger events: [Events that make them an ideal target — new hire, funding, competitive switch, regulation, growth milestone]
- Watering holes: [Where they consume content — LinkedIn communities, podcasts, industry events]

PROGRAM PARAMETERS:
- AI voice platform: [Bland AI / Vapi / Synthflow / ElevenLabs Conversational AI / Retell AI / Aircall AI]
- Call volume target: [X calls/day or week]
- Target geography/timezone coverage: [Regions and calling hours]
- Call list source: [Apollo / LinkedIn Sales Nav / ZoomInfo / Clay / Inbound leads / Event attendees]
- CRM: [Tool + version] with [active integrations]
- Calendar tool: [Calendly / Chili Piper / HubSpot Meetings / Salesforce Scheduler]
- AE team capacity for meetings: [X meetings/AE/week]

---

SCRIPT ARCHITECTURE DESIGN:

Section 1 — The First 8 Seconds (The Survival Zone)

The first 8 seconds determine whether the prospect stays on the line. Design the opening to:
a) Sound like a professional human, not a robocall
b) Establish immediate context and relevance
c) Earn permission to continue the conversation

Required elements:
- Greeting formula: Name + company + single-sentence context hook
- Pattern interrupt technique: use a trigger event, mutual connection, or observation that signals this call is NOT generic
- Soft permission bridge: "I know this is out of the blue — can I take 30 seconds?" or equivalent
- Voice persona guidelines: tone, pace, filler word policy, handling of "Who is this?" or "Is this AI?"

Generate 3 alternative opening scripts for my ICP — one trigger-event-based, one social proof-based, one curiosity-based. Each must be under 25 words before the permission ask.

Transparency protocol for AI disclosure:
- At what point (if ever) should the AI disclose it is an AI?
- Recommended approach given FTC, TCPA, and state AI disclosure requirements (as of 2025)
- How to handle "Are you a real person?" without lying or losing the call

Section 2 — Value Delivery Architecture (20-Second Pitch Framework)

Design the value delivery section using the "Problem → Proof → Promise" framework:
a) Problem statement: Name a specific pain in their language (not your feature language)
b) Proof bridge: One-sentence customer result that makes the problem concrete
c) Promise: What changes for them specifically if they take 20 minutes

Constraints:
- Zero jargon: every word must be understood by someone outside their industry
- One metric minimum: quantify the outcome ("X% faster" / "Y hours saved" / "$Z recovered")
- No features: zero product feature mentions in the opening pitch — only outcomes

Generate 3 value delivery scripts for my top 3 ICP pain points. Each must be 3 sentences maximum.

Section 3 — Qualifying Conversation Design (MEDDPICC Integration)

Design 5 discovery questions the AI can naturally ask during a call to qualify on:

M — Metrics: What is the quantifiable cost of the problem they have?
E — Economic Buyer: Is this person the decision-maker, or who is?
D — Decision Criteria: What does "good solution" look like to them?
C — Champion: Are they personally motivated to change, or just politely listening?
I — Implicitly: What's the urgency driver (timeline, event, consequence)?

For each question:
- Natural language version (how a human SDR would ask it in conversation)
- If/then branching logic: what the AI does if the answer signals disqualified vs. qualified
- How to transition between questions without sounding like a checklist

Qualification scoring rubric:
- Hot (book immediately): Criteria list + fast-track calendar booking script
- Warm (nurture): Criteria list + what the AI promises to send and when
- Cold (disqualify): Criteria list + professional exit language + how to preserve the relationship for future outreach

Section 4 — Objection Response System

Design AI-native rebuttals for the 8 most common cold call objections in B2B SaaS outbound:

Objection 1: "I'm not interested."
- Detect-and-bridge response: acknowledge, reframe, micro-ask
- What NOT to say (common mistakes that guarantee the hang-up)
- Maximum 2 attempts before graceful exit

Objection 2: "Just send me an email."
- Why this objection is actually a soft yes
- How to honor the request while still planting a calendar hook
- Follow-up email template triggered immediately post-call

Objection 3: "We already use [competitor]."
- Discovery question to uncover satisfaction level without attacking the competitor
- How to position your differentiation against the specific competitor named
- Softening language for "switching" conversations

Objection 4: "We don't have budget right now."
- How to determine if this is a timing objection or a disqualification signal
- Budget creation question: "If this solved [X problem], what would it be worth to fix?"
- Pipeline nurture sequence trigger for "Q3/Q4 budget cycle"

Objection 5: "Can you call me next quarter?"
- How to lock in a specific callback date in real-time (not "sure, I'll reach out")
- Calendar hold language that gets the prospect to accept while on the call
- CRM task automation for the callback

Objection 6: "I need to loop in [other person]."
- How to identify whether this is a stall or a legitimate buying committee requirement
- Script for requesting a 3-way call with the other stakeholder
- Multi-threading email to the additional contact triggered post-call

Objection 7: "How did you get my number?"
- Transparency response that builds trust rather than destroys it
- Legal compliance language for TCPA, GDPR, and state-level calling regulations
- When to immediately remove from list vs. when to continue

Objection 8: "I'm too busy right now."
- Ultra-short meeting ask (15-minute version instead of 30)
- "What would make this worth 15 minutes?" reverse-qualifying question
- Voicemail drop strategy if they ask you to leave a message

Section 5 — Meeting Booking & Handoff Design

The moment the prospect says yes, the AI must execute flawlessly:

a) Calendar booking flow:
- How to offer 2-3 specific time slots (not "what works for you?" — too open-ended)
- Time zone confirmation protocol
- Confirmation language that reduces no-shows
- Calendar invite subject line formula: specific, not generic ("Exploring [Specific Outcome] for [Company]")

b) Pre-meeting sequence (triggered immediately post-booking):
- Confirmation email: sent within 60 seconds of call end
- 24-hour reminder: includes agenda, what to prepare, who will be on the call
- 1-hour reminder: short, specific, action-oriented
- No-show recovery: automated reschedule attempt + SDR human escalation trigger

c) CRM data capture requirements (what the AI must log per call):
- Contact record updates: verified title, direct number, email, LinkedIn URL
- Call outcome field: Connected-Booked / Connected-Nurture / Connected-Disqualified / Voicemail / No Answer
- Qualification data: MEDDPICC fields populated from conversation
- AI call summary: auto-generated transcript summary in 3 bullet points
- Recording: where to store and who gets access

d) AE handoff package (what lands in AE inbox when meeting is booked):
- Account snapshot: company + contact + pain points surfaced on call
- Call transcript or AI summary
- Recommended meeting agenda based on qualification signals
- Competitive intelligence: if competitor was mentioned, flag and include battlecard link

Section 6 — Compliance & Ethical Guardrails

AI calling compliance requirements (2025):
a) TCPA compliance: Do-Not-Call list scrubbing protocol, calling hour restrictions by state, consent requirements for B2B vs. B2C
b) AI disclosure laws: States with mandatory AI disclosure requirements (California, Colorado, Texas, Illinois as of 2025); recommended universal disclosure language
c) GDPR/CCPA: Data handling for EU and California contacts, call recording consent requirements, right-to-erasure process
d) Internal suppression lists: Competitors, existing customers, active opportunities, recently closed-lost (cooling period), unsubscribed contacts from any channel

Guardrails to prevent AI failure modes:
- Infinite loop prevention: max conversation turns before graceful exit
- Profanity or hostile language detection: immediate de-escalation and call end protocol
- "Remove me from your list" handling: instant suppression + confirmation language
- Technical failure fallback: what happens if voice platform latency causes awkward silence or response errors

Section 7 — Performance Analytics & Optimization

Weekly AI SDR scorecard metrics:
- Dial-to-connect rate (target: 8–15% for cold lists; 20–35% for warm/event lists)
- Connect-to-conversation rate (target: 60–70% of connects engage past 30 seconds)
- Conversation-to-meeting rate (target: 15–25% of conversations book)
- Meeting show rate (target: 70–80% for AI-booked meetings with strong pre-meeting sequence)
- Meeting-to-opportunity rate (target: 40–60% of meetings create qualified opportunities)
- Pipeline generated per 1,000 dials (the ultimate efficiency metric)

A/B testing framework for AI calls:
- Test 1 (Week 1–2): Opening script variant (trigger-event vs. curiosity vs. social proof)
- Test 2 (Week 3–4): Value proposition angle (ROI-based vs. risk-reduction vs. competitive displacement)
- Test 3 (Week 5–6): Call timing (time of day, day of week by persona type)
- Test 4 (Week 7–8): Meeting ask framing (15-min vs. 20-min vs. 30-min / discovery call vs. demo vs. quick chat)
- How to isolate variables in AI calling (vs. email A/B testing — different constraints)
- Minimum call volume for statistical significance by metric type

Monthly optimization review:
- Transcript analysis: which objections are appearing most? What's working in rebuttals vs. not?
- Conversion funnel drop-off: where are the biggest leakage points?
- ICP refinement: which segments are booking at 2x+ the average rate?
- Script iteration protocol: how often to update scripts without losing performance baselines

OUTPUT FORMAT:
- Each section as a clearly labeled, standalone deliverable
- All scripts in quotation marks, ready to copy into your voice platform prompt
- Objection trees in if/then format
- Integration steps with specific platform-level configuration instructions
- Flag any recommendations requiring legal review before deployment

## Example Input/Output

**Input Example:**
Company: Veloxa — AI-powered field service scheduling software for HVAC, plumbing, and electrical contractors with 10–100 technicians
ICP: Owner/Operations Manager at residential service companies, 10–100 employees, using ServiceTitan or Jobber
Target outcome: Book 30-min product demo with AE
ACV: $18,000–$45,000/year
Platform: Bland AI
CRM: HubSpot
Call list: Apollo (filtered by company size + ServiceTitan/Jobber technology signal)

**Output Example (Opening Script — Trigger-Event Based):**

Opening: "Hi [Name], this is Jordan from Veloxa. Quick question — I saw you're hiring two more dispatchers on Indeed right now. Is that because scheduling volume is outpacing what your current system can handle?"

[If yes]: "That's exactly why I'm calling. We helped Accurate Air — a similar HVAC company in Phoenix with 28 techs — cut their dispatch team by one coordinator while booking 22% more jobs in the same week. I'd love to show you how. Could I grab 30 minutes on Thursday or Friday?"

[If no/confused]: "Totally understand — I had the wrong read on that. I do work with a lot of HVAC operators your size who are managing scheduling headaches as they scale. Is that something you're dealing with at all?"

---

**Objection Response (Competitor Handling — ServiceTitan):**

Prospect: "We use ServiceTitan for everything — scheduling, dispatch, invoicing."

AI Response: "ServiceTitan is solid for invoicing and job tracking — a lot of our customers came from there. The gap they usually hit is that ServiceTitan's scheduling still requires a human dispatcher making judgment calls all day. What we do is automate that routing decision entirely — the AI assigns the right tech based on location, skill set, and availability in real-time, without someone manually moving tiles around. If your dispatchers are still spending 3+ hours a day on scheduling, that's the exact problem we solve. Would it be worth 20 minutes to see what that looks like for a team your size?"

---

**Qualification Scoring (from a 4-minute conversation):**

Hot indicators: Using Jobber/ServiceTitan (tech signal confirmed) + "We had 3 double-bookings last month" (pain confirmed) + "I make the technology decisions here" (economic buyer confirmed) + "We're trying to fix this before summer season" (urgency confirmed) → **Book immediately**

Warm indicators: Uses generic scheduling tool + mentions "my office manager handles that" + no expressed urgency → **Soft CTA: send comparison guide, follow up in 2 weeks**

Cold indicators: Solo operator with 2 techs + "We don't really have scheduling problems" + "Not looking to spend money right now" → **Disqualify + suppress 6 months**

## Success Metrics

- **Dial-to-meeting rate:** Target 2–5% of total dials result in a booked meeting (1,000 dials → 20–50 meetings)
- **Meeting show rate:** Target >72% — AI-booked meetings with a strong pre-meeting sequence outperform human-booked meetings in many programs
- **Cost per meeting booked:** Target $15–$50/meeting (vs. $150–$500 for human SDR programs at scale)
- **Meeting-to-opportunity rate:** Target 45–60% of held meetings convert to qualified opportunities in CRM
- **Pipeline efficiency:** Track pipeline generated per $1 spent on AI voice program vs. human SDR program
- **Compliance score:** Zero TCPA violations, 100% DNC list scrubbing, all disclosures logged per call

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Outbound-Prospecting/Cold-Call-Script-&-Phone-Outreach-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Outbound-Prospecting/Multi-Channel-Outbound-Sequence-Orchestrator.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Outbound-Prospecting/AI-Powered-Cold-Email-Personalization-at-Scale-&-Deliverability-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Outbound-Prospecting/Buying-Committee-Intelligence-&-Multi-Stakeholder-Outreach-Engine.md`

## Integration Tips

- **Bland AI / Vapi:** Use the "pathway" feature to build branching conversation trees for each objection scenario; set max call duration to 8 minutes to maintain high connect-to-meeting ratios; enable call transcription and webhook to push transcripts to HubSpot/Salesforce in real-time
- **HubSpot:** Create a custom contact property "AI Call Outcome" (dropdown: Booked / Nurture / Disqualified / No Answer / Voicemail); use workflow automation to enroll booked contacts in pre-meeting email sequence and suppress them from all outbound email sequences; log call recordings as attachments on contact record
- **Salesforce:** Build a "Voice SDR" lead source value for attribution; use Flow to auto-create a Task on the assigned AE's record when a meeting is booked with the AI call summary as the description; trigger Slack notification to AE via Salesforce-Slack integration
- **Calendly / Chili Piper:** Configure AI to pass UTM parameters (source: ai-voice, campaign: cold-outbound) in calendar booking links for accurate pipeline attribution; use round-robin routing to distribute meetings across AE team; set buffer time between AI-booked meetings (minimum 15 min) to give AEs prep time
- **Clay:** Use Clay to build pre-call research enrichment — pull LinkedIn recent posts, job change signals, company news, and tech stack data before the AI dials; feed enriched context into the call script as dynamic variables for hyper-personalized openings
- **Zapier / Make:** Connect voice platform webhooks to trigger post-call email sequences in your MAP (HubSpot / Marketo / Outreach); route "not interested" contacts to a 90-day re-engagement nurture sequence; alert human SDR manager in Slack when AI encounters a conversation pattern it cannot resolve (escalation trigger)

## Troubleshooting

**Problem: Connect rate is high (12%+) but conversation-to-meeting rate is below 8%**
Solution: The AI is connecting but failing in the first 30 seconds. Pull call transcripts and find the drop-off point: (1) If prospects hang up within 10 seconds — your opening is sounding robotic or overly salesy; rewrite the first sentence to lead with a trigger event or observation, not your company name. (2) If prospects engage for 30–60 seconds then disengage — your value proposition is too feature-focused; strip all product language and replace with one customer outcome in plain English. (3) If prospects engage past 90 seconds but don't book — your qualification questions are too interrogative; restructure as a two-way conversation with shorter questions and active listening cues ("That makes sense — tell me more about that").

**Problem: Meeting show rate is below 55% for AI-booked meetings**
Solution: AI-booked meetings tend to have lower commitment than human-booked meetings because there's no relationship established on the call. Fix with a pre-meeting sequence: (1) Send a personalized confirmation email within 60 seconds of booking that references something specific from the call ("As we discussed, I'll show you exactly how we solved [specific pain they mentioned]"). (2) Add a 24-hour reminder that includes a 2-sentence agenda so the prospect knows exactly what to expect and has a reason to show up. (3) Send a 1-hour reminder with the AE's name, photo, and LinkedIn profile — humanizing the meeting increases show rates by 15–25%. (4) For no-shows: trigger an automated "missed connection" email within 10 minutes offering 2 reschedule options; do not wait for the AE to notice.

**Problem: Receiving cease-and-desist or regulatory complaints about AI calling**
Solution: Immediately audit your compliance stack: (1) Confirm you are scrubbing against the National DNC Registry AND state-specific DNC lists before every dialing session — not just at list import. (2) Check your AI disclosure language — as of 2025, California (AB 2602), Colorado, and Texas require disclosure that the caller is an AI within the first 10 seconds for consumer-facing calls; B2B has more latitude but best practice is to disclose when asked directly. (3) Verify calling hours: federal rules allow 8am–9pm local time; some states (e.g., Florida, Maryland) have stricter windows. (4) Never call contacts who have expressed "do not contact" preferences in any channel — your suppression list must be omnichannel, not just phone-specific. Consult legal counsel before resuming calls in affected regions.

## Version History
- v1.0: Initial creation (auto-generated)
