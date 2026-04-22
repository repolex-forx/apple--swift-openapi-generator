# Repolex Knowledge Graph of apple/swift-openapi-generator

RDF knowledge graph data for [apple/swift-openapi-generator](https://github.com/apple/swift-openapi-generator), parsed by [repolex](https://repolex.ai).

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
lexq download apple/swift-openapi-generator
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 73997cc62c2193d5046e431c9d546119dda14502
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 73997cc62c2193d5046e431c9d546119dda14502.nq.gz
│   └── repolex
│       └── 73997cc62c2193d5046e431c9d546119dda14502
│           └── chunk-001.nq.gz
└── blob
    ├── 0176b4ddbf1ee266ffd3a51359ce40bd03ea3d52.nq.gz
    ├── 036dfc3bb6747a126405ebed1a2c4919dcbd7810.nq.gz
    ├── 040c641b1b0387e98c525045f2ae5adb8f6634ca.nq.gz
    ├── 04500c4e73f75373a7e35861af454c81974d6bb1.nq.gz
    ├── 04a6083344ee46856cf160beb12b4735c9c5d7d8.nq.gz
    ├── 052ca016cf3bdbaccd086d70e53c2652f7aefb0d.nq.gz
    ├── 052cc8eb8dcbc11499eec663040d956720ffe108.nq.gz
    ├── 05a7fb7a86191c17fd04539bd6e5d168a35a5ea7.nq.gz
    ├── 0875530ca7682ade9ff521ac0b4b7db3880e3377.nq.gz
    ├── 087e4ee9bd278e1e4e14b216e5588415d044e350.nq.gz
    ├── 08891d83f67181f147fc91135bf6c0016a2bea7e.nq.gz
    ├── 08b62d469603e36fcdf65efff5a42a7541c29570.nq.gz
    ├── 0a2e00eefc816aed3fdf35ebe9441e89871a093f.nq.gz
    ├── 0b1c0d0c2d11c19c21179db04a49fd5ac8ce5ffc.nq.gz
    ├── 0c217fbd9546789bec5f1995bac76870e8fa0894.nq.gz
    ├── 0da8df65cd41086e5abf6cf1b32254115c4c65dd.nq.gz
    ├── 0e3306fa933bbd369cd65204c1fef5e9e269f1a3.nq.gz
    ├── 0eeeba34265a4dc68d67069ac8ca5d0a211e4527.nq.gz
    ├── 0fa07dc975e0aeb0c796cfd32c5153b443fed77f.nq.gz
    ├── 1096ae08eb04af911a3caaac6a954a827ee9bd7b.nq.gz
    ├── 111a400a845ec1acf65b491f1c055a45ffeb9fa9.nq.gz
    ├── 112b9a8e9d2800a24b90cfac96033c54c187f97c.nq.gz
    ├── 1182bb258e56a7496b8f606765a547f6ce9cd757.nq.gz
    ├── 11b1c4cb48e33d3538060b4f1edbe16c9e247e1e.nq.gz
    ├── 11f1a22ae64953d789b23c62f419d06728433cac.nq.gz
    ├── 127de434c1ef345e3c585a9b1b2b421c046b7593.nq.gz
    ├── 128b5550268617ea240d04cad1f4e4cd061e6cf5.nq.gz
    ├── 13613e3ee1a9348462a11a77a619faa808a346eb.nq.gz
    ├── 13ef674eb577ef2cbfb48a1c0e21f86d8b58a07f.nq.gz
    ├── 141a34dff4f15f5043ba32e88607a116b6485057.nq.gz
    ├── 1430380709c5bd459850ec8ab8292297a4cf56b8.nq.gz
    ├── 1555731d3c15ac90fea53facc5504b70db657133.nq.gz
    ├── 1678ad56222144300c8d82e227b8aa94d75e49e1.nq.gz
    ├── 16eb02db5a4722b3908f8d51f9447b362c3b4031.nq.gz
    ├── 16f5580c9ca5c0914df45860aaf25eed576a75a5.nq.gz
    ├── 17e6572663a474413e8465471311aec8d486ace6.nq.gz
    ├── 1816cabc97510748e3b8079eeb13209c889ad7bc.nq.gz
    ├── 181ccf3874dab0224276c9bdce92748ecbdd6f9d.nq.gz
    ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
    ├── 19c38bd1861be4d5ed6765aae8742cd3d6315913.nq.gz
    ├── 19dcf61f33149bf8333930cf234912869ce58c74.nq.gz
    ├── 1a15d464faf0d557ec403080de6dcf04890ca740.nq.gz
    ├── 1b83a1bf2272d0cad80bed9ce2828875c7960313.nq.gz
    ├── 1bce2ffa9d78dc3c7c9ad337b91fd18864e8e718.nq.gz
    ├── 1c2696c6160975a6aed7bb099806c9f6dcb1245f.nq.gz
    ├── 1c2a243efd3ecd8800c13b00d27f1bbfa16af968.nq.gz
    ├── 1c503ae742b113cacdeac2f4052d85aa9d398fad.nq.gz
    ├── 1cf0267eb6beb79eb0b0fa0f04940ae981f40e21.nq.gz
    ├── 1d1e89f52e9beb23c056646d8877c5de1ca871c8.nq.gz
    ├── 1ebe5af7efc452d2bcab800f4906758bcadf676d.nq.gz
    ├── 1fe8b4ea646682e16b4c0138fccdcfff84aa1126.nq.gz
    ├── 202025f4304c59bcfda9b0c66f1f15781677a348.nq.gz
    ├── 2091a0f8c23a733af546ebb04b4d9e197779db06.nq.gz
    ├── 20f131c0355beb7687e30d6d0d23a8487c871092.nq.gz
    ├── 2279bd1a21fe85c6d90908d8cf26432da9cd856a.nq.gz
    ├── 2295d9eef10d511aa26ecd0cf7523c46ba515fab.nq.gz
    ├── 231becf8eac819d4c059a71f3f147d23ed6d7f50.nq.gz
    ├── 2348d37ba99d44699e1f0609f9bed5918a956d8e.nq.gz
    ├── 24405191b84d8a2124931f279f80d8c87a764ca9.nq.gz
    ├── 24984a65f08c44c061996ec82dc02ea0aad82d09.nq.gz
    ├── 24a2165dc712fb8bfd624b9dd5b44d94efbb0ac1.nq.gz
    ├── 258848f3d5bdabf275f318c24b899e99ac067e86.nq.gz
    ├── 25a67f5ed22df21702ea4af0f25ea21d3737d804.nq.gz
    ├── 26a4052963dcfd128a757bc23b0196a97d1da9e3.nq.gz
    ├── 2751186aaef1b446e9efeb5bb0dde914f8eea2cb.nq.gz
    ├── 27da7efa2d5638b76ccad5b41731b92fd512f2f9.nq.gz
    ├── 285bf5f967f2714b07af5522154f607163a07f0f.nq.gz
    ├── 290b39429b4d7990950746bdab18c6c0e7e8433f.nq.gz
    ├── 2941b10e0f2efe8143e5e1a16fbbc3478dae8d38.nq.gz
    ├── 2967d27b5bf3a2a7832a0434c0ac0c1bdfb1b96f.nq.gz
    ├── 29703d2ff9af6d5e7cf38557c7599bd381b45ab3.nq.gz
    ├── 2aec2e292bc5011bd0179072baaf5f7b17665605.nq.gz
    ├── 2b2af38c2de1d1f24792a0977d0bb06585d6f189.nq.gz
    ├── 2b6daa90aa5a506111e449cf4817946357fa37e5.nq.gz
    ├── 2bdeba3814cdab94f9af664fc04e176e00fa2d92.nq.gz
    ├── 2c2e126524fdb8927b27cddc39a26ade0976ddb4.nq.gz
    ├── 2cd5f2991957f443b5228a0f477f68589662a3ff.nq.gz
    ├── 2e5a0cae4ffd8d8d0dd7819e3d1d6e523db0d4d2.nq.gz
    ├── 2f9134ed99a9b2b291dd2b3e9c753c0af6d61a32.nq.gz
    ├── 2f9588285c74f0bbed950646605f489d0ca888e3.nq.gz
    ├── 2fd05ce3edfd253e4e25a7a2b5cf7337e28a364c.nq.gz
    ├── 3093aa6a8741c3361ed1a65230bda47a7f851931.nq.gz
    ├── 30c6268d3d866e27317623c416ebadad2120118b.nq.gz
    ├── 30c912935f88a6b2bc83ebf4459cc48a3cda9a7c.nq.gz
    ├── 310db658f65b850d2167a5a2dbccaf56d8e5402d.nq.gz
    ├── 3155d81b40bff0c6bfe925e8b19e002812938289.nq.gz
    ├── 31d787b82aeb5d97601e8bcdcc43be1126eaa115.nq.gz
    ├── 3213ba65bdb5a6c21dea8baac31ba94aa3bc19f2.nq.gz
    ├── 32f9b0a7a5b657f8d6a54ea0c4715ffb460a1411.nq.gz
    ├── 342138899f51a850e55e9f52685cc3c367e4df64.nq.gz
    ├── 347541ac54a975f19d803e69f10fe962f4b8466b.nq.gz
    ├── 35536b078fc947088f711ef0ff794f6713b24ebc.nq.gz
    ├── 3596a147b45dbb4aa826a433a651ac08e412f4cb.nq.gz
    ├── 36a54bb66b50d259ae95d62ac5fe59d92a3e91a4.nq.gz
    ├── 3706ef00b0b5124fa547769f50e7f9bccb483576.nq.gz
    ├── 396c56c54fd101af2603593cfe6cb72bb983f262.nq.gz
    ├── 399c11f8777d65fc609ccb9e6c76f0018e87e7d5.nq.gz
    ├── 39dc89d7ca358ba2dbf3afb97769d034b10716f3.nq.gz
    ├── 39e25cc49bc1cc4a8e6d12014b096467be7ff312.nq.gz
    ├── 3a6ffc66e9e659cd38faa6a2afd51c2c6033d7fd.nq.gz
    ├── 3a9a0d635c256c1874a416b61e9a976692439a9e.nq.gz
    ├── 3a9c89e36210fe17d3f5b76cffe3a3edc572c497.nq.gz
    ├── 3b1507bab848ffcbef71f346ff4c0b61f8007fde.nq.gz
    ├── 3b3684ceb51249c8c6d62c1814ce94466cf33572.nq.gz
    ├── 3d098c8f1e9c66a4460d4a68ced92b241ff6bee1.nq.gz
    ├── 3d0e0442daa93b05f1367086bf76720d32bb8575.nq.gz
    ├── 3dcdbe754aa13377600ae6cabcbaefb0bf3a0cbe.nq.gz
    ├── 3e4e48b0b5fe6b468434d6767749b399319f2da2.nq.gz
    ├── 40cdfa8b3ac9c77d1188f8b0d356d17bac27bd64.nq.gz
    ├── 41615b3b3c983e36e39aeb0bce1175ff1327f089.nq.gz
    ├── 4198091eef11536a17980fd1895a9fd167a32937.nq.gz
    ├── 42952905a0f993e65546a12cd6efa83b4e3a2476.nq.gz
    ├── 42ed6b2e82cced4bae34ebe4e1aac14800bd454e.nq.gz
    ├── 440fdc498e9ae8d77bc8c3dc860db7447c94f57b.nq.gz
    ├── 4410b831e6ecc5e0a54356a7ceba199a2c1e0fe1.nq.gz
    ├── 4474d74b7c7100e6d86ee42cba25e790738b195e.nq.gz
    ├── 44b0691285e8ae873b4882ab448703ccf2e5f368.nq.gz
    ├── 44c4f25416f452de4c17cbbdff6e83c8ae864c45.nq.gz
    ├── 44e20d5acc415f30f4fbc0aee37b21b1ea34f18f.nq.gz
    ├── 4527bbe91b0b9b92443d9a29326414aae82c0ae8.nq.gz
    ├── 4588b73e57230748aefcb95528ef19bbe35a2e8f.nq.gz
    ├── 46bcd0294f9c7b342754719ca962fb1952d849e4.nq.gz
    ├── 46cadef32c1912fd7a818f81486219bada232f0c.nq.gz
    ├── 471bb6dfc22b96265213608eb9a7174fc066a9ef.nq.gz
    ├── 4776d29a43ce826ad38d41ac2c1efaba9b7e2095.nq.gz
    ├── 47d269390a0ae42e2c350d06a1145355e6e50e8f.nq.gz
    ├── 48155db20157e045d21d658ada2cba8f0b3fb6c6.nq.gz
    ├── 4919a78673b4ffaf2df1d11a9727ded01e5f401f.nq.gz
    ├── 49fb4466f6eca6b8a0afb239e9ca97219afbe2b8.nq.gz
    ├── 4a7cacef57f5d1d540654c7eadba4d7d573484bf.nq.gz
    ├── 4c8494a4ed785b17509432e32252bfcf10ab9ef9.nq.gz
    ├── 4e4ee3c1b0e75ed6f79418d6e9e3bc3961731765.nq.gz
    ├── 4f45e2886a668297206c8a3053114a0398251ce2.nq.gz
    ├── 4f9caf2fdb44127c854f149a136fe116187537a6.nq.gz
    ├── 524e500f23929083abe30e31265cab574beaa5dc.nq.gz
    ├── 526f3ba6916f28ad4e03189d7c27cde5f47522e8.nq.gz
    ├── 5319cd013646bb1248d4920306f9164fb61d997e.nq.gz
    ├── 5448de584765d1c3ff591da06dbc59c6d85f5ce6.nq.gz
    ├── 54a1b6b9f6815f661d1da85acbec9df31bec901d.nq.gz
    ├── 5596602bdd40e704074a1b24333885b0d398eadf.nq.gz
    ├── 55992e890d7fe54ed32c6213d709ac09fa9a1745.nq.gz
    ├── 55c7989af2f705f950bd2c6a817028be951db3cd.nq.gz
    ├── 5672df8b504b0dc4b629a4b2a396d3d4dd8c39fd.nq.gz
    ├── 571986c20703be103617aeb12870715cf626fa51.nq.gz
    ├── 57ada4ae9cf9aef10d4c269a9dafa9dd843d9616.nq.gz
    ├── 57f12ffb1d805241894bc9d476bd31cebdf786e5.nq.gz
    ├── 5819aab6021d86315af07d3d7977b8d2cb9760cd.nq.gz
    ├── 5899fba36d142e15a76a29d0ee5c9e842d34e36d.nq.gz
    ├── 58f0dbffb43c7df3a80ef419fbfe1bd3fa34f635.nq.gz
    ├── 5922754274c77472722666c6043a626ec52a3241.nq.gz
    ├── 59f03875be4e5386627e79547f8726faefa6dd55.nq.gz
    ├── 5a0ca45bfc4d1ca0063a35b08bf5b66351896431.nq.gz
    ├── 5a8fe7daf80ab106166fae0281bf097bef6d75a8.nq.gz
    ├── 5ace4600a1f26e6892982f3e2f069ebfab108d87.nq.gz
    ├── 5aea608f102b5e4f2c52d536cdcf96ec0e7f2c35.nq.gz
    ├── 5c598c1bac96619f642d41d15adee5795f860c59.nq.gz
    ├── 5d005788448288f373ca5acffc2dcb7601e6e420.nq.gz
    ├── 608522f45a0e65f503af17f4f05e8e69f504e16e.nq.gz
    ├── 60ec288e6f9dee2408a9b321fc5884b1664ed660.nq.gz
    ├── 612b7af3620770c5266a80b6d9cd7cff6e082d55.nq.gz
    ├── 61488e3632bf37c94de6d4850f1836e2f2fa619a.nq.gz
    ├── 61c839dd6c65eca03d0209fa45b958f8dfe932d8.nq.gz
    ├── 62490bc76e6e3db3add4b73536486e6af692cb64.nq.gz
    ├── 63262bc72f27fcda8330e33993254ff4b9a6bb64.nq.gz
    ├── 632dc1e6de211b4704f99eea9e50c836269e2870.nq.gz
    ├── 637a25e37d621191caf3bb786d6562db46ca9df5.nq.gz
    ├── 65afa8ef64a71f38eff845fa1a76e34647ccc1b0.nq.gz
    ├── 67484d422ee255c0491e1280d5b9e66364382fff.nq.gz
    ├── 679629753dbbd25726562d60753f47f72c3309fe.nq.gz
    ├── 686368fd4f7996d692c2daceb83b136cc792d6d5.nq.gz
    ├── 6889e9b68bea12351cddc6b17f07e92ca026c104.nq.gz
    ├── 6990d6a275990a355370737d5052879b1a6f7e19.nq.gz
    ├── 69af650016784fd757c68e8556935930a7153189.nq.gz
    ├── 6b0b1270ff0ca8f03867efcd09ba6ddb6392b1e1.nq.gz
    ├── 6b44ae4f118748d4b22297a5bafe066b4b53fc46.nq.gz
    ├── 6b839ba4260587ffd08a4ec062d550780a955488.nq.gz
    ├── 6ce7cc5d1ba0e5ec25297b823e213274bf5df2cf.nq.gz
    ├── 6d46f0264ffa3fbefa9026f1e5f4bb797816ad07.nq.gz
    ├── 6d8e0798e518a21148625e4f5c1f94e150fc8a51.nq.gz
    ├── 6d9f5468572a489a30231732ab2a25552e7b2430.nq.gz
    ├── 6efeb4b5d8d0a6c3011a8198639583847e47bc72.nq.gz
    ├── 6f3d1782eb60406c56c1f97440225f3d8aaad618.nq.gz
    ├── 6f4edf66ad0d154b83ef3f094d67ff22f55af526.nq.gz
    ├── 6f8aebfb6ee8dab37defd25db3922e18709ae5ed.nq.gz
    ├── 6fbbea83d237f020ed9cb77d2dd8acbdc4a3f75d.nq.gz
    ├── 6fe9a309008c123cb8d00f96ece8a350f342241f.nq.gz
    ├── 712a74a8cef9ec5f75d603c0b9c98ac5d1329452.nq.gz
    ├── 71d66b2dac28d4679d8ea648a4449a71f25ab8d5.nq.gz
    ├── 71e1f59fea48df195f9eea6c57aa48a2b24e0825.nq.gz
    ├── 71e5ce2df3e07a81b2a986050d9438dfcc438f33.nq.gz
    ├── 724e061ed738d5ebd786993995c1d9e6cd57dfb8.nq.gz
    ├── 726d883d4489f788ccc5f41960405169cbb6f7bc.nq.gz
    ├── 728e4bc83d0adf75611f56e4e538d61fecb41daf.nq.gz
    ├── 737abe5718b158b80b305ccb98d7d2fc25676670.nq.gz
    ├── 73c00596a7fca3f3d4bdd64053b69d86745f9e10.nq.gz
    ├── 7425224653f0d244c6885d1c6b9b1f7e763daa79.nq.gz
    └── 74bb6f13e9db868e96d5682cfd85251befd81f5c.nq.gz

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

[apple/swift-openapi-generator](https://github.com/apple/swift-openapi-generator)

---
*Parsed on 2026-04-22 by [repolex](https://repolex.ai)*
