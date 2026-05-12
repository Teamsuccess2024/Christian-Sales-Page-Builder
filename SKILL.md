**File path:** christian-sales-page-builder/SKILL.md

**SKILL.md - Christian Sales Page Builder (Master Orchestrator)**

**Purpose**

This skill equips Claude to write high-converting sales pages for Christian digital products, ebook bundles, faith-based courses, ministry resources, and Kingdom-focused funnels. It combines ten proven direct-response methodologies with Christian voice, scripture integration, and the specific conversion psychology of believing buyers.

The skill exists because Christian audiences respond differently than secular audiences. They have unique objections, are sensitive to manipulation, value stewardship, and convert higher when sales copy reflects servant-hearted truth-telling rather than hype.

**When to Trigger This Skill**

Claude should load this skill any time the user requests help with:

- Sales pages for Christian ebooks, bundles, or courses
- Funnel copy for faith-based digital products
- Ministry product pages or donation-adjacent offers
- Christian coaching or membership sales pages
- Upsell, downsell, or order bump copy for Christian offers
- Headlines or hooks for faith-based marketing
- Rewriting secular sales copy to fit a Christian audience
- Any landing page where the buyer is identified as a believer

Trigger words and phrases that signal this skill is needed: _Christian_, _faith-based_, _believer_, _Kingdom_, _ministry_, _ebook bundle_, _Christian funnel_, _biblical_, _scripture-anchored_, _Team Success Network_, _Purpose in Pain_, _suffering bundle_, _Christian library_.

If the user's request is ambiguous, ask one clarifying question before loading the skill: _"Is this for a Christian / faith-based audience, or general market?"_

**The Ten Methodologies**

This skill teaches Claude to write using these ten high-converting methods, each adapted specifically for Christian audiences. Full guidance for each lives in the corresponding reference file.

- **Testimony-Driven PAS** - Problem, Agitate, Solution anchored in personal or biblical testimony. See references/method-01-testimony-pas.md.
- **Scripture-Anchored Big Idea** - One contrarian biblical truth that reframes the reader's situation and becomes the page's spine. See references/method-02-scripture-big-idea.md.
- **Belief Breaking (Graziosi-Style)** - Identify and dismantle the three false beliefs blocking the sale (vehicle, internal, external). See references/method-03-belief-breaking.md.
- **Transformation Bridge** - Vivid before-and-after identity contrast with the offer as the bridge. See references/method-04-transformation-bridge.md.
- **Curated Library Frame** - Position access, curation, and order as the product (especially when content exists free elsewhere). See references/method-05-curated-library.md.
- **Value Stack with Stewardship Framing** - Build perceived value section by section, then frame the price as wise stewardship rather than expense. See references/method-06-value-stack.md.
- **StoryBrand Christian Hero's Journey** - Reader as hero, author as guide, offer as the plan, scripture as the wisdom. See references/method-07-storybrand-hero.md.
- **Awareness-Stage Layering** - Match copy depth and framing to where the reader sits on Schwartz's awareness spectrum. See references/method-08-awareness-layering.md.
- **Objection-Crushing FAQ Close** - Proactively dismantle the specific objections Christian buyers raise before checkout. See references/method-09-objection-faq.md.
- **Risk Reversal + Kingdom Urgency** - Honest guarantees paired with non-manipulative urgency rooted in the cost of continued inaction. See references/method-10-risk-reversal.md.

Not every page uses all ten. A typical sales page uses six to eight, selected based on the offer, price point, and audience awareness stage.

**Workflow**

Claude follows this sequence when building a Christian sales page.

**Step 1 - Intake**

Before writing anything, Claude runs the intake questionnaire from templates/intake-questionnaire.md to gather:

- The offer (what's being sold, format, delivery)
- The price point and any upsells or downsells
- The specific pain or aspiration the offer addresses
- The author's testimony or origin story
- Anchor scriptures and theological framing
- Target denomination range and audience awareness stage
- The transformation promised
- The full funnel path (lead magnet, tripwire, core, upsell, etc.)

If the user has not provided enough context, Claude asks the intake questions before drafting.

**Step 2 - Load Foundation References**

Claude always reads these three before drafting:

- references/philosophy.md - to anchor in Kingdom-first selling principles
- references/voice-guide.md - to calibrate Christian tone and language patterns
- references/awareness-stages.md - to match copy depth to reader awareness

**Step 3 - Select Methods**

Based on the intake, Claude chooses which of the ten methods to deploy and in what order. Selection guidance lives in references/sales-page-anatomy.md, which maps methods to page sections.

General defaults:

- **Low-ticket (\$27 and under):** Methods 1, 2, 6, 9, 10
- **Mid-ticket (\$47-\$197):** Methods 1, 2, 3, 4, 6, 7, 9, 10
- **High-ticket (\$297+):** All ten, with heavier emphasis on 3, 4, 7, and 9
- **Library or membership upsells:** Methods 4, 5, 6, 7, 10 with frame-shift from problem-solving to lifetime resourcing

**Step 4 - Draft Using the Skeleton**

Claude uses templates/full-sales-page-skeleton.md (or templates/upsell-page-skeleton.md for upsells) as the structural backbone. Headlines are generated using templates/headline-generator.md - produce twenty options, narrow to three, recommend one with reasoning.

Scripture integration follows references/scripture-integration.md. Pricing language follows references/pricing-positioning.md. Voice matching follows templates/voice-calibration.md.

**Step 5 - Self-Review Against Conversion Killers**

Before delivering, Claude reads references/conversion-killers.md and audits the draft for:

- Fake urgency or manufactured scarcity
- Prosperity-gospel language or manipulation
- Denominational landmines
- Overly churchy jargon that alienates seekers, or seeker-friendly language that feels shallow to mature believers
- Excessive hype, "secrets" framing, or guru posturing
- Theological inaccuracies in scripture usage
- Generic Christian marketing tropes

Any flag triggers a revision before output.

**Step 6 - Deliver**

Output the finished sales page with a brief annotation showing which of the ten methods were deployed and where. This helps the user understand the structure and request adjustments.

**Examples Available**

For reference and pattern-matching, fully written examples live in:

- examples/purpose-in-pain-bundle.md - \$97 Christian suffering bundle
- examples/library-upsell-297.md - \$297 full-library upsell
- examples/single-ebook-27.md - Low-ticket single ebook
- examples/coaching-program-497.md - High-ticket Christian coaching

Claude consults these when the user's request is similar to an existing example, but never copies them verbatim - the voice must match the specific author and offer at hand.

**Core Principles That Override Everything Else**

Three principles take precedence over any tactic in this skill.

**Truth over conversion.** A sentence that converts better but misrepresents the offer, the scripture, or the transformation must be rewritten. Christian audiences detect and punish exaggeration, and Claude is here to serve the reader, not extract from them.

**Servant-hearted urgency.** Urgency is biblical - "today is the day of salvation" - but manufactured urgency is manipulation. Real stakes (continued suffering without scripture, missed transformation, ongoing isolation) are fair to name. Fake countdowns and invented scarcity are not.

**Scripture handled rightly.** Verses are quoted accurately, in context, and never weaponized to pressure a sale. When in doubt about a verse's application, Claude paraphrases the principle rather than misusing the text.

**What This Skill Does Not Do**

This skill writes sales pages only. For adjacent funnel assets - ad creative, email sequences, thank-you pages, cart abandonment, retargeting - the user should request a separate funnel-builder skill or extend this one.

This skill also does not handle theology debates, denominational disputes, or doctrinal teaching. If a request crosses from marketing into teaching, Claude flags it and asks whether the user wants marketing copy or content writing.

**End of Master Orchestrator**

Proceed to load referenced files as needed based on the user's specific request.