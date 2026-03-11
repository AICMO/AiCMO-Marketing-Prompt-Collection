# Signal-Based GTM Automation & Revenue Trigger Engine - Autonomous Buying Signal Detection, Scoring & Multi-Motion Orchestration

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** demand generation, signal-based selling, GTM automation, intent data, revenue operations, AI agents

## Overview

Builds a fully autonomous, signal-based go-to-market system that monitors dozens of first-party and third-party buying signals, scores and routes them to the optimal GTM motion (SDR outreach, marketing nurture, CSM expansion, or partner-assisted), and generates hyper-personalized outreach at scale — without manual SDR research or routing decisions. Use when your team is leaving revenue on the table because you can't act on signals fast enough, or when outbound is volume-based rather than signal-triggered.

## Quick Copy-Paste Version

You are a GTM automation architect. Build a complete signal-based revenue trigger system for [Your Company], a [B2B SaaS/tech company] selling [Your Product] to [Your ICP: e.g., VP Sales at Series B+ SaaS companies, 50-500 employees].

**Step 1 — Build the Signal Taxonomy**
Create a categorized list of 20+ buying signals across these categories:
- First-Party Behavioral (pricing page visits, demo request abandonment, feature usage spikes, doc page visits for advanced features)
- Firmographic Triggers (funding rounds, headcount growth >20% in 90 days, new executive hire in buyer role, geographic expansion)
- Intent & Research (G2/Capterra profile visits, competitor review activity, relevant job postings, third-party intent keywords from Bombora/6sense)
- Social & Community (LinkedIn posts about the pain we solve, conference speaking on relevant topics, podcast appearances, community questions)
- Technographic Changes (competitor tool removal from BuiltWith/Datanyze, integration partner adoption, relevant tech stack additions)
- Relationship Signals (mutual connections, alumni network overlap, reply to cold email, content engagement sequence)

**Step 2 — Build the Signal Scoring Model**
For each signal, assign:
- Signal Strength: 1-10 (recency + intent specificity + historical conversion correlation)
- Decay Rate: how quickly signal loses value (hours/days/weeks)
- Composite Score formula: sum weighted signals, normalize to 0-100

Thresholds:
- 0-29: Marketing Nurture (drip sequence, retargeting ads)
- 30-59: Sales Development (SDR personalized outreach, 5-touch sequence)
- 60-79: AE Direct Engagement (AE outreach + exec sponsor email)
- 80-100: Priority Pursuit (multi-thread, gift/direct mail, exec-to-exec)

**Step 3 — Generate Outreach for a Specific Account**
Use this account profile to generate outreach:
- Company: [Company Name]
- Signals Detected: [list 3-5 signals with dates]
- Contact: [Name, Title, LinkedIn URL]
- Composite Signal Score: [0-100]
- Our Product: [what we sell]
- Their Likely Pain: [infer from signals]

Generate:
1. Email subject line (A/B: pattern interrupt + curiosity)
2. Email body (< 100 words, signal-led opening, one specific insight, one soft CTA)
3. LinkedIn connection request note (< 300 chars)
4. LinkedIn follow-up message (if connected, Day 3)
5. Call voicemail script (20 seconds)
6. SDR internal briefing (bullet points: why now, what to say, what NOT to say)

**Step 4 — Build the Orchestration Playbook**
For each GTM motion tier, output a table with:
- Trigger conditions
- Owner (SDR / AE / Marketing / CS)
- Day 0 action (within 4 hours of signal)
- 14-day sequence (channels + messages)
- Success metric
- Disqualification criteria

## Advanced Customizable Version

ROLE: You are a Revenue Intelligence Architect with expertise in signal-based GTM strategy, intent data activation, and autonomous outbound orchestration. You have implemented signal-led systems at $10M-$500M ARR B2B SaaS companies and understand the full tech stack from data capture to CRM routing to personalized execution.

CONTEXT:
Company: [Company Name]
Product: [Product description — one sentence on what it does and for whom]
ICP Definition:
  - Firmographics: [Industry, company size, geography, funding stage]
  - Technographics: [Tech stack they typically run — CRM, MAP, data tools]
  - Roles: [Primary buyer, champion, influencer, blocker]
  - Pain Triggers: [Top 3 problems we solve]
  - ACV: [$X — affects how aggressive the pursuit model should be]
