# Cloudflare Workers AI

[中文](./README.md) | [English](./README.en.md)

- 官网：[Workers AI Pricing](https://developers.cloudflare.com/workers-ai/platform/pricing/)
- 注册：Cloudflare 账号登录后启用 Workers AI
- 免费：官方定价页说明 Workers AI 基于 Neurons 计费，Workers Free 和 Workers Paid 均有每日 `10,000` Neurons 免费 allocation，并在 `00:00 UTC` 重置；Workers Free 用完后请求会失败，需升级到 Workers Paid 才能继续调用。Paid plan 超出每日免费 allocation 的部分按每 `1,000 Neurons $0.011` 计费；预付 AI Gateway credits 是另一条计费路径
- 计费口径：Cloudflare 当前按模型展示示例成本，并说明文本、图片、音频等模型的输入/输出或推理量会换算为 Neurons；同样 `10,000` Neurons 对不同模型代表的请求量不同
- Free plan 模型范围：定价页当前明确 `@cf/moonshotai/kimi-k2.6`、`@cf/moonshotai/kimi-k2.7-code`、`@cf/zai-org/glm-5.2`、`@cf/zai-org/glm-5.3`、`@cf/zai-org/glm-5.3-flash`、`@cf/deepseek-ai/deepseek-v4-flash-0731`、`@cf/deepseek-ai/deepseek-v4.1-flash-1017`、`@cf/deepseek-ai/deepseek-v4-pro-0813`、`@cf/thinkingmachines/inkling-2-small` 不支持 Workers Free plan；使用这些模型需要 Workers Paid 或预付 AI Gateway credits。该名单会独立变化，使用前应逐行复核目标模型
- 兼容：官方提供 Workers binding、REST API，以及 OpenAI compatible API endpoints 文档
- 推荐用途：Cloudflare Worker 内调用、边缘侧 AI demo、轻量自动化

目录文件：

- [computer-use.md](computer-use.md)
- [cc-switch-template.json](cc-switch-template.json)
