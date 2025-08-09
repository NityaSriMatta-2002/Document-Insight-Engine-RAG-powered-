# Document Insight Engine

**Document Insight Engine** is an AI-powered question-answering system that uses Retrieval-Augmented Generation (RAG) to extract meaningful answers from PDF documents. It combines document embeddings, vector search, and GPT language models to let users ask questions in natural language and get accurate answers based on PDF content.

## Features

- Load and process PDF documents  
- Split documents into chunks for embedding  
- Generate semantic embeddings using sentence-transformer models  
- Store and search embeddings with Chroma vectorstore  
- Retrieve relevant context chunks based on user queries  
- Generate natural language answers using OpenAI GPT models  
- Interactive command-line interface for asking questions  

## How It Works
Loads and splits PDFs into chunks.

Creates embeddings using HuggingFace sentence-transformers.

Stores embeddings in Chroma vectorstore for similarity search.

Retrieves relevant chunks when a query is asked.

Feeds context and question to OpenAI GPT to generate answers.

## Technologies
Python 3.11+

LangChain

HuggingFace Sentence-Transformers

Chroma Vectorstore

OpenAI GPT-4o-mini


