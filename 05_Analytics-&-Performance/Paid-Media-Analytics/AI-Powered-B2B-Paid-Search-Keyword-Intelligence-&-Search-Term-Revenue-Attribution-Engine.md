# AI-Powered B2B Paid Search Keyword Intelligence & Search Term Revenue Attribution Engine

**Difficulty:** Advanced | **Time:** 20 min | **Tags:** b2b, paid-search, google-ads, microsoft-ads, keyword-analytics, revenue-attribution, ppc, search-intent, pipeline-optimization

## Overview
Analyzes search term query reports, keyword-level pipeline data, and Quality Score signals to identify which queries actually drive revenue (vs. just clicks), surface budget waste from irrelevant or low-conversion terms, optimize Smart Bidding signals, and build a keyword portfolio strategy that maximizes pipeline-per-dollar. Use this when CPL is rising despite stable spend, when you're scaling paid search budgets, or when you need to prove keyword-level ROI to leadership.

## Quick Copy-Paste Version

You are a B2B paid search expert specializing in revenue attribution. Analyze the following keyword and search term data and produce a comprehensive optimization report.

SEARCH TERM / KEYWORD DATA:
[Paste your search term report: Search Term | Match Type | Impressions | Clicks | CTR | Avg CPC | Spend | Conversions | Conv Rate | Pipeline Generated | Closed-Won Revenue | Quality Score (if available)]

BUSINESS CONTEXT:
- Product: [what you sell]
- ICP: [ideal customer — e.g., "VP of Finance at 200-2000 employee SaaS companies"]
- Average ACV: [your ACV]
- Average sales cycle: [weeks]
- Monthly paid search budget: [total]
- Primary conversion goal: [demo request / trial signup / contact form]
- CRM attribution available: [Yes/No — if yes, specify model]

ANALYSIS REQUIRED:
1. Segment all search terms into 4 categories: Revenue Drivers, Volume Traps, Brand Defense, and Waste (define criteria for each)
2. Identify the top 10 search terms generating pipeline and calculate cost-per-pipeline-dollar for each
3. Surface the top 15 search terms spending budget with zero or near-zero pipeline contribution — these are your immediate cut list
4. Recommend specific bid adjustments for Revenue Driver terms (increase %) and Waste terms (pause/reduce)
5. Extract a negative keyword list of at least 20 terms from the Waste segment — include match type for each
6. Identify 5 high-intent query patterns that should be added as exact-match keywords
7. Assess keyword-to-landing page message match: flag terms where intent misaligns with destination page
8. Score overall search term portfolio health on 5 dimensions: Intent Alignment, Revenue Concentration Risk, Competitive Coverage, Negative Keyword Hygiene, Smart Bidding Signal Quality

Output as: Executive Summary (3 bullets), Search Term Segmentation Table, Revenue Driver Deep-Dive, Negative Keyword List, Bid Strategy Recommendations, Portfolio Health Scorecard, and 30-day Action Plan.

## Advanced Customizable Version

ROLE: You are a senior B2B paid search analyst with 10+ years of experience managing Google Ads and Microsoft Advertising accounts for enterprise SaaS companies. You specialize in connecting search query data to CRM pipeline, optimizing Google Smart Bidding with offline conversion imports, and building keyword portfolio strategies that scale efficiently without inflating CPL.

CONTEXT:
Company: [Company name]
Product category: [e.g., "cloud data observability platform"]
Primary ICP: [e.g., "VP of Data Engineering, VP of IT Operations at 200-5,000 employee companies"]
Secondary ICP (if applicable): [e.g., "Director of Analytics at mid-market SaaS"]
Revenue stage: [Startup scaling / Growth / Enterprise optimization]
Monthly paid search budget (Google + Microsoft): $[X,XXX]
Quarterly pipeline target from paid search: $[X]M
Current pipeline generated this quarter: $[X] ([X]% to goal)
Average ACV: $[X,XXX]
Average sales cycle: [X] weeks
Primary conversion action: [Demo request / Free trial / Contact sales / Gated content download]
CRM: [HubSpot/Salesforce]
Attribution model in use: [Last-touch / First-touch / Linear / Time-decay / Data-driven]
Offline conversion import status: [Active / Not set up / Partial — leads only]

