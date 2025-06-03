# STIR/SHAKEN CA Ecosystem Compliance

## NetNumber

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### CA Certificates

- 2 potential certificates were requested for retrieval
- 2 candidate certificates were included in the corpus being tested
- 0 certificates in the candidate corpus were skipped because they are duplicates
- 0 certificates in the candidate corpus were skipped because they are outside-target-validity-period
- 0 certificates in the candidate corpus were skipped because they did not chain to trust anchors
- 2 certificates being tested against the remaining rules
- 2.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 50.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 100.00% of certificates are too old to be assessed against currently enforced expectations
- 8069 days is the average remaining validity for the certificates in the corpus
- 8212 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_signature_algorithm_ca](ISSUES/e_atis_signature_algorithm_ca/README.md) | ATIS1000080 |
| 1 | [e_atis_subject_public_key_ca](ISSUES/e_atis_subject_public_key_ca/README.md) | ATIS1000080 |

### Details

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 12&#160;Jul&#160;21&#160;23:25&#160;UTC | NetNumber SHAKEN Root CA | 07&#160;Jul&#160;41&#160;23:25&#160;UTC | false | [view](CERTS/7ac80e8481ecb019dc95484016842db78686069efbc0f703e7f39310217b6157/README.md) |
| 27&#160;Sep&#160;21&#160;19:45&#160;UTC | NetNumber SHAKEN Root CA 1 | 21&#160;Sep&#160;46&#160;19:45&#160;UTC | true | [view](CERTS/2dd1386ca717f31d550b35b9bce9daa9b02483bcdb98bdfcfca07202276136d7/README.md) |


Generated: 03 Jun 25 00:33 UTC