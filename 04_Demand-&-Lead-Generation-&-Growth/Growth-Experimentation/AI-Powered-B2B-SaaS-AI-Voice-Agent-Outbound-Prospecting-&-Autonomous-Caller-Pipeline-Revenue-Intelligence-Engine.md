# AI-Powered B2B SaaS AI Voice Agent Outbound Prospecting & Autonomous Caller Pipeline Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** b2b, outbound, voice-ai, ai-agents, pipeline-generation, sales-development, autonomous-prospecting, tcpa, conversational-ai, saas

## Overview
Design and deploy an autonomous AI voice agent outbound prospecting program that dials target prospects, qualifies leads using structured conversations, handles objections, and books meetings with human sales reps — without human involvement per call. Use it when inbound pipeline is insufficient, SDR capacity is capped, outbound economics need improvement, or you want to experiment with AI-first sales development as a scalable, compounding acquisition channel.

## Quick Copy-Paste Version

You are a senior B2B sales development strategist specializing in AI voice agent outbound programs. Design a complete autonomous calling program for my company.

My company: [What we do — one sentence]
Target buyer: [Job title + company size + industry]
Average deal size (ACV): [Annual contract value]
Sales cycle length: [Average days to close]
Current outbound motion: [Cold calling / email-only / no outbound / hybrid SDR model]
Current SDR team size: [Number of SDRs or "none"]
Primary objections prospects raise: [Top 3 objections]
Our strongest proof points: [2–3 specific customer outcomes with numbers]
Compliance geography: [US-only / EU / Global]
CRM: [Salesforce / HubSpot / Other]

Design the following:

1. CALL LIST ARCHITECTURE — Define ICP scoring criteria for AI calling eligibility, lead prioritization tiers (Tier 1/2/3), data enrichment requirements (firmographic, technographic, trigger signals), and call list refresh cadence.

2. CONVERSATION FLOW DESIGN — Write the complete AI voice agent conversation script: opening hook (first 8 seconds), qualification gate (MEDDIC-lite: Pain + Authority + Timeline), value proof delivery, top-3 objection handling sequences, meeting booking close, and graceful disqualification exit.

3. COMPLIANCE FRAMEWORK — Map TCPA consent requirements, DNC list scrubbing process, call time window rules by timezone, mandatory AI disclosure language, opt-out handling, and state-specific restrictions (California, Connecticut, Colorado AI caller laws).

4. HUMAN HANDOFF PROTOCOL — Define triggers for live transfer vs. booked-meeting handoff, the warm transfer script the AI uses, what data gets pushed to the rep's screen at transfer, and fallback routing when no rep is available.

5. TECHNOLOGY STACK RECOMMENDATION — Recommend specific AI calling infrastructure (Bland AI / Retell AI / Vapi.ai / ElevenLabs), voice synthesis, CRM integration, and estimated cost per connected conversation.

6. PERFORMANCE KPIs — Define 6 metrics: dial-to-connect rate, conversation completion rate, qualification rate, meeting booking rate, cost per booked meeting, and AI-attributed pipeline contribution.

Output as numbered sections with ready-to-use scripts, compliance checklists, and a 60-day deployment roadmap with weekly milestones.

## Advanced Customizable Version

# ROLE
You are a world-class AI-powered revenue development architect with 12+ years building outbound prospecting programs at B2B SaaS companies from $5M to $500M ARR, and deep expertise in deploying AI voice agent technology for autonomous sales development. You have built AI calling programs using Bland AI, Retell AI, Vapi.ai, ElevenLabs Conversational AI, and custom LLM-orchestrated voice systems. You understand the fundamental dynamics that determine success in AI voice outbound: the first 8 seconds determine whether a prospect stays on the line (pattern interrupt + instant credibility), qualification must happen conversationally rather than as sequential interrogation, and handoff to human reps must feel seamless rather than mechanical. You have deep expertise in:

- TCPA compliance, STIR/SHAKEN caller ID reputation, and state-level AI disclosure laws (California AB 302, Colorado SB 205, Connecticut PA 23-16)
- Conversation design for LLM-powered voice agents — Retell AI flow nodes, Bland AI pathway builder, VAPI workflow design
- Outbound sequencing strategy — email warm-up before AI dial to increase connect rates 20–35%
- A/B testing AI voice persona, call timing windows, and opening hook variants
- CRM-native lead scoring and intent signal prioritization using Salesforce and HubSpot
- Revenue attribution models for AI-driven pipeline (first-touch, multi-touch, influenced pipeline)
- Human-AI collaboration: when AI should book asynchronously vs. execute a live warm transfer
- Voice psychology for B2B: tone, pacing, and interruption handling that keeps skeptical executives engaged

Your programs are fully autonomous — AI dials, qualifies, and books without per-call human intervention, with human oversight limited to QA review, exception handling, and strategic program optimization.

# CONTEXT

