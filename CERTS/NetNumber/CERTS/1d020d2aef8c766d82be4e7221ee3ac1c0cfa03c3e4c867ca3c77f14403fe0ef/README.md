# STIR/SHAKEN CA Ecosystem Compliance

## Certificate Baltimore-Washington Telephone Company SHAKEN cert 8697

Tested At: 01 Jun 25 21:48 UTC\
Initial Validity Period: 30 day(s)\
Remaining Validity Period: 5 day(s)\
Subject: O=Baltimore-Washington Telephone Company, C=US, CN=Baltimore-Washington Telephone Company SHAKEN cert 8697\
Issuer: L=Lowell, ST=Massachusettes, OU=US, O=NetNumber Inc, C=US, CN=NetNumber SHAKEN Root Intermediate CA 1\
Link: https://bwt.io/8697a2.crt

[View certificate details](https://x509.io/?cert=MIICvDCCAkOgAwIBAgIJANbSjYjfNni2MAoGCCqGSM49BAMCMIGOMTAwLgYDVQQDDCdOZXROdW1iZXIgU0hBS0VOIFJvb3QgSW50ZXJtZWRpYXRlIENBIDExCzAJBgNVBAYTAlVTMRYwFAYDVQQKDA1OZXROdW1iZXIgSW5jMQswCQYDVQQLDAJVUzEXMBUGA1UECAwOTWFzc2FjaHVzZXR0ZXMxDzANBgNVBAcMBkxvd2VsbDAeFw0yNTA1MDcwNzAwMDBaFw0yNTA2MDYwNzAwMDBaMIGAMUAwPgYDVQQDDDdCYWx0aW1vcmUtV2FzaGluZ3RvbiBUZWxlcGhvbmUgQ29tcGFueSBTSEFLRU4gY2VydCA4Njk3MQswCQYDVQQGEwJVUzEvMC0GA1UECgwmQmFsdGltb3JlLVdhc2hpbmd0b24gVGVsZXBob25lIENvbXBhbnkwWTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAAR7PqgstTJ0GphOuUb64MPJkWWX6Nd%2FNz9kYzpj%2BjtDTPIPk2EMAzGCSNNBFuRF0obuipQkJf6mYYHRZPSkS%2BqBo4GVMIGSMBYGCCsGAQUFBwEaBAowCKAGFgQ4Njk3MAwGA1UdEwEB%2FwQCMAAwDgYDVR0PAQH%2FBAQDAgeAMB8GA1UdIwQYMBaAFHEvyILcqOAi49%2BgaPn4XlyE3uW9MB0GA1UdDgQWBBS8CFGQU1KbdE7xcbVIUHRr4NPURTAaBgNVHSABAf8EEDAOMAwGCmCGSAGG%2FwkBAQEwCgYIKoZIzj0EAwIDZwAwZAIwOjBEV6eoc3wB4HgdYKumpCoqGRijyoohCWOySx%2B9CcBsxDvWnEMTChZFuVPUZe8DAjB4o%2BW3h0N64pmJq5yuDyyC3xOangOv75z%2FoCWrmNnd8oZonx7RDshB7h%2FVIvOEWZY%3D)

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_ext_certificate_policies](../../ISSUES/e_atis_ext_certificate_policies/README.md) | error | ATIS1000080 | The Certificate Policies extension is marked as critical |
| [e_atis_subject_cn_spc](../../ISSUES/e_atis_subject_cn_spc/README.md) | error | ATIS1000080 | Common name shall contain the text string 'SHAKEN 8697', but common name is 'Baltimore-Washington Telephone Company SHAKEN cert 8697' |
| [e_atis_ext_crl_distribution](../../ISSUES/e_atis_ext_crl_distribution/README.md) | error | ATIS1000080 | STI End-Entity certificates shall contain a CRL Distribution Points extension |
| [e_shaken_certificate_policies_id](../../ISSUES/e_shaken_certificate_policies_id/README.md) | error | US_SHAKEN_CP | The Certificate Policies extension contains an invalid OID value: 2.16.840.1.114569.1.1.1. Available OIDs: 2.16.840.1.114569.1.1.3, 2.16.840.1.114569.1.1.4 |


Generated: 01 Jun 25 21:52 UTC