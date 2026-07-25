---
paths:
  - "**/*.tsx"
  - "**/*.jsx"
  - "**/*.vue"
  - "**/*.svelte"
  - "**/*.html"
  - "**/*.astro"
  - "**/*.mdx"
---

# Conversion Page Anatomy

When building or restructuring a **whole page** (landing, homepage, service/SEO, contact, collection, product detail), decide the section list and order *before* writing any element. This rule owns section architecture; the companion `high-converting-ui` rule owns the words and elements inside each section.

Page anatomy below is distilled from the wireframe framework published by **ThrillX** ([@arsh-sanwarwala](https://www.youtube.com/@arsh-sanwarwala)) — see [How To Build The PERFECT Landing Page](https://www.youtube.com/watch?v=tAzpvg0TDZc).

## The core idea

> A long page is not a cognitive burden if every section is self-contained and terminates in the same single action.

The instinct to shorten a page confuses *choice load* (bad, governed by Hick's Law) with *scroll length* (neutral). You do not know where conviction happens — different readers are persuaded by the pain section, the comparison, the guarantee, or the FAQ. The page's job is to make every one of those moments actionable.

## The canonical spine (full-length form)

Order is fixed; templates omit sections but never reorder them.

1. **Nav** — logo · phone · CTA. Page links *only* on website pages, never on a landing page.
2. **Proof micro-line** — borrowed credibility above the headline.
3. **Hero** — 6 fixed slots (below).
4. **Proof strip** — heavier tier just below the fold.
5. **Pain / old way** — conditional; name the pain, attack the status quo, tie in your differentiator.
6. **Proof section** — first full-bleed block: stats, testimonials, case studies.
7–9. **Benefit blocks ×3** — eyebrow → benefit headline → media → mechanism → CTA. Same shape three times.
10. **Proof section** — second full block.
11. **Differentiators** — 3- or 6-cell grid: how you do it, why that differs.
12. **How it works** — exactly 3 steps. Job is *perceived effort reduction*, not information.
13. **Team / About** — optional.
14. **Guarantee** — omit only if you genuinely cannot offer one. Risk reversal is high-leverage.
15. **Proof strip** — frames the FAQ.
16. **FAQ** — 6 questions (4 + media on ecom). Last objection sweep.
17. **Ancillary** — website only: blog, locations, resources. SEO surface.
18. **Final close** — mirrors the hero.
19. **Footer**

## Cadence rules (the page-scale rules most often missed)

- **One CTA per section** — roughly one per 800px of scroll. Every section terminates in the CTA; no section is a dead end. Always the *same* action — there is no secondary-CTA ladder. This is reinforcement, not choice (the set stays at n=1), so it does not violate Hick's Law.
- **Social proof is tiered, at five depths** — micro-line (~20pt: rating, count, logos), strip (~32pt: logo bar), full section (~44pt: testimonials, stats, UGC). Micro-line and strip each appear **twice**, bracketing the page: above the H1, above the FAQ, above the close.
- **Friction copy goes *below* the button** — ~70px under every primary CTA, never above. Above it, it's preamble; below, it's reassurance at the moment of hesitation.
- **The close mirrors the hero** — proof line → outcome headline → media → value-prop triple → CTA → friction line. The last screen restates the first.
- **Nav is the tell** — landing pages have no page links (every exit that isn't the CTA is removed); website pages have them; ecom uses in-page anchors plus an announcement bar.
- **Length is set by funnel position** — cold traffic (landing, homepage) ~10,000px and 12–13 modules; mid-funnel (service, PDP) ~9,000px; down-funnel (contact) ~3,400px and 7 modules; browse (collection) ~1,700px. Shortening a cold-traffic page to "reduce cognitive load" is the most common way to break one.

## Hero — 6 slots, fixed order

Proof micro-line → headline → media → subhead → CTA → friction line.

- **Headline formula:** `Dream outcome (End Result, Time Period, Emotional Payoff)`. The outcome, not the product, not the company.
- **Subhead formula:** negation hook + mechanism — `"Stop doing X" | "No more Y" | "Pain Point"`, then *our solution does X, Y, Z* **and how you do it in a proprietary or unique way**. A benefit without a mechanism is just a claim.
- **Media must satisfy all 3 buying dimensions:** *Functional* (solves a specific problem), *Emotional* (confident, secure, excited), *Social* (status, image, belonging).

## Page-type variants

- **Landing (canonical)** — full spine, no nav links. Hero media may be image, video, or form.
- **Landing, form-in-hero** — form + 3 value props replaces hero media; differentiator grid becomes a you-vs-5-competitors table; drops team and guarantee. ⚠️ Contradicts reciprocity unless the form *is* the value (instant quote, calculator, audit) or traffic is high-intent.
- **Ecom** — announcement bar (free shipping / guarantee), anchor nav, product grids with per-card tag + rating + inline add-to-cart, two 7-icon benefit belts, money-back section, an "additional offer" secondary path for non-buyers.
- **PDP** — buy box above fold, then the full spine below. Buy box order: rating + count → tag → H1 as `{Biggest Benefit} - {Product Name}` (benefit first) → price anchor pair + `You Save $X (X%)` → benefit chips → numbered variant pickers with option counts → bundle ladder with "Most Popular" on the middle tier → `Total:` with the anchor **repeated** → add-to-cart → guarantee/return/shipping trio directly beneath → details/FAQ/how-it-works/shipping accordion.
- **Homepage** — adds page links, a services/solutions grid routing to sub-pages, and a blog/locations ancillary block. Pain section becomes conditional.
- **Service / Location / Course (SEO)** — eyebrow above H1 becomes the target keyword; proof micro-line moves *below* the CTA. Use for feature, use-case, and pillar pages.
- **Contact** — 6 sections only: form hero (5 value props) → proof → how it works → proof strip → FAQ → footer. No benefit blocks, differentiators, team, guarantee, or urgency close. 3 CTAs total.
- **Collection** — abandons the spine. Rating bar → title → sort + availability/price filters → card grid. Persuasion lives in the **card**: tag + rating + price anchor trio + button.

## Block copy formulas

- **Benefit block ×3** — `DREAM OUTCOME SUMMARY` eyebrow → benefit headline ("what's in it for me") → media → mechanism sentence → CTA.
- **Pain section** — paint the prospect's pain vividly, expose the flaws of the status quo, then tie in your differentiator. This is a status-quo attack, distinct from loss aversion (which targets the user's own assets at risk).
- **How it works** — exactly 3 steps. Headline is count-forward ("…in 3 steps") or effort-collapse ("Install in 5 min, no special tools"). Each step = action headline + one detail line. **The last step is the emotional payoff, never a task** — "Watch their face light up", not "Receive your order".
- **Comparison table** — your column pairs claim + substantiating proof; their column gets dismissive specifics. Rows are *negated mirrors* in the same order, so the reader doesn't have to do the diffing.
- **Final close** — fill "why act today" with the reader's *existing pain persisting*, tied back to the pain section. Not a manufactured deadline.

## PDP image carousel (a separate artifact from the page)

Square slides, in this order: **1. Plain product shot** (required) → **2. Problem visualization** (if applicable) → **3. How it works** (required) → **4. Social proof** (required) → **5. Reduce FUDs / risk reversal** (required) → **6. Comparison** (if applicable) → **7. Lifestyle** (required).

- **Problem visualization** — `BEFORE | VS | AFTER`, 3-vs-3 mirrored rows, parallel phrasing, same order both sides.
- **How it works** — 3 numbered steps, count in the headline, emotional payoff last.
- **Social proof** — UGC tiles, star rating, named attribution, exact review total.
- **Comparison** — two columns, negated mirror rows, claim + proof pairs.
- **Lifestyle** — product in context; add an occasion grid if gift-relevant.

## Pairing — slots vs contents

This rule's labels are **slot names, not shippable copy**. Every one gets filled under `high-converting-ui`: CTA labels → verb weight, "my" not "your", button states the outcome; "reduce FUDs" → name the audience's *actual* fear; rating/review placeholders → exact non-round numbers; prices → one number, never in isolation, strikethrough + % off; variant pickers → swatches not dropdowns, pre-select the target; urgency → name the concrete loss.

## Anti-patterns to flag

A single CTA at the top and nothing for 8,000px · two *competing* CTAs in one section · proof in only one place · friction copy above the button · a cold-traffic page shortened for "cognitive load" · a contact page built to landing-page length · page links in a landing-page nav · a benefit with no mechanism · how-it-works with 5+ steps or a final step that's a task · comparison rows that aren't parallel · collection cards with no rating, tag, or price anchor · shipping the slot labels literally.

> The test: open the page, pick any section at random, and ask *"if the reader were convinced right here, could they act without scrolling?"* If not, the spine is incomplete.
