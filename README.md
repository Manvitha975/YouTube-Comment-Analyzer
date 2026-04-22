# 🎥 YouTube Comment Analyzer

An interactive web application that allows you to analyze YouTube comments using AI, sentiment analysis, and vector search.

---

## 🚀 Features

- 🔗 **YouTube API Integration**  
  Fetch up to 100 comments from any YouTube video.

- 🔍 **Vector Search (Qdrant)**  
  Store and search comment embeddings efficiently.

- 🤖 **AI Q&A (OpenAI GPT)**  
  Ask questions about the comments and get intelligent answers.

- 😊 **Sentiment Analysis (VADER)**  
  Visualize sentiment distribution (positive / neutral / negative).

- 🔑 **Keyword Extraction**  
  Extract top 10 important keywords from comments.

- 📊 **Interactive Dashboard**  
  Clean UI built using Streamlit and Plotly.

---

## 🛠 Tech Stack

- Python 3.9+
- Streamlit
- Sentence Transformers
- Qdrant
- OpenAI Python SDK
- Google API Client
- VADER Sentiment
- Plotly Express
- Scikit-learn
- Transformers

---

## 📦 Installation

Install all required dependencies:

```bash
pip install streamlit sentence-transformers scikit-learn qdrant-client \
google-api-python-client vaderSentiment plotly transformers
