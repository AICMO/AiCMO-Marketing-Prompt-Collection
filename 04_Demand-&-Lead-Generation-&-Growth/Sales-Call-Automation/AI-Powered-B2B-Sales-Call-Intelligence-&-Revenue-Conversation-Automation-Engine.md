# AI-Powered B2B Sales Call Intelligence & Revenue Conversation Automation Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** sales-call, conversation-intelligence, revenue, b2b, automation, gong, pipeline, sdr, ae, enablement

## Overview
Automates the full sales call lifecycle — pre-call research briefings, real-time objection handling playbooks, post-call follow-up generation, and pattern analysis across your call library — so every rep walks in prepared, follows up instantly, and your team extracts coaching insights at scale. Use it when onboarding new AEs, diagnosing why deals stall, or building a conversation intelligence program from scratch without a six-figure Gong contract.

## Quick Copy-Paste Version

You are a senior B2B sales strategist with 15 years of experience running revenue teams at SaaS companies from Series A to IPO. I need you to build a complete sales call intelligence and automation system.

My context:
- Company: [Describe your product and what problem it solves in 2-3 sentences]
- ICP: [Buyer persona, company size, industry]
- Average deal size: [e.g., $24K ACV]
- Sales cycle length: [e.g., 60-90 days]
- Team size: [e.g., 4 AEs, 2 SDRs]
- Call recording tool: [Gong / Chorus / Fathom / Fireflies / None]
- CRM: [HubSpot / Salesforce / Other]

Produce the following:

1. PRE-CALL INTELLIGENCE BRIEF TEMPLATE
   - Account snapshot (company news, funding, job postings, tech stack signals)
   - Stakeholder profile (LinkedIn intel, seniority, likely priorities, communication style)
   - Deal history (prior touchpoints, objections raised, open action items)
   - Competitive landscape (which competitors are likely in the deal and how to position against each)
   - Meeting objective and success criteria (what "win" looks like for this specific call)

2. CALL STRUCTURE PLAYBOOK
   - Opening framework that establishes agenda, rapport, and credibility in under 3 minutes
   - Discovery question bank: 10 high-impact questions organized by pain area
   - Objection handling matrix: top 5 objections with word-for-word response scripts
   - Demo/presentation anchoring techniques to tie features to stated pains
   - Closing and next-step commitment framework

3. POST-CALL AUTOMATION SEQUENCE
   - Meeting summary template (decisions made, open questions, next steps, owner + due date)
   - Follow-up email template sent within 60 minutes of call end
   - CRM update checklist (fields to populate, stage advancement criteria)
   - Internal Slack summary for deal review

4. CONVERSATION INTELLIGENCE SCORECARD
   - 8 metrics to score every call (talk-time ratio, question rate, objection frequency, next-step commitment, etc.)
   - What "good" looks like for each metric with benchmarks
   - Red flags that predict deal loss within 30 days

5. COACHING FRAMEWORK
   - How to use call recordings to identify top-performer patterns
   - Weekly call review process for managers
   - Ramp acceleration playbook for new AEs using recorded call libraries

## Advanced Customizable Version

ROLE: You are an elite revenue intelligence architect. You combine the analytical precision of a data scientist with the pattern recognition of a 20-year sales veteran. You have built conversation intelligence programs that reduced sales cycle length by 30%+ and increased win rates from 18% to 31% at Series B and C SaaS companies.

MISSION: Design a production-ready, AI-powered sales call intelligence system that automates pre-call preparation, post-call follow-up, and cross-call pattern extraction — enabling every rep to perform like your top quartile, regardless of tenure or experience.

COMPANY CONTEXT:
- Company name: [Your company]
- Product description: [What you sell and the core problem it solves]
- Primary buyer: [Job title, seniority, company size — e.g., VP of Operations at mid-market manufacturing]
- Average ACV: [Dollar amount]
- Average sales cycle: [Days from first meeting to close]
- Typical buying committee size: [Number of stakeholders involved in a deal]
- Win rate: [Current % — e.g., 22%]
- Primary competitors: [Top 2-3 alternatives prospects evaluate]

