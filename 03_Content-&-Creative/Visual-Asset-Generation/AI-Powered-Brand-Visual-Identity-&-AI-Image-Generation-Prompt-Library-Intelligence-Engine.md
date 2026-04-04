# AI-Powered Brand Visual Identity & AI Image Generation Prompt Library Intelligence Engine - Systematic Brand-Consistent AI Image Creation at Scale

**Difficulty:** Advanced | **Time:** 20 min | **Tags:** visual-content, brand, ai-image-generation, content-creation, design, b2b, automation, creative-ops

## Overview
Builds a systematic, brand-consistent AI image generation system — creating a master prompt library, style guide translation layer, and quality-gate workflow so any team member can generate on-brand visuals using Midjourney, DALL-E 3, Adobe Firefly, Flux, or Stable Diffusion without a designer. Use it when scaling visual content production, onboarding AI image tools, or eliminating stock photo dependency.

## Quick Copy-Paste Version

You are a senior visual brand strategist and AI image prompt engineer. Your job is to build a complete AI image generation system for my brand.

Brand context:
- Company: [Company name and one-line description]
- Industry: [e.g., B2B SaaS, fintech, healthcare tech]
- Brand personality: [e.g., "professional but approachable, data-driven, modern"]
- Primary brand colors: [hex codes or descriptions]
- Typography style: [e.g., "clean sans-serif, geometric"]
- Visual style reference: [e.g., "like Stripe meets Linear — clean, technical, premium"]
- What to avoid: [e.g., "no cheesy stock photos, no clip art, no busy backgrounds"]
- Primary use cases: [e.g., LinkedIn posts, blog headers, ad creative, website hero images]

Deliver:

1. BRAND VISUAL DNA BRIEF (2 paragraphs): Translate our brand into visual language — lighting, composition, color palette, subject style, background treatment, mood/atmosphere, and photographic style that AI tools can execute.

2. MASTER STYLE SUFFIX (1 paragraph): A single reusable prompt suffix to append to any image prompt to lock in brand style. Should work across Midjourney, DALL-E 3, and Adobe Firefly.

3. CORE PROMPT LIBRARY (10 prompts): Ready-to-use prompts for our top use cases:
   - 3x LinkedIn feed image prompts (thought leadership/educational)
   - 2x blog header image prompts
   - 2x paid ad creative prompts (social)
   - 2x website/landing page hero section prompts
   - 1x email header prompt
   Each prompt: [Subject + Scene] + [Composition] + [Lighting] + [Style] + [Brand suffix]

4. NEGATIVE PROMPT LIBRARY: 15 elements to exclude (--no flags or negative prompts) that protect brand consistency.

5. QUALITY GATE CHECKLIST (5 criteria): How to evaluate each AI-generated image before publishing. Binary pass/fail for each.

6. TOOL-SPECIFIC ADAPTATIONS: How to adjust the master prompt suffix for Midjourney (v6+), DALL-E 3 (via ChatGPT/API), Adobe Firefly (Generative Fill/Text-to-Image), and Flux (via Replicate).

## Advanced Customizable Version

ROLE: You are a Creative Director with 15+ years in B2B brand building, now specializing in AI-native visual content systems. You've helped 50+ companies eliminate stock photo dependency and build scalable AI image pipelines. You understand both the technical parameters of AI image models and the strategic requirements of brand consistency.

OBJECTIVE: Build a complete, production-ready AI image generation system that any marketing team member can execute without design experience, while maintaining the quality and consistency of a $300/hour creative agency.

COMPANY CONTEXT:
- Company name and description: [name + 2-sentence description]
- Industry vertical: [e.g., B2B SaaS, cybersecurity, healthcare, fintech, manufacturing tech]
- Target buyer persona: [e.g., "VP of Engineering at 200-1000 person enterprise companies"]
- Brand archetype: [Sage/Expert, Hero/Bold, Creator/Innovative, Ruler/Premium, etc.]
- Existing brand assets: [describe logo style, color palette with hex codes if known, fonts]
- Visual style inspiration: [3 brands or websites whose visual style you admire — be specific]
- Competitors' visual style: [what to differentiate from]
- Primary distribution channels: [LinkedIn, Meta, Google Display, website, email, events]
- Content volume need: [e.g., "20 LinkedIn images/week, 5 blog headers/week, 10 ad variants/month"]
- AI tools available: [Midjourney subscription tier, DALL-E 3, Adobe Creative Cloud, Firefly, Flux]
- Brand restrictions: [legal, compliance, persona representation requirements, geographic considerations]

DELIVERABLE 1 — BRAND VISUAL TRANSLATION DOCUMENT

Translate brand identity into AI-executable visual language across 8 dimensions:

