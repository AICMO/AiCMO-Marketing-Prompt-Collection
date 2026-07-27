# AI-Powered B2B SaaS Marketing-to-Sales Handoff Architecture & Revenue SLA Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** marketing-operations, lead-handoff, sla, mql-sql, revenue-alignment, b2b-saas, pipeline-quality, marketing-sales-alignment, lead-scoring, revenue-ops

## Overview
This prompt engineers a complete marketing-to-sales handoff system — defining MQL/SAL/SQL thresholds, SLA agreements, automated handoff workflows, rejection feedback loops, and pipeline quality accountability — so revenue teams stop arguing about lead quality and start closing more deals.

## Quick Copy-Paste Version

You are a senior Revenue Operations architect with 12+ years designing marketing-to-sales handoff systems for B2B SaaS companies.

Design a complete MQL-to-SQL handoff architecture for [Company Name], a [product description] selling to [ICP — e.g., "Director-level+ at 200-2,000 employee companies in financial services"]:

CURRENT SITUATION:
- Monthly MQL volume: [X]
- Current MQL-to-SQL conversion rate: [X%]
- Average time from MQL to first sales contact: [X hours/days]
- Sales rejection rate (MQLs rejected by sales): [X%]
- Top rejection reasons from sales: [list top 3]
- Current lead scoring model: [describe or "none"]
- CRM: [HubSpot / Salesforce / other]
- Marketing automation: [Marketo / HubSpot / Pardot / other]

DEAL CONTEXT:
- Average contract value (ACV): $[X]
- Typical sales cycle: [X days]
- Number of SDRs/BDRs: [X]
- Number of AEs: [X]
- Current pipeline coverage ratio: [X:1]

Design and deliver:
1. MQL DEFINITION: Exact behavioral + demographic scoring model with point thresholds (minimum 150-point scale)
2. SAL/SQL CRITERIA: Stage-by-stage qualification gates using BANT/MEDDPICC components
3. SLA FRAMEWORK: Response time commitments by lead tier (Tier 1/2/3) with escalation triggers
4. HANDOFF WORKFLOW: Step-by-step automated sequence from MQL creation to sales acceptance
5. REJECTION PROTOCOL: Structured feedback form + automated recycle/nurture routing by rejection reason
6. FEEDBACK LOOP: Weekly marketing-sales alignment cadence with specific metrics and accountability owners
7. REVENUE IMPACT MODEL: Expected pipeline yield improvement at current MQL volume with conservative/target/stretch scenarios

## Advanced Customizable Version

ROLE: You are a Principal Revenue Operations Architect specializing in B2B SaaS marketing-to-sales alignment systems. You combine Sirius Decisions Demand Waterfall methodology, MEDDPICC qualification frameworks, behavioral economics (loss aversion in sales motivation), and process automation design to build handoff architectures that eliminate revenue leakage between marketing and sales. Your systems have generated $400M+ in attributable pipeline across 15+ B2B SaaS companies.

COMPANY CONTEXT:
- Company: [Company Name]
- Stage: [Seed / Series A / Series B / Series C / Growth / Public]
- ARR: $[X]M
- ARR growth target: [X%] YoY
- Product: [1-sentence description]
- Primary ICP: [Exact title, company size, industry, tech stack]
- Secondary ICP segments: [List 2-3 additional target segments with distinct characteristics]
- GTM motion: [Sales-led / PLG + sales / product-led]
- Deal complexity: [Transactional <$25K / Mid-market $25K-$100K / Enterprise $100K+]

CURRENT FUNNEL STATE:
Provide all available data:

Volume Metrics:
- Monthly MQL volume: [X] (definition: [describe current MQL definition])
- MQL-to-SAL rate: [X%] (SAL = Sales Accepted Lead)
- SAL-to-SQL rate: [X%] (SQL = Sales Qualified Lead)
- SQL-to-Opportunity rate: [X%]
- Opportunity-to-Close rate: [X%]
- MQL-to-Close rate (full funnel): [X%]

Quality Metrics:
- Average MQL score at handoff: [X/150]
- Sales rejection rate: [X%]
- Top 5 rejection reasons (ranked by frequency): [list]
- Average time MQL sits before first contact: [X hours]
- Show rate on SDR-booked meetings: [X%]
- Average discovery-to-demo conversion: [X%]

