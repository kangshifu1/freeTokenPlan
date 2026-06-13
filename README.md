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

## 快速导航

- [中文总览](./README.md)
- [English Overview](./README.en.md)
- [供应商目录索引](#供应商目录索引)
- [标准收录格式](#标准收录格式)
- [如何用-cc-switch-接入](#如何用-cc-switch-接入)
- [如何在-codex-中使用](#如何在-codex-中使用)
- [如何在-claude-code-中使用](#如何在-claude-code-中使用)

面向刚入门的用户，目标是把 2026 年仍可用、适合接入 AI 编程工具的免费额度整理成一份公开索引。

- 更新时间：`2026-06-13`
- 适用对象：想在 `Codex`、`Claude Code`、`CC Switch`、OpenAI 兼容客户端里低成本试用模型的人
- 说明：免费策略变化很快，本文只收录“官方页面能查到”的信息；无法稳定量化的额度会明确标注“以控制台为准”

## 先说结论

如果你只想先跑起来，优先看这 4 个：

1. [Google AI Studio / Gemini API](https://ai.google.dev/gemini-api/docs/pricing)  
   适合零预算长期试用，官方长期保留 Free tier，很多模型有免费档。
2. [OpenRouter](https://openrouter.ai/docs/quickstart)  
   适合“一个账号试很多模型”，并且有大量 `:free` 模型。
3. [Cohere](https://docs.cohere.com/docs/rate-limits)  
   适合轻量测试，官方明确给出试用期速率限制。
4. [DashScope / 阿里云百炼](https://help.aliyun.com/zh/model-studio/model-pricing)  
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
  - 文档明确列出多个模型的免费层，例如 `Gemini 3 Pro`、`Gemini 3 Flash`、`Gemini Embedding`
  - 官方还列出 `Grounding with Google Search` 免费档每天 `500 RPD`
- 使用限制：
  - 免费档按模型区分，不是所有模型都有 Free tier
  - 速率限制、上下文长度、是否启用搜索等都按模型单独计算
  - 免费档数据可能会用于 Google 产品改进，付费档默认不会
  - AI Studio 新建 key 默认更偏向 `auth keys`；官方说明从 `2026-06-19` 开始会拒绝不受限制的 `standard keys`
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
  - 对常见聊天模型，试用 key 的限制是 `1000 API calls/month`、`20 calls/minute`
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

- 官网：[Pricing and Billing](https://huggingface.co/docs/api-inference/pricing)
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
  - [Pricing and Billing](https://huggingface.co/docs/api-inference/pricing)

### 5. Groq

- 官网：[Groq Docs](https://console.groq.com/docs/overview)
- 类型：模型 API
- 注册方式：Groq Console 注册并创建 API Key
- 是否需要信用卡：通常不需要先绑卡即可开始
- 免费内容：
  - 官方定价页写明可以“Get started free”
  - 官方文档提供 OpenAI 兼容接口
- 使用限制：
  - 官方没有在统一页面长期公布一个固定“送多少 token”
  - 官方速率限制文档说明限制按组织级别生效，实际速率和模型权限更适合以控制台 `limits` / `models` 页面为准
  - 免费层适合交互式、低延迟场景，不适合默认认为有大批量免费额度
- 有效期限：持续可用，但具体配额以账号控制台为准
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

- 官网：[Mistral Pricing](https://docs.mistral.ai/getting-started/pricing/)
- 类型：模型 API / 开发工具
- 注册方式：Mistral 平台注册
- 是否需要信用卡：看使用路径；评估阶段通常可先试
- 免费内容：
  - 官方定价页写明 `Mistral Code` 的 `Vibe` 在 `Free` 计划中可用
  - 官方文档仍把免费 / 低门槛试用定位为评估与原型验证用途，具体 API key 与额度状态以 Studio / Console 当前页面为准
- 使用限制：
  - 免费模式适合轻量评估，文档没有长期公开一个统一的“注册送多少 token”数字
  - 更像“提供免费试用模式”，不是大额度长期免费池
- 有效期限：以账户和产品当前策略为准
- OpenAI 兼容：有兼容生态
- Anthropic 兼容：否
- 适合接入：`CC Switch`、代理层、轻量开发测试
- 优惠策略：
  - 先用官方免费模式判断模型风格是否合适
  - 真要做日常 coding 主力，通常需要再配一个稳定免费或低价路由
- 官方文档：
  - [Pricing](https://docs.mistral.ai/getting-started/pricing/)

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
  - 官方页面说明中国内地用户可领取模型免费额度，开通后 `90 天` 内有效，不同模型额度和活动窗口不同
- 使用限制：
  - 强依赖模型、地域、活动阶段
  - 免费额度领取和使用受地域、账号状态、开通时间限制影响
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

`CC Switch` + `OpenRouter` / `Gemini` / `DashScope`

适合原因：

- 一个界面管多个 key
- 可以切模型，不用反复改环境变量
- 对 `Codex`、`Claude Code`、`Gemini CLI` 这类工具更友好

### 路线 B：只想给 Codex 找免费上游

优先顺序建议：

1. `Gemini API`
2. `OpenRouter free models`
3. `Groq`
4. `DashScope`

### 路线 C：中国大陆网络优先

优先顺序建议：

1. `DashScope / 百炼`
2. `SiliconFlow`
3. `OpenRouter`

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
3. `Groq`：适合低延迟交互
4. `Gemini`：更适合通过中间层统一接入

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
│   ├── dashscope/
│   └── siliconflow/
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
- [DashScope / 百炼](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/dashscope/README.md)
- [SiliconFlow](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/siliconflow/README.md)

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
  - [Pricing and Billing](https://huggingface.co/docs/api-inference/pricing)
- Groq
  - [Overview](https://console.groq.com/docs/overview)
  - [OpenAI compatibility](https://console.groq.com/docs/openai)
  - [Rate limits](https://console.groq.com/docs/rate-limits)
  - [Pricing](https://groq.com/pricing/)
- Mistral
  - [Pricing](https://docs.mistral.ai/getting-started/pricing/)
- Cerebras
  - [Introduction](https://inference-docs.cerebras.ai/introduction)
  - [OpenAI SDK](https://inference-docs.cerebras.ai/resources/openai)
  - [Models](https://inference-docs.cerebras.ai/models)
- DashScope / 百炼
  - [Pricing](https://help.aliyun.com/zh/model-studio/model-pricing)
  - [OpenAI Responses compatibility](https://help.aliyun.com/zh/model-studio/openai-responses-api)
  - [Anthropic compatibility](https://help.aliyun.com/zh/model-studio/anthropic-api)
- SiliconFlow
  - [Docs](https://docs.siliconflow.cn/)
  - [Use with Claude Code](https://docs.siliconflow.cn/quickstart/use_with_claude_code)
  - [Use with CC Switch](https://docs.siliconflow.cn/cn/userguide/introduction/use-with-cc-switch)
- Codex
  - [Config](https://developers.openai.com/codex/config)
  - [Advanced config](https://developers.openai.com/codex/config-advanced)
- Claude Code
  - [Overview](https://docs.anthropic.com/en/docs/claude-code/overview)
  - [LLM gateway](https://docs.anthropic.com/en/docs/claude-code/llm-gateway)
- CC Switch
  - [GitHub](https://github.com/farion1231/cc-switch)
  - [README_ZH](https://github.com/farion1231/cc-switch/blob/main/README_ZH.md)
