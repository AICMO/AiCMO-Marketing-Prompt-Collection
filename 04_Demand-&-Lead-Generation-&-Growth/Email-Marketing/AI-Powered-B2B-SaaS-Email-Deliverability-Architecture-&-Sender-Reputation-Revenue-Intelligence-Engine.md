# AI-Powered B2B SaaS Email Deliverability Architecture & Sender Reputation Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** email-deliverability, sender-reputation, email-marketing, inbox-placement, spf-dkim-dmarc, list-hygiene, email-warmup, domain-reputation, suppression-management, b2b-saas, marketing-operations, hubspot, marketo, sendgrid

## Overview

This prompt deploys an autonomous email deliverability diagnostic and remediation system that audits your sender infrastructure, rebuilds damaged domain reputation, designs domain warming schedules, and creates permanent deliverability governance protocols — restoring inbox placement rates to 90%+ and protecting revenue-critical email programs from Gmail and Microsoft filtering. Use it when open rates have dropped unexpectedly, when a new sending domain or IP needs warming, when your bounce rate exceeds 2%, or when you suspect spam folder filtering is silently killing pipeline.

## Quick Copy-Paste Version

You are a senior email deliverability architect and B2B SaaS marketing operations specialist with 15 years of experience managing high-volume sending infrastructures across HubSpot, Marketo, Salesforce Marketing Cloud, SendGrid, and Mailgun. I need you to diagnose and fix my email deliverability program.

My situation:
- Company: [COMPANY NAME], selling [PRODUCT] to [ICP — e.g., VP of Finance and CFOs at PE-backed companies with $50M–$500M in revenue]
- Monthly send volume: [e.g., 250,000 emails/month across marketing automation and sales sequences]
- Primary sending platform: [e.g., HubSpot Marketing Hub + Outreach for sales sequences]
- Current symptoms: [e.g., average open rate dropped from 32% to 18% over 90 days, Gmail filtering 30%+ to spam, bounce rate at 3.1%]
- Domain setup: [e.g., primary domain company.com for marketing, subdomain outreach.company.com for sales sequences — SPF configured, DKIM partially set up, no DMARC]

Produce a complete Email Deliverability Audit & Remediation Architecture with these components:

1. DELIVERABILITY HEALTH SCORECARD — Score my program (0–100) across 8 dimensions: SPF/DKIM/DMARC configuration, domain age and reputation, IP reputation, list hygiene score, engagement rate trends, bounce/complaint rates, sending consistency, and content/spam trigger risk. For each dimension: current state assessment based on the symptoms I described, benchmark score, my estimated score, and priority level (Critical/High/Medium).

2. TECHNICAL INFRASTRUCTURE REMEDIATION PLAN — Provide exact configuration steps for:
   - SPF record: Write the exact SPF TXT record for my DNS based on my sending platforms
   - DKIM: Step-by-step DKIM key rotation and selector configuration
   - DMARC: Progressive DMARC policy rollout (p=none → p=quarantine → p=reject) with monitoring cadence and RUA/RUF reporting setup
   - MX record validation for bounce processing
   - BIMI logo setup for brand trust signal (if DMARC p=reject achieved)

3. DOMAIN & IP WARMING SCHEDULE — If I need to warm a new subdomain or IP:
   - 8-week progressive warming calendar (Day 1: volume, Day 7: volume, Week 2–4 ramp, etc.)
   - Engagement tier segmentation for warming: which list segments to use in which order (most engaged first)
   - Throttling rules and daily send caps per week of warming
   - Go/no-go metrics to accelerate or pause warming

4. LIST HYGIENE & SUPPRESSION ARCHITECTURE — Design a permanent list hygiene protocol:
   - Real-time email validation setup at all capture points (web forms, CRM imports, API integrations)
   - Automated suppression rules: hard bounce (immediate), soft bounce (3 strikes), complaint (immediate), 6-month non-opener re-engagement or suppress
   - Sunset policy: Define the re-engagement sequence for cold subscribers, the sunset criteria, and the suppression list maintenance cadence
   - List segmentation by engagement tier: Active (opened last 30 days), Warm (opened last 90 days), Cold (90–180 days), Sunset candidates (180+ days)

5. INBOX PLACEMENT TESTING PROTOCOL — Define a pre-send deliverability QA checklist:
   - Seed list testing tools and setup (GlockApps, Litmus Spam Testing, MXToolbox)
   - Pre-campaign checklist: 10 items to check before every batch send >10,000 emails
   - Spam trigger content audit: 15 phrases and formatting patterns to avoid
   - A/B testing variables that improve inbox placement (from/name, subject length, plain text vs. HTML ratio)

