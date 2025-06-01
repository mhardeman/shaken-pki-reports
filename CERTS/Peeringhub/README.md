# STIR/SHAKEN CA Ecosystem Compliance

## Peeringhub

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 48 certificates were included in the corpus being tested
- 5 certificates in the corpus were skipped because they are duplicates
- 12 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 31 certificates being tested against the remaining rules
- 0.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 0.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 298 days is the average remaining validity for the certificates in the corpus
- 306 days is the average initial validity for the certificates in the corpus
- 8 certificates expire in the next 30 days
- 1.03 average number of unexpired certificates per OCN observed
- 30 unique OCNs observed in unexpired and valid certificate corpus

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
| 11&#160;Jun&#160;24&#160;20:32&#160;UTC | Wavecall LLC_1718137942094 SHAKEN 939K | 11&#160;Jun&#160;25&#160;20:32&#160;UTC | false | [view](CERTS/3fac1aaffc1d33baa1e1d342d44d3f4e3ceacaf53a342d56da832f69f5f49168/README.md) |
| 18&#160;Jun&#160;24&#160;21:30&#160;UTC | Ahoi SHAKEN 883K | 18&#160;Jun&#160;25&#160;21:30&#160;UTC | false | [view](CERTS/c041e4169ff485642cd76e764413abb68e951d1ce1e7caea1c187e688363d0cc/README.md) |
| 24&#160;Jun&#160;24&#160;19:29&#160;UTC | Conveytel_1719257376064 SHAKEN 892K | 12&#160;Jun&#160;25&#160;17:13&#160;UTC | false | [view](CERTS/76b71d6315c37ab0edcda6ec33f44649a9a29d005ea8e390b622415b0c907c87/README.md) |
| 25&#160;Jun&#160;24&#160;17:14&#160;UTC | Telcast Networks_1719335648799 SHAKEN 611J | 25&#160;Jun&#160;25&#160;17:14&#160;UTC | false | [view](CERTS/b30f6c4c5a9ec72333773acd717df1692bdaf1de3b8e71628e035899149a1d0f/README.md) |
| 12&#160;Jul&#160;24&#160;16:44&#160;UTC | VaultTel Solutions Inc_1720802660210 SHAKEN 811K | 25&#160;Jun&#160;25&#160;18:28&#160;UTC | false | [view](CERTS/5eaa8a832b4708f839bdff3d09875030e0536d015f19450d5a628e174defb29e/README.md) |
| 02&#160;Aug&#160;24&#160;21:33&#160;UTC | Perfect Network LLC_1722634425181 SHAKEN 458K | 02&#160;Aug&#160;25&#160;21:33&#160;UTC | false | [view](CERTS/ab8985f314df3ccccd7986ba9268c047c0059216c830a2d1acf363b8aa5c8859/README.md) |
| 05&#160;Aug&#160;24&#160;03:57&#160;UTC | DiDCentral LLC SHAKEN 756J | 05&#160;Aug&#160;25&#160;03:57&#160;UTC | false | [view](CERTS/69f3edd7be8aa1f21de026ffd129608b918188a75b4bac41bedd9ce94aa92238/README.md) |
| 08&#160;Aug&#160;24&#160;20:16&#160;UTC | Autodial Telecommunications LLC_1723148189119 SHAKEN 677K | 08&#160;Aug&#160;25&#160;20:16&#160;UTC | false | [view](CERTS/e2bfccd2f356a0a4635639aa5363e180429b6a0901a1cbb180b4e96dacfa809d/README.md) |
| 28&#160;Aug&#160;24&#160;00:27&#160;UTC | DIAL WORLD COMMUNICATIONS LLC_1724804850035 SHAKEN 727K | 05&#160;Aug&#160;25&#160;23:59&#160;UTC | false | [view](CERTS/e035fb9c865457525a27b5e0eccd59de2795a8f3838f366790d7798296786c83/README.md) |
| 04&#160;Sep&#160;24&#160;20:59&#160;UTC | Jaintel LLC SHAKEN 586K | 04&#160;Sep&#160;25&#160;20:59&#160;UTC | false | [view](CERTS/2b291c419ae7f36b4e6626c61b973a82ce6c2f840b90491e142de89571f827a7/README.md) |
| 11&#160;Oct&#160;24&#160;18:50&#160;UTC | VoyageNetworks_1728672609930 SHAKEN 006L | 11&#160;Oct&#160;25&#160;18:50&#160;UTC | false | [view](CERTS/c96b4c6a543b1df3110d0769b4c64e096e5749fb1ae434b0e9f317eec8bf4e6a/README.md) |
| 21&#160;Oct&#160;24&#160;18:47&#160;UTC | Voipedia_1729536460984 SHAKEN 712K | 21&#160;Oct&#160;25&#160;18:47&#160;UTC | false | [view](CERTS/77b337bd7af475c810110836e6cbd153aa04051e61712de0caed187aa1268618/README.md) |
| 04&#160;Nov&#160;24&#160;21:43&#160;UTC | Teleinx, LLC_1730756614004 SHAKEN 744J | 20&#160;Sep&#160;25&#160;13:11&#160;UTC | false | [view](CERTS/ac59a2ba3b893e9742d563dbc3f67fe1e8700ee7a8f7f2f51de7fbee97339d43/README.md) |
| 07&#160;Nov&#160;24&#160;19:46&#160;UTC | Telecom Business Network LLC_1731008761381 SHAKEN 824K | 07&#160;Nov&#160;25&#160;19:46&#160;UTC | false | [view](CERTS/ffe00a2d194b964738ec33f98f6d07320e79d3407f363dc602922ca88d5a8cdb/README.md) |
| 25&#160;Nov&#160;24&#160;06:12&#160;UTC | Apex Teleocm LLC_1732515132751 SHAKEN 288K | 25&#160;Nov&#160;25&#160;06:12&#160;UTC | false | [view](CERTS/cd88f32e1fa0c6ade2be7748cff95117f7b0287e0145351a2bfec0824d00aa15/README.md) |
| 12&#160;Dec&#160;24&#160;00:17&#160;UTC | 1234Voip.com LLC_1733962630456 SHAKEN 056L | 30&#160;Nov&#160;25&#160;22:28&#160;UTC | false | [view](CERTS/2c9bef3333855dc0338ce5a78bb57f9385213ba84691e7ae26dec1bafdd1943f/README.md) |
| 26&#160;Dec&#160;24&#160;22:05&#160;UTC | IronSIP LLC_1735250708660 SHAKEN 676K | 26&#160;Dec&#160;25&#160;22:05&#160;UTC | false | [view](CERTS/a65f005b1040abd05dc75121ecbf0d487f95ce844bc228cd98f5d3e7ef3d2641/README.md) |
| 13&#160;Jan&#160;25&#160;18:27&#160;UTC | Telnextrix_1736792856068 SHAKEN 077L | 13&#160;Jan&#160;26&#160;18:27&#160;UTC | false | [view](CERTS/d1aca87d35449ada608b8ddda96c4250fee0e2f88505e667e6d86fdd932c91d5/README.md) |
| 22&#160;Jan&#160;25&#160;22:57&#160;UTC | INSTACALL LLC_1737586625863 SHAKEN 281K | 22&#160;Jan&#160;26&#160;19:11&#160;UTC | false | [view](CERTS/e6a042ea51e05367aaa83b2d0be471bec283bff51ec9c6106df1010b52987c7d/README.md) |
| 21&#160;Mar&#160;25&#160;21:01&#160;UTC | VoyageNetworks_1742590882637 SHAKEN 006L | 18&#160;Oct&#160;25&#160;18:41&#160;UTC | false | [view](CERTS/3ad7b737c9351e7fcdb9cde34349e3b50a84a94bccbbc2b80f3ffcbd814c6463/README.md) |
| 24&#160;Mar&#160;25&#160;16:15&#160;UTC | On Air Telecom LLC_1742832914104 SHAKEN 861J | 16&#160;Jul&#160;25&#160;18:07&#160;UTC | false | [view](CERTS/b879f4148c63855ff262338c7ad56f691239d80b589f4733cebf8973c593e940/README.md) |
| 26&#160;Mar&#160;25&#160;20:06&#160;UTC | Infinity Sip_1743019587569 SHAKEN 279K | 26&#160;Mar&#160;26&#160;20:06&#160;UTC | false | [view](CERTS/581a906690a2c6bb1f898acbcc6319cc5939cc4c047e1020a3886a8a561d4270/README.md) |
| 31&#160;Mar&#160;25&#160;20:14&#160;UTC | TheSchmied LLC_1743452080175 SHAKEN 165L | 31&#160;Mar&#160;26&#160;20:14&#160;UTC | false | [view](CERTS/d7bee017f61367bc45f3dbe3cd0f5231a03d166b3641b3096ce133216a72401e/README.md) |
| 03&#160;Apr&#160;25&#160;12:58&#160;UTC | TalkAsiaVoip LLC_1743685125410 SHAKEN 198K | 03&#160;Apr&#160;26&#160;12:58&#160;UTC | false | [view](CERTS/f4d6413626903a53c4dd878d80dba7eeed0ce67663b188e3bfbb03eee29a3981/README.md) |
| 08&#160;Apr&#160;25&#160;05:01&#160;UTC | FlowVOIP LLC._1744088504457 SHAKEN 849K | 08&#160;Apr&#160;26&#160;05:01&#160;UTC | false | [view](CERTS/8b02a3c2a6f90aadabb62241d56afa144fb8934f91e055813dcd7a6f5b264aa7/README.md) |
| 05&#160;May&#160;25&#160;16:14&#160;UTC | Fullnet Advanced Communications Inc_1746461689005 SHAKEN 068F | 05&#160;May&#160;26&#160;16:14&#160;UTC | false | [view](CERTS/eea96bd3fd7a92e912ce1646a25c49d1cce94df7502858b642ff4cebc0a0a8fe/README.md) |
| 09&#160;May&#160;25&#160;17:35&#160;UTC | ARit services LLC_1746812115427 SHAKEN 827K | 16&#160;Jun&#160;25&#160;17:31&#160;UTC | false | [view](CERTS/ec6d65afd90955dbce211cde3f392841a0bcea8d3189c143cf6821312abf7466/README.md) |
| 13&#160;May&#160;25&#160;19:38&#160;UTC | SHAKEN 088K | 13&#160;May&#160;26&#160;19:38&#160;UTC | false | [view](CERTS/9efea51511ce7ae4d8f9df9bbc31489c89bfebc0c1df07148ad06de607b15e16/README.md) |
| 14&#160;May&#160;25&#160;20:10&#160;UTC | beltalk solutions LLC_1747253421716 SHAKEN 745K | 17&#160;Jun&#160;25&#160;13:24&#160;UTC | false | [view](CERTS/d2ea9a8bbb8f8f5dc12fa1ed0d5ddbb229508a8f98b27ca8d4ba06a6cae146f1/README.md) |
| 24&#160;May&#160;25&#160;19:15&#160;UTC | MAQS Solutions LLC_1748114156658 SHAKEN 255K | 23&#160;Jun&#160;25&#160;23:05&#160;UTC | false | [view](CERTS/8435ef6de0ecf33db364226c039e4a05180e239c6162d6a1f1739ec5a05ddfc6/README.md) |
| 26&#160;May&#160;25&#160;21:05&#160;UTC | Tacit Solutions LLC_1748293549184 SHAKEN 066L | 03&#160;Jul&#160;25&#160;21:02&#160;UTC | false | [view](CERTS/42666a0b8a7e261f6036438f102e2f86341bf1fe97296f15eaaa6aba2c92f5e1/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 17&#160;Dec&#160;20&#160;15:31&#160;UTC | Peeringhub Inc Root CA | 12&#160;Dec&#160;40&#160;15:31&#160;UTC | true | [view](CERTS/0ad4adc0b4d93fdb0e628c577020c73b8a5caff750e7e499f80ee2ab362a3f6a/README.md) |
| 22&#160;Jun&#160;22&#160;22:45&#160;UTC | Peeringhub Inc SHAKEN Intermediate CA 2 | 19&#160;Jun&#160;32&#160;22:45&#160;UTC | true | [view](CERTS/f00871963a40b04269c4b019968e42f9f40964cbfb512ff5342307e9942874ce/README.md) |


Generated: 01 Jun 25 21:52 UTC