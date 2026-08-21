# Cohere

[中文](./README.md) | [English](./README.en.md)

- 官网：[Cohere Rate Limits](https://docs.cohere.com/docs/rate-limits)
- 注册：Cohere 账号注册后创建试用 key
- 免费：试用 key 可免费试用；官方文档说明试用 key 以及部分较新的 Chat 模型生产 key 受 `1000 API calls/month` 限制
- 限制：当前 Chat API 试用限制通常为 `20 req/min`；`Embed` 为 `2,000 inputs/min`，`Rerank` 为 `10 req/min`；模型文档当前把 `Command A`、`North Mini`、`Command R+`、`Command R` 等可聊天模型标为 “Try for free with rate limits”，其中 `Command A` 与 `North Mini` 还标注为 `fast`
- 用途边界：Cohere pricing 明确试用 key 不允许用于生产或商业用途
- 推荐用途：评估、轻量 prompt 测试
- 参考：[Model docs](https://docs.cohere.com/docs/models)

目录文件：

- [computer-use.md](computer-use.md)
- [cc-switch-template.json](cc-switch-template.json)
