# STIR/SHAKEN Certificate Repository Compliance

## RCN

Name: `https://cdn-cr.cgah.tnsi.com/certs/91cb0b66fe231e4eb06ddad650a80f4f09cdfdc4`\
Tested At: 02 Jun 25 00:17 UTC\
Time: 26ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 02 Jun 25 01:01 UTC