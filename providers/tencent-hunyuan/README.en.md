# Tencent Hunyuan

[中文](./README.md) | [English](./README.en.md)

- Website: [Hunyuan billing overview](https://cloud.tencent.com/document/product/1729/97731) / [TokenHub new-user trial package](https://cloud.tencent.com/document/product/1823/130053) / [TokenHub](https://console.cloud.tencent.com/tokenhub)
- Registration: create a Tencent Cloud account, enable Hunyuan or TokenHub, and complete required real-name verification
- Free tier: the current official billing overview says Tencent Hunyuan capabilities are gradually moving to `TokenHub`; existing purchased services are not affected for now, while new model services or additional capabilities should be opened in TokenHub rather than assumed available through the legacy Hunyuan console path
- TokenHub trial package: the official TokenHub new-user trial page was updated on `2026-07-21` and currently lists language-model and visual-model packages. The current activity is scheduled through `2026-12-31`, subject to page notices or platform announcements. Language and multimodal-understanding packages provide `1M Tokens / 1 year`; the current visual-model free packages are video-generation `50 points / 1 year` and 3D-generation `100 points / 1 year`
- Hunyuan package: after real-name verification, first clicking "Use Now" grants free trial quota. The current Hunyuan text-generation free quota is a one-time resource package: listed Hunyuan text models, excluding `Hunyuan-lite`, and Hunyuan multimodal models share `1M tokens` valid for `1 year` from service activation; `Hunyuan-embedding` is listed separately with `1M tokens / 1 year`
- Billing behavior: Tencent deducts free packages before paid packages and postpaid billing. When free or paid packages are exhausted or expire, usage does not automatically roll into postpaid unless the user explicitly enables postpaid in the console
- Compatibility: Tencent Hunyuan documents OpenAI-compatible access; current TokenHub / Hunyuan base URLs, authentication details, and model names should be verified in official docs. Do not mix TokenHub trial-package types with the legacy Hunyuan package when recording entry point, validity, model scope, or metering unit
- Recommended for: mainland China Hunyuan trials, lightweight text generation, and OpenAI-compatible client integration

Files in this directory:

- [computer-use.md](computer-use.md)
- [computer-use.en.md](computer-use.en.md)
- [cc-switch-template.json](cc-switch-template.json)
