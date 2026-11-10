# Vercel AI Gateway Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## Operator Steps

1. Open [https://vercel.com/docs/ai-gateway](https://vercel.com/docs/ai-gateway)
2. Sign in to Vercel
3. Select the team / project
4. Open AI Gateway settings or usage
5. Create or copy the token / project configuration required by AI Gateway
6. Save the actual SDK variable locally, for example `AI_GATEWAY_API_KEY`
7. Open [Pricing](https://vercel.com/docs/ai-gateway/pricing) and confirm whether the free tier is still `$5/month` credits for all available models and whether credits have already been purchased
8. For CC Switch, first verify whether the current AI Gateway exposes an OpenAI-compatible base URL supported by your installed version; if you need BYOK provider keys, confirm that the account is on a paid plan that supports them

## Human Takeover Points

- Vercel login
- Team / project selection
- Billing or usage-page confirmation

## Final Checklist

- Current team is still under the `$5/month` free-credit rule
- Target model is still listed as an available AI Gateway model
- Monthly free credit no longer applying after purchased credits is understood
- Actual call path is AI SDK, OpenAI-style gateway, or a project-local proxy
