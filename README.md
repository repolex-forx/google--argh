# Repolex Knowledge Graph of google/argh

RDF knowledge graph data for [google/argh](https://github.com/google/argh), parsed by [repolex](https://repolex.ai).

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
rlex download google/argh
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 939affd3acc60395bb34749cabb80cc19bcd20eb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 939affd3acc60395bb34749cabb80cc19bcd20eb
│           └── chunk-001.nq.gz
├── blob
│   ├── 023d9a7449057b8b5fb4032246ae2cfdbb54454a.nq.gz
│   ├── 08661a757f2a7c1b3ec119ec1b1a2a88d1b47e2c.nq.gz
│   ├── 0aeaeb7a929b72ebc5cd41935fea407601e4176f.nq.gz
│   ├── 0f8d6d061d42a16657a91c0e53940008182ca374.nq.gz
│   ├── 13f3a6efe0c0d9f92689494f5cfe0754b1a7554c.nq.gz
│   ├── 14e4f300882b4f6a1af2ee4fd9b382eedfa8499e.nq.gz
│   ├── 177a3db0b95ea72f0a2a6bfeb8d23095ca9ed544.nq.gz
│   ├── 18c039a522ab42caf46642c8f40aea2f88679694.nq.gz
│   ├── 32d46ee883b58d6a383eed06eb98f33aa6530ded.nq.gz
│   ├── 3e1f0531b99d93b7d253c8bbab8d1c18315f5346.nq.gz
│   ├── 413162d369fd2a39845fce273c601a3c110d269b.nq.gz
│   ├── 46083477b17aef3ca9b7f7ddfb4d20d2ad7029b3.nq.gz
│   ├── 53b90ab92b72b1e5b41f2ec3bc9b8a9a0e17edb9.nq.gz
│   ├── 550a7aae0b67dc2d3304243afe46f94516685511.nq.gz
│   ├── 57d9942609643f04bcad12f97f59c9af23523ee5.nq.gz
│   ├── 5b7d4217ad5963c0c110e234ab0c127bbd72c617.nq.gz
│   ├── 5f4bc2e4b04e226bbf3b4d82aaf113d0c46c2ae3.nq.gz
│   ├── 654a071648d6c1647f845136cf9805de41c34916.nq.gz
│   ├── 6aaf8cf2fe8dc06897e418aac7f6c68a0fd6a2c3.nq.gz
│   ├── 6dca2e0ce5e562ec674706e4610130c95cb8c314.nq.gz
│   ├── 744cf42e56aca2be6f769cbe07cb63475c380e63.nq.gz
│   ├── 7e5a0dd411e243b96c1c6faa159f6a38cdf22639.nq.gz
│   ├── 87f152cc553ac3be3508815593e229a00967296a.nq.gz
│   ├── 8c5944c85997a7fd01cf4d6f68beda0cfda9ebef.nq.gz
│   ├── 9322eb38e2f3088623caf86d7cae9d839214381b.nq.gz
│   ├── 9ef1774a50dd8c79a56539653cfe5fb9be65093e.nq.gz
│   ├── a1b458ded7c10cb47bd238a311874af27fcd209f.nq.gz
│   ├── a3a0a42b56c1252344ed91fef0665909f93bbd17.nq.gz
│   ├── a52bddb9d19602d41f096c14565a86c2ae4c87d0.nq.gz
│   ├── ab6ec0a6d2467f8bb9f444dc1deff5a8a9299597.nq.gz
│   ├── aef5d3cc7864d0ea85498ce742db3b6d6ad0c918.nq.gz
│   ├── baec1121051788f1580ccdb86d587c1d1eb96503.nq.gz
│   ├── bd72ecddd22fd40347eeb15ba6756b9a048e5bde.nq.gz
│   ├── c6ff0798f5e40ce1a68ac51bf3f19b0266e722dd.nq.gz
│   ├── ca7c1c0c48f3dffbd84585df0d6971ff8003adf9.nq.gz
│   ├── cfb5a729a124dfdc93ef4f284a4d24237ae81c41.nq.gz
│   ├── d64e075712402bd8b0945a3a06baa28eebad7867.nq.gz
│   ├── d6d3d67438c938725cf6a6ecd6b29106a6e7f142.nq.gz
│   ├── ea5b60640b01f74e295037aa8a6b7d4ea278a739.nq.gz
│   ├── f25f0a7b3e7f0090451c33f72cb5dedc9a29fe4e.nq.gz
│   ├── f6a63999dc120fa4028679edd2b73c813a10b4d6.nq.gz
│   ├── f8b12cb550a3ea803a9caf83648f827dfe1a6d70.nq.gz
│   ├── fc5b584fc86d1d6c079947ae3519464dc8c2de1a.nq.gz
│   └── ff439d06432c14d72f37bf09735059c38653f066.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 939affd3acc60395bb34749cabb80cc19bcd20eb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 52 files
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

[google/argh](https://github.com/google/argh)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
