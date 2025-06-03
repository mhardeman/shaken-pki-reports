# STIR/SHAKEN Certificate Repository Compliance

## Coztel Carrier

Name: `https://ssc.getsipnav.com/certs/72bbf8fad95d5b9cc085ab8296f642ac091647b6`\
Tested At: 03 Jun 25 02:10 UTC\
Time: 190ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header has 'max-age' directive but it's value is less than 24 hours |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 03 Jun 25 02:15 UTC