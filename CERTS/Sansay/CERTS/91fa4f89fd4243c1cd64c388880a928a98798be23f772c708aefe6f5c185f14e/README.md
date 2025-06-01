# STIR/SHAKEN CA Ecosystem Compliance

## Certificate SHAKEN 563j

Tested At: 01 Jun 25 21:45 UTC\
Initial Validity Period: 30 day(s)\
Remaining Validity Period: -31 day(s)\
Subject: CN=SHAKEN 563j, O=Threshold Communications Inc, C=US\
Issuer: CN=SHAKEN Sansay Intermediate CA US WEST 1, OU=Sansay CA, O=Sansay Corporation, ST=California, C=US\
Link: https://cr.sansay.com/563j/429C7C70711E3820F0B8E1DEAE6FF3262264C57D.pem

[View certificate details](https://x509.io/?cert=MIICrjCCAlSgAwIBAgIUQpx8cHEeOCDwuOHerm%2FzJiJkxX0wCgYIKoZIzj0EAwIwgYUxCzAJBgNVBAYTAlVTMRMwEQYDVQQIDApDYWxpZm9ybmlhMRswGQYDVQQKDBJTYW5zYXkgQ29ycG9yYXRpb24xEjAQBgNVBAsMCVNhbnNheSBDQTEwMC4GA1UEAwwnU0hBS0VOIFNhbnNheSBJbnRlcm1lZGlhdGUgQ0EgVVMgV0VTVCAxMB4XDTI1MDQwMTE2NDkwNFoXDTI1MDUwMTE2NDkwNFowSjELMAkGA1UEBhMCVVMxJTAjBgNVBAoMHFRocmVzaG9sZCBDb21tdW5pY2F0aW9ucyBJbmMxFDASBgNVBAMMC1NIQUtFTiA1NjNqMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAEfi2lHn336oEMqtpsROBxooiSG9aIQHQqZ4y64BkRyTNWcB9iA6FKHhGxJ1rH11KAHbQrpJ1Cd0cMJAhbvILRraOB2zCB2DAWBggrBgEFBQcBGgQKMAigBhYENTYzajAXBgNVHSAEEDAOMAwGCmCGSAGG%2FwkBAQQwHQYDVR0OBBYEFDGBlhjOWW4zpNoe1PgjOxu77DvsMB8GA1UdIwQYMBaAFKzTk%2FVDQ8wKvkVYFxN9knzcwwFGMEcGA1UdHwRAMD4wPKA6oDiGNmh0dHBzOi8vYXV0aGVudGljYXRlLWFwaS5pY29uZWN0aXYuY29tL2Rvd25sb2FkL3YxL2NybDAMBgNVHRMBAf8EAjAAMA4GA1UdDwEB%2FwQEAwIHgDAKBggqhkjOPQQDAgNIADBFAiAKFnuXT0Bv6Kt%2B53IpCwhPJ3yaaxSyRhJ27cB%2FPn%2BLzwIhANruB1dHdAVfoVFMvUr4apm7U26oJm%2F3JxZpHJQxXGUZ)

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_tn_auth_list_spc_format](../../ISSUES/e_atis_tn_auth_list_spc_format/README.md) | error | ATIS1000080 | the SPC value '563j' contains characters other than uppercase letters and numbers |
| [e_atis_ext_crl_distribution_struct](../../ISSUES/e_atis_ext_crl_distribution_struct/README.md) | error | ATIS1000080 | CRL Distribution Point shall contain a CRLIssuer field |


Generated: 01 Jun 25 21:52 UTC