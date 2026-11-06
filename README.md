# Repolex Knowledge Graph of facebookresearch/recipes

RDF knowledge graph data for [facebookresearch/recipes](https://github.com/facebookresearch/recipes), parsed by [repolex](https://repolex.ai).

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
rlex download facebookresearch/recipes
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0e70491af39fd63b1d76aa2acb62f1eb83ae441b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0e70491af39fd63b1d76aa2acb62f1eb83ae441b
│           └── chunk-001.nq.gz
└── blob
    ├── 001bf6e1e865ae3be9a31f43633ac67b07f15f6c.nq.gz
    ├── 00e0a415192baebe1d8aa0bc93e97f94d3a43d70.nq.gz
    ├── 02b9071ee5dd841074a53cfedc280c3ab31bcbf4.nq.gz
    ├── 030ad5e718e412d96d51624b211124f9f351f464.nq.gz
    ├── 03bcc99a2a167445fc4e69d6f5ebbd847138d139.nq.gz
    ├── 03c23fb5d7c5a24ecf31e0d65b476b10c2f35e39.nq.gz
    ├── 0506e511ca810ad47f28439d3abe1073eef5a5ee.nq.gz
    ├── 07b58f4b277a39e723e8a11e3a7fd72199566db0.nq.gz
    ├── 0997ec8d84e6761888cf364dff5fa26d304b444a.nq.gz
    ├── 0af16eb529c8f24cbe1937ca75b8ab26eaef932d.nq.gz
    ├── 0c3c6df6f061370534cf3c86e11da29af459360b.nq.gz
    ├── 0e7f0ddae24d9905a3f2d474c4b5d3426db5f3cc.nq.gz
    ├── 0e888054af5acf71d209512cba69e61cf6478595.nq.gz
    ├── 0ee5614a39f2b7958baee17637241f20c1c60ba2.nq.gz
    ├── 0f756f14d12024194555e713814622b3efafb1a9.nq.gz
    ├── 11e4ed4492359e4a3d042a35df2f20e079d8bacc.nq.gz
    ├── 132ccc3a33555ed9a62e3b0a318f2ff07da7b442.nq.gz
    ├── 1448b3788dab6071fd20ea62e6f55bfc27138069.nq.gz
    ├── 1500f42956a9277c3110a96470872a5f36382c73.nq.gz
    ├── 152b1549247b2d81af784e1558a98695952dd7d0.nq.gz
    ├── 173221d38dce46a73772fdb4374be2ef98a5a1b6.nq.gz
    ├── 19b730957592dba0b3d82a8a6a52a4fd3bf8524d.nq.gz
    ├── 1f5f23fb0c6a42713d46cbb3625748a8dcfb4ae9.nq.gz
    ├── 1f7f2ccd1d74a9491ecc1509d64f20b10830fb34.nq.gz
    ├── 22150152aab6d7203f79363a53fe81a9ae558225.nq.gz
    ├── 22a1ba794a19609073f3006d67066f6158770d07.nq.gz
    ├── 23b23563137b5cd68487f2aaf9b3a5564f9c6379.nq.gz
    ├── 26b807ad259c14cee3ef445b517ba614809a7fac.nq.gz
    ├── 26eee0d264df56c73c66683bd9e0af177f5b310b.nq.gz
    ├── 287ad4541bc76ec825248923142e0e7daa540d93.nq.gz
    ├── 29239b42a39eabccd8771ace7260a2c41eb755d5.nq.gz
    ├── 2992ed60acef3df060b17bfe379d6479afa59569.nq.gz
    ├── 2b0fc97466b5fd1f2618d7532de5876b24f33822.nq.gz
    ├── 2c749b6055046d3c9fe0624c825beff89cd190af.nq.gz
    ├── 2ced87b7d8ce9be555f73d72742dd384a4ffda74.nq.gz
    ├── 2df68eeed3065569d3389abdc01c8e02594c92ae.nq.gz
    ├── 2e3c67ec112b2434373ee37150a45283fa29f1ce.nq.gz
    ├── 2f4b311a00e9ba1bebd10b4c28a2bde212667569.nq.gz
    ├── 30335ffec0e391dbef4c128fcc0d017afcdd634e.nq.gz
    ├── 3375c521a3e0ccf0c359cc35e4744d3a4947b361.nq.gz
    ├── 34e3a3716ef6d4b61e80af259602f227f10b728c.nq.gz
    ├── 3a09ef7ca91a2be6435a07768ddeb2b9f48aad3b.nq.gz
    ├── 3abec45709eb864fe6a7eee0d288feaaced735e9.nq.gz
    ├── 3b0cdcf73f01bf2840760e6731607bc0eeee5bde.nq.gz
    ├── 3b11cdc1c90faa7f5431e502a77683461f002401.nq.gz
    ├── 3b93d6a140d1538df8d1e6aa86ba67071dfb8c45.nq.gz
    ├── 3c7be7105d2a370aa0e388d714678573988ff9b3.nq.gz
    ├── 3caef9e0efb0d22a2f3490413324371a15072043.nq.gz
    ├── 3e1af1b2408408d9cdaa5d8f26976e8a8e9b7986.nq.gz
    ├── 3fcea823615c6a065d7f2c1fa161dad4c936bcab.nq.gz
    ├── 4140b18b822a5d8eec31dfc70d2c4cf7e983b8bb.nq.gz
    ├── 41cd17be7ac37a87695fab9625df9640af677d8c.nq.gz
    ├── 426502ec44eb3faab24374082ec0984b3f8794fe.nq.gz
    ├── 42d5e71383530f864801dcd2269f9dd20d550dda.nq.gz
    ├── 47a251cea28220693f64563542f07f02e5e69226.nq.gz
    ├── 49973900676420a934ca72e12b4612d4aba4fc83.nq.gz
    ├── 4a15c53e22009ced30926068994f44b93cdc5075.nq.gz
    ├── 4b6e759ff0fc26f4ceaedbdb2ef58c44871babb5.nq.gz
    ├── 4bade6cce69fcf2e59246a3e845a0db3f6ef5084.nq.gz
    ├── 4e67ca4593cdaa666161c51597ee08f6ae991be3.nq.gz
    ├── 4f480b2fd0c5dbbfdeab48ab0ab3c1e2d0843274.nq.gz
    ├── 4fabf8c794c1dbbc45dc75f1a6d3f1ddb830d2da.nq.gz
    ├── 500883305f965e57c98ed56fd8934c6fff075a9f.nq.gz
    ├── 5068356d960712f39c17b8da9b553018089269e7.nq.gz
    ├── 51553e12bf63ed8705339911cee19ff27c437e17.nq.gz
    ├── 528a426a3401633c626049a0aca3bf2e9b84d6ed.nq.gz
    ├── 5625c2c7559b511d9e97eb59ab7a03f71283c412.nq.gz
    ├── 58e26f30e99c12c453db0d72b202ed82f96ea459.nq.gz
    ├── 5938b45f0d9930c2fa95bfa6a5bc2ab73fb844a0.nq.gz
    ├── 59e2268360a78e08e94a1751e3a0726b38b01a17.nq.gz
    ├── 5af9ae06c4deaac092e11eea5698313ed0ca00dd.nq.gz
    ├── 5c89df70185fbe453884163e8ddc3fb734c7b542.nq.gz
    ├── 5d2bd0067582e3cf74ee8198587e5164ccac8b6d.nq.gz
    ├── 5ee8a86b0d7f572795fe9c37668bfa8a4222e267.nq.gz
    ├── 602070cc66619dcebc9ae907b8269607e35e58d7.nq.gz
    ├── 606c724ff1ffc62c9ee9ee12c4225d1643b314c5.nq.gz
    ├── 60c85a5c0521b69e060460c97ff7120de5145f9b.nq.gz
    ├── 615adc4ca9744fb4111941bbde298d9c74f7481d.nq.gz
    ├── 69f137f820abd9a08f92a578b9e6e1dd5f93e939.nq.gz
    ├── 6a83fe1be9df453d678bb5acfdb3cb316d40f31f.nq.gz
    ├── 6d5bb497d9dc9f3387c554ce6774d80aa03a7ac2.nq.gz
    ├── 6f297bd73515910a060a2523e2b32f4bef2da1ea.nq.gz
    ├── 6f4a8101c159f4f9322791dd6da0e210868b2bc3.nq.gz
    ├── 71afc3efe25860e8d4733d5287ab8df4153b1d22.nq.gz
    ├── 71bc5d045fe111d7dd1672395ed8e5e468e92de4.nq.gz
    ├── 71d2f75268054fb6387331c67d5fff2db298a6fa.nq.gz
    ├── 72157d5e955f42ca5bf5278c2f6f6bee41afac51.nq.gz
    ├── 735ce6e40dce4679736314c9420a938a701fe6ad.nq.gz
    ├── 746e652633189adc398234826f17c4ac68cdb619.nq.gz
    ├── 76a88f11c5e9d24aada781821c06b8ec900c1856.nq.gz
    ├── 7848d26c64bd19838f3b8247bd6487cd9283b62d.nq.gz
    ├── 7b337314781cfe76cdd9c839fb8c5583fffbb8b9.nq.gz
    ├── 7b406264f775807619405bde166b2161676ac214.nq.gz
    ├── 7dcb3a2d4cc3b48b6283dd46870bfeb78f88aac9.nq.gz
    ├── 7f24b6b37227f781c999ca583182d6604d5d1089.nq.gz
    ├── 80e67e8761cadae50d367f0f54236ce82cfe263b.nq.gz
    ├── 81071b90e40dbb55f1d7e669d328c476e356be67.nq.gz
    ├── 81c0905c7e897c6a444e9f4ec3d056ffe413da64.nq.gz
    ├── 820d0991e87c8e6d6283d1f735e3c67b65fce5e3.nq.gz
    ├── 82a1dea622fe117ec42e06da4b0ba631513f9994.nq.gz
    ├── 844cb8043a543c29f6ffd7e8e2f1abe1b6a051e4.nq.gz
    ├── 866ed8a5d58cf1c2e3ac49263d623f1b32bfdc2b.nq.gz
    ├── 86edde0c635fb204b5637d62af666b1a829b2218.nq.gz
    ├── 8c4dbf8ca5fa566d02a0bb44c99a3f28ae1ecba1.nq.gz
    ├── 8caac107c7d4c65e486add90d8a03e0ab3c9c4e1.nq.gz
    ├── 8cc3615fb34a1fd83809059c3b77e214000c0a99.nq.gz
    ├── 8ce20ef08a40c05851ec1497441b4c38f5397f79.nq.gz
    ├── 8e25da8a87153cf2a57555bb7dce7f1e7ceed707.nq.gz
    ├── 8ea4128fa19a4dfec6e4749da3eecd6f1f6608a5.nq.gz
    ├── 8f4670e9e4b0681b337707e1cb0c1acc41b2e49b.nq.gz
    ├── 940e184086534dbe0376bb447221dc98c4c67a90.nq.gz
    ├── 9536906f73282c1235427fc3baf99ef0f63dbb8d.nq.gz
    ├── 975c9baed0bb8f0c02b3fe33faf19ceea50d19f6.nq.gz
    ├── 983625dce8953fee6eb660300f802a5de2ce0973.nq.gz
    ├── 98718c9f4276d8683558dd36b07df538e22481e3.nq.gz
    ├── 990a0d6084c29ed09733a20f5a0f07cc4df5d95b.nq.gz
    ├── 9c01702d362cd15dfab16a6cba22fae6c8947913.nq.gz
    ├── 9e3e15d6a4d658e1f084eb5993c46e98816d0edb.nq.gz
    ├── 9eb47371f92b7b7e35132baacd8fcc2f85a63dc0.nq.gz
    ├── 9f3c0b3aebcdea29bcd80be5b1f6084fe25e0e5d.nq.gz
    ├── 9f935642f83bb921c88568353cb1b39e8a717b8e.nq.gz
    ├── a30db93e25a3a40b014b391c21839bd491fe2862.nq.gz
    ├── a367903b058ddc8c737478a040bda64611ba522f.nq.gz
    ├── a493789cba09a7744ed02cee819226409896aa15.nq.gz
    ├── a4b13c32e4e89a3c4ec86f4de7801d43b876810e.nq.gz
    ├── a4c5e02149a1cc4738b04266a32a3e312fa5a4cd.nq.gz
    ├── a5ea7ca664c73f59032285ddfb3ba51489a7aa19.nq.gz
    ├── a81c8ee121952cf06bfaf9ff9988edd8cded763c.nq.gz
    ├── aa55ef77fb68a4a3d77875164582b0bdfecbefe6.nq.gz
    ├── aa7d7e48b5a03b1d9cc53f0547d60906cbcb88fd.nq.gz
    ├── ab0dd54a83a9ea963e3fcc39075b9853866571b0.nq.gz
    ├── ad13799aab808b6e987a45f5f2ef1f886c1bdc92.nq.gz
    ├── aec97f1ea63fcab21ee32ef6e29ff3c3a0629659.nq.gz
    ├── afc3b2d74cff2565aa74318dbd2981f99215c170.nq.gz
    ├── b0800970a7b9b85fc205b811fa3077dab480335c.nq.gz
    ├── b1771ba42b69d31c4fc4b7df3bdcee8f877ead6a.nq.gz
    ├── b1b85daf6209b956d631bb243dfe32bb1bf3fc0b.nq.gz
    ├── b20609f673eb157d60398f4c96354150c58e89dc.nq.gz
    ├── b2f4a4bfc58c0d7dc25eda3bd5f9eb1306505a1e.nq.gz
    ├── b44f215526e7d8f8596a59756dd1097196e3dfd7.nq.gz
    ├── b4add4b01009396770a854ca3464fa996e3bf2ff.nq.gz
    ├── b5aa17873afe3cc81bfca0937f229de8e80c1618.nq.gz
    ├── b69b9bce9dedd5bcace3ca974a4dbf1754215a3a.nq.gz
    ├── b6dbbdbec7403bd5112a024f60879ae3c90b7dac.nq.gz
    ├── b7f847912fbba9da63c03675f587b37ab3c83744.nq.gz
    ├── b925d12bd142e1f32f224d9a8ec89fcf4effb53d.nq.gz
    ├── bddca183eae4c3823294fcb0a821a28e779b3cad.nq.gz
    ├── bdeadfd397fd79b73434e9daadd65fe889a5adb0.nq.gz
    ├── bf4c7537882be1dd28cc0c9fdd3e6675e4958cdb.nq.gz
    ├── bf8037aa7c95c73ad1f1942d22be1926c0747330.nq.gz
    ├── bf9ddda394830e71805cda934db6ab7e7e8b4737.nq.gz
    ├── bfc6d5aaeaedecaaff473e76cf874a504e28627f.nq.gz
    ├── c039c2fd64b71b28618d2179f250a74624697ceb.nq.gz
    ├── c18422081dd622ca9e49215a1be644cd5fafa4bb.nq.gz
    ├── c21fdce35f5b90965e4a9c752d735902227e40b5.nq.gz
    ├── c2f140e0c596345f906a9ca2776742bb3a7b799c.nq.gz
    ├── c41bbb7fb55a8965fa14456d9d72f90006972d90.nq.gz
    ├── c4b4250a14f1aaa512f725e664b5925d865c805a.nq.gz
    ├── c6d7811bdfe5a27a70caf109fa8ba817fd2ea61e.nq.gz
    ├── c6dd028ca7731495a5b76e41f0f8ca828d804b1b.nq.gz
    ├── c79ea3ac6ba01a783a8d37bf6d26c395d13a5d84.nq.gz
    ├── c7dfd01f31af2d1ce1612a4fb764aa26d3a35f8a.nq.gz
    ├── c86441a97fcf02321f8dfa28a6fdcdd2b6e19637.nq.gz
    ├── cc30b05990172a4105fd078586cab3e286c17597.nq.gz
    ├── cf6c91f0539a46f8e45f0052536ab1c4f015e7f6.nq.gz
    ├── d059e9329f3f2e3ff8a6b0abd5d92ba451c82027.nq.gz
    ├── d18a7a91d477ddd17daed7ada0950c722621f373.nq.gz
    ├── d1ea58b804c84a380514677452e15bb1990ab803.nq.gz
    ├── d4b17afbbbb151075257c26858380966c0326928.nq.gz
    ├── d64edb8578e401ef13b5d71f9fe7ace6ffc29ea5.nq.gz
    ├── d8af4d8cf565baf066b65a9b0a8d4862bb578ff2.nq.gz
    ├── d9cf8a42050a1be2ad666154ebcb3310187dbeda.nq.gz
    ├── db791617bf10f3d3465ea358ae2dfa3ae6ffad0c.nq.gz
    ├── dd34b1ed320a92dea81e4d215c0a731fc46cc53f.nq.gz
    ├── dfbd1ab773418044a431334b0a7f604b4a6811ac.nq.gz
    ├── dfce855dd421e1d7a73e28e9015f844c930b8921.nq.gz
    ├── e05a7b087578fc74d2136946392f01bc0ec9a4c6.nq.gz
    ├── e19c488c96b5d747fdfd374d399709f4b2835e4d.nq.gz
    ├── e1e9532c5b791c8a88b413ae5f254226921cb498.nq.gz
    ├── e493ea0caff7b76d4264b25ca8f73a81d2fce3c0.nq.gz
    ├── e6247e013af4be85005869172a33db5f9f8c8d0a.nq.gz
    ├── e65fa6c69a7c3fb1640bf9da379bfa4ceeeff576.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e76438c0caf820a421970708adb4eec7418f9143.nq.gz
    ├── e8f6fa9b9106e2e393e58838ccb6473af4ba39b4.nq.gz
    ├── e98299fadc1d3ef112e9cc13685e1d6cdad11fbe.nq.gz
    ├── e9f0bdc58a78655b1b639e006e156ec4a31f3e18.nq.gz
    ├── ea6758f5e92e07f19bc2b16d716a860e70f8658a.nq.gz
    ├── ea6e695c5c7cd0b20d332c84204522fe1b692179.nq.gz
    ├── ed56e14ddd9b15236a00630fb1fc4bef01f61378.nq.gz
    ├── ee8ae11b41efb39cea55fc229ccb6edabbf569b4.nq.gz
    ├── f049d4c53173cc44e0d0755b874d108891a5bfc5.nq.gz
    ├── f1c9f7999c03d824622eb10bdfd42c137a96bca2.nq.gz
    ├── f29dbbec953cdcbbd3ec1e9685933551477b1d5e.nq.gz
    ├── f3c59420fea254bff1a89ecd44ccb1c31fe8d7a4.nq.gz
    ├── f3d0b7258f1c92054d63a3eb9b100dc1b9831f9a.nq.gz
    ├── f9f853d22a2c406549d72216677db8e579794c89.nq.gz
    └── fa07974be2f78db52f7876044d82effeb13afb8d.nq.gz

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

[facebookresearch/recipes](https://github.com/facebookresearch/recipes)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
