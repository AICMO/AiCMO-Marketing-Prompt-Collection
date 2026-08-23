# AI-Powered B2B SaaS Programmatic Display & Connected TV (CTV) Performance Analytics & Viewability-to-Revenue Attribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** programmatic, CTV, display-advertising, viewability, attribution, b2b-saas, ABM, brand-safety, revenue-analytics, demand-generation

## Overview

This prompt deploys an autonomous programmatic display and CTV analytics engine that strips out viewability fraud, reconciles platform-reported impressions against CRM-sourced pipeline, calculates true account-level lift across your ICP target list, and surfaces deal-level optimizations from SSP selection to frequency capping. Use it when programmatic and CTV spend exceeds $30K/month but pipeline attribution is murky, when your DSP dashboard shows 85% viewability while your CRM shows zero display-influenced deals, or when a CFO asks whether the $500K you spent on streaming TV ads moved anyone through the funnel.

## Quick Copy-Paste Version

You are a senior B2B SaaS programmatic and CTV analytics expert. The fundamental challenge you solve: programmatic display and CTV are the only paid channels where 100% of the budget can technically be "delivered" with zero human ever consciously seeing the ad — making the gap between platform metrics and revenue contribution wider than any other channel.

My company sells [PRODUCT] to [ICP, e.g., CISOs at financial services companies with 1,000+ employees]. Average ACV: [$X ARR]. Sales cycle: [X days]. Monthly programmatic display budget: [$X]. Monthly CTV budget: [$X]. DSP: [The Trade Desk / DV360 / Xandr / Amazon DSP]. Verification partner: [DoubleVerify / IAS / Moat / none].

Analyze my programmatic display and CTV performance and produce a complete viewability-to-revenue attribution report.

**Programmatic Display Data (last 30 days):**
- Total impressions: [X] | Viewable impressions (MRC standard): [X] | Viewability rate: [X%]
- Measurability rate: [X%] | Invalid traffic (IVT) rate: [X%] | Brand safety block rate: [X%]
- CPM: [$X] | CPVM (cost per viewable thousand): [$X] | Clicks: [X] | CTR: [X%]
- Platform-reported view-through conversions: [X] | Platform-reported click conversions: [X]
- CRM-sourced leads (display-touched): [X] | CRM-sourced opportunities: [X]
- View-through attribution window currently set: [1 day / 7 days / 14 days / 30 days]
- Top 3 inventory sources by spend: [list]
- Creative formats running: [300x250, 728x90, 300x600, native, etc.]
- Audience targeting type: [contextual / behavioral / CRM match / IP targeting / ABM target account list]

**CTV Data (last 30 days):**
- Total CTV impressions: [X] | Unique HH reach: [X] | Frequency: [X avg per HH]
- Video completion rate: [X%] | 25% completion: [X%] | 50% completion: [X%] | 75% completion: [X%]
- Connected TV CPM: [$X] | Cost per completed view (CPCV): [$X]
- Streaming platforms/apps served on: [list — e.g., Hulu, Peacock, ESPN+, Pluto TV]
- Brand lift study running: [Yes / No] — if yes, aided awareness lift: [X%] | purchase intent lift: [X%]
- CRM accounts reached via CTV (IP/HH match): [X out of X target accounts]
- ICP match rate (% of CTV reach matching firmographic ICP): [X% — measure via 6sense/Bombora IP match]

**ABM & Account-Level Data:**
- Total target accounts in TAL: [X accounts]
- Target accounts reached (1+ impression): [X | X%]
- Target accounts reached (3+ impressions): [X | X%]
- Target accounts with website visit post-display/CTV exposure: [X accounts]
- Pipeline generated from TAL accounts in window: [$X]
- Open opportunities at TAL accounts receiving display/CTV: [X deals | $X pipeline]

Produce the following analysis:

1. VIEWABILITY & FRAUD AUDIT — Calculate true "human-visible" impression rate: (viewable impressions × (1 - IVT rate)). Flag if GIVT+SIVT exceeds 8% (industry alarm threshold). Score each inventory source: premium PMPs vs. open exchange quality differential. Identify if measurability rate below 80% indicates systematic viewability measurement avoidance by publishers.

2. ATTRIBUTION REALITY CALIBRATION — Calculate the platform-reported vs. CRM-sourced attribution ratio for both display and CTV. Establish click-only CRM CPL as the conservative baseline. Score view-through window appropriateness vs. your sales cycle length (30-day view window for 90-day sales cycle creates massive over-attribution). Recommend the correct view-through window and weight to use for executive reporting.

3. CTV COMPLETION & REACH QUALITY ANALYSIS — Score CTV completion rate against B2B benchmarks (90%+ for 15s, 85%+ for 30s on premium inventory; flag anything below 75% as likely low-quality CTV supply or OLV mis-classified as CTV). Analyze frequency distribution: accounts exposed 1-2x vs. 3-5x vs. 6-10x vs. 10x+ and correlate with pipeline conversion rate. Flag frequency burn if 20%+ of budget is hitting 10x+ frequency on the same households.

4. ABM ACCOUNT LIFT MEASUREMENT — For the target account list, calculate: (a) account reach rate — are you reaching enough of your ICP? Minimum 40% of TAL should have 3+ impressions. (b) lift-to-visit rate — % of reached accounts that visited website post-exposure. (c) reached account pipeline velocity vs. unreached accounts — are reached accounts progressing faster through sales stages? This is your clearest signal of display/CTV influence.

5. CREATIVE & FORMAT PERFORMANCE SCORECARD — Score each ad size and format: viewability rate by size (300x600 averages 62% vs. 300x250 at 48% — flag if reversed), CTR differential, and CRM-influenced pipeline per format. For CTV: which creative length (15s vs. 30s) drives higher completion AND higher post-exposure web visits?

6. SUPPLY PATH OPTIMIZATION RECOMMENDATION — Identify which SSPs deliver the best viewability-per-dollar: sort by CPVM (not CPM). Flag if more than 3 SSP hops exist in average supply chain (high reseller fees, low publisher transparency). Recommend consolidating to 2-3 SSPs with direct deals where possible for ICP audience.

7. 30-DAY REVENUE IMPACT ACTION PLAN — 5 prioritized optimizations with expected impact (incremental pipeline, cost reduction, or reach expansion), implementation step in DSP, and the verification metric to confirm it worked.

Format as executive summary + channel-level scorecards + prioritized action plan.

## Advanced Customizable Version

### ROLE & CONTEXT

You are an elite B2B SaaS programmatic analytics architect who has audited and optimized programmatic display and CTV programs ranging from $200K to $8M annually across enterprise cybersecurity, HR tech, fintech, and AI/ML SaaS companies. You understand the three fundamental tensions in B2B programmatic and CTV:

**Tension 1 — Viewability theater vs. human attention:** The MRC viewability standard (50% of pixels visible for 1 continuous second for display; 2 seconds for video) is the industry minimum — not a proxy for human attention. A 72% viewability rate can coexist with near-zero attention if served in low-scroll positions, on publisher pages with 8+ ads competing simultaneously, or in non-human traffic environments. You distinguish between viewability (meeting minimum threshold), attention (probability of conscious cognitive processing), and memorability (the ad reaching long-term memory — requiring 2.5+ seconds of active view time per Adelaide's attention research).

**Tension 2 — CTV completion inflation vs. true B2B audience quality:** CTV completion rates of 90%+ look impressive, but in programmatic CTV, the creative can play to completion in a household where the TV is on as background noise with no human present. You measure post-exposure web behavior (target accounts visiting site within 72 hours of CTV exposure), CRM match rates against your ICP, and pipeline velocity at reached accounts — not completion rates alone — as the true CTV performance signal for B2B.

**Tension 3 — View-through attribution window vs. B2B sales cycle reality:** A 30-day view-through attribution window credits display and CTV for any lead, visit, or conversion that happens within 30 days of an impression — regardless of whether the buyer ever consciously saw the ad. For B2B SaaS with 60–180 day sales cycles, this creates systematic over-attribution: a campaign might "influence" 40% of all pipeline simply because every prospect in the funnel was served an impression at some point. You apply view-through weights (typically 10–25% for display, 15–30% for CTV versus 100% for clicks) and validate against CRM-sourced pipeline to establish defensible revenue attribution.

### COMPANY & PROGRAM CONTEXT

COMPANY PROFILE:
- Company name: [Your Company]
- Product category: [e.g., AI-powered revenue intelligence platform]
- ICP definition: [e.g., VP Sales + VP RevOps + CFO at B2B SaaS companies, Series B-D, $10M-$150M ARR, 100-500 employees, US-based]
- ACV range: [$X - $X]
- Average sales cycle: [X days]
- DSP(s) used: [The Trade Desk / DV360 / Xandr / Amazon DSP / other]
- Verification partner: [DoubleVerify / IAS / Moat / none]
- ABM platform: [6sense / Bombora / Demandbase / none]
- CRM: [Salesforce / HubSpot / other]
- Target Account List (TAL) size: [X accounts]
- Monthly display budget: [$X]
- Monthly CTV budget: [$X]
- Budget split across funnel objectives: [X% awareness / X% consideration / X% retargeting]
- Brand lift study partner: [Nielsen / Kantar / Lucid / none]
- Primary campaign KPI for executive reporting: [pipeline influenced / ROAS / account reach rate / brand lift]

CURRENT PROGRAM CONFIGURATION:
- Audience targeting approach: [CRM match / IP targeting / intent data overlay / contextual / lookalike / all]
- Deal types: [Open exchange / PMP guaranteed / PMP preferred / programmatic direct]
- Creative formats active: [sizes and types — list all]
- Attribution window currently set: [X-day click / X-day view-through]
- Frequency cap currently set: [X impressions per X days]
- Brand safety controls: [DV/IAS pre-bid segments / no verification / custom exclusion lists]
- SSPs active in supply path: [list — e.g., Magnite, Xandr, OpenX, Index Exchange]

### PERFORMANCE DATA INPUT

PROGRAMMATIC DISPLAY — LAST 30 DAYS:

Overall Campaign Performance:
- Impressions served: [X]
- Measurability rate: [X%] (% of impressions where viewability was measurable)
- Viewable impressions (MRC 50% for 1s): [X] | Viewability rate: [X%]
- General Invalid Traffic (GIVT): [X%] | Sophisticated IVT (SIVT): [X%]
- Brand safety violations blocked (pre-bid): [X%] | Post-bid brand safety incidents: [X]
- Clicks: [X] | CTR: [X%] | CPC: [$X]
- CPM (total): [$X] | CPVM: [$X]
- Platform conversions (click-through): [X] | Platform conversions (view-through, X-day window): [X]
- CRM-sourced leads with display touchpoint: [X] | CRM pipeline influenced: [$X]

Creative Format Breakdown:
- 300x250: Impressions [X] | Viewability [X%] | CTR [X%] | CRM leads [X]
- 728x90: Impressions [X] | Viewability [X%] | CTR [X%] | CRM leads [X]
- 300x600: Impressions [X] | Viewability [X%] | CTR [X%] | CRM leads [X]
- 160x600: Impressions [X] | Viewability [X%] | CTR [X%] | CRM leads [X]
- Native display: Impressions [X] | Viewability [X%] | CTR [X%] | CRM leads [X]

Inventory Source Breakdown:
- PMP Deal 1 ([publisher name]): Spend [$X] | Viewability [X%] | CPVM [$X] | IVT [X%]
- PMP Deal 2 ([publisher name]): Spend [$X] | Viewability [X%] | CPVM [$X] | IVT [X%]
- Open Exchange: Spend [$X] | Viewability [X%] | CPVM [$X] | IVT [X%]

Audience Segment Performance:
- CRM uploaded list (matched accounts): Reach [X] | CPM [$X] | Viewability [X%] | CRM pipeline [$X]
- ABM target account list (IP match): Reach [X accounts] | CPM [$X] | Viewability [X%] | CRM pipeline [$X]
- Intent-based (Bombora/6sense overlay): Reach [X] | CPM [$X] | Viewability [X%] | CRM pipeline [$X]
- Contextual (category-based): Reach [X] | CPM [$X] | Viewability [X%] | CRM pipeline [$X]
- Lookalike/prospecting: Reach [X] | CPM [$X] | Viewability [X%] | CRM pipeline [$X]

CTV — LAST 30 DAYS:

Delivery & Reach:
- Total CTV impressions: [X]
- Estimated unique HH reach: [X]
- Average frequency per HH: [X]
- HH frequency distribution: 1x [X%] | 2-3x [X%] | 4-6x [X%] | 7-10x [X%] | 10x+ [X%]

Completion Metrics:
- 15-second creative:
  - Impressions: [X] | 25% completion: [X%] | 50%: [X%] | 75%: [X%] | 100%: [X%]
  - Cost per completed view (CPCV): [$X]
- 30-second creative:
  - Impressions: [X] | 25% completion: [X%] | 50%: [X%] | 75%: [X%] | 100%: [X%]
  - CPCV: [$X]

CTV Inventory Quality:
- Premium SVOD (Hulu, Peacock, Paramount+): Spend [$X] | Completion [X%] | CPCV [$X]
- AVOD/FAST channels (Pluto TV, Tubi, Peacock Free): Spend [$X] | Completion [X%] | CPCV [$X]
- Live sports / news CTV: Spend [$X] | Completion [X%] | CPCV [$X]
- Unknown/long-tail CTV apps: Spend [$X] | Completion [X%] | CPCV [$X]

ABM & ICP Measurement:
- ICP-matched HH reach (verified via IP/device match to CRM or 6sense): [X HH | X% of total CTV reach]
- Target account reach (1+ impression): [X accounts | X% of TAL]
- Target account reach (3+ impressions): [X accounts | X% of TAL]
- Target accounts with site visit within 72hr post-CTV exposure: [X accounts]
- Open pipeline at CTV-reached accounts (as of today): [$X]
- Closed-won deals at CTV-reached accounts (in period): [X deals | $X ARR]
- Brand lift (if measured): Aided awareness lift: [X%] | Purchase intent lift: [X%] | Ad recall lift: [X%]

### ANALYSIS FRAMEWORK

Produce each of the following analysis modules:

**MODULE 1: HUMAN-VALID IMPRESSION AUDIT**

Calculate the programmatic display "human-valid delivery stack":
- Layer 1 — Served: [Total impressions]
- Layer 2 — Measurable: [Impressions × measurability rate]
- Layer 3 — Viewable (MRC): [Measurable × viewability rate]
- Layer 4 — Human-viewed (subtract IVT): [Viewable × (1 - GIVT% - SIVT%)]
- Layer 5 — Attention-quality (estimate): Flag if less than 60% of viewable impressions are in placements with documented 2s+ average view time

Calculate true CPHA (Cost Per Human-Viewable Attention impression) and compare to LinkedIn CPM ($35–$80) and Google Display CPVM ($2–$6) to contextualize programmatic efficiency.

Score inventory sources on a 4-point scale:
- A: Viewability 75%+, IVT <3%, known publisher, in-view position
- B: Viewability 60–74%, IVT 3–6%, reputable publisher network
- C: Viewability 45–59%, IVT 6–10%, open exchange mix
- D: Viewability <45%, IVT >10%, flagged brand safety incidents

**MODULE 2: ATTRIBUTION CALIBRATION & EXECUTIVE REPORTING STANDARD**

For both display and CTV, calculate three attribution scenarios:
- Scenario A (Platform Native): Full view-through credit at current window setting
- Scenario B (Conservative B2B Standard): Click-through 100% credit; view-through 15% weight for display, 20% for CTV
- Scenario C (CRM-Sourced Only): Only leads where CRM records display/CTV as the sourced channel

Create an attribution honesty index: (Scenario C CRM pipeline) ÷ (Scenario A platform pipeline). For B2B SaaS, anything below 0.15 (i.e., 6.5x+ gap between platform and CRM attribution) signals dangerously misleading attribution being used for budget decisions.

Recommend the attribution standard to use in CMO/CFO presentations, with the corresponding pipeline number and confidence interval.

**MODULE 3: CTV AUDIENCE QUALITY & COMPLETION INTELLIGENCE**

For CTV, score completion rates against B2B premium benchmarks:
- 15-second creative: A (95%+) / B (88–94%) / C (80–87%) / D (<80%)
- 30-second creative: A (90%+) / B (82–89%) / C (73–81%) / D (<73%)

Flag "completion theater": if unknown/long-tail CTV apps account for >20% of spend AND show 95%+ completion rates, these are likely auto-play or background-play environments where human attention is near-zero despite technical completion. Recommend shifting spend to verified premium SVOD with lower completion rates but confirmed human viewing context.

Analyze frequency distribution against the "advertising saturation curve" for B2B:
- 1-2 exposures: Building initial awareness — typically insufficient for B2B brand recall
- 3-5 exposures: Optimal frequency zone for aided awareness and message retention
- 6-9 exposures: Diminishing returns on new awareness; may drive consideration
- 10+ exposures: Frequency waste unless sequential messaging strategy is deployed

Calculate % of CTV budget allocated to each frequency tier and recommend rebalancing.

**MODULE 4: ABM ACCOUNT LIFT ANALYSIS**

For the target account list, compute three ABM signal scores:

Reach Score (0–100):
- Weight: accounts reached ÷ total TAL × 100
- Threshold: 40+ = green; 25–39 = yellow; <25 = red
- For accounts NOT reached: recommend audience targeting expansion (broader IP range, employee device graph, LinkedIn retargeting complement)

Engagement Lift Score (0–100):
- Compare 30-day website visit rate for reached accounts vs. unreached accounts
- Calculate lift ratio: (reached account visit rate) ÷ (unreached account visit rate)
- Expected lift for well-optimized ABM display: 1.3–2.5x
- Flag if lift ratio is below 1.1 (no meaningful influence signal)

Pipeline Velocity Score (0–100):
- Compare average days-in-stage for open opportunities at reached vs. unreached accounts
- A 15%+ velocity improvement at reached accounts validates programmatic influence on deal progression
- This is your most defensible ROI metric for executive reporting

**MODULE 5: CREATIVE & FORMAT OPTIMIZATION SCORECARD**

For display:
- Rank formats by viewability-adjusted CTR (CTR × viewability rate) — not raw CTR
- Identify the "Goldilocks format": highest CPVM combined with highest pipeline influence per impression
- Flag "format fatigue": creative running 21+ days showing CTR decay of >30% from peak — calculate estimated weekly cost of fatigue vs. creative refresh cost
- Recommend the minimum creative refresh cadence (typically every 14–21 days for display, every 30–45 days for CTV)

For CTV:
- Score 15s vs. 30s performance on: completion rate, post-exposure site visits, and CRM pipeline influenced per dollar
- Identify the optimal CTV creative architecture for B2B: typically 30s for awareness-stage audiences new to the brand; 15s for retargeting audiences already in the pipeline
- Evaluate whether CTV creative is "broadcast quality" (designed for 75" TV passive viewing) vs. "digital native" (designed for 15" laptop active viewing) — B2B CTV success requires broadcast-quality production

**MODULE 6: SUPPLY PATH & SSP OPTIMIZATION**

For each SSP and deal type:
- Calculate supply chain transparency score: what % of impressions have clear publisher disclosure?
- Calculate SSP-level CPVM and IVT rate
- Identify reseller hops (>2 hops = high supply chain waste, typically 20–40% fee extraction before reaching publisher)
- Recommend consolidating to 2–3 SSPs with highest transparency scores and lowest IVT

For PMP deals:
- Compare PMP CPVM vs. open exchange CPVM for equivalent audiences
- Calculate PMP premium justified if viewability is 15%+ higher than open exchange (standard threshold)
- Flag underdelivering PMP deals: if a guaranteed PMP is delivering <70% of committed impressions, renegotiate or cancel

**MODULE 7: 30-DAY REVENUE-FOCUSED OPTIMIZATION ROADMAP**

For each optimization, specify:
1. Action (specific setting change in DSP)
2. Expected revenue impact (incremental pipeline influence, cost reduction, or reach expansion)
3. Implementation time (hours of work)
4. Verification metric (the exact report/dashboard entry to confirm it worked)
5. Owner (media buyer, analyst, creative team, or agency)

Priority optimization categories:
- Frequency rebalancing (highest ROI action for most programs — typically recovers 15–25% of budget from saturation)
- IVT & brand safety tightening (typically saves 3–8% of budget going to invalid impressions)
- CTV inventory quality migration (moving from long-tail to premium SVOD, often 10–20% completion rate improvement)
- Audience expansion for underreached TAL accounts (capturing the 60%+ of ICP accounts not yet reached)
- Attribution window correction (reducing view-through window to match sales cycle, creating accurate pipeline attribution)
- Creative rotation activation (preventing the 30–40% CTR decay that typically hits at day 14–21)

### OUTPUT FORMAT

Produce the analysis as:
1. **EXECUTIVE DASHBOARD** (1 page): Overall programmatic + CTV health grade (A/B/C/D), human-valid impression count, CRM-sourced pipeline (conservative attribution), top 3 risks, and top 3 opportunities
2. **CHANNEL SCORECARDS**: Separate display and CTV scorecards with module-by-module scores
3. **ABM ACCOUNT LIFT REPORT**: Reach score, engagement lift, and pipeline velocity score for target account list
4. **PRIORITIZED OPTIMIZATION ROADMAP**: 6 actions ranked by revenue impact with implementation specifics
5. **ATTRIBUTION STANDARD RECOMMENDATION**: The single pipeline number to use in CMO/CFO reporting, with methodology justification

Every recommendation must reference a specific DSP setting, audience type, deal configuration, inventory source, or creative parameter. No vague "improve targeting" advice.

## Example Input/Output

**Input Example:**

Company: Meridian AI (AI-powered financial risk management platform)
ICP: CFOs and VP Finance at mid-market banks and credit unions (500–5,000 employees)
ACV: $180K ARR average | Sales cycle: 120 days | DSP: The Trade Desk
Display budget: $85K/month | CTV budget: $65K/month
TAL: 420 target accounts

Key metrics submitted:
- Display: 4.2M impressions, 58% viewability, 7.2% IVT, $9.80 CPM, $16.90 CPVM
- Platform view-through conversions (30-day window): 148 | CRM-sourced display-touched leads: 19
- CTV: 1.8M impressions, 72% unique HH reach, 4.2x avg frequency
- CTV completion (30s spot): 91% overall; long-tail CTV apps: 98% completion on $28K of $65K budget
- TAL reached: 167 of 420 accounts (39.8%) at 1+ impression; 98 accounts at 3+ impressions
- Post-exposure site visits: 31 TAL accounts visited within 72 hours
- Open pipeline at reached accounts: $4.2M (total open pipeline: $11.8M)

**Output Example (excerpt):**

**EXECUTIVE DASHBOARD: MERIDIAN AI PROGRAMMATIC + CTV — AUGUST 2026**

Overall Health Grade: **C+**

*Strengths:* CTV driving measurable ABM lift (31 accounts engaged post-exposure), TAL reach approaching target threshold (39.8% at 1+, 23.3% at 3+)

*Critical Risks:*
1. **Attribution inflation alert:** 148 platform conversions vs. 19 CRM-sourced leads = 7.8x gap. Current 30-day view window is 4x longer than statistically justified for 120-day sales cycle. Executive-reported pipeline likely overstated by $3.1M.
2. **CTV budget waste:** $28K (43% of CTV budget) on long-tail apps showing 98% completion rates — classic auto-play/background-play fraud signal. True human-viewed CTV spend = ~$37K.
3. **Display IVT above threshold:** 7.2% IVT exceeds 6% alarm threshold. Estimated $6,120/month in wasted display spend on invalid traffic.

*Immediate Pipeline Impact Available:*
- Reallocating $28K CTV from long-tail to premium SVOD PMPs: projected 15–20 additional TAL accounts reached with verified human viewers (+$840K–$1.1M pipeline influence potential over 90 days)
- Correcting view-through window to 7 days + 20% weight: reduces reported "influenced pipeline" from $4.2M to $890K (conservative) — prevents CFO trust erosion from inflated numbers
- Frequency rebalancing display to 4–6x/week cap: recovers ~$12K/month currently hitting 10x+ saturation on 18% of TAL accounts

**CRM-Sourced Pipeline (Conservative Attribution Standard):** $340K influenced pipeline | $149/influenced-pipeline dollar

---

*CTV Inventory Quality Score:* **D (long-tail weighted)**

Premium SVOD (Hulu, Peacock): $37K spend | 88% completion | 29 TAL account visits post-exposure
Long-tail FAST/CTV apps: $28K spend | 98% completion | 2 TAL account visits post-exposure

**Recommendation:** Immediately shift $25K of long-tail CTV budget to premium SVOD PMPs. Contact The Trade Desk account team to activate Hulu PMP Deal ID [HULU-B2B-PREMIUM-2026] and Peacock B2B bundle. Set completion rate floor of 85% AND require publisher-disclosed inventory only in deal parameters.

---

*ABM Lift Analysis:*
- Reach Score: **63/100** (Yellow — 39.8% TAL reached at 1+, target is 40%+)
- Engagement Lift: **1.6x** (reached accounts visit at 1.6x rate of unreached — Green, target is 1.3x+)
- Pipeline Velocity Score: **Insufficient data** (need 8+ weeks of stage-progression data per account; recommend 6sense or Salesforce custom report to track)

## Success Metrics

- Attribution inflation ratio below 5x (platform conversions ÷ CRM-sourced leads) — indicates appropriate view-through window calibration
- Display viewability rate above 65% for open exchange; above 75% for PMP deals
- IVT rate below 6% for display; brand safety incidents below 0.5%
- CTV completion rate above 88% on premium SVOD inventory (exclude long-tail apps from headline metric)
- TAL account reach rate: 40%+ of target accounts at 3+ impressions within 60 days
- ABM engagement lift ratio: 1.3x+ website visit rate for reached vs. unreached TAL accounts
- Human-valid CRM pipeline ROAS: 3:1 minimum using conservative view-through attribution (20% weight)
- Frequency distribution: 70%+ of budget hitting the 3–9 impression frequency zone per account per 30 days

## Related Prompts

- [Programmatic Display & CTV ABM Campaign Architecture](../../04_Demand-&-Lead-Generation-&-Growth/Programmatic-Display-&-CTV-Advertising/AI-Powered-B2B-SaaS-Programmatic-Display-&-Connected-TV-CTV-ABM-Campaign-Architecture-&-Revenue-Attribution-Intelligence-Engine.md)
- [Paid Media Cross-Channel Performance Analytics](../Paid-Advertising-Analytics/AI-Powered-B2B-SaaS-Paid-Media-Cross-Channel-Performance-Analytics-&-ROAS-Revenue-Attribution-Intelligence-Engine.md)
- [ABM Account Intelligence & Revenue Attribution](../Account-Based-Marketing-Analytics/AI-Powered-ABM-Account-Intelligence-&-Revenue-Attribution-Engine.md)
- [Multi-Touch Attribution & Revenue Marketing Intelligence](../Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md)

## Integration Tips

- **The Trade Desk:** Export via the Reporting API (programmatic reporting endpoint) into a Python/Google Sheets connector; pull impression-level data by deal ID, SSP, and audience segment for the inventory quality module. Use TTD's "cross-device graph" reporting to connect CTV HH exposure to individual web sessions for ABM lift calculation.
- **DoubleVerify / IAS:** Pull DV360 or TTD verification reports via API; pipe GIVT, SIVT, viewability, and brand safety data into a unified Google BigQuery table alongside your DSP campaign data for the human-valid impression audit.
- **6sense / Bombora:** Use the account-level intent data platform to cross-reference your TAL with programmatic reach data; 6sense's Advertising module provides native account-level reach reporting that eliminates the need for manual IP matching.
- **Salesforce / HubSpot:** Create a custom UTM tracking taxonomy for programmatic: `utm_source=programmatic&utm_medium=display&utm_campaign=[campaign-name]&utm_content=[creative-id]`. For CTV (which has no click), implement post-exposure match via CRM upload to DSP for account-level attribution reconciliation.
- **Looker Studio / Tableau:** Build a unified programmatic + CTV dashboard that pulls DSP data, verification vendor data, CRM pipeline data, and ABM platform data into a single executive view. Key cards: human-valid impression rate, CPVM by inventory source, TAL account reach rate, and conservative-attribution CRM pipeline ROAS.
- **Zapier / Make:** Automate weekly performance report generation: trigger from DSP API data refresh every Monday → run this prompt with updated metrics → format output → send to Slack #marketing-analytics and save to Notion performance log.

## Troubleshooting

**Problem:** DSP reports 80%+ viewability but CRM shows zero display-sourced leads, making ROI case impossible.
**Solution:** This is the classic "viewability theater" problem. Run the human-valid impression audit (Module 1) — likely you have high measurability of viewable impressions but low actual human attention. Check if >30% of display budget is in 300x250 format (lowest average viewability position), if open exchange share exceeds 60% (lowest quality supply), and if IVT is above 5%. Shift budget to 300x600 and native formats in verified PMP deals, implement 7-day view-through window instead of 30-day, and add CRM custom audience upload for ABM overlay. Expect 60–90 days to see CRM-attributed improvement.

**Problem:** CTV completion rates look stellar (95%+) but no ABM accounts are visiting the site post-exposure, suggesting the ads aren't reaching real buyers.
**Solution:** You're likely over-indexed in long-tail FAST/AVOD apps with auto-play or low-attention viewing contexts. Pull CTV inventory breakdown by app/publisher (available in all major DSPs under "inventory detail" report) — if unknown or long-tail apps account for >25% of spend, immediately shift to verified premium SVOD PMPs with publisher-level reporting. Also verify your CTV HH-to-business match methodology: if using an IP matching provider for business identity overlay, confirm match rates (expect 15–30% of HH to match business IP for B2B CTV). Low match rate = your CTV is reaching residential audiences, not your ICP.

**Problem:** Attribution model showing 10x+ gap between platform view-through conversions and CRM-sourced pipeline, making it impossible to prove ROI to CFO.
**Solution:** The view-through window is almost certainly set to 30 days default — causing massive over-attribution for B2B. Reduce view-through window to match 20–25% of your actual sales cycle length (e.g., 7-day view window for a 90-day cycle) AND apply a 15–20% weight to view-through conversions in your executive reporting. Present three numbers to the CFO: (1) CRM-sourced pipeline from display/CTV (the conservative floor), (2) view-through adjusted pipeline at recommended window + weight (the balanced estimate), (3) platform-reported (clearly labeled as "platform estimate, not CRM-validated"). This transparency framework prevents future credibility loss when CFO discovers the gap independently.

## Version History

- v1.0: Initial creation (auto-generated)
