# Repolex Knowledge Graph of tiangolo/dockerswarm.rocks

RDF knowledge graph data for [tiangolo/dockerswarm.rocks](https://github.com/tiangolo/dockerswarm.rocks), parsed by [repolex](https://repolex.ai).

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
rlex download tiangolo/dockerswarm.rocks
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c504a4b34d7babd970771255c4e1a57f710ee4dc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c504a4b34d7babd970771255c4e1a57f710ee4dc
│           └── chunk-001.nq.gz
├── blob
│   ├── 00813a799c8300590e2542760bb85139da6c5881.nq.gz
│   ├── 094f2988c49eb301db834aa289647a2c3236bfea.nq.gz
│   ├── 0e55d05f1eca183de18f49df66add97f4b999b27.nq.gz
│   ├── 10a0d1feadcf876e28c2a2255a0321003e7c83c4.nq.gz
│   ├── 1591365077b207a09fca211cc2654400cbf9cdf6.nq.gz
│   ├── 1ec3a615befb12e9e6f0c9eb00d8d10c00431174.nq.gz
│   ├── 239e2352c9f0193fce16e990a7ef1d6dfdc3358b.nq.gz
│   ├── 288e03621e80c239e6d182880c5d61de9b4dd6ff.nq.gz
│   ├── 2c0733315e415bfb5e5b353f9996ecd964d395b2.nq.gz
│   ├── 30637a5285dbdbdf5947c79e574a7076db63ba03.nq.gz
│   ├── 307d2dbdd35bd5ce0a7051178930451946ae3501.nq.gz
│   ├── 3e56a2d4f5c061dbd8cad7f0ff39896ff015340c.nq.gz
│   ├── 46fc6ccc8bed0142e9bb0c193f95ee686393b115.nq.gz
│   ├── 4f4ae2f74e4034638161f7c5da452f25e2601e29.nq.gz
│   ├── 53201d0a681074f24c6467270cb89e5c1b4c9c61.nq.gz
│   ├── 545d30a18cec93495328868463868efc1fccb7d8.nq.gz
│   ├── 566c94bd3387dcaaf6743d2458a725e30deed893.nq.gz
│   ├── 699bb1d65116173435175dafe8804cac376e4edd.nq.gz
│   ├── 726dbade3b84902f6fd83ebc82a938fa71e86827.nq.gz
│   ├── 72bff281cbfe0e4b02ed575cf619a07c357fc186.nq.gz
│   ├── 72c73aa625829571da2c59305b95e14e3c9085d0.nq.gz
│   ├── 755f8bcf8cb515ef28dbed472d7a51606ad6f0fd.nq.gz
│   ├── 77d0e6c5aa917cf5fd5edba06c299be7a7b120a8.nq.gz
│   ├── 7a24cf398f0577b68948f8e139a46248e24482cf.nq.gz
│   ├── 7a254464cc78ccea32b3ded00513c44c4e4da412.nq.gz
│   ├── 7c59b92d3c14232a63fc32b3cc60b4e725d560f8.nq.gz
│   ├── 7d0f40ced171ff121d2433559e373147e77754b7.nq.gz
│   ├── 7e2c90b71347f675132fe39a4b2842dae129cabc.nq.gz
│   ├── 81dd8e68cfd2a961d46ca46e85af6bbe203cfaa0.nq.gz
│   ├── 834e180c1440f6eee8b97e91f83d208eef675170.nq.gz
│   ├── 8db80351daedf8ca6a1b5eb74ce589bfdd019b1e.nq.gz
│   ├── 9c3df61d6b7608d207671ab8ea3b5177bd56d699.nq.gz
│   ├── a0c025a069d276b61fd2fce100a8355c032dbcef.nq.gz
│   ├── a0de9ec4b263b8d75af58334d6c197a5842d3b30.nq.gz
│   ├── a501efa8488dd96ef26f58dcd7c3bc628b0cc393.nq.gz
│   ├── a5f7b7dff9ee187601f3999377a322e429e91dcf.nq.gz
│   ├── acd18198fdb3dd8abc2584f8fb36f6dfd1cfd2f2.nq.gz
│   ├── b3e312833cea777e9bb5ccde3e46b39d0bf4eb19.nq.gz
│   ├── b5945a006c7966935a09903e2f9184f1a2bcc910.nq.gz
│   ├── b7fdc1ca7ea8012a1f315363b1b219ed8858c26a.nq.gz
│   ├── b98b0b6c0b14e39277fa9edfd834df20bbb04c64.nq.gz
│   ├── bf97d0ea8e2fba1e77c829a4af57b4b8b5cdca10.nq.gz
│   ├── c4ff91f43506b70b30e3a4ee9f9989b13e150d7e.nq.gz
│   ├── ca09433b2ef20538fec35213200daafdb83c8c09.nq.gz
│   ├── cb65936840581dd3ae59dcf8e248bc1e1423f059.nq.gz
│   ├── cbf75bca50538d64121e05b548bdee3b4cb53514.nq.gz
│   ├── cc0798138c3245d6c260645523429b2e49e3f280.nq.gz
│   ├── d4141ee9f6ef471fed35c1bfe8b05ac8ce85908c.nq.gz
│   ├── d8e682c5181797221e610f314dc02ee8a1fba08f.nq.gz
│   ├── d91e8a664a39972357f255f593d65721e7b4d489.nq.gz
│   ├── d9734509889c3c31146d79428e25e378a9e9bfc3.nq.gz
│   ├── da2c24175946a218c49208f7198348fa94a6fcf6.nq.gz
│   ├── daa6038a0a8a386d6315b541c501a9a2abddc650.nq.gz
│   ├── de4d8d1442e93d761007e4be0c28dcf6b157d8da.nq.gz
│   ├── e1eee513a63e8371ddd3cc67bda2c37592bfef2a.nq.gz
│   ├── e69332b36faa84e38a071319de216f8f2f844b3e.nq.gz
│   ├── e75f530fad59d6bbab5d52b827f2c8fcefaf15ef.nq.gz
│   ├── e9f9e125f79ad3d8171ce40a38f54e6d26266e76.nq.gz
│   ├── eb8a24ab181bf3044ddc05892c67460ef9ca83c5.nq.gz
│   ├── f4cb8ff876cfd1a3e33533eb3822fe4a1705e972.nq.gz
│   └── f94530eaa55f5eb76ef8653e9322dbc6e1f8533e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c504a4b34d7babd970771255c4e1a57f710ee4dc.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 69 files
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

[tiangolo/dockerswarm.rocks](https://github.com/tiangolo/dockerswarm.rocks)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
