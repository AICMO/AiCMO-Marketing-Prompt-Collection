# AI-Powered B2B SaaS Paid Search & SEM Analytics - Google Ads Revenue Attribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** paid-search, sem, google-ads, revenue-attribution, keyword-analytics, b2b-saas, demand-generation, pipeline-intelligence

## Overview

This prompt deploys a fully autonomous paid search analytics system that connects keyword-level Google Ads performance to pipeline contribution, closed-won revenue, and CAC efficiency — going beyond click and CPA metrics to reveal which search intents actually produce customers. Use it when you need to defend paid search budget, identify wasted spend, or make smart bidding decisions grounded in revenue outcomes rather than lead volume.

## Quick Copy-Paste Version

You are a senior B2B SaaS paid search analyst with deep expertise in Google Ads performance measurement, search intent attribution, and revenue contribution analytics.

Conduct a comprehensive paid search analytics audit for [Your SaaS Product] — a [product category] platform serving [ICP: e.g., "VP of Operations at 100-1000 person manufacturing companies"].

Our paid search situation:
- Monthly Google Ads spend: $[X]
- Primary conversion goal: [demo requests / trial signups / form fills]
- CRM: [HubSpot / Salesforce / other]
- Attribution model currently in use: [last-click / data-driven / other]
- Average deal size: $[X] ACV
- Average sales cycle: [X] days
- Monthly search conversions: [X]

Deliver the following analytics intelligence:

**1. Keyword Revenue Attribution Matrix**
For each keyword tier (brand, competitor, category, pain-point, solution), analyze:
- Conversion rate vs. MQL-to-SQL conversion rate vs. close rate
- Which search intents produce your highest-ACV customers vs. highest-volume leads
- Keywords with strong CTR/conversion but poor downstream pipeline contribution
- Keywords with weak CTR but strong pipeline-to-revenue conversion (underinvested)

**2. Search Term Report Intent Mining**
From the actual search queries triggering your ads:
- Identify the top 20 highest-revenue-contributing search terms (not just keywords)
- Surface search terms signaling competitor evaluation (should trigger conquest ads)
- Find search terms with zero revenue contribution but consuming >$500/month budget
- Map search intent to buyer journey stage (awareness / consideration / decision)

**3. Quality Score Diagnostic Report**
For each keyword cluster:
- Identify Quality Score below 6 and diagnose the primary root cause (CTR / ad relevance / landing page experience)
- Calculate the CPC premium being paid due to low Quality Scores (vs. competitor benchmark)
- Prioritize top 10 QS improvement opportunities by estimated budget savings per month

**4. Impression Share Gap Analysis**
- Where are you losing impression share to budget vs. rank?
- Which keywords have >60% impression share lost to rank (signal: need creative/QS improvement)
- Which keywords have >40% impression share lost to budget (signal: consider bid strategy or budget increase)
- Competitor auction insight analysis: where are specific named competitors consistently outranking you?

**5. Smart Bidding Performance Audit**
Evaluate each bidding strategy in use (tCPA, tROAS, Maximize Conversions, Performance Max):
- Is target CPA aligned with actual blended cost-per-pipeline opportunity (not cost-per-lead)?
- Where is smart bidding optimizing for the wrong signal (e.g., high-volume low-quality leads)?
- Performance Max cannibalization check: is PMax capturing brand traffic that should be attributed to branded search?
- Recommendation: which campaigns should shift to value-based bidding using CRM deal stage data?

**6. Budget Efficiency & Waste Audit**
- Top 10 keywords by spend with zero pipeline contribution in last 90 days → immediate pause/reduce candidates
- Hour-of-day and day-of-week performance segmentation: where is budget being spent during low-conversion windows?
- Device performance split: mobile vs. desktop conversion rate and pipeline contribution (most B2B shows 80%+ pipeline from desktop)
- Geographic performance: identify regions consuming budget with no closed-won revenue contribution

**7. Competitive Intelligence from Auction Data**
Using Auction Insights report data:
- Identify which competitors have increased outranking share in last 90 days
- Where are you losing top-of-page rate despite high bids (Quality Score issue vs. budget issue)?
- Recommend defensive keyword strategy for brand terms with high competitor presence

