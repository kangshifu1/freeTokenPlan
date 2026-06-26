# GitHub Models Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## 操作脚本

1. 打开 [GitHub Models](https://github.com/marketplace/models)
2. 使用 GitHub 账号登录
3. 选择一个模型并进入 playground
4. 在模型页面确认该模型属于 low / high / embedding 等哪类 rate limit
5. 若要 API 调用，打开 GitHub token 设置页并创建可用于 Models 的 token
6. 本地保存为环境变量：`GITHUB_TOKEN`
7. 记录端点：`https://models.github.ai/inference`
8. 记录默认模型 ID，例如 `openai/gpt-4.1-mini` 或当前页面推荐模型
9. 导入 CC Switch 前，复核该模型当前免费 API 限制；Copilot Free 下常见 tier 可先按 `Low=15 RPM/150 RPD/5 并发`、`High=10 RPM/50 RPD/2 并发`、`Embedding=15 RPM/150 RPD/5 并发` 作为保守记录，但 `DeepSeek-R1`、`xAI Grok-3` 等模型有更低的独立限制，必须按当前官方表逐模型确认

## 人工接管点

- GitHub 登录和 2FA
- Personal access token 创建与权限确认；本地 API 调用需要 `models:read` 权限
- 组织策略可能限制 Models 使用

## 完成后核对

- token 权限是否足够且不过大
- 模型 ID 是否来自当前 GitHub Models 页面
- 免费 API 的 RPM / RPD / tokens/request / 并发限制是否已记录，且记录的是当前账号类型下的限制
