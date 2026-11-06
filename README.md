# Repolex Knowledge Graph of zopefoundation/zope.testing

RDF knowledge graph data for [zopefoundation/zope.testing](https://github.com/zopefoundation/zope.testing), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/zope.testing
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 66b408d90c4db50b505eb1e25c443c9813874cee
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 66b408d90c4db50b505eb1e25c443c9813874cee
│           └── chunk-001.nq.gz
├── blob
│   ├── 0824061bcd876eec43fadccc8126d086a7bf8683.nq.gz
│   ├── 087ab07af700e78f47850c7d857f1f1fad49d7a8.nq.gz
│   ├── 0f532bbe0e91c0e7723bb4a5caa28638a0e3c791.nq.gz
│   ├── 10cebbbce57b14facc6cba920808bc6402fc4336.nq.gz
│   ├── 18de3b9f67d03d6f0dce41edfc940bff98c07bf7.nq.gz
│   ├── 1ba319c8c0ccbc3ebf6a4071670fe15ca427e02d.nq.gz
│   ├── 233aee9cc74f4b3fc7884ded5a200411cb286fc0.nq.gz
│   ├── 2839fd53ea911e5734bea2a991d4e71e93aa14c6.nq.gz
│   ├── 33da03d565cb2d049a1d34c7d1859c6826b0d5b2.nq.gz
│   ├── 394044efa82fac238fe2d5a5b00d9f52e12e6656.nq.gz
│   ├── 3a14f329045629a21ffaed89f3098fdd5f651156.nq.gz
│   ├── 43ddcd77930a0268c267804569b6269fec3bcd75.nq.gz
│   ├── 4fcc74cf38deee296f6d14e74cc793aae6e7e127.nq.gz
│   ├── 5186624798ba46e8b24a57cc042a84fbdc009a1f.nq.gz
│   ├── 555b526dd9d2d1edc5cd1daadea82156ddb089c7.nq.gz
│   ├── 5ce1024a2d96856f260554f4b484620a9923b017.nq.gz
│   ├── 607136fe7eb60eb0f5675fb4255a9a20f7545df9.nq.gz
│   ├── 6773ba162d626d224b5da93e24639c800a3e1576.nq.gz
│   ├── 6b175eef31071ac9d9e8e98703e5f00fba0ff0fe.nq.gz
│   ├── 6bddc8adaf941a87ef9aa2acae3bd04606d8765d.nq.gz
│   ├── 6d37aad62fbc64e15399574822b2c1859bbe0e4a.nq.gz
│   ├── 744e249829ad498cb4906fb95e1bca9b129d0b76.nq.gz
│   ├── 793adfd5d8e13b54e9a5bdf564b471beb6148d09.nq.gz
│   ├── 7a212982f9012b2c6e643ee1bcd8db95168da326.nq.gz
│   ├── 7c7de3d71b92bb9aee293c28e8cb0ffa3aee72ad.nq.gz
│   ├── 7f80bc5d14ced13a4cd68c7b7442c80fd3d96aed.nq.gz
│   ├── 89f4e9d9d2c969ce0d5f3da921d7cd754b2462b2.nq.gz
│   ├── 8cc3cb9af04e166c9df585905d2b0dc14d7a0743.nq.gz
│   ├── 90df8c21a252bea8708871c5e6ee04a79ada385d.nq.gz
│   ├── 93515e6f85366dcf876fe735a11490dc99b0a971.nq.gz
│   ├── a70575bf5153a4623c02d8411588a46a0054a183.nq.gz
│   ├── a75b90e5ba8e30c89fd2e451f3ab9c8792497481.nq.gz
│   ├── a812d1906d6ed5fecf8df562774c1947ec8999ff.nq.gz
│   ├── aeba0aa0a6e41f8466301f39ffda96fd16120944.nq.gz
│   ├── b315dbd628d99de6e1e4a33d1a62118660ebd483.nq.gz
│   ├── b81e15edf21824f7c83360759fb8a7a46cf04f88.nq.gz
│   ├── b8581dd898cbb33e63961b4d181ff0ffbe5d03ee.nq.gz
│   ├── b9ed0a7dc8b7794f05873af93b27c9c5a6a8a90e.nq.gz
│   ├── ca517f4eb0cec1c691c0c2b54cd5eb85e906f11b.nq.gz
│   ├── cdaff84736755cf1d38973a6debda4376f7925eb.nq.gz
│   ├── cf080834d8696765c0e806f23d0705f58e9fa950.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── dcdb04d881145e0435f326597c9ede79fd3e9886.nq.gz
│   ├── e0f36172a17f3b60107c6b6ccd20c94f8c7253d8.nq.gz
│   ├── e184fd8f41cbc229060cf69967d916bf6e2ddf2a.nq.gz
│   ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
│   ├── e336092b52689b1fb6b2049e6edb0b1455b0fc42.nq.gz
│   ├── e4b867329e05886a4818f86b117fca2102bc84bf.nq.gz
│   ├── e9c9ff70a18f32fcbb72b3822dd1f29b7f47a535.nq.gz
│   ├── ebf54dc8f022bcf51a9f75e74a7ae56a115c630f.nq.gz
│   ├── ed2311b853ea713291dbfecba6869e9acda1e50b.nq.gz
│   ├── f24df1cd34d152b08d9e7a781086be9882eb372f.nq.gz
│   ├── f507feda73c43de02c9268ef502bc4c3a2ebf32d.nq.gz
│   ├── f81cabf053fb4487bb3496afbc276556076bc3f2.nq.gz
│   └── fc902591f2e96a95cb62a31f68ad9ba059cc322f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 66b408d90c4db50b505eb1e25c443c9813874cee.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 63 files
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

[zopefoundation/zope.testing](https://github.com/zopefoundation/zope.testing)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
