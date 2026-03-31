# AI-Powered DTC & E-Commerce Cart Abandonment Recovery & Post-Purchase Revenue Expansion Intelligence Engine

**Difficulty:** Advanced | **Time:** 20 min | **Tags:** dtc, ecommerce, retention, email, sms, automation, revenue-recovery, post-purchase, personalization

## Overview
This engine designs and executes a full multi-channel cart abandonment recovery and post-purchase upsell/cross-sell system—using AI to segment abandoners by intent signals, personalize recovery sequences by product category and price point, and orchestrate follow-up flows that maximize recovered revenue and 90-day LTV. Use it when you're leaving money on the table from high abandonment rates or when post-purchase revenue per customer is below industry benchmarks.

## Quick Copy-Paste Version

You are an expert DTC e-commerce revenue recovery specialist. Analyze this abandoned cart scenario and build a complete recovery system.

BRAND: [Your Brand Name]
PRODUCT CATEGORY: [e.g., skincare, apparel, supplements, home goods]
AVERAGE ORDER VALUE: $[X]
CART ABANDONMENT RATE: [X]% (industry avg: 70%)
CURRENT RECOVERY RATE: [X]% (industry avg: 5-8%)
TOP ABANDONMENT REASON: [price, distraction, shipping cost, comparison shopping]

Build me:

1. A 5-touch cart abandonment sequence (Email x3, SMS x2) with exact send times, subject lines, and message copy for each touchpoint using: urgency at T+1hr, social proof at T+4hr, incentive reveal at T+24hr, FOMO at T+72hr, and final offer at T+7d

2. A post-purchase expansion sequence (3 emails + 1 SMS) timed to maximize repurchase and AOV lift: thank you/cross-sell at T+1d, usage tips/upsell at T+7d, review request at T+14d, replenishment/loyalty at T+30d

3. Retargeting ad brief for Meta and Google (Dynamic Product Ads + Search Remarketing) to run alongside the email/SMS sequences, with audience exclusion logic

4. A/B test recommendations: 3 hypotheses ranked by expected revenue impact

For each touchpoint include: subject line, preview text, hero copy (2-3 sentences), CTA, and personalization tokens.

Use psychological principles: scarcity (genuine stock limits), social proof (review counts/star ratings), loss aversion, and reciprocity for the incentive reveal.

Output everything in a structured format I can paste directly into Klaviyo, Attentive, and Meta Ads Manager.

## Advanced Customizable Version

ROLE: You are a senior DTC growth strategist with deep expertise in e-commerce revenue recovery, behavioral email marketing, and AI-powered personalization. You have recovered $50M+ in abandoned cart revenue across beauty, apparel, supplements, and home goods brands.

BRAND CONTEXT:
- Brand: [Brand Name]
- Category: [Product category]
- Price tier: [Budget / Mid-market / Premium / Luxury]
- AOV: $[X] | Cart value range: $[min]-$[max]
- Top SKUs abandoned: [SKU 1, SKU 2, SKU 3]
- Customer segments: [New visitor / Returning customer / Loyalty member / Lapsed customer]
- Primary abandonment reasons (from exit surveys/heatmaps): [List top 3]
- Current martech: [e.g., Klaviyo + Attentive + Shopify + Meta CAPI]

OBJECTIVE: Design a full-funnel revenue recovery and post-purchase expansion system that: (1) recovers 12-18% of abandoned carts (vs industry avg 5-8%), (2) increases 90-day LTV by 25%+ through intelligent post-purchase sequencing, (3) operates fully autonomously via AI agent with zero manual intervention.

PART 1: ABANDONMENT INTENT SEGMENTATION
Classify abandoners into 4 tiers based on behavioral signals:
- Tier 1 (High Intent): Multiple sessions, product page >90s, cart value >1.5x AOV → Personalized 1:1 recovery
- Tier 2 (Medium Intent): Single session, 30-90s on product, cart value = AOV → Social proof + urgency
- Tier 3 (Low Intent): Bounce after add-to-cart, cart value <0.5x AOV → Broad discount + ease friction
- Tier 4 (Browse Abandon): Viewed product, never added to cart → Retargeting only, no email/SMS
For each tier, define: sequence variation, incentive level (none / free shipping / 5% / 10-15%), and channel priority (email-first vs SMS-first)

