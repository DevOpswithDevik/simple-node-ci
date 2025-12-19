# Simple Node.js CI

![Node.js CI Build](https://github.com/DevOpswithDevik/simple-node-ci/actions/workflows/node.js.yml/badge.svg)
![Node Version](https://img.shields.io/badge/node-18.x+-green.svg)

A lightweight Node.js project demonstrating an automated Continuous Integration (CI) pipeline using GitHub Actions.

## 🚀 Features
* **Automated CI:** Automatically triggers a Node.js build on every push to the `main` branch.
* **Workflow Visibility:** Includes status badges to monitor build health at a glance.
* **Minimalist Setup:** Focused purely on demonstrating CI pipeline mechanics for Node.js applications.

## 📁 Project Structure
```text
simple-node-ci/
├── .github/workflows/  # Contains the Node.js CI Build configuration
├── index.js            # Main entry point of the application
└── package.json        # Project metadata and dependency management

🛠️ Getting Started
Clone the repository:

Bash

git clone [https://github.com/DevOpswithDevik/simple-node-ci.git](https://github.com/DevOpswithDevik/simple-node-ci.git)
cd simple-node-ci

Install dependencies: npm install
Run the application: node index.js

⚙️ CI/CD Pipeline

The project uses GitHub Actions to ensure code stability. The workflow performs the following steps:

Environment Setup: Provisions a virtual runner with the specified Node.js version.

Dependency Installation: Runs npm install to prepare the environment.

Build/Verification: Executes any build scripts or tests defined in the workflow.

You can monitor the history of these builds in the Actions tab.

Created by DevOpswithDevik