# Marketing Technology Stack Audit Engine - Full MarTech Rationalization & Optimization System

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** martech, operations, analytics, b2b, saas, strategy, budget, automation, integration

## Overview
This prompt takes your complete marketing technology inventory — tools, costs, owners, and usage data — and produces a boardroom-ready audit: redundancy analysis, utilization scoring, integration gap mapping, consolidation roadmap, and projected cost savings. Use it annually, before budget season, or when martech spend exceeds 15-20% of the total marketing budget.

## Quick Copy-Paste Version

You are a marketing technology strategist and MarTech advisor. Audit my current marketing technology stack and produce a full rationalization plan.

My current stack (list each tool, its monthly cost, primary function, and rough usage level 1-10):
[Paste your tool list here, e.g.:
- HubSpot Marketing Hub: $3,200/mo — CRM/marketing automation — usage: 8/10
- Salesforce Sales Cloud: $2,400/mo — CRM/sales — usage: 9/10
- Marketo: $1,800/mo — email automation — usage: 4/10
- Drift: $1,500/mo — conversational marketing — usage: 3/10
- Hotjar: $99/mo — heatmaps/session recording — usage: 5/10
- Semrush: $449/mo — SEO/competitor research — usage: 7/10
- Sprout Social: $599/mo — social media management — usage: 6/10
- Clearbit: $12,000/yr — data enrichment — usage: 4/10
- Bombora: $3,000/mo — intent data — usage: 3/10
- Loom: $99/mo — async video — usage: 8/10]

My company context:
- Business type: [B2B SaaS / B2C / D2C / agency]
- Team size (marketing): [X] people
- Annual marketing budget: $[X]
- Primary go-to-market motion: [inbound / outbound / PLG / ABM]

Deliver:
1. A tool-by-tool assessment: keep / consolidate / cut / upgrade for each tool
2. Redundancy pairs — tools doing the same job
3. Critical gaps — capabilities we are missing
4. Consolidation opportunities with estimated annual savings
5. A 90-day rationalization roadmap with prioritized actions
6. The ideal stack for a company of my size and motion

## Advanced Customizable Version

ROLE:
You are a Senior MarTech Consultant and Marketing Operations Architect with 15 years of experience auditing and optimizing marketing technology stacks for B2B SaaS companies at the Series A through IPO stages. You have evaluated 200+ stacks across companies spending $50K to $5M/year on MarTech. You use frameworks like Gartner's MarTech Category Model, the Capability Maturity Model, and vendor TCO analysis to produce ruthlessly prioritized recommendations that balance functionality, integration quality, and cost efficiency. Your recommendations are always actionable — you never suggest cutting a tool without naming its replacement or confirming the function is no longer needed.

OBJECTIVE:
Conduct a comprehensive audit of the provided marketing technology stack. Produce a structured rationalization report that: identifies waste and redundancy, surfaces capability gaps, scores each tool against utilization and strategic fit, and delivers a phased consolidation roadmap with quantified cost and productivity impact.

CONTEXT — COMPANY PROFILE:

Company information:
- Company name: [Your Company]
- Business model: [B2B SaaS / B2C eCommerce / D2C / Marketplace / Professional Services]
- Stage: [Seed / Series A / Series B / Growth / Enterprise]
- Industry vertical: [Fintech / HR Tech / DevTools / Healthcare / Retail / Other]
- Marketing team size: [X] full-time employees
- Annual marketing budget: $[X]
- MarTech budget as % of marketing budget: [X]%
- Primary GTM motion: [Inbound-led / Outbound-led / Product-Led Growth / ABM / Channel/Partner]
- Primary ICP: [SMB / Mid-Market / Enterprise / Consumer]
- CRM system of record: [HubSpot / Salesforce / Pipedrive / Other]
- Data warehouse / BI tool: [Snowflake+Looker / BigQuery+Tableau / None / Other]

Current stack inventory (for each tool provide all fields you have):
Tool Name | Category | Monthly Cost | Annual Cost | Primary Owner | Team Usage % | Last Evaluated | Integration Status | Notes
[Paste your full inventory here]

If you do not have all fields, provide what you have. Estimate where needed.

