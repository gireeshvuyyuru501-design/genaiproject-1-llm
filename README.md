# 🤖 Full-Stack GenAI Application | Custom ChatGPT with RAG

> Production-ready Full-Stack Generative AI application built using **LangChain**, **FastAPI**, **Hugging Face**, **Groq**, **OpenAI**, **FAISS**, and **Retrieval-Augmented Generation (RAG)**.

---

# 📖 Overview

This project demonstrates how to build an enterprise-grade ChatGPT-style application using modern Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), and vector search.

The application allows users to upload documents, perform semantic search, and receive context-aware responses powered by enterprise AI workflows.

---

# 🎯 Business Problem

Traditional chatbots:

- Cannot access private company documents
- Hallucinate frequently
- Lack contextual understanding
- Cannot answer organization-specific questions

Organizations require AI assistants capable of retrieving trusted enterprise knowledge while minimizing hallucinations.

---

# 💡 Solution

This application combines modern Generative AI technologies to deliver accurate, context-aware responses using enterprise Retrieval-Augmented Generation (RAG).

Key capabilities include:

- Document ingestion
- Embedding generation
- Vector similarity search
- Context-aware prompting
- Multi-LLM support
- FastAPI backend
- Semantic document retrieval

---

# 🏗️ Architecture

```
                     User
                       │
                       ▼
                React / Streamlit UI
                       │
                       ▼
                  FastAPI Backend
                       │
      ┌────────────────┼────────────────┐
      ▼                ▼                ▼
 LangChain         HuggingFace       Groq/OpenAI
      │
      ▼
 Document Processing
      │
      ▼
 Embeddings (FAISS)
      │
      ▼
 Vector Search
      │
      ▼
 LLM Response
```

---

# 🛠️ Tech Stack

## AI

- LangChain
- Hugging Face
- OpenAI
- Groq API
- FAISS
- RAG
- Prompt Engineering

## Backend

- Python
- FastAPI
- Pydantic
- SQLAlchemy

## Database

- PostgreSQL
- pgvector

## DevOps

- Docker
- GitHub Actions
- CI/CD

---

# ✨ Features

✅ Custom ChatGPT Interface

✅ Retrieval-Augmented Generation (RAG)

✅ Semantic Search

✅ Document Upload

✅ PDF Processing

✅ Vector Search

✅ FastAPI REST APIs

✅ Multi-LLM Support

✅ Enterprise AI Architecture

✅ Docker Deployment

---

# 📂 Project Structure

```
backend/

frontend/

database/

embeddings/

documents/

api/

services/

README.md
```

---

# ⚙️ Installation

```bash
git clone https://github.com/gireeshvuyyuru501-design/genaiproject-1-llm

cd genaiproject-1-llm

python -m venv .venv

pip install -r requirements.txt

uvicorn main:app --reload
```

---

# 📡 API Endpoints

| Method | Endpoint | Description |
|----------|----------------|-------------------------|
| POST | /chat | Chat with AI |
| POST | /upload | Upload Documents |
| GET | /documents | List Documents |
| POST | /embeddings | Generate Embeddings |
| GET | /health | Health Check |

---

# 📊 Project Highlights

- Enterprise Retrieval-Augmented Generation
- LangChain AI pipelines
- Multi-LLM architecture
- Hugging Face integration
- FAISS vector search
- FastAPI backend
- Docker-ready deployment
- Production AI workflow

---

# 🚀 Future Enhancements

- LangGraph Multi-Agent Workflow
- Model Context Protocol (MCP)
- LangSmith Observability
- Redis Caching
- Kubernetes Deployment
- Streaming Responses
- Pinecone Integration
- AWS Bedrock Deployment

---

# 👨‍💻 Author

**Girish V**

AI/ML Engineer | Generative AI | Agentic AI

📧 girishsap45@gmail.com

💼 LinkedIn:
https://www.linkedin.com/in/girish-genai-engineer

💻 GitHub:
https://github.com/gireeshvuyyuru501-design

---

# ⭐ Support

If you found this project helpful, please ⭐ Star the repository.
