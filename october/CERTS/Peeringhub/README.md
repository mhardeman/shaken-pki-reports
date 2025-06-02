# STIR/SHAKEN CA Ecosystem Compliance

## Peeringhub

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 7 certificates were included in the corpus being tested
- 1 certificates in the corpus were skipped because they are duplicates
- 2 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 4 certificates being tested against the remaining rules
- 0.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 0.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 294 days is the average remaining validity for the certificates in the corpus
- 361 days is the average initial validity for the certificates in the corpus
- 1 certificates expire in the next 30 days
- 1.00 average number of unexpired certificates per OCN observed
- 4 unique OCNs observed in unexpired and valid certificate corpus

No error, warning, or notice level issues were found

#### CA Certificates

- 2 certificates were included in the corpus being tested
- 0 certificates in the corpus were skipped because they are duplicates
- 0 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 2 certificates being tested against the remaining rules
- 1.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 100.00% of certificates are too old to be assessed against currently enforced expectations
- 5541 days is the average remaining validity for the certificates in the corpus
- 5475 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_subject_cn_ca](ISSUES/e_atis_subject_cn_ca/README.md) | ATIS1000080 |
| 1 | [e_shaken_certificate_policies_id_ca](ISSUES/e_shaken_certificate_policies_id_ca/README.md) | US_SHAKEN_CP |

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 12&#160;Jul&#160;24&#160;16:44&#160;UTC | VaultTel Solutions Inc_1720802660210 SHAKEN 811K | 25&#160;Jun&#160;25&#160;18:28&#160;UTC | false | [view](CERTS/5eaa8a832b4708f839bdff3d09875030e0536d015f19450d5a628e174defb29e/README.md) |
| 19&#160;Aug&#160;24&#160;13:09&#160;UTC | SHAKEN 788J 1724072973 | 19&#160;Aug&#160;25&#160;13:09&#160;UTC | false | [view](CERTS/a93853adcdf9f247570c397d0d5d2af29ba09e0f132ff8c140aa39b326f48b38/README.md) |
| 03&#160;Apr&#160;25&#160;20:41&#160;UTC | SHAKEN 331K | 03&#160;Apr&#160;26&#160;20:41&#160;UTC | false | [view](CERTS/f2ea79c13fbb33f721d7d87b4ed95fca835e4caf00d363dedfa6617f0f725d8c/README.md) |
| 08&#160;Apr&#160;25&#160;05:01&#160;UTC | FlowVOIP LLC._1744088504457 SHAKEN 849K | 08&#160;Apr&#160;26&#160;05:01&#160;UTC | false | [view](CERTS/8b02a3c2a6f90aadabb62241d56afa144fb8934f91e055813dcd7a6f5b264aa7/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 17&#160;Dec&#160;20&#160;15:31&#160;UTC | Peeringhub Inc Root CA | 12&#160;Dec&#160;40&#160;15:31&#160;UTC | true | [view](CERTS/0ad4adc0b4d93fdb0e628c577020c73b8a5caff750e7e499f80ee2ab362a3f6a/README.md) |
| 22&#160;Jun&#160;22&#160;22:45&#160;UTC | Peeringhub Inc SHAKEN Intermediate CA 2 | 19&#160;Jun&#160;32&#160;22:45&#160;UTC | true | [view](CERTS/f00871963a40b04269c4b019968e42f9f40964cbfb512ff5342307e9942874ce/README.md) |


Generated: 02 Jun 25 02:39 UTC