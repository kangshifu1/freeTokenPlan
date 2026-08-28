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
8. Open [new-user free quota](https://cloud.baidu.com/doc/qianfan/s/Imi2rpirg), confirm whether the free quota was issued automatically on first activation, then record covered models, token grants, and validity; current official examples include `ERNIE-4.5-Turbo`, `DeepSeek`, `Kimi`, and `Qwen3` / `Qwen3-Coder` models, but the account page remains authoritative
9. For normal model-service access through CC Switch or another OpenAI-compatible client, open the [OpenAI SDK compatibility](https://cloud.baidu.com/doc/qianfan/s/Hmh4suq26) guide and record the normal model-service base URL: `https://qianfan.baidubce.com/v2`
10. If the target is a coding-tool subscription, open [Token Plan personal](https://cloud.baidu.com/doc/qianfan/s/Dmrabu8b6) and the [quickstart](https://cloud.baidu.com/doc/qianfan/s/kmracfgi2), confirm whether the account should purchase or migrate to `Token Plan`, and copy the dedicated `Token Plan personal` API key from the subscription page
11. Record the dedicated `Token Plan personal` base URLs: OpenAI `https://qianfan.baidubce.com/v2/tokenplan/personal`, Anthropic `https://qianfan.baidubce.com/anthropic/tokenplan/personal`
12. For CC-Switch with Claude Code, open Baidu's [Token Plan personal CC-Switch guide](https://cloud.baidu.com/doc/qianfan/s/Tmrad8foj), use the official JSON fields such as `ANTHROPIC_AUTH_TOKEN`, `ANTHROPIC_BASE_URL`, and the currently supported model; do not mix a normal Qianfan key with a Token Plan dedicated key
13. Set the default model to a model covered by either the current account's free quota or Token Plan package; record normal new-user free quota, `Token Plan personal`, and legacy `Coding Plan` quota / base URLs separately

## Human Takeover Points

- Baidu Cloud login
- Individual or business verification
- SMS or email security checks
- Token Plan subscription purchase, migration, or auto-renewal confirmation

## Final Checklist

- Free quota claimed
- Validity period recorded from the current page
- Default model is within the current account's free quota
- OpenAI-compatible base URL recorded from current official docs
- If Token Plan is used, dedicated API key, OpenAI / Anthropic base URLs, package validity, and covered models are recorded
