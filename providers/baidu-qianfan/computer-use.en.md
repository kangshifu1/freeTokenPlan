# Baidu Qianfan Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## Operator Steps

1. Open [Baidu Qianfan Console](https://console.bce.baidu.com/qianfan/)
2. Sign in with a Baidu Cloud account
3. Enable Qianfan if it is not already enabled
4. Complete required individual or business verification
5. Open the API key / security credential page
6. Create and copy the API key / secret
7. Save it locally as `QIANFAN_API_KEY`; if required, also save `QIANFAN_SECRET_KEY`
8. Open [new-user free quota](https://cloud.baidu.com/doc/qianfan/s/Imi2rpirg), then record available models, token grants, and validity
9. For CC Switch, first confirm whether the current model exposes an OpenAI-compatible route or needs a local proxy

## Human Takeover Points

- Baidu Cloud login
- Individual or business verification
- SMS or email security checks

## Final Checklist

- Free quota claimed
- Validity period recorded from the current page
- Default model is within the current account's free quota
- Compatibility endpoint comes from current official docs
