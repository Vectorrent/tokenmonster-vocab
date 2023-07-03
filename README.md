---
license: mit
---
## TokenMonster

The documentation and code is available on Github [alasdairforsythe/tokenmonster](https://github.com/alasdairforsythe/tokenmonster).

The prebuilt vocabularies are all available for download [here](https://huggingface.co/alasdairforsythe/tokenmonster/tree/main/vocabs).

**July 3:** TokenMonster v1.0 has been released. The "420" prebuilt vocabularies are being released as they are completed, at a rate of around 10 per day. Let me know if there's one you want and I can prioritize it.

Choose a dataset from:

- `code`
- `english`
- `englishcode`
- `fiction`

Choose a vocab size from:
- `1024`
- `2048`
- `4096`
- `8000`
- `16000`
- `24000`
- `32000`
- `40000`
- `50256`
- `65536`
- `100256`

Choose an optimization mode from:
- `unfiltered`
- `clean`
- `balanced`
- `consistent`
- `strict`

For a capcode disabled vocabulary add:
- `nocapcode`

And finally add the version number:
- `v1`

Examples:
- `fiction-24000-consistent-v1`
- `code-4096-clean-nocapcode-v1`