# 🧠 LLM Question Router: Wikipedia or Vector Store

This project uses a Large Language Model (LLM) to intelligently route user questions either to a **Wikipedia search** or a **Vector Store** (semantic search) using LangGraph and Pydantic. It helps decide the best source of truth based on the question's nature.

---

## 🚀 Features

- 🤖 LLM-based decision routing using structured output
- 📚 Wikipedia integration for general knowledge questions
- 📦 Vector Store integration for domain-specific or learned content
- 🔄 Real-time streaming of node execution with LangGraph
- ✅ Clean extraction of answers (like summary only)

---

## 🛠️ Tech Stack

- Python 3.10+
- [LangGraph](https://github.com/langchain-ai/langgraph)
- [LangChain](https://github.com/langchain-ai/langchain)
- Pydantic
- Wikipedia API or LangChain tools
- Optional: Vector database (e.g., FAISS, ChromaDB)
