# Jarbis – Offline Personal AI Assistant

**Jarbis** is a local-first, privacy-respecting personal AI assistant that runs 100% offline.  
It's built in Python and designed for full control, persistent memory, and smart automation.

---

## 🔧 Features (WIP)

- ✅ Fully local, no cloud dependency
- ✅ Persistent memory using MySQL (organized by date, topic, type)
- ✅ Flask-based API for local commands and memory updates
- 🔄 LLM integration via [Ollama](https://ollama.com/) or [llama.cpp](https://github.com/ggerganov/llama.cpp)
- 🔄 Agent orchestration planned (CrewAI or custom lightweight agent)
- 🔄 Goal: semantic memory and vector search integration

---

## 📁 Folder structure

- `app/`: core logic and backend
- `db/`: SQL schema
- `models/`: local LLM usage notes
- `docs/`: development notes, roadmap, ideas

---

## 📌 Project Goals

- Build a modular, privacy-first AI assistant
- Run LLMs locally using GPU (RTX 4060 Ti)
- Integrate function calling, memory, and agents in one clean flow
- Collaborate and learn with others building similar tools

---

## 💬 Want to Collaborate?

This is a solo learning project but I'm open to feedback, collaboration or just sharing progress.  
Check the [Issues](https://github.com/funeodo/jarbis-offline-personal/issues) or open a new one!

---

## 🧠 Tech Stack

- Python 3.x
- Flask
- MySQL
- Ollama / llama.cpp
- Possibly Supabase (if switching from MySQL for vector search)

---

## 📜 License

MIT License – feel free to fork, reuse and build on it.