6. REPUTATION MONITORING & ALERTING — Build an always-on reputation monitoring stack:
   - Google Postmaster Tools setup and key metrics to track weekly (domain reputation, IP reputation, spam rate)
   - Microsoft SNDS enrollment and monitoring cadence
   - Feedback loop (FBL) enrollment with major ISPs
   - Alert thresholds: when to pause sending, when to escalate to deliverability specialist
   - Monthly deliverability health report template

7. 90-DAY REMEDIATION ROADMAP — Prioritized action plan:
   - Week 1–2: Critical infrastructure fixes
   - Week 3–4: List hygiene cleanup and suppression rebuild
   - Week 5–8: Reputation rebuilding via engaged-segment-only sending
   - Week 9–12: Full volume resumption with new governance protocols
   - KPIs to track: target inbox placement rate, spam complaint rate, bounce rate, and open rate milestones per phase

Output as a structured operations playbook that my marketing ops team can hand directly to our email platform admin and DNS engineer.

## Advanced Customizable Version

ROLE: You are an Email Deliverability Architect and Revenue Operations Specialist with deep expertise in B2B SaaS email infrastructure, ISP filtering algorithms (Google, Microsoft, Yahoo), and marketing automation platforms. You understand that email deliverability is not a technical footnote — it is a direct revenue lever: a 10-point drop in inbox placement rate for a company sending 500,000 emails/month can suppress $2M+ in annual pipeline.

COMPANY CONTEXT:
- Company: [COMPANY NAME]
- Product/Service: [DESCRIBE PRODUCT AND KEY VALUE PROP]
- ICP: [JOB TITLE, COMPANY SIZE, INDUSTRY]
- Annual Revenue: [ARR/REVENUE — helps calibrate send volume expectations]
- Team Size: [Marketing team size — 2-person scrappy vs. 15-person enterprise]

SENDING INFRASTRUCTURE:
- Primary Marketing Automation Platform: [HubSpot / Marketo / Pardot / SFMC / ActiveCampaign]
- Sales Sequencing Tool: [Outreach / Salesloft / Apollo / Groove / None]
- Transactional Email Provider: [SendGrid / Mailgun / AWS SES / Postmark]
- ESP/SMTP Relay: [If separate from above]
- Dedicated IPs: [Yes/No — if yes, how many]
- Shared IP Pool: [Yes/No]
- Sending Domains: [List all domains and subdomains used for email sending]

CURRENT PROGRAM METRICS:
- Monthly Send Volume: [X emails/month, split by: marketing automation / sales sequences / transactional]
- Average Open Rate (last 90 days): [X%] — Benchmark: 25–35% for engaged B2B lists
- Average Click-to-Open Rate: [X%] — Benchmark: 10–20%
- Hard Bounce Rate: [X%] — Should be <0.5%
- Soft Bounce Rate: [X%] — Should be <2%
- Spam Complaint Rate: [X%] — Must be <0.1% (Google threshold)
- Unsubscribe Rate: [X%] — Benchmark: <0.3% per send
- Inbox Placement Rate: [X% if known from seed testing — otherwise "unknown"]
- Google Postmaster Domain Reputation: [High/Medium/Low/Bad — check at postmaster.google.com]

SYMPTOMS & TRIGGER FOR THIS AUDIT:
[Describe what prompted this: sudden open rate drop, ISP block notice, spam complaint spike, new domain setup, platform migration, list import from acquisition, etc.]

AUDIENCE SEGMENTS:
- Total contactable database size: [X contacts]
- Engagement tiers (approximate): Active (last 30d): [X%], Warm (31–90d): [X%], Cold (91–180d): [X%], Dormant (180d+): [X%]
- Opt-in sources: [Gated content, demo requests, event registrations, purchased lists, CRM legacy contacts, etc.]
- Geographic distribution: [US-only / EU-heavy (GDPR) / Global — affects compliance requirements]

COMPLIANCE CONTEXT:
- GDPR compliance: [In scope / Not in scope]
- CAN-SPAM compliance: [Always in scope for US]
- CASL compliance: [In scope if Canadian contacts]
- Existing consent management: [Tool used — OneTrust, Cookiebot, custom, none]

BUSINESS OBJECTIVES:
- Primary email goal: [Pipeline generation / Customer retention / Product adoption / All]
- Revenue tied to email: [Estimated % of pipeline influenced by email marketing]
- Recovery timeline target: [e.g., "Need inbox placement back above 85% within 60 days for Q3 demand gen"]
- Budget for deliverability tooling: [e.g., <$500/month / $500–$2,000/month / $2,000+/month]

