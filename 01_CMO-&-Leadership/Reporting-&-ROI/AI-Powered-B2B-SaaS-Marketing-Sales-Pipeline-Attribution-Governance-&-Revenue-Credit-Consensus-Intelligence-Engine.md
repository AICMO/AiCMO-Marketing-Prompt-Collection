# AI-Powered B2B SaaS Marketing-Sales Pipeline Attribution Governance & Revenue Credit Consensus Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** b2b-saas, attribution, revenue-operations, cmo, pipeline, governance, marketing-sales-alignment

## Overview

Designs a complete, board-ready marketing-sales pipeline attribution governance framework that definitively answers "which revenue does marketing own?" — including the rules engine, dispute resolution process, CRM data model, and quarterly reporting methodology that both CMO and CRO will actually sign off on.

## Quick Copy-Paste Version

You are a senior B2B SaaS revenue operations architect with deep expertise in pipeline attribution and marketing-sales alignment. Design a complete pipeline attribution governance framework for a B2B SaaS company selling [Product] to [ICP Buyer: title, company size] at an ACV of [ACV], with [Marketing Team Size] in marketing and [Sales Team Size] in sales.

Build the definitive attribution governance system:

**1. ATTRIBUTION CLASSIFICATION RULES**
Write the exact logic for each category:
- Marketing-Sourced Pipeline (full credit): Define the criteria — what counts as a qualifying marketing origination? Specify the lookback window (30/60/90 days), the qualifying touchpoints (content download, event registration, demo request, trial signup, paid ad click), and the CRM field that locks the source.
- Marketing-Influenced Pipeline (partial credit): Define the influence criteria — any marketing touchpoint within [X days] before opportunity creation. Specify what % credit marketing receives (20%? 40%? weighted by touchpoint recency?).
- Sales-Sourced / Exec-Sourced Pipeline: Define when AEs and executives receive full sourcing credit — cold outbound with no prior marketing touchpoint, CEO relationship, referral from board.
- Co-Attribution Scenarios: Define the specific split logic for joint situations (field event + AE follow-up, content download + SDR outbound, partner referral + marketing campaign).
- Dark Funnel Attribution: Define how to handle deals where the buyer self-educates anonymously — the survey-at-close methodology, pipeline weighting rules, and default attribution when no touchpoint exists.

**2. THE GOVERNANCE OPERATING MODEL**
Design the operational infrastructure:
- Monthly attribution reconciliation meeting: agenda, attendees (CMO, CRO, RevOps lead, Finance), the data report format, and the decision authority matrix for disputes
- Dispute resolution process: who has override authority, what evidence is required to change attribution, the escalation path when CMO and CRO disagree
- CRM data integrity rules: which Salesforce/HubSpot fields are locked (no AE override), which are editable and require justification, and the audit log requirements
- Quarterly model calibration: how to review whether the attribution model is producing accurate results and the process for updating rules

**3. THE ATTRIBUTION RULES DOCUMENT**
Write the actual agreement document — a concise, signed-off rules document that both CMO and CRO can reference when disputes arise. Include:
- 5-7 specific attribution scenarios with the correct classification for each
- The override request form and 48-hour review SLA
- The "benefit of the doubt" rule (default to marketing attribution when evidence is ambiguous)

**4. BOARD AND CFO PRESENTATION FRAMEWORK**
Create the quarterly attribution reporting template:
- Marketing-Sourced Pipeline ($, % of total, conversion rate to closed-won)
- Marketing-Influenced Pipeline ($, % of total pipeline touched by marketing)
- New Logo Pipeline by Source (compare marketing vs. sales vs. partner sourcing)
- NRR and Expansion Attribution (which marketing programs drove upsell/cross-sell)
- Year-over-year trend and what changed

Deliver the complete governance framework as an operating document that can be implemented in 30 days.

## Advanced Customizable Version

