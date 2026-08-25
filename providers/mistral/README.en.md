# Mistral

[中文](./README.md) | [English](./README.en.md)

- Website: [Mistral Pricing](https://mistral.ai/pricing)
- Registration: create a Mistral platform account
- Free tier: the public pricing page still lists Mistral Free with limited Vibe for code access and `$10/mo` in API credits; the Studio quickstart says API `Free mode` is enabled by default, does not require a credit card for the free trial, and uses limited rate limits for evaluation and prototyping
- Key / billing boundary: API keys are not tied to a billing mode; the same key follows the workspace's current plan and billing state as it moves from `Free mode` to `Pay as you go` or a higher tier; the official developer quickstart also maps `402 Payment Required` to an account with no payment method, so first API calls still need current workspace payment-method and billing-state checks
- Upgrade path: move to the `Scale` plan for higher limits, then usage tiers increase with cumulative billed usage
- Recommended for: model-style testing and light development evaluation

Files in this directory:

- [computer-use.md](computer-use.md)
- [computer-use.en.md](computer-use.en.md)
- [cc-switch-template.json](cc-switch-template.json)
