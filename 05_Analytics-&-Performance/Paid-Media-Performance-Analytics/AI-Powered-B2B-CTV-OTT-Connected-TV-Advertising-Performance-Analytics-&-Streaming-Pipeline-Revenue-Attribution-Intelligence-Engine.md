# AI-Powered B2B CTV/OTT Connected TV Advertising Performance Analytics & Streaming Pipeline Revenue Attribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** ctv, ott, connected-tv, streaming-advertising, b2b-programmatic, account-based-advertising, brand-lift, video-completion-rate, pipeline-attribution, incrementality, the-trade-desk, roku, hulu, ip-targeting

## Overview
Conducts a full-funnel CTV/OTT advertising performance audit for B2B revenue teams — analyzing streaming ad spend across platforms (Hulu, Peacock, Roku, Amazon, Max, Paramount+, Disney+) to surface completion rate anomalies, account match rate issues, frequency waste, and pipeline attribution gaps using incrementality testing and exposed-versus-control cohort analysis as the gold standard. Use monthly or post-campaign to translate brand-lift signals into pipeline revenue proof and optimize DSP bidding for account-matched B2B audience quality.

## Quick Copy-Paste Version

You are a senior B2B programmatic advertising analyst with 10 years of experience running CTV/OTT campaigns on The Trade Desk, Amazon DSP, and DV360 for enterprise SaaS and professional services companies. Analyze the following CTV/OTT performance data and produce a complete revenue attribution intelligence report with specific optimization actions tied to pipeline outcomes.

CTV/OTT PERFORMANCE DATA (past 30 days vs. prior 30 days):
[Paste your data — include: platform/publisher (Hulu/Peacock/Roku/Amazon/Max/Paramount+/Disney+/FAST channels), DSP used, campaign name, audience targeting method (IP-based account list/intent data overlay/contextual/lookalike), spend, impressions, reach (unique households), frequency, video completion rate (VCR), 15-sec completion rate, 30-sec completion rate, skip rate if applicable, account match rate, accounts reached, exposed accounts that opened opportunities, pipeline influenced ($), cost per reached account]

BUSINESS CONTEXT:
- ICP: [e.g., VP of IT Security at financial services companies, 1,000–10,000 employees]
- Average deal size: [e.g., $185,000 ARR]
- Monthly CTV/OTT budget: [e.g., $60,000]
- DSP platform(s) in use: [e.g., The Trade Desk, Amazon DSP]
- Account list size targeted: [e.g., 3,200 target accounts from Salesforce]
- Attribution approach: [e.g., account-level exposure matching in Salesforce, lift study via Nielsen]
- Brand lift study in place: [yes/no — if yes, include: aided awareness lift, ad recall lift, consideration lift]

Produce this analysis:

1. EXECUTIVE SUMMARY (3 bullets: pipeline influenced vs. cost, reach efficiency vs. target account list, top recommendation)

2. PLATFORM SCORECARD — for each streaming platform/publisher:
   - Spend, unique household reach, account match rate, avg frequency, VCR, cost per reached account, pipeline influenced ($)
   - Green/Yellow/Red status with one-line diagnosis
   - Recommended action: Scale / Hold / Optimize / Pause

3. AUDIENCE TARGETING EFFICIENCY — compare performance by targeting method (IP-based account list vs. intent overlay vs. contextual vs. lookalike); identify which delivers highest account match rate and pipeline influence per dollar

4. FREQUENCY ANALYSIS — flag accounts overexposed (household frequency > 8/month) and underexposed accounts (< 2 impressions); recommend frequency cap adjustments per platform

5. VIDEO COMPLETION RATE BREAKDOWN — analyze VCR by creative length (15s vs. 30s vs. 60s), by platform, and by time of day; flag any creative or placement driving < 75% VCR (below B2B CTV benchmark)

6. PIPELINE ATTRIBUTION ASSESSMENT — show: accounts reached by CTV that subsequently had pipeline activity (demo requests, opportunity opens, accelerated deal velocity) within the attribution window; calculate cost per influenced account

7. QUICK WINS (3 actions this week ranked by estimated pipeline impact)

