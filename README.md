# Project Name

## Description
Brief description of the project and its purpose.

## Deployment Process

### Deploying to AWS S3
- The static site is deployed to AWS S3 using GitHub Actions.
- A sync process is triggered on each push to the `main` branch.
- The `aws s3 sync` command is used to sync the contents of the repository with the S3 bucket.

### Deploying to EC2 Instance
- After deploying to S3, the workflow SSHes into an EC2 instance to perform additional deployment tasks.
- The SSH action is used to connect to the EC2 instance.
- Once connected, a script is executed on the EC2 instance to pull the latest changes from the repository.

## Prerequisites
List of prerequisites or dependencies required to run the project.

## Getting Started
Instructions on how to set up and run the project locally.

## Usage
Instructions on how to use the project or deploy it to a live system.



