# Repolex Knowledge Graph of iamr0s/Dhizuku

RDF knowledge graph data for [iamr0s/Dhizuku](https://github.com/iamr0s/Dhizuku), parsed by [repolex](https://repolex.ai).

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
rlex download iamr0s/Dhizuku
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5fbda16acbf845f7c812fc8215e3a6fdd2a1fb0e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5fbda16acbf845f7c812fc8215e3a6fdd2a1fb0e
│           └── chunk-001.nq.gz
└── blob
    ├── 007d7a26b4a7ddeccd452d6506f9578be57220bf.nq.gz
    ├── 00bd92b65ee6caca997d45e9ac4cc321e4b5c80f.nq.gz
    ├── 018ccb543c05f03cf036b892e52335ac9fb5ecef.nq.gz
    ├── 02714db8056be2933be165b9b973720fd8ed5ff9.nq.gz
    ├── 028e189c291fa214e446a2df23482d0f8b40e728.nq.gz
    ├── 0337931363b6a86784f33ce4d83bcc6ebfe19b76.nq.gz
    ├── 04abd0aa2bb73c80d6252e67a93b2c0628646e2d.nq.gz
    ├── 0614db7cb77066fb975fde010544c5b12be78e19.nq.gz
    ├── 071cdc40521b35d65335176f376b16bead07de2d.nq.gz
    ├── 07f5f3c6786456bb6adc0c2b256816c496eddfc4.nq.gz
    ├── 0ac125c27996686923e4a64ad07e319f839729cd.nq.gz
    ├── 0ac8e545b56a9b528c3f80db2cb0882bd445184f.nq.gz
    ├── 0ca5f9d2be8c6aee86018c2ba7d2fd2a6ab3ac2f.nq.gz
    ├── 0ca60fdbe9103eef0d3cea21e5c7628eed0d3fa0.nq.gz
    ├── 0ddf42b9514c2034be236c0e69ccaa7a4f0c2015.nq.gz
    ├── 0deb3bddc850f9f1e086639eacd66ff7ba0577dd.nq.gz
    ├── 0e21032673982cf4bf4df01b250dd6d7feaa69c6.nq.gz
    ├── 0faf9b442dd6837c605a9a8f898630f95029fdeb.nq.gz
    ├── 0fb92dc81a67f662d5e54b82a598917141384375.nq.gz
    ├── 1052af1daa45faf4b5b612b85d74755133bf35c0.nq.gz
    ├── 10adef77f8deb3bef3f89f5e5d0d55979793838f.nq.gz
    ├── 10d8c714a32265a84c13242ce90c68686cc0db5e.nq.gz
    ├── 1294a81d0020f551e33b386c09fe6d8b4fc8a8ff.nq.gz
    ├── 136900a31f089db7381704cab3c4435aefe00a3d.nq.gz
    ├── 142dd8092bf4561ea32c31bd6414b6fd6b3cca8b.nq.gz
    ├── 14a4f61e1599b0d8814e43d9570535f59f7c71df.nq.gz
    ├── 14c341276eb488830cbf05da23eb326c690799b4.nq.gz
    ├── 15c17c7a2192b3e303c40ba3e6a377bd60d085a0.nq.gz
    ├── 15fa4186289a2f35ffd865b20f77b52992d01d93.nq.gz
    ├── 160cee5ebfef6db41a1e68b2f23844d2996fb547.nq.gz
    ├── 161b8516b8d909d67e314bb2450a9456eff6e455.nq.gz
    ├── 168925bc2e6234d4c6463691f72de160abc7c62f.nq.gz
    ├── 16d6bb5afdd74f730b8fa5043e03b7f1ded8614c.nq.gz
    ├── 1754b0dca3262a352f1fe74670a3bd1d13e31ea8.nq.gz
    ├── 1761b742e146101ef75dc374f81f462786691b96.nq.gz
    ├── 17d9f8a145ead8fbdae11a89225b73e1d7237f21.nq.gz
    ├── 18157aafa2356be33d0fece5c2f880f982c419e1.nq.gz
    ├── 18711c11c9dfbf5d5019b8f7f1628f307194a6f6.nq.gz
    ├── 18a95797d2d78b89a6f969106323a75c6155a7c8.nq.gz
    ├── 18b749d3f132c0c9d130bfc6ead6557d5b6e8a7a.nq.gz
    ├── 18e2e300221ca41db7e85ffdaacc2ec2e1e7ddaa.nq.gz
    ├── 18f203cfe39af7f5baaa416cad6132abc537a3ad.nq.gz
    ├── 191c74d9ecb648529ae8525b69788668f8f403cc.nq.gz
    ├── 19b390533ee5140ba672001fca3e4ae7b2408f7c.nq.gz
    ├── 1b733e5f79f9748579b359b60805e368ea9fa220.nq.gz
    ├── 1bfbd3dd69b94af7adf74a32e562b3e7e90df355.nq.gz
    ├── 1d3bc451b51f207648db5f9068f6718422ddbfbd.nq.gz
    ├── 1dbd6fdfca032f182caf6c5a451e4e8f1dce0953.nq.gz
    ├── 2012b24a585fff497da5744b71de80a771c6e809.nq.gz
    ├── 2029fa35082ee2076e82fe90a3ee0f4047d6d47e.nq.gz
    ├── 248d9f4a303071881453384dcc6f41656230ef7d.nq.gz
    ├── 249efbb032ce46a80c687c0723eb172e85f6a136.nq.gz
    ├── 24da30d923d4bb7a418eb6dfbd3fcc1b2b8c0462.nq.gz
    ├── 25b415708165f089f959115e1d8831d896e14b46.nq.gz
    ├── 25e7bcf8c746e8cbc89385d00733bc2efc4a5aa7.nq.gz
    ├── 260501966d0e5bf80176018aba73af7ed88c9193.nq.gz
    ├── 26c7a178a6433f32918fc08fb1f300f0e08edc49.nq.gz
    ├── 28a6d7e2b8a614e14254566886043b728cd89575.nq.gz
    ├── 28ddba6f714ae93c0867ae4e343225757b29a48b.nq.gz
    ├── 2992bc46a5056d0ef0c5c77e0115436b847ed42d.nq.gz
    ├── 29e0cf0a2ea4f985404c8ab23eb183ae0b0e6f21.nq.gz
    ├── 2a041ddde43445d85a26f36da986a6ad54c9806b.nq.gz
    ├── 2a548ec5ba1631513d7a817be9a540a9e4033867.nq.gz
    ├── 2a90ea8ee0903e596b5d6647f97c9aa5087cb357.nq.gz
    ├── 2adab4fe447f184ed5268bea3200d8d8f125cbd9.nq.gz
    ├── 2b2bc1f36d1d389486b2147a1369741ce8e49afe.nq.gz
    ├── 2bfb6ce5ff26258374ecdb2fc65704e4d72099c9.nq.gz
    ├── 2c9eba3d660d3084d047bf8bf09cea71d347022a.nq.gz
    ├── 2d9360c674514e3bc56fa10ad7cce2bc16eb5ed7.nq.gz
    ├── 3033ec86a37273676b6c0003ae6cfeae90df48e1.nq.gz
    ├── 314aef2ca30254d00b00bf9408b773da35a45d1e.nq.gz
    ├── 3185a43f78fabec15ca99b0ca6bf1e666218d5ca.nq.gz
    ├── 31bc1ff9ae5a59f797eb375c26081d02fcd84993.nq.gz
    ├── 3298752120f55246c6e9139400ee1a66a012b3d2.nq.gz
    ├── 33135d699f5d817c753bce14875d61de4bbb1669.nq.gz
    ├── 331b9e652a054f0c2a4e061a54528640e3d7e137.nq.gz
    ├── 342e16241e0227689fbc6103a094adeb042591bc.nq.gz
    ├── 34eb55f7aa37466919459f2f400df570f5e26647.nq.gz
    ├── 351025c8e7e64da5ec37cd79454cfe08f10f13a3.nq.gz
    ├── 35291bdfa53605dc80b07a26b6be569cb2060a5f.nq.gz
    ├── 3555b8a3a43b7e1746e9050056fbd2c5e619d5d7.nq.gz
    ├── 3703f735fc171150b3882ffc7da93fefd6dbac71.nq.gz
    ├── 370e339c30e6e16456c0ee4e6469002a261e0f99.nq.gz
    ├── 37bc2a9f815f982771ca1e3ddb7e58d5488fe808.nq.gz
    ├── 37fbbd4bc7d302c21f2ec18fbbacc33dda1641b2.nq.gz
    ├── 380e531aa3090a1f923c6268e26fde388cd07895.nq.gz
    ├── 38264455e8e4c950bad97dc505a29b3c202a497e.nq.gz
    ├── 3989a2ac70155750c1f3948cb79d44088e5d8f52.nq.gz
    ├── 39eaf2c2d85eb1fea28304c4f5af668c1f93b598.nq.gz
    ├── 3a35c5d32a5f2e038f631cd99c2ddd9c63cf190e.nq.gz
    ├── 3b6788eebd471fb5191613f9e583e51686d9d5dd.nq.gz
    ├── 3b9c5a53a6e87045f4c0b00ae1344a7768f0e741.nq.gz
    ├── 3bb3d864d705219fd8cf5a7b50910709e596fe72.nq.gz
    ├── 3ccafd6f685f65d11da7dff011c7b5ce353e4d54.nq.gz
    ├── 3d00178bca79165990d74f23247e3ad233fc026a.nq.gz
    ├── 3d05ef3895ea8d4417d6677e04e10504dd742077.nq.gz
    ├── 3d1e0ba5378df43eb5e144e1157bd9d82f25f463.nq.gz
    ├── 3d2db7d6eb47155e9402fff80f4d1350e4996959.nq.gz
    ├── 3d80853920c22aa4dfb2a5c26fb3c691b3c60b55.nq.gz
    ├── 3ee44eb5e9285fda17172d00283199759b5a18cd.nq.gz
    ├── 3f486f9dc4ee281e00e4d67482939e0342c00a69.nq.gz
    ├── 3fbf645a70587a37bb82a54c436d9bd2971051b4.nq.gz
    ├── 401ba8b5612c0de4d26207c0d73ba30e0e325c5c.nq.gz
    ├── 412e05835f11cb307a61f4f337fe61312c6a952d.nq.gz
    ├── 41a209d0998f275609a7698281a9193c1ec1423a.nq.gz
    ├── 4306343f9ba769d53365f2e6cf4a263e4b50a3ae.nq.gz
    ├── 433d378d8e100e2a0eb413301b384c6e9276876a.nq.gz
    ├── 43ae8953bb1f2d3cebe285bba87ebc3778862f68.nq.gz
    ├── 43e587913e3378767a9cb6bc33bd3c03ec0f9cd0.nq.gz
    ├── 4431a5dbdef3e8cb193a73d7330e1c9edcdf8b5e.nq.gz
    ├── 45b17e7c03942c61ab61e7cfdef2eaba143a3aea.nq.gz
    ├── 46429c0f9d8ed9013b959433cd810fddda77f0f0.nq.gz
    ├── 479139af836578ed30fe843dc444aa4fc7ab2f7d.nq.gz
    ├── 47fe5409f18743cba6a4fa7e893c28d874e8dcf2.nq.gz
    ├── 488fbee074e332763d51b7e0b44be51ae5e4dc38.nq.gz
    ├── 489a3544df42b599cd80e672c8e13a38a09ad174.nq.gz
    ├── 48b2078670d32247ba96196dbfdc518c6108714f.nq.gz
    ├── 48ee15aa123fce7d73335d8791a1824b4d10688e.nq.gz
    ├── 4909d2503c2f64fd8d209edc47639b69ea44c38d.nq.gz
    ├── 492e4082cf838d58099ac2b81a171b10e8e64b4d.nq.gz
    ├── 4a468835bbb99c9b48a710240528dc4a76bf739e.nq.gz
    ├── 4a4f9913711d09b1f7acdfce9b046ff861c9dfcf.nq.gz
    ├── 4a7f9ea52c43a226f3cb67b7dcaba6f25852116e.nq.gz
    ├── 4c557fc34866d77b0a4dfdea3ad116ae64227e03.nq.gz
    ├── 4e2593546c3e712fba3fe771379849f29c0885ba.nq.gz
    ├── 4fb48df5395c389e852440e7f0f35287c4dc634e.nq.gz
    ├── 4fe21cd401f2099c4cdcabb242e364fd9f4bf873.nq.gz
    ├── 4ffceb7778f3c006f4ff6bbf2115834c93debce9.nq.gz
    ├── 500b34454f69ebeafb212d9b6806d9cca4f6bb9b.nq.gz
    ├── 504bf7cc412458ad9962ce60ff1d00b5621684b2.nq.gz
    ├── 506661d6678596e10e377b0e5a20f283a2a36b80.nq.gz
    ├── 50d9aaa174df2093b18914d6ba29eb2b370b676a.nq.gz
    ├── 50dce04de8cd1f5c54563f173ea061e3e678e32e.nq.gz
    ├── 5108a6858992de4ed9931a9dfe04e7e013b52435.nq.gz
    ├── 511c1d0f439747f0be6d3a5b9773ecb731e2e119.nq.gz
    ├── 514e30dd3f6d3222b85b14b7c4bb065199d6b124.nq.gz
    ├── 521608df4ed311202b71919dfe8a3fa1b7d3981c.nq.gz
    ├── 5290d31a782552e560853c1fbbe97a62653f5f3e.nq.gz
    ├── 52a8ff2576b08325144970b16a783eb4723f995f.nq.gz
    ├── 52e8533ba365e224e823d947d32a3d9642ba7c0a.nq.gz
    ├── 533f0ba590a046de39f0d48f67ccf9466aac4e4b.nq.gz
    ├── 538ad582a07b475bef48fa10ff304eee9a8c9918.nq.gz
    ├── 53b367c10f1e0cad2cadf1549ee6d3c464b37a44.nq.gz
    ├── 542380477fcbcd9b5e18cae310062c4305b69c86.nq.gz
    ├── 5506cc15cb6cb88b6db7881e9c10e4f73fb8f42c.nq.gz
    ├── 550d122d100aa36c4d64147088c4f68b6dad83f1.nq.gz
    ├── 553aada0fb22768f99721220e0aaa7d79eb7ac7f.nq.gz
    ├── 56c32d7d8b6f7b32c14f8bafa38d0f2be5781ada.nq.gz
    ├── 57a117b754839efc18c41178e039457f451fd478.nq.gz
    ├── 584d2f04163b9c66c02d855daf31bc393a429e52.nq.gz
    ├── 585911cea8fcbf5ebe306e51ef23b58f49a6cf54.nq.gz
    ├── 5907d39c37e5c2459269d48fa629f6e761fef763.nq.gz
    ├── 591ae9aa85acc0e7d0fb795b5d1feb3ea7699720.nq.gz
    ├── 59428de3bfbc3b261c6cd623d79c3dac0cae50c1.nq.gz
    ├── 59571aef33650e45f8ab0edfbd8f4ba01153ae75.nq.gz
    ├── 596ac6888b03e5ce70775b06f519e49fe18ec433.nq.gz
    ├── 598b4454c8700cec186a843728a2fa8a4d973646.nq.gz
    ├── 5b335f62aa139feeb5834b82df8eed2108b67de2.nq.gz
    ├── 5b5df16d2a46cda61f7e5e8c95e42ca21b1bcab6.nq.gz
    ├── 5c041d41d3372c135ece472651751db2cf3398de.nq.gz
    ├── 5c314cbe4d44dc7997ff42a6e964ceb5d670633f.nq.gz
    ├── 5c7099f8080459ab918cb98e02e3c548576415e4.nq.gz
    ├── 5c7754bba9df1774a745b7cb2c08ada38856c8f5.nq.gz
    ├── 5ccac79b5cb91ab5ed6fcf3446ef8f645308692b.nq.gz
    ├── 5d3252a7d5c1a0f37d6ee0ad404f86cd9e588ec4.nq.gz
    ├── 5d983272b424e174646e706f4dcbf87ea7f8faf8.nq.gz
    ├── 5dff164922f1a9f7926b98e9e2f5ca2ea60bd97f.nq.gz
    ├── 5f972b3a79df1b7013d2d0e0dfec4a4ea067e7ad.nq.gz
    ├── 5fb96200802501a92344a9159be82f4fad456800.nq.gz
    ├── 6045e4ecfd76d2fb8f957edf2a02177563f62300.nq.gz
    ├── 607ae0d6e6fbe6411e8bb2c97f3c2032a22ea2b5.nq.gz
    ├── 63aa823cfed47a2f8feff6874b219183950202aa.nq.gz
    ├── 63b0036b6da2cdbc780fba541f6b3bd22efdf56f.nq.gz
    ├── 640342ddcb405dcbaf2af22150386d5346c30c35.nq.gz
    ├── 650ec06254e600ce09f43cdce4df3cb6dafc9f55.nq.gz
    ├── 6539695d3ec79ca31dbb00cf196b7866896a7dcc.nq.gz
    ├── 6540f97983f351b99f5e36ad779d8c22eb7f736a.nq.gz
    ├── 65545fd6d98e5f4b1d757539892e2be400e5e9df.nq.gz
    ├── 655e34c9cd21070f7f0259a3a51c0b98f404f6e1.nq.gz
    ├── 662886d44e32e3fd477a7f2f8f079a09f86eb29a.nq.gz
    ├── 664eee59a09e1ab9cbb24fa7e23aaf78110d73b9.nq.gz
    ├── 66d256bc6b66d20b73ea4f501458275d0984b256.nq.gz
    ├── 67bcd7f63b89add4998c09548497cbe566e5f81a.nq.gz
    ├── 67ffbcfffb9665cb391be44b4223b611ead279ad.nq.gz
    ├── 6899f678e9a0cef3ce5288b9c9fde4640914011f.nq.gz
    ├── 6952a4f74be37035b256fd2df8ccd2a419739219.nq.gz
    ├── 69828f7230f5b3e667f06eb0a46af849daf364e9.nq.gz
    ├── 69b98add1a783424ddf27d41cef5c5b8279ca3fd.nq.gz
    ├── 6bc962324baa9b844f889e8ab895b3c5a240a867.nq.gz
    ├── 6d213c61a1a9909a5a378bb4ba35403f48b6ce46.nq.gz
    ├── 6ddf3b189a6859660bfcfd2cd302ee408774c6a7.nq.gz
    ├── 6df193e8ba57936c1ab91b26e497d8e681cb753e.nq.gz
    ├── 6e929d778c158aeeb71c06dca2c4bd9528aa7c84.nq.gz
    ├── 6ed68bc167d29c90659fc417bd868ad2e9758489.nq.gz
    ├── 6efee56775b0818e1f4c94dfeade3ac21fb870f0.nq.gz
    ├── 6f3ca6d2e6292aa1dc0bf4b455e7c53785d03371.nq.gz
    ├── 705c70dd70f357861dd66ca12054a47705fc0990.nq.gz
    └── 715e174d0b224ad4ccb3865fbe4b39aef2b226d7.nq.gz

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

[iamr0s/Dhizuku](https://github.com/iamr0s/Dhizuku)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
