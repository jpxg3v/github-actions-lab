# GitHub Actions Lab 🚀 [![Hello GitHub Actions](https://github.com/jpxg3v/github-actions-lab/actions/workflows/hello-devops.yml/badge.svg)](https://github.com/jpxg3v/github-actions-lab/actions/workflows/hello-devops.yml)

This repo serves as a foundational demo of **CI/CD** using GitHub Actions, focusing on automation, security, and environment visibility.

## 🛠️ Concepts Demonstrated

* **Event Triggers:** Configured for `push`, `pull_request`, and manual triggers (`workflow_dispatch`).
* **Dependency Management:** Used the `needs` keyword to ensure jobs run in a specific order, demonstrating workflow orchestration.
* **Job Isolation:** Managed separate Ubuntu runners, utilizing `actions/checkout` to handle persistence across isolated virtual environments.
* **Security & Secrets:** Implemented **GitHub Secrets** and verified automatic log masking to protect sensitive credentials (a core DevSecOps practice).
* **Environment Context:** Extracted and utilized GitHub metadata (Actor, Repo, Event type) to create environment-aware automations.
* **Linux System Administration:** Performed system logging and navigated hidden directory structures (`.github/`) using standard CLI tools on `ubuntu-latest`.

## 📈 How to view:

Navigate to the **Actions** tab in this repository to see the execution logs and system details for each run. You can see how GitHub masks secrets and handles job dependencies in the log history.
