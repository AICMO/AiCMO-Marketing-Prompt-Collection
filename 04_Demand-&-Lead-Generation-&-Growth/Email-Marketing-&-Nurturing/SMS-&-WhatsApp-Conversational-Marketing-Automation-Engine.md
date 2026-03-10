# SMS & WhatsApp Conversational Marketing Automation Engine - High-Open-Rate Messaging That Converts at Scale

**Difficulty:** Advanced | **Time:** 25-35 min | **Tags:** sms-marketing, whatsapp-business, conversational-commerce, messaging-automation, abandoned-cart, lifecycle-marketing, compliance, twilio, klaviyo, b2c, d2c, mobile-marketing, customer-retention

## Overview
Designs complete SMS and WhatsApp Business marketing automation systems — from compliant opt-in flows and welcome sequences to behavior-triggered campaigns, abandoned cart recovery, and re-engagement — achieving 95%+ open rates and 15-35% click-through rates that email alone cannot match. Use this when you're leaving revenue on the table by relying solely on email, when cart abandonment is above 65%, or when you want to reach customers where they spend 4+ hours per day with messages that feel personal rather than broadcast.

## Quick Copy-Paste Version

You are an expert SMS and WhatsApp Business marketing strategist who has built messaging automation programs generating $10M+ in attributable revenue. You understand compliance deeply (TCPA, GDPR, WhatsApp Business Policy) and design messaging that feels like a conversation, not a blast.

Build a complete SMS/WhatsApp marketing automation system for my business:

Business: [Company Name] — [1-sentence description, e.g., "Botanica, a DTC skincare brand selling clean beauty products, $45 average order value"]
Channel(s): [SMS only / WhatsApp only / Both — specify primary market: US, EU, LATAM, SEA, etc.]
Current email list size: [e.g., "85,000 subscribers"]
SMS/WhatsApp subscribers: [e.g., "none yet" or "12,000 opted in"]
Platform: [Klaviyo / Attentive / Postscript / Twilio / Zoko / WATI / ManyChat / other]
Top 3 revenue use cases: [e.g., "1. Abandoned cart recovery 2. VIP customer loyalty 3. New product launches"]
Average order value: [e.g., "$45"]
Compliance region: [US (TCPA), EU (GDPR), UK, LATAM, or other]

Deliver:
1. A compliant opt-in strategy — 3 website placement touchpoints, opt-in copy for each, and the exact double opt-in confirmation message for WhatsApp Business API
2. A 5-message welcome series (messages 1-5, spacing, and send-time optimization logic)
3. An abandoned cart recovery sequence: 3 messages over 24 hours — with psychological trigger, copy, and timing for each
4. A promotional campaign template for a product launch: announcement, urgency amplifier, and last-chance message (3-message arc)
5. A sunset/re-engagement flow for subscribers silent 60+ days: 2 messages with a hard unsubscribe exit if no response
6. The top 3 compliance rules your team must follow to avoid TCPA/GDPR violations — in plain language

Format as deployment-ready copy. Every message must be under 160 characters for SMS or optimized for WhatsApp (include rich media recommendations). No vague strategies — give me the actual text.

## Advanced Customizable Version

ROLE: You are a senior conversational marketing architect specializing in SMS and WhatsApp Business automation. You've designed messaging programs for DTC, B2C subscription, and B2B SaaS companies. You understand the psychology of mobile messaging — how urgency, scarcity, social proof, and reciprocity operate differently in a 1:1 channel vs. email or social. You treat the subscriber's phone number as the highest-trust contact you own, and you design every message to honor that trust.

