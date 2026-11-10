# Repolex Knowledge Graph of Azure/DotNetty

RDF knowledge graph data for [Azure/DotNetty](https://github.com/Azure/DotNetty), parsed by [repolex](https://repolex.ai).

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
rlex download Azure/DotNetty
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 379d8cc1d32d2b557347aad1f7b6c48656212a4b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 379d8cc1d32d2b557347aad1f7b6c48656212a4b
│           └── chunk-001.nq.gz
└── blob
    ├── 00e595d7197cb84ee49ce01001eed01adaddfdd0.nq.gz
    ├── 01c9d6bca38774f1e9b05bbb8d2b8824245b5633.nq.gz
    ├── 02e315cdddbc1d60df976d9a92312d2b2bd0b67c.nq.gz
    ├── 03e7a99bc5643b3d11a6bfeaa4e7690a147d215c.nq.gz
    ├── 0424a3d1ef9366838b6da6904c9618a4016ef89b.nq.gz
    ├── 046a6359178ca3779277b036c89fe35aa437e0b8.nq.gz
    ├── 049b2dedcbc299228459eec1d56b05211f1a7c7d.nq.gz
    ├── 04b2f7c6fd8cbe6594046b7400f8b20b9505ddec.nq.gz
    ├── 04d7cb930428cb402615a516484a216266f83cec.nq.gz
    ├── 05081a47e0c56b387e3101a6cb0bd88685eeae22.nq.gz
    ├── 075fb6533015b9e42e2f6c4b5ff73ad91a057ec1.nq.gz
    ├── 08093dafbc32ff835982b7a203070590f9153ca4.nq.gz
    ├── 08523ff0b193e54c7f8409999d0f46c871bd44fd.nq.gz
    ├── 087575cfb91702d4c05305cbaf73d2c9640f7e7f.nq.gz
    ├── 0890a34352d0809d48f7652ae89adda3f997264a.nq.gz
    ├── 096d2a84f9cc9793b512f693f04a184a4dffbd35.nq.gz
    ├── 0a61d06649b0a67c6466bee634511c9c9e80832b.nq.gz
    ├── 0a72fcb677e3ed568ec92681bfc12341597c6828.nq.gz
    ├── 0a8e765e3257bc07a7e28ca4c1fc5e85875fa6c9.nq.gz
    ├── 0af355e62ec0f2e275ec3c20106c7f297c428bbb.nq.gz
    ├── 0b8b5b743d27ad46a9730b8fdf79469f0fea0e13.nq.gz
    ├── 0cd7d71c4ab30f9eafa5693ddcb3ec358ea97e76.nq.gz
    ├── 0dede14191468a380ba1df0a38d78284b82371b3.nq.gz
    ├── 0e3aa022a363e1d85a255ba1e53a6da4abe011c8.nq.gz
    ├── 0f304e87479358e5c0dbf8b6aa34f0c53126b118.nq.gz
    ├── 10af2ef2ce4fdb8ca13c94dde2c1c30693fd734c.nq.gz
    ├── 10bd753e3b0cd56d186c9a33c85eb9bc457dc021.nq.gz
    ├── 10e244f1533624b8a860db4cd814c72837198a5e.nq.gz
    ├── 1115d1f41c66f1b490aa1deb24c0d37cd988d81f.nq.gz
    ├── 12bff90ef92439722fcd3257ca83441360e6157b.nq.gz
    ├── 1408f9d2d88adaf8816ee477ab57a87f7c910082.nq.gz
    ├── 14100453d3f2fda6bd9ef1c0e56787b6c22dc4b4.nq.gz
    ├── 1473e5cc0dbbf294f35db753c0f74745a59a9e6d.nq.gz
    ├── 14cb703004fb33990dda37c1ce4a9206d2ae79ea.nq.gz
    ├── 15a53d6de39b1ba2b3048ec4b93405d68f61bfa0.nq.gz
    ├── 15cae5dd69bc22c02099ef0acd0a55ca2bc9bcb9.nq.gz
    ├── 163d190bbe0dabdd171b0937c75b27f31d4868eb.nq.gz
    ├── 174bc4736a8f00eda90e54f7cd99ae898c572322.nq.gz
    ├── 185340f3264f641eb64949219bcc529997212e91.nq.gz
    ├── 18c917ca723043143a4907bb4fb1a9ff3be9f681.nq.gz
    ├── 1937f01cbe18513261197999f5121246bfa4d417.nq.gz
    ├── 19572de314d66189676c900e7f507e19743388d6.nq.gz
    ├── 1960c68192c60ec081156c5f186280113b1d6f19.nq.gz
    ├── 196239b7db1bc93f6ca8f9716410bdf7c0549792.nq.gz
    ├── 1a6f78a80f4846f242a8a96be094d443ad5ba3f4.nq.gz
    ├── 1ad239fa8d8e773938a22adbbe4f394df12ea4a7.nq.gz
    ├── 1c487e41fadb0d10da0d5ab22e12a4ee61831c66.nq.gz
    ├── 1d300ae6c6df8c631f18a417492431c0158fc472.nq.gz
    ├── 1e0c6a08591bb207fc4c20f133faea5af9d9872c.nq.gz
    ├── 1e771e561ecf962a1d5559f9a7e9d87d324a5459.nq.gz
    ├── 20daafb4f01f7ab8d0ea35feaeb2a7addbdf4f4e.nq.gz
    ├── 20f92c395e6914dad465e610a07a20556accddda.nq.gz
    ├── 218fd4b2e1e5726710c86bf0ba0b7b712dfdde2d.nq.gz
    ├── 2256dbb12b7ba1995ca5c83e35406dfdd468384a.nq.gz
    ├── 229c0be1af9e33e4514b94b9241b39a5a49df706.nq.gz
    ├── 22c11959f01807a958f91eb01f6b537daba30ffc.nq.gz
    ├── 230886ccab072a15c5cfe6a214fb4ed4ad18acd1.nq.gz
    ├── 23da26e3a440da9163add7fe8de03b1f9e6e9ae6.nq.gz
    ├── 254c124b065b3f075d6c78c1c7159afb9afa8097.nq.gz
    ├── 2706fe9ed97f72d4f9fdc7247e81c1d2882c9143.nq.gz
    ├── 271e8d7eac08f72467d4d3a47a3646ada7cf07c6.nq.gz
    ├── 279612c964f12149501e84aa0b385a5ea8908abf.nq.gz
    ├── 27e9d1259de8c0d507dfaa943f0b8f90329a943f.nq.gz
    ├── 284b730656c230edb44b6a40aea306d512974619.nq.gz
    ├── 28643a4370543896f9b7a17456088a4282a99289.nq.gz
    ├── 288995b397fdbef1fb7e85afd71445d5de1952c5.nq.gz
    ├── 28b08f3686baed2076776eb904895fe15b7b70b3.nq.gz
    ├── 2a4a03c300eb67e254e757ead5bcff381041414b.nq.gz
    ├── 2acfc48c0a7f136b3fc9b4664bbde243e1dfea07.nq.gz
    ├── 2b68ad7337cb45338f14c67bccf2f774f7c6f9b2.nq.gz
    ├── 2d77740fc1fff4a69b759d421cb95de516441e64.nq.gz
    ├── 2dd45095716c91f79ec9e0a852754ccb6cc452eb.nq.gz
    ├── 2e9320c18b9e6ffc70e9e90037ff92477dd6b1c1.nq.gz
    ├── 2ee85814f9381d13d74d437c805c6ef70971ad95.nq.gz
    ├── 2f453a0e6cbe2525294bdad78a927a3c4abb9f29.nq.gz
    ├── 300746510dbc5c62ec14bd3f092c3fa6639202b0.nq.gz
    ├── 3008264a8de545545024ba05b8826c1f86820ed3.nq.gz
    ├── 3021adea02da42e0c6d47e524797a2cf6111d679.nq.gz
    ├── 3067f9c7bdc90a26d4bc93f25334a8c5470e89ff.nq.gz
    ├── 3077af5125af67336124eb27027831baa9ac90c0.nq.gz
    ├── 3085fb0eecfcdab621bbcbd0686f75f1f001adee.nq.gz
    ├── 318405e0c1ec6a466f1170e23b5a6f5817bb5185.nq.gz
    ├── 322afcbe87cbd0baf43dfaaa649e707015174bb7.nq.gz
    ├── 32a96d5d6513807d0f48f96747cfbd9cade02a9d.nq.gz
    ├── 3314c6b208bf08c6801c31bd54e301c74528fc38.nq.gz
    ├── 34145e8c1bacf56100ea1c1d6fd87f1a4a58477e.nq.gz
    ├── 344fe5cd605a65613d46a97b6d7fdb4906c05d3b.nq.gz
    ├── 347ece1bc045c8c4188bb7ba961a18bc10ac00ee.nq.gz
    ├── 34cf1d5b0c7a5dbfaef46e9922553152ba5132be.nq.gz
    ├── 35a074d8e3a0cfb4acf8fa8ad8499fc0a9408e56.nq.gz
    ├── 35ec49bc43f65f0c3ab2ea6b7adefcee9b486ad0.nq.gz
    ├── 35eed08d9948a26a60e2736ecce6a6ae3866415b.nq.gz
    ├── 35fa55a5e8a3ca0c5891d5d23971d7787434b766.nq.gz
    ├── 36eb0631830edc4f6e85ede825e29f4026f02d68.nq.gz
    ├── 3711c9709b1c276039c5d4112e8a4b38815c5260.nq.gz
    ├── 37f7c705c63aabab124999b680d307309c6c9f2e.nq.gz
    ├── 38517a526585dcdfe2784f43cc503706a8a6d7c3.nq.gz
    ├── 386979b8aaa7372de6b823e7e3bfe6e1b9edd161.nq.gz
    ├── 38837663d6102429a25bfa51be1dcef4c9b884cc.nq.gz
    ├── 3a6fc077cf91c7da43ec58499ab8f204de718e2c.nq.gz
    ├── 3ae0aaf524d5fbb77b80a18491985f13cf938dd8.nq.gz
    ├── 3b2e6f503460f725118a7cb4201ea5dcb6cd224e.nq.gz
    ├── 3b9010096f2462aa54a6f425fdf552618301f914.nq.gz
    ├── 3bda831e41aff5bff0ab070845a148420cb1641a.nq.gz
    ├── 3be397583b47a0f2562dcb753a20f638d8143ac9.nq.gz
    ├── 3be495e039978fbaa1b35f861d89e5c9d03f161b.nq.gz
    ├── 3c1decd26678b2053b2fcdeee46e1ed9d4129bdc.nq.gz
    ├── 3c3b4cbc132d83213f426e899929c2a8316ccec7.nq.gz
    ├── 3c9af3019bcc36d7b1ec1cda0c799192d500a4aa.nq.gz
    ├── 3d9d8faf06e3ba2daa9460cb62e19f4f299b401b.nq.gz
    ├── 3e2a87c733d01d43d9c305951dac0449c4623270.nq.gz
    ├── 3f0da15220ff2293731ed259ee5e30b45a94fa21.nq.gz
    ├── 3fb8453ee91acefcc79c04dc21c13616d91e3ada.nq.gz
    ├── 40ced387c1f4d0251a0a85bb74f8952967dff295.nq.gz
    ├── 41b6901cdd23f2ff7e1bc77786eae124402a5c89.nq.gz
    ├── 423f0f2a07095deb415925c1a02370068fa49f0e.nq.gz
    ├── 42846ccd1dcd9c3fa184eb0fd36936dcef9c2cc3.nq.gz
    ├── 43b62770755b1c80e708eb4ae134083b42f33fbb.nq.gz
    ├── 44298137ae7d8cf748d974e8062ab88007ff24b6.nq.gz
    ├── 4547937dc93a25af7808171f73aa4968e2277c3f.nq.gz
    ├── 45599f331c6551df9473e0fdc30fffe841e41007.nq.gz
    ├── 45aad90b9073d0a15a38ee8e815d424148bd2cdf.nq.gz
    ├── 45e4f32455b01a1e661118ebc2dd1ce8db7ef8f8.nq.gz
    ├── 46769f16645132a5f1af18fb4b778ab5be691344.nq.gz
    ├── 46ea0f9bef17ad79e1c02b6f2020093477d6ef57.nq.gz
    ├── 47109cb79d6900c05f03690bb3afec6ed799a487.nq.gz
    ├── 47287bbb7f9556c4a35de215e226fcccedf7e978.nq.gz
    ├── 4749e51adc48b5b03fefcbab8910c49a38f3595b.nq.gz
    ├── 4826f7fc6088ccaac026fca318beff90dc9c1d20.nq.gz
    ├── 486604c06878d5faedeb7e46d65c8ba814561bab.nq.gz
    ├── 490aa74f892cb898086a123cedc7f90627185936.nq.gz
    ├── 4980f4913cf57ef6e63f34f021d7485b4f505319.nq.gz
    ├── 498630b0e259f5549d10c570b18fd5ca46f68e67.nq.gz
    ├── 49bed41e0fc93aa8d767aa906a623039f77cea3d.nq.gz
    ├── 4aa4d5093511e60bcf2cb54f6544a51e70db73ea.nq.gz
    ├── 4b80a1e52fad6590d35fd747ce985d11026ad52a.nq.gz
    ├── 4ba8e30bf7a4baead739acc59efd8620274bd925.nq.gz
    ├── 4d079ec5fc5339e7a776c9349d4994014904da10.nq.gz
    ├── 4d522831bc25d94108f9e682ab53be167b0b902f.nq.gz
    ├── 4e06cf7a21ee1c7912f4304fac8339e793eedf2b.nq.gz
    ├── 4f9a5ed08ac920ecd53e94e970d2632ea5d5900d.nq.gz
    ├── 4fdf0b86153292389bb22c83e60bc7de56fe8c4c.nq.gz
    ├── 503c218a3d9eb8a9d91081565ee3fd690b67359e.nq.gz
    ├── 5077ced52ee7b5a13e442334df637988ca8f7aa3.nq.gz
    ├── 51585e41bfa0ca632cec5b65f864d76683297d43.nq.gz
    ├── 515d0db8d45da35ed1e099fde4e5429b7b1a0394.nq.gz
    ├── 523f681f583f8ddf115ed979c5d76cacb93ba4ef.nq.gz
    ├── 52c945fbdd59f1d900806cc4186e16e900e27099.nq.gz
    ├── 52d5dd44aed1ee125f2cfc93f5e458c223c09061.nq.gz
    ├── 534e8ea63a2e85ffd59270b101d28c14e99cd0e1.nq.gz
    ├── 53a6899e06ecf87ccb311d7b9abcfbf4ec6c2c1f.nq.gz
    ├── 53ca74f9ffe2a2a50aa6edf21d1b7f12371b597b.nq.gz
    ├── 5411c7a583fa2b0465c3f4f4c64bec59f0fa0b88.nq.gz
    ├── 547fd585fc7711ca5673fb2e6c22064b00a07e31.nq.gz
    ├── 54d880c85e79480b064eddf6f4a505ca9ba304ae.nq.gz
    ├── 54dcb9a9fe2f98f9e0da592b555199f1b879f092.nq.gz
    ├── 553965b61f761592ba3ae0ad4a43219af2a105ee.nq.gz
    ├── 55d2ff7b8aa6ad4e22ac78a80d9e3ebc00c3a23c.nq.gz
    ├── 5633847616aab34b20d4118718528aa93b21d1e6.nq.gz
    ├── 563afbe9c895231efa1bd2f279e8b9367e8d81d0.nq.gz
    ├── 56ca6fcb779579f78149e217b5b0d0dd8eaa40d0.nq.gz
    ├── 57abe9d4c2f16b83ea1db2c3c033e91933809375.nq.gz
    ├── 57ce0678ea88952a7cceed22e762c0dfa2ea7757.nq.gz
    ├── 57cf6a585a9e76dea05e624efc7bbc2cd556afd7.nq.gz
    ├── 582fddd7a13ed41718849df8c407ae579fe8874d.nq.gz
    ├── 5896fbcf972cc5e4d6177c01bec2c3d7ea256318.nq.gz
    ├── 58c5c10a81745fcc33d454fa9b2bc9da8c4cc321.nq.gz
    ├── 59266d0fd13675e658a102260fc8ff1df0571f24.nq.gz
    ├── 5b755130f23345f20a825d5cc7b808aadc6e3d6a.nq.gz
    ├── 5b77ea045a9489da88ac7f4e70ea0def01e76d80.nq.gz
    ├── 5bc8cd0afc64dfef8dae19675fcf456d728a0c53.nq.gz
    ├── 5c0e8e3e861f5a818d9075879a696fcb9faf05df.nq.gz
    ├── 5c2e59e806d20b420a9d723a2cd3a7c5fb2fcbec.nq.gz
    ├── 5c58ca21c7b9417a5882950a31cbb58a0e457564.nq.gz
    ├── 5c7e6422ef922b77d8011b3fd747c33ba9d7ccf9.nq.gz
    ├── 5cd9917e466002ad98fca63a4f4351a16f35d509.nq.gz
    ├── 5da9208d79876b04ed84038f21032a6fd8ca20aa.nq.gz
    ├── 5ef9ecfea3d9949e4d78b5c275100126efd59df7.nq.gz
    ├── 5f5457d33a594c8900558ab60286e0fe1d4e683b.nq.gz
    ├── 5f6437ae9543242b6bbe0b43286bb91fc13a3377.nq.gz
    ├── 6186ddddc2ee505bdc9b6bbfd9c77db5f5d50e19.nq.gz
    ├── 6275ac92996200a98c9f59ee3fa3c5ff2cd5de7b.nq.gz
    ├── 62a1d59abd086dfec618307dca0ada72600ccd16.nq.gz
    ├── 62ef05a8ff1a1e8df87a677fe54eba57f128e512.nq.gz
    ├── 638ff03961d41176fdbef8ffadc5994df3db6bcd.nq.gz
    ├── 63c8c1bfd254d903a4d14afdf0872f3c0957d474.nq.gz
    ├── 64bf9d6978678e78e0cbbe93d0c25cfbbc2ca0ee.nq.gz
    ├── 65fb4f0c439f5b2fbc339ceb60ae1e689426b2c0.nq.gz
    ├── 665482e57be230aa644ff01693a5af740a3d2a2e.nq.gz
    ├── 66970d94d2274c49dc372e6186999f86c248b7fb.nq.gz
    ├── 66f6e3dd43a10a313273d15211cf548be07c4176.nq.gz
    ├── 6715716dfbb61a67c4a84f72cd07999e6a57d735.nq.gz
    ├── 679af4aa6ded3eec64f23c7dde6c7096cbb7daea.nq.gz
    ├── 67a64795f975ff82c4f4e1745a8c0e017e092474.nq.gz
    ├── 67e424482366422bc52a79753824e76fda1e3a62.nq.gz
    ├── 67f8ea046ef0f3a33c1cb62726cf07bdab1e3354.nq.gz
    ├── 6827c9dcc719e766b09dbcffe74a406012434777.nq.gz
    └── 6854fe2b286e087485dbed9a862857afaf44c839.nq.gz

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

[Azure/DotNetty](https://github.com/Azure/DotNetty)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
