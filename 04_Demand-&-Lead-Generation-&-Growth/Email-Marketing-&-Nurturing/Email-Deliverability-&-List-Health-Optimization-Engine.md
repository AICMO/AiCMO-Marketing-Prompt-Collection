# Email Deliverability & List Health Optimization Engine - Full-Stack Deliverability Intelligence System

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** email deliverability, list hygiene, inbox placement, sender reputation, email operations

## Overview
Diagnose and systematically fix email deliverability problems using AI-driven analysis of bounce data, engagement signals, sending infrastructure, and list health metrics. Use this when inbox placement rates drop below 90%, open rates are declining, you're seeing soft/hard bounce spikes, or you're about to launch a major campaign and need to de-risk sending to a large or cold list.

## Quick Copy-Paste Version

You are an email deliverability expert with deep knowledge of ISP filtering algorithms, authentication protocols, and list hygiene best practices.

I need a complete Email Deliverability Diagnostic & Optimization Plan for my email program.

My current situation:
- ESP/Platform: [HubSpot / Mailchimp / Outreach / Klaviyo / etc.]
- List size: [total contacts]
- Monthly send volume: [emails/month]
- Current avg open rate: [X%] (industry benchmark for my space: [Y%])
- Current hard bounce rate: [X%]
- Current soft bounce rate: [X%]
- Spam complaint rate: [X%]
- Primary sending domain: [domain.com]
- Last list import date: [date] — source: [trade show / content download / purchased / organic opt-in]
- Biggest concern: [inbox placement / Gmail tabs / high bounces / low engagement / blacklisting]

Please produce:

1. **Deliverability Health Score** — Rate my program 1-10 across: sender reputation, list hygiene, authentication, content, engagement segmentation. Flag any critical issues (🔴), warnings (🟡), and healthy signals (🟢).

2. **30-Day Remediation Roadmap** — Prioritized action plan organized by:
   - Week 1: Critical fixes (stop the bleeding)
   - Week 2-3: List segmentation & suppression strategy
   - Week 4: Infrastructure hardening & re-engagement campaign launch

3. **Suppression List Strategy** — Rules for automated suppression: which contacts to suppress immediately, which to put through re-engagement, and which to sunset. Include specific engagement thresholds (e.g., "suppress anyone with 0 opens in 180 days AND no web activity").

4. **Re-Engagement Campaign Blueprint** — 3-email win-back sequence for cold subscribers (60-180 days inactive). Include subject lines, email copy framework, and sunset criteria.

5. **Warm-Up / Ramp-Up Schedule** — If my domain/IP reputation needs rebuilding, provide a 4-week volume ramp-up plan with daily send caps per segment.

6. **Monitoring Dashboard Spec** — Specify exactly which metrics to track weekly, alert thresholds, and which tools to use (Google Postmaster Tools, MXToolbox, etc.).

7. **Authentication Checklist** — Verify SPF, DKIM, DMARC, BIMI setup requirements and flag what's likely misconfigured based on my situation.

Output everything in structured tables and checklists that I can paste directly into a project management tool.

## Advanced Customizable Version

ROLE: You are a senior email deliverability consultant with 12+ years of experience managing enterprise email programs for B2B SaaS companies sending 10M+ emails/month. You have deep expertise in ISP filtering logic (Gmail, Microsoft 365, Yahoo), authentication protocols (SPF/DKIM/DMARC/BIMI), list acquisition hygiene, behavioral engagement segmentation, and CAN-SPAM/GDPR compliance. You think in systems — not one-off fixes.

CONTEXT:
Company: [Company name]
Industry: [B2B SaaS / E-commerce / Media / etc.]
Business model: [subscription / transactional / PLG / enterprise sales]
Email program maturity: [startup (<1yr) / established (1-5yr) / mature (5yr+)]

