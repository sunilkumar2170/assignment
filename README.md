# 💬 Learnato Discussion Forum

A browser-based discussion forum microservice built for the **Learnato Hackathon 2025**, designed to **empower learning through conversation**.

Users can post questions, reply in real-time, upvote posts, and view discussions dynamically.

---

## Features

✅ Create and view discussion posts  
✅ Add replies under posts  
✅ Upvote any post  
✅ Search and sort discussions  
✅ Responsive modern UI  
✅ Works locally or deployable in cloud  
✅ Fully containerized with Docker  

---

 🧰 Tech Stack

| Layer        | Technology                 |
|---------------|---------------------------|
| Frontend      | React.js, CSS Animations  |
| Backend       | Node.js + Express.js      |
| Database      | PostgreSQL (Sequelize ORM)|
| Deployment    | Docker / Render / Vercel  |

---

🧩 Project Structure

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
│ ├── package.json
│ ├── public/
│ └── Dockerfile
│
├── docker-compose.yml
└── README.md

Clone the Repository

 git clone https://github.com/usernmaeassignment

 

🖥️ 2️⃣ Backend Setup
cd backend
npm install
npm start

.env file inside the backend directory with the following content:

PORT=5000
DB_HOST=localhost
DB_USER=postgres
DB_PASS=yourpassword
DB_NAME=discussion_forum
DB_DIALECT=postgres




Backend will run at: http://localhost:5000



Frontend Setup
cd ../frontend
npm install
npm start


🟣 Frontend will run at: http://localhost:3000


---





