# Lead Scoring Model Optimization & Predictive Buying Signal Intelligence Engine - Build AI-Powered Lead Scoring That Sales Actually Trusts

**Difficulty:** Advanced | **Time:** 25-35 min | **Tags:** b2b, saas, lead-scoring, analytics, revenue-operations, predictive-analytics, hubspot, marketo, automation

## Overview
Designs, audits, or rebuilds a lead scoring model by reverse-engineering what your actual closed-won customers looked like at the MQL stage — then maps behavioral, firmographic, and technographic signals to conversion probability. Use this when your sales team ignores MQL scores, when your MQL-to-SQL rate is below 25%, or when you need to explain to leadership why "more leads" isn't fixing pipeline.

## Quick Copy-Paste Version

You are a B2B revenue operations expert specializing in lead scoring and pipeline quality. Audit and rebuild my lead scoring model to maximize MQL-to-SQL conversion accuracy.

My current situation:
- Marketing automation platform: [HubSpot / Marketo / Pardot / ActiveCampaign / other]
- CRM: [Salesforce / HubSpot CRM / other]
- Monthly MQL volume: [N leads]
- Current MQL-to-SQL conversion rate: [X]%
- Current SQL-to-Closed-Won conversion rate: [X]%
- Top 3 ICP firmographic criteria: [e.g., 50-500 employees, B2B SaaS, US-based]
- Current scoring criteria (list them): [e.g., email opens +5, pricing page visit +10, company size match +20, demo request +50]
- What sales says about lead quality: [e.g., "too many SMBs," "leads aren't ready," "they don't know our product"]

Please deliver:
1. Diagnosis — what's wrong with my current scoring model (over-rewarding intent signals, ignoring fit signals, etc.)
2. Fit score framework — firmographic, technographic, and behavioral criteria that predict ICP fit (weight each 1-100)
3. Engagement score framework — specific page visits, content downloads, and email behaviors that predict purchase intent (weight each 1-100)
4. Combined score thresholds — what score combinations qualify as MQL, Hot MQL, and Recycle
5. Negative scoring rules — behaviors that should reduce score or disqualify
6. Lead routing logic — which leads go to SDR vs. AE vs. self-serve vs. nurture
7. 30-day implementation plan — exact steps to rebuild in [my platform] without disrupting current pipeline
8. A/B test design to validate the new model within 60 days

Show score ranges, thresholds, and exact field names where possible.

## Advanced Customizable Version

ROLE: You are a Senior Revenue Operations Architect with 12+ years designing lead scoring models for B2B SaaS companies ranging from $2M to $200M ARR. You have built predictive lead scoring models in HubSpot, Marketo, Pardot, and 6sense — and you've sat in the war rooms when sales and marketing fight about lead quality. You know that most lead scoring fails because it rewards activity (email opens) over fit (right company) and intent (right behavior). You build models that increase MQL-to-SQL rates by 30–50% by treating lead scoring as a supervised machine learning problem, even in platforms without native AI.

BUSINESS CONTEXT:
- Company: [Company Name]
- Stage: [Seed / Series A / Series B / Series C / Growth]
- ARR: $[X]
- ACV or deal size: $[X average]
- Sales motion: [Self-serve / Inside Sales (SDR + AE) / Field Sales / PLG + Sales-Assist]
- Sales cycle: [< 30 days / 30–90 days / 90–180 days / 180+ days]
- ICP segments: [SMB / Mid-Market / Enterprise — specify primary]
- Industries targeted: [list top 3]
- Geographies: [US only / US + EMEA / Global]
- Marketing automation: [HubSpot / Marketo / Pardot / Salesforce Pardot / ActiveCampaign / other]
- CRM: [Salesforce / HubSpot CRM / other]
- Intent data tools (if any): [6sense / Bombora / G2 Buyer Intent / DemandBase / none]
- Enrichment tools (if any): [Clearbit / Apollo / ZoomInfo / Lusha / none]

