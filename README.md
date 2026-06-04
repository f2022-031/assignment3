# Assignment 3: Kubernetes Orchestration & Full DevOps Pipeline

**Student Name:** Fizza Mahmood  
**Roll Number:** F2022-031  

This repository contains a complete 3-tier microservice application orchestrated using Kubernetes on Minikube. The architecture includes an Nginx reverse proxy gateway, a Flask REST API backend, and a MySQL database layer utilizing persistent storage bounds.

---

## 📁 Directory Structure
* `.github/workflows/` - Continuous Integration pipeline workflow for automated DockerHub image pushes.
* `app/` - Local multi-container development application environment (Docker Compose).
* `k8s/` - Production orchestration manifests (Deployments, Services, PVC, ConfigMaps, Secrets).
* `start.sh` - Automated evaluation initialization script.

---

## 🚀 How to Deploy the Application

An automated startup handler script has been provided to spin up the cluster infrastructure, map environment configurations, and verify node health states cleanly.

To run the full deployment pipeline, execute the following command from the project root folder:

```bash
./start.sh
