# AI-Powered B2B SaaS Prospect Earnings Call Intelligence & Executive Priority-Triggered GTM Outreach Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** gtm-engineering, earnings-intelligence, signal-based-outreach, executive-outreach, account-intelligence, outbound, clay, salesforce, b2b-enterprise, revenue-signals, financial-intelligence, personalization

## Overview
Public company executives telegraph their exact buying priorities every 90 days on earnings calls — yet most GTM teams never listen. This prompt architects a fully autonomous AI system that monitors your target account list's quarterly earnings calls and 10-Q/10-K filings, extracts executive priorities and pain points that map to your solution, and triggers hyper-personalized multi-channel outreach sequences within 24 hours of transcript release. Use it to turn the Fortune 500's most honest, analyst-grade prioritization signals into pipeline before your competitors even finish reading the headline.

## Quick Copy-Paste Version

You are a senior GTM engineer and enterprise sales strategist who has built signal-based outreach systems at Gong, Clari, and Outreach. Help me design an AI-powered earnings call monitoring and outreach trigger system for my target accounts.

My context:
- My company: [e.g., "PipelineIQ — AI-powered revenue forecasting and pipeline analytics for enterprise sales teams, $60K–$180K ACV"]
- My ICP: [e.g., "CRO, VP Sales, and VP Revenue Operations at publicly traded B2B companies with $200M–$2B revenue and 50+ person sales teams"]
- My solution's core value: [e.g., "We replace spreadsheet-based forecasting with AI-driven accuracy, giving CROs 94% forecast accuracy and 3× faster pipeline reviews"]
- Target account list: [e.g., "We have 150 named enterprise accounts we're actively pursuing, all publicly traded companies in software, manufacturing, and financial services"]
- Current outreach approach: [e.g., "Standard SDR sequences with basic company research — not using any real-time signal triggers"]

Design an end-to-end AI system that:

1. **MONITORING ARCHITECTURE** — Which services, APIs, and tools to use to automatically detect when any of our 150 target accounts releases an earnings call transcript within 15 minutes of publication (SEC EDGAR, Seeking Alpha API, Refinitiv, FactSet, or similar). Include free vs. paid tier options and recommended stack for a 10-person GTM team.

2. **SIGNAL EXTRACTION PROMPT** — Write the exact AI prompt we use to analyze each earnings call transcript and extract: (a) stated executive priorities for the next 12 months, (b) revenue/growth targets that imply need for better forecasting, (c) pipeline or sales efficiency language that maps to our solution, (d) risk factors or challenges that our product directly addresses, (e) headcount plans for sales that indicate investment appetite, and (f) specific CFO or CRO quotes we can reference directly in outreach.

3. **RELEVANCE SCORING MODEL** — How to score each extracted signal 1–10 on relevance to our solution, and define the threshold (≥ 7) that triggers an automated outreach sequence vs. queues for human SDR review.

4. **OUTREACH TRIGGER SEQUENCES** — Write 3 complete outreach sequences (email + LinkedIn) for 3 different signal types:
   a. "Revenue scale challenge" signal: company CRO mentions they're scaling from 50 to 150 reps and struggling to maintain forecast accuracy
   b. "Efficiency mandate" signal: CFO explicitly says they need to "do more with less" in the go-to-market motion
   c. "Competitive urgency" signal: company warns analysts that improving sales productivity is a top Q3 priority

5. **PERSONALIZATION VARIABLES** — The 8 specific variables to extract from each earnings call that get dynamically inserted into outreach templates, making each message feel like the SDR spent an hour researching the account.

6. **TIMING INTELLIGENCE** — Optimal timing to send outreach relative to earnings release (immediate vs. 24–48 hours vs. after first analyst follow-up reports publish) and why the 24-hour window beats both extremes.

Produce the complete system architecture, extraction prompts, and outreach templates I can deploy with Clay + HubSpot within one week.

## Advanced Customizable Version

ROLE: You are a principal GTM engineer with 12+ years building signal-based outbound systems at high-growth enterprise SaaS companies. You have implemented earnings call intelligence programs at companies targeting Fortune 500 and mid-market enterprise accounts that achieved 3–5× response rates vs. generic SDR sequences, and you understand the mechanics of public financial filings, SEC EDGAR data feeds, analyst call dynamics, and how C-suite executives respond to outreach that demonstrates genuine financial intelligence vs. AI-generated noise. You design systems where AI agents handle monitoring, extraction, scoring, and personalization drafting — and human SDRs review, approve, and send — achieving 40+ touch-points per SDR per day without sacrificing quality.

