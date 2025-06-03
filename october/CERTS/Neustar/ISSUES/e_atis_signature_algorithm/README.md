# STIR/SHAKEN CA Ecosystem Compliance

## Neustar

Name: e_atis_signature_algorithm\
Source: ATIS1000080\
Citation: ATIS-1000080.v003 / 6.4.1 SHAKEN Certificate Requirements\
Effective Date: 03 Dec 20 00:00 UTC\
Description: STI certificates shall contain a Signature Algorithm field with the value 'ecdsa-with-SHA256'

### Leaf Certificates

| Status | Subject | Link | Details |
|--------|---------|------|---------|
| error | SHAKEN-6744 | [view](../../CERTS/414671d6f2e7beffdd958279b4cb2e705c5ee59f107aa1fb7b2a06008ae117b6/README.md) | SignatureAlgorithm field is not 'ecdsa-with-SHA256', got 1.2.840.113549.1.1.11 |

### CA Certificates

No error, warning, or notice level issues were found


Generated: 03 Jun 25 02:15 UTC