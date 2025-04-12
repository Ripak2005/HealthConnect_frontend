# 🏥 HealthConnect - Doctor Appointment Booking System

**HealthConnect** is a full-featured, scalable **MERN Stack web application** that streamlines the process of booking doctor appointments online. It offers **role-based dashboards** for **Patients**, **Doctors**, and **Admins**, with secure authentication, online payments, and real-time appointment management.

## 🔗 Live Demo

🚀 [View Live Project](https://health-connect-frontend.vercel.app/)  

---

## 📌 Features

### 👥 Patient Panel
- Register/Login securely
- Browse and book appointments with doctors
- Pay appointment fee online (Stripe/Razorpay)
- View and manage booked appointments

### 🩺 Doctor Dashboard
- Doctor login with secure auth
- View upcoming appointments
- Track total earnings
- Edit and update doctor profile

### 🛠️ Admin Panel
- View and manage all appointments
- Add/update/delete doctor profiles
- Role-based access and analytics

---

## 🔐 Authentication & Security

- JWT-based authentication
- Passwords hashed using bcrypt
- Role-based route protection (Patient, Doctor, Admin)

---

## 💳 Payment Integration

- Integrated **Razorpay** for secure and instant online payments
- Payment success/failure tracking
- Transaction history management

---

## 💻 Tech Stack

| Frontend  | Backend     | Database   | Auth   | Payment |
|-----------|-------------|------------|--------|---------|
| React.js  | Node.js     | MongoDB    | JWT    | Stripe / Razorpay |
| Tailwind CSS | Express.js | Mongoose | bcrypt |         |

---

## ⚙️ Installation

1. Clone the repo  
```bash
git clone [https://github.com/Ripak2005/HealthConnect_frontend.git]
cd healthconnect
```
2. Install dependencies
```bash
npm install
```
3. Run
```bash
npm run dev


