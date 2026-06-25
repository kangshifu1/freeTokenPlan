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
8. Save the key locally as `XFYUN_MAAS_API_KEY`
9. If you use `Coding Plan`, record `astron-code-latest` as the default model first; if you use `Token Plan`, record the supported current `modelId`
10. Before importing into `CC Switch`, re-check validity, remaining quota, supported models, and the allowed usage scenario

## Human Takeover Points

- iFlytek login and verification
- Plan purchase
- Choosing between regular inference, `Token Plan`, and `Coding Plan`

## Final Checklist

- API key came from the correct subscription page
- Base URL matches the selected plan and is not confused with the regular `maas-api`
- `Coding Plan` still uses `astron-code-latest` if that plan is selected
- The current plan allows the intended tool and usage scenario