SEARCH CAMPAIGN STRUCTURE:
Number of active campaigns: [X]
Campaign types: [Search / DSA / Performance Max / Smart — list all]
Bidding strategy: [Manual CPC / Target CPA / Target ROAS / Maximize Conversions — per campaign]
Current Target CPA: $[X] | Current Target ROAS: [X]x
Average Quality Score across account: [X/10]
Impression share: [X]% | Lost IS (budget): [X]% | Lost IS (rank): [X]%

SEARCH TERM QUERY DATA (Last 30/60/90 days — specify):
Format: Search Term | Match Type Triggered | Campaign | Ad Group | Impressions | Clicks | CTR | Avg CPC | Spend | Form Fills | MQLs | SQLs | Pipeline Generated | Closed-Won | Quality Score (keyword level)
[Paste full search term report — minimum 50 rows for meaningful analysis]

KEYWORD-LEVEL PERFORMANCE (separate from search terms):
Format: Keyword | Match Type | Bid | Impressions | Clicks | Avg Position | Spend | Conversions | Pipeline $ | Quality Score | Landing Page
[Paste keyword data]

COMPETITOR CONTEXT:
Primary competitors in auction: [list 3-5]
Known competitor keywords you're targeting: [list]
Competitor brand terms in your search term report: [yes/no — list if yes]
Your brand terms in competitor search (if known): [yes/no]

OBJECTIVE:
Produce a definitive keyword intelligence report that (1) identifies exactly where budget is being wasted, (2) reveals which search queries are generating the most revenue, (3) provides actionable bid and structure recommendations, and (4) improves the quality of signals feeding into Google Smart Bidding — all executable without waiting for a new campaign flight.

DELIVERABLES:

1. SEARCH INTENT PORTFOLIO ANALYSIS
   Classify all search terms into intent tiers:
   
   Tier 1 — HIGH COMMERCIAL INTENT (ready to evaluate vendors)
   Examples: "[product category] software," "best [product] for [use case]," "[competitor] alternative"
   Metrics target: CTR >3%, Conv Rate >4%, pipeline ROAS >8x
   
   Tier 2 — SOLUTION-AWARE (know the problem, exploring solutions)
   Examples: "how to [solve problem your product addresses]," "[problem] platform," "[use case] tool"
   Metrics target: CTR >2%, Conv Rate >2%, pipeline ROAS >4x
   
   Tier 3 — PROBLEM-AWARE (know the pain, not the category)
   Examples: "[symptom of problem]," "[pain point]," "[job title] challenges"
   Metrics target: CTR >1%, Conv Rate >0.5%, pipeline ROAS >2x
   
   Tier 4 — WASTE (irrelevant, non-ICP, or informational with no conversion signal)
   Immediate action: pause or add as negative keywords
   
   For each tier: total spend %, total pipeline %, ROAS, recommended bid posture

2. REVENUE DRIVER DEEP-DIVE
   For the top 20 search terms by pipeline generated:
   | Search Term | Tier | Match Type | Spend | Pipeline $ | Pipeline ROAS | Cost-per-SQL | Quality Score | Bid Recommendation | Landing Page Fit (A/B/C) |
   
   For each Revenue Driver:
   - Current keyword match type — is it broad when it should be exact? (Signal: high impression share from irrelevant variants)
   - Landing page message alignment score (1-5): does the page immediately address the search intent?
   - Bid headroom analysis: is the term at impression share <80%? If so, calculate $ needed to capture remaining share
   - Smart Bidding signal contribution: is this term getting enough conversions (>10/month) to inform Target ROAS/CPA algorithms?

