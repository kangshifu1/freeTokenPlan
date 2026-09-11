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
8. Check the OpenAI SDK, Account & Billing, Rate Limits, and official Models pages in the docs to confirm the Free Trial `$5` / `30-day` boundary, `5 RPM` / `30K uncached TPM` / `90K total TPM` / `1M TPH` / `1M TPD` limits, and the current public models `gpt-oss-120b` and `qwen-3.8-27b`
9. Record the compatible routing details for `CC Switch`

## Human Takeover Points

- Email verification
- Payment-method verification
- Risk-control checks

## Final Checklist

- Current model IDs recorded and checked against the official Models page
- Current Free Trial credits, validity, dual-bucket rate limits, and the lack of a permanent free tier recorded
- Current public models confirmed against the official Models page
