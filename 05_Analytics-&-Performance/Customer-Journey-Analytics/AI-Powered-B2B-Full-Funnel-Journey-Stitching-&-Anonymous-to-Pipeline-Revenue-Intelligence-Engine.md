# AI-Powered B2B Full-Funnel Journey Stitching & Anonymous-to-Pipeline Revenue Intelligence Engine - Connect Every Touchpoint From First Anonymous Visit to Closed Revenue

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** b2b, customer-journey, attribution, anonymous-visitor, full-funnel, revenue-intelligence, saas, ga4, cdp, salesforce, hubspot, journey-stitching, pipeline-analytics

## Overview
Builds a complete data architecture and analytics framework that stitches anonymous buyer touchpoints (dark funnel website visits, content consumption, paid ad impressions) to known lead records to open opportunities to closed-won revenue — giving you a single continuous journey view per buyer and account. Use this when your attribution data has a "black hole" before lead creation, your first-touch credit is wrong because buyers visited you 12 times before filling a form, or you can't explain to your CFO how top-of-funnel investment created bottom-of-funnel pipeline.

## Quick Copy-Paste Version

You are a senior B2B marketing analytics architect specializing in customer journey intelligence and revenue attribution. I need you to design a complete system for stitching anonymous buyer touchpoints to pipeline revenue across the full funnel.

My context:
- Company type: [B2B SaaS / Enterprise Software / Professional Services]
- Average ACV: [$X]
- Average sales cycle: [X days]
- Monthly unique website visitors: [X]
- Monthly new leads / MQLs: [X]
- CRM: [Salesforce / HubSpot]
- Marketing automation: [Marketo / HubSpot / Pardot]
- Website analytics: [GA4 / Segment / Amplitude]
- CDP or identity resolution tool: [Segment / RudderStack / mParticle / None]
- Visitor intelligence tool: [6sense / Clearbit / Warmly / RB2B / None]
- Biggest current gap: [e.g., "We have no data on what anonymous visitors did before converting," "Our first-touch attribution is almost always paid search because that's where people convert but we know they saw us elsewhere first," "We can't stitch mobile and desktop sessions for the same person"]

Please deliver:

1. **Journey stage taxonomy** — Define 6 stages from first anonymous signal to closed-won, with specific behavioral definitions for what qualifies a buyer for each stage transition, and what data is available at each stage (anonymous vs. known vs. enriched)

2. **Identity resolution architecture** — The technical approach for stitching anonymous visitor IDs (cookies, device fingerprints) to known person IDs (email, CRM contact ID) at conversion, including how to handle cross-device journeys and the exact tools/APIs to use

3. **Pre-conversion data recovery playbook** — Specific queries and data pipeline steps to retroactively associate anonymous session history to a contact record at the moment they fill a form, including GA4 → CRM linkage logic

4. **Journey gap analysis framework** — How to identify where buyers are falling out of the journey (not just funnel conversion rates but the specific pages, content pieces, or time gaps that precede abandonment), with SQL-style pseudocode for the analysis

5. **Revenue attribution model** — A specific attribution formula that allocates pipeline credit across the full journey including pre-known touchpoints, with a weighting rationale that a CFO would accept as credible

6. **Automated alerts and activation triggers** — 5 specific automated workflows triggered by journey intelligence (e.g., "Account visited pricing page 3+ times in 14 days but no contact has responded to outbound — trigger SDR alert")

Make every recommendation implementable with named tools and specific configuration steps, not abstract frameworks.

## Advanced Customizable Version

ROLE: You are a VP of Marketing Analytics and Revenue Operations with 14 years of B2B SaaS experience across companies from seed-stage to post-IPO. You specialize in customer data infrastructure, journey analytics, multi-touch attribution, and building measurement systems that connect marketing investment to revenue with statistical credibility. You've built journey stitching systems on Segment, Salesforce, GA4, Marketo, and Snowflake. You understand both the business requirement (prove marketing ROI) and the technical implementation (data engineering, SQL, API integrations). You've presented attribution models to boards and survived CFO scrutiny.

---

COMPANY PROFILE:
- Company: [Company Name]
- Stage / ARR: [e.g., Series B / $25M ARR | Series C / $80M ARR | Pre-IPO / $200M ARR]
- Business model: [SaaS / Usage-based / Hybrid SaaS+Services]
- ACV: [$X] | Average sales cycle: [X days] | Win rate: [X%]
- GTM motion: [Inbound-led / Outbound-led / PLG+Sales-Assist / Pure Enterprise]
- ICP: [Company size, industry, buying personas — e.g., "100-2,000 employee B2B SaaS companies, buyers are VP Marketing and RevOps Director"]

