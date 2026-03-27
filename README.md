# 🚀 Agentic RAG System

An **Agentic Retrieval-Augmented Generation (RAG)** system that combines LLMs with intelligent retrieval and tool usage to answer queries from documents.

---

## 📌 Overview

This project implements an **Agent-based RAG pipeline**, where:

* 📄 Documents are ingested and processed
* 🔍 Relevant context is retrieved using embeddings
* 🤖 An AI agent decides how to answer queries
* 🧠 LLM generates accurate, context-aware responses

Unlike traditional RAG, this system can:

* Use tools dynamically
* Decide when to retrieve information
* Improve reasoning and response quality

---

## 🏗️ Architecture

```
User Query
    ↓
Agent (LLM)
    ↓
Retriever (Vector DB)
    ↓
Relevant Documents
    ↓
LLM Response Generation
```

---

## ⚙️ Features

* ✅ Agent-based decision making
* ✅ Retrieval-Augmented Generation (RAG)
* ✅ PDF / document ingestion
* ✅ Vector embeddings for semantic search
* ✅ Modular and extensible design
* ✅ Supports OpenAI models

---

## 📂 Project Structure

```
Agentic_Rag.ipynb   # Main notebook implementation
data/               # Input documents (PDFs, text, etc.)
embeddings/         # Stored vector embeddings
utils/              # Helper functions (if any)
```

---

## 🧰 Tech Stack

* Python 🐍
* OpenAI API
* Vector Database (FAISS / Chroma)
* LangChain / custom agent logic
* Jupyter Notebook

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Praveenravva61/Agentic_Rag_system
cd Agentic_Rag_system
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Set your API key

```bash
export OPENAI_API_KEY=your_api_key_here
```

(Windows)

```bash
set OPENAI_API_KEY=your_api_key_here
```

---

## ▶️ Usage

Run the notebook:

```bash
jupyter notebook Agentic_Rag.ipynb
```

Steps inside notebook:

1. Load documents
2. Create embeddings
3. Initialize retriever
4. Run agent
5. Ask questions

---

## 💡 Example Queries

* "What is the coverage in this insurance document?"
* "Summarize the key points of the PDF"
* "What are the exclusions mentioned?"

---

## 🧠 How It Works

1. Documents are converted into embeddings
2. Stored in a vector database
3. Agent receives user query
4. Decides whether to retrieve context
5. Retrieves relevant chunks
6. LLM generates final response

---

## 🔥 Future Improvements

* Add UI (Gradio / Streamlit)
* Multi-document reasoning
* Tool integration (search, APIs)
* Memory-enabled agents
* Real-time data retrieval

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

* Open issues
* Submit pull requests
* Suggest improvements

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 🙌 Acknowledgements

* OpenAI
* LangChain ecosystem
* RAG research community

---

## 👨‍💻 Author

**Praveen Ravva**

---

⭐ If you found this useful, consider giving it a star!
