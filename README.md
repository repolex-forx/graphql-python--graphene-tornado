# Repolex Knowledge Graph of graphql-python/graphene-tornado

RDF knowledge graph data for [graphql-python/graphene-tornado](https://github.com/graphql-python/graphene-tornado), parsed by [repolex](https://repolex.ai).

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
rlex download graphql-python/graphene-tornado
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e4fa7d7b4c2256fa37f5ad89cbfd4d4bf6fdb606
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e4fa7d7b4c2256fa37f5ad89cbfd4d4bf6fdb606
│           └── chunk-001.nq.gz
├── blob
│   ├── 03da99398bcb069a19328257ed7131187cb2493a.nq.gz
│   ├── 05603868e8eddd9a4e208f679e2bd93a86cef307.nq.gz
│   ├── 05dbc977e6fcf99c18d4d6ab9e2376db74cea401.nq.gz
│   ├── 0968fdb4dffe6169322138b2ed5a2d5a3793ff7d.nq.gz
│   ├── 0fae50475083265e30489116ba71bc5ea2b8c376.nq.gz
│   ├── 121a49d8c66efc380e4e673b38ac1881be844b5c.nq.gz
│   ├── 132c96863bc693d2f04e20195b26a854a555ac4d.nq.gz
│   ├── 246f2d56994bad4d39c21dcdc8a09ce18c509022.nq.gz
│   ├── 2603afdf14103b66384e4d375299256abe4550bf.nq.gz
│   ├── 263d314e37cb5c2eea3ebacf48639c1ef643d774.nq.gz
│   ├── 27fc677729e0fe4953b4b90aab95dea6a1b26691.nq.gz
│   ├── 321e5ca09d0fec5a6ef31f33007b48e5b9491a93.nq.gz
│   ├── 389a5a6374156825069b669209718575f0bfd22b.nq.gz
│   ├── 3a563715ff4be57fb856072b0789b7952183a224.nq.gz
│   ├── 3cb3770d325de09a8ce8764f09ade0c9dcfbc9e0.nq.gz
│   ├── 4b7e1a0848bc90c2da7b8ee394d9fb35c7c68ff4.nq.gz
│   ├── 51542c4e0ad18586394d9991f2e34ef70d672d34.nq.gz
│   ├── 518f3c1e5a8199d870f8b66c5958bae61ad4650f.nq.gz
│   ├── 55cb2b39c93589e31794fb529bcbb9499ceb7358.nq.gz
│   ├── 55cb2c105d395e74d3b98695001961d4bdaeda00.nq.gz
│   ├── 56b2800d9b4e53b60428dcf610708fad2357d0fb.nq.gz
│   ├── 64ad321dfff2eb592df2776b35a1cf9131f44f1c.nq.gz
│   ├── 7b2a5ea693ba9bdd33aa5b41915ce33a2d137a47.nq.gz
│   ├── 7e40cdec7d725ebfe9f33896caab68c96ff2c3d3.nq.gz
│   ├── 868d01e83bcdb456d60aa2763351b5955cffec76.nq.gz
│   ├── 8b05a3b7d587f95492a13bd47e0dfead9cc128d2.nq.gz
│   ├── 91a781cc69a511c4158e7736f2d394d6ab572ebc.nq.gz
│   ├── 9cc136a196ee55a22204796106a7d77f67eadfd3.nq.gz
│   ├── a48afeb9da3204bb47c956475d30038d4eb75958.nq.gz
│   ├── b4a4b7012583d3f6c27e73c5ba0c7b91b4eb3112.nq.gz
│   ├── b5aaec43219bf92a99d9227abf69c4d37ea854aa.nq.gz
│   ├── b677466aaa18fbeb8567cad04009ec68788a3b86.nq.gz
│   ├── b70306ec12ad5c9ec11480680bdaa27ce8ab20e3.nq.gz
│   ├── b88f6522e1c3f9310b30fc6eb9246ecd280335b2.nq.gz
│   ├── ba3e12fd943f78c2750fa3f83d9a4a8c1fbf4331.nq.gz
│   ├── bd5a8daf562d28de5879272dde96318b0c10e81a.nq.gz
│   ├── bf4459d02c1823e509b1ef3499fabfbdeb45a088.nq.gz
│   ├── cac6ea9d4586c24d811f212d3c5c4d22a5bacd05.nq.gz
│   ├── cd21b453b3502525d06c90e4432d21f0fe83082d.nq.gz
│   ├── ce8ea2030aaff46e32ec94ec70a3083c65555f54.nq.gz
│   ├── d478050e718d8d3e42a5f4a9ce83c2d8d0d0dd1d.nq.gz
│   ├── d750d99f5a46540c1228c6386a555e8c5d3b0a40.nq.gz
│   ├── ddd13f365bd4cfe97621cfdb9bb556eb391fc186.nq.gz
│   ├── e034d0c8d8769aea30abeb9d992c1230a1849005.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eca06baba49c0125367b6588bc747852fbb5a003.nq.gz
│   ├── ef8b90efa729d33d40116ab46705e18e423997fa.nq.gz
│   ├── f17939e748b9f0b60582d3b4f5da3f5cc07d15fe.nq.gz
│   ├── fea8034bd9d44e69e5259243f1309fee4eb561c7.nq.gz
│   └── ff1b37c25e7b5ab180af8ad7c0a5fef12a96aad5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e4fa7d7b4c2256fa37f5ad89cbfd4d4bf6fdb606.nq.gz
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

[graphql-python/graphene-tornado](https://github.com/graphql-python/graphene-tornado)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
