# Marketing Automation Workflow Architecture Engine - Full-Stack MOps Blueprint Generator

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** martech, marketing-ops, automation, hubspot, marketo, b2b, lead-scoring, nurture, lifecycle, saas

## Overview
Designs complete marketing automation workflow architectures — lead scoring models, lifecycle stage logic, trigger-based nurture sequences, and routing rules — tailored to your platform, GTM motion, and funnel data. Use it when building a new automation infrastructure from scratch, rebuilding after a platform migration, or when your current workflows are a patchwork of untested logic no one fully understands.

## Quick Copy-Paste Version

You are a senior marketing automation architect. Design a complete workflow architecture for my marketing automation platform.

MY SETUP:
- Platform: [HubSpot / Marketo / Pardot / ActiveCampaign / Klaviyo / other]
- Business model: [B2B SaaS / B2C eCommerce / D2C / other]
- CRM: [HubSpot CRM / Salesforce / Pipedrive / other]
- Monthly new leads: [X] per month
- Current funnel stages: [e.g., Subscriber → MQL → SQL → Opportunity → Customer]
- Average sales cycle length: [X days/weeks]
- Marketing team size: [X] people who will manage these workflows

MY BIGGEST AUTOMATION GAPS (pick your top 3):
- [ ] Lead scoring model doesn't exist or isn't trusted
- [ ] No automated lifecycle stage progression
- [ ] Nurture sequences are generic, not segmented
- [ ] Lead routing to sales is manual or broken
- [ ] No re-engagement or win-back logic
- [ ] Post-purchase/onboarding automation is missing
- [ ] Behavioral triggers aren't being used

Build me:
1. A lead scoring model — demographic fit score (0-100) + behavioral engagement score (0-100), with MQL threshold and score decay rules
2. Lifecycle stage definitions with entry/exit criteria and workflow triggers for each transition
3. A nurture workflow map — 3 tracks minimum (early-stage, late-stage, re-engagement), with branching logic based on persona or behavior
4. Lead routing rules — conditions for routing to sales, assigning to reps, and setting priority
5. A workflow naming convention and folder structure so the system stays manageable at scale

Output each as a structured spec ready to build in [my platform], not as general advice.

## Advanced Customizable Version

ROLE:
You are a Marketing Operations Architect with 12+ years of experience designing and auditing automation infrastructures for B2B SaaS companies from Series A through IPO. You have built MOps systems on HubSpot, Marketo, Pardot, and ActiveCampaign, and you specialize in translating messy funnel data into clean, scalable workflow logic. You think in systems — every workflow you design accounts for edge cases, data quality issues, and the operational load on a small marketing ops team. You follow the Sirius Decisions (now Forrester) Demand Unit Waterfall model for lifecycle design, the MadKudu framework for lead scoring, and platform-native best practices for workflow governance.

OBJECTIVE:
Design a complete, production-ready marketing automation architecture for the company described below. Every output must be specific enough to implement directly — no generic frameworks, no "it depends" answers. Every workflow must include trigger conditions, branch logic, wait steps, exit criteria, and the human action (if any) required at each stage.

CONTEXT — COMPANY PROFILE:

Company details:
- Company name: [Your Company]
- Business model: [B2B SaaS / B2C eCommerce / D2C / Agency / Marketplace]
- Stage: [Seed / Series A / Series B / Growth / Enterprise]
- Industry vertical: [Fintech / HR Tech / DevTools / Healthcare / E-commerce / Other]
- ICP description: [e.g., "VP/Director of Finance at manufacturing companies with 100-1,000 employees, US-based, using legacy ERP"]
- ACV / AOV: $[X]
- Average sales cycle: [X days]
- Marketing team (total + ops dedicated): [X] total / [X] ops-focused
- Monthly new inbound leads: [X]
- Monthly MQLs passed to sales: [X] (or "unknown")
- MQL-to-SQL conversion rate: [X]% (or "unknown — one of the problems")

