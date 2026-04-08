# 🚀 Flowise RAG Chatbot

A Retrieval-Augmented Generation (RAG) chatbot built using Flowise that enables intelligent document-based question answering using embeddings, vector search, and conversational AI.

---

## 📌 Overview

This project demonstrates how to build a RAG pipeline using Flowise by combining:

- Document ingestion and chunking
- Embedding generation (Google Gemini)
- Vector storage and retrieval
- Conversational AI using Mistral
- Chat interface for user interaction

---

## 🧠 Architecture

### 🔹 RAG Pipeline
![RAG Pipeline](flowise-rag-pipeline.png.png)

### 🔹 Chat Interface
![Chat UI](flowise-chat-ui.jpeg.jpeg)

---

## ⚙️ Tech Stack

- Flowise
- Mistral AI (LLM)
- Google Gemini Embeddings
- In-Memory Vector Store
- Conversational Retrieval QA Chain

---

## 🔄 Workflow

1. Upload document (PDF/DOCX)
2. Split text using Recursive Character Text Splitter
3. Generate embeddings via Google Gemini
4. Store embeddings in vector database
5. Retrieve relevant chunks using similarity search
6. Pass context to Mistral LLM
7. Generate responses via chat interface

---

## 🛠️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/harmeet11009-debug/flowise-rag-chatbot.git
cd flowise-rag-chatbot

## 📦 Flowise Configuration

You can directly import the pre-built Flowise pipeline using the provided JSON file:

*File:* flowise-rag-flow.json

### Steps to Import:
1. Open Flowise
2. Click *Import*
3. Upload the JSON file
4. Run the flow
