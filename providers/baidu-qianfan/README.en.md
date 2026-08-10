# Baidu Qianfan

[中文](./README.md) | [English](./README.en.md)

- Website: [Qianfan new-user free quota](https://cloud.baidu.com/doc/qianfan/s/Imi2rpirg)
- Registration: create a Baidu Cloud account, enable Qianfan, and complete required real-name verification
- Free tier: the official new-user free-quota page says users who enable Qianfan for the first time from `2025-10-24 00:00:00` automatically receive eligible model quotas; the current page lists multiple models at `1M tokens` valid for `3 months`, including examples from `ERNIE-4.5-Turbo`, `DeepSeek-R1`, `DeepSeek-V3.1`, `Kimi-K2-Instruct`, and `Qwen3` / `Qwen3-Coder` families
- Limits: validity starts from the first Qianfan activation date; exact models, token grants, campaign windows, and availability follow the official page
- Tool plan: Baidu's official notice says all `Coding Plan` tiers stopped accepting new purchases from `2026-07-13 10:00:00`, while `Token Plan personal` became fully available; existing valid `Coding Plan` packages can continue until the service period ends and can migrate to `Token Plan`
- Compatibility: Qianfan documents [OpenAI SDK compatibility](https://cloud.baidu.com/doc/qianfan/s/Hmh4suq26), with normal model-service V2 base URL `https://qianfan.baidubce.com/v2`; `Token Plan personal` uses a dedicated API key, OpenAI base URL `https://qianfan.baidubce.com/v2/tokenplan/personal`, and Anthropic base URL `https://qianfan.baidubce.com/anthropic/tokenplan/personal`
- Boundary: `Token Plan personal` is limited to interactive use in compatible AI coding and agent tools; do not treat it as normal new-user free quota, automation-script quota, or an application-backend key
- Recommended for: mainland China users testing domestic models, DeepSeek/Kimi/Qwen-style aggregated models, OpenAI-compatible agent integration, and Token Plan tool access for `Codex` / `Claude Code` / `CC-Switch`
- References: [Token Plan personal](https://cloud.baidu.com/doc/qianfan/s/Dmrabu8b6), [quickstart](https://cloud.baidu.com/doc/qianfan/s/kmracfgi2), [CC-Switch guide](https://cloud.baidu.com/doc/qianfan/s/Tmrad8foj), [stop-sale notice](https://cloud.baidu.com/doc/qianfan/s/Fmrexuejc)

Files in this directory:

- [computer-use.md](computer-use.md)
- [computer-use.en.md](computer-use.en.md)
- [cc-switch-template.json](cc-switch-template.json)
