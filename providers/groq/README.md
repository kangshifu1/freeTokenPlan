# Groq

[中文](./README.md) | [English](./README.en.md)

- 官网：[Groq Docs](https://console.groq.com/docs/overview)
- 注册：Groq Console 注册后创建 API Key
- 免费：可免费开始；官方 Rate Limits 页面现在列出 `Free Plan Limits` 表，按模型给出 `RPM`、`RPD`、`TPM`、`TPD`
- 当前示例：`groq/compound` / `groq/compound-mini` 为 `30 RPM` / `250 RPD` / `70K TPM`；`meta-llama/llama-prompt-guard-2-22m` / `meta-llama/llama-prompt-guard-2-86m` 为 `30 RPM` / `14.4K RPD` / `15K TPM` / `500K TPD`；`openai/gpt-oss-120b` / `openai/gpt-oss-20b` 和 `qwen/qwen3.6-27b` 为 `30 RPM` / `1K RPD` / `8K TPM` / `200K TPD`
- 限制：限流按组织级别生效，且官方说明公开表是高层摘要；账号的精确当前限额仍以控制台 `Limits` 页面为准
- 推荐用途：低延迟交互、命令行问答

目录文件：

- [computer-use.md](computer-use.md)
- [cc-switch-template.json](cc-switch-template.json)
