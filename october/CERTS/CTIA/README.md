# STIR/SHAKEN CA Ecosystem Compliance

## CTIA

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### CA Certificates

- 1 potential certificate URLs were requested for retrieval
- 1 candidate certificates were parsed from the potential certificate URLs
- 0 certificates in the candidate corpus were excluded because they are duplicates
- 0 certificates in the candidate corpus were excluded because they are outside-target-validity-period
- 0 certificates in the candidate corpus were excluded because they did not chain to trust anchors
- 1 valid certificates being tested against the remaining rules
- 1.00 issues on average found in valid but non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 8769 days is the average remaining validity for the valid certificates
- 9125 days is the average initial validity for the valid certificates

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_subject_public_key_ca](ISSUES/e_atis_subject_public_key_ca/README.md) | ATIS1000080 |

### Details

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 21&#160;Jun&#160;23&#160;13:15&#160;UTC | SHAKEN Root CA | 14&#160;Jun&#160;48&#160;13:15&#160;UTC | true | [view](CERTS/ee1cf83becad4777dcf250170efecc7fc7498d85097e9a570dfac542151ebf53/README.md) |


Generated: 03 Jun 25 01:30 UTC