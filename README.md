# 🏥 Doctor Appointment Booking System

A full-stack **Doctor Appointment Booking System** built with the **MERN stack** (MongoDB, Express.js, React.js, Node.js).  
This project allows patients to **book appointments with doctors online**, while admins and doctors can manage their schedules efficiently.  

---

## ✨ Features

### 👨‍💻 User Features
- 🔐 User Authentication (Register/Login with JWT)
- 🩺 Browse doctors by specialization
- 📅 Book, reschedule, or cancel appointments
- 💳 Online payment integration (Stripe & Razorpay)
- 📄 View booking history

### 🩻 Doctor Features
- 👨‍⚕️ Doctor dashboard to manage appointments
- 📆 Accept or reject appointment requests
- ⏰ Manage availability slots

### 🛠 Admin Features
- 📊 Admin dashboard for managing users, doctors, and appointments
- ✔ Approve or reject doctor registrations
- 💰 Track payment history

---

## 🛠 Tech Stack

**Frontend**  
- React.js  
- React Router DOM  
- Context API / Redux (for state management)  
- Axios (API communication)  
- TailwindCSS  

**Backend**  
- Node.js  
- Express.js  
- MongoDB + Mongoose  
- JWT Authentication  
- Stripe & Razorpay Payment Gateways  

**Other Tools**  
- Git & GitHub for version control  
- Postman for API testing  
- Cloudinary (for doctor/patient profile images)  

---

## 📂 Project Structure

Doctor-appointment-booking-system/
│── backend/ # Node.js + Express + MongoDB server
│ ├── models/ # Database models
│ ├── routes/ # API routes
│ ├── controllers/ # Business logic
│ ├── config/ # DB & server config
│ └── .env # Environment variables (not committed)
│
│── frontend/ # React.js frontend
│ ├── src/
│ │ ├── components/ # Reusable components
│ │ ├── pages/ # Page components
│ │ ├── context/ # State management
│ │ └── utils/ # Helper functions
│ └── package.json
│
│── .gitignore
│── README.md



## 🚀 Getting Started

1️⃣ Clone the Repository

git clone https://github.com/SandeepNehra01/Doctor-appointment-booking-system.git
cd Doctor-appointment-booking-system

2️⃣ Setup Backend
cd backend
npm install

# Create a .env file inside backend/:
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
## npm run server

3️⃣ Setup Frontend
cd ../frontend
npm install
npm start

📝 License
This project is licensed under the MIT License.

👨‍💻 Author
@Sandeep Nehra
📧 sandeepnehra760@gmail.com
🌐 GitHub Profile

