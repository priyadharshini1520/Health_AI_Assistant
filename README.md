🩺 Health AI – Intelligent Healthcare Assistant
📌 Project Overview

Health AI is an intelligent healthcare assistant powered by IBM Granite LLM.
It helps users with:

✅ Symptom Checking

✅ Health Policy Summarization (from PDF/text)

✅ Health Q&A

✅ Preventive Health Tips

This project uses Gradio to provide an interactive web-based interface and supports both text and PDF input for health-related tasks.

⚙️ Tech Stack

Python 3

Transformers (Hugging Face)

PyTorch

Gradio

PyPDF2

🚀 Features
1. Symptom Checker

Users can enter symptoms (e.g., fever, cough, sore throat) and get:

Possible common causes

Self-care tips

Doctor consultation advice

2. Health Policy Summarization

Upload a PDF or paste healthcare policy text

AI provides a structured summary:

Purpose

Benefits

Eligibility

Access procedure

3. Health Q&A

Ask general health-related questions and get AI-powered responsible answers.

4. Preventive Tips Generator

Enter a health topic (e.g., diabetes, heart health, hygiene) to receive clear preventive healthcare tips.

🖥️ How to Run
Install dependencies
pip install gradio torch transformers pypdf2

Run the app
python HealthAI.py


If using Google Colab, just open the notebook and run all cells.
App will launch with a public link via Gradio.

📂 Project Structure
HealthAI/
│── Health AI.ipynb         # Colab Notebook
│── app.py                  # (Optional) Python script version
│── requirements.txt        # Dependencies
│── README.md               # Documentation

🔒 Disclaimer

This is an educational project, not a replacement for professional medical advice.
For any serious health condition, always consult a certified doctor.

📜 License

MIT License
