# Repolex Knowledge Graph of celery/pytest-celery

RDF knowledge graph data for [celery/pytest-celery](https://github.com/celery/pytest-celery), parsed by [repolex](https://repolex.ai).

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
rlex download celery/pytest-celery
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fdbdccf378a7d6fa3203c623c9bad238bee1e7f3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fdbdccf378a7d6fa3203c623c9bad238bee1e7f3
│           └── chunk-001.nq.gz
└── blob
    ├── 004717da0046f759696cfd8eb656885b072538af.nq.gz
    ├── 00676a0e1b0c156d027a3fc8673cf86852a1bc65.nq.gz
    ├── 0307b437ec6ddc0720ed772df3696ac9ffdb6ee4.nq.gz
    ├── 0346b3c2a272138cc225fd6d948ae37259412704.nq.gz
    ├── 05633a7da84f7918e506ba0b87ceb7bc336421b3.nq.gz
    ├── 063da150197e9f590d5b8501bf715d8f63707b9b.nq.gz
    ├── 0646eb8d82605d3287f0641a8a44dd9b8450ad91.nq.gz
    ├── 0763b7743d8cd118e564ea6949422d6af378163d.nq.gz
    ├── 084dd07f8137f9a07141c39302cfb8e7272fb027.nq.gz
    ├── 09f335bb2b61923b9dab8fa266cd2e8c7c1369ad.nq.gz
    ├── 0bc1aa42e7e54df54521178203abbbc184f8978e.nq.gz
    ├── 0bec3a5dcf68055cd88f62d2d589f2ca351405a1.nq.gz
    ├── 0d8518d14b3a9c31bfa584a047556e5f742fcaea.nq.gz
    ├── 0dfc5ecaf60cfd475bbee0573f3a1dc28a389b70.nq.gz
    ├── 1055fe4778e1210fe16321876b676468db2c83ec.nq.gz
    ├── 131cea49d589e7b19ed040808bcfae482fc1f45c.nq.gz
    ├── 14fe7971b6b78219cc37b8b7046d15b865dfff24.nq.gz
    ├── 1527f6c024c66c005d7d05a920ad959bb9cec8d9.nq.gz
    ├── 15afd47f4ab8c32fe4a42692a0e338ac48753930.nq.gz
    ├── 163234f205142340eca1bc31f208a267a690e966.nq.gz
    ├── 171af666f455b5ee0c8e8f001e1833fb9b9efd87.nq.gz
    ├── 176bbde924162ea9de27913deb93c1b316dd66ab.nq.gz
    ├── 1827ce06c0f5c35b1ce9a7383c496631200899c4.nq.gz
    ├── 18e03f683baac6fd3cd3328cdbcde354c175bd12.nq.gz
    ├── 190d58d09741bb70b5b9456c1858d3d17b342c65.nq.gz
    ├── 199e45bda3cd6b632e5b947be597a76f839689cd.nq.gz
    ├── 19b71f25ffb07fe675cf6141d526ee8c400745b5.nq.gz
    ├── 1a6b2dfe907bfb9d81b3aa08178cec04d2d9b860.nq.gz
    ├── 1acafa0b56d137bb376bbd354afc861cb3c6641c.nq.gz
    ├── 1c33df49146129fdeb7233f9f5d382ab6a410109.nq.gz
    ├── 1d1992b442c772334660a61015af100a2cebbc3d.nq.gz
    ├── 1d8a4da0c1076b3bad8a7ec084a96848d2a4afbd.nq.gz
    ├── 1e34336e7b8fedbab732f6b6df00db8eebd5c8a2.nq.gz
    ├── 1f7d09ead22464847d64bcb4398ef4241574a2c6.nq.gz
    ├── 2182f2142f97c345b07e2357f9f7c39f5cfd3ffa.nq.gz
    ├── 21e200e02b5a7bf6886cbc244dcffa4c0d63083c.nq.gz
    ├── 23011038945cb87ec643e278fa57ce7cc058a7b1.nq.gz
    ├── 238662648a20aa95808acc87203a586f9611dbd1.nq.gz
    ├── 2448ae4fcb7838eb5e49505426d06e0e59e27d23.nq.gz
    ├── 25163151930a25c27fd6d815a1b0cebe62a0c924.nq.gz
    ├── 25bcfb3e46b3391f5fb8bda897e7caa1af9de023.nq.gz
    ├── 271430b6a01de480c01a0ddbadca1d067a46a6f5.nq.gz
    ├── 2936d16c813c4ffbb7332175b72ea9074eb65baa.nq.gz
    ├── 2b7114d0e11a41787aa608a5220c36ee5efe4a50.nq.gz
    ├── 2d38c29b123633ef653f46b163d623f384fc99f4.nq.gz
    ├── 2d68be659860d707ac13fa36fd46111956728745.nq.gz
    ├── 30a912fe9dbb7bc3e1bc48cc1de1aa3764bf4a69.nq.gz
    ├── 32c105a1829236d2ba4572e71332ff8c0dff6bb4.nq.gz
    ├── 32e731f3176230d9c4d18dcbc055e3dfd2497cad.nq.gz
    ├── 339be48c8c4ff7179f231a5ec58c0f45db3cfa10.nq.gz
    ├── 34599c04c5e4a4a780558ad55690f72a5b729120.nq.gz
    ├── 35531cc18725f58c12fb9f6aca109e582d5984d9.nq.gz
    ├── 361dc0899ef2d338a62b1e238c72fd47f244b637.nq.gz
    ├── 3791114dfb1dfc1657fc183aa999efc3413a1fce.nq.gz
    ├── 383102c14edb150abba009fcc59cae966adaca90.nq.gz
    ├── 38640ede31c89613f61d3ddfb0613f468db6e7a0.nq.gz
    ├── 3886f8f85c73067ca5fcaf484279b8d891b8c61f.nq.gz
    ├── 38cdb250019f39703d4b70bfa6ec87f4f878eb48.nq.gz
    ├── 391597bab7d9ebc1677f383f02c4d4a6c908f925.nq.gz
    ├── 39677140d6800d8691f91219463f3531f9a8323a.nq.gz
    ├── 3d8d66d8447d665aec5307a222901c6f84a46927.nq.gz
    ├── 3d944bedded33cfffe9727f7746634d997dcc044.nq.gz
    ├── 41ff9d2fe416b4e62bc83d3e9f4c2ce326d9a1ca.nq.gz
    ├── 42bdf2e521e4c9a1f225a9cbfee35d6b07584d43.nq.gz
    ├── 430b7c85e9f29530016e53ac7966761283c52cb6.nq.gz
    ├── 47a31bc9d657ef5ba89d1889963b30ab32f1ebd5.nq.gz
    ├── 48de88142646bb07bfe546362e6368c58b065e11.nq.gz
    ├── 4959128243ba1dc19c855183d25579fe15248a44.nq.gz
    ├── 4c8dcdf9aabaf41717d9b02cd8e95b66df1339df.nq.gz
    ├── 4d235441d79c97639df5ab9517aec44631bd782c.nq.gz
    ├── 4d4fd837744af930b3823c703e278112251fc085.nq.gz
    ├── 4d86af476ef685c1a7615cd02983bace0a721d94.nq.gz
    ├── 4e7472b295201a62e782e76b90d56e6efde5d95f.nq.gz
    ├── 4e8477246ced6686198d75717da09b03bc8450fd.nq.gz
    ├── 4f025f623331b2a0e0b8af57445b0decc01572a6.nq.gz
    ├── 4fd37d5957629775e8224a9f907f0f1274369f19.nq.gz
    ├── 533d4d9a6bfbc9f0395448ff50f3aa234035bf90.nq.gz
    ├── 53797a9013701bd16b5b4fd0b7945634fd699a4d.nq.gz
    ├── 55519b4b5be6f1bef543a98ee8b30c45d05ae4b7.nq.gz
    ├── 5568b6d791f793c565bcd7f9dd9b8cf5235760e0.nq.gz
    ├── 56117d36e56cc7571d7cf0b0b360e6478ba82979.nq.gz
    ├── 563c3b50e543acfe46e547e87f4f0d24328aea53.nq.gz
    ├── 5779d4000957ba961fa91d440185f9eca7f665a0.nq.gz
    ├── 57df72703b71779afd6cfa5b0dddf3d00d361c59.nq.gz
    ├── 5857adca4de46148456b950878dcec9183cba968.nq.gz
    ├── 598d3907ff4fc00cabbfd0bf2f7ab49f025022cc.nq.gz
    ├── 59bbfa9a78d09937aa4e3ccd4c64df251d19511a.nq.gz
    ├── 5d55946e62e97e6b8d82450c12b3ec72429123f5.nq.gz
    ├── 5f2782f73d6c80ebd003459936f66e9cb6d39a83.nq.gz
    ├── 600a817523e8f4fe5a90682175934b536d1f2909.nq.gz
    ├── 60adf9b423e9a8034f93059e662f225dc528bd80.nq.gz
    ├── 60f00ef0ef347811e7b0c0921b7fda097acd9fcc.nq.gz
    ├── 6144030a723dfe5ab5fc3bac725c07b3b338945b.nq.gz
    ├── 64a657de5cd5a035781eb3f12e167acc233b9937.nq.gz
    ├── 65fe8d405ca97c678f46fafc37d84f5d513cc55e.nq.gz
    ├── 6732834a4af9e15c21dad1c7121c2ba9f3289d52.nq.gz
    ├── 688771e8fd82b214a3eb4a95909178c1db3f6195.nq.gz
    ├── 68a872c8fc25f214d98a056125c0ddbe1f3f5d1b.nq.gz
    ├── 69073671feca9b222046b79cb7951fef0b2a478a.nq.gz
    ├── 6a19206608b098a5c1c07483bcbcd7ca7f9e266c.nq.gz
    ├── 6b9fc29452abccb1a5b0524f0d176adcad7d0fa2.nq.gz
    ├── 6cfd043d427d24a2255696b4f4fadf6f46e3b625.nq.gz
    ├── 6d17594300a84409812ca3aaf602b146289e2751.nq.gz
    ├── 6deafc261704e20369c0983af88042e502ae4880.nq.gz
    ├── 6e298b2827567f2d8617891f176de0fc9b3c4072.nq.gz
    ├── 6f337c15d00e4c1a3aee1df2a9c35ff6652daefc.nq.gz
    ├── 6f34edc79a070779a9b5d00d7130d808bf284282.nq.gz
    ├── 703389d37c9d87f6dee571153f5454dc0ff01b5d.nq.gz
    ├── 706fbb473ad27d81ca5b10936757c35df40d78f1.nq.gz
    ├── 71bd74d74995b042c273a657b44218642b2080c7.nq.gz
    ├── 7216938da9f8ac3aae83361d98b699740ef55168.nq.gz
    ├── 73237066b00733ee736109f817ec104b252d8d05.nq.gz
    ├── 73d1e83b79d7668a5b2d035f4fb8e6ee69192e24.nq.gz
    ├── 76092a38029fed294f8b7753226d49a542b4c922.nq.gz
    ├── 77178dbefb56408b0858e15c70f9c1b59038c2dc.nq.gz
    ├── 797ced29436766e2b896550cf5a701031e84ba84.nq.gz
    ├── 79b5491c785b56e0eaebd2dd8c1cdfa5862050dc.nq.gz
    ├── 7c4dd9a8d27e51e82dc34feef211afded0b89d26.nq.gz
    ├── 7d22e17df3b4bf388f943101aaed58297a9336fc.nq.gz
    ├── 80f8e5c1c062e9fe672afc68f38e31ba3a3bf82e.nq.gz
    ├── 81faa305f4a9f8b7efb4e3bd4beb094fa33936ee.nq.gz
    ├── 82305b868eca3a4382729645ce4e1f58c05320a4.nq.gz
    ├── 82d545f603395e3e280ab633ffc4c61980b36d97.nq.gz
    ├── 840b3c1332b239c411f44c91ea324b38b931fd9e.nq.gz
    ├── 8559cbd55eb259fa9878484109eab6e1bb9b1013.nq.gz
    ├── 87a5bf9ddc36cdc3c2795f7d3356d20764a9c1b0.nq.gz
    ├── 886fb829ffac2b2b65386d2ad0d508f1125638a1.nq.gz
    ├── 8b98fb0a897cb8797e18d860057c18b51fb65eea.nq.gz
    ├── 8cc206044cf46e328d0b0ca977e2e8631b128173.nq.gz
    ├── 8da9343d550e50384a9710786cb388cadbcb1084.nq.gz
    ├── 8e5960d176a11997be97b4ab18a76e9888e65d36.nq.gz
    ├── 8f72b07de409048e759d88fc9465aca5e85186fa.nq.gz
    ├── 8f9eb3bececc460ff71ae9cec80562b75009408a.nq.gz
    ├── 91d1b785bb02a6770015be42a3c8f249bbfe1984.nq.gz
    ├── 932a6971a42b6f1a5765d52099013b17d8344dbc.nq.gz
    ├── 93efd55ea199509ba5ad88d090d07382709ef0a0.nq.gz
    ├── 958b327fde910731acfd9a2a8ad7c0a06e023664.nq.gz
    ├── 96f6df8c73af92bab4462bc7b90b451d8b2fdade.nq.gz
    ├── 9758953a22e6995902e4d61a5a280c26a3e055e9.nq.gz
    ├── 97b3e96908486b38ffd685239e58c95683f694ec.nq.gz
    ├── 9964e89d68133d0b63f478cb3b62693922f0fd52.nq.gz
    ├── 99e38dcb51e317e60e1e4d98e406b4440258a563.nq.gz
    ├── 9af6037998c2db4161a1fe38837fff5a4b2c879e.nq.gz
    ├── 9c37e2f4b30404be8bacb4f7dbe174c188085ece.nq.gz
    ├── 9c46548a6c1587459ad2ba158cf50c9c3d6517f0.nq.gz
    ├── 9e45dfa59bcad6711abdf2b377f4117673ca67e1.nq.gz
    ├── 9fee6550eefca3bf6e21bb77a2e473f302c00e2e.nq.gz
    ├── a1269150a52ddbe01a09cc728513860e4fc2efa3.nq.gz
    ├── a2100cd2ab3b7586deb15aee5a2271dd5a346b98.nq.gz
    ├── a3e71d31069e7a8caaaff22abc311135da106f8b.nq.gz
    ├── a5fd89268f2499e0018ecb29e09c4ba93fdd5adb.nq.gz
    ├── a71023389fd47ae0dc40bac8e953adef410b308b.nq.gz
    ├── a9c583d970c8db0e4696bc2d69b67e28e175a1c3.nq.gz
    ├── ab3330833637cc7096623a9a7dc14a06997a0f96.nq.gz
    ├── ac9e1b1c5eb4240f7e03ec46593f8f61c6ed0ed5.nq.gz
    ├── ad41099a00a7d6937959052a81bd7421a1933da9.nq.gz
    ├── ae81980838fae80595f77ce9810fe77a6a685ed7.nq.gz
    ├── af1295e9b2165a8e74909e9f1d24653ecdd05f97.nq.gz
    ├── afc11b0ae1d38c3d1fb62db9546d60ae3aa3df3d.nq.gz
    ├── b018ef9d0a2130e1376533f48893ad9c1c534ba7.nq.gz
    ├── b1aee3d3caee83ff8a412a9313932140cae55936.nq.gz
    ├── b1c28ca2fea087702060e11698f1ae80ceeda450.nq.gz
    ├── b21dd885184d96d81f1593cc7f619454ee56cc0d.nq.gz
    ├── b26af071c23fc556bad93b098e0f5e3d8a35f873.nq.gz
    ├── b6c98a481ea1c44134d8de4f3c1ebb26afa6cf15.nq.gz
    ├── b8dd2c76e5d5eb36ff7ebd057dd204c6c0704191.nq.gz
    ├── ba1e3e7087cfe8d11b63cb9be66f42791c6a0ac4.nq.gz
    ├── ba5b996354f5ca9a3bcac1004b82c25544aea8a1.nq.gz
    ├── bb238825f88d7ccf58e243e4a9511c1ea5c351de.nq.gz
    ├── bcfaec2ddab1dca9db06fe3751e98ceecc4e1832.nq.gz
    ├── bd22cd4a2db62b030040f08a6d90d155e7e624f7.nq.gz
    ├── bd9fb467121d15b867b1b76ac86bc4decb3ecf93.nq.gz
    ├── be9808f9600dcd43240af4e15ba37a7d873ed1d2.nq.gz
    ├── bf05606f3486816fe5df988708d7e2a64fc9a0ca.nq.gz
    ├── c1b0492d72a14b4a29094e65d3a7e0559cf47697.nq.gz
    ├── c1dc6a12b247b39ee42640e71b7f4a64e2d62875.nq.gz
    ├── c2481f754e9b924d80bd3a126ec114024a5ae05f.nq.gz
    ├── c309328aa0783658e8a31a1007493fcc04144e50.nq.gz
    ├── c4205211bb316b2d87045191988bc4b8aa425ded.nq.gz
    ├── c58f62418c3b45e8ee79564bc8a975d8034cad24.nq.gz
    ├── c667844f0bb566abff08d80834609f426288d487.nq.gz
    ├── c670c44fd63c912139e65206b879f8dbb8450fdb.nq.gz
    ├── c76ebc1f48423f26fd6521880bb72a11218d3f1f.nq.gz
    ├── c8c91d0decc4964458d7bb75f5d1de2ef31ec7c0.nq.gz
    ├── cb4a071053bb4a0f7861b45d579a2d18896050d7.nq.gz
    ├── cc0f67b99e986a8e74d9241b12dc02b422ef9b41.nq.gz
    ├── cdb4703009cbb936b554fa2b3a89a7826926eb6d.nq.gz
    ├── d25594d61001be890e1bb9d8465267154705e3de.nq.gz
    ├── d356ab598220ade0f6982a75bf8994c8f08fe8f6.nq.gz
    ├── d4169fafc78a2b3b7d0907ab881bb9288756f308.nq.gz
    ├── d46814344fca9962882537fbc9be8e70a0d69f3a.nq.gz
    ├── d737a422b6f9a1994db6b90ec356a8bdd99d55ab.nq.gz
    ├── d7f71437c95047097388380045c911d6647495f9.nq.gz
    ├── d9c696acf8ee058d3b62e5ae0c81f83e49b7b864.nq.gz
    ├── da0e074584173da8a3b2b0ce5127dd7ce637ea8a.nq.gz
    ├── daa761f7981757f628d0f1846874bcb98f0b391e.nq.gz
    ├── db3f35d1f1d29a040882e977caddfa231bfa5508.nq.gz
    └── db4984827b2295d05e3a4d19a6a25ac199e29f2a.nq.gz

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

[celery/pytest-celery](https://github.com/celery/pytest-celery)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
