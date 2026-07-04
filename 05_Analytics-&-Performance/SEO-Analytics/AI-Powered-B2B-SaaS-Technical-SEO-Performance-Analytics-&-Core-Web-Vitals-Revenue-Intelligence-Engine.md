# AI-Powered B2B SaaS Technical SEO Performance Analytics & Core Web Vitals Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-25 min | **Tags:** b2b-saas, seo, technical-seo, core-web-vitals, analytics, revenue-attribution, site-performance, engineering-alignment

## Overview
Analyzes technical SEO health data — Core Web Vitals, crawl efficiency, indexation rate, JavaScript rendering errors, and site architecture signals — and translates performance trends into pipeline and revenue impact. Use this when diagnosing an unexplained organic traffic drop, justifying a technical SEO investment to your engineering team or CFO, or building a continuous monitoring system that surfaces revenue-relevant technical issues before they compound.

## Quick Copy-Paste Version

You are a senior B2B SaaS technical SEO analyst. Analyze the following technical performance data and produce an engineering-ready diagnostic report with revenue impact modeling.

SITE PERFORMANCE DATA:
- Product/domain: [your domain]
- CMS/tech stack: [e.g., Next.js, WordPress, Webflow, HubSpot CMS]
- Monthly organic sessions (current): [X]
- Monthly organic sessions (3 months ago): [X]
- Organic MQL rate: [X]% of organic visitors convert to MQL
- Average ACV: $[X]
- Core Web Vitals (from Google Search Console / PageSpeed Insights):
  - LCP (Largest Contentful Paint): [X]s — [pass/fail]
  - CLS (Cumulative Layout Shift): [X] — [pass/fail]
  - INP (Interaction to Next Paint): [X]ms — [pass/fail]
- Crawl data (from Screaming Frog, Sitebulb, or GSC Coverage report):
  - Total pages crawled: [X]
  - Pages indexed: [X]
  - Pages excluded/errors: [X]
  - Crawl errors (4xx, 5xx): [X]
- JavaScript rendering issues: [yes/no — describe if yes]
- Internal linking issues: [yes/no]
- Duplicate content / canonical issues: [yes/no]
- Recent site changes (migrations, redesigns, CMS changes): [describe or "none"]

ANALYSIS REQUIRED:
1. REVENUE IMPACT ESTIMATE: Calculate the organic pipeline at risk from current technical issues. If Core Web Vitals fail thresholds, estimate ranking suppression effect using Google's documented 1–10% traffic penalty range — translate to MQLs and ARR.
2. ISSUE PRIORITIZATION MATRIX: Rank all identified technical issues by: (a) estimated ranking/traffic impact, (b) engineering complexity (hours/sprint points), (c) revenue recovery speed. Output as a prioritized table with P1/P2/P3 classification.
3. CORE WEB VITALS TREND ANALYSIS: Diagnose the root cause of any failing metric. LCP issues → likely image optimization, server response time, or render-blocking resources. CLS issues → likely dynamic ad injection, font loading, or lazy-loaded images without size attributes. INP issues → likely excessive JavaScript execution or third-party script bloat.
4. CRAWL EFFICIENCY AUDIT: Calculate indexation rate (indexed ÷ submitted). If below 85%, identify likely causes: orphaned pages, thin content, duplicate URL patterns, faceted navigation, or noindex errors applied incorrectly.
5. 90-DAY RECOVERY ROADMAP: Sequence fixes by sprint. Output a 3-sprint technical SEO improvement plan with estimated organic traffic recovery timeline and projected MQL uplift.

Produce a board-ready technical SEO health summary + an engineering sprint brief that a developer can action without further marketing interpretation.

## Advanced Customizable Version

ROLE: You are a B2B SaaS technical SEO revenue intelligence architect. You sit at the intersection of engineering and marketing — you translate PageSpeed scores, crawl logs, and indexation reports into language that CFOs and CTOs act on. You understand that every 100ms of LCP improvement has a measurable conversion and ranking impact, and you build data models that prove it. Your job is to surface technical debt that is silently costing organic pipeline and turn it into engineering tickets with revenue justification.

