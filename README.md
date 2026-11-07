# Repolex Knowledge Graph of huggingface/diffusers

RDF knowledge graph data for [huggingface/diffusers](https://github.com/huggingface/diffusers), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/diffusers
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 84532a058702c74ae5d1dd6ceb05683fc5d5e768
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── 84532a058702c74ae5d1dd6ceb05683fc5d5e768
│           └── chunk-001.nq.gz
└── blob
    ├── 002ead7eda176add1ce96d199dbdd44956739dac.nq.gz
    ├── 00832171dcde7a902742a77c679ec73b09c4fc70.nq.gz
    ├── 013df7acc7c78bb26823d6bf7b9a85bfb8aa4fd4.nq.gz
    ├── 014298e12927c510de9a665977ed2ef5e5263c42.nq.gz
    ├── 01544aa4b43022225b31df7b879baa37ac8f0b72.nq.gz
    ├── 0202016165220c99c501389a0ed14be28e05faab.nq.gz
    ├── 02e45e1452468ba40c1daad42a987e6c80d6c647.nq.gz
    ├── 0341623d8783ec350a4c36982f7edf23491bf61e.nq.gz
    ├── 0378ffcdf985de3378cc80bbdeb56e24136e86fe.nq.gz
    ├── 046b28223b3d4efd541cbe35d6596b746aecca5f.nq.gz
    ├── 04b4bd6c29c07702dd35eb797d2c8c5ad4c31af4.nq.gz
    ├── 05bf8200f58877a5059a850c147cb04bcced0f68.nq.gz
    ├── 05ce1037b5375934b9ddea6279f0c731127b7b6f.nq.gz
    ├── 0756a5ed71ff97d0b25363643b77404a6785d936.nq.gz
    ├── 08c22a2707fe55770a519db481954881c1cad26e.nq.gz
    ├── 08c30f9b1e0c2ce1f7baab82f5076efabe465a69.nq.gz
    ├── 08d3f4ed10b8513b63313208818fe8956e400937.nq.gz
    ├── 0949d8cd1caf102128380222973fae8d4400243a.nq.gz
    ├── 0a352051121ac1b73d643e76202b7bbf5634beb3.nq.gz
    ├── 0c2058c887fc187060e94a45534129c8efcfda04.nq.gz
    ├── 0c4d3abe60c816b854bf6f3463b2a28520a61695.nq.gz
    ├── 0c8fd842fcbab26dbfe0e4dc8252dc22512e3093.nq.gz
    ├── 0d4bc196afc3719bc7308c117757b35cd5097746.nq.gz
    ├── 0e7aec5364fbcebdd13784fd0d318d8d5d636c43.nq.gz
    ├── 0eced957190ca46c14877827bb410cc7b84ed6ae.nq.gz
    ├── 0f078f9bad0eab3f712708ab8fb65359faea2c64.nq.gz
    ├── 0f3c89e418226bfb22871af5c199a1a21c3c827a.nq.gz
    ├── 0f494e8158b7aaf3f2f24554aa9b9e5f18e9ffcd.nq.gz
    ├── 0fbe1d0e658242b0a7f3c90653df1ddd1a50a99d.nq.gz
    ├── 0fec7b2ffcda8c785ebcc3cd78f9080315948fc9.nq.gz
    ├── 105c198b9975513bcb3a794807260f6d5899e91d.nq.gz
    ├── 10afb1b89ee074311571615f44d918cb1016a33e.nq.gz
    ├── 1185567a5ed6ff7b1c774b1b85f42aa68e8bfb6c.nq.gz
    ├── 118d2c8df7971e79afdb86c997820500acd0fabb.nq.gz
    ├── 11e005b5d2914a71a605f7247d8d482ae278464a.nq.gz
    ├── 123e46e53baef1c714f00ef405fb8188f2cfb17d.nq.gz
    ├── 124baee3614d2275c9e8bc6c76a1ca07fd4fd0e7.nq.gz
    ├── 12985815b604e01456314edad7e729aa1b8e9348.nq.gz
    ├── 1310b20c5c11febf61069a70b7e47982830304d4.nq.gz
    ├── 13c6904682223de2382b2d0d7b38e4a435f97988.nq.gz
    ├── 13f28e3ee8c7c1611c47d11bddce07fcdec425c7.nq.gz
    ├── 141748b084a02dce07114a63df84b2b60e27f04e.nq.gz
    ├── 141850e64f2eff9d704ab172965a25dcdcb5b32f.nq.gz
    ├── 14584c89cdfdb412e61976763bf24938a8d7cbbd.nq.gz
    ├── 15c55579218f3b713c8241c21549cdbfa9f1aa12.nq.gz
    ├── 15c9a8c27f98dd7e1913bd57dfd5e8dae71172b4.nq.gz
    ├── 164baeb0a4d3b69c108d5957ae08a934b04b90c8.nq.gz
    ├── 16bb83bbcf345385975be131a462b15f411c3563.nq.gz
    ├── 17caa7e2a219094342148ad73076851021f1e937.nq.gz
    ├── 184a9bee4b5fd4423e2510de0230b42b6d8b98fb.nq.gz
    ├── 187a3d8a01d71381e26f3d54510f502c7e312eab.nq.gz
    ├── 18e041b35db7d4046b3a98873406b3e03a27a77f.nq.gz
    ├── 18e7335126572c946bcfa7b5050c817f27aa219c.nq.gz
    ├── 19eae9a9ce444a8afa1ebca290acd86c5b89ce69.nq.gz
    ├── 1ad08729e8ebb1eedc793a353d2945395bc4e08e.nq.gz
    ├── 1c414bb1f3c53bc9c2e3538b77f456c0cd2af518.nq.gz
    ├── 1e3a2e225ebf2e2cb4803083fa13e0ddcc8474b2.nq.gz
    ├── 1e8474eabf3fbde483bf093674da0a19b68e53ec.nq.gz
    ├── 1ec565bac00e2782b6ed8496d1ea490abc066132.nq.gz
    ├── 1f501d7eba0765ac4488d1d4dd5f0ec61a0afbcf.nq.gz
    ├── 1f72c6c35069d61c91722baadfd10b52d1996230.nq.gz
    ├── 1ff6e8f7a1b68c01cf5cda7a8548c8af57d36a5f.nq.gz
    ├── 207a95b17d0e807f46de78b38613b257359b85eb.nq.gz
    ├── 20ad17cfdd967ab9b9bd537796397a84177718c7.nq.gz
    ├── 21567ffa9e7a95abd86c573761ca90d1648b8002.nq.gz
    ├── 2194b5a57063aaf27837774f68d2a9a492c0caef.nq.gz
    ├── 21e307d53df49cd62b9ede046e38bb68c07351c6.nq.gz
    ├── 228b479df090961df6e6f20d028d041eeda094de.nq.gz
    ├── 238541173c82c64c739df2f4f5727ab8050c8f38.nq.gz
    ├── 23c13e6a501c93ec3d672b76b0e6d454a70a6a14.nq.gz
    ├── 25e34fe060924629ca6d7a7b2115efb581e489d4.nq.gz
    ├── 25ed70941f825f6011c8e46a6ae09920224eac01.nq.gz
    ├── 26ae2b5d715f0e471207848e43fc0c24c8a7e830.nq.gz
    ├── 26f259512cbd146dbb27419d5df08db109a9499c.nq.gz
    ├── 270e96b3e9a25423768c772e1d551d9b73bbba43.nq.gz
    ├── 2907dc5f26eee784edc0b209d5666b32502a141a.nq.gz
    ├── 299dad58707d7109709679b3968072c953398547.nq.gz
    ├── 29a98c0e9e5791eb7dbc089a97c720b5559ea65d.nq.gz
    ├── 29dd2ba7f9ab4b49f841f71bdf36df884cf05716.nq.gz
    ├── 2aa1114a5b1a154e70d3fb20bb0d4010a02111e8.nq.gz
    ├── 2bb7c855a54a0e7076b9240aa8637ddb07b621b3.nq.gz
    ├── 2c0695ce55953aceaa2c7dfa32a92892d8e59150.nq.gz
    ├── 2d85be33a836f1378c786080cfaf236465c93caf.nq.gz
    ├── 2d985b107eb30a77887a921d17bf123002a74277.nq.gz
    ├── 2dbf3f60ea0f4ef29a51ab4a793dccdb51a038cd.nq.gz
    ├── 2f1718d5b7122c5ef84235ebc23d2f4fc3a75b5e.nq.gz
    ├── 2f4a1d38d960e3a2da436865aa1360a78fa1ec7f.nq.gz
    ├── 2fd7faea1693c2942a27a41f63b046b5e8dd565a.nq.gz
    ├── 2fe0777daf7dd266f59ef2c1aaa321d502dd13fe.nq.gz
    ├── 31105b6a589052d0724b0b2cb7c70bb2f3bbe655.nq.gz
    ├── 31ad27793e34783faabc222adf98691fb396a0d8.nq.gz
    ├── 3280820eab0ce829595060bd78feeddf1555cd86.nq.gz
    ├── 3288bba9477221862b3040e69abc1fb6e4d438e0.nq.gz
    ├── 328e109e1e4c07cb21905f38a895398b03accec0.nq.gz
    ├── 33e1a44dad92ed7eb7661c16bdeb4fbdcdbc0607.nq.gz
    ├── 3487147f704f255e9b8ebaaa5f16843a4afb1f91.nq.gz
    ├── 34bfb8637f68d3e56b95774c711386e507fb1425.nq.gz
    ├── 34c59795de328f2fa2cbe610625d866e4710d4a2.nq.gz
    ├── 350fba3bcf8056bf07d41ebde00857112a87deb5.nq.gz
    ├── 3579c3abd8d1ba1887871e5a14cf42ec8401f0bb.nq.gz
    ├── 35a96e6f67bccfa135f784446560ae29cde6cb91.nq.gz
    ├── 35cb015a6cc7b908f884b9a809837c6fa5ee3f35.nq.gz
    ├── 3664ab652fe6eccf505a68750410be1f5b0ddd87.nq.gz
    ├── 36b350bd825876674e3ed6e4fd7bca0707302f5a.nq.gz
    ├── 3747be705379a937cc2c1d4c45a0a42950ea9719.nq.gz
    ├── 388444fbc65b22908e3986485f4a065b63267d1c.nq.gz
    ├── 38f5af842e1b07a1beaf6c241143e1c7300bcf45.nq.gz
    ├── 393d7a0a6751204989ef8d6e5f18128650ced464.nq.gz
    ├── 3b3db863744b3d63bdb57d3105d6919d46daba5d.nq.gz
    ├── 3cdd6bcdc6e95e6201082a1e1171313f164dc44c.nq.gz
    ├── 3d0d73dcb951ea5b8b91e255d79b893a2a103ed3.nq.gz
    ├── 3d5b8adfbab7cb0805c7dadd825278f557811a32.nq.gz
    ├── 3d7d3500e669f6378b7b0ee79e17f15faa7b5efe.nq.gz
    ├── 3d7f6c691c92c46158d406c91b5ba63eb20a0e05.nq.gz
    ├── 3d8e14dd50e24e2a372ebe9c62ba11757fa6a2c5.nq.gz
    ├── 3d928c0cd1e73d00d8423e4a86bb136c197e478e.nq.gz
    ├── 3df7b162f896778e08596cc3c642922c6c08b370.nq.gz
    ├── 3f8732029b3fb02d76ef47d2fef3481858bb733d.nq.gz
    ├── 41f18a72ec1e02e80676ac1824d84dc769707a65.nq.gz
    ├── 42efabc71763756ac23c53f92014b941e3c67a85.nq.gz
    ├── 4303faa08671fa949790a2e2a19327ead72ce0af.nq.gz
    ├── 43f801d81e2e00ae6563eb4f6aa8d2e614d813bc.nq.gz
    ├── 44ab937d349760e56aa5def539a012487a49456b.nq.gz
    ├── 45fdf4f826ee131447ec224e09dd5656331146fb.nq.gz
    ├── 46002e086a286d7de793dbf390b94e40045b9d99.nq.gz
    ├── 462222f7aeaa21a1e86bca60cf862dc5d1de5a3a.nq.gz
    ├── 46876051778f7b5c019cb36adb0e9b0156c9ba46.nq.gz
    ├── 489125ff6a62eeefb35ed889608cd2cb9def5fed.nq.gz
    ├── 48a24c15f1d4807e39da5e302d0783b8e75a9244.nq.gz
    ├── 49aa848e3e0befecc6a062b726a4e840a608fcf7.nq.gz
    ├── 4a1a539b6b113bb31f53fb9a8e24b60f06d4d5cc.nq.gz
    ├── 4ad0fb72548403e43bc35000791fd77a29ae925f.nq.gz
    ├── 4ae4989bd8bb26c47622ae33c950241c8b49c10c.nq.gz
    ├── 4b6e3010ec67c5dfbc2a41711662f99a65e8fc17.nq.gz
    ├── 4b770d95361c3f5813917aa1512c6e230e2d4f3e.nq.gz
    ├── 4b926b82c4744f89640f8e90e5e590d50c6d299f.nq.gz
    ├── 4c6fe90cb09f10af84bf0399ac907c4c44f47a0e.nq.gz
    ├── 4c8c00ad8aa95949f21d107cf67f822922ff32db.nq.gz
    ├── 4ca22a1aff71e1c3f4de795b2bbd44dfb9fcef46.nq.gz
    ├── 4cb9cedce29c0a8d5a34fef3b561007a87ca0efe.nq.gz
    ├── 4cc3136a21b9a9c7467bd9a33528bf8ec714e3ff.nq.gz
    ├── 4e22e2d4eb8e81d97bbdd88571cad366165e77df.nq.gz
    ├── 4e53730faef6a5bb6434a93edf4c2a8e77e6e6ab.nq.gz
    ├── 4eec632d7853f8fa9afc42c3d0ba4bc1e9efc78f.nq.gz
    ├── 4f075e8a7dfc58a1dd36bcab52474f935e42aec3.nq.gz
    ├── 507f71ad61ef3079869e7d2ae95fddcedb765412.nq.gz
    ├── 50895251ba0b67dc2848b99654cbdd08312833f5.nq.gz
    ├── 50973afb5471f522c959d7f29e9f81e95c9c32e3.nq.gz
    ├── 50a936b43ef4ea9e956a1b4be550f8d137808c09.nq.gz
    ├── 50fd51e283f6d81099ffa7e39d3335d653dce49b.nq.gz
    ├── 52200d9c664d632f25cd5f3d83a00ee7e01b88c2.nq.gz
    ├── 52586e770e33dfd1023e51d2bf1977ec40e4a612.nq.gz
    ├── 52e4635008470550de4d02ce9474bdb321ac96ee.nq.gz
    ├── 52e586624878c9ef8f76936cb208a40bae6048f4.nq.gz
    ├── 531d9d3e4b20c786245dce67ca43e77066fc76ff.nq.gz
    ├── 5347b00c46082c697b5b51b5c856b482eb992f0f.nq.gz
    ├── 548fdd9e1734109bec5bddf10a10f904134350dd.nq.gz
    ├── 54ae68d19fb493686a883af538d60463026535c7.nq.gz
    ├── 54e3a98139086e716d3c85cb7433bf8249d6e31b.nq.gz
    ├── 554fbc150e09527fd2f836c54ce52d148828c849.nq.gz
    ├── 558736176a4f85a5537420beb8135a17d5e41c92.nq.gz
    ├── 55c9feadd2c16c4b2e1e3ff2492dd6cc46fc881e.nq.gz
    ├── 562f629e7c274001d3daba5a7945d6addf9a3ad6.nq.gz
    ├── 5660698405c3ba0e6eb0a67e33adadf16fbce14c.nq.gz
    ├── 56657f37d912c52704af428704e85f69962f8937.nq.gz
    ├── 567e5e3caaa36896b278aa816ffe32638b7b8734.nq.gz
    ├── 569ffe530186ef87f2570c41b589ef0de3390c4a.nq.gz
    ├── 56c68ae8c9d05aac3f5529f8d79da5aaf4bd1ef4.nq.gz
    ├── 572292c14291b4e24a706df8bd557cc8137190a2.nq.gz
    ├── 580e1f37f30a4bfc91878692c9e0004a233aa64e.nq.gz
    ├── 58567f80f55062bb97c91a592adf288685bca455.nq.gz
    ├── 58928a20cc195801790ba3f9ae48ae25755b0453.nq.gz
    ├── 5900d8cfbaca1a2f8fb9da22e4e7ae36a0b9d482.nq.gz
    ├── 5a29c4c94d99e98f16776460dfdefc8b33180006.nq.gz
    ├── 5a461b1911b2e0246215b29fb58b752b7ef87309.nq.gz
    ├── 5afe68c7ebfadb736bcf65a5ea5caa14ff8301ce.nq.gz
    ├── 5b3df0b4f095a3f937f02263e34582d83cb428cf.nq.gz
    ├── 5c2cbcc13ff1139fa49b88cfde739013153e93b7.nq.gz
    ├── 5c47f3293a312944be98e0e52ed349a89c2f2a95.nq.gz
    ├── 5d60dcb62e35a1cadbbf4428e4ecd7f186cb3444.nq.gz
    ├── 5e3668769a219111db68b6e908c023229cff1b91.nq.gz
    ├── 5e7fb08ede5627b386fbef3ef89cfcd63df8559e.nq.gz
    ├── 5ef96fd0fa9c79df3821c7f65c13c3f87f8d636a.nq.gz
    ├── 5f8d3f48c99755239b7c268b0cff38483239bc12.nq.gz
    ├── 5fa6c3c386e7c768d44ec80867fc05ab2f4bfc21.nq.gz
    ├── 5fc475ddc0791cb95950515472fd3b0bcaee6ec3.nq.gz
    ├── 60302b9d44390eecbba3f95628a0ca0bd32641bd.nq.gz
    ├── 606f7b378a79489bbcbaa87db2040bd4196bbd8a.nq.gz
    ├── 6097b612fda4254272a6010ec57fe615cc05e640.nq.gz
    ├── 60ad201219edcc9431cca5916d89fc80534c1034.nq.gz
    ├── 60b5828cb8acd6aa210472faa73896037e5a9736.nq.gz
    ├── 6214ea556fb6245d267c85a3e481c29ec893a229.nq.gz
    ├── 625dbd552136739789ab9311adedd0b9bdf56ebf.nq.gz
    ├── 62ae4537b61bf4cf9607959d659a1a4cc2a27f0b.nq.gz
    ├── 632f6601a6f697b616180075f101346a30cdf225.nq.gz
    ├── 634b4c9cc6eba374581249cf276bf74ab5504d6e.nq.gz
    └── 63b1872f07eb8149c4ba2a020c30e62bbc47d444.nq.gz

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

[huggingface/diffusers](https://github.com/huggingface/diffusers)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
