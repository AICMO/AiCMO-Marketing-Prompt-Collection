# Marketing Operations Data Quality & CRM Hygiene Intelligence Engine - Eliminate the Bad Data That's Costing You Pipeline

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** marketing-ops, crm-hygiene, data-quality, revops, hubspot, salesforce, mops, attribution, lead-management, automation

## Overview
Performs a comprehensive AI-driven audit of your marketing database and CRM data quality — scoring lead records, identifying attribution gaps, detecting duplicate and zombie records, validating UTM hygiene, and generating a prioritized remediation plan with automated workflow fixes. Use this when your pipeline data is unreliable, attribution reports don't reconcile with Salesforce, or leadership is questioning whether your MQL numbers are real.

## Quick Copy-Paste Version

You are a senior Marketing Operations analyst specializing in CRM data quality and revenue operations. Audit my marketing database and CRM data and produce a complete data quality report with prioritized fixes.

My stack and context:
- CRM: [HubSpot / Salesforce / HubSpot + Salesforce sync]
- Marketing automation: [HubSpot / Marketo / Pardot / ActiveCampaign]
- Database size: [X total contacts, X leads/contacts in CRM, X companies/accounts]
- Data sources feeding the CRM: [web forms, paid ads, list imports, SDR prospecting, events, enrichment tools like Clearbit/ZoomInfo]
- Known data problems: [e.g., "duplicate leads," "missing lead source," "UTMs not flowing through," "HubSpot–Salesforce sync failures," "zombie contacts inflating database"]
- Lead scoring in use: [Yes/No — tool: HubSpot scoring / Marketo scoring / custom]
- Average database age: [How long since a full data hygiene audit, or "never"]
- Compliance requirements: [GDPR / CCPA / both / neither]

Please deliver:
1. Data quality scoring matrix — grade each of these dimensions (A/B/C/D/F): contact completeness, lead source attribution, email validity, duplicate rate estimate, UTM hygiene, HubSpot–Salesforce sync integrity, consent/compliance fields, company/account data quality
2. Top 10 data problems — ranked by revenue impact, with root cause, blast radius estimate (how many records affected), and fix complexity
3. UTM taxonomy audit — evaluate my current UTM structure and produce a standardized UTM framework for all active channels with enforcement recommendations
4. Duplicate detection strategy — a step-by-step deduplication workflow using native CRM tools plus any recommended third-party tools
5. Zombie contact cleanup protocol — criteria for identifying and suppressing/archiving inactive contacts without losing attribution history
6. Lead source normalization — a mapping of all current lead source values to a clean, standardized taxonomy that works for attribution reporting
7. 90-day data quality remediation roadmap — prioritized sprints with effort estimates, owner assignments (MOps vs. SDR vs. Ops), and success metrics
8. Data governance SOP — a one-page standard operating procedure for maintaining data quality on an ongoing basis

## Advanced Customizable Version

ROLE: You are a VP of Marketing Operations and Revenue Operations with 12 years of B2B SaaS experience. You have managed marketing databases ranging from 50,000 to 5 million contacts across HubSpot, Marketo, and Salesforce stacks. You specialize in CRM data architecture, marketing attribution data quality, GDPR/CCPA compliance, and building self-healing data workflows. You have run data quality programs that directly recovered 20–40% of pipeline that was previously invisible due to broken attribution. You understand the technical configuration of HubSpot properties, Salesforce fields, Marketo smart lists, and integration middleware (Zapier, Make, Workato, native CRM sync).

COMPANY CONTEXT:
- Company Name: [Company Name]
- Stage / ARR: [Seed / Series A / Series B / Series C+]
- Industry vertical: [e.g., HR Tech, FinTech, DevOps, HealthTech]
- Business model: [B2B SaaS / B2B Services / PLG / Enterprise]
- ICP: [job titles, company sizes, industries]
- GTM motion: [Inbound / Outbound / PLG / ABM / Channel / Hybrid]
- Team size — MOps: [X dedicated MOps headcount or "shared RevOps team"]

