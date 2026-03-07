# Marketing Attribution & ROI Intelligence Engine - Multi-Touch Revenue Attribution & Marketing ROI Modeling System

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** attribution, roi, revenue-intelligence, multi-touch, analytics, b2b, pipeline, reporting

## Overview
Build a complete multi-touch attribution model for your marketing program, assign fractional revenue credit to every channel and campaign, and produce an executive-ready ROI report with budget reallocation recommendations. Use this when leadership questions marketing's revenue contribution, when CRM-reported pipeline doesn't match platform numbers, or when you need to choose between competing attribution methodologies.

## Quick Copy-Paste Version

You are a senior marketing analytics strategist specializing in B2B revenue attribution. Analyze the following funnel and channel data to produce a complete multi-touch attribution model with executive-ready ROI conclusions.

**Company Context:**
- B2B SaaS | ACV: $28,000 | Sales cycle: 67 days | Close rate (SQL to Closed-Won): 22%
- Total marketing budget last quarter: $180,000
- Total Closed-Won revenue last quarter: $1,260,000 (45 deals)
- CRM: HubSpot | Primary conversion events: Demo Request → SQL → Closed-Won

**Touchpoint Data (Last Quarter, from CRM contact activity logs):**

Touchpoints recorded across all 45 closed deals (total touchpoints: 612):
- Organic Search (SEO blog + landing pages): 148 touchpoints, appeared in 38 of 45 deals
- LinkedIn Ads (Sponsored Content + Lead Gen Forms): 97 touchpoints, appeared in 29 of 45 deals
- Google Ads (Search): 84 touchpoints, appeared in 31 of 45 deals
- Email Nurture (HubSpot sequences): 112 touchpoints, appeared in 41 of 45 deals
- Direct / Dark Social (unknown source): 89 touchpoints, appeared in 35 of 45 deals
- Content Downloads (gated whitepapers, ROI calculators): 52 touchpoints, appeared in 24 of 45 deals
- Webinar / Virtual Event: 18 touchpoints, appeared in 11 of 45 deals
- Referral / Partner: 12 touchpoints, appeared in 8 of 45 deals

**Channel Spend Last Quarter:**
- LinkedIn Ads: $62,000
- Google Ads: $48,000
- Content Production (blog, whitepapers): $28,000
- Email Marketing (platform + labor): $14,000
- Webinar Hosting: $11,000
- SEO (agency + tools): $17,000
Total: $180,000

Run ALL four attribution models below and present results in a single comparison table:

1. **First-Touch:** 100% credit to the first touchpoint recorded in each deal
2. **Last-Touch:** 100% credit to the touchpoint immediately before demo request or opportunity creation
3. **Linear:** Equal credit distributed across all touchpoints in each deal
4. **W-Shaped (Position-Based):** 40% credit to first touch, 40% to lead creation touch, 20% distributed across middle touches

For each model, produce:
- Revenue attributed per channel
- ROI per channel (attributed revenue / channel spend)
- MQL and SQL contribution estimate per channel
- Recommended channel investment action (Scale / Hold / Optimize / Cut)

Then recommend which attribution model to adopt as primary and why, based on the sales cycle length and touchpoint distribution shown. Close with a 90-day budget reallocation recommendation showing exact dollar moves.

## Advanced Customizable Version

ROLE: You are a VP of Marketing Analytics with deep expertise in B2B revenue attribution, marketing mix modeling, and CFO-level ROI reporting. You use a combination of heuristic attribution models, cohort analysis, and incremental lift reasoning to give CMOs defensible, accurate numbers — not platform-inflated vanity metrics.

BUSINESS CONTEXT:
Company: [Company Name]
Business model: [B2B SaaS / B2B Services / B2C E-commerce / D2C / Marketplace]
ACV or Average Order Value: $[X]
Sales cycle length: [X days]
Close rate (SQL → Closed-Won): [X]%
Marketing-sourced pipeline target: [X]% of total pipeline
CRM platform: [HubSpot / Salesforce / Pipedrive / Other]
Attribution window: [X days before first touch to deal creation]
Total marketing budget: $[X] per [month/quarter]
Total Closed-Won revenue (period): $[X] | Total deals: [X]
Total pipeline generated (period): $[X] | Open opportunities: [X]

