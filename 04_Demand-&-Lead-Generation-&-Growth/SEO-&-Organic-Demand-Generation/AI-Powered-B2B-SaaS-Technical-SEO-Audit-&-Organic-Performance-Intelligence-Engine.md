# AI-Powered B2B SaaS Technical SEO Audit & Organic Performance Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** technical-seo, core-web-vitals, crawl-optimization, site-architecture, indexation, b2b-saas, organic-growth

## Overview

This prompt runs a systematic technical SEO audit for B2B SaaS sites — diagnosing crawl inefficiencies, indexation gaps, Core Web Vitals failures, site architecture weaknesses, and schema markup deficiencies that silently suppress organic rankings and pipeline. Use it when organic traffic has plateaued, rankings are inconsistent, or you need a CFO-ready technical SEO investment case.

## Quick Copy-Paste Version

You are a senior technical SEO engineer with 12+ years of experience auditing B2B SaaS sites. Run a comprehensive technical SEO audit for [Your Company], a [product description] targeting [ICP: job title, company size, industry].

Based on the following site data, diagnose every technical issue suppressing our organic rankings and provide a prioritized remediation roadmap:

**Site context:**
- Domain: [your-domain.com]
- Monthly organic sessions: [X]
- CMS/Tech stack: [WordPress/Webflow/Next.js/custom]
- Primary product pages: [/pricing, /features, /integrations, /blog]
- Top 5 target keyword clusters: [list them]
- Existing GSC issues flagged: [paste GSC coverage report summary]

**Audit scope — analyze and produce findings for each:**

1. **Crawl Budget & Indexation Health**
   - Identify pages being crawled but shouldn't be (admin, staging, duplicate, thin content)
   - Flag pages that should be indexed but aren't (key product/feature pages)
   - Diagnose robots.txt and XML sitemap inconsistencies
   - Estimate crawl budget waste as a % and its revenue impact

2. **Core Web Vitals & Page Experience**
   - Identify LCP, INP, and CLS failures by page template (homepage, landing pages, blog posts)
   - Diagnose root causes: render-blocking JS, unoptimized images, layout shift culprits
   - Prioritize fixes by traffic volume × ranking impact potential

3. **Site Architecture & Internal Linking**
   - Map PageRank flow from homepage to money pages
   - Identify orphaned pages, excessive crawl depth (>3 clicks), and broken internal links
   - Recommend hub-and-spoke architecture adjustments for priority keyword clusters

4. **Duplicate Content & Canonicalization**
   - Surface URL parameter issues, www/non-www splits, HTTP/HTTPS mixing, trailing slash inconsistencies
   - Identify content cannibalization (multiple pages competing for the same keyword)
   - Prescribe canonical tag strategy

5. **Schema Markup & Structured Data**
   - Audit current schema implementation against what competitors have deployed
   - Recommend schema types by page: SoftwareApplication, FAQPage, HowTo, BreadcrumbList, Review, Organization
   - Write ready-to-implement JSON-LD snippets for top 3 priority page types

6. **Mobile & International SEO**
   - Flag mobile rendering failures and tap target issues
   - Identify hreflang errors if serving multiple languages/regions

**Output format:**
- Executive summary: 3 critical issues costing us the most organic revenue
- Prioritized issue list: P0 (fix this week), P1 (this sprint), P2 (next quarter)
- For each issue: root cause, business impact (estimated traffic/pipeline at risk), fix instructions, and success metric
- 30/60/90-day technical SEO sprint roadmap

## Advanced Customizable Version

ROLE: You are a principal technical SEO architect specializing in B2B SaaS platforms with deep expertise in Google Search Central guidelines, Core Web Vitals optimization, and organic revenue attribution. You combine the diagnostic rigor of a site reliability engineer with the commercial focus of a demand generation leader.

CONTEXT:
Company: [Company Name]
Product: [Brief description — what it does, who it serves]
ICP: [Primary buyer persona — title, company size, industry verticals]
Tech Stack: [CMS, JavaScript framework, CDN, hosting]
Domain Authority: [Estimated or known DA/DR]
Monthly Organic Traffic: [Sessions/month]
GSC Data Available: [Yes/No — paste key issues if yes]
Primary Revenue Pages: [List URLs of pricing, demo, key feature/product pages]
Top Competitor Domains: [Competitor 1, Competitor 2, Competitor 3]
Avg Deal Size: $[X] ACV | Sales Cycle: [X months]

