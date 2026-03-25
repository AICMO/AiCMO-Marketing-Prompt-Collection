# AI-Powered Conversational Marketing & Chatbot Lead Qualification Intelligence Engine - Convert Anonymous Website Visitors Into Pipeline-Ready Leads Through AI Chat

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** conversational-marketing, chatbot, lead-qualification, inbound, b2b, demand-gen, ai-automation, drift, intercom, hubspot-chat, pipeline

## Overview
Designs a complete AI-powered conversational marketing system that replaces static forms with dynamic chat flows, qualifies leads in real time using BANT + intent signals, routes hot prospects to sales instantly, and nurtures everyone else automatically. Use this when your website converts below 2%, demo request forms get abandoned, or you want to capture pipeline from buyers who won't fill out a 7-field form but will answer 3 questions in a chat window.

## Quick Copy-Paste Version

You are a senior B2B demand generation strategist specializing in conversational marketing, AI chatbots, and real-time lead qualification. I need to build an AI-powered conversational marketing system for my website that turns anonymous visitors into qualified pipeline.

My context:
- Company: [e.g., Vanta — B2B SaaS for automated security compliance]
- ICP: [e.g., CTO, VP Engineering, and Security leads at SaaS companies with 50-500 employees]
- Core product: [e.g., Automated SOC 2 and ISO 27001 compliance platform]
- Average deal size: [e.g., $28,000 ARR]
- Monthly website visitors: [e.g., 45,000 unique visitors/month]
- Current conversion rate: [e.g., 1.8% visitor-to-demo-request]
- Chat platform: [e.g., Drift / Intercom / HubSpot Conversations / Qualified.com]
- CRM/MAP stack: [e.g., Salesforce + HubSpot Marketing Hub]
- Sales team structure: [e.g., 8 AEs covering SMB and mid-market; SDR team of 5]

Please deliver a complete Conversational Marketing & Chatbot Lead Qualification System:

1. VISITOR SEGMENTATION & CHAT TRIGGER ARCHITECTURE
   - Rules for when and where to trigger the chatbot: high-intent pages (pricing, demo, solutions), returning visitors, known accounts from 6sense/RB2B/Clearbit Reveal, vs. first-time anonymous visitors
   - Audience-specific chat playbooks: ICP company visiting → route to instant meeting booking; competitor customer visiting → fire competitive displacement chat; existing customer visiting → suppress demo bot, show CS bot
   - Timing and trigger logic: seconds-on-page, scroll depth, exit intent, number of sessions — the specific thresholds that indicate genuine intent vs. accidental visits
   - Suppress logic: never trigger on careers pages, legal pages, or for known contacts already in an active deal

2. LEAD QUALIFICATION CONVERSATION FLOWS
   - Design 3 core chat flows: (a) Inbound Demo Request flow, (b) Pricing Page Visitor flow, (c) General Website Visitor flow
   - Each flow must qualify BANT in ≤5 conversational turns using natural language (not "What is your budget?" — use "How many employees are you trying to bring into compliance?")
   - Branching logic: if visitor says they're an individual/student → gracefully exit to blog resources; if they reveal a pain point that matches your ICP → accelerate to booking
   - AI-powered free-text intent classification: when visitor types a free-form message, classify intent into: [Evaluating now / Just researching / Need a specific feature / Competitor comparison / Pricing only] and route accordingly

3. REAL-TIME ROUTING & SALES HANDOFF ORCHESTRATION
   - Hot lead routing rules: define the exact signals that trigger "pull in a live sales rep NOW" vs. "book a meeting" vs. "enroll in automated sequence"
   - Rep availability management: primary, secondary, and fallback routing so no hot lead ever gets an "all agents busy" dead-end
   - Instant meeting booking integration: embed calendar directly in chat for qualified leads; offer next-day slots with specific rep names (personalization lifts booking rates 31%)
   - Handoff briefing: auto-generate a 3-bullet context card for the incoming sales rep showing: who they are, what they clicked, what they said, their firmographic profile from enrichment

4. BOT CONVERSATION COPYWRITING
   - Write the exact opening messages, question sequences, and branching responses for each of the 3 core flows above
   - Tone calibration: match your brand voice (enterprise = formal, PLG SaaS = conversational, developer tools = technically fluent)
   - Objection handling scripts: when a visitor says "just browsing," "not ready to talk to sales," or "send me an email" — specific deflection responses that keep them engaged without being pushy
   - Closing micro-CTAs: 5 specific formulations that convert chat conversations into meeting bookings, trial activations, or content downloads

5. CHAT ANALYTICS & CONVERSION OPTIMIZATION
   - KPI framework: 8 metrics to track beyond "conversations started" — qualification rate, routing accuracy, meeting-booked-to-show rate, chat-to-pipeline conversion, and avg. days-to-opportunity from chat
   - A/B testing plan: 4 high-leverage experiments for chat (opening message, bot avatar, question sequence, CTA at close)
   - Chat session replay analysis: what to look for in failed conversations — where do visitors drop off, what questions cause hesitation, which answers trigger "disqualified" routes incorrectly

