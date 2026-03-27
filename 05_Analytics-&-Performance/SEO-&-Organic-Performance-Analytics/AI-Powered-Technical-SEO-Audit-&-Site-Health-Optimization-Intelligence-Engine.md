# AI-Powered Technical SEO Audit & Site Health Optimization Intelligence Engine - Identify Every Crawlability, Indexing, and Performance Issue Killing Your Organic Rankings

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** technical SEO, site audit, Core Web Vitals, crawlability, indexing, page speed, schema markup, B2B SaaS, organic growth, site health

## Overview
Transforms your site URL, CMS, and technical configuration into a complete technical SEO audit with prioritized remediation roadmap — covering crawlability, indexing, Core Web Vitals, site architecture, JavaScript rendering, structured data, and mobile-first compliance. Use it when organic traffic has plateaued or declined unexpectedly, before a major site migration, when launching a new domain, or as part of a quarterly SEO health review.

## Quick Copy-Paste Version

You are a senior technical SEO engineer. Conduct a comprehensive technical SEO audit for my website.

Site URL: [e.g., https://clearpath.io]
CMS / tech stack: [e.g., Next.js, hosted on Vercel / WordPress on WP Engine / Webflow]
Site size (approx. pages): [e.g., ~850 indexed pages]
Current organic traffic trend: [e.g., dropped 35% over last 3 months / flat / growing slowly]
Top 3 pages by traffic: [e.g., /blog/project-management-software, /pricing, /integrations]
Known issues (if any): [e.g., site migration 6 weeks ago / recently switched to JavaScript rendering / added hreflang for EU expansion]
Google Search Console access: [yes/no — if yes, describe any errors flagged]

Deliver a complete technical SEO audit across these 8 pillars:

1. CRAWLABILITY & INDEXING — robots.txt analysis, XML sitemap health, canonical tag issues, noindex tags, redirect chains, crawl budget waste, orphan pages

2. CORE WEB VITALS & PAGE EXPERIENCE — LCP, CLS, INP diagnosis, server response time (TTFB), render-blocking resources, image optimization, caching strategy

3. SITE ARCHITECTURE & URL STRUCTURE — URL hygiene, directory depth, faceted navigation issues, pagination handling, parameter management

4. JAVASCRIPT RENDERING — Client-side rendering risks, dynamic content indexing, lazy-load content visibility to Googlebot

5. STRUCTURED DATA & SCHEMA — Missing or broken schema types, opportunities for rich results (FAQ, HowTo, Product, Article, BreadcrumbList)

6. MOBILE-FIRST INDEXING — Mobile usability, responsive design compliance, touch target sizing, font legibility, content parity between mobile/desktop

7. INTERNAL LINKING — Link equity flow, orphan pages, over-optimized anchor text, crawl depth of key pages, broken internal links

8. INTERNATIONAL SEO (if applicable) — hreflang implementation, geo-targeting, ccTLD vs. subdirectory structure

For each pillar: severity rating (Critical / High / Medium / Low), specific issues found, remediation action with implementation steps, estimated effort (hours), and expected ranking impact.

Close with a PRIORITIZED 90-DAY REMEDIATION ROADMAP sorted by: (Ranking Impact × Fix Difficulty⁻¹).

## Advanced Customizable Version

ROLE: You are a Principal Technical SEO Engineer and Site Architecture Specialist with 12+ years optimizing large-scale B2B SaaS, e-commerce, and enterprise web properties. You have deep expertise in Google's crawling and rendering infrastructure, Core Web Vitals optimization, JavaScript SEO, and migration-proof site architecture. Your audits have consistently recovered 40–120% organic traffic for sites hit by algorithm updates or technical debt.

MISSION: Conduct a full-spectrum technical SEO audit for the company below. Produce a consultant-grade deliverable — specific, evidence-based, prioritized — that a developer and SEO manager can execute without additional discovery.

═══════════════════════════════════════
SITE PROFILE
═══════════════════════════════════════
Company / site name: [e.g., Clearpath — B2B SaaS project management for construction teams]
Primary domain: [e.g., https://clearpath.io]
CMS / rendering tech: [e.g., Next.js 14 with ISR / WordPress 6.x / Webflow / HubSpot CMS]
Hosting / CDN: [e.g., Vercel + Cloudflare / AWS + Fastly / WP Engine]
Site size: [e.g., ~1,200 URLs, ~400 indexable pages]
Target market geography: [e.g., US, UK, Canada — English only / multi-language EU expansion]
Primary conversion page: [e.g., /demo / /free-trial / /pricing]
Google Search Console errors (list top issues): [e.g., 142 "Page with redirect" / 38 "Crawled - not indexed" / 14 "Soft 404"]
Recent site changes: [e.g., migrated from HubSpot to Webflow 8 weeks ago / added React hydration for blog in January / redesigned /pricing page last month]
Known symptoms: [e.g., organic traffic down 28% since migration / featured snippets lost / demo page dropped from #3 to #11]

═══════════════════════════════════════
CRAWLABILITY & INDEXING AUDIT
═══════════════════════════════════════
Analyze and diagnose:

**robots.txt:**
- Are any critical pages accidentally blocked? (pricing, demo, blog, product pages)
- Is Googlebot blocked from CSS/JS files needed for rendering?
- Are third-party scripts unnecessarily crawled?
- Crawl-delay directives that may throttle Googlebot?

**XML Sitemap:**
- Are all indexable pages included? Any noindex pages accidentally in sitemap?
- Are sitemaps < 50,000 URLs / < 50MB?
- Sitemap index file vs. single sitemap — which is appropriate at this scale?
- Last modified dates accurate? Do they update on content change?

**Indexing Status:**
- "Crawled - currently not indexed" clusters: identify likely cause (thin content, duplicate content, low PageRank, crawl budget, internal links insufficient)
- "Discovered - currently not indexed": crawl budget exhaustion indicators
- Soft 404s: pages returning 200 status but delivering thin/empty content
- Canonical confusion: self-referencing vs. consolidating canonicals — misuse patterns

**Redirect Architecture:**
- Identify redirect chains (A→B→C = crawl waste + PageRank dilution)
- Redirect loops
- 302s where 301s should be used
- Post-migration redirect coverage gaps

**Crawl Budget Optimization:**
- Faceted navigation URL explosion (filters, sorting, session IDs)
- Infinite scroll / pagination generating duplicate content
- Low-value pages consuming crawl budget (tag pages, author archives, search result pages)

═══════════════════════════════════════
CORE WEB VITALS & PAGE EXPERIENCE AUDIT
═══════════════════════════════════════
Diagnose and prescribe fixes for:

**Largest Contentful Paint (LCP) — target: < 2.5s**
- Hero image: WebP/AVIF format? Preloaded? Correctly sized for viewport?
- LCP element identified (image vs. text block vs. video thumbnail)?
- Server response time (TTFB): < 800ms? If not, root cause (server, no CDN, no caching)?
- Render-blocking resources: CSS/JS in <head> delaying LCP paint?
- Third-party scripts (chat, analytics, A/B testing) deferrable?

**Cumulative Layout Shift (CLS) — target: < 0.1**
- Images without explicit width/height attributes causing reflow?
- Web fonts causing FOIT/FOUT layout shift? (font-display: swap usage?)
- Ads, embeds, or iframes without reserved space?
- Dynamic content injected above-the-fold after initial load?
- Cookie consent banners / popups causing CLS?

**Interaction to Next Paint (INP) — target: < 200ms**
- Heavy JavaScript bundles blocking main thread?
- Long tasks (>50ms) in performance profile?
- Third-party scripts competing for main thread?
- Event handler optimization opportunities?

**Additional Page Experience Signals:**
- HTTPS: All pages served over TLS? Mixed content warnings?
- Intrusive interstitials: Full-screen popups on mobile that may trigger Google penalty?
- Safe Browsing: Any malware/phishing flags?

═══════════════════════════════════════
SITE ARCHITECTURE & URL STRUCTURE AUDIT
═══════════════════════════════════════
Evaluate:

**URL Hygiene:**
- URLs: short, descriptive, lowercase, hyphens not underscores?
- Session IDs, tracking parameters, or UTM parameters creating duplicate URLs?
- Trailing slash consistency (pick one, redirect the other)
- Special characters, encoded characters in URLs
- Dynamic URLs vs. static URL patterns

**Directory Structure & Crawl Depth:**
- Any high-value pages more than 3 clicks from the homepage?
- Blog / resource posts buried 5+ levels deep?
- Category / subcategory hierarchy creating orphan leaves?

**Faceted Navigation:**
- E-commerce-style filters generating millions of low-value URLs?
- Parameter-based URLs for sort, filter, page — blocked via robots or canonical?
- Infinite scroll: does Googlebot see paginated URLs?

**Pagination:**
- rel="next"/rel="prev" (deprecated but still useful signal for link equity distribution)?
- Paginated content canonical strategy (canonical to page 1 vs. self-referential)?

═══════════════════════════════════════
JAVASCRIPT RENDERING AUDIT
═══════════════════════════════════════
Diagnose rendering risks:

**Rendering Architecture:**
- Is the site Server-Side Rendered (SSR), Client-Side Rendered (CSR), or Static Site Generated (SSG)?
- For CSR/hybrid: is critical content (title, H1, body, links, CTAs) in the initial HTML served or dependent on JS execution?
- Google's two-wave rendering: any content only visible after JS execution?

**Dynamic Content Indexability:**
- Internal links rendered via JavaScript — are they crawlable? (innerHTML links vs. proper <a href> tags)
- Lazy-loaded images: do they use loading="lazy" (indexable) or JS-triggered intersection observer (potentially missed)?
- API-fetched content (product descriptions, reviews, pricing) — does Googlebot receive it?

**Testing Protocol:**
- Google Search Console URL Inspection → "View Tested Page" → compare DOM screenshot vs. rendered HTML
- Fetch as Googlebot vs. raw HTML comparison methodology
- Signs of JavaScript rendering failures in GSC (pages indexed but with empty/minimal content)

**SPA / React / Vue / Angular Specific:**
- History API pushState navigation: are page titles and canonical tags updating on route change?
- Pre-rendering / static generation for key landing pages?
- Hydration errors causing content flicker or CLS?

═══════════════════════════════════════
STRUCTURED DATA & SCHEMA AUDIT
═══════════════════════════════════════
Identify gaps and errors:

**Current Schema Implementation:**
- Organization schema: name, logo, sameAs social profiles, address, contact
- WebSite schema with SearchAction (sitelinks searchbox)
- BreadcrumbList on all inner pages?
- Article / BlogPosting on all blog posts?
- FAQPage on FAQ sections (high value for AI Overview appearances)
- Product / SoftwareApplication on product pages?
- Review / AggregateRating if pulling in G2/Capterra scores?
- HowTo schema on tutorial/guide content?
- Event schema on webinar/event pages?

**Common Schema Errors:**
- Missing required properties (name, url, author on Article)
- Incorrect type nesting (Product inside Article)
- Schema not matching visible page content (policy violation)
- Duplicate schema blocks for the same entity
- JSON-LD in <body> vs. <head> (both valid, but <head> preferred)

**Rich Result Opportunities:**
- Which pages have highest potential for SERP enhancements with schema addition?
- Estimated CTR uplift per rich result type

═══════════════════════════════════════
MOBILE-FIRST INDEXING AUDIT
═══════════════════════════════════════
Verify compliance:

**Content Parity:**
- Is all text content (body copy, headings, structured data) identical between mobile and desktop rendering?
- Images: same ALT text on mobile? Same images loaded?
- Navigation: mobile hamburger menu — are navigation links in the DOM and crawlable?

**Usability:**
- Touch targets: minimum 48px × 48px with 8px spacing
- Font size: minimum 16px body text, no zoom required
- Viewport meta tag: <meta name="viewport" content="width=device-width, initial-scale=1">
- Horizontal scrolling: none on standard mobile viewports
- Interstitials: no full-page popups on mobile landing (Google penalty risk)

**Mobile Page Speed:**
- Does mobile CWV score differ significantly from desktop? (It should be the indexed version's score)

═══════════════════════════════════════
INTERNAL LINKING AUDIT
═══════════════════════════════════════
Map and optimize link equity flow:

**Link Equity Distribution:**
- Which pages have the highest internal PageRank concentration? Is it flowing to highest-priority conversion pages?
- Revenue-critical pages (pricing, demo, product features): how many internal links do they receive? From which page types?
- Blog posts: do they link to product/pricing pages with commercial-intent anchor text?

**Orphan Page Detection:**
- Pages with 0 internal links pointing to them (only discoverable via sitemap)
- New content published but not linked from any existing page — estimate Google discovery delay

**Anchor Text:**
- Over-optimized exact-match anchor text on internal links (soft spam risk)
- Generic "click here" / "learn more" anchors wasting topical signal
- Anchor text distribution — does it match keyword strategy?

**Broken Internal Links:**
- 404s from internal links (crawl waste + poor UX)
- Links pointing to redirected URLs (chain waste — should point to final destination)

**Crawl Depth:**
- 3-click rule compliance for top 20 priority pages
- Any high-priority page more than 4 clicks from homepage?

═══════════════════════════════════════
INTERNATIONAL SEO AUDIT (if applicable)
═══════════════════════════════════════
Validate multi-region/multi-language setup:

**hreflang Implementation:**
- Correct language/region codes (en-us, en-gb, de-de, fr-fr — not just "en")?
- Reciprocal hreflang tags (page A must reference page B AND page B must reference page A)?
- x-default tag for users in unspecified regions
- Consistent implementation across HTML, HTTP header, or XML sitemap (pick one method)
- Self-referencing hreflang on each page

**Site Structure:**
- ccTLD (.de, .fr) vs. subdomain (de.site.com) vs. subdirectory (site.com/de/) — which is current? What's recommended given domain authority?
- Geotargeting settings in Google Search Console (subdirectories can be geo-targeted; subdomains cannot)
- IP delivery / CDN geo-routing creating different content for Googlebot (US-based)?

**Content Parity:**
- Machine-translated vs. human-translated content: thin content risk
- Localized currency, date formats, phone numbers — consistency

═══════════════════════════════════════
DELIVERABLE REQUIREMENTS
═══════════════════════════════════════
Structure your complete audit as:

**SECTION 1: EXECUTIVE SUMMARY**
- Overall site health score (0–100)
- Top 5 critical issues requiring immediate action (with estimated ranking impact)
- Estimated organic traffic recovery potential if all Critical/High issues fixed
- One-sentence narrative of the site's technical SEO posture

**SECTION 2: ISSUE REGISTER**
Full table format: Issue | Pillar | Severity (Critical/High/Medium/Low) | Pages Affected | Root Cause | Remediation Steps | Estimated Dev Effort (hours) | Ranking Impact (High/Medium/Low) | Priority Score

**SECTION 3: 90-DAY REMEDIATION ROADMAP**
Sprint 1 (Days 1–30): Critical fixes — zero tolerance items that are actively costing rankings today
Sprint 2 (Days 31–60): High-impact structural fixes — architecture, internal linking, schema
Sprint 3 (Days 61–90): Performance & optimization — CWV improvements, international, structured data expansion

Format each sprint as: Action | Owner (Dev/SEO/Content) | Tool Required | Success Metric | Expected Outcome

**SECTION 4: MONITORING & REGRESSION PREVENTION**
- 5 GSC alerts to set up immediately
- Weekly technical SEO health checklist (5 items)
- Pre-deployment technical SEO QA checklist for future site changes
- Recommended tooling stack for ongoing monitoring

## Example Input/Output

**Input Example:**

Company: Clearpath (B2B SaaS, project management for construction companies)
Site: https://clearpath.io — Next.js 14, Vercel, Cloudflare CDN
Size: ~920 URLs, ~380 indexable pages
Traffic: Dropped 31% in 8 weeks following rebrand + CMS migration from WordPress to Next.js
GSC errors: 218 "Crawled - currently not indexed," 67 "Page with redirect," 29 "Soft 404"
Recent changes: WordPress → Next.js migration 9 weeks ago, new blog architecture, URL restructure
Known issue: Lost ~40 ranking positions across mid-funnel blog posts post-migration

**Output Example (partial):**

**EXECUTIVE SUMMARY:**
Overall Site Health Score: 41/100 — Critical post-migration technical debt is actively suppressing rankings

Top 5 Critical Issues:
1. Redirect chain cascades — 67 redirect chains averaging 3 hops (Clearpath's main pillar pages losing ~18% PageRank per hop vs. direct links)
2. JavaScript-only internal links — Next.js Link component generating `<a>` tags invisible to Googlebot's first-wave HTML crawl; ~140 blog internal links not passing equity
3. Missing self-referencing hreflang on /en/ subdirectory rollout (causing 38 duplicate indexing errors)
4. LCP failure on /pricing and /demo pages: hero image not preloaded, TTFB averaging 1.8s (target: <800ms) — Googlebot's mobile score triggering Core Web Vitals demotion signal
5. 218 "Crawled - currently not indexed" pages concentrated in blog — likely cause: thin post-migration content (posts under 400 words), no internal links from high-authority pages pointing to newly migrated URLs

Estimated Traffic Recovery Potential: 60–90% of lost traffic recoverable within 90 days if Critical/High items resolved

---

**ISSUE REGISTER SAMPLE:**

| Issue | Pillar | Severity | Pages Affected | Root Cause | Remediation | Dev Hours | Impact | Priority |
|---|---|---|---|---|---|---|---|---|
| Redirect chains (3+ hops) | Crawlability | Critical | 67 pages | WordPress redirects stacked on top of migration redirects | Audit all redirects, collapse to single-hop 301s, update internal links to final destination URL | 4h | High | 1 |
| JS-rendered internal links not crawlable | JS Rendering | Critical | ~140 blog posts | Next.js client-side routing generating links post-hydration | Ensure all <Link> components render static <a href> tags in SSR HTML output; validate with "View Page Source" | 6h | High | 2 |
| LCP > 4.2s on /pricing, /demo | Core Web Vitals | Critical | 2 pages | Hero image not preloaded, no explicit fetchpriority="high", TTFB 1.8s | Add <link rel="preload"> for hero, add fetchpriority="high", enable Vercel Edge Config for faster TTFB | 3h | High | 3 |
| 218 orphaned blog posts post-migration | Internal Linking | High | 218 posts | Migration created new URL structure without updating pillar page links | Systematic internal link audit; add links from top-10 highest-authority pages to migrated blog URLs | 8h | High | 4 |
| Missing BreadcrumbList schema | Structured Data | Medium | ~380 pages | Schema not reimplemented post-migration | Add BreadcrumbList JSON-LD to all inner pages via Next.js _app.js global schema component | 2h | Medium | 8 |

---

**SPRINT 1 SAMPLE (Days 1–30):**

| Action | Owner | Tool | Success Metric | Expected Outcome |
|---|---|---|---|---|
| Audit + collapse all redirect chains to single-hop | Dev | Screaming Frog / Ahrefs Site Audit | 0 chains with > 1 hop in GSC "Page with redirect" | PageRank flows cleanly to final destination URLs; redirect errors resolved in GSC within 2 crawl cycles (~3 weeks) |
| Fix Next.js Link component to render crawlable static HTML | Dev | Chrome DevTools "View Page Source" | All internal links visible in raw HTML before JS execution | Googlebot starts passing link equity to 140 blog posts; "Crawled - not indexed" count drops over 4–6 weeks |
| Preload hero images + fix TTFB on /pricing and /demo | Dev | PageSpeed Insights / Vercel Analytics | LCP < 2.5s on mobile for both pages | CWV "poor" pages removed from GSC report; potential ranking recovery for converted demo/pricing pages |

## Success Metrics

- Issue Register captures 100% of Critical and High severity issues — zero surprises after audit is complete
- 90-Day Roadmap is sprint-ready: each action has an assigned owner, a specific tool, and a measurable success condition
- Executive Summary can be sent to a CTO or VP Engineering without translation — non-technical but specific
- At least 3 "quick wins" (< 2 dev hours each) that can generate measurable ranking movement within 30 days
- Post-remediation: GSC "Page with redirect" and "Crawled - currently not indexed" counts drop by ≥ 50% within 45 days of sprint 1 completion
- Core Web Vitals "Poor" URL count reaches zero within 60 days of CWV sprint execution

## Related Prompts

- `./Keyword-Research-&-Search-Intent-Mapping-Intelligence-Engine.md` — Build the keyword strategy that technical fixes unlock access to
- `./Competitor-SEO-&-Organic-Market-Share-Intelligence-Engine.md` — Identify competitive gaps after technical health is restored
- `../../03_Content-&-Creative/Blog-&-Article-Writing/Content-Audit-&-SEO-Refresh-Intelligence-Engine.md` — Remediate thin content and "crawled - not indexed" blog posts
- `../../03_Content-&-Creative/GEO-AIO-GEN-AI-Optimization/Structured-Data-Schema-Markup-&-AI-Parsing-Intelligence-Engine.md` — Expand schema markup for AI search visibility after core schema is fixed

## Integration Tips

- **Google Search Console**: Export all coverage errors before and after each sprint. Track weekly "Valid," "Error," and "Warning" counts as your primary leading indicator. Set up email alerts for any new spike in "Server errors" or "Soft 404" counts.
- **Screaming Frog SEO Spider**: Connect to GSC + GA4 for enriched crawl data. Schedule automated weekly crawls and export delta reports to catch regressions before they compound. Map crawl depth report against GSC "Crawled - currently not indexed" to find buried pages.
- **Vercel / Cloudflare / CDN Dashboard**: After fixing TTFB issues, monitor real-user Interaction to Next Paint (INP) and LCP via Vercel Web Analytics or Cloudflare Web Analytics. These are real-user metrics — faster than GSC's CWV update lag.
- **HubSpot**: If using HubSpot CMS, use the SEO Recommendations tool for lightweight ongoing monitoring. Map technical SEO fixes to HubSpot page performance reports to correlate rankings + conversions.
- **Datadog / Sentry**: Set up uptime and error monitoring for site-wide 5xx errors and JavaScript exceptions that could affect Googlebot rendering. A 500 error spike on crawl days = indexing setback.
- **Zapier / Make**: Automate: GSC API → Google Sheets → Slack alert when "Crawled - not indexed" count rises > 10% week-over-week. Catches new technical regressions from deployments before they become ranking incidents.
- **Linear / Jira**: Convert the 90-Day Roadmap directly into a sprint board. Each pillar = an epic. Each issue register row = a ticket with estimated effort pre-filled. Tag tickets by owner (Dev/SEO/Content) for capacity planning.

## Troubleshooting

**Issue: AI audit output is generic ("check your robots.txt") without specific diagnoses**
Fix: Paste the actual content of your robots.txt, sitemap URL, and the raw HTML from `view-source:yourdomain.com/key-page` directly into the prompt. The more raw data you provide — GSC error screenshots, actual URL examples, CMS template names — the more precise the diagnosis. Treat the AI like a consultant on their first day: give them the briefing doc, not just the job title.

**Issue: Recommended Core Web Vitals fixes don't improve PageSpeed Insights scores in practice**
Fix: PageSpeed Insights and real-user CWV (field data) are different datasets. Run fixes against both Lab data (PSI Lighthouse) AND real-user field data (CrUX via PageSpeed Insights "Field Data" section). If scores improve in lab but not field data, the problem is real-user variability — run the audit prompt again specifying "I need fixes specifically for real-user CWV improvement, not Lighthouse lab score" and include your CrUX percentile breakdown (p75 LCP, p75 INP, p75 CLS).

**Issue: After fixing redirect chains, GSC still shows old redirect errors for weeks**
Fix: This is normal — GSC reflects historical crawl data with a 2–4 week lag after fixes are deployed. Verify fixes are live using `curl -I https://yourdomain.com/old-url` to check actual HTTP response codes. If curl confirms 200s and clean single-hop 301s, trust the fix. Expedite re-crawling of key fixed URLs via GSC URL Inspection → "Request Indexing" for the 10–15 highest-priority pages.

## Version History
- v1.0: Initial creation (auto-generated)