TOUCHPOINT DATA:
Provide either:
(A) Touchpoint-level data: For each closed deal, list every touchpoint (channel, content, date, deal ID) — ideal if exporting from HubSpot Contact Activity or Salesforce Campaign Influence
(B) Aggregate summary: Total touchpoints per channel across all closed deals, number of deals each channel appeared in, and average position (first / middle / last) per channel

[Paste touchpoint data here]

CHANNEL SPEND DATA:
For each marketing channel active during the measurement period:
Channel | Monthly/Quarterly Spend | Primary Goal | Primary Asset Type

[Paste spend data here]

DARK FUNNEL ESTIMATE:
Direct / unknown source traffic %: [X]%
Self-reported attribution data available (post-demo survey): [Yes/No]
If yes, paste self-reported first-touch distribution: [Channel: X%]
LinkedIn organic engagement estimate (impressions, not tracked): [X impressions/month]
Community / word-of-mouth referral estimate: [X deals/quarter]

ANALYSIS FRAMEWORK:

1. FOUR-MODEL ATTRIBUTION COMPARISON

Run all four models simultaneously and produce a master attribution table.

FIRST-TOUCH MODEL:
- Logic: 100% of deal revenue credited to the first recorded touchpoint for each contact/account
- Best for: Brand awareness investment decisions, top-of-funnel channel evaluation
- Limitation: Ignores all nurture, middle-funnel, and closing touches

LAST-TOUCH MODEL:
- Logic: 100% of deal revenue credited to the touchpoint immediately preceding opportunity creation or demo request
- Best for: Conversion optimization, bottom-of-funnel investment decisions
- Limitation: Inflates credit for demand capture channels (Google Search, retargeting) at the expense of demand creation channels (content, social)

LINEAR MODEL:
- Logic: Revenue divided equally across all touchpoints in the deal's history
- Best for: Long sales cycles (60+ days) with many touchpoints; rewards consistent nurture
- Limitation: Treats a 5-second ad impression identically to a 45-minute webinar

W-SHAPED (POSITION-BASED) MODEL:
- Logic: First touch = 40%, Lead creation touch = 40%, Remaining touches split the final 20%
- Best for: B2B SaaS with a clear MQL/demo-request milestone; balances awareness and conversion credit
- Limitation: 40/40/20 split is arbitrary — consider customizing based on sales cycle data

TIME-DECAY MODEL (optional, for sales cycles > 90 days):
- Logic: Touchpoints closer to deal close receive exponentially more credit (half-life: [X days])
- Formula: Credit weight = e^(-λ × days_before_close), where λ = ln(2) / half_life
- Best for: Complex enterprise sales with 3-12 month cycles

RECOMMENDED MODEL SELECTION LOGIC:
- Sales cycle < 30 days AND < 5 touchpoints per deal: Use Last-Touch
- Sales cycle 30-90 days AND 5-15 touchpoints: Use W-Shaped
- Sales cycle > 90 days AND > 15 touchpoints: Use Time-Decay or Linear
- Any cycle, if self-reported survey data is available: Weight models 50% algorithmic + 50% self-reported

2. DARK FUNNEL ADJUSTMENT

The "Direct / Unknown" bucket in B2B attribution typically contains:
- LinkedIn organic (impressions, comments, DMs not tracked by CRM)
- Dark social shares (content shared in Slack, email, WhatsApp — no referrer)
- Podcast / PR / analyst mentions
- Word-of-mouth referrals not captured in CRM

ADJUSTMENT METHODOLOGY:
Step 1: Run post-demo survey asking "How did you first hear about us?" — collect for minimum 30 respondents
Step 2: Map survey responses to channels — this gives self-reported first-touch distribution
Step 3: Apply survey distribution to reallocate the "Direct / Unknown" revenue bucket
Step 4: Recalculate all four models with adjusted dark funnel allocation
Step 5: Report both pre- and post-adjustment numbers to leadership — flag the methodology difference

