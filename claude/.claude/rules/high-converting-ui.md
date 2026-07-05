---
paths:
  - "**/*.tsx"
  - "**/*.jsx"
  - "**/*.vue"
  - "**/*.svelte"
  - "**/*.html"
  - "**/*.astro"
  - "**/*.css"
---

# High-Converting UI

When designing, critiquing, or improving any screen where a user makes a decision (buy, subscribe, sign up, book, upgrade), apply conversion psychology — not just visual polish. Always give the **rule + the reason + the concrete pattern**, not vague advice.

## The core idea

> Every element on a screen asks the user a question. The question you ask determines whether they act or hesitate.

"Is this worth $19/mo?" is a hard question → hesitation. "Can I try it free?" is an easy question → action. Before shipping a screen, name the question each element asks; if it's hard, rewrite it to be easy. Users are not logical: defaults read as recommendations, the first number sets the anchor, a gift creates a debt, building something makes it theirs, progress creates momentum.

## Principle library (rule → why → pattern)

**Reduce the cost of deciding**
- **A1 Ask the easy question** — reframe hard → easy. CTA frames the low-commitment next step, not the terminal commitment. "How your free trial works" > "Get access — $19/mo".
- **A2 Smart defaults** — 70–90% never change a default; it reads as a recommendation. Pre-select the target option with "Most Popular"; pre-fill forms; button = "Show 12 results" not blank "Search".
- **A3 Fewer choices** — jam study: 24 options → 3% bought, 6 → 30%. Show ≤3 tiers; collapse the rest behind "More options".
- **A4 Recognition over recall** — for <5 options, kill the dropdown; use visible swatches/cards. A dropdown forces click→scroll→read just to see choices.
- **A5 Progressive disclosure** — clean initial view; reveal detail on interaction (clicking a choice expands bundle tiers).
- **A6 Evaluative ease** — options comparable in ~2s. One number per option; show totals so there's no math.

**Frame and anchor**
- **B1 One number, never a range** — the brain anchors a range to its high end. "$14" not "$13–$17".
- **B2 Control the first number (contrast)** — never show cost in isolation; place it after a larger related number. $50 under a $1,900 laptop labeled "just 2.6%" feels like nothing.
- **B3 Strikethrough anchor** — ~~€129~~ **€89** `−31%`. Anchoring working for you.
- **B4 Specificity is trust** — round numbers read as fake. "4.9 stars, 221 reviews", "start in 2 taps", "delivery in 23 minutes". The number does the convincing.

**Build trust and remove risk**
- **C1 Transparency bias** — volunteer a downside and users trust you more. "Day 5: we'll remind you before your trial ends" beats three feature bullets.
- **C2 Reciprocity** — give real value before asking for signup/email/pay (Cialdini; free samples lift purchases ~2000%). Show a partial useful result, then "Save your report". Never blur results behind a signup wall.
- **C3 Social proof** — "500+ sold this week", specific review counts, "guest favorite" badges. Converts "should I be first?" into "hundreds chose this".
- **C4 Halo badge** — "Best Seller" badge *above* the title frames the whole product before a detail is read.
- **C5 Answer the unspoken objection specifically** — generic trust text ("Free shipping") builds nothing. Name the actual fear: "third-party tested for heavy metals", "free cancellation", total-price-on-button.

**Create investment and momentum**
- **D1 Goal gradient (never start at 0%)** — count something already done. Car-wash study: 10-stamp card with 2 pre-filled beat an 8-stamp blank ~2×. Open onboarding at ~20%.
- **D2 IKEA / endowment** — let users build/customize before signup; closing the tab then feels like abandoning something they made. Button = "Continue" not "Sign up".
- **D3 Loss aversion** — pain of losing is ~2× the pleasure of gaining (Kahneman). Show the specific thing at risk; make the escape hatch admit the cost ("I'll risk it" not "Maybe later").
- **D4 Commitment & consistency** — lock a small easy commitment first (chosen destination/plan), so the real ask is "keep or change" not "choose from scratch".

**Copy**
- **E1 Weigh your verbs** — "Start" (light) not "Subscribe" (locked in). "Continue" not "Sign up".
- **E2 "My" not "your"** — "Start **my** free trial" creates ownership before the tap.
- **E3 Sensory/emotional language** — describe the experience, not the specs. "Beachside escape, steps from the sand" transports; "Beach house with garden" informs.
- **E4 One word categorizes** — a small green "Cheaper" badge pre-decides the choice.

**Imagery and hierarchy**
- **F1 Show, don't decorate** — every image answers "what am I getting?". Real content/product-in-use, not abstract art.
- **F2 Bridge the imagination gap** — show product *and* its result together (the tub next to the mixed glass).
- **F3 Transport, don't inform** — large hero imagery for aspirational products; thumbnails only for dense lists.
- **F4 First/second/third glance** — badge → hero → title → proof → decision → CTA. Reserve the accent color for the target choice + primary CTA only.

## Screen playbooks (ordered moves)

- **Product page:** halo badge (C4) → hero shows product in use (F1/F2) → specific social proof (B4/C3) → swatches not dropdowns (A4) → side-by-side cards, target pre-selected + "Most Popular", reassurance inside the card (A2/D4) → progressive-disclosed bundles (A5) → reframed CTA + audience-specific trust icons (E1/C5).
- **Paywall/trial:** ask "can I try free?" (A1) → trial timeline with pre-charge reminder (C1) → verb "Start", "my", step count (E1/E2/B4) → hero shows real unlocked content (F1).
- **Pricing:** anchor a higher tier (B2) → one number per tier, ≤3 tiers (B1/A3) → pre-select target + "Most Popular" (A2) → strikethrough savings (B3) → add-ons priced relative to main purchase (B2).
- **Onboarding:** never start at 0% (D1) → build/customize before signup, button "Continue" (D2/E1) → smart defaults (A2) → deliver a real result before the account ask (C2).
- **Booking:** large imagery + sensory title (F3/E3) → strikethrough + %off (B3) → cost→convenience ("2 min away", night count) (A6) → total price on button + free-cancellation line (C5/C1) → destination locked first (D4).
- **Forms:** pre-fill everything inferable (A2) → minimum fields, progressive disclosure (A3/A5) → button states outcome + count ("Reserve · €445 total"), never blank "Submit" (A6/B4).

## Anti-patterns to flag

Blank forms; round numbers as fake data; dropdowns for 2–3 options; equal-weight radios where one should be nudged; "Add to cart"/"Subscribe"/"Submit" verbs; price ranges and unanchored prices; value locked behind a signup wall before any value given; decorative hero art; generic trust badges; onboarding at 0%; everything framed as a gain with a frictionless "Maybe later".

> The test: a screen that does everything "right" and still feels *fine* usually fails — *fine doesn't convert*. Informing the user isn't enough; you have to move them.
