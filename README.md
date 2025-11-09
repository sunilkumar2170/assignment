💬 Learnato Discussion Forum

A browser-based **discussion forum microservice** built for **Learnato Hackathon 2025**, designed to empower learning through meaningful conversation and collaboration.

Users can **post questions**, **reply in real-time**, **upvote posts**, and **view discussions dynamically** — all with a clean and responsive UI.

---

## 🚀 Features

✅ Create and view discussion posts  
✅ Add replies under posts  
✅ Upvote any post  
✅ Search and sort discussions  
✅ Responsive modern UI  
✅ Works locally or deployable in the cloud  
✅ Fully containerized with Docker

---

## 🧰 Tech Stack

| Layer      | Technology |
|-------------|-------------|
| **Frontend** | React.js, CSS Animations |
| **Backend**  | Node.js + Express.js |
| **Database** | PostgreSQL (Sequelize ORM) |
| **Deployment** | Docker / Render / Vercel |

---

## 🧩 Project Structure

Mini-Course-Dashboard/
│
├── backend/
│ ├── server.js
│ ├── models/
│ ├── routes/
│ ├── package.json
│ └── Dockerfile
│
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ │ └── MainPage.jsx
│ │ └── App.jsx
│ ├── public/
│ ├── package.json
│ └── Dockerfile
│
├── docker-compose.yml
└── README.md

yaml
Copy code

---

## 🧱 Setup Guide

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/sunilkumar2170/assignment.git
cd Mini-Course-Dashboard
2️⃣ Backend Setup
bash
Copy code
cd backend
npm install
npm start
Create a .env file inside the backend directory with the following content:

env
Copy code
PORT=5000
DB_HOST=localhost
DB_USER=postgres
DB_PASS=yourpassword
DB_NAME=discussion_forum
DB_DIALECT=postgres
Backend will run on 👉 http://localhost:5000

3️⃣ Frontend Setup
bash
Copy code
cd ../frontend
npm install
npm start
Frontend will run on 👉 http://localhost:3000

🐳 Docker Setup (Optional but Recommended)
You can run both frontend and backend using Docker with a single command.

Step 1: Build and start containers
bash
Copy code
docker-compose up --build
Step 2: Access the app
Frontend → http://localhost:3000

Backend API → http://localhost:5000

🧪 API Endpoints Overview
Method	Endpoint	Description
POST	/api/posts	Create a new post
GET	/api/posts	Get all posts
GET	/api/posts/:id	Get post with replies
POST	/api/posts/:id/upvote	Upvote a post
POST	/api/posts/:id/reply	Add a reply

