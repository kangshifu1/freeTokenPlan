# iFlytek Astron MaaS Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## Operator Steps

1. Open [https://maas.xfyun.cn/modelSquare](https://maas.xfyun.cn/modelSquare)
2. Sign in with an iFlytek account
3. Open the subscription or model-square area and decide whether you need regular inference, `Astron Token Plan`, or `Astron Coding Plan`
4. For coding-tool integration, open the official `Token Plan` or `Coding Plan` docs and verify the current base URL and model ID
5. Purchase or activate the selected plan, then copy the dedicated API key
6. For `Token Plan`:
   - OpenAI Base URL: `https://maas-token-api.cn-huabei-1.xf-yun.com/v2`
   - Anthropic Base URL: `https://maas-token-api.cn-huabei-1.xf-yun.com/anthropic`
7. For `Coding Plan`:
   - OpenAI Base URL: `https://maas-coding-api.cn-huabei-1.xf-yun.com/v2`
   - Anthropic Base URL: `https://maas-coding-api.cn-huabei-1.xf-yun.com/anthropic`
   - Responses Base URL: `https://maas-coding-api.cn-huabei-1.xf-yun.com/v1/responses`
8. Save the key locally as `XFYUN_MAAS_API_KEY`
9. If you use `Coding Plan`, record `astron-code-latest` as the default model first; you can also switch to an official underlying `modelId`, such as `xopglm52`, `xopglm51`, `xopglm5`, `xopdeepseekv4pro`, `xopdeepseekv4flash`, `xopdeepseekv32`, `xopkimik26`, `xopkimik25`, `xopqwen35397b`, `xopqwen36v35b`, `xop3qwencodernext`, or `xopglmv47flash`
10. Before importing into `CC Switch`, re-check the current plan version, such as the discontinued first-month plan, monthly / quarterly renewed-version offers, or enterprise / team `Token Plan`, plus validity, remaining quota, supported models, and the allowed usage scenario
11. If you use `Coding Plan`, confirm the task is an interactive coding-tool scenario such as Claude Code, OpenCode, Cursor, OpenClaw, or Codex; do not use it for automation scripts, batch jobs, or self-hosted backend workloads
12. If using off-peak windows at night, on weekends, or on holidays, confirm whether the current `0.8` coefficient still applies to request limits / point usage

## Human Takeover Points

- iFlytek login and verification
- Plan purchase
- Choosing between regular inference, `Token Plan`, and `Coding Plan`

## Final Checklist

- API key came from the correct subscription page
- Base URL matches the selected plan and is not confused with the regular `maas-api`
- `Coding Plan` still uses `astron-code-latest` or the currently configured underlying model
- The Responses-compatible endpoint is used only for the `Coding Plan` route
- The current plan version, validity, and quota allow the intended tool and usage scenario, especially whether the first-month plan is still unavailable and whether the renewed-version offer is monthly or quarterly
