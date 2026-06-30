# AI-Powered B2B SaaS Demo Request Conversion Architecture & Pipeline Qualification Velocity Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** cro, demo-conversion, pipeline-velocity, lead-qualification, speed-to-lead, b2b-saas, inbound-conversion, demo-show-rate, pipeline-qualification, revenue-operations

## Overview
Engineers the complete conversion journey from demo request submission to qualified pipeline opportunity — optimizing every touchpoint (form design, post-submit personalization, SDR handoff, pre-demo nurture, show rate, and discovery-to-qualification conversion) using AI agents that personalize each step in real time. Use this when your demo request volume is healthy but pipeline conversion rates are below benchmark, when show rates are under 60%, or when you're losing qualified inbound leads to slow SDR follow-up.

## Quick Copy-Paste Version

You are a B2B SaaS conversion optimization expert specializing in inbound demo pipeline velocity. Analyze the demo request journey below and produce a complete optimization architecture with specific actions, copy, sequences, and automation logic to maximize qualified pipeline from inbound demo requests.

COMPANY CONTEXT:
- Company: [Company name and product description]
- ICP: [Ideal customer profile — company size, industry, primary buyer persona]
- ACV: [$X average contract value]
- Deal motion: [Sales-led / PLG-assisted / enterprise / SMB high-velocity]
- CRM: [HubSpot / Salesforce / other]
- Marketing automation: [Marketo / HubSpot / Outreach / other]
- Current demo request volume: [X per month]
- Current demo-to-show rate: [X%]
- Current show-to-SQL rate: [X%]
- Speed-to-lead (avg time from request to first SDR contact): [X minutes/hours]

CURRENT DEMO REQUEST FORM:
- Fields collected: [List all form fields]
- Form location: [Where the form lives — pricing page, homepage CTA, product page, etc.]
- Post-submit experience: [What happens immediately after submission]
- Routing logic: [How leads get assigned to SDRs/AEs]

BIGGEST CONVERSION PROBLEMS (check all that apply):
- [ ] Form completion rate is low / too much friction
- [ ] Leads sit unworked for hours or days
- [ ] Show rate under 60%
- [ ] SDRs don't know enough to personalize the first contact
- [ ] Discovery calls don't convert to qualified opportunities
- [ ] High no-show rate for scheduled demos

ANALYSIS REQUIRED:
1. FORM OPTIMIZATION: Redesign the form with progressive profiling and AI-inferred enrichment to minimize friction while maximizing qualification data.
2. POST-SUBMIT AI PERSONALIZATION: Design the immediate post-submit experience (confirmation page, email, Slack notification to SDR) personalized by ICP segment.
3. SPEED-TO-LEAD AUTOMATION: Build the automated qualification and routing workflow that gets the right SDR engaging the right prospect within 5 minutes during business hours.
4. PRE-DEMO NURTURE SEQUENCE: Create a 3-5 touch pre-demo sequence (email + LinkedIn + SMS if appropriate) that increases show rates by educating and building commitment before the call.
5. SHOW RATE OPTIMIZATION: Specific tactics to increase show rates — calendar reminders, value preview content, social proof, stakeholder expansion tactics.
6. DISCOVERY-TO-QUALIFICATION FRAMEWORK: AI-generated discovery call framework and qualification criteria (MEDDPICC/BANT adapted) to increase SQL conversion rate.
7. NO-SHOW RECOVERY: Automated rescue sequence for no-shows that re-books within 24 hours.
8. MEASUREMENT FRAMEWORK: KPIs, benchmarks, and weekly monitoring cadence.

Output a complete conversion architecture with specific copy, automation triggers, and implementation sequence.

## Advanced Customizable Version

ROLE: You are a VP of Revenue Operations and Demand Generation with 15+ years of B2B SaaS experience optimizing inbound pipeline conversion. You have a deep understanding of buyer psychology at the moment of high intent, the science of demo show rate optimization, and how AI personalization transforms generic inbound flows into revenue-producing machines. You understand that the demo request is the single highest-intent action a B2B buyer takes — and most companies squander it with slow follow-up, generic confirmation emails, and no pre-demo preparation. You speak the language of both CMOs (pipeline sourced, cost per SQL, inbound conversion rate) and CROs (show rate, SQL rate, sales cycle length). You design systems that turn high-intent signals into closed revenue with minimal human latency.