PART 2: MULTI-CHANNEL RECOVERY SEQUENCES
For each abandonment tier, create:

EMAIL SEQUENCE (3 emails per tier):
- Email 1 (T+1 hour): Subject line A/B options (3 variants), preview text, hero headline, body copy using [Tier-specific angle: urgency/social proof/discount], product image guidance, CTA copy + color psychology rationale, mobile optimization notes
- Email 2 (T+4-6 hours): Shift angle to [social proof: X,XXX customers love this / review highlights], include UGC image guidance, FAQ block addressing top 3 objections, secondary CTA for "view full collection"
- Email 3 (T+24 hours): Incentive reveal (tier-appropriate), scarcity signal ("Only X left in your size/shade"), countdown timer guidance, urgency-stacked CTA

SMS SEQUENCE (2 messages per tier):
- SMS 1 (T+2 hours): 160-char max, direct link, one hook (urgency OR social proof)
- SMS 2 (T+48 hours): Incentive + deadline ("Expires tonight"), opt-out language compliant

PART 3: POST-PURCHASE EXPANSION FLOWS
Design a 4-touch post-purchase sequence to maximize 90-day LTV:

Email 1 - Thank You + Cross-Sell (T+1 day post-purchase):
- Emotional thank you + brand story reinforcement
- "Frequently bought together" engine: recommend [2-3 complementary SKUs based on purchased item]
- Early loyalty program CTA if applicable

Email 2 - Usage/Education + Upsell (T+7 days):
- Product tips that increase perceived value (reduces returns + builds habit)
- Upsell to higher-tier SKU or bundle with [X]% first-purchase loyalty discount
- "How to get the most out of [Product]" content block

Email 3 - Review Request + Social Proof Generation (T+14 days):
- Review request with photo/video UGC incentive ($[X] store credit)
- Include referral CTA: "Share with a friend, get $[X] each"

Email 4 - Replenishment / Subscription Pitch / Loyalty Tier (T+30-45 days based on product consumption cycle):
- For consumables: "Time to reorder?" + Subscribe & Save upsell
- For non-consumables: Seasonal/collection new arrival preview
- Loyalty tier progress bar if program exists

PART 4: PAID RETARGETING BRIEF
Meta Dynamic Product Ads:
- Audience: Cart abandoners by tier (Tier 1: 1-day LAL, Tier 2: 7-day, Tier 3: 30-day)
- Exclusions: Purchasers (rolling 30-day), current email sequence enrollees (suppress to avoid message conflict)
- Creative brief: UGC-style video (hook: problem they were solving) + static image carousel
- Bid strategy by tier: Tier 1 = highest value/ROAS target, Tier 3 = volume/CPA target
- Frequency cap: Max 7 impressions/7 days per user

Google Search Remarketing:
- RLSA campaign targeting abandoners searching [brand name + product category keywords]
- Bid adjustment: +40-60% for Tier 1 cart abandoners
- Ad copy variant emphasizing: "Still interested? [Benefit] + [Urgency signal]"

PART 5: A/B TEST ROADMAP
Generate 5 A/B test hypotheses ranked by expected revenue impact:
For each test include: hypothesis, variant A vs B, segment to test on, success metric, minimum sample size for statistical significance (90% confidence), estimated timeline to results

PART 6: KLAVIYO IMPLEMENTATION GUIDE
- Flow architecture diagram (text-based)
- Trigger events and filter logic
- Conditional splits (segment-based branching)
- Smart Send Time vs Fixed Time recommendation by email
- UTM parameter structure for attribution
- Suppression lists to manage

OUTPUT FORMAT: Structured markdown with headers for each part. All copy should be ready to paste into Klaviyo. Flag any personalization tokens that require custom property setup.

## Example Input/Output

