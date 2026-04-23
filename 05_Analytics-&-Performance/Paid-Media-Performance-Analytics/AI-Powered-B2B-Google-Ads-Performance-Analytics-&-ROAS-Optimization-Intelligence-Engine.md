# AI-Powered B2B Google Ads Performance Analytics & ROAS Optimization Intelligence Engine

**Difficulty:** Advanced | **Time:** 20 min | **Tags:** google-ads, paid-search, performance-max, analytics, roas, cpl, pipeline-attribution, smart-bidding, b2b

## Overview
Conducts a deep-dive audit of Google Ads performance for B2B marketers — analyzing Search, Performance Max, Display, and YouTube campaigns together to surface CPL root causes, Smart Bidding failures, impression share opportunities, and budget waste with pipeline revenue as the single source of truth. Use it weekly or after any significant performance shift to diagnose problems and produce a prioritized action plan tied to revenue outcomes.

## Quick Copy-Paste Version

You are a senior B2B Google Ads performance analyst with 15 years of experience managing $10M+ annual Google Ads budgets for SaaS and professional services companies. Analyze the following Google Ads account data and produce a complete performance intelligence report focused on pipeline and revenue outcomes.

GOOGLE ADS PERFORMANCE DATA (past 30 days vs. prior 30 days):
[Paste your data here — include: campaign name, campaign type (Search/PMax/Display/YouTube), spend, impressions, clicks, CTR, avg CPC, quality score (where available), conversions, CPL, MQLs, MQL rate, pipeline sourced, CPO (cost per opportunity)]

BUSINESS CONTEXT:
- ICP: [e.g., VP of Engineering at B2B SaaS companies, 100–1,000 employees]
- Average deal size: [e.g., $52,000 ARR]
- Monthly Google Ads budget: [e.g., $55,000]
- Primary conversion action: [e.g., demo request]
- Top 5 target keywords: [e.g., "api monitoring software", "observability platform"]
- Current landing page: [e.g., /demo or /solutions/engineering]

Produce this analysis:

1. EXECUTIVE SUMMARY (3 bullets: what improved, what degraded, what needs immediate action)

2. CAMPAIGN SCORECARD — for each active campaign:
   - Spend, CPL, pipeline ROAS, MQL rate vs. prior period
   - Green/Yellow/Red status with one-line diagnosis
   - Recommended action: Scale / Hold / Pause / Fix

3. SMART BIDDING HEALTH CHECK — are your automated bid strategies performing? Flag any campaigns where CPL is > 30% above target or where conversion volume dropped > 20% (Smart Bidding data starvation risk)

4. QUALITY SCORE IMPACT ANALYSIS — identify any ad groups with QS < 6, estimate CPL penalty vs. QS 8+, and provide specific fix for each

5. IMPRESSION SHARE OPPORTUNITY — which campaigns are losing IS to budget vs. rank? Calculate the revenue opportunity of recovering lost impressions

6. SEARCH TERM AUDIT — flag high-spend terms with zero pipeline attribution, identify negative keyword gaps, surface new intent clusters worth targeting

7. QUICK WINS (3 actions this week, ranked by pipeline revenue impact)

8. 30-DAY TEST ROADMAP — 2 specific experiments to run with hypothesis, success metric, and evaluation date

Format output as a structured report ready to present to VP Marketing or CMO.

## Advanced Customizable Version

ROLE: You are an AI-powered Google Ads performance intelligence engine embedded as a senior B2B paid search strategist within a revenue marketing team. Your mandate is to convert Google Ads account data into precise, pipeline-tied recommendations — eliminating waste, recovering lost revenue opportunities, and compounding ROAS improvement quarter over quarter.

OBJECTIVE: Produce a comprehensive Google Ads performance audit that diagnoses inefficiency at the campaign, ad group, keyword, and creative level — and outputs a prioritized action plan with projected pipeline impact for each recommendation.

---

INPUTS — Provide all available data:

ACCOUNT-LEVEL DATA (current period vs. comparison period):
- Total spend, impressions, clicks, CTR, avg CPC, conversions, CPL
- Impression share (lost to budget vs. lost to rank) by campaign
- Conversion rate by device (desktop/mobile/tablet)
- Top vs. Other impression share percentages

CAMPAIGN-LEVEL DATA:
Format: Campaign Name | Type | Bid Strategy | Target CPA or ROAS | Spend | Impressions | Clicks | CTR | CPC | Conversions | CPL | MQLs | MQL Rate | Pipeline $ | CPO | ROAS
[Paste data for each campaign]

AD GROUP / KEYWORD DATA:
- Quality Score distribution (count of keywords by QS score 1–10)
- Top 10 keywords by spend with QS, CTR, CVC, conversion rate
- Bottom 10 keywords by Quality Score
- Search term report: top 20 search terms by spend including pipeline attribution

LANDING PAGE PERFORMANCE:
- Conversion rate by landing page URL
- Bounce rate and time on page by campaign (if available from Google Analytics / GA4)

SMART BIDDING STATUS:
- Bid strategy type per campaign (Target CPA, Target ROAS, Maximize Conversions, etc.)
- Conversion volume per campaign (last 30 days)
- Any "Limited" or "Learning" status campaigns

BUSINESS PARAMETERS:
- Target CPL by buyer segment: [e.g., Enterprise: $400, Mid-Market: $200, SMB: $80]
- Target pipeline ROAS: [e.g., minimum 5:1]
- Monthly budget by campaign type: [data]
- ICP definition with firmographic + technographic criteria: [data]
- Current funnel conversion rates: [lead-to-MQL %, MQL-to-opp %, opp-to-close %]
- Offline conversion import: [Yes/No — are closed deals imported back into Google Ads?]

---

ANALYSIS FRAMEWORK — Execute in this exact sequence:

STEP 1 — PIPELINE ROAS AUDIT BY CAMPAIGN TYPE
For each campaign type (Search, Performance Max, Display, YouTube):
- Calculate pipeline ROAS = pipeline sourced / spend
- Calculate effective CPO = spend / opportunities created
- Rank all campaigns by pipeline ROAS descending
- Apply the TIER classification:
  - TIER 1 (Scale): pipeline ROAS ≥ target × 1.25 AND conversion volume ≥ 30/month
  - TIER 2 (Optimize): pipeline ROAS between 0.8× and 1.25× target
  - TIER 3 (Fix or Pause): pipeline ROAS < 0.8× target OR CPL > 150% of target

STEP 2 — SMART BIDDING HEALTH DIAGNOSIS
Apply the Smart Bidding Reliability Test:
- Conversion Volume Threshold: flag any campaign with < 30 conversions/month as "data-starved" — Smart Bidding cannot optimize reliably; recommend switching to Maximize Clicks or manual CPC with bid modifiers
- Bid Strategy Alignment Test: is the bid strategy aligned to the right conversion action? (e.g., if demo requests are the primary goal but the campaign is optimizing for "page views," flag as "misaligned conversion goal")
- Learning Period Detection: flag campaigns in "Learning" status — identify trigger (budget change, bid strategy change, new ad) and estimate days to exit learning
- Offline Conversion Import Audit: if closed deals are not being imported back to Google Ads via GCLID, Smart Bidding is flying blind on revenue. Flag as Critical if absent — estimate CPL improvement from implementing offline conversion import at 15–30%

STEP 3 — QUALITY SCORE IMPACT QUANTIFICATION
Using the QS Financial Impact Model:
- Baseline: QS 7 = no CPC penalty/bonus
- QS 1–3 = CPC penalty 25–50% above auction price (calculate exact $ waste)
- QS 4–6 = CPC penalty 10–25% (calculate)
- QS 8–10 = CPC discount 5–30% (calculate savings opportunity)