CURRENT SCORING MODEL:
Describe your current scoring setup — or indicate "no formal model":

Positive Score Rules (list all):
- [Behavior/attribute]: [Points]
- [Behavior/attribute]: [Points]
- [Add all current rules]

Negative Score Rules (list all, or "none"):
- [Behavior/attribute]: [Points reduction]

Current MQL threshold: [X points]
Current MQL-to-SQL rate: [X]%
Current SQL-to-Opportunity rate: [X]%
Current Opportunity-to-Closed-Won rate: [X]%
Average time from MQL to SQL: [X days]
Monthly MQL volume: [N]
Monthly new customers from MQLs: [N]

Sales feedback on lead quality (be honest — this is the most important input):
- [What sales says about the leads marketing sends]
- [Specific objections they raise about MQL quality]
- [Segments, industries, or deal sizes sales says "never close"]

CLOSED-WON ANALYSIS DATA:
Provide data about your last 50–100 closed-won customers (or describe what you know):

Firmographic patterns in closed-won:
- Company size (employees): [most common range]
- Industry: [top 3 industries]
- Geography: [top markets]
- Company growth stage/signals: [e.g., recently funded, hiring SDRs, expanding headcount]
- Technology stack signals: [tools they used before buying you, e.g., Salesforce + Outreach, Shopify + Klaviyo]
- Revenue: [range if known]

Behavioral patterns in closed-won (before they became MQLs):
- Content most consumed: [top 3 pieces/pages]
- Pages visited on website: [list key pages — pricing, /vs/ comparison, use cases, etc.]
- Email engagement patterns: [opened sequences, responded to outbound, clicked specific topics]
- Event/webinar attendance: [Y/N, frequency]
- Time from first touch to MQL: [X days average]
- Number of sessions/visits before MQL: [N]

Firmographic patterns in CHURNED customers (anti-ICP — equally important):
- [What types of companies churned early or were hard to close]
- [What lead sources produced the most churned customers]
- [What behaviors at MQL stage predicted churn]

---

LEAD SCORING MODEL DESIGN:

**Section 1: Fit Score (0–100) — Is This the Right Company?**

Design the Fit Score independently from engagement. Fit is binary-ish: either a lead comes from an ICP company or they don't. Engagement should never compensate for poor fit.

Analyze the closed-won patterns provided and assign fit score points for each criteria below:

**Tier A Fit Criteria (each criterion worth 15–25 points — these are the strongest ICP signals):**
Design 3–5 Tier A criteria specific to this company's ICP. Examples:
- Company size in ICP range (e.g., 50–500 employees): 25 pts
- Industry is in top 3 ICP verticals: 20 pts
- Technology stack match (uses Salesforce CRM): 20 pts
- Recent funding event (Series A/B in last 12 months): 18 pts
- Job title is economic buyer or champion (VP/Director of [Function]): 15 pts

**Tier B Fit Criteria (each criterion worth 5–14 points — positive signals but not disqualifying if absent):**
Design 4–6 Tier B criteria. Examples:
- Company size in adjacent range (25–49 or 501–1000 employees): 10 pts
- Secondary ICP industry: 8 pts
- Company is VC-backed: 8 pts
- Job title is influencer/user (Manager/Senior [Function]): 7 pts
- Geographic match (target market): 5 pts

**Fit Score Ranges:**
- 75–100: Strong Fit (advance regardless of engagement score)
- 50–74: Moderate Fit (needs engagement score to compensate)
- 25–49: Weak Fit (high engagement required; still goes to nurture not SDR)
- 0–24: Poor Fit (disqualify; do not pass to SDR under any circumstances)

For each criteria, specify:
1. The exact field name in HubSpot/Salesforce/Marketo that stores this data
2. How to populate it (manual entry, enrichment tool, form field, inferred from behavior)
3. Whether it requires an enrichment tool or can be self-reported

**Section 2: Engagement Score (0–100) — How Ready Are They to Buy?**

