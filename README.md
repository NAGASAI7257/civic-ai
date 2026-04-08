# 🚀 Civic AI – Smart Civic Issue Reporting System

A Flask-based intelligent web application that enables citizens to report civic issues (like potholes, garbage, streetlights) with automatic priority detection and real-time insights.

---

## 📌 Overview

Civic AI is designed to bridge the gap between citizens and authorities by providing a smart, user-friendly platform for reporting and managing civic problems efficiently.

---

## ✨ Key Features

* 📝 Issue Reporting System
  Users can submit complaints such as potholes, garbage, drainage issues, etc.

* 🧠 AI-Based Classification (Rule-Based NLP)
  Automatically categorizes issues and assigns priority (High / Medium / Low)

* 📊 Admin Dashboard
  View all complaints with structured data and insights

* 📈 Real-Time Analytics
  Visual statistics for better decision-making

* 🎯 Dynamic Priority System
  Issues are prioritized based on keywords and severity

* 📱 Responsive UI
  Works smoothly on mobile and desktop devices

---

## 🛠️ Tech Stack

* Backend: Python (Flask)
* Frontend: HTML, CSS, JavaScript
* Visualization: Chart.js
* Logic: Rule-based AI (NLP)

---

## 📂 Project Structure

civic-AI/
├── app.py
├── templates/
├── static/
├── instance/
├── README.md

---

## ▶️ Run Locally

1. Clone the repository
   git clone https://github.com/your-username/civic-AI.git

2. Navigate to project folder
   cd civic-AI

3. Install dependencies
   pip install flask

4. Run the application
   python app.py

5. Open in browser
   http://127.0.0.1:5000/

---

## 🧠 How the AI Works

This project uses a rule-based NLP system:

* Keyword detection from user input
* Category mapping (e.g., garbage → sanitation)
* Priority assignment based on severity words

Advantages:

* Fast execution
* No external APIs required
* Works offline

---

## 📊 Future Improvements

* Add SQLite/MySQL database
* Image upload with AI detection
* Deploy on cloud (AWS / Render / Vercel)
* User authentication system
* Location-based complaint tracking
* Upgrade to ML-based NLP model (BERT/OpenAI)

---

## 👨‍💻 Author

Nagasai
CSE Student | BMSIT

---

## ⭐ Support

If you like this project, give it a star and share it!
