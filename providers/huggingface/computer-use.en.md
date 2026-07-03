# Hugging Face Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## Operator Steps

1. Open [https://huggingface.co/join](https://huggingface.co/join)
2. Register or sign in
3. Complete email verification
4. Open [https://huggingface.co/settings/tokens](https://huggingface.co/settings/tokens)
5. Create a new token
6. Copy the token
7. Save it locally as `HF_TOKEN`
8. Open the [Inference Providers billing docs](https://huggingface.co/docs/inference-providers/pricing), confirm whether Free users still receive `$0.10` monthly credits, then check which provider or model route you plan to use
9. Confirm whether the call is routed through Hugging Face; if you bring a custom third-party provider key, do not count it against Hugging Face monthly credits
10. For `CC Switch`, prefer a compatible gateway before import

## Human Takeover Points

- Email verification
- Token scope selection

## Final Checklist

- Token scopes are not overly broad
- Remaining `$0.10` monthly credits are noted if needed
- The route uses Hugging Face routing rather than a custom third-party provider key
