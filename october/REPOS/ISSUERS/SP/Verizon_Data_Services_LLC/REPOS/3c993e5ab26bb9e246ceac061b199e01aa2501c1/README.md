# STIR/SHAKEN Certificate Repository Compliance

## Verizon Data Services LLC

Name: `https://sti.verizon.com/vzwcert/vzshaken-02-2024.crt`\
Tested At: 03 Jun 25 02:12 UTC\
Time: 269ms

### Issues

| Code | Type | Source | Details |
|------|------|--------|---------|
| [e_atis_cache_header](../../ISSUES/e_atis_cache_header/README.md) | error | ATIS-1000074 | The STI-VS shall implement the cache behavior. The Cache-Control header is missed |
| [w_atis_content_type](../../ISSUES/w_atis_content_type/README.md) | warn | ATIS-1000080 | HTTP response should contain Content-Type header and it's value should be application/pem-certificate-chain |

Generated: 03 Jun 25 02:15 UTC