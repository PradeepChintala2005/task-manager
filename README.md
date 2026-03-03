📝 Task Manager (MERN Stack)

Frontend-React

Backend-Node.js

Database-MongoDB

A powerful and clean Task Manager Web Application built using the MERN Stack (MongoDB, Express.js, React.js, Node.js).
This application helps users manage daily tasks efficiently with authentication, priority filtering, dark mode, and profile management.


🚀 Features

🔐 User Authentication (JWT based Login & Signup)

📝 Create, Edit & Delete Tasks

⚡ Set Task Priority (High / Medium / Low)

🔍 Filter Tasks by Priority

📋 View:

All Tasks

Pending Tasks

Completed Tasks

🌙 Light & Dark Mode Toggle

🖼️ Upload & Update Profile Picture (Cloudinary Integration)

🔒 Protected Routes & Secure APIs

🛠️ Technologies Used

🔹 Frontend

React.js

Axios

Tailwind CSS (if used)

🔹 Backend

Node.js

Express.js

JWT Authentication

bcrypt (Password Hashing)

🔹 Database

MongoDB

Mongoose

🔹 Cloud Services

Cloudinary (Profile Image Upload)

Render (Deployment)

📁 Project Structure

task-manager/

│

├── backend/

│   ├── controllers/

│   ├── models/

│   ├── routes/

│   ├── middleware/

│   └── server.js

│
├── frontend/

│   ├── src/

│   └── public/

│

└── README.md


⚙️ Installation & Setup

1️⃣ Clone the Repository
git clone https://github.com/PradeepChintala2005/task-manager.git

cd task-manager

2️⃣ Backend Setup
cd backend

npm install

npm run dev

Create a .env file inside backend:

PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

CLOUDINARY_CLOUD_NAME=your_cloud_name

CLOUDINARY_API_KEY=your_api_key

CLOUDINARY_API_SECRET=your_api_secret

3️⃣ Frontend Setup

cd frontend

npm install

npm run dev

🔐 Authentication Flow

User registers with email & password

Password is hashed using bcrypt

JWT token is generated on login

Protected routes verify token before granting access

🧠 Future Improvements

Task deadlines & reminders

Email notifications

Drag & Drop task reordering

Mobile responsive improvements

Deployment with CI/CD

👨‍💻 Author

Pradeep Chintala
🔗 GitHub: https://github.com/PradeepChintala2005

📜 License

This project is licensed under the MIT License.
