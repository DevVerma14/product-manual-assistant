# 📘 Product Manual Assistant (RAG + ScaleDown)

A Streamlit-based **RAG application** that allows users to upload any Product Manual PDF and ask questions from it.

It uses:

- PDF Text Extraction  
- Chunking + FAISS Semantic Search  
- Context Compression using ScaleDown  
- Answer Generation from Retrieved Manual Sections  

---

## 🎥 Demo Video

📌 Watch Project Demo Here:  
👉 https://github.com/user-attachments/assets/20637079-b4cb-41a8-ba03-a9ab6505d208

---

## 🚀 Features

✅ Upload Product Manual (PDF)  
✅ Extract text automatically (PyMuPDF)  
✅ Chunk-based Retrieval (RAG Pipeline)  
✅ Semantic Search using FAISS  
✅ Context Compression using ScaleDown  
✅ Streamlit UI for interactive Q&A  
✅ Displays retrieved chunks + compression metrics  

---

## 🛠 Tech Stack

- **Python**
- **Streamlit**
- **FAISS Vector Store**
- **PDF Text Extraction (PyMuPDF)**
- **ScaleDown Compressor**
- **Sentence Transformers Embeddings**

---

## 📂 Project Structure

```bash
product-manual-assistant/
│
├── app.py                  # Main Streamlit Application
│
├── rag/
│   ├── pdf_loader.py        # Extracts text from PDF
│   ├── chunker.py           # Splits text into chunks
│   ├── retriever.py         # FAISS semantic retriever
│   └── generator.py         # Extractive answer generator
│
├── scaledown/
│   └── compressor.py        # Context compression module
│
├── dashboard/
│   └── metrics.py           # Manual statistics + token metrics
│
├── sample_data/
│   └── sample_manual.txt    # Example manual text
│
├── requirements.txt
└── README.md
```
---

## ⚡ Quick Start
1️⃣ Clone Repository

git clone https://github.com/DevVerma14/product-manual-assistant.git

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

## 💬 Example Questions
Try asking:

How do I load paper in the printer?

How do I print on envelopes?

What should I do if paper jams?

How can I improve print quality?

---

## ⚠ Notes
This project uses a basic extractive answer generator

It does NOT require any paid API key

Answers are generated directly from retrieved manual chunks

---

## 📌 Future Improvements
Add page-level citations

Integrate full LLM-based answer generation

Improve chunk ranking

Deploy on Streamlit Cloud

---

## 👨‍💻 Author
Built by Dev Verma

Project: Product Manual Assistant (RAG + ScaleDown)
