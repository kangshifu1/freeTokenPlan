# Vercel AI Gateway Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## 操作脚本

1. 打开 [https://vercel.com/docs/ai-gateway](https://vercel.com/docs/ai-gateway)
2. 登录 Vercel
3. 选择 team / project
4. 打开 AI Gateway 设置或 usage 页面
5. 创建或复制 AI Gateway 所需 token / project 配置
6. 本地按实际 SDK 保存环境变量，例如 `AI_GATEWAY_API_KEY`
7. 打开 [Pricing](https://vercel.com/docs/ai-gateway/pricing)，确认当前免费 credits 和是否已经发生过付费使用
8. 若通过 CC Switch 使用，先确认当前 Vercel AI Gateway 是否暴露可被该版本识别的 OpenAI-compatible base URL

## 人工接管点

- Vercel 登录
- Team / project 选择
- 账单或 usage 页面确认

## 完成后核对

- 当前 team 是否仍有免费 credits
- 首次付费后免费 credits 规则是否变化
- 实际调用方式是 AI SDK、OpenAI 风格网关，还是项目内代理
