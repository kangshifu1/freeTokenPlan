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
8. 查看 docs 中的 OpenAI SDK、Account & Billing、Rate Limits 和官方 Models 页面，确认 Free Trial 的 `$5` / `30` 天边界、`5 RPM` / `30K uncached TPM` / `90K total TPM` / `1M TPH` / `1M TPD` 限制，以及当前公开模型 `gpt-oss-120b` 和 `qwen-3.8-27b`
9. 在 CC Switch 中录入兼容信息

## 人工接管点

- 邮箱验证
- 支付方式验证
- 风控校验

## 完成后核对

- 是否记录了当前控制台可用模型，并与官方 Models 页面核对
- 是否记录了 Free Trial credits、有效期、双桶速率限制和“无永久免费层”说明
- 是否从官方 Models 页面确认当前公开模型
