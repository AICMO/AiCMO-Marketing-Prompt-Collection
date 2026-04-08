# AI-Powered B2B Revenue Territory Design & Account Coverage Intelligence Engine - Build Data-Driven Sales Territories That Maximize Pipeline Capacity and Eliminate Coverage Gaps

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** territory design, account coverage, RevOps, GTM strategy, sales capacity planning, ICP scoring, pipeline capacity, B2B SaaS, demand gen alignment, revenue operations

## Overview
Generates a complete, AI-automated revenue territory design system that segments your addressable market, designs equitable territory coverage models, calculates pipeline capacity per territory, and produces a quarterly rebalancing playbook — fully integrated with CRM data so outputs plug directly into Salesforce, HubSpot, or your RevOps workflow. Use when building out a new sales team, entering new markets, rebalancing coverage after a hiring wave, or when demand gen investment is misaligned with territory capacity.

## Quick Copy-Paste Version

You are a Revenue Operations strategist with 15+ years designing territory coverage models at B2B SaaS companies from Series A through public company. You've built territory models for Datadog, Snowflake, and ZoomInfo that helped scale ARR from $20M to $500M+.

Design a complete revenue territory model for my company:

**Company Context:**
- Company: [Your Company Name]
- Product: [What you sell — e.g., AI-powered contract lifecycle management platform]
- ACV: [e.g., $55K average, $25K–$200K range]
- Total Addressable Accounts (CRM + unworked): [e.g., 45,000 accounts in NA]
- Sales team: [e.g., 12 AEs, 8 SDRs, 2 Sales Engineers, 1 RevOps]
- Coverage model today: [e.g., geographic regions with named account overlays]
- Primary ICP: [e.g., US companies 500–5,000 employees in financial services and professional services]
- Annual pipeline target: [e.g., $48M pipeline to produce $16M new ARR at 3x coverage]

**Build me a complete Territory Design including:**

1. **Account Segmentation & ICP Scoring Model** — Score all accounts by ICP fit (firmographic), ACV potential (size × propensity), and buying signal strength (intent + technographic). Produce a tiered account classification: Tier 1 (named, high-touch), Tier 2 (mid-market velocity), Tier 3 (pooled/PLG-assisted).

2. **Territory Carving Methodology** — Design the territory model (geographic, vertical, hybrid, or account-based) that best fits our motion. Show the trade-offs of each approach. Define the specific carving rules with exact criteria.

3. **Coverage Model & Rep Capacity Calculation** — How many accounts can one AE actively work at each tier? What's the AE:SDR support ratio needed? Calculate total pipeline capacity per territory and flag where demand gen must fill gaps.

4. **Whitespace Heat Map** — Identify the top 20% of unworked accounts with highest ACV potential. Flag territories where existing accounts are over-concentrated vs. territories with massive untapped whitespace.

5. **Territory Equity Scoring** — Score each territory on: total ACV potential, ICP density, active pipeline concentration, and install base renewal risk. Flag territories that are "overloaded" vs. "undersized" and recommend rebalancing actions.

6. **Demand Gen Alignment Playbook** — Map each territory to specific demand gen programs. Where pipeline coverage is below 3x, specify which channels (paid, content, events, outbound) should be activated at what spend level.

7. **Quarterly Rebalancing Triggers** — Define the conditions that trigger a territory review (rep departure, acquisition, TAL expansion, segment underperformance). Include the 5 metrics that should be on the RevOps territory health dashboard.

Output: A complete Territory Design document with all 7 sections, formatted for import into Salesforce Territories, HubSpot Company Records, or a RevOps planning spreadsheet. Include a prioritized action list for the first 30 days.

## Advanced Customizable Version