Design the Engagement Score to measure demonstrated purchase intent, not just marketing engagement. An email open is not intent. Visiting the pricing page three times is.

**High-Intent Behaviors (15–30 points each — these are "hand-raise" moments):**
- Pricing page visit: 25 pts (each subsequent visit: +10, cap at 50)
- Demo/trial request form submitted: 50 pts (this alone should trigger routing review)
- Attended a live demo or webinar: 20 pts
- Visited /vs/ or comparison page: 22 pts (shows active evaluation)
- Viewed a customer case study in their industry: 18 pts
- ROI calculator completion: 28 pts
- Engaged with sales outreach (replied to email, answered call): 30 pts
- Repeated site visits within 14-day window (3+ sessions): 20 pts

**Medium-Intent Behaviors (5–14 points each):**
- Downloaded a bottom-of-funnel content piece (ROI guide, implementation checklist): 12 pts
- Attended a recorded webinar: 8 pts
- Email click to product or solution page: 10 pts
- Visited use case or solution page: 10 pts
- Downloaded a case study: 10 pts
- Visited careers page (signal: researching your company): 5 pts

**Low-Intent / Awareness Behaviors (1–4 points each — these should not drive MQL threshold alone):**
- Email open: 1 pt (cap at 5 pts total — prevent passive openers inflating score)
- Blog post read: 2 pts
- Downloaded a top-of-funnel educational piece: 3 pts
- Social media ad click: 2 pts

**Engagement Score Decay Rules:**
- Reduce engagement score by 20% for every 30 days of inactivity (last 90 days: -20%, 91–180 days: -40%, 180+ days: reset to 0)
- Rationale: A lead who downloaded a whitepaper 6 months ago and has been silent is not ready to buy today
- Implementation: Use HubSpot Workflows or Marketo Smart Campaigns to run score decay on a weekly schedule

**Section 3: Combined MQL Thresholds & Routing Logic**

Design a 2x2 routing matrix based on Fit Score and Engagement Score:

| | High Engagement (50+) | Low Engagement (<50) |
|---|---|---|
| **Strong Fit (75+)** | 🔥 HOT MQL → Route to AE directly | ✅ MQL → SDR outreach within 4 hours |
| **Moderate Fit (50–74)** | ✅ MQL → SDR outreach within 24 hours | ♻️ NURTURE → Add to long-term nurture sequence |
| **Weak Fit (25–49)** | 📧 NURTURE → High-intent nurture sequence | ❌ DISQUALIFY → Do not create contact activity |
| **Poor Fit (<25)** | ❌ DISQUALIFY regardless of engagement | ❌ DISQUALIFY |

**MQL Definitions:**
- Hot MQL: Fit ≥ 75 + Engagement ≥ 50 → Route directly to AE; SLA: 1 hour response
- Standard MQL: Fit ≥ 50 + Engagement ≥ 40, OR Fit ≥ 75 + Engagement ≥ 20 → Route to SDR; SLA: 4-hour response (business hours)
- Nurture MQL: Fit ≥ 50 + Engagement ≥ 25 → Automated nurture; revisit after 30-day re-engagement trigger
- Self-serve: Fit < 50 with strong engagement → Route to self-serve trial or product-led motion

**Section 4: Negative Scoring & Disqualification Rules**

Define explicit negative score rules that reduce score or hard-disqualify:

**Hard Disqualifiers (immediately set lead status = "Disqualified", remove from all scoring):**
- Email domain is personal (gmail.com, yahoo.com, hotmail.com, etc.): -100 pts (or auto-disqualify)
- Job title contains: student, intern, "looking for work," freelancer: -100 pts
- Company size: 1–4 employees (unless your ICP includes solopreneurs): -50 pts
- Competitor domain detected: Flag for review, do not auto-disqualify (could be competitive intel or job seeker)
- Unsubscribed from all marketing: Remove from scoring; do not pass to SDR