Current State: [Describe current outbound process — e.g., "SDRs pull lists weekly from ZoomInfo, no intent data, 2% reply rates"]
Tech Stack Available: [e.g., HubSpot, Salesforce, Apollo, Clay, Bombora, 6sense, Clearbit, LinkedIn Sales Nav, Slack]

OBJECTIVE: Build a production-ready, AI-executable signal-based GTM system that can run autonomously with minimal human intervention. The system must be deterministic (same inputs = same routing decision) and auditable.

---

MODULE 1: SIGNAL TAXONOMY & INSTRUMENTATION PLAN

For each signal category, output a structured table:

| Signal Name | Source Tool | Data Point Captured | Capture Method | Latency | Signal Weight (1-10) | Decay Window |
|---|---|---|---|---|---|---|

Categories to cover (minimum 5 signals per category):

**Category A: First-Party Website & Product Signals**
- Pricing page: >2 visits in 14 days = high intent
- Feature docs for [premium/advanced features]: indicates upgrade research
- Demo abandonment: started but didn't complete (recapture sequence)
- Integration docs: researching whether we connect to their stack
- Case study page: >3 studies consumed = deep evaluation mode
- ROI calculator completion: highest-intent page in site
- Careers page for [relevant role]: understands our product, maybe hiring

**Category B: Firmographic Event Triggers**
Use: LinkedIn, Crunchbase, Apollo, PitchBook, Diffbot
- Series A/B/C funding announced: new budget, new initiatives
- New VP/Director of [Buyer Function] hired: new decision maker, 90-day window
- Headcount growth >20% QoQ in target department: scaling pain
- New office opened in [our geographic focus market]
- Acquisition announcement: integration needs, stack consolidation
- Company IPO filed or announced: compliance, scale, visibility

**Category C: Third-Party Intent & Research Signals**
Use: Bombora, G2, TrustRadius, 6sense, Demandbase
- Surge in [your category keywords]: e.g., "sales engagement platform," "revenue intelligence"
- G2 competitor profile viewed by accounts in your ICP
- Review written about a competitor (positive or negative)
- Analyst report downloaded that covers our category
- Gartner/Forrester Magic Quadrant research activity

**Category D: Social & Community Signals**
Use: LinkedIn Sales Navigator, Mention, Sparktoro, Common Room
- LinkedIn post asking about [problem we solve] — within 48 hours = urgent
- Comment on competitor's content expressing frustration
- Community post in relevant Slack/Discord (RevOps Co-op, Pavilion, etc.)
- Speaking slot accepted at conference covering our space
- Published article/newsletter mentioning pain we address

**Category E: Technographic Change Signals**
Use: BuiltWith, Datanyze, HG Insights, Siftery
- Competitor tool REMOVED from their stack (displacement opportunity)
- Our integration partner ADDED (complementary adoption)
- Data warehouse tool added (readiness for our data-heavy product)
- Relevant compliance tool added (regulatory trigger)

**Category F: Relationship & Engagement Signals**
Use: HubSpot, Outreach, LinkedIn, email tracking
- Opened email 3+ times without replying (high interest, unclear objection)
- Clicked link to ROI page or case study in outreach email
- Viewed LinkedIn profile of our AE or SE after cold outreach
- Mutual connection in common (warm intro opportunity)
- Previously engaged lead re-engaged after 90+ days dark

---

MODULE 2: COMPOSITE SIGNAL SCORING ENGINE

Design a mathematical scoring model:

**Base Score Calculation:**
Signal_Score = Σ (Signal_Weight × Recency_Multiplier × Confidence_Factor)

Recency Multipliers:
- Signal < 24 hours old: 1.0x
- 1-3 days: 0.85x
- 4-7 days: 0.65x
- 8-14 days: 0.40x
- 15-30 days: 0.20x
- > 30 days: 0.05x (decay to noise)

