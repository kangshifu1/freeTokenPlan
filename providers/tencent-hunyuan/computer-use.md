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
8. 打开 [混元计费概述](https://cloud.tencent.com/document/product/1729/97731) 和 [TokenHub 新用户体验包](https://cloud.tencent.com/document/product/1823/130053)，确认当前入口是否已迁移到 `TokenHub`，新增能力是否需要在 TokenHub 开通
9. 记录当前领取的是 TokenHub 新用户体验包还是混元存量资源包；TokenHub 语言模型和多模态理解体验包当前为 `100万 tokens / 90 天`，图片 / 视频 / 3D 生成体验包按次数或积分计量，混元生文 / 多模态共享资源包当前为 `100万 tokens / 1 年`
10. 记录免费资源包、共享模型范围、有效期、入口来源、计量口径，以及 `Hunyuan-lite` 是否被排除在共享资源包外
11. 检查控制台后付费设置，确认免费/付费资源包耗尽后是否会转入后付费
12. 若使用 OpenAI 兼容模式，打开官方兼容文档复核 base URL 和模型名

## 人工接管点

- 腾讯云登录
- 实名认证
- 短信 / 微信 / 邮箱安全验证

## 完成后核对

- 免费资源包是否已发放
- 有效期是否与控制台一致
- 当前模型是否在对应入口的资源包范围内，或是否需要在 `TokenHub` 另行开通 / 使用独立鉴权
- TokenHub 各类体验包和混元存量资源包的入口、有效期、模型范围、计量口径没有混记
- 资源包耗尽或到期后是否保持不会自动后付费
- OpenAI 兼容配置是否来自官方当前文档
