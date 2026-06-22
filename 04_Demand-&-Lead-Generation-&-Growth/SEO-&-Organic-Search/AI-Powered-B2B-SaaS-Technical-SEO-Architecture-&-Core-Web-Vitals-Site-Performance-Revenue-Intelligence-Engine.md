# AI-Powered B2B SaaS Technical SEO Architecture & Core Web Vitals Site Performance Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** technical-seo, core-web-vitals, site-performance, b2b-saas, crawlability, indexation, schema-markup, organic-search, page-speed, revenue-attribution

## Overview
Designs and executes a complete technical SEO implementation program for B2B SaaS — including crawl architecture optimization, Core Web Vitals remediation, schema markup deployment, JavaScript rendering fixes, and internal link authority flow — producing a prioritized technical roadmap tied directly to ranking recovery, organic traffic growth, and pipeline revenue impact. Use when organic rankings are underperforming despite strong content, when a site migration or platform change has caused traffic loss, or when building a technically flawless SEO foundation to maximize returns from content and link building investments.

## Quick Copy-Paste Version

You are a senior B2B SaaS technical SEO architect. Perform a complete technical SEO assessment and implementation plan for [Your SaaS Website] — a [brief product description] targeting [ICP: job title/department] at [company size/type] companies.

Produce a prioritized technical SEO implementation plan covering:

1. CRAWL & INDEXATION ARCHITECTURE:
   - Identify pages that should be indexed vs. blocked (robots.txt, noindex, canonical conflicts)
   - Audit XML sitemap for accuracy: only include indexable, canonical, 200-status pages
   - Detect crawl traps: infinite pagination, faceted navigation, parameter duplication
   - Identify crawl budget waste: thin pages, duplicate content, redirect chains consuming bot crawl allocation
   - Priority fix: Consolidate duplicate URL variants via canonical tags and 301 redirects

2. CORE WEB VITALS REMEDIATION:
   - LCP (Largest Contentful Paint): Identify the LCP element on key landing pages; prescribe fixes (preload LCP image, upgrade hosting/CDN, eliminate render-blocking resources)
   - CLS (Cumulative Layout Shift): Identify unstable elements (ads, embeds, dynamic content without reserved dimensions); prescribe CSS fixes
   - INP (Interaction to Next Paint): Identify JavaScript execution blocking main thread; prescribe code splitting and defer/async strategies
   - Target: LCP < 2.5s, CLS < 0.1, INP < 200ms on all pages generating organic pipeline

3. SITE ARCHITECTURE & INTERNAL LINKING:
   - Audit URL structure for logical hierarchy reflecting keyword intent clusters
   - Identify orphaned pages (no internal links pointing to them) — these rank poorly regardless of content quality
   - Design internal linking architecture: pillar pages → cluster pages → supporting pages, with keyword-rich anchor text
   - Identify pages accumulating external link equity but failing to pass authority internally to priority ranking pages

4. SCHEMA MARKUP DEPLOYMENT:
   - Organization schema: name, logo, sitelinks, social profiles (required for branded search panel)
   - SoftwareApplication schema on product pages: operating system, application category, aggregate rating
   - FAQPage schema on all blog posts with Q&A sections (increases SERP real estate)
   - BreadcrumbList schema on all pages (improves crawl efficiency and SERP display)
   - HowTo schema on tutorial/guide content targeting procedural search queries

5. JAVASCRIPT & RENDERING:
   - Identify critical content rendered client-side (invisible to Googlebot without JavaScript execution)
   - Prescribe server-side rendering (SSR) or static generation for all SEO-critical pages
   - Verify Google Search Console's URL Inspection Tool confirms correct rendered content vs. raw HTML

6. TECHNICAL QUICK WINS (implement within 30 days):
   - Fix all 404 errors to returning content or 301 to relevant live pages
   - Eliminate redirect chains (A→B→C should become A→C)
   - Compress all images to WebP format; implement lazy loading for below-fold images
   - Add missing title tags and meta descriptions to pages missing them
   - Verify HTTPS security: no mixed content warnings, valid SSL certificate, HSTS headers active

Output a prioritized implementation roadmap with: critical fixes (blocking ranking), high-impact improvements (ranking acceleration), and optimization (compound gains) — each with estimated engineering effort and projected ranking impact.

## Advanced Customizable Version

