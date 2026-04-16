# AI-Powered B2B Signal-Based Prospecting & Real-Time Account Trigger Outbound Intelligence Engine - The Complete Buying Signal Detection, Account Trigger Scoring & Hyper-Personalized Outreach Automation System

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** signal-based-selling, outbound-prospecting, b2b, demand-generation, intent-data, lead-generation, account-triggers, sdr, personalization, sales-development, pipeline-generation, automation

## Overview
Builds a fully autonomous AI-powered system that continuously monitors 15+ buying signal types across data sources, scores trigger combinations into prioritized prospect queues, and auto-generates hyper-personalized multi-touch outreach sequences — launching within minutes of a signal firing. Use this when your outbound conversion rates are below 3%, when SDRs are burning time on manual research, or when you need to scale pipeline generation without proportionally scaling headcount.

## Quick Copy-Paste Version

You are a B2B signal-based prospecting engine. I need you to build a complete trigger-based outbound system for my company.

MY COMPANY:
- Company: [e.g., Ashby — AI-native ATS and recruiting intelligence platform]
- Target buyers: [e.g., VPs of Talent Acquisition and CHROs at Series B–D tech companies, 200–2,000 employees]
- Primary pain we solve: [e.g., recruiting teams drowning in manual workflows; no visibility into funnel quality or offer acceptance predictors]
- Core differentiation: [e.g., structured hiring + analytics in one system vs. stitching Greenhouse + Lever + spreadsheets]
- Current outbound motion: [e.g., 3 SDRs, manual LinkedIn + cold email, ~1.5% reply rate, no signal-based triggers]

For each of the following 8 trigger types, generate:
1. Exactly what the trigger looks like (how I detect it)
2. Why it predicts buying intent (the psychology behind it)
3. A 3-touch outreach sequence (Email 1, LinkedIn DM, Email 2) — verbatim, personalized to this trigger
4. Timing: when to send each touch relative to signal detection

TRIGGER TYPES TO BUILD SEQUENCES FOR:

**Trigger 1 — Hiring for my buyer persona's team**
Signal: Target account posts 3+ open roles for Recruiters, Talent Partners, or Sourcers in 30 days.
Why it matters: [Generate the buying logic]
Sequences: [Generate verbatim email + LinkedIn + email]

**Trigger 2 — Leadership change in the buying role**
Signal: New VP of Talent Acquisition or CHRO hired in the last 60 days.
Why it matters: [Generate]
Sequences: [Generate]

**Trigger 3 — Funding event (Series B/C/D)**
Signal: Target company announced funding round in last 45 days.
Why it matters: [Generate]
Sequences: [Generate]

**Trigger 4 — Competitor tech stack detected**
Signal: Target company is listed as using [legacy ATS competitor] on G2, BuiltWith, or LinkedIn job descriptions.
Why it matters: [Generate]
Sequences: [Generate]

**Trigger 5 — Negative G2/Capterra review of incumbent**
Signal: Someone at the target account left a 2-3 star review of their current ATS in last 90 days.
Why it matters: [Generate]
Sequences: [Generate]

**Trigger 6 — Rapid headcount growth**
Signal: Target account grew headcount by 20%+ in last 6 months per LinkedIn data.
Why it matters: [Generate]
Sequences: [Generate]

**Trigger 7 — Content engagement signal**
Signal: Someone from the target account downloaded our "State of Recruiting Tech" report or attended a webinar.
Why it matters: [Generate]
Sequences: [Generate]

**Trigger 8 — Super Signal (3+ triggers firing simultaneously)**
Signal: Account has funding + leadership change + hiring surge all within 60-day window.
Why it matters: [Generate the compounding urgency logic]
Sequences: [Generate a more aggressive 5-touch sequence for this tier]

OUTPUT FORMAT: For each trigger, produce ready-to-send copy with [PERSONALIZATION VARIABLE] placeholders clearly marked. Every email under 150 words. Every LinkedIn DM under 75 words. Subject lines A/B tested (two options each).

## Advanced Customizable Version

ROLE: You are a B2B Signal Intelligence & Outbound Architecture AI Agent. You specialize in building trigger-based prospecting systems that combine real-time data signals with AI-generated personalization at scale — transforming reactive cold outreach into proactive, context-rich engagement that arrives at the exact moment a prospect is in an active buying window.

EXPERTISE: Revenue operations, SDR program design, intent data activation, signal scoring, multi-touch sequence architecture, deliverability engineering, and buyer psychology.

