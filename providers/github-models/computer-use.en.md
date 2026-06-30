# GitHub Models Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## Operator Steps

1. Open [GitHub Models](https://github.com/marketplace/models)
2. Sign in with a GitHub account
3. Select a model and open the playground
4. Check whether the model is in a low, high, embedding, or other rate-limit tier
5. For API usage, open GitHub token settings and create a token usable with Models
6. Save it locally as `GITHUB_TOKEN`
7. Record the endpoint: `https://models.github.ai/inference`
8. Record the default model ID, for example `openai/gpt-4.1-mini` or the current page recommendation
9. Before importing into CC Switch, re-check the model's current free API limits; under Copilot Free, common tiers can start from `Low=15 RPM/150 RPD/5 concurrent`, `High=10 RPM/50 RPD/2 concurrent`, and `Embedding=15 RPM/150 RPD/5 concurrent`, but models such as `DeepSeek-R1` and `xAI Grok-3` have lower model-specific limits and must be confirmed against the current official table; higher-tier rows such as `Azure OpenAI Global Standard`, `Azure OpenAI Data Zone Standard`, and `o1` / `o3` / `gpt-5` families are not applicable to Copilot Free

## Human Takeover Points

- GitHub login and 2FA
- Personal access token creation and scope review; local API calls need `models:read`
- Organization policies that may restrict GitHub Models usage

## Final Checklist

- Token scopes are sufficient but not excessive
- Model ID was copied from the current GitHub Models page
- Free API RPM / RPD / tokens/request / concurrency limits are recorded for the current account type