---

CURRENT TECH STACK:
- CRM: [Salesforce / HubSpot — include which edition/tier]
- Marketing automation: [Marketo / HubSpot / Pardot / ActiveCampaign]
- Website analytics: [GA4 — include measurement ID / Segment — include workspace details]
- Customer data platform: [Segment / RudderStack / mParticle / Tealium / None]
- Identity resolution / visitor intelligence: [6sense / Clearbit Reveal / Warmly / RB2B / Albacross / None]
- Data warehouse: [Snowflake / BigQuery / Redshift / None yet]
- BI / reporting: [Looker / Tableau / Metabase / native CRM dashboards]
- Session recording / heatmap: [Hotjar / FullStory / Microsoft Clarity / None]
- Ad platforms running: [Google Ads / LinkedIn / Meta / G2 / Programmatic / list all]

---

CURRENT MEASUREMENT GAPS (check all that apply):
- [ ] No visibility into what anonymous visitors did before form fill — first touch is always the conversion source
- [ ] Can't stitch mobile sessions to desktop sessions for the same buyer
- [ ] No account-level journey view — only individual contact journeys
- [ ] Can't connect ad impressions to website sessions (impression → visit stitching)
- [ ] Dark funnel activity (G2 views, community engagement, podcast listens) not tracked at all
- [ ] Journey data lives in 4+ systems with no unified view
- [ ] Pre-conversion journey data is lost after 90 days (GA4 data retention)
- [ ] Can't distinguish new business journeys from expansion journeys for existing customers

---

JOURNEY ARCHITECTURE OBJECTIVES:
- Primary goal: [e.g., "Prove that content investment drives pipeline, not just traffic" / "Build a first-party data asset that survives cookie deprecation" / "Identify the 3-5 touchpoints that most reliably precede an enterprise deal"]
- Board/CFO reporting requirement: [e.g., "Show marketing's contribution to pipeline with a model the CFO accepts" / "Demonstrate ROI on $2M content investment"]
- Sales team pain: [e.g., "AEs go into calls blind on what the prospect has already consumed" / "SDRs are reaching out to accounts with no engagement context"]
- Compliance constraints: [GDPR / CCPA / both / none — affects what pre-conversion data you can retain]

---

DELIVERABLES:

**SECTION 1: JOURNEY STAGE ARCHITECTURE**

Define a 6-stage full-funnel journey model specific to this company:

For each stage, provide:
- Stage name and behavioral definition
- Minimum qualifying signals (what data must exist for a buyer to be classified here)
- Data availability state (anonymous / partially known / fully known / enriched)
- Average duration at this stage based on [ACV] and [sales cycle length]
- The stage transition trigger (what event moves a buyer to the next stage)
- What marketing plays are appropriate at this stage

Stages to define:
1. **Dark Signal** (pre-site — third-party intent, community activity, social engagement)
2. **Anonymous Visitor** (on-site but not yet identified — cookie/device ID only)
3. **Identity-Resolved Visitor** (still anonymous but IP-matched to account via visitor intelligence tool)
4. **Known Lead** (form fill, trial signup, or enrichment-triggered identification)
5. **Engaged Prospect** (MQL-equivalent based on behavioral engagement score)
6. **Active Opportunity** (SQL through closed-won/lost)

---

**SECTION 2: IDENTITY RESOLUTION TECHNICAL ARCHITECTURE**

Design the identity graph for this company's stack:

2a. **Anonymous Identity Layer**
- How to create and persist a visitor UUID across sessions (first-party cookie approach)
- The specific GA4 client_id capture and CRM write-back mechanism
- Cross-device stitching approach using [CDP or email-based matching]
- How to handle Safari ITP / Firefox ETP impact on cookie persistence

2b. **Identity Merge Event (The "Stitch Moment")**
- Exact technical steps when a visitor submits a form: capture GA4 client_id from cookie, pass as hidden field, write to CRM contact record, trigger retroactive session association
- Code snippet (JavaScript) for capturing GA4 client_id from cookie on form submission
- Salesforce or HubSpot field configuration for storing the anonymous visitor ID
- The webhook or API call that associates pre-conversion sessions to the contact record in your data warehouse

