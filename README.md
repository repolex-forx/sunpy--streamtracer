# Repolex Knowledge Graph of sunpy/streamtracer

RDF knowledge graph data for [sunpy/streamtracer](https://github.com/sunpy/streamtracer), parsed by [repolex](https://repolex.ai).

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
rlex download sunpy/streamtracer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fdd618e518f9704f6a1ac3a8d341514cb61afc69
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fdd618e518f9704f6a1ac3a8d341514cb61afc69
│           └── chunk-001.nq.gz
├── blob
│   ├── 01130302dae4aac9522059644978aa015bbdeecc.nq.gz
│   ├── 0a2da916dedbdaad8fb5cd2b4f44b45f3f51c4eb.nq.gz
│   ├── 0da9ccf303848275af6af8e5bef432883067a236.nq.gz
│   ├── 1bed0c84d3190a600f01b57190cc90b1a08d2763.nq.gz
│   ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
│   ├── 2140b1c29df0d36a7c367603b000f892cd758e8f.nq.gz
│   ├── 25fdbed0a01e5416cfc20ea2ad21fc1ef29ab336.nq.gz
│   ├── 278b0045aa9d03f1f415b871d5a7abd821a6818a.nq.gz
│   ├── 27a99baee6e0ea78fef2636295896cf14d2925a1.nq.gz
│   ├── 28abb4f6108a4bcf135e8d87ecda8b15351e433d.nq.gz
│   ├── 2edde51128e8931be5652bf5a05121717cdb8cbe.nq.gz
│   ├── 3a4df5cfa923745ade388f267c17ed4992abc43d.nq.gz
│   ├── 4d4ed0fbae99c908d3902a39fa8b7a5785e4259b.nq.gz
│   ├── 5055efa889054986b6c9c826d7b10eb3c14eac9c.nq.gz
│   ├── 52f978068556c50e9fd7503f7203e779b371a208.nq.gz
│   ├── 5a91cac2270d7e2c186cf54ab41aca3ebfd16c5a.nq.gz
│   ├── 667818eec2b06bde6b88b15acf38e1f098463999.nq.gz
│   ├── 683a1cb131299fae20debd3885535578753ba40c.nq.gz
│   ├── 6bd91a193bf78c419e022933902a0464681930bf.nq.gz
│   ├── 7858124b6e760214e2f3301e0d17904032acf463.nq.gz
│   ├── 79183a10f68f0e9358958edd409f6a158a741e54.nq.gz
│   ├── 79d9f9717eb281ebdd2e87632b333b65cb698efc.nq.gz
│   ├── 7d388e3ef17b14d560a2a08fa3004807ad0bcbd5.nq.gz
│   ├── 82953c54f6e8d41cc261ec22b75e5ffefb4ee5db.nq.gz
│   ├── 86cb3ae2a37686da9e34121a866d4dc6ed345250.nq.gz
│   ├── 86d3db729e5576b878b462729238138e84e390f0.nq.gz
│   ├── 8b0974c59d9d2496f476c4d4d170b04425a8c4d9.nq.gz
│   ├── 8fe09b731963a1272a62a3360bbf019ea563aef2.nq.gz
│   ├── 94a9ed024d3859793618152ea559a168bbcbb5e2.nq.gz
│   ├── 970a27f7d1383f248c1ab60731c134efd8c1629c.nq.gz
│   ├── a024e35b9651ce5ef4044f5d3868813dcea848d4.nq.gz
│   ├── a3678c42ba4e535aa6fe8a762603275a4319378c.nq.gz
│   ├── ae41dbf3acdd747ac50270a23f45fe782c473c30.nq.gz
│   ├── b069f3e96b8423c6c1b1f680e340b4622d74bf1d.nq.gz
│   ├── b1bcf192b15904f007be5ddb062634906971e994.nq.gz
│   ├── b3d86e6a627132853b1de08ee86627b541747311.nq.gz
│   ├── b45677739ea40b85c37958b53e9becf99bcd52bb.nq.gz
│   ├── ba9dcc240654079a51990b7205821c95878fa360.nq.gz
│   ├── bf724b1dfc13ee6f78f43f18a7a7c02d662cad04.nq.gz
│   ├── c318a551d0e94e05267540f9665750053ff4de3c.nq.gz
│   ├── ca0eac2e8b861e50ffd49e8e2a60a40dcacdff64.nq.gz
│   ├── cb412fd8b3b3e51621544977ffc9a53e698e90ab.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── e09d480dd59ce8dd9ca4adfe2a25c8cbd85ca5b8.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eec8ac9edde83dc0bdf27a26c3c7092dbb848c47.nq.gz
│   ├── f3c5bd04af61538a99858f865387e485eee74933.nq.gz
│   ├── fbb5a035bd7cd00dded02929d2b8bfb7af3e6d1d.nq.gz
│   └── fda8e1151aaf71b07480e80e4358b733c21e3bf8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fdd618e518f9704f6a1ac3a8d341514cb61afc69.nq.gz
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

[sunpy/streamtracer](https://github.com/sunpy/streamtracer)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
