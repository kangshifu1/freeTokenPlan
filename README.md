# AI 免费 Token / 免费额度清单

[![GitHub last commit](https://img.shields.io/github/last-commit/kangshifu1/freeTokenPlan)](https://github.com/kangshifu1/freeTokenPlan/commits/main)
[![GitHub repo size](https://img.shields.io/github/repo-size/kangshifu1/freeTokenPlan)](https://github.com/kangshifu1/freeTokenPlan)
[![Language](https://img.shields.io/badge/language-ZH%20%7C%20EN-blue)](./README.en.md)
[![License](https://img.shields.io/badge/license-MIT-green)](https://opensource.org/licenses/MIT)

[中文](./README.md) | [English](./README.en.md)

面向新手的公开索引仓库，用来整理市面上可用于 AI 工具、AI 编程客户端、代理网关的免费额度、试用配额、注册路径、`CC Switch` 导入模板，以及 `Computer Use` 操作脚本。

## 这个仓库有什么

- 免费额度清单：只收录适合接 `Codex`、`Claude Code`、`CC Switch`、OpenAI 兼容客户端的项目
- 双语文档：中文与英文并列维护
- 供应商目录化：每个供应商单独一个目录，方便维护和分享
- `Computer Use` 脚本：方便 AI 或人工按步骤注册、取 key、录入配置
- `CC Switch` 模板：方便做标准化导入准备

## 顶部清单

| 供应商 | 免费类型 | 适合接入 |
|---|---|---|
| [Gemini](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/gemini/README.md) | 长期 Free tier，按模型限额 | `CC Switch` / OpenAI 兼容代理 |
| [OpenRouter](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/openrouter/README.md) | `:free` 模型，按分钟 / 每日限流 | `Codex` / `CC Switch` |
| [Cohere](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/cohere/README.md) | Trial key 月度调用额度 | 轻量测试 / prompt 验证 |
| [Hugging Face](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/huggingface/README.md) | Inference Providers 月度 credits | API 联调 / demo |
| [Groq](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/groq/README.md) | Free Plan 按模型 RPM/RPD/TPM/TPD 限流 | 低延迟 OpenAI 兼容调用 |
| [Mistral](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/mistral/README.md) | Free 计划 / 评估模式 | 模型风格试用 |
| [Cerebras](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/cerebras/README.md) | 免费 API key 流程，额度看控制台 | 高速推理试用 |
| [NVIDIA NIM](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/nvidia-nim/README.md) | 免费 serverless NIM 开发调用 | OpenAI 风格原型验证 |
| [GitHub Models](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/github-models/README.md) | 免费 playground / API 限额 | GitHub 账号原型测试 |
| [Vercel AI Gateway](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/vercel-ai-gateway/README.md) | 免费档每月 `$5` AI Gateway credits | Vercel / AI SDK 项目 |
| [Cloudflare Workers AI](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/cloudflare-workers-ai/README.md) | 每日 `10,000` Neurons 免费 allocation，按模型消耗核算 | Workers / 边缘 demo |
| [DashScope / 百炼](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/dashscope/README.md) | 新人实时推理免费额度，支持用完即停 | 中国大陆 / `Codex` / `Claude Code` |
| [SiliconFlow](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/siliconflow/README.md) | 实名后免费模型 | 中国区多模型试用 |
| [Agnes AI](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/agnes-ai/README.md) | 官网公开宣传 free API credits / key / tokens / models | 海外多模型 API 原型验证 |
| [百度千帆](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/baidu-qianfan/README.md) | 新用户模型 token 赠送，常见 `100万 Tokens / 3个月` | 国产模型 / OpenAI 兼容 agent |
| [讯飞星辰 MaaS](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/xfyun-maas/README.md) | 模型广场 + `Token Plan` / `Coding Plan` 套餐接入 | 中国大陆编程工具接入 |
| [腾讯混元](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/tencent-hunyuan/README.md) | 首次开通共享 `100万 tokens / 1年` 资源包，迁移至 TokenHub | 混元文本生成 |
| [火山方舟](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/volcengine-ark/README.md) | 免费推理额度 / 活动额度 / Agent Plan | 豆包 / DeepSeek / Coding Plan |

## 快速导航

- [中文总览](./README.md)
- [English Overview](./README.en.md)
- [供应商目录索引](#供应商目录索引)
- [标准收录格式](#标准收录格式)
- [如何用-cc-switch-接入](#如何用-cc-switch-接入)
- [如何在-codex-中使用](#如何在-codex-中使用)
- [如何在-claude-code-中使用](#如何在-claude-code-中使用)

面向刚入门的用户，目标是把 2026 年仍可用、适合接入 AI 编程工具的免费额度整理成一份公开索引。

- 更新时间：`2026-06-26`
- 适用对象：想在 `Codex`、`Claude Code`、`CC Switch`、OpenAI 兼容客户端里低成本试用模型的人
- 说明：免费策略变化很快，本文只收录“官方页面能查到”的信息；无法稳定量化的额度会明确标注“以控制台为准”

## 先说结论

如果你只想先跑起来，优先看这些：

1. [Google AI Studio / Gemini API](https://ai.google.dev/gemini-api/docs/pricing)  
   适合零预算长期试用，官方长期保留 Free tier，很多模型有免费档。
2. [OpenRouter](https://openrouter.ai/docs/quickstart)  
   适合“一个账号试很多模型”，并且有大量 `:free` 模型。
3. [NVIDIA NIM](https://build.nvidia.com/)
   适合试用 NVIDIA 托管模型和 OpenAI 风格 API，官方 Build 页面提供免费开发调用入口。
4. [GitHub Models](https://docs.github.com/en/github-models/use-github-models/prototyping-with-ai-models)
   适合已有 GitHub 账号的原型验证，免费 API 有明确 rate limit。
5. [Cohere](https://docs.cohere.com/docs/rate-limits)
   适合轻量测试，官方明确给出试用期速率限制。
6. [DashScope / 阿里云百炼](https://help.aliyun.com/zh/model-studio/model-pricing)
   适合中国大陆用户，控制台、文档、兼容模式都比较完整。

如果你要把这些额度接入 IDE / agent 工具，优先路线是：

1. `CC Switch` 统一管理供应商和模型
2. `Codex` 走 OpenAI 兼容入口
3. `Claude Code` 走 Anthropic gateway 或 CC Switch 提供的路由

## 标准收录格式

以后新增供应商，建议统一按下面模板收录：

```md
## 名称

- 官网：
- 类型：API / 路由聚合 / 聊天工具 / IDE 工具
- 注册方式：
- 是否需要信用卡：
- 免费内容：
- 使用限制：RPM / RPD / TPM / 模型范围 / 地域限制 / 是否仅测试用途
- 有效期限：长期免费 / 新用户 X 天 / 每月重置 / 以控制台为准
- OpenAI 兼容：
- Anthropic 兼容：
- 适合接入：Codex / Claude Code / CC Switch / OpenCode / 其他
- 优惠策略：
- 官方文档：
- 备注：
```

## 免费额度清单

下面只列“对接 agent / CLI / IDE 工具比较有价值”的项目。

### 1. Google AI Studio / Gemini API

- 官网：[Gemini API Pricing](https://ai.google.dev/gemini-api/docs/pricing)
- 类型：模型 API
- 注册方式：Google 账号登录 AI Studio，创建 API Key
- 是否需要信用卡：通常不需要先绑卡即可试用 Free tier
- 免费内容：
  - 官方长期提供 `Free` 档
  - 文档明确列出多个模型的免费层，当前公开定价示例已推进到 `Gemini 3.5 Flash`、`Gemini 3.5 Live Translate`、`Gemini 3.1`、`Gemini 2.5`、`Gemini Embedding` 等模型
  - `Grounding with Google Search` 免费额度按模型分列；例如部分 `Gemini 2.5 Flash / Flash-Lite` 路径仍显示免费档每天 `500 RPD`，Gemini 3.x 相关行则需要逐模型确认
- 使用限制：
  - 免费档按模型区分，不是所有模型都有 Free tier
  - 速率限制、上下文长度、是否启用搜索等都按模型单独计算
  - 免费档数据可能会用于 Google 产品改进，付费档默认不会
  - AI Studio 新建 key 默认生成 `auth keys`；官方说明自 `2026-06-19` 起已拒绝不受限制的 `standard keys`，受显式限制的 `standard keys` 暂可继续使用，并计划在 `2026-09` 停用所有 `standard keys`
- 有效期限：长期免费档，不是一次性赠金
- OpenAI 兼容：官方提供 OpenAI compatibility 端点；但功能覆盖不等同于完整 OpenAI API
- Anthropic 兼容：否
- 适合接入：`CC Switch`、OpenAI 兼容代理、部分 IDE 网关
- 优惠策略：
  - 新手优先用当前官方 `Flash` 系列，不要默认把 `Pro` 当作高频免费模型
  - 需要 embedding 时优先用官方免费 embedding 档
  - 搜索 grounding 有单独免费额度，适合做轻量检索 demo
- 官方文档：
  - [Pricing](https://ai.google.dev/gemini-api/docs/pricing)
  - [Rate limits](https://ai.google.dev/gemini-api/docs/rate-limits)
  - [API key security](https://ai.google.dev/gemini-api/docs/api-key)
  - [OpenAI compatibility](https://ai.google.dev/gemini-api/docs/openai)

### 2. OpenRouter

- 官网：[OpenRouter Quickstart](https://openrouter.ai/docs/quickstart)
- 类型：模型路由聚合平台
- 注册方式：邮箱 / 第三方账号注册后创建 API Key
- 是否需要信用卡：官方文档写明“免费账户也能拿到 key，且不需要信用卡”
- 免费内容：
  - 官方提供大量 `free` 模型
  - 免费模型在排行榜、模型页、API 中可直接筛选
- 使用限制：
  - 官方文档明确：免费账户默认速率限制为 `20 requests/min`
  - 如果累计购买额度低于 `$10`，免费模型日限额为 `50 requests/day`
  - 如果累计购买额度达到 `$10`，免费模型日限额提升到 `1000 requests/day`
  - 免费模型可用性会因为上游拥堵而波动
- 有效期限：长期可用，但按日 / 分钟限流
- OpenAI 兼容：是
- Anthropic 兼容：部分工具可经由代理转换
- 适合接入：`Codex`、`CC Switch`、OpenAI 兼容客户端
- 优惠策略：
  - 优先挑带 `:free` 后缀的模型
  - 用它做“多模型试吃”最省时间
  - 严格设低并发，避免把每天免费请求数很快打完
- 官方文档：
  - [Quickstart](https://openrouter.ai/docs/quickstart)
  - [Free models](https://openrouter.ai/models?max_price=0)
  - [Rate limits](https://openrouter.ai/docs/api-reference/limits)

### 3. Cohere

- 官网：[Cohere Rate Limits](https://docs.cohere.com/docs/rate-limits)
- 类型：模型 API
- 注册方式：注册 Cohere 账户，创建 trial / production key
- 是否需要信用卡：试用通常不需要先绑卡
- 免费内容：
  - 官方文档明确：`trial keys` 可免费试用
  - 试用 key 以及部分较新的 Chat 模型生产 key 受 `1000 API calls/month` 限制
  - 当前 Chat API 试用限制通常为 `20 req/min`；`Embed` 为 `2,000 inputs/min`，`Rerank` 为 `10 req/min`
  - 模型目录页中也有“free until rate limit reached”描述
- 使用限制：
  - 主要面向评估和开发，不适合直接当高并发生产额度
  - 模型可用性受 key 类型影响
- 有效期限：通常按月限额重置；是否长期保留以官方账号策略为准
- OpenAI 兼容：有兼容生态，但建议走代理或适配层
- Anthropic 兼容：否
- 适合接入：`CC Switch`、OpenAI 兼容代理、轻量脚本
- 优惠策略：
  - 更适合做 prompt 验证和小样测试
  - 把试用额度留给高价值模型验证，不要用于批处理
- 官方文档：
  - [Rate limits](https://docs.cohere.com/docs/rate-limits)
  - [Models overview](https://docs.cohere.com/docs/models)

### 4. Hugging Face Inference Providers

- 官网：[Inference Providers Pricing and Billing](https://huggingface.co/docs/inference-providers/pricing)
- 类型：模型聚合 / 托管推理
- 注册方式：Hugging Face 账号登录
- 是否需要信用卡：免费额度阶段通常不需要
- 免费内容：
  - 官方文档明确：免费用户每月有 `$0.10` credits
  - `PRO` 用户每月有 `$2.00` credits
  - 自托管 endpoint 不在这类免费额度范围内
- 使用限制：
  - 金额不大，只适合 API 联调、样例、页面 demo
  - 按 provider 实际调用结算，热门模型消耗会很快
- 有效期限：每月重置
- OpenAI 兼容：部分 provider / SDK 可兼容
- Anthropic 兼容：否
- 适合接入：脚本测试、模型探索、轻量 demo
- 优惠策略：
  - 用于“验证某模型能否跑通”最划算
  - 不建议把它当主力编程模型源
- 官方文档：
  - [Pricing and Billing](https://huggingface.co/docs/inference-providers/pricing)

### 5. Groq

- 官网：[Groq Docs](https://console.groq.com/docs/overview)
- 类型：模型 API
- 注册方式：Groq Console 注册并创建 API Key
- 是否需要信用卡：通常不需要先绑卡即可开始
- 免费内容：
  - 官方定价页写明可以“Get started free”
  - 官方文档提供 OpenAI 兼容接口
  - 官方 Rate Limits 页面现在直接列出 `Free Plan Limits` 表，按模型给出 `RPM`、`RPD`、`TPM`、`TPD`
- 使用限制：
  - 官方速率限制文档说明限制按组织级别生效，可能先触发请求数或 token 数任一维度
  - 当前免费计划示例：`llama-3.1-8b-instant` 为 `30 RPM` / `14.4K RPD` / `6K TPM` / `500K TPD`
  - 当前免费计划示例：`llama-3.3-70b-versatile` 为 `30 RPM` / `1K RPD` / `12K TPM` / `100K TPD`
  - 当前免费计划示例：`openai/gpt-oss-120b` 和 `openai/gpt-oss-20b` 均为 `30 RPM` / `1K RPD` / `8K TPM` / `200K TPD`
  - 官方说明该表是高层摘要，账号的精确当前限额仍应以控制台 `Limits` 页面为准
  - 免费层适合交互式、低延迟场景，不适合默认认为有大批量免费额度
- 有效期限：持续可用，但模型和配额以官方 Rate Limits / 控制台为准
- OpenAI 兼容：是
- Anthropic 兼容：否
- 适合接入：`Codex`、`CC Switch`、OpenAI 兼容客户端
- 优惠策略：
  - 适合放在“便宜且快”的备用线路
  - 尤其适合命令行问答、短上下文 coding、结构化输出
- 官方文档：
  - [Overview](https://console.groq.com/docs/overview)
  - [OpenAI compatibility](https://console.groq.com/docs/openai)
  - [Rate limits](https://console.groq.com/docs/rate-limits)
  - [Pricing](https://groq.com/pricing/)

### 6. Mistral

- 官网：[Mistral Pricing](https://mistral.ai/pricing)
- 类型：模型 API / 开发工具
- 注册方式：Mistral 平台注册
- 是否需要信用卡：看使用路径；评估阶段通常可先试
- 免费内容：
  - 官方定价页继续列出 `Mistral Free` 计划，并说明包含有限的 `Vibe for code` 能力
  - 官方 tier 文档说明 API `Free mode` 默认启用，带有限 rate limit，面向评估与原型验证
- 使用限制：
  - 免费模式适合轻量评估，文档没有长期公开一个统一的“注册送多少 token”数字
  - 更像“提供免费试用模式”，不是大额度长期免费池
  - 需要更高限额时升级到 `Scale` 计划，随后按累计账单进入更高 usage tier
- 有效期限：以账户和产品当前策略为准
- OpenAI 兼容：有兼容生态
- Anthropic 兼容：否
- 适合接入：`CC Switch`、代理层、轻量开发测试
- 优惠策略：
  - 先用官方免费模式判断模型风格是否合适
  - 真要做日常 coding 主力，通常需要再配一个稳定免费或低价路由
- 官方文档：
  - [Pricing](https://mistral.ai/pricing)

### 7. Cerebras Inference

- 官网：[Cerebras Inference Docs](https://inference-docs.cerebras.ai/introduction)
- 类型：模型 API
- 注册方式：注册后创建 API Key
- 是否需要信用卡：通常可先试用
- 免费内容：
  - 官方文档明确提供“免费 API key”获取流程
  - 官方提供 OpenAI SDK / OpenAI compatible 用法
- 使用限制：
  - 官方没有在统一页面给出固定的长期免费 token 数字
  - 更适合作为“可试用的高速推理入口”，具体额度看控制台
  - 官方模型页当前列出公开生产端点 `gpt-oss-120b`，并标注 `zai-glm-4.7` 为预览模型；默认模型应以模型页为准
- 有效期限：以控制台和活动策略为准
- OpenAI 兼容：是
- Anthropic 兼容：否
- 适合接入：`Codex`、`CC Switch`、OpenAI 兼容客户端
- 优惠策略：
  - 可以当高速候补线路
  - 真正长期项目要先观察限额稳定性
- 官方文档：
  - [Introduction](https://inference-docs.cerebras.ai/introduction)
  - [OpenAI SDK](https://inference-docs.cerebras.ai/resources/openai)
  - [Models](https://inference-docs.cerebras.ai/models)

### 8. DashScope / 阿里云百炼

- 官网：[模型计费与免费额度](https://help.aliyun.com/zh/model-studio/model-pricing)
- 类型：模型 API
- 注册方式：阿里云账号开通百炼
- 是否需要信用卡：不需要信用卡，但可能需要阿里云实名认证 / 账户体系
- 免费内容：
  - 官方文档明确有“新人免费额度”
  - 部分模型在指定地域下有免费时长或免费 token 配额
  - 官方新人免费额度说明写明，首次开通百炼时会自动发放符合条件模型的新人免费额度；当前有效期为 `30～90 天`，且 `2025-09-08 11:00` 起首次开通用户获赠额度有效期调整为 `90 天`
- 使用限制：
  - 免费额度仅适用于华北 `2`（北京）地域、中国内地部署范围的模型实时推理
  - 不抵扣 Batch、模型调优、模型部署或自定义模型费用
  - 免费策略比国际平台更复杂，必须实际看当前模型页和地域说明
- 有效期限：新用户活动期 + 模型 / 地域条件
- OpenAI 兼容：是，官方有 [OpenAI 兼容-Responses](https://help.aliyun.com/zh/model-studio/openai-responses-api) 文档
- Anthropic 兼容：是，官方有 [Anthropic 兼容](https://help.aliyun.com/zh/model-studio/anthropic-api) 文档
- 适合接入：`Codex`、`Claude Code`、`CC Switch`
- 优惠策略：
  - 中国大陆用户优先考虑它，网络和实名体系更顺
  - 先拿新人免费额度练接入，再决定是否转付费
- 官方文档：
  - [Pricing](https://help.aliyun.com/zh/model-studio/model-pricing)
  - [OpenAI Responses compatibility](https://help.aliyun.com/zh/model-studio/openai-responses-api)
  - [Anthropic compatibility](https://help.aliyun.com/zh/model-studio/anthropic-api)

### 9. SiliconFlow

- 官网：[SiliconFlow Docs](https://docs.siliconflow.cn/)
- 类型：模型 API / 聚合平台
- 注册方式：账户注册并创建 API Key
- 是否需要信用卡：通常不需要
- 免费内容：
  - 官方模型广场会对部分模型标注 `免费`
  - 官方文档说明实名认证后可使用免费模型
  - 官方还专门写了 [Claude Code 接入教程](https://docs.siliconflow.cn/quickstart/use_with_claude_code)
- 使用限制：
  - 需要完成平台要求的账号验证 / 实名认证后再确认可用免费模型
  - 免费额度通常按“具体模型是否免费”来定，不是统一全站赠送
  - 哪些模型免费、免费多久，变化会比较快
- 有效期限：以模型页实时标注为准
- OpenAI 兼容：是
- Anthropic 兼容：通过兼容或代理方式可接
- 适合接入：`CC Switch`、`Claude Code`、`Codex`
- 优惠策略：
  - 非常适合中国区用户做多模型试用
  - 先挑免费模型练手，再决定是否充值
- 官方文档：
  - [Docs Home](https://docs.siliconflow.cn/)
  - [Platform Introduction](https://docs.siliconflow.cn/cn/userguide/introduction)
  - [Use with Claude Code](https://docs.siliconflow.cn/quickstart/use_with_claude_code)
  - [Use with CC Switch](https://docs.siliconflow.cn/cn/userguide/introduction/use-with-cc-switch)
  - [Models](https://cloud.siliconflow.cn/models)

### 10. NVIDIA NIM

- 官网：[NVIDIA Build / NIM APIs](https://build.nvidia.com/)
- 类型：模型 API / Serverless NIM
- 注册方式：NVIDIA Developer / build.nvidia.com 账号登录后创建 API Key
- 是否需要信用卡：开发试用入口通常不需要先绑卡，生产使用以 NVIDIA 当前策略为准
- 免费内容：
  - Build 页面提供面向开发和原型验证的免费 serverless NIM API
  - 模型、速率和可用性按账号与模型页实时变化
- 使用限制：
  - 免费路径应视为 development / prototyping，不应当作生产额度
  - 速率限制、并发和模型名单需要在 build.nvidia.com 当前页面确认
- 有效期限：以账号和模型页当前策略为准
- OpenAI 兼容：是，常见 base URL 为 `https://integrate.api.nvidia.com/v1`
- Anthropic 兼容：否
- 适合接入：`Codex`、`CC Switch`、OpenAI 兼容客户端
- 优惠策略：
  - 用来验证 NVIDIA 托管模型和高性能推理体验
  - 导入前从当前模型页复制模型 ID，避免模板里的示例模型过期
- 官方文档：
  - [NVIDIA Build](https://build.nvidia.com/)
  - [NVIDIA NIM](https://developer.nvidia.com/nim)

### 11. GitHub Models

- 官网：[GitHub Models](https://docs.github.com/en/github-models)
- 类型：模型 API / Playground
- 注册方式：GitHub 账号登录后使用 Models playground 或 API
- 是否需要信用卡：免费 API 用量通常不需要先绑卡；付费扩容另行开通
- 免费内容：
  - 官方文档说明 playground 和 API 有免费使用额度
  - 免费 API 按模型 tier 限制 RPM、RPD、tokens/request 和并发请求
  - Copilot Free 下普通 `Low` 模型当前免费 API 限制为 `15 RPM`、`150 RPD`、`8000 input / 4000 output tokens per request`、`5` 并发请求
  - Copilot Free 下 `High` 模型当前免费 API 限制为 `10 RPM`、`50 RPD`、`8000 input / 4000 output tokens per request`、`2` 并发请求
  - Copilot Free 下 `Embedding` 模型当前免费 API 限制为 `15 RPM`、`150 RPD`、`64000 tokens/request`、`5` 并发请求
  - Copilot Free 下 `DeepSeek-R1` / `DeepSeek-R1-0528` / `MAI-DS-R1` 当前限制为 `1 RPM`、`8 RPD`、`4000 input / 4000 output tokens/request`、`1` 并发；`xAI Grok-3` 当前限制为 `1 RPM`、`15 RPD`、`1` 并发
- 使用限制：
  - Low / High / Embedding 以及部分具名模型的 tier 限额不同
  - 生产级更高限额需要开通 paid usage 或自带 provider key
- 有效期限：长期可用，但限额可能调整
- OpenAI 兼容：官方示例可用 OpenAI SDK，base URL 为 `https://models.github.ai/inference`
- Anthropic 兼容：否
- 适合接入：`Codex`、`CC Switch`、OpenAI 兼容客户端
- 优惠策略：
  - 适合 GitHub 用户低成本试模型
  - 先用低成本 / 低 tier 模型做连通性测试
- 官方文档：
  - [Prototyping with AI models](https://docs.github.com/en/github-models/use-github-models/prototyping-with-ai-models)
  - [GitHub Models](https://github.com/marketplace/models)

### 12. Vercel AI Gateway

- 官网：[AI Gateway Pricing](https://vercel.com/docs/ai-gateway/pricing)
- 类型：AI 网关 / 多 provider 路由
- 注册方式：Vercel 账号登录后启用 AI Gateway
- 是否需要信用卡：免费 credits 阶段以 Vercel team / billing 状态为准
- 免费内容：
  - 官方定价页显示每个 team account 的免费档包含 `$5/month` AI Gateway credits
  - credits 从首次 AI Gateway 请求开始；购买 credits 后，月度免费 credits 不再适用
- 使用限制：
  - 更适合 Vercel AI SDK / 项目内代理，而不是直接当通用 OpenAI 兼容供应商
  - 具体 provider、模型、URL 以当前项目配置为准
- 有效期限：按月 credits；购买 credits 后会影响免费规则
- OpenAI 兼容：以当前 AI Gateway 文档和项目配置为准
- Anthropic 兼容：以当前 AI Gateway 文档和项目配置为准
- 适合接入：Vercel 项目、AI SDK、项目内统一网关
- 优惠策略：
  - 适合已有 Vercel 项目的前端 / 全栈 demo
  - 不建议没有 Vercel 项目时优先选择它做 CLI 主力上游
- 官方文档：
  - [AI Gateway](https://vercel.com/docs/ai-gateway)
  - [Pricing](https://vercel.com/docs/ai-gateway/pricing)

### 13. Cloudflare Workers AI

- 官网：[Workers AI Pricing](https://developers.cloudflare.com/workers-ai/platform/pricing/)
- 类型：边缘 AI / 模型 API
- 注册方式：Cloudflare 账号登录后启用 Workers AI
- 是否需要信用卡：免费 allocation 阶段通常不需要先绑卡；Workers 计划状态会影响能力边界
- 免费内容：
  - 官方定价页说明 Workers AI 基于 Neurons 计费，并提供每日 `10,000` Neurons 免费 allocation
  - Cloudflare 当前按模型展示示例成本；文本、图片、音频等模型的输入/输出或推理量会换算为 Neurons
  - 不同模型消耗的 Neurons 不同，同样 `10,000` Neurons 对不同模型代表的请求量不同
  - 超过免费 allocation 后需要 Workers Paid plan
- 使用限制：
  - 更适合 Cloudflare Worker / REST API / 边缘 demo
  - 如果要接通通用 agent 工具，需要确认当前 OpenAI compatible endpoint
- 有效期限：每日 allocation，官方说明在 `00:00 UTC` 重置
- OpenAI 兼容：官方有 OpenAI compatible API endpoints 文档
- Anthropic 兼容：否
- 适合接入：Cloudflare Worker、轻量自动化、边缘侧 demo
- 优惠策略：
  - 适合已经在 Cloudflare 上部署 Worker 的项目
  - 先计算目标模型的 Neurons 消耗并估算请求量，再决定是否纳入日常工具链
- 官方文档：
  - [Pricing](https://developers.cloudflare.com/workers-ai/platform/pricing/)
  - [OpenAI compatible API endpoints](https://developers.cloudflare.com/workers-ai/configuration/open-ai-compatibility/)

### 14. 百度千帆

- 官网：[新用户免费额度](https://cloud.baidu.com/doc/qianfan/s/Imi2rpirg)
- 类型：模型 API / Agent 平台
- 注册方式：百度智能云账号开通千帆，按要求完成实名认证
- 是否需要信用卡：通常不需要信用卡，但需要百度智能云账号与实名体系
- 免费内容：
  - 官方新用户免费额度页说明，`2025年10月24日 0 点起` 首次开通千帆的用户会自动领取适用模型的免费额度
  - 当前页面列出多款模型各 `100万 Tokens`，有效期 `3 个月`，示例包括 `ERNIE-4.5-Turbo` 系列、`DeepSeek-R1`、`DeepSeek-V3.1`、`Kimi-K2-Instruct`、`Qwen3` / `Qwen3-Coder` 系列等
  - 免费额度有效期从用户首次开通千帆之日算起；支持模型、tokens 和活动规则以官方页面为准
- 使用限制：
  - 免费额度只覆盖官方页面列出的模型和服务范围
  - 模型名单、赠送 tokens、有效期和是否仍在活动窗口内受官方页面影响
  - 通过 OpenAI 兼容入口接入时，仍需按当前模型确认名称、上下文和工具能力
- 有效期限：以官方新用户免费额度页面为准
- OpenAI 兼容：是，官方 V2 兼容模式 base URL 为 `https://qianfan.baidubce.com/v2`
- Anthropic 兼容：需按当前文档确认
- 适合接入：中国大陆用户、国产模型试用、轻量 agent
- 优惠策略：
  - 先开通千帆并确认免费额度已自动到账，再选当前免费范围内的模型
  - 需要 CC Switch 时优先记录官方 OpenAI 兼容 base URL，并把默认模型设为当前账号免费额度覆盖的模型
- 官方文档：
  - [New-user free quota](https://cloud.baidu.com/doc/qianfan/s/Imi2rpirg)
  - [OpenAI SDK compatibility](https://cloud.baidu.com/doc/qianfan/s/Hmh4suq26)

### 15. Agnes AI

- 官网：[Agnes AI](https://agnes-ai.com/)
- 类型：AI gateway / 模型 API 平台
- 注册方式：官网注册并进入平台创建 API Key
- 是否需要信用卡：官网首页公开文案未要求绑卡；具体以当前控制台为准
- 免费内容：
  - 官网首页明确宣传 `free AI API credits`
  - 官网首页明确宣传可创建 `free AI API key`
  - 官网首页明确宣传提供 `free AI API tokens` 和 `free AI API models`
- 使用限制：
  - 当前官网公开文案足以确认“有免费 API 入口”，但没有在公开首页稳定列出统一额度数字
  - 具体模型、额度、协议、base URL 和重置规则应以 quick start / dashboard 为准
  - 导入 `CC Switch` 前不应凭首页营销文案猜测完整 OpenAI 兼容细节
- 有效期限：以当前控制台和开发者文档为准
- OpenAI 兼容：待按当前开发者文档复核
- Anthropic 兼容：待按当前开发者文档复核
- 适合接入：海外多模型试用、轻量原型、统一 API gateway 测试
- 优惠策略：
  - 先确认免费 credits 是否已到账，再复制当前免费模型与接口配置
  - 若只看到首页营销文案但未看到开发者接口细节，模板先保留 `check-console`
- 官方文档：
  - [Homepage](https://agnes-ai.com/)
  - [Quick start](https://agnes-ai.com/doc/quick-start)

### 16. 讯飞星辰 MaaS

- 官网：[讯飞星辰 MaaS 模型广场](https://maas.xfyun.cn/modelSquare)
- 类型：模型 API / 模型广场 / 编程工具套餐接入
- 注册方式：讯飞账号登录后进入星辰 MaaS 平台，按页面要求完成认证与套餐开通
- 是否需要信用卡：通常不需要信用卡，但可能需要手机号、实名或企业账号体系
- 免费内容：
  - 模型广场可浏览当前模型与平台能力
  - 当前公开、可稳定复核的编程工具接入文档重点是 `Astron Token Plan` 与 `Astron Coding Plan`
  - `Coding Plan` 页面当前展示 `首月版` 与 `焕新版` 等套餐/活动入口，应按购买页确认当期价格、额度和有效期
  - 这两类文档强调的是套餐接入与兼容协议，不应被误写成“长期全站免费 API”
- 使用限制：
  - `Token Plan` 和 `Coding Plan` 各有独立 API Key 与独立 base URL，不能和常规 `maas-api` 混用
  - `Token Plan` 当前 OpenAI 兼容 base URL 为 `https://maas-token-api.cn-huabei-1.xf-yun.com/v2`，Anthropic 兼容为 `https://maas-token-api.cn-huabei-1.xf-yun.com/anthropic`
  - `Coding Plan` 当前 OpenAI 兼容 base URL 为 `https://maas-coding-api.cn-huabei-1.xf-yun.com/v2`，Anthropic 兼容为 `https://maas-coding-api.cn-huabei-1.xf-yun.com/anthropic`
  - `Coding Plan` 官方当前默认模型标识为 `astron-code-latest`
  - `Coding Plan` 官方文档明确覆盖 Claude Code、OpenCode、Cursor、OpenClaw 等交互式编程工具接入；不要把套餐 API Key 当成普通后端批量调用 key 使用
- 有效期限：以当前套餐、订阅周期和控制台规则为准
- OpenAI 兼容：是
- Anthropic 兼容：是
- 适合接入：中国大陆用户、`Claude Code`、`Cursor`、`OpenCode`、OpenAI / Anthropic 兼容客户端
- 优惠策略：
  - 如果目标是编程工具接入，优先看 `Coding Plan`
  - 如果目标是多模型切换，优先核对 `Token Plan` 当前支持的 `modelId`
  - 导入前先明确自己接的是普通推理、`Token Plan` 还是 `Coding Plan`
- 官方文档：
  - [Model square](https://maas.xfyun.cn/modelSquare)
  - [Token Plan](https://www.xfyun.cn/doc/spark/TokenPlan.html)
  - [Coding Plan](https://www.xfyun.cn/doc/spark/CodingPlan.html)

### 17. 腾讯混元

- 官网：[混元大模型计费概述](https://cloud.tencent.com/document/product/1729/97731)
- 类型：模型 API
- 注册方式：腾讯云账号开通混元，按要求完成实名认证
- 是否需要信用卡：通常不需要信用卡，但需要腾讯云账号与实名体系
- 免费内容：
  - 官方计费页说明混元大模型相关能力将逐步迁移至 `TokenHub`，新增模型服务或更多模型能力应前往 TokenHub 开通
  - 完成实名认证后首次点击“立即使用”会发放免费体验额度
  - 当前混元生文免费额度为一次性共享资源包：列出的混元生文（不含 `Hunyuan-lite`）与混元多模态模型共享 `100万 tokens`，自开通日起 `1 年` 内有效
  - `Hunyuan-embedding` 单独列出 `100万 tokens / 1 年`
- 使用限制：
  - 免费资源包、共享 tokens、有效期、模型范围和 TokenHub 入口以当前文档 / 控制台为准
  - 扣费顺序为“免费资源包 > 付费资源包 > 按量后付费”；资源包耗尽或到期后不会自动转入后付费，需要主动开通
  - 腾讯云 SecretId / SecretKey 可能需要经过兼容网关转换成工具期望的 bearer key
- 有效期限：当前文档列出的生文 / 多模态共享资源包为 `1 年`
- OpenAI 兼容：官方提供兼容文档，导入前需复核 base URL 和模型名
- Anthropic 兼容：否
- 适合接入：中国大陆用户、混元轻量文本生成、OpenAI 兼容客户端
- 优惠策略：
  - 优先用资源包覆盖的模型做连通性测试，不要默认把 `Hunyuan-lite` 计入共享资源包
  - 注意云账号费用保护；如果需要超出资源包继续调用，再主动开通后付费
- 官方文档：
  - [Billing overview](https://cloud.tencent.com/document/product/1729/97731)

### 18. 火山方舟

- 官网：[火山方舟文档](https://www.volcengine.com/docs/82379)
- 类型：模型 API / Agent Plan / Coding Plan
- 注册方式：火山引擎账号开通方舟，按要求完成实名认证
- 是否需要信用卡：以火山引擎账号和活动要求为准
- 免费内容：
  - 官方文档和控制台会展示免费推理额度、安心体验模式和活动额度
  - 具体额度、模型和有效期以当前控制台 / 活动页为准
- 使用限制：
  - 方舟活动和套餐规则变化快，必须以控制台为准
  - 建议启用安心体验模式或明确关闭超额付费风险
- 有效期限：以当前控制台 / 活动页为准
- OpenAI 兼容：方舟文档包含 OpenAI 兼容和多种 AI 工具接入说明
- Anthropic 兼容：以当前工具接入文档为准
- 适合接入：中国大陆用户、豆包 / DeepSeek 等模型、Coding Plan / Agent Plan 工具
- 优惠策略：
  - 先用免费推理额度验证 endpoint 和模型名
  - Coding / Agent 工具接入优先看官方“接入 AI 工具”文档
- 官方文档：
  - [Volcengine Ark docs](https://www.volcengine.com/docs/82379)

## 不要搞混：工具本体和模型供应商不是一回事

很多新手一开始会把这三类东西混在一起：

### 1. Codex

- `Codex` 是工具 / agent，不是免费模型池
- 你仍然需要一个上游模型提供方，或者一个兼容网关
- 官方配置文档见：[Codex config](https://developers.openai.com/codex/config)

### 2. Claude Code

- `Claude Code` 是工具，不是免费 token 供应商
- 它默认更贴近 Anthropic 生态，但也能通过 gateway 接其他上游
- 官方文档见：[Claude Code overview](https://docs.anthropic.com/en/docs/claude-code/overview)

### 3. CC Switch

- `CC Switch` 是“供应商 / 模型 / 路由配置管理器”
- 它本身不送 token，但能显著降低切换成本
- GitHub 项目页：[cc-switch](https://github.com/farion1231/cc-switch)

## 推荐接入方式

### 路线 A：新手最省事

`CC Switch` + `OpenRouter` / `Gemini` / `NVIDIA NIM` / `DashScope`

适合原因：

- 一个界面管多个 key
- 可以切模型，不用反复改环境变量
- 对 `Codex`、`Claude Code`、`Gemini CLI` 这类工具更友好

### 路线 B：只想给 Codex 找免费上游

优先顺序建议：

1. `Gemini API`
2. `OpenRouter free models`
3. `NVIDIA NIM`
4. `GitHub Models`
5. `Groq`
6. `DashScope`

### 路线 C：中国大陆网络优先

优先顺序建议：

1. `DashScope / 百炼`
2. `SiliconFlow`
3. `百度千帆`
4. `腾讯混元`
5. `火山方舟`
6. `OpenRouter`

## 如何用 CC Switch 接入

以下步骤基于 `cc-switch` 官方 README。

### 1. 安装

macOS 可以直接：

```bash
brew install --cask cc-switch
```

也可以去 GitHub Releases 下载：

- 项目主页：[cc-switch](https://github.com/farion1231/cc-switch)
- 中文说明：[README_ZH](https://github.com/farion1231/cc-switch/blob/main/README_ZH.md)

### 2. 添加供应商

在 `CC Switch` 里通常有两种方式：

1. 直接添加内置供应商
2. 通过 `Universal Provider` / 自定义供应商方式接 OpenAI 兼容接口

新手推荐先加：

- `OpenRouter`
- `Gemini`
- `Groq`
- `DashScope`
- `SiliconFlow`
- `NVIDIA NIM`
- `GitHub Models`
- `百度千帆`
- `腾讯混元`
- `火山方舟`

你需要准备的信息通常只有：

- 名称
- `Base URL`
- `API Key`
- 可选的默认模型

### 3. 同步到工具

`CC Switch` 官方文档写明，它可以同步到：

- `Claude Code`
- `Codex`
- `Gemini CLI`
- 其他常见 AI 编程工具

推荐顺序：

1. 先在 `CC Switch` 里把供应商配通
2. 点击同步到目标工具
3. 打开对应工具检查模型是否可见

### 4. 什么时候需要“本地路由”

`cc-switch` 文档里明确提到一种常见场景：

- 如果上游只支持 `Chat Completions`
- 或模型名不是 `gpt-*`
- 或工具要求更严格的 OpenAI Responses 协议

这时就启用 `Needs Local Routing`

新手可以直接理解为：

- 上游接口“不够标准”时，让 `CC Switch` 在本机做一层协议适配
- 对 `Codex` 这种比较挑协议的工具尤其有用

### 5. 常见坑

- 只填了 `API Key`，没填对 `Base URL`
- 供应商支持的是 `chat/completions`，但你直接当 `responses` 用
- 模型名抄错
- 免费额度已经被打完，但你以为是配置错了
- 工具切换后没有重启终端 / 没重新加载配置

## 如何在 Codex 中使用

### 方案 1：优先用 CC Switch

这是最推荐的方式，原因很简单：

- `Codex` 对协议要求比普通聊天工具更高
- 很多第三方虽然号称 OpenAI 兼容，但只兼容到 `chat/completions`
- `CC Switch` 或其他本地代理可以帮你补齐差异

### 方案 2：手动写 Codex provider

OpenAI 官方 `Codex` 文档支持自定义 provider。标准骨架如下：

```toml
model = "your-model"
model_provider = "custom"

[model_providers.custom]
name = "Custom Provider"
base_url = "https://your-gateway.example.com/v1"
env_key = "CUSTOM_PROVIDER_API_KEY"
wire_api = "responses"
```

参考文档：

- [Codex config](https://developers.openai.com/codex/config)
- [Advanced config](https://developers.openai.com/codex/config-advanced)

实操建议：

1. 如果上游官方明确支持 `OpenAI Responses API`，可以直接试手动接入
2. 如果上游只支持 `Chat Completions`，优先走 `CC Switch`、LiteLLM、Moon Bridge 这类适配层
3. 第一次接入先用最便宜或免费的模型验证联通性

### Codex 适合接哪些免费源

优先建议：

1. `DashScope`：因为官方明确给了 `OpenAI Responses` 文档
2. `OpenRouter`：因为免费模型多，但更建议配合适配层
3. `NVIDIA NIM`：适合 OpenAI 风格 chat/completions 原型验证
4. `GitHub Models`：适合已有 GitHub token 的轻量测试
5. `Groq`：适合低延迟交互
6. `Gemini`：更适合通过中间层统一接入

## 如何在 Claude Code 中使用

### 方案 1：优先用 CC Switch

对新手最稳，因为你不需要手动记住各种网关差异。

### 方案 2：手动走 gateway

Anthropic 官方提供 `LLM Gateway` 文档，核心是这两个环境变量：

```bash
export ANTHROPIC_BASE_URL=https://your-gateway.example.com
export ANTHROPIC_AUTH_TOKEN=your-token
```

参考文档：

- [Claude Code LLM gateway](https://docs.anthropic.com/en/docs/claude-code/llm-gateway)

如果你的上游本身提供了 Anthropic 兼容接口，例如：

- `DashScope / 百炼`

就更适合拿来接 `Claude Code`。

## 当前仓库结构

当前仓库建议按“每个供应商一个目录”维护：

```text
.
├── README.md
├── providers/
│   ├── gemini/
│   │   ├── README.md
│   │   ├── computer-use.md
│   │   └── cc-switch-template.json
│   ├── openrouter/
│   ├── cohere/
│   ├── huggingface/
│   ├── groq/
│   ├── mistral/
│   ├── cerebras/
│   ├── nvidia-nim/
│   ├── github-models/
│   ├── vercel-ai-gateway/
│   ├── cloudflare-workers-ai/
│   ├── dashscope/
│   ├── siliconflow/
│   ├── baidu-qianfan/
│   ├── tencent-hunyuan/
│   └── volcengine-ark/
└── templates/
    ├── provider-template.md
    └── cc-switch-template.json
```

这样做的好处：

- `README` 只放总览
- 每个供应商目录都能独立给小白使用
- `computer-use.md` 适合 AI / 人照着点网页执行
- `cc-switch-template.json` 适合后续导入或二次转换

## 供应商目录索引

- [Gemini](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/gemini/README.md)
- [OpenRouter](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/openrouter/README.md)
- [Cohere](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/cohere/README.md)
- [Hugging Face](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/huggingface/README.md)
- [Groq](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/groq/README.md)
- [Mistral](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/mistral/README.md)
- [Cerebras](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/cerebras/README.md)
- [NVIDIA NIM](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/nvidia-nim/README.md)
- [GitHub Models](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/github-models/README.md)
- [Vercel AI Gateway](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/vercel-ai-gateway/README.md)
- [Cloudflare Workers AI](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/cloudflare-workers-ai/README.md)
- [DashScope / 百炼](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/dashscope/README.md)
- [SiliconFlow](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/siliconflow/README.md)
- [Agnes AI](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/agnes-ai/README.md)
- [百度千帆](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/baidu-qianfan/README.md)
- [讯飞星辰 MaaS](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/xfyun-maas/README.md)
- [腾讯混元](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/tencent-hunyuan/README.md)
- [火山方舟](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/volcengine-ark/README.md)

## 维护建议

这个仓库最容易过期的地方有 4 个：

1. 免费额度数字
2. 免费模型名单
3. 是否需要绑卡
4. Codex / Claude Code / CC Switch 的配置方式

建议维护规则：

- 每次更新都写上日期
- 只引用官方文档或官方控制台说明
- 对“控制台实时变化”的项目明确写“以控制台为准”
- 不要把第三方博客当一手依据

## 参考链接

- Google Gemini API
  - [Pricing](https://ai.google.dev/gemini-api/docs/pricing)
  - [Rate limits](https://ai.google.dev/gemini-api/docs/rate-limits)
  - [API key security](https://ai.google.dev/gemini-api/docs/api-key)
  - [OpenAI compatibility](https://ai.google.dev/gemini-api/docs/openai)
- OpenRouter
  - [Quickstart](https://openrouter.ai/docs/quickstart)
  - [Rate limits](https://openrouter.ai/docs/api-reference/limits)
  - [Free models](https://openrouter.ai/models?max_price=0)
- Cohere
  - [Rate limits](https://docs.cohere.com/docs/rate-limits)
  - [Models](https://docs.cohere.com/docs/models)
- Hugging Face
  - [Pricing and Billing](https://huggingface.co/docs/inference-providers/pricing)
- Groq
  - [Overview](https://console.groq.com/docs/overview)
  - [OpenAI compatibility](https://console.groq.com/docs/openai)
  - [Rate limits](https://console.groq.com/docs/rate-limits)
  - [Pricing](https://groq.com/pricing/)
- Mistral
  - [Pricing](https://mistral.ai/pricing)
- Cerebras
  - [Introduction](https://inference-docs.cerebras.ai/introduction)
  - [OpenAI SDK](https://inference-docs.cerebras.ai/resources/openai)
  - [Models](https://inference-docs.cerebras.ai/models)
- DashScope / 百炼
  - [Pricing](https://help.aliyun.com/zh/model-studio/model-pricing)
  - [New-user free quota](https://help.aliyun.com/zh/model-studio/new-free-quota)
  - [OpenAI Responses compatibility](https://help.aliyun.com/zh/model-studio/openai-responses-api)
  - [Anthropic compatibility](https://help.aliyun.com/zh/model-studio/anthropic-api)
- SiliconFlow
  - [Docs](https://docs.siliconflow.cn/)
  - [Use with Claude Code](https://docs.siliconflow.cn/quickstart/use_with_claude_code)
  - [Use with CC Switch](https://docs.siliconflow.cn/cn/userguide/introduction/use-with-cc-switch)
- Agnes AI
  - [Homepage](https://agnes-ai.com/)
  - [Quick start](https://agnes-ai.com/doc/quick-start)
- NVIDIA NIM
  - [NVIDIA Build](https://build.nvidia.com/)
  - [NVIDIA NIM](https://developer.nvidia.com/nim)
- GitHub Models
  - [Prototyping with AI models](https://docs.github.com/en/github-models/use-github-models/prototyping-with-ai-models)
  - [GitHub Models marketplace](https://github.com/marketplace/models)
- Vercel AI Gateway
  - [AI Gateway](https://vercel.com/docs/ai-gateway)
  - [Pricing](https://vercel.com/docs/ai-gateway/pricing)
- Cloudflare Workers AI
  - [Pricing](https://developers.cloudflare.com/workers-ai/platform/pricing/)
  - [OpenAI compatible API endpoints](https://developers.cloudflare.com/workers-ai/configuration/open-ai-compatibility/)
- 百度千帆
  - [New-user free quota](https://cloud.baidu.com/doc/qianfan/s/Imi2rpirg)
  - [OpenAI SDK compatibility](https://cloud.baidu.com/doc/qianfan/s/Hmh4suq26)
- 讯飞星辰 MaaS
  - [Model square](https://maas.xfyun.cn/modelSquare)
  - [Token Plan](https://www.xfyun.cn/doc/spark/TokenPlan.html)
  - [Coding Plan](https://www.xfyun.cn/doc/spark/CodingPlan.html)
- 腾讯混元
  - [Billing overview](https://cloud.tencent.com/document/product/1729/97731)
- 火山方舟
  - [Docs](https://www.volcengine.com/docs/82379)
- Codex
  - [Config](https://developers.openai.com/codex/config)
  - [Advanced config](https://developers.openai.com/codex/config-advanced)
- Claude Code
  - [Overview](https://docs.anthropic.com/en/docs/claude-code/overview)
  - [LLM gateway](https://docs.anthropic.com/en/docs/claude-code/llm-gateway)
- CC Switch
  - [GitHub](https://github.com/farion1231/cc-switch)
  - [README_ZH](https://github.com/farion1231/cc-switch/blob/main/README_ZH.md)
