# 📬 AI Email Assistant (GPT-4o Powered, Voice-Controlled)

> **Auto-reads. Understands. Speaks. Replies.**  
> Your fully automated email productivity weapon — built with `n8n`, `GPT-4o`, and voice magic.

---
<img src='![image](https://github.com/user-attachments/assets/89846b5a-0787-49e8-8c66-d9d75770c679)
'>

## 🚀 Overview

The **AI Email Assistant** is a voice-controlled agent that automates how you manage, read, and reply to emails. It pulls recent emails, understands the context, converses with you using natural language, and even *responds back professionally* — all through voice or chat.

> ⚠️ This isn’t a toy GPT bot. It’s a real-world AI agent using:
- 🤖 **n8n AI Agent** with GPT-4o
- 📬 **Gmail Triggers** for real-time email pulls
- 📊 **Google Sheets** for memory/context tracking
- 🎤 **Voice Input/Output** for hands-free control
- 📡 Cloud-based and production-ready

---

## 💡 Features

- 🔄 **Auto-fetch latest emails** using Gmail API (triggered every X minutes)
- 📚 **Context memory** with Google Sheets (storing last 20 threads)
- 🔍 **Ask-anything agent**:
  - “What did that client say about payment?”
  - “Summarize unread emails from today”
  - “Reply to the offer from HR”
- ✍️ **Auto-response drafting** using GPT-4o
- 🎤 **Voice-controlled agent** (works with browser/desktop mic)
- 🧠 Conversational — remembers past thread references
- 🛠️ Fully automated via **n8n Cloud**

---

## 🧠 Architecture

```plaintext
Gmail Trigger → Google Sheets (Context) → GPT-4o Agent → Voice I/O
                          ↓
               Email Draft Generator (GPT)
