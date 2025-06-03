# STIR/SHAKEN CA Ecosystem Compliance

## Peeringhub

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 7 potential certificate URLs were requested for retrieval
- 7 candidate certificates were parsed from the potential certificate URLs
- 1 certificates in the candidate corpus were excluded because they are duplicates
- 2 certificates in the candidate corpus were excluded because they are outside-target-validity-period
- 0 certificates in the candidate corpus were excluded because they did not chain to trust anchors
- 4 valid certificates being tested against the remaining rules
- 1.00 issues on average found in valid but non-compliant certificates
- 50.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 265 days is the average remaining validity for the valid certificates
- 326 days is the average initial validity for the valid certificates
- 1.33 average number of unexpired certificates per OCN observed
- 3 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 2 | [e_shaken_certificate_policies_id](ISSUES/e_shaken_certificate_policies_id/README.md) | US_SHAKEN_CP |

#### CA Certificates

- 2 potential certificate URLs were requested for retrieval
- 2 candidate certificates were parsed from the potential certificate URLs
- 0 certificates in the candidate corpus were excluded because they are duplicates
- 0 certificates in the candidate corpus were excluded because they are outside-target-validity-period
- 0 certificates in the candidate corpus were excluded because they did not chain to trust anchors
- 2 valid certificates being tested against the remaining rules
- 1.00 issues on average found in valid but non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 100.00% of certificates are too old to be assessed against currently enforced expectations
- 5541 days is the average remaining validity for the valid certificates
- 5475 days is the average initial validity for the valid certificates

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_subject_cn_ca](ISSUES/e_atis_subject_cn_ca/README.md) | ATIS1000080 |
| 1 | [e_shaken_certificate_policies_id_ca](ISSUES/e_shaken_certificate_policies_id_ca/README.md) | US_SHAKEN_CP |

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 21&#160;Jun&#160;23&#160;00:42&#160;UTC | Meta-lynk Telecom SHAKEN 442K | 30&#160;Jan&#160;24&#160;00:00&#160;UTC | true | [view](CERTS/723af9321b9721ed8c7efcecfc7c6dbb59b3de3b957d707fb030fa6006f29b8c/README.md) |
| 17&#160;Aug&#160;23&#160;22:05&#160;UTC | SHAKEN 788J 1692309910 | 16&#160;Aug&#160;24&#160;22:05&#160;UTC | true | [view](CERTS/6ff13b878806b2584400b1ecc88a909d07fd7480d4c72db64c430f52d8c9909c/README.md) |
| 12&#160;Jul&#160;24&#160;16:44&#160;UTC | VaultTel Solutions Inc_1720802660210 SHAKEN 811K | 25&#160;Jun&#160;25&#160;18:28&#160;UTC | false | [view](CERTS/5eaa8a832b4708f839bdff3d09875030e0536d015f19450d5a628e174defb29e/README.md) |
| 19&#160;Aug&#160;24&#160;13:09&#160;UTC | SHAKEN 788J 1724072973 | 19&#160;Aug&#160;25&#160;13:09&#160;UTC | false | [view](CERTS/a93853adcdf9f247570c397d0d5d2af29ba09e0f132ff8c140aa39b326f48b38/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 17&#160;Dec&#160;20&#160;15:31&#160;UTC | Peeringhub Inc Root CA | 12&#160;Dec&#160;40&#160;15:31&#160;UTC | true | [view](CERTS/0ad4adc0b4d93fdb0e628c577020c73b8a5caff750e7e499f80ee2ab362a3f6a/README.md) |
| 22&#160;Jun&#160;22&#160;22:45&#160;UTC | Peeringhub Inc SHAKEN Intermediate CA 2 | 19&#160;Jun&#160;32&#160;22:45&#160;UTC | true | [view](CERTS/f00871963a40b04269c4b019968e42f9f40964cbfb512ff5342307e9942874ce/README.md) |


Generated: 03 Jun 25 01:30 UTC