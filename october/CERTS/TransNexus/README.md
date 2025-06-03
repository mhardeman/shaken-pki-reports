# STIR/SHAKEN CA Ecosystem Compliance

## TransNexus

### Summary

\* The percent of errors, warnings and notices is calculated against total observed unexpired and trusted certificates from the specified issuer.\
\*\* Tests use the ATIS-1000080 and Certificate Policy versions release dates to determine if tests are ran.

#### Leaf Certificates

- 84 potential certificate URLs were requested for retrieval
- 84 candidate certificates were parsed from the potential certificate URLs
- 0 certificates in the candidate corpus were excluded because they are duplicates
- 11 certificates in the candidate corpus were excluded because they are outside-target-validity-period
- 0 certificates in the candidate corpus were excluded because they did not chain to trust anchors
- 73 valid certificates being tested against the remaining rules
- 1.00 issues on average found in valid but non-compliant certificates
- 39.73% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 0.00% of certificates are too old to be assessed against currently enforced expectations
- 3 days is the average remaining validity for the valid certificates
- 7 days is the average initial validity for the valid certificates
- 12.17 average number of unexpired certificates per OCN observed
- 6 unique OCNs observed in unexpired and valid certificate corpus

| Instances | Test | Source |
|-----------|------|--------|
| 29 | [e_us_cp_subject_sn_shall](ISSUES/e_us_cp_subject_sn_shall/README.md) | US_SHAKEN_CP |

#### CA Certificates

- 3 potential certificate URLs were requested for retrieval
- 3 candidate certificates were parsed from the potential certificate URLs
- 0 certificates in the candidate corpus were excluded because they are duplicates
- 0 certificates in the candidate corpus were excluded because they are outside-target-validity-period
- 0 certificates in the candidate corpus were excluded because they did not chain to trust anchors
- 3 valid certificates being tested against the remaining rules
- 0.00 issues on average found in valid but non-compliant certificates
- 0.00% of certificates contain one or more Error level issue
- 0.00% of certificates contain one or more Warning level issue
- 0.00% of certificates contain one or more Notice level issue
- 66.67% of certificates are too old to be assessed against currently enforced expectations
- 5240 days is the average remaining validity for the valid certificates
- 4870 days is the average initial validity for the valid certificates

No error, warning, or notice level issues were found

### Details