---

DELIVERABLE: Produce a comprehensive Email Deliverability Architecture & Remediation Playbook covering all sections below. Every recommendation must be specific, actionable, and executable by a marketing ops manager without requiring an external consultant.

---

SECTION 1: DELIVERABILITY HEALTH DIAGNOSTIC SCORECARD

Score the program across 8 dimensions (0–100 scale for each, weighted total score):

**Dimension 1 — Authentication Infrastructure (Weight: 25%)**
- SPF: Is the SPF record properly configured? Is it within the 10-lookup limit? Are all sending sources authorized? Score: 0 (missing) → 50 (partial) → 100 (fully configured, under 10 lookups, all sources included)
- DKIM: Is DKIM implemented on all sending domains/subdomains? Is key length ≥2048 bits? Is key rotation scheduled? Score accordingly.
- DMARC: Policy level (p=none=25pts, p=quarantine=75pts, p=reject=100pts). Is RUA reporting active? Is DMARC alignment enforced?
- BIMI: Bonus 10pts if BIMI implemented with VMC certificate
- Output: Exact DNS TXT record templates for each missing or misconfigured element

**Dimension 2 — List Quality & Consent Health (Weight: 20%)**
- Bounce rate analysis: Score based on hard bounce % (0–0.5%=100, 0.5–1%=70, 1–2%=40, >2%=10)
- Complaint rate analysis: (0–0.05%=100, 0.05–0.1%=75, 0.1–0.3%=25, >0.3%=0)
- List age and acquisition method quality score
- Duplicate and invalid address % estimate
- Consent documentation quality (express opt-in=100, soft opt-in=60, legacy/unclear=20, purchased=0)
- Output: Priority list hygiene actions with estimated impact on each metric

**Dimension 3 — Engagement Rate Trend (Weight: 20%)**
- 90-day open rate trend (improving/stable/declining)
- Click-to-open rate benchmark comparison
- Unsubscribe rate trend
- Engagement cohort decay rate (how fast does list engagement degrade?)
- Output: Engagement tier segmentation rules and cadence recommendations

**Dimension 4 — Sending Behavior Patterns (Weight: 15%)**
- Volume consistency score (steady daily sends vs. sporadic large batches)
- Time-of-day and day-of-week optimization score
- Throttling and rate limiting configuration
- Output: Recommended sending cadence pattern and volume caps

**Dimension 5 — Content & Template Quality (Weight: 10%)**
- HTML-to-text ratio (ideal: 60/40)
- Image-to-text ratio
- Link volume per email
- Spam trigger phrase audit (top 20 high-risk phrases for B2B SaaS)
- Unsubscribe link prominence and one-click compliance
- Output: Template audit checklist and rewrite recommendations

**Dimension 6 — IP Reputation (Weight: 5%)**
- Shared vs. dedicated IP analysis for current volume
- Blacklist status check across major RBLs (Spamhaus, Barracuda, SORBS)
- IP warming history
- Output: IP strategy recommendation

**Dimension 7 — Platform Configuration (Weight: 3%)**
- Bounce processing automation (auto-suppress hard bounces?)
- Unsubscribe processing SLA (should be <10 business days for CAN-SPAM, immediate recommended)
- Feedback loop (FBL) enrollment status
- Output: Platform configuration checklist

**Dimension 8 — Monitoring & Governance (Weight: 2%)**
- Google Postmaster Tools active?
- Microsoft SNDS enrolled?
- Regular seed testing cadence?
- Deliverability review cadence?
- Output: Monitoring stack setup guide

TOTAL WEIGHTED SCORE: [Calculated] / 100
Risk Level: 80–100 = Healthy | 60–79 = At Risk | 40–59 = Degraded | <40 = Critical

---

SECTION 2: TECHNICAL REMEDIATION SPECIFICATIONS

For each authentication record, provide:

**SPF Configuration:**
v=spf1 include:[platform1] include:[platform2] ip4:[dedicated-IP-range] ~all
- Write the exact SPF record for my specific platform stack
- Identify any over-permissive mechanisms (avoid "+all")
- Identify SPF flattening need if >10 DNS lookups
- Recommend SPF flattening service if needed (dmarcly.com, Postmark SPF Flattener)

**DKIM Configuration:**
- Selector naming convention for each platform
- Key generation commands for self-hosted DKIM
- DKIM rotation schedule (recommend every 6–12 months)
- Dual-selector setup for zero-downtime rotation
- Platform-specific DKIM setup guides (HubSpot, Outreach, SendGrid)

