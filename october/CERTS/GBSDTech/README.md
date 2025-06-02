# STIR/SHAKEN CA Ecosystem Compliance

## GBSDTech

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 6 certificates were included in the corpus being tested
- 0 certificates in the corpus were skipped because they are duplicates
- 3 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 3 certificates being tested against the remaining rules
- 4.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 745 days is the average remaining validity for the certificates in the corpus
- 851 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days
- 1.00 average number of unexpired certificates per OCN observed
- 3 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_ext_certificate_policies](ISSUES/e_atis_ext_certificate_policies/README.md) | ATIS1000080 |
| 1 | [e_atis_ext_crl_distribution](ISSUES/e_atis_ext_crl_distribution/README.md) | ATIS1000080 |
| 3 | [e_atis_serial_number_size](ISSUES/e_atis_serial_number_size/README.md) | ATIS1000080 |
| 1 | [e_atis_subject_cn](ISSUES/e_atis_subject_cn/README.md) | ATIS1000080 |
| 3 | [e_atis_subject_cn_spc](ISSUES/e_atis_subject_cn_spc/README.md) | ATIS1000080 |
| 1 | [e_atis_tn_auth_list](ISSUES/e_atis_tn_auth_list/README.md) | ATIS1000080 |
| 1 | [e_atis_tn_auth_list_spc_format](ISSUES/e_atis_tn_auth_list_spc_format/README.md) | ATIS1000080 |
| 1 | [e_shaken_certificate_policies_id](ISSUES/e_shaken_certificate_policies_id/README.md) | US_SHAKEN_CP |

#### CA Certificates

- 4 certificates were included in the corpus being tested
- 0 certificates in the corpus were skipped because they are duplicates
- 0 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 4 certificates being tested against the remaining rules
- 2.33 issues on average found in unexpired, trusted, and non-compliant certificates
- 75.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 50.00% of certificates are too old to be assessed against currently enforced expectations
- 7002 days is the average remaining validity for the certificates in the corpus
- 7300 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days

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
| 03&#160;Aug&#160;23&#160;19:55&#160;UTC | MYPBXManager SHAKEN | 02&#160;Aug&#160;26&#160;19:55&#160;UTC | true | [view](CERTS/ea5813855308274fae05fdcae622a159efa47cde2ccf87a9cdf09d9ef43d93f2/README.md) |
| 11&#160;Feb&#160;25&#160;18:42&#160;UTC | ccctelecom.com | 10&#160;Feb&#160;26&#160;18:42&#160;UTC | true | [view](CERTS/7ed6c39c5ac9266fe9fcc9b777f7231de3c57af2fa94edc9073ce13a2b61ff99/README.md) |
| 05&#160;May&#160;25&#160;16:48&#160;UTC | FracTEL LLC SHAKEN | 04&#160;May&#160;28&#160;16:48&#160;UTC | true | [view](CERTS/703a1ebb0715a4bfcacac752f2d1fba1b03aa25e770fbab46df5f89e4d004063/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 05&#160;May&#160;21&#160;19:05&#160;UTC | GBSDTech SHAKEN Root CA | 30&#160;Apr&#160;41&#160;19:05&#160;UTC | false | [view](CERTS/6d2bee73a01c1c9fe92273ff8ba56e0c870b7b901cbebcc9e12226fc109e1af9/README.md) |
| 05&#160;May&#160;21&#160;20:22&#160;UTC | 1RouteGroup SHAKEN Intermediate CA | 29&#160;Apr&#160;41&#160;20:22&#160;UTC | true | [view](CERTS/99e9a67644a30ebc33ecc9aa8df6335524d49a4691164e357c5d2406b58a578e/README.md) |
| 27&#160;Dec&#160;23&#160;06:18&#160;UTC | SHAKEN 1RouteGroup Intermediate CA | 22&#160;Dec&#160;43&#160;06:18&#160;UTC | true | [view](CERTS/de6fcb6ba446b8b669a53ed338795ce54b2e3f5be20320fef1644e10fe3b9c3a/README.md) |
| 09&#160;Jul&#160;24&#160;22:39&#160;UTC | SHAKEN 1RouteGroup Intermediate CA | 04&#160;Jul&#160;44&#160;22:39&#160;UTC | true | [view](CERTS/7dea6c98003ca7bd868598f4b62b7be016f5cad5542e8fd95150225d1accf9cf/README.md) |


Generated: 02 Jun 25 01:01 UTC