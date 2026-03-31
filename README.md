# 🚀 MarketIQ — AI Market Intelligence Platform

> Analyze company trends, extract insights, and make smarter decisions using AI-powered intelligence.

---

## 🌟 Highlights

* 📊 Real-time company analysis
* 🤖 AI-driven insights & classification
* 🔔 Smart notification system
* 🔐 Secure authentication (JWT + Google OAuth)
* ⚡ Full-stack production-ready architecture

---

## 🧱 Architecture Overview

```text
Frontend (Next.js)  →  Backend (FastAPI)  →  External APIs (Tavily / AI)
        │                      │
        └──── REST API ────────┘
```

---

## 📁 Project Structure

```bash
marketiq/
├── frontend/   # Next.js frontend
├── backend/    # FastAPI backend
```

---

## ⚙️ Tech Stack

### 🖥️ Frontend

* Next.js
* TypeScript
* Tailwind CSS

### ⚙️ Backend

* FastAPI
* Python
* REST APIs
* JWT Authentication

---

## 🚀 Quick Start

### 🔹 Clone Repo

```bash
git clone https://github.com/YOUR_USERNAME/marketiq.git
cd marketiq
```

---

### 🔹 Start Backend

```bash
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload
```

👉 Runs at: `http://localhost:8000`

---

### 🔹 Start Frontend

```bash
cd frontend
npm install
npm run dev
```

👉 Runs at: `http://localhost:3000`

---

## 🔐 Environment Setup

### Backend `.env`

```env
TAVILY_API_KEY=your_api_key
JWT_SECRET=your_secret
```

---

### Frontend `.env.local`

```env
NEXT_PUBLIC_API_URL=http://localhost:8000
```

---

## 📡 API Example

```http
GET /analyze?company=Tesla&days=7
```

---

## 🎯 Key Features

* 📈 Company news analysis engine
* 🧠 AI domain classification system
* 🔔 Scheduled notifications
* 🔐 User authentication system
* 📊 Insights dashboard

---

## 🛡️ Security

* Environment-based secret management
* No sensitive data exposed in repo

---

## 🧠 Innovation

MarketIQ combines:

* AI-based classification
* Real-time data pipelines
* Modular backend architecture

---