ROLE: You are a Principal Revenue Operations Architect and GTM strategist with 12+ years of experience building attribution governance systems at B2B SaaS companies from $10M to $500M ARR. You have mediated 50+ CMO/CRO attribution disputes, designed attribution models for board presentations, and configured multi-touch attribution in Salesforce, HubSpot, Marketo Measure (Bizible), and custom data warehouse environments. You understand both the political dynamics of marketing-sales attribution conflicts and the technical infrastructure required to enforce governance at scale.

CONTEXT:
- Company: [Company Name]
- Stage: [Series A / Series B / Series C / Pre-IPO / Public]
- ARR: [Current ARR]
- ACV: [Average Contract Value — this determines how complex attribution needs to be; $10K ACV can use simpler models than $200K ACV]
- Sales Motion: [Full-cycle AE / SDR + AE / PLG + Sales-Assisted / Enterprise with multiple stakeholders]
- Marketing Team: [Headcount and structure — demand gen, content, product marketing, field marketing]
- Sales Team: [AE count, SDR count, field sales vs. inside sales split]
- CRM: [Salesforce / HubSpot / other — this determines technical implementation]
- Current Attribution State: [No model exists / First-touch only / Last-touch only / Broken multi-touch / Disputed manual process]
- Primary Attribution Conflict: [Sales overrides marketing source / AEs claim cold-called deals that had prior marketing touchpoints / Dark funnel deals with no trackable touchpoints / Events: who gets credit when both marketing and AEs attend? / Other]
- Marketing's Current Claimed Pipeline Contribution: [%]
- Sales' Counter-Claim: [%]
- Board/CFO Position: [Neutral / Skeptical of marketing numbers / Demands clean methodology]
- Attribution Tool Budget: [None — use native CRM / Willing to invest in Marketo Measure or equivalent / Already using multi-touch tool]

OBJECTIVE: Design a comprehensive pipeline attribution governance framework that:
1. Produces a single agreed-upon attribution methodology that both CMO and CRO will commit to in writing
2. Operates in the existing CRM without requiring a data science team to maintain it
3. Eliminates the monthly "who gets credit" argument from pipeline review meetings
4. Produces board-ready numbers that the CFO trusts
5. Scales without breaking as the company grows from current ARR to 3x ARR

---

**MODULE 1: ATTRIBUTION CLASSIFICATION FRAMEWORK**

Define the complete ruleset with binary decision logic:

TIER 1 — MARKETING-SOURCED (100% Marketing Credit)
Qualifying Definition: Marketing is the first recorded touchpoint with a net-new contact at a net-new account, AND an opportunity was created within [X] days of that touchpoint, AND there was no prior AE outreach to that account in the preceding [Y] days.

Qualifying First Touchpoints:
- Inbound form fill on website (demo request, trial signup, contact us, gated content)
- Paid media click → landing page → form fill (source: paid channel)
- Organic search → website → form fill
- Event registration AND attendance (the contact attended, not just registered)
- Referral program participation (referee submits intro form)
- Direct outreach to a marketing-generated contact list (SDR follows up on content download within [X] days)
- Product-qualified lead (PQL) who reaches activation milestone and requests sales contact

Non-Qualifying (Marketing Attribution Disqualified):
- AE cold called the account first, then the contact happened to fill out a form later
- The contact is a known prospect the AE has been working for 60+ days
- The deal originated from an executive/board relationship

CRM Implementation: "Lead Source" field locked at creation, stamped by form/UTM, no manual override. "Attribution Override" requires VP RevOps approval and audit log entry.

TIER 2 — MARKETING-INFLUENCED (Partial Credit: [20-40%])
Qualifying Definition: An opportunity was created by Sales (AE cold outreach or exec relationship), BUT a marketing touchpoint occurred within [90 days] before the opportunity creation date.

Qualifying Influence Touchpoints:
- Attended a company-hosted event or webinar (min. 30 minutes)
- Downloaded gated content (not just viewed ungated)
- Engaged with 3+ email campaigns (opened AND clicked)
- Visited the pricing page or demo page 2+ times in a 30-day window
- Engaged with paid retargeting ads (view-through within 14 days)

