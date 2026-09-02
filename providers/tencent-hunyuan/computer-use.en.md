# Tencent Hunyuan Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## Operator Steps

1. Open [Tencent Cloud Console](https://console.cloud.tencent.com/)
2. Sign in to Tencent Cloud
3. Search for and open Hunyuan; if the console points to `TokenHub`, continue from TokenHub
4. Enable Hunyuan text generation or the corresponding TokenHub model service if it is not already enabled
5. Complete real-name verification, security checks, or service authorization
6. Create API credentials / SecretId / SecretKey
7. Save them locally as `TENCENT_SECRET_ID` and `TENCENT_SECRET_KEY`
8. Open [Hunyuan billing overview](https://cloud.tencent.com/document/product/1729/97731) and [TokenHub new-user trial package](https://cloud.tencent.com/document/product/1823/130053), then confirm whether the current entry point has moved to `TokenHub` and whether new capabilities must be enabled there
9. Record whether the account received a TokenHub new-user trial package or the legacy Hunyuan package. The TokenHub new-user trial page was updated on `2026-07-21`; the current language and multimodal-understanding trial packages are `1M Tokens / 1 year`, and the current visual-model free packages are video generation `50 points / 1 year` and 3D generation `100 points / 1 year`; the current Hunyuan text-generation / multimodal shared package is `1M tokens / 1 year`
10. Record the free package, shared model scope, validity, entry-point source, metering unit, and whether `Hunyuan-lite` is excluded from the shared package
11. Check the console postpaid setting and confirm whether usage can continue after free / paid packages are exhausted
12. If using OpenAI compatibility, open the official compatibility docs and verify the base URL and model name

## Human Takeover Points

- Tencent Cloud login
- Real-name verification
- SMS / WeChat / email security checks

## Final Checklist

- Free resource package is issued
- Validity matches the console
- Target model is covered by the matching entry point's package or needs to be opened separately in `TokenHub` / use separate authentication
- TokenHub trial-package types and legacy Hunyuan package entry point, validity, model scope, and metering unit were not mixed, and the TokenHub activity end date still matches the official page
- Exhausted or expired packages still do not automatically roll into postpaid
- OpenAI-compatible configuration comes from current official docs
