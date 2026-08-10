# 百度千帆 Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## 操作脚本

1. 打开 [百度千帆控制台](https://console.bce.baidu.com/qianfan/)
2. 使用百度智能云账号登录
3. 若未开通千帆，按页面提示开通
4. 完成实名认证或企业认证要求
5. 打开 API Key / 安全认证相关页面
6. 创建并复制 API key / secret
7. 本地保存为环境变量：`QIANFAN_API_KEY`，如页面要求也保存 `QIANFAN_SECRET_KEY`
8. 打开 [新用户免费额度](https://cloud.baidu.com/doc/qianfan/s/Imi2rpirg)，确认免费额度是否已自动到账，并记录当前账号覆盖的模型、tokens 和有效期；当前官方页示例覆盖 `ERNIE-4.5-Turbo`、`DeepSeek`、`Kimi`、`Qwen3` / `Qwen3-Coder` 等模型，但实际可用名单以账号页面为准
9. 如果要使用普通模型服务接入 CC Switch 或 OpenAI 兼容客户端，打开 [OpenAI SDK 兼容说明](https://cloud.baidu.com/doc/qianfan/s/Hmh4suq26)，记录普通模型服务 base URL：`https://qianfan.baidubce.com/v2`
10. 如果目标是编程工具套餐，打开 [Token Plan 个人版](https://cloud.baidu.com/doc/qianfan/s/Dmrabu8b6) 和 [快速开始](https://cloud.baidu.com/doc/qianfan/s/kmracfgi2)，确认是否购买 / 迁移 `Token Plan`，并从“我的订阅”获取 `Token Plan 个人版`专用 API Key
11. 记录 `Token Plan 个人版`专用 base URL：OpenAI 为 `https://qianfan.baidubce.com/v2/tokenplan/personal`，Anthropic 为 `https://qianfan.baidubce.com/anthropic/tokenplan/personal`
12. 如用 `CC-Switch` 连接 Claude Code，打开 [Token Plan 个人版 CC-Switch 指南](https://cloud.baidu.com/doc/qianfan/s/Tmrad8foj)，按官方 JSON 使用 `ANTHROPIC_AUTH_TOKEN`、`ANTHROPIC_BASE_URL` 和当前支持模型；不要把普通千帆 key 与 Token Plan 专用 key 混用
13. 将默认模型设置为当前账号免费额度或 Token Plan 套餐覆盖的模型；普通新用户免费额度、`Token Plan 个人版`、存量 `Coding Plan` 的额度和 base URL 要分开记录

## 人工接管点

- 百度智能云登录
- 实名认证 / 企业认证
- 短信或邮箱安全验证
- Token Plan 订阅购买、迁移或自动续费确认

## 完成后核对

- 免费额度是否已领取
- 有效期是否记录为当前页面显示值
- 默认模型是否在当前账号免费额度范围内
- OpenAI 兼容 base URL 是否记录为官方当前文档值
- 如使用 Token Plan，是否记录了专用 API Key、OpenAI / Anthropic 专用 base URL、套餐有效期和可用模型
