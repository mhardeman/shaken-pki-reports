# STIR/SHAKEN Certificate Repository Compliance

## Avid Communications

Name: `https://cdn-cr.cgah.tnsi.com/certs/0cd04dcda95032f0305055d449d60db49bfd1b0a`\
Tested At: 01 Jun 25 22:33 UTC\
Time: 19ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 01 Jun 25 22:38 UTC