If no survey data exists, apply this conservative heuristic for B2B SaaS:
- LinkedIn organic: 30% of dark funnel
- Word of mouth / referral: 25% of dark funnel
- Podcast / PR / content share: 20% of dark funnel
- Genuinely direct (typed URL): 25% of dark funnel

3. CHANNEL ROI CALCULATION

For each channel, calculate:

Attributed Revenue (per chosen model): $[X]
Channel Spend: $[X]
Gross ROI: (Attributed Revenue - Channel Spend) / Channel Spend × 100 = [X]%
Payback Period: Channel Spend / (Monthly Attributed Revenue) = [X] months

Pipeline Contribution:
- Marketing-Sourced Pipeline: Revenue of open opportunities where marketing was first touch
- Marketing-Influenced Pipeline: Revenue of open opportunities where marketing appeared anywhere in journey

B2B Benchmark Context (apply to score each channel):
- Elite channel ROI (scale aggressively): > 500% ROI
- Strong channel ROI (scale with optimization): 200–500% ROI
- Breakeven zone (optimize before scaling): 50–200% ROI
- Underperforming (diagnose or cut): < 50% ROI

4. COHORT ANALYSIS BY DEAL SIZE

Segment attribution results by deal size:
- SMB (ACV < $10K): Which channels drive small deals fastest?
- Mid-Market (ACV $10K–$100K): Which channels appear most in sweet-spot deals?
- Enterprise (ACV > $100K): Which channels appear in largest deals?

Insight goal: Identify if your highest-spend channels are optimized for your highest-value segments or if you're inadvertently generating low-ACV leads at premium CPL rates.

5. TIME-TO-REVENUE ANALYSIS

For each channel, calculate:
- Average days from first touch to demo request: [X days]
- Average days from demo request to Closed-Won: [X days]
- Total average days from first touch to revenue: [X days]
- Compare vs. company-average sales cycle: faster / slower / at parity

Insight: Channels with below-average time-to-revenue are acceleration assets. Channels with above-average time-to-revenue are awareness/nurture assets. Budget them accordingly — do not cut a slow-but-necessary awareness channel based on last-touch ROI alone.

6. INCREMENTALITY SANITY CHECK

For your top 3 channels by attributed revenue, apply the incrementality question:
"If we spent $0 on [Channel] for 90 days, what would actually happen to revenue?"

Framework:
- HIGH incrementality (cut = real revenue loss): Channels where your ICP can only discover you this way, or where competitors would capture that demand instead
- MEDIUM incrementality (cut = partial revenue loss): Channels that accelerate deals but do not create them
- LOW incrementality (cut = minimal revenue loss): Channels capturing demand already created by other channels

Flag any channel where Last-Touch attribution is significantly higher than W-Shaped or Linear — this is the primary signal of a low-incrementality "credit-claiming" channel (typically: branded search, retargeting).

7. EXECUTIVE ROI REPORT FORMAT

Produce a board-ready summary with these sections:

HEADLINE METRICS:
- Total marketing investment: $[X]
- Total Closed-Won revenue in period: $[X]
- Marketing-sourced revenue (primary attribution model): $[X] ([X]% of total)
- Marketing-influenced revenue: $[X] ([X]% of total)
- Blended marketing ROI: [X]x return on every $1 invested
- Cost per Closed Deal: $[X]
- Marketing pipeline coverage ratio: $[X] pipeline / $[X] quota = [X]x

CHANNEL SCORECARD TABLE:
Channel | Spend | Attributed Revenue (W-Shaped) | ROI | Deals Influenced | Avg Deal ACV | Time to Revenue | Action

NARRATIVE INSIGHTS (3-5 bullet points):
- "Our #1 ROI channel is [X], returning $[X] for every $1 invested — we are leaving an estimated $[X] in pipeline uncaptured by not scaling this channel."
- "Last-touch attribution was overcrediting [Channel] by [X]x vs. W-Shaped — after correcting for attribution inflation, its ROI drops to [X]%."
- "Dark funnel accounts for [X]% of our deals. After self-reported survey adjustment, LinkedIn Organic is our #1 awareness driver despite generating $0 in last-touch revenue."

