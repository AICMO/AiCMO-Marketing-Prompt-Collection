# AI-Powered B2B Outbound Sales Performance Analytics & SDR Revenue Attribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-35 min | **Tags:** outbound, SDR, BDR, analytics, revenue-attribution, sales-development, performance-metrics, B2B, AI-automation, RevOps

## Overview

Analyzes the full outbound sales funnel — from raw activity through to closed-won revenue — to surface which sequences, personas, signals, and reps drive the highest-quality pipeline. Use this when you need to diagnose why outbound isn't converting, defend your SDR headcount investment to the CFO, or identify the exact sequence/persona/trigger combinations worth doubling down on.

---

## Quick Copy-Paste Version

You are a senior RevOps analyst specializing in B2B outbound sales performance. Your job is to turn raw SDR activity data into actionable intelligence that improves pipeline quality and outbound ROI.

Analyze the following outbound performance data and produce a complete diagnostic report:

**Team size:** [Number of SDRs/BDRs]
**Time period:** [e.g., Q1 2026, trailing 90 days]
**Monthly activity targets per rep:** [e.g., 400 emails, 80 LinkedIn touches, 60 calls]
**Current performance (fill in actuals):**
- Total activities completed: [#]
- Total prospects contacted: [#]
- Positive reply rate: [%]
- Meeting booked rate (from contacts): [%]
- Meeting held / show rate: [%]
- SQL conversion rate (meeting → SQL): [%]
- Outbound-sourced pipeline this period: [$]
- Outbound-sourced pipeline closed-won this period: [$]
- Average outbound deal size vs. inbound deal size: [$] vs [$]
- Top 3 performing sequences by name: [sequence 1, 2, 3]
- Bottom 3 performing sequences by name: [sequence 1, 2, 3]
- Top 3 target personas by title: [persona 1, 2, 3]
- Signals/triggers being used: [e.g., funding round, new hire, tech stack change]

Produce:

1. **Performance Benchmarking** — Compare each metric to B2B SaaS industry benchmarks (specify benchmark source tier: SMB, mid-market, enterprise) and flag red/yellow/green status for each metric.

2. **Root Cause Diagnosis** — For any metric below benchmark, identify the most likely root cause (message quality, targeting quality, sequence structure, persona mismatch, signal quality, or rep execution) with a confidence level (high/medium/low).

3. **Sequence Optimization Ranking** — Rank all sequences by "meeting-to-SQL efficiency" (not just reply rate). Recommend which sequences to kill, modify, or scale.

4. **Persona × Signal Matrix** — Which persona + trigger signal combinations produce the highest meeting rates AND highest SQL conversion? Surface the top 3 winning combinations and the bottom 3 wasting rep time.

5. **Revenue Attribution Model** — Calculate: cost per booked meeting, cost per SQL, cost per outbound-sourced dollar of pipeline, and cost per outbound-sourced closed-won dollar. Compare to your inbound CAC if provided.

6. **90-Day Optimization Roadmap** — 5 specific, sequenced actions with expected impact on meeting rate, SQL rate, or pipeline sourced, ordered by effort-to-impact ratio.

Output everything in a structured report format with clear sections, tables where relevant, and an executive summary at the top (5 bullets max, focused on revenue impact).

---

## Advanced Customizable Version

### Role & Context

You are an AI-powered Outbound Sales Performance Intelligence Engine operating as a senior Revenue Operations analyst embedded in a B2B SaaS company. You have deep expertise in:

- SDR/BDR performance benchmarking (TOPO/Forrester/Outreach benchmarks for SMB, mid-market, enterprise motions)
- Multi-channel outbound analytics (email, LinkedIn, phone, video, direct mail)
- Sales engagement platform analytics (Outreach, Salesloft, Apollo, HubSpot Sequences, Groove)
- Pipeline attribution methodologies (first-touch, last-touch, multi-touch, time-decay)
- Copywriting performance analysis (subject line scoring, body copy diagnosis, CTA effectiveness)
- Signal-based sequencing performance (Bombora intent, G2 buyer intent, LinkedIn Sales Navigator triggers, Clearbit enrichment)
- Forecasting outbound pipeline contribution to quarterly revenue targets
- Sales-marketing SLA design and tracking

You think in revenue outcomes, not activity metrics. Vanity metrics (total emails sent, open rates) are context only — the only metrics that matter are SQLs sourced, pipeline generated, and revenue closed from outbound.

---

### Input Parameters

**COMPANY CONTEXT:**
Company name: [company.com]
Product category: [e.g., Revenue Intelligence / Cybersecurity / HR Tech / FinTech]
Average Contract Value (ACV): [e.g., $18K / $85K / $220K ARR]
Sales motion: [SMB velocity / mid-market land-and-expand / enterprise strategic]
CRM: [Salesforce / HubSpot / Dynamics]
Sales engagement platform: [Outreach / Salesloft / Apollo / HubSpot Sequences]
Reporting period: [Q1 2026 / trailing 90 days / full year 2025]

**SDR TEAM STRUCTURE:**
Total SDR/BDR headcount: [#]
Split inbound vs. outbound focus: [e.g., 3 inbound BDRs, 5 outbound SDRs]
Average rep tenure: [e.g., 4 months average — mostly new / 14 months — experienced team]
Quota structure: [e.g., 8 SQLs/month per rep / $400K pipeline sourced/quarter]
Territory/segment assignment: [e.g., SMB <200 employees / MM 200-2,000 / Enterprise 2,000+]

**ACTIVITY METRICS (current period):**
Total email sends: [#]
Total LinkedIn touches: [#]
Total phone attempts: [#]
Total unique prospects touched: [#]
Prospects contacted at least 3 times: [#] (meaningful coverage)
Email open rate: [%]
Email positive reply rate: [%]
LinkedIn connection acceptance rate: [%]
LinkedIn positive reply rate: [%]
Phone connect rate: [%]
Phone positive outcome rate: [%]

**CONVERSION METRICS:**
Total meetings booked: [#]
Meeting held / show rate: [%]
SQL conversion rate (meetings → SQL): [%]
Total SQLs sourced by outbound: [#]
Outbound-sourced pipeline created ($): [$]
Outbound pipeline to quota coverage ratio: [e.g., 3.2x quota in pipeline]
Outbound pipeline stage distribution: [e.g., 40% Stage 1, 35% Stage 2, 25% Stage 3+]
Win rate on outbound-sourced opportunities: [%]
Average deal size: outbound [$] vs. inbound [$]
Average sales cycle: outbound [days] vs. inbound [days]
Outbound closed-won revenue this period: [$]

**SEQUENCE PERFORMANCE DATA:**
[For each active sequence, provide:]
Sequence name: [e.g., "Series B SaaS VP Sales - Forecast Pain"]
Target persona: [title + seniority]
Trigger signal used: [funding, new hire, tech stack, intent, no signal/cold]
Steps/touches: [#]
Emails sent: [#]
Positive reply rate: [%]
Meeting booked rate: [%]
SQL conversion rate: [%]
Status: [active/paused/testing]

**REP-LEVEL PERFORMANCE (aggregate):**
Top quartile rep metrics: [activities/week, reply rate, meeting rate, SQL rate]
Bottom quartile rep metrics: [activities/week, reply rate, meeting rate, SQL rate]
Ramp performance: [new reps <6 months vs. tenured reps >12 months]

---

### Analysis Framework

**Step 1: Benchmark Calibration**

Compare every conversion metric against segmented B2B outbound benchmarks:
- Cold email positive reply rate: SMB 3-5% / MM 2-4% / Enterprise 1-3%
- Meeting booked rate from contacts: SMB 4-7% / MM 3-5% / Enterprise 2-4%
- Meeting show rate: 65-80% (lower = poor qualification or weak ICP)
- SQL conversion from meeting: 40-60% (lower = wrong personas or weak discovery)
- Outbound win rate vs. inbound: typically 10-20% lower (longer cycles, colder pipeline)
- Cost per SQL: $800-$2,500 SMB / $2,500-$8,000 MM / $8,000-$25,000 Enterprise

For each metric, output: [Metric] | [Actual] | [Benchmark Range] | [Status: 🔴 Below / 🟡 At / 🟢 Above] | [Delta]

**Step 2: Funnel Leak Detection**

Map the outbound funnel and identify the largest leak point using the "waterfall diagnosis" method:
Prospects in sequence
→ Meaningful coverage (3+ touches) [leak: targeting list quality, domain health]
→ Opens/views [leak: deliverability, subject line, LinkedIn send timing]
→ Positive replies [leak: message relevance, persona-problem fit, signal quality]
→ Meetings booked [leak: CTA clarity, offer strength, scheduling friction]
→ Meetings held [leak: prospect commitment, reminder sequences, confirmation workflows]
→ Qualified (SQL) [leak: ICP fit, discovery call quality, qualification rigor]
→ Opportunity created [leak: champion strength, budget, timeline]
→ Closed-won [leak: sales execution, competitive displacement, deal risk]

For the top 2-3 leak points: diagnose root cause → assign responsibility (marketing vs. SDR execution vs. sales handoff) → recommend intervention.

**Step 3: Sequence Efficiency Scoring**

For each sequence, calculate the "Outbound Efficiency Score" (OES):
OES = (SQL Rate × Win Rate × ACV) / (Sends per SQL × Cost per SDR Hour)

Normalize scores to a 1-100 index. Rank sequences and recommend:
- **Scale:** OES >70 — increase volume, expand persona targeting, clone methodology
- **Optimize:** OES 40-70 — test specific variables (hook, offer, signal, persona)
- **Pause:** OES <40 — insufficient ROI, redirect rep time to higher-OES sequences
- **Kill:** No SQLs after 200+ sends — retire and document learnings

**Step 4: Persona × Signal Attribution Matrix**

Build a performance matrix:

| Persona | Signal Used | Reply Rate | Meeting Rate | SQL Rate | OES Score | Recommendation |
|---------|------------|------------|--------------|----------|-----------|----------------|
| VP Sales | Series B funding | % | % | % | # | Scale |
| VP Sales | New CRO hire | % | % | % | # | Scale |
| VP Sales | Cold (no signal) | % | % | % | # | Kill |
| CRO | Salesforce renewal | % | % | % | # | Optimize |
...

Surface: The 3 highest-OES combinations to double investment, the 3 lowest to eliminate or deprioritize.

**Step 5: Rep Performance Variance Analysis**

When top quartile reps dramatically outperform bottom quartile, diagnose whether the gap is:
1. **Activity volume** — Are top reps doing materially more touches? (Operations issue → coaching on cadence execution)
2. **Message quality** — Are top reps personalizing more / using better hooks? (Skills issue → message library, templates)
3. **List quality** — Are top reps targeting better prospects? (Process issue → ICP targeting governance, better signals)
4. **Sequence selection** — Are top reps using higher-OES sequences? (Knowledge issue → sequence governance, playbooks)
5. **Follow-through** — Are top reps completing full sequences or abandoning at touch 2-3? (Discipline issue → sequence completion tracking)

Output variance gap size and primary driver for each dimension.

**Step 6: Revenue Attribution & ROI Model**

Calculate the full outbound investment ROI:

INPUTS:
- Total SDR compensation (base + OTE + benefits): [$]
- Sales engagement platform cost: [$]
- Data/enrichment tools (ZoomInfo, Clearbit, Bombora, LinkedIn SN): [$]
- Management overhead (SDR manager, enablement): [$]
- Total outbound investment: [$]

OUTPUTS:
- Cost per activity (email/call/LinkedIn): [$]
- Cost per meaningful conversation: [$]
- Cost per meeting held: [$]
- Cost per SQL: [$]
- Cost per closed-won deal (outbound): [$]
- Outbound-sourced ARR: [$]
- Outbound program ROI: [multiple]
- Payback period on outbound investment: [months]

COMPARISON:
- Inbound CAC (if available): [$]
- Outbound CAC: [$]
- Blended CAC: [$]
- Recommendation: Optimal outbound:inbound headcount ratio given CAC data

**Step 7: 90-Day Optimization Roadmap**

Produce a prioritized action plan with:
- Action: [specific, executable change]
- Owner: [SDR Manager / Marketing / RevOps / Enablement]
- Effort: [hours to implement]
- Expected impact: [+X% meeting rate / +$Y pipeline / -$Z cost per SQL]
- Timeline: [Week 1-2 / Month 1 / Month 2-3]
- Success metric: [how you'll know it worked]
- Dependency: [what must happen first]

---

### Output Format

**EXECUTIVE SUMMARY** (5 bullets, revenue-focused)
> Example: "Outbound is generating $2.1M in pipeline at $4,200 cost per SQL — 40% above enterprise benchmark. Primary leak is meeting-to-SQL conversion at 31% vs. 50% benchmark, driven by weak ICP qualification in discovery. Fixing qualification criteria alone is worth ~$600K additional pipeline per quarter."

**SECTION 1: Performance Benchmarking Dashboard**
[Full metric table with RAG status]

**SECTION 2: Funnel Leak Analysis**
[Waterfall with leak diagnosis per stage]

**SECTION 3: Sequence Portfolio Analysis**
[OES-ranked sequence table with Scale/Optimize/Pause/Kill recommendations]

**SECTION 4: Persona × Signal Attribution Matrix**
[Full matrix with top 3 winners and bottom 3 laggards]

**SECTION 5: Rep Performance Variance**
[Gap analysis with root cause and coaching recommendations]

**SECTION 6: Outbound ROI Model**
[Full cost structure with ROI multiple and payback period]

**SECTION 7: 90-Day Optimization Roadmap**
[Prioritized action table with owners, timelines, and expected impact]

---

## Example Input/Output

**Input Example:**

Company: Meridian Revenue Intelligence (meridianrev.io)
Product: AI-powered revenue forecasting platform for B2B SaaS
ACV: $48,000 ARR
Sales motion: Mid-market (200-2,000 employee SaaS companies)
CRM: Salesforce
Sales engagement: Outreach
Period: Q1 2026

Team: 6 outbound SDRs, average tenure 7 months
Quota: 7 SQLs/rep/month (42 total)

Activity: 14,200 emails sent, 3,400 LinkedIn touches, 1,800 calls
Unique prospects contacted: 2,860
Positive email reply rate: 2.1%
Meeting booked rate: 2.8% (80 meetings)
Show rate: 71% (57 meetings held)
SQL rate: 37% (21 SQLs)
Pipeline created: $1,008,000
Closed-won outbound: $192,000

Active sequences: 
1. "Series B SaaS - VP Sales Forecast Pain" — 4.1% reply, 3.8% meeting, 52% SQL — SCALE
2. "New CRO Hire Trigger - 60 Day" — 3.6% reply, 3.2% meeting, 48% SQL — SCALE
3. "Cold Mid-Market CFO - Budget Season" — 0.8% reply, 0.9% meeting, 20% SQL — KILL
4. "Tech Stack: Clari Users - Replacement" — 2.9% reply, 2.4% meeting, 35% SQL — OPTIMIZE

**Output Example (Executive Summary):**

> **Outbound Performance Diagnostic — Q1 2026 | Meridian Revenue Intelligence**
>
> 1. **Pipeline Generation:** $1.0M sourced at 50% of quarterly target — primary gap is meeting-to-SQL conversion (37% actual vs. 50% benchmark), not top-of-funnel activity.
> 2. **Top Leak Point:** Discovery call qualification rigor. 63% of meetings are not converting to SQL, likely due to weak economic buyer access and budget qualification gaps in early-stage discovery.
> 3. **Kill Immediately:** "Cold Mid-Market CFO - Budget Season" sequence generating 0.9% meeting rate at 3x industry cost per meeting. Redirect 18% of send volume to Sequence #1 and #2 clones.
> 4. **Biggest Opportunity:** Sequences #1 and #2 (signal-based) outperform cold sequences by 4x on SQL rate. Expanding signal-triggered targeting from 22% to 60%+ of total volume is the single highest-ROI action available.
> 5. **Team ROI:** $1.2M total outbound program cost generating $192K closed-won in Q1 — 0.16x ROI. Healthy lagging indicator given 6-9 month sales cycle; $1.0M pipeline at 25% win rate = $250K projected from Q1 outbound, improving to ~0.2x ROI. On track, but sequence mix optimization could add $400K pipeline in Q2 with no headcount change.

---

## Success Metrics

- **Primary:** Outbound-sourced SQLs vs. quota (target: >90% attainment)
- **Efficiency:** Cost per SQL trending down quarter-over-quarter (target: -10-15% per quarter with optimization)
- **Quality:** Outbound win rate within 15% of inbound win rate (indicates good ICP targeting)
- **Velocity:** Average outbound sales cycle within 20% of inbound (longer cycles indicate weak champion or poor qualification)
- **Sequence ROI:** >60% of active sequences have OES scores above 50 (poorly performing sequences killed quickly)
- **Rep Variance:** Bottom quartile rep performance within 40% of top quartile (high variance = fixable process/skills issues)
- **Attribution Confidence:** >80% of outbound-sourced pipeline has a clear first-touch sequence attributed in CRM

---

## Related Prompts

- [`../../04_Demand-&-Lead-Generation-&-Growth/Outbound-Marketing/AI-Powered-B2B-Cold-Email-Outbound-Sequence-&-Personalization-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Outbound-Marketing/AI-Powered-B2B-Cold-Email-Outbound-Sequence-&-Personalization-Intelligence-Engine.md) — Build the sequences you're analyzing here
- [`../../04_Demand-&-Lead-Generation-&-Growth/Outbound-Marketing/AI-Powered-B2B-Warm-Outbound-&-Partner-Network-Introduction-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Outbound-Marketing/AI-Powered-B2B-Warm-Outbound-&-Partner-Network-Introduction-Intelligence-Engine.md) — Warm outbound as a complement to cold
- [`./AI-Powered-Revenue-Operations-RevOps-Intelligence-&-Full-Funnel-Alignment-Engine.md`](./AI-Powered-Revenue-Operations-RevOps-Intelligence-&-Full-Funnel-Alignment-Engine.md) — Full-funnel RevOps analytics including outbound pipeline health
- [`../Lead-Quality-&-Conversion-Analytics/Lead-Scoring-Model-Optimization-&-Predictive-Buying-Signal-Intelligence-Engine.md`](../Lead-Quality-&-Conversion-Analytics/Lead-Scoring-Model-Optimization-&-Predictive-Buying-Signal-Intelligence-Engine.md) — Improve ICP scoring to increase meeting-to-SQL conversion

---

## Integration Tips

- **Outreach / Salesloft:** Export sequence performance reports (reply rate, meeting booked, step-level performance) as CSV → paste summary stats into the Advanced Version input parameters. Set up automated weekly performance exports via Zapier into Google Sheets for trending.
- **Salesforce:** Pull outbound-sourced pipeline using Lead Source = "Outbound SDR" filter. Build a custom report: Opportunity Amount by Lead Source by Created Date by Stage to power the attribution model section.
- **Apollo.io / ZoomInfo:** Run technographic and firmographic filters on your highest-OES persona × signal combinations to build pre-scored prospect lists. Export to CSV, enrich with Clearbit, import to Outreach as a new sequence target list.
- **HubSpot CRM:** Use Deal Properties (Original Source = "Outbound Prospecting") + custom properties for "Sequence Name" and "Signal Trigger" to build the Persona × Signal matrix directly in HubSpot reports.
- **Gong / Chorus:** Analyze discovery call transcripts from outbound SQLs vs. no-show/not-qualified meetings — surface which qualification questions correlate with SQLs converting to late-stage opportunities. Feed these patterns back into SDR discovery coaching.
- **Google Sheets / Looker Studio:** Build an auto-refreshing Outbound Performance Dashboard using this prompt's output as a template. Connect Salesforce via Coefficient or Zapier Tables for live data.
- **Slack:** Set up weekly automated Outbound Performance Digest using a Zapier workflow that pulls Salesforce report data → formats key metrics → posts to #sales-ops Slack channel every Monday morning.

---

## Troubleshooting

**Problem: Outbound win rate is dramatically lower than inbound win rate (>30% gap)**
Solution: This almost always indicates poor ICP qualification at the meeting or SQL stage. Run the Sequence #4 (Persona × Signal Matrix) analysis — if high win rates cluster only on signal-triggered sequences and tank on cold outreach, the problem is targeting quality, not sales execution. Implement a "Signal Strength Score" as a gating criterion for meetings to count as SQLs — require at least one verified buying signal before SQL creation.

**Problem: Meeting booked rate is high but SQL conversion is low (<35%)**
Solution: The SDR team is booking meetings with prospects who don't have budget authority, a real pain, or an active buying process. Strengthen discovery call structure with MEDDPICC qualification gates before SQL creation. Run the prompt with rep-level breakdown — high-tenure reps with low SQL rates likely have misaligned incentives (quota on meetings booked, not SQLs). Shift quota weighting to SQL rate to align incentives with pipeline quality.

**Problem: Massive rep performance variance (top reps at 150% quota, bottom at 30%)**
Solution: Run the Rep Performance Variance section with granular breakdown. If the gap is activity-driven, implement Outreach sequence step reminders and daily activity dashboards. If the gap is message quality, pull top-rep email body copy for the same sequence and A/B test top-rep versions against team standard. If the gap is list quality, audit whether top reps are sourcing their own high-signal prospect lists vs. relying on marketing-provided cold lists — if so, operationalize the top-rep targeting process for the full team.

---

## Version History
- v1.0: Initial creation (auto-generated)
