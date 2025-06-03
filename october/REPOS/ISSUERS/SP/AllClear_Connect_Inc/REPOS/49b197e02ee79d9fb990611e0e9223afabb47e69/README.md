# STIR/SHAKEN Certificate Repository Compliance

## AllClear Connect Inc

Name: `https://ssc.getsipnav.com/certs/b4ec00e21e2d97c0707f1c726d5358dd1ae3903b`\
Tested At: 03 Jun 25 02:10 UTC\
Time: 189ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header has 'max-age' directive but it's value is less than 24 hours |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 03 Jun 25 02:15 UTC