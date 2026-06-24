# AI-Powered B2B SaaS AI Voice Agent Outbound Prospecting & Conversational Pipeline Generation Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** outbound, ai-voice, pipeline-generation, b2b, automation, prospecting, sdr

## Overview
This prompt architects a fully autonomous AI voice agent outbound prospecting program for B2B SaaS — covering script engineering, persona targeting, compliance guardrails, objection handling trees, meeting booking logic, and CRM integration. Use it when you want to deploy AI voice agents (Bland.ai, Vapi, Retell AI, ElevenLabs Conversational AI) for scalable outbound pipeline generation without scaling headcount.

## Quick Copy-Paste Version

You are a senior outbound revenue architect with deep expertise in AI voice agent deployment for B2B SaaS prospecting. I need to build a complete AI voice outbound program.

My company: [Your Company Name]
Product: [Brief product description — what it does, for whom]
ICP: [Ideal Customer Profile — industry, company size, title targeted]
Average deal size: [$X ACV]
Current outbound motion: [Cold email only / SDR team / None]
AI voice platform: [Bland.ai / Vapi / Retell AI / Other]

Deliver:

1. CALL SCRIPT ARCHITECTURE
   - Opening hook (first 8 seconds — pattern interrupt, not a pitch)
   - Permission-based bridge: get them to agree to 20 seconds
   - Core value statement: one outcome, one number, one proof point
   - Qualifying question tree (3 branching paths based on responses)
   - Objection handling: scripts for "Not interested," "We have a vendor," "Send me an email," "Bad time"
   - Micro-commitment close: book meeting OR get referral to right person
   - Voicemail script (under 25 seconds, specific callback hook)

2. TARGETING & TIMING LOGIC
   - Which signals trigger a call (job change, funding, hiring surge, G2 review, intent data spike)
   - Optimal call windows by timezone and persona (CTO vs. VP Sales vs. CFO)
   - Call cadence: how many attempts, what spacing, when to disqualify

3. COMPLIANCE GUARDRAILS
   - TCPA / DNC list scrubbing requirements
   - Required disclosures for AI-generated calls (varies by state)
   - Do-not-call handling in real time
   - Recording consent logic by jurisdiction

4. AI VOICE CONFIGURATION
   - Voice persona: tone, pacing, filler word policy, interruption handling
   - Transfer-to-human triggers: when the AI escalates to a live rep
   - Post-call data capture: what to log to CRM automatically

5. MEETING BOOKING FLOW
   - Calendar integration logic (Calendly / Chili Piper / native)
   - Confirmation + reminder sequence triggered post-book
   - No-show recovery call script

6. PERFORMANCE BENCHMARKS & OPTIMIZATION
   - KPIs to track: connect rate, conversation rate, meeting rate, show rate, pipeline sourced
   - A/B test framework: what to test first (opening vs. value prop vs. timing)
   - Weekly optimization cadence

Format each section with exact scripts, decision trees, and platform configuration notes.

## Advanced Customizable Version

ROLE: You are a Chief Revenue Architect specializing in AI-augmented outbound systems for B2B SaaS. You have deployed AI voice outbound programs that generate $2M–$20M in pipeline annually. You think in conversion rates, compliance risk, and human psychology simultaneously.

CONTEXT:
Company: [Company Name]
Stage: [Seed / Series A / Series B / Growth / Enterprise]
Product category: [e.g., Revenue Intelligence Platform, HR Tech, Cybersecurity]
Primary ICP:
  - Industry: [e.g., Financial Services, Healthcare, SaaS companies 50-500 employees]
  - Title targeted: [e.g., VP of Sales, CISO, Head of People]
  - Company size: [e.g., 100–1,000 employees, $10M–$100M revenue]
ACV: [$X]
Sales cycle: [X weeks/months]
Existing outbound: [Describe current motion — emails, SDRs, LinkedIn, etc.]
AI voice platform: [Bland.ai / Vapi / Retell AI / ElevenLabs / Synthflow / Custom]
CRM: [Salesforce / HubSpot / Pipedrive]
Intent data available: [Yes — 6sense/Bombora/G2 / No]
Operating regions: [US only / US + Canada / International]
Legal review: [Completed / Needed / Not applicable]

OBJECTIVE: Design a production-ready AI voice agent outbound program that generates [X meetings/month] with [Y% show rate], fully autonomous from trigger to CRM update, compliant in all operating jurisdictions.

DELIVERABLES:

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
SECTION 1: STRATEGIC PROGRAM ARCHITECTURE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

