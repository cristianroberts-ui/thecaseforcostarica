# Step 0 — Mandatory Intake Protocol

Intake is blocking. Ask everything in one batched pass, wait for the answer,
and only then begin Phase 1. Never interleave analysis with intake, and never
ask these questions across multiple rounds — one pass, then work.

## How to ask

- If `AskUserQuestion` is available, use it. It caps at 4 questions per call,
  so send the battery as two back-to-back calls (groups A–D, then E–G), or
  fall back to a single plain-text message containing all seven groups.
- If asking in plain text, number the questions exactly as below so the user
  can answer by number, and say explicitly: partial answers are fine — any
  gap will be filled with a stated assumption.
- Keep the intake message short. No preamble about the methodology; one
  sentence of framing, then the questions.

## The question battery

**A. Idea and pain hypothesis**
1. State the idea in one sentence.
2. Who specifically has the pain, and what is your hypothesis about the pain
   (what do they struggle with today, in their words if you have them)?

**B. Market and geography**
3. Target market segment (consumer / SMB / mid-market / enterprise, vertical
   if any) and geography (country or region; where would you sell first?).

**C. Founder advantages, assets, constraints**
4. What unfair advantages do you have (domain expertise, audience, network,
   distribution, proprietary data, technical skill)?
5. What existing assets can you deploy (email list, social following, code,
   content, partnerships)?
6. Constraints: available capital for validation, hours per week, team (solo
   or with others, and their skills)?

**D. Revenue model and price**
7. How do you hypothesize this makes money (subscription, one-time,
   usage-based, services, marketplace take rate)?
8. What price point range do you have in mind, even a rough one?

**E. Risk tolerance and timeline**
9. Risk tolerance: do you need this to work (income-critical) or is this a
   portfolio bet you can afford to kill?
10. Target timeline to first revenue?

**F. Existing evidence**
11. What evidence already exists — waitlist signups, customer conversations,
    prior tests, preorders, a current side project? Numbers if you have them.

**G. Report audience**
12. Who is this report for — your own decision, business partners, an
    investment committee, or LPs? (This calibrates depth on unit economics
    and market sizing, not the register — register is always institutional.)

## Default assumptions for unanswered items

When answers arrive, restate what was provided, then list — verbatim, in a
table — the assumption adopted for each unanswered item. Copy every adopted
assumption into the report's Key Assumptions Log with tag `[ASSUMPTION —
intake default]`.

| Item | Default assumption when unanswered |
|---|---|
| Pain hypothesis (2) | Derive from the one-sentence idea; treat the derived pain as hypothesis, not evidence |
| Market/geography (3) | Founder's home market; consumer vs B2B inferred from the idea; flag inference |
| Advantages (4) | None assumed — founder-fit scored conservatively (≤2/5) until evidence provided |
| Assets (5) | None assumed |
| Constraints (6) | Solo founder, ≤10 hrs/week, ≤$500 validation budget |
| Revenue model (7) | Most common model for the category; state which and why |
| Price point (8) | Anchor to nearest comparable product found in Phase 1; disclose the comparable |
| Risk tolerance (9) | Moderate — cannot absorb >6 months of dead-end effort |
| Timeline (10) | First revenue within 90 days |
| Existing evidence (11) | None — all demand claims must come from Phase 1 research |
| Audience (12) | Personal decision; full IC structure and register retained regardless |

## Hard rules

- If the user answers with "just proceed" or equivalent, that is a valid
  response: adopt every default above, list them, and proceed.
- If the user supplies a new or changed idea mid-analysis, stop, re-run
  intake deltas for what changed, and restate assumptions before continuing.
- Do not ask follow-up clarifying questions after the batch unless an answer
  is genuinely unintelligible; prefer a stated assumption over a second round.