Stack performance context:
- Current MQL-to-SQL conversion rate: [X]% (industry avg: 13-27% for B2B SaaS)
- Marketing-sourced pipeline as % of total pipeline: [X]%
- Campaign time-to-launch average: [X] days
- Data hygiene score (% of contacts with complete profile): [X]%
- Biggest operational pain points (rank top 3):
  1. [e.g., "CRM and email platform do not sync in real time"]
  2. [e.g., "No single source of truth for attribution"]
  3. [e.g., "Too many manual steps in lead routing"]

CONSTRAINTS:
- Flag vendor contract lock-in risk before recommending cuts (note if the tool is mid-contract)
- Never recommend removing a tool that is the CRM system of record without a full migration plan
- Consolidation recommendations must account for data migration complexity
- Identify tools where the team has deep institutional knowledge — switching cost matters
- All cost savings estimates should be conservative (use the lower bound)
- Recommendations must be actionable by a marketing ops team of [X] people without external consultants

OUTPUT STRUCTURE — DELIVER ALL SECTIONS:

**1. Stack Health Scorecard**
Create a table with every tool scored on:
- Utilization (1-10): How actively is it being used vs. its licensed capacity?
- Strategic Fit (1-10): Does it align with current GTM motion and ICP?
- Integration Quality (1-10): How well does it connect to the stack's core data layer?
- Cost Efficiency (1-10): Value delivered relative to cost vs. best available alternative?
- Composite Score: Weighted average (Utilization 35%, Strategic Fit 30%, Integration 20%, Cost 15%)
- Verdict: KEEP / OPTIMIZE / CONSOLIDATE / CUT / EVALUATE

**2. Redundancy Map**
- Identify all tool pairs or groups with overlapping functionality
- For each redundancy: name the primary tool (keep) and the redundant tool (migrate or cut)
- Estimate annual savings from each consolidation
- Flag which redundancies are intentional (e.g., backup tools) vs. accidental

**3. Capability Gap Analysis**
Using the Gartner Marketing Technology Landscape categories, identify which core capabilities the current stack is missing or underserving:
- Content management and personalization
- Customer data platform (CDP) / unified customer view
- Conversational marketing and chatbots
- Review and social proof automation
- Revenue intelligence / conversation analytics
- Marketing attribution (multi-touch)
- Account intent data
- Marketing asset management (DAM)
Rate each gap: CRITICAL (revenue impacting) / MODERATE (efficiency impacting) / NICE-TO-HAVE

**4. Total Cost of Ownership (TCO) Analysis**
- Current annual MarTech spend (licenses only)
- Estimated hidden costs: integration maintenance, training time, data migration, admin overhead
- True TCO estimate: licenses + hidden costs
- Benchmark: industry median MarTech spend for a company of this size and stage
- Rationalization dividend: projected annual savings if all CONSOLIDATE and CUT recommendations are executed
- Reinvestment priority: where freed budget should flow for maximum pipeline impact

**5. Vendor Risk Assessment**
- Tools with single-vendor dependency risk (no viable substitute within 90 days)
- Tools being acquired, sunset, or showing product decay signals
- Tools where you are likely overpaying vs. market rate (flag for renegotiation)
- Tools approaching contract renewal (negotiate before renewal date, not at it)

**6. The Ideal Stack Blueprint**
Based on the company's stage, GTM motion, team size, and budget, design the optimal stack:
- Core stack: Must-have tools (non-negotiable for current stage)
- Growth stack: Tools to add when ARR exceeds [X] or team exceeds [X] people
- Consolidation opportunities: Where one platform can replace two or more point solutions
- For each recommended addition or change: name the specific vendor, estimated cost, and migration path
- Build the stack as a visual hierarchy: Data Layer → Engagement Layer → Analytics Layer → Orchestration Layer

**7. 90-Day Rationalization Roadmap**
Phase 1 (Days 1-30): Quick wins — cuts and consolidations with no data migration required
Phase 2 (Days 31-60): Medium complexity — consolidations requiring data migration or team retraining
Phase 3 (Days 61-90): Strategic moves — platform upgrades or new capability additions
For each action: Owner role, effort estimate (hours), cost impact, and risk level (Low/Med/High)

**8. Stakeholder Communication Plan**
- Talking points for presenting the audit to the CFO (frame as cost optimization + capability upgrade)
- Talking points for presenting to the marketing team (frame as efficiency gain, not tool removal)
- How to handle vendor pushback when downgrading or canceling
- Template email for notifying internal teams of tool sunset timeline

