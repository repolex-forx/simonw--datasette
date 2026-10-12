# Repolex Knowledge Graph of simonw/datasette

RDF knowledge graph data for [simonw/datasette](https://github.com/simonw/datasette), parsed by [repolex](https://repolex.ai).

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
rlex download simonw/datasette
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cf113a59850862125b86ce1a58c117aa21341e07
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cf113a59850862125b86ce1a58c117aa21341e07
│           └── chunk-001.nq.gz
└── blob
    ├── 001ce9b3aef7db250e03a309a68d4019ec720f8b.nq.gz
    ├── 005404645e2a16d2fc7b6b81b6d79717442a0edd.nq.gz
    ├── 03bd9b290dcf7677f6e0792aa47d38062589699d.nq.gz
    ├── 03d6a68fb91996d5c5a0ade7e443edb38e36456c.nq.gz
    ├── 0469d7a8cc5fc38e6215c84c07486724cf763d34.nq.gz
    ├── 0499d086acce1ae4709b7e440ba441595cf887b8.nq.gz
    ├── 049e35ed434268cddd7d933794d0bc7e93035ec6.nq.gz
    ├── 072f32b46d49ebc2af82c9f1bc49d48db5063cc3.nq.gz
    ├── 0a5f9fa6f0e5ccf582db6d65b7984d0b9744f2ac.nq.gz
    ├── 0a6f8799eb1543e7b86f9cab6654174bb79217a3.nq.gz
    ├── 0a908c69aff91da951ee96fa9762eb4be37711bb.nq.gz
    ├── 0cece53b05b24f16a9a6489e38dd8963182875e3.nq.gz
    ├── 0d11737edf72702c5c5a3fcc285598f18b1e1254.nq.gz
    ├── 0ddeb847d1a5db84108f8a62ad98d259d27f5eff.nq.gz
    ├── 0e01f52fccd15252efa9ee9bf9576d1e59599aab.nq.gz
    ├── 0f2f32efd75c2df68227cb27908c17a758a1c37b.nq.gz
    ├── 0f61ebd64caa43abd0b95beb8988021db164adba.nq.gz
    ├── 0fb6a5522e4a1fb63ff1ea8ccfe6e90d04c75111.nq.gz
    ├── 0fba104149fb325e3eccb42f5428198746fecdb9.nq.gz
    ├── 10021ddfd3ad95fc843a467de6d1c932c5e0de01.nq.gz
    ├── 10325f9af1f673992c5722991c92503bd31d5bd6.nq.gz
    ├── 1084d27045dd26a8e9c96527d93aff6436289bb9.nq.gz
    ├── 11a66a13f01781da3d146ed8b3b9b3f865a9bb2d.nq.gz
    ├── 11fd4008174a10d86786e9f5bee31088e3e134c2.nq.gz
    ├── 127ee7db133e7e345470125b97b72ebcb9d92772.nq.gz
    ├── 132f9edf50129645f4db7557e86660a0a2d97f87.nq.gz
    ├── 135aec38a0038b3f24b9d9039e37edeb840d0f88.nq.gz
    ├── 14d4c567dd3e90b667121f87e1093fdf573d84ce.nq.gz
    ├── 159f952d28bb44b976057fd6676394115a4fc519.nq.gz
    ├── 163d3fcca2c7dedf221e2754b3858e2d25020ed7.nq.gz
    ├── 182c7ab128eb8775e4bfc2c2f2ec937fc30c6061.nq.gz
    ├── 194fcf014eacedb6fe03fb8b55750b43fd47a4de.nq.gz
    ├── 1bf17f8ed806c897c89c1cd084a77fdefd0e188f.nq.gz
    ├── 1f79778f18dea0eab241b342de7b2418bdc85186.nq.gz
    ├── 1fbda6f942886d25960b8b0451a505b1fa02c7f5.nq.gz
    ├── 1fcc93b036636492147de78cbb6f915f8b250c6e.nq.gz
    ├── 1fceeabef0fe9fe2cf3929823feb172d88dabe84.nq.gz
    ├── 213999c14ef80d54ddfb51a1d3811e96c6518e4d.nq.gz
    ├── 2183e70b0d6ec307fa6db7107b0880c4fc7b7db1.nq.gz
    ├── 21cfa95293d2d98c989c4ddc093fec285ceed591.nq.gz
    ├── 222861c341540db6785e10c2b6461d5cbc94a6eb.nq.gz
    ├── 22d13f65cb6deb88d723433bc834e0ffb22d5279.nq.gz
    ├── 232a34c75f3470fd05db1bb0172628227a4f79fc.nq.gz
    ├── 232eb051535e5a930ec9dec149642427558fbd86.nq.gz
    ├── 24a40cefff7a02cd0adabea25dd5cdaac087f0b5.nq.gz
    ├── 26e45a5b135883a9b50d7a54553084e832fa1676.nq.gz
    ├── 2705f2c587539255a608dad67b8b0e46e77a4ff8.nq.gz
    ├── 2775cbc530cb8f2ef598304277562d7b89626b86.nq.gz
    ├── 27abd0cdde44f4db140024b7bd637cc9ca6b4eb0.nq.gz
    ├── 27dfd4bf4ade2142073fcdff4930334ae402874a.nq.gz
    ├── 2846590a5196adb23249e6dab5149642196c6e6e.nq.gz
    ├── 29046dc34f5ba99f24b4b900b3d13f6c3d4e7961.nq.gz
    ├── 296ef55d44aa9fcd67cefc407339deb7e3a54e79.nq.gz
    ├── 29729f273a533591d67d0771623d4fb5cee1fc74.nq.gz
    ├── 297f5ae551780c057e78de9d4c325e72a3f47705.nq.gz
    ├── 29bf7b1e387c53659291dea4fb78f59f2964a6fd.nq.gz
    ├── 2a5c1439f6b8a511815a21fca90ca2142e7106a0.nq.gz
    ├── 2a7f66201abaa531a3e9465d972783b7345a4dd5.nq.gz
    ├── 2ae1be9ba8274a5dbbfb6f66ae4e0c2f1d08ccf4.nq.gz
    ├── 2d2425605d3e2bc898762fb6cbb840bcb892b5d3.nq.gz
    ├── 2d4086b3d2b3cdee46cd468883cc731a97faba71.nq.gz
    ├── 2d4a6cffbc8a773d7be0f8b207ef3b05532456a2.nq.gz
    ├── 2de1fce06078a83fd7fc4394a11d1e241d7a28cd.nq.gz
    ├── 2e465b82d18e9a1f7e0bec1fb14de64af610c93f.nq.gz
    ├── 2f20e8e8ee1a031a833fedad048f7b902e3affb2.nq.gz
    ├── 2fca1d6648f6ff96d7860a3769e3566c2c288afe.nq.gz
    ├── 2fd5a9dcea47b2498115cf08a56a132655ae5364.nq.gz
    ├── 312294c15e2328979af3bef05e93f1d6dd9a6b35.nq.gz
    ├── 32cfc43d6e4543c6472e09f452713b027bb9070e.nq.gz
    ├── 33a8343ba4d455c4473e8a454f12ac158e0120d5.nq.gz
    ├── 34d81594b36e558f7bb0a8beb0c4cce7ad50beab.nq.gz
    ├── 35b4dcc6d3a69f1b4ec9f59381171615f8500a2e.nq.gz
    ├── 363814d7a4cc772c95e4b6c9ea49b38d5668ad4b.nq.gz
    ├── 3a25ccbce35582babf3d48c6aec413f46a47c7dd.nq.gz
    ├── 3c4345bf48f1728470f4322196b953da5083dcfc.nq.gz
    ├── 3efff7a4ebe35d3756e4eb08dd9e5265f311962d.nq.gz
    ├── 4302ed94a8809617df17913796f5deb460c97c07.nq.gz
    ├── 43b20589f74c071bc94d3fca0f3cb13cef1ae086.nq.gz
    ├── 4427757c01ca0146a78514ff7a6e3e7a7d9bfdf3.nq.gz
    ├── 449855f388b28baf2df743ad7b493d14cb6a3a7b.nq.gz
    ├── 45eea4833e620f0952738801343b8115d92cb314.nq.gz
    ├── 45f9854b9449bec6c4141bfada27ba6ccba5d316.nq.gz
    ├── 4993163f703c425c6512dec380dafe2ca52051a7.nq.gz
    ├── 49d8e8ea22069ca5ef3c04cb8042a97f8afae2e2.nq.gz
    ├── 4a0014b4b32d3faf4a95e7b6d15b0f6102a256fa.nq.gz
    ├── 4adef844322dbc40b460b38b4e5ee58cf1d0a960.nq.gz
    ├── 4c6e44266f42946287f515f27dfafe4e7d95ee78.nq.gz
    ├── 4d29ab67e89f50a5e8a3c67b6e53d1bc8f344695.nq.gz
    ├── 4dbcf5cd05451ace1e6f903b6374c426df899097.nq.gz
    ├── 4e0089268fa4b98d19aaf04dda1c3199ca263852.nq.gz
    ├── 5078bf4795fdcbd0e4307e3e35a3610c29bf833c.nq.gz
    ├── 50bf1d676ab21cdca9c235fdf1f146d338dfb886.nq.gz
    ├── 50c61995617acab286edd5dde36211a32f98e8d2.nq.gz
    ├── 52daf8a2476c8a0cf55db0edd22bb5b15a12a89a.nq.gz
    ├── 52e6af5d91c7a4da397dda030861415f4d628ae2.nq.gz
    ├── 542b3012dbd0c1c923541cb1dcc06a8682f6314b.nq.gz
    ├── 562bd7aafb545dadd5eabd450a251a04120069d0.nq.gz
    ├── 573726136aa40a2fcd0954d53ce7a455d5ea7daa.nq.gz
    ├── 58287dd741e7d9cdce4b81c5195a5c45dc44fd60.nq.gz
    ├── 587380ed15a54bed3a1f381237202ec497091138.nq.gz
    ├── 58a5ddc3ed53b116c71d1cd7be810e11dff529c2.nq.gz
    ├── 590054de40c9ecb26a02a38652d5bf5b132de89c.nq.gz
    ├── 5a8ee8e23be10cbea8bb1fbd8a732bc404a5ddbc.nq.gz
    ├── 5b6607a3b0fd0a14fc5c0a7b0121f1ccb43ff408.nq.gz
    ├── 5b8818c3488ef6a339eac8378233d9ba3f6919ee.nq.gz
    ├── 5e59b7b4c6020d458ad5557c19ec5af037841d00.nq.gz
    ├── 5ed2c12a7f2459b5887b76e4c54175e3b3aed5f1.nq.gz
    ├── 5f3fd06eb6dd4aa7566e270a0f23cad3e3abfc9e.nq.gz
    ├── 5fdbd51dbcfd8c73c55bc1fac2cef9f83af2a10f.nq.gz
    ├── 5fe970d9e12cd754f31d001b9fa35e59cafeaac5.nq.gz
    ├── 60eb7938d55c9d87056e491855a6cd1a5a0350c6.nq.gz
    ├── 6325e890dca212961ee51618795460f101cdeba8.nq.gz
    ├── 63d5b89b7d449efcc8f431fe772f9a053dd8c312.nq.gz
    ├── 64f28946ada86870bf83fa91b9eb8ed9b8b14ae0.nq.gz
    ├── 65c03a49ab627bef81dfe72f5da8b51cff1c99e7.nq.gz
    ├── 665ed32acb1c4bc2f0ff86b975c41f1aad2bd473.nq.gz
    ├── 669d04c732a85b7a19e0e86554c212e6c497beff.nq.gz
    ├── 671f2d1e28d03e8622a44ffe03af4d39b1244eb6.nq.gz
    ├── 67bf0d8bdfb1f27468e225050fd7f2975e394288.nq.gz
    ├── 68a2e6fd3c014a92089cd5f699ff906b97fddaaf.nq.gz
    ├── 68d4a5045bf07260eee4c0854ff238a4883e306c.nq.gz
    ├── 690cb080b617c8ff9dbc45fd2de7abcb3d2f7aa8.nq.gz
    ├── 691c2d642c48c6c6ac96af43c3cfe9e360fd4254.nq.gz
    ├── 69ac2c42fdebb3d715271da20c320ce6adea6950.nq.gz
    ├── 6a4d7da72602844e675224318c51f80dcaa8cfb2.nq.gz
    ├── 6b34fd850431f78a2531ec8c1bdb07b30a1e4c06.nq.gz
    ├── 6b52f8011e997ad836628874d625f33f62d88b92.nq.gz
    ├── 6ba956869d3e58b52eb1de87f2a44b1c9697e5f9.nq.gz
    ├── 6bb822e0053932e86360309f6cae7562e2f9dac1.nq.gz
    ├── 6c78f69d2f07520b943ce3e85e9ce45cd891c004.nq.gz
    ├── 6ca0fac86b44bf44fbcb54be390c7a3455fa5a62.nq.gz
    ├── 6def369848717b70d32b979cd844ce6edea30d12.nq.gz
    ├── 6e633ff6a1c5deb1a21cde64b7831d481fbc83b4.nq.gz
    ├── 6ebf10b91a5efb4d59fdb331138b63385ccc8e02.nq.gz
    ├── 6ecf5b7313e25068ae9e9c12248e1c5ad817b719.nq.gz
    ├── 6f3437d52a08b04a334466e27fb974b6ed486732.nq.gz
    ├── 6f97812bfda9a5ce41442b1aea05edd8bb663f6d.nq.gz
    ├── 700f3cceddfe5cbf2eb7e428f76ae10126eeee3c.nq.gz
    ├── 725d9cdb24ddaba69093e05df40f285a791fb76f.nq.gz
    ├── 7262edb4083fe06e2a198e02b30640e04646057a.nq.gz
    ├── 73212e703b0bfc8961055b9f0b0d0c5d0e475f22.nq.gz
    ├── 744258eb921d8f3b1ca0cbc4e315b5804666c811.nq.gz
    ├── 7503f1d513365477b3d4cef921ae4ae9f883e2e0.nq.gz
    ├── 75078e43c730f651cf9db0755ce9cffed68edbca.nq.gz
    ├── 76320bd11261d909867d57c92f6d6218779a5024.nq.gz
    ├── 774064fd7dab889215b4787feee3d4d5094dd32b.nq.gz
    ├── 77a4431be0213148adfa68aad5a71566e8c2ae79.nq.gz
    ├── 79f840d2d4f4024b8dc0decacd837fb1fa0a8018.nq.gz
    ├── 7cc9dde2086a037bacada7116d33af420ed9cf8b.nq.gz
    ├── 801876df8b31eebd4710c949e87b22ca6757e777.nq.gz
    ├── 808feea78a22b7fa8a21717135b6188739410384.nq.gz
    ├── 8176a63015f44f056f6c3e4a025e23e8bc2711c9.nq.gz
    ├── 81dc90dc0a97a9876e99a354590aaf609171070f.nq.gz
    ├── 8327ecbf655e2177e749277327ec105d5eeceb8f.nq.gz
    ├── 84e574fd9fecea7a85652c07c44fb98f564c57d2.nq.gz
    ├── 85369f6c8228ec18144653446be4f19093e8ef26.nq.gz
    ├── 857b73cdb1180b76b3639c4b327570f63c93818f.nq.gz
    ├── 87360c321dec70fdbb0ee8cbdef57d2c5fa1117d.nq.gz
    ├── 88bb03b1abe77716779ce90f0f309c27460154dc.nq.gz
    ├── 8957fe832f1a34c4d8c6eeb189285ac98124360e.nq.gz
    ├── 8b3e54aa0431d06698b017b81d4c199315733c63.nq.gz
    ├── 8b627cdc8f9acbd59063ef603415a454680fc54b.nq.gz
    ├── 8c19d9a6205ba7f976c09a99d16f6bc0a1719510.nq.gz
    ├── 8c5e3ee6d68f09f21094ae709c730bce7ea3d52a.nq.gz
    ├── 8cc91db3170b159abc00dacf4f161333e3af02ae.nq.gz
    ├── 8d7fa08e4c44d8404a9e121e77883a0f01c47828.nq.gz
    ├── 8dada3edaf50dbc082c9a125058f25def75e625a.nq.gz
    ├── 8ea3c2870b7eaa64612602aa0df6d3a7801282c7.nq.gz
    ├── 90ed925fec4685652e338b0845fd19a14f90d942.nq.gz
    ├── 918dab95553db221c6c4841ef747279f04aae6d9.nq.gz
    ├── 91c3e306beb1c687f1e707fe7a1fa69eb2500ee4.nq.gz
    ├── 91ef368f5b884739d3e6a485eb20f87b96cf419d.nq.gz
    ├── 926722a1bc2341750214e3eef81912db3298f985.nq.gz
    ├── 927b2c2d7332fcec7482f9ca0296f758eee1b5cc.nq.gz
    ├── 92e75199babf95af3256d560996059944740fbdf.nq.gz
    ├── 92fdd96985ee95ab51f2b32e2c4e702788e7aee6.nq.gz
    ├── 9398afb907a8f5173e442c5a5e5a370d8f0e095c.nq.gz
    ├── 94c9a7c960b0e3ffd98f4938637c5cbb3691087e.nq.gz
    ├── 95b4b52ee8fc83bbfa1e0450934064c7958273a0.nq.gz
    ├── 95b8a366a8637b6f7975f72dc120b21797e10c7b.nq.gz
    ├── 982dcc79814ae01858438bb2bf4f9e4e188d9857.nq.gz
    ├── 99d413fc2db036b1c88be39fd20a7c1895f48e95.nq.gz
    ├── 9a4dba23defdc18657565d4f4891d5ccd5f3e9ff.nq.gz
    ├── 9a8448daf3fe4646aeca49adc6a53ea074ab98ac.nq.gz
    ├── 9ace865bbdecf8ddb154d804faf1a13abda39803.nq.gz
    ├── 9b17d24b77f9bebd622f5675e19c15a9e6e74f9a.nq.gz
    ├── 9c4086aeaab0a4d48e84580c68dd0abc5203c7ec.nq.gz
    ├── 9c95dc7900eaa933469d384845ddd1fdae00d633.nq.gz
    ├── 9de7576f76f93b4896a8a6c87be6d77242c73b13.nq.gz
    ├── 9f201fdf0e47410989bf051147dbec8a67d8a9fe.nq.gz
    ├── a0d17c816e17e5a52f87a69379413ae33c33a842.nq.gz
    ├── a4f5a4de390a58f56d0816288f7cae7e53604053.nq.gz
    ├── a544b9a833e15d60725d4e33e89f786151ee6a47.nq.gz
    ├── a62f94730d65143159de91999fb2c1aa7bc315d6.nq.gz
    ├── a6782c551e65b6f6f157f23ee5eb703ed79c160c.nq.gz
    ├── a7c2bc24257dca411310f3086c3f9f1bf65147f5.nq.gz
    ├── a8ddf460c95cf1dce7c7c0c8205d3e0073a59c96.nq.gz
    └── aa35338ff1c1ba3e7a56b57d3f5af841857a3324.nq.gz

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

[simonw/datasette](https://github.com/simonw/datasette)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
