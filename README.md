# AWS Static Website – DevOps CI/CD Project

## Architecture

GitHub → Jenkins → Amazon S3 → CloudFront

## AWS Services

- Amazon S3
- Amazon CloudFront
- IAM
- EC2

## DevOps Tools

- Git
- GitHub
- Jenkins
- AWS CLI

## CI/CD Flow

1. Developer pushes code to GitHub.
2. GitHub Webhook triggers Jenkins.
3. Jenkins checks out the latest code.
4. Jenkins deploys the website to S3.
5. Jenkins creates a CloudFront cache invalidation.
6. Updated website is available through CloudFront.

## Jenkins Pipeline

The Jenkins pipeline automates deployment from GitHub to S3 and CloudFront.

## Project Status

GitHub → Jenkins → S3 → CloudFront deployment is working successfully
