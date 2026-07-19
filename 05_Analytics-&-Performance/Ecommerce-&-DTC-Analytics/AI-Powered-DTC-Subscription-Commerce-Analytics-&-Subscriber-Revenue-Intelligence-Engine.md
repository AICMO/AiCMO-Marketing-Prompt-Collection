# AI-Powered DTC Subscription Commerce Analytics & Subscriber Revenue Intelligence Engine — MRR, Subscriber Churn, Dunning Recovery & Subscription LTV Optimization for Direct-to-Consumer Subscription Brands

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** dtc-subscription, mrr, subscriber-churn, dunning, recharge, ordergroove, skio, subscription-analytics, ltv, pause-behavior, winback, shopify-subscription

## Overview
Transforms raw subscription platform data (Recharge, Bold, Ordergroove, Skio, or native Shopify) into a complete subscriber health and revenue intelligence report: MRR/ARR movement, voluntary vs. involuntary churn root-cause analysis, pause/skip behavior as a leading churn indicator, dunning recovery performance, and subscription LTV by acquisition channel. Use this monthly to understand why subscribers cancel — and exactly which interventions produce the highest revenue-per-subscriber recovery before the economics compound against you.

## Quick Copy-Paste Version

You are a senior DTC subscription commerce analytics strategist specializing in subscriber health, MRR growth, and retention economics for direct-to-consumer subscription brands.

I need a complete subscriber health and revenue intelligence analysis for my subscription brand. Here is our context:

**Brand profile:**
- Brand: [e.g., "Vault Coffee Club — specialty coffee subscriptions, $3.2M MRR, DTC-first on Shopify"]
- Product type: [e.g., "consumable replenishment / subscription box / digital membership / hybrid one-time + subscription"]
- Subscription platform: [Recharge / Bold Subscriptions / Ordergroove / Skio / Stay.ai / Native Shopify / Other]
- Average subscription interval: [e.g., "monthly / every 30 days / every 60 days / custom"]
- Average subscriber billing amount: [$ per interval]
- Reporting period: [e.g., "June 2026 — June 1 through June 30"]