CONTEXT:
Company: [Company name]
Product: [Product category, primary use case, core differentiator in one sentence]
Business model: [B2B SaaS — ACV range: $X-$Y, sales motion: enterprise/mid-market/SMB/PLG-assisted]
Primary ICP: [Company size range, industry focus, key buyer persona titles]
Secondary ICPs: [If applicable — describe segments with different conversion motions]
Current stage: [ARR and growth rate]
Core CRM: [Salesforce / HubSpot]
Marketing automation platform: [Marketo / HubSpot / Pardot / other]
Sales engagement platform: [Outreach / Salesloft / Apollo / other]
Scheduling tool: [Calendly / Chili Piper / HubSpot Meetings / other]
Data enrichment stack: [Clearbit / 6sense / ZoomInfo / Clay / Bombora / other]
Conversational AI / chatbot: [Drift / Intercom / Qualified / none]
Call recording / intelligence: [Gong / Chorus / Avoma / none]

CURRENT-STATE FUNNEL METRICS:
Monthly website visitors: [X]
Demo request form views: [X]
Form submissions (demo requests): [X per month] → Form conversion rate: [X%]
Leads contacted by SDR within 5 minutes: [X%]
Leads contacted within 1 hour: [X%]
Demo requests that result in scheduled meetings: [X%]
Meetings held (show rate): [X%]
Discovery calls converting to SQL: [X%]
Overall demo request → SQL rate: [X%]
Average time from demo request to SQL: [X days]
Benchmark you're targeting: [e.g., "45% demo-to-SQL rate" or "70% show rate"]

SEGMENTATION:
Describe 2-4 distinct ICP segments that would receive different demo conversion experiences:
Segment 1: [Name, company size, industry, persona — e.g., "Enterprise: 1,000+ employees, Financial Services, CISO"]
Segment 2: [Name — e.g., "Mid-Market: 200-999 employees, SaaS/Tech, VP Engineering"]
Segment 3: [Name — e.g., "Growth: 50-199 employees, any industry, Head of Operations"]
Segment 4 (optional): [Name — e.g., "SMB PLG: <50 employees, self-serve signal, founder/CEO"]

INTENT SIGNALS AVAILABLE:
(Check all data sources you can access at time of demo request)
- [ ] Company firmographics via enrichment (Clearbit/ZoomInfo)
- [ ] Page visit history / session behavior
- [ ] Content consumed before requesting demo
- [ ] Ad source / UTM parameters
- [ ] G2/Capterra review pages visited
- [ ] Pricing page visited
- [ ] Competitive comparison pages visited
- [ ] Job postings from the account (technographic intent)
- [ ] 3rd party intent data (Bombora/6sense)
- [ ] LinkedIn profile data
- [ ] Prior email engagement
- [ ] Previous product trial / freemium usage data

