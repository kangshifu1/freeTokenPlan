# Free AI Token and Free Tier Catalog

[![GitHub last commit](https://img.shields.io/github/last-commit/kangshifu1/freeTokenPlan)](https://github.com/kangshifu1/freeTokenPlan/commits/main)
[![GitHub repo size](https://img.shields.io/github/repo-size/kangshifu1/freeTokenPlan)](https://github.com/kangshifu1/freeTokenPlan)
[![Language](https://img.shields.io/badge/language-ZH%20%7C%20EN-blue)](./README.md)
[![License](https://img.shields.io/badge/license-MIT-green)](https://opensource.org/licenses/MIT)

[中文](./README.md) | [English](./README.en.md)

This is a public repository for beginners who want a practical index of free AI tokens, free tiers, trial quotas, registration flows, `CC Switch` import-prep templates, and `Computer Use` operator scripts for AI coding tools and compatible gateways.

## What This Repo Includes

- Free-tier catalog: focused on providers useful for `Codex`, `Claude Code`, `CC Switch`, and OpenAI-compatible clients
- Bilingual docs: Chinese and English maintained side by side
- One directory per provider: easier to maintain and share
- `Computer Use` scripts: step-by-step operator flow for sign-up, key creation, and setup
- `CC Switch` templates: normalized provider records for import preparation

## Provider List

| Provider | Free type | Best fit |
|---|---|---|
| [Gemini](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/gemini/README.en.md) | Long-term model-dependent Free tier | `CC Switch` / OpenAI-compatible gateway |
| [OpenRouter](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/openrouter/README.en.md) | `:free` models with minute / daily limits | `Codex` / `CC Switch` |
| [Cohere](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/cohere/README.en.md) | Trial-key monthly call quota | Lightweight tests / prompt validation |
| [Hugging Face](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/huggingface/README.en.md) | Monthly Inference Providers credits | API checks / demos |
| [Groq](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/groq/README.en.md) | Free start, console-defined limits | Low-latency OpenAI-compatible calls |
| [Mistral](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/mistral/README.en.md) | Free plan / evaluation mode | Model-style testing |
| [Cerebras](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/cerebras/README.en.md) | Free API-key flow, console-defined limits | High-speed inference trials |
| [NVIDIA NIM](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/nvidia-nim/README.en.md) | Free serverless NIM development calls | OpenAI-style prototypes |
| [GitHub Models](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/github-models/README.en.md) | Free playground / API limits | GitHub-account prototypes |
| [Vercel AI Gateway](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/vercel-ai-gateway/README.en.md) | Free-tier `$5/month` AI Gateway credits | Vercel / AI SDK projects |
| [Cloudflare Workers AI](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/cloudflare-workers-ai/README.en.md) | Daily `10,000` Neurons free allocation | Workers / edge demos |
| [DashScope / Bailian](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/dashscope/README.en.md) | New-user realtime inference quota with stop-after-free control | Mainland China / `Codex` / `Claude Code` |
| [SiliconFlow](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/siliconflow/README.en.md) | Free models after verification | China-region multi-model trials |
| [Baidu Qianfan](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/baidu-qianfan/README.en.md) | New-user model token grants, commonly `1M tokens / 3 months` | Domestic models / OpenAI-compatible agents |
| [Tencent Hunyuan](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/tencent-hunyuan/README.en.md) | First-activation package / `Hunyuan-lite` | Hunyuan text generation |
| [Volcengine Ark](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/volcengine-ark/README.en.md) | Free inference / campaign quota / Agent Plan | Doubao / DeepSeek / Coding Plan |

## Quick Navigation

- [Chinese Overview](./README.md)
- [English Overview](./README.en.md)
- [Provider Index](#provider-index)
- [Repository Structure](#repository-structure)
- [About the CC Switch Templates](#about-the-cc-switch-templates)
- [Official References](#official-references)

This repository is a public starter guide for beginners who want to try AI tools with free or low-cost quotas and connect them to coding agents such as `Codex`, `Claude Code`, and `CC Switch`.

- Updated: `2026-06-17`
- Audience: beginners, indie builders, AI tool users
- Scope: only official or first-party-documented free tiers, trial quotas, and compatibility notes
- Warning: free-tier policies change often; account dashboards always win over this repo

## Quick Start

If you just want to get started fast, start with:

1. [Google Gemini API](https://ai.google.dev/gemini-api/docs/pricing)
2. [OpenRouter](https://openrouter.ai/docs/quickstart)
3. [NVIDIA NIM](https://build.nvidia.com/)
4. [GitHub Models](https://docs.github.com/en/github-models/use-github-models/prototyping-with-ai-models)
5. [Cohere](https://docs.cohere.com/docs/rate-limits)
6. [DashScope / Alibaba Cloud Bailian](https://help.aliyun.com/zh/model-studio/model-pricing)

Recommended tool path:

1. Use `CC Switch` to manage providers and models
2. Connect `Codex` through an OpenAI-compatible route
3. Connect `Claude Code` through an Anthropic-compatible gateway or a compatible route

## Repository Structure

Each provider has its own directory with:

- `README.md`: Chinese summary
- `README.en.md`: English summary
- `computer-use.md`: Chinese operator script
- `computer-use.en.md`: English operator script
- `cc-switch-template.json`: repo-defined import-prep template for `CC Switch`

```text
.
├── README.md
├── README.en.md
├── providers/
│   ├── gemini/
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
```

## Provider Index

- [Gemini](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/gemini/README.en.md)
- [OpenRouter](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/openrouter/README.en.md)
- [Cohere](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/cohere/README.en.md)
- [Hugging Face](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/huggingface/README.en.md)
- [Groq](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/groq/README.en.md)
- [Mistral](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/mistral/README.en.md)
- [Cerebras](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/cerebras/README.en.md)
- [NVIDIA NIM](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/nvidia-nim/README.en.md)
- [GitHub Models](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/github-models/README.en.md)
- [Vercel AI Gateway](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/vercel-ai-gateway/README.en.md)
- [Cloudflare Workers AI](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/cloudflare-workers-ai/README.en.md)
- [DashScope / Bailian](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/dashscope/README.en.md)
- [SiliconFlow](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/siliconflow/README.en.md)
- [Baidu Qianfan](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/baidu-qianfan/README.en.md)
- [Tencent Hunyuan](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/tencent-hunyuan/README.en.md)
- [Volcengine Ark](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/volcengine-ark/README.en.md)

## Current Provider Notes

- Gemini: the Free tier remains model-dependent, with current public pricing examples now led by Gemini 3.5 models. AI Studio now steers new keys toward `auth keys`, and Google documents that unrestricted `standard keys` will be rejected from `2026-06-19`, with all `standard keys` planned for shutdown in `2026-09`. Gemini also has an official OpenAI compatibility endpoint, but it is not a full OpenAI API replacement.
- OpenRouter: free accounts can still create keys without a credit card and use `:free` models, subject to the published per-minute and daily free-model limits.
- Cohere: trial keys remain the correct free testing path, with a documented `1,000 API calls/month` cap and per-endpoint limits such as `20 req/min` for current Chat models, `2,000 inputs/min` for Embed, and `10 req/min` for Rerank.
- Hugging Face: Inference Providers still use small monthly credits for free accounts, and the official pricing docs now live under the Inference Providers docs, so this is best treated as a smoke-test or demo route.
- Groq: official docs provide OpenAI-compatible access, but current quota and model availability should be checked on the organization-level limits page in the console.
- Mistral: the public pricing page still lists Mistral Free with limited Vibe for code access, and the tier docs say API Free mode is enabled by default with limited limits for evaluation and prototyping.
- Cerebras: the docs still show a free API-key flow and OpenAI SDK usage; the current public production endpoint is `gpt-oss-120b`, with `zai-glm-4.7` marked as preview on the models page.
- NVIDIA NIM: NVIDIA Build exposes free serverless NIM APIs for development and prototyping, with OpenAI-style chat completions at `https://integrate.api.nvidia.com/v1`; production capacity and limits are account/model-page dependent.
- GitHub Models: free playground and API usage are available with model-tier-specific limits. Under Copilot Free, current free API limits are `15 RPM / 150 RPD / 5 concurrent` for Low models, `10 RPM / 50 RPD / 2 concurrent` for High models, and `15 RPM / 150 RPD / 5 concurrent` for Embedding models, with per-request token caps published in the GitHub docs.
- Vercel AI Gateway: team accounts get a free tier with `$5/month` AI Gateway credits. Credits start on the first AI Gateway request, and the monthly free credit no longer applies after purchasing credits; treat it as a project gateway rather than a generic provider.
- Cloudflare Workers AI: Workers AI includes a free daily allocation of `10,000` Neurons, resetting daily at `00:00 UTC`. Cloudflare also documents OpenAI-compatible endpoints; model Neurons cost should be checked first.
- DashScope / Bailian: free quota is regional and activity-based. The official pricing page says mainland China users can claim model free quotas that are valid for `90 days` after activation, with model-specific quota details.
- SiliconFlow: official docs say free models are available after real-name verification; the docs also include Claude Code and CC Switch integration guides.
- Baidu Qianfan: official new-user free-quota docs now say first-time Qianfan activations after `2025-10-24 00:00:00` automatically receive eligible model quotas. The current page lists multiple models at `1M tokens` valid for `3 months`, and Baidu documents an OpenAI-compatible V2 base URL at `https://qianfan.baidubce.com/v2`.
- Tencent Hunyuan: first-time activation can grant a free resource package, and `Hunyuan-lite` is marked free in official pricing; endpoint details should be checked in current docs.
- Volcengine Ark: free inference quota, safe-experience mode, and campaign credits may be available; exact model, quota, and endpoint details are console-dependent.

## About the CC Switch Templates

All `cc-switch-template.json` files in this repo are **import-prep templates**, not guaranteed official export/import files from the latest `CC Switch` release.

Use them as:

1. a normalized provider record
2. a handoff file for operators
3. a conversion source for your own automation

Before importing into a live `CC Switch` build, verify field names against your installed version.

## Maintenance Rules

- Always attach an update date
- Prefer official docs and official dashboards
- Mark unstable items as `check-console`
- Do not present guessed token numbers as facts

## Official References

- Gemini API
  - [Pricing](https://ai.google.dev/gemini-api/docs/pricing)
  - [Rate limits](https://ai.google.dev/gemini-api/docs/rate-limits)
  - [API key security](https://ai.google.dev/gemini-api/docs/api-key)
  - [OpenAI compatibility](https://ai.google.dev/gemini-api/docs/openai)
- OpenRouter
  - [Quickstart](https://openrouter.ai/docs/quickstart)
  - [Limits](https://openrouter.ai/docs/api-reference/limits)
- Cohere
  - [Rate limits](https://docs.cohere.com/docs/rate-limits)
- Hugging Face
  - [Pricing and Billing](https://huggingface.co/docs/inference-providers/pricing)
- Groq
  - [Overview](https://console.groq.com/docs/overview)
  - [OpenAI compatibility](https://console.groq.com/docs/openai)
  - [Rate limits](https://console.groq.com/docs/rate-limits)
- Mistral
  - [Pricing](https://mistral.ai/pricing)
- Cerebras
  - [Introduction](https://inference-docs.cerebras.ai/introduction)
  - [Models](https://inference-docs.cerebras.ai/models)
- DashScope
  - [Pricing](https://help.aliyun.com/zh/model-studio/model-pricing)
  - [New-user free quota](https://help.aliyun.com/zh/model-studio/new-free-quota)
  - [OpenAI Responses compatibility](https://help.aliyun.com/zh/model-studio/openai-responses-api)
  - [Anthropic compatibility](https://help.aliyun.com/zh/model-studio/anthropic-api)
- SiliconFlow
  - [Docs](https://docs.siliconflow.cn/)
  - [Use with Claude Code](https://docs.siliconflow.cn/quickstart/use_with_claude_code)
  - [Use with CC Switch](https://docs.siliconflow.cn/cn/userguide/introduction/use-with-cc-switch)
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
- Baidu Qianfan
  - [New-user free quota](https://cloud.baidu.com/doc/qianfan/s/Imi2rpirg)
  - [OpenAI SDK compatibility](https://cloud.baidu.com/doc/qianfan/s/Hmh4suq26)
- Tencent Hunyuan
  - [Billing overview](https://cloud.tencent.com/document/product/1729/97731)
- Volcengine Ark
  - [Docs](https://www.volcengine.com/docs/82379)
