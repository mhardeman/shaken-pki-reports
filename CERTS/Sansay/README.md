# STIR/SHAKEN CA Ecosystem Compliance

## Sansay

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 642 certificates were included in the corpus being tested
- 4 certificates in the corpus were skipped because they are duplicates
- 434 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 204 certificates being tested against the remaining rules
- 1.70 issues on average found in unexpired, trusted, and non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 130 days is the average remaining validity for the certificates in the corpus
- 130 days is the average initial validity for the certificates in the corpus
- 145 certificates expire in the next 30 days
- 2.29 average number of unexpired certificates per OCN observed
- 89 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 195 | [e_atis_ext_crl_distribution_struct](ISSUES/e_atis_ext_crl_distribution_struct/README.md) | ATIS1000080 |
| 137 | [e_atis_subject_cn_spc](ISSUES/e_atis_subject_cn_spc/README.md) | ATIS1000080 |
| 5 | [e_atis_tn_auth_list_spc_format](ISSUES/e_atis_tn_auth_list_spc_format/README.md) | ATIS1000080 |
| 6 | [e_shaken_certificate_policies_id](ISSUES/e_shaken_certificate_policies_id/README.md) | US_SHAKEN_CP |
| 3 | [e_us_cp_subject_sn_shall](ISSUES/e_us_cp_subject_sn_shall/README.md) | US_SHAKEN_CP |

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
- 5137 days is the average remaining validity for the certificates in the corpus
- 4928 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days

