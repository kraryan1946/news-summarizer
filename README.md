# 📰 News Summarizer App

A lightweight and efficient AI-powered web application built with Streamlit that automatically summarizes long news articles.  
Powered by the DistilBART CNN model from Hugging Face, the app lets you paste any article, choose summary length, and instantly generate a concise summary.

---

## 🚀 Features

### 🔹 AI Text Summarization
Uses the model **sshleifer/distilbart-cnn-12-6**, optimized for summarizing news articles.

### 🔹 Customizable Summary Length
Choose the summary style:
- Short  
- Medium  
- Long  

### 🔹 Reading Time Estimation
Calculates how long the original article takes to read.

### 🔹 Copy or Download Summary
- Download as `.txt`  
- Copy summary to clipboard  
- Displayed in a clean text block  

### 🔹 Fast Performance
Streamlit’s caching ensures the model loads only once.

---

## 🛠️ Tech Stack

| Component  | Technology               |
|------------|---------------------------|
| Framework  | Streamlit                |
| NLP Model  | DistilBART (HuggingFace) |
| Language   | Python                   |
| Backend    | PyTorch                  |

---

## 📁 Project Structure
```
NewsSummarizerApp/
├── news_summarizer_app.py
├── requirements.txt
└── .gitignore

```
---

## 📦 Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/kraryan1946/news-summarizer.git
cd news-summarizer
python -m venv .venv
.venv\Scripts\activate       # Windows
source .venv/bin/activate    # macOS/Linux
pip install -r requirements.txt
streamlit run news_summarizer_app.py
```
---
## 🧠 Model Information

- Using DistilBART CNN-12-6:

- Fast distilled version of BART

- High-quality abstractive summarization

- Ideal for news articles

Model page:
https://huggingface.co/sshleifer/distilbart-cnn-12-6

---
## 🖼️ How It Works

- Paste a news article

- Select summary length

- Click Generate Summary

- Copy or download the summary
---
## ✨ Future Improvements

Add URL/PDF input

Bullet-point summaries

Dark mode

Deployment to Streamlit Cloud or HuggingFace Spaces

---
## 👤 Author

Kraryan
GitHub: https://github.com/witharyank

## ⭐ Support the Project

If you find this project useful, please star the repo — it helps others discover it!
