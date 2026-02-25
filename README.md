# Enterprise CI/CD Automation Platform

## Overview
This project demonstrates an enterprise-grade CI/CD pipeline integrating container build, security scanning, artifact publishing, and Kubernetes deployment.

## Tech Stack
- GitHub Actions
- Docker
- Trivy (Container Security)
- Helm
- Kubernetes (EKS Ready)
- Flask Application

## Pipeline Flow
1. Code commit triggers pipeline
2. Docker image build
3. Vulnerability scanning with Trivy
4. Push to container registry
5. Helm-based Kubernetes deployment

## Security Controls
- Automated container scanning
- No hardcoded credentials
- Secrets stored in GitHub Secrets
- Resource limits enforced in Kubernetes

## Future Enhancements
- EKS integration
- SonarQube code scanning
- Multi-environment promotion
