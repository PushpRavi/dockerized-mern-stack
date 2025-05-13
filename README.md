# dockerized-mern-stack
MERN Stack Web App - Dockerized Deployment
📦 MERN Stack Web App - Dockerized Deployment
This repository contains a full-stack MERN (MongoDB, Express.js, React.js, Node.js) web application, containerized using Docker. The project demonstrates modern DevOps practices by building and deploying frontend and backend services independently via Dockerfiles, and orchestrating them using docker-compose.
<img width="308" alt="image" src="https://github.com/user-attachments/assets/a15efb0f-e4d0-42ff-9056-d92faf01222d" />


🚀 Features
Frontend: Built with React, containerized using a multi-stage Dockerfile for production builds.
<img width="818" alt="image" src="https://github.com/user-attachments/assets/94df2634-8d93-422e-b87d-ef34ac9bfe3d" />


Backend: Built with Express and Node.js, uses a Dockerfile for containerized deployment.

Database: MongoDB service included via Docker Compose.

Docker Compose: Manages multi-container setup, enabling seamless development and deployment.

⚙️ Deployment Instructions
Clone the repository:
git clone https://github.com/your-username/mern-docker-app.git
cd mern-docker-app
Build and run containers:

docker-compose up --build
Access the app:

Frontend: http://localhost:3000

Backend API: http://localhost:5000/api

MongoDB: Accessible internally by services via mongodb://mongo:27017/dbname

📁 Technologies Used
Frontend: React.js, HTML, CSS

Backend: Node.js, Express.js

Database: MongoDB

DevOps: Docker, Docker Compose
