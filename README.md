# 📧 MailBuddy – AI Powered Email Reply Generator

MailBuddy is an AI-based email reply generator built with Spring Boot, Google Gemini API, and a clean HTML/CSS/JavaScript frontend.
Users simply enter the email content and optionally choose a tone, and MailBuddy generates a smart, context-aware AI reply.

---

## 🚀 Features
- 🤖 Generate AI-powered email replies using Gemini API
- 🌐 Lightweight HTML/CSS/JS frontend
- 🔐 Secure API key via environment variable
- ☁️ Fully deployable to Railway

---

## 🧠 How MailBuddy Works
1. User enters:
      - Email message/content
      - Optional tone (dropdown input)
2. Frontend sends POST request.
3. Backend formats the prompt and sends it to Gemini API.
4. Gemini generates a reply matching the requested tone.
5. Reply is returned and displayed.

---

## 🛠️ Tech Stack
- Backend
    - Java 21
    - Spring Boot
    - Google Gemini API
- Frontend
    - HTML
    - CSS
    - JavaScript
- Deployment
    - Railway

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

