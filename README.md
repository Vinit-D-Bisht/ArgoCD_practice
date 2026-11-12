uu# ArgoCD Practice 🚀

This repository contains my hands-on practice and experiments with **Argo CD and GitOps** using Kubernetes Kind clusters.

The goal is to understand GitOps workflows, application deployment, automation, multi-cluster management, monitoring, and other advanced Argo CD features through practical implementations.

## 📂 Repository Structure

| Folder | Description |
|---|---|
| `ui_deployment/` | Deploying applications through the Argo CD Web UI. |
| `cli_deployment/` | Managing and deploying applications using the Argo CD CLI. |
| `declarative_deployment/` | Declarative application deployment using Kubernetes YAML manifests. |
| `app-of-apps-approach/` | Implementing the App of Apps pattern to manage multiple Argo CD applications through a parent application. |
| `Applicationset/` | Exploring ApplicationSets to automate the creation and management of multiple applications. |
| `multi-cluster-management/` | Managing and deploying applications across multiple Kubernetes clusters. |
| `autoimage-updater/` | Exploring Argo CD Image Updater for automating container image updates. |
| `notifications/` | Configuring Argo CD notifications for application events and deployment status. |
| `monitoring/` | Practicing monitoring and observability for Argo CD and deployed applications. |
| `project/` | Working with Argo CD Projects to organize applications and configure access restrictions. |
| `RBAC/` | Implementing Role-Based Access Control (RBAC), user management, and permission policies. |

## 🛠️ Technologies & Tools

- **Kubernetes:** Kind
- **GitOps:** Argo CD
- **Containerization:** Docker
- **Configuration:** YAML
- **Version Control:** Git & GitHub
- **Monitoring:** Prometheus / Grafana (where configured)
- **Automation:** Argo CD Image Updater, ApplicationSets

## 🎯 Learning Objectives

- Understand GitOps principles and workflows.
- Deploy applications using Argo CD UI, CLI, and declarative manifests.
- Implement automated application synchronization.
- Manage multiple applications using App of Apps and ApplicationSets.
- Configure multi-cluster deployments.
- Automate container image updates.
- Configure notifications and monitoring.
- Implement RBAC and access management.
- Understand Argo CD Projects and application permissions.

## 🚀 Lab Environment

All experiments are performed in a local Kubernetes environment using **Kind (Kubernetes in Docker)**.

The repository contains individual folders for different concepts and experiments, with their respective manifests and configurations.

This is a personal learning and practice repository. Configurations and implementations are added and improved as I explore different Argo CD features and GitOps workflows.

d
