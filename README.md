[![Hello GitHub Actions](https://github.com/jpxg3v/github-actions-lab/actions/workflows/hello-devops.yml/badge.svg)](https://github.com/jpxg3v/github-actions-lab/actions/workflows/hello-devops.yml)

# GitHub Actions Lab 🚀

This repo serves as a foundational demo of **CI/CD** using GitHub Actions.

## 🛠️ Concept Demonstrated
- **Event Triggers** Configured for `push` , `pull_request` , and manual triggers (`workflow_dispatch`)
- **Jobs & Steps** Logical separation of tasks between environment logging and file verifications
- **Runners:** Utilizing GitHub-hosted `ubuntu-latest` virtual environments. 
- **Dependency Management:** Using the `needs` keyword to ensure jobs run in a specific order.

## 📈 How to view:
Navigate to the **Actions** tab in this repository to see the execution logs and system details for each run.