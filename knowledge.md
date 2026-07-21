---
type: Knowledge
title: Knowledge Contract
description: Contract for attributable, challengeable, revisable knowledge corpora.
tags: [knowledge, evidence, provenance, uncertainty, contradictions]
protocol_version: "0.2.0"
status: experimental
---

# Knowledge Contract

A knowledge corpus is the disclosed set of claims and context through which an organization presently understands a domain.

## Required distinctions

```text
source          recoverable artifact or observation
claim           statement that may be supported, disputed, or unresolved
evidence        source material relevant to a claim
inference       conclusion drawn from evidence and assumptions
uncertainty     what is not established and how strongly
contradiction   materially incompatible claims or sources
known unknown   a gap that must not be silently filled
synthesis       a derived account that links back to recoverable inputs
```

## Rules

1. A claim without evidence remains a claim.
2. A source artifact outranks memory.
3. Generated summaries, retrieval scores, graph links, and model output are not evidence by themselves.
4. Contradictions are recorded or resolved, not silently flattened.
5. Unknowns remain explicit.
6. Every durable synthesis preserves recoverable provenance.
7. Canonical sources remain readable without a specific model, database, embedding provider, graph engine, or agent runtime.
8. Private knowledge stays within its authorized instance.
9. Knowledge is revised or retired when stronger evidence or changed conditions justify it.

Add `living-knowledge` only when the corpus changes rapidly enough to require governed maintenance cycles.
