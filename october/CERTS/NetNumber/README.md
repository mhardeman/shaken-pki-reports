# STIR/SHAKEN CA Ecosystem Compliance

## NetNumber

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 63 potential certificate URLs were requested for retrieval
- 63 candidate certificates were parsed from the potential certificate URLs
- 0 certificates in the candidate corpus were excluded because they are duplicates
- 30 certificates in the candidate corpus were excluded because they were not valid during the target validity period
- 0 certificates in the candidate corpus were excluded because they did not chain to program trust anchors
- 33 valid certificates were tested against the remaining rules
- 4.52 issues on average found in valid but non-compliant certificates
- 100.00% of valid certificates contain one or more Error level issue
- 0.00% of valid certificates contain one or more Warning level issue
- 0.00% of valid certificates contain one or more Notice level issue
- 0.00% of valid certificates are too old to be assessed against currently enforced expectations
- 32 days is the average remaining validity of the valid certificates
- 50 days is the average initial validity of the valid certificates
- 8.25 average number of unexpired certificates per OCN observed
- 4 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 33 | [e_atis_ext_certificate_policies](ISSUES/e_atis_ext_certificate_policies/README.md) | ATIS1000080 |
| 16 | [e_atis_ext_crl_distribution](ISSUES/e_atis_ext_crl_distribution/README.md) | ATIS1000080 |
| 17 | [e_atis_serial_number_size](ISSUES/e_atis_serial_number_size/README.md) | ATIS1000080 |
| 17 | [e_atis_subject_cn](ISSUES/e_atis_subject_cn/README.md) | ATIS1000080 |
| 33 | [e_atis_subject_cn_spc](ISSUES/e_atis_subject_cn_spc/README.md) | ATIS1000080 |
| 33 | [e_shaken_certificate_policies_id](ISSUES/e_shaken_certificate_policies_id/README.md) | US_SHAKEN_CP |

#### CA Certificates

