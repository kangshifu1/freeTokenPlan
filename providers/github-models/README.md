# GitHub Models

[中文](./README.md) | [English](./README.en.md)

- 官网：[GitHub Models](https://docs.github.com/en/github-models)
- 注册：GitHub 账号登录后在 Models playground 或 API 中试用
- 免费：官方文档说明 playground 和 API 提供免费使用，但按模型类型区分 RPM、RPD、tokens/request、并发请求等限制
- Copilot Free 当前常见限制：
  - `Low` 模型：`15 RPM`、`150 RPD`、`8000 input / 4000 output tokens/request`、`5` 并发
  - `High` 模型：`10 RPM`、`50 RPD`、`8000 input / 4000 output tokens/request`、`2` 并发
  - `Embedding` 模型：`15 RPM`、`150 RPD`、`64000 tokens/request`、`5` 并发
  - `DeepSeek-R1` / `DeepSeek-R1-0528` / `MAI-DS-R1`：`1 RPM`、`8 RPD`、`4000 input / 4000 output tokens/request`、`1` 并发
  - `xAI Grok-3`：`1 RPM`、`15 RPD`、`4000 input / 4000 output tokens/request`、`1` 并发；`xAI Grok-3-Mini`：`2 RPM`、`30 RPD`、`4000 input / 8000 output tokens/request`、`1` 并发
- 注意：官方 rate-limit 表也列出 `Azure OpenAI Global Standard`、`Azure OpenAI Data Zone Standard`、`o1` / `o3` / `gpt-5` 系列等更高层级限制；这些行在 `Copilot Free` 下标为不适用，不能当作免费账户额度
- 备注：模型页会标出 rate limit tier；官方说明这些限制可能变更，进入生产前需要重新确认
- 兼容：官方 API 示例可使用 OpenAI SDK 与 `https://models.github.ai/inference` 端点
- 推荐用途：GitHub 用户原型验证、多模型评估、轻量脚本测试

目录文件：

- [computer-use.md](computer-use.md)
- [cc-switch-template.json](cc-switch-template.json)
