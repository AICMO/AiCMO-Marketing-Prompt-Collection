# SaaS Renewal Intelligence & Automated Contract Renewal Revenue Engine - Forecast, Automate, and Win Every Renewal at Full or Expanded Value

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** renewal-management, net-revenue-retention, b2b-saas, contract-renewal, expansion-revenue, customer-success, forecasting, automation, revenue-operations

## Overview
Build a complete renewal intelligence and automation system that forecasts renewal outcomes at 90/60/30 days, automates multi-touch renewal campaign sequences, and generates commercial negotiation playbooks — so your CS and Sales teams close every renewal at full value or above. Use this when you want to stop losing renewals to inertia, last-minute discounting, or lack of a systematic renewal motion.

## Quick Copy-Paste Version

You are a senior Customer Success and Revenue Operations strategist specializing in B2B SaaS renewal management. Your job is to build a complete, fully automated renewal intelligence system.

My renewal context:
- Company: [Your Company Name]
- Product: [What you sell, e.g., project management platform for engineering teams]
- Total ARR under renewal in next 12 months: [e.g., $3.8M across 140 accounts]
- Average ACV: [e.g., $27K]
- Current gross renewal rate: [e.g., 84%]
- Current net revenue retention (NRR): [e.g., 101%]
- Renewal model: [Annual contracts / Multi-year with annual true-ups / Monthly rolling]
- Who owns renewals: [CSM only / CSM + AE / AE only / dedicated renewal team]
- CRM: [Salesforce / HubSpot / other]
- CS platform: [Gainsight / ChurnZero / Totango / none]

Deliver a complete renewal intelligence and automation system with these 6 components:

1. RENEWAL FORECAST MODEL (90/60/30-Day Pipeline)
   - Weighted renewal probability scoring: 12 signals to assess likelihood of full renewal, partial renewal, downsell, or churn — with specific weights and data sources
   - 4-tier renewal forecast buckets: Commit (>90% confidence), Likely (70-89%), At-Risk (40-69%), Called Loss (<40%)
   - Commercial risk flags: accounts likely to request discounts, contract reductions, or payment term changes
   - Expansion signal overlay: accounts showing buying signals for upsell at renewal
   - Weekly renewal forecast template (ready for Salesforce opportunity or Google Sheet) with formulas

2. RENEWAL OUTREACH SEQUENCES BY TIER
   For each forecast tier (Commit, Likely, At-Risk, Called Loss), provide complete, production-ready email sequences:
   - 90-day pre-renewal: kickoff message, value reinforcement framing
   - 60-day: ROI review invite, champion engagement, stakeholder map review
   - 30-day: commercial conversation opener, urgency creation without pressure
   - 14-day: final close sequence with escalation to exec sponsor if needed
   - 7-day and renewal date: last-chance and confirmation templates
   Include subject lines, full email body, and send-time recommendations for each touch

3. ROI & VALUE DELIVERY PACKAGE GENERATOR
   - Customizable ROI summary template (the "business case for renewal" document)
   - 8 value proof data points every CSM should pull before a renewal conversation
   - Customer-specific metrics to highlight: usage depth, time-to-value, incidents prevented, revenue generated, team adoption rate
   - Competitive vulnerability assessment: what a competitor would say and how to preemptively counter it
   - Executive summary format (one-pager) the champion can forward to their CFO/CPO to justify renewal

4. COMMERCIAL NEGOTIATION PLAYBOOK
   - Discount request response matrix: 6 types of discount requests and the specific counter-script for each (budget freeze, price comparison, scope reduction, economic headwinds, contract consolidation, "loyalty" ask)
   - Value-to-price reanchoring framework: how to redirect from price to business impact using the JOLT method (Justify, Overcome, Link, Tie-down)
   - Multi-year upsell-at-renewal playbook: when and how to propose a 2-3 year deal with favorable pricing in exchange for commitment
   - Guardrails: maximum discount thresholds by ACV tier and minimum acceptable renewal terms
   - Escalation script: exact language to use when looping in a VP or executive to close a stalled renewal

5. RENEWAL RISK INTERVENTION PLAYBOOK
   - Early intervention triggers: 8 signals that should auto-generate a renewal risk alert (e.g., champion departure, support ticket surge, no logins in 21 days, billing dispute)
   - "Save before renewal" playbook: 3-stage rapid intervention sequence for accounts entering red status within 60 days of renewal
   - Executive sponsor activation: when to bring in your CEO/VP to engage their C-suite counterpart
   - Last-resort offer framework: commercial concession hierarchy (delay, pilot extension, success guarantee) to use only after all else fails

