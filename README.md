# 📄 LegalRAG: Retrieval-Augmented Contract Clause Analyzer

LegalRAG is a Streamlit-powered application that enables users to upload contract PDFs and ask context-aware questions using a Retrieval-Augmented Generation (RAG) pipeline powered by OpenAI and FAISS.

---

## 🚀 Features

- 🔍 Upload any contract or legal PDF  
- 🤖 Ask natural language questions (e.g., "What are the termination clauses?")  
- 📚 Retrieves relevant chunks using Sentence-BERT and FAISS  
- 🧠 Generates answers using OpenAI GPT-4  
- 💡 Displays source document chunks used in each response  
- 🧼 Clean interface built with Streamlit  

---

## 🧰 Tech Stack

- **Python**  
- **Streamlit** – UI  
- **LangChain** – Orchestration  
- **OpenAI API** – Generation  
- **FAISS** – Vector store  
- **HuggingFace Transformers** – Sentence embeddings  
- **PyPDFLoader** – Document parsing  

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/legalrag.git
cd legalrag
python -m venv env
source env/bin/activate  # On Windows use `env\\Scripts\\activate`
pip install -r requirements.txt
