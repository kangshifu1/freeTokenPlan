# Hugging Face Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## 操作脚本

1. 打开 [https://huggingface.co/join](https://huggingface.co/join)
2. 注册或登录
3. 完成邮箱验证
4. 进入 [Access Tokens](https://huggingface.co/settings/tokens)
5. 创建一个新 token
6. 复制 token
7. 本地保存为环境变量：`HF_TOKEN`
8. 打开推理 provider 文档，确认准备接哪个 provider
9. 如果要接入 CC Switch，建议通过统一网关先转换为 OpenAI 兼容接口

## 人工接管点

- 邮箱验证
- 访问令牌权限选择

## 完成后核对

- token 权限是否过大
- 本月剩余额度是否需要记录
