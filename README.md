<p align="center">
  <img src="https://img.shields.io/badge/Project-AI%20Resume%20Analyzer-00bfa5?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Tech-Streamlit-blue?style=for-the-badge&logo=streamlit" />
  <img src="https://img.shields.io/badge/Backend-Python-yellow?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Database-SQLite-lightgrey?style=for-the-badge&logo=sqlite" />
</p>

<h1 align="center">🏝️ Smart AI Resume Analyzer</h1>

<p align="center">
<b>🚀 Intelligent Resume Analysis & Builder powered by AI</b><br>
Developed by <b>Rudra Suhagia</b>
</p>

---

## 🎓 About This Project

This project was developed as a **System Design Practices (SDP)** coursework during my **6th Semester** at **Dharmsinh Desai University**, pursuing **Bachelor of Computer Engineering (CE)**.

The goal of this project is to build an intelligent system that:

* Analyzes resumes using AI
* Provides actionable feedback
* Helps users improve their chances of getting shortlisted

---

## 🚀 Features

### 🔍 Resume Analyzer

* ATS Compatibility Score
* Keyword Gap Detection
* Role-based Suggestions
* Skills Analysis

### 🧠 AI-Powered Insights

* Smart Resume Feedback
* Content Optimization Suggestions
* Industry-based Recommendations

### 📝 Resume Builder

* Create resumes from scratch
* Structured sections (Education, Skills, Projects)
* Clean and professional formatting

### 📊 Dashboard

* Stores analyzed resumes
* View previous results
* Admin-level access

---

## 🛠️ Tech Stack

| Layer     | Technology                          |
| --------- | ----------------------------------- |
| Frontend  | Streamlit                           |
| Backend   | Python                              |
| Database  | SQLite                              |
| AI        | Google Gemini API                   |
| Libraries | Pandas, PyPDF2, spaCy, scikit-learn |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/rudrahacked-ux/Smart-AI-Resume-Analyzer.git
cd Smart-AI-Resume-Analyzer
```

---

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Install spaCy Model

```bash
python -m spacy download en_core_web_sm
```

---

### 5️⃣ Setup Environment Variables

Create a `.env` file inside the project:

```env
GOOGLE_API_KEY=your_api_key_here
```

👉 Get API key from: https://aistudio.google.com/app/apikey

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

---

## 🔐 Admin Access

You can manually create admin credentials using SQL:

```sql
INSERT INTO admin (email, password)
VALUES ('admin@example.com', 'admin123');
```

---

## 📸 Quick Glance

> Screenshots of the application

<div align="center">  
<table>  
<tr>  
<td><img src="https://github.com/user-attachments/assets/2dc1b44d-7eb6-4371-81f9-3a140f83064c" width="500"></td>  
<td><img src="https://github.com/user-attachments/assets/b9f4c7b0-fbd6-40c4-9d8b-231d9fdd91a7" width="500"></td>  
</tr>  

<tr>  
<td><img src="https://github.com/user-attachments/assets/02b6d379-a04f-421e-9377-1bb077324f17" width="500"></td>  
<td><img src="https://github.com/user-attachments/assets/830e738e-a76b-4818-b426-d98189d8c441" width="500"></td>  
</tr>  

<tr>  
<td><img src="https://github.com/user-attachments/assets/fcfb02f2-2831-4f26-a251-8c67266afca8" width="500"></td>  
<td><img src="https://github.com/user-attachments/assets/90704043-a559-42fb-bcf1-330ebfedee2b" width="500"></td>  
</tr>  

<tr>  
<td><img src="https://github.com/user-attachments/assets/7ebdf0d0-1172-47dd-a281-7d4bb058bd3f" width="500"></td>  
<td><img src="https://github.com/user-attachments/assets/982f26b9-f84d-4cec-b8c2-beeec23b5e8b" width="500"></td>  
</tr>  

<tr>  
<td><img src="https://github.com/user-attachments/assets/0b9bab57-5c73-4944-90bb-c9c374c4b559" width="500"></td>  
<td><img src="https://github.com/user-attachments/assets/10aaa50e-3c28-415b-948d-a9744f942dcd" width="500"></td>  
</tr>  

<tr>  
<td><img src="https://github.com/user-attachments/assets/88f85cca-35df-4575-a949-b5ac49d822f5" width="500"></td>  
<td><img src="https://github.com/user-attachments/assets/649625ed-a8c8-436a-bdbe-4f261b598ef3" width="500"></td>  
</tr>  
</table>  
</div>

---

## 🐞 Known Issue

**Autofill Bug (Resume Builder)**
Sometimes browser autofill is not detected.

### Fix:

* Edit the field manually (delete & retype one character)

---

## 🎯 Why This Project?

* 🎓 Academic SDP Project
* 🤖 Real-world AI integration
* 💼 Portfolio-ready application
* 🚀 Demonstrates full-stack + ML concepts

---

## 👨‍💻 Author

**Rudra Suhagia**
GitHub: https://github.com/rudrahacked-ux

---

## ⭐ Support

If you found this project helpful:

👉 Give it a **star ⭐ on GitHub**