**DMARC Progressive Rollout:**
Phase 1 (Week 1): `v=DMARC1; p=none; rua=mailto:dmarc-reports@[company.com]; ruf=mailto:dmarc-forensics@[company.com]; sp=none; adkim=r; aspf=r; pct=100`
Phase 2 (Week 4–6, if <5% DMARC failures): `v=DMARC1; p=quarantine; rua=mailto:...; pct=10` → increase pct gradually
Phase 3 (Week 10–12): `v=DMARC1; p=reject; rua=mailto:...; pct=100`

- DMARC reporting parser recommendations (Dmarcian, Valimail, EasyDMARC)
- How to interpret DMARC aggregate reports
- Failure analysis: Common sources of DMARC failure (forwarding, third-party senders, CRM integrations)

---

SECTION 3: DOMAIN WARMING MASTER PLAN

**For New Domain/Subdomain Warming:**

Provide an 8-week warming calendar:

| Week | Daily Max Volume | Cumulative Sends | Segment | Throttle Rate | Expected Inbox % |
|------|-----------------|------------------|---------|---------------|------------------|
| 1    | 200/day         | 1,400            | Hyper-engaged (opened last 14 days) | 50/hr | 90%+ |
| 2    | 500/day         | 5,000            | Engaged (opened last 30 days) | 100/hr | 85%+ |
| 3    | 1,500/day       | 15,500           | Active (opened last 60 days) | 200/hr | 80%+ |
| 4    | 3,000/day       | 36,500           | Warm (opened last 90 days) | 400/hr | 75%+ |
| 5    | 6,000/day       | 78,500           | Broad warm (opened last 120 days) | 600/hr | 75%+ |
| 6    | 12,000/day      | 162,500          | Standard active list | 1,000/hr | 80%+ |
| 7    | 25,000/day      | 337,500          | Full engaged list | 2,000/hr | 82%+ |
| 8    | Full volume      | Ongoing          | All segments per normal cadence | Platform default | 85%+ |

- Warm-up acceleration criteria: If inbox placement >90% AND complaint rate <0.05% AND bounce rate <0.5% for 7 consecutive days, advance to next phase
- Warm-up pause criteria: If spam complaint rate >0.15% OR inbox placement <70% for 3 days → pause, diagnose, remediate before continuing
- Content strategy during warming: Send highest-value, most relevant content during warming (avoid promotional/offer emails in weeks 1–2)

**For Reputation Rebuilding on Existing Domain:**
- 30-day engagement-only sending protocol (send only to opened-last-90-days segment)
- Progressive re-inclusion schedule for cold segments (weeks 4–8)
- Win-back sequence design for 90–180-day cold segment before bulk resumption

---

SECTION 4: LIST HYGIENE SYSTEM ARCHITECTURE

**Real-Time Validation Layer (at point of capture):**
- JavaScript email validation at form level: syntax check, disposable domain detection, role-based address blocking (info@, noreply@, admin@)
- API-level email verification integration: NeverBounce, ZeroBounce, or Kickbox API setup at form submission
- CRM import hygiene: Pre-import scrub workflow before any list upload
- Recommended tools with pricing tier: NeverBounce ($8/1,000), ZeroBounce ($15/1,000 with scoring), Kickbox ($0.008/email for Detect API)

**Automated Suppression Rules (build in MAP):**
IF hard_bounce = true → suppress immediately, add to global suppression list, flag in CRM
IF soft_bounce_count >= 3 (within 30 days) → suppress, flag for manual review
IF spam_complaint = true → suppress immediately, flag in CRM as "complaint", notify CSM if customer
IF unsubscribe = true → suppress immediately across all lists, sync to CRM within 24hrs
IF last_open_date > 180 days AND no_purchase_history → add to sunset_candidate tag
IF last_open_date > 365 days → suppress from all marketing, move to archived segment

**Engagement Tier Segmentation Model:**
| Tier | Criteria | Send Cadence | Content Type | List Size Expectation |
|------|----------|--------------|--------------|----------------------|
| Tier 1: Champions | Opened last 30 days, clicked last 60 days | 2–3x/week | All content including promotional | 15–25% of list |
| Tier 2: Active | Opened last 30–60 days | 1–2x/week | Educational + light CTA | 20–30% of list |
| Tier 3: Warm | Opened last 60–90 days | 1x/week | High-value educational only | 15–20% of list |
| Tier 4: Cold | Opened last 90–180 days | 2x/month max | Re-engagement content | 20–30% of list |
| Tier 5: Sunset | No open 180+ days | Re-engagement sequence only (max 3 emails) | "We miss you" + unsubscribe nudge | 15–25% of list |
| Suppressed | Bounced, complained, or post-sunset | No sends | N/A | Remove from all sends |

