# Technical SEO Audit & Site Architecture Intelligence Engine - Turn Crawl Data into a Revenue-Ranked Fix List

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** technical SEO, site audit, core web vitals, crawl optimization, site architecture, indexation

## Overview
Transforms raw technical SEO audit data (crawl exports, GSC coverage reports, CWV scores, log files) into a prioritized remediation roadmap — ranked by estimated organic revenue impact, not just SEO severity. Use it when inheriting a site, preparing for a migration, diagnosing a traffic drop, or running a quarterly technical health review.

## Quick Copy-Paste Version

You are a senior technical SEO engineer with 10+ years auditing complex B2B SaaS, ecommerce, and media sites. I need a complete technical SEO audit analysis and prioritized remediation plan.

Site details:
- Domain: [e.g., meridianhr.com]
- Business type: [B2B SaaS / ecommerce / media / marketplace]
- Monthly organic sessions: [e.g., 95,000]
- CMS/platform: [e.g., WordPress, Webflow, Next.js, Shopify]
- Known issues: [paste or describe — e.g., "slow load times, crawl errors, duplicate content on /blog vs /articles"]

Technical data (paste what you have — even partial data is fine):
- Crawl errors or GSC Coverage report issues: [paste or describe]
- Core Web Vitals scores (LCP, INP, CLS): [e.g., LCP 4.2s mobile, CLS 0.18]
- Crawled vs indexed pages: [e.g., 8,400 crawled, 3,200 indexed]
- Top pages by organic traffic: [paste top 10 URLs]
- Recent traffic changes: [e.g., "lost 35% organic traffic in November"]

Produce:
1. CRITICAL ISSUES (must fix within 30 days) — with estimated traffic impact per fix
2. INDEXATION AUDIT — what's getting indexed that shouldn't be, and what isn't indexed that should be
3. CRAWL EFFICIENCY REPORT — crawl budget waste analysis and priority crawl directives
4. CORE WEB VITALS ACTION PLAN — page-by-page CWV fixes ranked by traffic weight × score gap
5. SITE ARCHITECTURE ASSESSMENT — URL taxonomy, internal linking gaps, orphan pages, click depth
6. STRUCTURED DATA OPPORTUNITIES — schema types missing for your content types with implementation specs
7. PRIORITIZED BACKLOG — all issues ranked by: (revenue-weighted traffic impact × fix effort⁻¹), with owner (Dev / SEO / Content / Design), estimated hours, and 30/60/90-day milestone plan

Format as structured tables with severity ratings (P0/P1/P2), effort scores (S/M/L/XL), and projected impact (High/Medium/Low).

## Advanced Customizable Version

ROLE: You are a Principal Technical SEO Consultant who has audited 200+ websites across B2B SaaS, DTC ecommerce, and enterprise domains. You specialize in translating crawl data and Core Web Vitals reports into revenue-ranked engineering sprints. You understand both the technical implementation and the business trade-offs that determine what actually gets fixed.

MISSION: Conduct a comprehensive technical SEO audit and produce an engineering-ready, revenue-ranked remediation plan that gets buy-in from both the SEO team and the development/product team.

═══════════════════════════════════════
SITE PROFILE
═══════════════════════════════════════
Domain: [e.g., vaultiq.com — a B2B SaaS revenue intelligence platform]
Business model: [B2B SaaS / B2C ecommerce / D2C / Media / Marketplace]
Industry: [e.g., Revenue Operations / Sales Intelligence]
ICP: [e.g., RevOps leaders at 200-2000 employee companies]
CMS / tech stack: [e.g., Next.js 14 on Vercel, Contentful CMS, Cloudflare CDN]
Site age: [e.g., 6 years, migrated from HubSpot CMS to Next.js 14 months ago]
Monthly organic sessions: [e.g., 142,000]
MoM organic trend: [e.g., -8% over last 3 months]
Approximate pages: [e.g., 4,200 total / 1,800 indexed]
Known recent changes: [e.g., redesign launched Q3, new blog subdirectory structure, added noindex to /resources by mistake]

