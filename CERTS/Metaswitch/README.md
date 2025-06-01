# STIR/SHAKEN CA Ecosystem Compliance

## Metaswitch

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 49 certificates were included in the corpus being tested
- 1 certificates in the corpus were skipped because they are duplicates
- 0 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 48 certificates being tested against the remaining rules
- 2.27 issues on average found in unexpired, trusted, and non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 6.25% of certificates are too old to be assessed against currently enforced expectations
- 1079 days is the average remaining validity for the certificates in the corpus
- 1095 days is the average initial validity for the certificates in the corpus
- 1 certificates expire in the next 30 days
- 1.02 average number of unexpired certificates per OCN observed
- 47 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 19 | [e_atis_ext_crl_distribution_struct](ISSUES/e_atis_ext_crl_distribution_struct/README.md) | ATIS1000080 |
| 33 | [e_atis_ext_key_usage_ee](ISSUES/e_atis_ext_key_usage_ee/README.md) | ATIS1000080 |
| 28 | [e_atis_subject_cn_spc](ISSUES/e_atis_subject_cn_spc/README.md) | ATIS1000080 |
| 29 | [e_us_cp_subject_sn_shall](ISSUES/e_us_cp_subject_sn_shall/README.md) | US_SHAKEN_CP |

#### CA Certificates

