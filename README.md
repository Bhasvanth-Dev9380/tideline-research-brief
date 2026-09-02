# Tideline — 25-day research brief

**Private.** Companion to the [Brigade strategy brief](https://github.com/Bhasvanth-Dev9380/brigade-strategy-brief), same rules, same design system.

A two-page brief on the 25 days (2–27 September 2026) that build Tideline v2's foundation — the mathematical models and the protocol, each measured on a public harness with a cost column — before any product work.

| Page | What it is |
|---|---|
| [`index.html`](index.html) | The brief. The moment, the thesis (a protocol and three models, not an algorithm), what is already verified, the six phases with the artifact each ends in, what will and will not be claimed, risks as an opponent would argue them, budget. |
| [`evidence.html`](evidence.html) | Every figure on the brief with its source: benchmarks, market and competitor claims (labelled vendor-reported), prior art cited instead of claimed, and the Tideline internals referenced. |

## Rules this brief follows

1. **A number appears only if it is on the evidence page.** Competitor figures are quoted from the vendor's own page and labelled as such; independent numbers link to the paper or harness.
2. **Nothing is claimed as new that has an ancestor.** The prior-art table on the evidence page lists what is cited instead — MemoRepair, MemTX, Fides, vLLM RFC #16016, PromptPeek, Colaco & Lahjouji, RA-RAG, and the rest.
3. **Every phase ends in a measurement, not a feature.** If a phase's number comes out badly, the brief reports it that way; a low edge-recall number is a bounded result, not a failure to mention.
4. **Our own future numbers get the same label we give Sentra's**: vendor-reported until someone else runs the harness.

Competitor, benchmark and vendor-documentation figures were retrieved **2 September 2026** and are not refreshed automatically. Tideline internals were read at `spinabot/brigade` `main` on the same date.

## Updating

Static HTML, no build step. Edit and push; GitHub Pages serves `main`. Light theme only — `color-scheme: light` is declared and there are no dark tokens.

Found a figure that is wrong, stale, or unfair to a competitor? Open an issue. A wrong cell in this brief costs more than an unflattering one.
