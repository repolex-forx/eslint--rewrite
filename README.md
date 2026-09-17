# Repolex Knowledge Graph of eslint/rewrite

RDF knowledge graph data for [eslint/rewrite](https://github.com/eslint/rewrite), parsed by [repolex](https://repolex.ai).

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
lexq download eslint/rewrite
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d2dbf7b73d01505da89a69b7465e486d8a88aa8f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── d2dbf7b73d01505da89a69b7465e486d8a88aa8f.nq.gz
│   └── repolex
│       └── d2dbf7b73d01505da89a69b7465e486d8a88aa8f
│           └── chunk-001.nq.gz
└── blob
    ├── 0010db6c8c87c068bb9d3d9d351b6a4f289dab9e.nq.gz
    ├── 0749d3711c9d1017eeaffb0793d17a0e0d70fd1e.nq.gz
    ├── 09982d6805a4ca9813481d84edfc1411cb383489.nq.gz
    ├── 0a02e1a0fd10a9a53623e685cc5138917fd69bf0.nq.gz
    ├── 0b580c510217753633f90d404a059bdc317d3a48.nq.gz
    ├── 0ec27fb8807d6804b31bf47f0dbda1bcf3f48061.nq.gz
    ├── 10ccf5a3947811397de7cda6b21fc15c68e657d3.nq.gz
    ├── 156d72a33401e471c147e6bf75c426c2e122260d.nq.gz
    ├── 16d8a42d2a65ef8c5f7fdb5803dc83102088c47c.nq.gz
    ├── 1736aac251aeda170c4a01f927b39dd6f33c369c.nq.gz
    ├── 18bbae7cfc6988dc627acbb3ef63ce1e7656905d.nq.gz
    ├── 19a5c672cf7f13dba8c084e50bb46a9a63184ad4.nq.gz
    ├── 1b8d61778e8f29747ffa9930b4297ef2bea886f9.nq.gz
    ├── 1c9eb46c25d0f6ecbf73b49f995efcf396c6235a.nq.gz
    ├── 1cdd2462f0ea50b7685c0748571ea9411f9f00f2.nq.gz
    ├── 1ce15682da980c8c2af788498186474c04912640.nq.gz
    ├── 1d2e669a54971a99f3b595e40b30f11d66bed0df.nq.gz
    ├── 205a2b5124f3b51172de780ed2fbc4a63729dfea.nq.gz
    ├── 2071c94cd7965f2ad4dabca76ed3f75a81732d05.nq.gz
    ├── 213e6de09134c9f748db9e6cbc3a8580784265ab.nq.gz
    ├── 21c59b95103d88b1363b6e860cfee3056982b507.nq.gz
    ├── 23260cd7d2e5d6d24bfea48f5b8b11bd6c3065e8.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 26302befc5d3fd7c28ee06d00e358ed3f87d88f8.nq.gz
    ├── 29e6e3f9809a0f7ff843f2fd97c45cd3528829eb.nq.gz
    ├── 2c3dc333436820c4da9fa5294576340e6c1f3133.nq.gz
    ├── 2d23b9c160ac27d199700918b842310e61d3547d.nq.gz
    ├── 2d49e39bdb11de44197db79deec6606e835caa93.nq.gz
    ├── 2ece54b6a4e9b32e98978d2a1f82cd14d63ac9c2.nq.gz
    ├── 2fe5e2b2e94db5f402c9ea29481a921c661d5b90.nq.gz
    ├── 304df261b0b68c713d2d77a44cf58e9b1d170454.nq.gz
    ├── 31eb06a69957ce52e99553da587cbd8ff4e9f491.nq.gz
    ├── 35a0bced5cff979a27e3c9ffa3c220426f3554f0.nq.gz
    ├── 38018afa9d32f13c8375fce12dcdc3ae4b9f7911.nq.gz
    ├── 382556ee81b67ed9cd7f5a8d24b9be2cc4de4412.nq.gz
    ├── 3bf4c4f2c27bfc63640a3e6d01e48a5bfc58d99b.nq.gz
    ├── 3c26905bbb7a320bf47990001f3d4677c5f0c749.nq.gz
    ├── 3c3adb4625f6e81cf2146ca26f27c4fafdb2e2d6.nq.gz
    ├── 3c9fa1540a1122cbae9788c7b254b1ed8e42a558.nq.gz
    ├── 3cda6859b80c289a456a00ac2afa9e27a65fad3d.nq.gz
    ├── 3f661b4658b02eaf5c9738749730184fd3a05409.nq.gz
    ├── 400269d102041d436106e6ea8732624a2f964502.nq.gz
    ├── 40a3546ead7226a013a7cf4e0539450ab327d20b.nq.gz
    ├── 40ece132839d5549f2abbe0f6305b7e82ea4863c.nq.gz
    ├── 4281354698c79aec99ee526c0a6d60acef62f9ab.nq.gz
    ├── 44912051b86cda52792264abd80813660f22087c.nq.gz
    ├── 4639d59c5fbc3097b6fc9eccf011977453cec430.nq.gz
    ├── 48af387f884e4815c3c602a8c84c07cef7b43001.nq.gz
    ├── 4a2f57108c30ddca8225f0db53a27bfebbd3a161.nq.gz
    ├── 4a308cf06d597bc99ebeeb1fba6cafa182f829ae.nq.gz
    ├── 4c27291b94eaf9836b92f4675a6b71619ccb0c28.nq.gz
    ├── 4d7285780fbae80ad6e8104f9cba65295b24ceee.nq.gz
    ├── 4e6f7b34ca687ded72bc349eeb551677cca84997.nq.gz
    ├── 51eb9b1b3818fdb6e9c7b4dc6ef450b04dba9d2a.nq.gz
    ├── 529c21bb6ea11ee463d487f32e0bec28178fde73.nq.gz
    ├── 531dff5ce9b903f833c960735b7f98aad78b3025.nq.gz
    ├── 546d4ff94acb82da26aef59f2cf22c77130d5f53.nq.gz
    ├── 54ff21792d2571fc1583212e0528f0b9b8abe97a.nq.gz
    ├── 56113a9f9998c6049c77ba1e7af98a692fb99b7a.nq.gz
    ├── 57eaab00301e9f650aca548e7b8e3f439ea44d00.nq.gz
    ├── 59149ffcd70c206d8c08d4504ba91623eac27e34.nq.gz
    ├── 5aa842f0abe3922b8a43663063294d3df5391fbf.nq.gz
    ├── 5b813a88468402dff07900a8f26e9c540ec2816c.nq.gz
    ├── 5c21341fb793fb52e7b8475c34dac3ac1da79893.nq.gz
    ├── 5d8149a4469803d4f8d3a8575b9d35216506d030.nq.gz
    ├── 5e6fda4594aaf445f15d0c53c76e6b8fb0516602.nq.gz
    ├── 5e7ad117520490f1fff2ab5768634fecfa2e174f.nq.gz
    ├── 60a48a8a699feeb2eac499bb9bcf2aaf9256767c.nq.gz
    ├── 614a7f37c9da53112fc38fed3418b8408ba4b5e0.nq.gz
    ├── 616d4b7e95eafe1c511a6a52d8156bb19889ae3e.nq.gz
    ├── 6386d4fac6f1830d4b8f27c12e990457f726bb48.nq.gz
    ├── 638c0f3a53aec8d669b20aebe4152518666af6fd.nq.gz
    ├── 64a05415e93bad10c54d8862c2d29f6e5264b895.nq.gz
    ├── 65e1f0f1031e00922d3ff26043ad6ddae7430d2e.nq.gz
    ├── 66a29397aa00e53f24d50b9c6bd0f1c0a7f747dc.nq.gz
    ├── 66c87d0aaf387fee4b2abb79f59770f1eeda801b.nq.gz
    ├── 67750a203bd1145a8d96bac4873b61ede5651ad7.nq.gz
    ├── 67eed0696a8a05f429f29ddd6a44e60fa9adf4ee.nq.gz
    ├── 6bfce2beb3b6e3725a4b636f9093f8de65ee840b.nq.gz
    ├── 6d990956af2d18351893e46ab58c972c5f685842.nq.gz
    ├── 6f7eddf19e7423f368b70e99880b033771ae0386.nq.gz
    ├── 70ba5e47abbf2b4e13cd6a6b6e4c2a213941004f.nq.gz
    ├── 72688540b195eb38ac279eae74fd356685a9a837.nq.gz
    ├── 75b77e314b01b61f193ca9bc5bdaa4e25770446d.nq.gz
    ├── 779639cfe4828117fb107019ab220b6bc56bda89.nq.gz
    ├── 7a722eab777fe136234a586cbebc2c23b487fa3d.nq.gz
    ├── 7ce10923ab237672f6b54ad1d22926925739d7d9.nq.gz
    ├── 7d7bd4710de5394db57a07e5b43f53dcb1de9661.nq.gz
    ├── 7f4ae65e5b5895dae49badc13b32c0418ba53800.nq.gz
    ├── 8144e77e229fef6be071cef50cfa925cb79be21e.nq.gz
    ├── 825c32f0d03d98995ebe3e6d797f14daf2df51d9.nq.gz
    ├── 82fe388d60e60f46a23e53f7f5f557e6617a8b63.nq.gz
    ├── 852b0e5197b41164b991e50bd13d09d2b8fb05e2.nq.gz
    ├── 857f70cf7639fc03823dc4fd9678c917e7a96193.nq.gz
    ├── 8580f8242eafd5dc0f85283e8f52ffcc297d889c.nq.gz
    ├── 8acf582c479b567fe85d60245f4ae99ed9bf8dbf.nq.gz
    ├── 8aedb8fe14c604626b315bcd11ea146d15509e42.nq.gz
    ├── 8e6e0a023365dcfe27ec5471cb6cbf64536fb146.nq.gz
    ├── 8ea48dce04b9eba706d2309571b39a4dd16a2c95.nq.gz
    ├── 9025a7c7382bae86fdd2e82d29e1c8f9421d03a4.nq.gz
    ├── 90573da872619b9f14b44520bdf6826f67a2a40c.nq.gz
    ├── 91164b0ff9227e415e718d11aaec6cccea7c4f03.nq.gz
    ├── 9140c9c424627afb0710ae9d350b85f27f466343.nq.gz
    ├── 91f2e3f94f33563d36d3300e7c1a5933f109b48b.nq.gz
    ├── 94c9f2a354e6377fffbde209ee4b77211f5f2906.nq.gz
    ├── 96d0986659e6d3a7d6d1421ac56b745a6924f05e.nq.gz
    ├── 96d55ab505b6c626dc56fc6bd27d69ba67db51fb.nq.gz
    ├── 978769d90c9fdd9ee4f4e0b711659636d8df48fa.nq.gz
    ├── 97b15fa89327aa25918548b62db6cf96fec8941c.nq.gz
    ├── 98a6ed1a7b3b693833286cf058b78b777ab66562.nq.gz
    ├── 9900e5f09d59d6b6f68252cb4bcbee65391df177.nq.gz
    ├── 9966e0b93b62bb497d514eb6664f1fc3c9ff31c9.nq.gz
    ├── 9984c2bd20d75c05d27f7cd256f939315f0ae95d.nq.gz
    ├── 99f09c08d4985c56bc98c0ef5451bc5beb9b9e6c.nq.gz
    ├── 9a9a062ed61b53dd5516e5cb22edcec17a2312c1.nq.gz
    ├── 9c9863c720f0d38d8c9f1ad2c78f5756a98a1141.nq.gz
    ├── 9c98d587045f8bbf5807cd9916edd825d40863c7.nq.gz
    ├── 9d172d1d5b32a1722d1df5c5bb1c032c2c50741d.nq.gz
    ├── 9d46bc087604dac7df384a980b6277bb8b53ae2f.nq.gz
    ├── 9dc2eb82b575b1a50983a31c1208558ca8270924.nq.gz
    ├── 9de24264e02e44c5ab389020e03503ddcdea075d.nq.gz
    ├── 9eaa603e9d3e0581728dd2561051173ca897e12f.nq.gz
    ├── 9ed858a8c1e43892d77fadddabac730d57275511.nq.gz
    ├── 9fb7175ba48029b900a8d8858ca4b7efcfccd986.nq.gz
    ├── a0ed0cff022991d7f270281bf2d9cb60ee51ff89.nq.gz
    ├── a117b390c9857389689ecb6a1d4d2b409bb352cf.nq.gz
    ├── a347d712e4c8fd94265926f8b6640ec79e7a3502.nq.gz
    ├── a3ee655a99190ad837a72542af7cb21cbfca93f4.nq.gz
    ├── a3f3b4474d5554777348bec5c9f7d5aa2a0531c6.nq.gz
    ├── a70b42986a5b6ff6cab6661857e14ae7c53090ae.nq.gz
    ├── a85fe17aaa0944bbcfa8afbd1cd8ffc7df769c55.nq.gz
    ├── a8cbadde8302bb8137db32570d7cbeb9be230577.nq.gz
    ├── aab622fe66f0e363df3252db3582547bddbbc402.nq.gz
    ├── ab8e8ebfb742b156f61dea9c71e1c0a289f6ada5.nq.gz
    ├── abf4e233897d10280dbba5a52d2b0d9f6218c9e8.nq.gz
    ├── ac2bc10e76e305af671641a9379b0e65e8128ea6.nq.gz
    ├── accffc858d43dc9baa56285a87888417a0db2ac2.nq.gz
    ├── ada28ff2056c534f0bf268ef07faf0ab5b70821d.nq.gz
    ├── b1720c3c20325a5cbb14961a74a6bbd7443f5e20.nq.gz
    ├── b1c33fd7b455794dc510cad84884d24126b41f1f.nq.gz
    ├── b215511468e9d847613218f30fbcc272eec26062.nq.gz
    ├── b351b0cbef8fbbdbef838162cd9155deb08b922f.nq.gz
    ├── b35a3109dd7b9bba1f9c16549269a11c6b16a3b8.nq.gz
    ├── b4148ee3331ea6c868e79f81f7d6ae81cbbeb262.nq.gz
    ├── b9322968356d58b08da02683902f0b2b27299a25.nq.gz
    ├── bb5a64364412c98742bae619c4c97fbfcf5d3a86.nq.gz
    ├── bb92433a5eba77f1c257d8057537996997ea054d.nq.gz
    ├── bbe6bceb003569297c4ba2f636384c2dcfce4520.nq.gz
    ├── bc16fe662dcf40df27be805431d340671fed7ba1.nq.gz
    ├── bcccb9ee4581aa6a7d3a02d89fcdc6ac24492e32.nq.gz
    ├── bcd43cd2198eef003eb96d292898784f7debbe3f.nq.gz
    ├── bed0ae74aa9d1f6f8bbf9e39fcd9361fda7a73cb.nq.gz
    ├── bf48b2b5679bef7be64f15ba3d76704b970d417d.nq.gz
    ├── c0f08be02aadee719b4280b130336a05c21057da.nq.gz
    ├── c14c97a0695d59886065e53ebb7246f410a871d5.nq.gz
    ├── c334317f16c4094b1d6cf8c123214a3ca81a4ae6.nq.gz
    ├── c6a8402822f291411d9538065ba6dbbf3d1b0864.nq.gz
    ├── c7043226e3cee1092ff8c66e268c2aa3adfd6411.nq.gz
    ├── c70c82830e977c8c3f757f9ab6c4a18e1b11f8da.nq.gz
    ├── c8082b8e14435df0341891583094bc4310a8dfc7.nq.gz
    ├── c881de639a48f905eeb00cbc637912a89d565090.nq.gz
    ├── c8891d71c613ba3a33c3085df34dd89cfa1d4698.nq.gz
    ├── c8f2485bc7d08c230490feb49e0c79222c5754db.nq.gz
    ├── c8f5c0e88a415294df370896efca8ac57535294f.nq.gz
    ├── ca27a13e99034532d0e96d56dde4e4f6dfe8fbb4.nq.gz
    ├── ca5df10ac9f3a659fd543f3049ae51c1254d19e0.nq.gz
    ├── ca7086bffe0a3735226f3c4c7cf1e22035570d96.nq.gz
    ├── cbf01cefc70092055937140c5aa46b4c7e31cbf6.nq.gz
    ├── cc230e8b1a903ffa4542538b4f6817294b830a95.nq.gz
    ├── cc36f4d25bb5ce6e6a68ec07396b0cc36dddff22.nq.gz
    ├── cdd3f5ebd11c2a8c8133173301f0224a2ce51aac.nq.gz
    ├── ce0cf8e7d742a7f8f283efb26adbaa7427763f37.nq.gz
    ├── cf6b7eb2f6057785d74afd38ae1347acdbd3a045.nq.gz
    ├── d0579a75853648fe2f9b611b283ec982b604ade9.nq.gz
    ├── d078731fbb1a07e49dd6b987b38875918fd60625.nq.gz
    ├── d1d85eecdd342de2edfb82fad4ba0fb078983ffe.nq.gz
    ├── d1fed39f84cf782a6bf61ff9da5ca8bf51d889b1.nq.gz
    ├── d369788cfb1fbaa0421ff8c514c7e4fd53458d62.nq.gz
    ├── d4519c186a3b20140a34158dd6836e69c6b05d63.nq.gz
    ├── d60f001d19ba5743d682b79e803e055af8cb622d.nq.gz
    ├── d6a5309dd4f050be91999b79463f34c89bff0d04.nq.gz
    ├── d88d1c37ddecd80c38881712e996db67640ac548.nq.gz
    ├── d94e4e8515b088ae4e04e321c6699e7a25ae6f5f.nq.gz
    ├── da8412aab7faa79533d58913f8ab699baca6b62e.nq.gz
    ├── dbf3f1c87662243a77dc95ea55be68020aa5de90.nq.gz
    ├── dc7bad59721c4a1f39b1f53821e6e2f871ca94b9.nq.gz
    ├── dccc948045dbe98c5ab0fa1c7b197ea50895605e.nq.gz
    ├── df767d4a352de7dc3d171c49ebef2a8a8cf4c9f3.nq.gz
    ├── e1239ed65bfdfff1fd55d28701c17ca7474acc97.nq.gz
    ├── e19de7a93fe2dc02a6752c618bce692ad819744e.nq.gz
    ├── e49fded65e005f6c2b752519d906464153ca5fbd.nq.gz
    ├── e60310db61d5c147baff721ba3041aff1f3e682d.nq.gz
    ├── e6801710faadbdfb90503c103870303c7d324c50.nq.gz
    ├── e733450ed128dce87d241fad1cef841beacc43ed.nq.gz
    ├── e87954de250de5d37de8add34cc48f430cad94ee.nq.gz
    ├── e893f52e779e48089b7cb710966309905c0c55f3.nq.gz
    └── e8dcac2d2ab1172e13d1dc02d50dc423d04caf74.nq.gz

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

[eslint/rewrite](https://github.com/eslint/rewrite)

---
*Parsed on 2026-09-17 by [repolex](https://repolex.ai)*
