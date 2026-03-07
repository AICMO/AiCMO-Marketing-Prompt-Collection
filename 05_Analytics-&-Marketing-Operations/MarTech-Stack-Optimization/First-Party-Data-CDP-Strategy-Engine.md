# First-Party Data & CDP Strategy Engine - Cookieless Marketing Intelligence Architecture

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** cdp, first-party-data, martech, analytics, privacy, b2b, b2c, attribution, personalization, operations

## Overview
This prompt audits your current first-party data collection posture, designs a Customer Data Platform (CDP) strategy, and produces an end-to-end activation roadmap — from data capture and identity resolution to audience segmentation, channel personalization, and privacy-compliant measurement. Use it when migrating off third-party cookies, evaluating CDP vendors, or when your marketing data is siloed across disconnected tools with no unified customer view.

## Quick Copy-Paste Version

You are a marketing data strategist and CDP architect. Analyze my current first-party data situation and build a complete strategy for collecting, unifying, and activating customer data without relying on third-party cookies.

My current situation:
- Business type: [B2B SaaS / B2C eCommerce / D2C / Marketplace]
- Monthly website visitors: [X]
- Known contacts in CRM: [X]
- Current data tools: [e.g., GA4, HubSpot, Salesforce, Klaviyo, Segment — or "none unified"]
- Biggest data pain points: [e.g., "Can't connect anonymous web behavior to known CRM contacts", "No single customer view", "Can't personalize email based on site behavior"]
- Current CDP or data warehouse: [tool name or "none"]
- Budget range for data infrastructure: $[X/month]

Deliver:
1. First-party data audit — where am I collecting data today and what am I missing
2. Identity resolution strategy — how to stitch anonymous and known identities
3. CDP vendor recommendation with 3 options ranked by fit for my situation
4. Top 5 audience segments I should build and activate immediately
5. A 90-day implementation roadmap to full first-party data activation
6. Privacy compliance checklist (GDPR, CCPA, consent management)
7. How to replace the top 3 third-party cookie use cases I am currently dependent on

## Advanced Customizable Version

ROLE:
You are a Senior Customer Data Platform Architect and Marketing Data Strategist with 15 years of experience designing first-party data infrastructure for B2B SaaS, B2C eCommerce, and D2C brands. You have led CDP implementations at companies ranging from $5M to $500M ARR, built on platforms including Segment (Twilio), RudderStack, mParticle, Treasure Data, ActionIQ, and Adobe Real-Time CDP. You understand the full data lifecycle: event collection, identity stitching, profile enrichment, audience modeling, channel activation, and privacy-compliant measurement. You are equally fluent in marketing strategy and data engineering trade-offs, so your recommendations are always actionable by a marketing ops team — not just engineers.

OBJECTIVE:
Conduct a comprehensive audit of the company's current first-party data posture, design an optimal CDP architecture for their stage and GTM motion, and deliver a complete activation strategy that replaces third-party cookie dependence, unifies the customer view across all touchpoints, and enables real-time personalization and attribution — all within applicable privacy regulations.

CONTEXT — COMPANY PROFILE:

Company information:
- Company name: [Your Company]
- Business model: [B2B SaaS / B2C eCommerce / D2C / Marketplace / Media / Financial Services]
- Stage: [Seed / Series A / Series B / Growth / Enterprise]
- Industry vertical: [Fintech / Retail / HR Tech / Healthcare / DevTools / Media / Other]
- Monthly website unique visitors: [X]
- Monthly active users (product): [X] (if applicable)
- Known contacts / customers in CRM: [X]
- Annual marketing budget: $[X]
- Marketing team size: [X] FTEs
- Primary GTM motion: [Inbound / Outbound / PLG / ABM / DTC / Marketplace]
- Primary ICP: [SMB / Mid-Market / Enterprise / Consumer segment]
- Key markets and geographies (for privacy law applicability): [US / EU / UK / APAC / Global]

