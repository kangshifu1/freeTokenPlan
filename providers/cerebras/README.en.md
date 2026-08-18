# Cerebras

[中文](./README.md) | [English](./README.en.md)

- Website: [Cerebras Inference Docs](https://inference-docs.cerebras.ai/introduction)
- Registration: sign up, add a verified payment method to activate Playground / API access, then create an API key
- Free tier: the official Account & Billing and Rate Limits docs say new accounts receive `$5` Free Trial credits after adding a verified payment method; credits expire `30` days after they are granted and can be used across all public models
- Limits: the Free Trial tier currently lists `5 RPM` / `30K TPM` / `1M TPH` / `1M TPD` for `gpt-oss-120b` and `gemma-4-31b`; token rate limiting is now documented as a dual-bucket model with independent uncached and total token limits, with uncached-token visibility described by the official docs as rolling out to consoles by `2026-08-17`; actual account limits still depend on the console and current docs
- Models: check the official [Models](https://inference-docs.cerebras.ai/models) page for current model IDs; the public production endpoint is `gpt-oss-120b`, while `gemma-4-31b` and `zai-glm-4.7` are marked as preview; the change log says `zai-glm-4.7` is scheduled for deprecation on `2026-08-17`
- Recommended for: fast inference backup routes

Files in this directory:

- [computer-use.md](computer-use.md)
- [computer-use.en.md](computer-use.en.md)
- [cc-switch-template.json](cc-switch-template.json)
