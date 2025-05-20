
# Academic Portal - Multi Page Web App

## Overview
This project includes:
- Books & Courses Listings
- Student Forum
- User Authentication (JWT)
- Admin Dashboard
- Stripe Payment Integration

## Setup Instructions

### 1. Backend
- Go to `backend/`
- Create a `.env` file:
  ```
  MONGO_URI=mongodb://localhost:27017/academic_portal
  JWT_SECRET=your_jwt_secret
  STRIPE_SECRET_KEY=sk_test_XXXXXX
  ```
- Run:
  ```
  npm install
  node server.js
  ```

### 2. Frontend
- Go to `frontend/`
- Open `index.html` in browser (or serve via Vercel/Netlify)

## Deployment
- Backend: Render, Railway, or Heroku
- Frontend: GitHub Pages, Netlify, or Vercel