6. ENRICHMENT & CRM INTEGRATION
   - Data flow: how every chat interaction (regardless of whether the visitor provides their email) should generate a de-anonymized company signal using Clearbit Reveal / 6sense / RB2B
   - Progressive identity resolution: how to stitch anonymous chat sessions to known CRM contacts when they later convert elsewhere
   - CRM record creation rules: what triggers a new Contact vs. updating an existing one; how to log chat transcripts as Activities; which chat fields map to CRM properties for lead scoring

Output in structured markdown. Include specific conversation scripts, not just frameworks — I need copy I can paste into Drift/Intercom today.

## Advanced Customizable Version

ROLE: You are a B2B revenue marketing architect with 15+ years of experience building conversational marketing systems, chatbot lead qualification engines, and real-time pipeline capture programs for SaaS companies from Series A through enterprise. You have built and optimized chat programs on Drift, Intercom, Qualified.com, and HubSpot Conversations. You understand the psychology of buyers who visit websites but avoid forms, the technical architecture of bot-to-human routing, and the CRM hygiene requirements that make chat data actually useful in revenue reporting. You know the exact tipping points where a chatbot feels helpful vs. intrusive, and you can calculate the pipeline impact of each routing decision.

CONTEXT:
Company: [Company name and 1-sentence description]
Stage: [Seed/Series A/Series B/Series C/Enterprise]
ICP (primary): [Job title, company size, industry, key buying trigger]
ICP (secondary): [If applicable]
Product category: [Your market category]
ACV/Deal size: [Average annual contract value]
Sales cycle: [Average days from first touch to close]
Monthly website visitors: [Unique visitors/month]
High-intent pages: [List your pricing, demo, solutions, comparison pages by URL or name]
Current visitor-to-conversion rate: [% of visitors who fill a form or book a meeting]
Chat platform: [Drift / Intercom / HubSpot Conversations / Qualified.com / Freshchat / custom]
Intent data vendor: [6sense / Bombora / RB2B / Clearbit Reveal / G2 Buyer Intent / None]
CRM: [Salesforce / HubSpot CRM / Pipedrive]
MAP: [HubSpot / Marketo / Pardot / None]
Sales team structure: [How many AEs/SDRs, territory or segment model, hours of coverage]
Current chat performance: [If live: conversations/month, qualification rate, pipeline attributed — or "not yet deployed"]
Brand voice: [Formal / Conversational / Technically-fluent / Startup / Enterprise]
Key differentiators: [Top 3 reasons customers choose you over competitors]

OBJECTIVE: Build a complete conversational marketing and AI chatbot lead qualification system that:
1. Captures pipeline from the 98%+ of website visitors who leave without filling a form
2. Qualifies leads in ≤5 conversational turns using BANT + behavioral intent signals
3. Routes hot leads to live reps or instant booking in under 90 seconds
4. Enriches every conversation — even anonymous ones — with firmographic intelligence
5. Feeds clean, structured data into CRM that powers revenue reporting and lead scoring

FRAMEWORK: CONVERSATIONAL PIPELINE CAPTURE SYSTEM

MODULE 1: VISITOR SEGMENTATION & INTELLIGENT CHAT TRIGGER ARCHITECTURE

Trigger Layer 1 — Account-Level Intent Signals (Highest Priority):
Apply this logic BEFORE any page-based trigger, using your intent data vendor:

□ Known ICP Account in-market (6sense/Bombora Stage: Decision or Purchase):
  → Trigger: Proactive chat with account-specific personalization within 5 seconds of landing
  → Message: "Hey [Company Name] team — I noticed you're looking into [Category]. We work with [3 similar companies]. Want a 15-minute comparison walkthrough?" 
  → Route: Skip bot qualification; connect directly to assigned AE or top-of-rotation SDR
  → Priority: P1 (escalate immediately, even if rep must interrupt another call)

□ Known Account — Active Opportunity in CRM (any stage):
  → Suppress: All lead-gen bots
  → Trigger: CS or AE-branded chat: "Hi, this is [Assigned Rep Name] — happy to answer any questions about your evaluation."
  → Route: Notification to deal owner; do not auto-qualify, do not auto-book

□ Known Competitor Customer (identified via email domain or 6sense technographic):
  → Trigger: Competitive displacement chat playbook (see Module 2, Flow D)
  → Message opens with competitor pain point empathy, not a product pitch
  → Route: SDR with competitive displacement training; attach competitive battlecard to handoff note

□ Anonymous Visitor — High-Intent Page (pricing, demo, compare, ROI calculator):
  → Trigger: After 15 seconds on page OR 60% scroll depth, whichever comes first
  → De-anonymize via Clearbit Reveal/RB2B: identify company name and industry from IP
  → Personalize opening based on industry if available; generic if not
  → Route: Standard qualification flow (Module 2, Flow A or B based on page)

□ Anonymous Visitor — Educational Content Page (blog, guides, webinars):
  → Trigger: Exit-intent only (cursor moves toward browser chrome)
  → Offer: Content upgrade or newsletter signup — NOT a demo push
  → Route: Email capture → nurture sequence; do not hand to sales

□ Known Contact — No Open Opportunity (visited in last 90 days, no deal):
  → Trigger: On return visit to any high-intent page
  → Pre-populate name from CRM: "Welcome back, [First Name] — anything specific you're trying to figure out today?"
  → Route: Re-engagement qualification flow; check if previous disqualification reason has changed

