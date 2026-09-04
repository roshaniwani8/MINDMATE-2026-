# 🧠 MindMate AI

> **Your AI-powered wellness companion for everyday mental well-being.**

MindMate AI is a smart wellness application designed to help users understand and track their emotions, maintain healthy habits, and have supportive AI-powered conversations in a simple and friendly environment.

## ✨ Features

* 💬 **AI Wellness Chat** — Have supportive conversations with an AI companion.
* 😊 **Mood Tracker** — Record your daily mood and monitor emotional patterns.
* 📊 **Wellness Tracking** — Keep track of your well-being over time.
* 🧠 **Smart Conversation Memory** — Provides more context-aware conversations.
* ⚡ **Real-Time AI Responses** — Smooth conversational experience with streaming responses.
* 🔒 **Privacy-Friendly Design** — Designed with user privacy and local data handling in mind.
* 📱 **Responsive UI** — Works across desktop and mobile screen sizes.
* 🌙 **Modern Dark UI** — Clean, calming interface designed for comfortable use.

## 🎯 Why MindMate?

Mental well-being is an important part of everyday life, but people may not always have an easy way to reflect on how they are feeling.

MindMate provides a simple digital space where users can:

**Track → Reflect → Understand → Improve**

The goal is not to replace professional mental-health care, but to provide an accessible wellness companion for everyday reflection and habit tracking.

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript
* Fetch API
* Local Storage

### Backend

* Python
* Flask
* REST API

### AI

* Qwen 2.5 3B through Ollama for local AI inference
* AI conversation system
* Streaming responses
* Conversation context/memory

### Data

* Local Storage for mood history and client-side persistence
* JSON-based API communication

## 🏗️ Project Structure

```text
MindMate/
│
├── backend/
│   ├── app.py
│   ├── api_reference.py
│   ├── integrations.json
│   ├── requirements.txt
│   ├── index.html
│   ├── script.js
│   ├── style.css
│   └── mindmate_data/
│
├── README.md
└── .gitignore
```

## 🚀 How to Run Locally

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd MindMate
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it:

**Windows**

```bash
.venv\Scripts\activate
```

**macOS/Linux**

```bash
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r backend/requirements.txt
```

### 4. Start the Flask server

```bash
python backend/app.py
```

### 5. Open MindMate

Open the local address shown by Flask in your browser.

## 🤖 Local AI Setup

MindMate can use **Ollama** with the Qwen 2.5 3B model for local AI inference.

Make sure Ollama is installed and the required model is available before using the local AI chat functionality.

> If local AI is unavailable, the application can still provide its wellness-tracking features.

## 🔐 Privacy

MindMate is designed with privacy in mind. Mood history and other client-side information can be stored locally in the user's browser rather than requiring unnecessary cloud storage.

MindMate is a **wellness application**, not a replacement for a qualified mental-health professional or emergency service.

## 🌟 Future Improvements

* 🎙️ Voice-based AI conversations
* 📈 Advanced mood analytics
* 🔔 Personalized wellness reminders
* 🧘 Guided breathing and relaxation activities
* 📅 Personalized wellness plans
* 🌐 Multilingual AI support
* 📱 Progressive Web App / mobile version
* ☁️ Optional secure cloud synchronization

## 🏆 Hackathon Project

**MindMate AI** was developed as a health-focused AI project with the goal of using technology to make everyday wellness tracking and emotional reflection more accessible.

## 👩‍💻 Built With

**Python • Flask • HTML • CSS • JavaScript • REST APIs • Ollama • Qwen 2.5 3B**

---

### 💙 MindMate AI

**A small step toward better everyday well-being.**