8. INCREMENTALITY TEST RECOMMENDATION — if no holdout test is running, prescribe the test design (holdout %, control group strategy, measurement window, success KPIs)

Format as a structured report ready to present to VP Demand Generation or CMO.

## Advanced Customizable Version

ROLE: You are an AI-powered CTV/OTT advertising performance intelligence engine embedded as a senior B2B programmatic strategist within a demand generation team. Your mandate is to transform disconnected streaming ad data — from The Trade Desk, Amazon DSP, DV360, or direct publisher buys — into pipeline-tied account intelligence that proves CTV's revenue contribution and compounds reach efficiency quarter over quarter.

OBJECTIVE: Produce a comprehensive CTV/OTT performance audit that diagnoses inefficiency at the platform, audience, creative, frequency, and attribution level — and outputs a prioritized action plan with projected pipeline revenue impact per recommendation, calibrated for the brand-building plus account-based demand generation role that CTV plays in B2B GTM motions.

---

INPUTS — Provide all available data:

CAMPAIGN CONFIGURATION:
- DSP(s) in use: [The Trade Desk / Amazon DSP / Google DV360 / Direct Publisher / Basis / Xandr]
- Targeting method(s): [IP-based account list / firmographic contextual / intent data overlay (Bombora/6sense/G2) / device graph lookalike / genre/content targeting]
- Account list source: [Salesforce target account list / MAP engaged accounts / ICP model / intent-qualified accounts]
- Creative lengths in rotation: [15s / 30s / 60s / 90s]
- Attribution window configured: [7-day / 14-day / 30-day post-exposure]

ACCOUNT-LEVEL DATA (current 30 days vs. prior 30 days):
- Total spend, total impressions, unique households reached, unique accounts reached
- Blended account match rate (accounts reached ÷ accounts targeted)
- Average household frequency, average frequency per reached account
- Overall VCR by creative length
- Accounts with pipeline activity during attribution window (exposed cohort)
- Control group accounts with pipeline activity (if holdout test running)
- Cost per reached account, cost per influenced account (pipeline activity)

PLATFORM-LEVEL DATA:
Format: Platform | DSP | Audience Method | Spend | Impressions | Unique Households | Account Match Rate | Avg Frequency | VCR (15s) | VCR (30s) | Accounts Reached | Pipeline Influenced ($) | Cost per Reached Account
[Paste data for each platform/publisher]

CREATIVE PERFORMANCE DATA:
- Each creative: Creative Name | Length | Platform | Impressions | VCR | Skip Rate (if applicable) | Account Reach | Frequency
- Creative age (first served date) to flag fatigue
- Any A/B or sequential creative test results

BRAND LIFT DATA (if Nielsen, iSpot, TVision, or platform-native study):
- Aided awareness lift (% point change: exposed vs. control)
- Ad recall lift
- Brand consideration lift
- Purchase intent lift (if measured)
- Sample size and statistical confidence level

DOWNSTREAM PIPELINE DATA (connect CTV exposure to revenue outcomes):
- Accounts reached by CTV that had: demo request, opportunity created, proposal stage reached, deal closed — within attribution window
- Average deal velocity comparison: CTV-exposed accounts vs. non-exposed matched accounts
- Average deal size: CTV-influenced accounts vs. non-influenced ICP accounts
- CTV's role in multi-touch attribution: first touch / mid-funnel assist / late-stage acceleration?

---

ANALYSIS FRAMEWORK — Apply all of the following:

**1. ACCOUNT REACH QUALITY ASSESSMENT**
The primary success metric for B2B CTV is account-level reach quality, not household impressions:
- Calculate: Account Match Rate = Accounts Reached ÷ Accounts Targeted × 100%
- Flag campaigns where match rate < 35% (indicates IP list quality issues, stale firmographic data, or DSP inventory limitations)
- Score each platform on: match rate, frequency distribution, ICP-tier account concentration
- Identify "ghost reach" — impressions served to households that cannot be matched to any target account (wasted CPM)
- Recommend: IP list refresh cadence, data partner upgrade (if match rate consistently < 40%), or suppression of non-ICP-match households

