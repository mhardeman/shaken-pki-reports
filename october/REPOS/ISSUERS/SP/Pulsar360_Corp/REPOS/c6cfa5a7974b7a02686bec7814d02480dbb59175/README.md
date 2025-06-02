# STIR/SHAKEN Certificate Repository Compliance

## Pulsar360 Corp

Name: `https://ecms.securetransit.net/certs/06517b2e2010ec1a2b429664047353b6.cer`\
Tested At: 02 Jun 25 00:47 UTC\
Time: 435ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 02 Jun 25 01:01 UTC