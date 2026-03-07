# Marketing Anomaly Detection & Performance Alerting Engine - Real-Time KPI Deviation Diagnosis & Escalation System

**Difficulty:** Advanced | **Time:** 20 min | **Tags:** analytics, anomaly-detection, kpi, alerting, monitoring, marketing-ops, automation

## Overview
Detect statistically significant deviations in your marketing KPIs before they become crises, identify root causes with precision, and generate escalation-ready alert narratives in seconds. Use this when metrics have moved unexpectedly -- traffic drops, conversion spikes, CPL surges, email deliverability crashes -- and you need to know why and what to do in the next 30 minutes.

## Quick Copy-Paste Version

You are a senior marketing analytics engineer specializing in anomaly detection and root cause analysis. I am seeing an unexpected movement in my marketing metrics and need an immediate diagnostic.

**Anomaly Observed:**
- Metric: [e.g., organic sessions, demo request CVR, email open rate, CPA, MQL volume]
- Current value: [X]
- Expected value (prior 7-day average or same period last week/month): [X]
- % deviation: [X]% [above / below] expected
- Time window: [When did the deviation start? e.g., "Started 2 days ago", "Dropped overnight Nov 14"]

**Business Context:**
- Company: [Company name and business model]
- Channel/funnel stage affected: [e.g., Top-of-funnel organic, mid-funnel email nurture, bottom-funnel demo page]
- Recent changes (last 14 days): [Any deployments, campaign launches, landing page edits, pricing changes, team changes]
- Known external events: [Product launches by competitors, industry events, algorithm updates, seasonality]

**Available Data (paste what you have):**
[Paste raw numbers: daily or weekly time series, broken down by channel or segment if possible]

Analyze this anomaly and produce:
1. Anomaly severity classification (P1 Critical / P2 High / P3 Medium / P4 Low) with justification
2. Top 3 most likely root causes ranked by probability, with evidence from the data
3. Diagnostic checklist: the 5 specific things I should check in the next 30 minutes (with exact tool/location for each)
4. Immediate containment action (what to do right now if this is a revenue-impacting issue)
5. Escalation narrative: a 3-sentence Slack message I can send to my CMO right now
6. Recovery timeline estimate: when should this metric return to normal range if root cause is [most likely cause]

## Advanced Customizable Version

ROLE: You are a VP-level Marketing Analytics engineer with 12+ years of experience building anomaly detection systems for B2B SaaS, D2C, and enterprise marketing teams. You apply statistical process control, causal inference, and marketing funnel expertise to distinguish signal from noise and identify actionable root causes within minutes of a metric deviation.

BUSINESS CONTEXT:
Company: [Company Name]
Business model: [B2B SaaS / B2C e-commerce / D2C / Marketplace / PLG]
Monthly revenue: $[X] | MRR/ARR: $[X]
Primary conversion events: [e.g., Free trial signup, demo request, purchase, MQL]
Marketing channels active: [SEO / Paid Search / Paid Social / Email / Outbound / Events / PLG]
Analytics stack: [GA4 / Mixpanel / Amplitude / HubSpot / Salesforce / Looker / custom BI]
Alert recipient: [CMO / Head of Demand Gen / Marketing Ops / Full marketing team]

ANOMALY INVENTORY (fill in all metrics showing deviation):

METRIC 1:
Name: [metric name]
Current period value: [X] | Period: [last 24h / 7 days / month-to-date]
Baseline value: [X] | Baseline period: [prior 7-day avg / same week last year / rolling 30-day avg]
% deviation: [X]% | Direction: [above / below]
First detected: [date/time]
Segment breakdown available: [Yes -- by channel / device / geo / campaign | No]

METRIC 2 (add as many as needed):
[Repeat above structure]

RECENT CHANGES LOG (last 14 days -- include everything, even seemingly unrelated changes):
- [Date]: [Change description -- e.g., "Nov 12: Deployed homepage redesign", "Nov 10: Launched Google Ads campaign for Q4 push", "Nov 8: Updated email unsubscribe flow"]

