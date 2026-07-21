# Knowledge

> **Status: experimental, pre-1.0.** This layer organizes disclosed claims, sources, evidence, uncertainty, contradictions, and known unknowns. It does not turn generated synthesis, memory, retrieval scores, or authority into truth.

`knowledge` may stand alone as one manually curated corpus:

```bash
npx architectonic@latest init my-corpus --preset knowledge --source npm
```

Use `knowledge-system` when the corpus also needs reusable ingestion, query, audit, and retirement procedures:

```bash
npx architectonic@latest init my-corpus --preset knowledge-system --source npm
```

Add `living-knowledge` only when correctness decays as external sources change independently of your edits.

Canonical Markdown may be accompanied by lexical search, embeddings, databases, graph projections, Obsidian, Graphify, GraphRAG, or other retrieval and visualization tools. Those are replaceable access paths; the corpus and source trail remain authoritative.

See [`WHEN_TO_USE.md`](./WHEN_TO_USE.md) and [`knowledge.md`](./knowledge.md).
