# STIR/SHAKEN CA Ecosystem Compliance

## Certificate Priority Communications SHAKEN Cert 327K

Tested At: 03 Jun 25 00:33 UTC\
Initial Validity Period: 1095 day(s)\
Remaining Validity Period: 97 day(s)\
Subject: CN=Priority Communications SHAKEN Cert 327K, O=Priority Communications, C=US\
Issuer: CN=Metaswitch STI-CA SHAKEN Issuing 1\
Link: https://cdn-cr.cgah.tnsi.com/certs/1a0286ffe0ccbae396beddec370748d2bb0af933

[View certificate details](https://x509.io/?cert=MIICajCCAg%2BgAwIBAgIQB3Cd8LHPFKbK6hNtXBj7WTAKBggqhkjOPQQDAjAtMSswKQYDVQQDDCJNZXRhc3dpdGNoIFNUSS1DQSBTSEFLRU4gSXNzdWluZyAxMB4XDTIyMDkwODE2MDQyOVoXDTI1MDkwNzE2MDQyOVowYjELMAkGA1UEBhMCVVMxIDAeBgNVBAoMF1ByaW9yaXR5IENvbW11bmljYXRpb25zMTEwLwYDVQQDDChQcmlvcml0eSBDb21tdW5pY2F0aW9ucyBTSEFLRU4gQ2VydCAzMjdLMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAEkTtUWzhhDt%2FwBFNUklEu6XHJ2076%2Byu8kdEd7UAWUhRJ1NsTY%2BaVvBuRRYlGv5SySUvmUCqsKdYQz%2BuaknRvYKOB2zCB2DAMBgNVHRMBAf8EAjAAMA4GA1UdDwEB%2FwQEAwIF4DAWBggrBgEFBQcBGgQKMAigBhYEMzI3SzBHBgNVHR8EQDA%2BMDygOqA4hjZodHRwczovL2F1dGhlbnRpY2F0ZS1hcGkuaWNvbmVjdGl2LmNvbS9kb3dubG9hZC92MS9jcmwwFwYDVR0gBBAwDjAMBgpghkgBhv8JAQEDMB0GA1UdDgQWBBQCYplglToMtwd8CytmIxodXT0TyzAfBgNVHSMEGDAWgBTNHqcAEBDaMh1pGjnV0kYLLDyH1jAKBggqhkjOPQQDAgNJADBGAiEA%2Bzddj5Nj6z8fvafpY6fwlM0EY4rJeZw8X6lT2DGACd0CIQDTlPoZM1ThWUoMxvQj2zva%2BhlDC1M0FJCI%2BAIDPMtgLA%3D%3D)

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_ext_key_usage_ee](../../ISSUES/e_atis_ext_key_usage_ee/README.md) | error | ATIS1000080 | The Key Usage extension for STI end-entity certificates shall contain a single key usage value of digitalSignature (0). |
| [e_atis_subject_cn_spc](../../ISSUES/e_atis_subject_cn_spc/README.md) | error | ATIS1000080 | Common name shall contain the text string 'SHAKEN 327K', but common name is 'Priority Communications SHAKEN Cert 327K' |
| [e_us_cp_subject_sn_shall](../../ISSUES/e_us_cp_subject_sn_shall/README.md) | error | US_SHAKEN_CP | The DN does not contain a serialNumber attribute. |

### Not Effective

- e_atis_ext_not_specified
- e_atis_serial_number_size
- e_atis_subject_c_iso
- e_atis_tn_auth_list_spc_format

\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran. Certificates issued before these dates are not executed as the rules may not have been enforce at the time.


Generated: 03 Jun 25 00:33 UTC