SENDING INFRASTRUCTURE:
- Primary ESP: [platform]
- Secondary ESP (if any): [platform or none]
- Dedicated IP(s): [yes — X IPs / shared pool]
- Sending domains: [list all: marketing.company.com, sales.company.com, etc.]
- Subdomain strategy: [separate for transactional vs. marketing? Y/N]
- Authentication status: SPF [set up Y/N], DKIM [set up Y/N], DMARC policy [none/quarantine/reject], BIMI [Y/N]

LIST HEALTH DATA (pull from your ESP):
- Total active list size: [X]
- List growth rate (MoM): [X%]
- List acquisition sources and % breakdown:
  * Organic opt-in (website forms): [X%]
  * Content downloads / lead magnets: [X%]
  * Events / trade shows: [X%]
  * Cold outbound import: [X%]
  * Co-marketing / partner lists: [X%]
  * Purchased/rented lists: [X%]
- Average list age (oldest contacts): [months/years]
- Double opt-in used: [Y/N]
- Last major list clean performed: [date / never]

CURRENT PERFORMANCE METRICS (trailing 90 days):
- Avg open rate: [X%] | Click rate: [X%] | Click-to-open rate: [X%]
- Hard bounce rate: [X%] | Soft bounce rate: [X%]
- Spam complaint rate: [X%] (alert threshold: 0.08% for Google, 0.3% for others)
- Unsubscribe rate: [X%]
- Inbox placement rate (if known via tool like GlockApps/250ok): [X%]
- Blacklist status: [clean / listed on: specify RBLs]
- Google Postmaster Tools domain reputation: [High/Medium/Low/Bad]
- Recent deliverability incidents: [describe any sudden drops, Gmail tab shifts, etc.]

SEGMENTATION & SENDING BEHAVIOR:
- Engagement segments currently in use: [describe or "none"]
- Send frequency by segment: [X emails/week to active, Y to cold]
- Suppression rules currently enforced: [describe or "none"]
- Transactional vs. marketing email separation: [Y/N]
- Time zone sending optimization: [Y/N]

BUSINESS CONSTRAINTS:
- Upcoming high-volume campaigns (e.g., product launch, seasonal): [date + expected volume]
- CRM/MAP integrations affecting list sync: [Salesforce / HubSpot / Marketo / etc.]
- Compliance requirements: [CAN-SPAM only / GDPR / CASL / all]
- Budget for deliverability tools: [none / <$500/mo / $500-2000/mo / unlimited]

OBJECTIVE: Produce a comprehensive Email Deliverability Remediation & Optimization System that I can hand to my marketing ops team and execute immediately.

DELIVERABLES:

### 1. DELIVERABILITY AUDIT SCORECARD
Score each dimension 1-10 with status indicators and rationale:
| Dimension | Score | Status | Key Issues | Priority Fix |
|---|---|---|---|---|
| Sender Reputation (domain + IP) | | | | |
| List Hygiene & Quality | | | | |
| Authentication (SPF/DKIM/DMARC) | | | | |
| Engagement Segmentation | | | | |
| Content & Spam Signal Risk | | | | |
| Sending Cadence & Volume | | | | |
| Compliance & Consent | | | | |
| **Overall Program Score** | | | | |

### 2. LIST SEGMENTATION ARCHITECTURE
Design a 5-tier engagement segmentation model:
- Tier 1 (Champions): Definition + recommended send frequency + content type
- Tier 2 (Actives): Definition + recommended send frequency + content type
- Tier 3 (At-Risk): Definition + re-engagement trigger criteria
- Tier 4 (Dormant): Definition + win-back campaign eligibility window
- Tier 5 (Sunset): Definition + suppression execution criteria

Include the exact query/filter logic to build each segment in [their ESP].

### 3. SUPPRESSION & SUNSET POLICY (AUTOMATED RULES)
Design suppression automation rules using behavioral signals:
- Hard bounces: [auto-suppress after X bounces — provide exact rule]
- Soft bounces: [suppress after X bounces in Y days — provide exact rule]
- Spam complaints: [suppress immediately + retroactive lookback rule]
- Engagement-based: [suppress contacts meeting X criteria — be specific]
- Re-permission required: [contacts requiring explicit re-consent]
- Sunset criteria: [final suppression rules for contacts completing dormant cycle]

