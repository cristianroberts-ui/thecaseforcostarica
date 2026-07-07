# Phase 1 — Value Extraction (Demand Archaeology)

Goal: establish whether the pain the founder wants to solve actually exists
in the wild, at what intensity, and whether the evidence points at the stated
problem or a different one. This phase produces evidence, not opinions.

## Source checklist

Work through as many as the environment's research tools allow. For each
source, log whether it was examined, and if not, why (no access, no results,
out of scope).

| Source class | What to mine | Signal quality |
|---|---|---|
| Reddit (subreddits for the niche + r/entrepreneur-adjacent complaint threads) | Complaint threads, "how do I", "does anyone else" posts | High — unsolicited, emotional |
| Amazon reviews (adjacent physical/book products) | 1–3 star reviews of competing or adjacent products | High — paid customers describing failure |
| G2 / Capterra (B2B software) | Low-star reviews, "dislikes" sections, switching stories | High for B2B |
| App Store / Google Play | 1–3 star reviews of category apps | High for consumer software |
| Discord / Slack communities (public, searchable) | Recurring help requests, pinned workarounds | Medium-high; log community name and size |
| Industry forums / niche communities (Stack Exchange, specialized boards) | Repeated questions, accepted-answer workarounds | Medium-high |
| Vendor support forums / GitHub issues | Long-lived unresolved threads, most-upvoted feature requests | High — demand vendors ignore |
| Job boards / freelance markets (Upwork, Fiverr, Indeed) | People paying humans to do the task manually | Very high — direct willingness-to-pay |

## Query construction

Run multiple query families per source; log every query verbatim in the
methodology log. Families:

- **Complaint mining:** `"[task] is so frustrating"`, `"I hate [tool/task]"`,
  `"why is [task] so hard"`, `site:reddit.com [niche] problem`
- **Workaround mining:** `"[task] workaround"`, `"[task] hack"`,
  `"spreadsheet to [task]"`, `"I built my own"`, `"duct tape"`
- **Alternative-seeking:** `"[incumbent] alternative"`, `"cheaper than
  [incumbent]"`, `"switching from [incumbent]"`
- **Willingness-to-pay:** `"would pay for"`, `"shut up and take my money"`,
  `"is there a paid tool"`, Upwork/Fiverr listings for the manual task
- **Aspiration mining:** `"is there a way to"`, `"does anything exist that"`

## Methodology log (mandatory)

Maintain this table from the first query. It goes in Appendix A verbatim.

| # | Date | Source | Query / path | Results examined | Usable signals |
|---|---|---|---|---|---|

"Results examined" is the count of threads/reviews actually read, not the
count returned. Sample sizes matter: fewer than ~15 distinct voices across
all sources means demand evidence is thin — say so in the report.

## Signal categorization

Bucket every usable signal into exactly one primary category:

1. **Repeated complaint** — same pain expressed by different people. Count
   distinct voices, not thread replies.
2. **High-intensity language** — profanity, exasperation, all-caps, "rage
   quit", time/money loss quantified by the speaker. These are weighted
   heavier than mild annoyance.
3. **Workaround behavior** — spreadsheets, scripts, hired help, chained
   tools, manual processes. The strongest demand signal short of payment:
   people are already spending effort.
4. **Willingness-to-pay** — explicit "I'd pay", existing paid alternatives
   with revenue, freelancers hired for the task, prices mentioned.

## Scoring rubrics

Score each on the anchors below. Do not use unanchored gut numbers.

**Pain intensity (1–5)**
- 1: mild preference ("would be nice")
- 2: annoyance, no action taken
- 3: recurring frustration, workaround attempted
- 4: measurable time/money loss stated; active search for solutions
- 5: pain drives purchasing, hiring, or churn today

**Frequency (1–5)**
- 1: rare/one-off · 2: few times a year · 3: monthly · 4: weekly ·
- 5: daily or blocks a daily workflow

**Urgency (1–5)**
- 1: indefinitely deferrable · 2: "someday" list · 3: this quarter ·
- 4: actively evaluating solutions now · 5: deadline or bleeding money now

**Composite demand score** = 0.4·intensity + 0.3·frequency + 0.3·urgency.
Report per-segment if evidence clusters into distinct customer segments.
A composite below 3.0 is a red flag to carry into the scoring matrix and
recommendation.

## Stated problem vs real problem

Explicitly test the founder's hypothesis against the evidence:

1. Write the founder's stated problem (from intake) in one sentence.
2. Write the dominant evidence cluster's problem in one sentence.
3. If they match: say so, one line, move on.
4. If they diverge: produce a **Problem Reframe** section — what the founder
   proposed, what the evidence supports, what changes downstream (target
   customer, offer, price), and whether Phases 2–4 should target the
   reframed problem (recommended default: yes, and say so decisively).

## Evidence integrity rules

- Quote patterns, not fabrications. Present verbatim quotes only when
  actually retrieved; otherwise write pattern summaries clearly labeled as
  paraphrase ("multiple reviewers describe X in terms like Y").
- Every row in the evidence table cites its source (URL or source+query).
- Sources searched with zero results are still logged — absence of
  complaints is itself a finding and belongs in the report.

## Deliverable — Demand Evidence Package

1. **Demand evidence table:** columns — source, signal category, pattern
   summary (with verbatim quote where retrieved), distinct-voice count,
   intensity/frequency/urgency scores, WTP indicator (Y/N + detail).
2. **Methodology log** (table above).
3. **Pain scoring summary:** composite score, scoring rationale, sample-size
   caveat.
4. **Problem Reframe section** (only if divergence found).
