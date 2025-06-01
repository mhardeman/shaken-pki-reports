# STIR/SHAKEN Certificate Repository Compliance

## Kaplan Telephone

Name: `https://cdn-cr.cgah.tnsi.com/certs/e8a30914a93822abe2262f6ffedfadd7837edc3e`\
Tested At: 01 Jun 25 21:45 UTC\
Time: 54ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 01 Jun 25 21:52 UTC