Current data infrastructure (list every relevant tool):
- CRM: [HubSpot / Salesforce / Pipedrive / None]
- Email / marketing automation: [Klaviyo / HubSpot / Marketo / Mailchimp / None]
- Web analytics: [GA4 / Adobe Analytics / Mixpanel / Heap / None]
- Product analytics: [Mixpanel / Amplitude / PostHog / None]
- Advertising platforms: [Google Ads / Meta Ads / LinkedIn Ads / TikTok Ads — list all]
- Current CDP or event pipeline: [Segment / RudderStack / mParticle / None]
- Data warehouse: [Snowflake / BigQuery / Redshift / Databricks / None]
- Data activation / reverse ETL: [Census / Hightouch / None]
- Consent management platform: [OneTrust / Cookiebot / Usercentrics / None]
- Customer support: [Intercom / Zendesk / Freshdesk / None]
- Commerce / billing: [Stripe / Shopify / Recurly / Chargebee / None]

Current data collection reality:
- Do you fire a JavaScript snippet on your website to capture page views and click events? [Yes / No / Partial]
- Do you capture form submission data and tie it to a user profile in your CRM? [Yes / No / Partial]
- Do you track post-login product behavior and associate it with the CRM contact record? [Yes / No / Partial]
- Do you have server-side event tracking (vs. browser-only)? [Yes / No]
- Do you have a unified customer identifier that persists across web, email, product, and support? [Yes / No]
- What percentage of your website visitors are identified (logged-in or matched to a known CRM record)? [X]%
- Biggest data quality problem: [e.g., duplicate contact records / no product-to-CRM sync / anonymous traffic with no identity resolution / inconsistent event naming]

Third-party cookie dependency assessment — check all that apply:
- [ ] Retargeting and remarketing ads (Google, Meta, LinkedIn)
- [ ] Cross-site behavioral tracking
- [ ] Frequency capping across ad networks
- [ ] Conversion attribution for paid campaigns
- [ ] Lookalike audience building
- [ ] Behavioral personalization on the website
- [ ] A/B test assignment persistence across sessions

Privacy compliance context:
- Do you serve users in the EU or UK (GDPR / UK GDPR applies)? [Yes / No]
- Do you have California users with greater than $25M revenue or more than 100K users (CCPA / CPRA applies)? [Yes / No]
- Do you operate in other regulated markets? [List if applicable]
- Current consent management status: [No CMP / Basic cookie banner / Full consent management platform]
- Do you have a data processing agreement in place with all vendors who process personal data? [Yes / No / Partial]

CONSTRAINTS:
- All recommendations must be implementable by a marketing ops team of [X] people — specify which steps require engineering resources and estimated hours
- CDP vendor recommendations must include a free or open-source option alongside premium options
- Every data activation use case must include the specific audience definition logic usable in HubSpot, Klaviyo, Segment, or the recommended CDP
- Privacy recommendations must be specific to the geographies listed — do not provide generic GDPR summaries
- Attribution approach must work in a cookieless environment with no reliance on third-party cookie-based last-click
- Implementation roadmap must be sequenced so that each phase produces standalone value before the next phase begins

OUTPUT STRUCTURE — DELIVER ALL SECTIONS:

**1. First-Party Data Audit**
Assess the current state across five data collection layers:

Layer 1 — Acquisition Data (UTM parameters, ad click IDs, referral sources)
- Current status: What is being captured and where is it stored?
- Gaps: What acquisition data is being lost?
- Impact: What decisions are being made blind because of this gap?
- Fix: Specific implementation instructions

Layer 2 — Anonymous Behavioral Data (website visits, page views, scroll depth, content engagement)
- Current status: What events are being tracked and in which tool?
- Gaps: What behavior is invisible?
- Impact: What personalization and targeting opportunities are being missed?
- Fix: Specific implementation instructions

Layer 3 — Identity Data (email addresses, company domains, CRM records, customer IDs)
- Current status: How many contacts are identified? What is the current match rate?
- Gaps: Where is identity data fragmented or duplicated?
- Impact: Quantify the duplicate ad spend or missed personalization from identity fragmentation
- Fix: Identity resolution approach (deterministic matching strategy, probabilistic fallbacks)

Layer 4 — Behavioral Product Data (feature usage, login frequency, in-app events, health scores)
- Current status: Is product behavior flowing into marketing tools?
- Gaps: What product signals are being ignored in marketing campaigns?
- Impact: Revenue impact of ignoring high-intent product signals
- Fix: Specific event taxonomy and CRM sync instructions

Layer 5 — Transactional and Support Data (purchase history, subscription status, support ticket themes, NPS scores)
- Current status: Is this data accessible to marketing for segmentation and personalization?
- Gaps: What transactional signals are missing from the marketing data model?
- Fix: Reverse ETL or native integration recommendations

