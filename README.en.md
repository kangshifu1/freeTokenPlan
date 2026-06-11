# Free AI Token and Free Tier Catalog

[中文](./README.md) | [English](./README.en.md)

This repository is a public starter guide for beginners who want to try AI tools with free or low-cost quotas and connect them to coding agents such as `Codex`, `Claude Code`, and `CC Switch`.

- Updated: `2026-06-11`
- Audience: beginners, indie builders, AI tool users
- Scope: only official or first-party-documented free tiers, trial quotas, and compatibility notes
- Warning: free-tier policies change often; account dashboards always win over this repo

## Quick Start

If you just want to get started fast, start with:

1. [Google Gemini API](https://ai.google.dev/gemini-api/docs/pricing)
2. [OpenRouter](https://openrouter.ai/docs/quickstart)
3. [Cohere](https://docs.cohere.com/docs/rate-limits)
4. [DashScope / Alibaba Cloud Bailian](https://help.aliyun.com/zh/model-studio/model-pricing)

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
│   ├── dashscope/
│   └── siliconflow/
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
- [DashScope / Bailian](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/dashscope/README.en.md)
- [SiliconFlow](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/siliconflow/README.en.md)

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
- OpenRouter
  - [Quickstart](https://openrouter.ai/docs/quickstart)
  - [Limits](https://openrouter.ai/docs/api-reference/limits)
- Cohere
  - [Rate limits](https://docs.cohere.com/docs/rate-limits)
- Hugging Face
  - [Pricing and Billing](https://huggingface.co/docs/api-inference/pricing)
- Groq
  - [Overview](https://console.groq.com/docs/overview)
  - [OpenAI compatibility](https://console.groq.com/docs/openai)
- Mistral
  - [Pricing](https://docs.mistral.ai/getting-started/pricing/)
- Cerebras
  - [Introduction](https://inference-docs.cerebras.ai/introduction)
- DashScope
  - [Pricing](https://help.aliyun.com/zh/model-studio/model-pricing)
  - [OpenAI Responses compatibility](https://help.aliyun.com/zh/model-studio/openai-responses-api)
  - [Anthropic compatibility](https://help.aliyun.com/zh/model-studio/anthropic-api)
- SiliconFlow
  - [Docs](https://docs.siliconflow.cn/)
  - [Use with Claude Code](https://docs.siliconflow.cn/quickstart/use_with_claude_code)

