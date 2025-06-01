# STIR/SHAKEN Certificate Repository Compliance

## Telesystem

Name: `https://cdn-cr.cgah.tnsi.com/certs/1119f8a66803e30896e315d1e9766b55ab10e7f9`\
Tested At: 01 Jun 25 22:31 UTC\
Time: 24ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 01 Jun 25 22:38 UTC