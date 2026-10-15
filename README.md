# Repolex Knowledge Graph of viewflow/django-fsm

RDF knowledge graph data for [viewflow/django-fsm](https://github.com/viewflow/django-fsm), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download viewflow/django-fsm
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 88eeeca1a4f7b5a88c8aa9fce5fecbb5ceb2b74f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 88eeeca1a4f7b5a88c8aa9fce5fecbb5ceb2b74f
│           └── chunk-001.nq.gz
├── blob
│   ├── 0f76e543c973a54413e1ef21f0d3f949063c6799.nq.gz
│   ├── 11afcc640b16f673c6bfd961ee0fb610e6c3561e.nq.gz
│   ├── 147759d8194f505150f3c3dcbef5e7e409d42467.nq.gz
│   ├── 2b8e1d68392733926ab03949c288b47d0b1ac26e.nq.gz
│   ├── 2db24e411c5cb649e123268878e59fbb9eb3ba47.nq.gz
│   ├── 2e115c988052d13d7638dc1a49cad0190e5918f9.nq.gz
│   ├── 3e49f5a1cd1e9255afc725accde8ea028cf37724.nq.gz
│   ├── 4e9bfcfe40039b0d3081623fd3fcba2831d7db85.nq.gz
│   ├── 4fc0259fe8dd84c8d548a47658607e0afd2cc1cb.nq.gz
│   ├── 562fc68ad5647ca37520b6547202a1bc944ea41b.nq.gz
│   ├── 608b08ba7cef6477c8c630323ae56762ee5dd737.nq.gz
│   ├── 60f00ef0ef347811e7b0c0921b7fda097acd9fcc.nq.gz
│   ├── 691868e5ae17f769e8685cf7c3f92892942954b8.nq.gz
│   ├── 6d0c5f9af3e9b3ed801dd1c0af50918dfba426a5.nq.gz
│   ├── 6d63813799e30f0b75551950f260b0d588f0521c.nq.gz
│   ├── 6f3916ff1e9924af32ce44f0d22f384fbf0322df.nq.gz
│   ├── 743284d9997ca3de2a77839a89172e5597677d8e.nq.gz
│   ├── 82b879411b5a1d778cb71469c2c761fca405d792.nq.gz
│   ├── 8a7e1850c284313fc1293d71c6f34d1d5dfbfdaa.nq.gz
│   ├── 8d48a83366cb74f119d8d839a9dce07a2d650af0.nq.gz
│   ├── 9ce6da721e36ad3df11cefa3b5d49adf66c7e93e.nq.gz
│   ├── 9f08379a1d038fc62236408fa48d27b47552c83d.nq.gz
│   ├── a6c8856d17decf672f1e0c74d2e26fe7ba121286.nq.gz
│   ├── a6ef2917f3aadaa53449dc3d4a522970a5dc9315.nq.gz
│   ├── a9894c59103eba7d720a6fdc99e9f0bdda9ba59b.nq.gz
│   ├── a9a6d20e21b35d711a1c8f5ce525c618919e14c6.nq.gz
│   ├── abc1219bafc764533157c29e66b2dce260a60d74.nq.gz
│   ├── c81fa3b1392f2ae870617023753fc5426f7aeb87.nq.gz
│   ├── d476c4880cef790f7507f108521b1bd8748b2202.nq.gz
│   ├── d69ad7210b3d4909b87597b02cb13c58477b4e76.nq.gz
│   ├── dcc172304897158ad60da4e751b70b5c6b432a9a.nq.gz
│   ├── df5ef4bff62bdafa1ed5861780341b98e3400cab.nq.gz
│   ├── e326809ea5de337141ab087955bc76e0f39e037b.nq.gz
│   ├── e5cf602ccafe6d1348f22161b80f9ddec24ae2a0.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e73d6564fa57fe45826367ddabe70cc653d51073.nq.gz
│   ├── edca474a2f5c69851d6508c278fa6744be1c324e.nq.gz
│   ├── f273f6a6ce42156fc963725499cf69d22968bcdd.nq.gz
│   ├── f2a30d4d1bde83e3fae9e836894682d3f4342644.nq.gz
│   ├── f5fa9293bac741f92df09d076a4ba0c235fcbae3.nq.gz
│   ├── f64d6d1e7cd02a993a1f2d737ea61bf14d9c9225.nq.gz
│   └── fcaa0c00c56e964b775d3afb8d7e78ffabbf38c2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 88eeeca1a4f7b5a88c8aa9fce5fecbb5ceb2b74f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 50 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[viewflow/django-fsm](https://github.com/viewflow/django-fsm)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
