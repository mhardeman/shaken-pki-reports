# STIR/SHAKEN CA Ecosystem Compliance

## Peeringhub

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 8 potential certificates were requested for retrieval
- 8 candidate certificates were included in the corpus being tested
- 0 certificates in the candidate corpus were skipped because they are duplicates
- 4 certificates in the candidate corpus were skipped because they are outside-target-validity-period
- 0 certificates in the candidate corpus were skipped because they did not chain to trust anchors
- 4 certificates being tested against the remaining rules
- 0.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 0.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 293 days is the average remaining validity for the certificates in the corpus
- 361 days is the average initial validity for the certificates in the corpus
- 2 certificates expire in the next 30 days
- 1.00 average number of unexpired certificates per OCN observed
- 4 unique OCNs observed in unexpired and valid certificate corpus

No error, warning, or notice level issues were found

#### CA Certificates

- 2 potential certificates were requested for retrieval
- 2 candidate certificates were included in the corpus being tested
- 0 certificates in the candidate corpus were skipped because they are duplicates
- 0 certificates in the candidate corpus were skipped because they are outside-target-validity-period
- 0 certificates in the candidate corpus were skipped because they did not chain to trust anchors
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
| 18&#160;Jun&#160;24&#160;21:30&#160;UTC | Ahoi SHAKEN 883K | 18&#160;Jun&#160;25&#160;21:30&#160;UTC | false | [view](CERTS/c041e4169ff485642cd76e764413abb68e951d1ce1e7caea1c187e688363d0cc/README.md) |
| 12&#160;Jul&#160;24&#160;16:44&#160;UTC | VaultTel Solutions Inc_1720802660210 SHAKEN 811K | 25&#160;Jun&#160;25&#160;18:28&#160;UTC | false | [view](CERTS/5eaa8a832b4708f839bdff3d09875030e0536d015f19450d5a628e174defb29e/README.md) |
| 02&#160;Aug&#160;24&#160;21:33&#160;UTC | Perfect Network LLC_1722634425181 SHAKEN 458K | 02&#160;Aug&#160;25&#160;21:33&#160;UTC | false | [view](CERTS/ab8985f314df3ccccd7986ba9268c047c0059216c830a2d1acf363b8aa5c8859/README.md) |
| 08&#160;Aug&#160;24&#160;20:16&#160;UTC | Autodial Telecommunications LLC_1723148189119 SHAKEN 677K | 08&#160;Aug&#160;25&#160;20:16&#160;UTC | false | [view](CERTS/e2bfccd2f356a0a4635639aa5363e180429b6a0901a1cbb180b4e96dacfa809d/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 17&#160;Dec&#160;20&#160;15:31&#160;UTC | Peeringhub Inc Root CA | 12&#160;Dec&#160;40&#160;15:31&#160;UTC | true | [view](CERTS/0ad4adc0b4d93fdb0e628c577020c73b8a5caff750e7e499f80ee2ab362a3f6a/README.md) |
| 22&#160;Jun&#160;22&#160;22:45&#160;UTC | Peeringhub Inc SHAKEN Intermediate CA 2 | 19&#160;Jun&#160;32&#160;22:45&#160;UTC | true | [view](CERTS/f00871963a40b04269c4b019968e42f9f40964cbfb512ff5342307e9942874ce/README.md) |


Generated: 03 Jun 25 00:33 UTC