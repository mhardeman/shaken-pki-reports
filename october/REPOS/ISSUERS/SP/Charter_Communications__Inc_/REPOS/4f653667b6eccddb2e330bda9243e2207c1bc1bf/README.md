# STIR/SHAKEN Certificate Repository Compliance

## Charter Communications, Inc.

Name: `https://shaken.spectrum.com/a9214dea8d75b74eb4717f01ceecf0ad.cer`\
Tested At: 02 Jun 25 03:40 UTC\
Time: 320ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 02 Jun 25 03:45 UTC