# MERN Chat Application

A real-time chat application built using the MERN Stack (MongoDB, Express.js, React.js, Node.js). Users can register, log in, and exchange messages in real time.

## 🚀 Features

### Authentication

* User Registration
* User Login
* Password Hashing using bcrypt
* JWT-based Authentication
* Protected Routes

### Chat Features

* One-to-One Messaging
* Real-Time Communication using Socket.IO
* Online/Offline User Status
* Message Timestamps
* Chat History Storage

### User Management

* View Registered Users
* Search Users
* User Profile Information

## 🛠️ Tech Stack

### Frontend

* React.js
* React Router
* Axios
* Socket.IO Client
* CSS / Tailwind CSS

### Backend

* Node.js
* Express.js
* Socket.IO
* JWT Authentication
* bcrypt

### Database

* MongoDB
* Mongoose ODM
```


## 🔐 Environment Variables

### Server

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLIENT_URL=http://localhost:5173
```

## 📦 Installation

### Clone Repository

```bash
git clone <repository-url>
cd mern-chat-app
```

### Install Backend Dependencies

```bash
cd server
npm install
```

### Install Frontend Dependencies

```bash
cd ../client
npm install
```

### Start Backend

```bash
npm run dev
```

### Start Frontend

```bash
npm run dev
```

## 🔄 Application Flow

1. User registers or logs in.
2. JWT token is generated and stored.
3. User connects to Socket.IO server.
4. User selects another user to chat with.
5. Messages are sent through Socket.IO.
6. Messages are stored in MongoDB.
7. Receiver gets messages instantly.
8. Chat history is available on reload.

## 🎯 Future Improvements

* Group Chats
* Message Read Receipts
* Typing Indicators
* Media/File Sharing
* Voice Messages
* Video Calling
* Push Notifications
* User Blocking
  
