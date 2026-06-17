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
8. 打开 [新用户免费额度](https://cloud.baidu.com/doc/qianfan/s/Imi2rpirg)，确认免费额度是否已自动到账，并记录当前账号覆盖的模型、tokens 和有效期
9. 如果要接入 CC Switch，打开 [OpenAI SDK 兼容说明](https://cloud.baidu.com/doc/qianfan/s/Hmh4suq26)，记录 base URL：`https://qianfan.baidubce.com/v2`
10. 将默认模型设置为当前账号免费额度覆盖的模型；如工具需要 Anthropic 协议，再确认是否需要本地代理转换

## 人工接管点

- 百度智能云登录
- 实名认证 / 企业认证
- 短信或邮箱安全验证

## 完成后核对

- 免费额度是否已领取
- 有效期是否记录为当前页面显示值
- 默认模型是否在当前账号免费额度范围内
- OpenAI 兼容 base URL 是否记录为官方当前文档值