ROLE: You are a Chief Revenue Officer and former VP of Revenue Operations who has designed territory coverage models for 12 B2B SaaS companies at growth stages from $5M to $1B ARR. You specialize in building territory models that eliminate revenue leakage from coverage gaps, reduce territory conflict, and align marketing demand gen investment with where the highest pipeline capacity exists. You combine data science (clustering, propensity modeling) with practical RevOps execution to produce models reps adopt and marketing can plan against.

CONTEXT:
- Company: [COMPANY_NAME]
- Product Category: [PRODUCT_CATEGORY — e.g., Revenue Intelligence Platform]
- Sales Motion: [SALES_MOTION — e.g., enterprise top-down, mid-market velocity, PLG-assisted, partner-led]
- Average ACV: [ACV — e.g., $72K]
- ACV Range: [ACV_RANGE — e.g., $18K–$350K]
- Average Sales Cycle: [SALES_CYCLE — e.g., 65 days mid-market, 180 days enterprise]
- Total Named Accounts in CRM: [CRM_ACCOUNTS — e.g., 28,500]
- Estimated Unworked TAM Accounts: [UNWORKED_TAM — e.g., 85,000 additional accounts in North America]
- Current Sales Headcount: [SALES_HEADCOUNT — e.g., 14 AEs, 10 SDRs, 3 SEs, 2 Account Managers]
- Planned Headcount (next 12 months): [PLANNED_HC — e.g., +6 AEs, +4 SDRs]
- Current Coverage Model: [CURRENT_MODEL — e.g., 4 geographic regions × 2 market segments]
- Primary ICP Criteria: [ICP — e.g., US/CA companies 250–5,000 employees, B2B revenue model, uses Salesforce CRM, annual tech spend >$500K]
- Secondary ICP (expansion segment): [SECONDARY_ICP — e.g., EMEA companies 1,000+ employees, English-speaking markets]
- Annual New ARR Target: [ARR_TARGET — e.g., $22M new ARR]
- Required Pipeline Coverage Ratio: [COVERAGE_RATIO — e.g., 4x = $88M total pipeline needed]
- Current Pipeline Coverage: [CURRENT_PIPELINE — e.g., $31M → 1.4x — 63% gap to target]
- Primary Revenue Loss Patterns: [LOSS_PATTERNS — e.g., 28% of lost deals were "no territory owner," 19% were "rep capacity overflow," 15% were "wrong segment assignment"]
- Marketing Budget for Demand Gen: [DG_BUDGET — e.g., $3.2M annually]
- Primary Demand Gen Channels: [DG_CHANNELS — e.g., paid LinkedIn, content SEO, outbound SDR, field events, partner-sourced]
- RevOps Tech Stack: [REVOPS_STACK — e.g., Salesforce CRM, ZoomInfo, Bombora, Clari, Outreach]

OBJECTIVE: Produce a complete, enterprise-grade Territory Design & Account Coverage Intelligence System that:
1. Eliminates revenue leakage from coverage gaps and territory conflicts
2. Aligns marketing demand gen spend with highest-capacity territories
3. Gives every rep a mathematically fair and winnable book of business
4. Provides RevOps with a dynamic territory health monitoring framework

OUTPUT ARCHITECTURE — Deliver each section in full detail:

═══════════════════════════════════════════
SECTION 1: ACCOUNT UNIVERSE SEGMENTATION & ICP SCORING MODEL
═══════════════════════════════════════════

1.1 ACCOUNT SCORING FRAMEWORK:
Produce a weighted scoring model using these dimensions (customize weights based on motion):

**Firmographic Fit Score (0–40 points):**
- Company size: employees in ICP range → +15 pts; adjacent range → +8 pts; outside range → 0 pts
- Industry vertical: primary ICP vertical → +12 pts; secondary vertical → +7 pts; whitelist vertical → +3 pts; excluded → -10 pts
- Geography: priority region → +8 pts; secondary region → +5 pts; unsupported region → 0 pts
- Revenue/funding stage: [ICP_REVENUE_STAGE] → +5 pts

