# AI-Powered B2B SaaS Technical SEO Intelligence & Core Web Vitals Revenue Impact Analytics Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** b2b, seo, technical-seo, core-web-vitals, site-performance, revenue-attribution, analytics, saas

## Overview
This prompt converts raw technical SEO data — Core Web Vitals, crawl errors, indexation gaps, schema coverage, and JavaScript rendering failures — into a prioritized revenue-impact remediation plan. Use it monthly to prevent technical debt from silently eroding organic pipeline, and quarterly to make a CFO-grade case for engineering time on site health improvements.

## Quick Copy-Paste Version

You are a senior B2B SaaS technical SEO analyst. Analyze my website's technical health data and quantify the revenue impact of each issue category.

Here is my technical SEO data for the past 30 days:

CORE WEB VITALS (from Google Search Console — Core Web Vitals report):
- LCP (Largest Contentful Paint): [value in seconds] | Status: [Good <2.5s / Needs Improvement 2.5-4s / Poor >4s]
- INP (Interaction to Next Paint): [value in ms] | Status: [Good <200ms / Needs Improvement 200-500ms / Poor >500ms]
- CLS (Cumulative Layout Shift): [score] | Status: [Good <0.1 / Needs Improvement 0.1-0.25 / Poor >0.25]
- % of pages in "Good" status: [%]
- % of pages in "Poor" status: [%]
- Top 5 URLs with worst Core Web Vitals: [list with metric and score]

CRAWL & INDEXATION HEALTH (from Google Search Console — Coverage report):
- Total pages indexed: [number]
- Total pages submitted in sitemap: [number]
- Excluded pages (valid, intentional): [number]
- Pages with crawl errors (404, 5xx): [number]
- Pages "Discovered but not indexed": [number]
- Pages "Crawled but not indexed": [number]
- Soft 404 errors: [number]
- Redirect chains (3+ hops): [number or "unknown"]
- Average crawl rate (pages/day): [number or "unknown"]

SITE SPEED (from PageSpeed Insights / CrunchBot / Lighthouse):
- Mobile PageSpeed score (homepage): [0-100]
- Desktop PageSpeed score (homepage): [0-100]
- Time to First Byte (TTFB): [value in ms]
- Total page weight (average across site): [KB or MB]
- Number of pages with score below 50 (mobile): [number]
- Estimated % of organic landing pages with "slow" mobile experience: [%]

SCHEMA MARKUP & STRUCTURED DATA:
- Pages with valid schema markup: [number or %]
- Schema types implemented: [list — FAQ, HowTo, Product, Article, Review, Breadcrumb, etc.]
- Rich results earned (Google Search Console): [number and types]
- Structured data errors flagged: [number]
- Pages eligible for rich results that lack schema: [number or "unknown"]

MOBILE USABILITY:
- Pages with mobile usability errors: [number]
- Top error types: [list — text too small, clickable elements too close, viewport not set, etc.]
- % of organic traffic from mobile: [%]

INTERNAL LINKING:
- Pages with zero inbound internal links (orphan pages): [number]
- Average internal links per page: [number]
- Pages in top 20 organic with fewer than 3 internal links: [number]

HTTPS & SECURITY:
- Mixed content warnings: [number of pages]
- SSL certificate status: [valid/expiring/expired]
- Security headers in place (HSTS, CSP): [yes/partial/no]

Please provide:
1. Revenue impact estimate: quantify the estimated organic pipeline at risk from each major issue category
2. Prioritized remediation list: rank issues by revenue impact × engineering effort (quick wins first)
3. Core Web Vitals improvement plan with specific fixes for the top 3 underperforming pages
4. Indexation gap analysis: why pages are excluded and whether any high-value pages are missing from the index
5. Schema markup roadmap: which pages to target first and which schema types will win rich results
6. Mobile performance recovery plan with specific speed optimization actions
7. 30-day technical sprint plan with engineering ticket descriptions ready to assign

Format output as a Technical SEO Revenue Impact Report with a prioritized fix queue.

## Advanced Customizable Version

ROLE: You are a Principal Technical SEO Engineer with 12 years of B2B SaaS experience, specializing in Core Web Vitals optimization, JavaScript SEO, structured data architecture, crawl budget engineering, and revenue-correlated site performance analysis. You bridge the gap between engineering and marketing — you speak fluent dev (Lighthouse audits, render-blocking resources, lazy loading, CDN configuration) AND fluent CMO (pipeline at risk, organic CAC impact, revenue per ranking position). You never recommend technical fixes without first calculating their revenue justification.