---

COMPANY & SOLUTION CONTEXT:

**Your Company:**
- Company name + product: [e.g., "PipelineIQ — AI-powered revenue forecasting and deal inspection platform that gives CROs real-time, AI-calibrated pipeline accuracy across every deal, rep, and stage"]
- Product category: [e.g., "Revenue Intelligence / Sales Forecasting"]
- Core value prop: [e.g., "Replace spreadsheet-based forecast calls with AI that achieves 94% forecast accuracy, 3× faster pipeline review cycles, and automatic identification of at-risk deals before they slip"]
- Primary buyer: [e.g., "CRO, VP Sales, VP Revenue Operations at B2B companies with 50–500 person sales teams"]
- Economic buyer: [e.g., "CFO and CRO jointly sign; CFO approves budget, CRO owns champion relationship"]
- ACV range: [e.g., "$60,000–$180,000 with expansion to $300K+ at enterprise tier"]
- Typical sales cycle: [e.g., "45–90 days for mid-market; 90–180 days for enterprise with procurement involved"]
- Key competitors: [e.g., "Clari, Gong, Salesforce Einstein (native), spreadsheets"]
- What you replace: [e.g., "Typically replacing manual CRM updates, Excel forecast models, and weekly pipeline review PowerPoints that waste 6+ hours of CRO/VP time per week"]

**Target Account Profile:**
- Account list size: [e.g., "150 named accounts, all publicly traded on NYSE or NASDAQ"]
- Revenue range: [e.g., "$200M–$2B ARR, B2B-focused, 50+ AE teams"]
- Key verticals: [e.g., "Enterprise SaaS, B2B services, manufacturing technology, financial services software"]
- Seniority targeting: [e.g., "CRO, VP Sales, VP Revenue Ops (primary), with CFO and CEO as economic buyer multithreads"]
- Current pipeline stage: [e.g., "Mix of cold accounts (70), early-stage conversations (50), and stalled deals (30)"]

**Current GTM Toolstack:**
- CRM: [e.g., "Salesforce Enterprise with Revenue Intelligence module"]
- Sales engagement: [e.g., "Outreach with 6-step SDR sequences averaging 22% open rate, 3.1% reply rate"]
- Data enrichment: [e.g., "Clay for account research, ZoomInfo for contact data, Clearbit for firmographic enrichment"]
- AI tools: [e.g., "Claude for message drafting, GPT-4o for transcript analysis, n8n for workflow automation"]
- ABM platform: [e.g., "6sense for intent data overlay, Demandbase for account scoring"]

**Signal Performance Context:**
- Current best outreach signal: [e.g., "Job postings for 'Revenue Operations Manager' roles — 4.8% reply rate"]
- Worst performing signal: [e.g., "Generic 'congratulations on your funding' messages — 0.8% reply rate"]
- Earnings call outreach history: [e.g., "Never done this systematically — SDRs sometimes manually read G2 reviews but no earnings call monitoring"]

---

DELIVERABLE 1: MONITORING & EXTRACTION INFRASTRUCTURE

Design the complete technical architecture for automated earnings call signal capture.

**1A. Monitoring Stack Options**

Provide a tiered recommendation based on budget and technical sophistication:

**Tier 1 — No-Code (Budget: $500–$1,500/month):**
- Tools: Seeking Alpha Premium API ($300/month for earnings transcript access) + Zapier or Make.com for automation
- Coverage: Earnings call transcripts available 2–4 hours post-call via Seeking Alpha
- Workflow: New transcript published → Zapier webhook → Claude API analysis → Scored output pushed to Salesforce via Zapier
- Limitation: 2–4 hour lag; transcript quality dependent on Seeking Alpha accuracy

**Tier 2 — Low-Code (Budget: $2,000–$5,000/month):**
- Tools: Refinitiv (LSEG) Streaming APIs or FactSet Transcripts API ($1,500–$3,000/month) + n8n self-hosted automation + Clay for enrichment
- Coverage: Near-real-time transcript access (15–30 min post-call close), earnings surprises, analyst Q&A sections
- Workflow: n8n webhook listens for new transcripts on watched tickers → pipes to Claude for analysis → enriches with Clay account data → scores and routes in Salesforce/HubSpot
- Advantage: Near-real-time, higher quality transcripts, ability to monitor SEC 8-K filings and press releases simultaneously

