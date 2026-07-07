# AI-Powered B2B SaaS Technical SEO Performance Analytics & Core Web Vitals Revenue Attribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** technical-seo, core-web-vitals, crawl-analytics, indexation, page-experience, seo-revenue-attribution, b2b-saas, organic-search

## Overview
Audits technical SEO health signals — crawlability, indexation, Core Web Vitals, structured data, and page experience — and translates them directly into revenue impact estimates, prioritizing fixes by pipeline opportunity rather than engineering effort. Use this when organic traffic is declining without obvious content cause, when Google Search Console surfaces crawl or coverage errors, or when you need to build a business case for a technical SEO engineering sprint.

## Quick Copy-Paste Version

You are a B2B SaaS technical SEO revenue analytics expert. Analyze the following technical SEO data and produce a complete diagnostic with revenue impact attribution and a prioritized remediation roadmap.

TECHNICAL SEO AUDIT DATA:
- GSC Coverage Report (paste: valid pages, excluded pages, error types, counts): [paste data]
- Core Web Vitals (LCP, INP, CLS — mobile and desktop, % pages Poor/Needs Improvement/Good): [paste data]
- Crawl budget data (total pages crawled/day, crawl errors, disallowed paths): [paste data]
- Structured data errors and warnings from GSC Rich Results report: [paste data]
- Site speed (TTFB, FCP, page weight) for top 10 organic landing pages: [paste data]

BUSINESS CONTEXT:
- Monthly organic sessions: [X]
- Organic pipeline contribution (last 90 days): $[X]
- Top 10 organic landing pages by pipeline value: [list URLs + pipeline $]
- Average ACV: $[X]
- MQL-to-pipeline conversion rate: [X]%

ANALYSIS REQUIRED:
1. Estimate the monthly pipeline leakage caused by each technical issue category (indexation gaps, Core Web Vitals failures, crawl errors) — show the math
2. Rank remediation items by pipeline recovery potential per engineering hour, not by SEO severity score alone
3. Flag any pages currently excluded from the index that should be generating pipeline — these are your highest-urgency fixes
4. Identify Core Web Vitals failures on high-pipeline pages and quantify the CTR uplift available from passing the Page Experience signal
5. Surface structured data opportunities on BOFU pages (FAQ, HowTo, Product, Review) that could capture SERP features
6. Build a 30/60/90-day technical SEO sprint plan with specific tickets, expected pipeline impact, and success metrics for engineering handoff

Output as: Executive Summary (Revenue Impact Score), Issue Registry Table (sorted by pipeline impact), 30/60/90-Day Sprint Plan, and Engineering Ticket Templates.

## Advanced Customizable Version

ROLE: You are a senior technical SEO and revenue analytics strategist with 14+ years of experience at B2B SaaS companies. You specialize in translating Core Web Vitals, crawl efficiency, indexation architecture, and structured data into CFO-ready business cases. You think in pipeline dollars, not keyword rankings.

CONTEXT:
Company: [Company name]
Product category: [e.g., "Customer Data Platform for B2B SaaS"]
CRM & attribution: [HubSpot/Salesforce + attribution model]
Primary ICP: [e.g., "VP of Marketing at 200-2000 employee B2B SaaS"]
Average ACV: $[X,XXX]
MQL-to-SQL rate: [X]%
SQL-to-close rate: [X]%
Monthly organic sessions (last 90 days average): [X]
Organic-sourced pipeline (last 90 days): $[X]
Total indexed pages: [X]
CMS/Tech stack: [WordPress / Webflow / Next.js / Contentful / etc.]
CDN: [Cloudflare / Fastly / AWS CloudFront / none]
Primary SEO platform: [Ahrefs / Semrush / Screaming Frog / Sitebulb]

TECHNICAL SEO DATA INPUTS:

**1. Google Search Console — Coverage Report (last 30 days):**
Valid (indexed): [X pages]
Valid with warnings: [X pages — list top warning types]
Excluded: [X pages — breakdown: Crawled but not indexed: X | Discovered but not crawled: X | Excluded by noindex: X | Redirect: X | 404: X | Canonical (non-selected): X]
Errors: [X pages — breakdown: Server error 5xx: X | Redirect error: X | Not found 404: X | Blocked by robots.txt: X]

**2. Core Web Vitals (CrUX data — last 28 days, mobile + desktop):**
LCP (Largest Contentful Paint):
  - Mobile: Good [X]% | Needs Improvement [X]% | Poor [X]%
  - Desktop: Good [X]% | Needs Improvement [X]% | Poor [X]%
INP (Interaction to Next Paint):
  - Mobile: Good [X]% | Needs Improvement [X]% | Poor [X]%
  - Desktop: Good [X]% | Needs Improvement [X]% | Poor [X]%
