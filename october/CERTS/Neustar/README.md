# STIR/SHAKEN CA Ecosystem Compliance

## Neustar

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 11 potential certificates were requested for retrieval
- 11 candidate certificates were included in the corpus being tested
- 0 certificates in the candidate corpus were skipped because they are duplicates
- 0 certificates in the candidate corpus were skipped because they are outside-target-validity-period
- 1 certificates in the candidate corpus were skipped because they did not chain to trust anchors
- 10 certificates being tested against the remaining rules
- 1.10 issues on average found in unexpired, trusted, and non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 334 days is the average remaining validity for the certificates in the corpus
- 365 days is the average initial validity for the certificates in the corpus
- 8 certificates expire in the next 30 days
- 1.43 average number of unexpired certificates per OCN observed
- 7 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_ext_not_specified](ISSUES/e_atis_ext_not_specified/README.md) | ATIS1000080 |
| 10 | [e_us_cp_subject_sn_shall](ISSUES/e_us_cp_subject_sn_shall/README.md) | US_SHAKEN_CP |

#### CA Certificates

- 4 potential certificates were requested for retrieval
- 4 candidate certificates were included in the corpus being tested
- 0 certificates in the candidate corpus were skipped because they are duplicates
- 0 certificates in the candidate corpus were skipped because they are outside-target-validity-period
- 1 certificates in the candidate corpus were skipped because they did not chain to trust anchors
- 3 certificates being tested against the remaining rules
- 0.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 0.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 100.00% of certificates are too old to be assessed against currently enforced expectations
- 6046 days is the average remaining validity for the certificates in the corpus
- 6088 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days

No error, warning, or notice level issues were found

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 30&#160;Apr&#160;23&#160;22:24&#160;UTC | SHAKEN 997E | 29&#160;Apr&#160;24&#160;22:24&#160;UTC | true | [view](CERTS/0dc3f445b4b78538a8c2c930df2b0334edcc81f225e64312ce14fc9e290b86f3/README.md) |
| 26&#160;Sep&#160;23&#160;15:26&#160;UTC | SHAKEN 9555 | 25&#160;Sep&#160;24&#160;15:26&#160;UTC | true | [view](CERTS/b9cae288342f8bbe68f46fd1853f3f5f8f2861b9257b388edff1a7886a5ba986/README.md) |
| 18&#160;Oct&#160;23&#160;17:32&#160;UTC | SHAKEN 510J | 17&#160;Oct&#160;24&#160;17:32&#160;UTC | true | [view](CERTS/c6ad12e2e74892c0478600fac25879b56ecbbb3a4a166795701723473bbe1459/README.md) |
| 07&#160;Dec&#160;23&#160;16:28&#160;UTC | ATT SHAKEN 4036 | 06&#160;Dec&#160;24&#160;16:28&#160;UTC | true | [view](CERTS/af305ddae3b679f7bde37d64510b467dddfa0d2312be53aa9ae8dd83839d77ce/README.md) |
| 15&#160;Apr&#160;24&#160;16:57&#160;UTC | SHAKEN 997E | 15&#160;Apr&#160;25&#160;16:57&#160;UTC | true | [view](CERTS/fa6c1952b481a1a69b032efb2d3bba89e6408158aaad971debf9d8057298be47/README.md) |
| 22&#160;May&#160;24&#160;18:36&#160;UTC | SHAKEN 139K | 22&#160;May&#160;25&#160;18:36&#160;UTC | true | [view](CERTS/b42601237dcb1c77ca4896380df9e216d5deaa3b1838f0e749d033d99e593739/README.md) |
| 01&#160;Jul&#160;24&#160;17:05&#160;UTC | SHAKEN 962J | 01&#160;Jul&#160;25&#160;17:05&#160;UTC | true | [view](CERTS/0ba8d7326d25fd1fdcd6c28325ddff0fe1cf610a1a8ec92ef8a8083e3f3cc4ee/README.md) |
| 01&#160;Jul&#160;24&#160;17:58&#160;UTC | SHAKEN 4036 | 01&#160;Jul&#160;25&#160;17:58&#160;UTC | true | [view](CERTS/0823fce516b339bda1acf5b484481f12fe068273d2760a87647fbcfd93591c6c/README.md) |
| 19&#160;Aug&#160;24&#160;18:27&#160;UTC | SHAKEN 872J | 19&#160;Aug&#160;25&#160;18:27&#160;UTC | true | [view](CERTS/0ed4f22a2a19b5c7e8c70d7955a49dd652582f02dbadbb3863f213282404567b/README.md) |
| 25&#160;Sep&#160;24&#160;15:16&#160;UTC | SHAKEN 9555 | 25&#160;Sep&#160;25&#160;15:16&#160;UTC | true | [view](CERTS/f7b7228d0701b14410f37040c818167d03df044fe52355c59b91dd49579acbde/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 23&#160;Sep&#160;19&#160;13:26&#160;UTC | Neustar Certified Caller ID Root CA | 23&#160;Sep&#160;39&#160;13:26&#160;UTC | false | [view](CERTS/4a77c17cd411cb0ff2984b97687f75ab1db451ac7b717ab81c931351c2d547a1/README.md) |
| 17&#160;Aug&#160;21&#160;17:19&#160;UTC | Neustar Certified Caller ID SHAKEN Root CA | 17&#160;Aug&#160;41&#160;17:19&#160;UTC | false | [view](CERTS/4c728d18b628cc67dda5490e0b4aa8ef4ba679f96d033f34f1680e219e0806c3/README.md) |
| 05&#160;Oct&#160;22&#160;17:26&#160;UTC | Neustar Certified Caller ID SHAKEN CA-2 | 05&#160;Oct&#160;32&#160;17:26&#160;UTC | false | [view](CERTS/0bd95ecbb97c09de0df079ca41e10c360c4b5928ac56c496879a2c90c6bbffe4/README.md) |


Generated: 03 Jun 25 00:36 UTC