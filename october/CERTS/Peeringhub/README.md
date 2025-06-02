# STIR/SHAKEN CA Ecosystem Compliance

## Peeringhub

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 79 certificates were included in the corpus being tested
- 7 certificates in the corpus were skipped because they are duplicates
- 50 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 22 certificates being tested against the remaining rules
- 0.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 0.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 265 days is the average remaining validity for the certificates in the corpus
- 274 days is the average initial validity for the certificates in the corpus
- 11 certificates expire in the next 30 days
- 1.05 average number of unexpired certificates per OCN observed
- 21 unique OCNs observed in unexpired and valid certificate corpus

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
| 07&#160;Mar&#160;24&#160;18:12&#160;UTC | Infinity Sip_1709835154271 SHAKEN 279K | 07&#160;Mar&#160;25&#160;18:12&#160;UTC | false | [view](CERTS/36ac9c9983376a0c62d2bd2de4b817debe4798d166442c1e4e72c7356293eceb/README.md) |
| 11&#160;Jun&#160;24&#160;20:32&#160;UTC | Wavecall LLC_1718137942094 SHAKEN 939K | 11&#160;Jun&#160;25&#160;20:32&#160;UTC | false | [view](CERTS/3fac1aaffc1d33baa1e1d342d44d3f4e3ceacaf53a342d56da832f69f5f49168/README.md) |
| 18&#160;Jun&#160;24&#160;21:30&#160;UTC | Ahoi SHAKEN 883K | 18&#160;Jun&#160;25&#160;21:30&#160;UTC | false | [view](CERTS/c041e4169ff485642cd76e764413abb68e951d1ce1e7caea1c187e688363d0cc/README.md) |
| 25&#160;Jun&#160;24&#160;17:14&#160;UTC | Telcast Networks_1719335648799 SHAKEN 611J | 25&#160;Jun&#160;25&#160;17:14&#160;UTC | false | [view](CERTS/b30f6c4c5a9ec72333773acd717df1692bdaf1de3b8e71628e035899149a1d0f/README.md) |
| 12&#160;Jul&#160;24&#160;16:44&#160;UTC | VaultTel Solutions Inc_1720802660210 SHAKEN 811K | 25&#160;Jun&#160;25&#160;18:28&#160;UTC | false | [view](CERTS/5eaa8a832b4708f839bdff3d09875030e0536d015f19450d5a628e174defb29e/README.md) |
| 17&#160;Jul&#160;24&#160;16:04&#160;UTC | TruTelco SHAKEN 926K | 20&#160;May&#160;25&#160;17:55&#160;UTC | false | [view](CERTS/552bc06d4306f0f17761764b12fc0955e20640d0875bd950d7eb0f847b99a7cb/README.md) |
| 02&#160;Aug&#160;24&#160;21:33&#160;UTC | Perfect Network LLC_1722634425181 SHAKEN 458K | 02&#160;Aug&#160;25&#160;21:33&#160;UTC | false | [view](CERTS/ab8985f314df3ccccd7986ba9268c047c0059216c830a2d1acf363b8aa5c8859/README.md) |
| 05&#160;Aug&#160;24&#160;03:57&#160;UTC | DiDCentral LLC SHAKEN 756J | 05&#160;Aug&#160;25&#160;03:57&#160;UTC | false | [view](CERTS/69f3edd7be8aa1f21de026ffd129608b918188a75b4bac41bedd9ce94aa92238/README.md) |
| 19&#160;Aug&#160;24&#160;13:09&#160;UTC | SHAKEN 788J 1724072973 | 19&#160;Aug&#160;25&#160;13:09&#160;UTC | false | [view](CERTS/a93853adcdf9f247570c397d0d5d2af29ba09e0f132ff8c140aa39b326f48b38/README.md) |
| 28&#160;Aug&#160;24&#160;00:27&#160;UTC | DIAL WORLD COMMUNICATIONS LLC_1724804850035 SHAKEN 727K | 05&#160;Aug&#160;25&#160;23:59&#160;UTC | false | [view](CERTS/e035fb9c865457525a27b5e0eccd59de2795a8f3838f366790d7798296786c83/README.md) |
| 04&#160;Sep&#160;24&#160;20:59&#160;UTC | Jaintel LLC SHAKEN 586K | 04&#160;Sep&#160;25&#160;20:59&#160;UTC | false | [view](CERTS/2b291c419ae7f36b4e6626c61b973a82ce6c2f840b90491e142de89571f827a7/README.md) |
| 30&#160;Sep&#160;24&#160;13:11&#160;UTC | ARit services LLC_1727701880593 SHAKEN 827K | 01&#160;Nov&#160;24&#160;15:40&#160;UTC | false | [view](CERTS/93fdb4cbcb3f39df39bba2650f95aac1917477a3a9b24630cf06b76387140b1a/README.md) |
| 30&#160;Sep&#160;24&#160;18:34&#160;UTC | Itel Corp SHAKEN 775K 2 | 03&#160;Nov&#160;24&#160;23:15&#160;UTC | false | [view](CERTS/7ade6b21f5f1dce581fb84a30f6a12d3a693309d2a465877d0886de0ccb8b52c/README.md) |
| 30&#160;Sep&#160;24&#160;23:02&#160;UTC | beltalk solutions LLC_1727737340643 SHAKEN 745K | 01&#160;Nov&#160;24&#160;15:02&#160;UTC | false | [view](CERTS/0dacca27bec77e6e8a5a0f2845494a5bf487fdb91fa4bea6936cc95cc6a66d39/README.md) |
| 25&#160;Nov&#160;24&#160;06:12&#160;UTC | Apex Teleocm LLC_1732515132751 SHAKEN 288K | 25&#160;Nov&#160;25&#160;06:12&#160;UTC | false | [view](CERTS/cd88f32e1fa0c6ade2be7748cff95117f7b0287e0145351a2bfec0824d00aa15/README.md) |
| 22&#160;Jan&#160;25&#160;22:57&#160;UTC | INSTACALL LLC_1737586625863 SHAKEN 281K | 22&#160;Jan&#160;26&#160;19:11&#160;UTC | false | [view](CERTS/e6a042ea51e05367aaa83b2d0be471bec283bff51ec9c6106df1010b52987c7d/README.md) |
| 24&#160;Mar&#160;25&#160;16:15&#160;UTC | On Air Telecom LLC_1742832914104 SHAKEN 861J | 16&#160;Jul&#160;25&#160;18:07&#160;UTC | false | [view](CERTS/b879f4148c63855ff262338c7ad56f691239d80b589f4733cebf8973c593e940/README.md) |
| 03&#160;Apr&#160;25&#160;20:41&#160;UTC | SHAKEN 331K | 03&#160;Apr&#160;26&#160;20:41&#160;UTC | false | [view](CERTS/f2ea79c13fbb33f721d7d87b4ed95fca835e4caf00d363dedfa6617f0f725d8c/README.md) |
| 08&#160;Apr&#160;25&#160;05:01&#160;UTC | FlowVOIP LLC._1744088504457 SHAKEN 849K | 08&#160;Apr&#160;26&#160;05:01&#160;UTC | false | [view](CERTS/8b02a3c2a6f90aadabb62241d56afa144fb8934f91e055813dcd7a6f5b264aa7/README.md) |
| 05&#160;May&#160;25&#160;00:00&#160;UTC | VOCALTRANSIT SHAKEN 783J | 15&#160;Jun&#160;25&#160;00:00&#160;UTC | false | [view](CERTS/2785d57a9a9f00f67cc96bcb65b9e1d0ce45f8acac2a71f7f3483702d6c90fe0/README.md) |
| 13&#160;May&#160;25&#160;19:38&#160;UTC | SHAKEN 088K | 13&#160;May&#160;26&#160;19:38&#160;UTC | false | [view](CERTS/9efea51511ce7ae4d8f9df9bbc31489c89bfebc0c1df07148ad06de607b15e16/README.md) |
| 14&#160;May&#160;25&#160;20:10&#160;UTC | beltalk solutions LLC_1747253421716 SHAKEN 745K | 17&#160;Jun&#160;25&#160;13:24&#160;UTC | false | [view](CERTS/d2ea9a8bbb8f8f5dc12fa1ed0d5ddbb229508a8f98b27ca8d4ba06a6cae146f1/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 17&#160;Dec&#160;20&#160;15:31&#160;UTC | Peeringhub Inc Root CA | 12&#160;Dec&#160;40&#160;15:31&#160;UTC | true | [view](CERTS/0ad4adc0b4d93fdb0e628c577020c73b8a5caff750e7e499f80ee2ab362a3f6a/README.md) |
| 22&#160;Jun&#160;22&#160;22:45&#160;UTC | Peeringhub Inc SHAKEN Intermediate CA 2 | 19&#160;Jun&#160;32&#160;22:45&#160;UTC | true | [view](CERTS/f00871963a40b04269c4b019968e42f9f40964cbfb512ff5342307e9942874ce/README.md) |


Generated: 02 Jun 25 03:45 UTC