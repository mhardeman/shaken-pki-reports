# STIR/SHAKEN CA Ecosystem Compliance

## TransNexus

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 3592 certificates were included in the corpus being tested
- 1 certificates in the corpus were skipped because they are duplicates
- 3562 certificates in the corpus were skipped because they are expired
- 9 certificates in the corpus were skipped because they are not currently trusted
- 20 certificates being tested against the remaining rules
- 1.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 25.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 291 days is the average remaining validity for the certificates in the corpus
- 308 days is the average initial validity for the certificates in the corpus
- 12 certificates expire in the next 30 days
- 1.11 average number of unexpired certificates per OCN observed
- 18 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 5 | [e_us_cp_subject_sn_shall](ISSUES/e_us_cp_subject_sn_shall/README.md) | US_SHAKEN_CP |

#### CA Certificates

- 4 certificates were included in the corpus being tested
- 0 certificates in the corpus were skipped because they are duplicates
- 0 certificates in the corpus were skipped because they are expired
- 1 certificates in the corpus were skipped because they are not currently trusted
- 3 certificates being tested against the remaining rules
- 0.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 0.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 66.67% of certificates are too old to be assessed against currently enforced expectations
- 5241 days is the average remaining validity for the certificates in the corpus
- 4870 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days

No error, warning, or notice level issues were found

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 06&#160;Nov&#160;23&#160;09:42&#160;UTC | SHAKEN 8526 | 05&#160;Nov&#160;24&#160;09:42&#160;UTC | true | [view](CERTS/4c86bf33be8b4189a469827d24c257723b4e5e3236981d9666d04de493b5cb6a/README.md) |
| 08&#160;Dec&#160;23&#160;21:57&#160;UTC | SHAKEN 299K | 07&#160;Dec&#160;24&#160;21:57&#160;UTC | true | [view](CERTS/7b677c8ad6481aa908931a3bec7ec5645e51770d15afca1e706b99f09203eca5/README.md) |
| 31&#160;Jan&#160;24&#160;18:59&#160;UTC | SHAKEN 873J | 30&#160;Jan&#160;25&#160;18:59&#160;UTC | true | [view](CERTS/8342db52ef1e9b25620a252b82f1378cff688a8cc0e594a6669f50ac17b34d03/README.md) |
| 01&#160;Mar&#160;24&#160;06:44&#160;UTC | SHAKEN 736J | 01&#160;Mar&#160;25&#160;06:44&#160;UTC | true | [view](CERTS/006173a1cbc2ce2a785eecfce090df4cc92990833dcae0bb0486f3f2dbf1e9c9/README.md) |
| 18&#160;Mar&#160;24&#160;16:29&#160;UTC | SHAKEN 663J | 18&#160;Mar&#160;25&#160;16:29&#160;UTC | true | [view](CERTS/3eba87a4329cf652b47f2f727feb9b01b5b3465ed41208db0e4e1190bafe9036/README.md) |
| 02&#160;Apr&#160;24&#160;15:50&#160;UTC | SHAKEN 2720 | 02&#160;Apr&#160;25&#160;15:50&#160;UTC | false | [view](CERTS/95a275a51dc842f102c43cd6b11f37b85a911ba727fca4cc6e3f9b859e05070d/README.md) |
| 30&#160;May&#160;24&#160;17:57&#160;UTC | SHAKEN 597J | 30&#160;May&#160;25&#160;17:57&#160;UTC | false | [view](CERTS/71feb09973117fb5d4aef0cfa3de26c3bfabfcb28a658609059777ae3af2d10c/README.md) |
| 06&#160;Jun&#160;24&#160;15:31&#160;UTC | SHAKEN 622J | 03&#160;Dec&#160;24&#160;15:31&#160;UTC | false | [view](CERTS/a9ccde055631fc083e64ef93fcd1baf25af1d2dfc7cedb8633e485f7699064c1/README.md) |
| 19&#160;Jun&#160;24&#160;22:07&#160;UTC | SHAKEN 505J | 16&#160;Dec&#160;24&#160;22:06&#160;UTC | false | [view](CERTS/c60b1f474c0d2900182c895719a34ade2a616a7cde7a3a3016c2d438579e8084/README.md) |
| 05&#160;Jul&#160;24&#160;16:00&#160;UTC | SHAKEN 578J | 05&#160;Jul&#160;25&#160;16:00&#160;UTC | false | [view](CERTS/b48322c4b531e0140e731d1af1acdfcf3535c2f41842655af5fb9f672fb164ee/README.md) |
| 15&#160;Jul&#160;24&#160;22:33&#160;UTC | SHAKEN 6628 | 11&#160;Jan&#160;25&#160;22:33&#160;UTC | false | [view](CERTS/c2bbe61b47c13c983b1c78857c023fbbbf0a0278ae08f58539b816814009cc60/README.md) |
| 16&#160;Jul&#160;24&#160;20:09&#160;UTC | SHAKEN 158K | 16&#160;Jul&#160;25&#160;20:08&#160;UTC | false | [view](CERTS/c6b5bf2bb2de6fa53997627a7050a90ec0f6b9786721642366f4ed5392037d64/README.md) |
| 21&#160;Jul&#160;24&#160;18:14&#160;UTC | SHAKEN 807J | 21&#160;Jul&#160;25&#160;18:14&#160;UTC | false | [view](CERTS/8e674cdfd9e11313d090b12d33deee35dceed42b64e1c751aba1a605ac1265f8/README.md) |
| 08&#160;Aug&#160;24&#160;21:49&#160;UTC | SHAKEN 073H | 08&#160;Aug&#160;25&#160;21:49&#160;UTC | false | [view](CERTS/618b83ffb285c2c03f430be1e7783fc04767222fb618affd492c968e1e834035/README.md) |
| 06&#160;Sep&#160;24&#160;19:33&#160;UTC | SHAKEN 193E | 05&#160;Nov&#160;24&#160;19:33&#160;UTC | false | [view](CERTS/723b4c8404f36d63551aaf21371f5ef5cc32ef29771ba6cdfc3443e74e43dedc/README.md) |
| 11&#160;Sep&#160;24&#160;15:51&#160;UTC | SHAKEN 8526 | 11&#160;Sep&#160;25&#160;15:51&#160;UTC | false | [view](CERTS/d6a1f4a1d2f8ce03e6dba18e0bc71b409cac0908d422f832e2571d23abfda212/README.md) |
| 16&#160;Sep&#160;24&#160;19:01&#160;UTC | SHAKEN 706J | 16&#160;Sep&#160;25&#160;19:01&#160;UTC | false | [view](CERTS/3caad270afdbb509ba024f3862f34fa12de1f441e22bfd8f9935505f568feb0d/README.md) |
| 01&#160;Oct&#160;24&#160;10:12&#160;UTC | SHAKEN 815G | 30&#160;Dec&#160;24&#160;10:12&#160;UTC | false | [view](CERTS/47d716e167310b235ba5d20c966eee2f717ed849d331f865fa68583ab8cf9761/README.md) |
| 19&#160;Nov&#160;24&#160;19:12&#160;UTC | SHAKEN 857J | 19&#160;Nov&#160;25&#160;19:12&#160;UTC | false | [view](CERTS/6bd8a0de8d6ccf1a4ad706d777d5ca1c2480f8583229be9db7428ba0362ef82a/README.md) |
| 27&#160;Mar&#160;25&#160;21:54&#160;UTC | SHAKEN 2720 | 27&#160;Mar&#160;26&#160;21:54&#160;UTC | false | [view](CERTS/5f4584f83fc32179b7a529f77d8bbb88da32b8239b508d5bea41a4d1d5282237/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 24&#160;Oct&#160;22&#160;00:00&#160;UTC | TransNexus, Inc. SHAKEN Issuing CA4 | 23&#160;Oct&#160;32&#160;23:59&#160;UTC | false | [view](CERTS/80dd12d935f46c256c7c1289a0834b21ec8f2f8c35f2864928d1e75f3a280665/README.md) |
| 24&#160;Oct&#160;22&#160;00:00&#160;UTC | TransNexus, Inc. SHAKEN Root CA2 | 23&#160;Oct&#160;42&#160;23:59&#160;UTC | false | [view](CERTS/a26e04fc786ab70b8085236b2c53f8cfbf5d0c6a5c2c9c3e9f91669fbb8ea4d5/README.md) |
| 21&#160;Mar&#160;24&#160;00:00&#160;UTC | TransNexus, Inc. SHAKEN Issuing CA5 | 20&#160;Mar&#160;34&#160;23:59&#160;UTC | false | [view](CERTS/cd50eeb8c083af686a49964a10b030048b800530edbeee8f0991388c3a79e75a/README.md) |


Generated: 02 Jun 25 03:45 UTC