# AI-Powered PDF Querying and Summarization with FAISS, LangChain, Ollama, and Hugging Face

This repository contains multiple implementations that leverage AI technologies to perform **PDF querying and summarization**. The approaches demonstrated in this project utilize state-of-the-art tools such as **FAISS**, **LangChain**, **Ollama**, and **Hugging Face** to extract and analyze content from PDF files, providing contextual answers and summaries.

## Features
- **PDF Text Extraction**: Extracts text from PDF documents using `PyPDF2` or `SimpleDirectoryReader` from `LlamaIndex`.
- **Embedding-based Search**: Uses Hugging Face embeddings for semantic search and FAISS for efficient similarity search.
- **Advanced Querying**: Leverages LangChain, Hugging Face, and Ollama's models for contextual question answering and document summarization.
- **Multi-library Integration**: Combines several powerful AI tools to extract insights from PDF documents in real-time.
  
## Libraries and Tools Used
- **FAISS**: A library for efficient similarity search using embeddings.
- **LangChain**: A framework for building applications that interact with language models, and handle document loading, splitting, and querying.
- **Ollama**: A powerful LLM for advanced query answering.
- **Hugging Face**: For embedding models and pre-trained transformers, such as `all-MiniLM-L6-v2`, `BAAI/bge-large-en-v1.5`, and question-answering models like `deepset/roberta-base-squad2`.

## Requirements

- Python 3.7+
- Install the following dependencies:
  
```bash
pip install faiss-cpu langchain transformers huggingface_hub PyPDF2
pip install llama-index llama-index-embeddings-huggingface llama-index-llms-huggingface
pip install colab-xterm
pip install ollama