CURRENT DEMO REQUEST FORM:
Fields currently collected: [List all fields]
Form location(s): [Where forms live — e.g., "Pricing page CTA, Homepage hero, Product feature pages"]
Hidden fields / UTM capture: [Yes/No — what's captured]
Post-submit redirect: [Confirmation page URL or "thank you message only"]
Current confirmation email: [Describe briefly or paste subject line]
Current SDR notification: [Slack alert / CRM task / email / none]
Current routing logic: [Round-robin / territory-based / segment-based / manual]

SALES TEAM CONTEXT:
SDR team size: [X SDRs]
AE team size: [X AEs]
Demo handled by: [SDR → AE handoff / AE runs discovery + demo / Founder-led / Customer Success-led]
SDR working hours: [Hours and time zones]
After-hours coverage: [AI SDR / Chatbot / None]
SDR quota per week (demos set): [X]
Discovery call duration: [X minutes]
Demo call duration: [X minutes]

KNOWN CONVERSION PROBLEMS:
(Describe in detail the specific drop-off points you're experiencing)
Biggest form friction issue: [e.g., "Prospects abandon when they see we ask for phone number"]
Biggest speed-to-lead challenge: [e.g., "SDRs average 4 hours to first contact during business hours"]
Biggest show rate challenge: [e.g., "40% of scheduled demos don't show — mostly Enterprise segment"]
Biggest discovery challenge: [e.g., "SDRs can't qualify budget on discovery calls — deals die in pipeline"]
Biggest post-no-show challenge: [e.g., "No-shows rarely rebook — SDRs give up after 2 attempts"]

COMPETITIVE CONTEXT:
Primary competitors: [List 2-3 main competitors]
What prospects typically say when comparing you to competitors: [e.g., "They're evaluating us against Competitor X and always ask about Y"]
Common objection at discovery stage: [e.g., "We're not sure if we have budget approved for this year"]

OUTPUT REQUIRED:

### 1. FORM ARCHITECTURE & PROGRESSIVE PROFILING DESIGN
Design a multi-stage form strategy:

**Stage 1 — Minimal Friction Form (public-facing):**
Fields to collect: [Specify exactly — email + 1-2 maximum enrichable fields]
AI enrichment at submit: [Which data sources to ping immediately with email domain]
Hidden fields: [UTM parameters, referrer, session data to capture]
Form copy: [Headline, subheadline, CTA button text — specific copy]

**Stage 2 — Post-Submit Progressive Profiling:**
After email capture, redirect to: [Enriched qualification questions if enterprise signal / Calendly direct if SMB signal]
Segment routing logic: [If company size > 500 → route to enterprise flow / else SMB self-serve flow]
What to ask in qualification questions: [3-4 questions that map to MEDDPICC criteria without feeling like an interrogation]

**Stage 3 — Enrichment-Informed Routing:**
Enrichment-based routing rules: [Specify exact firmographic triggers for each SDR/AE segment]
Scoring model inputs at demo request: [Which signals trigger immediate SDR alert vs. async nurture]

### 2. AI-PERSONALIZED POST-SUBMIT EXPERIENCE
Design the immediate post-submit experience for each ICP segment:

**Confirmation Page Design (per segment):**
[For Enterprise segment:]
- Headline: [Specific copy]
- Body: [What to show — case study relevant to their industry, ROI data point, next steps]
- Social proof: [Which customer logo/quote to display based on industry]
- Scheduling: [Immediate Calendly link for AE OR message that SDR will call in X minutes]
- Content offer: [Which relevant asset to surface based on UTM/referral source]

[For Mid-Market segment:]
- [Repeat above structure]

[For SMB/PLG segment:]
- [Self-scheduling link + trial activation if applicable]

**Confirmation Email (per segment):**
Subject line variants by segment: [Specific subject lines — 3 variants each]
Preview text: [Specific preview text]
Email body structure: [Outline the sequence — social proof → what to expect → content → scheduling link]
Send time: [Immediate / within 5 min]

**Internal SDR Notification:**
Slack alert format: [Exact Slack message template including enrichment data, intent signals, suggested personalized opener]
CRM task creation: [What fields auto-populate in CRM task for SDR]
Priority scoring: [How to surface Tier 1 accounts vs. Tier 3 in SDR queue]

### 3. SPEED-TO-LEAD AUTOMATION ARCHITECTURE
**Business Hours Workflow (immediate response):**
Trigger: Demo form submission
Step 1 [0-60 seconds]: AI enrichment pings (Clearbit/ZoomInfo/6sense data pull)
Step 2 [60-90 seconds]: Routing logic runs based on enrichment output
Step 3 [90 seconds - 5 min]: SDR Slack priority alert + CRM task + suggested call script
Step 4 [5 min]: If no SDR response → escalation alert to SDR manager
Step 5 [10 min]: If still no response → AI chatbot engagement on confirmation page
AI-suggested call opener for each segment: [Specific opening line SDR should use based on intent signals]

**After-Hours Workflow:**
Option A (AI SDR): [How Conversational AI should engage — opening message, qualification questions sequence, scheduling logic]
Option B (Next-day sequence): [Automated email + LinkedIn + morning SDR priority task with context summary]
After-hours promise: [What to tell prospects about follow-up timing to set expectations]

### 4. PRE-DEMO NURTURE SEQUENCE (Show Rate Optimization)
Design a 3-5 touch sequence from "demo scheduled" to "demo date":

**Touch 1 — Scheduling Confirmation [Immediate]:**
Calendar invite: [Title format, description template, video call link]
Confirmation email: [Subject line, body — what to include: agenda preview, prep materials, social proof]
Pre-read content: [What to send — case study, ROI calculator, competitive comparison relevant to their segment]

**Touch 2 — Value Primer [T-2 days before demo]:**
Channel: Email
Subject line: [Specific copy — create curiosity about what they'll see]
Content: [Customer outcome story in their industry, specific metric that makes it relevant]
CTA: [Confirm attendance / add to calendar / invite a colleague]

**Touch 3 — Stakeholder Expansion [T-2 days, if enterprise]:**
Message: [Template for asking prospect to bring a relevant stakeholder — framed as "maximize value of your time"]
Who to invite: [Suggest specific titles based on their ICP segment]

**Touch 4 — Day-Before Reminder:**
Channel: Email + SMS (if opted in) + LinkedIn DM
Email subject: [Specific copy — reminder + anticipation-building]
SMS text: [Specific copy — max 160 characters]
LinkedIn: [Brief personal message template from SDR/AE]

**Touch 5 — Day-Of Reminder [2 hours before]:**
Email/SMS: [Short, warm reminder with meeting link prominent]
What to include: [Agenda bullet points, any homework they said they'd do, direct dial backup]

### 5. SHOW RATE OPTIMIZATION TACTICS
Beyond the nurture sequence, specify:

**Meeting Title Psychology:**
Formula for calendar invite title that increases show rates: [Specific formula — e.g., "[Company Name] × [Your Company] — Revenue Operations Strategy Session" vs. "Demo with Company"]

**Agenda Commitment Technique:**
Template for pre-meeting agenda email that creates commitment and reduces no-shows: [Specific template — ask them to confirm one agenda item they care most about]

**Stakeholder Expansion Play:**
Script for expanding attendees beyond single contact: [Specific email/call script to invite decision-makers without feeling presumptuous]

**Cancellation Interception:**
When prospect tries to cancel: [Automated response template offering to reschedule immediately vs. cancel]
Cancellation re-engagement sequence: [3-touch rescue sequence if they cancel — timing, channels, copy]

**Benchmark Show Rate Targets by Segment:**
Enterprise: [X%]
Mid-Market: [X%]
SMB: [X%]
Below-benchmark triggers: [When to escalate and review specific segment's show rate]

### 6. DISCOVERY-TO-QUALIFICATION CONVERSION FRAMEWORK
Design the AI-powered discovery call preparation and qualification system:

**Pre-Call Intelligence Brief (AI-generated for each SDR/AE):**
What the brief should include:
- Account research summary [LinkedIn company page, recent funding, headcount growth, tech stack]
- Contact research [LinkedIn profile, recent posts, mutual connections, job tenure]
- Intent signal summary [Pages visited, content consumed, ad source, 3rd party intent if available]
- Competitor exposure [If they've visited G2 comparing you to a competitor]
- Suggested opening hypothesis: [AI-generated opener based on all signals — e.g., "Based on your recent hiring for 3 RevOps roles and the fact that you visited our pricing page after reading our Salesforce integration guide..."]

**Discovery Call Framework (MEDDPICC-informed):**
For each qualification criterion, specify the question and expected qualifying answer:

Metrics:
- Discovery question: [Specific question to uncover quantified pain]
- Qualifying indicator: [What answer means they're qualified]
- Disqualifying indicator: [Red flag answer]

Economic Buyer:
- Discovery question: [Who owns this budget? How to ask without alienating]
- Qualifying indicator: [They have access to Economic Buyer]

Decision Process:
- Discovery question: [How do they buy software? Who's involved?]
- Qualifying indicator: [Clear process with reasonable timeline]

Decision Criteria:
- Discovery question: [What does "success" look like to them?]
- Qualifying indicator: [Criteria you can win]

Identified Pain:
- Discovery question: [What's the consequence of not solving this?]
- Qualifying indicator: [Quantified business pain with urgency]

Champion:
- Discovery question: [Are they invested? Will they push internally?]
- Qualifying indicator: [Willingness to schedule next meeting with Economic Buyer]

**Post-Discovery AI Scoring:**
Auto-scored qualification summary that SDR/AE completes in CRM within 15 minutes post-call:
[Specify the 5-7 field quick-score form that generates a MEDDPICC health score]
Score thresholds: [80+ = pass to AE immediately / 50-79 = nurture + follow-up / <50 = MQL recycle]

### 7. NO-SHOW RECOVERY ARCHITECTURE
**Same-Day Rescue (within 2 hours of missed demo):**
Channel: Email + SMS simultaneously
Email subject: [Specific copy — empathetic, not annoying]
Email body: [Short — acknowledge missed meeting, offer 2 specific reschedule times OR Calendly link, value reminder]
SMS text: [Specific copy — 160 characters max]

**Day 2 Recovery:**
Personal LinkedIn message from AE/SDR: [Specific template]
Re-engagement hook: [Tie to something timely — recent company news, industry event, new case study]

**Day 4 Final Attempt:**
Email subject: [Break-up style — creates urgency without pressure]
Body: [Short — acknowledge they're busy, give them an easy out, leave door open]
Offer: [Alternative to full demo — 15-min exec briefing, async video, product trial]

**No-Show Recycle Protocol:**
After 3 failed recovery attempts: [Move to long-term nurture / SDR cadence / specific re-engagement trigger]
Re-engagement triggers: [6sense intent spike / job change / pricing page revisit / competitor G2 review]

### 8. MEASUREMENT & OPTIMIZATION CADENCE

**Primary KPIs and Benchmarks:**
| Metric | Your Current | B2B SaaS Benchmark | Your 90-Day Target |
|--------|-------------|-------------------|-------------------|
| Form completion rate | X% | 12-18% | X% |
| Demo request → scheduled meeting | X% | 55-65% | X% |
| Speed-to-lead (business hours) | X min | <5 min | X min |
| Show rate | X% | 65-75% | X% |
| Discovery → SQL rate | X% | 35-50% | X% |
| Demo request → SQL rate (overall) | X% | 25-40% | X% |
| Demo request → closed won (90 days) | X% | 8-15% | X% |

**Weekly Review Cadence:**
Every Monday: [Which metrics to review, who reviews them, what triggers investigation]
Every Friday: [SDR outreach velocity check, show rate rolling 30-day, routing efficiency]

**A/B Test Roadmap (first 90 days):**
Month 1: [Form test — X vs. Y field count / confirmation page CTA test]
Month 2: [Pre-demo nurture — 3-touch vs. 5-touch / day-before reminder channel test]
Month 3: [Discovery call framework — qualification question sequence test / AI-brief adoption rate vs. non-users]

**Anomaly Triggers:**
If show rate drops below X% in any 7-day period → [Investigation and response protocol]
If speed-to-lead exceeds 15 min average → [SDR coverage review trigger]
If SQL rate drops below X% → [Discovery call recording audit protocol]

## Example Input/Output

**Example Company**: Meridian AI — B2B SaaS revenue intelligence platform for mid-market SaaS companies (200-2,000 employees). ACV $42K. Salesforce + Outreach + Chili Piper + Clearbit + 6sense. SDR team of 8, AE team of 6. Current: 180 demo requests/month, 58% schedule rate, 54% show rate, 28% show-to-SQL, 8.7% overall demo-to-SQL.

**Sample AI-Generated Output (Excerpt):**

**Segment Routing Logic (Clearbit-triggered, executes within 90 seconds of form submit):**
- Company size ≥500 AND industry = SaaS/FinTech/MarTech → Enterprise queue → immediate AE Slack alert + Chili Piper forced scheduling redirect
- Company size 200-499 → Mid-Market SDR queue → Slack alert within 5 min → Outreach sequence auto-enrolled
- Company size 50-199 → Growth SDR queue → Outreach sequence starts immediately, SDR call attempt within 30 min
- Company size <50 AND no 6sense intent score → PLG nurture → trial activation email + product tour video

**Enterprise Confirmation Email (Clearbit-detected: 800-person FinTech, VP Revenue):**
Subject: "Your Meridian session — what we're customizing for you"
Preview: "We pulled some context on Apex Financial before our call."

> Hi [First Name],
> 
> Thanks for requesting a Meridian demo. I've already pulled together some context on Apex Financial's current revenue stack to make sure we don't waste your time with a generic walkthrough.
> 
> Before our session, I wanted to share how Crossbeam (a similar-sized FinTech) reduced their forecast variance from 34% to 8% in one quarter using Meridian's deal intelligence layer. I think the parallels to your situation will be immediately obvious.
> 
> [Read the Crossbeam case study →]
> 
> I'll send a calendar invite shortly with an agenda tailored to your role. If there's someone from your RevOps or finance team who should join, now's the perfect time — executives at your level tend to get 3x more value when their RevOps lead is in the room.
> 
> Talk soon,
> [AE Name, Meridian]

**Show Rate Benchmark Results After Implementing This Architecture (example outcomes from similar B2B SaaS deployments):**
- Show rate: 54% → 71% (31% improvement)
- Overall demo-to-SQL: 8.7% → 17.4% (100% improvement)
- Speed-to-lead: 4.2 hours → 6 minutes
- Monthly SQLs from inbound: 15 → 31

## Success Metrics

**This prompt produced a high-quality output if:**
- Form optimization reduces friction to 2-3 fields with clear enrichment logic for missing data
- Post-submit personalization is segment-specific, not generic — different confirmation copy for enterprise vs. SMB
- Speed-to-lead automation has explicit trigger logic, not vague "notify the SDR"
- Pre-demo nurture sequence has specific subject lines, not placeholder copy
- Show rate tactics include specific calendar title formulas and agenda commitment scripts
- Discovery framework maps to MEDDPICC with segment-specific qualifying questions
- No-show recovery has timed follow-up sequences with specific copy, not just "send a follow-up"
- KPI table includes current state, benchmarks, and specific 90-day targets

**Benchmark targets your implementation should reach within 90 days:**
- Form completion rate: >15%
- Demo request → scheduled meeting: >60%
- Speed-to-lead (business hours): <5 minutes
- Show rate: >68%
- Discovery → SQL rate: >40%
- Overall demo request → SQL: >25%

## Related Prompts
- [AI-Powered B2B SaaS Lead Capture Optimization](./AI-Powered-B2B-SaaS-Lead-Capture-Optimization-&-Conversion-Friction-Elimination-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Voice AI Lead Response](./AI-Powered-B2B-SaaS-Voice-AI-Lead-Response-&-Speed-to-Lead-Conversion-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Post-Demo Nurture Sequence](../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/AI-Powered-B2B-SaaS-Post-Demo-Nurture-Sequence-&-Buying-Committee-Deal-Velocity-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Demo Show Rate Analytics](../../05_Analytics-&-Performance/Conversion-Rate-Optimization-Analytics/AI-Powered-B2B-SaaS-Demo-Show-Rate-Analytics-&-No-Show-Revenue-Recovery-Intelligence-Engine.md)

## Integration Tips

**HubSpot:**
- Use HubSpot's workflow branching to route by Clearbit-enriched company size at form submit
- Set up contact scoring property "Demo_Intent_Score" to surface priority leads in SDR views
- Connect Meetings tool for automatic show tracking and no-show workflow triggers
- Use Sequences to auto-enroll in pre-demo nurture the moment a meeting is booked

**Salesforce + Outreach:**
- Build a "Demo Request" lead source with enrichment trigger via Process Builder/Flow
- Create Outreach sequence "Pre-Demo High-Intent" with dynamic variables pulling from Salesforce fields
- Set up Salesforce Einstein Activity Capture to auto-log email engagement as lead score inputs
- Configure Chili Piper routing rules with Salesforce field conditions for segment-based AE routing

**Calendly / Chili Piper:**
- Create segment-specific meeting types with different buffer times (Enterprise = 60 min / SMB = 30 min)
- Set up automatic calendar invite customization using meeting invitee's Clearbit-enriched data
- Configure no-show webhooks to trigger the immediate recovery sequence in your MAP

**Gong / Chorus:**
- Tag demo calls with segment and ICP match score for pattern analysis
- Build a "Discovery Framework Adherence" tracker — auto-flag calls where SDR didn't ask qualifying questions
- Create a "Best Demo" playlist from top-performing discovery calls for SDR training

**Slack:**
- Build a #inbound-demos channel with bot alerts formatted as: Account name | Size | Industry | Intent score | UTM source | Suggested opener | Calendar link
- Create a daily digest of demo pipeline health: scheduled vs. actual show rate, SDR speed-to-lead average

**Clay:**
- Use Clay to waterfall enrich demo requests across Clearbit → ZoomInfo → LinkedIn → Apollo before SDR notification
- Build a Clay table that auto-generates a personalized pre-call brief for every demo request within 2 minutes of form submit

## Troubleshooting

**Problem: Show rate improves but SQL rate stays flat**
Cause: Pre-demo nurture is warming them up but discovery calls lack qualification rigor. Fix: Audit 10 discovery call recordings for MEDDPICC adherence. Implement mandatory post-call MEDDPICC scoring in CRM before AE handoff. Run a 2-hour discovery call framework training session with roleplay using Gong examples.

**Problem: Speed-to-lead is under 5 minutes but schedule rate doesn't improve**
Cause: Fast contact ≠ right message. SDRs are calling quickly but using a generic opener that doesn't match the prospect's context. Fix: Implement the AI-generated pre-call brief requirement — no SDR should make the first call without reading the intent signal summary. A/B test: personalized opener (referencing their page visits / company news) vs. generic opener. Track schedule rate by SDR and opener type.

**Problem: After-hours demo requests consistently convert at 40% lower rate**
Cause: Buying intent decays fast — a prospect who requested a demo at 10pm on Thursday loses urgency by Monday morning. Fix: Deploy a conversational AI SDR (Qualified, Drift, or Intercom) to engage after-hours requests within 60 seconds — qualify, answer initial questions, and book a meeting before they leave the website. If this isn't feasible, implement a same-night automated email with direct Calendly link and a compelling "reason to meet" asset that creates urgency to book before they forget.

## Version History
- v1.0: Initial creation (auto-generated)
