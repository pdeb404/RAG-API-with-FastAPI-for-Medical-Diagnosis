# RAG API

This project implements a Retrieval-Augmented Generation (RAG) API using FastAPI, ChromaDB, and Ollama.

The API accepts user questions, retrieves relevant context from a local knowledge base, and generates accurate answers using a locally running language model.

## Tech Stack
- Python
- FastAPI
- ChromaDB (vector database)
- Ollama (local LLM runtime)

## Project Goal
To understand how modern AI systems combine document retrieval with language models to provide accurate, context-aware answers.

## Environment Setup

This project uses Python for the API layer and Ollama to run a local language model.

- Python is used to build the FastAPI backend and handle embeddings.
- Ollama runs a local LLM, avoiding cloud APIs and external costs.
- The tinyllama model is used for lightweight local inference.

Before running the API, Python and Ollama must be installed and Ollama should be running in the background.