CLS (Cumulative Layout Shift):
  - Mobile: Good [X]% | Needs Improvement [X]% | Poor [X]%
  - Desktop: Good [X]% | Needs Improvement [X]% | Poor [X]%
Overall Page Experience status: [Failing / Passing]

**3. Top 20 Organic Landing Pages — Technical Snapshot:**
[URL] | [Monthly Sessions] | [Pipeline Attributed $] | [LCP ms] | [INP ms] | [CLS score] | [TTFB ms] | [Page Size KB] | [Indexed Y/N] | [Structured Data Present Y/N] | [Canonical Status]

**4. Crawl Efficiency Data:**
Daily crawl budget (Googlebot): [X pages/day]
Pages crawled but not indexed (last 30 days): [X]
Identified crawl waste sources: [parameter URLs / pagination / faceted nav / low-value thin pages / etc.]
Robots.txt blocks: [list key disallowed paths]
XML sitemap status: [URL, last crawled date, submitted vs. indexed count]

**5. Structured Data Audit:**
Schema types deployed: [Article / FAQ / Product / Review / BreadcrumbList / Organization / SoftwareApplication]
GSC Rich Results errors: [paste error summary]
SERP features currently winning (from SEO platform): [Featured Snippet X keywords | FAQ X keywords | Sitelinks X]
SERP feature opportunities identified: [paste from SEO tool]

**6. Competitor Technical Benchmarks (optional):**
Competitor 1: [name] — estimated indexed pages: [X] | Page Experience status: [Pass/Fail] | Core Web Vitals: [LCP / INP / CLS scores]
Competitor 2: [name] — [same]

OBJECTIVE:
Produce a technical SEO performance intelligence report that:
(a) Quantifies the revenue impact of each technical debt category
(b) Prioritizes all remediation work by pipeline-per-engineering-hour
(c) Gives the CMO a boardroom-ready business case
(d) Gives the engineering team ready-to-execute sprint tickets

DELIVERABLES:

**1. TECHNICAL SEO REVENUE IMPACT SCORECARD**
- Total estimated monthly pipeline leakage from technical issues: $[X]
- Breakdown by issue category with revenue math shown:
  * Indexation gaps: [X pages that should be indexed × average sessions/indexed page × organic conversion rate × MQL-to-pipeline rate × ACV] = $[X] monthly opportunity
  * Core Web Vitals failures: [% of pipeline pages failing × estimated CTR uplift from Page Experience improvement (benchmark: 5-12% CTR increase) × current pipeline] = $[X] monthly opportunity
  * Crawl waste (budget inefficiency): [estimated % of crawl budget wasted × crawl budget × compounding indexation delay cost] = $[X] annualized opportunity
  * Structured data gaps: [BOFU pages without FAQ/Product schema × estimated CTR uplift from rich results × pipeline value per page] = $[X] monthly opportunity
- Technical SEO Health Score (0-100): [score with methodology]
- Urgency rating: Critical / High / Medium / Low

**2. ISSUE REGISTRY — SORTED BY PIPELINE IMPACT**
Issue | Type | Affected Pages | Pipeline Impact ($/month) | Fix Effort (eng hours) | ROI ($/hour) | Priority | Owner | Deadline
[Row per issue, sorted descending by ROI]

**3. CORE WEB VITALS DEEP DIVE**
For each failing metric on top-10 pipeline pages:
- Root cause diagnosis (image optimization / render-blocking JS / layout shift culprit / slow server response)
- Specific fix with implementation detail (e.g., "Convert hero images on /pricing and /demo to WebP, implement lazy loading, add explicit width/height attributes to eliminate CLS 0.18 score")
- Expected metric improvement after fix
- Estimated CTR uplift and resulting pipeline impact
- Engineering ticket template (title, description, acceptance criteria, estimated story points)

**4. INDEXATION ARCHITECTURE ANALYSIS**
- Canonical strategy audit: are canonical tags correctly configured on product tour pages, blog pagination, and UTM-parameter variants?
- Crawl waste elimination plan: which URLs should be added to robots.txt disallow, noindex, or consolidated?
- Priority pages incorrectly excluded: [list with specific reason and fix]
- Sitemap optimization: does the sitemap include all pipeline pages and exclude all non-indexable pages?
- Internal linking gaps: which high-pipeline pages have fewer than [X] internal links pointing to them?

**5. STRUCTURED DATA REVENUE PLAYBOOK**
For each BOFU/MOFU page cluster:
- Schema type to implement
- Expected SERP feature: FAQ accordion / Sitelinks searchbox / Product rich result / Review stars
- JSON-LD code template ready to deploy (complete, valid structured data)
- Estimated CTR uplift (% based on Sistrix/industry benchmarks for that schema type)
- Pages to prioritize: [list]