ROLE: You are a B2B SaaS technical SEO architect with 12+ years optimizing complex SaaS websites for organic search performance. You understand that technical SEO is the foundation that determines whether content and link investments compound or leak — a single crawl error, JavaScript rendering issue, or Core Web Vitals failure can suppress dozens of pages simultaneously. You build systems that identify root causes, not symptoms, and you prioritize fixes by revenue impact, not technical severity alone.

SITE CONTEXT:
- Website URL: [Your domain, e.g., acme.com]
- CMS/Platform: [e.g., Next.js, WordPress, Webflow, HubSpot CMS, custom React]
- Monthly organic sessions (current): [e.g., 18,000 sessions/month]
- Primary organic revenue KPI: [e.g., demo requests, free trial signups, MQL volume]
- Known issues or recent changes: [e.g., site migration in Q3, new blog platform launched, traffic dropped 35% after update]
- Target ICP for organic: [e.g., VP of Engineering, CTO at Series B-D SaaS companies]
- Priority keyword categories: [e.g., "best [category] software", "[use case] tools", "[problem] solution"]
- Engineering team capacity: [e.g., 2 frontend engineers, 1 sprint per month for SEO work]
- Current toolstack: [e.g., Google Search Console, Screaming Frog, Ahrefs, GA4, Vercel hosting]

OBJECTIVE: Identify and remediate every technical SEO issue suppressing organic performance, implement a crawl-efficient site architecture, deploy revenue-accelerating structured data, and establish a recurring technical SEO maintenance system — all executable by AI agents with minimal engineering dependency.

DELIVERABLE 1 — TECHNICAL AUDIT PRIORITIZATION MATRIX:

Categorize every issue by: Impact (High/Medium/Low) × Effort (Hours/Days/Sprint) × Root Cause Type

CRITICAL (P0 — Fix within 7 days, ranking recovery at risk):
- Indexation blockers: noindex on money pages, robots.txt blocking CSS/JS, sitemap listing non-canonical URLs
- Duplicate content at scale: parameter-generated duplicates, trailing slash / non-trailing slash conflicts, www vs. non-www
- Broken internal link clusters creating crawl dead-ends on pillar pages
- Core Web Vitals failures (CWV score "Poor") on pages generating >20% of organic pipeline

HIGH IMPACT (P1 — Fix within 30 days, ranking acceleration):
- Missing or duplicate title tags on pages ranking 4-20 for target keywords (title tag directly influences CTR)
- Thin content pages diluting crawl budget (< 300 words, no unique value, not excluded from index)
- Redirect chains (3+ hops) on pages receiving external backlinks (link equity loss at each hop)
- Missing schema markup on product pages, blog posts with Q&A sections, and pricing pages
- Internal linking gaps: pages with external backlinks not linked internally to priority conversion pages

OPTIMIZATION (P2 — Fix within 90 days, compound gains):
- Image optimization: uncompressed images > 100KB above the fold
- Lazy loading implementation for below-fold media
- Font preloading for critical typography
- Third-party script audit: identify scripts adding >200ms to INP scores
- Hreflang implementation if targeting multiple language/region markets
- Structured logging for 404 error detection and auto-remediation in CI/CD pipeline

DELIVERABLE 2 — CORE WEB VITALS REMEDIATION PLAN:

For each of the top 10 organic traffic pages (pull from Google Search Console > Performance > Pages):

Page: [URL]
Current Scores: LCP [Xs], CLS [X], INP [Xms] — Status: [Good/Needs Improvement/Poor]

LCP Remediation for [URL]:
- LCP element: [e.g., hero image, H1 text block, above-fold video]
- Root cause: [e.g., image not preloaded, hosted on slow origin, render-blocked by CSS]
- Fix: Add `<link rel="preload" as="image" href="[LCP image URL]">` in `<head>`; migrate hero image to CDN (Cloudflare Images or Imgix); defer non-critical CSS
- Engineering effort: 2-3 hours
- Expected LCP improvement: 1.8s → 1.1s (Good threshold: < 2.5s)

CLS Remediation for [URL]:
- Shifting elements: [e.g., banner ad loaded without reserved space, dynamic CTA appearing after page load]
- Fix: Set explicit width/height attributes on all images and video embeds; reserve space for dynamic ad slots with CSS min-height; move CTA injection to SSR
- Engineering effort: 4 hours
- Expected CLS improvement: 0.18 → 0.05