For each ad group with QS ≤ 6:
- Identify the weak component (Expected CTR / Ad Relevance / Landing Page Experience)
- Estimate monthly CPL penalty in dollars
- Provide specific fix: headline rewrite, ad group restructure, or landing page change
- Project CPL improvement after fix (assume QS improvement from 5→7 = 18% CPC reduction)

STEP 4 — IMPRESSION SHARE & LOST REVENUE ANALYSIS
For each campaign:
- Calculate Search Impression Share Lost to Budget:
  - If IS Lost to Budget > 15%: the campaign is revenue-constrained by budget, not performance
  - Calculate: (IS Lost to Budget) × (estimated impressions if fully funded) × (historical CTR) × (conversion rate) × (average pipeline value per lead)
  - This is "Revenue Left on Table" — present as a dollar figure to justify budget increase
- Calculate Search Impression Share Lost to Rank:
  - If IS Lost to Rank > 20%: bid levels or Quality Score is suppressing reach
  - Diagnose: is it a QS problem (Step 3) or a competitive bid problem (analyze top-of-page bid estimates)?

STEP 5 — SEARCH TERM INTELLIGENCE AUDIT
Analyze the search term report with the Revenue Signal Framework:
- CAPTURE terms: high commercial intent + pipeline attribution → bid up, protect with exact match
- EXPLORE terms: high clicks, no conversions yet, moderate intent → test with Target CPA, add to observation list
- WASTE terms: spend > $100 with zero conversions → immediate negative keyword candidates
- THREAT terms: competitor brand terms appearing in your campaigns → evaluate cost vs. pipeline before protecting

Identify minimum 5 new negative keywords to add and 3 new keyword clusters to test.

STEP 6 — PERFORMANCE MAX AUDIT (if applicable)
For PMax campaigns, apply the PMax Transparency Protocol:
- Asset Group Performance: identify which asset groups are "Low" performing — rewrite headlines/descriptions using the ICP's Job-to-be-Done language
- Search Theme Alignment: verify search themes match your ICP's actual buying intent queries
- Audience Signal Effectiveness: confirm customer match list or in-market segments are applied — estimate 15–25% CPL improvement vs. no audience signals
- Brand vs. Non-Brand Traffic Split: if PMax is cannibalizing branded search traffic (verify via brand campaign IS), apply brand exclusions immediately
- Search Impression Share from PMax: estimate whether PMax is competing with your own Search campaigns for the same queries

STEP 7 — BUDGET EFFICIENCY & REALLOCATION MODEL
Build a data-driven reallocation recommendation:
- Identify campaigns past the diminishing returns frontier (CPL rising each week as spend increases)
- Identify campaigns with headroom to scale (high pipeline ROAS + IS lost to budget)
- Produce a reallocation table: From Campaign | To Campaign | Amount | Expected CPL Change | Expected Pipeline Delta | Confidence Level

---

OUTPUT FORMAT:

## EXECUTIVE PERFORMANCE DASHBOARD
[3-bullet summary: overall pipeline ROAS vs. target, biggest efficiency problem, biggest scale opportunity]

## CAMPAIGN TIER CLASSIFICATION
[Table: Campaign | Type | Spend | CPL | Pipeline ROAS | Tier | Priority Action]

## SMART BIDDING HEALTH REPORT
[Table: Campaign | Bid Strategy | Monthly Conversions | Status | Issue | Fix]

## QUALITY SCORE FINANCIAL IMPACT
[Table: Ad Group | QS | Weak Component | Monthly CPL Penalty ($) | Fix Required | Projected CPL Improvement]

## REVENUE LEFT ON TABLE — IMPRESSION SHARE ANALYSIS
[Table: Campaign | IS Lost to Budget | IS Lost to Rank | Monthly Revenue Opportunity ($) | Recommended Action]

## SEARCH TERM INTELLIGENCE REPORT
[Capture terms to protect | Explore terms to test | Waste terms to negative | Threat terms to evaluate]
[5 new negatives to add | 3 new keyword clusters to test with estimated volume and intent]

## PERFORMANCE MAX AUDIT
[Asset Group scores | Brand cannibalization risk | Audience signal gaps | Recommended fixes]