Company & Outbound Profile:
- Company Name: [Company name]
- What You Do: [One-sentence value proposition — outcome-focused, not feature-focused]
- ICP Description: [Job title(s) + company size (employees or ARR range) + industry + geography]
- Target Buying Committee Roles: [Economic buyer title / Technical evaluator title / Champion/end-user title]
- Average Contract Value (ACV): [Annual deal size]
- Sales Cycle Length: [Average days from first contact to close]
- Current Outbound Approach: [Cold email only / mixed calling and email / no outbound / full SDR team with description]
- SDR Team Size & Capacity: [Number of human SDRs, dials/day per rep, current connect rate %, current booking rate — or "no SDR team"]
- Pipeline Target from Outbound: [Monthly or quarterly pipeline goal this program needs to contribute]
- Primary ICP Pain Points: [Top 3 pains your best customers had before buying]
- Top 3 Prospect Objections: [What prospects say to deflect — verbatim if possible]
- Strongest Proof Points: [2–3 specific customer outcomes with numbers — e.g., "Reduced month-end close from 5 days to 6 hours at Acme Corp"]
- Industry Urgency Context: [Regulatory changes, competitive pressures, or market events creating timing urgency]
- Compliance Geography: [US-only / EU-GDPR / UK-PECR / Global — list key markets]
- CRM: [Salesforce / HubSpot / Pipedrive / Other]

Current Tech Stack:
- CRM: [Salesforce / HubSpot / Pipedrive / Other]
- Email Sequencing: [Outreach / Salesloft / Apollo / HubSpot Sequences / Other]
- Data Enrichment: [ZoomInfo / Apollo / Clay / Clearbit / None]
- Phone Dialer (if existing): [Aircall / Dialpad / Gong / Outreach / Other]
- AI Calling Tool (evaluating): [Bland AI / Retell AI / Vapi.ai / ElevenLabs / Other / "Help me choose"]
- Conversation Intelligence: [Gong / Chorus / Clari / None]

# OBJECTIVE
Design a production-ready AI voice agent outbound prospecting program deployable in 60 days that autonomously generates qualified pipeline at a cost-per-booked-meeting economics 3–5× superior to traditional human cold calling, with zero compliance violations and measurable pipeline attribution in CRM.

# CONSTRAINTS
- All conversation scripts must pass the "prospect dignity" test — no high-pressure tactics, no deception about capabilities, no artificial urgency manufacturing
- AI must disclose its AI nature if directly asked; in jurisdictions with mandatory upfront disclosure laws, use transparent opening language ("This is an AI assistant from [Company]")
- TCPA call timing: 8:00am–9:00pm prospect local time only; no Sundays for cold outreach; no federal holidays
- DNC compliance is non-negotiable — scrub against federal DNC registry, applicable state DNC lists, and internal suppression list before every dial trigger
- Qualification threshold must match what a human rep considers an acceptable meeting — do not book unqualified meetings to inflate booking rate metrics
- Any prospect who says "I'd like to speak with a person" must be connected to a human or offered a callback within 30 seconds
- Every AI conversation outcome must be logged in CRM with structured fields — no unlogged call activity

# OUTPUT FORMAT

## Section 1: Call List Architecture & Lead Prioritization

### ICP Eligibility Requirements for AI Calling Pool

**Firmographic Gates (minimum requirements — contact excluded if any are missing):**
- Company size: [Minimum employee count or ARR range]
- Industry: [List qualifying and disqualifying SIC/NAICS codes]
- Geography: [Target geographies, including timezone implications for call window compliance]
- Company health: Active (not in bankruptcy, acquisition freeze, or known operational shutdown)

**Contact-Level Gates:**
- Job title matches Tier 1, 2, or 3 definitions below
- Seniority: [Minimum Manager / Director / VP] level
- Verified direct phone number (not HQ main line without extension) — waterfall enrichment via [ZoomInfo → Apollo → Cognism] until direct dial confirmed
- Prior contact check: No human rep contact in last [X] days, no active opportunity in CRM for this account

**Intent Signal Scoring Matrix (prioritization, not gating):**
| Signal | Score Weight | Data Source |
|--------|-------------|-------------|
| Visited pricing page (last 30 days) | +25 pts | Clearbit/website analytics |
| Downloaded gated content (last 60 days) | +20 pts | Marketing automation |
| Job change at target account (new role <90 days) | +15 pts | LinkedIn / ZoomInfo |
| Competitor customer (technographic signal) | +15 pts | Bombora / ZoomInfo |
| Funding round announced (last 90 days) | +10 pts | Crunchbase / Apollo |
| Actively hiring for relevant roles | +10 pts | LinkedIn Jobs API |
| Conference registration or attendance | +8 pts | Event data integration |
| Opened email in last 14 days (prior sequence) | +5 pts | Email sequencer webhook |

