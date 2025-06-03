# STIR/SHAKEN CA Ecosystem Compliance

## Sansay

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 5 potential certificate URLs were requested for retrieval
- 5 candidate certificates were parsed from the potential certificate URLs
- 0 certificates in the candidate corpus were excluded because they are duplicates
- 0 certificates in the candidate corpus were excluded because they are outside-target-validity-period
- 0 certificates in the candidate corpus were excluded because they did not chain to trust anchors
- 5 valid certificates being tested against the remaining rules
- 1.60 issues on average found in valid but non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 316 days is the average remaining validity for the valid certificates
- 365 days is the average initial validity for the valid certificates
- 1.67 average number of unexpired certificates per OCN observed
- 3 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 2 | [e_atis_ext_crl_distribution_struct](ISSUES/e_atis_ext_crl_distribution_struct/README.md) | ATIS1000080 |
| 3 | [e_atis_subject_cn_spc](ISSUES/e_atis_subject_cn_spc/README.md) | ATIS1000080 |
| 3 | [e_us_cp_subject_sn_shall](ISSUES/e_us_cp_subject_sn_shall/README.md) | US_SHAKEN_CP |

#### CA Certificates

- 2 potential certificate URLs were requested for retrieval
- 2 candidate certificates were parsed from the potential certificate URLs
- 0 certificates in the candidate corpus were excluded because they are duplicates
- 0 certificates in the candidate corpus were excluded because they are outside-target-validity-period
- 0 certificates in the candidate corpus were excluded because they did not chain to trust anchors
- 2 valid certificates being tested against the remaining rules
- 0.00 issues on average found in valid but non-compliant certificates
- 0.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 100.00% of certificates are too old to be assessed against currently enforced expectations
- 5136 days is the average remaining validity for the valid certificates
- 4928 days is the average initial validity for the valid certificates

No error, warning, or notice level issues were found

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 05&#160;Apr&#160;23&#160;16:27&#160;UTC | SHAKEN Swift Telco LLC 452K | 04&#160;Apr&#160;24&#160;16:27&#160;UTC | true | [view](CERTS/947b46067a639b79ff82ab3f48c453e4af7cc6d6036f6d66a742cc935bc8a35e/README.md) |
| 11&#160;Aug&#160;23&#160;11:45&#160;UTC | SHAKEN Call Hub Inc. 688K | 10&#160;Aug&#160;24&#160;11:45&#160;UTC | true | [view](CERTS/598f41e0ff84df174314d76b406d85a0f3875aa68f1266c268b98c22f4ee912b/README.md) |
| 06&#160;Dec&#160;23&#160;03:21&#160;UTC | SHAKEN Bulk Solutions, LLC 644J | 05&#160;Dec&#160;24&#160;03:21&#160;UTC | true | [view](CERTS/ab634090acf3c02b7dcd70995171b6522e39c5a72d73fe26e32e99b1acd716d7/README.md) |
| 10&#160;Aug&#160;24&#160;19:01&#160;UTC | SHAKEN 688K Call Hub Inc. | 10&#160;Aug&#160;25&#160;19:01&#160;UTC | true | [view](CERTS/d8fe53673498502aa06d1deb531144cdeac93dba56e9c7094fef9fe192b5b14c/README.md) |
| 22&#160;Aug&#160;24&#160;16:18&#160;UTC | SHAKEN 688K Call Hub Inc. | 22&#160;Aug&#160;25&#160;16:18&#160;UTC | true | [view](CERTS/c9514ae8afe29c81cba005d0e97ddd87c0588caca1e39a20368d4f872619984d/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 21&#160;Aug&#160;20&#160;01:22&#160;UTC | SHAKEN Sansay Root CA US | 16&#160;Aug&#160;40&#160;01:22&#160;UTC | false | [view](CERTS/8356d251b255f4ac3fd108bb79be4c02dcea2d3b13d138892bdb3a70cbe6a343/README.md) |
| 02&#160;Sep&#160;22&#160;20:53&#160;UTC | SHAKEN Sansay Intermediate CA US WEST 1 | 31&#160;Aug&#160;29&#160;20:53&#160;UTC | false | [view](CERTS/4b1dfdba2b1e4bbffbf900a20f1f6f7befbef0008b963e4922a64469cb97d24b/README.md) |


Generated: 03 Jun 25 01:30 UTC