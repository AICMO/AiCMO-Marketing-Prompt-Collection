# AI-Powered B2B SaaS Paid Media Performance Analytics & Cross-Channel ROAS Attribution Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** paid-media, roas-attribution, cross-channel-analytics, b2b-saas, pipeline-analytics, linkedin-ads, google-ads, cac-efficiency, revenue-attribution, demand-generation

## Overview
This prompt constructs an AI-executable paid media analytics system that measures true pipeline ROI across all paid channels — Google, LinkedIn, Meta, programmatic display, CTV, and retargeting — translating ad platform vanity metrics into CFO-defensible pipeline contribution, CAC efficiency benchmarks, and algorithmic budget reallocation recommendations that maximize pipeline per dollar spent.

## Quick Copy-Paste Version

You are a B2B SaaS paid media analyst specializing in cross-channel performance measurement and pipeline attribution. Analyze our paid media portfolio and produce a full performance report with budget optimization recommendations.

Company: [Your Company]
Product: [What you sell and the core measurable outcome it delivers, e.g., "AI-powered contract management for legal and finance teams"]
ICP: [e.g., "VP Legal, General Counsel, CFO at B2B companies with 200-2,000 employees"]
Paid channels active: [List channels: LinkedIn Ads, Google Search, Google Performance Max, Meta, programmatic display, retargeting, YouTube, CTV — include monthly spend per channel]
CRM: [e.g., HubSpot / Salesforce]
Attribution model in use: [e.g., last-touch, first-touch, W-shaped multi-touch, or "UTM-based, no formal model"]
Average deal size: [e.g., "$32,000 ACV"]
Sales cycle length: [e.g., "75 days"]
Reporting period: [e.g., Last 90 days]
Target pipeline CAC (cost per opportunity): [e.g., "$1,500-$2,200"]
Target pipeline multiple: [e.g., "5x — $5 in pipeline per $1 of paid media spend"]

Deliver:

1. CHANNEL PERFORMANCE SCORECARD — For each paid channel: spend, tracked leads, MQLs, pipeline attributed, CPL, CPO, pipeline multiple, and a Scale/Hold/Optimize/Cut recommendation
2. ATTRIBUTION ACCURACY AUDIT — Identify where your current attribution model overcredits or undercredits each channel, with specific correction methodology
3. BUDGET REALLOCATION MATRIX — Specific dollar reallocation across channels to maximize pipeline per dollar within the same total budget
4. CREATIVE & AUDIENCE PERFORMANCE BREAKDOWN — Top and bottom performing ad creative themes, audience segments, and bidding strategies by channel with specific optimization actions
5. EXECUTIVE PAID MEDIA ROI SUMMARY — CFO/CMO-ready one-page showing total paid spend, pipeline generated, blended CPO, CAC efficiency vs. benchmarks, and 90-day optimization impact projection

Use B2B SaaS pipeline metrics — pipeline multiple, CPO, and CAC payback — not consumer ROAS or CTR. Every recommendation must be directly executable by a performance marketer or AI agent without additional analysis.

## Advanced Customizable Version