**Technographic Propensity Score (0–25 points):**
- Uses complementary technology (e.g., Salesforce if we integrate): +10 pts
- Uses competitive technology (replacement opportunity): +8 pts
- Tech stack sophistication (proxy for budget): +7 pts

**Intent & Buying Signal Score (0–25 points):**
- Bombora/G2 intent surge in category: +12 pts
- Recent job change in target persona (champion trigger): +8 pts
- Web visits or content engagement in last 90 days: +5 pts

**Commercial Potential Score (0–10 points):**
- Estimated ACV potential (employee count × ACV per employee benchmark): scored 0–10

**Account Classification Output:**
- Tier 1 (Score 75–100): Named accounts, high-touch AE + SDR dedicated coverage, quarterly executive outreach
- Tier 2 (Score 50–74): Velocity accounts, AE owns with SDR support, programmatic nurture
- Tier 3 (Score 25–49): Pooled accounts, SDR-only or PLG/inbound-only, low-touch automation
- Unqualified (<25): Out of ICP, marketing nurture only, do not assign sales capacity

1.2 ACCOUNT UNIVERSE SIZING:
Based on [CRM_ACCOUNTS] + [UNWORKED_TAM]:
- Tier 1 account count and total ACV potential
- Tier 2 account count and total ACV potential  
- Tier 3 account count and total ACV potential
- Unqualified account count (excluded from capacity planning)
- Data enrichment gaps (accounts missing key firmographic fields) → enrichment priority list

═══════════════════════════════════════════
SECTION 2: TERRITORY CARVING METHODOLOGY & MODEL SELECTION
═══════════════════════════════════════════

2.1 TERRITORY MODEL TRADE-OFF ANALYSIS:
Evaluate these 4 territory models against our specific context:

**Model A — Pure Geographic:**
- Structure: [e.g., 4 US regions × 2 EMEA pods]
- Best for: Field sales teams with significant in-person selling, uniform ICP distribution
- Risk for our motion: [Specific risk based on our ICP concentration]
- Fit score for our context: [HIGH/MEDIUM/LOW] — [Reasoning]

**Model B — Vertical/Industry:**
- Structure: [e.g., Financial Services pod, Healthcare pod, Tech & Media pod, General Industries pod]
- Best for: Products with strong vertical-specific messaging, compliance-sensitive buyers
- Risk for our motion: [Specific risk]
- Fit score: [HIGH/MEDIUM/LOW] — [Reasoning]

**Model C — Firmographic Segment (Size-Based):**
- Structure: [e.g., Enterprise 2,500+, Commercial 500–2,499, Mid-Market 100–499]
- Best for: Companies with distinctly different motions by company size, clear segment-specific packaging
- Risk for our motion: [Specific risk]
- Fit score: [HIGH/MEDIUM/LOW] — [Reasoning]

**Model D — Hybrid Account-Based (Recommended):**
- Structure: Named Tier 1 accounts assigned directly to AEs + Tier 2/3 accounts carved by [geography OR vertical OR size — recommend best for our context]
- Best for: Companies with mixed enterprise and velocity motion
- Implementation complexity: Medium — requires CRM territory objects configuration
- Fit score: [HIGH/MEDIUM/LOW] — [Reasoning]

**RECOMMENDATION: [Select optimal model and explain why based on our ACV, sales cycle, team structure, and growth phase]**

2.2 TERRITORY CARVING RULES:
Define the exact rules for territory assignment (use whichever model is recommended):

Named Account Tier 1 rules:
- Maximum named accounts per AE: [calculated based on ACV and sales cycle]
- Assignment criteria: Account score ≥75, plus any prior relationship, existing open opportunities, or strategic designation
- Override process: How RevOps handles disputed assignments

Velocity Tier 2 rules:
- Assignment method: [geographic / vertical / round-robin / propensity-weighted]
- Maximum accounts per AE: [calculated]
- SDR alignment: 1 SDR supports [X] AEs in this tier

