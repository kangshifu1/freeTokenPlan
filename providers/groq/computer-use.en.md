# Groq Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## Operator Steps

1. Open [https://console.groq.com/](https://console.groq.com/)
2. Register or sign in
3. Open the API keys page
4. Create a new key
5. Copy the key
6. Save it locally as `GROQ_API_KEY`
7. Check the official Rate Limits docs and the organization-level `Limits` page for current availability; record the target model's `RPM`, `RPD`, `TPM`, and `TPD`
8. In `CC Switch`, add:
   - Base URL: `https://api.groq.com/openai/v1`
   - Default model: a currently available model from the console

## Human Takeover Points

- Email verification
- Security verification

## Final Checklist

- Key works
- Target model Free Plan limits still match the official Rate Limits page
- Current organization-level limits are noted if they differ from the public table
