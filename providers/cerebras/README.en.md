# Cerebras

[中文](./README.md) | [English](./README.en.md)

- Website: [Cerebras Inference Docs](https://inference-docs.cerebras.ai/introduction)
- Registration: sign up, add a verified payment method to activate Playground / API access, then create an API key
- Free tier: the official Account & Billing and Rate Limits docs say new accounts receive `$5` Free Trial credits after adding a verified payment method; credits expire `30` days after they are granted and can be used across all public models
- Limits: the Free Trial tier currently lists `5 RPM` / `30K uncached TPM` / `90K total TPM` / `1M TPH` / `1M TPD` for `gpt-oss-120b` and `qwen-3.8-27b`; token rate limiting uses independent uncached and total token buckets, and actual account limits still depend on the console and current docs
- Models: check the official [Models](https://inference-docs.cerebras.ai/models/overview) page for current model IDs; the public shared endpoints currently list `gpt-oss-120b` and `qwen-3.8-27b`; Cerebras does not currently offer a permanently renewing free allowance
- Recommended for: fast inference backup routes

Files in this directory:

- [computer-use.md](computer-use.md)
- [computer-use.en.md](computer-use.en.md)
- [cc-switch-template.json](cc-switch-template.json)