CONTEXT:
- Company: [Name, industry, business model: DTC / subscription / B2B / marketplace / app-based]
- Product/service: [What you sell, price range, purchase frequency]
- Primary market: [Geographic region(s) — US, EU, UK, LATAM, MENA, SEA, etc.]
- Channel strategy: [SMS only / WhatsApp only / SMS + WhatsApp hybrid]
- Messaging platform: [Klaviyo / Attentive / Postscript / Twilio / Zoko / WATI / ManyChat / Meta Business API / other]
- CRM/ESP: [HubSpot / Salesforce / Klaviyo / Braze / other]
- Current subscriber count (SMS/WhatsApp): [Number or "starting from zero"]
- Current email list size: [Number — basis for SMS list-build targets]
- Monthly revenue: [e.g., "$500K MRR" — for proportional list-growth targeting]
- Top customer segments: [e.g., "first-time buyers, VIP repeat purchasers (3+ orders), lapsed 90+ days"]
- Average order value + purchase frequency: [e.g., "$65 AOV, 3.2x per year"]
- Compliance obligations: [TCPA (US), GDPR (EU/UK), CASL (Canada), LGPD (Brazil), other]
- Prior messaging experience: [First program / existing program needing optimization]
- Key business events: [Sales calendar, product launches, seasonal peaks in next 90 days]

OBJECTIVE: Build a complete, compliance-first SMS/WhatsApp marketing automation system that generates measurable revenue lift while protecting subscriber trust.

OUTPUT REQUIREMENTS:

### PART 1: COMPLIANCE & OPT-IN ARCHITECTURE

**Regulatory Compliance Checklist**
For each applicable regulation (TCPA / GDPR / WhatsApp Business Policy), produce:
- Required opt-in language (exact copy)
- Double opt-in flow: trigger, confirmation message text, timeout logic
- Consent record-keeping requirements (what to log, how long to retain)
- STOP/HELP/UNSUBSCRIBE keyword handling and auto-response copy
- Prohibited content categories for this region
- Maximum sending frequency guardrails

**Opt-In Acquisition Strategy**
Design 5 opt-in touchpoints with conversion copy for each:
1. Homepage popup (exit-intent or scroll-triggered)
2. Post-purchase checkout confirmation page
3. Email list cross-promotion (for SMS list growth from existing email subscribers)
4. In-store / offline QR code (if applicable)
5. Social media / DM opt-in (Instagram, WhatsApp Click-to-Chat)

For each: headline, body copy, CTA, incentive (if applicable), and expected opt-in conversion rate benchmark.

**Welcome Series — 5-Message Onboarding Flow**
Message 1 (Immediate): Confirm subscription + deliver promised incentive
Message 2 (Day 1, 2 hours after opt-in): Brand story — why you exist, what makes you different (3-5 sentences max)
Message 3 (Day 2): Social proof — a specific customer result or bestseller with review snippet
Message 4 (Day 4): Product education — one key use case or "how to get the most out of [product]"
Message 5 (Day 7): Urgency trigger — limited-time offer or scarcity signal if message 4 generated no purchase

For each message: exact copy (character count for SMS), send-time recommendation, behavioral exit rule (e.g., "suppress if purchase made"), and WhatsApp rich media specification (image, CTA button text).

### PART 2: REVENUE RECOVERY AUTOMATIONS

**Abandoned Cart Recovery — 3-Message Sequence**
Based on the Behavioral Sequencing Model (urgency escalation + social proof + loss aversion):

Message 1 (30 minutes post-abandonment):
- Psychological trigger: curiosity + mild urgency
- Copy framework: Product name + what they're missing + soft CTA
- Character limit: 160 (SMS) or 1,024 (WhatsApp)
- Personalization variables: [first_name], [product_name], [cart_link]

Message 2 (3 hours post-abandonment, only if no purchase):
- Psychological trigger: social proof + scarcity
- Copy framework: "X people are viewing this right now" or "Low stock" signal + review
- Include: product image recommendation (WhatsApp), fallback for SMS

Message 3 (22 hours post-abandonment, only if no purchase):
- Psychological trigger: loss aversion + final incentive
- Copy framework: "Last chance" + specific discount or free shipping offer
- Include: hard expiry timestamp, STOP unsubscribe notice (TCPA compliance)

