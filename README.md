# 📰 AI-Powered Daily News Automation using n8n

An intelligent workflow automation system built with **n8n** that fetches the latest news from multiple RSS feeds, summarizes articles using an **LLM (OpenAI/Gemini)**, generates a clean HTML email, and automatically delivers a daily news digest via Gmail.

---

## 🚀 Features

- 📰 Fetches news from multiple RSS feeds
- 🤖 AI-powered article summarization using an LLM
- 📂 Categorizes news by topic
- 📧 Generates a professional HTML email
- ⏰ Runs automatically on a schedule
- ✉️ Sends the news digest directly to Gmail
- ⚡ Fully automated end-to-end workflow

---

## 🛠️ Tech Stack

- n8n
- OpenAI / Gemini LLM
- RSS Feeds
- JavaScript
- HTML
- Gmail API
- JSON
- Workflow Automation

---

# Workflow Architecture

```
Schedule Trigger
        │
        ▼
Read RSS Feeds
        │
        ▼
Filter & Limit Articles
        │
        ▼
Data Preprocessing (JavaScript)
        │
        ▼
LLM Summarization
        │
        ▼
Format Structured Output
        │
        ▼
Generate HTML Email
        │
        ▼
Send Daily Digest via Gmail
```

---

## 📸 Screenshots

### n8n Workflow

> *(Add `workflow.png` here after uploading the screenshot)*

---

### Sample Email Output

> *(Add your Daily News Digest screenshot here)*

---

## 📂 Project Structure

```
AI-News-Automation
│
├── Workflow
│   └── news-workflow.json
│
├── Screenshots
│   ├── workflow.png
│   ├── email-output.png
│
├── docs
│   └── architecture.png
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## ⚙️ Workflow Overview

1. Trigger workflow automatically every day.
2. Read news articles from multiple RSS feeds.
3. Filter and limit the number of articles.
4. Clean and preprocess article data.
5. Generate AI summaries using an LLM.
6. Format the output into HTML.
7. Send a beautifully formatted email via Gmail.

---

## 🎯 Use Cases

- Daily AI news updates
- Personalized news digest
- Business intelligence
- Technology monitoring
- Automated email newsletters

---

## 🔮 Future Improvements

- Support multiple email recipients
- Add more RSS sources
- AI-based article ranking
- Telegram & WhatsApp notifications
- Multi-language support
- Dashboard for workflow analytics

---

## 👨‍💻 Author

**Shreyansh Verma**

B.Tech – Artificial Intelligence & Machine Learning  
Manipal University Jaipur

---

⭐ If you found this project useful, consider giving it a star.
