# 🧠 Simple RAG Pipeline from Scratch

This repository demonstrates how to implement a **Retrieval-Augmented Generation (RAG)** pipeline **from scratch** — without relying on pre-built frameworks like LangChain or LlamaIndex.  
The goal is to help you understand the inner workings of RAG by breaking it into its core components: **document preprocessing, embedding generation, retrieval, and LLM-based generation**.

---

## 📌 Overview

**Retrieval-Augmented Generation (RAG)** enhances large language models by grounding their responses in **retrieved context** from an external knowledge source.  
This project walks through:

1. **Document ingestion** – Loading raw text data.
2. **Preprocessing** – Cleaning and chunking text.
3. **Embedding generation** – Using vector representations for similarity search.
4. **Vector search retrieval** – Finding relevant chunks for a query.
5. **LLM-based response generation** – Using retrieved context to answer questions.

---