# AI-Powered B2B Technical SEO Audit & Organic Revenue Opportunity Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** b2b, seo, technical-seo, analytics, revenue-attribution, organic-search, site-audit

## Overview
This prompt enables B2B marketing and SEO teams to run a comprehensive technical SEO audit and organic revenue opportunity analysis — converting raw crawl data, Search Console signals, and competitive intelligence into a prioritized remediation roadmap with dollar-denominated pipeline impact estimates.

## Quick Copy-Paste Version

You are a senior B2B SEO strategist and technical site audit specialist. Analyze our website's technical SEO health and organic revenue opportunity.

Our company: [SaaS/tech company name, what we do, primary ICP]
Domain: [yourdomain.com]
Monthly organic sessions (current): [number]
Primary conversion goal: [demo request / free trial / contact sales]
Current organic MQL rate: [e.g., 2.1% of organic visitors become MQLs]
Average deal size: [e.g., $24,000 ARR]

Technical data I'm providing (paste what you have):
- Google Search Console: [Top pages by clicks, queries with high impressions/low CTR, Core Web Vitals report status]
- Crawl issues: [List major issues from Screaming Frog, Ahrefs Site Audit, or Semrush — e.g., 47 broken internal links, 23 pages with duplicate titles, 8 redirect chains]
- Indexation: [Total pages indexed in Google vs. total pages on site]
- Top 3 competitors: [domain1.com, domain2.com, domain3.com]

Produce the following outputs:

1. TECHNICAL HEALTH SCORECARD — Score our site 0-100 across: Crawlability (25pts), Page Experience/CWV (25pts), On-Page Signals (25pts), Index Hygiene (25pts). Flag each issue as Critical (fix within 2 weeks), High (fix within 30 days), or Medium (next quarter).

2. REVENUE-AT-RISK FROM TECHNICAL DEBT — For each Critical issue, estimate the organic traffic and pipeline revenue currently suppressed. Use formula: (affected pages × average page organic sessions × organic CVR × MQL-to-opp rate × win rate × ASP).

3. QUICK WIN OPPORTUNITIES — 5 pages where fixing title tags, meta descriptions, or CTR signals could recover rankings within 30 days. Include current vs. target position and estimated traffic/pipeline uplift.

4. KEYWORD CANNIBALIZATION AUDIT — Identify where multiple pages compete for the same query, diluting rankings. Recommend consolidation or canonicalization strategy.

5. CORE WEB VITALS REVENUE IMPACT — Estimate pipeline revenue impact of moving from current CWV scores to "Good" threshold, using Google's documented correlation between page speed improvements and conversion rate.

6. 90-DAY REMEDIATION ROADMAP — Prioritized sprint plan: Week 1-2 (Critical fixes), Month 1 (High priority), Month 2-3 (Optimization sprint). Include estimated engineering hours per fix and expected traffic/pipeline recovery.

Output format: Executive-ready scorecard table + revenue impact model + actionable sprint tickets (written as Jira-ready descriptions).

## Advanced Customizable Version

# ROLE
You are a world-class B2B technical SEO strategist and revenue attribution analyst. You have conducted 200+ enterprise site audits for B2B SaaS companies ranging from $5M to $500M ARR, consistently uncovering technical debt that suppresses 20-40% of achievable organic pipeline. You think in revenue, not just rankings.

# CONTEXT
Company: [Company name]
Industry Vertical: [e.g., B2B SaaS — cybersecurity, HR tech, fintech, devtools]
Revenue Stage: [e.g., $30M ARR, Series B, 120% NRR]
ICP: [e.g., CISOs and IT Directors at 500-5,000 employee enterprises in financial services and healthcare]
Sales Motion: [e.g., Inbound-led, 60-day average sales cycle, 7 stakeholders in buying committee]
Primary Conversion Events: [e.g., demo request (primary), free security assessment download (secondary)]

Site Architecture:
- Domain: [yourdomain.com]
- Total indexed pages (Google): [number]
- Total crawlable pages on site: [number]
- Blog/content section URL pattern: [e.g., /blog/, /resources/]
- Product/solution pages URL pattern: [e.g., /solutions/, /platform/]
- Competitor domains: [list top 3-5]

Traffic & Conversion Baseline:
- Monthly organic sessions: [number]
- Organic session-to-MQL rate: [e.g., 1.8%]
- MQL-to-SQL rate: [e.g., 22%]
- SQL-to-close rate: [e.g., 28%]
- Average contract value (ACV): [e.g., $48,000]
- Pipeline influenced by organic last 90 days: [$amount]