**2. Identity Resolution Strategy**
Design the full identity graph architecture:

a) Deterministic Identity Matching
- Primary identifier: Define the master customer ID and which system is the system of record
- Email-based matching: How to use hashed email (SHA-256) to match across web, email, advertising, and product
- Login-event stitching: How to connect pre-login anonymous session to post-login known profile
- Cross-device identity: How to connect mobile, desktop, and tablet sessions for the same user

b) Probabilistic Identity Matching (for anonymous traffic)
- IP-to-company matching for B2B (tools: Clearbit Reveal / 6sense / Kickfire / RB2B)
- Cohort-based matching (Google Privacy Sandbox TOPICS API integration)
- Privacy risk vs. match rate trade-off analysis

c) Identity Resolution Architecture
Describe the full data flow from anonymous visit to unified profile:
Anonymous session created → Event stream to CDP → Form fill or login triggers email capture → Identity stitching links anon_id to user_id → Profile enriched with firmographic data → Unified profile synced to CRM, ad platforms, and email tool

d) Match Rate Improvement Plan
- Current estimated match rate based on inputs
- Target match rate achievable within 90 days
- Specific tactics to improve match rate: progressive profiling, gated content, login incentives, server-side ID sync

**3. CDP Vendor Evaluation and Recommendation**
Evaluate and rank 3 CDP options specifically for this company's profile:

For each vendor score and explain:
- Data collection capability (client-side, server-side, mobile, warehouse-native)
- Identity resolution quality (native stitching vs. requires custom logic)
- Activation destinations (number and quality of native integrations to ad platforms, CRMs, email tools)
- Real-time vs. batch processing capability
- Engineering effort to implement (hours to value)
- Pricing model and estimated annual cost at current traffic and contact volume
- Privacy and compliance features (consent forwarding, data residency, PII masking)
- Best fit: what company profile this option is ideal for

Vendor options to evaluate — select 3 most appropriate from:
- Budget tier: RudderStack Cloud Free, PostHog, June.so
- Mid-market tier: Segment (Twilio), RudderStack Cloud, Freshpaint
- Enterprise tier: mParticle, ActionIQ, Treasure Data, Adobe Real-Time CDP, Salesforce Data Cloud
- Warehouse-native tier: dbt plus Census or Hightouch (if data warehouse already exists)

Final recommendation: Name the top choice with justification specific to this company's stage, team size, and budget.

**4. Audience Segmentation Strategy**
Design the top 8 segments to build and activate immediately, ordered by revenue impact.

For each segment provide:
- Segment name and description
- Exact audience definition logic (field names, values, and operators usable in HubSpot, Klaviyo, Segment, or the recommended CDP)
- Size estimate as a percentage of total audience
- Activation channels: which platforms to sync this segment to (Google Ads, Meta, LinkedIn, email, in-app, sales outreach)
- Personalization play: what specific message, offer, or experience this segment should receive
- Expected lift vs. non-segmented baseline

B2B SaaS example segments:
1. High-Intent Anonymous Accounts (company domain matched, 3+ product page views in 7 days, no CRM record)
2. Trial-to-Paid Conversion Risk (free trial day 5-12, has not completed activation milestone, no sales touch in 3 days)
3. Champion Change Alert (CRM contact changed job title or company in last 30 days)
4. Expansion Signal (customer using more than 80% of plan limits, no upsell conversation in 90 days)
5. At-Risk Churners (login frequency dropped more than 50% vs. prior 30 days)
6. Warm Inbound (visited pricing page, opened last 2 emails, not yet in a sales sequence)
7. Competitor Research Audience (visited comparison pages or searched competitor terms on site)
8. Event Attendees Not Yet Opportunity (attended webinar, not yet an opportunity in CRM)

B2C / D2C example segments:
1. High-Value Browsers (3+ sessions, 5+ product page views, no cart created)
2. Cart Abandoners — High Intent (cart value above $75, abandoned more than 2 hours ago)
3. One-Time Buyers in Repurchase Window (purchased once, 45-60 days ago, product lifecycle suggests repurchase due)
4. VIP Loyalists (top 10% LTV, 3+ purchases, no loyalty program enrollment)
5. Win-Back Candidates (last purchase more than 120 days ago, previously purchased 2+ times)
6. Category Enthusiasts (viewed same product category 3+ times across 2+ sessions, no purchase)
7. Lapsed Email Engagers (opened email in last 90 days but no site visit in 45+ days)
8. Post-Purchase Upsell Window (purchased product A 14-21 days ago, never viewed complementary product B)

