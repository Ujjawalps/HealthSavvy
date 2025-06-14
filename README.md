# 🩺 HealthSavvy - Your AI-Powered Medical Assistant

HealthSavvy is an intelligent, conversational AI chatbot designed to help users understand symptoms and get general health guidance based on natural language inputs.

> “AI meets healthcare – helping you become more aware, one symptom at a time.”

---

## 🚀 Live Demo

🌐 [Check it out on Render](https://healthsavvy.onrender.com)  
*(Link will be updated once deployed from your fork)*

---

## ✨ Features

- 🔎 Symptom-based query handling
- 🧠 Uses LLMs (like Gemini or OpenAI) for contextual answers
- 📚 Embedding-based medical knowledge from `Medical_book.pdf`
- 💬 Clean and user-friendly chat interface
- 🧾 PDF-based medical vector search via Pinecone
- 🛡️ Works entirely in-browser with no login required

---

## 🧠 Tech Stack

| Layer         | Tech Used                                |
|---------------|-------------------------------------------|
| Backend       | Python, Flask                             |
| AI/Embedding  | Langchain, Gemini/OpenAI, Pinecone        |
| Frontend      | HTML, CSS, JS (Vanilla)                   |
| Deployment    | Render.com                                |
| Data Source   | Custom PDF (`Medical_book.pdf`)           |

---

## 🛠️ How to Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/yourusername/HealthSavvy.git
cd HealthSavvy

# 2. Create virtual environment
python -m venv venv
.\venv\Scripts\activate      # Windows
# source venv/bin/activate   # Mac/Linux

# 3. Install dependencies
pip install -r requirements.txt

# 4. Add your .env file with API keys (Gemini, Pinecone, etc.)

# 5. Run the app
python app.py


# 📜 License

MIT License – see LICENSE file for details.
