# STIR/SHAKEN Certificate Repository Compliance

## Neustar

Name: `https://cr.ccid.neustar.biz/ccid/authn/v2/certs/11541.10421.pem`\
Tested At: 01 Jun 25 22:53 UTC\
Time: 334ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 01 Jun 25 22:59 UTC