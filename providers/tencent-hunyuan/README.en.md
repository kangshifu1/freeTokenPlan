# Tencent Hunyuan

[中文](./README.md) | [English](./README.en.md)

- Website: [Hunyuan billing overview](https://cloud.tencent.com/document/product/1729/97731)
- Registration: create a Tencent Cloud account, enable Hunyuan, and complete required real-name verification
- Free tier: the current official billing overview says Tencent Hunyuan capabilities are gradually moving to `TokenHub`; existing purchased services are not affected for now, while new model services or additional capabilities should be opened in TokenHub
- Free package: after real-name verification, first clicking "Use Now" grants free trial quota. The current Hunyuan text-generation free quota is a one-time resource package: listed Hunyuan text models, excluding `Hunyuan-lite`, and Hunyuan multimodal models share `1M tokens` valid for `1 year` from service activation; `Hunyuan-embedding` is listed separately with `1M tokens / 1 year`
- Billing behavior: Tencent deducts free packages before paid packages and postpaid billing. When free or paid packages are exhausted or expire, usage does not automatically roll into postpaid unless the user explicitly enables postpaid in the console
- Compatibility: Tencent Hunyuan documents OpenAI-compatible access; current base URL and model names should be verified in official docs
- Recommended for: mainland China Hunyuan trials, lightweight text generation, and OpenAI-compatible client integration

Files in this directory:

- [computer-use.md](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/tencent-hunyuan/computer-use.md)
- [computer-use.en.md](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/tencent-hunyuan/computer-use.en.md)
- [cc-switch-template.json](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/tencent-hunyuan/cc-switch-template.json)