EXTERNAL CONTEXT:
- Seasonality: [Is this a historically high/low-traffic period? YoY comparison?]
- Competitor activity: [Any known competitor launches, pricing changes, campaigns?]
- Platform/algorithm changes: [Recent Google core update? Meta algorithm shift? Email provider policy change?]
- Macroeconomic signals: [Industry headwinds, economic events affecting buyer behavior?]

HYPOTHESIS BANK (optional -- list any internal theories already proposed):
- [Hypothesis 1]: [e.g., "The homepage redesign broke the demo CTA button on mobile"]
- [Hypothesis 2]: [e.g., "Google's November core update penalized our blog"]

ANALYSIS FRAMEWORK:

1. ANOMALY CLASSIFICATION & SEVERITY SCORING

Statistical significance check:
- Is the deviation > 2 standard deviations from the rolling 30-day mean? If yes: statistically significant
- Is the deviation > 3 standard deviations? If yes: extreme outlier -- treat as P1 until proven otherwise
- Is the deviation isolated to a single day or sustained across 3+ days? Sustained = higher severity
- Is it isolated to one segment (channel/device/geo) or system-wide? Isolated = more likely operational cause; system-wide = more likely external or structural

Severity classification:
- P1 Critical: Revenue-impacting, sustained 3+ days, deviation > 30%, or conversion pipeline at risk -- requires immediate executive escalation and mitigation
- P2 High: Significant efficiency or volume impact, deviation 15-30%, isolated to key channels -- requires same-day diagnosis and action plan
- P3 Medium: Notable deviation 8-15%, early-stage or single-day signal -- requires monitoring and hypothesis testing within 48 hours
- P4 Low: Deviation < 8%, within historical volatility range -- log and monitor, no immediate action required

Business impact quantification:
- Calculate revenue or pipeline at risk: (Expected conversions - Actual conversions) x Average deal value / conversion rate
- Express in dollars: "This deviation represents an estimated $[X] in at-risk pipeline over 30 days if the trend continues"

2. ROOT CAUSE HYPOTHESIS RANKING

For each anomaly, generate a ranked list of hypotheses using the MECE (Mutually Exclusive, Collectively Exhaustive) framework across four root cause categories:

TECHNICAL (site/tracking/infrastructure):
- Tracking implementation errors (tag fires, GA4 configuration changes, UTM parameter breakage)
- Site performance degradation (Core Web Vitals, page load speed, mobile rendering)
- Form/CTA functionality (broken submit buttons, validation errors, redirect failures)
- CRM/MAP integration failures (HubSpot form-to-CRM sync, lead deduplication errors)

ALGORITHMIC/PLATFORM (external system changes):
- Search engine algorithm update (Google core, helpful content, spam updates)
- Paid platform algorithm shift (Meta delivery algorithm, Google Smart Bidding behavior change)
- Email platform changes (deliverability rule updates, sender reputation changes, ISP filtering)
- Social platform reach/engagement algorithm changes

MARKET/COMPETITIVE (external demand shifts):
- Competitor action (new product launch, aggressive pricing, viral campaign capturing share)
- Category demand shift (seasonal decline, economic headwind, trend reversal)
- ICP behavior change (buying cycle elongation, new research behavior, channel migration)

INTERNAL/OPERATIONAL (self-inflicted changes):
- Content changes (landing page redesign, copy A/B test, offer change)
- Campaign changes (budget reallocation, new targeting, creative rotation)
- Team changes (staffing, process change, vendor switch)
- Audience fatigue (email list burnout, ad frequency saturation, content repetition)

Rank hypotheses by:
1. Probability (based on timing correlation with changes log and deviation pattern)
2. Testability (how quickly and cheaply can this hypothesis be confirmed or rejected?)
3. Impact if true (if this is the cause, what is the fix and how fast can we recover?)

Format each hypothesis as:
Rank | Hypothesis | Evidence | Probability (H/M/L) | Test Method | Time to Confirm | If True: Fix

3. DIAGNOSTIC CHECKLIST (30-MINUTE TRIAGE PROTOCOL)