**Sunset Re-Engagement Sequence (3-email max):**
- Email 1 (Day 1): "We haven't heard from you in a while — is this email still useful?" — Single CTA: "Yes, keep me subscribed"
- Email 2 (Day 7): "One last thing before we say goodbye" — Highest-value asset or offer, single CTA to confirm interest
- Email 3 (Day 14): "We're removing you from our list tomorrow" — Final chance, automatic suppression if no click within 48hrs
- Post-sunset: Move to CRM-only for sales-touch consideration, remove from all marketing lists permanently

---

SECTION 5: PRE-SEND DELIVERABILITY QA PROTOCOL

**10-Point Pre-Send Checklist (required before any send >5,000 recipients):**

☐ 1. **Authentication check**: Verify SPF/DKIM/DMARC pass using mail-tester.com or MXToolbox Email Header Analyzer on test send
☐ 2. **Spam score test**: Run email through GlockApps ($29/month) or Litmus Spam Testing — target <3.0 SpamAssassin score
☐ 3. **Inbox placement seed test**: Test across Gmail, Outlook, Yahoo, Apple Mail using GlockApps seed list — must be >80% inbox before sending
☐ 4. **Bounce rate check**: Verify recipient segment bounce rate <0.5% in last 30 days
☐ 5. **Engagement qualifier**: Confirm send segment meets minimum engagement threshold (e.g., opened at least once in last 90 days, or new opt-in)
☐ 6. **Spam trigger scan**: Run subject line through IsNotSpam.com, run body through SpamAssassin checker
☐ 7. **Unsubscribe link audit**: Confirm one-click unsubscribe in header (required for Gmail bulk senders >5K/day since Feb 2024) AND visible link in body
☐ 8. **HTML/text ratio**: Confirm HTML email has plain-text alternative; verify image-to-text ratio is not image-heavy (>60% text preferred)
☐ 9. **Link validation**: Test all links are live, not redirecting through flagged domains, using UTM parameters correctly
☐ 10. **Volume throttle**: Confirm send volume and sending speed are within warmed capacity — no sudden volume spikes >3x normal daily volume

**High-Risk Spam Trigger Phrases for B2B SaaS (avoid in subject lines and above-the-fold copy):**
- "Free trial" (use "try it" or "start your trial")
- "Act now" / "Don't miss out" / "Limited time"
- "Click here" / "Click below"
- "100% free" / "No cost"
- "Guaranteed" / "Risk-free"
- ALL CAPS in subject line
- Excessive punctuation "!!!" or "???"
- "$$$" or excessive dollar signs
- "Winner" / "Congratulations" / "You've been selected"
- "Unsubscribe" in subject line

---

SECTION 6: REPUTATION MONITORING STACK

**Google Postmaster Tools (Free — setup required):**
- Domain verification: Add TXT record to DNS, verify within 24hrs
- Key metrics to monitor weekly:
  - Domain Reputation: High (green) = healthy, Medium (yellow) = watch, Low (orange) = remediate now, Bad (red) = stop all sending immediately
  - Spam Rate: Must stay below 0.10% (Google threshold for bulk senders)
  - Authentication: % of email passing SPF, DKIM, DMARC alignment
  - Delivery Errors: Identify specific error codes (550 = rejected, 421 = throttled)
- Weekly review cadence: Every Monday, 15-minute review of prior week's metrics

**Microsoft SNDS (Smart Network Data Services — Free):**
- Enrollment: postmaster.live.com → request access for sending IP addresses
- Key metrics: Complaint rate, trap hits, filter verdict
- Junk Mail Reporting Program (JMRP): Enroll to receive complaint notifications
- IP Delist: services.live.com/services/snds if blocked by Microsoft

**Monthly Deliverability Health Report Template:**
MONTHLY EMAIL DELIVERABILITY HEALTH REPORT — [MONTH YEAR]

EXECUTIVE SUMMARY: [1-sentence status: Healthy / At Risk / Degraded]

AUTHENTICATION STATUS:
- SPF: ✅ Pass / ⚠️ Issues / ❌ Fail
- DKIM: ✅ Pass / ⚠️ Issues / ❌ Fail
- DMARC Policy: [none/quarantine/reject] — Failure rate: [X%]