**5. Channel Activation Playbook**
For each of the top 3 activation channels provide a specific implementation guide:

a) Google Ads — Enhanced Conversions and Customer Match
- How to implement Google Enhanced Conversions (server-side, hashed email) to recover attribution lost from cookie blocking
- How to upload first-party audience lists via Customer Match for retargeting and suppression
- How to use Google Privacy Sandbox TOPICS API as a cookie alternative for display targeting
- Estimated match rate improvement vs. standard pixel-based tracking
- Step-by-step implementation using CDP destinations or native integrations

b) Meta Ads — Conversions API
- Server-side CAPI implementation plan (via CDP, direct API, or Meta partner integrations)
- Event deduplication strategy ensuring browser pixel and CAPI events do not double-count
- How to build Custom Audiences from first-party segments and sync on a weekly refresh schedule
- Lookalike audience construction from high-LTV customer list (hashed emails)
- Expected Event Match Quality score improvement vs. browser-only pixel

c) Email and Marketing Automation — Behavioral Triggers
- The top 5 behavioral trigger sequences to build based on first-party data signals
- How to set up real-time event streaming from CDP to email platform (Klaviyo / HubSpot / Marketo)
- Dynamic content personalization using segment membership to render different email content blocks
- Suppression lists: how to automatically exclude recent purchasers and current customers from acquisition campaigns

**6. Cookieless Attribution Framework**
Design a measurement approach that works without third-party cookies:

a) Server-Side Tracking Implementation
- Which events to move from client-side to server-side and why
- Implementation approach: CDP server-side destinations vs. direct API calls vs. GTM Server-Side
- How server-side tracking improves data accuracy against ad blockers, ITP, and browser restrictions

b) First-Party Attribution Model
- UTM parameter capture: how to write UTM data to the CRM contact record at first touch AND update with most recent touch
- Multi-touch attribution logic using CDP event data without third-party tools
- How to build a data-driven attribution model in BigQuery or Snowflake using first-party event data
- Revenue attribution reporting: connecting deal closed to the specific campaigns, content, and channels that influenced it

c) Incrementality Testing
- Geo holdout tests: how to run a geographic control group for paid campaigns
- Intent-matched holdout design for B2B (matched pairs of accounts, one in-flight, one suppressed)
- Recommended cadence: quarterly incrementality tests with budget reallocation based on causal lift results

d) Privacy-Safe Analytics Alternatives
- Google Analytics 4 with consent mode v2 — implementation requirements for EU traffic
- Cookieless analytics tools: Plausible, Fathom, or PostHog for privacy-first baseline reporting
- How to reconcile GA4 data with server-side event data for a complete picture

**7. Privacy Compliance Architecture**
Build a compliance framework specific to the geographies and regulations identified:

a) Consent Management Implementation
- CMP recommendation: OneTrust / Cookiebot / Usercentrics / Axeptio
- Consent mode v2 implementation (required for Google Ads and Google Analytics EU compliance)
- Consent signal forwarding: how to pass consent status to all downstream tools (CDP, ad pixels, analytics)
- Cookie audit: categorize all cookies currently set by the site (strictly necessary / functional / analytics / marketing)

b) Data Subject Rights
- Right to deletion workflow: how to trigger a delete cascade from CRM to CDP to all connected destinations
- Right to access workflow: how to generate a complete data export for a specific individual across all connected systems
- Data retention policies: recommended retention periods by data category and how to automate deletion at policy expiry

c) Vendor Due Diligence
- Data Processing Agreement status check: list all vendors processing personal data and flag which need a signed DPA
- Data residency: which CDP options support EU data residency for GDPR-strict use cases
- Vendor risk: tools being acquired, sunset, or showing product decay signals

d) Consent-Based Segmentation
- How to build "consented for marketing" as a required filter on all marketing segments
- How to suppress non-consented profiles from ad platform audience syncs automatically
- Automated suppression workflow triggered by opt-out event

**8. 90-Day First-Party Data Implementation Roadmap**