Revenue Attribution:
- % of closed-won deals with marketing touch: [X%]
- % of pipeline sourced vs. marketing-influenced: [X% sourced / X% influenced]
- Marketing's contribution to pipeline coverage: [$XM of $XM target = X:1 coverage]

TEAM STRUCTURE:
- Marketing Ops headcount: [X FTEs] — [describe responsibilities]
- SDR/BDR team: [X reps] — [describe territories/segments]
- AE team: [X reps] — [describe segments, quotas]
- RevOps/Sales Ops: [X FTEs or "none"]
- CRM admin: [X person / shared resource]

TECHNOLOGY STACK:
- CRM: [Salesforce / HubSpot / other] — version/tier: [X]
- Marketing automation: [Marketo / HubSpot / Pardot / Eloqua / other]
- Lead enrichment: [Clearbit / ZoomInfo / Apollo / 6sense / other]
- Intent data: [6sense / Bombora / G2 Buyer Intent / none]
- Sales engagement: [Outreach / Salesloft / Apollo / HubSpot Sequences / other]
- Chat/conversational: [Drift / Intercom / Qualified / none]
- Routing: [LeanData / Chili Piper / native CRM / none]

CURRENT PAIN POINTS (mark all that apply and add detail):
- [ ] Sales ignores marketing MQLs — [describe: % ignored, how measured]
- [ ] No agreed MQL definition — [describe: who owns definition, when last updated]
- [ ] Slow follow-up destroys conversion — [describe: current avg response time vs. benchmark]
- [ ] Marketing-sales attribution dispute — [describe: what each team claims]
- [ ] No rejection feedback mechanism — [describe: how rejections are currently logged]
- [ ] Recycled leads get re-MQLed without changes — [describe: how recycling currently works]
- [ ] Pipeline quality declining over time — [describe: trend data if available]
- [ ] SDRs cherry-pick best leads — [describe: how leads are assigned]

---

DELIVERABLE 1: LEAD SCORING ARCHITECTURE

Design a 150-point lead scoring model with two components:

A. DEMOGRAPHIC / FIRMOGRAPHIC FIT SCORE (70 points max):
Score each attribute with clear point values and disqualification triggers:

Tier 1 Attributes (ICP Core Match — 40 points):
- Job title/seniority match: [point breakdown by title level]
- Company size match: [point breakdown by employee range]
- Industry vertical match: [point breakdown by ICP industry fit]
- Technology stack match: [point breakdown by relevant tools detected]

Tier 2 Attributes (ICP Enhancement — 20 points):
- Geography: [point breakdown]
- Revenue/funding stage: [point breakdown]
- Growth signals (hiring, funding, expansion): [point breakdown]

Disqualification Criteria (negative scoring):
- Auto-disqualify triggers: [list hard disqualifiers — competitors, students, wrong geography, etc.]
- Negative score attributes: [-5 to -20 points for soft disqualifiers]

B. BEHAVIORAL / INTENT SCORE (80 points max):
Design decay-adjusted behavioral scoring:

High-Intent Actions (30-40 points each, 7-day decay):
- Pricing page visit: [X points, decay schedule]
- Demo request form abandonment: [X points, decay schedule]
- ROI calculator completion: [X points]
- Competitor comparison page: [X points]
- Free trial signup: [X points]

Medium-Intent Actions (10-20 points each, 14-day decay):
- Case study download: [X points by ICP relevance]
- Webinar attendance: [X points — live vs. on-demand]
- Product page visit (3+ times in 7 days): [X points]
- Email sequence engagement (opened 3 of last 5): [X points]
- Blog visit (5+ pages in session): [X points]

Low-Intent Engagement (2-5 points each, 30-day decay):
- Newsletter open: [X points]
- Single blog post: [X points]
- Social media click: [X points]

Intent Data Multipliers (when 3rd-party intent available):
- Active buying intent signal from 6sense/Bombora: multiply behavioral score by 1.5x
- Category intent (researching your category): multiply by 1.25x

MQL THRESHOLD LOGIC:
- MQL Trigger: Demographic fit score ≥ [X] AND behavioral score ≥ [X] AND total ≥ [X]
- Exception rule: Fit score ≥ [X] + ANY high-intent action = immediate MQL regardless of total
- Exclusion override: Auto-MQL for specific triggers regardless of score (e.g., demo request, pricing inquiry, chat with intent keywords)

---

DELIVERABLE 2: LEAD TIER CLASSIFICATION & SLA FRAMEWORK

TIER DEFINITION:

Tier 1 — Hot (Top 20% of MQLs by score + ICP fit):
- Score criteria: [X+ total, X+ fit, X+ behavioral]
- Business signals: [specific company trigger events — funding, exec hire, competitor churn]
- SLA: First contact within [X] business hours of MQL creation
- Assignment: Direct to AE (skip SDR qualification for highest tier) OR top-performing SDR
- Follow-up sequence: [X] touches over [X] days via [channels]

Tier 2 — Warm (Next 40%):
- Score criteria: [X-X total score range]
- SLA: First contact within [X] business hours
- Assignment: SDR queue by territory/segment
- Follow-up sequence: [X] touches over [X] days

Tier 3 — Qualified (Remaining 40%):
- Score criteria: [meets MQL threshold, lower fit or behavioral score]
- SLA: First contact within [X] business days
- Assignment: Automated nurture with SDR outreach on day [X]
- Follow-up sequence: [X] touches over [X] days, heavier email/LinkedIn

ESCALATION TRIGGERS (auto-escalate to higher tier):
- Pricing page visit after initial contact: escalate to next tier
- Inbound chat with intent keywords: instant Tier 1
- Executive sponsor identified in buying committee: escalate + notify AE
- Competitor contract end date identified: immediate AE assignment

SLA BREACH RESPONSE:
- Tier 1 breach at +30 min: auto-alert SDR manager via Slack
- Tier 1 breach at +2 hours: auto-escalate to AE with override flag
- Tier 2 breach at +4 hours: manager notification
- Daily SLA breach report: auto-generated and sent to RevOps + Marketing Ops + SDR manager

---

DELIVERABLE 3: HANDOFF WORKFLOW AUTOMATION

MAP THE AUTOMATED SEQUENCE:

Step 1 — MQL Creation (T+0):
- System trigger: [what creates the MQL status change in CRM]
- Auto-enrichment: [enrichment tool pulls missing firmographic data]
- Deduplication check: [merge rules if contact already exists]
- Account matching: [match to existing account or create new]
- Tier classification: [automated score calculation → tier assignment]

Step 2 — Routing (T+0 to T+5 min):
- Routing logic: [LeanData/Chili Piper rules by territory, company size, industry]
- Conflict resolution: [what happens if contact is already owned by AE]
- Inbound routing exception: [chat/demo requests route differently]
- Notification: [SDR/AE receives Slack alert + CRM task with priority flag]

