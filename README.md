# DevOps Portfolio

A collection of hands-on DevOps projects built during my [TechWorld with Nana DevOps Bootcamp](https://www.techworld-with-nana.com/devops-bootcamp). Each project focuses on a real-world DevOps scenario including CI/CD, build automation, Docker, Jenkins, cloud, infrastructure automation, Kubernetes, and monitoring.

## Projects at a glance

| # | Project | Core topics | Stack |
|---|---------|-------------|-------|
| 1 | [Build Automation & CI/CD with Jenkins](https://github.com/migi-devops/java-maven-app) | CI/CD, Jenkins pipeline, Docker image build, Maven versioning | Jenkins · Docker · Java · Maven · GitHub · Groovy |
| 2 | Coming soon | AWS deployment | AWS · EC2 · Docker · Jenkins |
| 3 | Coming soon | Kubernetes deployment | Kubernetes · Docker · Jenkins |
| 4 | Coming soon | Infrastructure as Code | Terraform · AWS |
| 5 | Coming soon | Configuration Management | Ansible · AWS |
| 6 | Coming soon | Monitoring & Automation | Prometheus · Python · Grafana |

## 1. Build Automation & CI/CD with Jenkins

**Repo:** [java-maven-app](https://github.com/migi-devops/java-maven-app)

Built a Jenkins CI/CD pipeline for a Java Maven application.

- Builds a Java Maven application
- Increments the application version automatically
- Builds a Docker image
- Pushes the image to Docker Hub
- Commits the updated version back to GitHub
- Uses GitHub webhook triggers
- Uses Jenkins credentials securely
- Integrates a Jenkins Shared Library

## Skills covered

| Area | Technologies |
|------|--------------|
| CI/CD | Jenkins, Jenkinsfile, Multibranch Pipeline |
| Containers | Docker, Docker Compose |
| Orchestration | Kubernetes (EKS, LKE), kubectl |
| Infrastructure as Code | Terraform (AWS VPC, EC2, EKS) |
| Configuration Management | Ansible (playbooks, roles, dynamic inventory) |
| Cloud | AWS, Digital Ocean |
| Scripting & Automation | Python, Bash, Groovy |
| Security | Secrets management, RBAC, `.gitignore` for sensitive files |
