# Email Deliverability & Sender Reputation Optimization Intelligence Engine — Full-Stack Inbox Placement & List Health Automation

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** email deliverability, sender reputation, inbox placement, list hygiene, email authentication, B2B SaaS, demand generation

## Overview
Diagnoses your complete email deliverability ecosystem — authentication infrastructure, sender reputation scores, list hygiene signals, engagement patterns, and ISP-level blocking indicators — then generates a prioritized remediation roadmap and ongoing monitoring protocol. Use this when open rates are declining, emails are landing in spam, or before launching a high-volume campaign to a cold or semi-engaged list.

## Quick Copy-Paste Version

You are an email deliverability expert. Analyze the following email program data and produce a complete deliverability diagnostic and remediation plan.

EMAIL PROGRAM DATA:
- ESP: [Mailchimp/HubSpot/Klaviyo/Marketo/other]
- Monthly send volume: [number]
- List size: [number], acquisition source: [organic/purchased/mixed]
- List age: [months since last full hygiene scrub]
- Current metrics: Open rate [%], Click rate [%], Bounce rate [%], Spam complaint rate [%], Unsubscribe rate [%]
- Authentication setup: SPF [yes/no], DKIM [yes/no], DMARC [yes/no/partial]
- Primary sending domain: [domain.com]
- Dedicated IP or shared IP pool: [dedicated/shared]
- Recent issues: [spam folder placement/low open rates/bounce spikes/ISP blocks/none]
- Last deliverability audit: [date or never]

Produce:

1. DELIVERABILITY HEALTH SCORE (0-100) with breakdown across:
   - Authentication & technical infrastructure (25 pts)
   - List quality & hygiene (25 pts)
   - Engagement signals & sender reputation (25 pts)
   - Content & sending patterns (25 pts)

2. CRITICAL ISSUES (P0 — fix within 48 hours)
   For each issue: what it is, why it's causing damage, exact fix with commands/settings

3. HIGH-PRIORITY REMEDIATION (P1 — fix within 2 weeks)
   Ranked by revenue impact, with specific implementation steps

4. LIST HYGIENE PROTOCOL
   - Segments to suppress immediately (hard bounces, spam complainers, 12-month unengaged)
   - Re-engagement campaign design for 6-12 month inactive subscribers
   - Ongoing hygiene automation rules (trigger-based suppression logic)

5. SENDER REPUTATION REBUILDING PLAN
   If reputation is damaged: 30-day IP warming / reputation recovery schedule with daily/weekly send volumes and engagement thresholds to hit before escalating

6. AUTHENTICATION HARDENING
   Exact DNS records needed for SPF, DKIM, DMARC with recommended DMARC policy progression (none → quarantine → reject timeline)

7. ONGOING MONITORING DASHBOARD
   10 KPIs to track weekly, with alert thresholds and automated response playbooks

8. PROJECTED IMPACT
   Expected open rate improvement, inbox placement rate, and estimated revenue impact from fixing each issue category

## Advanced Customizable Version

ROLE: You are a Principal Email Deliverability Architect with 12+ years of experience managing high-volume email programs for B2B SaaS companies. You have deep expertise in ISP feedback loops, SMTP protocols, domain reputation management, and inbox placement optimization across Gmail, Outlook/Microsoft 365, Yahoo, and corporate mail servers. You understand the intersection of technical deliverability and marketing performance.

CONTEXT:
Company: [Company Name]
Industry: [B2B SaaS / E-commerce / B2C / Media / Other]
Revenue model: [ARR-based / transactional / subscription]
ESP/MAP: [HubSpot / Marketo / Salesforce Marketing Cloud / Klaviyo / Sendgrid / Other]
CRM: [Salesforce / HubSpot / Other]

CURRENT EMAIL PROGRAM STATE:

Technical Infrastructure:
- Primary sending domain: [domain.com] — dedicated or shared: [type]
- Subdomain strategy: [marketing.domain.com / em.domain.com / none]
- SPF record: [paste current record or "not configured"]
- DKIM: [configured for which selectors / not configured]
- DMARC: [paste current policy or "not configured"]
- BIMI: [configured / not configured]
- Dedicated IP(s): [yes/no — if yes, how many and age]
- IP warming history: [completed / partial / never done]
- Bounce handling: [automatic suppression / manual / unknown]
- Feedback loop registrations: [ISPs registered / none / unknown]

