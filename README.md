# MovieProject
• Store and manage movies, actors, and their images. • Associate multiple actors with a movie and allow actors to appear in multiple movies. • Edit all the details of a movie (including its list of actors). • Use a React frontend to interact with your backend API.

# 🎬 FlickStack

FlickStack is a full-stack movie and actor management app built using **React**, **Express**, and **MySQL**. It allows you to create, edit, and view movies and their associated actors

---

## ✨ Features

- 📚 Add / edit / delete movies and actors
- 🎭 Link multiple actors to each movie and vice versa (many-to-many)
- 🔍 Real-time search for movies and actors
- 🧱 Backend built with Express + MySQL
- 🎨 Modern dark UI with modals and reusable components

---

## ⚙️ Tech Stack

- **Frontend:** React, Vite, Axios, React-Select
- **Backend:** Node.js, Express, MySQL, node-fetch
- **Styling:** CSS Modules, Dark Theme

---


---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/<your-username>/FlickStack.git
cd FlickStack

# Frontend
cd Frontend
npm install

# Backend
cd ../Backend
npm install

cp .env.example .env


mysql -u root -p < Backend/init.sql

run...

Terminal 1
cd Backend
npm run dev

Terminal 2
cd Frontend
npm run dev


you should copy this to .env
DB_NAME=movies_db
DB_USER=root
DB_PASSWORD=your_password
DB_HOST=localhost
DB_PORT=3306
PORT=5000