**2. FREQUENCY OPTIMIZATION MODEL**
B2B CTV frequency research (Nielsen/TVision benchmarks) indicates:
- Optimal B2B CTV frequency: 4–8 exposures per account per month for top-of-funnel awareness
- Diminishing returns threshold: > 10 exposures per account per month (brand safety and waste risk)
- Under-frequency floor: < 2 exposures (insufficient for recall in B2B consideration cycles)

For each platform:
- Map frequency distribution: % of reached accounts with 1–2 / 3–5 / 6–8 / 9–12 / 12+ exposures
- Flag overexposed account clusters (frequency > 10) — estimate wasted spend on excess frequency
- Flag underexposed accounts (frequency < 2) — calculate CPM efficiency of adding one more exposure
- Recommend: platform-level frequency caps, DSP-level household frequency rules, dayparting adjustments to distribute frequency over 30-day period

**3. VIDEO COMPLETION RATE DIAGNOSTIC**
VCR benchmarks for B2B CTV (non-skippable premium streaming):
- 15-second spots: ≥ 95% VCR (non-skippable; below 92% indicates delivery quality issues)
- 30-second spots: ≥ 88% VCR (premium inventory); < 80% flags non-premium or skippable placement
- 60-second spots: ≥ 75% VCR; < 68% indicates creative engagement failure for length

For each creative/platform combination:
- Diagnose VCR underperformance: skippable vs. non-skippable inventory mix, FAST channel vs. premium publisher quality, creative hook failure at 0–5 second mark
- Calculate "Effective Completion CPM": CPM ÷ VCR — a proxy for cost per message delivered
- Recommend: shift budget from low-VCR placements to premium guaranteed inventory, creative hook retest (first 5 seconds), creative length optimization (30s outperforming 60s? Cut down)

**4. PIPELINE ATTRIBUTION ARCHITECTURE**
CTV attribution for B2B requires a fundamentally different model than click-based channels:

**Exposed-vs.-Control Cohort Method (Gold Standard):**
- Divide target account list into exposed (served CTV ads) and control (holdout — matched accounts withheld from CTV targeting)
- Compare pipeline event rates: demo requests, opportunity creation, deal acceleration
- Calculate incremental lift: (Exposed conversion rate − Control conversion rate) ÷ Control conversion rate
- Attribute incremental pipeline value: (Lift % × Control group baseline pipeline) × (Exposed account count / Control account count)

**Account Progression Model (if no holdout):**
- Track accounts reached by CTV: did they progress through a funnel stage (MQL → SQL → Opportunity → Proposal) within the attribution window?
- Compare stage progression velocity: CTV-exposed accounts vs. matched non-exposed accounts from same ICP tier
- Flag accounts where CTV exposure correlated with: first website visit, first content download, or first BDR response — indicating CTV as awareness catalyst

**Time-Decay Attribution:**
- Assign CTV credit based on proximity to conversion event: 100% credit if only CTV touchpoint; 30–50% credit if CTV preceded direct response channel (paid search, SDR email) within 14 days
- Recommended multi-touch model for CTV: weighted first-touch for brand awareness stage, 20–30% assist credit for mid-funnel pipeline influence, 0% last-touch (CTV is not a conversion channel)

**5. INCREMENTALITY TEST DESIGN (if not running)**
If no holdout study is in place, prescribe the following design:
- Holdout percentage: 15–20% of target account list withheld from all CTV targeting
- Holdout construction: randomly assign accounts within each ICP tier to ensure statistical equivalence (same company size, industry, and intent score distribution)
- Measurement window: 30-day exposure period + 30-day post-exposure pipeline tracking window
- Primary success metrics: (1) pipeline creation rate: exposed vs. control, (2) deal velocity: average days from MQL to opportunity in each cohort, (3) average deal size delta
- Statistical requirements: minimum 500 accounts per cohort for 80% statistical power at 5% significance level
- Secondary metrics: brand lift (if partnering with iSpot.tv, TVision, or platform-native study)

