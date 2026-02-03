# 🤖 Stateful LLM Chat System (LangGraph)

This project explores how to build a **stateful conversational LLM system** using **LangGraph** and **LangChain**, moving beyond simple prompt-response interactions.

The system manages conversation flow using graph-based execution and supports **local LLMs via Ollama**.

---

## 🚀 Features

- Stateful conversation management using LangGraph
- Message routing with graph-based workflows
- Local LLM inference via Ollama
- Support for multiple models:
  - LLaMA 3
  - Mistral
  - Phi
- Modular backend and frontend structure
- Message checkpointing and persistence
- Streaming and threaded frontend experiments

---

## 🛠️ Tech Stack

- **Python**
- **LangGraph**
- **LangChain**
- **Ollama**
- **Streamlit**
- **SQLite (for persistence)**

---

## 📂 Project Structure

```text
LANG_CHAT/
│
├── langgraph_backend.py
├── langgraph_database_backend.py
├── langgraph_tool_backend.py
├── streaming_frontend_threading.py
├── streamlit_frontend.py
├── chatbot_async.py
├── chatbot_mcp.py
├── chatbot.db
├── tools.ipynb
├── persistence.ipynb
├── main.py
└── README.md