**Tier 3 — Enterprise (Budget: $10,000+/month):**
- Tools: Bloomberg Terminal API or Refinitiv Eikon full access + dedicated data engineering pipeline
- Coverage: Real-time earnings call audio stream (before transcript is available), 10-Q/10-K auto-monitoring, 8-K material event alerts
- Use case: Companies targeting 500+ named accounts where 30-minute signal advantage matters

**Recommended stack for this company:** [Design based on the inputs above — typically Tier 2 for 150-account lists]

**1B. SEC EDGAR Supplemental Monitoring**

Beyond earnings calls, design the EDGAR filing monitor:
- 8-K (Material Events): Monitor for executive leadership changes (new CRO/CFO = high signal), strategic acquisitions, and revenue guidance changes
- 10-Q (Quarterly Reports): Monitor Management Discussion & Analysis (MD&A) section for technology investment mentions, sales productivity language, and revenue operations challenges
- DEF 14A (Proxy Statement): Extract executive compensation structure — if a CRO has revenue targets tied to pipeline accuracy, that's a high-relevance signal for forecasting tools
- Alert threshold: Any 8-K that mentions "sales," "revenue operations," "go-to-market efficiency," or "commercial" in the first 200 words triggers immediate signal extraction

**1C. Trigger Event Classification**

Design 5 earnings signal categories, ranked by outreach priority and expected response rate:

| Signal Class | Example Language | Priority | Expected Reply Rate Lift vs. Control |
|---|---|---|---|
| A: Revenue Scale Signal | "We're expanding our sales force from 80 to 200 reps in the next 18 months" | Immediate (Day 0) | 3.2× |
| B: Efficiency Mandate | "Our focus for next year is sales efficiency — we need to do more with the same headcount" | Immediate (Day 0) | 2.8× |
| C: Competitive Pressure | "We're seeing pricing pressure and need to improve our win rates and forecast predictability" | 24 hours | 2.4× |
| D: Technology Investment | "We're investing $12M in our go-to-market technology stack as part of our digital transformation" | 24 hours | 2.1× |
| E: Leadership Change | "Our new CRO [name] joins from [company] where she built a $2B pipeline practice" | 48 hours | 1.9× |

---

DELIVERABLE 2: AI SIGNAL EXTRACTION PROMPT

Write the master prompt used to analyze each earnings call transcript. This prompt runs inside Claude or GPT-4o and produces a structured JSON output that feeds directly into Salesforce and outreach automation.

**2A. Master Extraction Prompt**

SYSTEM: You are a senior revenue intelligence analyst who extracts buying signals for enterprise B2B software companies from public financial disclosures. You are analyzing this earnings call transcript on behalf of PipelineIQ, which sells AI-powered revenue forecasting software to CROs and VP Sales at companies with 50+ person sales teams.

You will extract structured signals that indicate whether this company is a high-priority outreach target for our product. Be conservative — only flag genuine signals, not generic business language. A "revenue challenge" signal must include specific language about pipeline visibility, forecast accuracy, sales efficiency, or CRO-level challenges — not just general mentions of revenue growth.

TRANSCRIPT:
[TRANSCRIPT TEXT — inserted programmatically]

COMPANY TICKER: [AUTO-INSERTED]
COMPANY NAME: [AUTO-INSERTED]
CALL DATE: [AUTO-INSERTED]
ACCOUNT STAGE IN OUR CRM: [AUTO-INSERTED FROM SALESFORCE]

Analyze this transcript and return a JSON object with the following structure:

