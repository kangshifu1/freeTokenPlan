# Groq

[中文](./README.md) | [English](./README.en.md)

- Website: [Groq Docs](https://console.groq.com/docs/overview)
- Registration: create a Groq Console account and generate an API key
- Free tier: free start available; the official Rate Limits page now lists `Free Plan Limits` by model across `RPM`, `RPD`, `TPM`, and `TPD`
- Current examples: `groq/compound` / `groq/compound-mini` have `30 RPM` / `250 RPD` / `70K TPM`; `meta-llama/llama-prompt-guard-2-22m` / `meta-llama/llama-prompt-guard-2-86m` have `30 RPM` / `14.4K RPD` / `15K TPM` / `500K TPD`; `openai/gpt-oss-120b` / `openai/gpt-oss-20b` and `qwen/qwen3.6-27b` have `30 RPM` / `1K RPD` / `8K TPM` / `200K TPD`; `qwen/qwen3.8-27b` has `30 RPM` / `1K RPD` / `8K TPM` / `2M TPD`
- Limits: rate limits apply at the organization level, and Groq describes the public table as a high-level summary; use the console `Limits` page for exact current account limits
- Recommended for: low-latency interaction and CLI-style workflows

Files in this directory:

- [computer-use.md](computer-use.md)
- [computer-use.en.md](computer-use.en.md)
- [cc-switch-template.json](cc-switch-template.json)