Phase 1 — Foundation (Days 1-30): Capture and Identify
- Implement server-side event tracking for top 10 conversion events (Owner: Engineering, Effort: 16-24 hrs)
- Standardize UTM parameter capture and write to CRM at first touch and last touch (Owner: Marketing Ops, Effort: 4 hrs)
- Audit and merge duplicate CRM records, establish primary email as master ID (Owner: RevOps, Effort: 8 hrs)
- Deploy or upgrade CMP with Consent Mode v2 for EU traffic (Owner: WebDev + Legal, Effort: 8 hrs)
- Implement basic identity stitching: fire identify() call on form submission or login to link anon_id to user_id (Owner: Engineering, Effort: 8 hrs)
- Begin CDP evaluation: set up free tier of recommended CDP and run parallel tracking for 30 days (Owner: Marketing Ops, Effort: 4 hrs)

Phase 2 — Unify (Days 31-60): Integrate and Segment
- Connect product event stream to CDP: sync top 5 in-app behavioral events (Owner: Engineering, Effort: 12-20 hrs)
- Build and activate top 3 priority audience segments in email platform (Owner: Marketing Ops, Effort: 8 hrs)
- Implement Google Enhanced Conversions for top conversion events (Owner: Marketing Ops + Engineering, Effort: 6 hrs)
- Implement Meta Conversions API for Purchase, Lead, and ViewContent events (Owner: Engineering, Effort: 8 hrs)
- Set up Customer Match audience upload cadence to Google and Meta (weekly refresh) (Owner: Marketing Ops, Effort: 3 hrs)
- Build suppression lists: active customers excluded from acquisition campaigns across all ad platforms (Owner: Marketing Ops, Effort: 2 hrs)

Phase 3 — Activate (Days 61-90): Personalize and Measure
- Build behavioral trigger email sequences for top 3 segments (Owner: Email Manager, Effort: 12 hrs)
- Activate all 8 priority segments across ad platforms for retargeting, suppression, and lookalike (Owner: Paid Media Manager, Effort: 8 hrs)
- Implement multi-touch attribution reporting in GA4 or BI tool (Owner: Marketing Ops / Analyst, Effort: 16 hrs)
- Run first geo holdout incrementality test on highest-spend campaign (Owner: Paid Media Manager, Effort: 4 hrs)
- Document data retention policies and automate deletion at expiry for each data category (Owner: Marketing Ops + Legal, Effort: 6 hrs)
- Publish first First-Party Data Health Report: match rate, segment sizes, attribution coverage, consent rate (Owner: Marketing Ops, Effort: 4 hrs)

## Example Input/Output

**Input Example:**
- Company: Veridian Commerce (fictional), B2C DTC fitness equipment brand
- Monthly website visitors: 320,000
- Known contacts in CRM (Klaviyo): 185,000
- Current tools: GA4 (browser pixel only), Klaviyo, Shopify, Meta Ads pixel, Google Ads pixel — no CDP, no server-side tracking
- Data pain points: "Meta ROAS dropped 35% after iOS 14. We cannot connect email opens to site sessions. Retargeting audiences are shrinking because pixel match rate has fallen below 40%. We do not know which email sequences are driving actual purchases vs. which are just getting opens."
- Budget for data infrastructure: $1,000-$2,500/month
- Geographies: US only (CCPA applies, no GDPR)

**Output Example (abbreviated):**

First-Party Data Audit — Top 3 Critical Gaps:

Gap 1 — Acquisition Attribution Collapse
Status: Google and Meta pixels are browser-only. iOS 14 and browser ITP block 40-60% of conversion signals from reaching ad platforms. Klaviyo captures email conversions but does not link them to the paid channel that drove the original acquisition.
Impact: Meta is optimizing campaigns against an incomplete signal set, inflating CPAs by an estimated 25-40%. Budget is likely over-indexed toward channels that appear efficient in-platform but underperform on actual revenue.
Fix: Implement Meta Conversions API via Shopify's native CAPI integration (zero engineering required). Implement Google Enhanced Conversions using Shopify's Google and YouTube app. Both are native Shopify integrations deployable in 4 hours total.

Gap 2 — Anonymous-to-Known Identity Gap
Status: 320K monthly visitors, 185K known contacts. Current identified rate: approximately 15% (DTC industry benchmark: 25-40%). Sessions are not linked to Klaviyo profiles, so email-influenced browsing behavior is invisible.
Fix: Implement Klaviyo's JavaScript snippet on all pages. When a visitor opens a Klaviyo email and clicks through, Klaviyo automatically identifies the browser session and links it to the subscriber profile — no CDP required at this stage. Estimated match rate improvement: from 15% to 30-35% within 30 days.

