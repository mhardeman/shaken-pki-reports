# STIR/SHAKEN CA Ecosystem Compliance

## Certificate Smithville Communications CLEC SHAKEN Cert 774D

Tested At: 01 Jun 25 22:57 UTC\
Initial Validity Period: 1095 day(s)\
Remaining Validity Period: 610 day(s)\
Subject: CN=Smithville Communications CLEC SHAKEN Cert 774D, O=Smithville Communications CLEC, C=US\
Issuer: CN=Metaswitch STI-CA SHAKEN Issuing 1\
Link: https://cdn-cr.cgah.tnsi.com/certs/05eb1b2fde3d68f2deffd36d9fadf8c3e42e3272

[View certificate details](https://x509.io/?cert=MIICdjCCAh2gAwIBAgIQf3NvGkdmU9MeB%2BwEK%2FVsUDAKBggqhkjOPQQDAjAtMSswKQYDVQQDDCJNZXRhc3dpdGNoIFNUSS1DQSBTSEFLRU4gSXNzdWluZyAxMB4XDTI0MDIwMjE4MTYzOFoXDTI3MDIwMTE4MTYzOFowcDELMAkGA1UEBhMCVVMxJzAlBgNVBAoMHlNtaXRodmlsbGUgQ29tbXVuaWNhdGlvbnMgQ0xFQzE4MDYGA1UEAwwvU21pdGh2aWxsZSBDb21tdW5pY2F0aW9ucyBDTEVDIFNIQUtFTiBDZXJ0IDc3NEQwWTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAASMGuHykV0PksIY9EFktFn%2BE7Fi9OzSOwW3oAJSasHKn2IsallTmvE2St4KNkjW0ltuMYx2ZqwzfQCPovxa5Z3Wo4HbMIHYMAwGA1UdEwEB%2FwQCMAAwDgYDVR0PAQH%2FBAQDAgXgMBYGCCsGAQUFBwEaBAowCKAGFgQ3NzREMEcGA1UdHwRAMD4wPKA6oDiGNmh0dHBzOi8vYXV0aGVudGljYXRlLWFwaS5pY29uZWN0aXYuY29tL2Rvd25sb2FkL3YxL2NybDAXBgNVHSAEEDAOMAwGCmCGSAGG%2FwkBAQMwHQYDVR0OBBYEFK24eAGjCVIZC2jwj4djxoe%2FRsBCMB8GA1UdIwQYMBaAFM0epwAQENoyHWkaOdXSRgssPIfWMAoGCCqGSM49BAMCA0cAMEQCIA7BxkCPtomtgEUszf5ml6AH71%2BLc1PXVV21Kfu2xv9XAiBDiHCUZGwYaEfkwa8Q8YVxIJxRXg5u%2Bz2sY19vp2Xl0w%3D%3D)

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_subject_cn_spc](../../ISSUES/e_atis_subject_cn_spc/README.md) | error | ATIS1000080 | Common name shall contain the text string 'SHAKEN 774D', but common name is 'Smithville Communications CLEC SHAKEN Cert 774D' |
| [e_atis_ext_key_usage_ee](../../ISSUES/e_atis_ext_key_usage_ee/README.md) | error | ATIS1000080 | The Key Usage extension for STI end-entity certificates shall contain a single key usage value of digitalSignature (0). |
| [e_us_cp_subject_sn_shall](../../ISSUES/e_us_cp_subject_sn_shall/README.md) | error | US_SHAKEN_CP | The DN does not contain a serialNumber attribute. |


Generated: 01 Jun 25 22:59 UTC