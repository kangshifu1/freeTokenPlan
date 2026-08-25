# NVIDIA NIM Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## Operator Steps

1. Open [https://build.nvidia.com/](https://build.nvidia.com/)
2. Sign in with an NVIDIA Developer account, or register first
3. Open the target model page and confirm that `Model Availability` still shows `Free Endpoint` as `Available`
4. Click `Get API Key`, `Build with this model`, or the equivalent action
5. Generate and copy the API key
6. Save it locally as `NVIDIA_API_KEY`
7. Record the current model ID, endpoint, `Free Endpoint` status, and visible rate-limit wording
8. For CC Switch, add it as an OpenAI-compatible provider:
   - Base URL: `https://integrate.api.nvidia.com/v1`
   - API key: the copied key
   - Default model: copy from the current model page before import

## Human Takeover Points

- NVIDIA account login / email verification
- Organization or developer terms
- Region, rate-limit, `Free Endpoint: Deprecated`, or other model availability warnings

## Final Checklist

- API key created successfully
- Current model page still shows `Free Endpoint: Available`
- Account or model-page rate limits are recorded
- Development-prototype free calls are not confused with production use