## Example Input/Output

**Input Example:**
- Company: Meridian Labs (fictional), B2B SaaS HR tech, Series B, $12M ARR
- Marketing team: 8 people
- Annual marketing budget: $2.1M
- MarTech budget: $340K/year (16.2%)
- GTM motion: Inbound + ABM hybrid
- CRM: HubSpot Marketing Hub + Salesforce dual stack

Stack:
- HubSpot Marketing Hub Enterprise: $38,400/yr — marketing automation — 7/10 usage
- Salesforce Sales Cloud: $28,800/yr — CRM — 9/10 usage
- Marketo Engage: $21,600/yr — email nurture — 4/10 usage (legacy, partially migrated to HubSpot)
- Drift: $18,000/yr — chatbot/conversational — 3/10 usage
- 6sense: $36,000/yr — ABM/intent — 5/10 usage
- Bombora: $18,000/yr — intent data — 3/10 usage
- Semrush: $5,400/yr — SEO — 8/10 usage
- Sprout Social: $7,200/yr — social management — 5/10 usage
- Loom: $1,188/yr — video — 9/10 usage
- Clearbit: $12,000/yr — data enrichment — 4/10 usage (overlaps with 6sense enrichment)
- Hotjar: $1,188/yr — UX analytics — 6/10 usage
- Canva Teams: $3,000/yr — design — 9/10 usage
- Vidyard: $7,200/yr — video hosting/analytics — 3/10 usage (overlaps with Loom)
- Outreach: $15,600/yr — sales engagement — 8/10 usage (owned by sales)
- Chili Piper: $9,600/yr — meeting scheduling — 7/10 usage

**Output Example (abbreviated):**

Stack Health Scorecard (top findings):

| Tool | Utilization | Strategic Fit | Integration | Cost Eff. | Score | Verdict |
|------|-------------|---------------|-------------|-----------|-------|---------|
| Salesforce Sales Cloud | 9 | 10 | 9 | 8 | 9.1 | KEEP |
| HubSpot Marketing Hub | 7 | 9 | 8 | 7 | 7.9 | KEEP + OPTIMIZE |
| Marketo Engage | 4 | 3 | 4 | 2 | 3.4 | CUT (migrate to HubSpot) |
| 6sense | 5 | 8 | 6 | 5 | 6.1 | KEEP + OPTIMIZE |
| Bombora | 3 | 6 | 4 | 3 | 3.9 | CONSOLIDATE into 6sense |
| Clearbit | 4 | 5 | 5 | 3 | 4.3 | CONSOLIDATE into 6sense |
| Vidyard | 3 | 4 | 3 | 2 | 3.1 | CUT (use Loom) |
| Drift | 3 | 5 | 4 | 2 | 3.6 | EVALUATE (HubSpot chatbot may replace) |

Top Redundancies Identified:

1. Marketo + HubSpot Marketing Hub — duplicate email automation. Annual savings on elimination: $21,600. Migration effort: 60 hours. Verdict: Sunset Marketo. All nurture sequences are already partially rebuilt in HubSpot.

2. Bombora + 6sense intent data — 6sense ingests Bombora data natively. You are paying for both the raw feed and the platform that processes it. Annual savings: $18,000. Action: confirm 6sense contract includes Bombora co-op data; cancel Bombora direct.

3. Clearbit + 6sense enrichment — 6sense enriches accounts with firmographic and contact data natively. Clearbit is being used only on 2 landing pages. Annual savings: $12,000. Action: rebuild those 2 Clearbit forms using HubSpot progressive profiling + 6sense enrichment.

4. Vidyard + Loom — both used for video, but Vidyard is underused at 3/10 and the team defaults to Loom. Annual savings: $7,200. Action: export Vidyard analytics data, migrate hosted videos to YouTube unlisted, cancel Vidyard.

Rationalization Dividend:
- Conservative annual savings from executing all CUT and CONSOLIDATE recommendations: $58,800
- As % of current MarTech budget: 17.3%
- Recommended reinvestment: $30K into 6sense seat expansion (cover full AE team for ABM plays) + $28K into a CDP evaluation (Segment or RudderStack) to solve the HubSpot/Salesforce data sync pain point