List Composition & Health:
- Total contact database: [number]
- Marketable/opted-in contacts: [number]
- List growth sources: [% organic, % content/gated, % events, % purchased, % scraping]
- Average list age: [months since signup for median contact]
- Last list hygiene / validation run: [date]
- NeverBounce / ZeroBounce / BriteVerify: [used / not used]
- Role-based address volume: [known % or "unknown"]
- Spam trap exposure: [known / suspected / unknown]

Sending Patterns:
- Weekly send frequency per contact: [average]
- Batch send vs. triggered send split: [%/%]
- Peak daily volume: [number]
- Send time strategy: [fixed schedule / send-time optimization / random]
- Content mix: [% promotional, % nurture, % transactional, % newsletters]

Current Performance Metrics (last 90 days):
- Average open rate: [%] — tracking method: [pixel / click-inferred / mixed]
- Average click-to-open rate (CTOR): [%]
- Hard bounce rate: [%]
- Soft bounce rate: [%]
- Spam complaint rate: [per 1,000 emails or %]
- Unsubscribe rate: [%]
- List growth rate vs. churn rate: [+/-%]

Inbox Placement Intelligence (if available):
- Gmail inbox placement: [%]
- Outlook/M365 inbox placement: [%]
- Yahoo inbox placement: [%]
- Corporate domains inbox placement: [%]
- Tools used: [Litmus / Email on Acid / GlockApps / 250ok / Postmaster Tools / none]

Known Issues:
- [List any specific issues: ISP blocks, sudden open rate drops, spam folder complaints from prospects, Postmaster Tools warnings, etc.]
- [Revenue impact of current deliverability problems if quantifiable]

OBJECTIVE: Produce an exhaustive deliverability audit and remediation intelligence report that a marketing operations engineer and CMO can act on immediately. Every recommendation must have a specific implementation method, owner, timeline, and success metric.

CONSTRAINTS:
- Do not recommend purchased list strategies or tactics that violate CAN-SPAM, GDPR, or CASL
- Prioritize fixes by revenue impact and time-to-resolution
- All technical recommendations must include exact configurations, not vague guidance
- Assume the team has access to DNS management, ESP admin access, and Google Postmaster Tools
- Design for full automation — every ongoing process should be automatable via ESP rules, Zapier, or API

OUTPUT STRUCTURE:

═══════════════════════════════════════════
SECTION 1: DELIVERABILITY HEALTH SCORECARD
═══════════════════════════════════════════

Overall Score: [X/100] — [Grade: A/B/C/D/F] — [Status: Healthy/At Risk/Damaged/Critical]

Subscore Breakdown:
┌─────────────────────────────────────────┬───────┬──────────┐
│ Category                                │ Score │ Max      │
├─────────────────────────────────────────┼───────┼──────────┤
│ Authentication & Technical Infrastructure│  /25  │   25     │
│ List Quality & Hygiene                  │  /25  │   25     │
│ Engagement Signals & Sender Reputation  │  /25  │   25     │
│ Content & Sending Patterns              │  /25  │   25     │
└─────────────────────────────────────────┴───────┴──────────┘

Benchmark Comparison:
- Your open rate [X%] vs. industry benchmark [Y%]: [above/below/at parity]
- Your complaint rate [X%] vs. Gmail threshold [0.10%]: [safe/at risk/exceeds threshold]
- Your bounce rate [X%] vs. acceptable ceiling [2%]: [status]

═══════════════════════════════════════════
SECTION 2: CRITICAL ISSUES — P0 REMEDIATION (48-HOUR SLA)
═══════════════════════════════════════════

For each P0 issue:
ISSUE: [Name]
Severity: CRITICAL | Impact: [Revenue / Reputation / Compliance]
Root Cause: [Technical explanation]
Business Impact: [What is happening to revenue/pipeline as a result]
Exact Fix:
  Step 1: [Specific action with exact settings/commands]
  Step 2: [...]
  Verification: [How to confirm the fix worked]
Expected Result: [What metric should improve and by how much]

═══════════════════════════════════════════
SECTION 3: HIGH-PRIORITY REMEDIATION — P1 (2-WEEK SPRINT)
═══════════════════════════════════════════

