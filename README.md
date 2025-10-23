# 🚀 AI Streaming Starter (FastAPI + Next.js + Clerk + Stripe)

This project demonstrates a **production-ready AI web app** with real streaming responses from OpenAI, secure user authentication, and paid subscriptions.

---

## 🧩 Tech Stack
| Layer | Technology | Purpose |
|-------|-------------|----------|
| Frontend | [Next.js](https://nextjs.org/) (React) | Client-side UI with `"use client"` components |
| Backend | [FastAPI](https://fastapi.tiangolo.com/) | Async Python backend & API gateway |
| AI | [OpenAI API](https://platform.openai.com/) | Real-time streaming responses |
| Auth | [Clerk](https://clerk.com/) | Authentication & session tokens |
| Billing | [Stripe](https://stripe.com/) | Subscription and payment management |
| Hosting | [Vercel](https://vercel.com/) | Deploys the frontend + optional API routes |

---

## ⚙️ Features
✅ Secure authentication with JWT (Clerk)  
✅ Streaming chat responses via FastAPI + OpenAI  
✅ Subscription plans (Stripe integration)  
✅ Modern React frontend using `use client`  
✅ Compatible with mobile clients (SwiftUI)  

---

## 🧠 Architecture Overview
```
[Next.js] → [FastAPI] → [OpenAI]
│ ↑
└── Clerk JWT → verifies user
```

---

## 🚀 Getting Started

### Backend (FastAPI)

cd backend
pip install -r requirements.txt
uvicorn main:app --reload

### Frontend (Next.js)
cd frontend
npm install
npm run dev

MIT License © 2025 Meo Flauta

