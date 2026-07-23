# AI-Powered B2B SaaS Voice AI SDR Analytics & Autonomous Outbound Pipeline Attribution Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** voice-ai, ai-sdr, outbound-analytics, pipeline-attribution, conversation-intelligence, revenue-intelligence, b2b-saas, sales-automation, call-analytics, autonomous-selling

## Overview
Voice AI SDRs (AI-powered autonomous outbound callers built on platforms like Bland AI, Vapi, and ElevenLabs) are booking pipeline at 3–10x the volume of human SDRs at 20–40% of the cost — but most revenue teams can't measure them properly, can't optimize the calls, and can't attribute pipeline accurately. This prompt builds a complete Voice AI SDR analytics system: tracking connection rates, conversation quality, meeting booking conversion, pipeline attribution, and compliance — and then generates the optimization frameworks to continuously improve call performance. Use it when you've deployed a voice AI calling program and need to prove ROI, identify failure modes, or scale what's working.

## Quick Copy-Paste Version

You are a senior B2B revenue analytics strategist who has built measurement systems for Voice AI SDR programs generating $2M–$15M in attributed pipeline annually.

Help me build a complete analytics system for our Voice AI SDR outbound program.

Our context:
- Product: [e.g., "Operix — AI-powered field service management platform; automates job scheduling, technician dispatch, and customer communication for HVAC, plumbing, and electrical service companies with 10–200 technicians"]
- ICP: [e.g., "Operations Directors, Owner-Operators, and General Managers at residential and commercial service companies with $3M–$50M annual revenue, managing 10–200 technicians"]
- Voice AI platform: [e.g., "Bland AI + Vapi for fallback; ElevenLabs for voice cloning of our top human SDR"]
- Monthly call volume: [e.g., "4,000–6,000 outbound calls per month to cold and warm lists"]
- Current CRM: [e.g., "HubSpot + Salesforce synced; Gong for human rep call recording; Outreach for sequencing"]
- Current program age: [e.g., "3 months live; booking 35–50 meetings/month but unsure if this is good or how to improve"]
- Key conversion goal: [e.g., "Book a 30-minute discovery call with a qualified prospect; qualification criteria: 10+ technicians, uses paper/spreadsheets for scheduling, open to demos in next 30 days"]

Build me:

1. **VOICE AI CALL PERFORMANCE SCORECARD**
   - The 12 core metrics to track from connection to closed-won with target benchmarks for each
   - How to pull these metrics from your voice AI platform API and sync them to your CRM automatically
   - A weekly performance dashboard template your VP of Sales and CMO can actually read

2. **CONVERSATION QUALITY INTELLIGENCE**
   - How to use AI (Claude/GPT-4o) to score every call transcript automatically on 8 quality dimensions
   - The specific patterns that correlate with meeting booking vs. call abandonment vs. objection failure
   - A script optimization loop: how to A/B test conversation branches and measure statistical significance

3. **PIPELINE ATTRIBUTION ARCHITECTURE**
   - How to tag voice AI-sourced pipeline in your CRM without double-counting (when human SDRs follow up on AI-booked meetings)
   - The multi-touch attribution model for deals that started with a voice AI call but involved 3+ subsequent touches
   - How to calculate true CAC and payback period for your voice AI program

4. **COMPLIANCE & QUALITY ASSURANCE SYSTEM**
   - Automated compliance checking for TCPA, GDPR, and Do-Not-Call registry against every call record
   - The escalation system for flagged calls: what triggers human review, what triggers automatic suppression
   - How to maintain FCC/Ofcom compliance as regulations evolve in 2025–2026

5. **90-DAY OPTIMIZATION ROADMAP**
   - Month 1: Baseline measurement and data infrastructure setup
   - Month 2: Conversation pattern analysis and first script optimization cycle
   - Month 3: Full attribution reporting and ROI proof for board presentation

Produce a complete, AI-agent-executable system. Every section should include specific metric formulas, CRM field names, automation triggers, and decision thresholds.

## Advanced Customizable Version

ROLE: You are a principal-level revenue analytics architect specializing in autonomous outbound systems, AI-to-human sales handoff design, and conversation intelligence for B2B SaaS. You have built Voice AI SDR measurement frameworks for companies deploying 2,000–50,000 outbound calls per month — across verticals including fintech, HR tech, field service, and developer tools. You understand that Voice AI outbound is simultaneously the highest-leverage and highest-risk channel in modern B2B GTM: done right, it generates meetings at cost structures that make traditional SDR economics obsolete; done wrong, it generates TCPA violations, brand damage, and burned prospect lists. You approach every analytics build as a dual mandate: maximize pipeline contribution while maintaining zero compliance incidents. You design systems where AI agents handle call data ingestion, transcript analysis, performance scoring, and CRM updating autonomously — your analytics output is ready for human executive review without manual data preparation.