Generate a prioritized 5-step diagnostic checklist. Each step must include:
- Exact action: what to look at
- Exact tool: where to find it (GA4 > Acquisition > Traffic Acquisition; HubSpot > Reports > Email Health; etc.)
- What you are looking for: the specific signal that confirms or rejects a hypothesis
- Decision rule: if you see [X], then hypothesis [Y] is [confirmed/rejected]

Example format:
Step 1 (5 min): Check GA4 real-time data -- are sessions still flowing or is the drop ongoing?
- Tool: GA4 > Reports > Realtime > Users in last 30 minutes
- Signal: If < [X] users active right now vs. normal [Y] at this hour, the issue is ongoing. If normal, it may have self-resolved.
- Decision rule: Ongoing = escalate immediately. Self-resolved = monitor for 24h before diagnosing.

4. CORRELATION ANALYSIS

Check for correlated metric movements to triangulate root cause:

Traffic anomaly correlation matrix:
- If sessions dropped AND organic specifically dropped AND paid held: likely SEO or technical issue
- If sessions dropped AND all channels dropped equally: likely tracking failure or site-wide issue
- If sessions held AND conversions dropped: likely CRO/funnel issue (landing page, form, offer)
- If conversions held AND MQL count dropped: likely lead scoring change or CRM sync issue
- If email opens dropped suddenly: likely deliverability problem (check spam complaint rate, sender score)
- If CTR dropped but impressions held: creative fatigue or SERP layout change (featured snippet captured position)

For each correlation pattern identified from the data provided, state what it implies and what to do next.

5. ADAPTIVE THRESHOLD RECOMMENDATIONS

Based on the historical volatility observed in the data provided, recommend alert thresholds that minimize false positives while catching real issues early:

For each key metric, specify:
- Green zone: [X]% variance from rolling 7-day average = normal, no action
- Yellow zone: [X]% variance = watch and log, check for pattern over 48h
- Red zone: [X]% variance = immediate triage required
- Black alert: [X]% variance or [X] consecutive days of decline = P1 escalation

Threshold calibration rule: Yellow threshold = 1.5 standard deviations; Red threshold = 2.5 standard deviations; Black alert = 3+ standard deviations or sustained 5-day decline > 10%.

6. ESCALATION COMMUNICATION PACKAGE

Generate three escalation assets:

Asset 1 -- Slack Alert (for marketing ops channel, auto-trigger format):
[SEVERITY] Marketing Alert -- [Metric Name]
Detected: [Metric] is [X]% [below/above] expected for [time period]
Business impact: ~$[X] pipeline at risk if trend continues 30 days
Most likely cause: [Top hypothesis in plain language]
Action taken: [What ops has already done or is doing]
Next update: [Time of next check-in]

Asset 2 -- CMO Email (for P1/P2 escalations, written to be forwarded):
Subject: [ACTION REQUIRED / FYI] [Metric] anomaly detected -- [date]
Body: 3 paragraphs -- What happened, what we know, what we are doing. No jargon. Revenue impact front and center.

Asset 3 -- Incident Log Entry (for post-mortem and pattern tracking):
Date/time detected | Metric affected | Deviation % | Duration | Root cause confirmed | Time to resolution | Preventive action taken

7. RECOVERY PROJECTION

For the top 2 most likely root causes, project recovery timeline:
- If root cause is [A]: Expected fix time = [X hours/days]. Recovery to baseline = [X days after fix]. Leading indicator that recovery is working = [specific metric to watch].
- If root cause is [B]: Expected fix time = [X hours/days]. Recovery to baseline = [X days after fix]. Leading indicator = [specific metric to watch].

Note: some root causes have asymmetric recovery curves -- SEO penalty recovery can take 4-12 weeks even after the underlying issue is fixed. Flag these explicitly.

8. PREVENTION SYSTEM DESIGN

After diagnosing the current anomaly, generate a prevention architecture so this class of issue is caught earlier next time:

Recommended monitoring setup:
- Daily automated checks: [list 5-7 metrics to check daily, with threshold per metric]
- Weekly review cadence: [list what to review weekly vs. daily]
- Automated alert rules: [specific rules to set up in GA4, HubSpot, or your analytics platform]
- Canary metrics: [leading indicators that predict downstream metric drops 3-7 days in advance]