Step 3 — First Touch (T+SLA window):
- Required actions before first contact: [research checklist — company news, LinkedIn, tech stack]
- Mandatory personalization elements: [specific details that MUST be referenced]
- Approved first-touch channels: [call + email + LinkedIn simultaneously? Sequence?]
- First-touch script/template: [provide 3-sentence opener formula using prospect's trigger event]

Step 4 — SAL Acceptance (SDR confirms lead is valid):
- SAL criteria: [contact is reachable + meets basic BANT components + willing to have discovery]
- Time limit: SDR must accept or reject within [X] hours of assignment
- Acceptance action: [CRM status update + sequence enrollment + meeting booking link sent]

Step 5 — SQL Qualification (AE confirms opportunity is real):
- SQL criteria: [full MEDDPICC components identified — Metrics, Economic Buyer, Decision Criteria, Decision Process, Identify Pain, Champion, Competition]
- Required fields before SQL: [list mandatory CRM fields that must be populated]
- SQL action: [opportunity created in CRM + revenue stage = Qualify]

---

DELIVERABLE 4: REJECTION PROTOCOL & RECYCLE SYSTEM

REJECTION TAXONOMY (design structured rejection reasons):

Quality Rejections (marketing accountability):
- "Wrong ICP": [auto-route to nurture stream X, remove from active scoring]
- "Bad contact data": [send back to enrichment, flag data source]
- "No budget authority": [route to lower-tier nurture, attempt to identify economic buyer]
- "Already a customer": [route to customer success, flag marketing data issue]

Timing Rejections (not marketing's fault — recyclable):
- "Not in-market now": [hold in nurture for X days, re-surface on next intent signal]
- "Evaluating in [X] months": [create future date task, lower-intent nurture sequence]
- "No budget until next fiscal year": [date-based re-engagement trigger]

Process Rejections (RevOps accountability):
- "No response after X touches": [return to marketing — exhausted outreach]
- "Duplicate lead": [merge records, assign to original owner]

REJECTION WORKFLOW:
1. SDR selects structured rejection reason in CRM (free text not allowed — forces categorization)
2. Rejection triggers automated notification to marketing ops with data appended
3. Marketing ops reviews quality rejections weekly — identifies scoring model issues
4. Recycle routing: [describe logic for each rejection type — immediate nurture vs. hold vs. delete]
5. Re-MQL rules: [what behavioral threshold re-activates recycled lead?]

FEEDBACK LOOP MECHANICS:
- Weekly "Rejection Report": auto-generated from CRM, sent to marketing ops + SDR manager
- Rejection rate by source: shows which marketing channels produce lowest-quality MQLs
- Win-back rate: tracks % of recycled leads that eventually convert to pipeline
- Quarterly scoring model review: marketing ops + RevOps recalibrate thresholds based on 90 days of data

---

DELIVERABLE 5: MARKETING-SALES SLA AGREEMENT (FORMAL DOCUMENT)

Design a one-page SLA including:

MARKETING COMMITS TO:
- MQL volume: [X] MQLs/month by [date] with [X%] ICP match score ≥ [threshold]
- MQL quality: [X%] SAL acceptance rate (measured monthly)
- Enrichment completeness: [X%] of MQLs have [required fields] populated
- Content support: [X] new pieces/month to support pipeline stages [X-Y]
- Feedback response time: Review and respond to sales feedback within [X] business days

SALES COMMITS TO:
- SLA response time: First contact within [X] hours for Tier 1, [X] hours for Tier 2
- Structured rejection: All MQL rejections categorized within [X] hours of rejection
- CRM hygiene: [Required fields] completed within [X] hours of opportunity creation
- Feedback participation: Attend monthly marketing-sales alignment meeting
- Re-engagement: Follow up on recycled leads when re-MQL threshold hit

JOINT GOVERNANCE:
- Weekly pulse check: 30-min standup — SDR manager + marketing ops — review SLA adherence
- Monthly review: 60-min deep-dive — VP Marketing + VP Sales — MQL quality, pipeline coverage, win rate by source
- Quarterly recalibration: Adjust MQL definition, scoring thresholds, and SLA targets based on performance data

---

DELIVERABLE 6: REVENUE IMPACT MODEL

Project pipeline improvement at current MQL volume:

BASELINE (current state):
- Monthly MQLs: [X]
- SAL rate: [X%] = [X] SALs
- SQL rate: [X%] = [X] SQLs
- Opportunity-to-Close rate: [X%]
- ACV: $[X]
- Monthly pipeline sourced by marketing: $[X]

SCENARIO MODELING (3 scenarios):

Conservative (fix SLA compliance only):
- Assumption: Response time compliance to SLA increases from [current X%] to [target X%]
- Impact on contact rate: +[X%]
- Impact on SAL rate: +[X pp]
- Pipeline uplift: +$[X]/month

Target (fix SLA + improve scoring model):
- Assumption: Rejection rate decreases from [X%] to [X%] via better scoring
- Impact on SAL rate: +[X pp] vs. baseline
- Impact on SQL rate: +[X pp] via better qualification criteria
- Pipeline uplift: +$[X]/month

Stretch (full architecture + recycle program):
- Assumption: Recycle program re-activates [X%] of previously rejected leads/month
- Recycle-to-pipeline conversion rate: [X%]
- Additional pipeline from recycled leads: +$[X]/month
- Total pipeline uplift: +$[X]/month vs. current

---

## Example Input/Output

**Input Example:**

Company: Folio Analytics — B2B SaaS revenue intelligence platform
ICP: VP Sales and CRO at 50-500 employee B2B SaaS companies
ACV: $42,000 ARR | Sales cycle: 47 days
Monthly MQLs: 280 | MQL-to-SAL: 31% | SAL-to-SQL: 58% | SQL-to-Close: 22%
Sales rejection rate: 41% | #1 rejection reason: "Too small / wrong industry"
Avg time to first contact: 31 hours | SLA target (aspirational): 4 hours
CRM: Salesforce | MAP: Marketo | Intent: 6sense | Routing: LeanData

**Output Example (excerpt):**

LEAD SCORING MODEL — FOLIO ANALYTICS:

Demographic Fit Score (70 points max):
- Job Title: VP Sales = 20 pts | CRO/CSO = 20 pts | Director of Sales = 15 pts | Head of Revenue = 18 pts | Sales Ops = 10 pts | Other = 0-5 pts
- Company Size: 100-500 employees = 20 pts | 50-99 = 15 pts | 500-1,000 = 10 pts | Under 50 = 0 pts (hard disqualifier)
- Industry: B2B SaaS = 20 pts | B2B tech (non-SaaS) = 15 pts | SaaS-adjacent = 10 pts | Other = 0 pts (hard disqualifier below 5)
- Tech Stack — Salesforce CRM detected: +10 pts (signals sales maturity)

DISQUALIFIERS (auto-remove from scoring):
- Employee count < 20: remove from scoring pool
- Industry = ecommerce, healthcare, consumer: auto-disqualify
- Title = student, intern, freelancer: auto-disqualify

Behavioral Score (80 points max, with decay):
- Pricing page (3 visits in 7 days): 40 pts | decay to 20 pts at day 8, 0 at day 15
- ROI calculator completion: 35 pts | no decay for 30 days
- Competitive comparison page (/vs-clari, /vs-gong): 30 pts | decay 50% at day 8
- Demo request abandonment (form opened, not submitted): 25 pts
- Case study download (revenue intelligence topic): 20 pts | decay 50% at day 21
- Webinar attendance (live): 18 pts | on-demand: 12 pts
- Email sequence: opened 4/5 most recent: 15 pts
- 5+ page visits in single session: 12 pts

MQL THRESHOLD:
- Standard MQL: Fit ≥ 30 AND behavioral ≥ 25 AND total ≥ 65
- Immediate MQL overrides: Demo request form = instant MQL regardless of score | Pricing page visit + VP/CRO title = instant Tier 1 MQL

SLA FRAMEWORK:
- Tier 1 (score 110+, fit 50+): First contact ≤ 90 minutes. Assignment: Direct to AE Kyle (Enterprise) or AE Sarah (Mid-Market). Alert: Slack #tier1-alerts channel + CRM task priority = Critical
- Tier 2 (score 75-109): First contact ≤ 4 business hours. Assignment: SDR queue rotational by territory. Alert: CRM task priority = High
- Tier 3 (score 65-74): First contact ≤ 1 business day. Assignment: SDR batch email sequence, phone attempt day 2

REJECTION TAXONOMY (Folio Analytics example):
- "Company <50 employees": route to 12-month low-touch nurture, flag as mis-scored (update disqualifier threshold)
- "Non-SaaS company": investigate data source error, remove from active database
- "Evaluating in Q4": set re-MQL date trigger for August 1st, enroll in "future buyer" sequence
- "No response in 8 touches over 14 days": return to marketing as "exhausted outreach," re-enter nurture pool

REVENUE IMPACT MODEL:
Current state: 280 MQLs × 31% SAL × 58% SQL × 22% close × $42K ACV = $246K pipeline/month

Conservative (SLA fix — response from 31 hrs to 4 hrs):
Research shows contact rate increases 11x when called within 5 minutes vs. 30 minutes (InsideSales.com)
Estimated SAL rate improvement: 31% → 37% = +19 additional SALs/month
Additional pipeline: +$46K/month = +$552K ARR equivalent annually

Target (SLA + scoring model — rejection rate 41% → 22%):
Additional MQLs reaching SAL: +54/month
Additional pipeline: +$127K/month = +$1.52M ARR equivalent annually

Stretch (full architecture + recycle program):
Recycled lead win-back rate (industry benchmark: 8-15%): 11% estimated
Reactivated leads: ~45 recycled leads × 11% = 5 additional deals/month
Additional pipeline: +$210K/month = +$2.52M ARR equivalent annually

## Success Metrics

**Handoff Quality:**
- SAL acceptance rate target: ≥ 70% (up from current baseline)
- MQL rejection rate: ≤ 20% within 90 days of implementation
- Time-to-first-contact (Tier 1 SLA): ≥ 90% compliance

**Pipeline Impact:**
- Marketing-sourced pipeline coverage ratio: ≥ 3:1 (pipeline vs. quarterly revenue target)
- Marketing-sourced win rate: ≥ industry benchmark for your segment
- Recycle-to-pipeline rate: ≥ 8% of recycled leads generating new pipeline within 6 months

**Alignment Health:**
- Monthly marketing-sales alignment meeting attendance: 100%
- CRM data completeness on MQL records: ≥ 90%
- Scoring model recalibration: completed within 14 days of quarterly review

## Related Prompts

- [CRM Data Quality & Revenue-Ready Marketing Database](AI-Powered-B2B-SaaS-CRM-Data-Quality-&-Revenue-Ready-Marketing-Database-Architecture-Intelligence-Engine.md)
- [Inbound Lead Scoring & Revenue Qualified Pipeline](AI-Powered-B2B-SaaS-Inbound-Lead-Scoring-&-Revenue-Qualified-Pipeline-Architecture-Intelligence-Engine.md)
- [Lead Routing & Sales Assignment Architecture](AI-Powered-B2B-SaaS-Lead-Routing-&-Sales-Assignment-Architecture-&-Revenue-Qualified-Pipeline-Distribution-Intelligence-Engine.md)
- [ABM Program Architecture & Account Tier Strategy](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/AI-Powered-B2B-ABM-Program-Architecture-&-Account-Tier-Strategy-Intelligence-Engine.md)

## Integration Tips

**Salesforce:**
- Create custom MQL/SAL/SQL Status field with picklist values matching your tier taxonomy — do NOT repurpose native Lead Status
- Build Process Builder (or Flow) trigger: when MQL Score ≥ threshold AND Fit Score ≥ threshold → auto-create Task assigned to routing owner + send Slack notification via Zapier webhook
- Use Assignment Rules with Round-Robin logic for Tier 2/3; use direct assignment for Tier 1 (manually maintained by RevOps)
- Dashboard: "MQL SLA Compliance" report — fields: Lead Created Date, First Activity Date, time delta, Tier, Owner — filter by Created Date = this week

**HubSpot:**
- Use Lifecycle Stage = "Marketing Qualified Lead" triggered by workflow when Score Property ≥ [X]
- Build separate workflows for each tier with distinct enrollment criteria and task assignment
- Use "Contact owner" rotation in Sequences for Tier 2/3 auto-enrollment
- Reports: Create "Time to First Contact" calculated property using First Touch Date - Create Date

**Marketo:**
- Build Revenue Cycle Model with MQL/SAL/SQL stages and transition rules matching your SLA
- Use Smart Campaigns for behavioral score additions with time-decay via score expiration
- Interesting Moments setup: auto-log key behavioral events to CRM activity timeline for SDR context before first call
- Velocity reporting: track stage-to-stage conversion rates and average days in stage

**Chili Piper / LeanData:**
- Build routing rules: Tier 1 (score ≥ 110) → Chili Piper "Concierge" for instant calendar booking on demo request, bypass SDR entirely
- Territory rules: map company HQ state/country → SDR/AE assignment
- Round-robin exception: if assigned rep hasn't logged activity in 90 minutes → auto-reassign to backup rep

**Slack Integration (via Zapier or native Salesforce/HubSpot → Slack):**
- #tier1-alerts: posts when Tier 1 MQL created — includes company name, title, score, last high-intent action, link to CRM record
- #sla-breaches: posts daily digest of leads that missed SLA window with rep name and minutes overdue
- #rejection-digest: weekly summary of rejection reasons by rep and source

## Troubleshooting

**Problem: Sales team rejects the scoring model and continues ignoring MQLs**
Solution: Run a 90-day validation study — pull last 12 months of closed-won deals and reverse-engineer what their MQL score would have been. Show sales that high-scoring MQLs close at [X%] vs. low-scoring at [X%]. Create a "Sales Proof Dashboard" that sales reps can self-serve to see MQL quality evidence. Never ask sales to trust marketing data — show them the outcomes.

**Problem: Score inflation over time — too many leads hitting MQL threshold without actually converting**
Solution: Implement "score freshness decay" — behavioral scores must have at least one high-intent action (≥ 20 points) in the last 30 days to maintain MQL status. Add a "recency gate": even if total score is high, no activity in 45 days triggers automatic MQL → Nurture demotion. Review threshold quarterly and raise by 5-10 points if rejection rate creeps above 30%.

**Problem: SDRs bypass the system and cherry-pick leads by title/company name, ignoring score**
Solution: Remove direct list views from SDR Salesforce profile — all leads must come through the CRM queue view sorted by score + tier. Add a compensation kicker: SDRs earn 1.25x meeting credit when the meeting leads came from MQLs with SAL acceptance (not cherry-picked self-sourced). Track and report "cherry-pick rate" — deals sourced outside the queue — in the weekly SDR team meeting.

## Version History
- v1.0: Initial creation (auto-generated)
