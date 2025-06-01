# STIR/SHAKEN Certificate Repository Compliance

## 6x6 Termination

Name: `https://ssc.getsipnav.com/certs/f9c28e4d2a68ced32a566392621883c8d8923c97`\
Tested At: 01 Jun 25 22:34 UTC\
Time: 49ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header has 'max-age' directive but it's value is less than 24 hours |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 01 Jun 25 22:38 UTC