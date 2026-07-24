# 讯飞星辰 MaaS

[中文](./README.md) | [English](./README.en.md)

- 官网：[讯飞星辰 MaaS 模型广场](https://maas.xfyun.cn/modelSquare)
- 注册：讯飞账号 / 控制台登录后开通星辰 MaaS，并按页面要求完成必要认证
- 免费：模型广场可浏览模型与平台能力，但当前对编程工具接入更清晰、可公开复核的是 `Astron Token Plan` 和 `Astron Coding Plan` 套餐文档；`Token Plan` 当前面向企业 / 团队场景并列出 `GLM-5.2` / `GLM-5.1` / `GLM-5`、`DeepSeek-V4-Pro`、`DeepSeek-V4-Flash`、`DeepSeek-V3.2`、`Kimi-K2.6`、`Kimi-K2.5`、`MiniMax-M2.5`、`Qwen3.5` / `Qwen3.6`、`Qwen3-Coder-Next-FP8`、`GLM-4.7-Flash` 等可切换模型示例；`Coding Plan` 使用 `astron-code-latest` 作为统一默认模型，并列出包含 `Kimi-K2.7-Code` 的相近模型池，按积分 / 请求流控计量并有非高峰 `0.8` 时段系数；`2026-07-23` 版本的模型抵扣系数表中 `Kimi-K2.7-Code` 的 `modelId` 为 `xopkimi27code`，抵扣系数为 `5`；`Coding Plan` 当前说明 `首月版` 自 `2026-04-09 00:00` 起不再支持购买，`焕新版` 自 `2026-04-09` 起按月订购、自 `2026-06-15` 起支持按季订购，并自 `2026-06-18` 起按高峰 / 波谷系数折算请求流控，不应把它们写成长期全站免费 API
- 兼容：官方文档明确给出 `OpenAI`、`Anthropic` 以及 `Coding Plan` 的 Responses 兼容入口；`Token Plan` 与 `Coding Plan` 使用各自独立 base URL，不能和普通 `maas-api` 混用
- 推荐用途：中国大陆用户接入 `Claude Code`、`Cursor`、`OpenCode`、`OpenClaw` 等编程工具，按套餐选择统一模型路由

目录文件：

- [computer-use.md](computer-use.md)
- [cc-switch-template.json](cc-switch-template.json)
