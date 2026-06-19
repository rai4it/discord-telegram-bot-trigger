# 3rb Investing — Discord Intelligence Bot

An automated bot that reads the **3rb Investing** Discord server and delivers intelligent Arabic summaries directly to Telegram.

---

## What It Does

The bot monitors all channels in the 3rb Investing server and provides on-demand analysis:

- 📋 **Channel summaries** — pick any channel and get a detailed Arabic summary for any time period
- 👤 **Admin insights** — see everything the admin posted recently across all channels
- 📈 **Stock research** — search what was said about any stock across all channels
- 🎙 **Voice transcription** — voice recordings are automatically transcribed and included in summaries
- 🔗 **Source links** — every summary point links back to the original Discord message
- 🔤 **Smart translation** — English-only channels are translated to Arabic accurately, preserving all numbers and tickers

---

## Telegram Commands

| Command | Description |
|---|---|
| `/start` | Help and command list |
| `/admin` | Summarize admin messages — pick period and type (text or voice) |
| `/channels` | Browse all channels — tap any to summarize |
| `/stock <ticker>` | Everything said about a stock (symbol or company name) |

### Period Options
`6h` · `24h` · `3d` · `1w` · `1m` — default **24h**, max **2 months**

---

## Powered By

- **Discord** — reads server messages via REST API
- **Groq LLM** — `llama-3.3-70b-versatile` for Arabic summarization and translation
- **Groq Whisper** — `whisper-large-v3-turbo` for voice transcription
- **Telegram** — delivers results via `python-telegram-bot`

---

## Access

This is a private bot. To request access contact: **@rai4it**