2c. **Account-Level Journey Assembly**
- How to aggregate individual contact journeys to an account-level view in Salesforce
- The specific Salesforce custom object or HubSpot association model for storing account journey milestones
- How to handle multiple stakeholders from the same company (buying committee journey assembly)

---

**SECTION 3: PRE-CONVERSION DATA RECOVERY**

Provide specific implementation steps for recovering anonymous journey data:

3a. **GA4 → CRM Retroactive Linkage**
- The BigQuery export query to pull all sessions associated with a GA4 client_id in the 90 days before form fill
- How to enrich those historical sessions with the now-known contact identity
- The data pipeline architecture (GA4 → BigQuery → transformation → CRM enrichment)

3b. **Ad Platform Impression-to-Visit Stitching**
- How to use LinkedIn Insight Tag and Google Ads conversion linker to associate ad exposure to on-site behavior
- The UTM parameter architecture for full-journey tracking across all paid channels
- How to handle view-through attribution for display and LinkedIn impression data

3c. **Dark Funnel Signal Integration**
- How to ingest G2 Buyer Intent, Bombora, or 6sense intent signals as pre-conversion journey signals
- The data schema for storing third-party intent signals alongside first-party session data
- How to weight third-party intent signals vs. owned touchpoints in the attribution model

---

**SECTION 4: JOURNEY ANALYTICS AND GAP IDENTIFICATION**

4a. **Funnel Visualization Specification**
Design the exact analytics views needed:
- Anonymous visitor → Identity-resolved account → Known lead conversion rate by traffic source
- Time-in-stage analysis: Average days spent at each journey stage, with breakdown by deal size, industry, and entry channel
- Journey path analysis: The 10 most common content consumption sequences in the 30 days before opportunity creation
- Stage regression analysis: Percentage of leads that stall or regress, and the behavioral signals that predict stall

4b. **Journey Gap Identification Framework**
For each stage transition, specify:
- The conversion rate benchmark (use realistic B2B SaaS benchmarks if company-specific data not available)
- The top 3 causes of stage stall or drop-off
- The specific behavioral signals that distinguish buyers who advance vs. stall
- The intervention play triggered when a buyer shows stall signals

4c. **Revenue Impact of Journey Optimization**
- How to calculate the incremental pipeline value of a 10% improvement at each stage transition
- A/B testing framework for journey optimization experiments (what to test, how to measure, minimum sample size)
- The dashboard specification for tracking journey optimization program ROI

---

**SECTION 5: ATTRIBUTION MODEL DESIGN**

5a. **Full-Funnel Attribution Formula**
Design a custom attribution model that:
- Allocates credit to pre-conversion anonymous touchpoints (not just post-form-fill)
- Accounts for time decay (recent touches get more credit than 90-day-old touches)
- Differentiates between "awareness" touches (gave them their first exposure) vs. "conversion" touches (triggered the form fill) vs. "acceleration" touches (re-engaged a stalled deal)
- Is explainable in plain English to a CFO who will challenge every assumption

Provide:
- The specific weight allocation formula (as a mathematical expression, not vague principles)
- A worked example: Take a fictional 7-touch journey and show exactly how credit distributes
- The 3 scenarios where this model will produce counterintuitive results and how to explain them
- How to validate the model against historical closed-won data to confirm predictive accuracy

5b. **Reporting Hierarchy**
Specify the 5 reports that fully describe marketing's revenue contribution:
- Report 1: Channel-level attributed pipeline (with full-funnel vs. last-touch comparison)
- Report 2: Content asset pipeline influence (which pieces accelerate deals, not just generate leads)
- Report 3: Account journey velocity by deal size cohort
- Report 4: Pre-conversion investment ROI (e.g., "40% of closed-won deals had 5+ anonymous sessions before we ever knew who they were — here's the investment that drove those sessions")
- Report 5: Journey stage conversion optimization dashboard

---

**SECTION 6: AUTOMATED ACTIVATION TRIGGERS**

Design 8 automated workflows triggered by journey intelligence:

For each workflow, provide:
- Trigger condition (specific behavioral signal or journey state, with threshold values)
- The automated action (notification, sequence enrollment, ad audience update, CRM task creation)
- The tool that executes it (Salesforce Flow, HubSpot Workflow, Marketo Smart Campaign, Segment Destination, etc.)
- Expected business impact (what revenue outcome does this workflow protect or accelerate)
- How to measure if the workflow is working

