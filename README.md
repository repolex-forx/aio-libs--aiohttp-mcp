# Repolex Knowledge Graph of aio-libs/aiohttp-mcp

RDF knowledge graph data for [aio-libs/aiohttp-mcp](https://github.com/aio-libs/aiohttp-mcp), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/aiohttp-mcp
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9783c7bb7b9113c64110ff003138dc0251d06d84
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9783c7bb7b9113c64110ff003138dc0251d06d84
│           └── chunk-001.nq.gz
├── blob
│   ├── 02bc5c4ba4c18c625dee125a88e58e6e07c41956.nq.gz
│   ├── 192e8db559bbbd535b9fa7418cea17dc5ac9aea2.nq.gz
│   ├── 19d8e60d050c214c0592800ac59b3ac4b85bfa12.nq.gz
│   ├── 1a99952726d5d30f0797152d110390f8cde2e13b.nq.gz
│   ├── 2072df9d39185f07915314862c07978735a7c088.nq.gz
│   ├── 25f72799ed0d344b83922b4a590bf2fe3bd1090e.nq.gz
│   ├── 2f5f80b9a32d757246b862c259fd1d65764e5528.nq.gz
│   ├── 2f65153b29343f04f4b79f96852b99c4961253a9.nq.gz
│   ├── 320fd6e5c178f148463d4a38b60bc86f54e935da.nq.gz
│   ├── 36979982708b367032730848375b2a457cf360b8.nq.gz
│   ├── 373108131c80528a9123a3bd88c09d8ff029a8f0.nq.gz
│   ├── 392da5720c17596f517c40fbd4e03cbf98bf9883.nq.gz
│   ├── 3d20e7ce6d5529e427c3e025b24f7fd340d52ab4.nq.gz
│   ├── 3e7f5511f31498ecf3bdb6e2f2f674c8cdbada01.nq.gz
│   ├── 3f0ed21ffa290fbefd65707e6e876f25666c72df.nq.gz
│   ├── 3f62510d85cb219333e991fdd11c56fdc1d441b1.nq.gz
│   ├── 4574f34fa30a5c684089dfc8a163b012ef1a8a1a.nq.gz
│   ├── 4aea38b28edbbc1a1f9f5eeb1089e0ebe7f890f4.nq.gz
│   ├── 4b138fac98ba7fd44fb5faf34f9dc0d56a8908b2.nq.gz
│   ├── 4b790e815f8533359009aacb900e5d88c0623349.nq.gz
│   ├── 4ee2138838ae2e0921901d86cdbf15de7086a2ac.nq.gz
│   ├── 515c88a45760e5ef7c434c2fc2b8d6f51b309193.nq.gz
│   ├── 536eb0e97f590eff3e84cec312a1665dccd430ce.nq.gz
│   ├── 54b1f30f99ff9df8e47907eebdd944589dd8d861.nq.gz
│   ├── 56a32039c897c790fec7651bbf07f8091630078c.nq.gz
│   ├── 58dd30ca07c4fdae62862de1193f1247d2c20bcd.nq.gz
│   ├── 59cd8de29f155db62553eecfd6b6eb317434a98d.nq.gz
│   ├── 5b57456c95809350a52515e7607bec12be8e356d.nq.gz
│   ├── 5b73e469f0ab5a123a4036a91fd88f8344562d7f.nq.gz
│   ├── 5cbde0e7c5af551ea3650885cca9f0f58ecc780d.nq.gz
│   ├── 602019f04d8f8c6b50b4dda0d3865adf88803f3b.nq.gz
│   ├── 6a8dca06fb916441226de2082f9619aec68f409d.nq.gz
│   ├── 6bf055f8aecf988299e6cbc549ba110f63a55557.nq.gz
│   ├── 7007b9ebdbcdcd88d20c110861c9680f4c6bca9a.nq.gz
│   ├── 7231ff158be16e3b7812d53f24b30b94c77f2354.nq.gz
│   ├── 7aa64f15a7676fcb3a5d00ea8017d3e232500924.nq.gz
│   ├── 86eb9efb81a95c634859d1c0cea96430cba12d9c.nq.gz
│   ├── 888dd151a3803005ff33d75ab6cf0cf714a2e5d1.nq.gz
│   ├── 8a5f813b1e2d3191facf1a28c954b20330c65db6.nq.gz
│   ├── 8c17b24bccf983b8a8d6785af4c7f806c65806dd.nq.gz
│   ├── 8d97a89f010b3477b1a2942524eb6f38f2885b63.nq.gz
│   ├── 8ef3e616be0e70e482b941ae16db3789e1f9ecb4.nq.gz
│   ├── 913bfcef18d6fea66006cf173699501b3d7b7039.nq.gz
│   ├── 9f08f1c7de818044b20f1e9493ecf852b60fd5fa.nq.gz
│   ├── a0c0654e6b328638925a060510eaaa2407cfbaa9.nq.gz
│   ├── abac2ced49785027ec39c37e94763c0153868a6e.nq.gz
│   ├── abafe726f464e15d290476054e03b7ad7d042336.nq.gz
│   ├── ac20735c360ce38de4b7ea709b06102154bce315.nq.gz
│   ├── b1fd35cfba69307a09520ab44df17ccf2d8edbe2.nq.gz
│   ├── b339c17506f41f0977d53f0bd09d19e193cf7bdd.nq.gz
│   ├── b95f42f6dbade959f49e7f4038e7366c5f180482.nq.gz
│   ├── b9fb8a6e0f4a5ce99899eb97d872c6b90f4bb678.nq.gz
│   ├── ba2f3fc0f682f2e93919c71927bc8467c74c5328.nq.gz
│   ├── bbce2a82bdcb9b4e76a08d9b01557f991e6ddbe2.nq.gz
│   ├── be519e473268e29c33c3155c82a3161fc56d66c0.nq.gz
│   ├── bf3345081622974952b52ba17428806206992abd.nq.gz
│   ├── c2cef132156445bdd029a9f47c3df0c64353b997.nq.gz
│   ├── cd78b2abc98268848f333404973730d97497ebfe.nq.gz
│   ├── d1c51aebb7506ac19aed6bbcc45fc964335f884e.nq.gz
│   ├── d2eccd766445cebcf09f42080858e2055a43ae7c.nq.gz
│   ├── d7212bf5fda5d6d9d37a4fba7118e52cde5f9984.nq.gz
│   ├── dbc5970d545f7ceeeee2424910568b35aec00e51.nq.gz
│   ├── dc6b53aad3a0166253f1eb674828bf437f234478.nq.gz
│   ├── de2a55828d1437caeeb35cf19659d18fd2ddef39.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e91a0a49f5c461d3eb0eb5334860cc1e47d47f93.nq.gz
│   ├── edd5f90b9aa0a31194de62b2c6d9e6fafa03a2e2.nq.gz
│   ├── f743538c24ebe572011b19a9f7801d45f6290350.nq.gz
│   ├── fa3572c91f5b6524b5bc10995b7299dd77b8d8fe.nq.gz
│   └── ff4a91c1fd065ce9367c4af86f5570cdbb83c97b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9783c7bb7b9113c64110ff003138dc0251d06d84.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 78 files
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

[aio-libs/aiohttp-mcp](https://github.com/aio-libs/aiohttp-mcp)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
