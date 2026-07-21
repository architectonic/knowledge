# Knowledge

> **Status: experimental, pre-1.0.** This package defines one layer of the Architectonic protocol. Evaluate it through its canonical contract, package validator, conformance manifest, and explicit limitations.

`knowledge` defines a readable, attributable, challengeable, and revisable corpus for agents and humans.

## What it gives an agent

- one predictable home for this concern;
- a canonical entry that can be found through `architectonic map`;
- a machine-readable `architectonic.protocol.json`;
- boundaries that prevent neighboring layers from silently owning the same concept;
- package validation that runs against both the source checkout and the exact npm tarball.

## Canonical entry

```text
knowledge.md
```

## Boundary

Memory, retrieval scores, generated summaries, graph edges, and model output are not evidence by themselves.

## Install

```bash
npx architectonic@latest add knowledge --source npm
npx architectonic@latest verify
```

Installing a layer provides reusable public structure. Organization-specific facts, private knowledge, credentials, runtime state, and local decisions belong only in controlled workspace instances.

## Claims

This package claims only that its declared structure and validators are inspectable and reproducible. It does not claim universal performance improvement or domain correctness.