6. RENEWAL OPERATIONS DASHBOARD & AUTOMATION RULES
   - 10 KPIs to track weekly: gross renewal rate, net renewal rate, weighted renewal pipeline, days to renewal coverage, average discount depth, renewal cycle length, expansion-at-renewal rate, at-risk ARR, forecast accuracy, CSM renewal quota attainment
   - Alert automation rules: Zapier/Make trigger templates for CRM-based renewal date approaching, health score threshold crossed, no response after 3 touches
   - Monthly renewal retrospective template: what to analyze after each renewal period closes
   - Quarterly renewal forecast cadence: meeting agenda and review format for CS + Finance + Revenue leadership

Format each component as a ready-to-implement system — not bullet-pointed advice. Include all email copy, scoring formulas, and decision trees in full, usable form.

## Advanced Customizable Version

ROLE:
You are a Chief Customer Officer and Revenue Operations expert with 15+ years of experience building renewal management systems for B2B SaaS companies from Series B through public. You understand the full commercial, operational, and relationship dynamics of contract renewals. You write systems that CSMs can execute without ambiguity and that RevOps can automate without custom engineering.

CONTEXT:
Company profile:
- Company name: [Your Company]
- Product category: [e.g., data observability platform / HR tech / marketing automation]
- Target customer: [e.g., mid-market tech companies, 200-2,000 employees]
- GTM model: [Product-led with sales assist / Sales-led / Channel partner]
- Total ARR: [e.g., $12.4M]
- ARR up for renewal in next 12 months: [e.g., $4.1M across 160 accounts]
- ACV range: [e.g., SMB $8K–$15K / Mid-Market $25K–$80K / Enterprise $100K+]
- Current gross renewal rate: [e.g., 87%]
- Current NRR: [e.g., 104%]
- Renewal ownership model: [CSM-led / AE-led / Pooled renewal team / Split by ACV tier]
- Renewal cycle start: [e.g., CS initiates at 90 days; AE joins at 60 days if risk or expansion]
- Biggest renewal challenges: [e.g., late starts, champion turnover, budget freezes, price competition from [competitor]]
- CRM: [Salesforce / HubSpot / Pipedrive]
- CS platform: [Gainsight / ChurnZero / Totango / HubSpot CS / Spreadsheets]
- Product analytics: [Mixpanel / Amplitude / Pendo / built-in / none]
- Billing: [Stripe / Zuora / Chargebee / NetSuite]

OBJECTIVE:
Build a complete, production-ready renewal intelligence and automation system that achieves:
- Gross renewal rate of 92%+
- NRR of 110%+ by systematically surfacing expansion at renewal
- Zero surprise churns — every at-risk renewal identified 90 days out
- CSMs spending <15% of their time on renewal admin and >85% on value delivery and relationships

DELIVERABLE 1 — RENEWAL FORECASTING ENGINE:
Construct a data-driven renewal forecast model incorporating:
a) Signal categories and weights:
   - Product adoption signals (30% weight): DAU/MAU ratio, feature depth score, core workflow completion rate, API call volume trend, seats utilized vs. licensed
   - Relationship signals (25% weight): executive sponsor engagement, champion tenure, QBR attendance, CSM sentiment score, multi-threading depth (# of contacts with meaningful engagement)
   - Commercial signals (20% weight): invoice payment timeliness, last discount depth, seats vs. capacity headroom, budget ownership changes, contract expansion history
   - Support signals (15% weight): ticket volume trend (90-day rolling), CSAT on tickets, time-to-resolution trend, severity of open issues
   - Engagement signals (10% weight): marketing email engagement, community activity, event attendance, NPS score and trend

b) Scoring formula:
   - Output a 0–100 renewal health score
   - Map score ranges to forecast categories: Commit (80–100), Likely (60–79), At-Risk (35–59), Called Loss (0–34)
   - Include a separate "expansion probability" overlay score (0–100)
   - Create the formula structure for Salesforce formula fields or a Google Sheets implementation

c) Renewal pipeline report structure:
   - Account name | ACV | Renewal date | Renewal health score | Forecast category | Owner | Last touch date | Risk flags | Expansion signals | Next action | Notes
   - Weekly review cadence and participants
   - How to present to Finance for revenue forecasting

DELIVERABLE 2 — RENEWAL CAMPAIGN SEQUENCES:
For each account type, provide complete multi-touch renewal campaign sequences with all copy written in full:

