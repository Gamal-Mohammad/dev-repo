# Dev Repo – Kubernetes Manifests

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white)

> Kubernetes Pod and Deployment manifests from the DevOps group labs.

## Overview

Kubernetes lab manifests: an **nginx** Pod in the `test` namespace and an nginx **Deployment** scaled to 10 replicas.

## Tech Stack

- **Kubernetes**
- **Nginx**

## Repository Structure

```text
deployment-myapp.yml
pod.yml
README.md
```

## Getting Started

```bash
git clone https://github.com/Gamal-Mohammad/dev-repo.git
cd dev-repo
```

### Deploy to Kubernetes

| File | Kind | Name |
|---|---|---|
| `deployment-myapp.yml` | Deployment | `nginx-deployment` |
| `pod.yml` | Pod | `lab1` |

```bash
kubectl apply -f deployment-myapp.yml
kubectl apply -f pod.yml
kubectl get pods,svc
```

## Author

**Gamal Mohammad**

[![GitHub](https://img.shields.io/badge/GitHub-Gamal--Mohammad-181717?logo=github)](https://github.com/Gamal-Mohammad)
