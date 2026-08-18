# Cerebras

[中文](./README.md) | [English](./README.en.md)

- 官网：[Cerebras Inference Docs](https://inference-docs.cerebras.ai/introduction)
- 注册：注册后添加已验证支付方式，激活 Playground / API access，再创建 API key
- 免费：官方账号 / 计费与 Rate Limits 文档说明，新账号添加已验证支付方式后可获得 `$5` Free Trial credits，发放后 `30` 天有效，可用于所有 public models；不额外购买 credits 不会收费
- 限制：Free Trial 层当前对 `gpt-oss-120b` 与 `gemma-4-31b` 列出 `5 RPM` / `30K TPM` / `1M TPH` / `1M TPD`；token rate limiting 现在说明为独立的 uncached token limit 与 total token limit 双桶模型，uncached token 限制可见性按官方说明在 `2026-08-17` 前逐步显示到控制台，实际账号限额仍以控制台和当前 docs 为准
- 模型：当前模型应以官方 [Models](https://inference-docs.cerebras.ai/models) 页面为准；公开生产端点为 `gpt-oss-120b`，`gemma-4-31b` 与 `zai-glm-4.7` 标注为预览模型；变更日志说明 `zai-glm-4.7` 计划在 `2026-08-17` 下线
- 推荐用途：高速推理候补线路

目录文件：

- [computer-use.md](computer-use.md)
- [cc-switch-template.json](cc-switch-template.json)
