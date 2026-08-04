# DashScope / 百炼

[中文](./README.md) | [English](./README.en.md)

- 官网：[模型计费与免费额度](https://help.aliyun.com/zh/model-studio/model-pricing)
- 注册：阿里云账号开通百炼
- 免费：首次开通百炼时平台会自动发放各模型新人专属免费额度；官方新人免费额度页主规则当前写明仅华北 `2`（北京）地域模型享有免费额度，其他地域无免费额度；同页 FAQ 后文也提到“仅新加坡地域的模型”，因此必须按具体模型行和控制台剩余额度重新核对
- 有效期：官方当前主规则为 `90 天`；`2025-09-08 11:00` 前已开通用户的有效期可能不足 `90 天`
- 套餐边界：`Token Plan` / `Coding Plan` 专属 API Key 不消耗普通新人免费额度；用新人免费额度测试时应使用普通模型调用 API Key，并按地域和模型行核对
- 风控：已认证用户额度耗尽后可能继续按量扣费，建议在控制台开启“免费额度用完即停”；耗尽后会返回 `AllocationQuota.FreeTierOnly`
- 补充：[新人免费额度说明](https://help.aliyun.com/zh/model-studio/new-free-quota) 用于核对当前领取规则和有效期
- 推荐用途：中国大陆用户接入 `Codex`、`Claude Code`

目录文件：

- [computer-use.md](computer-use.md)
- [cc-switch-template.json](cc-switch-template.json)
