# Repolex Knowledge Graph of canonical/oauth2-proxy-k8s-operator

RDF knowledge graph data for [canonical/oauth2-proxy-k8s-operator](https://github.com/canonical/oauth2-proxy-k8s-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/oauth2-proxy-k8s-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 933570c2547c811cb29a86bd2cd5cf9809b152f6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 933570c2547c811cb29a86bd2cd5cf9809b152f6
│           └── chunk-001.nq.gz
├── blob
│   ├── 03cce058e21785f5ceb94014ab6ea85bde71fffa.nq.gz
│   ├── 065eb0f11e67869d4117f127a6c0977836e76232.nq.gz
│   ├── 086403edc36a0d81f38ed0959ea46a181b1c1b65.nq.gz
│   ├── 1243caa07ec68662a994c352166bc3a33c08b96c.nq.gz
│   ├── 13ec6ce68ff3b2595f1bff8d2eac5ad5b6775fa0.nq.gz
│   ├── 166bb70f891efe5f46673da9763dc00f1866d8bd.nq.gz
│   ├── 250a9776f14de87fc8322a46932e5504f1031c17.nq.gz
│   ├── 25ac6edc6cbd9bc5afa5d4768488af9223fcbf89.nq.gz
│   ├── 2cd960c5ef6dd49f09707323e4b54201a7a7dcaf.nq.gz
│   ├── 2fade8e491141f379ad0c7f7ef5d345868afdb35.nq.gz
│   ├── 31af79f19a0c4f72f855cf74577b6e2d302acb93.nq.gz
│   ├── 34dd026407a968c94b3eb7c22bebae0d6d16ca58.nq.gz
│   ├── 3658bbaa34fe809d2fd0c4feb2da44689eeacba9.nq.gz
│   ├── 37f84f4826b7ce8b85eed45aefbd6ca0163a8d8c.nq.gz
│   ├── 382581e536e69ea9d357f899c42dd221c65b05f8.nq.gz
│   ├── 3941648fe616c4859bd0c4af68052ac2607edd87.nq.gz
│   ├── 3ba5af504a16fe8fba9191b1e208887998dea6d4.nq.gz
│   ├── 4260bcba6a0345676866e574aa49fe7e9841ce18.nq.gz
│   ├── 444e0a33c0f03930adcc99fbb6c3973c2d170d75.nq.gz
│   ├── 44a35480cf9226e18d7aec0b208e7d4841a27a08.nq.gz
│   ├── 46e60952b3f79b577859e0cce2debbc809f563c9.nq.gz
│   ├── 4fa549f230343bc90dcdbf5282ba1f45f20140b4.nq.gz
│   ├── 5554c7878549f804db2e2d01a4cfe14090ab91c1.nq.gz
│   ├── 58a21e39cef317fca203458f7558fc0b3e5edd78.nq.gz
│   ├── 5b8558cc899028e5ea26586ab58997af6d735ec2.nq.gz
│   ├── 6512f3f47fc3c894f48bb0d7d5f49beb4b327c7e.nq.gz
│   ├── 693be846b50981f6fd2d04a8c1f7ff7833c6315c.nq.gz
│   ├── 6956acb28821cdf8837075bace6c85e4cb488ab4.nq.gz
│   ├── 6ccd559eabeae93e4d23215fa450130fa9b37ace.nq.gz
│   ├── 6ec6de4f7542fe2b61a1c5b2428508391948b81d.nq.gz
│   ├── 76f15e80e6ed89f83b6a02aee8f1fcd14f2f5af3.nq.gz
│   ├── 773d62eb66213526e9e6a4edeb932fb482856151.nq.gz
│   ├── 87c62675acdb96bc9b94929acc97d0675c8248ef.nq.gz
│   ├── 8e8aa8777aae9723d91633ac9745dcc840d0a8f4.nq.gz
│   ├── 93a988abd3c979763972aadcab8b14be2bf4a3f2.nq.gz
│   ├── 97117f4c047423f56fe87cc25580bdead00705db.nq.gz
│   ├── 99232c2be5da6200388535a8bade1089566ec2a3.nq.gz
│   ├── a04e32e0998d895d6ae78b879e761911d6457423.nq.gz
│   ├── a3fb91091c5af8099bc9e5e03868241527b8d16c.nq.gz
│   ├── a60d12ae209286b96077567015a29ccc8ad2a07e.nq.gz
│   ├── acf487cf3b7d336c93f40bde7b70e59df4a32fde.nq.gz
│   ├── ad43250e3315c26825ba35f19a2a9e1a8659bdde.nq.gz
│   ├── afd0f2fdc3c2e9f79951161344ff90f6e9aacb2b.nq.gz
│   ├── b0c0284d812534875708fe302c0fc7d5ce91231b.nq.gz
│   ├── b2348b9fbfdc4eb154566c80f844510446be1d02.nq.gz
│   ├── c0b35a3a058285371a656f208d4194286c72a075.nq.gz
│   ├── c3df54d3b48f54a51eeebfea819147ef99de09eb.nq.gz
│   ├── c4a371b812c1a5056a6bfe2068b2a73eb8bd3a7a.nq.gz
│   ├── c7cedef565a7c06e0cab82b7421eabfe1ed659ff.nq.gz
│   ├── c94679f688f60b972d07b6388bb05de566fc9e24.nq.gz
│   ├── cc3e5e93003812f32372ffe1d1c630a0e29541a4.nq.gz
│   ├── cc4c3e1032f0b22c43b67869ebbd41bea5306a31.nq.gz
│   ├── d45673d0ea5778c3ecccdf5bb0280992ccbc2ba2.nq.gz
│   ├── dc4d84559dd2db7206f81a77f8381b9f75609e73.nq.gz
│   ├── e020a07585a80d8fcbbe1c8bd5fd3e7d13f0d215.nq.gz
│   ├── e639a8f03d1a433ab19f486d5818c47420998a50.nq.gz
│   ├── e99ee2ee36340dc218ffa7ed49c68455fa01dcc4.nq.gz
│   ├── ebb45f4f4962c48d8e134552f082837741a52d93.nq.gz
│   ├── ec6c8562cb17231171a42e72e59c96906243c3e2.nq.gz
│   ├── ecd0c0d12406272ccd82990c137332116305355b.nq.gz
│   ├── ee9b81733309304dd1d02cc71128e558c9894bfd.nq.gz
│   ├── f430c4e21a731aa14c0c7e0e836f5377923c04d5.nq.gz
│   ├── f849d85841908f003664a296aac67898d46d4f18.nq.gz
│   ├── fd7990b452c77140b4cafe3e731314f8e2617f22.nq.gz
│   └── ffeec6e52ce561b3043a2d878cab6f59201e8a62.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 933570c2547c811cb29a86bd2cd5cf9809b152f6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 73 files
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

[canonical/oauth2-proxy-k8s-operator](https://github.com/canonical/oauth2-proxy-k8s-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
