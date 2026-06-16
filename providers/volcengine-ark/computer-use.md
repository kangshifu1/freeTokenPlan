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
9. 若使用 `Agent Plan` / `Coding Plan`，打开对应计费或活动页，区分套餐抵扣、活动折扣和免费推理额度
10. 打开对应模型或接入工具文档，确认 OpenAI 兼容 base URL、模型名和 endpoint
11. 导入 CC Switch 前，确认当前模型是否仍在免费额度或活动范围内

## 人工接管点

- 火山引擎登录
- 实名认证
- 短信 / 邮箱 / 风控验证

## 完成后核对

- 免费推理额度是否可见
- 是否启用安心体验模式或明确关闭超额付费风险
- `Agent Plan` / `Coding Plan` 是否只是套餐或活动折扣，而不是长期免费 API 额度
- 默认模型和 endpoint 是否来自当前控制台
- OpenAI 兼容配置是否通过官方文档确认
