---
name: venture-validation
description: Transforms a business idea into an investment-committee-ready validation report via a four-phase methodology - demand archaeology across primary sources, an execution-ready fake-door signal test, an operating system of four repeatables, and a dated 30/60/90 launch plan - assembled into an IC-grade document with a GO / CONDITIONAL GO / NO-GO recommendation. Use when the user shares a business idea, startup concept, or proposed venture and wants it validated, stress-tested, researched, or assessed ("validate this idea", "is this a good business", "should I build this", "write an IC memo for..."). Always opens with a mandatory batched intake questionnaire before any analysis.
---

# Venture Validation

Turn a business idea into a rigorous, investment-committee-ready validation
report. The methodology has a blocking intake step, four analysis phases, and
a final assembly step. Execute them in order. Do not skip phases and do not
begin analysis before intake answers arrive.

## Non-negotiables (apply to every phase and every output)

1. **Institutional register.** Answer-first, evidence-forward, plain
   declarative prose. No marketing language, no hype adjectives, no hedging
   filler. Write like a memo to a skeptical investment committee.
2. **Every claim is sourced or flagged.** Each quantitative or factual claim
   carries a source citation or an explicit `[ASSUMPTION]` tag. No
   unsupported assertions anywhere in the report.
3. **Decisive recommendations with honest gaps.** End with an explicit GO /
   CONDITIONAL GO / NO-GO and a conviction level. Name what you do not know
   in a dedicated gaps section rather than hedging the recommendation.
4. **Never fabricate evidence.** Do not invent verbatim quotes, review
   counts, or statistics. If a source cannot be examined, log it as not
   examined and mark dependent findings as assumptions.
5. **Log methodology as you go.** Record search queries, sources examined,
   and sample sizes at the moment of research, not reconstructed afterward.

## Workflow

### Step 0 — Mandatory intake (blocking)

Read `references/intake.md`, then ask the full structured question battery in
a single batched pass (use AskUserQuestion when available; otherwise one
message containing all questions). **Stop and wait for answers. Do not
proceed to Phase 1 until the user responds.** When answers arrive, restate
them, and for every unanswered item state the exact default assumption you
will adopt and record it in the assumptions log.

### Phase 1 — Value Extraction (demand archaeology)

Read `references/phase-1-value-extraction.md` before starting. Mine primary
demand signals (Reddit, Amazon/G2/Capterra/App Store reviews, Discord/Slack
communities, industry and support forums, job boards) using live web research
tools where available. Score pain intensity, frequency, and urgency on the
rubrics defined in the reference. Test whether the founder is solving the
stated problem or the real problem.

**Deliverable:** demand evidence table, methodology log, pain scoring, and a
Problem Reframe section if evidence diverges from the founder's hypothesis.

### Phase 2 — Signal Testing (demand validation design)

Read `references/phase-2-signal-testing.md` before starting. Design a
complete fake-door test: 2–3 landing page concepts with exact copy and price
anchors, ad creative for a $50–$250 budget on a justified channel, targeting
parameters, pre-committed success/kill thresholds benchmarked to channel
norms, test duration, and a kill / pivot / double-down decision tree. Include
the ethical guardrails from the reference. Use
`templates/test-plan-template.md` for the deliverable.

**Deliverable:** an execution-ready test plan the founder can launch within
48 hours.

### Phase 3 — Systemization (repeatables, not SOPs)

Read `references/phase-3-systemization.md` before starting. Define the four
core repeatables — research, validate, create, sell — as concrete,
tool-specified workflows with explicit AI-executes vs human-judgment
checkpoints, a weekly operating cadence, a leading-indicators-only metrics
dashboard spec, and scaling triggers for SOP graduation. Use
`templates/repeatable-one-pager.md` for each repeatable.

**Deliverable:** a one-page operating system per repeatable.

### Phase 4 — Self-Deployment (launch and build-in-public plan)

Read `references/phase-4-self-deployment.md` before starting. Produce a dated
30/60/90-day ship plan: MVP scope cut to the first-revenue path, a
build-in-public content calendar and channel strategy, the explicit
excuse-traps-to-skip list, pricing and a first-10-customers acquisition plan,
and a fix-it-out-loud feedback loop protocol.

**Deliverable:** a dated execution roadmap with weekly milestones.

### Final step — Assemble the IC report

Read `references/report-assembly.md` before assembling. Populate
`templates/report-template.md` in full: executive summary with recommendation
and conviction level, weighted scoring matrix, TAM/SAM/SOM with disclosed
methodology, competitive landscape, preliminary unit economics, risk
register, key assumptions log separating evidence from hypothesis, and
appendices containing all Phase 1–4 work product. Render the finished report
as a formatted DOCX (preferred) or PDF per the output instructions in the
reference, and deliver the file to the user.

## Research tooling

Prefer live research: WebSearch, WebFetch, and Tavily tools when available.
When the environment has no web access, say so plainly, run the methodology
against what the user provides plus general knowledge, and downgrade every
affected finding to `[ASSUMPTION]` — never present unverified recall as
harvested evidence.

## File map

| File | Load when |
|---|---|
| `references/intake.md` | Step 0, before asking anything |
| `references/phase-1-value-extraction.md` | Start of Phase 1 |
| `references/phase-2-signal-testing.md` | Start of Phase 2 |
| `references/phase-3-systemization.md` | Start of Phase 3 |
| `references/phase-4-self-deployment.md` | Start of Phase 4 |
| `references/report-assembly.md` | Before final assembly |
| `templates/report-template.md` | Final assembly |
| `templates/test-plan-template.md` | Phase 2 deliverable |
| `templates/repeatable-one-pager.md` | Phase 3 deliverable |
