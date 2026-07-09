# Cloudflare Workers AI

[中文](./README.md) | [English](./README.en.md)

- 官网：[Workers AI Pricing](https://developers.cloudflare.com/workers-ai/platform/pricing/)
- 注册：Cloudflare 账号登录后启用 Workers AI
- 免费：官方定价页说明 Workers AI 基于 Neurons 计费，每日免费 allocation 为 `10,000` Neurons；超过后需要 Workers Paid plan
- 计费口径：Cloudflare 当前按模型展示示例成本，并说明文本、图片、音频等模型的输入/输出或推理量会换算为 Neurons；同样 `10,000` Neurons 对不同模型代表的请求量不同
- 兼容：官方提供 Workers binding、REST API，以及 OpenAI compatible API endpoints 文档
- 推荐用途：Cloudflare Worker 内调用、边缘侧 AI demo、轻量自动化

目录文件：

- [computer-use.md](computer-use.md)
- [cc-switch-template.json](cc-switch-template.json)
