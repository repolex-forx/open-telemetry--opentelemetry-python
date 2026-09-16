# Repolex Knowledge Graph of open-telemetry/opentelemetry-python

RDF knowledge graph data for [open-telemetry/opentelemetry-python](https://github.com/open-telemetry/opentelemetry-python), parsed by [repolex](https://repolex.ai).

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
lexq download open-telemetry/opentelemetry-python
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1a178fcc5c689516849ced80fb2533fe7db7a80f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 1a178fcc5c689516849ced80fb2533fe7db7a80f.nq.gz
│   └── repolex
│       └── 1a178fcc5c689516849ced80fb2533fe7db7a80f
│           └── chunk-001.nq.gz
└── blob
    ├── 002639bf2ef4f7ee38030e0dcc5dc2d4c786b20b.nq.gz
    ├── 007481ae9ead122b22c3556d7510c4446ebf386c.nq.gz
    ├── 007610a90ad67a70cf80fece758f9161be3b05c5.nq.gz
    ├── 008e1f04d512fe1e2fbd58ddfba8e1c0d117241d.nq.gz
    ├── 00d1e7cfd51fd8870c09fece370fea4309b4a568.nq.gz
    ├── 01486fbda9c9e19252a7675559d6074969b4dc09.nq.gz
    ├── 01a913f22a30466ac082120a38cf049e3a15545c.nq.gz
    ├── 0205446c808aab2209fb7b42564eec363fa85742.nq.gz
    ├── 02381147f9b06752c18aa776fd2a0347fdaa858b.nq.gz
    ├── 029b95f5c0f137822c1f6bbfef91daf5c80f87a1.nq.gz
    ├── 04d60847f02fb7e1a9565248186767298a153c54.nq.gz
    ├── 05fc0fe03d8c22188761ac811d83cbcc2398e861.nq.gz
    ├── 06b6143f0940ae59f9a1d2cbb6567fdc40eebf05.nq.gz
    ├── 0724f33d8cbd7f396b3d8418958a44db1e122373.nq.gz
    ├── 077d2fbb2b8862ad397a74d9248401f72bb0a58d.nq.gz
    ├── 07c7b9aa6e49526a511b460196023ba0dd046ab5.nq.gz
    ├── 08732ac0253246a65f41911467c817d9320a2053.nq.gz
    ├── 08825315bef55e043fbf3fae12714de1822ad458.nq.gz
    ├── 0893268eb76a26679ef6bd5ddaaac08b8ec9268f.nq.gz
    ├── 08dddb03cd88ebc18b7f6a7586536d8e0cc4f723.nq.gz
    ├── 08f6343e73f1580d983b3bf66a5915527212804c.nq.gz
    ├── 09057ee1c15435bdcfcd859c648b69fccb5faa83.nq.gz
    ├── 0a03344f883c748ed3bb8e11d8bc003ebc62d488.nq.gz
    ├── 0a42809e349524e5607296e4dc14b544544fe8cc.nq.gz
    ├── 0ab6dd8fc90fd584f3416e8bf9e8215fe1c2df3e.nq.gz
    ├── 0af527cf3a3da9876397966f5d0ec65e3527890c.nq.gz
    ├── 0b2ccf83b4fa8eb2d2d9202adaad4dd82a99dba4.nq.gz
    ├── 0b62b1771488fd6c312bf15e6fb66bf734958e33.nq.gz
    ├── 0b640d30bf9137afcdc298fb6e397595cfb5cd77.nq.gz
    ├── 0b79bbb2073a379490ea8452ba7c1bac609c50b3.nq.gz
    ├── 0ba4ab8ed470bb9db053c25f8b3e67d519c4297c.nq.gz
    ├── 0c0efaaf911f2e97ddbc43590ef460d1e164f422.nq.gz
    ├── 0c1ae08807dcb2eda290c179167b997adde0d489.nq.gz
    ├── 0c86902e4ca79a8cdd00fd9033616b97cedc6d16.nq.gz
    ├── 0cf5c8c59b3d6907c6669670d06e80b63118cef6.nq.gz
    ├── 0d7b15db7b2938af55042b17a743610bce5a4513.nq.gz
    ├── 0d8944805852cd94e63d259027ab90df611f7eed.nq.gz
    ├── 0d8d9cbb92d6d0260e48c7156a87d311df669729.nq.gz
    ├── 0e3b0c7d9cc0657934e5ff86e4e3ec8a45c2c32f.nq.gz
    ├── 0e669403d9410bca7847c5e5329d3464aae90580.nq.gz
    ├── 0ea36443bcc4ab8fa5de993ab45730d3900196b3.nq.gz
    ├── 0ea5f48bcdbb294afaeb8c61b3e3e45505a3b2f0.nq.gz
    ├── 0ec59e4cbbd5f556a32ce1004713f463f19ceedd.nq.gz
    ├── 0ec7d594ca5298c21f48998eaa0b9241f3e8d3a5.nq.gz
    ├── 0f12b7b66ca1faacb4de735dcd076b497d7f83b0.nq.gz
    ├── 0f374be93ee9a6ad65bcf1159a59add9d041db82.nq.gz
    ├── 0f8c3a75521d1652320f74e409ae71519db6df00.nq.gz
    ├── 1191bcc30e08b8e5f142631eee52eab9f4fbae06.nq.gz
    ├── 1195e7facfc081f61faaea370477cb004a640a55.nq.gz
    ├── 11b3b12d4b4a76bae2d828c193e5959b0a009dba.nq.gz
    ├── 11f4c154a8e338cbd459eed1d745e27f55ed1f9b.nq.gz
    ├── 12801dbf3775962dba51067f55aea0a940fca5d9.nq.gz
    ├── 130fbbf39ddeed004d7382c603af8b1702a76339.nq.gz
    ├── 13491c0d63a6768e1a041b2a0d138705edc3d935.nq.gz
    ├── 134e246e0421cd51e63fdf234354b27533ee4625.nq.gz
    ├── 13a803a56f32ce189a13281d06231015fe061d33.nq.gz
    ├── 13c9e50a4ef904afcd45754f6755aa7840b79f5b.nq.gz
    ├── 13ef66e75a2d637143196fecfcc4cf884ec0fa82.nq.gz
    ├── 1461a891cc6fc2e664288fa7ff1c5ccfc3914870.nq.gz
    ├── 1499a4bf8e6a36b32ce0cf7824f7800f5eb78aac.nq.gz
    ├── 149a13d9b930dfdb654c56a8f8df32db1ecc92cb.nq.gz
    ├── 14d1894153b3f768c24e84a860324aea504dcb64.nq.gz
    ├── 14f8fc3f0d1218084629cd2e7478e8b2ef23c59f.nq.gz
    ├── 15175428d3d95d0bda13fc4ba4cac36946ab8989.nq.gz
    ├── 152be1ea01d09d3ec66500779547cbff06aa3675.nq.gz
    ├── 1619da9716585bd4fce07328e9f2d2a720717e54.nq.gz
    ├── 163edcf97b913b58b49b6337063068747d3e6485.nq.gz
    ├── 168d2b25af72f76092480143fa5a412f3ec95d80.nq.gz
    ├── 16fd666dd1a4339ad819495e7c51c532fd38bc38.nq.gz
    ├── 175a10e860592f88359855e984bbaa429f48944c.nq.gz
    ├── 178a0b889f914e8397882d8d42973849cef1d346.nq.gz
    ├── 17a2b85bae81d2f0feebee06cadfb4b3cc08709b.nq.gz
    ├── 17c538863407b31a305bd11d8dca2a9ac431bdc5.nq.gz
    ├── 1844b46a42c5b946c02f4a1b7231367a1624de30.nq.gz
    ├── 185e7006e404237a4d41ecee7a1f94bb6e695e28.nq.gz
    ├── 18b8b157340b768d7fba9e16ff628f3a8f22b8db.nq.gz
    ├── 18f6f68a514b79801d89a21aff63c334d7d69be7.nq.gz
    ├── 18fced706125086251f67eb9c6946f26a423e0ab.nq.gz
    ├── 18fe3f045cbc2935d37d718d2c0e82f404e6bac6.nq.gz
    ├── 195177f0256f8c5bab4456ae27b7746636197209.nq.gz
    ├── 1965f3d7d34aba16660ef65ede43123909ef358d.nq.gz
    ├── 19b189e5b9c96c90a60c0ba61aba5dffc3b6e4e8.nq.gz
    ├── 19f30be795e3130fe4d01c1be58382fa5ee77ac0.nq.gz
    ├── 1a8bdc9aa2e5fce20e88a3ec94fefcabfa2d1323.nq.gz
    ├── 1ac1d17821eaba4a79ddff6a26836dd93e059fe6.nq.gz
    ├── 1b6d27e3e01539b7732f3c79111bb612e3e0ed60.nq.gz
    ├── 1bcda539bbd79da52d1f69934b423f83d6bd3ad4.nq.gz
    ├── 1bdb7d228c26ee5a510ea1392b7c956e935eda7b.nq.gz
    ├── 1c0f82ac0558cac95b306aeb5caabf313949abfe.nq.gz
    ├── 1c4374e70e102dbb5ece2212186e904c825dcdfd.nq.gz
    ├── 1c7cdf2cb5a4d2d555e351fbec111c6eb7ebb102.nq.gz
    ├── 1cd6c8da46615ae389d450859d4de08b6b2cfece.nq.gz
    ├── 1d5ff3406f2e8d330bdc8ff6512ea700a4e48ac6.nq.gz
    ├── 1ecacdd96d127edc22ac28a8cc7f7a53e8ceee3a.nq.gz
    ├── 1f210a384f62b2ef28b524ed260e24f70348a214.nq.gz
    ├── 1f4a16d7f69800943d4d002aeb688818cc965da4.nq.gz
    ├── 1f6659a79736543c19f5e14e70df8ecf5d5e2efb.nq.gz
    ├── 1f9fd368aa10b67078045d392bb1827140a340fa.nq.gz
    ├── 1fa93a71eff12a9821837b940761a48969a1d52d.nq.gz
    ├── 2012035247ae069ce57c06ad5a8629e12b569252.nq.gz
    ├── 201c9bd87645e75a60f979d3c7c2e3bfbf73b255.nq.gz
    ├── 20609551021b9e52041c361918702c828b1dbb35.nq.gz
    ├── 21c532cbc007778e6beeddc3c94ada93f697d9d2.nq.gz
    ├── 21c5dc15622aab27e3e61834e873f9acbc885fe3.nq.gz
    ├── 2273ac80c02a2ca0aff2afa663bfc48ee44aa327.nq.gz
    ├── 227dcf5b1ff999abbb27f5aca27537429c1972a8.nq.gz
    ├── 22abfbd3cfede3e57077cd5b51df6238c409f3a8.nq.gz
    ├── 22d1ee9f75e62221898c4ec00f31dbfaa2e3d75e.nq.gz
    ├── 242437428e50a2d70caa6823b32203deeaec71e9.nq.gz
    ├── 2445ca879b706e0070fdc6fa90bc7bc9544c3402.nq.gz
    ├── 2460e4f332c1e8212fdb5563dbf532e12f5df98d.nq.gz
    ├── 257351135f31203c7550a73067e747a4c0c6f7a7.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 2653f54ade40c52efee8bc8dcce2eb3ec225c155.nq.gz
    ├── 26770c9e1f486b932809a93bbb95a7b781eb0e6c.nq.gz
    ├── 26fdb650f27900f9ab8aaf9174269a70afec2e62.nq.gz
    ├── 27703db859badb6f435e514309949ff4ca263169.nq.gz
    ├── 2799bcbad92319afeb70cddb671a734cc2b96a20.nq.gz
    ├── 279e1aed21e5096c0589e0a61d9ceb56ad71c4e0.nq.gz
    ├── 27f573b87af11e2cbbd9f54eb1ee285a58550146.nq.gz
    ├── 28237f09c4bca536ae9ea063788e8a3abb84cb76.nq.gz
    ├── 284675cf0809ba550985836780bdf98b682d1aa0.nq.gz
    ├── 28ecd03d3ec7f479c82b9368e9fcdfbfe089d6dc.nq.gz
    ├── 28f33f097cd8c89b19090dab78ebb9a1b76a2656.nq.gz
    ├── 294a7c4b09cfc3e7ec05cca5a93a7fe4412124b3.nq.gz
    ├── 2959163eed81ee674b2001e9e5fd843e1719b934.nq.gz
    ├── 29aadeb72ba55e8ab4c9ca934b84499d7f2eb323.nq.gz
    ├── 2ad571963b6f4e1e667f83ab025a1620a23a3f6f.nq.gz
    ├── 2af57652000faf1caa7a513855549b868f6fc9de.nq.gz
    ├── 2b3ff1608ce2acf02f459aefccb2d3958dba455c.nq.gz
    ├── 2baa967f8adb054e59953f88478116b3f8b2db09.nq.gz
    ├── 2bd4041b66aec1382a6987948b123072943139b0.nq.gz
    ├── 2c2224664bb6223c54a308004ae362063be2979f.nq.gz
    ├── 2c34d3cbaee774681f817c9aa1285a82665ef43e.nq.gz
    ├── 2c480f5e64eb8dabaa20b6d44998857c91e3fcd7.nq.gz
    ├── 2c5b27a135b78f9e9e1322826495f397dc8498ad.nq.gz
    ├── 2d1321df81b2712ad211ee1ee1a2a936893f63fa.nq.gz
    ├── 2d336aee8340c11c15bcb80b2a58a474783d031e.nq.gz
    ├── 2e066e102da9ca93de04b80cb3a0c1a674e59092.nq.gz
    ├── 2edcf7e9e829ee0edba1617387a49058b9fbfff9.nq.gz
    ├── 2f2c894e4a7dd85a0fcba497e041e7f9d0405f6d.nq.gz
    ├── 2f6e47a178cdd35efd12cb41e0e9f7dbab5aed76.nq.gz
    ├── 2f7aad25c6ebb665683484c370184562e4759a77.nq.gz
    ├── 2ff3f9df117ddafbc0a2ba015c040a3d5dcef896.nq.gz
    ├── 300f4e1546c4fc4a11778d1b098c5dfccd77975a.nq.gz
    ├── 302f82d99247fd0b248680f4d76d731d0724790e.nq.gz
    ├── 303ad187f915ce4ff585cff69e1788e1f450afba.nq.gz
    ├── 3047987c2c4f85498a44114e9f8b481751f68144.nq.gz
    ├── 3158955192b1b9240b70ba713ac8b4c1cec858dc.nq.gz
    ├── 317fda0b420ef6302f3168341775b3cb263e6404.nq.gz
    ├── 31b2d85a6546fdc06ec0a28fc6b77420f37f1063.nq.gz
    ├── 31c1b416482e5e59c0b1a76454f6d2b0e512800f.nq.gz
    ├── 32023a7804403a77c0dbb8d1f66b58560f3fc6b1.nq.gz
    ├── 32dfd96567b30946fff10069ec1b3b21aeb2be66.nq.gz
    ├── 331557d2dde47c18c1e5cdef5bc816fdd47ac37c.nq.gz
    ├── 33ee4360db13fa90eec8fd9c0e40b7d93387f8ff.nq.gz
    ├── 33f1039ef87a25ab91aeb56c98b4cc0d00a80765.nq.gz
    ├── 343a4748a68a8db9e91bd833adcdee9c3fbdf989.nq.gz
    ├── 345735c4728b3efeddfdff17236930889658b10f.nq.gz
    ├── 34712e78bd87a7e23a9cf8bbe25ccafd09fc2c6b.nq.gz
    ├── 3488d0ea80219dccfd8d493bf04d8bb9993be815.nq.gz
    ├── 34968a7ae3be17532f915f0fd40562845e3b485c.nq.gz
    ├── 34b4591596c228957df0fefd0a991e80773bc5de.nq.gz
    ├── 3509f7eb03a1f732089d711a22bbd7b7b135c335.nq.gz
    ├── 3525242fe99ced867155360215555c4a19fda853.nq.gz
    ├── 35386d4f4680583b3d2d465a565e6b39990e4b5a.nq.gz
    ├── 35edf0457da3cfafe555e7ce665d715ac603a55b.nq.gz
    ├── 36a78f1a0521c5c54bab031ac55d0fd6298ff5f9.nq.gz
    ├── 36ce043915f2e4331d9990354a1a5199bf72bdcb.nq.gz
    ├── 372c39c16fd7c3bfdee2c74b78cb177e7a184ab0.nq.gz
    ├── 3742ae591e334fc27597491c65e845ebe3778c7a.nq.gz
    ├── 37a0414fcad441397c61862b7330be598cc7f266.nq.gz
    ├── 37e22148dbea926d65d538839981758a7b48a38e.nq.gz
    ├── 387b1d1444f7935edc869cb7d7a646b6354bff76.nq.gz
    ├── 387bfc465d94ca8bcb63090c3fe2d31395827c87.nq.gz
    ├── 388d229bab6a979a8d77408b14e9660c6c6fc9b1.nq.gz
    ├── 38abc02fb4fc144b08cff73ca23e77e2fcba81a0.nq.gz
    ├── 38d36758f393af496ed9fc2eb9896fef11caf8c9.nq.gz
    ├── 394b4cf5e52e3af4f3e0d3cc1b8373cb92143502.nq.gz
    ├── 395229b52081ca3afa3e442ff1739ffeee394b3f.nq.gz
    ├── 39fc5f8e63d9ef3c7821be5ed0549fc6beb5e1a1.nq.gz
    ├── 3b8f3d910a00d852445eba2986b60b1c6db6acbb.nq.gz
    ├── 3c16682fad33eaff5f635424506c7bd801b54df8.nq.gz
    ├── 3c6372bb738851c0b34d856407eb5e7e40ed05ec.nq.gz
    ├── 3c8bff1d3c0c4975ff44b253ef4ee915f58efede.nq.gz
    ├── 3c92c674254257e93cff7e02775959dc4e6b1f64.nq.gz
    ├── 3cd7e79a44043ca95c8fb46282c96900dbc9ef1b.nq.gz
    ├── 3cfa07b764dfd5532142a4b188dd1144a7291023.nq.gz
    ├── 3ddf61d15f51718f8fdb45e7aaf4c531864972b8.nq.gz
    ├── 3e47e577689dbd76b5653c466ad75ba32c8ca686.nq.gz
    ├── 3ea2e26dcb902f7fb435df5097b0639554200eda.nq.gz
    ├── 3ee2e63ccf58decd6a70c28e138be7dd7e7b423f.nq.gz
    ├── 3f9c4763018c4a70a415d5649a2dc6f238ba5c83.nq.gz
    ├── 3fe64e28961ac4da201e59c7e80e4159209e803e.nq.gz
    ├── 403b955c79d5d7f224994608ea4b47156563f178.nq.gz
    ├── 404472754fed692acdb2b0a2f6104f90b4ebed8d.nq.gz
    └── 41a0f6a954011110dbf61dd77e429b7a5ca41030.nq.gz

8 directories, 200 files
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

[open-telemetry/opentelemetry-python](https://github.com/open-telemetry/opentelemetry-python)

---
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