---

PROGRAM CONTEXT:

**Company & Product:**
- Company + product description: [e.g., "Operix — AI-powered field service management platform; automates job scheduling, technician routing, customer notifications, and invoice generation; integrates with QuickBooks, ServiceTitan, and major ERP systems; primary differentiator is 'zero-touch scheduling' that reduces dispatcher headcount by 60–80%"]
- Product category: [e.g., "Field Service Management (FSM) / Service Operations Software"]
- Average contract value: [e.g., "$18,000–$65,000 ACV; 36-month average contract length"]
- Sales cycle: [e.g., "45–90 days from first meeting; requires demo + ROI review + IT security sign-off for companies over 50 technicians"]
- ICP: [e.g., "Operations Directors, Owner-Operators, General Managers at HVAC/plumbing/electrical/pest control service companies; 10–200 technicians; $3M–$50M revenue; currently scheduling on whiteboards, Excel, or legacy FSM software (ServiceMax, FieldEdge)"]

**Voice AI Program Infrastructure:**
- Voice AI platform(s): [e.g., "Primary: Bland AI (autonomous calling, branching conversation logic); Fallback: Vapi; Voice: ElevenLabs voice clone of our #1 human SDR 'Marcus' — internal name 'Marcus AI'"]
- Human SDR integration: [e.g., "3 human SDRs who handle all inbound responses, follow up on AI-booked meetings within 4 hours, and handle any 'too complex' call escalations flagged by the AI system"]
- Call list sources: [e.g., "Apollo.io for cold lists filtered by technician headcount signals; ZoomInfo for intent-enriched contacts; HubSpot marketing-engaged contacts who haven't converted in 60+ days; conference attendee lists from industry events"]
- Monthly volume: [e.g., "5,000–8,000 outbound call attempts/month; target: 1,000+ live conversations, 80–120 meetings booked"]
- Current CRM stack: [e.g., "HubSpot (marketing + CRM); Salesforce (deals $50K+ ACV); Outreach (human SDR sequences); Gong (human call recording); Bland AI webhook → Zapier → HubSpot for AI call logging"]
- Compliance environment: [e.g., "US-focused, operating in all 50 states; TCPA compliance required; registered with DNC registry; using Bland AI's built-in DNC scrub + our own suppression list in HubSpot"]

**Current Program State:**
- Program launch date: [e.g., "3 months ago; ramp-up month 1, testing month 2, current full deployment month 3"]
- Current performance (known): [e.g., "~5,500 call attempts/month; ~800 live conversations (14.5% connection rate); ~45 meetings booked/month (5.6% meeting rate from live conversations); ~$410K in Voice AI-sourced pipeline (3 months combined); 0 TCPA complaints filed"]
- Known problems: [e.g., "High call abandonment in the first 8 seconds (45% of conversations end before 30 seconds); unclear whether meeting quality from AI-sourced meetings is comparable to human-sourced meetings; can't tell which conversation branches are underperforming; no systematic script A/B testing running"]
- Executive pressure: [e.g., "CFO wants payback period analysis by next board meeting (60 days); Sales leader wants to see meeting-to-opportunity conversion rate for AI-sourced vs. human-sourced meetings to decide whether to expand the program"]

---

DELIVERABLE 1: VOICE AI PERFORMANCE MEASUREMENT FRAMEWORK

**MASTER METRICS HIERARCHY**

Organize all Voice AI SDR metrics into four tiers:

**Tier 1 — Activity Metrics** (volume and connection efficiency):

| Metric | Definition | Formula | Benchmark (B2B SaaS cold outbound) | Data Source |
|--------|------------|---------|-------------------------------------|-------------|
| Call Attempts | Total outbound dials initiated | Raw count | N/A | Voice AI platform |
| Connection Rate | % of attempts that result in a live human answering | Connected calls ÷ Attempts | 8–18% (varies heavily by list quality and time of day) | Voice AI platform |
| Voicemail Rate | % of attempts reaching voicemail | Voicemails ÷ Attempts | 40–55% | Voice AI platform |
| DNC Hit Rate | % of calls blocked by DNC scrub | DNC blocked ÷ Attempts | <2% (if >2%, list sourcing problem) | Voice AI platform + suppression log |
| Average Dial Delay | Time from contact entering call queue to first dial | Minutes | <4 hours for warm leads; <24 hours for cold | Call logs |

