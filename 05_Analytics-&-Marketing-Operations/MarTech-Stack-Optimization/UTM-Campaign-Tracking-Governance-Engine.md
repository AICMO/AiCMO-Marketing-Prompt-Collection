# UTM Campaign Tracking Governance Engine - Complete UTM Taxonomy & Data Integrity System for Marketing Teams

**Difficulty:** Intermediate | **Time:** 15 min | **Tags:** analytics, martech, attribution, operations, b2b, b2c, data-quality

## Overview
Generates a complete, organization-wide UTM tracking taxonomy, naming convention library, and data governance ruleset so every campaign is tracked consistently, attribution reports are trustworthy, and marketing can prove revenue contribution without fighting dirty data. Use this when setting up a new marketing stack, auditing broken attribution, or onboarding a new team to campaign tracking standards.

## Quick Copy-Paste Version

You are a marketing operations expert. Design a complete UTM tracking system for my marketing team.

My situation:
- Company type: [B2B SaaS / B2C ecommerce / D2C / other]
- Main channels we run: [e.g., Google Ads, LinkedIn Ads, email newsletters, organic social, partner referrals, events]
- CRM/Analytics tools: [e.g., HubSpot + Google Analytics 4 + Salesforce]
- Team size managing campaigns: [e.g., 4 people across paid, content, email]

Deliver the following:

1. UTM PARAMETER TAXONOMY TABLE
For each of my channels, define the exact values for utm_source, utm_medium, utm_campaign (naming pattern), utm_content, and utm_term. Use a consistent hierarchy so I can filter and group data reliably in GA4/HubSpot.

2. CAMPAIGN NAMING CONVENTION
A formula for utm_campaign that captures: channel category, campaign type, target audience or product, and launch quarter. Example pattern: [channel]-[type]-[audience]-[quarter]. Show examples for at least 5 different campaign types.

3. GOVERNANCE RULES (10 non-negotiable rules)
The rules every team member must follow — things like "always lowercase," "no spaces (use hyphens)," "utm_source must match the exact approved list." Format as a one-page reference card.

4. APPROVED VALUES MASTER LIST
A table I can paste into a shared Google Sheet: approved utm_source values, approved utm_medium values, campaign type codes. This becomes our single source of truth.

5. URL BUILDER TEMPLATE
A Google Sheets formula (=CONCATENATE or similar) that auto-builds UTM URLs when team members fill in a form — eliminates typos at the source.

6. AUDIT CHECKLIST
10 questions to run monthly to catch UTM drift before it corrupts attribution reports.

Output everything in a format I can immediately share with my team as a Notion page or Google Doc.

## Advanced Customizable Version

ROLE: You are a senior Marketing Operations architect with 12+ years of experience building revenue attribution systems for B2B SaaS and D2C companies. You've seen what happens when UTM governance breaks down — attribution collapses, channel credit gets misassigned, and finance questions every marketing dollar. You build systems that are simple enough for a junior coordinator to follow but rigorous enough to survive a CFO audit.

CONTEXT:
- Company: [Company Name]
- Business model: [B2B SaaS / B2C / D2C / Marketplace / PLG / Sales-led]
- Annual marketing budget: [e.g., $2M / $500K / $200K]
- Active channels: [List all: Paid Search, Paid Social (LinkedIn/Meta/TikTok), Email (HubSpot/Klaviyo/Marketo), Organic Social, Influencer/Creator, Affiliate/Partner, Events/Field, Content/SEO, Referral Programs, PR/Earned]
- MarTech stack: [e.g., GA4 + HubSpot CRM + Salesforce + Looker]
- Attribution model in use: [First-touch / Last-touch / Linear / Time-decay / Data-driven / W-shaped]
- Team members who create UTMs: [e.g., Paid Manager, Email Manager, Content Manager, Agency Partner]
- Current problems: [e.g., "utm_source has 47 variations of 'linkedin'", "agency uses different naming than internal team", "can't distinguish brand vs. non-brand paid search in HubSpot"]
- Reporting cadence: [Weekly / Monthly / Quarterly board reporting]

OBJECTIVE: Build a complete, enterprise-grade UTM Campaign Tracking Governance System that (1) standardizes all campaign tracking, (2) enables accurate multi-touch attribution, (3) is simple enough for non-technical team members to follow without making errors, and (4) produces clean data that CRMs and BI tools can reliably ingest.

