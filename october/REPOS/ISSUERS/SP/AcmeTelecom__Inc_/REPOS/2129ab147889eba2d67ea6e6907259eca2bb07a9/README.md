# STIR/SHAKEN Certificate Repository Compliance

## AcmeTelecom, Inc.

Name: `https://65.108.80.93/cert.pem`\
Tested At: 03 Jun 25 00:35 UTC\
Time: 536ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [e_tls_transport](../../ISSUES/e_tls_transport/README.md) | error | System | Get "https://65.108.80.93/cert.pem": x509: certificate has expired or is not yet valid: current time 2025-06-03T00:35:57Z is after 2024-09-12T19:30:51Z |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 03 Jun 25 00:36 UTC