**8. 30-Day Optimization Action Plan**
Produce a prioritized action plan with:
- Immediate actions (week 1): Pause/reduce waste, fix critical QS issues
- Short-term (weeks 2-3): Reallocate budget to high-revenue keywords
- Structural changes (week 4): Bidding strategy adjustments, campaign restructuring recommendations
- Revenue impact estimate for each action

Output: A complete paid search analytics report with keyword revenue attribution matrix, waste identification list, QS improvement prioritization table, bidding strategy recommendations, and 30-day optimization calendar — formatted for both CMO review and hands-on PPC manager execution.

## Advanced Customizable Version

ROLE: You are a Principal B2B SaaS Paid Search Analytics Architect with 12+ years specializing in Google Ads performance measurement, search intent revenue attribution, and AI-assisted budget optimization for enterprise B2B companies. You have managed and audited $75M+ in annual Google Ads spend across SaaS companies from Series A through public markets. You think in pipeline contribution and CAC payback, not in CPCs and CTRs.

COMPANY CONTEXT:
- Company: [Company Name]
- Product: [One-sentence description of what the software does]
- ICP: [Job title + company size + industry vertical]
- Primary buying triggers: [3-5 business events that cause someone to buy your product]
- Key competitors targeted via Google Ads: [List 3-5 competitors]
- Monthly Google Ads budget: $[X] (search), $[X] (Performance Max), $[X] (display retargeting)
- CRM: [HubSpot/Salesforce/other] — connected to Google Ads via [import method]
- Current attribution model: [last-click / data-driven / linear]
- Sales cycle length: [X] days average
- Average ACV: $[X]
- MQL definition: [what qualifies as a marketing qualified lead]

BUSINESS OBJECTIVES:
- Primary goal: [Pipeline contribution / Closed-won revenue / CAC reduction / Market share capture]
- Secondary goal: [Brand protection / Competitor displacement / Category creation]
- Board-level KPI this analytics work must support: [e.g., "Reduce blended CAC by 25% in Q3 while maintaining pipeline coverage at 4x"]

PAID SEARCH DATA INPUTS TO ANALYZE:
Provide (or instruct the AI to simulate using realistic B2B SaaS benchmarks):
- Last 90 days of keyword performance data: impressions, clicks, CTR, avg CPC, conversions, conversion value
- Search terms report (last 30 days): actual queries, match type, clicks, conversions
- Auction Insights data: impression share, outranking share, overlap rate vs. named competitors
- Quality Score data by keyword: current QS, expected CTR, ad relevance, landing page experience scores
- CRM pipeline data mapped to Google Ads source: leads → MQLs → SQLs → opportunities → closed-won

ANALYSIS FRAMEWORK — EXECUTE ALL EIGHT MODULES:

MODULE 1: SEARCH INTENT REVENUE ATTRIBUTION
Classify all keywords into intent tiers and map to revenue outcomes:

Tier 1 — Decision Intent (highest priority):
- "[Product category] software" + pricing/cost modifiers
- "[Your brand]" brand terms
- "[Competitor] alternative/vs/comparison" terms
- "Best [product category]" + buyer modifiers
Expected characteristics: Lower volume, higher CPCs, highest close rates (target: >25% lead-to-close)

Tier 2 — Evaluation Intent:
- "[Product category] for [industry/use case]"
- Feature-specific terms: "[capability] tool/software/platform"
- Problem-solution terms: "how to [solve problem your product solves]"
Expected characteristics: Medium volume, moderate CPCs, strong MQL quality (target: >15% lead-to-close)

Tier 3 — Awareness/Education Intent (exercise caution):
- Generic problem terms without solution modifier
- Industry terms without purchase intent signal
- "What is [category]" informational queries
Expected characteristics: High volume, low CPCs, poor lead quality (target: evaluate strictly on assisted conversion value)

