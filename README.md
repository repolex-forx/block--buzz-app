# Repolex Knowledge Graph of block/buzz-app

RDF knowledge graph data for [block/buzz-app](https://github.com/block/buzz-app), parsed by [repolex](https://repolex.ai).

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
rlex download block/buzz-app
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 3a1eb5601e997811009d01601786df8af9393a7f
│   │   │   ├── chunk-001.nq.gz
│   │   │   └── chunk-002.nq.gz
│   │   └── fefbfd05f60c5fe8623fcbc51dcd066e7be6043a
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── fefbfd05f60c5fe8623fcbc51dcd066e7be6043a.nq.gz
│   └── repolex
│       └── 3a1eb5601e997811009d01601786df8af9393a7f
│           └── chunk-001.nq.gz
└── blob
    ├── 0006a3a9d9ef23cfef6d9182e60d87b7d3f1bf81.nq.gz
    ├── 00942648ac194375cb205aa5876e0c48452dd7aa.nq.gz
    ├── 00dda80a6286d4a86495a743c3f1dc152c151c31.nq.gz
    ├── 011497d2b00c19682b1105dd7c9fb2aee698df81.nq.gz
    ├── 012756accfab8880e921d3c1f3fdb2fa20605971.nq.gz
    ├── 01385f97a7fb35ade1eeaf2684a08acd4c332cfb.nq.gz
    ├── 0219b818ec57e17bd4303050da51ce40addf0211.nq.gz
    ├── 0237536c989cfd8375c11bd27be914471c2e539c.nq.gz
    ├── 025bc324b0e901b25463e4ed19001049c4e070dc.nq.gz
    ├── 02967276cd443aa6aa05a1a1a214259fda3933c0.nq.gz
    ├── 02b5d795e07df41d1ffb76cfc3699bb6d1904342.nq.gz
    ├── 02d09ae99c24fe72b66a8122ff3f616202f89348.nq.gz
    ├── 02f7b3e5ce79bdcef8d998bc5f01ed1e7b11ed67.nq.gz
    ├── 0340209cae0a47978bdfb1d0ba492c389845e813.nq.gz
    ├── 0355eaddbbf89bb86df01530d027a0a5eb31ce70.nq.gz
    ├── 0367d2331a2cbfb3dadb43da08affe106a235c28.nq.gz
    ├── 037c59588083991e49748b3603794f3179e3c9d6.nq.gz
    ├── 03b48ebb568608abc031ab2a8df88a0b8574d3c4.nq.gz
    ├── 03c319249358a1ed6877f47d9af20911820067af.nq.gz
    ├── 03da9d654464b0992c8b17ba20de984982ae75fb.nq.gz
    ├── 03f36bf39f2e9b6afb9b5f322221264dc78ec26a.nq.gz
    ├── 0424937214f45367efde3393383849879e2885b7.nq.gz
    ├── 0438837e63481bebe4004d5f9400df84f22f9b93.nq.gz
    ├── 050e997ae6b29f0d6604aa553678f86e972fbda5.nq.gz
    ├── 0532574674b6038b4279c245d3f7a2e45d0ad48d.nq.gz
    ├── 0586ba71674661fce397d68f4433e31bcf1930b5.nq.gz
    ├── 05988dcadfdc9a17e309222145acbf60261142f7.nq.gz
    ├── 05ab3384ec79ffa247ebfec5ff86e601075ced18.nq.gz
    ├── 070fc7d7d7e2efabd9a68557c8e80d3a450c4440.nq.gz
    ├── 08b829688330ea094ceef387ac41394ac0f4aa26.nq.gz
    ├── 08ddbb1e72b1215f5ba35b60b8ddcf14762b066d.nq.gz
    ├── 091017012c062bbab22499a993edafe9d89ddbba.nq.gz
    ├── 0919aaa176f9ee51de27459073008ef85b4bf688.nq.gz
    ├── 0a0581badda32aae97ab349cf066b8e834cfa5bc.nq.gz
    ├── 0a0c4b73226cd4793aaebb21d82aa073ef8c5af1.nq.gz
    ├── 0aadab592234fdbaf6d38001921b564c0a22aed9.nq.gz
    ├── 0b0c1e35c25ac24b81712d6fcb4e1e34414dc2b8.nq.gz
    ├── 0b554daa5ec15859fa51b82a70f34075806f5752.nq.gz
    ├── 0b9b22d56c50427804b0eeb1e46a284a515f15da.nq.gz
    ├── 0baef1489f46b007c54560fa765791b48f8dda2d.nq.gz
    ├── 0bef090608dd9524c0248f54af87453b6b827cba.nq.gz
    ├── 0c3f74b8580ab85c9625e4283386809f8b0b92e2.nq.gz
    ├── 0c631f62f27cff4c49788c096894dc897cdb9a40.nq.gz
    ├── 0c8b0de75eec2ef3eef29e31600a899898f84c3a.nq.gz
    ├── 0d386f17a30cbe0d77246473e3a8e286f1d17f86.nq.gz
    ├── 0d6b537ae1a4f9a87c2b49bf7c27559426ab03c6.nq.gz
    ├── 0de7786018374204c7cd4960a30ed004c5b66111.nq.gz
    ├── 0e43f257724734689b2314803d06049a4277f4ec.nq.gz
    ├── 0e54617a79753d1d0e0a19c18a2b7d03cbb5d832.nq.gz
    ├── 0ec20d8d5adae0e7c48296b63e067d58494f0bbe.nq.gz
    ├── 0f41004361b5d2fa6f899d8aac5c3fd5d681e772.nq.gz
    ├── 0fa27ea6cd66daf8e0fec60b7200b6937c80c6d0.nq.gz
    ├── 0fc21e7a5b48c42ae8e51b8228fae4e1d56f4bae.nq.gz
    ├── 0ff1a3d4ec2f8c0a0db0326445f31ef867e43bb9.nq.gz
    ├── 0ff65d54136a6778a7a02bd71e5fac96ac93c337.nq.gz
    ├── 103c118f683530c6b743b52f20a55eb0893622bd.nq.gz
    ├── 10838ed6f538524fb3bcfd652e0b2cd89b85247b.nq.gz
    ├── 10c26af979a0c952b1e3f31231b0ee196ca7f000.nq.gz
    ├── 112191e5f986cd63c49f1df356e1800f1316b9ba.nq.gz
    ├── 11222c733f91ae6753241f1083790caa103876a8.nq.gz
    ├── 1149f9d90ac11e46c47ce857d6b40d18a2109376.nq.gz
    ├── 115d859ac5d2512cb957565ceeac29c71739f21f.nq.gz
    ├── 12239455767856622153b42bbaabc3bf60d3df02.nq.gz
    ├── 1228b16ac3b87dd9e573bc5c10fb505c20e0fed1.nq.gz
    ├── 126f230924f1cec28ee4251c90497fe43a07e63b.nq.gz
    ├── 127d1b50aa7eb4820951e03b9194be839baa5431.nq.gz
    ├── 12ebfadaceecc883d7616a0135c1b5803bb78ec4.nq.gz
    ├── 139130c95574761d3116e3e3e7c30651de95e205.nq.gz
    ├── 139231a029ca8eb0961831df1e3e05be2e69b330.nq.gz
    ├── 1392aaf956ddcf2af07be74541d77b000684f869.nq.gz
    ├── 13a00ebe2073de9e6df575dcf7aadb7f46700985.nq.gz
    ├── 13e2160364d698e2b0a4bb3b2287efc83b894298.nq.gz
    ├── 13f85682488aadf71b0e1c720115d6d379420dcb.nq.gz
    ├── 13fcb4d90f4e9b3769e4dd4b83f2a8e1e81fe208.nq.gz
    ├── 1455ccb65dda8716d6c37909d3751c1b0cf2360e.nq.gz
    ├── 14c58aeac57c446d60c39ce4b203b0cfee07ce8e.nq.gz
    ├── 154ddeec5d2c9ac7b2659785d878f290bda17615.nq.gz
    ├── 1572c5c6871a5b9eea3ce07df9ac5c16d4572ca5.nq.gz
    ├── 159ff17c6a1085f496a9ded594dd21db56e14a2b.nq.gz
    ├── 15c17a6b226b5a91111dd02ff74247fa920360a1.nq.gz
    ├── 16a04d2f82701fe4fa877166f04f68804de736d5.nq.gz
    ├── 16d7629b46673324d39aab7ebb43a2e118b52417.nq.gz
    ├── 16deba1ebf9d00acf7b17d36ebea7514bd9c290e.nq.gz
    ├── 16fff68917ea3a07db96726c8db3641205cf4d57.nq.gz
    ├── 170fd626b9f179fa6dc6cc8985d90606a9caf8c7.nq.gz
    ├── 17657a063161c9223c6cd7b67537b9d560df1577.nq.gz
    ├── 17ac3895ef9e6598feb263d7e9ddefabebf2d5eb.nq.gz
    ├── 180e3ff53c84bb05c271a8c404b063dffd65fd73.nq.gz
    ├── 186419a607805735e6f9db48e371ceda08ef1dd0.nq.gz
    ├── 1895728a10c5797dee68e57aa75b36c8539f80c3.nq.gz
    ├── 19621f6e21cf72bd4c1a04928c08ffbd4d48372c.nq.gz
    ├── 199b750381c1f74fa320feb585ba5027f5bfccd0.nq.gz
    ├── 19d053ef171af7e9931a8f734a8d0ce88e13c379.nq.gz
    ├── 19dcfdcd76363d55917ff5ccd7414502d62f2ba6.nq.gz
    ├── 1a123906f5a32230e2d8aa7ea38d4cc40be79301.nq.gz
    ├── 1a218e769f77c0713c3bd69b00f6162491fe5497.nq.gz
    ├── 1a2d1b7b13fc5f9427f09e4a8c8d0ca72ea60da2.nq.gz
    ├── 1a8d30138fecc0ed7128d7086b44bacc044e2057.nq.gz
    ├── 1a8e195e1cf6eb82ba0f2ad0f9cfb74360f9b466.nq.gz
    ├── 1aaf1bc33ae2511f75e1eb0834088635cc5b6400.nq.gz
    ├── 1abf819e4d58257eaca621d2852c3229b58843ee.nq.gz
    ├── 1b128bd36d4b84c875513260e7737a5d9f1a9c0d.nq.gz
    ├── 1b8daea851edbd399242e250a2b0f61fc31f6716.nq.gz
    ├── 1bb25cd3ae6d5a7038e38fe2baaf26d4bd91c932.nq.gz
    ├── 1bc29d5e7ba62bce6dbddc7c4f8286bd7f787c67.nq.gz
    ├── 1bce86ba255db5f27ff9a5c7ccb95ec77328478f.nq.gz
    ├── 1bf7bb52f91068f5c5db1f94d5292622f362f9bf.nq.gz
    ├── 1cf15f9c0082ec271bf3048de97192dc42fb7aa1.nq.gz
    ├── 1d96942bfda7fa2e6c2cf80947642d90e680ceb3.nq.gz
    ├── 1dbfdcfaa8d32bde902c375a9ef62214ac400381.nq.gz
    ├── 1dc3937800763923cf3364c0cc60f602daf6bff2.nq.gz
    ├── 1ea7470714f35ccf4dc356b25fce079c9ca2348e.nq.gz
    ├── 1eaf23b8c0a7a2eb78f7981699eef1abfd840f5f.nq.gz
    ├── 1ed2d50e7dc0c6c2bf19869cf3d5aa4c387d5ee5.nq.gz
    ├── 1ed9fb4d5dce6156901199dd889bac2a74270173.nq.gz
    ├── 1edaa772efafdd0e400e3781e9fec3693b320c79.nq.gz
    ├── 1f2a67e5547a6329f431fe19dccf978aad2f191a.nq.gz
    ├── 1f4c12159374b2af25cf78262ec6d24fc269b95a.nq.gz
    ├── 1f9b1f31c18388b8ab9e3b0eb32f6cf2c0dacd68.nq.gz
    ├── 201f7130ea28be81c4db6f6fe33bc31ab926a9ad.nq.gz
    ├── 2041853d49fbcfbf07cc091cf008debc534d9c96.nq.gz
    ├── 207b21c3db5c153e78dc8413d1300eb9f869f409.nq.gz
    ├── 20afcd200f008c0eab143a3dcc717db30ddc398d.nq.gz
    ├── 20cdc6ec5e0d58acdac6e253185bfd075883a87d.nq.gz
    ├── 20ee8fc03100bb74f08024621ebcd8969ba94c92.nq.gz
    ├── 211db67852abfc1ada51b8e66b93ccc9cc3f5dd9.nq.gz
    ├── 2142f8d61dc505b49f2cd4f7d8cc9043d323f3c5.nq.gz
    ├── 214dbde553f2f4925fa2831f53d5adcd2f27661c.nq.gz
    ├── 218413498720005687353e2807e7dbffe6691e51.nq.gz
    ├── 21b01c3811c0c1bfc3dab4e410f99aad289e856e.nq.gz
    ├── 21dd88b0f9d399c6ec4b36820d7e0182205ce569.nq.gz
    ├── 21e42dbcab6ee9338a223207f393e4fe0472c00e.nq.gz
    ├── 227188222e1d030ee80a1f778f149b58b01b06b8.nq.gz
    ├── 2285e70ff1ff03ec768e476d78524805cdfef51e.nq.gz
    ├── 228f7f02aa8b8d0b6fb6ea3cec8d8b2ee5249772.nq.gz
    ├── 22ac1b6b10074f34bf6b488017f9cd04c229850b.nq.gz
    ├── 232ececb441a2c14521562fb24be20a2f7f3aee4.nq.gz
    ├── 233ba1b3f6ea0bce036f156701f1fdf16ebbee7e.nq.gz
    ├── 23a13285ce57a8af015f6643debc7b6b440d7e2e.nq.gz
    ├── 23dbdd1d4e3259f9e398d3ee7679116a955022a1.nq.gz
    ├── 2460b8fc66136aeb6f00abfc931d013971beb41c.nq.gz
    ├── 246528025ef90cc8a00c540121fe5409b239df17.nq.gz
    ├── 24f0defe2f113f769753fb940b3699f20b58c97a.nq.gz
    ├── 25176d05a7532b325e8d7e0e5277a4248f0b4a0c.nq.gz
    ├── 25d2b069e3e4dee0cd1092c6edf963176fa76fa7.nq.gz
    ├── 25edb43c88c98eeaa8f5e51b9a9b31a4c829938c.nq.gz
    ├── 25f0bc5ed80683a81f46e6bfd1cf8ea0b56c6807.nq.gz
    ├── 2639c10fc166055aa03d7c4113cbf99844372dee.nq.gz
    ├── 266968129652d26d4366622abd926fd0d2240d5d.nq.gz
    ├── 26ad14a5b4788f22761bce1d6c599c007fc9a662.nq.gz
    ├── 26bc0a9fa97a0db3caf8819d67f39f4fd2e3389e.nq.gz
    ├── 2769f0686ecdf08f4685ef26f85899dbfada7008.nq.gz
    ├── 2a9052ce535d87d0d6cf2513f1c84802037eaa9d.nq.gz
    ├── 2b7e944b585b93b606fbae12d137bd11a337a775.nq.gz
    ├── 2be7caa1fe11a18e8c5a4bc27faf846ffe7ed8d4.nq.gz
    ├── 2bf443692ddb6ea7e37e7820ee7d5bcb9d3cd144.nq.gz
    ├── 2c6126301a81debf41dda65ff7480124f584d102.nq.gz
    ├── 2cb3d87ea26d1ca2cb2d6f0c9ec744f6029a5fa4.nq.gz
    ├── 2cca45bbbaf30f9a72b2679821e38ab3a4f9584b.nq.gz
    ├── 2d10b447f1f440b321a28bf25b24971b9e8104f8.nq.gz
    ├── 2d510ed314a267fe20cb0c9ded697c65191cc1d9.nq.gz
    ├── 2d56d03a6cbfd25ac5381077386026fc1051f35c.nq.gz
    ├── 2e822414587797743ba582abafbf60037f0c8cb2.nq.gz
    ├── 2e88758edce7a6e12a2d6a3faed50bd288a4196f.nq.gz
    ├── 2e9a554937f6a7f27646da453b5c3b37050aa7ec.nq.gz
    ├── 2ec4572d5e19d68592335108662318361342726e.nq.gz
    ├── 2effb1eda70604f8cb9b1e6218450e7e0b58a95f.nq.gz
    ├── 2f1e55286e7518e60f6f921cd8962fcf5289902f.nq.gz
    ├── 2f7fc67442a99a71543f3da46268aecba383ed8f.nq.gz
    ├── 3024ed81d614779baf7b5667986d13b30171a3ca.nq.gz
    ├── 3114171ef4cb7d07ae637985ed1422e6d763ab53.nq.gz
    ├── 314742ff5a749af24483a03e911bdab34092dad5.nq.gz
    ├── 31e44fd3c5c03c8628ba431f17a1e6be3bdafea3.nq.gz
    ├── 3247bc4dd5674a906cfae9f16b855ccdaf3a415c.nq.gz
    ├── 325215d219c200998c6bea5bb1c8c025511f3e4b.nq.gz
    ├── 332884b596bb3c8fd29da90dd618cbd23a41ae67.nq.gz
    ├── 334b3ea4e96d2f82eeee57a0d32e47902e6e9175.nq.gz
    ├── 339b2f3dcdffba57461fed0f161ca238c3dc93e5.nq.gz
    ├── 33a97f51cc0fa8b5ae2d0d0e426fcb545a7f86ea.nq.gz
    ├── 33acf897a18c84b3bfacc97f1b4dd6b56194d165.nq.gz
    ├── 33b0955cf06f89b6b97a02ab36ba0be3d8ddc50f.nq.gz
    ├── 345449409e891a49b9ecbfa7f4bf632c4cd5c463.nq.gz
    ├── 347b12d056ce4b26fa9535e80cc6440f8506c2ce.nq.gz
    ├── 35730395c8395994b246ce5f4bbd47359729e4a2.nq.gz
    ├── 358cad4e2529c71d95235ee5ee55210181edafa2.nq.gz
    ├── 359bece0ea17bb46a60305ae950a7438a54d1f5a.nq.gz
    ├── 35ada825e06b9491d2082af0da59195b94a34aa0.nq.gz
    ├── 35ae4d2775a17c1fb8f05ed363bbf91fa1d6445e.nq.gz
    ├── 35c09f6185fdd88d092d766a13b9a706597dbf61.nq.gz
    ├── 35c14e734c28401640af6feba07a3cdfa6a3186e.nq.gz
    ├── 35daacb8b321ebe5e414de524daad305c9bff250.nq.gz
    ├── 35dd5896e431848cbeb95c55896c3e40502c2d1f.nq.gz
    ├── 35fdb5701750dfe9c1eca14c8ee74dea75afbe9a.nq.gz
    ├── 3604a8275f1c2ead2685b9f1d84fab6958ce41df.nq.gz
    └── 360eafbbb98556e6e1f8a82b2cfddbbe9779f211.nq.gz

9 directories, 200 files
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

[block/buzz-app](https://github.com/block/buzz-app)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
