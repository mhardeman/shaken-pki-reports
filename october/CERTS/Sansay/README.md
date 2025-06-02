# STIR/SHAKEN CA Ecosystem Compliance

## Sansay

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 1932 certificates were included in the corpus being tested
- 10 certificates in the corpus were skipped because they are duplicates
- 1835 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 87 certificates being tested against the remaining rules
- 1.67 issues on average found in unexpired, trusted, and non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 309 days is the average remaining validity for the certificates in the corpus
- 311 days is the average initial validity for the certificates in the corpus
- 76 certificates expire in the next 30 days
- 1.19 average number of unexpired certificates per OCN observed
- 73 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 42 | [e_atis_ext_crl_distribution_struct](ISSUES/e_atis_ext_crl_distribution_struct/README.md) | ATIS1000080 |
| 56 | [e_atis_subject_cn_spc](ISSUES/e_atis_subject_cn_spc/README.md) | ATIS1000080 |
| 2 | [e_atis_tn_auth_list_spc_format](ISSUES/e_atis_tn_auth_list_spc_format/README.md) | ATIS1000080 |
| 23 | [e_shaken_certificate_policies_id](ISSUES/e_shaken_certificate_policies_id/README.md) | US_SHAKEN_CP |
| 22 | [e_us_cp_subject_sn_shall](ISSUES/e_us_cp_subject_sn_shall/README.md) | US_SHAKEN_CP |

#### CA Certificates

- 2 certificates were included in the corpus being tested
- 0 certificates in the corpus were skipped because they are duplicates
- 0 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 2 certificates being tested against the remaining rules
- 0.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 0.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 100.00% of certificates are too old to be assessed against currently enforced expectations
- 5136 days is the average remaining validity for the certificates in the corpus
- 4928 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days

