# STIR/SHAKEN CA Ecosystem Compliance

## Ribbon Communications

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 22 certificates were included in the corpus being tested
- 0 certificates in the corpus were skipped because they are duplicates
- 0 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 22 certificates being tested against the remaining rules
- 1.55 issues on average found in unexpired, trusted, and non-compliant certificates
- 100.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 27.27% of certificates are too old to be assessed against currently enforced expectations
- 332 days is the average remaining validity for the certificates in the corpus
- 365 days is the average initial validity for the certificates in the corpus
- 22 certificates expire in the next 30 days
- 1.83 average number of unexpired certificates per OCN observed
- 12 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 6 | [e_atis_ext_crl_distribution_struct](ISSUES/e_atis_ext_crl_distribution_struct/README.md) | ATIS1000080 |
| 10 | [e_atis_ext_not_specified](ISSUES/e_atis_ext_not_specified/README.md) | ATIS1000080 |
| 2 | [e_atis_subject_cn_spc](ISSUES/e_atis_subject_cn_spc/README.md) | ATIS1000080 |
| 16 | [e_shaken_certificate_policies_id](ISSUES/e_shaken_certificate_policies_id/README.md) | US_SHAKEN_CP |

#### CA Certificates

- 3 certificates were included in the corpus being tested
- 0 certificates in the corpus were skipped because they are duplicates
- 0 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 3 certificates being tested against the remaining rules
- 1.00 issues on average found in unexpired, trusted, and non-compliant certificates
- 66.67% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 66.67% of certificates are too old to be assessed against currently enforced expectations
- 6387 days is the average remaining validity for the certificates in the corpus
- 5966 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days

