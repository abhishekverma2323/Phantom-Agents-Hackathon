# 🤖 Phantom Agent – Smart Health Chatbot
By HackVengers

![Hackathon](https://img.shields.io/badge/Hackathon-Project-blueviolet?style=flat-square&logo=hackclub)
![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python)
![Flask](https://img.shields.io/badge/Flask-Backend-black?style=flat-square&logo=flask)
![SQLite](https://img.shields.io/badge/SQLite-Database-07405e?style=flat-square&logo=sqlite)
![Status](https://img.shields.io/badge/Status-Active-success?style=flat-square)

---

## 🚀 Overview

**Phantom Agent** is an **AI-powered Health Chatbot** built for hackathons.  
It helps users track their **health profile**, get **fitness tips**, calculate **BMI**, and even **learns from user preferences** (like vegetarian diet, fitness goals).  

- 🧠 **Hybrid Brain** → Rule-based + Learning Memory  
- 📊 **Personalized Recommendations** → Stores user age, weight, height, goals  
- ⚡ **Offline & Lightweight** → Runs on `Flask + SQLite`, no heavy GPU required  
- 🔥 **Hackathon Ready** → Easy to deploy, extend, and demo  

---

## ✨ Features

✅ BMI Calculation  
✅ Health & Lifestyle Tips  
✅ User Profile Management (Age, Weight, Height)  
✅ Preference Memory (e.g., diet, fitness goals)  
✅ Offline Learning with TF-IDF Matching  
✅ Clear Chat / Profile Reset  

---

## 🛠️ Tech Stack

- **Backend:** [Flask](https://flask.palletsprojects.com/)  
- **Database:** SQLite3  
- **Frontend:** HTML, CSS, JavaScript  
- **ML/NLP:** Scikit-learn (TF-IDF, similarity search)  
- **Language:** Python 3.10+  

---

## 📂 Project Structure

📦 AI HEALTH COMPANION
┣ 📜 app.py # Flask server
┣ 📜 database.py # Database models & functions
┣ 📜 brain.py # Bot logic (rules + learning memory)
┣ 📜 static/ # CSS, JS, Images
┣ 📜 templates/ # HTML UI
┣ 📜 README.md # Project Docs
┗ 📜 requirements.txt

🧠 How the Bot Thinks

Rule-based engine → Handles BMI, greetings, predefined tips.

Learning memory → Stores diet/goals in DB.

Query similarity → Uses TF-IDF to match new queries with past knowledge.

Personalized responses → Bot replies differently depending on memory.

🚀 Future Enhancements

 Integrate OpenAI API / LLM for advanced replies

 Add voice interaction

 Mobile-first PWA design

 Nutrition & workout plan generator

👨‍💻 Team HackVengers

Built with ❤️ at Phantom Agents.

⚡ “Don’t just chat… Think!”