**Negative Score Behaviors (reduce score, do not disqualify):**
- Visited careers page only (no product pages): -10 pts
- Bounced from pricing page in < 10 seconds: -5 pts
- Only engaged with content published before your last major product change: -5 pts
- Opened 5+ consecutive emails with no clicks: -8 pts (likely auto-open from email security scanner)

**Section 5: Data Enrichment Strategy**

Define how to fill scoring fields automatically without relying on long forms:

**Free/Low-Cost Enrichment Methods:**
- Reverse IP lookup: Identify company from anonymous website visitors (Clearbit Reveal free tier, Albacross, Leadfeeder)
- LinkedIn profile scraping via form fill: When someone fills a form, auto-enrich company size and industry from LinkedIn via Clearbit or Apollo
- Technology stack detection: Use BuiltWith or Clearbit's tech stack data to identify if a prospect uses Salesforce, HubSpot, or key complementary tools
- Intent signal import: If using G2, import G2 Buyer Intent data directly into HubSpot/Marketo as a field: "G2 Intent Active = Yes" → add 30 pts to engagement score
- Email provider detection: Business email domain → auto-populate Company domain field → use for enrichment trigger

**Form Strategy for Fit Data:**
- Demo request form: Collect Job Title + Company + Company Size (required) — these 3 fields auto-calculate a preliminary Fit Score before any enrichment
- Content download form: Progressive profiling — first download: Name + Email. Second download: Company + Role. Third download: Industry + Challenge. Never ask for the same field twice.

**Section 6: Implementation Roadmap**

Provide a 30-day implementation plan specific to [marketing automation platform]:

**Week 1: Audit & Data Prep**
- [ ] Export all MQLs from last 12 months with final outcome (Closed Won / Closed Lost / Recycled / Churned)
- [ ] Identify the 10 firmographic and behavioral attributes most common in Closed Won — this is your ground truth
- [ ] Audit current score rules: delete any rule you cannot trace to a Closed Won pattern
- [ ] Map every score field to a CRM field name — confirm it populates consistently
- [ ] Set up enrichment tool (Clearbit/Apollo) and confirm it fires on new contact creation

**Week 2: Build Fit Score**
- [ ] Create "Fit Score" as a separate property from "Engagement Score" in your MAP
- [ ] Build Fit Score workflow: IF Company Size is [range] THEN Fit Score + 25; IF Industry is [X] THEN Fit Score + 20; etc.
- [ ] Test on 20 known Closed-Won customers — confirm they all score ≥ 75
- [ ] Test on 10 known churned/bad-fit customers — confirm they score ≤ 40
- [ ] Fix any rules that produce incorrect results

**Week 3: Build Engagement Score with Decay**
- [ ] Rebuild engagement score from scratch using the new intent-weighted criteria above
- [ ] Delete legacy rules that reward email opens disproportionately
- [ ] Set up score decay workflow: runs weekly, -20% if no activity in 30 days
- [ ] Test on 5 recent pipeline opportunities — engagement score should reflect their actual readiness

**Week 4: Routing Logic & Sales Alignment**
- [ ] Build the 2x2 routing matrix in your CRM/MAP using Fit Score + Engagement Score thresholds
- [ ] Create "Hot MQL" alert: Slack notification + immediate CRM task for AE when a Hot MQL is created
- [ ] Present new model to sales leadership: show the logic, show 3 example contacts at each tier, get explicit buy-in
- [ ] Launch with 30-day freeze: do not adjust scoring weights for 30 days — let data accumulate
- [ ] Schedule a Day 30 review meeting with sales: review MQL-to-SQL rate, lead quality NPS from sales team

**Section 7: Model Validation & A/B Testing**

Design a 60-day validation framework to prove the new model works:

**Metric Baseline (capture before launch):**
- MQL-to-SQL rate (trailing 90 days): [X]%
- SQL-to-Opportunity rate (trailing 90 days): [X]%
- Average time from MQL creation to first SDR outreach: [X hours]
- Lead quality rating from sales (survey: 1–5 scale): [X]
- Pipeline generated from MQLs per month: $[X]

