# Repolex Knowledge Graph of sphinx-contrib/sphinx-lint

RDF knowledge graph data for [sphinx-contrib/sphinx-lint](https://github.com/sphinx-contrib/sphinx-lint), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-contrib/sphinx-lint
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a3c2554c7c75f869483d297f7e369e4d027aa33c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a3c2554c7c75f869483d297f7e369e4d027aa33c
│           └── chunk-001.nq.gz
├── blob
│   ├── 0080cd6c99a728fd6a27f62cce6840d6410e4277.nq.gz
│   ├── 01db56faa04757436e8cb3002c711b18425cb97f.nq.gz
│   ├── 06270a736d12b1572d939b2c4940437677dddcf1.nq.gz
│   ├── 07b68981c52db7ecc24cd152ada92041caa90cda.nq.gz
│   ├── 08c85e373cd4a9364a7aa04879b9d426dddcf4d8.nq.gz
│   ├── 0f1270750502575d755bfbbcd44b442b411d702b.nq.gz
│   ├── 11a1bb065e1c55c16c38c6526940674ff0a91398.nq.gz
│   ├── 13b7b607077ffc8d2e36561834a9c3440b264072.nq.gz
│   ├── 149252495f829537f44e802471550ed2a0ee00ec.nq.gz
│   ├── 14cad099e1d5c896178c767e54e6f7033baff541.nq.gz
│   ├── 181d55990d67680a47bca2693908876df9bd36c8.nq.gz
│   ├── 1ae229ed764fb3d7f6aa41f74e3d37e37e809b2f.nq.gz
│   ├── 206ca5745c817ac37cf3405165f3846ef6f097b9.nq.gz
│   ├── 2394a4ad2c1602604908c8d33ffd99f2223957ee.nq.gz
│   ├── 28ac80f66fddb4b2ab5e04619c7cd643cc708ad9.nq.gz
│   ├── 2a72d7361a095ba3dfcdd621a37e601bdaf24ea1.nq.gz
│   ├── 2bb42aa0a9ae6e7400eb2057911b5a1b326b4a91.nq.gz
│   ├── 2be752a76730f6640d6aa4cbea07cecad6e1d8bb.nq.gz
│   ├── 2c080208e33ef292cc8f762e246afd696c873931.nq.gz
│   ├── 308ee6c5b6a75a05091046b699de1d3275f80355.nq.gz
│   ├── 30903a431bc885b985d63296d31adcb427e0c565.nq.gz
│   ├── 340559eadc7d78de1f3a57bf75543591d32402ec.nq.gz
│   ├── 344eb49658a6126fdc7bcfee42d914c9e24383fe.nq.gz
│   ├── 34a7792dd2eae0de383a0410ed3c24310c8b3118.nq.gz
│   ├── 3805f087f614e68f99c62294d2670405628322fa.nq.gz
│   ├── 3e3cfa792f9976d575fbfb823f7f28577601548f.nq.gz
│   ├── 4085393e4e84d603bc35001a014b3ca53beec5ac.nq.gz
│   ├── 41f960da85c87b7a49b00f3b1913c1776ef91529.nq.gz
│   ├── 43b6436f46bf4202b924506aa158e5b451ef6dc5.nq.gz
│   ├── 4635e7116a714a3ec6bc0f5c4e5cb3bf309929b3.nq.gz
│   ├── 478151086f0b4d7bc44eace6012b9aa14b2ace4d.nq.gz
│   ├── 4c7e0502f30e06b9061c796f417ec711182b1d96.nq.gz
│   ├── 4fa189149003637ecc1180685f4f893799f04326.nq.gz
│   ├── 520afc032081a7c222e0a218c5717ff45f161893.nq.gz
│   ├── 5227678497aa68b47f185d269d366c9625431824.nq.gz
│   ├── 526d2f1ce3cc3fcb5e561382f6db7f539b8d4784.nq.gz
│   ├── 52ce21615f7b42ffd2305883ba57edfb25f68dca.nq.gz
│   ├── 55fbb26863944acb5aa42ebebf27d11be7a8bc02.nq.gz
│   ├── 568818cc8ada4e67a82b0df0878000cb1cad8627.nq.gz
│   ├── 5b9151e883333183b7458ef26f1c9a31dd292bff.nq.gz
│   ├── 5e68eaa4b972634e230a9ff9e28e3fd7d3a8b4b7.nq.gz
│   ├── 5e9a634f5ae2c3e0b128e2e6d53d1923949c9b51.nq.gz
│   ├── 5f11685188d3e4441ccffa4b689fa0799a116b8e.nq.gz
│   ├── 5ff2e0fe4836d8d12c63aec144e7689ff4c0df1f.nq.gz
│   ├── 63a8b281f9aa6ee70db6115954c68035c9cc5450.nq.gz
│   ├── 65ae9f32210b99353187b24907dd055ff2e1d379.nq.gz
│   ├── 6cc47509e0ec36f80ef70975db500b97ddd248de.nq.gz
│   ├── 6e8bcf3a14407000caba4658e982e8b4121e8a46.nq.gz
│   ├── 6f35e4dd80381c94de294b178b1655f6db5d9edc.nq.gz
│   ├── 7221ee5d989d8f8e017749c2c833eebbcc87ee63.nq.gz
│   ├── 7263c55a0db491d875b202e753994db40152f74f.nq.gz
│   ├── 726cdedb1f3ec46ea2330075318625f51c09b9ad.nq.gz
│   ├── 7294c760180948152a6221d2f33341c6bb7d0869.nq.gz
│   ├── 781bbb9431796d2e247dfc2364a5dd4f8dde5cf5.nq.gz
│   ├── 7a661ad9ab88d348e2379d10ba8e1b5f6054f915.nq.gz
│   ├── 7c964b0bf40523bc108b5c1cc9c5675b9c3b666d.nq.gz
│   ├── 7d440b91a25e5d2009d17e988a02b15be8767acd.nq.gz
│   ├── 7da26896337ecb721aa2630b1976387f63e51b0a.nq.gz
│   ├── 804c43887a91d43529b195d6862f25f4a9b7698b.nq.gz
│   ├── 832789911022b4ab6f339f2aa1cbf1666361d09e.nq.gz
│   ├── 8c3c55a6cbde83acbb4daf9c9399c1d43afa12d3.nq.gz
│   ├── 8cf2e5189bd382c83c9437bcc40ad09e14504040.nq.gz
│   ├── 8cfb40139e3afe7ad966d171e461feb3838a1f79.nq.gz
│   ├── 902d4d61fda9fa4dfe8c0e455859c2679d2cca9d.nq.gz
│   ├── 91df0747217cb46470a028ad0b7c68dd4abb0693.nq.gz
│   ├── 9c75ad42d5760539a57436e661878218136e611e.nq.gz
│   ├── 9ccb669edb178734a3827601e40a6f48049b8af7.nq.gz
│   ├── 9ecf3e8d8e9435d35c935db04c31b340f26693c9.nq.gz
│   ├── a5082affa5b19f577b04150b2aff04d495e6f721.nq.gz
│   ├── a539ca0925246a05fc1116ca7218b9517facc8bd.nq.gz
│   ├── a6b022974c86d0930986efec53d102a006aae29b.nq.gz
│   ├── a7904ff244d0cc467822fdaa420c0e387fdd32c6.nq.gz
│   ├── a8693bef77fe8ba20ae8bcd77840bc183988d5af.nq.gz
│   ├── a9b2196fd10b753a314836f21c01dde594ce0138.nq.gz
│   ├── ab14c701e30e50aa96249d4bbc2460e014edf71a.nq.gz
│   ├── abb24a69ff885b8fde0925ba3fff977db6db80db.nq.gz
│   ├── ade2fd5ca60d5f55af7c8a49719d61b717b4ba82.nq.gz
│   ├── aed83182cf300d0b86577c14c5e9dcf953e75ff4.nq.gz
│   ├── b13223b694b5748a94347196553af2502df88d29.nq.gz
│   ├── b1b76967744491772e87990636125cb2cf022dc2.nq.gz
│   ├── b362dd827a3acea1ce162265ae3d957534953f49.nq.gz
│   ├── b40dbb298d77212e883e53184a80cecef64b4075.nq.gz
│   ├── b536a212f69b93b2a1f41a87ce6c98f4a7450581.nq.gz
│   ├── b69dc8e68b6a3624e4b433f206c8c8e0d483c668.nq.gz
│   ├── c0c80ddbd5808b1ad028a3b1f9c33d580dd54988.nq.gz
│   ├── c1cebcfcb87be9832c1e4ea989d35eceb4f314da.nq.gz
│   ├── c1d09e7fe66166eafec881ed3ccf052e7ce477c7.nq.gz
│   ├── c3b7dae5daf776eab6e0bf53bc69066b76f0b5c3.nq.gz
│   ├── c48d7063259b43ea3e92bc720c4445572b46f1fd.nq.gz
│   ├── c4c15d9ced024d47aaa86590615171a4ac1f8576.nq.gz
│   ├── c5a6fcb342a7ecd2dea159774581231c07f754cc.nq.gz
│   ├── c6eb3a8c43eb0acca596505f9d0d6560fcd8d5af.nq.gz
│   ├── c7059586ed60195eef4f93787de5c184991e4ca4.nq.gz
│   ├── c7e5e39b4d746f01e2b33f213b0893108036b839.nq.gz
│   ├── ca8c74ba8d424c9d4a62f1b1c34fa18192208b8e.nq.gz
│   ├── cdbdbae6cc28babeb6e62ac2fbef33751f9df606.nq.gz
│   ├── ce29eaab4141f6f215dc246020f41c48d455592b.nq.gz
│   ├── cfdcb512f0effd98988c9797dabcefeadd6cfd8a.nq.gz
│   ├── d002354c6a11afb289b90dcfd57a57719d803a3d.nq.gz
│   ├── d32dbd48bdf2a780e7259aa6c0ad2e7a42a4d62a.nq.gz
│   ├── d47d2aa037fd922311bbd4a2bec614c525c62b00.nq.gz
│   ├── d50c2997771190d8317f9598fad8f266ed6004e6.nq.gz
│   ├── dba7db8d588c2f7903be4e4851856a72c91db587.nq.gz
│   ├── dd85588e91804c81fdd12cbed54df66d7bb14c85.nq.gz
│   ├── e34197d739e5b4dfd3291768163eedc1f2e8b6fd.nq.gz
│   ├── e373c0b75154d52f017530855bdc73052ea5e9f8.nq.gz
│   ├── e3a7bacd7680d136181781e152f12495e55cffd3.nq.gz
│   ├── e5b61d95a2872ea81c5e3ca63567b7d93d95c92d.nq.gz
│   ├── e6d5a04f8c7e472b462affa2421ecc860e7aa364.nq.gz
│   ├── e8c6b3c526165585d74ef80380eeedb209eb68e9.nq.gz
│   ├── eab9d8a19c41c76036a52b3055ea165b5e569d11.nq.gz
│   ├── ec66adcacf86074d213f778aa1f43d314ea5c288.nq.gz
│   ├── ec699dbf992122ceba266c219bb62999e81f96a2.nq.gz
│   ├── edb9c681a0eb21869f3700f60cda41d04e464870.nq.gz
│   ├── ee8ea3e4db5b3909f729603b7431ca5f1e1e8945.nq.gz
│   ├── f5083174ceaada4e443e0d802984b8fc08ee675a.nq.gz
│   ├── fc5b0ae689b5d0153fa252bf1240bbc8845bac3a.nq.gz
│   └── fc5c4116eda58a202a3528ccd0b1403f1e0d64d2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a3c2554c7c75f869483d297f7e369e4d027aa33c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 126 files
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

[sphinx-contrib/sphinx-lint](https://github.com/sphinx-contrib/sphinx-lint)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