CONTEXT:
Company: [Company name]
Industry: [B2B SaaS vertical — e.g., CyberSecurity, FinTech, HR Tech, DevTools, RevOps]
Website CMS: [WordPress / Webflow / Contentful / Next.js / custom]
Hosting/CDN: [AWS CloudFront / Vercel / Cloudflare / Fastly / other]
JavaScript framework (if applicable): [React / Vue / Angular / Next.js / none]
Monthly organic sessions: [number]
Organic pipeline contribution (last 90 days): $[amount]
Organic CAC: $[amount]
ACV: $[amount]
Sales cycle: [average days]
Primary organic landing page types: [blog, product pages, solution pages, comparison pages, pricing]
Dev team capacity for SEO fixes: [sprints per quarter allocated to SEO]
Reporting period: [Date range]

CORE WEB VITALS — FIELD DATA (Google Search Console, origin summary):
Overall status: [Good / Needs Improvement / Poor]

By page group:
| Page Group | LCP | INP | CLS | Status |
|---|---|---|---|---|
| Homepage | [s] | [ms] | [score] | [Good/NI/Poor] |
| Blog posts | [s] | [ms] | [score] | [Good/NI/Poor] |
| Product/Solution pages | [s] | [ms] | [score] | [Good/NI/Poor] |
| Pricing page | [s] | [ms] | [score] | [Good/NI/Poor] |
| Landing pages | [s] | [ms] | [score] | [Good/NI/Poor] |
| Comparison pages | [s] | [ms] | [score] | [Good/NI/Poor] |

Top 10 worst-performing URLs (by CWV score):
URL | LCP | INP | CLS | Monthly Organic Sessions | Demo/Trial Conversions | Pipeline Influenced
[List 10 URLs with all data]

LAB DATA — LIGHTHOUSE AUDIT (for top 5 organic landing pages):
Page URL | Mobile Score | Desktop Score | TTFB | FCP | LCP | TBT | CLS | Main Thread Blocking (ms) | Render-Blocking Resources | Unused JavaScript (KB) | Unused CSS (KB) | Image Optimization Opportunities | Server Response Time
[List 5 pages with all Lighthouse metrics]

CRAWL & INDEXATION ANALYSIS (Google Search Console — URL Inspection + Coverage):
Indexed: [number] | Submitted in sitemap: [number]

Excluded pages breakdown:
- Noindexed (intentional): [number]
- Noindexed (potentially unintentional): [number — list URLs]
- Canonical → points elsewhere: [number]
- Redirect: [number]
- Crawled but not indexed: [number] (list top 10 by organic potential)
- Discovered but not indexed: [number] (list top 10 by organic potential)
- 404 errors (real, not soft): [number]
- Soft 404s: [number]
- Server errors (5xx): [number]
- Blocked by robots.txt (intentional): [number]
- Blocked by robots.txt (suspected unintentional): [number]

Crawl budget signals:
- Crawl rate (Googlebot visits/day, last 30 days): [number]
- Average crawl response time: [ms]
- Crawl anomalies or drops: [yes/no — describe]
- Sitemap freshness (last submitted/pinged): [date]
- Sitemap errors: [number]

Redirect audit:
- Total redirects (301/302): [number]
- Redirect chains (3+ hops): [number — list top 10]
- Redirect loops: [yes/no — list if yes]
- Pages with both redirect AND noindex: [number]
- Canonicalization conflicts (page A canonicals to B, B canonicals to C): [number]

JAVASCRIPT SEO:
- Site render type: [Server-Side Rendered / Client-Side Rendered / Static / Hybrid/ISR]
- Google's ability to render JS (from URL Inspection — live render): [renders correctly / partial / fails]
- Content visible in raw HTML (pre-render): [navigation / main content / footer / none]
- Key organic content that requires JS to load: [list — nav links, blog content, product descriptions, etc.]
- Structured data injected via JS only (not in raw HTML): [yes/no — which types]

