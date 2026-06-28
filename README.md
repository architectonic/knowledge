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

Optional addon for teams that want governed refresh campaigns:

```bash
npx architectonic add living-knowledge
```

## Role

Knowledge operationalizes Aletheia: the system's disclosed body of knowledge.

It may contain company files, project files, source indexes, claims, evidence notes, concept maps, citations, known unknowns, and reconciled knowledge artifacts.

## Boundary

`knowledge` is not the same as memory. Memory records traces. Knowledge contains claims that have been organized, sourced, reviewed, or explicitly marked with uncertainty.

`knowledge` should not contain private secrets or runtime credentials.

## Relationship to the stack

```text
constitution      = root scaffold
doctrine          = governs what knowledge means and how it may be used
identity          = defines who can assert, review, or approve knowledge
project           = provides context for project-specific knowledge
skills            = provides procedures for collecting and verifying it
knowledge         = stores the reviewed corpus itself
meta              = audits drift and maintenance of the system
living-knowledge  = optional addon for campaign-based maintenance of this corpus
```

## Core file

```text
knowledge.md -- root knowledge policy and corpus index
```
