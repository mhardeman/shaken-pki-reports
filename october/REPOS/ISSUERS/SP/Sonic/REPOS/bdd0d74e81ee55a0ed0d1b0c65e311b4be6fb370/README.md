# STIR/SHAKEN Certificate Repository Compliance

## Sonic

Name: `https://crs.qcall.sonic.net/certs/Sonic2024certchain.crt`\
Tested At: 03 Jun 25 02:02 UTC\
Time: 311ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 03 Jun 25 02:15 UTC