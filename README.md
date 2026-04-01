# 🤖 AI Smart Learning Assistant (RAG Edition)

An interactive learning assistant built with **Streamlit** and **Google Gemini API**, designed to help students study smarter with explanations, practice summaries, and quizzes.

## 🚀 Features
- 📂 Upload PDFs or PPTX files
- 📖 Explain topics at different depth levels (Summary, Standard, Deep Dive)
- 📝 Generate practice summaries
- 🧠 Take interactive quizzes with hints
- 📊 Track mastery progress (Reading, Practice, Quiz)

## 🛠️ Tech Stack
- Streamlit (UI)
- Google Gemini API (AI responses)
- PyPDF2 & python-pptx (file parsing)
- Python dotenv (API key management)

## 📦 Installation
```bash
git clone https://github.com/yourusername/ai-learning-assistant.git
cd ai-learning-assistant
pip install -r requirements.txt

## Add your Gemini API key in a .env file:
GEMINI_API_KEY=your_api_key_here

## ▶️ Run the App
-streamlit run app.py
