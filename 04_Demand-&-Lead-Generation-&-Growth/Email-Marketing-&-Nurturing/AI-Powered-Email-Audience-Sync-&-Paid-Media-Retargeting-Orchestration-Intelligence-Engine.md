# AI-Powered Email Audience Sync & Paid Media Retargeting Orchestration Intelligence Engine - Unified Email-to-Ad Revenue Coordination System

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** email-marketing, paid-media, retargeting, audience-sync, omnichannel, b2b-saas, d2c, customer-match, revenue-attribution

## Overview
Designs and operates a closed-loop system that synchronizes your email subscriber list with paid advertising platforms — Meta, LinkedIn, Google, TikTok — to retarget engaged openers with ads, suppress already-converting contacts to save budget, and build revenue-weighted lookalike audiences. Use this when your email program and paid media are running in separate silos and you're leaving pipeline on the table by not coordinating both channels around the same buyer journey.

## Quick Copy-Paste Version

You are a senior demand generation strategist who has managed integrated email + paid media programs for B2B SaaS and D2C companies. You understand customer data platforms, audience matching, and cross-channel attribution deeply.

Design a complete email audience sync and paid media retargeting orchestration system for the following company:

Company: [Your Company Name]
Business model: [B2B SaaS / D2C / E-commerce / PLG SaaS]
Email platform: [HubSpot / Klaviyo / Marketo / Mailchimp / ActiveCampaign]
Paid media platforms active: [Meta / LinkedIn / Google / TikTok — list all]
Monthly email list size: [e.g., 45,000 subscribers]
Current average email open rate: [e.g., 28%]
Monthly paid media budget: [e.g., $40,000]
Average deal value or AOV: [e.g., $12,000 ACV for B2B / $85 AOV for D2C]

Deliver:

1. **Audience Segmentation Architecture** — Define 6–8 email-derived audiences to sync to paid platforms. For each: segment name, qualification criteria (engagement signals + CRM fields), estimated size, which paid platforms to activate on, and the strategic goal (retarget, suppress, or expand via lookalike).

2. **Engagement-Based Retargeting Sequences** — Design a coordinated email + paid media sequence for 3 high-priority scenarios:
   - Scenario A: Opened last 3 emails, clicked once, no demo booked
   - Scenario B: Downloaded gated content 14+ days ago, went cold
   - Scenario C: Active trial user who hasn't upgraded after 21 days
   For each scenario: the email touch, the retargeting ad that runs in parallel, the message angle, and the handoff signal to sales.

3. **Suppression Strategy** — Define exactly who to exclude from paid acquisition campaigns and why: recent customers, active opportunities in CRM, high-engagement subscribers already in nurture, recently churned accounts. Estimate monthly budget savings from proper suppression.

4. **Lookalike Audience Build Plan** — Identify 2–3 seed audiences from your email list (e.g., top 10% most engaged, customers with >120% NRR, closed-won deals in last 90 days) and specify how to build, size, and test lookalikes on each platform.

5. **Attribution & Measurement Framework** — Define the multi-touch attribution model that credits both email and paid media touches across the buyer journey. Include the KPIs to track weekly, and a simple spreadsheet structure for cross-channel ROI reporting.

Write every recommendation as an actionable workflow, not a strategy slide. Include the exact steps in HubSpot or Klaviyo + the corresponding steps in Meta/LinkedIn Ads Manager.

## Advanced Customizable Version

ROLE: You are a VP of Revenue Marketing and Marketing Technology with 15+ years running sophisticated email + paid media programs at B2B SaaS companies ($10M–$500M ARR) and high-growth D2C brands. You think in terms of audience architecture, customer data infrastructure, and cross-channel revenue impact — not vanity metrics. You have deep expertise in customer match technologies, CDPs, identity resolution, first-party data strategy, and multi-touch attribution.

---

BUSINESS CONTEXT:
Company: [Company Name]
Industry vertical: [e.g., HR Tech / Fintech / E-commerce / DevTools / Healthcare SaaS]
Business model: [B2B SaaS / PLG SaaS / D2C / Marketplace / Hybrid]
Revenue model: [Subscription $X/mo / Transactional / Freemium→Paid / Usage-based]
Current ARR/Annual Revenue: [$X]
Average contract value / AOV: [$X]
Sales motion: [Self-serve / Sales-assisted / Enterprise / Product-Led]
Target buyer: [Job title, company size, industry — be specific]