8. 90-DAY BUDGET REALLOCATION PLAN

Based on channel ROI and incrementality analysis:

SCALE (increase budget):
- Channel: [X] | Current spend: $[X]/mo | Recommended: $[X]/mo | Rationale: [ROI + incrementality logic]

HOLD (maintain budget, optimize):
- Channel: [X] | Current spend: $[X]/mo | Recommended: $[X]/mo | Optimize: [specific action]

REALLOCATE (shift budget to higher-ROI channel):
- From: [Channel A] $[X] | To: [Channel B] $[X] | Net budget neutral | Expected outcome: [metric]

CUT (eliminate or pause):
- Channel: [X] | Current spend: $[X]/mo | Recommended: $0 | Rationale: Low incrementality confirmed by [evidence]

TEST BUDGET (10% of total budget reserved for new channels):
- Hypothesis: [What you're testing and why] | Success metric: [X] | Measurement period: [X days]

OUTPUT CONSTRAINTS:
- All revenue numbers must distinguish between "attributed" (model output) and "verified" (CRM Closed-Won)
- Flag any channel where platform-reported attribution exceeds CRM-verified contribution by > 2x — this is attribution window inflation
- Do not recommend cutting a channel based solely on last-touch attribution without running the incrementality sanity check first
- Every budget recommendation must cite specific evidence from the attribution analysis

## Example Input/Output

**Input Example:**

Company: Veritas Workflows — compliance automation SaaS for financial services
ACV: $42,000 | Sales cycle: 74 days | Close rate: 19% | Budget: $210,000/quarter
Closed-Won: $1,890,000 (45 deals) | CRM: Salesforce

Touchpoints across 45 deals (total: 738 touchpoints):
- Organic Search: 181 TPs, in 41/45 deals
- Google Ads (Search): 94 TPs, in 33/45 deals
- LinkedIn Ads: 112 TPs, in 28/45 deals
- LinkedIn Organic (exec posts): 67 TPs, in 22/45 deals (tracked via UTM on bio links)
- Email Nurture: 143 TPs, in 43/45 deals
- Webinar (monthly compliance briefings): 41 TPs, in 19/45 deals
- Direct / Unknown: 100 TPs, in 38/45 deals

Channel spend: Google Ads $58K | LinkedIn Ads $72K | Content/SEO $31K | Email $16K | Webinars $18K | Events $15K

**Output Example:**

**Attribution Comparison Table:**

| Channel | First-Touch Rev | Last-Touch Rev | Linear Rev | W-Shaped Rev | Spend | W-Shaped ROI |
|---|---|---|---|---|---|---|
| Organic Search | $756,000 | $283,500 | $461,434 | $582,750 | $31,000 | 1,780% |
| Google Ads | $283,500 | $661,500 | $241,327 | $302,400 | $58,000 | 421% |
| LinkedIn Ads | $189,000 | $189,000 | $287,247 | $264,600 | $72,000 | 267% |
| LinkedIn Organic | $0 | $0 | $171,886 | $94,500 | $0 | ∞ |
| Email Nurture | $0 | $378,000 | $366,819 | $283,500 | $16,000 | 1,672% |
| Webinars | $189,000 | $94,500 | $105,230 | $198,450 | $18,000 | 1,003% |
| Direct/Unknown | $472,500 | $283,500 | $256,057 | $163,800 | $0 | — |

**Recommended Model: W-Shaped**
Rationale: 74-day sales cycle with a clearly defined demo-request milestone (MQL → SQL handoff) makes the W-Shaped model structurally appropriate. First touch and lead creation are the two highest-leverage moments in this funnel; distributing 40% credit to each captures that reality better than Linear (which undersells the importance of first touch) or Last-Touch (which overcredits Google Search by 2.3x).

**Key Insights:**

1. **Email is massively undervalued by last-touch.** Last-touch attributes $378K to email (it's a common closing channel in a 74-day cycle). W-Shaped drops that to $283K — still the #3 channel. But the real insight: email's ROI is 1,672% because spend is only $16K. This is your highest-leverage channel per dollar invested.

2. **Google Ads attribution inflation alert.** Last-touch gives Google Ads $661K (35% of all revenue). W-Shaped drops it to $302K (16%). Google Search is a demand capture channel for Veritas — it's capturing leads already warmed by Organic Search and LinkedIn. Incrementality score: MEDIUM. Do not scale Google Ads before scaling Organic Search and LinkedIn first.

3. **LinkedIn Organic is your dark funnel anchor.** 22 of 45 closed deals had a tracked LinkedIn Organic touchpoint — and this undercounts actual influence since most LinkedIn impressions are untracked. After dark funnel adjustment (reallocating 30% of the Direct/Unknown bucket), LinkedIn Organic estimated attributed revenue rises to ~$220K with $0 spend. This is your highest-ROI asset. Invest in executive LinkedIn content immediately.

4. **Webinar ROI is 1,003%.** 19 of 45 deals attended at least one webinar. At $18K/quarter cost, this is dramatically underinvested. Each webinar attendee who converts represents $42K ACV — at a CPL of approximately $947/attendee-who-closed.

**90-Day Budget Reallocation:**

| Action | Channel | Current | Recommended | Change |
|---|---|---|---|---|
| Scale | Content/SEO | $31K/qtr | $52K/qtr | +$21K |
| Scale | Webinars | $18K/qtr | $34K/qtr | +$16K |
| Scale | Email (automation + sequences) | $16K/qtr | $22K/qtr | +$6K |
| Hold + Optimize | LinkedIn Ads | $72K/qtr | $65K/qtr | -$7K |
| Reduce | Google Ads | $58K/qtr | $43K/qtr | -$15K |
| New Test | LinkedIn Organic (content program) | $0 | $15K/qtr | +$15K |
| Cut | Events (low attribution data) | $15K/qtr | $0 | -$15K |
| **Net** | | **$210K** | **$231K** | **+$21K for 10% test budget** |

**Projected Impact (90 days):**
- Organic search pipeline: +$340K (increased content production)
- Webinar-sourced deals: +6 deals/quarter at $42K ACV = +$252K pipeline
- Google Ads savings reallocated to higher-ROI channels: net pipeline positive within 60 days

## Success Metrics
- Attribution model agreed upon by marketing, sales, and finance within one review cycle
- Platform-reported revenue vs. CRM-verified revenue variance < 2x per channel
- Marketing-sourced pipeline coverage ratio ≥ 3x monthly quota
- Executive report reviewed and accepted by CFO/CEO without re-work requests
- Budget reallocation implemented within 30 days of analysis completion
- Quarterly attribution re-run scheduled and automated via Looker Studio or BI tool

## Related Prompts
- [Paid Media Cross-Channel Performance Intelligence Engine](./Paid-Media-Cross-Channel-Performance-Intelligence-Engine.md) - Optimize channel-level performance once attribution confirms budget priorities
- [SEO Organic Performance Analytics Engine](./SEO-Organic-Performance-Analytics-Engine.md) - Deep-dive organic channel analysis to validate attribution-driven investment in SEO
- [Marketing ROI Reporting Automation](../../01_CMO-&-Leadership/Reporting-&-ROI/Marketing-ROI-Reporting-Automation.md) - Automate ongoing ROI reporting once attribution methodology is established
- [CMO Board Presentation Builder](../../01_CMO-&-Leadership/Reporting-&-ROI/CMO-Board-Presentation-Builder.md) - Convert attribution insights into board-level narrative and slides

## Integration Tips
- **Salesforce:** Use the Campaign Influence object with Salesforce's native multi-touch attribution. Go to Setup > Campaign Influence > enable "Auto-Association." Export via Reports > Campaign Reports > Campaign Influence with Primary Campaign Source. For custom W-Shaped logic, use the Customizable Campaign Influence model (requires Salesforce Enterprise+).
- **HubSpot:** Navigate to Reports > Attribution > Revenue Attribution. HubSpot natively supports First-Touch, Last-Touch, Linear, U-Shaped (= W-Shaped without deal close touch), W-Shaped, and Full-Path models. Export the attribution breakdown as CSV and paste directly into the Advanced Version. Note: HubSpot attribution only tracks known contacts — anonymous website visits are not included.
- **Google Looker Studio:** Connect HubSpot or Salesforce via native connectors. Build a blended attribution dashboard with model toggle (use a Looker Studio parameter to switch between models in a single view). Share with CFO and sales leadership for live review during QBRs.
- **Google Sheets:** Use SUMIF formulas to calculate W-Shaped attribution manually from a touchpoint export. Template: Column A = Deal ID, Column B = Channel, Column C = Position (First/Middle/Last), Column D = Deal ACV. Then apply position-based weighting with IF statements.
- **Segment / Rudderstack (CDP):** Route all website events through a CDP to unify anonymous pre-session behavior with known contact records. This dramatically reduces the "Direct/Unknown" bucket — typically from 30-40% down to 10-15% of touchpoints — by resolving identity across devices and sessions before first form fill.
- **Zapier / Make:** Automate a monthly data pull from your CRM's attribution report into Google Sheets. Trigger an AI analysis run on the 1st of each month to produce a standing attribution report without manual data assembly. Send output summary via Slack to the marketing leadership channel.
- **Self-Reported Attribution (Typeform/HubSpot Forms):** Add a "How did you first hear about us?" field to every demo request form. Route responses to a custom CRM property. After 60+ responses, query: `SELECT self_reported_channel, COUNT(*) FROM demo_requests GROUP BY 1` — this becomes your dark funnel decoder ring and should be weighted into the attribution model each quarter.

## Troubleshooting

**Problem: Platform-reported ROAS is 5x higher than CRM-verified attributed revenue per channel.**
Solution: This is attribution window inflation — the most common B2B attribution problem. Platforms default to claiming credit with generous windows (Google: 30-day click + 30-day view; Meta: 7-day click + 1-day view). Fix by: (1) Standardizing all platforms to a 7-day click, 0-day view window. (2) Using CRM Closed-Won revenue as your ground truth, not platform-reported conversions. (3) Running this attribution analysis from your CRM's activity log, not from platform dashboards. The discrepancy between platform numbers and CRM numbers is a known and expected gap — always present CRM-verified numbers to leadership and note that platform numbers overcount due to multi-platform overlap.

**Problem: My Salesforce or HubSpot attribution shows most deals as "Direct" or "Unknown Source" — attribution data is sparse.**
Solution: This means your CRM was not capturing touchpoints before opportunity creation. Fix going forward: (1) Install UTM tracking on all paid and email links using a consistent UTM taxonomy (utm_source, utm_medium, utm_campaign). (2) Enable HubSpot's "Original Source" and "Latest Source" properties on all contact records. (3) In Salesforce, turn on Campaign Influence auto-association for all active campaigns. (4) For historical analysis: use your ad platform dashboards to reconstruct first-touch distribution — cross-reference demo request dates with campaign impression/click dates to estimate channel contribution for dark-funnel-heavy periods.

**Problem: Sales leadership disputes marketing attribution, claiming deals were "sales-sourced" that marketing claims as "marketing-sourced."**
Solution: This is a definitional dispute, not a data dispute. Solve it by establishing shared definitions before running attribution: (1) "Marketing-sourced" = first touchpoint in the deal was a marketing-owned channel (ads, content, email, SEO). (2) "Sales-sourced" = first touchpoint was SDR outreach, networking, or direct executive relationship. (3) "Marketing-influenced" = marketing appeared anywhere in the deal journey regardless of source. Present all three metrics in the executive report — total marketing-influenced pipeline is always the most politically defensible number because it does not require winning the "who sourced it" debate.

## Version History
- v1.0: Initial creation (auto-generated)
