# STIR/SHAKEN Certificate Repository Compliance

## Swift Telco LLC

Name: `https://cdn.cnxcdn.com/shaken/c015310d91.crt`\
Tested At: 02 Jun 25 02:37 UTC\
Time: 291ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header has 'max-age' directive but it's value is less than 24 hours |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 02 Jun 25 02:39 UTC