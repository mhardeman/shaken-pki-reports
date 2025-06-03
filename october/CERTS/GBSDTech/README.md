# STIR/SHAKEN CA Ecosystem Compliance

## GBSDTech

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 6 potential certificate URLs were requested for retrieval
- 6 candidate certificates were parsed from the potential certificate URLs
- 0 certificates in the candidate corpus were excluded because they are duplicates
- 3 certificates in the candidate corpus were excluded because they were not valid during the target validity period
- 0 certificates in the candidate corpus were excluded because they did not chain to program trust anchors
- 3 valid certificates were tested against the remaining rules
- 5.67 issues on average found in valid but non-compliant certificates
- 100.00% of valid certificates contain one or more Error level issue
- 0.00% of valid certificates contain one or more Warning level issue
- 0.00% of valid certificates contain one or more Notice level issue
- 0.00% of valid certificates are too old to be assessed against currently enforced expectations
- 562 days is the average remaining validity of the valid certificates
- 608 days is the average initial validity of the valid certificates
- 1.00 average number of unexpired certificates per OCN observed
- 3 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 2 | [e_atis_ext_certificate_policies](ISSUES/e_atis_ext_certificate_policies/README.md) | ATIS1000080 |
| 2 | [e_atis_ext_crl_distribution](ISSUES/e_atis_ext_crl_distribution/README.md) | ATIS1000080 |
| 3 | [e_atis_serial_number_size](ISSUES/e_atis_serial_number_size/README.md) | ATIS1000080 |
| 1 | [e_atis_subject_cn](ISSUES/e_atis_subject_cn/README.md) | ATIS1000080 |
| 3 | [e_atis_subject_cn_spc](ISSUES/e_atis_subject_cn_spc/README.md) | ATIS1000080 |
| 2 | [e_atis_tn_auth_list](ISSUES/e_atis_tn_auth_list/README.md) | ATIS1000080 |
| 2 | [e_atis_tn_auth_list_spc_format](ISSUES/e_atis_tn_auth_list_spc_format/README.md) | ATIS1000080 |
| 2 | [e_shaken_certificate_policies_id](ISSUES/e_shaken_certificate_policies_id/README.md) | US_SHAKEN_CP |

#### CA Certificates

- 4 potential certificate URLs were requested for retrieval
- 4 candidate certificates were parsed from the potential certificate URLs
- 0 certificates in the candidate corpus were excluded because they are duplicates
- 0 certificates in the candidate corpus were excluded because they were not valid during the target validity period
- 0 certificates in the candidate corpus were excluded because they did not chain to program trust anchors
- 4 valid certificates were tested against the remaining rules
- 2.33 issues on average found in valid but non-compliant certificates
- 75.00% of valid certificates contain one or more Error level issue
- 0.00% of valid certificates contain one or more Warning level issue
- 0.00% of valid certificates contain one or more Notice level issue
- 50.00% of valid certificates are too old to be assessed against currently enforced expectations
- 7002 days is the average remaining validity of the valid certificates
- 7300 days is the average initial validity of the valid certificates

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_ext_authority_key_identifier_ca](ISSUES/e_atis_ext_authority_key_identifier_ca/README.md) | ATIS1000080 |
| 1 | [e_atis_ext_certificate_policies_ca](ISSUES/e_atis_ext_certificate_policies_ca/README.md) | ATIS1000080 |
| 1 | [e_atis_ext_crl_distribution_ca](ISSUES/e_atis_ext_crl_distribution_ca/README.md) | ATIS1000080 |
| 2 | [e_atis_serial_number_size_ca](ISSUES/e_atis_serial_number_size_ca/README.md) | ATIS1000080 |
| 1 | [e_ext_authority_key_identifier_missing](ISSUES/e_ext_authority_key_identifier_missing/README.md) | RFC5280 |
| 1 | [e_ext_authority_key_identifier_no_key_identifier](ISSUES/e_ext_authority_key_identifier_no_key_identifier/README.md) | RFC5280 |

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 24&#160;Apr&#160;23&#160;22:53&#160;UTC | Edify SHAKEN | 23&#160;Apr&#160;24&#160;22:53&#160;UTC | true | [view](CERTS/d092ee80d10eb8c6656246f9ffa3d2100319fb217c50c8cc03e4d84e654da026/README.md) |
| 03&#160;Aug&#160;23&#160;19:55&#160;UTC | MYPBXManager SHAKEN | 02&#160;Aug&#160;26&#160;19:55&#160;UTC | true | [view](CERTS/ea5813855308274fae05fdcae622a159efa47cde2ccf87a9cdf09d9ef43d93f2/README.md) |
| 22&#160;Apr&#160;24&#160;20:43&#160;UTC | alluretelecom.com | 21&#160;Apr&#160;25&#160;20:43&#160;UTC | true | [view](CERTS/5486360ac5b339b588547ee88d42ca59ee3cdd87a0911ce2d16c3a8dd376efe0/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 05&#160;May&#160;21&#160;19:05&#160;UTC | GBSDTech SHAKEN Root CA | 30&#160;Apr&#160;41&#160;19:05&#160;UTC | false | [view](CERTS/6d2bee73a01c1c9fe92273ff8ba56e0c870b7b901cbebcc9e12226fc109e1af9/README.md) |
| 05&#160;May&#160;21&#160;20:22&#160;UTC | 1RouteGroup SHAKEN Intermediate CA | 29&#160;Apr&#160;41&#160;20:22&#160;UTC | true | [view](CERTS/99e9a67644a30ebc33ecc9aa8df6335524d49a4691164e357c5d2406b58a578e/README.md) |
| 27&#160;Dec&#160;23&#160;06:18&#160;UTC | SHAKEN 1RouteGroup Intermediate CA | 22&#160;Dec&#160;43&#160;06:18&#160;UTC | true | [view](CERTS/de6fcb6ba446b8b669a53ed338795ce54b2e3f5be20320fef1644e10fe3b9c3a/README.md) |
| 09&#160;Jul&#160;24&#160;22:39&#160;UTC | SHAKEN 1RouteGroup Intermediate CA | 04&#160;Jul&#160;44&#160;22:39&#160;UTC | true | [view](CERTS/7dea6c98003ca7bd868598f4b62b7be016f5cad5542e8fd95150225d1accf9cf/README.md) |


Generated: 03 Jun 25 02:15 UTC