Influence Credit Split Logic:
- 1 qualifying touchpoint: 20% marketing credit / 80% sales credit
- 2-3 qualifying touchpoints: 30% marketing credit / 70% sales credit
- 4+ qualifying touchpoints across 2+ channels: 40% marketing credit / 60% sales credit

TIER 3 — SALES-SOURCED (0% Marketing Credit)
Definition: AE-initiated cold outbound with no prior marketing touchpoints, executive relationship from prior company, board or investor-introduced deal, inbound referral from customer (CS-sourced).

TIER 4 — PARTNER/CHANNEL-SOURCED (Track separately from marketing and sales)
Definition: Partner referred or co-sold deal, marketplace listing conversion. Track partner contribution as a fourth category, not marketing.

---

**MODULE 2: DARK FUNNEL ATTRIBUTION PROTOCOL**

B2B buyers research anonymously for 60-80% of their buying journey. Standard attribution models systematically undercount marketing's contribution. Implement this protocol:

Survey-at-Close Methodology:
- Embed a 2-question survey in the DocuSign packet or MSA signature flow
- Q1: "Before you first connected with our team, how did you hear about [Company]?" (Checkbox: Word of mouth / LinkedIn / Search / Content/Podcast / Industry event / Trade publication / Analyst report / I didn't — was cold outreach / Other)
- Q2: "Which resources were most helpful in your evaluation?" (Checkbox: Website / Case studies / Product demo / Peer referral / Analyst report / Sales conversations / Other)

Dark Funnel Attribution Rules:
- If survey indicates marketing touchpoint + CRM shows sales-sourced: reclassify as Marketing-Influenced (30% credit)
- If survey indicates unknown (buyer can't remember) AND deal is $[X]+ ACV: conduct 15-minute win interview to uncover journey
- Track dark funnel pipeline quarterly and report as a separate line item ("Pipeline with Unattributed Marketing Influence") in board deck

Pipeline Weighting for Dark Funnel:
- Apply a 25% marketing influence credit to all Sales-Sourced pipeline as a statistical correction factor when survey data is not available (validate this % quarterly by comparing to deals where survey data IS available)

---

**MODULE 3: GOVERNANCE OPERATING CADENCE**

Monthly Attribution Reconciliation Meeting (90 minutes):
- Attendees: CMO, CRO, RevOps Lead, Finance/FP&A representative
- Agenda:
  - (15 min) Prior month closed-won pipeline by attribution category — review actual vs. model
  - (20 min) Open pipeline by attribution category — is coverage balanced?
  - (20 min) Dispute queue: any attribution overrides requested since last meeting — review evidence and vote
  - (20 min) Leading indicators: are new-logo sourcing trends changing? Should model be adjusted?
  - (15 min) Alignment: agree on the numbers both CMO and CRO will present to their teams

Decision Authority Matrix for Disputes:
- Tier 1 disputes (< $25K ACV): RevOps Lead makes final call, 48-hour SLA
- Tier 2 disputes ($25K–$100K ACV): CMO + CRO jointly decide, 72-hour SLA
- Tier 3 disputes ($100K+ ACV): CMO + CRO + CEO makes final call, 1-week SLA
- Default rule: When evidence is ambiguous, default to Marketing-Influenced (30% credit) — never default to zero marketing credit unless clear counter-evidence exists

CRM Data Integrity Protocol:
- "Lead Source" field: Locked. Set by UTM/integration at form submission. Cannot be edited by AE.
- "Lead Source Detail" field: Editable by AE, but requires 50+ characters of explanation. Logged in audit trail.
- "Attribution Override Requested" checkbox: Triggers automated notification to RevOps and CMO.
- "Marketing Influenced" field: Boolean, populated by marketing automation rules, not AE input.
- Monthly data quality report: Flag any opportunities created without Lead Source, any overrides in the prior 30 days.

Quarterly Model Calibration:
- Pull closed-won deals and validate attribution against deal notes, call recordings, and customer interviews
- Calculate "attribution accuracy rate" — what % of deals do customers confirm our attributed source?
- Adjust lookback windows and influence thresholds if accuracy rate falls below 70%
- Document all model changes with rationale and communicate to CMO + CRO + Board

---

**MODULE 4: THE ATTRIBUTION AGREEMENT DOCUMENT**

[This is the actual document to be signed by CMO and CRO]

PIPELINE ATTRIBUTION GOVERNANCE AGREEMENT
[Company Name] — Effective [Date]

We, the undersigned, agree to the following attribution methodology for all pipeline and closed-won revenue reporting:

AGREED DEFINITIONS:
[Paste Tier 1–4 definitions from Module 1]

AGREED SCENARIOS AND CLASSIFICATIONS:
1. A contact fills out a demo request form → AE closes the deal. Attribution: Marketing-Sourced (100%).
2. AE cold calls a VP who had downloaded a whitepaper 45 days prior. Attribution: Marketing-Influenced (30%).
3. Board member introduces CEO to prospect, no prior touchpoints. Attribution: Sales-Sourced (0% marketing).
4. Company sponsors a conference. An attendee at the booth fills out a lead capture card. AE follows up and closes. Attribution: Marketing-Sourced if no prior AE contact, Marketing-Influenced (30%) if AE had prior contact.
5. Prospect seen in website visitor intelligence tool (Clearbit/6sense) but no form fill. AE cold outreaches and closes. Attribution: Sales-Sourced unless prospect self-identifies a prior marketing touchpoint in post-close survey.
6. SDR sends cold outbound sequence. Prospect had previously opened 4 emails from a marketing nurture track. Attribution: Marketing-Influenced (30%).
7. Existing customer refers a prospect via referral program form fill → AE closes. Attribution: CS-Sourced / Partner (track separately, 0% marketing sourcing credit, may count as marketing-influenced if marketing ran the referral program).

DISPUTE RESOLUTION:
[Paste Module 3 decision authority matrix]

REVIEW CADENCE:
This agreement will be reviewed quarterly and updated if accuracy validation indicates model adjustments are needed.

Signed:
_____________________          _____________________
[CMO Name], CMO               [CRO Name], CRO

Date: _________________        Date: _________________

---

**MODULE 5: BOARD AND CFO REPORTING FRAMEWORK**

Quarterly Marketing Attribution Summary (Board Deck Slide Format):

HEADLINE METRICS:
- Marketing-Sourced New Logo Pipeline: $[X]M ([Y]% of total new logo pipeline)
- Marketing-Influenced New Logo Pipeline: $[X]M ([Y]% of total new logo pipeline with any marketing touch)
- Marketing-Sourced Closed Won: $[X]M ARR ([Y]% of new ARR)
- Marketing-Sourced Win Rate: [Z]% (vs. Sales-Sourced Win Rate: [A]%)
- Pipeline Coverage from Marketing-Sourced: [B]x (current quarter pipeline / quarter target)

TREND ANALYSIS:
- QoQ change in marketing sourcing % (is marketing generating more or less of the pipeline?)
- CAC by source (marketing-sourced vs. sales-sourced — which is more efficient?)
- Time-to-close by source (does marketing-sourced pipeline close faster or slower?)

METHODOLOGY NOTE (Required for Board Credibility):
"Marketing-Sourced pipeline is defined as opportunities where the first recorded touchpoint was a marketing channel touchpoint with no prior AE contact in the preceding [X] days. This methodology was agreed upon jointly by the CMO and CRO on [Date] and is reviewed quarterly. [Y]% of our closed-won deals this quarter had their attribution validated through our post-close survey."

---

Deliver the complete governance framework as a Word-ready operating document, including the signed agreement template, the CRM field specification sheet, and the first board deck attribution summary slide with placeholder data structure.

## Example Input/Output

**Input Example:**
- Company: Flowify — B2B SaaS workflow automation for mid-market ops teams
- Stage: Series C, $48M ARR
- ACV: $28,000
- Sales Motion: SDR + AE, 2-week average sales cycle for SMB, 6-week for mid-market
- CRM: Salesforce with HubSpot Marketing Hub integrated
- Current State: First-touch attribution only; AEs routinely claim deals that had marketing content touchpoints; CMO and CRO in monthly argument about who sourced the Acme Corp ($320K) deal
- Primary Conflict: SDR outbound follows up on content downloads within 3 days — Sales claims sourcing credit; Marketing claims the content download was the first touch

**Output Example:**

### Attribution Classification for Flowify

**Tier 1 — Marketing-Sourced (100% Marketing Credit)**
A contact submits any form on flowify.com (demo, trial, content download, event registration) AND either:
a) No AE had logged a call, email, or LinkedIn contact to that account in the prior 45 days, OR
b) The form submission was the account's first recorded touchpoint in Salesforce

