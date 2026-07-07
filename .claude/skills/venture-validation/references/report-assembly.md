# Final Assembly — IC-Grade Report

Populate `templates/report-template.md` in full, then render to DOCX
(preferred) or PDF. The report must stand alone: a committee member who
never saw this conversation can read it and decide.

## Register rules (enforced throughout)

- **Answer-first:** the recommendation is the first sentence of the
  executive summary, not the conclusion of it.
- **Evidence-forward:** lead paragraphs with the finding, follow with the
  support. No claim without a source citation or `[ASSUMPTION]` tag.
- **No marketing language:** delete superlatives, momentum words, and
  category hype. "Reviews on three platforms describe the same failure" —
  not "massive underserved market."
- **Decisive with honest gaps:** the recommendation never hedges; the gaps
  section carries the uncertainty instead.

## Recommendation and conviction

- **GO** — evidence supports proceeding to the Phase 4 roadmap now.
- **CONDITIONAL GO** — proceed only after named conditions; each condition
  states its metric, threshold, and deadline (typically: the Phase 2 test
  clearing its pre-committed thresholds). This is the most common honest
  outcome for a pre-test idea, since Phase 2 is designed, not yet run.
- **NO-GO** — evidence contradicts the opportunity or founder-fit. State
  explicitly what new evidence would reverse the verdict.

Conviction level: **High / Moderate / Low**, with one sentence on what
drives it (usually sample size and evidence directness). A NO-GO can carry
high conviction; a GO on thin evidence cannot.

## Scoring matrix

Score five dimensions, 1–5, with stated weights (defaults below — adjust
with justification), one paragraph of rationale per row citing evidence:

| Dimension | Weight | What 5 looks like | What 1 looks like |
|---|---|---|---|
| Demand evidence | 30% | Composite pain ≥4, many voices, WTP signals | Thin/contradictory signals |
| Competitive position | 15% | Clear wedge incumbents can't cheaply copy | Crowded, undifferentiated |
| Founder-fit | 20% | Unfair advantage maps to the wedge | No stated advantage (intake default) |
| Unit economics hypothesis | 20% | Payback < 6 mo on conservative inputs | Payback implausible at hypothesized price |
| Execution risk | 15% | MVP concierge-able within constraints | Requires capital/skills the founder lacks |

Weighted total out of 5.0; state the mapping used (e.g., ≥3.8 supports GO,
2.8–3.7 CONDITIONAL, <2.8 NO-GO) and apply it consistently — the matrix must
agree with the recommendation or the divergence must be explained.

## TAM / SAM / SOM — methodology disclosed

- Compute **both** top-down (market reports, disclosed with source and year)
  and bottom-up (count of target customers × realistic price × plausible
  penetration). Present ranges, not points. Bottom-up is the load-bearing
  number; say so.
- Every input is cited or tagged `[ASSUMPTION]`. Show the arithmetic.
- SOM is bounded by the founder's actual channel capacity from Phase 3/4
  (outreach quota × conversion), not a percentage plucked from TAM.

## Competitive landscape

Table of direct competitors, adjacent substitutes, and the do-nothing/DIY
option (always include DIY — Phase 1 workarounds prove it is the real
incumbent). Columns: who, offer, price, wedge this venture exploits,
counter-risk. Follow with a short positioning paragraph.

## Preliminary unit economics

All labeled hypothesis. Inputs trace to phases:

- **CAC hypothesis:** from Phase 2 cost-per-signal × an assumed
  signal→customer conversion (state the assumed rate and its basis).
- **LTV hypothesis:** price (intake/Phase 2 anchor) × gross margin ×
  expected lifetime (cite comparable churn norms or tag as assumption).
- **Contribution margin:** price minus direct delivery cost — for a
  concierge MVP, include the founder's time at a stated hourly value.
- **Payback period:** CAC ÷ contribution per period. Show the arithmetic
  and run a pessimistic case (halve conversion, double CAC) alongside the
  base case.

## Risk register

Top 5–8 risks. Columns: risk, category (demand / execution / competitive /
regulatory / personal-founder), likelihood (H/M/L), impact (H/M/L),
mitigation, early-warning indicator (tie to the Phase 3 dashboard where
possible). Regulatory risks must reflect the intake geography.

## Key assumptions log

Single table, every assumption in the report in one place:

| # | Claim | Status | Source / validation path |
|---|---|---|---|

Status is exactly one of: **EVIDENCE** (cite source), **ASSUMPTION —
intake default**, **ASSUMPTION — industry heuristic**, **HYPOTHESIS — testable**
(name the Phase 2/4 test that resolves it). Anything in the report that is
not evidence appears here. This table is the report's honesty guarantee.

## Appendices

- **A:** Phase 1 full work product (methodology log, evidence table, scoring)
- **B:** Phase 2 complete test plan
- **C:** Phase 3 four one-pagers, cadence, dashboard spec
- **D:** Phase 4 dated roadmap and content calendar

Nothing from Phases 1–4 is discarded; the main body summarizes, appendices
carry the full work product.

## Rendering to DOCX / PDF

1. Write the completed report as a single markdown file (e.g.,
   `venture-validation-report-<slug>.md`) in the working or scratchpad
   directory.
2. **DOCX (preferred):** `pandoc report.md -o report.docx` — check pandoc
   exists first (`pandoc --version`). If missing, try installing; otherwise
   generate via `python-docx` (headings, tables, and paragraphs from the
   template structure).
3. **PDF (if requested or DOCX impossible):** `pandoc report.md -o
   report.pdf` (needs a LaTeX engine) or render HTML and print via headless
   Chromium; fall back to delivering the markdown plus a note.
4. Verify the output file is non-empty and opens (check file size; for DOCX,
   `python3 -c "from docx import Document; Document('report.docx')"` when
   python-docx is available).
5. Deliver the file to the user (SendUserFile when available), stating
   format and any rendering compromises. If every rendering path fails, say
   so plainly and deliver the markdown — never silently downgrade.