Confidence Factors:
- Direct first-party data (our own tracking): 1.0x
- Verified third-party (Bombora Surge confirmed): 0.85x
- Inferred from proxy signal: 0.60x
- Social/community (noisy, could be research): 0.50x

**Score Normalization:**
Raw scores vary wildly. Normalize to 0-100 using:
Normalized = (Raw_Score / Max_Possible_Score) × 100

Adjust for ICP Fit:
- Perfect ICP fit: no penalty
- Partial ICP fit (missing 1 criterion): -15 points
- Weak ICP fit (missing 2+ criteria): -30 points

**Routing Thresholds:**
| Score Range | GTM Motion | Owner | SLA |
|---|---|---|---|
| 0-19 | Drip Nurture + Retargeting | Marketing Automation | 24-hour enrollment |
| 20-39 | SDR Assisted Outreach | SDR | Within 4 business hours |
| 40-59 | SDR Priority + AE Briefed | SDR lead, AE informed | Within 2 business hours |
| 60-79 | AE Direct + Multi-Thread | AE owns, SDR supports | Within 1 business hour |
| 80-100 | Executive Pursuit + Gifting | AE + VP/CRO + SDR | Within 30 minutes |

---

MODULE 3: AUTONOMOUS OUTREACH GENERATION

For each account routed, generate a complete outreach package. Use this framework:

**Signal-Led Personalization Framework (SLIP):**
S — Specific Signal: name the exact trigger ("I noticed you posted on LinkedIn about…")
L — Link to Outcome: connect signal to a business outcome they care about
I — Insight: add one non-obvious insight they haven't heard before
P — Precise Ask: one specific, low-friction next step

**Outreach Templates by Channel:**

EMAIL (Channel 1 of 5-touch sequence):
- Subject lines: Test two variants
  - Pattern Interrupt: "[First Name], [unexpected observation]"
  - Mutual Connection/Context: "Re: your [LinkedIn post/funding/hire] — a thought"
- Body structure:
  - Line 1: Signal acknowledgment (1 sentence, ultra-specific)
  - Line 2-3: Insight or stat they haven't seen (non-obvious, cite source)
  - Line 4: Social proof (similar company, similar signal, outcome)
  - Line 5: One specific ask (15-min call, Loom video, resource)
- Length: 75-100 words max

LINKEDIN MESSAGE (Channel 2):
- Connection note: < 300 chars, no pitch, reference signal naturally
- Follow-up message (Day 3 after connect): < 500 chars, SLIP framework

COLD CALL VOICEMAIL (Channel 3):
- 20-second script
- Lead with signal ("Reason for my call — saw that [company] just [signal]…")
- State one outcome you've helped similar companies achieve
- CTA: "I'll shoot you a quick email with one idea — no ask, just useful"

DIRECT MAIL / GIFT (80-100 score only, Channel 4):
- Gift recommendation based on signal (e.g., funding round → champagne + hand-written note; new exec hire → "The First 90 Days" book + note)
- Personalized gift note copy template

VIDEO PROSPECTING (Channel 5, for 60+ scores):
- Loom/Vidyard script outline (90 seconds)
- Screen share: their website/LinkedIn + our relevant case study
- Framework: Problem → Proof → Path → Ask

---

MODULE 4: GTM MOTION PLAYBOOK (14-DAY SEQUENCES)

For each routing tier, build the full 14-day orchestration:

**Tier 1: Marketing Nurture (Score 0-19)**
Goal: Warm the account until score crosses 20+

| Day | Channel | Action | Content |
|---|---|---|---|
| 0 | Email | Enroll in drip sequence | Educational email: "The [Category] Benchmark Report" |
| 0 | Display | Add to retargeting audience | Brand + case study ads |
| 3 | Email | Value email 2 | "[Pain Point] Checklist: How [Peer Company] Fixed It" |
| 7 | LinkedIn | Like/comment on their recent post (SDR) | Genuine engagement only |
| 10 | Email | Case study | "[Exact ICP Company] went from [X] to [Y] in 90 days" |
| 14 | Email | Direct CTA | "Worth 15 minutes?" |

**Tier 2: SDR Outreach (Score 20-39)**
Goal: Book exploratory call within 14 days

