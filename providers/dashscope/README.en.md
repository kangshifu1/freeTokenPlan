# DashScope / Bailian

[中文](./README.md) | [English](./README.en.md)

Verified: `2026-11-24`

- Website: [Pricing and Free Quota](https://help.aliyun.com/zh/model-studio/model-pricing)
- Registration: sign in with an Alibaba Cloud account and enable Bailian; the official new-user free-quota page requires real-name verification before activation; unverified accounts receive no free quota
- Free tier: when Bailian is first enabled, Alibaba Cloud automatically issues new-user free quota for eligible models; the official new-user free-quota page's main rule currently says China North `2` (Beijing) region models receive free quota and other regions do not; the same FAQ later also mentions Singapore-region model rows, so verify the exact model row and console quota
- Validity: the current main rule is `90 days`; accounts that enabled Bailian before `2025-09-08 11:00` may have shorter validity
- Package boundary: dedicated `Token Plan` / `Coding Plan` API keys do not consume the normal new-user free quota; use a regular model API key for free-quota tests, then verify the region and model row
- Cost guard: the stop-after-free-quota control is off by default; enable it before the first call to stop with HTTP `403` / `AllocationQuota.FreeTierOnly` on exhaustion instead of automatically paying for overage
- Extra reference: [new-user free quota](https://help.aliyun.com/zh/model-studio/new-free-quota) for current claim rules and validity
- Recommended for: Chinese mainland users, `Codex`, and `Claude Code`

Files in this directory:

- [computer-use.md](computer-use.md)
- [computer-use.en.md](computer-use.en.md)
- [cc-switch-template.json](cc-switch-template.json)