3. BUDGET WASTE IDENTIFICATION
   Terms to pause or deprioritize (sorted by $ wasted):
   | Search Term | Spend (Period) | Pipeline $ | ROAS | Waste Classification | Recommended Action |
   
   Waste classifications:
   - IRRELEVANT: query has no product-ICP match (e.g., "free" modifier when product is $50K ACV)
   - INFORMATIONAL TRAP: high volume, educates but doesn't convert (e.g., "what is [category]")
   - JOB SEEKER: terms triggering from hiring/career intent
   - STUDENT/RESEARCHER: academic or research intent with no commercial signal
   - COMPETITOR MOAT: competitor brand terms where your conversion rate <0.5% (cost of impression share not worth it)
   - BROAD MATCH BLEED: irrelevant expansions from broad/BMM keywords generating wasted spend
   
   Total rescue budget: $[X] per month that can be reallocated

4. NEGATIVE KEYWORD MASTER LIST
   Provide minimum 30 recommended negative keywords with:
   | Negative Keyword | Match Type (Exact/Phrase/Broad) | Campaign or Account Level | Rationale | Estimated Monthly Savings |
   
   Categories to cover:
   - Job/career intent terms
   - "Free" / "open source" / "DIY" intent modifiers
   - Non-ICP company size signals ("small business," "personal," "individual")
   - Informational-only queries with no buying signal
   - Competitor brand terms where conversion data doesn't justify cost
   - Geographic qualifiers if not in target markets
   - Academic/student signals ("thesis," "research paper," "assignment")

5. KEYWORD GAP ANALYSIS
   High-intent search patterns NOT currently captured as keywords:
   | Recommended New Keyword | Match Type | Estimated Monthly Searches | Intent Tier | Suggested Bid | Ad Group Placement | Landing Page Recommendation |
   
   Sources to analyze:
   - Search terms triggering from broad/phrase campaigns not yet as exact-match keywords
   - Competitor name + "alternative" / "vs" / "comparison" patterns
   - Job-title-qualified high-intent terms ("VP of Engineering [category] software")
   - Use-case-specific terms from your ICP's language (not your internal product language)
   - "Best [category] for [industry]" patterns — check which industries your closed-won customers are in

6. QUALITY SCORE OPTIMIZATION PLAN
   For keywords with Quality Score ≤6/10:
   | Keyword | Current QS | Expected CTR Issue | Ad Relevance Issue | Landing Page Issue | Specific Fix | Expected QS Improvement |
   
   Quality Score improvement levers (apply in order of impact):
   a. Ad copy relevance: headline 1 must contain the exact keyword or close variant
   b. Landing page keyword density: target keyword should appear in H1, first paragraph, and meta title
   c. Expected CTR: compare ad copy CTR to account average — rewrite underperformers
   d. Ad group structure: ensure single-theme ad groups (STAGs) for Revenue Driver terms
   e. Negative keyword pruning: remove irrelevant traffic inflating bounce rates on landing pages

7. SMART BIDDING SIGNAL ENRICHMENT PLAN
   Google Smart Bidding (Target ROAS/CPA) learns from conversion signals. Weak signals = poor optimization. Assess:
   
   Current signal quality:
   - Total monthly conversions feeding Smart Bidding: [X] (minimum threshold: 30-50/month per campaign for reliability)
   - Offline conversion import: [active/not active] — CRITICAL: if not importing SQLs or pipeline data, Smart Bidding is optimizing for CPL not revenue
   - Conversion value assignments: are you using actual ACV or a flat value? (Flat value = misleading ROAS data)
   
   Recommendations:
   - Import CRM stage milestones as micro-conversions: Form Fill (value: $50), MQL (value: $200), SQL (value: $1,000), Opportunity Created (value: $5,000)
   - Set Target ROAS campaigns to optimize toward pipeline value (not just lead value)
   - Create a "revenue signal" audience from closed-won customers and use for RLSA bid boosts (+30-50%) on Revenue Driver terms
   - Portfolio bid strategy assessment: should campaigns be consolidated under one portfolio strategy or managed separately?