COMPANY CONTEXT:
- Domain: [your domain]
- Tech stack: [CMS, JavaScript framework, CDN, hosting infrastructure]
- Organic search monthly sessions: [current] vs. [3 months ago] vs. [12 months ago]
- Organic MQL volume: [current monthly] vs. [3 months ago]
- Average ACV: $[X] | Average sales cycle: [X weeks/months]
- Organic-attributed pipeline (last 90 days): $[X]
- Primary ICP: [job title(s)] at [company size/type]
- Geographic organic mix: [US / EMEA / global — specify % by region]
- Core Web Vitals status (paste full GSC CWV report or PageSpeed Insights JSON if available): [data]
- GSC Coverage report (Valid, Excluded, Error counts): [data]
- Known technical events in last 6 months: [migrations, redesigns, hosting changes, CMS upgrades, ad platform script additions — or "none"]
- Competitor domains to benchmark against: [Competitor A], [Competitor B]
- Current domain authority / DR / domain rating: [X]
- Ahrefs/Semrush organic traffic trend: [X% change over 90 days]

OBJECTIVE: Produce a complete technical SEO performance analytics report that (1) quantifies the revenue impact of current technical debt, (2) prioritizes fixes by engineering effort vs. revenue recovery, (3) delivers a 90-day improvement roadmap, and (4) establishes a continuous monitoring framework so this analysis runs automatically each week.

---

DELIVERABLE 1 — TECHNICAL SEO REVENUE IMPACT DASHBOARD:

Build a revenue-impact model for each identified technical category:

| Technical Issue Category | Affected Pages | Estimated Traffic Suppression | Organic Sessions at Risk/mo | MQLs at Risk/mo | ARR at Risk/yr |
|---|---|---|---|---|---|
| Core Web Vitals failures (LCP/CLS/INP) | [X] | [1–10% per Google data] | [X] | [X] | $[X] |
| Crawl errors (4xx/5xx) | [X] | [Direct — uncrawled = unindexed] | [X] | [X] | $[X] |
| Indexation gaps (submitted but not indexed) | [X] | [100% for affected pages] | [X] | [X] | $[X] |
| Duplicate content / canonicalization errors | [X] | [Dilutes PageRank to wrong variant] | [X] | [X] | $[X] |
| JavaScript rendering failures | [X] | [Googlebot may not see content] | [X] | [X] | $[X] |
| Internal linking orphans | [X] | [Reduces crawl depth & PageRank flow] | [X] | [X] | $[X] |
| Mobile usability failures | [X] | [Google mobile-first indexing penalty] | [X] | [X] | $[X] |

TOTAL ORGANIC PIPELINE AT RISK: $[X]/year

---

DELIVERABLE 2 — CORE WEB VITALS DEEP DIAGNOSIS:

For each failing metric, provide root cause analysis and fix specification:

LCP ANALYSIS (Target: <2.5s):
- Current LCP value: [X]s — Field data vs. Lab data delta: [X]
- LCP element identified: [hero image / H1 text block / background image / video]
- Root cause diagnosis (rank by probability):
  □ Server response time (TTFB) >600ms → investigate hosting, CDN configuration, server-side caching
  □ Render-blocking CSS/JS above the fold → audit <head> resource loading order
  □ Unoptimized hero image (wrong format, no preload hint, no responsive srcset)
  □ Client-side rendering delay (Next.js/React hydration lag)
  □ Third-party script (chat widget, analytics, ad tags) blocking LCP element
- Recommended fix: [specific engineering action with expected improvement]
- Estimated improvement: [X]s reduction in LCP
- Estimated ranking/traffic impact: [X]% organic traffic recovery

CLS ANALYSIS (Target: <0.1):
- Current CLS score: [X] — Most significant layout shift element: [X]
- Root cause diagnosis:
  □ Ad slots without reserved dimensions (Google Ads, LinkedIn Insight Tag)
  □ Web font loading causing FOUT (flash of unstyled text) — check font-display property
  □ Lazy-loaded images missing explicit width/height attributes
  □ Dynamic content injected above existing content (banners, cookie notices, chat)
  □ iframes without fixed dimensions
- Engineering fix spec: [concrete action]

INP ANALYSIS (Target: <200ms):
- Current INP value: [X]ms — Interaction type causing delay: [click / tap / keyboard]
- Root cause diagnosis:
  □ Long tasks (>50ms) blocking main thread — profile with Chrome DevTools Performance panel
  □ Excessive JavaScript bundle size — check Webpack/Next.js bundle analyzer
  □ Third-party scripts (Intercom, HubSpot tracking, Drift, Segment) on main thread
  □ React/Vue component re-render storms on user interaction
  □ Synchronous localStorage/sessionStorage access in event handlers
- Fix priority: [Immediate P1 / P2 next sprint / P3 backlog]

---