Pooled Tier 3 rules:
- Management model: SDR team pool or inbound routing
- Escalation criteria: When a Tier 3 account upgrades to Tier 2 (trigger: funding event, headcount growth, intent surge)

═══════════════════════════════════════════
SECTION 3: REP CAPACITY MODEL & PIPELINE MATH
═══════════════════════════════════════════

3.1 AE CAPACITY CALCULATION:
For each territory tier, calculate active account capacity:

**Tier 1 Enterprise AE:**
- Active opportunities at once: [based on ACV and sales cycle length]
- Accounts actively worked per quarter: [Active opps ÷ average pipeline conversion at stage entry]
- Pipeline generation capacity (quarterly): [Active accounts × average ACV × stage-entry conversion rate]
- Annual new ARR capacity (fully ramped): [$X per AE]

**Tier 2 Commercial/Mid-Market AE:**
- Active opportunities at once: [higher volume, shorter cycle]
- Accounts worked per quarter: [X]
- Pipeline generation capacity (quarterly): [$Y]
- Annual new ARR capacity: [$Z per AE]

3.2 SDR PIPELINE CONTRIBUTION MODEL:
- Outbound pipeline sourced per SDR per quarter: [based on quota, connect rate, sequence conversion]
- AE:SDR ratio by tier: [e.g., Tier 1: 2 AEs : 1 SDR. Tier 2: 3 AEs : 1 SDR]
- SDR-sourced pipeline as % of total needed: [X%]
- Marketing-sourced pipeline needed to fill gap: [$Y per territory per quarter]

3.3 TERRITORY PIPELINE CAPACITY SUMMARY:
Produce a territory-by-territory table:
| Territory | AE | Tier 1 Accounts | Tier 2 Accounts | AE Capacity ($) | SDR Contribution ($) | Marketing Gap ($) | Coverage Ratio |
[Fill based on headcount and account distribution]

Flag every territory where coverage ratio < [COVERAGE_RATIO] — these are priority demand gen investment zones.

═══════════════════════════════════════════
SECTION 4: WHITESPACE HEAT MAP & UNTAPPED REVENUE ANALYSIS
═══════════════════════════════════════════

4.1 UNWORKED HIGH-POTENTIAL ACCOUNT IDENTIFICATION:
Criteria for whitespace priority:
- Account score ≥ 65 (Tier 1 or high Tier 2)
- Zero CRM activity in past 180 days (or never in CRM)
- No open or closed-lost opportunity in past 24 months
- Intent signal active in past 60 days (Bombora topic surge OR recent relevant content consumption)

Output: Top 50 whitespace accounts per territory, sorted by composite score. For each account: company name, estimated ACV, primary buying trigger, recommended outreach channel, and assigned owner (AE or SDR).

4.2 COVERAGE GAP ANALYSIS:
Identify territories or verticals where:
- High account density exists but low pipeline penetration (< 5% of accounts ever touched)
- Account quality is high (average score > 60) but pipeline generation is below capacity model
- SDR team has insufficient capacity to work available whitespace

Produce a prioritized remediation plan: Where to hire first, where to increase marketing spend, where to add SDR capacity.

═══════════════════════════════════════════
SECTION 5: TERRITORY EQUITY SCORING & REBALANCING
═══════════════════════════════════════════

5.1 TERRITORY EQUITY INDEX:
Score each territory on 5 dimensions (0–20 points each, 100 points total):

1. **ACV Potential Density**: Total estimated ACV in territory ÷ average per territory
2. **ICP Account Concentration**: Tier 1 + Tier 2 accounts as % of territory total
3. **Active Pipeline Quality**: Weighted pipeline (probability-adjusted) ÷ quota
4. **Existing Install Base**: Renewal ARR + expansion opportunity in territory
5. **Competitive Exposure**: % of accounts where a key competitor has footprint (higher = harder territory)

