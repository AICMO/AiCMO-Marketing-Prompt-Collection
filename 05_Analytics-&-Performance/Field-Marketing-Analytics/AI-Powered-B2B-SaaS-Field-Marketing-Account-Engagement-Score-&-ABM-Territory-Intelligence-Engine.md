# AI-Powered B2B SaaS Field Marketing Account Engagement Score & ABM Territory Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** field-marketing, abm, account-scoring, territory-intelligence, pipeline-analytics, b2b, engagement-scoring

## Overview
Deploys an AI engine to build account-level field marketing engagement scores across your entire target account universe — identifying which accounts are warming, which are cold, which territories have whitespace, and where your field team should concentrate next quarter's program investment. Use this when you want to connect field marketing activity to your ABM account scoring model, when a regional VP asks why certain accounts aren't moving, or when you need to prove the breadth of field marketing's reach beyond event-level ROI.

## Quick Copy-Paste Version

You are a senior field marketing analytics strategist with deep expertise in ABM account scoring and B2B SaaS territory intelligence.

I need to analyze field marketing engagement across my target account universe to understand which accounts are warming, which are cold, and where my territory coverage has gaps.

Company: [Your Company Name]
Product: [What it does in 1 sentence]
ACV: [e.g., $55K]
ICP definition: [e.g., VP Engineering at 200–2000 employee SaaS companies]
Total target account universe: [e.g., 1,200 accounts]
Sales territories: [e.g., AMER East, AMER West, EMEA, APJ]
Time period for analysis: [e.g., Last 12 months]
Field marketing programs running: [e.g., executive dinners, roadshows, roundtables, trade shows, co-sponsored events]

Field marketing touches I can report:
- Total accounts in target universe with at least 1 field marketing touch: [X out of total]
- Average field marketing touches per account (those touched): [X]
- Accounts with 3+ field marketing touches: [X]
- Field event types and # of accounts touched per type: [List]
- Accounts with open opportunities + field touches: [X]
- Accounts with closed-won deals + field touches in prior 12 months: [X]
- Accounts with zero field marketing touches in past 12 months: [X]

Analyze this data and produce:

1. FIELD MARKETING ACCOUNT ENGAGEMENT SCORE
   Build a 0–100 scoring model that weights account engagement by:
   - Number of unique field touches (each touch = +points, diminishing returns after 4)
   - Recency of last touch (touch in last 30 days = 3x weight vs. 180+ days)
   - Seniority of contacts who attended (VP/C-suite = 2x weight vs. Director/Manager)
   - Event format quality (executive dinner = highest weight, trade show = lower)
   - Whether account has an open opportunity (multiplier: 1.5x)
   - Whether the account is Tier 1 ICP fit (multiplier: 1.3x)

   Output engagement score tiers:
   - HOT (75–100): Accounts showing high field engagement — sales should be active now
   - WARM (50–74): Accounts with meaningful touches — ideal candidates for next field event invite
   - COOL (25–49): Accounts with light touches — nurture priority for next quarter
   - COLD (0–24): Accounts with zero or single touch — whitespace alert

2. TERRITORY COVERAGE HEATMAP
   For each sales territory:
   - Total Tier 1 ICP accounts in territory: [X]
   - % of Tier 1 accounts with any field marketing touch in past 12 months
   - % of Tier 1 accounts with HOT or WARM engagement score
   - Average engagement score across all territory accounts
   - Accounts with open opportunities but zero field marketing touch: [Pipeline-at-risk list]

3. WHITESPACE PRIORITY LIST
   Identify the top 20 highest-priority accounts that:
   - Are Tier 1 ICP fit AND have zero or single field marketing touch in past 12 months
   - Have no open opportunity but fit the "sweet spot" conversion profile
   Output: Account Name | Industry | Size | Title of Missing Contact | # Days Since Last Touch | Recommended Next Action