Workflows to include:
1. **High-intent anonymous account alert** — Account with 3+ visits to pricing/ROI pages in 14 days but no known contact → alert SDR to find and engage buying committee
2. **Stalled opportunity re-engagement trigger** — Opportunity with no champion engagement for 21+ days + account still visiting website → trigger personalized video outreach from AE
3. **Competitive research detected** — Known contact visits competitor comparison pages → immediately surface battlecard to AE and add to competitive sequence
4. **Stage regression rescue** — Lead that was MQL regresses to cold status (60 days no engagement) but account still has anonymous visitors → trigger re-nurture with new angle content
5. **Deal acceleration signal** — Multiple new anonymous visitors from same account domain appear while deal is in Proof of Concept stage → alert AE that buying committee is expanding their research
6. **Champion departure detection** — Primary champion contact changes jobs (detected via LinkedIn/Clearbit enrichment) → trigger multi-stakeholder re-engagement campaign to same account
7. **Win-back journey trigger** — Churned customer account begins anonymous research activity that mirrors pre-purchase journey pattern → alert CS and marketing for coordinated win-back
8. **ICP account journey activation** — Net-new ICP-fit account (not in CRM) begins high-intent journey (5+ sessions, 3+ pages, pricing visit) → trigger account creation, ICP enrichment, and SDR notification

---

OUTPUT FORMAT:

Deliver this as an implementation blueprint organized by the 6 sections above. For each technical component:
- Specify the exact tools, APIs, or queries to use (not generic "use your CDP")
- Where relevant, include pseudo-code, JSON schemas, or SQL structure
- Flag the 3 highest-risk implementation dependencies (what can cause this to break in production)
- Estimate implementation effort in engineering days for a team with 1 marketing engineer and access to Salesforce admin

Close with a prioritized 90-day implementation roadmap: what to build in weeks 1-4 (foundational identity layer), weeks 5-8 (attribution model), and weeks 9-12 (automated activation).

## Example Input/Output

**Input Example:**

Company: Fieldpath — B2B SaaS, $18M ARR Series B
ACV: $45,000 | Sales cycle: 87 days | Win rate: 22%
GTM: Inbound-led with SDR team for enterprise ($100K+ ACV) assist
ICP: Operations and Supply Chain leaders at mid-market manufacturers (200-2,000 employees)
Stack: Salesforce Enterprise, HubSpot Marketing Hub Pro, GA4, no CDP, 6sense Team tier, LinkedIn + Google Ads
Biggest gap: "We know buyers are researching us heavily before converting — our SDRs often hear 'yeah we've been watching you for months' on discovery calls — but our CRM shows first touch as the paid search click that drove the form fill. We're not getting credit for the brand investment that warmed those accounts."

**Output Example (condensed):**

**Journey Stage Architecture for Fieldpath:**

Stage 1: Dark Signal — 6sense intent spike (Manufacturing + Operations keyword cluster, surge score >60) or LinkedIn post engagement with Fieldpath content by uncaptured persona. No person ID available; only account-level signal from 6sense. Average duration: 14–45 days. Transition trigger: first on-site session from account domain.

Stage 2: Anonymous Visitor — Session from IP address matching a manufacturing company in ICP size range, no form fill. GA4 client_id assigned. 6sense de-anonymizes domain to company (e.g., "Werner Industries, 850 employees, Milwaukee"). Average duration: 7–21 days. Transition trigger: 3+ sessions OR pricing/ROI calculator page visit.

Stage 3: Identity-Resolved Visitor — Same as Stage 2 but 6sense has matched the visiting company to a Salesforce Account record. Marketing automation now knows the account is actively researching. Can run targeted LinkedIn ads to matched company. Average duration: 5–14 days. Transition trigger: any contact at the account fills a form OR SDR creates a contact after receiving a Stage 2 alert.

Stage 4: Known Lead — Form fill (demo request, content download, webinar registration). Stitch event fires: JavaScript captures GA4 client_id from cookie → passes to hidden HubSpot form field → HubSpot writes ga_client_id to Contact record → Segment (added to stack in Week 1 implementation) queries BigQuery for all GA4 sessions matching that client_id in last 90 days → retroactively associates those sessions to HubSpot Contact via enrichment. Average duration: 3–7 days to MQL qualification.

**Identity Stitch Implementation (Fieldpath-Specific):**

