BrainX Backend (MERN + Gemini API)

This is the backend for BrainX, an intelligent e-learning platform with AI-powered guidance.
It is built using Node.js, Express, MongoDB, and integrates with the Gemini API for additional functionality.

⚙️ Tech Stack

Node.js (v18+ recommended)

Express.js

MongoDB

Mongoose (MongoDB ORM)

Axios / Gemini API for external AI integration

🚀 Getting Started
1️⃣ Clone the repository
git clone https://github.com/Swetha-Oruganti/BrainX-.git

2️⃣ Navigate to the backend folder
cd BrainX-/server

3️⃣ Install dependencies
npm install

4️⃣ Create environment variables

Create a .env file in the server folder with the following keys:

PORT=5000
MONGO_URI=your_mongodb_connection_string
GEMINI_API_KEY=your_gemini_api_key
GEMINI_API_SECRET=your_gemini_api_secret


Replace with your actual MongoDB URI and Gemini API credentials.

5️⃣ Run the server
npm start


or for development with auto-reload:

npm run dev


The server will start on:

http://localhost:5000

🧩 API Testing

Use Postman or Insomnia to test APIs. Example endpoints:

GET /api/users
POST /api/login
POST /api/gemini/query

🛠️ Common Scripts
Task	Command
Start server	npm start
Start dev server	npm run dev
Install packages	npm install
Test APIs	Use Postman / Insomnia
📁 Folder Structure
server/
 ├── controllers/       # Route handlers
 ├── models/            # Mongoose models
 ├── routes/            # Express routes
 ├── utils/             # Helper functions, Gemini API integration
 ├── .env               # Environment variables
 ├── package.json
 └── server.js          # Main server entry

🤝 Contributing

Open issues or pull requests for bug fixes and improvements.

🧾 License

MIT License
