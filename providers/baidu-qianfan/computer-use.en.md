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
8. Open [new-user free quota](https://cloud.baidu.com/doc/qianfan/s/Imi2rpirg), confirm whether the free quota was issued automatically, then record covered models, token grants, and validity; current official examples include `ERNIE-4.5-Turbo`, `DeepSeek`, `Kimi`, and `Qwen3` / `Qwen3-Coder` models, but the account page remains authoritative
9. For CC Switch, open the [OpenAI SDK compatibility](https://cloud.baidu.com/doc/qianfan/s/Hmh4suq26) guide and record the base URL: `https://qianfan.baidubce.com/v2`
10. Set the default model to a model covered by the current account's free quota; if the target tool needs Anthropic protocol behavior, confirm whether a local proxy is still required

## Human Takeover Points

- Baidu Cloud login
- Individual or business verification
- SMS or email security checks

## Final Checklist

- Free quota claimed
- Validity period recorded from the current page
- Default model is within the current account's free quota
- OpenAI-compatible base URL recorded from current official docs
