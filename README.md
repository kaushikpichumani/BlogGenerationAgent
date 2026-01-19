
Each node performs a dedicated responsibility, making the system modular, debuggable, and production-ready.

---

## 🧠 Architecture

### Graph Nodes

| Node Name | Responsibility |
|---------|---------------|
| `__start__` | Entry point of the LangGraph workflow |
| `title_creation` | Generates a compelling blog title based on user input |
| `content_generator` | Expands the title into a full blog article |
| `__end__` | Terminates the workflow |

---

## ✨ Features

- ✅ Modular agent design using **LangGraph**
- ✅ Stateful execution with clear node transitions
- ✅ Observability & tracing via **LangSmith**
- ✅ Easy local development using `langgraph dev`
- ✅ Python 3.11 compatible
- ✅ Production-friendly architecture

---

## 🛠️ Tech Stack

- **Python 3.11+**
- **LangGraph**
- **LangChain**
- **LangSmith**
- **OpenAI / LLM provider**
- **uv** (for fast dependency management)

---

## 📦 Project Structure

