# STIR/SHAKEN CA Ecosystem Compliance

## Comcast

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 87 certificates were included in the corpus being tested
- 0 certificates in the corpus were skipped because they are duplicates
- 59 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 28 certificates being tested against the remaining rules
- 2.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 30 days is the average remaining validity for the certificates in the corpus
- 30 days is the average initial validity for the certificates in the corpus
- 28 certificates expire in the next 30 days
- 28.00 average number of unexpired certificates per OCN observed
- 1 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 28 | [e_atis_ext_crl_distribution_struct](ISSUES/e_atis_ext_crl_distribution_struct/README.md) | ATIS1000080 |
| 28 | [e_atis_serial_number_size](ISSUES/e_atis_serial_number_size/README.md) | ATIS1000080 |

#### CA Certificates

- 2 certificates were included in the corpus being tested
- 0 certificates in the corpus were skipped because they are duplicates
- 0 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 2 certificates being tested against the remaining rules
- 2.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 50.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 50.00% of certificates are too old to be assessed against currently enforced expectations
- 6666 days is the average remaining validity for the certificates in the corpus
- 7300 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_ext_crl_distribution_struct_ca](ISSUES/e_atis_ext_crl_distribution_struct_ca/README.md) | ATIS1000080 |
| 1 | [e_atis_serial_number_size_ca](ISSUES/e_atis_serial_number_size_ca/README.md) | ATIS1000080 |

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 03&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 02&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/32e593a0a9bdaabcbe341430b7ea1764afe5759fdd52fdda381bfade46288ca8/README.md) |
| 04&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 03&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/aa5a8c57d6b052cf61cf105880b62f75609e34b3cb444af61dc68c1d98b8d95b/README.md) |
| 05&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 04&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/406c7d391aa38f45f10a119d417fa4a54c2a588dde3a69d188600ec9650c6b35/README.md) |
| 06&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 05&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/ffab69fefce217ff4c096887d48d3778855b898b78756ecc390b542446fe0c5a/README.md) |
| 07&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 06&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/3672479af0ec3e9fc6ff93c25e49afb3191e1dfdf77862a0e9d933452a2c215a/README.md) |
| 08&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 07&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/7025c070e59506272f6c511f4a3691d7ed795041b6ffc5a5bad884a32101bfa7/README.md) |
| 09&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 08&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/fdbad88c364069585d91c1346dbfec1d344e2b2945bf6ae2ba3eeb13565d3537/README.md) |
| 10&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 09&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/cddb06a2ef02bd30ffdbf35fb9a242066217eba86389fbe638779fa51e6712e9/README.md) |
| 11&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 10&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/2201739db2f5f989a7f4a4cab3c31307ebd5813fd6472252600923cd4953616c/README.md) |
| 12&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 11&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/cffbd5f5f23fc76c06af85b46e58b982c1cdf825321a800330197a312de22ab3/README.md) |
| 13&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 12&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/23463e18eb075d2c12e39f45bfd97f0840af13bc0470c0d2b7e6aea2faff0422/README.md) |
| 14&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 13&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/296473a45f0df18b646a7ade22acda669b5bc1a18653929ad10bcf00e2e745d7/README.md) |
| 15&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 14&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/ee37e65ef31d76a6756555779ade44056b85e4aa0f4716ba7745ab0dafaf4b03/README.md) |
| 16&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 15&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/ee5af57b1ae8058b27dcb3ebb1c3b84ad3b2f0d9ec9c58672328b051188a5912/README.md) |
| 17&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 16&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/b541479a06e65e6953bcc08eace51479d983aef07b43876aa8b25a550688fd94/README.md) |
| 18&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 17&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/b8c557a7cb44a98379c8929c618d0db2c4b5018d13cf70c391e3d47c56d302f5/README.md) |
| 19&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 18&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/8f8786bd7946dab1e40f13c55715c09da6dd6ec9cdfa1ae5ea9595c976d479fb/README.md) |
| 20&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 19&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/000e234decbfd2f178398648063ac5e37417709087285f2af0a7f5ac4818ed48/README.md) |
| 21&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 20&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/2d7b0d1230096c0efd5e0ce880da4d78825ff61aa1094d9a02a68b64cedc8dba/README.md) |
| 22&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 21&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/ecdad80fc7370ec387bd222a2d79131b8d48d78936c88a9ea2102bb8510ec7d0/README.md) |
| 23&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 22&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/c22212d96be067eec2abe9da116194d5b1254d69b8d545b5cc13cff417ba8b6e/README.md) |
| 24&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 23&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/1a147375731c538addb8d159db352024495f8b4fd9fc88ea17e9419487016ae7/README.md) |
| 25&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 24&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/9cf86292bf8261a9d49b41eac3e5eb75e2f61ed6d2bf912d35a7bdf8107fd490/README.md) |
| 26&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 25&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/a1d4f1c3b59263783f1cea608a7de6cd4fcf93a503cf1954034b9fcde9b0e9e9/README.md) |
| 27&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 26&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/7cb0a929ccf02283621fd20fd392f4b6b8e209f729097ee979b63fa65cf6dc93/README.md) |
| 28&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 27&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/a4aa05756cf19ffda86c926763e8910ca0b8e3c00a63ab89b1a376bc5202d05f/README.md) |
| 29&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 28&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/9f73acf34e95c165f47e06ff50bd7bc9a6f53903d821a957c8c935a2c1e2e54d/README.md) |
| 30&#160;May&#160;25&#160;08:56&#160;UTC | SHAKEN 318J | 29&#160;Jun&#160;25&#160;08:56&#160;UTC | true | [view](CERTS/2e363445142eb76c5f44c8b0f3d40df8c761dccaf4fb9698b9c17a2b63750e5e/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 17&#160;Mar&#160;20&#160;14:45&#160;UTC | Comcast SHAKEN Root CA | 12&#160;Mar&#160;40&#160;14:45&#160;UTC | false | [view](CERTS/b1132c5f12c3ca4d2ff119f2df99544336eb1703512ac99cc42d596e25125bbd/README.md) |
| 11&#160;Jan&#160;24&#160;02:59&#160;UTC | Comcast SHAKEN Intermediate CA | 06&#160;Jan&#160;44&#160;02:59&#160;UTC | true | [view](CERTS/25af737667ed8b05cb8b8e7f44b2d7b5861551bea95ec48a73306ec75a92a662/README.md) |


Generated: 01 Jun 25 21:52 UTC