1.1 Program Thesis
    - Why AI voice, why now, what hypothesis you're testing
    - Expected lift over cold email alone (benchmark data)
    - Resource requirements: platform cost, human oversight hours/week

1.2 Segment Prioritization Matrix
    - Which ICP segments get AI voice first (highest propensity + lowest risk)
    - Segments to exclude (enterprise logos requiring white-glove, regulated industries)
    - Volume model: calls/day to hit meeting targets

1.3 Signal-to-Call Trigger Logic
    Tier 1 triggers (call within 24 hours):
      - [Funding announcement in target range]
      - [New VP/C-suite hire in buying role]
      - [High-intent website visit + email open]
      - [G2/Capterra review of competitive product]
    Tier 2 triggers (call within 72 hours):
      - [Job posting for role your product supports]
      - [LinkedIn engagement with your content]
      - [Bombora/6sense intent spike in your category]
    Tier 3 (scheduled outbound, no specific trigger):
      - [Standard ICP list — cold]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
SECTION 2: CALL SCRIPT ENGINEERING
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

2.1 Opening Architecture (0–8 seconds)
    Framework: Pattern Interrupt → Identity → Reason for Call
    
    Template A (Trigger-based):
    "Hey [First Name], this is [AI Persona Name] calling from [Company]. I'm reaching out because [company] just [trigger event — hired a new VP of Sales / raised a Series B / posted 12 AE jobs]. We help [ICP description] [achieve specific outcome] — do you have 20 seconds?"
    
    Template B (Cold/No trigger):
    "Hey [First Name], [AI Persona Name] from [Company] — I promise I'll be quick. We work with [2 company names they'd recognize] to [specific outcome]. Am I catching you at a terrible time, or do you have 30 seconds?"
    
    Template C (Referral/Warm):
    "Hey [First Name], [AI Persona Name] from [Company]. [Mutual connection / Their colleague] mentioned you might be the right person to talk to about [specific challenge]. Is that accurate?"

2.2 Permission Bridge & Value Delivery (8–25 seconds)
    After permission granted:
    "[Company] is a [category]. We specifically work with [ICP] to [outcome achieved]. Most recently, we helped [similar company] [specific result with number — e.g., reduce time-to-hire by 40% in 60 days]. The reason I'm calling is [specific reason tied to their situation]."

2.3 Qualifying Question Tree
    
    PRIMARY QUESTION: "Are you the right person to talk to about [problem area], or is that someone else on your team?"
    
    Branch A — They are the right person:
      → "Perfect. Quick question: how are you currently handling [pain point]? Is that working well for you, or is it something you're looking to improve?"
      
      Sub-branch A1 — Currently have a solution:
        → "Got it — what would have to be true for you to look at alternatives? Is it a contract renewal timing thing, or more about capability gaps?"
      
      Sub-branch A2 — Looking to improve:
        → "That's exactly why companies like [peer company] came to us. Would it make sense to spend 15 minutes to see if we could move that needle for you? I can pull up a calendar right now."
    
    Branch B — They refer to someone else:
      → "Appreciate that. Before I let you go — is [name they gave] typically open to these conversations, or would an intro from you help?"
    
    Branch C — Gatekeeper / EA:
      → "Thanks — is [executive name] generally available for these kinds of calls, or is email a better way to get on their radar first?"

2.4 Objection Handling Scripts
    
    "Not interested":
    "Totally fair — I appreciate the honesty. Just so I don't waste your time again: is it that [problem we solve] isn't a priority right now, or more that you've got it covered?"
    → If not a priority: "Got it — when does that typically come back on the radar? Q3 budget season, or more toward end of year?"
    → If covered: "That makes sense. Out of curiosity, who are you using? [Pause] Good to know. If that ever changes, we're the alternative most [ICP type] end up evaluating. Fair to keep you in the loop?"
    
    "We already have a vendor":
    "Completely understand — we actually work alongside [common competitor] in a lot of cases, or we end up being the replacement when contracts are up. When does your current agreement renew?"
    
    "Send me an email":
    "Happy to — and I will. Can I ask: what would make an email worth opening from us? Is it more about [specific outcome], or [alternative angle]? I want to make sure it's actually relevant to you."
    
    "Bad time / Call me back":
    "Of course. Is [specific day and time] realistic, or is there a better window? And is this number the best way to reach you?"
    
    "Is this an AI?":
    "[Required disclosure script — see Section 3 Compliance]. That said, the information I have for you is very real: [pivot back to value]. Does that change whether this is worth 15 minutes?"

