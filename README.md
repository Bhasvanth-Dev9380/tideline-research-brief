# Tideline — 25-day research brief

**Live:** https://bhasvanth-dev9380.github.io/tideline-research-brief/

Companion to the [Brigade strategy brief](https://github.com/Bhasvanth-Dev9380/brigade-strategy-brief), same rules, same design system.

Tideline v2 is a memory layer for AI agents where personal, team and company memory are one store distinguished by a label, facts stay correct when the world changes, and what the model derives inherits the permissions of what it was derived from. This is the plan for the twenty-five days (2–27 September 2026) that build its foundation, and the research the plan rests on.

| Page | What it answers |
|---|---|
| [`index.html`](index.html) | **The brief.** Why now, the thesis, what is already verified, the six phases and what each produces, what will and will not be claimed, risks, budget. |
| [`protocol.html`](protocol.html) | **Design.** What the thing is: one store with labels instead of separate personal and company memories, the eight rules with what each is for and where it came from, the five doors into company memory, the three models, and how Tideline / Grokbot / living pages fit. |
| [`build.html`](build.html) | **The build.** Every file that changes and what goes in it — the record, the label lattice, propagation on supersession, four-valued belief, source reliability, label-ordered assembly, the billing ledger, and where the private package lives. |
| [`benchmarks.html`](benchmarks.html) | **Exams.** Why running a public benchmark is not testing a competitor, what MEME asks with a worked episode, and what each of the other harnesses is for. |
| [`landscape.html`](landscape.html) | **Field.** Ninety-one products surveyed, the four claims they share, what the enterprise incumbents actually enforce, and the three pieces of uncontested ground. |
| [`prior-art.html`](prior-art.html) | **Prior art.** What already exists, the four ideas we killed on inspection, and a ledger marking every mechanism cite / taken / ours. |
| [`evidence.html`](evidence.html) | **Evidence.** Every figure with its source. |

## Rules this brief follows

1. **A number appears only if it is on the evidence page.** Competitor figures are quoted from the vendor's own page and labelled as such; independent numbers link to the paper or harness.
2. **Nothing is claimed as new that has an ancestor.** The prior-art ledger marks each mechanism `cite`, `taken` or `ours`, and four ideas we had were killed after finding them published.
3. **Every phase builds something, and the number at the end is the receipt that it works** — not a separate activity, and never a test of somebody else's product.
4. **If a measurement comes out badly it is published anyway**, stated as the bound it establishes.
5. **Our own numbers carry the same label we give everyone else's** until an independent party re-runs them: vendor-reported.

Competitor, benchmark and vendor-documentation figures were retrieved **2 September 2026** and are not refreshed automatically. Tideline internals were read at `spinabot/brigade` `main` on the same date.

## Updating

Static HTML, no build step. Edit and push; GitHub Pages serves `main`. Light theme only — `color-scheme: light` is declared and there are no dark tokens.

Found a figure that is wrong, stale, or unfair to a competitor? Open an issue. A wrong cell in this brief costs more than an unflattering one.