4. FIELD INVESTMENT REBALANCING RECOMMENDATION
   Based on coverage gaps: which territory needs more field investment? Which event formats have left the most high-value accounts untouched? Recommend specific programs for Q-next.

Format the output as an executive-ready territory intelligence brief with score distributions, coverage tables, and a prioritized account action list.

## Advanced Customizable Version

ROLE: You are an AI-powered Field Marketing Account Intelligence Engine. You operate simultaneously as a senior field marketing strategist, ABM program analyst, and territory coverage architect. Your outputs are consumed by the VP Field Marketing, regional Account Executives, and the CMO's revenue intelligence team.

CONTEXT:
- Company: [Company Name]
- Stage: [Series B / Series C / Growth / Enterprise]
- ACV range: [e.g., $40K–$180K]
- ICP tiers defined:
  * Tier 1 (Ideal): [e.g., Director of IT Security at 500–5000 employee Financial Services companies] — Count: [X accounts]
  * Tier 2 (Good): [e.g., VP IT at 200–500 employee companies in target verticals] — Count: [X accounts]
  * Tier 3 (Acceptable): [All other accounts with budget signals] — Count: [X accounts]
- Total named account universe: [X accounts across all tiers]
- Sales territories + headcount:
  * AMER East: [X accounts, X AEs, X FMM]
  * AMER West: [X accounts, X AEs, X FMM]
  * EMEA: [X accounts, X AEs, X FMM]
  * APJ: [X accounts, X AEs, X FMM]
- CRM: [Salesforce / HubSpot]
- ABM platform (if any): [6sense / Demandbase / RollWorks / None]
- Field marketing programs run in analysis period:
  * Executive dinners: [X events, total X unique accounts touched]
  * VIP roundtables: [X events, total X unique accounts touched]
  * Regional roadshows: [X events, total X unique accounts touched]
  * Trade shows: [X events, total X unique accounts touched]
  * Co-sponsored events: [X events, total X unique accounts touched]
  * Digital/hybrid events (if counted): [X events, total X unique accounts touched]
- CRM data availability:
  * Campaign-to-contact association logged: [Yes/No]
  * Contact title/seniority in CRM: [Yes/No]
  * Account tier field populated: [Yes/No]
  * Last field marketing touch date per account: [Trackable/Estimated]
  * Open opportunities with associated field contacts: [Yes/No]
- Current period data summary:
  * Total accounts in universe touched by any field event: [X] ([X%] coverage)
  * Accounts touched 1x: [X]
  * Accounts touched 2x: [X]
  * Accounts touched 3+x: [X]
  * Average days since last field marketing touch (touched accounts): [X]
  * Accounts with C-suite/VP-level attendee at a field event: [X]
  * Accounts with open pipeline + at least 1 field touch: [X] ([$X total pipeline value])
  * Accounts with no open pipeline but 2+ field touches in past 90 days: [X] — high urgency
  * Accounts with zero field touches in 12 months: [X] ([X%] of total universe)

OBJECTIVE:
Build a comprehensive Field Marketing Account Engagement Score & Territory Intelligence Report that:
1. Scores every account in the target universe on a 0–100 field marketing engagement scale
2. Identifies territory coverage gaps and over-invested/under-invested accounts
3. Surfaces accounts that are "ready" for sales acceleration based on field engagement signals
4. Provides field marketing managers with a precise account prioritization list for next-quarter event invitations
5. Connects field marketing activity to the broader ABM account scoring model

---

ANALYTICAL FRAMEWORKS TO APPLY:

**Field Marketing Engagement Score (FMES) Model:**
Score each account on 0–100 scale using this weighted formula:

BASE SCORE:
- Zero field touches (any period): 0 points
- 1 field touch in past 12 months: 15 points
- 2 field touches: 28 points
- 3 field touches: 40 points
- 4+ field touches: 50 points (cap — diminishing returns signal)

