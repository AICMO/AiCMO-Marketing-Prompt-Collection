# CRM & Revenue Operations Intelligence Engine - Full-Funnel Pipeline Health & RevOps Optimization

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** revops, crm, salesforce, hubspot, pipeline-management, revenue-operations, forecasting, data-hygiene

## Overview
Audits your CRM configuration, pipeline health, and Revenue Operations (RevOps) architecture to produce a prioritized remediation plan, forecasting model, and automation blueprint. Use it when pipeline accuracy is poor, marketing-to-sales handoffs are leaking revenue, or leadership is demanding better forecast confidence.

## Quick Copy-Paste Version

You are a senior Revenue Operations consultant with 12+ years optimizing CRM systems and go-to-market alignment at B2B SaaS companies with $5M–$200M ARR.

Audit and optimize our CRM and RevOps setup:

CRM platform: [Salesforce / HubSpot / Pipedrive / other]
Current ARR: $[X]
Average deal size: $[X]
Sales cycle length: [X days average]
Number of AEs: [X]
Pipeline coverage ratio: [X:1 or "unknown"]
Monthly MQLs: [X]
MQL-to-SQL conversion rate: [X% or "unknown"]
Biggest current pain: [e.g., forecast misses, dirty data, slow handoffs, duplicate records]

Deliver:
1. CRM data health score (0–100) based on what I've shared, with top 3 data quality issues and fixes
2. Pipeline stage audit: Identify which stages are likely bottlenecks based on typical SaaS benchmarks for my deal size and cycle length
3. Marketing-to-sales SLA design: MQL criteria, 24-hour response protocol, and recycle rules
4. Forecasting model recommendation: Commit/Best Case/Pipeline categories with AI-assisted confidence scores
5. Top 5 automation workflows to implement immediately in [CRM platform] with step-by-step logic
6. RevOps KPI dashboard: 10 metrics to track weekly with target ranges for my ARR tier
7. 90-day RevOps remediation roadmap with sequenced priorities

Be specific — include actual field names, workflow trigger logic, and metric benchmarks. No generic advice.

## Advanced Customizable Version

ROLE: You are a VP of Revenue Operations with a track record of taking Series B/C SaaS companies from chaotic, gut-feel forecasting to data-driven pipeline management. You have deep expertise in CRM architecture (Salesforce and HubSpot), marketing-sales alignment, and building RevOps systems that compound — where clean data and tight processes directly increase revenue velocity.

CONTEXT:
Company: [Company Name]
CRM platform: [Salesforce / HubSpot CRM / Pipedrive / other]
Current ARR: $[X] | Growth target: $[X] in 12 months
Average contract value (ACV): $[X]
Sales motion: [PLG / inbound-led / outbound-led / channel-led / enterprise]
Sales team: [X] AEs, [X] SDRs, [X] SEs
Marketing team: [X] people, primarily using [HubSpot Marketing / Marketo / Pardot / other]
Sales cycle: [X] days average, [X] days enterprise
Current CRM data quality issues: [e.g., duplicate contacts, missing company data, inconsistent stage usage, stale opportunities]
Current forecast method: [manual gut call / stage-weighted / AI-assisted / none]
Current pipeline coverage: [X:1 or unknown]
Integration stack: [e.g., Outreach, Gong, Clearbit, ZoomInfo, Slack, Notion]
Key friction points: [e.g., AEs not logging activity, MQLs going cold, poor stage-to-stage conversion visibility]
Board/exec reporting cadence: [weekly / monthly / quarterly]

OBJECTIVE: Design a complete Revenue Operations intelligence system that (1) restores CRM data integrity, (2) creates airtight marketing-to-sales-to-success handoff protocols, (3) builds a defensible forecasting methodology, and (4) generates a self-improving analytics loop — all configured specifically for our CRM platform and GTM motion.

DELIVERABLES:

1. CRM ARCHITECTURE AUDIT
   - Pipeline stage audit: Evaluate each stage for clarity, exit criteria, and benchmark conversion rates for our ACV tier
   - Required vs. optional field mapping: Which fields to enforce at each stage, with validation rules
   - Object relationship audit: Contact ↔ Account ↔ Opportunity ↔ Activity model — identify where data breaks down
   - Duplicate prevention strategy: Matching rules, merge logic, and ongoing deduplication workflow
   - Scoring model: Lead score + engagement score with weighted criteria and threshold triggers

2. MARKETING-TO-SALES HANDOFF PROTOCOL
   - MQL definition: Specific behavioral + demographic criteria for our ICP using [Lead Scoring fields]
   - SLA design: Response time SLAs by lead source and tier, escalation paths, and breach alerts
   - Routing logic: Round-robin, territory, or account-based routing rules with specific workflow triggers
   - Recycle & disqualification rules: When and how MQLs re-enter nurture vs. go to dead
   - Feedback loop: How sales signals (call dispositions, stage movements) flow back to marketing for attribution

