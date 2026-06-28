---
type: Entry Point
title: knowledge
description: Runtime-neutral knowledge corpus package for claims, sources, evidence, uncertainty, and known unknowns.
tags: [knowledge, aletheia, evidence, sources, claims, okf]
okf_version: "0.1"
status: draft
---

# knowledge

`knowledge` is the corpus layer of an Architectonic constitution.

Install it with:

```bash
npx architectonic add knowledge
```

## Role

Knowledge operationalizes Aletheia: the system's disclosed body of knowledge.

It may contain company files, project files, source indexes, claims, evidence notes, concept maps, citations, known unknowns, and reconciled knowledge artifacts.

## Boundary

`knowledge` is not the same as memory. Memory records traces. Knowledge contains claims that have been organized, sourced, reviewed, or explicitly marked with uncertainty.

`knowledge` should not contain private secrets or runtime credentials.

## Core file

```text
knowledge.md -- root knowledge policy and corpus index
```