For EACH tier, output:
- Keyword count currently active
- Spend allocation ($ and % of total budget)
- Conversion volume and CPA
- Estimated pipeline contribution (use CRM data or apply historical MQL-to-pipeline rate)
- Revenue efficiency score: Revenue Attributed / Spend (target ratio by tier)
- Investment recommendation: Increase / Maintain / Reduce / Pause

MODULE 2: SEARCH TERM INTELLIGENCE REPORT
Mine the raw search terms report for revenue signal:

A. High-Value Search Terms Underrepresented as Keywords:
   - Queries with 3+ conversions but not yet added as exact match keywords
   - Queries indicating specific use case or industry fit that should trigger dedicated ad groups
   - Long-tail queries with CPAs below $[target CPA] — candidates for keyword expansion

B. Negative Keyword Opportunities:
   - Queries with 5+ clicks and zero conversions consuming >$[X] budget
   - Queries indicating wrong ICP (company size too small, wrong industry, consumer intent)
   - Competitor brand queries (if not running conquest campaigns, these waste budget)
   - Job seeker queries: "jobs at [competitor]", "careers [category]", "[category] salary"
   - Academic/research queries: "what is", "definition of", "history of"

C. Competitor Intent Queries:
   - Search terms containing competitor brand names → route to dedicated conquest ad groups
   - "[Competitor] reviews/problems/issues" → high-intent displacement opportunity
   - "[Competitor] pricing" → buyer actively evaluating, needs immediate ROI comparison ad

D. Emerging Intent Signals:
   - New search terms appearing in last 30 days with >10 impressions
   - Seasonal or event-triggered queries (product launches, regulations, market events)
   - AI-related search terms if product has AI capabilities ("[capability] AI", "AI [category]")

MODULE 3: QUALITY SCORE REVENUE IMPACT ANALYSIS
Model the revenue impact of Quality Score improvements:

For each keyword with QS < 7:
a) Diagnose primary QS driver using this waterfall:
   - Below average Expected CTR → Ad copy relevance problem (headline doesn't match query)
   - Below average Ad Relevance → Keyword-to-ad misalignment (wrong ad group structure)  
   - Below average Landing Page Experience → Page load speed, content relevance, or mobile UX

b) Calculate CPC Premium:
   Formula: (Competitor QS / Your QS) × Your Bid ≈ Effective CPC premium
   A keyword at QS 5 vs. competitor at QS 8 costs ~37% more per click to achieve same position.

c) Prioritize QS improvements by:
   - Monthly spend on affected keywords (fix the most expensive problems first)
   - Estimated CPC reduction if QS improves from current to target (QS 7+)
   - Implementation complexity: landing page changes (hard) vs. ad copy changes (easy)

QS Improvement Playbook by Root Cause:
- Low Expected CTR: Test 3 new RSA headline variants emphasizing benefit clarity and query match; add ad customizers for dynamic keyword insertion on exact match campaigns
- Low Ad Relevance: Break large ad groups into single keyword ad groups (SKAGs) for highest-spend terms; ensure each ad group contains <10 tightly themed keywords
- Low Landing Page Experience: Audit page load time (target <2.5s LCP); ensure above-fold content directly answers the search query; add FAQ schema for informational-adjacent terms

MODULE 4: IMPRESSION SHARE STRATEGIC ANALYSIS
Categorize impression share loss and prescribe specific actions:

Budget-Limited Keywords (IS Lost to Budget > 30%):
- These keywords want to run but can't — you're leaving intent signals uncaptured
- Calculate: Daily budget required to capture 90% IS = (Current spend / Current IS) × 0.9
- Prioritize budget expansion here BEFORE pausing underperformers
- Consider: campaign-level vs. shared budget adjustments

Rank-Limited Keywords (IS Lost to Rank > 40%):
- Your bid × Quality Score isn't competitive enough
- Step 1: Fix Quality Score (more cost-effective than raising bids)
- Step 2: If QS is already 7+, consider manual bid increase or tCPA target reduction
- Step 3: Review search partner performance — sometimes disabling partners improves rank on Google.com

