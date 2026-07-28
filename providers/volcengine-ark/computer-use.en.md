# Volcengine Ark Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## Operator Steps

1. Open [Volcengine Ark Console](https://console.volcengine.com/ark/)
2. Sign in with a Volcengine account
3. Enable Ark if it is not already enabled
4. Complete real-name and security verification
5. Open API key / endpoint management
6. Create and copy an API key
7. Save it locally as `ARK_API_KEY`
8. Check the console for free inference quota, safe-experience mode, and current campaign quota
9. If using Doubao Search / `web_search`, open the service docs or console and confirm the current `500` free uses per month, supported tools, and overage rules
10. If using `Coding Plan`, open the relevant package / billing / campaign page and confirm package quota, model scope, validity, and discount rules
11. Open the `Agent Plan` / `Coding Plan` AI-tool integration docs and confirm the base URL, model name, endpoint, and environment variables for the target Codex, Claude Code, OpenCode, OpenClaw, or similar entry point
12. Before importing into CC Switch, confirm that the current model is still covered by free quota or a campaign

## Human Takeover Points

- Volcengine login
- Real-name verification
- SMS / email / risk-control checks

## Final Checklist

- Free inference quota is visible
- Safe-experience mode is enabled or paid overage risk is clearly understood
- Doubao Search / `web_search` still shows `500` free uses per month in the current service docs or console
- The `Coding Plan` package quota, model scope, validity, and discount rules come from the current package page
- `Agent Plan` / `Coding Plan` is understood as a package or campaign route, not guaranteed long-term free API quota
- The selected tool entry comes from the current official AI-tool integration page
- Default model and endpoint come from the current console
- OpenAI-compatible configuration is confirmed in official docs