INP Remediation for [URL]:
- Heavy JS tasks: [e.g., analytics initialization, chat widget, A/B testing script blocking main thread]
- Fix: Move Intercom/Drift chat initialization to `requestIdleCallback`; async-load Google Tag Manager; implement Partytown for third-party script isolation
- Engineering effort: 1 sprint (3-5 days for Partytown integration)
- Expected INP improvement: 380ms → 140ms

DELIVERABLE 3 — CRAWL ARCHITECTURE OPTIMIZATION:

Crawl Budget Analysis (for sites with > 10,000 indexable URLs):
- Total crawlable URLs: [from Screaming Frog or log file analysis]
- Pages Google should crawl: [money pages + supporting content]
- Pages wasting crawl budget: [faceted navigation, session-parameterized URLs, duplicate paginated archives]

URL Consolidation Plan:
- Parameter handling: Add `?ref=`, `?utm_source=`, and `?sort=` parameters to Google Search Console's URL Parameter tool as "No Googlebot crawling" or handle via canonical
- Faceted navigation: noindex all faceted combinations that don't target unique keywords; canonical faceted pages to their parent category
- Pagination: Implement `rel="next"` / `rel="prev"` (deprecated but still crawl-signal valuable) + ensure paginated pages only indexed if they contain unique content
- Duplicate variants: Choose canonical URL pattern (trailing slash or not, www or not) and 301 all variants to canonical

XML Sitemap Architecture:
- Separate sitemaps by content type: /sitemap-pages.xml, /sitemap-blog.xml, /sitemap-landing-pages.xml
- Include only: 200-status, indexed (not noindex), canonical URLs
- Update dynamically: trigger sitemap rebuild via CI/CD whenever new content publishes
- Submit and monitor: Google Search Console > Sitemaps > verify "Discovered URLs" count matches actual indexable content

DELIVERABLE 4 — SCHEMA MARKUP IMPLEMENTATION LIBRARY:

Copy-paste JSON-LD blocks for each schema type (implement via Google Tag Manager or CMS template injection):

Organization Schema (sitewide, inject in `<head>`):
{
  "@context": "https://schema.org",
  "@type": "Organization",
  "name": "[Company Name]",
  "url": "https://[yourdomain].com",
  "logo": "https://[yourdomain].com/images/logo.png",
  "sameAs": [
    "https://www.linkedin.com/company/[handle]",
    "https://twitter.com/[handle]",
    "https://g2.com/products/[product-name]/reviews"
  ],
  "contactPoint": {
    "@type": "ContactPoint",
    "contactType": "sales",
    "url": "https://[yourdomain].com/demo"
  }
}

SoftwareApplication Schema (product pages):
{
  "@context": "https://schema.org",
  "@type": "SoftwareApplication",
  "name": "[Product Name]",
  "applicationCategory": "BusinessApplication",
  "operatingSystem": "Web",
  "offers": {
    "@type": "Offer",
    "price": "0",
    "priceCurrency": "USD",
    "description": "Free trial available"
  },
  "aggregateRating": {
    "@type": "AggregateRating",
    "ratingValue": "[Your G2/Capterra rating]",
    "reviewCount": "[Number of reviews]"
  }
}

FAQPage Schema (blog posts with Q&A sections — generates rich snippet accordion in SERP):
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [{
    "@type": "Question",
    "name": "[Q1 from post]",
    "acceptedAnswer": {
      "@type": "Answer",
      "text": "[Concise answer — 40-60 words]"
    }
  }, {
    "@type": "Question",
    "name": "[Q2 from post]",
    "acceptedAnswer": {
      "@type": "Answer",
      "text": "[Concise answer]"
    }
  }]
}

DELIVERABLE 5 — JAVASCRIPT RENDERING VERIFICATION PROTOCOL:

For each priority ranking page, verify using Google Search Console URL Inspection → "View Tested Page" → "Screenshot" tab:

Verification Checklist:
- [ ] Page title and H1 visible in rendered screenshot
- [ ] Navigation links rendered and crawlable (not loaded via client-side router only)
- [ ] Primary body content visible (not placeholder "Loading..." state)
- [ ] Internal links to cluster pages present in rendered HTML
- [ ] Structured data detected by Rich Results Test