**Input Example:**
Brand: Luminos Skincare
Category: Premium skincare (serums, moisturizers)
AOV: $87 | Cart value range: $45-$220
Top SKUs abandoned: Vitamin C Serum ($65), Retinol Night Cream ($72), Starter Kit Bundle ($110)
Abandonment reasons: Shipping cost (42%), "thinking about it" (31%), price (27%)
Current martech: Klaviyo + Attentive + Shopify Plus + Meta CAPI
Current recovery rate: 4.2%

**Output Example (Tier 1 Cart Abandonment, Email 1):**

*Subject Line Options:*
- A: "Your Vitamin C Serum is selling out (we saved it for you)"
- B: "Lea, your cart has 4,327 other admirers"
- C: "Don't let your skin wait"

*Preview Text:* "Free shipping on orders over $75 → you're $10 away"

*Hero Headline:* "Your glow-up is one click away."

*Body Copy:*
"You left something behind—and so did your skin. Your Vitamin C Serum is reserved in your cart, but we can't hold it forever. Over 12,400 Luminos customers call this their 'can't-live-without' morning essential. We've also unlocked free shipping on your order: add just $10 more and your entire cart ships free."

*CTA:* "Complete My Order → Free Shipping Unlocked"

*Personalization tokens required:* `{{ person.first_name }}`, `{{ cart.items[0].product_title }}`, `{{ cart.total_price }}`, `{{ cart.url }}`

---

**SMS 1 (T+2 hours, Tier 1):**
"Your Vitamin C Serum is almost gone 🔥 47 people are eyeing your cart. Complete your order + unlock free shipping: [link] Reply STOP to opt out"

---

**Email 3 — Incentive Reveal (T+24 hours):**
*Subject:* "Last chance: 10% off expires at midnight (just for you)"
*Preview:* "Only 3 serums left in your cart size"

*Body Copy:*
"We don't do this often. As a first-time Luminos customer, we're offering you 10% off your cart—tonight only. This isn't a generic coupon. It's a one-time offer reserved specifically for your order. Your Vitamin C Serum: only 3 bottles remain in stock.

Use code: **LUMINOS10** at checkout. Expires at 11:59 PM tonight."

*CTA:* "Claim 10% Off → Expires Tonight"

---

**Post-Purchase Email 2 (T+7 days, Vitamin C Serum purchaser):**
*Subject:* "Week 1 with your Serum: here's what to expect"
*Body:* "Day 1-7: You may notice mild tingling—that's the Vitamin C activating. By Day 14-21, most customers see visible brightening. Week 4: Full glow. To accelerate your results, 73% of Vitamin C users also add our Hyaluronic Acid Serum. It locks in the C and boosts absorption by 40%."

*Upsell CTA:* "Add Hyaluronic Acid — 15% Off This Week Only → $49 (was $58)"

---

**A/B Test Priority #1:**
- Hypothesis: Revealing free shipping threshold in Email 1 increases recovery rate by 15-20% for carts $55-$74 (within $10-$20 of free shipping threshold)
- Variant A: Standard urgency Email 1
- Variant B: Email 1 with dynamic "You're $X away from free shipping" banner
- Segment: Tier 1 + Tier 2 abandoners with cart $55-$74
- Metric: Cart recovery rate + AOV of recovered orders
- Sample needed: 400 per variant | Estimated timeline: 3-4 weeks

## Success Metrics
- **Primary:** Cart recovery rate (target: 12-18% vs baseline 4-8%)
- **Revenue impact:** Monthly recovered revenue = (monthly abandons × recovery rate lift × AOV)
- **Post-purchase LTV:** 90-day repeat purchase rate (target: 35-45% from post-purchase flow vs 15-20% control)
- **Email metrics:** Email 1 open rate >45%, click rate >12%; SMS click rate >18%
- **Incentive efficiency:** Cost of discount/incentive vs incremental revenue recovered (target: 10:1 ROI)
- **Suppression health:** Unsubscribe rate <0.3% per send; SMS opt-out rate <1.5% per send
- **A/B test velocity:** Minimum 1 validated test per 30 days, compounding 2-3% recovery rate improvements

