---
type: Knowledge
title: Knowledge Contract
description: Root contract for maintaining an Architectonic knowledge corpus.
tags: [knowledge, aletheia, claims, evidence, uncertainty, okf]
okf_version: "0.1"
status: draft
---

# Knowledge Contract

Knowledge is the disclosed corpus through which a system presently understands its world.

## Contents

A knowledge corpus may contain:

```text
claims
sources
evidence notes
concepts
relationships
vocabulary
known unknowns
uncertainty labels
reconciliations
company or project files
```

## Rules

1. A claim without evidence remains a claim.
2. A source artifact outranks memory.
3. Unknowns must be preserved instead of filled by inference.
4. Contradictions must be recorded or resolved, not silently flattened.
5. Knowledge is revisable when stronger evidence appears.
6. Private knowledge must stay inside its intended instance.

## Relationship to Other Layers

```text
doctrine  defines epistemic rules
identity  defines actors and source authority
project   defines operating context and relevant sources
skills    define procedures for acquiring and verifying knowledge
meta      defines upkeep and drift review
```
