# STIR/SHAKEN CA Ecosystem Compliance

## Certificate Duo Broadband SHAKEN Cert 0401

Tested At: 01 Jun 25 22:33 UTC\
Initial Validity Period: 1095 day(s)\
Remaining Validity Period: 603 day(s)\
Subject: CN=Duo Broadband SHAKEN Cert 0401, O=Duo Broadband\\ , C=US\
Issuer: CN=Metaswitch STI-CA SHAKEN Issuing 1\
Link: https://cdn-cr.cgah.tnsi.com/certs/e6c8f8013706c0cbf0a78beb80d1f21374f43b1d

[View certificate details](https://x509.io/?cert=MIICVTCCAfygAwIBAgIQNj2x9IiaDJuuBM6sxSGT7DAKBggqhkjOPQQDAjAtMSswKQYDVQQDDCJNZXRhc3dpdGNoIFNUSS1DQSBTSEFLRU4gSXNzdWluZyAxMB4XDTI0MDEyNjE2MDcxNVoXDTI3MDEyNTE2MDcxNVowTzELMAkGA1UEBhMCVVMxFzAVBgNVBAoMDkR1byBCcm9hZGJhbmQgMScwJQYDVQQDDB5EdW8gQnJvYWRiYW5kIFNIQUtFTiBDZXJ0IDA0MDEwWTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAARHi2nImlIBVoTbbv%2B50As%2B4qZpXoKQJ%2BTLq58zIMM3W8KGd1EmOj5yJaPKpnub%2FyaIJLdc8aSB8ZhL8UTuStJio4HbMIHYMAwGA1UdEwEB%2FwQCMAAwDgYDVR0PAQH%2FBAQDAgXgMBYGCCsGAQUFBwEaBAowCKAGFgQwNDAxMEcGA1UdHwRAMD4wPKA6oDiGNmh0dHBzOi8vYXV0aGVudGljYXRlLWFwaS5pY29uZWN0aXYuY29tL2Rvd25sb2FkL3YxL2NybDAXBgNVHSAEEDAOMAwGCmCGSAGG%2FwkBAQMwHQYDVR0OBBYEFOnW1xGrcnRXpx6uLkWbVYVGeEHnMB8GA1UdIwQYMBaAFM0epwAQENoyHWkaOdXSRgssPIfWMAoGCCqGSM49BAMCA0cAMEQCIAO0ZcCiIQkWJsBmZa5g3XeQHfs1ZCJTljB1mhki48wdAiAcUO7g9Luk18AcwEakIZX4vvkGJAdHtZtf9rxKdCW7KA%3D%3D)

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_ext_key_usage_ee](../../ISSUES/e_atis_ext_key_usage_ee/README.md) | error | ATIS1000080 | The Key Usage extension for STI end-entity certificates shall contain a single key usage value of digitalSignature (0). |
| [e_us_cp_subject_sn_shall](../../ISSUES/e_us_cp_subject_sn_shall/README.md) | error | US_SHAKEN_CP | The DN does not contain a serialNumber attribute. |
| [e_atis_subject_cn_spc](../../ISSUES/e_atis_subject_cn_spc/README.md) | error | ATIS1000080 | Common name shall contain the text string 'SHAKEN 0401', but common name is 'Duo Broadband SHAKEN Cert 0401' |


Generated: 01 Jun 25 22:39 UTC