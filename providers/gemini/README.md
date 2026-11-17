# Gemini

[中文](./README.md) | [English](./README.en.md)

- 官网：[Gemini API Pricing](https://ai.google.dev/gemini-api/docs/pricing)
- 注册：Google 账号登录 AI Studio 后创建 API Key；新建 key 默认生成 `auth keys`
- 免费：官方长期提供按模型和调用模式区分的 Free tier；当前 `gemini-3.8-flash` Standard API 的输入、输出和上下文缓存均免费，但 Batch、Google Search grounding 和 Maps grounding 不在其 Free tier。付费档当前为 Gemini 3 及更新模型共享每月 `5,000` 次免费 Search / Maps requests，不应记作 Free tier 配额。Gemini 2.5 和 Embedding 等其他模型仍需逐行确认；创建或迁移 key 时还应确认 key 类型和状态
- 兼容：官方提供 [OpenAI compatibility](https://ai.google.dev/gemini-api/docs/openai)，当前 base URL 为 `https://generativelanguage.googleapis.com/v1beta/openai/`，但建议先确认下游工具所需协议
- 推荐用途：免费试用、轻量 coding、搜索 grounding demo

目录文件：

- [computer-use.md](computer-use.md)
- [cc-switch-template.json](cc-switch-template.json)