- 3 certificates were included in the corpus being tested
- 0 certificates in the corpus were skipped because they are duplicates
- 0 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 3 certificates being tested against the remaining rules
- 2.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 33.33% of certificates are too old to be assessed against currently enforced expectations
- 5428 days is the average remaining validity for the certificates in the corpus
- 5353 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_subject_c_iso_ca](ISSUES/e_atis_subject_c_iso_ca/README.md) | ATIS1000080 |
| 1 | [e_atis_subject_c_us_ca](ISSUES/e_atis_subject_c_us_ca/README.md) | US_SHAKEN_CP |
| 2 | [e_atis_subject_dn_ca](ISSUES/e_atis_subject_dn_ca/README.md) | ATIS1000080 |
| 1 | [e_atis_subject_o_required_ca](ISSUES/e_atis_subject_o_required_ca/README.md) | ATIS1000080 |
| 1 | [e_shaken_certificate_policies_id_ca](ISSUES/e_shaken_certificate_policies_id_ca/README.md) | US_SHAKEN_CP |

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 07&#160;Jun&#160;22&#160;12:24&#160;UTC | Avid Communication SHAKEN Cert 742D | 06&#160;Jun&#160;25&#160;12:24&#160;UTC | true | [view](CERTS/b63d54026dfcdfd16495ad6fdda8993de182c86b4aa870784177c38c53842cba/README.md) |
| 08&#160;Sep&#160;22&#160;16:04&#160;UTC | Priority Communications SHAKEN Cert 327K | 07&#160;Sep&#160;25&#160;16:04&#160;UTC | true | [view](CERTS/272753ac210e9937d9fbf8fcb367c945c68edc3c7bd8d5193cfb09bf8252331a/README.md) |
| 02&#160;Dec&#160;22&#160;17:33&#160;UTC | Ritter Communications SHAKEN cert 095A | 01&#160;Dec&#160;25&#160;17:33&#160;UTC | true | [view](CERTS/28f471821d4f6e3c04d12ffc72c29afe143a2998efbd6fb4f4f55a42d8d594c2/README.md) |
| 14&#160;Mar&#160;23&#160;23:37&#160;UTC | Consolidated Telcom ND SHAKEN Cert 7008 | 13&#160;Mar&#160;26&#160;23:37&#160;UTC | true | [view](CERTS/47618375275c0752509a0796d400c1a874033575cde6333b6f8dc730d496a253/README.md) |
| 26&#160;Mar&#160;23&#160;22:56&#160;UTC | Eatel SHAKEN Cert 8839 | 25&#160;Mar&#160;26&#160;22:56&#160;UTC | true | [view](CERTS/a28d2c246508e2e6cff13fe388c7553b5490afb448d03437142aaea9ddc8d439/README.md) |
| 19&#160;Apr&#160;23&#160;14:19&#160;UTC | Blackfoot Communications SHAKEN Cert 2235 | 18&#160;Apr&#160;26&#160;14:19&#160;UTC | true | [view](CERTS/1ae2c0be152e4cef8d41bcfc9809e5d8c71251f93f845e84304ca5a3603019a4/README.md) |
| 19&#160;Apr&#160;23&#160;14:23&#160;UTC | Lemonweir Valley Telephone Company SHAKEN Cert 0900 | 18&#160;Apr&#160;26&#160;14:23&#160;UTC | true | [view](CERTS/35b3aec98409afbb2e53cc6990597e61c467a67c10c07cc01c1cbf90385af469/README.md) |
| 29&#160;Apr&#160;23&#160;11:11&#160;UTC | Project Mutual SHAKEN Cert 2231 | 28&#160;Apr&#160;26&#160;11:11&#160;UTC | true | [view](CERTS/d0a2456e20d153010a45b43f3247b0e6ce7bbd4e614967f3184d8e9516995bba/README.md) |
| 03&#160;May&#160;23&#160;16:53&#160;UTC | 3 Rivers Communications SHAKEN Cert 2255 | 02&#160;May&#160;26&#160;16:53&#160;UTC | true | [view](CERTS/8b53182b31f279a02c6fd03f50762f1d9e3412dc8bd0d2535380627545e28a2c/README.md) |
| 03&#160;May&#160;23&#160;16:55&#160;UTC | Chariton Valley SHAKEN 250A | 02&#160;May&#160;26&#160;16:55&#160;UTC | true | [view](CERTS/377c6fcbcdf110f0b2474415f03d1fb592deb2fcd7394e0404799ede3bb74163/README.md) |
| 12&#160;May&#160;23&#160;11:11&#160;UTC | Fastwyre Broadband SHAKEN Cert 0425 | 11&#160;May&#160;26&#160;11:11&#160;UTC | true | [view](CERTS/2da263aa90b8ba1747cc000ba40674f5d534903d8ee0c5cd38ea276bc95f02f3/README.md) |
| 12&#160;May&#160;23&#160;11:14&#160;UTC | Vermont Telephone Company Inc SHAKEN Cert 3332 | 11&#160;May&#160;26&#160;11:14&#160;UTC | true | [view](CERTS/806a5eafa00be93ae29369dd117912199d430d7dde919301a3a8a27f7b55b41a/README.md) |
| 07&#160;Jun&#160;23&#160;16:55&#160;UTC | Five Area Telephone SHAKEN Cert 2071 | 06&#160;Jun&#160;26&#160;16:55&#160;UTC | true | [view](CERTS/db99dd8dc88710f1a73aebd4530a1d432ef3468c5e3b7ac911ec9c96703fd108/README.md) |
| 08&#160;Jun&#160;23&#160;16:02&#160;UTC | Whidbey Telephone Company SHAKEN Cert 2452 | 07&#160;Jun&#160;26&#160;16:02&#160;UTC | true | [view](CERTS/11a8d77aa46349b365d5740e537d242f906b2729b3a16dcc5008297a8a7e3a3c/README.md) |
| 29&#160;Jun&#160;23&#160;11:04&#160;UTC | Vexus Fiber SHAKEN Cert 4913 | 28&#160;Jun&#160;26&#160;11:04&#160;UTC | true | [view](CERTS/db225e5de1d4140135822c964fe884cc86f526f4c7c108fa9aa3c426cbd39cb6/README.md) |
| 05&#160;Oct&#160;23&#160;13:44&#160;UTC | Fidelity Communications SHAKEN Cert 1882 | 04&#160;Oct&#160;26&#160;13:44&#160;UTC | true | [view](CERTS/af56b81c67b9b517530e053f153af3c7d6a72620c04f84b1ff648e7c137e1376/README.md) |
| 06&#160;Dec&#160;23&#160;17:30&#160;UTC | TDS Telecom SHAKEN Cert 7804 | 05&#160;Dec&#160;26&#160;17:30&#160;UTC | true | [view](CERTS/dce299b1c08b1429bf51a4f30484ba06034302b3a668d75122b8df4e6d847077/README.md) |
| 10&#160;Jan&#160;24&#160;10:41&#160;UTC | Telesystem SHAKEN Cert  786E | 09&#160;Jan&#160;27&#160;10:41&#160;UTC | true | [view](CERTS/1803673087bbc5010fdcdf8ec7308a8d5c3fee7bc564896cce642b5e32744f6b/README.md) |
| 17&#160;Jan&#160;24&#160;17:28&#160;UTC | Buckeye SHAKEN Cert 7608 | 16&#160;Jan&#160;27&#160;17:28&#160;UTC | true | [view](CERTS/d3a051450eb1766106edeb97ef0206906b249e07e741717dbb954dbb987baef3/README.md) |
| 26&#160;Jan&#160;24&#160;16:07&#160;UTC | Duo Broadband SHAKEN Cert 0401 | 25&#160;Jan&#160;27&#160;16:07&#160;UTC | true | [view](CERTS/e0fb299e0423a9609fee77056c92fca4a5af32ea3a45fced6d88d206c2fcc772/README.md) |
| 02&#160;Feb&#160;24&#160;18:16&#160;UTC | Smithville Communications CLEC SHAKEN Cert 774D | 01&#160;Feb&#160;27&#160;18:16&#160;UTC | true | [view](CERTS/e77fcd9b9b6732cf310e955dc3b3312bcff51f5ae04db38efc87166f0d034cd6/README.md) |
| 02&#160;Feb&#160;24&#160;18:21&#160;UTC | GCI SHAKEN Cert 7785 | 01&#160;Feb&#160;27&#160;18:21&#160;UTC | true | [view](CERTS/756b85600764bd2c72e98777b98791b6005640feb1fba6f3d9c1a278c9e66f87/README.md) |
| 13&#160;Feb&#160;24&#160;10:39&#160;UTC | Northeast Communications of Wisconsin SHAKEN Cert 6692 | 12&#160;Feb&#160;27&#160;10:39&#160;UTC | true | [view](CERTS/3d46aceeef2cac6a05000c9888af4d55ccd3201ea00ab98a2c6ff4309ef8dfb3/README.md) |
| 16&#160;Feb&#160;24&#160;10:32&#160;UTC | Cellular South Licenses SHAKEN Cert 6581 | 15&#160;Feb&#160;27&#160;10:32&#160;UTC | true | [view](CERTS/00941a6765df10dc35107d8f82f07a6bde43aeef738821df1ac58d997fcaf5ea/README.md) |
| 23&#160;Feb&#160;24&#160;11:12&#160;UTC | Segra SHAKEN Cert 1784 | 22&#160;Feb&#160;27&#160;11:12&#160;UTC | true | [view](CERTS/43e33ae8510822ad85afd4b972224c56b6e303b38e8ee3487836f32e2b2b6c89/README.md) |
| 27&#160;Feb&#160;24&#160;11:26&#160;UTC | RCN SHAKEN Cert 7615 | 26&#160;Feb&#160;27&#160;11:26&#160;UTC | true | [view](CERTS/a3e31a58c4128199dd01dd48c23aa4d650b693b47341f25c0c316f4196e034b9/README.md) |
| 08&#160;Mar&#160;24&#160;16:27&#160;UTC | Altafiber SHAKEN Cert 600F | 08&#160;Mar&#160;27&#160;16:27&#160;UTC | true | [view](CERTS/539f95db9ccfdb4fbde5313b77c2b42bd0353b0bb2506829cbc995f7bb7bcf8e/README.md) |
| 15&#160;Mar&#160;24&#160;10:27&#160;UTC | USCellular SHAKEN Cert 6349 | 15&#160;Mar&#160;27&#160;10:27&#160;UTC | true | [view](CERTS/ec7913d85bed7d54482116c71ed51e9b018642cd690670bb870d5c7fc55ff439/README.md) |
| 20&#160;Mar&#160;24&#160;19:46&#160;UTC | Nex-Tech Wireless SHAKEN Cert 122D | 20&#160;Mar&#160;27&#160;19:46&#160;UTC | true | [view](CERTS/29b17dc541b9267c439d4c77923a9cdbb64b8183e42a8915c9c7e705234538fa/README.md) |
| 28&#160;Mar&#160;24&#160;16:43&#160;UTC | Allstream SHAKEN 4130 | 28&#160;Mar&#160;27&#160;16:43&#160;UTC | true | [view](CERTS/22cb64f2b77df09828d02feae3f6a3c7d3d9caba0ac156bc09214c57b3e0abc2/README.md) |
| 05&#160;Apr&#160;24&#160;09:53&#160;UTC | U. S. Telepacific Corp SHAKEN 7453 | 05&#160;Apr&#160;27&#160;09:53&#160;UTC | true | [view](CERTS/2382a05acdbbcac50de555226898695d61ee942019e54ce2f84dbb85455b2e46/README.md) |
| 11&#160;Apr&#160;24&#160;10:10&#160;UTC | Everstream SHAKEN 472C | 11&#160;Apr&#160;27&#160;10:10&#160;UTC | true | [view](CERTS/ef8932bec0b9fb4dce93bc75b789ad3c6b7f2a9d16d781a65d0b314651d3a8af/README.md) |
| 25&#160;Apr&#160;24&#160;12:08&#160;UTC | Viaero Wireless SHAKEN 6874 | 25&#160;Apr&#160;27&#160;12:08&#160;UTC | true | [view](CERTS/a78a872118a4c72e76b6751e8c04590e534c15dbdbf9813d6d1f5a3e671e44a8/README.md) |
| 26&#160;Apr&#160;24&#160;09:58&#160;UTC | WOW Internet Cable and Phone SHAKEN 665E | 26&#160;Apr&#160;27&#160;09:58&#160;UTC | true | [view](CERTS/738ec11f972c1bfbc225dc01ba5c7b46968fa610303d3f3698d03d3e431da0c9/README.md) |
| 01&#160;May&#160;24&#160;12:33&#160;UTC | Nemont SHAKEN 2247 | 01&#160;May&#160;27&#160;12:33&#160;UTC | true | [view](CERTS/263baad0d554f1aae94ec2b8b776ed02c511d6be3a70fdbf1abd2b84630ed79c/README.md) |
| 01&#160;May&#160;24&#160;12:38&#160;UTC | New Horizon SHAKEN 127E | 01&#160;May&#160;27&#160;12:38&#160;UTC | true | [view](CERTS/5b5b2d67ae750d1db589bd45461c3844563b09b14b41c293e66cfd8966aa5e49/README.md) |
| 07&#160;May&#160;24&#160;16:35&#160;UTC | ENA SHAKEN 521F | 07&#160;May&#160;27&#160;16:35&#160;UTC | true | [view](CERTS/5003525959e13e5a8db645098c431af4e079327fe4b80986685e99b8a57af61d/README.md) |
| 07&#160;May&#160;24&#160;16:46&#160;UTC | Appalachian Wireless SHAKEN 6940 | 07&#160;May&#160;27&#160;16:46&#160;UTC | true | [view](CERTS/dff6375d9e6b33e8de3587cf30d392a1cbc6dc0a7c7eacf726c8b32e533d2284/README.md) |
| 13&#160;May&#160;24&#160;10:03&#160;UTC | Utility SHAKEN 9262 | 13&#160;May&#160;27&#160;10:03&#160;UTC | true | [view](CERTS/55f07535beff566a23d1d772234b291470b678370907afa2c2db1ae4ecbe92ef/README.md) |
| 16&#160;May&#160;24&#160;16:46&#160;UTC | Union Telephone Company SHAKEN 2297 | 16&#160;May&#160;27&#160;16:46&#160;UTC | true | [view](CERTS/9301e697d6eb128e4eb645e111ff8166dca39e0ff11b0eae54aab95f46111bdb/README.md) |
| 03&#160;Jun&#160;24&#160;17:14&#160;UTC | Mediacom SHAKEN 846F | 03&#160;Jun&#160;27&#160;17:14&#160;UTC | true | [view](CERTS/a2d12c9920c165e8132a4bc24e4d7eed1f1a077add8515b2252dc058d348c728/README.md) |
| 13&#160;Jun&#160;24&#160;09:26&#160;UTC | Sonic Telecom SHAKEN 433E | 13&#160;Jun&#160;27&#160;09:26&#160;UTC | true | [view](CERTS/f18ce346a58e8224d3c89a2fe9b70579724cd396eff02d4af2df348f40aca05a/README.md) |
| 17&#160;Jul&#160;24&#160;14:08&#160;UTC | Syringa Networks SHAKEN 5869 | 17&#160;Jul&#160;27&#160;14:08&#160;UTC | true | [view](CERTS/4731edae61e1131659b03880edd8fe753fdf24220f6cd175776ae3f49b84b21d/README.md) |
| 22&#160;Aug&#160;24&#160;12:37&#160;UTC | CTS Telecom SHAKEN 8331 | 22&#160;Aug&#160;27&#160;12:37&#160;UTC | true | [view](CERTS/1105b6e2d6935bdf1422eea9cdc2304880ac1b7d24554abfc4c3435adf77ca26/README.md) |
| 04&#160;Nov&#160;24&#160;11:37&#160;UTC | Mid-Rivers Telephone Coop SHAKEN 2246 | 04&#160;Nov&#160;27&#160;11:37&#160;UTC | true | [view](CERTS/b4eba8b87c952d1b52dd01120108cd615e5b764ddbec19007744200b6e108815/README.md) |
| 04&#160;Mar&#160;25&#160;12:35&#160;UTC | Kaplan Telephone SHAKEN 0432 | 03&#160;Mar&#160;28&#160;12:35&#160;UTC | true | [view](CERTS/1383a4139fe75e8c3ce1471dae86bb752e8834206b45b542c7575600268f4b59/README.md) |
| 20&#160;Mar&#160;25&#160;12:39&#160;UTC | Avid Communication SHAKEN 742D | 19&#160;Mar&#160;28&#160;12:39&#160;UTC | true | [view](CERTS/0ab008a053e687bfcea698300df5fb1ac5d098a28cbfaa781a241107cdabc5a0/README.md) |
| 25&#160;Mar&#160;25&#160;11:42&#160;UTC | DTC Communications SHAKEN 0562 | 24&#160;Mar&#160;28&#160;11:42&#160;UTC | true | [view](CERTS/32687417bb824dc966edad52715c89c0a5ed312db84797ef332d96dde8d33ecf/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 25&#160;Nov&#160;20&#160;11:21&#160;UTC | Metaswitch STI-CA SHAKEN Root | 20&#160;Nov&#160;40&#160;11:21&#160;UTC | true | [view](CERTS/c27184f75f81fc119b85d51d416477bf635040e5d66ce6051799b37b9aa17485/README.md) |
| 10&#160;Feb&#160;23&#160;14:38&#160;UTC | Metaswitch STI-CA SHAKEN Issuing 1 | 07&#160;Feb&#160;35&#160;14:38&#160;UTC | true | [view](CERTS/8a7fb50e95b8c43a63d19e2f279de565fa611ae3f24a14f82394e3208782be7a/README.md) |
| 21&#160;Mar&#160;24&#160;10:14&#160;UTC | Metaswitch STI-CA SHAKEN Issuing 1 | 18&#160;Mar&#160;36&#160;10:14&#160;UTC | true | [view](CERTS/12d67681ec2bd575ddcb33c721fe445dc556f0e362ba5b565a1f03897cb542f6/README.md) |


Generated: 01 Jun 25 22:59 UTC