Gap 3 — Post-Purchase Signal Gap
Status: Shopify purchase events are in Klaviyo but post-purchase behavior (product reviews, support interactions, repurchase timing) is not used to trigger sequences.
Fix: Enable Shopify-Klaviyo native sync for Order Placed, Order Fulfilled, Refund Issued, and Review Submitted events. Use these to trigger: post-purchase sequences (day 3, 14, 45), refund recovery sequences, and review request flows. Estimated incremental revenue from post-purchase sequences: 8-15% of total email revenue within 60 days.

CDP Recommendation for Veridian Commerce:

Rank 1: RudderStack Cloud Starter ($750/month at 320K MTUs)
Rationale: Native Shopify source connector pulls all order and customer events automatically. Native Klaviyo and Meta CAPI destination connectors. Warehouse sync to BigQuery or Snowflake for attribution modeling. Engineering effort: 20-30 hours for full implementation. Better value than Segment at this traffic volume with a comparable destination library.

Rank 2: Segment (Twilio) — Growth tier ($1,250/month at 320K MTUs)
Rationale: Best-in-class Shopify integration, 450+ destination connectors, strong documentation. Higher cost but lower engineering effort than RudderStack. Ideal if the team has limited technical resources and needs faster time-to-value.

Rank 3: No CDP — Klaviyo plus Shopify native plus CAPI direct ($0 additional)
Rationale: For a US-only DTC brand at this stage, native Shopify-Klaviyo sync, Klaviyo's built-in identity stitching, Shopify's CAPI for Meta, and Google Enhanced Conversions covers 80% of activation use cases without any CDP investment. Revisit when monthly visitors exceed 1M or multi-warehouse data modeling is needed.

Top 3 Audience Segments — Immediate Activation:

Segment 1: High-Intent Browsers Not Yet Converted
Definition: Klaviyo profile OR anonymous session | Viewed product page 3 or more times in 7 days | No purchase in last 12 months | Not in active cart abandonment flow
Size: approximately 8,500 profiles per month
Activation: Meta Custom Audience (hashed email via CAPI) — Dynamic Product Ads. Google Ads Customer Match — Shopping campaign bid multiplier +35%. Klaviyo browse abandonment flow triggered at 2-hour mark.
Personalization: Show the specific product viewed, not a generic catalog. Include social proof: "4,800 customers rated this 4.8 stars." Add urgency only if inventory is genuinely low.

Segment 2: One-Time Buyers in Repurchase Window
Definition: Klaviyo profile | Exactly 1 lifetime purchase | Purchase date 35-50 days ago | Product category is consumable or replaceable | No second purchase
Size: approximately 3,200 profiles per month
Activation: Klaviyo 3-email sequence on Day 35 (replenishment reminder), Day 42 (10% loyalty discount), Day 50 (last chance). Meta exclusion: suppress from new customer acquisition campaigns.
Expected lift: 18-24% repurchase rate within 60 days of sequence enrollment vs. 9% without outreach.

Meta CAPI Implementation — Veridian Commerce:
Events to cover: Purchase, AddToCart, ViewContent, InitiateCheckout, Lead
Event Match Quality target: 7.5+ (vs. current estimated 4.2 with browser pixel only)
Deduplication: Pass event_id equal to Shopify order_id for purchases and session_id for behavioral events — Meta deduplicates automatically when both browser pixel and CAPI fire the same event_id
Timeline: Shopify App Store installation — 45 minutes. Full event QA in Meta Events Manager — 2 hours. Total effort: 3 hours.

## Success Metrics
- First-party data match rate improves from baseline to 30%+ for B2C and 20%+ for B2B within 90 days
- Meta Event Match Quality score reaches 7.0+ for all conversion events within 30 days of CAPI implementation
- Google Enhanced Conversions closes 20-35% of the conversion gap vs. browser-only pixel
- Behavioral trigger email sequences generate 10-20% of total email revenue within 60 days of activation
- CDP is fully implemented with all priority sources and destinations connected within 90 days
- Data subject deletion requests are processable end-to-end (CRM to CDP to all destinations) within 72 hours
- Attribution reporting covers 85%+ of actual conversions vs. previous browser-cookie baseline

