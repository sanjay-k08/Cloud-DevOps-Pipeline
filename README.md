# Cloud-DevOps-Pipeline

This project demonstrates how to build and deploy a Continuous Integration (CI) pipeline using various tools available in Google Cloud Platform (GCP). It walks through the full lifecycle of a Python Flask application, from writing code and containerizing it, to pushing it through an automated build process using Cloud Build, and finally deploying the built image to a virtual machine instance using Compute Engine.


# Project Objectives

Set up a Git repository using Cloud Source Repositories

Build and test a simple Python Flask application

Create a Dockerfile to containerize the application

Use Cloud Build to build Docker images

Store Docker images in Container Registry

Create build triggers to automate the CI/CD process

Deploy Docker containers using Compute Engine

Test and verify build and deployment pipelines


# Tools & Technologies Used

Google Cloud Source Repositories – Git hosting

Google Cloud Build – Continuous Integration tool

Google Container Registry – Image storage and management

Google Compute Engine – Deploy and test Docker containers

Docker – Containerization

Python & Flask – Web application

Git – Version control

Cloud Shell & Cloud Shell Editor – Development and testing environment


# Project Workflow Overview

1. Create a Git Repo – Using Cloud Source Repositories to manage the source code.

2. Build a Flask App – A simple Flask app with HTML templates is created.

3. Containerize with Docker – Dockerfile is added to define how the app is packaged.

4. Build & Store Image – Use Cloud Build to build Docker image and push it to Container Registry.

5. Create Triggers – Set up Cloud Build triggers to automate builds on Git push.

6. Deploy & Test – Launch a Compute Engine VM and deploy the container directly from Container Registry.


# Directory Structure
    css
    devops-repo/
    ├── Dockerfile
    ├── main.py
    ├── requirements.txt
    ├── templates/
    │   ├── layout.html
    │   └── index.html


# Tasks Breakdown

    Task 1: Create Git repository

    Task 2: Create and test Flask app in Cloud Shell

    Task 3: Define Dockerfile for container build

    Task 4: Use Cloud Build & Container Registry for image creation

    Task 5: Automate build pipeline with triggers

    Task 6: Deploy and test Docker image using Compute Engine


This project serves as a practical introduction to DevOps practices using Google Cloud Platform. It highlights how easily you can automate application builds, image management, and deployments using native GCP tools, enhancing your CI/CD pipeline and reducing manual effort.


