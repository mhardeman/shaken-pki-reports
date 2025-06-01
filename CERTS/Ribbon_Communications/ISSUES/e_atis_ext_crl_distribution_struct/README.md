# STIR/SHAKEN CA Ecosystem Compliance

## Ribbon Communications

Name: e_atis_ext_crl_distribution_struct\
Source: ATIS1000080\
Citation: ATIS-1000080.v004 / 6.4.1 STI Certificate Requirements\
Effective Date: 16 Jan 22 00:00 UTC\
Description: STI intermediate and end-entity certificates shall contain a CRL Distribution Points extension containing a single DistributionPoint entry. The DistributionPoint entry shall contain a distributionPoint field identifying the HTTP URL reference to the file containing the SHAKEN CRL hosted by the STI-PA, and a cRLIssuer field that contains the DN of the issuer of the CRL.

### Leaf Certificates

| Status | Subject | Link | Details |
|--------|---------|------|---------|
| error | Eastex SHAKEN 2068 | [view](../../CERTS/2af7e084a64ee7e985d334a54b93169abe4d7ebbd6f1981a3c66e45edb7af5d8/README.md) | CRL Distribution Point shall contain a CRLIssuer field |

### CA Certificates

No error, warning, or notice level issues were found


Generated: 01 Jun 25 22:59 UTC