If content appears in JavaScript-rendered view but not in raw HTML:
- Next.js sites: Migrate pages from CSR (client-side rendering) to SSR (`getServerSideProps`) or SSG (`getStaticProps`)
- React SPA sites: Implement prerendering via Prerender.io or migrate to Next.js/Nuxt.js
- WordPress with heavy plugins: Audit plugins using Chrome DevTools Network tab; identify which JS files delay content paint

DELIVERABLE 6 — TECHNICAL SEO MAINTENANCE SYSTEM:

Automated Monitoring (set up once, runs continuously):

Weekly AI-Powered Technical Digest:
- Source: Screaming Frog scheduled crawl → export CSV → AI analysis → Slack/email report
- Report includes: New 404 errors, pages newly blocked by robots.txt, new duplicate title tag clusters, Core Web Vitals regressions (via CrUX API)
- AI prompt for weekly digest: "Analyze this Screaming Frog CSV export and identify: (1) new issues vs. last week's baseline, (2) top 3 highest-impact new issues ranked by estimated organic traffic impact, (3) issues on pages generating demo requests or free trial signups. Output as a prioritized Slack message with emoji severity indicators."

Monthly Technical SEO Review:
- Google Search Console: Coverage report → new errors, index coverage drops, manual actions
- Core Web Vitals: CrUX dashboard → page-level CWV trend by traffic segment (mobile vs. desktop)
- Crawl efficiency: Google Search Console → Crawl Stats → daily crawl rate trend; alert if Googlebot crawl rate drops >20%
- Structured data: Rich Results Test on all schema-enabled pages; fix any validation errors blocking rich snippet eligibility

CI/CD Integration (for engineering teams):
- Pre-deploy check: Automated Lighthouse CI run on staging before every production deploy
- Threshold gates: Block deploy if LCP degrades >500ms or CLS exceeds 0.15 vs. baseline
- Post-deploy validation: Automated sitemap ping to Google after content deployment
- 404 monitoring: Daily check of GA4 + server logs for 404 errors generating > 10 sessions/month → auto-ticket creation in Jira/Linear