{
  "relevance_score": [1-10 integer, where 7+ triggers automatic outreach],
  "signal_class": ["A_revenue_scale" | "B_efficiency_mandate" | "C_competitive_pressure" | "D_technology_investment" | "E_leadership_change" | "NONE"],
  "executive_priorities": [array of 3-5 verbatim executive quotes about growth, efficiency, or technology],
  "pain_point_map": {
    "forecast_accuracy": [true/false — does executive mention forecast visibility or accuracy challenges?],
    "sales_efficiency": [true/false — does exec mention productivity, efficiency, or headcount optimization?],
    "pipeline_velocity": [true/false — mentions of deal cycle, win rate, or pipeline speed?],
    "revenue_predictability": [true/false — mentions of revenue miss, guidance accuracy, or visibility for board?],
    "crm_frustration": [true/false — any mentions of CRM limitations, data quality, or manual processes?]
  },
  "personalization_variables": {
    "ceo_name": "",
    "cro_name": "",
    "cfo_name": "",
    "specific_revenue_target": "",
    "specific_headcount_expansion": "",
    "stated_q_over_q_priority": "",
    "named_competitor_mentioned": "",
    "verbatim_pain_quote": ""
  },
  "outreach_angle": [one sentence describing the most compelling hook for personalized outreach],
  "recommended_sequence": ["A_day0_urgent" | "B_day1_standard" | "C_day2_nurture" | "D_human_review_required"],
  "do_not_contact_flag": [true/false — flag if company is in distress, layoffs, or freeze context that makes outreach inappropriate],
  "analyst_sentiment": ["beat_and_raise" | "in_line" | "miss" | "mixed"],
  "filing_follow_up": [list of SEC filings to monitor for follow-up signals: "10-Q", "8-K", "proxy"]
}

Do not infer signals that are not present. Return only genuine, specific language. If relevance_score is below 4, return minimal fields to save compute cost.

**2B. Relevance Scoring Rubric**

Define the scoring logic that determines score 1–10:

| Score | Criteria | Action |
|---|---|---|
| 9–10 | Multiple explicit pain mentions, named CRO initiative, specific revenue miss tied to forecast | Immediate Sequence A — SDR personalizes and sends within 4 hours |
| 7–8 | Clear efficiency mandate OR scale challenge with relevant team size mention | Sequence B — SDR reviews AI draft and sends within 24 hours |
| 5–6 | Indirect relevance — revenue growth target without explicit operational pain | Queue for weekly human review — SDR decides whether to pursue |
| 3–4 | Minimal relevance — financial performance discussion without GTM ops language | Log signal, monitor next quarter's call for escalation |
| 1–2 | No relevant signals or do-not-contact flag triggered | No action — update CRM with "earnings call reviewed — no signal" note |

---

DELIVERABLE 3: OUTREACH SEQUENCE TEMPLATES

Write complete, deployment-ready outreach sequences for each signal class. Each sequence has 4 touches over 10 business days: Email 1 (Day 0), LinkedIn connection request (Day 1), Email 2 (Day 3), LinkedIn message (Day 7), Email 3 (Day 10).

**3A. Signal Class A — Revenue Scale Sequence (CRO Adding 50+ Reps)**

Scenario: Target company's CRO said in earnings: *"We're expanding our commercial sales organization from 85 to 160 account executives by Q4, and the key challenge will be maintaining forecast accuracy and deal inspection at that scale without a proportional increase in RevOps headcount."*

**Email 1 (Day 0 — same day as transcript release):**

Subject line options (test all 3):
- Option 1: "[First name], saw the call this morning — your 160-rep scale challenge is exactly what we built PipelineIQ for"
- Option 2: "Doubling the team, keeping forecast accuracy — how [similar company] did it"
- Option 3: "RE: Q2 earnings — [Company] going from 85 to 160 AEs"

Body:
---
[First name],

Listened to [Company]'s call this morning. [CRO name]'s point about scaling from 85 to 160 AEs while keeping forecast accuracy stood out — that's precisely where most companies either (a) hire more RevOps headcount proportionally, or (b) watch their CRO visibility degrade as the team grows.

[Similar company at similar scale — e.g., "When Meridian Software scaled from 90 to 175 reps last year, their CRO was running weekly forecast calls that took 4 hours each and still missed the quarter by 11%."] They switched to PipelineIQ and now run a 35-minute weekly review with 94% forecast accuracy.

I realize this is a specific ask right after an earnings call, so I'll be direct: are you the right person at [Company] to have a 20-minute conversation about how you're thinking about the RevOps infrastructure for that headcount expansion? If not, happy to connect with whoever owns that.

[Your name]
[Title], PipelineIQ
---

