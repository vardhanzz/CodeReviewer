# 🔍 CodeReviewer

**CodeReviewer** is an intelligent web-based tool that analyzes your code snippets and provides meaningful feedback, suggestions, and improvements. Whether you're a beginner or a seasoned developer, CodeReviewer helps enhance code quality, reusability, and clarity — with the power of AI.

---

## 📸 Preview

<img width="1460" alt="Screenshot 2025-07-01 at 12 18 52 AM" src="https://github.com/user-attachments/assets/836df2b5-287e-4d4c-8913-39db2976be46" /> <br>
<img width="1460" alt="Screenshot 2025-07-01 at 12 19 31 AM" src="https://github.com/user-attachments/assets/073bf154-8da6-4d75-8b67-ddd1ef06cb55" />

---

## ✨ Features

- 🧠 **AI-Powered Code Review**  
  Analyzes code using Google's Gemini Flash 2.0 model and suggests improvements.

- 🖊️ **Live Code Editor**  
  Write code directly in the editor and get instant feedback.

- 🔄 **Improvement Suggestions**  
  Highlights issues in your code (e.g., poor structure, missing parameters) and gives detailed fixes.

- 💡 **Usability Enhancements**  
  Encourages best practices like documentation, dynamic inputs, and modular design.

- 🎨 **Modern UI**  
  Sleek gradient-based UI inspired by soft pink-blue aesthetics for a smooth user experience.

---

## 🛠️ Tech Stack

| Layer      | Technology         |
|------------|--------------------|
| Frontend   | React, PrismJS, Axios, React Markdown |
| Backend    | Node.js, Express.js |
| AI Review  | Google Gemini Flash 2.0 (via `@google/generative-ai`) |

---

## 🚀 How It Works

1. Type any code snippet (in any language) into the left editor.
2. Click the **Review** button.
3. CodeReviewer sends your code to the backend, which interacts with the Gemini AI.
4. The AI evaluates the code and sends back a detailed review.
5. The result is displayed beautifully on the right panel with suggested fixes and improvements.

---

## 🧪 Example Use Cases

- Reviewing small functions for correctness and best practices.
- Learning better code writing habits with AI suggestions.
- Quickly refining prototype snippets before using in larger projects.

---

## 📦 Setup Instructions

```bash
# Clone the repository
git clone https://github.com/your-username/codeReviewer.git
cd codeReviewer

# Install backend dependencies
cd BackEnd
npm install

# Install frontend dependencies
cd ../Frontend
npm install

# Create your .env file in /BackEnd
GOOGLE_GEMINI_KEY=your_api_key_here

# Run the backend
cd ../BackEnd
node server.js

# Run the frontend (in another terminal)
cd ../Frontend
npm run dev