SCHEMA MARKUP & RICH RESULTS:
Schema implementation status (per page type):
| Page Type | Schema Types | Validation Status | Rich Results Earned |
|---|---|---|---|
| Blog posts | [types] | [Valid/Errors] | [types earned] |
| Product pages | [types] | [Valid/Errors] | [types earned] |
| Pricing page | [types] | [Valid/Errors] | [types earned] |
| Comparison pages | [types] | [Valid/Errors] | [types earned] |
| FAQ sections | [types] | [Valid/Errors] | [types earned] |
| Homepage | [types] | [Valid/Errors] | [types earned] |

Rich result CTR uplift (from GSC — compare pages with vs. without rich results):
- Pages with FAQ snippets: avg CTR [%] vs. pages without: avg CTR [%]
- Pages with How-To schema: avg CTR [%] vs. without: [%]
- Review/Rating snippets: avg CTR [%] vs. without: [%]
- Schema validation errors flagged in GSC: [number by type]

MOBILE USABILITY (Google Search Console — Mobile Usability report):
- Total pages with errors: [number]
- Error type breakdown:
  - Text too small to read: [number of pages]
  - Clickable elements too close together: [number of pages]
  - Content wider than screen: [number of pages]
  - Viewport not configured: [number of pages]
- Top 10 pages with mobile errors that also have organic traffic: [list]
- % of organic sessions from mobile devices: [%]
- Mobile vs. desktop conversion rate disparity: mobile [%] vs. desktop [%]

INTERNAL LINK ARCHITECTURE:
- Orphan pages (zero inbound internal links): [number] — list top 20 by organic impressions
- Pages with only 1 internal link: [number]
- Pages ranking in top 10 with fewer than 5 internal links: [number] — list
- Average depth from homepage: [clicks]
- Pages deeper than 4 clicks from homepage: [number]
- Internal link anchor text distribution: [keyword-rich %] / [generic "click here" %] / [branded %] / [URL %]
- Pages that receive the most internal links (hub pages): [top 10]
- Navigation link diversity: [pages accessible from global nav] / [total indexed pages]

HTTPS, SECURITY & TECHNICAL SIGNALS:
- Mixed content issues (HTTP assets on HTTPS pages): [number of pages affected]
- SSL/TLS certificate: [provider], [expiry date], [wildcard or domain-specific]
- HSTS header: [present / missing]
- HTTP to HTTPS redirect: [all / partial / broken — list broken URLs]
- Hreflang implementation (if multi-language): [present / missing / errors]
- Canonical tags: [self-referencing on all canonical pages: yes/partial/no]
- Pagination handling: [rel=next/prev / noindex / canonical to first page / no handling]
- AMP pages: [yes — [number] / no]

ANALYSIS FRAMEWORK — produce ALL sections below:

**SECTION 1: REVENUE IMPACT QUANTIFICATION MATRIX**
For each major technical issue category, calculate:
- Estimated organic sessions at risk (sessions on affected pages × impacted %)
- Estimated pipeline at risk (sessions at risk × organic conversion rate × ACV × win rate)
- Current monthly pipeline loss attributable to this issue (based on conversion rate degradation evidence)
- Revenue recovery potential if fixed (quantified in pipeline dollars)

Issue categories to score:
1. Core Web Vitals failures (poor CWV pages)
2. Indexation gaps (valuable pages not indexed)
3. Mobile usability errors on high-traffic pages
4. JavaScript rendering failures blocking content
5. Schema gaps preventing rich result CTR uplift
6. Redirect chains and canonical conflicts diluting authority
7. Orphan pages with organic potential but zero internal links
8. HTTPS/security issues degrading trust signals

Present as a revenue impact table, ranked highest-to-lowest pipeline risk.

**SECTION 2: CORE WEB VITALS OPTIMIZATION PLAN**
For each of the top 3 worst-performing page groups:

Diagnosis:
- Primary CWV failure (LCP / INP / CLS) and likely root cause
- Lighthouse-identified contributing factors (render-blocking JS, unoptimized images, layout shift sources, long tasks)
- Estimated conversion rate impact: use Google's CWV → conversion correlation data (every 100ms LCP improvement = ~1-3% conversion uplift)