## BUDGET REALLOCATION RECOMMENDATION
[Table: From | To | Amount | Expected Pipeline Delta | Confidence]

## 30-DAY ACTION PLAN
[Priority Rank | Action | Campaign/Ad Group | Expected Impact | Owner | Deadline]

## TEST ROADMAP
[Test 1: Hypothesis | Campaign | Variable | Success Metric | Evaluation Date]
[Test 2: Hypothesis | Campaign | Variable | Success Metric | Evaluation Date]

---

CONSTRAINTS:
- Every recommendation must be tied to pipeline or CPL impact — no recommendations based solely on CTR or impression volume
- Always distinguish between "CPL improved but MQL quality degraded" — surface MQL rate changes alongside CPL changes
- Never recommend pausing a campaign without specifying where the budget moves and what pipeline impact to expect
- Confidence-weight all pipeline projections: High (based on > 60 conversions of historical data), Medium (30–60 conversions), Low (< 30 conversions)
- Treat Performance Max and Search as separate accountability centers — never blend their performance data in ROAS calculations
- Flag any data gaps that limit diagnostic accuracy (e.g., no offline conversion import, GA4 not connected, CRM pipeline data unavailable)

## Example Input/Output

**Input Example:**

Company: Vantage Ops (B2B SaaS, cloud cost optimization for DevOps teams)
ICP: Engineering Managers and VP Engineering at tech companies, 200–2,000 employees
Deal size: $41,000 ARR | Sales cycle: 55 days | Monthly Google Ads budget: $62,000

Campaign data (30 days vs. prior 30):

| Campaign | Type | Spend | CPL | Pipeline $ | Pipeline ROAS | Prior ROAS |
|----------|------|-------|-----|------------|---------------|------------|
| Brand | Search | $3,200 | $48 | $210,000 | 65.6x | 71.2x |
| Non-Brand Core | Search | $27,000 | $318 | $168,000 | 6.2x | 7.8x |
| Competitor | Search | $8,500 | $612 | $38,000 | 4.5x | 5.1x |
| PMax - All Products | PMax | $18,000 | $284 | $62,000 | 3.4x | 4.1x |
| Display Retargeting | Display | $5,300 | $891 | $14,000 | 2.6x | 3.2x |

Smart Bidding status: Non-Brand Core (Target CPA $300, 49 conversions/month — OK). PMax (Target ROAS 500%, 41 conversions/month — Learning). Competitor (Maximize Conversions, 14 conversions/month — data-starved).

Quality Score distribution: 3 ad groups at QS 4, 8 ad groups at QS 6–7, 12 ad groups at QS 8–10.

Impression Share: Non-Brand Core — 58% IS (14% lost to budget, 28% lost to rank). PMax — IS not available.

Top waste terms identified: "aws cost savings blog" ($340 spend, 0 conversions), "cloud bill calculator free" ($280 spend, 0 conversions), "azure pricing comparison" ($190 spend, 0 conversions).

---

**Output Example (abbreviated):**

