# Cloudflare Workers AI Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## Operator Steps

1. Open [Cloudflare Dashboard](https://dash.cloudflare.com/)
2. Sign in to Cloudflare
3. Open Workers AI
4. Create an API token, or configure an AI binding in a Worker project
5. Save the account ID locally as `CLOUDFLARE_ACCOUNT_ID`
6. Save the token locally as `CLOUDFLARE_API_TOKEN`
7. Open [Pricing](https://developers.cloudflare.com/workers-ai/platform/pricing/) and confirm whether the free daily allocation is still `10,000` Neurons
8. For OpenAI-compatible calls, open [OpenAI compatible API endpoints](https://developers.cloudflare.com/workers-ai/configuration/open-ai-compatibility/) and verify the current base URL

## Human Takeover Points

- Cloudflare login and 2FA
- Account ID selection
- API token scope review

## Final Checklist

- Daily `10,000` Neurons free allocation is still available
- Model Neurons cost fits the intended usage
- Call path is REST API, Workers binding, or OpenAI-compatible endpoint
