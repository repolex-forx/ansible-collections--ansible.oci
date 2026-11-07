# Repolex Knowledge Graph of ansible-collections/ansible.oci

RDF knowledge graph data for [ansible-collections/ansible.oci](https://github.com/ansible-collections/ansible.oci), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/ansible.oci
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4bb571838b9a7f09d2955462cb78bdd98d1deaa6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4bb571838b9a7f09d2955462cb78bdd98d1deaa6
│           └── chunk-001.nq.gz
└── blob
    ├── 00f418ccce89ddca9d14ee85a9e027a8436b4207.nq.gz
    ├── 0106a132ec6f200e5aa829205d0b203bbcd7b234.nq.gz
    ├── 01338e2782f23afbcdc72f6783481df986a61afc.nq.gz
    ├── 017c5e87ca873fe8a6311cc443feaf39578a7e6d.nq.gz
    ├── 0239e3b74ab3080c6c29aa6e1ff6c0209f3dba5e.nq.gz
    ├── 0273292443b8e7aca6ebae6a52b92b897296023e.nq.gz
    ├── 02b5960a8759674da27cea8bccf1aa4f2245c39c.nq.gz
    ├── 030b4e5a4439162ea12a3b3ea6f1cc5edfa38a89.nq.gz
    ├── 03670ba72d92350650f67d7298d30b32799f84c9.nq.gz
    ├── 04df0060d0b769a406f187918219367ab2e5df62.nq.gz
    ├── 0545686eed2fb8be2afea9c812168b140544da0c.nq.gz
    ├── 05a281b8b1c00081b24b66bf9e047f0ee89df3b4.nq.gz
    ├── 05ccecaaae83a026cf51e9114b2fe99be2e6cf38.nq.gz
    ├── 061c1b2ef793c6a2ae90691ca38dc68de648dca3.nq.gz
    ├── 07dea3b13aba9bac79638d36a927fe18804cb959.nq.gz
    ├── 0b94ffbac14b2d036adc33e88c4b4e1f290cc872.nq.gz
    ├── 0ba21b6e6faf227b5879cc59f3dce286171a8bad.nq.gz
    ├── 0bda07548a26ba74e993ace2bca4a2aabaee8644.nq.gz
    ├── 0ce71056b0aa0fd01d58e0a67ef785ccd5bc1579.nq.gz
    ├── 0d786c03a32230192fff67d65d6533fc0ccb702d.nq.gz
    ├── 102c632a6a33216a695863677ddce80a5d70c064.nq.gz
    ├── 106f00f008e250cfa11016440a4c9f47befdafff.nq.gz
    ├── 117ac9175ebd1d758ce253b291d81c27424acfd2.nq.gz
    ├── 11ce9407a2943d6fd43cf18fbe2bd45458f7f372.nq.gz
    ├── 121818036297ba2def30ef59a947c5ee51d3b1e0.nq.gz
    ├── 1259a0a5f0bb442b611ae65f48f20d7f8895a631.nq.gz
    ├── 127ea6fccc52c5bf49a9b3310c2cd5eeb1fc1cd9.nq.gz
    ├── 12c227970a5269dedf76e8d029e6f0f4a78f0c74.nq.gz
    ├── 136c05e0d0290e2dc7eb89bceaa27b5f011e780a.nq.gz
    ├── 139e583702be22954e86d916ec6c8f7759dd96c2.nq.gz
    ├── 1453fe17b62d9862149d0ac290f3485edbe22c7d.nq.gz
    ├── 14ced5102114e9d9a73ff3edd54836147b61d2a3.nq.gz
    ├── 14fa7194d9ece6ddd4f29ec6a8a6805ed1d22819.nq.gz
    ├── 15293ff00909fb6c3b7866fe3c2a52e044424258.nq.gz
    ├── 1635a6387b206edbecfa05324fbded8e96dc8c8b.nq.gz
    ├── 1711b53064ecde1794445216645e0124010c136f.nq.gz
    ├── 1772841a58525506b200c6f7fba2ddb844822d0f.nq.gz
    ├── 1897998fff686ec8a1e51623206d5f39373cdb4f.nq.gz
    ├── 18c8060357cffdc18bb22e014c0f11e7ff66e284.nq.gz
    ├── 190377cfdb216a972d580588d36dcd8c89819e5e.nq.gz
    ├── 1a3040e76aa589876f689321c925cbf96e81768b.nq.gz
    ├── 1a94f4618aa36f183c1284473c307b1dc1f9f697.nq.gz
    ├── 1b3c8c434729ed6cce38c452e4690204333b50e2.nq.gz
    ├── 1bbb2d13c410dbbe82dab7aa7640ec6403cb159f.nq.gz
    ├── 1be8f8a5aff20bc530782d58cb945c1375ce759c.nq.gz
    ├── 1c829c6890229c2402f15ba0cd9343191bfa9834.nq.gz
    ├── 1d0c7ee700b1df680ad4f036ebeebd0c37b58065.nq.gz
    ├── 1dc2caa87aa027431180690501337dfa114e5999.nq.gz
    ├── 1e894f00c7e76a4081250aac95db28f0e96192f3.nq.gz
    ├── 1ee0470490ba0ed96f304560b3de567fd5b5e491.nq.gz
    ├── 2015c54c31b2bddb8ff9058ede217bbf47885511.nq.gz
    ├── 21a2c200a12d84004fac5d87b9b35f1a6e03c6b9.nq.gz
    ├── 21d156c5904a35fa5560c18f18d9c75b3d4109ad.nq.gz
    ├── 232e2c2bae9969642251a33a9841c72dfb88442f.nq.gz
    ├── 23e2573c6b55f642839377dc7dbde53999966c95.nq.gz
    ├── 23fc21fc8a95a98a6a5927b4cef54bb90d560294.nq.gz
    ├── 249fe026855c0e686e3c42869f6eec5e42f2e377.nq.gz
    ├── 24d882ed2964f8919a876145bcbfba0961e9d13b.nq.gz
    ├── 25130dee0f53ed28ca28cebddcd1f2a0f47e3646.nq.gz
    ├── 2587b8d2ef34549263fd4293ed0d02985a21dc2c.nq.gz
    ├── 25dcd9630c8017393029078530000fccf271a241.nq.gz
    ├── 2616e55bdd790ff24000641f4ff72a12cf53ab56.nq.gz
    ├── 26d7763d94c8fb4d1f1972e50f613d50314eb105.nq.gz
    ├── 29438d0a999d39f7064adba69aabf0358334c1e6.nq.gz
    ├── 29745c44643cc5de8435aee66e64559331c5c014.nq.gz
    ├── 298012e2f27daded17a9bbe299910309642d998a.nq.gz
    ├── 29cc4cadaaa197ad6a52ce45cf608b8bb04c3a79.nq.gz
    ├── 2aa60df8cd38722ec8c518550d82edacd63c5d49.nq.gz
    ├── 2aab6d8acdd2c290de5225e7c0364f6df3327309.nq.gz
    ├── 2b3a820c5c53a73e691ab898d959ce0aae6b5ea8.nq.gz
    ├── 2b63dfa995f741752358eeaba8e8d7d849c1f6b2.nq.gz
    ├── 2b783e8bde3fd645c30c82c2670b0f1bdedaf29f.nq.gz
    ├── 2ba382a8244fdf7472a6e4a7b0bf34c5747df07e.nq.gz
    ├── 2baeee3b26fe459f2bd271f48733749ef4ae2984.nq.gz
    ├── 2be974a8774c7a959f4d02fea3f26b8f9866bc5f.nq.gz
    ├── 2c46bd91a493f37305dc3df4f7ff5f6e2d6f12a9.nq.gz
    ├── 2ce5e5e4d66410d3160a7b7c06990bdac2972485.nq.gz
    ├── 2ce812b95846c800502cbb3e71186c2653a7fc70.nq.gz
    ├── 2e183a834be56069862ac45a9c396e2e696b90ad.nq.gz
    ├── 2f25aea1a4b5941ed528ad1dc878316f8b64cfc5.nq.gz
    ├── 2f9c6d406bd2c86278688bf6fe90d868e9f108c4.nq.gz
    ├── 30ca94fc015d804a52785561e461277fc6a1f6ea.nq.gz
    ├── 31368dcb706b75bcac97144613cf8c5b6bfe7002.nq.gz
    ├── 317a53bc1aecaa34442a026d2300a550a916d212.nq.gz
    ├── 3309dff2da9cf22fcc49f262681f4bac8bb99ec3.nq.gz
    ├── 332977d963eb3605c00ce765672beb322ec0ed85.nq.gz
    ├── 335ed006b5c43ee99aa21d8ef127b9e574bf89b1.nq.gz
    ├── 340add1aadd983a89105127cf552db307a0ee8bb.nq.gz
    ├── 34291ce82f5291d33c082b4100e94d1f291bac30.nq.gz
    ├── 34f3389f6a5044830eee1678e16ee8f16b8979f0.nq.gz
    ├── 3572dfd7f20aa3aa16ccc1cd47c0a281c2a418ee.nq.gz
    ├── 3591c544c1a371e9597a18c3aa9deb71e4e41d14.nq.gz
    ├── 35b30345968ebbe17149c334f424554affe9c0bc.nq.gz
    ├── 36f6a51f1344421363b421520e5df236287ab971.nq.gz
    ├── 37a6e745fe8c3581731e71a2a599e70398699830.nq.gz
    ├── 37aa538e2c790fed1b6ecced58dbb1613dc7bf01.nq.gz
    ├── 37cbd0a46eeebe1cce623c54d53e2b7755290f06.nq.gz
    ├── 3802af2b335ed2494629e084f78ff22c30eee53a.nq.gz
    ├── 3957d749de6abb3e8874ccd02ad6a4a4cf925f4a.nq.gz
    ├── 39984bc1376e71eef6fa623540662aaf02ddf8b9.nq.gz
    ├── 399c67b294c675c8716921834da09e25c3d4b20a.nq.gz
    ├── 3aa76acb339429a81b5b3b63c850707c22bca155.nq.gz
    ├── 3b6e4c72430cfdaf7e0ee2abca2b32e9399de10f.nq.gz
    ├── 3b7aeabf7c9295543e530965284fae8b505c6574.nq.gz
    ├── 3c319a0764e5f2342aa4bdd0dfd1f31346877f79.nq.gz
    ├── 3d50cb96e384a2ec41b5f0f3ccc9e019743b4e21.nq.gz
    ├── 3dad9a7a97412b6bc9097ab1c3a7a056b7439a99.nq.gz
    ├── 3dde92ba08c92b94f45904a4f982792fd3799a4a.nq.gz
    ├── 3e630cabd124464d70986ac8c2c2c2607243e20f.nq.gz
    ├── 3e7b73178dc59f4e6b5e9d58259dbf84675ed6d4.nq.gz
    ├── 3f80c9944c9009aadda5b593f039a66d88cd6ec6.nq.gz
    ├── 3f8135da0716a1047c57a2a363edf8cc7da5fc51.nq.gz
    ├── 4104ced3a4cfa1bdca271fc8c841ed0dfbcf58af.nq.gz
    ├── 4137154f33ae3f0ceb943d4c0b0d575a3b310107.nq.gz
    ├── 413841645ae07ee8cccfae24eaa95ed9f81b7355.nq.gz
    ├── 41a870a6797dc8594b0a38b4e6f6eabd7feafdc1.nq.gz
    ├── 41ff4fc1ba938271b37bcd18f899cfde7a94a986.nq.gz
    ├── 427487225714098de0a3a7cc29298c23c8efdcaa.nq.gz
    ├── 4279391fd8d60282aeb427902413b1cbc97677af.nq.gz
    ├── 428bffebbe9ffd7f802a47893e55043d1062df0a.nq.gz
    ├── 42cd037173f2a51c236d0bf6f260290cea9daa1a.nq.gz
    ├── 43570a9835403e7f0436d944ac4da4a632edcb67.nq.gz
    ├── 43ef5e70715306e6d214f468d233fb3f73ded34d.nq.gz
    ├── 4442b00409e4c8a6316e0a85c8e58d6b1612c647.nq.gz
    ├── 4458bc7bcc074d1a9e02a486ccf605238030d378.nq.gz
    ├── 44b09208ad357bb6f540c3fb9e6c78802ee9372b.nq.gz
    ├── 44ba9acfcf86ef0e451f09f1f68fcfe2f557dca9.nq.gz
    ├── 44eed446c1666e6fcb274062cdc4568047616b43.nq.gz
    ├── 4519140b613a4a5a1679f58863a0cc3e3b4fe845.nq.gz
    ├── 45b45ede97b3c64b8a82f92dc5aebfdb486df155.nq.gz
    ├── 45d3af5c63c5c5924d86b646909fba3275d396e6.nq.gz
    ├── 4646f4a390164c5538c36e8b98c75a51cf823549.nq.gz
    ├── 4670521eb14c8e5b8fc886bcad61a026190e88d9.nq.gz
    ├── 482c7fd36c6d30af1f7bf1a46689907241f2daf7.nq.gz
    ├── 4864944e420de9b409884434e141d06d82175ed3.nq.gz
    ├── 48a51600ee76cdbe5866de448e0554c87ded5845.nq.gz
    ├── 498134f18de84e60673ddc202d6795fc69ef0d38.nq.gz
    ├── 49f67d4ffd57e948e21d20e51f3976a8f945c179.nq.gz
    ├── 4a24d36b938fe1324b5e62773f96f3665543bf63.nq.gz
    ├── 4a56461dcd538210c85108b85b2329b6d528780c.nq.gz
    ├── 4b13c7289748488c0d0becb36db42078a4e7bf40.nq.gz
    ├── 4b248280d166a3f5bfb382e7031311fb87b4e4aa.nq.gz
    ├── 4be6dc6e9c0363b4abb64d493b324ebca7b69280.nq.gz
    ├── 4bfda273a44ff7f3460da432e5bb0348123911c5.nq.gz
    ├── 4ca9ddf828d01af1192badb11dadd8b0f2ae7f80.nq.gz
    ├── 4d9a1d540ee17bdfeba3cfcc1a202cbfd6f6ee91.nq.gz
    ├── 4dc58d171749eb062172dd1c474ca73f7704b4df.nq.gz
    ├── 4dc78347185e1e9e07c10432f3cf966e9f77e76a.nq.gz
    ├── 4e26b2d7610a5111e8ee8fcb7242a98febee8a8e.nq.gz
    ├── 4e9bcaca7eb82ec2501d8f96fc3e9ef080c5c26e.nq.gz
    ├── 4f02c9fa69d457450b85781c5f2bd17bc06f084d.nq.gz
    ├── 4f1088d6049e69addc419f9d93aca397dd0c251b.nq.gz
    ├── 50392b1f50d457aaa25f6baf82acd1df73981596.nq.gz
    ├── 515e4040c06b0e7a4a8ed8ed0602656501843957.nq.gz
    ├── 5216ffe41c2ba6f346bad17ff0b05318330687f8.nq.gz
    ├── 52b761f0318ebab7985b2861cb0587e61c312460.nq.gz
    ├── 535f87dc6f8c5a93d2ff9ae5aa7481bf2b2a6ddc.nq.gz
    ├── 536e4725e7973552d64b8c433ba59d9fc95a4ce1.nq.gz
    ├── 53b137e52a4adf95811b1b18716544e7255ad577.nq.gz
    ├── 54076a000670b1a6a525b8b42f9f23570a1ceb08.nq.gz
    ├── 54f6618c484b51c2fc2eefdb5c432e1bd8659972.nq.gz
    ├── 558d23432362e6a69048b65db5533c1b4294241d.nq.gz
    ├── 56e9b88152378476af1c42b29bc4a1e7baff6e4c.nq.gz
    ├── 59317a381590150ca263d0bf4d44ed2a72ccd9f7.nq.gz
    ├── 595459b3acd7e62c2556d682b6a8d64bc0b68519.nq.gz
    ├── 598321a74ba7290d95a86c8e933ea1fb0b6f4d82.nq.gz
    ├── 59ac139fdb699c0288010ec25d37026f5f28d3ce.nq.gz
    ├── 59ceb2cdf37fe4abb1da0332aea61430eea0ffcc.nq.gz
    ├── 5a79ec8ee3a019cbe2f41d83017f01db52674905.nq.gz
    ├── 5af1eae9120f7dc38e8db18f120716fc6233cb10.nq.gz
    ├── 5b7804f662f4113fc10d341d029bf2ae0725c1cc.nq.gz
    ├── 5bf755616cfaa9f5310b1d791cd02ae24a28456e.nq.gz
    ├── 5c4b109783f2bd9e151a4d61ef4b2711caff5a85.nq.gz
    ├── 5cae24f9438285bb0cd854d9e42b61299f333dad.nq.gz
    ├── 5db0bad55c4955feafea5a577ce184ccfe9b0ca5.nq.gz
    ├── 5e7105dc4cc58b94ef3d3bf93faf800630fcb067.nq.gz
    ├── 5f397d4f8f66dc766cb7764879d3e464bb0de3d1.nq.gz
    ├── 5f3b72a5295bea8c57592c14fb468688c3e5e93c.nq.gz
    ├── 5f5064fd6b9c4fd4c2fe2acc796d694fb3da9b48.nq.gz
    ├── 5fd1c4d5234649130b2e99fcaf98dfcbce372d2c.nq.gz
    ├── 6053dec3d41883221030863b1b446d2e20170be8.nq.gz
    ├── 6095f4d401792756485af9569f2440a6a146bf9c.nq.gz
    ├── 609f434a7c0e00e049dcdccefffb02e912d9f26f.nq.gz
    ├── 60ad08e962b1257904227bac8aa6fbb679e31feb.nq.gz
    ├── 60f148dbe03b9bd231b88d2702efd3717226c1c8.nq.gz
    ├── 610020bf6d4a25b89d06e690a260437c9780fb8c.nq.gz
    ├── 61f18c2063d8ace91b123bcaabfee8bbfae4257f.nq.gz
    ├── 6378cad9b165b429f30df10e7fcb17b6791da475.nq.gz
    ├── 6379ff73e999b2145bc218dc2ceac037817405a2.nq.gz
    ├── 64b214e62ac2566868274adb7b8a331c2a598e8e.nq.gz
    ├── 64c16626bf67d8664cc2a6559a26d94f2636dd5f.nq.gz
    ├── 652e6183c5d564445d1ed81ecd3fe5b206d7e675.nq.gz
    ├── 65331c81557e7bbc8ff003db63f3ae466eb52b9d.nq.gz
    ├── 655b7ea07b84480afb0ce98068f24c816412a00e.nq.gz
    ├── 65905c7ae0e8525fbcd8fbe8344ce2831722bdd0.nq.gz
    ├── 66909160ba08fcd60916d47c8851cbc66af01205.nq.gz
    ├── 66d99bbd77ddbcf06c4b83b007566cf9bc6ac6c6.nq.gz
    └── 67a7b0a2c546d65b46b3207d6db1a896830e5944.nq.gz

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

[ansible-collections/ansible.oci](https://github.com/ansible-collections/ansible.oci)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
