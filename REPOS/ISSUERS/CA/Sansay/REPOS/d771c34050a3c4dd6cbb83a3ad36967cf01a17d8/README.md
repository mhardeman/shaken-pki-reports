# STIR/SHAKEN Certificate Repository Compliance

## Sansay

Name: `https://cr.sansay.com/864J/429C7C70711E3820F0B8E1DEAE6FF3262264C69E.pem`\
Tested At: 01 Jun 25 22:56 UTC\
Time: 281ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 01 Jun 25 22:59 UTC