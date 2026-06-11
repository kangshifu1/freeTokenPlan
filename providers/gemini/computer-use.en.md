# Gemini Computer Use Script

[中文](./computer-use.md) | [English](./computer-use.en.md)

## Goal

1. Sign in with a Google account
2. Open AI Studio
3. Create an API key
4. Record the key and recommended models
5. Fill `cc-switch-template.json`

## Preconditions

- A usable Google account
- Email or phone verification available if required
- Human takeover for CAPTCHA or security checks

## Operator Steps

1. Open [https://aistudio.google.com/](https://aistudio.google.com/)
2. Click `Sign in` if not signed in
3. Complete Google login and any secondary verification
4. Open `Get API key` or `API keys`
5. Click `Create API key`
6. If asked for a project, use the default project or create a small test project
7. Copy the generated key immediately
8. Save it locally as `GEMINI_API_KEY`
9. Record suggested starter models:
   - `gemini-2.5-flash`
   - `gemini-2.5-flash-lite`
10. For `CC Switch`, use a compatible gateway if your downstream tool expects an OpenAI-style API

## Human Takeover Points

- Google verification
- Account security review
- Region or browser risk checks

## Final Checklist

- API key created successfully
- Creation date recorded
- Current free-tier model list checked

