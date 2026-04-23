# DevOps Group Project

## This project is a group project in class ET 562. 
## Project members: Wayne Sikes, Georgios Somalakis, and Tea Gonzales

## Project Overview
This project demonstrates a simple DevOps workflow using a small Python Flask application, GitHub for version control, GitHub Actions for CI/CD, and Docker for containerization.

## Tools Used
- Python
- Flask
- GitHub
- GitHub Actions
- Docker

## Workflow
1. Code is stored in a GitHub repository.
2. When code is pushed to the main branch, GitHub Actions automatically starts the CI pipeline.
3. The pipeline installs dependencies.
4. The pipeline runs automated tests.
5. The pipeline builds a Docker image for the application.

## Application Endpoints
- `/` returns: DevOps project running
- `/health` returns: OK

## Project Purpose
The purpose of this project is to demonstrate core DevOps concepts including version control, automation, testing, continuous integration, and containerization.