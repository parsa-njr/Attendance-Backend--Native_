# Attendance Backend API

A scalable and modular Node.js backend for an Attendance Management System.
This backend provides APIs for employee attendance tracking, authentication, shift management, leave handling, reporting, and real-time updates.

Built with Express.js, MongoDB, and Socket.IO.

---

# 🚀 Features

* 🔐 JWT Authentication & Authorization
* 👥 User & Employee Management
* 🕒 Attendance Check-In / Check-Out
* 📍 Location-based Validation
* 📅 Shift & Work Schedule Management
* 🧾 Leave & Overtime Requests
* 📊 Attendance Reporting & Excel Export
* 🔔 Real-time Updates with Socket.IO
* 📂 File Upload Support
* 🇮🇷 Jalali (Persian) Date Support
* ⚡ RESTful API Architecture
* 🛡️ Request Validation using Joi

---

# 🛠️ Tech Stack

## Backend

* Node.js
* Express.js
* MongoDB
* Mongoose

## Authentication & Security

* JWT (jsonwebtoken)
* bcrypt

## Validation

* Joi

## Realtime

* Socket.IO

## File Handling

* Multer

## Utilities

* Axios
* Dotenv
* Date-fns
* Moment
* Moment-Jalaali
* Jalaali-JS

## Reports

* ExcelJS

---

# 📦 Installation

## 1. Clone the repository

```bash id="s7m22s"
git clone <repository-url>
cd basic-node-js-project
```

---

## 2. Install dependencies

Using npm:

```bash id="jd82mk"
npm install
```

---

## 3. Create environment variables

Create a `.env` file in the project root:

```env id="2mzvdf"
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

CLIENT_URL=http://localhost:3000
```

---

# ▶️ Running the Project

## Development Mode

```bash id="txg0l7"
npm run dev
```

---

## Production Mode

```bash id="s2n7cs"
npm start
```

---

# 📁 Suggested Project Structure

```bash id="fcb7cg"
project/
│
├── controllers/        # Route controllers
├── models/             # Mongoose models
├── routes/             # API routes
├── middlewares/        # Custom middlewares
├── validations/        # Joi validation schemas
├── services/           # Business logic
├── utils/              # Utility functions
├── uploads/            # Uploaded files
├── sockets/            # Socket.IO logic
├── config/             # Configurations
├── app.js              # Main application entry
└── .env
```

---

# 🔐 Authentication

The API uses JWT-based authentication.

After login, include the token in request headers:

```http id="av23pf"
Authorization: Bearer YOUR_TOKEN
```

---

# 📊 Main Modules

* Authentication
* Employees
* Attendance
* Shifts
* Leave Requests
* Overtime
* Reports
* Notifications
* File Uploads

---

# 📤 Export Reports

The backend supports exporting attendance reports to Excel using ExcelJS.

---

# 🔌 Real-time Features

Socket.IO is used for:

* Live attendance updates
* Notifications
* Real-time dashboard data

---

# 🧪 Testing

```bash id="tk6x4j"
npm test
```

---

# 🌍 API Architecture

* RESTful API Design
* Modular Structure
* Scalable Service-based Architecture

---

# ⚡ Performance & Scalability

* Async error handling with `express-async-errors`
* Optimized MongoDB queries
* Modular and maintainable architecture

---

# 👨‍💻 Developer

Developed with ❤️ using Node.js, Express, and MongoDB.

---


