# 🚗 Car Rental Booking Application (MERN Stack)
A full-stack Car Rental Booking Application built using the MERN stack (MongoDB, Express.js, React.js, Node.js), designed to provide a seamless and user-friendly car rental experience. The application enables users to securely register and log in, browse a wide range of available cars, view detailed information with optimized images, and book vehicles for specific dates. Users can also track and manage their booking history through a clean and intuitive interface.

---

## 🎥 Project Demo

[![Watch the video](https://img.youtube.com/vi/E6j7wWdN9_c/0.jpg)](https://youtu.be/E6j7wWdN9_c)



## 📌 Features

### 👤 User Features

* User authentication (Register / Login)
* Browse available cars
* View car details with images
* Book cars for selected dates
* View booking history
* Secure payment-ready booking flow (can be integrated)

### 🛠️ Admin Features

* Admin dashboard
* Add, update, and delete cars
* Manage bookings
* Manage users
* Upload and optimize car images using **ImageKit**

---

## 🧰 Tech Stack

### Frontend

* React.js
* React Router
* Axios
* Tailwind CSS / CSS

### Backend

* Node.js
* Express.js
* MongoDB (Mongoose)
* JWT Authentication
* Role-based access control (Admin/User)

### Other Tools & Services

* ImageKit (image upload & optimization)
* Cloud deployment (Vercel / Render / Railway)
* Git & GitHub

---

## 📂 Project Structure

```
car-rental-app/
│
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── services/
│   │   └── App.js
│   └── package.json
│
├── server/                 # Node & Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   └── server.js
│
├── .env
├── README.md
└── package.json
```

---

## 🔐 Authentication & Authorization

* JWT-based authentication
* Password hashing using bcrypt
* Role-based access (Admin & User)
* Protected routes using middleware

---

## 🗄️ Database Models

### User Model

* name
* email
* password
* role (user/admin)

### Car Model

* name
* brand
* pricePerDay
* image
* availability

### Booking Model

* user
* car
* startDate
* endDate
* totalPrice
* status

---



---

## ▶️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/car-rental-app.git
cd car-rental-app
```

### 2️⃣ Backend Setup

```bash
cd server
npm install
npm run dev
```

### 3️⃣ Frontend Setup

```bash
cd client
npm install
npm start
```

---

---


## 🧪 Future Improvements

* Online payment gateway integration
* Email notifications
* Reviews & ratings


---

## 👨‍💻 Author

**Nishant Kumar Sinha**