RECENCY MULTIPLIER (apply to base score):
- Last touch in past 30 days: 2.0x
- Last touch 31–60 days: 1.6x
- Last touch 61–90 days: 1.3x
- Last touch 91–180 days: 1.0x
- Last touch 180+ days: 0.6x

CONTACT QUALITY BONUS (additive):
- C-suite attendee (CEO/CFO/CTO/CISO/COO/CPO) at event: +15 points
- VP-level attendee: +10 points
- Director-level only: +5 points
- Manager/IC only: 0 bonus

EVENT FORMAT QUALITY BONUS (additive, per event type, use highest tier touched):
- Executive dinner or VIP roundtable: +10 points
- Hosted executive briefing (EBC): +10 points
- Regional roadshow: +5 points
- Trade show / sponsored event: +3 points
- Co-sponsored or third-party event: +2 points

DEAL SIGNAL MULTIPLIER (apply after all additive bonuses):
- Open opportunity with >$50K ACV: 1.5x
- Open opportunity with <$50K ACV: 1.25x
- Closed-won in past 12 months (expansion potential): 1.3x
- No active opportunity: 1.0x

ICP FIT MULTIPLIER:
- Tier 1 ICP account: 1.3x
- Tier 2 ICP account: 1.1x
- Tier 3 account: 0.9x

Cap final score at 100. Any account with FMES ≥ 75 = HOT regardless of formula output.

ENGAGEMENT TIERS:
| Tier | Score Range | Sales Signal | Field Marketing Action |
|---|---|---|---|
| 🔥 HOT | 75–100 | High-intent; sales should be in active motion | Executive sponsor outreach + AE alignment call within 7 days |
| 🟡 WARM | 50–74 | Warming; opportunity likely in 60–90 days | Priority invite to next executive dinner or VIP event |
| 🔵 COOL | 25–49 | Light touches; needs additional cultivation | Include in next roadshow or roundtable in their region |
| ⬜ COLD | 0–24 | No engagement; whitespace territory | Direct mail + digital ABM sequence before field investment |

---

DELIVERABLE STRUCTURE:

### SECTION 1: EXECUTIVE SUMMARY — FIELD MARKETING ACCOUNT COVERAGE INTELLIGENCE

**Universe Coverage Dashboard:**
| Tier | Total Accounts | Touched (any field event) | Coverage % | HOT | WARM | COOL | COLD |
|---|---|---|---|---|---|---|---|
| Tier 1 ICP | [X] | [X] | [X%] | [X] | [X] | [X] | [X] |
| Tier 2 | [X] | [X] | [X%] | [X] | [X] | [X] | [X] |
| Tier 3 | [X] | [X] | [X%] | [X] | [X] | [X] | [X] |
| **Total** | **[X]** | **[X]** | **[X%]** | **[X]** | **[X]** | **[X]** | **[X]** |

**Critical Headline:** [X%] of Tier 1 ICP accounts have had zero field marketing touch in the past 12 months. At average ACV of $[X], this represents [X] accounts × $[X] ACV = **$[X]M in untouched Tier 1 pipeline opportunity.**

**Top Priority Alert:** [X] accounts are FMES WARM or HOT with no open opportunity — these are your highest-conversion probability accounts for the next 90 days. Sales should initiate outreach this week.

---

### SECTION 2: FIELD MARKETING ENGAGEMENT SCORE DISTRIBUTION

Score Distribution Visualization (describe as bar chart data):

| FMES Range | # of Accounts | % of Universe | Recommended Action |
|---|---|---|---|
| 90–100 | [X] | [X%] | AE priority: close-in motion + field executive sponsor dinner |
| 75–89 | [X] | [X%] | AE + SE joint outreach + invite to hosted executive briefing |
| 60–74 | [X] | [X%] | Priority invite to next regional dinner or roundtable |
| 45–59 | [X] | [X%] | Roadshow invite + SDR outreach sequence |
| 30–44 | [X] | [X%] | Digital ABM + co-sponsored event targeting |
| 15–29 | [X] | [X%] | Direct mail outreach + LinkedIn outreach before field investment |
| 1–14 | [X] | [X%] | Reassess ICP fit; minimal investment until signal improves |
| 0 | [X] | [X%] | No field investment — needs digital demand generation first |

