# STIR/SHAKEN CA Ecosystem Compliance

## Telonium

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 4 potential certificates were requested for retrieval
- 4 candidate certificates were included in the corpus being tested
- 0 certificates in the candidate corpus were skipped because they are duplicates
- 2 certificates in the candidate corpus were skipped because they are outside-target-validity-period
- 0 certificates in the candidate corpus were skipped because they did not chain to trust anchors
- 2 certificates being tested against the remaining rules
- 1.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 50.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 434 days is the average remaining validity for the certificates in the corpus
- 638 days is the average initial validity for the certificates in the corpus
- 1 certificates expire in the next 30 days
- 1.00 average number of unexpired certificates per OCN observed
- 2 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_ext_not_specified](ISSUES/e_atis_ext_not_specified/README.md) | ATIS1000080 |

#### CA Certificates

- 5 potential certificates were requested for retrieval
- 5 candidate certificates were included in the corpus being tested
- 0 certificates in the candidate corpus were skipped because they are duplicates
- 0 certificates in the candidate corpus were skipped because they are outside-target-validity-period
- 0 certificates in the candidate corpus were skipped because they did not chain to trust anchors
- 5 certificates being tested against the remaining rules
- 4.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 60.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 4208 days is the average remaining validity for the certificates in the corpus
- 4309 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_ext_certificate_policies_ca](ISSUES/e_atis_ext_certificate_policies_ca/README.md) | ATIS1000080 |
| 1 | [e_atis_ext_crl_distribution_ca](ISSUES/e_atis_ext_crl_distribution_ca/README.md) | ATIS1000080 |
| 2 | [e_atis_ext_key_usage](ISSUES/e_atis_ext_key_usage/README.md) | ATIS1000080 |
| 1 | [e_atis_subject_c_iso_ca](ISSUES/e_atis_subject_c_iso_ca/README.md) | ATIS1000080 |
| 3 | [e_atis_subject_cn_ca](ISSUES/e_atis_subject_cn_ca/README.md) | ATIS1000080 |
| 2 | [e_atis_subject_cn_root](ISSUES/e_atis_subject_cn_root/README.md) | ATIS1000080 |
| 1 | [e_atis_subject_dn_ca](ISSUES/e_atis_subject_dn_ca/README.md) | ATIS1000080 |
| 1 | [e_shaken_certificate_policies_id_ca](ISSUES/e_shaken_certificate_policies_id_ca/README.md) | US_SHAKEN_CP |

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 10&#160;Jul&#160;23&#160;14:44&#160;UTC | SHAKEN 656K | 28&#160;Jun&#160;25&#160;19:35&#160;UTC | true | [view](CERTS/fd285a02878cd6c995f532bbc9b51b4721f5dd3828aa271194760254eb1cd549/README.md) |
| 20&#160;Jun&#160;24&#160;19:05&#160;UTC | SHAKEN 633K | 27&#160;Dec&#160;25&#160;16:31&#160;UTC | false | [view](CERTS/5c0d32d70b614b08cec3502a7ef34663daa44eb814894c021def70d56c113d62/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 08&#160;Mar&#160;23&#160;18:40&#160;UTC | Telonium STI-CA Root1 | 05&#160;Mar&#160;35&#160;18:40&#160;UTC | true | [view](CERTS/96c66865ce5558c2ce3723c0b414538fcacadcd0f3286108fef57dc447f122f9/README.md) |
| 08&#160;Mar&#160;23&#160;18:40&#160;UTC | Telonium STI-CA Root2 | 07&#160;Mar&#160;38&#160;18:40&#160;UTC | true | [view](CERTS/a58b27999411d3d54121d4eadc82aa128be1fef96cda3029b2015677188ea40b/README.md) |
| 09&#160;Mar&#160;23&#160;15:18&#160;UTC | Telonium STI-CA Intermediate CA | 06&#160;Mar&#160;33&#160;15:18&#160;UTC | true | [view](CERTS/7c701216e591c9a3b84550ff46566dd420c7f182eb3cfc5abe5739cdbe271169/README.md) |
| 21&#160;Jul&#160;23&#160;00:49&#160;UTC | Telonium SHAKEN ROOT G1 | 21&#160;Jul&#160;35&#160;00:49&#160;UTC | false | [view](CERTS/37e1a126fc5d84ff59f332b2fe8196205bd0e4f7353be497ad17770d9ca6cea5/README.md) |
| 01&#160;Aug&#160;23&#160;16:36&#160;UTC | Telonium SHAKEN Intermediate G1 | 01&#160;Aug&#160;33&#160;16:36&#160;UTC | false | [view](CERTS/8c0ef8682826bec79a8c64881899f6a5a4a1d52dfebe28ae419c23f85df96ea0/README.md) |


Generated: 03 Jun 25 00:33 UTC