**Browse Abandonment Flow (High-Intent, No Cart)**
2-message sequence for visitors who viewed a product page 2+ times without adding to cart:
- Message 1 (4 hours): Curiosity hook + product benefit
- Message 2 (24 hours): Peer proof + objection handle

**Post-Purchase Upsell & Cross-Sell Flow**
3-message sequence starting 48 hours after delivery confirmation:
- Message 1: "How's your [product]?" — satisfaction check + UGC/review request
- Message 2 (Day 5, if no review given): Related product recommendation based on purchase category
- Message 3 (Day 14): Replenishment reminder (if applicable) or complementary product bundle

**Winback / Re-Engagement Sequence**
For subscribers silent 60-90 days:
- Message 1: Re-permission signal — "Still want to hear from us?" with Yes/No quick reply
- Message 2 (Day 3, only if no response): Final offer — highest-value incentive in your toolkit
- Auto-unsubscribe after 7 days of no response (TCPA/GDPR best practice)

### PART 3: BROADCAST CAMPAIGN FRAMEWORKS

**Product Launch Campaign Arc (3-Message Broadcast)**
Message 1 — Pre-launch teaser (48 hours before): Build anticipation with exclusive early access angle
Message 2 — Launch day (9AM local): Full announcement with hero benefit, price, and urgency
Message 3 — Last chance (48 hours before close or while stock lasts): FOMO + social proof + direct link

For each: copy in SMS (160 char) and WhatsApp (with button options and media recommendations), send-time rationale, and A/B test variant suggestion.

**VIP / Loyalty Tier Messaging**
Design a VIP subscriber cadence for top 20% of buyers:
- Monthly VIP exclusive offer (first access, extra % off, or gift-with-purchase)
- Milestone messaging: 3rd purchase, 6-month anniversary, spend threshold unlock
- Birthday/anniversary flow with personalized offer

**Flash Sale Acceleration Sequence**
For time-limited 24-48 hour sales:
- Announcement message (sale opens)
- Mid-sale social proof pulse ("X units sold in 12 hours")
- Closing urgency message (2 hours before end)
Include: legal requirements for "limited time offer" disclosures by region.

### PART 4: MEASUREMENT & OPTIMIZATION

**KPI Dashboard — Metrics That Matter**
For each automation, define:
- Primary conversion metric (e.g., recovered cart revenue)
- Open rate benchmark (SMS: 95%+, WhatsApp: 85-98%)
- Click-through rate benchmark (SMS: 8-15%, WhatsApp: 15-35%)
- Revenue-per-message benchmark for your AOV/frequency profile
- Unsubscribe rate red flag threshold (> 2% per broadcast = content/frequency problem)

**A/B Testing Roadmap — First 90 Days**
Month 1: Test send time (morning vs. evening) for welcome series
Month 2: Test offer type (% discount vs. free shipping vs. gift) in abandoned cart Message 3
Month 3: Test message length (short punchy vs. narrative) for broadcast campaigns

Provide: hypothesis, success metric, minimum sample size for statistical significance at 95% confidence, and decision rule.

**Frequency & Fatigue Guardrails**
- Maximum broadcast frequency: [set based on subscriber engagement health]
- Suppression rules: customers in active support tickets, post-purchase cool-down window, opted-down "low frequency" subscribers
- Subscriber health scoring: define "engaged," "at-risk," and "dormant" tiers for this channel

### PART 5: TECHNICAL INTEGRATION SPECIFICATIONS

**Platform Configuration Requirements**
For [specified platform], list:
- Required API connections (CRM, ecommerce platform, CDP)
- Webhook triggers for each automation flow
- Data fields required for personalization (name, product, cart total, last purchase date)
- WhatsApp Business API template approval categories (Utility vs. Marketing — affects delivery)
- Rate limits and throughput considerations for large broadcast sends

