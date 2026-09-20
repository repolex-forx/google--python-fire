# Repolex Knowledge Graph of google/python-fire

RDF knowledge graph data for [google/python-fire](https://github.com/google/python-fire), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download google/python-fire
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 2b5902a15857287066108fdd204a790b3cca8887
│   │   │   └── chunk-001.nq.gz
│   │   ├── 343e6b6cec2d174d511e99dec7e5a24849121c2e
│   │   │   └── chunk-001.nq.gz
│   │   ├── 61785e614c9ee1f0f16f8d8f1fd18b92a1981b4a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6912ccd56f50e0f4bb30a0725d95858ef29f3bde
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8ea2f631e6dc904f69ec59f645fa81eb0a3c2b8e
│   │   │   └── chunk-001.nq.gz
│   │   ├── 90b7f824f2e760e6363b0d10c52b1940346a0fa6
│   │   │   └── chunk-001.nq.gz
│   │   ├── c1a7e2f21fb95e37d80d3e32c7ecbefa12140edf
│   │   │   └── chunk-001.nq.gz
│   │   ├── d77453938a4b7a5a2bb71d9cb40397ee8bbc2e0a
│   │   │   └── chunk-001.nq.gz
│   │   ├── e1e95ffe2454f7e9887640883e35c01543f54139
│   │   │   └── chunk-001.nq.gz
│   │   ├── e76a10c0511ea4485b57543ccb966e7778213279
│   │   │   └── chunk-001.nq.gz
│   │   └── fb7ee3a716020f6a04c0e55967612f9322d16893
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 2b5902a15857287066108fdd204a790b3cca8887.nq.gz
│   │   ├── 343e6b6cec2d174d511e99dec7e5a24849121c2e.nq.gz
│   │   ├── 61785e614c9ee1f0f16f8d8f1fd18b92a1981b4a.nq.gz
│   │   ├── 6912ccd56f50e0f4bb30a0725d95858ef29f3bde.nq.gz
│   │   ├── 8ea2f631e6dc904f69ec59f645fa81eb0a3c2b8e.nq.gz
│   │   ├── 90b7f824f2e760e6363b0d10c52b1940346a0fa6.nq.gz
│   │   ├── c1a7e2f21fb95e37d80d3e32c7ecbefa12140edf.nq.gz
│   │   ├── d77453938a4b7a5a2bb71d9cb40397ee8bbc2e0a.nq.gz
│   │   ├── e1e95ffe2454f7e9887640883e35c01543f54139.nq.gz
│   │   ├── e76a10c0511ea4485b57543ccb966e7778213279.nq.gz
│   │   └── fb7ee3a716020f6a04c0e55967612f9322d16893.nq.gz
│   └── repolex
│       ├── 2b5902a15857287066108fdd204a790b3cca8887
│       │   └── chunk-001.nq.gz
│       ├── 343e6b6cec2d174d511e99dec7e5a24849121c2e
│       │   └── chunk-001.nq.gz
│       ├── 61785e614c9ee1f0f16f8d8f1fd18b92a1981b4a
│       │   └── chunk-001.nq.gz
│       ├── 6912ccd56f50e0f4bb30a0725d95858ef29f3bde
│       │   └── chunk-001.nq.gz
│       ├── 8ea2f631e6dc904f69ec59f645fa81eb0a3c2b8e
│       │   └── chunk-001.nq.gz
│       ├── 90b7f824f2e760e6363b0d10c52b1940346a0fa6
│       │   └── chunk-001.nq.gz
│       ├── c1a7e2f21fb95e37d80d3e32c7ecbefa12140edf
│       │   └── chunk-001.nq.gz
│       ├── d77453938a4b7a5a2bb71d9cb40397ee8bbc2e0a
│       │   └── chunk-001.nq.gz
│       ├── e1e95ffe2454f7e9887640883e35c01543f54139
│       │   └── chunk-001.nq.gz
│       ├── e76a10c0511ea4485b57543ccb966e7778213279
│       │   └── chunk-001.nq.gz
│       └── fb7ee3a716020f6a04c0e55967612f9322d16893
│           └── chunk-001.nq.gz
└── blob
    ├── 0047fa951cac3b8951e842590fe201418c1aeffe.nq.gz
    ├── 018eb89e8995b230041dab0be289a3605887f750.nq.gz
    ├── 0257be285f8e717d36a1bd1678e639e9bb0d62ef.nq.gz
    ├── 035adf953c2632a4fa9429f0afd4df1c80788b19.nq.gz
    ├── 044fcb37da1cc13817b7df63306f802e1a034f68.nq.gz
    ├── 0541a9a5e8f15794ffae00224ab2c0983f960736.nq.gz
    ├── 058f329c314cdce853752d209f95eb9bb418b0e7.nq.gz
    ├── 05a88c496ced2e1b856ebeaa6ad79149722325cd.nq.gz
    ├── 0786fdf434684f6ef3b5eac90cb7813bdb9c4d2a.nq.gz
    ├── 07993de9d03d6c9cd4ea1b4ad01ba163c913db2b.nq.gz
    ├── 08c2aef11a01b78dc22e77c18ec0719985f9d48e.nq.gz
    ├── 0d6e5d1823b9ac05395d0ff164e70e7a3b713efd.nq.gz
    ├── 0f369a9a58de9f4ef9fa0c5cebc4b7960b6dcd92.nq.gz
    ├── 0fa8e7d35f31466bf99464cc127739c34a922d48.nq.gz
    ├── 10f497cf2cb9b42cfee627b39b7be23f7ed8b55a.nq.gz
    ├── 111257ae024d33a73c25b77d1c6e3bbed6f44066.nq.gz
    ├── 129f765eccc363e8b7107615dcf50264b6ed26a8.nq.gz
    ├── 1371e2a13a8aaa1ece981aeda9c54d954833036f.nq.gz
    ├── 13880c9c6aca67407babcd85d7c48bea394f40c3.nq.gz
    ├── 13fd8204566bc06d6d1db9342a17008080c1ad6f.nq.gz
    ├── 140b4a76852419253bf902c079ffdbbcf58ac1d4.nq.gz
    ├── 1482d56d17f6cacfb71a90231d509a1ea6773a7b.nq.gz
    ├── 1597d464622897fe55964f130fbca53cd93b30c2.nq.gz
    ├── 15f32f9142de294ea86d4d3aec1aa275e3dc1151.nq.gz
    ├── 1621a59384db9486a3b515ec49f27ff44cd67758.nq.gz
    ├── 16246cb802304a0e63ab0e67e0ef686aa9e62a82.nq.gz
    ├── 1644ff506f314622050996aeb2f58332557c46f1.nq.gz
    ├── 168312d4749d3ccc682095986fa4f5ffaa6d0730.nq.gz
    ├── 171ae26efc26692cb66273ad90d9a965f40847f7.nq.gz
    ├── 17fb932c1fe8fa2b898187dde72dd2e114bae740.nq.gz
    ├── 191e8b297257925fcdea417a78d4fa3e6bd63d84.nq.gz
    ├── 192302d3ba9a18fa446b82d28964f54c80e73826.nq.gz
    ├── 19d068fdb0ac97669414410d4140362e07fccda8.nq.gz
    ├── 1aba38f67a2211cf5b09466d7b411206cb7223bf.nq.gz
    ├── 1b1c5cc2c81537da2216e60fc9a13490f7db530f.nq.gz
    ├── 1c843f4231de9f117e3beaf48557279a4d2aad8c.nq.gz
    ├── 1cc64a07ee04df04ee87f05c167827f43ecad1d3.nq.gz
    ├── 1cfadea93b5a7205750c2a9ebcfe5e418d7ec992.nq.gz
    ├── 1d165b3769c9c0d18f3cbd7874c16ab14c1fee49.nq.gz
    ├── 1dec90325eba830c4b29236574c57b1aa04fdda4.nq.gz
    ├── 1e52944cde48149750ff0e61541a7a92e437aa10.nq.gz
    ├── 1e92b5313304619037aef9d18cd7eada297cf7a9.nq.gz
    ├── 1f858f5e0913f6fd694b6f2cb8f444a708e2294b.nq.gz
    ├── 1f9ed766f804b680c31825eeaf47905d51c8d0ea.nq.gz
    ├── 2328ef16d6aa6f5eaeed2de3384c981be97208f0.nq.gz
    ├── 235cb95dad9704bf588dabf74124b6e5a65b1310.nq.gz
    ├── 23c46c5af34c5a43941aef216584d8eccd6481a7.nq.gz
    ├── 23f8680327f0f2b9fd464adcf66e2aae814d9ac8.nq.gz
    ├── 24e0e325e5730230759d86bebf7e855ad1f50859.nq.gz
    ├── 266671f194f9faad993dbf1178aa8cb8d27204da.nq.gz
    ├── 26a07756af8e3b7f53f3eb183c1b1dbad37c2b14.nq.gz
    ├── 26a25753563c70c8be6b0d73f10929a67092d346.nq.gz
    ├── 274cf382f1bb31c07b6dd1fbb0a3514d5041c5f5.nq.gz
    ├── 27c9f41889cba4a96969e0ab1ab4b498a6366a69.nq.gz
    ├── 285c42cdee69db91ed8ebb4d56546868028dbd47.nq.gz
    ├── 28d79a6c2d277322681fd8f250d2246e756cee6f.nq.gz
    ├── 29fa7597cf42b95e4d5d5d8a88aab1637cafea35.nq.gz
    ├── 2ad217d6183c42ecc3567b56cc856308e4a7c355.nq.gz
    ├── 2adfe5ec7f84844438aa4ca5c05fde61b640b376.nq.gz
    ├── 2aff8bd7c0753e321bab5b61c360e72ebb2d03bd.nq.gz
    ├── 2b85820d31fe799a2c279bd7609e50bb2367f2ae.nq.gz
    ├── 2bacc8fed6d816715bd711fdc9688d43ac831967.nq.gz
    ├── 2be6b83de1924529488dce505ee1de3c808a8526.nq.gz
    ├── 2c360d2b12dbd9dc4ea27720b9edcf3d387c1eca.nq.gz
    ├── 2d7c7e63dda6cd3b6837c5752174237804e210da.nq.gz
    ├── 2d8f61b5f8628bad0abe6807b0de4663a144b629.nq.gz
    ├── 2e59ce8a43a3798fe35fe31262b168281f8ece1a.nq.gz
    ├── 2f286824e3e9c451e46c6d2d90d8ce60e07edd96.nq.gz
    ├── 2f2df3fd624edc5c00d55692c855c426a21e248d.nq.gz
    ├── 30d556e4a7df919aa5d43ccd20bbc1b5759804aa.nq.gz
    ├── 318d6276068145eed3ee00a4aca13d7262e6dd9b.nq.gz
    ├── 31a2badbf0a21d079cfe2d89bd1270f07ddcf3fe.nq.gz
    ├── 32e0e9cc5db87868ed667447f328e6d5e07cd1e6.nq.gz
    ├── 3463fd50817fc6383239a9122a1342784f734b10.nq.gz
    ├── 347278dabcd00f2ba405b4ce3813fc52511af434.nq.gz
    ├── 35c10fbaac9891a90c49cee074a6e9c6065dae15.nq.gz
    ├── 3619fb061dd82501de5f8439c6fa5a9c633579be.nq.gz
    ├── 372cee606aa1f557cd92d264edf19ea4d65b3e74.nq.gz
    ├── 37bfa447e1204482017b60f325755688e80e82b4.nq.gz
    ├── 38918dee901caf9103bf1b27049980198d045c59.nq.gz
    ├── 3c21f4bacf26bcf39883b49f6ff303f1fed1adb7.nq.gz
    ├── 3cb40fbe89c393f98b77880c01658f8a942c170e.nq.gz
    ├── 3ce30cb5f64d3da881ccf6b731d6d6018a8695f6.nq.gz
    ├── 3d3b9f81f823696154787951201761dcd80a7286.nq.gz
    ├── 3ef6b5484c158d942901310c16e4bff0b51e856a.nq.gz
    ├── 404d98123f1c668d61d137bf3c778182e1a94aa0.nq.gz
    ├── 404e18e7b1578b795ff472b24bb01924fc7a3546.nq.gz
    ├── 40769fe36d1dffecf3016ed2664645c5eefeaa2b.nq.gz
    ├── 41699ac62b4e192d22c7650e29b394994e94227e.nq.gz
    ├── 41bda634f77aac24b117524f4a91042e85e41983.nq.gz
    ├── 4393880d96dde88435d3970ba87acf1bad19bd45.nq.gz
    ├── 444a76ff8c21f9c28654c6a6aa6571270e0c7d32.nq.gz
    ├── 44b7d7beae530ca8ca6599758350d0cc099ad17f.nq.gz
    ├── 44d8a46d47fe9bff357783b8c01508e14c81025e.nq.gz
    ├── 44edde6e5b01b8a51957812afc9838a6e804c11a.nq.gz
    ├── 451438839e82c4e7ec532fdd4c174974c582247d.nq.gz
    ├── 451e202147b87e66e530d8c41423b2adc53577ee.nq.gz
    ├── 46010c073d97c4260b475af6dbf37b324fe49c85.nq.gz
    ├── 479cbaf6cbf98ff6de69c97ee90cde5782536b63.nq.gz
    ├── 47de7e72ebb0673e4312fbf84678ba50f1b6d3fd.nq.gz
    ├── 4a6d4776feb36a7be8d83c82b0c9a477c2834e21.nq.gz
    ├── 4b58e63ca02ee77fa041c848f2e4120dd6c0dc9a.nq.gz
    ├── 4cc7621065eaa63e732cabc2a3eec467727e4c68.nq.gz
    ├── 4cd95e147f1beb18eb8e6b3360479d56e9babde3.nq.gz
    ├── 4cfc09375c6e417fd0fbc948aca66d0b56f949c6.nq.gz
    ├── 4eb114b111736112e21579f9507d8982c1b632b5.nq.gz
    ├── 4f2ffb9be4a706472d38a787f40b6218f666a5a1.nq.gz
    ├── 5140921df49d3b1c3dcdadbf8a60301abf378063.nq.gz
    ├── 531f882cfc4598e345697d633b19edc62c56a863.nq.gz
    ├── 547153c65a0ce5472641adc2d6563f4593807ff5.nq.gz
    ├── 558d3ba25ea23e260bf3c2472bf1cc0b94917b35.nq.gz
    ├── 565c7e1ebae5c780cf801335a2fbe80606f51b3f.nq.gz
    ├── 582e5bbca3a39ab7ad2787597f01d725a754f468.nq.gz
    ├── 592eb0f9baf2743e58055cbf54e8e3ca517734e1.nq.gz
    ├── 59b0a4baadc7f57283224f3b6a0885fa18ba422f.nq.gz
    ├── 5c23de3a8aa7bfb669fefae3ec5a514bc18c36d0.nq.gz
    ├── 5e244f8cdb25146306a3e271326fa85ce7c55930.nq.gz
    ├── 5f693a400b1824ad50a09e7b2d98c9e645665ec4.nq.gz
    ├── 5f8751471c1090af24af72917c6424a03eb7886e.nq.gz
    ├── 5fcb056ee180b8b1b3c22bbb8a550772d39b3fe6.nq.gz
    ├── 601026fdfa65f856f73cbd01ca23a46a7ff5d956.nq.gz
    ├── 614243af7d3cd3695c1e98f0c28dcb51af6aa69b.nq.gz
    ├── 61cce0e867e60e15b315e63b5680f42f17a70d87.nq.gz
    ├── 625e9d8600f4f98742eea01b8b68e03b301f9aa0.nq.gz
    ├── 62afdf115680a85cf794d5ced1543721eb7ea5af.nq.gz
    ├── 6367262d255e72c2c92120264804dce523316934.nq.gz
    ├── 662342c656f2daeb19a77928905e8bd1547378fc.nq.gz
    ├── 6645107165b8c45cd3b917e9b8bd6b1f4df99b4c.nq.gz
    ├── 66be8006dd78972f74f3e2dc63554597920aab3d.nq.gz
    ├── 6810364928fc237ebda4cbbb0a55b3293f1d8d73.nq.gz
    ├── 68484c27987c8f1757ffb08fd01ad249bb103646.nq.gz
    ├── 695b01b3b705eb1bbfc8406e0655422722d67b8b.nq.gz
    ├── 69970f43db0e176bc98eed0860acd127b46e2156.nq.gz
    ├── 6cff2d5d5f414db30d110a4fb18a89dd698c18e8.nq.gz
    ├── 6dd8fd67d2bef401c339a34be5ec7563428489b0.nq.gz
    ├── 6e2188d61b10ad4c2d01ef5790ca7476b9e6cd90.nq.gz
    ├── 6e7fbb07f368fb1108d271663968babab0f5d9e4.nq.gz
    ├── 6fd8f73b493f9399299e658bbe6266cbb807ba77.nq.gz
    ├── 7174f9947a896618cb9b7495f3d99ad5df764a4c.nq.gz
    ├── 73e68488133046a5fe49e1158c0e6202ba46e8cc.nq.gz
    ├── 749ab6d0954965a0e006f4092e5f11cf080be645.nq.gz
    ├── 75a687f3acd146a44bebbae45885109704fa3a3e.nq.gz
    ├── 75b76998602742a9e883a2cb8622f5f412d20f0b.nq.gz
    ├── 7609f4f812a7accff8fe6080ed6e8ae23cbf7771.nq.gz
    ├── 763b3d1330ab9c536e2b511e992fde7857542177.nq.gz
    ├── 768f0e232e72ab150355e72088ddefac26db1b73.nq.gz
    ├── 777f1f48af82ea475f808f11999c996dfdedfd0f.nq.gz
    ├── 780e5a28b8219e25fee6ae4be6118935fef99495.nq.gz
    ├── 784369b7e762464212dd290f5c132d7b6b4071c0.nq.gz
    ├── 79d7c7a146c3c2c6ba6a2dd3b621592d8a07f7ca.nq.gz
    ├── 7a98013617ca19c334957241b32d4742281f0882.nq.gz
    ├── 7c2e139bc72306104f8311396af8ec3061a9d53c.nq.gz
    ├── 7df32841c6be57e53f57c79dc060c7ccf72104bc.nq.gz
    ├── 7e4cccb85c369804eed436a34b88da577601468c.nq.gz
    ├── 7f0f5195e1f79fcf26606fff104c1ebd6344e872.nq.gz
    ├── 7fd9ca795ae0984c7137b80ad41bc34555075c7b.nq.gz
    ├── 81308973bf28da209c4c74cf27e81d8315f19b7d.nq.gz
    ├── 815e16b8791ae16916ac34618920d8abfe278b38.nq.gz
    ├── 81a513c3e70bb018b74fb42ae479edcbf10c366e.nq.gz
    ├── 83610a5d35872f4de5680bcc2060a33bfc1fa2ea.nq.gz
    ├── 8482c7bcbc5facd269c527c522e8909eb19863af.nq.gz
    ├── 8520769ac7cd4c477350c468979d189f65021dcd.nq.gz
    ├── 858201ff782c13588630b25e78d03840cb3a0f56.nq.gz
    ├── 8589b79e89fd81cbc1f2099c759c081d849e774b.nq.gz
    ├── 862f5f23e398ec88d88bad3343f4a55787672186.nq.gz
    ├── 869c594965769adcad6a52602a7a698512a3e372.nq.gz
    └── 86c7d4acbb62e0447380b9c4c68ef07bbf5ead1b.nq.gz

28 directories, 200 files
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

## Source repository

[google/python-fire](https://github.com/google/python-fire)

---
*Parsed on 2026-09-20 by [repolex](https://repolex.ai)*
