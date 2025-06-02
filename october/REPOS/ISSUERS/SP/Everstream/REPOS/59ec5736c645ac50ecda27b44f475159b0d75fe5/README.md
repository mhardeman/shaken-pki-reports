# STIR/SHAKEN Certificate Repository Compliance

## Everstream

Name: `https://cdn-cr.cgah.tnsi.com/certs/9a7b2a6d4386c07c3a93defdf06692adca9b47c8`\
Tested At: 02 Jun 25 02:37 UTC\
Time: 102ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 02 Jun 25 02:39 UTC