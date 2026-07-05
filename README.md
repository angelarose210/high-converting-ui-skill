# High-Converting UI

There are plenty of design skills that make your site look *pretty*. Pretty doesn't pay the bills. A gorgeous landing page that still asks the visitor a hard question at the wrong moment converts exactly as badly as an ugly one — sometimes worse, because now it looks like effort was spent and *still* nobody's buying.

This skill works on the layer that actually moves the number: the **persuasion psychology** underneath the pixels. It teaches your AI to design and critique screens the way a conversion-rate optimizer would — naming the question every element asks the user, and rewriting the hard questions ("Is this worth $19/mo?") into easy ones ("Can I try it free?"). Same product, same price, same traffic; one framing converts multiples better than the other.

Distilled from real product-page, paywall, pricing, and booking teardowns, and grounded in named research (Iyengar's jam study, Kahneman's loss aversion, Cialdini's reciprocity, the car-wash goal-gradient study). Every recommendation comes with the **rule, the reason, and the concrete UI pattern** — never gut-feel.

## What It Does

- **Turns "looks nice" into "converts"** — 26 named principles (anchoring, loss aversion, goal gradient, reciprocity, smart defaults, halo effect, progressive disclosure, and more), each with the research behind it and the exact pattern that applies it.
- **Ships screen-type playbooks** — ordered move-lists for product pages, paywalls, pricing pages, onboarding, booking flows, and forms. Pick the screen, follow the moves.
- **Runs a conversion audit checklist** — point it at an existing screen and it flags every doubt-creating element, names the principle, and gives the specific fix.

## Quick Start

```
Use high-converting-ui to critique my pricing page and tell me what's killing conversions.
```

```
Use high-converting-ui to redesign this paywall so it asks an easier question.
```

## Example

**Input:** a paywall reading *"Get access to 1,000 games — $19/mo"* with a decorative space illustration.

**Output:** reframe to *"Start my free trial"* (E1/E2), add a trial timeline with an explicit "Day 5: we'll remind you before you're charged" line for transparency-bias trust (C1), swap the decorative art for real game characters so the user can picture what they're unlocking (F1), and add "no charge today, cancel anytime" beneath the button (C5). Same product, same price — a far easier question to say yes to.

## Install

### Hermes
Copy `hermes/marketing/high-converting-ui/` to `~/.hermes/skills/marketing/`

### Codex CLI
Copy `codex/.agents/skills/high-converting-ui/` to `.agents/skills/` in your project

### OpenClaw
Copy `openclaw/skills/high-converting-ui/` to `.agents/skills/` in your project

### Claude Code
Copy `claude/.claude/rules/high-converting-ui.md` to `.claude/rules/` in your project.
It's scoped to frontend files (`.tsx`, `.jsx`, `.vue`, `.svelte`, `.html`, `.astro`, `.css`), so it loads only when you're working on UI.

## Pairs Well With

A visual-craft skill (typography scale, spacing rhythm, color systems). This skill owns the *persuasion* layer; a craft skill owns the *aesthetic* layer. High-converting **and** beautiful = ship both.

## Not Included

This is the distilled framework — the principle library, playbooks, and audit checklist. It deliberately does **not** bundle:

- **Source video transcripts, key frames, or screenshots.** The framework was distilled from third-party UX case-study videos; those copyrighted materials aren't redistributed. Every principle is stated in full on its own terms, so the skill is fully standalone.
- **Named brands as case data.** Brand names appear only as widely-known illustrations of a public pattern, not as endorsements or proprietary data.
- **Any tooling or pipeline** used to produce the original analysis.

Cited research is public — look up the primary sources directly.