DELIVERABLE 3 — CRAWL EFFICIENCY & INDEXATION AUDIT:

INDEXATION HEALTH SCORE:
- Submitted URLs: [X] | Indexed URLs: [X] | Indexation Rate: [X]%
- Benchmark: Healthy B2B SaaS sites maintain 85–95% indexation rates

EXCLUSION ROOT CAUSE ANALYSIS:
For each exclusion category from GSC Coverage report:
- "Crawled – currently not indexed": [X pages] → Likely causes: thin content (<500 words), low E-E-A-T signals, duplicate near-content, blocked by robots.txt indirectly
- "Discovered – currently not indexed": [X pages] → Likely causes: poor internal linking, crawl budget exhaustion, low PageRank flow to these pages
- "Page with redirect": [X pages] → Audit redirect chains >2 hops; each hop costs crawl budget
- "Excluded by noindex tag": [X pages] → Validate intentional vs. accidental noindex (common on HubSpot staging, WordPress plugin conflicts, CMS template errors)
- "Duplicate, Google chose different canonical": [X pages] → Review canonical tag implementation; check for www/non-www or HTTP/HTTPS duplication

CRAWL BUDGET OPTIMIZATION RECOMMENDATIONS:
- Faceted navigation generating duplicate URLs: [diagnose and recommend parameter handling in GSC or robots.txt]
- Paginated content: [recommend rel=next/prev or canonical to root]
- Session ID or UTM parameter URLs being indexed: [recommend URL parameter configuration in GSC]
- Orphaned pages with zero internal links: [identify and add to site architecture]

---

DELIVERABLE 4 — JAVASCRIPT RENDERING INTELLIGENCE:

