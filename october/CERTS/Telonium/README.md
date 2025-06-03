# STIR/SHAKEN CA Ecosystem Compliance

## Telonium

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
- 0.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 0.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 270 days is the average remaining validity for the certificates in the corpus
- 366 days is the average initial validity for the certificates in the corpus
- 1 certificates expire in the next 30 days
- 1.00 average number of unexpired certificates per OCN observed
- 2 unique OCNs observed in unexpired and valid certificate corpus

No error, warning, or notice level issues were found

#### CA Certificates

- 4 potential certificates were requested for retrieval
- 4 candidate certificates were included in the corpus being tested
- 0 certificates in the candidate corpus were skipped because they are duplicates
- 0 certificates in the candidate corpus were skipped because they are outside-target-validity-period
- 0 certificates in the candidate corpus were skipped because they did not chain to trust anchors
- 4 certificates being tested against the remaining rules
- 3.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 50.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 4319 days is the average remaining validity for the certificates in the corpus
- 4474 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days

| Instances | Test | Source |
|-----------|------|--------|
| 2 | [e_atis_ext_key_usage](ISSUES/e_atis_ext_key_usage/README.md) | ATIS1000080 |
| 2 | [e_atis_subject_cn_ca](ISSUES/e_atis_subject_cn_ca/README.md) | ATIS1000080 |
| 2 | [e_atis_subject_cn_root](ISSUES/e_atis_subject_cn_root/README.md) | ATIS1000080 |

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 30&#160;Apr&#160;24&#160;15:58&#160;UTC | SHAKEN 902K | 30&#160;Apr&#160;25&#160;15:59&#160;UTC | false | [view](CERTS/de7f61878b7336e75166e84320fcbb0ebce13837c032a691680c71d71ac933f0/README.md) |
| 20&#160;Aug&#160;24&#160;17:07&#160;UTC | SHAKEN 974K | 20&#160;Aug&#160;25&#160;17:08&#160;UTC | false | [view](CERTS/cc64adfd746943da601c5f1fe4572b2124f6ac35a134d79a0e1df3981d31d518/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 08&#160;Mar&#160;23&#160;18:40&#160;UTC | Telonium STI-CA Root1 | 05&#160;Mar&#160;35&#160;18:40&#160;UTC | true | [view](CERTS/96c66865ce5558c2ce3723c0b414538fcacadcd0f3286108fef57dc447f122f9/README.md) |
| 08&#160;Mar&#160;23&#160;18:40&#160;UTC | Telonium STI-CA Root2 | 07&#160;Mar&#160;38&#160;18:40&#160;UTC | true | [view](CERTS/a58b27999411d3d54121d4eadc82aa128be1fef96cda3029b2015677188ea40b/README.md) |
| 21&#160;Jul&#160;23&#160;00:49&#160;UTC | Telonium SHAKEN ROOT G1 | 21&#160;Jul&#160;35&#160;00:49&#160;UTC | false | [view](CERTS/37e1a126fc5d84ff59f332b2fe8196205bd0e4f7353be497ad17770d9ca6cea5/README.md) |
| 01&#160;Aug&#160;23&#160;16:36&#160;UTC | Telonium SHAKEN Intermediate G1 | 01&#160;Aug&#160;33&#160;16:36&#160;UTC | false | [view](CERTS/8c0ef8682826bec79a8c64881899f6a5a4a1d52dfebe28ae419c23f85df96ea0/README.md) |


Generated: 03 Jun 25 00:48 UTC