Platform environment:
- Marketing automation platform (MAP): [HubSpot Marketing Hub / Marketo Engage / Pardot / ActiveCampaign / Klaviyo / other]
- MAP tier/edition: [e.g., HubSpot Marketing Hub Enterprise / Marketo Business Tier]
- CRM: [HubSpot CRM / Salesforce / Pipedrive / other]
- CRM sync status: [Real-time bi-directional / One-way MAP to CRM / Broken / Not configured]
- Data enrichment tool: [Clearbit / 6sense / Apollo / ZoomInfo / None]
- Intent data tool: [6sense / Bombora / G2 Buyer Intent / None]
- Form and landing page tool: [MAP native / Unbounce / Webflow / WordPress / other]
- Chat tool: [Drift / Intercom / HubSpot Chat / None]

Current funnel stages (customize to match your CRM):
- Stage 1: [e.g., Subscriber — has email, no BANT qualification]
- Stage 2: [e.g., Lead — submitted a non-gated form or attended a webinar]
- Stage 3: [e.g., MQL — meets ICP fit criteria + minimum engagement score]
- Stage 4: [e.g., SAL — sales has accepted and is actively working]
- Stage 5: [e.g., SQL — discovery call held, BANT partially qualified]
- Stage 6: [e.g., Opportunity — formal opportunity in CRM]
- Stage 7: [e.g., Customer]
- Stage 8: [e.g., Churned / Lost]

Known data problems (flag anything relevant):
- [e.g., "30% of form submissions have no company name"]
- [e.g., "Job title field is free text — 200+ variations of VP Marketing"]
- [e.g., "CRM and MAP contacts are not deduplicated — ~15% duplicate rate"]
- [or "None identified" if data is clean]

Persona segments (list 2-4 core buyer personas for nurture branching):
1. [Persona name + role + primary pain point]
2. [Persona name + role + primary pain point]
3. [Persona name + role + primary pain point]

Content available for nurture sequences:
- [List available content types: blog posts, ebooks, webinar recordings, case studies, demo videos, ROI calculators, templates — be specific about quantity and topics if known]

CONSTRAINTS:
- All workflows must be buildable by a marketing ops generalist without developer support
- Workflow logic must account for contact data quality issues noted above — include data normalization steps where critical
- Lead scoring model must include a score decay mechanism to prevent "MQL zombie" inflation
- Every nurture sequence must have a hard exit condition (time-based or behavior-based) so no contact is stuck in a workflow indefinitely
- Routing rules must cover edge cases: no assigned rep, rep is OOO, contact re-enters funnel after previously being disqualified
- Naming conventions must be enforceable by a team of [X] people and survive staff turnover

OUTPUT — DELIVER ALL SECTIONS IN ORDER:

---

**SECTION 1: LEAD SCORING MODEL**

Deliver two independent score components:

*1A. Fit Score (Demographic/Firmographic — 0 to 100)*
Build a weighted scoring table:
- Company size (employee count or revenue range): assign points by band
- Industry vertical: assign positive points for ICP-match verticals, negative for disqualified verticals
- Job title / seniority: map common title variants to role categories and assign points per category
- Geography: points for target regions, negative for excluded regions
- Technology signal (if enrichment tool available): points for key tech stack indicators
- Total fit score — MQL fit threshold: [X points]

*1B. Engagement Score (Behavioral — 0 to 100)*
Build a behavioral scoring table covering:
- Email opens and clicks (with decay: distinguish first-open from repeated opens)
- Form submissions by type (gated content download > newsletter subscribe)
- Website page visits by intent signal (pricing page, demo page, case studies > blog > homepage)
- Event attendance (webinar attended live > registered but no-show)
- Chat interaction initiated
- Direct sales email reply
- CRM activity logged by sales rep
Include score decay rule: subtract [X] points per [X days] of inactivity, never below 0

*1C. MQL Threshold Logic*
Define the composite MQL rule:
- Minimum fit score required: [X]
- Minimum engagement score required: [X]
- Hard exclusion conditions that block MQL status regardless of score (e.g., competitor domain, free email domain, student/intern title, previously disqualified by sales)
- Fast-track MQL conditions (contact qualifies even with lower engagement if: e.g., pricing page visited + demo requested, or intent data spike detected)

*1D. Score Decay Implementation*
Specify:
- Decay frequency: daily or weekly scheduled workflow
- Decay amount: [X] points per [X days] of zero engagement
- Floor: score never drops below 0
- Re-MQL logic: if a previously disqualified contact re-engages and crosses MQL threshold again, define re-routing rule (auto re-MQL or manual review queue)

