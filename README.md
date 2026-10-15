# Repolex Knowledge Graph of astropy/pyvo

RDF knowledge graph data for [astropy/pyvo](https://github.com/astropy/pyvo), parsed by [repolex](https://repolex.ai).

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
rlex download astropy/pyvo
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 545eac3ce72c5b13d706245a137ab5b345e9aaf3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 545eac3ce72c5b13d706245a137ab5b345e9aaf3
│           └── chunk-001.nq.gz
└── blob
    ├── 0035607b63521a66e3348ab942e0d2ce502e05f7.nq.gz
    ├── 01aad9ac18bd542a13901182fc710ab14e295609.nq.gz
    ├── 02477a5d52fef84914d275e09b260ef16bf0fdde.nq.gz
    ├── 027ad6a5f0a1861b8631ae25e7d5ab93aba317d2.nq.gz
    ├── 031e976007905d26687b8e0b4f375f7750a73dba.nq.gz
    ├── 03608c38d15deb9e343faf391c5025bbc32a9328.nq.gz
    ├── 03ae859ecdaf191ea40c95ab240bdae030b014d6.nq.gz
    ├── 0456c94ae23fa13ab8da38bad28d84cfc2dc418b.nq.gz
    ├── 05701e26874110fb8ca35294d167c2e4b59d067d.nq.gz
    ├── 05cbbc676cd0d96c8767260a54b12d9967bc079e.nq.gz
    ├── 07099693e0e98333e42780b33631450204d2ccd1.nq.gz
    ├── 07c0ce8d7de6111de9e7db55b9108c80c3dd29c2.nq.gz
    ├── 07f1a670195b7a31dc75bcbf2f33be484c090a53.nq.gz
    ├── 084579238e2e04aeb44bf99be4275a66a154a91a.nq.gz
    ├── 087c91be2500700d168f2ea326acc52d7a4b9e9e.nq.gz
    ├── 0979a2a3c8db30c262f3a7c3dd3428a903557c01.nq.gz
    ├── 099a6944b6a067ce80297d7027a2f93fade13853.nq.gz
    ├── 09d32daf83fd3445d4f39e90bd0cc51c9f876e33.nq.gz
    ├── 0a4dbc5aeef8c8f7c962df67ae7285290dbd8d9f.nq.gz
    ├── 0a63ba524826e0743144eac6762ee9fbf8c2a5c8.nq.gz
    ├── 0ca6afaf79fd532b5864e951be4bd0294a00cd5d.nq.gz
    ├── 0dbb96f018a0b3bdf3b9c1de470c5330826e3a8b.nq.gz
    ├── 0e4782e8fc8bf1ed919d8844ffd8d31c039601c6.nq.gz
    ├── 0ed050c67e73d31c8f2150f6a098c1f15f1c54a5.nq.gz
    ├── 0f2c9d23a79065397ccca04c02532605fb6e5460.nq.gz
    ├── 0f61f1836a803e1c6d46d21cb239f445686c8ce9.nq.gz
    ├── 0f901ad8969ebca90d9b584b84d363db8668bb27.nq.gz
    ├── 0fec885e4c0303d96d78c299605d7e2637ae8eeb.nq.gz
    ├── 10deddae06d8add5076efa552457e3921d14f7e3.nq.gz
    ├── 129461f9aa4afb70a1145a00f5e4ef12eb26f991.nq.gz
    ├── 1494f8d3bb3bbe7d1a8ceca4149654e79f5ec99a.nq.gz
    ├── 14b698b86d8c9b47faa0f48a5753d134532fe2ca.nq.gz
    ├── 1555fc383275001d675bf4df1b6d64971bc16528.nq.gz
    ├── 159c17c9b293ad5d02aa93f85bf5eae433073e08.nq.gz
    ├── 15a5169733f521d2a33e3b6f44e9d9061a9b785d.nq.gz
    ├── 15c09114dd3ae8e916648e9af6e545385358ad8f.nq.gz
    ├── 1650fb364f10b1a6c28cc1a85da6f6d4fb5301c9.nq.gz
    ├── 1660cf1a3ef167840dae899c6046cbceb23107b4.nq.gz
    ├── 16944d090391d2e19c18b57b391c366dc1db2fe1.nq.gz
    ├── 16eab3fc1a789175ae618038d673436c02f8a43a.nq.gz
    ├── 1706fd72f349aba021f96986de95a1ace222f603.nq.gz
    ├── 18c183a9c2d0b0e8498e372f133d7666758676b8.nq.gz
    ├── 198c8c508b17c7a1cc92a6bac49a878d6afe1dd2.nq.gz
    ├── 19d4741ca9cc2f54b586e2c2d4e8c8e99a44cae0.nq.gz
    ├── 1a13ec4c0f101338a685b34812e76661cb29a88d.nq.gz
    ├── 1a8a305a41cf5bd297a41eb018544038be79c1e2.nq.gz
    ├── 1b3f2455ab3f72cfdbafceef02d2d8f05d667b85.nq.gz
    ├── 1b7a6e7c7619ff15477750b7991756e2faf5ee62.nq.gz
    ├── 1be32f6c242b610ef3156a4cdc80241fbe87627a.nq.gz
    ├── 1c5096f53f1fc97b72bc7b1b5394d5b0ac5cb23e.nq.gz
    ├── 1c5a4dcf020e26f023844c86dedd59779e8f2ed5.nq.gz
    ├── 1cee3c1a6f361479ec39e9bb65494b69bb7931a4.nq.gz
    ├── 1d9cd878f4153c2ebf1c3e0716d5a025e86efeb1.nq.gz
    ├── 1e757a260a323345ebd4cb9546b0a44327fd3d7a.nq.gz
    ├── 1f768ee8b14d6dd3ba9a9a8c332d333bc7ab3c9f.nq.gz
    ├── 1fe4e80ba7f6c9c3c5f4c6f7119e8575a9972668.nq.gz
    ├── 2009b053601e7b98e9bee00416574219509256e1.nq.gz
    ├── 2058b8b85e53fa48816b472aae31e7bb50f67406.nq.gz
    ├── 208c3e4e7872bb6e88c6470cb8c4223df8684f80.nq.gz
    ├── 20c7cd4d5cb28f6e0d40aa4466dc00e26cecaa64.nq.gz
    ├── 2259d25acc2d4e922c6a29bb4d9db4ce7d12fa36.nq.gz
    ├── 229ca69f6b04f582565d7e22d586b3eafe7fe343.nq.gz
    ├── 2383b83db1dc8dc87348d10ad2a9472dcbe3ab30.nq.gz
    ├── 23ca555c71616b5914d4580ee537386fe2843762.nq.gz
    ├── 2445887e205c536430effccf6a7f34e964de18c3.nq.gz
    ├── 246d71343b096ee9e5b9ee30e989e6ad06c049bf.nq.gz
    ├── 25c48d365d26c34122daf4f61e910c3b584fa77a.nq.gz
    ├── 25e0071965a2578dbdab9fb334e825b6f50ebcb2.nq.gz
    ├── 26d2a6d1801a9b267068c7a5193e8d7b21a3dabc.nq.gz
    ├── 27d03c9ef88a303bb09684b667ee73daadd97a9a.nq.gz
    ├── 2838cf7411856325cf53d7c8e00a3b5c9319b11f.nq.gz
    ├── 28d19e097a9a1395e97e3a8f2ed35d6b40981b54.nq.gz
    ├── 28e0989a5be4d1e19382500f3de2c69d7e63015c.nq.gz
    ├── 290b2d925d37fd6eec5dcc4f1944541877c0469c.nq.gz
    ├── 2b1b2aa3b9c14be0b9246abcf44b4bfb93845a48.nq.gz
    ├── 2b64e476bda80ef22fb61c05498620154e910c8f.nq.gz
    ├── 2bd37aacb3708038b433e92e35ece8c7e9918ea3.nq.gz
    ├── 2de6b5e6f4dd8e14065938836aa894e5f6b92a99.nq.gz
    ├── 2e18cd1d5fd3d327246795ad3cca8f78b80bd89a.nq.gz
    ├── 30067dc406f0982791bd1c6cec38fef76ab9fdf5.nq.gz
    ├── 307843f64f53d0829833516a6617cb6867e616ac.nq.gz
    ├── 327608e65c655efff863f2f44807f4cb164b9689.nq.gz
    ├── 3329ca63aaa87421d91a03c42fccbce26bc71124.nq.gz
    ├── 334989da037536584765bc4e3561b83242708089.nq.gz
    ├── 33833a21e599e0e09aa78e6ecab85d017d22a154.nq.gz
    ├── 345d6b2a3086fa3297c401acfc822e87ac046b7c.nq.gz
    ├── 3470f82f468c7a8ef63dca5245260a0ca9a3b7b6.nq.gz
    ├── 34c4a920ae42a2d7f75006f1af63610e3a3cdce2.nq.gz
    ├── 351fa70c7057417701acafd163ca5b990bf14e2a.nq.gz
    ├── 35f4a52414e4059ae1ab18cbeda9103a90ef007f.nq.gz
    ├── 37810e4fb65d2dc2246ec81af5004a57f628cea5.nq.gz
    ├── 378b2bde6ee6e2ba120ed802b17c18d96d3beb67.nq.gz
    ├── 3822f7883f6fc2d9151ae85a0ea48333dae20164.nq.gz
    ├── 38af7d042b6b789e3be8a9d90244681287966321.nq.gz
    ├── 39de509fd72c648be147103dbb3638341102d9aa.nq.gz
    ├── 3dd18113e00cd368e9e97c0259a12785659a298e.nq.gz
    ├── 3f886cd788f1524bf4a0b129cb374af195075dc6.nq.gz
    ├── 406af0e922a44fd2918ce0b6fe2f7b8158c89bbb.nq.gz
    ├── 41041a32f1067c37ec73be9a2975dc327fc05a4a.nq.gz
    ├── 43905772dcdc9ed0729ca4a1b3352ce1228952be.nq.gz
    ├── 44ac0c57a02b3d8db3154689a7f7446161805a79.nq.gz
    ├── 45d245b082d94a8e3dd02c63d31b6472d2b2f7e3.nq.gz
    ├── 47aa3db4051217a8aea42b457e0fa2fa90bfad43.nq.gz
    ├── 47c92b8545ec67592619846009aaff421e208c5b.nq.gz
    ├── 47e9e72f3b37a9a27a5f939000cbe9ebc350e85a.nq.gz
    ├── 482b4a7f8c8a4566653c54bf981507a99b33a064.nq.gz
    ├── 48acdcc835b46dafdeaf3b5687d325626eb377b5.nq.gz
    ├── 48bc9e1b6fd9914c9ad5113e754bb2837f4abc19.nq.gz
    ├── 48e3d165775a59387916c3d86c8f9470c40a245a.nq.gz
    ├── 49704725cf60a77701ccf99dbbe90506a3f28ef0.nq.gz
    ├── 4a3ab580bf96bfe0c84e967e64a0b6c07a1b476f.nq.gz
    ├── 4a8559a09f321f73baaf12ce115659a38a58928b.nq.gz
    ├── 4bcf827a2161ee4ebd02e3fd360a4611b576b4ba.nq.gz
    ├── 4cb8bd1981a3fd73a64c16a8860ba5675122edb0.nq.gz
    ├── 4e003b90ee17b860fa7533f341dd9579c4ead8b2.nq.gz
    ├── 4e050be26ac963ea4babc4b53ea797527e9c93c5.nq.gz
    ├── 4e848b5b684112931aae178e2908df53be6710b5.nq.gz
    ├── 5055df8dca2434f8f58068bae9f0b1491f46c56a.nq.gz
    ├── 50f5f36461af644149c6865302a8c86d55ad55dd.nq.gz
    ├── 516dc7d9e02646cd0c2221df17174f102e35a558.nq.gz
    ├── 5345c89019ee24c2a62e22daba9ffe3a4c00a4a1.nq.gz
    ├── 53b08b82c1cebceb82b00e3764cf932a32b9e7d1.nq.gz
    ├── 53ee7e1955ed0d1de23470577c8baee47867a511.nq.gz
    ├── 54a58cf9a485803968868c1a08f387178eea85a3.nq.gz
    ├── 54d12ba3e20b8863a75a7539a6c30168a6845c14.nq.gz
    ├── 55348a5d468899e49d2346082d459e192cc7624f.nq.gz
    ├── 554c4b56fbfb0b00a1acea17cec8df565c526a4a.nq.gz
    ├── 556766c05d5dd1ffffda9ff1e32b5d173e7f226a.nq.gz
    ├── 559d2c92a4db69d90c2ee2d10be94f6309d15e65.nq.gz
    ├── 55a1636bbfc4794319022415f047d067fd8244cc.nq.gz
    ├── 567b1cfbdbdd7ee7093b91545127d44b8c231a30.nq.gz
    ├── 56aecc1e8e3b34246f0f0d1a3e4091f905890637.nq.gz
    ├── 56e8805b723a740956756caee3333624cb8fa8fc.nq.gz
    ├── 575564b4b7acab28bdd407f1b4fd2e555242a5c8.nq.gz
    ├── 576f65ee8e77afb2ad6ecdb632700f600bbc6d59.nq.gz
    ├── 58477f499f0fa014927dfcff8c4c4fc2003a6c95.nq.gz
    ├── 5eb6bc4de54929b5c37a3140cf4c9cdfebdcbbc4.nq.gz
    ├── 601006f394bc050d2c14917b14d143f60b64ea26.nq.gz
    ├── 61acfd269d0f86d0605402ebb35433d50c8ff144.nq.gz
    ├── 621e2766612de4abf752a39cdeadfb9b2aa5d6e2.nq.gz
    ├── 625ece03b758c5f41f8fa0ef1ead8a52fbda949e.nq.gz
    ├── 62af6ef7de5799faa590087e6183c76fb98db2e5.nq.gz
    ├── 63767deb963e328b85a76b952b637d9914c3189f.nq.gz
    ├── 63a4101865121f25bf541427ae908c15e1911687.nq.gz
    ├── 63fb6e3afb574427cd3bc01693e985d4cafc1acd.nq.gz
    ├── 670e9f5377ccefbd74da55088a414fdbb9edee2e.nq.gz
    ├── 677103f95702cd830472fa49aa99d5dd58a18c45.nq.gz
    ├── 6b2130433e08de389350ba7639aa1bbc1893ced1.nq.gz
    ├── 6b214a5c09d3a2ed5399a65ba6100bdfd0b070ca.nq.gz
    ├── 6b69e58bb876d584a10dd94d678b2b5600399616.nq.gz
    ├── 6bd95ce70a200052c8e6130695d5705b8fa8b855.nq.gz
    ├── 6cd7031143c2eb8ff661f6afcaf23bb2933f0904.nq.gz
    ├── 6ce9e1999441fb2947afc59eb1c2577a55d5af96.nq.gz
    ├── 6da26d613ee5f25278871952de5c926b6c9b06b2.nq.gz
    ├── 6e25c6d790d00af7627d998a849d9de6a86299b5.nq.gz
    ├── 6ea8087d0e251a0e0edeba0d8575ef58bbfd4548.nq.gz
    ├── 6eb363253dd0665784ff7fd7054f86eddbe7ba06.nq.gz
    ├── 6fcf5cdc69caf29a8126f3f171a59a8902b59603.nq.gz
    ├── 70726d95dbe934a79e0853fc48c2b612c2abdf66.nq.gz
    ├── 719cb6d56e00f3917995767a97c1eadae05edf41.nq.gz
    ├── 74360e041f58d9b8e3e128a53a269109f5c4ff59.nq.gz
    ├── 752be2105ae3d37ddde027b1e98d68d77e15c331.nq.gz
    ├── 75a255d45f5d6376d33239c89455d6398a191da3.nq.gz
    ├── 76d74ce7a9712f860bd6cdfdb5ca615e7d86e7bb.nq.gz
    ├── 76e2ff9b3424d50030fd665c422fef641cb1a6f3.nq.gz
    ├── 7755bacdd3a43dd7469c051ea5b28946fd2400d3.nq.gz
    ├── 776b7c0c6867999ad958223ae1be3979b36833fc.nq.gz
    ├── 78224092499c8e3d5e9b689224aeb17b8288409f.nq.gz
    ├── 788b2c58ec978b59835464570e4386ebba55318e.nq.gz
    ├── 7893d933821654bfb65d3ad55fab4bb001fc9d48.nq.gz
    ├── 7ca66da946f5fa5e5e54cc82de7623fa27d37bee.nq.gz
    ├── 7d062f0e274659fa8838c819c757cba262668cd1.nq.gz
    ├── 7d39ec60520be01821de8f9dc4b5d5d5ae64f78c.nq.gz
    ├── 7d98dffe063ab9e32f6d73b9487d086a29b73f7b.nq.gz
    ├── 7dc65a475d880666026de40bfd9f2b07e9ac524c.nq.gz
    ├── 7de4ac61df4287457aafd8ee0fcbfbd5391fedef.nq.gz
    ├── 7ee6dc9ba0bd76ee158c34e28277513937ed1d52.nq.gz
    ├── 803d0033d341b6aa8e96e129ca5fa0f0f5ee0ffb.nq.gz
    ├── 810c4491c34ce20a4e9c598a271fb83fb9830163.nq.gz
    ├── 81d872161abf9c1300d258e4a1af6e7ce14efb6e.nq.gz
    ├── 81f06b37abed5c662b84e8c69a79f7b6315fe325.nq.gz
    ├── 8282999e22e9e1182eae5109e6114e7c197d4522.nq.gz
    ├── 8290b5a561aa4a2f8de6af884e19b2e14e20e4a4.nq.gz
    ├── 82bcd0f81e37711706cda4213d4edaca39564119.nq.gz
    ├── 8564ee482ea8a42fc45f85d7a7e4d488a403f4c4.nq.gz
    ├── 86f94d895b040f27d5695f2a6b23e9c9662898cc.nq.gz
    ├── 8706af3e9faa21bd05c73acff78f67a0a7002728.nq.gz
    ├── 88c97fa4394a5bb48c6aa86f77af4d644cf4f44a.nq.gz
    ├── 898ea1bb9e5d61f860ca6584ddbd68ebbee1d6e0.nq.gz
    ├── 8b185299b1c3a2c18daa37a996ca0439025234c7.nq.gz
    ├── 8b80bcf742dc6f41cd7135a699ca0ff39432a178.nq.gz
    ├── 8fcab4e7e11955882f17b6c5c0cfead25981b470.nq.gz
    ├── 912852ee7b21059ab1d7c60a7f894ef4d3cc6fb1.nq.gz
    ├── 914b48e243d230092e70d8dc28009a07dafd42df.nq.gz
    ├── 92df19c46b9adcbfadf3647f87f62139a103106c.nq.gz
    ├── 9314fa0eeafadab59dede9ab4f5d2b96eb0518cc.nq.gz
    ├── 935afe6bafb38a18ec399581d4b94f1981aa527e.nq.gz
    └── 93dfe92b9c98e009c2f75b6477817411d3a15585.nq.gz

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

[astropy/pyvo](https://github.com/astropy/pyvo)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