MISSION: Design a complete, production-ready Signal-Based Prospecting Intelligence System for the company described below. This system must be fully automatable — an AI agent should be able to execute the entire workflow from signal detection through sequence delivery without human intervention except for quality review gates.

---

### PART 1: COMPANY & ICP CONTEXT

**Company information:**
- Company name & product: [e.g., Mosaic — AI-powered financial planning and revenue intelligence for CFOs]
- Product category: [e.g., Strategic Finance Platform — replaces Excel-based FP&A with real-time scenario modeling]
- Primary ICP: [e.g., CFOs and VPs of Finance at Series B–D SaaS companies, $5M–$50M ARR, 50–500 employees]
- Secondary ICP: [e.g., Controllers and FP&A Managers who influence the CFO's tool evaluation]
- Core pain solved: [e.g., Finance teams spending 80% of time in spreadsheets, no real-time visibility into runway or revenue forecast]
- Key differentiators: [e.g., CRM + HRIS + billing data integration in one model, 10x faster board deck prep]
- Average deal size: [$X ARR] | Sales cycle: [X weeks] | Win rate: [X%]
- Current outbound results: [Reply rate: X%, Meeting rate: X%, Signal-based triggers used: None/Basic/Advanced]

**ICP firmographic filters:**
- Company size: [e.g., 50–500 employees]
- Industries: [e.g., SaaS, FinTech, HealthTech — exclude agencies and services firms]
- Funding stage: [e.g., Series A minimum, raised in last 18 months preferred]
- Tech stack signals: [e.g., Salesforce or HubSpot as CRM, Stripe or Recurly for billing, suggests SaaS model]
- Geography: [e.g., North America primary, UK/ANZ secondary]
- Exclusions: [e.g., Bootstrapped, pre-revenue, government, nonprofit]

---

### PART 2: SIGNAL TAXONOMY & SCORING MODEL

Build a complete signal library. For each signal category, generate: detection method, data source, signal strength score (1–10), and decay window (how long the signal stays relevant).

**TIER 1 — HIGH-INTENT SIGNALS (Score 8–10, Act within 24 hours)**

Signal 1.1 — Role-specific hiring surge
- What to detect: 3+ open finance roles (FP&A, Financial Analyst, Controller) posted in 30-day window
- Data sources: LinkedIn Jobs API, Greenhouse/Lever job boards, Indeed, Glassdoor
- Signal score: 9 | Decay window: 45 days
- Buying logic: [Generate: why hiring finance headcount predicts openness to finance tooling]
- Disqualification check: [e.g., exclude if company is hiring for a Finance Director role — signals they may be building internal capacity rather than buying tools]

Signal 1.2 — Leadership transition in buying role
- What to detect: New CFO, VP Finance, or Controller hired in last 60 days (LinkedIn "Started new role" notification)
- Data sources: LinkedIn Sales Navigator Job Change Alerts, Zoominfo Scoops, Bombora new hire signal
- Signal score: 10 | Decay window: 90 days
- Buying logic: [Generate: the "first 90 days" mandate and tool stack evaluation psychology]
- Enrichment required: Pull new hire's previous company to identify what tools they used — if they came from a company using [competitor], lead with migration narrative

Signal 1.3 — Funding event (relevant stage)
- What to detect: Series B, C, or D funding announcement within 45 days
- Data sources: Crunchbase API, Dealroom, TechCrunch Funding RSS, PitchBook alerts
- Signal score: 8 | Decay window: 60 days
- Buying logic: [Generate: post-funding tool evaluation cycle, board reporting pressure, investor CFO scrutiny]
- Trigger refinement: Weight higher if founding team is engineering-heavy with no dedicated finance hire yet

Signal 1.4 — Negative competitor review
- What to detect: 2–3 star review of [Competitor A] or [Competitor B] posted by someone with target company email domain on G2, Capterra, or Trustpilot in last 90 days
- Data sources: G2 API (review webhook), Capterra scrape, ReviewTrackers
- Signal score: 9 | Decay window: 30 days
- Buying logic: [Generate: active dissatisfaction + validation that they're already evaluating the category]

**TIER 2 — MEDIUM-INTENT SIGNALS (Score 5–7, Act within 72 hours)**

Signal 2.1 — Rapid headcount scaling
- What to detect: 25%+ headcount growth in 6 months per LinkedIn employee count tracking
- Data sources: LinkedIn Company Insights, Harmonic.ai, People Data Labs
- Signal score: 7 | Decay window: 60 days
- Buying logic: [Generate: scaling companies outgrow spreadsheets; finance complexity grows non-linearly with headcount]

Signal 2.2 — Board composition change or investor addition
- What to detect: New board member or lead investor with operational finance background joins
- Data sources: Crunchbase board tracking, LinkedIn executive changes, company press releases
- Signal score: 6 | Decay window: 90 days
- Buying logic: [Generate: new board members bring tool standards from portfolio companies; investor CFOs mandate reporting infrastructure upgrades]

Signal 2.3 — Tech stack trigger (new tool adoption suggesting category readiness)
- What to detect: Target company recently added Salesforce, HubSpot, or NetSuite (signals investment in business systems)
- Data sources: BuiltWith, HG Insights, Datanyze, G2 Stack
- Signal score: 6 | Decay window: 120 days
- Buying logic: [Generate: systematic business system investment patterns predict finance tool evaluation windows]

Signal 2.4 — Content engagement (first-party intent)
- What to detect: Contact from target account viewed pricing page 2+ times, downloaded ROI calculator, or attended webinar
- Data sources: HubSpot/Marketo behavioral data, Clearbit Reveal for anonymous traffic, Demandbase IP identification
- Signal score: 7 | Decay window: 14 days
- Buying logic: [Generate: recency and specificity of content intent signals]

Signal 2.5 — Conference attendance (relevant industry event)
- What to detect: Target account employees listed as attending SaaStr, CFO Summit, Pavilion Finance Summit, or similar event
- Data sources: Event attendee lists (LinkedIn event RSVPs, conference hashtag monitoring), speaker announcements
- Signal score: 5 | Decay window: 30 days (pre-event) / 14 days (post-event)
- Buying logic: [Generate: event attendance as proxy for active investment in professional development and vendor evaluation]

**TIER 3 — AWARENESS SIGNALS (Score 1–4, Nurture only, no direct outreach)**

Signal 3.1 — Social engagement with competitor content
Signal 3.2 — Category keyword search activity (third-party intent)
Signal 3.3 — Tangential industry news (new regulation, economic event affecting industry)
- For each: [Generate detection method, data source, and nurture action — add to ad audiences, not SDR queue]

---

### PART 3: SIGNAL SCORING & ACCOUNT PRIORITIZATION ENGINE

**Composite Signal Score formula:**
Build a scoring model that aggregates signals into an Account Priority Score (APS).

For each target account, calculate daily:
APS = Σ(Signal Score × Recency Multiplier × ICP Fit Score)

Where:
- Signal Score = Tier 1–3 score from library above
- Recency Multiplier = 1.0 (within decay window) → 0.5 (at 50% of decay window) → 0.0 (expired)
- ICP Fit Score = 1.0 (perfect ICP match) / 0.7 (close match) / 0.3 (fringe match)

**Super Signal Threshold:** APS ≥ 20 within a 30-day window = activate Tier 1 (high-urgency) sequence
**Standard Threshold:** APS 10–19 = activate Tier 2 (standard) sequence
**Nurture Threshold:** APS 5–9 = ad retargeting only, no SDR outreach
**Disqualified:** APS < 5 = suppress from active outreach

Generate: 3 example account profiles showing how the scoring model works in practice with realistic signal combinations and resulting APS scores.

---

### PART 4: OUTREACH SEQUENCE ARCHITECTURE

For each signal type, generate a complete multi-touch sequence. Sequences must be:
- Verbatim and send-ready (not templates requiring heavy editing)
- Signal-specific in the opening line (personalization that can only be written for THIS trigger)
- Value-led, not pitch-led (lead with insight, not "we help companies like yours")
- Under 150 words per email / Under 75 words per LinkedIn message
- A/B tested subject lines (2 variants per email)

**SEQUENCE FORMAT FOR EACH SIGNAL:**

SIGNAL: [Signal name]
TRIGGER CONDITION: [What exact event fires this sequence]
SEQUENCE OWNER: SDR | Marketing automation | Sales rep | AI agent
APPROVAL GATE: Auto-send | Human review required before send

Touch 1 — Email (Send within [X hours] of signal)
Subject A: [Subject line variant A]
Subject B: [Subject line variant B]
Body: [Full email text — under 150 words]
[PERSONALIZATION VARIABLES] clearly bracketed

Touch 2 — LinkedIn DM (Send [X days] after Touch 1 if no reply)
Message: [Full DM text — under 75 words]
Connection note (if not connected): [25-word note]

Touch 3 — Email (Send [X days] after Touch 2 if no reply)
Subject A: [Subject line variant A]
Subject B: [Subject line variant B]
Body: [Full email text — shorter than Touch 1, direct ask]

Touch 4 — Break-up email (Send [X days] after Touch 3 if no reply)
Subject: [Break-up subject — curiosity-driven, low pressure]
Body: [Under 75 words — permission to disengage or resurface interest]

**Generate complete sequences for:**
1. New CFO hire (Tier 1 — highest priority)
2. Funding announcement + hiring surge (Super Signal)
3. Negative competitor G2 review
4. Rapid headcount growth (25%+ in 6 months)
5. Content engagement — pricing page viewed 3+ times
6. Conference attendance (pre-event)

---

### PART 5: DELIVERABILITY & INFRASTRUCTURE REQUIREMENTS

Generate a deliverability checklist and infrastructure specification for running signal-based outbound at scale without harming sender reputation.

**Email Infrastructure:**
- Domain configuration: [Generate: exact SPF, DKIM, DMARC setup requirements]
- Sending domain strategy: [Generate: primary domain protection vs. subdomain warming]
- Inbox warmup: [Generate: sequence volume ramp, what tools to use — Lemwarm, Mailreach, Instantly warmup]
- Volume limits: [Generate: safe daily send limits by mailbox age — Week 1, Month 1, Month 3+]

**List hygiene automation:**
- Bounce handling: [Generate: hard bounce threshold, suppression rules]
- Engagement-based suppression: [Generate: when to remove from active outreach]
- GDPR/CCPA compliance: [Generate: opt-out mechanism, data retention policy, right-to-erasure workflow]

**A/B test architecture:**
- What to test first: Subject line vs. opening line vs. CTA — generate testing priority rationale
- Statistical significance threshold: [Generate: sample size requirements for valid conclusions]
- Test cadence: [Generate: weekly review cadence, what metrics to review]

---

### PART 6: TECH STACK INTEGRATION MAP

Generate a specific tool recommendation and integration workflow for each component of the system.

**Signal detection & monitoring:**
- LinkedIn signals → [Tool: Sales Navigator + Phantombuster or Clay.com] → [Output: enriched lead record in CRM]
- Funding signals → [Tool: Crunchbase Pro API or Harmonic] → [Output: Slack alert + CRM task creation]
- Tech stack signals → [Tool: HG Insights or BuiltWith API] → [Output: account enrichment field update]
- G2 review signals → [Tool: G2 Buyer Intent API] → [Output: account scoring update in MAP]
- First-party intent → [Tool: HubSpot Behavioral Events or Marketo RTP] → [Output: real-time SDR alert]

**Sequence execution:**
- [Tool: Outreach.io, Salesloft, Apollo, or Instantly] for email sequence automation
- [Tool: LinkedIn Sales Navigator InMail or Expandi for LinkedIn automation]
- [Tool: Clay.com] for AI-personalized first-line generation at scale

**Scoring & prioritization:**
- [Tool: 6sense, Demandbase, or Clearbit] for account scoring aggregation
- [Tool: HubSpot, Salesforce] as CRM of record for APS field and SDR task routing

**Reporting:**
- [Metrics to track per signal type]: Signal-to-meeting rate, signal-to-pipeline rate, sequence step conversion, reply sentiment breakdown
- [Dashboard recommendation]: Metabase or Looker for signal performance reporting; weekly SDR signal review meeting agenda

---

### PART 7: AI AGENT AUTOMATION WORKFLOW

Design the full end-to-end automation workflow that an AI agent executes daily without human intervention.

**Daily Agent Workflow (runs at 6am in target prospect's timezone):**

Step 1: Signal Harvest
→ Pull new signals from all configured data sources (LinkedIn, Crunchbase, G2, first-party MAP)
→ Deduplicate against last 90-day signal log
→ Enrich new signals with firmographic data (company size, funding, tech stack)

Step 2: Account Scoring
→ Calculate updated APS for all accounts with new signals
→ Flag accounts crossing priority thresholds (Nurture→Standard, Standard→Super Signal)
→ Update CRM account records with new APS score and signal breakdown

Step 3: Sequence Trigger Logic
→ For accounts crossing Standard threshold: check if SDR is assigned, if sequence is already active
→ If no active sequence: generate personalized opening line using signal context → queue Touch 1 for send
→ For Super Signal accounts: route to SDR Slack notification + auto-queue sequence with human review gate

Step 4: Personalization Generation
→ For each new prospect entering sequence: pull signal context (e.g., "just raised Series B on April 14")
→ Generate signal-specific first line using AI: "Saw [Company] just closed your Series B — congrats..."
→ Insert into sequence template, flag for SDR review (< 2 min review time target)

Step 5: Send Execution
→ Send Touch 1 for all approved sequences
→ Log send events in CRM (timestamp, signal trigger, template version, subject line variant)
→ Update A/B test tracking dashboard

Step 6: Response Processing
→ Monitor for replies, auto-categorize (Positive/Neutral/Out of Office/Unsubscribe/Negative)
→ For positive replies: alert SDR immediately via Slack with full context (signal type, sequence history, company background)
→ For OOO replies: pause sequence and resume after OOO end date
→ For unsubscribes: suppress contact across all tools (CRM, MAP, LinkedIn)

Step 7: Daily Report Generation
→ Output: Signals detected, accounts scored, sequences triggered, emails sent, reply rate, meetings booked
→ Highlight: Super Signal accounts requiring SDR attention today
→ Distribute: SDR manager morning briefing Slack message

---

### PART 8: PERFORMANCE BENCHMARKS & OPTIMIZATION TRIGGERS

Generate realistic performance benchmarks for each signal type and define optimization trigger thresholds.

**Benchmark Targets (B2B SaaS, ACV $30K–$150K):**

| Signal Type | Expected Reply Rate | Meeting Rate | Pipeline per 100 Triggers |
|---|---|---|---|
| New CFO hire | 15–25% | 8–12% | $400K–$800K |
| Super Signal (3+ triggers) | 20–35% | 12–18% | $600K–$1.2M |
| Funding announcement | 8–15% | 4–8% | $200K–$400K |
| Negative competitor review | 12–20% | 6–10% | $250K–$500K |
| Rapid headcount growth | 6–12% | 3–6% | $120K–$300K |
| Content engagement | 18–30% | 10–15% | $450K–$900K |
| Conference attendance | 8–14% | 5–9% | $200K–$350K |

**Optimization Triggers (when to change sequences):**
- Reply rate < 50% of benchmark after 50 sends: Rewrite subject lines, A/B test new opening
- Meeting rate < 50% of benchmark: Review CTA clarity, add social proof or urgency element
- Unsubscribe rate > 2%: Reduce sequence volume, audit signal quality — may be reaching wrong tier accounts
- 0 Super Signal accounts in 30 days: Audit signal detection logic, likely data source failure

Generate: 5 specific optimization experiments to run in first 90 days, with hypothesis, test design, and success criteria.

---

## Example Input/Output

**Input Example:**

Company: Navan (formerly TripActions) — Business travel and expense management platform
Target buyers: CFOs and VPs of Finance at companies 200–2,000 employees
Signal fired: "Brex announces layoffs of 20% of headcount + Navan prospect account (MedTech company, 400 employees) just posted 2-star Brex review on G2"

**Output Example — Negative Competitor Review Sequence:**

---
**Touch 1 — Email (Send within 4 hours of G2 review detection)**

Subject A: Your Brex review caught our attention
Subject B: After that Brex review — worth 15 minutes?

Hi [FIRST NAME],

Saw your G2 review of Brex this week — the frustration around [REVIEW PAIN POINT, e.g., "receipt matching requiring manual uploads"] is something we hear constantly from finance teams at [COMPANY SIZE]-person companies.

Navan automatically syncs every transaction with receipt capture, policy enforcement, and real-time spend visibility — no manual reconciliation.

We've helped 40+ MedTech companies [INDUSTRY RELEVANCE] cut T&E close time from 5 days to 4 hours.

Worth a 15-minute look? Happy to show you specifically how we'd handle [REVIEW PAIN POINT].

[SIGNATURE]

P.S. — We have a MedTech customer reference happy to take your call if that's useful.

---

**Touch 2 — LinkedIn DM (Day 3 if no reply)**

Hi [FIRST NAME] — noticed your recent Brex feedback. The [PAIN POINT] issue is solvable. Navan handles it automatically for companies your size. Would love to show you a 10-minute demo — can I send a calendar link?

---

**Touch 3 — Email (Day 7)**

Subject A: Still thinking about the Brex situation?
Subject B: Quick question about your T&E process

[FIRST NAME],

Finance leaders at [COMPANY SIMILAR PEER] switched from Brex to Navan last quarter — saved $180K annually and cut month-end close from 6 days to 2.

Happy to share how they did it. 15 minutes this week?

[SIGNATURE]

---

## Success Metrics

**System-Level Metrics (measure monthly):**
- Total signals detected vs. signals actioned (target: >80% of Tier 1 signals result in sequence trigger within 24 hours)
- Signal-to-meeting rate by signal type (benchmark targets above)
- Signal-sourced pipeline as % of total pipeline (target: 25–40% within 6 months)
- Cost per signal-sourced meeting vs. cold outbound meeting

**Sequence Performance Metrics (measure weekly per signal type):**
- Open rate (target: >45% for signal-specific subject lines)
- Reply rate (target: signal-type benchmark ± 20%)
- Positive reply rate (target: >60% of replies classified positive or neutral)
- Meeting acceptance rate from reply (target: >50%)
- Meeting no-show rate (target: <20% — high-intent signals should produce higher show rates)

**Quality Metrics:**
- SDR time saved per week vs. manual research baseline (target: >5 hours/SDR/week)
- Personalization score (0–10 scale based on SDR review — is the AI-generated first line truly signal-specific?)
- Data source accuracy rate (spot-check 10% of signals weekly — are they real and recent?)

## Related Prompts

- [AI-Powered B2B Intent Data Program Architecture & Multi-Signal Revenue Orchestration Intelligence Engine](./AI-Powered-B2B-Intent-Data-Program-Architecture-&-Multi-Signal-Revenue-Orchestration-Intelligence-Engine.md)
- [ABM Intent Data Activation & Buying Signal Prioritization Engine](../Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md)
- [AI-Powered B2B Outbound SDR Program & Cold Outreach Intelligence Engine](../../02_Product-Marketing/Sales-Enablement-Content/AI-Powered-B2B-Outbound-SDR-Program-&-Cold-Outreach-Intelligence-Engine.md)
- [AI-Powered Demand Sensing & Market Signal Intelligence Engine](../../05_Analytics-&-Performance/Demand-Sensing-&-Market-Intelligence/AI-Powered-Demand-Sensing-&-Market-Signal-Intelligence-Engine.md)

## Integration Tips

**HubSpot:** Use Workflows + Custom Properties to store APS score per account. Create a Deal Pipeline stage triggered when APS crosses threshold. Connect Crunchbase via Zapier for funding signal auto-enrichment. Use Sequences for email automation with personalization tokens mapped to signal fields.

**Salesforce:** Build a custom "Signal Score" field on Account object. Use Flow to auto-create SDR tasks when score exceeds threshold. Integrate with Outreach or Salesloft via native connector for sequence execution. Use Einstein Activity Capture to log signal-correlated meetings back to the account.

**Clay.com:** Build a Clay table that pulls signals from multiple sources (LinkedIn, Crunchbase, G2 via Zapier), runs enrichment waterfalls, and auto-writes personalized first lines using AI columns. Output to Smartlead or Instantly for email execution.

**Slack:** Configure signal alert Webhook to post Super Signal notifications to #sdrs-signal-alerts channel with full context: account name, signal type, APS score, assigned SDR, direct link to CRM account. Include one-click "Start Sequence" button via Salesforce Slack app.

**Zapier/Make:** Build automation: G2 Review Intent webhook → Enrich with Clearbit → Score in spreadsheet → If APS > threshold → Create Outreach sequence → Log in HubSpot. Total build time: 4–6 hours for a non-technical operator.

## Troubleshooting

**Problem: Signal detection is generating false positives (e.g., flagging accounts that already bought or have active deals)**
Solution: Build an exclusion list that syncs with your CRM daily — suppress any account with an open opportunity, active customer status, or "Lost" deal in last 90 days. Add a "Do Not Contact" field check before any sequence trigger fires. Review exclusion list weekly to ensure CRM data quality.

**Problem: AI-generated personalization first lines feel generic despite signal specificity**
Solution: The opening line prompt needs to be more specific about what to include. Instead of "You just raised funding," use "Saw [Company] closed your $[AMOUNT] Series B led by [INVESTOR] on [DATE] — impressive milestone." Pull funding details from Crunchbase enrichment and inject full context. Test prompt variations with SDRs rating outputs 1–5 until average score exceeds 4.

**Problem: Reply rates are good but meeting acceptance rates are low**
Solution: Your CTA is likely too vague. Replace "would love to connect" with a specific value exchange: "I'll show you exactly how [PEER COMPANY] eliminated [PAIN FROM SIGNAL] in 30 days — here's a 15-minute slot this week." Alternatively, lead with the peer customer reference rather than a product demo — warm introductions to customers convert at 2–3x higher rates than demo offers.

## Version History
- v1.0: Initial creation (auto-generated)
