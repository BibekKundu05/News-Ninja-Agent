# 🥷 NewsNinja — AI-Powered News Digest Agent

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge\&logo=python)
![LangGraph](https://img.shields.io/badge/LangGraph-Agentic%20Workflow-black?style=for-the-badge)
![Groq](https://img.shields.io/badge/Groq-LLM%20Inference-orange?style=for-the-badge)
![Tavily](https://img.shields.io/badge/Tavily-Real--Time%20Search-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

### 🚀 Intelligent Multi-Step AI Agent for Real-Time News Research & Summarization

*Built with LangGraph, Groq LLMs, and Tavily Search*

</div>

---

## ✨ Overview

**NewsNinja** is an AI-powered news digest agent that automatically:

* 🔍 Optimizes user queries
* 🌐 Searches the internet in real time
* 🧠 Extracts meaningful insights from articles
* ✍️ Generates polished news summaries
* ⚡ Uses an agentic workflow powered by **LangGraph**

Instead of performing a simple search, NewsNinja follows a **multi-node intelligent pipeline** where every stage has a specific responsibility.


---

# ⚙️ Architecture

The project uses a modular **LangGraph Agent Architecture**.

| Node         | Responsibility                            |
| ------------ | ----------------------------------------- |
| 🧩 Parser    | Optimizes and restructures the user topic |
| 🔎 Searcher  | Searches the web using Tavily             |
| ✍️ Writer    | Creates a refined AI-generated digest     |
| 🧠 LangGraph | Manages state transitions between nodes   |

---

# 🚀 Features

## ✅ Real-Time Internet Search

Uses **Tavily Search API** to fetch fresh news articles.

## ✅ Agentic Workflow

Built using **LangGraph StateGraph** for structured reasoning.

## ✅ AI-Powered Summaries

Uses **Groq LLMs** to generate concise and high-quality news digests.

## ✅ Modular Node-Based Design

Each task is separated into independent reusable nodes.

## ✅ Interactive CLI Experience

Simple command-line workflow for fast experimentation.

---

# 🛠️ Tech Stack

| Technology       | Purpose                      |
| ---------------- | ---------------------------- |
| Python           | Core Programming Language    |
| LangGraph        | Agent Workflow Orchestration |
| LangChain        | Tooling & LLM Integration    |
| Groq             | High-Speed LLM Inference     |
| Tavily           | Real-Time Search Engine      |
| Jupyter Notebook | Development Environment      |

---

# 📦 Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/newsninja.git
cd newsninja
```

## 2️⃣ Install Dependencies

```bash
pip install -qU langchain-groq langgraph langchain-community tavily-python
```

---

# 🔑 API Keys Setup

You need:

* Groq API Key
* Tavily API Key

## Get API Keys

* 🔗 Groq: [https://console.groq.com/keys](https://console.groq.com/keys)
* 🔗 Tavily: [https://app.tavily.com/home](https://app.tavily.com/home)

## Configure Keys

```python
import os
import getpass

os.environ["GROQ_API_KEY"] = getpass.getpass()
os.environ["TAVILY_API_KEY"] = getpass.getpass()
```

---

# ▶️ Run the Project

```python
topic = input("Enter a news topic to research: ")

result = app.invoke({"topic": topic})

print(result)
```

---

# 📸 Example

## Input

```bash
Enter a news topic to research:
AI replacing software engineers
```

## Output

```text
NewsNinja searched multiple sources and generated a concise AI-powered digest summarizing the latest discussions, trends, and expert opinions about AI replacing software engineers.
```

---

# 🧩 Project Structure

```bash
NewsNinja/
│
├── NewsNinja.ipynb        # Main Notebook
├── README.md              # Project Documentation
└── requirements.txt       # Dependencies (optional)
```

---

# 🔄 Workflow Breakdown

## 1️⃣ Parser Node

Transforms raw user input into a more search-friendly query.

### Example

```text
Input:
"AI jobs"

Optimized Query:
"Latest impact of AI on global job markets in 2026"
```

---

## 2️⃣ Searcher Node

Uses Tavily tools to fetch:

* Recent articles
* Headlines
* Web insights
* Trending updates

---

## 3️⃣ Writer Node

Processes gathered information and produces:

* Clean summaries
* Digestible insights
* AI-enhanced reports

---

# 🎯 Future Improvements

* 🌍 Web dashboard using Streamlit
* 🗞️ Daily automated news digest
* 📧 Email newsletter support
* 📱 Mobile-friendly interface
* 🧠 Multi-agent collaboration
* 📊 Sentiment analysis
* 🔔 Real-time breaking news alerts

---

# 🤝 Contributing

Contributions are welcome!

```bash
# Fork the repository
# Create a feature branch
# Commit changes
# Open a Pull Request
```

---

# ⭐ Support

If you found this project useful:

* ⭐ Star the repository
* 🍴 Fork the project
* 🧠 Share ideas & improvements

---

# 📜 License

This project is licensed under the MIT License.

---

<div align="center">

## 🚀 Built with AI + Agentic Workflows

### "Turning raw information into intelligent news insights."

</div>