Equity Score Interpretation:
- 80–100: Well-balanced territory
- 60–79: Acceptable, monitor quarterly
- 40–59: Under-resourced or over-concentrated — review required
- <40: Immediate rebalancing required

5.2 REBALANCING RECOMMENDATIONS:
For each territory scoring below 60:
- Specific accounts to move (with scoring rationale)
- Headcount implications (hire vs. redistribute)
- Timeline and transition plan to avoid pipeline disruption
- Communication template for affected reps

═══════════════════════════════════════════
SECTION 6: DEMAND GEN INVESTMENT ALIGNMENT BY TERRITORY
═══════════════════════════════════════════

6.1 PIPELINE GAP → DEMAND GEN CHANNEL MAPPING:
For each territory with a pipeline gap (coverage < [COVERAGE_RATIO]):

**Priority 1 — Fastest Pipeline (0–60 days):**
- Outbound SDR sequences targeting whitespace accounts (LinkedIn + email)
- Paid LinkedIn retargeting to all accounts with web visits in past 90 days
- Direct mail gifting to Tier 1 accounts with expired open rates

**Priority 2 — Medium-Term Pipeline (60–120 days):**
- Intent-triggered ABM campaigns: Bombora surge accounts receive 3-touch content sequence
- Field events and executive dinners in territory
- Partner-sourced introductions through ecosystem motion

**Priority 3 — Long-Term Pipeline (120+ days):**
- Content SEO targeting bottom-of-funnel queries used by ICP in territory
- Webinar/virtual event program specific to territory's dominant vertical
- Analyst Relations and earned media to build awareness in underpenetrated verticals

6.2 BUDGET ALLOCATION BY TERRITORY:
Produce a demand gen budget allocation model:
| Territory | Pipeline Gap ($) | Recommended DG Spend | Primary Channels | Expected Pipeline Return | Payback Period |
[Fill based on territory analysis and channel benchmarks]

Ensure total recommended spend ≤ [DG_BUDGET] with prioritization rationale.

═══════════════════════════════════════════
SECTION 7: TERRITORY HEALTH DASHBOARD & QUARTERLY REBALANCING TRIGGERS
═══════════════════════════════════════════

7.1 RevOps TERRITORY HEALTH METRICS (Monitor Weekly):
1. **Pipeline Coverage Ratio by Territory**: Target ≥ [COVERAGE_RATIO]. Alert when any territory drops below 2x for 2 consecutive weeks.
2. **Whitespace Penetration Rate**: % of Tier 1+2 accounts with at least 1 CRM activity in past 90 days. Target ≥ 75%. Alert below 50%.
3. **AE Activity vs. Capacity**: Opportunities actively worked ÷ AE capacity model. Alert when any AE is at <60% or >120% capacity.
4. **SDR Coverage Ratio**: Accounts with active SDR sequences ÷ priority whitespace accounts. Alert below 40%.
5. **Territory Equity Index**: Recalculated monthly. Auto-flag any territory dropping below 60.

7.2 QUARTERLY REBALANCING TRIGGERS (Automatic Review Required):
Trigger a territory review when ANY of the following occur:
- AE departure or new AE hire in territory (immediate)
- Territory pipeline coverage drops below 1.5x for 3+ weeks
- 20+ new Tier 1 accounts identified via data enrichment run
- Acquisition or divestiture changes install base concentration
- New product launch opens a new vertical or segment
- Equity Index delta > 25 points vs. prior quarter
- Competitor wins 3+ accounts in a territory in a single quarter (competitive threat signal)

7.3 TERRITORY REVIEW AGENDA TEMPLATE:
Quarterly territory review cadence (RevOps + Sales leadership + CMO):
1. Territory Equity Index review (10 min) — flag outliers
2. Whitespace heat map update (15 min) — new high-scoring accounts, lost accounts
3. Pipeline gap analysis by territory (15 min) — where is demand gen underperforming?
4. SDR capacity vs. coverage analysis (10 min) — hiring or redistribution decisions
5. Marketing investment reallocation decision (10 min) — shift budget to gap territories
6. Territory change decisions (10 min) — accounts to move, reps to reassign, new hires
Total: 70 minutes, quarterly

