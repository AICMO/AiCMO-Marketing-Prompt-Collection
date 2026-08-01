# AI-Powered B2B SaaS Voice AI SDR Performance Analytics & Autonomous Outbound Call Revenue Attribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** voice-ai, ai-sdr, outbound-analytics, revenue-attribution, conversation-intelligence, pipeline, b2b, autonomous-agents, call-performance, saas

## Overview

This prompt builds a complete analytics and revenue attribution system for autonomous Voice AI SDR programs — measuring call connection rates, conversation quality scores, objection-handling effectiveness, pipeline contribution by call cohort, and cost-per-pipeline-dollar versus human SDR benchmarks. Use it when you have deployed AI voice agents for outbound prospecting and need to prove revenue impact, identify which call scripts and prospect segments convert best, and continuously optimize your AI agent's conversation model.

## Quick Copy-Paste Version

You are a senior B2B revenue analytics strategist with deep expertise in AI-powered outbound sales programs and conversation intelligence measurement. My company sells [PRODUCT/CATEGORY] to [ICP: job titles + company size + industry]. We have deployed a Voice AI SDR system ([TOOL: e.g., Artisan, 11x, Relevance AI, or custom-built]) making autonomous outbound calls to [X] prospects per month.

Build a complete analytics and attribution framework to measure our Voice AI SDR program's revenue contribution and optimize conversation performance.

1. CALL PERFORMANCE FUNNEL ANALYTICS:
   - For each call cohort (segment, persona, call script variant), calculate:
     * Dial-to-connect rate: % of dials resulting in a live conversation (target: 8-15% with AI caller ID optimization)
     * Connect-to-conversation rate: % of connected calls where prospect stays on longer than 45 seconds
     * Conversation-to-meeting rate: % of substantive conversations that book a qualified meeting
     * Meeting-to-opportunity rate: % of AI-booked meetings that become open pipeline
     * Opportunity-to-closed-won rate: pipeline closed from Voice AI SDR source
   - Calculate pipeline velocity by source: how many days from first AI call to closed-won vs. human SDR
   - Rank prospect segments by cost-per-meeting and cost-per-pipeline-dollar

2. CONVERSATION QUALITY SCORING MODEL:
   - Define a Conversation Quality Score (CQS) from 0-100 based on: prospect engagement duration, questions asked by prospect, objections raised and successfully navigated, meeting acceptance rate, post-call email engagement
   - Identify which script elements and conversation flows correlate with CQS >70 (meetings booked) vs. CQS <30 (immediate hang-ups)
   - Flag "ghost meetings" risk: AI-booked meetings with CQS <40 that have high no-show probability
   - Analyze objection frequency and resolution rate by objection type: "Not interested," "Already have a solution," "Wrong person," "Call me back," "Send an email"

3. CALL TIMING & SEQUENCE INTELLIGENCE:
   - Identify optimal call windows by day-of-week and hour for each ICP segment using connect rate data
   - Measure "call cadence fatigue": does connect rate drop after the 2nd, 3rd, or 4th AI call attempt to the same prospect?
   - Determine optimal time gap between call attempts (same-day, next-day, 3-day, 7-day gaps)
   - Analyze impact of voicemail messages on eventual connect rate: do AI voicemails left on attempt 1 improve connect rates on attempt 2?

4. VOICE AI VS. HUMAN SDR BENCHMARKING:
   - Calculate fully-loaded cost per meeting: Voice AI (platform cost + infrastructure) vs. human SDR (salary + benefits + tools + ramp time)
   - Compare quality metrics: AI-booked meeting show rates vs. human SDR meeting show rates
   - Identify which prospect segments the AI outperforms humans on (e.g., SMB, inbound re-engagement, event follow-up) vs. underperforms (e.g., enterprise, complex multi-stakeholder deals)
   - Build a "handoff intelligence model": at what conversation stage should AI hand off to human (triggered by intent signals detected in the call)