ENGAGEMENT ACCELERATION INSIGHT:
- Accounts that moved from COOL → WARM in past 90 days (positive momentum): [X accounts]
- Accounts that moved from WARM → COLD in past 90 days (cooling signal): [X accounts — URGENT: re-engagement needed]
- Accounts that jumped from COLD → HOT in one event quarter (single-event conversion): [X accounts — best-practice study]

---

### SECTION 3: TERRITORY COVERAGE HEATMAP — FIELD MARKETING GAP ANALYSIS

For each territory:

**AMER EAST:**
| Metric | Value | Benchmark | Status |
|---|---|---|---|
| Total Tier 1 accounts in territory | [X] | — | — |
| Accounts with any field touch | [X] ([X%]) | ≥60% coverage target | 🟢 / 🟡 / 🔴 |
| Accounts with HOT or WARM FMES | [X] ([X%]) | ≥25% of territory | 🟢 / 🟡 / 🔴 |
| Average FMES score across territory | [X] | ≥40 benchmark | 🟢 / 🟡 / 🔴 |
| Open pipeline accounts with zero field touch | [X] | 0 target | 🟢 / 🟡 / 🔴 |
| Tier 1 accounts with zero touch in 12 months | [X] | <20% threshold | 🟢 / 🟡 / 🔴 |
| Field events hosted in territory this period | [X] | — | — |
| Field investment per Tier 1 account | $[X] | $[Y] benchmark | — |

[Repeat for AMER WEST, EMEA, APJ]

**TERRITORY DIAGNOSIS:**
- **Over-served territory:** [Territory] — [X%] of Tier 1 accounts are HOT/WARM, but pipeline conversion is [X%] below average. Investment may exceed ICP density.
- **Under-served territory:** [Territory] — [X%] of Tier 1 accounts COLD with [X] open opportunities untouched by field. Immediate field investment recommended.
- **High-efficiency territory:** [Territory] — Smallest field investment, highest average FMES. Replicate program mix in other territories.

---

### SECTION 4: TOP 25 WHITESPACE PRIORITY ACCOUNTS

Accounts with highest Tier 1 ICP fit score + zero or minimal field marketing touch:

| Priority | Account Name | Industry | Employees | Tier | # Field Touches | Last Touch | Key Missing Title | AE Owner | Recommended Action |
|---|---|---|---|---|---|---|---|---|---|
| 1 | [Account] | Fintech | 800 | Tier 1 | 0 | Never | CISO | [AE Name] | Executive dinner invite + SDR sequence |
| 2 | [Account] | Healthcare | 1,200 | Tier 1 | 1 | 11 months ago | VP IT | [AE Name] | Re-engagement: regional roadshow invite |
| 3 | [Account] | Manufacturing | 2,500 | Tier 1 | 0 | Never | VP Operations | [AE Name] | Field-coordinated direct mail + LinkedIn |
[Continue for top 25]

**WHITESPACE VALUE AT STAKE:**
If these 25 accounts convert at the average rate for Tier 1 accounts after 2+ field touches ([X%] conversion, [X%] close rate), projected pipeline value = **$[X]M ARR**.

**Recommended Investment:** One targeted regional executive dinner per territory focused exclusively on these whitespace accounts would cost approximately $[X] and address [X] accounts per event. Projected pipeline at 5x PSR: $[Y].

---

### SECTION 5: HIGH-ENGAGEMENT ACCOUNTS WITH NO OPEN OPPORTUNITY — URGENT PIPELINE ACTIVATION