**LinkedIn Connection Request (Day 1):**
*"[First name] — listened to [Company]'s Q2 call. The 85→160 AE expansion you're planning is the exact scale inflection where forecast tooling becomes make-or-break. Connecting because I think PipelineIQ could be relevant for what you're building."*

**Email 2 (Day 3):**

Subject: The RevOps infrastructure question behind [Company]'s Q4 hiring plan

Body:
---
[First name],

Following up because I want to be specific about why this feels timely.

When B2B sales teams scale past 100 AEs, the math changes. At 85 reps, an experienced CRO can stay close to every deal through manual pipeline reviews. At 160 reps, that's physically impossible — you need the system doing the deal inspection for you.

The three things that break at scale, in order:
1. **Forecast accuracy** falls because reps sandbag or overcommit when they know the CRO can't inspect every deal
2. **Pipeline review cycles** get longer, not shorter — 2-hour calls become 4-hour calls, and your RevOps team is building slides instead of fixing problems
3. **Rep coaching signal** disappears because no one knows which deals to focus QBR conversations on

PipelineIQ solves all three automatically. AI inspects every deal in real time, gives CROs a 35-minute weekly review cycle, and tells reps exactly which deals need attention before they slip.

Worth 20 minutes to see how it works? I'll bring the [competitor] and [similar company] benchmarks so the comparison is concrete.

[Your name]
---

**Email 3 (Day 10 — final touch):**

Subject: Last note on the [Company] scale challenge

Body:
---
[First name],

I've reached out a few times since the Q2 call and understand if the timing is wrong.

I'll leave you with one data point: every B2B sales team that has scaled past 100 AEs and then implemented forecasting AI has a specific moment they point to — the first quarter where the AI caught 3–4 deals that would have slipped without human intervention.

If there's ever a time when thinking about RevOps infrastructure for the 160-AE build is on the agenda, I'm at [email].

[Your name]
---

**3B. Signal Class B — Efficiency Mandate Sequence (CFO Says "Do More With Less")**

Scenario: CFO said: *"Our 2026 plan is built on achieving 15% revenue growth with flat headcount in go-to-market. We expect efficiency improvements in our sales motion to be a meaningful contributor."*

**Email 1 (Day 0):**

Subject: [First name] — on [CFO name]'s "flat headcount, 15% growth" mandate

Body:
---
[First name],

[Company] CFO's message this morning — 15% revenue growth with flat go-to-market headcount — is a specific challenge that usually comes down to one question: how do you get 15% more out of the same AEs?

Most teams try to solve this by shortening cycles or improving win rates. Those matter, but the highest-leverage lever is usually forecast accuracy and deal inspection — specifically, getting your CROs and RevOps team out of the manual pipeline review loop so they spend time coaching deals, not tracking them.

I realize this lands right after earnings, which is a busy time. But if improving sales efficiency is on your roadmap for 2026, PipelineIQ is worth a 20-minute look — we've helped several companies achieve exactly the "more revenue from flat headcount" math by giving CROs AI-driven deal inspection instead of manual calls.

Would next Tuesday or Wednesday work?

[Your name]
---

**3C. Signal Class C — Competitive Pressure Sequence**

[Follow same structure as 3A and 3B, adapted for scenario where company mentions slipping win rates or competitive losses requiring improved deal qualification and forecasting]

---

DELIVERABLE 4: PERSONALIZATION VARIABLE EXTRACTION & DYNAMIC TEMPLATE SYSTEM

**4A. The 8 Critical Personalization Variables**

For each earnings call analyzed, extract these 8 variables and inject them into outreach templates:

1. **`{{cro_name}}`** — Full name and full title of the CRO/VP Sales who spoke (extract from call intro)
2. **`{{specific_growth_target}}`** — Exact revenue or growth target mentioned (e.g., "$1.2B ARR by end of 2026")
3. **`{{headcount_expansion}}`** — Specific rep count change mentioned (e.g., "from 85 to 160 AEs")
4. **`{{stated_challenge_verbatim}}`** — The exact quote from the CRO/CFO that maps to your solution
5. **`{{q_priority_phrase}}`** — The phrase executive used to describe their #1 commercial priority (e.g., "sales velocity" or "forecast predictability")
6. **`{{named_competitor}}`** — Any competitor mentioned by name on the call (enables differentiation angle)
7. **`{{analyst_question_topic}}`** — What analysts asked about on the call — reveals market pressure points (e.g., "analysts asked 4 questions about sales efficiency, signaling this is a known concern in their peer group")
8. **`{{earnings_sentiment_context}}`** — Whether company beat/missed guidance — beats make expansion budget available; misses create urgency for efficiency solutions