Absolute Top IS Analysis:
- Brand keywords should achieve >80% Absolute Top IS — anything below signals competitor aggression
- High-value decision-intent keywords: target >50% Absolute Top IS
- Category awareness terms: Absolute Top IS is less critical, optimize for cost efficiency

Auction Insights Competitive Matrix:
For each major competitor appearing in Auction Insights:
| Competitor | Overlap Rate | Outranking Share | Position Above Rate | Threat Level |
|------------|-------------|-----------------|--------------------|-|
| [Competitor A] | [X%] | [X%] | [X%] | High/Med/Low |
| [Competitor B] | [X%] | [X%] | [X%] | High/Med/Low |

Recommended responses by threat level:
- High threat (outranking >50% of overlaps): Defensive bid increase on shared keywords + quality improvement sprint
- Medium threat: Monitor weekly, test ad copy that directly references your advantage vs. this competitor
- Low threat: No action needed, redirect budget to other opportunities

MODULE 5: SMART BIDDING AUDIT & VALUE-BASED BIDDING UPGRADE PATH
Evaluate current automated bidding performance:

Phase 1 — tCPA/tROAS Health Check:
- Is the target CPA set based on cost-per-form-fill or cost-per-pipeline-opportunity? (The former creates misaligned optimization)
- Correct formula for B2B tCPA target: (Pipeline Opportunity Target Value) × (MQL-to-Opportunity Rate) = tCPA that generates real pipeline
  Example: Target $15,000 pipeline opportunity × 12% MQL-to-Opportunity rate = $1,800 tCPA per conversion
- Is the learning period (minimum 30 conversions per month) being met? If not, consolidate campaigns.

Phase 2 — Performance Max Cannibalization Audit:
- Pull brand search terms appearing in PMax search terms report → brand queries should be excluded from PMax
- Compare branded CPC before and after PMax launch (PMax frequently bids on brand, inflating costs)
- Determine if PMax is serving on competitor brand terms (check auction overlap report)
- Recommendation: Create brand exclusion lists in PMax asset groups; run dedicated brand campaign on Manual CPC or Maximize Clicks with brand bid cap

Phase 3 — Value-Based Bidding Implementation Plan:
Connect Google Ads to CRM revenue data for bid optimization on actual revenue, not lead volume.

Step 1: Define conversion values by lead quality tier
- Trial signup from Tier 1 account (>500 employees, target industry): Value = $[X] (based on historical close rate × ACV)
- Demo request from ICP-fit company: Value = $[X]
- Content download / webinar registration: Value = $[X] (assisted value, typically 10-20% of demo value)

Step 2: CRM integration for offline conversion import
- Connect Salesforce/HubSpot pipeline stage changes as offline conversion events imported back to Google Ads
- Opportunity Created: import as secondary conversion with full opportunity value
- Closed-Won: import as primary revenue conversion with actual ACV

Step 3: Bid strategy upgrade path
- Current state: tCPA on form fills → produces lead volume but not pipeline
- Target state: tROAS on opportunity value → Google AI optimizes for keywords generating real pipeline
- Transition: 30-day learning period with existing conversion history imported as offline conversions first

MODULE 6: BUDGET WASTE IDENTIFICATION & REALLOCATION MAP
Find and reallocate budget from waste to revenue:

Waste Category 1 — Zero-Revenue Keywords (Last 90 Days)
Criteria: Keywords with ≥$500 spend + 0 MQLs/pipeline contribution
Action: Pause immediately unless strategic (brand protection or competitive blocking)
Estimated monthly savings: $[X]

Waste Category 2 — High-CPA Low-Quality Keywords
Criteria: CPA >3× target AND MQL-to-SQL rate <5%
Action: Reduce bids by 40% for 30 days; if no improvement, pause
Estimated monthly savings: $[X]

Waste Category 3 — Off-Hours Spend with Poor Conversion Rate
B2B SaaS benchmark: 75-85% of pipeline generated Mon-Fri 8am-6pm local time
- Run ad schedule analysis by hour + day of week
- Apply bid adjustments: -50% on weekend spend unless conversion data contradicts
- Apply -30% bid adjustment on weekday hours 8pm-6am
Estimated monthly savings: $[X]

