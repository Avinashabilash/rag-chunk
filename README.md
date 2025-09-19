# 🧠 Retrieval-Augmented Generation (RAG) Project

[![Python](https://img.shields.io/badge/python-3.8+-blue?logo=python)](https://www.python.org/) 
[![PyTorch](https://img.shields.io/badge/PyTorch-1.15-red?logo=pytorch)](https://pytorch.org/) 
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

**RAG: Real-time Document Question Answering System**  
Python | PyTorch | FAISS | Sentence Transformers

<p align="center">
  <img src="assets/rag_demo.gif" alt="RAG Demo" width="600"/>
</p>

A project implementing a **Retrieval-Augmented Generation (RAG)** system to answer questions based on documents (PDFs or text) using retrieval and language generation.

---

## 📖 Table of Contents
- [Project Overview](#project-overview)  
- [Goal](#goal)  
- [Objectives](#objectives)  
- [Methodology](#methodology)  
- [Key Features](#key-features)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Results](#results)  
- [File Structure](#file-structure)  
- [Future Enhancements](#future-enhancements)  
- [License](#license)  
- [Contributing](#contributing)  

---

## 🔍 Project Overview
RAG combines **document retrieval** and **language generation** to answer user queries efficiently.  
It extracts relevant text chunks from uploaded documents and generates **context-aware answers** using a Transformer model.

---

## 🎯 Goal
To build an AI-powered system that provides **accurate answers from documents** in real-time, reducing manual reading effort.

---

## 📝 Objectives
1. Extract and preprocess text from PDFs and text files.  
2. Split documents into meaningful chunks for semantic retrieval.  
3. Generate embeddings using **Sentence Transformers**.  
4. Store embeddings in **FAISS** for fast similarity search.  
5. Use a language model to generate informative responses.  
6. Provide an interactive query interface for real-time interaction.

---

## 🛠️ Methodology

### Data Preprocessing
- Extract text from PDFs with `pdfplumber` and `PyPDF2`  
- Clean text (remove special characters, normalize spaces)  
- Split text into chunks for embedding

### Embedding & Retrieval
- Use **Sentence Transformers** to create vector embeddings  
- Store embeddings in **FAISS** for efficient semantic search  
- Retrieve top-k relevant chunks for a user query

### Response Generation
- Combine retrieved chunks with a query  
- Generate answers using a language model (GPT/transformer-based)  

### Evaluation
- Relevance of retrieved chunks  
- Accuracy and coherence of generated answers  
- Query response time  

---

## ✨ Key Features
- PDF and text document processing  
- Semantic chunking of documents  
- FAISS-based fast retrieval  
- Transformer-based response generation  
- Interactive terminal/Jupyter interface  
- Colored and formatted output for readability  

---

## ⚙️ Installation

### Prerequisites
- Python 3.8+  
- pip package manager  

### Setup
```bash

### 🤝 Contributing

- Fork the repository

- Create a new branch (git checkout -b feature-name)

- Commit your changes (git commit -m "Add feature")

- Push to the branch (git push origin feature-name)

- Open a Pull Request
- git clone https://github.com/Avinashabilash/rag-chunk.git