**1.1 Color Psychology & Application**
- Primary palette translation for AI: How to describe colors in scene-building language (e.g., "cool steel blue ambient light" vs. "#0052CC")
- Color ratio guidelines: Background vs. subject vs. accent color ratios
- Lighting color temperature: Warm (3200K) vs. cool (6500K) and when to use each
- Shadow and highlight treatment: Soft diffused vs. dramatic contrast

**1.2 Composition Framework**
- Primary composition rule: [Rule of thirds, centered, golden ratio]
- Subject placement: [left, right, center] and why
- Negative space philosophy: How much and where
- Depth treatment: Shallow depth of field vs. environmental context
- Frame within frame techniques

**1.3 Subject & People Representation**
- Human representation style: [Photorealistic, illustrated, silhouette, abstract]
- Diversity and inclusion requirements: Representation guidelines for people
- Professional styling: Wardrobe, environment, age range
- Emotion and expression: [Confident, collaborative, focused, aspirational]
- Avoid: [Stock-photo clichés like handshakes, generic office scenes, pointing at screens]

**1.4 Background & Environment**
- Primary environments: [Abstract, architectural, natural, data visualization]
- Texture and material language: [Glass, concrete, gradient, particle systems]
- Depth and atmosphere: [Bokeh, motion blur, environmental haze]
- Brand pattern integration: How to incorporate brand elements without text

**1.5 Lighting Philosophy**
- Primary light source direction and quality
- Studio vs. environmental vs. cinematic
- Time of day if applicable
- Mood lighting for different content types (educational vs. promotional vs. emotional)

**1.6 Post-Processing Aesthetic**
- Color grading style: [Desaturated tech, warm editorial, high-contrast commercial]
- Sharpness and clarity treatment
- Grain and texture: Clean digital vs. film grain vs. painterly

**1.7 Iconography & Abstract Elements**
- Data visualization aesthetics: How to represent charts, flows, networks
- Technology representation: [Abstract circuits, flowing data, geometric systems]
- Motion and energy: Static vs. implied motion

**1.8 Prohibited Elements**
- Comprehensive list of visual clichés to ban
- Competitor visual signatures to avoid
- Technical artifacts to filter (AI hands, text in images, watermarks)

DELIVERABLE 2 — MASTER PROMPT ARCHITECTURE

**2.1 Universal Brand Suffix (UBS)**
Build a 60-80 word suffix that locks brand style across all prompts. Structure:
[Rendering style] + [Lighting directive] + [Color treatment] + [Composition note] + [Quality flags] + [Negative elements]

Provide version for:
- Midjourney v6+ (include --ar ratios, --style, --chaos settings)
- DALL-E 3 (optimized for ChatGPT 4o and API calls)
- Adobe Firefly (Generative Fill and Text-to-Image)
- Flux 1.1 Pro (via Replicate or API)
- Stable Diffusion XL (with LoRA considerations)

**2.2 Content-Type Prompt Templates**

For each template, provide:
- Full prompt with [VARIABLE] placeholders
- Aspect ratio recommendation
- Model-specific parameters
- 3 example instantiations with different topics

Templates to build:
A. LinkedIn Single Image — Educational/Thought Leadership
B. LinkedIn Single Image — Company News/Announcement
C. Blog Post Header (16:9 and 4:3)
D. Email Newsletter Header
E. Paid Social Ad — Awareness (Meta/LinkedIn)
F. Paid Social Ad — Retargeting/Conversion
G. Website Hero Section Background
H. Case Study / Testimonial Visual
I. Event / Webinar Promotional Image
J. Report / Ebook Cover
K. Twitter/X Card Image
L. YouTube Thumbnail

**2.3 Persona-Specific Prompt Variations**
For each of your top 3 buyer personas, modify the master templates to:
- Adjust environment to persona's professional context
- Match aspiration level (individual contributor vs. executive)
- Include relevant technical or industry visual elements

DELIVERABLE 3 — PRODUCTION WORKFLOW SYSTEM

**3.1 Prompt Engineering Playbook**
Step-by-step process for any team member to create new on-brand prompts:
1. Start with the appropriate template from 2.2
2. Replace [VARIABLES] using the brand vocabulary from 1.x
3. Apply the UBS from 2.1
4. Run quality gate from 3.2

**3.2 Quality Gate (10-Point Scoring Rubric)**
Score each generated image 1-3 on:
1. Color palette adherence
2. Composition match
3. Subject/people representation quality
4. Background treatment
5. Lighting consistency
6. Text legibility zone (is there clear space for overlay text?)
7. Technical quality (no AI artifacts)
8. Brand differentiation (would this look like our competitor?)
9. Emotional resonance (does it match intended content mood?)
10. Channel fit (correct aspect ratio, visual weight for platform)
Score 22+ = Publish | 18-21 = Minor edit | Under 18 = Regenerate