**6. CREATIVE SEQUENCING INTELLIGENCE**
B2B CTV creative best practice is sequential storytelling across exposures:
- Exposure 1–2: Brand awareness / problem agitation (15s: "Is your [problem] costing you [outcome]?")
- Exposure 3–5: Solution introduction / differentiation (30s: product story, customer outcome)
- Exposure 6–8: Social proof / conversion trigger (30s: customer testimonial + specific result + CTA to search brand name)
- Assess: Is your current creative rotation supporting this sequence? Or serving the same spot repeatedly?
- Recommend: creative sequencing rules in DSP (e.g., The Trade Desk creative rotation logic), ensure brand CTA in exposures 5+ directs to high-intent search behavior (brand SEM campaign should be aligned and funded)

**7. CROSS-CHANNEL HALO EFFECT ANALYSIS**
CTV's most important attribution signal is often not direct pipeline creation but acceleration of other channels:
- Brand SEM lift: Did branded search volume increase in geos/segments where CTV was active? (Track in Google Search Console and Google Ads)
- Direct traffic lift: Did direct website sessions from target account IP ranges increase during and after CTV flight?
- Email open rate lift: Did outbound email open rates from BDRs targeting CTV-exposed accounts improve vs. non-exposed segments?
- Report: CTV Halo Coefficient — estimate the % lift in other channel performance attributable to CTV exposure using pre/post analysis in exposed vs. control geos or account segments

**8. COMPETITIVE CTV INTELLIGENCE**
- Monitor competitor CTV activity using iSpot.tv, AdSpy, or Vivvix (Kantar) to identify if competitors are running streaming campaigns in your target verticals
- Flag: Are competitors appearing in the same premium streaming environments (Hulu, Peacock) competing for the same audience mindshare?
- Recommend: counter-programming strategy — if competitor is heavy on one premium publisher, evaluate surround-sound strategy on adjacent publishers or outbid for key placements in their primary vertical

---

OUTPUT FORMAT:

**Section 1: CMO-Ready Executive Scorecard**
- 3 headlines: pipeline influenced vs. spend, account reach vs. target list, top recommendation
- RAG (Red/Amber/Green) status for: Account Match Rate, Frequency Efficiency, VCR Quality, Attribution Coverage, Incrementality Confidence

**Section 2: Platform-Level Action Table**
| Platform | Account Match Rate | Avg Frequency | VCR (30s) | Pipeline Influenced | CPM Efficiency | Status | Primary Action |
[Populate for each active streaming platform/publisher]

**Section 3: Top 5 Prioritized Recommendations**
For each: Problem → Root Cause → Specific Action → Estimated Account Reach Impact → Estimated Pipeline Influence Improvement → Implementation Effort (Low/Medium/High) → Owner (Programmatic / Creative / Demand Gen)

**Section 4: Creative Performance Assessment**
- VCR ranking by creative + platform combination
- Creative fatigue flags (30+ days in rotation with VCR decline)
- Specific creative brief for next rotation: length, hook, sequencing position, CTA type

**Section 5: Attribution Integrity Checklist**
- IP list freshness (last updated date vs. recommended monthly refresh)
- Holdout study status (active / not running — escalate if not running)
- Brand lift study status (active / vendor / no measurement)
- Cross-channel halo analysis status (done / in progress / not set up)

**Section 6: 30-Day Optimization Roadmap**
Week 1: [frequency cap enforcement + IP list refresh + DSP bidding adjustments]
Week 2: [creative rotation sequencing setup + VCR underperformer pauses]
Week 3: [holdout study launch or mid-flight check + halo effect data pull]
Week 4: [full performance review + brand lift readout if available + budget reallocation for next flight]

---

CONSTRAINTS:
- Never judge CTV performance by click-through rate (CTR) — CTV is a non-clickable, awareness-first channel; pipeline influence and account reach quality are the only valid primary metrics
- Never recommend pausing CTV entirely without first running a minimum 60-day incrementality test — the halo effect on other channels will not appear in direct attribution models
- When attribution data is limited, use account progression velocity (funnel stage movement) as the proxy pipeline metric rather than attributing specific revenue
- Always contextualize CTV results within the full media mix — CTV is most powerful as a demand creation layer above search, email, and direct outbound, not as a standalone conversion channel

## Example Input/Output

