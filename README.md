# 🧠 Job–Resume Matcher

An NLP-based tool that compares resumes with job descriptions using **BERT embeddings** and **spaCy** for text and entity extraction.

---

## 🚀 Features
- Extract text from PDF/DOCX resumes  
- Identify entities & skills using spaCy  
- Compute semantic similarity with Sentence-BERT  
- Output a job–resume match score

---

## 🧩 Tech Stack
**Python**, **spaCy**, **Sentence-Transformers**, **PyMuPDF**, **docx2txt**, **NumPy**, **Torch**

---

## ⚙️ Setup
```bash
git clone https://github.com/<your-username>/Job-Resume-Matcher.git
cd Job-Resume-Matcher
pip install -r requirements.txt
python -m spacy download en_core_web_sm
