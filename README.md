
A Simle Machine Learning Application


[![CircleCI](https://dl.circleci.com/status-badge/img/gh/dayo0009/devops_microservices/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/dayo0009/devops_microservices/tree/main)



# devops_microservices
Building a machine learning with AI


Project Task
The project goal is to operationalize a pre-built SKLearn Machine Learning Microservice Application using Kubernetes (K8s), which is an open-source system for automating deployment, scaling, and management of containerized applications by doing the following

Kubernetes is open source which gives you the freedom to take advantage of on-premises, hybrid, or public cloud infrastructure, letting you effortlessly and seamlessly move workloads to where it matters to you.

Test project code using hadolint

Install softwares using the Make file 

Setup and create a Dockerfile to containerize this application

Build and Deploy the containerized application using Docker and make a prediction

Improve the log statements in the source code for the application

Setup Kubernetes and minikube  to create a Kubernetes cluster

Deploy the containerize app to Kubernetes cluster and make a prediction

Github repository

Use CircleCI as a CICD tool

Technology dependencies used for the deployment, automaton and integration process are below

This dependencies resides in the requirements.txt file but we have name a few below

python 3.7

pip

Flask

pytest

PyLint

Docker

Kubernetes

CircleCI

Setup the Environment

•	Create a virtualenv and activate it

•	Run make install to install the necessary dependencies


Running app.py

1.	Standalone: python app.py

2.	Run in Docker: ./run_docker.sh

3.	Run in Kubernetes: ./run_kubernetes.sh

Kubernetes Steps
•	Register a docker hub account

•	Setup and Configure Docker locally

•	Setup and Configure Kubernetes locally

•	Setup minikube to connect to Kubernetes. This is focusing on running kubectl locally

•	Create Flask app in Container

•	Run via kubectl

•	Upload docker to docker hub


Verify the application is running

Application listens on port 8000
________________________________________


Testing

This project uses pytest


Author

Mustapha Shuaib Temidayo



