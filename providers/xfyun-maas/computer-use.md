# 讯飞星辰 MaaS Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## 操作脚本

1. 打开 [https://maas.xfyun.cn/modelSquare](https://maas.xfyun.cn/modelSquare)
2. 登录讯飞账号
3. 进入套餐订阅或模型广场，确认你要接的是普通推理、`Astron Token Plan` 还是 `Astron Coding Plan`
4. 若用于编程工具接入，优先打开官方 `Token Plan` 或 `Coding Plan` 文档核对当前 base URL 与 modelId
5. 在对应订阅页购买或开通后复制专属 API Key
6. 若接 `Token Plan`：
   - OpenAI Base URL：`https://maas-token-api.cn-huabei-1.xf-yun.com/v2`
   - Anthropic Base URL：`https://maas-token-api.cn-huabei-1.xf-yun.com/anthropic`
7. 若接 `Coding Plan`：
   - OpenAI Base URL：`https://maas-coding-api.cn-huabei-1.xf-yun.com/v2`
   - Anthropic Base URL：`https://maas-coding-api.cn-huabei-1.xf-yun.com/anthropic`
   - Responses Base URL：`https://maas-coding-api.cn-huabei-1.xf-yun.com/v1/responses`
8. 本地保存环境变量：`XFYUN_MAAS_API_KEY`
9. 如果使用 `Coding Plan`，默认模型先记录为 `astron-code-latest`，也可以按官方列表切换到底层 `modelId`，例如 `xopglm52`、`xopdeepseekv4pro`、`xopdeepseekv4flash`、`xopkimik26`、`xopqwen36v35b`
10. 导入 `CC Switch` 前，再核对当前套餐版本（如已下架的 `首月版`、按月 / 按季 `焕新版`、企业 / 团队 `Token Plan`）、有效期、剩余额度、支持模型和使用场景限制
11. 若接 `Coding Plan`，确认当前任务属于 Claude Code、OpenCode、Cursor、OpenClaw、Codex 等交互式编程工具场景；不要用于自动化脚本、批量任务或自建后端
12. 若在夜间、周末或节假日错峰使用，按当前文档确认 `0.8` 系数是否仍适用于流控 / 积分消耗

## 人工接管点

- 讯飞登录与认证
- 套餐购买
- 普通推理 / `Token Plan` / `Coding Plan` 路径选择

## 完成后核对

- API Key 是否来自正确的订阅页面
- Base URL 是否与所选套餐一致，没有误用普通 `maas-api`
- `Coding Plan` 是否仍要求使用 `astron-code-latest` 或当前控制台配置的底层模型
- Responses 兼容入口是否只在 `Coding Plan` 路径使用
- 当前套餐版本、有效期和额度是否允许目标工具和目标使用场景，尤其确认 `首月版` 是否仍不可购买、`焕新版` 是否按月 / 按季套餐执行
