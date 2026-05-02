}
# 🚀 ILMORA Education – Cinematic SaaS Platform

## 📌 Overview
ILMORA is a cinematic SaaS platform designed to guide students from confusion to successful university admission.

---

## 🧠 Tech Stack

- React + TypeScript
- Vite
- Firebase (Auth + Firestore)
- tRPC-style API
- Modular SaaS architecture

---

## 📁 Project Structure

- /src → Frontend application
- /pages → Routes (Home, Admin, Student)
- /sections → Cinematic landing components
- /components → UI components
- /api → Backend logic
- /lib/firebase.ts → Firebase config

---

## ⚙️ Setup Instructions

### 1. Clone Repo

bash git clone <repo> cd project npm install 

---

### 2. Setup Environment Variables

Create .env:

env VITE_FIREBASE_API_KEY= VITE_FIREBASE_AUTH_DOMAIN= VITE_FIREBASE_PROJECT_ID= VITE_FIREBASE_STORAGE_BUCKET= VITE_FIREBASE_MESSAGING_SENDER_ID= VITE_FIREBASE_APP_ID= 

---

### 3. Run Locally

bash npm run dev 

---

## 🔥 Firebase Setup

1. Go to Firebase Console  
2. Create Project  
3. Enable Authentication (Email/Password)  
4. Create Firestore Database  

---

## 🔐 Admin Access

Admin access is controlled via:

- Firebase user roles (recommended)
- OR email-based restriction

Example:

ts if (user.email === "admin@ilmora.com") {   role = "admin" } 

---

## 🚀 Deployment (Vercel)

1. Push code to GitHub  
2. Import repo in Vercel  
3. Set build command:

npm run build

4. Output directory:

dist

5. Add environment variables in Vercel dashboard  

---

## 📦 Build

bash npm run build 

---

## 🧪 Features

- Cinematic landing page
- Student dashboard
- Admin dashboard
- Authentication system
- Scalable API structure

---

## 📌 Future Improvements

- Role-based Firestore security rules
- Payment integration
- University application tracking
- AI counseling assistant

---

## 👨‍💻 Author

ILMORA Education
                {