These accounts have FMES ≥ 60 (WARM or HOT) but have no open sales opportunity. They are your highest-probability pipeline creation targets.

| Account | FMES | # Field Touches | Most Senior Attendee | Last Touch | AE Owner | Days in Limbo |
|---|---|---|---|---|---|---|
| [Account 1] | 82 | 4 | CTO (attended 2 executive dinners) | 22 days ago | [AE] | — |
| [Account 2] | 71 | 3 | VP Infrastructure | 8 days ago | [AE] | — |
| [Account 3] | 68 | 2 | CISO | 41 days ago | [AE] | — |

**ACTIVATION PROTOCOL FOR EACH ACCOUNT:**
1. AE reviews event attendance history and any Gong/sales call notes from post-event outreach
2. Field Marketing Manager sends a personalized follow-up asset (benchmark report, ROI calculator, or executive briefing invitation) within 48 hours
3. AE makes a direct call referencing the most recent event — specific talk track generated in Section 6
4. If no response in 7 days: executive sponsor co-signature outreach (CMO or VP Field Marketing)
5. If still no response in 14 days: downgrade to COOL status and move to next-quarter roadshow sequence

**ESTIMATED UNREALIZED PIPELINE: [X accounts] × [$X avg ACV] × [X%] conversion rate = $[X]M**

---

### SECTION 6: FIELD MARKETER COVERAGE SCORE — BY FMM AND REGION

Measure each regional Field Marketing Manager's account coverage efficiency:

| FMM | Territory | Tier 1 Accounts Owned | Accounts Touched | Coverage % | HOT Accounts | Open Pipeline Touched | FMES Avg |
|---|---|---|---|---|---|---|---|
| [FMM Name] | AMER East | [X] | [X] | [X%] | [X] | [X] ($[X]M) | [X] |
| [FMM Name] | AMER West | [X] | [X] | [X%] | [X] | [X] ($[X]M) | [X] |

**PERFORMANCE SPREAD:** [FMM with highest coverage] is covering [X%] of Tier 1 accounts vs. [FMM with lowest coverage] at [X%]. This [X] percentage point gap suggests different event volume or different event formats — investigate program mix before making headcount changes.

**AE-FIELD ALIGNMENT SCORE (new metric):** For each territory, measure what % of open opportunities have had at least one field marketing touch in the past 90 days:
- AMER East: [X%] of open opps have field touch (target: ≥70%)
- AMER West: [X%]
- EMEA: [X%]
- APJ: [X%]

Any territory below 50% AE-field alignment score = immediate joint planning session required between AE manager and FMM.

---

### SECTION 7: MULTI-TOUCH PROGRESSION ANALYSIS

Track accounts that have been touched by multiple field events over 12 months and analyze their pipeline progression:

**Multi-Touch Account Conversion Funnel:**
| # Field Touches | Accounts in Cohort | % with Open Opportunity | % Closed-Won | Avg ACV (Won) | Avg Days to Close |
|---|---|---|---|---|---|
| 1 touch | [X] | [X%] | [X%] | $[X] | [X] days |
| 2 touches | [X] | [X%] | [X%] | $[X] | [X] days |
| 3 touches | [X] | [X%] | [X%] | $[X] | [X] days |
| 4+ touches | [X] | [X%] | [X%] | $[X] | [X] days |

**KEY INSIGHT TO SURFACE:** If 3-touch accounts convert at 2x+ the rate of 1-touch accounts, this is your evidence that multi-touch field programs warrant sustained investment per account (not one-and-done event attendance).

**DIMINISHING RETURNS THRESHOLD:** Identify at what touch count the incremental conversion rate improvement drops below 10 percentage points. Beyond this threshold, field investment in the same account format has low marginal value — pivot to a different program format or escalate to executive sponsor program.

---

### SECTION 8: NEXT QUARTER FIELD MARKETING INVESTMENT BRIEF