Suppress Logic (never trigger any bot):
□ Careers, Legal, Privacy, Support, Status pages
□ Internal traffic (office IP ranges)
□ Existing paying customers (identified by email domain in customer list)
□ Contacts with "Do Not Contact" flag in CRM
□ Visitors who have dismissed the chat 3+ times in the last 30 days (bot fatigue)

MODULE 2: LEAD QUALIFICATION CONVERSATION FLOWS

Design Principles for Conversational Qualification:
□ Never ask more than 5 questions before offering value (a next step, a resource, or a meeting)
□ Use soft language that implies collaboration, not interrogation: "What are you trying to figure out?" beats "What is your use case?"
□ Every question must have a business reason — and the visitor should feel they're being helped, not screened
□ Branch immediately when disqualified — don't string along non-ICP visitors
□ End every conversation with a clear next step, even for nurture-track visitors

FLOW A: HIGH-INTENT PAGE VISITOR (Pricing / Demo Request / Solutions page)
This visitor is in active evaluation mode. Goal: qualify and book in ≤3 minutes.

Turn 1 — Opening (triggered at 15s on page or 60% scroll):
"Hey there! Are you exploring [Product Category] for your team, or just doing some research?"
→ If "for my team" → Turn 2A (qualification)
→ If "just researching" → Turn 2B (nurture path)
→ If no response in 45 seconds → auto-follow: "No worries — if you have any questions about [specific pricing tier they're viewing] or want to see how we work with [auto-detected industry], just ask."

Turn 2A — Qualification (scale signal):
"Totally — happy to help. How large is the team or organization you're thinking about?"
→ < [minimum viable company size]: "Got it! We're best suited for teams of [X]+, but [lower-tier offer / free trial / PLG path] might be a great fit. Want me to send you a link?"
→ In ICP range → Turn 3A
→ > enterprise threshold → flag as enterprise, route to enterprise AE

Turn 3A — Timeline & urgency:
"And is this something you're actively looking to get in place in the next [quarter / 90 days], or still in early scoping?"
→ "Actively evaluating" → Turn 4A (booking)
→ "Early scoping" → Turn 4B (content offer + nurture)
→ "We have a deadline" → Turn 4A with urgency flag in routing

Turn 4A — Meeting booking (for active evaluators):
"Perfect — it would make sense to spend 20 minutes with one of our team members who works with [their industry/size] companies like [relevant customer name]. Does [specific day, e.g., Thursday] work, or would you prefer to pick a time that's convenient?"
→ Embed calendar widget inline
→ If they book → confirm + deliver prep email with 3 questions AE will ask + what to expect
→ If they hesitate → "What's holding you back? I can connect you with a quick 10-minute intro instead — no pitch, just questions."

Turn 4B — Nurture path (for researchers):
"Totally fine — would it be useful if I sent you [Relevant Resource: ROI calculator / benchmark report / comparison guide] so you have something concrete to evaluate later?"
→ Email capture → enroll in intent-based nurture sequence (not generic drip)
→ Trigger: When this contact returns to high-intent page → skip turns 1-3, go straight to Turn 4A

FLOW B: PRICING PAGE SPECIFIC
Pricing page visitors have already self-selected as evaluators. Accelerate.

Turn 1 (trigger at 10s, no scroll-depth wait):
"Comparing options? Happy to walk you through what's included at each tier — or if you tell me your team size and use case, I can point you to the right one in about 60 seconds."

Turn 2 — Intent classification based on response:
→ Asks about specific feature → answer directly, then: "That feature's in our [tier]. Want to see a 10-min demo focused on that?"
→ Mentions competitor → activate competitive playbook (see Flow D)
→ Asks about custom pricing → route to enterprise AE: "For teams [above threshold], we do custom pricing — let me get you in front of the right person."
→ Silent → follow up at 60s: "Pricing can be confusing. What would make it clearer — a tier comparison doc, or a quick walkthrough?"

FLOW C: GENERAL WEBSITE VISITOR (Homepage / Blog / Resource pages)
These visitors are in awareness mode. Goal: capture email, not book a meeting. Don't over-qualify — you'll lose them.

Turn 1 (exit-intent only):
"Before you go — are you exploring [Category] for the first time, or coming back to dig deeper?"
→ First time → offer a high-value resource: "[Resource Title] might be a good starting point — want me to send it over?"
→ Coming back → "What brought you back? I can pull up the right resource or connect you with someone on the team."

Turn 2 — Soft email capture:
"Where should I send it? Just your work email and I'll get it over."
→ Personal email → "Just to make sure you get the [company-specific benchmark/analysis] — do you have a work email? No pressure if not."
→ Business email → confirm + enroll in nurture → set re-engagement trigger for return to high-intent page

FLOW D: COMPETITIVE DISPLACEMENT (Known competitor customer)
Turn 1 — Open with empathy, not product:
"Hey — I noticed [Competitor Name] customers are visiting us a lot lately. What's making you look around?"
→ This question converts 3-4× better than "Want to see a demo?" for competitor visitors because it meets them in their frustration
→ Listen for: pain with specific feature, pricing, support, compliance gap, scalability issue
→ Route: competitive displacement-trained SDR with relevant battlecard + ROI of switching calculator pre-loaded

MODULE 3: REAL-TIME ROUTING & SALES HANDOFF ORCHESTRATION

