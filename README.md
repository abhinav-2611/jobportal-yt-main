# jobportal-yt-main

# Job Portal - MERN Stack Project

This is a **Job Portal Web Application** built using the **MERN stack** (MongoDB, Express.js, React, Node.js). The platform allows users to post and apply for jobs, while administrators can manage listings and users efficiently.

## 🧰 Tech Stack

**Frontend:**
- React.js
- Tailwind CSS
- Axios
- React Router DOM
- Vite

**Backend:**
- Node.js
- Express.js
- MongoDB (with Mongoose)
- JWT Authentication
- dotenv

**Tools & Services:**
- Git & GitHub
- ESLint
- PostCSS
- Vite.js
- VS Code

---

## 📁 Project Structure

obportal-yt-main/
├── backend/ # Node.js + Express backend
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── middlewares/
│ ├── utils/
│ └── index.js # Entry point for backend
│
├── frontend/ # React.js frontend
│ ├── public/
│ ├── src/
│ ├── tailwind.config.js
│ └── vite.config.js



## 🚀 Features

- 🔐 **User Authentication** with JWT
- 👤 Role-based access (User & Admin)
- 📄 Job Posting & Application
- 🔍 Job Search & Filter
- 🧾 Admin Panel to manage users and jobs
- 🛡️ Protected Routes
- 🌐 Responsive UI with Tailwind CSS

---

## 🛠️ Installation & Setup

### 1. Clone the repository


git clone https://github.com/your-username/jobportal-yt-main.git
cd jobportal-yt-main


### 2.  Setup backend

cd jobportal-yt-main/backend
npm install
Create a .env file with the following environment variables:

env

PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
Start the backend server:

bash
npm run dev

### 3. Setup Frontend
bash

cd ../frontend
npm install
npm run dev


✅ Future Enhancements
Resume upload and preview

Email notifications

Advanced filtering

Pagination support

Integration with LinkedIn or other platforms

### 📬 Contact
Author: Abhinav Srivastava