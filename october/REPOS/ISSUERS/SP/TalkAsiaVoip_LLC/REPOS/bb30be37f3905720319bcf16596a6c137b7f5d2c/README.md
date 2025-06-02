# STIR/SHAKEN Certificate Repository Compliance

## TalkAsiaVoip LLC

Name: `https://www.talkasiavoip.com/198K.pem`\
Tested At: 02 Jun 25 18:56 UTC\
Time: 226ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 02 Jun 25 18:58 UTC