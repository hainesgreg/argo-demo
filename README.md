# GitOps Proof of Concept

This is a proof-of-concept repo to showcase the benefits of a **true GitOps workflow**, specifically focusing on the capabilities of **Argo CD**.

## 🔍 Topics Covered

- ✅ Automated application reconciliation  
- ✅ Automated image updates with Argo CD Image Updater

## 🛠️ Prerequisites

To replicate this demo in your own environment, you'll need the following:

- 🗂️ Access to a version control system — _this demo uses **GitHub**_
- 📦 A container image registry — _this demo uses **Docker Hub**_
- ☸️ A Kubernetes cluster — _a single-node setup is sufficient; **Minikube** is used here_
- 🚀 Argo CD installed in the cluster — _deployed in its own namespace_
