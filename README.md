# Repolex Knowledge Graph of jazzband/djangorestframework-simplejwt

RDF knowledge graph data for [jazzband/djangorestframework-simplejwt](https://github.com/jazzband/djangorestframework-simplejwt), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/djangorestframework-simplejwt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a7cb077ea0809f78cc6a99cb6825ab7594eae627
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a7cb077ea0809f78cc6a99cb6825ab7594eae627
│           └── chunk-001.nq.gz
├── blob
│   ├── 01bef769a9412c6c5ff859a83985b2b9a7ceec6a.nq.gz
│   ├── 02f39c5ce08d587809b8b4f752d81abf77a04746.nq.gz
│   ├── 03bada52ce8bd45edb33460c1b3f70e90a74bf1d.nq.gz
│   ├── 069fdb143baee2af62dcbbbd3930f450b75f5d7c.nq.gz
│   ├── 0869c9e9f8cdf3ef0912d7af8366536cdd18bef2.nq.gz
│   ├── 0b98e9992b7286a0cf44488a1b9b5626e18f92df.nq.gz
│   ├── 0c54b08d37c3a2740ed4e63f44edc8d67ae953f2.nq.gz
│   ├── 0d5f317f2b71fc74f40db9fdc54051b813b7c8e0.nq.gz
│   ├── 0dc8aa18f668d52517058c44320a1289141098bc.nq.gz
│   ├── 0f67f81b0ff4dd049bd534135fcac9d950624113.nq.gz
│   ├── 10f9f1e2a4031daa22a3cbeb743628855d3dafd0.nq.gz
│   ├── 145b393f9f05e9e272f9c96298fd43d1fda8fff3.nq.gz
│   ├── 14bd13df96380bfb5b8a1fcc41155cacb9049623.nq.gz
│   ├── 1501b7de95b533047905fcffa69711eee2aff983.nq.gz
│   ├── 1708e9dd890ba0a8008ee2b95afe8d319deb4a79.nq.gz
│   ├── 190a44127281f41ab83b8c1835522a93ffaf10ee.nq.gz
│   ├── 1b753499a62580fbc7a2d462b624c69481332787.nq.gz
│   ├── 1eaf1ccab351d8da6d8408469fd8327b30cbdb98.nq.gz
│   ├── 2012289c917615f9068c6be9cc7fbe35277b0cd6.nq.gz
│   ├── 2017a54164bbdf7b57edc9c52c005628d83a7f65.nq.gz
│   ├── 21b32c2a72373d00b768c3304fe2819879b811c1.nq.gz
│   ├── 2637df2336f667a100bf924a12564e3f8b2ac10f.nq.gz
│   ├── 26c20b3f3b76eb8d2cbd322f0e23559b6913439d.nq.gz
│   ├── 2b140ed9f2e0033d82648a42aae7bbd7d594d7f2.nq.gz
│   ├── 2e2be82a97ab33c1b333a3efd79ff1a31a38ae2a.nq.gz
│   ├── 2febd7b9a6f1006ce364f4a73de530d5ccb52315.nq.gz
│   ├── 30aeed53fee92181860b8269435010226bece81a.nq.gz
│   ├── 30e9ee38d4ae240dd4eba003fed48d734132abe4.nq.gz
│   ├── 35a814812a4a9e5d303891ad717426496c8908ff.nq.gz
│   ├── 374342e2447de537b9606e6494b86904de5783c5.nq.gz
│   ├── 3b3451154fe4cff6dfebc25cd6730fe58d8e19bd.nq.gz
│   ├── 3f8babd27d321db238da9a96407af49ab88f94a4.nq.gz
│   ├── 498ec14ac4d5520dbd87f7f7066cca7ca79719f4.nq.gz
│   ├── 4a56a2ee990db904a6ea04913b0d3ff7cdb2596d.nq.gz
│   ├── 4a63b233b29ad579409948d31832d5bc0b97b34b.nq.gz
│   ├── 4bf2a52bf7022ebb627b129949ed58fcd9138f79.nq.gz
│   ├── 4c599a3944edd308684382cc8cb498856f060cee.nq.gz
│   ├── 4ef3f80adc5fa743ecb4081934524411560a20d5.nq.gz
│   ├── 4f17f358356f4199303b6eb33f06a8390677afed.nq.gz
│   ├── 5120d5aaad2aae5d47feadcf5ef2ed05061c36ca.nq.gz
│   ├── 5165dd9126e08f013856757d7bdfe0d36bb76677.nq.gz
│   ├── 5233808b17759905604395f14e111753047669b0.nq.gz
│   ├── 5248ff08c168247bc638cc1717d74ccf5d020cde.nq.gz
│   ├── 52eae959f78ccc7004831554dbf831d8b071fd2a.nq.gz
│   ├── 565593ff07a09e51bd0f50231392be08170d4f8c.nq.gz
│   ├── 569964c5d32c815c635dc2dda7386d77ade834ea.nq.gz
│   ├── 59af197e6948d08ad82ab3709f5b8045407dd21d.nq.gz
│   ├── 5b65a7ba05986199e87914431f53d6fe17e3079c.nq.gz
│   ├── 5c75a354dc1c100459f1402076e23b3178887f86.nq.gz
│   ├── 5fa602fd1f7c3e0c2264d5068f0a6fc07a77931d.nq.gz
│   ├── 61e629b50643e2df59a9c5d347400c3bf2582397.nq.gz
│   ├── 660da686ddf8ef8fa1fd6b5a5c336958d4a2d2f6.nq.gz
│   ├── 6b6ff273908d6f87b665df60e1e742fb39fb0785.nq.gz
│   ├── 7194706391cac51154c48e91ca5c599cf815e631.nq.gz
│   ├── 72837a95337fff6884fafb68264562c942399138.nq.gz
│   ├── 733f5e97bfff233cb7325e06c89aa7ecd410712b.nq.gz
│   ├── 747841a059160953942a95936ae6dfb53d807c95.nq.gz
│   ├── 79c7575b43ad3467d8c8c2aa50078e38a10a8b9c.nq.gz
│   ├── 79e1387c1f509738548a14f9fe67f7fb98b78f1a.nq.gz
│   ├── 7a71a1014f159ec419d28f3e701b1cbc1fe4b899.nq.gz
│   ├── 7aa333f744c630fdb4c7a1ac1cd3a87bc2b726f9.nq.gz
│   ├── 7ae89c3aa0b3f848d689921d202a8794a971375b.nq.gz
│   ├── 803232a04c46f44157ee3177176d8d8bb809f5d5.nq.gz
│   ├── 80681b04eefda4f7d5eaec8621464a153567b738.nq.gz
│   ├── 83b7a02e52e7edf2d5de3eaa9b0131269671f6bd.nq.gz
│   ├── 843783c61724de61419f250e75339c08c3ca171d.nq.gz
│   ├── 85e8da7f9a82ba36bc80ce12beb1e0045f3f37ed.nq.gz
│   ├── 863091c2451b31e81a4d2fea7f64b71edc01bd9a.nq.gz
│   ├── 88baa7d93855866ed06991ba8e57a7179b5c4689.nq.gz
│   ├── 8dc5caa0426b9cd8ae7bc9d91eab8900e1fd3fce.nq.gz
│   ├── 8f8f25c220840275d5f84142a0cd6c8194c7b16c.nq.gz
│   ├── 91d5e06452832107d0eb9d8a35d3c1394003bf99.nq.gz
│   ├── 9212c7cf419c11b87bde1d8314ca4753d31266e5.nq.gz
│   ├── 931452c2e8339e56b8e28db23a9a0336b4e43a74.nq.gz
│   ├── 94d8558bb35e75a6f52f7432c05b570a33e18ec6.nq.gz
│   ├── 978b8d922882e4fa8f2510fb90fe7e42ff90f45f.nq.gz
│   ├── 99395607864a2dfa80fa0eb133fe442201c5c554.nq.gz
│   ├── 9a773572989ec1fa5eb2c6a15b36a87d6ef0962b.nq.gz
│   ├── 9ac52a642957a15392ba6edcf19deebf658fbf34.nq.gz
│   ├── 9e4c2c4cb0b4810cbe1d3eb78c307b33e3473c41.nq.gz
│   ├── a018e228b91fc4e0e2e025b9a63f5cad074834f5.nq.gz
│   ├── a268a422c9cbf805ce1c7f0712ee7d6c5410dc35.nq.gz
│   ├── a3cc991a6b90911616d0b5dbf3bc1ee632601ff4.nq.gz
│   ├── a48219332328aa2ad5cab9fc219fe67f0495f584.nq.gz
│   ├── a5c125a2d8052dd5efdc29a7a186989910c3de9b.nq.gz
│   ├── a64a03105165b8c2725b8ed06573ba8b11dec309.nq.gz
│   ├── a7dea8ecaa93750df4c3f2693673b7d10cd4400b.nq.gz
│   ├── ad693386bf8701f5774880b912931643ebd7d7b7.nq.gz
│   ├── b001cf5d3b74a3af2e87d2c643a573eb9f254eb8.nq.gz
│   ├── b6d595df9f921fd66c9922dd2cd39468fe659786.nq.gz
│   ├── b8e5e83033a59552094f879ed096218e04978e1f.nq.gz
│   ├── bab553d50c0fff5fd265ed6c06e0ae1d324af46a.nq.gz
│   ├── be94970be48c70ff318f27ff1542babed8737d79.nq.gz
│   ├── bea42c762daca1133742a6d3125ea57d3e201f8b.nq.gz
│   ├── beee3d55227c8d6dc13957de3593dfcb7b857a7a.nq.gz
│   ├── bf5d6bfca97bbe4b21b76fee4d90df5b5f2e0071.nq.gz
│   ├── c02604ba10b8d857f44c170cea9020e6f73462d7.nq.gz
│   ├── c0e5fa104d70fbc3098aeb7ce75b805947334620.nq.gz
│   ├── c1de9f6bfdd3bd94bd0d20cf65da41d945378674.nq.gz
│   ├── c97f7c224eff6437b525fc08e3f9bbcda85ecb9f.nq.gz
│   ├── ca0741422c67503b65133e1ac6dd2ca91688d132.nq.gz
│   ├── cca09ecbe8ce287d7026e305fd7c0398cc8d9d6a.nq.gz
│   ├── cd102e0c286d361252d79e275ef5a3e318aa0293.nq.gz
│   ├── ce573f2042cfba2cab94e14f27c9edd600e4720e.nq.gz
│   ├── d2b06d87a75e56bc9029e71f464d845dc6092ca0.nq.gz
│   ├── d38b0435abd54d0dd8167b05b2903747b753a4b6.nq.gz
│   ├── d6526e5d484f2c9fb981d767c58b82db6113d552.nq.gz
│   ├── d87cddd1107d20cbbe80c221d8da0991d01ab1ca.nq.gz
│   ├── da76a4076e38057546af91cdae62525829adb471.nq.gz
│   ├── dc8edcac2abc6e14200e3bc0e7126f3eebe58880.nq.gz
│   ├── dcaf2a1e18a57fdc6091e1d431902df14de8b014.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e2c26df5c2db43a4ea3ed83a38e3d00adbb75906.nq.gz
│   ├── e5c7700ad359515bccdcce8c732e442a68726d6a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e76a81308b4f256cb359009765497b43ccf0d632.nq.gz
│   ├── e7d0c23f302ba18b8b7e3001d8ae434425461f0e.nq.gz
│   ├── e8309849ce012e6317c36a9f0198442fadce8dfd.nq.gz
│   ├── e99a0f7d208b093208f77e672bdc556fc3c368a6.nq.gz
│   ├── ea281e3c69b708b0301ed023ad7d126538538a43.nq.gz
│   ├── ed8645e54146db0efd3334864fd333bc50551ad4.nq.gz
│   ├── ee0e81409c59d4e26de5b02f7bca0888703cdc8f.nq.gz
│   ├── ee85c195dc40b1a3751d91e6a9ee410d52e12dc3.nq.gz
│   ├── efa121584091aacf7d9f19b843b8dd7ee5d2a019.nq.gz
│   ├── f0346b34ca638b1a9e3b5284edc89bd48212ffdc.nq.gz
│   ├── f2d621322ddb223c7d3cb7b3dd7a3570be3a3e82.nq.gz
│   ├── f49662b05b278c5e93307d4c1509f418b8fd9ecf.nq.gz
│   ├── f5ba7e9ff2f983e499e2bce184c56dfb80d5c15e.nq.gz
│   ├── f68b4bf84775472f0a497d2908b5d4c6315cdfbb.nq.gz
│   ├── fbf54629eabcf79fd3b1254606aef69364126b83.nq.gz
│   ├── fc3af324a4ec2b5fc548aa6d22de7eb54bfda44a.nq.gz
│   ├── fe70a52dd733a9dcceccf706f918b25bf2a5e13d.nq.gz
│   └── ffa60576908fd99344b19a8aec180524efc00cd2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a7cb077ea0809f78cc6a99cb6825ab7594eae627.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 141 files
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

[jazzband/djangorestframework-simplejwt](https://github.com/jazzband/djangorestframework-simplejwt)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