TECH STACK DETAILS:
- Primary CRM: [HubSpot CRM / Salesforce / both via native sync]
  - If HubSpot: [Hub tier — Starter / Professional / Enterprise]
  - If Salesforce: [Edition — Professional / Enterprise / Unlimited]
- Marketing automation: [HubSpot Marketing Hub / Marketo / Pardot / ActiveCampaign / other]
- Sync middleware: [Native HubSpot–Salesforce sync / Zapier / Make / Workato / Tray.io / custom]
- Data enrichment: [Clearbit / ZoomInfo / Apollo / Cognism / 6sense / none]
- Intent data: [6sense / Bombora / G2 Buyer Intent / none]
- Form platform: [HubSpot forms / Unbounce / Typeform / Webflow / WordPress Gravity Forms]
- CDP in use: [Segment / mParticle / RudderStack / none]
- Ad platforms sending lead data to CRM: [Google Ads Lead Extensions / LinkedIn Lead Gen Forms / Facebook Lead Ads / other]

DATABASE CURRENT STATE:
Total records:
- Contacts/Leads: [X]
- Companies/Accounts: [X]
- Active marketing contacts (emailable): [X]
- Contacts with valid email: [X%]
- Contacts with known lead source: [X%]
- Contacts with full firmographic data (company, title, industry, size): [X%]
- Estimated duplicate rate: [X% or "unknown"]
- Last full deduplication run: [Date or "never"]
- Last consent/GDPR audit: [Date or "never"]

KNOWN DATA QUALITY ISSUES (check all that apply):
[ ] Duplicate contact records — estimate: [X% duplication rate]
[ ] Missing or incorrect lead source / lead source detail
[ ] UTM parameters not flowing from ads into CRM
[ ] HubSpot ↔ Salesforce sync conflicts or failures (specify: [field conflicts, owner assignment errors, lifecycle stage mismatches])
[ ] Zombie contacts — contacts with zero engagement in [X+ months] still in active lists
[ ] Bounce rate issues — hard/soft bounces not suppressed correctly
[ ] Invalid or role-based email addresses (info@, sales@, noreply@)
[ ] Personal email domains mixed in with business emails (gmail.com, yahoo.com)
[ ] Inconsistent lead lifecycle stages — contacts stuck in wrong stages
[ ] Missing or incorrect MQL timestamps — MQL date doesn't match actual scoring threshold crossing
[ ] Lead assignment routing errors — leads going to wrong owners or falling into no-owner black hole
[ ] Contact-to-Account matching failures — contacts not associated with correct account
[ ] Campaign membership gaps — contacts influenced by campaigns not recorded as campaign members
[ ] Form submissions not creating CRM records correctly
[ ] Data enrichment overwriting good data with bad enrichment data

UTM TRACKING CURRENT STATE:
- UTM structure currently in use: [describe your utm_source / utm_medium / utm_campaign / utm_content / utm_term taxonomy or "ad hoc / inconsistent"]
- UTM capture method: [Hidden form fields / URL parameter persistence / HubSpot tracking code / Google Tag Manager / cookie-based]
- Known UTM gaps: [e.g., "LinkedIn organic traffic not tracked," "events always show direct," "email clicks attributed to organic"]
- CRM field mapping: [UTMs mapped to CRM contact properties: Yes/Partial/No]

ATTRIBUTION CONTEXT:
- Current attribution model: [Last touch / First touch / HubSpot multi-touch / Salesforce campaign influence / none]
- Revenue attributed to marketing in CRM: [$X or X% of closed-won]
- Known attribution blind spots: [e.g., "SDR outbound deals show no marketing touchpoints," "dark social completely invisible," "events never get credit"]
- Finance/CEO confidence in marketing attribution data: [High / Medium / Low / "they don't trust any of it"]

COMPLIANCE REQUIREMENTS:
- Regions served: [US only / EU (GDPR) / UK (UK GDPR) / Canada (CASL) / APAC / global]
- Consent management platform: [OneTrust / Cookiebot / HubSpot consent / custom / none]
- Unsubscribe/opt-out compliance: [Fully automated / manual / unknown]
- Data retention policy: [Documented / not documented]
- Last compliance audit: [Date or "never"]

