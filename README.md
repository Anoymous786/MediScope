# 🩺 MediScope – Specialist Doctor Recommendation & Appointment Booking System

**MediScope** is a full-stack web application designed and developed by **Utkarsh Singh** to help users predict diseases based on symptoms and book appointments with the most suitable specialists. It provides secure access for patients, doctors, and admins with tailored dashboards for each role.

---

## ✨ Features

### 👤 User Functionality
- **User Registration & Login** with JWT security
- **Symptom Input Form**
- **AI-Powered Disease Prediction**
- **Doctor Recommendation** based on predicted disease
- **Appointment Booking System**
- **Appointment Tracking** – Reschedule or cancel
- **Feedback and Ratings System**

### 👨‍⚕️ Doctor Functionality
- **Doctor Account Creation and Login**
- **Doctor Dashboard** – View upcoming appointments
- **Patient Medical History Access**
- **Manage Appointment Status**

### 🛠️ Admin Functionality
- **Admin Dashboard**
- **User and Doctor Management**
- **Global Appointment Monitoring**
- **Analytics and Reports**
- **System Settings Configuration**

### 💡 General Features
- ✅ Responsive UI (Mobile & Desktop)
- 🔒 Role-Based Access Control (JWT)
- 📬 Email/Notification Support
- 💳 Payment Gateway Integration
- 🔍 Search by Doctor, Location, Specialization

---

## 💻 Technologies Used

| Layer         | Technology                         |
|---------------|-------------------------------------|
| Frontend      | Next.js (React) + Tailwind CSS      |
| Backend       | Node.js + Express.js                |
| Authentication| JWT, bcrypt                         |
| Database      | MongoDB + Mongoose                  |
| ML Prediction | Python (optional integration)       |
| Deployment    | Vercel (Frontend), Render (Backend) |
| Payment       | Razorpay / Stripe                   |

---

## 🚀 Installation

### 🔧 1. Clone Repository

```bash
git clone https://github.com/Anoymous786/MediScope.git
cd MediScope
```

### 📦 2. Install Frontend
```bash
cd client
npm install
npm run dev
```
Frontend runs at: [http://localhost:3000](http://localhost:3000)

### 🔧 3. Install Backend
```bash
cd ../server
npm install
```
Create a `.env` file inside `/server`:
```
PORT=5000
MONGO_URI=mongodb://localhost:27017/mediscope
JWT_SECRET=yourSecretKey
```
Run the backend:
```bash
npm run dev
```
Backend runs at: [http://localhost:5000](http://localhost:5000)

---

## ✍️ Author

**Utkarsh Singh**  
GitHub: [Anoymous786](https://github.com/Anoymous786)  
Email: [utsi22ise@cmrit.ac.in](mailto:utsi22ise@cmrit.ac.in)  
LinkedIn: [linkedin.com/in/utkarsh746](https://www.linkedin.com/in/utkarsh746)

---

> ✅ Built by Utkarsh Singh to demonstrate full-stack proficiency in React/Next.js and Node.js, aligned with job roles requiring frontend/backend development experience.
