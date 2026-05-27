# 🌐 AI Translation App (Streamlit + OpenAI + gTTS)

This is a simple AI-powered translation app built with Streamlit. It translates text using OpenAI and can also convert translated text into speech using gTTS.

🔗 Live Demo: https://translator-mzmgbaljhusvagspnnkn4p.streamlit.app/

---

## 🚀 Features

- Translate text into multiple languages
- AI-powered translation using OpenAI GPT
- Text-to-Speech audio output (gTTS)
- Simple Streamlit interface

---

## ⚙️ How to Run the App

Run the app using:

```bash
streamlit run app.py
🔑 API Key Setup (IMPORTANT)

To make the app work, you need an OpenAI API key.

👉 Replace this code:
api_key = st.secrets["OPENAI_API_KEY"]
client = OpenAI(api_key=api_key)
👉 With this:
api_key = "your_api_key_here"
client = OpenAI(api_key=api_key)
🌍 Supported Languages
French
Spanish
German
Chinese
Japanese
Hindi
Urdu
📁 Project Structure
app.py
requirements.txt
README.md