**6. 30/60/90-DAY TECHNICAL SEO SPRINT PLAN**
Days 1-30 (Critical Pipeline Recovery):
- [Specific action] → Owner: [Eng/SEO] → Pipeline impact: $[X] → Completion criteria: [measurable]
[2-3 actions max — highest ROI only]

Days 31-60 (Performance & Authority):
- [Specific action] → Owner → Pipeline impact → Completion criteria
[3-4 actions]

Days 61-90 (Scale & Compound):
- [Specific action] → Owner → Pipeline impact → Completion criteria
[3-4 actions]

Total projected pipeline recovery over 90 days: $[X]
Investment required (engineering hours + SEO tool costs): $[X]
Technical SEO program ROI: [X]x

**7. EXECUTIVE SUMMARY FOR CMO/CFO**
- One-paragraph technical debt narrative in revenue language (no jargon)
- Current technical SEO health vs. top competitor
- 3 investment recommendations with ROI: [Quick Win | Strategic Investment | Defensive Fix]
- What happens if we do nothing: 6-month traffic and pipeline projection under status quo

## Example Input/Output

**Company:** Momentum Analytics — B2B SaaS revenue intelligence platform, $1.8M ACV, 400-employee company

**Sample Input Data:**
- Total indexed pages: 847 | Pages excluded (crawled not indexed): 312 | 404 errors: 67
- Mobile Core Web Vitals: LCP Poor 43% | INP Needs Improvement 38% | CLS Good 91%
- Monthly organic sessions: 28,400 | Organic pipeline last 90 days: $4.2M
- Top pipeline page `/revenue-intelligence-platform` (position 3.1, 6,200 sessions, $890K pipeline): LCP 4.8s, INP 380ms
- Structured data: BreadcrumbList only; no FAQ schema on /pricing, /demo, or comparison pages
- Competitor Clari.com: Page Experience PASSING, LCP 1.9s average

**Sample Output Excerpt:**

**Revenue Impact Scorecard:**
- Total monthly pipeline leakage from technical issues: **$387,000/month** ($4.6M annualized)
- Indexation gaps: 312 excluded pages × est. 28 sessions/page/month × 3.2% MQL rate × 18% pipeline conversion × $1,800 ACV = **$89,000/month**
- Core Web Vitals failures: 43% of pipeline pages failing LCP × 8% estimated CTR uplift × $4,200K/quarter pipeline = **$183,000/month opportunity**
- Structured data gaps on BOFU pages: 12 pages without FAQ schema × 14% average CTR uplift from FAQ rich result × $8,400 pipeline/page/month = **$115,000/month**

**Top Priority Fix (Sprint Day 1-14):**
Fix `/revenue-intelligence-platform` LCP from 4.8s → target <2.5s
Root cause: 2.3MB unoptimized hero image, no server push for critical CSS
Fix: Convert hero to AVIF (420KB), implement `fetchpriority="high"` on LCP image, defer non-critical JS
Estimated LCP improvement: 4.8s → 2.1s
CTR uplift: +9% (from SERP position 3 — Google Page Experience ranking boost + user behavior)
Monthly pipeline impact: +$80,000
Engineering effort: 6 hours
ROI: $13,333 per engineering hour

**FAQ Schema Deployment for /pricing:**
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "How long does implementation take?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Most customers are fully deployed within 14 days using our pre-built CRM connectors."
      }
    },
    {
      "@type": "Question",
      "name": "Does Momentum Analytics work with HubSpot?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes — native bidirectional sync with HubSpot, Salesforce, and 47 other CRM and MAT platforms."
      }
    }
  ]
}
Expected result: FAQ rich result in 3-6 weeks, +11% CTR on /pricing, +$43,000/month pipeline.

## Success Metrics

**Technical Health Indicators:**
- Core Web Vitals: ≥75% of pages achieve "Good" status on LCP, INP, and CLS within 90 days
- Indexation efficiency: <5% of indexable pages excluded from index within 60 days
- Crawl waste: Crawl budget utilization on pipeline-driving pages >80% (reduce wasted crawls on thin/duplicate pages)
- Structured data: Zero GSC Rich Results errors; rich results appearing on ≥90% of target BOFU pages

**Revenue Attribution Indicators:**
- Organic pipeline recovery rate: ≥80% of projected pipeline impact realized within 90 days of fixes deploying
- Organic CTR improvement: ≥5% average CTR lift on pages receiving Core Web Vitals fixes
- Pipeline pages indexed: 100% of pages generating >$10K/month pipeline have "Valid" indexation status

**Report Quality Check:**
- Every recommendation has a specific dollar amount, engineering hour estimate, and named owner
- CMO can present revenue impact to CFO without additional translation
- Engineering team receives tickets requiring zero clarification to implement

