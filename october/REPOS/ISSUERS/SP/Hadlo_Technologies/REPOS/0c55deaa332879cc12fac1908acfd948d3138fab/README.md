# STIR/SHAKEN Certificate Repository Compliance

## Hadlo Technologies

Name: `https://www.hadlotechnologies.com/ss_certs/hadlo_ssi_public_20231113.crt`\
Tested At: 02 Jun 25 03:43 UTC\
Time: 224ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [e_tls_transport](../../ISSUES/e_tls_transport/README.md) | error | System | Get "https://www.hadlotechnologies.com/ss_certs/hadlo_ssi_public_20231113.crt": x509: certificate has expired or is not yet valid: current time 2025-06-02T03:43:56Z is after 2025-03-15T23:59:59Z |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 02 Jun 25 03:45 UTC