---

**SECTION 2: LIFECYCLE STAGE ARCHITECTURE**

For each stage in the funnel, define:
- Entry criteria: exact conditions that trigger stage enrollment (data fields + score thresholds + behavioral signals)
- Exit criteria: conditions that move contact to next stage or disqualify
- Time-in-stage SLA: maximum days before escalation or disqualification triggered
- Automation trigger: what workflow fires on stage entry
- Notification: who is notified and how (Slack, email, CRM task, etc.)
- Disqualification path: where does a contact go if they do not progress? (recycle to nurture vs. archive)

Build the full stage map as a structured table, then explain the two most complex transition workflows in step-by-step detail.

---

**SECTION 3: NURTURE WORKFLOW MAP**

Design a minimum of 4 nurture tracks:

*Track 1 — Top of Funnel / Early Stage (Subscriber to Lead)*
- Enrollment trigger: contact submits top-of-funnel form or joins list
- Goal: move contact to MQL-qualifying engagement within 45 days
- Sequence: 6-8 emails over 30-45 days
- Branching logic: if persona is identified (from form field or enrichment), branch to persona-specific content; if not, send universal track
- Exit conditions: (a) contact hits MQL threshold — exit and trigger MQL workflow; (b) contact reaches email 8 with no engagement — exit to re-engagement track; (c) contact unsubscribes — exit and suppress

*Track 2 — Middle of Funnel / Late Stage (MQL to SQL Support)*
- Enrollment trigger: contact becomes MQL but has not booked a meeting in [X] days
- Goal: drive demo/meeting booking or provide sales with multi-touch context before outreach
- Sequence: 4-5 emails over 14-21 days (shorter, more direct, proof-heavy)
- Branching logic: if contact visits pricing page mid-sequence — send pricing-specific email immediately, skip scheduled send; if sales logs a call note in CRM — exit workflow to avoid overlap
- Exit conditions: (a) meeting booked — exit; (b) sales marks as SAL — exit; (c) sequence complete with no meeting — recycle to top-of-funnel nurture with 90-day wait

*Track 3 — Re-Engagement (Cold Subscribers / Stale MQLs)*
- Enrollment trigger: contact score falls to [X] after [X days] of zero engagement, or was previously disqualified by sales more than 90 days ago
- Goal: re-qualify for sales or suppress permanently
- Sequence: 3 emails over 21 days — escalating stakes (last chance framing on email 3)
- Exit conditions: (a) any click or form submit — re-score and re-enter top-of-funnel track; (b) no engagement after email 3 — move to suppression list, remove from active scoring, flag for list hygiene review

*Track 4 — Post-Purchase / Onboarding (Customer Activation)*
- Enrollment trigger: contact stage = Customer in CRM (synced from closed-won opportunity)
- Goal: drive product activation milestone within [X days], reduce early churn signal
- Sequence: 6 emails over 30 days — milestone-based (not time-based where possible; trigger each email on product event if event data is available)
- Branching logic: if product activation milestone hit — move to expansion nurture; if no login within [X days] — trigger CSM alert task in CRM
- Exit conditions: (a) customer hits activation milestone — exit to expansion track; (b) customer churns — exit and enroll in win-back sequence

For each track, output:
- A step-by-step workflow diagram (described in numbered steps with branching clearly labeled)
- Email subject line and body hook for each step (not full emails — the framework, not the copy)
- The specific MAP workflow settings: enrollment trigger conditions (exact field/property logic), re-enrollment settings (yes/no and under what conditions), suppression list applied

---

**SECTION 4: LEAD ROUTING ARCHITECTURE**

Design the complete lead routing ruleset:

*4A. Routing Logic*
Define rules in priority order (first match wins):
1. Existing owner rule: if contact already has an assigned rep in CRM and rep is active — route to existing owner
2. ABM/named account rule: if contact's company is on the target account list — route to assigned AE, not SDR
3. Territory/geography rule: assign by rep territory (define territories and mapping)
4. Round-robin: for unowned contacts not matching rules 1-3 — round-robin across SDR pool
5. Overflow: if assigned rep has not followed up within [X hours] — escalate to sales manager via Slack alert + create overdue task in CRM