#### Leaf Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 30&#160;Sep&#160;23&#160;15:05&#160;UTC | SHAKEN 012K | 07&#160;Oct&#160;23&#160;15:05&#160;UTC | true | [view](CERTS/28fed147af492ab17ab048361ef8d2b6bb3dc8fe1cfe371ac1bcd8ef0407b14b/README.md) |
| 03&#160;Oct&#160;23&#160;15:05&#160;UTC | SHAKEN 012K | 10&#160;Oct&#160;23&#160;15:05&#160;UTC | true | [view](CERTS/328b062988fade949b3b9c5657905823778587761fb0ae1b60ab0525d761990d/README.md) |
| 06&#160;Oct&#160;23&#160;15:05&#160;UTC | SHAKEN 012K | 13&#160;Oct&#160;23&#160;15:05&#160;UTC | true | [view](CERTS/34c007390f0b63f6690257f26459a89abfb6a3a2eae35b0e232c770ca453b6ad/README.md) |
| 07&#160;Oct&#160;23&#160;14:40&#160;UTC | SHAKEN 208K | 14&#160;Oct&#160;23&#160;14:40&#160;UTC | true | [view](CERTS/20af2dd9bb4299a76d03c840e04795d0afc14205de2b3d119619a0e3d75ea298/README.md) |
| 09&#160;Oct&#160;23&#160;15:05&#160;UTC | SHAKEN 012K | 16&#160;Oct&#160;23&#160;15:05&#160;UTC | true | [view](CERTS/cda8fb9759e84d46c7450209fd910360d7e7d735618d3d4fc9a014d37677ec41/README.md) |
| 10&#160;Oct&#160;23&#160;14:40&#160;UTC | SHAKEN 208K | 17&#160;Oct&#160;23&#160;14:40&#160;UTC | true | [view](CERTS/e4b622edca6abe10a4e39433e24fe60ca5421195f0f6e56e8f8bbf306bf62f91/README.md) |
| 13&#160;Oct&#160;23&#160;14:40&#160;UTC | SHAKEN 208K | 20&#160;Oct&#160;23&#160;14:40&#160;UTC | true | [view](CERTS/ac66251f8913cad0adec9a85190fde5338c1cc25bc0defe06ca5b5547ad429eb/README.md) |
| 16&#160;Oct&#160;23&#160;14:40&#160;UTC | SHAKEN 208K | 23&#160;Oct&#160;23&#160;14:40&#160;UTC | true | [view](CERTS/e3f0966d5ab445dd47dc99c49026afd2e7cf5a598f92e68d5d3c874d094a58db/README.md) |
| 19&#160;Oct&#160;23&#160;14:41&#160;UTC | SHAKEN 208K | 26&#160;Oct&#160;23&#160;14:41&#160;UTC | true | [view](CERTS/931b2483816efd98dc65c86b9bb5367ca68f1ea89bc95bbdc152d4da5a8dc6cb/README.md) |
| 22&#160;Oct&#160;23&#160;14:42&#160;UTC | SHAKEN 208K | 29&#160;Oct&#160;23&#160;14:41&#160;UTC | true | [view](CERTS/b50c7d4d79541ff8760909d79ad2a8618e4e6f34ee1ac2b2465fab4aa0f9cc6d/README.md) |
| 22&#160;Oct&#160;23&#160;15:32&#160;UTC | SHAKEN 155F | 29&#160;Oct&#160;23&#160;15:32&#160;UTC | true | [view](CERTS/a362f777bdc5f47480b7ea351cfbd7b360695980f22ecd83c0f12d08690fd192/README.md) |
| 24&#160;Oct&#160;23&#160;15:07&#160;UTC | SHAKEN 012K | 31&#160;Oct&#160;23&#160;15:07&#160;UTC | true | [view](CERTS/3725f6cc80e6a3b9fa88161082c5c2462a46c30b636e153c550f95cf5d20f0d4/README.md) |
| 25&#160;Oct&#160;23&#160;14:42&#160;UTC | SHAKEN 208K | 01&#160;Nov&#160;23&#160;14:42&#160;UTC | true | [view](CERTS/dbd5bdde7ae90980feaf6b2c931b92fc23d4a8dd4f27288cf3ee43a18c795b99/README.md) |
| 30&#160;Oct&#160;23&#160;15:08&#160;UTC | SHAKEN 012K | 06&#160;Nov&#160;23&#160;15:08&#160;UTC | true | [view](CERTS/afe69bcfc0bc1692d21ae7cc4b2c899ba7c1c8ffee71f856db6441e75f0db86f/README.md) |
| 02&#160;Nov&#160;23&#160;15:08&#160;UTC | SHAKEN 012K | 09&#160;Nov&#160;23&#160;15:08&#160;UTC | true | [view](CERTS/8d5a29bafce8ffd4eec624dda0ef4d4c9e56102652a6c96e40b1a6ccd0198908/README.md) |
| 05&#160;Nov&#160;23&#160;15:08&#160;UTC | SHAKEN 012K | 12&#160;Nov&#160;23&#160;15:08&#160;UTC | true | [view](CERTS/766141526ceebda4e609f567ce83b8c58213df4d1dcaee052318718168d4becf/README.md) |
| 08&#160;Nov&#160;23&#160;15:08&#160;UTC | SHAKEN 012K | 15&#160;Nov&#160;23&#160;15:08&#160;UTC | true | [view](CERTS/8e27581cdb74f0001a8a3d49a0ab3dae43ab2975484149f86312e594bc950ff4/README.md) |
| 14&#160;Nov&#160;23&#160;15:09&#160;UTC | SHAKEN 012K | 21&#160;Nov&#160;23&#160;15:09&#160;UTC | true | [view](CERTS/3a6cd1a300433dae960d4036383817f141d79ab20fb436dd5e48e0793886af95/README.md) |
| 12&#160;Dec&#160;23&#160;14:45&#160;UTC | SHAKEN 208K | 19&#160;Dec&#160;23&#160;14:45&#160;UTC | true | [view](CERTS/5f99aec472642352aa6aef51f948c43a7d97a6e223133e09e223b52668e6b753/README.md) |
| 14&#160;Dec&#160;23&#160;15:11&#160;UTC | SHAKEN 012K | 21&#160;Dec&#160;23&#160;15:11&#160;UTC | true | [view](CERTS/c012454957a53aafe4317ce2f803bd40f39221b614b8b5e6e78d9acca01a3dd0/README.md) |
| 29&#160;Dec&#160;23&#160;15:12&#160;UTC | SHAKEN 012K | 05&#160;Jan&#160;24&#160;15:12&#160;UTC | true | [view](CERTS/9076f5e495a317f61f815ee27946548b89fe171a466cdb0e00fb3760acefff8e/README.md) |
| 08&#160;Jan&#160;24&#160;14:47&#160;UTC | SHAKEN 208K | 15&#160;Jan&#160;24&#160;14:47&#160;UTC | true | [view](CERTS/827c19bd766a9c72a9307216b2c1ffb14762c0992a1ae5124fa0000bf0ab46b4/README.md) |
| 11&#160;Jan&#160;24&#160;14:48&#160;UTC | SHAKEN 208K | 18&#160;Jan&#160;24&#160;14:48&#160;UTC | true | [view](CERTS/759213c3e4f167b6ff0f19afe7cfb9040d20abad3cb4edf6bfda0c6b05f9affa/README.md) |
| 13&#160;Jan&#160;24&#160;15:13&#160;UTC | SHAKEN 012K | 20&#160;Jan&#160;24&#160;15:13&#160;UTC | true | [view](CERTS/73deb88ba25759bdcd068c628c5efd403a0a5b81bc7ad6310da8291603c23e7d/README.md) |
| 14&#160;Jan&#160;24&#160;14:48&#160;UTC | SHAKEN 208K | 21&#160;Jan&#160;24&#160;14:48&#160;UTC | true | [view](CERTS/710330723abb0cf6b8100f670cbb5295ae72a4927f3400f0dc3ce43ad7f9a587/README.md) |
| 17&#160;Jan&#160;24&#160;14:49&#160;UTC | SHAKEN 208K | 24&#160;Jan&#160;24&#160;14:49&#160;UTC | true | [view](CERTS/311d51bb879e8ef6f055491b9cc32ae89f2cef26017c08c444ba1a2752f67aee/README.md) |
| 20&#160;Jan&#160;24&#160;14:49&#160;UTC | SHAKEN 208K | 27&#160;Jan&#160;24&#160;14:49&#160;UTC | true | [view](CERTS/dd120e7f840d7afcaeb3e4dfac7d516e37d5e402d8c6f2b2a5b238ecbb51deee/README.md) |
| 23&#160;Jan&#160;24&#160;14:49&#160;UTC | SHAKEN 208K | 30&#160;Jan&#160;24&#160;14:49&#160;UTC | true | [view](CERTS/bf564871da4bc52682e3b9ac6ee97a4ca88b38be1667a78ff253e4259b4e0bc8/README.md) |
| 31&#160;Jan&#160;24&#160;15:15&#160;UTC | SHAKEN 012K | 07&#160;Feb&#160;24&#160;15:15&#160;UTC | true | [view](CERTS/ceed20508531333fa30328d1f671dcbf6df024da8bebc83f959f7ed940f833e3/README.md) |
| 01&#160;May&#160;24&#160;15:28&#160;UTC | SHAKEN 208K | 08&#160;May&#160;24&#160;15:28&#160;UTC | false | [view](CERTS/cdd36f0ee4bdb7b25eb19d424eb616cbddf98b7dc1f8446e7d7525cebcdd2879/README.md) |
| 04&#160;May&#160;24&#160;15:29&#160;UTC | SHAKEN 208K | 11&#160;May&#160;24&#160;15:29&#160;UTC | false | [view](CERTS/53d0a55a4d65951a60bcad29e4c7fad3d86436452426ccd925954f0445793f3d/README.md) |
| 10&#160;May&#160;24&#160;15:29&#160;UTC | SHAKEN 208K | 17&#160;May&#160;24&#160;15:29&#160;UTC | false | [view](CERTS/f63ede0b2ec0631a0fada38361c671c1f2e43974c15db8193a6302088cc3fe3a/README.md) |
| 16&#160;May&#160;24&#160;15:30&#160;UTC | SHAKEN 208K | 23&#160;May&#160;24&#160;15:30&#160;UTC | false | [view](CERTS/af15df845c44eb4c0eef1edad89d340b6696550e0708f7d938560ab79b2e86c5/README.md) |
| 19&#160;May&#160;24&#160;15:31&#160;UTC | SHAKEN 208K | 26&#160;May&#160;24&#160;15:31&#160;UTC | false | [view](CERTS/56da984012634d665b520db6809cc4b85c4186e283bd318dc3eaf0de81d9a68e/README.md) |
| 22&#160;May&#160;24&#160;15:31&#160;UTC | SHAKEN 208K | 29&#160;May&#160;24&#160;15:31&#160;UTC | false | [view](CERTS/b6e2671f3ad2c895f55ea28b62df400c5a63d46c3fe11f511fe304beb0db9a3a/README.md) |
| 28&#160;May&#160;24&#160;15:31&#160;UTC | SHAKEN 208K | 04&#160;Jun&#160;24&#160;15:31&#160;UTC | false | [view](CERTS/ff13b7925c855c978c1d38d36befb92f31df089b86fe376aafc0d69d9f3aca46/README.md) |
| 31&#160;May&#160;24&#160;15:32&#160;UTC | SHAKEN 208K | 07&#160;Jun&#160;24&#160;15:31&#160;UTC | false | [view](CERTS/3b880df071063c61b7592b1554596db4635f8b595a3f6524af20848d478c247d/README.md) |
| 03&#160;Jun&#160;24&#160;14:18&#160;UTC | SHAKEN 912K | 10&#160;Jun&#160;24&#160;14:18&#160;UTC | false | [view](CERTS/0fdf98a9ee5dc30fcc0c9bc625b3b04f7078f6e455fe4f943d708675a8079652/README.md) |
| 06&#160;Jun&#160;24&#160;15:33&#160;UTC | SHAKEN 208K | 13&#160;Jun&#160;24&#160;15:33&#160;UTC | false | [view](CERTS/ac20bef91265f5df43d67ccc0cf2de484486218533129fd4cf77b7a7df6aba1e/README.md) |
| 09&#160;Jun&#160;24&#160;15:33&#160;UTC | SHAKEN 208K | 16&#160;Jun&#160;24&#160;15:33&#160;UTC | false | [view](CERTS/d8c63ab1758f745edf4f3340c6a8bb041f2a3a91a3f2a38e3f7ae779df58bb67/README.md) |
| 12&#160;Jun&#160;24&#160;15:33&#160;UTC | SHAKEN 208K | 19&#160;Jun&#160;24&#160;15:33&#160;UTC | false | [view](CERTS/3e536ead833ac5f4f2c854095bd3bd45047bc3afde27c889571221816a868e0f/README.md) |
| 18&#160;Jun&#160;24&#160;15:33&#160;UTC | SHAKEN 208K | 25&#160;Jun&#160;24&#160;15:33&#160;UTC | false | [view](CERTS/c6450d07ecd7671909bc01f384fef12228ed5729f3edeaa2dd723ca72af40d80/README.md) |
| 27&#160;Jun&#160;24&#160;15:34&#160;UTC | SHAKEN 208K | 04&#160;Jul&#160;24&#160;15:34&#160;UTC | false | [view](CERTS/c2ffe170122cf0175e87fd34d682fecea37e98d1c3a0084dca7604f622cf2411/README.md) |
| 03&#160;Jul&#160;24&#160;14:21&#160;UTC | SHAKEN 912K | 10&#160;Jul&#160;24&#160;14:21&#160;UTC | false | [view](CERTS/ecee9d9e0181dc18b4691f639b9b0f4b75541b1293f68c893417ac7dda0ac0e2/README.md) |
| 03&#160;Jul&#160;24&#160;15:35&#160;UTC | SHAKEN 208K | 10&#160;Jul&#160;24&#160;15:35&#160;UTC | false | [view](CERTS/9fe37becd1e7f469314b0b4e4aa367ccb14444f70ea96724f75b40f9e7aad90f/README.md) |
| 09&#160;Jul&#160;24&#160;15:35&#160;UTC | SHAKEN 208K | 16&#160;Jul&#160;24&#160;15:35&#160;UTC | false | [view](CERTS/db5f424a03759c35d5628d961fd0b142d3a325944ed0a927e4937be4d4427ef0/README.md) |
| 11&#160;Jul&#160;24&#160;15:30&#160;UTC | SHAKEN 012K | 18&#160;Jul&#160;24&#160;15:30&#160;UTC | false | [view](CERTS/449740c845b686560b3afededc71b5959d541acbea59a0c376430692a9d834be/README.md) |
| 12&#160;Jul&#160;24&#160;15:35&#160;UTC | SHAKEN 208K | 19&#160;Jul&#160;24&#160;15:35&#160;UTC | false | [view](CERTS/0a9b0ec16014d20126f9effae8b194a115fd9401ae3042a1763d197e9fa98ee9/README.md) |
| 15&#160;Jul&#160;24&#160;14:22&#160;UTC | SHAKEN 912K | 22&#160;Jul&#160;24&#160;14:22&#160;UTC | false | [view](CERTS/b753442d2382ee96efc624e308bd2de3f9ece2d1df4dfefafe9e5ba41d69e920/README.md) |
| 21&#160;Jul&#160;24&#160;15:36&#160;UTC | SHAKEN 208K | 28&#160;Jul&#160;24&#160;15:36&#160;UTC | false | [view](CERTS/e05700d4dd0a01cdc0de725a418e257ebe8835c5b68232f57664b6724821c866/README.md) |
| 24&#160;Jul&#160;24&#160;15:36&#160;UTC | SHAKEN 208K | 31&#160;Jul&#160;24&#160;15:36&#160;UTC | false | [view](CERTS/a9296c4ef645a8579f277b1c37db956a7a3aa7074f7b1c618b6a6088a4580601/README.md) |
| 27&#160;Jul&#160;24&#160;14:23&#160;UTC | SHAKEN 912K | 03&#160;Aug&#160;24&#160;14:23&#160;UTC | false | [view](CERTS/c9fe4fcd88f125888579f01792142e87e4e56725120fddd5cd05ed492d544b4d/README.md) |
| 05&#160;Aug&#160;24&#160;15:38&#160;UTC | SHAKEN 208K | 12&#160;Aug&#160;24&#160;15:38&#160;UTC | false | [view](CERTS/9cfebe3eea9d2054965590ad033ddf9360b8752a356c233d017c6823677ad25d/README.md) |
| 11&#160;Aug&#160;24&#160;15:38&#160;UTC | SHAKEN 208K | 18&#160;Aug&#160;24&#160;15:38&#160;UTC | false | [view](CERTS/95685bd06b00edc8974046445dbf0ee04ff8eb02282a0a5f34f70be24ae25095/README.md) |
| 11&#160;Aug&#160;24&#160;22:29&#160;UTC | SHAKEN 021K | 18&#160;Aug&#160;24&#160;22:29&#160;UTC | false | [view](CERTS/39924f784d77d711a514b736e01c9ab964d4f5f21b6a107bbc0ea2b82b75e33e/README.md) |
| 13&#160;Aug&#160;24&#160;15:33&#160;UTC | SHAKEN 012K | 20&#160;Aug&#160;24&#160;15:33&#160;UTC | false | [view](CERTS/66a9a4a0db77fef34834d14c02ffb6be75fb0bfd7645026016b9c61f04cbe260/README.md) |
| 17&#160;Aug&#160;24&#160;15:39&#160;UTC | SHAKEN 208K | 24&#160;Aug&#160;24&#160;15:39&#160;UTC | false | [view](CERTS/b31af1d7e63a998a290010b9af01bf8fa8281473d6183c8e221f0e6e66c51d45/README.md) |
| 20&#160;Aug&#160;24&#160;14:25&#160;UTC | SHAKEN 912K | 27&#160;Aug&#160;24&#160;14:25&#160;UTC | false | [view](CERTS/d41ecf2105de52ce12af9d4f12891a3055d02e93b1ad7dcf94f6ead19da10665/README.md) |
| 20&#160;Aug&#160;24&#160;15:39&#160;UTC | SHAKEN 208K | 27&#160;Aug&#160;24&#160;15:39&#160;UTC | false | [view](CERTS/cdfaeef7117d9b605ae3121fa1cba831db0f59d5c7755802b1ebca33dfcef161/README.md) |
| 22&#160;Aug&#160;24&#160;15:34&#160;UTC | SHAKEN 012K | 29&#160;Aug&#160;24&#160;15:34&#160;UTC | false | [view](CERTS/73f485a4a8fb6c77f4128e8dc7b1b46e751b73933926f1f3edc8d465dc86aed5/README.md) |
| 23&#160;Aug&#160;24&#160;15:40&#160;UTC | SHAKEN 208K | 30&#160;Aug&#160;24&#160;15:40&#160;UTC | false | [view](CERTS/d061ed571f8c788824596e097ef166dd1bf789e6703caf4e5f95b4acf610ac02/README.md) |
| 26&#160;Aug&#160;24&#160;14:25&#160;UTC | SHAKEN 912K | 02&#160;Sep&#160;24&#160;14:25&#160;UTC | false | [view](CERTS/d2dca6af589acc42732d828f778b74e630c77754e389c39439c15c433915bc3b/README.md) |
| 26&#160;Aug&#160;24&#160;15:40&#160;UTC | SHAKEN 208K | 02&#160;Sep&#160;24&#160;15:40&#160;UTC | false | [view](CERTS/2ff87ff42035e75058477067d7d73e1f7c1bf4b49945f39074f80e6f5f33daf0/README.md) |
| 28&#160;Aug&#160;24&#160;15:34&#160;UTC | SHAKEN 012K | 04&#160;Sep&#160;24&#160;15:34&#160;UTC | false | [view](CERTS/986e836e9a6f1e5c1ce1f8d19fbd72354665ce0db7c210c3f89bdd701cc5d8c4/README.md) |
| 29&#160;Aug&#160;24&#160;20:50&#160;UTC | SHAKEN 0843 | 05&#160;Sep&#160;24&#160;20:50&#160;UTC | false | [view](CERTS/b57c50d45c0078a09ecf23d2b227b3f8f3a0aa3d66f19aade8b643ba91d55e96/README.md) |
| 04&#160;Sep&#160;24&#160;14:26&#160;UTC | SHAKEN 912K | 11&#160;Sep&#160;24&#160;14:26&#160;UTC | false | [view](CERTS/84aebb1778985fdd6fe9fb54972c63f1939432294ea7f5612eb3271e01ed267a/README.md) |
| 06&#160;Sep&#160;24&#160;15:35&#160;UTC | SHAKEN 012K | 13&#160;Sep&#160;24&#160;15:35&#160;UTC | false | [view](CERTS/fecab3b8f1b4d4bb6a84d5e4d5f5c65c134dea44edcd60a0bbd23458495b2030/README.md) |
| 10&#160;Sep&#160;24&#160;15:42&#160;UTC | SHAKEN 208K | 17&#160;Sep&#160;24&#160;15:42&#160;UTC | false | [view](CERTS/65e912165f989cc0150e6290735262d1b60df57443ef1af0b3f05adba13b8aac/README.md) |
| 13&#160;Sep&#160;24&#160;15:42&#160;UTC | SHAKEN 208K | 20&#160;Sep&#160;24&#160;15:42&#160;UTC | false | [view](CERTS/7ad236a6ebfe94eebb21b340dbc09dc9fae8dc7fef17129fb85b1a925e44f3e1/README.md) |
| 17&#160;Sep&#160;24&#160;18:08&#160;UTC | SHAKEN 155F | 24&#160;Sep&#160;24&#160;18:08&#160;UTC | false | [view](CERTS/0dd23906260a925c2374d671e4bdd8381f8f599d88b648b59f532e5ab35a025a/README.md) |
| 18&#160;Sep&#160;24&#160;15:36&#160;UTC | SHAKEN 012K | 25&#160;Sep&#160;24&#160;15:36&#160;UTC | false | [view](CERTS/4a7070b627dccac3543f1b64d802c4bed07b6e939aee1079142fb544dd455db8/README.md) |
| 21&#160;Sep&#160;24&#160;15:37&#160;UTC | SHAKEN 012K | 28&#160;Sep&#160;24&#160;15:37&#160;UTC | false | [view](CERTS/69806d7e40616482ad84ebdc3c45aff8dbaebf01ccef2b32f1ce52b7b96570b6/README.md) |
| 23&#160;Sep&#160;24&#160;18:08&#160;UTC | SHAKEN 155F | 30&#160;Sep&#160;24&#160;18:08&#160;UTC | false | [view](CERTS/d2b2f93fc8ed942c7c1459310014891d2b0545153dfb5169a49e53fd2a19cceb/README.md) |

#### CA Certificates

| Created At | Subject | Not After | Problems | Link |
|------------|---------|-----------|----------|------|
| 24&#160;Oct&#160;22&#160;00:00&#160;UTC | TransNexus, Inc. SHAKEN Issuing CA4 | 23&#160;Oct&#160;32&#160;23:59&#160;UTC | false | [view](CERTS/80dd12d935f46c256c7c1289a0834b21ec8f2f8c35f2864928d1e75f3a280665/README.md) |
| 24&#160;Oct&#160;22&#160;00:00&#160;UTC | TransNexus, Inc. SHAKEN Root CA2 | 23&#160;Oct&#160;42&#160;23:59&#160;UTC | false | [view](CERTS/a26e04fc786ab70b8085236b2c53f8cfbf5d0c6a5c2c9c3e9f91669fbb8ea4d5/README.md) |
| 21&#160;Mar&#160;24&#160;00:00&#160;UTC | TransNexus, Inc. SHAKEN Issuing CA5 | 20&#160;Mar&#160;34&#160;23:59&#160;UTC | false | [view](CERTS/cd50eeb8c083af686a49964a10b030048b800530edbeee8f0991388c3a79e75a/README.md) |


Generated: 03 Jun 25 01:30 UTC