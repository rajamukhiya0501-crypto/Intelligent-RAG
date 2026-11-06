# Intelligent RAG – HR Policy Chatbot

An AI-powered Retrieval-Augmented Generation (RAG) chatbot that answers employee questions using company HR policy documents.

## Project Overview

Employees often need to search through multiple HR documents to find information about company policies, leave rules, salary, benefits, and other workplace guidelines.

This project uses RAG to retrieve relevant information from HR documents and generate context-aware answers using a Large Language Model (LLM).

## Problem Statement

Build an intelligent HR assistant that can understand employee questions, retrieve relevant information from company documents, and provide accurate answers based on the available knowledge base.

## Key Features

- **Document Loading:** Reads company HR policy PDF documents.
- **Text Chunking:** Splits documents into smaller text chunks.
- **Embeddings:** Converts text into numerical vectors.
- **Vector Search:** Retrieves relevant document chunks.
- **LLM Integration:** Uses Groq to generate answers.
- **Context-Aware Responses:** Answers questions using retrieved HR information.
- **Out-of-Scope Handling:** Handles questions unrelated to HR policies.

## RAG Architecture

```text
HR Policy PDF Documents
          |
          v
    Document Loading
          |
          v
      Text Chunking
          |
          v
       Embeddings
          |
          v
     Vector Database
          |
          v
   Relevant Retrieval
          |
          v
    Context + Question
          |
          v
       Groq LLM
          |
          v
    Generated Answer
```

## Technology Stack

- Python
- LangChain
- Groq API
- Embedding Models
- Vector Database
- Pandas
- Jupyter Notebook

## Project Structure

```text
Intelligent-RAG/
│
├── code.ipynb
├── .gitignore
├── README.md
└── .env                 # Keep private
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/rajamukhiya0501-crypto/Intelligent-RAG.git
```

### 2. Open the project

```bash
cd Intelligent-RAG
```

### 3. Install dependencies

Install the Python packages required by the notebook.

### 4. Configure API credentials

Create a `.env` file and configure your Groq API key using the environment variable expected by the notebook.

Never upload API keys or `.env` files to GitHub.

### 5. Run the notebook

Open `code.ipynb` in Jupyter Notebook or VS Code and execute the cells in order.

## Learning Outcomes

Through this project, I explored:

- Retrieval-Augmented Generation (RAG)
- Document processing
- Text chunking
- Semantic embeddings
- Vector similarity search
- LLM integration
- Context-based question answering

## Author

**Raja**

GitHub: [@rajamukhiya0501-crypto](https://github.com/rajamukhiya0501-crypto)

---

*Built as part of my Generative AI learning journey.*