**Cross-Channel Orchestration**
Define suppression logic between email and SMS to avoid double-messaging:
- If email abandoned cart Message 1 sent within last 2 hours → delay SMS Message 1 by 90 minutes
- If customer unsubscribed from SMS → do not re-prompt via email within 30 days
- If customer purchases via email link → immediately suppress all SMS recovery flows

## Example Input/Output

**Example Input:**
- Business: Fieldnotes Coffee Co. — DTC coffee subscription, $42 AOV, 6 bags/year average
- Channel: SMS (US market, TCPA compliance)
- Platform: Postscript + Klaviyo
- Subscribers: 2,800 SMS / 48,000 email
- Top 3 use cases: abandoned cart, subscription renewal reminders, limited roast drops
- Region: United States

**Example Output (Selected):**

**Welcome Message 1 (Immediate — 118 chars):**
"Your 15% off is waiting, [First Name] ☕ Shop Fieldnotes: fieldnotes.co/new — Reply STOP to opt out."

**Welcome Message 2 (Day 1, 10AM — 152 chars):**
"We source from 12 farms. No blending, no hiding. Just the roast we'd drink ourselves. Fieldnotes.co — Reply STOP to unsubscribe."

**Abandoned Cart Message 1 (30 min — 145 chars):**
"Hey [First Name], you left [Product Name] behind. It's still in your cart: [Link] — Reply STOP to opt out."

**Abandoned Cart Message 2 (3 hours — 155 chars):**
"42 people ordered [Product Name] this week. Only 8 bags left at this roast date. Still yours: [Link] — STOP to quit."

**Abandoned Cart Message 3 (22 hours — 158 chars):**
"Last chance: free shipping on your [Product Name] — expires midnight. [Link] Ends tonight. Reply STOP anytime."

**VIP Flash Sale Message (243 chars — WhatsApp):**
"[First Name], you're on the VIP list. Our Guatemala La Hermosa micro-lot drops tomorrow at 9AM — you get 24hr early access before we open to everyone. Only 200 bags. Shop: [Link]"
*Button CTA: "Shop Now" | Image: product photography of bag against coffee origin map*

**Compliance confirmation (TCPA — US):**
"Fieldnotes Coffee: You're subscribed to SMS alerts (1-2 msgs/wk). Msg&data rates may apply. Reply HELP for info, STOP to cancel. fieldnotes.co/sms-terms"

**KPI Benchmarks for Fieldnotes (AOV $42, 6x/year):**
- Abandoned cart recovery rate target: 12-18% of abandoned carts
- Revenue per abandoned cart SMS sequence: $4.20-$7.56 per send
- Welcome series purchase conversion target: 8-12% within 7 days of opt-in
- Broadcast click-through target: 9-14%
- Projected annual SMS-attributed revenue at 2,800 subscribers: $47K-$84K

## Success Metrics

**Automation-Level Health Checks:**
- Abandoned cart sequence: > 12% recovery rate, < 3% unsubscribe rate
- Welcome series: > 8% purchase conversion within 7 days
- Win-back sequence: > 5% re-engagement rate before sunset

**Program-Level Health Checks:**
- List growth rate: > 2% month-over-month net subscriber growth
- Revenue per subscriber per month: > $1.50 (DTC benchmark)
- Unsubscribe rate per broadcast: < 1.5%
- Compliance incidents: 0 (TCPA/GDPR violations are existential risks)

