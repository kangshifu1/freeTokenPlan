# OpenRouter Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## Goal

1. Register an OpenRouter account
2. Create an API key
3. Identify free models
4. Prepare `CC Switch` import data

## Operator Steps

1. Open [https://openrouter.ai/](https://openrouter.ai/)
2. Click `Sign In`
3. Complete login by email or social provider
4. Open [https://openrouter.ai/keys](https://openrouter.ai/keys)
5. Click `Create Key`
6. Name the key, for example `cc-switch-test`
7. Copy the key
8. Save it locally as `OPENROUTER_API_KEY`
9. Open the models page and filter for `free`, or open the official `Free Models Router` docs to decide whether `openrouter/free` fits this low-volume test
10. Record 1 to 3 currently available free models and note the official free-model limits: `20 requests/min`, `50 requests/day` before `$10` purchased credits, and `1000 requests/day` after `$10`
11. In `CC Switch`, add:
   - Name: `OpenRouter`
   - Base URL: `https://openrouter.ai/api/v1`
   - API key: the copied key
   - Default model: one verified `:free` model

## Human Takeover Points

- Email verification
- Suspicious-login review if triggered

## Final Checklist

- API key created
- Current default free model recorded
- Daily and per-minute limits noted from the current official limits page
