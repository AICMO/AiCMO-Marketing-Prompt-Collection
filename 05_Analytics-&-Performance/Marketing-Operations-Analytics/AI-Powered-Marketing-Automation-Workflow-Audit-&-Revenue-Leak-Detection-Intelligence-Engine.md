# AI-Powered Marketing Automation Workflow Audit & Revenue Leak Detection Intelligence Engine - Find & Fix the Hidden Revenue Drain in Your Marketing Automation Platform

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** b2b, marketing-ops, automation, hubspot, marketo, pardot, revenue-ops, analytics, crm

## Overview
Conducts a systematic AI-powered audit of your marketing automation platform to uncover broken workflows, zombie contacts, misrouted leads, attribution blind spots, and funnel-stage velocity failures that are silently draining revenue. Use this when pipeline has slowed without obvious cause, before a quarterly business review, after a CRM or MAP migration, or when sales is complaining about lead quality and MQL-to-SAL conversion rates.

## Quick Copy-Paste Version

You are a marketing operations expert and revenue intelligence analyst. Audit my marketing automation platform for revenue leaks and workflow failures.

My setup:
- MAP platform: [HubSpot / Marketo / Pardot / ActiveCampaign / Other]
- CRM: [Salesforce / HubSpot CRM / Other]
- Total contacts in database: [number]
- Active workflows/sequences: [approximate number]
- Monthly MQL volume: [number]
- MQL-to-SAL conversion rate: [%]
- Average sales cycle: [days]
- Last database clean: [date or "never"]