// Add to all HubSpot forms via HubSpot's "Additional Form Options" → Custom Code
window.addEventListener('message', function(event) {
  if (event.data.type === 'hsFormCallback' && event.data.eventName === 'onFormReady') {
    // Get GA4 client_id from cookie
    function getGA4ClientId() {
      var match = document.cookie.match(/_ga=GA\d\.\d\.(\d+\.\d+)/);
      return match ? match[1] : null;
    }
    var clientId = getGA4ClientId();
    if (clientId) {
      var hiddenField = document.querySelector('input[name="ga_client_id"]');
      if (hiddenField) hiddenField.value = clientId;
    }
  }
});

HubSpot contact property to create: `ga_client_id` (single-line text, not shown in forms, written by above script).

**Attribution Model (Fieldpath Worked Example):**

Buyer journey: Jordan Webb, Operations Director at Werner Industries
- Day -67: 6sense surge signal (Fieldpath not aware yet) → 0% credit (dark signal, pre-engagement)
- Day -52: Anonymous visit, 3 pages, 8 min (6sense resolves to Werner Industries) → 12% credit (Awareness anchor — first time Fieldpath "met" this account)
- Day -38: LinkedIn ad impression, "Supply Chain Visibility" campaign → 5% credit (brand reinforcement)
- Day -31: Anonymous return visit, downloaded ROI calculator PDF (anonymous) → 15% credit (high-intent pre-conversion engagement)
- Day -22: LinkedIn Thought Leader ad click on VP of Ops case study → 8% credit (proof-point engagement)
- Day -14: Anonymous visit to pricing page → 18% credit (commercial intent signal — most predictive of near-term conversion)
- Day -3: Google Ads branded search click → 12% credit (conversion facilitator — they were already convinced, searched your brand)
- Day 0: Demo request form fill → 15% credit (conversion event)
- Day 14: Case study email clicked, champion forwarded to CFO → 15% credit (acceleration/champion activation)

Attribution result: 47% of pipeline credit goes to pre-form-fill touchpoints. Without journey stitching, 100% would go to branded Google search.

**Automated Workflow #1 — High-Intent Anonymous Account Alert:**

Trigger: 6sense account score >75 AND 3+ page views in last 14 days AND no open Opportunity in Salesforce AND no Contact with "Contacted" status from this account domain in last 30 days.
Action: Salesforce Flow creates a Task for the territory SDR: "High-intent anonymous account — Werner Industries has 6 visits this week including Pricing. No active contact. Priority: find and engage 2 buying committee members." Task priority: High. Due: tomorrow.
Tool: Salesforce Flow + 6sense Salesforce integration (native).
Impact: In pilot testing with 20 similar accounts at Fieldpath's peer companies, SDR outreach triggered by this signal converted to opportunity at 3.2x the rate of cold outbound.

## Success Metrics

- **Stitch rate:** Percentage of new contacts where pre-conversion journey data was successfully recovered — target 70%+ within 60 days of implementation
- **Attribution model acceptance:** CFO and CRO sign off on using full-funnel attribution model for quarterly business reviews (binary: yes/no within 90 days)
- **Pre-conversion pipeline credit:** Percentage of closed-won pipeline where pre-known touchpoints receive attribution credit — track month-over-month as implementation matures
- **Workflow trigger accuracy:** Percentage of high-intent anonymous account alerts that result in an identified contact within 30 days — target >25% (benchmark: 6–12% for cold outbound)
- **Journey velocity improvement:** Average days from Stage 2 (Anonymous Visitor) to Stage 4 (Known Lead) — should decrease 15–25% as activation workflows optimize handoffs
- **Reporting adoption:** Percentage of weekly marketing reviews that reference full-funnel attribution data vs. last-touch — target 100% within 60 days of dashboard launch

## Related Prompts

- [AI-Powered B2B Customer Journey Intelligence & Multi-Touch Buyer Path Optimization Intelligence Engine](./AI-Powered-B2B-Customer-Journey-Intelligence-&-Multi-Touch-Buyer-Path-Optimization-Intelligence-Engine.md)
- [Dark Funnel Attribution & Anonymous Buyer Intent Intelligence Engine](../Attribution-&-Revenue-Analytics/Dark-Funnel-Attribution-&-Anonymous-Buyer-Intent-Intelligence-Engine.md)
- [AI-Powered B2B Anonymous Visitor Intelligence & Account Pipeline Identification Engine](../Website-Analytics-&-Behavioral-Intelligence/AI-Powered-B2B-Anonymous-Visitor-Intelligence-&-Account-Pipeline-Identification-Engine.md)
- [AI-Powered B2B Anonymous Website Visitor De-Anonymization & Account-Based Outbound Trigger Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Inbound-Marketing/AI-Powered-B2B-Anonymous-Website-Visitor-De-Anonymization-&-Account-Based-Outbound-Trigger-Intelligence-Engine.md)