OBJECTIVE: Conduct an expert-level technical SEO audit that identifies every infrastructure-level issue suppressing organic rankings and pipeline. Produce a prioritized, commercially framed remediation plan that a marketing leader can present to engineering leadership with clear business cases for each fix.

AUDIT FRAMEWORK — Execute each section with expert depth:

━━━ SECTION 1: CRAWL INTELLIGENCE & INDEXATION AUDIT ━━━

Crawl Budget Analysis:
□ Calculate estimated daily crawl budget based on domain authority and site size
□ Identify crawl budget wasters: URL parameters, faceted navigation, session IDs, internal search results
□ Audit robots.txt — disallowed directories, crawl-delay directives, sitemap declarations
□ Cross-reference: pages blocked in robots.txt vs. pages receiving organic traffic (critical conflict detection)

Indexation Audit:
□ Estimated indexed pages vs. total pages — flag over-indexation and under-indexation
□ Diagnose noindex tags on revenue-critical pages (check product pages, pricing, integrations)
□ Identify soft 404s, redirect chains >2 hops, and redirect loops
□ Flag pages with "Discovered — currently not indexed" and "Crawled — currently not indexed" GSC statuses and diagnose root causes

XML Sitemap Audit:
□ Sitemap includes 404s, redirected URLs, or noindexed pages (common error)
□ Sitemap last modification dates accuracy
□ Dynamic sitemap generation for new content (blog, changelog, product updates)

━━━ SECTION 2: CORE WEB VITALS & PAGE EXPERIENCE ━━━

LCP (Largest Contentful Paint) — Target: <2.5s:
□ Identify LCP element by page template (usually hero image or H1)
□ Diagnose: server response time (TTFB), render-blocking resources, unoptimized images, no lazy loading deferral strategy
□ Prescribe: image format (WebP/AVIF), preload hints, CDN configuration, server-side rendering vs. CSR decisions

INP (Interaction to Next Paint) — Target: <200ms:
□ Identify heavy JavaScript execution paths on key landing pages
□ Flag third-party scripts (chat widgets, analytics, A/B testing tools) contributing to INP bloat
□ Recommend: script deferral strategy, web worker offloading, event handler optimization

CLS (Cumulative Layout Shift) — Target: <0.1:
□ Identify layout shift culprits: images without dimensions, late-loading ads/embeds, web font FOIT/FOUT
□ Prescribe CSS containment, font-display: swap, explicit size reservations

Page Experience Signals:
□ HTTPS: full implementation, mixed content warnings
□ Intrusive interstitials: audit exit-intent popups and demo CTAs for Google penalty risk
□ Mobile usability: viewport configuration, tap target sizing, font size compliance

━━━ SECTION 3: SITE ARCHITECTURE & LINK EQUITY FLOW ━━━

Information Architecture Analysis:
□ Map the click depth of all revenue-critical pages from homepage
□ Identify pages at depth >3 that should be at depth 1-2 (pricing, key integrations, top product features)
□ Recommend flattened URL structure for high-value content clusters

Internal Link Equity Mapping:
□ Identify top link equity receivers vs. top revenue pages — flag misalignment
□ Surface orphaned pages (zero internal links pointing to them)
□ Recommend hub-and-spoke internal linking model for each core keyword cluster
□ Prescribe anchor text diversity ratio (exact match vs. partial match vs. branded)

URL Structure Audit:
□ Subdomain vs. subdirectory decisions for blog, docs, academy (revenue impact analysis)
□ URL length and keyword inclusion optimization
□ Dynamic vs. static URL patterns

━━━ SECTION 4: DUPLICATE CONTENT & CANONICALIZATION ━━━

Technical Duplication Sources:
□ WWW vs. non-WWW — single canonical version enforced?
□ HTTP vs. HTTPS — full redirect chain audit
□ Trailing slash inconsistency (/pricing vs /pricing/)
□ URL parameter proliferation (UTM parameters, sorting/filtering parameters)
□ Paginated content handling (rel="next/prev" deprecated — current best practice)

