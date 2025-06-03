# STIR/SHAKEN CA Ecosystem Compliance

## Metaswitch

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 2 potential certificates were requested for retrieval
- 2 candidate certificates were included in the corpus being tested
- 0 certificates in the candidate corpus were skipped because they are duplicates
- 0 certificates in the candidate corpus were skipped because they are outside-target-validity-period
- 0 certificates in the candidate corpus were skipped because they did not chain to trust anchors
- 2 certificates being tested against the remaining rules
- 3.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 50.00% of certificates are too old to be assessed against currently enforced expectations
- 937 days is the average remaining validity for the certificates in the corpus
- 1095 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days
- 1.00 average number of unexpired certificates per OCN observed
- 2 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 2 | [e_atis_ext_key_usage_ee](ISSUES/e_atis_ext_key_usage_ee/README.md) | ATIS1000080 |
| 2 | [e_atis_subject_cn_spc](ISSUES/e_atis_subject_cn_spc/README.md) | ATIS1000080 |
| 2 | [e_us_cp_subject_sn_shall](ISSUES/e_us_cp_subject_sn_shall/README.md) | US_SHAKEN_CP |

#### CA Certificates

- 2 potential certificates were requested for retrieval
- 2 candidate certificates were included in the corpus being tested
- 0 certificates in the candidate corpus were skipped because they are duplicates
- 0 certificates in the candidate corpus were skipped because they are outside-target-validity-period
- 0 certificates in the candidate corpus were skipped because they did not chain to trust anchors
- 2 certificates being tested against the remaining rules
- 2.50 issues on average found in unexpired, trusted, and non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 50.00% of certificates are too old to be assessed against currently enforced expectations
- 5777 days is the average remaining validity for the certificates in the corpus
- 5840 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_subject_c_iso_ca](ISSUES/e_atis_subject_c_iso_ca/README.md) | ATIS1000080 |
| 2 | [e_atis_subject_dn_ca](ISSUES/e_atis_subject_dn_ca/README.md) | ATIS1000080 |
| 1 | [e_atis_subject_o_required_ca](ISSUES/e_atis_subject_o_required_ca/README.md) | ATIS1000080 |
| 1 | [e_shaken_certificate_policies_id_ca](ISSUES/e_shaken_certificate_policies_id_ca/README.md) | US_SHAKEN_CP |

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 08&#160;Sep&#160;22&#160;16:04&#160;UTC | Priority Communications SHAKEN Cert 327K | 07&#160;Sep&#160;25&#160;16:04&#160;UTC | true | [view](CERTS/272753ac210e9937d9fbf8fcb367c945c68edc3c7bd8d5193cfb09bf8252331a/README.md) |
| 13&#160;Feb&#160;24&#160;10:39&#160;UTC | Northeast Communications of Wisconsin SHAKEN Cert 6692 | 12&#160;Feb&#160;27&#160;10:39&#160;UTC | true | [view](CERTS/3d46aceeef2cac6a05000c9888af4d55ccd3201ea00ab98a2c6ff4309ef8dfb3/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 25&#160;Nov&#160;20&#160;11:21&#160;UTC | Metaswitch STI-CA SHAKEN Root | 20&#160;Nov&#160;40&#160;11:21&#160;UTC | true | [view](CERTS/c27184f75f81fc119b85d51d416477bf635040e5d66ce6051799b37b9aa17485/README.md) |
| 10&#160;Feb&#160;23&#160;14:38&#160;UTC | Metaswitch STI-CA SHAKEN Issuing 1 | 07&#160;Feb&#160;35&#160;14:38&#160;UTC | true | [view](CERTS/8a7fb50e95b8c43a63d19e2f279de565fa611ae3f24a14f82394e3208782be7a/README.md) |


Generated: 03 Jun 25 00:33 UTC