2.5 Micro-Commitment Close
    
    Primary close — book meeting:
    "Based on what you shared, this seems like it could be relevant. I have [Day] at [Time] or [Day] at [Time] available for a 15-minute call with one of our [title]s — which works better?"
    
    Secondary close — get referral:
    "I appreciate your time. Who on your team typically evaluates [category]? Even a name and email would help me make sure I'm talking to the right person."
    
    Tertiary close — permission to follow up:
    "Fair enough. Is it okay if I follow up in [30/60/90] days when timing might be better? And what's the best way — email or another call?"

2.6 Voicemail Script (≤25 seconds)
    "[First Name], [AI Persona Name] from [Company]. We help [ICP] [specific outcome] — [company peer example] saw [result] in [timeframe]. Worth 15 minutes to see if we can do the same for [their company]? Call me back at [number] or I'll try you again [specific day]. That's [AI Persona Name] from [Company]."

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
SECTION 3: COMPLIANCE ARCHITECTURE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

3.1 Jurisdiction-Based Compliance Matrix
    
    United States:
    - TCPA: Required consent for calls to mobile numbers using auto-dialers; B2B exemptions apply but are narrowing
    - DNC Registry: Scrub against National DNC + state DNC lists before every campaign load
    - State-specific AI disclosure laws:
      → California (AB 302): Caller must disclose AI nature if asked; criminal penalties for deceptive AI voice
      → Illinois, Texas, New York: Emerging legislation — monitor quarterly
      → Federal (pending): FTC AI disclosure rulemaking in progress as of 2025
    
    Recommended disclosure script when asked "Are you an AI?":
    "Yes, I'm an AI assistant calling on behalf of [Company]. A human representative can take over this call at any time — would you like me to connect you, or are you okay continuing with me?"
    
    Canada (if applicable):
    - CASL applies to commercial electronic messages; voice calls have separate requirements
    - Quebec Law 25: Stricter privacy law; additional consent requirements
    
    3.2 Real-Time DNC Enforcement
    - Pre-call scrub: DNC.com API or TowerData/Webbula integration
    - In-call: if prospect self-identifies as DNC request, immediate termination + automatic suppression list add
    - Post-call: log all DNC requests within 24 hours per FTC requirement
    
    3.3 Recording Consent
    - One-party consent states: AI can record without disclosure
    - Two-party/all-party consent states (CA, FL, IL, MD, MA, MI, MT, NV, NH, OR, PA, WA): Required disclosure at call start
    - Recommended universal disclosure: "This call may be recorded for quality and training purposes."

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
SECTION 4: AI VOICE CONFIGURATION SPECS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

4.1 Voice Persona Design
    - Name: [Choose a human name that matches your brand — avoid generic names like "Alex"]
    - Voice model: [ElevenLabs Turbo v2 / OpenAI TTS / Bland native / Retell custom clone]
    - Pacing: [120–140 WPM — conversational, not robotic]
    - Filler words: [Allow minimal — "um," "let me check that" increases authenticity 18% per Bland.ai data]
    - Interruption handling: immediate pause + "Sorry — go ahead" acknowledgment
    - Silence detection: 2.5-second pause before prompting continuation
    
4.2 Conversation Flow Configuration
    - Max call length: [3 minutes before escalation offer]
    - Sentiment detection: route to human if negative sentiment score drops below threshold
    - Escalation triggers (transfer to live rep immediately):
      → Prospect asks to speak to a human
      → Meeting booking confirmed (human confirms + sends calendar invite)
      → Legal/compliance mention (lawsuit, regulator, attorney)
      → Existing customer detected (route to CSM queue)
      → High-value target (ACV > $[X] — flag for AE callback same day)
    
4.3 Post-Call Automation
    CRM field population (auto-logged within 60 seconds of call end):
    - Call outcome: [Connected / Voicemail / No Answer / DNC / Wrong Number / Meeting Booked]
    - Sentiment score: [Positive / Neutral / Negative]
    - Objection raised: [dropdown — not interested / have vendor / bad time / send email / interested]
    - Next step: [auto-created task with due date]
    - Call recording URL: [linked to CRM record]
    - Transcript: [AI-summarized, attached to record]
    
    Follow-up sequence trigger:
    - Meeting booked → confirmation email + calendar invite + 24hr reminder
    - Voicemail left → email sent within 2 hours referencing the voicemail
    - Connected / not interested → 30-day suppression, then re-evaluate
    - No answer (3+ attempts) → route to email-only sequence

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
SECTION 5: PERFORMANCE FRAMEWORK
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

