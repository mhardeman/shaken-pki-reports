# STIR/SHAKEN Certificate Repository Compliance

## Blackfoot Communications

Name: `https://cdn-cr.cgah.tnsi.com/certs/bc1696dd44b2d632822353b64e87d310d5fd7bf4`\
Tested At: 01 Jun 25 22:34 UTC\
Time: 10ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 01 Jun 25 22:39 UTC