*4B. Routing Conditions by Lead Type*
- Demo request form submission: Priority HIGH. Route directly to AE (not SDR). SLA: contact within 5 minutes. If AE unavailable, auto-send calendar link via email within 2 minutes.
- Pricing page visit (no form) + engagement score above threshold: Priority MEDIUM. Create CRM task for assigned rep. SLA: 24 hours.
- Content download (ebook, guide): Priority LOW. Enroll in nurture Track 1. No immediate sales routing.
- Intent data spike (via 6sense/Bombora): Priority HIGH. Create task for AE + send rep a Slack alert with account summary.
- Chat conversation with email captured: Priority HIGH. Route to rep or SDR on-call within 15 minutes.

*4C. Edge Case Handling*
- Rep OOO: if CRM rep status = OOO, reroute to backup rep (define backup assignment logic — manager or round-robin?)
- Re-engaged previously disqualified contact: flag in CRM task with disqualification reason + context for rep to review before outreach
- Duplicate contact: do not route until dedup workflow resolves; alert marketing ops via Slack

---

**SECTION 5: WORKFLOW GOVERNANCE**

*5A. Naming Convention*
Define a naming structure every workflow must follow: [STAGE]-[TYPE]-[AUDIENCE]-[QUARTER]

Examples:
- MQL-Nurture-EnterpriseBuyers-2026Q1
- LEAD-Reengagement-AllPersonas-2026Q1
- CUST-Onboarding-SMB-2026Q1

Rules:
- No spaces — use CamelCase or hyphens
- Date = quarter of creation (not last-modified)
- Deprecated workflows: prefix with ZZ-ARCHIVE- so they sort to the bottom and are not re-activated

*5B. Folder Structure*
Organize your MAP into this hierarchy:
- /Nurture/TopOfFunnel
- /Nurture/MidFunnel
- /Nurture/Reengagement
- /Lifecycle/StageTransitions
- /Lifecycle/Routing
- /Transactional/PostPurchase
- /Transactional/EventRegistration
- /Operational/Scoring
- /Operational/DataNormalization
- /Operational/ListHygiene
- /ZZ-Archive

*5C. Workflow Audit Cadence*
Quarterly review checklist:
- Pull enrollment and completion rates for all active workflows — flag any with less than 5% completion or more than 40% drop-off at a single step
- Check for contacts stuck in workflows more than 90 days — investigate and manually resolve
- Review MQL score distribution — if more than 40% of MQLs have scores within 5 points of the threshold, the model may need recalibration
- Verify CRM sync is functioning for all stage transition workflows — spot-check 10 random contacts
- Archive any workflow not actively enrolling contacts and not scheduled to enroll in the next quarter
- Review email performance in each sequence — flag subject lines with open rate below 20% or CTR below 2% for A/B testing

---

## Example Input/Output

**Input Example:**
- Company: Veritas Analytics (fictional), B2B SaaS, Series B, $8M ARR
- Product: Business intelligence platform for mid-market retail and CPG brands
- ICP: VP of Analytics / Director of Business Intelligence at retail/CPG companies, 200-2,000 employees
- ACV: $48,000 | Sales cycle: 45-60 days
- MAP: HubSpot Marketing Hub Enterprise | CRM: Salesforce
- CRM sync: Real-time bi-directional via HubSpot-Salesforce native integration
- Monthly new leads: 420 | Monthly MQLs: ~38 (9% conversion — known to be too low)
- Enrichment: Clearbit | Intent: Bombora
- Personas: (1) "The Analyst" — Director of BI, builds the dashboards; (2) "The Buyer" — VP Analytics, owns the budget and decision; (3) "The IT Gatekeeper" — IT Director, pulled in for security/infra review

**Output Example (abbreviated):**

---

**Fit Score Model (excerpt):**