**Success Metrics at Day 30:**
- MQL-to-SQL rate: Target ≥ 25% (if currently below); or ≥ +5 percentage points vs. baseline
- SDR outreach speed on Hot MQLs: 100% contacted within 1 business hour
- Lead quality sales survey: Target ≥ 3.5/5.0 average

**Success Metrics at Day 60:**
- MQL-to-SQL rate: Target ≥ 30%
- SQL-to-Closed-Won rate: Stable or improving vs. baseline (no quality deterioration)
- Pipeline coverage from MQLs: Stable or improving — total pipeline $, not just volume
- Churned/bad-fit accounts in new pipeline: Should be lower than trailing 90-day average

**A/B Test Design:**
- Route 50% of MQLs through new model, 50% through old model for first 30 days (if volume allows)
- Tag each lead with "Scoring Model = New" or "Scoring Model = Old"
- Compare MQL-to-SQL and SQL-to-Close by group at Day 30 and Day 60
- If new model outperforms on both metrics, sunset old model and implement 100%

**OUTPUT REQUIREMENTS:**
- Complete score card table: every scoring rule, point value, and field name
- Fit/Engagement 2x2 routing matrix formatted for sharing with sales
- HubSpot or Marketo workflow pseudocode for the top 5 score rules
- "Model Rationale" slide deck outline (5 slides) to present new model to sales and leadership
- 30-day implementation checklist formatted as a project management checklist
- Scoring model one-pager: single table showing all rules, weights, and thresholds — the "source of truth" document

CONSTRAINTS:
- Do not recommend tools that require 6+ month implementation timelines
- All score thresholds must be explainable to a salesperson in 60 seconds
- Every scoring rule must have a documented rationale tied to closed-won data — no "best practice" rules without evidence
- Negative scores must be explicitly defined — an incomplete negative scoring model is one of the most common failure modes
- The model must be maintainable by a marketing ops person, not a data scientist

## Example Input/Output

**Input Example:**

Company: Velora (B2B SaaS, Series B, $11M ARR, $22K ACV)
Sales motion: SDR + AE, inside sales
ICP: 100–1,000 employee B2B tech companies using Salesforce CRM
Current scoring: Email open +5, Link click +10, Form submit +30, Pricing page +25, Demo request +50
Current MQL threshold: 80 points
MQL-to-SQL rate: 18%
Sales feedback: "Half the MQLs are too small, and the ones who ask for demos are often just researching, not buying"
Closed-won patterns: 200–600 employees, uses Salesforce, VP of Sales or VP RevOps is champion, visited pricing page 3+ times before requesting demo

---

**Output Example (abbreviated):**

**DIAGNOSIS**
Velora's current model has three structural failures:
1. Email opens (+5 pts) are driving ~30% of total scores for passive contacts who have never visited the product — SDRs are calling list-hygiene problems, not buyers
2. No Fit Score exists — a 10-person company that watches every webinar scores higher than a 500-person Salesforce shop that visited pricing once
3. Demo request (+50 pts) fires without fit gating — a poor-fit company requesting a demo creates an MQL and gets SDR time, burning capacity on deals that will never close

**SCORING MODEL REBUILD**

Fit Score (0–100):

| Criteria | Points | Field Name | Data Source |
|----------|--------|------------|-------------|
| Company size 100–600 employees | 30 | `numberofemployees` | Clearbit enrichment |
| Uses Salesforce CRM | 25 | `tech_stack_salesforce` | Clearbit Tech |
| Industry: B2B Tech, SaaS, FinTech | 20 | `industry` | Form + Enrichment |
| Job title: VP/Director RevOps, Sales, Marketing | 20 | `jobtitle` | Form + Enrichment |
| VC-backed company | 10 | `company_funding_status` | Clearbit enrichment |
| Company size 601–1,000 employees | 8 | `numberofemployees` | Clearbit enrichment |
| Located in US or UK | 5 | `country` | IP + Form |