**4B. Template Merge Logic in Clay**

Design the Clay table structure that:
- Receives the JSON output from the extraction prompt via webhook
- Maps each extracted variable to a Clay column
- Merges variables into pre-built email templates stored as Clay prompt templates
- Exports merged, ready-to-send drafts to Outreach or HubSpot sequences
- Flags drafts with `relevance_score < 7` for SDR human review before they enter the sequence

---

DELIVERABLE 5: TIMING INTELLIGENCE & SEQUENCE CALENDAR

**5A. Optimal Outreach Timing Post-Earnings**

Design the timing logic based on three outreach windows:

**Window 1: Same-day (0–6 hours post-transcript release) — Signal Classes A and B only**
- Who to send to: CRO and VP Revenue Ops when transcript shows Class A or Class B signals
- Why it works: Executives who just finished an earnings call are in a "priorities are crystallized" mindset; reference to specific quotes demonstrates you were paying attention in real time
- Risk: Appears opportunistic if poorly personalized; requires high-quality extraction
- Personalization requirement: Must reference a specific quote from the call — do not send without {{stated_challenge_verbatim}} populated

**Window 2: 24–48 hours — Signal Classes B, C, and D**
- Who to send to: CRO, VP Sales, VP Revenue Ops
- Why this window wins: Day 1 post-earnings, analyst follow-up reports begin publishing, creating a "market conversation" context you can reference ("I saw the Thomson Reuters note on your efficiency focus...")
- Content approach: Lead with the analyst/market narrative first, your product second

**Window 3: 5–7 days — All signal classes, stalled opportunities, leadership changes**
- Use for: Existing cold accounts where you want to re-engage with a fresh angle
- Lead with the earnings narrative as a reason to re-open conversation: "[First name], I know we last connected in March. The Q3 call last week had some context I thought was worth sharing..."

**5B. Annual Earnings Calendar Automation**

Set up the following monitoring calendar for 150 target accounts:
- Download the full earnings calendar from Seeking Alpha or FactSet at the start of each quarter
- Load all earnings dates into Clay or your automation tool as future trigger events
- Set up notification 24 hours before earnings release (to brief SDRs on company context before the call)
- Set up automatic transcript pull 30 minutes after market close on earnings date
- Schedule the signal extraction job to run immediately upon transcript availability

---

## Example Input/Output

**Input Example:**

Company: Velocity360 (fictional — a $450M ARR B2B logistics software company, NYSE: VLY)
Earnings call excerpt: *"Let me add some context on our go-to-market efficiency initiative. We're targeting 18% revenue growth next fiscal year, and we've made a deliberate decision to hold sales headcount flat at 140 account executives. Our CRO, Jennifer Park, has made it clear that improving deal inspection and forecast accuracy is a Q1 priority — we had too many late-quarter surprises this year and we cannot repeat that in 2026. Jennifer, anything you want to add?"*
*CRO Jennifer Park: "Yes — we had three deals in Q4 that moved from 'high confidence' to 'slipped' in the final two weeks of the quarter. That's not acceptable when we're trying to run a predictable business. We're looking at tools and processes that give us better visibility at the deal level earlier in the quarter."*

**Output Example (signal extraction JSON):**

{
  "relevance_score": 9,
  "signal_class": "B_efficiency_mandate",
  "executive_priorities": [
    "18% revenue growth with flat headcount at 140 AEs",
    "Deal inspection and forecast accuracy named as Q1 CRO priority",
    "Three deals slipped from high-confidence to lost in final two weeks of Q4 — explicitly named as unacceptable"
  ],
  "pain_point_map": {
    "forecast_accuracy": true,
    "sales_efficiency": true,
    "pipeline_velocity": false,
    "revenue_predictability": true,
    "crm_frustration": false
  },
  "personalization_variables": {
    "ceo_name": "[auto-extracted from call intro]",
    "cro_name": "Jennifer Park",
    "cfo_name": "[auto-extracted]",
    "specific_revenue_target": "18% revenue growth",
    "specific_headcount_expansion": "Flat at 140 AEs",
    "stated_q_over_q_priority": "deal inspection and forecast accuracy — Q1 CRO priority",
    "named_competitor_mentioned": "None",
    "verbatim_pain_quote": "We had three deals in Q4 that moved from 'high confidence' to 'slipped' in the final two weeks of the quarter. That's not acceptable when we're trying to run a predictable business."
  },
  "outreach_angle": "Jennifer Park explicitly named late-quarter deal slippage as the top CRO priority — this is the exact problem PipelineIQ solves through AI-powered deal inspection",
  "recommended_sequence": "A_day0_urgent",
  "do_not_contact_flag": false,
  "analyst_sentiment": "in_line",
  "filing_follow_up": ["10-Q", "8-K"]
}

