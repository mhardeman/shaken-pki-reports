# STIR/SHAKEN CA Ecosystem Compliance

[Approved Certificate Authorities](https://ecosystemcompliance.martinisecurity.com/#:~:text=Approved%20Certificate%20Authorities) in the STIR/SHAKEN ecosystem are required to meet technical requirements from [ATIS-1000080](https://access.atis.org/apps/group_public/document.php?document_id=62163) and policy requirements from the supporting CA ecosystem’s [Certificate Policy](https://authenticate.iconectiv.com/documents-authenticate).

This report is broken int two parts:
1. One generated using [Zlint](https://github.com/zmap/zlint) a tool commonly used to asses CA ecosystem compliance with such requirements. The tests used to generate this report are currently not part of the main [Zlint](https://github.com/martinisecurity/zlint) distribution but can be found here.
2. One generated with a custom script that eumerates the known STIR/SHAKEN certificates and asses each repository against the current rule set . The source for this test can be found here while the report itself can be found [here](REPOS/README.md).

## Summary

### Leaf Certificates

- 3228 certificates were included in the corpus being tested
- 143 certificates in the corpus were skipped because they are duplicates
- 2396 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 689 certificates being tested against the remaining rules
- 1.62 issues on average found in unexpired, trusted, and non-compliant certificates
- 59.94% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.44% of certificates are too old to be assessed against currently enforced expectations
- 256 days is the average remaining validity for the certificates in the corpus
- 256 days is the average initial validity for the certificates in the corpus
- 286 certificates expire in the next 30 days
- 6.22 average number of unexpired certificates per OCN observed
- 519 unique OCNs observed in unexpired and valid certificate corpus

### CA Certificates

- 37 certificates were included in the corpus being tested
- 0 certificates in the corpus were skipped because they are duplicates
- 0 certificates in the corpus were skipped because they are expired
- 0 certificates in the corpus were skipped because they are not currently trusted
- 37 certificates being tested against the remaining rules
- 2.31 issues on average found in unexpired, trusted, and non-compliant certificates
- 43.24% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 56.76% of certificates are too old to be assessed against currently enforced expectations
- 5934 days is the average remaining validity for the certificates in the corpus
- 5862 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days

## Certificate Repository URL

- 65.02% of certificate repository URLs contain one or more Error level issue
- 67.49% of certificates repository URLs contain one or more Warning level issue
- 0.00% of certificates repository URLs contain one or more Notice level issue

## Details

\* The percent of certificates per issuer is calculated against total certificates from all issuers.\
\*\* The percent of errors, warnings and notices is calculated against total observed certificates from the specified issuer.\
\*\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran. Certificates issued before these dates are not executed as the rules may not have been enforce at the time.

### Leaf Certificates

| Issuers | Certificates | Errors | Warnings | Notices | Not Effective |
|---------|--------------|--------|----------|---------|---------------|
| [CTIA](CERTS/CTIA/README.md#leaf-certificates) | 1 (0.15%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Comcast](CERTS/Comcast/README.md#leaf-certificates) | 28 (4.06%) | 28 (100.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [GBSDTech](CERTS/GBSDTech/README.md#leaf-certificates) | 3 (0.44%) | 3 (100.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Martini Security](CERTS/Martini_Security/README.md#leaf-certificates) | 129 (18.72%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Metaswitch](CERTS/Metaswitch/README.md#leaf-certificates) | 48 (6.97%) | 48 (100.00%) | 0 (0.00%) | 0 (0.00%) | 3 (6.25%) |
| [NetNumber](CERTS/NetNumber/README.md#leaf-certificates) | 5 (0.73%) | 5 (100.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Neustar](CERTS/Neustar/README.md#leaf-certificates) | 121 (17.56%) | 121 (100.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Peeringhub](CERTS/Peeringhub/README.md#leaf-certificates) | 31 (4.50%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Ribbon Communications](CERTS/Ribbon_Communications/README.md#leaf-certificates) | 1 (0.15%) | 1 (100.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Sansay](CERTS/Sansay/README.md#leaf-certificates) | 204 (29.61%) | 204 (100.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [T-Mobile](CERTS/T-Mobile/README.md#leaf-certificates) | 1 (0.15%) | 1 (100.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Telonium](CERTS/Telonium/README.md#leaf-certificates) | 49 (7.11%) | 2 (4.08%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [TransNexus](CERTS/TransNexus/README.md#leaf-certificates) | 68 (9.87%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| **Total** | 689 (100.00%) | 413 (59.94%) | 0 (0.00%) | 0 (0.00%) | 3 (0.44%) |

### CA Certificates

| Issuers | Certificates | Errors | Warnings | Notices | Not Effective |
|---------|--------------|--------|----------|---------|---------------|
| [CTIA](CERTS/CTIA/README.md#ca-certificates) | 2 (5.41%) | 1 (50.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Comcast](CERTS/Comcast/README.md#ca-certificates) | 2 (5.41%) | 1 (50.00%) | 0 (0.00%) | 0 (0.00%) | 1 (50.00%) |
| [GBSDTech](CERTS/GBSDTech/README.md#ca-certificates) | 3 (8.11%) | 2 (66.67%) | 0 (0.00%) | 0 (0.00%) | 2 (66.67%) |
| [Martini Security](CERTS/Martini_Security/README.md#ca-certificates) | 4 (10.81%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 2 (50.00%) |
| [Metaswitch](CERTS/Metaswitch/README.md#ca-certificates) | 3 (8.11%) | 3 (100.00%) | 0 (0.00%) | 0 (0.00%) | 1 (33.33%) |
| [NetNumber](CERTS/NetNumber/README.md#ca-certificates) | 3 (8.11%) | 2 (66.67%) | 0 (0.00%) | 0 (0.00%) | 3 (100.00%) |
| [Neustar](CERTS/Neustar/README.md#ca-certificates) | 3 (8.11%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 3 (100.00%) |
| [Peeringhub](CERTS/Peeringhub/README.md#ca-certificates) | 2 (5.41%) | 2 (100.00%) | 0 (0.00%) | 0 (0.00%) | 2 (100.00%) |
| [Ribbon Communications](CERTS/Ribbon_Communications/README.md#ca-certificates) | 2 (5.41%) | 1 (50.00%) | 0 (0.00%) | 0 (0.00%) | 1 (50.00%) |
| [SOMOS](CERTS/SOMOS/README.md#ca-certificates) | 1 (2.70%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Sansay](CERTS/Sansay/README.md#ca-certificates) | 2 (5.41%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 2 (100.00%) |
| [T-Mobile](CERTS/T-Mobile/README.md#ca-certificates) | 2 (5.41%) | 1 (50.00%) | 0 (0.00%) | 0 (0.00%) | 2 (100.00%) |
| [Telonium](CERTS/Telonium/README.md#ca-certificates) | 5 (13.51%) | 3 (60.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [TransNexus](CERTS/TransNexus/README.md#ca-certificates) | 3 (8.11%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 2 (66.67%) |
| **Total** | 37 (100.00%) | 16 (43.24%) | 0 (0.00%) | 0 (0.00%) | 21 (56.76%) |

### Key

| Type | Description |
|------|-------------|
| Errors | Tests in which the specifications are unambiguous on what the expected behavior must be. |
| Warnings | Tests in which the specifications are ambiguous or are provide only a recommendation. |
| Notices | Tests in which industry best practices are not followed. |
| Not Effective | Tests that exist in the current specifications but were not in effect at the time of issuance. |


Generated: 01 Jun 25 22:39 UTC