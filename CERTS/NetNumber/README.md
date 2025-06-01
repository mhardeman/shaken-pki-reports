# STIR/SHAKEN CA Ecosystem Compliance

## NetNumber

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 16 certificates were included in the corpus being tested
- 0 certificates in the corpus were skipped because they are duplicates
- 11 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 5 certificates being tested against the remaining rules
- 4.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 137 days is the average remaining validity for the certificates in the corpus
- 164 days is the average initial validity for the certificates in the corpus
- 3 certificates expire in the next 30 days
- 1.00 average number of unexpired certificates per OCN observed
- 5 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 5 | [e_atis_ext_certificate_policies](ISSUES/e_atis_ext_certificate_policies/README.md) | ATIS1000080 |
| 2 | [e_atis_ext_crl_distribution](ISSUES/e_atis_ext_crl_distribution/README.md) | ATIS1000080 |
| 1 | [e_atis_serial_number_size](ISSUES/e_atis_serial_number_size/README.md) | ATIS1000080 |
| 2 | [e_atis_subject_cn](ISSUES/e_atis_subject_cn/README.md) | ATIS1000080 |
| 5 | [e_atis_subject_cn_spc](ISSUES/e_atis_subject_cn_spc/README.md) | ATIS1000080 |
| 5 | [e_shaken_certificate_policies_id](ISSUES/e_shaken_certificate_policies_id/README.md) | US_SHAKEN_CP |

#### CA Certificates

- 3 certificates were included in the corpus being tested
- 0 certificates in the corpus were skipped because they are duplicates
- 0 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 3 certificates being tested against the remaining rules
- 3.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 66.67% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 100.00% of certificates are too old to be assessed against currently enforced expectations
- 7147 days is the average remaining validity for the certificates in the corpus
- 6935 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days

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
| 02&#160;Oct&#160;24&#160;15:56&#160;UTC | DISH Wireless L.L.C.SHAKEN.490J | 02&#160;Oct&#160;25&#160;15:56&#160;UTC | true | [view](CERTS/0f55e9a64c9e80bd8d9ad8b5e8324e6f842dc193a2b81e708a45dfc4f41d96c8/README.md) |
| 09&#160;Apr&#160;25&#160;00:00&#160;UTC | Plivo Inc | 08&#160;Apr&#160;26&#160;00:00&#160;UTC | true | [view](CERTS/bbe59f37361998b1c699b9ba5e63173f244c486d6ab8db6dc9edc8cc259c9d00/README.md) |
| 07&#160;May&#160;25&#160;07:00&#160;UTC | Baltimore-Washington Telephone Company SHAKEN cert 8697 | 06&#160;Jun&#160;25&#160;07:00&#160;UTC | true | [view](CERTS/1d020d2aef8c766d82be4e7221ee3ac1c0cfa03c3e4c867ca3c77f14403fe0ef/README.md) |
| 14&#160;May&#160;25&#160;00:02&#160;UTC | Google SHAKEN cert 969H | 13&#160;Jun&#160;25&#160;00:02&#160;UTC | true | [view](CERTS/b8f986e02dc82c42615acd258df99fc9038632cac5c63ce3b65bed891505f7cf/README.md) |
| 16&#160;May&#160;25&#160;00:00&#160;UTC | HD CARRIER LLC | 14&#160;Jun&#160;25&#160;23:59&#160;UTC | true | [view](CERTS/b56dac4fd4d3e49443fc841b22700f21ccbd3a80c2e5029c2adf59d432a2ac8c/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 12&#160;Jul&#160;21&#160;23:25&#160;UTC | NetNumber SHAKEN Root CA | 07&#160;Jul&#160;41&#160;23:25&#160;UTC | false | [view](CERTS/7ac80e8481ecb019dc95484016842db78686069efbc0f703e7f39310217b6157/README.md) |
| 27&#160;Sep&#160;21&#160;19:45&#160;UTC | NetNumber SHAKEN Root CA 1 | 21&#160;Sep&#160;46&#160;19:45&#160;UTC | true | [view](CERTS/2dd1386ca717f31d550b35b9bce9daa9b02483bcdb98bdfcfca07202276136d7/README.md) |
| 29&#160;Sep&#160;21&#160;13:22&#160;UTC | NetNumber SHAKEN Root Intermediate CA 1 | 26&#160;Sep&#160;33&#160;13:22&#160;UTC | true | [view](CERTS/e449803766edf02ab50b034dd7e89e54efd332cce87688a032f89b340d039878/README.md) |


Generated: 01 Jun 25 22:38 UTC