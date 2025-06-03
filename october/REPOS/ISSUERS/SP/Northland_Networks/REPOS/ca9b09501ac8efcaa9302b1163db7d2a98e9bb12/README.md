# STIR/SHAKEN Certificate Repository Compliance

## Northland Networks

Name: `https://cdn-cr.cgah.tnsi.com/certs/b612c440f3a242d373cf151cef48cb787d8346d7`\
Tested At: 03 Jun 25 01:30 UTC\
Time: 13ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 03 Jun 25 01:30 UTC