**EXECUTIVE PERFORMANCE DASHBOARD**
Total pipeline ROAS is 4.1x against a 5.0x target — a 18% decline driven by three compounding problems: PMax is cannibalizing branded queries while delivering 3.4x ROAS (vs. Brand campaign's 65x), the Competitor campaign is data-starved with only 14 conversions preventing Smart Bidding from optimizing, and three ad groups with QS 4 are inflating Non-Brand Core CPL by an estimated $47/lead. The Non-Brand Core "rank loss" IS problem (28% lost to rank) points to a Quality Score drag, not a bid problem — fixing QS should recover IS without increasing spend.

**CAMPAIGN TIER CLASSIFICATION**

| Campaign | Type | Spend | CPL | Pipeline ROAS | Tier | Priority Action |
|----------|------|-------|-----|--------------|------|-----------------|
| Brand | Search | $3.2K | $48 | 65.6x | TIER 1 | Scale — increase budget 30%, recover IS lost to budget (est. $85K additional pipeline) |
| Non-Brand Core | Search | $27K | $318 | 6.2x | TIER 2 | Fix QS drag first; ROAS declining — address rank IS loss via QS improvement |
| Competitor | Search | $8.5K | $612 | 4.5x | TIER 2 | Switch from Maximize Conversions to Manual CPC — insufficient conversion data for Smart Bidding |
| PMax - All Products | PMax | $18K | $284 | 3.4x | TIER 3 | Apply brand exclusions immediately; add customer match audience signal; restructure asset groups |
| Display Retargeting | Display | $5.3K | $891 | 2.6x | TIER 3 | Pause or reduce to $2K; reallocate $3.3K to Brand campaign |

**QUALITY SCORE FINANCIAL IMPACT**

3 ad groups at QS 4 (Cloud Cost Monitoring, AWS Optimization, DevOps Tooling):
- Estimated CPC penalty: 22% above market rate = $380/month additional CPL tax
- Root cause: Low Expected CTR (headlines not matching search intent) + Poor Landing Page Experience (DevOps-specific page sending to generic homepage)
- Fix: Rewrite headlines to mirror "cloud cost optimization for DevOps" intent; send to /solutions/devops landing page
- Projected CPL improvement after fix: -$47/lead across Non-Brand Core (18% reduction)

**REVENUE LEFT ON TABLE**
Non-Brand Core lost 14% of impressions to budget: estimated 890 missed impressions/month × 4.2% CTR × 12.8% conversion rate × $41K deal × 0.14 pipeline factor = **$28,400 in additional pipeline recoverable with $4,200 additional monthly budget** (6.8x incremental pipeline ROAS).

**IMMEDIATE 30-DAY ACTIONS**
1. Apply brand exclusion to PMax — prevents cannibalizing Brand campaign. Est. Brand IS recovery: +8%, pipeline impact: +$22,000 (HIGH confidence)
2. Add 12 waste term negatives immediately — $810 monthly waste recovered, reallocate to Non-Brand Core branded intent terms (HIGH confidence)
3. Switch Competitor campaign to Manual CPC with $4.50 bid floor — exit data-starvation Smart Bidding cycle, stabilize CPL within 2 weeks (MEDIUM confidence)

## Success Metrics

- Overall account pipeline ROAS meets or exceeds target within 45 days of implementing recommendations
- Quality Score improvement from ≤ 6 to ≥ 7 across flagged ad groups within 30 days
- Impression share lost to rank decreases by ≥ 15 percentage points within 60 days of QS fixes
- Smart Bidding campaigns exit "Learning" status and stabilize within target CPA ± 15% within 21 days of conversion volume fix
- Waste term negatives added within 7 days; CPL impact measurable within 21 days
- Budget reallocation model accuracy: actual pipeline delta within 25% of projected

## Related Prompts

- [`../../05_Analytics-&-Performance/Paid-Media-Performance-Analytics/AI-Powered-B2B-Paid-Search-&-Paid-Social-Cross-Channel-Performance-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Paid-Media-Performance-Analytics/AI-Powered-B2B-Paid-Search-&-Paid-Social-Cross-Channel-Performance-Intelligence-Engine.md)
- [`../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-&-PPC/AI-Powered-B2B-Google-Ads-Campaign-Strategy-&-Search-Intent-Demand-Capture-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-&-PPC/AI-Powered-B2B-Google-Ads-Campaign-Strategy-&-Search-Intent-Demand-Capture-Intelligence-Engine.md)
- [`../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md)
- [`../../05_Analytics-&-Performance/CAC-Payback-&-Unit-Economics-Analytics/AI-Powered-CAC-Channel-Efficiency-&-Marketing-Investment-Optimization-Intelligence-Engine.md`](../../05_Analytics-&-Performance/CAC-Payback-&-Unit-Economics-Analytics/AI-Powered-CAC-Channel-Efficiency-&-Marketing-Investment-Optimization-Intelligence-Engine.md)

## Integration Tips

- **Google Ads + HubSpot Offline Conversion Import**: Connect Google Ads to HubSpot using the Google Ads integration. Configure HubSpot to push "Deal Created" and "Deal Closed Won" events back to Google Ads as offline conversions via GCLID matching. This feeds actual revenue data into Smart Bidding — typically reduces CPL 15–30% within 60 days as the algorithm learns which clicks produce closed deals, not just form fills.
- **Google Ads API + Google Sheets Automation**: Use the Google Ads API (or a connector like Supermetrics or Coupler.io) to auto-export campaign performance data to Google Sheets weekly. Build a template that mirrors the input format for this prompt — then use a Claude API integration via Apps Script to run the analysis automatically every Monday morning and post results to Slack.
- **GA4 + Google Ads Linked Account**: Link GA4 to Google Ads and import GA4 conversion events (demo_request, trial_signup, contact_form_submit) as conversion actions. Use GA4's "Advertising" reports to see assisted conversion paths — identify which campaigns influence the journey even if they are not the last click before conversion.
- **Search Console Integration for QS Improvement**: Export Google Search Console's top queries for your domain alongside Google Ads search term reports. Identify organic keyword clusters with high impression volume that your paid campaigns are not targeting — these are QS-friendly keyword additions because Google already recognizes your page's relevance to those terms.
- **Salesforce Campaign Influence for Pipeline ROAS**: In Salesforce, use the Customizable Campaign Influence model to attribute pipeline to Google Ads campaigns. Export "Pipeline by Primary Campaign Source" and "Pipeline by Influenced Campaigns" — use both in this prompt for first-touch and multi-touch pipeline ROAS calculations. Set up Salesforce to capture GCLID in Lead records for precise campaign-level attribution.

## Troubleshooting

**Problem: Performance Max ROAS looks strong but actual pipeline quality is poor — many leads from PMax don't convert to MQLs.**
Solution: PMax optimizes for the conversion action you define, which is often a form fill — not an MQL or pipeline opportunity. If your defined conversion is "form submitted" and your MQL rate from PMax is < 20% vs. > 40% from Search, PMax is finding the wrong users. Fix this by (1) importing MQL or Deal Created as an offline conversion action with a higher conversion value than form fills, so Smart Bidding learns to prioritize quality leads; (2) tighten audience signals to your highest-converting customer segments; and (3) review PMax asset groups for consumer-facing vs. business-facing messaging — PMax often drifts toward broader, consumer-intent traffic.

**Problem: Smart Bidding on my Target CPA campaign keeps overshooting — CPL is 40–60% above target consistently.**
Solution: Smart Bidding overshoots when it has too few conversions to calibrate (< 30/month is the danger zone) or when your Target CPA is set too aggressively below historical performance. Diagnose: if you have < 30 conversions/month, switch to Maximize Conversions without a CPA target for 4–6 weeks to accumulate data, then reintroduce Target CPA at your actual historical average CPL (not your aspirational target). If conversion volume is sufficient but overshoot persists, check whether a recent budget cut or bid cap is creating constraints that confuse the algorithm — Smart Bidding performs best when given flexibility within ± 20% of its target.

**Problem: Impression share analysis says 28% lost to rank, but I've already raised bids — why hasn't IS improved?**
Solution: IS lost to rank is driven by Ad Rank, which is Quality Score × bid — raising bids alone is only half the equation. If QS is dragging your Ad Rank down, you can double bids and still lose to a competitor with a QS 9 campaign bidding less. Run a Quality Score audit (Step 3 in the Advanced framework) and identify which component is weakest: Expected CTR (headlines aren't resonating), Ad Relevance (keyword-to-ad mismatch), or Landing Page Experience (page speed, relevance, or UX issues in Google's assessment). Fixing QS from 5 to 7 typically costs $0 and reduces CPL more than a 30% bid increase would.

## Version History
- v1.0: Initial creation (auto-generated)
