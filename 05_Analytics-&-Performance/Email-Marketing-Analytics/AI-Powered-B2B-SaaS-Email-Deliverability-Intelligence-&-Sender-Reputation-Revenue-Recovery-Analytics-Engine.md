# AI-Powered B2B SaaS Email Deliverability Intelligence & Sender Reputation Revenue Recovery Analytics Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** email, analytics, deliverability, b2b, revenue-recovery, automation

## Overview
Diagnose email deliverability collapse, quantify its revenue impact, and produce a prioritized sender reputation recovery roadmap — fully automatable by an AI agent using data from your ESP, CRM, and pipeline records. Use this when pipeline velocity drops unexpectedly, email engagement metrics are declining, or you suspect deliverability issues are masking actual campaign performance.

## Quick Copy-Paste Version

You are a B2B email deliverability analyst with expertise in sender reputation systems, MTA infrastructure, and revenue impact modeling.

I'm running a B2B SaaS email program and need a complete deliverability intelligence audit. Here's my current data:

ESP/Sending platform: [HubSpot / Outreach / Salesloft / Apollo / other]
Monthly email volume: [number] emails/month across [number] sending domains
Current metrics:
- Average bounce rate: [X]%
- Average spam complaint rate: [X]%
- Average inbox placement rate: [X]% (if known)
- Open rate trend (last 90 days): [increasing / declining / flat]
- Unsubscribe rate: [X]%
- Google Postmaster Domain Reputation: [high / medium / low / bad / unknown]
- Microsoft SNDS IP Reputation: [green / yellow / red / unknown]

Email program breakdown:
- Outbound cold email volume: [X]/month
- Marketing nurture/newsletter volume: [X]/month
- Transactional/lifecycle email volume: [X]/month
- AI SDR sequences: [yes/no, volume if yes]

Pipeline impact context:
- Pipeline generated from email this quarter vs. last quarter: [$X vs. $Y]
- SQL to email-influenced deal ratio change: [X%]
- Average email-sourced deal size: [$X]

Please provide:
1. Deliverability Health Score (0-100) based on my metrics with benchmarks for B2B SaaS at my volume tier
2. Root cause diagnosis — identify which of these is most likely causing issues: domain warming failure, IP reputation, list hygiene, sending frequency, content triggers, authentication gaps (SPF/DKIM/DMARC/BIMI), or engagement signal decay
3. Revenue impact quantification — calculate estimated pipeline at risk and revenue recovery potential if deliverability is restored to healthy benchmarks
4. 30/60/90-day recovery roadmap with specific actions, owners, and success metrics
5. Monitoring dashboard spec — what metrics to track weekly and what thresholds trigger escalation
6. Domain segmentation strategy — how to separate cold outbound, marketing, and transactional email across domains to protect sender reputation going forward

## Advanced Customizable Version

ROLE: You are a senior email deliverability strategist and revenue analytics architect specializing in B2B SaaS organizations sending high-volume mixed email programs (outbound SDR sequences, marketing nurture, lifecycle, and transactional). You understand MTA infrastructure, ISP feedback loops, Google Postmaster Tools, Microsoft SNDS, bounce classification systems, and the causal relationship between sender reputation and B2B pipeline generation.

CONTEXT:
Organization: [Company name]
Industry: [B2B SaaS vertical, e.g., HR Tech, FinTech, CyberSecurity]
ARR: [$X million]
Team size (email-impacted): [Marketing: X, Sales/SDR: X]
ICP email domains: [Primarily Gmail / Microsoft 365 / Mixed enterprise]
Sending infrastructure: [ESP: X, Outbound tool: X, Transactional: X]
Number of sending domains: [X domains — list them if possible]
IP type: [Shared / Dedicated / Pool]

DELIVERABILITY METRICS (provide all available):
Authentication:
- SPF configured: [yes/no/partial]
- DKIM configured: [yes/no, key size]
- DMARC policy: [none/quarantine/reject, % enforcement]
- BIMI implemented: [yes/no]
- MTA-STS configured: [yes/no]

Bounce analysis (last 30 days):
- Hard bounce rate: [X]%
- Soft bounce rate: [X]%
- Top bounce categories: [mailbox full / domain not found / policy rejection / reputation block]
- Bounce rate trend (MoM): [increasing X% / declining X% / flat]

Spam/complaint signals:
- Spam complaint rate (ESP-reported): [X]%
- Google Postmaster complaint rate: [X]%
- FBL (Feedback Loop) complaints: [X/month]
- Spam trap hits: [known / suspected / unknown]

