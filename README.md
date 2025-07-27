# 🎙️ Telegram Voice Chat Bot (Whisper + GPT + TTS)

This project implements a fully automated Telegram bot that:
- Accepts voice messages from users.
- Converts them to text using **Whisper (via OpenRouter API)**.
- Sends the text to an **AI language model** to generate a human-like response.
- Converts the response back to voice using **gTTS (Google Text-to-Speech)**.
- Sends the audio reply back to the user in Telegram — all without human intervention.

---

## ✅ Features Implemented

- 🎧 Voice message input (via Telegram)
- 🧠 Speech-to-text transcription using Whisper
- 🤖 AI-generated replies using OpenRouter LLM
- 🔊 Text-to-speech response using gTTS
- 🔁 End-to-end automation (no manual steps)
- 📦 Git versioning and logging setup

---

## 🔧 Requirements

- Python 3.11+
- `python-telegram-bot`
- `gtts`
- `requests`
- OpenRouter API Key
- Telegram Bot Token

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/telegram-voice-bot.git
   cd telegram-voice-bot
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Create a .env or set environment variables:
   ```bash
   export TELEGRAM_TOKEN="your-telegram-bot-token"
   export OPENROUTER_API_KEY="your-openrouter-key"
5. Run the bot:
   ```bash
   python main.py

