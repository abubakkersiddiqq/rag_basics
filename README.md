# RAG Basics - Learning Playground

## What this is
A personal learning repo where I built a basic RAG pipeline 
from scratch - including the mistakes, fixes, and iterations.

## What I built
An end-to-end RAG pipeline that answers user questions 
from a given PDF document using retrieval + LLM generation.

## Stack
- Python
- LangChain + LangChain Community
- HuggingFace Embeddings (all-MiniLM-L6-v2)
- ChromaDB (vector store)
- OpenRouter API (LLM)
- Jupyter Notebook

## What I learned
- How chunking and chunk size affect retrieval quality
- How embeddings convert text into searchable vectors
- How retrieval + LLM generation work together in a RAG pipeline
- How prompt engineering controls LLM output format and tone

## What comes next
Building this into a deployed FastAPI service → semantic-search-api
