# 📄 Resume Ranking Web App

A smart web application built with Flask that ranks uploaded resumes based on how closely they match a given job description using NLP and cosine similarity.

---

## 🚀 Features

- Upload multiple resumes (PDF)
- Paste a job description
- NLP-based matching using spaCy (lemmatization, stopword removal)
- Ranks resumes using **TF-IDF + Cosine Similarity**
- View sorted scores in a neat UI

---

## 🛠️ Tech Stack

- Python (Flask)
- HTML, CSS
- PDF Text Extraction: `PyMuPDF`
- NLP: `spaCy`
- Similarity: `scikit-learn` (TF-IDF + cosine similarity)

---

## 📦 Setup Instructions

### 1. Clone this Repository

```bash
git clone https://github.com/your-username/resume-ranker.git
cd resume-ranker
