# 📘 Product Manual Assistant (RAG + ScaleDown)

A simple **Streamlit-based RAG application** that allows users to:

- Upload any Product Manual PDF  
- Automatically extract text  
- Split it into chunks  
- Store embeddings in a FAISS vector database  
- Retrieve relevant sections for user questions  
- Compress context using ScaleDown  
- Display answers with source snippets  

---

## 🚀 Features

✅ Upload Product Manual (PDF)  
✅ Semantic Search using FAISS  
✅ Chunk-based Retrieval (RAG Pipeline)  
✅ Context Compression using ScaleDown  
✅ Streamlit UI for interactive Q&A  
✅ Shows retrieved chunks + compression metrics  

---

## 🛠 Tech Stack

- **Python**
- **Streamlit**
- **FAISS Vector Store**
- **PDF Text Extraction (PyMuPDF)**
- **ScaleDown Compressor**
- **Embedding Model (Sentence Transformers)**

---

## 📂 Project Structure

```bash
product-manual-assistant/
│
├── app.py                  # Main Streamlit App
├── rag/
│   ├── pdf_loader.py        # PDF text extraction
│   ├── chunker.py           # Chunking logic
│   ├── retriever.py         # FAISS retriever
│   └── generator.py         # Answer generation (basic)
│
├── scaledown/
│   └── compressor.py        # Context compression module
│
├── dashboard/
│   └── metrics.py           # Manual statistics
│
├── sample_data/
│   └── sample_manual.txt
│
├── requirements.txt
└── README.md

⚡ Quick Start
1️⃣ Create Virtual Environment
bash
Copy code
python -m venv .venv
Activate:

bash
Copy code
.venv\Scripts\activate
2️⃣ Install Requirements
bash
Copy code
pip install -r requirements.txt
3️⃣ Run Streamlit App
bash
Copy code
streamlit run app.py
💬 Example Questions
Try asking:

How do I load paper in the printer?

How do I print on envelopes?

How can I improve print quality?

What should I do if paper jams?

⚠ Notes
This project uses a basic extractive answer generator.

It does not require any paid API key.

Answers are generated from retrieved manual chunks.

📌 Future Improvements
Add better LLM-based answer generation

Add page-level citations

Improve chunking + ranking

Deploy on Streamlit Cloud

👨‍💻 Author
Built by Dev Verma
Project: Product Manual Assistant (RAG + ScaleDown)