Canary metric examples:
- Crawl budget consumption (Search Console: Coverage > Crawled pages) predicts organic traffic 2-4 weeks ahead
- Email list growth rate predicts deliverability health 30-60 days ahead
- Free trial activation rate predicts paid conversion rate 14-30 days ahead
- Ad frequency per user predicts CTR decay 7-14 days ahead

OUTPUT FORMAT:
Produce a structured incident report with these labeled sections:
1. Anomaly Summary (severity, business impact in $, duration)
2. Root Cause Ranking (top 3 hypotheses with evidence and probability)
3. 30-Minute Diagnostic Checklist (5 steps, exact tools and decision rules)
4. Correlation Analysis (what other metrics confirm or reject the top hypothesis)
5. Immediate Actions (what to do right now, in priority order)
6. Escalation Package (Slack message + CMO email + incident log entry)
7. Recovery Projection (timeline and leading indicators to watch)
8. Prevention System (monitoring setup to prevent recurrence)

CONSTRAINTS:
- Every root cause hypothesis must cite a specific signal from the data provided as evidence
- Every diagnostic step must name the exact tool, menu path, and metric to check -- no vague directions
- Dollar impact must be calculated even if estimates are rough -- use ranges if needed
- Do not recommend "wait and see" without specifying exactly what leading indicator to watch and a decision trigger for action

## Example Input/Output

**Input Example:**

Company: Vaultline (B2B SaaS, revenue intelligence platform for enterprise sales teams)
Business model: B2B SaaS | ACV: $48,000 | Primary conversion: Demo request
Active channels: SEO, Google Ads, LinkedIn Ads, HubSpot email nurture
Analytics: GA4 + HubSpot + Salesforce

Anomaly: Demo request CVR (sessions-to-demo) dropped from 2.1% to 0.9% -- a 57% decline
Current CVR: 0.9% over the last 4 days
Baseline: 2.1% rolling 30-day average
Sessions are stable: 14,200 sessions/week vs. 13,800 expected -- no traffic anomaly
First detected: Tuesday morning after Monday evening deployment

Recent changes:
- Nov 18 (Monday): Deployed new homepage redesign (A/B test ended, variant B made permanent)
- Nov 15 (Friday): Launched new LinkedIn campaign targeting VP Sales at 500-5,000 employee companies
- Nov 10: Updated HubSpot form on demo page (added 2 new fields: company revenue and team size)

No known external events or seasonality factors.

**Output Example:**

**1. Anomaly Summary**

Severity: P1 Critical
- CVR drop of 57% sustained for 4 consecutive days -- statistically extreme (approximately 4.2 standard deviations below 30-day baseline)
- Sessions are stable, which isolates the problem to the conversion funnel, not traffic acquisition
- Business impact: At 2.1% CVR, 14,200 sessions should produce approximately 298 demo requests/week. Actual: 128. Gap: 170 demo requests/week. At 15% close rate and $48,000 ACV, that is $1,224,000 in at-risk pipeline per month if unresolved.

**2. Root Cause Ranking**

| Rank | Hypothesis | Evidence | Probability | Time to Confirm |
|---|---|---|---|---|
| 1 | HubSpot form friction: 2 new required fields added Nov 10 increased form abandonment | Timing: form change predates deployment but CVR decline hit Tuesday -- possible delayed effect as redesign sent more cold traffic to demo page, exposing latent form friction | High | 15 minutes |
| 2 | Homepage redesign (Variant B) degraded CTA prominence or removed a high-converting path | Timing: CVR drop detected the morning after Monday's deployment -- strongest single-event correlation | High | 20 minutes |
| 3 | LinkedIn campaign sending lower-intent traffic that dilutes blended CVR | New campaign launched Nov 15. LinkedIn traffic tends to browse without immediately converting; volume inflates session count without proportional conversions | Medium | 30 minutes |

**3. 30-Minute Diagnostic Checklist**