Known symptoms (check all that apply):
- [ ] Pipeline is down but lead volume is steady
- [ ] Sales says MQL quality is poor
- [ ] High unsubscribe rates
- [ ] Contacts entering workflows but not progressing
- [ ] Attribution gaps (can't explain where deals came from)
- [ ] Workflows haven't been reviewed in 6+ months
- [ ] Recent MAP or CRM migration

Please audit and deliver:
1. Top 5 workflow failure points (broken triggers, wrong branch logic, dead ends)
2. Contact database health score — estimate % of contacts that are zombie/disengaged
3. Revenue leak estimate — how much pipeline value is being lost to automation failures
4. Funnel velocity breakdown — where contacts are getting stuck and average dwell time per stage
5. Attribution gaps — which conversion events are untracked or mis-attributed
6. Quick wins list — the 10 fixes that will recover the most revenue in under 2 hours each
7. 30-day remediation roadmap — prioritized by estimated revenue impact

Show me the reasoning behind each finding. Flag where you're estimating vs. calculating from data I provided.

## Advanced Customizable Version

ROLE: You are a senior marketing operations architect and revenue intelligence analyst with 12+ years auditing marketing automation platforms for B2B SaaS, enterprise software, and mid-market companies. You specialize in diagnosing MAP-CRM integration failures, funnel velocity analysis, and quantifying the revenue impact of automation breakdowns. You apply systematic diagnostic frameworks — not generic best-practice lists — and every recommendation maps to a dollar value.

COMPANY CONTEXT:
- Company: [Company Name]
- Industry: [B2B SaaS / Enterprise Software / Manufacturing / Professional Services / Other]
- Stage: [Startup / Growth / Scale / Mature]
- Annual revenue: [$X]
- Marketing team size: [number]
- Sales team size: [number, AEs + SDRs]
- Average contract value (ACV): [$X]
- Sales cycle length: [X days average]

MARKETING TECHNOLOGY STACK:
- Marketing Automation Platform (MAP): [HubSpot / Marketo Engage / Adobe Marketo / Pardot/MCAE / ActiveCampaign / Eloqua / Other]
  - MAP version/tier: [e.g., HubSpot Marketing Hub Enterprise]
  - In production since: [year]
  - Last major configuration review: [date or "never"]
- CRM: [Salesforce / HubSpot CRM / Microsoft Dynamics / Other]
  - MAP↔CRM sync method: [native / Zapier / custom / unknown]
  - Sync direction: [bidirectional / MAP→CRM only / CRM→MAP only]
- Intent data platforms: [6sense / Bombora / G2 / ZoomInfo / None]
- Enrichment tools: [Clearbit / Cognism / Apollo / None]
- Tracking/analytics: [GA4 / Segment / Heap / RudderStack / Other]
- Chat/conversational: [Drift / Intercom / qualified.com / None]

DATABASE HEALTH (provide what you have; estimate where you don't):
- Total contacts: [number]
  - Marketing-contactable: [number or %]
  - Unsubscribed: [number or %]
  - Hard bounced: [number or %]
  - No engagement in 12+ months: [number or % — estimate if unknown]
  - No email, phone, or company: [number or %]
- Lead sources (top 3 by volume): [e.g., "Organic Search 40%, Events 25%, Outbound 20%"]
- Database growth rate: [X new contacts/month]
- Last list clean/suppression update: [date]

WORKFLOW INVENTORY (describe your MAP's current state):
Active workflows (approximate count by type):
- Lead nurture sequences: [number] | Avg enrollment/month: [number]
- Lead scoring rules: [number of scoring actions] | MQL threshold: [score]
- Lifecycle stage transitions: [describe: e.g., "MQL → SAL triggered when score > 80"]
- Re-engagement / winback: [number] | Last updated: [date]
- Alert / sales notification workflows: [number]
- Post-conversion / onboarding: [number]
- Operational (data sync, field updates): [number]
- Total estimated active workflows: [number]
- Estimated dormant/untouched workflows (>6 months): [number or %]

FUNNEL PERFORMANCE DATA (provide last 90 days if available):
| Stage | Volume | Avg Days in Stage | Conversion to Next Stage |
|-------|--------|-------------------|--------------------------|
| New Lead → MQL | [X] leads | [X days] | [X%] |
| MQL → SAL/SQL | [X] MQLs | [X days] | [X%] |
| SQL → Opportunity | [X] SQLs | [X days] | [X%] |
| Opportunity → Closed Won | [X] opps | [X days] | [X%] |

KNOWN PAIN POINTS (describe any symptoms you're experiencing):
[Describe: e.g., "Sales says leads are cold when they receive them, MQL-to-SAL rate dropped from 28% to 14% over the last quarter, we had a Salesforce migration 4 months ago that we never fully QA'd, 30% of our workflows haven't been touched in over a year"]

---

## AUDIT FRAMEWORK — EXECUTE IN ORDER:

### MODULE 1: Workflow Integrity Audit

For each workflow category, identify failure patterns:

**1A — Trigger Failures**
- Enrollment triggers that are too broad (capturing wrong audience)
- Enrollment triggers that are too narrow (missing qualified contacts)
- Triggers dependent on fields that are frequently blank or inconsistently populated
- Date-based triggers that have expired or reference past events
- Workflows triggered by events that no longer exist (deleted forms, deprecated UTMs, sunset pages)

**1B — Branch Logic Failures**
- IF/THEN branches with conditions that are never true (dead branches)
- Branches dependent on field values that are never set
- Mutually exclusive conditions that leave contacts in limbo
- A/B test branches where the losing variant was never turned off
- Branches that direct contacts to sequences that no longer exist

**1C — Exit and Goal Failures**
- Workflows with no exit criteria (contacts enrolled indefinitely)
- Goal completions that fire too early, removing contacts before sequence completes
- Workflows with goals that can never be achieved given the enrollment criteria
- Missing suppression lists (e.g., existing customers enrolled in new-business nurtures)

**1D — Timing and Sequence Failures**
- Sequences with unrealistic wait times (24-hour gaps in enterprise nurtures, week-long gaps in trial onboarding)
- Sequences where contacts time out before receiving key conversion messages
- Overlapping sequences sending conflicting messages to the same contact simultaneously
- High-frequency sequences causing list fatigue and unsubscribes

Audit Output Format for Module 1:
| Workflow Name | Type | Last Modified | Enrollment/Month | Issue Category | Severity (High/Med/Low) | Revenue Impact Estimate | Recommended Fix |
|---------------|------|---------------|-----------------|----------------|------------------------|------------------------|-----------------|

### MODULE 2: Contact Database Health & Zombie Detection

**2A — Engagement Decay Analysis**
Segment the database into health tiers:
- Tier 1 — Active (opened/clicked in last 90 days): estimate %
- Tier 2 — Dormant (90–365 days since last engagement): estimate % and revenue opportunity if reactivated
- Tier 3 — Zombie (365+ days no engagement, never converted): estimate % and recommendation (suppress, segment, or purge)
- Tier 4 — Invalid (bounced, unsubscribed, no valid email): estimate % and cleanup action

**2B — Data Quality Impact on Automation**
Identify fields that, when blank, break automation logic:
- Lead source / UTM fields (blank rate estimate)
- Lead score (contacts that should have scored but didn't)
- Lifecycle stage (contacts stuck at "Subscriber" or "Lead" who should have advanced)
- Industry / company size (segmentation fields blank in estimated X% of records)
- CRM sync fields (fields that MAP reads but CRM doesn't write reliably)

**2C — Duplicate and Shadow Record Analysis**
- Estimate duplicate contact rate (contacts with same email under different records)
- Identify contacts existing in MAP but not CRM (orphaned MAP records)
- Identify contacts in CRM as customers/prospects but still enrolled in top-of-funnel nurtures

Database Health Scorecard:
| Metric | Current Estimate | Benchmark (B2B SaaS) | Gap | Priority |
|--------|-----------------|---------------------|-----|----------|
| Deliverable email rate | | >85% | | |
| Active engagement rate (90-day) | | >25% | | |
| MQL scoring coverage | | >70% | | |
| CRM sync accuracy | | >95% | | |
| Duplicate rate | | <3% | | |

### MODULE 3: Revenue Leak Quantification

Map every identified failure to a pipeline dollar value using this methodology:

**Revenue Leak Formula:**
(Contacts affected by failure) × (Expected conversion rate to MQL) × (MQL→Opp rate) × (Opp→Win rate) × (ACV) = Pipeline leak per period

Apply this formula to each major failure category:

**3A — Routing & Assignment Leaks**
- Leads not routed to sales within SLA (estimate avg response time vs. target)
- Leads routed to the wrong sales rep (wrong territory, wrong segment)
- Leads marked as MQL but never assigned (stuck in queue)
- Inbound leads that entered a nurture instead of being fast-tracked to sales

**3B — Timing & Sequence Leaks**
- Leads that aged past the sales-accepted window (contacted too late)
- Trial/freemium users who never received onboarding emails (activation leak)
- Leads that unsubscribed mid-sequence before receiving key conversion messages

**3C — Attribution Leaks**
- Contacts that converted but were not attributed to any campaign (dark revenue)
- Multi-touch activities (webinar attendance, content downloads) not recording to CRM
- UTM parameters that aren't passing through to lead records
- Offline conversions (event leads, direct sales referrals) with no digital attribution

Revenue Leak Summary Table:
| Leak Category | Contacts Affected | Est. Pipeline at Risk | Confidence Level | Fix Complexity |
|---------------|------------------|----------------------|-----------------|----------------|
| Routing failures | | | | |
| Zombie contacts (dormant) | | | | |
| Broken workflows | | | | |
| Attribution gaps | | | | |
| **Total** | | | | |

### MODULE 4: Funnel Velocity Diagnostic

For each funnel stage, calculate and benchmark:

**4A — Stage Conversion Rate Analysis**
Compare actual conversion rates vs. B2B benchmarks:
- Lead → MQL: [actual %] vs. benchmark 8–15% (varies by lead source)
- MQL → SAL: [actual %] vs. benchmark 20–35% for demand-gen MQLs
- SAL → SQL/Opportunity: [actual %] vs. benchmark 50–70%
- SQL → Closed Won: [actual %] vs. benchmark 20–30%

For any stage converting below benchmark: diagnose whether the cause is:
(a) Qualification bar set too high/low (scoring issue)
(b) Routing failure (timing or assignment)
(c) Content/messaging failure at that stage
(d) Data quality failure (wrong contact, wrong segment)

**4B — Velocity Bottleneck Identification**
Identify the one stage where contacts are spending the most time beyond expected:
- Average days in stage vs. target (from sales cycle modeling)
- % of contacts that "expire" at this stage (no activity for 2x the expected dwell time)
- Top 3 likely causes of the bottleneck
- Automation intervention recommendation to accelerate velocity

**4C — Lead Source Velocity Comparison**
Show conversion rate and velocity for top 3 lead sources:
| Lead Source | MQL Rate | SAL Rate | Opp Rate | Win Rate | Avg Cycle | Blended LTV/CAC |
|-------------|----------|----------|----------|----------|-----------|-----------------|

### MODULE 5: Attribution Gap Analysis

**5A — Coverage Audit**
For each marketing channel, assess attribution completeness:
| Channel | Tracked? | Attribution Model | Gaps Identified | Revenue Blind Spot |
|---------|----------|-------------------|-----------------|-------------------|
| Paid Search | | | | |
| Paid Social | | | | |
| Organic Search | | | | |
| Email / MAP | | | | |
| Events / Webinars | | | | |
| Content Downloads | | | | |
| Partner / Referral | | | | |
| Direct / Dark Social | | | | |

**5B — UTM Governance Assessment**
- % of inbound traffic with no UTM parameters (estimate)
- Inconsistent UTM naming patterns (e.g., "LinkedIn" vs. "linkedin" vs. "LI" as source values)
- Missing campaign-level tracking on top-spending channels
- Recommendation: UTM governance framework with naming convention enforcement

**5C — First-Party Data Signal Capture**
For each intent signal, assess whether it's being captured and actioned:
| Signal | Captured? | Triggers Workflow? | Updates Lead Score? | Alerts Sales? |
|--------|-----------|--------------------|---------------------|---------------|
| Pricing page visit | | | | |
| Case study download | | | | |
| Demo page visit (no request) | | | | |
| Return visit (3rd+ session) | | | | |
| Job change trigger (champion moved) | | | | |
| G2/review site visit (intent data) | | | | |

### MODULE 6: Quick Wins Prioritization Matrix

Produce a prioritized fix list ranked by: (Revenue Impact × Fix Speed) ÷ Implementation Complexity

Format:
| # | Fix Description | Revenue Impact ($) | Time to Fix | Complexity (1-5) | Priority Score | Owner |
|---|----------------|-------------------|-------------|------------------|----------------|-------|
| 1 | | | | | | |
...through top 10

At least 3 of the top 10 must be executable in under 2 hours with no engineering dependencies.

### MODULE 7: 30-Day Remediation Roadmap

Organize fixes into a phased plan:

**Week 1 — Stop the Bleeding (Revenue-critical fixes)**
- Day 1-2: [Fix 1 — highest revenue impact, lowest complexity]
- Day 3-4: [Fix 2]
- Day 5: [Fix 3 — database suppression / routing emergency fix]

**Week 2 — Patch the Leaks (High-impact, medium complexity)**
- [Fix 4-6 — workflow logic corrections, scoring recalibration]

**Week 3 — Optimize Performance (Strategic improvements)**
- [Fix 7-9 — attribution cleanup, UTM governance, sequence optimization]

**Week 4 — Measure & Validate**
- Define success metrics for each fix
- Set up monitoring dashboards
- Schedule 30-day post-fix review

CONSTRAINTS:
- Every fix recommendation must specify the MAP platform steps needed (HubSpot workflow editor / Marketo Smart Campaign / Pardot Engagement Studio)
- Revenue impact estimates must show the calculation, not just a number
- Where data is unknown, provide a diagnostic question the user can answer in their MAP to get the actual number
- Prioritize fixes that don't require engineering resources — marketing ops should be able to implement independently
- Flag any fix that requires CRM admin access or IT support so the user can plan accordingly

OUTPUT FORMAT:
- Executive Summary (150 words): What's broken, estimated revenue at risk, top 3 actions
- Module outputs as labeled sections with tables
- Quick Wins matrix (most important single output)
- 30-day roadmap as a week-by-week action plan
- Appendix: Diagnostic questions to run in your MAP to gather data not provided

## Example Input/Output

**Input Example:**

Company: Meridian Analytics (B2B SaaS, Series B, $11M ARR, $38K ACV, 6-month avg sales cycle)
MAP: HubSpot Marketing Hub Enterprise | CRM: Salesforce
Total contacts: 87,000 | Marketing-contactable: 52,000 | Unsubscribed: 14,000
Active workflows: ~120 (estimate; many haven't been touched since 2022)
Monthly MQL volume: 180 | MQL→SAL rate: 17% (down from 31% 8 months ago)
Symptoms: Sales complaining about cold leads, pipeline down 22% QoQ despite steady MQL volume, Salesforce migration completed 6 months ago, attribution in HubSpot "looks wrong"

---

**Output Example (abbreviated):**

**EXECUTIVE SUMMARY**

Meridian's automation platform has three critical failure points accounting for an estimated $1.8M in at-risk annual pipeline. The Salesforce migration 6 months ago broke bidirectional sync on 11 key lead routing fields, causing 23% of MQLs to route to incorrect sales reps or sit unassigned for 5+ days — well past the industry-standard 5-minute response window. Simultaneously, 34 workflows last modified in 2021-2022 contain dead branch logic referencing deprecated forms and UTM values that no longer exist, enrolling ~400 contacts/month into dead-end sequences. Third, the MQL scoring model awards 20 points for "Pricing Page Visit" but 67% of pricing page traffic isn't being tracked due to a missing HubSpot tracking code on the new website (deployed post-migration). Immediate actions: (1) Fix Salesforce sync on routing fields — 4-hour fix, recovers ~$840K pipeline at risk. (2) Add HubSpot tracking code to pricing page — 30-minute fix, restores intent scoring for 1,200 monthly visitors. (3) Suppress 12,400 zombie contacts (no engagement in 18+ months) to protect sender reputation and improve deliverability.

---

**Revenue Leak Summary (Top Issues)**

| Leak Category | Contacts Affected/Month | Est. Pipeline at Risk (Annual) | Confidence | Fix Complexity |
|---------------|------------------------|-------------------------------|------------|----------------|
| CRM routing field sync break | ~41 MQLs misrouted | $840K | High | Low (4 hrs) |
| Pricing page tracking gap | 1,200 visitors unscored | $480K | Medium | Very Low (30 min) |
| Dead-end workflow enrollments | ~400 contacts/month | $310K | Medium | Medium (1-2 days) |
| Zombie contact deliverability drag | 12,400 contacts | $180K (inbox rate) | Medium | Low (2 hrs) |
| Missing UTM attribution (Paid Social) | ~35% of paid leads | $290K (dark pipeline) | Low | Medium |
| **Total** | | **~$2.1M** | | |

---

**Quick Wins Prioritization Matrix (Top 5)**

| # | Fix | Revenue Impact | Time to Fix | Complexity | Priority |
|---|-----|---------------|-------------|------------|----------|
| 1 | Re-map 11 broken Salesforce sync fields for lead routing | $840K | 4 hrs | 2/5 | 🔴 Critical |
| 2 | Install HubSpot tracking code on pricing page (missing post-migration) | $480K | 30 min | 1/5 | 🔴 Critical |
| 3 | Suppress 12,400 contacts with 18+ months no engagement (protect deliverability) | $180K inbox rate | 2 hrs | 1/5 | 🟠 High |
| 4 | Archive/deactivate 34 workflows with dead branch logic referencing deprecated forms | $310K | 1 day | 3/5 | 🟠 High |
| 5 | Standardize UTM source values across paid social (LinkedIn/LI/linkedin → linkedin) | $290K attribution | 3 hrs | 2/5 | 🟡 Medium |

## Success Metrics

- Revenue leak estimate covers ≥80% of total database contacts analyzed (not just top symptoms)
- Quick Wins matrix identifies at least 3 fixes executable in under 2 hours with no engineering dependency
- Funnel velocity analysis pinpoints the single stage with the largest conversion rate gap vs. benchmark
- Attribution gap table covers all 8+ channels with specific gap identification (not "N/A" responses)
- 30-day roadmap is specific enough to assign to a marketing ops manager with no additional planning required
- Executive summary passes the "CMO test": readable in 60 seconds, answers "what's broken and what do I do first?"

## Related Prompts

- `../../05_Analytics-&-Performance/Marketing-Operations-Analytics/Campaign-Post-Mortem-&-Marketing-Learning-Loop-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Lead-Quality-&-Conversion-Analytics/Marketing-Lead-Quality-&-Sales-Handoff-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Funnel-Conversion-&-Pipeline-Velocity/Pipeline-Stage-Conversion-Optimization-&-Revenue-Leak-Detection-Engine.md`
- `../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md`

## Integration Tips

- **HubSpot:** Run the Workflow Health dashboard (Reports → Workflows) and export enrollment history. Use the "Contacts Timeline" view to trace a sample of recently closed-lost deals backward through their lifecycle stages — this reveals routing and timing failures faster than aggregate reports. Enable the "Goal Not Met" filter in workflow analytics to find sequences where contacts are falling through.
- **Marketo:** Export your Smart List for "Leads in Active Campaigns" and cross-reference against the CRM opportunity stage. Use the Email Performance report filtered by campaign to identify sequences with >5% unsubscribe rates (threshold for immediate review). Marketo's "Marketing Activities" audit log shows which workflows were last edited and by whom.
- **Salesforce:** Build a custom report: Leads/Contacts created in last 90 days × Lead Status × Time to First Activity. Filter for "MQL status" with no CRM owner assigned — this is your routing leak quantification. The "Converted Leads" report with "Lead Source" shows where your attribution is breaking.
- **Google Analytics 4:** Use the "Funnel Exploration" report to trace users from pricing page → demo request. If you see high drop-off rates on form pages, cross-check against MAP contact creation to identify tracking code failures (GA4 seeing traffic that MAP isn't capturing).
- **Zapier/Make:** Build an automation: Weekly → pull HubSpot workflow performance report → flag any workflow with enrollment rate drop >30% week-over-week → post alert to Slack #marketing-ops channel. This early warning system catches broken triggers before they become revenue leaks.
- **Notion/Confluence:** Use Module 7's 30-day roadmap as a live project tracker. Create a "Marketing Automation Health Log" — a running document updated quarterly after each audit cycle — so you can track whether fixes held or degraded over time.
- **Looker Studio / Google Data Studio:** Connect your MAP and CRM data sources to build a live "Revenue Leak Dashboard" showing: routing SLA compliance, workflow health scores, MQL velocity by source, and attribution coverage by channel. Automate weekly screenshots to Slack.

## Troubleshooting

**Problem: "I don't know how many workflows we have or when they were last edited — our MAP is a black box"**
Solution: Start with a workflow inventory export (HubSpot: Settings → Workflows → Export; Marketo: Marketing Activities → Right-click root → Export Tree). Sort by "Last Modified Date" — anything untouched in 12+ months is an audit candidate. You don't need perfect data to start; use the Quick Copy-Paste version to describe symptoms, and the AI will guide you through what diagnostic data to pull from your specific platform.

**Problem: "The revenue impact estimates seem too high — we don't have $2M in at-risk pipeline from automation issues"**
Solution: The estimates use conservative funnel conversion benchmarks. Input your actual MQL→Close rates and ACV to recalibrate. The methodology (contacts affected × conversion rate × ACV) is directionally correct even if specific numbers vary. More importantly: even if the actual at-risk pipeline is 30% of the estimate, the ranking of issues by relative impact is still valid — fix the top 3 items regardless of the absolute number.

**Problem: "Sales says our MQL quality is bad but our scoring model looks fine to me — who's right?"**
Solution: This is the most common marketing-sales misalignment in B2B. Use Module 4C (Lead Source Velocity Comparison) to separate the argument from subjective feelings. Pull MQL-to-Close rates by lead source and lead score bucket from your CRM. If demo requests convert at 3x the rate of content-download MQLs, the scoring model is over-indexing on content engagement and under-weighting buying-intent signals. Show sales the data segmented by source — not aggregate MQL quality — and you'll quickly identify where the real conversion failure is happening.

## Version History
- v1.0: Initial creation (auto-generated)
