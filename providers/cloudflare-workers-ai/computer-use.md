# Cloudflare Workers AI Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## 操作脚本

1. 打开 [Cloudflare Dashboard](https://dash.cloudflare.com/)
2. 登录 Cloudflare 账号
3. 打开 Workers AI 页面
4. 创建 API token，或在 Worker 项目中配置 AI binding
5. 本地保存账号 ID：`CLOUDFLARE_ACCOUNT_ID`
6. 本地保存 token：`CLOUDFLARE_API_TOKEN`
7. 打开 [Pricing](https://developers.cloudflare.com/workers-ai/platform/pricing/) 确认当前每日免费 allocation 是否仍为 `10,000` Neurons
8. 在 Pricing 页查目标模型的示例 Neurons 成本，记录输入、输出或推理量如何换算，避免把 `10,000` Neurons 当作固定请求数
9. 在 Pricing 页确认目标模型是否支持 Workers Free plan；当前 `@cf/moonshotai/kimi-k2.6`、`@cf/moonshotai/kimi-k2.7-code`、`@cf/zai-org/glm-5.2`、`@cf/zai-org/glm-5.3`、`@cf/zai-org/glm-5.3-flash`、`@cf/deepseek-ai/deepseek-v4-flash-0731`、`@cf/deepseek-ai/deepseek-v4-pro-0813` 需要 Workers Paid plan 或预付 AI Gateway credits
10. 如果需要 OpenAI 兼容调用，打开 [OpenAI compatible API endpoints](https://developers.cloudflare.com/workers-ai/configuration/open-ai-compatibility/) 复核当前 base URL

## 人工接管点

- Cloudflare 登录和 2FA
- Account ID 选择
- API token 权限范围

## 完成后核对

- 每日 `10,000` Neurons 免费 allocation 是否仍可用
- 模型消耗的 Neurons 是否适合当前用量，且已按目标模型重新估算请求量
- 目标模型是否在 Workers Free plan 可用范围内
- 是否使用 REST API、Workers binding，还是 OpenAI compatible endpoint
