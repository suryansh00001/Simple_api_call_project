
# 🍳 Cooking Guide AI

A focused, no-nonsense Cooking Mentor web app powered by Google's Gemini API.  
Ask any cooking-related question and get serious, instructional advice from an AI culinary expert.

---

## 🚀 Features

- 🧑‍🍳 Professional culinary guidance on:
  - Recipes
  - Techniques
  - Ingredients
  - Tools
  - Food safety
  - Preparation methods
- 🔒 Strict topic boundaries — non-cooking topics are rejected
- ✨ Clean, responsive UI with thoughtful design
- ⚡ Powered by Gemini 2.0 Flash via Google Generative Language API

---
## 🌐 Live Demo

👉 **Hosted Web App**: [Click to Open Cooking Guide AI](https://cook-something.netlify.app/)

> ⚠️ To use this demo, ask the developer for the **last 4 characters** of the API key to complete authentication.

## 🛠️ Setup Instructions

1. **Clone this repo**

2. **Add your Google API Key**

   In the `index.html` file, replace the placeholder in this line:

   ```js
   const fullKey = "PASTE_YOUR_FULL_API_KEY_HERE";
   ```

   > ⚠️ _Do not expose your full API key in production. Use a backend proxy for secure handling._

3. **Open in Browser**
   Simply open the `index.html` file in any browser:
   ```bash
   open index.html   # macOS
   start index.html  # Windows
   ```

---

## 🖼️ Screenshot

![Cooking Guide AI Screenshot](<img width="939" height="855" alt="image" src="https://github.com/user-attachments/assets/6f015027-c8d1-406d-a0c0-9a3e48e88d50" />
)

---

## 📁 Project Structure

```
cooking-guide-ai/
├── index.html       # Main web app code
└── README.md        # You're here
```

---

## 🧠 AI Behavior Guide

The AI has been instructed to:

- **Only** respond to cooking-related content.
- **Reject and redirect** any non-cooking topics.
- Maintain a **professional tone** — serious, educational, and supportive.
- Avoid jokes, small talk, or personal opinions.

---

## 🔐 Security Warning

This app uses the **full Google API key on the frontend**, which is **not secure for production**.

To protect your key:
- Use a backend (e.g., Node.js, Flask) to proxy the API request.
- Keep your key server-side and never expose it in the browser.

---

## 📜 License

MIT License © 2025 [Your Name or Organization]

---
