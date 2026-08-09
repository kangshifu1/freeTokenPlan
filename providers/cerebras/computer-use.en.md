# Cerebras Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## Operator Steps

1. Open [https://inference.cerebras.ai/](https://inference.cerebras.ai/)
2. Register or sign in
3. Add a verified payment method when the console asks, then confirm whether Free Trial credits were granted; the current official note is `$5`, valid for `30` days after grant
4. Open the API keys page
5. Create a key
6. Copy the key
7. Save it locally as `CEREBRAS_API_KEY`
8. Check the OpenAI SDK, Account & Billing, Rate Limits, and official Models pages in the docs to confirm Free Trial terms, dual-bucket uncached / total token limits, model status, and deprecation notices
9. Record the compatible routing details for `CC Switch`

## Human Takeover Points

- Email verification
- Payment-method verification
- Risk-control checks

## Final Checklist

- Current model IDs recorded
- Current Free Trial credits, validity, and dual-bucket rate-limit note recorded
- Default model plus production / preview status and `zai-glm-4.7` deprecation date confirmed against the official Models / Change Log pages