**Tier 2 — Conversation Quality Metrics** (how well the AI performs live):

| Metric | Definition | Formula | Benchmark | Data Source |
|--------|------------|---------|-----------|-------------|
| 30-Second Retention Rate | % of connected calls that last 30+ seconds | 30s+ calls ÷ Connected calls | 55–70% | Call recording timestamps |
| Full Conversation Rate | % of connected calls completing the full scripted qualification flow | Completed flows ÷ Connected calls | 35–55% | Voice AI platform |
| Objection Recovery Rate | % of times the AI successfully handles an objection and continues | Recoveries ÷ Objections triggered | >60% = good; <40% = script problem | Transcript NLP scoring |
| Disqualification Rate | % of live conversations that end in confirmed disqualification (wrong ICP) | DQ'd ÷ Connected calls | 15–35% (healthy; reflects list quality) | CRM disposition tag |
| Escalation Rate | % of calls escalated to human review before close | Escalated ÷ Connected calls | <5% (if higher, AI confidence thresholds need tuning) | Voice AI platform |

**Tier 3 — Conversion Metrics** (meetings and pipeline):

| Metric | Definition | Formula | Benchmark | Data Source |
|--------|------------|---------|-----------|-------------|
| Meeting Booking Rate (from live conversations) | % of live conversations that result in a booked meeting | Meetings ÷ Connected calls | 4–9% (cold list); 10–20% (warm/intent list) | CRM meeting log |
| Meeting Booking Rate (from attempts) | Overall efficiency metric | Meetings ÷ Attempts | 0.5–1.5% | CRM |
| Meeting Show Rate | % of AI-booked meetings where prospect actually attends | Shows ÷ Booked | 65–80% (AI-booked meetings often show lower than human-booked without follow-up sequence) | CRM / calendar |
| Meeting-to-Opportunity Rate | % of attended meetings that progress to a qualified opportunity | Opps ÷ Shows | 35–55% | CRM |
| Meeting-to-Closed-Won Rate | % of AI-sourced meetings that convert to revenue (3–6 month lag) | Won ÷ Meetings | 3–8% | CRM |

**Tier 4 — Revenue Attribution Metrics** (business impact):

| Metric | Definition | Formula | Data Source |
|--------|------------|---------|-------------|
| Voice AI-Sourced Pipeline | Total ARR of open opportunities where first touch was an AI call | Sum of opp ARR where Source = Voice AI | CRM |
| Voice AI-Influenced Pipeline | Pipeline where AI call appeared in any touch (not first touch) | Sum of opp ARR where AI call in touch history | CRM |
| Voice AI CAC | Cost to acquire one customer via the Voice AI program | (Voice AI platform cost + human oversight cost) ÷ Customers won | Finance + CRM |
| CAC Payback Period | Months to recover Voice AI CAC | Voice AI CAC ÷ (ACV ÷ 12) | Target: <12 months |
| Voice AI ROI | Return on investment for the program | (Voice AI-attributed ARR − Voice AI program cost) ÷ Voice AI program cost | Finance |

---

DELIVERABLE 2: AI-POWERED CONVERSATION INTELLIGENCE SYSTEM

**AUTOMATED TRANSCRIPT SCORING ARCHITECTURE**

Every Voice AI call generates a transcript. Build an AI pipeline that processes every transcript automatically:

**Step 1: Transcript Ingestion**
- Voice AI platform webhooks → Zapier/Make trigger on call completion
- Pull full transcript (JSON) + call metadata (duration, outcome, disposition)
- Store raw transcript in your data warehouse (Snowflake, BigQuery, or Notion database for smaller programs)

**Step 2: AI Quality Scoring (Claude or GPT-4o prompt)**

System prompt for automated scoring:

You are a B2B outbound call quality analyst. Score this Voice AI SDR call transcript on the following 8 dimensions, each on a 1–10 scale. Output structured JSON with scores and evidence quotes.

SCORING DIMENSIONS:

1. OPENING HOOK EFFECTIVENESS (1–10)
   - Did the AI capture attention in the first 8 seconds?
   - Did it reference something specific about the prospect (company name, role, relevant trigger)?
   - Score 1 if prospect interrupted to ask "is this a robot?" within 5 seconds; score 10 if prospect asked a genuine question showing curiosity