| Signal | Condition | Points |
|--------|-----------|--------|
| Industry | Retail, CPG, Consumer Goods | +25 |
| Industry | Manufacturing, Distribution | +15 |
| Industry | Healthcare, Finance, Tech | +5 |
| Industry | Education, Government, Non-profit | -20 |
| Employee count | 200-2,000 | +20 |
| Employee count | 2,001-10,000 | +15 |
| Employee count | Under 50 | -15 |
| Job title | VP Analytics / Head of BI / Chief Data Officer | +25 |
| Job title | Director Analytics / Director BI / Analytics Manager | +20 |
| Job title | Data Analyst / BI Developer | +10 |
| Job title | CTO / IT Director / VP Engineering | +5 |
| Job title | HR, Finance, Sales (non-buyer roles) | -10 |
| Tech stack (Clearbit) | Uses Snowflake, dbt, or Looker | +10 |
| Tech stack (Clearbit) | Uses SAP or Oracle BI | +15 (migration signal) |
| Email domain | Free domain (gmail, yahoo, hotmail) | -50 (hard disqualifier) |
| Geography | United States, Canada | +10 |
| Geography | UK, Australia, Germany | +5 |

MQL Fit Threshold: 40 points minimum
Fast-track override: Fit score 60+ plus any pricing page visit = instant MQL regardless of engagement score

---

**Lifecycle Stage: MQL to SAL Transition Workflow (step-by-step):**

Trigger: Contact property "Lifecycle Stage" changes to "MQL"

Step 1 — Data validation (immediate):
Check if company name is populated. If blank, enroll in Data Normalization workflow (Clearbit enrichment request) and hold MQL routing for up to 1 hour pending enrichment. If enrichment fails, route anyway with "Incomplete Profile" flag on contact record.
Check if the contact is already associated with an open Salesforce Opportunity. If yes, exit this workflow — do not create a duplicate routing task. Alert the assigned AE via Slack: "[Contact Name] from [Company] just re-engaged (MQL re-trigger). They're in your pipeline."

Step 2 — CRM task creation (immediate, after Step 1):
Create Salesforce task: Type = "MQL Follow-Up" | Priority = High | Due date = today + 1 business day | Description = "MQL triggered. Fit: [FitScore]. Engagement: [EngagementScore]. Last engagement: [MostRecentPageView or EmailClick]. Persona: [PersonaField]."
Assign to the rep determined by routing rules in Section 4.

Step 3 — Sales notification (immediate):
Send Slack DM to assigned rep via Zapier/Workato: "[Contact Name], [Title] at [Company] — just hit MQL. Score: [FitScore]/[EngagementScore]. Last action: [trigger event]. [Link to Salesforce record]"
Send internal email to rep with the same information plus link to the contact's HubSpot timeline.

Step 4 — SLA monitoring (24-hour delay):
Wait 24 business hours. Check whether the Salesforce Task status has changed to "Completed." If yes, exit workflow — rep has engaged. If no, escalate: create a new Salesforce task for the sales manager ("OVERDUE MQL — [Rep Name] has not followed up on [Contact Name] from [Company]. Task was due [Date].") and send the sales manager the same alert via Slack.

Step 5 — Auto-nurture safety net (48 hours from trigger):
If the contact is still in "MQL" lifecycle stage and no CRM activity has been logged in the last 48 hours, enroll the contact in Track 2 (Mid-Funnel Nurture) as a safety net to prevent the MQL from going cold while awaiting sales follow-up. Do not send sales another notification — avoid rep fatigue.

Step 6 — SAL transition (triggered by rep action):
When a Salesforce Opportunity is created for this contact, HubSpot lifecycle stage auto-updates to "SAL" via native sync, this workflow exits, and the contact enrolls in the SAL-Lifecycle-StageTransition workflow.

---

## Success Metrics
- MQL-to-SAL conversion rate should reach 40-60% within 90 days of implementation (industry benchmark for a healthy routing and nurture system combined)
- Lead scoring accuracy: track the "MQL to Disqualified" rate — if more than 30% of MQLs are immediately disqualified by sales, scoring thresholds need adjustment
- Workflow health: no active workflow should have a drop-off rate above 35% at a single step — that step has a structural problem
- Sales SLA compliance: more than 90% of MQL routing tasks completed within 24 business hours
- Nurture influence rate: at least 20% of closed-won deals should have touched a nurture workflow email in the 90 days prior to close
- Score inflation check: monthly — if more than 15% of the active contact database carries a behavioral score above 50, score decay is not aggressive enough and must be recalibrated