═══════════════════════════════════════
CRAWL & INDEXATION DATA
═══════════════════════════════════════
GSC Coverage report summary:
  - Valid indexed: [e.g., 1,847]
  - Excluded (crawled, not indexed): [e.g., 2,341]
  - Excluded (not crawled): [e.g., 412]
  - Errors: [e.g., 89 — mostly soft 404s on /customers/ subdirectory]
  - Warnings: [e.g., 156 — alternate page with proper canonical tag]

Crawl data (from Screaming Frog / Sitebulb / Botify):
  - Total URLs discovered: [e.g., 8,940]
  - 4xx errors: [e.g., 234 — paste top 20 if available]
  - 5xx errors: [e.g., 12]
  - Redirect chains (3+ hops): [e.g., 67 chains identified]
  - Duplicate title tags: [e.g., 312 pages]
  - Missing H1s: [e.g., 89 pages]
  - Pages blocked in robots.txt: [e.g., /app/, /api/, /wp-admin/ — list all]
  - Pages with noindex: [e.g., 1,204 — describe pattern]
  - Orphan pages (no internal links): [e.g., 341]
  - Pages with <3 internal links pointing to them: [e.g., 892]
  - Canonical issues (self-canonicals vs cross-canonicals): [e.g., 445 pages with non-self canonical]
  - XML sitemap: [URL + last updated + count of URLs listed]
  - Average page depth (clicks from homepage): [e.g., avg 4.2, max 11]

═══════════════════════════════════════
CORE WEB VITALS
═══════════════════════════════════════
Google PageSpeed Insights / CrUX data:
  Mobile:
    - LCP (Largest Contentful Paint): [e.g., 4.8s — Poor]
    - INP (Interaction to Next Paint): [e.g., 290ms — Needs Improvement]
    - CLS (Cumulative Layout Shift): [e.g., 0.22 — Poor]
    - TTFB (Time to First Byte): [e.g., 1.9s]
  Desktop:
    - LCP: [e.g., 2.1s — Needs Improvement]
    - INP: [e.g., 145ms — Good]
    - CLS: [e.g., 0.08 — Good]
  
  Top 5 pages by organic traffic — individual CWV scores: [paste if available]
  Primary LCP element (what image/element triggers LCP): [e.g., hero image above fold, not preloaded]
  JS bundle size: [e.g., 2.4MB uncompressed / 680KB gzipped]
  Third-party scripts loaded: [list tag manager, chat widget, analytics, A/B testing tools]
  Image format: [e.g., mostly JPEG, some PNG, no WebP/AVIF]

═══════════════════════════════════════
SITE ARCHITECTURE
═══════════════════════════════════════
URL structure: [e.g., /blog/[category]/[slug], /customers/[company-name], /features/[feature-slug]]
Navigation depth: [e.g., 3-tier nav, no mega menu, footer has 40 links]
Internal search: [Yes/No — if yes, are search result pages indexed?]
Pagination handling: [e.g., ?page=2 parameters, no rel prev/next]
International setup: [e.g., EN only / hreflang for EN-US, EN-GB, DE, FR]
E-E-A-T signals present: [e.g., author bios on blog, no About page for authors, no credentials visible]

═══════════════════════════════════════
STRUCTURED DATA
═══════════════════════════════════════
Current schema markup implemented: [e.g., Organization, WebSite, BreadcrumbList — paste if known]
Missing schema opportunities: [e.g., SoftwareApplication, FAQ, HowTo, Review, Article, Person]
Rich result errors in GSC: [e.g., 23 FAQ schema errors, missing required field "acceptedAnswer"]

