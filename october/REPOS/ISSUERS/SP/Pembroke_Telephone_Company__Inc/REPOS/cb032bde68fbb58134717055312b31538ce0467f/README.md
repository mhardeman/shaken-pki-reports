# STIR/SHAKEN Certificate Repository Compliance

## Pembroke Telephone Company, Inc

Name: `https://cdn-cr.cgah.tnsi.com/certs/54f1b46e13a9f05d1b3f49b6f71314b0b97cc086`\
Tested At: 03 Jun 25 01:30 UTC\
Time: 22ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 03 Jun 25 01:30 UTC