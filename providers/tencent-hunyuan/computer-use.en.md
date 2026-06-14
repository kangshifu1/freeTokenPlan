# Tencent Hunyuan Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## Operator Steps

1. Open [Tencent Cloud Console](https://console.cloud.tencent.com/)
2. Sign in to Tencent Cloud
3. Search for and open Hunyuan
4. Enable Hunyuan text generation if it is not already enabled
5. Complete real-name verification, security checks, or service authorization
6. Create API credentials / SecretId / SecretKey
7. Save them locally as `TENCENT_SECRET_ID` and `TENCENT_SECRET_KEY`
8. Open [Hunyuan billing overview](https://cloud.tencent.com/document/product/1729/97731), then record free resource package, validity, and `Hunyuan-lite` free status
9. If using OpenAI compatibility, open the official compatibility docs and verify the base URL and model name

## Human Takeover Points

- Tencent Cloud login
- Real-name verification
- SMS / WeChat / email security checks

## Final Checklist

- Free resource package is issued
- Validity matches the console
- Default model is still free or covered by the package
- OpenAI-compatible configuration comes from current official docs