**Output Example (Day 0 outreach email generated from template merge):**

Subject: Jennifer Park's Q4 slip pattern — what PipelineIQ would have caught

Body:
---
Jennifer,

Listened to VLY's call this afternoon. Your specific call-out — three deals moving from high-confidence to slipped in the final two weeks of Q4 — is the exact pattern that surfaces in AI deal inspection before it becomes a miss.

What typically happens: reps classify deals as high-confidence based on rep-reported data, not AI-verified signals (call frequency, stakeholder engagement, contract activity). In the last 10 business days of the quarter, that gap becomes visible — but by then, it's too late to change the outcome.

PipelineIQ flags at-risk deals 4–6 weeks before quarter close, giving you time to act. A company similar to VLY with 140 AEs used this to eliminate late-quarter slippage from 11% to 3% of committed deals within two quarters.

Would 20 minutes to walk through how that specific slippage scenario gets caught make sense? I can share the exact deal inspection model.

[Your name]
PipelineIQ
---

## Success Metrics

**System Performance Metrics:**
- Transcript monitoring latency: < 30 minutes from earnings call end to signal extraction complete
- Extraction accuracy: Relevance score validated by human SDR review — target ≥ 80% agreement between AI score and SDR assessment
- False positive rate: < 15% of sequences triggered should result in SDR review determining "not relevant" on reflection
- Coverage rate: 100% of target account earnings calls captured within same business day

**Outreach Performance vs. Control:**
- Reply rate lift vs. standard SDR sequences: target ≥ 2.5× (e.g., if control is 3.2%, earnings-triggered sequences should achieve ≥ 8%)
- Positive reply rate (meeting booked or further conversation): target ≥ 4% on Class A and B signals
- Meeting conversion: target ≥ 35% of positive replies become first meetings
- Pipeline sourced from earnings-triggered outreach: track as a distinct source in Salesforce for quarterly attribution

**ROI Tracking:**
- Cost per signal (monitoring + enrichment + extraction compute): target < $8 per account per quarter
- Cost per meeting sourced: target < $400 (vs. $1,200+ for outbound SDR work without signal context)
- Pipeline influenced: earnings-triggered sequences should contribute ≥ 12% of SDR-sourced pipeline within 6 months of program launch

## Related Prompts
- [Funding Round Signal GTM Orchestration](./AI-Powered-B2B-SaaS-Funding-Round-Signal-GTM-Orchestration-&-New-Capital-Pipeline-Revenue-Intelligence-Engine.md)
- [Technographic Intelligence & Automated Competitor Displacement](./AI-Powered-B2B-SaaS-Technographic-Intelligence-&-Automated-Competitor-Displacement-GTM-Orchestration-Revenue-Intelligence-Engine.md)
- [Enterprise Account Penetration & Buying Committee Orchestration](../Account-Based-Marketing/AI-Powered-B2B-Enterprise-Account-Penetration-&-Buying-Committee-Orchestration-Intelligence-Engine.md)
- [Earnings Intelligence & Financial Filing Content Mining](../../03_Content-&-Creative/Repurpose-Rewrite/AI-Powered-B2B-Earnings-Intelligence-&-Financial-Filing-Content-Mining-Marketing-Intelligence-Engine.md)

## Integration Tips

**Clay Integration:**
- Create a Clay table called "Earnings Signal Queue" with columns mapped to every JSON field from the extraction prompt
- Use Clay's webhook trigger to receive the JSON output from your n8n or Zapier automation
- Build Clay Formulas that auto-classify sequences (A/B/C/D) based on `relevance_score` and `signal_class` fields
- Use Clay's AI Column feature to generate the personalized email draft using the 8 personalization variables as inputs
- Export finalized drafts to HubSpot Sequences or Outreach Sequences with one-click sync

