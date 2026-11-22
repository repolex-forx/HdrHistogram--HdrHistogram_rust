# Repolex Knowledge Graph of HdrHistogram/HdrHistogram_rust

RDF knowledge graph data for [HdrHistogram/HdrHistogram_rust](https://github.com/HdrHistogram/HdrHistogram_rust), parsed by [repolex](https://repolex.ai).

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
rlex download HdrHistogram/HdrHistogram_rust
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 199643836b0c68a9d90d904cc3feb96b8c6e87ce
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 199643836b0c68a9d90d904cc3feb96b8c6e87ce.nq.gz
│   └── repolex
│       └── 199643836b0c68a9d90d904cc3feb96b8c6e87ce
│           └── chunk-001.nq.gz
├── blob
│   ├── 05cea4ce2d93b2e22830a1a434e0c3d6f94f124f.nq.gz
│   ├── 096b4b5117084063cea81b372d77cbdc62f90ba6.nq.gz
│   ├── 0ad6e1e00b56f92c6c731393381a0f8fb23fdb06.nq.gz
│   ├── 11758a030f13d3d243d27afaebb2ddfa2ae5ead3.nq.gz
│   ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
│   ├── 189d4d5ec3d2ef66bded00e95cd6308c0820c3f6.nq.gz
│   ├── 1a9d57108897553851098d03c393757a12e2702c.nq.gz
│   ├── 1c75138cd2d1a86d8d9615ecddaefc6573285f02.nq.gz
│   ├── 23b579acb073da37f0c5bdb54659ec30bc323237.nq.gz
│   ├── 259e15e519ddda2a1ab1b4084624ba86080da30b.nq.gz
│   ├── 2fb733c7c9c02b60c925bb38576d10739788a036.nq.gz
│   ├── 30e44c264b336b0c1d50117bd3eb2686eccff2e6.nq.gz
│   ├── 4131eea0eb5f072c554acfba8bd511fc40d437ea.nq.gz
│   ├── 44e29a6d2d34d06c73faad78cad46c7bd41e15fa.nq.gz
│   ├── 45548d67580f2ef1982b64b83555d8cc1ac04b3d.nq.gz
│   ├── 476a3c42feb49c4262348ae27466bc00a096d217.nq.gz
│   ├── 520f41dc75ff2d6b81e8113deaf6f500dd31dee7.nq.gz
│   ├── 60565f0314cf7955ec254477179db338735fec2d.nq.gz
│   ├── 66e9bef0237892e5f7229d0abac10ee06f753fdb.nq.gz
│   ├── 7052cf12c815585d50bcdc9bf94bd474e9bbd200.nq.gz
│   ├── 72fb0445968e880794f3e412ffe98aa5270e219b.nq.gz
│   ├── 7a704edea5ef21ed3b3abac8303ee389e5bce73a.nq.gz
│   ├── 7c3c37042c90d16e02833ee78108634253ea3b23.nq.gz
│   ├── 8361f1822fa79fe31f89232501d7c2d19688b44c.nq.gz
│   ├── 8562e488c42d31ca82bc0f312b78a27a3ec376b7.nq.gz
│   ├── 897d39689f3cc159b98d276660e9b115aca7670e.nq.gz
│   ├── 8a2200e878dc8574b5f3c72293d63cc5cb0ccaef.nq.gz
│   ├── 8bdb42207fbb73cd7eba19d6955f5192a93360f9.nq.gz
│   ├── 92e8e4627e8493cf7249d07b33d054ff3df65a79.nq.gz
│   ├── 95090d87810097a6b7ae38fd952f9dfa6e1434b5.nq.gz
│   ├── 9a423ac5727fff4bd60c54b90532eb003aa99973.nq.gz
│   ├── 9cf2f421fc76d3acf592da2cb5781a6c99eb3760.nq.gz
│   ├── 9edb556d3465cd159610d600fc4feab438d33cc7.nq.gz
│   ├── 9fedbe0d518d199b46c7f28a32e446ebf4773f87.nq.gz
│   ├── a1f1f4de9474bfab6ff9b1752d09daeb95e60e07.nq.gz
│   ├── a41476083632dc530557866ee9124cd5f27c9244.nq.gz
│   ├── aad1bc9bf59e7c3b07fa6a452a0bded3be2e45fd.nq.gz
│   ├── b257d5c595854cc7d3a46ceb11da630a1632f956.nq.gz
│   ├── b2b802da71079e97d213d3825a799cbd1805b0c4.nq.gz
│   ├── b2d9fb6ecf9cbc6c0e75b14007dcd9d55b5218c6.nq.gz
│   ├── b357d50589367a49e2d874cb0d1f15b3f33c4ae8.nq.gz
│   ├── b67559183eae9872e6d97d47fc0d51173422a169.nq.gz
│   ├── b853acb64892353929736965810f90268427a205.nq.gz
│   ├── c11d24fd1b03ee88a47f0b1ec7b13cca14a1fc81.nq.gz
│   ├── c14b11192e90bac4e822f140ce5836722965bbc1.nq.gz
│   ├── c259e301a9dc73ef5cc90a05ad3b497be4a0298d.nq.gz
│   ├── c67583d6e7dcb68ef9ca73d7f980c2ed0ad7dee4.nq.gz
│   ├── cbcd7628381513579cd124b92e719ba2a0eb031a.nq.gz
│   ├── cd5ce8fc15e9de5579b178249e6950c38ba6ebe4.nq.gz
│   ├── ce3f2fccc24076c9a72664dd33a000fa15c26f42.nq.gz
│   ├── d254ed87b8f2a7b8f25514c7ca934aab6d3aa34e.nq.gz
│   ├── dd7b85c4c3a0916fefc8dd3d8698b3c93d240127.nq.gz
│   ├── e932784c7507d16bca92e783cf021d0e481bc8d9.nq.gz
│   ├── ee50e1c31ec277368193841f5de1aa7079be6424.nq.gz
│   ├── f06b1c93bafb3cdc13248318988f1da234cf5917.nq.gz
│   ├── f6ac1dfe2acdc123eb7c960d54e41b9a06691571.nq.gz
│   ├── fa4d1bdaf70a0d975de18136671513a2581c2a38.nq.gz
│   ├── fb4087b4df9c059eda0ce640c558ad45da443f77.nq.gz
│   └── fbf1758fc24ebcc3301cc9382f0dd3b1ca7b594e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 199643836b0c68a9d90d904cc3feb96b8c6e87ce.nq.gz
├── filetree
│   └── 199643836b0c68a9d90d904cc3feb96b8c6e87ce.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 69 files
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

[HdrHistogram/HdrHistogram_rust](https://github.com/HdrHistogram/HdrHistogram_rust)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
