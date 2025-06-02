# STIR/SHAKEN Certificate Repository Compliance

## Appalachian Wireless

Name: `https://cdn-cr.cgah.tnsi.com/certs/d180ac25a9b0d046adeaa25f62424c7be186c2ab`\
Tested At: 02 Jun 25 00:08 UTC\
Time: 23ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 02 Jun 25 00:08 UTC