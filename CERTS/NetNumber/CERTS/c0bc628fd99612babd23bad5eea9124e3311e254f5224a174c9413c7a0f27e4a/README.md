# STIR/SHAKEN CA Ecosystem Compliance

## Certificate HD CARRIER LLC

Tested At: 01 Jun 25 21:43 UTC\
Initial Validity Period: 30 day(s)\
Remaining Validity Period: -30 day(s)\
Subject: L=Long Beach, ST=California, O=HD CARRIER LLC, C=US, CN=HD CARRIER LLC\
Issuer: L=Lowell, ST=Massachusettes, OU=US, O=NetNumber Inc, C=US, CN=NetNumber SHAKEN Root Intermediate CA 1\
Link: https://d64db847f381fcb974ab1b6150b49a91.cxstatic.com/f/808c1df2-014a-4f16-a31f-1b7f260b9fe5

[View certificate details](https://x509.io/?cert=MIICpTCCAiugAwIBAgIJAOHBZq%2FhoI6%2FMAoGCCqGSM49BAMCMIGOMTAwLgYDVQQDDCdOZXROdW1iZXIgU0hBS0VOIFJvb3QgSW50ZXJtZWRpYXRlIENBIDExCzAJBgNVBAYTAlVTMRYwFAYDVQQKDA1OZXROdW1iZXIgSW5jMQswCQYDVQQLDAJVUzEXMBUGA1UECAwOTWFzc2FjaHVzZXR0ZXMxDzANBgNVBAcMBkxvd2VsbDAeFw0yNTA0MDIwMDAwMDBaFw0yNTA1MDEyMzU5NTlaMGkxFzAVBgNVBAMMDkhEIENBUlJJRVIgTExDMQswCQYDVQQGEwJVUzEXMBUGA1UECgwOSEQgQ0FSUklFUiBMTEMxEzARBgNVBAgMCkNhbGlmb3JuaWExEzARBgNVBAcMCkxvbmcgQmVhY2gwWTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAAQ%2BjoiWl6irYziXFAhlLCYvdJM89omNmggSAFtV%2F6DLW2LIqknZPy7jK3ki%2Fj1x9MSrlQ71x66y2t16Da5xroQto4GVMIGSMBYGCCsGAQUFBwEaBAowCKAGFgQzMjFKMAwGA1UdEwEB%2FwQCMAAwDgYDVR0PAQH%2FBAQDAgeAMB8GA1UdIwQYMBaAFHEvyILcqOAi49%2BgaPn4XlyE3uW9MB0GA1UdDgQWBBRO4uQ%2Ffm72A4oT%2Fr6226RSEv8OhTAaBgNVHSABAf8EEDAOMAwGCmCGSAGG%2FwkBAQEwCgYIKoZIzj0EAwIDaAAwZQIwO7Uo5E%2FO%2For5qTa9X4PwwzGMCP6HXgub5wMYdXsTrqCc5hsyLkdolPY1tGyYI7wkAjEA8XAp814i9XL9pl%2By2Ep8k3OyBk0ZCT2bxUomuK2VjVeDbbrtNOW4kSnbTc15qAui)

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_subject_cn_spc](../../ISSUES/e_atis_subject_cn_spc/README.md) | error | ATIS1000080 | Common name shall contain the text string 'SHAKEN 321J', but common name is 'HD CARRIER LLC' |
| [e_atis_ext_crl_distribution](../../ISSUES/e_atis_ext_crl_distribution/README.md) | error | ATIS1000080 | STI End-Entity certificates shall contain a CRL Distribution Points extension |
| [e_shaken_certificate_policies_id](../../ISSUES/e_shaken_certificate_policies_id/README.md) | error | US_SHAKEN_CP | The Certificate Policies extension contains an invalid OID value: 2.16.840.1.114569.1.1.1. Available OIDs: 2.16.840.1.114569.1.1.3, 2.16.840.1.114569.1.1.4 |
| [e_atis_ext_certificate_policies](../../ISSUES/e_atis_ext_certificate_policies/README.md) | error | ATIS1000080 | The Certificate Policies extension is marked as critical |
| [e_atis_subject_cn](../../ISSUES/e_atis_subject_cn/README.md) | error | ATIS1000080 | Common Name attribute 'HD CARRIER LLC' does not contain 'SHAKEN' |


Generated: 01 Jun 25 21:52 UTC