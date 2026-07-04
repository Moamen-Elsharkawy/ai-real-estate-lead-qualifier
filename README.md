# AI Real Estate Lead Qualifier

A lead-qualification agent for real estate: engages prospects in natural conversation, collects buying signals, scores every lead automatically, and hands the sales team a structured, prioritized sheet, so agents spend time only on serious buyers.

**Demo video:** https://youtu.be/emWKoHsvySY

## What it does

- Engages inbound prospects in conversation over Telegram
- Extracts the signals that matter: budget, location, purpose, timeline
- Scores and classifies each lead automatically
- Logs structured lead data to Google Sheets for the sales team, filtering out unqualified buyers before they cost an agent's hour

## Workflow

| File | Role |
|---|---|
| `lead-qualification.json` | The complete qualification agent: conversation, extraction, scoring, and sheet logging |

## Stack

n8n, OpenRouter (LLM), Telegram Bot API, Google Sheets.

## Import and setup

1. Import the JSON into n8n.
2. Create credentials: OpenRouter API key, Telegram bot token, Google Sheets. Credential references are name-only placeholders.
3. Replace `YOUR_SPREADSHEET_ID` with your leads sheet.

## Note on redaction

All credentials, webhook IDs, spreadsheet IDs, and phone numbers have been replaced with self-describing placeholders. The workflow logic is exactly what runs in the demo.

---

Built by [Moamen Elsharkawy](https://www.linkedin.com/in/moamen--elsharkawy/), AI Automation Engineer. More builds: [portfolio](https://www.notion.so/Moamen-Elsharkawy-AI-Automation-Specialist-c201df9dd81482998591011f978b1bda) | [GitHub profile](https://github.com/Moamen-Elsharkawy)
