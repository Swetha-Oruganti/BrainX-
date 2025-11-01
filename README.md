# BrainX Full-Stack Project

**BrainX** is an intelligent e-learning platform providing personalized learning paths and AI-powered guidance.  
This project uses a **MERN stack** (MongoDB, Express, React, Node.js) and integrates with the **Gemini API**.

---

## ⚙️ Tech Stack

- **Frontend:** React.js, HTML, CSS, JavaScript, Axios  
- **Backend:** Node.js, Express.js, MongoDB, Mongoose  
- **External API:** Gemini API for AI guidance  

---

## 🚀 Full Setup Instructions

###1️⃣ Clone the repository
```
git clone https://github.com/Swetha-Oruganti/BrainX-.git
```
###2️⃣ Navigate to the backend folder
```
cd BrainX-/server
```
###3️⃣ Install backend dependencies
```
npm install
```

###4️⃣ Create environment variables

Create a .env file in the server folder with the following keys:
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
GEMINI_API_KEY=your_gemini_api_key
GEMINI_API_SECRET=your_gemini_api_secret
```

Replace your_mongodb_connection_string and Gemini API credentials with your own.

###5️⃣ Run the backend server
```
nodemon server.js
```

The backend will run on:

http://localhost:5000

###6️⃣ Navigate to the frontend folder

Open a new terminal window/tab and run:

```
cd BrainX-/frontend
```
###7️⃣ Install frontend dependencies
```
npm install
```
###8️⃣ Run the frontend
```
npm start
```

The frontend will run on:

http://localhost:3000

###📁 Folder Structure
##Backend (server/)
server/
 ├── controllers/       # Route handlers
 ├── models/            # Mongoose models
 ├── routes/            # Express routes
 ├── utils/             # Helper functions, Gemini API integration
 ├── .env               # Environment variables
 ├── package.json
 └── server.js          # Main server entry

##Frontend (frontend/)
frontend/
 ├── src/
 │   ├── components/    # React components
 │   ├── pages/         # Pages / Screens
 │   ├── services/      # API service calls
 │   ├── App.js
 │   └── index.js
 ├── package.json
 └── public/            # Static assets

Testing APIs

Use Postman or Insomnia to test backend APIs. Example endpoints:

GET /api/users
POST /api/login
POST /api/gemini/query

