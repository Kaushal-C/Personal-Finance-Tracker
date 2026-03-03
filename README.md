Personal Finance Tracker

A full-stack web application to track your income and expenses with a clean and interactive dashboard.
The app also includes a basic health checker module and secure user authentication system.

Built using:

⚛️ React (Frontend)
🟢 Node.js + Express (Backend)
🍃 MongoDB (Database)

🚀 Features

🔐 User Authentication (Register / Login / Logout)
📊 Dashboard with financial summary
➕ Add Income & Expenses
✏️ Edit & Delete Transactions
📅 Track transactions by date
📈 Real-time balance calculation
🏥 Basic Health Checker module
🔒 Secure API with JWT authentication

🛠️ Tech Stack

Frontend

React.js
Axios
React Router
CSS / Tailwind (if used)

Backend

Node.js
Express.js
MongoDB
Mongoose
JSON Web Token (JWT)
bcrypt (Password Hashing)

📂 Project Structure
FinancialTracker/
│
├── frontend/              # React Frontend
│   ├── src/
│   └── public/
│
├── server/              # Node + Express Backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── middleware/
│
└── README.md

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/fintracker.git
cd fintracker
2️⃣ Setup Backend
cd server
npm install

Create a .env file inside the server folder:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

Start the backend server:

npm start
3️⃣ Setup Frontend
cd client
npm install
npm start

Frontend will run on:

http://localhost:3000

Backend runs on:

http://localhost:5000
🔐 Authentication Flow

User registers with email & password

Password is hashed using bcrypt

JWT token is generated upon login

Protected routes require valid token