OBJECTIVES FOR THIS AUDIT:
Primary goal: [e.g., "recover missing attribution before Q2 board meeting," "reduce database cost by cutting zombie contacts," "fix HubSpot–Salesforce sync before migrating to Salesforce as system of record," "prepare for GDPR audit"]
Success metrics: [e.g., "increase contacts with known lead source from 45% to 80%," "reduce duplicate rate from 18% to <3%," "pass external GDPR audit"]
Timeline: [X weeks / X months]
Available MOps bandwidth: [X hours/week dedicated to this project]

REQUESTED DELIVERABLES:

1. DATA QUALITY SCORECARD
Grade each dimension (A = >95% clean, B = 85–95%, C = 70–85%, D = 50–70%, F = <50%) with specific metric benchmarks, current estimated score, and target score:
- Email validity and deliverability health
- Lead source attribution completeness
- Contact completeness (required fields populated)
- Account/company data quality and matching
- Duplicate record rate
- UTM hygiene and channel attribution integrity
- CRM sync integrity (if applicable)
- Consent and compliance field completeness
- Lifecycle stage accuracy and transition logic
- Campaign membership and touchpoint capture rate

Overall Database Health Score: [weighted composite — provide scoring methodology]

2. PRIORITIZED ISSUE REGISTER
For each identified issue:
- Issue name and description
- Root cause (technical / process / governance / tool configuration)
- Blast radius: estimated number of records affected
- Revenue impact: how this is distorting pipeline/attribution reporting
- Fix complexity: Easy (hours) / Medium (days) / Hard (weeks)
- Fix owner: MOps / Admin / RevOps / vendor support
- Recommended fix approach (native CRM tool / workflow / manual / third-party tool)

3. UTM TAXONOMY REBUILD
Deliver a complete standardized UTM framework:

Source taxonomy:
- Paid: google / linkedin / meta / microsoft / tiktok / reddit / youtube / [platform]
- Organic: organic-search / organic-social / direct / referral / [partner-name]
- Owned: email / newsletter / [program-name]
- Events: event / webinar / conference / [event-name]

Medium taxonomy:
- cpc / paid-social / organic / email / referral / affiliate / event / display / video / sms

Campaign naming convention: [brand]-[quarter]-[audience]-[offer]-[funnel-stage]
Example: acme-q2-mid-market-ebook-mofu

Content/creative taxonomy for A/B testing attribution: [format]-[variant]
Example: carousel-v1 / carousel-v2

UTM enforcement mechanism: [UTM builder template in Notion/Google Sheets / UTM parameter validation in CRM workflow / ad platform UTM templates]

4. DEDUPLICATION WORKFLOW
Step-by-step deduplication strategy:
- Pre-dedup analysis: identify duplicate clusters using [email / name+company / phone / enrichment ID]
- Dedup tool recommendation: [HubSpot native dedup / Dedupely / DemandTools / Cloudingo / Salesforce Duplicate Management]
- Merge logic: which record wins (newest / most complete / oldest MQL date preserved)
- Campaign history preservation: how to maintain attribution touchpoints on surviving record
- Validation step: QA sample size and spot-check process
- Ongoing prevention: duplicate prevention workflows / form duplicate detection / enrichment dedup

5. ZOMBIE CONTACT SUPPRESSION PROTOCOL
Define suppression criteria and workflow:
- Zombie definition: [no email open in X months AND no web activity in X months AND no CRM activity in X months]
- Suppression segments: [Tier 1: Hard bounce → immediate suppression / Tier 2: Chronic soft bounce → 3-strike suppression / Tier 3: Zombie engagement → re-engagement sequence before suppression]
- Re-engagement sequence design: [2-email re-permission campaign with sunset logic]
- Archive vs. delete decision: [GDPR considerations, data retention policy, attribution history preservation]
- Expected database size reduction: [X% reduction estimate]
- Cost savings estimate: [MAP pricing tier reduction, if applicable]

6. LEAD SOURCE NORMALIZATION FRAMEWORK
Current lead source chaos → clean taxonomy:
Map all existing lead source variants to standardized values:

| Raw Value (current) | Normalized Lead Source | Lead Source Detail | Channel |
|---|---|---|---|
| "hs_google_ads" | Paid Search | Google Ads | Paid |
| "linkedin" | Paid Social | LinkedIn Ads | Paid |
| "direct" | Direct | (unknown) | Unknown |
| [all current variants] | [normalized] | [detail] | [channel] |

Attribution hierarchy (when multiple sources exist): [define which source wins for lead source vs. lead source detail vs. original source]

7. AUTOMATED WORKFLOW REMEDIATION LIBRARY
Build these HubSpot/Salesforce/Marketo workflows to auto-maintain data quality:

Workflow 1 — Lead Source Backfill
Trigger: Contact created with blank Lead Source
Action: Derive Lead Source from UTM parameters → set Lead Source + Lead Source Detail

Workflow 2 — Lifecycle Stage Correction
Trigger: Contact has MQL-level score but lifecycle = Lead
Action: Set Lifecycle Stage = MQL, stamp MQL Date, notify owner

Workflow 3 — Account Matching
Trigger: New contact created with company email domain
Action: Match to existing Account by domain → associate contact if confidence >90%

Workflow 4 — Form Submission UTM Capture
Trigger: Form submission event
Action: Write utm_source, utm_medium, utm_campaign, utm_content, utm_term to contact properties (only if currently blank — no overwrite)

Workflow 5 — HubSpot-Salesforce Sync Error Alert
Trigger: Sync error detected on contact/deal record
Action: Notify MOps Slack channel + create internal task for manual review

Workflow 6 — Consent Expiry Management
Trigger: Consent date > [24 months] AND region = EU
Action: Flag for re-consent campaign, remove from active marketing lists until re-consent received

8. 90-DAY REMEDIATION ROADMAP

Sprint 1 (Days 1–30) — Stop the Bleeding:
- [ ] Implement UTM capture workflow (no-overwrite)
- [ ] Fix top 3 form-to-CRM mapping errors
- [ ] Run emergency deduplication on contacts created in last 90 days
- [ ] Suppress hard bounces and role-based emails
- [ ] Fix HubSpot–Salesforce sync errors causing attribution loss
- Success metric: Lead source attribution rate improves from X% to Y%

Sprint 2 (Days 31–60) — Clean the Database:
- [ ] Run full historical deduplication
- [ ] Execute zombie re-engagement sequence + suppression
- [ ] Normalize lead source taxonomy (backfill historical records)
- [ ] Rebuild UTM taxonomy and deploy naming convention templates
- [ ] Implement lifecycle stage correction workflows
- Success metric: Duplicate rate drops to <3%; database cost reduction realized

Sprint 3 (Days 61–90) — Build for the Future:
- [ ] Deploy full automated workflow remediation library
- [ ] Build data quality dashboard in CRM/BI tool
- [ ] Publish data governance SOP
- [ ] Train SDR/sales team on data entry standards
- [ ] Schedule quarterly data quality audit cadence
- Success metric: Data quality scorecard average grade improves from C to B+

9. DATA GOVERNANCE SOP
One-page standard operating procedure covering:
- Data entry standards (required fields, format rules, approved picklist values)
- UTM creation and approval process (who creates, how validated, where stored)
- New data source onboarding checklist (what to configure before any new form/ad/import goes live)
- Enrichment policy (which fields can be overwritten by enrichment vs. locked)
- Quarterly audit schedule and owner
- Escalation path for data quality issues

10. ROI OF DATA QUALITY
Quantify the business case for this investment:
- Pipeline recovered: X% of closed-won deals currently have zero marketing attribution → recovering attribution could shift X% of revenue to marketing-influenced
- Database cost savings: X% reduction in active contacts → estimated MAP tier savings of $X/year
- SDR productivity gain: X hours/week saved by eliminating bad leads, bounces, and duplicates in sequences
- Attribution credibility: quantify the decision-making error from current bad data (e.g., "current data suggests paid search drives 22% of pipeline; after cleanup, true figure is likely 31% — meaning $X/month in LinkedIn Ads is being underfunded")
- Compliance risk avoided: estimated cost of GDPR/CCPA violation if current gaps are not resolved