[COMMIT ACCOUNTS] — High health, low risk, possible expansion
- 90 days: Strategic value review invitation (email + calendar invite template)
- 60 days: Future roadmap preview + mutual success plan refresh
- 30 days: Commercial conversation with multi-year or expansion proposal
- Close: Renewal confirmation + expansion upsell presentation outline

[LIKELY ACCOUNTS] — Moderate health, standard renewal expected
- 90 days: ROI-led check-in to reinforce value before renewal conversation
- 60 days: Renewal kickoff email with ROI summary attachment (template)
- 45 days: Stakeholder alignment call — confirm budget and approvers
- 30 days: Renewal proposal delivery email
- 14 days: Follow-up if proposal not signed — specific urgency framing
- 7 days: Final close email

[AT-RISK ACCOUNTS] — Lower health, requires intervention before renewal
- 90 days: Immediate intervention — CSM + manager review, account-specific save plan
- 80 days: Executive sponsor re-engagement (your side)
- 70 days: Value redelivery session request (live demo of value metrics)
- 60 days: Executive-to-executive outreach (your VP/CCO to their VP/CFO)
- 45 days: Commercial conversation — what flexibility can we offer vs. what's non-negotiable
- 30 days: Formal save offer with specific terms
- 14 days: Escalation decision — full save or manage exit

[CALLED LOSS ACCOUNTS] — Very low probability, manage for best possible outcome
- Immediate: Win/loss analysis conversation request
- If responding: One final commercial offer with clear deadline and terms
- If not responding: Managed offboarding sequence to preserve relationship for future recovery
- Post-churn: 90-day check-in from VP/CCO to keep door open

For each email in every sequence: include subject line, email body (300–500 words), and post-send action trigger.

DELIVERABLE 3 — VALUE DELIVERY PACKAGE SYSTEM:
Design a scalable system for generating customized renewal business cases:

a) Data pull checklist: exactly what data to pull from CRM, product analytics, and support systems 14 days before each renewal conversation — listed as a CSM task checklist

b) ROI summary template (ready-to-fill structure):
   - Section 1: Usage & Adoption (key metrics with YoY or QoQ comparison)
   - Section 2: Business Outcomes (outcomes in customer's language tied to their original success criteria)
   - Section 3: Support & Partnership (response times, issues resolved, CSM touchpoints)
   - Section 4: What's Coming (roadmap items relevant to their use case)
   - Section 5: Investment Snapshot (what they've spent, what it's delivered, cost of alternatives)

c) Executive one-pager template (for champion to share internally for budget approval)

d) Competitive counter-narrative: for the top 2 competitors in the space [fill in: Competitor A, Competitor B], provide the renewal-stage talking points that reframe why switching costs, integration risk, and data migration would cost more than renewal savings

DELIVERABLE 4 — COMMERCIAL NEGOTIATION FRAMEWORK:
Provide a complete renewal negotiation system:

a) Pricing conversation preparation:
   - BATNA analysis template: understand their alternatives before the conversation
   - Price-to-value ratio benchmark: how to help the customer understand cost-per-outcome vs. total contract cost
   - Discount authority matrix: CSM / Director / VP / CCO approval levels with specific thresholds

b) Objection response scripts — write the full response for each scenario:
   - "We need to cut the budget by 20%"
   - "Competitor X is offering the same features for half the price"
   - "We're going to reduce our seat count this year"
   - "We'd like to move to a month-to-month arrangement"
   - "Can you match the price we got in year one?"
   - "We need to delay the renewal by 90 days — budget cycle"
   - "We've had too many issues this year to justify full price"

c) Expansion-at-renewal playbook:
   - Timing: when in the renewal sequence to introduce expansion (not before value is validated)
   - Package: how to structure a "renewal + expansion bundle" offer that's commercially compelling
   - Multi-year offer framework: what to give up (modest discount) vs. what you get (commit, reduces churn risk, improves cash flow)
   - Cross-sell trigger: if renewal health is Green and expansion score is 70+, introduce specific add-on or module with business case

DELIVERABLE 5 — AUTOMATION RULES & WORKFLOW ARCHITECTURE:
Define the complete automation architecture:

a) CRM automation triggers (Salesforce/HubSpot):
   - 90 days before renewal date: create Renewal Opportunity record, assign to CSM, send task "Start renewal health assessment"
   - When renewal health score drops below 60: trigger "At-Risk Renewal" workflow, notify CSM manager, add to weekly pipeline review
   - When renewal opportunity reaches 30 days with no activity: escalation alert to Director of CS
   - When renewal is closed-won: trigger expansion discovery task for accounts with expansion score >65
   - When renewal is closed-lost: trigger win/loss survey and 90-day re-engagement sequence