Output as an automation workflow spec that can be built in HubSpot, Marketo, or Klaviyo.

### 4. RE-ENGAGEMENT CAMPAIGN SYSTEM (3-STAGE WIN-BACK)
For Tier 3 (At-Risk) and Tier 4 (Dormant) contacts:

**Email 1 — "We Miss You" (Day 0)**
- Subject line options (3 variants for A/B test, using curiosity + personalization)
- Preview text
- Email body framework (150-200 words max — urgency, value reminder, single CTA)
- CTA: [specific action]
- Success metric: 15% open rate or click on "Stay Subscribed"

**Email 2 — Last Chance + Incentive (Day 7, non-openers only)**
- Subject line options (scarcity + direct)
- Incentive framework (what to offer for different business models)
- Body framework
- CTA: [specific action]

**Email 3 — "This is Goodbye" (Day 14, non-openers only)**
- Subject line: curiosity-driven final message
- Body: ultra-short (3-4 sentences), permission reminder, one-click resubscribe
- Post-send action: auto-suppress non-engagers within 48 hours

### 5. DOMAIN WARM-UP / REPUTATION REPAIR PLAN
If reputation score is Medium/Low/Bad, provide:
- Week 1: Daily send caps by segment (start with Champions only)
- Week 2: Expand to Actives tier, volume ramp %
- Week 3: Include At-Risk with re-engagement sequence
- Week 4: Full program re-launch criteria and go/no-go checklist
- Monitoring checkpoints: What to look for before advancing each week

### 6. AUTHENTICATION & INFRASTRUCTURE HARDENING CHECKLIST
- [ ] SPF record: exact syntax check + recommended record
- [ ] DKIM: key rotation schedule + selector naming convention
- [ ] DMARC: recommended policy progression (none → quarantine → reject) + reporting inbox setup
- [ ] BIMI: requirements check + SVG logo spec
- [ ] Reverse DNS (PTR records): verification steps
- [ ] Subdomain strategy: separate sending domains for transactional vs. marketing
- [ ] Feedback loop (FBL) registration: ISP FBL list + registration links
- [ ] List-Unsubscribe header: one-click implementation spec (RFC 8058)

### 7. CONTENT SPAM SIGNAL AUDIT
Analyze common spam triggers relevant to [industry] and provide:
- Words/phrases to avoid (with alternatives)
- HTML-to-text ratio recommendation
- Image-heavy email risk mitigation
- Link count and domain diversity guidelines
- Personalization tokens that improve engagement (with ESP merge field syntax)

### 8. WEEKLY DELIVERABILITY MONITORING PROTOCOL
| Metric | Tool | Healthy Range | Alert Threshold | Action if Threshold Breached |
|---|---|---|---|---|
| Inbox placement rate | GlockApps / 250ok | >92% | <85% | |
| Domain reputation (Gmail) | Google Postmaster | High | Medium | |
| Spam complaint rate | ESP + FBL | <0.08% | >0.1% | |
| Hard bounce rate | ESP | <0.5% | >1% | |
| Blacklist status | MXToolbox | Clean | Any listing | |
| Engagement rate (opens+clicks) | ESP | >15% combined | <10% | |

### 9. 90-DAY ROADMAP & IMPLEMENTATION TIMELINE
Gantt-style breakdown:
- Days 1-7: [specific tasks + owners]
- Days 8-21: [specific tasks + owners]  
- Days 22-45: [specific tasks + owners]
- Days 46-90: [specific tasks + owners]
- Success KPIs at Day 90: [specific measurable outcomes]

CONSTRAINTS:
- All recommendations must be executable within [their ESP] without custom engineering
- Provide exact filter/query logic, not vague guidance
- Flag if any recommendation requires 3rd-party tool investment and specify cost
- Every automation rule must include a rollback/exception protocol
- No recommendations that require pausing the entire email program unless critical

FORMAT: Use structured tables, numbered checklists, and clear headers. Write as if handing this to a marketing ops manager on their first day — no jargon without explanation.

