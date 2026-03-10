# Revenue Operations Data Quality & CRM Hygiene Intelligence Engine - AI-Powered CRM Audit, Deduplication & Data Governance Automation

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** revops, crm, data-quality, hubspot, salesforce, martech, data-governance, lead-intelligence, marketing-ops, b2b

## Overview
Deploys an AI agent to audit your CRM and marketing automation platform for data quality issues, generate deduplication logic, design enrichment workflows, and produce a prioritized data hygiene roadmap — turning dirty data from a revenue drain into a clean, trusted system that sales and marketing actually rely on. Use this when pipeline accuracy is questioned, conversion rates are declining for no clear reason, or when your CRM data is known to be unreliable.

## Quick Copy-Paste Version

You are a senior Revenue Operations architect specializing in CRM data quality and marketing database hygiene. Conduct a comprehensive data quality audit and create a remediation plan.

MY CRM/MAP SETUP:
- CRM: [Salesforce / HubSpot CRM / Microsoft Dynamics / other]
- Marketing Automation: [HubSpot Marketing / Marketo / Pardot / ActiveCampaign / other]
- Total contact records: [X]
- Total account/company records: [X]
- Data sources feeding the CRM: [web forms, paid ads, SDR manual entry, enrichment tools, events, CSV imports, API integrations]
- Last data quality audit: [never / X months ago]
- Known data issues: [duplicates, missing fields, outdated contacts, unsubscribes, wrong lifecycle stages, etc.]

Run a complete data quality intelligence analysis covering:

**1. DATA QUALITY SCORECARD**
Score each dimension 1-10 with specific benchmarks:
- Completeness: % of records with required fields populated (Name, Email, Company, Title, Phone, Country)
- Accuracy: % of records with valid, non-generic email domains and real company names
- Freshness: % of records touched/validated within last 12 months
- Uniqueness: estimated duplicate rate and root cause
- Consistency: field format standardization (phone formats, country codes, job title normalization)
- Compliance: GDPR/CCPA consent status, opt-out accuracy

**2. DUPLICATE DETECTION & MERGE LOGIC**
Design deduplication rules:
- Match criteria hierarchy (email exact → email fuzzy → name + company → phone)
- Survivor record logic (which record wins on field-by-field conflicts)
- Automated merge workflow vs. human review queue thresholds
- Ongoing duplicate prevention at point-of-entry (form validation, API dedup checks)

**3. FIELD COMPLETION & ENRICHMENT STRATEGY**
Map critical missing fields to enrichment sources:
- Which fields to auto-enrich via Clearbit/Apollo/ZoomInfo/Clay vs. ask via progressive profiling
- Enrichment waterfall logic (source priority, confidence scoring, overwrite rules)
- Fields that should NEVER be overwritten by enrichment tools

**4. LIFECYCLE STAGE AUDIT & CORRECTION**
Identify misclassified records:
- Contacts stuck in wrong lifecycle stage (e.g., "Lead" with closed-won deal)
- Orphaned contacts with no associated company
- Dead accounts with 100% churned contacts still marked active
- Stage progression logic gaps causing contacts to skip stages

**5. SEGMENTATION RELIABILITY ASSESSMENT**
Which segments are currently untrustworthy due to data gaps:
- ICP fit scoring accuracy
- Geographic segmentation reliability
- Industry/vertical classification quality
- Persona assignment confidence

**6. DATA DECAY PREVENTION SYSTEM**
Design ongoing hygiene automation:
- Scheduled verification jobs (email validation, company data refresh)
- Trigger-based hygiene (when a deal closes, when a contact emails bounce, when a company is acquired)
- Re-engagement + data update campaigns for stale contacts
- SDR/AE data entry standards enforcement

**7. PRIORITIZED REMEDIATION ROADMAP**
30/60/90-day data cleanup plan:
- Quick wins (high impact, low effort) in first 30 days
- Enrichment campaigns and automation setup in 60 days
- Governance policy rollout and training in 90 days
- Estimated pipeline impact of clean data (use: 1% improvement in contact-to-MQL conversion = $X pipeline)

