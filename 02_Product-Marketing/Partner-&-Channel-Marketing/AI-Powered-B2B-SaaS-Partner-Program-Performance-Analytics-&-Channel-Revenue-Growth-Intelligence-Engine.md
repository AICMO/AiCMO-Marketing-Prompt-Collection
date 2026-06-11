# AI-Powered B2B SaaS Partner Program Performance Analytics & Channel Revenue Growth Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** b2b, channel-marketing, partner-program, revenue-attribution, mdf, pipeline-analytics, partner-enablement

## Overview

This prompt builds a full-stack AI analysis engine that diagnoses your partner program's revenue performance, identifies your highest-ROI partners, optimizes MDF (Market Development Funds) allocation, and generates specific programmatic recommendations to grow partner-sourced pipeline. Use it when your partner program feels like a black box — activity is happening but revenue impact is unclear, or you suspect 20% of partners drive 80% of results and need to act on that.

## Quick Copy-Paste Version

You are a senior channel revenue strategist. Analyze the following B2B SaaS partner program data and produce a complete performance intelligence report.

**Partner Program Context:**
- Company: [Your Company] — [one-line product description]
- ICP: [Company size, industry, buyer title]
- Partner types: [VAR / MSP / ISV / Referral / GSI — list which apply]
- Total active partners: [X]
- Partner-sourced pipeline last quarter: $[X]
- Partner-influenced pipeline last quarter: $[X]
- Total MDF budget last quarter: $[X]
- CRM: [HubSpot / Salesforce]

**Analyze and produce:**

1. **Partner Tier Performance Scorecard**
   - Classify partners into Tier 1 (Champion), Tier 2 (Growth), Tier 3 (Inactive) based on: pipeline generated, deal close rate, average ACV, time-to-close, and MDF ROI
   - Flag any partners who received MDF but produced zero pipeline in 90+ days

2. **Revenue Attribution Clarity**
   - Separate partner-sourced (partner owns the relationship) from partner-influenced (partner accelerated our sourced deal)
   - Calculate blended partner CAC vs. direct CAC
   - Identify which partner types have the shortest sales cycle and highest close rates

3. **MDF ROI Optimization**
   - Rank MDF investments by revenue-per-dollar-spent
   - Identify MDF programs that consistently underperform (below 3:1 pipeline ROI)
   - Recommend reallocation from low-performers to high-performers with specific dollar amounts

4. **Top Partner Playbook Extraction**
   - Identify the top 5 partners by revenue contribution
   - Extract the common patterns: What activities did they run? What content did they use? What joint campaigns drove deals?
   - Convert these patterns into a repeatable playbook for Tier 2 partners

5. **90-Day Growth Action Plan**
   - 3 specific programs to activate in the next 90 days with expected pipeline impact
   - Partner recruitment criteria to fill gaps in your ICP coverage
   - Quarterly Business Review (QBR) framework for Tier 1 partners

Output as a board-ready partner program performance report with executive summary, detailed analysis, and a prioritized action plan.

---

**Your partner program data:**
[Paste partner performance data, CRM export, or describe your situation in detail]

## Advanced Customizable Version

### ROLE
You are a B2B SaaS Channel Revenue Architect with 15+ years of experience building partner programs that generate 30-40% of company ARR. You have run channel programs at companies from Series B through post-IPO, managed 500+ partner ecosystems, and built the analytics infrastructure to prove partner ROI to CFOs and boards. You think in revenue math, not partner activity metrics.

### PROGRAM CONTEXT

**Company Profile:**
Company name: [Company Name]
Product: [One-sentence description — what it does, who it serves, key differentiator]
ACV range: $[X] to $[Y]
Sales cycle (direct): [X months]
Sales cycle (partner-sourced): [X months — if known]
GTM motion: [Direct + Partner / Partner-First / Partner-Led]
Revenue goal next 12 months: $[X ARR]
Partner-sourced revenue target: [X%] of total ARR = $[X]

**Current Partner Ecosystem:**
Total partner accounts in PRM/CRM: [X]
Partners registered in last 12 months: [X]
Partners who registered 1+ deal last quarter: [X]
Partner types and counts:
  - Referral/Affiliate partners: [X]
  - Value-Added Resellers (VARs): [X]
  - Managed Service Providers (MSPs): [X]
  - ISV/Technology Alliance partners: [X]
  - Global/Regional Systems Integrators (GSIs): [X]
  - Hyperscaler partners (AWS/Azure/GCP): [X]