b) Zapier/Make automation blueprints:
   - Trigger: renewal date approaching (pull from CRM) → Action: populate renewal playbook in Notion/Confluence → Notify CSM in Slack
   - Trigger: health score drops (from Gainsight/ChurnZero webhook) → Action: create at-risk task in CRM → Post to #at-risk-accounts Slack channel with account context
   - Trigger: renewal signed (closed-won in CRM) → Action: send congratulations email to champion → Create upsell opportunity → Log renewal metrics in Google Sheets

c) Renewal retrospective template:
   - Monthly: what renewed, what churned, what downgraded — with root cause categorization
   - Quarterly: renewal rate trend, NRR trend, discount depth trend, forecast accuracy score, top 3 save wins, top 3 losses with lessons learned

CONSTRAINTS:
- Every email must be immediately usable — no placeholders left unfilled except [Customer Name], [Company], [CSM Name]
- Commercial guidance must include specific numbers and thresholds, not vague guidance like "use your judgment"
- Automation rules must be implementable in Salesforce flows or HubSpot workflows without custom code
- All playbooks must be executable by a CSM with 12 months of experience — not requiring 10 years of institutional knowledge
- No boilerplate advice. Every recommendation must be specific, actionable, and tied to revenue outcomes

OUTPUT FORMAT:
Organize all 5 deliverables clearly with headers, sub-headers, and tables where appropriate. Write all email sequences in full — no "fill in the details" shortcuts. Provide the scoring model as a formula, not a narrative. Include a 1-page "Quick Reference Card" at the end summarizing the full renewal motion timeline, key thresholds, and escalation triggers.

## Example Input/Output

**Input Example:**
- Company: Stratify (B2B SaaS, sales forecasting platform)
- ARR up for renewal: $2.1M across 87 accounts
- ACV range: Mid-market $18K–$55K
- Current gross renewal rate: 81%
- NRR: 96% (losing value on renewals)
- Renewal ownership: CSM-led, AE joins at 30 days if risk or expansion
- Biggest challenge: Champion turnover and budget freezes in current macro environment
- CRM: HubSpot, CS platform: ChurnZero

**Output Example (excerpt):**

**Renewal Health Score — Stratify Configuration**

| Signal | Weight | Measure | Data Source |
|---|---|---|---|
| Core feature activation (forecast model used weekly) | 20% | % weeks active / last 12 | Mixpanel |
| Seats utilized / licensed | 10% | Licensed seats with ≥2 logins in last 30 days | ChurnZero |
| Executive sponsor engagement | 15% | EBR attended in last 90 days + executive email open last 30 days | HubSpot |
| NPS score (last survey) | 10% | Raw NPS (0–10), normalized | Delighted → ChurnZero |
| Support ticket trend | 10% | 90-day rolling ticket count vs. prior 90-day period | Zendesk |
| Invoice payment timeliness | 10% | Days-to-pay on last 3 invoices | Chargebee |
| Champion tenure at account | 10% | Primary contact tenure in role (months) | HubSpot Contact) |
| Multi-thread depth | 10% | # contacts with email open in last 60 days | HubSpot |
| Product breadth | 5% | # distinct modules/features used in last 30 days | Mixpanel |

**Score: 78 → Forecast: Likely**

---

**At-Risk Renewal — 90-Day Email (Stratify CSM → Champion)**

Subject: Let's get ahead of [Company]'s renewal — I want to make sure we're set up for success

Hi [Champion Name],

I'm reaching out because [Company]'s renewal is coming up in 90 days and I want to make sure we're delivering real value before we have that commercial conversation.

Before we talk contract, I want to earn the renewal.

I'm pulling together your impact report — usage data, forecast accuracy improvements, and pipeline call outcomes tied to Stratify over the last year. I want to share that with you in a 30-minute session and hear honestly: what's working, what isn't, and what would need to change to make this an easy yes when renewal comes up.

Would [Date/Time Option 1] or [Date/Time Option 2] work for a quick 30-minute call?

No agenda pressure — just an honest conversation about whether we're delivering what we promised.

[CSM Name]
Customer Success, Stratify

---

**Discount Objection: "We need to reduce our commitment by 20% this year."**

Response framework:

"I hear you — I want to work within your constraints. Before we change the commercial terms, I want to make sure we're not leaving value on the table that you're already paying for.

Can I ask: is the 20% reduction driven by budget ceiling, or by seats you're not using?