Ranked by revenue impact:
1. [Issue] → Fix → Owner → Timeline → Success Metric
2. [Issue] → Fix → Owner → Timeline → Success Metric
[Continue for all P1 issues]

Sprint Kickoff Checklist:
□ [Day 1 tasks]
□ [Day 3 tasks]
□ [Day 7 tasks]
□ [Day 14 validation]

═══════════════════════════════════════════
SECTION 4: LIST HYGIENE INTELLIGENCE ENGINE
═══════════════════════════════════════════

Immediate Suppression Segments (automate via ESP):
Rule 1: [Segment definition + suppression trigger + implementation path]
Rule 2: Hard bounces → Suppress after [1] hard bounce, auto-tag "invalid_email"
Rule 3: Spam complainants → Suppress + flag for CRM "do_not_email" within 15 minutes via webhook
Rule 4: 12-month unengaged → Move to "sunset" segment before suppression
Rule 5: Role-based addresses (info@, admin@, sales@) → Downgrade send frequency, suppress from cold sends

Re-Engagement Campaign Design:
Audience: [12-month non-openers/non-clickers]
Sequence:
  Email 1 (Day 0): [Subject line psychology — curiosity/urgency] + single CTA
  Email 2 (Day 5): [Different hook — value reminder] + preference center link
  Email 3 (Day 10): [Break-up email structure] + final unsubscribe option
Success Threshold: [X%] engagement to reinstate to active list
Sunset Protocol: [% of segment expected to suppress, timeline, list size impact]

Ongoing Hygiene Automation:
- New contact validation: [NeverBounce API on form submission or ESP-native validation]
- Monthly hygiene jobs: [Automated segment review, bounce analysis, complaint monitoring]
- Quarterly deep scrub: [Full list validation service, spam trap screening process]

═══════════════════════════════════════════
SECTION 5: AUTHENTICATION HARDENING PROTOCOL
═══════════════════════════════════════════

Current State Assessment:
SPF: [Analysis of current record — too many lookups? missing includes? ~all vs -all?]
DKIM: [Key length, rotation schedule, selector analysis]
DMARC: [Current policy, alignment mode, reporting setup]

Recommended Configurations:

SPF Record (final):
v=spf1 [exact record to implement]

DKIM Configuration:
Selector: [selector name]
Key Length: 2048-bit minimum
Rotation: Every [90/180] days
Implementation: [ESP-specific DKIM setup instructions]

DMARC Policy Progression:
Phase 1 (Week 1-4): v=DMARC1; p=none; rua=mailto:[dmarc-reports@domain.com]; ruf=mailto:[dmarc-failures@domain.com]; pct=100
Phase 2 (Week 5-8): p=quarantine; pct=25 → escalate to pct=100 if <0.1% failure rate
Phase 3 (Week 9+): p=reject; pct=100
BIMI Record (after p=reject): [Implementation instructions with VMC/SVG logo requirements]

DMARC Reporting Setup:
- Aggregate report parser: [Dmarcian / Valimail / URIports — free vs. paid tradeoffs]
- Alert setup: [Automated alerts for policy failures >X%]

═══════════════════════════════════════════
SECTION 6: SENDER REPUTATION RECOVERY PLAN
═══════════════════════════════════════════

[Include this section only if reputation score is below 70/100]