---

DELIVERABLE 1: MASTER UTM TAXONOMY TABLE

For each channel, define all five UTM parameters with approved values. Format as a structured table:

| Channel | utm_source | utm_medium | utm_campaign Pattern | utm_content | utm_term |
|---------|-----------|------------|---------------------|-------------|---------|

Channel categories to cover:
- Paid Search (branded vs. non-branded; Google vs. Bing)
- Paid Social (each platform gets its own utm_source — never "social")
- Email (distinguish transactional, newsletter, nurture, sales outreach, lifecycle)
- Organic Social (distinguish each platform; flag that organic is harder to track)
- Display / Programmatic
- Affiliate & Partner referrals
- Events (pre-event, at-event, post-event follow-up)
- Direct Mail / Offline (QR code campaigns)
- Influencer / Creator campaigns
- Retargeting campaigns (distinguish from prospecting)

CRITICAL RULES to enforce in the taxonomy:
- utm_source = WHERE (the platform/publisher): always lowercase, no spaces, use approved list only
- utm_medium = HOW (the mechanism): cpc, email, social, display, referral, affiliate, event, direct — never invent new values
- utm_campaign = WHAT (the specific campaign): use the naming formula below, always lowercase with hyphens
- utm_content = WHICH CREATIVE (ad variant, email subject line code, CTA version)
- utm_term = TARGET KEYWORD or AUDIENCE (paid search keywords; for non-search, use audience segment code)

---

DELIVERABLE 2: CAMPAIGN NAMING FORMULA

Design a utm_campaign naming convention that captures all the metadata needed for reporting without being so long it becomes unusable.

Required formula elements:
- Channel category code (2-3 chars): e.g., ps=paid-search, ls=linkedin, me=meta, em=email, ev=event
- Campaign type code: e.g., pb=pipeline-building, rt=retargeting, ab=ABM, nrt=nurture, lch=launch
- Audience/segment code: e.g., smb, mm=midmarket, ent=enterprise, icp-[vertical], persona-[name]
- Product/feature (if product line company): abbreviated product name
- Quarter: q1-26, q2-26, etc.
- Optional: A/B test variant indicator: -va, -vb

Full formula: {channel-code}-{type-code}-{audience}-{product}-{quarter}{-variant}

Examples for 8 different campaign types:
1. LinkedIn ABM campaign targeting enterprise CFOs in Q1 2026: ls-ab-ent-cfo-q1-26
2. Google Ads non-brand search for SMB: ps-nb-smb-core-q1-26
3. HubSpot email nurture for mid-market prospects: em-nrt-mm-core-q1-26
4. Meta retargeting for free trial users: me-rt-trial-core-q1-26
5. Event pre-registration email for SaaStr 2026: ev-pre-ent-core-q1-26
6. LinkedIn content ad for ICP awareness (B2B fintech vertical): ls-aw-icp-fintech-q1-26
7. Affiliate/partner referral from specific partner: ref-{partnername}-q1-26
8. A/B test variant B of paid search brand campaign: ps-br-all-core-q1-26-vb

---

DELIVERABLE 3: DATA GOVERNANCE RULEBOOK

Write a governance rulebook in plain language that any team member (including an agency partner or intern) can follow. Include:

SECTION A — THE 12 COMMANDMENTS (non-negotiable rules)
Write each rule as a one-sentence imperative. Cover:
1. Case sensitivity (always lowercase — GA4 and HubSpot are case-sensitive)
2. Space prohibition (always hyphens, never spaces or underscores)
3. Source list compliance (only approved values — no improvising)
4. One URL per ad/email variant (never reuse UTM URLs across different campaigns)
5. Paid vs. organic separation (utm_medium=cpc for paid; utm_medium=social for organic — never mix)
6. Email campaign UTMs (all marketing emails must have UTMs; transactional emails must NOT have utm_medium=email)
7. Agency accountability (agencies must submit UTM spreadsheet for approval before campaigns go live)
8. Redirect rules (UTM parameters must survive redirects — test before launch)
9. UTM on every external link (in emails, ads, and any paid or owned distribution)
10. Never UTM-tag internal links (internal navigation UTMs overwrite incoming source data — common mistake)
11. Document before launch (all campaign UTMs logged in the master tracker before the campaign goes live)
12. Test in staging (verify UTMs fire correctly in GA4 before spending budget)