**Benchmark References:**
- SMS open rate: 95-98% (vs. email: 22-25%)
- SMS CTR: 8-19% (vs. email: 2-4%)
- WhatsApp open rate: 85-98%
- WhatsApp CTR: 15-35%
- Abandoned cart SMS recovery: 10-25% (vs. email alone: 5-12%)

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Behavioral-Email-Trigger-Lifecycle-Automation-Engine.md` — Design complementary email automation alongside SMS for true cross-channel orchestration
- `../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Customer-Win-Back-&-Cold-Lead-Reactivation-Engine.md` — Extend win-back campaigns to include SMS/WhatsApp escalation for non-responders
- `../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Conversational-Marketing-&-Chatbot-Pipeline-Generation-Engine.md` — Pair website chatbot qualification with SMS/WhatsApp follow-up sequences
- `../../03_Content-&-Creative/Email-Marketing-Content/Behavioral-Email-Automation-Lifecycle-Engine.md` — Build consistent behavioral logic across email and SMS channels

## Integration Tips

**Klaviyo + Postscript (DTC Standard Stack):**
- Use Klaviyo flows to trigger Postscript via webhook — share subscriber events (purchase, browse, cart abandon) between platforms
- Suppress SMS sends in Postscript when Klaviyo email has sent within the last 2 hours using shared event timestamps
- Sync Klaviyo segments (VIP, lapsed, new) to Postscript lists for coordinated campaign targeting

**HubSpot + Twilio (B2B SaaS Stack):**
- Use HubSpot workflows to trigger Twilio SMS via webhook for trial expiration, onboarding milestone nudges, and renewal reminders
- Map HubSpot contact properties (lifecycle stage, deal stage) to Twilio messaging service for automatic routing
- Log all SMS responses back to HubSpot contact activity timeline via Twilio webhook → HubSpot API

**WhatsApp Business API (Meta Direct or via BSP):**
- Business Solution Providers (BSPs) with strong automation: Zoko, WATI, Bird (formerly MessageBird), Vonage
- Template message categories: "Utility" (transactional, free) vs. "Marketing" (paid per conversation window)
- 24-hour conversation window: once a subscriber messages you, you can reply freely for 24 hours — design flows that encourage replies to open free windows

**Zapier / Make Automation:**
- Trigger: Shopify order placed → Zap → SMS confirmation via Twilio (for platforms without native integration)
- Trigger: Form submission (Typeform/HubSpot) → Zap → WhatsApp welcome message via WATI
- Trigger: Stripe payment failed → Zap → SMS recovery message via Postscript or Twilio

**Compliance Automation:**
- Store opt-in consent records in a dedicated compliance table (timestamp, IP address, opt-in source, exact consent language shown) — automate via Zapier → Google Sheets or database
- Set up automatic opt-out processing: STOP keyword → update CRM contact property → suppress from all future campaigns within 10 minutes (TCPA requirement)

## Troubleshooting

**Problem 1: High unsubscribe rates (> 2% per broadcast)**
*Cause:* Too frequent sending, irrelevant content, or sending at the wrong time
*Fix:* Audit your broadcast frequency (max 2-4/month for most brands). Add preference center: let subscribers choose "Daily deals," "New arrivals only," or "VIP only." Segment broadcasts by purchase history — don't send a "first purchase" offer to 10x buyers. Test send times (10AM-12PM and 6PM-8PM local time typically outperform off-hours).

**Problem 2: WhatsApp template messages rejected by Meta**
*Cause:* Templates that read as promotional are rejected if submitted under "Utility" category; or variable placeholders aren't properly formatted
*Fix:* Submit promotional messages under the "Marketing" category — they cost per conversation but will be approved. Use exact Meta placeholder format: `{{1}}` not `[first_name]`. Avoid urgency language ("Act now," "Limited time") in Utility templates — move those to Marketing category. Allow 48-72 hours for approval and build a buffer before campaigns.

**Problem 3: Low abandoned cart recovery rates (< 8%)**
*Cause:* Message timing too slow, no personalization, or offer not compelling enough
*Fix:* Move Message 1 from 1-hour delay to 30 minutes — data consistently shows 30-minute messages recover 30-50% more carts than 1-hour messages. Ensure product name and image (WhatsApp) are dynamically populated. Test adding a specific benefit ("free 2-day shipping") in Message 1 rather than waiting until Message 3. If AOV > $100, include a phone number for "text us and we'll help" — concierge conversion works at higher price points.

## Version History
- v1.0: Initial creation (auto-generated)
