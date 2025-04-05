# 🧠 Medical Chatbot – AI-Powered Healthcare Q&A Assistant

This is an AI-driven **Medical Chatbot** that provides concise, context-aware answers to healthcare-related questions. Built with **Python**, **Flask**, **LangChain**, **GPT**, and **Pinecone**, the chatbot leverages medical documents and retrieval-augmented generation (RAG) to deliver accurate responses.

> ⚠️ **Disclaimer**: This chatbot is for educational and informational purposes only. It does **not** provide real medical advice, diagnosis, or treatment. Always consult a licensed healthcare professional.

---

## 💡 Features

- ✅ Question-answering assistant powered by GPT
- ✅ Uses retrieved context for accurate responses (RAG)
- ✅ Semantic search using Pinecone vector database
- ✅ Flask-based API server for frontend/backend integration
- ✅ Trained on medical documents (upload your own)
- ✅ Answers limited to **3 concise sentences**

---

## ⚙️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Python** | Programming language |
| **Flask** | Lightweight backend server |
| **LangChain** | Framework for connecting GPT with vector search |
| **OpenAI GPT** | Language model for generating responses |
| **Pinecone** | Vector database for semantic search |
| **FAISS (optional)** | Local alternative to Pinecone |

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/medical-chatbot.git
cd medical-chatbot

### 2.  Install Requriments**

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt

### 3. Run
Create .env file
```bash
python app.py




