# STIR/SHAKEN Certificate Repository Compliance

## TextMe Incorporated

Name: `https://textme-stirshaken.s3.us-west-2.amazonaws.com/textme_20250927.pem`\
Tested At: 01 Jun 25 22:30 UTC\
Time: 326ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 01 Jun 25 22:38 UTC