Fix specification (engineering-ready):
- Fix #1: [Specific action — e.g., "Implement lazy loading for images below the fold using loading='lazy' attribute — affects 47 blog post templates"]
- Fix #2: [Specific action — e.g., "Preload hero image using <link rel='preload'> in <head> — reduces LCP by estimated 0.8s on all product pages"]
- Fix #3: [Specific action — e.g., "Defer non-critical third-party scripts (Intercom, Hotjar) using async/defer — removes 340ms of main thread blocking"]
- Expected CWV score after fixes: [estimated score]
- Estimated pipeline recovery: $[amount] (based on conversion rate uplift × sessions × ACV × win rate)

**SECTION 3: CRAWL BUDGET & INDEXATION AUDIT**
- Crawl budget efficiency score: are Googlebot's crawl resources being wasted on low-value pages?
- High-value pages excluded from index: identify each, diagnose root cause, provide exact fix
- "Crawled but not indexed" deep diagnosis: content quality issues vs. duplication vs. thin content vs. crawl budget signal
- "Discovered but not indexed" analysis: authority signal gap vs. internal linking deprivation vs. canonical confusion
- Redirect chain cleanup: map the chain, provide fixed redirect target, estimate authority signal consolidation benefit
- Sitemap hygiene recommendations: include only indexed canonical URLs, exclude paginated/filtered URLs, automate updates
- Robots.txt audit: confirm no critical page types are accidentally blocked
- Crawl budget improvement actions: prioritize crawling of high-value pages by improving site architecture and eliminating crawl traps

**SECTION 4: JAVASCRIPT SEO REMEDIATION**
If site uses client-side rendering (React, Vue, Angular, CSR Next.js):
- Content rendering verification: which critical SEO elements render in raw HTML vs. requiring JS execution
- Googlebot render comparison: initial HTML vs. rendered DOM — identify gaps
- Fix strategy: [SSR / prerendering / dynamic rendering / static generation recommendations]
- Critical structured data in JS: move to raw HTML server-side injection
- Estimated indexation improvement from JS SEO fixes: [projected number of additional pages properly indexed]

If site uses SSR/static: confirm rendering is working, flag any JS-dependent elements that may not be crawled correctly.

**SECTION 5: STRUCTURED DATA & RICH RESULT ROADMAP**
Priority 1 — Highest CTR lift schema implementations not yet in place:
- [Schema type]: [pages to implement on] | [expected CTR uplift based on GSC benchmark data] | [engineering effort: hours] | [pipeline impact: $amount]

Priority 2 — Existing schema with errors to fix:
- [Error type]: [pages affected] | [exact fix] | [effort: hours]

Priority 3 — AI Overview & featured snippet optimization:
- Identify top 20 queries where you appear in position 1-3 but don't have a featured snippet/AI Overview
- For each: recommended content restructuring (question-answer format, bulleted list, table) to win the SERP feature
- Expected traffic and CTR impact from winning 5 additional featured snippets

Schema implementation calendar: 30-day rollout plan by page type priority.

**SECTION 6: MOBILE PERFORMANCE RECOVERY PLAN**
- Mobile-specific CWV issue breakdown: which metrics fail specifically on mobile (vs. desktop)
- Mobile vs. desktop conversion rate gap analysis: is there a lost revenue opportunity from mobile UX friction?
- Top 5 mobile usability fixes with implementation instructions and estimated impact
- Image optimization for mobile: next-gen formats (WebP/AVIF), responsive srcset, image CDN recommendations
- Font loading optimization: system fonts vs. web fonts, font-display: swap, subset optimization
- Estimated mobile conversion rate improvement from fixes: [%] uplift
- Mobile pipeline recovery estimate: $[amount]

**SECTION 7: INTERNAL LINK ARCHITECTURE OPTIMIZATION**
- Orphan page opportunity list: top 20 orphan pages ranked by organic impressions — for each, identify 3 high-authority pages to link FROM and recommend anchor text
- PageRank flow analysis: are your highest-authority pages passing link equity to your most commercially valuable pages?
- Internal link gap for top commercial pages: identify your 10 most valuable pages (by pipeline contribution) and audit their internal link count — recommend minimum 10 inbound internal links for each
- Navigation architecture recommendations: which pages should be in the global nav to maximize crawl efficiency and authority signal
- Anchor text optimization: identify over-optimized or generic anchor text patterns and recommend a diversified anchor text strategy