SECTION B — COMMON MISTAKES & FIXES
For each mistake, write: What went wrong → How to detect → How to fix

Mistakes to cover:
- utm_source="LinkedIn" vs "linkedin" vs "linkedin-ads" vs "lnkd" (case chaos)
- utm_medium="paid social" (space breaks tracking)
- Using utm_medium="website" (not a valid medium type)
- Forgetting UTMs on email footer CTAs
- Agency overwriting your naming convention
- UTMs not surviving URL redirects
- Paid search keywords with spaces not encoded (%20 vs +)

---

DELIVERABLE 4: APPROVED VALUES MASTER LIST

Create a definitive reference table for all approved values. This becomes the locked sheet in your UTM builder spreadsheet.

Format as three tables:

TABLE A — APPROVED utm_source VALUES
| Source Value | Platform/Channel It Represents | Notes |
|-------------|-------------------------------|-------|
(Include: google, bing, linkedin, meta, facebook, instagram, tiktok, twitter, youtube, newsletter, hubspot, marketo, klaviyo, salesforce, [partner-name], direct, qr-[event-name], and 10+ more)

TABLE B — APPROVED utm_medium VALUES (strict list — no additions without Marketing Ops approval)
| Medium Value | When to Use |
|-------------|------------|
(Include: cpc, email, social, display, referral, affiliate, organic, event, direct, sms, push, podcast, influencer, video)

TABLE C — CAMPAIGN TYPE CODES
| Code | Full Name | When to Use |
|------|-----------|------------|

---

DELIVERABLE 5: GOOGLE SHEETS UTM BUILDER

Provide complete Google Sheets formulas for an automated UTM builder. Include:

Sheet structure:
- Input columns: Source (dropdown), Medium (dropdown), Campaign Name (auto-generated or manual), Content, Term, Base URL
- Output column: Complete UTM URL built by formula
- Validation rules: Data validation dropdowns for Source and Medium locked to approved lists

Formulas to provide:
1. UTM URL builder formula (CONCATENATE with IF statements to handle empty utm_term/content gracefully)
2. Campaign name auto-builder (concatenates channel code + type code + audience + quarter from separate input cells)
3. URL length checker (warns if URL exceeds 2,000 characters — a real-world paid search issue)
4. Duplicate URL checker (COUNTIF to flag if the same UTM combination has been used before)

Also provide: Zapier/Make automation description to auto-log every new UTM URL into the master tracker when it's generated.

---

DELIVERABLE 6: MONTHLY UTM AUDIT CHECKLIST

15 diagnostic questions to run monthly in GA4 and your CRM to catch UTM drift before it corrupts quarterly reports.

For each question, specify: where to look (GA4 report, HubSpot report, Salesforce view), what healthy looks like vs. red flag, and what action to take if flagged.

Organize by urgency:
- Critical (attribution-breaking) — run weekly
- Important (data quality issues) — run monthly
- Hygiene (naming consistency) — run quarterly

---

DELIVERABLE 7: STAKEHOLDER ROLLOUT PLAN

Brief plan for rolling out this UTM governance system to the team. Include:
- Communication template to send to all campaign managers (3-sentence announcement + link to master doc)
- Onboarding checklist for new team members and agency partners (10 items)
- Enforcement mechanism: what happens when someone breaks the rules (automated Slack alert via GA4 anomaly detection, monthly audit review, etc.)
- Retroactive fix guide: how to handle historical UTM chaos without breaking reporting continuity (hint: create a UTM mapping table in GA4 / Looker, not by changing historical data)

CONSTRAINTS:
- All naming conventions must work across GA4, HubSpot, Salesforce, and any standard BI tool without custom parsing
- The system must be simple enough that an intern can follow it after a 15-minute orientation
- Every convention must have a documented "why" — teams that understand the reason follow rules better than teams given mandates
- Flag any conventions that differ for GA4 vs. Universal Analytics if the company is mid-migration
- Account for iOS14+ tracking limitations and UTM reliance increasing for paid social attribution

## Example Input/Output

**Input Example:**

