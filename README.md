# End-to-End DevOps Implementation on an E-Commerce Project (OpenTelemetry Astronomy Shop)

## 📌 Overview
This project demonstrates a full-scale **DevOps implementation** on an **E-Commerce platform** using the OpenTelemetry Astronomy Shop. The goal is to provide hands-on experience in setting up and managing a real-world **microservices-based** application using modern DevOps practices.

## 🚀 Key Features
- **Infrastructure as Code (IaC)** using Terraform to provision AWS resources.
- **Kubernetes (EKS)** for orchestrating containerized microservices.
- **GitOps with ArgoCD** to automate deployments.
- **Continuous Integration & Continuous Deployment (CI/CD)** using GitHub Actions.
- **Custom Domain Setup** with Route 53 and Ingress controller.
- **Monitoring & Observability** using OpenTelemetry.

## 🛠️ Tech Stack
- **Cloud Provider:** AWS (EC2, IAM, Route 53, VPC, EKS)
- **Infrastructure as Code:** Terraform
- **Containerization:** Docker
- **Orchestration:** Kubernetes
- **GitOps Tool:** ArgoCD
- **CI/CD Pipeline:** GitHub Actions
- **Monitoring & Logging:** OpenTelemetry

## 📑 Project Breakdown
### 1️⃣ Infrastructure Setup on AWS
- Configure IAM roles & security groups.
- Set up EC2 instances and networking.
- Install & configure Terraform for AWS provisioning.
- Provision Kubernetes cluster using Terraform.

### 2️⃣ Kubernetes Deployment
- Write Kubernetes manifest files.
- Deploy microservices using Kubernetes.
- Configure Ingress for traffic management.

### 3️⃣ GitOps Implementation
- Install & configure ArgoCD.
- Deploy applications using ArgoCD for automated updates.

### 4️⃣ CI/CD Automation
- Implement GitHub Actions for automated builds & deployments.
- Integrate ArgoCD with GitHub Actions for seamless CI/CD.

### 5️⃣ Monitoring & Observability
- Set up OpenTelemetry for tracing and monitoring.
- Implement logging and alerting mechanisms.

## 🏗️ Installation & Setup
### Prerequisites:
- AWS Account
- Terraform installed
- Docker & Kubernetes (kubectl) installed
- GitHub account

### Deployment Steps:
1. **Clone the repository:**
   ```bash
   git clone https://github.com/open-telemetry/opentelemetry-demo.git
   cd opentelemetry-demo
   ```
2. **Set up AWS credentials:**
   ```bash
   export AWS_ACCESS_KEY_ID=your_access_key
   export AWS_SECRET_ACCESS_KEY=your_secret_key
   ```
3. **Provision Infrastructure using Terraform:**
   ```bash
   terraform init
   terraform apply -auto-approve
   ```
4. **Deploy application to Kubernetes:**
   ```bash
   kubectl apply -f k8s/
   ```
5. **Install and configure ArgoCD:**
   ```bash
   kubectl apply -n argocd -f argocd-install.yaml
   ```
6. **Set up CI/CD pipelines in GitHub Actions.**

## 🎯 Learning Outcomes
- Hands-on experience with **real-world DevOps workflows**.
- Deep understanding of **Kubernetes deployments & GitOps methodologies**.
- Implementing **cloud infrastructure & security best practices**.
- Building a **scalable, production-ready DevOps solution**.

## 📖 Resources
- [OpenTelemetry Demo](https://github.com/open-telemetry/opentelemetry-demo)
- [Terraform AWS Provider](https://registry.terraform.io/providers/hashicorp/aws/latest/docs)
- [ArgoCD Documentation](https://argo-cd.readthedocs.io/en/stable/)
- [Kubernetes Official Docs](https://kubernetes.io/docs/)

## 🤝 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

## 📜 License
This project is licensed under the MIT License.

---

🚀 **Developed with ❤️ for DevOps Enthusiasts**