Strong Fit threshold: ≥ 75 | Moderate: 50–74 | Weak: 25–49 | Disqualify: < 25

Engagement Score (0–100):

| Behavior | Points | Notes |
|----------|--------|-------|
| Demo request submitted | 50 | Only relevant if Fit ≥ 50 |
| Pricing page visit | 25 | Each repeat visit: +10 (cap 50) |
| Visited /vs/ comparison page | 22 | Strong active evaluation signal |
| ROI calculator completion | 28 | Highest intent signal |
| Attended live demo/webinar | 20 | |
| Case study in tech/SaaS industry | 18 | |
| 3+ site sessions in 14 days | 20 | |
| Email click to product page | 10 | |
| Bottom-of-funnel content download | 12 | |
| Email open | 1 | Cap at 5 pts total |

**ROUTING MATRIX**

| | Engagement ≥ 50 | Engagement < 50 |
|---|---|---|
| Fit ≥ 75 | 🔥 HOT MQL → AE directly (1-hour SLA) | ✅ MQL → SDR (4-hour SLA) |
| Fit 50–74 | ✅ MQL → SDR (24-hour SLA) | ♻️ Nurture sequence |
| Fit < 50 | ❌ Nurture only — no SDR regardless of engagement | ❌ No action |

**30-DAY PROJECTION**
Based on Velora's current 18% MQL-to-SQL rate, the primary drag is poor-fit companies inflating the denominator. Eliminating companies with Fit Score < 50 from SDR routing reduces MQL volume by ~35%, but removes the lowest-converting tier. Expected result: MQL-to-SQL rate rises to 28–33% within 60 days. SDR capacity freed: ~12 hours/week per SDR currently spent on poor-fit leads.

## Success Metrics

- Fit Score and Engagement Score are tracked as separate properties (not blended into a single score)
- Model has explicit negative scoring rules for at least 3 disqualifying conditions
- MQL routing matrix is documented and shared with sales leadership
- Scoring rules are traceable to closed-won customer patterns, not assumed best practices
- Score decay is implemented for contacts inactive > 30 days
- Day-30 MQL-to-SQL rate target is defined and measured from model launch date
- Sales team receives the model one-pager and provides feedback before go-live

## Related Prompts

- `../../05_Analytics-&-Performance/Lead-Quality-&-Conversion-Analytics/Marketing-Lead-Quality-&-Sales-Handoff-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Funnel-Conversion-&-Pipeline-Velocity/Marketing-Funnel-Conversion-&-Pipeline-Velocity-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Inbound-Marketing/B2B-Website-Personalization-&-Dynamic-Visitor-Intelligence-Engine.md`
- `../../02_Product-Marketing/Customer-&-Market-Research/ICP-Discovery-Engine.md`

## Integration Tips

