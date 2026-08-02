# DashScope / Bailian

[中文](./README.md) | [English](./README.en.md)

- Website: [Pricing and Free Quota](https://help.aliyun.com/zh/model-studio/model-pricing)
- Registration: sign in with an Alibaba Cloud account and enable Bailian
- Free tier: when Bailian is first enabled, Alibaba Cloud automatically issues new-user free quota for eligible models; the top rule in the current official new-user free-quota FAQ says only China North `2` (Beijing) models receive new-user free quota and other regions do not; if the same FAQ or pricing tables show Singapore-region / international-deployment free quota for a specific model, verify that exact model row
- Validity: the current main rule is `90 days`; accounts that enabled Bailian before `2025-09-08 11:00` may have shorter validity
- Cost guard: verified users may be charged after free quota is exhausted, so enable the console's stop-after-free-quota control; exhausted quota returns `AllocationQuota.FreeTierOnly`
- Extra reference: [new-user free quota](https://help.aliyun.com/zh/model-studio/new-free-quota) for current claim rules and validity
- Recommended for: Chinese mainland users, `Codex`, and `Claude Code`

Files in this directory:

- [computer-use.md](computer-use.md)
- [computer-use.en.md](computer-use.en.md)
- [cc-switch-template.json](cc-switch-template.json)