Content Cannibalization Detection:
□ Identify keyword clusters where multiple pages compete for the same intent
□ Flag low-authority pages splitting link equity from primary target pages
□ Recommend: consolidation, redirect, or canonical strategy per cluster

Canonical Implementation Audit:
□ Self-referencing canonicals present on all indexable pages?
□ Canonical chains (canonical pointing to another canonical)?
□ Canonical conflicts with noindex tags?
□ Hreflang + canonical conflicts for international sites?

━━━ SECTION 5: SCHEMA MARKUP & RICH RESULT OPTIMIZATION ━━━

Current Implementation Audit:
□ What schema types are currently deployed? Are they error-free?
□ Competitor schema gap analysis — what rich results are competitors winning that we're not?
□ Validate against Google's Rich Results Test

Schema Opportunity Map by Page Type:
□ Homepage: Organization, SiteNavigationElement, SearchAction (sitelinks searchbox)
□ Product/Feature pages: SoftwareApplication, Product, Offer
□ Pricing page: Offer, PriceSpecification
□ Blog/Content: Article, BlogPosting, BreadcrumbList
□ FAQ pages: FAQPage (high CTR uplift potential)
□ Case studies: Review, Rating
□ Integration pages: SoftwareApplication with applicationCategory

Implementation Deliverable:
For each priority schema type: provide complete, error-free JSON-LD code block ready for developer implementation.

━━━ SECTION 6: TECHNICAL LINK PROFILE & AUTHORITY ━━━

Link Profile Health:
□ Toxic/spammy backlink patterns requiring disavow consideration
□ Lost high-authority links (404 pages that formerly had backlinks — 301 redirect opportunities)
□ Competitor backlink gap — authoritative domains linking to competitors but not us
□ Internal link equity amplification opportunities for link-building targets

━━━ OUTPUT REQUIREMENTS ━━━

Deliver a Technical SEO Audit Report with:

1. EXECUTIVE SUMMARY (Board-ready, 200 words)
   - 3 critical issues and estimated organic revenue at risk
   - Investment required (engineering hours) vs. projected pipeline recovery
   - 12-month organic growth projection if issues are resolved

2. PRIORITIZED ISSUE REGISTER
   For each issue:
   - Issue name and category
   - Severity: P0 (revenue-critical, fix this week) / P1 (high impact, this sprint) / P2 (optimization, next quarter)
   - Root cause diagnosis
   - Business impact: estimated traffic delta, pipeline at risk (calculate using: organic sessions × conversion rate × ACV)
   - Fix specification: exact developer instructions
   - Effort estimate: engineering hours
   - Success metric: how to confirm the fix worked

3. SPRINT ROADMAP
   Week 1-2 (P0 fixes): [list]
   Sprint 1-2 (P1 fixes): [list]
   Q2 Optimization (P2): [list]

4. SCHEMA IMPLEMENTATION PACKAGE
   Ready-to-implement JSON-LD for top 3 priority page types

5. MONITORING SETUP
   - GSC queries to track weekly
   - GA4 events to configure for organic conversion tracking
   - Core Web Vitals monitoring alerts (recommend PageSpeed Insights API + Lighthouse CI)

CONSTRAINTS:
- Frame every issue in terms of pipeline and revenue impact, not just technical severity
- Assume engineering bandwidth is the constraint — prioritize ruthlessly
- Reference Google Search Central documentation for every recommendation where applicable
- Do not recommend tactics that conflict with Google's spam policies or that could trigger manual actions

## Example Input/Output

**Input:**
Company: Flowline
Product: Revenue operations automation platform for B2B sales teams
ICP: RevOps Directors, VPs of Sales, Series B+ SaaS companies, 100-1,000 employees
Tech Stack: Next.js 14, Vercel CDN, Contentful CMS
Domain Rating: 51
Monthly Organic Traffic: 28,000 sessions
GSC Issues: 847 "Discovered - currently not indexed" URLs, 12 URLs with Core Web Vitals failures
Revenue Pages: /pricing, /features/forecasting, /features/pipeline-management, /integrations
Top Competitors: Clari, Gong, Bowtie
Avg Deal Size: $28,000 ACV, 45-day sales cycle

**Output excerpt:**