3. FORECASTING METHODOLOGY
   - Forecast category system: Commit / Best Case / Pipeline / Omitted — with specific criteria for each
   - Confidence scoring: How to layer in deal age, activity recency, stakeholder engagement (using Gong / Outreach signals if applicable), and historical stage conversion rates
   - Rollup process: Rep → Manager → VP → CRO rollup cadence with inspection questions for each layer
   - Early warning system: Identify deals at risk using [X] signals (inactivity, single-threaded, compressed timeline)
   - Forecast accuracy benchmark: Target ±10% accuracy by month 3, ±5% by month 6

4. CRM AUTOMATION BLUEPRINT
   For each of the following, specify: Trigger → Condition logic → Action → Outcome metric
   - Lead assignment and round-robin rotation workflow
   - Stale opportunity alert (no activity in [X] days by stage)
   - MQL-to-SQL conversion notification with context bundle to AE
   - Stage progression alert to customer success for post-close handoff
   - Closed-lost auto-enrollment into re-engagement nurture sequence (30-day delay)
   - Executive stakeholder engagement drop alert (no contact with VP+ in 14 days on enterprise deals)

5. REVOPS KPI COMMAND CENTER
   Weekly metrics (with target ranges for our ARR tier):
   - Pipeline coverage ratio (target: 3–4x for inbound, 4–5x for outbound)
   - Stage conversion rates (MQL→SQL, SQL→Opportunity, Opportunity→Closed Won)
   - Average sales cycle by segment, lead source, and AE
   - New pipeline created vs. pipeline consumed
   - Win rate by competitor, channel, and deal size
   - Forecast accuracy (actual vs. called, rolling 90-day)
   - Time-to-first-meaningful-activity (SDR speed to lead)
   - AE activity efficiency (meetings held per opportunity per stage)
   - Expansion revenue as % of net new ARR
   - Marketing-influenced pipeline % (with attribution model specified)

6. DATA GOVERNANCE FRAMEWORK
   - CRM admin responsibilities vs. RevOps vs. sales ops (RACI matrix)
   - Data entry standards documentation (field-by-field guide for AEs)
   - Monthly data hygiene audit checklist (automated report + manual review items)
   - Contact and account enrichment strategy: When to enrich, with which tool (Clearbit/ZoomInfo/Apollo), triggered automatically on record creation

7. 90-DAY REVOPS TRANSFORMATION ROADMAP
   Week 1–2: Foundation — CRM audit, quick wins (kill duplicate records, fix required fields, enforce stage exit criteria)
   Week 3–4: Process — Implement MQL SLA, routing rules, and stale deal alerts
   Week 5–8: Intelligence — Build forecast methodology, activate scoring models, launch KPI dashboard
   Week 9–12: Optimization — Analyze first 60 days of data, calibrate scoring, train team, activate expansion triggers
   For each phase: specific actions, owners, success criteria, and tools required

## Example Input/Output

**Input:**
- CRM platform: HubSpot CRM
- ARR: $4.2M, growing toward $8M target
- ACV: $28,000
- Sales motion: Inbound-led with SDR outbound overlay
- Sales team: 4 AEs, 2 SDRs
- Sales cycle: 45 days average, 90 days enterprise (>$50K)
- Data quality issues: Duplicate contacts, AEs not logging activities, no clear MQL definition
- Forecast method: AE gut-feel submitted via Slack every Friday
- Current pipeline coverage: Unknown (no tracking)
- Integrations: HubSpot Marketing Hub, Outreach, Gong, Slack

**Output (excerpt):**

**CRM Architecture Audit:**

*Pipeline Stage Diagnosis (with HubSpot-specific fix actions):*

| Stage | Current Usage | Benchmark Conversion ($28K ACV) | Issue | Fix |
|---|---|---|---|---|
| MQL | Undefined | — | No entry criteria → everything is an MQL | Define: 40+ lead score OR demo request from ICP company |
| SQL | Ad hoc | 35–45% MQL→SQL | AEs accept/reject without logging reason | Add required "Disqualification Reason" field with picklist |
| Discovery Call Held | Rarely used | — | Stage skipped; no activity timestamp | Enforce: stage advance only after first Gong call logged |
| Proposal Sent | Mixed usage | 60–70% SQL→Proposal | No proposal date tracked | Add required field: Proposal Date; trigger 5-day follow-up |
| Negotiation | Often skipped | — | Deals jump to Closed Won; no visibility | Require deal stage entry when discount >10% is requested |
| Closed Won | ✓ | 25–35% overall | Clean | Trigger CS handoff sequence on stage change |

