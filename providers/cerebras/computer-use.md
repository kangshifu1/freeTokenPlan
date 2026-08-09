# Cerebras Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## 操作脚本

1. 打开 [https://inference.cerebras.ai/](https://inference.cerebras.ai/)
2. 注册或登录
3. 按控制台提示添加已验证支付方式，确认 Free Trial credits 是否到账；官方当前说明为 `$5`，发放后 `30` 天有效
4. 进入 API Keys 页面
5. 创建 key
6. 复制 key
7. 本地保存为环境变量：`CEREBRAS_API_KEY`
8. 查看 docs 中的 OpenAI SDK、Account & Billing、Rate Limits 和官方 Models 页面，确认 Free Trial、uncached / total token 双桶速率限制、模型状态和下线提示
9. 在 CC Switch 中录入兼容信息

## 人工接管点

- 邮箱验证
- 支付方式验证
- 风控校验

## 完成后核对

- 是否记录了当前控制台可用模型
- 是否记录了 Free Trial credits、有效期和双桶速率限制说明
- 是否从官方 Models / Change Log 页面确认默认模型、生产 / 预览状态和 `zai-glm-4.7` 下线日期