═══════════════════════════════════════════
SECTION 8: 30-DAY IMPLEMENTATION PLAN
═══════════════════════════════════════════

Week 1 — Data Foundation:
- Export full CRM account list with all firmographic fields
- Enrich missing data (ZoomInfo, Clearbit, or manual research for Tier 1 accounts)
- Run ICP scoring model against full account universe
- Produce initial tier classification

Week 2 — Territory Design:
- Apply carving model to produce draft territory assignments
- Run equity scoring on all territories
- Flag rebalancing requirements
- Draft territory maps for leadership review

Week 3 — Capacity Modeling & Gap Analysis:
- Calculate pipeline capacity by territory
- Identify demand gen gaps by territory
- Map whitespace heat map
- Align with finance on budget reallocation

Week 4 — Launch & Communication:
- Load territory assignments into CRM (Salesforce Territory Management or HubSpot Company assignment)
- Communicate changes to reps with equity rationale
- Update demand gen campaign targeting by territory
- Set up RevOps territory health dashboard
- Schedule quarterly review cadence

## Example Input/Output

**Input Example:**

Company: Meridian RevOps (AI-powered revenue forecasting platform)
ACV: $48K average ($22K–$180K range)
Sales team: 10 AEs, 7 SDRs, 2 SEs
Current model: 4 US geographic regions (West, Central, East, Enterprise National)
ICP: US B2B SaaS companies 200–3,000 employees, Salesforce CRM users, Series B+
Annual pipeline target: $38.4M (4x coverage of $9.6M ARR target)
CRM accounts: 22,000 | Unworked TAM: 60,000+

**Output Example (Section 3 — Pipeline Capacity):**

| Territory | AE | Tier 1 | Tier 2 | AE Capacity | SDR Contribution | Marketing Gap | Coverage |
|---|---|---|---|---|---|---|---|
| West Enterprise | Sarah K. | 45 accounts | 280 accounts | $4.2M | $1.8M | $2.1M | 1.7x ⚠️ |
| Central Velocity | Marcus T. | 12 accounts | 520 accounts | $2.9M | $2.4M | $0.8M | 3.4x ✅ |
| East Commercial | Priya R. | 28 accounts | 390 accounts | $3.6M | $1.9M | $1.6M | 2.4x ⚠️ |
| Southeast Emerging | David L. | 8 accounts | 310 accounts | $2.1M | $1.3M | $3.2M | 1.2x 🚨 |

**Demand Gen Priority Action:**
- Southeast Emerging: Deploy $380K additional LinkedIn ABM + 2 SDR sequences targeting 47 whitespace Tier 1 accounts. Expected pipeline: $2.8M in 90 days.
- West Enterprise: Activate direct mail gifting to 18 stalled Tier 1 accounts + executive dinner in San Francisco for 12 VP-level prospects. Expected pipeline reactivation: $1.4M.

**Sample Whitespace Heat Map Entry:**
| Account | Score | Est. ACV | Trigger | Owner | Recommended Action |
|---|---|---|---|---|---|
| Vanta Inc. | 91 | $95K | Bombora surge: "revenue forecasting" + headcount growth 40% YoY | Sarah K. | Personal AE outreach + LinkedIn connection + direct mail |
| Brex Financial | 87 | $140K | CRO hire 45 days ago (champion trigger) + Salesforce power user | Marcus T. | SDR multi-touch sequence + SE briefing prep |
| Scale AI | 84 | $78K | G2 category research + Series D funding announcement | David L. | LinkedIn Thought Leader ad sequence + content engagement track |

## Success Metrics