INBOX PLACEMENT (from monthly seed test):
- Gmail: [X%] (Target: >90%)
- Outlook/Microsoft: [X%] (Target: >85%)
- Yahoo/AOL: [X%] (Target: >85%)
- Apple Mail: [X%] (Target: >90%)
- Overall: [X%] (Target: >88%)

ENGAGEMENT METRICS:
- Open Rate: [X%] (Prior month: [X%] | Trend: ↑/↓/→)
- Click-to-Open Rate: [X%] (Prior month: [X%] | Trend: ↑/↓/→)
- Unsubscribe Rate: [X%] (Benchmark: <0.3%)
- Spam Complaint Rate: [X%] (Threshold: <0.10%)

LIST HEALTH:
- Hard Bounce Rate: [X%] (Threshold: <0.5%)
- Soft Bounce Rate: [X%] (Threshold: <2%)
- Emails suppressed this month: [X] (Hard bounce: [X], Complaint: [X], Sunset: [X])
- Net contactable list change: [+X / -X]

BLACKLIST STATUS: [Clean / Listed on: X]

ACTIONS TAKEN THIS MONTH: [Summary]
ACTIONS REQUIRED NEXT MONTH: [Priority list]

---

SECTION 7: 90-DAY REMEDIATION ROADMAP

**Phase 1: Triage & Infrastructure (Days 1–14)**
Priority: Stop the bleeding, fix authentication

Actions:
- Day 1–3: Run full authentication audit (SPF, DKIM, DMARC, MX). Fix any critical misconfigurations.
- Day 1–3: Pause all sends to contacts with >180 days no engagement
- Day 1–3: Pause all sales sequences to contacts who have not opted in via marketing (if complaints are from prospecting lists)
- Day 3–5: Emergency list scrub — run all active contacts through NeverBounce, remove invalid/risky addresses
- Day 5–7: Enroll in Google Postmaster Tools and Microsoft SNDS if not already active
- Day 7–10: Reduce send volume by 50% — send only to engaged (last 60 days opened) contacts
- Day 10–14: Implement pre-send QA checklist; run seed test on reduced list
- KPI targets by Day 14: Bounce rate <1%, Complaint rate <0.08%, Volume reduced to engaged-only

**Phase 2: Reputation Repair (Days 15–45)**
Priority: Rebuild sender reputation through engagement quality

Actions:
- Send only to Tier 1 and Tier 2 segments (opened last 60 days)
- Send only highest-value content (no promotional emails, no discount offers, no "buy now")
- Reduce send frequency by 40% (quality over quantity)
- Implement sunset sequence for 180+ day dormant contacts (3-email series then suppress)
- Run A/B tests on subject lines and from-names to identify highest-engagement variants
- Weekly Google Postmaster Tools review — track domain reputation score improvement
- KPI targets by Day 45: Domain reputation = Medium or High, Open rate recovering toward baseline, Complaint rate <0.05%

**Phase 3: Gradual Volume Recovery (Days 46–75)**
Priority: Reintroduce cold segments carefully

Actions:
- Re-engage Tier 3 (opened last 90–180 days) with 2x/month cadence, educational content only
- Run pre-send seed test for every send to Tier 3 before deploying
- Increase send frequency by 20% per week if inbox placement remains >80%
- Implement real-time email validation at all new capture points
- Deploy DMARC p=quarantine (if p=none was Phase 1 starting point)
- KPI targets by Day 75: Open rate within 80% of pre-issue baseline, Inbox placement >82% across major ISPs

**Phase 4: Full Governance Implementation (Days 76–90)**
Priority: Permanent infrastructure and governance protocols

Actions:
- Launch monthly deliverability health report cadence
- Complete full warming back to original send volume
- Progress DMARC to p=reject if failure rate <2%
- Implement BIMI for Gmail brand trust signal (if budget allows)
- Document updated sending policies in team wiki
- Train sales team on sales sequence email hygiene standards
- KPI targets by Day 90: Inbox placement >88%, Open rate at or above pre-issue baseline, Domain reputation = High, Spam complaint rate <0.05%

---

PLATFORM-SPECIFIC CONFIGURATION NOTES:

**HubSpot:**
- Dedicated sending IP: Available on Marketing Hub Enterprise ($3,600+/month)
- DKIM: Settings → Email → Authentication — add DKIM record for sending domain
- Suppression lists: Settings → Marketing → Email → Subscriptions
- Bounce processing: Automatic for hard bounces; soft bounces after 5 failures
- Compliance: CAN-SPAM unsubscribe processed within 10 business days by default (enable instant unsubscribe in settings)

