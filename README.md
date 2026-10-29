
# Docker CI/CD Pipeline with AWS

A hands-on DevOps project demonstrating Docker image creation and automated build steps using AWS CodeBuild and Amazon Elastic Container Registry (ECR).

## Project Overview

This project explores how Docker images can be built, tagged, and pushed to Amazon ECR using an AWS CodeBuild build specification.

## Technologies Used

- AWS CodeBuild
- Amazon Elastic Container Registry (ECR)
- Docker
- GitHub
- Linux
- YAML

## CI/CD Workflow

1. Store project source code in GitHub.
2. Configure AWS CodeBuild to execute the build specification.
3. Authenticate with Amazon ECR.
4. Build a Docker image.
5. Tag the image for the ECR repository.
6. Push the image to Amazon ECR.

## Project Configuration

The `buildspec.yml` configuration defines the following phases:

- **Pre-build:** Authenticate Docker with Amazon ECR.
- **Build:** Build the Docker image.
- **Post-build:** Tag and push the image to the ECR repository.

## Repository

[View the source code on GitHub](https://github.com/ameeansary-bit/dockerdemo2)

## Learning Outcomes

- Understanding Docker image creation and tagging.
- Working with AWS CodeBuild build specifications.
- Managing Docker images using Amazon ECR.
- Exploring CI/CD workflow concepts and GitHub version control.

## Future Improvements

- Add automated testing.
- Integrate infrastructure provisioning with Terraform.
- Configure HTTPS for an application deployment.
- Extend the pipeline to deploy an application to a hosting environment.

---

**Author:** Ameen Ansary
