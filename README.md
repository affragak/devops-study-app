# DevOps Study App

This is a learning-oriented full-stack application for exploring modern DevOps practices. It serves as a foundation for experimenting with development containers, multi-stage Docker builds, GitHub Actions CI/CD pipelines, security scanning, and Python-based web applications.

## 📁 Project Structure

## 🛠️ Development Environment

The development environment is containerized using [Devpod](https://devpod.dev/) and configured with [mise](https://mise.jdx.dev/) and [chezmoi](https://www.chezmoi.io/)

## 🐍 Python Application

The app (both backend & frontend) is written in Python and lives in the /src directory. It uses uv as the fast, modern Python package manager and runner.

## 🐳 Docker Build

The project uses a multi-stage Docker build for small, production-ready images.

## ⚙️ CI/CD with GitHub Actions

The project includes a CI/CD pipeline defined under .github/workflows/. The pipeline automates:

- Linting and formatting checks
- Python Coverage tests
- Docker image build
- Security scan using Trivy