Current Reputation Status: [Damaged/Rebuilding/Unknown]
Primary Signal Drivers: [List what's hurting the reputation score]

30-Day Recovery Schedule:

Week 1 — Triage & Stabilize:
- Suppress [X%] of list (all high-risk segments)
- Reduce daily send volume to: [Y emails/day]
- Send to: Engaged-only segment (opened in last 30 days)
- Content restriction: No promotional content — only high-value, expected content
- Complaint rate target: <0.05%

Week 2 — Controlled Expansion:
- Volume increase: [+25% if complaint rate holds below threshold]
- Add segment: 90-day engaged subscribers
- Monitor: Postmaster Tools daily, bounce rate hourly during sends

Week 3-4 — Graduated Ramp:
- Expand to 6-month engaged
- Volume: [Z emails/day]
- Engagement threshold to proceed: Open rate >[X%], complaint rate <[Y%]

Post-Recovery Maintenance:
- Engagement-based send frequency: [Algorithm for scoring contacts and adjusting frequency]
- Reputation monitoring: [Specific tools and check frequency]

═══════════════════════════════════════════
SECTION 7: ONGOING MONITORING & ALERT SYSTEM
═══════════════════════════════════════════

Weekly KPI Dashboard:
KPI 1: Inbox Placement Rate — Target: >95% — Alert: <90%
KPI 2: Spam Complaint Rate — Target: <0.05% — Alert: >0.08% (Google threshold), Critical: >0.10%
KPI 3: Hard Bounce Rate — Target: <0.5% — Alert: >1%
KPI 4: Soft Bounce Rate — Target: <2% — Alert: >3%
KPI 5: Gmail Postmaster Domain Reputation — Target: High — Alert: Medium, Critical: Low/Bad
KPI 6: List Growth Rate — Target: Net positive — Alert: List shrinking >2%/month
KPI 7: Click-to-Open Rate (CTOR) — Target: >[industry benchmark]% — Alert: <50% of benchmark
KPI 8: Unsubscribe Rate — Target: <0.2% — Alert: >0.3%
KPI 9: Reply-to-Complaints Ratio — Target: >10:1 — Alert: <5:1
KPI 10: SPF/DKIM/DMARC Pass Rate — Target: 100% — Alert: <99%

Automated Alert Playbooks:
TRIGGER: Spam complaint rate >0.10% on any single campaign
ACTION: Auto-pause all non-transactional sends → Alert deliverability lead via Slack → Generate segment analysis within 30 minutes

TRIGGER: Hard bounce spike >2% in 24-hour window
ACTION: Suppress affected domain segment → Run validation → Escalate if systemic

TRIGGER: Gmail Postmaster drops to "Medium" reputation
ACTION: Reduce send frequency by 50% → Re-engagement campaign for Gmail segment → Daily monitoring

═══════════════════════════════════════════
SECTION 8: PROJECTED REVENUE IMPACT
═══════════════════════════════════════════

Current State Revenue Leakage:
- Estimated emails not reaching inbox: [X/month]
- Estimated lost pipeline from deliverability failures: $[Y]
- Estimated revenue impact of [Z%] open rate improvement at current conversion rates: $[calculated]

Fix-by-Fix Revenue Attribution:
Fix 1: [Authentication hardening] → Expected inbox placement improvement: [+X%] → Revenue impact: $[Y/year]
Fix 2: [List hygiene] → Expected engagement rate improvement: [+X%] → Revenue impact: $[Y/year]
Fix 3: [Reputation recovery] → Expected open rate improvement: [+X%] → Revenue impact: $[Y/year]

90-Day Revenue Recovery Target: $[Total projected improvement]
Key Assumption: [X% of emails currently going to spam, at Y% pipeline conversion rate, Z ACV]

## Example Input/Output

**Input:**
Company: Fulcrum Analytics (B2B SaaS, $8M ARR, marketing analytics platform)
ESP: HubSpot Marketing Hub Enterprise
Monthly send volume: 180,000 emails
List size: 42,000 contacts (mix: 60% organic inbound, 25% content gated, 15% tradeshow/event)
List age: Last hygiene scrub 14 months ago
Current metrics: Open rate 18.2%, Click rate 1.9%, Bounce rate 3.1%, Spam complaint rate 0.14%, Unsubscribe rate 0.4%
Authentication: SPF ✓, DKIM ✓, DMARC: p=none (reporting only)
Primary sending domain: marketing.fulcrumanalytics.io (dedicated subdomain)
Dedicated IP: Yes, dedicated IP, warmed 8 months ago
Recent issues: Gmail open rates dropped 22% over last 60 days, several enterprise prospects reported emails going to spam, bounce rate spike after last tradeshow list import

**Output (abbreviated):**

**Deliverability Health Score: 58/100 — Grade: C — Status: AT RISK**

| Category | Score | Max |
|---|---|---|
| Authentication & Technical Infrastructure | 18 | 25 |
| List Quality & Hygiene | 9 | 25 |
| Engagement Signals & Sender Reputation | 16 | 25 |
| Content & Sending Patterns | 15 | 25 |

**Critical Finding — P0 (Fix Immediately):**

**ISSUE: Spam Complaint Rate at 0.14% — Exceeds Google's 0.10% Enforcement Threshold**
- Root Cause: Tradeshow list imported without permission-based re-opt-in; these contacts have no prior relationship with marketing.fulcrumanalytics.io
- Business Impact: Google is actively deprioritizing emails from this sending domain. Gmail represents ~58% of Fulcrum's prospect database. Every week this continues, domain reputation degrades further — estimated $6,200/month in pipeline lost to spam folder placement.
- Exact Fix:
  - Step 1: Immediately suppress all 6,300 contacts acquired from tradeshow events in the last 14 months from all non-transactional campaigns
  - Step 2: In HubSpot → Contacts → Filters: "Original Source = Event" AND "Create Date >= [14 months ago]" → Create suppression list "Tradeshow-No-Permission-Suppress"
  - Step 3: Apply list exclusion to ALL active campaigns within next 6 hours
  - Step 4: For contacts you want to re-engage legitimately: launch a cold-outbound sequence from a sales rep's personal email domain, not the marketing subdomain
  - Verification: Monitor Google Postmaster Tools daily — complaint rate should drop below 0.08% within 5 business days
  - Expected Result: Complaint rate from 0.14% → 0.04%; Gmail inbox placement from ~62% → ~88% over 30 days

**ISSUE: Hard Bounce Rate at 3.1% — 2.8x Above Industry Ceiling**
- Root Cause: 14-month stale list with no validation; email addresses decaying at ~2%/month naturally; tradeshow imports typically have 8-15% invalid address rate
- Exact Fix:
  - Step 1: Export full contact database from HubSpot as CSV
  - Step 2: Run through NeverBounce bulk verification (API: $0.008/contact, ~$336 for 42K list)
  - Step 3: Suppress all "Invalid" results immediately; move "Risky" to monthly re-engagement only
  - Step 4: Configure HubSpot to auto-suppress hard bounces (Settings → Marketing Email → Subscription Types → automatic suppression already on — verify it hasn't been disabled)
  - Step 5: For future imports: implement NeverBounce API validation at form submission (HubSpot workflow → webhook → NeverBounce → reject if invalid before contact is created)

**DMARC Hardening Plan:**
- Current: `v=DMARC1; p=none` — provides zero protection and signals to ISPs that you haven't completed authentication
- Week 1: Add `rua=mailto:dmarc-reports@fulcrumanalytics.io; ruf=mailto:dmarc-failures@fulcrumanalytics.io` to existing none policy
- Week 3 (after confirming <0.5% failure rate in reports): `p=quarantine; pct=10` → `pct=100` by day 14
- Week 7: `p=reject; pct=100`

**Projected Revenue Impact:**
- Current estimated pipeline in spam folder: ~340 leads/month never seeing emails
- At 12% email → MQL conversion, $22K ACV: ~$897K/year pipeline suppressed by deliverability failures
- 90-day remediation target: Recover $320K in reachable pipeline through inbox placement improvements

## Success Metrics

| Metric | Baseline | 30-Day Target | 90-Day Target |
|---|---|---|---|
| Inbox Placement Rate | ~62% (Gmail) | >85% | >95% |
| Spam Complaint Rate | 0.14% | <0.06% | <0.03% |
| Hard Bounce Rate | 3.1% | <1.0% | <0.5% |
| Open Rate (Gmail) | 18.2% | 22%+ | 26%+ |
| DMARC Policy | p=none | p=quarantine | p=reject |
| List Health Score | Unhealthy | Recovering | Healthy |

**Output Quality Criteria:**
- Authentication issues are identified with exact DNS record fixes, not vague recommendations
- List suppression segments are defined with specific HubSpot/Marketo/Klaviyo implementation paths
- Revenue impact is quantified with specific assumptions made transparent
- Recovery timeline includes concrete weekly milestones and go/no-go thresholds

## Related Prompts

- [`Email-Marketing-Performance-Analytics-&-Revenue-Intelligence-Engine.md`](./Email-Marketing-Performance-Analytics-&-Revenue-Intelligence-Engine.md)
- [`Email-Automation-Sequence-Architecture-&-Revenue-Flow-Intelligence-Engine.md`](./Email-Automation-Sequence-Architecture-&-Revenue-Flow-Intelligence-Engine.md)
- [`../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/`](../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/)
- [`../../05_Analytics-&-Performance/Lead-Quality-&-Conversion-Analytics/Marketing-Lead-Quality-&-Sales-Handoff-Intelligence-Engine.md`](../Lead-Quality-&-Conversion-Analytics/Marketing-Lead-Quality-&-Sales-Handoff-Intelligence-Engine.md)

## Integration Tips

**HubSpot Marketing Hub:**
- Connect Google Postmaster Tools via HubSpot's Email Health dashboard (Settings → Marketing Email → Email Health)
- Create suppression workflows: Enrollment trigger = "Email bounce occurred" (type: Hard) → Set contact property "Email Opt Out" = true
- Automate complaint suppression: Connect HubSpot feedback loop via Settings → Email → Bounce & Unsubscribe handling
- Build deliverability monitoring report: Reports → Custom Reports → filter by email send events, bounce types, complaint flags

**Salesforce Marketing Cloud (SFMC):**
- SAP Connect (Send Log) to BigQuery for bounce/complaint trend analysis
- Suppression lists via Data Extensions — sync with Email Studio → Admin → Suppression Lists
- Smart Capture forms: integrate NeverBounce API at form submission via SFMC AMPscript

**Google Postmaster Tools:**
- Register sending domain at postmaster.google.com
- Monitor: Domain Reputation, IP Reputation, Spam Rate, Authentication (SPF/DKIM/DMARC pass rates), Delivery Errors
- Connect via Data Studio (Looker Studio) for automated weekly reports — Google provides native Postmaster Tools connector

**Zapier / Make Automation:**
- Zapier: NeverBounce → HubSpot: Trigger on form submission → validate email → update contact property "Email Valid" → conditional suppression
- Make: Monitor Google Postmaster Tools API → if reputation drops to "Medium" → send Slack alert to #deliverability-ops → create HubSpot task for immediate review

**Klaviyo (E-commerce):**
- Deliverability Hub (built-in): Real-time inbox placement, complaint rate, bounce analysis
- Smart Sending: Klaviyo's native frequency capping — enable for all flows
- Suppression sync: Export Klaviyo suppression list → sync to all connected platforms monthly

**Litmus / Email on Acid:**
- Pre-send spam score testing: Run every campaign through Litmus Spam Testing before deployment
- Inbox preview across 100+ clients: Catch rendering issues that indirectly hurt engagement signals

## Troubleshooting

**Problem: Open rates dropped after Apple MPP (Mail Privacy Protection) inflated then deflated your open metrics — now can't tell what's real.**
Fix: Shift primary measurement to Click-to-Open Rate (CTOR) and click rate, not raw open rate. In HubSpot/Klaviyo, filter Apple Mail opens (User-Agent: Mozilla/5.0 AppleWebKit) out of reporting. Use Google Postmaster Tools spam rate and bounce rate as your ground truth for deliverability health — these are ISP-reported and unaffected by MPP. For A/B testing, use CTOR as your primary winner metric.

**Problem: DMARC reports showing 15-20% authentication failures even though SPF and DKIM are configured.**
Fix: Failures usually stem from email forwarding (breaks SPF alignment) or third-party senders (marketing tools, CRMs, transactional email services) not included in your SPF record. Pull your DMARC aggregate XML reports and parse them (use Dmarcian free tier or MXToolbox DMARC analyzer). Look for source IPs sending on your domain's behalf that aren't in your SPF record. Common culprits: Intercom, Zendesk, Sendgrid, Mailchimp, Salesforce. Add each legitimate sender to SPF (stay under 10 DNS lookup limit — use SPF flattening tools like dmarcly.com if needed). Set DKIM signing in each platform. DKIM alignment is preferred over SPF alignment for forwarded mail.

**Problem: Rebuilt reputation, reduced complaints, but Gmail inbox placement is still stuck at 70-75%.**
Fix: At this stage, deliverability is primarily an engagement problem, not a technical one. Gmail's algorithm heavily weights positive engagement signals (replies, moves from spam to inbox, stars, forwards) over neutral signals (opens, clicks). Run a "Gmail Engagement Reset" campaign: export your Gmail-domain contacts who have opened in the last 90 days → send a single high-value email asking them to reply with one word (works for B2B: "Reply 'Yes' to get our new benchmark report"). Replies are the strongest positive signal Gmail tracks. Also ensure you're sending to engaged segments only for 30 days — Gmail evaluates the engagement quality of your sends in aggregate, not just per-recipient.

## Version History
- v1.0: Initial creation (auto-generated, 2026-03-23)