Routing Priority Matrix:

Priority 1 — Live Rep NOW (response target: <90 seconds):
Trigger conditions (all three must be true):
□ Visitor is from an ICP-match company (size, industry, title confirmed or inferred)
□ Timeline is "actively evaluating" or "have a deadline"
□ High-intent page visited (pricing, demo, compare)
Action:
□ Push Slack alert to available rep: "[Company Name] | [Industry] | [Size] — on pricing page, says evaluating now. Pick up the chat."
□ Rep joins chat within 60s; bot stays live with filler messages if rep is delayed ("Let me get the right person to help — they'll be with you in under a minute")
□ If no rep responds in 90s → auto-offer calendar embed; log as "missed live routing" for ops review

Priority 2 — Instant Meeting Booking (book now, talk later):
Trigger conditions:
□ ICP-match company + active timeline but rep unavailable
□ ICP-match company + active timeline but visitor preference is "prefer email/async"
□ Any visitor who explicitly says "schedule a call"
Action:
□ Embed rep-specific calendar inline (round-robin or account-assigned depending on CRM routing rules)
□ Pre-fill name and company on calendar form using data already collected in chat
□ Post-booking: auto-send a prep email: "Here's what to expect in your [20-min / 30-min] call — and 3 questions [Rep Name] will ask so you can come prepared"
□ 24-hour reminder with LinkedIn profile of the rep (personalization reduces no-show rate by 18%)

