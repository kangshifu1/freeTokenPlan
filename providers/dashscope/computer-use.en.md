# DashScope Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

Verified: `2026-11-24`

## Operator Steps

1. Open [https://dashscope.console.aliyun.com/](https://dashscope.console.aliyun.com/)
2. Sign in with an Alibaba Cloud account
3. Complete real-name verification, then sign in with the Alibaba Cloud main account or a RAM account with `AliyunBailianFullAccess`; the service activates automatically
4. Read the [new-user free-quota rules](https://help.aliyun.com/zh/model-studio/new-free-quota) and confirm quota was issued; unverified accounts receive no free quota
5. Open the API key management page
6. Create an API key
7. Copy the key
8. Save it locally as `DASHSCOPE_API_KEY`
9. Check the current free models, new-user quota, the main `90-day` validity rule, and the China North `2` (Beijing) main route; if needed, open [new-user free quota](https://help.aliyun.com/zh/model-studio/new-free-quota) and the pricing tables to verify whether the target model has Singapore-region free quota
10. If the console shows a dedicated `Token Plan` / `Coding Plan` API key, do not use it to judge the normal new-user free quota; free-quota validation should use a regular model API key
11. Before the first call, enable stop-after-free-quota for the target model on the free-quota page (off by default); wait for it to take effect to avoid automatic paid overage
12. Record both OpenAI-compatible and Anthropic-compatible endpoints if needed

## Human Takeover Points

- Alibaba Cloud login
- Real-name verification before activation and quota issuance; recharge confirmation for continued paid usage
- SMS security verification

## Final Checklist

- Free campaign still valid
- Account is eligible for the mainland China new-user free quota
- Region, deployment scope, and model match the chosen route
- The key is either a regular model API key or a separate `Token Plan` / `Coding Plan` key, and quota expectations match that route
- Stop-after-free-quota is enabled, or paid overage risk is explicitly accepted
- Compatible endpoints noted
