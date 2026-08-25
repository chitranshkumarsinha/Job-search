# 🚀 Job Search Platform

A full-stack **MERN** (MongoDB, Express, React, Node.js) job search application that goes beyond listings and applications — it brings the interview *into* the platform with built-in **video calling** and a **live, collaborative code editor**, so recruiters and candidates can conduct technical interviews without ever leaving the app.

[![Live Demo](https://img.shields.io/badge/demo-online-success)](https://new-job-search-1.onrender.com/)
[![Stack](https://img.shields.io/badge/Stack-MERN-61DAFB?logo=react)](https://github.com/chitranshkumarsinha/Job-search)
[![License](https://img.shields.io/badge/license-ISC-blue)](#-license)

🔗 **Live Demo:** [new-job-search-1.onrender.com](https://new-job-search-1.onrender.com/)

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Tech Stack](#️-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Environment Variables](#-environment-variables)
- [Running the App](#-running-the-app)
- [Deployment](#-deployment)
- [Roadmap](#-future-enhancements)
- [Contributing](#-contributing)
- [Author](#-author)
- [License](#-license)

---

## 🌟 Overview

Traditional job boards stop at the application. **Job Search Platform** takes it a step further by combining a classic job-search/application experience with the tools needed to actually run a remote technical interview — video, chat, and a shared code editor — all in one place.

## ✨ Features

| Feature | Description |
|---|---|
| 📹 **Video Calling** | Built-in, browser-based video conferencing for remote interviews — no third-party app required. |
| 💻 **Live Code Editor** | Real-time, collaborative coding environment for on-the-spot technical assessments. |
| 🖥️ **Screen Sharing** | Share screens during technical discussions and walkthroughs. |
| 💬 **Chat Integration** | Text-based communication alongside the video call for links, notes, and quick messages. |
| 🔍 **Job Search & Listings** | Browse and search job postings as a candidate. |
| 🔐 **User Accounts** | Separate flows for candidates and recruiters/employers. |

## 🛠️ Tech Stack

### Frontend
- **React.js** — component-based UI
- **Redux** — global state management
- **React Router** — client-side routing
- **Axios** — HTTP client for API communication
- **CSS3 / Styled Components** — styling and responsive layout

### Backend
- **Node.js** — JavaScript runtime
- **Express.js** — REST API framework
- **MongoDB** — NoSQL document database
- **Mongoose** — schema-based ODM for MongoDB

### Real-Time & Interview Tooling
- **Socket.io** — real-time bidirectional events (chat, editor sync, signaling)
- **WebRTC** — peer-to-peer video calling
- **Piston API** — remote code execution engine powering the live code editor

## 📁 Project Structure

```
Job-search/
├── backend/          # Express API, MongoDB models, routes, controllers, Socket.io server
├── frontend/          # React application (UI, Redux store, routes, components)
├── .gitignore
├── package.json       # Root-level scripts / dependencies
└── README.md
```

## 🚦 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v16+ recommended)
- [npm](https://www.npmjs.com/)
- A [MongoDB](https://www.mongodb.com/) instance (local or [MongoDB Atlas](https://www.mongodb.com/atlas))

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/chitranshkumarsinha/Job-search.git
   cd Job-search
   ```

2. **Install backend dependencies**
   ```bash
   cd backend
   npm install
   ```

3. **Install frontend dependencies**
   ```bash
   cd ../frontend
   npm install
   ```

## 🔑 Environment Variables

Create a `.env` file inside the `backend/` directory with the variables your server needs, for example:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLIENT_URL=http://localhost:3000
```

> ⚠️ Check `backend/` for the exact variable names expected by the codebase, and never commit your `.env` file.

## ▶️ Running the App

**Start the backend server:**
```bash
cd backend
npm start
```

**Start the frontend (in a separate terminal):**
```bash
cd frontend
npm start
```

The frontend will typically run on `http://localhost:3000` and the backend API on `http://localhost:5000` (or whatever `PORT` you configured).

## ☁️ Deployment

The application is live and deployed on **Render**:
🔗 [https://new-job-search-1.onrender.com/](https://new-job-search-1.onrender.com/)

## 🔮 Future Enhancements

- [ ] AI-powered job recommendations
- [ ] Resume builder with templates
- [ ] Skill assessment tests

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 👨‍💻 Author

**Chitransh Kumar Sinha**

- GitHub: [@chitranshkumarsinha](https://github.com/chitranshkumarsinha)
- LinkedIn: [linkedin.com/in/cksinha121](https://linkedin.com/in/cksinha121)
- Email: cksinha844115@gmail.com

## 📄 License

This project currently has no explicit license file. Consider adding one (e.g., MIT) if you plan to accept outside contributions.

---

⭐ If you find this project useful, consider giving it a star on [GitHub](https://github.com/chitranshkumarsinha/Job-search)!
