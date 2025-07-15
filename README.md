# 🧠 Jarvis – Voice-Activated AI Assistant

Jarvis is a simple yet powerful voice assistant built with Python, leveraging OpenAI's GPT models, speech recognition, and text-to-speech synthesis. It listens to your voice, sends it to ChatGPT, and replies back in spoken language—just like Iron Man's assistant.

---

## 🎯 Features

- 🎙️ **Speech Recognition** — Uses your microphone to listen in real-time.
- 🤖 **AI Conversations** — Sends transcribed audio to OpenAI's `gpt-3.5-turbo` for intelligent responses.
- 🗣️ **Voice Response** — Uses `pyttsx3` to speak responses out loud.
- 🔁 **Continuous Loop** — Listens and responds continuously in a conversation loop.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| `speech_recognition` | Converts voice to text |
| `pyttsx3` | Converts text to speech |
| `openai` | Connects to ChatGPT |
| `Python` | Core language |

---

## 🚀 Getting Started

1. **Clone this repo**
   ```bash
   git clone https://github.com/yourusername/jarvis.git
   cd jarvis
