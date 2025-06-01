# STIR/SHAKEN CA Ecosystem Compliance

## Neustar

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 253 certificates were included in the corpus being tested
- 119 certificates in the corpus were skipped because they are duplicates
- 14 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 120 certificates being tested against the remaining rules
- 1.02 issues on average found in unexpired, trusted, and non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 364 days is the average remaining validity for the certificates in the corpus
- 365 days is the average initial validity for the certificates in the corpus
- 8 certificates expire in the next 30 days
- 1.01 average number of unexpired certificates per OCN observed
- 119 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 2 | [e_atis_tn_auth_list_spc_format](ISSUES/e_atis_tn_auth_list_spc_format/README.md) | ATIS1000080 |
| 120 | [e_us_cp_subject_sn_shall](ISSUES/e_us_cp_subject_sn_shall/README.md) | US_SHAKEN_CP |

#### CA Certificates

- 3 certificates were included in the corpus being tested
- 0 certificates in the corpus were skipped because they are duplicates
- 0 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 3 certificates being tested against the remaining rules
- 0.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 0.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 100.00% of certificates are too old to be assessed against currently enforced expectations
- 6046 days is the average remaining validity for the certificates in the corpus
- 6088 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days

No error, warning, or notice level issues were found

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 04&#160;Jun&#160;24&#160;15:41&#160;UTC | SHAKEN 2455 | 04&#160;Jun&#160;25&#160;15:41&#160;UTC | true | [view](CERTS/0a2b27236292a4a2a8bd15873a6c7034b3e30a40cb0c3bdb4cae6efe68cc6f13/README.md) |
| 05&#160;Jun&#160;24&#160;13:24&#160;UTC | SHAKEN 955G | 05&#160;Jun&#160;25&#160;13:24&#160;UTC | true | [view](CERTS/d6aed2417609e5bab18e80927228e6c550a2045021fe17766b2f7bf342fb0000/README.md) |
| 12&#160;Jun&#160;24&#160;01:48&#160;UTC | SHAKEN 939H | 12&#160;Jun&#160;25&#160;01:48&#160;UTC | true | [view](CERTS/0ad417bdd791409e4898348037698c654959cea6429dbf2fb0a471f44c48297d/README.md) |
| 18&#160;Jun&#160;24&#160;18:37&#160;UTC | SHAKEN 697J | 18&#160;Jun&#160;25&#160;18:37&#160;UTC | true | [view](CERTS/723f017230bf9cee9e3cc5efe147c369423d24fa072cc380a3f036e0a60d6eec/README.md) |
| 28&#160;Jun&#160;24&#160;14:34&#160;UTC | SHAKEN 074K | 28&#160;Jun&#160;25&#160;14:34&#160;UTC | true | [view](CERTS/da5763a039a62edb0cd90dae36d2a457e0f778a904f439123cc98b83523eff13/README.md) |
| 01&#160;Jul&#160;24&#160;17:05&#160;UTC | SHAKEN 962J | 01&#160;Jul&#160;25&#160;17:05&#160;UTC | true | [view](CERTS/0ba8d7326d25fd1fdcd6c28325ddff0fe1cf610a1a8ec92ef8a8083e3f3cc4ee/README.md) |
| 01&#160;Jul&#160;24&#160;17:19&#160;UTC | SHAKEN 715J | 01&#160;Jul&#160;25&#160;17:19&#160;UTC | true | [view](CERTS/889452e1992267fbff32faea6e899da134b0ddce949cf87a93058d36ec1b48e3/README.md) |
| 01&#160;Jul&#160;24&#160;17:58&#160;UTC | SHAKEN 4036 | 01&#160;Jul&#160;25&#160;17:58&#160;UTC | true | [view](CERTS/0823fce516b339bda1acf5b484481f12fe068273d2760a87647fbcfd93591c6c/README.md) |
| 03&#160;Jul&#160;24&#160;18:07&#160;UTC | SHAKEN 0088 | 03&#160;Jul&#160;25&#160;18:07&#160;UTC | true | [view](CERTS/7fa1b583c052cdf86a274d76e73e9eecc80a5aa6722a23247527b4c2361c72a4/README.md) |
| 08&#160;Jul&#160;24&#160;14:51&#160;UTC | SHAKEN 171K | 08&#160;Jul&#160;25&#160;14:51&#160;UTC | true | [view](CERTS/e1fe072fe133772853ce883665c87635cc3989789b875f9fd19743a16715ec52/README.md) |
| 12&#160;Jul&#160;24&#160;18:11&#160;UTC | SHAKEN 0734 | 12&#160;Jul&#160;25&#160;18:11&#160;UTC | true | [view](CERTS/3694817483d551655d4deb864856f268c35cdd030263b72fb50a1dfc2139e93c/README.md) |
| 12&#160;Jul&#160;24&#160;18:18&#160;UTC | SHAKEN 765J | 12&#160;Jul&#160;25&#160;18:18&#160;UTC | true | [view](CERTS/1ff447ab289519ff3cd7163ec4563e8884cf46e4f3d63f98cbe33512ab55033c/README.md) |
| 16&#160;Jul&#160;24&#160;15:39&#160;UTC | SHAKEN 1401 | 16&#160;Jul&#160;25&#160;15:39&#160;UTC | true | [view](CERTS/ef6e3435322c3ac87988443419392794e063d4ce8c1afaa7d624ceeb6aa101bf/README.md) |
| 16&#160;Jul&#160;24&#160;16:17&#160;UTC | SHAKEN 0523 | 16&#160;Jul&#160;25&#160;16:17&#160;UTC | true | [view](CERTS/5e770904975223443b421b1b375e9ea47a2b5e9754d0d0d0d5d61a9b71ded91a/README.md) |
| 18&#160;Jul&#160;24&#160;21:20&#160;UTC | SHAKEN 558a | 18&#160;Jul&#160;25&#160;21:20&#160;UTC | true | [view](CERTS/6af235e2580e430922580fbdf255be09b24d784d63ddd118d338dd2527a6fa36/README.md) |
| 22&#160;Jul&#160;24&#160;16:07&#160;UTC | SHAKEN 235C | 22&#160;Jul&#160;25&#160;16:07&#160;UTC | true | [view](CERTS/c29c9334a93c4ae5a855a55f1c3e60f71aab7345e41e424180e2df20f8141dc4/README.md) |
| 02&#160;Aug&#160;24&#160;18:32&#160;UTC | SHAKEN 224C | 02&#160;Aug&#160;25&#160;18:32&#160;UTC | true | [view](CERTS/652a6cad05ce2c6d198c7bac5cd00089ea28e468dd9181569aa8c6a0f833e6ac/README.md) |
| 05&#160;Aug&#160;24&#160;15:31&#160;UTC | SHAKEN 653K | 05&#160;Aug&#160;25&#160;15:31&#160;UTC | true | [view](CERTS/cd7ee68b472bc66018e2b8f20c1f7760281442d4dfa38a5c6ac9f51aa6cd764b/README.md) |
| 08&#160;Aug&#160;24&#160;16:33&#160;UTC | SHAKEN 710A | 08&#160;Aug&#160;25&#160;16:33&#160;UTC | true | [view](CERTS/3471bbb6f67e65ef8755acc2b953f95d8f3da877d7ba1f3f43bc16a1581b39e2/README.md) |
| 13&#160;Aug&#160;24&#160;18:14&#160;UTC | SHAKEN 502J | 13&#160;Aug&#160;25&#160;18:14&#160;UTC | true | [view](CERTS/f3830ae70430b0efbc7c0b93170b190e3278692ccf3264c13317e751b13916f0/README.md) |
| 13&#160;Aug&#160;24&#160;18:27&#160;UTC | SHAKEN 707J | 13&#160;Aug&#160;25&#160;18:27&#160;UTC | true | [view](CERTS/577ae45e12b17ae033b2170ee68501297cabbe2c3a3166bafab5a8bf94f177c9/README.md) |
| 13&#160;Aug&#160;24&#160;19:36&#160;UTC | SHAKEN 709J | 13&#160;Aug&#160;25&#160;19:36&#160;UTC | true | [view](CERTS/9c28b0e6a5efb18f42d447ef858709acab4781e1f14468d2aa617483d0da0701/README.md) |
| 13&#160;Aug&#160;24&#160;19:42&#160;UTC | SHAKEN 219K | 13&#160;Aug&#160;25&#160;19:42&#160;UTC | true | [view](CERTS/b57d2f4d6594d1f64557e45b37da28b60c61ebb4119ea6ae406e6b75b0998496/README.md) |
| 20&#160;Aug&#160;24&#160;15:09&#160;UTC | prod SHAKEN 811J | 20&#160;Aug&#160;25&#160;15:09&#160;UTC | true | [view](CERTS/df3342e4029403892dea49e7e2d6833acc34edb37b6816a915749a2cb7d3802d/README.md) |
| 06&#160;Sep&#160;24&#160;17:13&#160;UTC | SHAKEN 5606 | 06&#160;Sep&#160;25&#160;17:13&#160;UTC | true | [view](CERTS/65a65fadb9982a4917eaeb9acf4a2630e216eb56608731d54d9c121ea4bccf5c/README.md) |
| 09&#160;Sep&#160;24&#160;19:39&#160;UTC | SHAKEN 7126 | 09&#160;Sep&#160;25&#160;19:39&#160;UTC | true | [view](CERTS/fcc811243704c597f352e036e72a821672199f0b6f323fc8129625aa40bc3ad6/README.md) |
| 19&#160;Sep&#160;24&#160;14:08&#160;UTC | SHAKEN 7575 | 19&#160;Sep&#160;25&#160;14:08&#160;UTC | true | [view](CERTS/64835c9ed7b4b767d708e235701103ae7ff8fac71356103ad64cac44feb1d924/README.md) |
| 25&#160;Sep&#160;24&#160;15:16&#160;UTC | SHAKEN 9555 | 25&#160;Sep&#160;25&#160;15:16&#160;UTC | true | [view](CERTS/f7b7228d0701b14410f37040c818167d03df044fe52355c59b91dd49579acbde/README.md) |
| 27&#160;Sep&#160;24&#160;15:41&#160;UTC | SHAKEN 745J | 27&#160;Sep&#160;25&#160;15:41&#160;UTC | true | [view](CERTS/4b0bcf3e10b9099b8ca8ac63ef02a9fdbeb489cd2e784e4d2f36e80a1465aae8/README.md) |
| 01&#160;Oct&#160;24&#160;14:51&#160;UTC | SHAKEN 5493 | 01&#160;Oct&#160;25&#160;14:51&#160;UTC | true | [view](CERTS/46eb629ff28f8562a29af3eaab51e1de8c0b11c002ce3a8256a4876657a5d023/README.md) |
| 04&#160;Oct&#160;24&#160;15:08&#160;UTC | SHAKEN 510J | 04&#160;Oct&#160;25&#160;15:08&#160;UTC | true | [view](CERTS/e45b8e15e923f9efefcc4cedd312255b2603ae40b0b822cb392d605a69a1e04c/README.md) |
| 09&#160;Oct&#160;24&#160;17:23&#160;UTC | SHAKEN 403K | 09&#160;Oct&#160;25&#160;17:23&#160;UTC | true | [view](CERTS/0c53d6e5a4e3d1060082293fa154f662f168a3a9a1e2d56af3dde430fd0b1dcf/README.md) |
| 14&#160;Oct&#160;24&#160;19:57&#160;UTC | SHAKEN 506J | 14&#160;Oct&#160;25&#160;19:57&#160;UTC | true | [view](CERTS/2baa23b5ed8b2eca1c3a82f1e538cc0fa2a65e2255b5e4ce94591663c33c15c5/README.md) |
| 18&#160;Oct&#160;24&#160;14:58&#160;UTC | SHAKEN 819J | 18&#160;Oct&#160;25&#160;14:58&#160;UTC | true | [view](CERTS/b2ac7c7951ec86aa05e82719f8b210c86a1f3e613d5e770bf0c392ff4f80244e/README.md) |
| 23&#160;Oct&#160;24&#160;18:35&#160;UTC | SHAKEN 7076 | 23&#160;Oct&#160;25&#160;18:35&#160;UTC | true | [view](CERTS/676e7a05a1e718df5fb4c8c6e405d4242cee7d01e91a73d08235751716e1213b/README.md) |
| 28&#160;Oct&#160;24&#160;20:01&#160;UTC | SHAKEN 312K | 28&#160;Oct&#160;25&#160;20:01&#160;UTC | true | [view](CERTS/56687b35ef6ad01cb32a32b40f46951d70d928d517617224190ad282a2a6df35/README.md) |
| 07&#160;Nov&#160;24&#160;23:36&#160;UTC | SHAKEN 333K | 07&#160;Nov&#160;25&#160;23:36&#160;UTC | true | [view](CERTS/98c983b78992f9813c273ba51be9b536f15ef35bb7802faa3c5ee94b1f892227/README.md) |
| 11&#160;Nov&#160;24&#160;15:36&#160;UTC | SHAKEN 197D | 11&#160;Nov&#160;25&#160;15:36&#160;UTC | true | [view](CERTS/901f295fab41496d34dca054b834a0bedd6515f20b93662c84b71857ae17da89/README.md) |
| 14&#160;Nov&#160;24&#160;13:37&#160;UTC | SHAKEN 689H | 14&#160;Nov&#160;25&#160;13:37&#160;UTC | true | [view](CERTS/03c69bd48fd2da7d5c5537d4355bf9cd67b3bcfc8f7db71cec0eaad8fbbea599/README.md) |
| 14&#160;Nov&#160;24&#160;16:40&#160;UTC | SHAKEN 776J | 14&#160;Nov&#160;25&#160;16:40&#160;UTC | true | [view](CERTS/e7e31c7a1029324fd85bcaf11d07529d6ad9f38223ec0f1d86dea998fb8ccf92/README.md) |
| 20&#160;Nov&#160;24&#160;18:09&#160;UTC | SHAKEN 2473 | 20&#160;Nov&#160;25&#160;18:09&#160;UTC | true | [view](CERTS/18f8657fb2aba86aed243fe73b3b733e5cd893c35f5621bf36978adb9ba3415b/README.md) |
| 22&#160;Nov&#160;24&#160;22:21&#160;UTC | SHAKEN 193E | 22&#160;Nov&#160;25&#160;22:21&#160;UTC | true | [view](CERTS/b116a8f3c1bcaca66ced363b9c4e47c4dadf1a861b16766290eae7e80969c819/README.md) |
| 25&#160;Nov&#160;24&#160;17:40&#160;UTC | SHAKEN 871J | 25&#160;Nov&#160;25&#160;17:40&#160;UTC | true | [view](CERTS/91cae7a14aedec4b72cad34fdc94644ec7309e73221b7e30f9d91c1a22ae2376/README.md) |
| 29&#160;Nov&#160;24&#160;16:31&#160;UTC | SHAKEN 567G | 29&#160;Nov&#160;25&#160;16:31&#160;UTC | true | [view](CERTS/a50541c6f8e3e65430a7f8ad31763eef1084e86ca8d10fa5e1481b9bff0deb46/README.md) |
| 03&#160;Dec&#160;24&#160;16:28&#160;UTC | SHAKEN 899J | 03&#160;Dec&#160;25&#160;16:28&#160;UTC | true | [view](CERTS/ebe3705954b91941085c3e5fa23ef8c0c80603d11b8fa8abe4619b7eef783025/README.md) |
| 03&#160;Dec&#160;24&#160;17:58&#160;UTC | SHAKEN 063E | 03&#160;Dec&#160;25&#160;17:58&#160;UTC | true | [view](CERTS/a5507532a65af8c5d95a9f040af0542ddcdada7e6d018e25748947a3b2b76293/README.md) |
| 09&#160;Dec&#160;24&#160;15:49&#160;UTC | SHAKEN 701J | 09&#160;Dec&#160;25&#160;15:49&#160;UTC | true | [view](CERTS/c24451992a65278429be82aa0713de5da65abfe78e14cb4ab38b9103e01d1323/README.md) |
| 20&#160;Dec&#160;24&#160;15:55&#160;UTC | SHAKEN 791K | 20&#160;Dec&#160;25&#160;15:55&#160;UTC | true | [view](CERTS/ca8b7324a8852a7aa0f7d916aacd5a6cc73125627670cd9657879cb88b3c4334/README.md) |
| 07&#160;Jan&#160;25&#160;16:01&#160;UTC | SHAKEN 750J | 07&#160;Jan&#160;26&#160;16:01&#160;UTC | true | [view](CERTS/67bdafc3fb47ed70621751cdd74261c8fbaa91ec96403993a04f3024fd3f15fc/README.md) |
| 08&#160;Jan&#160;25&#160;15:36&#160;UTC | SHAKEN 5447 | 08&#160;Jan&#160;26&#160;15:36&#160;UTC | true | [view](CERTS/7bb905f3c39ec592bbe45d3ba2ea9062439e3936ecc7c0fa81433d31bcbec621/README.md) |
| 08&#160;Jan&#160;25&#160;21:39&#160;UTC | SHAKEN 418c | 08&#160;Jan&#160;26&#160;21:39&#160;UTC | true | [view](CERTS/7cba7a88ee508d4394523cb770b00f1f3b59865f7561847cab1684b93b3371a3/README.md) |
| 09&#160;Jan&#160;25&#160;15:52&#160;UTC | SHAKEN 546J | 09&#160;Jan&#160;26&#160;15:52&#160;UTC | true | [view](CERTS/458caf8ffa0ec761c0198950176024582ec8de8fcd0d11f7e64ed68209f52ed4/README.md) |
| 09&#160;Jan&#160;25&#160;17:23&#160;UTC | SHAKEN 1591 | 09&#160;Jan&#160;26&#160;17:23&#160;UTC | true | [view](CERTS/328fb43be898d97550bb82a8c8ac9aa1755f5adb2bfa27eaecd77a560f7439b3/README.md) |
| 15&#160;Jan&#160;25&#160;15:01&#160;UTC | SHAKEN 023B | 15&#160;Jan&#160;26&#160;15:01&#160;UTC | true | [view](CERTS/207c0e0ca756ad991397bc0f2fd718746f3d9623e9c49146db0bb77c49bcad3a/README.md) |
| 21&#160;Jan&#160;25&#160;16:38&#160;UTC | SHAKEN 393J | 21&#160;Jan&#160;26&#160;16:38&#160;UTC | true | [view](CERTS/1aed1213527ea155e5e2c5d370de799efed4034babfa6aac76b57793db3722d2/README.md) |
| 21&#160;Jan&#160;25&#160;16:44&#160;UTC | SHAKEN 1563 | 21&#160;Jan&#160;26&#160;16:44&#160;UTC | true | [view](CERTS/41704ad0c1676513b7cea5e226b8bd0af391ce1dbf4217f626db77425c5872a6/README.md) |
| 21&#160;Jan&#160;25&#160;19:01&#160;UTC | SHAKEN 863J | 21&#160;Jan&#160;26&#160;19:01&#160;UTC | true | [view](CERTS/823c82def7fb39ead1a936a2b84464ac0623864bd98327ea767371725e70f745/README.md) |
| 22&#160;Jan&#160;25&#160;17:18&#160;UTC | SHAKEN 023K | 22&#160;Jan&#160;26&#160;17:18&#160;UTC | true | [view](CERTS/ee7a2cec41c5910ed266f890339cfdd4feabfaddb54ff5a60282037a713a04ac/README.md) |
| 27&#160;Jan&#160;25&#160;16:47&#160;UTC | SHAKEN 8833 | 27&#160;Jan&#160;26&#160;16:47&#160;UTC | true | [view](CERTS/4633bd45e5a462aa963acd4b4dbd9e3e31c2b5beb8b5bc65905c3dd1e8c058b6/README.md) |
| 28&#160;Jan&#160;25&#160;17:43&#160;UTC | SHAKEN 766C | 28&#160;Jan&#160;26&#160;17:43&#160;UTC | true | [view](CERTS/4eec51b7890d5526713c39d78e9fe7292963a2bebbb95653b39ec576ad2b5bb1/README.md) |
| 06&#160;Feb&#160;25&#160;19:15&#160;UTC | SHAKEN 1556 | 06&#160;Feb&#160;26&#160;19:15&#160;UTC | true | [view](CERTS/a384dc669d1c4a690352954d333c8a2c274bf70de7cbe209237558229fa60e3d/README.md) |
| 06&#160;Feb&#160;25&#160;19:28&#160;UTC | SHAKEN 951J | 06&#160;Feb&#160;26&#160;19:28&#160;UTC | true | [view](CERTS/0a6026268ea3b4dea7af65f4799f212e22bc90ef25629360e5ddcda2be8f587b/README.md) |
| 06&#160;Feb&#160;25&#160;21:45&#160;UTC | SHAKEN 455J | 06&#160;Feb&#160;26&#160;21:45&#160;UTC | true | [view](CERTS/95872b9acef4832cd023db7479b13ac101cadeceb1936d3c13e565dd8c908417/README.md) |
| 07&#160;Feb&#160;25&#160;12:06&#160;UTC | SHAKEN 005K | 07&#160;Feb&#160;26&#160;12:06&#160;UTC | true | [view](CERTS/02d154047138fa27b5da08b036f95c80ac41d848b2d2d2b5014b6417281a32bb/README.md) |
| 07&#160;Feb&#160;25&#160;18:43&#160;UTC | SHAKEN 782K | 07&#160;Feb&#160;26&#160;18:43&#160;UTC | true | [view](CERTS/5a46dfa572ccc1dc0b9c79ac1b2d884f76f28ca1750b21e58151b68bc7806293/README.md) |
| 09&#160;Feb&#160;25&#160;04:30&#160;UTC | SHAKEN 886G | 09&#160;Feb&#160;26&#160;04:30&#160;UTC | true | [view](CERTS/131cb87d52cb76302cf5fb0c4d05535c1e34cbd2b06c3d346da45b03ed98c4da/README.md) |
| 09&#160;Feb&#160;25&#160;04:57&#160;UTC | SHAKEN 4852 | 09&#160;Feb&#160;26&#160;04:57&#160;UTC | true | [view](CERTS/808ab314efb0b3c7e1415766122c047baaa9ffbf1e5360516755eef9841f8235/README.md) |
| 09&#160;Feb&#160;25&#160;05:36&#160;UTC | SHAKEN 2018 | 09&#160;Feb&#160;26&#160;05:36&#160;UTC | true | [view](CERTS/a6c60cd2c3548c87ca7a33eba5f7917d332ea8050b61dde8b49801144baaa6d3/README.md) |
| 10&#160;Feb&#160;25&#160;15:37&#160;UTC | SHAKEN 128K | 10&#160;Feb&#160;26&#160;15:37&#160;UTC | true | [view](CERTS/9b18ba30c0e566f282b16ba41d9e1f1f3ebac1260a45500caf6fd5ea4b30b17a/README.md) |
| 11&#160;Feb&#160;25&#160;20:15&#160;UTC | SHAKEN 1358 | 11&#160;Feb&#160;26&#160;20:15&#160;UTC | true | [view](CERTS/392d02414a36776f05734693441384da268f9114bd3581bdc0ac2abedbfaa7e0/README.md) |
| 12&#160;Feb&#160;25&#160;16:45&#160;UTC | SHAKEN 280K | 12&#160;Feb&#160;26&#160;16:45&#160;UTC | true | [view](CERTS/ad7df619eb88a964bca6c710d832d527c9c49120ba361bb5bebb92782c474e00/README.md) |
| 13&#160;Feb&#160;25&#160;17:44&#160;UTC | SHAKEN 7661 | 13&#160;Feb&#160;26&#160;17:44&#160;UTC | true | [view](CERTS/73c35497e6ea7537b79976fcbc0ec7adbfa4a3c6af6362a297771e543aff1dc9/README.md) |
| 19&#160;Feb&#160;25&#160;17:11&#160;UTC | SHAKEN 973J | 19&#160;Feb&#160;26&#160;17:11&#160;UTC | true | [view](CERTS/b27dea83b5e71648d6ab7caaa1c603988b48cb6247832e70ea1c8bc3a9dbc53d/README.md) |
| 20&#160;Feb&#160;25&#160;20:28&#160;UTC | SHAKEN 739J | 20&#160;Feb&#160;26&#160;20:28&#160;UTC | true | [view](CERTS/9eb4d58730da3f43711ad563ba64e10ce53ce56b7d9299126daa6dc6849b643b/README.md) |
| 01&#160;Mar&#160;25&#160;05:14&#160;UTC | SHAKEN 150K | 01&#160;Mar&#160;26&#160;05:14&#160;UTC | true | [view](CERTS/4401f23f99dfd3c762fbbb55e142fd33491211dd57121bb5ef198a1e6ab445cb/README.md) |
| 03&#160;Mar&#160;25&#160;17:10&#160;UTC | SHAKEN 030J | 03&#160;Mar&#160;26&#160;17:10&#160;UTC | true | [view](CERTS/7c45e36b6c311b934b70377cdccad16a7683eda7616f28dfe06168f6881627d1/README.md) |
| 04&#160;Mar&#160;25&#160;21:26&#160;UTC | SHAKEN 473G | 04&#160;Mar&#160;26&#160;21:26&#160;UTC | true | [view](CERTS/fc4258372cd83900d4496c5215eb6c04934682a27710c96cb49b0429bceff6ad/README.md) |
| 05&#160;Mar&#160;25&#160;21:39&#160;UTC | SHAKEN 502E | 05&#160;Mar&#160;26&#160;21:39&#160;UTC | true | [view](CERTS/029c0c9856a6c1cfc16ce0cf72850c4350f9c1198785d639dcf49003c8281529/README.md) |
| 11&#160;Mar&#160;25&#160;17:15&#160;UTC | SHAKEN 1558 | 11&#160;Mar&#160;26&#160;17:15&#160;UTC | true | [view](CERTS/d8634d9fddc479095b4f9b096ea5918ffa9d866875d17eee2d9ccef5cf6fe534/README.md) |
| 11&#160;Mar&#160;25&#160;18:45&#160;UTC | SHAKEN 1845 | 11&#160;Mar&#160;26&#160;18:45&#160;UTC | true | [view](CERTS/180851d7e652b405fa7e287e66a69b83fce324d41019262b256b4b3b6b47c658/README.md) |
| 12&#160;Mar&#160;25&#160;15:24&#160;UTC | SHAKEN 704J | 12&#160;Mar&#160;26&#160;15:24&#160;UTC | true | [view](CERTS/1aa887555cfae52822b9d468b91f1ebc0e6c0be152315e7e56e2db33b848d061/README.md) |
| 17&#160;Mar&#160;25&#160;14:20&#160;UTC | SHAKEN 0435 | 17&#160;Mar&#160;26&#160;14:20&#160;UTC | true | [view](CERTS/06a3c966ef51cff73ac461e93a6f4cd59a9f8162e5127bdac426b9c0c794c23e/README.md) |
| 18&#160;Mar&#160;25&#160;15:07&#160;UTC | SHAKEN 692J | 18&#160;Mar&#160;26&#160;15:07&#160;UTC | true | [view](CERTS/b287d3e355fffd342b471484b6773ca7e269d43f529399e92f546988cc3298ed/README.md) |
| 19&#160;Mar&#160;25&#160;15:02&#160;UTC | SHAKEN 4427 | 19&#160;Mar&#160;26&#160;15:02&#160;UTC | true | [view](CERTS/5b57a22ac5c3efe98415d18707220f0d44ee4868ebba03e1136f3742c045d4ef/README.md) |
| 19&#160;Mar&#160;25&#160;15:24&#160;UTC | SHAKEN 845J | 19&#160;Mar&#160;26&#160;15:24&#160;UTC | true | [view](CERTS/1f2ffe1509de8f507f032d54f0970204b1976b4811ac04b174b071fd88a051e4/README.md) |
| 20&#160;Mar&#160;25&#160;14:38&#160;UTC | SHAKEN 821J | 20&#160;Mar&#160;26&#160;14:38&#160;UTC | true | [view](CERTS/2c99179a823c9bf29e205a95002a4ca4dd2ba84725a396bd25894fa83884b61e/README.md) |
| 20&#160;Mar&#160;25&#160;18:02&#160;UTC | SHAKEN 098L | 20&#160;Mar&#160;26&#160;18:02&#160;UTC | true | [view](CERTS/f92145ac745814562286bb9abbd07a756a03848ed4ac867b5e5046d26d9e689f/README.md) |
| 24&#160;Mar&#160;25&#160;14:10&#160;UTC | SHAKEN 854J | 24&#160;Mar&#160;26&#160;14:10&#160;UTC | true | [view](CERTS/4e8a01d24798e681bbf56ed1599fe2a7350153b4346be97e5eadc66ecd9e47e3/README.md) |
| 25&#160;Mar&#160;25&#160;14:53&#160;UTC | SHAKEN 554J | 25&#160;Mar&#160;26&#160;14:53&#160;UTC | true | [view](CERTS/bf3820a67f6ecb886772651117372d2b12e795ab376896781883920b7a607e13/README.md) |
| 27&#160;Mar&#160;25&#160;13:46&#160;UTC | SHAKEN 598J | 27&#160;Mar&#160;26&#160;13:46&#160;UTC | true | [view](CERTS/7deb4d51c491726bbb1c5c157657f5066bb106f7c70b4d277b42f048ed7afc34/README.md) |
| 27&#160;Mar&#160;25&#160;15:30&#160;UTC | SHAKEN 997E | 27&#160;Mar&#160;26&#160;15:30&#160;UTC | true | [view](CERTS/bc23814d7bd109e97a7d85d0368da062294ef5cf7df62bb64308c6ef01005575/README.md) |
| 27&#160;Mar&#160;25&#160;16:30&#160;UTC | SHAKEN 067K | 27&#160;Mar&#160;26&#160;16:30&#160;UTC | true | [view](CERTS/d27e6054035b63b18f9efd3033c988cef78dd6a9382e7954a08a12e116a9516d/README.md) |
| 28&#160;Mar&#160;25&#160;19:41&#160;UTC | SHAKEN 129L | 28&#160;Mar&#160;26&#160;19:41&#160;UTC | true | [view](CERTS/7405217083f58c277a494019c368ddbd2c837b475fb09a56983475ca15c91997/README.md) |
| 16&#160;Apr&#160;25&#160;20:50&#160;UTC | SHAKEN 738J | 16&#160;Apr&#160;26&#160;20:50&#160;UTC | true | [view](CERTS/75198daf3dac0f11d06eb995e42ad2d482052705b82b6d740209c0e248e05345/README.md) |
| 16&#160;Apr&#160;25&#160;23:35&#160;UTC | SHAKEN 465J | 16&#160;Apr&#160;26&#160;23:35&#160;UTC | true | [view](CERTS/47d7df96d7cbef0b6b2f7c3b58a9542f3f832779a98ba1634e621bf72d8f34ce/README.md) |
| 18&#160;Apr&#160;25&#160;16:06&#160;UTC | SHAKEN 534J | 18&#160;Apr&#160;26&#160;16:06&#160;UTC | true | [view](CERTS/b97e50a43f53dec87160fd39f700873094d0e9984da8383890c569028a684c69/README.md) |
| 18&#160;Apr&#160;25&#160;18:42&#160;UTC | SHAKEN 406H | 18&#160;Apr&#160;26&#160;18:42&#160;UTC | true | [view](CERTS/2939af6a71a0db34ea777be312df1e7dbc831d08c6e6124eef52075172ad5571/README.md) |
| 18&#160;Apr&#160;25&#160;18:52&#160;UTC | SHAKEN 178H | 18&#160;Apr&#160;26&#160;18:52&#160;UTC | true | [view](CERTS/3969cf5fb5d64a0cbcb96233461fcebec516f62cf677acaac102d3d44043fa11/README.md) |
| 19&#160;Apr&#160;25&#160;03:25&#160;UTC | SHAKEN 254H | 19&#160;Apr&#160;26&#160;03:25&#160;UTC | true | [view](CERTS/506a835f64337fca490e165c5d086e1bfa87e6a72be75d407edf0d31fc20ffd4/README.md) |
| 24&#160;Apr&#160;25&#160;15:06&#160;UTC | SHAKEN 1442 | 24&#160;Apr&#160;26&#160;15:06&#160;UTC | true | [view](CERTS/6194fc447599a862f82d1f583083dab9f33ea4048c5ffe6f624d132feac7583f/README.md) |
| 24&#160;Apr&#160;25&#160;16:26&#160;UTC | SHAKEN 348K | 24&#160;Apr&#160;26&#160;16:26&#160;UTC | true | [view](CERTS/5a0a9f4a6d949506464695164d05fc1166d55dabe1a07a52aac823b8f75bc1d6/README.md) |
| 24&#160;Apr&#160;25&#160;18:27&#160;UTC | SHAKEN 139K | 24&#160;Apr&#160;26&#160;18:27&#160;UTC | true | [view](CERTS/454c87ce47aff63e10b7528233154a03d4bd0f84f188b0dbbe7ec06d5e13daa8/README.md) |
| 28&#160;Apr&#160;25&#160;15:21&#160;UTC | SHAKEN 402E | 28&#160;Apr&#160;26&#160;15:21&#160;UTC | true | [view](CERTS/8bf7362fd271a221e5890cdf2bab46c8ea36677e49d7922b66be6881e937309b/README.md) |
| 30&#160;Apr&#160;25&#160;16:00&#160;UTC | SHAKEN 4151 | 30&#160;Apr&#160;26&#160;16:00&#160;UTC | true | [view](CERTS/02a26eec879cfc82e33f73bf8c80a72a2d81eeac23d88d0eeaac403ca8c2f325/README.md) |
| 02&#160;May&#160;25&#160;17:12&#160;UTC | SHAKEN 049K | 02&#160;May&#160;26&#160;17:12&#160;UTC | true | [view](CERTS/4aec5c0a9e706b21ca35b1526cbb8b23530a50850b6ec8e5d2f2f3eb442b7216/README.md) |
| 05&#160;May&#160;25&#160;16:31&#160;UTC | SHAKEN 700H | 05&#160;May&#160;26&#160;16:31&#160;UTC | true | [view](CERTS/fb9033486bbda32af78e676b392a853416a17229790d43762f03b6a33d255d57/README.md) |
| 06&#160;May&#160;25&#160;16:17&#160;UTC | SHAKEN 393K | 06&#160;May&#160;26&#160;16:17&#160;UTC | true | [view](CERTS/a47790aa1695dfeeec102a8ddff563bc4137c779051580d28a430c2400f871f3/README.md) |
| 07&#160;May&#160;25&#160;18:23&#160;UTC | SHAKEN 672J | 07&#160;May&#160;26&#160;18:23&#160;UTC | true | [view](CERTS/b80b99d1fde7bfb9413b8ba7b05cee3a09e7c42060770e50a89a66e643c75a46/README.md) |
| 08&#160;May&#160;25&#160;15:46&#160;UTC | SHAKEN 500J | 08&#160;May&#160;26&#160;15:46&#160;UTC | true | [view](CERTS/00b7f841195c0f21ff1521db4d433413e4220f819dd462348dba3f44ddfb516d/README.md) |
| 11&#160;May&#160;25&#160;14:56&#160;UTC | SHAKEN 235K | 11&#160;May&#160;26&#160;14:56&#160;UTC | true | [view](CERTS/097cc3b541a20d92f5de451ab2439829a6ce235b88d0663f545c0a1c901ca7ff/README.md) |
| 12&#160;May&#160;25&#160;17:27&#160;UTC | SHAKEN 697J | 12&#160;May&#160;26&#160;17:27&#160;UTC | true | [view](CERTS/6008ad316fb0147c5a95c500add0c3657cfbf584fba0f5b31e84457d4390cf80/README.md) |
| 12&#160;May&#160;25&#160;18:22&#160;UTC | SHAKEN 8052 | 12&#160;May&#160;26&#160;18:22&#160;UTC | true | [view](CERTS/f238f901a6109acad1e729e80486eefb2d7c7f2d208e3e66d530677bc674f896/README.md) |
| 12&#160;May&#160;25&#160;18:35&#160;UTC | SHAKEN 8468 | 12&#160;May&#160;26&#160;18:35&#160;UTC | true | [view](CERTS/2200a9ee13990b1745335685e87672b07e27c88b1539d5822f5c7aadaeec8073/README.md) |
| 14&#160;May&#160;25&#160;14:49&#160;UTC | SHAKEN 508K | 14&#160;May&#160;26&#160;14:49&#160;UTC | true | [view](CERTS/8a0f4107b9d9b3b8c77b29f9075cb75a9f59bac18ed28d73da27eb2571d3013e/README.md) |
| 15&#160;May&#160;25&#160;15:12&#160;UTC | SHAKEN 537K | 15&#160;May&#160;26&#160;15:12&#160;UTC | true | [view](CERTS/0be0e77741ff4f927a9a759f907bc5c426151db89acd4dd3647e34c9a4016024/README.md) |
| 15&#160;May&#160;25&#160;15:30&#160;UTC | SHAKEN 712J | 15&#160;May&#160;26&#160;15:30&#160;UTC | true | [view](CERTS/d5e5077bdaa505ee4687fbaa630f3ae8eaa4a434fe47cb9f18896ad577446edc/README.md) |
| 16&#160;May&#160;25&#160;17:53&#160;UTC | SHAKEN 669B | 16&#160;May&#160;26&#160;17:53&#160;UTC | true | [view](CERTS/95a59e7cd2a103730411f3dc233675786de22d183a6f777482c297416eee22c8/README.md) |
| 23&#160;May&#160;25&#160;13:42&#160;UTC | SHAKEN 573J | 23&#160;May&#160;26&#160;13:42&#160;UTC | true | [view](CERTS/7635eee5aa87605a7d0cb2d931e8c025d996c71392c388cc98e65fac3752ce7c/README.md) |
| 27&#160;May&#160;25&#160;16:12&#160;UTC | SHAKEN 1060 | 27&#160;May&#160;26&#160;16:12&#160;UTC | true | [view](CERTS/99c4ff96e19bb784f9efc80fdee24497231f7bbaa2a8625cd26abdfe38710ff3/README.md) |
| 28&#160;May&#160;25&#160;16:10&#160;UTC | SHAKEN 773J | 28&#160;May&#160;26&#160;16:10&#160;UTC | true | [view](CERTS/a77e930d36920cb0d719f2dd85ed3cdc6638aec0da7ad8ee62eaca562cd5dc76/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 23&#160;Sep&#160;19&#160;13:26&#160;UTC | Neustar Certified Caller ID Root CA | 23&#160;Sep&#160;39&#160;13:26&#160;UTC | false | [view](CERTS/4a77c17cd411cb0ff2984b97687f75ab1db451ac7b717ab81c931351c2d547a1/README.md) |
| 17&#160;Aug&#160;21&#160;17:19&#160;UTC | Neustar Certified Caller ID SHAKEN Root CA | 17&#160;Aug&#160;41&#160;17:19&#160;UTC | false | [view](CERTS/4c728d18b628cc67dda5490e0b4aa8ef4ba679f96d033f34f1680e219e0806c3/README.md) |
| 05&#160;Oct&#160;22&#160;17:26&#160;UTC | Neustar Certified Caller ID SHAKEN CA-2 | 05&#160;Oct&#160;32&#160;17:26&#160;UTC | false | [view](CERTS/0bd95ecbb97c09de0df079ca41e10c360c4b5928ac56c496879a2c90c6bbffe4/README.md) |


Generated: 01 Jun 25 22:38 UTC