[Full 5-touch, 3-channel sequence with specific messaging per day]

**Tier 3: SDR Priority + AE Briefed (Score 40-59)**
Goal: Book qualified discovery call, multi-thread by Day 7

[Full sequence with AE intro email by Day 5, executive sponsor outreach by Day 10]

**Tier 4: AE Direct Pursuit (Score 60-79)**
Goal: Booked discovery + business case request within 7 days

[Compressed 7-day sequence, AE-led, SDR as support]

**Tier 5: Executive Pursuit (Score 80-100)**
Goal: CEO/VP meeting within 5 days; gift dispatched Day 0

[High-touch sequence: gift D0, CEO email D1, AE call D2, exec-to-exec D4]

---

MODULE 5: TECH STACK IMPLEMENTATION BLUEPRINT

**Data Layer (Signal Capture):**
- First-Party Behavioral: HubSpot Tracking Code / Segment / Heap → pipe to CRM
- Firmographic Events: Clay.com (enriches accounts nightly using Clearbit + Crunchbase APIs)
- Intent Data: Bombora Surge → HubSpot Custom Object → Score update trigger
- Social Signals: Common Room or Trigify → Webhook → HubSpot

**Scoring Layer:**
- HubSpot Calculated Properties (for teams ≤ 500 accounts)
- Clay Enrichment Tables with formula columns (mid-market)
- Custom Python script / n8n workflow for complex multi-source scoring (enterprise)

**Routing Layer:**
- HubSpot Workflows: If Score crosses threshold → Create Task → Assign Owner
- Salesforce Apex Trigger: Score field update → Lead Routing Rule fires
- Slack notification: Zapier → #hot-accounts Slack channel with signal summary

**Execution Layer:**
- SDR Tier (20-59): Outreach.io or Apollo sequences, auto-enroll on signal
- AE Tier (60-79): Salesloft cadences, AE-personalized steps
- Executive Tier (80-100): Handwritten note via Sendoso/Reachdesk, manual AE outreach

**Reporting Layer:**
- Weekly Signal Report: Accounts by tier, signal volume, sequence engagement
- Signal Attribution: Which signals most correlated with meetings booked (track in HubSpot Deals)
- ROI Dashboard: Signal → Meeting → Opportunity → Revenue conversion rates

---

MODULE 6: DISQUALIFICATION CRITERIA & GUARDRAILS

Do NOT route to any active sequence if:
- Account is an existing customer (route to CSM expansion motion instead)
- Account already in active opportunity (route to AE for deal acceleration)
- Contact opted out of all communications
- Account is a competitor
- Account is too small/large for ICP (score penalty should have caught this)

Human review required before outreach if:
- Score ≥ 80 and company has fewer than 10 employees (anomaly check)
- Signal is social post that could be interpreted ambiguously
- Executive-level contact at a brand-name account (do not auto-send)

OUTPUT FORMAT:
Deliver a complete Signal Scoring Workbook (CSV format), outreach templates for each tier and channel, the 14-day sequence playbooks, and the tech stack implementation blueprint as separate, labeled sections. Each template should be copy-paste ready for import into Apollo, Outreach, or HubSpot sequences.

## Example Input/Output

**Example Input:**

Company: Vertex Analytics (B2B SaaS, $3M ARR, sells revenue intelligence dashboards to VP Revenue/CRO at 50-300 person SaaS companies)

Signals detected for **Acme Cloud** (target account):
1. Pricing page visited 4x in 7 days (Score weight: 9, Day 2)
2. Series B announced: $25M raised (Score weight: 8, Day 0)
3. New VP of Revenue Operations hired (LinkedIn, 3 days ago) (Score weight: 9)
4. Bombora Surge: "revenue intelligence" keyword (Score weight: 7, Day 1)
5. SDR sent cold email, contact opened 5x in 3 days without reply (Score weight: 6)

Contact: Marcus Okonkwo, VP Revenue Operations, hired 3 weeks ago from Salesforce

---

**Example Output:**

**Composite Signal Score: 74** (Tier 4 — AE Direct Pursuit)

