# DashScope / Bailian

[中文](./README.md) | [English](./README.en.md)

- Website: [Pricing and Free Quota](https://help.aliyun.com/zh/model-studio/model-pricing)
- Registration: sign in with an Alibaba Cloud account and enable Bailian
- Free tier: when Bailian is first enabled, Alibaba Cloud automatically issues new-user free quota for eligible models; the official new-user free-quota page's main rule currently says only China North `2` (Beijing) region models receive free quota and other regions do not; the same FAQ later also mentions Singapore-only model rows, so verify the exact model row and console quota
- Validity: the current main rule is `90 days`; accounts that enabled Bailian before `2025-09-08 11:00` may have shorter validity
- Package boundary: dedicated `Token Plan` / `Coding Plan` API keys do not consume the normal new-user free quota; use a regular model API key for free-quota tests, then verify the region and model row
- Cost guard: verified users may be charged after free quota is exhausted, so enable the console's stop-after-free-quota control; exhausted quota returns `AllocationQuota.FreeTierOnly`
- Extra reference: [new-user free quota](https://help.aliyun.com/zh/model-studio/new-free-quota) for current claim rules and validity
- Recommended for: Chinese mainland users, `Codex`, and `Claude Code`

Files in this directory:

- [computer-use.md](computer-use.md)
- [computer-use.en.md](computer-use.en.md)
- [cc-switch-template.json](cc-switch-template.json)