CONSTRAINTS:
- All technical recommendations must be implementable without rebuilding the site from scratch — prescribe the minimal change for maximum impact
- Engineering effort estimates must be realistic for a 2-3 person frontend team with competing product priorities
- Schema markup must comply with Google's structured data guidelines — no schema for content not visible on the page
- Core Web Vitals targets must be met for both mobile and desktop (mobile is primary for Google ranking)
- All redirect recommendations must be tested in staging before production deployment to prevent redirect loop risks
- Maintenance system must be automatable with existing toolstack (no new paid tools required beyond what's already in use)

OUTPUT FORMAT: Deliver as:
1. Executive summary: 3 critical issues identified, estimated traffic recovery if fixed (X% organic sessions)
2. P0 fix checklist (7-day sprint ready for developer handoff)
3. P1 improvement backlog (30-day roadmap with effort estimates)
4. Schema markup library (copy-paste JSON-LD blocks for each page type)
5. Core Web Vitals remediation cards (one per priority page)
6. Automated monitoring setup guide (one-time setup instructions)

## Example Input/Output

**Input Example:**
- Website: stackflow.io — AI-powered workflow automation platform for RevOps teams
- Platform: Next.js 13 (App Router), hosted on Vercel
- Monthly organic sessions: 12,400 (down 28% since migration from WordPress 4 months ago)
- Primary KPI: Demo requests (current: 47/month from organic, target: 85/month)
- Known issues: Migration moved blog from /blog to /resources; old URLs returning 404
- Priority keywords: "workflow automation software" (pos. 11), "RevOps automation" (pos. 8), "revenue operations tools" (pos. 19)
- Engineering: 2 frontend engineers, 1 sprint/month available for SEO
- Tools: Google Search Console, Screaming Frog, Ahrefs, GA4, Vercel Analytics

**Output Example:**

**Executive Summary:**
3 critical issues identified, collectively explaining ~70% of post-migration traffic loss:

1. **Mass 404 cascade:** 847 old /blog URLs returning 404 with zero 301 redirects implemented. These pages held 340+ referring domains — link equity is currently unresolved. Estimated traffic recovery: +35-40% organic sessions within 60 days of 301 implementation.

2. **Client-side rendering on product pages:** Stackflow's feature pages (/features/*, /integrations/*) render via React client components — Googlebot sees empty `<div id="__next">` containers. These pages have zero organic presence despite targeting high-intent keywords. Fix: Convert to Server Components (Next.js App Router default behavior, 0 engineering days for pages not using client hooks).

3. **LCP failure on homepage (3.8s):** Hero section uses unoptimized 2.1MB PNG loaded without preload hint. LCP element is the hero image. Fix: Convert to WebP (Squoosh.app, 45 minutes), add preload tag, serve via Vercel's Image Optimization API.

**P0 Fix Checklist (7-day sprint):**

Day 1-2 (No-code, SEO manager):
- [ ] Export all old /blog URLs from Wayback Machine / Ahrefs crawl of old site
- [ ] Map old /blog/[slug] → new /resources/[slug] (bulk redirect map in CSV)
- [ ] Implement 301 redirects in next.config.js redirects array (or Vercel redirect rules)
- [ ] Verify with Screaming Frog: all old blog URLs now return 301 → 200

Day 3-4 (1 frontend engineer, ~6 hours):
- [ ] Audit /features/* and /integrations/* pages: identify any using 'use client' directive unnecessarily
- [ ] Remove 'use client' from pages that only use static data (no browser APIs, no useState/useEffect for content)
- [ ] Verify with URL Inspection: rendered content now matches visual design

Day 5 (Design + engineer, 3 hours):
- [ ] Convert hero image from PNG to WebP (Squoosh.app)
- [ ] Add `<link rel="preload" as="image" href="/hero.webp">` to layout.tsx head
- [ ] Replace `<img>` with Next.js `<Image>` component (automatic sizing, lazy loading, WebP conversion)
- [ ] Verify LCP improvement in PageSpeed Insights: target < 2.5s

**Schema Markup Deployed (Week 2):**

Homepage Organization schema: ✅ Ready to inject via Google Tag Manager
/features/* SoftwareApplication schema: ✅ Ready with G2 rating aggregation (4.7/5, 312 reviews)
/resources/[slug] BlogPosting schema: ✅ Template configured for CMS auto-injection
FAQPage schema: ✅ Added to 14 blog posts with Q&A sections → projected 15-20% CTR lift on SERP

**30-Day Outcome Projection:**
- Organic sessions: 12,400 → estimated 16,800-17,500 (+35-40%)
- Demo requests from organic: 47 → estimated 62-70 (+32-49%)
- Pages indexed: 340 → 680 (blog migration resolution unlocks second half of content library)
- Core Web Vitals: Homepage from Poor (LCP 3.8s) → Good (LCP ~1.2s) within 28-day CrUX rolling window

## Success Metrics

- **Crawl coverage recovery:** Pages indexed in Google Search Console increases to ≥ 95% of intentionally indexable pages within 60 days
- **Core Web Vitals:** All pages generating > 5% of organic pipeline achieve "Good" status (LCP < 2.5s, CLS < 0.1, INP < 200ms) within 90 days
- **Organic session recovery:** Sites with post-migration traffic drops recover ≥ 80% of lost traffic within 60-90 days of P0 fixes
- **Crawl efficiency:** Screaming Frog crawl shows < 5% of crawled URLs are redirect chains (2+ hops) or returning 4xx errors
- **Rich snippet eligibility:** ≥ 80% of schema-enabled pages pass Google Rich Results Test with zero validation errors
- **Demo requests from organic:** Organic-attributed pipeline KPI improves ≥ 25% within 90 days of full technical remediation
- **Redirect resolution:** < 48 hours from 301 implementation to Googlebot re-crawl and indexation (verify via URL Inspection)

## Related Prompts

- [AI-Powered B2B SaaS Organic Search Demand Generation Architecture & Pipeline Revenue Intelligence Engine](./AI-Powered-B2B-SaaS-Organic-Search-Demand-Generation-Architecture-&-Pipeline-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Link Building & Digital Authority Architecture & Domain Rating Revenue Intelligence Engine](./AI-Powered-B2B-SaaS-Link-Building-&-Digital-Authority-Architecture-&-Domain-Rating-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B GEO-Optimized Long-Form Content Architecture & AI Search Citation Capture Intelligence Engine](../../03_Content-&-Creative/Blog-&-Article-Writing/AI-Powered-B2B-GEO-Optimized-Long-Form-Content-Architecture-&-AI-Search-Citation-Capture-Intelligence-Engine.md)
- [AI-Powered B2B Technical SEO Audit & Site Health Revenue Impact Intelligence Engine](../../05_Analytics-&-Performance/SEO-&-Organic-Search-Analytics/AI-Powered-B2B-Technical-SEO-Audit-&-Site-Health-Revenue-Impact-Intelligence-Engine.md)

## Integration Tips

- **Google Search Console API:** Pull Coverage report and Core Web Vitals data programmatically → feed into AI weekly to auto-generate prioritized fix recommendations without manual GSC login
- **Screaming Frog + AI:** Schedule weekly crawls → export all tabs as CSV → pipe into GPT-4o or Claude with prompt: "Identify the top 10 highest-impact technical issues from this crawl data, ranked by estimated organic traffic impact" → post report to Slack #seo-alerts channel via Zapier
- **Vercel / Netlify:** Enable Lighthouse CI plugin in your CI/CD pipeline — automatically blocks deploys that would regress Core Web Vitals below threshold, preventing regressions from shipping
- **Google Tag Manager:** Inject all JSON-LD schema markup via GTM Custom HTML tags — enables non-engineers to update schema without code deploys; trigger schema per page template using GTM variables
- **Ahrefs / Semrush Site Audit:** Run weekly automated site audits → webhook to Linear or Jira to auto-create tickets for new issues above severity threshold; assign to engineering sprint automatically
- **PageSpeed Insights API:** Integrate into weekly marketing report — pull CWV scores for top 20 organic landing pages automatically; flag any that regress to "Needs Improvement" for immediate action
- **Cloudflare Images / Vercel Image Optimization:** Enable at the CDN layer — automatically serves WebP to supporting browsers and resizes images to viewport without per-image engineering work; single configuration change eliminates most LCP failures
- **Prerender.io / Rendertron:** For React SPAs or Vue apps where converting to SSR is not feasible in the short term — implement dynamic rendering as a bridge solution, serving pre-rendered HTML to Googlebot while serving SPA to human users

## Troubleshooting

**Problem:** Site migrated to new platform 90 days ago and traffic is still down despite implementing 301 redirects.
**Solution:** 301 redirects alone don't guarantee immediate recovery — Googlebot must re-crawl each redirected URL, process the 301, re-index the new URL, and the new URL must pass all quality signals. Check three things: (1) Are the 301s chaining? Old URL → intermediate URL → new URL loses link equity at each hop — collapse to single-hop. (2) Does the destination page match the original in content quality and topical relevance? Redirecting /blog/salesforce-crm-tips to /resources/crm-software loses topical signal — match content themes. (3) Pull Google Search Console → Coverage → "Redirect error" tab — if redirects are appearing there, Googlebot is detecting redirect loops or chains it can't resolve.

**Problem:** Core Web Vitals pass in PageSpeed Insights (lab data) but Google Search Console still shows "Poor" for CWV.
**Solution:** PSI lab data and Search Console CWV use different data sources. PSI uses a simulated, controlled test environment (Lighthouse). Search Console uses Chrome User Experience Report (CrUX) — real user data from Chrome browsers, averaged over a 28-day rolling window. Lab data can show "Good" while real users experience "Poor" due to: (1) Real users on slower mobile networks (3G/4G in emerging markets), (2) Pages that pass in isolation but are slow when loaded after other pages in a session (cached state differs), (3) Third-party scripts that perform differently in real user sessions vs. lab. Fix: Use Web Vitals JavaScript library to measure real user CWV in your analytics events — send to GA4 custom events to see actual user CWV distribution by device type and connection speed, then prioritize fixes for the lowest-performing segments.

**Problem:** Schema markup deployed but no rich snippets appearing in search results after 6 weeks.
**Solution:** Schema eligibility and activation are separate. Validate using three checks: (1) Google Rich Results Test — paste your page URL; if it shows validation errors (red/yellow), fix those first (errors prevent eligibility entirely). (2) Verify the schema content matches visible page content — Google won't display FAQ rich snippets if the Q&A text in schema differs from what appears on the page (they call this "misleading structured data"). (3) Check if your page ranks in top 10 for the target query — Google only shows rich snippets for pages already ranking well; if you're on page 3, earn the ranking first. For FAQ schema specifically: ensure questions are genuinely informational (not marketing copy phrased as questions) and answers are concise (under 300 words per answer for best rich snippet display).

## Version History
- v1.0: Initial creation (auto-generated)
