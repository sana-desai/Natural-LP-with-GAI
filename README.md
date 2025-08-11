# Natural-LP-with-GAI
Medical Assistance Project using NLP_RAG

End-to-end Retrieval-Augmented Generation (RAG) system that retrieves trusted medical context and generates grounded, explainable answers for clinical decision support.

## ✨ Highlights
- **Domain**: Healthcare AI & NLP
- **Stack**: Python, LangChain, Sentence Transformers, FAISS, LLaMA
- **Features**: context-aware responses, groundedness & relevance scoring, specialty model extensions
- **Compliance**: HIPAA/GDPR considerations (audit trails, source citations)

## 📂 Repo Contents
- `RAG_Healthcare_Notebook.ipynb` – full code notebook
- `RAG_Healthcare_Notebook.html` – HTML export (read-only preview)
- `images/architecture.png` – system architecture
- `images/infographic.png` – 1-page summary infographic
- `NLP_RAG_Healthcare_Assistant_Summary.pdf` – slide-style summary

## 🚀 Quickstart
```bash
# (1) create & activate a virtual env (recommended)
python -m venv .venv && source .venv/bin/activate  # Windows: .venv\\Scripts\\activate

# (2) install deps
pip install -r requirements.txt

# (3) run the notebook
jupyter notebook RAG_Healthcare_Notebook.ipynb
