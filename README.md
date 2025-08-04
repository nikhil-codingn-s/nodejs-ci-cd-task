# Node.js CI/CD Task 🚀

This project demonstrates a CI/CD pipeline using **GitHub Actions** and **DockerHub**.

## 📦 Tech Stack
- Node.js + Express
- Docker
- GitHub Actions

## ⚙️ CI/CD Flow
On every push to the `main` branch:
1. Install dependencies
2. Run dummy test
3. Build Docker image
4. Push image to DockerHub

## 🐳 Run Locally with Docker
```bash
docker run -p 3000:3000 YOUR_DOCKERHUB_USERNAME/nodejs-ci-cd-task
