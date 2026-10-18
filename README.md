# Repolex Knowledge Graph of kvesteri/wtforms-alchemy

RDF knowledge graph data for [kvesteri/wtforms-alchemy](https://github.com/kvesteri/wtforms-alchemy), parsed by [repolex](https://repolex.ai).

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
rlex download kvesteri/wtforms-alchemy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8b5bc887ed6c05c41259341a6b315b277cfd0aa0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8b5bc887ed6c05c41259341a6b315b277cfd0aa0
│           └── chunk-001.nq.gz
├── blob
│   ├── 06e3f0f122b5bc816932ee63476327384909514b.nq.gz
│   ├── 07898b4934dbfa1fd27e8f6aaee18290548bfc52.nq.gz
│   ├── 101f0e5af783ea2c33cd5c44439a17bdd06c0da4.nq.gz
│   ├── 17c6b1b2f8721078bff9537d05cdaca889b84fc5.nq.gz
│   ├── 1b865e98d15778eb1be407b42117da40b2353caf.nq.gz
│   ├── 1d4e0ea831b91967dfbca6aa82739f63fa3b6aa9.nq.gz
│   ├── 207140835e74b401b60fbad765585c4964d9b9dd.nq.gz
│   ├── 222c3514fef499f33802feb1f315386f41ae6593.nq.gz
│   ├── 2440d7556a562fba28fe14bdfb1676e15325fba1.nq.gz
│   ├── 28ff2fc1cac0b7cd04a62b9a4f7552a0c5cfc105.nq.gz
│   ├── 29482e3a6622fab4f54b2d3c04bd36e1f6769302.nq.gz
│   ├── 2fb1f6f6fbc220e0b4e43b9f0094803b02015458.nq.gz
│   ├── 3227a334c2303b563b0d7637c2f8e0a457c7d9e8.nq.gz
│   ├── 39e756786b472a2b338bf13c349c18279d44deee.nq.gz
│   ├── 3a31a071e6c946b917ae68e60be6764940613196.nq.gz
│   ├── 3c436a9f67dd10e8e947c12117247741a4990285.nq.gz
│   ├── 3c7d0edd8d955baf4e945f410c7b7cb86e8424bb.nq.gz
│   ├── 425553805845299e81ba449adf34eeefcc796022.nq.gz
│   ├── 4827e228426990fde826aa94313dc73a46180a30.nq.gz
│   ├── 4cebc8942eadc3e2c75543c66c1c5514907ac3d4.nq.gz
│   ├── 50aa044a5863dcb3c1b92ef6bcaaf489ff8fd9a6.nq.gz
│   ├── 5106afcbdb8f131e3bd4d93c325cc3a68ba1dd09.nq.gz
│   ├── 54bd3fd596eacbdff7e26f14a12d75cf540be1ea.nq.gz
│   ├── 5610ec4e90962f50bfcb6547a53c0884cbc7b70d.nq.gz
│   ├── 5732cbf876b05671992ebebf1802299e0bdd6eb2.nq.gz
│   ├── 594dc35beacc22cb7c95d885cd6a317dff7b0519.nq.gz
│   ├── 599f809089d5b038b7d51483b108866b032cee2f.nq.gz
│   ├── 640391beb6683f314b28bed76d3b193eff362f9e.nq.gz
│   ├── 65e364fba02f7a24df47324d4fa79d8573bf5b85.nq.gz
│   ├── 66f0eb48de09e9069358da699cf881757527841f.nq.gz
│   ├── 71abcc05e8046b344a304ebfcaab669cfe33d34e.nq.gz
│   ├── 74e93b18f0afdcbc59e6f8e17a8e79d318f19ac0.nq.gz
│   ├── 7c91b36d3a292943c7810fb9771103f87235734f.nq.gz
│   ├── 7e6291f3b9bea34542bd0bf4af2fe238d981952a.nq.gz
│   ├── 836b8ce0e36319ffbf8ca4d72105da7787fe9f63.nq.gz
│   ├── 84979f2954891ffcb0c42d87622ebfb1e78fd415.nq.gz
│   ├── 92d640a0758bb7ac7d6bd91af61e95b91bed5b43.nq.gz
│   ├── 94eac291426d741a4db7135cd9b36e3e3084421f.nq.gz
│   ├── 97b88067d81f8d766cc6f1cea29ffd5f8bfa7398.nq.gz
│   ├── 97d7ea58d60e7b5ecfb2d7a2d5f27d212634acab.nq.gz
│   ├── a17075fe267eff7c87f3281b00b6e61fbe7e7c18.nq.gz
│   ├── a9719d09d03d4b45a03894ae9d7408e9f064310f.nq.gz
│   ├── ac4f19f14d98741b3b32275ab874a8507e154856.nq.gz
│   ├── bc744789170e6cc3b5a2cedfeac44a5e4a214ba1.nq.gz
│   ├── be7b890b3001197a14ced26dd1c68f59e9eb20f0.nq.gz
│   ├── c43cb608658d313d46b6fea305f99f7aace6590e.nq.gz
│   ├── cd079497270795dad8429c61cb463c64f3a425ec.nq.gz
│   ├── d24641c03449164a6c9003f42bbee5b03176ee89.nq.gz
│   ├── d4a0d39dfaf380c7241dfe377aec3de7caaa8a67.nq.gz
│   ├── d604ce842e5f36785bebdf279b73cce044923b6e.nq.gz
│   ├── d656cf76d0f82d131fda8e61a4a4ce3f51faf3bb.nq.gz
│   ├── d8552917c54c8dcff8641c71aabb40db2dad8bb8.nq.gz
│   ├── e6927bd1e8d6669d44f9cc2d5636ffb6d87abf0a.nq.gz
│   ├── e7ca1c2da00cc47448e0c2fd8ef7567fea50d050.nq.gz
│   ├── e7e0df9240b7f5de8cb32e55e45f83ac0b1b904e.nq.gz
│   ├── e993c0fa1de87214a1442e10cc587efa3086294f.nq.gz
│   ├── ea0d9bb21bb23f7a212e4b6b4bdbe78971fb050b.nq.gz
│   ├── f056bb19a5eea270b7fff816aacaef09875e4e2a.nq.gz
│   ├── f06a0ce9cd99777c4067752c2f8a96f110fe3fff.nq.gz
│   ├── f0e96bb9c9da8a7a2400119dd56d49fbc665df2a.nq.gz
│   ├── f23baff3b8ea82bec2c784095bf289692b1c8366.nq.gz
│   ├── f68b5e87a2de2a21faa58c9bdb101b56341b8867.nq.gz
│   └── f902ba934cc507a98108d6a731313b8f1b0d5521.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8b5bc887ed6c05c41259341a6b315b277cfd0aa0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 71 files
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

[kvesteri/wtforms-alchemy](https://github.com/kvesteri/wtforms-alchemy)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