EMAIL PROGRAM DETAILS:
Email platform: [HubSpot / Klaviyo / Marketo / Pardot / Customer.io / Braze / Mailchimp]
Total list size: [X subscribers]
Active (engaged last 90 days): [X subscribers]
Current segmentation approach: [e.g., persona-based / lifecycle stage / engagement score / flat list]
Average open rate: [X%] | Click rate: [X%] | Unsubscribe rate: [X%]
Existing automation flows: [e.g., welcome series, behavioral triggers, drip nurture]
CRM connected: [HubSpot / Salesforce / Pipedrive] — with bidirectional sync? [Yes/No]

PAID MEDIA STACK:
Active platforms: [Meta Ads / LinkedIn Ads / Google Ads / TikTok Ads / YouTube / Programmatic]
Monthly paid media budget: [$X total, broken down by platform if available]
Current ROAS or CPL benchmarks: [e.g., Meta CPL $85, LinkedIn CPL $310]
Current audience strategy: [Interest-based / Lookalike / Retargeting pixel / Account list / None]
Attribution model in use: [Last-touch / Linear / Data-driven / Unknown]

TECH STACK & DATA:
CDP or data layer: [Segment / RudderStack / Amplitude / Mixpanel / None]
Identity resolution tool: [LiveRamp / Clearbit / Apollo / None]
Data warehouse: [BigQuery / Snowflake / Redshift / None]
Consent management: [OneTrust / Cookiebot / None — GDPR/CCPA status]
Email list upload method currently: [Manual CSV / API sync / Zapier / Segment / None]

BUSINESS OBJECTIVES (rank top 3):
[ ] Increase qualified pipeline from existing subscribers
[ ] Reduce paid CAC by suppressing already-engaged contacts
[ ] Accelerate trial → paid conversion through coordinated touches
[ ] Expand into new accounts via lookalike audience targeting
[ ] Improve attribution accuracy across email + paid channels
[ ] Reduce wasted ad spend on existing customers

---

DELIVERABLE 1 — AUDIENCE ARCHITECTURE BLUEPRINT

Design a complete taxonomy of email-derived audiences for paid media activation. For each audience:

**Audience Name:**
**Source data:** [Which email fields + CRM fields + behavioral signals qualify a contact]
**Qualification logic:** [Boolean rules — e.g., "opened ≥2 emails in last 30 days AND job title contains 'VP' AND company_revenue > $50M AND NOT Opportunity.StageName IN ('Closed Won','Customer')"]
**Estimated segment size:** [X contacts]
**Platform activation:** [Which platforms — Meta / LinkedIn / Google / TikTok]
**Match rate expectation:** [e.g., LinkedIn ~55–70%, Meta ~70–85%, Google ~50–65%]
**Activation goal:** [Retarget with bottom-of-funnel offer / Suppress from prospecting / Seed for lookalike / Upsell/cross-sell]
**Recommended bid adjustment:** [e.g., +30% for high-intent segments on LinkedIn]
**Refresh frequency:** [Daily / Weekly — sync cadence]
**Privacy compliance note:** [Consent basis for upload — legitimate interest / explicit consent]

Required audiences to design (minimum 8):
1. High-Intent Openers — opened 3+ emails in last 30 days, never converted
2. Content Downloaders — downloaded gated content 7–60 days ago, no sales activity
3. Trial Non-Converters — active trial, day 14–25, not upgraded
4. Dormant MQLs — qualified but no activity in 45–90 days
5. Closed-Won Customers — suppress from acquisition + retarget for expansion
6. Active Opportunities — suppress from brand awareness, retarget with deal-acceleration content
7. Champion Movers — contacts who have changed jobs (use Clearbit/Apollo enrichment)
8. Revenue-Weighted Seed Audience — customers with highest LTV for lookalike creation
9. [Optional] Competitive Churned — former customers who left for a competitor
10. [Optional] Event Registrants — webinar attendees who haven't booked a demo

---

DELIVERABLE 2 — CHANNEL ORCHESTRATION PLAYBOOKS

For each of the following 5 buyer scenarios, design a fully coordinated email + paid media sequence:

**SCENARIO TEMPLATE:**