**Pipeline & Revenue Data (Last Quarter):**
Partner-sourced pipeline created: $[X] across [X] deals
Partner-influenced pipeline: $[X] across [X] deals
Partner-sourced deals closed-won: $[X] ARR from [X] deals
Partner-sourced close rate: [X%] vs. direct close rate: [X%]
Average partner-sourced ACV: $[X] vs. direct ACV: $[X]
Partner attach rate to existing customer expansions: [X%]

**MDF & Program Investment:**
Total MDF budget last quarter: $[X]
MDF claimed vs. MDF approved: [X%] utilization
MDF programs offered: [list — co-branded events, content syndication, digital ads, etc.]
Top MDF recipient partners: [Partner 1: $X, Partner 2: $X, Partner 3: $X]
Partner portal engagement: [X% of partners logged in last 30 days]
Partner-facing content assets available: [X]

**Top Performers (if known):**
Top 3 partners by revenue: [Partner A: $X ARR, Partner B: $X ARR, Partner C: $X ARR]
Top 3 partners by deal volume: [Partner A: X deals, etc.]
Partners who churned/went inactive last quarter: [X]
NPS or satisfaction score from last partner survey: [X/10 or unknown]

### OBJECTIVE

Produce a complete Partner Program Performance Intelligence Report that gives the VP of Channel or CMO a precise, data-backed understanding of what's working, what's failing, and exactly what to do next. This report must be actionable enough to present to the CEO and CFO.

### ANALYSIS FRAMEWORK

**Module 1 — Partner Revenue Segmentation (Pareto Analysis)**

Apply the Partner Revenue Contribution Matrix:
- **Champions (Tier 1):** Top 20% of partners by revenue — calculate their share of total partner-sourced ARR, average ACV, close rate, sales cycle, and MDF ROI. These are your franchise partners.
- **Growth Partners (Tier 2):** Middle 30% — high potential, inconsistent execution. Identify what's blocking them: enablement gaps, ICP misalignment, insufficient joint pipeline activity, or lack of co-sell motion.
- **Laggards (Tier 3):** Bottom 50% — registered but not producing. Segment by: recently onboarded (under 6 months), dormant (registered deal 6-12 months ago), and zombie (no deal activity ever). Each requires a different intervention.

For each tier, calculate:
- Revenue per partner (annualized)
- Pipeline-to-revenue conversion rate
- MDF ROI (pipeline generated ÷ MDF invested)
- Time-to-first-deal from registration
- Sales cycle vs. company average

**Module 2 — Revenue Attribution Architecture**

Build a precise attribution model that separates:

*Partner-Sourced Revenue:*
- Partner introduced the opportunity with no prior company contact
- Partner owns the primary relationship throughout the sales cycle
- Calculate: Partner-sourced CAC = (MDF + partner program costs) ÷ partner-sourced new ARR
- Compare to direct CAC — if partner CAC is lower, make the case for increased partner investment

*Partner-Influenced Revenue:*
- Company sourced the lead, partner accelerated or expanded the deal
- Quantify influence: did partner involvement reduce sales cycle? Increase ACV? Improve close rate?
- Build a "partner influence uplift" factor: (partner-influenced close rate ÷ uninfluenced close rate) - 1

*Co-Sell Attribution:*
- Identify deals where both internal AEs and partners were active simultaneously
- Measure whether partner involvement correlated with faster close or larger deal size
- Use this data to build the business case for your co-sell motion

**Module 3 — MDF Investment Optimization**

For each MDF program type, calculate:
- Pipeline generated per $1 of MDF invested (target: 5:1 minimum, 10:1 ideal)
- Deals influenced per campaign
- Average time from MDF activity to registered opportunity
- Revenue realized from MDF-funded activities (closed deals where MDF was a factor)

Identify:
1. **High-ROI programs** to double down on — specific program types and partner profiles that consistently exceed 8:1 pipeline ROI
2. **Low-ROI programs** to cut or restructure — programs below 3:1 ROI with specific diagnosis of why (wrong partner tier, wrong geography, wrong content, wrong timing)
3. **MDF leakage** — funds claimed but with no traceable pipeline outcome; quantify the leakage and recommend a proof-of-performance claims process

Build an MDF reallocation recommendation: specific dollar amounts shifted from underperforming programs to proven performers, with projected pipeline impact.

