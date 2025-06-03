# STIR/SHAKEN CA Ecosystem Compliance

## Sansay

Name: e_atis_ext_crl_distribution_struct\
Source: ATIS1000080\
Citation: ATIS-1000080.v004 / 6.4.1 STI Certificate Requirements\
Effective Date: 16 Jan 22 00:00 UTC\
Description: STI intermediate and end-entity certificates shall contain a CRL Distribution Points extension containing a single DistributionPoint entry. The DistributionPoint entry shall contain a distributionPoint field identifying the HTTP URL reference to the file containing the SHAKEN CRL hosted by the STI-PA, and a cRLIssuer field that contains the DN of the issuer of the CRL.

### Leaf Certificates

| Status | Subject | Link | Details |
|--------|---------|------|---------|
| error | SHAKEN 688K Call Hub Inc. | [view](../../CERTS/c9514ae8afe29c81cba005d0e97ddd87c0588caca1e39a20368d4f872619984d/README.md) | CRL Distribution Point shall contain a CRLIssuer field |
| error | SHAKEN 688K Call Hub Inc. | [view](../../CERTS/d8fe53673498502aa06d1deb531144cdeac93dba56e9c7094fef9fe192b5b14c/README.md) | CRL Distribution Point shall contain a CRLIssuer field |

### CA Certificates

No error, warning, or notice level issues were found


Generated: 03 Jun 25 01:18 UTC