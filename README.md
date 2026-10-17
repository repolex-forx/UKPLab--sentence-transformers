# Repolex Knowledge Graph of UKPLab/sentence-transformers

RDF knowledge graph data for [UKPLab/sentence-transformers](https://github.com/UKPLab/sentence-transformers), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/sentence-transformers
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1fa45b4212a53e7d6c8d3c2682f88743338179fb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1fa45b4212a53e7d6c8d3c2682f88743338179fb
│           └── chunk-001.nq.gz
└── blob
    ├── 00222d597586a742a1d191abb620b02d730a724f.nq.gz
    ├── 006da515ec29ebe52bc6ce20e08d69079e6fad5d.nq.gz
    ├── 00baac679ed745032af4f141b7dee247d86469d7.nq.gz
    ├── 0130da4d2398f59762caa2ecbe88ab92de76bcb3.nq.gz
    ├── 01714205bbb57bde91d410b892d4ff28ec030999.nq.gz
    ├── 029b3621817e7f092a5536fc4e1a6f5d35f732c0.nq.gz
    ├── 035462e8887f81eed11e65b4b21f28a031e4e822.nq.gz
    ├── 0382fe7493da3e2372b7d715490d794dbe54d180.nq.gz
    ├── 03cff357ac3aeded7b053aba4fd81944522bf7e1.nq.gz
    ├── 03e210f91961f04283f757cc00a5f27c492be849.nq.gz
    ├── 04224d2eea7f1340a36ee042e3cae6facd8d6f29.nq.gz
    ├── 047b0a2199c59ea26f77a9218c023a277b5a67e1.nq.gz
    ├── 058a5c644c69f92bfee1aa3b1f165383b7098c57.nq.gz
    ├── 05b01f7b77edb8666aef63841eb642b4f989aec2.nq.gz
    ├── 06be2be32c5770f226414a01c33199aa2bfc00d5.nq.gz
    ├── 07775351e786a55a6e1106bcb12cb808742d49e4.nq.gz
    ├── 08201513c1dbeec8fb3b8134619612bf1c52d7c2.nq.gz
    ├── 082683886b6b894067f085fd134440a818098296.nq.gz
    ├── 083c1711a01d4b2145de21ba71e63b3eaa390db7.nq.gz
    ├── 0926bb1d13d06d7c76c0872b6f5301bc6a7a8740.nq.gz
    ├── 095e2ed587fb403ff4c33a1039d4bddbce67e341.nq.gz
    ├── 099b960a54c2803bb394fae6794f5d6d9554c996.nq.gz
    ├── 0aa0da784ad4d498e9054eb963403de3f0fbd1b4.nq.gz
    ├── 0ae5ccc40ef6acbbbef077257b91ef0b49ce95d7.nq.gz
    ├── 0c1fe951beadb0e14f6ff343ba5e924f8bd1fc40.nq.gz
    ├── 0d0ecf5e166f8c0a4ff53e171531db2754e62cc4.nq.gz
    ├── 0d899a7f709a6be476e6dae8beeaa23958b83dab.nq.gz
    ├── 0d9b0cd1aa64ace86085774a0b7df1531668e911.nq.gz
    ├── 0dcc6087dc939f4053d1a04a7e3e75ad1cd27f41.nq.gz
    ├── 0dec489463cccf146e71331f6c91de5880b128d1.nq.gz
    ├── 0f944c90c16e7c712bdc5062b913909ab5ab59de.nq.gz
    ├── 0f9a57ace55f36190717df1d29d82d11c3a8cab2.nq.gz
    ├── 0ff1248c1092369975f930aaf7a55cd0f0895e49.nq.gz
    ├── 111cc0df45fad5682b3e42ed9fd3ac5199ad4b93.nq.gz
    ├── 112c65cbbb9211cf21299779cfcf45ffc82ece93.nq.gz
    ├── 1135859eb8247cd48958ce1535a43d652699bbcb.nq.gz
    ├── 1142795438a27b2cc6036019b0368a42620e14c2.nq.gz
    ├── 11be946d7a0f84d76d4b8b136c441f0ec6aafc1f.nq.gz
    ├── 1214cbf0d5230664ae829fad0ebb6ce4ed3fba2e.nq.gz
    ├── 142af04342590cd90a346369df4c7c0a776f7c0d.nq.gz
    ├── 144f3d75bfd7983c976c985b52bb86f8ad2bdcb1.nq.gz
    ├── 1474f8ea763070b4a615dc21f111c8e6fb2fbc5e.nq.gz
    ├── 152a2be4c9c1565ecc2c2116f1220ed0327d8583.nq.gz
    ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
    ├── 162a240e11070bd40158d9b826257fe552f3a223.nq.gz
    ├── 16ab821a8c3b310019587e78dda380dd904abb8a.nq.gz
    ├── 16ea619dbda3a9b1b793d65263493ecc534b20e4.nq.gz
    ├── 16eba858a142609beee806fe0595ec55f2d73e23.nq.gz
    ├── 17666aaf8bd4a20aa6eb9bffceab561422f388e4.nq.gz
    ├── 1766d4c2ffe50c34ffbc12c9d591c9821b5ea56e.nq.gz
    ├── 17e5cbac9d83a370d59972786bfa548fae405cbc.nq.gz
    ├── 18797de4f9c0389cb77c78f53ba83403b5609bab.nq.gz
    ├── 1892a4d721b6b958815355b5c991756347ac95f1.nq.gz
    ├── 18964602423fbe0bcf6ed56618f59cd87ce41ad7.nq.gz
    ├── 1921e54d9a0f65925ef75850e2eafabaa91f4f74.nq.gz
    ├── 19eeec4c1f2064e4e494896ec4325d3afb148caa.nq.gz
    ├── 1b80ac9c7bb9114480dabfaa07d1357646805288.nq.gz
    ├── 1c52605901ee89b5f014cd507e42c560264ad02d.nq.gz
    ├── 1c7bf4907e6f1602fdc2065731f9bd58e108820d.nq.gz
    ├── 1cbb796f9c928e28d71d1f0d6c8b48f9f248765a.nq.gz
    ├── 1d1fdf660b4fdaf0a49a1c75f8b7870ab35e5671.nq.gz
    ├── 1d404e8ac4bae0f51a52c6e4000bf2513dbdd54d.nq.gz
    ├── 1dabb2681fba99e6faf401e66ce2c22e7c6063e8.nq.gz
    ├── 1e560ef2aed647100adc473ff32c20e370e65cd8.nq.gz
    ├── 1e65e0a2d277b56594b0aba7065574edd8ae0261.nq.gz
    ├── 1ecc4c709f8a5f9bb86df99fd5ea629312200429.nq.gz
    ├── 1f327c43aa035fd15f2f289d6d22947433f77477.nq.gz
    ├── 1f7484614ea22b33ea753d6164c2362bff33981d.nq.gz
    ├── 1ff5cb7336f84b7e5cb4780078acf960b6064bdd.nq.gz
    ├── 211a83cd0934c826f60772b968413b5d4ce2f48f.nq.gz
    ├── 21fa416662a19a811eb5447b9953b222daee6930.nq.gz
    ├── 22567655573fc1cce39864106d1eeab34bb70c3a.nq.gz
    ├── 2266d72a7fdd7ab6ca92ee5d737cb446422199b2.nq.gz
    ├── 24d5ec47220d04cdab7663485a5d5be596a08f70.nq.gz
    ├── 250fe9c61e22974c13dff394e09db89c33ea626b.nq.gz
    ├── 264b3582f7895ac0f66bd51ace08910049aff89e.nq.gz
    ├── 26cd44ccd3ddc4a8dd53c6bdfae8b79e7e2be223.nq.gz
    ├── 26e3afa3c795d03d26782760bae6a347c39aa465.nq.gz
    ├── 272865cb537e8e9675dc547dd74210d7e6b0612b.nq.gz
    ├── 273926a8c9daf2aec8a5203444763302a332e23f.nq.gz
    ├── 27ac2ee7d2579c1b59f18b85fda8e2f8d55436d3.nq.gz
    ├── 295696c6bcabd5fea6fd77154ddaf9171e567773.nq.gz
    ├── 297a455cd06a0b5f99d5a42fb7e291e8573f7730.nq.gz
    ├── 2a1a4c952a7867001a45e3ee635c1816660a18f0.nq.gz
    ├── 2bd0a33fc5fef0c2894df137697601c4984f976a.nq.gz
    ├── 2d317ef6d166c712d6cc3c26ee59eb5023e5a982.nq.gz
    ├── 2d9048e540f395b6930711e5ce4ab7f860c998a7.nq.gz
    ├── 2d98c055295c9bf1e2f86dcaaaf540b324fc6f41.nq.gz
    ├── 2dde0333769b5b43a4eb71e2b99551b54efe0644.nq.gz
    ├── 2f5ae2d969ba1ce0f49352e263a71328152e1b91.nq.gz
    ├── 2f857097361742902cb161da08432daf93b3dfee.nq.gz
    ├── 2f8edc85be394c076d1fb92bddefcd4f1b8be6ae.nq.gz
    ├── 2fc23071175175141529fcba0e53a132f676b6a0.nq.gz
    ├── 2fe4c6a22b27f0b3de9a5b9904044e24edd7391b.nq.gz
    ├── 2fece2141cf684aa51311bf5f65492db5509baf3.nq.gz
    ├── 308d1543b196f0a902af9e4f36bd51d34e08cedf.nq.gz
    ├── 3132d27759a73fb0fdc8f79ab7d018db9c223145.nq.gz
    ├── 316a1f40148ee9d52bd82332107b165a06110b86.nq.gz
    ├── 320de4034352842dbcad12038f8cb497b09d7ae5.nq.gz
    ├── 32189ec43f65d45d7fd1df779482567e409ccbe6.nq.gz
    ├── 323a0b04020a1b1acd30b09e67f4fe2d03ac7284.nq.gz
    ├── 3479e2e9ed5c7cf19dbde75e4e2f853318c0f5d2.nq.gz
    ├── 352a91776a491adfafc068cdea09dd0859edb3e6.nq.gz
    ├── 352ba16ac91157a9367b32acd8f3f124a6a97ec9.nq.gz
    ├── 352db6ae3038371d40f795e1ab83d2c1d9129279.nq.gz
    ├── 35d9c96d0a562b252cf6816e3d3e0ecdbcc5b516.nq.gz
    ├── 366ef1224cc8666f1cdf7c4d88afad58ff6fc399.nq.gz
    ├── 36fadbd1ff2d63f1487285392a2bb89a42998e73.nq.gz
    ├── 3703f80f8f73306d37bdc445d0cd5d3cd4da5230.nq.gz
    ├── 37610952524631148bf84e27e2f913c9ab440096.nq.gz
    ├── 37c8381b1391d1e72b2bb39635a591cea6f8dd0c.nq.gz
    ├── 37ff06d5f2bbbde5f3b304c402d12388c7c1a59f.nq.gz
    ├── 380ab6ebea5c64db6032f0882b99acae3884eda3.nq.gz
    ├── 380e3a39938326c063e06fcec79c2f29f4763db0.nq.gz
    ├── 38db16929f751b3b0efa8fe2e0605a273cdc2371.nq.gz
    ├── 393029c4950ff8beaf83b3bcbc5cfd3ce9494fe2.nq.gz
    ├── 394a7a990c1290f65dfe46a97cd78ec2d2229ce7.nq.gz
    ├── 395de024f9dd88d43131df2077fb0e41a818a00b.nq.gz
    ├── 39d415d6277bba5e722276ced15f6f82e8a172b3.nq.gz
    ├── 3a2be55d2bef58e9ea4e89043b6665adf338fae6.nq.gz
    ├── 3a326fb61beb29ed92e342405671af36587ed58d.nq.gz
    ├── 3a7402cbe09c767eeb4dfc44c1b44025dc279131.nq.gz
    ├── 3adcdb6e6d12cc5a24597d3e5adc71a7be8d5b21.nq.gz
    ├── 3b280c1ae91561991e9e15b7ccad6d9c78592ac3.nq.gz
    ├── 3b507cb0d599696e3debedfb3f56586fa8dd573c.nq.gz
    ├── 3b541353f8262aab61aeb4ecdc9f5516b9d298d1.nq.gz
    ├── 3bbb1a8c20e6ab116fd1f6346f2f11c74dc7980b.nq.gz
    ├── 3cd251204acea6eb47ecfc24b5f2924b3e2b38e4.nq.gz
    ├── 3ecb93afe4f3178ca7350e753ad7397f57bb36cd.nq.gz
    ├── 3f2e1f6e058606f9c2d5d342d8b918bacbff96b8.nq.gz
    ├── 3f405bf51734bf0ce77b88d40c4576ae1fcd9bc4.nq.gz
    ├── 3f486f8c5322ce7487c1ea442055bd132d5d8357.nq.gz
    ├── 3f5605185f64de75a102af048aa310a24a287f74.nq.gz
    ├── 3fa1193f0e71158ad6112f8ed9bb3d7b1e1b0422.nq.gz
    ├── 3fc8a061b4a1ad4d0a589224d2dcc93da63f42e3.nq.gz
    ├── 3fcbdfe1cc80355155bc4e746888d991627cc494.nq.gz
    ├── 3fe3f95970aee54b12b3b7e34991667ff28dab8b.nq.gz
    ├── 400f1b89f7eb07d3174a85ffce5ddb363c9391ae.nq.gz
    ├── 4053435ef999173fed85030af932934379574169.nq.gz
    ├── 40ed70ed7b08c3e9b3687bd8d6237110c40d08dd.nq.gz
    ├── 427eb4be754e94b3cf64f428b683a7df61621e11.nq.gz
    ├── 429f7f16034084fc6a5cfa79b654c81c692f0748.nq.gz
    ├── 42b644a837616fde145f657a0a2e722996e7df7c.nq.gz
    ├── 42c13aa12a004b220f227a6ad0e765a05e872dbb.nq.gz
    ├── 42c5fad4374873d9cc034ebdfa563302c826cb0b.nq.gz
    ├── 432088a98eb657a4201939af36d21599e587533c.nq.gz
    ├── 4409d6f37437092d378255ac4f2cf9efb744d554.nq.gz
    ├── 455cd88837d7373a43c5c09d0993603582f214a5.nq.gz
    ├── 45b7b0b46bd263f8e6162f1617fff900e8f85e94.nq.gz
    ├── 46c4662b4f86ca980a66e00fad0f3f8554877888.nq.gz
    ├── 47e41b09911a62bc23a52a6684e51f42a7f4f793.nq.gz
    ├── 497ce3f5dff9b712cd45bbad4188071fc4348844.nq.gz
    ├── 499d3e992c7a19778105d816175b78c55075cfde.nq.gz
    ├── 49b4be9547e4ec109e3d4789ff2cf2e8f63ec4cc.nq.gz
    ├── 4a1739fd9aefa0402627f9e12438d3556be85c4d.nq.gz
    ├── 4a6ac66963fcc2ab5cbcb647d3f7ec00a2f9d634.nq.gz
    ├── 4a8c5bd61190b1e5ff7d2b1bd28a5040b66f31f7.nq.gz
    ├── 4a8e38dd180ebff1e6dd0c26dd15c754726a73d6.nq.gz
    ├── 4c288e11e125f0b2363bdeedda3a852921413138.nq.gz
    ├── 4db7a02958db1baf34bd3dea44f41b4b268eab8c.nq.gz
    ├── 4e2b21c181bb828c3a34fa8ad883944563e32b43.nq.gz
    ├── 4ee241c9fd5ecb7a80a70b5c6a367615a399512b.nq.gz
    ├── 4ef3717eacd35211ba0531188b540ca4896f2d68.nq.gz
    ├── 4ef4c0d01f18b8481b37b41f8b3a3dfb61ca960a.nq.gz
    ├── 4f958e7564bcc3da21cf6091b988133c70298f24.nq.gz
    ├── 502b4d45a932598062ed7b59edc4526f874ba4d4.nq.gz
    ├── 525c8782dedc4862d458c2ab0c908419ec9dcca3.nq.gz
    ├── 52ce8103be5a7e920235272fbd73e5b62954746c.nq.gz
    ├── 53b7383ec9a2416be59020519f938da1b61b98c0.nq.gz
    ├── 5483c62629afb4cfb048b7e323198739afe38d2a.nq.gz
    ├── 54a30801905f82a8294b394a6d2a34a573fa042b.nq.gz
    ├── 55389915acef35ed0850293e2d6b013e43970dba.nq.gz
    ├── 554601ca39f31032539bd906606efa113d311aaf.nq.gz
    ├── 55f9a01c8e40824e75a913c4a5fd17a3b529f3ed.nq.gz
    ├── 562da68f161d432ed681f69d10148616b3c1593f.nq.gz
    ├── 5682973e18822f9c591c6262f54d985d6b989fcd.nq.gz
    ├── 56e0ca393492969870dd1efe4eaac07217fa7909.nq.gz
    ├── 571c8146b74e91b3a29f99b4c59429e01efbcc72.nq.gz
    ├── 5726cd5e4803a1ddedbe28cd428305cdf9d81a2c.nq.gz
    ├── 578a0960353e840cd049210d3b861ea094f589fa.nq.gz
    ├── 58710baf309618f693f80d925cf5cd6b59a6dbd8.nq.gz
    ├── 588528c3cb6ffb3f4e8ba17e36642dd1f26b461e.nq.gz
    ├── 58a2ef9d1398074a1aef9d594f17a399d1716a19.nq.gz
    ├── 590e7ba516200e50c3ae6fa2aab4ee69b56d2978.nq.gz
    ├── 592b8a0a928f17db966b21e71697cbd39030c518.nq.gz
    ├── 5963ca3f4f65e2a6813034df840a3e5a2448bcc6.nq.gz
    ├── 598e8c243a955b3ef5f7636d8ee3f7681e0fbd92.nq.gz
    ├── 59953c83f245e428c53eea436a1536dd7e3d348e.nq.gz
    ├── 5a791416184c08423b0651e95725a73ddadc54db.nq.gz
    ├── 5b8bb45971c4d2f11b130a46222efc390ec692a5.nq.gz
    ├── 5c2071e4dbd68c1c802aa92c19fd50c77ed1893a.nq.gz
    ├── 5c6a3be705f224a927950861c92c4a2210bc2372.nq.gz
    ├── 5d0d574226c1edf47c4d4009430fd49cdcb8b689.nq.gz
    ├── 5d3eb7b12c9f3b86549ae2e18c0b4b950b4e8e87.nq.gz
    ├── 5d90f312634db80a44c8b892b4536893f26dc6be.nq.gz
    ├── 5dbc563ef798ffeb72030b074614830bad2f8131.nq.gz
    ├── 5eb0f528877efe590d1e25c2ab07ba2deb73c9f1.nq.gz
    └── 606ee146839e6beff47719a615f09e5953f88270.nq.gz

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

[UKPLab/sentence-transformers](https://github.com/UKPLab/sentence-transformers)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
