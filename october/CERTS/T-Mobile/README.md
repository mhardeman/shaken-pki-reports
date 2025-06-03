# STIR/SHAKEN CA Ecosystem Compliance

## T-Mobile

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 4 potential certificate URLs were requested for retrieval
- 4 candidate certificates were parsed from the potential certificate URLs
- 0 certificates in the candidate corpus were excluded because they are duplicates
- 1 certificates in the candidate corpus were excluded because they were not valid during the target validity period
- 0 certificates in the candidate corpus were excluded because they did not chain to program trust anchors
- 3 valid certificates were tested against the remaining rules
- 1.00 issues on average found in valid but non-compliant certificates
- 100.00% of valid certificates contain one or more Error level issue
- 0.00% of valid certificates contain one or more Warning level issue
- 0.00% of valid certificates contain one or more Notice level issue
- 33.33% of valid certificates are too old to be assessed against currently enforced expectations
- 208 days is the average remaining validity of the valid certificates
- 366 days is the average initial validity of the valid certificates
- 3.00 average number of unexpired certificates per OCN observed
- 1 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 3 | [e_us_cp_subject_sn_shall](ISSUES/e_us_cp_subject_sn_shall/README.md) | US_SHAKEN_CP |

#### CA Certificates

- 3 potential certificate URLs were requested for retrieval
- 3 candidate certificates were parsed from the potential certificate URLs
- 0 certificates in the candidate corpus were excluded because they are duplicates
- 0 certificates in the candidate corpus were excluded because they were not valid during the target validity period
- 0 certificates in the candidate corpus were excluded because they did not chain to program trust anchors
- 3 valid certificates were tested against the remaining rules
- 1.00 issues on average found in valid but non-compliant certificates
- 33.33% of valid certificates contain one or more Error level issue
- 0.00% of valid certificates contain one or more Warning level issue
- 0.00% of valid certificates contain one or more Notice level issue
- 100.00% of valid certificates are too old to be assessed against currently enforced expectations
- 4958 days is the average remaining validity of the valid certificates
- 4261 days is the average initial validity of the valid certificates

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_subject_cn_ca](ISSUES/e_atis_subject_cn_ca/README.md) | ATIS1000080 |

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 01&#160;Nov&#160;22&#160;13:46&#160;UTC | SHAKEN 6529 | 01&#160;Nov&#160;23&#160;14:16&#160;UTC | true | [view](CERTS/a3bffabdf710ee8fd719f4bf09ec27341e7e9705b4ac4687b98e4d137222cf38/README.md) |
| 12&#160;Sep&#160;23&#160;14:17&#160;UTC | SHAKEN 6529 | 11&#160;Sep&#160;24&#160;14:47&#160;UTC | true | [view](CERTS/ecd9d4ee9cf6d3fa4727df3dbf725fff3b1a0928545039fc00f0a5cc84d65f13/README.md) |
| 05&#160;Aug&#160;24&#160;15:05&#160;UTC | SHAKEN 6529 | 05&#160;Aug&#160;25&#160;15:35&#160;UTC | true | [view](CERTS/a78accd6535f468392211319d17105e4372f5dde35b10cfca4d7e2e5f0d4b263/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 19&#160;Sep&#160;19&#160;20:12&#160;UTC | TMOBILE-PROD-ROOT-STIRSHAKEN-EC | 18&#160;Sep&#160;44&#160;20:12&#160;UTC | false | [view](CERTS/d54b8c44268da3eaee9c5483c289652d1bd7f82420891114475470adebf8bf1e/README.md) |
| 27&#160;Sep&#160;19&#160;17:12&#160;UTC | TMOBILE-PROD-SUB-STIRSHAKEN-EC | 25&#160;Sep&#160;24&#160;17:42&#160;UTC | false | [view](CERTS/4378a3f136510465232246b4d6a72d600db7e11117ac0e3d59c65528f47c9c4f/README.md) |
| 27&#160;Oct&#160;22&#160;21:18&#160;UTC | TMOBILE-PROD-SUB-STIRSHAKEN-EC | 26&#160;Oct&#160;27&#160;21:48&#160;UTC | true | [view](CERTS/a22dda815630c32b2fa32fb3483ded024fe4d333b6865bf47dbb00a5194472ad/README.md) |


Generated: 03 Jun 25 02:15 UTC