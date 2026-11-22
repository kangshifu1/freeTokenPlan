# Cloudflare Workers AI

[中文](./README.md) | [English](./README.en.md)

- Website: [Workers AI Pricing](https://developers.cloudflare.com/workers-ai/platform/pricing/)
- Registration: sign in with a Cloudflare account and enable Workers AI
- Free tier: both Workers Free and Workers Paid include a daily allocation of `10,000` free Neurons, resetting at `00:00 UTC`. On Workers Free, requests fail after the allocation is exhausted; upgrade to Workers Paid to continue calling models. Workers Paid charges `$0.011 per 1,000 Neurons` above the daily allocation; prepaid AI Gateway credits are a separate billing path
- Billing unit: Cloudflare now shows example costs by model and explains that text, image, audio, and other model usage is converted into Neurons; the same `10,000` Neurons maps to different request volume depending on the model
- Free-plan model scope: the pricing page currently says `@cf/moonshotai/kimi-k2.6`, `@cf/moonshotai/kimi-k2.7-code`, `@cf/zai-org/glm-5.2`, `@cf/zai-org/glm-5.3`, `@cf/zai-org/glm-5.3-flash`, `@cf/deepseek-ai/deepseek-v4-flash-0731`, `@cf/deepseek-ai/deepseek-v4.1-flash-1017`, `@cf/deepseek-ai/deepseek-v4-pro-0813`, and `@cf/thinkingmachines/inkling-2-small` are unavailable on Workers Free; using these models requires Workers Paid or prepaid AI Gateway credits. Re-check the exact target model row because this list changes independently of the daily allocation
- Compatibility: Cloudflare documents Workers bindings, REST API, and OpenAI-compatible API endpoints
- Recommended for: Cloudflare Worker calls, edge AI demos, and lightweight automation

Files in this directory:

- [computer-use.md](computer-use.md)
- [computer-use.en.md](computer-use.en.md)
- [cc-switch-template.json](cc-switch-template.json)
