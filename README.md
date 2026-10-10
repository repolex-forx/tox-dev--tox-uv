# Repolex Knowledge Graph of tox-dev/tox-uv

RDF knowledge graph data for [tox-dev/tox-uv](https://github.com/tox-dev/tox-uv), parsed by [repolex](https://repolex.ai).

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
rlex download tox-dev/tox-uv
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 808fc710f75e7fede6c5eb0d8c280879a5fe58d2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 808fc710f75e7fede6c5eb0d8c280879a5fe58d2
│           └── chunk-001.nq.gz
├── blob
│   ├── 00acdcf55af96ae48c5fdfbb53239c51a0a83d92.nq.gz
│   ├── 0dba255e8c8d29a25cd7a4cd60f516fe67661ab0.nq.gz
│   ├── 0f9e29ba8c2dadd452306034fef7602da9e07023.nq.gz
│   ├── 156aa8a91732a0daf7540bf2e232b161491beece.nq.gz
│   ├── 176eab8e9436278c1dbb32a3c3ac14c0b35cca21.nq.gz
│   ├── 17b52737c26cfe1011a49aa9f83414ca8e8b7f76.nq.gz
│   ├── 28b56885814bb2e9a611611dc9593a14bdb869db.nq.gz
│   ├── 29bea9e12d127112a570d81c97e840af1b0ea79a.nq.gz
│   ├── 2bb180c9f5d88bc0f12d6474011d56293e0f0fc9.nq.gz
│   ├── 362e879482018d602da2f10b4d31c866072049c7.nq.gz
│   ├── 364982344fbd94d55705e1f27a9a87abaa255333.nq.gz
│   ├── 3950347d75e3f4842e4ff21863d78ea35ba62dd0.nq.gz
│   ├── 3bd9b1c10239877c59c4265e2767e0becda8d5d1.nq.gz
│   ├── 3d3566e374863ecd9e298f2ca529dd6a511df33d.nq.gz
│   ├── 468368363ec7e4d5a64fc382f7576beecee7d942.nq.gz
│   ├── 4976c5e4cb3bc48cfcf75429302a2f78253619b1.nq.gz
│   ├── 4b0be76e1d55b19c1c7762995025b7198bef028b.nq.gz
│   ├── 542cdd2c89c8fcba8bd110bd97675c7129b97184.nq.gz
│   ├── 5968e5bcc55e7d0e43554bfb3203512e1e1fe0d0.nq.gz
│   ├── 5f89818f9e63c2f6829c7706c57f223cdb5bbd38.nq.gz
│   ├── 62b1de5587486d76011b14c0f7cc8be67dd1251d.nq.gz
│   ├── 67fd9f3a0b291ae7d0450c3503f032aee2522cbc.nq.gz
│   ├── 69d0cfd202c019ca1d5a92d59faf9a1380c61930.nq.gz
│   ├── 6c0b75b9bea9f21d889aaf4fb5188144563a204c.nq.gz
│   ├── 713cf99948e8f5a194070eff24126f707f550d9f.nq.gz
│   ├── 74259c1159f592a8feda09f9045471c38f9881aa.nq.gz
│   ├── 80e425487141275d6c6490100fa0528a2f27ece7.nq.gz
│   ├── 849bb48c171c449efae36f9119267b27c73958e5.nq.gz
│   ├── 8e987d129e2fef0908a6dfb87303c21fdcbf410c.nq.gz
│   ├── 9354f9f8f7d4cf953e07f00c389a20b0e5337513.nq.gz
│   ├── 937fb7ced7114917afe533d0cb4716cc5cbfa8c1.nq.gz
│   ├── 9e69dd6e2fbae75915253793a79d29e54e550c8a.nq.gz
│   ├── b02156dfc63a143b463327340ad452fafe247e40.nq.gz
│   ├── b42d2d6249ab0d4b0e538a22f64d8f413a399f28.nq.gz
│   ├── b624afd4b1dd238d84fbf60cf12f015e47df8a33.nq.gz
│   ├── b76886825641b81fb1e0b514bf1fb04d8eed3432.nq.gz
│   ├── b853180fd52c13b7a5e07ff7d014bc534c76215f.nq.gz
│   ├── c792f1303917a09991cabd6fe2e49c1d9b714bf2.nq.gz
│   ├── cffa571e274dc76c536a011df7179119952842d4.nq.gz
│   ├── d1436c7054a0eacb2242cdcd6696e1f1c01bbd61.nq.gz
│   ├── d2e02fffc4df0e9177324b4a30dd306f9d71989d.nq.gz
│   ├── d3fd6d92a7e995b672180627d1af94370dd7e4d7.nq.gz
│   ├── db843b08d845fa814833983130e74ea22be4acd6.nq.gz
│   ├── de75b337ce73bad60f0efaa27c4ce518c2f16c96.nq.gz
│   ├── e49e2e98ab7dc2ee2b49a79f3a9cd4836abcfaf6.nq.gz
│   ├── e66d53ac9c94347a955fb58cd62262f5e56e4801.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e71250d14d6470fdb06f6762f3c563d2b57327d1.nq.gz
│   ├── e7a0393c63a71dba389de60356a7f0c7917535c1.nq.gz
│   └── fec68a3678bc83d2f2756306425478c878acd7e2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 808fc710f75e7fede6c5eb0d8c280879a5fe58d2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 58 files
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

[tox-dev/tox-uv](https://github.com/tox-dev/tox-uv)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
