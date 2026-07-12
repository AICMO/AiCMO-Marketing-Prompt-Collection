# AI-Powered B2B SaaS Customer Marketing Expansion Revenue Campaign Architecture & Cross-Sell Upsell Pipeline Intelligence Engine - Signal-Triggered Expansion Orchestration, Multi-Channel Customer Campaign Design & Marketing-Sourced NRR Pipeline Attribution

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** b2b, customer-marketing, expansion-revenue, cross-sell, upsell, nrr, pipeline, automation, lifecycle, saas, marketing-ops

## Overview
Transforms product usage signals, health scores, and firmographic growth data into autonomous cross-sell and upsell campaigns that generate marketing-sourced expansion pipeline. Use it to design expansion campaign architecture from scratch, to diagnose why customer marketing isn't contributing to NRR, or to build the signal-detection-to-campaign-execution workflow that runs without manual intervention from your CS team.

## Quick Copy-Paste Version

You are a B2B SaaS customer marketing strategist with deep expertise in expansion revenue programs. Design a complete customer marketing expansion campaign system for my company.

**Company profile:**
- Product: [e.g., revenue intelligence platform, HR automation software, cybersecurity SaaS]
- ACV: [$X] | Average contract length: [X months]
- Current NRR: [X%] | NRR target: [X%]
- Primary expansion type: [Seat expansion / Product line cross-sell / Usage tier upsell / Add-on modules]
- Expansion ACV opportunity per customer: [$X average]
- CRM/MAP stack: [e.g., Salesforce + Marketo / HubSpot / other]
- CS team size: [X CSMs managing X customers]

