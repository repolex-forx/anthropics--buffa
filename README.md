# Repolex Knowledge Graph of anthropics/buffa

RDF knowledge graph data for [anthropics/buffa](https://github.com/anthropics/buffa), parsed by [repolex](https://repolex.ai).

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
lexq download anthropics/buffa
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fcb490109f9b76746815f0534211856bf2d7baf0
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── fcb490109f9b76746815f0534211856bf2d7baf0.nq.gz
│   └── repolex
│       └── fcb490109f9b76746815f0534211856bf2d7baf0
│           └── chunk-001.nq.gz
└── blob
    ├── 00b799d359f6100bdfe9eea94521587c776fe21a.nq.gz
    ├── 02061bb753bca6e4013e47593d8d30d7c31fb1ba.nq.gz
    ├── 04414be79a7418bba81bb809f5e8a9ed3ead0c47.nq.gz
    ├── 0507a19b4c41c5d0266d1933e4cd27b84132005b.nq.gz
    ├── 0551dbb6eaca946fd5500b4ae64a77845b130a42.nq.gz
    ├── 076afcd1c62780cba822e75d516535a26d06bcd5.nq.gz
    ├── 089ca0198f6aac9eaf5814a541d8711f6fc35314.nq.gz
    ├── 09ea4856906b197c760f5d2322e5a37997f0ca88.nq.gz
    ├── 0a08304a69ba6d8be48bbd91982ff87fe346d562.nq.gz
    ├── 0c2a810344c86f06bef15c411cd61cd239dfac6e.nq.gz
    ├── 0c62cf992fe97da18878a236147deeb489161415.nq.gz
    ├── 0e0f08bb540f5a04b7701099a995d294095270f0.nq.gz
    ├── 0e91547b27d5cf432e1c353ed471d1c7c9ed0f94.nq.gz
    ├── 0efc9a5bd2bcf6e9c517d61e8ad58cf2c6438b2e.nq.gz
    ├── 102a6839d00b3e069e5795144221be0ec0d6cb98.nq.gz
    ├── 10d285f8a540f93c8d46e59a98514fedf24a7aa6.nq.gz
    ├── 1102735a01488edd670f9b5dc2c41ab127b77ba4.nq.gz
    ├── 13270895a8a24398062793bd42a4cfe964b5fa33.nq.gz
    ├── 1674d5e6896d4ad5f88997925e784fc8675793e5.nq.gz
    ├── 176ccf4eda36c24027b34915c2e997f7c44eee5a.nq.gz
    ├── 1781ab81a51d901db71b213813c3eede7a576338.nq.gz
    ├── 17c90c77ee3f4608b4f6ebfad36494f9f3221203.nq.gz
    ├── 18b8fe26bf8c14b243d9ba268dc84ef8c762ca8c.nq.gz
    ├── 19193b8893e9cc3ca7ee2823cfd873bccc460d18.nq.gz
    ├── 19402c02f88036daca74c8de091850e83a98081e.nq.gz
    ├── 1959fa55a4e7f284a9d6a78a447c5d89d137e87c.nq.gz
    ├── 1a0928da4bb2965016c68de383bc2028957d84ad.nq.gz
    ├── 1b88483cea9458a02f2a93dc1c432e20499a00f3.nq.gz
    ├── 1bf0c1ad9586578e8332d061f7648dcb041ec063.nq.gz
    ├── 1bf3086b317bb7e5263e4eea117a1fdcf37c9310.nq.gz
    ├── 1c6be058231f7c09bd304473d069a72636fe9f30.nq.gz
    ├── 1d30012a5705df41ba18727c6a99daf943fe6828.nq.gz
    ├── 1d32223d2656e3f7e457cc0a7a3d7f5c22036dde.nq.gz
    ├── 1da51226b5d3340e11741c70182eccec0b8af282.nq.gz
    ├── 1e002871e16589a36a1afe3f5ddc12c1535f1d9d.nq.gz
    ├── 206205011f727c38bdecb62f6674823469498c02.nq.gz
    ├── 20a53a825d7d616c38b9c45a660f4bb31e90afd4.nq.gz
    ├── 21c4d91bf76caff0545a25e5b425ff2c2e6dabaf.nq.gz
    ├── 227ea3951843d4fa096a3f6967d0ae0df1863c25.nq.gz
    ├── 22c99fd1a4c4a992b2ffd21b7cfd00447284965d.nq.gz
    ├── 232430b61413417952500daf2ce423f97e700bc8.nq.gz
    ├── 232eee895e152d67288b77ae479d6409db3fe8b0.nq.gz
    ├── 2460e89a4e88ecdc56a90236534ae68c1da62b5f.nq.gz
    ├── 252b0cf66e6766208d7ff0dadd9dd173035c6de7.nq.gz
    ├── 26f2eaa0096c9091f512f2e6c82cef3f7238deea.nq.gz
    ├── 281987033184a876ca29f51b06a1db045f7a6ac5.nq.gz
    ├── 291c90810b4a63024c99494cd84fee40f06c955a.nq.gz
    ├── 2a47380f2d44a7ff41ab09b74f398cd90c6dcf77.nq.gz
    ├── 2b0602cf62d174309166fda696b91a75aa2ba168.nq.gz
    ├── 2c6b5ce844591472836399731ebaedf791c8b7c5.nq.gz
    ├── 2c96eb1b6517f2617f9ddeae9f07f5fd7bd7ddef.nq.gz
    ├── 2d3c72bc45db9412dd6a18774cf0a90202101ebd.nq.gz
    ├── 2d9ef785d4f310ec2f6ecd371294e40c718fb310.nq.gz
    ├── 2e47ebf999fa3e12c5a0f4b2748ce7f4d430e028.nq.gz
    ├── 2ef584d68c9f41fcd1ee38c2d60a58325619ed35.nq.gz
    ├── 2ef6c5a5223d9491866da8b5affb74a463f43210.nq.gz
    ├── 30770c79e7b0ad3b496890f7ca515ea4d1adb91b.nq.gz
    ├── 3077a7ca4809648bf630c1d0a64063843e9b8436.nq.gz
    ├── 32084f836d78121b0df5c515cd57d94f217c82d2.nq.gz
    ├── 32463f10dc83519bc562c1a4e1121d2e1b2d23c4.nq.gz
    ├── 33792af378e3a252a4fade47dc29222d178b5677.nq.gz
    ├── 34cf43c53f2c25201e6fdb0b45a2fe3696956611.nq.gz
    ├── 3681503022b88a314ef25a1c38ffe17aba2faf00.nq.gz
    ├── 3783182b8678c8c06a504f2cfb22d8d17a913fda.nq.gz
    ├── 37a6a1744e9e7475110609a6b9ae65eaf04247aa.nq.gz
    ├── 387ecc364b9ac39cee0d082321d1566d23e287d0.nq.gz
    ├── 38e42ae2bb04f69ca0eb5990722faa46338dd6a5.nq.gz
    ├── 39b4aa0e8bd4d4c2825c86315544831f67412cdb.nq.gz
    ├── 39dfeca629aa3da9683ec5242c02cc3ba1606494.nq.gz
    ├── 3ae45ac0c324b1ee90031ca184b06fa6f1fab8c5.nq.gz
    ├── 41f40c22247de377be99e30784229f3f128508a2.nq.gz
    ├── 422a8101d9a2492a88b31777be61b8bb065c4853.nq.gz
    ├── 4233b8ce106bd9fe41106ca56c3f599cb76a0d25.nq.gz
    ├── 42fbe759a7cc07e5f41933d952c63b5fd29537c3.nq.gz
    ├── 4615072d3c0f71b177796138b5422149d0338770.nq.gz
    ├── 4667c4a003b287c6843e0bc1155d0d729ae1f7ba.nq.gz
    ├── 471a23feb608bab41c45bef155851f847cd22fb8.nq.gz
    ├── 475a818c5a7ea3561185c363650ca72ea2d0e423.nq.gz
    ├── 47b68b84906920292e685f0d75b8678e9a27276a.nq.gz
    ├── 47e603bb19b592402d1ca284a44c1c1236e679de.nq.gz
    ├── 495181a55cf5940a6542c6a8be37b44fce288ab6.nq.gz
    ├── 4955bed31b5aee2a257a4979edd3c1b6291b335f.nq.gz
    ├── 495ac32da2f2940f9c5a10f9bb5ba7f2fb8adfd8.nq.gz
    ├── 4cfceca529111187b5a7a2d0c332beb4760fafde.nq.gz
    ├── 4e480f6351a518eefd6f27cdd100f096fd7a8c59.nq.gz
    ├── 4f7e88d0bdeaf6bfdefdc3dd788846c2fb793069.nq.gz
    ├── 5154d24b2ccd609e1ff074a8f8e665a39b053765.nq.gz
    ├── 535c94df5f8abbd135ddcdb017c86a2db6a3a753.nq.gz
    ├── 542d8fce61b7ea2e3458f5a56389bab026084063.nq.gz
    ├── 5532364d807b0c4eac8dcffdc94552053d1b9bb3.nq.gz
    ├── 587dbc2b008397a468d864c9c16130e51c47dd8d.nq.gz
    ├── 58a40f92a70f5151ad0d07423a6f5a8e8a273f80.nq.gz
    ├── 58e429b3b72810c906959c1b222fc7b93a77fd8f.nq.gz
    ├── 5c6a05b81cd8e22b69a4e591c9cac69e94ecfbe7.nq.gz
    ├── 5d00b5cb661757af57c92d4bc9f315cb70a0611e.nq.gz
    ├── 5de5f43719b60354087ff234bddca8abf32cd823.nq.gz
    ├── 5ee4c9f198cb45040a74ce61e6419fbc87b254c2.nq.gz
    ├── 6102184a1e74c0cd2391e2f560c788424794f5a8.nq.gz
    ├── 61988003fa8b928c4bb1d08a2258742087cb0d76.nq.gz
    ├── 64be2da97fb35ae992828720fe3af86ff7bf2b11.nq.gz
    ├── 65253895dad5afc6ca8f6d835fc7094e6898be8c.nq.gz
    ├── 65283c5cabeb8617f29526b2424fa2fdca001241.nq.gz
    ├── 65ae99fede98235eb0abb8ce7a0b99aa52cab5da.nq.gz
    ├── 65c274307f5dbc2f027e90725b25a76144945db7.nq.gz
    ├── 663c92cb01dd1915edb753c65f86567e8b692b68.nq.gz
    ├── 66f95bb48013cdb1f9c4856e68d07588f14ac5fa.nq.gz
    ├── 677215eaba7a0797ae1dbfa12b1eb632bac366a1.nq.gz
    ├── 681311eb9cf453d0faddf3aacaec7357e97ba8e9.nq.gz
    ├── 69fd43665c2315508d1292c2f997c0d82211d2cb.nq.gz
    ├── 6bcf6b9fe239ec614db9dda846c7bab032ddafb1.nq.gz
    ├── 6c77f14c9e2bceed0cdf817138e5ced090a7a333.nq.gz
    ├── 6d36be0f281e5c18770013211e733118c681c19e.nq.gz
    ├── 6d56441cf9b3bc915fa984d043e590fb5f2f3e7b.nq.gz
    ├── 6d7f5b8e696b07a824f9962333fc396fe9db128d.nq.gz
    ├── 708483524ce96c56361eeeab43f07fe09bc826ef.nq.gz
    ├── 71010dad1a3ad07cf1a817f1904c2a3050a03987.nq.gz
    ├── 7103c0d20a027f6a34613d8ebeea2aa3146348e6.nq.gz
    ├── 71c54298d534d92fe6d17e19a7789ce2783eb218.nq.gz
    ├── 740976d8e4e0f85c6382d6d08e7e53919904788f.nq.gz
    ├── 74714ded7a2885468d1f504435639f6c45f1fb33.nq.gz
    ├── 747fe3419847ad1305383eedba0a175be46e4792.nq.gz
    ├── 7494f7838b0b44e78d6ac82d0e37ce852eacd244.nq.gz
    ├── 76c2365b634dce49bec8de0ce8213ef22b4a3364.nq.gz
    ├── 788cd104715af168c9de39edbd8d1c7561f0a35c.nq.gz
    ├── 78ad9b121a4a78a26e6c29c47deeecc0c01425c8.nq.gz
    ├── 794ea2d72d68084eccc415cfade5358254771b44.nq.gz
    ├── 7a03ff59371f4b053823710e59d5cf1a933ffd3b.nq.gz
    ├── 7d2533b7bc46ea06700c65ad5aeff384a7c50b16.nq.gz
    ├── 7ea3e7f37766be755072a4d63b065bb709885bd6.nq.gz
    ├── 8051b3e3f9d7d0a3dd3805e5dc7ba421ddf5cdc7.nq.gz
    ├── 836ed7f455650a83ceea4d735b8c18d6b6474399.nq.gz
    ├── 85bb7b414be43be9df2483b1b4b983ee8eb78284.nq.gz
    ├── 86868c19f7c357835242eff6716c13e20f04305f.nq.gz
    ├── 887d21911765c986a61995d493789e8bd1cd50ab.nq.gz
    ├── 8aee2f672832701739700aa9302dc38e804372ae.nq.gz
    ├── 8db7448a9da193fa34486cafc25e02cd4b24eaf8.nq.gz
    ├── 8f0d89107e37c8ede5d6eded33b340f968221037.nq.gz
    ├── 8f2877e5e779669566a02f53a456042fc968a487.nq.gz
    ├── 8f9156482a12c21e1721185ac68d2f23f09982db.nq.gz
    ├── 903842926fa49693c65a2a87d4a6df6756e0d9f2.nq.gz
    ├── 90c50e5f1729a7c5f331c3d815aa85f186550e0c.nq.gz
    ├── 9233df877e5cfdfe5e1052001acd53a8309ed2fb.nq.gz
    ├── 92bb543c5ce00c39cc3bc4a3f70dcc4c8851a5c3.nq.gz
    ├── 943851ffc4d06212469d916982e915186daa23fa.nq.gz
    ├── 95dc3d3f8cb2de796860d6d276cf36a17f2b0386.nq.gz
    ├── 964a5decb5bc50ffd47b0e8ea481f9bb3bb42576.nq.gz
    ├── 97b37c125e74aacdb3e661659aeff97a3c3d4fb2.nq.gz
    ├── 9923ff2c0cd43f0fb5ab425bc8942e2bb1c0c6ab.nq.gz
    ├── 9aa89a081783933352ef6f6bcb04a3ef1f2e0c05.nq.gz
    ├── 9b54992a013ec4f1b5d8aecb2c22cedf32e0eb45.nq.gz
    ├── 9b6f2439ec4c12ef289799c5cbe57b41572041e6.nq.gz
    ├── 9bc65ecf7e4817032665ec5271da72b3481797a3.nq.gz
    ├── 9cde0f4d91996a5a599c56f66c43ff4493fae8c4.nq.gz
    ├── 9d05ae647f5fd1b82c7bb46c926cf68e0b920b83.nq.gz
    ├── 9dda2e6bc582e2f5fccadb05335aa91e3a9289e5.nq.gz
    ├── a088166ce6fb1827b866438efd47d48ee4b8fd3e.nq.gz
    ├── a0c6e9d9b5dd407b414c2b2116f93dba57c0e65b.nq.gz
    ├── a4b43001ee0272b8f8b1ce48703a385357efeeac.nq.gz
    ├── a8b90f4ead2707cae0d09f86036166caa0096925.nq.gz
    ├── a98ee1994e8283fa47b523d820ea74ecf15defb4.nq.gz
    ├── a9f325f2bfc236dcbeded9dfd6680b24cf1f9bd1.nq.gz
    ├── ab0ecd676d11d53545506916aa330c4352a1c7de.nq.gz
    ├── ab976f98a103ef1b91b8ddf27b7d409ecd4f232a.nq.gz
    ├── ad1d1ccb6dc539d9b55f777bef185fc651d7061a.nq.gz
    ├── ada26a12475f3818872a68a6074ed2adcb8c2834.nq.gz
    ├── aded648b40526b0bd18dd27611344009ff7ff329.nq.gz
    ├── ae117e5fa733a0adf387e9ec0c6384a08c769379.nq.gz
    ├── b0f430cb422cc176278062badbbcf7a31f66cf3a.nq.gz
    ├── b28334b94392b8af397a05ed702690fa6c9ab1ca.nq.gz
    ├── b417722229ef14a70c506728aeddf8d216b5e8b0.nq.gz
    ├── b4a9332502e54ebec062e80d1c9f7a8ba619682d.nq.gz
    ├── b4ab62b57212731207d6d6b9cb53912d34d5c4a4.nq.gz
    ├── b50e20d9638e2518aff27e4bec556dbf0addbb1c.nq.gz
    ├── b673ce71c5186e7f953251174a7a81cb9de6e363.nq.gz
    ├── b777c3b0eddff1d200f625d9683709407b95211f.nq.gz
    ├── b78cd7e489689dc16cd9edbbbae90414d140ccf7.nq.gz
    ├── b835e50fe223ff87b1045c44dcc58673781e3728.nq.gz
    ├── b8699818a008fe5adaface9ebf9c17383bb23e53.nq.gz
    ├── bab2dfe818b79495606f2e3d455a97f639441e22.nq.gz
    ├── bbfc6618a226f12ed268e4a274001a27586eb953.nq.gz
    ├── bd895ed1a34f0da51836b2e9ad82944f49799a49.nq.gz
    ├── be5a04afba2564190adb496394b1ca40575fef5b.nq.gz
    ├── c085a4a0332ab3a0d83c987f6179dd8e673c95af.nq.gz
    ├── c1c5ed3780653b88651c996f46dff66fb2159c33.nq.gz
    ├── c1fb3edecba8d231643ff4e81359771e30a2b949.nq.gz
    ├── c2f857d14351b61aee6fbc690daf73f637a8f354.nq.gz
    ├── c49f247f18180a821a8f9eddf82f53f7a535c22b.nq.gz
    ├── c645ca478fd24f8261f14be2d78436c5408350a0.nq.gz
    ├── c7181947aa936cfccd10cc607ea4ee277e070c3c.nq.gz
    ├── c74e91f1499ba5065289f7670d7767a261a667a8.nq.gz
    ├── c7db01a587fd642c83839cf914d96e90bb6d34d3.nq.gz
    ├── c835fab1d49e71617b9de7a22e1db4c8273270fe.nq.gz
    ├── c8aa6232f2b321c9efe07cfc68d749c4862e62a6.nq.gz
    ├── c9d6cd8e6681cb956e726220d2893148b380d93b.nq.gz
    ├── cad4c82da51e4c5bdd397d1c270de776311181e0.nq.gz
    ├── cbd17ef443cbc9cb9864191d84bd144b0a47adda.nq.gz
    └── cbe20f73b9171a1206efb165fd6328b232d8a43a.nq.gz

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

[anthropics/buffa](https://github.com/anthropics/buffa)

---
*Parsed on 2026-04-16 by [repolex](https://repolex.ai)*
