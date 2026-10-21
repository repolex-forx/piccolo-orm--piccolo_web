# Repolex Knowledge Graph of piccolo-orm/piccolo_web

RDF knowledge graph data for [piccolo-orm/piccolo_web](https://github.com/piccolo-orm/piccolo_web), parsed by [repolex](https://repolex.ai).

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
rlex download piccolo-orm/piccolo_web
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 61318f462c8cd723968b41df7da7d3a27bd0acb3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 61318f462c8cd723968b41df7da7d3a27bd0acb3
│           └── chunk-001.nq.gz
├── blob
│   ├── 0349f47b66b8abeab74f90c6c68bc9709114d5b6.nq.gz
│   ├── 0ac47a3a40fad86c0b09ca3aef9daf89a53fee1c.nq.gz
│   ├── 0f8ffc7082d2bd949e2dba390402a90943744bc4.nq.gz
│   ├── 1080486945690a55b462f6359c816bbd4c3682ba.nq.gz
│   ├── 127099a1256089947207876f6f8ffab7753ec4f0.nq.gz
│   ├── 13948b4f7542963b400389d4343b44253c64baa6.nq.gz
│   ├── 13a3e1dbfd300bc0e0baa8bfce27c8e6130d5d9f.nq.gz
│   ├── 155d109d48dde095ca14da36112d6cf21089a9f9.nq.gz
│   ├── 15c41171da4bc6b8e006a3a1479687eba48f1c22.nq.gz
│   ├── 178ba6ab75c889daf87836d151be817ec5c1bb42.nq.gz
│   ├── 1a0e2c2b29564d634d35e080cfb941a28d9f11df.nq.gz
│   ├── 1dc818b0a74de0602cb5941755a2a231bb7ea5c1.nq.gz
│   ├── 1fbbe92b90cc612884f944f54e5124102a0dc692.nq.gz
│   ├── 1fecaf0b7cb33333804241b8fd92a704f04e0833.nq.gz
│   ├── 20fc8df17be77c78babd7cbe8f6d0438d146c1a2.nq.gz
│   ├── 21fc29b358110b2a0b4da7ce228ff8b32a80067b.nq.gz
│   ├── 220dec7045ed0ed42590c148f5761a6c0fd0c008.nq.gz
│   ├── 2228f75c442932ad705eff6dc9676811c34236cf.nq.gz
│   ├── 234334f3e065c7a4660e452646afaeda817605e3.nq.gz
│   ├── 26fa3c1c3cef52ff78c5eb74acedfe52233aae4d.nq.gz
│   ├── 27ac1b6b8b405f6a8548d01d53fa4169f0ad7b36.nq.gz
│   ├── 2aa6690e0e0d1c244581e764a86cd487fa98aab0.nq.gz
│   ├── 2bcc58a18783751607042a38e6bb2ccd7c7f1380.nq.gz
│   ├── 2d27210c6a9c0729a2a927fad045e4ce0dfd9378.nq.gz
│   ├── 2e5eeea4450e7036566d2c9a7f19bf26722870dc.nq.gz
│   ├── 313dc4298334338269b07a77e870991451ef5384.nq.gz
│   ├── 33abacedd07789873c401fab4e1e5d943a14ffa6.nq.gz
│   ├── 38fa7af51d7dfea11db1ed7271321c911702568c.nq.gz
│   ├── 3a8c9008b86f9231444bce7fe7ff1690a9851e0d.nq.gz
│   ├── 3f3adea76c908fc5661728420a6d69705b53bee4.nq.gz
│   ├── 40fba78dc294112a12b5203d8ba77b283eb7d436.nq.gz
│   ├── 4153098cf70ea58fc8474722dfc77e078c45b9b0.nq.gz
│   ├── 41c81bdbe314c0de1f11f8cf59479e975e1380cb.nq.gz
│   ├── 4888b6d11e800747b42d4c0f0fc3b6ab4e621522.nq.gz
│   ├── 495d3759c075622f48a1acec017a9e5724a37c23.nq.gz
│   ├── 498ac19785aa42a5de4c4c47ed405fee0de0f7ed.nq.gz
│   ├── 4ab35abb9ce469a6586c250509bb9afd1d42463c.nq.gz
│   ├── 4b17447e27a7a2eac0d401f2a623e62af2f5837c.nq.gz
│   ├── 559579a79f76c2ff712e0d5152aa844bb248ab90.nq.gz
│   ├── 566d71295c544335c1436b97266f075931c5a53b.nq.gz
│   ├── 56964cfece8e0e6a73369ce5b8cf8f6166466f81.nq.gz
│   ├── 5750887e77d9c38bc1d6f6c2123b42cb62c3058f.nq.gz
│   ├── 59271d27607e18a5a97d92328f46408a7a22a84d.nq.gz
│   ├── 5db1ee0326478dad29f0ac0274b38c137bee18af.nq.gz
│   ├── 5e9352a0eee7f99705a866c7b3743ab0aa76955f.nq.gz
│   ├── 605e74634349b60bfcf3874163c0d3f06fd5e651.nq.gz
│   ├── 63e2489a23bc1f4f587dc8fca3e4dd12bf8d77fd.nq.gz
│   ├── 65ebe2220947af409dab15767d0bbf07874a2dae.nq.gz
│   ├── 669667df69ca7847a874a1c601fdc553dec4865a.nq.gz
│   ├── 6860998c6ad86aee6251595faef7c655ba2e1c72.nq.gz
│   ├── 70ba953cb34c94540bd2b5e8f26e1ab07a80911c.nq.gz
│   ├── 7311ad21c8c5b3d7c11b8eb8ed7d92a101b285da.nq.gz
│   ├── 75af462a625192ac1ee6997e12ae889131ecf762.nq.gz
│   ├── 7744da2e787c0e6eea1ba318cea80279befa3d0d.nq.gz
│   ├── 7a45ed1f6f5810a224ad7ef95a6f64ad72e8f45f.nq.gz
│   ├── 7c958340d8e4d4c30fe0f0dcd42f9da6328760f8.nq.gz
│   ├── 7db36540c0379de2a8fe327dfebdb41913c18fb4.nq.gz
│   ├── 7dfb9c4e498d3d13e574df521b2384c80ce4d24a.nq.gz
│   ├── 7e1d113db836405a80089750f14384c2cca6f185.nq.gz
│   ├── 7e76c2e27d1f00cc3d835aecab8c685e087393ff.nq.gz
│   ├── 7ee90aeb9a76406512c0feaae77d4ddb5c1d55fa.nq.gz
│   ├── 7f0f5a2f086ea00c4c396eff1001da536228d6aa.nq.gz
│   ├── 8268de1bfca181260899fb40ff99a960f672b6a4.nq.gz
│   ├── 850c5c4ab39cf8e81d6b7eccb3771d5ecdbe9a9c.nq.gz
│   ├── 86c2afe47671cc77e002d45fc347ccb7b4c9b4a5.nq.gz
│   ├── 880f9e4d3e2135cf0f272b3fd7ef8ce8f895f5ae.nq.gz
│   ├── 884b89e1e67746734a37fa5793ae6778cd80b89e.nq.gz
│   ├── 8afdd5ef552c48381b449b436d5928f816dd6469.nq.gz
│   ├── 8c7dc011666d820f585954377aeb13a578f0e041.nq.gz
│   ├── 8cc17e6859fca2fa80810b9154a20035cbc37816.nq.gz
│   ├── 8f358eb67ff6c1eac2d50e9973b1c801345776bb.nq.gz
│   ├── 929cf13801d55b1779323c82fa3362f335ae4db9.nq.gz
│   ├── 92b40bc1f008b4caee72c6953b848e95cd486cf5.nq.gz
│   ├── 92f3f4bc50eee334a106b368c80bb0f2da747ca2.nq.gz
│   ├── 95d1115c0420c1092f8ebb2af3a1b9cdd835f426.nq.gz
│   ├── 95de4f9087c64d2d3fd54a154dbdfb3e8417143c.nq.gz
│   ├── 9775c45e88c006612528fcd1fbb370a243794c41.nq.gz
│   ├── 9ccd02fb8e6ded2bcc10772017a725965b6f4087.nq.gz
│   ├── a1c2ba7ece4f784e299e236b24480643963fc220.nq.gz
│   ├── a29253f41d0ff7be07d919a854cb7663b4b22bd3.nq.gz
│   ├── a411a1eaf008e22fe9eef33ecb629cc50aac0dc2.nq.gz
│   ├── a5115a7af9dcd81dcbb30291a2041ffafe56f513.nq.gz
│   ├── a8c4f20fcc6b439ed5d2a89fd7e2ab7dca7bb51a.nq.gz
│   ├── a950c3f694110e6c6681c55e67d703a2a8018ba2.nq.gz
│   ├── ad16718b055dc3cedb8a3f0f66e12a4bfaf0a48d.nq.gz
│   ├── ad29eb4d112ff400075568a019d6bf3ec8c5ccc7.nq.gz
│   ├── b334ae6039af915c6af6f24d25e16574dcb364dc.nq.gz
│   ├── b4516f1077cf9f76044cdf0d7a42b564f62cb8ab.nq.gz
│   ├── b4c4a8e697604cbba2d3b2d105eddafacbcea6bd.nq.gz
│   ├── b54e5b55ee3711da04e4843bcd469f4a24ed021d.nq.gz
│   ├── b5abdfa8346bf5027528c3690d5e678e85fac3ec.nq.gz
│   ├── b63685a6767df8ca6afb6a296bb8407d70d18e99.nq.gz
│   ├── b6884f2112ecd3042a77e7c7fd604acc0f028b82.nq.gz
│   ├── b6e48a00c6b633896abc3b3d9a06b7dc6ad934fe.nq.gz
│   ├── b9a5bf542baa18d41d10e9cf19e8f1d5af7eb63e.nq.gz
│   ├── ba6dc5bb8340f33fabfd7f4c519bf420c150673b.nq.gz
│   ├── bbdb098c31dbbd93afd3a6eb45c02163bd4c2f44.nq.gz
│   ├── bcb936ea5a2076a5fb7b36c8d67542b5b0384a5c.nq.gz
│   ├── bcc0a7a7361d6cd4d3b0ee76e064757f52c73cc8.nq.gz
│   ├── bce67b750a7625dc2d4bc49e35b779182646efae.nq.gz
│   ├── bebc5fc0d2f4ed5d6bc5e69ba71d158785f782e3.nq.gz
│   ├── c80075eaca6cad8868bb2bab65b68defc6ec46b6.nq.gz
│   ├── cad384d2b63728bdc05b0ed1c72f47f1f012b919.nq.gz
│   ├── cae48014277d69ddab65d7bc1fd7902053ec60dd.nq.gz
│   ├── ce6382ff98574cf1e04a1e263d20a2d9d4c311fe.nq.gz
│   ├── cf654ea61665d49a3298a6fcf1f8f0b9d2e9bc49.nq.gz
│   ├── d2f8450236af635b4f801c579cd7b67d2236093c.nq.gz
│   ├── d3e60b7773792bfd9b0970cfaa9699996533ec05.nq.gz
│   ├── d4be8948d406f7f26329447d90c33e98b275f19a.nq.gz
│   ├── d66469bdbc775a881765e67e84809761f93d47bd.nq.gz
│   ├── d8835ec27f0fc31344a855c42c74def9bc1b4ed2.nq.gz
│   ├── da4d74d80a3da48a37f3f756982168250a556790.nq.gz
│   ├── dc6677ed71c1e3e9172df244718bd3ab15bdaeec.nq.gz
│   ├── dd7383fed9728f4334ed441c45ab2c986328905f.nq.gz
│   ├── de1b4dc0aa431b2d6e11c3c93ef66777eeaaef45.nq.gz
│   ├── df90c6a88b10b266333d9ad63089679adb383df2.nq.gz
│   ├── e38c02f4ea5ea7778e4683de0c0931dbc8aff3c2.nq.gz
│   ├── e69d252bb09a6aba119205c93fe775916d9c4b6b.nq.gz
│   ├── ec99fb22bf18d8ed70b74d0a0aef5138d364438b.nq.gz
│   ├── ed6cb35bbb023219321f3fcc30eabdb79e4ecf12.nq.gz
│   ├── ee2d95c4db02d24398d28ee146fa106fe5ce016f.nq.gz
│   ├── ee614317d75c736a30e0ebb72898898cb1f20ea7.nq.gz
│   ├── efa955783cf6494d510df1f471b4e0466955eb4b.nq.gz
│   ├── f079f972720988ca634b73b809503a09bc6ae71b.nq.gz
│   ├── f49f2f394f68410bb71b7fd1284bb0d4423facb6.nq.gz
│   ├── f4bf2e6cc7f26b737a37e4b969048afb0b1cbea4.nq.gz
│   ├── f6426fee75205b775c695ab3ad0faf1318b3c380.nq.gz
│   ├── f66e88092e5b155e69883b9390a2eb45f6b0f8b4.nq.gz
│   ├── f9c69472d7a0cb2444c91e34327b55ed1c075107.nq.gz
│   ├── faf64dc15c6def817bf09b2106ea3e3f53d0405c.nq.gz
│   ├── fdce73420fc2e2c161c171f2f486c68e596b6dbf.nq.gz
│   └── fe0cbd03a24b8a441c46563d550339f298a0fe05.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 61318f462c8cd723968b41df7da7d3a27bd0acb3.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 140 files
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

[piccolo-orm/piccolo_web](https://github.com/piccolo-orm/piccolo_web)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
