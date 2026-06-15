# 🌱 Smart Energy Advisor

### Interactive Sustainability Simulation Platform

[![Live Demo](https://img.shields.io/badge/Live-Demo-success?style=for-the-badge)](https://mini-intern.vercel.app/)
![React](https://img.shields.io/badge/Frontend-React-blue)
![FastAPI](https://img.shields.io/badge/Backend-FastAPI-green)
![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-blue)
![Chart.js](https://img.shields.io/badge/Visualization-Chart.js-orange)
## What Makes This Project Different?

Unlike traditional dashboards that only display data, Smart Energy Advisor contains a custom environmental simulation engine.

The platform evaluates user-defined energy portfolios using weighted sustainability models and rule-based recommendations to help users understand the trade-offs between cost, emissions, pollution, and long-term sustainability.
Smart Energy Advisor is a full-stack educational sustainability platform that enables users to simulate different energy source combinations and instantly analyze their environmental impact through interactive dashboards, real-time analytics, and personalized recommendations.

🔗 **Live Demo:** https://mini-intern.vercel.app/

---

## 🚀 Project Overview

Energy sustainability concepts are often difficult to understand through textbooks and static content alone.

Smart Energy Advisor transforms energy education into an interactive learning experience where users can experiment with different energy mixes and immediately observe their impact on:

* Pollution Levels
* CO₂ Emissions
* Sustainability Scores
* Energy Cost Index

The platform helps users understand the trade-offs between renewable and non-renewable energy sources through real-time simulation and visualization.

---

## 🎯 Problem Statement

Many students and general users struggle to understand how different energy sources affect environmental sustainability.

Traditional educational methods provide theoretical explanations but rarely allow users to explore the consequences of energy decisions interactively.

Smart Energy Advisor addresses this gap by providing a simulation-driven learning platform that visualizes environmental outcomes in real time.

---

## ✨ Key Features

### ⚡ Energy Mix Simulation

* Create custom energy combinations
* Configure Solar, Wind, Hydro, Coal, and Petroleum percentages
* Real-time sustainability calculations
* Interactive simulation engine

### 📊 Environmental Analytics

* Pollution Score Calculation
* CO₂ Emission Analysis
* Sustainability Score Evaluation
* Cost Index Estimation

### 📈 Interactive Visualizations

* Pie Chart for Energy Distribution
* Sustainability Comparison Charts
* Environmental Impact Dashboard
* Real-Time Metric Updates

### 🤖 Recommendation Engine

* Personalized sustainability recommendations
* Environmental risk detection
* Energy optimization suggestions
* Rule-based advisory system

### 🏆 Sustainability Challenge Mode

* Sustainability target challenges
* Performance evaluation
* Success/failure tracking
* Educational gamification

---

## 🏗️ System Architecture

```text
Frontend (React + Chart.js)
            │
            ▼
      Axios API Calls
            │
            ▼
Backend (FastAPI)
            │
            ▼
Business Logic Layer
(Simulation Engine +
Recommendation Engine)
            │
            ▼
PostgreSQL Database
```

---

## 🔄 Application Workflow

```text
User Selects Energy Mix
            ↓
Energy Validation
            ↓
Simulation Engine
            ↓
Environmental Calculations
            ↓
Dashboard Update
            ↓
Recommendation Generation
            ↓
Challenge Evaluation
```

---

## 📸 Screenshots

### Energy Simulation Dashboard

*Interactive dashboard allowing users to configure energy source percentages and observe environmental impact metrics in real time.*

![Dashboard](images/dashboard.png)

### Sustainability Analytics

*Dynamic charts and visualizations displaying pollution levels, CO₂ emissions, sustainability scores, and energy distribution.*

![Analytics](images/analytics.png)

### Recommendation Engine

*Personalized sustainability recommendations generated based on user-defined energy mixes and environmental performance.*

![Recommendations](images/recommendations.png)

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* JavaScript
* Axios
* Chart.js
* HTML5
* CSS3

### Backend

* FastAPI
* Python
* Pydantic
* SQLAlchemy

### Database

* PostgreSQL

### Deployment

* Vercel

### Version Control

* Git
* GitHub

---

## 📂 Project Structure

```text
Smart-Energy-Advisor/
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── services/
│   └── context/
│
├── backend/
│   ├── routers/
│   ├── services/
│   ├── models/
│   ├── schemas/
│   └── main.py
│
├── database/
├── docs/
├── README.md
└── requirements.txt
```

---

## 🎓 Educational Outcomes

After using the platform, users can:

* Understand renewable vs non-renewable energy sources
* Analyze environmental impact metrics
* Compare sustainability performance
* Evaluate pollution and carbon emissions
* Make informed energy planning decisions

---

## 🧪 Testing

### Functional Testing

* Energy Mix Validation
* Simulation Calculations
* Recommendation Generation
* Challenge Evaluation

### Edge Cases

* 100% Solar Energy
* 100% Coal Energy
* Equal Distribution Mix
* Invalid Inputs
* Total Percentage ≠ 100

---

## 🚀 Future Enhancements

* AI-Powered Sustainability Recommendations
* User Authentication
* Historical Simulation Tracking
* Carbon Footprint Analytics
* Leaderboards & Gamification
* Machine Learning Recommendation Models

---

## 👨‍💻 Team Project

Developed as part of the Internship 2026 Mini Project initiative to promote sustainability awareness through interactive educational technology.

---

## ⭐ Live Demo

https://mini-intern.vercel.app/

If you found this project interesting, consider giving it a star.
