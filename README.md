# DevOps Portfolio Project

This is a DevOps portfolio project demonstrating CI/CD, Docker, Kubernetes, and a Node.js application.

## 🔧 Project Components

- **GitHub Actions** for CI/CD
- **Docker** for containerization
- **Kubernetes** for orchestration
- **Node.js** backend
- **Static HTML** front-end

## 🧑‍💼 My Experience

I have professional experience as a **System Administrator**, where I:
- Managed Windows/Linux servers.
- Administered **Microsoft 365** and **ISTM** tools.
- Configured **Trellix** and **WatchGuard** firewalls.
- Supported **ERP tools like Box.com**.

## 🚀 Steps to Run Locally

1. Clone the repo:
   ```bash
   git clone <your-repo-url>
   cd devops-portfolio
   ```

2. Build and run using Docker:
   ```bash
   docker build -t devops-portfolio-app .
   docker run -p 3000:3000 devops-portfolio-app
   ```

3. Or deploy to Kubernetes:
   ```bash
   kubectl apply -f k8s/deployment.yaml
   kubectl apply -f k8s/service.yaml
   ```

## 🌐 Deployment

This project is designed to be deployed on services like **Render**, **GitHub Pages**, or **any Kubernetes cluster** with Cloudflare DNS and HTTPS.

