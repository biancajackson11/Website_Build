Project Overview

This project demonstrates the creation of a simple CI/CD pipeline for a static website using cloud services and automated deployment. The goal is to showcase practical cloud and DevOps skills by building, deploying, and automatically updating a website hosted in the cloud.

The website is stored in a repository on GitHub and deployed to a cloud storage bucket (such as Amazon S3). Using GitHub Actions, any changes pushed to the repository are automatically synchronised with the live website.

Purpose
This project is designed to demonstrate practical skills in:
- Cloud infrastructure
- Continuous Integration / Continuous Deployment (CI/CD)
- Version control with Git
- Automated deployments
- Basic frontend development

Key Features
- Static website built with HTML and CSS
- Website hosted in a cloud storage bucket
- Automated CI/CD pipeline using GitHub Actions
- Automatic deployment when code is pushed to the main branch
- Secure authentication using repository secrets

Architecture
- Website files are stored in a GitHub repository.
- A GitHub Actions workflow monitors the repository.
- When a commit is pushed to the main branch, the workflow runs.
- The workflow uses the AWS CLI to sync the repository files with an S3 bucket.
- The bucket hosts the live version of the website.