Step 1 (5 min): Segment CVR by channel in GA4
- Tool: GA4 > Explore > Funnel Exploration > Add dimension: Session source/medium
- Signal: If CVR is low across all channels, root cause is the demo page itself. If CVR is low only for LinkedIn, traffic quality is the issue.
- Decision rule: All-channel CVR < 1.5% = page-level issue (hypotheses 1 or 2). LinkedIn-only CVR < 1% with other channels holding = hypothesis 3.

Step 2 (5 min): Check HubSpot form completion rate pre/post Nov 10
- Tool: HubSpot > Marketing > Forms > [Demo Request Form] > Submissions vs. Views over time
- Signal: If form view-to-submission rate dropped on or after Nov 10 (not Nov 18), form friction is the primary cause.
- Decision rule: Form completion rate dropped > 20% after Nov 10 = form friction confirmed. Roll back 2 new fields immediately.

Step 3 (10 min): Compare post-redesign homepage scroll depth and CTA clicks
- Tool: GA4 > Events > demo_cta_click (if instrumented) or Hotjar/FullStory session recordings on homepage
- Signal: Did the primary demo CTA move below the fold? Did CTA clicks per session drop after Nov 18?
- Decision rule: CTA clicks/session dropped > 30% on Nov 18 = redesign buried the primary conversion path.

Step 4 (5 min): Check mobile vs. desktop CVR split
- Tool: GA4 > Reports > Tech > Tech Overview > segment by Device category
- Signal: If mobile CVR dropped dramatically but desktop held, the redesign broke mobile CTA rendering.
- Decision rule: Mobile CVR < 0.5% + desktop CVR > 1.8% = mobile-specific rendering issue requiring immediate QA.

Step 5 (5 min): Verify HubSpot-to-Salesforce sync is functioning
- Tool: HubSpot > Reports > Contacts > filter by Create date: last 4 days > confirm demo request contacts appear in Salesforce
- Signal: If contacts exist in HubSpot but not Salesforce, this is a CRM sync failure, not an actual CVR drop.
- Decision rule: HubSpot contacts created but not in Salesforce = escalate to RevOps immediately before any other changes.

**4. Correlation Analysis**

Pattern identified: Sessions stable + CVR dropped system-wide across channels = conversion funnel is broken, not traffic source.

This pattern eliminates: SEO penalty (sessions would have dropped), ad quality issues (channel-specific, not system-wide), and tracking failure (sessions would also appear deflated).

This pattern implicates: The demo page itself -- design, form, offer, or technical rendering. The two changes in the relevant window are the HubSpot form update (Nov 10) and homepage redesign (Nov 18). The redesign timing is the stronger suspect, but the form change is a plausible co-cause: the redesign may have directed more cold traffic to the demo page, where new form friction hit harder than it did with warmer organic traffic.

**5. Immediate Actions**

1. Right now: Roll back the HubSpot demo form to the pre-Nov 10 version (remove the 2 new fields). Five-minute change with zero risk. Eliminates a variable even if not the primary cause.

2. Within 30 minutes: QA the post-redesign homepage on mobile (iPhone Safari) and desktop Chrome. Click every CTA. Submit the demo form. Confirm the thank-you page fires a GA4 conversion event. If any step fails, revert the homepage to Variant A immediately.

3. Within 1 hour: If CVR does not show improvement within 4 hours of the form rollback, revert homepage to Variant A as containment. Re-run the A/B test from a capped 10% traffic split rather than a 100% rollout.

4. LinkedIn campaign: Reduce budget by 50% as a precaution. If blended CVR improves, that confirms traffic quality contributed to the decline.

**6. Escalation Package**