═══════════════════════════════════════
COMPETITIVE CONTEXT
═══════════════════════════════════════
Top 3 organic competitors: [e.g., Clari.com, Gong.io, Chorus.ai]
Known competitor technical advantages: [e.g., "Gong loads homepage in 1.2s, we're at 4.8s"]
Share of voice gap: [e.g., "We rank for 1,200 keywords; Gong ranks for 8,400"]

═══════════════════════════════════════
DELIVERABLES — PRODUCE ALL OF THESE
═══════════════════════════════════════

**MODULE 1: EXECUTIVE SUMMARY (CMO/VP-ready)**
- Technical health score (0-100) with benchmark vs industry
- Top 3 critical issues causing immediate revenue loss
- Estimated organic revenue at risk from unfixed P0 issues
- 6-month organic projection if roadmap is executed vs. status quo
- Investment required (dev hours) to capture projected upside

**MODULE 2: INDEXATION INTELLIGENCE**
- Crawl budget waste analysis: which URL patterns consume crawl budget without ranking potential
- Indexation efficiency ratio: (ranking pages / total indexed) with benchmark
- Indexation blockers: noindex, canonical, robots.txt, redirect — categorized by intent (intentional vs accidental)
- Priority index inclusions: pages currently excluded that should be indexed, ranked by keyword opportunity
- Priority index exclusions: pages currently indexed that should be excluded (thin content, parameterized URLs, etc.)
- Recommended robots.txt directives and XML sitemap structure

**MODULE 3: CRAWL ARCHITECTURE OPTIMIZATION**
- Crawl depth heatmap: pages deep in the architecture that have ranking potential
- Internal link equity flow: which pages receive the most link equity and whether it matches commercial priority
- Orphan page intervention plan: top 50 orphan pages with recommended internal linking anchors
- Redirect chain elimination: identify all 3+ hop chains and provide clean redirect map
- Crawl efficiency score and budget reallocation recommendations

**MODULE 4: CORE WEB VITALS REMEDIATION PLAN**
For each CWV metric (LCP, INP, CLS):
  - Root cause analysis (specific element, resource, or code pattern causing the issue)
  - Implementation fix with code-level specificity (e.g., "Add fetchpriority='high' to hero img tag")
  - Development effort estimate (story points / hours)
  - Expected score improvement after fix
  - A/B test recommendation (before/after measurement approach)
  
Third-party script audit: which scripts to defer, async, or remove — with GTM implementation guidance
Image optimization plan: WebP/AVIF conversion priority list, lazy loading rules, srcset recommendations
JavaScript optimization: bundle splitting recommendations, unused JS by page type

**MODULE 5: SITE ARCHITECTURE REDESIGN PLAN**
- URL taxonomy audit: inconsistencies, keyword cannibalization at URL level, recommended consolidations
- Information architecture recommendation: optimal 3-click rule implementation for top commercial pages
- Internal linking playbook: anchor text diversity targets, contextual link placement rules by page type
- Hub-and-spoke content clusters: identify missing hub pages and underlinked spoke content
- Click depth reduction plan: top commercial pages deeper than 3 clicks with recommended navigation paths

**MODULE 6: STRUCTURED DATA IMPLEMENTATION ROADMAP**
For each recommended schema type:
  - Page type it applies to
  - Required and recommended properties
  - Example JSON-LD implementation (ready to copy/paste)
  - Rich result eligibility and expected SERP enhancement
  - Implementation priority (P0/P1/P2)

**MODULE 7: E-E-A-T SIGNAL ENHANCEMENT PLAN**
- Content authority gaps: missing author credentials, expertise signals, source citations
- Trust signals: missing trust badges, security certificates, review schema
- Entity establishment: Wikipedia coverage, Knowledge Panel status, brand entity schema
- Author page templates: recommended schema + content structure for E-E-A-T compliance

