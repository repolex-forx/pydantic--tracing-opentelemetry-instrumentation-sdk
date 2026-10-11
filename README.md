# Repolex Knowledge Graph of pydantic/tracing-opentelemetry-instrumentation-sdk

RDF knowledge graph data for [pydantic/tracing-opentelemetry-instrumentation-sdk](https://github.com/pydantic/tracing-opentelemetry-instrumentation-sdk), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/tracing-opentelemetry-instrumentation-sdk
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 08ef24d98cbc76d5934d9ba65fadf6d5bc4bc91b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 08ef24d98cbc76d5934d9ba65fadf6d5bc4bc91b
│           └── chunk-001.nq.gz
├── blob
│   ├── 002dfc52d12b5e71668d54ca2833b453b1d942d6.nq.gz
│   ├── 00cf9b558855f5fe6939ad859200722a1da766af.nq.gz
│   ├── 0193dee3606763df59d8072001eff02569907535.nq.gz
│   ├── 034ab4d61ac51fb3a9fe618e3a20a88f85251510.nq.gz
│   ├── 03dee1286f8985511869da2632e75eb199681481.nq.gz
│   ├── 055580765fc8c6c48463a7aa89ab429206ee0558.nq.gz
│   ├── 0892ad71ea23a101dd474b5d71898c7cb222bb5a.nq.gz
│   ├── 090e2959ef5fe0e8053c4745220999e8042e4631.nq.gz
│   ├── 0aba7c5d6d30320683da816a4a811da5073627b3.nq.gz
│   ├── 0b8ffde79e34fb4d4925414032a836952e2ba659.nq.gz
│   ├── 0e259d42c996742e9e3cba14c677129b2c1b6311.nq.gz
│   ├── 10bf1a29c2eabc43b3b38e43cab15db55f566c3f.nq.gz
│   ├── 1111506743b0feeb4e677a7557727ac36e9f9e40.nq.gz
│   ├── 1152be61b3533e88b7a1f7ea13bdd2bf8594dd10.nq.gz
│   ├── 1906a9737f011b530fcca02b6f43866f3719f57d.nq.gz
│   ├── 19fd82ed076fd7bda6e801141a06a2a3bc3c56de.nq.gz
│   ├── 1eba7f0549e20d7fe09fe2a0fe75b49ca030986e.nq.gz
│   ├── 206e82ce8672230b00dbeecab7e14ca1b8d143f4.nq.gz
│   ├── 259779ab3e0c910fec94279123641eaba55b9c0b.nq.gz
│   ├── 27d17025b9da7e86b93673aa3025128f65142a03.nq.gz
│   ├── 27f413320488f27a3bfb64a89b8ef1dcf0ae0216.nq.gz
│   ├── 29860c18454f07c2e775a95ae1a1438fe1243104.nq.gz
│   ├── 299aaddfea15b6be74f89d97b7d68fb46f86e6e9.nq.gz
│   ├── 2cc2e215586ffccc8585ec8d86b248571f8b9170.nq.gz
│   ├── 2faecdb14dbadef6a2d7933e6a998a494fadb155.nq.gz
│   ├── 3023cbfa5f3c74c8cc7eeeb9b107b24c56ca1a9b.nq.gz
│   ├── 3044715c87884dd929f6b4b14aefbcb63a7064ca.nq.gz
│   ├── 332b5fcda08ef8214a77a2f0aa10f2442a770082.nq.gz
│   ├── 332e5744fe47a5cd87abdb307927df46be5784ce.nq.gz
│   ├── 375b0f2b95444715a82fed0e58b94b31bed31d14.nq.gz
│   ├── 3a919d7b7d37e85d80920db43e7d6ef591723b39.nq.gz
│   ├── 3d264595c1f6385f1f52393b42abecd239c5632f.nq.gz
│   ├── 3fff95c8b9237ed3de0736c7dec726a060712bfa.nq.gz
│   ├── 40984fbc3f402899c5238c7fb8815566861c0819.nq.gz
│   ├── 43bfad12c372895adf4091809e9ab3fc2b032d8a.nq.gz
│   ├── 440ff3ab621705e3e9419f0231ad13d97ff6189f.nq.gz
│   ├── 4457bcfff1e57b419189462afc77bc04655790ae.nq.gz
│   ├── 45cd10cd0ae948b6cb485191e535d92a61b3290b.nq.gz
│   ├── 46b2e745c731a8619f8cb89316992aa4ef785901.nq.gz
│   ├── 47dd582ccdf70070e71f0f994f75d96dc30eb0d8.nq.gz
│   ├── 4a0c26e2c05866fa188277eb51975dedde3b7c3e.nq.gz
│   ├── 4bd8e24c2cfd7b6315e03655b75789a43a7ec814.nq.gz
│   ├── 4d1e26ceeb5f8d93720fb1a6dfb71f6ee71b538b.nq.gz
│   ├── 4f3ed9583713be7c07cd0a4a3ff764d7bd4a082a.nq.gz
│   ├── 58f273a578ddbb4d5c0de3bab4ccfb1ce4104ced.nq.gz
│   ├── 5c08e795d69e25123a101bd14ac3be352570f2f3.nq.gz
│   ├── 5dfe2ba567c8c123e57bbb8799cdc19fc3f7a389.nq.gz
│   ├── 64b98a23a6b9874fe09439e0996ed69c25859bfd.nq.gz
│   ├── 69b182448ca2c20ef1a1bb4604d76028a6112968.nq.gz
│   ├── 6be2cb39f53c0d8d28942a3de291ddb848b414cc.nq.gz
│   ├── 70271e3d77ad4ea3f78ad736e28e284fec7f7fca.nq.gz
│   ├── 7221b30b0caa3872fa36baccdb64543179c0b0e6.nq.gz
│   ├── 727c955620b96a7dc63b9b9c04c75da93c78575f.nq.gz
│   ├── 7491742a4026a1124cab9520dc321b74cbba1d4f.nq.gz
│   ├── 752d1757474bca314bd80b49195e0e75d04d86eb.nq.gz
│   ├── 76ac917d98be7486874f925d216b1d8bfca639b7.nq.gz
│   ├── 7c13750f2f63c31fa7b435eb8ecfcaa36f8f1feb.nq.gz
│   ├── 85776a962ba5b52274493ff20777771853f7c94b.nq.gz
│   ├── 8613b02e463b833d6b2785e0fc8b2911e6de18bc.nq.gz
│   ├── 867090455cf32a36578c1f59ab4c76c53e0483b0.nq.gz
│   ├── 88d06336ee1f60be216796adce33f8f11e3ca29c.nq.gz
│   ├── 896cb2e92f208b11f834195d14ae3eeee6282aa4.nq.gz
│   ├── 89fbda81bb0575b0e19030144fe3d4f3dddbf534.nq.gz
│   ├── 8a65a8422ed5c4d0ecd6c36611dfc8607948a140.nq.gz
│   ├── 8a948d874dc264d7a3082ccfd12c61ee252b0d47.nq.gz
│   ├── 8ac6ebd488f7d36dca64587faaf0b01c4ecf0b1d.nq.gz
│   ├── 8cb344d8bad920bcafdeae488e67752ec6d2b93f.nq.gz
│   ├── 8f411f9f6b5b6f521bac13337d04192ede4469e6.nq.gz
│   ├── 92b9e7d679ff2943f59f7536e3d41396b603c94f.nq.gz
│   ├── 92d4e32f5b8ea84b7b21a6cfa744fe22104ae867.nq.gz
│   ├── 946920e1e0b85c6d59af3e97a9def6993707470f.nq.gz
│   ├── 95cd05b81e904528089a821bfbd7175e70114f03.nq.gz
│   ├── 9609c67ae838aeb6c863ba0ec875bdb6c236d2b0.nq.gz
│   ├── 97a110f992b5a2c9803b62934ce9606de5174d9f.nq.gz
│   ├── 9a76f9bcb6b9bc9d215b1e4a3d6d4d2abf428224.nq.gz
│   ├── 9fb297d41945d3724a48e98c983a881cf37764a3.nq.gz
│   ├── a40c9a996b3245010284e3f25a747387b71a937f.nq.gz
│   ├── a422f4295bda1352c7be1a22f38a64bc01714f68.nq.gz
│   ├── a69723d912dd7a21a8566ad29a21364765c78a37.nq.gz
│   ├── a8aa83d17df10a2393600a9eacb65c090704c7a6.nq.gz
│   ├── a9cd4040b5132cd5983a19c7e62787e194a4fb69.nq.gz
│   ├── aa68b7e92af78d44137a3a2a7faab553ccda4833.nq.gz
│   ├── b1fa59da107dd1fe3d1a30cb1c15ad4b98a0a8ee.nq.gz
│   ├── b6c046d5697869c243284a9d4df1138516ae2204.nq.gz
│   ├── b6df74b3065290b85bfa81555a9c6da6a0961c0e.nq.gz
│   ├── b7460aa6af4062ab6a26bd5581809783ff27fc67.nq.gz
│   ├── bb42ffa48fbd27c85af0fe10988b8bb27d19b502.nq.gz
│   ├── bf7d3b23dbe8f3ad63ef7d6e6d346f08e9f1154b.nq.gz
│   ├── bff29e6e175be9b05a768e79e9b28724ff22878f.nq.gz
│   ├── c36dc23028a65d81fdf0bdf14108570cf50c08e5.nq.gz
│   ├── c921227bdee96932d19d8c577f24d153aac4978e.nq.gz
│   ├── cb123226348d603def1f7222e18b2acce58b616f.nq.gz
│   ├── d08b7292a2af609b62e654d88ba1fc5ff978ecd9.nq.gz
│   ├── d7a94bfed6049fd3150368b2c2c45fdab1e7dd58.nq.gz
│   ├── d85df245c86725df92eb924fee961d3c5832eff2.nq.gz
│   ├── dacb97e38c581c7698d45b88d478269155907397.nq.gz
│   ├── dbfc482ed0955ef4c63ce3c79d53b013287c5def.nq.gz
│   ├── dc6cff9f6c277d34203ffc7e73d45163fba1fc96.nq.gz
│   ├── ddb8be47f195704a4f67f48ddaff7b3f30fe2bc2.nq.gz
│   ├── e189906bbacb4b3d7fad7a08b2356748d3f2d195.nq.gz
│   ├── e68370238fe0c1ab5c03cbf6e68f7d74ec3626e5.nq.gz
│   ├── e983807265db576bbe578c7eedf294665a8768c7.nq.gz
│   ├── ed2b0b31d825775f104984c9f994a122f8f76fe0.nq.gz
│   ├── ee3ca15981a4661e2e117b8f5ebfee603d0aed85.nq.gz
│   ├── f11fc7c5a6402fe16f0ac5f8a24341ba80086c6d.nq.gz
│   ├── f51c66068a7d7e6b5a78718ecb10f6c6de8586e8.nq.gz
│   ├── f6a2fb07ae83ae49f644177e8466f5583da9245d.nq.gz
│   ├── f7076ec5eda71e57d16ed8258e2d289477a96037.nq.gz
│   ├── fc92b058686f29b95389bb9dd03e3cd74835bcb8.nq.gz
│   ├── fdfdb1bcf84c4a3736534059f4948b3259c74017.nq.gz
│   └── fea01ec99fd7279cef6d2c228af7713e17ffeca6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 08ef24d98cbc76d5934d9ba65fadf6d5bc4bc91b.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 117 files
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

[pydantic/tracing-opentelemetry-instrumentation-sdk](https://github.com/pydantic/tracing-opentelemetry-instrumentation-sdk)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
