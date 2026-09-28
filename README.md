# HireReady

HireReady is a simple and interactive interview preparation platform designed for college students. It enables real-time audio/video interviews, collaborative code editing, and note sharing — helping students practice and get ready for real interviews.

## Features

* User authentication
* Start or join interviews using a room ID
* One-on-one audio and video calls with **PeerJS**
* Collaborative code editor and notepad
* Real-time chat and updates via **Socket.io**

## Tech Stack

* **Frontend:** React, Tailwind CSS
* **Backend:** Node.js, Express
* **Database:** MongoDB
* **Real-time Communication:** Socket.io, PeerJS

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/AdityAiiitl03/NextStep.git
   cd HireReady
   ```

2. Install backend dependencies:

   ```sh
   cd backend
   npm install
   ```

3. Install frontend dependencies:

   ```sh
   cd ../frontend
   npm install
   ```

4. Create a `.env` file in the `backend` directory with:

   ```sh
   MONGO_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   ```

5. Start the backend:

   ```sh
   cd backend
   npm start
   ```

6. Start the frontend:

   ```sh
   cd ../frontend
   npm run dev
   ```

## Usage

* Sign up or log in.
* Start an interview and share the room ID, or join using an existing room ID.
* Use audio/video, code editor, and notes for real-time practice.

---

Developed with ❤️ by [Aditya](https://github.com/AdityAiiitl03)