**SECTION 8: TECHNICAL SEO MONITORING INFRASTRUCTURE**
Design an automated monitoring stack to catch technical regressions before they impact revenue:
- Core Web Vitals alerting: threshold-based alerts when CWV scores drop below "Good" status
- Crawl error monitoring: daily GSC API pull → Slack alert for any new 4xx/5xx errors above [threshold]
- Index coverage monitoring: weekly comparison of indexed page count — alert on >2% drop
- Sitemap validation: automated weekly submission and error check
- Schema validation: scheduled structured data testing on deploy
- Redirect monitoring: weekly crawl of redirect chains — alert on any chain exceeding 2 hops
- Third-party script performance budget: alert when new third-party scripts exceed [KB] threshold
- Recommended tool stack: [Screaming Frog scheduled crawls / Ahrefs Site Audit / SEOmonitor / ContentKing / custom GSC API scripts]
- Reporting cadence: weekly automated dashboard → monthly deep-dive → quarterly engineering sprint

**SECTION 9: ENGINEERING SPRINT BACKLOG**
Format each fix as an engineering ticket ready to add to Jira or Linear:

Sprint 1 (Week 1-2 — Revenue-critical quick wins):
TICKET: [ID]
Title: [Fix title]
Description: [What needs to be done and why — revenue impact context]
Acceptance Criteria: [Specific, measurable outcome — e.g., "LCP < 2.5s on /product/ page group measured in GSC field data within 30 days"]
Effort estimate: [hours / story points]
Revenue impact: $[pipeline at risk if not fixed]
Files/pages affected: [specific list]
[Repeat for each Sprint 1 ticket]

Sprint 2 (Week 3-4 — Authority and indexation):
[Repeat ticket format]

Sprint 3 (Month 2 — Architecture improvements):
[Repeat ticket format]

**SECTION 10: BOARD-READY TECHNICAL SEO HEALTH SUMMARY**
- Technical SEO health score: [1-10] with benchmark context (B2B SaaS average, top quartile)
- Estimated current organic pipeline loss from technical issues: $[amount]/month
- Total pipeline recovery potential from full remediation: $[amount]/quarter
- Engineering investment required: [hours] over [timeline]
- ROI of technical SEO investment: $[pipeline recovered] per $[engineering hour cost] = [ROI multiple]
- Top 3 technical risks if not addressed in next 90 days
- Recommended: [Immediate action / Scheduled sprint / Monitoring only]

OUTPUT FORMAT: Structure as a Technical SEO Revenue Impact Report. Lead every section with a dollar figure or revenue-correlated metric. Use tables for the revenue impact matrix and engineering backlog. Write diagnostic language that a VP Engineering and a CMO can both read — technical specificity plus revenue framing throughout. No vanity metrics (do not mention "impressions" or "traffic" without connecting to pipeline or revenue).

## Example Input/Output

**Input Example:**
Company: Finlo (FinTech SaaS, expense management, ACV $42K, Series B)
Industry: FinTech / Finance Operations
CMS: Next.js (App Router, ISR)
CDN: Cloudflare
Monthly organic sessions: 86,000
Organic pipeline (last 90 days): $2.1M
ACV: $42,000 | Sales cycle: 52 days | Win rate: 22%
Dev capacity: 1 sprint/quarter allocated to SEO

Core Web Vitals: 68% of pages "Good," 22% "Needs Improvement," 10% "Poor"
Worst LCP: /blog/expense-report-software/ — LCP 5.1s (hero image not preloaded, no image CDN)
Crawl errors: 47 pages with 404 errors (from deprecated blog URLs) | 89 pages "crawled but not indexed" (thin content, mostly pagination)
Orphan pages: 34 pages with zero internal links, 8 of which have >500 monthly impressions
Schema: FAQ schema on 12 blog posts (valid); no schema on product pages, comparison pages, or pricing
Mobile score (Lighthouse): avg 44/100 across blog posts | 38% of organic traffic is mobile
Mobile conversion rate: 0.6% vs. desktop 2.1% (conversion rate gap = 1.5 percentage points)

**Output Example (abbreviated):**

**REVENUE IMPACT MATRIX (Highest-priority issues by pipeline at risk)**