If it's budget: I'd like to explore a multi-year structure where we lock in your current rate for 2 years rather than reduce scope. That protects your budget predictability and avoids a re-procurement process next year.

If it's unused seats: let's right-size now — but I want to walk through adoption data first, because we often find seats that look inactive are actually tied to workflows that matter. The last thing I want is for you to reduce and then need to add back in 6 months.

What's driving the reduction request?"

## Success Metrics

- Gross renewal rate improves to 90%+ within 2 renewal cycles of implementation
- NRR reaches or exceeds 108% as expansion-at-renewal becomes systematic
- Zero surprise churns (all churn accounts flagged in "At-Risk" or "Called Loss" 60+ days before renewal date)
- Average discount depth decreases by 30% as CSMs use value reanchoring scripts instead of defaulting to discounts
- Forecast accuracy: predicted vs. actual renewal rate within ±5% each quarter
- Renewal cycle length decreases (renewal initiated and closed earlier in the cycle)
- CSM time on renewal admin: measured before/after, target <15% of weekly time

## Related Prompts

- [Churn-Prevention-Expansion-Revenue-Engine.md](./Churn-Prevention-Expansion-Revenue-Engine.md)
- [Customer Health Score & Early Warning Intelligence Engine](../Customer-Success-Automation/Customer-Health-Score-&-Early-Warning-Intelligence-Engine.md)
- [QBR-EBR Automation Engine](../Customer-Success-Automation/QBR-EBR-Automation-Engine.md)
- [NPS & CSAT Closed-Loop Intelligence Engine](../Customer-Success-Automation/NPS-CSAT-Closed-Loop-Intelligence-Engine.md)

## Integration Tips

- **Salesforce**: Create a custom "Renewal Opportunity" record type with health score, forecast category, and renewal campaign stage fields. Use Flow Builder to trigger the 90/60/30-day task sequences based on the "Close Date" field. Install the Renewal Health Score as a formula field pulling from ChurnZero or Gainsight via API.
- **HubSpot**: Use Deal pipeline stages mapped to renewal forecast buckets. Set up Sequences for each tier's outreach cadence. Use Workflows to auto-enroll contacts into renewal sequences based on "Days to Renewal Date" enrollment trigger.
- **Gainsight/ChurnZero**: Configure Timeline entries to track all renewal touchpoints. Use Cockpit for at-risk renewal playbooks. Set Journey Orchestrator rules to auto-trigger renewal outreach sequences based on health score thresholds.
- **Google Sheets / Notion**: For teams without a CS platform, build the renewal forecast tracker in Google Sheets with conditional formatting by tier. Use Zapier to populate rows from HubSpot deal records. Connect to Notion for the renewal playbook wiki where CSMs log notes.
- **Slack integration**: Create a #renewal-pipeline channel with weekly automated digest (via Zapier + Slack) summarizing accounts renewing in 30/60/90 days with current health scores and owners.
- **Chargebee/Stripe Billing**: Trigger CRM renewal health flag when an invoice is overdue by 7+ days. Auto-populate renewal forecast with contract value from billing records.

## Troubleshooting

**Issue: CSMs aren't starting the renewal motion at 90 days — they wait until 30 days out.**
Fix: Remove the 90-day start from being a recommendation and make it a CRM automation. When renewal date = 90 days from today, the system should auto-create a task and log a Renewal Opportunity record with a mandatory Stage 1 completion requirement. CSM managers should track "% renewals with 90-day activity" as a KPI in their weekly pipeline review. Make late starts visible — shame the metric, not the person.

**Issue: The renewal health score produces inaccurate forecasts because product usage data is missing or stale.**
Fix: Before scoring, audit your data pipeline. The most common culprits are: product analytics events not firing correctly, CSM platform integration not syncing on schedule, or manual data (like NPS) not being entered. Start with a simplified 5-signal model using only data you trust, then layer in additional signals as you fix the data plumbing. A 70% accurate simple model beats a theoretically perfect model with bad data.

**Issue: Customers treat the renewal conversation as an opportunity to renegotiate — every renewal becomes a multi-month discount battle.**
Fix: This is a value delivery problem disguised as a commercial problem. If customers feel empowered to aggressively renegotiate, they don't believe they're getting full value. Implement the ROI summary package at 90 days — before any commercial conversation happens. When a customer sees documented proof of outcomes before price comes up, the framing shifts from "what can I cut?" to "what can we expand?" Also review your discount history — if you've granted deep discounts before, customers have learned to ask. Re-establish your pricing floor with a discount authority matrix and stick to it.

## Version History
- v1.0: Initial creation (auto-generated)