2. ICP QUALIFICATION ACCURACY (1–10)
   - Did the AI correctly identify and confirm ICP fit before advancing the conversation?
   - Score 1 if AI proceeded to pitch a clearly disqualified prospect; score 10 if AI accurately identified fit AND disqualified non-fit cleanly

3. PAIN POINT RESONANCE (1–10)
   - Did the prospect confirm or expand on the pain point the AI introduced?
   - Evidence: Look for phrases like "yes, that's exactly our problem," "we deal with that constantly," or equivalent acknowledgment
   - Score 1 if prospect denied having the pain; score 10 if prospect volunteered additional pain context unprompted

4. OBJECTION HANDLING EFFECTIVENESS (1–10)
   - If an objection was raised, did the AI recover effectively?
   - Score N/A if no objections were raised; score 1 if call ended due to an unhandled objection; score 10 if objection was handled and conversation continued productively

5. VALUE PROPOSITION CLARITY (1–10)
   - Was the core value proposition communicated clearly and specifically?
   - Score 1 if the AI delivered a generic pitch that could apply to any software company; score 10 if the AI customized the value prop to the prospect's stated situation

6. MEETING SETUP QUALITY (1–10)
   - If a meeting was booked, how complete was the booking confirmation?
   - Did AI confirm: date, time, email for calendar invite, who will join, what prospect should prepare?
   - Score N/A if no meeting was booked; score 1 if meeting details were vague; score 10 if all 5 confirmation elements were covered

7. CONVERSATION NATURALNESS (1–10)
   - Did the conversation flow naturally, or were there robotic transitions, response delays, or misunderstood questions?
   - Score 1 if prospect identified the AI as a bot and hung up due to frustration; score 10 if prospect engaged as though talking to a human

8. COMPLIANCE ADHERENCE (1–10)
   - Did the AI properly identify itself when required (if disclosing AI is required by your compliance policy or state law)?
   - Did the AI honor all opt-out/do-not-call requests immediately?
   - Score 1 if AI failed to honor a clear opt-out request; score 10 if all compliance requirements followed perfectly

Output format:
{
  "call_id": "[call_id]",
  "overall_quality_score": [weighted average, 1–10],
  "dimension_scores": { "opening_hook": X, "iq_qualification": X, "pain_resonance": X, "objection_handling": X, "value_prop_clarity": X, "meeting_setup": X, "naturalness": X, "compliance": X },
  "key_evidence_quotes": ["quote1", "quote2", "quote3"],
  "failure_mode": "[top failure reason if overall score < 6; null if score ≥ 6]",
  "recommended_script_update": "[specific line or branch that should be revised; null if no issues]",
  "human_review_flag": [true/false based on compliance score < 8 or any unusual pattern]
}

**Step 3: Pattern Analysis (Weekly AI Summary)**

Aggregate all call scores weekly and generate:

Analyze the quality scores from this week's [N] Voice AI SDR calls. Identify:

1. The top 3 failure modes (failure_mode field) — which are causing the most call quality problems?
2. The conversation branches with the highest drop-off rate (where calls ended abruptly)
3. The objection types that have the lowest objection_handling scores
4. The opening hooks with the highest vs. lowest 30-second retention correlation
5. The specific calls that most need human review (human_review_flag = true)

Format your output as:
- Executive Summary (3 bullets)
- Top 3 Script Issues with specific fix recommendations and estimated impact
- This Week's Compliance Incidents (if any)
- Recommended A/B Test for next week

**SCRIPT A/B TESTING FRAMEWORK**

Design Voice AI conversation experiments systematically:

**Test Structure:**
- Variant A = Control (current production script)
- Variant B = Modified script (one change at a time)
- Minimum sample: 200 connected calls per variant before declaring significance
- Primary metric: Meeting booking rate from connected calls
- Secondary metrics: 30-second retention, conversation completion rate

**What to Test (Priority Order):**
1. Opening line (highest impact — determines 30-second retention)
2. Objection responses (tests for the top 3 most common objections)
3. Pain point framing (which problem statement resonates most)
4. Meeting booking ask language (direct vs. soft ask)
5. Call-back offer language for prospects who decline but don't disqualify

**Statistical Significance Calculator:**
Variant A: [A_meetings] meetings from [A_calls] connected calls → Rate: [A_rate]%
Variant B: [B_meetings] meetings from [B_calls] connected calls → Rate: [B_rate]%

Using a two-proportion z-test at 95% confidence:
If p-value < 0.05, declare Variant B the winner and update production script.

---

DELIVERABLE 3: PIPELINE ATTRIBUTION ARCHITECTURE

**THE VOICE AI ATTRIBUTION CHALLENGE**

