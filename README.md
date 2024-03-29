# Python Monitoring Application with Flask, Docker, and Kubernetes

## Introduction

This project serves as a comprehensive guide for building a monitoring application in Python utilizing Flask and the psutil library. It covers key aspects such as local enviornment setup, containerization with Docker, and orchestration via Kubernetes. Additionally, the project provides detailed instructions on integrating with Amazon ECR to store Docker images and managing Kubernetes deployments and services using Aws Elastic Kubernetes Service and Python scripts.

![image](https://github.com/ayushh1804/Resource-Monitoring-app/assets/88641651/6507606f-3507-481e-b1f0-df333ab58744)


## Table of Contents

1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Getting Started](#getting-started)
    - [Running the Python Application Locally](#running-the-python-application-locally)
    - [Dockerization](#dockerization)
    - [Amazon ECR Integration](#amazon-ecr-integration)
    - [Kubernetes Setup](#kubernetes-setup)
4. [Usage](#usage)



## Features

- Real-time monitoring of system metrics such as CPU and memory usage.
- Containerization of the Python application using Docker.
- Integration with Amazon ECR for storing Docker images.
- Kubernetes setup for managing containerized applications.
- Creation of Kubernetes Deployments and Services using Python scripts.

## Technologies Used

- Python: Programming language used for building the monitoring application.
- Flask: Python web framework used for developing the RESTful API.
- psutil: Python library for retrieving system information and monitoring.
- Docker: Containerization platform for packaging and deploying applications.
- Kubernetes (EKS): Container orchestration tool for managing containerized applications.
- Amazon ECR: Fully-managed Docker container registry provided by AWS.
- Boto3: Python SDK for AWS, used for interacting with Amazon ECR.

![Screenshot 2024-03-29 142206](https://github.com/ayushh1804/Resource-Monitoring-app/assets/88641651/e2739950-7144-4695-a8c8-8a112e2ec9d5)

</br>
</br>

![Screenshot 2024-03-29 171615](https://github.com/ayushh1804/Resource-Monitoring-app/assets/88641651/d10177c6-1ad5-4735-8195-1c1537ab4ad9)


## Getting Started

### Running the Python Application Locally

1. Clone the repository:

```bash
git clone <repository-url>
cd monitoring-application
```

2. Set up Python environment:

```bash
pip install -r requirements.txt
```

3. Run the Python application locally:

```bash
python app.py
```

### Dockerization

1. Build Docker image:

```bash
docker build -t monitoring-app .
```

2. Run Docker container:

```bash
docker run -d -p 5000:5000 monitoring-app
```




Once the Python application is running locally or in a Docker container, access the monitoring dashboard at http://localhost:5000.
Use Kubernetes to manage and scale the application in a production environment.
Explore system metrics and utilize the monitoring application for performance analysis and optimization.

