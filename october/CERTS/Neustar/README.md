# STIR/SHAKEN CA Ecosystem Compliance

## Neustar

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 324 potential certificate URLs were requested for retrieval
- 324 candidate certificates were parsed from the potential certificate URLs
- 126 certificates in the candidate corpus were excluded because they are duplicates
- 96 certificates in the candidate corpus were excluded because they were not valid during the target validity period
- 6 certificates in the candidate corpus were excluded because they did not chain to program trust anchors
- 96 valid certificates were tested against the remaining rules
- 1.03 issues on average found in valid but non-compliant certificates
- 100.00% of valid certificates contain one or more Error level issue
- 0.00% of valid certificates contain one or more Warning level issue
- 0.00% of valid certificates contain one or more Notice level issue
- 10.42% of valid certificates are too old to be assessed against currently enforced expectations
- 368 days is the average remaining validity of the valid certificates
- 373 days is the average initial validity of the valid certificates
- 1.28 average number of unexpired certificates per OCN observed
- 75 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_ext_certificate_policies](ISSUES/e_atis_ext_certificate_policies/README.md) | ATIS1000080 |
| 1 | [e_atis_signature_algorithm](ISSUES/e_atis_signature_algorithm/README.md) | ATIS1000080 |
| 2 | [e_atis_tn_auth_list_spc_format](ISSUES/e_atis_tn_auth_list_spc_format/README.md) | ATIS1000080 |
| 95 | [e_us_cp_subject_sn_shall](ISSUES/e_us_cp_subject_sn_shall/README.md) | US_SHAKEN_CP |

#### CA Certificates