Waste Category 4 — Mobile Traffic with Poor Pipeline Conversion
B2B SaaS benchmark: Mobile clicks convert at 40-60% of desktop rate for pipeline generation
- Calculate mobile CPA vs. desktop CPA from CRM data
- If mobile CPA >2× desktop CPA: apply -40% mobile bid adjustment
- Exception: if your product is mobile-first or ICP uses mobile for research (validate with CRM data)
Estimated monthly savings: $[X]

Waste Category 5 — Geographic Underperformers
- Map spend by region vs. closed-won customers by region
- Identify regions with >5% of spend but <1% of closed-won revenue
- Exclude or severely reduce budget in these regions
Estimated monthly savings: $[X]

Budget Reallocation Target:
Total waste identified: $[X]/month
Reallocation priority:
1. High-revenue, budget-limited keywords (Impression Share Lost to Budget >30%)
2. Competitor conquest campaigns on underserved terms
3. New test campaigns targeting emerging high-intent queries

MODULE 7: PIPELINE CONTRIBUTION REPORTING TEMPLATE
Create a CMO-ready paid search revenue report:

Weekly Paid Search Pipeline Report (for marketing ops automation):
- Paid search spend this week: $[X] vs. budget $[X] (pacing %)
- Conversions (leads): [X] — vs. target [X]
- Pipeline opportunities created (from CRM): [X] — vs. target [X]
- Pipeline value created: $[X] — vs. target $[X]
- Cost-per-pipeline-opportunity: $[X] — vs. target $[X] — trend vs. last 4 weeks
- Top 5 performing keywords by pipeline contribution this week
- Top 3 keywords consuming budget with zero pipeline contribution (flagged for review)

Monthly Executive Dashboard Metrics:
- Total paid search investment: $[X]
- Pipeline sourced (first-touch): $[X] — % of total pipeline goal
- Pipeline influenced (assisted): $[X]
- Closed-won revenue attributed to paid search (90-day rolling): $[X]
- Paid search CAC: $[X] — vs. target $[X] — vs. last quarter
- CAC payback period for paid search cohort: [X] months
- Search impression share vs. key competitors: [X%] — trend
- Brand impression share: [X%] — alert if drops below 80%

MODULE 8: 30-DAY OPTIMIZATION SPRINT PLAN
Week 1 — Stop the Bleeding (Waste Elimination):
- Day 1-2: Add identified negative keywords across all campaigns (estimated savings: $[X]/month)
- Day 2-3: Pause zero-revenue keywords consuming >$500/month
- Day 3-5: Apply device bid adjustments based on mobile performance data
- Day 5-7: Apply ad schedule bid adjustments based on hour-of-day analysis
Expected week 1 budget efficiency gain: 15-25% of wasted spend recaptured

Week 2 — Quality Score Improvement Sprint:
- Restructure top 3 lowest-QS ad groups into single-theme ad groups
- Write and launch 3 new RSA variants for each restructured ad group
- Submit top 5 landing page improvement requests to web team with QS impact estimates
Expected impact: +1-2 QS points on targeted keywords within 2-3 weeks (lag time)

Week 3 — Budget Reallocation to Revenue Keywords:
- Increase bids on keywords identified as budget-limited with strong pipeline contribution
- Launch or expand competitor conquest campaigns with new ad copy tested
- Adjust tCPA targets to reflect MQL-to-pipeline rates (not just conversion volume)
Expected impact: 10-20% more pipeline from same total budget

Week 4 — Measurement Infrastructure Upgrade:
- Implement offline conversion import from CRM (opportunity created + closed-won)
- Set up value-based conversion tracking in Google Ads
- Enable data-driven attribution for campaigns with sufficient conversion volume
- Build automated weekly pipeline contribution report in Looker Studio / Google Sheets
Expected impact: Better AI bidding signals, enabling continued CPA improvement in month 2+