## Example Input/Output

**Example Company:** Meridian AI — Series B HR Tech SaaS, $18M ARR, 180-person company, selling to CHROs and VPs of People at mid-market companies (500–5,000 employees). Using HubSpot Enterprise + Salesforce Enterprise with native sync. 3-person MOps team.

**Sample Input:**
- Database: 95,000 contacts, 8,200 companies
- Known issues: 18% estimated duplicate rate, UTMs only captured on 55% of form submissions (Webflow forms not connected to HubSpot properly), HubSpot→Salesforce sync failing on ~200 records/week (field mapping conflict on "Lead Status"), last dedup run was 14 months ago, GDPR consent fields blank on 22,000 EU contacts
- Attribution: Marketing only getting credit for 34% of closed-won pipeline; CFO believes the number is "made up"

**Sample Output (excerpt — Data Quality Scorecard):**

| Dimension | Current Grade | Score | Target Grade | Priority |
|---|---|---|---|---|
| Email validity | B | 87% valid | A | Medium |
| Lead source attribution | D | 55% have source | B+ | CRITICAL |
| Contact completeness | C | 71% have title+company | B | High |
| Duplicate rate | F | 18% est. duplication | A | CRITICAL |
| UTM hygiene | D | 55% UTM capture rate | A | CRITICAL |
| HubSpot-SFDC sync | C | ~200 errors/week | A | High |
| Consent/compliance | F | 22K EU contacts unconsented | A | CRITICAL — legal risk |
| Lifecycle stage accuracy | C | 31% in wrong stage | B | High |
| Campaign membership | D | 41% of influenced deals have 0 campaign members | B | High |
| Account matching | C | 23% of contacts not matched to account | B | Medium |

**Overall Database Health Score: 47/100 (F — Revenue Operations at Risk)**

**Top Revenue-Impact Issue:** 45% of contacts from paid LinkedIn campaigns have no UTM data flowing into HubSpot (Webflow form missing hidden fields). This means LinkedIn is getting zero attribution credit for an estimated $280K in influenced pipeline over the past 6 months. Fix time: 4 hours. Owner: MOps.

**Sample Lead Source Normalization:**
Current state: 47 distinct lead source values in HubSpot including "Linkedin", "linkedin", "LinkedIn Ads", "LI", "linkedin ads", "LINKEDIN", "paid-linkedin"
Normalized to: Lead Source = "Paid Social" | Lead Source Detail = "LinkedIn Ads" | Channel = "Paid"
Backfill workflow: HubSpot workflow triggers on all 47 variants → normalizes → re-runs attribution aggregation

**Projected outcome after 90-day remediation:**
- Marketing-attributed pipeline: 34% → projected 52% of closed-won (recovering $1.4M ARR in "invisible" marketing-influenced pipeline)
- Database cost reduction: 14,200 zombie suppressed contacts → potential $18,400/year HubSpot tier savings
- Compliance risk: 22,000 EU contacts re-permissioned or suppressed → GDPR violation risk eliminated

## Success Metrics

**Data Quality KPIs to track monthly:**
- Lead source attribution rate: % of all net-new contacts with known lead source (target: >90%)
- UTM capture rate: % of form submissions with complete UTM data (target: >95%)
- Duplicate rate: % estimated duplicate records in database (target: <2%)
- Email deliverability rate: % of sends resulting in delivery (target: >98%)
- Contact completeness score: % of contacts with all required fields populated (target: >85%)
- CRM sync error rate: # of HubSpot–Salesforce sync failures per week (target: <5)
- Consent coverage: % of EU/UK contacts with documented consent (target: 100%)
- Lifecycle stage accuracy: % of contacts in correct stage per scoring rules (target: >95%)

**Business Impact KPIs:**
- Marketing-attributed pipeline % (should increase 10–25pp after cleanup)
- SDR bounce rate on outreach sequences (should decrease 40–60% after list hygiene)
- MAP licensing cost vs. active marketable contacts (should decrease 10–30%)

