# AI-Powered DTC Product Recommendation Quiz & Zero-Party Data Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** dtc, ecommerce, interactive-content, personalization, zero-party-data, email-automation, conversion

## Overview
Design and deploy AI-driven product recommendation quizzes that capture zero-party data, personalize the shopping experience, and feed automated email sequences — turning quiz takers into repeat buyers. Built for D2C brands in beauty, wellness, apparel, food, and lifestyle categories.

## Quick Copy-Paste Version

You are a D2C conversion strategist and quiz designer. I run a [YOUR PRODUCT CATEGORY] brand called [BRAND NAME] that sells [BRIEF DESCRIPTION OF PRODUCTS].

Design a complete product recommendation quiz for my website with the following:

1. QUIZ STRUCTURE (6-8 questions max):
   - Opening hook question that captures attention and feels personal
   - 3-4 diagnostic questions that reveal customer needs, preferences, or goals
   - 1-2 lifestyle/identity questions that enable deeper segmentation
   - Email capture question positioned mid-quiz (after they're invested)
   - Results configuration logic (map answers to product recommendations)

2. For each question, provide:
   - The exact question text (conversational, not clinical)
   - 3-5 answer options with copy that feels like the customer wrote it themselves
   - The zero-party data signal each answer captures
   - Which product SKU or collection each answer path leads toward

3. RESULTS PAGES (one per major segment):
   - Personalized headline that mirrors their answers back
   - 2-3 recommended products with 1-sentence "why this is perfect for you" copy
   - Social proof element (review snippet or statistic)
   - Primary CTA button copy and secondary soft CTA

4. POST-QUIZ EMAIL SEQUENCE (3 emails):
   - Email 1 (immediate): Results delivery + product recommendations
   - Email 2 (Day 2): Educational content that reinforces why their recommended product solves their problem
   - Email 3 (Day 5): Conversion push with urgency or offer

Format the quiz as a complete build spec I can hand to my development team or load into Octane AI / Typeform.

My top 3 products are: [PRODUCT 1], [PRODUCT 2], [PRODUCT 3]
My target customer is: [DESCRIBE IDEAL CUSTOMER]
The main problem my products solve: [CORE PROBLEM]

## Advanced Customizable Version

ROLE: You are a zero-party data strategist, conversion rate optimizer, and D2C growth engineer with deep expertise in quiz-based personalization, Klaviyo email automation, and Shopify conversion funnels.

BRAND CONTEXT:
- Brand: [BRAND NAME]
- Category: [e.g., skincare, supplements, pet food, apparel, home goods]
- AOV: $[AVERAGE ORDER VALUE]
- Top 3-5 SKUs by revenue: [LIST WITH PRICES]
- Primary customer segments you already know about: [e.g., sensitive skin / oily skin / combination skin]
- Current homepage conversion rate: [%] (if known)
- Email list size: [NUMBER] subscribers
- Platform: Shopify / WooCommerce / [OTHER]
- Email platform: Klaviyo / Mailchimp / [OTHER]

QUIZ DESIGN OBJECTIVES:
1. Capture zero-party data that improves personalization across email, ads, and on-site
2. Increase email list opt-in rate by [TARGET — e.g., 30%] by embedding capture mid-quiz
3. Recommend the highest-fit product for each visitor to increase first-purchase conversion
4. Build segmentation signals that enable lifecycle marketing sequences

DELIVERABLE 1 — QUIZ ARCHITECTURE:
Design a quiz titled "[QUIZ NAME — e.g., 'Find Your Perfect [Brand] Routine']" with:

A) QUESTION DESIGN (8 questions max, each serving a data purpose):
For each question provide:
- Question text (conversational, first-person voice, no jargon)
- Answer options (3-5, written as natural customer language)
- Data captured (e.g., skin type, goal, lifestyle, budget sensitivity)
- Branching logic (which question or result does each answer lead to?)
- Klaviyo profile property this answer should write to

B) SEGMENTATION MATRIX:
Create a 3x3 or 4x4 grid mapping answer combinations to customer segments:
- Segment name (internal use)
- Customer profile description (demographics, psychographics, JTBD)
- Primary product recommendation
- Secondary product recommendation
- Messaging angle that resonates with this segment

C) RESULTS PAGE COPY (one per segment):
For each segment produce:
- Personalized headline: "Based on your answers, you need [X]..."
- 2-sentence explanation of why this specific product fits their situation
- Product card copy (name, key benefit, social proof line)
- Primary CTA: [Shop Now / Get My [X] / Claim Your Results]
- Soft CTA: [See Full Collection / Take Quiz Again]
- Trust element: (return policy, number of reviews, certification)

