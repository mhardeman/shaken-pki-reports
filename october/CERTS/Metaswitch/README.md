# STIR/SHAKEN CA Ecosystem Compliance

## Metaswitch

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 86 potential certificates were requested for retrieval
- 86 candidate certificates were included in the corpus being tested
- 1 certificates in the candidate corpus were skipped because they are duplicates
- 0 certificates in the candidate corpus were skipped because they are outside-target-validity-period
- 0 certificates in the candidate corpus were skipped because they did not chain to trust anchors
- 85 certificates being tested against the remaining rules
- 2.02 issues on average found in unexpired, trusted, and non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 47.06% of certificates are too old to be assessed against currently enforced expectations
- 1087 days is the average remaining validity for the certificates in the corpus
- 1095 days is the average initial validity for the certificates in the corpus
- 33 certificates expire in the next 30 days
- 1.37 average number of unexpired certificates per OCN observed
- 62 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 13 | [e_atis_ext_crl_distribution_struct](ISSUES/e_atis_ext_crl_distribution_struct/README.md) | ATIS1000080 |
| 75 | [e_atis_ext_key_usage_ee](ISSUES/e_atis_ext_key_usage_ee/README.md) | ATIS1000080 |
| 2 | [e_atis_subject_cn](ISSUES/e_atis_subject_cn/README.md) | ATIS1000080 |
| 39 | [e_atis_subject_cn_spc](ISSUES/e_atis_subject_cn_spc/README.md) | ATIS1000080 |
| 43 | [e_us_cp_subject_sn_shall](ISSUES/e_us_cp_subject_sn_shall/README.md) | US_SHAKEN_CP |

#### CA Certificates

