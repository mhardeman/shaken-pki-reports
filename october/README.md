# STIR/SHAKEN CA Ecosystem Compliance

[Approved Certificate Authorities](https://ecosystemcompliance.martinisecurity.com/#:~:text=Approved%20Certificate%20Authorities) in the STIR/SHAKEN ecosystem are required to meet technical requirements from [ATIS-1000080](https://access.atis.org/apps/group_public/document.php?document_id=62163) and policy requirements from the supporting CA ecosystem’s [Certificate Policy](https://authenticate.iconectiv.com/documents-authenticate).

This report is broken int two parts:
1. One generated using [Zlint](https://github.com/zmap/zlint) a tool commonly used to asses CA ecosystem compliance with such requirements. The tests used to generate this report are currently not part of the main [Zlint](https://github.com/martinisecurity/zlint) distribution but can be found here.
2. One generated with a custom script that eumerates the known STIR/SHAKEN certificates and asses each repository against the current rule set . The source for this test can be found here while the report itself can be found [here](REPOS/README.md).

## Summary

### Leaf Certificates

- 117 certificates were included in the corpus being tested
- 5 certificates in the corpus were skipped because they are duplicates
- 46 certificates in the corpus were skipped because they are expired
- 2 certificates in the corpus were skipped because they are not currently trusted
- 64 certificates being tested against the remaining rules
- 2.37 issues on average found in unexpired, trusted, and non-compliant certificates
- 92.19% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 12.50% of certificates are too old to be assessed against currently enforced expectations
- 955 days is the average remaining validity for the certificates in the corpus
- 969 days is the average initial validity for the certificates in the corpus
- 4 certificates expire in the next 30 days
- 1.41 average number of unexpired certificates per OCN observed
- 83 unique OCNs observed in unexpired and valid certificate corpus

### CA Certificates

- 30 certificates were included in the corpus being tested
- 0 certificates in the corpus were skipped because they are duplicates
- 0 certificates in the corpus were skipped because they are expired
- 1 certificates in the corpus were skipped because they are not currently trusted
- 29 certificates being tested against the remaining rules
- 2.18 issues on average found in unexpired, trusted, and non-compliant certificates
- 37.93% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 65.52% of certificates are too old to be assessed against currently enforced expectations
- 6239 days is the average remaining validity for the certificates in the corpus
- 6157 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days

## Certificate Repository URL

- 100.00% of certificate repository URLs contain one or more Error level issue
- 100.00% of certificates repository URLs contain one or more Warning level issue
- 0.00% of certificates repository URLs contain one or more Notice level issue

## Details

\* The percent of certificates per issuer is calculated against total certificates from all issuers.\
\*\* The percent of errors, warnings and notices is calculated against total observed certificates from the specified issuer.\
\*\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran. Certificates issued before these dates are not executed as the rules may not have been enforce at the time.

### Leaf Certificates

| Issuers | Certificates | Errors | Warnings | Notices | Not Effective |
|---------|--------------|--------|----------|---------|---------------|
| [Metaswitch](CERTS/Metaswitch/README.md#leaf-certificates) | 53 (82.81%) | 53 (100.00%) | 0 (0.00%) | 0 (0.00%) | 8 (15.09%) |
| [Neustar](CERTS/Neustar/README.md#leaf-certificates) | 4 (6.25%) | 4 (100.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Peeringhub](CERTS/Peeringhub/README.md#leaf-certificates) | 4 (6.25%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Sansay](CERTS/Sansay/README.md#leaf-certificates) | 2 (3.12%) | 2 (100.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Telonium](CERTS/Telonium/README.md#leaf-certificates) | 1 (1.56%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| **Total** | 64 (100.00%) | 59 (92.19%) | 0 (0.00%) | 0 (0.00%) | 8 (12.50%) |

### CA Certificates

| Issuers | Certificates | Errors | Warnings | Notices | Not Effective |
|---------|--------------|--------|----------|---------|---------------|
| [CTIA](CERTS/CTIA/README.md#ca-certificates) | 1 (3.45%) | 1 (100.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Comcast](CERTS/Comcast/README.md#ca-certificates) | 1 (3.45%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 1 (100.00%) |
| [GBSDTech](CERTS/GBSDTech/README.md#ca-certificates) | 1 (3.45%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 1 (100.00%) |
| [Martini Security](CERTS/Martini_Security/README.md#ca-certificates) | 4 (13.79%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 2 (50.00%) |
| [Metaswitch](CERTS/Metaswitch/README.md#ca-certificates) | 4 (13.79%) | 4 (100.00%) | 0 (0.00%) | 0 (0.00%) | 2 (50.00%) |
| [NetNumber](CERTS/NetNumber/README.md#ca-certificates) | 3 (10.34%) | 2 (66.67%) | 0 (0.00%) | 0 (0.00%) | 3 (100.00%) |
| [Neustar](CERTS/Neustar/README.md#ca-certificates) | 3 (10.34%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 3 (100.00%) |
| [Peeringhub](CERTS/Peeringhub/README.md#ca-certificates) | 2 (6.90%) | 2 (100.00%) | 0 (0.00%) | 0 (0.00%) | 2 (100.00%) |
| [Ribbon Communications](CERTS/Ribbon_Communications/README.md#ca-certificates) | 1 (3.45%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 1 (100.00%) |
| [SOMOS](CERTS/SOMOS/README.md#ca-certificates) | 1 (3.45%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Sansay](CERTS/Sansay/README.md#ca-certificates) | 2 (6.90%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 2 (100.00%) |
| [T-Mobile](CERTS/T-Mobile/README.md#ca-certificates) | 1 (3.45%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 1 (100.00%) |
| [Telonium](CERTS/Telonium/README.md#ca-certificates) | 4 (13.79%) | 2 (50.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [TransNexus](CERTS/TransNexus/README.md#ca-certificates) | 1 (3.45%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 1 (100.00%) |
| **Total** | 29 (100.00%) | 11 (37.93%) | 0 (0.00%) | 0 (0.00%) | 19 (65.52%) |

### Key

| Type | Description |
|------|-------------|
| Errors | Tests in which the specifications are unambiguous on what the expected behavior must be. |
| Warnings | Tests in which the specifications are ambiguous or are provide only a recommendation. |
| Notices | Tests in which industry best practices are not followed. |
| Not Effective | Tests that exist in the current specifications but were not in effect at the time of issuance. |


Generated: 02 Jun 25 00:08 UTC