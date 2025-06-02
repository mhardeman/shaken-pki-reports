# STIR/SHAKEN CA Ecosystem Compliance

## T-Mobile

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 4 certificates were included in the corpus being tested
- 0 certificates in the corpus were skipped because they are duplicates
- 0 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 4 certificates being tested against the remaining rules
- 1.75 issues on average found in unexpired, trusted, and non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 50.00% of certificates are too old to be assessed against currently enforced expectations
- 240 days is the average remaining validity for the certificates in the corpus
- 366 days is the average initial validity for the certificates in the corpus
- 3 certificates expire in the next 30 days
- 4.00 average number of unexpired certificates per OCN observed
- 1 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_ext_basic_constraints](ISSUES/e_atis_ext_basic_constraints/README.md) | ATIS1000080 |
| 1 | [e_atis_subject_cn](ISSUES/e_atis_subject_cn/README.md) | ATIS1000080 |
| 1 | [e_atis_subject_cn_spc](ISSUES/e_atis_subject_cn_spc/README.md) | ATIS1000080 |
| 1 | [e_shaken_certificate_policies_id](ISSUES/e_shaken_certificate_policies_id/README.md) | US_SHAKEN_CP |
| 3 | [e_us_cp_subject_sn_shall](ISSUES/e_us_cp_subject_sn_shall/README.md) | US_SHAKEN_CP |

#### CA Certificates

- 3 certificates were included in the corpus being tested
- 0 certificates in the corpus were skipped because they are duplicates
- 0 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 3 certificates being tested against the remaining rules
- 1.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 33.33% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 100.00% of certificates are too old to be assessed against currently enforced expectations
- 4958 days is the average remaining validity for the certificates in the corpus
- 4261 days is the average initial validity for the certificates in the corpus
- 1 certificates expire in the next 30 days

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_subject_cn_ca](ISSUES/e_atis_subject_cn_ca/README.md) | ATIS1000080 |

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 14&#160;Jul&#160;22&#160;21:05&#160;UTC | cert.stir.t-mobile.com | 14&#160;Jul&#160;23&#160;21:35&#160;UTC | true | [view](CERTS/7f653e15453416082531011acd1d7dad4f664ddf5124f73e27d841138f4a89f8/README.md) |
| 01&#160;Nov&#160;22&#160;13:46&#160;UTC | SHAKEN 6529 | 01&#160;Nov&#160;23&#160;14:16&#160;UTC | true | [view](CERTS/a3bffabdf710ee8fd719f4bf09ec27341e7e9705b4ac4687b98e4d137222cf38/README.md) |
| 12&#160;Sep&#160;23&#160;14:17&#160;UTC | SHAKEN 6529 | 11&#160;Sep&#160;24&#160;14:47&#160;UTC | true | [view](CERTS/ecd9d4ee9cf6d3fa4727df3dbf725fff3b1a0928545039fc00f0a5cc84d65f13/README.md) |
| 05&#160;Aug&#160;24&#160;15:05&#160;UTC | SHAKEN 6529 | 05&#160;Aug&#160;25&#160;15:35&#160;UTC | true | [view](CERTS/a78accd6535f468392211319d17105e4372f5dde35b10cfca4d7e2e5f0d4b263/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 19&#160;Sep&#160;19&#160;20:12&#160;UTC | TMOBILE-PROD-ROOT-STIRSHAKEN-EC | 18&#160;Sep&#160;44&#160;20:12&#160;UTC | false | [view](CERTS/d54b8c44268da3eaee9c5483c289652d1bd7f82420891114475470adebf8bf1e/README.md) |
| 27&#160;Sep&#160;19&#160;17:12&#160;UTC | TMOBILE-PROD-SUB-STIRSHAKEN-EC | 25&#160;Sep&#160;24&#160;17:42&#160;UTC | false | [view](CERTS/4378a3f136510465232246b4d6a72d600db7e11117ac0e3d59c65528f47c9c4f/README.md) |
| 27&#160;Oct&#160;22&#160;21:18&#160;UTC | TMOBILE-PROD-SUB-STIRSHAKEN-EC | 26&#160;Oct&#160;27&#160;21:48&#160;UTC | true | [view](CERTS/a22dda815630c32b2fa32fb3483ded024fe4d333b6865bf47dbb00a5194472ad/README.md) |


Generated: 02 Jun 25 18:58 UTC