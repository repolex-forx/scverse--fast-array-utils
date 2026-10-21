# Repolex Knowledge Graph of scverse/fast-array-utils

RDF knowledge graph data for [scverse/fast-array-utils](https://github.com/scverse/fast-array-utils), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/fast-array-utils
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dce1f85e9d431e9013eb811a0fa58c1185022f2e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dce1f85e9d431e9013eb811a0fa58c1185022f2e
│           └── chunk-001.nq.gz
├── blob
│   ├── 0007725f342ac99e5b4e0747e196e0fbab42eb11.nq.gz
│   ├── 06603568492cf001494def177a578b7912847833.nq.gz
│   ├── 06e994558d7e698d71bf35990932d631f120ef8e.nq.gz
│   ├── 07276e9efde81d42163c67c17d6e4027dfafdf23.nq.gz
│   ├── 07c8b086343715a7162a77c14c7d5c5850cc9bbc.nq.gz
│   ├── 0a19cc0c8304224a4b51628d010efe90357f4c7a.nq.gz
│   ├── 0b17228c665ff899a9625d19926c612d1e8ef044.nq.gz
│   ├── 0e8daa30ec9c68d59a897281d22a5c499817df61.nq.gz
│   ├── 0fd9346d05499cc3a36d74498bc673ca25c315e3.nq.gz
│   ├── 1559667d05bb64e6aabfaae57ed071c52d22bd02.nq.gz
│   ├── 17b46deecc823b08f01db6dfe7262d16e5f97aa4.nq.gz
│   ├── 1be412951fa0a64e6841c2a99a6690d9fc8502df.nq.gz
│   ├── 22f3bba36ac61c2346706fb7f1c01ebf7a56a8d1.nq.gz
│   ├── 29951810701e399840c3302a3de60c303685c6f1.nq.gz
│   ├── 2a98e939738ab29173d0c57b020147c15cb2f215.nq.gz
│   ├── 2b8d5078ecd309bc8e6000e725ab807d4fed3beb.nq.gz
│   ├── 2c75ba4242ad16a7735a844717ed818ecd7f801e.nq.gz
│   ├── 318181a9535f385b28fd092c2b4198f70f99ee9a.nq.gz
│   ├── 328439a6f94fcfaef63650350eed07dc6a8516e3.nq.gz
│   ├── 33a894a1ad39b8158641414f57fb4b73f80c742d.nq.gz
│   ├── 38b7cc50a960645008e17dcf8c3a0e301062240d.nq.gz
│   ├── 38df35bf9834ca95ed2428a75d747f4258f80f66.nq.gz
│   ├── 39d03d3e0394fbe20fb2cb82af8d8a50f331fae7.nq.gz
│   ├── 3abd04d3d1fdb9b9190df5deeff0a2166b748b0c.nq.gz
│   ├── 3b797985edf285fffa255df9a7d6c621f40c283f.nq.gz
│   ├── 420daa42ff4f6f5ec16a486b490610b099cb3068.nq.gz
│   ├── 429018eb3f1c26d6305d55393c26c2d003820919.nq.gz
│   ├── 433609251879b18ea1b3df70c44a85b4a11c8bed.nq.gz
│   ├── 44a7519b5b8c71bd03d78a02dce7f432d94b6276.nq.gz
│   ├── 45a05b7f145486d125dfb42121ee64b17b0b4fbf.nq.gz
│   ├── 4797d7ac828b7a568033c593eec643436053b20c.nq.gz
│   ├── 487762bf0797141af6f1dad3bfaf3e8e416f90e0.nq.gz
│   ├── 4f1035d809b9c44982bc79a892ac5f055dfbf79f.nq.gz
│   ├── 50406f46fe0368a64943226fcd5f2a914ea2ef9b.nq.gz
│   ├── 50c8655564616eeb4097692a1e16207be2a4fcb1.nq.gz
│   ├── 51df2b1846c4d6d3fa896798ca761f85c86b6901.nq.gz
│   ├── 51eb3ccfd5e3c171b369fa14666783b3bd65da8a.nq.gz
│   ├── 595d4991e83bda132e12e69cc5d49906c35757e9.nq.gz
│   ├── 5cfd4391ace2f607cc3e0ba71486b6959e4a41d7.nq.gz
│   ├── 5d260a9cd12176e486d2fe7950f342ef154cdd96.nq.gz
│   ├── 5dc669d607c4931d764fe91c0caf615a3427c59f.nq.gz
│   ├── 5f6119f050333748456820bfff2c39b40173ca06.nq.gz
│   ├── 5fb573027a18b53e0595988d7cde14fa35e7105b.nq.gz
│   ├── 66d4646aefdba3ea7f2d9fcfe3a131277d926849.nq.gz
│   ├── 6775d0044936d69597cccdc1010210c4995310bd.nq.gz
│   ├── 6a169a682e2a3a0a20e5178b0b85e7b0b0032b63.nq.gz
│   ├── 6b8a44beff16e52d4e04e0b80740a2d3d4c9a642.nq.gz
│   ├── 6e93a223b6078e1ece8523da5f5f309e65ccf1bf.nq.gz
│   ├── 72dcb9534530d7cdf536b76645421a138fbbe101.nq.gz
│   ├── 7f0a25a7bc207a6fd2238862ecf583021d1cf891.nq.gz
│   ├── 7f0a46adb9e5367751f24fac656658bb1275a844.nq.gz
│   ├── 80e98eba7818817d385470ae6b5579cb667cf420.nq.gz
│   ├── 840b9c39f9477056ca64192b13b6f496abd99afa.nq.gz
│   ├── 86e2466fafddfd6a8daf3d2274d3c7f8715022ab.nq.gz
│   ├── 873ba7d3f5f6437c7a5f8e2f2a39fa1baea20beb.nq.gz
│   ├── 95b9fba66fe918c8d4146cc72b8b392ef4c4bbbe.nq.gz
│   ├── 99750968c9ba40c347511f2da9e1ff85f74e5f7d.nq.gz
│   ├── 9b4e33925e78478472f30d9547ac6d63f9bcd01a.nq.gz
│   ├── 9b8c8683dd77ffdfb250bb33b12b1ac9217076b0.nq.gz
│   ├── 9fda8302ab1a90744d7e8309c1b11142fef91daa.nq.gz
│   ├── a5084da6ba7a09fc7cd8a4ac0f4051b4e9e9b0dc.nq.gz
│   ├── a528dd585bf73eb04afb2c8c7ee380f836b03d6f.nq.gz
│   ├── a78578a391766ec0d770d5e5f50bcba7ad013ebf.nq.gz
│   ├── aa52f1b9b0065b63242cda324ae3088e4bc57a44.nq.gz
│   ├── aee112c5080508f0fcb16950d30febc3e054d7c0.nq.gz
│   ├── af041b193d617dfe5e1554896a5007e5e6ced617.nq.gz
│   ├── b18a4710729f238d35a6b713292f87b934968100.nq.gz
│   ├── b1ba1abc98db4e9dea81e03d89af805461d1348b.nq.gz
│   ├── bed5cc6a7e19c9e7d9f21f5d166b7dbba3d931bd.nq.gz
│   ├── bf31ec15c69d7a13ab6dbd31ba8027324504114f.nq.gz
│   ├── bfb92bc805cb9fa1ccb31c67c80af1228db278eb.nq.gz
│   ├── c6588f68f4aa84726ed959c9756aafa99f77eb0d.nq.gz
│   ├── ccad661a79120a9d1a107820aba40dd9b4781f12.nq.gz
│   ├── ce1a65a1deffe703592c5b647c1081c61516b500.nq.gz
│   ├── d00ffe236661b8dc8a411fbe10c5c210902ea471.nq.gz
│   ├── d039fa3f08638b238718fcfd86a1d2973d89f14e.nq.gz
│   ├── d389f5cb1ccf50b5f8082ab50b1023e8fe10e0f1.nq.gz
│   ├── d64f1b28a76f7726caceaf8dc6a0c7b83f9c679f.nq.gz
│   ├── d75e04cffcb2fd187dbb707eb5c51e7bc22ccc7c.nq.gz
│   ├── dce5cdd9fa4c0dbfd7c57ef3dbea1c9034dab31b.nq.gz
│   ├── dcf8b0391826043894da5400a6242f5e49722f0d.nq.gz
│   ├── dee11a1008eba2a6ff4f988ff115dab33e9db44e.nq.gz
│   ├── e0925179b67643f263272d7c4d9d98e07d3cbcec.nq.gz
│   ├── e0ebb2fae7bf8f35a51900ab32bbfb09fb4d5de6.nq.gz
│   ├── e67e691629f0940cba4da34f302820305aac9997.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea3ead1449a3e2320201640d09a31ed151546aa6.nq.gz
│   ├── f468508b5b60ebb700f31a3a2af53ca1509753e6.nq.gz
│   ├── f83eae8de13d79cd4e25c3cdcd92f6135ef41664.nq.gz
│   └── fa0dd0756c64a538bf6765e0354105d85624870c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── dce1f85e9d431e9013eb811a0fa58c1185022f2e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 98 files
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

[scverse/fast-array-utils](https://github.com/scverse/fast-array-utils)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
