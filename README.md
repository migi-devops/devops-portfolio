### 🚀 DevOps Portfolio – Miguel

I build and operate production-style DevOps systems focused on automation, CI/CD, cloud infrastructure, containerization, and Kubernetes.

This portfolio documents the evolution of a modern DevOps platform — from application build automation through cloud deployment and container orchestration.

---

#### ⚙️ DevOps Platform Roadmap

This portfolio follows a real-world engineering progression:

CI/CD → AWS Cloud → Kubernetes → Infrastructure as Code → Configuration Management → Monitoring & Automation

Each project extends the previous one, simulating how production systems evolve over time.

---

#### ✅ Completed Projects

#### 🚨 Build Automation & CI/CD with Jenkins

[![Repo](https://img.shields.io/badge/GitHub-Repo-blue)](https://github.com/migi-devops/java-maven-app)

Designed and implemented a Jenkins-based CI/CD pipeline for a Java application.

Key capabilities:

- Automated Maven builds and packaging
- Automated application versioning
- Docker image creation and tagging
- Docker Hub integration
- Jenkins Shared Library implementation
- GitHub Webhook integration
- Secure credential management
- Automated deployment workflows

#### Key Technologies

- Jenkins
- Maven
- Docker
- GitHub
- Groovy

#### Engineering Experience Gained

- Pipeline troubleshooting and recovery
- Docker build and deployment failures
- Git workflow and branch management
- Version automation
- CI/CD reliability improvements
- Build agent maintenance and cleanup

---

#### ☁️ AWS Services

#### Repository:

[![Repo](https://img.shields.io/badge/GitHub-Repo-blue)](https://github.com/migi-devops/aws-devops-pipeline)

Extended the CI/CD platform into AWS infrastructure.

Implemented and worked with:

- AWS IAM
- EC2
- Amazon ECR
- VPC fundamentals
- Security Groups
- Jenkins deployment to EC2
- Docker image publishing to ECR
- AWS CLI integration

#### Key Technologies

- AWS IAM
- EC2
- Amazon ECR
- VPC
- Security Groups
- AWS CLI
- Jenkins

#### Engineering Experience Gained

- Cloud infrastructure provisioning
- Secure access management
- Container registry operations
- Cloud deployment workflows
- Network and security fundamentals

---

#### 🔥 Current Focus

#### ☸️ Container Orchestration with Kubernetes

Building and managing containerized applications using Kubernetes, progressing from foundational orchestration concepts to multi-service deployments, configuration management, container registry integration, and Helm-based application management.

This chapter extends my previous CI/CD and AWS experience into Kubernetes, focusing on how containerized applications are deployed, configured, connected, and operated within a cluster.

The implementation combines practical deployment exercises with application verification, infrastructure troubleshooting, and Kubernetes resource lifecycle management.

#### Key Technologies

- Kubernetes
- Minikube
- Docker Desktop
- kubectl
- Kubernetes YAML manifests
- ConfigMaps and Secrets
- Kubernetes Services and networking
- AWS Elastic Container Registry (ECR)
- Helm
- Linode Kubernetes Engine (LKE)

---

#### 📂 Kubernetes Projects & Demonstrations

The following projects document my progression through Kubernetes orchestration, from individual application deployments to more advanced container management workflows.

**1. Kubernetes Application Deployment — MongoDB & Mongo Express**

Deployed MongoDB and Mongo Express on a local Kubernetes cluster using declarative YAML configurations.

Key implementations:

- MongoDB Deployment and internal ClusterIP Service
- Mongo Express Deployment and LoadBalancer Service
- Kubernetes Secrets for database credentials
- ConfigMap for application connection configuration
- Internal service discovery and container communication
- Local application access through Minikube service tunnelling
- Pod, Service, and application log verification

**Engineering Experience Gained**

- Kubernetes application deployment and resource management
- Configuration and credential separation
- Cluster recovery and Kubernetes API connectivity troubleshooting
- Resource cleanup without recreating the entire cluster
- LoadBalancer networking behaviour in a local environment
- Application authentication and connectivity verification

Successfully accessed the Mongo Express interface and verified connectivity to the MongoDB database.

---

**2. Kubernetes ConfigMaps & Secrets — Volume Configuration**

Explored Kubernetes application configuration using ConfigMaps, Secrets, and volume-based configuration techniques.

Key concepts:

- Separating configuration from application containers
- Kubernetes ConfigMap and Secret resources
- Volume-based configuration delivery
- Declarative resource management
- Application configuration within Kubernetes

**Engineering Focus**

Understanding how Kubernetes provides configuration and sensitive data to containerized workloads without requiring changes to application images.

---

**3. Deploying Private Container Images — AWS ECR & Kubernetes**

*Practical exercise completed; detailed portfolio documentation to follow.*

Deployed application workloads using container images stored in a private AWS Elastic Container Registry.

Key implementations:

- AWS ECR private container image references
- Kubernetes Docker registry Secrets
- `imagePullSecrets` configuration
- Deployment image-pull troubleshooting
- AWS CLI integration for registry authentication

**Engineering Experience Gained**

- Investigating `ImagePullBackOff` and `ErrImagePull`
- Identifying expired registry authentication tokens
- Refreshing AWS ECR credentials
- Updating Kubernetes image-pull Secrets
- Restarting Deployments and verifying Pod recovery

This exercise reinforced the importance of secure container registry access and operational troubleshooting when deploying private images.

---

#### 🔄 Kubernetes Work in Progress

**Helm & Microservices Application Deployment**

Continuing Kubernetes orchestration exercises involving:

- Helm charts and values configuration
- Multi-service application deployments
- Kubernetes networking and service discovery
- Application configuration management
- Managed Kubernetes environments
- Deployment validation and troubleshooting

Detailed project documentation will be added as the remaining demonstrations are completed and verified.

---

#### ⚙️ Kubernetes Engineering Experience

Across these exercises, I am developing practical experience in:

- Container orchestration and workload management
- Declarative Kubernetes deployments
- Pod lifecycle management
- Internal and external service networking
- Application configuration and Secret management
- Private container registry integration
- Kubernetes API and cluster troubleshooting
- Deployment recovery and operational verification
- Resource lifecycle management
- Kubernetes application packaging with Helm

The focus is on understanding not only how to deploy applications, but also how to investigate failures, restore services, and maintain reliable containerized environments.

---

#### 🎯 Next Kubernetes Milestones

- Complete Helm-based application deployments
- Expand multi-service application orchestration
- Improve Kubernetes deployment reproducibility
- Introduce persistent storage and application health checks
- Strengthen Kubernetes security and access controls
- Explore monitoring and observability
- Integrate Kubernetes deployments into automated CI/CD workflows

Each demonstration will be documented separately with its architecture, business problem, engineering value, implementation workflow, verification evidence, troubleshooting, and future improvements.


---

#### 🧪 Engineering Approach

This portfolio focuses on practical engineering rather than tutorial replication.

Key areas include:

- Troubleshooting production-style failures
- Infrastructure automation
- CI/CD reliability
- Cloud deployment workflows
- Container orchestration
- Operational problem solving

---

Projects include both successful implementations and documented troubleshooting scenarios to demonstrate real-world DevOps practices.

#### 📬 Connect With Me

LinkedIn: https://www.linkedin.com/in/e-miguel
