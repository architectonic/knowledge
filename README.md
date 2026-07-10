---
type: Entry Point
title: knowledge
description: Runtime-neutral knowledge package for claims, sources, evidence, uncertainty, relations, and known unknowns.
tags: [knowledge, evidence, sources, claims, provenance, relations, okf]
okf_version: "0.1"
status: draft
---

# knowledge

```bash
npx architectonic add knowledge
```

`knowledge` is the corpus layer of an Architectonic constitution. It stores disclosed claims and the context needed to inspect them: sources, evidence, uncertainty, relations, contradictions, and known unknowns.

For corpora whose sources change frequently — market data, tax codes, building codes, regulatory catalogs — add `living-knowledge` as an optional maintenance layer on top of this corpus.

## In the ensemble

```text
constitution      composition contract for the ensemble
doctrine          purpose, principles, ontology, epistemology, ethics, governance, incentives
identity          actors, roles, authority, delegation, incentives, privacy
project           operating-unit context, sources, decisions, risks, continuity
skills            reusable procedures, verification, failure handling
knowledge         claims, sources, evidence, uncertainty, known unknowns
models            model metadata, evaluations, capability requirements, routing policy
agents            software actors composed from identity, skills, models, knowledge, permissions
living-knowledge  optional: governed maintenance of frequently changing corpora
meta              audit, upkeep, drift review, revision policy
```

`knowledge` is not memory. Memory preserves traces or observations. Knowledge contains claims that have been organized, sourced, reviewed, or explicitly marked with uncertainty.

## Commands

```bash
npx architectonic add knowledge
npx architectonic add knowledge --source npm
npx architectonic add living-knowledge   # optional: maintenance for changing corpora
npx architectonic init
npx architectonic list
npx architectonic doctor
```

CLI: https://github.com/architectonic/architectonic

## Format principles

The corpus should remain understandable without a specific database, model, embedding provider, or agent runtime.

Prefer plain-text sources with stable identifiers, explicit provenance, typed metadata, rebuildable indexes, and clear separation between source material, extracted claims, synthesis, and inference.

Avoid treating retrieval scores, generated summaries, graph edges, or model output as evidence by themselves.

## Boundary

This package defines reusable public structure. Private corpora, personal records, client data, secrets, and runtime credentials belong only in appropriately controlled instances.

## Core file

```text
knowledge.md   root knowledge policy and corpus index
```