Technical Data Input (paste all that's available):
**Google Search Console (last 90 days):**
[Paste: top 20 queries by impressions, top 20 pages by clicks, CWV assessment status, pages excluded from index with reason]

**Crawl Report Summary (from Screaming Frog / Ahrefs / Semrush):**
[Paste: broken links count, redirect chains, pages with missing H1, duplicate title tags, duplicate meta descriptions, thin content pages (<300 words), orphaned pages, pages blocked by robots.txt, hreflang errors if international]

**Backlink Profile (from Ahrefs / Moz / Semrush):**
[Paste: domain authority/DR, total referring domains, top 5 link-earning pages, top 3 competitors' DR and referring domain counts, estimated backlink gap]

**Page Speed / Core Web Vitals:**
[Paste: LCP, FID/INP, CLS scores — mobile and desktop — from PageSpeed Insights or CrWD data]

**Keyword Rank Data:**
[Paste: top 30 ranking keywords with current position, prior period position, search volume, and keyword difficulty]

# OBJECTIVE
Conduct a comprehensive technical SEO revenue impact audit that (1) quantifies the revenue currently suppressed by technical debt, (2) prioritizes remediation by pipeline ROI per engineering hour, and (3) produces an actionable roadmap that any technical SEO or engineering team can execute directly.

# ANALYTICAL FRAMEWORKS TO APPLY

1. **TECHNICAL DEBT REVENUE MODEL**
For each critical technical issue category, apply:
Revenue Suppressed = (Affected Pages × Avg Organic Sessions/Page/Month) × Organic CVR × MQL→SQL Rate × SQL→Close Rate × ACV
Express as: current suppressed pipeline per month + 12-month cumulative opportunity.

2. **CRAWL EFFICIENCY SCORING**
Evaluate: (Pages Google Crawls Regularly / Total Important Pages) × 100. Score interpretation:
- 90-100%: Healthy — Google discovers content efficiently
- 70-89%: Moderate risk — crawl budget leakage likely
- <70%: Critical — significant content not being discovered or indexed

3. **CTR OPPORTUNITY MATRIX**
For keywords ranking positions 4-20 with >200 monthly impressions: calculate estimated traffic uplift from improving to position 1-3 using industry CTR curves (Pos 1: ~28%, Pos 2: ~15%, Pos 3: ~10%, Pos 4-7: 5-8%). Map to pipeline value.

4. **KEYWORD CANNIBALIZATION DETECTION**
Group all ranking keywords by semantic intent. Flag groups where 2+ pages rank for similar queries within 5 positions of each other. Score cannibalization severity: High (both pages ranked 1-10), Medium (one ranked 1-10, one 11-30), Low (both ranked 11-30+).

5. **CORE WEB VITALS REVENUE CORRELATION**
Apply Google's documented benchmarks: each 100ms LCP improvement = ~1% CVR lift. Each 0.1 CLS improvement = ~3% bounce rate reduction. Model current vs. "Good" threshold delta as estimated CVR improvement × organic traffic × pipeline value.

6. **BACKLINK VELOCITY GAP ANALYSIS**
Compare your domain's referring domain acquisition rate (last 6 months) vs. top 3 competitors. Calculate: months to close gap at current velocity vs. accelerated link-building pace. Map organic traffic ceiling imposed by current DA/DR vs. target authority for top 10 rankings in primary keyword cluster.

7. **REMEDIATION ROI PRIORITIZATION**
Score each fix: (Estimated Pipeline Recovered per Month) / (Engineering Hours to Fix). Rank by highest ROI ratio. Group into: Quick Wins (<4 hours, immediate impact), Sprint Work (1-2 week implementation), Structural Changes (requires architecture decisions).

# OUTPUT REQUIREMENTS

## Section 1: Executive Technical Health Scorecard
Produce a dashboard-ready table:
| Category | Score (/25) | Grade | Top Issue | Est. Monthly Revenue at Risk |
|---|---|---|---|---|
| Crawlability | | | | |
| Page Experience (CWV) | | | | |
| On-Page Signal Quality | | | | |
| Index Hygiene | | | | |
| **TOTAL** | **/100** | | | |

## Section 2: Revenue-At-Risk Breakdown
For each issue category, produce:
- Issue description (technical detail)
- Affected pages / URLs
- Revenue suppression estimate (monthly + 12-month cumulative)
- Confidence level: High / Medium / Low (based on data quality provided)
- Fix complexity: Simple (no-dev) / Engineering (1-5 hours) / Architecture (sprint-level)

## Section 3: Top 10 Quick Win Opportunities
For each opportunity:
- Page URL + Target Keyword
- Current Position → Target Position (30-day realistic)
- Current Monthly Traffic → Target Monthly Traffic
- Estimated Monthly Pipeline Uplift
- Specific action: [e.g., "Rewrite title tag to include 'software' modifier and move primary keyword to front"]

## Section 4: Cannibalization Map & Consolidation Recommendations
- Table of cannibalizing page pairs with severity rating
- Recommended resolution per pair: Canonical, 301 redirect, noindex, or content differentiation
- Estimated ranking improvement from consolidation

## Section 5: Core Web Vitals Pipeline Impact Model
- Current CWV scores vs. "Good" thresholds
- Estimated CVR improvement from reaching "Good" status
- Monthly pipeline uplift calculation
- Top 3 specific LCP/CLS/INP fixes with implementation guidance

## Section 6: 90-Day Technical SEO Sprint Roadmap
Format as sprint-ready tickets:

**SPRINT 1 (Days 1-14): Critical Revenue Recovery**
- Ticket 1: [Title] | Priority: P0 | Est. Hours: X | Pipeline Recovery: $X/mo
  - Description: [Jira-ready task description with technical specifics]
  - Acceptance Criteria: [Measurable definition of done]

**SPRINT 2 (Days 15-45): High-Value Optimization**
[Same format]

**SPRINT 3 (Days 46-90): Structural Improvements**
[Same format]

## Section 7: 6-Month Organic Revenue Forecast
Model two scenarios:
- **Status Quo:** Current organic pipeline trajectory assuming no changes
- **Remediation Complete:** Projected organic pipeline after full 90-day roadmap execution
Present as monthly pipeline table + cumulative 6-month delta

# CONSTRAINTS
- All revenue estimates must show calculation methodology — no unexplained numbers
- Flag data gaps explicitly: if input data is missing, state what assumption was made
- Prioritize by revenue impact, not by technical "correctness" — fixes that don't affect ranking or conversion are deprioritized
- Every recommendation must be immediately actionable — no vague "improve your content" suggestions
- Where competitors outrank on high-value keywords, explain the specific technical or authority gap, not generic advice

## Example Input/Output

**Input Example:**

Company: Vaultify Security — AI-powered cloud data security platform for enterprises
ICP: CISOs and VP Security at 1,000-10,000 employee companies in finance and healthcare
Monthly organic sessions: 28,400
Organic MQL rate: 2.3%
MQL-to-SQL: 19%, SQL-to-close: 31%, ACV: $72,000

Search Console shows: 847 pages indexed (site has ~1,200 crawlable pages), top query "cloud data security" getting 4,200 impressions/month at position 8.4 with only 2.1% CTR. CWV: LCP 4.2s (Poor), CLS 0.18 (Needs Improvement), INP 310ms (Needs Improvement).

Crawl issues: 134 broken internal links, 67 pages with duplicate title tags, 312 thin content pages, 18 redirect chains (3+ hops), 47 orphaned pages with no internal links.

Top competitor ahrefs.com [competitor domain] has DR 78 vs our DR 52 with 3,400 referring domains vs our 890.

---

**Output Example (excerpt):**

**Technical Health Scorecard:**
| Category | Score | Grade | Top Issue | Monthly Revenue at Risk |
|---|---|---|---|---|
| Crawlability | 14/25 | C | 312 thin pages consuming crawl budget | $31,400/mo |
| Page Experience | 11/25 | D | LCP 4.2s (target: <2.5s) on product pages | $18,700/mo |
| On-Page Signals | 18/25 | B | 67 duplicate title tags splitting equity | $9,200/mo |
| Index Hygiene | 16/25 | C | 353 pages indexed vs. 847 priority pages | $14,600/mo |
| **TOTAL** | **59/100** | **C** | | **$73,900/mo** |

**Top Quick Win — "cloud data security" (4,200 impressions, pos 8.4):**
Current: Position 8.4 → Target: Position 3 (30-day estimate)
Current monthly traffic: ~88 sessions → Target: ~420 sessions
Pipeline uplift: +332 sessions × 2.3% MQL rate × 19% SQL × 31% close × $72,000 ACV = **+$3,380/month**
Action: Title tag currently reads "Data Security Solutions | Vaultify" — rewrite to "Cloud Data Security Platform for Enterprise | Vaultify" and add FAQ schema targeting "what is cloud data security" (ranks #1 in PAA box for this query with 1,400 monthly searches).

**LCP Revenue Model:**
Current LCP: 4.2s → Target: 2.4s (Good threshold)
Google benchmark: every 1s LCP improvement = ~1.3% CVR lift
Expected improvement: 1.8s × 1.3% = 2.34% CVR lift
Monthly organic sessions × 2.34% CVR lift = +665 additional MQLs/year
Pipeline impact: 665 × 19% SQL × 31% close × $72,000 = **+$281,000 incremental pipeline annually**

## Success Metrics

- Technical health score improves from baseline by ≥15 points within 90 days
- Organic sessions increase ≥20% within 120 days of sprint completion
- Organic-influenced pipeline grows ≥30% within 6 months
- Critical issues (P0/P1) fully remediated within 30 days
- CWV "Good" status achieved on ≥80% of top 50 organic landing pages
- Keyword cannibalization reduced by ≥60% of identified pairs

## Related Prompts

- [AI-Powered B2B Content Cluster Performance Analytics & Topic Authority Revenue Attribution Intelligence Engine](./AI-Powered-B2B-Content-Cluster-Performance-Analytics-&-Topic-Authority-Revenue-Attribution-Intelligence-Engine.md)
- [Content Audit & SEO Refresh Intelligence Engine](../../03_Content-&-Creative/Blog-&-Article-Writing/Content-Audit-&-SEO-Refresh-Intelligence-Engine.md)
- [Programmatic SEO Content Factory](../../03_Content-&-Creative/Blog-&-Article-Writing/Programmatic-SEO-Content-Factory.md)
- [Programmatic SEO Topical Authority Engine](../../04_Demand-&-Lead-Generation-&-Growth/Inbound-Marketing/Programmatic-SEO-Topical-Authority-Engine.md)

## Integration Tips

- **Google Search Console API:** Automate data extraction with GSC API → push to BigQuery or Google Sheets. Feed output directly into the Advanced Version's "Keyword Rank Data" section on a weekly cadence. Use Zapier or Make to trigger this prompt when weekly impressions drop >10% week-over-week.
- **Screaming Frog + AI:** Schedule automated weekly crawls via Screaming Frog CLI, export CSV to Google Drive, then pipe into this prompt via a Python script using the Anthropic Claude API for weekly health score tracking.
- **HubSpot CRM Attribution:** Export HubSpot "original source = organic search" contacts from last 90 days with deal amounts. Use this as your "pipeline influenced by organic" input for the revenue model — far more accurate than GA4 last-touch.
- **Ahrefs / Semrush API:** Pull weekly backlink data and rank tracking via API, auto-populate the Advanced Version context block. Set up Slack alerts when a tracked keyword drops >3 positions and auto-trigger this prompt for diagnosis.
- **Jira Integration:** Copy Section 6 sprint tickets directly into Jira as epics and stories. Use Claude to auto-generate acceptance criteria if you paste the ticket descriptions back in: "Convert these SEO remediation tasks into Jira user stories with technical acceptance criteria."
- **Looker Studio / Google Data Studio:** Build a live SEO Revenue Dashboard pulling from GSC + GA4 + HubSpot. Use this prompt monthly to generate the narrative layer on top of the data visualization — the "so what" behind the charts.

## Troubleshooting

**Problem:** "I don't have crawl data from a paid tool like Ahrefs or Screaming Frog."
**Solution:** Use free alternatives: (1) Google Search Console → Coverage report exports all indexation issues; (2) Sitebulb free trial (2-week) for a one-time full crawl; (3) browser extension "Detailed SEO Extension" for page-level on-page signals. The Quick Copy-Paste version works with Search Console data alone — just mark the crawl section as "N/A — using GSC only."

**Problem:** "Revenue estimates seem too high / the pipeline math doesn't match our actual performance."
**Solution:** Override the default MQL-to-pipeline math with your actual funnel rates. The default formula uses industry benchmarks; your rates may differ significantly by segment or deal type. For enterprise deals with long sales cycles, use 6-month lagged attribution: pipeline influenced today won't close for months, so multiply by a 0.4-0.6 discount factor for realistic near-term projections.

**Problem:** "The AI gives generic recommendations like 'improve page speed' without specific technical fixes."
**Solution:** Paste your actual PageSpeed Insights JSON output (available via the PSI API) rather than just scores. Specific JSON data containing resource load times, render-blocking elements, and unused JavaScript enables the model to output precise technical fixes (e.g., "defer loading of HubSpot tracking script — currently blocking render by 1.8s on mobile").

## Version History
- v1.0: Initial creation (auto-generated)