| Issue | Affected Sessions/Mo | Pipeline at Risk | Recovery Potential | Effort |
|---|---|---|---|---|
| Mobile conversion rate gap (0.6% vs 2.1% desktop) | 32,680 mobile sessions | $208K/mo in lost pipeline | $156K/mo recoverable | 2 sprints |
| Orphan pages with impressions | ~3,400 sessions/mo missing | $63K/mo pipeline gap | $47K/mo if linked properly | 8 hrs |
| Poor CWV pages (10% of organic pages) | 8,600 sessions on poor pages | $48K/mo pipeline at risk | $32K/mo if fixed to "Good" | 1 sprint |
| 404 errors on deprecated blog URLs | ~2,100 sessions lost | $39K/mo pipeline loss | $29K/mo via 301 redirects | 4 hrs |
| Schema gaps on product/pricing pages | CTR uplift of est. 0.8% | $34K/mo additional pipeline | $28K/mo from rich results | 6 hrs |

**QUICK WIN #1 — Orphan Page Internal Linking (8 hours, $47K/mo recovery)**
Eight orphan pages have >500 monthly impressions but zero internal links — Googlebot barely crawls them and users can't discover them. Top opportunity: /blog/corporate-expense-policy-template/ (2,100 impressions/mo, ranks position 18 for "expense policy template") — add 5 internal links from related posts (/blog/expense-management-best-practices/, /blog/ap-automation-guide/, /solutions/expense-management/, /blog/receipt-management-software/, /resources/expense-report-template/) with keyword-anchored text. Expected result: ranking improvement from 18 → 9-12 within 60 days = ~180 additional clicks/month at 2.1% conversion = $158K additional pipeline per year.

**MOBILE CONVERSION RATE RECOVERY PLAN**
The 1.5-point mobile vs. desktop conversion rate gap costs Finlo an estimated $208K/month in foregone organic pipeline. Root cause: Lighthouse mobile average 44/100 — primary drag is unoptimized images (hero images served as 800KB+ JPEG, no WebP, no lazy loading) and render-blocking font loads (3 Google Fonts variants blocking render for 1.1s on mobile).

