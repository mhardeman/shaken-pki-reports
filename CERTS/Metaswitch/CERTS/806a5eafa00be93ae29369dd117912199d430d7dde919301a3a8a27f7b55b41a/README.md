# STIR/SHAKEN CA Ecosystem Compliance

## Certificate Vermont Telephone Company Inc SHAKEN Cert 3332

Tested At: 01 Jun 25 21:45 UTC\
Initial Validity Period: 1095 day(s)\
Remaining Validity Period: 344 day(s)\
Subject: CN=Vermont Telephone Company Inc SHAKEN Cert 3332, O=Vermont Telephone Company\\, Inc., C=US\
Issuer: CN=Metaswitch STI-CA SHAKEN Issuing 1\
Link: https://cdn-cr.cgah.tnsi.com/certs/a61dd4bdaec6164b6bf30c1fd3d6834d49e10a93

[View certificate details](https://x509.io/?cert=MIICdzCCAh2gAwIBAgIQOBOcD%2FpLI2GcvjkCa%2FxooDAKBggqhkjOPQQDAjAtMSswKQYDVQQDDCJNZXRhc3dpdGNoIFNUSS1DQSBTSEFLRU4gSXNzdWluZyAxMB4XDTIzMDUxMjExMTQzOFoXDTI2MDUxMTExMTQzOFowcDELMAkGA1UEBhMCVVMxKDAmBgNVBAoMH1Zlcm1vbnQgVGVsZXBob25lIENvbXBhbnksIEluYy4xNzA1BgNVBAMMLlZlcm1vbnQgVGVsZXBob25lIENvbXBhbnkgSW5jIFNIQUtFTiBDZXJ0IDMzMzIwWTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAARdZNNAI5ocGDQG7NXgEw861g5PrBMxRGfIwuIzsRMR9M38HLB5WFs76s95Ri2Fr6gPGIgTpuCKdMYTzhmQgI%2BAo4HbMIHYMAwGA1UdEwEB%2FwQCMAAwDgYDVR0PAQH%2FBAQDAgXgMBYGCCsGAQUFBwEaBAowCKAGFgQzMzMyMEcGA1UdHwRAMD4wPKA6oDiGNmh0dHBzOi8vYXV0aGVudGljYXRlLWFwaS5pY29uZWN0aXYuY29tL2Rvd25sb2FkL3YxL2NybDAXBgNVHSAEEDAOMAwGCmCGSAGG%2FwkBAQMwHQYDVR0OBBYEFNriHZugn8nri7Cxo55edd0hU2FwMB8GA1UdIwQYMBaAFM0epwAQENoyHWkaOdXSRgssPIfWMAoGCCqGSM49BAMCA0gAMEUCIQC%2BbLiYsDSXFmzfKRHGaKAdq28D0iBZZf%2FfuPRo70xiygIgeD%2Fzeqae1nwjDnPIjTAIOCyZrUrOVPfSHU2uULFLcys%3D)

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_subject_cn_spc](../../ISSUES/e_atis_subject_cn_spc/README.md) | error | ATIS1000080 | Common name shall contain the text string 'SHAKEN 3332', but common name is 'Vermont Telephone Company Inc SHAKEN Cert 3332' |
| [e_atis_ext_key_usage_ee](../../ISSUES/e_atis_ext_key_usage_ee/README.md) | error | ATIS1000080 | The Key Usage extension for STI end-entity certificates shall contain a single key usage value of digitalSignature (0). |
| [e_us_cp_subject_sn_shall](../../ISSUES/e_us_cp_subject_sn_shall/README.md) | error | US_SHAKEN_CP | The DN does not contain a serialNumber attribute. |


Generated: 01 Jun 25 21:52 UTC