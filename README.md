# SigmaGPT – Intelligent Conversational Agent

**SigmaGPT** is a web-based conversational AI application similar to ChatGPT. It leverages **OpenAI APIs** to provide intelligent responses to user queries in real-time. Built using the **MERN stack** (MongoDB, Express, React, Node.js), SigmaGPT demonstrates a full-stack AI application integrating advanced language models with a modern web interface.

---

## 🔹 Features

- Chat with an AI model powered by OpenAI GPT APIs
- Real-time conversation interface
- Persistent session (chat history)
- Responsive and user-friendly UI built with React and CSS
- Backend powered by Node.js + Express
- Secure API handling for OpenAI keys
- Easily extensible for multi-functional AI capabilities

---

## 🛠 Technology Stack

| Layer | Technology |
|-------|------------|
| Frontend | React, Vite, HTML, CSS, JavaScript |
| Backend | Node.js, Express |
| Database | MongoDB |
| AI | OpenAI GPT API |
| Version Control | Git & GitHub |

---

## 📁 Folder Structure
sigmagpt/
├── Backend/
│ ├── models/ # Mongoose schemas
│ │ └── Thread.js
│ ├── routes/ # API routes
│ │ └── chat.js
│ ├── utils/ # Helper functions (OpenAI integration)
│ │ └── openai.js
│ ├── server.js # Express server entry
│ ├── package.json
│ └── package-lock.json
├── Frontend/
│ ├── src/
│ │ ├── App.jsx
│ │ ├── Chat.jsx
│ │ ├── ChatWindow.jsx
│ │ ├── Sidebar.jsx
│ │ ├── MyContext.jsx
│ │ ├── CSS files
│ │ └── assets/
│ ├── public/
│ │ └── vite.svg
│ ├── package.json
│ └── vite.config.js
├── .gitignore
└── README.md


---

## ⚡ Installation

### 1. Clone the repository

git clone https://github.com/<your-username>/SigmaGPT.git
cd SigmaGPT

2. Setup Backend
cd Backend
npm install


Create a .env file in Backend/:

OPENAI_API_KEY=your_openai_api_key
MONGO_URI=your_mongodb_connection_string
PORT=5000


Start backend server:

npm start

3. Setup Frontend
cd ../Frontend
npm install
npm run dev


Open http://localhost:5173 (Vite default) to access SigmaGPT

Usage

Type your message in the chat input

AI responds in real-time using OpenAI GPT

Chat history can be maintained if MongoDB integration is enabled

Notes

Keep your .env file secret

Node.js v16+ is recommended

MongoDB Atlas recommended for cloud database

Future Enhancements

Multi-user chat sessions

Voice input & output

Advanced analytics for chat patterns

Deploy to cloud (Render / Vercel)


