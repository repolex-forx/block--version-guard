# Repolex Knowledge Graph of block/version-guard

RDF knowledge graph data for [block/version-guard](https://github.com/block/version-guard), parsed by [repolex](https://repolex.ai).

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
rlex download block/version-guard
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6444604ef8536901b3bf2831fe55d27b2e7c2c4b
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 6444604ef8536901b3bf2831fe55d27b2e7c2c4b.nq.gz
│   └── repolex
│       └── 6444604ef8536901b3bf2831fe55d27b2e7c2c4b
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ce0329beb332756cf246465f92c9cd674c537d.nq.gz
│   ├── 015224062a737df3235e441069b0110fb7aa84de.nq.gz
│   ├── 01ad644ffbcd401a8393bfe114d909d094af2a95.nq.gz
│   ├── 04418edbfdb6d12ff374906937ad883e47921645.nq.gz
│   ├── 054760e840f3223f81c3a192f6627edf039de74d.nq.gz
│   ├── 061947cf3ab56a6000c68292ec5fe54c972b0191.nq.gz
│   ├── 08c52f1c821297df428c111a088ffd5bd0abf1b6.nq.gz
│   ├── 0a066e929a55ffe899717cdc46e1f6fa5290ce32.nq.gz
│   ├── 0f6d8b554255343bdfdfa05e6e4dfb8502f34659.nq.gz
│   ├── 106a8b16667575d221ce581aa30fedfad3281054.nq.gz
│   ├── 1131da96298ba1684f42f42bfdd54efde79a09bb.nq.gz
│   ├── 12af9b5ada9e11bd65c824359acf64979e7aa5e5.nq.gz
│   ├── 12de960e80f6d02a8c212be0b3dd3f946d67be9a.nq.gz
│   ├── 1665b349846e176918ee709f19a9fe5f9b8ef52c.nq.gz
│   ├── 18ab0a53c99b12c14dca9202dfd429e840f35f36.nq.gz
│   ├── 196a0e9f33b754b638d411572e5878acf8201a17.nq.gz
│   ├── 1b7dd349f8fcb5cdc4d3b55b3eede3978eb02018.nq.gz
│   ├── 1b890a68ab2e914335a9b54075e276e161303f8e.nq.gz
│   ├── 1bb3327b88539f2b595437d84c7a84cca4d18f43.nq.gz
│   ├── 1bf9080f0e40db8a18bf1a85fc29df0b49a6d701.nq.gz
│   ├── 1e2cef9a439456f2348e0a5a50ccbc42dbcb6146.nq.gz
│   ├── 20f421d58a343122d3ef794b95b78bd039b67c5e.nq.gz
│   ├── 21fd10b96edb1a61f543a18096244b5580fe656f.nq.gz
│   ├── 2409a0ee9a2b01321549cddd78a3c7129ae2d4b3.nq.gz
│   ├── 25f0bc5ed80683a81f46e6bfd1cf8ea0b56c6807.nq.gz
│   ├── 27536034f494f68668f5a9a34006e7fb25630c6c.nq.gz
│   ├── 28c168a1ff5901c57b91b6784038284fb6a287c3.nq.gz
│   ├── 299dbbd1d3be05ecfebb14a12b1b8b07abc22ed3.nq.gz
│   ├── 2c1ffb1ad640816bff34e6ea080f7b89e0c4f2fe.nq.gz
│   ├── 2ea1d71bdd9d7fffde8282188ec5d4dd91f7b2a2.nq.gz
│   ├── 314df82a83a83dda4250a85a93b73e7b222c3b56.nq.gz
│   ├── 3397226555816ce23372ad2642d2f4cc40857810.nq.gz
│   ├── 35eada56d54dfe1990d778e7032c6955e65ab17b.nq.gz
│   ├── 374feab45d8d8ae76ab60b0bb7574d574920f71a.nq.gz
│   ├── 4038e9f97340c6e54d667fa3c87a1bd13cd9222c.nq.gz
│   ├── 44adedc3e31c13a7461a2ce2b0ceb55b810c7fc6.nq.gz
│   ├── 452be41bdbe3c2540067248bf51ddce4622a0716.nq.gz
│   ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
│   ├── 4b46d422b59914865cb32385f01f1f4b119baa92.nq.gz
│   ├── 4bc5fa744d37a11ad5ec635dd7cf8da98931e604.nq.gz
│   ├── 4c0d7c0a7307fb15695e812e91432f316fcffce6.nq.gz
│   ├── 4d5848e07a4e27073c34523a71010f0262983180.nq.gz
│   ├── 54e2102d143772c0e7a948964636505bca3f2382.nq.gz
│   ├── 550e9e27d7ce28ad2eb7f882b2e2c3d380716abe.nq.gz
│   ├── 55f07526401f78fb88fd796e1ebada11dca76db4.nq.gz
│   ├── 59b1bea3c7c0036c3f584bb753378ef8971f22bf.nq.gz
│   ├── 5c84e156b6820ec8c33dd7a1fe368190febaaba9.nq.gz
│   ├── 6282b703d9c4cb9c7ff8f9ed38930606e7db081f.nq.gz
│   ├── 63b35d25abfea8b0120bf7148580e4b1c9ced968.nq.gz
│   ├── 66312041e01a4300bebdfbd305bff6255b12fffb.nq.gz
│   ├── 665a30eda32486991e4400def03b9c417ac936a3.nq.gz
│   ├── 66c08e66f3484782eb0fb54367079b593ceae934.nq.gz
│   ├── 68c64e642a3bc5fd45cb57181f8f2e523b9276cb.nq.gz
│   ├── 6d30eda1492a56828c29ee8ccb10f349552951c1.nq.gz
│   ├── 6dad1452146b34d536fc6d6bc91219f3d0aba538.nq.gz
│   ├── 6f29f857b3273f885f74db0fc018e7790138d079.nq.gz
│   ├── 73de219dbc3d0496840f082fbf12d1882170e116.nq.gz
│   ├── 754e957f6b9bb151dabc2e5cf7fec4865682be5f.nq.gz
│   ├── 76ddd69aa4add7b977c8c6179f0a46b06c0bcd67.nq.gz
│   ├── 7fcf10552162f7a00a1f634c7a8d69dcf9759b59.nq.gz
│   ├── 815206d8d1cf0ce790a543daf1cac061d5b9f4f2.nq.gz
│   ├── 81ec3d6d5ec33fceff0877a6da9b4e1beee99e55.nq.gz
│   ├── 83e11e418fa8f71b8225aafb597306938e33ed48.nq.gz
│   ├── 862ee3c28647e7a58801a75236855c269c1448ae.nq.gz
│   ├── 884b11de9460871c55cb4e4829d53eda07266b98.nq.gz
│   ├── 884d195e4e959662bc54ed6e706a76f3dc9511df.nq.gz
│   ├── 8a71f1d9ad79e73da9c2306e12327b353918b029.nq.gz
│   ├── 8d0c446d6d4691bdd091243c714423c8f351552a.nq.gz
│   ├── 8fdf4de8efa0ae77029a5de8947771de0649fe3f.nq.gz
│   ├── 9140dd5f9cfeb3276b34e95afae61b94b7640e40.nq.gz
│   ├── 91c0c23d29b3a9c1cdd22f3db78a0bfed0de69a4.nq.gz
│   ├── 934f536932ba35676c86b774fc13e574b20c744e.nq.gz
│   ├── 9391766c7305ab0d7297f4ca5823c3b1f35cfce1.nq.gz
│   ├── 9582fc588754f78d9875691a3bd5e674295436b3.nq.gz
│   ├── 9ba706383ede003f542fdd82a30efc93d50b1d26.nq.gz
│   ├── 9db55bbbeb2621fc466bc01fd36692c970307e50.nq.gz
│   ├── a0314f3324db357ce5eb960126c5db71fb5e1c5a.nq.gz
│   ├── a36d7a97b0a3010c3e51c753df665b280386501f.nq.gz
│   ├── a4e5d51eeeff52376a3d447d4d4d0b250107bc53.nq.gz
│   ├── a8bc4f6388f97470b9a141d0fff1381242bb36ae.nq.gz
│   ├── a980978690a89ccab6931d235a4984c08f70ec4b.nq.gz
│   ├── aad048abe971d0ca77a72b668cc9dffcbb308ee4.nq.gz
│   ├── ab00c9390deacb6dfb0637fad24e643559197eb6.nq.gz
│   ├── ad28fab14a495f996a59a79dcc49f326f48b4a50.nq.gz
│   ├── ad6a7b0ed9be957e96fcd3555cafcc28efa0e092.nq.gz
│   ├── ae66429b1be6dc735b82c78a68465976fae5fd3b.nq.gz
│   ├── aefee3c0ee64fc929b620b669f76b673294517c6.nq.gz
│   ├── afadfcfcf3017c7dd44dddf04db1e3d146838f4b.nq.gz
│   ├── b0e6561bbf618927c9da50044ce243ccc3c0c855.nq.gz
│   ├── b1a289fd88347523d2acba8599c9e2ddbd51808b.nq.gz
│   ├── b225c3931fdbdbbb5f0854393e3220995c875077.nq.gz
│   ├── b4faa1ee20810529750afbe366ed96766775faa2.nq.gz
│   ├── b62276468dfe06f84e632246d71068778924f7a1.nq.gz
│   ├── b6fa9e767dea70d00cab3a9139a96496ae17e88b.nq.gz
│   ├── bba7020144c15715ea57bbcb955a184e49bff2f8.nq.gz
│   ├── bc2c93b69b8d94f7222783dc3b909f87947c0b94.nq.gz
│   ├── bde2b6fa0e78d08e75f15f6b06e28d813114073f.nq.gz
│   ├── c3c2e85f6dd683b7f6d6bc4bf7c499d1f13cc414.nq.gz
│   ├── c425b6b2af3ff58a2e7d5d3666be83fd4b0fe513.nq.gz
│   ├── c6d5c1ee54a3cd7d3124a7eb06eb168d0afaca5b.nq.gz
│   ├── c6eafc1c5a93af2ca903d0730a2710469a879453.nq.gz
│   ├── c8bb873d464a3dc8bc6f0b953f0ba1c40615d88d.nq.gz
│   ├── caad662f32c1871214a91c18108aa5cc0092382a.nq.gz
│   ├── cae978d275753ab0c1b43016e835c1e49494503b.nq.gz
│   ├── d0747e0ca4b970b0f909a166212fa0c877b4549f.nq.gz
│   ├── d4c78cf2b6e63f45ceca67c3c59901379e8c6a89.nq.gz
│   ├── d57c2b6d4dd9f9f794f1b70b67ba95dc311bcc1b.nq.gz
│   ├── d673f22d913dc2d26df332959dc839a66d51eaaf.nq.gz
│   ├── d75fd525c0415fcdd4bef73c87c7dcd9a4310f24.nq.gz
│   ├── d9880bf2898957cbc72ec0ac9dbdd97b728dd5de.nq.gz
│   ├── db3b36116fccda3ef76d6ae4867852a0b24c9909.nq.gz
│   ├── db996c9e4c465b50f458041c2a8638c06e120bca.nq.gz
│   ├── dba6935dd89c3ea51f4cfb1e776496d8d2ebd3cc.nq.gz
│   ├── df365d846ded71230aa096f7b3e3e2fb93e2d623.nq.gz
│   ├── e02bd03e8bc821de9c6272ef249aa28ddc8bc7a6.nq.gz
│   ├── e47766610a141e223628b99ba806dd32f7aa4699.nq.gz
│   ├── e4b69fbbc16c7beffa45fff779b4e3e0cf38e863.nq.gz
│   ├── e56542e7d1412d0cf64b5732680c9123068f680a.nq.gz
│   ├── ec4d59194986f63fa31dbee4978d6a7aecc98658.nq.gz
│   ├── ed40b5a34022986aceccfea959236b701fc65789.nq.gz
│   ├── f107cb6ac097ecf2bd8ecce2d26fad69d12ba965.nq.gz
│   ├── f59208a8adf51ed3369f9aac48b7354682e53f21.nq.gz
│   ├── f5cd6288226939fd4e0a4b223f97c6e5cbb1ea58.nq.gz
│   ├── f71af61873b8f791c36ee425d6237aee697fc8a0.nq.gz
│   ├── f78c5cabcb798259f1790e4fb86d0d61e8583726.nq.gz
│   ├── f81267dae93c612db84c98050f9c06c24c0f3721.nq.gz
│   ├── f820a011881d1a15f74613dd7c62822c937aa076.nq.gz
│   ├── f983fe173d205969131fd1196aa2ff76b8f9b4e1.nq.gz
│   ├── fa6e8e81ffffca5607cd7f5c26c4057a830a2091.nq.gz
│   ├── fc0774b259b907e76a599b9c1f7a1df98b97ec7d.nq.gz
│   ├── fda7b9ec3e53a0385be045d399dbaac728f67c8d.nq.gz
│   └── fe8c702ef99a1c983ae956f1d6b1e90c5a4954ac.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 6444604ef8536901b3bf2831fe55d27b2e7c2c4b.nq.gz
├── filetree
│   └── 6444604ef8536901b3bf2831fe55d27b2e7c2c4b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 142 files
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

[block/version-guard](https://github.com/block/version-guard)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