**Module 4 — Champion Partner Pattern Extraction**

Analyze your top 5 revenue-producing partners and extract:

*What they do differently:*
- Do they have dedicated headcount for your product?
- Do they run demand gen activities independently or rely entirely on your MDF programs?
- Do they sell your product as a standalone or bundle it with other solutions?
- What ICP do they consistently serve? Does it match your best-fit customer profile?

*Replicable behaviors to codify into a Partner Playbook:*
- Frequency and quality of joint pipeline reviews
- Co-sell activities that preceded their best deals (executive meetings, technical workshops, customer events)
- Content they used most frequently (battlecards, ROI calculators, implementation guides)
- Deal registration patterns (early registration = better close rates?)

*Partner Archetype Profile:* Build a "Champion Partner Profile" describing the company characteristics, team structure, market focus, and behavior patterns that predict success. Use this for recruitment targeting.

**Module 5 — Pipeline Velocity & Forecast Intelligence**

For the partner channel specifically:
- Partner pipeline coverage ratio: (partner pipeline ÷ partner revenue target) — target 4:1 minimum
- Partner pipeline aging analysis: flag deals stuck in stage for more than 2x average sales cycle
- Forecasted partner-sourced ARR for next quarter with confidence intervals
- Identify deals at risk: partner-registered opportunities with no activity in 30+ days

**Module 6 — Partner Health Score Model**

Build a Partner Health Score (0-100) using weighted signals:
Deal Activity (30 pts): Deals registered last 90 days — 0 = 0, 1 = 15, 2+ = 30
Revenue Production (25 pts): Closed-won ARR vs. tier expectation
Enablement Engagement (20 pts): Portal logins, certifications completed, training attendance
Co-Marketing Participation (15 pts): MDF programs activated, joint campaigns run
QBR Participation (10 pts): Attended last QBR, submitted partner business plan

Apply score to all active partners. Segment for intervention:
- Score 75-100: Champions — invest, expand, co-innovate
- Score 50-74: Growth — activate specific enablement and co-sell programs
- Score 25-49: At-risk — assign partner success manager, 60-day recovery plan
- Score 0-24: Offboard consideration — calculate cost of maintenance vs. projected revenue

### OUTPUT SPECIFICATIONS

Produce the following deliverable structure:

**Executive Summary (1 page)**
- Partner program health verdict (Red/Yellow/Green)
- Partner-sourced ARR contribution vs. target: $[X] of $[Y] = [Z%]
- Top 3 findings that require immediate action
- Expected revenue impact of recommended changes: +$[X] ARR in 90 days if recommendations implemented

**Section 1: Partner Tier Analysis**
- Tier distribution table with revenue, pipeline, close rate, MDF ROI per tier
- Champion partner profiles (top 5 by ARR)
- Laggard analysis with recommended interventions

**Section 2: Revenue Attribution Report**
- Partner-sourced vs. partner-influenced breakdown with revenue figures
- Partner CAC vs. direct CAC comparison
- Co-sell motion ROI quantification

**Section 3: MDF Optimization Plan**
- Program-by-program ROI table
- Reallocation recommendation with projected pipeline impact
- Proof-of-performance process to eliminate MDF leakage

**Section 4: Champion Partner Playbook**
- Behaviors that predict partner success (5-7 specific patterns)
- Champion Partner Profile for recruitment targeting
- Onboarding-to-first-deal acceleration path

**Section 5: 90-Day Action Plan**
- 3 high-priority programs with owner, investment, timeline, and expected pipeline
- Partner recruitment targets: 5 specific partner archetypes to recruit with ICP rationale
- QBR calendar and agenda for Tier 1 partners

**Appendix: Partner Health Score Report**
- Full partner list with health scores, tier designation, and recommended next action
- Partners flagged for offboarding with cost-benefit calculation

### CONSTRAINTS
- All revenue projections must be based on historical close rate and ACV data provided, not industry averages
- MDF reallocation must be budget-neutral (same total spend, different distribution)
- All recommendations must be actionable within 90 days with existing team
- Partner names and specific data are confidential — any output must be safe for internal executive distribution
- Do not recommend adding headcount unless current team is at verified capacity

## Example Input/Output

**Input Example:**

