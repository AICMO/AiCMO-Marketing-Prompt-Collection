# Partner Marketing Attribution & MDF ROI Intelligence Engine - AI-Powered Channel Revenue Contribution & Market Development Fund Optimization

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** partner-marketing, channel-marketing, MDF, partner-attribution, channel-revenue, co-marketing, partner-ecosystem, B2B-SaaS

## Overview
Automates the full lifecycle of partner marketing attribution and Market Development Fund (MDF) management — from partner campaign tracking and co-sell attribution to MDF ROI scoring and fund reallocation recommendations — producing partner-tier performance scorecards and data-driven funding decisions that revenue operations teams can act on immediately.

## Quick Copy-Paste Version

You are a channel marketing attribution specialist. My company sells [product/service] through a partner ecosystem of [number] partners across [tiers: e.g., Gold/Silver/Bronze]. We have a quarterly MDF budget of $[amount] and need to track partner-influenced vs. partner-sourced pipeline.

Analyze my partner marketing program and generate:

1. PARTNER ATTRIBUTION FRAMEWORK: Design a two-track attribution model — Partner-Sourced (partner identified and registered the opportunity before our team touched it) vs. Partner-Influenced (partner engaged with an existing prospect or deal). Include specific CRM fields, opportunity stages, and tagging logic to implement in Salesforce or HubSpot.

2. MDF PERFORMANCE SCORECARD: Create a scoring rubric (100-point scale) to evaluate each partner's MDF utilization based on: (a) campaign execution rate, (b) lead quality ratio (MQL-to-SQL conversion), (c) pipeline-to-MDF spend ratio, (d) deal velocity vs. direct-motion baseline, and (e) logo win rate. Include thresholds for Tier 1/2/3 qualification.

3. QUARTERLY MDF ALLOCATION MODEL: Based on partner scores, generate an allocation algorithm that: rewards top performers with 40% more MDF, places middle performers on a co-investment matching model, and puts bottom performers on a performance improvement plan (PIP) with activity-based milestones.

4. PARTNER CAMPAIGN ROI ANALYSIS: For each campaign type (webinar, trade show, digital ad co-op, email blast, in-person event), specify the minimum ROI threshold (pipeline generated / MDF spent) to continue, optimize, or cut funding. Use a 3x pipeline-to-spend floor as the baseline.

5. AUTOMATED REPORTING PACKAGE: Design a monthly partner marketing dashboard with: top 5 partners by pipeline contribution, MDF spend vs. pipeline by campaign type, partner-influenced deal velocity vs. direct-motion, and a fund health status (green/yellow/red) by partner tier.

Output as a ready-to-implement channel marketing operations playbook with specific metric formulas, CRM field names, and reporting cadence.

## Advanced Customizable Version

ROLE: You are a Senior Channel Marketing Operations Architect with 15 years of experience designing partner attribution systems and MDF programs for B2B SaaS companies scaling from $20M to $500M ARR. You have managed partner ecosystems with 200+ partners across VAR, SI, GSI, hyperscaler, and technology alliance tiers. You specialize in making partner revenue contribution mathematically defensible to CFOs and building automated attribution engines that require zero manual data entry.

COMPANY CONTEXT:
- Company: [Company Name]
- Product Category: [e.g., "B2B SaaS security platform," "cloud data infrastructure"]
- ARR: $[X]M | Partner-Sourced Revenue Goal: [X]% of new ARR
- Partner Ecosystem Size: [Number] active partners
- Partner Tiers: [e.g., Elite / Premier / Registered — or Gold / Silver / Bronze]
- CRM: [Salesforce / HubSpot / other]
- Quarterly MDF Budget: $[X] total | Allocated: $[X] to partners
- MDF Request Process: [Self-serve portal / Manual approval / Hybrid]
- Current Attribution Method: [None / Spreadsheet / Basic CRM field / Dedicated PRM tool]
- Top 3 Partner Types by Revenue: [VAR / SI / ISV / Hyperscaler / Referral]
- Deal Cycle Length (Partner vs. Direct): [X days partner vs. Y days direct]
- Average Partner Deal Size vs. Direct: [$X partner vs. $Y direct]
- Partner Enablement Stack: [e.g., Alliances/Impartner/PartnerStack/Salesforce PRM]
- Biggest Attribution Pain Point: [e.g., "partners claim all deals," "no tagging consistency," "MDF ROI is unmeasured"]

---

TASK 1 — DUAL-TRACK ATTRIBUTION ARCHITECTURE

Build a complete partner attribution model with technical implementation specs:

A) ATTRIBUTION CLASSIFICATION LOGIC:

**Partner-Sourced (Hard Attach):**
- Definition: Partner registered the account in PRM/CRM before any direct sales activity AND first meeting was partner-led
- Required Evidence: Partner registration timestamp < Opportunity created date; Partner contact on first meeting invite
- CRM Implementation: Custom Opportunity field "Partner_Attribution_Type" = "Partner-Sourced"; Partner Account lookup field populated within 7 days of opportunity creation
- Revenue Credit: 100% credit to partner tier metrics; counted in partner-sourced pipeline report

**Partner-Influenced (Soft Attach):**
- Definition: Partner engaged with the opportunity after direct sales had already touched the account but contributed materially to progression or closure
- Influence Tiers: (a) Deal Acceleration (partner accelerated stage progression by ≥14 days vs. baseline), (b) Technical Win (partner provided POC support or technical validation), (c) Executive Access (partner introduced C-suite contact not previously engaged), (d) Competitive Defense (partner leveraged relationship to counter competitor)
- CRM Implementation: Multi-select field "Partner_Influence_Type"; Partner contact activity logged in opportunity timeline with "Partner" tag; Weighted influence score (1-4) based on tier
- Revenue Credit: 25–75% weighted influence credit to partner pipeline dashboard (not direct attribution)

B) TAGGING & DATA HYGIENE PROTOCOL:

Implement automated tagging rules in [CRM] to prevent double-counting:
- Rule 1: If opportunity has both direct SDR activity AND partner registration within 14-day window → flag for RevOps review; default to Partner-Influenced unless partner registration predates ALL sales activity
- Rule 2: Partner registration must include: (a) account domain, (b) prospect name + title, (c) expected close quarter, (d) deal size estimate — incomplete registrations auto-expire in 30 days
- Rule 3: Hyperscaler co-sell (AWS/Azure/GCP) tracked separately in "Hyperscaler_CoSell" field with marketplace transaction confirmation as proof
- Rule 4: Monthly reconciliation report auto-generated from CRM: opportunities with zero partner tags vs. partner-claimed deals → gap list sent to channel team for audit

---

TASK 2 — MDF PERFORMANCE SCORING MODEL

Design a 100-point partner MDF scorecard updated quarterly:

**COMPONENT 1 — MDF Execution Rate (25 points)**
- 100% of allocated MDF spent on approved activities: 25 pts
- 75–99% spent: 20 pts
- 50–74% spent: 12 pts
- <50% spent or funds returned unspent: 0 pts (automatic review)
- Bonus +5 pts: Partner submitted results report within 30 days of campaign completion

**COMPONENT 2 — Lead Quality Ratio (25 points)**
- Calculate: (Partner-generated SQLs) / (Partner-submitted MQLs) × 100
- SQL conversion rate ≥ 25%: 25 pts
- SQL conversion rate 15–24%: 18 pts
- SQL conversion rate 8–14%: 10 pts
- SQL conversion rate <8%: 0 pts (lead quality PIP triggered)
- Benchmark against direct motion SQL conversion rate for same ICP segment

**COMPONENT 3 — Pipeline-to-MDF Spend Ratio (30 points)**
- Formula: (Qualified pipeline generated) / (MDF invested) = Pipeline Multiplier
- Multiplier ≥ 5x: 30 pts
- Multiplier 3–4.9x: 22 pts
- Multiplier 2–2.9x: 14 pts
- Multiplier 1–1.9x: 6 pts
- Multiplier <1x: 0 pts (automatic tier downgrade review)
- Note: Use 6-month trailing pipeline, not closed-won only, to account for deal cycle

**COMPONENT 4 — Deal Velocity & Win Rate (20 points)**
- Sub-score A (10 pts): Partner-attached deal cycle vs. direct baseline
  - ≥20% faster than direct: 10 pts | Same speed: 6 pts | Slower: 2 pts
- Sub-score B (10 pts): Partner deal win rate vs. direct win rate for same ICP
  - ≥5 percentage points higher: 10 pts | Within 5 pts: 7 pts | Lower: 3 pts

**SCORING THRESHOLDS:**
- 85–100: Elite tier — 150% MDF allocation next quarter; featured in partner spotlight
- 70–84: Premier tier — 100% MDF allocation maintained
- 50–69: Registered tier — 75% MDF allocation; partner success manager assigned
- 35–49: Performance Improvement Plan — 50% MDF; milestone-based release of remaining
- <35: MDF suspended; tier review meeting required within 30 days

---

TASK 3 — QUARTERLY MDF ALLOCATION ALGORITHM

Generate the Q[X] MDF allocation recommendations:

**STEP 1 — BASE ALLOCATION:**
Total quarterly MDF: $[X]
- Reserve 15% ($[Y]) for opportunistic/reactive campaigns (competitive situations, urgent co-sell)
- Reserve 10% ($[Y]) for new partner ramp (partners <6 months in program, no score yet)
- Distribute remaining 75% ($[Y]) based on performance score tiers

**STEP 2 — TIER-BASED DISTRIBUTION:**
For each tier, calculate per-partner allocation:
- Elite partners: (Partner score / Sum of all Elite scores) × Elite tier budget
- Premier partners: (Partner score / Sum of all Premier scores) × Premier tier budget
- Registered partners: Flat allocation based on business case submission + approval

**STEP 3 — CO-INVESTMENT MATCHING:**
For Premier-tier partners scoring 60–69:
- Company contributes 50% of MDF request; partner matches 50% from own marketing budget
- Co-investment proof required: Partner must submit signed co-investment commitment before fund release
- Converts to full MDF at next quarter if score improves ≥10 points

**STEP 4 — MDF REQUEST APPROVAL FRAMEWORK:**
For each incoming MDF request, auto-score on:
- Campaign type ROI history (from Task 4 analysis)
- Partner's trailing 2-quarter performance score
- Strategic alignment (is this ICP/vertical/use case we're prioritizing?)
- Time-to-execute (campaigns within 45 days get priority; >90 days require extra justification)
Auto-approve if: Score ≥ 70 AND campaign type ROI history ≥ 3x AND request < $[threshold]
Auto-flag for manual review: Any other combination

---

TASK 4 — CAMPAIGN TYPE ROI ANALYSIS & FUNDING THRESHOLDS

Evaluate each partner campaign type using trailing 4-quarter data:

| Campaign Type | Avg MDF/Event | Avg Pipeline Generated | Pipeline Multiplier | Avg SQL Count | Recommendation |
|---|---|---|---|---|---|
| In-Person Event (sponsored) | $[X] | $[Y] | [Z]x | [N] | Continue / Optimize / Cut |
| Virtual Webinar (co-hosted) | $[X] | $[Y] | [Z]x | [N] | Continue / Optimize / Cut |
| Digital Co-op Advertising | $[X] | $[Y] | [Z]x | [N] | Continue / Optimize / Cut |
| Email Campaign to Partner List | $[X] | $[Y] | [Z]x | [N] | Continue / Optimize / Cut |
| Trade Show Co-exhibit | $[X] | $[Y] | [Z]x | [N] | Continue / Optimize / Cut |
| Executive Dinner/Roundtable | $[X] | $[Y] | [Z]x | [N] | Continue / Optimize / Cut |
| Partner-Led Demo Day | $[X] | $[Y] | [Z]x | [N] | Continue / Optimize / Cut |
| Content Syndication (partner site) | $[X] | $[Y] | [Z]x | [N] | Continue / Optimize / Cut |

**Funding Decision Rules:**
- Pipeline Multiplier ≥ 5x: Priority funding — automatically approve at 125% of standard allocation
- Pipeline Multiplier 3–4.9x: Standard approval — maintain funding
- Pipeline Multiplier 2–2.9x: Conditional — require optimized campaign brief before approval
- Pipeline Multiplier 1–1.9x: Probation — 1 more chance with modified approach; cut if no improvement
- Pipeline Multiplier <1x: Cut — redirect funds to higher-performing campaign types

---

TASK 5 — AUTOMATED PARTNER MARKETING DASHBOARD SPEC

Design the monthly partner revenue contribution dashboard for the VP of Channel / CRO:

**DASHBOARD 1: Executive Summary (board-ready)**
- Partner-Sourced Pipeline This Quarter: $[X] (vs. target $[Y]) — [%] of company total
- Partner-Influenced Pipeline This Quarter: $[X] — [%] of company total
- MDF Invested: $[X] | Blended Pipeline Multiplier: [X]x
- Partner Deals Won This Quarter: [N] deals | Avg ASP: $[X] | Avg Cycle: [X] days vs. [Y] days direct
- Top 3 Partners by Pipeline Contribution: [Partner 1], [Partner 2], [Partner 3]

**DASHBOARD 2: Partner Performance Leaderboard (channel team ops)**
- Ranked table: Partner Name | Tier | MDF Allocated | MDF Spent | Pipeline Generated | Multiplier | Score | Status
- Color coding: Green (Elite), Yellow (Premier), Orange (PIP), Red (Suspended)
- Trend arrows: Score up/down vs. prior quarter

**DASHBOARD 3: Campaign Effectiveness (marketing ops)**
- Heatmap: Campaign Type × Partner Tier → Pipeline Multiplier
- Bar chart: MDF spent vs. pipeline generated by campaign type
- Waterfall: Cumulative quarterly pipeline build — direct vs. partner-sourced vs. partner-influenced

**DASHBOARD 4: Fund Health Status (finance + channel ops)**
- MDF budget utilization gauge: Spent / Allocated / Remaining
- Projected end-of-quarter MDF burn rate
- Alert: Partners with <30 days to use allocated MDF before expiry
- Alert: MDF requests pending approval >5 business days

**REPORTING CADENCE:**
- Weekly: MDF request status + partner deal registration activity (auto-email to channel managers)
- Monthly: Full dashboard refresh + partner score update + fund reallocation alert
- Quarterly: Partner scorecard sent to each partner via PRM + tier review decisions + next-quarter allocation letter

---

TASK 6 — PARTNER MARKETING ATTRIBUTION AUDIT & DATA CLEANUP

Generate a one-time data audit to fix historical attribution gaps:

1. UNCLAIMED OPPORTUNITY AUDIT: Pull all closed-won deals from past 4 quarters with no partner field populated. Match company domain against PRM partner registration database. Flag deals where: partner registered the account in PRM within 90 days of close; OR partner contact appears on meeting/email activity; OR deal originated from a partner-sponsored event lead list.

2. DOUBLE-ATTRIBUTION RESOLUTION: Find all opportunities tagged as both partner-sourced AND SDR-sourced. Apply resolution logic: If partner registration date < first SDR activity date → Partner-Sourced wins. If dates within 7-day window → RevOps manual review. If SDR activity clearly predates partner registration by ≥14 days → Direct wins, apply Partner-Influenced if any partner activity exists.

3. MDF RETROACTIVE ROI RECONCILIATION: For the past 4 quarters of MDF spend, match each campaign to: (a) leads generated, (b) opportunities created within 90 days of campaign, (c) revenue closed from those opportunities. Build the baseline for the campaign ROI table in Task 4.

OUTPUT FORMAT: Deliver as a structured partner marketing playbook with:
- Attribution decision tree (visual flowchart description with if/then logic)
- MDF scorecard template (table format, ready for Google Sheets or Salesforce report)
- Quarterly allocation recommendation memo (executive summary + tier breakdown)
- Dashboard spec (Salesforce report names, HubSpot dashboard blocks, or Tableau worksheet names)
- 90-day implementation roadmap for new attribution system rollout

---

## Example Input/Output

**Input:**
Company: Meridian Data Security (B2B SaaS, cloud data loss prevention)
ARR: $28M, partner-sourced goal: 35% of new ARR
Partner ecosystem: 47 active partners (12 Gold, 19 Silver, 16 Bronze)
Quarterly MDF budget: $180,000
CRM: Salesforce + Impartner PRM
Top partner types: MSSP (managed security service providers), VARs, and two hyperscaler co-sell agreements (AWS, Microsoft)

**Output (excerpt):**

**Q2 MDF Allocation Recommendation:**

After scoring all 47 partners on the 100-point framework:
- 4 Gold partners scored ≥85 (Elite threshold): CyberShield Solutions (92), DataGuard Partners (88), SecureNet Alliance (87), Apex MSP Group (85)
- 8 Gold/Silver partners scored 70–84 (Premier)
- 28 partners scored 50–69 (Registered)
- 7 partners scored <50 (2 on PIP, 5 requiring review)

**Allocation:**
Total allocatable MDF (after 25% reserved): $135,000

Elite tier (4 partners): $54,000 total
- CyberShield: $16,200 (score-weighted) — primary campaign recommendation: Executive Roundtable targeting CISO audience in NYC/Chicago (historical 6.2x multiplier for this partner + campaign type)
- DataGuard Partners: $14,400 — Digital co-op campaign targeting financial services vertical (partner's strongest vertical; prior 4.8x multiplier)

**Top Partner Attribution Wins (Q1 example):**
CyberShield Solutions: 6 partner-sourced deals | $840K pipeline | $285K closed-won | MDF invested: $12,000 | Pipeline multiplier: 70x (driven by 2 enterprise deals; normalizing to 18x excluding outliers)

**Campaign Type Recommendation:**
Cut: Email campaigns to partner lists → averaging 1.4x multiplier across all partners this year
Scale: Executive roundtables → averaging 7.8x multiplier with ≥3 attendees
Optimize: Virtual webinars → averaging 2.6x; can reach 4x+ with ICP-specific topics; require partner to contribute their own contact list minimum 500 names

---

## Success Metrics

Your partner marketing attribution output is working correctly when:
- **Attribution coverage:** ≥90% of partner-registered opportunities have complete attribution data (no null fields)
- **MDF multiplier:** Blended pipeline-to-MDF multiplier ≥ 4x within 2 quarters of implementing the framework
- **Partner tier accuracy:** Zero partner tier misclassifications identified in quarterly audits
- **Reporting adoption:** Channel managers use the dashboard as primary data source (validate via CRM login frequency)
- **Revenue goal:** Partner-sourced pipeline reaches target % of total company pipeline within 3 quarters
- **MDF utilization:** ≥85% of allocated MDF is spent per quarter with submitted results reports

---

## Related Prompts

- `../../02_Product-Marketing/Partner-&-Channel-Marketing/Partner-Co-Marketing-Campaign-Engine.md`
- `../../02_Product-Marketing/Partner-&-Channel-Marketing/VAR-Reseller-Channel-Demand-Generation-&-Partner-Sourced-Pipeline-Engine.md`
- `../../02_Product-Marketing/Partner-&-Channel-Marketing/Hyperscaler-Co-Sell-&-Cloud-Marketplace-Revenue-Engine.md`
- `../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md`

---

## Integration Tips

**Salesforce:**
- Create a custom Opportunity object field: `Partner_Attribution_Type` (Picklist: Partner-Sourced / Partner-Influenced / Direct / Hyperscaler Co-Sell)
- Create a Partner Account lookup on Opportunity: `Attributed_Partner_Account__c`
- Build a Salesforce report type: Opportunities with Partner Attribution — filter by `Partner_Attribution_Type` and group by Partner Account to auto-populate the performance leaderboard
- Use Salesforce Flows to auto-alert channel managers when a new opportunity is created without a partner field but the account exists in PRM

**HubSpot:**
- Use Deal Properties to add partner attribution fields; sync with PartnerStack or Alliances via HubSpot's native integration or Zapier
- Create a HubSpot Dashboard with filtered deal reports for partner pipeline; share via a read-only dashboard link with each partner's account manager

**Impartner / PartnerStack / Alliances:**
- Configure PRM to automatically sync deal registrations to Salesforce/HubSpot with a timestamp; use this timestamp as the source of truth for Partner-Sourced attribution decisions
- Enable automated MDF request workflows in PRM: request submission → auto-score → approval/rejection → fund release notification → results submission reminder at 30 days post-campaign

**Google Sheets / Looker Studio:**
- Export Salesforce partner attribution report to Google Sheets weekly via a scheduled report or Zapier
- Build a Looker Studio dashboard connected to the Google Sheet for stakeholder sharing without Salesforce licenses

**Zapier / Make.com Automation:**
- Trigger: New MDF request submitted in PRM → Action: Score request against partner's trailing performance data in Salesforce → Action: Auto-approve or flag for review → Action: Notify channel manager via Slack
- Trigger: End of month → Action: Pull partner deal data from Salesforce → Action: Calculate updated scorecard → Action: Email scorecard to each partner's designated contact

---

## Troubleshooting

**Problem: Partners are claiming deals that the direct sales team already sourced, inflating partner-sourced numbers.**
Fix: Enforce a strict "registration beats claim" rule — only registrations submitted to PRM BEFORE the first documented direct sales activity (logged call, meeting, or email in CRM) qualify as Partner-Sourced. Set a 7-day dispute window where SDRs can contest registrations with evidence (email timestamps, CRM activity logs). Final arbitration goes to the Channel Operations manager, not the sales rep or partner, to remove bias.

**Problem: MDF is being spent but there's no way to trace it to actual pipeline because partners aren't tagging leads properly.**
Fix: Make lead list submission a mandatory prerequisite for MDF fund release — partners must upload their campaign lead list (name, company, email, LinkedIn URL) into the PRM or a shared Google Form before funds are released. These leads get automatically created as contacts in your CRM with a campaign source tag, enabling closed-loop reporting from the first lead touch.

**Problem: The MDF scorecard shows high-scoring partners who aren't actually generating revenue — they're gaming the metrics with low-quality leads.**
Fix: Add a 6-month closed-won revenue gate to Elite tier qualification. Regardless of score, a partner cannot maintain Elite tier if their closed-won revenue from partner-sourced deals is <$[X] per quarter. Replace lead volume metrics with SQL-to-closed-won rate as the primary quality signal — this can't be gamed because it requires the direct sales team to confirm deal quality independently.

---

## Version History
- v1.0: Initial creation (auto-generated)