No error, warning, or notice level issues were found

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 02&#160;Nov&#160;23&#160;13:49&#160;UTC | SHAKEN Starlinq PBX Inc. 267K | 01&#160;Nov&#160;24&#160;13:49&#160;UTC | true | [view](CERTS/772495eb19f14de884567979521029ea8d0f85712aae22b5dea6ffadb6fd6aaf/README.md) |
| 03&#160;Nov&#160;23&#160;12:06&#160;UTC | SHAKEN Celtic Communications, LLC 836J | 02&#160;Nov&#160;24&#160;12:06&#160;UTC | true | [view](CERTS/0dae343c2561ca3b8f6c28949ee3800d2ca4b5f3fbffcc147407e74272912faf/README.md) |
| 07&#160;Nov&#160;23&#160;15:55&#160;UTC | SHAKEN Carrier One Inc. 705J | 06&#160;Nov&#160;24&#160;15:55&#160;UTC | true | [view](CERTS/89208e1662d350e58c5f5da80982aa62487d1cbf640a574d6d2ce7ebbf17a2fb/README.md) |
| 10&#160;Nov&#160;23&#160;02:10&#160;UTC | SHAKEN Star2Star Communications, LLC 590J | 09&#160;Nov&#160;24&#160;02:10&#160;UTC | true | [view](CERTS/d8197ed17be0c4415c77edbda2946e9c03f29dd67299927e8ecc654794c83951/README.md) |
| 13&#160;Nov&#160;23&#160;16:45&#160;UTC | SHAKEN ComData Solutions 451K | 12&#160;Nov&#160;24&#160;16:45&#160;UTC | true | [view](CERTS/dfe0f154e9a583eef556d6547d9d9d68ad605f05e867c9b8e7707811e2a9ed83/README.md) |
| 14&#160;Nov&#160;23&#160;13:29&#160;UTC | SHAKEN Asia Pacific Network 988J | 13&#160;Nov&#160;24&#160;13:29&#160;UTC | true | [view](CERTS/12b9440a58d22c821e164016a60deccd67ed5036e2244bd1694f39ce326e5811/README.md) |
| 14&#160;Nov&#160;23&#160;13:34&#160;UTC | SHAKEN Current Calls, LLC 746J | 13&#160;Nov&#160;24&#160;13:34&#160;UTC | true | [view](CERTS/a1db34e8f1daf7c5246c10508cf9dd97a3ab166f0ad7304ba124cdd53f199143/README.md) |
| 14&#160;Nov&#160;23&#160;13:36&#160;UTC | SHAKEN Godaddy 463K | 13&#160;Nov&#160;24&#160;13:36&#160;UTC | true | [view](CERTS/cc4ebe2a97d75e8560b603d277ce9e5bfb7a1e8dd5da0628e64e90576d270750/README.md) |
| 14&#160;Nov&#160;23&#160;13:36&#160;UTC | SHAKEN KW Corporation, inc. 206k | 13&#160;Nov&#160;24&#160;13:36&#160;UTC | true | [view](CERTS/b6441dfbf4073cb729806ab15547ac613968b2235ed989b9ae02c05d16aa1807/README.md) |
| 14&#160;Nov&#160;23&#160;13:38&#160;UTC | SHAKEN ONE OWL TELECOM INC 412K | 13&#160;Nov&#160;24&#160;13:38&#160;UTC | true | [view](CERTS/a8a6cbe884baa1d42768251df5233f7ffd0b33886539cf00df0d1b16cc48c3f3/README.md) |
| 14&#160;Nov&#160;23&#160;13:38&#160;UTC | SHAKEN OneStream Networks, LLC 630J | 13&#160;Nov&#160;24&#160;13:38&#160;UTC | true | [view](CERTS/d0a3700b7239c2f2aac6b3bbbac04b98db8bd5a8f725c2ebd1f8aed90126a4e1/README.md) |
| 14&#160;Nov&#160;23&#160;13:43&#160;UTC | SHAKEN Ringfree Communications Inc 317K | 13&#160;Nov&#160;24&#160;13:43&#160;UTC | true | [view](CERTS/066d5e0f2e11207f9a8aab5ae03e7bb3877292af0f325a690ce9cff6a9db42f9/README.md) |
| 14&#160;Nov&#160;23&#160;13:45&#160;UTC | SHAKEN Vumber LLC 225K | 13&#160;Nov&#160;24&#160;13:45&#160;UTC | true | [view](CERTS/4c72b9f5cbad420cbbb77aa0ca320baae202029d469d1953cb7e3b84ea42110d/README.md) |
| 27&#160;Nov&#160;23&#160;16:20&#160;UTC | SHAKEN Rayfield Communications, Inc. 006K | 26&#160;Nov&#160;24&#160;16:20&#160;UTC | true | [view](CERTS/b2ed7ac129b77320b8746043e76d523a27cfa3518f64cdffde32461737dae402/README.md) |
| 27&#160;Nov&#160;23&#160;17:58&#160;UTC | SHAKEN Drop Inc 258K | 26&#160;Nov&#160;24&#160;17:58&#160;UTC | true | [view](CERTS/3e07b9b82a23c5d6100f52a7d4532a6c3577b1a74a4e51850148bd1a44798a0b/README.md) |
| 27&#160;Nov&#160;23&#160;18:04&#160;UTC | SHAKEN MagicJack 324E | 26&#160;Nov&#160;24&#160;18:04&#160;UTC | true | [view](CERTS/09c017d4d76a9d8888d3aa630017a70534b727afdb22a0ad8031c4bf27e92454/README.md) |
| 27&#160;Nov&#160;23&#160;22:11&#160;UTC | SHAKEN Systemverse, LLC. 194K | 26&#160;Nov&#160;24&#160;22:11&#160;UTC | true | [view](CERTS/3c28ba328474fb61e883ba300c87a3881dc0ada933b30dc13f01209444ff5e55/README.md) |
| 06&#160;Dec&#160;23&#160;03:21&#160;UTC | SHAKEN Bulk Solutions, LLC 644J | 05&#160;Dec&#160;24&#160;03:21&#160;UTC | true | [view](CERTS/ab634090acf3c02b7dcd70995171b6522e39c5a72d73fe26e32e99b1acd716d7/README.md) |
| 18&#160;Dec&#160;23&#160;13:02&#160;UTC | SHAKEN Voice SY LLC 521K | 17&#160;Dec&#160;24&#160;13:02&#160;UTC | true | [view](CERTS/17cf3db291a3964a6e7d259ee034a5bf1ff6b0acfc4f2fee863c3984f67d37c2/README.md) |
| 27&#160;Dec&#160;23&#160;21:00&#160;UTC | SHAKEN Broadband Dynamics LLC 583j | 26&#160;Dec&#160;24&#160;21:00&#160;UTC | true | [view](CERTS/02c4ce9cf4dc82e32824fad2a5838b26279caa4b63db74fd1c40dabca7b9251b/README.md) |
| 28&#160;Dec&#160;23&#160;21:49&#160;UTC | SHAKEN California Telecom 319K | 27&#160;Dec&#160;24&#160;21:49&#160;UTC | true | [view](CERTS/28bc7840d450b8a6a1136187440b94d10a75465c409275151cd81f34ada8c490/README.md) |
| 29&#160;Dec&#160;23&#160;18:24&#160;UTC | SHAKEN IP Link Telecom Inc. 902J | 28&#160;Dec&#160;24&#160;18:24&#160;UTC | true | [view](CERTS/1f14385f4abd71de4dd72a9c1fd6699618abc7032794445bc8656c644a4a621d/README.md) |
| 29&#160;Dec&#160;23&#160;18:27&#160;UTC | SHAKEN IP Link Telecom Inc. 902J | 28&#160;Dec&#160;24&#160;18:27&#160;UTC | true | [view](CERTS/0927057b9fc6b184e8be7a88161eb4e88cb7ef138b26bc83d953db5d68f8fcca/README.md) |
| 11&#160;Jan&#160;24&#160;19:30&#160;UTC | SHAKEN Arbeit 816J | 10&#160;Jan&#160;25&#160;19:30&#160;UTC | true | [view](CERTS/655f8cf330bddb83c0b081bc6438e4ba274013772961c17e2417630e1f8eb7f7/README.md) |
| 22&#160;Jan&#160;24&#160;14:33&#160;UTC | SHAKEN Global Net Holdings Inc 306K | 21&#160;Jan&#160;25&#160;14:33&#160;UTC | true | [view](CERTS/df27855ac3adb23e2757af24806db9d4a98f70446fff9606d9a8d4196c66f64e/README.md) |
| 22&#160;Jan&#160;24&#160;14:37&#160;UTC | SHAKEN Global Net Holdings Inc 306K | 21&#160;Jan&#160;25&#160;14:37&#160;UTC | true | [view](CERTS/5b37238808c628f29580dc7b328a570ffa010e1bf0a2a02a6b15e0341dfc7d93/README.md) |
| 23&#160;Jan&#160;24&#160;18:14&#160;UTC | SHAKEN 599J Technology Innovation Lab | 22&#160;Jan&#160;25&#160;18:14&#160;UTC | true | [view](CERTS/1f4f7ee438c7fb0441e8b67a27ee334e35a339112bfb63acb3e8cece2322c1ac/README.md) |
| 25&#160;Jan&#160;24&#160;00:00&#160;UTC | SHAKEN 732K Serius Network | 24&#160;Jan&#160;25&#160;00:00&#160;UTC | true | [view](CERTS/942253ee2461223f4489b0996e387e0a8b43f365cdbc33f791f3542c153c7dde/README.md) |
| 29&#160;Jan&#160;24&#160;13:23&#160;UTC | SHAKEN ACS Technologies 488K | 28&#160;Jan&#160;25&#160;13:23&#160;UTC | true | [view](CERTS/0218a28abeeeb238045a8ddffa3593779dcf82a26f219585c3af62900a27ac51/README.md) |
| 21&#160;Feb&#160;24&#160;13:34&#160;UTC | SHAKEN Watchcomm  0590 | 20&#160;Feb&#160;25&#160;13:34&#160;UTC | true | [view](CERTS/f37c46fe22ca2348db842b6bef04535d9be4d6b413c2282fdca2969d292bcdcd/README.md) |
| 23&#160;Feb&#160;24&#160;16:46&#160;UTC | SHAKEN 781J iNet Communications | 22&#160;Feb&#160;25&#160;16:46&#160;UTC | true | [view](CERTS/e46cb2d0ae92726b11a121cee6fa0726a9dfabc72cfa74b5f7547c79838c503b/README.md) |
| 28&#160;Feb&#160;24&#160;17:13&#160;UTC | SHAKEN 839K Sigma Broadband | 27&#160;Feb&#160;25&#160;17:13&#160;UTC | true | [view](CERTS/d6f9b064110046c7c42acd971a566fb99b97c3740df54afb4b903a39179966b1/README.md) |
| 29&#160;Feb&#160;24&#160;23:52&#160;UTC | SHAKEN Ytel Inc. 703J | 28&#160;Feb&#160;25&#160;23:52&#160;UTC | true | [view](CERTS/118ca5f6b2653c823022d22375f900d88e845681ca442938142a44da593c4bb5/README.md) |
| 18&#160;Mar&#160;24&#160;17:10&#160;UTC | SHAKEN Identidad Advertising Development LLC 617K | 18&#160;Mar&#160;25&#160;17:10&#160;UTC | true | [view](CERTS/2f9861d9339c6094cd1c5acf955e0472ffd5534c329f4b69c90caae6f70d61a3/README.md) |
| 26&#160;Mar&#160;24&#160;13:55&#160;UTC | SHAKEN 597F VoIP Innovations | 26&#160;Mar&#160;25&#160;13:55&#160;UTC | true | [view](CERTS/80f9a4656d0d9e150183b3c4c10c11ef69148ab725647d650dd81be489d897cf/README.md) |
| 26&#160;Mar&#160;24&#160;16:02&#160;UTC | SHAKEN 867K Alpine Valley Consulting LLC | 26&#160;Mar&#160;25&#160;16:02&#160;UTC | true | [view](CERTS/d8e42ff7151f25922813aae6e3e9d214f0157ac39fa1132017259254a6fe40d2/README.md) |
| 26&#160;Mar&#160;24&#160;18:12&#160;UTC | SHAKEN 493K ComTelus Inc.  | 26&#160;Mar&#160;25&#160;18:12&#160;UTC | true | [view](CERTS/af4cf171b2ca99abd62e41f7649ac1e22395fda011d173fdfdbd31891f743971/README.md) |
| 28&#160;Mar&#160;24&#160;10:51&#160;UTC | SHAKEN Global Net Holdings Inc 306K | 28&#160;Mar&#160;25&#160;10:51&#160;UTC | true | [view](CERTS/fab84634747b289457158fa4984de05cadcd77c62855912a90ee98eb672b714f/README.md) |
| 29&#160;Mar&#160;24&#160;17:55&#160;UTC | SHAKEN 597F VoIP Innovations | 29&#160;Mar&#160;25&#160;17:55&#160;UTC | true | [view](CERTS/daa381020f162344a666c69b83e4adff78c7438c494521ce9b084dee47c37f49/README.md) |
| 01&#160;Apr&#160;24&#160;16:18&#160;UTC | SHAKEN 731K ChaseData Corp | 01&#160;Apr&#160;25&#160;16:18&#160;UTC | true | [view](CERTS/5e54f96ef86b3bfa4d20d0d4338366e809bc1cb7dd402fadc718bcecdd20de08/README.md) |
| 02&#160;Apr&#160;24&#160;22:06&#160;UTC | SHAKEN 056K Ascension Technologies | 02&#160;Apr&#160;25&#160;22:06&#160;UTC | true | [view](CERTS/b6dc8e79b26eaaaa7e9a1419681b884b85797c027ade6d4153821f46b18bb924/README.md) |
| 16&#160;Apr&#160;24&#160;00:42&#160;UTC | SHAKEN 525K AU Telecom | 16&#160;Apr&#160;25&#160;00:42&#160;UTC | true | [view](CERTS/694c1778f23e11db0dd3bdc9b48d3c96b62bba793f6883faa7d36776960ddc94/README.md) |
| 16&#160;Apr&#160;24&#160;01:44&#160;UTC | SHAKEN WWT INC dba VoIP Networks 053K | 16&#160;Apr&#160;25&#160;01:44&#160;UTC | true | [view](CERTS/06aa18d1b35b3d8560011f9b40f33801099a772c836ee30cf0c6677d08931cf5/README.md) |
| 16&#160;Apr&#160;24&#160;18:47&#160;UTC | SHAKEN 839J EON Telecom Inc. | 16&#160;Apr&#160;25&#160;18:47&#160;UTC | true | [view](CERTS/e732c0ce34c1ac96d34e6489654b580c6c96a076ff3c082bfd5d18946967c4fb/README.md) |
| 16&#160;Apr&#160;24&#160;20:38&#160;UTC | SHAKEN 894K SIPVOICE, LLC | 16&#160;Apr&#160;25&#160;20:38&#160;UTC | true | [view](CERTS/8f9b473e3a832636d10e3e83d66fc6c2298211e646bc7fa926fdfcc40875a177/README.md) |
| 17&#160;Apr&#160;24&#160;00:18&#160;UTC | SHAKEN 879K COMMUNICATIONS AND TELEPHONE SYSTEMS | 17&#160;Apr&#160;25&#160;00:18&#160;UTC | true | [view](CERTS/4fa5e10f0f209f8ea7352ff6ac522324adeb1ba6c2fc07b9bc0a5fddd586ecbd/README.md) |
| 17&#160;Apr&#160;24&#160;18:03&#160;UTC | SHAKEN 782J AM Communication Labs Inc. | 17&#160;Apr&#160;25&#160;18:03&#160;UTC | true | [view](CERTS/3abea89f7a0c9752a0af294e642070be6c7edd3fcf1f23c239708c1d2f798234/README.md) |
| 23&#160;Apr&#160;24&#160;20:24&#160;UTC | SHAKEN 089K Logista | 23&#160;Apr&#160;25&#160;20:24&#160;UTC | true | [view](CERTS/494eca4dc32b870f9dd3a0de68c1e36cc5dd601645447dcd19e871b74d4ce761/README.md) |
| 23&#160;Apr&#160;24&#160;20:32&#160;UTC | SHAKEN GIP Technology 434K | 23&#160;Apr&#160;25&#160;20:32&#160;UTC | true | [view](CERTS/8b89b7753c70f6c5e7642831b901ae0f37ce3be14e2a9bc4ec4b05646b23b330/README.md) |
| 23&#160;Apr&#160;24&#160;21:28&#160;UTC | SHAKEN 895K 6x6 Termination | 23&#160;Apr&#160;25&#160;21:28&#160;UTC | true | [view](CERTS/bef1d8df3e931bfba5331105c5375726011d60158f2463b25466bfd537ef1243/README.md) |
| 24&#160;Apr&#160;24&#160;05:56&#160;UTC | SHAKEN 492K Telxio Networks | 24&#160;Apr&#160;25&#160;05:56&#160;UTC | true | [view](CERTS/cf2eeaf7f14dcbcfac58ed276f8695116b260ed946dc7be13d5a66c07d2caf83/README.md) |
| 08&#160;May&#160;24&#160;00:00&#160;UTC | SHAKEN Nextiva, Inc 914H | 08&#160;May&#160;25&#160;00:00&#160;UTC | true | [view](CERTS/b1e659bd56d018982cb5db1667f7fdd898a2679f37cd2e75adec0b4fda02df8c/README.md) |
| 08&#160;May&#160;24&#160;16:51&#160;UTC | SHAKEN 267K Starlinq PBX Inc. | 08&#160;May&#160;25&#160;16:51&#160;UTC | true | [view](CERTS/f4180665065d7d42522d2ff11a94fb0b18be7c242bf316f57325219909d93828/README.md) |
| 22&#160;May&#160;24&#160;16:04&#160;UTC | SHAKEN ALD Telecom 780J | 22&#160;May&#160;25&#160;16:04&#160;UTC | true | [view](CERTS/af5a628bdfb896413578e9aae6e50c94fd8fb932a9535775b16af741f70f1708/README.md) |
| 23&#160;May&#160;24&#160;12:05&#160;UTC | SHAKEN Midwest Telecom of America 919A | 23&#160;May&#160;25&#160;12:05&#160;UTC | true | [view](CERTS/ec4710a2981dc9a9be4de30da579880ce1ddbdf830a53a2e790217bf5c13c6d4/README.md) |
| 28&#160;May&#160;24&#160;12:23&#160;UTC | SHAKEN Medtel Communications 994J | 28&#160;May&#160;25&#160;12:23&#160;UTC | true | [view](CERTS/6f77234f6369fa640a847f415b2c58f16044fc86453a2869d5d8f72d6dfd71a6/README.md) |
| 31&#160;May&#160;24&#160;19:33&#160;UTC | SHAKEN 938K Lynktel | 31&#160;May&#160;25&#160;19:33&#160;UTC | true | [view](CERTS/b2aa0de697866f9e9dec031d059f9a3d478ee21f540ff87ebe0a8c429527b220/README.md) |
| 03&#160;Jun&#160;24&#160;14:49&#160;UTC | SHAKEN 932K Alliance Phones | 03&#160;Jun&#160;25&#160;14:49&#160;UTC | true | [view](CERTS/277ded041e5ec5cda4c56eb0061ac4262dad2939b7ff40ce6b76946ed82facdb/README.md) |
| 09&#160;Jun&#160;24&#160;08:04&#160;UTC | SHAKEN 776K ActoinVox | 06&#160;Dec&#160;24&#160;08:04&#160;UTC | true | [view](CERTS/87b5e4ebe2f75f3bb1c8efe86e8a26d08435b5672243786f8a7f96d349694219/README.md) |
| 21&#160;Jun&#160;24&#160;20:19&#160;UTC | SHAKEN Connexum LLC 203K | 21&#160;Jun&#160;25&#160;20:19&#160;UTC | true | [view](CERTS/c405face9873a72f5ec4f1bc395a4124d7cfbf080a704060ebe5e9bf7a07d62d/README.md) |
| 29&#160;Jun&#160;24&#160;00:30&#160;UTC | SHAKEN Bek Communications Cooperative 1604 | 28&#160;Jun&#160;25&#160;00:30&#160;UTC | true | [view](CERTS/17a28f83e865e75a97e9a5a4b777355b93960ccf3b65a1d13e06693a0d03e399/README.md) |
| 01&#160;Jul&#160;24&#160;16:21&#160;UTC | SHAKEN Mercury Access Solutions 634K | 01&#160;Jul&#160;25&#160;16:21&#160;UTC | true | [view](CERTS/70cc27d2e747142c3446b6133993989be4e1ff3fe4d25b137def2745fc173d19/README.md) |
| 10&#160;Jul&#160;24&#160;19:13&#160;UTC | SHAKEN 958K SaveVoip LLC | 10&#160;Jul&#160;25&#160;19:13&#160;UTC | true | [view](CERTS/e78654b5bea29fa67df948244d36aefdad852322d5c375149c5ce147430f2b95/README.md) |
| 19&#160;Jul&#160;24&#160;17:35&#160;UTC | SHAKEN IPBTel 535K | 19&#160;Jul&#160;25&#160;17:35&#160;UTC | true | [view](CERTS/c777a6bdc52c45c7f7f66f40b765c70e167fe34b8cd36fea8bc287b20cb7d80e/README.md) |
| 10&#160;Aug&#160;24&#160;19:01&#160;UTC | SHAKEN 688K Call Hub Inc. | 10&#160;Aug&#160;25&#160;19:01&#160;UTC | true | [view](CERTS/d8fe53673498502aa06d1deb531144cdeac93dba56e9c7094fef9fe192b5b14c/README.md) |
| 13&#160;Aug&#160;24&#160;19:57&#160;UTC | SHAKEN 986K 7G Network, Inc | 09&#160;Feb&#160;25&#160;19:57&#160;UTC | true | [view](CERTS/a72429200b39e65918e1e74562a1040baf0ec10307218baf94ec7b0d718a9ad4/README.md) |
| 19&#160;Aug&#160;24&#160;18:17&#160;UTC | SHAKEN 203K Connexum LLC | 19&#160;Aug&#160;25&#160;18:17&#160;UTC | true | [view](CERTS/901fcdbe4946f6c9f2f338dd125112cf748dec475f4052db54963ef4e3c55d1f/README.md) |
| 22&#160;Aug&#160;24&#160;16:18&#160;UTC | SHAKEN 688K Call Hub Inc. | 22&#160;Aug&#160;25&#160;16:18&#160;UTC | true | [view](CERTS/c9514ae8afe29c81cba005d0e97ddd87c0588caca1e39a20368d4f872619984d/README.md) |
| 22&#160;Aug&#160;24&#160;17:42&#160;UTC | SHAKEN Contactivity Corp. 711K | 22&#160;Aug&#160;25&#160;17:42&#160;UTC | true | [view](CERTS/6f93189ff71fccb600f52ac36ac52ec2d7ff916d7bf9e9d3a8eb8ae6d4c7cd31/README.md) |
| 10&#160;Sep&#160;24&#160;13:47&#160;UTC | SHAKEN 455K Cloud Connect LLC | 08&#160;Jan&#160;25&#160;13:47&#160;UTC | true | [view](CERTS/e74d06224975e1d5c4b1a8a889b81da3ed4a0f9ed46a4a0b1a9179faed5b301e/README.md) |
| 23&#160;Sep&#160;24&#160;06:30&#160;UTC | SHAKEN 249K Primo Dialler LLC | 21&#160;Jan&#160;25&#160;06:30&#160;UTC | true | [view](CERTS/e37c2d2abb454090dc41a8a9b8f15661bde2d9f635106de57ea81bbd74dd3c3b/README.md) |
| 24&#160;Sep&#160;24&#160;17:01&#160;UTC | SHAKEN Sangoma 777G | 24&#160;Sep&#160;25&#160;17:01&#160;UTC | true | [view](CERTS/793541492ac2787c6052d4a9cfb63c7f6aed20d149d3d5e173aa531a5d1bb71b/README.md) |
| 01&#160;Oct&#160;24&#160;15:06&#160;UTC | SHAKEN Kloud 7 LLC 214K | 01&#160;Oct&#160;25&#160;15:06&#160;UTC | true | [view](CERTS/67fe5061b5b9244cdb233b8efd82fffde4a42fc661cce8860b6717318181ca80/README.md) |
| 02&#160;Oct&#160;24&#160;12:22&#160;UTC | SHAKEN Mango Voice LLC 579K | 01&#160;Nov&#160;24&#160;12:22&#160;UTC | true | [view](CERTS/6dabaea104b986a2d1e6159391f3c606811d585af7cbd6f2a07def6d96d35f43/README.md) |
| 02&#160;Oct&#160;24&#160;12:59&#160;UTC | SHAKEN Quality Voice & Data Inc. 548J | 01&#160;Nov&#160;24&#160;12:59&#160;UTC | true | [view](CERTS/16241228497cb74debe19464f431fd839a88abfbf8b2c974af4c8c81eb96e5a0/README.md) |
| 02&#160;Oct&#160;24&#160;15:34&#160;UTC | SHAKEN IDT America, Corp 363A | 01&#160;Nov&#160;24&#160;15:34&#160;UTC | true | [view](CERTS/00ad775b20353d97d9c808158c91c77a01a3529778cdc3dc1394d35a081ef2ad/README.md) |
| 03&#160;Oct&#160;24&#160;01:39&#160;UTC | SHAKEN Greenfly Networks Inc dba Clearfly Communications 210J | 02&#160;Nov&#160;24&#160;01:39&#160;UTC | true | [view](CERTS/075b169220d147430a9eccf048ae9c61dfda08b60b3f9c82ce5c0d539aa6d689/README.md) |
| 03&#160;Oct&#160;24&#160;10:35&#160;UTC | SHAKEN Lightspeed Voice 557F | 02&#160;Nov&#160;24&#160;10:35&#160;UTC | true | [view](CERTS/e394e7ed3c5c36107e36ca6c098ffdf2279ebd277b5c434e0f567c7f8d83a57c/README.md) |
| 03&#160;Oct&#160;24&#160;12:54&#160;UTC | SHAKEN Quality Voice & Data Inc. 548J | 02&#160;Nov&#160;24&#160;12:54&#160;UTC | true | [view](CERTS/89c28ee75f98cfa9876c0f4a1c1d42a06324eecae7d7a1f3a28106c647826abc/README.md) |
| 03&#160;Oct&#160;24&#160;15:29&#160;UTC | SHAKEN IDT America, Corp 363A | 02&#160;Nov&#160;24&#160;15:29&#160;UTC | true | [view](CERTS/e917cf4b97ed045860f4777330983956a9b230286a81f06d8bdd4c56b1a786a2/README.md) |
| 03&#160;Oct&#160;24&#160;18:06&#160;UTC | SHAKEN Zray Technologies Corporation 862J | 02&#160;Nov&#160;24&#160;18:06&#160;UTC | true | [view](CERTS/930b00d582cc83dffb2bdb45b4d9c5f513cb4db7e50947d30289d5f98a68d5f4/README.md) |
| 04&#160;Oct&#160;24&#160;01:34&#160;UTC | SHAKEN Greenfly Networks Inc dba Clearfly Communications 210J | 03&#160;Nov&#160;24&#160;01:34&#160;UTC | true | [view](CERTS/8e9aaa5c0368d9faa5d1c2d91939a5ce7bd9ce1fbf06e69c24b041a8b9ac0628/README.md) |
| 04&#160;Oct&#160;24&#160;12:49&#160;UTC | SHAKEN Quality Voice & Data Inc. 548J | 03&#160;Nov&#160;24&#160;12:49&#160;UTC | true | [view](CERTS/cc39b9af163b9ac535b980a6f90585bff0fa38d55a2dbc5736317455ab960feb/README.md) |
| 19&#160;Nov&#160;24&#160;17:43&#160;UTC | SHAKEN Drop Inc 258K | 19&#160;Nov&#160;25&#160;17:43&#160;UTC | true | [view](CERTS/6c7656a8a3e1ef4913ac75f3e4ce64822394ba9b6aaeab2501d2ed14af683182/README.md) |
| 23&#160;Apr&#160;25&#160;00:00&#160;UTC | SHAKEN 895K | 23&#160;Apr&#160;26&#160;00:00&#160;UTC | true | [view](CERTS/7f9656b8ac82c3a3d571c6314b7b0546d1e34dfe134b5a36f83229bc89455078/README.md) |
| 28&#160;Apr&#160;25&#160;12:06&#160;UTC | SHAKEN 521K | 25&#160;Oct&#160;25&#160;12:06&#160;UTC | true | [view](CERTS/6a8757a6e06800b00d63f0c91e476564b872813595a42196c59d6a4f2b989b0b/README.md) |
| 26&#160;May&#160;25&#160;06:00&#160;UTC | SHAKEN Convoso 758J | 30&#160;Jun&#160;25&#160;06:00&#160;UTC | true | [view](CERTS/02ab6c36d71b7282bd6120b953c088bc9380eda096e8f1983bedb3d4f4ad5675/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 21&#160;Aug&#160;20&#160;01:22&#160;UTC | SHAKEN Sansay Root CA US | 16&#160;Aug&#160;40&#160;01:22&#160;UTC | false | [view](CERTS/8356d251b255f4ac3fd108bb79be4c02dcea2d3b13d138892bdb3a70cbe6a343/README.md) |
| 02&#160;Sep&#160;22&#160;20:53&#160;UTC | SHAKEN Sansay Intermediate CA US WEST 1 | 31&#160;Aug&#160;29&#160;20:53&#160;UTC | false | [view](CERTS/4b1dfdba2b1e4bbffbf900a20f1f6f7befbef0008b963e4922a64469cb97d24b/README.md) |


Generated: 02 Jun 25 03:45 UTC