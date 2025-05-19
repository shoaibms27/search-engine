# 🔎 LangChain Search Agent – Chat with Web, Wikipedia & Arxiv

This project is a **Streamlit-based conversational AI assistant** built using **LangChain Agents** and **Groq's LLaMA3-8B model**. It integrates **DuckDuckGo**, **Wikipedia**, and **Arxiv** search tools to fetch real-time and scholarly information based on user queries.

> 💡 This app demonstrates how to build a **ReAct-based Agent** using LangChain and visualize its reasoning steps directly in a chat UI.

---


## 🚀 Features

- 🧠 Powered by **Groq’s LLaMA3-8B LLM**
- 🌐 Integrates:
  - 🔍 DuckDuckGo Search
  - 📚 Wikipedia Search
  - 📄 Arxiv API for research papers
- 🧩 Built using **LangChain Agents (ReAct)**
- 💬 Interactive **chat interface** with **streamed agent thoughts** using `StreamlitCallbackHandler`
- 🔐 Secure sidebar input for your **Groq API Key**

---

## 🛠️ Tech Stack

| Component        | Tool / Library              |
|------------------|-----------------------------|
| Web Framework    | Streamlit                   |
| LLM Integration  | LangChain + Groq API        |
| Search Tools     | DuckDuckGo, Wikipedia, Arxiv|
| Agent Type       | Zero-Shot ReAct Agent       |
| Streaming Output | LangChain `StreamlitCallbackHandler` |

---

## 📦 Installation

### 1. Clone the Repo

```bash
git clone https://github.com/yourusername/langchain-search-agent.git
cd langchain-search-agent