**3.3 Iteration Protocol**
When first-generation doesn't pass quality gate:
- Primary fix: Prompt modification strategies (add/remove elements)
- Secondary fix: Variation parameters (--chaos, seed, weight adjustments)
- Tertiary fix: Inpainting/outpainting specific problem areas
- Escalation: When to involve a human designer vs. keep iterating

**3.4 Asset Management System**
- File naming convention for AI-generated assets
- Metadata tagging for searchability (tool, date, prompt version, content type)
- Approved prompt archive structure in Notion/Airtable
- Version control for style evolution over time

DELIVERABLE 4 — CHANNEL-SPECIFIC SPECIFICATIONS

For each of your active channels, provide:
- Exact dimensions and safe zones for text overlay
- Platform-specific quality standards (LinkedIn recommends; Meta rejects)
- Compression and format requirements (JPEG vs. PNG vs. WebP)
- A/B testing prompt variation strategy

DELIVERABLE 5 — TEAM ENABLEMENT ASSETS

**5.1 30-Minute Onboarding Script**
How to teach any marketing team member to use this system in one session.

**5.2 FAQ: Common Mistakes**
Top 10 prompt engineering mistakes that break brand consistency and how to fix each.

**5.3 Monthly Visual Trend Audit Prompt**
A recurring prompt to evaluate if the brand visual system needs evolution based on:
- Competitor visual shifts
- Platform algorithm changes
- AI model updates
- Audience engagement data

FRAMEWORKS TO APPLY:
- Ogilvy's visual-copy integration principles (images as standalone storytellers)
- Nielsen Norman Group's visual hierarchy for digital UX
- Gestalt principles for composition (proximity, similarity, figure-ground)
- Byron Sharp's distinctive brand asset theory for visual salience

## Example Input/Output

**Input Example:**

Company: Kairos — B2B SaaS that automates contract lifecycle management for mid-market legal and finance teams

Brand personality: "Precise, trustworthy, quietly confident — like a law firm that discovered good design"
Primary colors: Deep navy #1B2B4A, Platinum #E8EDF5, Copper accent #C17D3C
Typography: Monument Extended (headings), Inter (body)
Visual inspiration: Notion meets Ironclad meets The Economist's data journalism
Avoid: Generic office people, handshakes, blue gradient blobs
Primary use cases: LinkedIn thought leadership, blog headers, Meta retargeting ads
Tools available: Midjourney v6, DALL-E 3, Adobe Firefly

**Output Example (excerpt):**

**Universal Brand Suffix (Midjourney):**

> "editorial documentary photography, cool diffused window light, desaturated navy and platinum color grade with copper warm accents, architectural negative space, precise sharp foreground subject with soft environmental depth, no people unless essential, cinematic 2.39:1 crop feel, Hasselblad medium format quality --ar 16:9 --style raw --chaos 5 --no blobs, gradients, handshakes, watermarks, clipart, text, logos, bright colors, lens flare, HDR --v 6.1"

**LinkedIn Thought Leadership Prompt:**

> "Overhead flat lay of a signed legal contract document on a dark navy linen surface, fountain pen resting at precise angle, shallow focus on signature line, copper-toned letterhead seal partially visible, architect's drafting tools in soft background blur, cool platinum ambient light from left, documentary still life composition, rule of thirds, [UBS]"

*Example output: A $0 image that reads "premium boutique law firm," instantly distinctive vs. competitors using Getty stock.*

**Quality Gate Score for this image:**
1. Color adherence: 3 ✓
2. Composition: 3 ✓
3. People: N/A → 3
4. Background: 3 ✓
5. Lighting: 3 ✓
6. Text zone: 2 (copper seal slightly intrudes on overlay area)
7. Technical quality: 3 ✓
8. Brand differentiation: 3 ✓
9. Emotional resonance: 3 ✓
10. Channel fit: 3 ✓
**Total: 29/30 → Publish ✓**

---

**Prompt Iteration Example:**

First attempt failed — AI generated generic hands signing contract (cliché).

Fix applied:
- Added to negative prompt: `--no hands, people, body parts, fingers`
- Added to subject: "document only, no human presence, pure object photography"

Second attempt: Passed all 10 quality gates.

## Success Metrics

