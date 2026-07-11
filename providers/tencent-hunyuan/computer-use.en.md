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
8. Open [Hunyuan billing overview](https://cloud.tencent.com/document/product/1729/97731), then confirm whether the current entry point has moved to `TokenHub` and whether new capabilities must be enabled there
9. Record the free package, shared model scope, validity, entry-point source, and whether `Hunyuan-lite` is excluded from the shared package
10. Check the console postpaid setting and confirm whether usage can continue after free / paid packages are exhausted
11. If using OpenAI compatibility, open the official compatibility docs and verify the base URL and model name

## Human Takeover Points

- Tencent Cloud login
- Real-name verification
- SMS / WeChat / email security checks

## Final Checklist

- Free resource package is issued
- Validity matches the console
- Target model is covered by the shared package or needs to be opened separately in `TokenHub` / use separate authentication
- Exhausted or expired packages still do not automatically roll into postpaid
- OpenAI-compatible configuration comes from current official docs
