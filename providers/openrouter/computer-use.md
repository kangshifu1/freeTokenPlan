# OpenRouter Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## 目标

1. 注册 OpenRouter
2. 创建 API Key
3. 找到免费模型
4. 导入 CC Switch

## 操作脚本

1. 打开 [https://openrouter.ai/](https://openrouter.ai/)
2. 点击 `Sign In`
3. 使用邮箱或第三方账号完成登录
4. 进入 [Keys 页面](https://openrouter.ai/keys)
5. 点击 `Create Key`
6. 给 key 起名，例如 `cc-switch-test`
7. 复制生成的 key
8. 本地保存为环境变量名：`OPENROUTER_API_KEY`
9. 打开模型页，筛选 `free`
10. 记录 1 到 3 个当前可用免费模型
11. 在 CC Switch 新增供应商：
   - 名称：`OpenRouter`
   - Base URL：`https://openrouter.ai/api/v1`
   - API Key：填刚复制的 key
   - 默认模型：填一个 `:free` 模型

## 人工接管点

- 邮箱验证
- 如果账号触发异常登录校验

## 完成后核对

- `Key` 是否可见
- 默认模型是否仍为 `free`
- 每日 / 每分钟限制是否需要单独备注
