# Nodusgraph — the Record and December 2026 Demo 0

[The public Record](https://nodusgraph.com/) documents the development of Nodusgraph, a relation-first project concerned with ordered testimony, provenance, attribution, and the history of ideas. This repository's `record` branch preserves source material and snapshots of that Record. Its descriptions of a database and formal system include research claims and plans; the files here should not be read as proof that those tools or claims are complete.

## What is here now

- [`entries/`](entries/) contains timestamped text entries from the earlier Record.
- [`hashes/`](hashes/) contains a hash ledger and its short explanatory note. The ledger records hashes for entries and some later material; it is not, by itself, a demonstrated verification or database system.
- [`htmlFiles/`](htmlFiles/) contains dated HTML snapshots of the Record, including [the September 25, 2026 snapshot](htmlFiles/index-2026-09-25T18:16:00-07:00.html). These preserve prose, revisions, timestamps, internal links, metadata, and artifact plans as they appeared in the snapshots.

The HTML Record is a readable development history and an initial dataset. It includes preliminary definitions, implementation notes, corrections, and claims at different levels of maturity. The snapshot's descriptions of NodusDB, ingestion, and traversal are plans or work in progress, not runnable capabilities established by this repository.

## December 2026 Demo 0 — planned

Demo 0 will use **the construction history of the formal paper** as its dataset. The goal is to instantiate the paper's developing concepts in NodusDB's own ordered relational storage format, then traverse that stored history offline. The paper is intended to be an artifact of the system it describes.

The demonstration should make it possible to follow a definition or claim through its witnessed formulation, revisions, rejected alternatives, attribution, and later use in the paper. A visitor should be able to inspect those connections through a small, unscripted traversal rather than rely on a polished final paper alone. This is a target for December, not a claim that the storage format, populated dataset, traversal CLI, or formal paper is already finished here.

The existing Record supplies historical context and potential source material for that work. It is not already the Demo 0 NodusDB dataset, and a dated HTML snapshot is not a database export.

## Scope

Demo 0 is focused on storing and traversing the paper's construction history. The current `record` branch should be read as a chronicle of the work and its evolving specifications, with implementation status checked against actual artifacts as they are added.
