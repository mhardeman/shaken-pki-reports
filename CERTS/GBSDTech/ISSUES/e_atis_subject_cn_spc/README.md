# STIR/SHAKEN CA Ecosystem Compliance

## GBSDTech

Name: e_atis_subject_cn_spc\
Source: ATIS1000080\
Citation: ATIS-1000080.v004 / 6.4.1 STI Certificate Requirements\
Effective Date: 16 Jan 22 00:00 UTC\
Description: For end-entity certificate, the Common Name attribute shall contain the text string SHAKEN, followed by a single space, followed by the SPC value identified in the TNAuthList of the end-entity certificate.

### Leaf Certificates

| Status | Subject | Link | Details |
|--------|---------|------|---------|
| error | MYPBXManager SHAKEN | [view](../../CERTS/ea5813855308274fae05fdcae622a159efa47cde2ccf87a9cdf09d9ef43d93f2/README.md) | Cannot get SPC value from the TNAuthList extension, bad TNAuthorizationList, bad TNAuthorizationList ASN.1 raw, asn1: syntax error: data truncated |
| error | allaccesstelecom.com | [view](../../CERTS/474b1c6c0e37b3ac6ac6e812a849b99ec02d055f3fad9bad7817e57ad88d150a/README.md) | Common name shall contain the text string 'SHAKEN 855K', but common name is 'allaccesstelecom.com' |
| error | ccctelecom.com | [view](../../CERTS/7ed6c39c5ac9266fe9fcc9b777f7231de3c57af2fa94edc9073ce13a2b61ff99/README.md) | Common name shall contain the text string 'SHAKEN 816K', but common name is 'ccctelecom.com' |

### CA Certificates

No error, warning, or notice level issues were found


Generated: 01 Jun 25 22:38 UTC