**Calling Priority Tiers:**
| Tier | Score Threshold | Call SLA | Attempt Cadence |
|------|----------------|----------|-----------------|
| Tier 1 | ≥50 pts | AI calls within 4 hours of entering pool | 3 attempts over 5 days |
| Tier 2 | 20–49 pts | AI calls within 24 hours | 2 attempts over 7 days |
| Tier 3 | <20 pts | AI calls within 72 hours | 1 attempt, then route to email-only |

### Call List Refresh Cadence
- **Weekly:** Pull new intent signal triggers — pricing page visitors, new content downloads, job change alerts
- **Bi-weekly:** Re-verify enrichment on contacts in pool >14 days without a connect (re-scrub DNC, re-verify phone)
- **Monthly:** Full ICP re-score of uncontacted pool; archive contacts outside the ICP window or beyond attempt limits
- **Quarterly:** Full database hygiene audit — bounce analysis, title verification, federal + state DNC re-scrub

---

## Section 2: AI Voice Agent Conversation Architecture

### 8-Stage Conversation Flow

**Stage 0 — Pre-Call Automation (no voice, before dial):**
System validates: prospect timezone within 8am–9pm window, DNC status clean, no active CRM opportunity for account, no duplicate call in last 3 days. If any validation fails, reschedule to next eligible window.

**Stage 1 — Opening Hook (Seconds 0–8):**
The first 8 seconds determine whether the prospect stays on the line. No "How are you today?" No "Is now a bad time?" No company pitch. Use the Pattern-Interrupt-Permission formula:

> "[First Name], this is [AI Name], an AI assistant from [Company] — I'll be brief. I'm calling because [specific insight about their company or role that creates curiosity]. Do you have 90 seconds?"

The AI disclosure ("AI assistant") is included upfront — in B2B contexts, transparency increases stay-on-rate because it signals the call is purposeful, not a scam.

*If they say yes → Stage 2. If they say "call me back" or give a specific time → Stage 7 callback scheduling. If they say "no, not interested" → Stage 8 exit.*

**Stage 2 — Context Bridge (10–20 seconds):**
Deliver a single relevant insight that explains why *this specific person* is being called — not a generic pitch.

> "[Specific trigger-based observation — e.g., 'I noticed [Company] recently [grew headcount 40% / closed a Series B / added Salesforce] — companies in that stage typically run into [specific pain we solve] right around now.' Does that resonate with your situation?"

Pause for genuine response. Listen for: pain acknowledgment, curiosity, or deflection. AI adjusts path accordingly.

**Stage 3 — Qualification Gate (45–90 seconds):**
Qualify Pain, Authority, and Timeline in conversational cadence — not as sequential Q&A. Weave questions into dialogue:

- **Pain:** *"What does your current [relevant process] look like — are you managing that through [common inferior alternative] or something else?"*
- **Authority:** *"Are you typically the person who evaluates [category] solutions, or would [peer title] be part of that conversation as well?"*
- **Timeline:** *"Is this something you're actively looking at now, or more on the radar for later this year?"*

**Qualification threshold to proceed to Stage 4:** Pain confirmed as real (not dismissed), authority ≥ influencer level, timeline not explicitly 12+ months out.

**Stage 4 — Value Proof Delivery (30 seconds):**
Two-sentence proof: [Specific customer] + [specific outcome with number] + [connection to their situation].

> *"We helped [Similar Company in same industry/stage] [specific outcome — e.g., 'cut their audit prep time from 4 weeks to 6 days'] within [timeframe]. Given what you described about [their specific pain they mentioned in Stage 3], that's exactly the kind of result we'd expect for [their company type]."*

**Stage 5 — Meeting Ask (15 seconds):**
Offer exactly 2 calendar slots from the assigned rep's live calendar (pulled via API — not generic "sometime next week").

> *"It sounds like a 20-minute conversation would be worth it to see if we can do the same for [Company Name]. I can connect you with [Rep Name] — does [Day, specific time] or [alternate day, specific time] work better?"*

**Stage 6 — Objection Handling Library:**
Pre-built sequences for the 5 most common B2B outbound objections:

**Objection 1: "I'm too busy / this is a bad time"**
> *"Completely understand — that's actually why I keep these short. Most [job title]s I speak with say the same thing, which is exactly why they took the 20-minute call — to see if this could remove some of that burden. Would [specific day 2–3 weeks out] work better than right now?"*

**Objection 2: "We already have something for that"**
> *"Good to know — what are you using? [pause and listen] A lot of our customers came from [Competitor/Category] and weren't planning to switch. The thing that changed their mind was [specific differentiator that's hard to replicate]. Is there anything in your current setup that's still manual or a frustration?"*

**Objection 3: "Send me an email"**
> *"Absolutely — I want to make sure I send you the right one. Is [inferred pain point] the biggest priority, or is it more [alternative pain]?"* [Confirms email address and AI triggers contextually relevant asset delivery immediately via marketing automation]