DELIVERABLE 2 — ZERO-PARTY DATA STRATEGY:
For each data point captured in the quiz, specify:
- Klaviyo property name and data type (string, boolean, array)
- How it should be used in segmentation (e.g., "skin_type = oily" → suppress dry skin product emails)
- Downstream personalization use cases (email subject lines, homepage banner, ad audiences, SMS)
- Data decay policy (when to re-quiz to refresh the data)

DELIVERABLE 3 — POST-QUIZ EMAIL FLOW (Klaviyo):

Flow trigger: Quiz completed + email captured

EMAIL 1 — "Your Results Are In" (send immediately):
- Subject line: [3 options using curiosity + personalization]
- Preview text: [3 options]
- Body: Mirror their answers back, reveal their result, deliver top 3 recommendations with direct links
- Dynamic content blocks: Product name, key ingredient/benefit, price
- CTA: Shop [Segment-Specific Product Name]
- P.S.: Urgency element or social proof

EMAIL 2 — "Why This Works for You" (send Day 2, 10am local time):
- Subject line: [3 options — educational angle]
- Body: Teach them about their identified problem (e.g., "Why oily skin still needs hydration")
- Content format: 3 key insights, each tied back to a product feature
- CTA: Read the Science / Shop Now
- Include: 1 customer quote from someone with the same profile

EMAIL 3 — "Don't Miss Your Match" (send Day 5):
- Subject line: [3 options — urgency/scarcity angle]
- Body: Overcome the #1 objection for their segment (price? skepticism? overwhelm?)
- Include: Limited-time offer OR free shipping threshold OR bundle deal
- Social proof: Number of customers with their profile who saw results
- CTA: Shop Now [with offer]
- Unsubscribe/preference center mention for compliance

DELIVERABLE 4 — INTEGRATION SPEC:
Provide a technical integration checklist for:
- Typeform / Octane AI / Interact quiz platform setup
- Klaviyo webhook configuration to receive quiz data
- Shopify metafield or customer tag strategy
- Google Analytics 4 event tracking (quiz_started, quiz_completed, quiz_email_captured, product_clicked)
- Meta Pixel custom event firing on quiz completion for retargeting audiences
- Optional: Postscript/Attentive SMS trigger for high-intent segments

CONSTRAINTS:
- Quiz must complete in under 2 minutes (≤ 8 questions)
- No question should feel like market research — every question must feel like it benefits the customer
- Email capture must be optional but incentivized (offer a "your personalized guide" or discount)
- Results must work even without email capture (show results, but reduce depth)
- All copy must match brand voice: [BRAND VOICE DESCRIPTION — e.g., "warm, science-backed, empowering, not pushy"]

OUTPUT FORMAT:
Produce each deliverable as a structured section with headers, tables, and email templates ready to copy into Klaviyo. Include a one-page launch checklist at the end.

## Example Input/Output

**Brand Profile:**
- Brand: Fauna Skincare
- Category: Clean skincare for sensitive skin
- Products: Calm Serum ($48), Balance Moisturizer ($62), Repair Overnight Mask ($54)
- Target customer: Women 28-45 with reactive or sensitive skin, ingredient-conscious
- AOV: $58, Email platform: Klaviyo, Store: Shopify

---

**Sample Quiz Flow Output:**

**Quiz Title:** "What Does Your Skin Actually Need? (2-Minute Quiz)"

**Question 1 — Opening Hook:**
> "When you wake up in the morning, your skin feels..."
> a) Tight and dry, like it needs a drink
> b) A little oily, especially around my T-zone
> c) Reactive — red patches or random irritation
> d) Pretty balanced, but loses it by midday

*Data captured: Baseline skin type → writes to Klaviyo property `skin_type`*

**Question 2 — Primary Goal:**
> "Right now, my biggest skin concern is..."
> a) Calming redness and sensitivity
> b) Keeping moisture locked in all day
> c) Waking up with genuinely better skin over time
> d) Finding products that won't break me out

*Data captured: Primary JTBD → writes to `skin_goal`*

**Question 3 — Email Capture (Mid-Quiz, after 3 questions):**
> "You're halfway there! Drop your email to save your results + get your personalized skincare guide."
> [Email field] → incentive: "We'll also include a 10% discount on your perfect match."

**Results Page — Segment: "Calm Seekers" (reactive/sensitive skin, redness focus):**