Based on FMES scoring, territory coverage gaps, and multi-touch progression data:

**RECOMMENDED PROGRAM ARCHITECTURE FOR Q-NEXT:**

Priority 1 — HOT Account Acceleration Program (Weeks 1–4):
- Format: 2 intimate executive dinners (8–10 accounts each) focused exclusively on FMES 75+ accounts with no open opportunity
- Target: [X] HOT accounts by territory
- Budget estimate: $[X]
- Projected pipeline at average 22% conversion × $[X] ACV: $[Y]

Priority 2 — WARM Account Warming Events (Weeks 3–8):
- Format: 2 regional roadshows with dedicated breakout sessions for FMES 50–74 accounts
- Target: [X] WARM accounts
- Budget estimate: $[X]
- Projected pipeline at average 12% conversion: $[Y]

Priority 3 — Whitespace Penetration Campaign (All quarter):
- Format: Targeted direct mail + co-sponsored digital event series for COLD Tier 1 accounts
- Target: [X] COLD Tier 1 accounts
- Budget estimate: $[X]
- First field event invite eligible after 1 digital engagement signal

**TERRITORY BUDGET REBALANCING:**
| Territory | Current Allocation | Recommended Q-Next | Rationale |
|---|---|---|---|
| AMER East | $[X] | $[Y] | Coverage at target — maintain |
| AMER West | $[X] | $[Y] | Under-served Tier 1 accounts — increase |
| EMEA | $[X] | $[Y] | Strong FMES avg — selective increase |
| APJ | $[X] | $[Y] | Very low coverage — invest in 1 high-quality event |

**PROJECTED Q-NEXT OUTCOMES:**
- Tier 1 coverage increase: from [X%] → [Y%]
- Average FMES improvement: from [X] → [Y]
- New opportunities projected: [X] accounts × [X%] conversion = [X] opps × $[X] ACV = **$[X]M pipeline**

OUTPUT FORMAT: Territory intelligence dashboard formatted for Salesforce dashboard import, executive brief for CMO/VP Field Marketing weekly review, and FMM account list exports for immediate action (prioritized by FMES score and territory whitespace urgency).

## Example Input/Output

**Input Example:**

Company: Meridian Secure (B2B SaaS cloud security platform)
ACV: $72K average
Tier 1 ICP: CISO/VP Security at 300–3000 employee companies in Financial Services, Healthcare, and SaaS
Total Tier 1 accounts: 380 accounts across 2 AMER territories
Period: Q3 + Q4 2025 (6 months)
Field programs: 3 executive dinners, 1 roadshow (Boston, NYC), 2 co-sponsored security summits
Total accounts touched: 112 out of 380 (29.5% coverage)
Accounts touched 3+: 31
Open pipeline accounts with field touch: 28 ($2.1M pipeline)
Zero field touch in 6 months: 268 accounts (70.5%)

**Output Example (Abbreviated):**

---
**FIELD MARKETING COVERAGE INTELLIGENCE — MERIDIAN SECURE Q3–Q4 2025**

**Universe Coverage:** 112 of 380 Tier 1 accounts touched (29.5%) — well below the 60% coverage target. **Critical gap: 268 Tier 1 accounts have had zero field marketing contact in 6 months.**

**Engagement Score Distribution:**
- 🔥 HOT (75–100): 18 accounts — 8 have no open opportunity (URGENT: $576K pipeline at risk)
- 🟡 WARM (50–74): 37 accounts — 14 have no open opportunity
- 🔵 COOL (25–49): 57 accounts
- ⬜ COLD (0–24): 268 accounts — 71% of total universe

**Territory Heatmap:**

| | AMER East | AMER West |
|---|---|---|
| Tier 1 Accounts | 190 | 190 |
| % Touched | 38% (72 accts) | 21% (40 accts) |
| HOT Accounts | 12 | 6 |
| Avg FMES | 41 | 27 |
| Open Opps with Field Touch | 18 ($1.4M) | 10 ($700K) |

