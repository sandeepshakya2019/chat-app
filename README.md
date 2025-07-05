# 💬 Real-Time Chat App

A real-time chat application built with **Node.js**, **Socket.IO**, **Express**, and **MongoDB**, allowing users to join chat rooms and exchange messages instantly.

---

## 🚀 Features

- Real-time messaging using **Socket.IO**
- Join and leave custom chat rooms
- Broadcast messages to all users in a room
- Stores messages in **MongoDB**
- Clean and responsive UI
- Modular backend structure

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript *(React if used)*
- **Backend**: Node.js, Express.js
- **Realtime**: Socket.IO
- **Database**: MongoDB (Mongoose)

---


## Video related to the app

https://github.com/sandeepshakya2019/chat-app/assets/51978973/f71f841c-342c-4cbc-8628-9666fb7a5b03


---

## 🧑‍💻 Getting Started

### 🔧 Backend Setup

1. Clone the repo:

```bash
git clone https://github.com/sandeepshakya2019/chat-app.git
cd chat-app/backend
```

2. Create a .env file (refer .sampleenv):
```
MONGO_URI=mongodb://localhost:27017
JWT_SECRET=your_jwt_secret
ADMIN_SECRET_KEY=your_admin_secret

NODE_ENV=DEVELOPMENT
CLIENT_URL=http://localhost:3000

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

```

3. Start MongoDB server locally.

4. Install backend dependencies:
```npm install```

5. Run the backend:
```npm run dev```


### 💻 To Run the Frontend

1️. Download or clone the frontend/ folder

2️. Open terminal inside the folder and run:
```npm install```
This will install all required dependencies.

3️. Start the development server with:
```npm run start```
The app will run on: http://localhost:3000
Make sure the backend is also running (typically at http://localhost:5000).