Priority 3 — SDR Follow-Up Within 2 Hours (for qualified leads who don't book):
Trigger conditions:
□ Completed qualification chat, ICP match, but did not book
□ Left email but exited before booking
Action:
□ SDR receives Slack notification with full chat transcript + firmographic profile
□ SDR outreach template pre-loaded: reference specific thing they said in chat ("You mentioned you're evaluating [X] — that's exactly what [Customer Name] was solving when they first came to us")
□ 2-hour SLA enforced via CRM task with manager visibility

Priority 4 — Automated Nurture (for non-ICP or early-stage visitors):
□ Enroll in content-based nurture sequence matching their stated interest
□ Intent signal monitoring: if they return to high-intent page within 30 days → escalate to Priority 2 routing
□ Do NOT assign to SDR — protect SDR capacity for qualified pipeline

Handoff Briefing Auto-Generated for Every P1/P2 Routing:
"[Visitor First Name], [Title if known], at [Company Name] ([Industry], [Employee Count])
Visited: [Pages visited + time on each]
Said in chat: '[Exact quote of highest-intent statement]'
Qualification: [Scale ✓ / Timeline ✓ / Authority: unknown] [BANT summary]
Enrichment: [Clearbit Reveal confidence] — [LinkedIn match if found]
Recommended opening: '[Suggested first message for the rep based on what they said]'"

MODULE 4: CONVERSATION COPY LIBRARY

Opening Message Variations (A/B test these):

Variant A — Question-first (highest engagement for B2B SaaS):
"Quick question — are you exploring [Category] because of a specific project, or still figuring out if it's the right fit?"

Variant B — Value-first (works well for enterprise buyers who hate chat):
"If you're comparing [Category] options, I can pull up a side-by-side in about 30 seconds — no form, no pitch. Just tell me your main use case."

Variant C — Empathy-first (works for complex, painful problems):
"Most people land on this page because [common pain point]. Is that what brought you here, or something different?"

Variant D — Authority-first (for high-ACV enterprise plays):
"We work with [Customer Name] and [Customer Name] on exactly this. Happy to pull up how they approached their evaluation if that's useful."

Objection Handling Scripts:

"Just browsing":
"Totally — no pressure at all. Is there a specific part of [Product] you're curious about? I can point you to the right resource without any commitment."

"Not ready to talk to sales":
"That's completely fine — I'm not trying to get you into a sales call. Is there something specific you're trying to figure out that I can just answer here?"

"Send me an email / I'll reach out when I'm ready":
"Sure — what's the best email? And is there a specific topic you'd want us to cover when we do connect, so I can make sure the right person reaches out?" [Captures email + intent signal for personalized SDR follow-up]

"We already use [Competitor]":
"That makes sense — what's making you look at alternatives now?" [Never badmouth the competitor; let them tell you the pain]

"I'm just an analyst/researcher/student":
"No problem — happy to help! Are you looking for general information on [Category], or is this for a specific company project?" [Gracefully exit to resources; capture email if relevant]

Micro-CTA Formulations (closing a conversation):

1. "Want me to hold a [20-min] spot on [Rep Name]'s calendar? I can lock it in right here."
2. "Would a personalized [ROI estimate / comparison report] be useful? I can put one together if you share your email."
3. "I can send you [Customer Name]'s case study — they were in the exact same spot. Just drop your email."
4. "If you want to skip the back-and-forth, I can set up a 10-minute call with someone on our team who works specifically with [their industry]. No commitment."
5. "Before you go — would it help to see how [Competitor]'s customers typically make the switch to us? Takes about 2 minutes to read."

MODULE 5: CHAT ANALYTICS & CONVERSION OPTIMIZATION

Primary KPI Framework (8 metrics that matter):

1. Visitor-to-Conversation Rate: % of targeted page visitors who engage with the bot
   Benchmark: 3-8% for proactive trigger; 8-15% for exit-intent
   Target: Optimize trigger timing and opening message to reach benchmark before scaling spend

2. Conversation-to-Qualification Rate: % of started conversations that complete the qualification flow
   Benchmark: 20-35% for high-intent pages; 10-15% for general pages
   Red flag: Below 15% on pricing page → opening message is wrong or trigger timing is off

3. Qualification-to-Meeting Rate: % of qualified conversations that result in a booked meeting
   Benchmark: 25-45% (depends heavily on ACV and market maturity)
   Improvement lever: Reduce friction in booking step; offer async alternatives (Loom, async demo)

4. Meeting-to-Show Rate (from chat-sourced meetings): % of chat-booked meetings that actually attend
   Benchmark: 65-80% (chat-booked meetings typically show 15-20% better than form-submitted)
   Improvement lever: Personalized reminder email + rep LinkedIn preview

5. Chat-to-Pipeline Conversion Rate: % of chat conversations that generate an opportunity in CRM within 30 days
   Benchmark: 1.5-4% of all chat conversations (including nurture-track ones)
   This is your north-star metric for budget justification

6. Average Pipeline Value per Chat Lead: (Total pipeline from chat) ÷ (Total chat-sourced leads)
   Track monthly; benchmark against other inbound channels
   Typical finding: chat-sourced leads have 20-35% higher ACV than form-submitted leads (self-selection effect)

7. Routing Accuracy Rate: % of P1 routings (live rep) that were correctly classified as hot
   Measure: P1 leads that converted to opportunity within 30 days ÷ total P1 routings
   Target: >50%; if below 30%, your qualification criteria are too loose

8. Missed Live Routing Rate: % of P1 triggers where no rep was available within 90s
   Target: <15%; if above 30%, expand coverage hours or add async fallback

A/B Testing Roadmap (prioritized by expected lift):

Test 1 — Opening Message Variant (expected +15-40% conversation start rate):
Control: Generic opening ("Hi! How can I help?")
Variant A: Problem-first question (Variant A from Module 4)
Variant B: Value-first offer (Variant B from Module 4)
Run time: 2 weeks minimum; 500+ trigger events per variant for significance
Metric: Conversation start rate + completion rate (volume alone is misleading)

Test 2 — Trigger Timing (expected +10-25% qualification completion):
Control: Trigger at 15s on pricing page
Variant: Trigger at 30s (gives visitor time to read before interrupting)
Metric: Conversation-to-qualification rate (earlier trigger often starts conversations that drop off faster)

Test 3 — Meeting Offer Framing (expected +15-30% booking rate):
Control: "Want to book a demo?"
Variant A: "Want to see how [Similar Company] solved [Pain Point]? I can set up a 15-minute walkthrough."
Variant B: "I can lock in a [20-min] slot with [Rep Name] who works with [their industry] companies — no pitch, just questions."
Metric: Meeting-booked rate from qualified conversations

Test 4 — Bot Avatar & Name (expected +5-15% engagement — often underestimated):
Control: Generic bot name ("Vanta Assistant") with company logo
Variant: Real rep photo + first name ("Hi, I'm Sarah from Vanta — happy to help you navigate the options")
Metric: Conversation start rate; qualitative: do visitors engage differently when they think it's a human?

Chat Session Replay Analysis Protocol (run weekly for first 90 days, monthly after):
□ Filter for: conversations that reached Turn 3+ but did not result in meeting or email capture
□ Look for: Which specific question caused drop-off? What did they say before abandoning?
□ Pattern signals: "Too expensive" → pricing objection scripts needed; "I need to check with my team" → champion enablement content needed; Long pause before answering role/company size → these fields cause hesitation
□ Reclassification errors: conversations routed to nurture that were actually P1 quality — check for signal vocabulary your qualification logic is missing

MODULE 6: ENRICHMENT & CRM INTEGRATION ARCHITECTURE

De-Anonymization Stack (for every session, including those that don't provide email):

Layer 1 — IP-to-Company (real-time, every session):
□ Clearbit Reveal or 6sense IP intelligence → company name, industry, size, location
□ RB2B → LinkedIn profile match for individual visitor (available in the US; B2B visitors only)
□ Store as "Anonymous Account Signal" in your MAP — do not create a Contact record without an email
□ Use: Trigger account-level intent alerts to AE/SDR even for anonymous visits ("Acme Corp is on your pricing page")

Layer 2 — Email Capture → Full Enrichment (on email collection):
□ Trigger Clearbit Enrichment API within 200ms of email submission
□ Auto-populate CRM Contact: First name, last name, title, company, company size, LinkedIn URL
□ Confidence score stored: if Clearbit match < 70%, trigger ZoomInfo fallback enrichment within 15 minutes
□ Business email validation: check against known personal domains; soft-prompt for work email if personal detected

Layer 3 — Chat Transcript → Intent Signal Extraction (AI classification):
□ After conversation ends, run transcript through AI prompt: "Extract the following from this chat: (1) Stated pain point [verbatim quote], (2) Buying timeline [Actively evaluating / In 6 months / Just researching], (3) Company context [stated company size, team size, current solution], (4) Objections raised [list verbatim], (5) Interest level [1-5 scale with reasoning]"
□ Output stored as structured Contact properties in CRM
□ Use for: Lead scoring input, SDR personalization context, AE handoff brief generation

Identity Resolution for Anonymous Sessions:
□ If anonymous session (no email) + company identified via IP → create an "Account Signal" object in Salesforce linked to the Account record (not a Contact)
□ When same company visitor later submits email on a different page → stitch retroactively using email domain + company match → populate "First Seen" and "Intent Journey" fields on the Contact
□ Cross-device tracking: if visitor returns from different device → use RB2B LinkedIn match (when email domain matches known session from same LinkedIn profile) to stitch sessions

CRM Integration Rules:

Contact Record Creation Logic:
□ Create new Contact: chat email ≠ any existing Contact in CRM AND company is not an existing Account
□ Update existing Contact: email matches → append chat transcript as Activity; update Lead Source to "Chat — [Page Name]"; update intent fields
□ Merge risk: if email matches but company doesn't → flag for RevOps review (job change? duplicate?)
□ Contact Source tracking: always log `Lead_Source = "Conversational Marketing"`, `Lead_Source_Detail = "[Specific Page] Chat — [Date]"`

Activity Logging:
□ Log every conversation as a Task/Activity in CRM: Type = "Inbound Chat", Subject = "[First Turn of Conversation]", Description = full transcript
□ For P1/P2 routes: create a CRM Task for the assigned rep with 2-hour due date and full handoff brief in Task description
□ For P4 nurture: add to appropriate nurture Campaign in MAP; do not create a rep task

Lead Scoring Integration:
□ Chat completion (email provided): +20 points
□ Qualification complete (BANT partial): +25 points
□ Timeline "actively evaluating": +35 points
□ Pricing page chat: +15 points (page intent)
□ Competitive question asked: +20 points (high commercial intent signal)
□ Meeting booked via chat: +50 points → auto-qualify to SQL

CONSTRAINTS:
- All flows must be implementable in native Drift, Intercom, HubSpot Conversations, or Qualified.com without custom engineering
- Routing logic must have fallback for off-hours and rep unavailability — no hot lead should reach a dead-end
- All CRM data writes must include Source field and timestamp for attribution reporting
- Progressive profiling: never ask in chat for information already in CRM (integrate with CRM lookup via API or native connector)
- GDPR/CCPA compliance: cookie consent must be obtained before tracking; chat transcript storage must follow data retention policy; explicit consent required before adding to email nurture

OUTPUT FORMAT:
Return a complete Conversational Marketing & Chatbot Lead Qualification System with:
- Visitor segmentation matrix and trigger rules
- 4 complete conversation flows with exact copy (Flows A, B, C, D)
- Routing priority matrix with SLAs and escalation paths
- Objection handling script library (minimum 8 scenarios)
- 8-metric KPI dashboard specification
- A/B testing roadmap (4 tests with expected lift ranges)
- CRM integration architecture and data flow diagram
- 30-day launch checklist

## Example Input/Output

**Input:**
- Company: Pylon — B2B SaaS for enterprise customer support operations (ticketing + QA + CSAT analytics)
- Stage: Series A, $12M raised
- ICP: VP Customer Success and Head of Support at B2B SaaS companies with 100-1,000 employees
- ACV: $42,000
- Sales cycle: 45-60 days
- Monthly visitors: 22,000 unique/month
- High-intent pages: /pricing, /demo, /vs-zendesk, /vs-intercom
- Current conversion rate: 1.4% visitor-to-demo-request
- Chat platform: Drift (Growth plan)
- Intent data: Clearbit Reveal (IP de-anonymization only)
- CRM: HubSpot (Sales Hub Pro)
- Sales team: 4 AEs (full-cycle), 2 SDRs; 9am-6pm EST M-F coverage
- Brand voice: Conversational, empathetic, practitioner-to-practitioner tone

**Output (excerpts):**

**Trigger Configuration for Pylon:**

Priority page set in Drift:
- /pricing: Trigger at 12 seconds (pricing visitors read fast; don't wait too long)
- /demo: Trigger at 8 seconds (self-selected intent — they're there to book; help them quickly)
- /vs-zendesk and /vs-intercom: Trigger immediately with competitive-specific playbook (Flow D)
- /blog/* and /resources/*: Exit-intent only, content upgrade offer

**Flow A — Demo Page (exact Drift copy for Pylon):**

Turn 1 (opens at 8s):
Bot [named "Pylon Team"]: "Hey there — are you exploring Pylon because you're outgrowing your current support setup, or for a different reason?"

Turn 2A (if "outgrowing" or "current tool isn't working"):
"Got it — that's super common for teams your size. How many support agents are you managing right now?"
→ <3 agents: "We're built for teams scaling past 10 — but if you're headed there, this might be worth bookmarking. Want me to send you a quick overview for later?"
→ 3-50 agents: Continue to Turn 3A
→ 50+ agents: Flag as mid-market/enterprise; route to AE Matt or Sarah specifically

Turn 3A:
"And is this something you're actively trying to solve in the next quarter, or still in early stages of figuring out what you need?"
→ "Next quarter" / "We have a deadline": Turn 4A (booking)
→ "Early stages": "Totally fine — would it help to see how [Fintech SaaS company] solved their CS ops when they were at your stage? 10-minute read." → email capture → nurture

Turn 4A:
"Perfect — it would make sense to talk to one of our team members who works specifically with SaaS CS teams in your size range. I can lock in a 20-minute call for you right here. Does Thursday afternoon work, or is a different day better?"
[Calendar embed: shows available slots for next 72 hours]

**Competitive Flow D — /vs-zendesk page (Drift copy for Pylon):**
Turn 1: "Hey — are you currently on Zendesk and thinking about making a switch, or comparing both options before you've decided anything?"
→ "On Zendesk": "What's the main frustration making you look around? We hear a lot of things from CS teams — curious what's coming up for you."
→ Common responses and routing:
  - "Too expensive / pricing changed" → SDR with ROI comparison doc pre-loaded
  - "Reporting is terrible / can't see what I need" → AE with analytics differentiation story
  - "Just comparing" → Flow A, Turn 2A (qualification)

**KPI Dashboard Spec for Pylon:**

| Metric | Current Baseline | 30-Day Target | 90-Day Target | Data Source |
|---|---|---|---|---|
| Visitor-to-Conversation Rate | 0% (not live) | 4% on /pricing and /demo | 6% | Drift Analytics |
| Conversation-to-Qualification | — | 25% | 35% | Drift + HubSpot |
| Qualification-to-Meeting Rate | — | 30% | 40% | Drift + HubSpot |
| Chat-to-Pipeline (30-day) | — | 1.5% | 2.8% | HubSpot Deals |
| Pipeline from Chat per Month | $0 | $85K | $220K | HubSpot Deals |
| Missed Live Routing Rate | — | <25% (ramp period) | <12% | Drift routing log |
| Meeting-to-Show Rate | — | 70% | 78% | HubSpot Meetings |
| Avg Pipeline Value / Chat Lead | — | $28K | $38K | HubSpot Deals |

**30-Day Launch Checklist for Pylon:**

Week 1 — Technical Setup:
□ Connect Drift to HubSpot (native integration): map Drift contact fields to HubSpot Contact properties
□ Configure Clearbit Reveal in Drift: enable company name + industry personalization in opening messages
□ Build Flow A (Demo page) and Flow B (Pricing page) in Drift's Playbook builder
□ Set up Slack notifications: create #chat-hot-leads channel; connect Drift routing alerts
□ Configure rep routing: round-robin between 4 AEs for P2 (booking); SDR team for P3 (follow-up)

Week 2 — Content & Copy:
□ Load all conversation flows (A, B, C, D) into Drift Playbooks
□ Test every branch manually: QA all yes/no paths, disqualification exits, calendar embed
□ Set up post-chat email automation: booking confirmation email, prep email for booked meetings, resource email for nurture-track
□ Create 8 objection-handling quick replies for live-rep mode

Week 3 — Analytics & Routing:
□ Build HubSpot dashboard: 8 KPIs from Module 5 framework
□ Set up HubSpot workflow: Chat lead → lead score increment → SDR task creation
□ Configure off-hours fallback: 8pm-8am EST → bot collects email and question → SDR follows up by 10am next business day
□ Set rep availability windows in Drift: 9am-6pm EST; after-hours routing to email capture only

Week 4 — Launch & Optimize:
□ Go live on /pricing and /demo pages first (highest intent — most forgiving for bot errors)
□ Monitor daily: session replays in Drift, routing accuracy in HubSpot
□ Day 7 post-launch: first A/B test — opening message variants A vs. B on /pricing
□ Day 14: expand to /vs-zendesk and /vs-intercom with competitive Flow D
□ Day 21: launch Flow C (general pages) for exit-intent email capture
□ Day 30: first performance review; adjust trigger timing and qualification thresholds based on data

## Success Metrics

**Pipeline Generation:**
- Chat-to-pipeline conversion rate: Target 2-4% of all chat conversations generate an opportunity within 30 days
- Pipeline generated per month from chat: Track against other inbound channels; target chat to account for 8-15% of total inbound pipeline within 90 days
- Average deal size from chat-sourced leads: Typically 15-25% higher than form-submitted leads (benchmark vs. your baseline)

**Conversion Efficiency:**
- Visitor-to-conversation rate: 4-8% on high-intent pages (benchmark target)
- Conversation-to-meeting rate: 25-40% for qualified conversations
- Meeting-to-show rate: >70% for chat-booked meetings (vs. typical 55-65% for form-booked)

**Speed & Responsiveness:**
- Median time from conversation start to meeting booked: Target <4 minutes
- Live rep response time for P1 triggers: <90 seconds during business hours
- SDR follow-up SLA adherence: >90% of P3 leads contacted within 2 hours

**Data Quality:**
- Chat lead enrichment coverage: >80% of email-captured leads with company, title, and company size within 1 hour
- CRM data completeness from chat: Chat-sourced contacts should have >85% field completeness (vs. typical 50-60% for form leads)
- Intent signal capture: % of conversations where AI classification successfully extracts pain point and timeline (target: >75% of completed qualification flows)

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Inbound-Marketing/AI-Powered-Gated-Content-Strategy-&-Progressive-Profiling-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Inbound-Marketing/B2B-Website-Personalization-&-Dynamic-Visitor-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Inbound-Marketing/Landing-Page-Generation/Conversion-Rate-Optimization-&-Landing-Page-Testing-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Website-Analytics-&-Behavioral-Intelligence/GA4-Website-Analytics-&-Conversion-Intelligence-Engine.md`

## Integration Tips

**Drift:**
- Use Drift's "Audiences" feature to build the visitor segmentation matrix from Module 1 — target by URL, time on page, number of sessions, and Clearbit Reveal attributes (company size, industry) without any custom code
- Drift's "Live View" shows reps all active conversations in real time; train reps to monitor this alongside their Slack alerts for P1 routing
- Use Drift's "Qualified Meetings" integration to sync booked meetings directly into HubSpot/Salesforce as Meetings with the bot conversation transcript attached
- Drift Fastlane: for accounts in your target list (upload as CSV from CRM), enable Fastlane to allow ICP visitors to skip the bot and connect live instantly — especially powerful for ABM target accounts

**Intercom:**
- Use Intercom's "Custom Bot" builder with branching logic to build Flows A-D; Intercom's AI features (Fin) can handle free-text responses with intent classification built in
- Intercom's "Series" feature creates multi-step conversation journeys — use for the nurture-track follow-up after an anonymous chat session
- Connect Intercom to Salesforce via native integration: push all conversation data as Salesforce Tasks; use the "Lead Source" field to track chat-sourced pipeline
- Intercom Signals: for enterprise buyers who show buying signals in chat but don't book — Intercom can flag these accounts for SDR follow-up based on conversation keywords

**HubSpot Conversations:**
- HubSpot's native Chatflows (included in Marketing Hub Professional+) can replicate all 4 conversation flows without a third-party tool — ideal for teams that want one platform
- Use HubSpot's "Chatbot" builder with branch logic and "If/Then" branches to replicate the BANT qualification sequence from Module 2
- HubSpot Meetings embed works natively in Chatflows — chatbot can offer a calendar widget inline with round-robin rep assignment
- HubSpot's "Conversation Intelligence" (Sales Hub Enterprise) transcribes and analyzes chat sessions automatically — use this for the session replay analysis protocol in Module 5

**Qualified.com:**
- Qualified is purpose-built for the exact use case in this prompt — integrates natively with Salesforce and Marketo; routes by CRM ownership, territory, and account tier automatically
- Qualified's "Pipeline Cloud" tracks pipeline generated from chat and attributes it to the correct rep and campaign — removes the attribution complexity from Module 6
- Use Qualified's "Signals" feature to trigger chat from G2 buyer intent data, 6sense stage changes, or Salesforce opportunity activity — most advanced trigger configuration available without custom code

**Zapier / Make:**
- Zap: New Drift/Intercom conversation completed (qualified = true) → create HubSpot Contact → enroll in "Chat Qualified" sequence → notify SDR in Slack with full enrichment profile
- Make scenario: Drift conversation with routing = P1 AND no rep response in 90s → send emergency Slack DM to backup rep AND sales manager → create follow-up task in CRM due in 15 minutes
- Zap: Chat meeting booked (from calendar embed) → send personalized pre-meeting prep email to visitor → create HubSpot deal in "Demo Scheduled" stage → notify AE with full briefing

## Troubleshooting

**Problem: Conversation start rate is below 2% even on high-intent pages — the bot is being ignored**
Fix: The most common cause is trigger timing — if the bot fires too quickly (under 8 seconds), visitors dismiss it as annoying before they've read anything meaningful. Increase trigger delay to 20-30 seconds on content-heavy pages. Second most common cause: the opening message sounds like every other chatbot ("Hi! Can I help you?"). Switch to a problem-first question specific to the page content — e.g., on a /pricing page, "Trying to figure out which plan fits your team?" outperforms generic openers by 2-4× in B2B SaaS. Also audit: is your chat widget loading before your page content? Slow load → visitors interact with the page before the chat widget appears, then don't notice it.

**Problem: High conversation start rate but low qualification completion — visitors drop off after the first question**
Fix: The drop-off point reveals the friction. Run Drift/Intercom session replays filtered to "started but not completed" conversations. If they drop after Turn 2 (the size/scale question), your minimum ICP threshold is too high and visitors self-select out correctly — review whether your ICP qualification criteria matches actual closed-won customer data. If they drop after free-text entry (they typed something and got no relevant response), your intent classification logic needs improvement — the bot isn't branching correctly based on what they said. Add more keyword triggers and expand your "if they say X" branch logic. If drop-off is consistent across all visitors regardless of what they type, the question itself is causing friction — rephrase from "How large is your company?" to "What's the size of the team you'd be using this for?" (narrower, less revealing framing).

**Problem: P1 routing is triggering too often — sales team is getting flooded with low-quality "hot leads" that don't convert**
Fix: Your qualification criteria are too loose. Audit the last 30 P1 routings: what % generated an opportunity within 30 days? If below 30%, tighten one or two criteria. Most common fix: add a minimum company size requirement (e.g., P1 only triggers for visitors from companies with >50 employees, verified by Clearbit Reveal). Second fix: require BOTH timeline confirmation ("actively evaluating") AND page intent (pricing or demo page) — not just one signal. Also check: are competitor pages triggering P1? Competitive visitors are high-intent but often not purchase-ready — route them to P3 SDR follow-up instead of live P1 connection.

## Version History
- v1.0: Initial creation (auto-generated)
