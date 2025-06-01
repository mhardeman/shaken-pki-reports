# STIR/SHAKEN CA Ecosystem Compliance

## Certificate Lemonweir Valley Telephone Company SHAKEN Cert 0900

Tested At: 01 Jun 25 22:59 UTC\
Initial Validity Period: 1095 day(s)\
Remaining Validity Period: 321 day(s)\
Subject: CN=Lemonweir Valley Telephone Company SHAKEN Cert 0900, O=Lemonweir Valley Telephone Company, C=US\
Issuer: CN=Metaswitch STI-CA SHAKEN Issuing 1\
Link: https://cdn-cr.cgah.tnsi.com/certs/a9a2447c07d34796f48eba3c111c847c93675956

[View certificate details](https://x509.io/?cert=MIICfjCCAiWgAwIBAgIQX0BX6cemlpy7UzfDREABQjAKBggqhkjOPQQDAjAtMSswKQYDVQQDDCJNZXRhc3dpdGNoIFNUSS1DQSBTSEFLRU4gSXNzdWluZyAxMB4XDTIzMDQxOTE0MjMwOVoXDTI2MDQxODE0MjMwOVoweDELMAkGA1UEBhMCVVMxKzApBgNVBAoMIkxlbW9ud2VpciBWYWxsZXkgVGVsZXBob25lIENvbXBhbnkxPDA6BgNVBAMMM0xlbW9ud2VpciBWYWxsZXkgVGVsZXBob25lIENvbXBhbnkgU0hBS0VOIENlcnQgMDkwMDBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABLcycw1CyV6xkqEsh%2B8EQ6nbsoCNdev6gKAlQdRPXgjTi99zrHVSlMdlD041E9SdNRb1GiVNoTnr5uvMv8nyvlWjgdswgdgwDAYDVR0TAQH%2FBAIwADAOBgNVHQ8BAf8EBAMCBeAwFgYIKwYBBQUHARoECjAIoAYWBDA5MDAwRwYDVR0fBEAwPjA8oDqgOIY2aHR0cHM6Ly9hdXRoZW50aWNhdGUtYXBpLmljb25lY3Rpdi5jb20vZG93bmxvYWQvdjEvY3JsMBcGA1UdIAQQMA4wDAYKYIZIAYb%2FCQEBAzAdBgNVHQ4EFgQUrxpPo2i4%2FUL%2BZZtp4oq%2BhW0p4McwHwYDVR0jBBgwFoAUzR6nABAQ2jIdaRo51dJGCyw8h9YwCgYIKoZIzj0EAwIDRwAwRAIgIZyeHs%2FQTsBx8k9CyVUrXfXYTay5%2FmiGo5sH8U1px0kCIGCjZdwBYwVJaDEMfSTJYQEkghlXLYzmu9LFlBgXmZ3q)

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_us_cp_subject_sn_shall](../../ISSUES/e_us_cp_subject_sn_shall/README.md) | error | US_SHAKEN_CP | The DN does not contain a serialNumber attribute. |
| [e_atis_subject_cn_spc](../../ISSUES/e_atis_subject_cn_spc/README.md) | error | ATIS1000080 | Common name shall contain the text string 'SHAKEN 0900', but common name is 'Lemonweir Valley Telephone Company SHAKEN Cert 0900' |
| [e_atis_ext_key_usage_ee](../../ISSUES/e_atis_ext_key_usage_ee/README.md) | error | ATIS1000080 | The Key Usage extension for STI end-entity certificates shall contain a single key usage value of digitalSignature (0). |


Generated: 01 Jun 25 22:59 UTC