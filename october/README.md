# STIR/SHAKEN CA Ecosystem Compliance

[Approved Certificate Authorities](https://ecosystemcompliance.martinisecurity.com/#:~:text=Approved%20Certificate%20Authorities) in the STIR/SHAKEN ecosystem are required to meet technical requirements from [ATIS-1000080](https://access.atis.org/apps/group_public/document.php?document_id=62163) and policy requirements from the supporting CA ecosystem’s [Certificate Policy](https://authenticate.iconectiv.com/documents-authenticate).

This report is broken int two parts:
1. One generated using [Zlint](https://github.com/zmap/zlint) a tool commonly used to asses CA ecosystem compliance with such requirements. The tests used to generate this report are currently not part of the main [Zlint](https://github.com/martinisecurity/zlint) distribution but can be found here.
2. One generated with a custom script that eumerates the known STIR/SHAKEN certificates and asses each repository against the current rule set . The source for this test can be found here while the report itself can be found [here](REPOS/README.md).

## Summary

### Leaf Certificates

- 235 potential certificates were requested for retrieval
- 201 candidate certificates were included in the corpus being tested
- 5 certificates in the candidate corpus were skipped because they are duplicates
- 13 certificates in the candidate corpus were skipped because they are outside-target-validity-period
- 2 certificates in the candidate corpus were skipped because they did not chain to trust anchors
- 181 certificates being tested against the remaining rules
- 1.72 issues on average found in unexpired, trusted, and non-compliant certificates
- 72.38% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 22.10% of certificates are too old to be assessed against currently enforced expectations
- 558 days is the average remaining validity for the certificates in the corpus
- 563 days is the average initial validity for the certificates in the corpus
- 123 certificates expire in the next 30 days
- 2.26 average number of unexpired certificates per OCN observed
- 89 unique OCNs observed in unexpired and valid certificate corpus

### CA Certificates

- 32 potential certificates were requested for retrieval
- 32 candidate certificates were included in the corpus being tested
- 0 certificates in the candidate corpus were skipped because they are duplicates
- 0 certificates in the candidate corpus were skipped because they are outside-target-validity-period
- 1 certificates in the candidate corpus were skipped because they did not chain to trust anchors
- 31 certificates being tested against the remaining rules
- 2.18 issues on average found in unexpired, trusted, and non-compliant certificates
- 35.48% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 64.52% of certificates are too old to be assessed against currently enforced expectations
- 6077 days is the average remaining validity for the certificates in the corpus
- 5995 days is the average initial validity for the certificates in the corpus
- 0 certificates expire in the next 30 days

## Certificate Repository URL

- 58.56% of certificate repository URLs contain one or more Error level issue
- 59.12% of certificates repository URLs contain one or more Warning level issue
- 0.00% of certificates repository URLs contain one or more Notice level issue

## Details

\* The percent of certificates per issuer is calculated against total certificates from all issuers.\
\*\* The percent of errors, warnings and notices is calculated against total observed certificates from the specified issuer.\
\*\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran. Certificates issued before these dates are not executed as the rules may not have been enforce at the time.

### Leaf Certificates

| Issuers | Certificates | Errors | Warnings | Notices | Not Effective |
|---------|--------------|--------|----------|---------|---------------|
| [Martini Security](CERTS/Martini_Security/README.md#leaf-certificates) | 2 (1.10%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Metaswitch](CERTS/Metaswitch/README.md#leaf-certificates) | 85 (46.96%) | 85 (100.00%) | 0 (0.00%) | 0 (0.00%) | 40 (47.06%) |
| [NetNumber](CERTS/NetNumber/README.md#leaf-certificates) | 1 (0.55%) | 1 (100.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Neustar](CERTS/Neustar/README.md#leaf-certificates) | 9 (4.97%) | 9 (100.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Peeringhub](CERTS/Peeringhub/README.md#leaf-certificates) | 4 (2.21%) | 2 (50.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Sansay](CERTS/Sansay/README.md#leaf-certificates) | 5 (2.76%) | 5 (100.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Telonium](CERTS/Telonium/README.md#leaf-certificates) | 2 (1.10%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [TransNexus](CERTS/TransNexus/README.md#leaf-certificates) | 73 (40.33%) | 29 (39.73%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| **Total** | 181 (100.00%) | 131 (72.38%) | 0 (0.00%) | 0 (0.00%) | 40 (22.10%) |

### CA Certificates

| Issuers | Certificates | Errors | Warnings | Notices | Not Effective |
|---------|--------------|--------|----------|---------|---------------|
| [CTIA](CERTS/CTIA/README.md#ca-certificates) | 1 (3.23%) | 1 (100.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Comcast](CERTS/Comcast/README.md#ca-certificates) | 1 (3.23%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 1 (100.00%) |
| [GBSDTech](CERTS/GBSDTech/README.md#ca-certificates) | 1 (3.23%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 1 (100.00%) |
| [Martini Security](CERTS/Martini_Security/README.md#ca-certificates) | 4 (12.90%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 2 (50.00%) |
| [Metaswitch](CERTS/Metaswitch/README.md#ca-certificates) | 4 (12.90%) | 4 (100.00%) | 0 (0.00%) | 0 (0.00%) | 2 (50.00%) |
| [NetNumber](CERTS/NetNumber/README.md#ca-certificates) | 3 (9.68%) | 2 (66.67%) | 0 (0.00%) | 0 (0.00%) | 3 (100.00%) |
| [Neustar](CERTS/Neustar/README.md#ca-certificates) | 3 (9.68%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 3 (100.00%) |
| [Peeringhub](CERTS/Peeringhub/README.md#ca-certificates) | 2 (6.45%) | 2 (100.00%) | 0 (0.00%) | 0 (0.00%) | 2 (100.00%) |
| [Ribbon Communications](CERTS/Ribbon_Communications/README.md#ca-certificates) | 1 (3.23%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 1 (100.00%) |
| [SOMOS](CERTS/SOMOS/README.md#ca-certificates) | 1 (3.23%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [Sansay](CERTS/Sansay/README.md#ca-certificates) | 2 (6.45%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 2 (100.00%) |
| [T-Mobile](CERTS/T-Mobile/README.md#ca-certificates) | 1 (3.23%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 1 (100.00%) |
| [Telonium](CERTS/Telonium/README.md#ca-certificates) | 4 (12.90%) | 2 (50.00%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [TransNexus](CERTS/TransNexus/README.md#ca-certificates) | 3 (9.68%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) | 2 (66.67%) |
| **Total** | 31 (100.00%) | 11 (35.48%) | 0 (0.00%) | 0 (0.00%) | 20 (64.52%) |

### Key

| Type | Description |
|------|-------------|
| Errors | Tests in which the specifications are unambiguous on what the expected behavior must be. |
| Warnings | Tests in which the specifications are ambiguous or are provide only a recommendation. |
| Notices | Tests in which industry best practices are not followed. |
| Not Effective | Tests that exist in the current specifications but were not in effect at the time of issuance. |


Generated: 03 Jun 25 01:18 UTC