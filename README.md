# chat-app-React-SpringBoot

💬 Chat App – React + Spring Boot

A full-stack real-time chat application built using React (Vite) for the frontend and Spring Boot for the backend. This project demonstrates modern web development practices including REST APIs, JWT authentication, and real-time communication.


🚀 Features

🔐 User Authentication (Login / Signup)
💬 Real-time Messaging (Chat Rooms / Private Chat)
🧑‍🤝‍🧑 Multiple Users Support
🔄 Live Updates using WebSocket / Polling
📦 RESTful APIs with Spring Boot
🗄️ MongoDB / MySQL Database Support
⚡ Fast frontend using Vite + React
🛡️ Secure APIs with JWT Authentication

🏗️ Tech Stack
🔹 Frontend

React (Vite)
JavaScript (ES6+)
CSS / Tailwind (if used)
Axios (API calls)


🔹 Backend
Spring Boot
Spring Security
REST APIs
WebSocket (optional)

🔹 Database
MongoDB 


Project Structure
chat-app-React-SpringBoot/
│
├── front-chat/        # React Frontend (Vite)
│   ├── src/
│   ├── public/
│   └── package.json
│
├── chat-app-backend/  # Spring Boot Backend
│   ├── src/main/java/
│   ├── src/main/resources/
│   └── pom.xml
│
└── README.md

⚙️ Setup Instructions
🔹 1. Clone the Repository
git clone https://github.com/Nishant-Sharma-102/chat-app-React-SpringBoot.git
cd chat-app-React-SpringBoot
🔹 2. Frontend Setup (React + Vite)
cd front-chat
npm install
npm run dev

👉 Runs on: http://localhost:5173

🔹 3. Backend Setup (Spring Boot)
cd chat-app-backend
mvn clean install
mvn spring-boot:run

👉 Runs on: http://localhost:8080

🔹 4. Configure Database

Update your application.properties:

For MongoDB:
spring.data.mongodb.uri=mongodb://localhost:27017/chatapp
For MySQL:
spring.datasource.url=jdbc:mysql://localhost:3306/chatapp
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
