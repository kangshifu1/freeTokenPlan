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

| Provider | Free type | Best fit | Registration required | Registration URL |
|---|---|---|---|---|
| [Gemini](providers/gemini/README.en.md) | Long-term model-dependent Free tier; unrestricted `standard keys` are on the retirement path | `CC Switch` / OpenAI-compatible gateway | Yes | [AI Studio](https://aistudio.google.com/) |
| [OpenRouter](providers/openrouter/README.en.md) | `:free` models: `20 RPM`, `50/day` before `$10` credits, `1000/day` after | `Codex` / `CC Switch` | Yes | [OpenRouter Keys](https://openrouter.ai/keys) |
| [Cohere](providers/cohere/README.en.md) | Trial-key monthly call quota | Lightweight tests / prompt validation | Yes | [Cohere Dashboard](https://dashboard.cohere.com/api-keys) |
| [Hugging Face](providers/huggingface/README.en.md) | `$0.10/month` Inference Providers credits for free users | API checks / demos | Yes | [User Access Tokens](https://huggingface.co/settings/tokens) |
| [Groq](providers/groq/README.en.md) | Free Plan RPM/RPD/TPM/TPD limits by model | Low-latency OpenAI-compatible calls | Yes | [Groq Console](https://console.groq.com/keys) |
| [Mistral](providers/mistral/README.en.md) | Free plan / evaluation mode | Model-style testing | Yes | [Mistral Console](https://console.mistral.ai/) |
| [Cerebras](providers/cerebras/README.en.md) | Public endpoints free to use, subject to rate limits | High-speed inference trials | Yes | [Cerebras Inference](https://inference.cerebras.ai/) |
| [NVIDIA NIM](providers/nvidia-nim/README.en.md) | Free serverless NIM development calls | OpenAI-style prototypes | Yes | [NVIDIA Build](https://build.nvidia.com/) |
| [GitHub Models](providers/github-models/README.en.md) | Free playground / API limits | GitHub-account prototypes | Yes | [GitHub Models](https://github.com/marketplace/models) |
| [Vercel AI Gateway](providers/vercel-ai-gateway/README.en.md) | Free-tier `$5/month` AI Gateway credits, limited to eligible models | Vercel / AI SDK projects | Yes | [Vercel Dashboard](https://vercel.com/dashboard) |
| [Cloudflare Workers AI](providers/cloudflare-workers-ai/README.en.md) | Daily `10,000` Neurons free allocation, model-cost dependent | Workers / edge demos | Yes | [Cloudflare Dashboard](https://dash.cloudflare.com/) |
| [DashScope / Bailian](providers/dashscope/README.en.md) | Regional new-user realtime inference quota, split by region and deployment scope | Mainland China / `Codex` / `Claude Code` | Yes | [DashScope Console](https://dashscope.console.aliyun.com/) |
| [SiliconFlow](providers/siliconflow/README.en.md) | Free models after real-name verification, with `CNY 16` reward noted on the CC Switch signup path | China-region multi-model trials | Yes | [SiliconFlow Console](https://cloud.siliconflow.cn/) |
| [Agnes AI](providers/agnes-ai/README.en.md) | Homepage-promoted free API credits / key / tokens / models | Overseas multi-model API prototypes | Yes | [Agnes AI](https://agnes-ai.com/) |
| [Baidu Qianfan](providers/baidu-qianfan/README.en.md) | New-user model token grants, commonly `1M tokens / 3 months` | Domestic models / OpenAI-compatible agents | Yes | [Qianfan Console](https://console.bce.baidu.com/qianfan/) |
| [iFlytek Astron MaaS](providers/xfyun-maas/README.en.md) | Model square plus `Token Plan` / `Coding Plan` subscription access | Mainland China coding-tool integration | Yes | [Package Subscription](https://maas.xfyun.cn/packageSubscription) |
| [Tencent Hunyuan / TokenHub](providers/tencent-hunyuan/README.en.md) | TokenHub language / multimodal-understanding trials provide `1M Tokens / 90 days`; image generation provides `50 generations / 365 days`, video generation `50 points / 365 days`, and 3D generation `100 points / 365 days`; legacy Hunyuan also has a shared `1M tokens / 1 year` package | Hunyuan text generation / TokenHub models | Yes | [TokenHub](https://console.cloud.tencent.com/tokenhub) |
| [Volcengine Ark](providers/volcengine-ark/README.en.md) | Free inference / campaign quota / Agent Plan / Coding Plan | Doubao / DeepSeek / tool integration | Yes | [Ark Console](https://console.volcengine.com/ark/) |

## Quick Navigation

- [Chinese Overview](./README.md)
- [English Overview](./README.en.md)
- [Provider Index](#provider-index)
- [Repository Structure](#repository-structure)
- [About the CC Switch Templates](#about-the-cc-switch-templates)
- [Official References](#official-references)

This repository is a public starter guide for beginners who want to try AI tools with free or low-cost quotas and connect them to coding agents such as `Codex`, `Claude Code`, and `CC Switch`.

- Updated: `2026-07-20`
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
4. If you want one local gateway for multiple providers, free-tier tracking, fallback, and compression, evaluate [OmniRoute](https://github.com/diegosouzapw/OmniRoute)

Gateway recommendation:

- `CC Switch`: best first stop for managing provider/model config and syncing common coding tools.
- `OmniRoute`: local AI gateway / smart router. Its README currently positions it as one endpoint for tools such as `Claude Code`, `Codex`, `Cursor`, and `Cline`, with multi-provider routing, fallback, token compression, and a dashboard. Treat it as a routing layer over upstream providers, not as a standalone free-token provider; real available quota still depends on each upstream provider account and terms.

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
│   ├── agnes-ai/
│   ├── baidu-qianfan/
│   ├── xfyun-maas/
│   ├── tencent-hunyuan/
│   └── volcengine-ark/
└── templates/
```

## Provider Index

- [Gemini](providers/gemini/README.en.md)
- [OpenRouter](providers/openrouter/README.en.md)
- [Cohere](providers/cohere/README.en.md)
- [Hugging Face](providers/huggingface/README.en.md)
- [Groq](providers/groq/README.en.md)
- [Mistral](providers/mistral/README.en.md)
- [Cerebras](providers/cerebras/README.en.md)
- [NVIDIA NIM](providers/nvidia-nim/README.en.md)
- [GitHub Models](providers/github-models/README.en.md)
- [Vercel AI Gateway](providers/vercel-ai-gateway/README.en.md)
- [Cloudflare Workers AI](providers/cloudflare-workers-ai/README.en.md)
- [DashScope / Bailian](providers/dashscope/README.en.md)
- [SiliconFlow](providers/siliconflow/README.en.md)
- [Agnes AI](providers/agnes-ai/README.en.md)
- [Baidu Qianfan](providers/baidu-qianfan/README.en.md)
- [iFlytek Astron MaaS](providers/xfyun-maas/README.en.md)
- [Tencent Hunyuan](providers/tencent-hunyuan/README.en.md)
- [Volcengine Ark](providers/volcengine-ark/README.en.md)

## Current Provider Notes

- Gemini: the Free tier remains model-dependent, with current public pricing examples now led by Gemini 3.5 models. AI Studio now creates new keys as `auth keys`, Google documents that unrestricted `standard keys` are rejected from `2026-06-19`, inactive unrestricted `standard keys` may be blocked sooner, and all `standard keys` are planned for shutdown in `2026-09`. Gemini also has an official OpenAI compatibility endpoint, but it is not a full OpenAI API replacement.
- OpenRouter: free accounts can still create keys without a credit card and use `:free` model variants. The current official limits page lists `20 requests/min`, `50 requests/day` for accounts with less than `$10` purchased credits, and `1000 requests/day` after purchasing at least `$10` credits; the `openrouter/free` router can pick from currently available free models for low-volume experiments.
- Cohere: trial keys remain the correct free testing path, with a documented `1,000 API calls/month` cap and per-endpoint limits such as `20 req/min` for current Chat models, `2,000 inputs/min` for Embed, and `10 req/min` for Rerank.
- Hugging Face: Inference Providers currently give free users `$0.10` monthly credits. Those credits apply to serverless Inference Providers calls routed through Hugging Face and do not apply when using custom third-party provider keys, so this is best treated as a smoke-test or demo route.
- Groq: official docs provide OpenAI-compatible access and now publish a Free Plan Limits table by model. Example Free Plan limits include `30 RPM / 14.4K RPD / 6K TPM / 500K TPD` for `llama-3.1-8b-instant`, `30 RPM / 1K RPD / 12K TPM / 100K TPD` for `llama-3.3-70b-versatile`, and `30 RPM / 1K RPD / 8K TPM / 200K TPD` for the current `openai/gpt-oss-*` models; exact account limits still belong on the console Limits page.
- Mistral: the public pricing page still lists Mistral Free with limited Vibe for code access, and the tier docs say API Free mode is enabled by default with limited limits for evaluation and prototyping.
- Cerebras: the docs still show OpenAI SDK usage, and the current models page says public endpoints are free to use subject to rate limits. The current public production endpoint is `gpt-oss-120b`, with `gemma-4-31b` and `zai-glm-4.7` marked as preview.
- NVIDIA NIM: NVIDIA Build exposes free serverless NIM APIs for development and prototyping, with OpenAI-style chat completions at `https://integrate.api.nvidia.com/v1`; production capacity and limits are account/model-page dependent.
- GitHub Models: free playground and API usage are available with model-tier-specific limits. Under Copilot Free, common free API tiers include `15 RPM / 150 RPD / 5 concurrent` for Low models, `10 RPM / 50 RPD / 2 concurrent` for High models, and `15 RPM / 150 RPD / 5 concurrent` for Embedding models; some named models such as `DeepSeek-R1` and `xAI Grok-3` have lower model-specific limits in the official table. Higher-tier rows such as `Azure OpenAI Global Standard`, `Azure OpenAI Data Zone Standard`, and `o1` / `o3` / `gpt-5` families are marked not applicable to Copilot Free.
- Vercel AI Gateway: team accounts get a free tier with `$5/month` AI Gateway credits. Credits start on the first AI Gateway request, and the monthly free credit no longer applies after purchasing credits; free credits only apply to eligible models, and BYOK provider keys are a paid feature, so treat it as a project gateway rather than a generic provider.
- Cloudflare Workers AI: Workers AI still includes a free daily allocation of `10,000` Neurons, resetting daily at `00:00 UTC`. Cloudflare's current pricing page explains that model-specific input/output and related usage are converted into Neurons and shows example costs by model, so check the target model's Neurons cost before treating the free allocation as usable volume.
- DashScope / Bailian: free quota is regional and activity-based. The official new-user free-quota FAQ says first activation automatically issues eligible model quotas, with the main mainland path limited to China North `2` (Beijing) and China mainland deployment scope; the pricing page also lists some Singapore-region / international-deployment models with free quota. Current validity is `30-90 days`, with first-time activations from `2025-09-08 11:00` onward receiving `90-day` validity.
- SiliconFlow: official docs say free models are available after real-name verification. A current official notice says unverified users cannot use platform functions from `2026-05-15`, and the official CC Switch guide notes a `CNY 16` reward balance after registering through that path and completing real-name verification. The docs also include Claude Code and CC Switch integration guides.
- Agnes AI: the official homepage now explicitly markets free AI API credits, a free API key, free API tokens, and free API models. That is enough to include it as a tracked provider, but exact quota, model list, and protocol details should still be treated as dashboard- or quickstart-dependent until the developer docs expose a stable public reference.
- Baidu Qianfan: official new-user free-quota docs now say first-time Qianfan activations from `2025-10-24 00:00:00` automatically receive eligible model quotas. The current page lists multiple models at `1M tokens` valid for `3 months`, including examples from `ERNIE-4.5-Turbo`, `DeepSeek-R1`, `DeepSeek-V3.1`, `Kimi-K2-Instruct`, and `Qwen3` / `Qwen3-Coder` families. Baidu documents an OpenAI-compatible V2 base URL at `https://qianfan.baidubce.com/v2`.
- iFlytek Astron MaaS: the public model square is the discovery entry, but the current coding-tool path is documented through separate `Token Plan` and `Coding Plan` products. Both publish OpenAI- and Anthropic-compatible endpoints, use dedicated plan-specific API keys, and should not be confused with the regular MaaS inference base URL. `Token Plan` now lists refreshed model examples such as `GLM-5.2` / `GLM-5.1` / `GLM-5`, `DeepSeek-V4-Pro`, `DeepSeek-V4-Flash`, `DeepSeek-V3.2`, `Kimi-K2.6`, `Kimi-K2.5`, `MiniMax-M2.5`, `Qwen3.5` / `Qwen3.6`, `Qwen3-Coder-Next-FP8`, and `GLM-4.7-Flash`, with point-based usage and a `0.8` off-peak time coefficient. `Coding Plan` still uses `astron-code-latest` as the official default model identifier, adds a Responses-compatible endpoint, lists the same refreshed model families, marks the first-month plan unavailable for purchase from `2026-04-09 00:00`, supports monthly renewed-version purchases from `2026-04-09` and quarterly renewed-version purchases from `2026-06-15`, and applies a `2026-06-18` off-peak coefficient to request limits. Treat it as an interactive coding-tool plan, not a backend batch API.
- Tencent Hunyuan / TokenHub: the current billing overview says Hunyuan capabilities are gradually moving to TokenHub, so new model services or expanded capabilities should be checked in TokenHub instead of assuming the legacy Hunyuan console path. The official TokenHub new-user trial page now lists language, multimodal-understanding, image-generation, video-generation, and 3D-generation packages, with the current activity scheduled through `2026-12-31` subject to page notices or platform announcements. Language and multimodal-understanding packages provide `1M Tokens` valid for `90 days`; `HY-Image-V3.0` image generation provides `50 generations / 365 days`, video-generation packages provide `50 points / 365 days`, and 3D-generation packages provide `100 points / 365 days`. First-time legacy Hunyuan activation can still issue a separate one-time shared `1M tokens` package valid for `1 year` across listed Hunyuan text and multimodal models, excluding `Hunyuan-lite`. Treat these as different entry points and validity windows; free packages are consumed before paid packages and postpaid billing, and exhausted or expired packages do not automatically roll into postpaid unless the user enables postpaid.
- Volcengine Ark: free inference quota, safe-experience mode, and campaign credits may be available, while `Agent Plan` / `Coding Plan` are separate tool-integration and campaign routes. Current Ark tool docs cover Codex, Claude Code, OpenCode, and OpenClaw-style entry points; exact model, quota, endpoint, and overage behavior remain console-dependent.

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
  - [Real-name verification update](https://docs.siliconflow.cn/cn/updates/20250515)
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
- Baidu Qianfan
  - [New-user free quota](https://cloud.baidu.com/doc/qianfan/s/Imi2rpirg)
  - [OpenAI SDK compatibility](https://cloud.baidu.com/doc/qianfan/s/Hmh4suq26)
- iFlytek Astron MaaS
  - [Model square](https://maas.xfyun.cn/modelSquare)
  - [Token Plan](https://www.xfyun.cn/doc/spark/TokenPlan.html)
  - [Coding Plan](https://www.xfyun.cn/doc/spark/CodingPlan.html)
- Tencent Hunyuan
  - [Billing overview](https://cloud.tencent.com/document/product/1729/97731)
  - [TokenHub new-user trial package](https://cloud.tencent.com/document/product/1823/130053)
- Volcengine Ark
  - [Docs](https://www.volcengine.com/docs/82379)
- OmniRoute
  - [GitHub](https://github.com/diegosouzapw/OmniRoute)
