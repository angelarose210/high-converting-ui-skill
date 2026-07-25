# High-Converting UI

There are plenty of design skills that make your site look *pretty*. Pretty doesn't pay the bills. A gorgeous landing page that still asks the visitor a hard question at the wrong moment converts exactly as badly as an ugly one — sometimes worse, because now it looks like effort was spent and *still* nobody's buying.

This repo ships **two skills that work as a pair**, on the two layers that actually move the number:

| Skill | Owns | Unit of work |
|---|---|---|
| **high-converting-ui** | The persuasion psychology inside a decision — verbs, anchors, defaults, proof, imagery | Elements in a screen |
| **conversion-page-anatomy** | The section architecture of a whole page — what blocks exist, in what order, how often the CTA repeats | Sections in a scroll |

They're deliberately separate because they fail differently. The first one's failure mode is *"the button says Subscribe."* The second one's is *"there's no guarantee section and the CTA appears once."* Fixing one doesn't fix the other.

Use them together: **page-anatomy defines the slots, high-converting-ui fills them.**

---

## high-converting-ui

Teaches your AI to design and critique screens the way a conversion-rate optimizer would — naming the question every element asks the user, and rewriting the hard questions ("Is this worth $19/mo?") into easy ones ("Can I try it free?"). Same product, same price, same traffic; one framing converts multiples better than the other.

Distilled from real product-page, paywall, pricing, and booking teardowns, and grounded in named research (Iyengar's jam study, Kahneman's loss aversion, Cialdini's reciprocity, the car-wash goal-gradient study). Every recommendation comes with the **rule, the reason, and the concrete UI pattern** — never gut-feel.

- **26 named principles** — anchoring, loss aversion, goal gradient, reciprocity, smart defaults, halo effect, progressive disclosure, and more. Each with the research behind it and the exact pattern that applies it.
- **Screen-type playbooks** — ordered move-lists for product pages, paywalls, pricing pages, onboarding, booking flows, and forms.
- **A conversion audit checklist** — point it at a screen and it flags every doubt-creating element, names the principle, and gives the specific fix.

```
Use high-converting-ui to critique my pricing page and tell me what's killing conversions.
```

**Example.** Input: a paywall reading *"Get access to 1,000 games — $19/mo"* with a decorative space illustration. Output: reframe to *"Start my free trial"* (E1/E2), add a trial timeline with an explicit "Day 5: we'll remind you before you're charged" line for transparency-bias trust (C1), swap the decorative art for real game characters so the user can picture what they're unlocking (F1), and add "no charge today, cancel anytime" beneath the button (C5). Same product, same price — a far easier question to say yes to.

---

## conversion-page-anatomy

Most conversion advice operates on one screen. This one operates on the **whole page** — and the rules that only exist at page scale are the ones most often missed.

- **The canonical spine** — the ~19-section order, with which sections are required, optional, and conditional.
- **Cadence rules** — one CTA per section (~800px apart, always the *same* action); social proof tiered across five depths, bracketing the page; friction copy always *below* the button; the closing section mirrors the hero.
- **Page-type variants** — landing, form-in-hero, ecom, PDP, homepage, service/SEO, contact, collection. Each with its section list and target length, because **length is set by funnel position**: ~10,000px for cold traffic, ~3,400px for contact, ~1,700px for a collection page.
- **Copy formulas per block** — headline (`End Result, Time Period, Emotional Payoff`), the negation-hook subhead, the 3-step how-it-works whose last step is an emotional payoff rather than a task, the negated-mirror comparison table.
- **The PDP image carousel** — a 7-slide sequence (5 mandatory, 2 conditional) for product galleries, which is a separate artifact from the page itself.

```
Use conversion-page-anatomy to lay out a landing page for my SaaS, then high-converting-ui to write the CTAs.
```

```
Use conversion-page-anatomy to audit my homepage — what sections am I missing?
```

**The one idea it hangs on:** a long page is not a cognitive burden if every section is self-contained and terminates in the same single action. You don't know where conviction happens — different readers are persuaded by the pain section, the comparison, the guarantee, or the FAQ. The page's job is to make every one of those moments actionable.

### Three tensions between the two skills, already resolved

Both skills document these, so you don't have to rediscover them:

1. **CTA repetition doesn't violate Hick's Law.** Hick's governs *simultaneous distinct* choices. Twelve instances of one identical action keeps the choice set at n=1. Two *competing* CTAs in one section is the real violation.
2. **Progressive disclosure is about interaction depth, not page length.** Collapse detail *inside* the decision zone (accordions); expand it below the fold. A long scroll of self-contained sections isn't cognitive load.
3. **Form-in-hero genuinely contradicts reciprocity.** Gating value behind a form before delivering any is the "card before the menu" problem. It's only defensible when the form *is* the value (instant quote, calculator, free audit) or traffic is high-intent.

---

## Install

Both skills install the same way; take one or both.

### Hermes
Copy `hermes/marketing/high-converting-ui/` and `hermes/marketing/conversion-page-anatomy/` to `~/.hermes/skills/marketing/`

### Codex CLI
Copy `codex/.agents/skills/high-converting-ui/` and `codex/.agents/skills/conversion-page-anatomy/` to `.agents/skills/` in your project

### OpenClaw
Copy `openclaw/skills/high-converting-ui/` and `openclaw/skills/conversion-page-anatomy/` to `.agents/skills/` in your project

### Claude Code
Copy `claude/.claude/rules/high-converting-ui.md` and `claude/.claude/rules/conversion-page-anatomy.md` to `.claude/rules/` in your project.

Both are scoped to frontend files (`.tsx`, `.jsx`, `.vue`, `.svelte`, `.html`, `.astro`, plus `.css` / `.mdx`), so they load only when you're working on UI. These are condensed variants of the full skills — same principles, compressed for always-on rule context.

## Pairs Well With

A visual-craft skill (typography scale, spacing rhythm, color systems). These two own *persuasion* and *architecture*; a craft skill owns the *aesthetic* layer. High-converting **and** beautiful = ship all three.

## Not Included

These are the distilled frameworks — the principle library, playbooks, spine, and checklists. They deliberately do **not** bundle:

- **Source video transcripts, key frames, or screenshots.** `high-converting-ui` was distilled from third-party UX case-study videos; those copyrighted materials aren't redistributed. Every principle is stated in full on its own terms, so the skill is fully standalone.
- **Source wireframe files or template extracts.** `conversion-page-anatomy` was distilled from a survey of production page structures; no third-party design files are redistributed. The section spine, cadence rules, and formulas are stated in full.
- **Named brands as case data.** Brand names appear only as widely-known illustrations of a public pattern, not as endorsements or proprietary data.
- **Any tooling or pipeline** used to produce the original analysis.

Cited research is public — look up the primary sources directly.

## License

MIT
