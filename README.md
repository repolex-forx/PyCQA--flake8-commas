# Repolex Knowledge Graph of PyCQA/flake8-commas

RDF knowledge graph data for [PyCQA/flake8-commas](https://github.com/PyCQA/flake8-commas), parsed by [repolex](https://repolex.ai).

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
rlex download PyCQA/flake8-commas
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b0bbc820c45eaedcfeac24ad9446e09fdcf2788b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b0bbc820c45eaedcfeac24ad9446e09fdcf2788b
│           └── chunk-001.nq.gz
├── blob
│   ├── 0098868e6f0fd2c0d4f8afa3413904c0beaa24d4.nq.gz
│   ├── 00ad04a248636409046b35f3e989fac113e2b275.nq.gz
│   ├── 08dfef2b6785fd908bdb82f7005bbc961d7c1367.nq.gz
│   ├── 0cf574a8f9e2a27e68890dcaa945e41b7cfce5c5.nq.gz
│   ├── 0e327e74e2c465addbe14b7598eecb54ad58e5fb.nq.gz
│   ├── 10104ae3aae53001a32cf4728dab1a9a1951565e.nq.gz
│   ├── 123b4ed17cf0b10949eb49edbe9c0eb96f126c7f.nq.gz
│   ├── 1a2aef3f81d3f1facad8a92fbd79c5157892ee68.nq.gz
│   ├── 26ee179feaab60d4b315dba1ffc8b8cc890c21f5.nq.gz
│   ├── 2d4375f345fa617acb9d26ca3626df6d2de6fda1.nq.gz
│   ├── 2e2d213bceca2ecee9f5daa4542627c5abd8c0eb.nq.gz
│   ├── 39d1daa4a373a7ab990a34c1dfb13917c142773a.nq.gz
│   ├── 45721ac52e78dcf524bf64e34ebe90c0ac58ab8a.nq.gz
│   ├── 50e630556976bbdb040a9002c25fd42c8044a3d1.nq.gz
│   ├── 5218307c8925abbb5d191f71a3a45326464d6554.nq.gz
│   ├── 5802340f2e76deff72cda41297df9cd7a3bd0619.nq.gz
│   ├── 59c7be2a296822f5ace8b7e1edc803d1336fa412.nq.gz
│   ├── 66ee005d2a20a2cbbbaf89c5c39e0af7da889f6a.nq.gz
│   ├── 6ab598b702650a5d36334bd7dd4371a1d7467492.nq.gz
│   ├── 6e822da82d61041c346f4631a94bd69ea1791d61.nq.gz
│   ├── 75bb215132f2675eb37ea981a20a2d1d05950c0c.nq.gz
│   ├── 79b6817d5b3caeedb3f51faacbf846040c08f44f.nq.gz
│   ├── 79e2bae76fa367cc934af0b13e0d6d823a48645d.nq.gz
│   ├── 85011f923216675756a851bd647e3f82aa3a0839.nq.gz
│   ├── 866ef228c27272022a59cfb97afeb07c217f7af4.nq.gz
│   ├── 8a2e421b875af6d0b8487d4eb888b0d9fcc9c70f.nq.gz
│   ├── 8bf48f257fef63b4e087e4bf873759156f397464.nq.gz
│   ├── 8d7392177f806771acc9ed02d8a13ecb387ff913.nq.gz
│   ├── 8e936c237297e41fcb6d7f77124a3405f5216c98.nq.gz
│   ├── 96dfb322262c744279502ee47871faf6a1cb5ec8.nq.gz
│   ├── 98613d27306557b6a5344882a44d9d3ddb13ae06.nq.gz
│   ├── 9d59639f49dc433c567c7e6be192c05cc5f5abb7.nq.gz
│   ├── a101791b6158a3576308ee899b75372ea73b799a.nq.gz
│   ├── a410b9c9f5b35a8cbdb1f1aaa7b753f5b3f01f26.nq.gz
│   ├── abf2bc25ce440ee989c350acd3cabab8d1809e71.nq.gz
│   ├── ad34a1b6c635fd1476f60ca062c30a00d5702b0b.nq.gz
│   ├── be1c9bd7e23cfafd1381339a2b4e2efa145770db.nq.gz
│   ├── c74773e2dd1dfa43d398c86889ed5897e8579aa7.nq.gz
│   ├── c772c2e57430f0f6b97e4202b25e22e9fdef4c5b.nq.gz
│   ├── cfdd303f361c630e608686651ebd8bf3f333cf94.nq.gz
│   ├── dd31554f280440db996aee3bd2ca988e8bf275a9.nq.gz
│   ├── debe6d4ba20c15a966d614cecb63f923a8b680f2.nq.gz
│   ├── e343c6a6d189cea9cf95e995dc291d11bf94c562.nq.gz
│   ├── e3d14530b3a19fd91bad49154e0e9e23f4fbfe0f.nq.gz
│   ├── e67e10f61f88844820886894515e9326908e5a41.nq.gz
│   ├── e9057d72e60be6815609e200fe4da7247db1749e.nq.gz
│   ├── eb992667a07d102f345943f491b42603d1db70cb.nq.gz
│   ├── edc5cb3fd15fd7805ff39220a86fdf0b272c065c.nq.gz
│   ├── f247790e489ddee9bede05350ef55119e5fe91c3.nq.gz
│   ├── f63fafd3031ee3a47af2e262d25e116ea429468b.nq.gz
│   └── f8d359a800583a825a5a50503e0f6ef8af8033e8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b0bbc820c45eaedcfeac24ad9446e09fdcf2788b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 59 files
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

[PyCQA/flake8-commas](https://github.com/PyCQA/flake8-commas)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
