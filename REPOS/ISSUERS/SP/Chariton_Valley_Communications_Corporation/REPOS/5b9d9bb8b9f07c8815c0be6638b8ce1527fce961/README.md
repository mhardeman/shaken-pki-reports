# STIR/SHAKEN Certificate Repository Compliance

## Chariton Valley Communications Corporation

Name: `https://cdn-cr.cgah.tnsi.com/certs/5059f73c1bde1cdf7d280f005cc7a0ba008c1e59`\
Tested At: 01 Jun 25 21:42 UTC\
Time: 40ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 01 Jun 25 21:52 UTC