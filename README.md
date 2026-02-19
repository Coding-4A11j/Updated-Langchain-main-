# Updated-Langchain


RAG Chatbot using LangChain

An intelligent Retrieval-Augmented Generation (RAG) chatbot built using LangChain, LLMs, and Vector Databases.
This chatbot can answer questions from custom documents by combining semantic search with powerful language models.

🚀 Features

🔎 Document-based Question Answering (PDF, TXT, Web)

🧠 RAG Architecture (Retriever + LLM)

⚡ Fast Vector Search (FAISS / ChromaDB)

🌐 Streamlit UI for interactive chat

🔐 Secure API Key Management with .env

📦 Modular & Scalable Project Structure

🏗️ Tech Stack

LangChain

OpenRouter / OpenAI / Groq LLM

FAISS / ChromaDB (Vector Store)

HuggingFace Embeddings

Streamlit (Frontend UI)

Python 3.10+

🧩 Architecture

User Query → Embed Query → Retrieve Relevant Chunks →
Send Context + Query to LLM → Generate Context-Aware Response

📂 Project Structure
├── app.py                # Streamlit UI
├── rag_pipeline.py       # RAG logic
├── vector_store/         # FAISS or Chroma DB
├── data/                 # Documents
├── .env                  # API keys
├── requirements.txt