**Customer base snapshot:**
- Total customers: [#]
- Customers below maximum seat/usage potential: [#, % of base]
- Customers eligible for cross-sell (missing one or more products): [#]
- Average product adoption score across base: [X/100 or N/A]
- NPS/health score data available: [Yes/No]

**Current expansion motion:**
- Who owns expansion today: [CS only / Marketing + CS / Sales + CS / No formal owner]
- Existing customer marketing touchpoints: [List: QBRs, newsletters, in-app, email nurtures, etc.]
- Marketing's current NRR contribution: [$X or unknown]

Design:
1. **Expansion Signal Library** — 10 specific signals that indicate upsell or cross-sell readiness, with the data source for each and the campaign trigger threshold
2. **Campaign Architecture Map** — for each major expansion motion (seat upsell, tier upgrade, cross-sell), design the full multi-channel campaign sequence with timing, channel, message angle, and CTA
3. **Customer Segmentation Model** — how to segment the customer base into expansion tiers (Hot / Warm / Not Yet) using health score, product usage, contract age, and firmographic growth signals
4. **Marketing-to-CS Handoff Protocol** — when marketing campaigns should auto-escalate to CSM outreach vs. run autonomously, and what data to pass in the handoff
5. **Content & Asset Requirements** — exactly which emails, ads, in-app messages, and case studies need to be built to support the campaigns
6. **Attribution Model** — how to measure marketing's contribution to expansion pipeline separately from CS-sourced expansion

Be specific. Use real trigger logic, exact timing, and specific message angles. No vague "personalize based on usage" — give me the actual segmentation criteria and message frameworks.

## Advanced Customizable Version

### Role & Context
You are an embedded B2B SaaS Customer Marketing Manager reporting to the VP of Demand Generation, with a dotted line to the VP of Customer Success. You are accountable for marketing-sourced expansion pipeline — tracked separately from CS-sourced upsells — and your work must integrate cleanly with CSM workflows without creating noise or stepping on active CS renewal/expansion conversations. Your programs must run autonomously via marketing automation for 80% of the base, with human escalation reserved for strategic or high-ACV expansion opportunities.

**Company profile:**
- Company name: [Company]
- Product category: [e.g., Revenue Intelligence / Marketing Analytics / HR Tech / Cybersecurity / FinTech SaaS]
- ARR: [$X] | Growth stage: [Series B / C / Growth / Pre-IPO]
- Average new logo ACV: [$X]
- Average expansion ACV per upsell/cross-sell event: [$X]
- Current NRR: [X%] | Board target NRR: [X%]
- NRR gap (current vs. target): [X percentage points = $X ARR shortfall]
- Primary expansion motions: [Seat expansion / Usage tier upsell / Add-on modules / Full product cross-sell]
- Customer segments: [SMB under $20K ACV / Mid-Market $20K-$100K / Enterprise $100K+]

**Customer base profile:**
- Total customers: [#] across [# of segments]
- Customers under-indexed on seat capacity (e.g., < 70% of purchased seats active): [#]
- Customers missing Product Line B (cross-sell eligible): [#]
- Customers on Tier 1 with usage patterns suggesting Tier 2 readiness: [#]
- Average customer health score: [X/100]
- Average product adoption score: [X/100]
- NPS distribution: [Promoters: X%, Passives: X%, Detractors: X%]
- Average customer age: [X months since first contract]
- Customers approaching contract renewal (next 90 days): [#]

**Signals and data available:**
- Product usage data: [Yes / No — tool: Mixpanel / Amplitude / Pendo / Gainsight / HubSpot / Other]
- Health score data: [Yes / No — tool: Gainsight / ChurnZero / Totango / Custom]
- CRM data quality: [Clean (90%+ populated) / Mixed / Sparse]
- Firmographic growth signals: [LinkedIn employee count changes / Funding events / Job postings — available via: ZoomInfo / Clearbit / 6sense / Other]
- Intent data (third-party): [Yes (tool: ___) / No]
- CS activity log (last touchpoint date, open renewal conversations): [In CRM: Yes/No]
- In-app messaging platform: [Pendo / Intercom / Appcues / None]

**Marketing and CS team context:**
- Marketing team owning customer campaigns: [Solo / Team of X]
- CSM ratio: [1 CSM per X customers]
- CSM bandwidth: [High (proactive) / Medium (mostly reactive) / Low (firefighting)]
- Current marketing-sourced expansion pipeline (if any): [$X / unknown]
- Marketing's authority: [Can send customer emails autonomously / Must get CSM approval / Partnership model — CSM + marketing sign off together]
- Tools available: [MAP: Marketo/HubSpot, CRM: Salesforce/HubSpot, In-app: Pendo/Intercom, Ad platform: LinkedIn/Meta, ABM: 6sense/Demandbase, CSM: Gainsight/Salesforce]

**Expansion motion priorities (rank 1-3):**
- Seat expansion (more users on existing product): [Priority rank]
- Usage tier upsell (upgrade to higher plan): [Priority rank]
- Add-on module cross-sell: [Priority rank]
- Full product cross-sell (second product line): [Priority rank]

### Campaign Architecture Framework

#### Section 1: Expansion Signal Library & Trigger Logic

Build a signal-based trigger system. For each signal, define:
- **Signal name and description**
- **Data source** (which system generates it)
- **Trigger threshold** (the exact value that fires the campaign)
- **Confidence score** (high = reliable expansion indicator; medium = directional; low = contextual)
- **Campaign mapped to** (which expansion motion this signal activates)

Design triggers across four signal categories:

**Category A: Product Usage Signals (in-app data)**
1. **Seat Saturation Signal**: Active users ÷ purchased seats ≥ 85% for 14+ consecutive days → triggers seat expansion campaign. Confidence: High. Data source: product analytics.
2. **Feature Ceiling Signal**: Customer has unlocked and actively used all features in current tier for 30+ days → triggers tier upgrade campaign. Confidence: High. Data source: feature flag + usage events.
3. **Usage Volume Spike**: Core metric (API calls, documents, records processed) exceeds 80% of plan limit in current billing period → triggers immediate upgrade campaign with urgency framing. Confidence: Very High. Data source: billing/metering system.
4. **Cross-Sell Feature Interest Signal**: User visited pricing page for Product B, opened help docs about Product B features, or clicked on in-app Product B promotional banner → triggers cross-sell sequence. Confidence: High. Data source: product analytics + web analytics.
5. **Champion Power User Emergence**: A specific user has 3x average engagement, has shared content externally (export events), or has invited multiple colleagues → triggers advocate identification and expansion outreach through this champion. Confidence: Medium. Data source: product analytics.

**Category B: Customer Success & Relationship Signals**
6. **High NPS Promoter Signal**: Customer submits NPS score ≥ 9 → triggers advocacy + expansion sequence within 48 hours while sentiment is hot. Confidence: High. Data source: NPS survey tool (Delighted/Medallia/HubSpot).
7. **QBR Success Signal**: CSM marks QBR outcome as "positive/expansion conversation noted" in CRM → triggers marketing-assisted follow-up sequence to buying committee members NOT on the QBR. Confidence: High. Data source: CRM activity log.
8. **Health Score Milestone**: Customer health score crosses from amber to green (e.g., 65 → 80+) for first time → triggers "you're thriving, here's what's next" expansion conversation. Confidence: Medium-High. Data source: Gainsight/ChurnZero.
9. **Case Study Participation**: Customer agrees to participate in case study, reference call, or co-marketing → signals high trust, triggers internal champion development + expansion conversation. Confidence: Medium. Data source: CRM/customer evidence program tracker.

**Category C: Firmographic & External Growth Signals**
10. **Headcount Growth Signal**: Customer company has grown employee count by 20%+ since contract start (via LinkedIn/ZoomInfo monitoring) → triggers seat expansion outreach to the economic buyer noting company growth. Confidence: Medium-High. Data source: Clearbit/ZoomInfo enrichment (monthly refresh).
11. **Funding Round Signal**: Customer company raises Series A/B/C → triggers executive-level expansion outreach referencing new growth capacity. Confidence: Medium. Data source: Crunchbase/ZoomInfo alerts.
12. **Job Posting Signal**: Customer posts 5+ new roles in functions that would benefit from the product → triggers expansion campaign to VP/Director of that function. Confidence: Medium. Data source: job posting monitor (ZoomInfo/Bombora).

**Category D: Behavioral & Lifecycle Signals**
13. **Contract Anniversary Signal**: 6-month contract mark → triggers "you've been with us 6 months — here's your ROI snapshot + what's possible next" expansion conversation. Confidence: Medium. Data source: CRM contract date.
14. **Pre-Renewal Window Signal**: 90 days before renewal → triggers renewal + expansion campaign sequence coordinated with CSM. Confidence: High (lifecycle-driven, not behavior-driven). Data source: CRM contract end date.
15. **Competitive Threat Signal**: Customer contact visits competitor comparison pages on your site, reads competitive battle card content → triggers expansion + stickiness campaign positioning switching costs. Confidence: Medium. Data source: reverse IP/account-level web analytics (6sense/Demandbase).

---

#### Section 2: Multi-Channel Campaign Architecture by Expansion Motion

Design end-to-end campaign sequences for each expansion type. For each campaign:
- Trigger (from Signal Library above)
- Channel sequence and timing
- Message angle per channel
- CTA and conversion path
- CSM notification (when/what)
- Exit criteria (when to stop the sequence)

**Campaign 1: Seat Expansion — "Your Team Is Outgrowing Your Plan"**

*Trigger*: Seat Saturation Signal (≥ 85% active seat utilization for 14 days) OR Headcount Growth Signal (20%+ employee growth)

*Audience*: Economic buyer (CXO/VP who signed the contract) + IT/Operations admin who manages the account

*Sequence*:
- **Day 1 — In-app banner (admin only)**: "You're using 87 of 100 seats. Teams this close to capacity typically hit bottlenecks within 30 days. [Add seats now — no contract change required]"
- **Day 1 — CSM Slack alert** (automated via Gainsight/Zapier): "[Company] hit 87% seat saturation today. Marketing expansion sequence started. If you have an active upsell conversation, reply PAUSE to hold the automated sequence."
- **Day 3 — Email to economic buyer**: Subject: "[Company] is scaling — your [Product] plan might be limiting you". Body: Usage data visualization (# active users, team activity metrics) + projected time to full capacity at current growth rate + specific seat pricing options with volume discount framing + single CTA: "Review expansion options" (links to personalized pricing page with current seat count pre-filled).
- **Day 7 — LinkedIn Matched Audience ad** (if economic buyer on LinkedIn): Account-targeted ad showing social proof from similar-size companies after seat expansion + outcomes metric ("Companies that expanded from 100 to 200 seats saw X% more [core metric]"). Impression frequency cap: 5/week.
- **Day 10 — Email #2 to economic buyer**: Subject: "What's a blocked colleague costing you?" (opportunity cost framing). Body: 3-sentence case study of similar company that delayed expansion, the productivity cost, and the outcome after expansion. CTA: "Schedule 15 min to add seats" → CS calendar link.
- **Day 14 — Champion outreach email** (to Power User identified in signal): "You've become one of [Product]'s top users at [Company] — have you thought about bringing the rest of [team/department] on? I can get you a team expansion quote today." From: CSM name.
- **Day 21 — Final email to economic buyer**: Subject: "Last check-in on the [Product] capacity question". Brief. CTA: Schedule call or upgrade online.
- **Exit criteria**: Seat expansion contract signed; CSM marks as "active commercial conversation in Salesforce"; economic buyer replies; 21-day sequence ends with no engagement → move to low-cadence 60-day re-trigger watch.

**Campaign 2: Tier Upgrade — "You've Outgrown Your Current Plan"**

*Trigger*: Feature Ceiling Signal (all Tier 1 features used for 30+ days) OR Usage Volume Spike (>80% of plan limit)

*Audience*: Power user who hit the ceiling + economic buyer

*Sequence*:
- **Immediate — In-app notification (power user)**: "You've explored everything [Product Tier 1] offers. See what's unlocked in [Tier 2] — your team is ready." CTA: "See Tier 2 features" → interactive feature comparison.
- **Day 1 — CSM alert**: Same format as above — automated Slack/email with override option.
- **Day 2 — Email to power user**: "You're one of our most advanced users — here's what [Tier 2] would unlock for someone using [Product] the way you do." 3 specific features relevant to their usage pattern (pulled from product analytics segment). CTA: "Start a free 14-day Tier 2 trial" → if self-serve trial available; else "Talk to your CSM about upgrading."
- **Day 5 — Email to economic buyer**: Business case framing. "[Power User Name] at your company is hitting the ceiling of your current plan — here's what upgrading to [Tier 2] unlocks and how other [Industry] companies have used it." ROI data. CTA: "See upgrade options."
- **Day 8 — LinkedIn ad (economic buyer)**: Customer testimonial from a peer company that upgraded, focusing on the business outcome unlocked.
- **Day 14 — CSM-sent email** (marketing-drafted, CSM-sent for personalization): "I wanted to follow up personally — based on how [Company] is using [Product], I think [Tier 2] would directly accelerate [specific use case]. Can I send you a custom upgrade proposal?"
- **Exit criteria**: Tier upgrade completed; active commercial negotiation in CRM; 21-day sequence ends with no engagement → 30-day rewatch.

**Campaign 3: Add-On Module Cross-Sell**

*Trigger*: Cross-Sell Feature Interest Signal (visited Add-On pricing page, opened Add-On docs) OR QBR Success Signal (CSM flagged expansion opportunity)

*Audience*: Contact who showed interest + economic buyer + relevant department head

*Sequence*:
- **Day 1 — Triggered email to contact who visited Add-On page**: "We noticed you were exploring [Add-On Name] — here's a 3-minute overview of how [Company in their industry] uses it alongside [Core Product]." Video thumbnail CTA → 3-min demo video. Soft close: "Happy to walk you through it on a call."
- **Day 1 — CSM alert**: "[Contact] showed interest in [Add-On] — I've started a nurture sequence. Do you want to be included in the follow-up or run point yourself?"
- **Day 3 — Case study email**: Customer in same industry/size using both Core Product + Add-On. Specific outcome metrics. CTA: "See how [Reference Company] uses [Core + Add-On] together."
- **Day 6 — Email to economic buyer**: "How [Add-On] pays for itself — the math for [Industry] companies." ROI calculator link (pre-filled with their company size and industry benchmarks). CTA: "Calculate your ROI."
- **Day 10 — LinkedIn ad** (economic buyer + department head): Customer success stat specific to the Add-On value proposition. "Companies using [Core + Add-On] together see X% [core metric improvement]."
- **Day 14 — CSM + Marketing joint email** (appears to come from CSM): "[Contact Name] — I've put together a custom [Add-On] proposal for [Company] based on how you're using [Core Product]. Can we jump on a 20-minute call this week?"
- **Day 21 — Final email from CSM**: Brief. "Still thinking about [Add-On]? I can get you a net-new pricing quote that factors in your existing contract."
- **Exit criteria**: Add-On demo scheduled; Add-On contract signed; CSM marks as "commercial"; 21 days with no engagement → quarterly re-trigger.

---

#### Section 3: Customer Segmentation for Expansion Prioritization

Build a three-tier expansion prioritization model. Each customer gets an **Expansion Readiness Score (ERS)** from 0-100 based on weighted inputs:

**Scoring Model (100 points total):**

| Dimension | Weight | Scoring Logic |
|---|---|---|
| Product adoption depth | 25 pts | Daily active usage: 25pts; Weekly: 18pts; Monthly: 10pts; Sporadic: 0pts |
| Seat/usage capacity | 20 pts | >85% utilization: 20pts; 70-84%: 14pts; 50-69%: 7pts; <50%: 0pts |
| Health score | 20 pts | Green (80-100): 20pts; Amber (60-79): 12pts; Red (<60): 0pts |
| Expansion eligibility | 15 pts | Missing 2+ products/tiers: 15pts; Missing 1: 10pts; Fully expanded: 0pts |
| Relationship indicators | 10 pts | NPS Promoter: 10pts; Passive: 5pts; Detractor: 0pts |
| Growth signals | 10 pts | Funding + headcount growth: 10pts; One signal: 6pts; None: 0pts |
| Contract stage | —bonus— | 90-day pre-renewal: +10 bonus pts |

**Tier Assignment:**
- **Tier 1 — Hot (ERS 75-100)**: Marketing automation + CSM active engagement. Personalized, high-touch sequences. CSM receives daily alert digest of Tier 1 signals.
- **Tier 2 — Warm (ERS 45-74)**: Marketing automation only. Trigger-based sequences run without CSM involvement. CSM receives weekly digest.
- **Tier 3 — Not Yet (ERS 0-44)**: Low-frequency nurture only (monthly customer newsletter, product announcements, no direct expansion pitch). Reassess quarterly.

**Segment Refresh Cadence:**
- Score recalculation: Monthly (pull from Gainsight/CRM + product analytics)
- Tier migrations: Automated — when ERS changes tier, immediately adjust enrollment in active campaign tracks
- Manual override: CSMs can flag any customer as "Expansion Paused — Renewal Risk" to suppress all marketing expansion campaigns

---

#### Section 4: Marketing-to-CS Handoff Protocol

Define exactly when marketing campaigns auto-escalate to CSM vs. run autonomously.

**Autonomous Marketing Execution (No CSM involvement required):**
- Customer ERS is Tier 2 (Warm)
- No open renewal conversation in CRM
- No active churn flag or health score < 60
- No CSM flag of "Expansion Paused"
- Campaign sequence is trigger-based (not account-specific)

**Auto-Escalate to CSM (Marketing pauses, CSM takes over):**
- Customer opens 3+ emails in sequence without converting → CSM receives "high-intent lead" alert with full engagement data
- Customer clicks pricing/upgrade CTA but doesn't complete purchase → Immediate CSM alert: "Expansion intent detected — contact within 24 hours"
- Customer ERS crosses from Tier 2 to Tier 1 → CSM notified to add account to their proactive outreach list
- Customer replies to any marketing email (even non-expansion) → Marketing auto-forwards to CSM to respond
- ACV of expansion opportunity exceeds [$X threshold] → Always CSM-led, marketing supports with assets only

**CSM Alert Format (delivered via Slack + CRM task):**

🔔 EXPANSION SIGNAL — [Company Name]
Signal type: [Seat Saturation / Cross-Sell Interest / Tier Ceiling / Other]
ERS Score: [X/100] | Tier: [Hot/Warm]
Trigger detail: [Specific trigger — e.g., "89% seat utilization for 17 days"]
Marketing campaign status: [Step 3 of 5 — Day 8 — 2 emails sent, 1 opened]
Economic buyer: [Name, Title, Email]
Last CSM touchpoint: [X days ago — [activity type]]
Expansion opportunity: [$X — [Tier upgrade / X seats / Add-On name]]
Recommended action: [Book a call by [date] / Review and reply / Take over sequence]
[Override options]: [PAUSE sequence | TAKE OVER | ADD NOTE | IGNORE]

---

#### Section 5: Content & Asset Production Requirements

List every asset needed to run the campaigns above, with specs:

**Email Templates (marketing-drafted):**
- Seat expansion sequence: 4 emails (economic buyer x3, power user x1) — tone: data-driven, respectful of relationship
- Tier upgrade sequence: 4 emails (power user x2, economic buyer x2) — tone: celebratory of achievement, aspirational
- Cross-sell sequence: 5 emails (interest contact x2, economic buyer x2, CSM-sent x1) — tone: consultative, peer-to-peer
- Pre-renewal expansion sequence: 3 emails (economic buyer + champion) — tone: partnership, forward-looking

**In-App Notifications:**
- Seat saturation banner (admin view): 1 variant for 85%+ utilization
- Feature ceiling banner (power user view): 1 variant per major feature ceiling point
- Cross-sell awareness banner: 1 variant per Add-On module
- Health milestone (green score) celebration: 1 variant with expansion prompt

**LinkedIn Ad Creative:**
- Seat expansion: 1 Single Image + 1 Carousel (social proof focus)
- Tier upgrade: 1 Video (customer testimonial) + 1 Single Image (ROI stat)
- Cross-sell: 1 Single Image (integration/use case visual) per Add-On
- All ads: Account-based targeting via LinkedIn Matched Audiences (customer email list) + Lookalike suppression (exclude new prospect list)

**Case Studies / Social Proof:**
- Minimum 1 case study per major expansion motion
- Each case study must include: expansion type, expansion ACV, specific metric improved post-expansion, customer quote from economic buyer
- Format: 1-page PDF + 400-word email version + LinkedIn post version

**ROI Calculator:**
- Seat expansion: "What does each additional seat generate?" (revenue per user metric)
- Tier upgrade: "What does [Tier 2 feature] unlock?" (value metric specific to industry)
- Cross-sell: "Add-On ROI Calculator" (pre-populated with customer's current usage as baseline)

---

#### Section 6: Attribution Model for Marketing-Sourced Expansion Pipeline

Define how to measure marketing's contribution to expansion pipeline separately from CS-sourced deals.

**Attribution Categories:**
- **Marketing-Sourced Expansion**: Customer clicked a marketing campaign CTA that directly created or accelerated the expansion opportunity. Marketing gets 100% credit.
- **Marketing-Influenced Expansion**: Marketing campaign ran to the customer before the expansion conversation was opened by CS. Marketing gets agreed % credit (typically 30-50%).
- **CS-Sourced Expansion**: No marketing campaign touchpoint. Marketing receives 0% credit.

**Data Capture Requirements (CRM fields):**
- Expansion Opportunity: New field "Expansion Source" = Marketing / CS / Self-Serve / Sales
- Expansion Opportunity: New field "Marketing Campaign Touchpoint" = [Campaign name + date of last touchpoint before opp creation]
- Contact: "Last Marketing Expansion Email Opened" date
- Contact: "Marketing Expansion CTA Clicked" Boolean + date

**Marketing Expansion Pipeline Dashboard (build in Salesforce/HubSpot):**
- Total expansion pipeline created (rolling 90 days): $X
- Marketing-sourced expansion pipeline: $X [%]
- Marketing-influenced expansion pipeline: $X [%]
- Expansion pipeline by campaign type (seat / tier / cross-sell / pre-renewal)
- Closed-won expansion ARR attributable to marketing: $X
- Marketing-sourced expansion CAC: $X per expansion deal
- Revenue multiple: $X expansion ARR : $X customer marketing investment

**Monthly Reporting Metric:**
"Marketing-Sourced Expansion ARR" = Closed-won expansion opportunities where marketing campaign touchpoint occurred within 45 days of opportunity creation date AND "Expansion Source" = Marketing or Influenced.

---

### Output Format

Structure your response as:
1. Expansion Signal Library (12-15 triggers with data source, threshold, confidence, and campaign mapped)
2. Campaign Architecture Map (sequences for top 2-3 expansion motions with day-by-day channel/message plan)
3. Customer Segmentation Model (scoring dimensions, tier assignments, refresh cadence)
4. Marketing-to-CS Handoff Protocol (escalation criteria, alert format, override logic)
5. Content & Asset Production Checklist (what needs to be built before launch, in priority order)
6. Attribution Model Setup (CRM fields, dashboard definition, monthly metric)
7. 90-Day Launch Roadmap (sequence: data audit → segment build → campaign build → CS enablement → launch → optimize)

## Example Input/Output

**Input (Sample Data):**

Company: Meridian Intelligence (B2B SaaS, Revenue Intelligence, $27M ARR, Series B)
ACV: $34,000 new logo | Average expansion ACV: $14,000 per event
Current NRR: 108% | Board target: 120% → $3.24M annual NRR gap to close
Primary expansion: Seat expansion (users on a seat-based plan) + Analytics Add-On cross-sell
CRM/MAP: Salesforce + HubSpot | CS tool: Gainsight | Product: Mixpanel | In-app: Pendo
Customer base: 340 customers | 185 on Starter Plan (≤25 seats), 105 on Growth Plan (≤75 seats), 50 on Enterprise (unlimited)
CSM team: 4 CSMs at 85 customers each — high workload, proactive expansion conversations rare
CS + Marketing split: Marketing has authority to send customer emails autonomously; must flag to CSM before any deal >$25K

**Output (Sample):**

**Top Expansion Signals for Meridian Intelligence:**

1. **Starter Seat Saturation (23+ of 25 seats active for 14 days)** → Triggers "Scale Your Revenue Intelligence Team" sequence. Data: Mixpanel DAU/MAU by account. Confidence: Very High. Estimated 28 customers currently triggering this signal.

2. **Analytics Add-On Page Visit** → Triggers "You're ready for Analytics" sequence. Data: HubSpot web analytics (account-level via 6sense). Confidence: High. 3+ page visits in 30 days = high intent. Average 6-8 customers/month trigger this.

3. **Growth Plan Feature Ceiling** → Customer has used all Growth Plan features (forecast models, integrations, data exports) for 21+ days → Triggers Enterprise upgrade conversation. Confidence: High. Data: Mixpanel feature flag + event tracking.

4. **NPS 9-10 Promoter** → Triggers advocacy + expansion sequence within 48 hours. Data: Delighted NPS surveys (sent at 90-day mark + annual). Confidence: High. 62% of Meridian's base is Promoter.

5. **Headcount Growth >20%** → Triggers seat expansion letter to VP of Sales or RevOps (the economic buyer). Data: ZoomInfo enrichment refresh (monthly). Confidence: Medium-High. Estimated 15 customers triggered in last quarter.

**Starter → Growth Seat Expansion Campaign (Sample Sequence):**

- Day 0: Pendo in-app banner to admin: "23 of 25 seats active — your team is almost at capacity. [Add seats now]"
- Day 0: Gainsight auto-alert to CSM: "Meridian Expansion Trigger — [Company] at 92% seat utilization. Marketing sequence Day 0 starting. Reply PAUSE to hold."
- Day 2: HubSpot email to VP Sales (economic buyer): Subject: "Your [Company] revenue team is approaching full capacity — here's what that means." Body: Screenshot of their Mixpanel seat utilization + projection at current growth rate + seat pricing table (Starter → Growth) with volume discount highlighted. CTA: "Review seat options" → personalized pricing page.
- Day 5: LinkedIn Single Image ad (VP Sales at [Company]): "Acme Corp expanded from 25 → 60 seats and increased forecast accuracy by 34% in 90 days." CTR target: 0.6%+.
- Day 8: HubSpot email #2 to VP Sales: Subject: "What a blocked RevOps analyst costs — the math." Body: Opportunity cost calculator (revenue per rep × number of reps without access × months delayed). CTA: "Get a custom seat expansion quote."
- Day 12: HubSpot email from CSM (drafted by marketing, sent as CSM via HubSpot): "Hi [Name], I've been watching [Company]'s adoption — you're one of our highest-performing teams. I'd love to put together a Growth Plan proposal before your team hits capacity. 15 minutes this week?"
- Day 18: Final email to VP Sales: Brief. "Wanted to check in one more time on the seat expansion. Happy to lock in pricing before our next rate adjustment on [date]."
- Exit: Opportunity created in Salesforce with "Expansion Source = Marketing" and "Marketing Campaign = Starter Seat Saturation Sequence."

**Attribution Win (Example):**
Q2 Results: 14 expansion deals closed, total $196K expansion ARR.
- Marketing-sourced (direct CTA click → opp): 6 deals, $84K ARR (43%)
- Marketing-influenced (campaign ran, CS closed): 5 deals, $70K ARR (36%)
- CS-sourced only: 3 deals, $42K ARR (21%)
Total customer marketing investment (Q2): $18,000 (staff time + ad spend + platform)
Marketing revenue multiple: ($84K sourced + 50% × $70K influenced) = $119K ÷ $18K = 6.6:1

## Success Metrics

A high-quality output from this prompt will:
- Identify at least 8 specific expansion signals with precise trigger thresholds — not vague criteria like "when the customer is healthy"
- Design multi-channel sequences (not just email) where LinkedIn ads, in-app, and CSM-sent emails work together as a coordinated program
- Produce a segmentation model that CSMs can immediately use to prioritize their outreach — the ERS scoring should auto-rank the customer base
- Define clear escalation criteria so marketing and CS don't step on each other's conversations
- Calculate the expected pipeline impact: [# customers with triggers] × [% conversion to expansion opp] × [average expansion ACV] = expansion pipeline projection

**Minimum viable benchmarks for a healthy customer marketing expansion program:**
- Signal trigger rate: 15-25% of customer base has at least one active expansion trigger at any time
- Sequence open rate: ≥ 35% (customer emails open significantly higher than prospect emails — benchmark is 45-55% for healthy programs)
- Expansion opportunity creation rate from triggered sequences: 8-15% of triggered customers create an expansion opportunity
- Marketing-sourced expansion pipeline as % of total NRR: 25-40% (rest is CS-sourced)
- Marketing expansion program ROI: ≥ 5:1 (expansion ARR generated ÷ customer marketing investment)

## Related Prompts

- `../../05_Analytics-&-Performance/Customer-Lifecycle-Marketing-Analytics/AI-Powered-B2B-SaaS-Customer-Expansion-Revenue-Marketing-Analytics-&-Upsell-Cross-Sell-Intelligence-Engine.md` — for measuring the performance of the expansion campaigns this prompt designs
- `../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/AI-Powered-B2B-SaaS-Champion-Nurture-&-Internal-Selling-Email-Intelligence-Engine.md` — for designing the champion development email sequences that feed into expansion campaigns
- `../../05_Analytics-&-Performance/Customer-Lifetime-Value-Analytics/AI-Powered-Net-Revenue-Retention-&-Expansion-Revenue-Intelligence-Engine.md` — for the NRR and CLV analytics framework that sets the revenue targets for expansion programs
- `../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/AI-Powered-B2B-SaaS-Late-Stage-Deal-Rescue-&-Marketing-Assisted-Pipeline-Acceleration-Intelligence-Engine.md` — for high-ACV expansion plays that require ABM-style orchestration rather than automated campaign sequences

## Integration Tips

**Gainsight + HubSpot/Marketo:**
- Create Gainsight Cockpit Alerts that fire when an expansion signal threshold is met; use Gainsight's outbound integration to push the signal to HubSpot as a Contact property update ("Expansion Signal Active = Seat Saturation") that auto-enrolls the contact in the relevant HubSpot expansion workflow
- Build a Gainsight Rule: "If Health Score crosses from Amber to Green AND ERS ≥ 65, create a Gainsight CTA for the CSM labeled 'Expansion Ready — Marketing Sequence Active' and trigger HubSpot enrollment"
- Suppress expansion campaigns for contacts linked to Gainsight red accounts: build a dynamic HubSpot suppression list from Gainsight's Account Health field pushed to HubSpot via native sync

**Salesforce + Marketo:**
- Create a custom Salesforce Object "Customer Expansion Signal" that logs every signal trigger with: Account, Signal Type, Trigger Date, ERS Score at trigger time, and Campaign Enrolled
- Build a Marketo Smart Campaign: trigger = Salesforce "Customer Expansion Signal Created" → add to corresponding Marketo Engagement Program stream; suppression filter = "Account: Open Renewal Opportunity = True" (prevents marketing from running expansion campaigns on accounts already in active renewal negotiations)
- Build a Salesforce report: "Marketing-Sourced Expansion Opportunities" filtered by Opportunity Type = Expansion AND Opportunity Source = Marketing Campaign — this is your board-ready number

**LinkedIn Campaign Manager (Customer Retargeting):**
- Upload your customer contact list to LinkedIn Matched Audiences monthly (minimum list size: 300 contacts for LinkedIn to activate; export from Salesforce by segment)
- Create separate LinkedIn campaigns per expansion motion (Seat Expansion / Tier Upgrade / Cross-Sell) with appropriate ad creative; use frequency caps (5 impressions/week) to avoid annoying existing customers
- Exclude your customer audience from new prospect campaigns — otherwise your ads reach people who are already paying, wasting budget and confusing positioning

**Pendo (In-App Messaging):**
- Build Pendo Guides triggered by feature events: "User triggered all 5 core features this session for 3rd consecutive week" → show contextual in-app banner: "You're our top user — ready to see what [next tier] unlocks?" with a single CTA linking to a customer-specific pricing page
- Tag Pendo Guide interactions in your MAP: Pendo → Zapier → HubSpot/Marketo logs "In-App Expansion Banner Clicked" as an engagement event that can increase lead score or trigger a follow-up email

**Zapier Automation (No-Code Signal Routing):**
- Zapier trigger: New row in Google Sheets (populated by monthly ZoomInfo enrichment export showing headcount changes) → filter for 20%+ growth → create HubSpot task for CSM + enroll contact in Headcount Growth expansion workflow
- Zapier trigger: HubSpot expansion email opened 3+ times without click → Slack notification to CSM: "High open frequency, no click — consider direct outreach. [Contact name, Company, email subject opened]"
- Zapier trigger: Salesforce Opportunity created (Type = Expansion) → Google Sheets row added to expansion pipeline tracker (for marketing attribution dashboard built in Looker Studio)

## Troubleshooting

**Problem:** CSMs are ignoring the Slack alerts and the marketing automation is running expansion campaigns to customers that CSMs are already in commercial conversations with, creating duplicate outreach and buyer confusion.
**Fix:** This is a process failure before it's a technology failure. Run a 30-minute workshop with the CS team showing 3 specific examples of how the system works and what the PAUSE/TAKE OVER override does. Set an expectation that responding to expansion alerts within 24 hours is part of the CSM job scorecard. Technically, add a "Commercial Conversation Open" checkbox field in Salesforce that CSMs update when any expansion/renewal discussion starts — build a dynamic HubSpot suppression list from this field so marketing campaigns automatically stop. The 24-hour CSM response SLA with auto-suppression as a fallback removes the trust issue.

**Problem:** Expansion campaign open rates are high (40%+) but conversion to expansion opportunity is under 3%, suggesting customers are interested but not progressing.
**Fix:** High open rate + low conversion typically means the CTA is wrong or the pricing friction is too high in the email itself. Test two things: (1) Replace "See pricing options" CTAs with "Schedule 15 minutes" — customers often want to talk to a human before committing to even a small expansion, so removing the friction of self-serve pricing from the flow increases conversions even though it adds a step; (2) Add a CSM-sent email as a parallel track (Step 4 in the sequence) that personalizes the expansion message — accounts receiving both automated + CSM emails convert at 2-3x the rate of automated-only sequences.

**Problem:** Marketing can't get clean product usage data to run signal-based campaigns because CS and product teams use different systems that don't sync.
**Fix:** Don't wait for a perfect data architecture. Build a "manual signal" process as a bridge: weekly, pull a simple CSV from your product analytics tool showing top metrics by account (e.g., seat utilization %, last login date, features used) and upload it to Salesforce via a data import. Map three fields to the Account object: Seat Utilization %, Feature Adoption Score, Last Active Date. This takes 2 hours/week and gives marketing enough signal to run segmented campaigns until the native integration is built. Use this manual process to prove revenue impact — that proof case is what gets the API integration prioritized.

## Version History
- v1.0: Initial creation (auto-generated)
