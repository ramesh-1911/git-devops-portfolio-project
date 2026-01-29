# Git Repository Management & CI/CD Governance Platform

Enterprise-grade Git repository management system implementing secure branching strategies, protected production workflows, and automated CI pipelines using GitHub Actions.

---

## 📌 Project Overview

This project demonstrates professional DevOps practices for managing source code repositories with:

- Branch protection rules
- Mandatory pull request reviews
- Automated CI pipeline enforcement
- GitFlow branching strategy
- Governance and security best practices

Designed to simulate real-world enterprise Git repository governance.

---

## 🛠 Tech Stack

- Version Control: Git, GitHub
- CI/CD: GitHub Actions
- Language: Python (Demo App)
- Automation: YAML Pipelines
- OS: Linux Runner (GitHub Hosted)
- Documentation: Markdown

---

## 🏗 Architecture Diagram

Developer
   |
   v
Feature Branch
   |
Pull Request
   |
CI Pipeline (GitHub Actions)
   |
Automated Validation
   |
Approval Required
   |
Protected Main Branch


---

## 🚀 Key Features

- GitFlow Branching Strategy (main, develop, feature)
- Protected Production Branch (main)
- Mandatory Pull Request Approval
- CI Pipeline Enforced Before Merge
- Automatic Build Validation
- Admin Bypass Governance Control
- Enterprise Repository Rulesets

---

## 🔐 Branch Protection Rules

Main branch is protected with:

- Required Pull Request Reviews
- Required CI Status Checks
- Up-to-date Branch Requirement
- Force Push Prevention
- Deletion Protection

---

## ⚙ CI/CD Pipeline Workflow

Pipeline automatically triggers on:

- Push to develop branch
- Pull Request to main branch

Pipeline performs:

- Source Code Checkout
- Python Environment Setup
- Application Execution Test

---

## 📸 Project Screenshots

Screenshots proving implementation:

| Feature | Proof |
-------|-------
Branch Protection Rules | screenshots/branch-protection-main.png |
CI Pipeline Success | screenshots/ci-pipeline-success.png |
Pull Request Checks | screenshots/pr-checks.png |
Protected Branch Error | screenshots/protected-branch-error.png |

---

## 📂 Repository Structure



git-devops-portfolio-project/
│
├── .github/workflows/
│ └── ci.yml
│
├── sample-app/
│ └── app.py
│
├── docs/
│ └── branching-strategy.md
│
├── screenshots/
│
└── README.md


---

## 🧠 Learning Outcomes

- Implemented enterprise Git governance
- Automated CI validation pipelines
- Applied DevOps best practices
- Managed secure branch workflows
- Production-level repository configuration

---

## 📈 Future Enhancements

- SonarQube code quality integration
- Deployment pipeline automation
- Slack notification integration
- Docker container build pipeline
- Infrastructure as Code integration

---

## 👨‍💻 Author

Ramesh  
DevOps Engineer  
GitHub: https://github.com/ramesh-1911