Voice AI outbound creates a unique attribution problem: the AI books the meeting, but a human SDR confirms it, runs the discovery call, and nurtures the deal for 45–90 days. Without a precise attribution model, you'll either over-credit the AI program (claiming all pipeline it touched) or under-credit it (attributing all revenue to the human SDR who closed).

**RECOMMENDED MODEL: First-Touch + Assist Attribution**

Define three pipeline categories:

**1. Voice AI Sourced** (AI gets 100% credit):
- First meaningful engagement = Voice AI call
- Meeting booked on that same call
- No prior marketing engagement within 90 days

Tag in CRM: `Lead Source = Voice AI Outbound` | `SDR Source = None`

**2. Voice AI Assisted** (AI gets 40% credit):
- Prospect had prior marketing engagement (email open, ad click, content download)
- Voice AI call was first sales outreach
- Meeting booked on AI call or within 7 days of AI call (after human follow-up)

Tag in CRM: `Lead Source = [Original Marketing Source]` | `SDR Source = Voice AI Assist` | `Pipeline Influence = Voice AI`

**3. Human SDR Sourced, AI Touched** (AI gets 10% credit):
- Human SDR originated the relationship
- AI called the same contact as part of a sequence
- Used only for influence reporting, not primary attribution

Tag in CRM: `Lead Source = Human SDR` | `AI Touch = Yes` | Weight: 10%

**CRM IMPLEMENTATION (HubSpot):**

Create these custom properties on the Contact object:
- `Voice AI Call Date` (Date) — date of first Voice AI call
- `Voice AI Outcome` (Dropdown) — Meeting Booked / Disqualified / Callback Requested / Voicemail / Hung Up / Opted Out
- `Voice AI Call Quality Score` (Number) — populated by automated scoring pipeline
- `Voice AI Meeting Source` (Checkbox) — true if meeting was booked by AI
- `Voice AI Pipeline Source` (Dropdown) — Sourced / Assisted / Touched / Not Involved

On the Deal object:
- `AI Source Type` (Dropdown) — Voice AI Sourced / Voice AI Assisted / Voice AI Touched / Human
- `AI Sourced ARR` (Number) — ARR to attribute to Voice AI program
- `AI Assist Credit` (Number) — fractional ARR credit (40% of deal ARR if Assisted)

**ATTRIBUTION REPORT TEMPLATE (Monthly):**

| Category | Meetings | Shows | Opps | Pipeline ARR | Weighted Credit |
|----------|---------|-------|------|-------------|----------------|
| Voice AI Sourced | [N] | [N] | [N] | $[X] | $[X] (100%) |
| Voice AI Assisted | [N] | [N] | [N] | $[X] | $[X] (40%) |
| Total Voice AI Contribution | | | | | $[Total] |
| Voice AI Program Cost (month) | | | | | $[Cost] |
| **Voice AI ROI (month)** | | | | | **[Total/Cost]x** |

---

DELIVERABLE 4: COMPLIANCE & QUALITY ASSURANCE SYSTEM

**AUTOMATED COMPLIANCE FRAMEWORK**

Voice AI outbound is the highest-risk outbound channel from a regulatory standpoint. Build a zero-tolerance compliance system:

**Pre-Call Compliance Checks (automated, before every dial):**

1. **DNC Registry Scrub:** Check contact against national DNC registry + your internal suppression list before every call. Flag if last scrub was >30 days ago.
2. **State-Specific Rules:** If calling into California, Florida, Indiana, or Texas — check state-specific calling hour restrictions (California: 8am–9pm local time; no Sunday calls before noon in some states)
3. **Prior Opt-Out Check:** Query HubSpot for any "Unsubscribed" or "Do Not Call" property = true before dialing
4. **Contact Record Age:** Flag contacts where all data was sourced >12 months ago (data decay risk)

**Automation (Zapier/Make):**
Trigger: New contact enters Voice AI calling queue
→ Step 1: Check HubSpot property "Do Not Call" — if true, remove from queue immediately
→ Step 2: Check "Last DNC Scrub Date" — if >30 days, hold and trigger scrub via Trestle/Melissa API
→ Step 3: Check prospect's state → apply time-of-day restrictions to call scheduling
→ Step 4: If all checks pass, confirm contact in queue; log pre-call compliance status

**During-Call Monitoring:**
- Any call where prospect says "I never consented to this call," "take me off your list," "stop calling me," or equivalent → flag for immediate suppression
- Train NLP classifier to detect opt-out phrases in transcript and trigger instant DNC add
- All calls with compliance_score < 8 in AI scoring pipeline → automatic human review within 24 hours

