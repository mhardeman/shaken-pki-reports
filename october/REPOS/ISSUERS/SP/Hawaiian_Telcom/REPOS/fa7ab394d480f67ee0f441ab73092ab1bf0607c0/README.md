# STIR/SHAKEN Certificate Repository Compliance

## Hawaiian Telcom

Name: `https://cdn-cr.cgah.tnsi.com/certs/d9fd0052c420d93208011ac9911e79e422d0edd4`\
Tested At: 02 Jun 25 03:09 UTC\
Time: 22ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 02 Jun 25 03:45 UTC