Company: Meridian Revenue (deal intelligence platform for enterprise sales teams)
Product: AI-powered CRM enrichment and deal scoring for Salesforce users; ICP is VP Sales/CRO at 500-5,000 employee B2B SaaS companies
ACV: $45,000-$180,000
Direct sales cycle: 75 days
Partner program: 210 registered partners — 12 VARs, 38 MSPs, 95 Referral partners, 65 ISV alliances
Partner-sourced pipeline Q3: $4.2M across 62 deals
MDF budget Q3: $185,000
Top 3 partners by revenue: Apex Solutions ($620K ARR), BridgePoint Consulting ($440K ARR), CloudSell Partners ($310K ARR)
Partners who registered deals Q3: 31 of 210 (14.8%)

**Output Example (Executive Summary excerpt):**

**Partner Program Health: YELLOW — High Concentration Risk with Embedded Growth Opportunity**

Your partner program generated $4.2M in Q3 pipeline — representing 28% of total company pipeline — against a 35% target. The revenue math is sound but structurally fragile: 3 partners (Apex, BridgePoint, CloudSell) account for 63% of partner-sourced ARR. If any one churns, you lose approximately $1.1M in annual pipeline generation.

**Critical Finding 1 — 85% of registered partners are non-producing zombies.**
Only 31 of 210 registered partners (14.8%) registered a deal last quarter. The remaining 85% represent $0 pipeline contribution despite consuming portal infrastructure, enablement resources, and partner manager time. Immediate triage required: 45 partners are newly onboarded (under 6 months) and need activation; 95 are dormant (registered previously, nothing in 90+ days); 39 are true zombies with zero deal history despite 12+ months of registration.

**Critical Finding 2 — MDF efficiency is polarized.**
Your co-branded digital ad programs with MSP partners returned 12.3:1 pipeline ROI ($1.1M pipeline from $89K MDF). Your in-person regional event MDF returned 1.8:1 ($95K pipeline from $52K MDF) — destroying capital. Reallocating the $52K from events to digital co-sell programs is projected to generate an additional $390K in Q4 partner pipeline with no incremental budget.

