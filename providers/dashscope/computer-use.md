# DashScope Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

核验日期：`2026-11-24`

## 操作脚本

1. 打开 [https://dashscope.console.aliyun.com/](https://dashscope.console.aliyun.com/)
2. 使用阿里云账号登录
3. 首次使用前完成实名认证；使用阿里云主账号或拥有 `AliyunBailianFullAccess` 权限的 RAM 账号登录，系统会自动开通百炼
4. 阅读 [新人免费额度说明](https://help.aliyun.com/zh/model-studio/new-free-quota)，确认免费额度已发放；未完成实名认证不发放免费额度
5. 打开 API Key 管理页
6. 创建 API Key
7. 复制 key
8. 本地保存为环境变量：`DASHSCOPE_API_KEY`
9. 查看当前免费模型、新人免费额度、`90 天` 主有效期，以及华北 `2`（北京）主路径；必要时打开 [新人免费额度说明](https://help.aliyun.com/zh/model-studio/new-free-quota) 和价格表，按目标模型行复核是否存在新加坡地域模型免费额度
10. 如果看到 `Token Plan` / `Coding Plan` 专属 API Key，不要用它判断普通新人免费额度；免费额度验证应使用普通模型调用 API Key
11. 首次调用前，在免费额度页为目标模型开启“免费额度用完即停”（默认关闭）；等待配置生效后再调用，避免额度耗尽后自动按量扣费
12. 在 CC Switch 中按需要录入：
   - OpenAI 兼容入口
   - Anthropic 兼容入口
   - 默认模型

## 人工接管点

- 阿里云登录
- 实名认证（开通及领取免费额度前必需）；充值确认（继续付费调用时）
- 安全短信验证

## 完成后核对

- 免费活动是否仍有效
- 当前账号是否符合中国内地新人免费额度领取条件
- 当前地域、部署范围和模型是否匹配
- 使用的是普通模型调用 API Key，还是单独的 `Token Plan` / `Coding Plan` key
- 是否已开启免费额度用完即停，或明确接受超额扣费风险
- 是否需要单独记录 OpenAI / Anthropic 兼容地址
