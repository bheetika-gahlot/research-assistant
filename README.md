# 🧠 Research Assistant Chrome Extension

A smart research assistant that summarizes selected text from any webpage using a Chrome extension and a Spring Boot backend powered by Google Gemini AI.

---

## 🚀 Features

- ✨ Summarize selected text from any webpage
- 🤖 AI-powered summaries using Google Gemini API
- 📝 Save and manage research notes locally
- 🔗 Chrome Extension + Spring Boot backend
- 🧪 API testing with Postman
- 🎯 Simple and clean user interface

---

## 🧩 Project Architecture
research-assistant/
│
├── backend/
│ ├── src/main/java/com/research/assistant/
│ │ ├── ResearchAssistantApplication.java
│ │ ├── ResearchController.java
│ │ ├── ResearchService.java
│ │ └── ResearchRequest.java
│ └── src/main/resources/
│ └── application.properties
│
├── extension/
│ ├── manifest.json
│ ├── popup.html
│ ├── popup.js
│ └── styles.css
│
├── postman/
│ └── research-assistant-collection.json
│
└── README.md

---

## 🛠 Tech Stack

### Frontend (Chrome Extension)
- JavaScript
- Chrome Extension APIs
- HTML & CSS

### Backend (Spring Boot)
- Spring Boot
- WebClient (Reactive)
- Jackson JSON Parser
- Google Gemini API

### API Testing
- Postman

---

## ⚙️ Setup Guide

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/research-assistant.git
cd research-assistant
```

---
### 2️⃣ Configure Backend
Open:
- src/main/resources/application.properties
- Add your Gemini API Key

---
### 3️⃣ Run Backend Server
- Run : ResearchAssistantApplication.java
- Backend runs at: http://localhost:8080

---

### 4️⃣ Test API Using Postman

---

### 5️⃣ Load Chrome Extension

---

Thanks for checking out this project 🙂  
If it helped you, consider giving it a ⭐ on GitHub.
