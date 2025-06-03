# STIR/SHAKEN CA Ecosystem Compliance

[Approved Certificate Authorities](https://ecosystemcompliance.martinisecurity.com/#:~:text=Approved%20Certificate%20Authorities) in the STIR/SHAKEN ecosystem are required to meet technical requirements from [ATIS-1000080](https://access.atis.org/apps/group_public/document.php?document_id=62163) and policy requirements from the supporting CA ecosystem’s [Certificate Policy](https://authenticate.iconectiv.com/documents-authenticate).

This report is broken int two parts:
1. One generated using [Zlint](https://github.com/zmap/zlint) a tool commonly used to asses CA ecosystem compliance with such requirements. The tests used to generate this report are currently not part of the main [Zlint](https://github.com/martinisecurity/zlint) distribution but can be found here.
2. One generated with a custom script that eumerates the known STIR/SHAKEN certificates and asses each repository against the current rule set . The source for this test can be found here while the report itself can be found [here](REPOS/README.md).

## Summary

### Leaf Certificates

- 9728 potential certificate URLs were requested for retrieval
- 8617 candidate certificates were parsed from the potential certificate URLs
- 160 certificates in the candidate corpus were excluded because they are duplicates
- 1479 certificates in the candidate corpus were excluded because they were not valid during the target validity period
- 18 certificates in the candidate corpus were excluded because they did not chain to program trust anchors
- 6960 valid certificates were tested against the remaining rules
- 1.53 issues on average found in valid but non-compliant certificates
- 46.34% of valid certificates contain one or more Error level issue
- 0.00% of valid certificates contain one or more Warning level issue
- 0.00% of valid certificates contain one or more Notice level issue
- 0.91% of valid certificates are too old to be assessed against currently enforced expectations
- 64 days is the average remaining validity of the valid certificates
- 64 days is the average initial validity of the valid certificates
- 12.71 average number of unexpired certificates per OCN observed
- 678 unique OCNs observed in unexpired and valid certificate corpus

### CA Certificates

- 47 potential certificate URLs were requested for retrieval
- 47 candidate certificates were parsed from the potential certificate URLs
- 0 certificates in the candidate corpus were excluded because they are duplicates
- 0 certificates in the candidate corpus were excluded because they were not valid during the target validity period
- 5 certificates in the candidate corpus were excluded because they did not chain to program trust anchors
- 42 valid certificates were tested against the remaining rules
- 2.16 issues on average found in valid but non-compliant certificates
- 45.24% of valid certificates contain one or more Error level issue
- 0.00% of valid certificates contain one or more Warning level issue
- 0.00% of valid certificates contain one or more Notice level issue
- 64.29% of valid certificates are too old to be assessed against currently enforced expectations
- 5660 days is the average remaining validity of the valid certificates
- 5590 days is the average initial validity of the valid certificates

## Certificate Repository URL

- 25.42% of certificate repository URLs contain one or more Error level issue
- 25.65% of certificates repository URLs contain one or more Warning level issue
- 0.00% of certificates repository URLs contain one or more Notice level issue

## Details

\* The percent of certificates per issuer is calculated against total certificates from all issuers.\
\*\* The percent of errors, warnings and notices is calculated against total observed certificates from the specified issuer.\
\*\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran. Certificates issued before these dates are not executed as the rules may not have been enforce at the time.

### Leaf Certificates

| Issuers | Certificates | Errors | Warnings | Notices | Not Effective |
|---------|--------------|--------|----------|---------|---------------|
| [GBSDTech](CERTS/GBSDTech/README.md#leaf-certificates) | 3 (0.04%) | 3 (100.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Martini Security](CERTS/Martini_Security/README.md#leaf-certificates) | 2262 (32.50%) | 137 (6.06%) | 0 (0.00%) | 0 (0.00%) | 2 (0.09%) |
| [Metaswitch](CERTS/Metaswitch/README.md#leaf-certificates) | 91 (1.31%) | 91 (100.00%) | 0 (0.00%) | 0 (0.00%) | 41 (45.05%) |
| [NetNumber](CERTS/NetNumber/README.md#leaf-certificates) | 33 (0.47%) | 33 (100.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Neustar](CERTS/Neustar/README.md#leaf-certificates) | 96 (1.38%) | 96 (100.00%) | 0 (0.00%) | 0 (0.00%) | 10 (10.42%) |
| [Peeringhub](CERTS/Peeringhub/README.md#leaf-certificates) | 61 (0.88%) | 13 (21.31%) | 0 (0.00%) | 0 (0.00%) | 2 (3.28%) |
| [Ribbon Communications](CERTS/Ribbon_Communications/README.md#leaf-certificates) | 17 (0.24%) | 17 (100.00%) | 0 (0.00%) | 0 (0.00%) | 1 (5.88%) |
| [Sansay](CERTS/Sansay/README.md#leaf-certificates) | 1466 (21.06%) | 1466 (100.00%) | 0 (0.00%) | 0 (0.00%) | 6 (0.41%) |
| [T-Mobile](CERTS/T-Mobile/README.md#leaf-certificates) | 3 (0.04%) | 3 (100.00%) | 0 (0.00%) | 0 (0.00%) | 1 (33.33%) |
| [Telonium](CERTS/Telonium/README.md#leaf-certificates) | 23 (0.33%) | 4 (17.39%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [TransNexus](CERTS/TransNexus/README.md#leaf-certificates) | 2905 (41.74%) | 1362 (46.88%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| **Total** | 6960 (100.00%) | 3225 (46.34%) | 0 (0.00%) | 0 (0.00%) | 63 (0.91%) |

### CA Certificates

| Issuers | Certificates | Errors | Warnings | Notices | Not Effective |
|---------|--------------|--------|----------|---------|---------------|
| [CTIA](CERTS/CTIA/README.md#ca-certificates) | 1 (2.38%) | 1 (100.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Comcast](CERTS/Comcast/README.md#ca-certificates) | 1 (2.38%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 1 (100.00%) |
| [GBSDTech](CERTS/GBSDTech/README.md#ca-certificates) | 4 (9.52%) | 3 (75.00%) | 0 (0.00%) | 0 (0.00%) | 2 (50.00%) |
| [Martini Security](CERTS/Martini_Security/README.md#ca-certificates) | 4 (9.52%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 2 (50.00%) |
| [Metaswitch](CERTS/Metaswitch/README.md#ca-certificates) | 4 (9.52%) | 4 (100.00%) | 0 (0.00%) | 0 (0.00%) | 2 (50.00%) |
| [NetNumber](CERTS/NetNumber/README.md#ca-certificates) | 3 (7.14%) | 2 (66.67%) | 0 (0.00%) | 0 (0.00%) | 3 (100.00%) |
| [Neustar](CERTS/Neustar/README.md#ca-certificates) | 6 (14.29%) | 1 (16.67%) | 0 (0.00%) | 0 (0.00%) | 6 (100.00%) |
| [Peeringhub](CERTS/Peeringhub/README.md#ca-certificates) | 2 (4.76%) | 2 (100.00%) | 0 (0.00%) | 0 (0.00%) | 2 (100.00%) |
| [Ribbon Communications](CERTS/Ribbon_Communications/README.md#ca-certificates) | 3 (7.14%) | 2 (66.67%) | 0 (0.00%) | 0 (0.00%) | 2 (66.67%) |
| [SOMOS](CERTS/SOMOS/README.md#ca-certificates) | 1 (2.38%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Sansay](CERTS/Sansay/README.md#ca-certificates) | 2 (4.76%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 2 (100.00%) |
| [T-Mobile](CERTS/T-Mobile/README.md#ca-certificates) | 3 (7.14%) | 1 (33.33%) | 0 (0.00%) | 0 (0.00%) | 3 (100.00%) |
| [Telonium](CERTS/Telonium/README.md#ca-certificates) | 5 (11.90%) | 3 (60.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [TransNexus](CERTS/TransNexus/README.md#ca-certificates) | 3 (7.14%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 2 (66.67%) |
| **Total** | 42 (100.00%) | 19 (45.24%) | 0 (0.00%) | 0 (0.00%) | 27 (64.29%) |

### Key

| Type | Description |
|------|-------------|
| Errors | Tests in which the specifications are unambiguous on what the expected behavior must be. |
| Warnings | Tests in which the specifications are ambiguous or are provide only a recommendation. |
| Notices | Tests in which industry best practices are not followed. |
| Not Effective | Tests that exist in the current specifications but were not in effect at the time of issuance. |


Generated: 03 Jun 25 02:15 UTC