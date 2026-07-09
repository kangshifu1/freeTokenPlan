# GitHub Models

[中文](./README.md) | [English](./README.en.md)

- Website: [GitHub Models](https://docs.github.com/en/github-models)
- Registration: sign in with a GitHub account, then use the Models playground or API
- Free tier: official docs provide free playground and API usage, limited by model tier with RPM, RPD, tokens/request, and concurrent-request caps
- Current common Copilot Free limits:
  - `Low` models: `15 RPM`, `150 RPD`, `8000 input / 4000 output tokens/request`, `5` concurrent requests
  - `High` models: `10 RPM`, `50 RPD`, `8000 input / 4000 output tokens/request`, `2` concurrent requests
  - `Embedding` models: `15 RPM`, `150 RPD`, `64000 tokens/request`, `5` concurrent requests
  - `DeepSeek-R1` / `DeepSeek-R1-0528` / `MAI-DS-R1`: `1 RPM`, `8 RPD`, `4000 input / 4000 output tokens/request`, `1` concurrent request
  - `xAI Grok-3`: `1 RPM`, `15 RPD`, `4000 input / 4000 output tokens/request`, `1` concurrent request; `xAI Grok-3-Mini`: `2 RPM`, `30 RPD`, `4000 input / 8000 output tokens/request`, `1` concurrent request
- Important: the official rate-limit table also lists higher-tier rows such as `Azure OpenAI Global Standard`, `Azure OpenAI Data Zone Standard`, and `o1` / `o3` / `gpt-5` families; those rows are marked not applicable for `Copilot Free` and should not be treated as free-account quota
- Note: each model page shows its rate-limit tier; GitHub says these limits may change, so re-check before production use
- Compatibility: official API examples can use the OpenAI SDK with the `https://models.github.ai/inference` endpoint
- Recommended for: GitHub-user prototypes, model evaluation, and lightweight scripts

Files in this directory:

- [computer-use.md](computer-use.md)
- [computer-use.en.md](computer-use.en.md)
- [cc-switch-template.json](cc-switch-template.json)