Run a pre/post-render comparison (use Google's Rich Results Test, Screaming Frog with rendering enabled, or Googlebot's perspective via GSC's URL Inspection tool):

- Content visible in HTML source (pre-render): [X elements]
- Content visible after JavaScript execution (post-render): [X elements]
- Delta — content Googlebot may miss: [describe]
- Affected content types: [navigation links / product descriptions / pricing / customer logos / reviews / CTAs]
- Revenue-critical content at risk: [list highest-value pages where JS rendering failures could suppress indexation]
- Recommended fix: [server-side rendering (SSR) / static site generation (SSG) / dynamic rendering / prerendering service]

---

DELIVERABLE 5 — COMPETITOR TECHNICAL BENCHMARK:

Compare your technical SEO profile against primary competitors:

| Metric | [Your Domain] | [Competitor A] | [Competitor B] | Industry Median |
|---|---|---|---|---|
| LCP (desktop/mobile) | [X]s / [X]s | [X]s / [X]s | [X]s / [X]s | [X]s / [X]s |
| CLS | [X] | [X] | [X] | [X] |
| INP | [X]ms | [X]ms | [X]ms | [X]ms |
| Domain Crawlability Score | [X]% | [X]% | [X]% | [X]% |
| Indexation Rate | [X]% | [X]% | [X]% | [X]% |
| Mobile Performance Score (0–100) | [X] | [X] | [X] | [X] |
| HTTPS Implementation | [✓/✗] | [✓/✗] | [✓/✗] | — |

COMPETITIVE INSIGHT: [Which competitors have technical SEO advantages? Where are they vulnerable? What is the ranking opportunity if you close the gap?]

---

DELIVERABLE 6 — ENGINEERING SPRINT PRIORITIZATION:

Translate findings into sprint-ready engineering tickets, prioritized by revenue impact per engineering hour invested:

PRIORITY 1 — IMMEDIATE (This Sprint / Next 2 Weeks):
For each P1 issue:
- Issue: [specific technical problem]
- Revenue impact: $[X] organic ARR at risk
- Engineering effort: [X hours / story points]
- Revenue per engineering hour: $[X]
- Acceptance criteria: [specific measurable outcome]
- Tools to verify fix: [GSC URL Inspection / PageSpeed Insights / Screaming Frog / Chrome DevTools]

PRIORITY 2 — HIGH (Next 30 Days):
[Same format]

PRIORITY 3 — MEDIUM (Next 60–90 Days):
[Same format]

BACKLOG — LOW (Quarterly Review):
[Same format]

---

DELIVERABLE 7 — CONTINUOUS MONITORING FRAMEWORK:

Design an AI agent monitoring system that runs weekly without human intervention:

WEEKLY AUTOMATED CHECKS:
- Pull Core Web Vitals field data via GSC API → flag any metric crossing from "Good" to "Needs Improvement"
- Pull GSC Coverage report delta → alert if indexed pages drop >2% week-over-week
- Run Lighthouse CI on top 20 organic landing pages → flag any page scoring <50 on Performance
- Check crawl error log via Ahrefs/Semrush API → alert on new 5xx errors on indexed pages
- Monitor redirect chain depth → alert on any chain >2 hops discovered on crawled pages

MONTHLY AUTOMATED REPORTS:
- Core Web Vitals trend chart (LCP/CLS/INP over rolling 90 days) → email to CMO + CTO
- Indexation rate trend → correlate with organic traffic changes
- Competitor technical score comparison → identify widening or closing gaps
- Engineering ticket progress → revenue recovered from fixes deployed

INTEGRATION STACK:
- Data sources: Google Search Console API, PageSpeed Insights API, Ahrefs API or Semrush API, Screaming Frog scheduled crawl exports
- Automation: Zapier or Make.com workflow → triggers on threshold breaches → creates Jira/Linear tickets with revenue context pre-populated
- Reporting: Looker Studio dashboard pulling GSC + CWV data → auto-refresh weekly
- Alerting: Slack channel #seo-alerts receives automated digest every Monday 9am

## Example Input/Output

**Input Example:**
- Domain: DataBridge.io (B2B SaaS data integration platform)
- Tech stack: Next.js 14 on Vercel, HubSpot CMS for blog
- Organic sessions: 42,000/month (current) vs. 51,000/month (3 months ago) — 18% decline
- Organic MQL rate: 2.1% | ACV: $28,000 | Sales cycle: 6 weeks
- Core Web Vitals: LCP 4.2s (FAIL), CLS 0.08 (PASS), INP 310ms (FAIL)
- GSC Coverage: 2,400 submitted, 1,680 indexed (70% indexation rate — below threshold)
- JavaScript rendering: Yes — pricing page content and customer logos only visible after JS execution
- Recent events: Migrated from Webflow to Next.js 4 months ago

**Output Example (abbreviated):**

REVENUE IMPACT SUMMARY:
- LCP failure (4.2s vs. 2.5s target): Estimated 8% organic traffic suppression = 3,360 sessions/month at risk = 71 MQLs/month = $1.98M organic ARR at risk
- INP failure (310ms vs. 200ms target): Estimated 4% additional suppression = 1,680 sessions/month = 35 MQLs/month = $990K organic ARR at risk
- Indexation gap (70% vs. 85% target): 360 pages stuck in "Discovered – not indexed" = estimated $840K organic ARR never reached
- JS rendering gap on pricing page: Googlebot may not index pricing content, suppressing high-commercial-intent rankings
- TOTAL ORGANIC ARR AT RISK: $3.81M/year

ROOT CAUSE DIAGNOSIS — LCP 4.2s:
- TTFB: 1.2s (Next.js ISR cache miss on Vercel edge — implement aggressive stale-while-revalidate)
- Hero image: 380KB WebP — missing preload hint in <head>; not using next/image component
- Third-party blocking: HubSpot tracking script loading synchronously in <head> — defer to after LCP element

ROOT CAUSE DIAGNOSIS — INP 310ms:
- React hydration taking 280ms on initial load — 47 components re-rendering on page mount
- Intercom chat widget executing on main thread at interaction time — lazy load after user interaction
- Custom analytics event listeners attached to 340 DOM elements on mount — implement event delegation

ENGINEERING SPRINT PLAN:
Sprint 1 (Weeks 1–2, ~40 engineering hours):
- Implement next/image for all above-the-fold images with explicit preload (8hrs, $1.2M ARR recovery)
- Move HubSpot tracking script to async defer after LCP (2hrs, $320K ARR recovery)
- Fix Intercom lazy loading (4hrs, $490K ARR recovery)
Revenue recovery potential: $2.01M ARR | Engineering hours: 14 | Revenue per hour: $143,571

Sprint 2 (Weeks 3–6, ~60 hours):
- Implement ISR with 60-second revalidation for product pages (12hrs)
- Resolve JS rendering on pricing page using Next.js SSR for critical content (16hrs)
- Fix 127 orphaned blog posts with zero internal links (8hrs)
Revenue recovery potential: $1.12M ARR

MONITORING SETUP:
- Zapier automation: GSC API → check weekly CWV field data → if LCP >3.5s on any top-50 organic page → create Jira P1 ticket with estimated MQL impact pre-populated
- Looker Studio: CWV trend + organic sessions + MQL volume on single dashboard, auto-refresh Mondays 6am

## Success Metrics

- Core Web Vitals all pages passing "Good" threshold within 90 days of implementing fixes
- Indexation rate returns to 85%+ within 60 days of crawl fixes
- Organic traffic recovering to pre-migration baseline within 90 days
- Engineering team completing P1 technical SEO fixes within 2-sprint cycle
- Automated monitoring catches new technical regressions within 7 days of occurrence
- CMO/CTO alignment: engineering accepts technical SEO tickets as revenue-justified work

## Related Prompts

- [AI-Powered B2B SaaS SEO Performance Analytics & Organic Search Revenue Attribution Intelligence Engine](./AI-Powered-B2B-SaaS-SEO-Performance-Analytics-&-Organic-Search-Revenue-Attribution-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Technical SEO Architecture & Core Web Vitals Site Performance Revenue Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/SEO-&-Organic-Search/AI-Powered-B2B-SaaS-Technical-SEO-Architecture-&-Core-Web-Vitals-Site-Performance-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Website Experimentation Program & A-B Testing Revenue Intelligence Engine](../Web-Analytics-&-Optimization/AI-Powered-B2B-SaaS-Website-Experimentation-Program-&-A-B-Testing-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Web Analytics Intelligence & Website Revenue Performance Optimization Engine](../Web-Analytics-&-Optimization/AI-Powered-B2B-SaaS-Web-Analytics-Intelligence-&-Website-Revenue-Performance-Optimization-Engine.md)

## Integration Tips

- **Google Search Console API**: Automate Core Web Vitals field data extraction weekly; build a pipeline of CWV scores per URL into BigQuery for trending and anomaly detection.
- **PageSpeed Insights API**: Run automated Lighthouse CI against your top 50 organic landing pages on every deployment — fail the CI build if any page drops below a Performance score of 60.
- **Screaming Frog + Google Sheets**: Schedule weekly crawls with Screaming Frog's API; export to Google Sheets; use Apps Script to color-code any page with 4xx/5xx errors or noindex issues and auto-email the SEO team.
- **Ahrefs or Semrush API**: Pull weekly organic traffic trend and ranking position changes; correlate with Core Web Vitals changes to build a regression model showing technical performance vs. ranking correlation.
- **Jira / Linear Integration**: Use Zapier or Make.com to auto-create engineering tickets when GSC API signals threshold breaches; pre-populate tickets with revenue context so engineering prioritizes correctly.
- **Looker Studio**: Build a live CEO/CTO technical SEO revenue dashboard: LCP/CLS/INP trend lines overlaid with organic traffic and MQL volume — makes the revenue case visual and undeniable.
- **Vercel / Netlify Analytics**: If using JAMstack, use built-in performance analytics to track real-user performance metrics by page and geography; feed this into your SEO performance model.

## Troubleshooting

**Problem:** Core Web Vitals show "Good" in lab data (PageSpeed Insights) but "Needs Improvement" or "Poor" in field data (GSC CWV report).
**Solution:** Lab data uses a simulated device on a fast connection; field data reflects real users on slower devices/networks. Prioritize field data for ranking impact. Focus on eliminating third-party script weight and optimizing for mid-range Android devices (Moto G4 class) which represent a large portion of the field data sample. Segment field data by device type in CrUX to identify if mobile or desktop is the primary failure.

**Problem:** 90-day organic traffic decline coincides with a major site migration but Core Web Vitals are passing.
**Solution:** CWV passing doesn't rule out technical causes. Audit: (1) were all 301 redirects implemented correctly from old URLs to new URLs? Check for redirect chains or 302 temporary redirects used instead of 301 permanent. (2) Were canonical tags carried over correctly to the new CMS? (3) Was XML sitemap updated and resubmitted? (4) Did internal links update to new URL structure? Use Screaming Frog's "Compare Crawls" feature to diff old vs. new URL structures.

**Problem:** Engineering team deprioritizes technical SEO tickets in favor of product features.
**Solution:** Never submit a technical SEO ticket without revenue justification pre-calculated. Use the revenue impact model from this prompt: "This 4.2s LCP is suppressing 8% of our organic traffic, costing $1.98M in organic ARR annually. The hero image fix takes 8 engineering hours and recovers $1.2M ARR — that's $150K revenue per engineering hour, higher than any feature we're building this quarter." Frame every ticket as an ROI decision, not a technical preference.

## Version History
- v1.0: Initial creation (auto-generated)
