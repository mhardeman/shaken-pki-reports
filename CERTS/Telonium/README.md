# STIR/SHAKEN CA Ecosystem Compliance

## Telonium

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 67 certificates were included in the corpus being tested
- 13 certificates in the corpus were skipped because they are duplicates
- 5 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 49 certificates being tested against the remaining rules
- 1.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 4.08% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 393 days is the average remaining validity for the certificates in the corpus
- 398 days is the average initial validity for the certificates in the corpus
- 5 certificates expire in the next 30 days
- 1.04 average number of unexpired certificates per OCN observed
- 47 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_ext_crl_distribution_struct](ISSUES/e_atis_ext_crl_distribution_struct/README.md) | ATIS1000080 |
| 1 | [e_atis_ext_not_specified](ISSUES/e_atis_ext_not_specified/README.md) | ATIS1000080 |

#### CA Certificates

- 5 certificates were included in the corpus being tested
- 0 certificates in the corpus were skipped because they are duplicates
- 0 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 5 certificates being tested against the remaining rules
- 4.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 60.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 4208 days is the average remaining validity for the certificates in the corpus
- 4309 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_ext_certificate_policies_ca](ISSUES/e_atis_ext_certificate_policies_ca/README.md) | ATIS1000080 |
| 1 | [e_atis_ext_crl_distribution_ca](ISSUES/e_atis_ext_crl_distribution_ca/README.md) | ATIS1000080 |
| 2 | [e_atis_ext_key_usage](ISSUES/e_atis_ext_key_usage/README.md) | ATIS1000080 |
| 1 | [e_atis_subject_c_iso_ca](ISSUES/e_atis_subject_c_iso_ca/README.md) | ATIS1000080 |
| 3 | [e_atis_subject_cn_ca](ISSUES/e_atis_subject_cn_ca/README.md) | ATIS1000080 |
| 2 | [e_atis_subject_cn_root](ISSUES/e_atis_subject_cn_root/README.md) | ATIS1000080 |
| 1 | [e_atis_subject_dn_ca](ISSUES/e_atis_subject_dn_ca/README.md) | ATIS1000080 |
| 1 | [e_shaken_certificate_policies_id_ca](ISSUES/e_shaken_certificate_policies_id_ca/README.md) | US_SHAKEN_CP |

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 10&#160;Jul&#160;23&#160;14:44&#160;UTC | SHAKEN 656K | 28&#160;Jun&#160;25&#160;19:35&#160;UTC | true | [view](CERTS/fd285a02878cd6c995f532bbc9b51b4721f5dd3828aa271194760254eb1cd549/README.md) |
| 27&#160;Feb&#160;24&#160;16:46&#160;UTC | SHAKEN 963J | 27&#160;Feb&#160;26&#160;16:47&#160;UTC | true | [view](CERTS/ceef9f6d88a1efc4c056ecaf0f5d42c5f106fb5fc895c8ccc1f7ea97b6ac1093/README.md) |
| 07&#160;Jun&#160;24&#160;14:15&#160;UTC | SHAKEN 755J | 22&#160;Jun&#160;25&#160;18:33&#160;UTC | false | [view](CERTS/ca7f62e6d23e7902067cff06b5953c060565765abc4311ef938a7f90dff6f488/README.md) |
| 20&#160;Jun&#160;24&#160;19:05&#160;UTC | SHAKEN 633K | 27&#160;Dec&#160;25&#160;16:31&#160;UTC | false | [view](CERTS/5c0d32d70b614b08cec3502a7ef34663daa44eb814894c021def70d56c113d62/README.md) |
| 21&#160;Jun&#160;24&#160;14:36&#160;UTC | SHAKEN 651K | 13&#160;Jul&#160;25&#160;05:57&#160;UTC | false | [view](CERTS/3ef68bc582f759993b4df1aac0bb51f80cd992b659931f51c28ef7271b169dcc/README.md) |
| 26&#160;Jun&#160;24&#160;21:01&#160;UTC | SHAKEN 930K | 26&#160;Jun&#160;25&#160;21:02&#160;UTC | false | [view](CERTS/9cadceccf69a1eb0ad9c47404f506cb771df0ec254c87e9f1c7d66b1cb680eee/README.md) |
| 12&#160;Aug&#160;24&#160;14:42&#160;UTC | SHAKEN 709K | 25&#160;Aug&#160;25&#160;20:59&#160;UTC | false | [view](CERTS/284ede2987dda2f3409b88ce30ee10e32787908a6cfbfb5e8abbaf305b33c7a4/README.md) |
| 12&#160;Aug&#160;24&#160;16:23&#160;UTC | SHAKEN 715K | 11&#160;Sep&#160;26&#160;18:30&#160;UTC | false | [view](CERTS/396ffc900acd18b268a476122bfaae0835afda50c8648220980093051eb2bbfb/README.md) |
| 19&#160;Aug&#160;24&#160;19:38&#160;UTC | SHAKEN 825J | 19&#160;Aug&#160;25&#160;19:39&#160;UTC | false | [view](CERTS/d5921517dd28f881b8a2bf899577fa5ac380577954a14ccdb120b8cd31af87c6/README.md) |
| 20&#160;Aug&#160;24&#160;17:07&#160;UTC | SHAKEN 974K | 20&#160;Aug&#160;25&#160;17:08&#160;UTC | false | [view](CERTS/cc64adfd746943da601c5f1fe4572b2124f6ac35a134d79a0e1df3981d31d518/README.md) |
| 27&#160;Sep&#160;24&#160;18:32&#160;UTC | SHAKEN 025L | 27&#160;Sep&#160;25&#160;18:33&#160;UTC | false | [view](CERTS/8f5f429f932d898d06db9e4c2cdce15ddbef77a6b3a460c26167d161198632e4/README.md) |
| 27&#160;Sep&#160;24&#160;20:14&#160;UTC | SHAKEN 014L | 27&#160;Sep&#160;25&#160;20:15&#160;UTC | false | [view](CERTS/b7e41a971284c3dd451dcf6a9974c99018744ea71ceb86b4dd576a55701aac3b/README.md) |
| 08&#160;Oct&#160;24&#160;20:55&#160;UTC | SHAKEN 037L | 08&#160;Oct&#160;25&#160;20:56&#160;UTC | false | [view](CERTS/4b51cafec85f04fa2df933fbb7d372fc0de2767ae70ee881e58a7e83844ac048/README.md) |
| 12&#160;Oct&#160;24&#160;00:08&#160;UTC | SHAKEN 016L | 12&#160;Oct&#160;25&#160;00:09&#160;UTC | false | [view](CERTS/89a8ebcd6931cc9cbef9496b87e12100c865d92738d91eef202b9c5dfbd37389/README.md) |
| 22&#160;Oct&#160;24&#160;21:06&#160;UTC | SHAKEN 042L | 22&#160;Oct&#160;25&#160;21:07&#160;UTC | false | [view](CERTS/dc9302f0877d1823865a6d356add8656babd54219650130a57bb9cf1eb7eaf78/README.md) |
| 24&#160;Oct&#160;24&#160;19:26&#160;UTC | SHAKEN 161K | 24&#160;Oct&#160;25&#160;19:27&#160;UTC | false | [view](CERTS/400f3284e4959f3f5340073e43c43d521b6b305cf2b1d3774fc182bcd1870653/README.md) |
| 13&#160;Nov&#160;24&#160;02:00&#160;UTC | SHAKEN 018L | 13&#160;Nov&#160;25&#160;02:01&#160;UTC | false | [view](CERTS/b8c98d15da79b182ecf38a430f0bbbfe9b2972f1671c9201163ea6ade4780643/README.md) |
| 17&#160;Dec&#160;24&#160;15:21&#160;UTC | SHAKEN 979K | 17&#160;Dec&#160;25&#160;15:22&#160;UTC | false | [view](CERTS/1a4bbce4d44b3de984f058ce18f11566508d6121e05d9956cee18421ce003fba/README.md) |
| 27&#160;Dec&#160;24&#160;18:01&#160;UTC | SHAKEN 033L | 27&#160;Dec&#160;25&#160;18:02&#160;UTC | false | [view](CERTS/fd08f0121922847730d6c92d0c49e66da96a6276dc9fe70235fecd728c70c661/README.md) |
| 07&#160;Jan&#160;25&#160;18:55&#160;UTC | SHAKEN 830K | 07&#160;Feb&#160;27&#160;17:05&#160;UTC | false | [view](CERTS/a2342336f01f23a09d73c1dfd195bbbc1c5889e50bde8b88dde4f3fedaebf4aa/README.md) |
| 07&#160;Jan&#160;25&#160;19:37&#160;UTC | SHAKEN 785K | 09&#160;Jan&#160;27&#160;14:51&#160;UTC | false | [view](CERTS/17b3fae323f14b2b2a097443ebf81c70f6ac4576456487bb78b90a70178791dd/README.md) |
| 08&#160;Jan&#160;25&#160;20:25&#160;UTC | SHAKEN 520F | 08&#160;Jan&#160;26&#160;20:26&#160;UTC | false | [view](CERTS/057554502eb6a8d0e6dd41a4a51c1e149459d48e646dafa43a961bc4e1eeae24/README.md) |
| 17&#160;Jan&#160;25&#160;20:11&#160;UTC | SHAKEN 442K | 30&#160;Jan&#160;26&#160;20:39&#160;UTC | false | [view](CERTS/369ac949f95655fa481f9ee6b0a78b786ae3939d8c71409cec7761373852d8e5/README.md) |
| 21&#160;Jan&#160;25&#160;20:57&#160;UTC | SHAKEN 772J | 04&#160;Apr&#160;26&#160;19:31&#160;UTC | false | [view](CERTS/701b836f7ac8a52b75b394f23dedf984b6b7ea747f25dcfcf439fbfd3f794b97/README.md) |
| 05&#160;Feb&#160;25&#160;15:42&#160;UTC | SHAKEN 847K | 04&#160;Mar&#160;26&#160;16:13&#160;UTC | false | [view](CERTS/d93fb236210dd6292ca8ac07fce7b55bb857ed234d49cbc2c51e5d20315f23ff/README.md) |
| 19&#160;Feb&#160;25&#160;16:02&#160;UTC | SHAKEN 034L | 07&#160;Oct&#160;25&#160;17:13&#160;UTC | false | [view](CERTS/10d385f563843e1536adb4a1426ac3c1ec323359c2d9ec2475f10ec9901420ca/README.md) |
| 19&#160;Feb&#160;25&#160;16:19&#160;UTC | SHAKEN 037L | 08&#160;Oct&#160;25&#160;20:56&#160;UTC | false | [view](CERTS/2118f6710c44b0249c1cc49d3f81179265f02300455e68ef227215036dd87d91/README.md) |
| 20&#160;Feb&#160;25&#160;16:55&#160;UTC | SHAKEN 014L | 27&#160;Sep&#160;25&#160;20:15&#160;UTC | false | [view](CERTS/62d31253cf6851ade341783eb31b8d6e901e11e100f81795935d22a43a84fe95/README.md) |
| 26&#160;Feb&#160;25&#160;16:30&#160;UTC | SHAKEN 854K | 08&#160;Mar&#160;26&#160;18:12&#160;UTC | false | [view](CERTS/f730cae1df3042f247b301603ef2952b82fd30367107bb654bd4a63e3db0a80b/README.md) |
| 06&#160;Mar&#160;25&#160;14:29&#160;UTC | SHAKEN 141L | 06&#160;Mar&#160;26&#160;14:30&#160;UTC | false | [view](CERTS/65821fb6778ef9d7f382a3da0c2b36a5601ae6757a9a4183d5a31345cbcf013a/README.md) |
| 13&#160;Mar&#160;25&#160;14:39&#160;UTC | SHAKEN 086L | 13&#160;Mar&#160;26&#160;14:40&#160;UTC | false | [view](CERTS/95c0032daa6ee1d27993df8eafab6bc987c645154f78dffe4e7a8c87ab4f2890/README.md) |
| 25&#160;Mar&#160;25&#160;19:17&#160;UTC | SHAKEN 123L | 26&#160;Apr&#160;26&#160;15:52&#160;UTC | false | [view](CERTS/11925bc269c017e724332fcdfa849b2567cb3fab7297b45a068f2399d59e186f/README.md) |
| 26&#160;Mar&#160;25&#160;13:44&#160;UTC | SHAKEN 991K | 26&#160;Mar&#160;26&#160;13:45&#160;UTC | false | [view](CERTS/4068d2696207160d510a5b336ed6605a8f3c3914d252a52653e062d8ac5960ea/README.md) |
| 03&#160;Apr&#160;25&#160;14:06&#160;UTC | SHAKEN 155L | 03&#160;Apr&#160;26&#160;14:07&#160;UTC | false | [view](CERTS/52bbec30845d0ae93203eaef74da92345e1a93ab8612360898d584bb0ec3a7e2/README.md) |
| 03&#160;Apr&#160;25&#160;14:19&#160;UTC | SHAKEN 902K | 30&#160;Apr&#160;26&#160;15:59&#160;UTC | false | [view](CERTS/e60602f293ba4cc681635c88bf749352789afc78685435f2ba359f21c931dde0/README.md) |
| 09&#160;Apr&#160;25&#160;14:19&#160;UTC | SHAKEN 178L | 09&#160;Apr&#160;26&#160;14:20&#160;UTC | false | [view](CERTS/a981746a10456befcebbbf3df6947e5eab1b73c677834cc38f45b740c8f55e65/README.md) |
| 09&#160;Apr&#160;25&#160;21:57&#160;UTC | SHAKEN 183L | 09&#160;Apr&#160;26&#160;21:58&#160;UTC | false | [view](CERTS/a5a2df93855df90fe26952915ee796b387c6cd57f6d7dc43ddc897e36e0e27ac/README.md) |
| 14&#160;Apr&#160;25&#160;18:43&#160;UTC | SHAKEN 187L | 14&#160;Apr&#160;26&#160;18:44&#160;UTC | false | [view](CERTS/830188d20858799960adc239c1a3f0a3f390de70d2538e09f69711226558c20d/README.md) |
| 16&#160;Apr&#160;25&#160;00:57&#160;UTC | SHAKEN 176L | 16&#160;Apr&#160;26&#160;00:58&#160;UTC | false | [view](CERTS/a08ab8764c5ca3920098d0b2722cd84358f834cd70fdd296d3b94d024db58803/README.md) |
| 21&#160;Apr&#160;25&#160;15:37&#160;UTC | SHAKEN 698K | 22&#160;Apr&#160;26&#160;18:39&#160;UTC | false | [view](CERTS/5579504d87539e03d7d19900820655eb5b8baacae7535e7a5038aab8e7ac3f00/README.md) |
| 22&#160;Apr&#160;25&#160;21:08&#160;UTC | SHAKEN 217L | 22&#160;Apr&#160;26&#160;21:09&#160;UTC | false | [view](CERTS/2a1a8ef7043b8c0eee3583d66931f98c07c7e67f9c004c8d7d5de879ffdfa4de/README.md) |
| 24&#160;Apr&#160;25&#160;19:19&#160;UTC | SHAKEN 225L | 24&#160;Apr&#160;26&#160;19:20&#160;UTC | false | [view](CERTS/bbbf4c31ea8d9a39ed62f721427a89fe9d65c1e9098c0760b36b6d2e71063e27/README.md) |
| 25&#160;Apr&#160;25&#160;23:24&#160;UTC | SHAKEN 188L | 25&#160;Apr&#160;26&#160;23:25&#160;UTC | false | [view](CERTS/ab1446b20b09da061e261af001af305701aaaede49a4649643700ecbb235161f/README.md) |
| 28&#160;Apr&#160;25&#160;20:02&#160;UTC | SHAKEN 241L | 28&#160;Apr&#160;26&#160;20:03&#160;UTC | false | [view](CERTS/1c6b3c0f116e04a85ed5d92094eaeb4359297f0ae6c8913a53d20b26bdb5bd37/README.md) |
| 03&#160;May&#160;25&#160;01:27&#160;UTC | SHAKEN 142L | 03&#160;May&#160;27&#160;01:28&#160;UTC | false | [view](CERTS/2093ae4e3a20fe19baffea6cf5b4838cd208525e1226e23ebbbd21b8a393354b/README.md) |
| 12&#160;May&#160;25&#160;23:58&#160;UTC | SHAKEN 144L | 13&#160;Jun&#160;25&#160;23:13&#160;UTC | false | [view](CERTS/90b81e44d6fb304c53fe2141a437c21a26d31bff882cbac9e4db0c3eeaafa42a/README.md) |
| 14&#160;May&#160;25&#160;18:47&#160;UTC | SHAKEN 242L | 14&#160;May&#160;26&#160;18:48&#160;UTC | false | [view](CERTS/4f0e992395004eb24a9c1fd525258ed6097bdd211a51170b0101b8edc8af6737/README.md) |
| 15&#160;May&#160;25&#160;20:02&#160;UTC | SHAKEN 865K | 20&#160;May&#160;26&#160;13:50&#160;UTC | false | [view](CERTS/2c8997d580c5d54a6b52b322329573ea88192c6e8b102534b8573ac2faad76b1/README.md) |
| 27&#160;May&#160;25&#160;17:09&#160;UTC | SHAKEN 223L | 28&#160;Jun&#160;25&#160;23:00&#160;UTC | false | [view](CERTS/b7ff0851db9c25f249965e81a396e28beb6d69c050ee11b130bc79de4655357e/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 08&#160;Mar&#160;23&#160;18:40&#160;UTC | Telonium STI-CA Root1 | 05&#160;Mar&#160;35&#160;18:40&#160;UTC | true | [view](CERTS/96c66865ce5558c2ce3723c0b414538fcacadcd0f3286108fef57dc447f122f9/README.md) |
| 08&#160;Mar&#160;23&#160;18:40&#160;UTC | Telonium STI-CA Root2 | 07&#160;Mar&#160;38&#160;18:40&#160;UTC | true | [view](CERTS/a58b27999411d3d54121d4eadc82aa128be1fef96cda3029b2015677188ea40b/README.md) |
| 09&#160;Mar&#160;23&#160;15:18&#160;UTC | Telonium STI-CA Intermediate CA | 06&#160;Mar&#160;33&#160;15:18&#160;UTC | true | [view](CERTS/7c701216e591c9a3b84550ff46566dd420c7f182eb3cfc5abe5739cdbe271169/README.md) |
| 21&#160;Jul&#160;23&#160;00:49&#160;UTC | Telonium SHAKEN ROOT G1 | 21&#160;Jul&#160;35&#160;00:49&#160;UTC | false | [view](CERTS/37e1a126fc5d84ff59f332b2fe8196205bd0e4f7353be497ad17770d9ca6cea5/README.md) |
| 01&#160;Aug&#160;23&#160;16:36&#160;UTC | Telonium SHAKEN Intermediate G1 | 01&#160;Aug&#160;33&#160;16:36&#160;UTC | false | [view](CERTS/8c0ef8682826bec79a8c64881899f6a5a4a1d52dfebe28ae419c23f85df96ea0/README.md) |


Generated: 01 Jun 25 22:59 UTC