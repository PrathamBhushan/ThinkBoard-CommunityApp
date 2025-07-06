# 🧠 ThinkBoard – A Note-Taking Community App

ThinkBoard is a modern, full-stack note-taking platform designed for collaborative student and college communities. Built with the MERN stack (MongoDB, Express, React, Node.js), it supports basic note creation and management with a clean, responsive UI.

---

## 🔧 Features

- 📝 Create, read, update, delete notes
- 💾 MongoDB-based data persistence
- ⚙️ Express REST API
- 🖥️ React frontend with Tailwind CSS & DaisyUI
- 📦 Axios for API requests
- 🚫 Rate limiting using Upstash Redis (100 reqs/min)

---

## 🚀 Live Demo
[🔗 Deployed App](https://thinkboard-communityapp.onrender.com) 

---

## 📁 Project Structure

```
├── backend/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── index.js
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   ├── lib/
│   │   └── components/
```

---

## ⚙️ Tech Stack

- **Frontend**: React, Vite, Tailwind CSS, DaisyUI
- **Backend**: Node.js, Express
- **Database**: MongoDB, Mongoose
- **Rate Limiting**: @upstash/ratelimit

---

## 🧪 .env Setup

### Backend (`/backend`)

```
MONGO_URI=<your_mongo_uri>

UPSTASH_REDIS_REST_URL=<your_redis_rest_url>
UPSTASH_REDIS_REST_TOKEN=<your_redis_rest_token>

NODE_ENV=development
```

## 🔧 Run the Backend

```
cd backend
npm install
npm run dev
```

## 💻 Run the Frontend

```
cd frontend
npm install
npm run dev
```

## ✨ Improvements You Can Add

- Authentication (JWT, session-based, etc.)
- Markdown editor or rich-text support
- Search and filter notes
- Tags and categories
- Light/Dark mode toggle
- Real-time collaborative editing via WebSockets

---

## 📜 License
MIT License © 2025 Pratham Bhushan Ghiloria

---

## 🙌 Contributions
Feel free to fork this project and enhance it. Pull requests are welcome!

---

## 🔗 Connect
- [LinkedIn](https://www.linkedin.com/in/pratham-bhushan-34564a24a/)
- [GitHub](https://github.com/prathambhushan)

> Made with ❤️ for students by a student.
