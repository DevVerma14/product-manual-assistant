# 📘 Product Manual Assistant (RAG + ScaleDown)

A modern **Streamlit-based Retrieval-Augmented Generation (RAG)** application that allows users to upload any **Product Manual PDF** and instantly ask questions from it.

This project combines:

- **PDF Text Extraction**
- **Semantic Search with FAISS**
- **Chunk-based Retrieval**
- **ScaleDown Context Compression**
- **Interactive Streamlit Dashboard UI**

---

## 🚀 Features

✅ Upload any Product Manual (PDF)  
✅ Automatic PDF text extraction  
✅ Chunking + Vector Indexing using FAISS  
✅ Semantic Retrieval of relevant manual sections  
✅ Context Compression using ScaleDown  
✅ Clean Answer Display with Retrieved Context  
✅ Modern UI with Metrics + Chunk Expanders + History  

---

## 🛠 Tech Stack

- **Python**
- **Streamlit**
- **FAISS Vector Store**
- **Sentence Transformers Embeddings**
- **PyMuPDF (PDF Loader)**
- **ScaleDown Compressor**

---

## 📂 Project Structure

```bash
product-manual-assistant/
│
├── app.py                  # Main Streamlit App
├── rag/
│   ├── pdf_loader.py        # PDF text extraction
│   ├── chunker.py           # Text chunking logic
│   ├── retriever.py         # FAISS semantic retriever
│   └── generator.py         # Extractive answer generator
│
├── scaledown/
│   └── compressor.py        # ScaleDown context compression
│
├── dashboard/
│   └── metrics.py           # Manual statistics module
│
├── sample_data/
│   └── sample_manual.txt
│
├── requirements.txt
└── README.md

---

## ⚡ Quick Start
1️⃣ Clone Repository
git clone https://github.com/<your-username>/product-manual-assistant.git
cd product-manual-assistant
2️⃣ Create Virtual Environment
python -m venv .venv
3️⃣ Activate Environment
Windows (PowerShell)
.venv\Scripts\activate
Mac/Linux
source .venv/bin/activate
4️⃣ Install Dependencies
pip install -r requirements.txt
5️⃣ Run Streamlit App
streamlit run app.py
App will open in browser at:
http://localhost:8501

---

## 🎥 Demo Video
📌 Watch the working demo here:
➡️ (Add your demo video link here)

Example:

md
Copy code
https://drive.google.com/file/d/XXXX/view
or

md
Copy code
https://youtu.be/XXXX
---

## 💬 Example Questions
Try asking:

How do I load paper in the printer?

How do I print on envelopes?

How can I print on both sides of the paper?

What should I do if paper jams?

How do I clean print cartridges?

---

## ⚠ Notes
This assistant uses a basic extractive answer generator.

It does not require any paid API key.

Answers are generated directly from retrieved manual chunks.

---

## 📌 Future Improvements
Add page-level citations

Integrate a full LLM-based answer generator

Support multiple manuals at once

Deploy on Streamlit Cloud

---

## 👨‍💻 Author
Built by Dev Verma
Project: Product Manual Assistant (RAG + ScaleDown)

