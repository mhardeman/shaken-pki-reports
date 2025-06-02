# STIR/SHAKEN CA Ecosystem Compliance

## Sansay

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 1932 certificates were included in the corpus being tested
- 10 certificates in the corpus were skipped because they are duplicates
- 1906 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 16 certificates being tested against the remaining rules
- 1.56 issues on average found in unexpired, trusted, and non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 322 days is the average remaining validity for the certificates in the corpus
- 333 days is the average initial validity for the certificates in the corpus
- 5 certificates expire in the next 30 days
- 1.14 average number of unexpired certificates per OCN observed
- 14 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 8 | [e_atis_ext_crl_distribution_struct](ISSUES/e_atis_ext_crl_distribution_struct/README.md) | ATIS1000080 |
| 9 | [e_atis_subject_cn_spc](ISSUES/e_atis_subject_cn_spc/README.md) | ATIS1000080 |
| 4 | [e_shaken_certificate_policies_id](ISSUES/e_shaken_certificate_policies_id/README.md) | US_SHAKEN_CP |
| 4 | [e_us_cp_subject_sn_shall](ISSUES/e_us_cp_subject_sn_shall/README.md) | US_SHAKEN_CP |

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
| 21&#160;Jun&#160;24&#160;20:19&#160;UTC | SHAKEN Connexum LLC 203K | 21&#160;Jun&#160;25&#160;20:19&#160;UTC | true | [view](CERTS/c405face9873a72f5ec4f1bc395a4124d7cfbf080a704060ebe5e9bf7a07d62d/README.md) |
| 29&#160;Jun&#160;24&#160;00:30&#160;UTC | SHAKEN Bek Communications Cooperative 1604 | 28&#160;Jun&#160;25&#160;00:30&#160;UTC | true | [view](CERTS/17a28f83e865e75a97e9a5a4b777355b93960ccf3b65a1d13e06693a0d03e399/README.md) |
| 01&#160;Jul&#160;24&#160;16:21&#160;UTC | SHAKEN Mercury Access Solutions 634K | 01&#160;Jul&#160;25&#160;16:21&#160;UTC | true | [view](CERTS/70cc27d2e747142c3446b6133993989be4e1ff3fe4d25b137def2745fc173d19/README.md) |
| 10&#160;Jul&#160;24&#160;19:13&#160;UTC | SHAKEN 958K SaveVoip LLC | 10&#160;Jul&#160;25&#160;19:13&#160;UTC | true | [view](CERTS/e78654b5bea29fa67df948244d36aefdad852322d5c375149c5ce147430f2b95/README.md) |
| 19&#160;Jul&#160;24&#160;17:35&#160;UTC | SHAKEN IPBTel 535K | 19&#160;Jul&#160;25&#160;17:35&#160;UTC | true | [view](CERTS/c777a6bdc52c45c7f7f66f40b765c70e167fe34b8cd36fea8bc287b20cb7d80e/README.md) |
| 10&#160;Aug&#160;24&#160;19:01&#160;UTC | SHAKEN 688K Call Hub Inc. | 10&#160;Aug&#160;25&#160;19:01&#160;UTC | true | [view](CERTS/d8fe53673498502aa06d1deb531144cdeac93dba56e9c7094fef9fe192b5b14c/README.md) |
| 19&#160;Aug&#160;24&#160;18:17&#160;UTC | SHAKEN 203K Connexum LLC | 19&#160;Aug&#160;25&#160;18:17&#160;UTC | true | [view](CERTS/901fcdbe4946f6c9f2f338dd125112cf748dec475f4052db54963ef4e3c55d1f/README.md) |
| 22&#160;Aug&#160;24&#160;16:18&#160;UTC | SHAKEN 688K Call Hub Inc. | 22&#160;Aug&#160;25&#160;16:18&#160;UTC | true | [view](CERTS/c9514ae8afe29c81cba005d0e97ddd87c0588caca1e39a20368d4f872619984d/README.md) |
| 22&#160;Aug&#160;24&#160;17:42&#160;UTC | SHAKEN Contactivity Corp. 711K | 22&#160;Aug&#160;25&#160;17:42&#160;UTC | true | [view](CERTS/6f93189ff71fccb600f52ac36ac52ec2d7ff916d7bf9e9d3a8eb8ae6d4c7cd31/README.md) |
| 24&#160;Sep&#160;24&#160;17:01&#160;UTC | SHAKEN Sangoma 777G | 24&#160;Sep&#160;25&#160;17:01&#160;UTC | true | [view](CERTS/793541492ac2787c6052d4a9cfb63c7f6aed20d149d3d5e173aa531a5d1bb71b/README.md) |
| 01&#160;Oct&#160;24&#160;15:06&#160;UTC | SHAKEN Kloud 7 LLC 214K | 01&#160;Oct&#160;25&#160;15:06&#160;UTC | true | [view](CERTS/67fe5061b5b9244cdb233b8efd82fffde4a42fc661cce8860b6717318181ca80/README.md) |
| 19&#160;Nov&#160;24&#160;17:43&#160;UTC | SHAKEN Drop Inc 258K | 19&#160;Nov&#160;25&#160;17:43&#160;UTC | true | [view](CERTS/6c7656a8a3e1ef4913ac75f3e4ce64822394ba9b6aaeab2501d2ed14af683182/README.md) |
| 23&#160;Apr&#160;25&#160;00:00&#160;UTC | SHAKEN 895K | 23&#160;Apr&#160;26&#160;00:00&#160;UTC | true | [view](CERTS/7f9656b8ac82c3a3d571c6314b7b0546d1e34dfe134b5a36f83229bc89455078/README.md) |
| 28&#160;Apr&#160;25&#160;12:06&#160;UTC | SHAKEN 521K | 25&#160;Oct&#160;25&#160;12:06&#160;UTC | true | [view](CERTS/6a8757a6e06800b00d63f0c91e476564b872813595a42196c59d6a4f2b989b0b/README.md) |
| 26&#160;May&#160;25&#160;06:00&#160;UTC | SHAKEN Convoso 758J | 30&#160;Jun&#160;25&#160;06:00&#160;UTC | true | [view](CERTS/02ab6c36d71b7282bd6120b953c088bc9380eda096e8f1983bedb3d4f4ad5675/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 21&#160;Aug&#160;20&#160;01:22&#160;UTC | SHAKEN Sansay Root CA US | 16&#160;Aug&#160;40&#160;01:22&#160;UTC | false | [view](CERTS/8356d251b255f4ac3fd108bb79be4c02dcea2d3b13d138892bdb3a70cbe6a343/README.md) |
| 02&#160;Sep&#160;22&#160;20:53&#160;UTC | SHAKEN Sansay Intermediate CA US WEST 1 | 31&#160;Aug&#160;29&#160;20:53&#160;UTC | false | [view](CERTS/4b1dfdba2b1e4bbffbf900a20f1f6f7befbef0008b963e4922a64469cb97d24b/README.md) |


Generated: 02 Jun 25 01:01 UTC