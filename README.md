# 🎓 LearningEdge - A Full-Stack Learning Platform

LearningEdge is a feature-rich, full-stack e-learning platform built with the MERN stack. It provides a comprehensive solution for online education, allowing instructors to create and manage courses while students can browse, purchase, and learn from a variety of courses.

![LearningEdge](screenshots/Schema.png)

## ✨ Features

### For Students
- 📚 Browse and search courses by category
- 🛒 Add courses to cart and purchase using Razorpay
- 📖 Track course progress with video completion
- ⭐ Rate and review courses
- 👤 Manage profile and settings
- 📊 View enrolled courses and learning history

### For Instructors
- 🎬 Create and publish courses with video content
- 📝 Organize courses into sections and subsections
- 📈 Dashboard with earnings and course analytics
- ✏️ Edit and manage existing courses
- 💰 Track revenue and student enrollment

### For Admin
- 👥 Manage all users (students & instructors)
- 📂 Create and manage course categories
- 📊 Platform-wide analytics and oversight

## 🛠️ Tech Stack

### Frontend
- **React.js** - UI Library
- **Redux Toolkit** - State Management
- **React Router** - Navigation
- **Tailwind CSS** - Styling
- **Vite** - Build Tool
- **React Hook Form** - Form Handling
- **Framer Motion** - Animations
- **React Hot Toast** - Notifications
- **Swiper** - Carousels/Sliders

### Backend
- **Node.js** - Runtime Environment
- **Express.js** - Web Framework
- **MongoDB** - Database
- **Mongoose** - ODM
- **JWT** - Authentication
- **Bcrypt** - Password Hashing
- **Nodemailer** - Email Services
- **Cloudinary** - Media Storage
- **Razorpay** - Payment Gateway

## 📁 Project Structure

LearningEdge/
├── frontend/ # React frontend application
│ ├── src/
│ │ ├── components/ # Reusable UI components
│ │ ├── pages/ # Page components
│ │ ├── services/ # API services
│ │ ├── slices/ # Redux slices
│ │ ├── hooks/ # Custom hooks
│ │ └── utils/ # Utility functions
│ └── ...
├── backend/ # Node.js backend application
│ ├── controllers/ # Route controllers
│ ├── models/ # Mongoose models
│ ├── routes/ # API routes
│ ├── middleware/ # Custom middleware
│ ├── config/ # Configuration files
│ ├── utils/ # Utility functions
│ └── mail/ # Email templates
└── screenshots/ # Project screenshots


## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- Cloudinary Account
- Razorpay Account

### Environment Variables

#### Backend (.env)
```env
PORT=4000
MONGODB_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

MAIL_HOST=smtp.gmail.com
MAIL_USER=your_email
MAIL_PASS=your_email_password

CLOUD_NAME=your_cloudinary_cloud_name
API_KEY=your_cloudinary_api_key
API_SECRET=your_cloudinary_api_secret

RAZORPAY_KEY=your_razorpay_key
RAZORPAY_SECRET=your_razorpay_secret
git clone https://github.com/Anantmishra121/LearningEdge--A-full-stack-learning-Platform.git
cd LearningEdge--A-full-stack-learning-Platform
cd backend
npm install
📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

👨‍💻 Author
Anant Mishra

GitHub: @Anantmishra121
🙏 Acknowledgments
Thanks to all contributors who helped in building this platform
Inspired by modern e-learning platforms like Udemy and Coursera