**Post-Call Compliance Log:**
Every call generates a compliance record with:
- Call date/time + prospect's local time
- DNC scrub confirmation (Y/N, date of last scrub)
- Opt-out phrase detection result
- AI compliance_score
- Human review status
- Suppression action taken (if any)

**MONTHLY COMPLIANCE AUDIT:**
Query all call records for the past 30 days. Report:
1. Total calls with compliance_score < 8 — how many received human review?
2. Total opt-out requests received — were all contacts added to suppression list within 24 hours?
3. Any calls made outside permitted hours?
4. DNC scrub age distribution — what % of contacts were scrubbed within 30 days?
5. Any formal complaints received (FTC, state AG, carrier reports)?

---

DELIVERABLE 5: BOARD-READY ROI ANALYSIS

**THE VOICE AI SDR ECONOMICS MODEL**

Build this financial model in Google Sheets and update it monthly:

**Cost Inputs:**
- Voice AI platform cost/month: $[X] (per-minute or per-call pricing model)
- Human SDR oversight cost/month: [Hours × Blended Rate] (SDR time reviewing escalations, confirming meetings)
- Data enrichment cost/month: $[X] (Apollo, ZoomInfo)
- Compliance tooling/month: $[X] (DNC scrub, legal review)
- **Total Voice AI Program Cost/Month:** $[Sum]

**Revenue Outputs (Month 3+ when first deals close):**
- Voice AI Sourced ARR: $[X] (100% credit)
- Voice AI Assisted ARR: $[X × 0.4] (40% credit)
- **Total Voice AI Attributed ARR/Month (blended):** $[Sum]

**Efficiency Benchmarks (compare to human SDR baseline):**
| Metric | Human SDR | Voice AI | AI Advantage |
|--------|-----------|----------|-------------|
| Meetings booked/month | 35–50 | 45–120+ | 1.3–3x |
| Cost per meeting | $800–$1,500 | $150–$400 | 4–10x cheaper |
| Daily reach capacity | 50–80 dials | 500–2,000 dials | 10–40x |
| Working hours | 8 hours | 24/7 | Always on |
| Ramp time | 60–90 days | 0 (immediate) | Eliminates ramp |

**12-Month Projection Model:**
Month 1–3: Ramp and optimization (meetings book but no deals close)
Month 4–6: First closed-won deals from AI-sourced meetings
Month 7–12: Full-velocity compounding; Voice AI program self-funding

Input: Monthly meeting bookings × Show rate × Opp rate × Close rate × ACV
Output: Monthly Voice AI ARR contribution + Cumulative ROI curve
Payback calculation: Month when cumulative ARR first exceeds cumulative program cost

---

OUTPUT FORMAT:

Produce your complete analytics system in this sequence:
1. **Measurement Dashboard** — complete metric hierarchy with benchmarks and data source mapping
2. **Transcript Scoring Prompt** — ready-to-deploy AI prompt for automated call quality analysis
3. **Weekly Pattern Analysis Prompt** — for aggregated performance summaries
4. **CRM Implementation Guide** — exact field names, dropdown values, and automation trigger logic for HubSpot/Salesforce
5. **Compliance Checklist** — pre-call, during-call, and post-call compliance protocols
6. **Board ROI Model** — the financial model structure with formulas and benchmark comparisons
7. **60-Day Quick Win Roadmap** — prioritized actions to demonstrate measurable program impact to executives

Every output should be executable by a Revenue Operations analyst within 48 hours of reading. No placeholders without specific examples.

## Example Input/Output

**Input Example:**

Company: Operix — AI-powered field service management platform for HVAC, plumbing, and electrical service companies.

ICP: Operations Directors and Owner-Operators at companies with 10–200 technicians; currently scheduling with Excel or whiteboards.

Voice AI Platform: Bland AI; 5,500 calls/month; 45 meetings/month booked; 3 months live.

**Output Example (Metrics Dashboard excerpt):**

**Current Program Diagnosis (Month 3 Baseline):**

| Metric | Your Rate | Benchmark | Status |
|--------|-----------|-----------|--------|
| Connection Rate | 14.5% (800/5,500) | 8–18% | ✅ Healthy |
| 30-Second Retention | 55% (440/800) | 55–70% | ⚠️ Low end — opening hook issue |
| Meeting Rate (from live) | 5.6% (45/800) | 4–9% cold | ✅ In range for cold list |
| Meeting Show Rate | Unknown | 65–80% | 🔴 Not tracked — fix immediately |
| Meeting-to-Opp Rate | Unknown | 35–55% | 🔴 Not tracked — biggest risk |