## Related Prompts
- [Marketing Technology Stack Audit Engine](./Marketing-Technology-Stack-Audit-Engine.md)
- [Marketing Attribution ROI Engine](../Campaign-Performance-Analysis/Marketing-Attribution-ROI-Engine.md)
- [Customer Segmentation & Behavioral Targeting Engine](../Advanced-Marketing-Intelligence/Customer-Segmentation-Behavioral-Targeting-Engine.md)
- [Lead Nurturing Workflows](../../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Lead-Nurturing-Workflows.md)

## Integration Tips
- **HubSpot**: Use contact-based active lists as the dynamic segmentation layer for each nurture track. Set workflow enrollment triggers to list membership rather than individual property conditions where possible — this makes it easier to audit who is in each track and manually add or remove contacts without touching workflow logic.
- **Salesforce**: Map every lifecycle stage to a corresponding Salesforce Lead Status or Contact Status field. Use the HubSpot-Salesforce native sync or a Workato recipe to keep them bidirectionally in sync. A contact that sales manually moves to "Disqualified" in Salesforce should automatically trigger re-engagement enrollment in HubSpot — not require a manual marketing ops step.
- **Slack**: Use Zapier or Make.com to send workflow-triggered Slack alerts to a #sales-mql-alerts channel or rep DMs. Include a direct link to the CRM record in every alert. Reps who receive alerts with one-click CRM access follow up within 2 hours at 3x the rate of those who must navigate to the record manually.
- **Google Sheets / Notion**: Maintain a Workflow Registry — one row per active workflow with columns: Name, Stage, Audience, Trigger, Active Enrollments, Last Reviewed, Owner. Review this registry in your weekly MOps standup. It prevents workflow sprawl and makes quarterly audits 10x faster.
- **Clay**: For high-value MQL routing, run a Clay enrichment waterfall (Apollo, then Clearbit, then LinkedIn) on every new MQL before the CRM task is created. A rep who receives an MQL alert with a complete firmographic profile follows up within 2 hours at 2x the rate of a rep who receives an alert with missing fields.
- **6sense / Bombora**: Feed intent surge data into the lead scoring model as a real-time score boost. When 6sense detects an account in the "Buying Stage" for your category keywords, add a +25 engagement score boost to all contacts at that account — even if they have not visited your website. This surfaces in-market pipeline that would otherwise wait 30-60 days to organically hit MQL threshold.

## Troubleshooting

**Problem: Contacts are hitting MQL threshold but sales is rejecting 50%+ as unqualified**
Solution: Your fit score weighting is too permissive — specifically, job title scoring is likely too broad or company size bands are not ICP-specific enough. Pull a 3-month sample of disqualified MQLs and export their fit score breakdown. Identify the highest-scoring attributes among the disqualified cohort. Reduce those attribute weights by 30-40%, raise the MQL threshold by 5-10 points, and re-run the model against historical data before deploying to production. Also audit whether fast-track MQL rules are overriding fit score minimums too aggressively — a pricing page visit alone is not a sufficient signal for accounts that fall outside ICP.

**Problem: Nurture email open rates are below 18% across all tracks**
Solution: The issue is almost certainly the sender identity and subject line, not the nurture architecture. Test three changes in sequence: (1) send from a real person's name and email address (e.g., "Sarah from Veritas Analytics") rather than a brand address — this typically lifts open rates 15-25% on its own; (2) audit list health — if bounce rate exceeds 2% or spam complaint rate exceeds 0.1%, inbox placement is degrading and you must reduce send volume before optimizing copy; (3) check whether contacts are enrolled in multiple simultaneous workflows receiving more than 2 marketing emails per week — implement a global frequency cap so no contact receives more than 2 marketing sends in any 7-day window, regardless of workflow enrollment count.

**Problem: Lead routing is creating duplicate Salesforce tasks and reps are ignoring alerts**
Solution: Add a deduplication check at the routing trigger. Before creating any task, the workflow must verify: (1) does an open task of type "MQL Follow-Up" already exist on this contact record? If yes, skip task creation and update the existing task's due date instead; (2) has sales logged any activity on this contact in the last 5 business days (check Last Activity Date in Salesforce)? If yes, skip routing entirely — the rep is already engaged. Over-alerting trains reps to ignore the channel. Fewer, higher-confidence signals drive faster follow-up than a constant stream of low-signal noise.

## Version History
- v1.0: Initial creation (auto-generated)