**MODULE 8: PRIORITIZED ENGINEERING BACKLOG**
Full issue inventory formatted as an engineering sprint backlog:
| Issue ID | Issue | Category | Severity | URLs Affected | Revenue Impact | Dev Hours | Priority | Sprint |
|----------|-------|----------|----------|---------------|----------------|-----------|----------|--------|

Scoring methodology:
  Revenue impact = (affected pages' organic sessions × avg CVR × ACV) × expected ranking improvement
  Priority formula: Revenue Impact Score ÷ Development Hours = ROI Score
  Sprint assignment: P0 = Sprint 1 (week 1-2), P1 = Sprint 2-3 (month 1), P2 = Sprint 4-6 (month 2-3)

**MODULE 9: POST-MIGRATION & MONITORING FRAMEWORK**
- KPIs to track weekly/monthly after fixes are deployed
- Google Search Console monitoring setup (alerts, custom reports)
- Crawl frequency recommendations (when to re-audit)
- Regression testing checklist before any site deployment
- Automated monitoring tools configuration (Screaming Frog scheduled crawls, GSC API alerts)

## Example Input/Output

**Input Example:**
Domain: vaultiq.com (B2B SaaS, revenue intelligence)
CMS: Next.js 14, Contentful
Monthly organic: 142,000 sessions, -8% MoM trend
Critical issues: LCP 4.8s mobile, 2,341 pages "crawled not indexed," 341 orphan pages, migration from HubSpot 14 months ago left 890 redirect chains
Competitors: Clari.com, Gong.io

**Output Example (Module 1 — Executive Summary):**

> **Technical Health Score: 42/100** (Industry benchmark for B2B SaaS: 61/100)
>
> **Top 3 Revenue-Critical Issues:**
> 1. **Mobile LCP 4.8s on top 20 revenue pages** — Google's ranking signal penalty estimated at -18% ranking position loss on mobile SERP. These 20 pages drive 67,000 of your 142,000 monthly sessions. Fixing LCP to <2.5s projected to recover 12,000-18,000 sessions/month (~$340K ARR at $4,200 ACV × 2.1% CVR).
> 2. **2,341 pages "crawled, not indexed"** — Crawl audit shows 1,847 of these are /blog/ posts from the HubSpot migration landing on soft 404s or duplicate canonical signals. Fixing canonicals and cleaning the sitemap should recover indexation for ~400 high-opportunity posts within 60 days.
> 3. **890 redirect chains (3+ hops)** — Inherited from HubSpot migration. Chains average 4.2 hops on top 200 commercial pages, diluting ~35% of inbound link equity before it reaches target pages. Estimated link equity recovery: +15% authority flow to commercial pages.
>
> **6-Month Projection:**
> - Status quo: organic continues -8% MoM → 74,000 sessions by month 6
> - Roadmap executed: +22,000 sessions recovery + 8% growth = 175,000 sessions
> - Revenue delta: $2.1M ARR difference (conservative model)
>
> **Investment Required:** 340 dev hours across 3 sprints

---

**Output Example (Module 4 — LCP Fix for hero image):**

> **Issue:** Hero image on /homepage/, /features/*, /pricing/ not preloaded — LCP element identified as `<img class="hero-bg">` at 2.4MB uncompressed JPEG
>
> **Fix:**
> ```html
> <!-- Add to <head> — critical for LCP -->
> <link rel="preload" as="image" href="/images/hero-bg.webp" fetchpriority="high">
>
> <!-- Update img tag -->
> <img src="/images/hero-bg.webp" 
>      alt="VaultIQ revenue intelligence dashboard" 
>      fetchpriority="high"
>      width="1440" height="680"
>      loading="eager">
> ```
>
> **Also convert to WebP:** Current JPEG is 2.4MB → WebP equivalent ~340KB (-86% size)
> **Expected LCP improvement:** 4.8s → 2.1s (within Good threshold)
> **Dev effort:** 2 hours (image conversion + markup update)
> **A/B measurement:** Deploy to 50% of traffic, measure CrUX LCP improvement in GSC after 28-day data window

## Success Metrics

- Technical health score improves by ≥20 points within 60 days of roadmap execution
- Crawl-not-indexed pages drop by ≥40% after sitemap + canonical fixes (track in GSC Coverage report)
- LCP on top 10 revenue pages reaches <2.5s on mobile (track in CrUX/PSI)
- CLS on all pages drops below 0.1 threshold
- Organic sessions recover to pre-drop baseline within 90 days
- Orphan page count reduced by ≥80% via internal linking sprint
- Redirect chain count reduced to zero 3+ hop chains on commercial pages
- Rich result impressions increase by ≥30% after structured data implementation (track in GSC Enhancements)

## Related Prompts

- [SEO Performance Analytics & Organic Revenue Intelligence Engine](./SEO-Performance-Analytics-&-Organic-Revenue-Intelligence-Engine.md)
- [Keyword Research & Search Intent Mapping Intelligence Engine](./Keyword-Research-&-Search-Intent-Mapping-Intelligence-Engine.md)
- [Digital PR & Link Building Intelligence Engine](../../03_Content-&-Creative/Press-Release-&-PR-Content/Digital-PR-&-Link-Building-Intelligence-Engine.md)
- [Content Audit & SEO Refresh Intelligence Engine](../../03_Content-&-Creative/Blog-&-Article-Writing/Content-Audit-&-SEO-Refresh-Intelligence-Engine.md)

## Integration Tips

- **Screaming Frog + GPT workflow:** Export crawl as CSV → paste column summaries into the Advanced prompt → receive prioritized fix list in minutes
- **Google Search Console API:** Use the Coverage, Performance, and Enhancements endpoints to pull structured data automatically; feed JSON output directly into the prompt
- **Jira/Linear integration:** The Module 8 backlog table is formatted to map directly to Jira tickets — copy into a bulk CSV import with columns: Summary, Priority, Story Points, Sprint, Label
- **Notion SEO Hub:** Paste the executive summary and backlog into a Notion database with Priority, Owner, and Status properties for ongoing tracking
- **Looker Studio dashboard:** Use the KPI list from Module 9 to build a Technical SEO Health dashboard pulling from GSC API + Screaming Frog scheduled crawl exports
- **PageSpeed Insights API:** Automate CWV monitoring by hitting `pagespeedonline.googleapis.com/pagespeedonline/v5/runPagespeed` on your top 20 revenue pages weekly; feed delta reports into the prompt for automated regression alerts
- **Cloudflare / CDN configuration:** Module 3 crawl recommendations map directly to Cloudflare Cache Rules and Page Rules for edge-level crawl control

## Troubleshooting

**Problem:** The AI gives generic recommendations instead of specific code-level fixes.
**Solution:** Feed more specific data — paste the actual PSI JSON output, the exact LCP element HTML, and your tech stack version. The more specific the input, the more specific the output. Include: `"My LCP element HTML is: [paste exact HTML]"` and `"My server response headers are: [paste curl -I output]"`.

**Problem:** The priority scores don't reflect your business reality (e.g., the AI is over-weighting low-traffic pages).
**Solution:** Add a revenue weight override: `"Weight all scoring by this page tier: Tier 1 (10x weight): /pricing/, /demo/, /features/* | Tier 2 (3x weight): /blog/[top 20 URLs] | Tier 3 (1x): all others"`. This forces the model to prioritize your commercial pages even if they have lower raw traffic.

**Problem:** Dev team isn't buying in on the estimated hours — fixes seem underestimated.
**Solution:** Add your tech stack constraints explicitly: `"Our deployment process requires: QA review (4h), staging deploy (2h), production deploy + monitoring (2h) per change. Factor these overhead costs into all effort estimates."` Also ask the model to break each fix into sub-tasks (research, implement, test, deploy) for more granular scoping.

## Version History
- v1.0: Initial creation (auto-generated)
