# Groq Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## 操作脚本

1. 打开 [https://console.groq.com/](https://console.groq.com/)
2. 注册或登录
3. 进入 API Keys 页面
4. 点击创建新 key
5. 复制 key
6. 本地保存为环境变量：`GROQ_API_KEY`
7. 打开官方 Rate Limits 文档和组织级 `Limits` 页面确认当前可用模型与限额；先记录目标模型的 `RPM`、`RPD`、`TPM`、`TPD`
8. 在 CC Switch 中添加：
   - Base URL：`https://api.groq.com/openai/v1`
   - 默认模型：选择当前控制台可见模型

## 人工接管点

- 邮箱验证
- 安全验证

## 完成后核对

- key 是否可用
- 目标模型的免费计划限额是否仍与官方 Rate Limits 页面一致
- 当前组织级限额是否低于公开表或需要备注到 README