- **HubSpot:** Create two separate Contact properties: "Fit Score" (number) and "Engagement Score" (number). Build Workflows for each: Fit Score workflow runs on contact create + update (enrichment trigger); Engagement Score workflow runs on page view, form submit, and email click events. Create a "Routing Tier" property (dropdown: Hot MQL / Standard MQL / Nurture / Disqualified) calculated by a third workflow that reads both scores and applies the 2x2 matrix. Set up a HubSpot List for "Hot MQL" = Routing Tier is Hot MQL AND Lead Status is not SQL — use this as the SDR's priority queue view.
- **Marketo:** Use two separate Score fields (default Marketo "Score" field for Engagement; create custom field "Fit Score" for firmographic scoring). Build Smart Campaigns for each scoring event. Use a "Score Router" Smart Campaign that triggers when either score changes, evaluates the combined threshold, and sets Lead Status accordingly. Enable Velocity Scoring via Marketo's built-in functionality to detect score acceleration (a lead jumping 40 points in 48 hours is more urgent than a slow accumulator).
- **Salesforce:** Sync both Fit Score and Engagement Score from your MAP to Salesforce Lead object. Build a Salesforce Report: "Hot MQLs Not Yet Contacted" — filters: Routing Tier = Hot MQL, Lead Status ≠ Working, Created Date = last 24 hours. Pin this report to the SDR team's Salesforce homepage. Use Flow to auto-create a Task for the assigned SDR when a Hot MQL is created.
- **6sense / Bombora Intent Data:** Add a third score component: Intent Score. When 6sense signals "Active Buying Stage" for a matched account, add 35 pts to Engagement Score and send a Slack alert to the relevant AE with account name + signal details. This converts anonymous intent data into concrete SDR action without requiring form fills.
- **Slack:** Create a #hot-mql-alerts channel. Use Zapier (HubSpot trigger: Lead status changed to Hot MQL) → Slack message with contact name, company, fit score, engagement score, and the 3 behaviors that triggered the score. SDR acknowledges with a thumbs-up emoji to confirm they've seen it. No acknowledgment in 60 minutes → automated escalation to SDR manager.
- **Google Sheets / Looker Studio:** Build a "Lead Scoring Health Dashboard" with: (1) MQL volume by tier by week, (2) MQL-to-SQL rate by tier (Hot vs. Standard vs. Nurture), (3) Score distribution histogram — if scores cluster at the threshold, adjust weights; if scores are bimodal, the model is working. Review weekly for the first 90 days, monthly thereafter.
- **Clearbit / Apollo Enrichment:** Set up enrichment to fire on new contact creation and on any contact that submits a form. Map enriched fields directly to Fit Score workflow triggers. For contacts without a business email (can't enrich), add to a "Needs Qualification" list for SDR manual review — do not auto-disqualify, but do not auto-advance.

## Troubleshooting

**Problem: "We implemented the new model and MQL volume dropped 40% — now sales is complaining we're not sending enough leads."**
Solution: This is the intended outcome if your previous model was qualification-light. A 40% drop in MQL volume with a 30%+ increase in MQL-to-SQL rate means you're sending fewer but better leads — which is the goal. Prepare a "quality vs. quantity" comparison: show sales the Closed Won rate per 100 MQLs under the old model vs. the new model. If 100 old MQLs generated 4 Closed Won deals and 60 new MQLs generate 5 Closed Won deals, the new model is performing correctly. Reframe the conversation from "lead volume" to "pipeline quality per lead." If leadership insists on volume, add a "Top of Funnel" track (separate from MQL) for lower-fit leads that SDRs work at lower priority — this preserves volume optics without degrading the core pipeline.

**Problem: "Sales is still ignoring the score — they're cherry-picking leads regardless of tier."**
Solution: Sales ignoring scores is almost always a trust problem, not a process problem. They've been burned by bad leads labeled "hot" before. Fix: sit with 3 SDRs and walk through 10 recent Hot MQLs together — for each one, ask "Would you have called this person?" If they say no, find out why and adjust the model. If they say yes, the problem is follow-through, not scoring. Create a weekly "Score Accuracy Review": SDRs rate each MQL they worked (1–5: Was this lead correctly scored?). Feed ratings back into model calibration monthly. Showing SDRs that their feedback directly changes the model builds the trust loop that makes scoring adoption sustainable.

**Problem: "Our enrichment tool is only filling data for 60% of contacts — the other 40% have incomplete Fit Scores."**
Solution: Build a "Fit Score Confidence" field (High / Medium / Low) that reflects data completeness. Contacts with < 3 fit score fields populated get Confidence = Low and route to SDR as a "Qualify First" task — the SDR's job is to ask 2 qualifying questions before pitching, not to demo immediately. For the form strategy: add one required qualifying question to your most-used form (e.g., "How many people are on your sales team?" or "What CRM do you use?") — this single self-reported field can be worth 20–25 Fit Score points and eliminates the enrichment gap for your highest-intent leads.

## Version History
- v1.0: Initial creation (auto-generated)