Lookback Window: 45 days. If an AE contacted the account 46+ days ago with no response, and marketing later generates a form fill, Marketing-Sourced.

SDR Follow-Up Rule: When an SDR emails or calls a contact within 7 days of a content download, the opportunity remains Marketing-Sourced (the SDR is marketing's response motion, not a separate sourcing motion). After 7 days, if no response and SDR continues outreach independently, reclassify to Marketing-Influenced.

**Acme Corp Dispute Resolution:**
The Acme Corp $320K deal scenario — if the first contact was a whitepaper download on March 1st, and the AE's first logged Salesforce activity was March 4th (3 days after), the opportunity is Marketing-Sourced. The AE's role was marketing-enabled follow-up, not cold sourcing.

**Flowify Attribution Agreement — Agreed Classifications:**
- Content download → SDR follow-up within 7 days → AE closes: **Marketing-Sourced**
- AE cold emails a dark account, contact had downloaded content 30 days prior (no prior AE activity): **Marketing-Influenced (30%)**
- CEO/AE cold outreach, zero prior marketing touchpoints: **Sales-Sourced**

**Quarterly Board Summary (Q2 Template):**
- Marketing-Sourced Pipeline: $4.2M (38% of new logo pipeline, up from 31% in Q1)
- Marketing-Sourced Win Rate: 34% vs. Sales-Sourced Win Rate: 22% — marketing-sourced deals close at 55% higher rate
- CAC from Marketing-Sourced: $8,200 vs. Sales-Sourced: $14,600 — marketing-sourced 44% more efficient
- Methodology validated: 78% of Q2 closed-won deals had attribution confirmed via post-close survey

## Success Metrics

- **Attribution Agreement Rate:** 90%+ of new opportunities have a locked Lead Source field within 24 hours of creation
- **Dispute Frequency:** Monthly dispute queue falls below 5 deals per month within 90 days of implementation
- **Model Accuracy:** Post-close survey validates CRM attribution in 75%+ of deals
- **CMO-CRO Alignment Score:** Both sign off on the same pipeline numbers for board reporting
- **Dark Funnel Capture:** Survey completion rate >80% on closed-won deals; dark funnel credit applied consistently
- **Board Acceptance Rate:** CFO/board accept the marketing pipeline numbers without requesting methodology re-explanation

## Related Prompts

- [Multi-Touch Attribution & Revenue Marketing Intelligence Engine](../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md) — technical implementation of multi-touch models
- [AI-Powered Marketing Revenue Contribution Narrative & CFO-CEO Alignment Intelligence Engine](../../01_CMO-&-Leadership/Reporting-&-ROI/AI-Powered-Marketing-Revenue-Contribution-Narrative-&-CFO-CEO-Alignment-Intelligence-Engine.md) — communicating attribution to the board
- [AI-Powered B2B SaaS Self-Reported Attribution & Survey-Based Marketing Measurement Intelligence Engine](../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/AI-Powered-B2B-SaaS-Self-Reported-Attribution-&-Survey-Based-Marketing-Measurement-Intelligence-Engine.md) — the survey methodology that fills dark funnel gaps
- [AI-Powered B2B SaaS CMO-CRO Revenue Partnership Architecture & Unified GTM Leadership Intelligence Engine](../../01_CMO-&-Leadership/Strategy-&-Planning/AI-Powered-B2B-SaaS-CMO-CRO-Revenue-Partnership-Architecture-&-Unified-GTM-Leadership-Intelligence-Engine.md) — the broader CMO-CRO relationship framework

## Integration Tips

- **Salesforce:** Configure Campaign Influence with Primary Campaign Source field. Use Salesforce's native First Touch, Last Touch, and Even Distribution models as baseline. Add custom "Attribution_Tier__c" picklist field (Marketing-Sourced / Marketing-Influenced / Sales-Sourced / Partner-Sourced) with automated population from UTM data via Zapier or native flow.
- **HubSpot:** Use the "Original Source" and "Original Source Drill-Down" properties — these are auto-set and AE-protected. Sync to Salesforce via native integration. Build a HubSpot report showing pipeline by Original Source monthly.
- **Marketo Measure (formerly Bizible):** The best tool for automated multi-touch attribution at $30M+ ARR. Configures directly in Salesforce. Use the "Custom Attribution" model to build the exact Tier 1/2/3 rules above. Costs $2,000-$5,000/month but eliminates the manual dispute process entirely.
- **Rockerbox or Triple Whale:** Better for companies with heavy paid media investment — connects ad spend to pipeline automatically with de-anonymization.
- **Outreach/Salesloft:** Sync AE activity logs to Salesforce contact history. This is what proves "no prior AE contact" in attribution disputes — if AE logged a call in Outreach and it synced, the record exists.
- **Notion/Google Docs:** Create the Attribution Agreement as a shared document with CMO and CRO as owners. Link it in the Salesforce "Opportunities" object description so AEs see the rules before requesting overrides.
- **Looker/Tableau/PowerBI:** Build the quarterly attribution summary dashboard with pre-built filters for Marketing-Sourced, Influenced, and Sales-Sourced. Set it as the default pipeline dashboard for the CMO and CRO.

## Troubleshooting

**Problem:** CRO refuses to sign the attribution agreement because it will lower their "sales-sourced" pipeline numbers.
**Solution:** Reframe the negotiation. Show the CRO that Marketing-Sourced pipeline converts at a higher rate AND has lower CAC — a higher marketing attribution % actually makes the CRO's win rate metric look better (AEs are closing higher-quality deals) and their CAC efficiency improve. Present the data first, then ask for sign-off on methodology. If still refused, escalate to CEO with a recommendation that both CMO and CRO present marketing-sourced, sales-sourced, and influenced as three separate lines — no argument about which is bigger, just clear visibility into the composition.

**Problem:** AEs keep manually changing the Lead Source field in Salesforce to "AE Outbound" even though marketing had prior touchpoints.
**Solution:** Lock the Lead Source field in Salesforce via field-level security — remove Edit access from all Salesforce profiles except RevOps Admin and System Admin. Create a separate "Attribution Override Request" field that AEs CAN edit, triggering a Salesforce Flow that sends an email to RevOps and the CMO with the deal details and the AE's explanation. Institute a 48-hour SLA for review. Make overrides visible in the monthly meeting — sunlight is the best disinfectant.

**Problem:** The board asks why marketing pipeline contribution jumped from 30% to 52% quarter-over-quarter after implementing the new model.
**Solution:** Document the methodology change explicitly: "In Q2, we implemented a formal attribution governance framework that replaces our prior first-touch-only model with a multi-tier model including marketing-influenced pipeline. The 52% figure reflects both improved tracking and the reclassification of pipeline that had unrecorded marketing touchpoints under the prior model. The prior model was knowingly conservative and understated marketing's role." Present both the old and new methodology numbers for 2-3 historical quarters so the board can see the trend using the new methodology, not just the jump.

## Version History
- v1.0: Initial creation (auto-generated)