**Priority 1 Fix (next 7 days):** The 45% call abandonment in the first 8 seconds (your known problem) means your opening 8 seconds is failing. Based on pattern analysis of calls scoring < 5 on Opening Hook, the AI is likely opening with a company name + generic pitch rather than a pattern interrupt. Test opening with a specific trigger: "I noticed [Company] recently added 3 new service vans on your website — wanted to ask Operations Director [Name] a quick question about scheduling those routes."

**Priority 2 Fix (next 14 days):** Implement Meeting Show Rate tracking immediately. Without it, you can't tell if your 45 meetings/month are genuine pipeline or no-shows. Add a Gong/Calendly automation that marks meeting as "Showed" or "No-Show" and syncs to HubSpot within 1 hour of meeting end time.

**CAC Estimate (current):**

If Voice AI program costs $8,000/month (platform + oversight + data):
- Cost per meeting attempt: $8,000 ÷ 45 meetings = $178/meeting
- Assuming 70% show rate = 31.5 shows/month; 45% meeting-to-opp = 14 opps/month; 15% close rate = 2.1 wins/month
- Voice AI CAC = $8,000 ÷ 2.1 = $3,810/customer
- At $18,000 ACV: Payback = 2.5 months ✅ Exceptional

## Success Metrics

**Week 2 (Data infrastructure live):**
- All 12 Tier 1–3 metrics pulling automatically from Voice AI platform API to CRM
- Automated transcript scoring running on 100% of call transcripts
- Meeting Show Rate and Meeting-to-Opp Rate tracked for first time

**Month 1 (Baseline established):**
- Full Month 1 performance report with benchmark comparison
- Top 3 failure modes identified from transcript pattern analysis
- First A/B test designed and running (minimum 400-call sample)
- Compliance audit completed with zero unresolved incidents

**Month 2 (First optimizations shipped):**
- Opening hook variant with 15%+ improvement in 30-second retention
- Meeting show rate improved to 70%+ via automated follow-up sequence triggered by AI-booked meetings
- Pipeline attribution model fully implemented in CRM (zero double-counting)

**Month 3 (Board-ready ROI proof):**
- Complete 3-month ROI report: Voice AI CAC vs. Human SDR CAC comparison
- First closed-won deals attributed to Voice AI program
- Compliance record: 100% of opt-out requests honored within 24 hours; zero formal complaints
- Program verdict: scale, optimize, or restructure with clear data-backed recommendation

## Related Prompts

- [AI-Powered B2B SaaS Website Chat & Sales AI Agent Performance Analytics & Pipeline Revenue Attribution Intelligence Engine](./AI-Powered-B2B-SaaS-Website-Chat-&-Sales-AI-Agent-Performance-Analytics-&-Pipeline-Revenue-Attribution-Intelligence-Engine.md)
- [AI-Powered SMS WhatsApp Conversational Marketing Analytics & Revenue Attribution Intelligence Engine](./AI-Powered-SMS-WhatsApp-Conversational-Marketing-Analytics-&-Revenue-Attribution-Intelligence-Engine.md)
- [AI-Powered B2B SaaS AI SDR Program Analytics & Outbound Revenue Contribution Intelligence Engine](../../05_Analytics-&-Performance/Demand-Generation-Program-Analytics/AI-Powered-B2B-SaaS-AI-SDR-Program-Analytics-&-Outbound-Revenue-Contribution-Intelligence-Engine.md)
- [AI-Powered B2B Autonomous AI SDR Program Architecture & Outbound Pipeline Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/AI-Powered-B2B-Autonomous-AI-SDR-Program-Architecture-&-Outbound-Pipeline-Intelligence-Engine.md)

## Integration Tips

**HubSpot:**
- Use HubSpot's Calling API to log Voice AI calls directly as call activities on the Contact record — include duration, outcome, and transcript link
- Create a "Voice AI Performance" dashboard using HubSpot's custom report builder: filter deals where `AI Source Type` is not null; build a funnel from meetings to closed-won
- Set up automated internal notifications: when a Voice AI-booked meeting's show status is confirmed in Calendly → Slack notification to assigned SDR with the call transcript and AI quality score, pre-loaded in HubSpot contact view
- Workflow: Meeting booked via Voice AI → auto-enroll in 48-hour pre-meeting email + SMS reminder sequence (improves show rate by 15–20%)

