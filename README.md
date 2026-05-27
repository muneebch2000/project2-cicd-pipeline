# Project 2 - CI/CD Pipeline with GitHub Actions

## Overview
Automated CI/CD pipeline that tests, builds, and pushes a Docker image to DockerHub on every push to main branch.

## Tech Stack
- Python 3.11
- Flask
- Docker
- GitHub Actions
- DockerHub
- Pytest

## Project Structure
project2-ci-cd-pipeline/
├── app/
│   └── app.py
├── tests/
│   └── test_app.py
├── .github/
│   └── workflows/
│       └── cicd.yml
├── Dockerfile
└── requirements.txt

## Pipeline Flow
Push Code → Run Tests → Build Docker Image → Push to DockerHub

## Features
- Automated testing with Pytest
- Automated Docker image build
- Automated push to DockerHub
- Triggers on every push to main branch

## How to Run Locally
git clone https://github.com/muneebch2000/project2-cicd-pipeline
cd project2-cicd-pipeline
pip install -r requirements.txt
python app/app.py

## Run Tests
pytest tests/

## CI/CD Pipeline
The pipeline automatically:
1. Sets up Python environment
2. Installs dependencies
3. Runs all tests
4. Builds Docker image
5. Pushes to DockerHub

## Skills Demonstrated
- GitHub Actions CI/CD
- Automated testing with Pytest
- Docker image build and push
- DockerHub integration
- DevOps automation