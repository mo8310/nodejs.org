
# Node.js Application Deployment on Kubernetes Cluster

This project outlines the deployment of a Node.js application on a local Kubernetes cluster using ArgoCD for continuous delivery. The build and deployment process is automated with a Jenkins pipeline. 

## Prerequisites

- **VM for Jenkins**
- **Docker** installed on the Jenkins VM
- **VM for Minikube and kubectl**
- **Minikube** installed on the second VM
- **ArgoCD** installed on Minikube
- **Jenkins** installed on the first VM
- **GitHub account**
- **Docker Hub account**

---

## Part 1: Jenkins Setup and Dockerization

### Step 1: Fork the Repository
1. Go to the [Node.js GitHub repository](https://github.com/nodejs/nodejs.org.git).
2. Fork the repository to your GitHub account.

### Step 2: Clone the Repository on Your VM
```bash
git clone https://github.com/mo8310/nodejs.org.git
cd nodejs.org
