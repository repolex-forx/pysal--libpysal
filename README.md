# Repolex Knowledge Graph of pysal/libpysal

RDF knowledge graph data for [pysal/libpysal](https://github.com/pysal/libpysal), parsed by [repolex](https://repolex.ai).

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
rlex download pysal/libpysal
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c74c2fdc216453320e714eb890f7c197149df1c1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c74c2fdc216453320e714eb890f7c197149df1c1
│           └── chunk-001.nq.gz
└── blob
    ├── 0042de91113f3fdeed4bab8b6b3bd5b109b8390b.nq.gz
    ├── 00f1c8cb557bad6002c6c9e454ea7cddc359b51b.nq.gz
    ├── 017fc38d099e7a1b58d703879c39b68d7a50c59e.nq.gz
    ├── 02c86516df735f587b72c1f55974b551e9926816.nq.gz
    ├── 03ea879bb0548ec37f36ecc1395458ebda6a385f.nq.gz
    ├── 0508084e16915ca94c8fc07b1629c7852c392ed3.nq.gz
    ├── 05f94d9ed9f1d737f2c10f1a42898592c73730b1.nq.gz
    ├── 067c72b7186a22d8a3ffdd4fbea56c34d6822238.nq.gz
    ├── 074e3cb827aa004a93613bf122f30d0916e1f702.nq.gz
    ├── 075a9840746241e193814b4789dfb6703ba6056d.nq.gz
    ├── 08f03817ca4b87b4fbf9164589dac1770d0d8510.nq.gz
    ├── 0a15d19215d36eaea9c5cfcf81d22cb047d23c2b.nq.gz
    ├── 0b330fdc543903f9e8cc325d93f02b795ac97f01.nq.gz
    ├── 0b53938833351d341132a70680f7305174b09c73.nq.gz
    ├── 0b860c1c84ee3d639b3cde89f7961c8d03ea17d7.nq.gz
    ├── 0c9b08ba41da07d47ba66989062c2519fb33467b.nq.gz
    ├── 0dcbaf03ee6e5bc146d67c152aefcfdbb2571aa5.nq.gz
    ├── 0e1665088db6399cd949373c6e66e7ebcf229cf4.nq.gz
    ├── 0e7317a331cd6825294f35f1fbc6824e551204dd.nq.gz
    ├── 1063e70f5771c02c6193f6ed8695849895ef0e94.nq.gz
    ├── 1259b393459352bec095e24844c79c77a0c5bdaa.nq.gz
    ├── 1343b39bd062e4e156b2fdeed25ade7ce6633b3c.nq.gz
    ├── 13b7f5b7565b436a151fc68b805c93197039c8a1.nq.gz
    ├── 13d1037db8b8ae5544984c6e4fa85bbfcf830d32.nq.gz
    ├── 13e756325b07110755331a0c707f9d7f4f26da99.nq.gz
    ├── 15bdea3f9311f872d5be61b9cd196171541c403a.nq.gz
    ├── 1627244c0ac5a979693194a2d11a3c32f2307793.nq.gz
    ├── 166bf46c0e54279eb3c5231b9e7d17de1618fd28.nq.gz
    ├── 18122427a2881c5d91affed408f686a5173739e3.nq.gz
    ├── 182f57397a9b70c56c7a1c6b118d9a8c734be4eb.nq.gz
    ├── 18f12e603823c0b58416ab3b3bb01ff30308b5bc.nq.gz
    ├── 19d0499d30b648ee21597c77672a2647d6f4d25e.nq.gz
    ├── 1b0f748750de465153a8ff38fab1ff6dcc0aceda.nq.gz
    ├── 1b2478cf0aba3a88ac1d7f8d7b393251a1fc61ae.nq.gz
    ├── 1b36d320780bfd6c773f3337725d401a83ba31be.nq.gz
    ├── 1bb03c0105ff75f9125354d4d36f5510bbc682c8.nq.gz
    ├── 1c8c631a5f7bc5909f9cbfdba0dac74f8a79582b.nq.gz
    ├── 1c9cd5c05a1ea96d0b4676432aee82de17260c99.nq.gz
    ├── 1cdb84786a367715e8bdc25f27cd5187fb6deedf.nq.gz
    ├── 1d032ddfa75abc04a2285b88ba63936c319fe1ba.nq.gz
    ├── 1d6c80394bb0dcaf117b544d39537e032083e12e.nq.gz
    ├── 1dc4917efc46eb5b9add2c2f56688a2e6d4bc0da.nq.gz
    ├── 1e433b70d48f7ad453d78307699746d131781098.nq.gz
    ├── 1efb869a8e136c4502d571d94f58b6f7b13960e1.nq.gz
    ├── 1f5b51b9e18600daff41614aab6a8e1c29c21a37.nq.gz
    ├── 1f77dc6184ddcdc011474160b697a79320c03f1b.nq.gz
    ├── 1f97a7876e43b27a063dd09233e978f7ec438310.nq.gz
    ├── 1fbf0aac430ab32d5be0d22abab3a8047c6ca259.nq.gz
    ├── 2013bfce674faffed4d330951a781d00bf4dd9cf.nq.gz
    ├── 227e7d423c35e548c75e7b8c3d09722dda0daa0d.nq.gz
    ├── 2352fc6e8e555824560793a1bb6cdd923839f1c5.nq.gz
    ├── 23b1e7d86fd49c04cb891729f6c8f6f030120fc6.nq.gz
    ├── 23cbfa1b954abc25a79ecf70bd9e715ea66a4232.nq.gz
    ├── 2417238e6d60057134bc5df8e8cad40b80347d0b.nq.gz
    ├── 24cc94ab412e5521e841434aa33605e81a1577d5.nq.gz
    ├── 24df0657b75abaa18a2538a77f8c3e9318e124c3.nq.gz
    ├── 25286d2b9d28ac15aca1268aebc44ce2e8c512f9.nq.gz
    ├── 2595b6b03deaff1c83c941147a2599a31c935e50.nq.gz
    ├── 269c99bbe73161b80c0e4030ac4e189c42e8e41a.nq.gz
    ├── 277149b229865fe8c8dddde08c145d74e703d738.nq.gz
    ├── 29b40e135377f1c04385f369220235894dbb78e0.nq.gz
    ├── 2a824536afa899c88b590272b54ad080072ac701.nq.gz
    ├── 2b0194ae36b23530f9ec56bc7777f7e4da64daeb.nq.gz
    ├── 2b03c104e17803e6b641c7a1d05323d909756be3.nq.gz
    ├── 2b18c3058125287294330d833e3d23d580f043d4.nq.gz
    ├── 2b72dcf7f7d5e7156d4d5108355b8cb0bfaf835c.nq.gz
    ├── 2bbc4f2e02a576abf3d7876bf106ad7d6a0e6b67.nq.gz
    ├── 2c6851e1c9b9c37435d788f36b0a12aade5aac84.nq.gz
    ├── 2e2cfec1c43c6132afe7499469bc1338a3a9ac46.nq.gz
    ├── 2f3f1c774f8256f4fd70a3cb3b14399e6e7722d6.nq.gz
    ├── 304bd330e30e0769c0542dfffaf98f69c4b62f00.nq.gz
    ├── 30889235ef4462e400554922ff0feed352a57d69.nq.gz
    ├── 324b3bbd2350a88ff3b21a8f57ddd7633e216175.nq.gz
    ├── 341f9e26cb7d0b1c20da192b91b5a13ccdb6f8fc.nq.gz
    ├── 3483d58225acfce5857e2afadddc352fdb571cf6.nq.gz
    ├── 34cef0a871d0dc6bd71275577d3519dcf0bd12b7.nq.gz
    ├── 34ee93785e79dc6d523f2b37ba7c7e2ac7117d06.nq.gz
    ├── 3517c1924fc0c38e04fac4b1c26a3349e190f37f.nq.gz
    ├── 357f61c900d3791b82f872240aa90af6fd46a620.nq.gz
    ├── 35d3010d451c434fa5751e3ca3e0434e279b0b60.nq.gz
    ├── 361193c39cce61e0201e52542f502cfaf09cd20b.nq.gz
    ├── 3739ae0b66fe180dbd0690c59c6e45a9d390405b.nq.gz
    ├── 37ea34062a25ced997a81bbe6d7a9722e7d2de8c.nq.gz
    ├── 3856a35872e269e8c1e464bd36535aaddbd852c2.nq.gz
    ├── 390a16565a3a9cb113a4dd2ddf024a7d92b1b73a.nq.gz
    ├── 3a307710b8c9cd3c0cf588d773122da5da1f8dec.nq.gz
    ├── 3a4b6cef70781468457e9e17b62d468f6ae17632.nq.gz
    ├── 3ad133c048f2189041151425a73485649e6c32c0.nq.gz
    ├── 3ad50c2738fb804144d1daa0e8a1bde04de3314d.nq.gz
    ├── 3b81c28aa752d612062b0f4503a7608359c6bd50.nq.gz
    ├── 3c4b88c6d666d76851357f1e7692a1a184744273.nq.gz
    ├── 3cdc6a1de4bb173850081b58020661012cd49e6b.nq.gz
    ├── 3ce44ab3dc3a0cc42fcae21e76383b3af518c431.nq.gz
    ├── 3e556bc7dbdc9a4e0d590733d02c722bd0655d6f.nq.gz
    ├── 3ee3f2c926f722836cb91f3b84dfe844801705a5.nq.gz
    ├── 3f2ec3fcd9f1f98ad3b10b64e2455f6a761b3942.nq.gz
    ├── 40d3c947785ba7aae4266d97c605f610196339df.nq.gz
    ├── 412d2638fbedff0a229b0c76d04d633a25cdecd4.nq.gz
    ├── 419729878319d18438f9322a75ff35455ffd1c1d.nq.gz
    ├── 42108ba42cce8c52ee5d9fd6e46fb725cfa9f1bd.nq.gz
    ├── 42ee589105464d71e50e0cd1ed34907e89ff07b2.nq.gz
    ├── 4317122f358219a6b72233b0e7a71f65aaec923b.nq.gz
    ├── 43bb70257d4d9905c997a758fd0cb6fc5c73633c.nq.gz
    ├── 4473fa26e05389a254de687336a57c3f158d70c3.nq.gz
    ├── 44fa9b5f11f8ad0eb92c415989439d0b359f0e7e.nq.gz
    ├── 459563f55523db3090ede6b00875a2077d7963f6.nq.gz
    ├── 45aedb033e5e9ae4103c511c97a76277701b95da.nq.gz
    ├── 45d123471324c385cb5c49c3d2cab07da1b825b5.nq.gz
    ├── 4646933c4b11e13a720f078001f78f4b6c87751b.nq.gz
    ├── 469d6aa590750890deaf5a3ebc10e7e87b7a3963.nq.gz
    ├── 473348450fd82781a7629447f605d72e36d567b9.nq.gz
    ├── 47ad24339bbb3d01dae82604d39f3fbcc4e3e259.nq.gz
    ├── 47af23fbadf44f789923fd50b49a4946aaf18f4b.nq.gz
    ├── 47e462562439d2331409e04ea04b9cbf05b7abb0.nq.gz
    ├── 47e5314c6b038e28d0aa29e813f72a8da028509d.nq.gz
    ├── 48b89d582a4c52e8b3f6b657c1d72fe7060dfe2a.nq.gz
    ├── 4923f436613be63aaf28949ea5cb05b2a98fb36a.nq.gz
    ├── 4a658ccaf1e2eeb8883202dcde4cb9bd46b955c2.nq.gz
    ├── 4a7fea53b13ab686724f0c7dfb5c0d8e9808db21.nq.gz
    ├── 4ab10fc4af61f01755a7815b487e76254afc5ee0.nq.gz
    ├── 4b5ef4ec670c1d422b70415d6408d1527f3e1bb8.nq.gz
    ├── 4bf9e5c48318440195d910c8848426c8ac6f1e75.nq.gz
    ├── 4bfed5f8f1fb774e7a32b9eed2bb403622421ca9.nq.gz
    ├── 4d1bed77629c3d8e1f1978d79ee21c4768f0d245.nq.gz
    ├── 4d6fc1d3b051a661eed7e4313fab83c3529faf21.nq.gz
    ├── 4da49a4424b1208b14aa09e07f2ee19740437d03.nq.gz
    ├── 4dc3bd5c3b0c4253f0a5896da76f4c24dd337f3c.nq.gz
    ├── 4e1344a774a19a7ed18d46c8bf35e61c47f52558.nq.gz
    ├── 4f4e82f1d6e2ed5e9e7ef4a6acfc1011150e8bd6.nq.gz
    ├── 4fc5234220190fe434e2a8c3e52c53bd6dc99a07.nq.gz
    ├── 506f731ca704b83a0d79a19e5d4f1ba83e14108b.nq.gz
    ├── 50c62e3771986d209fbdaed03c0e96fb5884729c.nq.gz
    ├── 5210c9f934c991835a3d5a4eb9d7e190660cad57.nq.gz
    ├── 523c2c806047d28addf338963c60b71599581776.nq.gz
    ├── 52cfeb43d8c4cec652b552b78fd3b5d90014feaf.nq.gz
    ├── 54761655a125a732cf86a865b9fd21ee6c930955.nq.gz
    ├── 56f35b43c8738be3faa1eeaabda28063ac918c36.nq.gz
    ├── 5748d53dcbb25ddcf7f5d45b14d64e0481c15306.nq.gz
    ├── 577420fe8f33f3e7416aa185a95e150131154b83.nq.gz
    ├── 57a5965347abdb13a91ec3d24ad1904ff5707ea2.nq.gz
    ├── 59166a07af7eabf82aabbf6e8e8840f68ab32ee3.nq.gz
    ├── 5931d0465d4b26a49aa3819f934a9301ceb26421.nq.gz
    ├── 593cea3dcf5f006545ddc09cfc18872d3636c0f0.nq.gz
    ├── 59a405a2679a6076f74f44066d6b9f96d9a0bf5f.nq.gz
    ├── 5a73a2a25597b72cb62135a3116839d00f36fee3.nq.gz
    ├── 5ad7991bb564ffc07443de7f4ea6611d7123f83e.nq.gz
    ├── 5aefa5a4895d50c4c7a68cc89272cfaef1977adf.nq.gz
    ├── 5c02927756fbe4715dea09273d4a3b4801a998ce.nq.gz
    ├── 5c20492b0b6a233ba8e10260ab680ea9dfe52660.nq.gz
    ├── 5c6f76df8b8d4714351777d7c661b9b893a67027.nq.gz
    ├── 5ce4c8cf0f90f811d15b67bfd3f216c59bf8ba09.nq.gz
    ├── 5d50281cd1b7b07069a5e21246a91a5aa4f29c13.nq.gz
    ├── 5d72561301b67d3df6e798703e4d9e4d908dc962.nq.gz
    ├── 5d9c3be668ef9da27ff059c6a7c14ab25060d92e.nq.gz
    ├── 5e1e787e55862236aa455e8a3c1713977f379056.nq.gz
    ├── 5e90891d5fa8aa498241da202d6b4041f7a113b9.nq.gz
    ├── 5eac494b8de18de1ddb05edbb4dadd3780272f23.nq.gz
    ├── 5f4233b9739acb422675dedfb935bc2ee1c0d501.nq.gz
    ├── 5fbc831e743348854289f8b0cacd8b553b1262cc.nq.gz
    ├── 5fc350e36d0a334404c4ddd614fe4245b5ba1d92.nq.gz
    ├── 5fdf379e35c5616d5b52ac613dced4375d1a40e2.nq.gz
    ├── 60dea1d612b8fc08eb1e5baf77dfa1df09300f7e.nq.gz
    ├── 622c92c373c3f6811f6af359ab77b3f405f82dcf.nq.gz
    ├── 6255f722d8ab1ecc03dc57351d5ac07377b63b55.nq.gz
    ├── 6256b7ec0cc47936ae1679532656befecc61dfff.nq.gz
    ├── 63577cee5f33354acdbcce6d0617c56f0474874b.nq.gz
    ├── 63aac55ef94e62f2f37c786832ab6e16137bde7a.nq.gz
    ├── 63f3af2d234d949cc2abe542f9c9403813b019f6.nq.gz
    ├── 66792288d37b59ac129526ab54e937708deb571b.nq.gz
    ├── 66be308cee5ab293af33d09a82f2a1286dc0283e.nq.gz
    ├── 670fa430169125586a8a4c35d29507b4b07c5a8f.nq.gz
    ├── 6720256a76bee71684d3c440122800a318da2c58.nq.gz
    ├── 678f0c0fa8114b5d070a7b0e67c0b7beaa589dca.nq.gz
    ├── 68bc36b0ab3a3287279062b57d68eab54f1f4549.nq.gz
    ├── 694982669ff77cc7b47b12b2f4c1b97fcd4e2f1d.nq.gz
    ├── 6a01e9cb458a35b4f1f40956bacb7513abca4749.nq.gz
    ├── 6ab0181436f16cebee0e24913982e25697b6e455.nq.gz
    ├── 6b3625c959a67445138a6bc671b3be32d53a3ac6.nq.gz
    ├── 6ba768eaf688116bb191bae80e712c05d4450fbe.nq.gz
    ├── 6bb511919afcf6b1a59ddd3fc81eba7dce661fde.nq.gz
    ├── 6c051d4af40d956cb14761821d32611b34ca0b37.nq.gz
    ├── 6ce2ee94b98f64dc94acf303442185e1c196409c.nq.gz
    ├── 6d1939d8815ec7e7753b1ac6cb177baeeb4a45af.nq.gz
    ├── 6d6df4cb37d32e5eb748af525f4ed2ee24818bbd.nq.gz
    ├── 6d9f40984ce090d890cd6df26858f4dcaf2fad3f.nq.gz
    ├── 6df2e85473c434af52b1526cc468e75d042fed74.nq.gz
    ├── 6e2730159021d3c282da8e5fbe4928837228e455.nq.gz
    ├── 706d55b0933398997d1d26d03077e28154419fd5.nq.gz
    ├── 7072581cc1e06ec9786d7525464b246d506b4fa8.nq.gz
    ├── 7086b6f232fddc91996a0000efe1499b28b14518.nq.gz
    ├── 70a36d2dbd398a5c78f882372204cb6c324d5150.nq.gz
    ├── 70ab8d1e3532f46b604bc6d250ddadd04fe1aa69.nq.gz
    ├── 70bf0e114b01d802d75cabb366d10291e9f97310.nq.gz
    ├── 712cf8d3df42a0c6aa73bce810bbd0736c39e70b.nq.gz
    ├── 72047acb0cfcc2a81817dfccec6ab998751fc9a6.nq.gz
    ├── 752600d88e1224b66e7eecd68eaecabcdf7a73e7.nq.gz
    ├── 753885d91c1e09e60c00a4da4d5f5ce8fe1a50fa.nq.gz
    └── 7595a0e34fac332c54191075c3b6a5416c4b688c.nq.gz

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

[pysal/libpysal](https://github.com/pysal/libpysal)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
