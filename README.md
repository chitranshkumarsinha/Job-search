# 🚀 Job Search Platform

A comprehensive full-stack job search application built with the MERN stack, featuring integrated video calling and a live code editor for seamless remote technical interviews.

[![Live Demo](https://img.shields.io/badge/demo-online-success)](https://new-job-search-1.onrender.com/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![MERN](https://img.shields.io/badge/Stack-MERN-61DAFB?logo=react)](https://github.com/chitranshkumarsinha/Job-search)

## 🌟 Features

### For Job Seekers
- **Advanced Job Search**: Find opportunities with powerful filtering and search capabilities
- **User Profiles**: Create and manage comprehensive professional profiles
- **Application Tracking**: Monitor the status of your job applications
- **Resume Management**: Upload and manage multiple versions of your resume

### For Employers
- **Job Posting**: Create and manage job listings with detailed requirements
- **Candidate Management**: Review applications and track candidate progress
- **Integrated Interview Tools**: Conduct technical interviews without leaving the platform

### Interview Features
- **📹 Video Calling**: Built-in video conferencing for remote interviews
- **💻 Live Code Editor**: Real-time collaborative coding environment
- **Screen Sharing**: Share screens during technical discussions
- **Chat Integration**: Text-based communication alongside video calls

## 🛠️ Tech Stack

### Frontend
- **React.js**: UI library for building interactive interfaces
- **Redux**: State management
- **React Router**: Client-side routing
- **Axios**: HTTP client for API requests
- **CSS3/Styled Components**: Styling and responsive design

### Backend
- **Node.js**: JavaScript runtime environment
- **Express.js**: Web application framework
- **MongoDB**: NoSQL database
- **Mongoose**: MongoDB object modeling

### Real-time Features
- **Socket.io**: Real-time bidirectional communication
- **WebRTC**: Video calling functionality
- **CodeMirror/Monaco Editor**: Live code editor integration

## 📋 Prerequisites

Before running this project, make sure you have the following installed:

- Node.js (v14.x or higher)
- npm or yarn
- MongoDB (v4.x or higher)
- Git

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/chitranshkumarsinha/Job-search.git
cd Job-search
```

### 2. Install dependencies

#### Backend
```bash
cd backend
npm install
```

#### Frontend
```bash
cd frontend
npm install
```

### 3. Environment Variables

Create a `.env` file in the backend directory with the following variables:

```env
# Server Configuration
PORT=5000
NODE_ENV=development

# Database
MONGODB_URI=your_mongodb_connection_string

# Authentication
JWT_SECRET=your_jwt_secret_key
JWT_EXPIRE=7d

# Email Configuration (for notifications)
SMTP_HOST=your_smtp_host
SMTP_PORT=587
SMTP_USER=your_email@example.com
SMTP_PASS=your_email_password

# Cloud Storage (for resume uploads)
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_key
CLOUDINARY_API_SECRET=your_cloudinary_secret

# WebRTC/Video Calling
PEER_SERVER_HOST=your_peer_server_host
PEER_SERVER_PORT=9000
```

Create a `.env` file in the frontend directory:

```env
REACT_APP_API_URL=http://localhost:5000
REACT_APP_SOCKET_URL=http://localhost:5000
```

### 4. Run the Application

#### Development Mode

**Backend:**
```bash
cd backend
npm run dev
```

**Frontend:**
```bash
cd frontend
npm start
```

The application will be available at:
- Frontend: `http://localhost:3000`
- Backend: `http://localhost:5000`

#### Production Mode

```bash
# Build frontend
cd frontend
npm run build

# Start backend server
cd backend
npm start
```

## 📁 Project Structure

```
Job-search/
│
├── backend/
│   ├── config/           # Configuration files
│   ├── controllers/      # Route controllers
│   ├── models/          # Database models
│   ├── routes/          # API routes
│   ├── middleware/      # Custom middleware
│   ├── utils/           # Utility functions
│   ├── socket/          # Socket.io configuration
│   └── server.js        # Entry point
│
├── frontend/
│   ├── public/          # Static files
│   ├── src/
│   │   ├── components/  # React components
│   │   ├── pages/       # Page components
│   │   ├── redux/       # Redux store and slices
│   │   ├── services/    # API services
│   │   ├── utils/       # Helper functions
│   │   ├── App.js       # Main App component
│   │   └── index.js     # Entry point
│   └── package.json
│
├── .gitignore
├── package.json
└── README.md
```

## 🔑 Key Functionalities

### User Authentication
- User registration and login
- JWT-based authentication
- Password encryption with bcrypt
- Email verification (optional)

### Job Management
- Create, read, update, delete job postings
- Advanced search with filters
- Job categorization and tagging
- Saved jobs feature

### Application Process
- One-click job applications
- Application status tracking
- Resume attachment
- Cover letter submission

### Interview Scheduling
- Calendar integration
- Automated email notifications
- Video interview links
- Code editor session management

## 🎨 Screenshots

> Add screenshots of your application here to showcase the UI

## 🚀 Deployment

The application is deployed on Render: [https://new-job-search-1.onrender.com/](https://new-job-search-1.onrender.com/)

### Deploy Your Own

#### Render/Heroku
1. Create a new Web Service
2. Connect your GitHub repository
3. Set environment variables
4. Deploy

#### MongoDB Atlas
1. Create a cluster
2. Get connection string
3. Add to environment variables

## 🧪 Testing

```bash
# Run backend tests
cd backend
npm test

# Run frontend tests
cd frontend
npm test
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Chitransh Kumar Sinha**

- GitHub: [@chitranshkumarsinha](https://github.com/chitranshkumarsinha)
- LinkedIn: [Add your LinkedIn profile]
- Email: [Add your email]

## 🙏 Acknowledgments

- Thanks to all contributors who have helped shape this project
- Inspired by modern job platforms like LinkedIn and Indeed
- Built with passion for improving the remote hiring process

## 📧 Contact

For any queries or suggestions, feel free to reach out:

- Create an issue in this repository
- Email: [your-email@example.com]

## 🔮 Future Enhancements

- [ ] AI-powered job recommendations
- [ ] Resume builder with templates
- [ ] Skill assessment tests
- [ ] Company review system
- [ ] Mobile application (React Native)
- [ ] Advanced analytics dashboard
- [ ] Multi-language support
- [ ] Social media integration

---

⭐ If you found this project helpful, please give it a star!

Made with ❤️ using MERN Stack
