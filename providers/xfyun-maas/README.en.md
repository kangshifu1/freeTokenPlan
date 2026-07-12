# iFlytek Astron MaaS

[中文](./README.md) | [English](./README.en.md)

- Website: [iFlytek Astron MaaS model square](https://maas.xfyun.cn/modelSquare)
- Registration: sign in with an iFlytek account, enable Astron MaaS, and complete any required verification
- Free tier: the model square exposes models and platform capabilities, but the clearest public coding-tool access path is currently documented through `Astron Token Plan` and `Astron Coding Plan`; `Token Plan` now targets enterprise / team scenarios and lists switchable model examples such as `GLM-5.2` / `GLM-5.1` / `GLM-5`, `DeepSeek-V4-Pro`, `DeepSeek-V4-Flash`, `DeepSeek-V3.2`, `Kimi-K2.6`, `Kimi-K2.5`, `MiniMax-M2.5`, `Qwen3.5` / `Qwen3.6`, `Qwen3-Coder-Next-FP8`, and `GLM-4.7-Flash`; `Coding Plan` uses `astron-code-latest` as the unified default model and lists a similar model pool. Both plans use plan metering / request limits with a `0.8` off-peak coefficient; `Coding Plan` says the first-month plan is no longer purchasable from `2026-04-09 00:00`, supports monthly renewed-version purchases from `2026-04-09` and quarterly renewed-version purchases from `2026-06-15`, and applies a peak / off-peak coefficient to request limits from `2026-06-18`, so do not treat those plans as a general long-term free API
- Compatibility: official docs explicitly provide `OpenAI`, `Anthropic`, and `Coding Plan` Responses-compatible endpoints; `Token Plan` and `Coding Plan` each use their own base URL and must not be mixed with the regular `maas-api` route
- Recommended for: mainland China access to coding tools such as `Claude Code`, `Cursor`, `OpenCode`, and `OpenClaw`, with plan-based routing across supported models

Files in this directory:

- [computer-use.md](computer-use.md)
- [computer-use.en.md](computer-use.en.md)
- [cc-switch-template.json](cc-switch-template.json)
