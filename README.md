Live Chat App

Overview
The Live Chat App is a real-time chat application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It enables users to send and receive messages instantly with an intuitive UI, real-time updates, and theme toggle functionality. The application is designed to be scalable, secure, and responsive, making it an ideal solution for modern communication needs.

Features
•	User Authentication (Login/Signup with JWT-based authentication)
•	Real-time Messaging using WebSockets (powered by Socket.io)
•	One-on-One & Group Chats with message history stored in MongoDB
•	Theme Toggle (Light/Dark Mode) for enhanced user experience
•	Responsive UI ensuring seamless experience across devices (desktop, tablet, mobile)
•	Secure End-to-End Communication with encrypted messages
•	Scalability allowing easy integration with additional features in the future

Technology Requirement
•	Frontend: React.js, Tailwind CSS, Redux 
•	Backend: Node.js, Express.js
•	Database: MongoDB 
•	Real-time Communication: Socket.io 
•	Authentication: JWT (JSON Web Token) for secure user authentication

Installation & Setup

Prerequisites

Ensure you have the following installed:
•	Node.js (Latest LTS version recommended)
•	MongoDB (Local or MongoDB Atlas for cloud database)
•	Git (for version control)
Clone the Repository
git clone https://github.com/username /repository name.git

cd Live-chat-App

Install Dependencies

Backend
cd server
npm install
Frontend

cd ../client
npm install

Environment Variables

Create a .env file in the server directory and configure the following:
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
SOCKET_PORT=your_socket_port
CLIENT_URL=http://localhost:3000

Running the Application
Start the Backend Server
cd server
npm run dev
Start the Frontend
cd client
npm start
The app will be running at http://localhost:3000.


Future Enhancements
•	Voice & Video Calls
•	Message Reactions (Emojis, GIF support)
•	Multi-language Support
•	Integration with Third-party APIs (Google Auth, Payments, etc.)
•	AI-powered Chatbot Assistance

License
This project is licensed under the MIT License.