Output as a structured RevOps Data Quality Report with executive summary, scored dimensions, SQL/workflow pseudocode for key automation, and a Jira-ready remediation backlog.

## Advanced Customizable Version

ROLE: You are a Principal RevOps Data Architect with deep expertise in Salesforce, HubSpot, Marketo, and the modern data enrichment ecosystem (Clay, Clearbit, Apollo, ZoomInfo, Cognism). You have led data quality transformations at 20+ B2B SaaS companies ranging from $10M to $500M ARR. You understand that bad data is a revenue problem, not just an IT problem.

CONTEXT:
Company: [Company Name]
Industry: [e.g., Cybersecurity SaaS, FinTech, Healthcare IT]
GTM Motion: [Sales-led / Product-led / Hybrid]
ARR: [$X]
ACV: [$X]
Sales team size: [X AEs + X SDRs]
Marketing team size: [X]
CRM: [Salesforce / HubSpot / other] — version/edition: [e.g., Salesforce Enterprise]
Marketing Automation Platform: [HubSpot / Marketo / Pardot / other]
Enrichment tools currently in use: [Clearbit / ZoomInfo / Apollo / Clay / none / other]
Email validation tools: [NeverBounce / ZeroBounce / BriteVerify / none]
Data volume:
  - Contacts: [X total, X active in last 90 days]
  - Accounts/Companies: [X total]
  - Leads (Salesforce): [X open leads, X converted]
  - Deals/Opportunities: [X open, X closed-won last 12mo]

PRIMARY DATA PAIN POINTS (rank order your top 5):
1. [e.g., Estimated 30%+ duplicate contact rate destroying email metrics]
2. [e.g., 60% of contacts missing job title — persona scoring is unreliable]
3. [e.g., Lifecycle stages are manually updated and often wrong]
4. [e.g., GDPR consent records are incomplete — legal risk]
5. [e.g., CRM accounts not linked to correct parent company hierarchy]

BUSINESS IMPACT TO QUANTIFY:
- Current contact-to-MQL conversion rate: [X%]
- Email deliverability rate: [X%]
- Bounce rate: [X%]
- Duplicate records estimate: [X% or "unknown"]
- Sales reps complaining about data quality: [yes/no, frequency]

COMPLIANCE REQUIREMENTS:
- GDPR applicable: [yes/no]
- CCPA applicable: [yes/no]
- HIPAA applicable: [yes/no]
- Current consent management tool: [OneTrust / Cookiebot / none / other]

OBJECTIVE: Produce a board-ready RevOps Data Quality Intelligence Report and fully actionable remediation system.

---

DELIVERABLE 1: EXECUTIVE DATA QUALITY SCORECARD

Score each dimension 0-100 with benchmark comparisons (top-quartile B2B SaaS):

| Dimension | Your Score | Top-Quartile Benchmark | Gap | Revenue Impact |
|-----------|-----------|----------------------|-----|----------------|
| Email Deliverability | [X] | 97%+ valid emails | [X] | [$X pipeline at risk] |
| Record Completeness | [X] | 85%+ required fields | [X] | [$X scoring inaccuracy] |
| Deduplication Rate | [X] | <3% duplicate rate | [X] | [$X double-spend] |
| Data Freshness | [X] | 70%+ updated <12mo | [X] | [$X wasted outreach] |
| Lifecycle Accuracy | [X] | <5% misclassified | [X] | [$X pipeline blind spots] |
| Consent Compliance | [X] | 100% consent records | [X] | [$X legal exposure] |

Overall Data Quality Score: [X/100]
Estimated Annual Revenue Impact of Current Data Quality: [$X]

---

DELIVERABLE 2: DEDUPLICATION INTELLIGENCE SYSTEM

