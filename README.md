WEBSITE LINK:https://mern-project-task4-client.onrender.com

This is a MERN (MongoDB, Express, React, Node.js) authentication system that includes:
✅ Login & Signup Forms
✅ Proper Validation & Error Handling
✅ JWT-Based Authentication
✅ Secure Password Hashing (bcrypt)
✅ Protected Routes

 Features
User Registration & Login
Form Validation (Frontend & Backend)
JWT Token Authentication & Authorization.
Password Hashing with bcrypt
Protected Routes in React

Tech Stack
Frontend: React.js, React Router, Axios
Backend: Node.js, Express.js
Database: MongoDB (Mongoose ORM)
Authentication: JWT (JSON Web Token), bcrypt

Folder Structure

/mern-auth  
│── /forntend 
│   ├── /src  
│   │   ├── components  
│   │   ├── pages  
│   │   ├── App.js  
│   │   ├── index.js  
│   ├── package.json  
│  
│── /backend
│   ├── /models  
│   ├── /routes  
│   ├── /middleware  
│   ├── server.js  
│   ├── package.json  
│  
└── README.md  

Authentication Flow
User signs up → Credentials are validated & stored securely.
User logs in → A JWT token is generated and sent to the client.
Protected routes → JWT token is required to access certain routes.


