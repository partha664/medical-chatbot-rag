# medical-chatbot-rag
AI-powered Medical Chatbot using RAG, HuggingFace, FAISS and Gradio
#  AI-Powered Medical Chatbot (RAG Architecture)

## Overview
A fully local Knowledge-based Medical Assistant built using 
RAG (Retrieval-Augmented Generation) architecture — no external APIs required.

## Tech Stack
- **LLM:** HuggingFace DialoGPT (fine-tuned on medical data)
- **Embeddings:** SentenceTransformer
- **Vector Store:** FAISS (similarity search)
- **Architecture:** RAG (Retrieval-Augmented Generation)
- **UI:** Gradio
- **Language:** Python

## Features
- Fine-tuned LLM on medical datasets
- FAISS-powered vector similarity search
- Context-aware clinical query responses
- Fully local — runs without internet/API

## How to Run
pip install -r requirements.txt
python app.py