**Duplicate Detection Algorithm:**

Tier 1 — Automatic Merge (confidence >95%):
- Exact email address match across Contact and Lead objects
- Same email domain + first/last name match within same account
→ Action: Auto-merge, keep most recently modified record as survivor

Tier 2 — High-Confidence Merge Queue (confidence 80-95%):
- Email domain + company name match + similar name (Levenshtein distance <2)
- Phone number exact match + same company
→ Action: Route to RevOps queue for 24-hour review, auto-merge if no action

Tier 3 — Manual Review Required (confidence 50-80%):
- Same first name + same company + different email
- Company name fuzzy match (e.g., "Acme Corp" vs "Acme Corporation")
→ Action: Flag for sales rep confirmation, include in weekly data review meeting

**Survivor Record Logic (field-by-field):**
- Email: Most recently validated (prioritize corporate over personal)
- Phone: Most recently added with valid format
- Title/Role: Most recently enriched from premium source
- Company: Link to existing Account record over raw text
- Lead Source: Preserve oldest (first-touch attribution)
- Lifecycle Stage: Take the more advanced stage
- GDPR Consent: Take the most restrictive consent status

**Ongoing Deduplication Prevention:**
// Form submission dedup check (pseudocode for HubSpot workflow or Salesforce trigger):
ON new_record_created:
  query existing_contacts WHERE email = new_email
  IF match_found:
    merge new_record into existing_record
    log merge event with timestamp and source
  ELSE:
    check company_domain against existing_accounts
    IF account_match:
      associate contact to existing account
    CREATE new_contact record
    ENRICH via Clay/Clearbit waterfall

---

DELIVERABLE 3: FIELD ENRICHMENT WATERFALL ARCHITECTURE

**Critical Fields Enrichment Priority Matrix:**

Tier 1 — Revenue-Critical (enrich immediately, auto-overwrite if blank):
- Job Title → Apollo > ZoomInfo > Clay AI research
- Company Size (employees) → Clearbit > Crunchbase API > Clay
- Industry/Vertical → SIC code lookup > Clearbit > manual
- LinkedIn URL → Apollo > manual