8. BID STRATEGY & STRUCTURE RECOMMENDATIONS
   | Campaign/Ad Group | Current Bid Strategy | Current Bid/Target | Recommended Change | Rationale | Expected Impact |
   
   Priority restructuring recommendations:
   - Revenue Driver terms with <80% impression share: increase bids or raise Target CPA
   - Waste-heavy broad match campaigns: convert to phrase/exact or add extensive negative lists
   - Ad groups with >20 keywords: break out top performers into dedicated STAGs
   - Campaigns sharing budget with conflicting intent tiers: separate budgets to control spend allocation

9. LANDING PAGE-TO-QUERY ALIGNMENT AUDIT
   For your top 30 highest-spend search terms, score message match (1-5):
   5 = Page H1 directly addresses the search query intent
   4 = Page addresses the category but not the specific use case in query
   3 = Page is tangentially relevant — generic product page
   2 = Page is wrong section of site (e.g., homepage for a product-specific query)
   1 = Complete mismatch — user will immediately bounce
   
   For any score ≤3: specify the recommended landing page change (H1 rewrite, CTA update, or new page creation)

10. 30-DAY EXECUTION ROADMAP
    | Week | Action | Channel/Campaign | Owner | Impact Estimate | Complexity |
    | Week 1 | Pause Waste-tier terms | All campaigns | PPC Manager | $X/month rescue | Low |
    | Week 1 | Upload negative keyword list | Account level | PPC Manager | $X/month rescue | Low |
    | Week 2 | Create STAGs for top Revenue Drivers | Google Search | PPC Manager | +X% QS, +X% pipeline | Medium |
    | Week 2 | Set up offline conversion import (SQLs) | Google Ads + CRM | RevOps + PPC | Smart Bidding improvement | Medium |
    | Week 3 | A/B test new ad copy for QS <6 keywords | Targeted campaigns | Copy + PPC | +X CTR | Medium |
    | Week 4 | Launch new keywords from Gap Analysis | New ad groups | PPC Manager | +$X pipeline/month | Medium |
    
    30-day success checkpoint metrics:
    - Rescue budget recaptured: $[X]
    - Pipeline ROAS improvement target: [X]x → [X]x
    - Quality Score improvement: average [X] → [X]
    - Smart Bidding signal volume: [X] → [X] conversions/month

OUTPUT FORMAT: Use markdown headers and tables for all structured data. Lead with the 3-bullet executive summary in CFO language (pipeline impact, waste identified, top opportunity). Write the action plan in PPC manager language — specific enough to execute in Google Ads UI without interpretation.

## Example Input/Output

**Input Example:**

Company: Veridian Security (B2B SaaS, cloud security posture management)
ICP: CISO and VP of Security at 500-5,000 employee enterprises
ACV: $120,000 | Sales cycle: 14 weeks
Monthly budget: $85,000 (Google Ads: $70K, Microsoft: $15K)
Quarterly pipeline target from paid search: $2.4M
Primary conversion: Demo request

Search term sample (last 60 days, top performers and worst offenders):
- "cloud security software" | Phrase | $8,400 | 22 MQLs | 7 SQLs | $840K pipeline | QS: 8
- "cspm tool" | Exact | $3,100 | 18 MQLs | 9 SQLs | $1.08M pipeline | QS: 9
- "cloud compliance platform" | Phrase | $4,200 | 14 MQLs | 5 SQLs | $480K pipeline | QS: 7
- "free cloud security scanner" | Broad | $2,800 | 8 MQLs | 0 SQLs | $0 pipeline | QS: 4
- "cloud security engineer jobs" | Broad bleed | $1,900 | 0 MQLs | 0 SQLs | $0 pipeline | QS: 3
- "what is cspm" | Phrase | $2,100 | 3 MQLs | 0 SQLs | $0 pipeline | QS: 5
- "wiz alternative" | Exact | $1,400 | 12 MQLs | 6 SQLs | $720K pipeline | QS: 8
- "prisma cloud alternative" | Phrase | $890 | 8 MQLs | 4 SQLs | $480K pipeline | QS: 7
- "cloud security for financial services" | BMM | $2,600 | 6 MQLs | 3 SQLs | $360K pipeline | QS: 6

