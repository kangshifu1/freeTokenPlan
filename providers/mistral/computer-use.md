# Mistral Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## 操作脚本

1. 打开 [https://console.mistral.ai/](https://console.mistral.ai/)
2. 注册或登录
3. 打开 API Keys 页面
4. 新建 key
5. 复制 key
6. 本地保存为环境变量：`MISTRAL_API_KEY`
7. 查看 Studio / Console、[Mistral Pricing](https://mistral.ai/pricing)、[Activate Studio and generate an API key](https://docs.mistral.ai/getting-started/quickstarts/studio/activate-and-generate-api-key) 和 [Send your first API request](https://docs.mistral.ai/getting-started/quickstarts/developer/first-api-request) 页面，确认当前 API `Free mode`、无需信用卡试用、rate limit、`Mistral Free` / `Vibe for code` 计划说明、Free 计划是否仍列出 `$10/月` API credits，以及当前文档是否仍把 `402 Payment Required` 归因为账号缺少支付方式
8. 查看 [API keys](https://docs.mistral.ai/admin/identity-access/api-keys)，记录 key 所属 workspace 的当前计划；不要把 key 写成“free key”或“PAYG key”，因为官方说明 key 会随 workspace 计划 / 账单状态生效
9. 若导入 CC Switch，建议通过统一兼容网关接入

## 人工接管点

- 邮箱验证
- 可能的组织或 workspace 创建步骤

## 完成后核对

- 是否已创建 key
- 是否记录当前免费模式条件、Free 计划 API credits、workspace 计划、支付方式要求和 key / 计费边界