**EXECUTIVE SUMMARY**

Flowline's organic channel is underperforming its domain authority by an estimated 35-40% due to three infrastructure failures: (1) 847 product and integration pages trapped in a crawl budget bottleneck caused by JavaScript rendering delays, blocking Google from indexing high-commercial-intent pages; (2) LCP failures of 4.2s average on /features/* templates, suppressing rankings for our highest-ACV keyword clusters; (3) content cannibalization across 14 keyword groups where thin integration pages split link equity from primary category pages.

Estimated pipeline at risk: $380K-$520K annual pipeline from organic, based on current MQL conversion rate (2.1%) and $28K ACV. Remediation investment: ~120 engineering hours over 6 weeks.

---

**P0 ISSUES — Fix This Week:**

**Issue: Dynamic rendering blocking 847 high-value pages from Google's index**
- Root Cause: Next.js client-side rendering on /integrations/* and /features/* routes. Googlebot's crawl budget is exhausted rendering JavaScript before reaching product content. GSC confirms 847 "Discovered - currently not indexed" URLs — 73% are integration and feature pages with transactional intent.
- Business Impact: Integration pages average 340 monthly searches each × 12% estimated SERP CTR × 2.1% MQL conversion × $28K ACV = **$68K annual pipeline per 10 indexed integration pages**. 847 pages represent $5.7M in potential annual pipeline.
- Fix: Implement Next.js static generation (getStaticProps) or incremental static regeneration (ISR) for all /integrations/* and /features/* routes. Alternatively, configure Vercel's Edge Functions for server-side rendering on these paths.
- Dev Effort: 16-24 hours
- Success Metric: GSC Coverage report shows <50 "Discovered - not indexed" URLs within 60 days; integration pages appearing in "Valid" index within 45 days

---

**Issue: LCP 4.2s average on /features/* templates (Google threshold: 2.5s)**
- Root Cause: Hero image (1.4MB PNG) loaded without WebP conversion, no preload hint, and Intercom chat widget script blocking render thread by 1.1s.
- Business Impact: Pages ranking positions 8-15 for "pipeline management software" and "revenue forecasting tool" (combined 6,200 monthly searches) estimated to gain 3-5 ranking positions with LCP fix, projecting +18% organic clicks to these pages. At current conversion rates: +$94K annual pipeline.
- Fix:
  1. Convert all hero images to WebP/AVIF; set explicit width/height attributes
  2. Add `<link rel="preload" as="image" href="/hero-features.webp">` in document `<head>`
  3. Defer Intercom initialization: load after `window.onload` event, not on DOMContentLoaded
  4. Implement `font-display: swap` for Inter font family
- Dev Effort: 8 hours
- Success Metric: PSI score for /features/* templates reaches LCP <2.5s; validate in GSC Core Web Vitals report within 28 days

---

**SCHEMA IMPLEMENTATION — /pricing page:**

{
  "@context": "https://schema.org",
  "@type": "SoftwareApplication",
  "name": "Flowline",
  "applicationCategory": "BusinessApplication",
  "operatingSystem": "Web",
  "offers": [
    {
      "@type": "Offer",
      "name": "Starter",
      "price": "599",
      "priceCurrency": "USD",
      "priceSpecification": {
        "@type": "UnitPriceSpecification",
        "price": "599",
        "priceCurrency": "USD",
        "unitText": "per month"
      }
    },
    {
      "@type": "Offer",
      "name": "Professional",
      "price": "1499",
      "priceCurrency": "USD",
      "priceSpecification": {
        "@type": "UnitPriceSpecification",
        "price": "1499",
        "priceCurrency": "USD",
        "unitText": "per month"
      }
    }
  ],
  "aggregateRating": {
    "@type": "AggregateRating",
    "ratingValue": "4.7",
    "reviewCount": "312"
  }
}

## Success Metrics

A high-quality output from this prompt should deliver:

- **Specificity**: Every issue includes a root cause diagnosis, not just symptom description
- **Commercial framing**: Pipeline impact calculated for each P0/P1 issue using: (traffic delta × CVR × ACV)
- **Actionability**: Developer-ready fix instructions that a junior engineer can execute without guesswork
- **Prioritization logic**: P0/P1/P2 classification based on pipeline impact × fix effort ratio, not technical severity alone
- **Schema completeness**: JSON-LD is syntactically valid and matches current Google structured data documentation
- **Measurability**: Each fix includes a specific success metric and a timeline to verify resolution in GSC

**Benchmark outcomes after implementing P0+P1 fixes (typical B2B SaaS site):**
- Crawl coverage improvement: +30-60% more pages indexed within 60 days
- Core Web Vitals: LCP reduction from >4s to <2s on key templates
- Organic traffic: +15-35% within 90 days of remediation
- Pipeline from organic: +$200K-$800K annual depending on existing traffic volume

## Related Prompts

- [AI-Powered B2B SaaS SEO Demand Generation Program Architecture](./AI-Powered-B2B-SaaS-SEO-Demand-Generation-Program-Architecture-&-Organic-Pipeline-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Demand Capture CRO & High-Intent Funnel Conversion](../../04_Demand-&-Lead-Generation-&-Growth/Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Demand-Capture-CRO-&-High-Intent-Funnel-Conversion-Intelligence-Engine.md)
- [AI-Powered B2B GEO-Optimized Long-Form Content Architecture & AI Search Citation Capture](../../03_Content-&-Creative/Blog-&-Article-Writing/AI-Powered-B2B-GEO-Optimized-Long-Form-Content-Architecture-&-AI-Search-Citation-Capture-Intelligence-Engine.md)
- [AI-Powered Marketing Dashboard & Anomaly Detection Intelligence Engine](../../01_CMO-&-Leadership/Reporting-&-ROI/AI-Powered-Marketing-Dashboard-&-Anomaly-Detection-Intelligence-Engine.md)

## Integration Tips

**Google Search Console (GSC):**
- Export Coverage report → paste "Discovered - not indexed" and "Crawled - not indexed" URL lists directly into the Advanced Version prompt
- Export Core Web Vitals report → paste failing URL templates for targeted diagnosis
- Use GSC's URL Inspection API to automate weekly indexation health checks

**Screaming Frog / Ahrefs / Semrush:**
- Export crawl data as CSV → feed into prompt for site architecture and orphan page analysis
- Ahrefs' Site Audit "Issues" export maps directly to the audit framework categories above

**Google Tag Manager:**
- Implement Core Web Vitals measurement via GTM's built-in Web Vitals template
- Tag organic landing pages with custom dimensions for organic-sourced pipeline attribution in GA4

**Vercel / Netlify / Cloudflare:**
- Use platform-native performance monitoring dashboards to track LCP/CLS/INP improvements post-fix
- Configure Cloudflare's Browser Insights or Vercel Analytics for real-user monitoring (RUM) data

**Jira / Linear:**
- Copy the P0/P1 issue register directly into engineering sprint tickets
- Tag all technical SEO tickets with "organic-revenue" label for CFO-visible pipeline tracking

**HubSpot / Salesforce:**
- Create "organic search" attribution source in CRM; track MQLs per landing page template to validate pipeline impact of technical SEO fixes
- Build a dashboard: organic-sourced leads by page → connect to closed-won revenue for 12-month SEO ROI calculation

## Troubleshooting

**Issue: Output is too generic — fixes aren't specific to my stack**
- Fix: Add your exact tech stack details in the prompt (framework version, CDN provider, JavaScript rendering approach). Include your GSC URL Inspection output for 2-3 specific failing pages. The more raw data you input, the more precise the diagnosis.

**Issue: The pipeline impact estimates seem too high/low**
- Fix: Adjust the calculation inputs. Provide your actual organic conversion rate (organic sessions → MQL), not an assumed benchmark. If you don't know your organic CVR, pull it from GA4: `Sessions from organic / Goals completed from organic`. Also verify your ACV is correct — this multiplier has the largest impact on pipeline estimates.

**Issue: Developers won't prioritize the fixes without more technical detail**
- Fix: Run the Advanced Version with your specific GSC data exported, then ask a follow-up prompt: "Expand the P0 fix for [specific issue] into a technical implementation spec with code examples, test scenarios, and rollback procedure for a Next.js/[your stack] implementation." This generates ticket-ready engineering specs.

## Version History
- v1.0: Initial creation (auto-generated)
