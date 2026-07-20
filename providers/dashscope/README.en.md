# DashScope / Bailian

[中文](./README.md) | [English](./README.en.md)

- Website: [Pricing and Free Quota](https://help.aliyun.com/zh/model-studio/model-pricing)
- Registration: sign in with an Alibaba Cloud account and enable Bailian
- Free tier: when Bailian is first enabled, Alibaba Cloud automatically issues new-user free quota for each eligible model; current official docs put the main mainland path on realtime inference for models in China mainland deployment scope and the China North `2` (Beijing) region, excluding Batch calls, fine-tuning, deployments, and custom models; the pricing page also lists some Singapore-region / international-deployment models with free quota
- Validity: current official rules say the quota is valid for `30-90 days`, and first-time activations from `2025-09-08 11:00` onward receive `90-day` validity
- Cost guard: verified users may be charged after free quota is exhausted, so enable the console's stop-after-free-quota control; exhausted quota returns `AllocationQuota.FreeTierOnly`
- Extra reference: [new-user free quota](https://help.aliyun.com/zh/model-studio/new-free-quota) for current claim rules and validity
- Recommended for: Chinese mainland users, `Codex`, and `Claude Code`

Files in this directory:

- [computer-use.md](computer-use.md)
- [computer-use.en.md](computer-use.en.md)
- [cc-switch-template.json](cc-switch-template.json)