CONSTRAINTS:
- Every recommendation must include estimated revenue impact, not just efficiency metrics
- Flag any changes requiring development resources vs. what can be done in Google Ads UI directly
- Provide specific instructions for implementation: exact settings, bid modifier amounts, budget reallocations
- Output must be structured for two audiences: (1) CMO-ready executive summary, (2) PPC manager implementation checklist

OUTPUT DELIVERABLES:
1. Executive Summary: 5-bullet paid search health scorecard with traffic light status (Green/Yellow/Red)
2. Keyword Revenue Attribution Matrix (spreadsheet-ready table format)
3. Waste Identification Report: Keywords to pause/reduce with $ savings estimate
4. Quality Score Improvement Priority List: Top 10 issues ranked by revenue impact
5. Budget Reallocation Map: From/to allocation with projected pipeline impact
6. 30-Day Sprint Calendar: Day-by-day implementation guide for PPC manager
7. Value-Based Bidding Upgrade Roadmap: Step-by-step CRM integration plan

## Example Input/Output

**Input Example:**

Company: Nexlane — a B2B SaaS platform for construction project management
ICP: VP of Operations / Project Director at general contractors with 50-500 employees
Monthly Google Ads budget: $45,000/month (search: $35,000, PMax: $10,000)
CRM: HubSpot with Google Ads connected via imported conversions (form fills only)
Average ACV: $28,000 | Sales cycle: 75 days | MQL-to-Close rate: 11%
Current conversion tracking: demo request form fill = 1 conversion (flat, no value assigned)
Last 90 days: 340 conversions, 32 MQLs, 8 pipeline opportunities created, 2 closed-won deals

---

**Output Example (excerpt):**

**Paid Search Health Scorecard — Nexlane (Last 90 Days)**

| Metric | Current | Target | Status |
|--------|---------|--------|--------|
| Cost-per-Pipeline-Opportunity | $4,218 | $2,800 | 🔴 Red |
| Brand Impression Share | 73% | >85% | 🟡 Yellow |
| MQL-to-Opportunity Rate | 25% | 30% | 🟡 Yellow |
| Waste % of Budget | 31% | <10% | 🔴 Red |
| QS Weighted Average | 5.8 | >7.0 | 🟡 Yellow |

**Top Revenue Finding:** "construction project management software" and "construction scheduling software" — both Tier 1 keywords — are limited by budget at 41% and 38% impression share respectively. Together they produced 6 of 8 pipeline opportunities but are losing to rank on 22% of auctions where Turner Tech (competitor) holds QS 8 vs. Nexlane's QS 6. Fixing these two QS issues before increasing budget is priority #1.

**Immediate Waste Identified — $12,800/month:**
- "project management software" (no industry modifier): $3,200 spend, 0 pipeline opportunities in 90 days → Pause
- Weekend spend (Sat/Sun): $2,100/month at 0.3% conversion rate vs. 2.1% weekday rate → -70% bid adjustment
- Mobile traffic: $4,800/month, 0 closed-won opportunities (all 2 won deals had desktop-first journey) → -50% mobile bid adjustment
- "free construction software" query variants: $1,400 spend, 0 MQLs (wrong ICP, no budget) → Negative keywords

**Value-Based Bidding Opportunity:** Currently Google AI optimizes for $0 conversion value (all conversions treated equally). By importing HubSpot pipeline stage data with values (Demo: $280 value proxy / Opportunity: $3,080 value proxy / Closed-Won: $28,000 actual ACV), estimated tROAS improvement: 35-45% lower CAC within 60 days of learning period completion.

**30-Day Pipeline Impact Projection:**
- Waste elimination + reallocation: +3-4 additional pipeline opportunities/month
- QS improvement on top 2 keywords: -$340 CPC reduction per click (estimated when QS reaches 8)
- Value-based bidding (month 2): -30% cost-per-pipeline-opportunity
- Total projected impact: Pipeline contribution from paid search from $224K/quarter → $310K/quarter

## Success Metrics

