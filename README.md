# Assignment_Cybernetyx_Generative-AI-Intern
RAG FastAPI Server with ChromaDB and Sentence-Transformers
This repository provides a lightweight FastAPI server implementation designed for retrieval-augmented generation (RAG) tasks. It enables document ingestion and querying using ChromaDB for document storage and sentence-transformers for embeddings.

Features
Document Ingestion: Ingests documents in PDF, DOC, DOCX, and TXT formats.
Embeddings with Sentence-Transformers: Uses sentence-transformers/all-MiniLM-L6-v2 for efficient embeddings generation.
Persistent Document Storage: Uses ChromaDB's persistent storage for document ingestion and retrieval.
Concurrency Handling: Non-blocking API endpoints with support for concurrent queries.
ngrok Integration: Enables public access to the server in Google Colab.