## Related Prompts

- [`05_Analytics-&-Performance/Organic-Search-Analytics/AI-Powered-B2B-SaaS-Organic-Search-Performance-Analytics-&-SEO-Revenue-Attribution-Intelligence-Engine.md`](./AI-Powered-B2B-SaaS-Organic-Search-Performance-Analytics-&-SEO-Revenue-Attribution-Intelligence-Engine.md) — Companion prompt for keyword cluster and content performance analytics
- [`04_Demand-&-Lead-Generation-&-Growth/SEO-&-Organic-Demand-Generation/AI-Powered-B2B-SaaS-Technical-SEO-Audit-&-Organic-Performance-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/SEO-&-Organic-Demand-Generation/AI-Powered-B2B-SaaS-Technical-SEO-Audit-&-Organic-Performance-Intelligence-Engine.md) — Demand generation focused technical SEO audit
- [`05_Analytics-&-Performance/GEO-&-AI-Search-Analytics/AI-Powered-GEO-Performance-Analytics-&-AI-Search-Share-of-Voice-Intelligence-Engine.md`](../GEO-&-AI-Search-Analytics/AI-Powered-GEO-Performance-Analytics-&-AI-Search-Share-of-Voice-Intelligence-Engine.md) — Companion analytics for AI search and GEO performance
- [`05_Analytics-&-Performance/Conversion-Rate-Optimization-Analytics/AI-Powered-B2B-SaaS-CRO-Analytics-&-Experimentation-Intelligence-Engine.md`](../Conversion-Rate-Optimization-Analytics/AI-Powered-B2B-SaaS-CRO-Analytics-&-Experimentation-Intelligence-Engine.md) — Conversion optimization analytics to pair with technical SEO improvements

## Integration Tips

**Google Search Console + Looker Studio:**
Pull GSC Coverage, Core Web Vitals, and Search Analytics data into Looker Studio. Blend with HubSpot/Salesforce pipeline data using session source/medium = organic. Build a live "Technical SEO Revenue Dashboard" refreshing daily. Use the output from this prompt as the analytical layer on top of that dashboard.

**Screaming Frog + Ahrefs + GSC Workflow:**
1. Run Screaming Frog crawl (export: all URLs, status codes, response times, canonical, noindex, structured data)
2. Export GSC Coverage report and Core Web Vitals report as CSVs
3. Pull Ahrefs Top Pages by organic traffic and estimated value
4. Paste consolidated data into this prompt for the revenue impact calculation

**HubSpot Revenue Attribution:**
In HubSpot, filter contacts by Original Source = Organic Search, then segment by First Page Seen. Export: URL, contact count, associated deal value. This gives you pipeline attribution by landing page to populate the "Top 20 Organic Landing Pages" input.

**Zapier / Make Automation:**
Trigger: Weekly GSC data pull via API → Format as structured table → Pass to Claude API with this prompt → Output to Notion database or Google Sheet → Slack notification to SEO team with the top 3 revenue-impacting issues.

**PageSpeed Insights API:**
Automate CWV data collection for top 50 pipeline pages using the PageSpeed Insights API (free). Schedule weekly. Feed outputs directly into the Core Web Vitals section of this prompt to track improvement over time without manual GSC exports.

## Troubleshooting

**"The pipeline attribution numbers feel unreliable because we use last-touch attribution"**
This is expected — last-touch systematically undervalues organic. In the Advanced version, explicitly specify your attribution model and ask the prompt to calculate both last-touch AND position-based attribution estimates. Present the range. Also ask it to generate a "self-reported attribution" analysis: survey your last 20 closed-won customers about where they first heard of you. This triangulation makes the organic case much stronger to a skeptical CFO.

**"Our Core Web Vitals show Good in GSC but the site still feels slow"**
GSC reports CrUX (Chrome User Experience Report) field data — real user measurements aggregated over 28 days. If you recently deployed fixes, the data lags by up to 28 days. Use PageSpeed Insights Lab data for immediate feedback. Also check if your CrUX data pool is large enough (GSC requires a minimum threshold of users) — low-traffic pages may not have CrUX data at all. Use Lighthouse in the prompt's "site speed" data input section instead.

**"We have 3,000+ pages and the crawl data is overwhelming"**
Segment the analysis. Run the prompt three times with filtered data: (1) BOFU pages only (pricing, demo, comparison, use case pages), (2) MOFU pages (blog posts with >$5K pipeline attributed), (3) TOFU pages. Prioritize fixes in that order. Do not try to fix all 3,000+ pages at once — the prompt is designed to surface the 20% of fixes that drive 80% of revenue recovery.

## Version History
- v1.0: Initial creation (auto-generated)