5.1 Benchmark KPIs (B2B SaaS, AI voice outbound, 2025)
    - Dial-to-connect rate: 8–15% (varies by segment, call window, caller ID reputation)
    - Connect-to-conversation rate: 60–75% (AI gets past "who is this?" stage)
    - Conversation-to-meeting rate: 4–8% of connects
    - Meeting-to-show rate: 55–70% (AI-booked shows lower than rep-booked; optimize with multi-channel confirm)
    - Meeting-to-opportunity rate: 25–40%
    
5.2 A/B Test Roadmap (prioritized)
    Week 1–2: Test opening hooks (pattern interrupt vs. referential vs. permission-first)
    Week 3–4: Test call timing (Tuesday–Thursday 8–10am vs. 4–6pm local time)
    Week 5–6: Test voicemail vs. no voicemail (impact on callback + email open rates)
    Week 7–8: Test AI persona name + voice model (gendered names, regional accents)
    Week 9–10: Test objection handling variants for top 2 objections
    
5.3 Caller ID Reputation Management
    - Rotate calling numbers across campaigns (avoid single number burnout)
    - Monitor Nomorobo, Hiya, and First Orion flags weekly
    - Use branded caller ID (STIR/SHAKEN attestation) where available
    - Decommission any number flagged as "Spam Likely" within 48 hours

5.4 Weekly Optimization Cadence
    Monday: Pull weekly report — dials, connects, meetings, pipeline $
    Tuesday: Review 5 call recordings — identify script friction points
    Wednesday: Implement 1 script change based on findings
    Thursday: Review caller ID health + compliance log
    Friday: Update A/B test tracker, prep next week's list

CONSTRAINTS:
- All scripts must be ≤ 3 minutes for complete conversations
- No deceptive practices: never deny AI nature when sincerely asked
- All trigger-to-call logic must be documentable for compliance audit
- CRM must be updated within 60 seconds of call completion
- Program must be operable by one marketing operations person (10 hrs/week oversight)
- No cold calls to numbers on state or national DNC lists

OUTPUT FORMAT:
Deliver each section as a standalone operations document. Include exact script language (copy-paste ready), platform configuration screenshots or settings paths where applicable, and decision trees in flowchart-ready format (describe nodes and branches clearly). Flag any sections requiring legal review before deployment.

## Example Input/Output

**Input Example:**

Company: Mosaic Analytics (Series B revenue intelligence platform)
Product: AI-powered revenue forecasting and pipeline analytics for B2B SaaS
ICP: VP of Sales and CRO at SaaS companies with 100–500 employees, $5M–$50M ARR
ACV: $48,000
Platform: Bland.ai
CRM: Salesforce
Intent data: 6sense for Tier 1 triggers
Operating region: US only

**Output Example (Section 2.1 — Opening Scripts):**

*Template A (Trigger-Based — New VP Sales hire detected):*

"Hey Sarah, Alex calling from Mosaic Analytics. I'm reaching out because Cloudify just brought you on as VP of Sales — congrats on that. We work with revenue leaders at SaaS companies like yours to get their forecasts accurate within 5% so they stop missing board calls. Do you have 20 seconds?"

*Template B (6sense intent spike, no specific trigger):*

"Hey Marcus, Alex from Mosaic Analytics — quick one. We specifically work with VPs of Sales at Series B SaaS companies to fix the gap between CRM data and what actually closes. Gong and Clari both use us for their own teams. Am I catching you at a terrible time, or do you have 30 seconds?"

*Voicemail (after 2nd unanswered attempt):*

"Marcus, Alex from Mosaic Analytics. We helped the VP of Sales at Salesloft get their pipeline forecast accurate to within 4% — cut their board prep from 8 hours to 45 minutes. Worth a 15-minute call to see if we can do the same for Cloudify? Call me back at 415-555-0193 or I'll try you Thursday morning. That's Alex from Mosaic."

**Objection Handling — "We already have Clari":**

"Good to know — we actually work alongside Clari in a lot of accounts, and we're also the upgrade path when teams outgrow it. When does your current contract with them renew? [Pause] So [month] — what would Clari need to do between now and then to make it a no-brainer renewal? [Listen] That's exactly the gap we address. Would it be worth 15 minutes before renewal to benchmark what you're getting versus what's possible?"

## Success Metrics

**Program-level KPIs (measure weekly):**
- Dial-to-connect rate: Target ≥ 10%; investigate <7%
- Connect-to-meeting rate: Target ≥ 5%; investigate <3%
- Meeting show rate: Target ≥ 60%
- Pipeline sourced per 1,000 dials: Target ≥ $50K ACV
- Caller ID spam flag rate: Target 0%; pause program if >2% of numbers flagged