**AMER WEST DIAGNOSIS:** Only 21% coverage vs. 38% in AMER East. Average FMES of 27 is 14 points lower. The 2 co-sponsored summits were AMER East heavy. Recommend 1 dedicated AMER West executive dinner targeting the top 20 COLD Tier 1 accounts in San Francisco and Seattle.

**Top 5 Whitespace Priority Accounts (AMER West):**
| Account | Industry | # Touches | Key Missing Title | Recommended Action |
|---|---|---|---|---|
| Pacific Financial Corp | Financial Services | 0 | CISO | Executive dinner invite + SDR LinkedIn sequence |
| NorthBridge Health Systems | Healthcare | 0 | VP Security | Co-sponsored healthcare security summit |
| LoopCloud Inc | SaaS | 1 (8 months ago) | VP Infrastructure | Re-engagement via direct mail + next roadshow |
| Coastal Credit Union | Financial Services | 0 | CTO | Direct mail + webinar invite to warm first |
| RapidBuild Technologies | SaaS | 0 | Head of Engineering | SDR outreach referencing industry benchmark report |

**8 HOT Accounts with No Open Opportunity — URGENT:**
Combined estimated value if converted at 35% rate: **$2.02M ARR**. AE + FMM joint outreach protocol initiated for all 8 accounts within 48 hours.

**Multi-Touch Progression:**
- 1 touch: 8% conversion to open opportunity
- 2 touches: 19% conversion (2.4x improvement)
- 3+ touches: 34% conversion (4.3x improvement vs. 1 touch)

**Recommendation:** Field marketing ROI per account increases dramatically after 3 touches. PRIORITIZE accounts at 2 touches for next-event invites — they have the highest marginal conversion rate improvement available.

---

## Success Metrics

- **Universe coverage improvement:** Tier 1 ICP account coverage increases by ≥15 percentage points within 2 quarters of running this analysis
- **FMES accuracy:** HOT accounts identified by FMES convert to open opportunity at ≥25% rate within 60 days (validated against CRM outcomes)
- **Whitespace activation:** ≥30% of top-25 whitespace priority accounts receive a field marketing touch within 90 days
- **AE-field alignment:** ≥70% of open pipeline accounts in each territory have had a field marketing touch in the prior 90 days
- **Multi-touch effect validation:** 3-touch accounts convert at ≥2.5x the rate of 1-touch accounts (validated over rolling 12 months)
- **Pipeline gap conversion:** ≥20% of HOT accounts with no open opportunity create an opportunity within 45 days of activation protocol execution

## Related Prompts

- [Field Marketing ROI Analytics & Event Pipeline Attribution](./AI-Powered-B2B-SaaS-Field-Marketing-ROI-Analytics-&-Event-Pipeline-Revenue-Attribution-Intelligence-Engine.md)
- [ABM Multi-Signal Account Engagement Score Architecture](../../05_Analytics-&-Performance/Account-Based-Marketing-Analytics/AI-Powered-B2B-Multi-Signal-Account-Engagement-Score-Architecture-&-Revenue-Activation-Intelligence-Engine.md)
- [Account-Based Field Marketing & Territory Pipeline Blitz](../../04_Demand-&-Lead-Generation-&-Growth/Field-Marketing/AI-Powered-B2B-SaaS-Account-Based-Field-Marketing-&-High-Value-Territory-Pipeline-Blitz-Intelligence-Engine.md)
- [Territory Field Marketing Program Architecture](../../04_Demand-&-Lead-Generation-&-Growth/Field-Marketing/AI-Powered-B2B-SaaS-Territory-Field-Marketing-Program-Architecture-&-Regional-Pipeline-Revenue-Intelligence-Engine.md)

## Integration Tips

