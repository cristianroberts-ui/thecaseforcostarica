# Phase 2 — Signal Testing (Demand Validation Design)

Goal: design a fake-door test the founder can launch within 48 hours that
converts Phase 1's observed pain into a falsifiable demand measurement.
Everything is pre-committed: thresholds are set before the test runs, so the
result cannot be rationalized afterward. Populate
`templates/test-plan-template.md` as the deliverable.

## Landing page concepts (2–3)

Each concept must be specific enough to be uncomfortable — a vague page
measures nothing. Every concept specifies, exactly:

- **Headline:** names the customer and the outcome, not the category.
  ("Bookkeeping done for your Etsy shop by Friday — $99/mo" not "Smart
  finance for sellers.")
- **Subhead:** the mechanism or proof point in one sentence.
- **CTA:** the exact button text and what it commits the visitor to
  ("Join the waitlist", "Get early access at $99/mo", "Reserve a founding
  spot").
- **Price anchor:** a visible price or price range on the page. A page with
  no price tests curiosity, not demand. Use the intake price hypothesis,
  cross-checked against Phase 1 comparables.

Vary exactly one primary axis between concepts (angle, price, or customer
segment) so a winner is interpretable. State which axis is being tested.

Tooling: Carrd, Framer, or Unbounce for the page (buildable in hours);
ConvertKit, MailerLite, or the page tool's native capture for email; a
simple thank-you page that sets honest expectations (see guardrails).

## Ad channel selection

Pick one primary channel and justify the choice in the plan. Selection
heuristics:

| Channel | Best fit | Watch out |
|---|---|---|
| Google Search | Existing, named demand — people already searching for the task or an incumbent alternative | Low search volume kills it; check keyword volume first |
| Meta (FB/IG) | Consumer products, visual demos, interest-based audiences | Weak for niche B2B; creative quality dominates |
| LinkedIn | B2B with a targetable job title/industry | CPCs often $8–$15+; a $250 budget buys few clicks — say so if chosen |
| Reddit | A niche with active subreddits found in Phase 1 | Strict community norms; conversational creative only |

Default rule: if Phase 1 found people *searching* for solutions, use Google;
if it found people *complaining in communities*, use Reddit or Meta; if the
buyer is defined by job title, use LinkedIn and shrink the click target.

## Budget, duration, and sample floor

- Budget: $50–$250 total. Allocate per concept (even split unless one
  concept is the clear primary hypothesis).
- Duration: 5–10 days, or stop early once the sample floor is met.
- Sample floor: **≥100 landing page visitors per concept** before judging
  capture rate; below that, results are directional only and the plan must
  say so. At these budgets nothing is statistically significant — the test
  measures order-of-magnitude interest, not precise conversion.

## Pre-committed thresholds

Benchmarks below are planning heuristics from commonly cited industry ranges
— they vary by niche; cite them as ranges, and tag them `[ASSUMPTION —
industry heuristic]` in the report. Set the actual thresholds relative to
the chosen channel's norms.

| Metric | Weak | Acceptable | Strong |
|---|---|---|---|
| CTR — Google Search | <2% | 3–5% | >6% |
| CTR — Meta | <0.8% | ~1–1.5% | >2% |
| CTR — LinkedIn | <0.4% | ~0.5–0.8% | >1% |
| CTR — Reddit | <0.3% | ~0.5–0.9% | >1% |
| Email capture rate (visitor → email) | <5% | 10–20% | >25% |
| Cost per email signal | > expected first-month price | ≈ comparable-product CAC/LTV sanity | well below price point |

## Decision tree (pre-committed, written before launch)

- **KILL** — capture rate <5% at the sample floor AND CPC at or above channel
  norm AND no qualitative interest (no replies, no shares, no DMs). Write
  the kill memo; do not relaunch variants of the same offer.
- **PIVOT** — strong CTR but weak capture (offer or price problem: rework
  page, keep audience), or weak CTR but strong capture among those who
  arrive (audience/targeting problem: keep offer, change channel/targeting),
  or Phase 1 reframe signals surfacing in ad comments. One pivot cycle, then
  re-judge against the same thresholds.
- **DOUBLE-DOWN** — capture ≥15% at acceptable cost per signal, or any
  unsolicited payment attempts / "when can I buy" replies. Proceed to
  Phase 4 execution and immediately email the captured list.

The founder signs these thresholds before spending a dollar. The report
presents the tree as a table with exact numbers filled in for the chosen
channel.

## Ethical guardrails (mandatory section in the plan)

- The page must be honest about product status: "coming soon", "join the
  waitlist", or "founding customer preorder" — never imply a shipping
  product that does not exist.
- Take no payment for a nonexistent product. If testing payment intent, use
  a clearly labeled refundable deposit or a "reserve your spot — card not
  charged until launch" mechanism, with terms stated on the page.
- Email every captured lead within days with an honest status update and a
  way to opt out. Captured emails are used only for this product's updates.
- Include a minimal privacy note on the page; collect email only.
- Comply with ad platform policies (no fabricated claims, no fake
  testimonials, no invented statistics in creative).

## Deliverable

A filled `templates/test-plan-template.md`: concepts with exact copy, channel
justification, targeting parameters, ad creative and copy variants, budget
and schedule, thresholds table, decision tree with numbers, guardrails, and
an hour-by-hour 48-hour launch checklist.
