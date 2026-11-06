# Repolex Knowledge Graph of jupyterhub/mybinder.org-user-guide

RDF knowledge graph data for [jupyterhub/mybinder.org-user-guide](https://github.com/jupyterhub/mybinder.org-user-guide), parsed by [repolex](https://repolex.ai).

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
rlex download jupyterhub/mybinder.org-user-guide
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1a4084931e8296769eab9b2ea75c5e29ac8e618b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1a4084931e8296769eab9b2ea75c5e29ac8e618b
│           └── chunk-001.nq.gz
├── blob
│   ├── 0214002c07023024e1d2774b992c041e87cc8490.nq.gz
│   ├── 06894cd0366871195b67e77e3bec608887909f7a.nq.gz
│   ├── 0a4a15312e40cec15639a1e41fe0e021f1b1d428.nq.gz
│   ├── 0dc89813dc10ed07777226c26d348a19ce3afb93.nq.gz
│   ├── 1526e034fe0199d15ed7f3cedd08ed1016d75822.nq.gz
│   ├── 174b7235b5900acfe5df5816cb5c8b6bab529fff.nq.gz
│   ├── 2330187799cecc22c4c79e89dd8eeab04c53410c.nq.gz
│   ├── 26e3abac28f7ad1a1a6870f059e48c4b42f19451.nq.gz
│   ├── 29cbccf5e4650ca1a577ab5384ae6ad9c08a0475.nq.gz
│   ├── 3458d5e14da86de0fdae4aba0a3988ebfdc0d968.nq.gz
│   ├── 3eb03b7636943ca95cb5c647aa886b96546a2af1.nq.gz
│   ├── 4179740a73ee93819ad41300c010c8e592fa1501.nq.gz
│   ├── 46a75538564df53a75f73a034fd1b372f585620b.nq.gz
│   ├── 4fe9ca353b7481e7e1608b4d661b2add636c4850.nq.gz
│   ├── 5aa143a2646378c50a537d91ed726c7232880675.nq.gz
│   ├── 5dc414bf9be1fc00a47f59c1144644b15f4d71cb.nq.gz
│   ├── 66bde15b03e37e14cf57622e1d4067507204bf7f.nq.gz
│   ├── 769225e747649e41c3dc9fbd67d6d0fa1437bd2a.nq.gz
│   ├── 82b6f69b988d26ab9650e0a96f91f3501add47a1.nq.gz
│   ├── 88a25eb4803fa69246ab547ba807256fdf1e850c.nq.gz
│   ├── 8948863967a79faf03f121884e3dc0505a257b03.nq.gz
│   ├── 8d38ce426f19f19239b01f1577e4b54289b5558b.nq.gz
│   ├── 8fafc04c353d4cddaf0dc67868f47cec3399e86e.nq.gz
│   ├── a42ad19b043c5fa69152a8304124ac84aa4986f5.nq.gz
│   ├── a4859f458a4a4a2c230526d45a7c730a64f53c34.nq.gz
│   ├── a4b71f502f03572d58e4d840195cd5794ea43469.nq.gz
│   ├── aa6dc901d3bec658a223579ac4b4d17da44d8b38.nq.gz
│   ├── b40ba36eed3fe015c0d3fbbd7fd85245cff006e3.nq.gz
│   ├── b7466467b0f5e7c4425b498acce49a8c4df12fd3.nq.gz
│   ├── ba0b1caed91956dd5f4f3a368068a4fedc214d89.nq.gz
│   ├── bcb432532cbdfc6b9ff73fd6831995844285a136.nq.gz
│   ├── ca436dd09f77fd8f81e5594b672d4a6f7b983a54.nq.gz
│   ├── cb98a3d60618a10de07c06bd988a749490fdccfe.nq.gz
│   ├── cf0bb81092a21778417c59e52a665d51212d6ee9.nq.gz
│   ├── cfab3947b02b89f27fc8784e096003d4dd41da2a.nq.gz
│   ├── d1fc94c6b6dda289e90b6f438ca954de5eac98c2.nq.gz
│   ├── d4d6e15989cae2f2e7430a850f3fdf0d33704d69.nq.gz
│   ├── d93af24e49ba836fcef5a7d0ca396bd84e1bba5c.nq.gz
│   ├── e3530cfd85c81a4b910b1edc02ed6cf1dd14f9f8.nq.gz
│   ├── e7d63a3cea382fa5742fa17f3dad5963a2798c72.nq.gz
│   ├── f3d1123771be823aca9be3f1606e1a2b8e18d326.nq.gz
│   ├── f425ba8e2f6f271ad507e93b9113564587a38143.nq.gz
│   ├── f65e4dc9cbe687d41ae3a6822e9f562272d006bf.nq.gz
│   ├── f874bccb8d643175e9451d71cbc9fa06ea8ac031.nq.gz
│   ├── fd7fca7df58c307b6a6ae4507d08f65fa66ffb8b.nq.gz
│   ├── fdb8917157e75b5bb7742e490cb03dbf8467c753.nq.gz
│   ├── ff0460f53286c68aa475df2e0a62127c7a9d62c9.nq.gz
│   ├── ff6681cd55778578e84e0529c19ba9636b3bb7af.nq.gz
│   └── ff93779e1f0219a6685fd2ba32d7ca5a99e0abff.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1a4084931e8296769eab9b2ea75c5e29ac8e618b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 57 files
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

[jupyterhub/mybinder.org-user-guide](https://github.com/jupyterhub/mybinder.org-user-guide)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
