# Repolex Knowledge Graph of NousResearch/funcchain

RDF knowledge graph data for [NousResearch/funcchain](https://github.com/NousResearch/funcchain), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/funcchain
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4ba7c6b9cd8961b916ff875a950015f89bff82a3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4ba7c6b9cd8961b916ff875a950015f89bff82a3
│           └── chunk-001.nq.gz
├── blob
│   ├── 006ae0983b4c3356d9c76f4f63329146db091e68.nq.gz
│   ├── 026f9e1378c885f14a3c362223c036ecb8c97d26.nq.gz
│   ├── 03eadc76f23eb18a35fbf2206893e8d009bf1abe.nq.gz
│   ├── 059c4f6fc6038d6baf2ff79d4322b11c536fbcef.nq.gz
│   ├── 0bc31d4a8168f23b9035c00c08467eba56ced400.nq.gz
│   ├── 0fe57e01fa024891a63385e384622d473a0d3698.nq.gz
│   ├── 1296f9eaa92b281b9a1b768041f292bf01421f73.nq.gz
│   ├── 135887e8f104f28f87bc60ac160988f2e44853f1.nq.gz
│   ├── 15d61cb8ace1e89d6218fa9892acd8b656c6d94e.nq.gz
│   ├── 18c1cf047553c2afa7e2e6c66ed114d19b4528e5.nq.gz
│   ├── 19c0f00f8943b0bdf835bef7358f2de252968299.nq.gz
│   ├── 1acf2dcb1ece0a7cd70fa72215d7fff391b9b530.nq.gz
│   ├── 1bfe69a5c6eac3265581a0704de122158325524d.nq.gz
│   ├── 1c2cf12b71cb1cb65631654d55a5851175b6102c.nq.gz
│   ├── 1c981022f37a56d928bfb9ce6375cabb499d71c9.nq.gz
│   ├── 1cf054639bf8154d719a8f369fc5d4f3c99fc3a9.nq.gz
│   ├── 1e810730ae51bcbf32035aedc401a6c7b60f8ef5.nq.gz
│   ├── 246f0970725b5a19b7fed8b99a560cdc85131814.nq.gz
│   ├── 24da4dea3aac3280d64b7d4dbff397bd0b009480.nq.gz
│   ├── 250fb25fc398edcf156cc8a14b7540c04b6cbcf0.nq.gz
│   ├── 299b7a336d6313969e6abc59d7726f621546d400.nq.gz
│   ├── 2b819eb023e004b35b881a46d9058134470efc31.nq.gz
│   ├── 2ca11eb6822d5bc2583718912a0518077ea5d38d.nq.gz
│   ├── 309f93ae00c5c1eb3ee1530f0bec2b52a0793f92.nq.gz
│   ├── 31552f536054e3eaafb9f62b7e14dcdd3d566a49.nq.gz
│   ├── 3174deef15ee541898778dfe7a12f1ce773099b2.nq.gz
│   ├── 31792e70ac2aef39fe212c26336673940de5a75d.nq.gz
│   ├── 32e1eb8193cc6623df14de70d25cc02e918e7381.nq.gz
│   ├── 365326f226d6b7a2a8be70b9b3d34250955746d9.nq.gz
│   ├── 37827babef1850dc64dfd29b6327b9c70d587d97.nq.gz
│   ├── 38f55ea22ccbd944afb08905d464fc3f15defee6.nq.gz
│   ├── 3c527390ea221d2a1ea65715b9a098280a278b49.nq.gz
│   ├── 3cd30bf8f4c5c4df2b3914a2279da5503fc17a4f.nq.gz
│   ├── 4631039974814a3856da641f6184b4dfa0433c03.nq.gz
│   ├── 46dcb48a3529ab2aaccf0cb7dd838f8f67dba31c.nq.gz
│   ├── 494b0f5350e59c0191c42b2119048b1e6c5290e3.nq.gz
│   ├── 4cb2131a85f4eb9fe63aa852c6adfbf05dd8ee3c.nq.gz
│   ├── 4cd6132c1dc70833d0489fee64a544d483dbee2e.nq.gz
│   ├── 50f81fbb997e88fc4682714fd889185443bdcadb.nq.gz
│   ├── 53bd2d1d73654ecc423d0dc176cd12bb77802c5f.nq.gz
│   ├── 54096e573b136dea2583efc410ae54ac03bb20af.nq.gz
│   ├── 5742fc2d387266e487445859cfed57610b5d58b6.nq.gz
│   ├── 5818f5d38a1dc89e24f83431be81c463b2de141b.nq.gz
│   ├── 5948e5e59770f3725b0dc407b32b705551451969.nq.gz
│   ├── 5958f32587120c882a850b9c0fe09a55a4097e7c.nq.gz
│   ├── 5af3576a383ffbf703ac1a4ce360ae1e166ef606.nq.gz
│   ├── 5bdc421d6ade953d6053a865ca25610362e56aaa.nq.gz
│   ├── 5c66c320ba6db5e2232b79bcd33e62234c2a26d1.nq.gz
│   ├── 5d2c0b04fad33427376fb34a1c99707883ec6204.nq.gz
│   ├── 5fca63baa4dcd085f9785c085867a8e46d7c4f31.nq.gz
│   ├── 65051440562690548fb05fbc9aae94e712257f99.nq.gz
│   ├── 68f0375cd3cf17314a8659b5714e91cbea023e3e.nq.gz
│   ├── 693ee65bd210f5f44d1ad49891246a32c29dca75.nq.gz
│   ├── 6c45f28d70385f0f09364176ed2e7d6db206f507.nq.gz
│   ├── 6c5435396a398147eac218a1d62fa5d0d5aea501.nq.gz
│   ├── 6e8fd94be109a074c05b704180655b33872f47b3.nq.gz
│   ├── 6eb35f7ebe8ee584e27fc38ca1647b5bbd47df63.nq.gz
│   ├── 6f06e58d9c3f45d7675f6818e29c302af0de0590.nq.gz
│   ├── 6f5f2c3a52f3993ad1349d3aa1ba680719b4275b.nq.gz
│   ├── 76328c8080c65574c9f73e24932e3964a7c90d2b.nq.gz
│   ├── 77763789743f98d077409f7bca4fa4ca4dbb3df3.nq.gz
│   ├── 77871e1379a2f9afb4c0382747ad94d92970a56b.nq.gz
│   ├── 790fb1807af8f75efada84c6f328f503ed2bedf7.nq.gz
│   ├── 7c2124d1c9be35bbf06039a44296c8e5d1d15920.nq.gz
│   ├── 7e55aa6ad4893c1ab58853b17ed582020f28878b.nq.gz
│   ├── 7ec78e181ccfc6bee598f48aa119718eb09d6446.nq.gz
│   ├── 8070e9a29d636720bd6c88163715a3b98f957d86.nq.gz
│   ├── 8340b5527c4d36942db0842926bfb93dce85974b.nq.gz
│   ├── 83b5d8384e26cc55e1160a0d64b75892749d555d.nq.gz
│   ├── 848903be4d3c02f402832a5d9ae27b7a59cc223f.nq.gz
│   ├── 84c87f37f0afc45ce60a582083f78fed2f553ecb.nq.gz
│   ├── 862ad25e0eeb3392102acb97e78fdbe9d451ced1.nq.gz
│   ├── 879cf336aa47bcb199b0d2bbb2dce5dfca02640a.nq.gz
│   ├── 8dc6afc39af47646936b0bb4745775ffe9bc1aff.nq.gz
│   ├── 924b1e2f72e35580816b8c45cd4db13da0b0c906.nq.gz
│   ├── 92d77e734488a3037079aa7b5a4d398cbff87cdc.nq.gz
│   ├── 95536000bbac8d3f16c6babfa895c20dd730971f.nq.gz
│   ├── 95f1f4a25cf0bb21b42a2c6d1846e802d75b0f11.nq.gz
│   ├── 97a30cdab02d25e9fe5cefa6cecafceef4d5c8a7.nq.gz
│   ├── 98337185a64f7e0b8cf641febaba9a483785ed6b.nq.gz
│   ├── 9e6176c8c877c4331d139cd1e2d5738717da22af.nq.gz
│   ├── a0168b5231c08e13aefe935d6bdadd40394f640b.nq.gz
│   ├── a1d24169b1b388b1b3038961409a1d3d990f2353.nq.gz
│   ├── a205df40d659d434f5c2387acd47d2996d9308a7.nq.gz
│   ├── a35b5d52fbd415e4bf5f5de20875c0c77caceff1.nq.gz
│   ├── a4467036877ba686899f8120661825855fde89a5.nq.gz
│   ├── a82fbc7cc43ff7ef584befb9b5bb5acb02c19be2.nq.gz
│   ├── a9d6661715f587e197e73ddab48fabf77855869d.nq.gz
│   ├── aa09320c5566ea8a6c88af2ae108e5bfce14f65f.nq.gz
│   ├── ac13a07a43cb373e2225be897a0eef9353d115a2.nq.gz
│   ├── b059829e00be72ce2f022463ad1a11f4d8441dab.nq.gz
│   ├── b2e76095afa03373a0bc909047ded07284143f0a.nq.gz
│   ├── b3611dd9d6eb7439e0a0dfc58f86300207352b11.nq.gz
│   ├── b46037dbb1737141223b797c941839ef48404b1a.nq.gz
│   ├── b7395217b95332e7bb8e57a2375996578406fe1a.nq.gz
│   ├── b90caa7e4b81553db4098ae6798e2b6709a8ec0a.nq.gz
│   ├── b9969f9a38653231c44cc3e5168ce27f5e488f83.nq.gz
│   ├── ba927381239f898a29566be388a66f31a806cd7b.nq.gz
│   ├── bc3b39dcd301e538f534c1336aea3ec443334012.nq.gz
│   ├── bd59dd46c07ec3cf5de66dee98bfd1faf4180584.nq.gz
│   ├── bdaa4dd4bb0070c7a28beb43c3fe5cabcd8d9101.nq.gz
│   ├── bf7f5c45ee28a94e4ffeb8775a7b7aac9374b257.nq.gz
│   ├── c07911c811db08cbd8c787dd374d2f6512d0df4d.nq.gz
│   ├── c10254d27828786a8c4cfc9319bed9d23fa05b41.nq.gz
│   ├── c24a23d8b0631c8725023ed1df90061ec479164b.nq.gz
│   ├── c2dac4fc824029e6a62a88056e04541bd87f7ef8.nq.gz
│   ├── c64f26403c1e6534832ec0de551e68f1f5b6251a.nq.gz
│   ├── c7d372db4be3c570f69c1cd2df16d750a7fc9f94.nq.gz
│   ├── ca67c011772da5c480263e56d1b957688fa912bf.nq.gz
│   ├── cb5f38c7dac2c0732cde1987938f4d43ef5775a2.nq.gz
│   ├── cbff13832d3dce47e2f27755f38ac00444517af4.nq.gz
│   ├── cc49d715510a505f7dd7152b56aea5073c40dec6.nq.gz
│   ├── cc84c536d9936e711dd4dae7af1cff569fd4444d.nq.gz
│   ├── cd96a0c93b9a70b888e5570a2b5dc04477eb1395.nq.gz
│   ├── ce79a89039cf6fa6b3eb0f071cf0b9aa42349a63.nq.gz
│   ├── cf2881d37c6cde3e287517d22ae6f02d0d8dbc0e.nq.gz
│   ├── d168e8e605d8f30c6135de0222ed4aa4915e78ae.nq.gz
│   ├── d1817ad8bc8fd26b40725d54d712113a97e47f55.nq.gz
│   ├── d4af6a7629dfe3b8cf22d9896bbbdd4bee58196f.nq.gz
│   ├── d5e383053b00ac544c433576f7d24e637225b48b.nq.gz
│   ├── d6c3b9f18402102d5de813fee39f29c333c7705c.nq.gz
│   ├── d6e51826206dd4b5ecab1be819058223c1ca8a72.nq.gz
│   ├── d8234f1d54ea327432797b6a6d91d809d57d4485.nq.gz
│   ├── dc32632f2f116b40829b2622bca245a719ef9178.nq.gz
│   ├── e326d92eee194cd22bfe8646741d330c2e08f9be.nq.gz
│   ├── e53da3c487a849257e50a1414cdb223ba730ec81.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e978ce3ceb123dc8aa487b2083f4a8397b463c35.nq.gz
│   ├── ebd1b1dc3b56222bd1e2f9cf0eb00dedfcb53dc7.nq.gz
│   ├── efbabed65c59fa586d57939eb0b50d614725e99c.nq.gz
│   ├── f19829a3df1b555cd3df91221eed19bad22f9d7d.nq.gz
│   ├── f4ebd82e0730dd72c85bff969286cec3f0d460b9.nq.gz
│   ├── f9c21a488b45a4fffe4910900f7eb81e43eb401c.nq.gz
│   ├── faa785284e1c1f280c4c25a4c1ab99e239876034.nq.gz
│   ├── fbbe9e47d4c9722b4fb994b3174caf6ed193f4e9.nq.gz
│   ├── fd38a7ba4ed6c1b7d3f149997ed45ffd85580a49.nq.gz
│   ├── feb8b3a6c9e932a43f9a45d98ecfb75847ee69da.nq.gz
│   ├── ff62c423853cd950e4e6fbe3e7d1bfef0bf2d52b.nq.gz
│   └── ff95c3697c582eab78b1bfbacc9c5fe277f32684.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4ba7c6b9cd8961b916ff875a950015f89bff82a3.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 145 files
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

[NousResearch/funcchain](https://github.com/NousResearch/funcchain)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
