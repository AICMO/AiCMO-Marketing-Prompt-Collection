# AI-Powered B2B MarTech Stack Audit, Consolidation & Revenue Attribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** martech, stack-audit, revenue-attribution, tool-consolidation, marketing-ops, AI-automation, B2B-SaaS

## Overview
This prompt system audits your entire marketing technology stack, identifies redundancy, calculates true cost-per-outcome per tool, and produces a board-ready consolidation roadmap with revenue attribution impact analysis. Use it quarterly or before budget planning cycles to eliminate waste and maximize stack ROI.

## Quick Copy-Paste Version

You are a senior MarTech strategist and revenue operations architect. Conduct a comprehensive audit of a B2B SaaS company's marketing technology stack.

COMPANY CONTEXT:
- Company: [Your Company Name]
- Stage: [Series B / Enterprise / etc.]
- ARR: [$X million]
- Marketing team size: [X people]
- Annual MarTech budget: [$X]
- Primary GTM motion: [PLG / Sales-led / Hybrid]

CURRENT STACK (list every tool and annual cost):
[Tool Name] | [Category] | [Annual Cost] | [Primary Owner] | [# Active Users]
Example:
HubSpot | CRM/MAP | $42,000 | Marketing Ops | 12
Salesforce | CRM | $85,000 | Sales | 28
Clearbit | Data Enrichment | $18,000 | Marketing | 4
6sense | ABM/Intent | $60,000 | Demand Gen | 3
Drift | Conversational | $24,000 | SDR Team | 6
Outreach | Sales Engagement | $36,000 | Sales | 8
Gong | Revenue Intelligence | $28,000 | Sales | 8
Segment | CDP | $30,000 | Engineering | 2

Deliver a complete MarTech Stack Intelligence Report with:

1. STACK HEALTH SCORECARD (score each tool 1-10 on: utilization, integration depth, revenue attribution, replaceability, vendor risk)

2. REDUNDANCY MAP (identify overlapping capabilities with % overlap estimate and consolidation opportunity value)

3. COST-PER-OUTCOME ANALYSIS (calculate cost per MQL, SQL, opportunity, and closed-won for each revenue-touching tool)

4. INTEGRATION DEBT ASSESSMENT (identify disconnected tools creating data silos, attribution blind spots, and manual work)

5. CONSOLIDATION ROADMAP (prioritized 90-day, 6-month, and 12-month plan with projected savings and risk assessment for each change)

6. REPLACEMENT SHORTLIST (for tools recommended for removal, provide 2-3 alternatives with cost comparison)

7. REVENUE ATTRIBUTION IMPACT (estimate current attribution coverage %, identify largest blind spots, project improvement from recommended changes)

8. BOARD SUMMARY (one-page executive view: current spend, recommended actions, projected savings, revenue attribution improvement)

Use specific numbers, not ranges. Flag any tool with <30% utilization or >$500 CAC contribution as high-priority review.

## Advanced Customizable Version

ROLE: You are a MarTech Revenue Operations Architect with 15 years of experience optimizing B2B SaaS marketing stacks. You have implemented and decommissioned 200+ tools across growth-stage and enterprise companies. You use a data-driven consolidation framework that balances cost efficiency, pipeline velocity, and attribution accuracy.

OBJECTIVE: Conduct a full-spectrum MarTech Stack Audit for {{COMPANY_NAME}}, producing a defensible, board-ready consolidation strategy with quantified ROI projections.

COMPANY PROFILE:
- Company: {{COMPANY_NAME}}
- Industry: {{INDUSTRY}} (e.g., HR Tech, Cybersecurity, FinTech)
- Stage: {{FUNDING_STAGE}} (Seed / Series A / Series B / Series C+ / Public)
- ARR: {{ARR}}
- YoY Growth Target: {{GROWTH_TARGET}}%
- Marketing Team: {{TEAM_SIZE}} headcount, {{MARKETING_BUDGET}} total budget
- MarTech Spend: {{MARTECH_SPEND}} ({{MARTECH_PERCENT}}% of marketing budget)
- GTM Motion: {{GTM_MOTION}} (PLG / Sales-Led / Channel / Hybrid)
- ICP: {{ICP_DESCRIPTION}}
- Average Contract Value: {{ACV}}
- Sales Cycle: {{SALES_CYCLE}} days

CURRENT STACK INVENTORY:
Provide in this format for each tool:
Tool: {{NAME}}
Category: {{CATEGORY}} [see taxonomy below]
Annual Cost: {{COST}}
Contract End: {{DATE}}
Primary Owner: {{TEAM}}
Active Users: {{COUNT}} / {{LICENSED_SEATS}}
Key Integrations: {{INTEGRATION_LIST}}
Primary Use Cases: {{USE_CASES}}
Satisfaction Score: {{1-10}} (internal team rating)
Data In/Out: {{DATA_FLOWS}}

STACK TAXONOMY (classify every tool):
- Data Foundation: CDP, Data Warehouse, ETL, BI/Analytics
- Demand Generation: MAP, Paid Media Management, SEO Tools, Intent Data
- Account Intelligence: ABM Platforms, Contact Data, Firmographic Enrichment
- Engagement: Email, Conversational Marketing, In-App Messaging, Webinar
- Sales Enablement: CRM, Sales Engagement, Revenue Intelligence, CPQ
- Attribution & Analytics: Multi-Touch Attribution, Web Analytics, Product Analytics
- Operations: iPaaS/Integration, Workflow Automation, Project Management
- Content & Creative: DAM, CMS, Video, Design

AUDIT FRAMEWORK — DELIVER ALL 9 MODULES:

MODULE 1: STACK HEALTH MATRIX
For every tool in the stack, score on 5 dimensions (1-10 scale):
- Utilization Rate: licensed seats vs. active users, feature adoption depth
- Revenue Attribution Depth: does it have measurable pipeline/revenue impact?
- Integration Maturity: native integrations vs. manual exports vs. dark data
- Strategic Alignment: does it support current GTM motion?
- Vendor Health: funding, NPS, support quality, roadmap confidence

Output: Sortable matrix with composite Health Score. Flag tools scoring <6.0 as At-Risk.

MODULE 2: CAPABILITY OVERLAP ANALYSIS
Map all tools against 40 core marketing capabilities. For each overlap:
- Primary tool (best-fit, keep)
- Redundant tool(s) (consolidate or remove)
- Overlap percentage (capabilities duplicated)
- Annual redundancy cost
- Consolidation complexity: Low / Medium / High
- Risk if removed: Low / Medium / High

Output: Visual capability matrix (text-based), ranked list of consolidation opportunities by dollar value.

MODULE 3: REVENUE ATTRIBUTION COVERAGE AUDIT
Map your entire customer journey touchpoint coverage:
- Awareness touchpoints tracked: {{LIST}}
- Consideration touchpoints tracked: {{LIST}}
- Decision touchpoints tracked: {{LIST}}
- Post-sale touchpoints tracked: {{LIST}}

For each stage, identify:
- % of touchpoints with attribution data
- Attribution model currently used (first-touch, last-touch, linear, W-shaped, data-driven)
- Revenue blind spots (touchpoints generating pipeline but not credited)
- Attribution model recommendation with projected accuracy improvement

Output: Attribution coverage score (current vs. potential), top 3 revenue blind spots with estimated untracked pipeline value.

MODULE 4: TOTAL COST OF OWNERSHIP ANALYSIS
For each revenue-touching tool, calculate true TCO:
- License cost
- Implementation/professional services (amortized)
- Internal admin time (hours × blended rate)
- Integration maintenance cost
- Training and onboarding costs
- Hidden costs (overages, add-ons, support tiers)

Then calculate cost-per-outcome:
- Cost per MQL
- Cost per SQL
- Cost per Opportunity Created
- Cost per Closed-Won
- Cost per Dollar of Pipeline Generated

Benchmark against industry standards:
- MAP: $15-40 per MQL (benchmark)
- Intent Data: $200-500 per opportunity influenced (benchmark)
- ABM Platform: $800-2,000 per account engaged (benchmark)

Flag any tool where cost-per-outcome exceeds 2× benchmark as Priority Review.

MODULE 5: INTEGRATION ARCHITECTURE ASSESSMENT
Map the current integration graph:
- Bidirectional integrations (real-time sync)
- Unidirectional integrations (one-way push)
- Manual exports/imports (data debt)
- Dark data (data that exists but is not flowing anywhere)

Identify:
- Single points of failure (integrations where breakage causes attribution loss)
- Data latency issues (time between action and CRM/MAP update)
- Data quality problems (field mapping conflicts, deduplication gaps)
- GDPR/CCPA compliance risks in data flows

Output: Integration debt score, top 5 integration improvements by business impact.

MODULE 6: CONSOLIDATION ROADMAP
Produce a phased roadmap with full risk analysis:

PHASE 1 — QUICK WINS (0-90 days):
- Tools to immediately decommission (clear redundancy, low risk)
- Contract negotiations to initiate (upcoming renewals)
- Feature consolidation moves (use existing tool feature instead of point solution)
- Projected savings: ${{X}}
- Implementation effort: {{X}} hours

PHASE 2 — STRATEGIC CONSOLIDATION (90-180 days):
- Platform migrations (e.g., consolidate MAP + CDP + attribution into unified platform)
- New tool evaluations triggered by gaps identified
- Team upskilling required
- Projected savings: ${{X}} net of new investments
- Risk assessment for each move

PHASE 3 — STACK EVOLUTION (6-12 months):
- Architecture-level changes (e.g., move from MAS-centric to CDP-centric stack)
- AI-native tool replacements (legacy → AI-powered equivalent)
- Data infrastructure upgrades needed
- Projected impact on revenue attribution accuracy

For each recommended change include:
- Business case (ROI calculation)
- Migration path (step-by-step)
- Rollback plan
- Success criteria

MODULE 7: AI-READINESS ASSESSMENT
Evaluate current stack for AI integration readiness:
- Data quality score (clean, unified customer data is the foundation)
- AI-native tools already in stack vs. AI-bolt-on tools
- Automation opportunities currently unrealized
- Recommended AI-native replacements for legacy tools
- Estimated efficiency gains (hours saved per week by team function)

MODULE 8: VENDOR RISK REGISTER
For each tool, assess:
- Acquisition risk (is the vendor likely to be acquired in 12-24 months?)
- Pricing trajectory (has pricing increased >15% in last 2 years?)
- Feature stagnation (release velocity declining?)
- Competitive pressure (is the category being commoditized?)
- Contract lock-in risk (auto-renewals, data portability clauses)

Output: Risk-ranked vendor list with recommended contract negotiation priorities.

MODULE 9: BOARD-READY EXECUTIVE SUMMARY
One-page format:
- Current State: Total MarTech spend, tool count, health score, attribution coverage %
- Problem Statement: Top 3 issues in current stack (with dollar quantification)
- Recommended Actions: Top 5 moves with combined projected savings and ROI
- Investment Required: Any net-new spend needed (with payback period)
- 12-Month Projection: Post-optimization spend, projected attribution improvement, estimated pipeline impact
- Request: Specific budget approvals or headcount needed to execute

OUTPUT FORMAT:
- Use tables for all matrices and scorecard data
- Use numbered lists for all recommendations
- Include confidence level (High/Medium/Low) for all financial projections
- Flag all assumptions explicitly
- Write at a CFO-readable level — no jargon, all acronyms defined

## Example Input/Output

**Input:**
Company: Prism Analytics (HR Tech, Series B, $18M ARR)
Stack: HubSpot $42K | Salesforce $85K | 6sense $55K | ZoomInfo $28K | Clearbit $18K | 
       Drift $22K | Outreach $36K | Gong $28K | Google Analytics 4 (free) | 
       Looker $40K | Segment $32K | Zapier $12K | Canva $3.6K
Total: $401,600/year
Team: 8 marketing, 12 sales | GTM: Sales-led | ACV: $42,000 | Cycle: 67 days

**Output (excerpt):**

**STACK HEALTH SCORECARD**
| Tool | Utilization | Attribution | Integration | Strategic Fit | Vendor Health | Score |
|---|---|---|---|---|---|---|
| HubSpot | 7 | 9 | 9 | 9 | 9 | **8.6** |
| Salesforce | 9 | 8 | 8 | 9 | 9 | **8.6** |
| 6sense | 5 | 7 | 6 | 9 | 8 | **7.0** |
| ZoomInfo | 6 | 4 | 5 | 7 | 7 | **5.8** ⚠️ |
| Clearbit | 4 | 3 | 6 | 7 | 6 | **5.2** ⚠️ |
| Drift | 3 | 4 | 5 | 6 | 7 | **5.0** ⚠️ |
| Segment | 4 | 6 | 7 | 8 | 8 | **6.6** |

**TOP REDUNDANCY FINDINGS:**
1. **ZoomInfo + Clearbit ($46K/year)** — 73% capability overlap in contact enrichment and firmographic data. 6sense intent data includes contact enrichment. Consolidate to 6sense + one data provider. Projected savings: **$28,000-$46,000/year**.

2. **Drift ($22K)** — HubSpot's native chatbot covers 80% of Drift's use cases for Prism's current lead volume. At $18M ARR, Drift's AI features are underutilized. Decommission at renewal (3 months). Savings: **$22,000/year**.

3. **Attribution Gap Identified:** Google Analytics 4 + HubSpot multi-touch captures only 61% of pipeline touchpoints. Dark funnel (G2 reviews, podcast listens, LinkedIn DMs) estimated at 18 untracked opportunities/quarter ($756K unattributed pipeline annually).

**CONSOLIDATION ROI:**
- Phase 1 savings: $46,000 (Clearbit + Drift removal)
- Phase 2 savings: $22,000 (ZoomInfo consolidation into 6sense)
- Phase 2 investment: $15,000 (Segment → 6sense CDP integration work)
- Net 12-month impact: **+$53,000 cash savings + 22% attribution accuracy improvement**
- Estimated pipeline recovery from improved attribution: **$189,000**

## Success Metrics

**Audit Quality:**
- Every tool has a numerical health score with supporting rationale
- All redundancy findings include dollar-value consolidation opportunity
- Attribution coverage percentage is calculable (not estimated)
- Phase 1 recommendations executable within 90 days without new headcount

**Output Readiness:**
- CFO can approve Phase 1 actions from the board summary alone
- Vendor names and contract dates are specific
- All cost projections include confidence level and key assumptions
- Migration risks are ranked and have mitigation steps

**Business Impact Targets:**
- Identify minimum 15-20% MarTech spend reduction opportunity
- Improve attribution coverage by minimum 15 percentage points
- Reduce integration maintenance burden by 20%+ (manual exports eliminated)

## Related Prompts

- `../../05_Analytics-&-Performance/Marketing-Mix-Modeling-&-Budget-Optimization/AI-Powered-B2B-Long-Term-Brand-Investment-ROI-Analytics-&-Brand-to-Demand-Revenue-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/`
- `../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/AI-Powered-B2B-Revenue-Trigger-ABM-Campaign-Architecture-&-Event-Based-Account-Activation-Intelligence-Engine.md`
- `../../01_CMO-&-Leadership/Reporting-&-ROI/`

## Integration Tips

**HubSpot:** Export the audit output as a custom object in HubSpot to track tool health scores quarterly. Create a "MarTech Vendor" object with health score, contract renewal date, and consolidation status fields.

**Salesforce:** Build a MarTech ROI dashboard in Salesforce connecting tool spend (custom object) to influenced pipeline and closed-won revenue. Auto-populate via Zapier from renewal tracker.

**Google Sheets/Notion:** Paste the Stack Health Matrix directly into a master MarTech tracker. Use conditional formatting to flag At-Risk tools (score <6) in red. Share with CFO and CRO before each budget cycle.

**Zapier/Make:** Automate contract renewal alerts — trigger 90-day, 60-day, and 30-day reminders to MarTech owner and CFO when any tool contract renewal date is approaching.

**Looker/Tableau:** Connect the attribution coverage data to your pipeline dashboard to show real-time "% of pipeline with attribution data" and track improvement quarter-over-quarter.

**Vendor Management:** Feed consolidation roadmap into a contract negotiation calendar. Schedule vendor reviews 120 days before renewal to preserve leverage.

## Troubleshooting

**Problem: No historical cost data for tool TCO calculation**
*Fix:* Start with license costs only and tag projections as "License Cost Only — TCO TBD." Ask Finance for invoices from the past 12 months. For admin time, use a default of 4 hours/month per tool for tools without a dedicated owner, 15 hours/month for tools with a dedicated admin.

**Problem: Attribution coverage % is impossible to calculate without a data team**
*Fix:* Use a proxy metric: count the number of distinct touchpoint types in your CRM vs. the number of channels you actively run (paid, organic, events, outbound, referral, etc.). Attribution Coverage ≈ (Touchpoint Types Tracked in CRM / Total Active Channels) × 100. Flag as estimated.

**Problem: The consolidation roadmap creates organizational conflict (tool is owned by Sales, not Marketing)**
*Fix:* Separate the technical recommendation from the political recommendation. Flag tools owned by other teams as "Cross-Functional Review Required" and list the business case for the CRO or COO to champion, not the CMO. Never recommend decommissioning a tool the Sales team owns without CRO buy-in explicitly noted in the output.

## Version History
- v1.0: Initial creation (auto-generated)
