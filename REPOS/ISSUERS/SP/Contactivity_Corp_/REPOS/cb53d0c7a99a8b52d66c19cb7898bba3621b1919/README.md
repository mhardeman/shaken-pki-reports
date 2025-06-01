# STIR/SHAKEN Certificate Repository Compliance

## Contactivity Corp.

Name: `https://ssc.getsipnav.com/certs/2b0bc92ebf4882b7c359a5c9b1894e9170775f99`\
Tested At: 01 Jun 25 22:28 UTC\
Time: 45ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header has 'max-age' directive but it's value is less than 24 hours |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 01 Jun 25 22:39 UTC