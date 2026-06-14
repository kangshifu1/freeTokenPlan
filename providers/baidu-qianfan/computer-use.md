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
8. 打开 [新用户免费额度](https://cloud.baidu.com/doc/qianfan/s/Imi2rpirg)，记录当前账号可领取模型、tokens 和有效期
9. 如果要接入 CC Switch，先确认当前模型是否有 OpenAI 兼容入口或需要本地代理转换

## 人工接管点

- 百度智能云登录
- 实名认证 / 企业认证
- 短信或邮箱安全验证

## 完成后核对

- 免费额度是否已领取
- 有效期是否记录为当前页面显示值
- 默认模型是否在当前账号免费额度范围内
- 兼容入口是否来自官方当前文档
