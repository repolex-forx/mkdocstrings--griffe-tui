# Repolex Knowledge Graph of mkdocstrings/griffe-tui

RDF knowledge graph data for [mkdocstrings/griffe-tui](https://github.com/mkdocstrings/griffe-tui), parsed by [repolex](https://repolex.ai).

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
rlex download mkdocstrings/griffe-tui
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6ccad19400d50d3f529f1afdd299b3b923e9779f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6ccad19400d50d3f529f1afdd299b3b923e9779f
│           └── chunk-001.nq.gz
├── blob
│   ├── 002b2a0406a2be01fdcfcd78c4a90218458ac9cd.nq.gz
│   ├── 0536cbbe261b2d97ed3d94f5b1fd86596a2ae486.nq.gz
│   ├── 0ca7fabfe18b401de8974a8668482dfddfb3b9e3.nq.gz
│   ├── 18228fbadd214d1236a47ba21116a1b43df1d41e.nq.gz
│   ├── 1c29755ef405b04c4b4d84091813ed27c1bba94e.nq.gz
│   ├── 2517e660921a2fc123131e97cd059592e983b797.nq.gz
│   ├── 2540e583c3f68dec71761f9bc6275d2b4c8c36f6.nq.gz
│   ├── 25dc7558c883b82745dac5acb72a32e78cca1a1f.nq.gz
│   ├── 276c7e5e06bcf6635c7eace9cbc8092145f978db.nq.gz
│   ├── 2d46305a68da4b9569bf6813f4d2fb1131653842.nq.gz
│   ├── 2df98fbcac88d8d93c9d18648ba7d5a800100ce0.nq.gz
│   ├── 2fcf869f97e3db32d04bba2de14fc59596538076.nq.gz
│   ├── 30571233ab2743c8bfa278db17f69b884823c94f.nq.gz
│   ├── 35ec8f1917b21691560159f7e6051600f0674f58.nq.gz
│   ├── 408214d2feefc5a607f138b13c70be726bdc9490.nq.gz
│   ├── 422225af973b385c3533e90df42af520afcbcde3.nq.gz
│   ├── 45d2179998a922633f0052dfd3d0baee05eff91b.nq.gz
│   ├── 461f7e3d73ca89f0dee46d673a8057f563b9873f.nq.gz
│   ├── 47bdf451de77bcc3097dbd22b563788ac408923c.nq.gz
│   ├── 4a9c425bcd4c1b04be799b1b4ed3f7a89168dc3e.nq.gz
│   ├── 50a101ef1f4b9ad32b68d7d5687b8de12b6c3ef2.nq.gz
│   ├── 51587578d052005002f5e1f131bfeb180807caed.nq.gz
│   ├── 539c158ce3c610a08251f56c8a8b1550a77efd46.nq.gz
│   ├── 5b25a00f43bcb9d2a68e49250995865e6608c26c.nq.gz
│   ├── 60800c3c1aee36065c399f44b3904712a1631f2a.nq.gz
│   ├── 61935e5d49e2b4f90babe55d6bda7b7401cfc1b9.nq.gz
│   ├── 6d312a5328a96a19f1a3ea4f80a0dd160a1561d4.nq.gz
│   ├── 6f0f2faf32486394750d5d5421e2261430b73fef.nq.gz
│   ├── 73145eec7e2a896212b2a9165dcc7449f0abd318.nq.gz
│   ├── 7b5f18c1854d6b18f56e04bb8b0de4444bd15cb1.nq.gz
│   ├── 812789e68bf5688ca56d42a80caecd04c1e0c4b4.nq.gz
│   ├── 82377e2175cb6a3e81bcd4650e4c158db89a8004.nq.gz
│   ├── 8b4b28b45f23b3a2cf22e732510ad59727333594.nq.gz
│   ├── 92ac8ec5dbe177b6e29da9600c7c3fd18d8069b9.nq.gz
│   ├── 975b5155b41e7a36c392dcf7ab0f7d690967de33.nq.gz
│   ├── 97724fa80f2fd81fddb1eb8b00029dc4fee78054.nq.gz
│   ├── 98cbfdd106f6af898b9ceed1ec1f707b532c5173.nq.gz
│   ├── a09379f1b6893041a9e5249ae2b8e054b532cd23.nq.gz
│   ├── a4003291c3172b3cc92c9cdd5d4f46d1708f75bd.nq.gz
│   ├── aacbe59290f38cae9a3b0f007ee63a5a9942c3fa.nq.gz
│   ├── aafa4fbc6f3814b284f2859e5ee0077fc36974e7.nq.gz
│   ├── b0e88007962f4801cb4c05ffe3d2f37d8a5e32fc.nq.gz
│   ├── b149d0120334ec19001efdbd479598561952c3a9.nq.gz
│   ├── b56a2866c098400c2cdb660aa908a99bfd0cba34.nq.gz
│   ├── ba70d623ce5027843996bc4e9b08da4a92264a07.nq.gz
│   ├── c1660d0d8acee48853d347f8f5cf7aa4cb882345.nq.gz
│   ├── c2eda0df52a5c1bd708ad342b50fcc917be81192.nq.gz
│   ├── c4a180a3325cd3b07f80af8b9720a194260373a6.nq.gz
│   ├── c65a958dbb1c1e60585700f45f4df3e865b9bf9b.nq.gz
│   ├── d08821b7c4397da8fe425a75043e0a6359cb2108.nq.gz
│   ├── d5a42eabd6ea3758a88140993b95e223e8648471.nq.gz
│   ├── dc711a48b9bd2f8029f3af22e74526a2cb8661f3.nq.gz
│   ├── dc9a8f17c6e3f0117661042120c4413a21065bce.nq.gz
│   ├── dffa5fc06d1e67601b3ba9f4ba429f8516d90169.nq.gz
│   ├── e16f4c389e075d1994b06b1750871e23762c8377.nq.gz
│   ├── e3d28b38c94eeb9fa2ea0a955d3ff31c8c3ef6e6.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6bb5b91b56c550fab69e0f2898006069366f3da.nq.gz
│   ├── ea5d47134c84edb8d3ed775e27b9ebdb167373e7.nq.gz
│   ├── f072271cb235e97740a9887ebc76955c62749a18.nq.gz
│   ├── f5839c5f018e9c11e0986a262a6f673220cf70e9.nq.gz
│   ├── f6ab1aa2cdbbb6aa245be35e5090520815c3f7ef.nq.gz
│   └── f97321a5d0ecc1a536fc3eeca5a23f446efb07bd.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6ccad19400d50d3f529f1afdd299b3b923e9779f.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 70 files
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

[mkdocstrings/griffe-tui](https://github.com/mkdocstrings/griffe-tui)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