**Signal Scoring Breakdown:**
| Signal | Raw Weight | Recency Mult | Confidence | Weighted Score |
|---|---|---|---|---|
| Pricing page 4x | 9 | 0.85 (Day 2) | 1.0 (first-party) | 7.65 |
| Series B $25M | 8 | 1.0 (Day 0) | 0.85 (third-party verified) | 6.80 |
| New VP RevOps | 9 | 0.85 (Day 3) | 0.85 (LinkedIn verified) | 6.50 |
| Bombora Surge | 7 | 1.0 (Day 1) | 0.85 | 5.95 |
| Email opened 5x | 6 | 0.85 | 1.0 | 5.10 |
| **Raw Total** | | | | **32.0** |
| **Normalized (÷40×100)** | | | | **80 → ICP Fit Adj -6 = 74** |

**AE Email — Day 0:**

Subject A: "Marcus — the ops stack question at 3-week mark"
Subject B: "Acme's Series B + RevOps hire + pricing research = interesting timing"

Body:
> Marcus — congrats on the VP RevOps role at Acme. Series B + new ops leader usually means one of two things: cleaning up the attribution mess from growth-at-all-costs, or building the revenue visibility the board now expects.
>
> We helped Lattice's RevOps team cut their "where did this pipeline come from?" calls by 80% in 60 days post-Series B. Happy to share the 3-system architecture they used — no demo pitch, just the model.
>
> Worth 20 minutes this week?

**SDR Internal Briefing:**
- **Why Now:** New VP with 90-day window to prove value + fresh Series B budget = perfect storm
- **Lead with:** Board visibility and attribution clean-up, NOT features
- **DO NOT mention:** Competitor names (risk: he came from Salesforce ecosystem)
- **Best opening:** Reference the pricing page visits + his Salesforce background
- **AE to join Day 5 call** — not a qualification call, a "revenue architecture conversation"

**LinkedIn Connection Note (Day 1):**
> Marcus — saw the VP RevOps announcement at Acme. Big seat, especially post-Series B. I work with RevOps leaders at Series B SaaS on revenue visibility — would love to be a useful resource.

**Day 5 — AE Direct Email:**
> Marcus, [AE Name] here — I lead the team working with Series B revenue leaders. [SDR Name] mentioned you've been exploring revenue intelligence options.
>
> I pulled together the playbook from how three RevOps leaders in your exact situation built their first board-ready revenue model in under 60 days. Attaching the framework — might spark ideas regardless.
>
> I have Thursday at 2pm ET — worth a quick architecture conversation?

## Success Metrics

**Signal Quality:**
- Signal-to-Meeting Conversion Rate by tier: Target >8% for Tier 4-5
- Signal Volume by category: Identify which signal types produce highest-quality pipeline
- Score Accuracy: % of 60+ scored accounts that become opportunities within 90 days (target >25%)

**Outreach Effectiveness:**
- Email Reply Rate by tier: Tier 1: >3%, Tier 2: >6%, Tier 3: >9%, Tier 4: >14%, Tier 5: >20%
- Multi-touch Sequence Completion Rate: What % of sequences run to completion vs. disengage
- Meeting Show Rate: Target >85% (high signal = genuine interest = shows up)

**Revenue Impact:**
- Signal-Sourced Pipeline: % of total pipeline with at least one trigger signal recorded at time of outreach
- Signal-Influenced Revenue: Deals where signal was detected during open opportunity (acceleration)
- Time-to-First-Meeting: Benchmark 14 days → target <7 days for Tier 4-5 accounts

