# STIR/SHAKEN Certificate Repository Compliance

## Primevox Communications, LLC

Name: `https://pvx1.s3.us-east-2.amazonaws.com/stirshaken/public_certificate.cer`\
Tested At: 01 Jun 25 22:59 UTC\
Time: 201ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 01 Jun 25 22:59 UTC