## Related Prompts
- [`../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/AI-Powered-DTC-Brand-Performance-Marketing-Flywheel-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/AI-Powered-DTC-Brand-Performance-Marketing-Flywheel-Intelligence-Engine.md)
- [`../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/AI-Powered-DTC-Customer-Loyalty-&-Rewards-Program-Revenue-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/AI-Powered-DTC-Customer-Loyalty-&-Rewards-Program-Revenue-Intelligence-Engine.md)
- [`../../03_Content-&-Creative/Email-Marketing/DTC-E-Commerce-Email-Lifecycle-&-Revenue-Automation-Engine.md`](../../03_Content-&-Creative/Email-Marketing/DTC-E-Commerce-Email-Lifecycle-&-Revenue-Automation-Engine.md)
- [`../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/SMS-&-WhatsApp-Conversational-Marketing-Automation-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/SMS-&-WhatsApp-Conversational-Marketing-Automation-Engine.md)

## Integration Tips

**Klaviyo (Email + SMS):**
- Build abandonment flow with trigger: "Started Checkout" → filter "Has Not Placed Order Since Starting Flow"
- Use conditional splits on `cart_value` and `customer_is_new_or_returning` to branch into tier-appropriate sequences
- Enable Smart Send Time for Email 2 and 3 only; use fixed timing for Email 1 (speed matters)
- Set up custom properties: `abandonment_tier`, `cart_product_category`, `days_since_last_order` for personalization

**Attentive (SMS):**
- Map to Klaviyo via Attentive's native integration or Zapier webhook on "Started Checkout" event
- Use Attentive's Concierge feature to respond to SMS replies that indicate purchase intent ("how much is shipping?")
- Suppress SMS sends for users who opened recovery Email 1 within 30 minutes (reduce message fatigue)

**Meta CAPI (Retargeting):**
- Pass `AddToCart` + `InitiateCheckout` events via Conversions API for cookieless attribution
- Create Custom Audiences: Tiered abandonment windows (1d, 3d, 7d) with purchase exclusions
- Use Advantage+ Catalog Ads with overlay text rules: "$10 to free shipping" for Tier 2-3

**Shopify Plus / Flow:**
- Trigger Klaviyo enrollment via Shopify Flow when `checkout.abandoned_at` fires
- Use Flow to tag customers with `abandonment_tier` based on cart value and session depth from Hotjar/Heatmap data
- Pass `cart_line_items` array to Klaviyo for dynamic product block rendering

**Google Analytics 4:**
- Create conversion event: `purchase_from_recovery_flow` with UTM `source=klaviyo&medium=email&campaign=cart-recovery-tier[1-3]`
- Build funnel exploration: Abandoned Checkout → Recovery Email Open → Recovery Email Click → Purchase

## Troubleshooting

**Issue: Recovery rate stuck below 5% despite sending all 3 emails**
*Solution:* Audit deliverability first—check sender reputation (target: spam rate <0.1% in Google Postmaster), preview text rendering on mobile (62% of opens are mobile), and whether Email 1 is arriving within 60 minutes. Most brands see 60% of recoveries happen within the first 2 hours; delays kill conversion. Also audit your checkout flow: if the cart URL in the email goes to a dead session, users can't recover easily. Use persistent cart tokens in Shopify.

**Issue: High SMS opt-out rates (>2%) from recovery texts**
*Solution:* Suppress SMS sends for users already enrolled in email recovery flow AND who opened Email 1 within 4 hours. Over-messaging a high-intent user who is already reading your emails will drive opt-outs without adding revenue. Reserve SMS for users who did NOT open Email 1 by T+2 hours. Also ensure SMS tone is conversational and not robotic—add a human name ("– Emma from Luminos") to increase trust and reduce opt-outs by ~30%.

**Issue: Post-purchase email 2 (upsell) has low click rate (<3%)**
*Solution:* The upsell is too early or too generic. Check two things: (1) Is the product recommendation actually complementary, or is it a best-seller shoehorn? Use purchase co-occurrence data (Shopify Analytics or Glew.io) to find actual "frequently bought together" pairs. (2) Is the email arriving before the customer has received/used the product? For beauty and supplements, delay Email 2 to T+10-12 days so the customer has experience to make an informed second purchase decision.

## Version History
- v1.0: Initial creation (auto-generated)