30-Day Quick Wins (Phase 1):
1. Cancel Vidyard — zero migration needed, save $7,200. Owner: Marketing Ops. Effort: 2 hours.
2. Cancel Bombora direct — call 6sense to confirm intent co-op data is included in existing contract. Save $18,000. Owner: Marketing Ops. Effort: 1 hour.
3. Freeze Marketo new campaign builds — no new investment in Marketo. Existing sequences run until migration is complete in Phase 2. Owner: Marketing Ops Lead.
4. Audit Clearbit usage — pull API log to confirm only 2 landing pages use Clearbit. If confirmed, rebuild in HubSpot and cancel Clearbit at renewal (next renewal: March 14). Owner: RevOps. Effort: 4 hours.

## Success Metrics
- Audit delivers at minimum 10% reduction in annual MarTech spend without removing any capability rated CRITICAL
- Every CONSOLIDATE recommendation includes a named replacement and data migration path
- Roadmap is fully executed within 90 days by an ops team of 2 without external consultants
- Stack Health Scorecard composite average improves by at least 1.5 points vs. current state after rationalization
- Campaign time-to-launch decreases by 20%+ due to reduced tool switching and integration complexity
- CFO approves reinvestment of rationalization savings within one budget cycle

## Related Prompts
- [Marketing Budget Allocation Engine](../../01_CMO-&-Leadership/Strategy-&-Planning/Marketing-Budget-Allocation-Engine.md)
- [Marketing Performance Dashboard Generator](../KPI-Dashboard-Creation/Marketing-Performance-Dashboard-Generator.md)
- [Marketing Attribution ROI Engine](../Campaign-Performance-Analysis/Marketing-Attribution-ROI-Engine.md)
- [Advanced Marketing Analytics Intelligence Platform](../Advanced-Marketing-Intelligence/Advanced-Marketing-Analytics-Intelligence-Platform.md)

## Integration Tips
- **HubSpot:** Before running the audit, export your HubSpot "Connected Apps" list (Settings > Integrations > Connected Apps). Paste this into the prompt as your integration inventory. It reveals which tools have live data connections vs. which are orphaned.
- **Salesforce:** Pull the "Installed Packages" list from Setup > Apps > Packaging > Installed Packages. This shows every third-party tool with a Salesforce connection — often includes tools the marketing team forgot they licensed.
- **Google Sheets:** Build a live MarTech inventory tracker with columns: Tool, Category, Owner, Monthly Cost, Contract End Date, Utilization Score, Last Reviewed. Run this audit quarterly by pasting the latest sheet into the prompt.
- **Notion:** Create a "MarTech Stack" database in Notion and use the audit output to tag each tool with its verdict (Keep/Consolidate/Cut). Link each tool page to its vendor contract in Google Drive for one-click renewal management.
- **Zapier / Make.com:** After the audit, build a Zap that fires 60 days before each tool's contract renewal date (sourced from the Google Sheet) and sends a Slack reminder to the Marketing Ops lead to re-run the utilization score before auto-renewing.
- **Claude API automation:** Export billing data from each SaaS vendor monthly, aggregate into a structured JSON object, and run this prompt via the Claude API on a quarterly cadence to auto-generate a fresh audit report and post it to a Notion database entry.

## Troubleshooting

**Issue: The AI recommends cutting a tool that is deeply embedded in critical workflows**
Fix: Add a "critical dependencies" section to your context listing tools that cannot be removed without a major migration (e.g., "Marketo is integrated with 14 Salesforce workflows — treat as high-migration-cost"). The audit will then flag the tool as EVALUATE instead of CUT and include a migration complexity warning.

**Issue: Cost savings estimates are too high or too low for your actual vendor contracts**
Fix: The AI uses list pricing as a baseline. Enterprise contracts often carry 30-60% discounts. Add your actual contract values to the inventory. Conversely, if you are on individual user plans and scaling, the savings estimates may be conservative — include current user count and projected headcount growth so the model can calculate true per-seat economics.

**Issue: The ideal stack blueprint recommends tools you have already evaluated and rejected**
Fix: Add an "evaluated and rejected" section to your context (e.g., "We evaluated Segment in 2024 and rejected it due to engineering bandwidth required for implementation"). The AI will suggest alternatives or flag the same tool with a note about the previously identified blockers.

## Version History
- v1.0: Initial creation (auto-generated)
