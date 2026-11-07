# Repolex Knowledge Graph of allenai/asta-plugins

RDF knowledge graph data for [allenai/asta-plugins](https://github.com/allenai/asta-plugins), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/asta-plugins
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b0d41db14b6b63d6a7dc8a132a86a11c8aceac54
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b0d41db14b6b63d6a7dc8a132a86a11c8aceac54
│           └── chunk-001.nq.gz
└── blob
    ├── 047325bad2ae288f2e9c38f5752047d3f06c8884.nq.gz
    ├── 04acd13ecd63953c1eca18b7aec86b0e979a594b.nq.gz
    ├── 05158fe423daee4199ab8d4ddceb2c21bba36558.nq.gz
    ├── 0569723b4792f84c4b04f8b75a043d737c1a44fd.nq.gz
    ├── 0756fb9932d9843e80bd0970549dec9f352aa1cc.nq.gz
    ├── 07b8e067031eb2fbf1e38b1cb961a87c141d277e.nq.gz
    ├── 07f4b0a03650a5913263d752a0a2dc76a75e8ef7.nq.gz
    ├── 08281aa1f72a3d30e05d5a0342d1d416ea3b2a0f.nq.gz
    ├── 086541360bdf5bd399bd9f29f56c7eab539aa956.nq.gz
    ├── 086bdd40986cf3c0e02d04c1a5b6d3ddd869e47d.nq.gz
    ├── 089206b07486a55824aa2778a962a8bd874f73a0.nq.gz
    ├── 08b3b5ab59324b8dc2c0d33dc3bb3b1386328cba.nq.gz
    ├── 08bdbe44a7c771f64180908a8a3c0c35a73eb5a7.nq.gz
    ├── 091cd92fee362d40885530c710f81367ec9eeab9.nq.gz
    ├── 0a3f13dbc6463831ca20b85fe981dfff27e23774.nq.gz
    ├── 0aa6e0223f4ce7f2e7e641959e24e0d0c94c8b0e.nq.gz
    ├── 0afec132c0251ac2f6a8df5cfb9792ebc79f67ba.nq.gz
    ├── 0c6eb4e4f0381ef2dce298d9a5641b638ff912d0.nq.gz
    ├── 0d8d1430eab8707a6f18076fb09debcec130b6fe.nq.gz
    ├── 0e9b9916eaa88abe236d346b3269d085756c2c2a.nq.gz
    ├── 0f02951b978bcbba488acdd0113cf4138b691263.nq.gz
    ├── 0fcf0b43369215531ce124415da0e03ad500aa9e.nq.gz
    ├── 10fd73c3e5654879cd057afa3803b51f240f7196.nq.gz
    ├── 126cac3645a25e41f8ba242c2c1f3805dda9ceac.nq.gz
    ├── 1415eb1226ebd04961c7c74941c7307ebe844867.nq.gz
    ├── 1430180b10e3b90904ab46dc7ad48ea9fa151044.nq.gz
    ├── 1432564de3098ddda9ecc8e5a89d71c68fdc7c25.nq.gz
    ├── 159fd05f4cb8ec5b8af56ccb5a1838c126f95c07.nq.gz
    ├── 167c3c9490107b5a217383fccec8a692b2cde23f.nq.gz
    ├── 179720ac70e705549d12e322af338a73af1b53e2.nq.gz
    ├── 1954e5b54d2f28651a7d13e57fa7b027336cf253.nq.gz
    ├── 1b3378c5c538a2e75ce94ff8ed8ce7885e22c515.nq.gz
    ├── 1be7fb9fe64936c38e4a607780c965533e7d4cff.nq.gz
    ├── 1c512c437ac88e563e81dfc0e8add0fa1266b334.nq.gz
    ├── 1dc704e8ae06b9615793ade8724ac3bdfbce0a2b.nq.gz
    ├── 1e19115b8a459a5251f80d60964ea371aa3877b3.nq.gz
    ├── 1e4014239e41fbb49c2579ac6d89d5a270d64da0.nq.gz
    ├── 1ef8629733f1917757529d6efd480dbbc83b5800.nq.gz
    ├── 202eb096155f522c39f302552c3bd8fe7efa8603.nq.gz
    ├── 224a0544a0c979df894b7debd5af9d62239bba5f.nq.gz
    ├── 226d01726bd29e857e96daf7bef4c473d440b2ed.nq.gz
    ├── 22ae7485a24528281b7dd9d99fc3bdbf58e0f4d3.nq.gz
    ├── 22b22aa49d820b70f618b9e51e6c725a50bd0cdb.nq.gz
    ├── 24c736f26695f008ebc0872eea17d6ad65b22cc6.nq.gz
    ├── 261974d4e84a37bf03a716f9b4cff754040bf661.nq.gz
    ├── 274709c0f130557b61703921b2150dabafe5266d.nq.gz
    ├── 276913b442a704e678883612467a07f513bb56c8.nq.gz
    ├── 284d8a0a45b519038983b7e661d6be53b76d824a.nq.gz
    ├── 28b6d2531f2ae6e8d1e1305f9391ea30c187acde.nq.gz
    ├── 29814c85c09261b5b232822d5a41655054d4a3eb.nq.gz
    ├── 29e953c44ca7c83a3f9b1da4c6911a68252393d1.nq.gz
    ├── 2a146364cd4e52ab9883627c5122c41daf7a47bd.nq.gz
    ├── 2bb2c53e71c1367d6b63ffd1ef13a8dcf50434ae.nq.gz
    ├── 2ca7b2f6d19707982489bb0c98bbcb3020a378f3.nq.gz
    ├── 2d17631441d66834751e10b11980e358c65766f6.nq.gz
    ├── 2d4defe6647f2a21f66992f75e8cd92ce03fdcc1.nq.gz
    ├── 2d93a89beaa1137d2aa41271b6872a9250c77aae.nq.gz
    ├── 2f147ab25749e2df1c9407d69e39517fe8903ee8.nq.gz
    ├── 2f9e3173f40d3328842ab97787a2ea28f2b0f1b4.nq.gz
    ├── 31a8ed85f8133666ec953eef8e8828b4f8690010.nq.gz
    ├── 31f60637e90eac3778fa722ed6efed42e31e3d01.nq.gz
    ├── 3378a825bade76357ec720d7e576d61d6a31d33d.nq.gz
    ├── 33b3e99a07cb1c4c2e8ba4fc323803755eaa4ae8.nq.gz
    ├── 33cff9d4997d3b4ddf59982a5919bac89c61a1db.nq.gz
    ├── 34cc3a439b3f517153141912e582fad1459174a5.nq.gz
    ├── 34f6aa76c6473ff52d1804ed6a37483202e7c635.nq.gz
    ├── 386f7f5cb96722c472572a24fef35474106685c3.nq.gz
    ├── 38f8174de7678cf1f5b2375ae031ba8537756f7f.nq.gz
    ├── 3931a316c87e7e27ddf692307dd4c7df6931856d.nq.gz
    ├── 393fdad00da1136040cf821f66d1fe1f1a9cbc20.nq.gz
    ├── 3970db212b920f7dfe2e8b1e1cbebaae25f5579d.nq.gz
    ├── 3a0a503feace26f9e24c7bbceeaa5c636e22b89d.nq.gz
    ├── 3a8710babe2bf03f3df85c1ad1d9258f95336fd0.nq.gz
    ├── 3a9ac950a226d1d693e77abefa6e96330c2e6adb.nq.gz
    ├── 3ab120301f48692084dea451a3b22fd4f4305f5f.nq.gz
    ├── 3f15209477ea525627ad437bf6a7e9165f189b92.nq.gz
    ├── 41fd851ecf982e3ef4ae791e018286f3b8a09436.nq.gz
    ├── 428ab8b822ff63a8289ee9d48db5258a3bf688b4.nq.gz
    ├── 4475d840edb2c8cb7d2aba9b610e20b4c6302ae5.nq.gz
    ├── 44d21cb25bcd31eba17d57a28b1d8905ad4ff228.nq.gz
    ├── 462d710932360c661cd0c3322643f5a51e7daaa2.nq.gz
    ├── 46fd5e407d44431241a3e6f66e39e3ef3ff2e5ad.nq.gz
    ├── 476caaf72a042fd6a472e86b947f9e8d5ca7a21c.nq.gz
    ├── 47c0ef801daa3f2875f9986d51739e6a04c789d3.nq.gz
    ├── 47eabaa78c16a3e5009c61d3e4317ed31d6995b9.nq.gz
    ├── 48a4bb6a2b89124578fe4deb46537abc0393114b.nq.gz
    ├── 491e049894ec429a7c41f2cb3ceb3500ef0511e6.nq.gz
    ├── 496dba4feb49a6a397c708f5a6c073fe5a8a4961.nq.gz
    ├── 4aac90b45c3b2751d48d9719fddd5f4d50adf8ec.nq.gz
    ├── 4b2221b5248677fa66030336217427b1f06cb6a0.nq.gz
    ├── 4b251fa29dc3ccbc116b9c6981b09aa9054e8e71.nq.gz
    ├── 4dff6e1820046be51867976826dc821d28c3b8a5.nq.gz
    ├── 501c552ed114099845d5180b9fd3509436606a31.nq.gz
    ├── 5220bb808a80a03ff2412227a20982b894f3b2c5.nq.gz
    ├── 53e2f76657aae8e1fa9553c42cd89155fe23e9ec.nq.gz
    ├── 5466a3092872a58be5851df4b8e3eb777030f515.nq.gz
    ├── 55261dcccf2fe6169202d24d03ab1c6a0ef14516.nq.gz
    ├── 55538547db4540fd16a142ad8291d6a30b8ef636.nq.gz
    ├── 575c5a787e47b4160ff5f79a5679f369173b91d3.nq.gz
    ├── 57a927da20534a3e79cfa60add17a9d34e04b51a.nq.gz
    ├── 57bbe9fdbe5b98e20bc613010a9887ada34cb5f8.nq.gz
    ├── 57bc88a15a0ee8266c259b2667e64608d3f7e292.nq.gz
    ├── 5a5c03f29d2de1d33c7838468ddb8288fbba7811.nq.gz
    ├── 5b2a2bcde423f77414bf0f58565055eb5152f802.nq.gz
    ├── 5b629eafecf959876a8b0b2f2a99a0ebec7595c1.nq.gz
    ├── 5cb39daa0b9071509e3cdbd5a6415c85c5b300db.nq.gz
    ├── 5d640f7006fcce1df457850dd578aef09ed7603c.nq.gz
    ├── 5d870c380387d7b19c2cd2d81e81ce54e48797d4.nq.gz
    ├── 5e5d6919238521c5976bc52b58b899367baeb7cf.nq.gz
    ├── 5f6b24225d519edf72017e237b8755b47fd5d3ed.nq.gz
    ├── 5f963ca96bf9a4ce5f59fb6fd6cb379b31853bc8.nq.gz
    ├── 5f9f0ce59e816725d01a87d4a287a3b87db49f33.nq.gz
    ├── 61af8e6f8c955ecd6ad95ce5d86fcecb0fec0a84.nq.gz
    ├── 61ba99869b85cb186ea99274fb25533caed2cfdc.nq.gz
    ├── 61cff4ec17fafbc39c74a0d2a71fe23e6cf22767.nq.gz
    ├── 638c543e5465263fe29d857307134335c10cf95a.nq.gz
    ├── 649414d769bdcd0f84b1a77f65e65e8c6a00b98b.nq.gz
    ├── 65755bf6ecce746b25b64fade27e0b2b75e386f2.nq.gz
    ├── 66ab7f3d7a63211458e7881c805e03353244426c.nq.gz
    ├── 66ded6ab9b31d2de3e7d432159867b276843ecd0.nq.gz
    ├── 6a9bbdf7ff2b95926317ba0b6806041e9f4864db.nq.gz
    ├── 6c6e2a516129b13a3a7eac5d72669d42bd439078.nq.gz
    ├── 6d5ea1d27f064ee7a2b1060f4ca05f34fcbdffa4.nq.gz
    ├── 6e8843c5d57a5c22bcfff0173cfa5c8ff9e3da16.nq.gz
    ├── 6ec926de6288532ebd844c7754588db06464fc51.nq.gz
    ├── 70a28f7da4d5dcc4c5860457b56e065ef9ebc798.nq.gz
    ├── 70eb50f7f3211028dd3825389d652e2f9b8749dc.nq.gz
    ├── 730c71456e5eb9654feecfa81b886ecbeb81596f.nq.gz
    ├── 73896aa499a53c99095f3272aa520ca9b197656f.nq.gz
    ├── 76ed260824f5deda775570b190f78f4189ff02ac.nq.gz
    ├── 770d29d98591ad4047f3c573d50d9de3d762d937.nq.gz
    ├── 77c00f2be3611005d9334a269a94d7c18d739425.nq.gz
    ├── 78e8c77eb8f40f31e13f4bc1468984f079d048cf.nq.gz
    ├── 79481bc62b92600640d0dc4f8cc771c4615f5fd2.nq.gz
    ├── 7b5f82fe3a142810834de11e47eff473fd28dd81.nq.gz
    ├── 7bc1df495fefa07773df95688a4e3f9b00c2d4f8.nq.gz
    ├── 7c6ff319967731d7955f239ffa10b185b411276c.nq.gz
    ├── 7cc3899b81291691796451b36291f1f137a1a4aa.nq.gz
    ├── 7d40e3dd256c545289b2b77ce613b76b0653b1a8.nq.gz
    ├── 7d7e925e754493a996ab0f464875b884b0d2e58e.nq.gz
    ├── 7ddd1ed07c394a1a300da63ab9d04d4e02e194ce.nq.gz
    ├── 7fddda49071b9f7b2db4483c70ec56b425c65201.nq.gz
    ├── 803229b474ca3b8f9d680cda2306bb38d7b71f6c.nq.gz
    ├── 8165657c0673890f8cb13fcac401e0ab52ba06fb.nq.gz
    ├── 8187c81ef5d5b2296e12d3544774ce68ded20928.nq.gz
    ├── 818c0aaefefb3a471b017ab8a5ea134df4b98d77.nq.gz
    ├── 820022fe99058d07d15e6b5f38270dbef64b381d.nq.gz
    ├── 82547e834ba4c343ceaa56a4311dc113c8a3bb6f.nq.gz
    ├── 829447bdb55add8a39403425110183dbd6e2e91a.nq.gz
    ├── 83559e23e7825bedfe05a808f50964eefb9a62be.nq.gz
    ├── 83a335b5c6b5b6fd2b4995e00df5737813835434.nq.gz
    ├── 862154a87c841a3d67647ac2af4241284b237f7c.nq.gz
    ├── 87d04a0d8edab69a8d6ba7b95822bf49da51b283.nq.gz
    ├── 88b0484638c56799fb99ace9ae3e4b02e2f536d4.nq.gz
    ├── 8af7e781eb7581292730196afccde565ecd28873.nq.gz
    ├── 8c8c00e0838ff02aa327e245ecc0e0fc1f1b088c.nq.gz
    ├── 8cac5e21c5973d29e5723233ca524eb910099fbf.nq.gz
    ├── 8d28995655c85abcd3d75d141aebe1cbb193dca3.nq.gz
    ├── 8db24cf86338a4c260eb68b1a470d48c90983705.nq.gz
    ├── 8e3b6902debb6d00e8b7b833a20882de55f671e9.nq.gz
    ├── 8e63a680f811264f32467a149aa877f026c7d561.nq.gz
    ├── 8e7df338d36eb52c49548ecc58afcb7eb3f73898.nq.gz
    ├── 8fb80dc36f8a0e2012ac19b6acab9985ac2808f4.nq.gz
    ├── 90a73ea6dc7bc6933b371aed3e31ee6821547b62.nq.gz
    ├── 9195a9104aaad8e34d3880ea5d5ef6197c7f460c.nq.gz
    ├── 91beb4b8cd6a888fc101c21245034d9d1a90a00d.nq.gz
    ├── 92a86f02e5385ed8b946e3f524b26d26ad5360b5.nq.gz
    ├── 93183a85e44bfda7c4d0d2152ec133edb7eb4b88.nq.gz
    ├── 9497276918f7feb1fc5f3a7ef469e7522def17e5.nq.gz
    ├── 953d5af776f6ff088daebe5392ef32dbf7b90f77.nq.gz
    ├── 9596d381ddf1e27ae86ae868b6b929d5f204d3da.nq.gz
    ├── 9649dc4984e18d343822b783a255207464f7289a.nq.gz
    ├── 97a403c6de28369a776544809a57a274a5814fac.nq.gz
    ├── 985b03c583d27c49c62ad5ebc3f6f82e7dfee63e.nq.gz
    ├── 987e3a7d7211cc5755cb3e0dabd2d712f851aebf.nq.gz
    ├── 9917ee6ed240e651b6d8db4a35a8eaeb5cb5b111.nq.gz
    ├── 99b5a80e0e0ef984d5d7574a99dd6c559814fe0c.nq.gz
    ├── 9a949832065f4f6ffa49cc94da391d6c7d68218c.nq.gz
    ├── 9aec76348e78748d367961b4896f4d760861af99.nq.gz
    ├── 9b00dd315e44e02139e2bb9027041f8018a60f9b.nq.gz
    ├── 9b4a570d684fb1b0838838941117ec8dd36addad.nq.gz
    ├── 9b62064e846f898078e86c503127d58027bff049.nq.gz
    ├── 9c58ca8f86b5695869fb7f1670125971d90f8a89.nq.gz
    ├── 9cb89dcb1c17f9837a35a0b50d75f9210c12d4b8.nq.gz
    ├── 9edeb871824800f2ccfbd2d4e896da48b8254e2d.nq.gz
    ├── 9efd98617b442b849924d2d3bf2cff971f24dc8d.nq.gz
    ├── 9f7fd1e27d7f88eda764379794266386ab8398b3.nq.gz
    ├── 9ffbc069ca03c75f4b41898d19c90c76e8949ed8.nq.gz
    ├── a1b4bf0fb220abd5f05c45b29ba4099de6546dca.nq.gz
    ├── a38fd68629e05f79905917c4fc1ecebfbd567a32.nq.gz
    ├── a3a7695636acf7d787973b173b21098410783f37.nq.gz
    ├── a724ac6bd3c81e23b67c2d5e3ccb81b07daef1e2.nq.gz
    ├── a9422955f8fb7626c4488366fc7363bd5e68c004.nq.gz
    ├── a97e6fea05abefd6b5529a1b936946dd9cf61cd4.nq.gz
    ├── aa52e0afbac6b3f4d3c53b2e5e76baf4081975b2.nq.gz
    ├── aaa6e4470fbb0bdd4b14223d7d1b804b6c5c26d8.nq.gz
    ├── abe2ed58c1448f2987cd9ee5813dbc6404d5dd94.nq.gz
    └── ac15a2178b60931cb541ca433fc2f9af72c086c4.nq.gz

7 directories, 200 files
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

[allenai/asta-plugins](https://github.com/allenai/asta-plugins)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
