# STIR/SHAKEN CA Ecosystem Compliance

[Approved Certificate Authorities](https://ecosystemcompliance.martinisecurity.com/#:~:text=Approved%20Certificate%20Authorities) in the STIR/SHAKEN ecosystem are required to meet technical requirements from [ATIS-1000080](https://access.atis.org/apps/group_public/document.php?document_id=62163) and policy requirements from the supporting CA ecosystem’s [Certificate Policy](https://authenticate.iconectiv.com/documents-authenticate).

This report is broken int two parts:
1. One generated using [Zlint](https://github.com/zmap/zlint) a tool commonly used to asses CA ecosystem compliance with such requirements. The tests used to generate this report are currently not part of the main [Zlint](https://github.com/martinisecurity/zlint) distribution but can be found here.
2. One generated with a custom script that eumerates the known STIR/SHAKEN certificates and asses each repository against the current rule set . The source for this test can be found here while the report itself can be found [here](REPOS/README.md).

## Summary

### Leaf Certificates

- 8637 certificates were included in the corpus being tested
- 159 certificates in the corpus were skipped because they are duplicates
- 0 certificates in the corpus were skipped because they are expired
- 18 certificates in the corpus were skipped because they are not currently trusted
- 8460 certificates being tested against the remaining rules
- 1.51 issues on average found in unexpired, trusted, and non-compliant certificates
- 53.10% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 3.07% of certificates are too old to be assessed against currently enforced expectations
- 63 days is the average remaining validity for the certificates in the corpus
- 63 days is the average initial validity for the certificates in the corpus
- 8260 certificates expire in the next 30 days
- 12.74 average number of unexpired certificates per OCN observed
- 678 unique OCNs observed in unexpired and valid certificate corpus

### CA Certificates

- 47 certificates were included in the corpus being tested
- 0 certificates in the corpus were skipped because they are duplicates
- 0 certificates in the corpus were skipped because they are expired
- 5 certificates in the corpus were skipped because they are not currently trusted
- 42 certificates being tested against the remaining rules
- 2.16 issues on average found in unexpired, trusted, and non-compliant certificates
- 45.24% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 64.29% of certificates are too old to be assessed against currently enforced expectations
- 5660 days is the average remaining validity for the certificates in the corpus
- 5590 days is the average initial validity for the certificates in the corpus
- 1 certificates expire in the next 30 days

## Certificate Repository URL

- 27.87% of certificate repository URLs contain one or more Error level issue
- 28.06% of certificates repository URLs contain one or more Warning level issue
- 0.00% of certificates repository URLs contain one or more Notice level issue

## Details

\* The percent of certificates per issuer is calculated against total certificates from all issuers.\
\*\* The percent of errors, warnings and notices is calculated against total observed certificates from the specified issuer.\
\*\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran. Certificates issued before these dates are not executed as the rules may not have been enforce at the time.

### Leaf Certificates

| Issuers | Certificates | Errors | Warnings | Notices | Not Effective |
|---------|--------------|--------|----------|---------|---------------|
| [GBSDTech](CERTS/GBSDTech/README.md#leaf-certificates) | 6 (0.07%) | 6 (100.00%) | 0 (0.00%) | 0 (0.00%) | 1 (16.67%) |
| [Martini Security](CERTS/Martini_Security/README.md#leaf-certificates) | 2480 (29.31%) | 138 (5.56%) | 0 (0.00%) | 0 (0.00%) | 52 (2.10%) |
| [Metaswitch](CERTS/Metaswitch/README.md#leaf-certificates) | 91 (1.08%) | 91 (100.00%) | 0 (0.00%) | 0 (0.00%) | 41 (45.05%) |
| [NetNumber](CERTS/NetNumber/README.md#leaf-certificates) | 63 (0.74%) | 63 (100.00%) | 0 (0.00%) | 0 (0.00%) | 11 (17.46%) |
| [Neustar](CERTS/Neustar/README.md#leaf-certificates) | 192 (2.27%) | 189 (98.44%) | 0 (0.00%) | 0 (0.00%) | 35 (18.23%) |
| [Peeringhub](CERTS/Peeringhub/README.md#leaf-certificates) | 72 (0.85%) | 16 (22.22%) | 0 (0.00%) | 0 (0.00%) | 2 (2.78%) |
| [Ribbon Communications](CERTS/Ribbon_Communications/README.md#leaf-certificates) | 22 (0.26%) | 22 (100.00%) | 0 (0.00%) | 0 (0.00%) | 6 (27.27%) |
| [Sansay](CERTS/Sansay/README.md#leaf-certificates) | 1922 (22.72%) | 1922 (100.00%) | 0 (0.00%) | 0 (0.00%) | 99 (5.15%) |
| [T-Mobile](CERTS/T-Mobile/README.md#leaf-certificates) | 4 (0.05%) | 4 (100.00%) | 0 (0.00%) | 0 (0.00%) | 2 (50.00%) |
| [Telonium](CERTS/Telonium/README.md#leaf-certificates) | 26 (0.31%) | 4 (15.38%) | 0 (0.00%) | 0 (0.00%) | 0 (0.00%) |
| [TransNexus](CERTS/TransNexus/README.md#leaf-certificates) | 3582 (42.34%) | 2037 (56.87%) | 0 (0.00%) | 0 (0.00%) | 11 (0.31%) |
| **Total** | 8460 (100.00%) | 4492 (53.10%) | 0 (0.00%) | 0 (0.00%) | 260 (3.07%) |

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


Generated: 02 Jun 25 18:58 UTC