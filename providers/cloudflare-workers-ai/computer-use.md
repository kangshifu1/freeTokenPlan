# Cloudflare Workers AI Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## 操作脚本

1. 打开 [Cloudflare Dashboard](https://dash.cloudflare.com/)
2. 登录 Cloudflare 账号
3. 打开 Workers AI 页面
4. 创建 API token，或在 Worker 项目中配置 AI binding
5. 本地保存账号 ID：`CLOUDFLARE_ACCOUNT_ID`
6. 本地保存 token：`CLOUDFLARE_API_TOKEN`
7. 打开 [Pricing](https://developers.cloudflare.com/workers-ai/platform/pricing/) 确认当前每日免费 Neurons allocation
8. 如果需要 OpenAI 兼容调用，打开 [OpenAI compatible API endpoints](https://developers.cloudflare.com/workers-ai/configuration/open-ai-compatibility/) 复核当前 base URL

## 人工接管点

- Cloudflare 登录和 2FA
- Account ID 选择
- API token 权限范围

## 完成后核对

- 免费 allocation 是否仍可用
- 模型消耗的 Neurons 是否适合当前用量
- 是否使用 REST API、Workers binding，还是 OpenAI compatible endpoint
