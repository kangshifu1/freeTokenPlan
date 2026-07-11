# 腾讯混元 Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## 操作脚本

1. 打开 [腾讯云控制台](https://console.cloud.tencent.com/)
2. 登录腾讯云账号
3. 搜索并进入混元大模型；若页面引导到 `TokenHub`，改从 TokenHub 继续
4. 若未开通，按页面提示开通混元生文服务或 TokenHub 对应模型服务
5. 完成实名认证、安全验证或服务授权
6. 创建 API key / SecretId / SecretKey
7. 本地保存为环境变量：`TENCENT_SECRET_ID`、`TENCENT_SECRET_KEY`
8. 打开 [混元计费概述](https://cloud.tencent.com/document/product/1729/97731)，确认当前入口是否已迁移到 `TokenHub`，新增能力是否需要在 TokenHub 开通
9. 记录免费资源包、共享模型范围、有效期、入口来源，以及 `Hunyuan-lite` 是否被排除在共享资源包外
10. 检查控制台后付费设置，确认免费/付费资源包耗尽后是否会转入后付费
11. 若使用 OpenAI 兼容模式，打开官方兼容文档复核 base URL 和模型名

## 人工接管点

- 腾讯云登录
- 实名认证
- 短信 / 微信 / 邮箱安全验证

## 完成后核对

- 免费资源包是否已发放
- 有效期是否与控制台一致
- 当前模型是否在共享资源包范围内，或是否需要在 `TokenHub` 另行开通 / 使用独立鉴权
- 资源包耗尽或到期后是否保持不会自动后付费
- OpenAI 兼容配置是否来自官方当前文档
