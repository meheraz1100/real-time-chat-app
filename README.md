# 💬 Real-Time Chat App

A full-stack real-time chat application built using **React**, **TailwindCSS**, **Node.js**, **Express**, **Socket.IO**, and **MongoDB**. This app allows users to register, log in, and engage in instant messaging with other users in real time.

---
<img width="1908" height="907" alt="image" src="https://github.com/user-attachments/assets/a2417f00-da93-454c-9969-fc9c57cde9cd" />

## 🚀 Live Demo

> [Live Site](https://real-time-chat-app-y2ne.onrender.com)

---

## 📌 Features

- 🔐 **Authentication** with JWT (login & register)
- 🧑‍🤝‍🧑 **User List** to see online users
- 💬 **Real-Time Messaging** using Socket.IO
- 🗃️ **MongoDB** for storing users and messages
- ⚡ Smooth UI with **React + TailwindCSS**
- 🔁 Auto-scroll and real-time message updates
- 🔐 Password hashing with **bcrypt**

---

## 🛠️ Tech Stack

**Client:**  
- React  
- TailwindCSS  
- Axios  
- Socket.IO Client  

**Server:**  
- Node.js  
- Express.js  
- Socket.IO  
- MongoDB  
- Mongoose  
- bcrypt  
- JSON Web Token (JWT)  
- dotenv  

---

## 🧑‍💻 Getting Started

### 🔧 Prerequisites

- Node.js & npm installed
- MongoDB database (local or cloud e.g. MongoDB Atlas)

### 📦 Installation

#### Clone the repo
```bash
git clone https://github.com/meheraz1100/real-time-chat-app.git
cd real-time-chat-app
Install Server Dependencies
```


```bash
cd server
npm install
```

Set up Environment Variables
Create a .env file inside the server folder:


PORT=5001
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
Start the Backend Server

```bash
npm start
```


Install Client Dependencies
```bash
cd ../client
npm install
```

Start the React App

```bash
npm run dev
```

📁 Project Structure

real-time-chat-app/
│
├── client/               # React Frontend
│   └── ...
├── server/               # Express Backend
│   ├── models/           # Mongoose models
│   ├── routes/           # API routes
│   └── index.js          # Main server file

🤝 Contribution
Pull requests are welcome! If you'd like to improve the app or fix bugs:

Fork the repository

Create your branch (git checkout -b feature/feature-name)

Commit your changes (git commit -m 'Add some feature')

Push to the branch (git push origin feature/feature-name)

Open a Pull Request

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙋‍♂️ Author
[Mosaiyeb Meheraz](https://github.com/meheraz1100)

🔗 [GitHub](https://github.com/meheraz1100)

📧 [Email](mosaiyebmeheraz@gmail.com)

