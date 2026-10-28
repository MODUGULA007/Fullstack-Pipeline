# 🚀 Fullstack Pipeline (CI/CD with Docker & GitHub Actions)

![GitHub repo size](https://img.shields.io/github/repo-size/MODUGULA007/Fullstack-Pipeline)
![GitHub last commit](https://img.shields.io/github/last-commit/MODUGULA007/Fullstack-Pipeline)
![GitHub stars](https://img.shields.io/github/stars/MODUGULA007/Fullstack-Pipeline?style=social)
![GitHub forks](https://img.shields.io/github/forks/MODUGULA007/Fullstack-Pipeline?style=social)

---

## 📌 Overview

This is a **Fullstack Web Application** built with **React (Frontend)** and **Node.js + Express (Backend)**, fully containerized using **Docker** and deployed using **CI/CD pipeline via GitHub Actions**.

The project demonstrates:
- Fullstack architecture
- Docker containerization
- Multi-service setup (Frontend + Backend)
- CI/CD automation
- Production-ready deployment flow

---

## 🧱 Tech Stack

### Frontend
- React.js
- Vite
- Nginx (production build)

### Backend
- Node.js
- Express.js

### DevOps / Tools
- Docker
- Docker Compose
- GitHub Actions (CI/CD)
- Git

---

## 📁 Project Structure


Fullstack-Pipeline/
│
├── client/ # React Frontend
│ ├── src/
│ ├── public/
│ └── Dockerfile
│
├── server/ # Node Backend
│ ├── index.js
│ └── Dockerfile
│
├── docker-compose.yml
├── .github/workflows/ # CI/CD pipeline
├── screenshots/ # Project screenshots
└── README.md


---

## 🐳 Docker Setup

### 🔧 Build & Run Containers

```bash
docker-compose up --build
Stop containers
docker-compose down
⚙️ CI/CD Pipeline (GitHub Actions)

This project uses GitHub Actions for:

✔ Auto build on push
✔ Docker image build
✔ Container deployment flow

📌 Workflow Location:
.github/workflows/

📸 CI/CD Pipeline Screenshot

GitHub Actions running
Build success logs
Docker build process
Deployment success
🌐 Application Access
Service	URL
Frontend	http://localhost:3000

Backend	http://localhost:5000

 screenshots inside /screenshots folder:

1. Home Page
2. Backend Running Terminal
3. Docker Containers Running
4. GitHub Actions Workflow Success
5. API Response ( Browser)

Fully containerized fullstack app
Backend API with Express
React frontend UI
Docker Compose orchestration
CI/CD automation using GitHub Actions
Production-ready deployment structure
🧪 API Example
GET /api/health

Response:

{
  "status": "Server is running 🚀"
}
🔥 Future Improvements
Kubernetes deployment
MongoDB integration
JWT Authentication
AWS deployment (EC2 / ECS)
Domain + SSL setup
👨‍💻 Author

MODUGULA007

GitHub: https://github.com/MODUGULA007