- **Salesforce:** Build the FMES as a custom Account score field updated via a Salesforce Flow triggered by Campaign Member creation. Use the formula builder to weight event format (via Campaign Type field), recency (via Last Activity Date), and contact seniority (via Title/Level field on Contact). Run a territory coverage report using Account Territory field + FMES field for the executive heatmap. Create an "FMES HOT — No Opportunity" Account report view for AE daily prioritization.
- **HubSpot:** Use HubSpot's Company Score property (custom) to store FMES. Trigger score updates via Workflows: when a Contact is associated with a Marketing Event, update the parent Company Score based on event format type and contact title. Use the custom Company reports with the Score filter to create the HOT/WARM/COOL/COLD tier lists. Export as a CSV weekly for FMM territory review.
- **6sense or Demandbase:** Layer FMES on top of your AI intent score. Create a combined "Field + Intent" composite score: accounts HOT on both field engagement and intent data = highest-priority for AE outreach within 24 hours. Accounts HOT on field only = add to next event cycle. Accounts HOT on intent only = invite to next field event as first engagement.
- **Marketo:** Use Marketo's Account Scoring (Engagement Programs with scoring campaign) to build FMES. Create separate scoring campaigns for: Event Attendance (weighted by event type), Contact Seniority bonus, and Deal Stage multiplier. Export the FMES account list to Salesforce via Marketo-SFDC sync for AE visibility.
- **Google Sheets / Notion:** Use the FMES scoring formula as a manual calculation template — paste event attendee data by account, apply the formula weights, and generate the score distribution table. Update monthly. Share the whitespace priority list as a Notion database with AE and FMM owners assigned to each account.
- **Zapier / Make:** Build a "Pipeline Gap Alert" automation: when an account reaches FMES ≥ 70 AND has no open opportunity in Salesforce, create a high-priority task for the AE and send a Slack alert to the FMM with the account name, last event attended, and recommended action.

## Troubleshooting

**Problem: "We don't have contact seniority data reliably populated in our CRM — we can't apply the title weighting."**
Solution: Use a two-pass approach. First, apply base FMES using only touch count and recency (the factors you have clean data for). Then run a LinkedIn enrichment on your top 100 highest-FMES accounts to validate or correct the title data — this targeted enrichment is faster than enriching the entire universe. Alternatively, use ZoomInfo, Clearbit, or Clay.com to append seniority at the account level for the top priority segment. For accounts where you genuinely don't know who attended, default to the Director-level weight (middle assumption) rather than leaving the bonus at zero — this prevents undercounting for events where title data wasn't captured.

**Problem: "Our field team doesn't consistently log event attendance in the CRM — we can't trust the touch count data."**
Solution: Shift the data source from rep-entered CRM fields to the authoritative source: your event management platform. Export check-in data from Cvent, Splash, Bizzabo, or even Eventbrite directly, match it against CRM contacts via email address, and auto-populate the campaign association. This eliminates the rep-logging dependency. Create a post-event SOP where the FMM (not the AE) handles the CRM data entry within 48 hours of each event using the check-in export. Treat any account with unmatched email addresses from attendee lists as a data enrichment priority for the week following the event.

**Problem: "Our VP of Sales says FMES doesn't matter — they only care about accounts where reps are already active, and field events don't influence deals they're already working."**
Solution: Run the multi-touch progression analysis (Section 7) and specifically pull the "deal velocity delta" — compare average days-to-close for opportunities where a field marketing touch occurred AFTER the opportunity was created (during active sales cycle) vs. deals with no field marketing touch in that window. If field-touched deals in the Evaluation or Proposal stage close 15–25% faster, you've proven that field marketing accelerates deals the rep is already working — making it an AE productivity tool, not just a top-of-funnel program. Present this data to the VP of Sales framed as "field events are a deal velocity tool for your team" rather than "field events are a lead generation channel" — the reframe typically changes the conversation.

## Version History
- v1.0: Initial creation (auto-generated)