Fix 1: Convert all blog hero images to WebP using Cloudflare Image Resizing — 0 engineering hours (Cloudflare config change). Expected mobile LCP improvement: 2.2s → ~1.4s on /blog/* pages.
Fix 2: Replace Google Fonts import with `font-display: swap` + preconnect hint in `<head>` — 2 engineering hours. Eliminates 1.1s render-blocking font load.
Fix 3: Implement `loading='lazy'` on all below-fold images across Next.js Image component — 6 engineering hours. Reduces initial page weight by ~60%.

Combined expected mobile PageSpeed improvement: 44 → 72/100. Estimated mobile conversion rate improvement: 0.6% → 1.3% (based on Google's CWV-to-conversion correlation for FinTech). Monthly pipeline recovery: ~$104K/month.

## Success Metrics

**Prompt output quality indicators:**
- Every issue is assigned a dollar figure (pipeline at risk or recovery potential) — no fix is recommended without revenue justification
- Engineering tickets are specific enough to execute without additional discovery
- Core Web Vitals recommendations cite specific Lighthouse metrics and implementation methods (not generic "improve site speed")
- The mobile optimization plan accounts for the real-world mobile vs. desktop conversion rate difference
- Schema recommendations are tied to measurable CTR uplift evidence, not assumed value

**Technical SEO health benchmarks (B2B SaaS):**
- Core Web Vitals: >75% of pages in "Good" status is the baseline; top quartile achieves >90%
- Mobile PageSpeed: >65/100 is functional; >80 is competitive for organic-focused SaaS
- Index coverage: indexed pages should represent >85% of submitted sitemap URLs
- Orphan pages: zero pages with organic impressions should have fewer than 3 inbound internal links
- Schema coverage: at minimum, FAQ and Article schema on all blog posts; Product/SoftwareApplication on product pages
- 404 error threshold: <0.5% of indexed pages with crawl errors in any 30-day window

## Related Prompts
- [AI-Powered B2B SaaS Organic Search Performance Analytics & Pipeline Revenue Attribution](./AI-Powered-B2B-SaaS-Organic-Search-Performance-Analytics-&-Pipeline-Revenue-Attribution-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Organic Search Demand Architecture & Technical SEO Pipeline Revenue](../../04_Demand-&-Lead-Generation-&-Growth/SEO-&-Organic-Growth/AI-Powered-B2B-SaaS-Organic-Search-Demand-Architecture-&-Technical-SEO-Pipeline-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Generative Engine Optimization GEO & AI Answer Engine Visibility](../../04_Demand-&-Lead-Generation-&-Growth/SEO-&-Organic-Growth/AI-Powered-B2B-SaaS-Generative-Engine-Optimization-GEO-&-AI-Answer-Engine-Visibility-Architecture-Pipeline-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS CRO Analytics & Experimentation Intelligence Engine](../Conversion-Rate-Optimization-Analytics/AI-Powered-B2B-SaaS-CRO-Analytics-&-Experimentation-Intelligence-Engine.md)

## Integration Tips

**Google Search Console API Automation:**
- Pull Core Web Vitals field data weekly via the Search Console API → Google Sheets → flag any page group that drops from "Good" to "Needs Improvement" and auto-create a Jira ticket via Zapier
- Use the URL Inspection API in batch mode to monitor your top 100 organic pages for indexation status changes monthly — pipe results into a Slack alert channel

**Screaming Frog + Ahrefs Monthly Crawl:**
- Schedule a monthly Screaming Frog crawl (headless rendering mode for JS sites) → export orphan pages, redirect chains, and schema gaps as CSV → feed directly into the prompt as the crawl data input
- Ahrefs Site Audit runs weekly and produces a technical health score — use the score trend and issue count as your quick-pulse input before the full monthly deep-dive

**Cloudflare / CDN Performance Integration:**
- Cloudflare Analytics provides real-user TTFB data by URL — pull top 50 organic landing pages monthly and use as your server response time input
- Configure Cloudflare image optimization (Polish + WebP auto-conversion) as a zero-engineering CWV improvement layer — document the before/after delta as prompt input

**ContentKing / Lumar Real-Time Monitoring:**
- ContentKing monitors every page change in real time — set alerts for any new noindex tags, canonical changes, or schema removals that could affect organic performance
- Use ContentKing's weekly summary as your "technical change log" input to the prompt — catches accidental technical regressions from CMS or code deployments

**HubSpot / Salesforce Mobile Attribution:**
- In HubSpot, create a custom property "Device Type at First Touch" (populate via hidden form field reading the user agent or GA4 session source) — use this to measure mobile-sourced pipeline separately and validate the mobile conversion rate gap input data
- Build a Salesforce report: "Opportunities with First Touch = Organic Search, Device = Mobile" — this is your ground-truth mobile pipeline number, not a sampling estimate

## Troubleshooting

**Problem: Core Web Vitals field data in Google Search Console shows "Not enough data" for most page groups, making it impossible to diagnose which pages are causing failures**
Solution: Switch to Lighthouse lab data as your primary diagnostic tool. Run PageSpeed Insights on your top 20 organic landing pages manually (or use the PageSpeed Insights API in bulk). Lab data doesn't reflect real-user conditions but gives you specific, actionable Lighthouse audit items. Simultaneously, implement Chrome User Experience Report (CrUX) monitoring via your CDN or a tool like DebugBear — you'll start building sufficient field data within 28 days (the CrUX rolling window period).

**Problem: The prompt recommends fixing JavaScript rendering issues but the engineering team insists the site "renders fine" because they can see the content in the browser**
Solution: The browser always executes JavaScript — the issue is whether Googlebot executes your JS before crawling. Use Google Search Console's URL Inspection tool → "Test Live URL" → view the "Screenshot" tab (what Google sees) and compare to "More Info → Crawled page" (the raw HTML). If the main content, navigation links, or structured data are absent from the raw HTML but present in the rendered screenshot, you have a JS SEO issue that will suppress rankings. Show the engineering team these two views side-by-side as proof.

**Problem: The executive team dismisses technical SEO as "developer stuff" with no revenue impact, making it impossible to get engineering time allocated**
Solution: Run the Revenue Impact Matrix section of this prompt first and present only the dollar figures to leadership before any technical discussion. Frame every fix as an investment decision: "Fixing the mobile page speed issue costs 12 engineering hours ($2,400 at blended rate) and recovers an estimated $104K/month in foregone organic pipeline — that's a 43x first-month ROI." Then provide the technical backlog as a second document to engineering. The CMO approves the business case; engineering executes the ticket queue.

## Version History
- v1.0: Initial creation (auto-generated)
