# STIR/SHAKEN CA Ecosystem Compliance

## Certificate Google SHAKEN cert 969H

Tested At: 01 Jun 25 22:57 UTC\
Initial Validity Period: 30 day(s)\
Remaining Validity Period: -58 day(s)\
Subject: O=Google Voice Inc., C=US, CN=Google SHAKEN cert 969H\
Issuer: L=Lowell, ST=Massachusettes, OU=US, O=NetNumber Inc, C=US, CN=NetNumber SHAKEN Root Intermediate CA 1\
Link: https://www.gstatic.com/gtp/stir/d6v7d1L0-84r8QKSzIBLLg.pem

[View certificate details](https://x509.io/?cert=MIIC0TCCAlagAwIBAgIJAM8yw7ugKJEdMAoGCCqGSM49BAMCMIGOMTAwLgYDVQQDDCdOZXROdW1iZXIgU0hBS0VOIFJvb3QgSW50ZXJtZWRpYXRlIENBIDExCzAJBgNVBAYTAlVTMRYwFAYDVQQKDA1OZXROdW1iZXIgSW5jMQswCQYDVQQLDAJVUzEXMBUGA1UECAwOTWFzc2FjaHVzZXR0ZXMxDzANBgNVBAcMBkxvd2VsbDAeFw0yNTAzMDUxMjAxNTBaFw0yNTA0MDQxMjAxNTBaMEsxIDAeBgNVBAMMF0dvb2dsZSBTSEFLRU4gY2VydCA5NjlIMQswCQYDVQQGEwJVUzEaMBgGA1UECgwRR29vZ2xlIFZvaWNlIEluYy4wWTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAAT56IQBY6QmPwIvlQtmfood9U2aOaUXbCu%2FENBBh4o0RRZwmc7hPzrVfwWEu1NwNhBXcQ5CD9BeTAAWFZz2ftN%2Bo4HeMIHbMBYGCCsGAQUFBwEaBAowCKAGFgQ5NjlIMAwGA1UdEwEB%2FwQCMAAwDgYDVR0PAQH%2FBAQDAgeAMB8GA1UdIwQYMBaAFHEvyILcqOAi49%2BgaPn4XlyE3uW9MB0GA1UdDgQWBBT0OTcvDFSLG7ksvTJe8cNejcIkCjBHBgNVHR8EQDA%2BMDygOqA4hjZodHRwczovL2F1dGhlbnRpY2F0ZS1hcGkuaWNvbmVjdGl2LmNvbS9kb3dubG9hZC92MS9jcmwwGgYDVR0gAQH%2FBBAwDjAMBgpghkgBhv8JAQEBMAoGCCqGSM49BAMCA2kAMGYCMQDX2GJ%2BW7yBBw5TzQz7QkW1L7zG0Ue2QnEc1LMLyPmiFgMX6OFuS47g0%2FriCHkia1YCMQDbn%2Fh4E6Wrjl4Mz4tCAD%2FAEYQ2a9AfdfiZvye4r3Sk5VXroI%2BFgvzq8r9Krlvpois%3D)

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_subject_cn_spc](../../ISSUES/e_atis_subject_cn_spc/README.md) | error | ATIS1000080 | Common name shall contain the text string 'SHAKEN 969H', but common name is 'Google SHAKEN cert 969H' |
| [e_shaken_certificate_policies_id](../../ISSUES/e_shaken_certificate_policies_id/README.md) | error | US_SHAKEN_CP | The Certificate Policies extension contains an invalid OID value: 2.16.840.1.114569.1.1.1. Available OIDs: 2.16.840.1.114569.1.1.3, 2.16.840.1.114569.1.1.4 |
| [e_atis_ext_certificate_policies](../../ISSUES/e_atis_ext_certificate_policies/README.md) | error | ATIS1000080 | The Certificate Policies extension is marked as critical |


Generated: 01 Jun 25 22:59 UTC