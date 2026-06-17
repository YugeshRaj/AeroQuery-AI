# AeroQuery

AeroQuery is an intelligent document chatbot built using Retrieval-Augmented Generation (RAG). The application allows users to upload and query PDF documents in natural language, providing context-aware answers based on the content of the documents.

The system processes PDF files, splits them into semantic chunks, generates embeddings using Sentence Transformers, and stores them in a FAISS vector database for efficient similarity search. When a user asks a question, the most relevant document chunks are retrieved and provided to a Large Language Model (LLM) through Groq for accurate and context-grounded responses.

## Features

* PDF document ingestion and processing
* Recursive text chunking for optimal retrieval
* Sentence Transformer embeddings
* FAISS vector database integration
* Retrieval-Augmented Generation (RAG) pipeline
* Groq LLM integration for answer generation
* FastAPI backend APIs
* React + TypeScript frontend chat interface
* Source-aware responses from uploaded documents
* Scalable architecture for multi-document knowledge bases

## Tech Stack

### Backend

* Python
* FastAPI
* LangChain
* FAISS
* Sentence Transformers
* Groq API

### Frontend

* React
* TypeScript
* Vite
* Bootstrap / Tailwind CSS

## Workflow

PDF Documents → Text Chunking → Embeddings Generation → FAISS Vector Store → Similarity Retrieval → Groq LLM → User Response

## Use Cases

* Enterprise Knowledge Base Assistant
* Document Search and Analysis
* Aviation Manual Assistant
* Research Paper Q&A
* Internal Company Documentation Chatbot
* Educational Content Assistant
