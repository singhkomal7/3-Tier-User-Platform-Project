# 3-Tier-User-Platform-Project

## Tech Stack: 
- AWS EKS 
- Docker 
- Kubernetes 
- GitHub Actions 
- SonarQube 
- Trivy 
- Checkov 
- Gitleaks 
- Amazon ECR 
- ALB 
- Route 53 
- ACM

-----

## Accomplished 

- Designed and implemented an end-to-end CI/CD pipeline using GitHub Actions to automate build, security scanning, and deployment to production on every merge to the main branch. 
- Reduced CI/CD pipeline execution time from ~5 minutes to ~2.5 minutes (~50% improvement) by introducing self-hosted runners, eliminating cold-start delays, pre-installing dependencies, and avoiding repeated environment setup across jobs. 
- Improved pipeline efficiency by parallelizing independent stages such as security scans and linting, reducing total execution time by ~30–40% compared to sequential execution. 
- Integrated DevSecOps practices using Gitleaks, Checkov, Trivy, and SonarQube to detect vulnerabilities across source code, infrastructure, Dockerfiles, and Kubernetes manifests before deployment. 
- Leveraged SonarQube analysis to identify code issues early in the development lifecycle, reducing rework effort and improving code maintainability. 
- Built and pushed container images to private registries (Docker Hub and Amazon ECR) using commit-SHA tagging, enabling traceability, version control, and faster rollback during failures. 
- Implemented secure deployment to Amazon EKS using GitHub OIDC-based authentication with IAM roles, eliminating long-lived credentials and enforcing least-privilege access. 
