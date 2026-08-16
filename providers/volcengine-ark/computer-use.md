# 火山方舟 Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## 操作脚本

1. 打开 [火山方舟控制台](https://console.volcengine.com/ark/)
2. 使用火山引擎账号登录
3. 若未开通方舟，按页面提示开通
4. 完成实名认证和安全验证
5. 打开 API Key / 接入点 / Endpoint 管理页
6. 创建并复制 API Key
7. 本地保存为环境变量：`ARK_API_KEY`
8. 查看控制台的免费推理额度、安心体验模式和当前活动额度
9. 若使用豆包搜索 / `web_search`，打开模型价格页、Agent Plan 套餐页或控制台，分开确认普通免费包、套餐周期搜索额度、适用工具和超额规则
10. 若使用 `Coding Plan`，打开对应套餐 / 计费 / 活动页，确认套餐额度、模型范围、有效期和折扣规则
11. 打开 `Agent Plan` / `Coding Plan` 下的“接入 AI 工具”文档，按目标工具确认 Codex、Claude Code、OpenCode、OpenClaw 等入口的 base URL、模型名、endpoint 和环境变量
12. 导入 CC Switch 前，确认当前模型是否仍在免费额度或活动范围内

## 人工接管点

- 火山引擎登录
- 实名认证
- 短信 / 邮箱 / 风控验证

## 完成后核对

- 免费推理额度是否可见
- 是否启用安心体验模式或明确关闭超额付费风险
- 豆包搜索 / `web_search` 的普通免费包和 Agent Plan 套餐搜索额度是否已按当前服务文档或控制台分开记录
- `Coding Plan` 的套餐额度、模型范围、有效期和折扣规则是否来自当前套餐页
- `Agent Plan` / `Coding Plan` 是否只是套餐或活动折扣，而不是长期免费 API 额度
- 所用工具入口是否来自当前官方“接入 AI 工具”页面
- 默认模型和 endpoint 是否来自当前控制台
- OpenAI 兼容配置是否通过官方文档确认