**Salesforce:**
- Create an `AI Outbound Call` custom object linked to Contact: store call_id, duration, quality_score, outcome, transcript URL, compliance_status
- Build a Voice AI Attribution Report using Salesforce's Attribution Intelligence: segment opportunities by `AI Source Type` and calculate win rates and cycle times by segment
- Einstein Analytics dashboard: overlay Voice AI call volume heatmap against pipe generation calendar — identify which weeks' call activity correlates with downstream pipeline 3–6 months later

**Gong / Chorus (for human SDR follow-up calls):**
- Tag all Gong calls where Opportunity `AI Source Type` = Voice AI Sourced — analyze whether human reps are referencing the AI conversation context in their discovery calls
- Build a "Voice AI Meeting Quality" tracker: compare Gong call outcomes (discovery-to-proposal rates) for AI-sourced vs. human-sourced meetings to prove (or disprove) that AI-booked meetings convert at comparable rates

**Zapier / Make Automation Stack:**
- Trigger: Voice AI call completed → Pull transcript via Bland AI API → Send to Claude API for quality scoring → Write scores to HubSpot Contact → Route compliance flags to Slack `#compliance-review` channel → Update Google Sheet analytics log
- Trigger: Voice AI meeting booked → Create HubSpot meeting record → Enroll contact in pre-meeting email sequence → Create Salesforce opportunity draft (if ACV threshold met) → Assign to nearest available human SDR via round-robin

**Snowflake / BigQuery (Data Warehouse):**
- Stream all Voice AI call records, transcript scores, and CRM outcomes to your data warehouse for longitudinal analysis
- Build a cohort analysis table: group contacts by the week they received their first Voice AI call; track their pipeline progression over 6 months; identify the "optimal call window" (how many days between first call and first qualified meeting)
- Run regression analysis: which call quality score dimensions (opening hook, pain resonance, etc.) are most predictive of meeting-to-closed-won? Weight your automated scoring accordingly.

## Troubleshooting

**Problem: Meeting show rates are significantly lower for Voice AI-booked meetings than for human-booked meetings (below 55%).**
Solution: The drop-off almost always happens because prospects don't feel a personal connection to the booking and de-prioritize the meeting. Fix with a same-day human touchpoint: within 2 hours of an AI-booked meeting, have a human SDR send a personalized Loom video (30 seconds) confirming the meeting, sharing the agenda, and introducing themselves. This single step typically lifts show rates from 55% to 72%+. Also audit your meeting booking confirmation language in the AI script — the AI should be confirming name, email, and a specific agenda item ("we'll show you specifically how HVAC companies with 20–40 technicians reduce dispatch time") rather than generic booking language. Finally, check your calendar integration: if the AI is using a generic calendar link instead of sending a personalized invite with the prospect's name, company, and agenda, the meeting feels impersonal and is more likely to be a no-show.

**Problem: Compliance audit flags a high number of calls where the opt-out detection NLP missed prospect phrases.**
Solution: Your opt-out NLP classifier likely isn't trained on industry-specific language. B2B prospects rarely say "remove me from your list" — they say things like "we're not interested right now," "please stop calling this number," "I'm busy, don't call again," or "we already have a solution." Run your last 500 call transcripts through your NLP classifier and manually review the false negatives. Expand your opt-out phrase dictionary to include these variants, and add a conservative "uncertainty" rule: any transcript where the prospect says a negative phrase about being contacted AND the call ends within 60 seconds of that phrase → automatic human review and 24-hour suppression hold (release only after human confirms not an opt-out). Also check that your suppression list syncs bidirectionally between your Voice AI platform and HubSpot in real time, not on a batch schedule — a 24-hour batch sync creates a compliance window.

**Problem: Transcript quality scores are high (avg 7.5/10) but meeting booking rates are low (below 4%).**
Solution: A scoring vs. conversion disconnect means your quality rubric is measuring the wrong things. Your AI is scoring calls as "good" based on naturalness and script adherence, but not on whether the AI is actually creating urgency and buying intent. Add two new scoring dimensions: (1) Urgency Creation Score — did the prospect express a timeframe or acknowledge why NOW is relevant? (2) Next Step Clarity Score — was the prospect 100% clear on what happens after this call? Recalibrate your score weights so that these conversion-predictive dimensions count for 40% of overall quality score instead of naturalness metrics. Then re-score your last 90 days of call transcripts and see if the high-booking calls cluster around high Urgency Creation scores — this will identify the specific language patterns driving conversions vs. the "polite but not interested" category that inflates your quality scores without producing pipeline.

## Version History
- v1.0: Initial creation (auto-generated)
