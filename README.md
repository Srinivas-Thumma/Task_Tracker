📝 Task Tracker

A full-stack task management web application built with Spring Boot, React, and PostgreSQL (via Docker).
This project helps users manage and organize their daily tasks with a simple and responsive interface.

💡 About the Project

I built this project to strengthen my full-stack development skills using Java and modern web technologies.
Through this project, I learned how to design REST APIs, connect a Spring Boot backend to a PostgreSQL database, and integrate it with a React TypeScript frontend for a seamless user experience.



https://github.com/user-attachments/assets/fb2a3e08-858e-414a-b084-f4531154217f



🚀 Features

🧩 Task Management: Create, edit, delete, and view tasks.

⚡ Spring Boot REST API: Backend handles all business logic and database operations.

🐘 PostgreSQL Integration: Data persistence through Dockerized PostgreSQL container.

🎨 React Frontend: Simple, responsive interface for interacting with the backend.

🧱 Modular Architecture: Clear separation between backend and frontend.

🧰 Containerized Environment: Easily deployable with Docker Compose.

🧰 Tech Stack
Layer	Technology
Frontend	React, TypeScript
Backend	Java, Spring Boot
Database	PostgreSQL (Docker)
API	RESTful architecture
Build Tool	Maven
Version Control	Git, GitHub

⚙️ Installation & Setup
1. Clone the repository
git clone https://github.com/owl-screen/Task_Tracker.git
cd Task_Tracker

2. Start PostgreSQL (via Docker)

If you have a docker-compose.yml file:

docker-compose up -d


Otherwise, start PostgreSQL manually:

docker run --name postgres -e POSTGRES_PASSWORD=yourpassword -p 5432:5432 -d postgres

3. Run the Backend
cd backend
./mvnw spring-boot:run


Backend starts on http://localhost:8080

4. Run the Frontend
cd frontend
npm install
npm start


Frontend starts on http://localhost:3000
