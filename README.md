# Repolex Knowledge Graph of python-pendulum/pendulum

RDF knowledge graph data for [python-pendulum/pendulum](https://github.com/python-pendulum/pendulum), parsed by [repolex](https://repolex.ai).

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
rlex download python-pendulum/pendulum
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e06dacedc4cdea90fa1286b3965d180ab94cf251
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e06dacedc4cdea90fa1286b3965d180ab94cf251
│           └── chunk-001.nq.gz
└── blob
    ├── 0059c11eac1c269d911d8edbbca5b1c75ac53cb0.nq.gz
    ├── 0071c944b3d56af133d01391dab78d90f236de3b.nq.gz
    ├── 0078b4884b1f8563aa1578f4c608125c7ae4667d.nq.gz
    ├── 056310776a03d316758b70502e82e31aaa4eeaa3.nq.gz
    ├── 0695a64fa462143438be658d3129dcff5c769f92.nq.gz
    ├── 07ab5f143332816254a816b63f501f46e5226543.nq.gz
    ├── 084f019ec2b6d593cff969243e765f307e482c58.nq.gz
    ├── 08df7d851623a0bb64a2761637fc62b9ca29d538.nq.gz
    ├── 0aaab900fae72c1e955d9e8f3b9aa64dc897ab90.nq.gz
    ├── 0b883e5834ba8192258849fc3620be92f1e7b192.nq.gz
    ├── 0c6e725dfc0f32d18a1cdec7769eec790747a9e1.nq.gz
    ├── 0d4ac4148ab34f7d9cf535a1d2cf16fe4a54dadb.nq.gz
    ├── 107e043c7140418be24d43b7e7a81b2d9e79a1f1.nq.gz
    ├── 121a7c294c2f33b444456341255061d78c4ac9c4.nq.gz
    ├── 13982c33d65f3661e32ff41c7dc6cc1cd86ec192.nq.gz
    ├── 168721190c24a84d77143ae4791867a74db82ad2.nq.gz
    ├── 16ae0865cf04be3497c4e44ef2d7a282952dab22.nq.gz
    ├── 1937e74dae6a8bb56188b84e2eabdbbac8fe63dc.nq.gz
    ├── 193a4934c2311d0a6aac7651374f2c3b0a445880.nq.gz
    ├── 1944c2e0b15c7ad5fbc5c983369f86f050ea5c09.nq.gz
    ├── 1969648cea7806c883b3ff44c0d8500eae552785.nq.gz
    ├── 19b7d1c6355460e7781e508f32795e586d2a2416.nq.gz
    ├── 1a2af87730ca2dd6cb5182a865f7e4730939e975.nq.gz
    ├── 1c3f6c54c7ba1778a0f984f150ba61ea289939d5.nq.gz
    ├── 1e51977940dbf59d64a617232e76bb186269e6b1.nq.gz
    ├── 1f79c6ee0034b60b9919a2aafe5aa8bae9a49647.nq.gz
    ├── 1f8b6180a43053f9a50ac37fe0efa2e9f7c31151.nq.gz
    ├── 1fc60fac69861cbd74ccd6b465f8d3fe0539ff96.nq.gz
    ├── 1fdc828ec782348186761aa59b35b9f390540aed.nq.gz
    ├── 200ed0962063a96f7604fed9bb09adba21df5753.nq.gz
    ├── 20733571b4062317c9c9edded39e1df9a4959dd5.nq.gz
    ├── 2385de53830b41a71b52c4936ed6313b9c4011af.nq.gz
    ├── 23dd176ca65970bee6c7e8be9cff8e24b9abbf3d.nq.gz
    ├── 2440ee6fabf729261d5df57cb1a62e39d41ff427.nq.gz
    ├── 248081605cb3aecdd9016fc4f8c160c780ea2aa4.nq.gz
    ├── 25aad8d691656cc2829893bd238ee4ac40de8d28.nq.gz
    ├── 2653f01fdb3bbf75dbac57d43dd0d557bf4ec5c6.nq.gz
    ├── 285e68b50ae49d1b818350ba0689975c1cebea4f.nq.gz
    ├── 28686e2d35ce3d1a1c573aa144ecc989650183ff.nq.gz
    ├── 28ec0c019af25f422e3b3291cfba1276d5c44834.nq.gz
    ├── 290891e9943860380bffbbde4a2a6e858fe46f93.nq.gz
    ├── 2ace4910a51bdf3dc6e6cd2a2bf5d1e79ea1efa2.nq.gz
    ├── 2c18f93dfb871b530cdf2c7551056bbddc286bc5.nq.gz
    ├── 2c77a698f7edeaa89e0e72e3d70c0cb509a362aa.nq.gz
    ├── 2d558432239833e323391ccf54570c7e5f781357.nq.gz
    ├── 2f48334b2268f43b80618bcbc99f86c5d42a3758.nq.gz
    ├── 2fe7b8cc662e9e81650bfc4aa86cfc9ee5a81561.nq.gz
    ├── 30ee8cd327f54937b021b61ddba310c782330609.nq.gz
    ├── 32cb875d0cfca2f21af19db2e35df9b39d53f5a8.nq.gz
    ├── 33855a42c7a38022f46ba33a5e67577996db48af.nq.gz
    ├── 34673c40ac22dde8d59b6a79634ecd543a225045.nq.gz
    ├── 34c69b15cf7a6f045d231ab18205881b4acb8cb0.nq.gz
    ├── 374fe3cfb060a84bf3e4cb82fe69fa393396c76f.nq.gz
    ├── 38dc70f1da527ad56c4e54e27807183a8caf0864.nq.gz
    ├── 3ae668d1883e4b30f2516882147162a6ab2e40e9.nq.gz
    ├── 3c18e72ba43caa6596e3892c042b72e423e55352.nq.gz
    ├── 3ccfc421e957da7220b1bf6236616b6475c83932.nq.gz
    ├── 3d4460cbb6449bb80d303d4721fc13bd112d02d2.nq.gz
    ├── 3f0fd1c8612493e269279805fa4fed1bd6ffb956.nq.gz
    ├── 3fea9c0284f8f8d0185ad2515ab2a88a9b3e84e9.nq.gz
    ├── 4049ad1cfeff516900396c1bdfc1b8a120a9ff70.nq.gz
    ├── 42d55aab74175f230c8339b87a3d8cddf38b10c9.nq.gz
    ├── 4527257f73de04515d1c3464f6179e80ec1f2f46.nq.gz
    ├── 4605055644a59cf61cbcd0b58267fa925eeef897.nq.gz
    ├── 4ab2784ec838e9e7d2c19b4b33cf1324e666881a.nq.gz
    ├── 4abc3f579a5dd5161c8d71107f18e402855c2840.nq.gz
    ├── 4acb411a64534b9366dee61f0825c04d5cfb49ff.nq.gz
    ├── 4b753943e60a1b7fe32c604158c26bb2a9a3c117.nq.gz
    ├── 4c0ce41a4853c7adce3225f4ffe8f7fa4fead2a9.nq.gz
    ├── 4e25f0d6341d3aff5fb304b83e015ab84d428500.nq.gz
    ├── 4f05c2f3d1ba7b942bca5f18675605d1da476391.nq.gz
    ├── 51eb059078c0e59c0d721fab868d9d7a74e779b8.nq.gz
    ├── 51f84145c17ef609b5bac86b69230b6059e79cd0.nq.gz
    ├── 530303fb6d5759ce3b889244775bd58751b37896.nq.gz
    ├── 550b8088a18b321f5bc6edf82a891ce6f5ad29c0.nq.gz
    ├── 550e5338a204c8d3b2d09569d1e89792d3ab936b.nq.gz
    ├── 554e7f3dbf328a985997a4e2d4df80d4da36a11b.nq.gz
    ├── 575ab9200d3807f825e929a66a6bfd8a96c91d62.nq.gz
    ├── 57e68f4a7047f2144aba6faed41a57ef71b21d66.nq.gz
    ├── 58ca7e8197995f49ea9156ed5313856dfe2011ee.nq.gz
    ├── 5b6eb783ddc76ffdc4016416c00c170dd92c47f4.nq.gz
    ├── 5bb25ad744d31f6f1e078200ed66294dc56f9465.nq.gz
    ├── 5e0269074888b7cf535df6adc060b1182bbf7ff4.nq.gz
    ├── 5ec00eeffcd167056874aeb27783feac023f9077.nq.gz
    ├── 629a0580ecc98681922075010b724c1c7c86a808.nq.gz
    ├── 64ca3a6538a3ca07aba48ab0eaa67d8fe789706f.nq.gz
    ├── 64d5dbbd5dcae9e880c6a68f6cbb797ab739c9ac.nq.gz
    ├── 65cf467ca79a9d4220bb22123cd00b2cbf8104bd.nq.gz
    ├── 68b54e74dd1110b589a48359ddd71e75dce25214.nq.gz
    ├── 694ef7b904a87ae963df3725d3144d4f56d74e74.nq.gz
    ├── 6be8d0da7d6fad3f7265bd970fb1feb5916af34f.nq.gz
    ├── 6ce475d361f539dd8581c3fbda5859b443d45844.nq.gz
    ├── 6d05d31eeb1e94aa27fdb6a617906eb830af1607.nq.gz
    ├── 6d48ea3dae5a9fcf98f206ee0ae2be8770c561b3.nq.gz
    ├── 6e9a460659afb739d03fb51569ea70a180e8a8a8.nq.gz
    ├── 6f38d055bcbdc6a80a8c9a1e0a123ac323be1fad.nq.gz
    ├── 701df228d97e9bf3f2b10c5634107daff2f7bd3d.nq.gz
    ├── 7075ebe22d50cf4fae68fe7f0496ea8761e512c0.nq.gz
    ├── 71374934eb0925fb277b032389d89c940f5f9b53.nq.gz
    ├── 7216a4e770abcb0d1333d76a8ea08eca1e6d38c4.nq.gz
    ├── 7253096967f60e4f11e82312b33ba4a80f454e65.nq.gz
    ├── 72d2005cf162f2d3191f1b9765c5e5e593267996.nq.gz
    ├── 737ee6dbb7e982e92ec57de8497210bf4c9e07e9.nq.gz
    ├── 74d7d830b384c096e65c29b4febbe6cb7e446500.nq.gz
    ├── 7560dae5908e8687dca26415acb5a6bd69b20b13.nq.gz
    ├── 76033450a52b3005d24f3bb1d46c8a0cb1f14968.nq.gz
    ├── 7751858e173bf3d231c10a307ba4da1f82332d04.nq.gz
    ├── 7781c3f96d26f7dce1c10629e7bed3a1af764630.nq.gz
    ├── 793cba8c8b4cae0a6e94b9aa5364054b57a35618.nq.gz
    ├── 79592daaba740db906d7ea41727044316a44aaa4.nq.gz
    ├── 7a315070f64c56de29efa82f060791679376954e.nq.gz
    ├── 7bfffca114c1e62dcc90029801d524236a8d88b5.nq.gz
    ├── 7d81b375dac4211f3dec0434c33031121b7fffe3.nq.gz
    ├── 7de028d2570510c716d3c489c3b8af30e31f3f58.nq.gz
    ├── 7f40f3f635547511875029ed7700c659f40c56d8.nq.gz
    ├── 8008536076a4da2af3bdd69c27d14f5219c15ddb.nq.gz
    ├── 8151ce12f00654d4c0e68b94dd91b732b33d8134.nq.gz
    ├── 833bae3c128b8e6881ec85a1974156ff720a7a91.nq.gz
    ├── 83f36b13ac99148c880d75cb0a8188cd4f5514f5.nq.gz
    ├── 856f2f3b511298ae5d2faaac98ae1d6486a220d8.nq.gz
    ├── 87a7702d4389fabc3d0fb0c97303661c2ffa1f4e.nq.gz
    ├── 8ef06cc40766bad889d937c1190e6ba4ec9ef687.nq.gz
    ├── 8f4c1ae23863033fb7bc1ee5b6a4e5f98de5c784.nq.gz
    ├── 90fc275ce03523eeaa8bbcf32d05c4049fc85052.nq.gz
    ├── 913656cb1e6b89a67f0c358f73d027e4ac4ee313.nq.gz
    ├── 913aca1c5fcbd2ad39de0b6642bce5c122f52f81.nq.gz
    ├── 91b95fc400e56f2b53e232daadd76e336a0b400f.nq.gz
    ├── 9402372c5220424e01355adbda8aa0f40c8543dd.nq.gz
    ├── 9418b05d52a05a22c215dbc9f5604d252b001a89.nq.gz
    ├── 94ac26df4c2ac07e4fc4fb407663ef159785f9c4.nq.gz
    ├── 951ba8be6eb802bd2dc9fa6a84afd8f36b701713.nq.gz
    ├── 95bd2d52bc58a3ebf5f7e31bda0427b5525f7278.nq.gz
    ├── 96aff25b2c288c492d77eebb1fa407ac8c0f3d15.nq.gz
    ├── 98dd175fa480f691404b876cc564ebcaf9358c0a.nq.gz
    ├── 99f4b93abe1e97b2b4ab750cb686551a29154dd6.nq.gz
    ├── 9b3dd7c8f42b0f62516e667ccb4e7a14cb34930e.nq.gz
    ├── 9f2d809b6503f2485ad4b065df31a4360fa80829.nq.gz
    ├── 9f80e87452f461363484ec3d0be4216ec62d5293.nq.gz
    ├── 9fd999bb5e3b5a74d33101260af4c49f22ed009d.nq.gz
    ├── a0e317a6bb48c60820cdf88752db6f561ff33df4.nq.gz
    ├── a1d3bd92fd617f6d7106bbf899a67349cac22aec.nq.gz
    ├── a2b72de682740b9f39531e61cc7efa5b9ea1ab6a.nq.gz
    ├── a3a9320789e3cbbe29232361e4e0de8b7e479912.nq.gz
    ├── a435f4651ae588947dac1c40c64c578eeea37642.nq.gz
    ├── a4927941b9d2033259788293c6e1e277c6fe4b01.nq.gz
    ├── a49c6a26c6699c867e0e42d51823122243fcd5eb.nq.gz
    ├── a657d9aef9f8ff8e73d4e8953408c9c9e3e011b4.nq.gz
    ├── a678e56e3ab6d4108fee45963e7e9e2df0d8a8b4.nq.gz
    ├── a96604954c3e0e91442e3e7f39f86a11bf9fca5c.nq.gz
    ├── aaa5390955b55108db089d555bc17d8ea46785a6.nq.gz
    ├── aabcd6c0a8b0d682c0c1c20c84fb9ea458dbf8d9.nq.gz
    ├── aac55da7e2769b2eae93912c99cfd105f4220e34.nq.gz
    ├── ae5dc39355a519b60bfa6c31f1d77f328ed73b85.nq.gz
    ├── af757ef6203a139e00587132c30b3c7d70d8eff2.nq.gz
    ├── afff59dcf9245fdb114e4ee535548bb33dd56cbc.nq.gz
    ├── b09977d0de96d06d8ba343ba7f0ffd8ae56af174.nq.gz
    ├── b0a7712d9d0cef13ad94726e1343a9a95861919e.nq.gz
    ├── b0bbc6a072df2066dabd1ae1b2794dfb45c71dd9.nq.gz
    ├── b1a77a096c2c93402a6e4247218944d0431c677d.nq.gz
    ├── b1b6142b6d645484003b898a8cae9ed6683cde8b.nq.gz
    ├── b285dc0603e4416b92f79f4aca6401b9c1e9ff37.nq.gz
    ├── b44d0f76d67f780101a59dc4519251cc2320a3bf.nq.gz
    ├── b7fd3c7ac2478e674a8bd461354919cbd36aecc1.nq.gz
    ├── b8286af673b819c34f3e86e33a077ff780493ce1.nq.gz
    ├── b83b67be8967b942667e09a1cf098d608fc0a9ad.nq.gz
    ├── b8eff6de61575257827daa6516e6a582ae6dbfe0.nq.gz
    ├── b9eab83abb46ba3227bca70d2f719a70e502da6c.nq.gz
    ├── bb98962524acda8c8ca2f77752533187a87fe418.nq.gz
    ├── c25f7d5c01e4facac185a043b081ca646acb381d.nq.gz
    ├── c3546b7ec7347b70119ad818f517bb4f2dd1af37.nq.gz
    ├── c3c2d1c595dff68240e0238498a6e4117cb7e12f.nq.gz
    ├── c3c447268ba9b938db97e97999c880a127c5018a.nq.gz
    ├── c5e0713a77192a800e9738f9e71d806d302d59f7.nq.gz
    ├── c65d249e56663349de297104fbd57e41f857c5ef.nq.gz
    ├── c70912028b36e298c067fbc00588b7a872d3a3a2.nq.gz
    ├── c76cc2f868acab1ecdd6f7f3f0197634a98fb0d5.nq.gz
    ├── c8d5f945a01f43995ea181e107c6d5401da61861.nq.gz
    ├── c8e1f70a192b7a61c699cabfef103d16730d7f0b.nq.gz
    ├── c909f324441e41a52ab5185ed1f38640a048cca2.nq.gz
    ├── c968f5af95674e03e6a1975a9c3d2ff9e92859d7.nq.gz
    ├── ca906739191d27381473de85a27fb31540249ee1.nq.gz
    ├── ca9ef9c95ea46612d206e7ced5686fa327b5ef04.nq.gz
    ├── cba11dfe2b1e838ee5eaeb09d007b812f92e4ab4.nq.gz
    ├── cba4d39d0bdf0aaee335ffbb92b292c0f88eb65d.nq.gz
    ├── cce3162646894c84a8af6a5db367e2500ef5e176.nq.gz
    ├── cd703d2ed350b512b7fdcf6d640cb27eecf025db.nq.gz
    ├── cedbd26941fe24222d2dc7f287cdd647c6f91afc.nq.gz
    ├── cede0e8499835b18a07c526707dc442f68fd7848.nq.gz
    ├── cf60282fada93cdd593b5eff11060bdde5fca5f6.nq.gz
    ├── cf6e2e2ee95355039a90146a7f77d14224551b65.nq.gz
    ├── cfececfce3aa6484a39e1e2ea01c508abf0b86a5.nq.gz
    ├── d036f78f5ee079af63a00a761ca5240184bce13c.nq.gz
    ├── d06c133cfaee9ec713925d3d62fcbff52a777fd4.nq.gz
    ├── d1f6036db0adff6cdd5130c19b0a896a9edcc863.nq.gz
    ├── d2ee0c9bb07d78165177ff73791b93c748b7856c.nq.gz
    ├── d6a0b73d703ad5b647bf8598b5cdae7ab225cdf5.nq.gz
    ├── d6cc0657dcec6293a85b08e28c1c0c7480d972fe.nq.gz
    └── d7f17d3d0fc29b4cfc0f24051a2aa5a7d5cec9b0.nq.gz

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

[python-pendulum/pendulum](https://github.com/python-pendulum/pendulum)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
