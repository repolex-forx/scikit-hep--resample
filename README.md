# Repolex Knowledge Graph of scikit-hep/resample

RDF knowledge graph data for [scikit-hep/resample](https://github.com/scikit-hep/resample), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-hep/resample
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2774eaaeb30c9de727815c3a62953ad3e7fa94d7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2774eaaeb30c9de727815c3a62953ad3e7fa94d7
│           └── chunk-001.nq.gz
├── blob
│   ├── 066a3be2e7645bb2aed5b143ae3811081c2dbe77.nq.gz
│   ├── 08846a7444a7c1882f8c64f6a9f70b10650b4f68.nq.gz
│   ├── 1aba38f67a2211cf5b09466d7b411206cb7223bf.nq.gz
│   ├── 24e1391a0a3fe6c255907c2cf9bb34f5215b4a56.nq.gz
│   ├── 27f573b87af11e2cbbd9f54eb1ee285a58550146.nq.gz
│   ├── 280c65a8cae3558a8866a77ae7fd2b269a66ce66.nq.gz
│   ├── 2f35a01c51d2ba471fc90f305646498204055f07.nq.gz
│   ├── 36e9a21d635457b78f3acf962e85ca3b765042d7.nq.gz
│   ├── 38403ab2f4757107e228a3cdabcb9b07b6d99fb7.nq.gz
│   ├── 3915879c9fd77884451def58f899b7f3146df11a.nq.gz
│   ├── 3bd963af2893e4c99e5218eb22e06692a0fba4e6.nq.gz
│   ├── 462cb711ff1337781fb2aeaa3b26eab81ff58c7a.nq.gz
│   ├── 4887933f7b0b15fe7c940684ec839016c0790ea3.nq.gz
│   ├── 4a7887b3b47adac599b67b5eff0267c8e06e8214.nq.gz
│   ├── 4c5eaddf557c83756c7b35c341b79ab0fc74bfa4.nq.gz
│   ├── 569fceef3b7a0e9a40a0fc2b709619fda7f10fda.nq.gz
│   ├── 67cab1fb38d5c9d0bfaaa4d2918d2d6b93d9f212.nq.gz
│   ├── 67f038a207ce75ed96147f048a2066c61a4d1cbc.nq.gz
│   ├── 6d9824c7784be21fcaf2cb2f15c196ae4fbb0370.nq.gz
│   ├── 70a7fa1e75b8d60693ff55a49b13595afe17d63c.nq.gz
│   ├── 80945e451176f4d63e681218d34b959bf7b9b862.nq.gz
│   ├── 844962103309636556f1bd60e0fc2f76cdd16400.nq.gz
│   ├── 85d2f837921fdac400909608527dcb93f1cf78a8.nq.gz
│   ├── 8b13673c14657c63f5a23c7b514f9fca0725174f.nq.gz
│   ├── 99a7b8683fba662d445e5ab268584f22d20626fc.nq.gz
│   ├── 9aba5c3668673f1e0c0605219f1da51fa22b3811.nq.gz
│   ├── 9bfc5fa49dde11f5bac4e59fd2f239e72c80af63.nq.gz
│   ├── 9c86b68aab9b7fb81dbbf8c8cdd2904afb124247.nq.gz
│   ├── a0d1fa9ac09b249b8a80fdb02857e528721c1a00.nq.gz
│   ├── ace4cc8de44a1780d664821976f41b91f51dea0b.nq.gz
│   ├── aeecc269d38a68acb24d74b6d04ba59e90faea79.nq.gz
│   ├── ba8b743a666a42ae4667d00ada4f26d9547ae742.nq.gz
│   ├── bab00a6ea8b7319f12b7c879fcee1a9f0982c5ef.nq.gz
│   ├── c238f7b30738560dc3d5f1aafbc5f1e6a6e4505b.nq.gz
│   ├── c3afd04071cf2d498077376ab5504292d5363f8b.nq.gz
│   ├── c4b6dab16637c3e1551b4f6e8c8d8104cccb9a7f.nq.gz
│   ├── c7b0db6b91b57190dcd9fc4e4abdd7a9e3999a2b.nq.gz
│   ├── d234f687975579545c503988aae7ae03df4c77ee.nq.gz
│   ├── d6316e584721918b9b2dfa395a31582113c91004.nq.gz
│   ├── d63705e8f109a770ab05f826f8defdb79e933303.nq.gz
│   ├── e0a04ba722d7b9d10299f1caac93b8a80b40147c.nq.gz
│   ├── e42f645684b98fac774c47b4561610e3b1d1c491.nq.gz
│   ├── e4bf803668ba4c478dcf3df313ca73d5d17c9cf5.nq.gz
│   ├── e6ad4a38f530ec83d97e70491c09944c39a53b0a.nq.gz
│   ├── efe3dc0f701bd4b217003c7bfb8b550ba0dee137.nq.gz
│   ├── f59bb0818df0caf1aeac668d9ae8360a2ea6b5ce.nq.gz
│   ├── f5a8af4fc632d13055877b64ad08bf7dce4e8ab4.nq.gz
│   └── ffb37394d81856b3dcbdb86f69fe1b0156c62f82.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2774eaaeb30c9de727815c3a62953ad3e7fa94d7.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 56 files
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

[scikit-hep/resample](https://github.com/scikit-hep/resample)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
