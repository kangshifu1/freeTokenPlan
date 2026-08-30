# DashScope Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## Operator Steps

1. Open [https://dashscope.console.aliyun.com/](https://dashscope.console.aliyun.com/)
2. Sign in with an Alibaba Cloud account
3. If Bailian is not enabled, enable it first
4. Read the enablement prompts; the official new-user free-quota page currently says real-name verification is not required to receive or use the free quota, and is needed with recharge only if the user wants to continue paid pay-as-you-go calls after exhaustion
5. Open the API key management page
6. Create an API key
7. Copy the key
8. Save it locally as `DASHSCOPE_API_KEY`
9. Check the current free models, new-user quota, the main `90-day` validity rule, and the China North `2` (Beijing) main route; if needed, open [new-user free quota](https://help.aliyun.com/zh/model-studio/new-free-quota) and the pricing tables to verify whether the target model has Singapore-region or international-deployment free quota
10. If the console shows a dedicated `Token Plan` / `Coding Plan` API key, do not use it to judge the normal new-user free quota; free-quota validation should use a regular model API key
11. On the model usage page, confirm the stop-after-free-quota state: brand-new unverified users are usually forced into stop-after-free-quota behavior, while verified accounts should enable it manually to avoid paid overage after exhaustion
12. Record both OpenAI-compatible and Anthropic-compatible endpoints if needed

## Human Takeover Points

- Alibaba Cloud login
- Real-name verification or recharge confirmation, only when continuing paid pay-as-you-go calls after exhaustion
- SMS security verification

## Final Checklist

- Free campaign still valid
- Account is eligible for the mainland China new-user free quota
- Region, deployment scope, and model match the chosen route
- The key is either a regular model API key or a separate `Token Plan` / `Coding Plan` key, and quota expectations match that route
- Stop-after-free-quota is enabled, or paid overage risk is explicitly accepted
- Compatible endpoints noted
