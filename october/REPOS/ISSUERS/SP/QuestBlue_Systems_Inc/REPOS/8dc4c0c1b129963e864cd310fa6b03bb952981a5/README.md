# STIR/SHAKEN Certificate Repository Compliance

## QuestBlue Systems Inc

Name: `https://customer.questblue.com/assets/questblue_shaken.cer`\
Tested At: 03 Jun 25 02:02 UTC\
Time: 145ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Pragma header contains 'no-cache' |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 03 Jun 25 02:15 UTC