ROLE: You are a senior B2B SaaS paid media analytics architect with 12+ years of experience building cross-channel measurement frameworks, multi-touch attribution models, and AI-powered budget optimization systems for B2B SaaS companies scaling from $10M to $200M ARR. You specialize in translating disconnected ad platform data — Google Ads, LinkedIn Campaign Manager, Meta Business Manager, DSP dashboards — into a unified pipeline contribution view that survives CFO scrutiny, accounts for attribution model bias, and drives capital-efficient paid media investment decisions. Your frameworks bridge platform-reported metrics (which systematically overstate performance) with CRM-verified pipeline data (which systematically understate paid media's contribution due to dark funnel influence). You present in the language of revenue, not media.

OBJECTIVE: Build a production-ready, AI-executable paid media analytics system that produces board-quality cross-channel ROI reporting, identifies attribution distortions, generates specific budget reallocation and creative optimization recommendations, and outputs a defensible paid media investment thesis — all based on the data inputs provided. Every output must be directly usable by a marketing analyst or AI agent without additional human judgment layers.

---

COMPANY CONTEXT:
- Company Name: [Company Name]
- Product Description: [One sentence: what it does, for whom, measurable outcome delivered]
- Category: [e.g., "Legal Operations Automation," "Revenue Intelligence," "Workforce Analytics"]
- Revenue Stage: [e.g., "$18M ARR growing 65% YoY" or "Series B, $8M ARR"]
- ACV / Deal Size: [e.g., "$28K-$85K ACV" or "$120K+ enterprise"]
- Primary ICP Titles: [e.g., "General Counsel, VP Legal, CFO, Chief Compliance Officer"]
- ICP Company Profile: [e.g., "B2B companies 200-2,000 employees, regulated industries (fintech, healthcare, SaaS), US/Canada"]
- Sales Cycle Length: [e.g., "60-90 days from first touch to close"]
- Sales Motion: [e.g., "Inbound-led with SDR qualification" / "AE-led mid-market" / "PLG + sales-assist"]
- CRM Platform: [e.g., HubSpot / Salesforce]
- Marketing Automation: [e.g., Marketo / HubSpot / ActiveCampaign]
- Web Analytics: [e.g., GA4 with enhanced measurement / Amplitude / Mixpanel]
- Attribution Infrastructure: [e.g., "UTM tracking in HubSpot, GA4 for web, no MTA model — last-touch only" OR "Rockerbox/Northbeam/Triple Whale for MTA, GA4 for web"]
- Company/Intent Data Tool: [e.g., 6sense, Demandbase, Clearbit, RB2B, or "none"]
- Pipeline Definition: [e.g., "SQL = AE-accepted opportunity with discovery call completed" / "MQL = score ≥85 in Marketo"]
- Target CAC by Segment: [e.g., "SMB: <$3,500 blended CAC; Mid-Market: <$8,000; Enterprise: <$22,000"]

PAID MEDIA PORTFOLIO:
[For each active paid channel, provide:]

**Channel:** [e.g., LinkedIn Ads]
- Monthly Spend: [e.g., "$28,000"]
- Campaign Types Active: [e.g., "Sponsored Content, Lead Gen Forms, Thought Leader Ads, Retargeting"]
- Primary Audience Targeting Method: [e.g., "Job title + company size + industry layering; retargeting website visitors 90-day window"]
- Primary Ad Formats: [e.g., "Single image, carousel, video (15-30s), document ads"]
- Primary CTA/Offer: [e.g., "Demo request, ROI calculator download, gated research report"]
- Bidding Strategy: [e.g., "Maximum delivery with $85 CPL target" / "Manual CPC at $14-18" / "Enhanced CPC"]
- Campaign UTM Conventions: [e.g., "utm_source=linkedin&utm_medium=paid-social&utm_campaign=[campaign-name]"]
- Landing Pages Used: [e.g., "Dedicated paid landing page + homepage for brand campaigns"]

[Repeat for each channel: Google Search, Google PMax, Meta, programmatic display, YouTube, CTV, retargeting]

PERFORMANCE DATA (REPORTING PERIOD: [e.g., Last 90 Days]):
For each channel, provide platform-reported AND CRM-verified metrics:

**[Channel Name]:**
- Platform-Reported Metrics:
  - Total spend: [$]
  - Impressions: [number]
  - Clicks: [number]
  - CTR: [%]
  - Platform-reported conversions: [number] — conversion action defined as: [e.g., "demo request form submit"]
  - Platform-reported CPA: [$]
  - Platform-reported ROAS or revenue attribution: [$, if tracked]
- CRM-Verified Metrics:
  - Leads created in CRM sourced to this channel (UTM-verified): [number]
  - MQLs attributed: [number]
  - SQLs / Opportunities attributed: [number]
  - Pipeline value attributed (opportunity value at creation): [$]
  - Closed/Won Revenue attributed: [$, or "too early — sales cycle incomplete"]
  - Assisted touchpoints in closed deals (if MTA data available): [number or "unknown"]

BASELINE METRICS:
- Total paid media budget (reporting period): [$]
- Blended paid media CPO (cost per opportunity, all channels): [$]
- Blended paid media pipeline multiple: [e.g., "3.8x"]
- Target paid media pipeline multiple: [e.g., "5x"]
- Organic/inbound CPO (for comparison): [$, or "unknown"]
- Blended company CAC (all channels, fully-loaded): [$]
- Average time from paid lead to closed deal: [days]
- Marketing-sourced pipeline as % of total pipeline: [%]
- Paid media as % of total marketing budget: [%]

ADDITIONAL CONTEXT:
- Known attribution gaps: [e.g., "LinkedIn retargeting gets no credit in last-touch because deal finally came from an organic Google search" / "display impression data not in CRM"]
- Sales team feedback on paid lead quality: [e.g., "LinkedIn leads show up to discovery well-educated; Google leads require more qualification time" / "Meta leads tend to be junior titles despite ICP targeting"]
- Any recent major changes: [e.g., "Launched LinkedIn Thought Leader Ads in Month 2; shifted Google budget from exact-match to PMax in Month 1"]
- Audience size constraints: [e.g., "LinkedIn matched audiences for our TAL are only 12,000 — too small for statistically meaningful optimization"]
- Industry/regulatory content restrictions: [e.g., "Healthcare targeting restrictions on Meta limit our ability to use clinical terminology in ad copy"]

---

DELIVERABLE 1 — CROSS-CHANNEL PERFORMANCE SCORECARD

For each paid channel, produce a structured performance table that reconciles platform-reported data with CRM-verified pipeline metrics:

**Platform vs. CRM Attribution Gap Analysis:**
For each channel, calculate:
- Platform-reported CPA vs. CRM-verified CPO: the ratio reveals attribution inflation or deflation
- Attribution inflation ratio = Platform-reported conversions / CRM-verified opportunities
  - Ratio >3x: high attribution inflation — platform is overclaiming (common in display, Meta, and Google PMax where view-through and assisted conversions are credited)
  - Ratio 1.5-3x: moderate inflation — typical for B2B paid social where last-touch CRM attribution undercredits upper-funnel channels
  - Ratio <1.5x: low inflation — channel likely well-tracked (common in branded Google Search where intent is explicit and conversion paths are short)
- Flag each channel's inflation ratio and explain the likely cause

**CRM-Verified Pipeline Metrics (Primary Performance View):**
For each channel:
| Channel | Spend | Tracked Leads | MQLs | Opps (SQLs) | Pipeline | CPL | CPO | Pipeline Multiple | vs. Target | Rec |
|---|---|---|---|---|---|---|---|---|---|---|

Recommendation tiers:
- SCALE: CPO ≤ target, pipeline multiple ≥ target, trend improving → recommend specific % spend increase
- HOLD: CPO within 20% of target, stable trend → hold budget, run creative/audience tests
- OPTIMIZE: CPO 20-50% above target but audience quality signals are strong → creative or bidding problem, not audience problem; prescribe specific 30-day fix
- CUT: CPO >2x target, declining trend, no compensating upper-funnel value → reduce budget 50%+ immediately
- KILL: CPO >3x target, declining pipeline quality, channel structurally misaligned with ICP targeting options → eliminate, reallocate budget

**Assisted/Influence Credit (if MTA data available):**
For upper-funnel channels (display, YouTube, CTV, programmatic) where last-touch attribution systematically undercredits:
- Calculate assisted touch rate: number of closed deals where this channel appeared in the journey / total closed deals in period
- Assign weighted pipeline influence credit using data-driven or position-based model
- Adjust effective CPO downward based on assisted credit to show true channel value
- Flag channels that are "death-spiral candidates" — being cut for poor last-touch CPO when they are actually driving significant early-funnel influence

---

DELIVERABLE 2 — ATTRIBUTION ACCURACY AUDIT

**The B2B Paid Media Attribution Problem:**
B2B SaaS buying cycles are 45-180 days. Last-touch attribution (the most common CRM default) systematically distorts paid media performance measurement in two directions:
1. Overcredits bottom-funnel channels (branded search, demo retargeting) that capture demand already created upstream
2. Undercredits upper-funnel channels (LinkedIn awareness, display, YouTube) that created the intent later captured by search

Build a channel-by-channel attribution bias assessment:

**For Each Channel, Assess:**

*Attribution Overcredit Indicators (channel likely getting more credit than earned):*
- High platform-reported conversion volume with low incremental pipeline lift when spend paused (holdout test signal)
- CPO dramatically lower than other channels in last-touch but channel activates primarily in retargeting audience (capturing existing interest, not creating new demand)
- Google Branded Search: if brand search volume tracks closely with LinkedIn/display spend, branded search is capturing paid social-created demand
- Google PMax: view-through conversions (impression → later conversion) inflate reported performance without CRM verification

*Attribution Undercredit Indicators (channel likely delivering more value than CRM shows):*
- Closed deals contain channel touchpoints in Salesforce/HubSpot activity history but the channel receives no pipeline credit in last-touch model
- Sales team reports prospects who "already knew us" or "saw our content everywhere" — signals upper-funnel paid media influence
- Direct traffic spikes correlating with LinkedIn campaign launches (dark social from professionals sharing ads in Slack/email)
- Low platform-reported CPA but poor CPO in CRM — channel is generating clicks that convert to leads but leads stall in pipeline (lead quality problem) OR attribution window is too short to capture longer B2B sales cycles (attribution gap problem)

**Attribution Correction Methodology:**

*Step 1 — Holdout Testing (Gold Standard):*
For channels where budget is ≥$8,000/month, design a geo-based or account-based holdout test:
- Suppress paid channel for 30 days in a randomly selected control cohort (geographic market or account segment)
- Measure incremental pipeline difference between exposed and control groups
- Calculate true incremental CPO = holdout-adjusted spend / incremental pipeline
- This is the only methodology that produces truly defensible attribution data for CFO review

*Step 2 — First-Party Signal Triangulation (Immediate, No Holdout Required):*
For each channel, gather three corroborating attribution signals:
a. Post-demo survey: "How did you first hear about us?" — compare self-reported channel distribution to CRM last-touch distribution
b. Sales call intelligence (Gong/Chorus): search for channel mentions in discovery call transcripts
c. Account overlap analysis: for ABM channels, calculate what % of converted accounts were in the targeted audience before the conversion

*Step 3 — Attribution Model Adjustment:*
Based on holdout and triangulation data, recommend which attribution model to apply per channel:
- Branded Search: last-touch is appropriate — intent is explicit
- Google Unbranded Search: first-touch or U-shaped (40/20/40) is more appropriate than last-touch — non-branded keywords create demand
- LinkedIn Awareness/Reach campaigns: time-decay with 90-day window; last-touch understates by 2-4x
- Display/Programmatic: impression influence credit required; last-touch understates by 3-6x; holdout test essential before cutting
- Retargeting: last-touch overcredits by 2-3x — retargeting captured demand created by other channels; use assisted credit model only
- YouTube/CTV: brand lift study + holdout test required; zero reliable last-touch attribution in B2B

---

DELIVERABLE 3 — BUDGET REALLOCATION MATRIX

**Reallocation Principles:**
1. Move money from channels with CPO >1.5x target (after attribution correction) to channels with CPO ≤ target with demonstrated capacity to absorb additional spend without CPO degradation
2. Do not cut upper-funnel channels (awareness, display, YouTube) purely on last-touch CPO — require holdout test data or attribution-corrected CPO before reducing
3. Maintain minimum viable budget thresholds: below ~$8K/month on LinkedIn, machine learning algorithms underoptimize; below ~$5K/month on Google Search, Smart Bidding lacks sufficient conversion data
4. Reserve 10-15% of reallocation budget for new channel tests based on ICP audience opportunity assessment

**Produce:**

*Current State Budget Allocation Table:*
| Channel | Current Monthly Spend | % of Total Budget | CRM-Verified CPO | Attribution-Corrected CPO | Pipeline Multiple | Rating |

*Recommended State Budget Allocation Table:*
| Channel | Recommended Monthly Spend | Change ($) | Change (%) | Projected CPO Impact | Projected Pipeline Lift |

*Reallocation Rationale (for each material change):*
- Why this channel is being increased: specific performance evidence
- Why this channel is being decreased: specific performance evidence and attribution-corrected rationale
- Risk flag: if a channel is being cut that has upper-funnel value not fully captured in CPO (e.g., brand awareness, competitive conquest impression share)

*30-Day Transition Plan:*
- Week 1-2: Pause/reduce underperforming campaigns within each channel (do not kill campaigns — pause and test reactivation in 60 days if budget allows)
- Week 3-4: Shift freed budget to scaling campaigns in outperforming channels; launch new audience tests with reallocated budget
- Watch metrics during transition: conversion volume drop in retargeting channels after upper-funnel reduction is expected — model the expected lag

---

DELIVERABLE 4 — CREATIVE & AUDIENCE PERFORMANCE BREAKDOWN

**Creative Performance Analysis:**
For each channel with sufficient data (≥50 leads tracked), produce:

*Ad Creative Theme Scorecard:*
Categorize all active ads into creative themes (not just individual ads):
- Problem/Pain-focused ads: lead with customer pain point
- Outcome/ROI-focused ads: lead with measurable business outcome or ROI claim
- Social proof ads: customer testimonials, case study results, customer logos
- Product demo/feature ads: show the product
- Thought leadership ads: educational content, research reports, insights
- Competitive positioning ads: explicit or implicit comparison to alternatives

For each theme, report: CPL, CPO, CTR, and quality score (lead-to-MQL conversion rate as proxy for audience quality)

*Audience Segment Performance (LinkedIn-specific):*
For LinkedIn, break down performance by:
- Job function + seniority combination (VP-level buyers vs. Director-level vs. Manager-level)
- Company size band (50-200 / 200-1,000 / 1,000-5,000 / 5,000+)
- Industry vertical (top 3 industries by CPO efficiency vs. bottom 3)
- Audience type (matched list / website retargeting / interest-based / Lookalike)
- Campaign type (Sponsored Content / Lead Gen Form / Thought Leader Ads / Message Ads)

Report which audience-creative combinations produce CPO ≤ target vs. which significantly inflate blended CPO.

*Google Search — Keyword & Intent Layer Performance:*
Categorize search keywords into intent tiers:
- Tier 1 — Branded: [Company name] keywords → highest intent, lowest CPO, but limited incremental demand creation
- Tier 2 — Category: [product category] keywords → high intent, competitive CPO, strong demand capture
- Tier 3 — Competitor: [Competitor name] + [competitor alternatives] keywords → high intent for switching buyers
- Tier 4 — Problem: [pain point] keywords → moderate intent, requires more nurturing, but reaches earlier in buying journey
- Tier 5 — Solution: [generic solution type] keywords → low intent, high volume, typically poor B2B CPO without tight landing page matching

Report CPL, CPO, and pipeline multiple by keyword tier. Recommend budget allocation shifts across tiers.

*Bidding Strategy Performance Comparison:*
If running multiple bidding strategies across campaigns:
- Manual CPC vs. Enhanced CPC vs. Target CPA vs. Max Conversions vs. Target ROAS
- Report CRM-verified CPO (not platform CPA) for each bidding strategy
- Flag where "smart" bidding strategies are optimizing for the wrong signal (e.g., optimizing for lead form submissions that include low-quality leads rather than MQLs)

*Specific Optimization Actions (30-Day Roadmap):*
For each channel, provide 3-5 specific, immediately executable optimization actions:
- Audience adjustments: which segments to exclude (e.g., company sizes that produce low MQL rates), which to expand
- Creative rotation: which ad themes to pause, which to scale, what new creative hypothesis to test
- Landing page: specific CTA or page structure change based on conversion rate data
- Bidding: specific strategy change with rationale
- Budget: specific campaign-level reallocation within the channel

---

DELIVERABLE 5 — INCREMENTALITY & SATURATION ASSESSMENT

**Diminishing Returns Detection:**
For each channel with ≥3 months of data, plot spend against pipeline to identify the saturation curve inflection point:

*Saturation Indicators:*
- CPO trending upward as spend increases without audience expansion (audience saturation)
- Frequency-capped impressions climbing above 8-10x per 30 days in LinkedIn (over-saturation of existing audience)
- Google Search impression share >80% with declining CPO improvement (keyword saturation — you're buying everything available)
- Declining CTR trend despite bid increases (creative fatigue compounding saturation)

*Channel Capacity Assessment:*
For each channel where SCALE is recommended, assess whether the channel can absorb additional spend without CPO degradation:
- LinkedIn: estimate maximum efficient spend = [ICP audience size] × [target frequency] × [average CPM] — spending beyond this inflates CPMs without new audience reach
- Google Search: impression share headroom — if at 80%+ impression share in target keyword set, incremental spend buys marginal volume at premium CPCs; expand keyword set before increasing budget
- Meta: B2B audience size constraints — calculate reachable ICP audience and model at what spend level frequency would push above efficiency threshold
- Display/Programmatic: effectively unlimited inventory; saturation is a creative problem, not an inventory problem — rotate creative every 21-30 days

---

DELIVERABLE 6 — EXECUTIVE PAID MEDIA ROI SUMMARY (CFO/CMO-READY)

Produce a one-page executive summary for board/CFO review:

**Reporting Period Summary:**
- Total paid media spend: $X
- Total CRM-verified pipeline generated: $X
- Blended pipeline multiple (pipeline/spend): Xx vs. target of Xx → [Above/Below/At target]
- Blended CPO (CRM-verified): $X vs. target of $X → [Above/Below/At target]
- Total opportunities created from paid media: X
- Paid media as % of total marketing-sourced pipeline: X%

**Attribution-Corrected View:**
- Upper-funnel channels (display, YouTube, CTV): estimated influenced pipeline not captured in last-touch: $X (methodology: holdout test / triangulation)
- Attribution-corrected total paid media pipeline influence: $X
- Attribution-corrected pipeline multiple: Xx

**Channel Ranking (by CRM-Verified CPO):**
1. [Best channel]: $X CPO — $X pipeline generated — Recommendation: SCALE
2. [Second]: $X CPO — $X pipeline generated — Recommendation: HOLD
3. [Third]: $X CPO — $X pipeline generated — Recommendation: OPTIMIZE
4. [Worst]: $X CPO — $X pipeline generated — Recommendation: CUT

**Budget Optimization Impact:**
- Proposed budget reallocation: shift $X from [underperforming channels] to [outperforming channels]
- Projected 90-day pipeline impact of reallocation: +$X pipeline (+X% increase)
- Projected CPO improvement: from $X to $X blended

**Q[Next Quarter] Paid Media Investment Recommendation:**
- Total paid media budget: $X (increase/decrease/hold vs. current)
- Top priority investments: [Channel 1, spend, rationale] / [Channel 2, spend, rationale]
- Pilot budget for new channel tests: $X for [new channel/audience hypothesis]
- Expected pipeline contribution next quarter: $X-$X range

## Example Input/Output

**Input Example:**

Company: Clauseworks — AI contract lifecycle management platform
ICP: General Counsel, VP Legal Ops, CFO at B2B SaaS and fintech companies, 200-2,000 employees
ACV: $36,000-$90,000
Sales cycle: 70 days average
Reporting period: 90 days (Q1)
Total paid media spend: $112,000

Channel breakdown:
- LinkedIn Ads: $52,000 (Sponsored Content + Lead Gen Forms + Thought Leader Ads)
- Google Search: $28,000 (branded + unbranded legal tech keywords)
- Google Performance Max: $12,000
- Meta Ads: $10,000
- Display/Retargeting: $10,000

CRM: Salesforce with Pardot; last-touch attribution only
Target CPO: $2,000-$2,800
Target pipeline multiple: 5x

**Output Example (excerpt):**

**Cross-Channel Scorecard — Q1:**

| Channel | Spend | Leads | MQLs | Opps | Pipeline | CPO | Pipeline Multiple | Rating |
|---|---|---|---|---|---|---|---|---|
| LinkedIn Ads | $52,000 | 187 | 64 | 26 | $1.04M | $2,000 | 20x | SCALE |
| Google Branded | $12,000 | 94 | 51 | 22 | $0.88M | $545 | 73x | HOLD (demand capture, not creator) |
| Google Unbranded | $16,000 | 31 | 8 | 3 | $108K | $5,333 | 6.8x | OPTIMIZE |
| Google PMax | $12,000 | 22 | 4 | 1 | $36K | $12,000 | 3x | CUT (reduce 75%) |
| Meta Ads | $10,000 | 48 | 6 | 1 | $42K | $10,000 | 4.2x | CUT (reduce 80%) |
| Display/Retargeting | $10,000 | 8 | 4 | 3 | $120K | $3,333 | 12x | HOLD (last-touch undercredits — upper-funnel value) |

**Attribution Bias Finding:**
Google Branded Search is reporting 73x pipeline multiple. This is attribution theft — not incremental demand creation. LinkedIn Thought Leader Ads and unbranded Google Search are creating the intent that branded search is capturing. Evidence: (1) branded search volume increased 31% in the 45 days following LinkedIn budget increase in Week 4, (2) 6 of 22 branded search opportunities mentioned "seeing Clauseworks content on LinkedIn" in discovery call notes (Gong query). Recommendation: credit Google Branded as "demand capture" not "demand generation" in reporting; do not increase branded search budget above efficient level to capture existing intent.

**Budget Reallocation (Same $112K Total Budget):**
- LinkedIn Ads: increase to $68,000 (+$16K) — expand Thought Leader Ads for General Counsel audience; test document ads with CLM benchmark research
- Google Branded: hold at $12,000 — already capturing near-100% of branded intent; any increase is wasted
- Google Unbranded: increase to $20,000 (+$4K) — shift from broad match to exact and phrase match for "contract lifecycle management" and "CLM software" keyword clusters; add negative list of 200+ irrelevant terms
- Google PMax: reduce to $3,000 (-$9K) — retain minimal budget for discovery but move primary budget back to standard campaigns with keyword control
- Meta Ads: reduce to $2,000 (-$8K) — retain for retargeting only; B2B CLM audience targeting constraints on Meta produce consistently poor lead quality (62% of Meta leads are non-ICP job titles per Salesforce analysis)
- Display/Retargeting: hold at $10,000 — requires holdout test before cutting; assisted pipeline influence is likely significant based on deal timeline analysis showing 71% of closed deals had display touchpoints

**Projected Impact of Reallocation:**
- Q2 projected pipeline from paid: $6.2M-$7.1M (vs. $5.5M in Q1) — +18-29% on same budget
- Projected blended CPO: $1,600-$1,950 (vs. $2,415 current) — 19-34% improvement

## Success Metrics

- Blended paid media CPO at or below target across all channels combined
- Attribution accuracy: holdout tests confirm within 25% of model-estimated incremental pipeline for top 2 channels
- Budget reallocation execution: reallocated within 14 days of report delivery
- Creative refresh cadence: underperforming ad themes paused within 7 days; replacement creative live within 21 days
- Quarter-over-quarter paid media pipeline multiple improves by ≥10% with same or lower total budget
- CFO accepts paid media pipeline contribution report as basis for budget planning (post-attribution audit)
- Saturation detected and addressed before CPO degrades >15% above target in any channel

## Related Prompts

- [Newsletter Sponsorship ROI Analytics](../Influencer-Marketing-Analytics/AI-Powered-B2B-SaaS-Newsletter-Sponsorship-ROI-Analytics-&-Creator-Partnership-Revenue-Attribution-Intelligence-Engine.md) — compare paid media CPO against newsletter CPO for portfolio-level budget decisions
- [Account-Based Advertising Dynamic Creative Personalization](../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-(PPC-&-Social)/AI-Powered-B2B-SaaS-Account-Based-Advertising-Dynamic-Creative-Personalization-&-Multi-Stakeholder-Paid-Media-Orchestration-Intelligence-Engine.md) — companion prompt for ABM-specific paid media creative execution
- [CAC Payback & Unit Economics Analytics](../CAC-Payback-&-Unit-Economics-Analytics/CAC-Payback-&-Unit-Economics-Intelligence-Engine.md) — incorporate paid media CPO into full customer acquisition cost modeling
- [Multi-Touch Attribution & Revenue Marketing](../Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md) — extend attribution model from paid media to full marketing mix

## Integration Tips

- **HubSpot:** Create custom contact properties for "Paid Channel First Touch" and "Paid Channel Last Touch" to preserve both attribution points; build HubSpot reports showing pipeline by UTM source with average deal size and close rate layered in; use HubSpot Ads integration to sync LinkedIn Lead Gen Form submissions directly into CRM with full UTM preservation
- **Salesforce:** Use Salesforce Campaign Influence with Customizable Campaign Influence to assign weighted pipeline credit to paid media campaigns based on campaign member status at each pipeline stage; build Opportunity Reports filtered by "Campaign: Source = Paid" with pipeline multiple calculated as a formula field; configure Campaign Hierarchy to roll up LinkedIn campaign spend against pipeline for single CMO dashboard view
- **Google Ads:** Enable auto-tagging and verify GA4 is importing Google Ads conversions correctly; import Salesforce opportunity data back into Google Ads as offline conversions using the Salesforce Google Ads Connector — this allows Smart Bidding to optimize for actual pipeline rather than lead form submissions; set up Google Ads conversion actions mapped to MQL creation and SQL creation as separate conversion goals with different values
- **LinkedIn Campaign Manager:** Enable LinkedIn Insight Tag with conversion tracking for all CRM form submissions; use LinkedIn's Revenue Attribution Report to see pipeline influence across Campaign Groups; configure LinkedIn matched audiences to sync from HubSpot/Salesforce lists for TAL targeting — refresh lists weekly via API for near-real-time account coverage
- **Rockerbox / Northbeam / Triple Whale:** If implementing MTA platform, map all UTM conventions to each platform's channel taxonomy before going live; export channel-level attribution data via API into your BI tool (Looker, Tableau, Metabase) to combine with CRM pipeline data in a single report; configure holdout test functionality for your top 2 paid channels in the first 60 days
- **Supermetrics / Funnel.io:** Use data aggregation tools to pull ad platform spend, impressions, and platform-reported conversions into a single BigQuery/Snowflake table; join against Salesforce/HubSpot opportunity data on UTM parameters to build a unified paid media dashboard that reconciles platform-reported vs. CRM-verified metrics automatically on daily refresh

## Troubleshooting

**Problem:** LinkedIn Lead Gen Form leads are high-volume but convert to pipeline at 40% the rate of website form submissions, inflating LinkedIn CPO.
**Solution:** This is a lead quality problem, not a LinkedIn performance problem. LinkedIn Lead Gen Forms auto-populate contact data, which lowers the friction barrier and lets lower-intent leads submit easily. Three fixes: (1) add a qualifying question to the Lead Gen Form — "What's your company's estimated number of contracts per year?" — to filter out low-volume prospects who won't reach ICP threshold; (2) create a separate Salesforce campaign for LinkedIn Lead Gen Form submissions with a distinct MQL scoring model that requires higher engagement threshold before MQL designation; (3) run a 60-day split test comparing LGF vs. click-to-landing-page campaigns with identical creative — measure CRM-verified CPO (not platform CPA) for each to determine whether the lower volume of website form conversions actually delivers better pipeline efficiency. Most B2B SaaS companies find website forms outperform LGF on CPO by 25-40% despite lower volume.

**Problem:** Google Performance Max is claiming enormous pipeline in its dashboard but CRM-verified attribution shows minimal contribution — yet Google's support team insists PMax is working.
**Solution:** PMax's attribution inflation is structural, not a bug. PMax credits view-through conversions (a user sees a PMax ad impression then converts later via any channel — organic, direct, branded search) as PMax-driven conversions. In B2B SaaS with 60-90 day sales cycles, PMax will claim credit for most pipeline by design. Fix: (1) pull all PMax UTM-tagged sessions from GA4 and map against CRM opportunities — the UTM-tagged sessions (where someone clicked a PMax ad) represent actual click-through performance, typically 5-15% of what PMax reports total; (2) run a 4-week holdout test: pause PMax completely for a randomized geographic cohort and compare lead/pipeline volume against the non-holdout cohort — if pipeline is unchanged, PMax is providing zero incremental value; (3) if you continue running PMax, exclude brand keywords from PMax via brand exclusion lists to prevent PMax from claiming credit for branded search conversions it didn't generate. For most B2B SaaS companies below $50M ARR, standard Google Search campaigns with tight keyword control and manual/tCPA bidding outperform PMax on CRM-verified CPO.

**Problem:** The CFO wants paid media to produce a 5x pipeline multiple, but the attribution model shows 3.8x — and cutting budget further would damage pipeline coverage.
**Solution:** The 5x target was likely set using a different attribution model or benchmark that doesn't match your current measurement framework. Before cutting budget, do three things: (1) run the attribution accuracy audit from Deliverable 2 — if upper-funnel channels are being undercredited, the attribution-corrected pipeline multiple may already be at or above 5x; (2) segment the pipeline multiple by channel — if LinkedIn delivers 8x and Google Unbranded delivers 6x while display and PMax deliver 2x, the portfolio average is dragged down by underperformers that can be cut; the corrective action is channel reallocation, not budget reduction; (3) frame the CFO conversation around incrementality, not multiples — the right question is "what would pipeline look like if we cut paid media budget by 30%?" not "is our pipeline multiple at target?" Present the holdout test methodology as the path to a definitive, defensible answer that both marketing and finance can agree on.

## Version History
- v1.0: Initial creation (auto-generated)
