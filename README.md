# DevOps Study App Repo

This is a learning-oriented repo for exploring modern DevOps practices. It serves as a foundation for experimenting with development containers, multi-stage Docker builds, GitHub Actions CI/CD pipelines, security scanning, and a full-stack Python application.

## 📁 Project Structure

## 🛠️ Development Environment

The development environment is containerized using [Devpod](https://devpod.dev/) and configured with [mise](https://mise.jdx.dev/) and [chezmoi](https://www.chezmoi.io/).

## 🐍 Python Application

The app (both backend & frontend) is written in Python and lives in the /src directory. It uses uv as the fast, modern Python package manager and runner.

## 🐳 Docker Build

The project uses a multi-stage Docker build for small, production-ready images.

## ⚙️ CI/CD with GitHub Actions

The project includes CI/CD pipelines defined under .github/workflows/. The pipelines automate:

- Linting and formatting checks
- Python Test Coverage
- Security scanning with Trivy
- End-to-End Testing in Kubernetes
- Automated versioning and release creation
- Building and pushing docker images
- Automating PRs on release, updating a gitops repo.
