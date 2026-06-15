# GitHub Models

[中文](./README.md) | [English](./README.en.md)

- Website: [GitHub Models](https://docs.github.com/en/github-models)
- Registration: sign in with a GitHub account, then use the Models playground or API
- Free tier: official docs provide free playground and API usage, limited by model tier with RPM, RPD, tokens/request, and concurrent-request caps
- Current Copilot Free limits:
  - `Low` models: `15 RPM`, `150 RPD`, `8000 input / 4000 output tokens/request`, `5` concurrent requests
  - `High` models: `10 RPM`, `50 RPD`, `8000 input / 4000 output tokens/request`, `2` concurrent requests
  - `Embedding` models: `15 RPM`, `150 RPD`, `64000 tokens/request`, `5` concurrent requests
- Note: each model page shows its rate-limit tier; GitHub says these limits may change, so re-check before production use
- Compatibility: official API examples can use the OpenAI SDK with the `https://models.github.ai/inference` endpoint
- Recommended for: GitHub-user prototypes, model evaluation, and lightweight scripts

Files in this directory:

- [computer-use.md](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/github-models/computer-use.md)
- [computer-use.en.md](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/github-models/computer-use.en.md)
- [cc-switch-template.json](/Users/kangxiaolin/projects/AI/freeTokenPlan/providers/github-models/cc-switch-template.json)
