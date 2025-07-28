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

yaml
Copy
Edit

---

## ⚙️ Installation

### 1. Clone the repo

```bash
git clone https://github.com/your-username/grab-your-meal-mern.git
cd grab-your-meal-mern
2. Install Backend
bash
Copy
Edit
cd backend
npm install
npm start
3. Install Frontend
bash
Copy
Edit
cd ../frontend
npm install
npm start
🌐 Environment Variables
🔐 In /backend/.env
env
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
📸 Screenshots
Add your screenshots inside /frontend/public/screenshots and reference them here:

markdown
Copy
Edit
![Admin Dashboard](./frontend/public/screenshots/admin-dashboard.png)
![Customer Booking](./frontend/public/screenshots/customer-booking.png)
```

👨‍💻 Author
Developed by Nikita Sain
Feel free to fork, star ⭐, and contribute!