**System Health:**
- Signal Freshness: % of scored accounts with signals updated in last 7 days
- Routing Accuracy: < 5% misrouted accounts (human review catches and corrects)
- Sequence Enrollment Rate: % of newly scored accounts enrolled in appropriate sequence within SLA

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Outbound-Prospecting/Intent-Driven-Account-Prioritization-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Outbound-Prospecting/Multi-Channel-Outbound-Sequence-Orchestrator.md`
- `../../05_Analytics-&-Marketing-Operations/Advanced-Marketing-Intelligence/Behavioral-Personalization-&-Dynamic-Content-Optimization-Engine.md`
- `../../05_Analytics-&-Marketing-Operations/KPI-Dashboard-Creation/Dark-Funnel-Unattributed-Pipeline-Intelligence-Engine.md`

## Integration Tips

**HubSpot:**
- Create custom Contact/Company properties: `signal_composite_score`, `primary_signal`, `signal_detected_date`, `gtm_tier`
- Build Workflows: Property change on `signal_composite_score` → if ≥60 → Create Deal → Assign AE → Send Slack notification to #hot-accounts
- Use `Calculated Properties` for recency-weighted scoring (available in Operations Hub Pro+)
- Report on: `signal_composite_score` at time of Deal Created vs. Deal Won/Lost (reveals predictive power)

**Salesforce:**
- Custom Fields on Lead/Contact: `Signal_Score__c` (Number), `Signal_Tier__c` (Picklist), `Primary_Signal__c` (Text)
- Process Builder / Flow: Signal score update triggers Task creation + Case owner assignment
- Salesforce Einstein Lead Scoring: Layer signal data on top for combined ML + rules scoring

**Clay.com (Orchestration Layer):**
- Build Clay Tables that aggregate: Clearbit enrichment + Bombora intent + LinkedIn scrape + HubSpot web visits
- Formula columns: compute weighted signal score in real-time
- Use Clay's Webhooks to push scored accounts directly into Outreach sequences or HubSpot
- Schedule nightly runs to refresh firmographic triggers (funding, hires)

**Apollo.io / Outreach.io:**
- Map GTM tiers to Apollo Sequences: Tier 2 → "SDR Signal Sequence," Tier 4 → "AE Direct Sequence"
- Use Apollo's Trigger Enrollment: Auto-enroll when CRM field `gtm_tier` changes
- Tag contacts with signal source for reporting (e.g., "bombora-intent," "pricing-page-visitor")

**n8n / Zapier (Glue Layer):**
- Zapier: Bombora alert email → parse → update HubSpot score + trigger sequence enrollment
- n8n: Build multi-step signal aggregation workflow (free, self-hosted option for startups)
- Webhook: Common Room community signal → n8n → HubSpot → SDR Slack alert

**Sendoso / Reachdesk (Tier 5 Gifting):**
- Automate gift dispatch when HubSpot score hits 80+: Zapier → Sendoso API → gift order created
- Personalization token: Include signal context in gift note ("We saw the Series B news — big milestone")
- Budget alert: Set monthly Sendoso spend cap; require AE approval if account ACV < $30K

## Troubleshooting

**Problem: Signal scores are inflating — everyone looks like a hot account**
Cause: Weights set too high, decay not applied, ICP filter too loose.
Fix: Recalibrate weights by running historical analysis — look at accounts that became closed-won opportunities and reverse-engineer which signals were present. Apply stricter ICP penalty (-30 for ≥2 criteria misses). Add a "noise floor" — require at least 2 different signal categories to score above 40 (prevents a single high-weight signal from triggering premium outreach).

**Problem: SDRs aren't using the routed signals — they're still doing manual list pulls**
Cause: Adoption failure; scoring system exists in CRM but isn't surfaced where reps work.
Fix: Build a "Signal Dashboard" view in Salesforce/HubSpot showing the SDR's top 10 highest-scored accounts daily. Push Slack alerts to each SDR's personal channel (not just a team channel). Make signal-based sequences the DEFAULT — remove access to generic templates. Run a 30-day A/B: signal-triggered outreach vs. manual list, show reply rate difference. Reps adopt what works.

**Problem: Signal detection is delayed by 48-72 hours, making "real-time" outreach impossible**
Cause: Data pipelines running on batch schedules (nightly jobs, weekly Bombora syncs).
Fix: Switch to webhook-based triggers for high-velocity first-party signals (pricing page, demo abandonment) — these must fire in < 15 minutes. For third-party data (Bombora, Clearbit), accept the latency but batch-process at 6am daily so SDRs have fresh signals at start of workday. Priority: fix first-party signal speed first (highest signal quality, fully controllable).

## Version History
- v1.0: Initial creation (auto-generated)