## Example Input/Output

**Example Input (Quick Version):**
- ESP: HubSpot Marketing Hub
- List size: 42,000 contacts
- Monthly send volume: 180,000 emails/month
- Current avg open rate: 14% (industry benchmark: 22%)
- Hard bounce rate: 3.8% (🔴 critical)
- Soft bounce rate: 1.1%
- Spam complaint rate: 0.18% (🔴 above Google's 0.08% threshold)
- Sending domain: marketing.nexoflow.io
- Last list import: 8 months ago from a SaaStr conference badge scan (4,200 contacts)
- Biggest concern: Google recently moved us from Primary to Promotions tab; Gmail open rates dropped 40%

**Example Output (Condensed):**

**Deliverability Health Score: 4.2/10 — Critical Intervention Required**

| Dimension | Score | Status | Critical Issue |
|---|---|---|---|
| Sender Reputation | 3/10 | 🔴 | 3.8% hard bounce is destroying domain reputation |
| List Hygiene | 3/10 | 🔴 | Conference import added ~4,200 unverified contacts |
| Authentication | 6/10 | 🟡 | DMARC at "none" — upgrade to quarantine immediately |
| Engagement Segmentation | 2/10 | 🔴 | No suppression tiers — sending to full list |
| Content | 6/10 | 🟡 | Promotions tab signals: too many images, weak text ratio |
| Sending Volume | 5/10 | 🟡 | Frequency fine but list quality dragging reputation |

**Week 1 Emergency Actions:**
1. **TODAY**: Suppress all 3.8% hard bounces (≈1,596 contacts) — HubSpot filter: `Email hard bounce count is greater than 0`
2. **TODAY**: Isolate all SaaStr conference imports into a quarantine segment — do not send until validated
3. **Day 2**: Register for Google Postmaster Tools at postmaster.google.com — monitor domain reputation daily
4. **Day 3**: Upgrade DMARC from `p=none` to `p=quarantine; pct=10` to start building reputation signal
5. **Day 5**: Run full list through NeverBounce or ZeroBounce — expected to remove 8-15% of list as invalid/risky
6. **Day 7**: Pause all sends to contacts with 0 opens + 0 clicks in last 120 days (est. 14,000 contacts)

**Re-Engagement Email 1 (for 14,000 dormant contacts):**

*Subject A:* Quick question about your [Company] emails
*Subject B:* Still want to hear from us? (one click to confirm)
*Preview text:* We've noticed you haven't opened in a while — no pressure either way.

*Body:*
Hey [First Name],

We've been sending you [Company] emails, but haven't heard from you in a while. No hard feelings — inboxes get wild.

If our content is still useful to you, click the button below and we'll keep you on the list. If not, we'll clean things up automatically in 10 days.

[YES — KEEP ME SUBSCRIBED] [No thanks, remove me]

Talk soon,
[Sender Name]
[Company]

*P.S. — If you stay subscribed, we'll send you our new [relevant resource] next week.*

**90-Day Target KPIs:**
- Hard bounce rate: <0.5% (from 3.8%)
- Spam complaint rate: <0.05% (from 0.18%)
- Gmail domain reputation: High (from Low)
- Open rate: >21% (from 14%)
- Inbox placement rate: >93%
- Engaged list size (post-cleanup): ~28,000 (vs. 42,000 current — smaller, dramatically more valuable)

## Success Metrics
- **Hard bounce rate** drops below 0.5% within 30 days
- **Spam complaint rate** below 0.08% within 21 days
- **Google Postmaster domain reputation** advances from Low → Medium → High within 60 days
- **Inbox placement rate** above 92% across Gmail, Outlook, Yahoo within 60 days
- **Open rate** recovers to within 80% of industry benchmark within 90 days
- **Engaged list size** is correctly segmented with suppression automation live within 14 days
- **Authentication** (SPF/DKIM/DMARC) fully configured and passing within 7 days

## Related Prompts
- [`../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Behavioral-Email-Trigger-Lifecycle-Automation-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Behavioral-Email-Trigger-Lifecycle-Automation-Engine.md) — Build the behavioral trigger system that feeds your healthy, segmented list
- [`../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Email-Personalization-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Email-Personalization-Engine.md) — Once deliverability is fixed, maximize engagement with deep personalization
- [`../../05_Analytics-&-Marketing-Operations/Campaign-Performance-Analysis/Marketing-Attribution-ROI-Engine.md`](../../05_Analytics-&-Marketing-Operations/Campaign-Performance-Analysis/Marketing-Attribution-ROI-Engine.md) — Attribute revenue impact of your recovered email channel
- [`../../05_Analytics-&-Marketing-Operations/MarTech-Stack-Optimization/Marketing-Automation-Workflow-Architecture-Engine.md`](../../05_Analytics-&-Marketing-Operations/MarTech-Stack-Optimization/Marketing-Automation-Workflow-Architecture-Engine.md) — Architect the automation workflows that enforce suppression rules at scale

## Integration Tips

**HubSpot:**
- Use Active Lists with enrollment triggers for each suppression tier (hard bounces, spam complainers, dormant)
- Set up Workflows: `Contact Property → Email Hard Bounce → Set Contact Status = Suppressed → Remove from all marketing lists`
- Connect Google Postmaster Tools data manually via weekly export into a HubSpot custom property dashboard

**Salesforce Marketing Cloud / Pardot:**
- Use Automation Studio to run nightly suppression list syncs
- Create separate Publication Lists for Tier 1-5 engagement segments
- Use Einstein Engagement Scoring to automate tier assignment

**Klaviyo:**
- Use built-in Deliverability Hub to monitor key metrics
- Create Suppression Segments using Klaviyo's predictive churn scoring
- Set Flow Filters to automatically exclude suppressed profiles from all active flows

**Outreach / Salesloft (SDR email):**
- Sync suppression list to exclude from all sequences via CRM integration
- Flag bounced/complained contacts in Salesforce with `Email_Status = Do_Not_Contact`

**Zapier Automation:**
- Trigger: ESP webhook fires on hard bounce event → Zap → Update CRM contact status → Add to Google Sheet suppression log → Slack alert to marketing ops

**Deliverability Tools to Integrate:**
- **NeverBounce** or **ZeroBounce**: API-connect to ESP for real-time validation on new signups
- **Google Postmaster Tools**: Daily monitoring; export weekly data to Data Studio dashboard
- **GlockApps** or **Mail-Tester**: Monthly inbox placement tests before major campaigns
- **MXToolbox**: Set up blacklist monitoring alerts (email notification if listed)

## Troubleshooting

**Problem: We cleaned the list but bounce rates are still high**
Fix: Bounce rate spikes are often caused by newly imported contacts — check the source of recent additions. Also check if your ESP is re-trying soft bounces as hard bounces. Review your ESP's bounce categorization logic and ensure you're using separate suppression rules for hard vs. soft bounces. Request a deliverability audit from your ESP's support team — many provide free audits for Enterprise accounts.

**Problem: Open rates improved but we're still landing in Gmail Promotions tab**
Fix: Gmail's Promotions tab placement is driven by email structure signals, not just reputation. Reduce image-to-text ratio (aim for 60% text, 40% images), remove excessive links (keep under 5 per email), add personalization tokens (First Name, company name), and use a plain-text style template for your most important campaigns. Also enable BIMI — Gmail gives preference-inbox treatment to authenticated senders with verified brand logos.

**Problem: Re-engagement campaign got terrible engagement — now our reputation is worse**
Fix: You sent the re-engagement campaign to too broad an audience too quickly. Pause immediately. Suppress everyone who didn't open either of the first two re-engagement emails. Rebuild domain reputation by sending exclusively to your most engaged contacts (Tier 1 Champions) for the next 2 weeks before attempting any additional re-engagement. In the future, always test re-engagement campaigns with a 5% sample of dormant contacts before full send.

## Version History
- v1.0: Initial creation (auto-generated)
