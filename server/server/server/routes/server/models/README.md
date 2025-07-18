# Full Stack To-Do List App

A basic full stack project with:

- **Frontend**: React (folder: `client/`)
- **Backend**: Node.js + Express + MongoDB (folder: `server/`)
- **Database**: MongoDB (Mongoose)

This structure is GitHub-ready for development or deployment.
---

## 🚀 Features

- Add, delete, and update to-do items
- Mark tasks as complete or incomplete
- MongoDB database integration
- RESTful API (CRUD operations)

---

## ⚙️ Technologies Used

- **Frontend**: React, Axios
- **Backend**: Express, Node.js, Mongoose
- **Database**: MongoDB
- **Others**: CORS, dotenv

---

## 🧠 How It Works (Overview)

1. User enters a to-do item in the frontend.
2. It sends a POST request to the backend.
3. The backend stores it in MongoDB.
4. GET, DELETE, PUT requests allow the frontend to interact with the database.

---

## 🛠️ Setup Instructions (Optional)

To run this project locally:

### 1. Clone the repo:
```bash
git clone https://github.com/your-username/todo-fullstack.git
cd todo-fullstack
cd server
npm install
touch .env  # Add MONGO_URI inside this file
node index.js
cd ../client
npm install
npm start
