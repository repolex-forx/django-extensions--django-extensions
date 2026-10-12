# Repolex Knowledge Graph of django-extensions/django-extensions

RDF knowledge graph data for [django-extensions/django-extensions](https://github.com/django-extensions/django-extensions), parsed by [repolex](https://repolex.ai).

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
rlex download django-extensions/django-extensions
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9bdf31556675e795c7c7c4f033f194dc075d5919
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9bdf31556675e795c7c7c4f033f194dc075d5919
│           └── chunk-001.nq.gz
└── blob
    ├── 00626a0d2b3b73aa10f15b57e2b0938610174fb2.nq.gz
    ├── 0191d1a83f70fef170fb24f13b4299bf5b4d8d12.nq.gz
    ├── 021ab87924ff06f19e37cc49237b5491764d76f7.nq.gz
    ├── 0282342d4fe7a803a66894a66c40beae1453a01c.nq.gz
    ├── 033ba598c95b511441c43f4184b881a42bf42838.nq.gz
    ├── 0363616ebc916df4f68a6e57790449cac323a253.nq.gz
    ├── 0380be89460888e4c9c8ca87acb7556618222f88.nq.gz
    ├── 05a71bb89df0a284a6bf61def02487735c0fca9f.nq.gz
    ├── 06ae238a54ba5d1cbc3242382a0b38e83d259709.nq.gz
    ├── 06d147b02c4ae9c4bd712e7f272afe4f0bd943b6.nq.gz
    ├── 073a3a15ed80eb150ca31e7d785654726315b778.nq.gz
    ├── 078a9491d6d61d5500aa82cccd4fc776744fb69c.nq.gz
    ├── 085ccaecaf5fa5c34bc14cd2c2ed5cbbd8e25dcb.nq.gz
    ├── 085e5793a3df2606b572ed95f5a202bdc4325a0f.nq.gz
    ├── 0955adf00d4b19afb02f4b3e1b1d6143a9c6ef31.nq.gz
    ├── 0981fb38c390732c1183f7b9b84e25ff6e4ff4f0.nq.gz
    ├── 0a89271a545726d224e4c03c4a9fa29a2a8c7c03.nq.gz
    ├── 0adec290009b6db91397aeba034d98b1efe46f8b.nq.gz
    ├── 0b4331b362b98a4e5947c491612f95a3c2e56686.nq.gz
    ├── 0bcc2317f91e9ff9a3f214e12230bf315069ae86.nq.gz
    ├── 0cc77456e57baf16998d27bb9adfb41bac62cddd.nq.gz
    ├── 0d697e9db0da809a838e65061c2355122fe1f855.nq.gz
    ├── 0ef803cc4c5af26e453528537e5727e7966714dc.nq.gz
    ├── 0fb9dc27b89a7f3a1ba683cbefb670530bceecd2.nq.gz
    ├── 0fba5aaf85ef9a97dde2142076253ff45fb00c0b.nq.gz
    ├── 106ebf4c7b01441e748c40d19e70dbd027b01b32.nq.gz
    ├── 10dc3b089c5cca92c397482ebb7249863f07e69b.nq.gz
    ├── 13b17b3d86c9b03d4ec2ea77eb409e2a33714f75.nq.gz
    ├── 13dbfb51652068b8b9c34697210e631c69d0f588.nq.gz
    ├── 13eed224e7ff85b626c8803d367b619d6cd8bf2c.nq.gz
    ├── 142292f9c845577b7965f065d10d8861a28cced7.nq.gz
    ├── 14497b26629dd307f2c2ac5fd5038bfdfb82a525.nq.gz
    ├── 14af204353db87a3324ca82b0112aae72184d640.nq.gz
    ├── 14e294bb3246c5e21150e1360308db74949abda1.nq.gz
    ├── 15626fb6b70b02a3ecbd5e8730d8f49b6275e61d.nq.gz
    ├── 157b742eeb7bf7d00d245083e2535adfba8de92a.nq.gz
    ├── 15daf34223750b9b90d00ce2eb2a5eb46e8fd7b1.nq.gz
    ├── 17540af284e3dfe5ae126bc6119d6b7f225d9a9c.nq.gz
    ├── 17c5ebc38c4987b8db982ddc40c8fb6a169339af.nq.gz
    ├── 180150ee03f266338c067ad9cee1e4e3616e8432.nq.gz
    ├── 18694d375555d782a0e698644902eaf8b35353d1.nq.gz
    ├── 1972c4f810fe8a171483e0d5b51ffd60e8c425dd.nq.gz
    ├── 19c67cd4f634d6d8680bca459bf3992b6d4cf4a9.nq.gz
    ├── 1a452ba00ef3be28b262a3cc17b02e504cfc891f.nq.gz
    ├── 1a9c2bc80da4930d433832d98273a79c1099b29a.nq.gz
    ├── 1b75fa43921cbadff539b8fff797ecf2c1141c1e.nq.gz
    ├── 1b8cd359de5df53423a39a24a446dfaaa4f6009d.nq.gz
    ├── 1c1a48a2592e8530d0ec007c400327ab2f535c71.nq.gz
    ├── 1c88e23b8af0dd4f2921b4bf384915283b17950a.nq.gz
    ├── 1f9cfaead7deeff7f6ee48cce634ae10509c47ee.nq.gz
    ├── 1fe0d8359cc508bf48ee261dc00d346a8e728461.nq.gz
    ├── 2002e9710925449889a153f57935a53d5018cb07.nq.gz
    ├── 200ab815715ea390de7c413efcdcbedbeaa90b0c.nq.gz
    ├── 206e620c4784a842ea9b803e3a4595170fe4a3e7.nq.gz
    ├── 20a710164111546d30042a1661de786076adfd6b.nq.gz
    ├── 2264aaf7f858f4f2dca8ee849f14c35a2c60811f.nq.gz
    ├── 23ad060f55cd96f2c778b5095a614405b08d8062.nq.gz
    ├── 23ecb6286e4d3d81985870aa8c585d89c0d83b3f.nq.gz
    ├── 2500fcc2f7227c8d84f8929db1e3762435217c0f.nq.gz
    ├── 269d137229b4449d0a7ae645e9eaa8215891ea58.nq.gz
    ├── 272f3c1c08ad436117ec289dbb5ddedf1a9d9f89.nq.gz
    ├── 279c6daa91566971bc842ca3fac94ef6449356ff.nq.gz
    ├── 27bccaa9d52bcfcd1585cffcf12dc9e4c989e910.nq.gz
    ├── 286711020dc28033807441a752c80373a620bb05.nq.gz
    ├── 29995020a2bf97e749a28235c6d05ccc4a71dc3b.nq.gz
    ├── 29eeddf598cd2fae59c4cfc42928d224f126ff4a.nq.gz
    ├── 2b9a4659bfe69cebb0d005613101dd8528c643ed.nq.gz
    ├── 2c157cbcf85b4ad8bf7590b6cc9df6031d524eae.nq.gz
    ├── 2d37d0b87a571962dd05f3e3b83e8f16641b192e.nq.gz
    ├── 2df0182f8051fd59fd14e551ce2091ae297c7ced.nq.gz
    ├── 2e0721517b45aa415b04a50b45ed3ddbba7c8989.nq.gz
    ├── 2ecd31c4d41cb69aa673bbbc0b358f934c13658b.nq.gz
    ├── 2f1866bd574a7876865b0ca91ad9ac6b71a3aad9.nq.gz
    ├── 2f98573ee24df46945ece336df0b4ad3a4b4c3e2.nq.gz
    ├── 321b54fb30a301733cc65a53faa47f88fffcbe7b.nq.gz
    ├── 32b145cc90073d5cd3995f8dcc418d35aa69efc9.nq.gz
    ├── 33b6a503cccd953fecf81b89b8bb104aab542b1e.nq.gz
    ├── 33d00dffe41dd9e82368544bd7dd5ea12d237aeb.nq.gz
    ├── 3472a6cd5ddaccc0c3d80eafb9a1b8129b48a848.nq.gz
    ├── 3554b7b9bace1526cea5dcc1ab921a5114a8056c.nq.gz
    ├── 378d30aadeddb2990a7df43acaa9e62103e3c51a.nq.gz
    ├── 3860be87ef7f7a0a27d61be829b42c5bc2c462b6.nq.gz
    ├── 3a40def2a437131a53b544f9717ea9d4de140593.nq.gz
    ├── 3b0ffcbdacb0e8e172e9e66eed077ed08bb10557.nq.gz
    ├── 3d1110aec484d6436691d9d36e84bad338d3a649.nq.gz
    ├── 3f31efcda0a18d3eefa5f1678960b1f3f6066fcb.nq.gz
    ├── 4185d360e9a725a190ddfd9b8cce8aeb0df64cc3.nq.gz
    ├── 42e323e935a9554d1eba4205671802f502ec8a1f.nq.gz
    ├── 432ef52192ca76344aa2798f2429c61cfe8035e2.nq.gz
    ├── 4378f759ee34b4678ed0e31475e2ff8d8635f4ca.nq.gz
    ├── 43844886f8df10238b3cf86675afa916e9e50a4f.nq.gz
    ├── 43d6e5eaceb8ca1c70e19f9e1438da971954a719.nq.gz
    ├── 4484fed9f61f670aa5ecb4260a01c7f4ec1a9a0a.nq.gz
    ├── 4629888f83dc798b3a799c8d7d74e5b313a5edfd.nq.gz
    ├── 477a6b986262b22f70c5bf2c82d02c01bf1cc61b.nq.gz
    ├── 486fdbf25e10672781e7cf378371c17664cd85d3.nq.gz
    ├── 4895d76d21b44052a7f63dee71d1ad275d9e058a.nq.gz
    ├── 4bd3b15fe4916bfeb09b49db1ccd875218341083.nq.gz
    ├── 4be8892bdbd63d5e69523ea56f60855b104951c1.nq.gz
    ├── 4c4f96677f54099aec804a1b71bf87d537e47836.nq.gz
    ├── 4eb1e413537876a9c8cc38240d778eb797f632d7.nq.gz
    ├── 4ed8824d31092b07af760f84f33aad2e54a619d0.nq.gz
    ├── 4f4bebd208f4ab27eae39bcd77c8f932ff145720.nq.gz
    ├── 4f69c2f546dc225d271ab9addc9812af973a7d37.nq.gz
    ├── 5016f422ba90398614e767970fcdd987164fa07c.nq.gz
    ├── 50ec58e476b8e452aee641ccd2e1d0ed6e801cf2.nq.gz
    ├── 514011894cb64fd83b6648a719480b197f2cb9a2.nq.gz
    ├── 55eeac1305cf3725aebb86f7cf74517f0f1e2c5b.nq.gz
    ├── 56ca5e2bf088fc291956de751fe42827886b9bd6.nq.gz
    ├── 57b4bbba881794870f19eaa2ac006666a691d308.nq.gz
    ├── 58328634813985ae1b232d6742143904db1924a6.nq.gz
    ├── 589a7b4245a540692447f8c699c1e9b953e490b2.nq.gz
    ├── 5928e286342355594385c235791d6cac42e3bf22.nq.gz
    ├── 592fded98ab96e34910828fd5537febe81fb982e.nq.gz
    ├── 59668f052d37bd9d9d7e85e1c61d57a96917ac3b.nq.gz
    ├── 5a509f56f203c86aa37ebff85ff8182af428e37a.nq.gz
    ├── 5bda529d1dea427a4f2ee51a1f52a30f8539b627.nq.gz
    ├── 5c54ff4d7bf7990197469ab2afb259f9e2f24ab6.nq.gz
    ├── 5d0014ef5162907622e77a37dbb477a4a2339bba.nq.gz
    ├── 5dd86521c525a304d86a644af420ad935df3ae69.nq.gz
    ├── 5e1fd9a977fc96d35612991a33534b396725467f.nq.gz
    ├── 5e36b00cb3bff29c550e6133802a816e77b3115a.nq.gz
    ├── 5e64e88737ff33bf6315cc6c84e1bb3cb8c36977.nq.gz
    ├── 5eadb2b717a69bef116d402facdb530d810c6424.nq.gz
    ├── 5f7e6ec7ede6d22869c2b33b31f2d8478b0180b0.nq.gz
    ├── 5fa8b4f159e691a5fa8af0d755e575fa617880b7.nq.gz
    ├── 5fce764876050926bceabc862edeaea82a9b7871.nq.gz
    ├── 60da2999813ff165843efe23f75b414853ff3a4f.nq.gz
    ├── 60ebf401e2fa96cc33fca0fefab8fa0cfb66ad3d.nq.gz
    ├── 60f00ef0ef347811e7b0c0921b7fda097acd9fcc.nq.gz
    ├── 6153e0069d9267c119dc2bd5481265fa7f21ac2e.nq.gz
    ├── 62ed9bfe1c4b4e593e6b35bb323f84f2bff8338d.nq.gz
    ├── 6367477a60131e171dced2207a9dd526008a3235.nq.gz
    ├── 64ba4c6e8e5c28bdd4cc77fa71b02a6cddbb5c80.nq.gz
    ├── 64fd2f3da053bfd7424b90e48c9ff04aa0759b61.nq.gz
    ├── 67d7e1436be5f0863605679cfc9c45090761933d.nq.gz
    ├── 689090c6a445beb0e05ba80387fa1c2cdb7654c9.nq.gz
    ├── 693609659e844b509eccea0fd689184cf02d9520.nq.gz
    ├── 6949682e7dc205a4e2799fab15152282c33446cf.nq.gz
    ├── 69c12d2c5ecfbbe91a7f71ec881a234b19af3f44.nq.gz
    ├── 6b1617af9064aa78141c19b91c91458c7c8cae17.nq.gz
    ├── 6bf57874de493de4f514f1569e7be7ddf50056f2.nq.gz
    ├── 6c8369db4f072ada727a689824ebae73116f777f.nq.gz
    ├── 6e23168f550e67c8d6e69c2c5f0da81dc1fa2257.nq.gz
    ├── 70e88c0206abfa8b8f6a4cbe7f6024db6123147e.nq.gz
    ├── 71a836239075aa6e6e4ecb700e9c42c95c022d91.nq.gz
    ├── 7239c66c87789e7b87bbe624a0f9a3f11e2f0636.nq.gz
    ├── 7339807751a66f0c33d8e71aae63eacaca8bc5ab.nq.gz
    ├── 736c9d3e9de2956ec4c75b33d00d17b9a9ae74a0.nq.gz
    ├── 7666a0451611252b344d03bee741044a9ebb9a70.nq.gz
    ├── 770af624413476155d8f060d188405adcf63610d.nq.gz
    ├── 77bea014d8ee418fbaea843e61ecafdc5ae5a700.nq.gz
    ├── 77c1db60a8ffa546dc8e718c7de53b98e6c81567.nq.gz
    ├── 785065569713ceee12bc8ec7e7022d237625f3fc.nq.gz
    ├── 78f4b24da800c749f7459b39a500274760b75d87.nq.gz
    ├── 796e5a4a48051884c37df99999d259f2d7799ce8.nq.gz
    ├── 7aa98f20ba37097aa7c2803e1f574fe64419fe13.nq.gz
    ├── 7bdfae5d2572f5b55762511b7d84595493406d95.nq.gz
    ├── 7c83a8608616e9591b59e8e42867ffb9823fb558.nq.gz
    ├── 7d33ffb2f7dba614bd48ec17a56307ecfbee8b59.nq.gz
    ├── 7d965ee68ab7b8e2f2c978f1476bc6a2212473b6.nq.gz
    ├── 7da351a5a35f3942cb52ff952016eba36c5059bf.nq.gz
    ├── 7dce17f79ee57d2a9e86f3529e79cd2891b6788d.nq.gz
    ├── 7e7bebec6fbd96acecaabf2947489a5487d1254b.nq.gz
    ├── 7f82661c42746d6579b73d1f4db6803ab4cad332.nq.gz
    ├── 7f8976b2c213406e76cc516a8c31eb960a2e7468.nq.gz
    ├── 7f9a633edef85317e55941a9980ce13b04824d37.nq.gz
    ├── 7ff2177c015b753842e64a4218612fa8d9e92a0f.nq.gz
    ├── 81a35db99e260548f396a120dec0ed85ce169281.nq.gz
    ├── 8250b2a700e3dbd8cef311bc476bc306d755e8f5.nq.gz
    ├── 82eb04b998989a8e1e80e5be7487fa71a9d3fcde.nq.gz
    ├── 837e341267dc77ae5eb62517e147d3a12a67dab4.nq.gz
    ├── 841e09ef1e7ffe99b9b2429b36ce73baf7ce15bf.nq.gz
    ├── 84e8767d29ed40a03a9795363b279969016f68fa.nq.gz
    ├── 85a5221c4d1d46eaa08b80724c12fec4e89575ef.nq.gz
    ├── 860c87ee5def0c32094202d5432003f5464c2164.nq.gz
    ├── 874dc4bd660dae3bc9ea155d44bb22a898d859dc.nq.gz
    ├── 8755e8f6e23a2f364323308db90715446fed81bb.nq.gz
    ├── 884fa2b7280037876d3b098eb29fcda615c90443.nq.gz
    ├── 89875dcb035c7751bf5454fc6f62546d879931a3.nq.gz
    ├── 89ab1ef8409b41e5ba283860935d7995a3121703.nq.gz
    ├── 8a1b8375b21de94cd9b34c399a322d6be999eb49.nq.gz
    ├── 8b276127be366e8a97dda2a079b079f74a7b4498.nq.gz
    ├── 8f4180ed1b200f8fef3758710100ac2c5897d132.nq.gz
    ├── 8fe53a1ec2fac8c7cb0a85b321adf7ff160c2cc4.nq.gz
    ├── 8ff3f06505ed1a813b53b4ce90f7a41f80d2b2eb.nq.gz
    ├── 9086a09bf902327d87a1d794a20c5a1f44682030.nq.gz
    ├── 913af39981d7c24330b9eaebb7428c03c4a5d30e.nq.gz
    ├── 91b6fc988bd1015f5874a4d71b96fe70ed666024.nq.gz
    ├── 9326cb01e4b0f88f9883602f7ce046d31c478a5f.nq.gz
    ├── 93878c0e308816c60d4e44d0e672e9830903d259.nq.gz
    ├── 941c3018201e1dbd09d4098f20823f46286ce1ad.nq.gz
    ├── 944797029d32d80e652fa29731b3763107a7896d.nq.gz
    ├── 94ccd63946fcdfb798890ba70c98aaa6d8bdb66e.nq.gz
    ├── 956d1b3e0f658c6c74e0390d62a25bc995eaeeca.nq.gz
    ├── 9593bc0f261f0fdee8a5290456fe79433e52257e.nq.gz
    ├── 95b488d8cfefb148f58a0efc5ea6ea9a1f526061.nq.gz
    └── 962c0891a1c0ffb7e06eaacf085e4f3f2299f154.nq.gz

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

[django-extensions/django-extensions](https://github.com/django-extensions/django-extensions)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