Engagement metrics (last 90 days trend):
- Open rate: [Month 1: X%, Month 2: X%, Month 3: X%]
- Click rate: [Month 1: X%, Month 2: X%, Month 3: X%]
- Reply rate (outbound): [X]%
- Unsubscribe rate: [X]%
- List growth vs. list decay rate: [+X% / -X% net]

Infrastructure signals:
- Google Postmaster Domain Reputation: [high / medium / low / bad]
- Google Postmaster IP Reputation: [high / medium / low / bad]
- Microsoft SNDS IP reputation: [green / yellow / red]
- Blacklist status: [clean / listed on: X]
- Inbox placement rate (Litmus/Email on Acid/GlockApps): [X]%

REVENUE/PIPELINE CONTEXT:
- Email-attributed pipeline this quarter: [$X]
- Email-attributed pipeline same quarter last year: [$X]
- Email-influenced (multi-touch) pipeline: [$X]
- Average days from email engagement to SQL: [X days]
- Email-sourced ACV: [$X]
- Deals in pipeline currently tied to email-active contacts: [X deals, $X pipeline]
- SDR email sequences active: [X sequences, X contacts/month]
- Marketing nurture sequences active: [X workflows, X contacts]

LIST HYGIENE STATUS:
- Last list hygiene / validation run: [date / never]
- Estimated invalid email % in active database: [X% / unknown]
- Re-engagement / sunset policy: [exists / none]
- Contact database age: [average record age X months]
- Data sources feeding email lists: [form fills / data vendors / ZoomInfo / Apollo / other]

DELIVERABILITY HISTORY:
- Previous deliverability incidents: [describe any known issues, blacklistings, rate limits]
- Changes made in last 6 months: [new sending domains / IP changes / volume increases / new tools]
- AI SDR deployment: [deployed X months ago / not deployed]

---

ANALYSIS FRAMEWORK — produce the following outputs:

## 1. DELIVERABILITY HEALTH SCORECARD
Score each dimension 0-100 with benchmark comparison:
- Authentication & Technical Infrastructure (weight: 20%)
- List Quality & Hygiene (weight: 25%)
- Engagement Signal Health (weight: 25%)
- Sending Behavior & Volume Management (weight: 15%)
- ISP Reputation (Google/Microsoft) (weight: 15%)

Overall Deliverability Health Score: [0-100]
Risk tier: [Critical / At Risk / Needs Improvement / Healthy / Excellent]
Benchmark: B2B SaaS companies at [volume tier] average score: [X]

## 2. ROOT CAUSE DIAGNOSIS
Apply Bayesian diagnostic logic to identify primary and contributing causes:

Primary cause (most likely, weighted by evidence): [cause]
Supporting evidence from provided metrics: [specific data points]
Confidence level: [High / Medium / Low]

Contributing factors (ranked by impact):
1. [Factor]: [Evidence] → Estimated contribution to deliverability degradation: [X]%
2. [Factor]: [Evidence] → [X]%
3. [Factor]: [Evidence] → [X]%

Causal chain narrative: [2-3 sentences explaining how the root cause led to current state]

## 3. REVENUE IMPACT QUANTIFICATION

Current State Modeling:
- Estimated true inbox placement rate: [X]% (vs. reported open rate)
- Contacts effectively unreachable due to deliverability: [X] (X% of active list)
- Pipeline generation gap vs. healthy-deliverability baseline: [$X/quarter]
- Deals at risk in current pipeline due to ongoing deliverability issues: [X deals, $X]

Recovery Value Modeling:
- If deliverability restored to [benchmark]%, estimated incremental pipeline: [$X/quarter]
- Time to value from recovery actions: [X weeks to first measurable improvement]
- 12-month cumulative revenue recovery potential: [$X - $X range]
- ROI on deliverability remediation investment (estimated): [X:1]

## 4. 90-DAY RECOVERY ROADMAP

### Week 1-2: Emergency Triage (Stop the Bleeding)
- [ ] Action: [Specific action]
  Owner: [Marketing Ops / Email Admin / SDR Ops]
  Tool: [Specific tool]
  Success metric: [Measurable outcome]
  Estimated timeline: [X days]

[Continue for all Week 1-2 actions]

### Week 3-4: Infrastructure Hardening
[Actions, owners, tools, metrics]

### Month 2: List Remediation & Engagement Reset
[Actions, owners, tools, metrics]

### Month 3: Volume Rebuild & Domain Warming
[Actions, owners, tools, metrics]

## 5. DOMAIN SEGMENTATION ARCHITECTURE
Design optimal domain/subdomain strategy:

Recommended domain structure:
- [domain1.com] → Use for: [Marketing nurture, newsletters] | Volume cap: [X/day] | Warming status: [established]
- [outbound.domain2.com] → Use for: [Cold outbound, AI SDR] | Volume cap: [X/day] | Separate IP: [yes]
- [mail.domain3.com] → Use for: [Transactional / product] | Volume cap: [X/day]

Cross-contamination prevention rules:
1. [Rule]
2. [Rule]
3. [Rule]

## 6. WEEKLY MONITORING DASHBOARD SPEC

Metrics to track weekly (with alert thresholds):
| Metric | Healthy | Warning | Critical | Data Source |
|--------|---------|---------|----------|-------------|
| Hard bounce rate | <0.5% | 0.5-1% | >1% | ESP |
| Spam complaint rate | <0.08% | 0.08-0.1% | >0.1% | Google Postmaster |
| Google Postmaster domain rep | High | Medium | Low/Bad | Google Postmaster |
| Inbox placement rate | >90% | 80-90% | <80% | Litmus/GlockApps |
| Open rate (7-day rolling) | >benchmark | -20% vs benchmark | -40% vs benchmark | ESP |
| Blacklist hits | 0 | 1 major | 2+ | MXToolbox |

Escalation protocol:
- Warning threshold hit → [Action]
- Critical threshold hit → [Action]
- Blacklist detected → [Action within X hours]

## 7. PREVENTION PLAYBOOK
Ongoing policies to prevent recurrence:
- List acceptance criteria for new data sources
- AI SDR volume governance rules
- Sunset/suppression policy (engagement-based)
- Quarterly deliverability audit schedule
- New domain warming SOP

## Example Input/Output

**Input Example:**

ESP: HubSpot (marketing) + Outreach (outbound SDR)
Monthly email volume: 280,000 emails/month across 3 sending domains
Current metrics:
- Average bounce rate: 3.2%
- Average spam complaint rate: 0.18%
- Average inbox placement rate: 61%
- Open rate trend (last 90 days): declining (28% → 19% → 11%)
- Unsubscribe rate: 0.6%
- Google Postmaster Domain Reputation: Low (for primary marketing domain)
- Microsoft SNDS IP Reputation: Yellow

Email program:
- Outbound cold email volume: 180,000/month (AI SDR deployed 4 months ago)
- Marketing nurture/newsletter volume: 80,000/month
- Transactional: 20,000/month
- AI SDR sequences: Yes, 180k/month

Pipeline impact:
- Email-attributed pipeline this quarter: $1.2M vs. $2.4M last quarter
- SQL to email-influenced deal ratio: declined 35%
- Average email-sourced deal size: $48,000

**Output Example (abbreviated):**

**Deliverability Health Score: 32/100 — CRITICAL**

Benchmark: B2B SaaS companies at 280k/month average score 71/100. You are 39 points below peer benchmark.

**Root Cause Diagnosis — Primary: AI SDR Volume Shock**

When you deployed AI SDR sending 180,000 cold emails/month 4 months ago, you co-mingled that sending with your established marketing domain infrastructure. This created an engagement ratio collapse: 64% of your total volume is now going to cold prospects who have never heard of you, with expected low engagement. ISPs (particularly Google) interpreted this as reputation-damaging behavior on your primary marketing domain.

Causal chain: AI SDR volume spike → engagement rate dilution → Google Postmaster demotes domain reputation to "Low" → inbox placement drops from ~88% to 61% → open rates collapse → existing nurture contacts who WANT your emails stop receiving them → pipeline dries up.

**Revenue Impact:**
- Pipeline at risk from deliverability degradation: $1.2M/quarter (your pipeline gap)
- Contacts effectively unreachable: ~68,000 of your 110,000 active marketing contacts
- 12-month recovery value if deliverability restored: $3.8M - $4.6M cumulative
- ROI on remediation: ~22:1 on estimated $50,000 in tool/labor costs

**Week 1-2 Emergency Actions:**
1. Immediately migrate all AI SDR outbound to separate dedicated domain (outbound.yourdomain.com) with dedicated IP pool — prevents further contamination of marketing domain. Owner: Email/RevOps. Tool: Outreach domain settings + email host. Timeline: 72 hours.
2. Pause all cold outbound from primary marketing domain effective immediately. Owner: SDR Manager. Timeline: 24 hours.
3. Run emergency list validation on your 110k marketing database via ZeroBounce or NeverBounce. Suppress all invalid, risky, catch-all addresses. Owner: Marketing Ops. Timeline: 5 business days.
4. Reduce HubSpot daily send volume by 60% while domain reputation recovers. Send only to highest-engagement cohort (opened/clicked in last 90 days). Timeline: Immediate.

