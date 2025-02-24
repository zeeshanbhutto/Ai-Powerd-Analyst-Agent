# AI-Powered Research Analyst Agent

## 📌 Overview
The **AI-Powered Research Analyst Agent** is an intelligent system designed to analyze and retrieve relevant information from PDFs using advanced AI techniques. This project integrates **Retrieval-Augmented Generation (RAG)** with **Ollama LLM**, **FAISS for embedding storage**, and **Sentence Transformers** to generate insightful responses based on uploaded documents.

## ✨ Features
- **PDF Processing**: Extracts and chunks text from PDFs.
- **Semantic Search**: Uses **FAISS** to store and retrieve relevant document embeddings.
- **AI-Powered Responses**: Generates context-aware answers using **Ollama's LLM**.
- **Efficient Embeddings**: Utilizes **Sentence Transformers** for high-quality vector representations.
- **Query-Based Analysis**: Finds the most relevant text snippets from stored PDFs based on user queries.

## 🏗️ Project Structure
```
📂 ai-powered-analyst-agent
│── 📜 README.md  # Project Documentation
│── 📜 requirements.txt  # Required dependencies
│── 📜 embedding_store.py  # FAISS-based embedding storage
│── 📜 pdf_loader.py  # PDF text extraction and chunking

```

## 🛠️ Installation
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/ai-powered-analyst-agent.git
cd ai-powered-analyst-agent
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Download and Run Ollama LLM
Ensure you have **Ollama** installed and the required model downloaded.
```bash
ollama pull gemma2:2b  # Download the model
```

## 🚀 Usage
### 1️⃣ Store Embeddings from PDFs
Run the script to extract text and store embeddings in FAISS.
```bash
python main.py --store sample.pdf
```

### 2️⃣ Retrieve Similar Content and Get AI Responses
```bash
python main.py --query "Explain AI in simple terms."
```

## 📚 Technologies Used
- **Python** (Core scripting language)
- **FAISS** (Efficient similarity search)
- **Ollama** (LLM for response generation)
- **PyMuPDF** (PDF text extraction)
- **Sentence Transformers** (Embedding generation)

## 📌 Future Enhancements
- ✅ Add support for multiple document formats (Word, TXT, etc.)
- ✅ Integrate a web-based UI for querying
- ✅ Deploy as a FastAPI-powered REST API

## 🤝 Contributing
Contributions are welcome! Feel free to fork, raise issues, or submit PRs.

## 🛡️ License
This project is licensed under the **MIT License**.

---
🚀 **Developed by [Your Name](https://github.com/zeeshanbhutto)**

