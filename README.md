# 🩺 MediBot - Medical PDF Question Answering Bot

MediBot is an AI-powered chatbot that can answer questions based on medical PDF documents. Built using **Hugging Face Transformers**, **LangChain**, **FAISS**, and **Streamlit**, this app allows users to interactively query the contents of a medical document with accurate and context-based responses.

---

## 💡 Features

- 📄 Ingests and understands medical PDF documents
- 🧠 Converts text to embeddings using `sentence-transformers/all-MiniLM-L6-v2`
- 🗃️ Stores vectors in FAISS for fast semantic search
- 🤖 Uses Hugging Face’s `mistralai/Mistral-7B-Instruct-v0.3` model for intelligent responses
- 💬 Provides a clean, interactive UI with Streamlit
- 🔐 Secure model access via Hugging Face API token

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit** – for UI
- **LangChain** – for building QA chains
- **FAISS** – for vector storage and retrieval
- **Hugging Face Inference Endpoint** – for language model interaction
- **dotenv** – for managing secrets like API keys

---

## 🚀 How It Works

1. **PDF is processed** to extract text.
2. **Text is embedded** using HuggingFace Sentence Transformers.
3. **Embeddings are stored** in FAISS vector database.
4. **User prompt** is matched with most relevant document chunks.
5. **Mistral LLM** generates an answer using retrieved context.

---

## 📂 Folder Structure