## Related Prompts

- [Multi-Touch Attribution & Revenue Marketing Intelligence Engine](../Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md)
- [Lead Scoring Model Optimization & Predictive Buying Signal Intelligence Engine](../Lead-Quality-&-Conversion-Analytics/Lead-Scoring-Model-Optimization-&-Predictive-Buying-Signal-Intelligence-Engine.md)
- [Marketing Funnel Conversion & Pipeline Velocity Intelligence Engine](../Funnel-Conversion-&-Pipeline-Velocity/Marketing-Funnel-Conversion-&-Pipeline-Velocity-Intelligence-Engine.md)
- [MarTech Stack Rationalization & AI Readiness Intelligence Engine](../../01_CMO-&-Leadership/Strategy-&-Planning/MarTech-Stack-Rationalization-&-AI-Readiness-Intelligence-Engine.md)

## Integration Tips

**HubSpot:**
- Use HubSpot's native Duplicate Management tool (Contacts → Actions → Manage Duplicates) for initial pass; supplement with Dedupely for high-volume or complex matching
- Build all remediation workflows in HubSpot Workflows with enrollment triggers on specific property conditions — avoid one-off manual fixes that can't be audited
- Use HubSpot's contact property history to preserve original lead source values before overwriting during normalization
- Create a "Data Quality" contact list that auto-enrolls records failing quality thresholds — your MOps team's daily work queue

**Salesforce:**
- Use Salesforce Duplicate Rules + Matching Rules for real-time prevention; DemandTools or Cloudingo for bulk historical cleanup
- Map all UTM properties as Salesforce Lead/Contact fields with a custom field set — expose these in the Lead and Contact page layouts for SDR visibility
- Use Salesforce Flow (not Process Builder) for automated lifecycle stage corrections — more reliable and easier to audit

**Zapier / Make:**
- Build a Zap/scenario that monitors your HubSpot–Salesforce sync error log webhook and posts to a dedicated Slack channel (#mops-alerts) with record ID and error type
- Use Make to build a weekly data quality report that queries HubSpot/SFDC via API and posts a dashboard snapshot to Slack or Notion

**Google Sheets / Notion:**
- Maintain your UTM Builder as a shared Google Sheet with dropdown validation for each UTM parameter — prevents typos, enforces taxonomy, auto-generates the full UTM URL
- Host your Data Governance SOP in Notion with a page per channel/source, including the UTM templates, form field mapping specs, and CRM field definitions

**BigQuery / Snowflake:**
- If you have a data warehouse, build a daily data quality monitoring table that scores every contact on all dimensions and surfaces degradation trends — much faster than native CRM reporting
- Connect to Looker/Tableau/Mode for executive-level data quality dashboards that CMO and RevOps leadership can access without CRM access

## Troubleshooting

**Problem: UTM normalization workflow keeps overwriting good data with blank values**
Fix: Always use "is known" as a condition before writing UTM properties in workflows. Structure: IF utm_source is known AND Lead Source is unknown → set Lead Source from UTM. Never run a blanket "set Lead Source" workflow without property-known guards.

**Problem: After deduplication, pipeline attribution history disappeared on merged records**
Fix: Before any merge, export a CSV of all campaign membership records for the contacts being merged. Most dedup tools preserve the winning record's campaign history but lose the loser record's history. Manually re-create campaign membership in the surviving record for all deals with pipeline value. For HubSpot, use the Associations API to re-link deal records before merging contacts.

**Problem: HubSpot–Salesforce sync errors keep recurring after fixing**
Fix: Sync errors are almost always caused by a field in Salesforce that has validation rules, required picklist values, or record type restrictions that HubSpot doesn't know about. Export the HubSpot sync error log → group by error type → map each error type to the specific Salesforce field causing it → either (a) relax the Salesforce validation rule, (b) add a HubSpot workflow that pre-populates the required Salesforce field value before sync triggers, or (c) remove the field from the sync mapping if not needed.

## Version History
- v1.0: Initial creation (auto-generated)