- **Territory Equity Index**: All territories score 60+ within 60 days of implementation
- **Whitespace Penetration Rate**: ≥70% of Tier 1 accounts have CRM activity within 90 days of launch
- **Pipeline Coverage**: All territories reach ≥3x coverage ratio within 2 quarters
- **AE Capacity Utilization**: 80–110% across all territories (no rep over-capacity or under-resourced)
- **Revenue Leakage Reduction**: Deals lost due to "no territory owner" drops to <5% of lost deals
- **Demand Gen ROI by Territory**: Marketing spend per pipeline dollar generated improves 20%+ in gap territories

## Related Prompts

- [GTM Motion Design & Scaling Engine](./GTM-Motion-Design-Scaling-Engine.md) — design the GTM motion before carving territories
- [Vertical Market Penetration & Industry GTM Intelligence Engine](./Vertical-Market-Penetration-&-Industry-GTM-Intelligence-Engine.md) — for vertical-model territory design
- [ICP Identification](../Customer-&-Market-Research/ICP-Identification.md) — foundation for account scoring
- [Marketing Sales Revenue Alignment & SLA Engine](../../01_CMO-&-Leadership/Strategy-&-Planning/Marketing-Sales-Revenue-Alignment-&-SLA-Engine.md) — define the SLAs that govern territory handoffs

## Integration Tips

- **Salesforce**: Load territory model into Salesforce Territory Management (Enterprise Edition+). Create custom fields for ICP Score, Tier Classification, and Whitespace Priority on the Account object. Use assignment rules to auto-route new accounts based on scoring thresholds.
- **HubSpot**: Use HubSpot's Company record Owner field + Teams to implement territory assignments. Create a "Territory" property and "ICP Score" property. Use workflow automation to alert the right AE when a new Tier 1 account enters via inbound.
- **ZoomInfo**: Use ZoomInfo's Streaming Intent feeds to trigger real-time alerts when whitespace accounts spike on priority topics. Connect via Salesforce Data Loader or ZoomInfo's native Salesforce integration.
- **Clari/Gong Forecast**: Segment pipeline forecasting by territory. Monitor territory-level coverage ratios in weekly forecast calls. Use Gong Engage to build account-specific sequences per territory tier.
- **Google Sheets/RevOps Dashboard**: Export territory equity scores and pipeline coverage ratios to a Google Sheet connected to a Looker Studio dashboard. Share with CMO and VP Sales for weekly territory health review.
- **Bombora/6sense**: Create territory-specific intent segments in Bombora or 6sense. Feed intent-surging accounts from each territory directly into the appropriate SDR's sequence queue in Outreach or Salesloft.

## Troubleshooting

**Problem: AEs resist territory changes because they lose accounts they've been working.**
Solution: Run the equity scoring analysis transparently with the sales team. Show each rep their new territory's total ACV potential vs. their old territory. Implement a 90-day transition period where reps retain credit on existing open opportunities even after territorial assignment changes. Create a clear "account movement" log in Salesforce showing why each account moved.

**Problem: The ICP scoring model produces too many Tier 1 accounts — every AE would be over capacity.**
Solution: Tighten the Tier 1 threshold from 75 to 82+. Alternatively, apply a "strategic overlay" to Tier 1: only accounts where you have a named champion contact in CRM, OR accounts where Bombora shows active intent, AND firmographic score ≥75 qualify as true named accounts. The rest move to high-priority Tier 2.

**Problem: Marketing refuses to shift budget to gap territories because existing programs are already generating pipeline elsewhere.**
Solution: Run a pipeline-per-dollar analysis by territory for the past 2 quarters. If gap territories have lower historical ROAS, the model needs to explain why (coverage was lower, not channel effectiveness). Present the whitespace analysis showing untouched high-score accounts — the pipeline gap is a coverage problem, not a market problem. Propose a 90-day pilot: shift 15–20% of demand gen budget to the lowest-coverage territory and measure pipeline generation rate vs. the model prediction.

## Version History
- v1.0: Initial creation (auto-generated)
