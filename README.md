# 📰 AI News Summarizer

An AI-powered news summarization and email automation workflow built using **n8n, Google Gemini, NewsAPI, and Gmail**.

## 🚀 Features

- Fetches the latest news using NewsAPI
- Allows searching news by category or keyword
- Uses Google Gemini AI to analyze and summarize news
- Generates a clean and readable news summary
- Automatically sends the summarized news through Gmail

## 🔄 Workflow

1. User sends a request through the chat interface.
2. The n8n workflow fetches relevant news using NewsAPI.
3. Google Gemini AI analyzes and summarizes the news.
4. The generated summary is formatted.
5. The final news digest is sent through Gmail.

## 🛠️ Technologies Used

- **n8n** – Workflow automation
- **Google Gemini** – AI-powered news analysis and summarization
- **NewsAPI** – Fetching latest news headlines
- **Gmail API** – Sending automated email updates

## 📂 Project Files

- `AI News Summarizer.json` – Exported n8n workflow

## ⚙️ Setup

1. Import the `AI News Summarizer.json` file into n8n.
2. Configure your NewsAPI credentials.
3. Configure your Google Gemini API credentials.
4. Connect your Gmail account.
5. Run the workflow and request the news you want.

> ⚠️ API keys and credentials are not included in this repository. You must add your own credentials after importing the workflow.

## 🎯 Project Purpose

This project demonstrates how AI and workflow automation can be combined to automatically fetch, analyze, summarize, and distribute news through email.

## 👩‍💻 Author

**Prerana**

---
⭐ If you found this project useful, feel free to star the repository!
