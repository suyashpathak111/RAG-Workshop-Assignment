# My RAG System

## Topic: Nike Marketing Strategies

## What I changed:

- Documents: Added 5 PDF case studies related to Nike’s marketing and brand positioning.

- Chunking: Used chunk_size=400 and chunk_overlap=50 for better context retention and summarization.

- Retrieval: Updated retriever settings to search_type="mmr", k=7, fetch_k=15, lambda_mult=0.8 for more relevant and detailed results.

## How to run:

1. Install requirements: pip install -r requirements.txt

2. Run: python RAG_Workshop_modified.py

## Test questions:

1. What is Nike as a brand known for ?

2. How did Nike use athlete endorsements to strengthen its brand image?

SYSTEM REQUIREMENTS:

Minimum 8GB RAM (16GB recommended for better performance)
At least 20GB free disk space for models and vector databases
Python 3.8+ installed
Stable internet connection for initial model downloads
Ollama installed (https://ollama.ai/)
phi3:mini model downloaded via: ollama pull phi3:mini
INSTALLATION STEPS:

Install Python 3.8+
Install Ollama from https://ollama.ai/
Run: ollama pull phi3:mini
Install required Python packages (see Part 0 below)
Create 'data' folder and add PDF documents


