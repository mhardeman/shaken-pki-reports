# STIR/SHAKEN CA Ecosystem Compliance

## Certificate HD CARRIER LLC

Tested At: 01 Jun 25 22:28 UTC\
Initial Validity Period: 30 day(s)\
Remaining Validity Period: 0 day(s)\
Subject: L=Long Beach, ST=California, O=HD CARRIER LLC, C=US, CN=HD CARRIER LLC\
Issuer: L=Lowell, ST=Massachusettes, OU=US, O=NetNumber Inc, C=US, CN=NetNumber SHAKEN Root Intermediate CA 1\
Link: https://d64db847f381fcb974ab1b6150b49a91.cxstatic.com/f/a19ad33f-2105-43c4-be8e-ee8bb0efd1d2

[View certificate details](https://x509.io/?cert=MIICozCCAimgAwIBAgIHSAS3w9XpCzAKBggqhkjOPQQDAjCBjjEwMC4GA1UEAwwnTmV0TnVtYmVyIFNIQUtFTiBSb290IEludGVybWVkaWF0ZSBDQSAxMQswCQYDVQQGEwJVUzEWMBQGA1UECgwNTmV0TnVtYmVyIEluYzELMAkGA1UECwwCVVMxFzAVBgNVBAgMDk1hc3NhY2h1c2V0dGVzMQ8wDQYDVQQHDAZMb3dlbGwwHhcNMjUwNTAyMDAwMDAwWhcNMjUwNTMxMjM1OTU5WjBpMRcwFQYDVQQDDA5IRCBDQVJSSUVSIExMQzELMAkGA1UEBhMCVVMxFzAVBgNVBAoMDkhEIENBUlJJRVIgTExDMRMwEQYDVQQIDApDYWxpZm9ybmlhMRMwEQYDVQQHDApMb25nIEJlYWNoMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAEPo6Ilpeoq2M4lxQIZSwmL3STPPaJjZoIEgBbVf%2Bgy1tiyKpJ2T8u4yt5Iv49cfTEq5UO9ceustrdeg2uca6ELaOBlTCBkjAWBggrBgEFBQcBGgQKMAigBhYEMzIxSjAMBgNVHRMBAf8EAjAAMA4GA1UdDwEB%2FwQEAwIHgDAfBgNVHSMEGDAWgBRxL8iC3KjgIuPfoGj5%2BF5chN7lvTAdBgNVHQ4EFgQUTuLkP35u9gOKE%2F6%2BttukUhL%2FDoUwGgYDVR0gAQH%2FBBAwDjAMBgpghkgBhv8JAQEBMAoGCCqGSM49BAMCA2gAMGUCMBe47BQJkubcmxGs9rOzwOg9UsJg%2FgpToKUk%2BhjmKj0GbLdBLmg3wuX3kMJuRCw2RQIxAIRoI240PB6eCQmc292sGLCM%2FNMFXSe7sAAseYEfAyzyY5h7Oy%2FnvEdvjpttxKgdoA%3D%3D)

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_shaken_certificate_policies_id](../../ISSUES/e_shaken_certificate_policies_id/README.md) | error | US_SHAKEN_CP | The Certificate Policies extension contains an invalid OID value: 2.16.840.1.114569.1.1.1. Available OIDs: 2.16.840.1.114569.1.1.3, 2.16.840.1.114569.1.1.4 |
| [e_atis_ext_crl_distribution](../../ISSUES/e_atis_ext_crl_distribution/README.md) | error | ATIS1000080 | STI End-Entity certificates shall contain a CRL Distribution Points extension |
| [e_atis_serial_number_size](../../ISSUES/e_atis_serial_number_size/README.md) | error | ATIS1000080 | STI certificates shall have a serial number that contains at least 64 bits, got 55 |
| [e_atis_subject_cn_spc](../../ISSUES/e_atis_subject_cn_spc/README.md) | error | ATIS1000080 | Common name shall contain the text string 'SHAKEN 321J', but common name is 'HD CARRIER LLC' |
| [e_atis_ext_certificate_policies](../../ISSUES/e_atis_ext_certificate_policies/README.md) | error | ATIS1000080 | The Certificate Policies extension is marked as critical |
| [e_atis_subject_cn](../../ISSUES/e_atis_subject_cn/README.md) | error | ATIS1000080 | Common Name attribute 'HD CARRIER LLC' does not contain 'SHAKEN' |


Generated: 01 Jun 25 22:39 UTC