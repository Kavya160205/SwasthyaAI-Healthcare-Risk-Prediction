# 🩺 SwasthyaAI

### AI-Powered Healthcare Risk Prediction Platform

<p align="center">
  <b>An Intelligent Healthcare Risk Assessment Platform using Artificial Intelligence, FastAPI, React, and Machine Learning.</b>
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-0.104-green?logo=fastapi)
![React](https://img.shields.io/badge/React-18-blue?logo=react)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange)
![Render](https://img.shields.io/badge/Backend-Render-purple)
![Vercel](https://img.shields.io/badge/Frontend-Vercel-black?logo=vercel)

</p>

---

# 📌 Project Overview

**SwasthyaAI** is an AI-powered healthcare web application that predicts the risk of common diseases based on user health information. The platform enables users to complete a health assessment and instantly receive AI-generated predictions through a responsive web interface.

The application combines **Machine Learning**, **FastAPI**, and **React** to provide a complete full-stack healthcare solution deployed on the cloud.

---

# 🎯 Objective

The primary objective of this project is to:

- Predict potential health risks using Machine Learning.
- Increase awareness of lifestyle-related diseases.
- Provide users with quick preliminary health assessments.
- Demonstrate a complete AI Full-Stack application for academic and portfolio purposes.

---

# 🚀 Live Project

### 🌐 Frontend

https://swasthya-ai-healthcare-risk-predict-gamma.vercel.app

### ⚙ Backend API

https://swasthyaai-backend-6lbi.onrender.com

### 📖 Swagger API Documentation

https://swasthyaai-backend-6lbi.onrender.com/docs

---

# ✨ Features

- AI-based Health Risk Prediction
- User-friendly Health Assessment Form
- FastAPI REST API
- React Responsive Interface
- Real-time Prediction Results
- Cloud Deployment
- Interactive Swagger Documentation
- Mobile-Friendly Design
- Frontend-Backend API Integration

---

# 🧠 Diseases Predicted

- Diabetes
- Hypertension
- Anemia
- Thyroid Disorders

---

# 🛠 Technology Stack

## Frontend

- React.js
- React Router
- Axios
- CSS

## Backend

- Python
- FastAPI
- Uvicorn
- Pydantic

## Machine Learning

- Scikit-Learn
- NumPy
- Joblib

## Deployment

- Render
- Vercel

## Version Control

- Git
- GitHub

---

## 📁 Project Structure

```text
SwasthyaAI
│
├── backend
│   ├── models
│   │   └── __init__.py
│   │
│   ├── routes
│   │   ├── __init__.py
│   │   ├── health.py
│   │   └── predict.py
│   │
│   ├── utils
│   │   ├── __init__.py
│   │   ├── advice.py
│   │   └── predictor.py
│   │
│   ├── main.py
│   ├── requirements.txt
│   ├── runtime.txt
│   └── .python-version
│
├── frontend
│   ├── public
│   │   └── index.html
│   │
│   ├── src
│   │   ├── components
│   │   │   └── Navbar.js
│   │   │
│   │   ├── pages
│   │   │   ├── LandingPage.js
│   │   │   ├── AssessmentPage.js
│   │   │   ├── DashboardPage.js
│   │   │   └── ResultsPage.js
│   │   │
│   │   ├── App.js
│   │   ├── index.js
│   │   └── index.css
│   │
│   ├── package.json
│   └── package-lock.json
│
├── README.md
├── .gitignore
├── start.bat
├── start.sh
└── SwasthyaAI.code-workspace
```
```

---

# ⚙ Installation Guide

## Clone Repository

```bash
git clone https://github.com/Kavya160205/SwasthyaAI-Healthcare-Risk-Prediction.git
```

## Move into Project

```bash
cd SwasthyaAI-Healthcare-Risk-Prediction
```

---

## Backend Setup

```bash
cd backend

python -m venv venv

venv\Scripts\activate

pip install -r requirements.txt

uvicorn main:app --reload
```

Backend URL

```
http://localhost:8000
```

Swagger

```
http://localhost:8000/docs
```

---

## Frontend Setup

```bash
cd frontend

npm install

npm start
```

Frontend

```
http://localhost:3000
```

---

# 🔗 REST API Endpoints

## Predict Disease

```
POST /api/predict/
```

Predicts the user's disease risk.

---

## Health Status

```
GET /api/health/status
```

Returns backend status.

---

## Disease List

```
GET /api/health/diseases
```

Returns supported diseases.

---

# 🔄 System Workflow

```
User

      │

      ▼

Health Assessment Form

      │

      ▼

React Frontend

      │

      ▼

FastAPI Backend

      │

      ▼

Machine Learning Prediction

      │

      ▼

Prediction Result

      │

      ▼

Displayed to User
```

---

# 🌍 Deployment

| Service | Platform |
|----------|----------|
| Frontend | Vercel |
| Backend | Render |
| API Documentation | Swagger UI |

---

# 📈 Future Enhancements

- User Login & Authentication
- Prediction History
- PDF Health Reports
- Explainable AI (SHAP/LIME)
- Doctor Recommendation System
- Cloud Database Integration
- AI Chatbot Support
- Email Notifications
- Appointment Booking
- Multilingual Support

---

# 🎓 Learning Outcomes

This project helped in understanding:

- Artificial Intelligence Applications
- Machine Learning Deployment
- REST API Development
- FastAPI Framework
- React Frontend Development
- API Integration
- Cloud Deployment
- Git & GitHub
- Full-Stack Development

---

# 💡 Challenges Solved

- Built a complete full-stack AI application.
- Connected React frontend with FastAPI backend.
- Resolved deployment issues on Render.
- Integrated cloud-hosted frontend and backend.
- Successfully deployed and tested the application on desktop and mobile devices.

---

# 👩‍💻 Author

## **Madupoju Kavya**

**B.Tech – Artificial Intelligence & Machine Learning**

GitHub:

https://github.com/Kavya160205

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

It helps others discover the project and supports my work.

---

# 📜 License

This project is developed for educational and portfolio purposes.