**Example Input — Scenario: Enterprise SaaS cybersecurity company, $65K/mo CTV spend**

Company: Veridian Security (cloud-native identity and access management platform)
ICP: CISO and VP of IT Security at financial services companies, 2,000–15,000 employees
Average deal size: $220,000 ARR | Sales cycle: 120–180 days
Monthly CTV budget: $65,000 | DSP: The Trade Desk
Account list: 2,800 target accounts (CISO-titled contacts at FS companies from Salesforce)
Platforms: Hulu ($28K), Peacock ($18K), Paramount+ ($12K), Pluto TV FAST ($7K)
Attribution: Account exposure matching in Salesforce (30-day window), no holdout study

Campaign data (30 days):
- Hulu: Spend $28K | Account match rate 58% | Avg frequency 5.2 | VCR (30s) 91% | Accounts reached: 892 | Pipeline influenced: $1.84M
- Peacock: Spend $18K | Account match rate 41% | Avg frequency 7.8 | VCR (30s) 84% | Accounts reached: 478 | Pipeline influenced: $740K
- Paramount+: Spend $12K | Account match rate 47% | Avg frequency 4.1 | VCR (30s) 87% | Accounts reached: 362 | Pipeline influenced: $510K
- Pluto TV FAST: Spend $7K | Account match rate 22% | Avg frequency 11.3 | VCR (30s) 71% | Accounts reached: 94 | Pipeline influenced: $88K

**Example Output (excerpt):**

**Executive Scorecard:**
- Pipeline influenced this period: $3.178M from $65K spend = 48.9x pipeline influence ratio (strong for upper-funnel channel; note: this is influence, not sourced — apply 20–25% attribution credit weighting in multi-touch model → $636K–$795K attributed pipeline)
- Account reach efficiency: 1,826 of 2,800 target accounts reached (65% account coverage) — strong for financial services ICP; recommend IP list refresh (last updated 47 days ago) to recapture accounts that have changed office IP ranges post-hybrid work
- Top recommendation: Immediately pause Pluto TV FAST allocation ($7K) — account match rate of 22% and frequency 11.3 indicate budget is being wasted on non-ICP households; reallocate to Peacock with stricter frequency cap of 6 and add a 30-day holdout study immediately to establish incrementality baseline

**Platform Tier Assessment:**
- Hulu → Scale. 58% match rate + 91% VCR + $2,063 cost per reached account. Increase to $34K; activate sequential creative sequencing (expose Hulu audience to problem-agitation spot first 3 exposures, product story exposures 4–6)
- Peacock → Optimize. 41% match rate is below 45% threshold; investigate IP targeting configuration in TTD — may be over-indexing on general sports content audience instead of premium news/business content inventory. Reduce frequency cap from 10 to 6; add business news contextual layer to tighten audience composition
- Paramount+: Hold. Solid performance but limited account universe in FS content (movie/drama heavy). Test adding CBS News and business content contextual targeting to improve match quality. Monitor for 30 days before scaling
- Pluto TV FAST → Pause. 22% match rate + 71% VCR below 75% threshold + frequency 11.3 = trifecta of waste signals. This is free ad-supported inventory with low content quality alignment for CISO audience — CISO personas are not the primary FAST channel consumer

**Top Priority Recommendation:**
Problem: No holdout/incrementality study — $65K/month CTV investment has no statistical proof of revenue contribution beyond correlation
Root Cause: Attribution is based entirely on post-exposure pipeline activity in exposed cohort with no control group, inflating apparent impact and making it impossible to defend budget at board level
Action: Immediately configure holdout study in The Trade Desk audience targeting: withhold 18% of target account list (504 accounts) from all CTV exposure; ensure holdout accounts are evenly distributed across FS sub-verticals (banking/insurance/asset management) and ICP tiers; run for 60 days; primary metric: opportunity creation rate in exposed vs. control cohort
Estimated Timeline: 10 days to configure + 60-day measurement window
Estimated Value of Measurement: Enables $780K+ annual budget justification or reallocation with 90% statistical confidence
Implementation Effort: Medium | Owner: Programmatic Manager (TTD configuration) + Marketing Ops (Salesforce holdout segment tagging)

