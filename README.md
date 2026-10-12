# Repolex Knowledge Graph of datasette/datasette-cron

RDF knowledge graph data for [datasette/datasette-cron](https://github.com/datasette/datasette-cron), parsed by [repolex](https://repolex.ai).

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
rlex download datasette/datasette-cron
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d90b8bd13d5cb836d9a630c7edd28a2fbd10eada
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d90b8bd13d5cb836d9a630c7edd28a2fbd10eada
│           └── chunk-001.nq.gz
├── blob
│   ├── 050c62bb7b9fe70604a64f2f222312a37097349d.nq.gz
│   ├── 10377e0b18fcd0a9167df94ca28f510f19e14750.nq.gz
│   ├── 143f312605c622bd3561c410823543b3888c1d30.nq.gz
│   ├── 1a3f50a2634ae80201f87ac8f7daca56322069cc.nq.gz
│   ├── 1edbfcbd224c09f0f8778abec78e7a41210a224f.nq.gz
│   ├── 1f4ebb02bc2d603feef6a61eefaaa458a065e064.nq.gz
│   ├── 21fca8ccb31312e21b69dc01f9b2629110b7faf7.nq.gz
│   ├── 244b5df2976738cc0c14128e41b2ace4cf1c8e8c.nq.gz
│   ├── 251fa9218a13c50ea23093c47e1db661a488fad0.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2874d25d68c04a42f89d533de701771606c7f8dd.nq.gz
│   ├── 2b1016154c2bb74b6a399229ff109a4649c657f9.nq.gz
│   ├── 2b85afe48e7e35ccc41e3ad5e12cfdb79665d25d.nq.gz
│   ├── 2d7df97c4fe24ae49aa2b38b0913048c6f3853b0.nq.gz
│   ├── 3086ab185f29d9a1a6bdd24d5e6df51bbb85e78d.nq.gz
│   ├── 34619dbf358d1b971609a00fc07942fa047a7886.nq.gz
│   ├── 3a39df0553f0f2c70ca5c39479ef1ad4fa4904eb.nq.gz
│   ├── 3db69adf9f6ee6bdeb6938182d8d40b4eb3d9d0c.nq.gz
│   ├── 3f7bc86d30d6be9f5ee3a97cb8fedcf103fb7e2e.nq.gz
│   ├── 42916bbdbdca5abed93d1cd9304eb64b97e6cb0a.nq.gz
│   ├── 45a2e5d89086ae783d037f0cad8024c4722d3fb1.nq.gz
│   ├── 4d2b8190a93aabfaef67e496f79409a214fa24f7.nq.gz
│   ├── 4e4d146081202b6c4c4ce39df6129a2576d8db44.nq.gz
│   ├── 507a0d1d07fe054f03aa0f1eb801b68fcf207caf.nq.gz
│   ├── 5532e6274bf003ec4f6d27a11436da4ae0f90131.nq.gz
│   ├── 5c62971a81d544ea6327f8163b855c4183a444c3.nq.gz
│   ├── 5fcda99676f92f3d19a321aca23e569eb0fe5f7d.nq.gz
│   ├── 61bdcc823105180527bb5c608984c1e73f9c4fa0.nq.gz
│   ├── 683f636884e24f8b9c2dc2a62cf645b86961a3ae.nq.gz
│   ├── 6f38c733ecebccf40d77ecd3fb3943a91243e630.nq.gz
│   ├── 6fd2ac604d410f3256ed4e2593c4b7d3a62f0d15.nq.gz
│   ├── 72e257c181f948a41f7860c440edc80908fa5bfe.nq.gz
│   ├── 7a865faa96553289288195c185eb494d746d95f9.nq.gz
│   ├── 7a8b1401d19b9ee6ab2bf8b0c65324b08c9aaa6a.nq.gz
│   ├── 7dc5621a9b1a50d73298a77234161b36391b7771.nq.gz
│   ├── 858ee9a552d6190543dfdd945b518c70f10a6d5b.nq.gz
│   ├── 887af8d31191601b987fad895c94079b2be0870a.nq.gz
│   ├── 903bfbb6915572635a2c9967bc025cc8e184475b.nq.gz
│   ├── 93754a6dd5d65350cceff607af6ce25d190c2e5d.nq.gz
│   ├── 9d7f6876b6380c4f3106d899ff8cdec7ae5423b8.nq.gz
│   ├── a05eb6cf88209ad988476d9e78461b6d507431be.nq.gz
│   ├── a22fcedafd76516308bbeb32d0814aaf55546d24.nq.gz
│   ├── a2b5f94cc7b81487369ad3908d2f8036ce261579.nq.gz
│   ├── a887955417707df37290248ae6ba2d6347a7f035.nq.gz
│   ├── ac217b3f21c8a9f58fdc38282f58a3df998fc86a.nq.gz
│   ├── b2d85154b49bbcd7a147b7bc3176cfcb23ec7327.nq.gz
│   ├── b68ae0ea79dc4fe715831e5c6f21e3a7df30f0fc.nq.gz
│   ├── b76946be687e76a95e3b917c221d8fc28e84d8c7.nq.gz
│   ├── b9945380dbee0c8091018063f292d564e7aaac6e.nq.gz
│   ├── ba6c1b5fd86a3c4d9e939ec53b5acb346f19ce96.nq.gz
│   ├── bc4b844ebb835bf4ac9cb3817d03c027185149f9.nq.gz
│   ├── c44733a69bb35d9aa61f90215dc375afb94d55c4.nq.gz
│   ├── cea352c1be3d0a27cc8c0135b48e8ac517c18a02.nq.gz
│   ├── d0e64483be5144a42bdbfdc2dd86fcbff6cb10dd.nq.gz
│   ├── d48bf9a4a2aa0f18f438b1441ce6eaca9923dcd1.nq.gz
│   ├── d8ca5ebf0ce39c797ac020754b2eae730bb7c766.nq.gz
│   ├── da1b2542cee56b0d6c54598bcc95d6a4158d9360.nq.gz
│   ├── de381e6419b913c4aee8d1634cbe163cec78ca39.nq.gz
│   ├── e2806726156477217e3f778acfec14e5a845e426.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9b6d98d20877f4d90db9746d72f12d415666122.nq.gz
│   ├── ec5270cd1d82812aff75bdac7a9d504a643949bd.nq.gz
│   ├── f2285df920b613663aaf9dff2bdeae9e6f8ffd66.nq.gz
│   ├── f5c6c7f2c2c4f32dfddf2b251b2c5a6b8df40e29.nq.gz
│   ├── f71d96219ebf9996e454e4bcc6e5dd3edff92461.nq.gz
│   ├── fbdf2487a0408abf9168b8bee2f598a470128ee8.nq.gz
│   └── fe77a7b8ad06ef14e7e343cc6059971d7b54f52e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d90b8bd13d5cb836d9a630c7edd28a2fbd10eada.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 74 files
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

[datasette/datasette-cron](https://github.com/datasette/datasette-cron)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