- 9 potential certificate URLs were requested for retrieval
- 9 candidate certificates were parsed from the potential certificate URLs
- 0 certificates in the candidate corpus were excluded because they are duplicates
- 0 certificates in the candidate corpus were excluded because they were not valid during the target validity period
- 3 certificates in the candidate corpus were excluded because they did not chain to program trust anchors
- 6 valid certificates were tested against the remaining rules
- 1.00 issues on average found in valid but non-compliant certificates
- 16.67% of valid certificates contain one or more Error level issue
- 0.00% of valid certificates contain one or more Warning level issue
- 0.00% of valid certificates contain one or more Notice level issue
- 100.00% of valid certificates are too old to be assessed against currently enforced expectations
- 5020 days is the average remaining validity of the valid certificates
- 4870 days is the average initial validity of the valid certificates

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_shaken_certificate_policies_id_ca](ISSUES/e_shaken_certificate_policies_id_ca/README.md) | US_SHAKEN_CP |

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 11&#160;Mar&#160;21&#160;18:18&#160;UTC | SHAKEN-6744 | 11&#160;Mar&#160;24&#160;18:18&#160;UTC | true | [view](CERTS/414671d6f2e7beffdd958279b4cb2e705c5ee59f107aa1fb7b2a06008ae117b6/README.md) |
| 26&#160;Oct&#160;22&#160;15:49&#160;UTC | SHAKEN 745J | 26&#160;Oct&#160;23&#160;15:49&#160;UTC | true | [view](CERTS/85bf5f426006bc4a831a744672f2e2f2a936f7c6cdda1104d3ee1e7dab7268f9/README.md) |
| 08&#160;Nov&#160;22&#160;22:26&#160;UTC | SHAKEN 775J | 08&#160;Nov&#160;23&#160;22:26&#160;UTC | true | [view](CERTS/d5eb605cc1d3b7bc055c96732f267e1a74d7d4221627e5b7855686dac442766c/README.md) |
| 09&#160;Dec&#160;22&#160;14:48&#160;UTC | SHAKEN 899J | 09&#160;Dec&#160;23&#160;14:48&#160;UTC | true | [view](CERTS/5a4ff0a70a41cd82a090a2153380b441113444ccc15c2312a25119f01f775b09/README.md) |
| 04&#160;Jan&#160;23&#160;15:48&#160;UTC | SHAKEN 847J | 04&#160;Jan&#160;24&#160;15:48&#160;UTC | true | [view](CERTS/55944a7a6a5eb8c12ffea55e8f49762d5b5e8c316465dc07cb8cd94eaacc595b/README.md) |
| 01&#160;Feb&#160;23&#160;17:56&#160;UTC | SHAKEN 701J | 01&#160;Feb&#160;24&#160;17:56&#160;UTC | true | [view](CERTS/1915a0da7d3d06216e52ea2fa8fe13bda8f474476121f3ec13e61505dbb81b14/README.md) |
| 01&#160;Feb&#160;23&#160;20:15&#160;UTC | SHAKEN 917J | 01&#160;Feb&#160;24&#160;20:15&#160;UTC | true | [view](CERTS/a0e94d69d78f415a65335a51c5346d9434f81fcfda9767af5a43317163366172/README.md) |
| 06&#160;Feb&#160;23&#160;15:28&#160;UTC | SHAKEN 863J | 06&#160;Feb&#160;24&#160;15:28&#160;UTC | true | [view](CERTS/d828c0e0f959db420a930264a3a30051f6a8a457ed717183fe3061af78ea8172/README.md) |
| 09&#160;Feb&#160;23&#160;20:10&#160;UTC | SHAKEN 597F | 09&#160;Feb&#160;24&#160;20:10&#160;UTC | true | [view](CERTS/60f18673867347c3986fd3a6e45e07dc85f1fc2a0137b836d3633e3dc16c8bf0/README.md) |
| 03&#160;Mar&#160;23&#160;17:51&#160;UTC | SHAKEN 963J | 02&#160;Mar&#160;24&#160;17:51&#160;UTC | true | [view](CERTS/a8265b81ba231916107001a33ad513830f6da031bb4ebc416aa647da8465faf0/README.md) |
| 21&#160;Mar&#160;23&#160;14:48&#160;UTC | SHAKEN 973J | 20&#160;Mar&#160;24&#160;14:48&#160;UTC | true | [view](CERTS/a297461669b36df06235c621e0e8edb01134b482355a8b1d2ca65ae3f039f6cf/README.md) |
| 21&#160;Mar&#160;23&#160;17:01&#160;UTC | SHAKEN 951J | 20&#160;Mar&#160;24&#160;17:01&#160;UTC | true | [view](CERTS/364eb4b1c2247d7a676f8e833c74c1e023847f1c81b8db0135aee4b2b439a936/README.md) |
| 07&#160;Apr&#160;23&#160;20:40&#160;UTC | SHAKEN 502E | 06&#160;Apr&#160;24&#160;20:40&#160;UTC | true | [view](CERTS/1273ffd08a646d060eb8a642da40518417e565144f635f1065c21dc56ed64d3e/README.md) |
| 14&#160;Apr&#160;23&#160;19:27&#160;UTC | SHAKEN 525K | 13&#160;Apr&#160;24&#160;19:27&#160;UTC | true | [view](CERTS/3e9c61f0e5e87d7f60638dfe2e50fa27220c1370d07cc1cdea317b1c18aec2d0/README.md) |
| 20&#160;Apr&#160;23&#160;17:29&#160;UTC | SHAKEN 772J | 19&#160;Apr&#160;24&#160;17:29&#160;UTC | true | [view](CERTS/ed40b11900cf117dd4a3be5497716f782100263f7bb1d8fd58e352532e01ba6e/README.md) |
| 26&#160;Apr&#160;23&#160;21:17&#160;UTC | SHAKEN 704J | 25&#160;Apr&#160;24&#160;21:17&#160;UTC | true | [view](CERTS/daa06df334b71280bbef4d2f7b1a528b3bc38be2a7ef4919ae2ad15bc12d14bc/README.md) |
| 28&#160;Apr&#160;23&#160;22:27&#160;UTC | SHAKEN 782J | 27&#160;Apr&#160;24&#160;22:27&#160;UTC | true | [view](CERTS/8408053ed34c756b214c00f5cdde40eee1cceaf48a094e277f4a17f338a7bec3/README.md) |
| 30&#160;Apr&#160;23&#160;22:24&#160;UTC | SHAKEN 997E | 29&#160;Apr&#160;24&#160;22:24&#160;UTC | true | [view](CERTS/0dc3f445b4b78538a8c2c930df2b0334edcc81f225e64312ce14fc9e290b86f3/README.md) |
| 12&#160;May&#160;23&#160;18:57&#160;UTC | SHAKEN 743J | 11&#160;May&#160;24&#160;18:57&#160;UTC | true | [view](CERTS/0d177e2c26f5198a22e5d0ef59ab49aa741d7edfb2d5260b919ec93d753d1ec0/README.md) |
| 27&#160;May&#160;23&#160;14:23&#160;UTC | SHAKEN 869J | 26&#160;May&#160;24&#160;14:23&#160;UTC | true | [view](CERTS/d827d78eee1794b02205387ff0e32270c9c38f3a1870cb691a9008b8f094683d/README.md) |
| 06&#160;Jun&#160;23&#160;16:10&#160;UTC | SHAKEN 964J | 05&#160;Jun&#160;24&#160;16:10&#160;UTC | true | [view](CERTS/f11c23c8e811d23be78ddb50d7bff10b9ccc40065e20b3fca89907338c9e0eeb/README.md) |
| 08&#160;Jun&#160;23&#160;18:13&#160;UTC | SHAKEN 261H | 07&#160;Jun&#160;24&#160;18:13&#160;UTC | true | [view](CERTS/1218a4fc3a09a5b50fe3f9db0a51602302929a023c080cfbf17e6379847b7209/README.md) |
| 09&#160;Jun&#160;23&#160;14:01&#160;UTC | SHAKEN 049K | 08&#160;Jun&#160;24&#160;14:01&#160;UTC | true | [view](CERTS/47b82e9130c50e4c2f313bc5bfb183d76f6a73b93df2a6bb36ada7554514b722/README.md) |
| 14&#160;Jun&#160;23&#160;16:19&#160;UTC | SHAKEN 955G | 13&#160;Jun&#160;24&#160;16:19&#160;UTC | true | [view](CERTS/bae4645e4558cb2ec73fdea0f5457dddbb800576a78d86855ef539ae1cf879b0/README.md) |
| 15&#160;Jun&#160;23&#160;02:03&#160;UTC | SHAKEN 939H | 14&#160;Jun&#160;24&#160;02:03&#160;UTC | true | [view](CERTS/575afdc6d8ddae553b4b4afddbe4b92ecaef5142aebd9ea1a5d9d76219cf0600/README.md) |
| 27&#160;Jun&#160;23&#160;16:12&#160;UTC | SHAKEN 611J | 26&#160;Jun&#160;24&#160;16:12&#160;UTC | true | [view](CERTS/ba33f74b2906af894fcd1b7d05a3eb29a0b28338720c0a3f0e458262fe7e4403/README.md) |
| 31&#160;Jul&#160;23&#160;17:47&#160;UTC | SHAKEN 074K | 30&#160;Jul&#160;24&#160;17:47&#160;UTC | true | [view](CERTS/1432982516027658b4bc7c65083202869066903d620f7d4697fe5cd44e9f2dd4/README.md) |
| 08&#160;Aug&#160;23&#160;16:31&#160;UTC | SHAKEN 653K | 07&#160;Aug&#160;24&#160;16:31&#160;UTC | true | [view](CERTS/9dd80f49fdd3b6395c209a19dacd1cbccb0a0ac63c15de2b63b22e4d0c31502a/README.md) |
| 05&#160;Sep&#160;23&#160;18:06&#160;UTC | SHAKEN 813J | 04&#160;Sep&#160;24&#160;18:06&#160;UTC | true | [view](CERTS/56128dc722cabed54b68846848314bc0d70a13a74c24aec77d44c458943b6fb2/README.md) |
| 06&#160;Sep&#160;23&#160;17:22&#160;UTC | SHAKEN 5606 | 05&#160;Sep&#160;24&#160;17:22&#160;UTC | true | [view](CERTS/44938d933b83818e9cf43c282c1bffcc58a816ac2a02f3c1573812a5d357f835/README.md) |
| 09&#160;Sep&#160;23&#160;13:26&#160;UTC | SHAKEN 707J | 08&#160;Sep&#160;24&#160;13:26&#160;UTC | true | [view](CERTS/1a774a6ee34a87e52b35d18fbd1da865c2a4bf62de90c95a367da5049a2b7171/README.md) |
| 09&#160;Sep&#160;23&#160;13:44&#160;UTC | SHAKEN 292K | 08&#160;Sep&#160;24&#160;13:44&#160;UTC | true | [view](CERTS/520ea20a1387d2464ea8e0a74135ec13cee9c385b0c830b60a3e3776e3135725/README.md) |
| 26&#160;Sep&#160;23&#160;15:26&#160;UTC | SHAKEN 9555 | 25&#160;Sep&#160;24&#160;15:26&#160;UTC | true | [view](CERTS/b9cae288342f8bbe68f46fd1853f3f5f8f2861b9257b388edff1a7886a5ba986/README.md) |
| 11&#160;Oct&#160;23&#160;18:00&#160;UTC | SHAKEN 745J | 10&#160;Oct&#160;24&#160;18:00&#160;UTC | true | [view](CERTS/0c46ac56c70e04855e8215207ba71d9a3b5c5ef7621b59a73ef5b1fd982b0f46/README.md) |
| 16&#160;Oct&#160;23&#160;18:22&#160;UTC | SHAKEN 7575 | 15&#160;Oct&#160;24&#160;18:22&#160;UTC | true | [view](CERTS/e1355be9ce64d55f65cdf56325854a081dcc6a588f58a3472fd00d7f47f04e20/README.md) |
| 18&#160;Oct&#160;23&#160;17:32&#160;UTC | SHAKEN 510J | 17&#160;Oct&#160;24&#160;17:32&#160;UTC | true | [view](CERTS/c6ad12e2e74892c0478600fac25879b56ecbbb3a4a166795701723473bbe1459/README.md) |
| 09&#160;Nov&#160;23&#160;22:45&#160;UTC | SHAKEN 775J | 08&#160;Nov&#160;24&#160;22:45&#160;UTC | true | [view](CERTS/22b5fab5795330c9d8e3f859d1433361ea6eb0d56f407b2206769e2a3f03beb5/README.md) |
| 13&#160;Nov&#160;23&#160;23:27&#160;UTC | SHAKEN 436J | 12&#160;Nov&#160;24&#160;23:27&#160;UTC | true | [view](CERTS/07e63b47922a725d6a5f5f30d687c9ccce1ee29fc71f100fcea8a5b931711e24/README.md) |
| 14&#160;Nov&#160;23&#160;19:09&#160;UTC | SHAKEN 333K | 13&#160;Nov&#160;24&#160;19:09&#160;UTC | true | [view](CERTS/b787851ac85dd4c86ad310eb327ae546feb1cffaa12c50bf55d62bd859c882c5/README.md) |
| 07&#160;Dec&#160;23&#160;20:45&#160;UTC | SHAKEN 871J | 06&#160;Dec&#160;24&#160;20:45&#160;UTC | true | [view](CERTS/36b3eedd85ce2b659dd950e1a6a67e8e15ffc01f9aca42129663a5ee9a14203c/README.md) |
| 14&#160;Dec&#160;23&#160;22:49&#160;UTC | SHAKEN 899J | 13&#160;Dec&#160;24&#160;22:49&#160;UTC | true | [view](CERTS/39077a791fa8709ec7c274304998a6de7c58d48e5a4837f809a1733cc3d3764d/README.md) |
| 20&#160;Dec&#160;23&#160;14:40&#160;UTC | SHAKEN 719k | 19&#160;Dec&#160;24&#160;14:40&#160;UTC | true | [view](CERTS/31b8e7e61121d38cb205a6e125de2112289f5c775402f6920a327f140b8c0ce2/README.md) |
| 10&#160;Jan&#160;24&#160;15:18&#160;UTC | SHAKEN 023K | 09&#160;Jan&#160;25&#160;15:18&#160;UTC | true | [view](CERTS/5aa45e9e2ecd094b9dada73c3021db7433ed29dd36ce6a7602a750f4deab3048/README.md) |
| 17&#160;Jan&#160;24&#160;17:35&#160;UTC | SHAKEN 701J | 16&#160;Jan&#160;25&#160;17:35&#160;UTC | true | [view](CERTS/874934e2240ac125e73b2da95e73090d20d511da46036c3b3542bb44f4ce247d/README.md) |
| 23&#160;Jan&#160;24&#160;17:30&#160;UTC | SHAKEN 6744 | 22&#160;Jan&#160;25&#160;17:30&#160;UTC | true | [view](CERTS/f13b452519c21356d7b45b561b75d94bf826dbfcb822b97c954723002461d88f/README.md) |
| 06&#160;Feb&#160;24&#160;22:01&#160;UTC | SHAKEN 863J | 05&#160;Feb&#160;25&#160;22:01&#160;UTC | true | [view](CERTS/d2b00f6249ca58e13cea1675cb3ff7b3e184f032b5e3b353e14afa538f1afeed/README.md) |
| 06&#160;Mar&#160;24&#160;16:54&#160;UTC | SHAKEN 973J | 06&#160;Mar&#160;25&#160;16:54&#160;UTC | true | [view](CERTS/ed5567e59e424070bb6ee7973003075f7fc2bfa98b01f20b72d65c121d955d36/README.md) |
| 07&#160;Mar&#160;24&#160;18:37&#160;UTC | SHAKEN 030J | 07&#160;Mar&#160;25&#160;18:37&#160;UTC | true | [view](CERTS/fbdd2efdd483276787d0bba8729b7f4eea82e6a085473193349532901c5fd872/README.md) |
| 18&#160;Mar&#160;24&#160;17:12&#160;UTC | SHAKEN 704J | 18&#160;Mar&#160;25&#160;17:12&#160;UTC | true | [view](CERTS/ed459f6c9ccf57d2f8040f1ec1fc4ba88404d405887611b649540e61bbe45735/README.md) |
| 29&#160;Mar&#160;24&#160;17:49&#160;UTC | SHAKEN 951J | 29&#160;Mar&#160;25&#160;17:49&#160;UTC | true | [view](CERTS/8654a153f0d075c9afc904e9f9cf8ef081d0c5611839950bca2e2e3bfe391fee/README.md) |
| 29&#160;Mar&#160;24&#160;19:26&#160;UTC | SHAKEN 502E | 29&#160;Mar&#160;25&#160;19:26&#160;UTC | true | [view](CERTS/b0f5d195244c73153295e56b3e246b96ba02844c2a40202c16e4421e2846383d/README.md) |
| 04&#160;Apr&#160;24&#160;19:31&#160;UTC | SHAKEN 772J | 04&#160;Apr&#160;25&#160;19:31&#160;UTC | true | [view](CERTS/52927107212c21e7d34b4fc2484de84aac8f47b467a3d62c286303fc6ffc7400/README.md) |
| 11&#160;Apr&#160;24&#160;15:17&#160;UTC | SHAKEN 690J | 11&#160;Apr&#160;25&#160;15:17&#160;UTC | true | [view](CERTS/484326821838bfb399098d04384695cd63d833d9b262727a23e5b1c05fd81f64/README.md) |
| 15&#160;Apr&#160;24&#160;16:57&#160;UTC | SHAKEN 997E | 15&#160;Apr&#160;25&#160;16:57&#160;UTC | true | [view](CERTS/fa6c1952b481a1a69b032efb2d3bba89e6408158aaad971debf9d8057298be47/README.md) |
| 11&#160;May&#160;24&#160;00:03&#160;UTC | SHAKEN 692J | 11&#160;May&#160;25&#160;00:03&#160;UTC | true | [view](CERTS/563e8056a6f7eba3fbcddd21c02428caf90c0407bf2705b807371e813635ac7f/README.md) |
| 14&#160;May&#160;24&#160;15:29&#160;UTC | SHAKEN 181D | 14&#160;May&#160;25&#160;15:29&#160;UTC | true | [view](CERTS/938b23d50e23c77834631af5ca0f90799cc9e8f0ffeaaed2165f31c1265e40c8/README.md) |
| 20&#160;May&#160;24&#160;16:31&#160;UTC | SHAKEN 846B | 20&#160;May&#160;25&#160;16:31&#160;UTC | true | [view](CERTS/f779619520f5d47aca9c565df913d0d7417297a8daca4df038399dbd98bd1425/README.md) |
| 22&#160;May&#160;24&#160;16:40&#160;UTC | SHAKEN 7379 | 22&#160;May&#160;25&#160;16:40&#160;UTC | true | [view](CERTS/5ca4e15bfd722c0ef2da51e75a346933eaa7669f12d852b8265dfa031d92a552/README.md) |
| 22&#160;May&#160;24&#160;18:36&#160;UTC | SHAKEN 139K | 22&#160;May&#160;25&#160;18:36&#160;UTC | true | [view](CERTS/b42601237dcb1c77ca4896380df9e216d5deaa3b1838f0e749d033d99e593739/README.md) |
| 30&#160;May&#160;24&#160;19:25&#160;UTC | SHAKEN 049K | 30&#160;May&#160;25&#160;19:25&#160;UTC | true | [view](CERTS/221ef4b9a33a01f7b1009a025995b7dd484a0c3e19f0a261fc227936fbbc3a95/README.md) |
| 30&#160;May&#160;24&#160;22:58&#160;UTC | SHAKEN 767J | 30&#160;May&#160;25&#160;22:58&#160;UTC | true | [view](CERTS/b2025d2954f7f37671d12ae4e36c0cddbd06e43fc182ab4d6ec0765c5e32a726/README.md) |
| 31&#160;May&#160;24&#160;19:03&#160;UTC | SHAKEN 869J | 31&#160;May&#160;25&#160;19:03&#160;UTC | true | [view](CERTS/fd12139955fd921744c8b76c4c99b83bf2a73426421b31abed6c99618b4d4eea/README.md) |
| 04&#160;Jun&#160;24&#160;15:41&#160;UTC | SHAKEN 2455 | 04&#160;Jun&#160;25&#160;15:41&#160;UTC | true | [view](CERTS/0a2b27236292a4a2a8bd15873a6c7034b3e30a40cb0c3bdb4cae6efe68cc6f13/README.md) |
| 05&#160;Jun&#160;24&#160;13:24&#160;UTC | SHAKEN 955G | 05&#160;Jun&#160;25&#160;13:24&#160;UTC | true | [view](CERTS/d6aed2417609e5bab18e80927228e6c550a2045021fe17766b2f7bf342fb0000/README.md) |
| 12&#160;Jun&#160;24&#160;01:48&#160;UTC | SHAKEN 939H | 12&#160;Jun&#160;25&#160;01:48&#160;UTC | true | [view](CERTS/0ad417bdd791409e4898348037698c654959cea6429dbf2fb0a471f44c48297d/README.md) |
| 18&#160;Jun&#160;24&#160;18:37&#160;UTC | SHAKEN 697J | 18&#160;Jun&#160;25&#160;18:37&#160;UTC | true | [view](CERTS/723f017230bf9cee9e3cc5efe147c369423d24fa072cc380a3f036e0a60d6eec/README.md) |
| 28&#160;Jun&#160;24&#160;14:34&#160;UTC | SHAKEN 074K | 28&#160;Jun&#160;25&#160;14:34&#160;UTC | true | [view](CERTS/da5763a039a62edb0cd90dae36d2a457e0f778a904f439123cc98b83523eff13/README.md) |
| 01&#160;Jul&#160;24&#160;17:05&#160;UTC | SHAKEN 962J | 01&#160;Jul&#160;25&#160;17:05&#160;UTC | true | [view](CERTS/0ba8d7326d25fd1fdcd6c28325ddff0fe1cf610a1a8ec92ef8a8083e3f3cc4ee/README.md) |
| 01&#160;Jul&#160;24&#160;17:19&#160;UTC | SHAKEN 715J | 01&#160;Jul&#160;25&#160;17:19&#160;UTC | true | [view](CERTS/889452e1992267fbff32faea6e899da134b0ddce949cf87a93058d36ec1b48e3/README.md) |
| 01&#160;Jul&#160;24&#160;17:58&#160;UTC | SHAKEN 4036 | 01&#160;Jul&#160;25&#160;17:58&#160;UTC | true | [view](CERTS/0823fce516b339bda1acf5b484481f12fe068273d2760a87647fbcfd93591c6c/README.md) |
| 08&#160;Jul&#160;24&#160;14:51&#160;UTC | SHAKEN 171K | 08&#160;Jul&#160;25&#160;14:51&#160;UTC | true | [view](CERTS/e1fe072fe133772853ce883665c87635cc3989789b875f9fd19743a16715ec52/README.md) |
| 12&#160;Jul&#160;24&#160;18:11&#160;UTC | SHAKEN 0734 | 12&#160;Jul&#160;25&#160;18:11&#160;UTC | true | [view](CERTS/3694817483d551655d4deb864856f268c35cdd030263b72fb50a1dfc2139e93c/README.md) |
| 16&#160;Jul&#160;24&#160;16:17&#160;UTC | SHAKEN 0523 | 16&#160;Jul&#160;25&#160;16:17&#160;UTC | true | [view](CERTS/5e770904975223443b421b1b375e9ea47a2b5e9754d0d0d0d5d61a9b71ded91a/README.md) |
| 16&#160;Jul&#160;24&#160;17:49&#160;UTC | SHAKEN 704H | 16&#160;Jul&#160;25&#160;17:49&#160;UTC | true | [view](CERTS/676bb55edc34215ff6e38f805e1a3efbc77d6b49c5bec3ee9a918156177333ca/README.md) |
| 18&#160;Jul&#160;24&#160;21:20&#160;UTC | SHAKEN 558a | 18&#160;Jul&#160;25&#160;21:20&#160;UTC | true | [view](CERTS/6af235e2580e430922580fbdf255be09b24d784d63ddd118d338dd2527a6fa36/README.md) |
| 22&#160;Jul&#160;24&#160;16:07&#160;UTC | SHAKEN 235C | 22&#160;Jul&#160;25&#160;16:07&#160;UTC | true | [view](CERTS/c29c9334a93c4ae5a855a55f1c3e60f71aab7345e41e424180e2df20f8141dc4/README.md) |
| 02&#160;Aug&#160;24&#160;18:32&#160;UTC | SHAKEN 224C | 02&#160;Aug&#160;25&#160;18:32&#160;UTC | true | [view](CERTS/652a6cad05ce2c6d198c7bac5cd00089ea28e468dd9181569aa8c6a0f833e6ac/README.md) |
| 05&#160;Aug&#160;24&#160;15:31&#160;UTC | SHAKEN 653K | 05&#160;Aug&#160;25&#160;15:31&#160;UTC | true | [view](CERTS/cd7ee68b472bc66018e2b8f20c1f7760281442d4dfa38a5c6ac9f51aa6cd764b/README.md) |
| 05&#160;Aug&#160;24&#160;21:09&#160;UTC | SHAKEN 545B | 05&#160;Aug&#160;25&#160;21:09&#160;UTC | true | [view](CERTS/7cc64b1efd15233a30c036dbb737078a70f57fa90fc9304412f2a97d1974ae89/README.md) |
| 08&#160;Aug&#160;24&#160;16:33&#160;UTC | SHAKEN 710A | 08&#160;Aug&#160;25&#160;16:33&#160;UTC | true | [view](CERTS/3471bbb6f67e65ef8755acc2b953f95d8f3da877d7ba1f3f43bc16a1581b39e2/README.md) |
| 13&#160;Aug&#160;24&#160;18:14&#160;UTC | SHAKEN 502J | 13&#160;Aug&#160;25&#160;18:14&#160;UTC | true | [view](CERTS/f3830ae70430b0efbc7c0b93170b190e3278692ccf3264c13317e751b13916f0/README.md) |
| 13&#160;Aug&#160;24&#160;18:27&#160;UTC | SHAKEN 707J | 13&#160;Aug&#160;25&#160;18:27&#160;UTC | true | [view](CERTS/577ae45e12b17ae033b2170ee68501297cabbe2c3a3166bafab5a8bf94f177c9/README.md) |
| 13&#160;Aug&#160;24&#160;19:31&#160;UTC | SHAKEN 0347 | 13&#160;Aug&#160;25&#160;19:31&#160;UTC | true | [view](CERTS/77f832b11afcad3fc3864bfc53fc276c6a273cfcec5fa7b55825058f22c39df2/README.md) |
| 13&#160;Aug&#160;24&#160;19:36&#160;UTC | SHAKEN 709J | 13&#160;Aug&#160;25&#160;19:36&#160;UTC | true | [view](CERTS/9c28b0e6a5efb18f42d447ef858709acab4781e1f14468d2aa617483d0da0701/README.md) |
| 13&#160;Aug&#160;24&#160;19:42&#160;UTC | SHAKEN 219K | 13&#160;Aug&#160;25&#160;19:42&#160;UTC | true | [view](CERTS/b57d2f4d6594d1f64557e45b37da28b60c61ebb4119ea6ae406e6b75b0998496/README.md) |
| 19&#160;Aug&#160;24&#160;18:27&#160;UTC | SHAKEN 872J | 19&#160;Aug&#160;25&#160;18:27&#160;UTC | true | [view](CERTS/0ed4f22a2a19b5c7e8c70d7955a49dd652582f02dbadbb3863f213282404567b/README.md) |
| 22&#160;Aug&#160;24&#160;00:32&#160;UTC | SHAKEN 678K | 22&#160;Aug&#160;25&#160;00:32&#160;UTC | true | [view](CERTS/2bfdb76da8c7bc6f2f353899498fff61918a60314ce7eca8f5ac9d32d2d9a1ae/README.md) |
| 06&#160;Sep&#160;24&#160;17:13&#160;UTC | SHAKEN 5606 | 06&#160;Sep&#160;25&#160;17:13&#160;UTC | true | [view](CERTS/65a65fadb9982a4917eaeb9acf4a2630e216eb56608731d54d9c121ea4bccf5c/README.md) |
| 09&#160;Sep&#160;24&#160;19:39&#160;UTC | SHAKEN 7126 | 09&#160;Sep&#160;25&#160;19:39&#160;UTC | true | [view](CERTS/fcc811243704c597f352e036e72a821672199f0b6f323fc8129625aa40bc3ad6/README.md) |
| 25&#160;Sep&#160;24&#160;15:16&#160;UTC | SHAKEN 9555 | 25&#160;Sep&#160;25&#160;15:16&#160;UTC | true | [view](CERTS/f7b7228d0701b14410f37040c818167d03df044fe52355c59b91dd49579acbde/README.md) |
| 01&#160;Oct&#160;24&#160;14:51&#160;UTC | SHAKEN 5493 | 01&#160;Oct&#160;25&#160;14:51&#160;UTC | true | [view](CERTS/46eb629ff28f8562a29af3eaab51e1de8c0b11c002ce3a8256a4876657a5d023/README.md) |
| 14&#160;Oct&#160;24&#160;19:57&#160;UTC | SHAKEN 506J | 14&#160;Oct&#160;25&#160;19:57&#160;UTC | true | [view](CERTS/2baa23b5ed8b2eca1c3a82f1e538cc0fa2a65e2255b5e4ce94591663c33c15c5/README.md) |
| 18&#160;Oct&#160;24&#160;14:58&#160;UTC | SHAKEN 819J | 18&#160;Oct&#160;25&#160;14:58&#160;UTC | true | [view](CERTS/b2ac7c7951ec86aa05e82719f8b210c86a1f3e613d5e770bf0c392ff4f80244e/README.md) |
| 22&#160;Oct&#160;24&#160;14:49&#160;UTC | SHAKEN 1049 | 22&#160;Oct&#160;25&#160;14:49&#160;UTC | true | [view](CERTS/250941643bdfe9aee3b97f03e70dc66d219351d3c281dcdce37856dcc2baf526/README.md) |
| 23&#160;Oct&#160;24&#160;18:35&#160;UTC | SHAKEN 7076 | 23&#160;Oct&#160;25&#160;18:35&#160;UTC | true | [view](CERTS/676e7a05a1e718df5fb4c8c6e405d4242cee7d01e91a73d08235751716e1213b/README.md) |
| 28&#160;Oct&#160;24&#160;20:01&#160;UTC | SHAKEN 312K | 28&#160;Oct&#160;25&#160;20:01&#160;UTC | true | [view](CERTS/56687b35ef6ad01cb32a32b40f46951d70d928d517617224190ad282a2a6df35/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 23&#160;Sep&#160;19&#160;13:26&#160;UTC | Neustar Certified Caller ID Root CA | 23&#160;Sep&#160;39&#160;13:26&#160;UTC | false | [view](CERTS/4a77c17cd411cb0ff2984b97687f75ab1db451ac7b717ab81c931351c2d547a1/README.md) |
| 23&#160;Sep&#160;19&#160;13:32&#160;UTC | Neustar Certified Caller ID CA-1 | 23&#160;Sep&#160;29&#160;13:32&#160;UTC | false | [view](CERTS/dade1a52e76c29fc9af1e1221a2a6be02c9899a552d396580855935c9592733b/README.md) |
| 17&#160;Aug&#160;21&#160;17:19&#160;UTC | Neustar Certified Caller ID SHAKEN Root CA | 17&#160;Aug&#160;41&#160;17:19&#160;UTC | false | [view](CERTS/4c728d18b628cc67dda5490e0b4aa8ef4ba679f96d033f34f1680e219e0806c3/README.md) |
| 19&#160;Aug&#160;21&#160;03:25&#160;UTC | Neustar Certified Caller ID SHAKEN CA-1 | 20&#160;Aug&#160;31&#160;03:25&#160;UTC | true | [view](CERTS/b6dc9bf58a55979c78ad569a17c86a7f644721bd3ab2bcf99a27d13636900cf4/README.md) |
| 30&#160;Aug&#160;22&#160;06:39&#160;UTC | Neustar Certified Caller ID SHAKEN CA-2 | 30&#160;Aug&#160;32&#160;06:39&#160;UTC | false | [view](CERTS/3ea530838e9952fdda913a8bd669bf37f88f4ffdb39a34698f34a63915c9e404/README.md) |
| 05&#160;Oct&#160;22&#160;17:26&#160;UTC | Neustar Certified Caller ID SHAKEN CA-2 | 05&#160;Oct&#160;32&#160;17:26&#160;UTC | false | [view](CERTS/0bd95ecbb97c09de0df079ca41e10c360c4b5928ac56c496879a2c90c6bbffe4/README.md) |


Generated: 03 Jun 25 02:15 UTC