*Top 3 Data Quality Fixes (Week 1):*
1. **Duplicate contact merge**: Run HubSpot's native duplicate management tool → filter by email domain → merge 400+ estimated duplicates → enable "Prevent duplicate contacts" setting going forward
2. **Required field enforcement**: Make Company Name, Job Title, Lead Source, and ICP Fit (Yes/No/Unknown) required at Contact creation — estimated 60% of current contacts missing ≥1 field
3. **Activity logging via Outreach**: Configure Outreach → HubSpot bi-directional sync so all email, call, and meeting activity auto-logs to CRM; AEs should not manually log — remove that expectation entirely

**MQL-to-SQL SLA Design:**
- MQL triggers routing: Lead score ≥40 OR demo form submission from company with ≥50 employees
- SDR response SLA: First touch within 4 business hours (target: 1 hour for demo requests)
- Routing logic: Round-robin among 2 SDRs; if lead's company matches active AE account → route directly to AE
- HubSpot workflow: `IF (Lead Score ≥ 40 OR Form = "Request Demo") AND (Company Size ≥ 50) THEN → Create Task for SDR [round-robin] → Notify via Slack #sdr-leads → Set "MQL Date" timestamp`
- SLA breach alert: If task not completed in 4 hours → escalate to SDR manager via Slack
- Recycle rule: If no SQL conversion in 14 days → return to marketing nurture track "Post-MQL Re-Engagement" (5-email sequence, 3-week cadence)

**Forecasting Model:**
- Commit: AE has verbal confirmation from economic buyer, next step is legal/procurement, close date ≤30 days — forecast at 85% probability
- Best Case: Active evaluation, multi-threaded (≥2 stakeholders engaged), proposal sent, close date ≤45 days — forecast at 50%
- Pipeline: Discovery held, needs identified, no proposal — forecast at 20%
- AI confidence overlay: Gong deal risk score + days since last activity + stakeholder tier → adjust AE category up/down by one tier if signals diverge by >30%

## Success Metrics
- Forecast accuracy improves from baseline to ±15% within 60 days, ±10% within 90 days
- MQL response time drops to <4 hours (tracked via HubSpot SLA reports)
- CRM data completeness score reaches ≥85% on required fields within 30 days
- Pipeline coverage visibility established (weekly tracking in RevOps dashboard)
- Win rate visibility by source, segment, and competitor within 45 days
- AE activity logging compliance ≥90% (automated, not manual) within 30 days

## Related Prompts
- [Marketing Attribution & ROI Engine](../../05_Analytics-&-Marketing-Operations/Campaign-Performance-Analysis/Marketing-Attribution-ROI-Engine.md)
- [Marketing Automation Workflow Architecture Engine](../../05_Analytics-&-Marketing-Operations/MarTech-Stack-Optimization/Marketing-Automation-Workflow-Architecture-Engine.md)
- [Predictive Revenue Forecasting Engine](../../05_Analytics-&-Marketing-Operations/Advanced-Marketing-Intelligence/Predictive-Revenue-Forecasting-Engine.md)
- [Sales Discovery Call Intelligence Engine](../../02_Product-Marketing/Sales-Enablement-Content/Sales-Discovery-Call-Intelligence-Engine.md)

## Integration Tips
- **HubSpot**: Build all workflows in Workflows → use "Deal Stage is Known" and "Last Activity Date" as primary triggers; connect to Slack via native HubSpot-Slack integration for real-time alerts
- **Salesforce**: Use Process Builder (or Flow) for stage-based alerts; deploy Einstein Deal Insights for AI confidence scoring overlay; use Reports + Dashboards for KPI command center
- **Gong**: Configure Deal Warnings in Gong to push at-risk signals to CRM custom fields via Gong's HubSpot/Salesforce integration — no manual entry required
- **Outreach**: Enable bi-directional sync so all sequences, calls, and emails log to CRM automatically; use Outreach's "Sequence Finished" trigger to auto-update CRM contact status
- **Slack**: Create #revops-alerts channel; route stale deal, SLA breach, and forecast deviation alerts there via Zapier or native integrations
- **Google Sheets / Looker Studio**: Export weekly pipeline snapshot via HubSpot/Salesforce API to a Google Sheet; build Looker Studio dashboard on top for exec-level visibility without CRM access required

## Troubleshooting
- **AEs resist logging activity**: Don't ask AEs to manually log — configure Outreach or your sequencing tool to auto-sync to CRM. If AEs aren't using a sequencing tool, that's the prior problem to solve. Every rep should have 100% of their email and call activity auto-captured.
- **Forecast categories inconsistently applied**: Run a 30-minute calibration session with each AE using real deals from their pipeline. Walk through 3–4 examples together, applying your criteria, until you get consistent interpretation. Document edge cases in a RevOps Notion page linked from CRM.
- **MQL volume overwhelms SDR capacity**: Add a "priority MQL" tier (score ≥60 OR enterprise company size) that gets same-day response vs. standard SLA for score 40–59. This prevents the best leads from aging while SDRs work lower-priority volume. Adjust thresholds monthly based on conversion data.

## Version History
- v1.0: Initial creation (auto-generated)