- **Brand consistency rate:** >90% of AI-generated images pass quality gate without human revision
- **Production speed:** Time from content brief to publish-ready image under 15 minutes (vs. 3-day designer queue)
- **Volume output:** 5-10x increase in unique visual assets per campaign without headcount addition
- **Stock photo elimination:** Zero Getty/Shutterstock purchases within 60 days of system launch
- **Engagement lift:** LinkedIn posts with custom AI images vs. stock — target 20%+ CTR improvement
- **Prompt library growth:** 50+ approved templates in first 90 days, covering all active content types
- **Team adoption:** All marketing contributors generating on-brand assets independently within 2 weeks

## Related Prompts

- [`../../03_Content-&-Creative/Content-Strategy-&-Calendar/AI-Powered-Content-Operations-&-Production-Workflow-Intelligence-Engine.md`](../../03_Content-&-Creative/Content-Strategy-&-Calendar/AI-Powered-Content-Operations-&-Production-Workflow-Intelligence-Engine.md)
- [`../../03_Content-&-Creative/Ad-&-Website-Copywriting/Dynamic-Creative-Optimization-&-Programmatic-Ad-Intelligence-Engine.md`](../../03_Content-&-Creative/Ad-&-Website-Copywriting/Dynamic-Creative-Optimization-&-Programmatic-Ad-Intelligence-Engine.md)
- [`../../01_CMO-&-Leadership/Brand-Stewardship/AI-Brand-Governance-&-Generative-AI-Content-Consistency-Intelligence-Engine.md`](../../01_CMO-&-Leadership/Brand-Stewardship/AI-Brand-Governance-&-Generative-AI-Content-Consistency-Intelligence-Engine.md)
- [`../../03_Content-&-Creative/Social-Media-Content/AI-Powered-B2B-Multi-Platform-Organic-Social-Content-Velocity-&-Pipeline-Intelligence-Engine.md`](../../03_Content-&-Creative/Social-Media-Content/AI-Powered-B2B-Multi-Platform-Organic-Social-Content-Velocity-&-Pipeline-Intelligence-Engine.md)

## Integration Tips

- **Notion/Airtable Prompt Library:** Store all approved prompts with tags (tool, content-type, channel, persona). Link each approved image asset to the prompt that generated it. Use Zapier to auto-log new image generations to the database with metadata.
- **Figma Integration:** Use Adobe Firefly's Generative Fill within Figma plugins (e.g., Magician) to generate backgrounds and fill zones directly in design files. Export final compositions with text overlays already applied.
- **HubSpot/WordPress:** Create a visual asset naming taxonomy that maps to HubSpot campaign UTMs and WordPress category tags for easy retrieval. AI-generated assets can be tagged with the prompt version for A/B testing attribution.
- **Meta Ads Manager / LinkedIn Campaign Manager:** Build a creative testing matrix — generate 4-6 image variants per campaign from the same base prompt with small parameter changes (--chaos 3/10/20, different seed values). Upload as carousel or multi-image ad sets to let the platform optimize.
- **Canva Pro:** Export approved AI images to Canva as smart mockup backgrounds. Use Canva's brand kit to overlay logos, text, and icons while keeping AI-generated backgrounds consistent.
- **Slack Workflow:** Build a Slack workflow where any team member can post a content brief → the workflow pings the prompt library → returns 3 suggested prompts → marketer runs in their AI tool → posts result for a 2-minute async approval before publish.
- **Google Sheets Prompt Tracker:** Maintain a shared Google Sheet tracking prompt → output → quality score → publish decision → performance (CTR, impressions) for continuous prompt improvement.

## Troubleshooting

**Problem: AI keeps generating images with people in the wrong cultural context or unrealistic diversity**
Solution: Be hyper-specific in people descriptions or switch to object/concept photography. Add `--no people` to test both approaches. For B2B content, most images perform equally well or better without people. If people are required, specify: "stock-photo-free authentic candid professional environment" and reference a specific scene (e.g., "software engineer reviewing code on dual monitor setup, natural window light").

**Problem: Brand suffix makes all images look too similar — creative team complains of monotony**
Solution: Create 3 "flavor" variations of your master suffix: Conservative (for enterprise/regulated content), Progressive (for thought leadership/innovation content), Editorial (for case studies/events). Rotate flavors by content type rather than using one suffix for everything. Introduce a monthly "controlled chaos" session to stress-test where brand boundaries can flex.

**Problem: AI image quality looks inconsistent — some images pass quality gate, others are unusable**
Solution: This is usually a model version or parameter problem. Pin your Midjourney prompts to a specific --v version (e.g., --v 6.1) and document it. For DALL-E 3, avoid single-word style cues (e.g., "photorealistic") — describe exactly what you see in a reference image using objective language. Build a "seed library" — save the seed numbers from your best-performing images and use them as starting points for similar content.

## Version History
- v1.0: Initial creation (auto-generated)
