# Repolex Knowledge Graph of mongodb/mongo-python-driver

RDF knowledge graph data for [mongodb/mongo-python-driver](https://github.com/mongodb/mongo-python-driver), parsed by [repolex](https://repolex.ai).

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
rlex download mongodb/mongo-python-driver
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 039144e9ef92f473cb92ae7838c718521b077b0c
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── 039144e9ef92f473cb92ae7838c718521b077b0c
│           └── chunk-001.nq.gz
└── blob
    ├── 0019d0c0bbf75d1d6ff0556c186f2753a600b32b.nq.gz
    ├── 00eb1356fb156e662c62e2f036fe95eb91d1733d.nq.gz
    ├── 018cdc7aa7312d7981b215434fe1cd7778623a83.nq.gz
    ├── 01cbc001165517dc2abbb6e930a172c4afb74e7c.nq.gz
    ├── 026f4a164cd55e75c204cb84827829872e1da8bf.nq.gz
    ├── 028c9a5cdb495cc2f0c6d4e4588d3fbd62d26e55.nq.gz
    ├── 02a728d37f25acb1cef5429841e6ff9307d78ad4.nq.gz
    ├── 0409e7ef68e0cb58aac1920f3c6d0d33bed3aeab.nq.gz
    ├── 044e04971ee80b24e26e0c324fddd9209c2bc35a.nq.gz
    ├── 054466e7299d8598fa0c38fa78a3fa22db3ac80b.nq.gz
    ├── 065543182f22bce041d801667ea0a9ce3fbc3b26.nq.gz
    ├── 0664e2a35baf0fcf9123499c389a46e5f6de7922.nq.gz
    ├── 07287dd62483373442dd41b13ee796df53687fcf.nq.gz
    ├── 07a10b02cacf827b3decead7fbc12fd0f8227428.nq.gz
    ├── 07d50f1b60033bed49d765dcace8dbe2fbe2a957.nq.gz
    ├── 0834dd6d7cfaa82cb01e77801f0bcfa68c686acd.nq.gz
    ├── 08c65510d066f8423f5bcd672025f475e2b663e0.nq.gz
    ├── 09ded813ac31634f7b39839d4c263a124a77e3f0.nq.gz
    ├── 09f2925ef56645c196cfe3df646453d8ce51d753.nq.gz
    ├── 0a18b0a936168772e796d3633b935606c83345dd.nq.gz
    ├── 0b1489c36f93511351cbfbc942e5493ca031ae9f.nq.gz
    ├── 0bf6c31a663dade7033fb0477d3b6fb34cf4f306.nq.gz
    ├── 0c4e7cffc212c39a5b57ddb9ec40d35a2481e370.nq.gz
    ├── 0c784c45d063b3c7163e37e62ce0af5d72c85105.nq.gz
    ├── 0e72372dc6e7e37f8bda9ec1473537f298051681.nq.gz
    ├── 0f4057061a763b445a4300825a450069a96f5719.nq.gz
    ├── 0f5f047dfbe248fab7cec058cfa1466e6cbd0c3d.nq.gz
    ├── 0faed74f7657e55acf7f82ec33a9c45a2f15b45c.nq.gz
    ├── 10aa1db198dd3a4cf22951c983870f2aa57ace7b.nq.gz
    ├── 11dd2e65ba402d182578155a0018ba53aa34e4ac.nq.gz
    ├── 13ea4649499c7d04cf366335b7ee239dabec570a.nq.gz
    ├── 145ce4dece7fe2ba1e20bce3f3345c52569c4dbe.nq.gz
    ├── 14b4faed2c4cafe8cf65a1b67156fe268fe906d5.nq.gz
    ├── 15792972acdab3a6fdf1947332a3ba07be93fb70.nq.gz
    ├── 1622304cfadf373f9546313c5471523dbf03d5ac.nq.gz
    ├── 1626c16f5847e6e0a3b276a863d86208705a1b02.nq.gz
    ├── 164ceafa62d3b49983b21cd1929530a34a36e2bf.nq.gz
    ├── 16d243d3181047c215b00dac426e1e13bb9f8a44.nq.gz
    ├── 16fcccb3776d8d16089a4b53d053d50a444c69b7.nq.gz
    ├── 18a543633e80ef8914463bdd3b40e8bd245db8b1.nq.gz
    ├── 190c561d0543973d1c6cc2a808a19acb38d72cce.nq.gz
    ├── 1af7a31d913fa2af9770b11da937d76b880494f5.nq.gz
    ├── 1afaad69fc3a2961302c7a43b6a417ef8aab29b0.nq.gz
    ├── 1bcf5c4951975bc7def91cc6bfb913d38dc7b28e.nq.gz
    ├── 1d0073a482092e338986e0109130223b8d230400.nq.gz
    ├── 1d30607baeb0163dca92cfa523c27e1ef6db7f4b.nq.gz
    ├── 1d624bd8c4c4fbae3f54165ce9e651bb5b940fb9.nq.gz
    ├── 1d77fa82a83cc25541d07d95991921cd062e3c37.nq.gz
    ├── 1e4d1c7e38fa997e84b993fe05537b85672451ec.nq.gz
    ├── 1f0c4a71387504ecbe042be4ae3bc5f17be4c4be.nq.gz
    ├── 1f68cf6ddcc781aa55b463e24abab52334197e69.nq.gz
    ├── 20519e16efd476be95af14f681772f290e1a2f62.nq.gz
    ├── 20ad7cedff109709b8c23d4fd0461fede1a753a2.nq.gz
    ├── 21cc65ac268f36633144a85102a07ef2646b4ba0.nq.gz
    ├── 22eb50a3fd7650747efbdbc570db35c237704991.nq.gz
    ├── 231625d8d737cf4f58733221d591651d2b9394b9.nq.gz
    ├── 24353db2a9a28268178c8f3144abacee0be53695.nq.gz
    ├── 24b3d65ae44c46ba11769d23772de89fa0c1c57d.nq.gz
    ├── 24beea2d48a94ad3aa4057ed2bd83dfbfbcef12d.nq.gz
    ├── 252b0daef039f7617e1bc2ff646f750e24d84db6.nq.gz
    ├── 255cc9a00418be1ba3c5fe473b1b00ad8f93d37c.nq.gz
    ├── 25ac2de351577e2e1a8fed1348fdc63fa73b088a.nq.gz
    ├── 25d1a779c6f978fd36107f9b5ffc570b16c777a3.nq.gz
    ├── 25d97721c1e81df3216adc35e3639b91609821a5.nq.gz
    ├── 25fc6f7ad6d6cd5afc88e651b1fe4b8179cf92b0.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 26c899e04c504f351b606510f512e29f11710710.nq.gz
    ├── 271f5e37fef3a18109d5d7c50640c2789a0210f4.nq.gz
    ├── 2830603b60d387617e160b1fb2fffa120d05487c.nq.gz
    ├── 2951af5db1a7b4a03958013682860dd6319ee6b2.nq.gz
    ├── 298eedcd3e52e01dda4a2f339e67bb0a1a2b1d90.nq.gz
    ├── 29ad8d4829e8ad3ba5213c053d8a4edfe68267a3.nq.gz
    ├── 29d0f17113c94cf7f0de5554233104bc4d33250b.nq.gz
    ├── 2aa62e87ad700354e70c55148e4fc93a4267a93d.nq.gz
    ├── 2b61dda1825ef3746584fd3755e0cff1c81c5096.nq.gz
    ├── 2b890b235710b595bdf3435a6220f7f045d88c59.nq.gz
    ├── 2b97464593c65e0b2de71a93e9d8b14da9696838.nq.gz
    ├── 2cd2f1b06176a6aa0fe271db7bd1ce8c6c939de6.nq.gz
    ├── 2cd9a0105b7dd97bb1b5f7690628617199cf3d2e.nq.gz
    ├── 2cf357bd5d741c07f55cf2ffbbd9421d7c26fe09.nq.gz
    ├── 2df232848f40e4bee8edbf74639030396e5e2c2c.nq.gz
    ├── 2eb14c9cb79cd9393c8e0334edfe7d42f45176a5.nq.gz
    ├── 2fa0aaebfed6f4b59ff5a275bdce72ef9d68c9f6.nq.gz
    ├── 2fe4ff5f3c4a9b49b45d96e19725fb96dd5ca1ac.nq.gz
    ├── 30783a73f186fc2626f8f4d2e536e39ade144739.nq.gz
    ├── 31aca76cab8da3ffa57a4b054892c7e4400f7398.nq.gz
    ├── 3224b3d1d9f606ed9363d185933756c5b15c73d0.nq.gz
    ├── 326bf2cf4e14dd564fe44c96bf48cada9fffef60.nq.gz
    ├── 3291169b07e2c9f28a98027aa65c2a104a4f3672.nq.gz
    ├── 32fde7970af27148083b62474b14a8358f2438dd.nq.gz
    ├── 3416bbd130f42ee93713d7a18b1612c39bf4cc84.nq.gz
    ├── 3446bc03c5924a467bbc0c1735cf2969ad7453b3.nq.gz
    ├── 34c4d05650243b5a81f5b30e1c6125c73c2b5ab0.nq.gz
    ├── 34f0fb31bc7cbc91b6e440b68c8559d08254a24b.nq.gz
    ├── 355e917fd9f2c49a8d867eba4d02a167071931de.nq.gz
    ├── 3589a81c865b133a8e6590523cf512e5504817f4.nq.gz
    ├── 362f67925cd9f0f04b68b1cfcce52b040c406716.nq.gz
    ├── 3632dfb161913cd2ad37b4df6cc5403c67187827.nq.gz
    ├── 36b442cf8095a82353cd39dd210b916089596539.nq.gz
    ├── 3728c3163c0e996fb9af1b26761a3fc34eeacb81.nq.gz
    ├── 372cf6535cd25010addfa7bdc2076ac83202318d.nq.gz
    ├── 3754c7467435a4bcf2cdb22ea5f745b123e00aea.nq.gz
    ├── 375d3dc9cd0f269cc65dc02ad282ee2e6885fd0f.nq.gz
    ├── 379a44d491de4635a695d1b3d46780cf23695eef.nq.gz
    ├── 3823182531509684739adb2b9e466e583baf7040.nq.gz
    ├── 385cd6ec16cedcc6e290a922926b32964a71ead8.nq.gz
    ├── 38f817c15dff6b928fcc665bac6501a2d457d424.nq.gz
    ├── 3a0acbe93292f5a212ace635760bc87ca821f626.nq.gz
    ├── 3acf43ff5ff740a98d3dd993ee0419a6f482c62b.nq.gz
    ├── 3af8fdf6b968c8a80c638a0e42595923dd446aba.nq.gz
    ├── 3b866abf1fdabffb52ea104115591f1dc7f3054e.nq.gz
    ├── 3b9a83e783155bdd05349213b0c09f430e068273.nq.gz
    ├── 3c455b4b0378badedf5715c0a7e5cd39489372c5.nq.gz
    ├── 3c9e067b1d3b052d97c3652039422aba6dd1aaa5.nq.gz
    ├── 3d0dc7ecfed41d19c545c13fe85f31c2718a295d.nq.gz
    ├── 3d3e581fdd7aa73a8c942833121540c7a8253b64.nq.gz
    ├── 3e6669a753ba038a39c43646480ac94ea3cc7189.nq.gz
    ├── 3ea50bbc1bd5346a66e51f1f4bb1ba9db987abfc.nq.gz
    ├── 3f5afc126220dcad0447250de96fe1ccda0ee241.nq.gz
    ├── 3fe2be9534c06cfc45a816589eb38f1779c5eb6c.nq.gz
    ├── 411916fc7aa89decd8082821b468c2a2ef8b4f33.nq.gz
    ├── 416744ac030e85c4e5e6de1b8d550c1f9ccd8ecb.nq.gz
    ├── 41865d2fd9639cb8e80f7cfc67a1f5e61848082b.nq.gz
    ├── 4241e651e9d5dba605a13fa99ebb1c531c9e558c.nq.gz
    ├── 424a2bbd838d38c1648063023b579c5b71c5c816.nq.gz
    ├── 42d64367eebe54e4773eed09d2e0302cf1ab6a32.nq.gz
    ├── 43256d18a59f15ad6b227c8d4716b92585ce7fe6.nq.gz
    ├── 433adef8417d5a7bfe29982198fe1b5b709556c7.nq.gz
    ├── 43c994c2d3617f947bcb5adf1933e21dabe46bb5.nq.gz
    ├── 446892e2eba8cb6dcac781f15b6c0b5e409bbd90.nq.gz
    ├── 44b36d3569eb7df17c2ec99d6ffc4cf32a986d81.nq.gz
    ├── 45a9adf5da7d4212c383d00905f1d64f334920e6.nq.gz
    ├── 45e86094fc6a351a3e9c9ff9600bc87cb03319e2.nq.gz
    ├── 4723def804e80153c4ec0955cb9e6226144b39ea.nq.gz
    ├── 47a72c1303f1619ed8b57254837744ab460284bf.nq.gz
    ├── 47d4910fdcf6867ac56ecf0a764c28d096ba9f3c.nq.gz
    ├── 47f2e40d0f7529c8521915a1d8ff9e993df0b8ae.nq.gz
    ├── 48801f2059bbfd216716b9607b7a27f4745ca7cd.nq.gz
    ├── 4a15b7d93a6719e1ad6fffdf2d7e79f6fa4516fc.nq.gz
    ├── 4b28687f4b4651df1a5228436e4e1ddb22808fe4.nq.gz
    ├── 4bb6a4817c625c299ccca846c4033d92a632ae2a.nq.gz
    ├── 4bc5f05f283ea08e75f28e929d8038216a26caf8.nq.gz
    ├── 4c4a0671bd565d216d2784fc972c65c5b5597223.nq.gz
    ├── 4caa90eebe74eb7618010197142432a14d9a35b1.nq.gz
    ├── 4cd9d689a514335267ba91fae6934ee5d7469b7e.nq.gz
    ├── 4d207b509b1097c5633a907dd98cde6a6f6ecd8d.nq.gz
    ├── 4d2f86547972def83ca5af7a2784a1a36b43ff12.nq.gz
    ├── 4d4614080321ce24978e766f70d041a5697dc5c2.nq.gz
    ├── 4eb78f62e1068209527aebed1c464be3a6b8431c.nq.gz
    ├── 4f4660590192ce8ed3554e67cdcf01e0f41eb30d.nq.gz
    ├── 4fb6c8156857a2e959c794960ac1a67755ec5a8d.nq.gz
    ├── 4fb6fcdc377fa7f0821eb40b42ba4f0c956a2bf8.nq.gz
    ├── 4ff67399b55d18033fb7841a76636cbc4cbf2f6a.nq.gz
    ├── 50158c4562da252c0cc0a0be1e13ea898f4f93ee.nq.gz
    ├── 50835bb92ca6d5dd21cd833773857033186e6cf5.nq.gz
    ├── 50bf0c8ad1fc1c01e5347787a09c58586c3244ce.nq.gz
    ├── 516a15b9e013aa753c352bef7df9c13c23d676fe.nq.gz
    ├── 51730d8579b7e162a80ba896ac21c99710b7dcbe.nq.gz
    ├── 5210e25d3691a187197bba6cac3db211c31ca0b4.nq.gz
    ├── 5281c7e49e55810ee0e82dbcb8da70f9611239d5.nq.gz
    ├── 5283ad9015578a1d403eebcfb4cb41b8a19a8454.nq.gz
    ├── 52c276b8b8100cdf6c2dc3747addd03b561715ad.nq.gz
    ├── 52ca029d265de009b296ef643bfaf4fcdddc5a11.nq.gz
    ├── 53196206245a7661e77ad0219be160bee40d6afe.nq.gz
    ├── 5324e74fabeb4a8dc620ae4c7944f7519c8ff880.nq.gz
    ├── 5417b1e926635b7ca9a943b653bd5fed737804c7.nq.gz
    ├── 54f0d4cd22a490dc1efee4cde4b8a9ed572618c1.nq.gz
    ├── 551cc40a2dbefe4cbca1ffcddd36579440708294.nq.gz
    ├── 57723098424d096ea2d30416c819d7eff6d59fe4.nq.gz
    ├── 58e5d0dbecd05e2b96422c19a95a7e5a043f92ae.nq.gz
    ├── 58f2fe80cbc5f370463471618f19adb2b5460a70.nq.gz
    ├── 594a28bc8887585a2d7f96d85bc05299f0d760fd.nq.gz
    ├── 59f4d03f5d06b0b6b534dcf362d2fc7272962748.nq.gz
    ├── 5b070010920d3159a2b4eb1bed834508fb799fde.nq.gz
    ├── 5b7da0f5a31b399c3e0eb7340da066f0ca00c020.nq.gz
    ├── 5b8f759fcdb75baeacc2f0226c2404fca9071846.nq.gz
    ├── 5c1d84c55c5f10cd097c0726899c11960f15c8dd.nq.gz
    ├── 5c6bbc9764049b10ee25fe25a76d775c023d090c.nq.gz
    ├── 5c7b4b39f68f89b8f1e4df47dda3418d9e5d7b63.nq.gz
    ├── 5c83b99dc9c59877ff561faad12f1ff2826812ff.nq.gz
    ├── 5ca4b26e04c4b0953a420e8ee565e9a647c86756.nq.gz
    ├── 5ce277e8a97698d97ed6cbdc0c28db28be139260.nq.gz
    ├── 5e213cccd866695c71b3725185a6fb7b1da996c4.nq.gz
    ├── 5e34c2d70203fd06ce212b76e14dc217b7a575d3.nq.gz
    ├── 5e3612583862b5e4e81b250508d97a781739a250.nq.gz
    ├── 5e48f2fb99a242e0972490790a74f5244770c3d7.nq.gz
    ├── 5ec13a2b568deb2b34209433e27c58edb4584309.nq.gz
    ├── 5f04f72adba197e32b5a81695015d456dec50230.nq.gz
    ├── 5f1980a5f97ea2fcd5e81ce53f6338f4a8fe7ca0.nq.gz
    ├── 6023350f5cdd65420a1fad4f167018ac7b140327.nq.gz
    ├── 607752524d6764b1885a6371a16121d9a5879d60.nq.gz
    ├── 60ac953046ba38ae02c67cb355c43ec38a4380e5.nq.gz
    ├── 614d7351ba5af22fc5a679b3d89f4eaccc8fa95c.nq.gz
    ├── 61606ead75b13ce9b55906b9b6c5a2449173f1ac.nq.gz
    ├── 61744e184dedf43c008247444312488da6554552.nq.gz
    ├── 61dd84ec2232755c4e8d7622ae5efcf2ebbd947d.nq.gz
    └── 62392fe68908b28f4239093a39885651b18958af.nq.gz

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

[mongodb/mongo-python-driver](https://github.com/mongodb/mongo-python-driver)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
