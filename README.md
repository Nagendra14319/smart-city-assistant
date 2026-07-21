# 🌱 Smart City Assistant

<div align="center">

### AI-Powered Sustainable Urban Management Platform

Build smarter, greener cities using **Google Gemini AI**, **FastAPI**, **Streamlit**, **PostgreSQL**, and **Machine Learning**.

![Python](https://img.shields.io/badge/Python-3.11+-blue?style=for-the-badge&logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-Framework-green?style=for-the-badge&logo=fastapi)
![Streamlit](https://img.shields.io/badge/Streamlit-Frontend-red?style=for-the-badge&logo=streamlit)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue?style=for-the-badge&logo=postgresql)
![Google Gemini](https://img.shields.io/badge/Google-Gemini-blue?style=for-the-badge&logo=google)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</div>

---

# 📖 Overview

Smart City Assistant is an AI-powered web application that helps citizens and administrators manage urban sustainability using Artificial Intelligence and Machine Learning.

The platform combines Google's Gemini AI with FastAPI, Streamlit, PostgreSQL, and Scikit-Learn to provide intelligent insights, forecasting, document summarization, anomaly detection, and citizen engagement in one unified platform.

---

# ✨ Features

## 🤖 AI Assistant
- AI-powered chatbot using Google Gemini
- Smart city guidance
- Sustainability recommendations
- Intelligent question answering

## 📄 Document Summarization
- Upload policy documents
- AI-generated summaries
- Quick document understanding

## 🌍 Sustainability Tips
- Personalized eco-friendly suggestions
- Green energy recommendations
- Waste management guidance

## 📈 KPI Forecasting
- Forecast future trends
- CSV data analysis
- Predictive analytics
- Visualization support

## 🚨 Anomaly Detection
- Detect unusual KPI values
- Identify abnormal patterns
- Early warning system

## 💬 Citizen Feedback
- Submit public issues
- Feedback management
- Complaint tracking

## 👤 User Authentication
- Secure Login
- User Registration
- Password Encryption
- Role-Based Access

## 👑 Admin Dashboard
- User Management
- Feedback Monitoring
- Activity Tracking

---

# 🏗️ System Architecture

```
                    Smart City Assistant

                           │
                           ▼

                  Streamlit Frontend
                           │
                           ▼

                    FastAPI Backend
                           │
     ┌──────────────┬───────────────┬──────────────┐
     ▼              ▼               ▼              ▼

 Authentication   Gemini AI      ML Models    PostgreSQL

                     │
      ┌──────────────┼───────────────┐
      ▼              ▼               ▼

 Summarization   AI Chatbot     Eco Tips

                     │
      ┌──────────────┼───────────────┐
      ▼              ▼               ▼

 Forecasting   Anomaly Detection   Feedback
```

---

# 📂 Project Structure

```
smart-city-assistant/

│

├── backend/
│   ├── models/
│   ├── routes/
│   ├── schemas/
│   ├── services/
│   ├── utils/
│   ├── database.py
│   └── main.py
│

├── frontend/
│   ├── pages/
│   ├── assets/
│   └── app.py
│

├── screenshots/

├── requirements.txt

├── README.md

├── .gitignore

└── .env

```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/Nagendra14319/smart-city-assistant.git

cd smart-city-assistant
```

---

## Create Virtual Environment

```bash
python -m venv venv
```

### Windows

```bash
venv\Scripts\activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🔐 Environment Variables

Create a `.env` file.

```env
GOOGLE_API_KEY=YOUR_API_KEY

DATABASE_URL=postgresql://username:password@localhost:5432/smart_city
```

---

# ▶️ Run Backend

```bash
cd backend

python -m uvicorn main:app --reload
```

Backend API

```
http://localhost:8000
```

Swagger Docs

```
http://localhost:8000/docs
```

---

# ▶️ Run Frontend

```bash
cd frontend

streamlit run app.py
```

Frontend

```
http://localhost:8501
```

---

# 🛠️ Technology Stack

### Frontend

- Streamlit

### Backend

- FastAPI
- Uvicorn

### Database

- PostgreSQL
- SQLAlchemy

### AI

- Google Gemini AI

### Machine Learning

- Scikit-Learn
- Pandas
- NumPy

### Authentication

- Passlib
- BCrypt

### Other Libraries

- Requests
- Python-dotenv

---

# 📊 Core Modules

| Module | Description |
|----------|-------------|
| Login | Secure Authentication |
| Dashboard | User Interface |
| AI Chat | Smart Assistant |
| Summarization | AI Document Summary |
| Forecasting | KPI Prediction |
| Anomaly Detection | Detect Abnormal Data |
| Sustainability Tips | AI Eco Suggestions |
| Feedback | Citizen Reports |
| Admin Panel | User Management |

---

# 📸 Screenshots

```
screenshots/

login.png

dashboard.png

chatbot.png

forecast.png

anomaly.png

feedback.png

admin.png
```

---

# 🚀 Future Enhancements

- IoT Sensor Integration
- Interactive GIS Maps
- Mobile Application
- Docker Deployment
- Kubernetes
- Cloud Deployment
- Real-time Analytics
- Email Notifications
- Multi-language Support
- Advanced AI Models

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository

2. Create a new branch

3. Commit your changes

4. Push your branch

5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

## Appala Nagendra Varma

### GitHub

https://github.com/Nagendra14319

### LinkedIn

https://www.linkedin.com/in/appala-nagendra-varma-25bbb9318/

---

# ⭐ Support

If you found this project useful,

⭐ Star this repository

🍴 Fork it

📢 Share it with others

---

<div align="center">

### Made with ❤️ using Python, FastAPI, Streamlit, PostgreSQL & Google Gemini AI

</div>