5. WEEKLY VOICE AI SDR PERFORMANCE REPORT:
   - 1-page executive summary: dials made, conversations had, meetings booked, pipeline created, top-converting script variant, worst-performing call cohort to pause/optimize
   - Include a "call waste rate": % of dials with no outcome that represent fixable problems (wrong number, unsubscribed contact, duplicate outreach)
   - Conversation intelligence highlights: top 3 objection patterns from the week and recommended script updates

Output: Complete measurement framework, conversation quality scoring model, timing optimization playbook, AI vs. human SDR benchmark dashboard, and weekly reporting template — ready to implement in your CRM, conversation intelligence platform, and BI tool.

## Advanced Customizable Version

ROLE: You are a VP of Revenue Analytics and AI Sales Operations with 15+ years of experience building performance measurement systems for high-velocity B2B outbound sales programs. You specialize in conversation intelligence analytics, AI agent performance optimization, and proving revenue contribution from emerging GTM technology to skeptical boards and CFOs. You understand that Voice AI SDR programs in 2026 require a fundamentally different measurement architecture than traditional human SDR programs — because the call volume is 10-50x higher, the data is richer (every conversation is recorded and transcribed), and the optimization levers are different (script logic, timing algorithms, voice model selection, objection handling trees).

COMPANY CONTEXT:
- Product: [PRODUCT NAME] — [1-sentence description of what it does and who it's for]
- ICP: [TARGET JOB TITLES] at [COMPANY SIZE] [INDUSTRY] companies
- ACV: [$X] | Average sales cycle: [X days] | Deal complexity: [transactional/consultative/enterprise]
- Voice AI SDR platform: [Artisan / 11x / Relevance AI / Bland AI / custom-built on ElevenLabs + LLM]
- Monthly call volume: [X dials/month] | Target connect rate: [X%]
- CRM: [Salesforce/HubSpot/other] | Conversation intelligence: [Gong/Chorus/native platform]
- BI tool: [Tableau/Looker/Metabase/other]
- Human SDR team size for benchmarking: [X reps]
- Current measurement gaps: [e.g., "can't track which call script variant drove the meeting," "no way to measure conversation quality systematically"]
- Primary ICP segments being called: [Segment A: X%, Segment B: Y%, Segment C: Z%]
- Call script variants currently running: [Name and brief description of each A/B test]

OBJECTIVE: Build a comprehensive analytics and attribution system that:
1. Quantifies pipeline and revenue contribution of the Voice AI SDR program with CFO-level rigor
2. Identifies which prospect segments, call scripts, and timing strategies maximize meeting conversion
3. Builds a conversation quality model that predicts meeting show rate and pipeline quality before the meeting happens
4. Benchmarks Voice AI ROI against human SDR cost and output with honest apples-to-apples comparison
5. Creates a continuous optimization loop: weekly insights that automatically improve the AI agent's conversation logic

---

DELIVERABLE 1 — VOICE AI SDR CONVERSION FUNNEL ARCHITECTURE:

Define each funnel stage with precise measurement instructions:

Stage 1 — Prospect Pool Quality:
- Definition: Contacts in the Voice AI SDR calling queue that meet ICP qualification criteria
- Measurement: ICP fit score distribution of calling list (% scoring 80+, 60-79, 40-59, <40)
- Data enrichment requirements: job title confirmed, direct phone verified, company size verified, not in DNC list, no active opportunity in CRM
- Quality gate: what % of imported contacts pass all enrichment checks? Flag vendors/lists with <60% pass rate
- Recommended data sources: [Apollo, ZoomInfo, Clay, Cognism] for phone number verification

Stage 2 — Dial Execution:
- Definition: Voice AI agent initiates an outbound call to a qualified prospect
- Measurement: total dials per day/week, dials per prospect (attempt tracking), time-of-day distribution
- Caller ID optimization: track connect rate by caller ID type (local presence, toll-free, direct line) — local presence numbers typically improve connect rates by 40-60%
- Abandonment analysis: % of dials where AI hangs up before connect (system errors, DNC matches, voicemail detection failures)

Stage 3 — Connection:
- Definition: Prospect answers the call and the AI agent begins the conversation
- Measurement: dial-to-connect rate by segment, day-of-week, hour, caller ID type, and number of previous attempts
- Voicemail detection accuracy: % of calls correctly identified as voicemail vs. live answer (false positive = AI delivers pitch to voicemail; false negative = AI leaves message for live person)
- Voicemail strategy analysis: measure callback rate from AI voicemails left at attempt 1 vs. no voicemail

Stage 4 — Substantive Conversation (>45 seconds):
- Definition: Connected call where prospect engages with the AI agent beyond the initial introduction
- Measurement: connect-to-conversation rate (target: >65% of connected calls lasting >45 seconds)
- Drop-off analysis: transcript analysis of calls that end in 0-30 seconds — what was the last thing the AI said? What was the prospect's response? (e.g., "I already have something," "Not interested," silence)
- Conversation depth metric: median call duration for conversations that book meetings vs. don't

Stage 5 — Meeting Booked:
- Definition: Prospect verbally agrees to a meeting during the AI call AND the meeting is confirmed (calendar invite accepted or meeting link clicked)
- Measurement: conversation-to-meeting rate, meeting confirmation rate (verbal agreement → calendar accepted), time from call end to calendar confirmation
- Qualified meeting criteria: [Define what makes a meeting "qualified" — e.g., correct job title, budget authority indicator, explicit use case fit mentioned during call]
- Ghost meeting risk score: assign probability of no-show based on CQS, confirmation status, seniority of contact, time gap between call and meeting

Stage 6 — Pipeline Created:
- Definition: AI-booked meeting results in a qualified opportunity created in CRM
- Measurement: meeting-to-opportunity rate, average pipeline value per Voice AI SDR opportunity vs. human SDR
- Opportunity quality indicators: deal size vs. ACV target, days to next stage progression, buyer engagement score
- Source attribution: tag all opportunities with "Voice-AI-SDR" as primary source, track through to closed-won for full-funnel attribution

Stage 7 — Revenue Closed:
- Definition: Voice AI SDR-sourced opportunity reaches Closed Won
- Measurement: close rate by segment and script variant, average deal size, sales cycle length vs. other sources
- CAC calculation: (Voice AI platform cost + infrastructure + human oversight hours × loaded rate) ÷ customers acquired from Voice AI SDR source
- LTV:CAC ratio: track 6-month and 12-month revenue from Voice AI SDR customers vs. other acquisition sources

---

DELIVERABLE 2 — CONVERSATION QUALITY SCORING (CQS) FRAMEWORK:

Build a Conversation Quality Score (0-100) that predicts pipeline quality before the meeting happens:

CQS Component Weights (total = 100 points):

1. Call Duration Score (0-20 points):
   - <30 seconds = 0 points (immediate rejection)
   - 30-60 seconds = 5 points (polite decline or voicemail)
   - 1-2 minutes = 10 points (surface-level engagement)
   - 2-4 minutes = 16 points (substantive conversation)
   - 4+ minutes = 20 points (deep engagement, multiple questions)

2. Prospect Engagement Signals (0-25 points):
   - Prospect asked at least one question about the product: +8 points
   - Prospect volunteered a pain point or challenge: +10 points
   - Prospect mentioned a current vendor or solution: +4 points (competitive context)
   - Prospect shared budget or timeline information: +3 points

3. Objection Navigation Score (0-20 points):
   - No objections raised (easy meeting): 10 points (neutral — may indicate low-quality contact)
   - Objection raised AND successfully navigated to meeting: 20 points (highest quality indicator)
   - Objection raised, partially addressed, meeting still booked: 12 points
   - Objection raised, not resolved, meeting booked anyway: 6 points (high ghost meeting risk)
   - Objection raised, not resolved, no meeting: 0 points

4. ICP Fit Confirmation (0-20 points):
   - Prospect confirmed correct job title and decision-making authority: +10 points
   - Prospect confirmed company fit (size, industry, tech stack match): +6 points
   - Prospect mentioned active initiative or budget cycle relevant to product: +4 points

5. Meeting Confirmation Quality (0-15 points):
   - Calendar invite accepted within 1 hour of call: 15 points
   - Calendar invite accepted within 24 hours: 10 points
   - Meeting confirmed verbally but invite pending: 5 points
   - No confirmation status (ghost meeting risk): 0 points

CQS Interpretation:
- 80-100: High-quality opportunity — fast-track for human AE outreach, add to enterprise nurture
- 60-79: Solid opportunity — standard AE follow-up within 24 hours
- 40-59: Moderate quality — AE follow-up within 48 hours, additional qualification call recommended
- <40: High ghost meeting risk — trigger automated re-confirmation sequence, consider reschedule proactively

---

DELIVERABLE 3 — CALL TIMING OPTIMIZATION MODEL:

Build a data-driven call scheduling algorithm:

Time-of-Day Analysis:
- Segment connect rate data by hour (6am-8pm prospect local time)
- Identify peak connect windows: typically 8-9am, 11am-12pm, 4-5pm (but validate with your actual data)
- Build segment-specific timing models: C-suite contacts may peak at 7:30-8:30am; managers may peak mid-morning
- Exclude low-performance windows from AI call scheduling to protect caller ID reputation

Day-of-Week Analysis:
- Calculate connect rate and conversation-to-meeting rate by day
- Identify "meeting-booking days" vs. "conversation-only days" — Tuesday/Wednesday typically peak for meeting acceptance
- Build "day weighting" into the AI scheduling algorithm: weight high-performing days 2x vs. low-performing days

Attempt Sequencing Model:
- Map connect rate by attempt number: does attempt 2 outperform attempt 1 because voicemail primes the prospect?
- Identify the "dead zone": at what attempt number does connect rate drop below cost-effective threshold (typically attempt 4-5 for AI callers)?
- Build "attempt spacing rules": optimal gap between attempt 1 and 2 (same day? next day?), between attempt 3 and 4 (3 days? 7 days?)
- Test mixed-channel sequences: AI call → automated email → AI call → LinkedIn view → final AI call

---

DELIVERABLE 4 — VOICE AI VS. HUMAN SDR ROI BENCHMARK:

Build an honest, CFO-ready comparison:

Cost Model — Voice AI SDR:
- Platform cost per month: [$X/month for [X] dials]
- Infrastructure costs: [CRM integration, phone numbers, data enrichment]
- Human oversight cost: [X hours/week × fully-loaded hourly rate for human SDR manager/QA reviewer]
- Total monthly cost: $[X]
- Cost per dial: $[X]
- Cost per connect: $[X]
- Cost per meeting booked: $[X]
- Cost per opportunity created: $[X]
- Cost per dollar of pipeline: $[X]

Cost Model — Human SDR (fully-loaded):
- Salary + benefits + employer taxes: $[X/year] = $[X/month]
- Sales tools (Outreach/Salesloft, LinkedIn Sales Nav, phone): $[X/month]
- Ramp time cost (assume 3 months at 50% productivity): amortized $[X/month]
- Manager time (assume 2 hours/week): $[X/month]
- Total monthly cost: $[X]
- Monthly dials (realistic for human): [300-500 dials/month for high-volume SDR]
- Cost per meeting booked: $[X]

Apples-to-Apples Quality Adjustment:
- AI meeting show rate vs. human SDR meeting show rate: if human SDR meetings show at 75% and AI at 60%, adjust pipeline value accordingly
- Opportunity-to-close rate: if human-sourced opportunities close at 25% and AI at 18%, apply quality discount to AI pipeline value
- ACV comparison: are AI-sourced deals the same size as human-sourced? Document discrepancy
- Net result: "AI-equivalent pipeline value" = raw pipeline × (AI show rate / human show rate) × (AI close rate / human close rate)

ROI Decision Matrix — Segments to Run AI vs. Human:
- Best for Voice AI: SMB (<100 employees), inbound lead re-engagement, event attendee follow-up, competitive displacement suspects, churn reactivation
- Best for human SDR: enterprise (>500 employees), existing customer expansion (CSQL), complex multi-stakeholder buying (4+ stakeholders), deals requiring deep technical discovery

---

DELIVERABLE 5 — CONTINUOUS OPTIMIZATION LOOP:

Build a weekly analytics-to-action system:

Weekly Voice AI SDR Report (1-page format):
- Week summary: [X] dials → [X] connects ([X]% rate) → [X] conversations ([X]% rate) → [X] meetings ([X]% rate) → [X] pipeline ($[X])
- Script variant performance: Variant A vs. B vs. C by conversation-to-meeting rate
- Segment performance: which ICP segments are converting above/below target?
- Objection heat map: top 5 objections this week by frequency and resolution rate
- Ghost meeting watch list: meetings scheduled this week with CQS <40 (send re-confirmation outreach)
- One recommended optimization: highest-impact change to script, timing, or prospect list based on this week's data

Monthly Optimization Sprint:
- Conversation transcript analysis: pull 50 random transcripts from high-CQS (>70) and low-CQS (<30) calls — identify what language patterns and conversation flows differentiate them
- Script update recommendations: 3-5 specific changes to call script logic, objection handling trees, or opening hooks with A/B test hypothesis
- List quality review: which lead sources are producing the highest connect rates and lowest "wrong person" rates?
- AI model performance review: if using a custom voice model, assess voice naturalness scores and call abandonment rates

---

DELIVERABLE 6 — TECHNICAL IMPLEMENTATION SPECIFICATIONS:

CRM Data Architecture:
- Custom object: "Voice AI Call" linked to Contact + Account + Opportunity
- Required fields: call_date, call_duration_seconds, connect_status, voicemail_left, conversation_quality_score, objections_raised (multi-select), meeting_booked (boolean), meeting_confirmed (boolean), script_variant_id, attempt_number, caller_id_used
- Conversation intelligence integration: auto-sync call transcripts and AI-generated summaries to CRM activity log
- Attribution tagging: all opportunities from Voice AI SDR tagged with source="Voice-AI-SDR", campaign="[program name]", script_variant="[ID]"

Dashboard Requirements (Tableau/Looker/Metabase):
- Executive dashboard: pipeline created, cost per meeting, AI vs. human SDR comparison (updated weekly)
- Operations dashboard: funnel metrics by segment and script variant (updated daily)
- Conversation intelligence dashboard: CQS distribution, top objections, meeting ghost risk (updated daily)
- Optimization dashboard: A/B test results, timing optimization, list quality scores (updated weekly)

Alerting Rules:
- Alert when: connect rate drops >20% week-over-week (caller ID flagged or list quality issue)
- Alert when: ghost meeting rate exceeds 30% in a week (CQS scoring issue or poor prospect targeting)
- Alert when: cost per meeting exceeds [$X threshold] for 2 consecutive weeks (escalate to leadership)
- Alert when: conversation-to-meeting rate drops below [X%] baseline (script optimization needed immediately)

## Example Input/Output

**Input Example:**

Company: TalentPulse — AI-powered hiring analytics platform for HR teams at 200-2000 employee companies
ICP: VP HR, Head of Talent Acquisition, CHROs at Series C+ tech companies and mid-market financial services
ACV: $42,000 | Sales cycle: 67 days | Team: 3 human AEs, Voice AI SDR on Bland AI
Monthly call volume: 3,200 dials/month | Current connect rate: 9.2%
CRM: HubSpot | Conversation intelligence: Gong | BI: Looker
Human SDR benchmark: 1 full-time SDR, 420 dials/month, $8,200/month loaded cost

**Output Example (excerpt):**

VOICE AI SDR PERFORMANCE SUMMARY — TalentPulse Q2 2026:

FUNNEL PERFORMANCE:
- 3,200 dials → 294 connects (9.2%) → 178 conversations >45s (60.5%) → 31 meetings booked (17.4% conversation rate) → 24 meetings showed (77.4% show rate) → 12 opportunities created ($504,000 pipeline) → 3 Closed Won ($126,000 ARR)

COST MODEL (vs. Human SDR):
- Voice AI cost: $2,800/month (Bland AI platform + enrichment) + $1,200 oversight = $4,000 total
- Cost per meeting: $4,000 ÷ 31 = $129/meeting
- Human SDR cost: $8,200/month total
- Human SDR meetings (estimated): 18 meetings/month (industry benchmark for 420 dials, 15% connect, 22% conversion)
- Human SDR cost per meeting: $8,200 ÷ 18 = $456/meeting
- Voice AI advantage: 72% lower cost per meeting — but quality-adjusted pipeline value shows AI meetings close at 12.5% vs. human SDR meetings at 22%, so net effective cost per pipeline dollar is roughly equal
- RECOMMENDATION: Run Voice AI for SMB/Series C targets; reserve human SDR for >1,000 employee enterprise and CHRO direct outreach

TOP CONVERTING SCRIPT VARIANT:
- Variant C ("Hiring velocity hook"): "I noticed [Company] posted 23 engineering roles in the last 60 days — at that growth rate, how are you currently tracking time-to-fill across departments?" — 24.1% conversation-to-meeting rate vs. 13.2% for Variant A
- Immediate action: Roll Variant C to 100% of volume; archive Variant A; create Variant D testing alternative pain-point hook for financial services segment

TOP OBJECTION REQUIRING SCRIPT UPDATE:
- "We already use Greenhouse for this" — fired 41 times, resolved to meeting 7 times (17% resolution rate)
- Current script response performing poorly: "We actually integrate with Greenhouse..."
- Recommended new response: "That's great — most of our customers use Greenhouse for ATS. Where they hit limits is on the analytics side: tracking quality-of-hire and 90-day performance back to source. Is that a gap you're measuring today?" — projected to increase resolution rate to 35%+

## Success Metrics

- Connect rate trending up week-over-week for core ICP segments (target: >10% for verified phone numbers)
- Conversation Quality Score distribution shifting right: >40% of conversations scoring 60+ within 60 days of optimization
- Ghost meeting rate below 25% (industry benchmark for AI-booked meetings)
- Cost per meeting below human SDR cost per meeting (or within 20% with quality-adjustment)
- AI-sourced pipeline coverage: Voice AI SDR contributing ≥15% of total pipeline within 90 days
- Monthly optimization cadence established: at least 1 script variant update per week based on CQS data

## Related Prompts

- [`../../04_Demand-&-Lead-Generation-&-Growth/Voice-AI-SDR/AI-Powered-B2B-SaaS-Voice-AI-Autonomous-Outbound-SDR-Pipeline-Architecture-&-Agentic-Cold-Calling-Revenue-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Voice-AI-SDR/AI-Powered-B2B-SaaS-Voice-AI-Autonomous-Outbound-SDR-Pipeline-Architecture-&-Agentic-Cold-Calling-Revenue-Intelligence-Engine.md) — Build and launch the Voice AI SDR program this analytics engine measures
- [`../../04_Demand-&-Lead-Generation-&-Growth/Voice-AI-SDR/AI-Powered-B2B-SaaS-Voice-AI-Post-Event-Follow-Up-&-Webinar-Attendee-Pipeline-Conversion-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Voice-AI-SDR/AI-Powered-B2B-SaaS-Voice-AI-Post-Event-Follow-Up-&-Webinar-Attendee-Pipeline-Conversion-Intelligence-Engine.md) — Specialized Voice AI motion for event/webinar follow-up with dedicated analytics
- [`../../05_Analytics-&-Performance/Demand-Generation-Program-Analytics/AI-Powered-B2B-SaaS-AI-SDR-Program-Analytics-&-Outbound-Revenue-Contribution-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Demand-Generation-Program-Analytics/AI-Powered-B2B-SaaS-AI-SDR-Program-Analytics-&-Outbound-Revenue-Contribution-Intelligence-Engine.md) — Broader AI SDR program analytics including email and LinkedIn channels
- [`../../04_Demand-&-Lead-Generation-&-Growth/Demand-Generation-Operations/AI-Powered-B2B-SaaS-Lead-Scoring-Architecture-&-MQL-Pipeline-Qualification-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Demand-Generation-Operations/AI-Powered-B2B-SaaS-Lead-Scoring-Architecture-&-MQL-Pipeline-Qualification-Intelligence-Engine.md) — Integrate Voice AI SDR meeting quality scores into your broader MQL qualification model

## Integration Tips

- **HubSpot:** Create a custom "Voice AI Call" object using HubSpot's Custom Objects API. Use Zapier or Make to push Bland AI/Artisan call data into HubSpot properties. Build a Voice AI SDR pipeline stage in your deals board to separate from human SDR-sourced pipeline.
- **Salesforce:** Use Custom Activities (Task records with custom fields) to log each Voice AI call. Build a Salesforce Flow that automatically creates an Opportunity record when a call result = "Meeting Booked" and CQS > 40. Use Campaign attribution to track Voice AI SDR as a campaign source.
- **Gong:** Connect your Voice AI platform to Gong via API to auto-import call transcripts. Use Gong's Smart Trackers to automatically tag calls where competitors are mentioned, budget signals appear, or objections are raised — these feed your CQS scoring model.
- **Looker/Tableau:** Build a funnel visualization using your CRM pipeline stage data. Use a date-spine join to calculate time-between-stages (call → meeting → opportunity → close) and compare Voice AI SDR vs. human SDR velocity.
- **Clay:** Use Clay as your prospect enrichment and phone verification layer before importing lists into your Voice AI platform. Build a Clay table that scores ICP fit and validates phone numbers, exporting only verified 70+ ICP score contacts to your calling queue — this alone typically improves connect-to-conversation rates by 15-25%.
- **Notion/Confluence:** Templatize the weekly Voice AI SDR report in Notion. Use Zapier to auto-populate key metrics from HubSpot/Salesforce each Friday morning so the report is ready for Monday leadership review without manual data pulls.

## Troubleshooting

**Problem:** Connect rate drops suddenly (from 9% to 4%) over 2-3 days.
**Solution:** Your caller IDs have been flagged as spam by STIR/SHAKEN protocols or carrier blacklists. Immediately rotate to new local presence numbers. Audit call volume per number per day — keep below 50-75 calls/number/day to avoid flagging. Check if a batch of calls went to non-ICP contacts with low connect intent, triggering block reports. Use a service like First Orion or Hiya to monitor caller ID reputation in real-time.

**Problem:** Meetings are being booked but 50%+ are no-shows (ghost meetings).
**Solution:** Low CQS meetings (<40) are being booked by an AI agent that's closing too aggressively on poorly qualified contacts. Review your objection-handling script — is the AI booking meetings before resolving the prospect's concern? Tighten your ICP qualification criteria at the list-building stage (wrong-person calls book easily and ghost reliably). Add a post-booking confirmation text or email sequence: prospects who verbally agreed but didn't click the calendar link need immediate re-engagement within 1 hour of the call ending.

**Problem:** Voice AI SDR is generating meetings but pipeline quality is low — deals are smaller than human SDR pipeline and close at half the rate.
**Solution:** Your calling list contains contacts that are too low in the buying committee (individual contributors vs. VP+). Audit the job titles of AI-booked meetings vs. human SDR meetings. Tighten ICP criteria to senior manager level and above. Also review your AI agent's qualification script — is it confirming budget authority and decision-making role during the call? Add 2-3 questions to the conversation flow that gate meeting booking on basic budget and authority confirmation.

## Version History
- v1.0: Initial creation (auto-generated)
