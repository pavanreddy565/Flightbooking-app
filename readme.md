# ✈️ Flight Booking App

The **Flight Booking App** is a full-stack web application built using the **MERN stack** (MongoDB, Express.js, React, Node.js). It enables users to book flights, manage flight schedules, and oversee the platform based on their roles.

## 🚀 Features

- **Customer**: 
  - Search and book flights.
  - View booking history.

- **Flight Operator**:
  - Add and manage flight schedules.
  - Await admin approval before accessing platform features.

- **Admin**:
  - Authenticate and approve new flight operators.
  - Oversee users, flights, and bookings.
  - Manage the entire application.

## 🔐 Special Feature

- **Operator Authentication**: Every new flight operator must be authenticated and approved by the admin before they can use the system.

---

## 🛠 Tech Stack

- **Frontend**: React
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Other**: Mongoose, JWT (authentication), REST APIs

---

## 📦 Getting Started

Follow the steps below to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/pavanreddy565/Flightbooking-app.git
```

### 2. Backend Setup

```bash
cd ../server
npm install
node index.js
```

> Server will start on the configured port (default: `http://localhost:6001`).

### 3. Frontend Setup

```bash
cd ../client
npm install
npm start
```

> React app will start on `http://localhost:3000`

### 📁 Project Structure
```bash
Flightbooking-app/
│
├── client/         # React frontend
└── server/         # Express backend & MongoDB connection
```
