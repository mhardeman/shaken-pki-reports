# STIR/SHAKEN Certificate Repository Compliance

## Duo Broadband 

Name: `https://cdn-cr.cgah.tnsi.com/certs/e6c8f8013706c0cbf0a78beb80d1f21374f43b1d`\
Tested At: 01 Jun 25 21:47 UTC\
Time: 44ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 01 Jun 25 21:52 UTC