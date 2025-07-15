# 🧠 Telegram-based AI Chatbot with Context Memory using n8n + Zep + OpenRouter

This workflow implements a Telegram bot using [n8n](https://n8n.io/) that connects users to an AI assistant powered by OpenRouter (LLMs), Zep and Postgres. It processes messages in real time and responds contextually using user-specific memory.



<img width="1006" height="509" alt="image" src="https://github.com/user-attachments/assets/a55cd33b-b35e-44ff-9023-ed2ece036c3b" />
<img width="1271" height="661" alt="image" src="https://github.com/user-attachments/assets/36ad0cf5-b28e-4cde-a030-3cbcae947b77" />


---

## 🚀 Features

- ✅ Telegram Bot Trigger
- 🧠 AI Agent powered by LangChain + OpenRouter (e.g., Mistral 7B)
- 📥 User input processed with Zep Graph API
- 🧾 Fact extraction via Code Node
- 🧠 Long-term memory using:
  - Zep memory vector store
  - Postgres memory (optional)
- 📤 Responses sent back to the user
- 🧠 Memory updates stored after each interaction

---

## 🛠️ Technologies Used

- [n8n](https://n8n.io/) (workflow automation)
- [Telegram Bot API](https://core.telegram.org/bots/api)
- [OpenRouter API](https://openrouter.ai/)
- [Zep](https://getzep.com/) (vector memory & user graph)
- LangChain Nodes for n8n
- Postgres DB (for hybrid memory)
- JavaScript (for fact extraction)

---

## 📌 Setup Instructions

1. Clone or import this workflow JSON into your n8n instance.
2. Set up the following credentials in n8n:
   - Telegram API
   - Zep API
   - OpenRouter API
   - Postgres (optional)
3. Start the Telegram bot and interact with it via chat.
4. Incoming queries are enriched with facts from Zep, processed by LLMs, and memory is updated per session.

---

## 🧠 Flow Summary

