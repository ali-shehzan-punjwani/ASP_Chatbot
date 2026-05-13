# ASP_Chatbot
Personal AI assistant chatbot built with Streamlit and Groq, featuring memory-based responses and a modern UI.
# ASP Chatbot 🤖

A personalized AI-powered chatbot built using **Streamlit** and **Groq LLM API**, designed as a modern interactive assistant with memory support and a clean UI.

---

## 🚀 Overview

ASP Chatbot is a lightweight AI assistant that allows users to interact with a large language model through a web interface. It supports conversational memory, animated responses, and a modern UI built with Streamlit.

This project demonstrates how to integrate:

* Large Language Models (LLMs)
* Web UI using Streamlit
* API-based AI inference (Groq)
* Session-based chat memory

---

## ✨ Features

* 💬 Chat-based AI interface (like ChatGPT style)
* 🧠 Memory support using JSON file
* ⚡ Fast responses using Groq LLM API
* 🎨 Modern UI with custom CSS styling
* ⌨️ Typing animation effect for responses
* 📱 Responsive Streamlit web app

---

## 🧰 Tech Stack

* Python
* Streamlit
* Groq API (LLaMA 3 model)
* JSON (for memory storage)

---

## 📁 Project Structure

```
ASP-Chatbot/
│
├── app.py                # Main Streamlit application
├── memory.json          # Stores chatbot memory data
├── requirements.txt     # Python dependencies
├── README.md            # Project documentation
├── .gitignore           # Files to ignore in Git
└── star_logo.png        # App logo
```

---

## ⚙️ Installation Guide

### 1. Clone or Download Project

Download the ZIP file and extract it.

---

### 2. Install Dependencies

Make sure you have Python 3.9+ installed.

```bash
pip install -r requirements.txt
```

---

### 3. Set Up API Key (Important 🔑)

This project uses Groq API.

Create a folder named:

```
.streamlit
```

Inside it create a file:

```
secrets.toml
```

Add your API key:

```toml
GROQ_API_KEY = "your_api_key_here"
```

---

## ▶️ How to Run the App

Run the following command in terminal:

```bash
streamlit run app.py
```

Then open the local URL shown in terminal (usually):

```
http://localhost:8501
```

---

## 🧠 How It Works

1. User enters a message in chat input
2. Message is sent to Groq LLM API
3. System prompt + memory are included
4. AI generates a response
5. Response is displayed with typing animation
6. Conversation is stored in session state

---

## 🔐 Security Note

* Never expose your API key publicly
* Always use Streamlit secrets or environment variables
* Do NOT upload `.streamlit/secrets.toml` to GitHub

---

## 📦 Requirements

```
streamlit
groq
```

---

## 🌐 References

* Streamlit: https://streamlit.io/
* Groq API: https://console.groq.com/docs
* GitHub: https://github.com/

---

## 👨‍💻 Author

**ASP Chatbot Project**
Personal AI assistant built for learning, experimentation, and portfolio development.

---

## 📌 Future Improvements

* Persistent database memory (instead of JSON)
* User authentication system
* Voice input/output
* Cloud deployment (Streamlit Cloud / AWS)
* Enhanced memory with vector database

---
