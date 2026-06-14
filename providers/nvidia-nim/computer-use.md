# NVIDIA NIM Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## 操作脚本

1. 打开 [https://build.nvidia.com/](https://build.nvidia.com/)
2. 使用 NVIDIA Developer 账号登录；没有账号则先注册
3. 打开目标模型页，确认该模型当前是否显示可用 API / 免费开发调用
4. 点击页面里的 `Get API Key`、`Build with this model` 或类似入口
5. 生成并复制 API key
6. 本地保存为环境变量：`NVIDIA_API_KEY`
7. 记录当前模型 ID、调用端点和页面显示的速率限制
8. 如果接入 CC Switch，优先按 OpenAI compatible provider 录入：
   - Base URL：`https://integrate.api.nvidia.com/v1`
   - API Key：刚复制的 key
   - 默认模型：导入前从当前模型页复制

## 人工接管点

- NVIDIA 账号登录 / 邮箱验证
- 组织或开发者条款确认
- 模型页的地区、速率或可用性提示

## 完成后核对

- API key 是否创建成功
- 当前模型是否仍提供免费开发调用
- 是否记录了账号页或模型页显示的 rate limit
- 是否明确区分开发原型免费调用和生产使用
