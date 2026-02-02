🚀 CodeCollab – Real-Time Collaborative Code Editor

CodeCollab is a web-based real-time collaborative code editor that allows multiple users to write and edit code together in the same workspace. It provides instant synchronization of code changes using WebSockets (Socket.IO) and offers a rich in-browser coding experience powered by the Monaco Editor (the core editor behind VS Code).

This project demonstrates modern full-stack web development, real-time systems, and scalable client–server communication. It is suitable for final-year academic submission as well as technical interviews.

🖼️ Preview

(Add screenshots here after running the project)

✨ Features

Real-time collaborative code editing

Room-based collaboration using unique room IDs

Live code synchronization using Socket.IO

VS Code–like editor experience using Monaco Editor

Modern frontend built with Next.js and React

Node.js + Express backend for real-time communication

Optional Docker-based isolated code execution (advanced feature)

🛠️ Tech Stack
Frontend

Next.js

React

TypeScript

Monaco Editor

Backend

Node.js

Express

Socket.IO

Tools & Others

WebSockets

Docker (optional)

npm

⚙️ Installation & Setup

Follow the steps below to clone and run the project on your local machine.

📌 Prerequisites

Make sure you have the following installed:

Node.js (LTS version)

npm

Git

Check versions:

node --version
npm --version
git --version

📥 Clone the Repository

Open a terminal and run:

git clone https://github.com/<your-username>/codecollab.git
cd codecollab

🔧 Backend Setup

Open a terminal in the project root and run:

cd server
npm install
npm start


The backend server will start on:

http://localhost:3001

🎨 Frontend Setup

Open a new terminal window (keep backend running):

cd codecollab
npm install
npm run dev


The frontend will start on:

http://localhost:3000

▶️ How to Use the Application

Open the app in your browser at http://localhost:3000

Enter a room ID and join the room

Open the same room in another browser or device

Start typing code — changes will sync in real time 🎉

🧪 Testing Real-Time Collaboration

Open the application in two different browsers

Join the same room

Type code in one browser

Observe real-time synchronization in the other browser

🐳 Docker Support (Optional)

This project includes optional Docker-based code execution for running user code in isolated containers.

⚠️ Docker is not required for basic real-time collaboration.
If Docker is not installed, the editor will still function normally.

📁 Project Structure
codecollab/
│── src/            # Frontend source code
│── server/         # Backend server (Socket.IO)
│── public/         # Static assets
│── README.md       # Project documentation
│── package.json    # Dependencies and scripts

🎯 Learning Outcomes

Understanding real-time web applications

Implementing WebSocket-based communication

Handling multiple users and collaborative sessions

Full-stack application development using modern tools

🚀 Future Enhancements

User authentication

Language selector (JavaScript, Python, Java)

Code persistence using database

Chat feature inside rooms

Dark/Light mode

👨‍💻 Author

Harsh Jaiswal
B.Tech Computer Science Engineering

📄 License

This project is created for educational purposes.

⭐ Support

If you like this project, don’t forget to star the repository ⭐
