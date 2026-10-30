# Jhoana Sophia Munar

Independent research on whether AI-system safety claims hold up when you
actually check them, not just when you read them.

Each project below states a falsifiable hypothesis before running any
code, and reports what the evidence supported — including when that's
the null hypothesis. See each repo's `RESEARCH.md` for the full
falsification report.

## Projects

**[polygraph](https://github.com/sopi22/polygraph)** — checks an AI
model checkpoint's own safety claim (e.g. "safetensors only, no
pickle") against what it actually does when loaded inside an isolated
sandbox. Static scanners never run the file; this does, because a
declared format can be honest and still be malicious.

**[claim-card](https://github.com/sopi22/claim-card)** — tests whether
epistemic-integrity violations in AI-agent-authored project docs (a
locked term reused, a caveat dropped between a log and its summary) can
be caught by deterministic, pattern-based text analysis instead of an
LLM judge. Current finding: weakly supported, with a named
generalization gap outside this project's own template family.

**[foss-escape-architecture](https://github.com/sopi22/foss-escape-architecture)**
(Pulse, Experiment 001) — represents software/environment compatibility
assumptions as falsifiable, behaviorally-observable probes on Android,
and tests whether that tells you anything conventional `getprop` /
`dumpsys` metadata doesn't. Phase 1 closed, supported, with one named
open limitation (no second-OEM physical device tested yet).

## Contact

Open an issue on any of the repos above, or reach me through GitHub ([@sopi22](https://github.com/sopi22)).