Company: Fortera (B2B SaaS, Series B, $14M ARR, HR tech platform for mid-market companies)
Channels: Google Ads (brand + non-brand), LinkedIn Ads, HubSpot email (newsletters + nurture), organic social (LinkedIn + Twitter), events (2 hosted webinars/quarter + 3 conferences/year), partner referrals (5 active partners)
Stack: GA4 + HubSpot CRM + Salesforce + Looker
Team: Paid Manager (internal), Email Manager (internal), Agency (runs LinkedIn Ads), Content Manager (owns organic)
Problems: "Agency uses 'LinkedIn_Ads' as utm_source; our team uses 'linkedin'; HubSpot shows 3 different source values for the same channel and we can't get clean attribution."

---

**Output Example (Deliverable 1 excerpt):**

**MASTER UTM TAXONOMY TABLE — FORTERA**

| Channel | utm_source | utm_medium | utm_campaign Pattern | utm_content | utm_term |
|---------|-----------|------------|---------------------|-------------|---------|
| Google Ads — Brand Search | google | cpc | ps-br-[audience]-core-[quarter] | Ad headline variant (e.g., h1-trust, h1-roi) | Keyword (lowercase, hyphens) |
| Google Ads — Non-Brand | google | cpc | ps-nb-[audience]-[product]-[quarter] | Ad variant ID | Primary keyword group |
| LinkedIn Ads — Prospecting | linkedin | cpc | ls-pb-[audience]-[product]-[quarter] | Creative ID or description (e.g., video-testimonial, img-stat) | Audience segment code (e.g., hrbp-mm) |
| LinkedIn Ads — Retargeting | linkedin | cpc | ls-rt-[segment]-[product]-[quarter] | Creative variant | Audience segment |
| HubSpot Newsletter | newsletter | email | em-nl-all-core-[quarter] | CTA location (e.g., cta-header, cta-inline) | (leave blank) |
| HubSpot Nurture | hubspot | email | em-nrt-[stage]-[product]-[quarter] | Email # in sequence (e.g., email-3) | (leave blank) |
| Partner Referral — Lattice | lattice | referral | ref-lattice-[quarter] | (leave blank) | (leave blank) |
| Hosted Webinar Pre-Reg | fortera-events | event | ev-pre-[webinar-name]-[quarter] | Invite email vs. reminder email | (leave blank) |

**APPROVED utm_source VALUES (partial)**

| Source Value | Represents | NEVER Use |
|-------------|-----------|-----------|
| google | All Google products (Search, Display, YouTube via paid) | Google, google-ads, Google_Ads, gads |
| linkedin | All LinkedIn paid and organic | LinkedIn, linkedin-ads, LinkedIn_Ads, lnkd |
| newsletter | Fortera marketing newsletter | email, marketing-email |
| hubspot | HubSpot-triggered nurture/lifecycle emails | hs, hubspot-email |
| lattice | Partner Lattice referral links | partner, lattice.com |

**AGENCY NOTICE (copy-paste into your agency brief):**
> "Fortera uses a locked UTM taxonomy. All LinkedIn Ads campaigns must use utm_source=linkedin (lowercase, no spaces, no underscores). Any deviation from the Approved Values Master List will be flagged in our weekly attribution audit and will require manual remapping. Please download the UTM builder sheet at [link] and submit your proposed UTM tags for approval before any campaign goes live. Campaigns launched without pre-approved UTMs will be paused until corrected."

---

**Output Example (Deliverable 5 — Google Sheets formula):**

=IF(A2="","",A2&"?"&"utm_source="&B2&"&utm_medium="&C2&"&utm_campaign="&D2&IF(E2="","","&utm_content="&E2)&IF(F2="","","&utm_term="&SUBSTITUTE(F2," ","+")))

Where: A2=Base URL, B2=utm_source, C2=utm_medium, D2=utm_campaign, E2=utm_content, F2=utm_term

Campaign auto-builder:
=LOWER(VLOOKUP(B2,ChannelCodes!A:B,2,0)&"-"&VLOOKUP(C2,TypeCodes!A:B,2,0)&"-"&D2&"-"&E2&"-"&TEXT(TODAY(),"q")&RIGHT(YEAR(TODAY()),2))

## Success Metrics