**MRR & revenue snapshot:**
- Beginning MRR (start of period): [$]
- New MRR (new subscribers × billing amount): [$]
- Expansion MRR (upgrades, upsells, interval changes): [$]
- Contraction MRR (downgrades): [$]
- Churned MRR (cancellations × lost ARR): [$]
- Ending MRR: [$]
- Total active subscribers (end of period): [#]
- Net new subscribers this period: [#]

**Subscriber acquisition:**
- New subscribers acquired this period: [#]
- Top acquisition channels (rank by volume): [e.g., "Meta Ads 42%, Organic Social 18%, Email 15%, Google 12%, Influencer 8%, Referral 5%"]
- Average CAC per subscriber by top channel: [$]
- Average first-billing conversion rate (signup → first successful charge): [%]

**Churn breakdown:**
- Total subscribers who cancelled this period: [#]
- Voluntary churn rate: [%] (cancellations initiated by subscriber)
- Involuntary churn rate: [%] (payment failures not recovered)
- Top cancellation reasons from exit survey (rank by frequency): [e.g., "too expensive 38%, product not used 22%, found alternative 15%, skipping too often 12%, quality issue 8%, other 5%"]
- Cancel funnel save rate: [%] (subscribers presented a save offer who accepted)
- Most effective save offer: [e.g., "50% off next box / free skip / subscription pause"]

**Skip & pause behavior (leading churn indicators):**
- Active paused subscribers (end of period): [#]
- Pause rate this period: [% of active base who paused]
- Average pause duration: [days]
- Post-pause churn rate: [% of paused subscribers who cancel within 60 days of returning]
- Subscribers who skipped 1+ order this period: [#]
- Average skips per subscriber per 6 months: [#]
- Correlation between skip frequency and churn: [describe if known, or enter "unknown"]

**Dunning & payment recovery:**
- Failed payment events this period: [#]
- Failed payment rate: [% of renewal attempts that failed]
- Recovery rate from dunning sequence: [% of failed payments ultimately recovered]
- Average days to recovery: [#]
- Revenue recovered through dunning: [$]
- Permanently lost revenue from unrecovered failures: [$]
- Dunning sequence type: [e.g., "retry only / email sequence / SMS alerts / email + SMS / in-app notification"]

**Subscription LTV & cohort data:**
- Average subscriber tenure (current active subscribers): [months]
- LTV at 3 months: [$]
- LTV at 6 months: [$]
- LTV at 12 months: [$]
- LTV at 24 months: [$]
- Prepaid subscribers (annual or multi-month) vs. monthly: [% split]
- LTV difference between prepaid and monthly subscribers: [% or $]

**Winback performance:**
- Winback email/SMS campaigns sent to cancelled subscribers: [#]
- Winback conversion rate: [%]
- Average time between cancel and winback: [days]
- Revenue generated from winbacks this period: [$]

Produce:
1. **Subscriber Health Scorecard** — red/yellow/green ratings across MRR growth rate, voluntary churn, involuntary churn, pause rate, dunning recovery, and LTV trajectory with period-over-period trend arrows
2. **MRR Bridge Analysis** — waterfall breakdown of beginning-to-ending MRR with new/expansion/contraction/churn components and net MRR growth rate vs. industry benchmarks
3. **Churn Root-Cause Diagnostic** — separate voluntary churn (by exit survey reason with weighted impact score) and involuntary churn (dunning failure rate, retry gap, payment method distribution) with priority interventions for each
4. **Pause & Skip Risk Model** — identify at-risk subscriber segments based on pause/skip frequency, calculate projected churn acceleration if left unaddressed, recommend proactive intervention triggers
5. **Dunning Optimization Recommendations** — assess current recovery sequence against best-practice benchmarks, calculate revenue-at-risk from sub-optimal retry timing, and produce an optimized dunning schedule
6. **Channel-Level Subscriber Quality Analysis** — rank acquisition channels by subscriber LTV, churn rate, and first-billing conversion to reveal which channels produce high-value loyal subscribers vs. high-churn discounters
7. **Winback Revenue Opportunity** — size the recoverable revenue in your cancelled subscriber pool, segment by recency and original cancel reason, and recommend a tiered winback sequence with expected revenue recovery
8. **Next 30-Day Subscriber Retention Action Plan** — 5 specific, sequenced interventions with projected MRR impact, implementation effort, and the metric that will confirm success

## Advanced Customizable Version

### Role & Context
You are the VP of Retention Analytics at a high-growth DTC subscription brand. Your monthly subscriber intelligence report is reviewed by the CEO, CFO, Head of Growth, and Head of CX to set subscriber acquisition investment levels, approve retention campaign budgets, and decide whether to adjust subscription pricing or box curation. You operate under a single-minded constraint: every 1% improvement in monthly subscriber churn rate compounds dramatically — at 5,000 subscribers and $50 average billing, cutting churn from 7% to 6% produces an additional $500K in annual MRR without a single new subscriber. Your analysis must be precise, defensible, and tie every metric to a revenue consequence.

---

### Section 1: Brand Profile & Subscription Model

**Brand context:**
- Brand name and one-line description: [Brand | product type | revenue stage]
- Business model type: [replenishment subscription (razors, vitamins, pet food) / curated subscription box (beauty, snacks, lifestyle) / access/membership (digital content, community) / hybrid transactional + subscription]
- Subscription platform: [Recharge / Bold Subscriptions / Ordergroove / Skio / Stay.ai / Native Shopify Subscriptions / Other]
- eCommerce platform: [Shopify / WooCommerce / Magento / Headless]
- Analytics stack: [Triple Whale / Northbeam / Rockerbox / GA4 / Mixpanel / Platform native reporting]
- CRM / retention platform: [Klaviyo / Attentive + Klaviyo / Postscript / Braze / Iterable]
- Reporting period: [Month | Quarter]

**Subscription economics:**
- Current subscription price(s) by tier: [e.g., "Core $29/mo, Pro $49/mo, Family $79/mo"]
- Available subscription frequencies: [e.g., "every 2 weeks / monthly / every 6 weeks / quarterly"]
- COGS per subscription fulfillment: [$]
- Gross margin per subscription: [%]
- Customer acquisition cost (blended, new subscribers only): [$]
- Target LTV:CAC ratio: [e.g., "3:1 at 12 months"]
- Current LTV:CAC ratio (12 months): [actual]

---

### Section 2: MRR Movement & Growth Rate Analytics

**MRR bridge inputs:**
- Beginning MRR: [$]
- New MRR from subscriber activations: [$]
- Expansion MRR (tier upgrades + frequency increases): [$]
- Contraction MRR (tier downgrades + frequency reductions): [$]
- Reactivation MRR (winbacks from cancelled subscribers): [$]
- Churned MRR (voluntary cancellations): [$]
- Involuntary Churned MRR (unrecovered payment failures): [$]
- Ending MRR: [$]

**Growth benchmarks (fill in actuals, AI will benchmark against industry):**
- Net MRR growth rate (MoM %): [%]
- Net subscriber growth rate (MoM %): [%]
- Target MRR growth rate: [%]
- Industry benchmark for your subscription category: [if known, or enter "unknown — please benchmark"]

**MRR analysis required:**
1. Calculate net MRR growth rate and decompose which component (new, expansion, or churn reduction) has the highest marginal impact on hitting target growth rate
2. Identify whether you are in a "growth-first" (new MRR dominates) or "retention-first" (churn reduction has greater ROI) phase given current metrics
3. Model the MRR impact of a 1%, 2%, and 3% improvement in voluntary churn rate using current subscriber base and billing economics
4. Calculate the subscriber acquisition spend required to offset current churn vs. the retention spend required to reduce churn by equivalent MRR — identify the more capital-efficient path

---

### Section 3: Subscriber Churn Deep-Dive

**Voluntary churn analysis:**
- Cancel rate this period: [% of active subscribers who cancelled]
- Cancel survey response rate: [% of cancellers who completed exit survey]
- Exit survey top reasons (by frequency %):
  - Price / too expensive: [%]
  - Product not being used / accumulating: [%]
  - Found a better alternative: [%]
  - Skipping too often / not the right cadence: [%]
  - Product quality or satisfaction issue: [%]
  - Financial hardship: [%]
  - Gifting period ended: [%]
  - Other: [%]
- Cancel page save offer types tested: [e.g., "50% discount, 1 free skip, 3-month pause, product swap"]
- Save offer acceptance rate by type: [e.g., "50% discount: 34% acceptance, skip: 22%, pause: 41%"]

**Involuntary churn analysis:**
- Payment failure rate on renewal charges: [%]
- Card decline types (if available): [e.g., "insufficient funds 41%, expired card 28%, stolen/fraudulent 18%, processor decline 13%"]
- Dunning sequence steps: [describe each retry attempt + communication channel + timing]
- Recovery rate at each dunning step: [% recovered at retry 1, retry 2, email notification, SMS notification, final warning]
- Account updater (Stripe / Braintree card update service) enabled: [Yes / No]
- Revenue permanently lost to involuntary churn this period: [$]

**Churn analysis required:**
1. Decompose voluntary churn root causes into three tiers: price-sensitive (recoverable with save offers), product-fit (recoverable with product swap or cadence change), and irrecoverable (gifting end, moving, financial hardship)
2. Calculate the monetary value of each voluntary churn reason and prioritize interventions by revenue impact
3. For involuntary churn: benchmark current recovery rate against 70%+ best practice, identify which dunning step has the highest drop-off, and model revenue recovered by adding one optimized retry or communication
4. Recommend specific cancel-flow save offer sequences tailored to top churn reasons with expected acceptance rates based on industry benchmarks

---

### Section 4: Skip & Pause Behavior as Leading Churn Indicators

**Behavioral data:**
- Total active paused subscriptions (end of period): [#]
- Pause rate (new pauses / active base): [%]
- Average pause duration: [days]
- Maximum pause duration allowed: [days]
- Subscribers who resumed after pause: [#]
- Post-pause 60-day churn rate: [%]
- Total skip events this period: [#]
- Subscribers who skipped 1 order: [#]
- Subscribers who skipped 2+ orders: [#]
- Average orders skipped per subscriber per 6-month window: [#]
- Skip rate MoM trend: [Increasing / Stable / Decreasing]

**Behavioral analysis required:**
1. Build a subscriber risk segmentation model based on pause and skip behavior:
   - Tier 1 (High Risk): [subscribers paused 60+ days OR skipped 3+ times in 6 months]
   - Tier 2 (Medium Risk): [subscribers paused 30–60 days OR skipped 2 times in 6 months]
   - Tier 3 (Low Risk): [no skips/pauses OR 1 skip in 6 months]
2. Calculate the projected 90-day churn rate for each risk tier based on historical cohort data (or request benchmarks if unknown)
3. Calculate the MRR at risk from Tier 1 and Tier 2 subscribers
4. Design a proactive intervention sequence for each risk tier: what trigger fires, what message is sent (email/SMS/in-app), what offer is made, and what success metric is tracked

---

### Section 5: Subscription LTV by Acquisition Channel & Cohort

**Cohort & channel data:**
- LTV by acquisition channel (12-month, if available):
  - Meta Ads subscribers: [$]
  - Google Ads subscribers: [$]
  - TikTok Ads subscribers: [$]
  - Organic Social subscribers: [$]
  - Email / Referral subscribers: [$]
  - Influencer / Creator subscribers: [$]
- Average retention rate at Month 1, 3, 6, 12 for most recent 12 cohorts: [% or "unavailable"]
- LTV difference between prepaid (annual/biannual) and monthly subscribers: [$]
- % of subscriber base on prepaid plans: [%]

**LTV & channel analysis required:**
1. Rank acquisition channels by 12-month subscriber LTV and calculate LTV:CAC ratio per channel — identify channels where subscriber LTV justifies higher CAC bids
2. Flag any channels producing subscribers with first-billing conversion rate below 85% (potential sign of incentive misalignment or discount-driven subscriber quality)
3. Model the revenue impact of converting an additional 5% of monthly subscribers to prepaid plans — what offer and framing maximizes prepaid conversion without cannibalizing new subscriber acquisition
4. Identify the cohort month with the highest 90-day churn cliff and design a specific intervention to address the root cause at that inflection point

---

### Section 6: Dunning Optimization & Payment Recovery

**Current dunning configuration:**
- Billing system: [Recharge / Stripe / Braintree / Other]
- Account updater service enabled: [Yes / No]
- Retry schedule (list all attempts with timing): [e.g., "Day 0 (initial failure), Day 3 (retry 1), Day 5 (email), Day 7 (retry 2), Day 10 (SMS), Day 14 (final email + retry 3)"]
- Smart retry (random time / intelligent retry) enabled: [Yes / No]
- Communication channels used in dunning: [Email only / Email + SMS / Email + SMS + in-app]

**Recovery analysis required:**
1. Benchmark current dunning recovery rate against best-practice subscription industry standards (70%+ for mature programs)
2. Calculate the additional revenue recoverable by: (a) enabling account updater if not active, (b) adding one SMS touchpoint to current email-only sequence, (c) implementing smart retry timing vs. fixed retry schedule
3. Identify the optimal dunning sequence architecture for this brand's business model and billing interval — produce a specific step-by-step recommendation with timing, channel, and message type at each step
4. Model the annual revenue impact of improving dunning recovery rate from current level to 70%

---

### Section 7: Winback Program Analytics & Optimization

**Winback data:**
- Cancelled subscriber pool size (total addressable winback audience): [#]
- Cancelled in last 30 days: [#]
- Cancelled 31–90 days ago: [#]
- Cancelled 91–180 days ago: [#]
- Cancelled 180+ days ago: [#]
- Winback campaigns sent this period: [# of sends, # of unique cancelled subscribers reached]
- Winback conversion rate (cancelled → reactivated): [%]
- Average time from cancel to reactivation: [days]
- Top reactivation offers used: [e.g., "50% off first box back, free product add-on, no-commitment restart"]
- Revenue from reactivations this period: [$]

**Winback analysis required:**
1. Segment the cancelled subscriber pool by recency, cancel reason (if captured), and original acquisition channel — identify highest-probability winback segments
2. Calculate the expected revenue from a structured 3-tier winback sequence targeting 30-day, 60-day, and 90–180-day lapsed subscribers with segment-appropriate offers
3. Design the specific winback messaging framework for top churn reasons:
   - "Too expensive" canceller: [retention offer + messaging frame]
   - "Accumulating product" canceller: [cadence adjustment + messaging frame]
   - "Found alternative" canceller: [competitive repositioning + proof point + messaging frame]
4. Model the annual winback revenue potential if current winback conversion rate is improved by 3 percentage points

---

### Output Requirements

Produce the following deliverables in sequence:

**1. Executive Subscriber Health Scorecard**
A one-page dashboard with red/yellow/green ratings for:
- Net MRR growth rate (target vs. actual)
- Voluntary churn rate (benchmark vs. actual)
- Involuntary churn rate (benchmark vs. actual)
- Dunning recovery rate (benchmark vs. actual)
- Pause/skip risk index (% of base in Tier 1 or Tier 2 risk)
- 12-month subscriber LTV vs. target
- LTV:CAC ratio vs. target

Each metric includes: current value | prior period | period-over-period change | status (green/yellow/red)

**2. MRR Bridge & Growth Narrative**
A waterfall analysis of MRR movement with the single most impactful lever for hitting the next 10% MRR growth milestone.

**3. Churn Root-Cause Report**
Separate voluntary and involuntary churn into prioritized root causes with:
- Revenue impact of each cause ($ MRR at risk)
- Intervention recommendation with expected recovery rate
- Implementation priority (this week / this month / next quarter)

**4. At-Risk Subscriber Intervention Playbook**
For each behavioral risk tier, a specific 3-step intervention sequence:
- Trigger (what behavior fires the sequence)
- Message 1: channel, timing, content, offer
- Message 2: channel, timing, content, offer
- Message 3: channel, timing, content, offer
- Success metric and threshold

**5. Channel-Level Subscriber Quality Matrix**
Table ranking acquisition channels by: CAC | 12-month LTV | LTV:CAC | first-billing conversion | 90-day churn rate | recommendation (scale / hold / reduce / test)

**6. 30-Day Subscriber Revenue Recovery Action Plan**
Five specific actions ranked by: projected MRR impact | implementation effort | who owns it | success metric
Format: Action → Expected MRR Impact → Owner → Success Metric → Deadline

## Example Input/Output

### Example Input

**Brand profile:**
- Brand: Vitalis Daily — premium adaptogen supplement subscription, $1.8M MRR, Shopify + Recharge
- Product type: Consumable replenishment subscription (monthly 30-day supply)
- Subscription platform: Recharge
- Average billing: $68/month
- Reporting period: June 2026

**MRR snapshot:**
- Beginning MRR: $1,780,000
- New MRR: $96,000 (1,412 new subscribers × $68)
- Expansion MRR: $11,200 (upgrades to 2-product bundles)
- Contraction MRR: -$4,400 (downgrades)
- Churned MRR: -$107,000 (1,573 voluntary cancellations × $68)
- Involuntary Churned MRR: -$34,000 (500 unrecovered payment failures × $68)
- Ending MRR: $1,741,800

**Churn data:**
- Voluntary churn rate: 5.9%
- Top cancel reasons: Too expensive 41%, Accumulating/not using 28%, Found alternative 17%, Other 14%
- Save offer acceptance: Pause 38%, 50% discount 29%, Skip 18%

**Dunning:**
- Failed payment rate: 8.2%
- Recovery rate: 54%
- Current dunning: Retry Day 3, email Day 5, retry Day 7, email Day 14

**Skip/pause:**
- Paused subscribers: 412 (1.6% of base)
- Subscribers with 2+ skips: 1,890 (7.3% of base)
- Post-pause 60-day churn: 31%

### Example Output (Excerpt)

**Executive Health Scorecard — June 2026**

| Metric | Actual | Benchmark | Status | MoM |
|--------|--------|-----------|--------|-----|
| Net MRR Growth | -2.1% | +3–5%/mo | 🔴 | ↓ |
| Voluntary Churn | 5.9% | 3–5% | 🟡 | → |
| Involuntary Churn | 3.8% | 1–2% | 🔴 | → |
| Dunning Recovery | 54% | 70%+ | 🔴 | → |
| Pause/Skip Risk | 8.9% in Tier 1–2 | <5% | 🟡 | ↑ |
| 12-mo LTV | $612 | $680 target | 🟡 | → |
| LTV:CAC | 2.4:1 | 3:1 target | 🟡 | ↓ |

**Highest-Priority Finding:** Involuntary churn (unrecovered payment failures) is the single largest recoverable revenue leak. Vitalis is losing $34K MRR per month to failed payments — but only recovering 54% vs. the 70%+ benchmark. Closing this gap alone recovers $8,500 MRR ($102K ARR) before touching a single acquisition campaign.

**Immediate Action 1: Enable Account Updater + Optimize Dunning Sequence**
Current dunning: 2 retries, 2 emails. Gap: No SMS touchpoint. No intelligent retry timing. No account updater.

Recommended optimized sequence:
- Day 0: Failed payment detected → Account Updater request (Stripe/Braintree auto-updates card — recovers ~15% of failures before any outreach)
- Day 1: Email "Uh oh, your shipment is on hold" — soft tone, card update CTA
- Day 2: SMS "Quick fix needed for your Vitalis order" — direct link to update payment
- Day 3: Smart retry (attempt at 9 AM local, highest approval time) 
- Day 5: Email "Last chance before we pause your membership" — urgency
- Day 7: Final retry + email "Your membership is about to expire"

Expected recovery improvement: 54% → 68% → additional $4,760 MRR recovered per month ($57K ARR annually)

**Churn Root-Cause Priority Matrix:**
1. "Too expensive" (41% of cancels, $43,900 MRR impact): Pause offer is most effective save (38% acceptance) — move pause offer to front of cancel flow before pricing conversation. Expected save improvement: +6 percentage points → $2,600/month recovered
2. "Accumulating/not using" (28% of cancels, $29,960 MRR impact): Cadence switch to every-45-days converts 31% of this segment vs. 12% discount offer — prioritize frequency adjustment as primary save offer for this segment
3. At-Risk Skip Cohort (1,890 subscribers with 2+ skips, $128,520 MRR at risk): 31% post-pause churn rate signals these subscribers are 6–8 weeks from voluntary cancel. Trigger a proactive intervention at the 2nd skip event rather than waiting for cancel intent.

## Success Metrics

A high-quality output from this prompt should produce:

- **MRR bridge accuracy**: All MRR components sum correctly to ending MRR with no arithmetic errors
- **Benchmark contextualization**: Every key metric includes an industry benchmark comparison (voluntary churn 3–7%, involuntary churn 1–2%, dunning recovery 65–75%, LTV:CAC 3:1+ at 12 months)
- **Revenue quantification**: Every insight has a dollar value attached (not "high churn is bad" but "$34K MRR lost to payment failures = $408K ARR opportunity")
- **Behavioral intervention specificity**: Skip/pause interventions specify exact trigger, channel, timing, message content, and offer — not generic "send a winback email"
- **Channel quality differentiation**: Subscriber LTV varies meaningfully by acquisition channel — the output should reveal which channels produce high-LTV loyalists vs. discount-seekers
- **30-day action plan sequencing**: Actions are prioritized by revenue impact, not ease — if dunning optimization recovers more MRR than a new winback campaign, it appears first

## Related Prompts

- [AI-Powered DTC Ecommerce Revenue Analytics & Customer Acquisition Retention Intelligence Engine](./AI-Powered-DTC-Ecommerce-Revenue-Analytics-&-Customer-Acquisition-Retention-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Predictive Churn Intelligence & Marketing-Led Retention Revenue Recovery Analytics Engine](../Churn-Prevention-&-Retention-Analytics/AI-Powered-B2B-SaaS-Predictive-Churn-Intelligence-&-Marketing-Led-Retention-Revenue-Recovery-Analytics-Engine.md)
- [AI-Powered DTC Subscription Commerce Subscriber Acquisition, Activation & Churn Reduction Revenue Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/AI-Powered-DTC-Subscription-Commerce-Subscriber-Acquisition-Activation-&-Churn-Reduction-Revenue-Intelligence-Engine.md)
- [Customer Lifetime Value Prediction & Acquisition Investment Intelligence Engine](../Customer-Lifetime-Value-Analytics/Customer-Lifetime-Value-Prediction-&-Acquisition-Investment-Intelligence-Engine.md)

## Integration Tips

**Recharge / Skio / Ordergroove:**
- Export the "Subscriptions" report filtered to active + cancelled for the period — map cancel reasons to the churn taxonomy in Section 3
- Pull the Dunning Analytics report (Recharge: Analytics → Dunning) to populate payment failure and recovery rates in Section 6
- Use the Cohort Analysis export (if available) to populate LTV by signup month in Section 5

**Klaviyo / Attentive:**
- Tag all subscription-triggered flows (welcome, skip-saved, pause-saved, dunning, winback) separately from transactional campaigns — this allows flow-level revenue attribution in the output
- Export the "Subscriber List Growth" report with opt-in source to cross-reference with acquisition channel LTV in Section 5
- Set up a Segment for "2+ skips in last 90 days" and "currently paused 30+ days" — feed these into the at-risk playbook interventions

**Triple Whale / Northbeam / Rockerbox:**
- Use the New Customer Revenue report filtered to "subscription first order" vs. "one-time purchase" to compare subscriber acquisition cost by channel
- If the attribution tool supports cohort LTV, export subscriber-specific cohorts vs. one-time buyer cohorts to validate channel quality differences

**Google Sheets / Notion / Hex:**
- Build an MRR bridge waterfall using this prompt's output as the data skeleton — pin it to a dashboard the CEO and CFO review weekly
- The subscriber health scorecard maps directly to a Notion database with green/yellow/red status properties — useful for tracking metric movement over consecutive months

**Zapier / Make (Automation):**
- Trigger a Slack alert when voluntary churn rate exceeds 6% for two consecutive months (using Recharge webhook → Zapier → Slack)
- Automatically enroll new-pause subscribers into the at-risk Klaviyo flow using a Recharge webhook that fires when a subscriber changes status to "paused"

## Troubleshooting

**Problem: Skip/pause data not available from subscription platform**
If your subscription platform (e.g., older Bold configurations) doesn't export skip/pause event data, use proxy signals instead: (a) track "subscription skipped" as a custom Klaviyo event via platform API, (b) look for subscribers whose order frequency dropped by 30%+ vs. their historical cadence, (c) survey subscribers who have gone 45+ days past their expected order date. Even rough behavioral segmentation outperforms no intervention.

**Problem: Cancel survey response rate is below 40%, making exit data unreliable**
With low survey response rates, supplement exit data by: (a) analyzing the save-offer acceptance rate by offer type as a proxy for cancel reason (subscribers accepting a cadence change are primarily "accumulating" cancellers, those accepting discounts are "price-sensitive"), (b) pulling cancel timing relative to order delivery (cancellations within 7 days of delivery often signal product dissatisfaction vs. cancellations mid-cycle which suggest price or accumulation), (c) running a 200-subscriber sample call campaign to manually gather churn reasons.

**Problem: LTV data is unavailable beyond 3 months because the brand is less than 12 months old**
For brands with less than 12 months of cohort data: (a) use 3-month LTV × an industry-standard retention curve for your product category (consumables typically retain 45–55% of subscribers at 12 months, boxes retain 35–45%), (b) flag all 12-month LTV figures as projected and note the confidence interval, (c) focus the analysis on metrics you can measure accurately (MRR bridge, dunning recovery, pause rate) and set explicit review checkpoints at Month 6 and Month 9 to validate projections.

## Version History
- v1.0: Initial creation (auto-generated)
