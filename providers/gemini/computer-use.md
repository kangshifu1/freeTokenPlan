# Gemini Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

适用对象：让 AI 助手或人工操作员按步骤完成注册、创建 key、填入 CC Switch。

## 目标

1. 登录 Google 账号
2. 打开 AI Studio
3. 创建 API Key
4. 记录 key 和建议模型
5. 填写到 `cc-switch-template.json`

## 前置条件

- 已准备可登录的 Google 账号
- 能接收短信或邮箱验证
- 如果遇到风控，人工接管验证码步骤

## 操作脚本

1. 打开 [https://aistudio.google.com/](https://aistudio.google.com/)
2. 如果未登录，点击 `Sign in`
3. 完成 Google 登录和可能出现的二次验证
4. 进入 AI Studio 后，打开 `Get API key` 或 `API keys`
5. 点击 `Create API key`
6. 若页面要求选择 project，优先创建 / 使用受限制的 `auth key`；避免使用不受限制的 `standard key`
7. 生成后立即复制 key
8. 本地保存为环境变量名：`GEMINI_API_KEY`
9. 建议默认模型记录为：
   - `gemini-2.5-flash`
   - `gemini-2.5-flash-lite`
10. 把 key 填入 CC Switch；如走 Gemini 官方 OpenAI compatibility，可记录官方兼容端点；如果下游要求完整 Responses API，仍建议先经兼容代理验证

## 人工接管点

- Google 登录验证码
- 账号安全验证
- 地区限制或浏览器风险校验

## 完成后核对

- 是否成功拿到 API key
- 是否记录了创建日期
- 是否确认了当前 Free tier 模型
- 是否确认 key 类型不是不受限制的 `standard key`