Tier 2 — Segmentation-Important (enrich within 48 hours, don't overwrite manual entries):
- Department → derive from title using keyword logic
- Seniority Level → derive from title (C-suite, VP, Director, Manager, IC)
- Funding Stage → Crunchbase > Dealroom > Clay
- Tech Stack → BuiltWith > Clay research

Tier 3 — Nice-to-Have (enrich in batch monthly):
- Social media profiles
- Company news/signals
- Personal interests (for ABM personalization)

**Fields to NEVER auto-overwrite:**
- Opt-out / Unsubscribe status
- GDPR consent records
- Deal-linked company name (sales relationship data)
- Custom fields set by sales reps (tagged with "do-not-overwrite" property)

**Progressive Profiling Triggers** (collect via forms, chatbot, or email):
- Gate high-value content behind 1-2 missing fields
- Use smart fields that only show if the value is unknown
- Prioritize: Phone → Budget → Timeline → Evaluating Competitors

---

DELIVERABLE 4: LIFECYCLE STAGE CORRECTION AUTOMATION

**Misclassification Detection Queries:**

Query 1 — Ghost Leads (Salesforce SOQL):
SELECT Id, Name, Email, Status, CreatedDate, LastActivityDate
FROM Lead
WHERE IsConverted = false
  AND LastActivityDate < LAST_N_DAYS:365
  AND Status NOT IN ('Disqualified', 'Dead')
ORDER BY LastActivityDate ASC
Action: Batch-update Status to 'Stale' → trigger re-engagement or disqualification workflow

Query 2 — Stage-Skippers (contacts who jumped from Subscriber to Opportunity):
SELECT c.Id, c.Email, c.Lifecycle_Stage__c, o.Id AS Opportunity_Id
FROM Contact c
JOIN OpportunityContactRole ocr ON c.Id = ocr.ContactId
JOIN Opportunity o ON ocr.OpportunityId = o.Id
WHERE c.Lifecycle_Stage__c = 'Subscriber'
  AND o.StageName NOT IN ('Closed Lost')
Action: Correct lifecycle to 'SQL' or 'Opportunity', log correction with timestamp

Query 3 — Orphaned Contacts (no associated account):
SELECT Id, Name, Email, Title, Company
FROM Contact
WHERE AccountId = null
  AND IsDeleted = false
Action: Run company name → account fuzzy match → associate or flag for SDR

---

DELIVERABLE 5: COMPLIANCE & CONSENT AUDIT

GDPR Risk Assessment:
- Records with no consent source documented: [X] → HIGH RISK
- Records with consent older than 3 years: [X] → MEDIUM RISK
- Records from EU/UK with no explicit opt-in: [X] → CRITICAL RISK

Remediation Actions:
1. Suppress all EU/UK contacts with no documented consent source from all marketing sends immediately
2. Run a re-permission campaign for contacts with consent >18 months old
3. Implement consent timestamp + source capture on all new form submissions
4. Configure your MAP to automatically suppress contacts who haven't engaged in 24 months unless re-permissioned

---

DELIVERABLE 6: AUTOMATED DATA HYGIENE SYSTEM DESIGN

**Daily Automated Jobs:**
- Email bounce processing: Hard bounces → mark invalid, suppress, trigger enrichment for replacement email
- Unsubscribe sync: Ensure opt-outs propagate from MAP → CRM within 15 minutes
- Duplicate check on new records: Run dedup algorithm within 1 hour of creation

**Weekly Automated Jobs:**
- Stale contact detection: Flag contacts with no activity + no email open in 90 days
- Lifecycle stage drift correction: Run queries 1-3 above, auto-correct high-confidence mismatches
- Enrichment refresh: Re-enrich Tier 1 fields for contacts added >6 months ago with blank values

**Monthly Automated Jobs:**
- Full database email validation via NeverBounce/ZeroBounce API (scan entire database)
- Company data refresh: Update employee count, funding stage, tech stack changes
- Data quality score recalculation and trending report to RevOps

**Trigger-Based Hygiene:**
- Contact email bounces → mark invalid, attempt enrichment for new email, notify SDR owner
- Deal closes → update all associated contacts to 'Customer' lifecycle
- Deal marked Closed-Lost → update contacts with loss reason, add to re-engagement suppression list
- Company acquired (via news alert) → flag accounts for manual review, update parent company

---

DELIVERABLE 7: 90-DAY DATA QUALITY TRANSFORMATION ROADMAP

**Days 1-30: Stop the Bleeding**
- [ ] Export and validate email list via NeverBounce — suppress all invalid/risky emails
- [ ] Run Tier 1 deduplication merge on exact email matches
- [ ] Identify and suppress EU/UK contacts without consent documentation
- [ ] Implement duplicate prevention on top 3 highest-volume form submissions
- [ ] Create data quality dashboard in CRM (5 key metrics, updated daily)
Estimated pipeline protection: [$X from improved deliverability]

**Days 31-60: Fix the Foundation**
- [ ] Configure enrichment waterfall for Tier 1 fields via Clay/Apollo/ZoomInfo
- [ ] Run lifecycle stage correction queries and auto-correct high-confidence records
- [ ] Set up progressive profiling on gated content (target: 15% field completion improvement)
- [ ] Deploy daily/weekly automated hygiene workflows
- [ ] Complete Tier 2 deduplication — review queue and merge
Estimated impact: [$X from improved lead scoring accuracy]

**Days 61-90: Scale and Govern**
- [ ] Launch data entry standards training for all SDRs and AEs
- [ ] Implement field validation rules in CRM (required fields, format enforcement)
- [ ] Set up monthly data quality review meeting cadence
- [ ] Create RevOps Data Quality SLA (response time for data issues, escalation path)
- [ ] Document all enrichment sources, overwrite rules, and consent management in runbook
Estimated impact: [X% improvement in contact-to-MQL conversion]

---

OUTPUT FORMAT:
Produce this as a structured RevOps Intelligence Report with:
1. Executive Summary (3 bullets: current state, cost of inaction, projected ROI of clean data)
2. Full scored Data Quality Scorecard with revenue impact calculations
3. System architecture diagrams (described in text) for dedup, enrichment, and hygiene workflows
4. Jira/Linear-ready remediation backlog (Epic → Story → Task format)
5. 30/60/90-day roadmap with owner, effort estimate, and success metric for each initiative
6. Data Governance Policy template (1 page) for sales and marketing to sign off on

## Example Input/Output

**Input Example:**
Company: Veloxa Security (B2B cybersecurity SaaS, $18M ARR, 45-person company)
CRM: Salesforce Enterprise
MAP: Marketo
Contacts: 42,000 total, ~8,000 active in last 90 days
Known issues: High duplicate rate from 3 trade show CSV imports in Q4, 55% of contacts missing job title, lifecycle stages manually updated and often wrong, no formal GDPR consent tracking

**Output Example (excerpt):**

**EXECUTIVE DATA QUALITY SCORECARD — Veloxa Security**

| Dimension | Score | Benchmark | Gap | Revenue Impact |
|-----------|-------|-----------|-----|----------------|
| Email Deliverability | 71/100 | 97%+ | -26pts | $340K pipeline at risk (estimated 12% soft bounce rate destroying sender reputation) |
| Record Completeness | 44/100 | 85%+ | -41pts | $210K/yr in wasted outreach to incorrectly segmented contacts |
| Deduplication | 52/100 | <3% dupe rate | ~18% est. dupe rate | $125K in double-spend on ads, inflated email costs |
| Data Freshness | 61/100 | 70%+ <12mo | -9pts | $89K in outreach to stale/churned contacts |
| Lifecycle Accuracy | 38/100 | <5% misclass | est. 34% wrong stage | $420K in pipeline misattribution, broken nurture routing |
| Consent Compliance | 29/100 | 100% | Missing EU consent for ~3,200 contacts | Potential €48K GDPR fine exposure |

**Overall Score: 49/100**
**Estimated Annual Revenue Drag: $1.18M**

**Top 3 Immediate Actions:**
1. Suppress 3,200 EU contacts with no consent documentation before next email send (legal risk)
2. Run email validation scan — estimated 4,200 invalid emails draining sender reputation
3. Execute Tier 1 dedup merge: Apollo analysis suggests 7,400+ duplicate contacts from Q4 event imports

**DEDUPLICATION BATTLE PLAN — Trade Show Import Crisis:**
- Exact email match across all Lead and Contact objects: found 4,840 likely duplicates
- Name + Company match (Levenshtein <2): additional 2,600 high-confidence dupes
- Merge strategy: Keep Salesforce Contact over Lead, preserve original Lead Source for attribution
- Survivor field rules: Title from most recent enrichment, Email from most recent valid entry
- Timeline: Auto-merge Tier 1 (4,840 records) in 48 hours; Tier 2 queue for RevOps review week 2

**ENRICHMENT WATERFALL — Job Title Recovery:**
- 55% missing job title = 23,100 contacts ungradeable for persona scoring
- Clay AI enrichment (LinkedIn scrape + company website): estimated 78% fill rate at $0.04/record = $740 to enrich entire database
- Remaining 22% → progressive profiling gate on next gated content download
- Post-enrichment: Persona scoring accuracy expected to improve from 43% → 81% confidence

## Success Metrics

- **Email Deliverability:** Bounce rate drops below 2%, spam complaint rate below 0.1%
- **Deduplication:** Duplicate rate reduced to <5% within 60 days, <3% at 90 days
- **Field Completeness:** Required fields (Email, Name, Title, Company) at 90%+ within 90 days
- **Lifecycle Accuracy:** <5% of contacts in wrong lifecycle stage after correction campaign
- **Enrichment Coverage:** 80%+ of ICP contacts have all Tier 1 fields populated
- **Compliance:** 100% of EU/UK contacts have documented consent source within 30 days
- **Business Impact:** Measurable improvement in MQL-to-SQL conversion rate (track pre/post)
- **Sales Trust:** Survey sales team on CRM data trust score before and after (target: +30 points)

## Related Prompts

- [`CRM-Revenue-Operations-Intelligence-Engine.md`](./CRM-Revenue-Operations-Intelligence-Engine.md) — Full CRM operations strategy and pipeline intelligence
- [`Marketing-Data-Enrichment-&-Lead-Intelligence-Engine.md`](./Marketing-Data-Enrichment-&-Lead-Intelligence-Engine.md) — Lead enrichment strategy and vendor evaluation
- [`UTM-Campaign-Tracking-Governance-Engine.md`](./UTM-Campaign-Tracking-Governance-Engine.md) — UTM governance to prevent attribution data corruption
- [`Marketing-Technology-Stack-Audit-Engine.md`](./Marketing-Technology-Stack-Audit-Engine.md) — Full MarTech audit including data flow architecture

## Integration Tips

- **Salesforce:** Use Data Loader for bulk deduplication merges; implement Duplicate Rules and Matching Rules in Setup to prevent future duplicates at point-of-entry; use Flow Builder for lifecycle stage auto-correction triggers
- **HubSpot:** Enable "Prevent duplicate contacts" in settings; use Lists for segmenting data quality cohorts; use Workflows for auto-enrichment and lifecycle stage correction; use the Data Quality Command Center (Operations Hub) for ongoing monitoring
- **Clay:** Build a Clay Table for enrichment waterfall — connect Apollo, Clearbit, LinkedIn, and Claude AI as enrichment sources; set confidence thresholds and conditional overwrite rules
- **Marketo:** Use Smart Campaigns with "Data Value Changes" triggers for hygiene automation; Engagement Programs for re-permissioning campaigns; Program tags for consent source tracking
- **Salesforce + Marketo:** Sync duplicate contacts to a "Quarantine" campaign in Marketo before merging in Salesforce to prevent sync errors from breaking marketing program memberships
- **ZoomInfo / Apollo:** Set up auto-export of enriched data to Google Sheets as an intermediate layer before pushing to CRM — allows QA before overwriting live records
- **NeverBounce API:** Connect to your HubSpot or Marketo via Zapier/Make to run real-time validation on every new form submission — block risky emails at the gate

## Troubleshooting

**Problem: Merging duplicates in Salesforce breaks associated Opportunities and Cases**
Solution: Before running bulk merges, export all OpportunityContactRole and CaseContactRole records. Set Salesforce merge to retain the master record's related lists. Run merges in batches of 200 and validate related objects after each batch before proceeding.

**Problem: Enrichment tool overwrites carefully researched manual data (e.g., custom persona tags)**
Solution: Create a "Do Not Enrich" checkbox field on Contact/Account. Train SDRs to check this for any custom fields. Configure your enrichment workflow to skip all fields where Do_Not_Enrich__c = TRUE. Alternatively, use Clay's conditional overwrite logic to only populate blank fields.

**Problem: Re-permissioning email campaign results in mass opt-outs, shrinking your database**
Solution: This is expected and healthy — a smaller, engaged list outperforms a large, cold one. Mitigate by: (1) warming up re-permission sends over 4 weeks with progressively more direct asks, (2) using SMS or in-app messaging for contacts who haven't opened email in 12+ months, (3) treating unsubscribes as a suppression cost, not a loss — they were never going to convert anyway.

## Version History
- v1.0: Initial creation (auto-generated)
