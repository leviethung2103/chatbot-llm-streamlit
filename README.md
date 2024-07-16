# Web Chatbot using RAG

This project implements a web-based chatbot using the LangChain framework.

Models:
- phi-3 model as llm 
- chromadb as vectorDB
- streamlit as frontend

Tools:
- Ollama
- Docker

This chatbot can be interacted with users 

## Features
- Web-based interface
- Document loading
- Text Splitting
- Vector store creation
- RAG 

## Details
- Document Loading: In order to comprehend the context of the conversation, the chatbot loads content from a designated website. 
- Text splitting: To facilitate processing, the website's information is divided into manageable parts. 
- Text segments are transformed into vectors and saved in a vector store for quick and easy access.
- Retrieval-Augmented Generation, or RAG, is a technique the chatbot utilizes to raise the caliber of its responses. The two primary elements of RAG are a conversation and a retriever chain. 


## Setup

Use these procedures to manage the project:

1. Install Olllama on your computer and choose an LLM to utilize.

2. Install the project's necessary dependencies:
```bash
pip install streamlit langchain chromadb huggingface_hub beautifulsoup4
```

3. Launch the app Streamlit:
```
streamlit run src/app.py
```

4. Enter a website URL in the sidebar of the Streamlit app once it has launched to begin a conversation with the chatbot.
