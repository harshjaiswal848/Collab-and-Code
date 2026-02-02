#🚀 CodeCollab – Real-Time Collaborative Code Editor#

CodeCollab is a web-based real-time collaborative code editor that allows multiple users to write and edit code together in the same workspace. It provides instant synchronization of code changes using WebSockets (Socket.IO) and offers a rich in-browser coding experience powered by the Monaco Editor (the editor behind VS Code).

🖼️ Preview

(Add screenshots here after running the project)

✨ Features

Real-time collaborative code editing

Room-based collaboration using unique room IDs

Live code synchronization with Socket.IO

VS Code–like editor using Monaco Editor

Modern UI built with Next.js

Node.js + Express backend

Optional Docker-based isolated code execution

🛠️ Tech Stack
🔹 Frontend

Next.js

React

TypeScript

Monaco Editor

🔹 Backend

Node.js

Express

Socket.IO

🔹 Tools

WebSockets

Docker (optional)

npm

⚙️ Installation & Setup
📌 Prerequisites

Make sure you have:

Node.js (LTS)

npm

Git

Check versions:

node --version
npm --version
git --version

📥 Clone the Repository
git clone https://github.com/<your-username>/codecollab.git
cd codecollab

🔧 Backend Setup
cd server
npm install
npm start


Backend runs on:

http://localhost:3001

🎨 Frontend Setup

Open a new terminal window:

npm install
npm run dev


Frontend runs on:

http://localhost:3000

▶️ How to Use

Open http://localhost:3000

Enter a Room ID

Open the same Room ID in another browser

Start coding together in real time 🚀

📁 Project Structure
codecollab/
│── src/
│── server/
│── public/
│── README.md
│── package.json

🎯 Learning Outcomes

Real-time web application development

WebSocket-based communication

Collaborative system design

Full-stack development skills

🚀 Future Enhancements

🔹 User authentication

🔹 Multi-language support

🔹 Code persistence

🔹 In-room chat

🔹 Dark/Light mode

👨‍💻 Author

Harsh Jaiswal
B.Tech Computer Science Engineering

⭐ Support

If you like this project, please star ⭐ the repository.
