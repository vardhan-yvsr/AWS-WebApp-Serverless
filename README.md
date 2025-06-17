# AWS-WebApp-Serverless

## Overview
A fully serverless web application leveraging AWS S3, Lambda, API Gateway, DynamoDB, and CloudFront for secure, scalable, and high-performance deployment.

## Architecture
- **Frontend**: Static assets hosted on S3, delivered via CloudFront
- **Backend**: Lambda functions (Python) triggered by API Gateway
- **Database**: DynamoDB for persistent, scalable NoSQL storage

## Features
- Secure HTTPS delivery with CloudFront
- RESTful API endpoints for data operations
- Fully managed, serverless infrastructure

## Deployment Steps
1. Create and configure S3 bucket for static hosting
2. Set up API Gateway with GET/POST endpoints
3. Write Lambda functions (Python) for backend logic
4. Create DynamoDB table for data storage
5. Configure CloudFront for secure, global content delivery

## Live Demo
[CloudFront URL](https://d35fg8fok02d7j.cloudfront.net/)

## Technologies
- AWS S3, Lambda, API Gateway, DynamoDB, CloudFront
- Python, JavaScript, HTML, CSS
