# Repolex Knowledge Graph of redis-rs/redis-rs

RDF knowledge graph data for [redis-rs/redis-rs](https://github.com/redis-rs/redis-rs), parsed by [repolex](https://repolex.ai).

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
rlex download redis-rs/redis-rs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 4508a2990557b081abe0163fa5d7dbd52481616c
│   │   │   └── chunk-001.nq.gz
│   │   ├── 63dc913f34817f53d33f6653e633ae970c8b62b8
│   │   │   └── chunk-001.nq.gz
│   │   └── df42d67b6c85deeae747b3d000df13a9d656cc8e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 63dc913f34817f53d33f6653e633ae970c8b62b8.nq.gz
│   └── repolex
│       └── 63dc913f34817f53d33f6653e633ae970c8b62b8
│           └── chunk-001.nq.gz
└── blob
    ├── 00fae7858b21ae208332cd13dc4835fd35d128fc.nq.gz
    ├── 0112138708e6e7165b9d3c0b48c36bc288438df6.nq.gz
    ├── 01a9e39745ba674de264b27e63fdf28c7b4695e3.nq.gz
    ├── 0274acea5309fb3cd6caacd5e3bb96af545418fc.nq.gz
    ├── 03df5186ec422abf34cf8520e2a16c69811e1819.nq.gz
    ├── 06308e80ace2ef4893713e3ed2608bca60c49735.nq.gz
    ├── 0646083d67305dc0f6ea1e7d78382b6c7969101a.nq.gz
    ├── 072db95531f0ccdf451677096d532e0b5655c17c.nq.gz
    ├── 073122203568106397b78e4d8435cb6030f1f18b.nq.gz
    ├── 086dfffb5007ac64ebe137542c94eb325ca2cec5.nq.gz
    ├── 08f6b66492869c821197dc896f14006e22cdc754.nq.gz
    ├── 090687598caca440d0415cd166dd1554d572d02c.nq.gz
    ├── 0a0a5b9f436e51b9978ee236726cf4c3ff2e8482.nq.gz
    ├── 0b6b9a18fa068b59a3fd8f737cb9f09de567db68.nq.gz
    ├── 0d564415cb3411031ed7ba38885e0f0fd5f7d333.nq.gz
    ├── 0d864f00f26aed0aa3a413490686ad56f9718cff.nq.gz
    ├── 0d9dd03def98c7e164b14addd1ea14e45eac9ac1.nq.gz
    ├── 0fa7386ef57076ba32d371e0984694e5be71d62f.nq.gz
    ├── 10fe8fcd583e1fa0341be8a3b4aa71b0e5781716.nq.gz
    ├── 120b089f8dcf6f0098668fe766c6ee04a029bc76.nq.gz
    ├── 1243460c33f78c05472bf6edffc9d5d803208d43.nq.gz
    ├── 14f4fd92912569509212b0dd76bfe1ba3f6459c4.nq.gz
    ├── 14f5891acd71a1b35c79c489be4caac0a08f5ac7.nq.gz
    ├── 15d7b6667ca23fad65f68b6a26a63f2d80ac026f.nq.gz
    ├── 1686817da5d49754beb56a79f72209bc33b4b16a.nq.gz
    ├── 1776e1323369f80d210d72cdb9508c0e7bc7c253.nq.gz
    ├── 1966eddd7c2c7b7c1b07ad398e1238f63c900a14.nq.gz
    ├── 19c1153009c4d558e5d3fec2ecae2fecc72361a1.nq.gz
    ├── 1b859a78f600fda18ee45f19f71bf7f0069d0be2.nq.gz
    ├── 1d1e7797d2f8edef2df47a299b40d5167f47c4a7.nq.gz
    ├── 209931a34cd41676fe85c4a093bf46619ac84d9a.nq.gz
    ├── 215053c2df17497fe17d86e09e74fa2d390a7e26.nq.gz
    ├── 21be083de66a067f94f4fd36013f16a3b3de7d3d.nq.gz
    ├── 2238e2fa851f455cb10da2d91d6b077d338340eb.nq.gz
    ├── 2280e7f6f496984638408c66525d19e27bfa9f9d.nq.gz
    ├── 22b1e8da2f557a60db8399dcab560a9ffb4f599e.nq.gz
    ├── 22cc5451350d821611052940d02a28837ecc3f65.nq.gz
    ├── 234601fc6d94ac3025e367c8ceeb7681f2a31aad.nq.gz
    ├── 23a269f9a0db507933c386ac5d0be483838e3a42.nq.gz
    ├── 24babee6ab785e0736d378a78ec4413b4a4af854.nq.gz
    ├── 253d304f96922f11e9a1cfad61073ab3c22c58cf.nq.gz
    ├── 25bead9966afa712daec50a13c1d4fb927e0c8dd.nq.gz
    ├── 277e8bfce59a4567029f4f02e4b8cd0b7987f5ec.nq.gz
    ├── 281bf3d9e56218aa05371feccd594ca90ab6a74d.nq.gz
    ├── 287b726b899122dcb5214a1291e4bd5996283e13.nq.gz
    ├── 296ea39523da2f3ade524a224d879bca781f3037.nq.gz
    ├── 29a8f57ad74a8b91cac4c78d64172786c02f1fdf.nq.gz
    ├── 2a49be8885dd67958761c51f5e5e08083eee9cb3.nq.gz
    ├── 2b217e281b4c3967398f99769ff8827fe493abf1.nq.gz
    ├── 2b3e815a94510438704b407c2427d7391af4fa39.nq.gz
    ├── 2ba7f19995a209e5c1a7ba754e040f5f3a4f3745.nq.gz
    ├── 2c275882aeb7c01b85d4499a974c665ada4a74bf.nq.gz
    ├── 2cdb4ea75ce09c917aecc94fc44f6aed790cc54d.nq.gz
    ├── 2e2e984a7cadf2e3c007fdda25df5ac822f58bbf.nq.gz
    ├── 2ee5f9a29ebbdd0bacdc794d7d057c59c7f37f15.nq.gz
    ├── 31d8ffa645e0ae066c6aec12d6d1cfc5b434698e.nq.gz
    ├── 3313b768b35ea654d3e889e9297335f8e000011e.nq.gz
    ├── 332394e405b2d9a063fff420d66525e9802b9103.nq.gz
    ├── 3365fa8cf8cc514aeeb0be6bdac72a2e142a033e.nq.gz
    ├── 339401568220f7f3a5edf8173beae12e4838f5f9.nq.gz
    ├── 3509cd742056695bef5a91149b92f5cee16018ba.nq.gz
    ├── 35b42b6a37ea6e1eb6521bfd2634f4fbdb112661.nq.gz
    ├── 3676142778c9566e3b7318d475f619643ffd39d8.nq.gz
    ├── 36b32b94664a97e6a05ddc51816459dbda4547aa.nq.gz
    ├── 37955522a279d90be08d50697f2dcef581eb6796.nq.gz
    ├── 381c117ff9a732b2b35291f340afcbac5d9d5feb.nq.gz
    ├── 392bafc8598c031045c6aafc9d6b7ecf734faace.nq.gz
    ├── 39b3ebdbc6254ad057f76b23a3c249222aec6ae4.nq.gz
    ├── 3a1ef822f999688b03bc1f606ff7de7aa2425d6e.nq.gz
    ├── 3d4af69990a907d6c3d08d656305b54fab4325f8.nq.gz
    ├── 3f297324acd3ba6fc8cc36abfd063cd18cea6449.nq.gz
    ├── 3f6069603a0a63c73e483cddd423a33eb4211b11.nq.gz
    ├── 3f83f0cb6a67c6d029eba29d11e173208ce0cd54.nq.gz
    ├── 4016d1bb6914a2e180f68f625f7a2aae90092daa.nq.gz
    ├── 40513c3f0241fa0a8f6a627e51195264d0c5e4b7.nq.gz
    ├── 4062e2a1c1e4fa762653e3f2192b8e85ae726669.nq.gz
    ├── 40b5a1b72e1c5b1c8046ebab77488cb46cf4367b.nq.gz
    ├── 41ed54e61daad18c97fe1054eb2c987cf4b5e8dc.nq.gz
    ├── 422f984f9d5427d8a73740631ed68ac2fbc2b3c6.nq.gz
    ├── 42a2d077bfd781494ee321e83c89e1078b1299ef.nq.gz
    ├── 43c24c25c57ce3fd8e8e71c7de0b1efc1b388d35.nq.gz
    ├── 444030f99fc39edcf7d9c1f6d40e0db1155925b9.nq.gz
    ├── 453fbbd98469d8109cc8556bff958adf25bb6e4f.nq.gz
    ├── 45a845ed5b669fbc6f3b2a0b82116f1815617183.nq.gz
    ├── 4629cdaa3880cc6b9db4f1cc65ebe56cdf888633.nq.gz
    ├── 466225c08c819929234ea4d49d3aec8a2e883dbd.nq.gz
    ├── 46d9b842832eb998c2e464b089854014e0d59b2e.nq.gz
    ├── 47d98cdb5091ef28d6ad31187b74b9fe85280093.nq.gz
    ├── 49094e4262d4e0ed5e6fd7af783b98dd5f9839d9.nq.gz
    ├── 496f4429ce28e21caa09522f7ea064502388a824.nq.gz
    ├── 49d3e51f526cf37b173e1f58e0dad75091a068cb.nq.gz
    ├── 4c12853d98f892e9f73e715478452377b0ac8d64.nq.gz
    ├── 4e2cd72af9aba775032462fa227eb73f455faf4d.nq.gz
    ├── 4eb50606b4b5f10a5db5ae6b411b2ad8eb4b1762.nq.gz
    ├── 4ebb8810e51547147bd401194400dc3b5cb3e6cf.nq.gz
    ├── 4f229c92392961ccbbdecb37b284306879b693df.nq.gz
    ├── 4f6d01cd0f28fae3ed5d3cae60852e2d9d38d62e.nq.gz
    ├── 4ff876902a55bd67740d5146556eedaa99aa513c.nq.gz
    ├── 5035cf0e7d3b8f995c3e77f9ee4b36d703a91b6d.nq.gz
    ├── 50862293f1fe823b7fffafdb17099d00ce90b2d2.nq.gz
    ├── 50ccbb6f5d9dfc682819ebd659e92b9c964b4f73.nq.gz
    ├── 510654ca0a661e006d4f197c40a46895e763f29b.nq.gz
    ├── 51dfd4d22a0f9638d6ff2bbac09fe18c8dd4cc53.nq.gz
    ├── 522295818771e43a89b26588cb780819e386c4e3.nq.gz
    ├── 52697d55010e0a3db2a9cb41dbedc38590082dd0.nq.gz
    ├── 52eff7ac45a14228a943fa65beeaf2323da3d0d7.nq.gz
    ├── 533ac4e5a2d89fa1d47efdcc426d0a4a823e7029.nq.gz
    ├── 5404a5689c43899b67b0ee0c6f67da6f1ec882b6.nq.gz
    ├── 5429e1445549e6096c8d07e8179fb7205fd5511f.nq.gz
    ├── 54741d9d3820a1c7e43ae61c69cb86a0f912d5bc.nq.gz
    ├── 54a00019c80f6d4e6d64b85780a4d91405798e54.nq.gz
    ├── 54faf09c53e7470d0dcb1c91811a977d1b607d21.nq.gz
    ├── 55b254699ae1d8a3e1da8d7a4d8dc6abf49a27bb.nq.gz
    ├── 57ceec038a8b7c9848d66f88f245149db64ed493.nq.gz
    ├── 57f4c39271a263206dcc6c3e4c0e2a23c7a44f2a.nq.gz
    ├── 5ae1619f19e5980e312cf7bd17ffb45b8166da95.nq.gz
    ├── 5ae79a3c8af9ae1ed852bb74f2523ace9e48cf9d.nq.gz
    ├── 5afde55aebf897a5fcc285a0ba101c42a7b66615.nq.gz
    ├── 5b4bb24f56649e42dc66fbd798116adef5e6c02d.nq.gz
    ├── 5ba07301e2e164eb4489278fb522a9fe4f970b49.nq.gz
    ├── 5c6061726e9b7b943e9e3947e44ac64b3aa869e8.nq.gz
    ├── 5e271d96715bf8ed46a4e438af60c853fdb7feea.nq.gz
    ├── 5f1037f348a7e622d20b5f8e34780039dba49e93.nq.gz
    ├── 5f4572acec7eb7af874e44acfb41114f6f417ac5.nq.gz
    ├── 5fb10c02de000708eb459ac94d2e078bbb6f3dd8.nq.gz
    ├── 6041bd5d24e0a0ab63295a9fba9a6b00240453b0.nq.gz
    ├── 60e1cbda19194a514f7b59768f03ef3397f28e58.nq.gz
    ├── 612ee5c440e9fb7d9708ea39b2f57fb87119bdc4.nq.gz
    ├── 61f9fc1151bd2cb2664a3c97f8efa976009d5c13.nq.gz
    ├── 62357a0e3855c7e742f2f4d5ce316bb95dc89392.nq.gz
    ├── 623ada35f71425956a34e0fc71d7d0ac6226e31f.nq.gz
    ├── 62418de2ff0939833e9bffff8f33a18774a7db84.nq.gz
    ├── 62e6d7b519a84ae017232b6c4dc4ea184d92f5da.nq.gz
    ├── 62f6ee501f7ebdc01d47427567cd648e328f1d31.nq.gz
    ├── 63c3fe15ed902e9d6a544d1101adc553ecf45fb0.nq.gz
    ├── 63d0c080c4d9ebbbb11c3003b2b995dc791afcc3.nq.gz
    ├── 662fa045cf60f1e4852caa658f5fa8bdaf3ca4d0.nq.gz
    ├── 6702fa7229a056a6fc07a0fa739fec007762c28e.nq.gz
    ├── 68fa9304079421d1201d93e72afa2157d66e5105.nq.gz
    ├── 69ee7554c452f44ecf89c4028ce504fa47841fc3.nq.gz
    ├── 6b2927ba53b33e166d89ceebfeb37e183267a583.nq.gz
    ├── 6bac9b1608da8a1ba5e7f02280c076b9e0fa8983.nq.gz
    ├── 6bdac7063852cda75157bef6f67d0006e1afce68.nq.gz
    ├── 6bf5f3bb017f345ce068a94755ff8aac47a61d9e.nq.gz
    ├── 6cf8976fb5db275c2757c83e1b25ce0c43fc5130.nq.gz
    ├── 6d2462d3ee6154cad1c32f4391b9ddac45c7b115.nq.gz
    ├── 6dc674edffe9ee2ff129ad580fa17992a07e4edc.nq.gz
    ├── 6e137464927c30b2c60fc8a2b4cfaf90948b847b.nq.gz
    ├── 6f7b632b0b6640a7ebd90e9bdc7ad897625453cb.nq.gz
    ├── 708d5c77c7187af409f2bf8f316dcfa99d5131e2.nq.gz
    ├── 70db6dcad091fe91365d8867104816c455ca9c95.nq.gz
    ├── 718cf03120e92dbeb260a98b22bcc29d404eea7c.nq.gz
    ├── 725f084c48b38017db7cf730084506b7c85a73ff.nq.gz
    ├── 72af1a57d0f571045eef3168a87c90c3d65907a5.nq.gz
    ├── 7317205777257e8b0d8dd8ef6bcaeae042e6fbe7.nq.gz
    ├── 73bbfca03061f57639913613b9236b9027359af3.nq.gz
    ├── 73c579cf40784d9aa70de7575bd77afb9f126a1b.nq.gz
    ├── 73d1f18ef5f5a5e21f373c5d6ad67cad5df1265b.nq.gz
    ├── 7431828c89fbb81d032a015aa597ad2175574157.nq.gz
    ├── 7549fff7f7b0c0c9291b0aba7b63009992d9ab91.nq.gz
    ├── 755d2c18c15f3deb5eaaeaa73c2baf58e8322822.nq.gz
    ├── 78ea637fca3bdcf7a3d59f1851ff3cc15ba58d0c.nq.gz
    ├── 79bd7bb208c09f17432342a317885a3a73bcabb6.nq.gz
    ├── 79cc22dd48530f92ee473e9b1868e76382519f6c.nq.gz
    ├── 79ec5f736982187d305b9a2785d7ef6374d44206.nq.gz
    ├── 79f50d4eaa4c8dd4ae65c1a4a6951a8b5e01dfbf.nq.gz
    ├── 79f53ed34ac9a12dee3796b974ee9a4b7856f0b5.nq.gz
    ├── 7a45d8fc4cfd2236d812c55993395a844a711abb.nq.gz
    ├── 7a49cd4b68aeef63101b0ad16761acfabd92888e.nq.gz
    ├── 7b5b272e59d33ed54b163c7ac35d243a11af30ec.nq.gz
    ├── 7b8b66d89c5cbc3a4a3619efe6752650ba791926.nq.gz
    ├── 7ce83c0f5f3652b0a6c330652aa07c50816e4ccc.nq.gz
    ├── 7dc5b7a0a6dfbfb96c0369da97b89f93ae30dba8.nq.gz
    ├── 7ee90085fe10ca8e5f84b9c99ceab8f85e574744.nq.gz
    ├── 82ab1363cd2455c1e7ff1f4665b34950b4b7d4aa.nq.gz
    ├── 8310b8def5e369fde7ff63ef117d656f06fd96ce.nq.gz
    ├── 83bd1625cbf2958b12618add6f1a819ce78932a7.nq.gz
    ├── 844a48d0d15a1cfa41092a2b8ad13edce32fec94.nq.gz
    ├── 84e08e7cd81f1fb8b9234db60c073fc4ea5cdcf9.nq.gz
    ├── 85ebc54f50a84a28dba6567316a18100bc6378ce.nq.gz
    ├── 8716b482fb1e7896689c4cdb690262ecec435f4d.nq.gz
    ├── 8826f8a0d0b9164e6e73d660409f468f4f081083.nq.gz
    ├── 88b77d3840c56691ee8c131239f65c9e361b88ae.nq.gz
    ├── 8aabda729b40583dd6aa8bdda8d7b915674f155f.nq.gz
    ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
    ├── 8bec9a1d73a214e264c33576a43613a13d8e1d9f.nq.gz
    ├── 8d03547d1d5dd6ceb0f6406b44ccf996d32b6218.nq.gz
    ├── 8dc17dbaaa5bda3406d2c470c00d6e7d792d5772.nq.gz
    ├── 8ed8c1e1f8290366e639be8a6ddea21dafc09e06.nq.gz
    ├── 8faa168c0e5c17c1a26ad724ecb97c09f2c48fdc.nq.gz
    ├── 911df394d73fa38ea01a8bdd939e542cbde7d9b9.nq.gz
    ├── 91791a2f796b23394ee326fe49d40a8ae472f74b.nq.gz
    ├── 9181b4fe60131adc2870c9e7b34469db0f5933e6.nq.gz
    ├── 91c308aa52472c0ba34ce3f55b4356928de6bc7a.nq.gz
    └── 930323b1fc1ae38c2d8f1d0ac201a76cec66d392.nq.gz

10 directories, 200 files
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

[redis-rs/redis-rs](https://github.com/redis-rs/redis-rs)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
