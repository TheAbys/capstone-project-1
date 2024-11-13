# Capstone project 1 - Complete CI/CD Pipeline with EKS and AWS ECR

Project description:

    Create private AWS ECR Docker repository
    Adjust Jenkinsfile to build and push Docker Image to AWS ECR
    Integrate deploying to K8s cluster in the CI/CD pipeline from AWS ECR private registry
    So the complete CI/CD project we build has the following configuration:
    - CI step: Increment versiona.
    - CI step: Build artifact for Java Maven applicationb.
    - CI step: Build and push Docker image to AWS ECRc.
    - CD step: Deploy new application version to EKS clusterd.
    - CD step: Commit the version update