- 3 potential certificate URLs were requested for retrieval
- 3 candidate certificates were parsed from the potential certificate URLs
- 0 certificates in the candidate corpus were excluded because they are duplicates
- 0 certificates in the candidate corpus were excluded because they were not valid during the target validity period
- 0 certificates in the candidate corpus were excluded because they did not chain to program trust anchors
- 3 valid certificates were tested against the remaining rules
- 3.00 issues on average found in valid but non-compliant certificates
- 66.67% of valid certificates contain one or more Error level issue
- 0.00% of valid certificates contain one or more Warning level issue
- 0.00% of valid certificates contain one or more Notice level issue
- 100.00% of valid certificates are too old to be assessed against currently enforced expectations
- 7146 days is the average remaining validity of the valid certificates
- 6935 days is the average initial validity of the valid certificates

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_ext_certificate_policies_ca](ISSUES/e_atis_ext_certificate_policies_ca/README.md) | ATIS1000080 |
| 2 | [e_atis_signature_algorithm_ca](ISSUES/e_atis_signature_algorithm_ca/README.md) | ATIS1000080 |
| 2 | [e_atis_subject_public_key_ca](ISSUES/e_atis_subject_public_key_ca/README.md) | ATIS1000080 |
| 1 | [e_shaken_certificate_policies_id_ca](ISSUES/e_shaken_certificate_policies_id_ca/README.md) | US_SHAKEN_CP |

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 02&#160;Sep&#160;23&#160;00:00&#160;UTC | HD CARRIER LLC | 01&#160;Oct&#160;23&#160;23:59&#160;UTC | true | [view](CERTS/917309fbf46151a26c6b51b50aca8d782b1fc809dc4f13cd6105038f8a0a60d7/README.md) |
| 16&#160;Sep&#160;23&#160;00:00&#160;UTC | HD CARRIER LLC | 15&#160;Oct&#160;23&#160;23:59&#160;UTC | true | [view](CERTS/78b56ec281b920cfa11a556303c50a6bcb3bf1020478eb0a6674d5ca0f27993f/README.md) |
| 20&#160;Sep&#160;23&#160;22:58&#160;UTC | Google SHAKEN cert 969H | 20&#160;Oct&#160;23&#160;22:58&#160;UTC | true | [view](CERTS/b668d985c40a1143cb4688ab626263a634eeadefc720f583ebc5e65ce438084e/README.md) |
| 02&#160;Oct&#160;23&#160;00:00&#160;UTC | HD CARRIER LLC | 31&#160;Oct&#160;23&#160;23:59&#160;UTC | true | [view](CERTS/b208c20dcf25f13dba943357532826488326f3ca538a67092cc56c1ed8aa70f6/README.md) |
| 13&#160;Oct&#160;23&#160;22:59&#160;UTC | Google SHAKEN cert 969H | 12&#160;Nov&#160;23&#160;22:59&#160;UTC | true | [view](CERTS/4a3cbee9d77e0d3c5aebe84d807d3eb63ddd2f14dbd6359104b80246581ffc23/README.md) |
| 16&#160;Oct&#160;23&#160;00:00&#160;UTC | HD CARRIER LLC | 14&#160;Nov&#160;23&#160;23:59&#160;UTC | true | [view](CERTS/f76f5256094c3a809b74bf7cd491bf683948f612d5131862634936ed4c3767ca/README.md) |
| 02&#160;Nov&#160;23&#160;00:00&#160;UTC | HD CARRIER LLC | 01&#160;Dec&#160;23&#160;23:59&#160;UTC | true | [view](CERTS/6ef9411ec5edc9f845f657e1e4b6adffe0c6a76b4f5e3f9d0b84c2ce9be651e4/README.md) |
| 06&#160;Nov&#160;23&#160;00:02&#160;UTC | Google SHAKEN cert 969H | 06&#160;Dec&#160;23&#160;00:02&#160;UTC | true | [view](CERTS/16f320d1971e6da38e8a26433b6d8006ff2144912ff1f128c51da37cfc2bd6c3/README.md) |
| 16&#160;Nov&#160;23&#160;00:00&#160;UTC | HD CARRIER LLC | 15&#160;Dec&#160;23&#160;23:59&#160;UTC | true | [view](CERTS/bef6faeb484fb93900c6e5c2d3988ab99efaae26939259683f81b3031aa15713/README.md) |
| 29&#160;Nov&#160;23&#160;04:01&#160;UTC | Google SHAKEN cert 969H | 29&#160;Dec&#160;23&#160;04:01&#160;UTC | true | [view](CERTS/e1b301e9be957cc7ba4f93ff5a8e59178f4922a1c1bed36eec2dac0731213a69/README.md) |
| 02&#160;Dec&#160;23&#160;00:00&#160;UTC | HD CARRIER LLC | 31&#160;Dec&#160;23&#160;23:59&#160;UTC | true | [view](CERTS/4091f69bfe4992301d59e84edd6268cfc38ed283a3d9339b9ec51ebde6dc9601/README.md) |
| 16&#160;Dec&#160;23&#160;00:00&#160;UTC | HD CARRIER LLC | 14&#160;Jan&#160;24&#160;23:59&#160;UTC | true | [view](CERTS/70f308a7f011c5aee00ea4493ea41782408424eb678beb827e5d855b7d8fc8c9/README.md) |
| 22&#160;Dec&#160;23&#160;04:03&#160;UTC | Google SHAKEN cert 969H | 21&#160;Jan&#160;24&#160;04:03&#160;UTC | true | [view](CERTS/a9d8c985511ddde5835fb1a095ea47ba42ae8dbe64b31865423bdc439930f7f1/README.md) |
| 02&#160;Jan&#160;24&#160;00:00&#160;UTC | HD CARRIER LLC | 31&#160;Jan&#160;24&#160;23:59&#160;UTC | true | [view](CERTS/1edb633693315e28634bd4afeb61b491b8c72d33dbacaa45fe70b95989ee5aef/README.md) |
| 14&#160;Jan&#160;24&#160;08:02&#160;UTC | Google SHAKEN cert 969H | 13&#160;Feb&#160;24&#160;08:02&#160;UTC | true | [view](CERTS/219583be0a46879699b163cfc1c6ee25f2fae2ea6c83a5889fd211a03ce88d44/README.md) |
| 16&#160;Jan&#160;24&#160;00:00&#160;UTC | HD CARRIER LLC | 14&#160;Feb&#160;24&#160;23:59&#160;UTC | true | [view](CERTS/d61794931ed919fde06b2ea87b472356ae5b2a87476516b62bcf6c5d58a1f996/README.md) |
| 06&#160;Feb&#160;24&#160;12:05&#160;UTC | Google SHAKEN cert 969H | 07&#160;Mar&#160;24&#160;12:05&#160;UTC | true | [view](CERTS/bcb2b91c1a3df613ba4f9e298d10bc26c44554cf155845b60106c0aea06588cb/README.md) |
| 15&#160;Apr&#160;24&#160;16:01&#160;UTC | Google SHAKEN cert 969H | 15&#160;May&#160;24&#160;16:01&#160;UTC | true | [view](CERTS/942c79935ad0f67c458b057086a0a47c1bb46210895b845d8c3789896192ef52/README.md) |
| 02&#160;May&#160;24&#160;00:00&#160;UTC | Plivo Inc | 01&#160;May&#160;25&#160;00:00&#160;UTC | true | [view](CERTS/842b9c1621617feb8d70fbe7aa3008ca7d41b51cae837e7ae72f235593062e0d/README.md) |
| 08&#160;May&#160;24&#160;20:02&#160;UTC | Google SHAKEN cert 969H | 07&#160;Jun&#160;24&#160;20:02&#160;UTC | true | [view](CERTS/02217803d9a4a17eb19d7b061b9ef92c4914dba927516ec8dbe2a5b2fe4f1265/README.md) |
| 31&#160;May&#160;24&#160;20:02&#160;UTC | Google SHAKEN cert 969H | 30&#160;Jun&#160;24&#160;20:02&#160;UTC | true | [view](CERTS/34d1e9293bfa9729ceb1313c47265f30dd51b6d9f3fa6db894fbe6ae06b560ba/README.md) |
| 23&#160;Jun&#160;24&#160;20:02&#160;UTC | Google SHAKEN cert 969H | 23&#160;Jul&#160;24&#160;20:02&#160;UTC | true | [view](CERTS/bacdabd0c4c7a80d84fcaee59d174df20d01dbc5f11bb8d9b41443bc84f63542/README.md) |
| 16&#160;Jul&#160;24&#160;00:00&#160;UTC | HD CARRIER LLC | 14&#160;Aug&#160;24&#160;23:59&#160;UTC | true | [view](CERTS/8b44aa70213e350585cc02cbc32cf32443e7c3d2a6e9110849de5bd1c4d3f080/README.md) |
| 17&#160;Jul&#160;24&#160;00:02&#160;UTC | Google SHAKEN cert 969H | 16&#160;Aug&#160;24&#160;00:02&#160;UTC | true | [view](CERTS/22e96f252ebf13df4ef06065fa492dff50a21f7fd78cc2ea1375081985431050/README.md) |
| 02&#160;Aug&#160;24&#160;00:00&#160;UTC | HD CARRIER LLC | 31&#160;Aug&#160;24&#160;23:59&#160;UTC | true | [view](CERTS/d908104498da62c7320b01c47ba0c84006483971cfcaf10ecf40336551fd2c15/README.md) |
| 09&#160;Aug&#160;24&#160;04:01&#160;UTC | Google SHAKEN cert 969H | 08&#160;Sep&#160;24&#160;04:01&#160;UTC | true | [view](CERTS/280809a53471d29f3ce68f5222ec5f15928109ccdf50e8aaa393b31a1b2bb991/README.md) |
| 16&#160;Aug&#160;24&#160;00:00&#160;UTC | HD CARRIER LLC | 14&#160;Sep&#160;24&#160;23:59&#160;UTC | true | [view](CERTS/0778cb5231bc65aa1eb179da12669b82d11ca974da3e62e71ebc5c05abe76c4e/README.md) |
| 01&#160;Sep&#160;24&#160;08:03&#160;UTC | Google SHAKEN cert 969H | 01&#160;Oct&#160;24&#160;08:03&#160;UTC | true | [view](CERTS/97dc7302c4f0f65dcd2cb346cbb8ccbbbd911e369bf5cb93a4d80e499bcca294/README.md) |
| 02&#160;Sep&#160;24&#160;00:00&#160;UTC | HD CARRIER LLC | 01&#160;Oct&#160;24&#160;23:59&#160;UTC | true | [view](CERTS/8d2d61fe643579a3a9cbe7f6293dac819e0959fbebfe74735b5e8ed66e52692d/README.md) |
| 16&#160;Sep&#160;24&#160;00:00&#160;UTC | HD CARRIER LLC | 15&#160;Oct&#160;24&#160;23:59&#160;UTC | true | [view](CERTS/528174dd9b29bfaf6a2a78c83c1de4fead01af5b8f18fd6980e71d4558b5aeab/README.md) |
| 24&#160;Sep&#160;24&#160;12:01&#160;UTC | Google SHAKEN cert 969H | 24&#160;Oct&#160;24&#160;12:01&#160;UTC | true | [view](CERTS/69219f6998113a47315877ee97d5d31000bb200bb8be146d97e62c1bd933c062/README.md) |
| 02&#160;Oct&#160;24&#160;00:00&#160;UTC | HD CARRIER LLC | 31&#160;Oct&#160;24&#160;23:59&#160;UTC | true | [view](CERTS/f6b414f509f7e782c90747f0964d246fd7c8ea9ad236caf99d97320e6f11fc01/README.md) |
| 02&#160;Oct&#160;24&#160;15:56&#160;UTC | DISH Wireless L.L.C.SHAKEN.490J | 02&#160;Oct&#160;25&#160;15:56&#160;UTC | true | [view](CERTS/0f55e9a64c9e80bd8d9ad8b5e8324e6f842dc193a2b81e708a45dfc4f41d96c8/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 12&#160;Jul&#160;21&#160;23:25&#160;UTC | NetNumber SHAKEN Root CA | 07&#160;Jul&#160;41&#160;23:25&#160;UTC | false | [view](CERTS/7ac80e8481ecb019dc95484016842db78686069efbc0f703e7f39310217b6157/README.md) |
| 27&#160;Sep&#160;21&#160;19:45&#160;UTC | NetNumber SHAKEN Root CA 1 | 21&#160;Sep&#160;46&#160;19:45&#160;UTC | true | [view](CERTS/2dd1386ca717f31d550b35b9bce9daa9b02483bcdb98bdfcfca07202276136d7/README.md) |
| 29&#160;Sep&#160;21&#160;13:22&#160;UTC | NetNumber SHAKEN Root Intermediate CA 1 | 26&#160;Sep&#160;33&#160;13:22&#160;UTC | true | [view](CERTS/e449803766edf02ab50b034dd7e89e54efd332cce87688a032f89b340d039878/README.md) |


Generated: 03 Jun 25 02:15 UTC