**Critical Finding 3 — Champion partner behaviors are clearly identifiable and replicable.**
Apex Solutions (your #1 partner) has three behaviors absent in your Tier 2 partners: (1) dedicated Meridian-certified sales engineer on staff, (2) independent monthly webinars to their customer base featuring Meridian use cases, (3) deal registration within 14 days of first prospect contact (vs. 45-day average for other partners). These behaviors can be codified into your partner onboarding curriculum and incentivized through your tier structure.

**90-Day Revenue Impact if Recommendations Implemented: +$780K projected pipeline**
- MDF reallocation to digital co-sell: +$390K pipeline
- Apex playbook activation for top 8 Growth partners: +$240K pipeline
- Fast-track 45 new partners to first deal: +$150K pipeline

---

**Partner Health Score Distribution:**
- Champions (75-100): 8 partners | $3.1M ARR | Average score: 84
- Growth (50-74): 23 partners | $1.1M ARR | Average score: 61
- At-Risk (25-49): 45 partners | $0.08M ARR | Average score: 38
- Offboard candidates (0-24): 134 partners | $0 ARR | Average score: 11

**Recommendation:** Offboard 134 zombie partners from active tier structure. This reduces your "active partner" count from 210 to 76 — but focuses 100% of partner management resources on partners with revenue potential. The 76 active partners currently generate 99.7% of partner ARR.

## Success Metrics

- **Attribution accuracy:** Partner-sourced vs. partner-influenced pipeline is cleanly separated with <5% disputed attribution in CRM
- **MDF ROI baseline:** Every active MDF program has a documented pipeline ROI; programs below 3:1 are restructured or eliminated within one quarter
- **Partner activation rate:** Target 30%+ of registered partners registering at least one deal per quarter (up from industry average of 15-20%)
- **Champion playbook adoption:** Tier 2 partners who adopt champion behaviors show >25% increase in deal registration within 60 days
- **Partner health score coverage:** 100% of registered partners have a calculated health score updated monthly
- **Partner-sourced pipeline coverage:** Maintain minimum 4:1 partner pipeline coverage ratio vs. partner ARR target
- **QBR completion rate:** 100% of Tier 1 partners complete quarterly business reviews with documented joint pipeline plans

## Related Prompts

- [Partner Marketing Attribution & MDF ROI Intelligence Engine](Partner-Marketing-Attribution-&-MDF-ROI-Intelligence-Engine.md) — Deep-dive on MDF program measurement
- [VAR Reseller Channel Demand Generation & Partner-Sourced Pipeline Engine](VAR-Reseller-Channel-Demand-Generation-&-Partner-Sourced-Pipeline-Engine.md) — Demand gen execution through reseller channels
- [Channel Partner Recruitment Scoring & Onboarding Intelligence Engine](Channel-Partner-Recruitment-Scoring-&-Onboarding-Intelligence-Engine.md) — Building the partner pipeline with better-fit partners
- [../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Ecosystem-Led-Growth-ELG-&-Partner-Qualified-Pipeline-Intelligence-Engine.md](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Ecosystem-Led-Growth-ELG-&-Partner-Qualified-Pipeline-Intelligence-Engine.md) — Broader ecosystem-led growth strategy

## Integration Tips

**Salesforce / HubSpot CRM:**
- Create a "Partner Source" field on Opportunity that distinguishes: Partner-Sourced, Partner-Influenced, Partner-Co-Sell, No Partner. Make this a required field at Stage 2 to enforce attribution discipline.
- Build a Partner Health Score object that syncs from your PRM (Alliances, PartnerStack, Impartner) into CRM and auto-creates tasks when a partner score drops below 50.
- Use CRM reports to build the Partner Tier Performance Scorecard as a live dashboard — refresh weekly and share with partner managers as their primary performance view.

**PRM Systems (Alliances, PartnerStack, Impartner, Salesforce PRM):**
- Export partner deal registration data, MDF claims, portal engagement, and certification completion into a Google Sheet or Snowflake table. Feed this into the prompt alongside your CRM opportunity data for a complete picture.
- Set up automated PRM alerts: partner with no deal registration in 45 days triggers an automated re-engagement sequence; partner health score drops below 40 triggers a partner success manager notification.

**Clari / Gong / Revenue Intelligence:**
- If your team uses Clari, build a dedicated Partner Channel forecast category. Partner-sourced pipeline should be forecasted separately from direct pipeline with a separate close rate assumption.
- Use Gong to analyze your top partner QBR calls — what topics correlate with partner QBRs that generate the most subsequent pipeline? Feed these themes back into your QBR agenda template.

**Slack / Notion / Google Slides:**
- Pipe the Executive Summary output directly into a Notion partner program page as your monthly partner health dashboard
- Use the 90-Day Action Plan as a Notion project with assigned owners, due dates, and weekly status updates
- Build the Champion Partner Playbook as a Notion wiki article that all partner managers can access and contribute to

**Zapier / Make Automation:**
- When a partner registers a new deal in your PRM, trigger a Slack notification to the assigned partner manager and the CRO with deal details and partner health score
- When a partner's health score drops below 40, automatically enqueue them for a partner success check-in sequence in Outreach or Salesloft
- When MDF is claimed, trigger a 45-day pipeline follow-up task to verify whether a traceable opportunity was created

## Troubleshooting

**Problem: Partner pipeline data is scattered across CRM, PRM, and spreadsheets — can't produce a unified view.**
Solution: Before running this prompt, do a data consolidation sprint. Export deals with partner source fields from CRM, MDF claims from PRM, and partner engagement metrics from your portal. Combine in Google Sheets with partner name as the join key. Even an imperfect consolidation gives the prompt enough to produce actionable analysis. Document data gaps explicitly and treat them as a risk factor in your findings.

**Problem: The analysis identifies that 80%+ of partners should be offboarded, and leadership is resistant to reducing partner count.**
Solution: Reframe the conversation using the "Active Partner Productivity" metric rather than total partner count. Show that your 20 truly active partners are generating 98% of revenue — and that partner manager capacity spent on zombie partners is being stolen from revenue-producing partners. Build the ROI case: if your partner managers freed up 40% of their time from zombie partner maintenance and reinvested it in Champion and Growth partners, what is the projected revenue upside? That math usually resolves the political resistance.

**Problem: Partners are disputing the attribution model — VARs claim they influenced deals that show as direct in CRM.**
Solution: This is a cultural and process problem, not a data problem. Implement deal registration SLAs: any partner must register a deal within 21 days of first contact to receive partner-sourced credit. Deals registered after Stage 2 receive partner-influenced credit only. Communicate this in writing to all partners and enforce it consistently. The first quarter will be painful; by quarter two, partners learn to register early and attribution disputes disappear.

## Version History
- v1.0: Initial creation (auto-generated)
