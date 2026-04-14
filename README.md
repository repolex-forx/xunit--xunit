# Repolex Knowledge Graph of xunit/xunit

RDF knowledge graph data for [xunit/xunit](https://github.com/xunit/xunit), parsed by [repolex](https://repolex.ai).

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
lexq download xunit/xunit
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 43d309b32b9eee15cda0e7732962d5f5e6c05279
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 43d309b32b9eee15cda0e7732962d5f5e6c05279.nq.gz
│   └── repolex
│       └── 43d309b32b9eee15cda0e7732962d5f5e6c05279
│           └── chunk-001.nq.gz
└── blob
    ├── 006f3f18aad01694f0046be8f2e46f5ba62405a5.nq.gz
    ├── 00e3d858a76f048e8835b18d926edc6e49b74ec9.nq.gz
    ├── 00eb29a033d6ceeab79730308e3066bc4aafd066.nq.gz
    ├── 014442cb0da8a8e808045c5ec2eb05e6c7ba3c06.nq.gz
    ├── 016b95a3454c3bca69597d6e6558016bae1f0fe5.nq.gz
    ├── 017df44f9a1929851750b629b9c7cf8be68f571f.nq.gz
    ├── 01a7bdfc543c8ec7c74ee6ed3dbe8f84baec4a32.nq.gz
    ├── 01b2229f70fba4e382bae4f8d167d685e4bebc51.nq.gz
    ├── 0239a7e91c535b1f00ec241ea5ec0ec6eedf1cd0.nq.gz
    ├── 026e79ec37a093da5d5ab8176e1259853302f3e4.nq.gz
    ├── 027fd131f6b35e4d2efdd5bdda39d93aba0a01c8.nq.gz
    ├── 028f3546728dac699c6450cd97bd5e8c326d2ac9.nq.gz
    ├── 0295b9a48d48cea8dd0a8ec30ed4712827de7b3d.nq.gz
    ├── 02c2f65a110c5782c72fd5de55720321e4ed8810.nq.gz
    ├── 0311bd5baa93092216521d8a2e08cb612de46292.nq.gz
    ├── 03336ec1bd8aa7aad58b8a4966fc15ff3a9b3be9.nq.gz
    ├── 039a32c5a4185f8811c428cfc1c9bc8d47c2de83.nq.gz
    ├── 0405ed3a5d82c772e5bcd0e73298eccf94f00157.nq.gz
    ├── 04452e6a9f00695d28ca459bdd37071d55f1a16f.nq.gz
    ├── 04723278a627c55c4fffeecb66e1807935f5a626.nq.gz
    ├── 04890fba409a6a35391ce15b529d36c17ac87708.nq.gz
    ├── 050102d97311d7b794410efc2ef7bb5f1efce603.nq.gz
    ├── 05824392db53b873b7a2bbd1aa3804a551704bb0.nq.gz
    ├── 05853a575697ce8df5cbab77a132c9786f7d6510.nq.gz
    ├── 058f93ee572ff5ab8ebba656458450c4af8fd614.nq.gz
    ├── 05b0d723b592bb13116d31f8b657886cacfee30c.nq.gz
    ├── 05c0513b3abe6909a70b26c9128539dcb707eaf0.nq.gz
    ├── 05c0bd437c824d1601f94ddb0f60fb4c93b7867f.nq.gz
    ├── 060ff05279999fb77d3e30eb5cf9f0753ddd8807.nq.gz
    ├── 0632673451dd6c5859e2c528bd79848a18cde1a6.nq.gz
    ├── 0695bf293cf44ae6b7b1cc14299a26f96f97ddc6.nq.gz
    ├── 069b2a8673647f5fa6f643d55a8c487cce94a133.nq.gz
    ├── 0703d09f142258c33bc0a9963b2ef0adadeb3c3c.nq.gz
    ├── 0778f0eac0d2e2549e8b78afcb512975cb191dc8.nq.gz
    ├── 07942044468ef188130c3ae9019ed8bff482df80.nq.gz
    ├── 079f5ee76ffebc84fd5f29f355e5ec4820700c46.nq.gz
    ├── 07b70b6dace7d8ca26faa7321e0e8508d05b852f.nq.gz
    ├── 07c6cad8874f5c71efd13b6032c7c27546930bde.nq.gz
    ├── 07f6da8b191dbd1636ae861812015ec5e702d80b.nq.gz
    ├── 0815c2078e234883a7086efc253592de4277c610.nq.gz
    ├── 081da3fd4fb2cd85b6776ec03c6f176389024196.nq.gz
    ├── 0857a2943b285e01de67481bb6ed0571ec6b6800.nq.gz
    ├── 08596831a0304daddcea0657bf3b7ec9978ae193.nq.gz
    ├── 0890c8cc931435789eb8162fd5e8b06a224229c2.nq.gz
    ├── 09476e1236d4ae4ac6ce56e4f94763062e788903.nq.gz
    ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
    ├── 096a86203f4a96b2f60a853f3650d037cc65aaa2.nq.gz
    ├── 09d3069df1a517de0cb7f4c628e1b443e6b4c574.nq.gz
    ├── 09f8c98bff15c4b4503cc44e98849ef480db03cf.nq.gz
    ├── 0a1a27d04317ffce8e823a2ae9174fa6f05de6e4.nq.gz
    ├── 0a81e1d515033fe00c48fff5df567011424957c1.nq.gz
    ├── 0a8af469b10ef9ffe8707fc0d1773fc01d3bee95.nq.gz
    ├── 0a900187484f3508fb28c986bdf08a0fb73db8b4.nq.gz
    ├── 0a99d30a48279fcbef150f640b3ff5ba63e8949c.nq.gz
    ├── 0a9c54bf7ed2cbd681fbaea3bbe7fa0601bb9416.nq.gz
    ├── 0aa18d904b4e4dd1749daa443b4d795aeb4c6453.nq.gz
    ├── 0aa6d240bed855e96f8435d14de5411e09b7964d.nq.gz
    ├── 0ac72fcdeb7caa279d30fbdf9be501c04b6aeaf4.nq.gz
    ├── 0b0fd6e1378d69160b6229b8b11e82a3facaf523.nq.gz
    ├── 0b542f648f6b73fa99d59b16891333b5126905f2.nq.gz
    ├── 0b6248ebffd9decf6d0a3d9be60db19a579cb5f8.nq.gz
    ├── 0bdc50d54ddd6e1759bb12fc9cca358ade2f949a.nq.gz
    ├── 0c01e531aa9164c5b1704d559746d82ccbe5e803.nq.gz
    ├── 0c3c77b782fd55949d1707b8411edb2679e20ea0.nq.gz
    ├── 0c42f3cc294d6d7d716fb42d5cadffd5d0dc9409.nq.gz
    ├── 0c50e7fa57ecc7f97b41621c2e5d4814604260fb.nq.gz
    ├── 0c6424ede3108459b787b80b6372393fcb4fdc62.nq.gz
    ├── 0c6ea25ba6bdb5a8c902ae6d59d2db3a5bec46b6.nq.gz
    ├── 0c75be6aa23f51fdd7bba063c2e5919f7268e2c6.nq.gz
    ├── 0cd4370898f6e406ba0b1bf0fa7f8d47b875a2b6.nq.gz
    ├── 0d11874a6c03d35cf6392c9f6e93332210edeace.nq.gz
    ├── 0d702d2d4aaa266f5ae3cd859e1ed1e178a31efe.nq.gz
    ├── 0dd1e4087ff772dc2a69781050df0b6cdba49322.nq.gz
    ├── 0ddb0fe32d09b7253e4a1ed143ba8f4cd1b92153.nq.gz
    ├── 0deb24cf136a5de04f575c1dab95ac41f6398798.nq.gz
    ├── 0e000b4c551e2d38ebf60af3867460857285f448.nq.gz
    ├── 0e2b234d0370892b3e25ca09a1c84f275c916f77.nq.gz
    ├── 0e42e7a1885e83f63d86bbfe169b1769c7ee95ba.nq.gz
    ├── 0e715a0946e86e9355bf3dab657e2bf88acb616f.nq.gz
    ├── 0e94db7108b8d38125e396abb1d76eaaf1b5bd65.nq.gz
    ├── 0e9a7adaabd411b7d7c89e34b0f51f1c30114f9f.nq.gz
    ├── 0f419ec605ce66ae88218c1b8a3fd980da86fb54.nq.gz
    ├── 0f7230b436e0cf12e9f7d1c595f3a1a95d9dd541.nq.gz
    ├── 0f76a180938d4fa4c2efd9832a0f9a8f242f5bc4.nq.gz
    ├── 0f7caf7c8f10230dc7b357fad5416ec26a67fbc4.nq.gz
    ├── 0fb7537b23b5271f4c7409959da5b8d2ebd687ed.nq.gz
    ├── 102309e256e8888f9ef72a63684d0b44eb232c6c.nq.gz
    ├── 104670a9fccc84775cb261d00c2c3e8561ece29c.nq.gz
    ├── 105aaa0ab52c304286db6f97dca317b4957badb2.nq.gz
    ├── 1065967321bcafe3d40b97a311957a9a5c73cb59.nq.gz
    ├── 10700059141c1f2939970344f04f341022fccac8.nq.gz
    ├── 10e1127a765e7aee224c0f5b5a3377c0a7a054ca.nq.gz
    ├── 1108e4507d7ccb50c328041e2e2b08138643bf72.nq.gz
    ├── 11090928c481d960b437dfb6d9396e3f640cbcfc.nq.gz
    ├── 112287b1385e68b3e9877f2d6a7b19eb1217fbc5.nq.gz
    ├── 114d06a406a07cf17cf7865294569c84cc2bb7ae.nq.gz
    ├── 1178ab2a5c692159a85e89d858d1c61684810b51.nq.gz
    ├── 11cc30dbbfdbca739c962e28695761fa9075f577.nq.gz
    ├── 11e043649f6308c2b568a8fd63330c16480a974e.nq.gz
    ├── 11f2d4d04ee5e8240e3a4a8d001d9c47c43d5a6e.nq.gz
    ├── 120b36715e31ac51ed35aa11aa4b7b53da57767c.nq.gz
    ├── 123434ea42568b0571068a2fa0456893dae243cb.nq.gz
    ├── 124cb58d576b0bdcba8337dfe97271f58f671af8.nq.gz
    ├── 12560537b389253802e55ab2d78d866dfcf3dccc.nq.gz
    ├── 1288a39258d8f8b9611df600d536c60d8d6c14d9.nq.gz
    ├── 1288f6af21d8d9b71000f3e1bb869d4450d52b29.nq.gz
    ├── 12926cb250873ff209d81c46a0e18ec8782e895e.nq.gz
    ├── 12c23a075f6e0c6227b000843daa174cd91dc1e1.nq.gz
    ├── 13281b173726e0c87ccfa7e0c2b024aef2019768.nq.gz
    ├── 133b3190663586050e3692faceeb1f0582506af4.nq.gz
    ├── 135eb06534dd4b5ea65d150867967c4195b6d0f5.nq.gz
    ├── 136f0580a61e9fbdbe7a20715c49a815a1f13358.nq.gz
    ├── 13eacb3ad52bb1f4c7da3fd3168256b44f34e231.nq.gz
    ├── 143202b567dcc4aa3caf8f1c8fd7c52bbd2c45cb.nq.gz
    ├── 145b1bf5c8a280509c1db2b5d283b909eca40d67.nq.gz
    ├── 1484da9c5207e9ea99c67f0b505d58800f2a341c.nq.gz
    ├── 148cc67cbef55e8f9baad878cdad722ef4a46b89.nq.gz
    ├── 14b965b3acb8522f29789a0ddc21c3ba526cdb2b.nq.gz
    ├── 14ba0c9bc62c8a432f8af9d2bfbede78de2eadc6.nq.gz
    ├── 14c6be6e5698f49039f5202214b8635beeeb04df.nq.gz
    ├── 14eebbfe7ae19d12d4f97ace6d54fdb6315617be.nq.gz
    ├── 15216b4f07619cbdacfe6528d4d3407d562ff5cd.nq.gz
    ├── 153ba5cebf1de521d076cdc7c97075aeb22ddef0.nq.gz
    ├── 153ca6a3d18cfb67b690c5e937d418072f8f95f2.nq.gz
    ├── 157d7ca35658b10a23c02080e81c216e262af364.nq.gz
    ├── 15aeb71b330b0d493b2696737653708a81e27ed7.nq.gz
    ├── 15b340cf22a55cbef85eacb840ef2693f0871e74.nq.gz
    ├── 15bf9a8fef49eab5d46e1cf95c928576ad69d42c.nq.gz
    ├── 15d1dbe900115f26e7bf5c92231db9d08685430f.nq.gz
    ├── 1603a472732b1f15340db22c92c48dda32ee6482.nq.gz
    ├── 1619e3b3047684f1ec62ad4eb96713ade1842737.nq.gz
    ├── 162979e223507dc66cc423b5c275f92ecc9e710b.nq.gz
    ├── 169fc4eccb9ce6b6e44c3ce9e1957cb6f1aeb587.nq.gz
    ├── 16a4c6d9bb4481dfaa0f302eddb150dd4a414819.nq.gz
    ├── 17001d8cbc83976b7b816ef35c94de0ed2227a00.nq.gz
    ├── 1723a1f8b33e77619d8d51b3d160c57a9ca47556.nq.gz
    ├── 1732ad777031df0242dbc75675817683ae6b97ee.nq.gz
    ├── 1766ece4276b1d5203c44e8d66ba10fc8a3a828f.nq.gz
    ├── 17ffebd437f23d4a7b6b13eb778a0ada3b254fb6.nq.gz
    ├── 1842d1d826643d922bb1b172adadb6e2a4ba79fa.nq.gz
    ├── 184ef122c9c0fa1ad9950401a6943f0ad54ddf5d.nq.gz
    ├── 187f7a517d297730e7cb26c6a5541bf9ee60667c.nq.gz
    ├── 1884aca718cb5f5478ded064c699f370dd96bee0.nq.gz
    ├── 188c2f2f41cc05fcbd2d63ca77ecb0e8198e3bb8.nq.gz
    ├── 188c95414f312ff2b9aab201bd9fff2a23f14f77.nq.gz
    ├── 199db30ac5a8714d30e2dbe90303feb58f1f6412.nq.gz
    ├── 19b607f458fcad00868331628235b721cc5ea607.nq.gz
    ├── 19bc8c844fdfbaa0d0f7719da8deb1affcc650f7.nq.gz
    ├── 19d55b1579eafe821c5b986a674654da2cd16531.nq.gz
    ├── 19eedc427a67240575e2479bd279f3f272582923.nq.gz
    ├── 19f46ebeb123c0e83ead53f2bd84c6e520a515b9.nq.gz
    ├── 1a0315e179ea4624166eba6d5b536c5917190a19.nq.gz
    ├── 1a1df3db1dfa7aa4c92b0094063e660490eeec88.nq.gz
    ├── 1a502cec1bbe32ad79a407753c640f287eb48153.nq.gz
    ├── 1a76e23f42d05619ec07ab57124fab83a5c68201.nq.gz
    ├── 1a7d28c9190e0c495aefa096e69d29c6905033bd.nq.gz
    ├── 1a8006ce4d5d17f06c8648d3054f8919afb951e7.nq.gz
    ├── 1a96073050b1ffc63153b9f0a238cca49dbdcedc.nq.gz
    ├── 1adcdeef6d7ab3a466c844b09782c3da08b33ce9.nq.gz
    ├── 1b0d25cb073d222dedd97d789c10b169a3c55233.nq.gz
    ├── 1b1869501902d6d47e9567e8ba738096b81ef145.nq.gz
    ├── 1b505f601f3668c55c0f8b0689084bc8615c16d0.nq.gz
    ├── 1b60cd91b740ac78d5e883990bdf2bf468150904.nq.gz
    ├── 1b8f8419c78ad1f2a31f5befdb98367182dd3f10.nq.gz
    ├── 1bce5fe120c6b17e53bbf09cb8a926e2f4211afe.nq.gz
    ├── 1be9039432cf0dcaedae791c5f8c4fa9e878ff09.nq.gz
    ├── 1bf73ca672f341a8cf7d7cf12ab3a3636a3e08f2.nq.gz
    ├── 1bfd849e4b56f0a15d3dc2e69499d0825bf991b7.nq.gz
    ├── 1c103c8d1859b939878b6bf95434d2e21da0d8fb.nq.gz
    ├── 1c2b46f1cd6ba856f73896f83b2d501b7fd636f8.nq.gz
    ├── 1c8169a9f425437758c10b1d26a9150ea6b271a8.nq.gz
    ├── 1ca0007b8f86fbcfe256bf4687e71046dd922308.nq.gz
    ├── 1ca3998ebb5621647b89d4f112620b5574273f54.nq.gz
    ├── 1d4c55809df6f047f10bc718ed01a572404ef097.nq.gz
    ├── 1d9131f12e28e191d6a30d5a83e9a5b297869421.nq.gz
    ├── 1d9dc364663ab19dc605d7a25d19a545054fe8e2.nq.gz
    ├── 1da72bea99da824f0d06f7de1804f03cf80e7796.nq.gz
    ├── 1db501654239dc36e1807c85513698a093116651.nq.gz
    ├── 1dc0529e8459ded81f5149af6692eeba89002664.nq.gz
    ├── 1e01b224243c43fb0bde991b79d7461f897a4814.nq.gz
    ├── 1e2c97816c085f6f64bd4db287e602887373f5cb.nq.gz
    ├── 1e47918d87cc85649001f02e9fe7f0dd8bd7d703.nq.gz
    ├── 1e47970fb76271f59c6319feeb6080fa02d93a3b.nq.gz
    ├── 1e52b8a4a0126d4b33ecd940ec4ecea53353d2ed.nq.gz
    ├── 1e932c4a7561b5fb9b398fc4ac221c97e6fbb43c.nq.gz
    ├── 1edd62c78dfdfd2a9e81c6f1c5f759c34252fdb6.nq.gz
    ├── 1f1c4b3aec8e2958f9a9d580146b20a223abdf17.nq.gz
    ├── 1f1dd7555172568267e9c4ea4df3773ce8bf2109.nq.gz
    ├── 1f3e3bd963a3ed1c2ee2091aa4c24d42879d9253.nq.gz
    ├── 1facb45810bef7b45b9f27ad6ee12647abfd2693.nq.gz
    ├── 1fb48b97a53d33526de903e797074ad910b6c437.nq.gz
    ├── 1fb8e0e4ee6ef8f2dd13cfc1918621e3f75a7c85.nq.gz
    ├── 1fc624fb76c2011024db0c1835edede4a2bd2c79.nq.gz
    ├── 1fdc0b011f4941acefdb5503f65f076a4c56cca4.nq.gz
    ├── 1ff5263e038d6d1a7a08d42151197d253d844268.nq.gz
    ├── 1ffb93b41e5117628e7b149544580e373aabc20a.nq.gz
    └── 2021365acf6f597705a57ac62fe39708009b5f59.nq.gz

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

[xunit/xunit](https://github.com/xunit/xunit)

---
*Parsed on 2026-04-14 by [repolex](https://repolex.ai)*
