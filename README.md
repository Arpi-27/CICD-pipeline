# CICD-pipeline
# 🚀 CI/CD Pipeline using GitHub Actions

## 📌 Project Overview

This project demonstrates a basic Continuous Integration (CI) pipeline using **GitHub Actions** and a simple **Flask** application. The pipeline automatically installs dependencies and executes unit tests whenever code is pushed to the repository or a pull request is created.

The objective of this project is to showcase how CI/CD automates software development tasks, improves code quality, and ensures reliable deployments.

## 🎯 Objectives

- Build a simple Flask web application.
- Write automated unit tests using Pytest.
- Configure GitHub Actions for Continuous Integration.
- Automatically install project dependencies.
- Run tests on every code push and pull request.
- Demonstrate an industry-standard CI/CD workflow.

## 🛠️ Technologies Used

- Python 3.13
- Flask
- Pytest
- Git
- GitHub
- GitHub Actions
- YAML

## 📂 Project Structure

CICD-pipeline/
│
├── app.py
├── requirements.txt
├── README.md
│
├── tests/
│   └── test_app.py
│
└── .github/
    └── workflows/
        └── ci.yml
```

---

## ⚙️ Workflow

1. Developer writes code.
2. Code is pushed to GitHub.
3. GitHub Actions automatically starts the workflow.
4. Python environment is created.
5. Dependencies are installed.
6. Pytest executes all unit tests.
7. If all tests pass, the workflow is marked successful.
8. The application is ready for deployment.

---

## 🔄 CI Pipeline Flow

```
Developer
      │
      ▼
Git Push
      │
      ▼
GitHub Repository
      │
      ▼
GitHub Actions
      │
      ▼
Install Dependencies
      │
      ▼
Run Pytest
      │
      ▼
Tests Passed ✅
      │
      ▼
Ready for Deployment
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/Arpi-27/CICD-pipeline.git
```

Move into the project directory

```bash
cd CICD-pipeline
```

Create a virtual environment

```bash
python -m venv myvenv
```

Activate the environment

### Windows

```powershell
myvenv\Scripts\activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python app.py
```

Open your browser:

```
http://127.0.0.1:5000
```

---

## 🧪 Running Tests

Execute the following command:

```bash
pytest
```

Expected Output

```
============================
1 passed
============================
```


## ⚡ GitHub Actions Workflow

The workflow performs the following tasks automatically:

- Checks out the repository
- Sets up Python
- Installs required packages
- Executes automated tests
- Reports build status

## 🌟 Benefits

- Automated testing
- Faster development cycle
- Early bug detection
- Improved code quality
- Reduced manual effort
- Reliable software delivery

## 📈 Future Enhancements

- Docker containerization
- Automated deployment to Azure App Service
- Code coverage reports
- Flake8 linting
- Black code formatting
- Security vulnerability scanning
- Multi-environment deployment (Development, Staging, Production)