**Marketo:**
- Dedicated IP: Available on Select and above tiers — request via Marketo support
- DKIM: Admin → Email → DKIM Signatures — requires CNAME records
- Deliverability lab: Marketo Deliverability Power Pack (add-on) includes seed testing
- Suppression: Smart List with "Email Bounced Hard" filter → suppress from all campaigns

**SendGrid:**
- IP Warm-up: Settings → IP Addresses → Enable Automatic Warmup for new IPs
- Domain Authentication: Settings → Sender Authentication — sets up SPF, DKIM, and DMARC in one flow
- Email Activity Feed: Diagnose delivery events in real-time
- Inbound Parse: Set up for bounce processing automation

Output all recommendations in a format ready to be shared as a Confluence/Notion ops playbook with exact DNS record templates, platform configuration screenshots references, and executable weekly review checklists.

## Example Input/Output

**Input Example:**
> Company: DataSync (B2B SaaS — data integration platform), selling to IT Directors and Data Engineering Leads at mid-market companies (500–5,000 employees). HubSpot Marketing Hub Pro + Outreach for sales sequences. Sending 85,000 emails/month. Open rate dropped from 28% to 14% over 60 days. Bounce rate 2.3%. Google Postmaster showing domain reputation dropped from High to Low in past 30 days. SPF configured, DKIM not set up for Outreach subdomain, no DMARC. No seed testing previously done.

**Output Example (excerpt):**

**DELIVERABILITY HEALTH SCORECARD — DataSync**
Total Score: 34/100 — CRITICAL

| Dimension | Score | Status | Priority |
|-----------|-------|--------|----------|
| Authentication Infrastructure | 25/100 | No DKIM for Outreach, no DMARC — spoofing risk | CRITICAL |
| List Quality & Consent Health | 20/100 | 2.3% bounce rate indicates 12–18 months of stale contacts | CRITICAL |
| Engagement Rate Trend | 35/100 | 50% open rate decline in 60 days = active reputation damage | CRITICAL |
| Sending Behavior | 55/100 | 85K/month is manageable but needs throttling | HIGH |
| Content & Template Quality | 60/100 | HTML heavy templates flagging — needs audit | MEDIUM |
| IP Reputation | 40/100 | HubSpot shared IP — check HubSpot IP reputation | HIGH |
| Platform Configuration | 45/100 | Bounce processing active but no FBL | HIGH |
| Monitoring & Governance | 10/100 | No Postmaster Tools monitoring until now | HIGH |

**Immediate Actions (Next 48 Hours):**
1. Pause all sending to contacts with last open >90 days (estimated 35–40K contacts based on typical decay)
2. Add Outreach DKIM: In Outreach admin, go to Settings → Email → Domain Settings → Add DKIM record `selector1._domainkey.outreach.datasync.com` with the key Outreach provides
3. Set up DMARC monitoring (p=none to start): `v=DMARC1; p=none; rua=mailto:dmarc@datasync.com; pct=100` — add to DNS as TXT record at `_dmarc.datasync.com`
4. Run NeverBounce bulk verification on entire active list — budget $680 for 85,000 contacts at $8/1,000 — remove all Invalid and Risky addresses

**8-Week Domain Warming Schedule for New Outreach Subdomain (outreach.datasync.com):**
- Week 1: Max 200 emails/day — use only contacts who opened within last 14 days
- Week 2: Max 600 emails/day — contacts who opened within last 30 days
- Week 3: Max 1,800 emails/day — contacts who opened within last 60 days
...

*By Week 8: DataSync projects return to 22–25% open rate on recovered list of ~55,000 contacts (post-hygiene from current 85,000), with domain reputation restored to Medium within 30 days and High within 60 days.*

## Success Metrics

**Deliverability Infrastructure:**
- ✅ SPF passes 100% on all sending domains (verify via mail-tester.com — target score 9+/10)
- ✅ DKIM signatures valid on all sending domains and subdomains
- ✅ DMARC policy at minimum p=quarantine within 60 days, p=reject within 90 days
- ✅ Google Postmaster domain reputation at High or Medium (never Low or Bad)
- ✅ Microsoft SNDS complaint rate <0.3% (their threshold for investigation)