## Related Prompts
- [Marketing Technology Stack Audit Engine](./Marketing-Technology-Stack-Audit-Engine.md)
- [Marketing Automation Workflow Architecture Engine](./Marketing-Automation-Workflow-Architecture-Engine.md)
- [Customer LTV CAC Optimization Engine](../Advanced-Marketing-Intelligence/Customer-LTV-CAC-Optimization-Engine.md)
- [Marketing Attribution ROI Engine](../Campaign-Performance-Analysis/Marketing-Attribution-ROI-Engine.md)

## Integration Tips
- **Segment (CDP):** Use Segment's Functions feature to build custom transformations that standardize event naming conventions across Shopify, HubSpot, and your product database before events reach any destination — this prevents the silent data quality rot that corrupts attribution over time.
- **RudderStack:** Use RudderStack's Transformations to add consent status as a property on every event (pulling from your CMP via a cookie read). This ensures that non-consented profiles are automatically excluded at the event level, not just at the destination level — the cleanest GDPR implementation.
- **HubSpot (B2B):** Use HubSpot's Custom Events API to push CDP events directly into the HubSpot contact timeline. This creates a chronological behavioral history on each contact record visible to sales reps — dramatically improving outreach quality by showing which pages were visited, which content was consumed, and which product features were used before the rep calls.
- **Klaviyo (B2C):** Klaviyo's native Shopify integration is underutilized by most brands. Enable "Automatic Segment Syncing" to push Klaviyo segments to Meta as Custom Audiences on a daily refresh. This eliminates the need for a separate CDP for the Meta activation use case at early stage.
- **Google Sheets / Notion:** Build a "First-Party Data Health Dashboard" that tracks weekly: identified visitor rate, email match rate, Meta EMQ score, server-side event coverage percentage, and consent opt-in rate. Review monthly with the full marketing team to catch data quality degradation before it impacts campaign performance.
- **Zapier / Make.com:** Automate weekly Customer Match audience uploads to Google Ads and LinkedIn: trigger on schedule, pull hashed email list from Klaviyo or HubSpot via API, format and upload to Google Ads Customer Match API, and log upload status to Google Sheet. Replaces a recurring manual ops task.
- **Claude API automation:** Feed weekly CDP event volume, match rate metrics, and audience size changes into a Claude API prompt that generates a "First-Party Data Health Digest" — a plain-language summary of what improved, what degraded, and what action to take. Post the digest to a Slack channel every Monday morning.

## Troubleshooting

**Issue: Meta Event Match Quality score remains below 6.0 even after CAPI implementation**
Fix: EMQ is primarily driven by the quality of match parameters sent with each event. Audit which parameters you are currently sending: email (hashed), phone (hashed), first name, last name, city, state, zip, country, date of birth, and external ID. The most impactful parameters are hashed email and hashed phone — ensure both are captured at checkout and passed with every Purchase event. If phone capture is below 30% on your forms, add a phone field with a copy incentive ("Get SMS-only offers"). Each additional match parameter typically improves EMQ by 0.3-0.8 points. Target: send at least 5 match parameters per event.

**Issue: CDP identity stitching is creating merged profiles that combine two different people**
Fix: This happens when probabilistic matching is too aggressive — typically IP-based matching in a household or office where multiple people share an IP. Reduce probabilistic matching confidence threshold or disable IP-based stitching for audiences that include shared-IP environments (B2B office workers, households). Use strictly deterministic matching (hashed email only) as the primary stitching signal. Implement a "split profile" workflow for cases where two different emails are associated with the same device before any login event.

**Issue: Consent Mode v2 is causing a significant apparent drop in observed conversions in Google Analytics and Google Ads**
Fix: This is expected behavior — Consent Mode uses modeled conversions to fill gaps where consent is not granted. The apparent drop is not real revenue decline; it is the removal of previously overcounted conversions that relied on third-party cookies. To validate true conversion volume, compare against your CRM's new deal or order count for the same period. If you see more than a 15% discrepancy between modeled GA4 conversions and CRM actuals, check your Consent Mode implementation: ensure ad_storage and analytics_storage consent signals are firing correctly via your CMP, and that the Google tag is loading in the correct sequence relative to the CMP decision in GTM.

## Version History
- v1.0: Initial creation (auto-generated)