**Objection 4: "We don't have budget right now"**
> *"Understood — when does your next planning cycle start? [pause] The reason I ask is that [comparable companies] used our ROI documentation in their internal business case to get approval. Even if timing isn't right today, that might be worth a quick look to set you up for the next cycle."*

**Objection 5: "I need to loop in [colleague] before talking"**
> *"That makes sense — is [colleague] typically the [economic buyer / technical evaluator] for this type of decision? [pause] We could structure the intro call to include both of you from the start — that actually tends to move faster than going back and forth. Could you cc them on the invite?"*

**Stage 7 — Callback Scheduling (when prospect can't talk now but is willing):**
> *"No problem at all. What's the best time to reach you? [pause] I'll have our team follow up on [day] at [time] — does [email] work for the confirmation?"*
AI logs callback time in CRM, triggers a human rep task or schedules another AI dial at the specified time.

**Stage 8 — Graceful Disqualification Exit:**
When prospect is outside ICP after qualification:
> *"Based on what you've shared, I don't want to waste your time — it sounds like the timing or fit may not be right for what we do right now. I'll make a note to check back in [X months] when [relevant condition changes]. Thanks for the few minutes."*
AI logs: `outcome: disqualified`, `disqualification_reason: [specific reason]` in CRM. No meeting booked. No follow-up sequence enrolled.

---

## Section 3: Compliance Framework

### TCPA Compliance Architecture (US)

**Federal Requirements:**
- Call window: 8:00am – 9:00pm prospect local time, calculated from area code + ZIP enrichment
- B2B cell phones: TCPA consent requirements apply — verify whether phone number is a business mobile vs. personal mobile; for ambiguous cases, restrict to business hours (9am–5pm) and document the basis
- DNC scrub: National DNC Registry (FTC Telemarketers API) + applicable state registries before every dial trigger — not batch-weekly
- STIR/SHAKEN: Register calling numbers with Hiya, First Orion, and TNS Caller ID registry to prevent "Spam Likely" labeling, which drops answer rates by 60–80%

**AI / Synthetic Voice Disclosure Requirements (as of mid-2025):**
| Jurisdiction | Requirement | Recommended Action |
|---|---|---|
| California | Disclose AI if directly asked; pending stronger upfront disclosure law | Use upfront "AI assistant" disclosure in all CA calls |
| Colorado | Cannot deceive about AI identity | Upfront disclosure recommended |
| Connecticut | Similar to Colorado | Upfront disclosure recommended |
| Texas | Disclosure required for political calls; B2B commercial: emerging guidance | Upfront disclosure as best practice |
| All other US states | No specific AI disclosure law as of mid-2025 | Upfront disclosure still recommended for trust |
| EU (GDPR) | Cannot create false impression of human interaction | Mandatory upfront AI disclosure |

**Recommended Disclosure Language (All Calls — Best Practice):**
> *"Hi [Name], this is an AI assistant from [Company] — I'll keep this short."*

This approach eliminates legal risk, builds trust (B2B decision-makers respect directness), and differentiates the call from spam robocalls. Research shows upfront AI disclosure in B2B contexts does not meaningfully reduce stay-on-rates when the opening hook is strong.

**DNC Compliance Process (Automated):**
1. Real-time FTC National DNC scrub at dial trigger (not weekly batch — dials triggered based on near-real-time scoring)
2. State DNC registry scrub for FL, TX, CA, NY, IN priority calling states
3. Internal suppression list scrub in real-time — CRM `do_not_call = true` flag gates all dial triggers
4. Opt-out propagation SLA: any "remove me" request logged in CRM within 1 hour, suppression propagated to all outbound systems within 24 hours

**GDPR/PECR (EU/UK) Additional Requirements:**
- Document Legitimate Interest Assessment (LIA) before calling EU/UK contacts
- Right to opt-out must be honored immediately; AI says: *"Absolutely — I'll make sure you're removed from our calling list right away"* and triggers suppression
- Call recordings stored in EU-region servers for EU contacts
- Data retention policy for call transcripts: [X] months maximum per data minimization principle

### Call Time Window Rules by Geography
| Region | Window | Notes |
|--------|--------|-------|
| Eastern US | 8:00am – 9:00pm ET | Adjust forward/back 1 hour at DST boundaries |
| Central US | 8:00am – 9:00pm CT | |
| Mountain US | 8:00am – 9:00pm MT | |
| Pacific US | 8:00am – 9:00pm PT | |
| UK | 9:00am – 8:00pm GMT | PECR guidelines |
| Germany / France | 9:00am – 6:00pm local | GDPR legitimate interest + cultural norms |
| No calls | Sundays (all regions) | US federal holidays (all US regions) |

---

## Section 4: Human Handoff Protocol

### Live Transfer Triggers (Immediate Human Connection)
AI initiates warm live transfer when:
1. Prospect explicitly requests human: *"Can I talk to a real person?"* or *"Let me speak with someone on your team"*
2. Prospect qualifies at Tier 1 AND signals high urgency ("We need to solve this in the next 30 days" / "We're in active evaluation right now")
3. Prospect mentions a specific named rep or executive at your company they've previously spoken with
4. Conversation reaches meeting close AND prospect's preferred time is "right now" or "today"
5. Prospect raises a technical, security, or pricing question beyond the AI's defined knowledge scope

**Warm Transfer Script (AI → Rep):**
> *"I have [Prospect First Name] from [Company] on the line — [Rep Name], I'll hand you over now. [Prospect Name], I'm connecting you with [Rep Name] who can go deeper on this."*

**Real-Time Data Pushed to Rep at Transfer (appears on rep's screen via CRM/softphone integration):**
- Prospect name, title, direct phone, company
- Pain point confirmed (verbatim quote from transcript highlight)
- Qualification status — MEDDIC fields: Pain ✓/✗, Authority level (Economic Buyer / Influencer / Champion), Timeline confirmed
- Top intent signals from enrichment (recent web visit, content download, funding round)
- Previous engagement history (emails opened, pages visited, prior conversations logged in CRM)
- Suggested opening line for rep: *"[Name], sounds like [pain point] is the pressing issue for you — [Rep Name] has worked with [similar company] on exactly that."*

### Async Meeting Booking (No Live Transfer)
When prospect agrees to a scheduled meeting:
1. AI offers 2 specific calendar slots (live calendar sync via Calendly Teams API or Chili Piper — not pre-set static times)
2. AI confirms prospect's email address verbally and logs in CRM
3. Calendar invite sends automatically within 60 seconds of booking confirmation
4. AI generates rep prep briefing email: call transcript summary (3 bullet points), qualification signals confirmed, objections raised, 2 suggested prep questions
5. Automated meeting reminder sequence fires: 72-hour email from rep's name, 24-hour email with agenda, 1-hour text (if mobile consent exists)

### Fallback Routing (No Rep Available for Live Transfer)
When transfer is triggered but all reps are unavailable (after-hours, all lines occupied):
> *"[Rep Name] is on another call right now — I want to make sure you get the right person, not a voicemail. Could I have them call you back within the next [15/30] minutes? Or I can grab time on their calendar right now — either way works for me."*

If prospect prefers callback: AI logs `callback_requested = true` + callback time, creates urgent CRM task for rep with high-priority flag, sends rep SMS notification.
If prospect prefers calendar: AI books directly, same as async flow above.

---

## Section 5: Technology Stack

### AI Calling Platform Comparison

**Bland AI — Best for: complex conversation flows, high call volume, US-focused B2B**
- Conversation engine: Visual pathway builder — define conversation branches as flowchart nodes; no coding required
- Voice: Multiple voice options including custom voice cloning to match brand persona
- Integrations: Native HubSpot/Salesforce connectors, webhook support for custom CRM
- Compliance features: Built-in TCPA call time validation, DNC integration support
- Pricing: ~$0.09–$0.12/minute (connected conversation minutes only)
- Best fit: Revenue teams wanting no-code deployment with enterprise reliability

**Retell AI — Best for: engineering-led teams, custom LLM control, multimodal future-proofing**
- Conversation engine: Real-time LLM integration — supports Claude, GPT-4o, custom fine-tuned models; allows dynamic conversation logic beyond static pathways
- Voice: ElevenLabs, Deepgram, Azure Speech — choose per use case
- Integrations: REST API + webhooks; built-in CRM webhooks; Zapier-compatible
- Pricing: ~$0.07–$0.11/minute + LLM inference costs (~$0.01–$0.03/conversation)
- Best fit: Companies wanting full control over conversation intelligence and LLM behavior

**Vapi.ai — Best for: fastest deployment, multilingual, API-first architecture**
- Conversation engine: VAPI workflow nodes with robust interruption handling and latency optimization
- Voice: Provider choice — Deepgram, ElevenLabs, Azure; sub-500ms response latency
- Integrations: Zapier/Make native connectors + full REST API
- Pricing: ~$0.05–$0.08/minute
- Best fit: Companies wanting rapid MVP deployment and multilingual support (EU expansion, LATAM)

### Recommended Full Stack for Most B2B SaaS Companies
| Component | Primary Recommendation | Alternative |
|-----------|----------------------|-------------|
| AI calling infrastructure | Bland AI | Retell AI |
| Voice synthesis | ElevenLabs (custom cloned voice) | Azure Cognitive Speech |
| Phone carrier | Twilio | Bandwidth |
| Number reputation management | Hiya + First Orion | TNS Caller ID |
| Lead enrichment | Clay (multi-source waterfall) | Apollo.io + ZoomInfo |
| DNC scrubbing | Thomson Reuters TCPA | FTC DNC API (federal only) |
| CRM integration | Native connector | Zapier / Make |
| Calendar booking | Calendly Teams API | Chili Piper |
| Call transcript review | Gong (via webhook) | Fireflies.ai |

### Unit Economics Benchmarks
| Metric | AI Voice Program | Human SDR Cold Call |
|--------|-----------------|-------------------|
| Dials per hour | 40–80 (concurrent) | 8–15 |
| Connect rate | 8–15% | 4–8% |
| Cost per connected conversation | $0.20–$0.50 | $15–$25 (fully loaded SDR) |
| Qualification rate from connects | 20–35% | 25–40% |
| Meeting booking rate from qualified | 40–60% | 50–65% |
| **Cost per booked meeting** | **$15–$60** | **$150–$400** |

---

## Section 6: 60-Day Deployment Roadmap

**Days 1–10: Foundation**
- Days 1–3: Select AI calling platform, configure trial account, provision phone numbers, verify STIR/SHAKEN registration
- Days 4–6: Build initial conversation flow — opening hook, qualification gate, top-3 objection handlers, meeting close; write 2 A/B variant openings to test
- Days 7–8: CRM integration — map call outcomes to structured CRM fields, configure webhook-to-CRM activity logging, set up rep prep briefing automation
- Days 9–10: Compliance infrastructure — DNC scrub API integration, call time window validation by timezone, legal review of disclosure language and opt-out handling

**Days 11–20: Controlled Pilot**
- Days 11–12: Build first call list — 100-contact Tier 1 pilot pool, full Clay/Apollo enrichment, complete DNC scrub
- Days 13–14: Internal QA — team listens to AI demo calls against internal volunteers, calibrate voice speed/tone, refine opening hook based on gut reaction
- Days 15–20: Live pilot — 100 contacts called in batches of 20/day, real-time monitoring of call recordings, document every objection heard for script iteration

**Days 21–35: Iterate & Optimize**
- Day 21: Pilot retrospective — review connect rate, conversation completion rate, qualification rate, and any booked meetings (expect 2–5 from 100-contact pilot)
- Days 22–25: A/B test opening hook variants (Test A: direct value hook vs. Test B: curiosity-gap/insight hook); route 50 contacts to each
- Days 26–30: Expand to 500-contact call list, enable Tier 2 prioritization, activate calendar auto-booking
- Days 31–35: First rep feedback loop — 30-minute session where reps review 3 AI call transcripts, calibrate on what they'd accept as a qualified meeting

**Days 36–50: Scale**
- Days 36–40: Launch email warm-up sequence (2 emails sent 5 and 2 days before AI dial) — increases connect rate 15–25% by warming the contact
- Days 41–45: Enable live transfer capability — wire to rep phone system or Aircall/Dialpad queue for Tier 1 qualifications
- Days 46–50: Expand to full ICP calling pool, automate weekly call list refresh from CRM intent scoring + Clay enrichment

**Days 51–60: Steady-State Operations**
- Days 51–55: Build pipeline attribution dashboard in CRM — AI-called pipeline by stage, cost per booked meeting, meeting-to-opportunity conversion rate, AI-influenced ARR
- Days 56–58: Establish weekly QA cadence — random sample of 5 call transcripts reviewed by sales leader; conversation quality scored on rubric (1–5)
- Days 59–60: 60-day program review — ROI vs. human SDR baseline, decision on headcount reallocation, Q2 optimization roadmap

---

## Section 7: Performance Metrics Dashboard

| Metric | Definition | Measurement Method | Industry Benchmark | 90-Day Target |
|--------|-----------|-------------------|--------------------|--------------|
| Dial-to-Connect Rate | % of dials resulting in live conversation (not voicemail/no-answer/hangup in <3 sec) | AI platform analytics | 8–15% | ≥12% |
| Conversation Completion Rate | % of connects that reach qualification outcome (not immediate hang-up in first 10 sec) | Platform analytics | 40–60% of connects | ≥55% |
| Qualification Rate | % of completed conversations where prospect meets defined ICP threshold | CRM + platform webhook | 20–35% of completed | ≥25% |
| Meeting Booking Rate | % of qualified conversations resulting in booked calendar meeting | CRM calendar integration | 40–60% of qualified | ≥45% |
| Meeting-to-Opportunity Rate | % of AI-booked meetings that convert to qualified pipeline opportunity | CRM stage tracking | 50–70% | ≥55% |
| Cost Per Booked Meeting | Total program cost (platform + infrastructure + list) ÷ meetings booked | Finance + platform analytics | $15–$60 target | ≤$40 |

### Secondary QA Metrics (Weekly Review)
- Average conversation length in minutes (target: 2.5–4 minutes for qualified conversations)
- Voicemail leave rate — % of no-answers where AI leaves a structured voicemail (recommended: leave voicemail on 1st and 3rd attempts only)
- Opt-out rate — should stay below 2% of connects; above 3% signals script is too aggressive or list quality is poor
- AI disclosure stay-on-rate — when AI discloses "AI assistant" upfront, % that continue conversation (benchmark: 65–80% for well-executed hooks)
- Rep quality rating for AI-booked meetings — 1–5 scale scored by rep after attending meeting; target ≥3.8/5.0 average

---

## Example Input/Output

**Input Example:**
- Company: Streamline — a B2B SaaS financial operations platform for CFO teams at Series B–D startups ($5M–$50M ARR)
- Target buyer: VP Finance or CFO at 50–500 employee SaaS companies
- ACV: $28,000/year
- Sales cycle: 45 days average
- Current outbound: 2 human SDRs; 5% connect rate, 8 booked meetings/month total
- Primary objections: "Spreadsheets work fine for us," "I need to loop in my CEO before any new tools," "We just closed a round and aren't focused on new software"
- Top proof points: "Cut audit prep from 4 weeks to 6 days for a 200-person SaaS company," "CFO at Bolt used Streamline to get board-ready reporting without hiring a controller"
- Compliance: US-only

**Output Example (abbreviated):**

---

**Call List Architecture — Streamline:**

Tier 1 (AI calls within 4 hours): VP Finance or CFO at 50–500 employee SaaS company + score ≥50.

Top qualifying signals: Just closed Series B/C funding (+10) AND using Excel/Google Sheets for finance function (technographic signal via BuiltWith/ZoomInfo, +20) AND job change in last 90 days (+15) AND visited Streamline pricing page in last 30 days (+25).

---

**Opening Hook — Streamline:**
> "Hi [Name], this is an AI assistant from Streamline — I'll be quick. I noticed [Company] just closed your Series [B/C], and finance teams at that stage usually hit a wall around month-end close and board deck prep. Does that sound familiar?"

*(Pattern interrupt: specific to their funding milestone. Permission-ask implied by pausing for response.)*

---

**Objection: "Spreadsheets work fine for us"**
> "That's what almost every CFO says before their first post-Series B board meeting takes 3 days instead of half a day. What does your current close process look like — how many days end-to-end?"
*(Reframes objection as future risk, asks diagnostic question to uncover latent pain)*

---

**Program Economics Projection:**
- AI dials 2,000/month → 220 connects (11%) → 66 qualified (30%) → 30 meetings (45% booking rate)
- Plus human SDR team refocuses from cold calling to follow-up on AI-qualified prospects: +10 additional meetings
- **Total: ~40 meetings/month vs. current 8 — 5× increase at ~$35 cost per AI meeting**

---

## Success Metrics

- **Dial-to-booked-meeting rate ≥1.5%** (15+ meetings per 1,000 dials): AI program is generating pipeline at efficient volume
- **Meeting-to-opportunity conversion ≥50%**: AI is booking qualified meetings, not inflating vanity metrics with unqualified meetings
- **Cost per booked meeting ≤$50**: AI outperforms human cold calling economics (typical human SDR: $150–$400/meeting)
- **Rep quality rating ≥3.8/5.0**: Human reps find AI-booked meetings valuable and arrive well-prepared
- **Opt-out rate <2% of connects**: AI respects prospect dignity and does not create brand damage
- **Zero TCPA violations in 90 days**: Program operates within all applicable calling regulations

## Related Prompts

- [`../Email-Marketing-&-Nurturing/AI-Powered-B2B-Autonomous-AI-SDR-Program-Architecture-&-Outbound-Pipeline-Intelligence-Engine.md`](../Email-Marketing-&-Nurturing/AI-Powered-B2B-Autonomous-AI-SDR-Program-Architecture-&-Outbound-Pipeline-Intelligence-Engine.md) — Combine AI voice with AI email sequencing for true multichannel autonomous outbound
- [`../Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Voice-AI-Lead-Response-&-Speed-to-Lead-Conversion-Intelligence-Engine.md`](../Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Voice-AI-Lead-Response-&-Speed-to-Lead-Conversion-Intelligence-Engine.md) — Deploy inbound AI voice agents on demo requests and form fills to complement outbound calling
- [`../../05_Analytics-&-Performance/Demand-Generation-Program-Analytics/AI-Powered-B2B-SaaS-AI-SDR-Program-Analytics-&-Outbound-Revenue-Contribution-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Demand-Generation-Program-Analytics/AI-Powered-B2B-SaaS-AI-SDR-Program-Analytics-&-Outbound-Revenue-Contribution-Intelligence-Engine.md) — Measure AI-driven pipeline contribution with full revenue attribution reporting
- [`../../02_Product-Marketing/Sales-Enablement/AI-Powered-B2B-SaaS-Customer-Reference-Program-Architecture-&-Sales-Proof-Automation-Intelligence-Engine.md`](../../02_Product-Marketing/Sales-Enablement/AI-Powered-B2B-SaaS-Customer-Reference-Program-Architecture-&-Sales-Proof-Automation-Intelligence-Engine.md) — Equip AI voice agents with proof points from customer references to increase qualification-to-booking conversion

## Integration Tips

- **Salesforce:** Create a custom Activity Type "AI Outbound Call" in Salesforce. Map call outcomes (Connected-Qualified, Connected-Not-Qualified, Voicemail-Left, Opted-Out, Callback-Scheduled) as structured Activity records with custom fields: `ai_call_pain_summary` (text), `ai_call_qualification_tier` (picklist), `ai_call_objection_raised` (text). Build a report grouping AI-called pipeline by source, qualification tier, and assigned rep to track program ROI.

- **HubSpot:** Use the HubSpot Engagement API to log AI calls as "Call" engagements on Contact records. Set up a HubSpot Workflow: trigger = `ai_call_outcome = qualified` → creates a rep Task ("Follow up with AI-qualified prospect"), sends rep an internal email with call summary, and enrolls prospect in a "Post-AI-Call" email sequence if meeting not yet booked.

- **Clay:** Build AI calling lead lists directly in Clay — pull contacts from Apollo, enrich with LinkedIn data, add technographic signals from BuiltWith, score with custom formulas, waterfall-enrich phone numbers (ZoomInfo → Apollo → Cognism), then push enriched, scored, DNC-scrubbed contacts to your calling platform via Clay's CRM push. Automate this list build to run weekly with new intent signal inputs.

- **Calendly Teams / Chili Piper:** Connect your AI calling platform to Calendly via REST API — AI calls the Calendly availability endpoint in real-time during Stage 5 to offer exactly 2 live slots from the assigned rep's actual calendar. When a meeting is booked via AI, Calendly webhook triggers automatically create a CRM Opportunity in the deal stage "Meeting Scheduled" — eliminating manual SDR data entry.

- **Zapier / Make:** Automate opt-out propagation — when AI call logs `outcome = opted_out`, a Zap immediately: (1) sets CRM contact field `do_not_call = true`, (2) removes contact from calling platform's active pool, (3) unsubscribes from all email sequences, (4) adds to internal DNC database with timestamp. Entire opt-out cycle completes in <5 minutes with zero manual steps.

- **Gong:** Connect your AI calling platform's transcript webhook to Gong's API — AI call transcripts appear in Gong alongside human call recordings. Sales leaders can run AI call quality scoring using Gong's Conversation Intelligence (track keywords, pain points mentioned, objection frequency), and compare AI-booked meeting quality scores against human SDR bookings using the same rubric.

## Troubleshooting

**Problem: Connect rate is below 6% — AI is rarely reaching prospects even at optimal call times.**
Solution: Low connect rate in AI calling has three primary causes: (1) *Caller ID reputation* — check if your numbers are marked "Spam Likely" using Hiya's free spam check tool. If flagged, register calling numbers with Hiya Protect, First Orion, and TNS Caller ID Registry ($50–$200/month) to restore clean status. Implement local presence calling (match number's area code to prospect's area code) — this alone increases B2B answer rates 40–60%. (2) *Call timing* — the highest-connect windows for B2B are Tuesday–Thursday between 8:00–9:30am and 4:00–5:30pm prospect local time; test moving from midday dials to morning/end-of-day windows. (3) *List quality* — if direct dials are actually HQ switchboard numbers, answer rates plummet. Run your list through a phone validation service (NeverBounce Phone, Telnyx Lookup) to flag lines likely to be answered vs. voicemail-only numbers.

**Problem: Meeting show rate is below 45% — prospects are booking but not attending AI-scheduled meetings.**
Solution: AI-booked meetings have higher no-show risk than human-booked meetings because the prospect had lower emotional investment in a 2-minute conversation than a 15-minute human call. Fix with a three-touch confirmation protocol: (1) Send a 72-hour reminder email FROM the assigned rep's personal email address (not noreply@), including the rep's headshot and one personalized sentence referencing what the AI call discussed — the human element dramatically reduces no-shows; (2) Send a 24-hour email with a 3-bullet agenda and 1 prep question to prime the prospect's thinking (primed prospects show up and are more engaged); (3) If mobile consent exists, send a 1-hour "looking forward to it" text from the rep's number. Implementing this sequence typically increases show rates from 45% to 65–75% within 30 days.

**Problem: Reps are skeptical of AI-booked meeting quality and underpreparing for calls.**
Solution: This is a rep adoption problem, not an AI quality problem — reps who haven't heard the qualification conversation tend to undervalue it. Two fixes that work: (1) Run a bi-weekly 20-minute "AI call transcript review" where the team listens together to 3 randomly selected AI call recordings — after hearing the actual qualification conversation, reps consistently rate meeting quality higher than they expected; (2) Require reps to complete a 30-second CRM pre-meeting prep checklist ("Top objection I expect," "Proof point I'll lead with") using the AI-provided call summary as input — reps who use the summary to prepare close AI-booked deals at rates equal to or higher than human-SDR-booked deals within 60 days. Track meeting-to-opportunity conversion by rep and share top performers' preparation process in team standup.

## Version History
- v1.0: Initial creation (auto-generated)