- **Primary:** Cost-per-pipeline-opportunity decreases 20-35% within 60 days of implementing waste elimination and bidding realignment
- **Brand Protection:** Brand keyword impression share consistently >85% (flag if drops below 80% for 3+ consecutive days)
- **Quality Score:** Weighted average QS across all active keywords reaches 7.0+ within 45 days of copy/landing page improvements
- **Budget Efficiency:** Waste % of total budget (keywords with zero pipeline contribution) drops below 10%
- **Attribution Completeness:** >90% of pipeline opportunities have a traceable paid search touch within 30 days of CRM integration
- **Reporting Cadence:** Automated weekly pipeline contribution report running without manual intervention within 30 days

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Retargeting/AI-Powered-B2B-SaaS-Google-Ads-RLSA-&-Performance-Max-Search-Retargeting-Architecture-Revenue-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-PPC-&-Social/AI-Powered-B2B-SaaS-Google-Ads-Campaign-Architecture-&-Paid-Search-Revenue-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/AI-Powered-B2B-Revenue-Attribution-Model-Architecture-&-Unified-Measurement-Framework-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/CAC-Payback-&-Unit-Economics-Analytics/CAC-Payback-&-Unit-Economics-Intelligence-Engine.md`

## Integration Tips

- **Google Ads → HubSpot/Salesforce:** Use the native Google Ads integration (HubSpot) or Salesforce connector to import pipeline stage changes as offline conversions — this is the single highest-leverage action for improving bid optimization
- **Looker Studio:** Connect Google Ads API + CRM data in Looker Studio to automate the weekly pipeline contribution report; template available via Google Ads "Report Editor" with CRM blended data source
- **Zapier / Make (Integromat):** When a HubSpot deal reaches "Opportunity Created" stage, trigger a Zapier flow to push the deal value and original Google Ads GCLID to a Google Sheets log for offline conversion import
- **Google Ads Scripts:** Automate the weekly waste audit — run a Google Ads Script every Monday that flags any keyword with >$300 spend + 0 conversions in the last 14 days and sends a Slack alert to the PPC manager
- **Supermetrics + BigQuery:** For enterprise-scale analysis, pull keyword-level data into BigQuery via Supermetrics; join against CRM closed-won data to run the full keyword revenue attribution matrix on SQL
- **Attribution Tools (Northbeam, Triple Whale, Rockerbox):** If using a third-party attribution platform, export the paid search channel contribution report and layer against this prompt's framework for a cross-validation check on your in-platform data

## Troubleshooting

**Problem:** CRM data shows very few conversions traceable back to specific keywords (attribution gaps)
*Solution:* Audit your GCLID auto-tagging setup — ensure Google Ads auto-tagging is enabled AND your CRM/landing page is preserving the GCLID parameter through form submissions. In HubSpot, check that the "Google Ads conversion tracking" feature is enabled. In Salesforce, verify the GCLID field is captured on Lead and Contact records. Most attribution gaps are GCLID tracking failures, not actual attribution problems.

**Problem:** Performance Max campaigns show strong conversion volume but the pipeline data doesn't match — PMax appears to be over-claiming credit
*Solution:* This is the most common PMax cannibalization pattern. Run a 2-week experiment: pause PMax and check if brand search campaign conversions increase proportionally. If brand search picks up 60-80% of PMax volume, PMax was largely capturing brand intent. Add your brand terms as negative keywords in PMax and use a separate brand campaign at Manual CPC. For competitive terms, pull the PMax search terms report (Settings → Insights → Search Terms) and verify PMax isn't bidding on competitor brand queries.

**Problem:** Smart bidding is not generating enough conversions to exit the learning phase (shown as "Limited" status)
*Solution:* Google Ads requires a minimum of 30 conversions per 30-day period per campaign to exit the learning phase effectively. If you're below this threshold: (1) Consolidate campaigns — combine similar campaigns to pool conversion volume; (2) Lower your funnel threshold — track a higher-funnel action like "pricing page visit" or "contact page visit" as a secondary micro-conversion with a low value ($5-10) to give the algorithm more signal; (3) Import historical offline conversion data (last 6 months of CRM data) to seed the algorithm before the learning period starts.

## Version History

- v1.0: Initial creation (auto-generated)