- Zero new utm_source variants appear in GA4 within 30 days of rollout (measure via "Source / Medium" report — flag any value not on the approved list)
- HubSpot/Salesforce "Unknown" or "Direct" traffic drops by 20%+ as previously untagged campaigns get UTMs applied
- Monthly UTM audit takes under 30 minutes (a sign the system is working, not that you're drowning in exceptions)
- Attribution reports pass a CFO review — finance can see channel-level spend vs. pipeline with no "Unknown" category above 5% of total
- New campaign UTMs are generated in under 2 minutes using the URL builder sheet (vs. manual construction)
- Agency and internal team generate zero conflicting source values for the same platform within 60 days

## Related Prompts

- [`./Marketing-Automation-Workflow-Architecture-Engine.md`](./Marketing-Automation-Workflow-Architecture-Engine.md)
- [`./Marketing-Technology-Stack-Audit-Engine.md`](./Marketing-Technology-Stack-Audit-Engine.md)
- [`../Campaign-Performance-Analysis/Marketing-Attribution-ROI-Engine.md`](../Campaign-Performance-Analysis/Marketing-Attribution-ROI-Engine.md)
- [`../KPI-Dashboard-Creation/Marketing-Performance-Dashboard-Generator.md`](../KPI-Dashboard-Creation/Marketing-Performance-Dashboard-Generator.md)

## Integration Tips

- **Google Analytics 4**: Navigate to Reports → Acquisition → Traffic Acquisition, then add utm_source as a secondary dimension to immediately audit which source values are coming through. Set up a GA4 custom alert to notify you when a new utm_source value appears that isn't on your approved list.
- **HubSpot**: Use HubSpot's "Original Source Drill-Down 1 and 2" properties to map UTM values to contact records. Create a HubSpot property-based list of contacts where Original Source Drill-Down 1 contains "linkedin" (any casing) and merge/standardize to clean historical data without deleting it.
- **Salesforce**: Build a Campaign Source picklist in Salesforce that mirrors your approved utm_source list exactly. Use Flow or Process Builder to auto-populate Campaign Source from UTM data passed through your web form → HubSpot → Salesforce sync, so revenue attribution in Salesforce closes the loop.
- **Google Sheets**: Share the UTM builder sheet with your agency via a "view + comment" permission level. Lock the approved values dropdown sheets so they can't be edited. Version-control the approved values tab with a changelog column.
- **Zapier/Make**: Build a Zap that watches the UTM Builder sheet for new rows, logs each new UTM URL to a master campaign tracker Notion database with fields: Campaign Name, UTM URL, Owner, Launch Date, Channel, Budget. This creates an auditable UTM registry that survives team turnover.
- **Looker/Metabase**: Create a "UTM Health Score" dashboard that tracks: % of sessions with UTMs, # of unapproved utm_source values, % of pipeline with known source attribution. Run this as a standing 5-minute agenda item in weekly Marketing Ops standups.

## Troubleshooting

**Problem: Historical UTM data is a mess — 40+ variants of "linkedin" in GA4 and you can't retroactively fix it.**
Solution: Don't touch historical data. Instead, create a UTM mapping table in Looker or Google Sheets that normalizes raw UTM values to canonical channel names for reporting purposes (e.g., "LinkedIn" → "linkedin", "linkedin-ads" → "linkedin", "lnkd" → "linkedin"). Apply this mapping layer in all reports going forward. Set a "data quality start date" in your dashboards — all attribution reporting references data from this date forward once the new governance is live. Communicate this clearly to leadership so they understand why historical vs. current data may look different.

**Problem: The URL builder formula breaks when the base URL already has query parameters (e.g., landing pages with ?variant=b).**
Solution: Use `&` instead of `?` when the base URL already contains a `?`. Add an IF statement: `=IF(ISNUMBER(FIND("?",A2)),A2&"&",A2&"?")&"utm_source="...` This checks whether the base URL already has a query string and uses the correct connector character.

**Problem: Agency keeps creating new UTM naming conventions because "the client's system is too complex."**
Solution: The UTM builder sheet solves this — they fill in dropdowns, the formula builds the URL. If the agency still deviates, add a contractual UTM compliance clause to your SOW: "Agency agrees to use client-provided UTM taxonomy for all campaign tracking. URLs deviating from the approved taxonomy will be corrected within 24 hours at no additional cost." The goal is to make compliance easier than deviation, not to win a compliance battle.

## Version History
- v1.0: Initial creation (auto-generated)