TECH STACK:
- CRM: [HubSpot / Salesforce / Pipedrive]
- Call recording tool: [Gong / Chorus / Fireflies / Fathom / Otter.ai / None]
- Meeting scheduler: [Calendly / Chili Piper / HubSpot Meetings]
- Outreach tool: [Outreach / Salesloft / Apollo / HubSpot Sequences]
- Slack: [Yes / No]

---

### MODULE 1: PRE-CALL INTELLIGENCE SYSTEM

Design an automated pre-call briefing that a rep can generate in under 5 minutes for any scheduled meeting.

**Section 1A — Account Intelligence Layer**

For each scheduled call, pull and synthesize:

a) Company signals (sourced from LinkedIn, Google News, Apollo, Crunchbase):
   - Recent funding rounds or M&A activity (last 12 months)
   - Executive hires or departures (especially in the buyer's department)
   - Job postings that signal budget, tech stack changes, or pain points (e.g., 8 open RevOps roles = broken systems)
   - Earnings call themes or press releases if public company
   - Tech stack from BuiltWith/Clearbit (tools they use that compete with or complement your product)

b) Prompt to generate account summary:
   "Synthesize the following signals about [Company Name] into a 5-bullet executive brief. Each bullet should connect the signal to a potential pain point my product solves. Signal data: [paste raw signals]. My product solves: [problem statement]."

**Section 1B — Stakeholder Intelligence Layer**

For each attendee on the meeting invite:

a) Profile synthesis prompt:
   "Based on this LinkedIn profile and recent activity for [Name, Title, Company], generate: (1) their likely top 3 professional priorities this quarter, (2) their likely communication style preference (data-driven vs. narrative-driven vs. process-oriented), (3) the question they are most likely to ask in a vendor evaluation meeting, and (4) one personalized opener I can use to build instant rapport."

b) Power mapping template:
   - Economic buyer: [Who controls the budget?]
   - Champion: [Who wants this to succeed internally?]
   - Technical evaluator: [Who will audit the product?]
   - Blocker: [Who has reason to resist?]
   - Each role: their likely concern and how to address it

c) MEDDIC/MEDDPICC pre-call checklist:
   - Metrics: What quantifiable outcome do they need to justify this purchase?
   - Economic buyer: Identified and engaged? Y/N
   - Decision criteria: What are their evaluation parameters?
   - Decision process: Who else is involved and what is the approval sequence?
   - Paper process: Legal/procurement timeline estimate?
   - Identify pain: What specific pain have they verbalized?
   - Champion: Do we have an internal advocate? Strength: High/Medium/Low
   - Competition: Which alternatives are in consideration?

**Section 1C — Deal History Synthesis**