**Script quality indicators:**
- Average conversation length ≥ 90 seconds (too short = rejected early)
- Objection-to-redirect conversion ≥ 25%
- Voicemail callback rate ≥ 3%

**Compliance health:**
- DNC complaint rate: 0 (any complaint = immediate program pause + audit)
- AI disclosure response rate: Track % of calls where disclosure is triggered
- Call recording consent error rate: 0

**Business impact:**
- Cost per meeting booked vs. SDR-sourced meetings
- AI voice pipeline-to-close rate vs. other channels
- Revenue attributed to AI voice in CRM (opportunity source field)

## Related Prompts

- [AI-Powered B2B Cold Outreach Sequence Architecture](./AI-Powered-B2B-Cold-Outreach-Sequence-Architecture-&-Multi-Channel-Pipeline-Generation-Intelligence-Engine.md)
- [AI-Powered B2B C-Suite Cold Prospecting](./AI-Powered-B2B-C-Suite-Cold-Prospecting-&-Executive-First-Response-Intelligence-Engine.md)
- [AI-Powered B2B Intent Signal Triggered Outbound](./AI-Powered-B2B-Intent-Signal-Triggered-Outbound-&-Buying-Trigger-Pipeline-Intelligence-Engine.md)
- [AI-Powered B2B Voice AI Lead Response & Speed-to-Lead Conversion](../../04_Demand-&-Lead-Generation-&-Growth/Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Voice-AI-Lead-Response-&-Speed-to-Lead-Conversion-Intelligence-Engine.md)

## Integration Tips

**Bland.ai configuration:**
- Use the `/v1/calls` API endpoint to trigger calls programmatically from CRM workflows
- Set `max_duration: 180` (seconds) to cap conversations at 3 minutes
- Enable `record: true` and pipe recording URLs directly to Salesforce via webhook
- Use `pathway_id` for branching conversation trees built in Bland Pathways UI

**Vapi configuration:**
- Deploy as a `phoneNumberId`-assigned assistant with `firstMessageMode: "assistant-speaks-first"`
- Use `endCallFunctionEnabled: true` to allow AI to gracefully close calls
- Configure `serverUrl` webhook to POST call summaries to your CRM in real time

**Salesforce integration:**
- Create a custom object "AI Voice Call" linked to Lead/Contact records
- Use Zapier or native Salesforce Flow to trigger call campaigns from `Lead Status = MQL`
- Build a Salesforce report: "AI Voice Pipeline by Trigger Source" to prove ROI

**HubSpot integration:**
- Use HubSpot Workflows to enroll contacts in calling sequences based on intent score
- Log calls via HubSpot Calling API (`POST /crm/v3/objects/calls`)
- Create a custom property "AI Voice Outcome" for pipeline attribution dashboards

**Compliance stack:**
- Telnyx or Twilio for number provisioning + STIR/SHAKEN attestation
- DNC.com API for pre-campaign scrubbing (real-time lookup available)
- Nomorobo API to monitor your own numbers for spam flagging

## Troubleshooting

**Problem: Low connect rates (<7%) despite good call timing**
Solution: Check caller ID reputation immediately using Hiya Developer Portal and First Orion. A single "Spam Likely" flag from a major carrier can drop connect rates 40–60%. Rotate to fresh numbers, apply for branded caller ID through TNS/First Orion, and limit daily outbound volume per number to <100 calls to avoid algorithmic flagging.

**Problem: AI conversation sounds robotic; prospects hang up within 10 seconds**
Solution: Enable filler words in your platform settings ("um," "let me think about that"). Reduce speaking pace to 120 WPM max. Add a 300ms pause after the prospect's name before continuing. Test ElevenLabs Turbo v2 voice models against your platform's native voices — most native voices underperform on naturalness benchmarks. A/B test female vs. male voice personas; recent data shows female AI voices receive 12% higher completion rates in B2B outbound.

**Problem: Meetings are booked but show rate is below 50%**
Solution: AI-booked meetings require stronger confirmation sequences than rep-booked. Implement a three-touch confirmation: (1) immediate calendar invite with agenda, (2) email 24 hours before with pre-read material, (3) AI voice reminder call 2 hours before scheduled time. Adding a specific pre-meeting question ("What's the #1 thing you'd want to see in our 15 minutes?") increases show rate by 15–20% by increasing prospect investment.

## Version History
- v1.0: Initial creation (auto-generated)
