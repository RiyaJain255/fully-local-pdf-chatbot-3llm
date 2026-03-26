# Fully Local PDF Chatbot using 3 LLMs

An AI-powered chatbot that can answer questions from PDF documents completely offline using multiple Large Language Models (LLMs).  
This project uses Retrieval Augmented Generation (RAG) to provide accurate answers based on document content while ensuring data privacy.

---

## Features

- Works completely offline (no paid API required)
- Supports multiple LLMs:
  - Ollama (Gemma / Mistral)
  - WebLLM (Phi-3)
  - Chrome Built-in AI (Gemini Nano)
- Chat with PDF documents
- Retrieval Augmented Generation (RAG)
- Ensures data privacy (files never leave your system)
- Runs locally on your laptop

---

## Tech Stack

- Node.js
- React
- LangChain
- Ollama
- WebLLM
- Vector Embeddings
- JavaScript / TypeScript

---

## LLMs Used

1. Gemma 2B (via Ollama)
2. Mistral 7B (via Ollama)
3. Phi-3 (via WebLLM)
4. Gemini Nano (via Chrome Built-in AI)

---

## How It Works (Architecture)

1. User uploads a PDF
2. Text is extracted from the document
3. Text is split into smaller chunks
4. Chunks are converted into embeddings (vector format)
5. Relevant chunks are retrieved based on user query
6. Selected LLM generates the final answer

This approach is called **Retrieval Augmented Generation (RAG)**.

---

---

## Advantages

- No internet required
- No API cost
- Secure document processing
- Supports multiple LLMs
- Fast local inference

---

## Use Cases

- Study assistant
- Research paper summarization
- Document Q&A
- Private company document analysis
- Notes understanding

---

## Future Improvements

- Add more LLM models
- Improve UI design
- Add support for DOCX files
- Cloud deployment option
- Chat history saving

---

## Acknowledgement

Base project inspired by open-source work and extended to support multiple LLMs and local RAG pipeline.