- 4 potential certificates were requested for retrieval
- 4 candidate certificates were included in the corpus being tested
- 0 certificates in the candidate corpus were skipped because they are duplicates
- 0 certificates in the candidate corpus were skipped because they are outside-target-validity-period
- 0 certificates in the candidate corpus were skipped because they did not chain to trust anchors
- 4 certificates being tested against the remaining rules
- 2.25 issues on average found in unexpired, trusted, and non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 50.00% of certificates are too old to be assessed against currently enforced expectations
- 5218 days is the average remaining validity for the certificates in the corpus
- 5110 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_ext_certificate_policies_ca](ISSUES/e_atis_ext_certificate_policies_ca/README.md) | ATIS1000080 |
| 1 | [e_atis_ext_crl_distribution_ca](ISSUES/e_atis_ext_crl_distribution_ca/README.md) | ATIS1000080 |
| 1 | [e_atis_subject_c_iso_ca](ISSUES/e_atis_subject_c_iso_ca/README.md) | ATIS1000080 |
| 1 | [e_atis_subject_c_us_ca](ISSUES/e_atis_subject_c_us_ca/README.md) | US_SHAKEN_CP |
| 3 | [e_atis_subject_dn_ca](ISSUES/e_atis_subject_dn_ca/README.md) | ATIS1000080 |
| 1 | [e_atis_subject_o_required_ca](ISSUES/e_atis_subject_o_required_ca/README.md) | ATIS1000080 |
| 1 | [e_shaken_certificate_policies_id_ca](ISSUES/e_shaken_certificate_policies_id_ca/README.md) | US_SHAKEN_CP |

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 17&#160;Dec&#160;20&#160;15:19&#160;UTC | TDS Telecom SHAKEN Cert 7804 | 17&#160;Dec&#160;23&#160;15:19&#160;UTC | true | [view](CERTS/a04a669738b79ff55c2b2197f72a12a112b731906e2e6a925d37ccee2fa00a11/README.md) |
| 27&#160;Jan&#160;21&#160;17:16&#160;UTC | Telesystem SHAKEN Cert 786E | 27&#160;Jan&#160;24&#160;17:16&#160;UTC | true | [view](CERTS/2d9aca0895c94291596161363091718089a6e7c19dfa57329ae548432533860f/README.md) |
| 10&#160;Mar&#160;21&#160;20:50&#160;UTC | Northeast Communications of Wisconsin SHAKEN Cert 6692 | 09&#160;Mar&#160;24&#160;20:50&#160;UTC | true | [view](CERTS/90042ab31d5de7abb64b89073a0d931ce22d864b89df13a9372887cb5db45f49/README.md) |
| 17&#160;Mar&#160;21&#160;17:06&#160;UTC | RCN SHAKEN Cert 7615 | 16&#160;Mar&#160;24&#160;17:06&#160;UTC | true | [view](CERTS/bbdec20ad80f4a2a8ed097204a9299566beca170460fb648c81a51d195d9b6f1/README.md) |
| 17&#160;Mar&#160;21&#160;17:12&#160;UTC | GCI SHAKEN Cert 7785 | 16&#160;Mar&#160;24&#160;17:12&#160;UTC | true | [view](CERTS/312e58dffa682b464f9867a7c373f9881d092b834767dcabe5baf8c7245e937c/README.md) |
| 17&#160;Mar&#160;21&#160;17:25&#160;UTC | Yelcot SHAKEN Cert 1733 | 16&#160;Mar&#160;24&#160;17:25&#160;UTC | true | [view](CERTS/f7e9897313ee276a419725d0aa81886e8f3636ad1cd1e9aad623166f56e6b141/README.md) |
| 24&#160;Mar&#160;21&#160;23:52&#160;UTC | Cspire SHAKEN Cert 6581 | 23&#160;Mar&#160;24&#160;23:52&#160;UTC | true | [view](CERTS/09ed5b3292b5bfc7ac80b1027a827138b9503aa8053a61431a8dc851ecad04f2/README.md) |
| 16&#160;Apr&#160;21&#160;15:27&#160;UTC | CBTS Technology Solutions SHAKEN Cert 600F | 15&#160;Apr&#160;24&#160;15:27&#160;UTC | true | [view](CERTS/3d02021a2da14f1ebfe588256a419be9ebc03c0d1fccc51cc29fa9d4a625c6bf/README.md) |
| 30&#160;Apr&#160;21&#160;16:51&#160;UTC | 702 Communications SHAKEN Cert 2737 | 29&#160;Apr&#160;24&#160;16:51&#160;UTC | true | [view](CERTS/c5f150937d7e08266fb699af1cacc1767ea6249bddc2ce99a9f468553d4486ee/README.md) |
| 30&#160;Apr&#160;21&#160;16:59&#160;UTC | Nex-Tech Wireless SHAKEN Cert 122D | 29&#160;Apr&#160;24&#160;16:59&#160;UTC | true | [view](CERTS/efe569be452e63d91da204eeda5030f1b08846836bf9bf036f51b1da5411acdc/README.md) |
| 30&#160;Apr&#160;21&#160;17:05&#160;UTC | Hunter Communications Shaken Cert 660C | 29&#160;Apr&#160;24&#160;17:05&#160;UTC | true | [view](CERTS/0d2022504ffa5407f662990a785786cb0da72ce014838e2cffdcd95cb70c6f64/README.md) |
| 05&#160;May&#160;21&#160;21:02&#160;UTC | American Broadband SHAKEN Cert 355D | 04&#160;May&#160;24&#160;21:02&#160;UTC | true | [view](CERTS/f2fe275fba183def77918369f90d81bc080f1ef58c5422620c3dc45140b2ae75/README.md) |
| 18&#160;May&#160;21&#160;13:14&#160;UTC | Segra SHAKEN Cert 1784 | 17&#160;May&#160;24&#160;13:14&#160;UTC | true | [view](CERTS/f802b8b879d063b87665d8b2a67f6d3ba78a94aa35782f664a6a40afc7586f56/README.md) |
| 18&#160;May&#160;21&#160;13:22&#160;UTC | Viaero Wireless SHAKEN Cert 6874 | 17&#160;May&#160;24&#160;13:22&#160;UTC | true | [view](CERTS/fe826427006707276b684368c81c7b2039d4ce72b25c5cf0a0c039993b026573/README.md) |
| 20&#160;May&#160;21&#160;22:04&#160;UTC | Appalachian Wireless SHAKEN Cert 6940 | 19&#160;May&#160;24&#160;22:04&#160;UTC | true | [view](CERTS/e14170c681e75c37d0ca45e304c09cc0d148246bd7d72e96f91f7a8fe27339fa/README.md) |
| 20&#160;May&#160;21&#160;22:20&#160;UTC | Everstream SHAKEN Cert 472C  | 19&#160;May&#160;24&#160;22:20&#160;UTC | true | [view](CERTS/8710bb38debebd39698fb1c273409b173951cca1fab53a6d4c4aca91e61e06df/README.md) |
| 26&#160;May&#160;21&#160;15:37&#160;UTC | WOW Internet Cable and Phone SHAKEN Cert 665E | 25&#160;May&#160;24&#160;15:37&#160;UTC | true | [view](CERTS/9f86e038b4f6c3bf7fabfe8d4008b071f81bd33a80c55ea66a1aadd79eb9b989/README.md) |
| 04&#160;Jun&#160;21&#160;17:29&#160;UTC | Union Telephone Company SHAKEN Cert 2297 | 03&#160;Jun&#160;24&#160;17:29&#160;UTC | true | [view](CERTS/e5d49f06964a0d852a706d02db3742482fada1f2c550cef4119ce0e25f80590e/README.md) |
| 11&#160;Jun&#160;21&#160;16:01&#160;UTC | Clearwave SHAKEN Cert 9915 | 10&#160;Jun&#160;24&#160;16:01&#160;UTC | true | [view](CERTS/de0c13b76c24e2ef34c5de58e88fbfeef9c8adb44175b42f3c69771db6586491/README.md) |
| 11&#160;Jun&#160;21&#160;16:14&#160;UTC | Carolina West Wireless SHAKEN Cert 5932 | 10&#160;Jun&#160;24&#160;16:14&#160;UTC | true | [view](CERTS/e85dec068c9fa23af68b345257d58269303c925d10fc9101b226d1e0e7d62a9d/README.md) |
| 15&#160;Jun&#160;21&#160;13:56&#160;UTC | ENA SHAKEN cert 521F | 14&#160;Jun&#160;24&#160;13:56&#160;UTC | true | [view](CERTS/a5293c77ed92fdeef1aeff04f6bed7932a6083abc55d03d74a3ec5b817fdba2b/README.md) |
| 21&#160;Jun&#160;21&#160;15:05&#160;UTC | Buckeye SHAKEN Cert 7608 | 20&#160;Jun&#160;24&#160;15:05&#160;UTC | true | [view](CERTS/61a18f942b4df978a21d6e9cf1df2f0cea0dbd9609b1fcfec8c5f97d5c6dcd7e/README.md) |
| 24&#160;Jun&#160;21&#160;22:33&#160;UTC | Hawaiian Telcom SHAKEN Cert 009G | 23&#160;Jun&#160;24&#160;22:33&#160;UTC | true | [view](CERTS/51136b93b3f0cdaef7856044881e5abc0747fe2b4d9a3202f78266ab5228a41d/README.md) |
| 30&#160;Jun&#160;21&#160;16:59&#160;UTC | Utility SHAKEN Cert 9262 | 29&#160;Jun&#160;24&#160;16:59&#160;UTC | true | [view](CERTS/97acbe1f0c7b2ceb99bec93a9da9ff2c1fd55e9a4cd78a32160237751f720236/README.md) |
| 20&#160;Jul&#160;21&#160;19:54&#160;UTC | New Horizon SHAKEN Cert 127E | 19&#160;Jul&#160;24&#160;19:54&#160;UTC | true | [view](CERTS/5b2842e49ecc543187018171fa660e32bdba390a7977c0de97a00aef35b8ae01/README.md) |
| 23&#160;Jul&#160;21&#160;16:59&#160;UTC | Tri-County Telephone Association Inc SHAKEN Cert 2296 | 22&#160;Jul&#160;24&#160;16:59&#160;UTC | true | [view](CERTS/059194bbdc7ecfd6fc3d30b071e4d73565e14360c7a9d19c60f9274ec1025d0f/README.md) |
| 30&#160;Jul&#160;21&#160;17:04&#160;UTC | Foothills Rural Tel SHAKEN Cert 0406 | 29&#160;Jul&#160;24&#160;17:04&#160;UTC | true | [view](CERTS/89a593de82dbaebcffd8d3d577faf5d7f4a6a898608bc75f9cbde11a9cf4f179/README.md) |
| 30&#160;Jul&#160;21&#160;17:16&#160;UTC | Syringa Networks SHAKEN Cert 5869 | 29&#160;Jul&#160;24&#160;17:16&#160;UTC | true | [view](CERTS/5b9b091228790e797adf24925cd1f2508b8372b744611f843a8026a703993d5a/README.md) |
| 16&#160;Sep&#160;21&#160;13:09&#160;UTC | CTS Telecom, Inc SHAKEN Cert 8331 | 15&#160;Sep&#160;24&#160;13:09&#160;UTC | true | [view](CERTS/5c9f6132a96a05a58d02d845ee70e914659682623fb98acbbecd9f8e383dcbec/README.md) |
| 02&#160;Mar&#160;22&#160;17:52&#160;UTC | Valley Telephone Cooperative Inc / VTX1 SHAKEN 2159 | 01&#160;Mar&#160;25&#160;17:52&#160;UTC | true | [view](CERTS/f0883d130f625c1b8157e54e090e4df461fd9afc05aff09d5a08cf50f9cd37aa/README.md) |
| 05&#160;May&#160;22&#160;14:14&#160;UTC | Kaplan Telephone SHAKEN cert 0432 | 04&#160;May&#160;25&#160;14:14&#160;UTC | true | [view](CERTS/24c1b7c4dc4aeda21b5d1c5ff7f059903693c4a8b67ecc054ef05542a2ff4c35/README.md) |
| 19&#160;May&#160;22&#160;15:44&#160;UTC | DTC Communications SHAKEN Cert 0562 | 18&#160;May&#160;25&#160;15:44&#160;UTC | true | [view](CERTS/e72f0cf001ceeb26687b4aefba16aedc0006f2ce1b8069325adb312389e28173/README.md) |
| 07&#160;Jun&#160;22&#160;12:24&#160;UTC | Avid Communication SHAKEN Cert 742D | 06&#160;Jun&#160;25&#160;12:24&#160;UTC | true | [view](CERTS/b63d54026dfcdfd16495ad6fdda8993de182c86b4aa870784177c38c53842cba/README.md) |
| 02&#160;Aug&#160;22&#160;10:43&#160;UTC | Encore Communications SHAKEN Cert 956H | 01&#160;Aug&#160;25&#160;10:43&#160;UTC | true | [view](CERTS/cc63709890efdf1d938ab01b88b7d4f8368361ffd8572f46cd707e5b3807c95f/README.md) |
| 18&#160;Aug&#160;22&#160;10:39&#160;UTC | Pembroke Telephone Company, Inc SHAKEN Cert 0376 | 17&#160;Aug&#160;25&#160;10:39&#160;UTC | true | [view](CERTS/69ab198b52280bf3d729e1427f62d521e91796e2bae19f99fa0ccd8d024b32de/README.md) |
| 12&#160;Oct&#160;22&#160;17:52&#160;UTC | Northeast Oklahoma Electric Cooperative SHAKEN Cert 945H | 11&#160;Oct&#160;25&#160;17:52&#160;UTC | true | [view](CERTS/b399b86f53e35dfa37c4cd7b28ee0132d934ef73354f564636d8edee42d58ccd/README.md) |
| 26&#160;Oct&#160;22&#160;16:12&#160;UTC | Northland Networks SHAKEN Cert 7556 | 25&#160;Oct&#160;25&#160;16:12&#160;UTC | true | [view](CERTS/7245e57bd5695bfa52c8ab554bf83a3a7dd21a0dacef76a9aee21b55db7f9963/README.md) |
| 02&#160;Dec&#160;22&#160;17:33&#160;UTC | Ritter Communications SHAKEN cert 095A | 01&#160;Dec&#160;25&#160;17:33&#160;UTC | true | [view](CERTS/28f471821d4f6e3c04d12ffc72c29afe143a2998efbd6fb4f4f55a42d8d594c2/README.md) |
| 22&#160;Feb&#160;23&#160;20:45&#160;UTC | GVTC SHAKEN Cert 2083 | 21&#160;Feb&#160;26&#160;20:45&#160;UTC | true | [view](CERTS/7d497f315d42dc54f854e8711b1873ac16c8966916434b58c8c02c003fb0c1f5/README.md) |
| 02&#160;Mar&#160;23&#160;17:57&#160;UTC | Summit Broadband SHAKEN Cert 7857 | 01&#160;Mar&#160;26&#160;17:57&#160;UTC | true | [view](CERTS/ed3e9cefca8e2fd0c60362a76618f89faafe7d12ea8979620b402eb887a53531/README.md) |
| 14&#160;Mar&#160;23&#160;23:37&#160;UTC | Consolidated Telcom ND SHAKEN Cert 7008 | 13&#160;Mar&#160;26&#160;23:37&#160;UTC | true | [view](CERTS/47618375275c0752509a0796d400c1a874033575cde6333b6f8dc730d496a253/README.md) |
| 26&#160;Mar&#160;23&#160;22:56&#160;UTC | Eatel SHAKEN Cert 8839 | 25&#160;Mar&#160;26&#160;22:56&#160;UTC | true | [view](CERTS/a28d2c246508e2e6cff13fe388c7553b5490afb448d03437142aaea9ddc8d439/README.md) |
| 29&#160;Mar&#160;23&#160;18:43&#160;UTC | Highland Telephone Cooperative SHAKEN Cert 0565 | 28&#160;Mar&#160;26&#160;18:43&#160;UTC | true | [view](CERTS/5d5c734ab29a426bd302cc7389cbad919187cdea1e6eb332af380dc9e1990045/README.md) |
| 31&#160;Mar&#160;23&#160;16:08&#160;UTC | Twin Lakes SHAKEN Cert 0579 | 30&#160;Mar&#160;26&#160;16:08&#160;UTC | true | [view](CERTS/863baf457cc2e6cbf29ba1bee6b324fb5546c206a8f279094b4ab189ec2a1b5f/README.md) |
| 06&#160;Apr&#160;23&#160;10:18&#160;UTC | West Kentucky Rural SHAKEN Cert 0421 | 05&#160;Apr&#160;26&#160;10:18&#160;UTC | true | [view](CERTS/62a29b3d0b7af5b22427dc5dee9d649652664d6a455a601ed01b85592ad9a0a6/README.md) |
| 19&#160;Apr&#160;23&#160;14:08&#160;UTC | Aeneas Communications SHAKEN Cert 2891 | 18&#160;Apr&#160;26&#160;14:08&#160;UTC | true | [view](CERTS/b93371d6de0afcb0e63f67eeca399e4ab95836083e70c573f10ace5c3c9d49de/README.md) |
| 19&#160;Apr&#160;23&#160;14:19&#160;UTC | Blackfoot Communications SHAKEN Cert 2235 | 18&#160;Apr&#160;26&#160;14:19&#160;UTC | true | [view](CERTS/1ae2c0be152e4cef8d41bcfc9809e5d8c71251f93f845e84304ca5a3603019a4/README.md) |
| 26&#160;Apr&#160;23&#160;23:44&#160;UTC | Point Broadband Inc Bristol SHAKEN Cert 9809 | 25&#160;Apr&#160;26&#160;23:44&#160;UTC | true | [view](CERTS/27b46292c626954e89bb6e92e5f752fd88b1efe5a0507ed0d1f72ab9bcdee40e/README.md) |
| 29&#160;Apr&#160;23&#160;11:11&#160;UTC | Project Mutual SHAKEN Cert 2231 | 28&#160;Apr&#160;26&#160;11:11&#160;UTC | true | [view](CERTS/d0a2456e20d153010a45b43f3247b0e6ce7bbd4e614967f3184d8e9516995bba/README.md) |
| 03&#160;May&#160;23&#160;16:53&#160;UTC | 3 Rivers Communications SHAKEN Cert 2255 | 02&#160;May&#160;26&#160;16:53&#160;UTC | true | [view](CERTS/8b53182b31f279a02c6fd03f50762f1d9e3412dc8bd0d2535380627545e28a2c/README.md) |
| 03&#160;May&#160;23&#160;16:55&#160;UTC | Chariton Valley SHAKEN 250A | 02&#160;May&#160;26&#160;16:55&#160;UTC | true | [view](CERTS/377c6fcbcdf110f0b2474415f03d1fb592deb2fcd7394e0404799ede3bb74163/README.md) |
| 05&#160;May&#160;23&#160;15:39&#160;UTC | Plant Telephone Company SHAKEN 0379 | 04&#160;May&#160;26&#160;15:39&#160;UTC | true | [view](CERTS/d3ebd5b2606561fe866139e30c52b829e0bc65c602e77467c8d070987f89df14/README.md) |
| 05&#160;May&#160;23&#160;15:48&#160;UTC | Crosstel Tandem Inc SEPB SHAKEN Cert 357H | 04&#160;May&#160;26&#160;15:48&#160;UTC | true | [view](CERTS/9543f4ce9c1bfae926f9f2103ed6366cb203a6f30586c4b496c24684aa1bec6e/README.md) |
| 09&#160;May&#160;23&#160;13:42&#160;UTC | Crosstel Tandem Inc Holston Shaken Cert 308H  | 08&#160;May&#160;26&#160;13:42&#160;UTC | true | [view](CERTS/c3ca2954b6b625e08636377012a5b92ef553eb182f77872b9a072b8644fe4096/README.md) |
| 12&#160;May&#160;23&#160;11:11&#160;UTC | Fastwyre Broadband SHAKEN Cert 0425 | 11&#160;May&#160;26&#160;11:11&#160;UTC | true | [view](CERTS/2da263aa90b8ba1747cc000ba40674f5d534903d8ee0c5cd38ea276bc95f02f3/README.md) |
| 25&#160;May&#160;23&#160;22:17&#160;UTC | Alma Tel SHAKEN 0344 | 24&#160;May&#160;26&#160;22:17&#160;UTC | true | [view](CERTS/1008e70b562dafabfb601eb7e7706c597172afcd0728a9e7602454dd0f365a7b/README.md) |
| 07&#160;Jun&#160;23&#160;16:55&#160;UTC | Five Area Telephone SHAKEN Cert 2071 | 06&#160;Jun&#160;26&#160;16:55&#160;UTC | true | [view](CERTS/db99dd8dc88710f1a73aebd4530a1d432ef3468c5e3b7ac911ec9c96703fd108/README.md) |
| 08&#160;Jun&#160;23&#160;16:02&#160;UTC | Whidbey Telephone Company SHAKEN Cert 2452 | 07&#160;Jun&#160;26&#160;16:02&#160;UTC | true | [view](CERTS/11a8d77aa46349b365d5740e537d242f906b2729b3a16dcc5008297a8a7e3a3c/README.md) |
| 20&#160;Jun&#160;23&#160;09:29&#160;UTC | Ben Lomand SHAKEN Cert 0553 | 19&#160;Jun&#160;26&#160;09:29&#160;UTC | true | [view](CERTS/ce469ff39f245721d8c523af0a6fbd26fc0742e3c18b0b5adc627794eaad6231/README.md) |
| 29&#160;Jun&#160;23&#160;11:04&#160;UTC | Vexus Fiber SHAKEN Cert 4913 | 28&#160;Jun&#160;26&#160;11:04&#160;UTC | true | [view](CERTS/db225e5de1d4140135822c964fe884cc86f526f4c7c108fa9aa3c426cbd39cb6/README.md) |
| 05&#160;Oct&#160;23&#160;13:44&#160;UTC | Fidelity Communications SHAKEN Cert 1882 | 04&#160;Oct&#160;26&#160;13:44&#160;UTC | true | [view](CERTS/af56b81c67b9b517530e053f153af3c7d6a72620c04f84b1ff648e7c137e1376/README.md) |
| 06&#160;Dec&#160;23&#160;17:30&#160;UTC | TDS Telecom SHAKEN Cert 7804 | 05&#160;Dec&#160;26&#160;17:30&#160;UTC | true | [view](CERTS/dce299b1c08b1429bf51a4f30484ba06034302b3a668d75122b8df4e6d847077/README.md) |
| 10&#160;Jan&#160;24&#160;10:41&#160;UTC | Telesystem SHAKEN Cert  786E | 09&#160;Jan&#160;27&#160;10:41&#160;UTC | true | [view](CERTS/1803673087bbc5010fdcdf8ec7308a8d5c3fee7bc564896cce642b5e32744f6b/README.md) |
| 17&#160;Jan&#160;24&#160;17:28&#160;UTC | Buckeye SHAKEN Cert 7608 | 16&#160;Jan&#160;27&#160;17:28&#160;UTC | true | [view](CERTS/d3a051450eb1766106edeb97ef0206906b249e07e741717dbb954dbb987baef3/README.md) |
| 02&#160;Feb&#160;24&#160;18:21&#160;UTC | GCI SHAKEN Cert 7785 | 01&#160;Feb&#160;27&#160;18:21&#160;UTC | true | [view](CERTS/756b85600764bd2c72e98777b98791b6005640feb1fba6f3d9c1a278c9e66f87/README.md) |
| 13&#160;Feb&#160;24&#160;10:39&#160;UTC | Northeast Communications of Wisconsin SHAKEN Cert 6692 | 12&#160;Feb&#160;27&#160;10:39&#160;UTC | true | [view](CERTS/3d46aceeef2cac6a05000c9888af4d55ccd3201ea00ab98a2c6ff4309ef8dfb3/README.md) |
| 16&#160;Feb&#160;24&#160;10:24&#160;UTC | South Central Rural Telecommunications Coop SHAKEN Cert 0418 | 15&#160;Feb&#160;27&#160;10:24&#160;UTC | true | [view](CERTS/3447893d621b5342a19be4adc6fa962c8b03b3d934d10ad5e8a9de85f1b33df5/README.md) |
| 16&#160;Feb&#160;24&#160;10:32&#160;UTC | Cellular South Licenses SHAKEN Cert 6581 | 15&#160;Feb&#160;27&#160;10:32&#160;UTC | true | [view](CERTS/00941a6765df10dc35107d8f82f07a6bde43aeef738821df1ac58d997fcaf5ea/README.md) |
| 23&#160;Feb&#160;24&#160;11:12&#160;UTC | Segra SHAKEN Cert 1784 | 22&#160;Feb&#160;27&#160;11:12&#160;UTC | true | [view](CERTS/43e33ae8510822ad85afd4b972224c56b6e303b38e8ee3487836f32e2b2b6c89/README.md) |
| 27&#160;Feb&#160;24&#160;11:26&#160;UTC | RCN SHAKEN Cert 7615 | 26&#160;Feb&#160;27&#160;11:26&#160;UTC | true | [view](CERTS/a3e31a58c4128199dd01dd48c23aa4d650b693b47341f25c0c316f4196e034b9/README.md) |
| 08&#160;Mar&#160;24&#160;16:27&#160;UTC | Altafiber SHAKEN Cert 600F | 08&#160;Mar&#160;27&#160;16:27&#160;UTC | true | [view](CERTS/539f95db9ccfdb4fbde5313b77c2b42bd0353b0bb2506829cbc995f7bb7bcf8e/README.md) |
| 20&#160;Mar&#160;24&#160;19:46&#160;UTC | Nex-Tech Wireless SHAKEN Cert 122D | 20&#160;Mar&#160;27&#160;19:46&#160;UTC | true | [view](CERTS/29b17dc541b9267c439d4c77923a9cdbb64b8183e42a8915c9c7e705234538fa/README.md) |
| 11&#160;Apr&#160;24&#160;10:09&#160;UTC | Hunter Communications SHAKEN 660C | 11&#160;Apr&#160;27&#160;10:09&#160;UTC | true | [view](CERTS/7ba7f6eec3035d5721469238231d79d35781c43b0830bdf252d62c2a9579e08e/README.md) |
| 11&#160;Apr&#160;24&#160;10:10&#160;UTC | Everstream SHAKEN 472C | 11&#160;Apr&#160;27&#160;10:10&#160;UTC | true | [view](CERTS/ef8932bec0b9fb4dce93bc75b789ad3c6b7f2a9d16d781a65d0b314651d3a8af/README.md) |
| 25&#160;Apr&#160;24&#160;12:08&#160;UTC | Viaero Wireless SHAKEN 6874 | 25&#160;Apr&#160;27&#160;12:08&#160;UTC | true | [view](CERTS/a78a872118a4c72e76b6751e8c04590e534c15dbdbf9813d6d1f5a3e671e44a8/README.md) |
| 26&#160;Apr&#160;24&#160;09:58&#160;UTC | WOW Internet Cable and Phone SHAKEN 665E | 26&#160;Apr&#160;27&#160;09:58&#160;UTC | true | [view](CERTS/738ec11f972c1bfbc225dc01ba5c7b46968fa610303d3f3698d03d3e431da0c9/README.md) |
| 01&#160;May&#160;24&#160;12:38&#160;UTC | New Horizon SHAKEN 127E | 01&#160;May&#160;27&#160;12:38&#160;UTC | true | [view](CERTS/5b5b2d67ae750d1db589bd45461c3844563b09b14b41c293e66cfd8966aa5e49/README.md) |
| 07&#160;May&#160;24&#160;16:35&#160;UTC | ENA SHAKEN 521F | 07&#160;May&#160;27&#160;16:35&#160;UTC | true | [view](CERTS/5003525959e13e5a8db645098c431af4e079327fe4b80986685e99b8a57af61d/README.md) |
| 07&#160;May&#160;24&#160;16:46&#160;UTC | Appalachian Wireless SHAKEN 6940 | 07&#160;May&#160;27&#160;16:46&#160;UTC | true | [view](CERTS/dff6375d9e6b33e8de3587cf30d392a1cbc6dc0a7c7eacf726c8b32e533d2284/README.md) |
| 13&#160;May&#160;24&#160;10:03&#160;UTC | Utility SHAKEN 9262 | 13&#160;May&#160;27&#160;10:03&#160;UTC | true | [view](CERTS/55f07535beff566a23d1d772234b291470b678370907afa2c2db1ae4ecbe92ef/README.md) |
| 16&#160;May&#160;24&#160;16:46&#160;UTC | Union Telephone Company SHAKEN 2297 | 16&#160;May&#160;27&#160;16:46&#160;UTC | true | [view](CERTS/9301e697d6eb128e4eb645e111ff8166dca39e0ff11b0eae54aab95f46111bdb/README.md) |
| 16&#160;May&#160;24&#160;16:50&#160;UTC | Tri-County Telephone Association Inc SHAKEN 2296 | 16&#160;May&#160;27&#160;16:50&#160;UTC | true | [view](CERTS/4356608c69640e50e94ba5e8dc38381a3bf7b01fbddd8297e37bfb89fa88dad7/README.md) |
| 24&#160;May&#160;24&#160;13:21&#160;UTC | Carolina West Wireless SHAKEN 5932 | 24&#160;May&#160;27&#160;13:21&#160;UTC | true | [view](CERTS/295732fec21729ae13022f5a282d6650170fb9ed597a7e64112d614ce5ce19ca/README.md) |
| 29&#160;May&#160;24&#160;09:35&#160;UTC | Hawaiian Telcom SHAKEN 009G | 29&#160;May&#160;27&#160;09:35&#160;UTC | true | [view](CERTS/66c671582a791af13a5672f2b6ea2e2c88ecc4e59d6b74bd8a4387554048d897/README.md) |
| 03&#160;Jun&#160;24&#160;16:26&#160;UTC | Clearwave SHAKEN 9915 | 03&#160;Jun&#160;27&#160;16:26&#160;UTC | true | [view](CERTS/496f7dda838fe8c12d36121018d5f77c50d6470e494da7b99a23e79b50fe3352/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 25&#160;Nov&#160;20&#160;11:21&#160;UTC | Metaswitch STI-CA SHAKEN Root | 20&#160;Nov&#160;40&#160;11:21&#160;UTC | true | [view](CERTS/c27184f75f81fc119b85d51d416477bf635040e5d66ce6051799b37b9aa17485/README.md) |
| 25&#160;Nov&#160;20&#160;11:57&#160;UTC | Metaswitch STI-CA SHAKEN Issuing 1 | 22&#160;Nov&#160;32&#160;11:57&#160;UTC | true | [view](CERTS/b91a9874fbefc3feda9d5f9bd336e8b999c9b15b25aae7fe3c61d87373a5d1a1/README.md) |
| 10&#160;Feb&#160;23&#160;14:38&#160;UTC | Metaswitch STI-CA SHAKEN Issuing 1 | 07&#160;Feb&#160;35&#160;14:38&#160;UTC | true | [view](CERTS/8a7fb50e95b8c43a63d19e2f279de565fa611ae3f24a14f82394e3208782be7a/README.md) |
| 21&#160;Mar&#160;24&#160;10:14&#160;UTC | Metaswitch STI-CA SHAKEN Issuing 1 | 18&#160;Mar&#160;36&#160;10:14&#160;UTC | true | [view](CERTS/12d67681ec2bd575ddcb33c721fe445dc556f0e362ba5b565a1f03897cb542f6/README.md) |


Generated: 03 Jun 25 00:48 UTC