Slack message (post to #marketing-ops):
[P1 ALERT] Demo Request CVR: -57% over 4 days
Impact: ~$1.2M in monthly pipeline at risk if unresolved. Sessions are stable -- drop isolated to conversion funnel.
Most likely cause: Homepage redesign deployed Monday night and/or HubSpot form fields added Nov 10 are driving abandonment.
Action taken: Rolling back form fields now. QA-ing homepage CTA flow on mobile and desktop. Root cause confirmed within 30 minutes.
Next update: 11:30am with diagnostic results.

CMO email:
Subject: [ACTION REQUIRED] Demo conversion rate down 57% -- diagnosing now

Our demo request conversion rate dropped from 2.1% to 0.9% starting Tuesday, resulting in approximately 170 fewer demo requests per week and roughly $1.2M in monthly pipeline at risk if the trend continues.

Sessions are completely stable, which tells us this is a funnel problem, not a traffic problem -- our ads and SEO are working fine. We have isolated it to two changes made in the last 8 days: a HubSpot form update that added two required fields, and Monday's homepage redesign deployment. We are rolling back both as an immediate containment measure while we confirm root cause.

I will have a confirmed root cause and recovery timeline by noon today. No action needed from you -- I will flag immediately if we need a budget decision to protect pipeline volume during recovery.

Incident log entry:
Date detected: Nov 19 | Metric: Demo request CVR | Deviation: -57% | Duration: 4 days (ongoing) | Root cause: TBD -- suspected form friction + homepage redesign | Time to resolution: In progress | Preventive action: Implement change freeze protocol requiring marketing ops sign-off before any demo page modifications

**7. Recovery Projection**

If root cause is homepage redesign (hypothesis 2):
- Fix time: 15 minutes to revert to Variant A
- Recovery: CVR should return to baseline (approximately 2.1%) within 24-48 hours as session cache clears
- Leading indicator: Watch GA4 demo_cta_click events hourly. If clicks per session recover within 2 hours of the revert, CVR will follow within 12 hours.

If root cause is HubSpot form friction (hypothesis 1):
- Fix time: 5 minutes to remove the 2 new fields
- Recovery: Immediate for new visitors. For the 4-day pool of visitors who abandoned, consider a retargeting campaign with a simplified CTA to recover lost pipeline.
- Leading indicator: HubSpot form completion rate (views-to-submissions ratio). Should recover to pre-Nov 10 rate within 6 hours of rollback.

**8. Prevention System**

Daily automated monitoring:

| Metric | Tool | Green | Yellow | Red |
|---|---|---|---|---|
| Demo request CVR (sessions-to-demo) | GA4 Funnel | Within 10% of 7-day avg | 10-20% deviation | > 20% deviation |
| HubSpot form completion rate | HubSpot Forms Report | Within 5% of 14-day avg | 5-15% deviation | > 15% deviation |
| Organic sessions | GA4 Acquisition | Within 8% of 7-day avg | 8-18% deviation | > 18% deviation |
| Demo page bounce rate | GA4 Engagement | Within 10% of 7-day avg | 10-25% deviation | > 25% deviation |
| Email deliverability rate | HubSpot Email Health | > 98% | 95-98% | < 95% |
| Paid CPA (blended) | Google/Meta Ads | Within 15% of 7-day avg | 15-30% deviation | > 30% deviation |

Canary metrics to add to weekly review:
- Homepage CTA click rate (tracks 7-14 days before CVR changes become visible in aggregate data)
- Form abandonment rate by field (HubSpot form analytics -- catch new-field friction before it compounds)
- Crawl coverage trend (Google Search Console -- detects indexing problems 3-4 weeks before organic traffic drops)
- Trial-to-paid activation rate (predicts MQL quality 30 days ahead)

GA4 automated alert setup (Admin > Custom Alerts):
- Alert: "Demo CVR drops > 15% vs. prior 7-day average" -- Trigger: Daily -- Notification: Email to marketing ops + Head of Demand Gen
- Alert: "Organic sessions drop > 20% vs. prior 7-day average" -- Trigger: Daily
- Alert: "Form submissions drop > 25% vs. prior 7-day average" -- Trigger: Daily

Process rule: Any code deployment or marketing asset change must be logged in a shared change log (Notion or Confluence) with format: Date | Change | Owner | Expected impact | Rollback plan. This becomes the first place to check during any anomaly triage.

## Success Metrics
- Time to root cause identification: under 30 minutes for P1/P2 incidents
- False positive alert rate: below 10% (well-calibrated thresholds prevent alert fatigue)
- Incident log completeness: 100% of P1/P2 anomalies have documented root cause and post-mortem within 48 hours
- Revenue recovered: track pipeline delta between "anomaly detected" and "resolved" dates vs. historical baselines
- Mean time to resolution (MTTR): P1 under 4 hours, P2 under 24 hours, P3 under 72 hours

## Related Prompts
- [Marketing Performance Dashboard Generator](./Marketing-Performance-Dashboard-Generator.md) - Build the baseline KPI dashboard that makes anomalies visible at a glance
- [Marketing OKR & Goal-Setting Framework](./Marketing-OKR-Goal-Setting-Framework.md) - Define the targets and thresholds that determine what counts as an anomaly
- [Funnel Performance Diagnostics](../Campaign-Performance-Analysis/Funnel-Performance-Diagnostics.md) - Deep-dive funnel stage analysis when a CVR anomaly is confirmed
- [Marketing Attribution & ROI Engine](../Campaign-Performance-Analysis/Marketing-Attribution-ROI-Engine.md) - Recalibrate attribution models after anomalies that affect conversion tracking

## Integration Tips
- **GA4 Custom Alerts:** Admin > Custom Insights > Create Insight. Set metric, condition (is less than/greater than), and threshold value. GA4 will email you when the threshold is breached. Pair with a secondary HubSpot check before escalating to reduce false positives.
- **HubSpot:** Marketing > Reports > Email Health Score for deliverability monitoring. Use the Forms report (Marketing > Forms > click any form > Analytics tab) to track form completion rates daily during the first 7 days after any form change.
- **Looker Studio:** Build a single "anomaly monitor" page with scorecards showing current vs. prior-period values. Use conditional formatting (red/yellow/green) based on deviation thresholds. Share the link in your Slack monitoring channel so anyone can check status without logging into multiple platforms.
- **Zapier / Make automation:** Create a workflow: GA4 alert email received > Parse alert details > Post formatted message to #marketing-ops Slack channel. This eliminates manual forwarding and ensures alerts reach the team within minutes of detection.
- **Salesforce:** Set up a report for "Leads created this week by source" with a comparison to prior week. Schedule it to email marketing ops every Monday morning. A sudden drop in leads from a specific source (e.g., web form) is often the first visible signal of a form or CRM sync failure.
- **Incident tracking:** Create a Notion database or Airtable base with the incident log template from this prompt. Link each incident to the change log entry that caused it. After 10+ incidents, patterns emerge -- e.g., Friday deployments cause disproportionate issues, LinkedIn campaigns always dilute blended CVR in the first week.

## Troubleshooting

**Problem: GA4 is showing a conversion drop, but HubSpot is showing normal lead volume -- which one is right?**
Solution: HubSpot is almost always more accurate for actual lead count because it tracks form submissions server-side. GA4 client-side tracking can be blocked by ad blockers, browser privacy settings, or misconfigured tags. If HubSpot shows normal leads but GA4 shows a drop, investigate your GA4 tag implementation first -- check Tag Manager preview mode and confirm events are firing on the thank-you page -- before assuming a real conversion decline.

**Problem: The anomaly self-resolved before I could diagnose it -- how do I prevent recurrence without knowing the cause?**
Solution: Self-resolving anomalies are often caused by bot traffic, temporary ISP issues, platform glitches, or time-limited external events. Log the incident anyway, noting "self-resolved, root cause unknown." After 3+ similar self-resolving anomalies, look for patterns: same day of week, same traffic source, same time of day. Patterns reveal systematic causes that do not show up in single-incident analysis.

**Problem: We have 20+ alerts per week firing and the team ignores them -- how do we fix alert fatigue?**
Solution: Alert fatigue is a system design failure, not a human failure. Recalibrate thresholds upward (from 10% deviation to 20% for yellow-zone metrics) and require 2 consecutive days of deviation before triggering a red alert. Reduce the monitored metric list to the 3-4 that most directly predict revenue impact. Create a separate Slack channel for P3/P4 alerts that only marketing ops monitors, and reserve the main channel for P1/P2 only. Review and retire any alert that has never triggered a confirmed actionable issue.

## Version History
- v1.0: Initial creation (auto-generated)
