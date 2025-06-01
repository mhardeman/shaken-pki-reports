# STIR/SHAKEN Certificate Repository Compliance

## Third Base International Telecom LLC

Name: `https://ssc.getsipnav.com/certs/0a8c103b1a8ad924229f7602a8149b7708c8fa6c`\
Tested At: 01 Jun 25 22:55 UTC\
Time: 35ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header has 'max-age' directive but it's value is less than 24 hours |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 01 Jun 25 22:59 UTC