# Cloudflare Workers AI

[中文](./README.md) | [English](./README.en.md)

- Website: [Workers AI Pricing](https://developers.cloudflare.com/workers-ai/platform/pricing/)
- Registration: sign in with a Cloudflare account and enable Workers AI
- Free tier: the official pricing page says Workers AI is priced in Neurons and includes a free daily allocation of `10,000` Neurons; usage above that requires Workers Paid or prepaid AI Gateway credits
- Billing unit: Cloudflare now shows example costs by model and explains that text, image, audio, and other model usage is converted into Neurons; the same `10,000` Neurons maps to different request volume depending on the model
- Free-plan model scope: the pricing page currently says `@cf/moonshotai/kimi-k2.6`, `@cf/moonshotai/kimi-k2.7-code`, and `@cf/zai-org/glm-5.2` are not available on Workers Free and require Workers Paid or prepaid AI Gateway credits
- Compatibility: Cloudflare documents Workers bindings, REST API, and OpenAI-compatible API endpoints
- Recommended for: Cloudflare Worker calls, edge AI demos, and lightweight automation

Files in this directory:

- [computer-use.md](computer-use.md)
- [computer-use.en.md](computer-use.en.md)
- [cc-switch-template.json](cc-switch-template.json)