**Salesforce Integration:**
- Add a custom field "Earnings Signal" (picklist: Class A/B/C/D/None) to the Account object
- Create a Salesforce trigger that automatically creates an SDR task when `relevance_score ≥ 7` is pushed from Clay
- Build a "Earnings-Triggered Pipeline" campaign source so all opportunities sourced from this program are attributed correctly
- Create a Salesforce dashboard showing "Accounts with Recent Earnings Signal" sorted by score — gives SDR team a prioritized daily work queue

**HubSpot Integration:**
- Create a custom property "Last Earnings Signal Date" and "Earnings Signal Class" on the Company object
- Build a HubSpot Workflow that enrolls contacts in the appropriate sequence (A, B, C) based on the earnings signal class property
- Use HubSpot Sequences with personalization tokens mapped to the extracted variables — {{stated_challenge_verbatim}}, {{cro_name}}, {{specific_growth_target}}
- Create a HubSpot report showing sequence performance by signal class to identify which signal type drives the highest response rates

**Seeking Alpha / FactSet Integration:**
- For Seeking Alpha API: use the `/v2/symbols/{ticker}/transcripts` endpoint to monitor earnings transcript availability; set up a webhook or polling interval (every 15 minutes) during earnings season
- For FactSet: use the FactSet Transcripts API with your watchlist of 150 tickers, configure push notifications to your n8n endpoint
- SEC EDGAR automation: use EDGAR's RSS feed (`https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany`) to monitor 8-K and 10-Q filings for your 150 target accounts — free, no API key required

**n8n Automation Workflow:**
- Trigger: New earnings transcript webhook from Seeking Alpha or FactSet
- Step 1: Fetch full transcript text
- Step 2: Enrich with Salesforce account data (current stage, owner, last contact date)
- Step 3: Send to Claude API with master extraction prompt
- Step 4: Parse JSON output, evaluate relevance score
- Step 5a (score ≥ 7): Push to Clay for email draft generation → route to Outreach/HubSpot sequence
- Step 5b (score 4–6): Create Salesforce task for SDR manual review
- Step 5c (score < 4): Log "Earnings reviewed — no signal" activity in Salesforce, no action

## Troubleshooting

**Problem:** AI extraction produces high false positive rates — flagging earnings calls as relevant when SDRs review them and disagree.
**Solution:** Audit the extraction prompt against a sample of 20 past transcripts. The most common failure mode is the AI interpreting generic "revenue growth" language as a specific sales efficiency signal. Add negative examples to the extraction prompt: "Do NOT flag as relevant if the only signal is revenue growth targets without accompanying language about CRO challenges, forecast accuracy, sales productivity, or operational efficiency." Also tighten the relevance score rubric — if you're seeing too many 7s, raise the threshold to 8 for automatic outreach and put 6–7 into human review.

**Problem:** Outreach reply rates from earnings signals aren't outperforming standard sequences.
**Solution:** Diagnose at the personalization level. Pull a sample of sent emails and check whether `{{stated_challenge_verbatim}}` is populated with a genuinely specific quote, or whether the extraction defaulted to generic language. Earnings-triggered outreach only outperforms when the quote you reference is specific and clearly maps to a pain your product solves. Also check timing — sequences sent 24–48 hours post-call consistently outperform same-day sends (4+ hours after call) because same-day sends sometimes arrive while the executive is still in investor meetings.

**Problem:** Target accounts are private companies that don't have public earnings calls.
**Solution:** For private companies, replace earnings call monitoring with equivalent private signal sources: (1) Press releases for funding announcements, leadership hires, and product launches via PRNewswire/BusinessWire RSS monitoring; (2) Job posting signals via LinkedIn API or PeopleDataLabs — when a private company posts for "VP Revenue Operations" or "Head of Sales Enablement," it indicates the same scale challenge an earnings call would surface for a public company; (3) LinkedIn company page follower growth as a proxy for organizational momentum; (4) Podcast appearances by the CRO or CEO where they discuss company challenges publicly. Build separate extraction prompts for each private signal type.

## Version History
- v1.0: Initial creation (auto-generated)