## Integration Tips

- **Salesforce:** Create a custom Contact field `GA4_Client_ID__c` (Text, 50 chars) and an Account-level rollup that shows all unique GA4 client IDs across related contacts. Use a Salesforce Flow that fires on Contact creation to query your data warehouse for pre-conversion sessions via an Apex callout to your data pipeline API.
- **HubSpot:** Add `ga_client_id` as a Contact property. Use the HubSpot Operations Hub Data Quality Automation or a native workflow to pass the value to Salesforce on sync. HubSpot's Contact Timeline can display retroactively associated sessions as custom Timeline events via the Timeline Events API.
- **GA4 + BigQuery:** Enable GA4 BigQuery Export (free for GA4 360, standard for free tier with 1M events/day limit). Key table: `events_*` — query by `user_pseudo_id` (GA4's client_id equivalent) to pull all sessions for a given visitor. Join to contact records using the `ga_client_id` field populated at form fill.
- **Segment / RudderStack:** Create an `Identify` call at form submission that merges the anonymous `anonymousId` (cookie-based) with the `userId` (email or CRM ID). Segment's Identity Graph feature (Unify) or RudderStack's Identity Resolution automatically retroactively associates prior anonymous events to the now-known user across all downstream tools.
- **6sense / Clearbit:** Use the Salesforce or HubSpot native integration to write account-level journey signals (intent surges, page visit events) directly to Account records. Configure webhook-based alerts to Slack (#sales-intelligence channel) for high-intent anonymous accounts rather than waiting for CRM notification review.
- **Snowflake / BigQuery (data warehouse):** Build a `unified_buyer_journey` table that joins GA4 sessions, CRM contacts/accounts, MAP engagement events, and intent provider signals on a shared `account_domain` key. This becomes the single source of truth for all journey analytics and powers BI dashboards in Looker or Tableau.

## Troubleshooting

**Problem:** GA4 client_id capture script fires but the value written to HubSpot/Salesforce is blank or null for 30–40% of form fills.
**Solution:** This typically means the GA4 cookie (`_ga`) hasn't loaded before the form ready event fires, or Safari ITP has deleted it. Fix: (1) Add a 500ms setTimeout before the cookie read in the JavaScript snippet. (2) Add a fallback that reads from `window.dataLayer` for GTM-based GA4 implementations. (3) For Safari, implement server-side first-party cookie via your domain's own subdomain (e.g., analytics.yourcompany.com) to extend persistence to 7 days from the default 7-day ITP limit.

**Problem:** The attribution model gives implausibly high credit to anonymous touchpoints and the CRO doesn't believe the data, calling it "marketing gaming the numbers."
**Solution:** Run a shadow period: show both last-touch attribution and full-funnel attribution side-by-side for 60 days without changing any decisions. Present the calibration analysis — show that accounts with 5+ pre-conversion sessions closed at 2x the rate of accounts with 1 session (the correlation validates the model). Invite the CRO and one AE to review 10 specific closed-won journeys together and verify that the pre-conversion touchpoints shown actually make sense given what they know about those deals. Social proof from AEs ("yes, I knew Werner had been watching us for months") validates the model better than any statistical argument.

**Problem:** Journey stitching is working but the retroactive session data in BigQuery is only 60 days old for most contacts, leaving a gap for long-cycle enterprise deals.
**Solution:** GA4 standard data retention is 14 months at the event level but defaults to 2 months for user-level data. Immediately change GA4 data retention setting to 14 months (Admin → Data Settings → Data Retention → User and event data retention → 14 months). For deals already in progress, retroactive recovery beyond your current retention window is not possible from GA4 alone — use 6sense or Bombora historical intent data as a proxy for pre-site activity before the retention window. Going forward, pipe all GA4 events to BigQuery via continuous export to create a permanent archive with no retention limit.

## Version History
- v1.0: Initial creation (auto-generated)
