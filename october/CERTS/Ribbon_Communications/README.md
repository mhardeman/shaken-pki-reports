# STIR/SHAKEN CA Ecosystem Compliance

## Ribbon Communications

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 22 certificates were included in the corpus being tested
- 0 certificates in the corpus were skipped because they are duplicates
- 21 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 1 certificates being tested against the remaining rules
- 1.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 185 days is the average remaining validity for the certificates in the corpus
- 365 days is the average initial validity for the certificates in the corpus
- 1 certificates expire in the next 30 days
- 1.00 average number of unexpired certificates per OCN observed
- 1 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_ext_crl_distribution_struct](ISSUES/e_atis_ext_crl_distribution_struct/README.md) | ATIS1000080 |

#### CA Certificates

- 3 certificates were included in the corpus being tested
- 0 certificates in the corpus were skipped because they are duplicates
- 0 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 3 certificates being tested against the remaining rules
- 1.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 66.67% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 66.67% of certificates are too old to be assessed against currently enforced expectations
- 6387 days is the average remaining validity for the certificates in the corpus
- 5966 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_ext_crl_distribution_ca](ISSUES/e_atis_ext_crl_distribution_ca/README.md) | ATIS1000080 |
| 1 | [e_atis_ext_crl_distribution_struct_ca](ISSUES/e_atis_ext_crl_distribution_struct_ca/README.md) | ATIS1000080 |

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 06&#160;Jun&#160;24&#160;13:33&#160;UTC | Peoples SHAKEN 2130 | 06&#160;Jun&#160;25&#160;13:33&#160;UTC | true | [view](CERTS/506e5980d9b8f24ac2c781f15c58fcc50dd50c9f82d8aac2ac72967211f262db/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 13&#160;May&#160;21&#160;00:00&#160;UTC | SHAKEN Ribbon Issuing CA | 12&#160;May&#160;33&#160;23:59&#160;UTC | true | [view](CERTS/05a71a04eaedbdf4b0534f40768616d7c19c8deb5a3aefd1f4a04b3aab55a48f/README.md) |
| 13&#160;May&#160;21&#160;00:00&#160;UTC | SHAKEN Ribbon Root CA | 12&#160;May&#160;46&#160;23:59&#160;UTC | false | [view](CERTS/7c2799d3642d04f04fe667c3ab251c18689af323acdc43b2fa5f3dc89e3a0f14/README.md) |
| 12&#160;Mar&#160;24&#160;00:00&#160;UTC | SHAKEN Ribbon Issuing CA 2 | 11&#160;Mar&#160;36&#160;23:59&#160;UTC | true | [view](CERTS/2b48949bed753b3edc3645a638704bd1e708cd047117e3fe8af6cb144fa3a8c5/README.md) |


Generated: 02 Jun 25 01:01 UTC