Generate a prompt that, when fed CRM notes and prior email threads, produces:
- A 3-sentence deal narrative (where are we, why did they engage, what's their stated priority)
- Open commitments from prior calls (what did you promise to do or send?)
- Objections already raised and how they were handled
- Sentiment score from last interaction: Positive / Neutral / At-risk

**Section 1D — Competitive Battlecard (Call-Specific)**

For each likely competitor in the deal, generate a 1-page call-ready battlecard:
- Their product's top 3 strengths (be honest — reps who dismiss competitor strengths lose credibility)
- Their top 3 weaknesses that your product solves
- The question to ask that surfaces their weakness without naming the competitor: "How important is it that [your differentiator] is native vs. requiring a separate integration?"
- If they say the competitor is better at X: trap question + reframe + proof point sequence

---

### MODULE 2: CALL EXECUTION FRAMEWORK

**Section 2A — Call Opening Protocol (First 3 Minutes)**

Provide a word-for-word call opening framework that:
1. Confirms time and attendees (90 seconds max)
2. Sets the agenda and hands control back to the prospect
3. Establishes credibility without pitching
4. Earns the right to ask deep discovery questions

Template:
"Thanks for making time, [Name]. We've got [X] minutes — I want to make sure this is useful for you, not just for me. Here's what I was thinking: [1 sentence agenda]. Before I jump in, is there anything on your end that's come up since we last talked that should shape where we focus? ... [pause, listen] ... Perfect. My one ask is that if at any point this isn't relevant, you tell me — I'd rather we spend 10 minutes on what actually matters than 45 on a slide deck. Sound good?"

**Section 2B — Discovery Question Bank by Pain Category**

Design 5 pain categories relevant to [your ICP] and generate 3 high-impact discovery questions per category. Questions must follow this principle: ask about the *consequences* of the problem, not just its existence.

Pain Category Framework:
- Category 1: [e.g., Operational efficiency] — questions that expose cost of status quo
- Category 2: [e.g., Revenue leakage] — questions that quantify missed opportunity
- Category 3: [e.g., Team scalability] — questions that surface people/capacity constraints
- Category 4: [e.g., Data/visibility gaps] — questions that reveal decision-making blindspots
- Category 5: [e.g., Competitive pressure] — questions that create urgency without manufacturing it

Question quality rules:
- Never ask yes/no questions in discovery
- Each question should make the prospect think, not just recall
- Questions should feel like a conversation, not an interrogation
- Best questions end with "...what does that look like for you?" or "...how does your team handle that today?"

**Section 2C — Objection Handling Matrix**

Generate word-for-word response scripts for each of these objection categories:

OBJECTION 1: "We're happy with what we have"
Framework: Acknowledge + Curiosity Gap + Proof Point
Script: "That's great to hear — what you have is clearly working well enough that you're not in crisis. Can I ask: when you think about [the specific outcome your product drives], how are you measuring that today? The reason I ask is that most teams we talk to who say they're happy find one area where the number actually surprises them when they dig in..."

OBJECTION 2: "Your price is too high / we don't have budget"
Framework: Decouple price from value + ROI bridge + timeline reframe
Script: [Generate 3-paragraph objection response]

OBJECTION 3: "We need to involve [other stakeholder / IT / procurement]"
Framework: Validate + Assist + Advance
Script: [Generate 3-paragraph objection response that expands the deal rather than stalling it]

OBJECTION 4: "We're evaluating [Competitor X] as well"
Framework: Celebrate + Qualify criteria + Plant differentiation seed
Script: [Generate 3-paragraph response that advances without disparaging the competitor]

OBJECTION 5: "We need to think about it / let me get back to you"
Framework: Uncover real objection + Mutual action plan + Soft commitment
Script: [Generate 3-paragraph response that moves forward without being pushy]

**Section 2D — Closing and Commitment Framework**

Design a closing system that secures a specific next step on every call — no "I'll follow up" vagueness.

The Mutual Action Plan (MAP) close:
"Before we wrap up, I want to make sure we leave with a clear picture of what happens next — for your team and mine. Based on what you've shared, here's what I see as the natural next steps: [list 2-3 steps]. Does that match how you're thinking about this? ... What I'd suggest is that we get [next step] on the calendar before we hang up — I find that when we leave it open, it's hard for both of us to protect the time. Does [date option A] or [date option B] work for you?"

Commitment ladder (from lowest to highest):
1. Send resources (weak — avoid as a standalone close)
2. Schedule next call (minimum acceptable close)
3. Introduce to economic buyer (strong close)
4. Sign mutual NDA / data sharing agreement (procurement signal)
5. Align on Mutual Action Plan with dates and owners (deal is real)

---

### MODULE 3: POST-CALL AUTOMATION SYSTEM

**Section 3A — Call Summary Generation Prompt**

Prompt to feed into any AI tool (Claude, ChatGPT, Gong AI) immediately after a call:

"You are a revenue operations analyst. I just completed a sales call and need a structured summary for my CRM. Here is the transcript or my call notes: [paste transcript or bullet notes].

Generate the following:
1. CALL SUMMARY (3 sentences max): What was discussed, what was the prospect's primary pain, what is their current situation
2. PAIN POINTS CONFIRMED: Bulleted list of pains the prospect explicitly articulated (use their words, not ours)
3. OBJECTIONS RAISED: Each objection and whether it was resolved, partially addressed, or still open
4. NEXT STEPS: For each party (rep and prospect), specific action with due date and owner
5. DEAL ASSESSMENT: On a scale of 1-5, rate deal health based on: budget confirmed (Y/N), timeline stated (Y/N), champion identified (Y/N), next step agreed (Y/N), competition named (Y/N)
6. RED FLAGS: Any signals that suggest deal risk (e.g., 'they mentioned they need to pause until Q3,' 'champion said their budget was just cut,' 'they mentioned a competitor has already done a proof of concept')
7. CRM UPDATE FIELDS: List specific fields to update in CRM with recommended values"

**Section 3B — Follow-Up Email Generator**

Prompt for generating follow-up email within 60 minutes of call:

"Write a follow-up email for a B2B sales call I just completed. Tone: professional, direct, no fluff. Do not use the words 'as discussed' or 'per our conversation.'

Context: [paste 3-4 bullet summary of call]
Prospect name and company: [Name, Company]
Key pain they shared: [specific pain]
Next step agreed: [what we agreed to do next]
Any resources I promised to send: [list]

Email structure:
- Subject line: reference the specific problem they mentioned, not a generic follow-up label
- Paragraph 1 (2-3 sentences): Acknowledge what they shared; reflect back their pain in their words to confirm you listened
- Paragraph 2 (2-3 sentences): Connect their pain to the outcome they're trying to achieve; bridge to next step
- Resources section: clean bulleted list of anything you're sharing
- Next step: specific, time-bound, mutual commitment from the call
- CTA: single, clear ask (confirm the next meeting, not 'let me know if you have questions')
- Sign-off: no 'best regards' — use 'Talk [day of next call],' or 'To [next step outcome]'"

**Section 3C — CRM Update Protocol**

Stage advancement criteria (customize per your stage definitions):

| Stage | Criteria to Advance | Fields to Update |
|---|---|---|
| Discovery → Qualified | BANT partially confirmed, pain articulated, champion identified | Pain points, budget timeline, champion name |
| Qualified → Evaluation | Demo completed, evaluation criteria defined, economic buyer engaged | Decision criteria, competitors, paper process |
| Evaluation → Proposal | Mutual action plan agreed, legal/procurement process known | Close date, deal value, stakeholders |
| Proposal → Negotiation | Proposal sent and received, commercial objections surfacing | Discount approval status, risk flags |
| Negotiation → Closed Won | DocuSign sent | Final ACV, start date, CSM assigned |

**Section 3D — Internal Slack Deal Update Template**

"🏃 [AE Name] — [Company] — [Stage] | [ACV]
📋 What happened: [1 sentence]
🎯 Key pain confirmed: [quote from prospect if possible]
✅ Next step: [specific action] by [date]
⚠️ Risk flags: [any red flags, or 'None identified']
📊 MEDDIC score: [X/7 criteria confirmed]"

---

### MODULE 4: CONVERSATION INTELLIGENCE SCORECARD

**Section 4A — Call Quality Metrics (8 Core KPIs)**

| Metric | Definition | Green | Yellow | Red |
|---|---|---|---|---|
| Talk-time ratio | Rep vs. prospect speaking time | 40/60 to 45/55 (rep/prospect) | 50/50 | Rep >55% |
| Discovery question rate | # of open questions per 30 min | >8 questions | 4-7 | <4 |
| Pain confirmation | Prospect verbalized specific pain | Named + quantified | Named only | Not surfaced |
| Objection handling | % of objections addressed vs. deflected | >80% addressed | 50-79% | <50% |
| Next step commitment | Specificity of agreed next step | Date + agenda confirmed | Date only | "I'll follow up" |
| Economic buyer access | Did rep ask to involve EB? | Yes, and access granted | Asked, denied | Not asked |
| Competitive intel gathered | Did rep learn which competitors are in deal? | Named + eval criteria known | Named only | Not surfaced |
| Call-to-follow-up speed | Time from call end to follow-up sent | <60 minutes | 60-240 min | >4 hours |

**Section 4B — Deal Health Prediction Model**

From call transcript analysis, these signals predict deal loss within 30 days with >70% accuracy:

RED FLAGS (any 2 = immediate manager review):
- Prospect said "we need to think about it" without committing to a specific decision date
- No second-line stakeholder introduced after 2+ meetings
- Rep mentioned price before pain was fully established
- Call ended without a confirmed next step on calendar
- Prospect asked "what does implementation look like?" but rep jumped to demo instead of answering
- Rep talked more than 55% of call time in a discovery meeting
- Economic buyer has never been on a call after Evaluation stage entered

GREEN FLAGS (strong deal signals):
- Prospect used the word "when" not "if" (e.g., "when we implement this...")
- Prospect asked for legal/security documentation unprompted
- Prospect shared internal budget cycle details voluntarily
- Champion offered to introduce rep to additional stakeholders
- Prospect asked about references or case studies from their industry

---

### MODULE 5: COACHING & RAMP ACCELERATION FRAMEWORK

**Section 5A — Manager Weekly Call Review Process**

Monday call review protocol (45 minutes):
1. Pull 3 call recordings from prior week: 1 deal won, 1 deal lost/stalled, 1 new rep call (10 min to select)
2. Review won deal (10 min): What moments sealed it? Which questions unlocked pain? Extract 2 "steal this" moments
3. Review lost/stalled deal (15 min): Where did momentum break? Which objection was mishandled? What should rep have done differently at that moment?
4. Review new rep call (10 min): Score against 8-metric scorecard; identify 1 specific behavior to change this week
5. Document findings in call review log: pattern → observed evidence → coaching prescription → follow-up date

**Section 5B — New AE Ramp Library Structure**

Build a curated call library that new AEs complete in their first 30 days:

Week 1 — Foundation calls (5 recordings):
- 1 perfect discovery call (annotated: here's why each question worked)
- 1 objection handling showcase (annotated: each objection and response)
- 1 deal lost call (annotated: here's the exact moment it broke)
- 1 demo excellence call (annotated: how top reps tie features to stated pain)
- 1 closing call (annotated: the exact language used to secure next steps)

Week 2 — Shadow and debrief:
- New AE joins 3 live calls as silent observer
- Debrief after each: "What questions did you notice? What would you have done differently?"

Week 3 — Coached calls:
- New AE conducts 3 calls with manager listening
- Manager provides real-time note-passing (not interrupting) via Slack DM
- 15-minute debrief immediately after each call

Week 4 — Independent with scorecard review:
- New AE runs calls independently
- Manager reviews recordings against scorecard; weekly 1:1 on patterns

**Section 5C — Top-Performer Pattern Extraction Prompt**

"Analyze the following 10 call transcripts from our highest-performing AE [name] who closed [X deals] last quarter at [X% win rate]. Identify: (1) the 5 question types they use most frequently and in what order, (2) how they handle the 3 most common objections compared to average performers, (3) the exact language they use to advance next steps, (4) their average talk-time ratio and how it shifts from discovery to demo to close calls, (5) any patterns in calls that converted within 30 days vs. those that dragged beyond 90 days. Produce a 'Top Performer Playbook' that I can train my entire team on."

---

## Example Input/Output

**Input Example:**
Company: Operata — AI-powered contact center analytics for VP Customer Experience and Head of CX Operations at enterprise companies (500+ seats)
ICP: VP of CX / Director of Contact Center Operations, 1,000+ employee companies, using Genesys, Avaya, or Amazon Connect
ACV: $85,000 average
Sales cycle: 90-120 days
Team: 3 AEs, 2 SDRs, 1 SE
Call tool: Fathom (no Gong)
CRM: Salesforce

**Output Example (Pre-Call Intelligence Brief — Account: NovaCare Health):**

---

**ACCOUNT SNAPSHOT — NovaCare Health | Discovery Call | [AE Name]**

🏢 Company signals:
- Acquired CarePoint Solutions (competitor) 3 months ago — integration complexity = likely CX disruption
- Posted 14 contact center analyst roles in past 60 days — signal of broken reporting/visibility
- CFO replaced in January — new financial scrutiny; deals need stronger ROI justification

👤 Stakeholder: Sarah Chen, VP of CX Operations
- LinkedIn: 9 years at NovaCare, promoted twice in last 3 years — she owns this problem and has organizational credibility
- Recent LinkedIn post: "Why 'good enough' contact center metrics are failing leadership" — she is already selling this problem internally, we are her external validation
- Communication style: Data-driven (posts cite specific statistics); open with numbers, not stories
- Rapport opener: "I read your piece on contact center metrics — you framed exactly the problem our customers describe before they find us. What prompted you to write that?"

🎯 Meeting objective: Surface the top 2 pain points from the CarePoint acquisition impact on CX visibility; earn the right to do a technical discovery with her team in week 2

⚔️ Competition: Likely evaluating Observe.AI (we know this from their job posting requirements); Observe.AI weakness = weak native integration with Amazon Connect (NovaCare runs Amazon Connect)

**MEDDIC Pre-Call Status:**
- Metrics: Not confirmed — priority for today
- Economic buyer: CFO likely; need to surface
- Decision criteria: Unknown — priority for today
- Decision process: Unknown
- Paper process: Unknown
- Identify pain: Likely CX visibility post-acquisition — confirm today
- Champion: Sarah Chen — strength: High (she wrote the post, she owns the problem)
- Competition: Observe.AI — confirmed from job posting language

---

**Output Example (Post-Call Follow-Up Email):**

Subject: The visibility gap you described — next steps

Sarah,

The problem you named today — not being able to see how agent performance shifted after the CarePoint migration — is exactly what breaks CX leadership's ability to make confident staffing and routing decisions. You're operating on instinct where you need data.

The two things I want to put in front of you before our next conversation are the NovaCare-adjacent case study (regional health system, similar Amazon Connect environment, similar post-acquisition situation) and the ROI model template your CFO's team can validate independently. Both attached.

**Resources:**
- [Operata CX Visibility Case Study — Regional Health System]
- [Contact Center Analytics ROI Model — CFO-Ready Template]

**Our next step:** 45-minute technical discovery with your CX Ops lead, week of [date]. I've sent a hold to your calendar — confirm if timing works.

Talk [day of confirmed meeting],
[Rep Name]

---

## Success Metrics

- **Pre-call brief adoption rate:** >90% of scheduled calls have a completed intelligence brief generated within 24 hours of scheduling
- **Follow-up speed:** Average follow-up email sent within 60 minutes of call end (track via email timestamp vs. calendar event end time)
- **Call scorecard average:** Team average >6.5/8 on conversation quality scorecard; no AE below 5/8 for 3+ consecutive weeks without coaching intervention
- **Next step commitment rate:** >85% of calls end with a confirmed calendar hold for the next meeting (tracked as CRM stage advancement with future activity date)
- **Discovery question rate:** Average >6 open-ended questions per 30 minutes in discovery calls
- **Talk-time ratio:** Team average rep talk-time <50% in discovery meetings (audited monthly via call recording tool)
- **Ramp time reduction:** New AEs achieve first close within 10 weeks (vs. industry average 14 weeks) using call library and coaching protocol
- **Win rate improvement:** Track quarterly win rate before and after implementing conversation scorecard; target +5pp improvement within 2 quarters

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Outbound-Prospecting/AI-Powered-Prospect-Research-Enrichment-&-Hyper-Personalization-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Outbound-Prospecting/Buying-Committee-Intelligence-&-Multi-Stakeholder-Outreach-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/AI-Powered-B2B-Pipeline-Acceleration-&-Late-Stage-Deal-Marketing-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Sales-Enablement-Analytics/AI-Powered-Sales-Onboarding-Analytics-&-Ramp-Acceleration-Intelligence-Engine.md`

## Integration Tips

- **Gong / Chorus:** Use call scorecards as custom Gong scorecards — configure each of the 8 KPIs as a scored dimension reviewers rate during call reviews; export weekly team averages to Google Sheets via Gong API for trend tracking
- **Fathom / Fireflies.ai:** Use the post-call summary prompt (Module 3A) as a Fathom AI summary template — paste into "Custom Summary Instructions" in Fathom settings so every call auto-generates the structured format
- **Salesforce:** Create a "Call Intelligence" custom object that stores: scorecard scores, health flags, MEDDIC status, and talk-time ratio for each meeting activity; use Flow to trigger a Slack notification when deal health drops below threshold
- **HubSpot:** Use HubSpot's AI call summaries as input to the Module 3A prompt — copy the auto-summary, feed it into the generation prompt, paste structured output into deal notes; create a Deal property "Next Step Committed" (boolean) to track whether calls end with a confirmed next meeting
- **Slack:** Create a #deal-intelligence Slack channel; configure Zapier or Make to auto-post the Module 3D Slack template when a rep updates a deal stage in CRM; use thread reactions (✅/⚠️/❌) for lightweight async deal review
- **Calendly / Chili Piper:** When a prospect books a meeting, trigger an automated Zap that: (1) pulls company data from Apollo/Clearbit, (2) pulls LinkedIn profile from Phantombuster, (3) generates a pre-call brief using Module 1 prompts, (4) sends the brief to the AE via Slack 2 hours before the meeting
- **Clay:** Build a Clay table that auto-enriches every booked meeting with: company news (Perplexity API), stakeholder LinkedIn activity (Phantombuster), tech stack (BuiltWith), and competitor signals (job posting keywords) — output as a formatted pre-call brief card sent to rep via email

## Troubleshooting

**Problem: Reps aren't using the pre-call brief template — they say it takes too long**
Solution: The brief should never take more than 5 minutes. If it does, the process is broken, not the rep. Fix in two steps: (1) Automate the data-gathering layer using Clay or a Zapier workflow that pre-populates the account signals section automatically when a meeting is booked — the rep only adds their deal-specific context. (2) Reduce the brief to a "5-bullet maximum" format for calls under $25K ACV — depth should match deal size. Reps resist processes that feel like overhead; make the brief feel like a weapon, not a form.

**Problem: AI-generated post-call summaries are generic and don't capture the nuances of the deal**
Solution: Generic output is always a prompt quality problem. The Module 3A prompt requires you to feed in actual transcript or detailed notes — if you're feeding in a 3-line summary, you'll get a 3-line output dressed up as a deliverable. Two fixes: (1) If using Gong/Chorus/Fathom, paste the full AI transcript (not the summary) into the generation prompt. (2) If taking manual notes, adopt the "4C format" during the call: Concern stated, Context given, Commitment made, Consequence of inaction. Four boxes per call, filled live, = enough raw material for a quality structured summary.

**Problem: Win rate isn't improving even though reps are running more structured calls**
Solution: Structured process without the right diagnosis is theater. Run this diagnostic: pull the last 15 lost deals and categorize loss reason by stage — if losses cluster in Discovery/Qualify, the problem is ICP targeting, not call execution. If losses cluster in Evaluation/Proposal, the problem is competitive positioning or economic buyer access, not discovery quality. If losses cluster in Negotiation, the problem is pricing strategy or champion strength. Map your scorecard improvements to the stage where deals are actually dying — a better discovery script won't fix a Champion who can't sell internally.

## Version History
- v1.0: Initial creation (auto-generated)