**Output Example (abbreviated):**

**Executive Summary:**
- **Rescue opportunity:** $6,800/month wasted on irrelevant terms ("free" modifiers, job seeker bleed, pure informational queries) with zero pipeline contribution — immediate reallocation funds 8 additional competitor alternative campaigns
- **Revenue concentration:** 3 terms ("cspm tool," "cloud security software," "wiz alternative") account for $2.64M of $3.96M total pipeline attributed — create STAGs and increase impression share from current 68% to 90%+ on these three
- **Top unlock:** "cspm tool" has pipeline ROAS of 348x at $3,100 spend and 68% impression share — adding $4,200/month (redirected from waste) captures remaining 32% share, projected to yield $1.3M additional pipeline/quarter

**Search Term Segmentation:**
| Intent Tier | Terms (Count) | Spend % | Pipeline % | ROAS |
|---|---|---|---|---|
| Tier 1: High Commercial | 12 terms | 41% | 79% | 67x |
| Tier 2: Solution-Aware | 8 terms | 22% | 18% | 29x |
| Tier 3: Problem-Aware | 6 terms | 11% | 3% | 9x |
| Tier 4: Waste | 14 terms | 26% | 0% | 0x |

**Top 5 Negative Keywords to Add Immediately:**
- "free" [Broad Match] — Account Level — saves $1,200/month
- "jobs" [Phrase Match] — Account Level — saves $1,900/month
- "what is" [Phrase Match] — Account Level — saves $900/month
- "open source" [Phrase Match] — Account Level — saves $420/month
- "certification" [Broad Match] — Account Level — saves $380/month

**Critical QS Fix — "cloud security software" (QS: 8 → target 10):**
Current H1: "Cloud Security Platform for Enterprises" → Rewrite to "Cloud Security Software That Prevents Breaches Before They Happen" — direct keyword inclusion expected to raise Expected CTR grade from Average to Above Average.

## Success Metrics

- **Pipeline ROAS per keyword** — primary metric; B2B enterprise target: >10x for Tier 1 terms
- **Waste % of budget** — target <10% in irrelevant/non-converting search terms (industry benchmark: 25-35% for accounts without regular hygiene)
- **Revenue Driver impression share** — target >85% on top 10 pipeline-generating terms
- **Quality Score average** — target ≥7/10 across active keywords; <6 triggers immediate optimization sprint
- **Smart Bidding conversion volume** — target >50 qualified conversions/month per campaign for algorithm reliability
- **Cost-per-SQL** — should decrease 15-25% within 60 days of negative keyword hygiene and bid reallocation

## Related Prompts

- [AI-Powered B2B Paid Media Performance Analytics & Cross-Channel ROAS Revenue Intelligence Engine](./AI-Powered-B2B-Paid-Media-Performance-Analytics-&-Cross-Channel-ROAS-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B Google Ads Campaign Strategy & Search Intent Demand Capture Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-&-PPC/AI-Powered-B2B-Google-Ads-Campaign-Strategy-&-Search-Intent-Demand-Capture-Intelligence-Engine.md)
- [AI-Powered Competitive PPC Intelligence & Search Conquest Revenue Engine](../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-(PPC-&-Social)/AI-Powered-Competitive-PPC-Intelligence-&-Search-Conquest-Revenue-Engine.md)
- [AI-Powered B2B Revenue Attribution Model Architecture & Unified Measurement Framework Intelligence Engine](../Attribution-&-Revenue-Analytics/AI-Powered-B2B-Revenue-Attribution-Model-Architecture-&-Unified-Measurement-Framework-Intelligence-Engine.md)

## Integration Tips

