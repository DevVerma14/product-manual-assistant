# Product Manual Assistant using RAG + ScaleDown Compression

This project provides a Streamlit-based chatbot for uploading large product manuals (PDFs), retrieving relevant sections via semantic search (FAISS + embeddings), compressing context via a ScaleDown-like compressor, and answering user questions with source citations.

Quick start

1. Create and activate Python environment (3.8+)

```bash
python -m venv .venv
.\.venv\Scripts\activate
pip install -r requirements.txt
```

2. Run the Streamlit app

```bash
streamlit run app.py
```

Notes
- The generator attempts to use OpenAI if `OPENAI_API_KEY` is set; otherwise it uses a local extractive responder.
- Compression metrics are shown in the UI.