> **"Your Skin Is Speaking. Here's What It's Asking For."**
>
> Based on your answers, your skin is in a constant state of low-grade stress. It needs ingredients that turn down the volume on inflammation before trying to do anything else. That's exactly what the Calm Serum was formulated for.
>
> **Your Match: Fauna Calm Serum — $48**
> *Centella asiatica + niacinamide blend shown to reduce redness markers in 14 days.*
> ⭐⭐⭐⭐⭐ "I've tried everything. This is the first thing that didn't make my skin angry." — Priya M., verified buyer
>
> [Shop Calm Serum →] [See My Full Routine →]

---

**Email 1 Subject Line Options:**
- "Your skin results are ready, [First Name] 🌿"
- "We found your match (it's not what you'd expect)"
- "Based on your answers: here's exactly what your skin needs"

**Email 3 Subject Line Options:**
- "48 hours left: your 10% quiz discount"
- "Still thinking? Here's what 4,200 sensitive-skin customers say"
- "[First Name], your skin match is waiting"

## Success Metrics

- **Quiz completion rate:** 55-75% of quiz starters should complete (industry average: 60%)
- **Email capture rate:** 35-55% of quiz completers should opt in
- **Quiz-to-purchase conversion rate:** 8-18% within 7 days of quiz completion (vs. 2-4% baseline site CVR)
- **Post-quiz email open rate:** Email 1 should achieve 45-65% open rate (personalization drives this)
- **Revenue per quiz completer:** Track 30-day revenue per quiz segment vs. non-quiz visitors
- **Segment accuracy:** Validate by tracking return rate and product reviews by segment — high accuracy = lower returns

## Related Prompts

- [Interactive Content Generation Overview](./Interactive-Content-Generation.md)
- [AI-Powered ROI Calculator Lead Generation Engine](./AI-Powered-ROI-Calculator-Lead-Generation-Engine.md)
- [AI-Powered DTC Cart Abandonment Recovery & Post-Purchase Revenue Expansion Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/AI-Powered-DTC-Cart-Abandonment-Recovery-&-Post-Purchase-Revenue-Expansion-Intelligence-Engine.md)
- [AI-Powered DTC Customer Loyalty & Rewards Program Revenue Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/AI-Powered-DTC-Customer-Loyalty-&-Rewards-Program-Revenue-Intelligence-Engine.md)

## Integration Tips

- **Octane AI** (Shopify-native): Best for D2C brands — natively syncs quiz answers as Klaviyo profile properties and Shopify customer tags, no Zapier needed
- **Typeform + Zapier → Klaviyo**: Use Typeform's hidden fields to pass UTM data alongside quiz answers; Zapier updates Klaviyo profiles and triggers flows
- **Interact.com**: Strong branching logic builder with native Klaviyo and Shopify integrations; export results as segment-tagged Klaviyo lists
- **Klaviyo Flows**: Build the post-quiz flow with a "Quiz Completed" custom event trigger; use conditional splits on `skin_type`, `skin_goal` properties to branch into segment-specific content
- **Meta Ads Retargeting**: Fire a Meta Pixel `CompleteQuiz` custom event with quiz segment as a parameter; build lookalike audiences from each high-LTV segment
- **Google Sheets (reporting)**: Connect Typeform responses to Google Sheets via Zapier; build a weekly dashboard showing quiz completions, email captures, revenue per segment
- **Postscript/Attentive (SMS)**: For high-intent segments (e.g., answered "ready to invest in my skin"), trigger an SMS 24 hours after Email 1 with a direct product link

## Troubleshooting

**Problem: Quiz completion rate is below 40%**
*Solution:* The quiz is too long or questions feel like market research. Audit each question: if removing it doesn't change the product recommendation, cut it. Rewrite answer options in the customer's own words — replace clinical language ("oily skin") with experiential language ("shiny by noon"). Add a progress bar so users know how close they are to results.

**Problem: Email capture rate below 25%**
*Solution:* The incentive isn't strong enough or positioned too early. Move the email capture to question 4 or 5 (after they're invested). Upgrade the incentive — "personalized skincare guide" outperforms "discount" for ingredient-conscious audiences. A/B test framing: "Save your results" vs. "Get your personalized routine" vs. "Unlock your 10% discount."

**Problem: Post-quiz email revenue is flat despite opens**
*Solution:* The product recommendations on the results page aren't matching the email recommendations — audit for consistency. Check that Klaviyo dynamic content blocks are pulling the correct segment-specific product. Review Email 3's offer — if the discount isn't compelling enough for the AOV, try a "buy 2, get free shipping" threshold instead. Ensure the CTA button links directly to a pre-filled cart, not the product page.

## Version History
- v1.0: Initial creation (auto-generated)