- **Google Ads Search Term Report:** Navigate to Keywords → Search Terms in Google Ads UI. Export 90-day data as CSV, including "All conversions value" column. For pipeline data, cross-reference with HubSpot/Salesforce using the GCLID or UTM Source/Medium/Campaign fields — join on the "Google Click ID" dimension.
- **HubSpot CRM Integration:** Use HubSpot's "Traffic Analytics" with "Original Source Drill-Down 1" set to "Paid Search" to get keyword-to-deal attribution. For keyword-level granularity, enable Google Ads integration in HubSpot and use the "Ad Source" property on Deals.
- **Salesforce + Google Ads:** Install the Google Ads for Salesforce connector. Map GCLID → Lead Source Detail to track search terms to opportunities. Build a Salesforce report: "Opportunities by Paid Search Keyword" filtered to Closed Won for highest-accuracy revenue attribution.
- **Google Ads Offline Conversion Import:** Export SQL-stage CRM records weekly with GCLID and conversion value (ACV or pipeline stage value). Import via Google Ads → Tools → Conversions → Upload. This feeds actual revenue signals to Smart Bidding — this single integration typically improves Target ROAS performance by 20-40%.
- **Looker Studio Dashboard:** Build a live keyword intelligence dashboard: connect Google Ads API + Google Sheets (CRM export) → create a "Revenue Driver Monitor" showing top 20 keywords by pipeline ROAS, impression share, and QS with weekly trend lines. Automate analysis with this prompt via API on a weekly cadence.
- **Zapier + Claude API Automation:** Trigger: New row in Google Sheets (weekly Search Term Report auto-export via Google Ads script) → Action: Send to Claude API with this Advanced prompt → Output: Email weekly Paid Search Intelligence Brief to demand gen team + Slack notification to #paid-media channel.

## Troubleshooting

- **Problem:** CRM pipeline data can't be tied to specific search terms — only to "Paid Search" as a channel.
  **Solution:** Implement UTM parameter taxonomy immediately: `utm_source=google&utm_medium=cpc&utm_campaign={campaign_name}&utm_content={adgroupid}&utm_term={keyword}`. Use ValueTrack parameters in Google Ads to auto-populate `{keyword}` and `{matchtype}`. This gives you keyword-level attribution in HubSpot/Salesforce within 30 days. In the interim, use conversion rate as a proxy for revenue quality — search terms with >4% demo conversion rate and high intent signals should be treated as Revenue Drivers even without direct pipeline data.

- **Problem:** Smart Bidding is underperforming — Target ROAS is set at 5x but actual ROAS is 2.3x.
  **Solution:** The algorithm needs sufficient signal volume (30+ conversions/month per campaign) and accurate conversion values. First, check: are you only importing form fills (value: $150) rather than SQLs (value: $2,000) and pipeline (value proportional to ACV)? If Smart Bidding thinks every lead is worth $150 and your actual ACV is $80K, it will massively underinvest. Import multi-stage conversions with escalating values. Second, lower your Target ROAS to a more achievable threshold (e.g., 3x) and let the algorithm build signal for 6 weeks before raising it. Third, consolidate under-performing campaigns with similar intent into a portfolio bid strategy to share signal across campaigns.

- **Problem:** The search term report shows extensive broad match bleed into irrelevant queries, but the account uses Smart Bidding with broad match as the recommended Google setup.
  **Solution:** Google's broad match + Smart Bidding combination can work well when you have rich offline conversion data and a well-trained audience signal — but it requires aggressive negative keyword management to prevent waste. Run a 30-day negative keyword hygiene sprint: add all Tier 4 Waste terms as negatives at the account level. Then implement a monthly "Search Term Audit" cadence: every 30 days, export the search term report, flag terms with >100 impressions and zero conversions in the period, and add as negatives. This typically reduces waste spend by 20-30% within 60 days while preserving the reach benefits of broad match for high-intent terms.

## Version History
- v1.0: Initial creation (auto-generated)
