# Medically Tuned AI Powered Chatbot using RAG

Welcome to the AI-Powered Medical Chatbot repository! This project offers an intelligent assistant capable of answering medically relevant questions by combining the power of semantic search with a cutting-edge Large Language Model (LLM). It is designed to aid users in accessing concise and reliable medical information derived from trusted literature.

## 🧠 Overview

This chatbot is built on a Retrieval-Augmented Generation (RAG) architecture, which retrieves relevant context from a vectorized document database and uses an instruction-tuned language model to generate accurate, context-aware responses. It features:
- Vectorization of medical PDFs using sentence-transformer embeddings.
- LLM-based question answering using Hugging Face’s `mistralai/Mistral-7B-Instruct` model.
- Streamlit-based web interface and CLI terminal interface.
- Strict domain filtering to allow only medical queries.

## 🚀 Features

- **RAG Architecture**: Combines semantic retrieval with generative response capabilities for reliable medical Q&A.
- **Medical Document Parsing**: Loads and splits medical PDFs into manageable chunks for indexing.
- **Vector Store with FAISS**: Efficient retrieval using FAISS-based similarity search on embedded document chunks.
- **Domain-Specific Filtering**: Ensures that only medically relevant questions are processed; all others are respectfully declined.
- **Interactive UI**: Streamlit-based chatbot interface with chat memory and source document expansion.
- **Command-Line Interface**: For terminal-based usage, allowing testing and debugging of LLM responses.

## 🧪 Technologies Used

- **LangChain** – Framework for RAG and LLM integration.
- **FAISS** – Vector similarity search for document retrieval.
- **sentence-transformers** – For generating semantic embeddings of PDF content.
- **Hugging Face Hub** – Hosting and calling the Mistral-7B-Instruct model via API.
- **Streamlit** – Frontend for user interaction.
- **Python** – Core development language.

## Getting Started

### Clone the Repository

```bash
git clone

