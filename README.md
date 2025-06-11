# AIVA

# 🧠 AIVA - Autonomous Interactive Virtual Assistant (Phase 1)

> Persistent, intelligent, evolving assistant with real-time knowledge.

---

## 🌟 Overview

AIVA is a next-gen AI companion that remembers you, understands emotion, and learns over time. This repo hosts **Phase 1**, focused on the core conversational brain.

---

## 🚀 Features (Phase 1)
- Text-based conversational UI
- Real-time web search via RAG (Retrieval-Augmented Generation)
- Long-term memory using vector embeddings
- FastAPI + LLM backend with LoRA-tuned model
- ChromaDB memory store
- Modular, extensible architecture

---

## 🧱 Tech Stack

| Layer         | Tech                       |
|--------------|----------------------------|
| Frontend     | Next.js (React + Tailwind) |
| Backend      | FastAPI (Python 3.10)      |
| LLM          | LLaMA 3 / Mistral (HF)     |
| Memory       | ChromaDB                   |
| Search       | Brave Search API / Serper  |
| Hosting      | Vercel + Render / AWS      |

---

## 🛠️ Getting Started

```bash
# Clone repo
git clone https://github.com/saipanindra7/AIVA.git && cd AIVA

# Setup backend
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

# Setup frontend
cd ../frontend
npm install
npm run dev
