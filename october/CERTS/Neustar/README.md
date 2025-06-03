# STIR/SHAKEN CA Ecosystem Compliance

## Neustar

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 20 potential certificates were requested for retrieval
- 20 candidate certificates were included in the corpus being tested
- 3 certificates in the candidate corpus were skipped because they are duplicates
- 14 certificates in the candidate corpus were skipped because they are outside-target-validity-period
- 0 certificates in the candidate corpus were skipped because they did not chain to trust anchors
- 3 certificates being tested against the remaining rules
- 1.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 307 days is the average remaining validity for the certificates in the corpus
- 365 days is the average initial validity for the certificates in the corpus
- 1 certificates expire in the next 30 days
- 1.00 average number of unexpired certificates per OCN observed
- 3 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 3 | [e_us_cp_subject_sn_shall](ISSUES/e_us_cp_subject_sn_shall/README.md) | US_SHAKEN_CP |

#### CA Certificates

- 3 potential certificates were requested for retrieval
- 3 candidate certificates were included in the corpus being tested
- 0 certificates in the candidate corpus were skipped because they are duplicates
- 0 certificates in the candidate corpus were skipped because they are outside-target-validity-period
- 0 certificates in the candidate corpus were skipped because they did not chain to trust anchors
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
| 01&#160;Jul&#160;24&#160;17:19&#160;UTC | SHAKEN 715J | 01&#160;Jul&#160;25&#160;17:19&#160;UTC | true | [view](CERTS/889452e1992267fbff32faea6e899da134b0ddce949cf87a93058d36ec1b48e3/README.md) |
| 27&#160;Sep&#160;24&#160;15:41&#160;UTC | SHAKEN 745J | 27&#160;Sep&#160;25&#160;15:41&#160;UTC | true | [view](CERTS/4b0bcf3e10b9099b8ca8ac63ef02a9fdbeb489cd2e784e4d2f36e80a1465aae8/README.md) |
| 14&#160;Oct&#160;24&#160;19:57&#160;UTC | SHAKEN 506J | 14&#160;Oct&#160;25&#160;19:57&#160;UTC | true | [view](CERTS/2baa23b5ed8b2eca1c3a82f1e538cc0fa2a65e2255b5e4ce94591663c33c15c5/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 23&#160;Sep&#160;19&#160;13:26&#160;UTC | Neustar Certified Caller ID Root CA | 23&#160;Sep&#160;39&#160;13:26&#160;UTC | false | [view](CERTS/4a77c17cd411cb0ff2984b97687f75ab1db451ac7b717ab81c931351c2d547a1/README.md) |
| 17&#160;Aug&#160;21&#160;17:19&#160;UTC | Neustar Certified Caller ID SHAKEN Root CA | 17&#160;Aug&#160;41&#160;17:19&#160;UTC | false | [view](CERTS/4c728d18b628cc67dda5490e0b4aa8ef4ba679f96d033f34f1680e219e0806c3/README.md) |
| 05&#160;Oct&#160;22&#160;17:26&#160;UTC | Neustar Certified Caller ID SHAKEN CA-2 | 05&#160;Oct&#160;32&#160;17:26&#160;UTC | false | [view](CERTS/0bd95ecbb97c09de0df079ca41e10c360c4b5928ac56c496879a2c90c6bbffe4/README.md) |


Generated: 03 Jun 25 00:33 UTC