**30-Day Outlook:** Google Postmaster domain reputation typically takes 45-90 days to recover from "Low" to "High" with consistent clean sending behavior. You should see inbox placement begin improving (61% → 75%) within 30 days of separating AI SDR sending.

## Success Metrics

**Deliverability recovery metrics (measure weekly):**
- Google Postmaster domain reputation returns to "High" within 60-90 days
- Inbox placement rate ≥90% (up from current baseline)
- Hard bounce rate ≤0.5%
- Spam complaint rate ≤0.08%

**Revenue metrics (measure monthly):**
- Email-attributed pipeline returning to prior-quarter baseline within 90 days
- Email-influenced SQL rate recovering by ≥25% within 60 days
- Open rates recovering to ≥20% within 45 days of infrastructure remediation

**Program health metrics (ongoing):**
- New domain/IP warming completed within 30 days
- List validation hygiene <1% invalid addresses in active database
- Weekly monitoring dashboard showing all metrics in "Healthy" or "Warning" tiers (no "Critical")

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Email-Deliverability-&-List-Health-Optimization-Engine.md`
- `../../05_Analytics-&-Performance/Email-Marketing-Analytics/AI-Powered-B2B-SaaS-Email-Marketing-Program-Analytics-&-Revenue-Attribution-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/AI-Powered-B2B-Autonomous-AI-SDR-Program-Architecture-&-Outbound-Pipeline-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Demand-Generation-Program-Analytics/AI-Powered-B2B-SaaS-AI-SDR-Program-Analytics-&-Outbound-Revenue-Contribution-Intelligence-Engine.md`

## Integration Tips

**HubSpot:**
- Pull email performance data from HubSpot Marketing Email Analytics → export bounce, complaint, and engagement cohort data by month → paste into the Advanced prompt's metrics section
- Connect HubSpot to Google Postmaster Tools for domain reputation auto-reporting
- Use HubSpot's email health dashboard (Settings → Email → Deliverability) as your weekly monitoring source

**Outreach / Salesloft / Apollo:**
- Export sequence-level bounce and reply data per domain from your outbound tool's reporting section
- Use Outreach's deliverability score or Salesloft's email health report as input to the audit prompt

**Google Postmaster Tools (free):**
- Connect your sending domain at postmaster.google.com
- Export Domain Reputation and Spam Rate data as CSV → paste into prompt context
- Set up weekly Google Postmaster monitoring — this is the most authoritative signal for deliverability health

**ZeroBounce / NeverBounce / Clearout:**
- Run your full active email database through validation before running the recovery prompt
- Feed validation results (% invalid, % risky, % catch-all) into the List Hygiene Status section
- Set up real-time validation API on all form captures to prevent future list quality decay

**Salesforce / CRM:**
- Pull "email-influenced pipeline" using campaign influence reports — compare current quarter vs. prior 4 quarters to calculate revenue impact baseline
- Tag contacts by email engagement tier (active/lapsed/inactive) for segmentation-based sending strategy

**Zapier / Make.com:**
- Build automated weekly deliverability report: Pull Google Postmaster API + ESP bounce data → run through this prompt → post summary to Slack #marketing-ops channel

## Troubleshooting

**Problem: Google Postmaster shows "Low" domain reputation but my ESP reports look fine (low bounce, normal open rates)**
Solution: This is the most dangerous pattern — it means Gmail is silently filtering your emails to spam without bouncing them. Your ESP only knows about emails it successfully handed off to Gmail's MTA. The fix: use an inbox placement testing tool (Litmus Email Guardian, GlockApps, or MxToolbox Email Health) to measure actual inbox vs. spam placement, and trust Postmaster over ESP metrics.

**Problem: After separating sending domains and running list hygiene, metrics still aren't recovering after 30 days**
Solution: Domain reputation recovery is a slow signal that requires consistent clean-sending behavior. Check: (1) Are you still co-mingling any volume on the damaged domain? Even small volumes of problematic sending reset the recovery clock. (2) Are you warming the new domain correctly — starting at ≤200 emails/day and doubling weekly? (3) Is your content triggering spam filters? Run your emails through Litmus Spam Filter Testing to identify content-level issues independent of reputation.

**Problem: The revenue impact calculation shows a huge number but leadership doesn't believe email deliverability caused the pipeline decline**
Solution: Build a causal correlation model using the evidence timeline: export pipeline by week for the last 6 months → overlay with email engagement rate by week → plot Google Postmaster reputation changes on the same timeline. The correlation between reputation decline and pipeline decline is typically visible within 4-6 weeks. Additionally, run a holdout test: restore deliverability for one market segment while keeping another at current state, and measure pipeline contribution difference over 45 days.

## Version History
- v1.0: Initial creation (auto-generated)
