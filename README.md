# Learning Management System (LMS)

## 🌟 Project Overview

This Learning Management System is a full-stack web application designed to facilitate online education, providing a seamless platform for instructors to create and manage courses while enabling students to discover, purchase, and learn from various educational content.

## ✨ Features

### For Instructors
- Course Creation and Management
- Video Upload Functionality
- Revenue Tracking
- Student Enrollment Monitoring
- Media Management with Cloudinary

### For Students
- Course Browsing
- Course Filtering by Categories
- PayPal Payment Integration
- Video Completion Tracking
- Seamless Learning Experience

## 🚀 Technologies Used

### Frontend
- React.js
- Tailwind CSS
- React Router
- Axios

### Backend
- Node.js
- Express.js
- Mongoose

### Database
- MongoDB

### Additional Technologies
- PayPal Payment Gateway
- Cloudinary
- JSON Web Token (JWT) for Authentication

## 🔧 Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js (v14 or later)
- npm (v6 or later)
- MongoDB
- PayPal Developer Account

## 🛠️ Installation

### Clone the Repository
bash
git clone https://github.com/dhruvbaraiya27/info6150_final-project


### Backend Setup
bash
cd backend
npm install


### Frontend Setup
bash
cd frontend
npm install


## 📝 Environment Variables

Create .env files in both backend and frontend directories with the following variables:

### Backend .env

MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PAYPAL_CLIENT_ID=your_paypal_client_id
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret


### Frontend .env

REACT_APP_PAYPAL_CLIENT_ID=your_paypal_client_id
REACT_APP_API_URL=your_backend_api_url


## 🏃 Running the Application

### Start Backend
bash
cd backend
npm start


### Start Frontend
bash
cd frontend
npm start


## 🧪 Running Tests
bash
npm test


## 📦 Build for Production
bash
npm run build


## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

## 🔒 Authentication

The application uses JWT (JSON Web Tokens) for secure authentication. Users can:
- Register
- Login
- Reset Password

## 💳 Payment Integration

Integrated PayPal payment gateway for secure course purchases.

## 🌈 Future Roadmap
- Live Class Integration
- Advanced Analytics
- Certification System


Project Link: [https://github.com/dhruvbaraiya27/info6150_final-project](https://github.com/dhruvbaraiya27/info6150_final-project)

## 📜 License

Distributed under the MIT License. See LICENSE for more information.

## 🙏 Acknowledgements
- React.js
- Node.js
- Express.js
- MongoDB
- PayPal
- Cloudinary
