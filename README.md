"# 🚀 CI/CD Node.js App with Docker and GitHub Actions

This project demonstrates a complete **CI/CD pipeline** for a simple Node.js web application using **GitHub Actions** and **Docker**. On every push to the `main` branch, the workflow automatically:

- Installs dependencies
- (Optionally) runs tests
- Builds a Docker image
- Pushes the image to DockerHub

> 💡 Bonus: The app is also tested and previewed using **GitHub Codespaces** with port forwarding.

---

## 🔧 Tech Stack

- **Node.js** + Express
- **Docker** for containerization
- **GitHub Actions** for CI/CD
- **DockerHub** for image hosting
- **GitHub Codespaces** for testing (no local Docker required)

---

## 📁 Project Structure

ci-cd-node-app/
├── index.js # Express app
├── package.json # Node dependencies
├── Dockerfile # Docker container definition
└── .github/
└── workflows/
└── main.yml # GitHub Actions workflow


## 🐳 DockerHub Image

DockerHub Repo:  
👉 [`jakkaushareddy/ci-cd-node-app`](https://hub.docker.com/r/jakkaushareddy/ci-cd-node-app)

You can pull and run it locally (or inside Codespaces):

```bash
docker pull jakkaushareddy/ci-cd-node-app
docker run -p 5000:5000 jakkaushareddy/ci-cd-node-app```

📦 How to Reproduce
Clone this repo

Set DOCKER_USERNAME and DOCKER_PASSWORD in GitHub repo secrets

Push to main branch

Watch GitHub Actions build & push the image

Test it using Docker or Codespaces

---
## Built with ❤️ by Ushareddy1310