## Success Metrics

A high-quality output from this prompt should produce:
- **Account match rate assessment** for every streaming platform with specific diagnosis of why match rate is above or below the 45% B2B benchmark
- **Frequency distribution map** identifying overexposed accounts (> 10/month) and the estimated budget waste attributable to excess frequency
- **VCR quality diagnosis** with root-cause explanation (skippable vs. non-skippable inventory, creative hook failure, FAST vs. premium) for any underperforming placement
- **Pipeline attribution model** that correctly frames CTV as an upper-funnel influence channel — not a conversion channel — with estimated attributed pipeline using 20–30% multi-touch weighting
- **Incrementality test design** (or mid-flight results) with statistical confidence, holdout construction logic, and specific success thresholds
- **Creative sequencing recommendation** specifying which creative runs at which frequency exposure number to maximize sequential storytelling impact
- **30-day optimization roadmap** with platform-specific DSP actions, owner assignments, and estimated account reach improvement for each action

Output should be directly pasteable into a demand gen strategy document, Notion campaign brief, or programmatic team sprint board — ready to execute without additional editing.

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Paid-Media-&-Advertising/AI-Powered-B2B-CTV-Connected-TV-OTT-Campaign-Architecture-&-Streaming-Audience-Pipeline-Revenue-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Paid-Media-Performance-Analytics/AI-Powered-B2B-Paid-Search-&-Paid-Social-Cross-Channel-Performance-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Paid-Media-Performance-Analytics/AI-Powered-B2B-Google-Ads-Performance-Analytics-&-ROAS-Optimization-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Marketing-Mix-Modeling-&-Budget-Optimization/AI-Powered-Incrementality-Testing-&-Media-Effectiveness-Intelligence-Engine.md`

## Integration Tips

**The Trade Desk:**
- Build a custom audience segment in TTD using your Salesforce account list IP data (upload via LiveRamp or IdentityLink); set account-level frequency caps at the deal/line item level (not just household) to enforce the 4–8 exposure recommendation
- Use TTD's Koa AI predictive clearing to optimize CTV bids toward supply paths with highest historical account match rates for your ICP industry codes (NAICS/SIC)
- Export TTD log-level data to Snowflake or BigQuery for account-level exposure stitching: join TTD account match table with Salesforce opportunity data by account domain to build your exposed cohort attribution model

**Salesforce / CRM:**
- Tag all target accounts in Salesforce with a custom field: `CTV_Exposure_Status` (Exposed / Holdout / Not Reached) — populated via nightly sync from TTD account match report
- Build a Salesforce report comparing pipeline velocity metrics across the three cohorts: Exposed, Holdout, Not Reached — update weekly to monitor incrementality in near-real-time
- Create a Salesforce dashboard for CTV influence tracking: accounts reached → accounts with CRM activity → accounts with open opportunities → accounts with closed deals (with 30-day rolling attribution window)

**HubSpot:**
- If using HubSpot, create a custom company property `CTV_Cohort` (Exposed/Control/Unreached) and segment your contact database to enable cohort-level reporting on email open rates, landing page visits, and form conversions — this powers the halo effect analysis for CTV's influence on outbound and inbound channels

**Google Analytics 4 / GA4:**
- Set up a GA4 audience based on company IP ranges from your target account list (using IP-to-company enrichment via Clearbit or 6sense); track website session lift from this IP-matched audience during and after CTV flights to measure direct traffic halo effect
- Use GA4's Attribution Comparison tool to compare CTV-influenced session paths (where CTV exposure preceded a GA4 session) vs. non-influenced sessions: benchmark pages per session, time on site, and conversion rate as indicators of purchase intent quality

**iSpot.tv / TVision / EDO (Brand Lift Measurement):**
- Integrate iSpot.tv for real-time CTV brand lift measurement: configure your campaign in iSpot to capture exposed vs. control brand search lift (the most reliable B2B CTV lift proxy when direct attribution is limited)
- TVision provides attention metrics (eyes-on-screen rate by creative) — use TVision data to identify which 5-second hooks are capturing attention vs. being ignored during passive viewing, and feed this back into creative iteration
- EDO's search lift data (measuring branded search volume uplift in zip codes exposed to CTV vs. control zip codes) is the fastest proxy for measuring CTV's intent-generation effect — recommended for B2B companies with measurable branded search volume (> 1,000 branded searches/month)

**Zapier / Make (Automation):**
- Trigger: Weekly account match rate report from TTD drops below 40% → Action: Slack alert to programmatic manager with platform name and current match rate, plus link to IP list last-updated date in Google Sheets
- Trigger: Holdout study 30-day milestone reached → Action: Auto-generate Google Sheets comparison report (exposed vs. control pipeline event rates) and send to CMO and demand gen lead for review

## Troubleshooting

**Problem: Account match rate is consistently below 30% across all streaming platforms — impressions are being served but reaching unmatchable households**
- *Root Cause:* B2B target account IP lists degrade at 20–30% per quarter due to office relocations, VPN usage by hybrid workers, and corporate network changes. A list last updated more than 45 days ago will have significant decay. Additionally, FAST channel (free ad-supported streaming like Pluto TV, Tubi) inventory tends to skew toward residential IP ranges rather than corporate IP clusters, driving low match rates even with fresh lists.
- *Fix:* (1) Refresh your IP list monthly — use a firmographic data provider (Bombora, 6sense, or Dun & Bradstreet) that maintains live IP-to-company mapping rather than a static export; (2) Suppress FAST channel placements from your buy and concentrate spend on premium authenticated publishers (Hulu, Peacock, Max) where household identity is stronger; (3) In TTD, layer intent data (Bombora or G2) over your IP list to add a second identity signal — accounts flagged as in-market with both IP match AND intent signal have 2–3x better downstream pipeline conversion than IP-only targeting

**Problem: CTV is showing high pipeline influence numbers but sales team is skeptical — they say they've never heard of CTV ads working for enterprise deals**
- *Root Cause:* This is an attribution communication problem, not a performance problem. CTV influence attribution (post-exposure account progression) is often conflated with direct sourcing attribution, and the correlation-vs.-causation gap is real without a holdout study. Sales teams see accounts in CRM marked "CTV influenced" when those accounts were already actively in sales cycle — they rightly question whether CTV drove anything.
- *Fix:* (1) Launch a holdout study immediately — it is the only way to establish true incrementality and silence this objection permanently; (2) While the holdout runs, reframe CTV reporting to sales: instead of "CTV influenced $X pipeline," show "deal velocity for CTV-exposed accounts was 14 days faster than matched non-exposed accounts" — velocity is a metric sales leaders intuitively trust; (3) Present branded search lift data from Google Search Console during CTV flight periods to show CTV's intent-generation signal even before pipeline impact is visible

**Problem: Video completion rate has dropped from 90% to 74% over the past 60 days without changing creative or platforms**
- *Root Cause:* This pattern almost always indicates inventory mix drift — your DSP's programmatic bidding has shifted budget from premium non-skippable inventory (where VCR is 88–95%) toward lower-cost skippable or FAST channel inventory (where VCR can be 55–75%) as premium inventory costs rise during high-demand periods (Q4, major live sports events). The DSP's optimization algorithm is buying "cheaper" impressions that are technically within your creative length specs but in lower-quality environments.
- *Fix:* (1) Pull inventory quality breakdown from your DSP — sort by domain/app and identify what percentage of impressions are now coming from non-premium or unclassified sources; (2) Add an allowlist of 15–20 premium streaming publishers (Hulu, Peacock, Paramount+, Disney+, Max, ESPN, Tubi Premium) and force all spend through this allowlist — accept the higher CPM as the cost of delivery quality; (3) Set a VCR floor of 85% as an automated optimization signal in your DSP: if a placement's rolling 7-day VCR falls below 85%, automatically suppress it and reallocate spend; (4) For creative: ensure your 30-second spot's hook (first 5 seconds) is compelling enough to survive partial attention environments — test a "pattern interrupt" opening (unexpected visual, provocative question) against your current hook to recover completion rates in mixed-quality placements

## Version History
- v1.0: Initial creation (auto-generated)
