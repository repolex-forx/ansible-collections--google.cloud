# Repolex Knowledge Graph of ansible-collections/google.cloud

RDF knowledge graph data for [ansible-collections/google.cloud](https://github.com/ansible-collections/google.cloud), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/google.cloud
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── db65ab6d6f3b7449fedbdc7167efad4f36bf3493
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── db65ab6d6f3b7449fedbdc7167efad4f36bf3493
│           └── chunk-001.nq.gz
└── blob
    ├── 005d65503515ac0df5e36b2051cc8018f6c86def.nq.gz
    ├── 019372d6c2b86412bb6c69a5af42146e839243ff.nq.gz
    ├── 021fae06d2cc25145926f599b95789529b5d1f00.nq.gz
    ├── 03df99ee27b3d8d3eeeac2f6173de147b91a83ca.nq.gz
    ├── 057a0b6bc99aa684d93bffe9fb9a48d459b732a2.nq.gz
    ├── 05c57644dcb13f19e6b66af5590b4db8ab7fd487.nq.gz
    ├── 05cfe9999fc55f87b548e5829624150f17b79abc.nq.gz
    ├── 0662841d40871e1d46e34307e9476c42fcd48317.nq.gz
    ├── 073655bc48ec991af932e576d6cad2889ca0ccd7.nq.gz
    ├── 0779728dcb0602ecceab05020a82ec96bcb4c34d.nq.gz
    ├── 0af89841dd571f4416c83a54e9af6308d2b4ebbb.nq.gz
    ├── 0b868692f4266348aa4b35aac8f6989778899929.nq.gz
    ├── 0c70745d126d2a7a537f53be2c21fcc87525203d.nq.gz
    ├── 0c764112adc62e14ab1b9967f9e91f6583f476e1.nq.gz
    ├── 0d2a092aff103ecafd900ff0f3e7270cc1699698.nq.gz
    ├── 0d30dba1f45f97adcfcf5c6099f454a9ec98fd19.nq.gz
    ├── 0d31fe73fe8a8c57bf64e9b7479216aa27014a74.nq.gz
    ├── 0d34f20aa804e1665c67b7c03ba8e17832a741d6.nq.gz
    ├── 0e092c8b6390f18d83dfccfdaa95926936933a45.nq.gz
    ├── 0e4419e32198a2c5c0812a0e6b692439e1ab2a9d.nq.gz
    ├── 0e619dc7e3a9a161b63578a29f330b59d6c7935b.nq.gz
    ├── 0eaa71245c47c83fd6872c69a31bd4ef980899ea.nq.gz
    ├── 0fd69eb233050e4be457ca915e30a765f28d948a.nq.gz
    ├── 109d3051fe7757deebe29d4eaf03a48119ed5d53.nq.gz
    ├── 10f1ec11749f106e83fb1b4a22263f202b85aeca.nq.gz
    ├── 128feaeb5beb3b246027e09861d328282c8a613d.nq.gz
    ├── 1315d6e8e1fcdfabeb2940f6e94721990353925b.nq.gz
    ├── 13f55f2a30a71839f1df67db5bccaa160821edb8.nq.gz
    ├── 141c555a0def06952cd177b276a61858387937bc.nq.gz
    ├── 14269007abf9c1cea8dcc0699076441c7257e92a.nq.gz
    ├── 14bb67283934cb8501f5e5f6c5fd0c2efcd04cbc.nq.gz
    ├── 156d54563e91562e2b9b7fa609373f9e1e553e9f.nq.gz
    ├── 158caab882f9436f0720ea5c7f9e262c18e8e266.nq.gz
    ├── 160a3c9b76381c64516e57725a4bb330583225a3.nq.gz
    ├── 16fe372631d85b324050835ee424dbbd4e96166d.nq.gz
    ├── 1719a90d142674db47a468c49d47610d80890931.nq.gz
    ├── 174ab473f8ce2dcb75bee71d1b16b17f4f50ad1e.nq.gz
    ├── 175533b5a041f6f9a63b2e3870ebb62326e673f9.nq.gz
    ├── 175dab858ace26ecf3547043ff5bf490f61bf822.nq.gz
    ├── 178352eafc3b3135115829dc27fd3894ad18c526.nq.gz
    ├── 17e6a92649a78c7112c5de0bc1decf079feb61b9.nq.gz
    ├── 1879840af2c613ad44a2a130a442b32db1c17ff2.nq.gz
    ├── 18d666280f71897deba3fb2d98f821f623ba822a.nq.gz
    ├── 193d32c7de4f81924c272b2d8aa871ce9a6b7f9c.nq.gz
    ├── 19ba5d56361a07d5ae52a890dbaf5e2995daec39.nq.gz
    ├── 1b76493e58da4d7769d45a1aafd66b95a2d4ec9d.nq.gz
    ├── 1bac434c98827dd6c414027bde93ca61033a5d70.nq.gz
    ├── 1c26d12f321be5da2e2237414745585247846db5.nq.gz
    ├── 1c52070d222249c774c6c932f352371f0b1ce252.nq.gz
    ├── 1c55662b943133bac091e761f7aab5f228ec7c5b.nq.gz
    ├── 1cdadc8425ee38da9f4dd56feac297afd865ce2f.nq.gz
    ├── 1dba0a71bb119659b9768a0dc2e729c46aa6c4a7.nq.gz
    ├── 1def020b15797de5a84535478dad9a5b19cc2586.nq.gz
    ├── 1eb98f1ddf66aef2036a2c5ee30983bc528e6016.nq.gz
    ├── 1fa069d136cb2b243417ad64b773e7b153a08fa7.nq.gz
    ├── 203f2e2c3c9444eed10f229145bf14f93e4e98c2.nq.gz
    ├── 21259acbb717c02f969007a271e21f9e17512d4a.nq.gz
    ├── 226d68d680333807495cf77b53fa30eb6cdf0d52.nq.gz
    ├── 22815350c3760b063713208d48837b6df2d48b5a.nq.gz
    ├── 2302e066f37903ab51e0c14e7a2e8fa516278258.nq.gz
    ├── 2440c4c870f4eadc68513d1872773f3e4a006f23.nq.gz
    ├── 247b4e8abbc68cce3a0bae40b4e4e77f17ce841c.nq.gz
    ├── 250ced00f3e5763bc4f266799fea66a35ce44c8c.nq.gz
    ├── 2578c418512979c82f4ddd5dea062f71b80df38a.nq.gz
    ├── 25cc92909f2afdc074452b10837753ca2c947a4f.nq.gz
    ├── 262895debdde2b3a8b3fff0afcadd74e2c4cdd1d.nq.gz
    ├── 26507c23cd3ccc21559ec096dea94604af923d60.nq.gz
    ├── 27139828cec63e0b42cb6696164422a812fa45a8.nq.gz
    ├── 28fdb08106d35e23e12de0cdc924689e550841a0.nq.gz
    ├── 2aec1fc2cbff618854cdcdf1563ce0d61bf653d4.nq.gz
    ├── 2b0d2ee969ba94978337ab242038a36418e9a638.nq.gz
    ├── 2c99fc7063ee2b1bd07437c7929e1c0f2b4e4b3b.nq.gz
    ├── 2cec554e8d915496d407c159ecbfa376f527c669.nq.gz
    ├── 2d025192a004cc1a0ac510aa2e05a1032d6fec56.nq.gz
    ├── 2da6d4d1c5ab9c091abcef4ab53120e760d54493.nq.gz
    ├── 2e9ec18bdb8851d74aad5e6a7cf332e6be4642ce.nq.gz
    ├── 2fdaa4951866b42c31ed1d7ca5191a4e08cd8f26.nq.gz
    ├── 30e822f6228a9bfcb3a923c41d50b5e54cee258d.nq.gz
    ├── 313a5a2ba7ec9c8bd1c5172c6e0cfc3ee671d544.nq.gz
    ├── 3155f817c18f056f9c9053c35154d499e8339217.nq.gz
    ├── 32434af944f16f4d43e2f181517e005ffba7172b.nq.gz
    ├── 32e41f75805cdafdf55faee68b52eda8c09e7e76.nq.gz
    ├── 341849bf963ea2ed36bd0664a7835adab17afe97.nq.gz
    ├── 34b3921c0743b0eebad6f0ca3065746075116d66.nq.gz
    ├── 34e057869736a0fd98f5a32f21bf342219a3bbd3.nq.gz
    ├── 3506830c5181eb228a582f72218638f67cbcf69d.nq.gz
    ├── 35318c2aa217ef56321245d0ee0de2bed852973d.nq.gz
    ├── 3575898447a9c923f762380c94498e864d20d1ea.nq.gz
    ├── 3648e29e111c5bdf22666909a4fa5756864ef295.nq.gz
    ├── 36fab9e981c36479e962f49004020baa6af7b24c.nq.gz
    ├── 3704b90907cc73a0fabfb5eb3d717c04d743eb2d.nq.gz
    ├── 3748ba3f3e64e9bdf40631bba87d8846bbd516b5.nq.gz
    ├── 377b5f48ae243748e32b593c0b2df330dadaf72f.nq.gz
    ├── 37aace006bb6f50b52b6446833ed44fb653839e7.nq.gz
    ├── 38cdf9405cdfc001ccbac0fa7e9b9b4bb7672951.nq.gz
    ├── 38d4b62f0ca7ccd8eebf2f28a07a60a292d10fa2.nq.gz
    ├── 38f7c13f00e10824d62a84c3843a02e5ffe24e23.nq.gz
    ├── 3a921857f4734a7dbe8b6b238960273bec788dd8.nq.gz
    ├── 3bee9adb2514442807cdd9fb3e0f0a499bdb56ed.nq.gz
    ├── 3c28f98c182e2e0b1b71f2b3bd3cf03f8e2a202d.nq.gz
    ├── 3e160f204fb97779b0e9ab1f35a1b42b527c2b8a.nq.gz
    ├── 3e90c212d213701c493afa0ea86d5eaef50fe26a.nq.gz
    ├── 3f5dd4836d626dab84338e242a4fceb4f623caf6.nq.gz
    ├── 405ad2af2ea6b1c5402f58bb8af47e662167cbc1.nq.gz
    ├── 40d0ae23f14ba5f3d4fbca4ff3374e8006224978.nq.gz
    ├── 40df4f65a9fbc3879588021f8d0cb2c22d20e6ae.nq.gz
    ├── 4115b62b04a725250c39f560ab94df530a6114c7.nq.gz
    ├── 420b59346e650e39090be3c70f87eb6ec45c1114.nq.gz
    ├── 4225d2d3325bad1682b7c66bc56052540c775511.nq.gz
    ├── 43cae101efcf300ed3e274306ea30f4285471ea3.nq.gz
    ├── 43f9b8cf7851af8f63708eb1bb294beead5f89e1.nq.gz
    ├── 44cf14c4bcc9e1a3a4c737bd51f77655bd7e36f0.nq.gz
    ├── 45066850842d84e81be0900f71a2c435477d3be4.nq.gz
    ├── 4597ca3affc5d7ad2ced43056765a74695728478.nq.gz
    ├── 45c119eec639a817c6ca2d65304c1d8f304230fe.nq.gz
    ├── 45c615f0c496f4cff608772523f3e77507f3bb68.nq.gz
    ├── 46391dd32f790f987cd3f7735030605022378dfc.nq.gz
    ├── 463c88458eb6680b225e9abc15a0de505013fdea.nq.gz
    ├── 46df721858fafed3ea48c2dd5d15f16e75d29939.nq.gz
    ├── 46eb0aef60323607c7aaca84cf5991f128f9cd88.nq.gz
    ├── 47c5b9c88c42f2afeaa5bf0e409b393b2ebe9554.nq.gz
    ├── 48118c120e09e89d7dfe79fb07ef161907f874d1.nq.gz
    ├── 4829081f2953b920967646b7a9f193392d1cc905.nq.gz
    ├── 4846e0a0e2987e7fc7a0057a478f3ed183f59fb2.nq.gz
    ├── 494b2aca5d68c4c1e8556172d192ee701b6bff7b.nq.gz
    ├── 49eb87298c2c040654e6038a79694b92299d519b.nq.gz
    ├── 4a08c1af3e91e75ffb4aa328afb33c03dc4c0aa1.nq.gz
    ├── 4bc6393c452141687943aaf984724c342be361c1.nq.gz
    ├── 4bd92583688d4674041ace4e393fedd6ff7fec74.nq.gz
    ├── 4d06ce289c53d116b90ec9a97789862394f6fbfd.nq.gz
    ├── 4f63add3b9c82556d7c06240ef17637a91c57571.nq.gz
    ├── 4f95a7a4869ddf6692c458c526127fc156ea9c32.nq.gz
    ├── 4fdace79e24533bf10f7c8ae575a29936119f951.nq.gz
    ├── 5083cdee10b571ff82de0027ce7db91d984305ed.nq.gz
    ├── 511f8b6eaa200beaea81d895eb0ca62e7fb60c68.nq.gz
    ├── 517d2fea43ee839f39989acf9676791c166056c5.nq.gz
    ├── 51d2866161d5ba6dffb193d794064304cb9533dd.nq.gz
    ├── 51e3cf7c19628bd11d89e14f5902a099ab85deea.nq.gz
    ├── 51eb42562d0e5c2dfc9940522e92a693235101a5.nq.gz
    ├── 536c838c4ebdb286f091796eac5f9ec3ef4a302d.nq.gz
    ├── 54171d62566f55a04c9330dd30bf275466c5d275.nq.gz
    ├── 55fd596bba2b93c20c9ed503924b670edf941bc1.nq.gz
    ├── 566d16b4984f5e964cb5acb678aee1a40d14fb0e.nq.gz
    ├── 56822582e1b56ef58bbf49baa9162581fa197b8b.nq.gz
    ├── 568fff748a1020f08a6240beb2541c8b7e2fe0f2.nq.gz
    ├── 5707d37a90ec300f4b71519e6b35eadca32aad61.nq.gz
    ├── 581af9d29d3752e3ab6384b189834e7bf11f6fb8.nq.gz
    ├── 584dc65a300cd14f9ceb9d48aa12c5e0f8905785.nq.gz
    ├── 5893d7e17bcfc542f1d12c285b73a70be6bfb9dd.nq.gz
    ├── 58c2db55d8feae14fb18e20e0dce4aa7d06b2de9.nq.gz
    ├── 593b063f2c37022326de15b60583d72da46b8a9b.nq.gz
    ├── 59763e263b3b188724dba194de3b00e6fdc3eda8.nq.gz
    ├── 5a5009c452e87149338526d5632b75fa721b63d3.nq.gz
    ├── 5b53dd2a924fc4242e4a6e8ba552ec1200f6eb6d.nq.gz
    ├── 5c1c5416bad584e462b202cf4adbe4cbb04593af.nq.gz
    ├── 5c6ba660a86726fd6d0b748dc139be9e68ef74a1.nq.gz
    ├── 5c8007ef8cf8dadeaaded5028c610654b0fc3b14.nq.gz
    ├── 5caf7c2960c78d6114db2fa21b5e7079905a5c79.nq.gz
    ├── 5ce6d4ca7dcf1bcc1654cbf5eb4896b980d474c5.nq.gz
    ├── 5de307c26842292e21ad662ada6b1bb3c61e4b58.nq.gz
    ├── 5deac092bb0ddb451d78b62180283f99da26d06a.nq.gz
    ├── 5e20e5a1f47d40577c5b9fe1dc9befd8cf068ce2.nq.gz
    ├── 5e92ee6bbe831f92046888d99788944da74d6e81.nq.gz
    ├── 5eed6deef8f2ef05b7258df9457c31d20092d861.nq.gz
    ├── 5f062306693bd345297a07a8c2c1d743f82991c2.nq.gz
    ├── 5f7f499ef854ed9faa6c1c78439e5c54dd95b62d.nq.gz
    ├── 5fe4415c997fd405c1a253b71131d104214ae38d.nq.gz
    ├── 603b1979a88d5b813a61cb06569547776887f290.nq.gz
    ├── 61bf28a9555f5ef413316b050d3cc26761e3aafd.nq.gz
    ├── 61fa8b0472b65690349200edbb5b86d101eba2ec.nq.gz
    ├── 621b84a4cb7162879fafeef89cad895a2e0f4d6f.nq.gz
    ├── 6298493c50a77b195941414e853b1adac519b65d.nq.gz
    ├── 62eed9efd5d1711d08c9bb85eb8fd51f443c1418.nq.gz
    ├── 63fdc2e1f8ee96a3437b6580cec47e0821ceb6e8.nq.gz
    ├── 6443072f475e4fe1da3c2ccebdfe66c6ee49f451.nq.gz
    ├── 6483a721d4cc6851daf231f777bf6fa0336cfdb5.nq.gz
    ├── 64a62fda6d7bf1dac3c5f953c222dc45a3cb7d2d.nq.gz
    ├── 64bc7a00b3a9ab0bb185a648522f6590a1dddcda.nq.gz
    ├── 64e68c480943cff9eb1b82fc5dfaf833994feed8.nq.gz
    ├── 654d37775b2eda23ef75ac4a00dfdf1d5a05c7db.nq.gz
    ├── 65abf77315c2de229789610a0428d101f215b424.nq.gz
    ├── 6748d0c8e1739d73f2737e37b686f63698ffd662.nq.gz
    ├── 6758587aab33fc5aed59c64533405445fe3a6f2b.nq.gz
    ├── 6775944c2abbc0cd42626230cc854316a830fd73.nq.gz
    ├── 67826df41a10ae87d471042080baca157a4a5e10.nq.gz
    ├── 678cb6a65f9cc29f853e619c6c8726218a61ef0d.nq.gz
    ├── 67f71be7060d8b793a105fa23034d33c10f66dc3.nq.gz
    ├── 6866bc511fa93d6b77208ee2c5b2828908e96256.nq.gz
    ├── 686886dc08631fa088bfe9b4420ba13798505756.nq.gz
    ├── 688019463cc9ad07c6b21fc43d4e8f3e86be4b0e.nq.gz
    ├── 68a2fdb90f5f6f9a514b9a2d26449fa9013d3d00.nq.gz
    ├── 68af24e6f6e661dfbfdad40b99a7cecc8863def5.nq.gz
    ├── 68de3cb058d40a9bd0721a55b35b043d05fca2f9.nq.gz
    ├── 68f9de4ce86afb948c9b839d4e45c88d7d9b1b28.nq.gz
    ├── 6aa2c285f7599037fa470e04b8016c199f998947.nq.gz
    ├── 6b25b42689ca1e7b5d070acce6bde19efbfb9f1b.nq.gz
    ├── 6d4cca95693e3f616ed2beb7afdc91139161b61e.nq.gz
    └── 6decbc8ca7cc9b90641ffb3fc048deafcfb79aca.nq.gz

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

[ansible-collections/google.cloud](https://github.com/ansible-collections/google.cloud)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