No error, warning, or notice level issues were found

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 03&#160;Jun&#160;24&#160;14:49&#160;UTC | SHAKEN 932K Alliance Phones | 03&#160;Jun&#160;25&#160;14:49&#160;UTC | true | [view](CERTS/277ded041e5ec5cda4c56eb0061ac4262dad2939b7ff40ce6b76946ed82facdb/README.md) |
| 29&#160;Jun&#160;24&#160;00:30&#160;UTC | SHAKEN Bek Communications Cooperative 1604 | 28&#160;Jun&#160;25&#160;00:30&#160;UTC | true | [view](CERTS/17a28f83e865e75a97e9a5a4b777355b93960ccf3b65a1d13e06693a0d03e399/README.md) |
| 19&#160;Jul&#160;24&#160;08:19&#160;UTC | SHAKEN 694K Icon Global Services Ltd | 19&#160;Jul&#160;25&#160;08:19&#160;UTC | true | [view](CERTS/b62da8c8aab66989c29febe4f191638817405c09f829cf50a2a20b04dfb1885c/README.md) |
| 10&#160;Aug&#160;24&#160;19:01&#160;UTC | SHAKEN 688K Call Hub Inc. | 10&#160;Aug&#160;25&#160;19:01&#160;UTC | true | [view](CERTS/d8fe53673498502aa06d1deb531144cdeac93dba56e9c7094fef9fe192b5b14c/README.md) |
| 19&#160;Aug&#160;24&#160;18:17&#160;UTC | SHAKEN 203K Connexum LLC | 19&#160;Aug&#160;25&#160;18:17&#160;UTC | true | [view](CERTS/901fcdbe4946f6c9f2f338dd125112cf748dec475f4052db54963ef4e3c55d1f/README.md) |
| 22&#160;Aug&#160;24&#160;16:18&#160;UTC | SHAKEN 688K Call Hub Inc. | 22&#160;Aug&#160;25&#160;16:18&#160;UTC | true | [view](CERTS/c9514ae8afe29c81cba005d0e97ddd87c0588caca1e39a20368d4f872619984d/README.md) |
| 24&#160;Sep&#160;24&#160;17:01&#160;UTC | SHAKEN Sangoma 777G | 24&#160;Sep&#160;25&#160;17:01&#160;UTC | true | [view](CERTS/793541492ac2787c6052d4a9cfb63c7f6aed20d149d3d5e173aa531a5d1bb71b/README.md) |
| 16&#160;Oct&#160;24&#160;20:57&#160;UTC | SHAKEN ConnectMeVoice 719J | 16&#160;Oct&#160;25&#160;20:57&#160;UTC | true | [view](CERTS/3512246c54e3f46d8e35b50c1f039b8ffbfd0ba069a3d3ce0e456c2fb867d843/README.md) |
| 22&#160;Oct&#160;24&#160;21:26&#160;UTC | SHAKEN 886G RCLEC, INC. | 22&#160;Oct&#160;25&#160;21:26&#160;UTC | true | [view](CERTS/7a2d5a620a393ebf3cb70cd070ebcd1a0bf86e57bff57a1a14f273f21cbd060a/README.md) |
| 25&#160;Oct&#160;24&#160;01:01&#160;UTC | SHAKEN Star2Star Communications, LLC 590J | 25&#160;Oct&#160;25&#160;01:01&#160;UTC | true | [view](CERTS/7e1bdafcc0cab24983fb0624b73a5809cb300e957e65e560a896e0c9178fc005/README.md) |
| 01&#160;Nov&#160;24&#160;22:34&#160;UTC | SHAKEN 052L Call Logistics INC | 01&#160;Nov&#160;25&#160;22:34&#160;UTC | true | [view](CERTS/138957dc3c44ec4d86c7d86669d6427ae04af5753decb8cafb4da515ffe066e8/README.md) |
| 19&#160;Nov&#160;24&#160;19:21&#160;UTC | SHAKEN InPhonex 1821 | 19&#160;Nov&#160;25&#160;19:21&#160;UTC | true | [view](CERTS/ee8b5624c5b63347f756c59989a079e8c2fe2692b5c36e495a88339f544a0726/README.md) |
| 25&#160;Nov&#160;24&#160;00:00&#160;UTC | SHAKEN MagicJack 324E | 25&#160;Nov&#160;25&#160;00:00&#160;UTC | true | [view](CERTS/3330e2b5058f40c15c44b87614cf85b359f523f4394b6b18b1259634eaad557b/README.md) |
| 29&#160;Nov&#160;24&#160;18:10&#160;UTC | SHAKEN VOIP OFFICE.COM LLC 389K | 29&#160;Nov&#160;25&#160;18:10&#160;UTC | true | [view](CERTS/8ef8397b5c8382a7b916906080c1c4902ed8280a3cc7e24b47a4f5545bde2e35/README.md) |
| 03&#160;Dec&#160;24&#160;16:37&#160;UTC | SHAKEN 644J Bulk Solutions, LLC | 03&#160;Dec&#160;25&#160;16:37&#160;UTC | true | [view](CERTS/990a495c31d1f01b0c57ceabce1d7d65392ac71cc19ffe213767b97e7c87bc5a/README.md) |
| 09&#160;Dec&#160;24&#160;14:07&#160;UTC | SHAKEN Dalton Utilities 3139 | 09&#160;Dec&#160;25&#160;14:07&#160;UTC | true | [view](CERTS/a838fce60100ffa0e8d874cf6854aa4a0cead296120d70ddfc0ada1a56f20fce/README.md) |
| 09&#160;Dec&#160;24&#160;18:54&#160;UTC | SHAKEN 696J Telcentris Inc. dba Voxox | 09&#160;Dec&#160;25&#160;18:54&#160;UTC | true | [view](CERTS/4a28cf567357f13f1fd334e66f49b22c31d3627fcf293a3a4455ab69a3b84a41/README.md) |
| 11&#160;Dec&#160;24&#160;21:31&#160;UTC | SHAKEN 899K Snapcom LLC | 11&#160;Dec&#160;25&#160;21:31&#160;UTC | true | [view](CERTS/c582d5a08cda913a0575c57c72ba785758b6db58ea79534bcb2fb3c5a62b10b7/README.md) |
| 18&#160;Dec&#160;24&#160;16:10&#160;UTC | SHAKEN 938K Lynktel | 18&#160;Dec&#160;25&#160;16:10&#160;UTC | true | [view](CERTS/a68c42c17cee40cd16de5665a354e1c64ee5cf9976dfb8928d75b417b89a331c/README.md) |
| 02&#160;Jan&#160;25&#160;18:09&#160;UTC | SHAKEN IP Link Telecom Inc. 902J | 02&#160;Jan&#160;26&#160;18:09&#160;UTC | true | [view](CERTS/caa25b9032d314a7da1a605766aed27f2aa6eaba92a6946bbe166158818f153c/README.md) |
| 02&#160;Jan&#160;25&#160;18:10&#160;UTC | SHAKEN IP Link Telecom Inc. 902J | 02&#160;Jan&#160;26&#160;18:10&#160;UTC | true | [view](CERTS/2ff532f3e54c7f977eacfeaee3e56374a9309bc51eae82adb8d74714ed7920a3/README.md) |
| 10&#160;Jan&#160;25&#160;00:00&#160;UTC | SHAKEN 583J Broadband Dynamics LLC | 10&#160;Jan&#160;26&#160;00:00&#160;UTC | true | [view](CERTS/5d562510c2d4169f277a83e6cd4406b1fab0e66f127942b7010ef73fccbcfa20/README.md) |
| 21&#160;Jan&#160;25&#160;20:12&#160;UTC | SHAKEN 599J Technology Innovation Lab | 21&#160;Jan&#160;26&#160;20:12&#160;UTC | true | [view](CERTS/49b4e630998d608cc95d3ab406123d07049fb3b79e578e00c5ce2da3695b0264/README.md) |
| 30&#160;Jan&#160;25&#160;05:13&#160;UTC | SHAKEN 548J Quality Voice & Data Inc. | 30&#160;Jan&#160;26&#160;05:13&#160;UTC | true | [view](CERTS/4c6acb3b95fb640cc7506b43c3f2a59558f94a8877abc7aac27c1cf783f69136/README.md) |
| 04&#160;Feb&#160;25&#160;17:10&#160;UTC | SHAKEN 0179 Laurel Highland Telephone Company | 04&#160;Feb&#160;26&#160;17:10&#160;UTC | true | [view](CERTS/652c8b8601a400173bc309184b9b5854aabae9cdce55d59fbcfad974560e16fd/README.md) |
| 10&#160;Feb&#160;25&#160;21:26&#160;UTC | SHAKEN Voiply, LLC 987J | 10&#160;Feb&#160;26&#160;21:26&#160;UTC | true | [view](CERTS/6a206075923b62df9310a89fe3a47b96b3311d433f59b64eb6b754e383f654f2/README.md) |
| 17&#160;Feb&#160;25&#160;22:12&#160;UTC | SHAKEN 455K Cloud Connect LLC | 17&#160;Feb&#160;26&#160;22:12&#160;UTC | true | [view](CERTS/7d072fe93e1d51156b2f34220c54c654c088b2ef5d794677cc4b19e31df80fca/README.md) |
| 20&#160;Feb&#160;25&#160;14:08&#160;UTC | SHAKEN 630J | 20&#160;Feb&#160;26&#160;14:08&#160;UTC | true | [view](CERTS/1dfffe62a80f8f065a60feac04563396ad79918bde39446a7755f269e3e9a219/README.md) |
| 20&#160;Feb&#160;25&#160;14:19&#160;UTC | SHAKEN 382G | 20&#160;Feb&#160;26&#160;14:19&#160;UTC | true | [view](CERTS/9b2460ed536c7f61e0f5e0ef205184b7387c899d5be75333c1884bd977458d3f/README.md) |
| 20&#160;Feb&#160;25&#160;14:25&#160;UTC | SHAKEN 996H | 20&#160;Feb&#160;26&#160;14:25&#160;UTC | true | [view](CERTS/71c70550e288b0ee19980130bf0381366089ee356860918b721d32ac6f867b6c/README.md) |
| 20&#160;Feb&#160;25&#160;15:06&#160;UTC | SHAKEN 634K | 01&#160;Jul&#160;25&#160;15:06&#160;UTC | true | [view](CERTS/f4fac0ac1a974b5872cdd725e9c4c175f1c3f44585364704bfc2263ba50cec5d/README.md) |
| 20&#160;Feb&#160;25&#160;16:38&#160;UTC | SHAKEN 649J | 20&#160;Feb&#160;26&#160;16:38&#160;UTC | true | [view](CERTS/6b2f772417f1b30c1d1d58dc0c1354807b669779c7092d98ed8558a3530ddd2b/README.md) |
| 20&#160;Feb&#160;25&#160;17:45&#160;UTC | SHAKEN 0590 | 20&#160;Feb&#160;26&#160;17:45&#160;UTC | true | [view](CERTS/10716df7aab521efe57498238265e990e33364396eb3ea92f0001db408663bc8/README.md) |
| 20&#160;Feb&#160;25&#160;18:11&#160;UTC | SHAKEN 321K | 20&#160;Feb&#160;26&#160;18:11&#160;UTC | true | [view](CERTS/2bf53dd87885645f0c69e6f317a6a2def1a462852070620f69f3e1fecdc6c46b/README.md) |
| 20&#160;Feb&#160;25&#160;18:40&#160;UTC | SHAKEN 056K | 20&#160;Feb&#160;26&#160;18:40&#160;UTC | true | [view](CERTS/9c73e0f3faa6d35048547cd0825f36ca36fe1465d8caf6002caa87725959ffe5/README.md) |
| 20&#160;Feb&#160;25&#160;18:57&#160;UTC | SHAKEN 214K | 20&#160;Feb&#160;26&#160;18:57&#160;UTC | true | [view](CERTS/2a37528a715ff03b8f44cb0045fe25f068d55cfaefb0b698efb4e78591187054/README.md) |
| 20&#160;Feb&#160;25&#160;20:56&#160;UTC | SHAKEN 616K | 20&#160;Feb&#160;26&#160;20:56&#160;UTC | true | [view](CERTS/15189226a8766851977e2f6525936247aa15c3e24b697597a5b8796747c3294e/README.md) |
| 20&#160;Feb&#160;25&#160;21:27&#160;UTC | SHAKEN 089K | 20&#160;Feb&#160;26&#160;21:27&#160;UTC | true | [view](CERTS/0091f8ad0a4eed342e71b0e405e6833568fc3ce003be60e6f1c84f3334a96c49/README.md) |
| 20&#160;Feb&#160;25&#160;21:33&#160;UTC | SHAKEN 388K | 20&#160;Feb&#160;26&#160;21:33&#160;UTC | true | [view](CERTS/a55b6bf425a1d63b687aa0701c1d0b20fcab7a0dac943f30a890dd0b6f712ae8/README.md) |
| 20&#160;Feb&#160;25&#160;23:10&#160;UTC | SHAKEN 324E | 20&#160;Feb&#160;26&#160;23:10&#160;UTC | true | [view](CERTS/481cbd108b2f3ee7133a67ffb8a94ada8019e44041adf86399dc9c407c1184d7/README.md) |
| 21&#160;Feb&#160;25&#160;00:00&#160;UTC | SHAKEN 711K | 21&#160;Feb&#160;26&#160;00:00&#160;UTC | true | [view](CERTS/cb14f5bc9526399cf58787e7c45ea51617bcba6e1b37cc1f61397639436175ac/README.md) |
| 21&#160;Feb&#160;25&#160;03:05&#160;UTC | SHAKEN 816J | 21&#160;Feb&#160;26&#160;03:05&#160;UTC | true | [view](CERTS/049b3b6a21d66af584268ad19aa242a3063dc9fbc2fb15c6124909ea59298aca/README.md) |
| 21&#160;Feb&#160;25&#160;05:02&#160;UTC | SHAKEN 351K | 21&#160;Feb&#160;26&#160;05:02&#160;UTC | true | [view](CERTS/106fe7d3fb2b85fec974a97ee0f09935eaaab4420a1fe245c9d4dd33cb1ddd41/README.md) |
| 21&#160;Feb&#160;25&#160;15:53&#160;UTC | SHAKEN 617K | 21&#160;Feb&#160;26&#160;15:53&#160;UTC | true | [view](CERTS/4b9968ba1d005dca86aa3c609e1b488bb9ce901774800b5214209a60231721c0/README.md) |
| 21&#160;Feb&#160;25&#160;21:53&#160;UTC | SHAKEN 703J | 21&#160;Feb&#160;26&#160;21:53&#160;UTC | true | [view](CERTS/81b4f0a5de78e344ce9d4902d19823d3db676161d1acd6f9f6ee5957edccbf98/README.md) |
| 24&#160;Feb&#160;25&#160;16:08&#160;UTC | SHAKEN 138K | 24&#160;Feb&#160;26&#160;16:08&#160;UTC | true | [view](CERTS/3a7a8f94d8a159c2b46e2f365438a79fbdfe60cbef1bb48b873a5f6b1786fdc0/README.md) |
| 24&#160;Feb&#160;25&#160;19:39&#160;UTC | SHAKEN 914H | 24&#160;Feb&#160;26&#160;19:39&#160;UTC | true | [view](CERTS/3e5b28c818d757aa9d8f852a2fea737a4247b969d0888537c946d957b1155cdd/README.md) |
| 03&#160;Mar&#160;25&#160;19:07&#160;UTC | SHAKEN 463K | 03&#160;Mar&#160;26&#160;19:07&#160;UTC | true | [view](CERTS/d782e2c27053d930002fc479c416f093d72b030dd353d7a201ae2aa6dad44b24/README.md) |
| 11&#160;Mar&#160;25&#160;14:40&#160;UTC | SHAKEN 3395 | 11&#160;Mar&#160;26&#160;14:40&#160;UTC | true | [view](CERTS/455d1615e3784fc903164f755adb4848fd2765c5d5135068605c16ece5e520c0/README.md) |
| 11&#160;Mar&#160;25&#160;19:26&#160;UTC | SHAKEN 940K | 11&#160;Mar&#160;26&#160;19:26&#160;UTC | true | [view](CERTS/c036e5b7c1d90d6ff94ca0f21a23b160a9fec7a692cd2574d7d6405ff7f0cdca/README.md) |
| 19&#160;Mar&#160;25&#160;20:39&#160;UTC | SHAKEN 839K | 19&#160;Mar&#160;26&#160;20:39&#160;UTC | true | [view](CERTS/c5b3f58b85b80e4ced1413f6ba810fb2651fefa5c9d37b8d8223e6bf5836fceb/README.md) |
| 24&#160;Mar&#160;25&#160;15:30&#160;UTC | SHAKEN 776K | 22&#160;Jun&#160;25&#160;15:30&#160;UTC | true | [view](CERTS/e921cf234d5f5d14191b33c7bb17f88d41150069f2575dbd79e91d8adb75a819/README.md) |
| 24&#160;Mar&#160;25&#160;16:05&#160;UTC | SHAKEN 597F | 24&#160;Mar&#160;26&#160;16:05&#160;UTC | true | [view](CERTS/b709567864fac36899b8a9c4a881415415875ab1d1518025a84afa2d7484fbfa/README.md) |
| 25&#160;Mar&#160;25&#160;16:03&#160;UTC | SHAKEN 493K | 25&#160;Mar&#160;26&#160;16:03&#160;UTC | true | [view](CERTS/447046563c983fe2d4f25657254fddb91cc90d01ffea9ea1a297337165c70862/README.md) |
| 26&#160;Mar&#160;25&#160;00:00&#160;UTC | SHAKEN 867K | 26&#160;Mar&#160;26&#160;00:00&#160;UTC | true | [view](CERTS/7c4809e55e37211bd3dad1e32e81bdbc9dbb6302a8394fdffb82c09f9d066151/README.md) |
| 11&#160;Apr&#160;25&#160;22:40&#160;UTC | SHAKEN 782J | 11&#160;Apr&#160;26&#160;22:40&#160;UTC | true | [view](CERTS/6d37eee4260e21189ae1a155ba248faa4b35853675b2b2048158ceb4abe9e369/README.md) |
| 15&#160;Apr&#160;25&#160;00:00&#160;UTC | SHAKEN 525K | 15&#160;Apr&#160;26&#160;00:00&#160;UTC | true | [view](CERTS/ebce41595a52d088bb76fb42451efeadd9867e410c092ec097bcbb1995f28cb8/README.md) |
| 17&#160;Apr&#160;25&#160;21:16&#160;UTC | SHAKEN 195L | 17&#160;Apr&#160;26&#160;21:16&#160;UTC | true | [view](CERTS/6b9dcf2954bdb9406f3924a5d863cc30bb921d697153c3fd790d4193a0561355/README.md) |
| 23&#160;Apr&#160;25&#160;00:00&#160;UTC | SHAKEN 895K | 23&#160;Apr&#160;26&#160;00:00&#160;UTC | true | [view](CERTS/7f9656b8ac82c3a3d571c6314b7b0546d1e34dfe134b5a36f83229bc89455078/README.md) |
| 28&#160;Apr&#160;25&#160;12:06&#160;UTC | SHAKEN 521K | 25&#160;Oct&#160;25&#160;12:06&#160;UTC | true | [view](CERTS/6a8757a6e06800b00d63f0c91e476564b872813595a42196c59d6a4f2b989b0b/README.md) |
| 30&#160;Apr&#160;25&#160;16:58&#160;UTC | SHAKEN 525G | 30&#160;Apr&#160;26&#160;16:58&#160;UTC | true | [view](CERTS/703da4b1d197ef4ec5acad260e76480705ea7b43425dc86a5017e417b544263c/README.md) |
| 03&#160;May&#160;25&#160;03:23&#160;UTC | SHAKEN BareTelecom 864J | 02&#160;Jun&#160;25&#160;03:23&#160;UTC | true | [view](CERTS/113216ef5bbd377ee10ca0a6d937c6d3d3c89deba8aaed4aee75a6e8e92a176b/README.md) |
| 03&#160;May&#160;25&#160;10:25&#160;UTC | SHAKEN IDT America, Corp 363A | 02&#160;Jun&#160;25&#160;10:25&#160;UTC | true | [view](CERTS/e47daffb3b82ded6f2f71d8c0acf69ae4c716bbf8392a8df910e411ba04f0958/README.md) |
| 04&#160;May&#160;25&#160;15:30&#160;UTC | SHAKEN Socket Telecom LLC 554a | 03&#160;Jun&#160;25&#160;15:30&#160;UTC | true | [view](CERTS/b74e9c6a6438de7df8fdf3a7834506dc35167530a4fd32fd276428a37b938d67/README.md) |
| 04&#160;May&#160;25&#160;16:14&#160;UTC | SHAKEN ASIA PACIFIC NETWORK CORPORATION 988J | 03&#160;Jun&#160;25&#160;16:14&#160;UTC | true | [view](CERTS/01dfe0453139d5f9c9b47ae0a2ada17e24dda221d9584b0dd965ce529e68dc40/README.md) |
| 04&#160;May&#160;25&#160;18:47&#160;UTC | SHAKEN Greenfly Networks Inc dba Clearfly Communications 210J | 03&#160;Jun&#160;25&#160;18:47&#160;UTC | true | [view](CERTS/140824fd7eb2136a203b1ddde9aed071b9894afe6ce7a7713b9e5a59ed6321b3/README.md) |
| 05&#160;May&#160;25&#160;03:12&#160;UTC | SHAKEN IPSBS Managed Services LLC 828J | 04&#160;Jun&#160;25&#160;03:12&#160;UTC | true | [view](CERTS/131b74824527cdeea7713821c533ff1e3531841861f665721d59d6f0ede400dd/README.md) |
| 05&#160;May&#160;25&#160;03:13&#160;UTC | SHAKEN BareTelecom 864J | 04&#160;Jun&#160;25&#160;03:13&#160;UTC | true | [view](CERTS/e17c03976072ee971db2c1d83a839df929359d8244ca458f153766faf42bc80a/README.md) |
| 05&#160;May&#160;25&#160;13:17&#160;UTC | SHAKEN DialedIn 731K | 04&#160;Jun&#160;25&#160;13:17&#160;UTC | true | [view](CERTS/7386ae9314d59c208592c16b4e66113a84863e19b1ef35da29ec7ceb7a8250d1/README.md) |
| 05&#160;May&#160;25&#160;16:09&#160;UTC | SHAKEN ASIA PACIFIC NETWORK CORPORATION 988J | 04&#160;Jun&#160;25&#160;16:09&#160;UTC | true | [view](CERTS/3a3a1478ab355caab708311c31a4e044a0d26c35520224f29c865c4fe3638115/README.md) |
| 05&#160;May&#160;25&#160;18:42&#160;UTC | SHAKEN Greenfly Networks Inc dba Clearfly Communications 210J | 04&#160;Jun&#160;25&#160;18:42&#160;UTC | true | [view](CERTS/8f4b824980d78aebca018bf35641b251bac18d0dd1198fd03a013db1b1f7e08f/README.md) |
| 06&#160;May&#160;25&#160;03:08&#160;UTC | SHAKEN BareTelecom 864J | 05&#160;Jun&#160;25&#160;03:08&#160;UTC | true | [view](CERTS/7ee19dbf05b0b82447b807b56ae01c8ba297ad538d2181040f1b89745c484a36/README.md) |
| 06&#160;May&#160;25&#160;13:12&#160;UTC | SHAKEN DialedIn 731K | 05&#160;Jun&#160;25&#160;13:12&#160;UTC | true | [view](CERTS/33983932c84a934203dbe1cc501211af9e9d6941b171890814a1e2bc7cc13449/README.md) |
| 06&#160;May&#160;25&#160;16:04&#160;UTC | SHAKEN ASIA PACIFIC NETWORK CORPORATION 988J | 05&#160;Jun&#160;25&#160;16:04&#160;UTC | true | [view](CERTS/307d3fa711dd88be80d794a30ae3979efb5a555bcbbf49511dbff577f4d50d6d/README.md) |
| 06&#160;May&#160;25&#160;17:38&#160;UTC | SHAKEN Mango Voice LLC 579K | 05&#160;Jun&#160;25&#160;17:38&#160;UTC | true | [view](CERTS/d7f9af95ea9efb4b7c59c63ee65332f8ea18143c19f9366a296f718dfe3ae5ec/README.md) |
| 06&#160;May&#160;25&#160;18:37&#160;UTC | SHAKEN Greenfly Networks Inc dba Clearfly Communications 210J | 05&#160;Jun&#160;25&#160;18:37&#160;UTC | true | [view](CERTS/adef752f15e8f0bf6f4ff033acb1c686007373192ed7c427baf2851249fc8f68/README.md) |
| 07&#160;May&#160;25&#160;00:00&#160;UTC | SHAKEN 986K | 06&#160;Jun&#160;25&#160;00:00&#160;UTC | true | [view](CERTS/0b238c6a9fc052384422bf113683e13e1d926065f7711909a1323b1276d96083/README.md) |
| 07&#160;May&#160;25&#160;03:03&#160;UTC | SHAKEN BareTelecom 864J | 06&#160;Jun&#160;25&#160;03:03&#160;UTC | true | [view](CERTS/4898a3f70f10ee2c757ab6452e09bd4585b7c4de8b8dfb31832f5c8134205a9f/README.md) |
| 07&#160;May&#160;25&#160;10:05&#160;UTC | SHAKEN IDT America, Corp 363A | 06&#160;Jun&#160;25&#160;10:05&#160;UTC | true | [view](CERTS/1baaa0f71dc9795d78a4f2f85efbd03c7e47ae66d5f9f8029f16f104cfd32257/README.md) |
| 07&#160;May&#160;25&#160;13:07&#160;UTC | SHAKEN DialedIn 731K | 06&#160;Jun&#160;25&#160;13:07&#160;UTC | true | [view](CERTS/27ddc7ca50c0a624f7cdd2e9db53e5bd4cd082af726400ff60cb3cad0ecddaf3/README.md) |
| 07&#160;May&#160;25&#160;15:59&#160;UTC | SHAKEN ASIA PACIFIC NETWORK CORPORATION 988J | 06&#160;Jun&#160;25&#160;15:59&#160;UTC | true | [view](CERTS/0a71d8f4c8ee755d0c6db6cc0d3a8eff9373a3f813a7b58b3dcf286ee1547bdc/README.md) |
| 07&#160;May&#160;25&#160;17:33&#160;UTC | SHAKEN Mango Voice LLC 579K | 06&#160;Jun&#160;25&#160;17:33&#160;UTC | true | [view](CERTS/52e4eed75e9e34f6f512e2b896db83b1752765b5e7c92250776ca10e7468a4ba/README.md) |
| 07&#160;May&#160;25&#160;18:32&#160;UTC | SHAKEN Greenfly Networks Inc dba Clearfly Communications 210J | 06&#160;Jun&#160;25&#160;18:32&#160;UTC | true | [view](CERTS/288be422eb24ca0426d35293ce2db1bae6d0c5c727aeb667fe0c610a6e6e2ecc/README.md) |
| 08&#160;May&#160;25&#160;02:58&#160;UTC | SHAKEN BareTelecom 864J | 07&#160;Jun&#160;25&#160;02:58&#160;UTC | true | [view](CERTS/783241f58e12104fea392933404e4a1947025f1d311f3f8e42f40040c713be31/README.md) |
| 08&#160;May&#160;25&#160;10:00&#160;UTC | SHAKEN IDT America, Corp 363A | 07&#160;Jun&#160;25&#160;10:00&#160;UTC | true | [view](CERTS/936700f1882bed0c6fb066e4cc0bfadf617ec78d1940507d39a0aeb4fcaaf559/README.md) |
| 08&#160;May&#160;25&#160;13:02&#160;UTC | SHAKEN DialedIn 731K | 07&#160;Jun&#160;25&#160;13:02&#160;UTC | true | [view](CERTS/4b3ef420854f3bf853017f01b97d705dc207cba1df88da7031e75fe69f7d0377/README.md) |
| 08&#160;May&#160;25&#160;15:54&#160;UTC | SHAKEN ASIA PACIFIC NETWORK CORPORATION 988J | 07&#160;Jun&#160;25&#160;15:54&#160;UTC | true | [view](CERTS/de5fc20d45c0954c1b199df54176fe931bc46d49505e4c6dc4bf3faae8977fea/README.md) |
| 08&#160;May&#160;25&#160;18:27&#160;UTC | SHAKEN Greenfly Networks Inc dba Clearfly Communications 210J | 07&#160;Jun&#160;25&#160;18:27&#160;UTC | true | [view](CERTS/2b12b83a26ee4ef2741f6cf4c8e63d3861ce2b9ee0119afe8bd314d3128e8356/README.md) |
| 09&#160;May&#160;25&#160;02:52&#160;UTC | SHAKEN IPSBS Managed Services LLC 828J | 08&#160;Jun&#160;25&#160;02:52&#160;UTC | true | [view](CERTS/457aea8fc0c3d8e4c7a4115fc94f1ec4ca13ddff84e68170fc3240b9c3e47b4b/README.md) |
| 09&#160;May&#160;25&#160;02:53&#160;UTC | SHAKEN BareTelecom 864J | 08&#160;Jun&#160;25&#160;02:53&#160;UTC | true | [view](CERTS/0b64ced51852047747315cef99c9ba9e55dc0e3bab0f761d2419b5e9ac1f7c51/README.md) |
| 09&#160;May&#160;25&#160;12:57&#160;UTC | SHAKEN DialedIn 731K | 08&#160;Jun&#160;25&#160;12:57&#160;UTC | true | [view](CERTS/c9395a552e8578ef5b38252813c9420ff4f8e411ba593c0bbc31dd4d871f8bf5/README.md) |
| 09&#160;May&#160;25&#160;13:40&#160;UTC | SHAKEN DLS Internet Services 815J | 08&#160;Jun&#160;25&#160;13:40&#160;UTC | true | [view](CERTS/1d8c984b0d3ab44b3d9a54a922fb68275ee344364516cc999be90cae5f4684d1/README.md) |
| 09&#160;May&#160;25&#160;15:49&#160;UTC | SHAKEN ASIA PACIFIC NETWORK CORPORATION 988J | 08&#160;Jun&#160;25&#160;15:49&#160;UTC | true | [view](CERTS/59081020bcd618a5a3c052d1d0d922fe9212f0f46fcd9c2448cc49beea987979/README.md) |
| 09&#160;May&#160;25&#160;18:22&#160;UTC | SHAKEN Greenfly Networks Inc dba Clearfly Communications 210J | 08&#160;Jun&#160;25&#160;18:22&#160;UTC | true | [view](CERTS/757ab1e7373f840adfe62a983bbedd2a1465c52ebb07e5e6a4744c6771bbd2e5/README.md) |
| 10&#160;May&#160;25&#160;02:48&#160;UTC | SHAKEN BareTelecom 864J | 09&#160;Jun&#160;25&#160;02:48&#160;UTC | true | [view](CERTS/b02415368f1af159968bb193562c94dffc9931f20efef92e0d61b252ce80bdbb/README.md) |
| 10&#160;May&#160;25&#160;15:44&#160;UTC | SHAKEN ASIA PACIFIC NETWORK CORPORATION 988J | 09&#160;Jun&#160;25&#160;15:44&#160;UTC | true | [view](CERTS/3bfe2e59748dfb8196641f8ac7774d5c8396a565209567d5aea7c1fc6613de8c/README.md) |
| 10&#160;May&#160;25&#160;18:17&#160;UTC | SHAKEN Greenfly Networks Inc dba Clearfly Communications 210J | 09&#160;Jun&#160;25&#160;18:17&#160;UTC | true | [view](CERTS/8d9b1d48723b13cc55b452eaa4f0221b6a1e23d2ad4a874a29e14b2aafc96851/README.md) |
| 11&#160;May&#160;25&#160;12:47&#160;UTC | SHAKEN DialedIn 731K | 10&#160;Jun&#160;25&#160;12:47&#160;UTC | true | [view](CERTS/3af8ad630c14cb4a09bb063e2790153440cc18ff0f4b27e690d50e6694170916/README.md) |
| 11&#160;May&#160;25&#160;15:39&#160;UTC | SHAKEN ASIA PACIFIC NETWORK CORPORATION 988J | 10&#160;Jun&#160;25&#160;15:39&#160;UTC | true | [view](CERTS/4847a86108c3c94e6f553c93bb96b550fd7baf1401edd953a33329e6d7038038/README.md) |
| 11&#160;May&#160;25&#160;18:12&#160;UTC | SHAKEN Greenfly Networks Inc dba Clearfly Communications 210J | 10&#160;Jun&#160;25&#160;18:12&#160;UTC | true | [view](CERTS/07ffcf23ed1cf20620a6d2d2f8b72335376345da884e14aa03bbffb0fc6a0f93/README.md) |
| 12&#160;May&#160;25&#160;02:38&#160;UTC | SHAKEN BareTelecom 864J | 11&#160;Jun&#160;25&#160;02:38&#160;UTC | true | [view](CERTS/3c9c9eca12676dfb5586cbd62e29c89dcd3b5db54d367e4992cdf65d0e663c88/README.md) |
| 12&#160;May&#160;25&#160;09:40&#160;UTC | SHAKEN IDT America, Corp 363A | 11&#160;Jun&#160;25&#160;09:40&#160;UTC | true | [view](CERTS/64acc442a9de16ae3d475784dfbc3dd9cac1e599a6f7609b4c0731fb82b5291c/README.md) |
| 12&#160;May&#160;25&#160;12:42&#160;UTC | SHAKEN DialedIn 731K | 11&#160;Jun&#160;25&#160;12:42&#160;UTC | true | [view](CERTS/91e6d46142ff65b679fbe3ed1b3d5ec54eb25335972276f7bab9812227a66c1e/README.md) |
| 12&#160;May&#160;25&#160;14:34&#160;UTC | SHAKEN InteractiveTel, LLC 920J | 11&#160;Jun&#160;25&#160;14:34&#160;UTC | true | [view](CERTS/5a0faaffb7ac3a38dbddd78c8fec0079123dfa02bb9faf37d413e09bf4c79069/README.md) |
| 12&#160;May&#160;25&#160;15:34&#160;UTC | SHAKEN ASIA PACIFIC NETWORK CORPORATION 988J | 11&#160;Jun&#160;25&#160;15:34&#160;UTC | true | [view](CERTS/0bc7028ab024a6361faafe794e39272b4b5852016ffae404c4a9703df403a5ee/README.md) |
| 12&#160;May&#160;25&#160;17:08&#160;UTC | SHAKEN Mango Voice LLC 579K | 11&#160;Jun&#160;25&#160;17:08&#160;UTC | true | [view](CERTS/51bc87311386046b7c57ab40f7edd09545ce0f0820ec068ebb8336605b166fe0/README.md) |
| 12&#160;May&#160;25&#160;18:07&#160;UTC | SHAKEN Greenfly Networks Inc dba Clearfly Communications 210J | 11&#160;Jun&#160;25&#160;18:07&#160;UTC | true | [view](CERTS/d6d9ebd0113faee174a6f9651b56d37784078993ce7347ad58bffb144e4bbbd8/README.md) |
| 12&#160;May&#160;25&#160;21:59&#160;UTC | SHAKEN CIMA Telecom, Inc 313K | 11&#160;Jun&#160;25&#160;21:59&#160;UTC | true | [view](CERTS/2ddd0ab377f59cc3b9302df7990a28c0725e2de89069184ac355d078e49f961b/README.md) |
| 13&#160;May&#160;25&#160;02:32&#160;UTC | SHAKEN IPSBS Managed Services LLC 828J | 12&#160;Jun&#160;25&#160;02:32&#160;UTC | true | [view](CERTS/d34ffbd34d904394fc44d008f433f26e14312638bd26548526fe5bc912d76453/README.md) |
| 13&#160;May&#160;25&#160;02:33&#160;UTC | SHAKEN BareTelecom 864J | 12&#160;Jun&#160;25&#160;02:33&#160;UTC | true | [view](CERTS/6dc44ad36d87a22a07825bfc29189f6e059af0fe4d2ec8c67f45c7e6a768c967/README.md) |
| 13&#160;May&#160;25&#160;09:35&#160;UTC | SHAKEN IDT America, Corp 363A | 12&#160;Jun&#160;25&#160;09:35&#160;UTC | true | [view](CERTS/a8b3d0dba6a16de9f3fa6fe6b080eb281155826053894f2437fbc8c146baeb2b/README.md) |
| 13&#160;May&#160;25&#160;12:37&#160;UTC | SHAKEN DialedIn 731K | 12&#160;Jun&#160;25&#160;12:37&#160;UTC | true | [view](CERTS/7011bff1f3932e56416de3e4e6823b352ca90873a98328f7d7d13ebd8b02fd79/README.md) |
| 13&#160;May&#160;25&#160;15:29&#160;UTC | SHAKEN ASIA PACIFIC NETWORK CORPORATION 988J | 12&#160;Jun&#160;25&#160;15:29&#160;UTC | true | [view](CERTS/8967d5f0e2f1a39d28c171f2f37c231c93aab0c550eb140bf058c41707668405/README.md) |
| 13&#160;May&#160;25&#160;15:39&#160;UTC | SHAKEN 563j | 17&#160;Jun&#160;25&#160;15:39&#160;UTC | true | [view](CERTS/6916a6aa706485c232ff6dd68b4f0d4f81d7485a14e0e3a5ec6ef56499a4fbfd/README.md) |
| 13&#160;May&#160;25&#160;15:41&#160;UTC | SHAKEN 5113 | 17&#160;Jun&#160;25&#160;15:41&#160;UTC | true | [view](CERTS/b3d3e4150e4883bed837647bf4fadb82f81b3c489c4989ce5129569eefeb6574/README.md) |
| 13&#160;May&#160;25&#160;15:42&#160;UTC | SHAKEN 683A | 17&#160;Jun&#160;25&#160;15:42&#160;UTC | true | [view](CERTS/6f70fd4a51290b79526b8e3abdec57f22f97315584c65c520534374b68f519bd/README.md) |
| 13&#160;May&#160;25&#160;15:43&#160;UTC | SHAKEN 012J | 17&#160;Jun&#160;25&#160;15:43&#160;UTC | true | [view](CERTS/ff82963bc57794220014bb3051487f3a7b4583c51a5460386a04324ae9110ab0/README.md) |
| 13&#160;May&#160;25&#160;15:45&#160;UTC | SHAKEN 684J | 17&#160;Jun&#160;25&#160;15:45&#160;UTC | true | [view](CERTS/7b7128c682a7774fb34af00206ec0a923634b2ae8759de579a728e7b4af9c983/README.md) |
| 13&#160;May&#160;25&#160;15:46&#160;UTC | SHAKEN 652J | 12&#160;Jun&#160;25&#160;15:46&#160;UTC | true | [view](CERTS/b6c155f04097b4a9fbd2870159429c4bffe7aa2117476a14cf257134737fb9e1/README.md) |
| 13&#160;May&#160;25&#160;15:50&#160;UTC | SHAKEN 633J | 17&#160;Jun&#160;25&#160;15:50&#160;UTC | true | [view](CERTS/e12509734be3aa584820d6a638aa1cbb46c57a2da601ac4918b9449e5d025796/README.md) |
| 13&#160;May&#160;25&#160;15:51&#160;UTC | SHAKEN 020K | 17&#160;Jun&#160;25&#160;15:51&#160;UTC | true | [view](CERTS/49df8a27115252b7dabf9507f0337e75ee3ea7b6f7fcb65a8bc2b309cab7c419/README.md) |
| 13&#160;May&#160;25&#160;15:53&#160;UTC | SHAKEN 187J | 17&#160;Jun&#160;25&#160;15:53&#160;UTC | true | [view](CERTS/f86b701ef1b370bfa8336e2eaed80278d23f0fc2af4f8202cb867f98810901a7/README.md) |
| 13&#160;May&#160;25&#160;15:55&#160;UTC | SHAKEN 596J | 17&#160;Jun&#160;25&#160;15:55&#160;UTC | true | [view](CERTS/18fb591ef19abe8a12cc772a982448422c947f3474891380e940b7f39059a4a0/README.md) |
| 13&#160;May&#160;25&#160;15:58&#160;UTC | SHAKEN 3395 | 17&#160;Jun&#160;25&#160;15:58&#160;UTC | true | [view](CERTS/8d3c435d142cdb03da66c2ca1b36fff65f800ab8a71957b0c5640d77825ac941/README.md) |
| 13&#160;May&#160;25&#160;16:03&#160;UTC | SHAKEN 3849 | 17&#160;Jun&#160;25&#160;16:03&#160;UTC | true | [view](CERTS/be5a9cfb95f79f8e2f0247376ea4d52955354926282781d5af632f0b8357e507/README.md) |
| 13&#160;May&#160;25&#160;17:03&#160;UTC | SHAKEN Mango Voice LLC 579K | 12&#160;Jun&#160;25&#160;17:03&#160;UTC | true | [view](CERTS/75ca3f631d3f4f3e658ec373e53144d5b47bc1c7cfb1005424ad387b98e82de3/README.md) |
| 13&#160;May&#160;25&#160;17:52&#160;UTC | SHAKEN 880K | 13&#160;May&#160;26&#160;17:52&#160;UTC | true | [view](CERTS/8cbe9168b79121bfedbb520a07dfe7e63a6b885e3d284004697853510520a23f/README.md) |
| 14&#160;May&#160;25&#160;02:28&#160;UTC | SHAKEN BareTelecom 864J | 13&#160;Jun&#160;25&#160;02:28&#160;UTC | true | [view](CERTS/24312ab7c5d3f2d75024e2305254914b0ad95d8e7bb49d36895f9a5c8c37c7da/README.md) |
| 14&#160;May&#160;25&#160;09:30&#160;UTC | SHAKEN IDT America, Corp 363A | 13&#160;Jun&#160;25&#160;09:30&#160;UTC | true | [view](CERTS/90dfe8288f95c470b6ea870a07e3609619ff8ca9df163d17a4484c1dcb26a61a/README.md) |
| 14&#160;May&#160;25&#160;12:32&#160;UTC | SHAKEN DialedIn 731K | 13&#160;Jun&#160;25&#160;12:32&#160;UTC | true | [view](CERTS/11006c0ec7aa83d8e9396198103ea4327b9f646d9b5a26c14404f0d686991c8c/README.md) |
| 14&#160;May&#160;25&#160;14:40&#160;UTC | SHAKEN Socket Telecom LLC 554a | 13&#160;Jun&#160;25&#160;14:40&#160;UTC | true | [view](CERTS/ccfdbcfc180c69687b51f8e60de09ba9c045ff814534e650b94a9ed60ab8d5ed/README.md) |
| 14&#160;May&#160;25&#160;15:24&#160;UTC | SHAKEN ASIA PACIFIC NETWORK CORPORATION 988J | 13&#160;Jun&#160;25&#160;15:24&#160;UTC | true | [view](CERTS/a7f6438618bf4d4e1da4a774f29ad848b884e86de9d3420e2af996d6a054e1f5/README.md) |
| 14&#160;May&#160;25&#160;15:50&#160;UTC | SHAKEN Greenfly Networks Inc dba Clearfly Communications 210J | 13&#160;Jun&#160;25&#160;15:50&#160;UTC | true | [view](CERTS/f506581421793f7d0a350ed3b9bcdd726c4e61aedb66c910f02aa983493ba05c/README.md) |
| 15&#160;May&#160;25&#160;02:23&#160;UTC | SHAKEN BareTelecom 864J | 14&#160;Jun&#160;25&#160;02:23&#160;UTC | true | [view](CERTS/13b5ea99b1239b3bbba2144d8df9649309bc706c9df10f6ba34e1c85ffb9d31b/README.md) |
| 15&#160;May&#160;25&#160;09:25&#160;UTC | SHAKEN IDT America, Corp 363A | 14&#160;Jun&#160;25&#160;09:25&#160;UTC | true | [view](CERTS/ec311821ba36c27b26618ddb0d1628f9cfcd4775bba7a1d6d065ad24c524aa9e/README.md) |
| 15&#160;May&#160;25&#160;15:19&#160;UTC | SHAKEN ASIA PACIFIC NETWORK CORPORATION 988J | 14&#160;Jun&#160;25&#160;15:19&#160;UTC | true | [view](CERTS/e9b7c6d97f5a01d4464753ff7ded224d58aa133cefc4cf0614df08acb9543b14/README.md) |
| 15&#160;May&#160;25&#160;15:45&#160;UTC | SHAKEN Greenfly Networks Inc dba Clearfly Communications 210J | 14&#160;Jun&#160;25&#160;15:45&#160;UTC | true | [view](CERTS/cea95118abfbd3370a9dd95581b6be58f2e94539306079e60e49f5160304304e/README.md) |
| 16&#160;May&#160;25&#160;02:18&#160;UTC | SHAKEN BareTelecom 864J | 15&#160;Jun&#160;25&#160;02:18&#160;UTC | true | [view](CERTS/2ff0790dcd4bec01ca793447305f723643e9b6d49ec99cf776fa34589d8f2761/README.md) |
| 16&#160;May&#160;25&#160;07:11&#160;UTC | SHAKEN Zella Technologies LLC 647K | 15&#160;Jun&#160;25&#160;07:11&#160;UTC | true | [view](CERTS/975ddb7d0ea6c2f0c448e8c7350a82f5dd8a8a373e64a44dd0d8ba3aaaa6fee6/README.md) |
| 16&#160;May&#160;25&#160;09:20&#160;UTC | SHAKEN IDT America, Corp 363A | 15&#160;Jun&#160;25&#160;09:20&#160;UTC | true | [view](CERTS/58f54feea32b54fc098305a5311ec8ea4241ddeec2d3a1e5160532ba284ae3d6/README.md) |
| 16&#160;May&#160;25&#160;15:14&#160;UTC | SHAKEN ASIA PACIFIC NETWORK CORPORATION 988J | 15&#160;Jun&#160;25&#160;15:14&#160;UTC | true | [view](CERTS/94f6e8763259ecf93224aa6d303058d5de3dd5761aed66a2312abea2a03eb0ec/README.md) |
| 16&#160;May&#160;25&#160;15:40&#160;UTC | SHAKEN Greenfly Networks Inc dba Clearfly Communications 210J | 15&#160;Jun&#160;25&#160;15:40&#160;UTC | true | [view](CERTS/5108a01239f37873dc50e7a2965ed9cdc63a49fcc9d0ad04cd11569d8b256c2c/README.md) |
| 17&#160;May&#160;25&#160;02:13&#160;UTC | SHAKEN BareTelecom 864J | 16&#160;Jun&#160;25&#160;02:13&#160;UTC | true | [view](CERTS/85337042ac10d15084863cec66c2df5d03628b2919d6961ed0081b05d337c5c4/README.md) |
| 18&#160;May&#160;25&#160;00:30&#160;UTC | SHAKEN Televergence Solutions Inc 779J | 17&#160;Jun&#160;25&#160;00:30&#160;UTC | true | [view](CERTS/761f66b777c9809e70c623a9e7968a4c35c41f6c5554c0ed20e1e7789e1f9311/README.md) |
| 18&#160;May&#160;25&#160;02:08&#160;UTC | SHAKEN BareTelecom 864J | 17&#160;Jun&#160;25&#160;02:08&#160;UTC | true | [view](CERTS/902ca3a6d9f50588d0235138586e3fd68ff395353c23e822a8a59d689f70de68/README.md) |
| 18&#160;May&#160;25&#160;15:30&#160;UTC | SHAKEN Greenfly Networks Inc dba Clearfly Communications 210J | 17&#160;Jun&#160;25&#160;15:30&#160;UTC | true | [view](CERTS/ad9d3c3a6c91468a5f43646072f620787d965a29a572fa95c234c6be59bfc2be/README.md) |
| 18&#160;May&#160;25&#160;16:38&#160;UTC | SHAKEN Mango Voice LLC 579K | 17&#160;Jun&#160;25&#160;16:38&#160;UTC | true | [view](CERTS/5576f30b7ae34ddfe7814c4d36b7113d98edac692fc74452e1494b472fb1172c/README.md) |
| 19&#160;May&#160;25&#160;00:26&#160;UTC | SHAKEN Televergence Solutions Inc 779J | 18&#160;Jun&#160;25&#160;00:26&#160;UTC | true | [view](CERTS/a677cec9212ab31248beec237b76a83215bc911924e4129cc4dc69a045a399c1/README.md) |
| 19&#160;May&#160;25&#160;05:27&#160;UTC | SHAKEN IDT America, Corp 363A | 18&#160;Jun&#160;25&#160;05:27&#160;UTC | true | [view](CERTS/bdf7459ebac885e8c1cb7e35ff4a9ae8be26e649a7c21df4071440cbdeff5470/README.md) |
| 19&#160;May&#160;25&#160;12:07&#160;UTC | SHAKEN DialedIn 731K | 18&#160;Jun&#160;25&#160;12:07&#160;UTC | true | [view](CERTS/b39d1b57bc894d451ae6e3c5164a13c44c7272488f660bb7ef26f9439e075afe/README.md) |
| 19&#160;May&#160;25&#160;14:59&#160;UTC | SHAKEN ASIA PACIFIC NETWORK CORPORATION 988J | 18&#160;Jun&#160;25&#160;14:59&#160;UTC | true | [view](CERTS/9aa6adb235e722707a8185b787bf7ce71657fbad6da28f8872a376c6d783a426/README.md) |
| 19&#160;May&#160;25&#160;15:25&#160;UTC | SHAKEN Greenfly Networks Inc dba Clearfly Communications 210J | 18&#160;Jun&#160;25&#160;15:25&#160;UTC | true | [view](CERTS/09deeec067d6dd0f5958333a44bca9cd78883e6b0bc52874deb2b2862d7e58d3/README.md) |
| 19&#160;May&#160;25&#160;16:33&#160;UTC | SHAKEN Mango Voice LLC 579K | 18&#160;Jun&#160;25&#160;16:33&#160;UTC | true | [view](CERTS/0f6f8a20b5078f7920f6b3741348634f98b3d6d451f5a0105aab4e4a9d9ef35c/README.md) |
| 20&#160;May&#160;25&#160;00:20&#160;UTC | SHAKEN Televergence Solutions Inc 779J | 19&#160;Jun&#160;25&#160;00:20&#160;UTC | true | [view](CERTS/1643126c0833efb8216a51e5d9e3ae28b9de913164c9ffbbc201bcee97ac272a/README.md) |
| 20&#160;May&#160;25&#160;05:22&#160;UTC | SHAKEN IDT America, Corp 363A | 19&#160;Jun&#160;25&#160;05:22&#160;UTC | true | [view](CERTS/9fde826dde8e2eb6fe2aaf2926c1f3c110633f97753b85cf5d061cd481e83ff5/README.md) |
| 20&#160;May&#160;25&#160;12:02&#160;UTC | SHAKEN DialedIn 731K | 19&#160;Jun&#160;25&#160;12:02&#160;UTC | true | [view](CERTS/896fd1f026d7478a58e255cdd960f3ecc847e0be55d22d0b115624d3f673ca66/README.md) |
| 20&#160;May&#160;25&#160;13:54&#160;UTC | SHAKEN InteractiveTel, LLC 920J | 19&#160;Jun&#160;25&#160;13:54&#160;UTC | true | [view](CERTS/e1b1a9ab780bbfdc35135d96d3cd0790187328559baa25fd0a97a7daa3a3251a/README.md) |
| 20&#160;May&#160;25&#160;13:58&#160;UTC | SHAKEN 9451 | 20&#160;May&#160;26&#160;13:58&#160;UTC | true | [view](CERTS/835365b651d1f2c9864e8957217bcd1ebbebef0b9a4f5da2a843709519083b25/README.md) |
| 20&#160;May&#160;25&#160;14:54&#160;UTC | SHAKEN ASIA PACIFIC NETWORK CORPORATION 988J | 19&#160;Jun&#160;25&#160;14:54&#160;UTC | true | [view](CERTS/b8a148ac38a478b08bf08acb66e5f0e70a1d73235ce152e4b711e33afc1a4a89/README.md) |
| 20&#160;May&#160;25&#160;15:20&#160;UTC | SHAKEN Greenfly Networks Inc dba Clearfly Communications 210J | 19&#160;Jun&#160;25&#160;15:20&#160;UTC | true | [view](CERTS/10f97c019c2f6350e593c5574744f6529d202cf94c63d7aae0c0fdf690c0acf3/README.md) |
| 21&#160;May&#160;25&#160;05:17&#160;UTC | SHAKEN IDT America, Corp 363A | 20&#160;Jun&#160;25&#160;05:17&#160;UTC | true | [view](CERTS/07aff0f02f235b38dc73cf082b6f51cb5593424b73c420087d8ca0040145ea82/README.md) |
| 21&#160;May&#160;25&#160;11:57&#160;UTC | SHAKEN DialedIn 731K | 20&#160;Jun&#160;25&#160;11:57&#160;UTC | true | [view](CERTS/5128a9bdcf644581cb20b9dda7a49948b8004bb786140acc4979356bc595913b/README.md) |
| 21&#160;May&#160;25&#160;14:49&#160;UTC | SHAKEN ASIA PACIFIC NETWORK CORPORATION 988J | 20&#160;Jun&#160;25&#160;14:49&#160;UTC | true | [view](CERTS/e77ace212ed3f1ea51d40bcc52f0232f4721a5dfab71a44e29a4002a1f39262d/README.md) |
| 21&#160;May&#160;25&#160;15:15&#160;UTC | SHAKEN Greenfly Networks Inc dba Clearfly Communications 210J | 20&#160;Jun&#160;25&#160;15:15&#160;UTC | true | [view](CERTS/1287f0432e22baf583ee16a87ea6bb2f61bc20bd43b71373defe96d8089793f1/README.md) |
| 21&#160;May&#160;25&#160;16:06&#160;UTC | SHAKEN Lightspeed Voice 557F | 20&#160;Jun&#160;25&#160;16:06&#160;UTC | true | [view](CERTS/b96de92f47b70e83abc414ca701cee4640954cd68436d5fdb8c8c7be054cc80f/README.md) |
| 22&#160;May&#160;25&#160;00:10&#160;UTC | SHAKEN Televergence Solutions Inc 779J | 21&#160;Jun&#160;25&#160;00:10&#160;UTC | true | [view](CERTS/c896e8358e115836478b3df10be3f101996e1c355a3d903bebb8779bfa28890d/README.md) |
| 22&#160;May&#160;25&#160;01:48&#160;UTC | SHAKEN BareTelecom 864J | 21&#160;Jun&#160;25&#160;01:48&#160;UTC | true | [view](CERTS/129867fdad1a7f2e8f186579b76105d14c7c7db9a52c53ffccfbc8dfccb011d0/README.md) |
| 22&#160;May&#160;25&#160;05:12&#160;UTC | SHAKEN IDT America, Corp 363A | 21&#160;Jun&#160;25&#160;05:12&#160;UTC | true | [view](CERTS/5fbe31eb7a73966196a6eb466364a61a81047c94a0f38892118dfac96f62a375/README.md) |
| 22&#160;May&#160;25&#160;11:52&#160;UTC | SHAKEN DialedIn 731K | 21&#160;Jun&#160;25&#160;11:52&#160;UTC | true | [view](CERTS/f60ad6ad7977773d5809756a0d73e0fa219306f96c6acdb54b8207b203ae4d75/README.md) |
| 22&#160;May&#160;25&#160;15:10&#160;UTC | SHAKEN Greenfly Networks Inc dba Clearfly Communications 210J | 21&#160;Jun&#160;25&#160;15:10&#160;UTC | true | [view](CERTS/f8ea47f7a58fc2370b71ace58af17d6dbd126aacf8a2bfc355b8a0e6a660ef91/README.md) |
| 22&#160;May&#160;25&#160;20:10&#160;UTC | SHAKEN 053K | 21&#160;Jun&#160;25&#160;20:10&#160;UTC | true | [view](CERTS/43f559f0cf3afa9ec04cddee021a7c21017e8021c91c5f52193787df85c2b38d/README.md) |
| 23&#160;May&#160;25&#160;00:05&#160;UTC | SHAKEN Televergence Solutions Inc 779J | 22&#160;Jun&#160;25&#160;00:05&#160;UTC | true | [view](CERTS/75dc0d3c0974ead3813568340563f30a5ec84a41ea16554908dd8ab3bde3358e/README.md) |
| 23&#160;May&#160;25&#160;01:43&#160;UTC | SHAKEN BareTelecom 864J | 22&#160;Jun&#160;25&#160;01:43&#160;UTC | true | [view](CERTS/708c85b488e0dc0abcdfc6d2cb1682f87a20c923e34159826ef909eb67750ed0/README.md) |
| 23&#160;May&#160;25&#160;05:07&#160;UTC | SHAKEN IDT America, Corp 363A | 22&#160;Jun&#160;25&#160;05:07&#160;UTC | true | [view](CERTS/66928ab1b5c2f8106ac4cbcff636e8a5453ab66ce055dd4887ebc21325c68661/README.md) |
| 23&#160;May&#160;25&#160;11:47&#160;UTC | SHAKEN DialedIn 731K | 22&#160;Jun&#160;25&#160;11:47&#160;UTC | true | [view](CERTS/f906c4626b09b2076e3d0ae7bcdabf8e099967ed6758841de9bdda6ee848a78e/README.md) |
| 23&#160;May&#160;25&#160;14:54&#160;UTC | SHAKEN 9157 | 22&#160;Jun&#160;25&#160;14:54&#160;UTC | true | [view](CERTS/c0a0555fcf235da8ef7b238bcdeb3cb703148684c8279065a04ac103a7a3f637/README.md) |
| 23&#160;May&#160;25&#160;15:05&#160;UTC | SHAKEN Greenfly Networks Inc dba Clearfly Communications 210J | 22&#160;Jun&#160;25&#160;15:05&#160;UTC | true | [view](CERTS/11f4ee24af001d3531046448a99309e6105b0e151db4397bf271f68b7c8e38ec/README.md) |
| 24&#160;May&#160;25&#160;01:38&#160;UTC | SHAKEN BareTelecom 864J | 23&#160;Jun&#160;25&#160;01:38&#160;UTC | true | [view](CERTS/d4ce5678ece48936e8ca2678a6ccc8829ef74a7ead94e16efe423cac17469b7f/README.md) |
| 26&#160;May&#160;25&#160;01:28&#160;UTC | SHAKEN BareTelecom 864J | 25&#160;Jun&#160;25&#160;01:28&#160;UTC | true | [view](CERTS/14ca2508f869737f531033839f3f2f8a092110813b684d5454b911b6be6fa957/README.md) |
| 26&#160;May&#160;25&#160;06:00&#160;UTC | SHAKEN Convoso 758J | 30&#160;Jun&#160;25&#160;06:00&#160;UTC | true | [view](CERTS/02ab6c36d71b7282bd6120b953c088bc9380eda096e8f1983bedb3d4f4ad5675/README.md) |
| 26&#160;May&#160;25&#160;14:24&#160;UTC | SHAKEN ASIA PACIFIC NETWORK CORPORATION 988J | 25&#160;Jun&#160;25&#160;14:24&#160;UTC | true | [view](CERTS/98f741067c88c1829cefc9e11e986a93652972cb7d7896f2cd92b3ae0356a276/README.md) |
| 26&#160;May&#160;25&#160;14:50&#160;UTC | SHAKEN Greenfly Networks Inc dba Clearfly Communications 210J | 25&#160;Jun&#160;25&#160;14:50&#160;UTC | true | [view](CERTS/dd8cb8b5b6992942a123c624ca065ac180f3cc36b593433ff68e1d4cddeb13fb/README.md) |
| 26&#160;May&#160;25&#160;23:45&#160;UTC | SHAKEN Televergence Solutions Inc 779J | 25&#160;Jun&#160;25&#160;23:45&#160;UTC | true | [view](CERTS/9cafa2da110ee17805106f7fa131da4bb7fa0a4fb3c206ed6f8a8492f066b759/README.md) |
| 27&#160;May&#160;25&#160;01:23&#160;UTC | SHAKEN BareTelecom 864J | 26&#160;Jun&#160;25&#160;01:23&#160;UTC | true | [view](CERTS/ac66f3ac179f48d509737b27baab0c903bb2844c0a8134c515df70f6f11cf231/README.md) |
| 27&#160;May&#160;25&#160;04:47&#160;UTC | SHAKEN IDT America, Corp 363A | 26&#160;Jun&#160;25&#160;04:47&#160;UTC | true | [view](CERTS/9f0e7601bfb70543fba4db15ec33e6668d911fa867122b6702c9f31ef77d74ea/README.md) |
| 27&#160;May&#160;25&#160;11:27&#160;UTC | SHAKEN DialedIn 731K | 26&#160;Jun&#160;25&#160;11:27&#160;UTC | true | [view](CERTS/24d287d6c9861377c8b355c80396980a98c57984b3260c00d1712b783d4cbce7/README.md) |
| 27&#160;May&#160;25&#160;13:19&#160;UTC | SHAKEN InteractiveTel, LLC 920J | 26&#160;Jun&#160;25&#160;13:19&#160;UTC | true | [view](CERTS/4c683a7c841ce043500bff0ebe8d1e442bb7933459ba009652c2a809531dba6f/README.md) |
| 27&#160;May&#160;25&#160;13:35&#160;UTC | SHAKEN Socket Telecom LLC 554a | 26&#160;Jun&#160;25&#160;13:35&#160;UTC | true | [view](CERTS/d22f1b82019451def20ebd923734fafdee06f43b541b995875bf24db610365c6/README.md) |
| 27&#160;May&#160;25&#160;14:19&#160;UTC | SHAKEN ASIA PACIFIC NETWORK CORPORATION 988J | 26&#160;Jun&#160;25&#160;14:19&#160;UTC | true | [view](CERTS/d6b4624fdf6624c8e13f4347be164b02ccba1695589f20db2b1b0b58acad9fcf/README.md) |
| 27&#160;May&#160;25&#160;15:53&#160;UTC | SHAKEN Mango Voice LLC 579K | 26&#160;Jun&#160;25&#160;15:53&#160;UTC | true | [view](CERTS/4974b83bc0ab51a7e0a345a9a689d87a53516c3426b4ebc79d20862fb69f0a71/README.md) |
| 27&#160;May&#160;25&#160;23:40&#160;UTC | SHAKEN Televergence Solutions Inc 779J | 26&#160;Jun&#160;25&#160;23:40&#160;UTC | true | [view](CERTS/d8fa5c559b91149ddbc7948ea1aecbd14537285ca3060d304e755cbcdf1c30e0/README.md) |
| 28&#160;May&#160;25&#160;01:18&#160;UTC | SHAKEN BareTelecom 864J | 27&#160;Jun&#160;25&#160;01:18&#160;UTC | true | [view](CERTS/b18ed0dc589300e38e235a1f82b32d7e4080495a75f5267f4a2f30b3083bf9ec/README.md) |
| 28&#160;May&#160;25&#160;04:42&#160;UTC | SHAKEN IDT America, Corp 363A | 27&#160;Jun&#160;25&#160;04:42&#160;UTC | true | [view](CERTS/97d20bccb5120c67e75db885c83d6a673558d42944f9780a229b2a0f0a65e8c2/README.md) |
| 28&#160;May&#160;25&#160;11:22&#160;UTC | SHAKEN DialedIn 731K | 27&#160;Jun&#160;25&#160;11:22&#160;UTC | true | [view](CERTS/c94fb1552999a8f088358ac9f22145759bd0d6c77783a2e41f0fe1377751f16d/README.md) |
| 28&#160;May&#160;25&#160;13:30&#160;UTC | SHAKEN Socket Telecom LLC 554a | 27&#160;Jun&#160;25&#160;13:30&#160;UTC | true | [view](CERTS/da9a1431330a6d00365721a3e01b9a5a77cc73e0173b8a80bb023957dd8d435a/README.md) |
| 28&#160;May&#160;25&#160;14:14&#160;UTC | SHAKEN ASIA PACIFIC NETWORK CORPORATION 988J | 27&#160;Jun&#160;25&#160;14:14&#160;UTC | true | [view](CERTS/704a2952f1a8e1d3f12593b27caaebfefb25de202e7b8cf8f9bc4547a42987a5/README.md) |
| 28&#160;May&#160;25&#160;23:35&#160;UTC | SHAKEN Televergence Solutions Inc 779J | 27&#160;Jun&#160;25&#160;23:35&#160;UTC | true | [view](CERTS/4bc9f7b14260a09d47aa0baee8afa850cc692cd06309dae0b5b577806af2f484/README.md) |
| 29&#160;May&#160;25&#160;01:13&#160;UTC | SHAKEN BareTelecom 864J | 28&#160;Jun&#160;25&#160;01:13&#160;UTC | true | [view](CERTS/c059af9bb403c8562621bea0c6a9c44902e616b85093c189c559e495b041eac9/README.md) |
| 29&#160;May&#160;25&#160;04:37&#160;UTC | SHAKEN IDT America, Corp 363A | 28&#160;Jun&#160;25&#160;04:37&#160;UTC | true | [view](CERTS/a9e46bb8f95d100ca83081d884b47c85c3f4caecd4c2fa7ffb0e22e33ca5a033/README.md) |
| 29&#160;May&#160;25&#160;11:17&#160;UTC | SHAKEN DialedIn 731K | 28&#160;Jun&#160;25&#160;11:17&#160;UTC | true | [view](CERTS/c468ca5f28fab8b3984f529ef40753aba241a25805697554da1dd9e5eb4f69de/README.md) |
| 29&#160;May&#160;25&#160;14:09&#160;UTC | SHAKEN ASIA PACIFIC NETWORK CORPORATION 988J | 28&#160;Jun&#160;25&#160;14:09&#160;UTC | true | [view](CERTS/1333044aa73aa7cb76322a1a22be7fe3f3e94b95c8e95d9cdbc69c11c8d9394b/README.md) |
| 29&#160;May&#160;25&#160;15:43&#160;UTC | SHAKEN Mango Voice LLC 579K | 28&#160;Jun&#160;25&#160;15:43&#160;UTC | true | [view](CERTS/7ba3f4d9fbda5daf5efc1e0a0024e9dc807a27bb1e8ae3c58a3cec549200c35e/README.md) |
| 30&#160;May&#160;25&#160;01:08&#160;UTC | SHAKEN BareTelecom 864J | 29&#160;Jun&#160;25&#160;01:08&#160;UTC | true | [view](CERTS/534f899b41532bea044ccf09ee8c7c887d60b6d093cb22b078743647278bce32/README.md) |
| 30&#160;May&#160;25&#160;14:04&#160;UTC | SHAKEN ASIA PACIFIC NETWORK CORPORATION 988J | 29&#160;Jun&#160;25&#160;14:04&#160;UTC | true | [view](CERTS/cb01faa7d87d3afad858eb10bd54046aa5e44c28f91b80b179a4adfde29fc98d/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 21&#160;Aug&#160;20&#160;01:22&#160;UTC | SHAKEN Sansay Root CA US | 16&#160;Aug&#160;40&#160;01:22&#160;UTC | false | [view](CERTS/8356d251b255f4ac3fd108bb79be4c02dcea2d3b13d138892bdb3a70cbe6a343/README.md) |
| 02&#160;Sep&#160;22&#160;20:53&#160;UTC | SHAKEN Sansay Intermediate CA US WEST 1 | 31&#160;Aug&#160;29&#160;20:53&#160;UTC | false | [view](CERTS/4b1dfdba2b1e4bbffbf900a20f1f6f7befbef0008b963e4922a64469cb97d24b/README.md) |


Generated: 01 Jun 25 22:59 UTC