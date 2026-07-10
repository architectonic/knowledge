---
type: Entry Point
title: knowledge
description: Runtime-neutral knowledge package for claims, sources, evidence, uncertainty, relations, and known unknowns.
tags: [knowledge, evidence, sources, claims, provenance, relations, okf]
okf_version: "0.1"
status: draft
---

# knowledge

`knowledge` is the corpus layer of an Architectonic constitution.

Install it with:

```bash
npx architectonic add knowledge
```

Optional addon for teams that want governed refresh campaigns:

```bash
npx architectonic add living-knowledge
```

## Role

The knowledge layer stores disclosed claims and the context needed to inspect them.

It may contain source indexes, claims, evidence notes, concept pages, citations, typed relations, known unknowns, contradictions, review state, and reconciled knowledge artifacts.

## Boundary

`knowledge` is not the same as memory. Memory preserves traces or observations. Knowledge contains claims that have been organized, sourced, reviewed, or explicitly marked with uncertainty.

This package defines a reusable public structure. Private corpora, personal records, client data, secrets, and runtime credentials belong only in appropriately controlled instances.

## Format principles

The corpus should remain understandable without a specific database, model, embedding provider, or agent runtime.

Prefer:

- plain-text source files with stable identifiers;
- explicit provenance and citations;
- typed metadata with documented schemas;
- links or typed edges that can be rebuilt deterministically;
- revision state, timestamps, and uncertainty markers;
- human-readable pages that can also be indexed by machines;
- generated indexes and embeddings that can be discarded and recreated;
- clear separation between source material, extracted claims, synthesis, and inference.

Avoid treating retrieval scores, generated summaries, graph edges, or model output as evidence by themselves.

## Converging knowledge-system patterns

Current open knowledge and second-brain systems increasingly converge on several useful patterns:

```text
portable markdown or text as the durable layer
structured frontmatter or manifests for machine interpretation
stable page and entity identifiers
provenance attached to claims
hybrid lexical, vector, and graph retrieval
explicit gap, contradiction, and staleness reporting
schema packs or profiles rather than one universal taxonomy
human review for promotion, publication, and destructive changes
rebuildable indexes separated from canonical source files
```

These are implementation patterns, not requirements to adopt any particular tool. Architectonic should preserve the distinctions and interfaces that allow multiple tools to coexist or be replaced.

## Relationship to the stack

```text
constitution      = root scaffold
doctrine          = governs what knowledge means and how it may be used
identity          = defines who can assert, review, or approve knowledge
project           = provides context for project-specific knowledge
skills            = provides procedures for collecting and verifying it
knowledge         = stores reviewed claims, sources, evidence, and relations
meta              = audits drift and maintenance of the system
living-knowledge  = optional addon for campaign-based maintenance of this corpus
```

## Core file

```text
knowledge.md -- root knowledge policy and corpus index
```
