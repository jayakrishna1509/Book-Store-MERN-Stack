# 📚 Book Store

A full-stack Book Store application built as a dynamic project using the MERN Stack.  
The application helps manage users, books, and authentication with email verification with notifications.

---

## ✅ Deployment

### Backend
The backend is deployed and can be accessed at: [https://book-store-mern-stack-bewg.onrender.com](https://book-store-mern-stack-bewg.onrender.com)

### Frontend
The frontend is deployed and can be accessed at: [https://book-store-mern-stack-bewg.onrender.com](https://book-store-mern-stack-bewg.onrender.com)

## 🚀 Features

- User Registration & Login
- Email Verification using OTP
- Secure Authentication (JWT)
- Book Management (Add / View / Update)
- MongoDB Database Integration
- Clean and Responsive UI
- Environment-based Configuration
- Ready for Deployment

---

## 🛠️ Tech Stack

### Frontend
- React (Vite)
- HTML, CSS, JavaScript

### Backend
- Node.js
- Express.js
- MongoDB
- Nodemailer (Email Service)
- JWT Authentication

---

## 🔐 Email Verification

- OTP-based email verification implemented
- Gmail App Password used for secure email sending
- Nodemailer configured with environment variables

---

## 📖 How to Use

### Prerequisites
- Node.js installed
- MongoDB database running
- Gmail App Password for email verification

## 📂 Project Structure

```
Book-Store/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   ├── utils/
│   ├── .env
│   └── server.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── utils/
│   │   └── App.jsx
│   ├── index.html
│   └── vite.config.js
└── README.md
```

## ⚙️ Configuration

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file with the following variables:
   ```
   MONGODB_URI=your_mongodb_connection_string
   PORT=5000
   JWT_SECRET=your_jwt_secret
   EMAIL_USER=your_gmail_email
   EMAIL_PASS=your_gmail_app_password
   ```
4. Start the backend server:
   ```bash
   npm run dev
   ```
   (For production: `npm start`)

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open your browser and navigate to the displayed local URL (usually http://localhost:5173)

### Building for Production
To build the frontend for production:
```bash
npm run build
```

## 🚩 API EndPoints
### Backend API EndPoints
```
POST /api/v1/auth/register - Register a new user
POST /api/v1/auth/login - Login user
POST /api/v1/auth/verify-otp - Verify OTP
POST /api/v1/auth/forgot-password - Forgot password
PUT /api/v1/auth/reset-password - Reset password
GET /api/v1/auth/me - Get current user
GET /api/v1/auth/logout - Logout user
```

## 🔷 Conclusion
This project demonstrates a complete full-stack application with modern web development write the code and secure authentication mechanisms.
