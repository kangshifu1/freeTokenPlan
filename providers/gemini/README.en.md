# Gemini

[中文](./README.md) | [English](./README.en.md)

- Website: [Gemini API Pricing](https://ai.google.dev/gemini-api/docs/pricing)
- Registration: sign in to Google AI Studio with a Google account, then create an API key; new keys are now created as `auth keys`
- Free tier: official long-term free tier, dependent on both model and call mode. The current pricing page marks `gemini-3.8-flash` Standard API input, output, and context caching as free of charge, while Batch, Google Search grounding, and Maps grounding are unavailable on its Free tier. The paid tier currently shares `5,000` free Search / Maps requests per month across Gemini 3 and newer models; do not record that as Free-tier grounding quota. Check Gemini 2.5, Embedding, and other model rows individually, and verify the API-key type and status during setup
- Compatibility: official [OpenAI compatibility](https://ai.google.dev/gemini-api/docs/openai) exists with base URL `https://generativelanguage.googleapis.com/v1beta/openai/`, but verify the downstream protocol requirement first
- Recommended for: beginner testing, lightweight coding, grounding demos

Files in this directory:

- [computer-use.md](computer-use.md)
- [computer-use.en.md](computer-use.en.md)
- [cc-switch-template.json](cc-switch-template.json)
