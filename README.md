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
│   │   ├── 8ea2f631e6dc904f69ec59f645fa81eb0a3c2b8e
│   │   │   └── chunk-001.nq.gz
│   │   ├── 90b7f824f2e760e6363b0d10c52b1940346a0fa6
│   │   │   └── chunk-001.nq.gz
│   │   ├── e1e95ffe2454f7e9887640883e35c01543f54139
│   │   │   └── chunk-001.nq.gz
│   │   └── fb7ee3a716020f6a04c0e55967612f9322d16893
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 2b5902a15857287066108fdd204a790b3cca8887.nq.gz
│   │   ├── 343e6b6cec2d174d511e99dec7e5a24849121c2e.nq.gz
│   │   ├── 8ea2f631e6dc904f69ec59f645fa81eb0a3c2b8e.nq.gz
│   │   ├── 90b7f824f2e760e6363b0d10c52b1940346a0fa6.nq.gz
│   │   ├── e1e95ffe2454f7e9887640883e35c01543f54139.nq.gz
│   │   └── fb7ee3a716020f6a04c0e55967612f9322d16893.nq.gz
│   └── repolex
│       ├── 2b5902a15857287066108fdd204a790b3cca8887
│       │   └── chunk-001.nq.gz
│       ├── 343e6b6cec2d174d511e99dec7e5a24849121c2e
│       │   └── chunk-001.nq.gz
│       ├── 8ea2f631e6dc904f69ec59f645fa81eb0a3c2b8e
│       │   └── chunk-001.nq.gz
│       ├── 90b7f824f2e760e6363b0d10c52b1940346a0fa6
│       │   └── chunk-001.nq.gz
│       ├── e1e95ffe2454f7e9887640883e35c01543f54139
│       │   └── chunk-001.nq.gz
│       └── fb7ee3a716020f6a04c0e55967612f9322d16893
│           └── chunk-001.nq.gz
└── blob
    ├── 0047fa951cac3b8951e842590fe201418c1aeffe.nq.gz
    ├── 018eb89e8995b230041dab0be289a3605887f750.nq.gz
    ├── 0257be285f8e717d36a1bd1678e639e9bb0d62ef.nq.gz
    ├── 035adf953c2632a4fa9429f0afd4df1c80788b19.nq.gz
    ├── 044fcb37da1cc13817b7df63306f802e1a034f68.nq.gz
    ├── 058f329c314cdce853752d209f95eb9bb418b0e7.nq.gz
    ├── 05a88c496ced2e1b856ebeaa6ad79149722325cd.nq.gz
    ├── 0786fdf434684f6ef3b5eac90cb7813bdb9c4d2a.nq.gz
    ├── 08c2aef11a01b78dc22e77c18ec0719985f9d48e.nq.gz
    ├── 0d6e5d1823b9ac05395d0ff164e70e7a3b713efd.nq.gz
    ├── 0f369a9a58de9f4ef9fa0c5cebc4b7960b6dcd92.nq.gz
    ├── 0fa8e7d35f31466bf99464cc127739c34a922d48.nq.gz
    ├── 10f497cf2cb9b42cfee627b39b7be23f7ed8b55a.nq.gz
    ├── 111257ae024d33a73c25b77d1c6e3bbed6f44066.nq.gz
    ├── 13880c9c6aca67407babcd85d7c48bea394f40c3.nq.gz
    ├── 13fd8204566bc06d6d1db9342a17008080c1ad6f.nq.gz
    ├── 140b4a76852419253bf902c079ffdbbcf58ac1d4.nq.gz
    ├── 1482d56d17f6cacfb71a90231d509a1ea6773a7b.nq.gz
    ├── 1597d464622897fe55964f130fbca53cd93b30c2.nq.gz
    ├── 15f32f9142de294ea86d4d3aec1aa275e3dc1151.nq.gz
    ├── 1621a59384db9486a3b515ec49f27ff44cd67758.nq.gz
    ├── 16246cb802304a0e63ab0e67e0ef686aa9e62a82.nq.gz
    ├── 17fb932c1fe8fa2b898187dde72dd2e114bae740.nq.gz
    ├── 191e8b297257925fcdea417a78d4fa3e6bd63d84.nq.gz
    ├── 192302d3ba9a18fa446b82d28964f54c80e73826.nq.gz
    ├── 1aba38f67a2211cf5b09466d7b411206cb7223bf.nq.gz
    ├── 1b1c5cc2c81537da2216e60fc9a13490f7db530f.nq.gz
    ├── 1cc64a07ee04df04ee87f05c167827f43ecad1d3.nq.gz
    ├── 1cfadea93b5a7205750c2a9ebcfe5e418d7ec992.nq.gz
    ├── 1d165b3769c9c0d18f3cbd7874c16ab14c1fee49.nq.gz
    ├── 1f858f5e0913f6fd694b6f2cb8f444a708e2294b.nq.gz
    ├── 1f9ed766f804b680c31825eeaf47905d51c8d0ea.nq.gz
    ├── 2328ef16d6aa6f5eaeed2de3384c981be97208f0.nq.gz
    ├── 24e0e325e5730230759d86bebf7e855ad1f50859.nq.gz
    ├── 266671f194f9faad993dbf1178aa8cb8d27204da.nq.gz
    ├── 26a25753563c70c8be6b0d73f10929a67092d346.nq.gz
    ├── 274cf382f1bb31c07b6dd1fbb0a3514d5041c5f5.nq.gz
    ├── 27c9f41889cba4a96969e0ab1ab4b498a6366a69.nq.gz
    ├── 29fa7597cf42b95e4d5d5d8a88aab1637cafea35.nq.gz
    ├── 2ad217d6183c42ecc3567b56cc856308e4a7c355.nq.gz
    ├── 2adfe5ec7f84844438aa4ca5c05fde61b640b376.nq.gz
    ├── 2aff8bd7c0753e321bab5b61c360e72ebb2d03bd.nq.gz
    ├── 2b85820d31fe799a2c279bd7609e50bb2367f2ae.nq.gz
    ├── 2bacc8fed6d816715bd711fdc9688d43ac831967.nq.gz
    ├── 2d7c7e63dda6cd3b6837c5752174237804e210da.nq.gz
    ├── 2f286824e3e9c451e46c6d2d90d8ce60e07edd96.nq.gz
    ├── 30d556e4a7df919aa5d43ccd20bbc1b5759804aa.nq.gz
    ├── 318d6276068145eed3ee00a4aca13d7262e6dd9b.nq.gz
    ├── 31a2badbf0a21d079cfe2d89bd1270f07ddcf3fe.nq.gz
    ├── 32e0e9cc5db87868ed667447f328e6d5e07cd1e6.nq.gz
    ├── 3463fd50817fc6383239a9122a1342784f734b10.nq.gz
    ├── 347278dabcd00f2ba405b4ce3813fc52511af434.nq.gz
    ├── 35c10fbaac9891a90c49cee074a6e9c6065dae15.nq.gz
    ├── 3619fb061dd82501de5f8439c6fa5a9c633579be.nq.gz
    ├── 37bfa447e1204482017b60f325755688e80e82b4.nq.gz
    ├── 3c21f4bacf26bcf39883b49f6ff303f1fed1adb7.nq.gz
    ├── 3cb40fbe89c393f98b77880c01658f8a942c170e.nq.gz
    ├── 3ce30cb5f64d3da881ccf6b731d6d6018a8695f6.nq.gz
    ├── 3d3b9f81f823696154787951201761dcd80a7286.nq.gz
    ├── 3ef6b5484c158d942901310c16e4bff0b51e856a.nq.gz
    ├── 404d98123f1c668d61d137bf3c778182e1a94aa0.nq.gz
    ├── 404e18e7b1578b795ff472b24bb01924fc7a3546.nq.gz
    ├── 41699ac62b4e192d22c7650e29b394994e94227e.nq.gz
    ├── 41bda634f77aac24b117524f4a91042e85e41983.nq.gz
    ├── 4393880d96dde88435d3970ba87acf1bad19bd45.nq.gz
    ├── 444a76ff8c21f9c28654c6a6aa6571270e0c7d32.nq.gz
    ├── 44d8a46d47fe9bff357783b8c01508e14c81025e.nq.gz
    ├── 451438839e82c4e7ec532fdd4c174974c582247d.nq.gz
    ├── 451e202147b87e66e530d8c41423b2adc53577ee.nq.gz
    ├── 47de7e72ebb0673e4312fbf84678ba50f1b6d3fd.nq.gz
    ├── 4a6d4776feb36a7be8d83c82b0c9a477c2834e21.nq.gz
    ├── 4cc7621065eaa63e732cabc2a3eec467727e4c68.nq.gz
    ├── 4cfc09375c6e417fd0fbc948aca66d0b56f949c6.nq.gz
    ├── 4eb114b111736112e21579f9507d8982c1b632b5.nq.gz
    ├── 4f2ffb9be4a706472d38a787f40b6218f666a5a1.nq.gz
    ├── 5140921df49d3b1c3dcdadbf8a60301abf378063.nq.gz
    ├── 531f882cfc4598e345697d633b19edc62c56a863.nq.gz
    ├── 547153c65a0ce5472641adc2d6563f4593807ff5.nq.gz
    ├── 558d3ba25ea23e260bf3c2472bf1cc0b94917b35.nq.gz
    ├── 565c7e1ebae5c780cf801335a2fbe80606f51b3f.nq.gz
    ├── 582e5bbca3a39ab7ad2787597f01d725a754f468.nq.gz
    ├── 59b0a4baadc7f57283224f3b6a0885fa18ba422f.nq.gz
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
    ├── 68484c27987c8f1757ffb08fd01ad249bb103646.nq.gz
    ├── 69970f43db0e176bc98eed0860acd127b46e2156.nq.gz
    ├── 6cff2d5d5f414db30d110a4fb18a89dd698c18e8.nq.gz
    ├── 6dd8fd67d2bef401c339a34be5ec7563428489b0.nq.gz
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
    ├── 780e5a28b8219e25fee6ae4be6118935fef99495.nq.gz
    ├── 79d7c7a146c3c2c6ba6a2dd3b621592d8a07f7ca.nq.gz
    ├── 7a98013617ca19c334957241b32d4742281f0882.nq.gz
    ├── 7df32841c6be57e53f57c79dc060c7ccf72104bc.nq.gz
    ├── 7e4cccb85c369804eed436a34b88da577601468c.nq.gz
    ├── 81308973bf28da209c4c74cf27e81d8315f19b7d.nq.gz
    ├── 815e16b8791ae16916ac34618920d8abfe278b38.nq.gz
    ├── 81a513c3e70bb018b74fb42ae479edcbf10c366e.nq.gz
    ├── 83610a5d35872f4de5680bcc2060a33bfc1fa2ea.nq.gz
    ├── 8482c7bcbc5facd269c527c522e8909eb19863af.nq.gz
    ├── 869c594965769adcad6a52602a7a698512a3e372.nq.gz
    ├── 887a0dc68c6685f3cae46329c543e42dca67be72.nq.gz
    ├── 8896bb5baa92674812fd5faf87350173ffaa7d87.nq.gz
    ├── 8aeabc6198bd2cef1daf1ace3f3193bb5196cabf.nq.gz
    ├── 8b1d768534ab4b93e4227c7878b7ac6cf213d021.nq.gz
    ├── 8b904c29f82c107f1c2df13ac20e72dda4d4d40e.nq.gz
    ├── 8be46672e4fcec44cd550ba22fdad141e33d1284.nq.gz
    ├── 8ca142c7078ee5d616df297706b6c9d8a8ca9d89.nq.gz
    ├── 8d4a381b216d9f239d4eff2d480980f1930d437f.nq.gz
    ├── 8dcc5db6db5b6708874d2951f4ef3a902e714b07.nq.gz
    ├── 9092ad75cc92699c1139fdcb74bf89138058fff0.nq.gz
    ├── 909ec43937ad39f0c29313c492035363ac7c482d.nq.gz
    ├── 90b7f466f57311fafb2e70282e2cef0fc152de76.nq.gz
    ├── 914b1de6fc6b5a65834a70e507a1722d01705329.nq.gz
    ├── 949632ef9ddbe3b31f2e28bfe67db535d26981f7.nq.gz
    ├── 9659ec6abc32181f2d904dcb032519d6ca044684.nq.gz
    ├── 97222c3d19fcc98561dd345a0a22fa1cffe2fc0e.nq.gz
    ├── 977056b0e8e4f8e054f10a3e7c1cf586669d415e.nq.gz
    ├── 9988743cc84a9354eee153032e544414227266de.nq.gz
    ├── 99b4a7c6fd05b5a74d036d5b31514af334484599.nq.gz
    ├── 9c34a5af4d81380989425cc3d7782add05823e81.nq.gz
    ├── 9c558e357c41674e39880abb6c3209e539de42e2.nq.gz
    ├── 9d8227adaa3203dbef3498706f79e1ec23beab9f.nq.gz
    ├── 9da8f54fa0639cb139fa06d232b96b3564ce9143.nq.gz
    ├── 9e1c382be703552e220ca4b44c7b0c54a32c2991.nq.gz
    ├── 9e56d6df7a03c8a90e27614305d734a6f5a96793.nq.gz
    ├── 9ff696d33307e74b461f6d1ce52e21957d5f499f.nq.gz
    ├── a01846200c27f487885f92be51a0aa73dfcfbd25.nq.gz
    ├── a216668492efe700ff5846af2a786db50dc1fa41.nq.gz
    ├── a25ba7af7fcfb11e4a9537b619898c0d38640579.nq.gz
    ├── a2723347994bbf83c901925e2d0db38f80146f1a.nq.gz
    ├── a404eea28cc152d4d30849fa56a699a0f4ed2f86.nq.gz
    ├── a56489892cfb4b0b6f2ff2662b9b87ed1dcce130.nq.gz
    ├── a5cd7188bc8d62cdfc7c7032fd060cc0f6ed2f24.nq.gz
    ├── a6b4acc3482a4cac97ce5d011f2a1546d586a912.nq.gz
    ├── a7193ca1b40de54f2ffaa2071f2fdc1d21ee2cdb.nq.gz
    ├── a7f38d4f8bfeaec487534d4697d41a088bd18383.nq.gz
    ├── aa918160d9c9fe5dcdd7acfcc227596751b2c947.nq.gz
    ├── aae92cd6bd2ef6bb10f1f96bf5528324058f3a5b.nq.gz
    ├── ac09f0be8f0439957073607002c7cd25d96ec2b8.nq.gz
    ├── ad604193a9c4708eeaa1ac77c74a0b2d364e5cb9.nq.gz
    ├── aeff52401b7ea6afb6548022b1e56aca7804e187.nq.gz
    ├── af0be03800e39a7e64e9d906e46d07d8fac2546b.nq.gz
    ├── b1470692a57028d87bcd844cb0d342a90172019b.nq.gz
    ├── b1d10b4489f08b9ac090220dc71423263e417428.nq.gz
    ├── b23401f7d18830839101d357f8789c3ef27398fc.nq.gz
    ├── b2e9b322d47bbc23996152f0c98d30f8eb11ced3.nq.gz
    ├── b3c758e1749a8561675bfd2ed78043f980163f64.nq.gz
    ├── b5d67c96b341661679ea52f98300ae33e24a6c39.nq.gz
    ├── b765e3f23182f8c23257e3ff337be9feb5a43d09.nq.gz
    ├── b7b3c6601dc770981dd8aafcdbe59bd4d9d79cdc.nq.gz
    ├── b89b16d1da1d94749fcaace473e295f5a7750e3f.nq.gz
    ├── b8e7f19cc4e07c21c8aebaab784b72c551d1cdfd.nq.gz
    ├── ba1b7f190fbaf66d34a830813fe2e831277bd5af.nq.gz
    ├── baae1a6e8e98213f9678dc935570b25311e27a6a.nq.gz
    ├── bb815e3794948ec4f20628f9212602ce334081ea.nq.gz
    ├── bbe1e848ec548370a386ac11f8fe8b149db794fb.nq.gz
    ├── bc5e04054124ea9e5a73ef771f91cf6673bbb37b.nq.gz
    ├── bdfcb7db49a492fe573fd253480860efcc307407.nq.gz
    ├── bf1cbeb2a1fabaed3cbaace7165deea64841c1a9.nq.gz
    ├── c0a137fdb2159056da507a27325d564d9d226e05.nq.gz
    ├── c0a3d784da0b6ecca0a65144f92182dd28d32412.nq.gz
    ├── c0d5d24f9ee896d64df58ebfa3d77856a3604c93.nq.gz
    └── c1e97367fcccf164a4c3ea94879859b6d34180b6.nq.gz

18 directories, 200 files
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