| Instances | Test | Source |
|-----------|------|--------|
| 1 | [e_atis_ext_crl_distribution_ca](ISSUES/e_atis_ext_crl_distribution_ca/README.md) | ATIS1000080 |
| 1 | [e_atis_ext_crl_distribution_struct_ca](ISSUES/e_atis_ext_crl_distribution_struct_ca/README.md) | ATIS1000080 |

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 06&#160;Apr&#160;22&#160;18:20&#160;UTC | Etex STI SHAKEN 3196 | 06&#160;Apr&#160;23&#160;18:20&#160;UTC | true | [view](CERTS/35c9db8a32e1607da879c8261325967abf72ef14d8470dabf68bb17b511969ca/README.md) |
| 29&#160;Apr&#160;22&#160;17:43&#160;UTC | Nuwave Communications SHAKEN 620J | 29&#160;Apr&#160;23&#160;17:42&#160;UTC | true | [view](CERTS/885b7fea5177d66a28bd5dea525144479428e27d2ed1ff7c493d767c73173fbc/README.md) |
| 20&#160;May&#160;22&#160;14:32&#160;UTC | Veracity SHAKEN 716D | 20&#160;May&#160;23&#160;14:32&#160;UTC | true | [view](CERTS/fccfbb719ccc9513231e9ea6f38906f0271f4640f253e1be0780da1e7b5f03ff/README.md) |
| 10&#160;Jun&#160;22&#160;19:00&#160;UTC | Netfortris SHAKEN 8886 | 10&#160;Jun&#160;23&#160;19:00&#160;UTC | true | [view](CERTS/64b7a3eed364e863b36e050a95b35799c594ea1c15c17562611907a2f0dd8bbe/README.md) |
| 16&#160;Jun&#160;22&#160;19:30&#160;UTC | UniVoIP SHAKEN 629J | 16&#160;Jun&#160;23&#160;19:30&#160;UTC | true | [view](CERTS/8bb3168ff6efb4095ace7fbacadb84245992fa74dfadf6c5d9ccafc4685091f8/README.md) |
| 14&#160;Dec&#160;22&#160;14:13&#160;UTC | Empire SHAKEN 087H | 14&#160;Dec&#160;23&#160;14:13&#160;UTC | true | [view](CERTS/29e15bd5cc5b91a308611d9a7c92b759279e4a4a839908894710c0a6fcf40c82/README.md) |
| 03&#160;Apr&#160;23&#160;21:08&#160;UTC | Etex STI SHAKEN 3196 | 02&#160;Apr&#160;24&#160;21:08&#160;UTC | true | [view](CERTS/2accbf5ec4af27017623e3199d568c6ce9e325a47208f4ddda26734089512d29/README.md) |
| 03&#160;Apr&#160;23&#160;22:02&#160;UTC | Nuwave Communications SHAKEN 620J | 02&#160;Apr&#160;24&#160;22:02&#160;UTC | true | [view](CERTS/a9acc6eb541548ac5f8f3aba269c00d545106957dc39e2967dd963c857f34789/README.md) |
| 08&#160;May&#160;23&#160;17:13&#160;UTC | Randolph SHAKEN 0496 | 07&#160;May&#160;24&#160;17:13&#160;UTC | true | [view](CERTS/4104fcb493a3117fa60e0d6a906a076a5292d8614c334754c8a453cda1c49583/README.md) |
| 16&#160;May&#160;23&#160;19:35&#160;UTC | Ironton SHAKEN 1234 0175 | 15&#160;May&#160;24&#160;19:35&#160;UTC | true | [view](CERTS/07fa407eefdb8964682deef6cbc734636b12b9e97acbc4268fef06f0182436d2/README.md) |
| 23&#160;May&#160;23&#160;06:03&#160;UTC | Veracity SHAKEN 716D | 22&#160;May&#160;24&#160;06:03&#160;UTC | true | [view](CERTS/e4aefc8dd53731a5551cd37bb287abb065dbc343e7e71113832134aee28a8c1a/README.md) |
| 07&#160;Jun&#160;23&#160;20:11&#160;UTC | Ribbon SHAKEN 2086 | 06&#160;Jun&#160;24&#160;20:11&#160;UTC | true | [view](CERTS/3b68b514e31a136d42c36b131614bf640f110cfadf0bc75d3bfcb638b411cfe5/README.md) |
| 07&#160;Jun&#160;23&#160;20:25&#160;UTC | Netfortris SHAKEN 8886 | 06&#160;Jun&#160;24&#160;20:25&#160;UTC | true | [view](CERTS/8c0640e8957388ff63bf60c6c9bef298b41d795259bfeb2f3b30985ead768806/README.md) |
| 04&#160;Jan&#160;24&#160;17:59&#160;UTC | Empire SHAKEN 087H | 03&#160;Jan&#160;25&#160;17:59&#160;UTC | true | [view](CERTS/ff4a083ed7527187359cb180383afae989c9a1144ad498e79ad3e3e05f5091fb/README.md) |
| 02&#160;Feb&#160;24&#160;14:07&#160;UTC | UniVoIP SHAKEN 629J | 01&#160;Feb&#160;25&#160;14:07&#160;UTC | true | [view](CERTS/aa242e08e8ae190ac6bb6f4592db929e3ff13278dac0629a9db7be151e253914/README.md) |
| 16&#160;Feb&#160;24&#160;19:41&#160;UTC | Nuwave Communications SHAKEN 620J | 15&#160;Feb&#160;25&#160;19:41&#160;UTC | true | [view](CERTS/e9e2df4bebfaedd61373b3a9ddc2be32e19d81d2431f40ddb790185ded4b6783/README.md) |
| 01&#160;Apr&#160;24&#160;13:12&#160;UTC | Etex STI SHAKEN 3196 | 01&#160;Apr&#160;25&#160;13:12&#160;UTC | true | [view](CERTS/9cb289044279fde9ca74c37807eb10061a1098c816b89e2d146e37c0d377e044/README.md) |
| 29&#160;Apr&#160;24&#160;05:30&#160;UTC | FirstDigital SHAKEN 5727 | 29&#160;Apr&#160;25&#160;05:30&#160;UTC | true | [view](CERTS/cf281053153a12955be41e5b0f99caf1572a1c30b21f62a5c22543bf337740f7/README.md) |
| 08&#160;May&#160;24&#160;17:05&#160;UTC | Ribbon SHAKEN 2086 | 08&#160;May&#160;25&#160;17:05&#160;UTC | true | [view](CERTS/a8850907d694bd9b9787d39dd18aff77488f3ff1d12a045b5a112dde73d8d5b2/README.md) |
| 13&#160;May&#160;24&#160;22:02&#160;UTC | Localtel SHAKEN 3229 | 13&#160;May&#160;25&#160;22:02&#160;UTC | true | [view](CERTS/92063be4763362c7e542a41e3f4ebd030f1816f5ec8600b444be908c646307e5/README.md) |
| 30&#160;May&#160;24&#160;19:04&#160;UTC | Ironton SHAKEN 1234 0175 | 30&#160;May&#160;25&#160;19:04&#160;UTC | true | [view](CERTS/897d53482f78c037e9dd54cc3e62a1a3dba25a5abff81f1faf3ec09ef58bb5a0/README.md) |
| 06&#160;Jun&#160;24&#160;13:33&#160;UTC | Peoples SHAKEN 2130 | 06&#160;Jun&#160;25&#160;13:33&#160;UTC | true | [view](CERTS/506e5980d9b8f24ac2c781f15c58fcc50dd50c9f82d8aac2ac72967211f262db/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 13&#160;May&#160;21&#160;00:00&#160;UTC | SHAKEN Ribbon Issuing CA | 12&#160;May&#160;33&#160;23:59&#160;UTC | true | [view](CERTS/05a71a04eaedbdf4b0534f40768616d7c19c8deb5a3aefd1f4a04b3aab55a48f/README.md) |
| 13&#160;May&#160;21&#160;00:00&#160;UTC | SHAKEN Ribbon Root CA | 12&#160;May&#160;46&#160;23:59&#160;UTC | false | [view](CERTS/7c2799d3642d04f04fe667c3ab251c18689af323acdc43b2fa5f3dc89e3a0f14/README.md) |
| 12&#160;Mar&#160;24&#160;00:00&#160;UTC | SHAKEN Ribbon Issuing CA 2 | 11&#160;Mar&#160;36&#160;23:59&#160;UTC | true | [view](CERTS/2b48949bed753b3edc3645a638704bd1e708cd047117e3fe8af6cb144fa3a8c5/README.md) |


Generated: 02 Jun 25 18:58 UTC