Buyer Scenario: [Describe the buyer's current state and what they need next]
Trigger condition: [The data event that kicks off this playbook]
Duration: [Total sequence length]
Goal: [Desired action by end of sequence]

| Day | Email Touch | Paid Media Running Simultaneously | Message Theme | Success Signal |
|-----|-------------|-----------------------------------|---------------|----------------|
| 0   | ...         | ...                               | ...           | ...            |

Email specs for each touch:
- Subject line: [Write it, not describe it]
- Preview text: [Write it]
- Body copy hook (first 2 sentences): [Write it]
- CTA: [Specific call-to-action]
- If-no-open logic: [Variant subject line + timing]

Paid ad specs running in parallel:
- Platform: [Meta / LinkedIn / Google Display]
- Ad format: [Single image / Carousel / Video / Sponsored Content]
- Headline: [Write it]
- Body: [Write it — 125 characters max for Meta, 150 for LinkedIn]
- CTA button: [Learn More / Book Demo / Start Free Trial]
- Landing page: [Where they click to]
- Spend recommendation: [$X/day for this audience segment]

Handoff-to-sales trigger: [The signal that fires a Sales task in CRM — e.g., clicked paid ad + opened email on same day]

Design playbooks for these scenarios:
1. Warm-but-Stalled: High email engagement, no conversion in 21 days
2. Content-Qualified Lead: Downloaded 2+ resources, visited pricing page
3. Trial Day 18: In-trial, moderate product usage, approaching trial end
4. Re-engagement: 60-day dormant, high historical email engagement
5. Expansion Target: Customer in contract renewal window, using only 1 of 3 modules

---

DELIVERABLE 3 — SUPPRESSION FRAMEWORK & BUDGET PROTECTION

Build a comprehensive suppression architecture that protects budget and prevents brand damage.

For each suppression segment:
**Segment Name:**
**Suppression Logic:** [Boolean criteria]
**Platforms to suppress on:** [All / specific platforms]
**Rationale:** [Why suppressing this group protects budget or improves experience]
**Exception cases:** [When to override — e.g., suppress from prospecting but keep in retargeting]
**Estimated monthly ad spend saved:** [$X — calculate based on CPM × audience size]

Required suppression segments:
- Active customers (by CRM field: Customer = True)
- Open pipeline opportunities above threshold ACV
- Unsubscribes and global optouts (legal requirement)
- Contacts engaged in live email nurture sequences
- Recent event registrants already receiving post-event emails
- Contacts flagged as competitors or press
- Internal employees and agency partners

Calculate: Total estimated monthly budget protection = $[X] based on [X] suppressed contacts × avg CPM × estimated impression frequency

---

DELIVERABLE 4 — LOOKALIKE & EXPANSION AUDIENCE STRATEGY

Design the seed audiences and expansion strategy for each paid platform.

For each seed audience:
**Seed Audience Name:**
**Qualification criteria:** [Who makes the cut — revenue threshold, engagement score, job title, etc.]
**Seed size:** [Minimum recommended: 1,000 for Meta, 300 for LinkedIn, 1,000 for Google]
**Quality signal:** [What makes this a strong seed — e.g., 94% customer retention, avg $18K ACV]
**Lookalike size targets:** [Start at 1% (precision), test 2–3% (scale)]
**Platform-specific notes:**
  - Meta: Use Value-Based Lookalike with LTV field from CRM
  - LinkedIn: Use Matched Audiences with Account List for ABM expansion
  - Google: Use Customer Match with similar audiences enabled
**Expected CPL vs. interest-based targeting:** [Estimate % improvement — typically 20–40% lower CPL]
**Refresh cadence:** [Monthly — add new customers, remove churned]

Seed audiences to build:
1. Top 20% LTV Customers (high-value lookalike)
2. Closed-Won Last 90 Days (recent win pattern lookalike)
3. Multi-Product Customers (expansion lookalike)
4. Champions-by-Job-Title (persona-matched lookalike)

---

DELIVERABLE 5 — ATTRIBUTION MODEL & MEASUREMENT SYSTEM

Design a cross-channel attribution model that gives proper credit to both email and paid media.

**Attribution Model Selection:**
Recommend which model fits this company's sales cycle and why:
- Last-touch: Simple, biases toward bottom-of-funnel
- Linear: Equal credit, good for long cycles
- Time-decay: Weights recent touches, good for 30–60 day cycles
- Position-based (U-shaped): Credits first and last touch most
- Data-driven (algorithmic): Best for high-volume programs with ML

**Touch Classification Framework:**
Define how to classify each touchpoint:
- Email opens: [Awareness touch / No credit / Intent signal]
- Email clicks: [Mid-funnel touch — X% credit]
- Paid ad impression: [Awareness touch / View-through — X% credit]
- Paid ad click: [Direct intent touch — X% credit]
- Email click → paid ad click same day: [Coordinated touch — X% credit, log as sequence]

**Weekly Dashboard KPIs:**

| Metric | Target | Alert Threshold | Owner |
|--------|--------|-----------------|-------|
| Email → Ad cross-channel click rate | ...    | ...             | ...   |
| Suppression coverage % (customers excluded from acq.) | 100% | <95% | ...   |
| Lookalike CPL vs. interest-based CPL | ...    | ...             | ...   |
| Pipeline influenced by email + paid coordinated sequences | ... | ... | ...   |
| Budget saved from suppression | $X/mo  | ...             | ...   |

**Reporting Cadence:**
- Daily: Audience sync status check (did uploads fire? match rates?)
- Weekly: Cross-channel sequence performance review
- Monthly: Full attribution analysis — pipeline influenced by coordinated vs. single-channel
- Quarterly: Audience architecture audit — add new segments, retire stale ones

---

DELIVERABLE 6 — TECHNICAL IMPLEMENTATION GUIDE

Provide step-by-step setup instructions for each integration:

**HubSpot → Meta Custom Audiences:**
1. In HubSpot: Create Active List with [criteria]
2. Connect via HubSpot Ads integration: Settings → Ads → Meta Business Account
3. Sync list to Meta: Ads > Audiences > Create Custom Audience > Customer List > HubSpot sync
4. Set refresh: Daily automatic sync
5. Verify match rate in Meta Ads Manager > Audiences (allow 24–48 hours)
6. Confirm GDPR consent field is mapped: HubSpot "GDPR consent" = Meta "has_data_processing_agreement"

**HubSpot → LinkedIn Matched Audiences:**
1. In HubSpot: Create Smart List
2. Export CSV: First Name, Last Name, Email, Company, Job Title
3. LinkedIn: Campaign Manager > Plan > Audiences > Create Audience > Upload List
4. Or: Use HubSpot LinkedIn integration for auto-sync (requires Marketing Hub Enterprise)
5. List size minimum: 300 matched contacts
6. Match rate expectation: 50–70% based on email match to LinkedIn profiles

**Klaviyo → Google Customer Match:**
1. In Klaviyo: Create Segment
2. Google integration: Klaviyo > Integrations > Google Ads > Sync Segment
3. Google Ads: Audience Manager > Customer lists > verify sync status
4. Enable Similar Audiences (Similar Segments) in Google Ads settings

**Suppression Automation (Zapier/Make):**
Trigger: HubSpot Contact Property "Lifecycle Stage" → Changes to "Customer"
Action 1: Add to HubSpot suppression list "Active Customers — All Platforms"
Action 2: Trigger Meta Conversion API event (mark as customer)
Action 3: Slack notification to RevOps: "[Contact Name] now customer — removed from all acquisition audiences"

---

DELIVERABLE 7 — PRIVACY COMPLIANCE CHECKLIST

[ ] All contacts in paid media upload lists have explicit consent for advertising use OR valid legitimate interest basis documented
[ ] Unsubscribes are suppressed within 24 hours across all platforms (automate via webhook)
[ ] Customer list uploads use hashed PII (SHA-256 email hashing) — verified for Meta and Google
[ ] LinkedIn data processing agreement signed in Campaign Manager
[ ] Privacy policy updated to disclose use of customer data for advertising
[ ] Annual audit of data retention — remove contacts from audiences after [X months] of inactivity
[ ] CCPA "Do Not Sell" requests mapped to audience suppression workflow

## Example Input/Output

**Input Example:**

Company: Mosaic Analytics — B2B SaaS for financial planning (FP&A) software
Business model: B2B SaaS, sales-assisted, $28K average ACV
Email platform: HubSpot Marketing Hub Enterprise
Paid platforms: LinkedIn Ads (primary), Meta Ads (secondary for brand), Google Ads (search + display)
List size: 38,000 contacts (12,000 engaged last 90 days)
Open rate: 31% | Click rate: 4.2%
Monthly paid media budget: $55,000 ($35K LinkedIn, $12K Google, $8K Meta)
CRM: Salesforce, synced bidirectionally with HubSpot

**Output Example (Audience Architecture excerpt):**

---

**Audience 1: High-Intent Finance Leaders — Warm Openers**
Source: HubSpot Active List
Qualification logic:
- Email opened ≥ 3 times in last 30 days
- AND Job Title contains [CFO, VP Finance, Director FP&A, Financial Planning]
- AND Company Employee Count > 200
- AND NOT Salesforce Opportunity Stage IN (Closed Won, Customer)
- AND NOT Global Email Opt-Out = True

Estimated size: ~1,850 contacts
Platform activation: LinkedIn Ads (primary), Meta Ads (secondary)
LinkedIn match rate: ~62% → ~1,150 matched profiles
Meta match rate: ~74% → ~1,370 matched profiles
Activation goal: Retarget with mid-funnel content — ROI calculator, customer case study (CFO at similar company)
Recommended LinkedIn bid: Target CPC $12–$18, increase bid by +35% for Director+ titles
Refresh frequency: Daily sync via HubSpot Ads integration
Spend allocation: $4,200/month for this segment (LinkedIn $3,000 + Meta $1,200)

Coordinated sequence:
- Day 0–3: Email "How Acme Corp cut FP&A cycle time by 40%" → LinkedIn Sponsored Content showing same case study
- Day 4–7: If no email click → LinkedIn Message Ad from [SDR Name], reference content they engaged with
- Day 8: If still no conversion → Meta retargeting ad "Start your free demo" with social proof from a CFO
- Day 9: HubSpot workflow fires SDR task: "High-intent warm lead — engaged across email + paid × 9 days"

Estimated pipeline contribution: $420K/quarter (based on 12% conversion from warm retarget to demo, $28K ACV, 15 demos/quarter from this segment)

---

**Suppression Segment: Active Mosaic Customers**
Logic: Salesforce Account Type = Customer AND Contract Status = Active
Size: 2,340 accounts (~4,100 contacts)
Suppress on: LinkedIn (exclude from all prospecting campaigns), Meta (exclude from acquisition campaigns), Google (exclude from branded + generic FP&A keywords)
Exception: Keep in LinkedIn retargeting for expansion/upsell campaigns (show content on advanced modules)
Estimated monthly budget saved: $3,800 (4,100 contacts × estimated $0.93 avg CPM × 1,000 impressions/contact/month that would be wasted)

---

**Lookalike Seed: Closed-Won Deals — Last 90 Days (High Conviction)**
Seed criteria: Salesforce Opportunity Stage = Closed Won AND CloseDate >= [90 days ago] AND ACV >= $20,000
Seed size: 87 contacts (Mosaic wins ~29 deals/month × 3 months × avg 1 contact per deal)
Quality signal: These are verified buyers at ICP-fit companies — strongest possible seed
LinkedIn Lookalike: Target 2% similarity → estimated ~180,000 Finance professionals in North America
Meta Lookalike: 1% similarity → ~340,000 people matching buyer profile
Expected CPL improvement vs. interest-based: 28–35% lower CPL based on industry benchmarks
Refresh cadence: Monthly — add new wins, maintain minimum 85 contacts

## Success Metrics

**Audience Sync Health:**
- Match rate on LinkedIn: > 55% (red flag if < 40% — list quality issue)
- Match rate on Meta: > 65% (red flag if < 50%)
- Audience sync success rate: 100% (zero failed uploads)
- Time to suppress new customers from acquisition audiences: < 24 hours

**Revenue Impact:**
- Pipeline influenced by coordinated email + paid sequences: track as a dedicated pipeline source
- CPL for lookalike audiences vs. interest-based: target 25–35% reduction
- Budget saved via suppression: minimum $2,000/month per $50K monthly spend
- Conversion rate, email + paid coordinated sequences vs. email-only: target 1.4–1.8x lift

**Program Efficiency:**
- Cross-channel sequence completion rate: % of contacts who complete the full email + ad sequence
- Email-to-ad click correlation: what % of paid ad clickers also engaged with email in same week
- Audience staleness: % of audiences refreshed within last 7 days (target: 100%)

## Related Prompts

- [Behavioral Email Trigger & Lifecycle Automation Engine](./Behavioral-Email-Trigger-Lifecycle-Automation-Engine.md)
- [Lead Nurture Sequence & Pipeline Acceleration Email Engine](./Lead-Nurture-Sequence-&-Pipeline-Acceleration-Email-Engine.md)
- [../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-(PPC-&-Social)/First-Party-Data-Audience-Strategy-&-Paid-Media-Activation-Intelligence-Engine.md](../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-(PPC-&-Social)/First-Party-Data-Audience-Strategy-&-Paid-Media-Activation-Intelligence-Engine.md)
- [../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-(PPC-&-Social)/Retargeting-Remarketing-Campaign-Intelligence-Engine.md](../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-(PPC-&-Social)/Retargeting-Remarketing-Campaign-Intelligence-Engine.md)

## Integration Tips

**HubSpot Integration:**
- Use HubSpot's native LinkedIn Ads and Meta Ads integrations (Settings > Integrations > Ad Networks) for automatic list sync — no CSV uploads needed
- Build Active Lists (not Static) so audience membership auto-updates as contacts qualify/disqualify
- Use HubSpot Workflows to fire "audience added" events to Slack/Salesforce when high-value contacts enter suppression or retargeting lists
- Enable bidirectional sync: when a contact converts via a LinkedIn Lead Gen Form, have it flow back into HubSpot as a form submission with source = "LinkedIn Ad"

**Salesforce + Paid Media:**
- Use Salesforce Advertising Studio (formerly Social.com) for enterprise-grade audience sync with built-in consent management
- Or sync via Segment: Salesforce → Segment → Meta/Google/LinkedIn simultaneously
- Create a Salesforce Campaign object for each paid media audience to enable proper multi-touch attribution in Salesforce Reports

**Segment (CDP) Setup:**
- Build Segment Audiences matching your HubSpot lists — Segment can push to all paid platforms simultaneously, ensuring consistent audience membership
- Use Segment's Personas feature to build unified customer profiles that merge email engagement + product usage + CRM data into a single score
- Enable Reverse ETL to push Segment audience membership back into HubSpot as a custom contact property

**Klaviyo + Meta:**
- Use Klaviyo's Facebook Advertising integration: Lists & Segments > Click segment > Sync to Facebook
- Enable "Automatically sync new subscribers" for real-time audience updates
- Use Klaviyo's predictive analytics (predicted CLV, churn risk) to create Meta audiences sorted by predicted value

**Google Customer Match:**
- Minimum 1,000 matched users required to be eligible for use
- Hash all PII before upload (Google accepts unhashed but recommends hashed)
- Enable "Optimized targeting" OFF for suppression audiences — you want exact matches, not Google's expansion
- Enable "Similar segments" ON for lookalike expansion

## Troubleshooting

**Issue: Low LinkedIn match rates (< 40%)**
Root cause: Email addresses in your list don't match personal email addresses registered on LinkedIn. B2B contacts often use work email in your CRM but personal email on LinkedIn.
Fix: Enrich your contact list with personal email addresses using Apollo, Clearbit, or Lusha before uploading. Alternatively, add First Name + Last Name + Company Name to your CSV — LinkedIn can match on these identity fields without email. Expect match rates of 60–75% with full identity data.

**Issue: Customers keep appearing in prospecting ads after winning their deal**
Root cause: Salesforce → HubSpot sync delay, or suppression list refresh isn't running daily.
Fix: Set up a Salesforce trigger (via Zapier or Salesforce Flow) that fires immediately when Opportunity Stage → Closed Won: (1) update HubSpot lifecycle stage to Customer, (2) trigger HubSpot list refresh, (3) run Meta/LinkedIn audience update. Also add a 30-minute delayed backup trigger in HubSpot Workflows as a safety net. Target: customer suppressed within 2 hours of deal close.

**Issue: GDPR compliance uncertainty — can you upload EU contacts to Meta/LinkedIn?**
Root cause: Platform-based advertising using personal data requires a valid legal basis under GDPR.
Fix: Ensure your privacy policy discloses use of contact data for advertising. For customers and engaged subscribers, Legitimate Interest may apply if documented in your ROPA (Record of Processing Activities). For cold contacts, only upload if they have explicitly consented to advertising. Use a consent management tool (OneTrust) to tag contacts by consent level and build HubSpot lists that only include contacts with appropriate consent status. Both Meta and LinkedIn have Data Processing Agreements — ensure these are signed in your ad account settings before any upload.

## Version History
- v1.0: Initial creation (auto-generated)
