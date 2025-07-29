# 🍽️ Grab Your Meal – MERN Stack

**Grab Your Meal** is a full-stack food booking platform using the MERN stack. It has two panels: **Admin** for managing meals, pricing plans, and customer bookings, and **Customer** for booking meals for fixed durations (1 month, 2 months) or custom day ranges.

---

## 🧩 Features

### 👨‍🍳 Admin Panel

- Manage Meals and Pricing Plans
- Manage Customers
- Manage & Customize Bookings
- Change Booking Status: Pending, Approved, Cancelled, Rejected

### 👤 Customer Panel

- Register/Login
- Book Meals for:
  - 1 month
  - 2 months
  - Custom: 1 to N days
- Track Booking Status
- Update Profile

---

## 🛠️ Tech Stack

- **Frontend:** React.js (in `/frontend`)
- **Backend:** Node.js, Express.js (in `/backend`)
- **Database:** MongoDB (via Mongoose)
- **Auth:** JWT
- **UI Framework:** Bootstrap / Tailwind

---

## 📁 Folder Structure

/frontend ← React frontend
└── public/
└── src/
└── components/
└── pages/
└── App.js

/backend ← Node + Express backend
└── models/
└── routes/
└── controllers/
└── server.js

.env ← Environment variables

---

## ⚙️ Installation

### 1. Clone the repo

git clone https://github.com/NikitaSain20/Grab-Your-Meal-MERN
cd grab-your-meal-mern

### 2. Install Backend

cd backend
npm install
npm start

### 3. Install Frontend

cd ../frontend
npm install
npm start

### 4.Set Environment Variables

🔐 In /backend/.env
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret

## 📸 Screenshots

<div align="center">
  <img src="public/screenshots/1.png" width="45%" style="margin: 10px;" />
  <img src="public/screenshots/2.png" width="45%" style="margin: 10px;" />
  <br/>
  <img src="public/screenshots/3.png" width="45%" style="margin: 10px;" />
  <img src="public/screenshots/4.png" width="45%" style="margin: 10px;" />
  <br/>
  <img src="public/screenshots/5.png" width="45%" style="margin: 10px;" />
  <img src="public/screenshots/6.png" width="45%" style="margin: 10px;" />
</div>

## 👨‍💻 Author

<br/>
Developed by Nikita Sain.
Feel free to fork, star ⭐, and contribute!
```