**List Health:**
- ✅ Hard bounce rate <0.5% per campaign
- ✅ Spam complaint rate <0.08% (well below Google's 0.10% threshold)
- ✅ Soft bounce rate <1.5%
- ✅ Unsubscribe rate <0.3% per campaign

**Inbox Placement (measured monthly via seed testing):**
- ✅ Gmail inbox placement >90%
- ✅ Outlook/Microsoft inbox placement >85%
- ✅ Yahoo inbox placement >85%
- ✅ Overall weighted inbox placement >88%

**Engagement Recovery:**
- ✅ Open rate restored to within 15% of pre-issue baseline within 60 days
- ✅ Click-to-open rate maintains >12%
- ✅ Monthly deliverability health report completed and reviewed

## Related Prompts

- [AI-Powered B2B SaaS Inbound Email Marketing Architecture](./AI-Powered-B2B-SaaS-Inbound-Email-Marketing-Architecture-&-Behavioral-Lead-Lifecycle-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Outbound Cold Email Prospecting Architecture](./AI-Powered-B2B-SaaS-Outbound-Cold-Email-Prospecting-Architecture-&-Pipeline-Generation-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Marketing Operations KPI Dashboard](../../05_Analytics-&-Marketing-Operations/AI-Powered-B2B-SaaS-Marketing-Operations-Real-Time-KPI-Dashboard-&-Autonomous-Performance-Reporting-Revenue-Intelligence-Engine.md)
- [Revenue Operations Data Quality & CRM Hygiene Intelligence Engine](../../05_Analytics-&-Marketing-Operations/MarTech-Stack-Optimization/Revenue-Operations-Data-Quality-&-CRM-Hygiene-Intelligence-Engine.md)

## Integration Tips

**HubSpot:**
- Create a dynamic list "Active — Opened Last 30 Days" for Tier 1 segment, update enrollment criteria daily
- Build workflow: Contact property "Email Bounced Hard = True" → Set lifecycle stage to "Unqualified" → Add to global suppression list
- Use HubSpot's built-in Email Health dashboard (Marketing → Email → Health) to monitor deliverability metrics weekly

**Marketo:**
- Create a Smart Campaign with "Email Bounced Hard" trigger → Add to Blocklist → Change data value "Email Invalid = True"
- Set up Revenue Cycle Modeler to track email-influenced pipeline separately from non-email-touched contacts
- Use Marketo Engagement Programs (streams) to automatically manage engagement tier transitions

**SendGrid / Mailgun / AWS SES (Transactional):**
- Set up Webhook integrations to push bounce and complaint events back to your CRM in real-time
- Use Event Webhook with filtered event types: `bounce`, `spamreport`, `unsubscribe` → trigger CRM suppression via Zapier or native integration
- Configure Suppression Groups in SendGrid to honor category-level unsubscribes (product emails vs. marketing vs. transactional)

**Google Postmaster Tools + Zapier:**
- Pull Postmaster Tools API data weekly → log to Google Sheets → trigger Slack alert if domain reputation drops below "High"
- API endpoint: `https://gmailpostmastertools.googleapis.com/v1beta1/domains/{domain}/trafficStats`

**Notion/Confluence Documentation:**
- Store monthly deliverability health reports in a running page with trend charts
- Maintain "Sending Policy Playbook" as living document updated after each major change
- Create pre-send QA checklist as a Notion database template for campaign managers to complete before every batch send

## Troubleshooting

**Problem: Open rates dropped suddenly but authentication looks clean**
Solution: The issue is almost always list quality or content, not authentication. Run a seed test immediately (GlockApps) to see actual inbox placement by ISP. If Gmail placement dropped but Outlook is fine, you likely have a domain reputation issue with Google specifically — check Google Postmaster Tools for spam rate spike, and pull back send volume to engaged-only segment for 2–3 weeks while Google reputation recovers.

**Problem: DMARC p=reject is breaking legitimate email (e.g., automated CRM notifications)**
Solution: This is extremely common. Before moving to p=reject, run on p=quarantine with p=quarantine for 2–4 weeks and review DMARC aggregate reports (via Dmarcian or EasyDMARC). Every legitimate sending source that fails DMARC must be fixed (add to SPF or configure DKIM) before advancing to p=reject. Common culprits: HR systems sending from company domain, support ticketing systems (Zendesk), calendar invites, legacy CRM integrations.

**Problem: Sales sequence emails triggering spam complaints at much higher rates than marketing emails**
Solution: Sales sequences have structurally higher complaint risk because they target non-opted-in cold prospects. Separate your sales outreach onto a subdomain (e.g., outreach.company.com) to protect your primary marketing domain reputation. Implement hard suppression rules: if a contact has marked any marketing email as spam, permanently exclude from all sales sequences. Train SDRs that spray-and-pray sequencing directly damages company revenue by destroying domain reputation.

## Version History
- v1.0: Initial creation (auto-generated)
